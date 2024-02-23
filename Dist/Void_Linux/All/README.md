Void Linux - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Void Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void_Linux/Desktop/README.md) and [notebooks](/Dist/Void_Linux/Notebook/README.md).

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

Total: 258

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 2ADE                        | Desktop     | [c98c83ddde](https://linux-hardware.org/?probe=c98c83ddde) | Jan 29, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [971c919cef](https://linux-hardware.org/?probe=971c919cef) | Jan 20, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [89387d46ef](https://linux-hardware.org/?probe=89387d46ef) | Jan 18, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c1e2f276ba](https://linux-hardware.org/?probe=c1e2f276ba) | Jan 18, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [cc169dad66](https://linux-hardware.org/?probe=cc169dad66) | Jan 08, 2024 |
| Dell          | 0G919G A00                  | Desktop     | [265aa7e914](https://linux-hardware.org/?probe=265aa7e914) | Jan 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [7caa5da564](https://linux-hardware.org/?probe=7caa5da564) | Dec 31, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [cd261e1bc3](https://linux-hardware.org/?probe=cd261e1bc3) | Dec 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [5f97c0d536](https://linux-hardware.org/?probe=5f97c0d536) | Dec 13, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [e553ac24bf](https://linux-hardware.org/?probe=e553ac24bf) | Dec 10, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [980caec27f](https://linux-hardware.org/?probe=980caec27f) | Dec 03, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6d20427d3](https://linux-hardware.org/?probe=f6d20427d3) | Nov 26, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7ed36f1817](https://linux-hardware.org/?probe=7ed36f1817) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2070cd827](https://linux-hardware.org/?probe=f2070cd827) | Nov 18, 2023 |
| Unknown       | T100                        | Desktop     | [298b8f8764](https://linux-hardware.org/?probe=298b8f8764) | Nov 16, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [426fd54105](https://linux-hardware.org/?probe=426fd54105) | Nov 15, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Supermicro    | X11SCA-F                    | Server      | [e63931ed4f](https://linux-hardware.org/?probe=e63931ed4f) | Nov 04, 2023 |
| Google        | Phaser360                   | Notebook    | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [3e65f94217](https://linux-hardware.org/?probe=3e65f94217) | Oct 28, 2023 |
| Dell          | Latitude D610               | Notebook    | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [9faa5f07eb](https://linux-hardware.org/?probe=9faa5f07eb) | Oct 20, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [4bec650d3e](https://linux-hardware.org/?probe=4bec650d3e) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [d96bdeca74](https://linux-hardware.org/?probe=d96bdeca74) | Oct 10, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Acer          | One S1003                   | Tablet      | [dd8e16ad67](https://linux-hardware.org/?probe=dd8e16ad67) | Sep 25, 2023 |
| Acer          | One S1003                   | Tablet      | [02c8574cb0](https://linux-hardware.org/?probe=02c8574cb0) | Sep 25, 2023 |
| HP            | 15                          | Notebook    | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e60d905c5](https://linux-hardware.org/?probe=1e60d905c5) | Sep 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [14dbf1a55b](https://linux-hardware.org/?probe=14dbf1a55b) | Jul 26, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [00a862ae7c](https://linux-hardware.org/?probe=00a862ae7c) | Jun 14, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | Notebook    | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| ASUSTek       | Q325UAR                     | Convertible | [b95d2d4e30](https://linux-hardware.org/?probe=b95d2d4e30) | Feb 02, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [43ba50f36c](https://linux-hardware.org/?probe=43ba50f36c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| MSI           | B550M PRO                   | Desktop     | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b30f8a638b](https://linux-hardware.org/?probe=b30f8a638b) | Dec 26, 2022 |
| MSI           | B550M PRO                   | Desktop     | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | Notebook    | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | Notebook    | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a3485b332a](https://linux-hardware.org/?probe=a3485b332a) | Sep 27, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [7e7f71a3c0](https://linux-hardware.org/?probe=7e7f71a3c0) | Jul 23, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [761dd08497](https://linux-hardware.org/?probe=761dd08497) | Jul 23, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP            | 3397                        | Desktop     | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI           | Z87-G43                     | Desktop     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| MSI           | B550M PRO                   | Desktop     | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | Notebook    | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| ASUSTek       | Q325UAR                     | Convertible | [fc83e5d0b3](https://linux-hardware.org/?probe=fc83e5d0b3) | Feb 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | Notebook    | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | Notebook    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | Notebook    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | Notebook    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| ASRock        | J4005B-ITX                  | Desktop     | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [32c0e61ea7](https://linux-hardware.org/?probe=32c0e61ea7) | May 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c96223f666](https://linux-hardware.org/?probe=c96223f666) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| Dell          | Inspiron 11 - 3148          | Notebook    | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Acer          | AO722                       | Notebook    | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| HP            | 82C0                        | Mini pc     | [44430304d3](https://linux-hardware.org/?probe=44430304d3) | Oct 19, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | Notebook    | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| Acer          | Nitro AN715-51              | Notebook    | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | Notebook    | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | Notebook    | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| ASUSTek       | P8H67-V                     | Desktop     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Acer          | AO722                       | Notebook    | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | Notebook    | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | Notebook    | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | Notebook    | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | Notebook    | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| Dell          | 0H8052                      | Desktop     | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek       | X555UJ                      | Notebook    | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | Notebook    | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| ASRock        | AB350M                      | Desktop     | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| MSI           | B350M GAMING PRO            | Desktop     | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| Positivo      | Mobile                      | Notebook    | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 147       | 73.87%  |
| Void Linux         | 52        | 26.13%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 196       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 11        | 5.24%   |
| 6.3.12_1  | 9         | 4.29%   |
| 5.13.19_1 | 7         | 3.33%   |
| 5.8.18_1  | 5         | 2.38%   |
| 6.1.4_1   | 4         | 1.9%    |
| 6.1.31_1  | 4         | 1.9%    |
| 5.3.9_1   | 4         | 1.9%    |
| 5.18.19_1 | 4         | 1.9%    |
| 5.16.20_1 | 4         | 1.9%    |
| 5.10.17_1 | 4         | 1.9%    |
| 6.6.8_1   | 3         | 1.43%   |
| 6.5.13_1  | 3         | 1.43%   |
| 6.5.11_1  | 3         | 1.43%   |
| 5.8.12_1  | 3         | 1.43%   |
| 5.19.17_1 | 3         | 1.43%   |
| 5.18.14_1 | 3         | 1.43%   |
| 5.15.32_1 | 3         | 1.43%   |
| 5.13.13_1 | 3         | 1.43%   |
| 5.12.10_1 | 3         | 1.43%   |
| 6.6.9_1   | 2         | 0.95%   |
| 6.6.1_1   | 2         | 0.95%   |
| 6.6.11_1  | 2         | 0.95%   |
| 6.5.9_1   | 2         | 0.95%   |
| 6.5.5_2   | 2         | 0.95%   |
| 6.5.10_1  | 2         | 0.95%   |
| 6.1.21_1  | 2         | 0.95%   |
| 6.1.10_1  | 2         | 0.95%   |
| 6.0.15_1  | 2         | 0.95%   |
| 6.0.13_1  | 2         | 0.95%   |
| 5.9.14_1  | 2         | 0.95%   |
| 5.4.24_1  | 2         | 0.95%   |
| 5.4.13_2  | 2         | 0.95%   |
| 5.19.16_1 | 2         | 0.95%   |
| 5.18.9_1  | 2         | 0.95%   |
| 5.15.41_1 | 2         | 0.95%   |
| 5.15.34_1 | 2         | 0.95%   |
| 5.15.22_1 | 2         | 0.95%   |
| 5.15.16_1 | 2         | 0.95%   |
| 5.13.15_1 | 2         | 0.95%   |
| 5.13.10_1 | 2         | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.13  | 11        | 5.24%   |
| 6.3.12  | 9         | 4.29%   |
| 5.13.19 | 7         | 3.33%   |
| 5.8.18  | 5         | 2.38%   |
| 6.1.4   | 4         | 1.9%    |
| 6.1.31  | 4         | 1.9%    |
| 5.8.12  | 4         | 1.9%    |
| 5.3.9   | 4         | 1.9%    |
| 5.18.19 | 4         | 1.9%    |
| 5.16.20 | 4         | 1.9%    |
| 5.10.17 | 4         | 1.9%    |
| 6.6.8   | 3         | 1.43%   |
| 6.5.13  | 3         | 1.43%   |
| 6.5.11  | 3         | 1.43%   |
| 5.19.17 | 3         | 1.43%   |
| 5.18.14 | 3         | 1.43%   |
| 5.15.32 | 3         | 1.43%   |
| 5.13.13 | 3         | 1.43%   |
| 5.12.10 | 3         | 1.43%   |
| 6.6.9   | 2         | 0.95%   |
| 6.6.11  | 2         | 0.95%   |
| 6.6.1   | 2         | 0.95%   |
| 6.5.9   | 2         | 0.95%   |
| 6.5.5   | 2         | 0.95%   |
| 6.5.10  | 2         | 0.95%   |
| 6.1.21  | 2         | 0.95%   |
| 6.1.10  | 2         | 0.95%   |
| 6.0.15  | 2         | 0.95%   |
| 6.0.13  | 2         | 0.95%   |
| 5.9.14  | 2         | 0.95%   |
| 5.4.24  | 2         | 0.95%   |
| 5.4.13  | 2         | 0.95%   |
| 5.19.16 | 2         | 0.95%   |
| 5.18.9  | 2         | 0.95%   |
| 5.15.41 | 2         | 0.95%   |
| 5.15.34 | 2         | 0.95%   |
| 5.15.22 | 2         | 0.95%   |
| 5.15.16 | 2         | 0.95%   |
| 5.13.15 | 2         | 0.95%   |
| 5.13.10 | 2         | 0.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 24        | 11.54%  |
| 6.3     | 20        | 9.62%   |
| 6.1     | 19        | 9.13%   |
| 5.8     | 18        | 8.65%   |
| 5.13    | 16        | 7.69%   |
| 6.5     | 15        | 7.21%   |
| 5.10    | 15        | 7.21%   |
| 5.18    | 12        | 5.77%   |
| 6.6     | 9         | 4.33%   |
| 5.12    | 9         | 4.33%   |
| 5.4     | 7         | 3.37%   |
| 6.0     | 6         | 2.88%   |
| 5.3     | 5         | 2.4%    |
| 5.19    | 5         | 2.4%    |
| 5.11    | 5         | 2.4%    |
| 5.9     | 4         | 1.92%   |
| 5.16    | 4         | 1.92%   |
| 4.19    | 4         | 1.92%   |
| 6.2     | 2         | 0.96%   |
| 6.4     | 1         | 0.48%   |
| 5.7     | 1         | 0.48%   |
| 5.6     | 1         | 0.48%   |
| 5.2     | 1         | 0.48%   |
| 5.17    | 1         | 0.48%   |
| 5.14    | 1         | 0.48%   |
| 5.1     | 1         | 0.48%   |
| 4.4     | 1         | 0.48%   |
| 4.14    | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 183       | 93.37%  |
| i686    | 7         | 3.57%   |
| aarch64 | 3         | 1.53%   |
| ppc64le | 1         | 0.51%   |
| ppc64   | 1         | 0.51%   |
| armv7l  | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Unknown      | 82        | 40.59%  |
| XFCE         | 33        | 16.34%  |
| KDE5         | 17        | 8.42%   |
| KDE          | 13        | 6.44%   |
| GNOME        | 11        | 5.45%   |
| MATE         | 9         | 4.46%   |
| i3           | 7         | 3.47%   |
| X-Cinnamon   | 6         | 2.97%   |
| sway         | 6         | 2.97%   |
| bspwm        | 4         | 1.98%   |
| awesome      | 4         | 1.98%   |
| openbox      | 3         | 1.49%   |
| Lumina       | 2         | 0.99%   |
| river        | 1         | 0.5%    |
| LXQt         | 1         | 0.5%    |
| LXDE         | 1         | 0.5%    |
| dwm          | 1         | 0.5%    |
| dot-xsession | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 138       | 69%     |
| Wayland | 27        | 13.5%   |
| Tty     | 21        | 10.5%   |
| Unknown | 14        | 7%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 148       | 74%     |
| LightDM | 23        | 11.5%   |
| SDDM    | 14        | 7%      |
| LXDM    | 8         | 4%      |
| GDM     | 5         | 2.5%    |
| SLiM    | 1         | 0.5%    |
| LDM     | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 106       | 52.48%  |
| Unknown | 22        | 10.89%  |
| en_GB   | 12        | 5.94%   |
| fr_FR   | 6         | 2.97%   |
| en_DK   | 6         | 2.97%   |
| ru_RU   | 5         | 2.48%   |
| it_IT   | 5         | 2.48%   |
| de_DE   | 5         | 2.48%   |
| C       | 5         | 2.48%   |
| es_ES   | 4         | 1.98%   |
| en_CA   | 3         | 1.49%   |
| cs_CZ   | 3         | 1.49%   |
| pt_BR   | 2         | 0.99%   |
| pl_PL   | 2         | 0.99%   |
| en_AU   | 2         | 0.99%   |
| el_GR   | 2         | 0.99%   |
| tr_TR   | 1         | 0.5%    |
| ru_UA   | 1         | 0.5%    |
| nb_NO   | 1         | 0.5%    |
| hu_HU   | 1         | 0.5%    |
| es_HN   | 1         | 0.5%    |
| es_DO   | 1         | 0.5%    |
| es_CL   | 1         | 0.5%    |
| es_AR   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| en_IE   | 1         | 0.5%    |
| ca_ES   | 1         | 0.5%    |
| bg_BG   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 107       | 53.5%   |
| BIOS | 93        | 46.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 120       | 60%     |
| Btrfs   | 46        | 23%     |
| Zfs     | 10        | 5%      |
| Xfs     | 10        | 5%      |
| Unknown | 6         | 3%      |
| F2fs    | 4         | 2%      |
| Overlay | 3         | 1.5%    |
| Ext3    | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 117       | 58.5%   |
| Unknown | 59        | 29.5%   |
| MBR     | 24        | 12%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 172       | 87.76%  |
| Yes       | 24        | 12.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 77.89%  |
| Yes       | 44        | 22.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 39        | 19.9%   |
| Lenovo                  | 35        | 17.86%  |
| Hewlett-Packard         | 23        | 11.73%  |
| MSI                     | 17        | 8.67%   |
| Acer                    | 17        | 8.67%   |
| Dell                    | 16        | 8.16%   |
| ASRock                  | 9         | 4.59%   |
| Gigabyte Technology     | 8         | 4.08%   |
| Unknown                 | 7         | 3.57%   |
| Notebook                | 2         | 1.02%   |
| Microsoft               | 2         | 1.02%   |
| HUAWEI                  | 2         | 1.02%   |
| Apple                   | 2         | 1.02%   |
| Toshiba                 | 1         | 0.51%   |
| Timi                    | 1         | 0.51%   |
| Supermicro              | 1         | 0.51%   |
| Samsung Electronics     | 1         | 0.51%   |
| Razer                   | 1         | 0.51%   |
| Raspberry Pi Foundation | 1         | 0.51%   |
| Positivo                | 1         | 0.51%   |
| Pine Microsystems       | 1         | 0.51%   |
| Nokia                   | 1         | 0.51%   |
| Google                  | 1         | 0.51%   |
| Getac                   | 1         | 0.51%   |
| Framework               | 1         | 0.51%   |
| Exo                     | 1         | 0.51%   |
| EVGA                    | 1         | 0.51%   |
| Digibras                | 1         | 0.51%   |
| Cisco Systems           | 1         | 0.51%   |
| Chuwi                   | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 7         | 3.57%   |
| MSI MS-7C02                           | 2         | 1.02%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW | 2         | 1.02%   |
| HP Pavilion Notebook                  | 2         | 1.02%   |
| HP Laptop 15-bw0xx                    | 2         | 1.02%   |
| HP 15                                 | 2         | 1.02%   |
| Dell OptiPlex 780                     | 2         | 1.02%   |
| Dell OptiPlex 7010                    | 2         | 1.02%   |
| ASUS X751LD                           | 2         | 1.02%   |
| ASUS PRIME Z390-P                     | 2         | 1.02%   |
| Acer Swift SF314-42                   | 2         | 1.02%   |
| Toshiba Satellite A200                | 1         | 0.51%   |
| Timi Redmi Book Pro 15 2022           | 1         | 0.51%   |
| Supermicro Super Server               | 1         | 0.51%   |
| Samsung 275E4E/275E5E                 | 1         | 0.51%   |
| Razer Blade 14 (2022) - RZ09-0427     | 1         | 0.51%   |
| RPi Raspberry Pi                      | 1         | 0.51%   |
| Positivo Mobile                       | 1         | 0.51%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 0.51%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 0.51%   |
| Notebook NH50_70RA                    | 1         | 0.51%   |
| Nokia Booklet 3G                      | 1         | 0.51%   |
| MSI Summit E13FlipEvo A12MT           | 1         | 0.51%   |
| MSI Prestige 15 A10SC                 | 1         | 0.51%   |
| MSI MS-7D95                           | 1         | 0.51%   |
| MSI MS-7D14                           | 1         | 0.51%   |
| MSI MS-7C92                           | 1         | 0.51%   |
| MSI MS-7C52                           | 1         | 0.51%   |
| MSI MS-7C35                           | 1         | 0.51%   |
| MSI MS-7B86                           | 1         | 0.51%   |
| MSI MS-7A68                           | 1         | 0.51%   |
| MSI MS-7A39                           | 1         | 0.51%   |
| MSI MS-7816                           | 1         | 0.51%   |
| MSI GV72 7RE                          | 1         | 0.51%   |
| MSI GF63 Thin 10SCXR                  | 1         | 0.51%   |
| MSI GE60 2OC\2OD\2OE                  | 1         | 0.51%   |
| MSI Bravo 15 A4DDR                    | 1         | 0.51%   |
| Microsoft Surface with Windows RT     | 1         | 0.51%   |
| Microsoft Surface Go 2                | 1         | 0.51%   |
| Lenovo Yoga 720-15IKB 80X7            | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 19        | 9.69%   |
| Acer Aspire              | 10        | 5.1%    |
| ASUS PRIME               | 9         | 4.59%   |
| Lenovo IdeaPad           | 8         | 4.08%   |
| ASUS VivoBook            | 7         | 3.57%   |
| Unknown                  | 7         | 3.57%   |
| HP Pavilion              | 5         | 2.55%   |
| HP Laptop                | 5         | 2.55%   |
| Dell OptiPlex            | 5         | 2.55%   |
| Dell Latitude            | 4         | 2.04%   |
| Dell Inspiron            | 4         | 2.04%   |
| ASUS TUF                 | 3         | 1.53%   |
| MSI MS-7C02              | 2         | 1.02%   |
| Microsoft Surface        | 2         | 1.02%   |
| Lenovo ThinkBook         | 2         | 1.02%   |
| HP Stream                | 2         | 1.02%   |
| HP ENVY                  | 2         | 1.02%   |
| HP Compaq                | 2         | 1.02%   |
| HP 255                   | 2         | 1.02%   |
| HP 15                    | 2         | 1.02%   |
| ASUS X751LD              | 2         | 1.02%   |
| ASUS ROG                 | 2         | 1.02%   |
| Acer Swift               | 2         | 1.02%   |
| Toshiba Satellite        | 1         | 0.51%   |
| Timi Redmi               | 1         | 0.51%   |
| Supermicro Super         | 1         | 0.51%   |
| Samsung 275E4E           | 1         | 0.51%   |
| Razer Blade              | 1         | 0.51%   |
| RPi Raspberry            | 1         | 0.51%   |
| Positivo Mobile          | 1         | 0.51%   |
| Pine Microsystems Pine64 | 1         | 0.51%   |
| Notebook NV4XMB          | 1         | 0.51%   |
| Notebook NH50            | 1         | 0.51%   |
| Nokia Booklet            | 1         | 0.51%   |
| MSI Summit               | 1         | 0.51%   |
| MSI Prestige             | 1         | 0.51%   |
| MSI MS-7D95              | 1         | 0.51%   |
| MSI MS-7D14              | 1         | 0.51%   |
| MSI MS-7C92              | 1         | 0.51%   |
| MSI MS-7C52              | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 28        | 14.29%  |
| 2020    | 23        | 11.73%  |
| 2018    | 20        | 10.2%   |
| 2013    | 15        | 7.65%   |
| 2021    | 14        | 7.14%   |
| 2017    | 13        | 6.63%   |
| 2022    | 12        | 6.12%   |
| 2014    | 11        | 5.61%   |
| 2016    | 10        | 5.1%    |
| 2012    | 10        | 5.1%    |
| 2015    | 8         | 4.08%   |
| 2011    | 8         | 4.08%   |
| 2010    | 5         | 2.55%   |
| Unknown | 5         | 2.55%   |
| 2023    | 4         | 2.04%   |
| 2009    | 2         | 1.02%   |
| 2008    | 2         | 1.02%   |
| 2007    | 2         | 1.02%   |
| 2006    | 2         | 1.02%   |
| 2005    | 2         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 119       | 60.71%  |
| Desktop        | 64        | 32.65%  |
| Tablet         | 4         | 2.04%   |
| Convertible    | 4         | 2.04%   |
| Server         | 2         | 1.02%   |
| System on chip | 1         | 0.51%   |
| Mini pc        | 1         | 0.51%   |
| All in one     | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 196       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 195       | 99.49%  |
| Yes  | 1         | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 42        | 21.21%  |
| 4.01-8.0        | 40        | 20.2%   |
| 8.01-16.0       | 35        | 17.68%  |
| 3.01-4.0        | 31        | 15.66%  |
| 32.01-64.0      | 24        | 12.12%  |
| 1.01-2.0        | 10        | 5.05%   |
| 24.01-32.0      | 6         | 3.03%   |
| 0.51-1.0        | 4         | 2.02%   |
| 64.01-256.0     | 3         | 1.52%   |
| More than 256.0 | 1         | 0.51%   |
| 2.01-3.0        | 1         | 0.51%   |
| 0.01-0.5        | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 60        | 28.99%  |
| 2.01-3.0    | 45        | 21.74%  |
| 4.01-8.0    | 26        | 12.56%  |
| 0.51-1.0    | 26        | 12.56%  |
| 3.01-4.0    | 25        | 12.08%  |
| 8.01-16.0   | 13        | 6.28%   |
| 0.01-0.5    | 8         | 3.86%   |
| 16.01-24.0  | 3         | 1.45%   |
| 64.01-256.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 119       | 60.1%   |
| 2      | 47        | 23.74%  |
| 3      | 22        | 11.11%  |
| 4      | 5         | 2.53%   |
| 5      | 3         | 1.52%   |
| 9      | 1         | 0.51%   |
| 0      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 78.06%  |
| Yes       | 43        | 21.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 80.2%   |
| No        | 39        | 19.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 74.11%  |
| No        | 51        | 25.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 64.97%  |
| No        | 69        | 35.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 40        | 20.41%  |
| Russia      | 17        | 8.67%   |
| Germany     | 16        | 8.16%   |
| India       | 10        | 5.1%    |
| Brazil      | 8         | 4.08%   |
| UK          | 7         | 3.57%   |
| France      | 7         | 3.57%   |
| Poland      | 6         | 3.06%   |
| Italy       | 6         | 3.06%   |
| Czechia     | 6         | 3.06%   |
| Netherlands | 5         | 2.55%   |
| Greece      | 5         | 2.55%   |
| Denmark     | 5         | 2.55%   |
| Ukraine     | 4         | 2.04%   |
| Switzerland | 4         | 2.04%   |
| Canada      | 4         | 2.04%   |
| Turkey      | 3         | 1.53%   |
| Spain       | 3         | 1.53%   |
| Bulgaria    | 3         | 1.53%   |
| Australia   | 3         | 1.53%   |
| Argentina   | 3         | 1.53%   |
| Vietnam     | 2         | 1.02%   |
| Serbia      | 2         | 1.02%   |
| Morocco     | 2         | 1.02%   |
| Finland     | 2         | 1.02%   |
| Uruguay     | 1         | 0.51%   |
| Thailand    | 1         | 0.51%   |
| Sweden      | 1         | 0.51%   |
| Portugal    | 1         | 0.51%   |
| Peru        | 1         | 0.51%   |
| Norway      | 1         | 0.51%   |
| Nigeria     | 1         | 0.51%   |
| New Zealand | 1         | 0.51%   |
| Mexico      | 1         | 0.51%   |
| Latvia      | 1         | 0.51%   |
| Jordan      | 1         | 0.51%   |
| Indonesia   | 1         | 0.51%   |
| Hungary     | 1         | 0.51%   |
| Honduras    | 1         | 0.51%   |
| Guatemala   | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Moscow             | 6         | 2.99%   |
| Prague             | 5         | 2.49%   |
| St Petersburg      | 3         | 1.49%   |
| Denver             | 3         | 1.49%   |
| Amsterdam          | 3         | 1.49%   |
| Toulouse           | 2         | 1%      |
| Spring Hill        | 2         | 1%      |
| Sofia              | 2         | 1%      |
| Sao Paulo          | 2         | 1%      |
| Rome               | 2         | 1%      |
| Orlando            | 2         | 1%      |
| Munich             | 2         | 1%      |
| Meknes             | 2         | 1%      |
| Lublin             | 2         | 1%      |
| Ioannina           | 2         | 1%      |
| Hyderabad          | 2         | 1%      |
| Harrisonburg       | 2         | 1%      |
| Geneva             | 2         | 1%      |
| Zarqa              | 1         | 0.5%    |
| Zagnansk           | 1         | 0.5%    |
| Yekaterinburg      | 1         | 0.5%    |
| Yambol             | 1         | 0.5%    |
| Worthing           | 1         | 0.5%    |
| Winnipeg           | 1         | 0.5%    |
| Wilen bei Wollerau | 1         | 0.5%    |
| Weatherford        | 1         | 0.5%    |
| Warsaw             | 1         | 0.5%    |
| Volgograd          | 1         | 0.5%    |
| Vlaardingen        | 1         | 0.5%    |
| Vienna             | 1         | 0.5%    |
| Viby J             | 1         | 0.5%    |
| Verkhnyaya Pyshma  | 1         | 0.5%    |
| Varna              | 1         | 0.5%    |
| Vancouver          | 1         | 0.5%    |
| Trujillo           | 1         | 0.5%    |
| Touget             | 1         | 0.5%    |
| Toms River         | 1         | 0.5%    |
| Tegucigalpa        | 1         | 0.5%    |
| Taranto            | 1         | 0.5%    |
| Syktyvkar          | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 59        | 78     | 20.63%  |
| WDC                         | 40        | 51     | 13.99%  |
| Seagate                     | 40        | 49     | 13.99%  |
| SanDisk                     | 17        | 20     | 5.94%   |
| Kingston                    | 17        | 18     | 5.94%   |
| Unknown                     | 16        | 23     | 5.59%   |
| Toshiba                     | 10        | 11     | 3.5%    |
| SK hynix                    | 10        | 11     | 3.5%    |
| Intel                       | 9         | 11     | 3.15%   |
| HGST                        | 9         | 10     | 3.15%   |
| Crucial                     | 9         | 10     | 3.15%   |
| Hitachi                     | 8         | 8      | 2.8%    |
| Phison                      | 3         | 3      | 1.05%   |
| Micron/Crucial Technology   | 3         | 3      | 1.05%   |
| Micron Technology           | 3         | 4      | 1.05%   |
| Kingston Technology Company | 3         | 4      | 1.05%   |
| A-DATA Technology           | 3         | 4      | 1.05%   |
| Patriot                     | 2         | 2      | 0.7%    |
| Corsair                     | 2         | 2      | 0.7%    |
| XrayDisk                    | 1         | 1      | 0.35%   |
| XPG                         | 1         | 4      | 0.35%   |
| Transcend                   | 1         | 1      | 0.35%   |
| SPCC                        | 1         | 1      | 0.35%   |
| PNY                         | 1         | 1      | 0.35%   |
| Phison Electronics          | 1         | 1      | 0.35%   |
| ORIGIN                      | 1         | 1      | 0.35%   |
| OCZ                         | 1         | 1      | 0.35%   |
| Maxtor                      | 1         | 1      | 0.35%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.35%   |
| LITEONIT                    | 1         | 1      | 0.35%   |
| Lenovo                      | 1         | 1      | 0.35%   |
| KIOXIA                      | 1         | 1      | 0.35%   |
| JMicron Technology          | 1         | 1      | 0.35%   |
| Intenso                     | 1         | 1      | 0.35%   |
| INNOVATION IT               | 1         | 1      | 0.35%   |
| IBM/Hitachi                 | 1         | 1      | 0.35%   |
| Gigabyte Technology         | 1         | 2      | 0.35%   |
| China                       | 1         | 1      | 0.35%   |
| BIWIN                       | 1         | 1      | 0.35%   |
| BHT                         | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 8         | 2.56%   |
| Unknown MMC Card  32GB                             | 6         | 1.92%   |
| Kingston SA400S37240G 240GB SSD                    | 6         | 1.92%   |
| Seagate ST2000DM008-2FR102 2TB                     | 5         | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 1.6%    |
| Unknown MMC Card  64GB                             | 4         | 1.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 4         | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4         | 1.28%   |
| Samsung SSD 870 EVO 500GB                          | 4         | 1.28%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 3         | 0.96%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.96%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB               | 3         | 0.96%   |
| Samsung NVMe SSD Drive 1TB                         | 3         | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 3         | 0.96%   |
| Kingston SHFS37A120G 120GB SSD                     | 3         | 0.96%   |
| HGST HTS545050A7E680 500GB                         | 3         | 0.96%   |
| Crucial CT500MX500SSD1 500GB                       | 3         | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 2         | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 2         | 0.64%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 2         | 0.64%   |
| Unknown MMC Card  128GB                            | 2         | 0.64%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 0.64%   |
| Toshiba DT01ACA050 500GB                           | 2         | 0.64%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1TB            | 2         | 0.64%   |
| Seagate ST500DM002-1BD142 500GB                    | 2         | 0.64%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB                     | 2         | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 0.64%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 0.64%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 0.64%   |
| Samsung SSD 870 QVO 1TB                            | 2         | 0.64%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 0.64%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.64%   |
| Samsung SSD 860 EVO 4TB                            | 2         | 0.64%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 0.64%   |
| Samsung NVMe SSD Drive 500GB                       | 2         | 0.64%   |
| Patriot Burst 120GB SSD                            | 2         | 0.64%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 2         | 0.64%   |
| Kingston SA400S37120G 120GB SSD                    | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 49     | 36.36%  |
| WDC                 | 33        | 40     | 30%     |
| Toshiba             | 9         | 10     | 8.18%   |
| HGST                | 9         | 10     | 8.18%   |
| Hitachi             | 8         | 8      | 7.27%   |
| Samsung Electronics | 6         | 7      | 5.45%   |
| XrayDisk            | 1         | 1      | 0.91%   |
| Unknown             | 1         | 1      | 0.91%   |
| Maxtor              | 1         | 1      | 0.91%   |
| JMicron Technology  | 1         | 1      | 0.91%   |
| IBM/Hitachi         | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 25     | 27.16%  |
| Kingston            | 16        | 17     | 19.75%  |
| SanDisk             | 7         | 8      | 8.64%   |
| Crucial             | 7         | 8      | 8.64%   |
| WDC                 | 6         | 7      | 7.41%   |
| Patriot             | 2         | 2      | 2.47%   |
| Intel               | 2         | 2      | 2.47%   |
| A-DATA Technology   | 2         | 3      | 2.47%   |
| Transcend           | 1         | 1      | 1.23%   |
| SPCC                | 1         | 1      | 1.23%   |
| SK hynix            | 1         | 1      | 1.23%   |
| PNY                 | 1         | 1      | 1.23%   |
| ORIGIN              | 1         | 1      | 1.23%   |
| OCZ                 | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| Lenovo              | 1         | 1      | 1.23%   |
| Intenso             | 1         | 1      | 1.23%   |
| INNOVATION IT       | 1         | 1      | 1.23%   |
| Gigabyte Technology | 1         | 2      | 1.23%   |
| Corsair             | 1         | 1      | 1.23%   |
| China               | 1         | 1      | 1.23%   |
| BIWIN               | 1         | 1      | 1.23%   |
| BHT                 | 1         | 1      | 1.23%   |
| Apple               | 1         | 1      | 1.23%   |
| AGI                 | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 92        | 129    | 35.52%  |
| NVMe    | 78        | 107    | 30.12%  |
| SSD     | 72        | 90     | 27.8%   |
| MMC     | 15        | 20     | 5.79%   |
| Unknown | 2         | 3      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 133       | 213    | 56.84%  |
| NVMe | 78        | 107    | 33.33%  |
| MMC  | 15        | 20     | 6.41%   |
| SAS  | 8         | 9      | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 92        | 118    | 53.18%  |
| 0.51-1.0   | 60        | 72     | 34.68%  |
| 1.01-2.0   | 16        | 23     | 9.25%   |
| 4.01-10.0  | 3         | 3      | 1.73%   |
| 3.01-4.0   | 2         | 3      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 25%     |
| 101-250        | 39        | 19.5%   |
| 501-1000       | 39        | 19.5%   |
| 1001-2000      | 17        | 8.5%    |
| 1-20           | 12        | 6%      |
| Unknown        | 12        | 6%      |
| More than 3000 | 11        | 5.5%    |
| 51-100         | 9         | 4.5%    |
| 21-50          | 6         | 3%      |
| 2001-3000      | 5         | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 58        | 28.02%  |
| 101-250        | 41        | 19.81%  |
| 21-50          | 30        | 14.49%  |
| 251-500        | 21        | 10.14%  |
| 51-100         | 19        | 9.18%   |
| Unknown        | 12        | 5.8%    |
| 1001-2000      | 11        | 5.31%   |
| 501-1000       | 9         | 4.35%   |
| More than 3000 | 4         | 1.93%   |
| 2001-3000      | 2         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 5.71%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 5.71%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 5.71%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 2.86%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 1      | 2.86%   |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 2.86%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 2.86%   |
| Toshiba MQ04ABF100 1TB                | 1         | 2      | 2.86%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.86%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 2.86%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 2.86%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 2.86%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 2.86%   |
| Seagate ST3750330AS 752GB             | 1         | 1      | 2.86%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 2.86%   |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 2      | 2.86%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 1      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 2.86%   |
| Samsung Electronics HM160HI 160GB     | 1         | 1      | 2.86%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 2.86%   |
| Samsung Electronics HD322HJ 320GB     | 1         | 1      | 2.86%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB     | 1         | 1      | 2.86%   |
| Hitachi HUA722010CLA330 1TB           | 1         | 1      | 2.86%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 2.86%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 2.86%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.86%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 2.86%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.86%   |
| Crucial CT256MX100SSD1 256GB          | 1         | 1      | 2.86%   |
| A-DATA Technology SU700 120GB SSD     | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 38.24%  |
| Hitachi             | 5         | 5      | 14.71%  |
| WDC                 | 4         | 5      | 11.76%  |
| Samsung Electronics | 4         | 4      | 11.76%  |
| HGST                | 3         | 3      | 8.82%   |
| Toshiba             | 2         | 3      | 5.88%   |
| IBM/Hitachi         | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 41.94%  |
| Hitachi             | 5         | 5      | 16.13%  |
| WDC                 | 4         | 5      | 12.9%   |
| Samsung Electronics | 3         | 3      | 9.68%   |
| HGST                | 3         | 3      | 9.68%   |
| Toshiba             | 2         | 3      | 6.45%   |
| IBM/Hitachi         | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 35     | 90.91%  |
| SSD  | 3         | 3      | 9.09%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 112       | 168    | 50%     |
| Detected | 80        | 143    | 35.71%  |
| Malfunc  | 32        | 38     | 14.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 105       | 42%     |
| AMD                              | 54        | 21.6%   |
| Samsung Electronics              | 38        | 15.2%   |
| SanDisk                          | 12        | 4.8%    |
| SK hynix                         | 9         | 3.6%    |
| Phison Electronics               | 5         | 2%      |
| Micron/Crucial Technology        | 4         | 1.6%    |
| Kingston Technology Company      | 4         | 1.6%    |
| ASMedia Technology               | 4         | 1.6%    |
| Micron Technology                | 3         | 1.2%    |
| Marvell Technology Group         | 2         | 0.8%    |
| ADATA Technology                 | 2         | 0.8%    |
| Toshiba America Info Systems     | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Nvidia                           | 1         | 0.4%    |
| MAXIO Technology (Hangzhou)      | 1         | 0.4%    |
| LSI Logic / Symbios Logic        | 1         | 0.4%    |
| KIOXIA                           | 1         | 0.4%    |
| JMicron Technology               | 1         | 0.4%    |
| Broadcom                         | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37        | 13.26%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 21        | 7.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 4.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 3.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 3.58%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 2.51%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 6         | 2.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.43%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.43%   |
| Intel SATA Controller [RAID Mode]                                              | 4         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.43%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.08%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 3         | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.08%   |
| Intel SSD 660P Series                                                          | 3         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.08%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 1.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.08%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.72%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.72%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.72%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.72%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.72%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.72%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.72%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 2         | 0.72%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.72%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 2         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 139       | 55.6%   |
| NVMe | 79        | 31.6%   |
| IDE  | 17        | 6.8%    |
| RAID | 15        | 6%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 121       | 61.73%  |
| AMD                      | 69        | 35.2%   |
| ARM                      | 4         | 2.04%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.51%   |
| PowerMac11,2             | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 6         | 3.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 3         | 1.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 3         | 1.53%   |
| ARM Processor                                      | 3         | 1.53%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 3         | 1.53%   |
| Intel Core i9-14900K                               | 2         | 1.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 2         | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 1.02%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 2         | 1.02%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 2         | 1.02%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 2         | 1.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 2         | 1.02%   |
| Intel Core i3-5005U CPU @ 2.00GHz                  | 2         | 1.02%   |
| Intel Core i3-4030U CPU @ 1.90GHz                  | 2         | 1.02%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 2         | 1.02%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 2         | 1.02%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 1.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz            | 2         | 1.02%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics         | 2         | 1.02%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 1.02%   |
| AMD Ryzen 7 5800X 8-Core Processor                 | 2         | 1.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 1.02%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 2         | 1.02%   |
| AMD Ryzen 5 5600H with Radeon Graphics             | 2         | 1.02%   |
| AMD Ryzen 5 4500U with Radeon Graphics             | 2         | 1.02%   |
| AMD Ryzen 5 3600X 6-Core Processor                 | 2         | 1.02%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 1.02%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx      | 2         | 1.02%   |
| AMD Ryzen 3 5300U with Radeon Graphics             | 2         | 1.02%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 1.02%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 1.02%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.51%   |
| PowerMac11,2 PPC970MP, altivec supported           | 1         | 0.51%   |
| Intel Xeon E-2146G CPU @ 3.50GHz                   | 1         | 0.51%   |
| Intel Xeon CPU E5506 @ 2.13GHz                     | 1         | 0.51%   |
| Intel Pentium M processor 2.13GHz                  | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 16.33%  |
| Intel Core i7           | 27        | 13.78%  |
| AMD Ryzen 5             | 23        | 11.73%  |
| Other                   | 20        | 10.2%   |
| Intel Core i3           | 17        | 8.67%   |
| AMD Ryzen 7             | 17        | 8.67%   |
| Intel Celeron           | 9         | 4.59%   |
| Intel Atom              | 7         | 3.57%   |
| AMD Ryzen 7 PRO         | 5         | 2.55%   |
| Intel Pentium           | 4         | 2.04%   |
| Intel Core i9           | 3         | 1.53%   |
| Intel Core 2 Duo        | 3         | 1.53%   |
| AMD Ryzen 3             | 3         | 1.53%   |
| AMD FX                  | 3         | 1.53%   |
| Intel Xeon              | 2         | 1.02%   |
| Intel Genuine           | 2         | 1.02%   |
| AMD Ryzen 9             | 2         | 1.02%   |
| AMD A8                  | 2         | 1.02%   |
| Intel Pentium M         | 1         | 0.51%   |
| Intel Pentium Gold      | 1         | 0.51%   |
| Intel Pentium 4         | 1         | 0.51%   |
| Intel Core 2 Quad       | 1         | 0.51%   |
| AMD Turion 64 X2 Mobile | 1         | 0.51%   |
| AMD Ryzen Threadripper  | 1         | 0.51%   |
| AMD Ryzen 5 PRO         | 1         | 0.51%   |
| AMD Phenom II X4        | 1         | 0.51%   |
| AMD E2                  | 1         | 0.51%   |
| AMD E1                  | 1         | 0.51%   |
| AMD C-60                | 1         | 0.51%   |
| AMD Athlon II X3        | 1         | 0.51%   |
| AMD Athlon II X2        | 1         | 0.51%   |
| AMD A6                  | 1         | 0.51%   |
| AMD A4                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 65        | 33.16%  |
| 2       | 59        | 30.1%   |
| 6       | 31        | 15.82%  |
| 8       | 23        | 11.73%  |
| 1       | 7         | 3.57%   |
| 12      | 3         | 1.53%   |
| 24      | 2         | 1.02%   |
| 14      | 2         | 1.02%   |
| 64      | 1         | 0.51%   |
| 10      | 1         | 0.51%   |
| 3       | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 193       | 98.47%  |
| 2       | 2         | 1.02%   |
| Unknown | 1         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 136       | 69.39%  |
| 1       | 58        | 29.59%  |
| 4       | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 180       | 91.84%  |
| Unknown        | 8         | 4.08%   |
| 32-bit         | 5         | 2.55%   |
| 64-bit         | 3         | 1.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 40.8%   |
| 0x40651    | 8         | 3.98%   |
| 0x306a9    | 7         | 3.48%   |
| 0x906e9    | 5         | 2.49%   |
| 0x0a404102 | 5         | 2.49%   |
| 0x906ea    | 4         | 1.99%   |
| 0x806ec    | 4         | 1.99%   |
| 0x806e9    | 4         | 1.99%   |
| 0x406e3    | 4         | 1.99%   |
| 0x08108102 | 4         | 1.99%   |
| 0x806ea    | 3         | 1.49%   |
| 0x30678    | 3         | 1.49%   |
| 0x206a7    | 3         | 1.49%   |
| 0x0a50000c | 3         | 1.49%   |
| 0x08600104 | 3         | 1.49%   |
| 0x906a3    | 2         | 1%      |
| 0x506e3    | 2         | 1%      |
| 0x106c2    | 2         | 1%      |
| 0x0a201009 | 2         | 1%      |
| 0x08701021 | 2         | 1%      |
| 0x08608103 | 2         | 1%      |
| 0x0800820d | 2         | 1%      |
| 0x07030105 | 2         | 1%      |
| 0x06006705 | 2         | 1%      |
| 0x06000852 | 2         | 1%      |
| 0x05000119 | 2         | 1%      |
| 0x010000c8 | 2         | 1%      |
| 0xa0671    | 1         | 0.5%    |
| 0xa0652    | 1         | 0.5%    |
| 0x906ed    | 1         | 0.5%    |
| 0x90675    | 1         | 0.5%    |
| 0x90672    | 1         | 0.5%    |
| 0x806eb    | 1         | 0.5%    |
| 0x806c1    | 1         | 0.5%    |
| 0x706e5    | 1         | 0.5%    |
| 0x706a1    | 1         | 0.5%    |
| 0x406c4    | 1         | 0.5%    |
| 0x306d4    | 1         | 0.5%    |
| 0x306c3    | 1         | 0.5%    |
| 0x30673    | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 17.86%  |
| Zen 3            | 16        | 8.16%   |
| Unknown          | 16        | 8.16%   |
| Haswell          | 14        | 7.14%   |
| Zen 2            | 13        | 6.63%   |
| IvyBridge        | 11        | 5.61%   |
| Zen+             | 9         | 4.59%   |
| Skylake          | 8         | 4.08%   |
| Silvermont       | 8         | 4.08%   |
| Alderlake Hybrid | 7         | 3.57%   |
| Zen              | 5         | 2.55%   |
| SandyBridge      | 5         | 2.55%   |
| Icelake          | 4         | 2.04%   |
| Excavator        | 4         | 2.04%   |
| TigerLake        | 3         | 1.53%   |
| Puma             | 3         | 1.53%   |
| Piledriver       | 3         | 1.53%   |
| Penryn           | 3         | 1.53%   |
| K10              | 3         | 1.53%   |
| Goldmont plus    | 3         | 1.53%   |
| Core             | 3         | 1.53%   |
| CometLake        | 3         | 1.53%   |
| Broadwell        | 3         | 1.53%   |
| Bonnell          | 3         | 1.53%   |
| P6               | 2         | 1.02%   |
| Bobcat           | 2         | 1.02%   |
| Westmere         | 1         | 0.51%   |
| NetBurst         | 1         | 0.51%   |
| Nehalem          | 1         | 0.51%   |
| K8 Hammer        | 1         | 0.51%   |
| Jaguar           | 1         | 0.51%   |
| Gracemont        | 1         | 0.51%   |
| Goldmont         | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 94        | 40.34%  |
| Nvidia                           | 68        | 29.18%  |
| AMD                              | 67        | 28.76%  |
| ASPEED Technology                | 2         | 0.86%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| Matrox Electronics Systems       | 1         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.58%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 2.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 2.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.5%    |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 2.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.08%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.67%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.25%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.25%   |
| Intel HD Graphics 630                                                                    | 3         | 1.25%   |
| Intel HD Graphics 620                                                                    | 3         | 1.25%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 1.25%   |
| AMD Lucienne                                                                             | 3         | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.25%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 3         | 1.25%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.83%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.83%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.83%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.83%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 30.15%  |
| 1 x AMD        | 58        | 29.15%  |
| 1 x Nvidia     | 33        | 16.58%  |
| Intel + Nvidia | 29        | 14.57%  |
| Other          | 5         | 2.51%   |
| AMD + Nvidia   | 4         | 2.01%   |
| 2 x Nvidia     | 2         | 1.01%   |
| 2 x AMD        | 2         | 1.01%   |
| AMD + ASPEED   | 2         | 1.01%   |
| 2 x Intel      | 1         | 0.5%    |
| 1 x SiS        | 1         | 0.5%    |
| 1 x Matrox     | 1         | 0.5%    |
| Intel + AMD    | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 140       | 70.35%  |
| Proprietary | 53        | 26.63%  |
| Unknown     | 6         | 3.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 55.17%  |
| 3.01-4.0   | 21        | 10.34%  |
| 1.01-2.0   | 20        | 9.85%   |
| 0.01-0.5   | 16        | 7.88%   |
| 7.01-8.0   | 11        | 5.42%   |
| 0.51-1.0   | 9         | 4.43%   |
| 5.01-6.0   | 5         | 2.46%   |
| 8.01-16.0  | 5         | 2.46%   |
| 2.01-3.0   | 2         | 0.99%   |
| 16.01-24.0 | 2         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 30        | 14.22%  |
| AU Optronics         | 26        | 12.32%  |
| BOE                  | 21        | 9.95%   |
| Samsung Electronics  | 18        | 8.53%   |
| LG Display           | 17        | 8.06%   |
| Hewlett-Packard      | 10        | 4.74%   |
| Dell                 | 10        | 4.74%   |
| Goldstar             | 7         | 3.32%   |
| Acer                 | 6         | 2.84%   |
| Philips              | 5         | 2.37%   |
| Iiyama               | 5         | 2.37%   |
| PANDA                | 4         | 1.9%    |
| BenQ                 | 4         | 1.9%    |
| AOC                  | 4         | 1.9%    |
| LG Philips           | 3         | 1.42%   |
| Lenovo               | 3         | 1.42%   |
| ASUSTek Computer     | 3         | 1.42%   |
| Apple                | 3         | 1.42%   |
| Ancor Communications | 3         | 1.42%   |
| Unknown              | 3         | 1.42%   |
| TMX                  | 2         | 0.95%   |
| Sharp                | 2         | 0.95%   |
| Fujitsu Siemens      | 2         | 0.95%   |
| Vizio                | 1         | 0.47%   |
| ViewSonic            | 1         | 0.47%   |
| Unknown              | 1         | 0.47%   |
| STD                  | 1         | 0.47%   |
| Sceptre Tech         | 1         | 0.47%   |
| Sceptre              | 1         | 0.47%   |
| Quanta Display       | 1         | 0.47%   |
| Panasonic            | 1         | 0.47%   |
| ONN                  | 1         | 0.47%   |
| MSI                  | 1         | 0.47%   |
| KK@                  | 1         | 0.47%   |
| InnoLux Display      | 1         | 0.47%   |
| Idek Iiyama          | 1         | 0.47%   |
| Huion                | 1         | 0.47%   |
| Gigabyte Technology  | 1         | 0.47%   |
| FUN                  | 1         | 0.47%   |
| eMachines            | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.38%   |
| Unknown                                                               | 3         | 1.38%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.92%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.92%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                 | 2         | 0.92%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 0.92%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 0.92%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch             | 2         | 0.92%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.92%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 0.92%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 0.92%   |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                    | 1         | 0.46%   |
| ViewSonic LCD Monitor VX2457 1920x1080                                | 1         | 0.46%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.46%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.46%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.46%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.46%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.46%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.46%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 0.46%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.46%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.46%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.46%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.46%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.46%   |
| Samsung Electronics LCD Monitor LU28R55 3840x2160                     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor LC49G95T 7040x1440                    | 1         | 0.46%   |
| Samsung Electronics LCD Monitor C49HG9x 7680x1080                     | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 87        | 42.65%  |
| 1366x768 (WXGA)    | 38        | 18.63%  |
| 2560x1440 (QHD)    | 10        | 4.9%    |
| 1920x1200 (WUXGA)  | 10        | 4.9%    |
| 3840x2160 (4K)     | 9         | 4.41%   |
| 1600x900 (HD+)     | 7         | 3.43%   |
| 3440x1440          | 4         | 1.96%   |
| 1680x1050 (WSXGA+) | 4         | 1.96%   |
| 1280x800 (WXGA)    | 4         | 1.96%   |
| Unknown            | 4         | 1.96%   |
| 2560x1600          | 3         | 1.47%   |
| 2560x1080          | 3         | 1.47%   |
| 2160x1440          | 3         | 1.47%   |
| 2880x1800          | 2         | 0.98%   |
| 1280x1024 (SXGA)   | 2         | 0.98%   |
| 1024x600           | 2         | 0.98%   |
| 7680x1080          | 1         | 0.49%   |
| 7040x1440          | 1         | 0.49%   |
| 3840x1600          | 1         | 0.49%   |
| 3840x1080          | 1         | 0.49%   |
| 3200x2000          | 1         | 0.49%   |
| 2288x1287          | 1         | 0.49%   |
| 2256x1504          | 1         | 0.49%   |
| 1920x1280          | 1         | 0.49%   |
| 1600x1200          | 1         | 0.49%   |
| 1360x768           | 1         | 0.49%   |
| 1280x720 (HD)      | 1         | 0.49%   |
| 1024x768 (XGA)     | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 52        | 24.76%  |
| 14      | 24        | 11.43%  |
| 24      | 19        | 9.05%   |
| Unknown | 18        | 8.57%   |
| 13      | 16        | 7.62%   |
| 21      | 12        | 5.71%   |
| 27      | 9         | 4.29%   |
| 23      | 9         | 4.29%   |
| 17      | 6         | 2.86%   |
| 11      | 6         | 2.86%   |
| 34      | 5         | 2.38%   |
| 22      | 4         | 1.9%    |
| 16      | 4         | 1.9%    |
| 12      | 4         | 1.9%    |
| 28      | 3         | 1.43%   |
| 10      | 3         | 1.43%   |
| 31      | 2         | 0.95%   |
| 25      | 2         | 0.95%   |
| 20      | 2         | 0.95%   |
| 19      | 2         | 0.95%   |
| 84      | 1         | 0.48%   |
| 40      | 1         | 0.48%   |
| 39      | 1         | 0.48%   |
| 37      | 1         | 0.48%   |
| 33      | 1         | 0.48%   |
| 32      | 1         | 0.48%   |
| 18      | 1         | 0.48%   |
| 8       | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 41.35%  |
| 501-600     | 36        | 17.31%  |
| 201-300     | 24        | 11.54%  |
| 401-500     | 19        | 9.13%   |
| Unknown     | 18        | 8.65%   |
| 701-800     | 7         | 3.37%   |
| 601-700     | 7         | 3.37%   |
| 351-400     | 6         | 2.88%   |
| 801-900     | 3         | 1.44%   |
| 1501-2000   | 1         | 0.48%   |
| 101-200     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 134       | 69.07%  |
| 16/10   | 25        | 12.89%  |
| Unknown | 17        | 8.76%   |
| 21/9    | 8         | 4.12%   |
| 3/2     | 7         | 3.61%   |
| 5/4     | 2         | 1.03%   |
| 4/3     | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 24.52%  |
| 201-250        | 33        | 15.87%  |
| 81-90          | 31        | 14.9%   |
| Unknown        | 18        | 8.65%   |
| 251-300        | 12        | 5.77%   |
| 351-500        | 11        | 5.29%   |
| 301-350        | 9         | 4.33%   |
| 71-80          | 7         | 3.37%   |
| 51-60          | 7         | 3.37%   |
| 111-120        | 5         | 2.4%    |
| 61-70          | 4         | 1.92%   |
| 151-200        | 4         | 1.92%   |
| 121-130        | 3         | 1.44%   |
| 501-1000       | 3         | 1.44%   |
| 41-50          | 2         | 0.96%   |
| 141-150        | 2         | 0.96%   |
| 131-140        | 2         | 0.96%   |
| 91-100         | 2         | 0.96%   |
| More than 1000 | 1         | 0.48%   |
| 1-40           | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 59        | 28.23%  |
| 51-100        | 57        | 27.27%  |
| 101-120       | 51        | 24.4%   |
| 161-240       | 19        | 9.09%   |
| Unknown       | 18        | 8.61%   |
| More than 240 | 4         | 1.91%   |
| 1-50          | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 160       | 80.81%  |
| 2     | 34        | 17.17%  |
| 0     | 4         | 2.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 110       | 38.33%  |
| Intel                            | 81        | 28.22%  |
| Qualcomm Atheros                 | 25        | 8.71%   |
| Broadcom                         | 16        | 5.57%   |
| MediaTek                         | 7         | 2.44%   |
| TP-Link                          | 5         | 1.74%   |
| Ralink Technology                | 5         | 1.74%   |
| Broadcom Limited                 | 5         | 1.74%   |
| Qualcomm                         | 4         | 1.39%   |
| Xiaomi                           | 3         | 1.05%   |
| Sierra Wireless                  | 3         | 1.05%   |
| Ralink                           | 2         | 0.7%    |
| Qualcomm Atheros Communications  | 2         | 0.7%    |
| Marvell Technology Group         | 2         | 0.7%    |
| Cypress Semiconductor            | 2         | 0.7%    |
| Aquantia                         | 2         | 0.7%    |
| Tenda                            | 1         | 0.35%   |
| STMicroelectronics               | 1         | 0.35%   |
| Standard Microsystems            | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Qualcomm Technologies            | 1         | 0.35%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.35%   |
| Nvidia                           | 1         | 0.35%   |
| Huawei Technologies              | 1         | 0.35%   |
| DisplayLink                      | 1         | 0.35%   |
| ASUSTek Computer                 | 1         | 0.35%   |
| ASIX Electronics                 | 1         | 0.35%   |
| Arduino SA                       | 1         | 0.35%   |
| Apple                            | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 72        | 21.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 4.55%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 4.55%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 2.42%   |
| Intel Wireless 8265 / 8275                                             | 8         | 2.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 2.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.52%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.52%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 4         | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.21%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.91%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.91%   |
| Intel Wireless 8260                                                    | 3         | 0.91%   |
| Intel Wireless 7265                                                    | 3         | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.61%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2         | 0.61%   |
| Intel Wireless 7260                                                    | 2         | 0.61%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 0.61%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.61%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 41.94%  |
| Realtek Semiconductor           | 29        | 18.71%  |
| Qualcomm Atheros                | 20        | 12.9%   |
| Broadcom                        | 10        | 6.45%   |
| MediaTek                        | 6         | 3.87%   |
| Ralink Technology               | 5         | 3.23%   |
| TP-Link                         | 4         | 2.58%   |
| Qualcomm                        | 4         | 2.58%   |
| Sierra Wireless                 | 3         | 1.94%   |
| Broadcom Limited                | 3         | 1.94%   |
| Ralink                          | 2         | 1.29%   |
| Qualcomm Atheros Communications | 2         | 1.29%   |
| Tenda                           | 1         | 0.65%   |
| ASUSTek Computer                | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 15        | 9.62%   |
| Intel Wireless 8265 / 8275                                    | 8         | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 7         | 4.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 6         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 3.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 3.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 3.21%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 3.21%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 4         | 2.56%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 4         | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.92%   |
| Ralink MT7601U Wireless Adapter                               | 3         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 3         | 1.92%   |
| Intel Wireless 8260                                           | 3         | 1.92%   |
| Intel Wireless 7265                                           | 3         | 1.92%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]     | 3         | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 3         | 1.92%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2         | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                               | 2         | 1.28%   |
| Intel Wireless 7260                                           | 2         | 1.28%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.28%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]       | 2         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 2         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.28%   |
| Broadcom BCM4311 802.11b/g WLAN                               | 2         | 1.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1         | 0.64%   |
| TP-Link 802.11n NIC                                           | 1         | 0.64%   |
| Tenda U12                                                     | 1         | 0.64%   |
| Sierra Wireless EM7455                                        | 1         | 0.64%   |
| Sierra Wireless EM7345 4G LTE                                 | 1         | 0.64%   |
| Sierra Wireless EM7305 Modem                                  | 1         | 0.64%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 1         | 0.64%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter               | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 100       | 59.52%  |
| Intel                            | 35        | 20.83%  |
| Broadcom                         | 7         | 4.17%   |
| Qualcomm Atheros                 | 6         | 3.57%   |
| Xiaomi                           | 3         | 1.79%   |
| Marvell Technology Group         | 2         | 1.19%   |
| Cypress Semiconductor            | 2         | 1.19%   |
| Broadcom Limited                 | 2         | 1.19%   |
| Aquantia                         | 2         | 1.19%   |
| TP-Link                          | 1         | 0.6%    |
| Standard Microsystems            | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Nvidia                           | 1         | 0.6%    |
| MediaTek                         | 1         | 0.6%    |
| Huawei Technologies              | 1         | 0.6%    |
| DisplayLink                      | 1         | 0.6%    |
| ASIX Electronics                 | 1         | 0.6%    |
| Apple                            | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 72        | 42.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 8.88%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 4.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 3.55%   |
| Intel I211 Gigabit Network Connection                                  | 5         | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.37%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 2.37%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 1.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.18%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.18%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 1.18%   |
| Cypress K38231_03                                                      | 2         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.59%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.59%   |
| Standard Microsystems Ethernet controller                              | 1         | 0.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.59%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.59%   |
| MediaTek File-CD Gadget                                                | 1         | 0.59%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.59%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.59%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.59%   |
| Intel Ethernet Controller I226-V                                       | 1         | 0.59%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.59%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.59%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.59%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.59%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.59%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.59%   |
| Huawei STG-LX1                                                         | 1         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 158       | 51.13%  |
| WiFi     | 146       | 47.25%  |
| Modem    | 3         | 0.97%   |
| Unknown  | 2         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 60.2%   |
| Ethernet | 78        | 39.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 90        | 45.92%  |
| 1     | 87        | 44.39%  |
| 3     | 9         | 4.59%   |
| 0     | 9         | 4.59%   |
| 4     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 162       | 81.82%  |
| Yes  | 36        | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 56        | 42.42%  |
| Realtek Semiconductor           | 17        | 12.88%  |
| Lite-On Technology              | 9         | 6.82%   |
| Broadcom                        | 9         | 6.82%   |
| Cambridge Silicon Radio         | 8         | 6.06%   |
| IMC Networks                    | 7         | 5.3%    |
| Foxconn / Hon Hai               | 7         | 5.3%    |
| Qualcomm Atheros Communications | 4         | 3.03%   |
| USI                             | 3         | 2.27%   |
| Realtek                         | 2         | 1.52%   |
| Apple                           | 2         | 1.52%   |
| Toshiba                         | 1         | 0.76%   |
| SIN                             | 1         | 0.76%   |
| Ralink                          | 1         | 0.76%   |
| Opticis                         | 1         | 0.76%   |
| Foxconn International           | 1         | 0.76%   |
| Dell                            | 1         | 0.76%   |
| ASUSTek Computer                | 1         | 0.76%   |
| Actions                         | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 12.03%  |
| Intel AX200 Bluetooth                               | 15        | 11.28%  |
| Realtek Bluetooth Radio                             | 10        | 7.52%   |
| Intel AX201 Bluetooth                               | 9         | 6.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 6.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 3.01%   |
| USI Bluetooth Device                                | 3         | 2.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.26%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 2.26%   |
| Intel Bluetooth Device                              | 3         | 2.26%   |
| Intel AX210 Bluetooth                               | 3         | 2.26%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.26%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 2.26%   |
| Realtek Bluetooth Radio                             | 2         | 1.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.5%    |
| Lite-On Bluetooth Device                            | 2         | 1.5%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.5%    |
| IMC Networks Bluetooth Device                       | 2         | 1.5%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.75%   |
| SIN Bluetooth Keyboard                              | 1         | 0.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.75%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.75%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.75%   |
| Opticis Bluetooth Radio                             | 1         | 0.75%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.75%   |
| IMC Networks Wireless_Device                        | 1         | 0.75%   |
| IMC Networks Bluetooth                              | 1         | 0.75%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.75%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.75%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.75%   |
| Broadcom HP Portable Valentine                      | 1         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 115       | 41.52%  |
| AMD                                  | 76        | 27.44%  |
| Nvidia                               | 45        | 16.25%  |
| Logitech                             | 6         | 2.17%   |
| C-Media Electronics                  | 6         | 2.17%   |
| JMTek                                | 5         | 1.81%   |
| Texas Instruments                    | 2         | 0.72%   |
| Creative Technology                  | 2         | 0.72%   |
| Corsair                              | 2         | 0.72%   |
| VIA Technologies                     | 1         | 0.36%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.36%   |
| SteelSeries ApS                      | 1         | 0.36%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.36%   |
| SAVITECH                             | 1         | 0.36%   |
| Razer USA                            | 1         | 0.36%   |
| KTMicro                              | 1         | 0.36%   |
| Fry's Electronics                    | 1         | 0.36%   |
| Focusrite-Novation                   | 1         | 0.36%   |
| Elgato Systems                       | 1         | 0.36%   |
| EDFIER                               | 1         | 0.36%   |
| Cambridge Silicon Radio              | 1         | 0.36%   |
| Cambridge Audio                      | 1         | 0.36%   |
| Blue Microphones                     | 1         | 0.36%   |
| BEHRINGER International              | 1         | 0.36%   |
| Astro Gaming                         | 1         | 0.36%   |
| ASRock                               | 1         | 0.36%   |
| Apple                                | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 8%      |
| AMD Starship/Matisse HD Audio Controller                                   | 16        | 4.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 4.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 4.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 3.14%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.14%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 2%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 2%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.71%   |
| JMTek USB PnP Audio Device                                                 | 5         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.43%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.43%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.14%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.14%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 1.14%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.14%   |
| AMD High Definition Audio Controller                                       | 4         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.14%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.86%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.86%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3         | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 37        | 23.57%  |
| Samsung Electronics | 35        | 22.29%  |
| Micron Technology   | 20        | 12.74%  |
| Kingston            | 13        | 8.28%   |
| Unknown             | 11        | 7.01%   |
| G.Skill             | 9         | 5.73%   |
| Corsair             | 9         | 5.73%   |
| A-DATA Technology   | 6         | 3.82%   |
| Crucial             | 5         | 3.18%   |
| Ramaxel Technology  | 3         | 1.91%   |
| Unknown (ABCD)      | 1         | 0.64%   |
| Transcend           | 1         | 0.64%   |
| Team                | 1         | 0.64%   |
| Patriot             | 1         | 0.64%   |
| Nanya Technology    | 1         | 0.64%   |
| Elpida              | 1         | 0.64%   |
| Avant               | 1         | 0.64%   |
| 4ea5                | 1         | 0.64%   |
| 48spaces            | 1         | 0.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 1.76%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 2         | 1.18%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.18%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.18%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 1.18%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 1.18%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s          | 2         | 1.18%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 2         | 1.18%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s              | 2         | 1.18%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 2         | 1.18%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                           | 1         | 0.59%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                    | 1         | 0.59%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                        | 1         | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                         | 1         | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 1         | 0.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 1         | 0.59%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                            | 1         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.59%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.59%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 1         | 0.59%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                       | 1         | 0.59%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.59%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                          | 1         | 0.59%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s                | 1         | 0.59%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 64        | 47.06%  |
| DDR3    | 45        | 33.09%  |
| LPDDR5  | 7         | 5.15%   |
| LPDDR4  | 5         | 3.68%   |
| LPDDR3  | 4         | 2.94%   |
| DDR2    | 4         | 2.94%   |
| DDR5    | 3         | 2.21%   |
| Unknown | 3         | 2.21%   |
| DDR     | 1         | 0.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 59.56%  |
| DIMM         | 41        | 30.15%  |
| Row Of Chips | 13        | 9.56%   |
| Unknown      | 1         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 64        | 42.67%  |
| 4096  | 46        | 30.67%  |
| 16384 | 17        | 11.33%  |
| 2048  | 13        | 8.67%   |
| 1024  | 5         | 3.33%   |
| 512   | 3         | 2%      |
| 32768 | 2         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 22.15%  |
| 2667    | 22        | 14.77%  |
| 3200    | 21        | 14.09%  |
| 2400    | 11        | 7.38%   |
| 1333    | 11        | 7.38%   |
| 6400    | 7         | 4.7%    |
| 3600    | 6         | 4.03%   |
| 1334    | 5         | 3.36%   |
| 2133    | 4         | 2.68%   |
| 4800    | 3         | 2.01%   |
| 1867    | 3         | 2.01%   |
| 667     | 3         | 2.01%   |
| 533     | 3         | 2.01%   |
| 3866    | 2         | 1.34%   |
| 3733    | 2         | 1.34%   |
| 3534    | 2         | 1.34%   |
| 8400    | 1         | 0.67%   |
| 4266    | 1         | 0.67%   |
| 3333    | 1         | 0.67%   |
| 3266    | 1         | 0.67%   |
| 3066    | 1         | 0.67%   |
| 3000    | 1         | 0.67%   |
| 2933    | 1         | 0.67%   |
| 2800    | 1         | 0.67%   |
| 2666    | 1         | 0.67%   |
| 1067    | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 38        | 28.57%  |
| IMC Networks                           | 18        | 13.53%  |
| Microdia                               | 13        | 9.77%   |
| Realtek Semiconductor                  | 8         | 6.02%   |
| Bison Electronics                      | 8         | 6.02%   |
| Quanta                                 | 7         | 5.26%   |
| Logitech                               | 7         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.76%   |
| Sunplus Innovation Technology          | 4         | 3.01%   |
| Acer                                   | 4         | 3.01%   |
| Syntek                                 | 3         | 2.26%   |
| Suyin                                  | 3         | 2.26%   |
| MacroSilicon                           | 2         | 1.5%    |
| Luxvisions Innotech Limited            | 2         | 1.5%    |
| WaveRider Communications               | 1         | 0.75%   |
| SunplusIT                              | 1         | 0.75%   |
| Sonix Technology                       | 1         | 0.75%   |
| Silicon Motion                         | 1         | 0.75%   |
| Samsung Electronics                    | 1         | 0.75%   |
| Microsoft                              | 1         | 0.75%   |
| Intel                                  | 1         | 0.75%   |
| GEMBIRD                                | 1         | 0.75%   |
| Asuscom Network                        | 1         | 0.75%   |
| Apple                                  | 1         | 0.75%   |
| Alcor Micro                            | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 11        | 8.15%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 5.19%   |
| Chicony HP Truevision HD camera               | 4         | 2.96%   |
| Syntek Integrated Camera                      | 3         | 2.22%   |
| Suyin HP Truevision HD                        | 3         | 2.22%   |
| Realtek USB Camera                            | 3         | 2.22%   |
| Quanta HD User Facing                         | 3         | 2.22%   |
| Microdia Integrated_Webcam_HD                 | 3         | 2.22%   |
| Logitech Webcam C270                          | 3         | 2.22%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 2.22%   |
| Chicony USB 2.0 Camera                        | 3         | 2.22%   |
| Chicony HD Webcam                             | 3         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.22%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.48%   |
| Microdia Webcam Vitade AF                     | 2         | 1.48%   |
| Microdia USB 2.0 Camera                       | 2         | 1.48%   |
| Microdia HP Integrated Webcam                 | 2         | 1.48%   |
| IMC Networks Integrated Camera                | 2         | 1.48%   |
| IMC Networks HD Camera                        | 2         | 1.48%   |
| Chicony USB2.0 Camera                         | 2         | 1.48%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.48%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.48%   |
| Chicony HD User Facing                        | 2         | 1.48%   |
| Chicony EasyCamera                            | 2         | 1.48%   |
| Bison Lenovo EasyCamera                       | 2         | 1.48%   |
| Bison Integrated RGB Camera                   | 2         | 1.48%   |
| Acer SunplusIT Integrated Camera              | 2         | 1.48%   |
| WaveRider USB Live camera                     | 1         | 0.74%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.74%   |
| Sunplus USB 2.0 Camera                        | 1         | 0.74%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.74%   |
| Sonix NexiGo HD Webcam                        | 1         | 0.74%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.74%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 0.74%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.74%   |
| Realtek Laptop Camera                         | 1         | 0.74%   |
| Realtek Integrated Webcam HD                  | 1         | 0.74%   |
| Realtek HD WebCam                             | 1         | 0.74%   |
| Realtek FULL HD 1080P Webcam                  | 1         | 0.74%   |
| Quanta VGA WebCam                             | 1         | 0.74%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 47.37%  |
| Shenzhen Goodix Technology | 4         | 21.05%  |
| Validity Sensors           | 3         | 15.79%  |
| Elan Microelectronics      | 2         | 10.53%  |
| Upek                       | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 26.32%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 15.79%  |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 15.79%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 5.26%   |
| Synaptics UWP WBDI Device                              | 1         | 5.26%   |
| Synaptics  WBDI                                        | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 66.67%  |
| Lenovo      | 1         | 16.67%  |
| Broadcom    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 4         | 66.67%  |
| Lenovo Integrated Smart Card Reader            | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 147       | 74.62%  |
| 1     | 37        | 18.78%  |
| 2     | 11        | 5.58%   |
| 3     | 2         | 1.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 30.16%  |
| Graphics card            | 14        | 22.22%  |
| Net/wireless             | 7         | 11.11%  |
| Chipcard                 | 6         | 9.52%   |
| Sound                    | 4         | 6.35%   |
| Multimedia controller    | 4         | 6.35%   |
| Camera                   | 4         | 6.35%   |
| Communication controller | 2         | 3.17%   |
| Network                  | 1         | 1.59%   |
| Net/ethernet             | 1         | 1.59%   |
| Bluetooth                | 1         | 1.59%   |

