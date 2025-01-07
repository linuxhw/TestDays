OpenMandriva 4.2 - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.2.

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

Total: 2349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E4310              | [68eec2c60e](https://linux-hardware.org/?probe=68eec2c60e) | Jan 04, 2025 |
| HP            | ProBook 6560b               | [c2ae1365c2](https://linux-hardware.org/?probe=c2ae1365c2) | Dec 31, 2024 |
| Panasonic     | CF-W8FWDAJS                 | [b07a63717b](https://linux-hardware.org/?probe=b07a63717b) | Nov 28, 2024 |
| Toshiba       | Satellite L300              | [5f14b73409](https://linux-hardware.org/?probe=5f14b73409) | Nov 27, 2024 |
| Clevo         | W251EFQ/W270EFQ             | [14cef10c67](https://linux-hardware.org/?probe=14cef10c67) | Nov 22, 2024 |
| Pegatron      | Spring Peak                 | [a3687da9ac](https://linux-hardware.org/?probe=a3687da9ac) | Nov 10, 2024 |
| HP            | Compaq Presario CQ71        | [170e0ba845](https://linux-hardware.org/?probe=170e0ba845) | Oct 31, 2024 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [1ad2d26ee7](https://linux-hardware.org/?probe=1ad2d26ee7) | Oct 30, 2024 |
| HP            | ProBook 6475b               | [afad291037](https://linux-hardware.org/?probe=afad291037) | Oct 23, 2024 |
| ASUSTek       | N751JK                      | [00ba90079e](https://linux-hardware.org/?probe=00ba90079e) | Oct 18, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a065d3b6e](https://linux-hardware.org/?probe=2a065d3b6e) | Sep 27, 2024 |
| Lenovo        | ThinkPad T430 2347H2U       | [f708e6c732](https://linux-hardware.org/?probe=f708e6c732) | Sep 23, 2024 |
| Dell          | Latitude E6410              | [8ce3baea7d](https://linux-hardware.org/?probe=8ce3baea7d) | Sep 12, 2024 |
| Samsung       | N100SP                      | [5b740218ab](https://linux-hardware.org/?probe=5b740218ab) | Aug 22, 2024 |
| Acer          | Aspire A315-31              | [6222616358](https://linux-hardware.org/?probe=6222616358) | Aug 11, 2024 |
| Dell          | Studio 1537                 | [a912e97b90](https://linux-hardware.org/?probe=a912e97b90) | Jul 23, 2024 |
| Acer          | Aspire 5738                 | [4118b16aa8](https://linux-hardware.org/?probe=4118b16aa8) | Jul 20, 2024 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [6b11963a37](https://linux-hardware.org/?probe=6b11963a37) | Jul 18, 2024 |
| HP            | Laptop 14-cm0xxx            | [e057c66153](https://linux-hardware.org/?probe=e057c66153) | Jul 15, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [f8379977a9](https://linux-hardware.org/?probe=f8379977a9) | May 27, 2024 |
| Acer          | Aspire F5-571               | [e448ae2f62](https://linux-hardware.org/?probe=e448ae2f62) | May 11, 2024 |
| HP            | EliteBook 840 G2            | [76e6f087bb](https://linux-hardware.org/?probe=76e6f087bb) | May 08, 2024 |
| Fujitsu Si... | LIFEBOOK E8410              | [30a913526e](https://linux-hardware.org/?probe=30a913526e) | May 07, 2024 |
| ASUSTek       | N53SN                       | [4c0db81fd7](https://linux-hardware.org/?probe=4c0db81fd7) | Apr 28, 2024 |
| Acer          | Aspire ES1-533              | [c4059b2efa](https://linux-hardware.org/?probe=c4059b2efa) | Apr 14, 2024 |
| Dell          | Studio XPS 1340             | [cac8add4c8](https://linux-hardware.org/?probe=cac8add4c8) | Apr 13, 2024 |
| Shuttle       | X50V6                       | [c6b8ac2413](https://linux-hardware.org/?probe=c6b8ac2413) | Apr 12, 2024 |
| HP            | 250 G6 Notebook PC          | [bddda9964b](https://linux-hardware.org/?probe=bddda9964b) | Apr 03, 2024 |
| Philco        | 14H                         | [93e4cd1668](https://linux-hardware.org/?probe=93e4cd1668) | Apr 02, 2024 |
| Gateway       | NE56R                       | [4e5c0a6186](https://linux-hardware.org/?probe=4e5c0a6186) | Mar 18, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [cd9270ccb4](https://linux-hardware.org/?probe=cd9270ccb4) | Mar 14, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [8ff31d6bc3](https://linux-hardware.org/?probe=8ff31d6bc3) | Mar 14, 2024 |
| HP            | Pavilion Power Laptop 15... | [67978c3e25](https://linux-hardware.org/?probe=67978c3e25) | Mar 10, 2024 |
| Acer          | Aspire A515-54G             | [4a2773a633](https://linux-hardware.org/?probe=4a2773a633) | Feb 17, 2024 |
| HP            | ProBook 450 G3              | [d367c2a560](https://linux-hardware.org/?probe=d367c2a560) | Feb 11, 2024 |
| Acer          | Aspire 6930G                | [f721e58007](https://linux-hardware.org/?probe=f721e58007) | Feb 10, 2024 |
| HP            | Pavilion dv9500             | [4745fa66f1](https://linux-hardware.org/?probe=4745fa66f1) | Feb 10, 2024 |
| Apple         | MacBookPro7,1               | [b708422791](https://linux-hardware.org/?probe=b708422791) | Feb 09, 2024 |
| Lenovo        | U41-70 80JV                 | [343e04ef36](https://linux-hardware.org/?probe=343e04ef36) | Feb 07, 2024 |
| HP            | 250 G7 Notebook PC          | [9dab8601c1](https://linux-hardware.org/?probe=9dab8601c1) | Jan 29, 2024 |
| Toshiba       | dynabook Satellite B552/... | [9c1f52e62f](https://linux-hardware.org/?probe=9c1f52e62f) | Jan 29, 2024 |
| Acer          | Aspire A315-31              | [22135f150d](https://linux-hardware.org/?probe=22135f150d) | Jan 12, 2024 |
| Acer          | Aspire E5-571               | [a9f2a0569a](https://linux-hardware.org/?probe=a9f2a0569a) | Jan 09, 2024 |
| HP            | ENVY Notebook               | [8a2c65e297](https://linux-hardware.org/?probe=8a2c65e297) | Jan 05, 2024 |
| Toshiba       | dynabook Satellite B552/... | [544ae58a40](https://linux-hardware.org/?probe=544ae58a40) | Dec 27, 2023 |
| ASUSTek       | X550EA                      | [a874ac5799](https://linux-hardware.org/?probe=a874ac5799) | Dec 18, 2023 |
| Dell          | Latitude E6320              | [dbacdcadba](https://linux-hardware.org/?probe=dbacdcadba) | Dec 12, 2023 |
| Acer          | Aspire 7730G                | [c98f96bcc1](https://linux-hardware.org/?probe=c98f96bcc1) | Dec 07, 2023 |
| Apple         | MacBookPro5,5               | [53e38cd006](https://linux-hardware.org/?probe=53e38cd006) | Dec 02, 2023 |
| Lenovo        | Unknown                     | [0324aeaf06](https://linux-hardware.org/?probe=0324aeaf06) | Nov 28, 2023 |
| Dell          | Vostro 15 5501              | [ebb962a4ff](https://linux-hardware.org/?probe=ebb962a4ff) | Nov 21, 2023 |
| Dell          | Latitude E5440              | [467d68239e](https://linux-hardware.org/?probe=467d68239e) | Nov 20, 2023 |
| ASUSTek       | X540YA                      | [ffdc6b121c](https://linux-hardware.org/?probe=ffdc6b121c) | Nov 17, 2023 |
| Samsung       | 370E4K                      | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| Sony          | VGN-FZ21M                   | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Dell          | Inspiron 5547               | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| HP            | Compaq Presario C768        | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| Toshiba       | Satellite L500              | [9c1b258088](https://linux-hardware.org/?probe=9c1b258088) | Sep 30, 2023 |
| HP            | Compaq Presario CQ70        | [8913bbd459](https://linux-hardware.org/?probe=8913bbd459) | Sep 28, 2023 |
| Dell          | Latitude E7440              | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| HP            | Compaq 615                  | [f2f7659e5b](https://linux-hardware.org/?probe=f2f7659e5b) | Sep 15, 2023 |
| Fujitsu       | LIFEBOOK S752               | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [218489cc3f](https://linux-hardware.org/?probe=218489cc3f) | Sep 09, 2023 |
| Dell          | Inspiron 3542               | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Dell          | Inspiron N4050              | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| Dell          | Latitude E5420              | [102bee1da1](https://linux-hardware.org/?probe=102bee1da1) | Aug 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Sony          | VGN-NW2SRF_S                | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| HP            | Pavilion g4                 | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| Acer          | Aspire 5742                 | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| Chuwi         | CoreBook Pro                | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Lenovo        | ThinkPad L460 20FVS01J00    | [96fe0142cd](https://linux-hardware.org/?probe=96fe0142cd) | Jul 23, 2023 |
| Dell          | Inspiron MP061              | [0a26ffe33b](https://linux-hardware.org/?probe=0a26ffe33b) | Jul 15, 2023 |
| Sony          | VPCCW2S8E                   | [4a3af37e51](https://linux-hardware.org/?probe=4a3af37e51) | Jul 05, 2023 |
| HP            | Laptop 15-db0xxx            | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Fujitsu Si... | LIFEBOOK E8420              | [c997fd76cf](https://linux-hardware.org/?probe=c997fd76cf) | Jul 02, 2023 |
| ASUSTek       | M51Vr                       | [16404e70f6](https://linux-hardware.org/?probe=16404e70f6) | Jun 25, 2023 |
| Toshiba       | Satellite Pro L500          | [44e57dc97b](https://linux-hardware.org/?probe=44e57dc97b) | Jun 25, 2023 |
| HP            | Compaq Presario CQ71        | [d5025e2864](https://linux-hardware.org/?probe=d5025e2864) | Jun 18, 2023 |
| Lenovo        | ThinkPad L430 24655Q7       | [7b45c0777e](https://linux-hardware.org/?probe=7b45c0777e) | Jun 08, 2023 |
| Samsung       | R530/R730                   | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| Acer          | Aspire E5-523G              | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| ASUSTek       | M51Vr                       | [27d265c73d](https://linux-hardware.org/?probe=27d265c73d) | Apr 15, 2023 |
| Acer          | Aspire 5733                 | [981bad2be2](https://linux-hardware.org/?probe=981bad2be2) | Apr 14, 2023 |
| HP            | Compaq Presario C700        | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| Acer          | Aspire 5538                 | [3128c45dbc](https://linux-hardware.org/?probe=3128c45dbc) | Apr 09, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| ASUSTek       | K54C                        | [a2a91e2071](https://linux-hardware.org/?probe=a2a91e2071) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [11c94aa91b](https://linux-hardware.org/?probe=11c94aa91b) | Mar 29, 2023 |
| Toshiba       | Satellite P200              | [c55a4d3166](https://linux-hardware.org/?probe=c55a4d3166) | Mar 29, 2023 |
| Dell          | Precision 7720              | [c3ef75d6eb](https://linux-hardware.org/?probe=c3ef75d6eb) | Mar 23, 2023 |
| Acer          | Aspire 4736Z                | [30e77255e4](https://linux-hardware.org/?probe=30e77255e4) | Mar 20, 2023 |
| Acer          | Aspire A315-55G             | [badcc52c19](https://linux-hardware.org/?probe=badcc52c19) | Mar 18, 2023 |
| Toshiba       | Satellite L50-C             | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| HP            | Pavilion dv6500             | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | [c2230a6690](https://linux-hardware.org/?probe=c2230a6690) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AN0070M... | [0d0877faf5](https://linux-hardware.org/?probe=0d0877faf5) | Mar 10, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Chuwi         | LapBook Plus                | [55365bb7ab](https://linux-hardware.org/?probe=55365bb7ab) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| Lenovo        | ThinkPad T520 4242NS9       | [6e2e5c8285](https://linux-hardware.org/?probe=6e2e5c8285) | Feb 22, 2023 |
| Timi          | TM1707                      | [9bc429fbd6](https://linux-hardware.org/?probe=9bc429fbd6) | Feb 22, 2023 |
| HP            | 15                          | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| ASUSTek       | K53SC                       | [df5351b94d](https://linux-hardware.org/?probe=df5351b94d) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| Positivo      | S14BW01                     | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Medion        | E7220                       | [a1b4318b54](https://linux-hardware.org/?probe=a1b4318b54) | Feb 14, 2023 |
| ASUSTek       | X555DG                      | [3f51c3533f](https://linux-hardware.org/?probe=3f51c3533f) | Feb 13, 2023 |
| HP            | ProBook 4530s               | [c081fdc9be](https://linux-hardware.org/?probe=c081fdc9be) | Feb 07, 2023 |
| ASUSTek       | K43SJ                       | [0cff4ad069](https://linux-hardware.org/?probe=0cff4ad069) | Jan 28, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [796df2715d](https://linux-hardware.org/?probe=796df2715d) | Jan 28, 2023 |
| Acer          | Peppy                       | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| ASUSTek       | X51L                        | [b482dc649b](https://linux-hardware.org/?probe=b482dc649b) | Jan 23, 2023 |
| Lenovo        | ThinkPad L510 2873A17       | [13f5fd23e5](https://linux-hardware.org/?probe=13f5fd23e5) | Jan 14, 2023 |
| Samsung       | 270E5G/270E5U               | [0ddeecd2b8](https://linux-hardware.org/?probe=0ddeecd2b8) | Jan 11, 2023 |
| Acer          | Aspire VX5-591G             | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | M51Vr                       | [ffc48a52ea](https://linux-hardware.org/?probe=ffc48a52ea) | Dec 22, 2022 |
| HP            | Presario CQ62               | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| HP            | Compaq 6735s                | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Acer          | Aspire A315-34              | [85794e606c](https://linux-hardware.org/?probe=85794e606c) | Dec 08, 2022 |
| HP            | Compaq Presario CQ60        | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| ASUSTek       | K70IJ                       | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| Dell          | Inspiron 3451               | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| HP            | G72                         | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Sony          | VPCEB1S1R                   | [1e64f5427a](https://linux-hardware.org/?probe=1e64f5427a) | Oct 21, 2022 |
| HP            | ENVY 15                     | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Apple         | MacBookPro13,2              | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| HP            | Notebook                    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Dell          | Inspiron 3451               | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| Toshiba       | Satellite C650D             | [69db41a0b6](https://linux-hardware.org/?probe=69db41a0b6) | Oct 06, 2022 |
| Dell          | Inspiron 3451               | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| Acer          | Aspire V3-471               | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| Dell          | Vostro 3500                 | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| Lenovo        | B50-45 20388                | [d55d9fad24](https://linux-hardware.org/?probe=d55d9fad24) | Sep 17, 2022 |
| Dell          | Inspiron 3451               | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Dell          | Inspiron 3451               | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| ASUSTek       | K53U                        | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Samsung       | RC420/RC520/RC720           | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Acer          | Aspire 5715Z                | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| Packard Be... | EasyNote TK37               | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| HP            | Notebook                    | [975f3e38e3](https://linux-hardware.org/?probe=975f3e38e3) | Aug 15, 2022 |
| Dell          | Latitude E6540              | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Dell          | Latitude E5470              | [9e78351999](https://linux-hardware.org/?probe=9e78351999) | Aug 04, 2022 |
| MSI           | GE62VR 7RF                  | [e5f6f7e14c](https://linux-hardware.org/?probe=e5f6f7e14c) | Aug 03, 2022 |
| ASUSTek       | K50ID                       | [2c1dddeaea](https://linux-hardware.org/?probe=2c1dddeaea) | Jul 29, 2022 |
| Dell          | Inspiron 3451               | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| HP            | Pavilion g6                 | [2f0de52d8e](https://linux-hardware.org/?probe=2f0de52d8e) | Jul 08, 2022 |
| Gateway       | NE56R                       | [69f2805432](https://linux-hardware.org/?probe=69f2805432) | Jul 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X542UA                      | [f5da6492ca](https://linux-hardware.org/?probe=f5da6492ca) | Jul 03, 2022 |
| Dell          | Latitude D630               | [df3001a64d](https://linux-hardware.org/?probe=df3001a64d) | Jul 02, 2022 |
| Notebook      | MIM 2200                    | [85748618b6](https://linux-hardware.org/?probe=85748618b6) | Jul 02, 2022 |
| Dell          | Inspiron 3451               | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Dell          | Latitude E7250              | [790850da0b](https://linux-hardware.org/?probe=790850da0b) | Jun 22, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Dell          | Inspiron 3451               | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| ASUSTek       | N71Vg                       | [6926193d76](https://linux-hardware.org/?probe=6926193d76) | Jun 18, 2022 |
| HP            | Pavilion dv6                | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Sony          | VGN-NW310F                  | [318b17f951](https://linux-hardware.org/?probe=318b17f951) | Jun 17, 2022 |
| HP            | Pavilion g4                 | [193875edcc](https://linux-hardware.org/?probe=193875edcc) | Jun 15, 2022 |
| Acer          | Extensa 5220                | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Dell          | Inspiron 3451               | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| HP            | Laptop 17-bs0xx             | [a4587cc1de](https://linux-hardware.org/?probe=a4587cc1de) | Jun 10, 2022 |
| Dell          | Inspiron 3451               | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [058bd1f6b9](https://linux-hardware.org/?probe=058bd1f6b9) | Jun 04, 2022 |
| Dell          | Inspiron 3451               | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| Medion        | E7220                       | [d4a700af57](https://linux-hardware.org/?probe=d4a700af57) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Dell          | Inspiron 3451               | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Clevo         | W55xEU                      | [c5fd2417f4](https://linux-hardware.org/?probe=c5fd2417f4) | May 25, 2022 |
| HP            | ProBook 450 G1              | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| Dell          | Inspiron 3451               | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Acer          | Aspire 5332                 | [f48da95c17](https://linux-hardware.org/?probe=f48da95c17) | May 21, 2022 |
| Dell          | Inspiron 3451               | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| Toshiba       | Satellite C670D-126         | [9df3447b21](https://linux-hardware.org/?probe=9df3447b21) | May 14, 2022 |
| Packard Be... | EasyNote MH35               | [f3180b0817](https://linux-hardware.org/?probe=f3180b0817) | May 13, 2022 |
| Toshiba       | Satellite C645D             | [53153cb65d](https://linux-hardware.org/?probe=53153cb65d) | May 04, 2022 |
| Acer          | Aspire F5-573               | [f571b0dc6f](https://linux-hardware.org/?probe=f571b0dc6f) | May 02, 2022 |
| ASUSTek       | UX31E                       | [35c8958673](https://linux-hardware.org/?probe=35c8958673) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Samsung       | RC530/RC730                 | [2e44e9228e](https://linux-hardware.org/?probe=2e44e9228e) | Apr 28, 2022 |
| PC Special... | NJ50_70CU                   | [a9b4399cad](https://linux-hardware.org/?probe=a9b4399cad) | Apr 26, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [80943ca395](https://linux-hardware.org/?probe=80943ca395) | Apr 18, 2022 |
| Dell          | Inspiron 15-5578            | [4e70c05231](https://linux-hardware.org/?probe=4e70c05231) | Apr 17, 2022 |
| HP            | Pavilion dv6                | [639a7422d8](https://linux-hardware.org/?probe=639a7422d8) | Apr 16, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [e9a5e187ad](https://linux-hardware.org/?probe=e9a5e187ad) | Apr 15, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| HP            | ProBook 470 G3              | [5c65c7eedd](https://linux-hardware.org/?probe=5c65c7eedd) | Apr 10, 2022 |
| HP            | Pavilion dv6                | [209dbfbea6](https://linux-hardware.org/?probe=209dbfbea6) | Apr 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c5c24ea4c2](https://linux-hardware.org/?probe=c5c24ea4c2) | Apr 06, 2022 |
| Packard Be... | EasyNote TJ71               | [9afad803e0](https://linux-hardware.org/?probe=9afad803e0) | Apr 05, 2022 |
| Sony          | VGN-FZ31M                   | [5e1ef6c19a](https://linux-hardware.org/?probe=5e1ef6c19a) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| HP            | Pavilion 17                 | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| HP            | 355 G2                      | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Acer          | Aspire 4738                 | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| HUAWEI        | MACH-WX9                    | [44d6d432f9](https://linux-hardware.org/?probe=44d6d432f9) | Mar 21, 2022 |
| HP            | ENVY Notebook               | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Dell          | Inspiron 1525               | [83a319f258](https://linux-hardware.org/?probe=83a319f258) | Mar 11, 2022 |
| Fujitsu Si... | AMILO Li3910                | [8762e9c632](https://linux-hardware.org/?probe=8762e9c632) | Mar 10, 2022 |
| ASUSTek       | K53Z                        | [1a3f77be23](https://linux-hardware.org/?probe=1a3f77be23) | Mar 09, 2022 |
| ASUSTek       | UX31E                       | [889c1ad7d2](https://linux-hardware.org/?probe=889c1ad7d2) | Mar 07, 2022 |
| ASUSTek       | X555DG                      | [74e5474a84](https://linux-hardware.org/?probe=74e5474a84) | Mar 05, 2022 |
| Dell          | Inspiron 1545               | [bb9daa5ab1](https://linux-hardware.org/?probe=bb9daa5ab1) | Mar 05, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [18b982d433](https://linux-hardware.org/?probe=18b982d433) | Mar 05, 2022 |
| HP            | Pavilion dv5                | [81371d4535](https://linux-hardware.org/?probe=81371d4535) | Mar 04, 2022 |
| HP            | Pavilion g4                 | [16ba341ccd](https://linux-hardware.org/?probe=16ba341ccd) | Mar 03, 2022 |
| Dell          | Inspiron 1420               | [30424b62be](https://linux-hardware.org/?probe=30424b62be) | Mar 03, 2022 |
| ASUSTek       | K50IJ                       | [fde5cc4a6c](https://linux-hardware.org/?probe=fde5cc4a6c) | Mar 01, 2022 |
| Toshiba       | Satellite C855              | [a757f64435](https://linux-hardware.org/?probe=a757f64435) | Feb 28, 2022 |
| Acer          | Aspire V3-571G              | [40f6802b71](https://linux-hardware.org/?probe=40f6802b71) | Feb 27, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Toshiba       | Satellite C650D             | [99c0e6257f](https://linux-hardware.org/?probe=99c0e6257f) | Feb 20, 2022 |
| Dell          | Studio 1555                 | [0fd5d9a994](https://linux-hardware.org/?probe=0fd5d9a994) | Feb 20, 2022 |
| ASUSTek       | X75A1                       | [232712babb](https://linux-hardware.org/?probe=232712babb) | Feb 19, 2022 |
| ASUSTek       | K50IJ                       | [e8a3ceb5a9](https://linux-hardware.org/?probe=e8a3ceb5a9) | Feb 18, 2022 |
| Acer          | One Z1402                   | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Extensa 2519                | [4da8d63710](https://linux-hardware.org/?probe=4da8d63710) | Feb 13, 2022 |
| Sony          | SVF1521G6EW                 | [365ef21d2a](https://linux-hardware.org/?probe=365ef21d2a) | Feb 13, 2022 |
| Toshiba       | Satellite L350              | [85b90b81ce](https://linux-hardware.org/?probe=85b90b81ce) | Feb 13, 2022 |
| Acer          | Aspire V5-122               | [d516569472](https://linux-hardware.org/?probe=d516569472) | Feb 13, 2022 |
| Acer          | Aspire E1-530               | [21e2a6f70a](https://linux-hardware.org/?probe=21e2a6f70a) | Feb 13, 2022 |
| ASUSTek       | K52F                        | [46e3780be8](https://linux-hardware.org/?probe=46e3780be8) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | [5182b3bbf6](https://linux-hardware.org/?probe=5182b3bbf6) | Feb 10, 2022 |
| ASUSTek       | X555LD                      | [bdda853706](https://linux-hardware.org/?probe=bdda853706) | Feb 09, 2022 |
| Acer          | Aspire 6935                 | [d0dd380298](https://linux-hardware.org/?probe=d0dd380298) | Feb 08, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bf3e4dae03](https://linux-hardware.org/?probe=bf3e4dae03) | Feb 08, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [9aa6cb1e41](https://linux-hardware.org/?probe=9aa6cb1e41) | Feb 08, 2022 |
| Dell          | Latitude E6410              | [6754affc30](https://linux-hardware.org/?probe=6754affc30) | Feb 08, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| Toshiba       | Satellite C855-22N          | [e8a4451a9d](https://linux-hardware.org/?probe=e8a4451a9d) | Feb 06, 2022 |
| Dell          | Inspiron 3520               | [3c1c6e0805](https://linux-hardware.org/?probe=3c1c6e0805) | Feb 06, 2022 |
| Apple         | MacBookPro12,1              | [261fb2f356](https://linux-hardware.org/?probe=261fb2f356) | Feb 06, 2022 |
| Dell          | G3 3779                     | [c9185bcf1f](https://linux-hardware.org/?probe=c9185bcf1f) | Feb 06, 2022 |
| ASUSTek       | X550CA                      | [fb82e73470](https://linux-hardware.org/?probe=fb82e73470) | Feb 06, 2022 |
| Dell          | Inspiron 3451               | [f00c7a8507](https://linux-hardware.org/?probe=f00c7a8507) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| Dell          | Inspiron 3451               | [9c87bc4fca](https://linux-hardware.org/?probe=9c87bc4fca) | Feb 05, 2022 |
| Acer          | Acadia V1.45                | [b18e761c0f](https://linux-hardware.org/?probe=b18e761c0f) | Feb 05, 2022 |
| Acer          | Swift SF314-41              | [61007dacfd](https://linux-hardware.org/?probe=61007dacfd) | Feb 05, 2022 |
| Acer          | Extensa 5620                | [d5048cae9a](https://linux-hardware.org/?probe=d5048cae9a) | Feb 05, 2022 |
| ASUSTek       | K52Dr                       | [fef25611fb](https://linux-hardware.org/?probe=fef25611fb) | Feb 05, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [895bbcb050](https://linux-hardware.org/?probe=895bbcb050) | Feb 05, 2022 |
| HP            | Pavilion dm1                | [4b0fcd3df5](https://linux-hardware.org/?probe=4b0fcd3df5) | Feb 04, 2022 |
| HP            | 355 G2                      | [2a05eb0f1c](https://linux-hardware.org/?probe=2a05eb0f1c) | Feb 04, 2022 |
| Acer          | Aspire 5715Z                | [378fec89b1](https://linux-hardware.org/?probe=378fec89b1) | Feb 04, 2022 |
| Lenovo        | G50-70 20351                | [c31d2c4893](https://linux-hardware.org/?probe=c31d2c4893) | Feb 04, 2022 |
| HP            | ProBook 640 G1              | [5d9fd312b4](https://linux-hardware.org/?probe=5d9fd312b4) | Feb 03, 2022 |
| Clevo         | P150HMx                     | [8f04d16711](https://linux-hardware.org/?probe=8f04d16711) | Feb 03, 2022 |
| Lenovo        | IdeaPad U330p 20267         | [b8645533ae](https://linux-hardware.org/?probe=b8645533ae) | Feb 02, 2022 |
| Dell          | Latitude D630               | [f7a31d8e3e](https://linux-hardware.org/?probe=f7a31d8e3e) | Feb 02, 2022 |
| Lenovo        | ThinkPad W700 27526LG       | [06b01ba136](https://linux-hardware.org/?probe=06b01ba136) | Feb 02, 2022 |
| HP            | 355 G2                      | [96a86baab9](https://linux-hardware.org/?probe=96a86baab9) | Feb 02, 2022 |
| MSI           | VR201                       | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| Lenovo        | ThinkPad T520 4243W4K       | [449f0842a4](https://linux-hardware.org/?probe=449f0842a4) | Feb 01, 2022 |
| Sony          | VGN-FE31H                   | [a7185cc26a](https://linux-hardware.org/?probe=a7185cc26a) | Feb 01, 2022 |
| Toshiba       | Satellite Pro R850          | [8d5f88157a](https://linux-hardware.org/?probe=8d5f88157a) | Feb 01, 2022 |
| HP            | EliteBook 8540p             | [ead4c2c3fb](https://linux-hardware.org/?probe=ead4c2c3fb) | Feb 01, 2022 |
| Lenovo        | V14-ADA 82C6                | [e8c4b3dfce](https://linux-hardware.org/?probe=e8c4b3dfce) | Jan 31, 2022 |
| Teclast       | F15S                        | [f3161d72b0](https://linux-hardware.org/?probe=f3161d72b0) | Jan 30, 2022 |
| HP            | ProBook 6470b               | [86ba660bb5](https://linux-hardware.org/?probe=86ba660bb5) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | [a909d3702b](https://linux-hardware.org/?probe=a909d3702b) | Jan 30, 2022 |
| Toshiba       | Satellite A300              | [b02315f2c0](https://linux-hardware.org/?probe=b02315f2c0) | Jan 30, 2022 |
| Acer          | Aspire V5-571               | [9c1e6c6a9e](https://linux-hardware.org/?probe=9c1e6c6a9e) | Jan 29, 2022 |
| Toshiba       | Satellite A300              | [ddf886b767](https://linux-hardware.org/?probe=ddf886b767) | Jan 29, 2022 |
| Toshiba       | Satellite Pro P200          | [2edecbff69](https://linux-hardware.org/?probe=2edecbff69) | Jan 29, 2022 |
| HP            | Laptop 14-cm0xxx            | [36fa473b25](https://linux-hardware.org/?probe=36fa473b25) | Jan 29, 2022 |
| Acer          | Aspire 8942G                | [97a7a92547](https://linux-hardware.org/?probe=97a7a92547) | Jan 28, 2022 |
| Packard Be... | EasyNote TJ65               | [9770dbdaeb](https://linux-hardware.org/?probe=9770dbdaeb) | Jan 28, 2022 |
| Dell          | Wolf                        | [8fc168eba7](https://linux-hardware.org/?probe=8fc168eba7) | Jan 27, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [e3308423e5](https://linux-hardware.org/?probe=e3308423e5) | Jan 26, 2022 |
| HP            | ProBook 6550b               | [02d7f3125e](https://linux-hardware.org/?probe=02d7f3125e) | Jan 26, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [4df21e66db](https://linux-hardware.org/?probe=4df21e66db) | Jan 25, 2022 |
| HP            | 655                         | [68e37d8274](https://linux-hardware.org/?probe=68e37d8274) | Jan 25, 2022 |
| Dell          | Latitude E5410              | [074ed63eb9](https://linux-hardware.org/?probe=074ed63eb9) | Jan 25, 2022 |
| Lenovo        | V330-15IKB 81AX             | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| Timi          | TM1801                      | [349fdb5215](https://linux-hardware.org/?probe=349fdb5215) | Jan 25, 2022 |
| HP            | Laptop 15-bs2xx             | [0210b11791](https://linux-hardware.org/?probe=0210b11791) | Jan 25, 2022 |
| Dell          | Inspiron 5567               | [e0eb175311](https://linux-hardware.org/?probe=e0eb175311) | Jan 25, 2022 |
| Positivo      | Mobile                      | [9b53719e46](https://linux-hardware.org/?probe=9b53719e46) | Jan 25, 2022 |
| Acer          | V5-131                      | [ac6664dce9](https://linux-hardware.org/?probe=ac6664dce9) | Jan 25, 2022 |
| Acer          | Extensa 2540                | [27a41f2533](https://linux-hardware.org/?probe=27a41f2533) | Jan 24, 2022 |
| Dell          | Inspiron 3451               | [a212372095](https://linux-hardware.org/?probe=a212372095) | Jan 24, 2022 |
| ASUSTek       | P50IJ                       | [154348ae3a](https://linux-hardware.org/?probe=154348ae3a) | Jan 24, 2022 |
| Lenovo        | ThinkPad T520 4242NS9       | [100812fcd9](https://linux-hardware.org/?probe=100812fcd9) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| Acer          | Aspire 7720                 | [20a42368f1](https://linux-hardware.org/?probe=20a42368f1) | Jan 23, 2022 |
| UMAX          | MediaBook 14                | [87cb50f680](https://linux-hardware.org/?probe=87cb50f680) | Jan 23, 2022 |
| HP            | Laptop 17-bs0xx             | [e018d5506c](https://linux-hardware.org/?probe=e018d5506c) | Jan 23, 2022 |
| Acer          | Extensa 4630Z               | [40d8b3d26c](https://linux-hardware.org/?probe=40d8b3d26c) | Jan 23, 2022 |
| Eii           | WSA116                      | [ecff258a89](https://linux-hardware.org/?probe=ecff258a89) | Jan 23, 2022 |
| Dell          | Inspiron 3451               | [cf464f5bce](https://linux-hardware.org/?probe=cf464f5bce) | Jan 22, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [eebb00a00f](https://linux-hardware.org/?probe=eebb00a00f) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| Philco        | 14I                         | [5006ca52e2](https://linux-hardware.org/?probe=5006ca52e2) | Jan 21, 2022 |
| Dell          | Latitude 3540               | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| Sony          | VPCEB18FD                   | [5fbd1a31a6](https://linux-hardware.org/?probe=5fbd1a31a6) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| Dell          | Inspiron 3482               | [f13427c9b0](https://linux-hardware.org/?probe=f13427c9b0) | Jan 21, 2022 |
| Apple         | MacBook6,1                  | [6907df60fb](https://linux-hardware.org/?probe=6907df60fb) | Jan 20, 2022 |
| Dell          | Inspiron 3451               | [e47bd66b78](https://linux-hardware.org/?probe=e47bd66b78) | Jan 20, 2022 |
| Acer          | Aspire F5-572G              | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | [e9bebad8ef](https://linux-hardware.org/?probe=e9bebad8ef) | Jan 19, 2022 |
| MSI           | GF63 Thin 9RCX              | [c00b17efdc](https://linux-hardware.org/?probe=c00b17efdc) | Jan 19, 2022 |
| Dell          | MXG071                      | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| Samsung       | R410P                       | [7837bc7c5f](https://linux-hardware.org/?probe=7837bc7c5f) | Jan 17, 2022 |
| HP            | Laptop 17-ca0xxx            | [e88e9c2f3d](https://linux-hardware.org/?probe=e88e9c2f3d) | Jan 17, 2022 |
| Acer          | Aspire 5740                 | [005887e692](https://linux-hardware.org/?probe=005887e692) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | V14-IGL 82C2                | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [fd321a896a](https://linux-hardware.org/?probe=fd321a896a) | Jan 16, 2022 |
| ASUSTek       | K53U                        | [7e754deb91](https://linux-hardware.org/?probe=7e754deb91) | Jan 16, 2022 |
| Lenovo        | ThinkPad T420 4236LP7       | [92673f1d6e](https://linux-hardware.org/?probe=92673f1d6e) | Jan 16, 2022 |
| Acer          | Aspire S3-391               | [a83705b242](https://linux-hardware.org/?probe=a83705b242) | Jan 16, 2022 |
| Dell          | Inspiron 3451               | [6da7af33f8](https://linux-hardware.org/?probe=6da7af33f8) | Jan 15, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | B50-45 20388                | [ccee69eba1](https://linux-hardware.org/?probe=ccee69eba1) | Jan 14, 2022 |
| Toshiba       | Satellite L45-B             | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| Acer          | Aspire A315-31              | [972630705f](https://linux-hardware.org/?probe=972630705f) | Jan 14, 2022 |
| Apple         | MacBookPro12,1              | [f6b8d075cf](https://linux-hardware.org/?probe=f6b8d075cf) | Jan 13, 2022 |
| Toshiba       | Satellite A300              | [59338f2a1a](https://linux-hardware.org/?probe=59338f2a1a) | Jan 12, 2022 |
| Toshiba       | Satellite C55D-B            | [5f8ab9c9ce](https://linux-hardware.org/?probe=5f8ab9c9ce) | Jan 11, 2022 |
| Samsung       | N100SP                      | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| Sony          | VPCEH1S1E                   | [854163fb58](https://linux-hardware.org/?probe=854163fb58) | Jan 10, 2022 |
| Dell          | Inspiron 3451               | [053236f8c0](https://linux-hardware.org/?probe=053236f8c0) | Jan 09, 2022 |
| System76      | Galago Pro                  | [1295378270](https://linux-hardware.org/?probe=1295378270) | Jan 09, 2022 |
| HP            | G62                         | [aacfc1cff1](https://linux-hardware.org/?probe=aacfc1cff1) | Jan 08, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0c29e5ae78](https://linux-hardware.org/?probe=0c29e5ae78) | Jan 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| Acer          | Aspire 1510                 | [26c825b4a7](https://linux-hardware.org/?probe=26c825b4a7) | Jan 07, 2022 |
| ASUSTek       | All Series                  | [951c8c3ffc](https://linux-hardware.org/?probe=951c8c3ffc) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [53e9ec174a](https://linux-hardware.org/?probe=53e9ec174a) | Jan 06, 2022 |
| Dell          | XPS L521X                   | [204c990a51](https://linux-hardware.org/?probe=204c990a51) | Jan 06, 2022 |
| Toshiba       | Satellite A305              | [c4aed880fb](https://linux-hardware.org/?probe=c4aed880fb) | Jan 05, 2022 |
| Chuwi         | Hero Book                   | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Dell          | Latitude 3301               | [e00b2dbfbc](https://linux-hardware.org/?probe=e00b2dbfbc) | Jan 05, 2022 |
| Dell          | Inspiron 3451               | [b34e6337ae](https://linux-hardware.org/?probe=b34e6337ae) | Jan 05, 2022 |
| ASUSTek       | N752VX                      | [073f2c3d43](https://linux-hardware.org/?probe=073f2c3d43) | Jan 05, 2022 |
| HP            | ProBook 4530s               | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| Lenovo        | IdeaPad Z470                | [b6c0836e89](https://linux-hardware.org/?probe=b6c0836e89) | Jan 04, 2022 |
| HP            | 635                         | [aafd01b4db](https://linux-hardware.org/?probe=aafd01b4db) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001DPB     | [cb0f7db023](https://linux-hardware.org/?probe=cb0f7db023) | Jan 04, 2022 |
| Dell          | Latitude E6540              | [665bf5dae7](https://linux-hardware.org/?probe=665bf5dae7) | Jan 04, 2022 |
| HP            | Pavilion m6                 | [be191c0d05](https://linux-hardware.org/?probe=be191c0d05) | Jan 04, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [95f33224e9](https://linux-hardware.org/?probe=95f33224e9) | Jan 04, 2022 |
| Sony          | VGN-NW2SRF_S                | [e1e99e3e88](https://linux-hardware.org/?probe=e1e99e3e88) | Jan 03, 2022 |
| HP            | Laptop 15-db0xxx            | [b4d1a18243](https://linux-hardware.org/?probe=b4d1a18243) | Jan 02, 2022 |
| Dell          | XPS M1530                   | [edfbd4eb1c](https://linux-hardware.org/?probe=edfbd4eb1c) | Jan 02, 2022 |
| HP            | Notebook                    | [48f175a513](https://linux-hardware.org/?probe=48f175a513) | Jan 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | [393b7857f2](https://linux-hardware.org/?probe=393b7857f2) | Jan 02, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Lenovo        | G50-45 80E3                 | [616c133c6e](https://linux-hardware.org/?probe=616c133c6e) | Jan 01, 2022 |
| eMachines     | E525                        | [192bbb8b30](https://linux-hardware.org/?probe=192bbb8b30) | Jan 01, 2022 |
| Dell          | Latitude E5430 vPro         | [a073f421c1](https://linux-hardware.org/?probe=a073f421c1) | Jan 01, 2022 |
| Acer          | Swift SF314-59              | [820456adab](https://linux-hardware.org/?probe=820456adab) | Dec 31, 2021 |
| Dell          | Latitude E6230              | [45bd8ebfa3](https://linux-hardware.org/?probe=45bd8ebfa3) | Dec 31, 2021 |
| Toshiba       | Satellite C870D-119         | [2731f273f4](https://linux-hardware.org/?probe=2731f273f4) | Dec 30, 2021 |
| Samsung       | R540/SA41/E452              | [5e1fcfa3a5](https://linux-hardware.org/?probe=5e1fcfa3a5) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| Lenovo        | B590 20208                  | [da7dd95049](https://linux-hardware.org/?probe=da7dd95049) | Dec 29, 2021 |
| Sony          | VGN-FZ31Z                   | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| Lenovo        | IdeaPad P500 20210          | [395d599207](https://linux-hardware.org/?probe=395d599207) | Dec 29, 2021 |
| Acer          | Aspire 5733                 | [50ccc07d3e](https://linux-hardware.org/?probe=50ccc07d3e) | Dec 29, 2021 |
| Toshiba       | Satellite L655              | [aad84241ca](https://linux-hardware.org/?probe=aad84241ca) | Dec 29, 2021 |
| Acer          | Aspire ES1-571              | [ae601c56b8](https://linux-hardware.org/?probe=ae601c56b8) | Dec 28, 2021 |
| ASUSTek       | N75SF                       | [6587985fe7](https://linux-hardware.org/?probe=6587985fe7) | Dec 28, 2021 |
| ASUSTek       | UX31E                       | [cd8cc790a0](https://linux-hardware.org/?probe=cd8cc790a0) | Dec 27, 2021 |
| ASUSTek       | X45U                        | [55d2da3313](https://linux-hardware.org/?probe=55d2da3313) | Dec 27, 2021 |
| Sony          | SVT11125CBS                 | [961f242a60](https://linux-hardware.org/?probe=961f242a60) | Dec 27, 2021 |
| HP            | EliteBook 8740w             | [6f583dfeaf](https://linux-hardware.org/?probe=6f583dfeaf) | Dec 27, 2021 |
| HP            | Notebook                    | [d496159ad3](https://linux-hardware.org/?probe=d496159ad3) | Dec 26, 2021 |
| HP            | EliteBook 6930p             | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Dell          | Inspiron 3451               | [d0340265ee](https://linux-hardware.org/?probe=d0340265ee) | Dec 26, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Lenovo        | V145-15AST 81MT             | [24ba3bb7a0](https://linux-hardware.org/?probe=24ba3bb7a0) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| Acer          | Aspire 5742                 | [45a5de08c7](https://linux-hardware.org/?probe=45a5de08c7) | Dec 25, 2021 |
| Acer          | Aspire 5920G                | [f06229224a](https://linux-hardware.org/?probe=f06229224a) | Dec 25, 2021 |
| LEADER        | NH5BT11                     | [763efa7eb2](https://linux-hardware.org/?probe=763efa7eb2) | Dec 25, 2021 |
| HP            | 650                         | [339ab3e2d2](https://linux-hardware.org/?probe=339ab3e2d2) | Dec 25, 2021 |
| Lenovo        | ThinkPad T500 2087A75       | [6a1f2d337c](https://linux-hardware.org/?probe=6a1f2d337c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [840f7b0eff](https://linux-hardware.org/?probe=840f7b0eff) | Dec 25, 2021 |
| Dell          | Inspiron 3451               | [73576a9684](https://linux-hardware.org/?probe=73576a9684) | Dec 24, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [8e6899196e](https://linux-hardware.org/?probe=8e6899196e) | Dec 24, 2021 |
| Dell          | Inspiron N4010              | [bf8476146c](https://linux-hardware.org/?probe=bf8476146c) | Dec 24, 2021 |
| Acer          | Extensa 215-51K             | [eb7ebb463b](https://linux-hardware.org/?probe=eb7ebb463b) | Dec 23, 2021 |
| Toshiba       | Satellite L355              | [63c919a1ed](https://linux-hardware.org/?probe=63c919a1ed) | Dec 23, 2021 |
| HUAWEI        | BOHB-WAX9                   | [2797b5bd37](https://linux-hardware.org/?probe=2797b5bd37) | Dec 23, 2021 |
| Fujitsu       | FMVNA7BEC                   | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Lenovo        | M30-70 20446                | [127f503834](https://linux-hardware.org/?probe=127f503834) | Dec 22, 2021 |
| Dell          | Latitude E6510              | [e637c26490](https://linux-hardware.org/?probe=e637c26490) | Dec 21, 2021 |
| Acer          | Aspire One 522              | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Dell          | Latitude E6430              | [5d9ca1d1db](https://linux-hardware.org/?probe=5d9ca1d1db) | Dec 21, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | [0b0d4dd23f](https://linux-hardware.org/?probe=0b0d4dd23f) | Dec 21, 2021 |
| Acer          | TravelMate P259-MG          | [e589fbcecc](https://linux-hardware.org/?probe=e589fbcecc) | Dec 20, 2021 |
| Dell          | G5 5590                     | [d548c52867](https://linux-hardware.org/?probe=d548c52867) | Dec 20, 2021 |
| eMachines     | Unknown                     | [6b9767faba](https://linux-hardware.org/?probe=6b9767faba) | Dec 20, 2021 |
| Dell          | Latitude E5400              | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | [899ca3371c](https://linux-hardware.org/?probe=899ca3371c) | Dec 20, 2021 |
| Acer          | TP-W701P-53334G1            | [674f2996b5](https://linux-hardware.org/?probe=674f2996b5) | Dec 19, 2021 |
| HP            | Notebook                    | [5aaca3e01e](https://linux-hardware.org/?probe=5aaca3e01e) | Dec 19, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [90575747f7](https://linux-hardware.org/?probe=90575747f7) | Dec 18, 2021 |
| HP            | 250 G8 Notebook PC          | [fda86b8b4a](https://linux-hardware.org/?probe=fda86b8b4a) | Dec 18, 2021 |
| Toshiba       | Satellite C855D             | [daee1ba27b](https://linux-hardware.org/?probe=daee1ba27b) | Dec 18, 2021 |
| Samsung       | 550XDA                      | [6b3fd04b47](https://linux-hardware.org/?probe=6b3fd04b47) | Dec 18, 2021 |
| Dell          | Inspiron 3451               | [bd37d8fdf8](https://linux-hardware.org/?probe=bd37d8fdf8) | Dec 18, 2021 |
| Acer          | Aspire 5733                 | [3854ed74f2](https://linux-hardware.org/?probe=3854ed74f2) | Dec 17, 2021 |
| Sony          | VPCEF3E1E                   | [f26bff938f](https://linux-hardware.org/?probe=f26bff938f) | Dec 17, 2021 |
| Acer          | Aspire ES1-571              | [972c765b35](https://linux-hardware.org/?probe=972c765b35) | Dec 17, 2021 |
| ASUSTek       | K53SJ                       | [1ffcc2cfda](https://linux-hardware.org/?probe=1ffcc2cfda) | Dec 16, 2021 |
| ASUSTek       | X541NA                      | [70801591a7](https://linux-hardware.org/?probe=70801591a7) | Dec 16, 2021 |
| Positivo      | S14BW01                     | [94de31910c](https://linux-hardware.org/?probe=94de31910c) | Dec 16, 2021 |
| Dell          | Inspiron N5010              | [061faf00df](https://linux-hardware.org/?probe=061faf00df) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Acer          | Aspire A315-54K             | [56741904bd](https://linux-hardware.org/?probe=56741904bd) | Dec 13, 2021 |
| ASUSTek       | UL30A                       | [3f3677f6ee](https://linux-hardware.org/?probe=3f3677f6ee) | Dec 13, 2021 |
| Toshiba       | Satellite L750              | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Dell          | Latitude E6430              | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| HP            | Pavilion 15                 | [99645415a4](https://linux-hardware.org/?probe=99645415a4) | Dec 10, 2021 |
| Lenovo        | ThinkPad T410 2537Z7A       | [d6ddba3925](https://linux-hardware.org/?probe=d6ddba3925) | Dec 10, 2021 |
| Sony          | SVE1513B1EW                 | [094d9138e5](https://linux-hardware.org/?probe=094d9138e5) | Dec 10, 2021 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | [e5a940ffdf](https://linux-hardware.org/?probe=e5a940ffdf) | Dec 10, 2021 |
| HP            | 250 G6 Notebook PC          | [3b955f362a](https://linux-hardware.org/?probe=3b955f362a) | Dec 10, 2021 |
| Toshiba       | TE5                         | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| LG Electro... | A410-G.BC49P1               | [5f952dc625](https://linux-hardware.org/?probe=5f952dc625) | Dec 09, 2021 |
| Lenovo        | ThinkPad E550 20DF002YUS    | [1533118145](https://linux-hardware.org/?probe=1533118145) | Dec 09, 2021 |
| eMachines     | D520 V1.04                  | [932e776d87](https://linux-hardware.org/?probe=932e776d87) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [9df7c17faf](https://linux-hardware.org/?probe=9df7c17faf) | Dec 08, 2021 |
| HP            | 620                         | [7612676b9a](https://linux-hardware.org/?probe=7612676b9a) | Dec 08, 2021 |
| HP            | Laptop 15-dw0xxx            | [96f8dadd49](https://linux-hardware.org/?probe=96f8dadd49) | Dec 08, 2021 |
| ASUSTek       | X550CL                      | [319b95b99d](https://linux-hardware.org/?probe=319b95b99d) | Dec 07, 2021 |
| Dell          | Inspiron 7773               | [2f7c3c0c0b](https://linux-hardware.org/?probe=2f7c3c0c0b) | Dec 07, 2021 |
| eMachines     | E525                        | [eb1ee3fb6c](https://linux-hardware.org/?probe=eb1ee3fb6c) | Dec 07, 2021 |
| Chuwi         | LapBook Pro                 | [ad5d162393](https://linux-hardware.org/?probe=ad5d162393) | Dec 06, 2021 |
| Positivo      | J14AL11                     | [2e5fd22945](https://linux-hardware.org/?probe=2e5fd22945) | Dec 06, 2021 |
| Acer          | Aspire E1-421               | [a7c18d534d](https://linux-hardware.org/?probe=a7c18d534d) | Dec 06, 2021 |
| RM            | NOTEBOOK 320                | [6998aef680](https://linux-hardware.org/?probe=6998aef680) | Dec 06, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| HP            | Notebook                    | [d7c2bef552](https://linux-hardware.org/?probe=d7c2bef552) | Dec 05, 2021 |
| Dell          | Latitude E6430              | [eee07229a4](https://linux-hardware.org/?probe=eee07229a4) | Dec 05, 2021 |
| Dell          | Latitude E6410              | [07ca5fc75a](https://linux-hardware.org/?probe=07ca5fc75a) | Dec 05, 2021 |
| ASUSTek       | K84L                        | [dce2044275](https://linux-hardware.org/?probe=dce2044275) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| HP            | Pavilion g7                 | [795980ab4c](https://linux-hardware.org/?probe=795980ab4c) | Dec 04, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [b71a9c285d](https://linux-hardware.org/?probe=b71a9c285d) | Dec 03, 2021 |
| LG Electro... | S460-G.BG31P1               | [bbdfd3b78e](https://linux-hardware.org/?probe=bbdfd3b78e) | Dec 02, 2021 |
| Medion        | Akoya E1317T                | [0d8103d7b7](https://linux-hardware.org/?probe=0d8103d7b7) | Dec 02, 2021 |
| Positivo      | H14BT58                     | [7e692b3a7a](https://linux-hardware.org/?probe=7e692b3a7a) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| MSI           | GE72 2QC                    | [db92825225](https://linux-hardware.org/?probe=db92825225) | Dec 02, 2021 |
| Philco        | 14F                         | [ab69e64295](https://linux-hardware.org/?probe=ab69e64295) | Dec 02, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [f69fadfb4b](https://linux-hardware.org/?probe=f69fadfb4b) | Dec 01, 2021 |
| Dell          | Latitude E6510              | [cef6e43321](https://linux-hardware.org/?probe=cef6e43321) | Dec 01, 2021 |
| Fujitsu Si... | AMILO Li3910                | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| TUXEDO        | Unknown                     | [ca8a5a1ea8](https://linux-hardware.org/?probe=ca8a5a1ea8) | Dec 01, 2021 |
| ASUSTek       | K53SC                       | [c935a13f9f](https://linux-hardware.org/?probe=c935a13f9f) | Nov 29, 2021 |
| Sony          | VPCEB1E9R                   | [28655d3e4d](https://linux-hardware.org/?probe=28655d3e4d) | Nov 29, 2021 |
| Lenovo        | ThinkPad L530 24792T1       | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Toshiba       | Satellite L500              | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| HP            | 14                          | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Apple         | MacBookPro9,1               | [aab55d2e9a](https://linux-hardware.org/?probe=aab55d2e9a) | Nov 28, 2021 |
| Acer          | P4LJ0                       | [0f57f6b606](https://linux-hardware.org/?probe=0f57f6b606) | Nov 27, 2021 |
| Dell          | Vostro 3700                 | [18f091832c](https://linux-hardware.org/?probe=18f091832c) | Nov 27, 2021 |
| Acer          | Ferrari One 200             | [57001d93d1](https://linux-hardware.org/?probe=57001d93d1) | Nov 27, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [1a6e8764f5](https://linux-hardware.org/?probe=1a6e8764f5) | Nov 27, 2021 |
| Acer          | Aspire A315-55G             | [448bb6c3ec](https://linux-hardware.org/?probe=448bb6c3ec) | Nov 26, 2021 |
| Toshiba       | Satellite A300              | [c62dc3b138](https://linux-hardware.org/?probe=c62dc3b138) | Nov 25, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4305ff478f](https://linux-hardware.org/?probe=4305ff478f) | Nov 25, 2021 |
| HP            | Compaq Presario C700        | [b6d30a2918](https://linux-hardware.org/?probe=b6d30a2918) | Nov 25, 2021 |
| HP            | Compaq 15                   | [8aede4cf2d](https://linux-hardware.org/?probe=8aede4cf2d) | Nov 25, 2021 |
| HP            | 245 G6                      | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| ASUSTek       | K50IN                       | [b3baa5bea0](https://linux-hardware.org/?probe=b3baa5bea0) | Nov 24, 2021 |
| HP            | Compaq CQ45                 | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| HP            | OMEN by Laptop              | [54c37833db](https://linux-hardware.org/?probe=54c37833db) | Nov 23, 2021 |
| Acer          | Aspire 5338                 | [db097f4f70](https://linux-hardware.org/?probe=db097f4f70) | Nov 23, 2021 |
| Dell          | Vostro 1510                 | [3eb9def4af](https://linux-hardware.org/?probe=3eb9def4af) | Nov 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ef65932064](https://linux-hardware.org/?probe=ef65932064) | Nov 23, 2021 |
| Lenovo        | B590 20206                  | [42e20a3566](https://linux-hardware.org/?probe=42e20a3566) | Nov 22, 2021 |
| Sony          | SVT13115FGS                 | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| Lenovo        | ThinkPad T430 2347CL1       | [c13939a100](https://linux-hardware.org/?probe=c13939a100) | Nov 22, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [860506d6bd](https://linux-hardware.org/?probe=860506d6bd) | Nov 22, 2021 |
| Acer          | Aspire 5733                 | [a87c6cfa14](https://linux-hardware.org/?probe=a87c6cfa14) | Nov 21, 2021 |
| Dell          | G5 5590                     | [7704b7b3ea](https://linux-hardware.org/?probe=7704b7b3ea) | Nov 21, 2021 |
| Medion        | Akoya P6638                 | [dca71e6592](https://linux-hardware.org/?probe=dca71e6592) | Nov 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [423bdd7d74](https://linux-hardware.org/?probe=423bdd7d74) | Nov 21, 2021 |
| Acer          | Aspire E5-432G              | [d6fe7992f3](https://linux-hardware.org/?probe=d6fe7992f3) | Nov 21, 2021 |
| Acer          | Aspire V5-471P              | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | EliteBook 840 G3            | [1a5ca1d992](https://linux-hardware.org/?probe=1a5ca1d992) | Nov 20, 2021 |
| Dell          | Inspiron 5566               | [c5dc9a3bde](https://linux-hardware.org/?probe=c5dc9a3bde) | Nov 20, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Apple         | MacBookPro5,4               | [ccd5a782d0](https://linux-hardware.org/?probe=ccd5a782d0) | Nov 20, 2021 |
| Acer          | TravelMate B311-31          | [75d144f180](https://linux-hardware.org/?probe=75d144f180) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Lenovo        | ThinkPad T520 4243ED3       | [973921bfad](https://linux-hardware.org/?probe=973921bfad) | Nov 19, 2021 |
| Acer          | Aspire A315-56              | [be19e72980](https://linux-hardware.org/?probe=be19e72980) | Nov 19, 2021 |
| ASUSTek       | K73SD                       | [75b029cf30](https://linux-hardware.org/?probe=75b029cf30) | Nov 19, 2021 |
| Medion        | A17                         | [55d3f6120b](https://linux-hardware.org/?probe=55d3f6120b) | Nov 19, 2021 |
| HP            | Notebook                    | [b93914e090](https://linux-hardware.org/?probe=b93914e090) | Nov 18, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | [1a1f1149c1](https://linux-hardware.org/?probe=1a1f1149c1) | Nov 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [bb94961cc9](https://linux-hardware.org/?probe=bb94961cc9) | Nov 18, 2021 |
| CSL-Comput... | R Evolve C14i               | [7efef38952](https://linux-hardware.org/?probe=7efef38952) | Nov 18, 2021 |
| HP            | Compaq CQ58                 | [9523e1fbb6](https://linux-hardware.org/?probe=9523e1fbb6) | Nov 18, 2021 |
| ASUSTek       | K50IJ                       | [9e28f131eb](https://linux-hardware.org/?probe=9e28f131eb) | Nov 18, 2021 |
| Lenovo        | G475 20080                  | [98bc985284](https://linux-hardware.org/?probe=98bc985284) | Nov 18, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| Acer          | Predator PH315-51           | [77c52e9cd3](https://linux-hardware.org/?probe=77c52e9cd3) | Nov 17, 2021 |
| Dell          | Latitude E5520              | [4cdf5273ab](https://linux-hardware.org/?probe=4cdf5273ab) | Nov 16, 2021 |
| Fujitsu       | LIFEBOOK E754               | [9569f15e49](https://linux-hardware.org/?probe=9569f15e49) | Nov 16, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [5b90bc1ed9](https://linux-hardware.org/?probe=5b90bc1ed9) | Nov 16, 2021 |
| Dell          | Inspiron 1545               | [f5a7f54888](https://linux-hardware.org/?probe=f5a7f54888) | Nov 16, 2021 |
| Lenovo        | B50-10 80QR                 | [cb474c37e6](https://linux-hardware.org/?probe=cb474c37e6) | Nov 15, 2021 |
| ASUSTek       | X751LJ                      | [79030e87e9](https://linux-hardware.org/?probe=79030e87e9) | Nov 15, 2021 |
| Dell          | Inspiron 1525               | [c057cfbdb4](https://linux-hardware.org/?probe=c057cfbdb4) | Nov 15, 2021 |
| Dell          | Latitude E6420              | [71905152a8](https://linux-hardware.org/?probe=71905152a8) | Nov 14, 2021 |
| Acer          | Aspire E1-572G              | [cf6f4d66a4](https://linux-hardware.org/?probe=cf6f4d66a4) | Nov 14, 2021 |
| SLIMBOOK      | PRO                         | [7aafeb8c15](https://linux-hardware.org/?probe=7aafeb8c15) | Nov 14, 2021 |
| HP            | Pavilion dv6                | [5120795ac2](https://linux-hardware.org/?probe=5120795ac2) | Nov 14, 2021 |
| Acer          | Aspire A315-34              | [29d6ad8b6f](https://linux-hardware.org/?probe=29d6ad8b6f) | Nov 14, 2021 |
| Dell          | Latitude E6320              | [2eebab8f3a](https://linux-hardware.org/?probe=2eebab8f3a) | Nov 14, 2021 |
| Medion        | ERAZER X7857 MD60893        | [2f979af179](https://linux-hardware.org/?probe=2f979af179) | Nov 14, 2021 |
| Acer          | Swift SF314-52              | [58ba001f88](https://linux-hardware.org/?probe=58ba001f88) | Nov 14, 2021 |
| HP            | Laptop 14-cm0xxx            | [7df7f1e92d](https://linux-hardware.org/?probe=7df7f1e92d) | Nov 14, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [bf655cd438](https://linux-hardware.org/?probe=bf655cd438) | Nov 13, 2021 |
| Dell          | Inspiron 5379               | [691dab9bbc](https://linux-hardware.org/?probe=691dab9bbc) | Nov 13, 2021 |
| HP            | ProBook 640 G1              | [72d5b9727b](https://linux-hardware.org/?probe=72d5b9727b) | Nov 12, 2021 |
| ASUSTek       | X75VC                       | [39352780e5](https://linux-hardware.org/?probe=39352780e5) | Nov 12, 2021 |
| Lenovo        | ThinkPad T460 MFG_IN_GO     | [91bd573a72](https://linux-hardware.org/?probe=91bd573a72) | Nov 12, 2021 |
| HP            | 2000                        | [8ba69b64fe](https://linux-hardware.org/?probe=8ba69b64fe) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | [0cbad8aae1](https://linux-hardware.org/?probe=0cbad8aae1) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| Samsung       | R530/R730/R540              | [a9360a0208](https://linux-hardware.org/?probe=a9360a0208) | Nov 09, 2021 |
| Acer          | Aspire E5-771               | [dd11733c60](https://linux-hardware.org/?probe=dd11733c60) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [9154e175ad](https://linux-hardware.org/?probe=9154e175ad) | Nov 09, 2021 |
| HP            | Laptop 15-bs0xx             | [1c8aa481f0](https://linux-hardware.org/?probe=1c8aa481f0) | Nov 09, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [fbc9822ad6](https://linux-hardware.org/?probe=fbc9822ad6) | Nov 09, 2021 |
| Acer          | AO725                       | [e39e3a5527](https://linux-hardware.org/?probe=e39e3a5527) | Nov 08, 2021 |
| HP            | EliteBook 8470p             | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| Dell          | Latitude E5470              | [affe63217a](https://linux-hardware.org/?probe=affe63217a) | Nov 07, 2021 |
| Acer          | Nitro AN517-52              | [ccfbf09818](https://linux-hardware.org/?probe=ccfbf09818) | Nov 07, 2021 |
| Lenovo        | ThinkPad T460 20FMS78014    | [415b6db3da](https://linux-hardware.org/?probe=415b6db3da) | Nov 07, 2021 |
| HP            | 15                          | [48da1734b3](https://linux-hardware.org/?probe=48da1734b3) | Nov 06, 2021 |
| Acer          | Aspire 5250                 | [effc5cc35d](https://linux-hardware.org/?probe=effc5cc35d) | Nov 06, 2021 |
| HP            | 255 G1                      | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| SIEMENS       | SIMATIC Field PG M5         | [8ef86a348c](https://linux-hardware.org/?probe=8ef86a348c) | Nov 06, 2021 |
| HP            | ENVY Notebook               | [bd814d20f6](https://linux-hardware.org/?probe=bd814d20f6) | Nov 05, 2021 |
| Lenovo        | V155-15API 81V5             | [b4eb5bdc7f](https://linux-hardware.org/?probe=b4eb5bdc7f) | Nov 05, 2021 |
| Fujitsu       | LIFEBOOK A555/G             | [4312be5851](https://linux-hardware.org/?probe=4312be5851) | Nov 05, 2021 |
| HP            | Pavilion dv4                | [d37c348339](https://linux-hardware.org/?probe=d37c348339) | Nov 04, 2021 |
| HP            | EliteBook 2560p             | [8fc8e01a40](https://linux-hardware.org/?probe=8fc8e01a40) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [33b288d9d0](https://linux-hardware.org/?probe=33b288d9d0) | Nov 01, 2021 |
| ASUSTek       | UX31E                       | [b089d44dc0](https://linux-hardware.org/?probe=b089d44dc0) | Nov 01, 2021 |
| Gateway       | NV42                        | [8f46bc202f](https://linux-hardware.org/?probe=8f46bc202f) | Nov 01, 2021 |
| MSI           | GE70 2QE                    | [36acedb60b](https://linux-hardware.org/?probe=36acedb60b) | Nov 01, 2021 |
| eMachines     | E720                        | [82e0c7193f](https://linux-hardware.org/?probe=82e0c7193f) | Oct 31, 2021 |
| Toshiba       | IS 1412                     | [c0faa178a2](https://linux-hardware.org/?probe=c0faa178a2) | Oct 31, 2021 |
| Dell          | Vostro A860                 | [55832dd912](https://linux-hardware.org/?probe=55832dd912) | Oct 30, 2021 |
| Fujitsu       | LIFEBOOK E746               | [767eb7c6d3](https://linux-hardware.org/?probe=767eb7c6d3) | Oct 30, 2021 |
| Fujitsu       | LIFEBOOK P702               | [4639f065c8](https://linux-hardware.org/?probe=4639f065c8) | Oct 29, 2021 |
| Medion        | WIM2180                     | [a1f9398a77](https://linux-hardware.org/?probe=a1f9398a77) | Oct 29, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [8272a05168](https://linux-hardware.org/?probe=8272a05168) | Oct 29, 2021 |
| Lenovo        | ThinkPad R400 7438T6U       | [8c2d9e608c](https://linux-hardware.org/?probe=8c2d9e608c) | Oct 28, 2021 |
| Dell          | Inspiron 3520               | [60a030aed3](https://linux-hardware.org/?probe=60a030aed3) | Oct 28, 2021 |
| Dell          | Latitude E5530 non-vPro     | [a377d34c0d](https://linux-hardware.org/?probe=a377d34c0d) | Oct 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [51b5e6cb3f](https://linux-hardware.org/?probe=51b5e6cb3f) | Oct 26, 2021 |
| ASUSTek       | UX31E                       | [62ce68edef](https://linux-hardware.org/?probe=62ce68edef) | Oct 26, 2021 |
| HP            | Laptop 15s-du3xxx           | [6f87ece998](https://linux-hardware.org/?probe=6f87ece998) | Oct 26, 2021 |
| HP            | Laptop 14-bs0xx             | [c25df06e57](https://linux-hardware.org/?probe=c25df06e57) | Oct 26, 2021 |
| Lenovo        | ThinkPad W520 42844DG       | [90895aab86](https://linux-hardware.org/?probe=90895aab86) | Oct 25, 2021 |
| Lenovo        | ThinkPad P70 20ERS00500     | [6988796caf](https://linux-hardware.org/?probe=6988796caf) | Oct 25, 2021 |
| Dell          | Inspiron 3542               | [102ed51abd](https://linux-hardware.org/?probe=102ed51abd) | Oct 25, 2021 |
| Dell          | Vostro 1400                 | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Lenovo        | V145-15AST 81MT             | [0036c99447](https://linux-hardware.org/?probe=0036c99447) | Oct 24, 2021 |
| ASUSTek       | UX31E                       | [3783b25b2a](https://linux-hardware.org/?probe=3783b25b2a) | Oct 24, 2021 |
| Samsung       | R530/R730/R540              | [cae9eeef46](https://linux-hardware.org/?probe=cae9eeef46) | Oct 24, 2021 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [3b7bf6fdeb](https://linux-hardware.org/?probe=3b7bf6fdeb) | Oct 24, 2021 |
| Sony          | VGN-FW270J                  | [dbfd29f616](https://linux-hardware.org/?probe=dbfd29f616) | Oct 24, 2021 |
| HP            | G70                         | [9ed49ae55e](https://linux-hardware.org/?probe=9ed49ae55e) | Oct 23, 2021 |
| HP            | ProBook 6460b               | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| Acer          | Aspire E5-575T              | [a03fc24624](https://linux-hardware.org/?probe=a03fc24624) | Oct 23, 2021 |
| Lenovo        | ThinkPad X121e 3051RT2      | [29fef13a3a](https://linux-hardware.org/?probe=29fef13a3a) | Oct 22, 2021 |
| Positivo      | S14BW01                     | [6b146fc86e](https://linux-hardware.org/?probe=6b146fc86e) | Oct 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [19f7ba4a63](https://linux-hardware.org/?probe=19f7ba4a63) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [703d0f2090](https://linux-hardware.org/?probe=703d0f2090) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Dell          | Latitude E6500              | [84217e1781](https://linux-hardware.org/?probe=84217e1781) | Oct 21, 2021 |
| ASUSTek       | M51Vr                       | [843c7a8519](https://linux-hardware.org/?probe=843c7a8519) | Oct 20, 2021 |
| Acer          | Aspire E5-573               | [2d9c3e1922](https://linux-hardware.org/?probe=2d9c3e1922) | Oct 20, 2021 |
| Lenovo        | ThinkPad E14 20RA0016SP     | [1221048e12](https://linux-hardware.org/?probe=1221048e12) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| Acer          | Aspire V3-772G              | [10e7ffc71d](https://linux-hardware.org/?probe=10e7ffc71d) | Oct 19, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [8735c1e718](https://linux-hardware.org/?probe=8735c1e718) | Oct 19, 2021 |
| Dell          | Latitude D630               | [a21cbd39f7](https://linux-hardware.org/?probe=a21cbd39f7) | Oct 19, 2021 |
| Toshiba       | Satellite A505              | [a955d2e293](https://linux-hardware.org/?probe=a955d2e293) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [235e8c9537](https://linux-hardware.org/?probe=235e8c9537) | Oct 18, 2021 |
| Toshiba       | Satellite Pro C50-A-1C8     | [bb444038cf](https://linux-hardware.org/?probe=bb444038cf) | Oct 18, 2021 |
| ASUSTek       | K52JT                       | [edec5d042a](https://linux-hardware.org/?probe=edec5d042a) | Oct 17, 2021 |
| Acer          | Aspire A315-42G             | [6134bf279a](https://linux-hardware.org/?probe=6134bf279a) | Oct 17, 2021 |
| eMachines     | E520 V1.06                  | [2d22d1c64a](https://linux-hardware.org/?probe=2d22d1c64a) | Oct 17, 2021 |
| Jumper        | Ezbook X3                   | [fe510b821a](https://linux-hardware.org/?probe=fe510b821a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [10a67c9e23](https://linux-hardware.org/?probe=10a67c9e23) | Oct 16, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [60456eb59b](https://linux-hardware.org/?probe=60456eb59b) | Oct 16, 2021 |
| Apple         | MacBookPro11,3              | [619a3816eb](https://linux-hardware.org/?probe=619a3816eb) | Oct 16, 2021 |
| Acer          | Aspire E5-571               | [b967df63ce](https://linux-hardware.org/?probe=b967df63ce) | Oct 15, 2021 |
| Lenovo        | G700 20251                  | [a1e8a47b13](https://linux-hardware.org/?probe=a1e8a47b13) | Oct 15, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| Positivo      | S14SL01                     | [5d92191da4](https://linux-hardware.org/?probe=5d92191da4) | Oct 15, 2021 |
| ASUSTek       | PU551JD                     | [1e77763341](https://linux-hardware.org/?probe=1e77763341) | Oct 15, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [92a4ba4aa3](https://linux-hardware.org/?probe=92a4ba4aa3) | Oct 15, 2021 |
| Acer          | Aspire A315-56              | [f30ecd32c2](https://linux-hardware.org/?probe=f30ecd32c2) | Oct 15, 2021 |
| HP            | EliteBook 8470p             | [3c24201057](https://linux-hardware.org/?probe=3c24201057) | Oct 15, 2021 |
| ASUSTek       | UX31E                       | [a20549b1ee](https://linux-hardware.org/?probe=a20549b1ee) | Oct 14, 2021 |
| HP            | ProBook 650 G1              | [15e5c85b3b](https://linux-hardware.org/?probe=15e5c85b3b) | Oct 14, 2021 |
| NEC Comput... | PC-LL550VG6R                | [5879ce1d61](https://linux-hardware.org/?probe=5879ce1d61) | Oct 13, 2021 |
| ASUSTek       | S551LN                      | [fdeccae58a](https://linux-hardware.org/?probe=fdeccae58a) | Oct 13, 2021 |
| HP            | EliteBook 8570w             | [b703149715](https://linux-hardware.org/?probe=b703149715) | Oct 13, 2021 |
| ASUSTek       | X555LAB                     | [858657e291](https://linux-hardware.org/?probe=858657e291) | Oct 12, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [7b592089b2](https://linux-hardware.org/?probe=7b592089b2) | Oct 12, 2021 |
| ASUSTek       | UX31E                       | [33cb7873b3](https://linux-hardware.org/?probe=33cb7873b3) | Oct 11, 2021 |
| Sony          | VPCEA3S1E                   | [dec993fe87](https://linux-hardware.org/?probe=dec993fe87) | Oct 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ea290c0520](https://linux-hardware.org/?probe=ea290c0520) | Oct 11, 2021 |
| HP            | Notebook                    | [41dd55250d](https://linux-hardware.org/?probe=41dd55250d) | Oct 11, 2021 |
| Dell          | Inspiron 3521               | [da35783974](https://linux-hardware.org/?probe=da35783974) | Oct 11, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ff57de0ffa](https://linux-hardware.org/?probe=ff57de0ffa) | Oct 10, 2021 |
| Lenovo        | ThinkPad Edge 031928G       | [04895faef4](https://linux-hardware.org/?probe=04895faef4) | Oct 10, 2021 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [217f56ead2](https://linux-hardware.org/?probe=217f56ead2) | Oct 10, 2021 |
| ARIMA         | W651UI                      | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| Alienware     | M11x R2                     | [3489d7096d](https://linux-hardware.org/?probe=3489d7096d) | Oct 10, 2021 |
| Lenovo        | G50-45 80E3                 | [d520f23d4e](https://linux-hardware.org/?probe=d520f23d4e) | Oct 10, 2021 |
| Acer          | Aspire E5-571G              | [95a7cc7345](https://linux-hardware.org/?probe=95a7cc7345) | Oct 09, 2021 |
| Lenovo        | G700 20251                  | [2a59a10bb7](https://linux-hardware.org/?probe=2a59a10bb7) | Oct 08, 2021 |
| Lenovo        | Z50-70 20354                | [22e290b148](https://linux-hardware.org/?probe=22e290b148) | Oct 08, 2021 |
| Dell          | Latitude E6520              | [b42465ddf3](https://linux-hardware.org/?probe=b42465ddf3) | Oct 08, 2021 |
| Acer          | Aspire S3-391               | [12f6dc750d](https://linux-hardware.org/?probe=12f6dc750d) | Oct 07, 2021 |
| Lenovo        | ThinkPad T520 4242A21       | [3888aa6ed7](https://linux-hardware.org/?probe=3888aa6ed7) | Oct 07, 2021 |
| Acer          | Aspire ES1-533              | [a1a36f11f4](https://linux-hardware.org/?probe=a1a36f11f4) | Oct 07, 2021 |
| Sony          | VPCS111FM                   | [0fb69d4d18](https://linux-hardware.org/?probe=0fb69d4d18) | Oct 06, 2021 |
| ASUSTek       | UX31E                       | [3d656a59f6](https://linux-hardware.org/?probe=3d656a59f6) | Oct 06, 2021 |
| Toshiba       | Satellite P755              | [d7893b2025](https://linux-hardware.org/?probe=d7893b2025) | Oct 06, 2021 |
| Dell          | Latitude E6420              | [3518feb297](https://linux-hardware.org/?probe=3518feb297) | Oct 06, 2021 |
| HP            | Pavilion dm4                | [4e6e58bbba](https://linux-hardware.org/?probe=4e6e58bbba) | Oct 06, 2021 |
| Acer          | Aspire ES1-520              | [b9968db322](https://linux-hardware.org/?probe=b9968db322) | Oct 05, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c9b430fff1](https://linux-hardware.org/?probe=c9b430fff1) | Oct 05, 2021 |
| Lenovo        | ThinkPad T530 2429MF7       | [64ac10f6b5](https://linux-hardware.org/?probe=64ac10f6b5) | Oct 05, 2021 |
| ASUSTek       | F3Sr                        | [546f7c0dbd](https://linux-hardware.org/?probe=546f7c0dbd) | Oct 05, 2021 |
| ASUSTek       | UX31E                       | [b24ee374eb](https://linux-hardware.org/?probe=b24ee374eb) | Oct 04, 2021 |
| ASUSTek       | X751MA                      | [7a7899c096](https://linux-hardware.org/?probe=7a7899c096) | Oct 04, 2021 |
| Timi          | Mi NoteBook Horizon Edit... | [f88ea3973e](https://linux-hardware.org/?probe=f88ea3973e) | Oct 04, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [b59eb435a5](https://linux-hardware.org/?probe=b59eb435a5) | Oct 04, 2021 |
| Dell          | Studio XPS 1340             | [e7799cbc49](https://linux-hardware.org/?probe=e7799cbc49) | Oct 04, 2021 |
| Medion        | E7417 MD99269               | [b8ed23fd23](https://linux-hardware.org/?probe=b8ed23fd23) | Oct 03, 2021 |
| HP            | EliteBook Revolve 810 G3    | [d3d205d3b0](https://linux-hardware.org/?probe=d3d205d3b0) | Oct 03, 2021 |
| HP            | 15                          | [ef614cc235](https://linux-hardware.org/?probe=ef614cc235) | Oct 03, 2021 |
| Sony          | VPCEH10EB                   | [c75fe465b1](https://linux-hardware.org/?probe=c75fe465b1) | Oct 03, 2021 |
| Dell          | Inspiron 15-3567            | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Apple         | MacBookPro12,1              | [18e31a37c1](https://linux-hardware.org/?probe=18e31a37c1) | Oct 02, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [627f5a64cf](https://linux-hardware.org/?probe=627f5a64cf) | Oct 02, 2021 |
| Lenovo        | Unknown                     | [56e7fa3c9b](https://linux-hardware.org/?probe=56e7fa3c9b) | Oct 02, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [368275ba77](https://linux-hardware.org/?probe=368275ba77) | Oct 02, 2021 |
| ASUSTek       | UX31E                       | [634508203a](https://linux-hardware.org/?probe=634508203a) | Oct 01, 2021 |
| Apple         | MacBook7,1                  | [fc165a022b](https://linux-hardware.org/?probe=fc165a022b) | Oct 01, 2021 |
| Dell          | Latitude E6500              | [2994c9526e](https://linux-hardware.org/?probe=2994c9526e) | Sep 30, 2021 |
| ASUSTek       | UX31E                       | [ae53a22db8](https://linux-hardware.org/?probe=ae53a22db8) | Sep 30, 2021 |
| MSI           | GE72 2QD                    | [772096be73](https://linux-hardware.org/?probe=772096be73) | Sep 29, 2021 |
| ASUSTek       | X751SA                      | [9b5b69452d](https://linux-hardware.org/?probe=9b5b69452d) | Sep 29, 2021 |
| Dell          | Latitude 5491               | [197b1a5c35](https://linux-hardware.org/?probe=197b1a5c35) | Sep 29, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| Sony          | VPCF23S1E                   | [bca5866f5e](https://linux-hardware.org/?probe=bca5866f5e) | Sep 28, 2021 |
| ASUSTek       | UX31E                       | [1ce98669cc](https://linux-hardware.org/?probe=1ce98669cc) | Sep 27, 2021 |
| Dell          | Inspiron 3521               | [3e85c5d96f](https://linux-hardware.org/?probe=3e85c5d96f) | Sep 27, 2021 |
| Acer          | Aspire 8930                 | [f6633135a3](https://linux-hardware.org/?probe=f6633135a3) | Sep 27, 2021 |
| ASUSTek       | UX31E                       | [65594b31db](https://linux-hardware.org/?probe=65594b31db) | Sep 27, 2021 |
| Acer          | Aspire 7250                 | [4550910b55](https://linux-hardware.org/?probe=4550910b55) | Sep 27, 2021 |
| Acer          | Aspire V5-552G              | [17710ebd6d](https://linux-hardware.org/?probe=17710ebd6d) | Sep 26, 2021 |
| ASUSTek       | UX31E                       | [61a05f66ef](https://linux-hardware.org/?probe=61a05f66ef) | Sep 24, 2021 |
| ASUSTek       | K53SD                       | [8bd68017a2](https://linux-hardware.org/?probe=8bd68017a2) | Sep 24, 2021 |
| ASUSTek       | A6Je                        | [4192e41344](https://linux-hardware.org/?probe=4192e41344) | Sep 24, 2021 |
| ASUSTek       | X555DG                      | [c0331b0d0b](https://linux-hardware.org/?probe=c0331b0d0b) | Sep 23, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [0064d74421](https://linux-hardware.org/?probe=0064d74421) | Sep 23, 2021 |
| HP            | EliteBook 8530p             | [8002401481](https://linux-hardware.org/?probe=8002401481) | Sep 23, 2021 |
| Dell          | Latitude E5510              | [5b02accd5b](https://linux-hardware.org/?probe=5b02accd5b) | Sep 23, 2021 |
| Packard Be... | EasyNote LM85               | [d4bcc9a744](https://linux-hardware.org/?probe=d4bcc9a744) | Sep 23, 2021 |
| Lenovo        | ThinkPad T61 7661BM5        | [574dd5f703](https://linux-hardware.org/?probe=574dd5f703) | Sep 22, 2021 |
| Dell          | Inspiron N5110              | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Samsung       | 550XCJ/550XCR               | [e886fe36b0](https://linux-hardware.org/?probe=e886fe36b0) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Samsung       | RV415                       | [9fbf78d306](https://linux-hardware.org/?probe=9fbf78d306) | Sep 21, 2021 |
| Dell          | Inspiron 3793               | [7334b969a1](https://linux-hardware.org/?probe=7334b969a1) | Sep 21, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [3c54753690](https://linux-hardware.org/?probe=3c54753690) | Sep 20, 2021 |
| ASUSTek       | UX31E                       | [02b242903b](https://linux-hardware.org/?probe=02b242903b) | Sep 20, 2021 |
| Acer          | Aspire A515-51              | [aa89265aaf](https://linux-hardware.org/?probe=aa89265aaf) | Sep 20, 2021 |
| HP            | Compaq 2510p                | [1f3c069a21](https://linux-hardware.org/?probe=1f3c069a21) | Sep 20, 2021 |
| HP            | Pavilion dm4                | [e860b20b4d](https://linux-hardware.org/?probe=e860b20b4d) | Sep 19, 2021 |
| HP            | EliteBook 2570p             | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| ASUSTek       | K73SV                       | [3a380949ba](https://linux-hardware.org/?probe=3a380949ba) | Sep 18, 2021 |
| ASUSTek       | UX31E                       | [6d3c0cb595](https://linux-hardware.org/?probe=6d3c0cb595) | Sep 18, 2021 |
| HP            | EliteBook 8540p             | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |
| Acer          | Aspire E5-551               | [223b8d9942](https://linux-hardware.org/?probe=223b8d9942) | Sep 18, 2021 |
| Fujitsu       | LIFEBOOK A555               | [b13a831913](https://linux-hardware.org/?probe=b13a831913) | Sep 17, 2021 |
| ASUSTek       | UX31E                       | [4771fb2aab](https://linux-hardware.org/?probe=4771fb2aab) | Sep 17, 2021 |
| Dell          | Latitude 7280               | [3a3823b149](https://linux-hardware.org/?probe=3a3823b149) | Sep 17, 2021 |
| Lenovo        | G500 20236                  | [b740654686](https://linux-hardware.org/?probe=b740654686) | Sep 17, 2021 |
| ASUSTek       | X550CA                      | [4340321f04](https://linux-hardware.org/?probe=4340321f04) | Sep 17, 2021 |
| Lenovo        | ThinkPad T400 2767C44       | [980d970cf5](https://linux-hardware.org/?probe=980d970cf5) | Sep 17, 2021 |
| ASUSTek       | K53E                        | [2e6fad8350](https://linux-hardware.org/?probe=2e6fad8350) | Sep 16, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ecb9711c99](https://linux-hardware.org/?probe=ecb9711c99) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | [6c54ed5e3e](https://linux-hardware.org/?probe=6c54ed5e3e) | Sep 16, 2021 |
| ASUSTek       | UX31E                       | [aa60d02a7b](https://linux-hardware.org/?probe=aa60d02a7b) | Sep 15, 2021 |
| Acer          | TravelMate 4400             | [8b304af834](https://linux-hardware.org/?probe=8b304af834) | Sep 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [de6c566c7f](https://linux-hardware.org/?probe=de6c566c7f) | Sep 15, 2021 |
| HP            | Notebook                    | [c3bcf38e50](https://linux-hardware.org/?probe=c3bcf38e50) | Sep 15, 2021 |
| Sony          | VGN-FZ21M                   | [f68a8cedaa](https://linux-hardware.org/?probe=f68a8cedaa) | Sep 15, 2021 |
| Acer          | Aspire 5250                 | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| Lenovo        | B570 HuronRiver Platform    | [0ddea0a24e](https://linux-hardware.org/?probe=0ddea0a24e) | Sep 14, 2021 |
| Toshiba       | Satellite P870              | [32a822de07](https://linux-hardware.org/?probe=32a822de07) | Sep 14, 2021 |
| Dell          | Inspiron 15-7569            | [6ccc3403f8](https://linux-hardware.org/?probe=6ccc3403f8) | Sep 14, 2021 |
| Acer          | Aspire ES1-520              | [4b4f263238](https://linux-hardware.org/?probe=4b4f263238) | Sep 14, 2021 |
| Lenovo        | ThinkPad T61 7659AB7        | [3c213b818b](https://linux-hardware.org/?probe=3c213b818b) | Sep 14, 2021 |
| ASUSTek       | UX31E                       | [e1b27b035e](https://linux-hardware.org/?probe=e1b27b035e) | Sep 13, 2021 |
| Positivo      | SW6H                        | [2653f4ff4b](https://linux-hardware.org/?probe=2653f4ff4b) | Sep 12, 2021 |
| ASUSTek       | G750JX                      | [185445c775](https://linux-hardware.org/?probe=185445c775) | Sep 12, 2021 |
| Toshiba       | Satellite P845              | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| Apple         | MacBookPro8,2               | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | TravelMate 5720             | [4de6ed548e](https://linux-hardware.org/?probe=4de6ed548e) | Sep 12, 2021 |
| Lenovo        | ThinkPad P50 20EQS3BT2E     | [cd882d5f13](https://linux-hardware.org/?probe=cd882d5f13) | Sep 11, 2021 |
| Toshiba       | Satellite A200              | [371cf70da6](https://linux-hardware.org/?probe=371cf70da6) | Sep 11, 2021 |
| Dell          | Latitude E6220              | [84556dee36](https://linux-hardware.org/?probe=84556dee36) | Sep 11, 2021 |
| Dell          | Latitude E5440              | [4464c56965](https://linux-hardware.org/?probe=4464c56965) | Sep 11, 2021 |
| Toshiba       | Satellite C850D-11R         | [34dcaf597d](https://linux-hardware.org/?probe=34dcaf597d) | Sep 10, 2021 |
| HP            | Compaq Presario CQ40        | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| HP            | EliteBook 8560p             | [48828ad0d3](https://linux-hardware.org/?probe=48828ad0d3) | Sep 10, 2021 |
| HP            | EliteBook 820 G1            | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | [6c992b7260](https://linux-hardware.org/?probe=6c992b7260) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [d137a3a584](https://linux-hardware.org/?probe=d137a3a584) | Sep 09, 2021 |
| Samsung       | R428/P428/R478              | [77a0a88cfc](https://linux-hardware.org/?probe=77a0a88cfc) | Sep 09, 2021 |
| ASUSTek       | UX31E                       | [4b97784aeb](https://linux-hardware.org/?probe=4b97784aeb) | Sep 08, 2021 |
| Dell          | Inspiron N4030              | [8944573827](https://linux-hardware.org/?probe=8944573827) | Sep 08, 2021 |
| Lenovo        | Z50-70 20354                | [cfcaf524be](https://linux-hardware.org/?probe=cfcaf524be) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [99fd24a032](https://linux-hardware.org/?probe=99fd24a032) | Sep 07, 2021 |
| Toshiba       | TECRA M9                    | [75287979cc](https://linux-hardware.org/?probe=75287979cc) | Sep 07, 2021 |
| ASUSTek       | UX31E                       | [e0160c202c](https://linux-hardware.org/?probe=e0160c202c) | Sep 06, 2021 |
| Lenovo        | ThinkPad T530 2429B14       | [c7e0c71a2b](https://linux-hardware.org/?probe=c7e0c71a2b) | Sep 06, 2021 |
| HP            | 15                          | [0082f1df8d](https://linux-hardware.org/?probe=0082f1df8d) | Sep 06, 2021 |
| Toshiba       | Satellite P750              | [ee2674ad2e](https://linux-hardware.org/?probe=ee2674ad2e) | Sep 06, 2021 |
| HP            | ProBook 450 G3              | [d480a297c7](https://linux-hardware.org/?probe=d480a297c7) | Sep 06, 2021 |
| ASUSTek       | X540LJ                      | [ae188f0f01](https://linux-hardware.org/?probe=ae188f0f01) | Sep 05, 2021 |
| Lenovo        | ThinkPad X130e 06222EU      | [a5822f49a3](https://linux-hardware.org/?probe=a5822f49a3) | Sep 05, 2021 |
| Acer          | Extensa 5620                | [1889e6a3ba](https://linux-hardware.org/?probe=1889e6a3ba) | Sep 05, 2021 |
| Dell          | Latitude E6410              | [62c06fee3f](https://linux-hardware.org/?probe=62c06fee3f) | Sep 04, 2021 |
| Chuwi         | CoreBook Pro                | [0fcccea10f](https://linux-hardware.org/?probe=0fcccea10f) | Sep 04, 2021 |
| AMI           | Intel                       | [61b25a4d10](https://linux-hardware.org/?probe=61b25a4d10) | Sep 04, 2021 |
| ASUSTek       | K53U                        | [a2f8f1be7d](https://linux-hardware.org/?probe=a2f8f1be7d) | Sep 04, 2021 |
| HP            | ENVY 4                      | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| Lenovo        | IdeaPad G485 QAWGE          | [e4e83ad591](https://linux-hardware.org/?probe=e4e83ad591) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 2306A44       | [8f97e284a7](https://linux-hardware.org/?probe=8f97e284a7) | Sep 03, 2021 |
| Toshiba       | dynabook R73/A              | [deb0351e19](https://linux-hardware.org/?probe=deb0351e19) | Sep 03, 2021 |
| HP            | Pavilion dv6                | [194d0a6b6d](https://linux-hardware.org/?probe=194d0a6b6d) | Sep 02, 2021 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [f987a10b43](https://linux-hardware.org/?probe=f987a10b43) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | [36e2960d9e](https://linux-hardware.org/?probe=36e2960d9e) | Sep 01, 2021 |
| Dell          | Latitude E6400              | [843b7bd830](https://linux-hardware.org/?probe=843b7bd830) | Sep 01, 2021 |
| MSI           | GS65 Stealth Thin 8RF       | [002d1b30c9](https://linux-hardware.org/?probe=002d1b30c9) | Sep 01, 2021 |
| ASUSTek       | UX31E                       | [f8455be078](https://linux-hardware.org/?probe=f8455be078) | Aug 31, 2021 |
| HP            | 650                         | [903702eab5](https://linux-hardware.org/?probe=903702eab5) | Aug 31, 2021 |
| Dell          | Latitude E6530              | [5996acf813](https://linux-hardware.org/?probe=5996acf813) | Aug 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [13a2f4c840](https://linux-hardware.org/?probe=13a2f4c840) | Aug 31, 2021 |
| Acer          | Extensa 5620                | [76628e61cc](https://linux-hardware.org/?probe=76628e61cc) | Aug 30, 2021 |
| HP            | Notebook                    | [2c504d9c43](https://linux-hardware.org/?probe=2c504d9c43) | Aug 30, 2021 |
| ASUSTek       | UX31E                       | [715882de9a](https://linux-hardware.org/?probe=715882de9a) | Aug 30, 2021 |
| HP            | Laptop 17-bs0xx             | [fe8aec7620](https://linux-hardware.org/?probe=fe8aec7620) | Aug 30, 2021 |
| HP            | Pavilion g6                 | [5b26455c9d](https://linux-hardware.org/?probe=5b26455c9d) | Aug 30, 2021 |
| Toshiba       | Satellite A200              | [e120bda033](https://linux-hardware.org/?probe=e120bda033) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [33ac3a2c18](https://linux-hardware.org/?probe=33ac3a2c18) | Aug 29, 2021 |
| Toshiba       | Satellite L675D             | [7ed7466f02](https://linux-hardware.org/?probe=7ed7466f02) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| Acer          | Aspire ES1-512              | [666660f555](https://linux-hardware.org/?probe=666660f555) | Aug 29, 2021 |
| BANGHO        | MAX G0101                   | [88ac236a11](https://linux-hardware.org/?probe=88ac236a11) | Aug 29, 2021 |
| HP            | Compaq Presario C700        | [6de0905808](https://linux-hardware.org/?probe=6de0905808) | Aug 28, 2021 |
| HP            | Notebook                    | [fa651d2327](https://linux-hardware.org/?probe=fa651d2327) | Aug 28, 2021 |
| HP            | Pavilion g6                 | [708de8642b](https://linux-hardware.org/?probe=708de8642b) | Aug 28, 2021 |
| Lenovo        | ThinkPad SL 27464RM         | [612cb5f7a2](https://linux-hardware.org/?probe=612cb5f7a2) | Aug 28, 2021 |
| Dell          | Latitude E6440              | [6636885dd6](https://linux-hardware.org/?probe=6636885dd6) | Aug 28, 2021 |
| Toshiba       | Satellite A300              | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Apple         | MacBookPro8,1               | [c7926f6e27](https://linux-hardware.org/?probe=c7926f6e27) | Aug 27, 2021 |
| Acer          | Aspire 4349                 | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| ASUSTek       | UX31E                       | [a626915a9b](https://linux-hardware.org/?probe=a626915a9b) | Aug 27, 2021 |
| Lenovo        | ThinkPad T420s 4174FM9      | [12fd92046e](https://linux-hardware.org/?probe=12fd92046e) | Aug 27, 2021 |
| Toshiba       | Satellite P200              | [9c5e106c1d](https://linux-hardware.org/?probe=9c5e106c1d) | Aug 26, 2021 |
| ASUSTek       | UX31E                       | [48a1496d43](https://linux-hardware.org/?probe=48a1496d43) | Aug 26, 2021 |
| Lenovo        | B590 20208                  | [231e5afd60](https://linux-hardware.org/?probe=231e5afd60) | Aug 26, 2021 |
| Dell          | Inspiron 3451               | [4864d7d088](https://linux-hardware.org/?probe=4864d7d088) | Aug 26, 2021 |
| Sony          | VPCEB43FG                   | [4a81e892f0](https://linux-hardware.org/?probe=4a81e892f0) | Aug 26, 2021 |
| Sony          | VPCCW2S8E                   | [a8c2dc6942](https://linux-hardware.org/?probe=a8c2dc6942) | Aug 26, 2021 |
| Acer          | Aspire E5-551               | [154250f58d](https://linux-hardware.org/?probe=154250f58d) | Aug 25, 2021 |
| HP            | Pavilion 15                 | [99f2fbc2fe](https://linux-hardware.org/?probe=99f2fbc2fe) | Aug 25, 2021 |
| HP            | ProBook 4430s               | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| Acer          | Aspire A315-56              | [bf1f07bd8f](https://linux-hardware.org/?probe=bf1f07bd8f) | Aug 25, 2021 |
| ASUSTek       | M51Vr                       | [11a3e4219e](https://linux-hardware.org/?probe=11a3e4219e) | Aug 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1a571bccee](https://linux-hardware.org/?probe=1a571bccee) | Aug 24, 2021 |
| Positivo      | Unknown                     | [28bac734c5](https://linux-hardware.org/?probe=28bac734c5) | Aug 24, 2021 |
| Acer          | Nitro AN515-54              | [5305fab05a](https://linux-hardware.org/?probe=5305fab05a) | Aug 24, 2021 |
| Unknown       | Unknown                     | [a12413ac7e](https://linux-hardware.org/?probe=a12413ac7e) | Aug 24, 2021 |
| HUAWEI        | HVY-WXX9                    | [428295be2a](https://linux-hardware.org/?probe=428295be2a) | Aug 24, 2021 |
| Lenovo        | Z50-75 80EC                 | [27b14654f6](https://linux-hardware.org/?probe=27b14654f6) | Aug 23, 2021 |
| GEO           | GeoBook3                    | [fd999a9ccb](https://linux-hardware.org/?probe=fd999a9ccb) | Aug 23, 2021 |
| eMachines     | eMachiens G443              | [dcb360fa9d](https://linux-hardware.org/?probe=dcb360fa9d) | Aug 23, 2021 |
| Dell          | Precision M3800             | [5b31ab2dd1](https://linux-hardware.org/?probe=5b31ab2dd1) | Aug 22, 2021 |
| Dell          | Inspiron 1520               | [3df4e95976](https://linux-hardware.org/?probe=3df4e95976) | Aug 22, 2021 |
| Lenovo        | ThinkPad E455 20DEA027CD    | [8edb3642cb](https://linux-hardware.org/?probe=8edb3642cb) | Aug 22, 2021 |
| ASUSTek       | X455LA                      | [d40617b08b](https://linux-hardware.org/?probe=d40617b08b) | Aug 22, 2021 |
| Dell          | Latitude E6400              | [6f5bf178ae](https://linux-hardware.org/?probe=6f5bf178ae) | Aug 21, 2021 |
| Lenovo        | Y50-70 20378                | [43adb60059](https://linux-hardware.org/?probe=43adb60059) | Aug 21, 2021 |
| MSI           | GL75 Leopard 10SCSR         | [9524392ab1](https://linux-hardware.org/?probe=9524392ab1) | Aug 21, 2021 |
| ASUSTek       | UX31E                       | [f11d89cc89](https://linux-hardware.org/?probe=f11d89cc89) | Aug 21, 2021 |
| Dell          | Inspiron N5110              | [a42427bf11](https://linux-hardware.org/?probe=a42427bf11) | Aug 21, 2021 |
| Lenovo        | G505 20240                  | [5a3e9b5118](https://linux-hardware.org/?probe=5a3e9b5118) | Aug 20, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7bbab53802](https://linux-hardware.org/?probe=7bbab53802) | Aug 20, 2021 |
| HP            | Laptop 17-by3xxx            | [58e4be097e](https://linux-hardware.org/?probe=58e4be097e) | Aug 20, 2021 |
| Apple         | MacBookPro9,2               | [9d083e28bc](https://linux-hardware.org/?probe=9d083e28bc) | Aug 20, 2021 |
| Samsung       | SBBA                        | [65f6d55cec](https://linux-hardware.org/?probe=65f6d55cec) | Aug 20, 2021 |
| Acer          | Aspire 5738                 | [f05072dfe2](https://linux-hardware.org/?probe=f05072dfe2) | Aug 20, 2021 |
| MSI           | GP63 Leopard 8RE            | [4386911d5e](https://linux-hardware.org/?probe=4386911d5e) | Aug 20, 2021 |
| Sony          | VGN-FW235J                  | [cf6cd49762](https://linux-hardware.org/?probe=cf6cd49762) | Aug 20, 2021 |
| ASUSTek       | UX31E                       | [36beb5b173](https://linux-hardware.org/?probe=36beb5b173) | Aug 19, 2021 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [71ce37eae0](https://linux-hardware.org/?probe=71ce37eae0) | Aug 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Lenovo        | ThinkPad W530 2447A55       | [bb1dabf95c](https://linux-hardware.org/?probe=bb1dabf95c) | Aug 19, 2021 |
| Philco        | 14L                         | [55ea231ff3](https://linux-hardware.org/?probe=55ea231ff3) | Aug 19, 2021 |
| ASUSTek       | K75VM                       | [21b58d5364](https://linux-hardware.org/?probe=21b58d5364) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2436542f9e](https://linux-hardware.org/?probe=2436542f9e) | Aug 19, 2021 |
| MSI           | VR601                       | [182064e2f6](https://linux-hardware.org/?probe=182064e2f6) | Aug 19, 2021 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [6d7fb6d592](https://linux-hardware.org/?probe=6d7fb6d592) | Aug 19, 2021 |
| Dell          | Inspiron 3541               | [231f84ef9a](https://linux-hardware.org/?probe=231f84ef9a) | Aug 18, 2021 |
| HP            | 620                         | [c2402bee8f](https://linux-hardware.org/?probe=c2402bee8f) | Aug 18, 2021 |
| ASUSTek       | UX31E                       | [0816a877bd](https://linux-hardware.org/?probe=0816a877bd) | Aug 18, 2021 |
| Dell          | Latitude E7440              | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Acer          | Aspire A515-44              | [99130e2a63](https://linux-hardware.org/?probe=99130e2a63) | Aug 17, 2021 |
| Toshiba       | Satellite L750              | [b9d7ea01d3](https://linux-hardware.org/?probe=b9d7ea01d3) | Aug 17, 2021 |
| ASUSTek       | UX31E                       | [7b007be9fd](https://linux-hardware.org/?probe=7b007be9fd) | Aug 16, 2021 |
| Lenovo        | V15-ADA 82C7                | [10584329de](https://linux-hardware.org/?probe=10584329de) | Aug 16, 2021 |
| ASUSTek       | UX31E                       | [f9243be85f](https://linux-hardware.org/?probe=f9243be85f) | Aug 16, 2021 |
| AVITA         | NE14A2                      | [cd5b403f7b](https://linux-hardware.org/?probe=cd5b403f7b) | Aug 16, 2021 |
| HP            | Pavilion g4                 | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | X555LAB                     | [492a70dafb](https://linux-hardware.org/?probe=492a70dafb) | Aug 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5099762c27](https://linux-hardware.org/?probe=5099762c27) | Aug 15, 2021 |
| HP            | Laptop 14-dk0xxx            | [aa814d2ef6](https://linux-hardware.org/?probe=aa814d2ef6) | Aug 15, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [c2dee4fe1c](https://linux-hardware.org/?probe=c2dee4fe1c) | Aug 14, 2021 |
| HP            | Pavilion dv6                | [85137e0eb5](https://linux-hardware.org/?probe=85137e0eb5) | Aug 14, 2021 |
| Acer          | Aspire E1-572               | [83fa6c50f9](https://linux-hardware.org/?probe=83fa6c50f9) | Aug 14, 2021 |
| Acer          | Aspire 5742G                | [47d7f0676e](https://linux-hardware.org/?probe=47d7f0676e) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| HP            | Laptop 15-ra0xx             | [0e21f00a7b](https://linux-hardware.org/?probe=0e21f00a7b) | Aug 13, 2021 |
| ASUSTek       | UX31E                       | [80cfc9b687](https://linux-hardware.org/?probe=80cfc9b687) | Aug 12, 2021 |
| eMachines     | Padus                       | [23d6f05daf](https://linux-hardware.org/?probe=23d6f05daf) | Aug 12, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [4efc66c85a](https://linux-hardware.org/?probe=4efc66c85a) | Aug 11, 2021 |
| Samsung       | R530/R730                   | [3c4eb18a66](https://linux-hardware.org/?probe=3c4eb18a66) | Aug 11, 2021 |
| ASUSTek       | UX31E                       | [4651e027d9](https://linux-hardware.org/?probe=4651e027d9) | Aug 11, 2021 |
| Dell          | Inspiron 15-3567            | [f3dce1cf9c](https://linux-hardware.org/?probe=f3dce1cf9c) | Aug 11, 2021 |
| Acer          | Aspire 5742Z                | [dd55e4423e](https://linux-hardware.org/?probe=dd55e4423e) | Aug 11, 2021 |
| Dell          | Latitude E6410              | [6fabd1e814](https://linux-hardware.org/?probe=6fabd1e814) | Aug 11, 2021 |
| Acer          | Aspire ES1-531              | [7e9380ffa9](https://linux-hardware.org/?probe=7e9380ffa9) | Aug 11, 2021 |
| ASUSTek       | UX31E                       | [28897c5b5f](https://linux-hardware.org/?probe=28897c5b5f) | Aug 09, 2021 |
| Acer          | Aspire ES1-571              | [f17ba50593](https://linux-hardware.org/?probe=f17ba50593) | Aug 09, 2021 |
| MSI           | CR610M                      | [68759b0315](https://linux-hardware.org/?probe=68759b0315) | Aug 08, 2021 |
| HP            | ProBook 470 G0              | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| Fujitsu       | LIFEBOOK V1020              | [8eff816347](https://linux-hardware.org/?probe=8eff816347) | Aug 08, 2021 |
| ASUSTek       | UX31E                       | [5c64722433](https://linux-hardware.org/?probe=5c64722433) | Aug 07, 2021 |
| ASUSTek       | UX31E                       | [88c691e7f1](https://linux-hardware.org/?probe=88c691e7f1) | Aug 07, 2021 |
| Sony          | VPCEB15FB                   | [15c824ba8c](https://linux-hardware.org/?probe=15c824ba8c) | Aug 07, 2021 |
| HP            | EliteBook Folio 9470m       | [007cd499bf](https://linux-hardware.org/?probe=007cd499bf) | Aug 06, 2021 |
| Acer          | Aspire E1-772G              | [f90e78e30c](https://linux-hardware.org/?probe=f90e78e30c) | Aug 06, 2021 |
| Dell          | Inspiron 11-3168            | [67552d79ac](https://linux-hardware.org/?probe=67552d79ac) | Aug 05, 2021 |
| Lenovo        | ZHAOYANG E49L 20178         | [312f83aef7](https://linux-hardware.org/?probe=312f83aef7) | Aug 04, 2021 |
| ASUSTek       | UX31E                       | [1e458b84be](https://linux-hardware.org/?probe=1e458b84be) | Aug 04, 2021 |
| Dell          | System Inspiron N7110       | [57caac7a11](https://linux-hardware.org/?probe=57caac7a11) | Aug 04, 2021 |
| ASUSTek       | X555QA                      | [9ea78fd6b8](https://linux-hardware.org/?probe=9ea78fd6b8) | Aug 04, 2021 |
| Acer          | Extensa 2511G               | [6a087db61e](https://linux-hardware.org/?probe=6a087db61e) | Aug 04, 2021 |
| ASUSTek       | UX31E                       | [8951f246ed](https://linux-hardware.org/?probe=8951f246ed) | Aug 04, 2021 |
| Toshiba       | Satellite L300              | [cf09ab3f7b](https://linux-hardware.org/?probe=cf09ab3f7b) | Aug 04, 2021 |
| Dell          | Latitude E6410              | [2642f1ccbf](https://linux-hardware.org/?probe=2642f1ccbf) | Aug 03, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b176392b38](https://linux-hardware.org/?probe=b176392b38) | Aug 02, 2021 |
| Toshiba       | Satellite Pro L300          | [56810e152d](https://linux-hardware.org/?probe=56810e152d) | Aug 02, 2021 |
| ASUSTek       | X555QA                      | [77f9efc15b](https://linux-hardware.org/?probe=77f9efc15b) | Aug 02, 2021 |
| ASUSTek       | X556URK                     | [39508e15e9](https://linux-hardware.org/?probe=39508e15e9) | Aug 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [fc496cc5f1](https://linux-hardware.org/?probe=fc496cc5f1) | Aug 02, 2021 |
| Dell          | Latitude E6330              | [805fbb547d](https://linux-hardware.org/?probe=805fbb547d) | Aug 02, 2021 |
| Lenovo        | ThinkPad T500 224235U       | [af0abeae96](https://linux-hardware.org/?probe=af0abeae96) | Aug 02, 2021 |
| HP            | Notebook                    | [d05f512f0c](https://linux-hardware.org/?probe=d05f512f0c) | Aug 01, 2021 |
| Acer          | Extensa 5620                | [9f11c37b87](https://linux-hardware.org/?probe=9f11c37b87) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| HP            | Pavilion dv7                | [2966b0fcc3](https://linux-hardware.org/?probe=2966b0fcc3) | Jul 31, 2021 |
| Dell          | Inspiron 5547               | [5956d016c4](https://linux-hardware.org/?probe=5956d016c4) | Jul 31, 2021 |
| Dell          | Latitude E6530              | [3318146af3](https://linux-hardware.org/?probe=3318146af3) | Jul 31, 2021 |
| ASUSTek       | N76VZ                       | [2659536413](https://linux-hardware.org/?probe=2659536413) | Jul 31, 2021 |
| Acer          | TravelMate 5720             | [b273b3b08b](https://linux-hardware.org/?probe=b273b3b08b) | Jul 30, 2021 |
| Sony          | VGN-FW190E                  | [76c6658153](https://linux-hardware.org/?probe=76c6658153) | Jul 30, 2021 |
| Dell          | Latitude E5520              | [596506d724](https://linux-hardware.org/?probe=596506d724) | Jul 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d111db11a8](https://linux-hardware.org/?probe=d111db11a8) | Jul 30, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [3da57c8f0a](https://linux-hardware.org/?probe=3da57c8f0a) | Jul 30, 2021 |
| Lenovo        | G40-45 80E1                 | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | [44b0620279](https://linux-hardware.org/?probe=44b0620279) | Jul 29, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [af6e658215](https://linux-hardware.org/?probe=af6e658215) | Jul 29, 2021 |
| HP            | Pavilion g6                 | [54748daba1](https://linux-hardware.org/?probe=54748daba1) | Jul 28, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [4d57aa7ae7](https://linux-hardware.org/?probe=4d57aa7ae7) | Jul 28, 2021 |
| Positivo      | S14BW01                     | [2c773d0a85](https://linux-hardware.org/?probe=2c773d0a85) | Jul 28, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8cdb059bd7](https://linux-hardware.org/?probe=8cdb059bd7) | Jul 28, 2021 |
| Digibras      | NH4CU03                     | [29e30b2f47](https://linux-hardware.org/?probe=29e30b2f47) | Jul 28, 2021 |
| Teclast       | F15S                        | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| Dell          | Latitude E5520              | [5c855b9a27](https://linux-hardware.org/?probe=5c855b9a27) | Jul 27, 2021 |
| HP            | 550                         | [6adbee7061](https://linux-hardware.org/?probe=6adbee7061) | Jul 27, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d696ddb724](https://linux-hardware.org/?probe=d696ddb724) | Jul 27, 2021 |
| Acer          | Aspire A515-54G             | [423dbfb637](https://linux-hardware.org/?probe=423dbfb637) | Jul 27, 2021 |
| Lenovo        | V110-15AST 80TD             | [8ead90b4e2](https://linux-hardware.org/?probe=8ead90b4e2) | Jul 27, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a49af6e8ca](https://linux-hardware.org/?probe=a49af6e8ca) | Jul 26, 2021 |
| Samsung       | Q430/Q530                   | [0c8ac8e636](https://linux-hardware.org/?probe=0c8ac8e636) | Jul 26, 2021 |
| Dell          | Latitude E5550              | [5770baf0a8](https://linux-hardware.org/?probe=5770baf0a8) | Jul 26, 2021 |
| ASUSTek       | X75VC                       | [b4132b0b83](https://linux-hardware.org/?probe=b4132b0b83) | Jul 25, 2021 |
| Acer          | Aspire A515-51G             | [490727e945](https://linux-hardware.org/?probe=490727e945) | Jul 25, 2021 |
| Sony          | SVE14A1S6EW                 | [d88a05e1ff](https://linux-hardware.org/?probe=d88a05e1ff) | Jul 25, 2021 |
| Intel         | W7645                       | [8465fa1bd1](https://linux-hardware.org/?probe=8465fa1bd1) | Jul 25, 2021 |
| Toshiba       | Satellite L755              | [0260029bde](https://linux-hardware.org/?probe=0260029bde) | Jul 25, 2021 |
| Toshiba       | Satellite C850D-11K         | [c442634262](https://linux-hardware.org/?probe=c442634262) | Jul 24, 2021 |
| Lenovo        | B590 37612ZG                | [d98c071ad8](https://linux-hardware.org/?probe=d98c071ad8) | Jul 24, 2021 |
| Acer          | Aspire E5-522               | [4df0ce18ff](https://linux-hardware.org/?probe=4df0ce18ff) | Jul 24, 2021 |
| HP            | 635                         | [06f1ff97b5](https://linux-hardware.org/?probe=06f1ff97b5) | Jul 24, 2021 |
| HP            | ProBook 440 G6              | [8d2d5c40d7](https://linux-hardware.org/?probe=8d2d5c40d7) | Jul 24, 2021 |
| Sony          | SVE14A35CXH                 | [9c5acaf613](https://linux-hardware.org/?probe=9c5acaf613) | Jul 23, 2021 |
| Dell          | Inspiron 3521               | [bea03aa7b8](https://linux-hardware.org/?probe=bea03aa7b8) | Jul 22, 2021 |
| Packard Be... | EasyNote TE69KB             | [86e553cd69](https://linux-hardware.org/?probe=86e553cd69) | Jul 22, 2021 |
| ASUSTek       | X550JK                      | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| HP            | 2000                        | [13aaafccdb](https://linux-hardware.org/?probe=13aaafccdb) | Jul 22, 2021 |
| Lenovo        | V15-ADA 82C7                | [b94ac5b0db](https://linux-hardware.org/?probe=b94ac5b0db) | Jul 22, 2021 |
| HUAWEI        | NBLL-WXX9                   | [f42c1709be](https://linux-hardware.org/?probe=f42c1709be) | Jul 21, 2021 |
| HP            | ProBook 455 G7              | [4cc429d760](https://linux-hardware.org/?probe=4cc429d760) | Jul 21, 2021 |
| ASUSTek       | GL752VW                     | [50d9d36655](https://linux-hardware.org/?probe=50d9d36655) | Jul 21, 2021 |
| Toshiba       | TECRA S11                   | [34a16c1c24](https://linux-hardware.org/?probe=34a16c1c24) | Jul 21, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [6d6a97729d](https://linux-hardware.org/?probe=6d6a97729d) | Jul 21, 2021 |
| HP            | Pavilion g4                 | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| Lenovo        | Z50-70 20354                | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| HP            | Pavilion g6                 | [9a5dcf0b58](https://linux-hardware.org/?probe=9a5dcf0b58) | Jul 21, 2021 |
| Sony          | SVF1521B1EW                 | [fd3b2d00e9](https://linux-hardware.org/?probe=fd3b2d00e9) | Jul 21, 2021 |
| Apple         | MacBookPro6,2               | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Fujitsu       | LIFEBOOK S752               | [cd451c84ac](https://linux-hardware.org/?probe=cd451c84ac) | Jul 21, 2021 |
| Lenovo        | G50-70m 20423               | [0b1a40c724](https://linux-hardware.org/?probe=0b1a40c724) | Jul 21, 2021 |
| Dell          | Latitude E4310              | [2bbea19fde](https://linux-hardware.org/?probe=2bbea19fde) | Jul 21, 2021 |
| Dell          | Inspiron 3493               | [df4bedc1fd](https://linux-hardware.org/?probe=df4bedc1fd) | Jul 21, 2021 |
| ASUSTek       | K84C                        | [3c199f4247](https://linux-hardware.org/?probe=3c199f4247) | Jul 21, 2021 |
| Dell          | Inspiron 15-3565            | [931f3dd3ce](https://linux-hardware.org/?probe=931f3dd3ce) | Jul 20, 2021 |
| HP            | EliteBook 850 G6            | [d0a8afe992](https://linux-hardware.org/?probe=d0a8afe992) | Jul 20, 2021 |
| Acer          | Aspire A315-21              | [259e326fa1](https://linux-hardware.org/?probe=259e326fa1) | Jul 20, 2021 |
| Dell          | Latitude E4300              | [3310bfe342](https://linux-hardware.org/?probe=3310bfe342) | Jul 20, 2021 |
| Lenovo        | ThinkPad X220 429144U       | [adb1e003e4](https://linux-hardware.org/?probe=adb1e003e4) | Jul 20, 2021 |
| Toshiba       | Satellite S855              | [fd91905dbd](https://linux-hardware.org/?probe=fd91905dbd) | Jul 20, 2021 |
| Acer          | Aspire A317-52              | [d2cf394833](https://linux-hardware.org/?probe=d2cf394833) | Jul 20, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [b957a1327b](https://linux-hardware.org/?probe=b957a1327b) | Jul 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b44e9be41b](https://linux-hardware.org/?probe=b44e9be41b) | Jul 19, 2021 |
| Lenovo        | IdeaPad Z580                | [b6b62cb7e9](https://linux-hardware.org/?probe=b6b62cb7e9) | Jul 19, 2021 |
| Apple         | MacBookAir6,2               | [9d8a333b02](https://linux-hardware.org/?probe=9d8a333b02) | Jul 19, 2021 |
| HP            | Pavilion dv6500             | [e4aa7493f2](https://linux-hardware.org/?probe=e4aa7493f2) | Jul 19, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [c499631e7e](https://linux-hardware.org/?probe=c499631e7e) | Jul 19, 2021 |
| Packard Be... | EasyNote ENTG71BM           | [788b497894](https://linux-hardware.org/?probe=788b497894) | Jul 19, 2021 |
| HP            | ENVY Spectre XT Ultraboo... | [bf877db72a](https://linux-hardware.org/?probe=bf877db72a) | Jul 19, 2021 |
| Lenovo        | B50-10 80QR                 | [0155a8f42f](https://linux-hardware.org/?probe=0155a8f42f) | Jul 19, 2021 |
| HP            | Pavilion Notebook           | [668bdbac43](https://linux-hardware.org/?probe=668bdbac43) | Jul 19, 2021 |
| HP            | ProBook 455 G1              | [99bdbe02e3](https://linux-hardware.org/?probe=99bdbe02e3) | Jul 19, 2021 |
| HP            | 250 G6 Notebook PC          | [14945dd66b](https://linux-hardware.org/?probe=14945dd66b) | Jul 19, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [9b9629e155](https://linux-hardware.org/?probe=9b9629e155) | Jul 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [0ae1d8d27e](https://linux-hardware.org/?probe=0ae1d8d27e) | Jul 18, 2021 |
| Clevo         | P170HMx                     | [ec390083cc](https://linux-hardware.org/?probe=ec390083cc) | Jul 18, 2021 |
| HP            | Laptop 15-bs0xx             | [c84d445008](https://linux-hardware.org/?probe=c84d445008) | Jul 18, 2021 |
| Acer          | Aspire E5-521               | [d4629ecbed](https://linux-hardware.org/?probe=d4629ecbed) | Jul 18, 2021 |
| Lenovo        | ThinkPad X270 20HNA003CD    | [51faf0c18d](https://linux-hardware.org/?probe=51faf0c18d) | Jul 18, 2021 |
| Acer          | Aspire E1-531               | [11fbbf6787](https://linux-hardware.org/?probe=11fbbf6787) | Jul 18, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [9325c953a8](https://linux-hardware.org/?probe=9325c953a8) | Jul 18, 2021 |
| Acer          | Extensa 5220                | [1617222801](https://linux-hardware.org/?probe=1617222801) | Jul 18, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [1b947b3e68](https://linux-hardware.org/?probe=1b947b3e68) | Jul 18, 2021 |
| HP            | Laptop 17-ak0xx             | [8aaa6730f3](https://linux-hardware.org/?probe=8aaa6730f3) | Jul 18, 2021 |
| HP            | Laptop 17-ca1xxx            | [70224ff941](https://linux-hardware.org/?probe=70224ff941) | Jul 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.2/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Notebooks | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 2164      | 94.7%   |
| 5.11.12-desktop-1omv4002       | 106       | 4.64%   |
| 5.11.0-desktop-clang-1omv4002  | 5         | 0.22%   |
| 5.9.12-desktop-1omv4002        | 2         | 0.09%   |
| 5.8.13-desktop-1omv4002        | 1         | 0.04%   |
| 5.16.13-desktop-1omv4003       | 1         | 0.04%   |
| 5.11.1-desktop-74.1.1bomv4002  | 1         | 0.04%   |
| 5.11.0-desktop-1omv4002        | 1         | 0.04%   |
| 5.11.0-desktop-0.rc4.1omv4002  | 1         | 0.04%   |
| 5.10.2-desktop-clang-1omv4002  | 1         | 0.04%   |
| 5.10.12-desktop-clang-1omv4002 | 1         | 0.04%   |
| Unknown                        | 1         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.14 | 2164      | 94.7%   |
| 5.11.12 | 106       | 4.64%   |
| 5.11.0  | 7         | 0.31%   |
| 5.9.12  | 2         | 0.09%   |
| 5.8.13  | 1         | 0.04%   |
| 5.16.13 | 1         | 0.04%   |
| 5.11.1  | 1         | 0.04%   |
| 5.10.2  | 1         | 0.04%   |
| 5.10.12 | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2166      | 94.79%  |
| 5.11    | 114       | 4.99%   |
| 5.9     | 2         | 0.09%   |
| 5.8     | 1         | 0.04%   |
| 5.16    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2251      | 99.96%  |
| Unknown | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 2248      | 99.78%  |
| Unknown  | 3         | 0.13%   |
| GNOME    | 1         | 0.04%   |
| Cinnamon | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2248      | 99.82%  |
| Wayland | 3         | 0.13%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 2250      | 99.91%  |
| Unknown | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1113      | 49.16%  |
| de_DE   | 190       | 8.39%   |
| fr_FR   | 152       | 6.71%   |
| pl_PL   | 136       | 6.01%   |
| ru_RU   | 131       | 5.79%   |
| pt_BR   | 102       | 4.51%   |
| cs_CZ   | 64        | 2.83%   |
| it_IT   | 63        | 2.78%   |
| es_ES   | 61        | 2.69%   |
| en_GB   | 48        | 2.12%   |
| es_AR   | 21        | 0.93%   |
| es_MX   | 17        | 0.75%   |
| hu_HU   | 11        | 0.49%   |
| fr_BE   | 9         | 0.4%    |
| es_CO   | 9         | 0.4%    |
| ru_UA   | 8         | 0.35%   |
| nl_NL   | 8         | 0.35%   |
| es_CL   | 8         | 0.35%   |
| en_AU   | 8         | 0.35%   |
| fr_CH   | 7         | 0.31%   |
| en_IN   | 7         | 0.31%   |
| de_AT   | 7         | 0.31%   |
| ro_RO   | 6         | 0.27%   |
| pt_PT   | 6         | 0.27%   |
| en_CA   | 6         | 0.27%   |
| da_DK   | 6         | 0.27%   |
| fr_CA   | 5         | 0.22%   |
| uk_UA   | 4         | 0.18%   |
| nl_BE   | 4         | 0.18%   |
| nb_NO   | 4         | 0.18%   |
| en_NZ   | 4         | 0.18%   |
| de_CH   | 4         | 0.18%   |
| Unknown | 4         | 0.18%   |
| es_UY   | 3         | 0.13%   |
| es_PE   | 3         | 0.13%   |
| es_CR   | 3         | 0.13%   |
| it_CH   | 2         | 0.09%   |
| es_VE   | 2         | 0.09%   |
| es_GT   | 2         | 0.09%   |
| en_ZA   | 2         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1316      | 58.28%  |
| EFI  | 942       | 41.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 1717      | 75.08%  |
| Ext4    | 542       | 23.7%   |
| Btrfs   | 11        | 0.48%   |
| F2fs    | 6         | 0.26%   |
| Ext2    | 5         | 0.22%   |
| Xfs     | 3         | 0.13%   |
| Ext3    | 2         | 0.09%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1325      | 58.55%  |
| MBR     | 934       | 41.27%  |
| Unknown | 4         | 0.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1135      | 50.07%  |
| Yes       | 1132      | 49.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1307      | 57.88%  |
| Yes       | 951       | 42.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 410       | 18.21%  |
| Hewlett-Packard     | 405       | 17.98%  |
| Dell                | 320       | 14.21%  |
| ASUSTek Computer    | 276       | 12.26%  |
| Acer                | 273       | 12.12%  |
| Toshiba             | 122       | 5.42%   |
| Sony                | 64        | 2.84%   |
| Samsung Electronics | 60        | 2.66%   |
| Apple               | 37        | 1.64%   |
| MSI                 | 36        | 1.6%    |
| Fujitsu             | 24        | 1.07%   |
| Packard Bell        | 21        | 0.93%   |
| Medion              | 18        | 0.8%    |
| Positivo            | 17        | 0.75%   |
| eMachines           | 14        | 0.62%   |
| Notebook            | 13        | 0.58%   |
| HUAWEI              | 13        | 0.58%   |
| Philco              | 10        | 0.44%   |
| Fujitsu Siemens     | 8         | 0.36%   |
| Unknown             | 8         | 0.36%   |
| Clevo               | 7         | 0.31%   |
| Chuwi               | 7         | 0.31%   |
| Timi                | 6         | 0.27%   |
| LG Electronics      | 6         | 0.27%   |
| TUXEDO              | 5         | 0.22%   |
| System76            | 5         | 0.22%   |
| Teclast             | 4         | 0.18%   |
| Panasonic           | 4         | 0.18%   |
| PC Specialist       | 3         | 0.13%   |
| Intel               | 3         | 0.13%   |
| Gateway             | 3         | 0.13%   |
| Wortmann AG         | 2         | 0.09%   |
| UMAX                | 2         | 0.09%   |
| Shuttle             | 2         | 0.09%   |
| NEC Computers       | 2         | 0.09%   |
| Jumper              | 2         | 0.09%   |
| HASEE Computer      | 2         | 0.09%   |
| BOX                 | 2         | 0.09%   |
| Alienware           | 2         | 0.09%   |
| VIT                 | 1         | 0.04%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS UX31E                                 | 44        | 1.95%   |
| Dell Inspiron 3451                         | 32        | 1.42%   |
| HP Notebook                                | 24        | 1.07%   |
| Unknown                                    | 20        | 0.89%   |
| HP Pavilion g6                             | 13        | 0.58%   |
| Dell Latitude E6430                        | 11        | 0.49%   |
| HP Pavilion dv6                            | 10        | 0.44%   |
| Dell Latitude D630                         | 10        | 0.44%   |
| Toshiba Satellite A300                     | 8         | 0.36%   |
| Dell Latitude E6410                        | 8         | 0.36%   |
| HP Pavilion 15                             | 7         | 0.31%   |
| HP EliteBook 8440p                         | 7         | 0.31%   |
| Dell Latitude E6420                        | 7         | 0.31%   |
| Dell Inspiron 15-3567                      | 7         | 0.31%   |
| Lenovo Z50-70 20354                        | 6         | 0.27%   |
| Lenovo IdeaPad S145-15AST 81N3             | 6         | 0.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 6         | 0.27%   |
| HP EliteBook 8570w                         | 6         | 0.27%   |
| HP 15                                      | 6         | 0.27%   |
| Dell Latitude E6500                        | 6         | 0.27%   |
| Dell Latitude E6400                        | 6         | 0.27%   |
| Dell Inspiron N5110                        | 6         | 0.27%   |
| ASUS X541NA                                | 6         | 0.27%   |
| ASUS K53E                                  | 6         | 0.27%   |
| Acer Aspire 5738                           | 6         | 0.27%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 5         | 0.22%   |
| Positivo Mobile                            | 5         | 0.22%   |
| Philco 14I                                 | 5         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 5         | 0.22%   |
| HP Pavilion Notebook                       | 5         | 0.22%   |
| HP Pavilion g4                             | 5         | 0.22%   |
| HP Laptop 15-bs0xx                         | 5         | 0.22%   |
| Dell Latitude E6320                        | 5         | 0.22%   |
| Dell Inspiron 3542                         | 5         | 0.22%   |
| ASUS X550CA                                | 5         | 0.22%   |
| ASUS K52F                                  | 5         | 0.22%   |
| Toshiba Satellite L500                     | 4         | 0.18%   |
| Toshiba Satellite L300                     | 4         | 0.18%   |
| Samsung 300E4C/300E5C/300E7C               | 4         | 0.18%   |
| Positivo S14BW01                           | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 209       | 9.28%   |
| Lenovo ThinkPad       | 167       | 7.42%   |
| Dell Latitude         | 141       | 6.26%   |
| Lenovo IdeaPad        | 133       | 5.91%   |
| Dell Inspiron         | 125       | 5.55%   |
| Toshiba Satellite     | 100       | 4.44%   |
| HP Pavilion           | 88        | 3.91%   |
| HP Laptop             | 58        | 2.58%   |
| HP EliteBook          | 51        | 2.26%   |
| ASUS UX31E            | 44        | 1.95%   |
| HP ProBook            | 42        | 1.87%   |
| HP Compaq             | 36        | 1.6%    |
| ASUS VivoBook         | 26        | 1.15%   |
| HP Notebook           | 24        | 1.07%   |
| Fujitsu LIFEBOOK      | 20        | 0.89%   |
| Unknown               | 20        | 0.89%   |
| Acer Extensa          | 19        | 0.84%   |
| Packard Bell EasyNote | 17        | 0.75%   |
| Dell Vostro           | 16        | 0.71%   |
| Acer TravelMate       | 16        | 0.71%   |
| HP 250                | 12        | 0.53%   |
| HP ENVY               | 11        | 0.49%   |
| Dell Studio           | 9         | 0.4%    |
| Toshiba dynabook      | 8         | 0.36%   |
| Dell XPS              | 8         | 0.36%   |
| HP Stream             | 7         | 0.31%   |
| HP 15                 | 7         | 0.31%   |
| Apple MacBookPro9     | 7         | 0.31%   |
| Acer Swift            | 7         | 0.31%   |
| Lenovo Z50-70         | 6         | 0.27%   |
| Lenovo B590           | 6         | 0.27%   |
| HP Presario           | 6         | 0.27%   |
| HP 255                | 6         | 0.27%   |
| Dell Precision        | 6         | 0.27%   |
| ASUS ZenBook          | 6         | 0.27%   |
| ASUS X541NA           | 6         | 0.27%   |
| ASUS TUF              | 6         | 0.27%   |
| ASUS K53E             | 6         | 0.27%   |
| Apple MacBookPro8     | 6         | 0.27%   |
| Acer Nitro            | 6         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 302       | 13.41%  |
| 2012    | 222       | 9.86%   |
| 2013    | 190       | 8.44%   |
| 2014    | 180       | 7.99%   |
| 2010    | 179       | 7.95%   |
| 2008    | 177       | 7.86%   |
| 2019    | 158       | 7.02%   |
| 2015    | 140       | 6.22%   |
| 2017    | 122       | 5.42%   |
| 2016    | 121       | 5.37%   |
| 2009    | 121       | 5.37%   |
| 2018    | 120       | 5.33%   |
| 2020    | 96        | 4.26%   |
| 2007    | 90        | 4%      |
| 2021    | 22        | 0.98%   |
| 2006    | 6         | 0.27%   |
| 2005    | 3         | 0.13%   |
| Unknown | 2         | 0.09%   |
| 2004    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2252      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2252      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2248      | 99.82%  |
| Yes  | 4         | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 919       | 40.77%  |
| 4.01-8.0   | 665       | 29.5%   |
| 8.01-16.0  | 295       | 13.09%  |
| 16.01-24.0 | 159       | 7.05%   |
| 1.01-2.0   | 129       | 5.72%   |
| 2.01-3.0   | 48        | 2.13%   |
| 32.01-64.0 | 29        | 1.29%   |
| 24.01-32.0 | 5         | 0.22%   |
| 0.51-1.0   | 4         | 0.18%   |
| Unknown    | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 1860      | 81.69%  |
| 0.51-1.0 | 250       | 10.98%  |
| 2.01-3.0 | 130       | 5.71%   |
| 0.01-0.5 | 28        | 1.23%   |
| 3.01-4.0 | 5         | 0.22%   |
| 4.01-8.0 | 3         | 0.13%   |
| Unknown  | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1702      | 75.38%  |
| 2      | 471       | 20.86%  |
| 3      | 41        | 1.82%   |
| 0      | 39        | 1.73%   |
| 4      | 4         | 0.18%   |
| 5      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1327      | 58.87%  |
| No        | 927       | 41.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2058      | 91.39%  |
| No        | 194       | 8.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2231      | 99.07%  |
| No        | 21        | 0.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1508      | 66.9%   |
| No        | 746       | 33.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 263       | 11.67%  |
| USA          | 203       | 9.01%   |
| France       | 189       | 8.39%   |
| Poland       | 187       | 8.3%    |
| Russia       | 165       | 7.32%   |
| Brazil       | 163       | 7.23%   |
| Italy        | 108       | 4.79%   |
| Spain        | 88        | 3.91%   |
| Czechia      | 75        | 3.33%   |
| UK           | 60        | 2.66%   |
| Canada       | 51        | 2.26%   |
| Mexico       | 43        | 1.91%   |
| India        | 33        | 1.46%   |
| Ukraine      | 32        | 1.42%   |
| Argentina    | 25        | 1.11%   |
| Romania      | 23        | 1.02%   |
| Indonesia    | 23        | 1.02%   |
| Portugal     | 22        | 0.98%   |
| Sweden       | 21        | 0.93%   |
| Netherlands  | 21        | 0.93%   |
| Japan        | 21        | 0.93%   |
| Hungary      | 21        | 0.93%   |
| Belgium      | 20        | 0.89%   |
| Australia    | 20        | 0.89%   |
| Switzerland  | 16        | 0.71%   |
| Greece       | 14        | 0.62%   |
| Finland      | 14        | 0.62%   |
| China        | 14        | 0.62%   |
| Chile        | 14        | 0.62%   |
| Bulgaria     | 13        | 0.58%   |
| Slovakia     | 12        | 0.53%   |
| Denmark      | 12        | 0.53%   |
| Belarus      | 12        | 0.53%   |
| Philippines  | 11        | 0.49%   |
| Norway       | 11        | 0.49%   |
| Colombia     | 11        | 0.49%   |
| Austria      | 11        | 0.49%   |
| South Africa | 10        | 0.44%   |
| Algeria      | 10        | 0.44%   |
| Thailand     | 9         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 49        | 2.14%   |
| Krakow         | 35        | 1.53%   |
| Warsaw         | 30        | 1.31%   |
| Moscow         | 30        | 1.31%   |
| Paris          | 26        | 1.14%   |
| Berlin         | 20        | 0.88%   |
| St Petersburg  | 16        | 0.7%    |
| Rome           | 16        | 0.7%    |
| Milan          | 16        | 0.7%    |
| Munich         | 13        | 0.57%   |
| Mexico City    | 13        | 0.57%   |
| Krasnodar      | 13        | 0.57%   |
| Sao Paulo      | 12        | 0.53%   |
| Wroclaw        | 10        | 0.44%   |
| Stuttgart      | 10        | 0.44%   |
| Rio de Janeiro | 10        | 0.44%   |
| Queens         | 10        | 0.44%   |
| Poznan         | 9         | 0.39%   |
| Madrid         | 9         | 0.39%   |
| Porto Alegre   | 8         | 0.35%   |
| Helsinki       | 8         | 0.35%   |
| Brno           | 8         | 0.35%   |
| Yekaterinburg  | 7         | 0.31%   |
| Lodz           | 7         | 0.31%   |
| Gdansk         | 7         | 0.31%   |
| Buenos Aires   | 7         | 0.31%   |
| Budapest       | 7         | 0.31%   |
| Bucharest      | 7         | 0.31%   |
| Vienna         | 6         | 0.26%   |
| Sydney         | 6         | 0.26%   |
| Santo André   | 6         | 0.26%   |
| Melbourne      | 6         | 0.26%   |
| Mannheim       | 6         | 0.26%   |
| Lisbon         | 6         | 0.26%   |
| Johannesburg   | 6         | 0.26%   |
| Hamburg        | 6         | 0.26%   |
| Florence       | 6         | 0.26%   |
| Yaroslavl      | 5         | 0.22%   |
| Thessaloniki   | 5         | 0.22%   |
| Tehran         | 5         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 436       | 454    | 16.91%  |
| Seagate             | 404       | 418    | 15.67%  |
| Toshiba             | 274       | 286    | 10.63%  |
| Samsung Electronics | 272       | 301    | 10.55%  |
| Kingston            | 149       | 157    | 5.78%   |
| Hitachi             | 146       | 150    | 5.66%   |
| SanDisk             | 135       | 140    | 5.24%   |
| Unknown             | 91        | 96     | 3.53%   |
| HGST                | 87        | 90     | 3.37%   |
| Crucial             | 71        | 74     | 2.75%   |
| Intel               | 51        | 57     | 1.98%   |
| SK hynix            | 47        | 49     | 1.82%   |
| A-DATA Technology   | 41        | 41     | 1.59%   |
| Fujitsu             | 26        | 26     | 1.01%   |
| Micron Technology   | 22        | 22     | 0.85%   |
| GOODRAM             | 20        | 22     | 0.78%   |
| Apple               | 20        | 23     | 0.78%   |
| PNY                 | 17        | 18     | 0.66%   |
| China               | 17        | 17     | 0.66%   |
| SPCC                | 14        | 14     | 0.54%   |
| OCZ                 | 14        | 15     | 0.54%   |
| Patriot             | 13        | 16     | 0.5%    |
| JMicron Technology  | 12        | 12     | 0.47%   |
| Intenso             | 11        | 12     | 0.43%   |
| LITEON              | 10        | 10     | 0.39%   |
| Transcend           | 9         | 10     | 0.35%   |
| Phison              | 9         | 9      | 0.35%   |
| LITEONIT            | 9         | 10     | 0.35%   |
| Hewlett-Packard     | 7         | 7      | 0.27%   |
| Apacer              | 7         | 7      | 0.27%   |
| Unknown             | 6         | 6      | 0.23%   |
| Teclast             | 5         | 5      | 0.19%   |
| Union Memory        | 4         | 5      | 0.16%   |
| SABRENT             | 4         | 6      | 0.16%   |
| Plextor             | 4         | 4      | 0.16%   |
| KIOXIA              | 4         | 5      | 0.16%   |
| KingSpec            | 4         | 4      | 0.16%   |
| KingDian            | 4         | 4      | 0.16%   |
| Corsair             | 4         | 5      | 0.16%   |
| Colorful            | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 74        | 2.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 47        | 1.8%    |
| Toshiba MQ01ABF050 500GB            | 44        | 1.68%   |
| SanDisk SSD U100 256GB              | 44        | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 35        | 1.34%   |
| Toshiba MQ01ABD100 1TB              | 33        | 1.26%   |
| Seagate ST9500325AS 500GB           | 26        | 0.99%   |
| WDC WD10JPVX-22JC3T0 1TB            | 25        | 0.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 25        | 0.96%   |
| Kingston SA400S37240G 240GB SSD     | 24        | 0.92%   |
| Toshiba MQ04ABF100 1TB              | 23        | 0.88%   |
| Samsung SSD 860 EVO 500GB           | 21        | 0.8%    |
| Kingston SA400S37120G 120GB SSD     | 20        | 0.76%   |
| Kingston SA400S37480G 480GB SSD     | 19        | 0.73%   |
| HGST HTS545050A7E680 500GB          | 18        | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 17        | 0.65%   |
| Hitachi HTS547550A9E384 500GB       | 17        | 0.65%   |
| HGST HTS721010A9E630 1TB            | 17        | 0.65%   |
| Seagate ST500LT012-9WS142 500GB     | 16        | 0.61%   |
| HGST HTS541010A9E680 1TB            | 16        | 0.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 14        | 0.53%   |
| Crucial CT240BX500SSD1 240GB        | 14        | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB            | 13        | 0.5%    |
| Samsung SSD 850 EVO 500GB           | 13        | 0.5%    |
| HGST HTS545050A7E380 500GB          | 13        | 0.5%    |
| Toshiba MQ01ABD050 500GB            | 12        | 0.46%   |
| Seagate ST9320325AS 320GB           | 12        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD    | 12        | 0.46%   |
| Hitachi HTS545050A7E380 500GB       | 12        | 0.46%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 11        | 0.42%   |
| Samsung SSD 850 EVO 250GB           | 11        | 0.42%   |
| Hitachi HTS545025B9A300 250GB       | 11        | 0.42%   |
| Crucial CT500MX500SSD1 500GB        | 11        | 0.42%   |
| Seagate ST500LM021-1KJ152 500GB     | 10        | 0.38%   |
| PNY CS900 120GB SSD                 | 10        | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB            | 9         | 0.34%   |
| Unknown SD/MMC/MS PRO 128GB         | 9         | 0.34%   |
| SanDisk SSD PLUS 240GB              | 9         | 0.34%   |
| Hitachi HTS543232A7A384 320GB       | 9         | 0.34%   |
| HGST HTS725050A7E630 500GB          | 9         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 400       | 413    | 30.96%  |
| WDC                 | 329       | 341    | 25.46%  |
| Toshiba             | 240       | 249    | 18.58%  |
| Hitachi             | 146       | 150    | 11.3%   |
| HGST                | 87        | 90     | 6.73%   |
| Samsung Electronics | 29        | 30     | 2.24%   |
| Fujitsu             | 26        | 26     | 2.01%   |
| Unknown             | 9         | 9      | 0.7%    |
| JMicron Technology  | 8         | 8      | 0.62%   |
| Apple               | 8         | 8      | 0.62%   |
| SABRENT             | 3         | 5      | 0.23%   |
| External            | 2         | 2      | 0.15%   |
| TO Exter            | 1         | 1      | 0.08%   |
| Intenso             | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| ASMT                | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 187       | 201    | 19.58%  |
| Kingston            | 132       | 138    | 13.82%  |
| SanDisk             | 126       | 130    | 13.19%  |
| Crucial             | 68        | 71     | 7.12%   |
| WDC                 | 60        | 60     | 6.28%   |
| A-DATA Technology   | 37        | 37     | 3.87%   |
| Intel               | 26        | 28     | 2.72%   |
| Toshiba             | 25        | 27     | 2.62%   |
| SK hynix            | 21        | 22     | 2.2%    |
| GOODRAM             | 20        | 22     | 2.09%   |
| Micron Technology   | 17        | 17     | 1.78%   |
| China               | 17        | 17     | 1.78%   |
| PNY                 | 15        | 16     | 1.57%   |
| OCZ                 | 14        | 15     | 1.47%   |
| SPCC                | 13        | 13     | 1.36%   |
| Patriot             | 13        | 16     | 1.36%   |
| Intenso             | 10        | 11     | 1.05%   |
| Transcend           | 9         | 10     | 0.94%   |
| LITEONIT            | 9         | 10     | 0.94%   |
| LITEON              | 9         | 9      | 0.94%   |
| Apple               | 9         | 9      | 0.94%   |
| Unknown             | 8         | 8      | 0.84%   |
| Apacer              | 7         | 7      | 0.73%   |
| Hewlett-Packard     | 6         | 6      | 0.63%   |
| Teclast             | 5         | 5      | 0.52%   |
| Unknown             | 5         | 5      | 0.52%   |
| Plextor             | 4         | 4      | 0.42%   |
| KingSpec            | 4         | 4      | 0.42%   |
| KingDian            | 4         | 4      | 0.42%   |
| Colorful            | 4         | 4      | 0.42%   |
| Netac               | 3         | 3      | 0.31%   |
| Leven               | 3         | 3      | 0.31%   |
| KingFast            | 3         | 3      | 0.31%   |
| INNOVATION IT       | 3         | 3      | 0.31%   |
| Corsair             | 3         | 4      | 0.31%   |
| BHT                 | 3         | 3      | 0.31%   |
| Smartbuy            | 2         | 2      | 0.21%   |
| Seagate             | 2         | 2      | 0.21%   |
| Mushkin             | 2         | 2      | 0.21%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1259      | 1336   | 50.44%  |
| SSD     | 904       | 1000   | 36.22%  |
| NVMe    | 229       | 258    | 9.17%   |
| MMC     | 84        | 93     | 3.37%   |
| Unknown | 20        | 20     | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2003      | 2262   | 83.32%  |
| NVMe | 229       | 255    | 9.53%   |
| SAS  | 88        | 97     | 3.66%   |
| MMC  | 84        | 93     | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1614      | 1792   | 75.74%  |
| 0.51-1.0   | 476       | 501    | 22.34%  |
| 1.01-2.0   | 38        | 40     | 1.78%   |
| 3.01-4.0   | 3         | 3      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 1221      | 53.34%  |
| 101-250    | 355       | 15.51%  |
| 251-500    | 260       | 11.36%  |
| 51-100     | 121       | 5.29%   |
| Unknown    | 121       | 5.29%   |
| 501-1000   | 113       | 4.94%   |
| 21-50      | 79        | 3.45%   |
| 1001-2000  | 17        | 0.74%   |
| 2001-3000  | 2         | 0.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 1985      | 86.83%  |
| Unknown   | 121       | 5.29%   |
| 21-50     | 68        | 2.97%   |
| 101-250   | 42        | 1.84%   |
| 51-100    | 36        | 1.57%   |
| 251-500   | 23        | 1.01%   |
| 501-1000  | 8         | 0.35%   |
| 1001-2000 | 2         | 0.09%   |
| 0         | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 44        | 44     | 7.36%   |
| Seagate ST500LT012-1DG142 500GB     | 21        | 21     | 3.51%   |
| Seagate ST9500325AS 500GB           | 20        | 22     | 3.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 16     | 2.68%   |
| Seagate ST500LT012-9WS142 500GB     | 14        | 16     | 2.34%   |
| Toshiba MQ01ABF050 500GB            | 13        | 13     | 2.17%   |
| HGST HTS545050A7E680 500GB          | 11        | 11     | 1.84%   |
| Seagate ST9320325AS 320GB           | 10        | 10     | 1.67%   |
| Hitachi HTS545050A7E380 500GB       | 9         | 9      | 1.51%   |
| Hitachi HTS547550A9E384 500GB       | 8         | 9      | 1.34%   |
| HGST HTS541010A9E680 1TB            | 8         | 8      | 1.34%   |
| Toshiba MQ01ABD100 1TB              | 7         | 7      | 1.17%   |
| Toshiba MQ01ABD050 500GB            | 7         | 7      | 1.17%   |
| Toshiba MK3265GSX 320GB             | 7         | 7      | 1.17%   |
| Seagate ST9500420AS 500GB           | 7         | 7      | 1.17%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 6      | 1%      |
| WDC WD10JPVX-22JC3T0 1TB            | 6         | 6      | 1%      |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 6      | 1%      |
| Hitachi HTS547564A9E384 640GB       | 6         | 7      | 1%      |
| Hitachi HTS545025B9A300 250GB       | 6         | 6      | 1%      |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 1%      |
| HGST HTS545050A7E380 500GB          | 6         | 6      | 1%      |
| Toshiba MQ01ABD075 752GB            | 5         | 5      | 0.84%   |
| Seagate ST9250827AS 250GB           | 5         | 5      | 0.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 5      | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 5      | 0.84%   |
| Samsung Electronics HM641JI 640GB   | 5         | 5      | 0.84%   |
| Hitachi HTS542516K9SA00 160GB       | 5         | 5      | 0.84%   |
| HGST HTS541075A9E680 752GB          | 5         | 5      | 0.84%   |
| WDC WD3200BEVT-60A23T0 320GB        | 4         | 4      | 0.67%   |
| WDC WD10JPCX-24UE4T0 1TB            | 4         | 4      | 0.67%   |
| Seagate ST320LT007-9ZV142 320GB     | 4         | 4      | 0.67%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 0.67%   |
| Hitachi HTS543232A7A384 320GB       | 4         | 4      | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3         | 3      | 0.5%    |
| WDC WD5000BPVT-22HXZT3 500GB        | 3         | 4      | 0.5%    |
| WDC WD3200BEKT-60F3T1 320GB         | 3         | 3      | 0.5%    |
| WDC WD2500BEVS-60UST0 250GB         | 3         | 3      | 0.5%    |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 3      | 0.5%    |
| Toshiba MK5055GSX 500GB             | 3         | 3      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 157    | 25.46%  |
| WDC                 | 96        | 98     | 16.08%  |
| Toshiba             | 92        | 94     | 15.41%  |
| Hitachi             | 81        | 83     | 13.57%  |
| SanDisk             | 53        | 53     | 8.88%   |
| HGST                | 40        | 40     | 6.7%    |
| Samsung Electronics | 28        | 28     | 4.69%   |
| Kingston            | 11        | 12     | 1.84%   |
| Fujitsu             | 9         | 9      | 1.51%   |
| Intel               | 7         | 8      | 1.17%   |
| Crucial             | 4         | 4      | 0.67%   |
| SK hynix            | 3         | 3      | 0.5%    |
| OCZ                 | 3         | 4      | 0.5%    |
| A-DATA Technology   | 2         | 2      | 0.34%   |
| Unknown             | 1         | 1      | 0.17%   |
| Transcend           | 1         | 1      | 0.17%   |
| SPCC                | 1         | 1      | 0.17%   |
| Platinet            | 1         | 1      | 0.17%   |
| Netac               | 1         | 1      | 0.17%   |
| Micron Technology   | 1         | 1      | 0.17%   |
| LITEONIT            | 1         | 1      | 0.17%   |
| KingSpec            | 1         | 1      | 0.17%   |
| KingDian            | 1         | 1      | 0.17%   |
| Intenso             | 1         | 1      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| Colorful            | 1         | 1      | 0.17%   |
| China               | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |
| 240G                | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 157    | 31.4%   |
| Toshiba             | 92        | 94     | 19.01%  |
| WDC                 | 88        | 90     | 18.18%  |
| Hitachi             | 81        | 83     | 16.74%  |
| HGST                | 40        | 40     | 8.26%   |
| Samsung Electronics | 19        | 19     | 3.93%   |
| Fujitsu             | 9         | 9      | 1.86%   |
| IBM/Hitachi         | 1         | 1      | 0.21%   |
| ASMT                | 1         | 1      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 481       | 495    | 80.98%  |
| SSD  | 111       | 114    | 18.69%  |
| NVMe | 2         | 2      | 0.34%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 14.29%  |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 14.29%  |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 7.14%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 7.14%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 7.14%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 7.14%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 7.14%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 7.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 7.14%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 7.14%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 7.14%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 42.86%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Crucial             | 2         | 2      | 14.29%  |
| SK hynix            | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1621      | 1897   | 67.88%  |
| Malfunc  | 589       | 611    | 24.66%  |
| Detected | 164       | 185    | 6.87%   |
| Failed   | 14        | 14     | 0.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1826      | 76.27%  |
| AMD                              | 313       | 13.07%  |
| Samsung Electronics              | 73        | 3.05%   |
| SanDisk                          | 51        | 2.13%   |
| Nvidia                           | 26        | 1.09%   |
| SK hynix                         | 22        | 0.92%   |
| Kingston Technology Company      | 18        | 0.75%   |
| Phison Electronics               | 13        | 0.54%   |
| Toshiba America Info Systems     | 10        | 0.42%   |
| Union Memory (Shenzhen)          | 6         | 0.25%   |
| Micron Technology                | 5         | 0.21%   |
| Silicon Motion                   | 4         | 0.17%   |
| KIOXIA                           | 4         | 0.17%   |
| Micron/Crucial Technology        | 3         | 0.13%   |
| JMicron Technology               | 3         | 0.13%   |
| Apple                            | 3         | 0.13%   |
| Silicon Image                    | 2         | 0.08%   |
| Realtek Semiconductor            | 2         | 0.08%   |
| Marvell Technology Group         | 2         | 0.08%   |
| Lenovo                           | 2         | 0.08%   |
| ADATA Technology                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Lite-On Technology               | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| ASMedia Technology               | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 235       | 9%      |
| AMD FCH SATA Controller [AHCI mode]                                                    | 227       | 8.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 226       | 8.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 190       | 7.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 174       | 6.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 123       | 4.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 110       | 4.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 103       | 3.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 95        | 3.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 92        | 3.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 70        | 2.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 69        | 2.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 69        | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 53        | 2.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 49        | 1.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 37        | 1.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 36        | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 35        | 1.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 30        | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 28        | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 27        | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 22        | 0.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 21        | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 21        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 20        | 0.77%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 17        | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 17        | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                  | 15        | 0.57%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 15        | 0.57%   |
| Intel SSD 660P Series                                                                  | 15        | 0.57%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 14        | 0.54%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 14        | 0.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 13        | 0.5%    |
| Nvidia MCP79 AHCI Controller                                                           | 12        | 0.46%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 12        | 0.46%   |
| SK hynix BC511 NVMe SSD                                                                | 11        | 0.42%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 11        | 0.42%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 11        | 0.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 10        | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 9         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1928      | 76.21%  |
| IDE  | 232       | 9.17%   |
| NVMe | 230       | 9.09%   |
| RAID | 140       | 5.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1892      | 84.01%  |
| AMD    | 360       | 15.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 2.13%   |
| Intel Core i7-2677M CPU @ 1.80GHz             | 44        | 1.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 35        | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 1.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 28        | 1.24%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 27        | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 27        | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 26        | 1.15%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 25        | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 24        | 1.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 1.02%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 23        | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.98%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 22        | 0.98%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 20        | 0.89%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 19        | 0.84%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 19        | 0.84%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 19        | 0.84%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.8%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 18        | 0.8%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.8%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 17        | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 17        | 0.75%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 16        | 0.71%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 15        | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 14        | 0.62%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.62%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 14        | 0.62%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 14        | 0.62%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 14        | 0.62%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 13        | 0.58%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 13        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 13        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 13        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 545       | 24.2%   |
| Intel Core i7           | 331       | 14.7%   |
| Intel Core i3           | 305       | 13.54%  |
| Intel Core 2 Duo        | 224       | 9.95%   |
| Intel Celeron           | 207       | 9.19%   |
| Intel Pentium           | 107       | 4.75%   |
| AMD Ryzen 5             | 55        | 2.44%   |
| Intel Pentium Dual-Core | 54        | 2.4%    |
| Intel Pentium Dual      | 38        | 1.69%   |
| AMD E                   | 35        | 1.55%   |
| Other                   | 29        | 1.29%   |
| AMD E1                  | 28        | 1.24%   |
| AMD A6                  | 27        | 1.2%    |
| AMD A4                  | 27        | 1.2%    |
| AMD A8                  | 24        | 1.07%   |
| AMD Ryzen 7             | 21        | 0.93%   |
| AMD E2                  | 21        | 0.93%   |
| Intel Atom              | 20        | 0.89%   |
| AMD Ryzen 3             | 13        | 0.58%   |
| AMD A10                 | 13        | 0.58%   |
| AMD Athlon              | 12        | 0.53%   |
| Intel Core 2            | 11        | 0.49%   |
| AMD C-60                | 11        | 0.49%   |
| Intel Pentium Silver    | 10        | 0.44%   |
| Intel Celeron Dual-Core | 9         | 0.4%    |
| AMD Athlon X2           | 7         | 0.31%   |
| AMD Athlon II           | 6         | 0.27%   |
| Intel Genuine           | 5         | 0.22%   |
| AMD C-70                | 5         | 0.22%   |
| AMD Athlon 64 X2        | 5         | 0.22%   |
| AMD Turion II Dual-Core | 4         | 0.18%   |
| AMD Phenom II           | 4         | 0.18%   |
| AMD A12                 | 4         | 0.18%   |
| Intel Core m3           | 3         | 0.13%   |
| Intel Core 2 Extreme    | 3         | 0.13%   |
| Intel Core m7           | 2         | 0.09%   |
| AMD V120                | 2         | 0.09%   |
| AMD Turion II           | 2         | 0.09%   |
| AMD Sempron             | 2         | 0.09%   |
| AMD C-50                | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1714      | 76.11%  |
| 4      | 437       | 19.4%   |
| 1      | 44        | 1.95%   |
| 6      | 40        | 1.78%   |
| 8      | 15        | 0.67%   |
| 5      | 1         | 0.04%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2252      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1323      | 58.75%  |
| 1      | 929       | 41.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2251      | 99.96%  |
| Unknown        | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 292       | 12.96%  |
| 0x306a9    | 218       | 9.68%   |
| 0x1067a    | 165       | 7.32%   |
| 0x20655    | 119       | 5.28%   |
| 0x40651    | 114       | 5.06%   |
| 0x6fd      | 96        | 4.26%   |
| 0x406e3    | 94        | 4.17%   |
| 0x306d4    | 79        | 3.51%   |
| 0x806e9    | 72        | 3.2%    |
| 0x30678    | 67        | 2.97%   |
| 0x10676    | 58        | 2.57%   |
| 0x306c3    | 57        | 2.53%   |
| 0x806ea    | 55        | 2.44%   |
| Unknown    | 52        | 2.31%   |
| 0x806ec    | 38        | 1.69%   |
| 0x406c4    | 37        | 1.64%   |
| 0x06006705 | 33        | 1.46%   |
| 0x20652    | 31        | 1.38%   |
| 0x706a1    | 30        | 1.33%   |
| 0x706e5    | 29        | 1.29%   |
| 0x506c9    | 29        | 1.29%   |
| 0x07030105 | 29        | 1.29%   |
| 0x906ea    | 28        | 1.24%   |
| 0x08108109 | 28        | 1.24%   |
| 0x0500010d | 27        | 1.2%    |
| 0x08108102 | 25        | 1.11%   |
| 0x506e3    | 19        | 0.84%   |
| 0x05000119 | 18        | 0.8%    |
| 0x906e9    | 16        | 0.71%   |
| 0x6fb      | 16        | 0.71%   |
| 0x806c1    | 14        | 0.62%   |
| 0x706a8    | 12        | 0.53%   |
| 0x106e5    | 11        | 0.49%   |
| 0x05000101 | 11        | 0.49%   |
| 0xa0652    | 10        | 0.44%   |
| 0x6f6      | 10        | 0.44%   |
| 0x07030104 | 10        | 0.44%   |
| 0x06001119 | 10        | 0.44%   |
| 0x05000028 | 10        | 0.44%   |
| 0x6fa      | 9         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 294       | 13.06%  |
| Penryn          | 223       | 9.9%    |
| IvyBridge       | 220       | 9.77%   |
| KabyLake        | 219       | 9.72%   |
| Haswell         | 173       | 7.68%   |
| Westmere        | 152       | 6.75%   |
| Core            | 139       | 6.17%   |
| Silvermont      | 118       | 5.24%   |
| Skylake         | 116       | 5.15%   |
| Broadwell       | 80        | 3.55%   |
| Bobcat          | 71        | 3.15%   |
| Zen+            | 60        | 2.66%   |
| Excavator       | 51        | 2.26%   |
| Puma            | 44        | 1.95%   |
| Goldmont plus   | 42        | 1.87%   |
| IceLake         | 30        | 1.33%   |
| Goldmont        | 30        | 1.33%   |
| Zen 2           | 23        | 1.02%   |
| K10             | 22        | 0.98%   |
| Jaguar          | 19        | 0.84%   |
| Piledriver      | 17        | 0.75%   |
| CometLake       | 16        | 0.71%   |
| Zen             | 15        | 0.67%   |
| Bonnell         | 15        | 0.67%   |
| TigerLake       | 14        | 0.62%   |
| Nehalem         | 11        | 0.49%   |
| K8 Hammer       | 11        | 0.49%   |
| K8 & K10 hybrid | 10        | 0.44%   |
| K10 Llano       | 8         | 0.36%   |
| Steamroller     | 6         | 0.27%   |
| Unknown         | 3         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1661      | 62.44%  |
| AMD                              | 522       | 19.62%  |
| Nvidia                           | 476       | 17.89%  |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 271       | 9.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 203       | 7.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 151       | 5.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 113       | 4.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 4.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 83        | 2.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 2.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 2.84%   |
| Intel HD Graphics 620                                                                    | 74        | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 72        | 2.59%   |
| Intel HD Graphics 5500                                                                   | 69        | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 60        | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.8%    |
| Intel UHD Graphics 620                                                                   | 47        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 1.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 41        | 1.47%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 38        | 1.36%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 32        | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 0.93%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26        | 0.93%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 25        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 23        | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 23        | 0.83%   |
| Intel HD Graphics 500                                                                    | 22        | 0.79%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 22        | 0.79%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 0.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 20        | 0.72%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 20        | 0.72%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 0.68%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 18        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.61%   |
| Intel HD Graphics 530                                                                    | 17        | 0.61%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 16        | 0.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.54%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 14        | 0.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.5%    |
| Intel HD Graphics 630                                                                    | 13        | 0.47%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 13        | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1268      | 56.31%  |
| 1 x AMD        | 390       | 17.32%  |
| Intel + Nvidia | 316       | 14.03%  |
| 1 x Nvidia     | 141       | 6.26%   |
| Intel + AMD    | 77        | 3.42%   |
| 2 x AMD        | 40        | 1.78%   |
| AMD + Nvidia   | 15        | 0.67%   |
| 2 x Nvidia     | 4         | 0.18%   |
| 1 x SiS        | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2237      | 99.29%  |
| Unknown     | 14        | 0.62%   |
| Proprietary | 2         | 0.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1303      | 57.86%  |
| 0.01-0.5   | 385       | 17.1%   |
| 1.01-2.0   | 266       | 11.81%  |
| 0.51-1.0   | 207       | 9.19%   |
| 3.01-4.0   | 59        | 2.62%   |
| 5.01-6.0   | 16        | 0.71%   |
| 7.01-8.0   | 9         | 0.4%    |
| 2.01-3.0   | 7         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 466       | 20.61%  |
| LG Display              | 389       | 17.2%   |
| Samsung Electronics     | 313       | 13.84%  |
| BOE                     | 300       | 13.27%  |
| Chimei Innolux          | 296       | 13.09%  |
| Chi Mei Optoelectronics | 107       | 4.73%   |
| Lenovo                  | 68        | 3.01%   |
| CPT                     | 57        | 2.52%   |
| LG Philips              | 41        | 1.81%   |
| Apple                   | 38        | 1.68%   |
| Goldstar                | 16        | 0.71%   |
| Sharp                   | 15        | 0.66%   |
| Dell                    | 15        | 0.66%   |
| InfoVision              | 14        | 0.62%   |
| Acer                    | 14        | 0.62%   |
| PANDA                   | 12        | 0.53%   |
| Sony                    | 10        | 0.44%   |
| Philips                 | 10        | 0.44%   |
| InnoLux Display         | 8         | 0.35%   |
| Hewlett-Packard         | 7         | 0.31%   |
| BenQ                    | 7         | 0.31%   |
| ViewSonic               | 5         | 0.22%   |
| Iiyama                  | 5         | 0.22%   |
| Ancor Communications    | 5         | 0.22%   |
| Panasonic               | 4         | 0.18%   |
| AOC                     | 4         | 0.18%   |
| Toshiba                 | 3         | 0.13%   |
| HannStar                | 3         | 0.13%   |
| Fujitsu Siemens         | 3         | 0.13%   |
| Eizo                    | 3         | 0.13%   |
| Unknown                 | 2         | 0.09%   |
| Quanta Display          | 2         | 0.09%   |
| ASUSTek Computer        | 2         | 0.09%   |
| Westinghouse            | 1         | 0.04%   |
| Vizio                   | 1         | 0.04%   |
| Vestel Elektronik       | 1         | 0.04%   |
| SNC                     | 1         | 0.04%   |
| S2-Tek                  | 1         | 0.04%   |
| RTK                     | 1         | 0.04%   |
| ONN                     | 1         | 0.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 44        | 1.94%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 34        | 1.5%    |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 1.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 25        | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 22        | 0.97%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 21        | 0.93%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 19        | 0.84%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 19        | 0.84%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 18        | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 15        | 0.66%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 15        | 0.66%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.66%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 14        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 13        | 0.57%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 13        | 0.57%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 12        | 0.53%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.53%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 11        | 0.49%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.49%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 11        | 0.49%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 10        | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 10        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 0.44%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 10        | 0.44%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 10        | 0.44%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.44%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.44%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 10        | 0.44%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 9         | 0.4%    |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 9         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 9         | 0.4%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 9         | 0.4%    |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 9         | 0.4%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 9         | 0.4%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 9         | 0.4%    |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 8         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1092      | 48.82%  |
| 1920x1080 (FHD)    | 541       | 24.18%  |
| 1600x900 (HD+)     | 232       | 10.37%  |
| 1280x800 (WXGA)    | 166       | 7.42%   |
| 1440x900 (WXGA+)   | 64        | 2.86%   |
| 3840x2160 (4K)     | 24        | 1.07%   |
| 1680x1050 (WSXGA+) | 24        | 1.07%   |
| 1920x1200 (WUXGA)  | 22        | 0.98%   |
| 2560x1440 (QHD)    | 12        | 0.54%   |
| 1024x600           | 11        | 0.49%   |
| 1280x1024 (SXGA)   | 7         | 0.31%   |
| 1024x768 (XGA)     | 7         | 0.31%   |
| 2560x1600          | 5         | 0.22%   |
| 1680x945           | 5         | 0.22%   |
| 2880x1800          | 4         | 0.18%   |
| 3200x1800 (QHD+)   | 3         | 0.13%   |
| 1360x768           | 3         | 0.13%   |
| 2560x1080          | 2         | 0.09%   |
| 2160x1440          | 2         | 0.09%   |
| 1920x540           | 2         | 0.09%   |
| 1400x1050          | 2         | 0.09%   |
| 3840x1100          | 1         | 0.04%   |
| 3300x2200          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 2256x1504          | 1         | 0.04%   |
| 1280x720 (HD)      | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1125      | 49.63%  |
| 13      | 344       | 15.17%  |
| 14      | 260       | 11.47%  |
| 17      | 241       | 10.63%  |
| 12      | 65        | 2.87%   |
| 11      | 41        | 1.81%   |
| 23      | 26        | 1.15%   |
| 18      | 21        | 0.93%   |
| 27      | 20        | 0.88%   |
| 21      | 16        | 0.71%   |
| 31      | 15        | 0.66%   |
| 24      | 14        | 0.62%   |
| 10      | 14        | 0.62%   |
| 20      | 12        | 0.53%   |
| 16      | 10        | 0.44%   |
| 22      | 8         | 0.35%   |
| 54      | 7         | 0.31%   |
| 19      | 4         | 0.18%   |
| 84      | 3         | 0.13%   |
| 72      | 3         | 0.13%   |
| 46      | 3         | 0.13%   |
| 25      | 3         | 0.13%   |
| 48      | 2         | 0.09%   |
| 34      | 2         | 0.09%   |
| 32      | 2         | 0.09%   |
| Unknown | 2         | 0.09%   |
| 142     | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 26      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1537      | 68.07%  |
| 351-400        | 296       | 13.11%  |
| 201-300        | 264       | 11.69%  |
| 501-600        | 62        | 2.75%   |
| 401-500        | 56        | 2.48%   |
| 601-700        | 16        | 0.71%   |
| 1001-1500      | 12        | 0.53%   |
| 1501-2000      | 6         | 0.27%   |
| 701-800        | 4         | 0.18%   |
| Unknown        | 2         | 0.09%   |
| More than 2000 | 1         | 0.04%   |
| 801-900        | 1         | 0.04%   |
| 901-1000       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 1851      | 85.5%   |
| 16/10 | 283       | 13.07%  |
| 3/2   | 10        | 0.46%   |
| 4/3   | 9         | 0.42%   |
| 5/4   | 8         | 0.37%   |
| 21/9  | 2         | 0.09%   |
| 3.40  | 1         | 0.05%   |
| 1.00  | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1121      | 49.47%  |
| 81-90          | 482       | 21.27%  |
| 121-130        | 193       | 8.52%   |
| 71-80          | 119       | 5.25%   |
| 61-70          | 63        | 2.78%   |
| 201-250        | 61        | 2.69%   |
| 131-140        | 45        | 1.99%   |
| 51-60          | 43        | 1.9%    |
| 141-150        | 25        | 1.1%    |
| 301-350        | 20        | 0.88%   |
| 351-500        | 19        | 0.84%   |
| 151-200        | 19        | 0.84%   |
| More than 1000 | 16        | 0.71%   |
| 41-50          | 13        | 0.57%   |
| 91-100         | 10        | 0.44%   |
| 111-120        | 6         | 0.26%   |
| 501-1000       | 5         | 0.22%   |
| 251-300        | 4         | 0.18%   |
| Unknown        | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1163      | 51.83%  |
| 121-160       | 630       | 28.07%  |
| 51-100        | 367       | 16.35%  |
| 161-240       | 49        | 2.18%   |
| 1-50          | 18        | 0.8%    |
| More than 240 | 15        | 0.67%   |
| Unknown       | 2         | 0.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2103      | 93.18%  |
| 2     | 143       | 6.34%   |
| 0     | 10        | 0.44%   |
| 3     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1229      | 32.79%  |
| Intel                             | 921       | 24.57%  |
| Qualcomm Atheros                  | 857       | 22.87%  |
| Broadcom                          | 272       | 7.26%   |
| Marvell Technology Group          | 70        | 1.87%   |
| Broadcom Limited                  | 68        | 1.81%   |
| Samsung Electronics               | 52        | 1.39%   |
| Ralink                            | 47        | 1.25%   |
| Huawei Technologies               | 35        | 0.93%   |
| JMicron Technology                | 31        | 0.83%   |
| Dell                              | 22        | 0.59%   |
| Ericsson Business Mobile Networks | 18        | 0.48%   |
| Nvidia                            | 15        | 0.4%    |
| Ralink Technology                 | 12        | 0.32%   |
| MediaTek                          | 10        | 0.27%   |
| Qualcomm Atheros Communications   | 9         | 0.24%   |
| TP-Link                           | 8         | 0.21%   |
| Sierra Wireless                   | 7         | 0.19%   |
| Xiaomi                            | 6         | 0.16%   |
| Motorola PCS                      | 5         | 0.13%   |
| Hewlett-Packard                   | 5         | 0.13%   |
| DisplayLink                       | 5         | 0.13%   |
| D-Link                            | 5         | 0.13%   |
| ASIX Electronics                  | 5         | 0.13%   |
| Qualcomm                          | 3         | 0.08%   |
| NetGear                           | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| Sitecom Europe                    | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |
| Edimax Technology                 | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| Apple                             | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |
| Qcom                              | 1         | 0.03%   |
| Lenovo                            | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 713       | 16.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 369       | 8.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 177       | 3.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 152       | 3.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 149       | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 131       | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 103       | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 87        | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 76        | 1.71%   |
| Intel Wireless 7265                                                     | 60        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 54        | 1.21%   |
| Intel Wireless 7260                                                     | 52        | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 51        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 50        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 50        | 1.12%   |
| Intel WiFi Link 5100                                                    | 50        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 47        | 1.06%   |
| Intel 82577LM Gigabit Network Connection                                | 44        | 0.99%   |
| Intel Wireless 8265 / 8275                                              | 42        | 0.94%   |
| Intel 82567LM Gigabit Network Connection                                | 42        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 38        | 0.85%   |
| Intel Wireless 8260                                                     | 37        | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 34        | 0.76%   |
| Huawei E353/E3131                                                       | 32        | 0.72%   |
| Intel Wireless 3160                                                     | 31        | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 0.67%   |
| Intel Wireless 3165                                                     | 30        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 29        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 29        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 29        | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 29        | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 28        | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 28        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 0.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 866       | 37.75%  |
| Qualcomm Atheros                | 765       | 33.35%  |
| Realtek Semiconductor           | 358       | 15.61%  |
| Broadcom                        | 163       | 7.11%   |
| Ralink                          | 47        | 2.05%   |
| Broadcom Limited                | 30        | 1.31%   |
| Ralink Technology               | 12        | 0.52%   |
| Dell                            | 11        | 0.48%   |
| Qualcomm Atheros Communications | 9         | 0.39%   |
| Sierra Wireless                 | 7         | 0.31%   |
| MediaTek                        | 6         | 0.26%   |
| TP-Link                         | 5         | 0.22%   |
| NetGear                         | 3         | 0.13%   |
| Linksys                         | 2         | 0.09%   |
| Edimax Technology               | 2         | 0.09%   |
| D-Link                          | 2         | 0.09%   |
| ASUSTek Computer                | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| AVM                             | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 177       | 7.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 152       | 6.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 149       | 6.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 131       | 5.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 87        | 3.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 76        | 3.3%    |
| Intel Wireless 7265                                                     | 60        | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 54        | 2.35%   |
| Intel Wireless 7260                                                     | 52        | 2.26%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 51        | 2.22%   |
| Intel WiFi Link 5100                                                    | 50        | 2.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 47        | 2.04%   |
| Intel Wireless 8265 / 8275                                              | 42        | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 1.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 1.7%    |
| Intel Centrino Advanced-N 6200                                          | 38        | 1.65%   |
| Intel Wireless 8260                                                     | 37        | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 1.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 34        | 1.48%   |
| Intel Wireless 3160                                                     | 31        | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 1.3%    |
| Intel Wireless 3165                                                     | 30        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 29        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 29        | 1.26%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 29        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 28        | 1.22%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 1.22%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 26        | 1.13%   |
| Intel Wi-Fi 6 AX200                                                     | 25        | 1.09%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 24        | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 21        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 21        | 0.91%   |
| Intel Centrino Wireless-N 2230                                          | 20        | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 19        | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 18        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 18        | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1121      | 53.3%   |
| Intel                            | 355       | 16.88%  |
| Qualcomm Atheros                 | 196       | 9.32%   |
| Broadcom                         | 142       | 6.75%   |
| Marvell Technology Group         | 70        | 3.33%   |
| Samsung Electronics              | 50        | 2.38%   |
| Broadcom Limited                 | 40        | 1.9%    |
| Huawei Technologies              | 34        | 1.62%   |
| JMicron Technology               | 31        | 1.47%   |
| Nvidia                           | 14        | 0.67%   |
| Xiaomi                           | 6         | 0.29%   |
| Motorola PCS                     | 5         | 0.24%   |
| DisplayLink                      | 5         | 0.24%   |
| ASIX Electronics                 | 5         | 0.24%   |
| MediaTek                         | 4         | 0.19%   |
| TP-Link                          | 3         | 0.14%   |
| Qualcomm                         | 3         | 0.14%   |
| D-Link                           | 3         | 0.14%   |
| OPPO Electronics                 | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 1         | 0.05%   |
| T & A Mobile Phones              | 1         | 0.05%   |
| Sitecom Europe                   | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Linksys                          | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Attansic Technology              | 1         | 0.05%   |
| Archos                           | 1         | 0.05%   |
| Allwinner Technology             | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 713       | 33.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 369       | 17.47%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 103       | 4.88%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 50        | 2.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 50        | 2.37%   |
| Intel 82577LM Gigabit Network Connection                                       | 44        | 2.08%   |
| Intel 82567LM Gigabit Network Connection                                       | 42        | 1.99%   |
| Huawei E353/E3131                                                              | 32        | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 28        | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 24        | 1.14%   |
| Intel Ethernet Connection I218-LM                                              | 21        | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                                          | 20        | 0.95%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 20        | 0.95%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 20        | 0.95%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 19        | 0.9%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 18        | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 17        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 16        | 0.76%   |
| Intel Ethernet Connection I219-LM                                              | 15        | 0.71%   |
| Intel 82566MM Gigabit Network Connection                                       | 15        | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 14        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 13        | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 13        | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 13        | 0.62%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 0.62%   |
| Intel 82579V Gigabit Network Connection                                        | 13        | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 13        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 13        | 0.62%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 12        | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 12        | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 12        | 0.57%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 12        | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 10        | 0.47%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 0.47%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 10        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 9         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 9         | 0.43%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 9         | 0.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 9         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2232      | 51.58%  |
| Ethernet | 2055      | 47.49%  |
| Modem    | 39        | 0.9%    |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1522      | 68.34%  |
| Ethernet | 705       | 31.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1891      | 83.97%  |
| 1     | 346       | 15.36%  |
| 0     | 10        | 0.44%   |
| 3     | 5         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1778      | 78.53%  |
| Yes  | 486       | 21.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 469       | 30.98%  |
| Qualcomm Atheros Communications | 236       | 15.59%  |
| Realtek Semiconductor           | 169       | 11.16%  |
| Broadcom                        | 125       | 8.26%   |
| Lite-On Technology              | 119       | 7.86%   |
| Foxconn / Hon Hai               | 69        | 4.56%   |
| IMC Networks                    | 64        | 4.23%   |
| Dell                            | 54        | 3.57%   |
| Toshiba                         | 40        | 2.64%   |
| Apple                           | 34        | 2.25%   |
| Hewlett-Packard                 | 31        | 2.05%   |
| Cambridge Silicon Radio         | 23        | 1.52%   |
| Ralink                          | 21        | 1.39%   |
| Realtek                         | 10        | 0.66%   |
| Foxconn International           | 10        | 0.66%   |
| Chicony Electronics             | 8         | 0.53%   |
| ASUSTek Computer                | 8         | 0.53%   |
| Alps Electric                   | 7         | 0.46%   |
| Ralink Technology               | 6         | 0.4%    |
| Askey Computer                  | 4         | 0.26%   |
| Taiyo Yuden                     | 3         | 0.2%    |
| Micro Star International        | 2         | 0.13%   |
| MediaTek                        | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 273       | 18.03%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 116       | 7.66%   |
| Realtek Bluetooth Radio                                                             | 84        | 5.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 52        | 3.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 49        | 3.24%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 48        | 3.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 43        | 2.84%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 43        | 2.84%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 34        | 2.25%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 34        | 2.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 31        | 2.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 28        | 1.85%   |
| Intel AX201 Bluetooth                                                               | 26        | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 26        | 1.72%   |
| Intel AX200 Bluetooth                                                               | 25        | 1.65%   |
| Dell DW375 Bluetooth Module                                                         | 25        | 1.65%   |
| IMC Networks Bluetooth Device                                                       | 23        | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 23        | 1.52%   |
| Apple Bluetooth Host Controller                                                     | 23        | 1.52%   |
| Lite-On Bluetooth Device                                                            | 22        | 1.45%   |
| Ralink RT3290 Bluetooth                                                             | 21        | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 21        | 1.39%   |
| Realtek RTL8723B Bluetooth                                                          | 19        | 1.25%   |
| IMC Networks Bluetooth Radio                                                        | 19        | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 18        | 1.19%   |
| Toshiba Bluetooth Device                                                            | 16        | 1.06%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 16        | 1.06%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 16        | 1.06%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 14        | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 14        | 0.92%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 14        | 0.92%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 13        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 0.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 11        | 0.73%   |
| Dell Wireless 360 Bluetooth                                                         | 11        | 0.73%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 11        | 0.73%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 0.73%   |
| Toshiba Integrated Bluetooth HCI                                                    | 10        | 0.66%   |
| Realtek Bluetooth Radio                                                             | 10        | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1871      | 72.41%  |
| AMD                                  | 430       | 16.64%  |
| Nvidia                               | 244       | 9.44%   |
| Creative Technology                  | 5         | 0.19%   |
| JMTek                                | 4         | 0.15%   |
| C-Media Electronics                  | 4         | 0.15%   |
| Logitech                             | 3         | 0.12%   |
| Texas Instruments                    | 2         | 0.08%   |
| Realtek Semiconductor                | 2         | 0.08%   |
| ASUSTek Computer                     | 2         | 0.08%   |
| Yamaha                               | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| TerraTec Electronic                  | 1         | 0.04%   |
| TEAC                                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.04%   |
| Razer USA                            | 1         | 0.04%   |
| Plantronics                          | 1         | 0.04%   |
| Phison Electronics                   | 1         | 0.04%   |
| M-Audio                              | 1         | 0.04%   |
| Lenovo                               | 1         | 0.04%   |
| GN Netcom                            | 1         | 0.04%   |
| Focusrite-Novation                   | 1         | 0.04%   |
| Elitegroup Computer Systems (ECS)    | 1         | 0.04%   |
| Corsair                              | 1         | 0.04%   |
| Bose                                 | 1         | 0.04%   |
| AudioQuest                           | 1         | 0.04%   |
| Apple                                | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 268       | 8.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 246       | 7.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 228       | 7.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 212       | 6.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 163       | 5.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 120       | 3.81%   |
| AMD FCH Azalia Controller                                                                         | 120       | 3.81%   |
| Intel 8 Series HD Audio Controller                                                                | 114       | 3.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 112       | 3.56%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 100       | 3.18%   |
| Intel Broadwell-U Audio Controller                                                                | 80        | 2.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 79        | 2.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 79        | 2.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 73        | 2.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 72        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 68        | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 60        | 1.91%   |
| AMD Wrestler HDMI Audio                                                                           | 58        | 1.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 57        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 53        | 1.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 51        | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 45        | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 41        | 1.3%    |
| AMD High Definition Audio Controller                                                              | 41        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 30        | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 30        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 0.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 28        | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 0.6%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 19        | 0.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 19        | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 18        | 0.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 0.57%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 0.57%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 0.54%   |
| AMD Trinity HDMI Audio Controller                                                                 | 17        | 0.54%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 16        | 0.51%   |
| Intel CM238 HD Audio Controller                                                                   | 16        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 705       | 26.3%   |
| SK hynix            | 545       | 20.33%  |
| Unknown             | 273       | 10.18%  |
| Kingston            | 251       | 9.36%   |
| Micron Technology   | 224       | 8.36%   |
| Elpida              | 139       | 5.18%   |
| Crucial             | 75        | 2.8%    |
| Ramaxel Technology  | 73        | 2.72%   |
| Nanya Technology    | 70        | 2.61%   |
| A-DATA Technology   | 64        | 2.39%   |
| Smart               | 43        | 1.6%    |
| Corsair             | 27        | 1.01%   |
| Unknown (ABCD)      | 22        | 0.82%   |
| Transcend           | 18        | 0.67%   |
| ASint Technology    | 15        | 0.56%   |
| High Bridge         | 13        | 0.48%   |
| G.Skill             | 13        | 0.48%   |
| Teikon              | 11        | 0.41%   |
| Apacer              | 11        | 0.41%   |
| Toshiba             | 9         | 0.34%   |
| AMD                 | 8         | 0.3%    |
| Patriot             | 7         | 0.26%   |
| Qimonda             | 6         | 0.22%   |
| Team                | 5         | 0.19%   |
| Smart Brazil        | 5         | 0.19%   |
| Silicon Power       | 4         | 0.15%   |
| PNY                 | 4         | 0.15%   |
| Unknown             | 4         | 0.15%   |
| SHARETRONIC         | 3         | 0.11%   |
| Qumo                | 2         | 0.07%   |
| Kingmax             | 2         | 0.07%   |
| GOODRAM             | 2         | 0.07%   |
| CSX                 | 2         | 0.07%   |
| Carry               | 2         | 0.07%   |
| A Force             | 2         | 0.07%   |
| ZIFEI               | 1         | 0.04%   |
| Visipro             | 1         | 0.04%   |
| V-GeN               | 1         | 0.04%   |
| Unknown (AB)        | 1         | 0.04%   |
| Unknown (8A02)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 58        | 2.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 50        | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 1.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 45        | 1.58%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 45        | 1.58%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 43        | 1.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 41        | 1.44%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 35        | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 34        | 1.19%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 0.98%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 27        | 0.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 25        | 0.88%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 24        | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 23        | 0.81%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.81%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 23        | 0.81%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 23        | 0.81%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 21        | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 20        | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 18        | 0.63%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.63%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 17        | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 16        | 0.56%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 16        | 0.56%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 16        | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 15        | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 14        | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 14        | 0.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 14        | 0.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 0.49%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 14        | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 13        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 13        | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1271      | 56.41%  |
| DDR4    | 510       | 22.64%  |
| DDR2    | 280       | 12.43%  |
| SDRAM   | 96        | 4.26%   |
| LPDDR4  | 47        | 2.09%   |
| Unknown | 22        | 0.98%   |
| LPDDR3  | 16        | 0.71%   |
| DRAM    | 6         | 0.27%   |
| DDR     | 5         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2137      | 96.92%  |
| Row Of Chips | 48        | 2.18%   |
| DIMM         | 10        | 0.45%   |
| Chip         | 7         | 0.32%   |
| Unknown      | 3         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1109      | 43.85%  |
| 2048  | 632       | 24.99%  |
| 8192  | 545       | 21.55%  |
| 1024  | 122       | 4.82%   |
| 16384 | 95        | 3.76%   |
| 32768 | 22        | 0.87%   |
| 512   | 4         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 775       | 30.73%  |
| 2667    | 301       | 11.93%  |
| 1334    | 278       | 11.02%  |
| 1333    | 201       | 7.97%   |
| 2400    | 166       | 6.58%   |
| 667     | 150       | 5.95%   |
| 1067    | 86        | 3.41%   |
| 3200    | 84        | 3.33%   |
| Unknown | 81        | 3.21%   |
| 800     | 71        | 2.82%   |
| 2133    | 65        | 2.58%   |
| 4199    | 56        | 2.22%   |
| 3266    | 43        | 1.7%    |
| 2048    | 35        | 1.39%   |
| 975     | 32        | 1.27%   |
| 1066    | 26        | 1.03%   |
| 533     | 22        | 0.87%   |
| 1867    | 20        | 0.79%   |
| 4267    | 5         | 0.2%    |
| 1639    | 5         | 0.2%    |
| 8400    | 3         | 0.12%   |
| 400     | 3         | 0.12%   |
| 333     | 3         | 0.12%   |
| 2933    | 2         | 0.08%   |
| 2267    | 2         | 0.08%   |
| 266     | 2         | 0.08%   |
| 3733    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1200    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 37.5%   |
| Samsung Electronics   | 5         | 20.83%  |
| Seiko Epson           | 3         | 12.5%   |
| Canon                 | 3         | 12.5%   |
| Brother Industries    | 2         | 8.33%   |
| Xerox                 | 1         | 4.17%   |
| Lexmark International | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer    | 3         | 12.5%   |
| HP LaserJet 1020                        | 2         | 8.33%   |
| HP DeskJet 3630 series                  | 2         | 8.33%   |
| Xerox Phaser 6000B                      | 1         | 4.17%   |
| Seiko Epson L360 Series                 | 1         | 4.17%   |
| Seiko Epson L312 Series                 | 1         | 4.17%   |
| Seiko Epson L210 Series                 | 1         | 4.17%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.17%   |
| Samsung M2070 Series                    | 1         | 4.17%   |
| Lexmark International E360d             | 1         | 4.17%   |
| HP LaserJet 200 colorMFP M275nw         | 1         | 4.17%   |
| HP ENVY Photo 6200 series               | 1         | 4.17%   |
| HP ENVY 6000 series                     | 1         | 4.17%   |
| HP ENVY 4520 series                     | 1         | 4.17%   |
| HP DeskJet 2130 series                  | 1         | 4.17%   |
| Canon PIXMA MG3500 Series               | 1         | 4.17%   |
| Canon PIXMA MG2500 Series               | 1         | 4.17%   |
| Canon LBP2900                           | 1         | 4.17%   |
| Brother MFC-J5330DW                     | 1         | 4.17%   |
| Brother DCP-L3550CDW                    | 1         | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 5590               | 2         | 40%     |
| Seiko Epson Scanner           | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 20%     |
| Canon CanoScan LiDE 110       | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 549       | 29.02%  |
| Suyin                                  | 180       | 9.51%   |
| IMC Networks                           | 143       | 7.56%   |
| Realtek Semiconductor                  | 138       | 7.29%   |
| Microdia                               | 129       | 6.82%   |
| Bison Electronics                      | 119       | 6.29%   |
| Sunplus Innovation Technology          | 91        | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 80        | 4.23%   |
| Quanta                                 | 71        | 3.75%   |
| Syntek                                 | 65        | 3.44%   |
| Silicon Motion                         | 45        | 2.38%   |
| Lite-On Technology                     | 40        | 2.11%   |
| Ricoh                                  | 38        | 2.01%   |
| Alcor Micro                            | 36        | 1.9%    |
| Apple                                  | 30        | 1.59%   |
| Lenovo                                 | 23        | 1.22%   |
| Acer                                   | 22        | 1.16%   |
| Primax Electronics                     | 15        | 0.79%   |
| Importek                               | 15        | 0.79%   |
| OmniVision Technologies                | 9         | 0.48%   |
| Luxvisions Innotech Limited            | 9         | 0.48%   |
| DigiTech                               | 9         | 0.48%   |
| ALi                                    | 9         | 0.48%   |
| Z-Star Microelectronics                | 5         | 0.26%   |
| Foxconn / Hon Hai                      | 3         | 0.16%   |
| Samsung Electronics                    | 2         | 0.11%   |
| Logitech                               | 2         | 0.11%   |
| Genesys Logic                          | 2         | 0.11%   |
| WaveRider Communications               | 1         | 0.05%   |
| Sunplus Technology                     | 1         | 0.05%   |
| Pixart Imaging                         | 1         | 0.05%   |
| Nokia Mobile Phones                    | 1         | 0.05%   |
| Nebraska Furniture Mart                | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| lihappe8                               | 1         | 0.05%   |
| JMicron Technology                     | 1         | 0.05%   |
| Intel                                  | 1         | 0.05%   |
| GEMBIRD                                | 1         | 0.05%   |
| Cubeternet                             | 1         | 0.05%   |
| Creative Technology                    | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                       | 56        | 2.96%   |
| Chicony Integrated Camera                               | 45        | 2.38%   |
| Suyin Integrated_Webcam_HD                              | 35        | 1.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 35        | 1.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 31        | 1.64%   |
| Realtek Integrated_Webcam_HD                            | 28        | 1.48%   |
| Chicony USB 2.0 Camera                                  | 27        | 1.43%   |
| Microdia Integrated_Webcam_HD                           | 25        | 1.32%   |
| Chicony USB2.0 HD UVC WebCam                            | 25        | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 24        | 1.27%   |
| Chicony VGA WebCam                                      | 23        | 1.22%   |
| Chicony EasyCamera                                      | 22        | 1.16%   |
| Syntek Lenovo EasyCamera                                | 21        | 1.11%   |
| Sunplus Integrated_Webcam_HD                            | 21        | 1.11%   |
| Quanta HP Webcam                                        | 21        | 1.11%   |
| Microdia Integrated Webcam                              | 21        | 1.11%   |
| Syntek Integrated Camera                                | 20        | 1.06%   |
| Chicony HP TrueVision HD                                | 20        | 1.06%   |
| Bison Lenovo EasyCamera                                 | 20        | 1.06%   |
| Bison Integrated Camera                                 | 20        | 1.06%   |
| Sunplus HD WebCam                                       | 19        | 1%      |
| Chicony TOSHIBA Web Camera - HD                         | 19        | 1%      |
| Realtek USB Camera                                      | 18        | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.95%   |
| Lite-On Integrated Camera                               | 17        | 0.9%    |
| Chicony Lenovo EasyCamera                               | 17        | 0.9%    |
| Quanta VGA WebCam                                       | 16        | 0.85%   |
| Suyin HP Truevision HD                                  | 15        | 0.79%   |
| IMC Networks UVC VGA Webcam                             | 15        | 0.79%   |
| Chicony Webcam                                          | 15        | 0.79%   |
| Chicony USB2.0 VGA UVC WebCam                           | 15        | 0.79%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.79%   |
| Chicony Acer CrystalEye Webcam                          | 15        | 0.79%   |
| Bison EasyCamera                                        | 15        | 0.79%   |
| Alcor Micro USB 2.0 Camera                              | 15        | 0.79%   |
| IMC Networks Integrated Camera                          | 14        | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.74%   |
| Bison Lenovo Integrated Webcam                          | 14        | 0.74%   |
| Alcor Micro Asus Integrated Webcam                      | 14        | 0.74%   |
| Realtek HD WebCam                                       | 13        | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 104       | 39.85%  |
| AuthenTec                  | 49        | 18.77%  |
| Upek                       | 32        | 12.26%  |
| Shenzhen Goodix Technology | 18        | 6.9%    |
| Synaptics                  | 16        | 6.13%   |
| STMicroelectronics         | 14        | 5.36%   |
| LighTuning Technology      | 14        | 5.36%   |
| Elan Microelectronics      | 13        | 4.98%   |
| Focal-systems.Corp         | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 10.73%  |
| AuthenTec AES2810                                                          | 21        | 8.05%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 6.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 5.75%   |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 5.75%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 5.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 4.98%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 4.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 4.21%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.45%   |
| Validity Sensors VFS491                                                    | 7         | 2.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 2.68%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 2.68%   |
| Synaptics  WBDI                                                            | 6         | 2.3%    |
| AuthenTec AES1600                                                          | 6         | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.92%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.53%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.53%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 1.15%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.15%   |
| Elan WBF Fingerprint Sensor                                                | 3         | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.77%   |
| Synaptics WBDI Device                                                      | 2         | 0.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.77%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.77%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.38%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.38%   |
| Synaptics TouchPad                                                         | 1         | 0.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.38%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.38%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.38%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Broadcom             | 74        | 54.41%  |
| O2 Micro             | 22        | 16.18%  |
| Alcor Micro          | 16        | 11.76%  |
| Lenovo               | 13        | 9.56%   |
| Upek                 | 8         | 5.88%   |
| SCM Microsystems     | 1         | 0.74%   |
| OmniKey              | 1         | 0.74%   |
| Microchip Technology | 1         | 0.74%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 47        | 34.56%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 16.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 13.97%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 9.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 5.88%   |
| Broadcom 5880                                                                | 8         | 5.88%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.74%   |
| OmniKey CardMan 4321                                                         | 1         | 0.74%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.74%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1702      | 75.51%  |
| 1     | 446       | 19.79%  |
| 2     | 102       | 4.53%   |
| 3     | 4         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 261       | 39.97%  |
| Graphics card            | 135       | 20.67%  |
| Chipcard                 | 134       | 20.52%  |
| Storage                  | 37        | 5.67%   |
| Net/wireless             | 30        | 4.59%   |
| Bluetooth                | 24        | 3.68%   |
| Multimedia controller    | 14        | 2.14%   |
| Camera                   | 6         | 0.92%   |
| Communication controller | 5         | 0.77%   |
| Card reader              | 3         | 0.46%   |
| Sound                    | 1         | 0.15%   |
| Network                  | 1         | 0.15%   |
| Modem                    | 1         | 0.15%   |
| Flash memory             | 1         | 0.15%   |

