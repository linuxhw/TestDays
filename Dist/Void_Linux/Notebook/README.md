Void Linux - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Void Linux.

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

Total: 166

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420 4180D81       | [586b69e749](https://linux-hardware.org/?probe=586b69e749) | Apr 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [4113f409f3](https://linux-hardware.org/?probe=4113f409f3) | Apr 22, 2024 |
| Lenovo        | ThinkPad T520 42433ZG       | [d2899d8de6](https://linux-hardware.org/?probe=d2899d8de6) | Apr 19, 2024 |
| HP            | Stream Laptop 14-cb1xxx     | [02724e5adf](https://linux-hardware.org/?probe=02724e5adf) | Apr 15, 2024 |
| ASUSTek       | E402MA                      | [58a1e32393](https://linux-hardware.org/?probe=58a1e32393) | Apr 14, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d6d03b4ad2](https://linux-hardware.org/?probe=d6d03b4ad2) | Apr 14, 2024 |
| Apple         | MacBookPro11,1              | [4e18f485f3](https://linux-hardware.org/?probe=4e18f485f3) | Apr 11, 2024 |
| Acer          | E1-510                      | [c53095abd3](https://linux-hardware.org/?probe=c53095abd3) | Apr 10, 2024 |
| Dell          | Latitude 5400               | [20fa0e002d](https://linux-hardware.org/?probe=20fa0e002d) | Mar 23, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [d5c50b0264](https://linux-hardware.org/?probe=d5c50b0264) | Mar 20, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [14b3cedbef](https://linux-hardware.org/?probe=14b3cedbef) | Mar 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d2152999e9](https://linux-hardware.org/?probe=d2152999e9) | Mar 13, 2024 |
| Lenovo        | ThinkPad T480 20L6S37W04    | [1278612ad9](https://linux-hardware.org/?probe=1278612ad9) | Mar 05, 2024 |
| Lenovo        | ThinkPad E590 20NB001AUK    | [45eadbd174](https://linux-hardware.org/?probe=45eadbd174) | Mar 03, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4dd27fbd4e](https://linux-hardware.org/?probe=4dd27fbd4e) | Feb 23, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [99f1228781](https://linux-hardware.org/?probe=99f1228781) | Feb 20, 2024 |
| Dell          | Latitude 7420               | [29ce5896a7](https://linux-hardware.org/?probe=29ce5896a7) | Feb 05, 2024 |
| Dell          | Latitude 7420               | [cdd5031988](https://linux-hardware.org/?probe=cdd5031988) | Feb 04, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [3cec123511](https://linux-hardware.org/?probe=3cec123511) | Feb 04, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [971c919cef](https://linux-hardware.org/?probe=971c919cef) | Jan 20, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Toshiba       | Satellite A200              | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Dell          | Inspiron N5010              | [cc169dad66](https://linux-hardware.org/?probe=cc169dad66) | Jan 08, 2024 |
| Acer          | Aspire A515-44              | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [cd261e1bc3](https://linux-hardware.org/?probe=cd261e1bc3) | Dec 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [5f97c0d536](https://linux-hardware.org/?probe=5f97c0d536) | Dec 13, 2023 |
| ASUSTek       | G750JX                      | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| HP            | Pavilion 11 x360 PC         | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| Lenovo        | Ducati 5 82ES               | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [426fd54105](https://linux-hardware.org/?probe=426fd54105) | Nov 15, 2023 |
| MSI           | Prestige 15 A10SC           | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| Google        | Phaser360                   | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | Latitude D610               | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| Unknown       | Unknown                     | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| MSI           | GF63 Thin 10SCXR            | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| HP            | 15                          | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| Acer          | Aspire A515-57              | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| Notebook      | NH50_70RA                   | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| ASUSTek       | X751LD                      | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| HP            | 255 G7 Notebook PC          | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| Lenovo        | B50-80 80EW                 | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| MSI           | GV72 7RE                    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Exo           | Exomate X352                | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Nokia         | Booklet 3G                  | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| HUAWEI        | HN-WX9X                     | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| ASUSTek       | X751LD                      | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Acer          | Aspire E1-531               | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Acer          | Aspire E1-531               | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| HP            | Laptop 15-bw0xx             | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| Samsung       | 275E4E/275E5E               | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| Lenovo        | G50-45 80E3                 | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| HP            | Laptop 14-dk0xxx            | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| Acer          | Aspire SW5-015              | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| Dell          | Inspiron 11 - 3148          | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| Acer          | AO722                       | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| Acer          | Nitro AN715-51              | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| Acer          | AO722                       | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| Dell          | Inspiron 1501               | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| Digibras      | NH4CU03                     | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| Positivo      | Mobile                      | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 108       | 79.41%  |
| Void Linux         | 28        | 20.59%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Void Linux | 135       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 6.3.13_1          | 7         | 4.93%   |
| 5.13.19_1         | 5         | 3.52%   |
| 6.6.22_1          | 4         | 2.82%   |
| 6.3.12_1          | 4         | 2.82%   |
| 5.18.19_1         | 4         | 2.82%   |
| 6.1.4_1           | 3         | 2.11%   |
| 5.8.18_1          | 3         | 2.11%   |
| 5.8.12_1          | 3         | 2.11%   |
| 5.3.9_1           | 3         | 2.11%   |
| 5.19.17_1         | 3         | 2.11%   |
| 5.10.17_1         | 3         | 2.11%   |
| 6.7.6_1           | 2         | 1.41%   |
| 6.6.9_1           | 2         | 1.41%   |
| 6.6.25_1          | 2         | 1.41%   |
| 6.6.16_1          | 2         | 1.41%   |
| 6.6.11_1          | 2         | 1.41%   |
| 6.5.13_1          | 2         | 1.41%   |
| 6.5.11_1          | 2         | 1.41%   |
| 6.5.10_1          | 2         | 1.41%   |
| 6.1.31_1          | 2         | 1.41%   |
| 6.1.21_1          | 2         | 1.41%   |
| 6.1.10_1          | 2         | 1.41%   |
| 5.4.24_1          | 2         | 1.41%   |
| 5.19.16_1         | 2         | 1.41%   |
| 5.18.14_1         | 2         | 1.41%   |
| 5.16.20_1         | 2         | 1.41%   |
| 5.15.32_1         | 2         | 1.41%   |
| 5.13.13_1         | 2         | 1.41%   |
| 5.12.10_1         | 2         | 1.41%   |
| 6.9.0-rc4_current | 1         | 0.7%    |
| 6.8.7_1           | 1         | 0.7%    |
| 6.8.6_1           | 1         | 0.7%    |
| 6.8.0-zen1_1      | 1         | 0.7%    |
| 6.6.23_1          | 1         | 0.7%    |
| 6.6.21_1          | 1         | 0.7%    |
| 6.6.1_1           | 1         | 0.7%    |
| 6.6.17_1          | 1         | 0.7%    |
| 6.5.5_2           | 1         | 0.7%    |
| 6.5.12_1          | 1         | 0.7%    |
| 6.4.8_1           | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.3.13  | 7         | 4.93%   |
| 5.13.19 | 5         | 3.52%   |
| 6.6.22  | 4         | 2.82%   |
| 6.3.12  | 4         | 2.82%   |
| 5.8.12  | 4         | 2.82%   |
| 5.18.19 | 4         | 2.82%   |
| 6.1.4   | 3         | 2.11%   |
| 5.8.18  | 3         | 2.11%   |
| 5.3.9   | 3         | 2.11%   |
| 5.19.17 | 3         | 2.11%   |
| 5.10.17 | 3         | 2.11%   |
| 6.7.6   | 2         | 1.41%   |
| 6.6.9   | 2         | 1.41%   |
| 6.6.25  | 2         | 1.41%   |
| 6.6.16  | 2         | 1.41%   |
| 6.6.11  | 2         | 1.41%   |
| 6.5.13  | 2         | 1.41%   |
| 6.5.11  | 2         | 1.41%   |
| 6.5.10  | 2         | 1.41%   |
| 6.1.31  | 2         | 1.41%   |
| 6.1.21  | 2         | 1.41%   |
| 6.1.10  | 2         | 1.41%   |
| 5.4.24  | 2         | 1.41%   |
| 5.19.16 | 2         | 1.41%   |
| 5.18.14 | 2         | 1.41%   |
| 5.16.20 | 2         | 1.41%   |
| 5.15.32 | 2         | 1.41%   |
| 5.13.13 | 2         | 1.41%   |
| 5.12.10 | 2         | 1.41%   |
| 6.9.0   | 1         | 0.7%    |
| 6.8.7   | 1         | 0.7%    |
| 6.8.6   | 1         | 0.7%    |
| 6.8.0   | 1         | 0.7%    |
| 6.6.23  | 1         | 0.7%    |
| 6.6.21  | 1         | 0.7%    |
| 6.6.17  | 1         | 0.7%    |
| 6.6.1   | 1         | 0.7%    |
| 6.5.5   | 1         | 0.7%    |
| 6.5.12  | 1         | 0.7%    |
| 6.4.8   | 1         | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.6     | 15        | 10.71%  |
| 6.1     | 14        | 10%     |
| 5.15    | 12        | 8.57%   |
| 6.3     | 11        | 7.86%   |
| 5.8     | 11        | 7.86%   |
| 5.13    | 11        | 7.86%   |
| 6.5     | 8         | 5.71%   |
| 5.18    | 7         | 5%      |
| 5.12    | 7         | 5%      |
| 5.10    | 7         | 5%      |
| 5.4     | 5         | 3.57%   |
| 5.19    | 5         | 3.57%   |
| 6.8     | 3         | 2.14%   |
| 6.0     | 3         | 2.14%   |
| 5.9     | 3         | 2.14%   |
| 5.3     | 3         | 2.14%   |
| 6.7     | 2         | 1.43%   |
| 6.2     | 2         | 1.43%   |
| 5.16    | 2         | 1.43%   |
| 6.9     | 1         | 0.71%   |
| 6.4     | 1         | 0.71%   |
| 5.7     | 1         | 0.71%   |
| 5.2     | 1         | 0.71%   |
| 5.14    | 1         | 0.71%   |
| 5.11    | 1         | 0.71%   |
| 5.1     | 1         | 0.71%   |
| 4.4     | 1         | 0.71%   |
| 4.14    | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 129       | 95.56%  |
| i686    | 4         | 2.96%   |
| aarch64 | 2         | 1.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 53        | 38.13%  |
| XFCE              | 21        | 15.11%  |
| KDE5              | 12        | 8.63%   |
| KDE               | 11        | 7.91%   |
| MATE              | 9         | 6.47%   |
| gnome             | 7         | 5.04%   |
| i3                | 6         | 4.32%   |
| sway              | 5         | 3.6%    |
| X-Cinnamon        | 2         | 1.44%   |
| bspwm             | 2         | 1.44%   |
| awesome           | 2         | 1.44%   |
| X-Generic         | 1         | 0.72%   |
| river             | 1         | 0.72%   |
| openbox           | 1         | 0.72%   |
| LXQt              | 1         | 0.72%   |
| LXDE              | 1         | 0.72%   |
| Lumina            | 1         | 0.72%   |
| dwm               | 1         | 0.72%   |
| dot-xsession      | 1         | 0.72%   |
| awesome-with-dbus | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 88        | 64.71%  |
| Wayland | 24        | 17.65%  |
| Tty     | 16        | 11.76%  |
| Unknown | 8         | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 98        | 72.06%  |
| LightDM | 16        | 11.76%  |
| SDDM    | 13        | 9.56%   |
| LXDM    | 6         | 4.41%   |
| SLiM    | 1         | 0.74%   |
| LDM     | 1         | 0.74%   |
| GDM     | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 75        | 54.74%  |
| en_GB   | 11        | 8.03%   |
| Unknown | 11        | 8.03%   |
| C       | 6         | 4.38%   |
| it_IT   | 5         | 3.65%   |
| en_DK   | 5         | 3.65%   |
| es_ES   | 4         | 2.92%   |
| de_DE   | 4         | 2.92%   |
| fr_FR   | 2         | 1.46%   |
| en_CA   | 2         | 1.46%   |
| tr_TR   | 1         | 0.73%   |
| ru_UA   | 1         | 0.73%   |
| ru_RU   | 1         | 0.73%   |
| pt_BR   | 1         | 0.73%   |
| nb_NO   | 1         | 0.73%   |
| es_HN   | 1         | 0.73%   |
| es_DO   | 1         | 0.73%   |
| es_AR   | 1         | 0.73%   |
| en_NZ   | 1         | 0.73%   |
| en_AU   | 1         | 0.73%   |
| el_GR   | 1         | 0.73%   |
| ca_ES   | 1         | 0.73%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 86        | 63.24%  |
| BIOS | 50        | 36.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 60.29%  |
| Btrfs   | 35        | 25.74%  |
| Xfs     | 6         | 4.41%   |
| Unknown | 5         | 3.68%   |
| Zfs     | 3         | 2.21%   |
| Overlay | 2         | 1.47%   |
| F2fs    | 2         | 1.47%   |
| Ext3    | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 90        | 65.69%  |
| Unknown | 33        | 24.09%  |
| MBR     | 14        | 10.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 122       | 89.71%  |
| Yes       | 14        | 10.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 77.94%  |
| Yes       | 30        | 22.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 29.63%  |
| Hewlett-Packard     | 19        | 14.07%  |
| ASUSTek Computer    | 17        | 12.59%  |
| Acer                | 16        | 11.85%  |
| Dell                | 13        | 9.63%   |
| MSI                 | 6         | 4.44%   |
| HUAWEI              | 3         | 2.22%   |
| Unknown             | 3         | 2.22%   |
| Notebook            | 2         | 1.48%   |
| Framework           | 2         | 1.48%   |
| Apple               | 2         | 1.48%   |
| Toshiba             | 1         | 0.74%   |
| Timi                | 1         | 0.74%   |
| Samsung Electronics | 1         | 0.74%   |
| Razer               | 1         | 0.74%   |
| Positivo            | 1         | 0.74%   |
| Pine Microsystems   | 1         | 0.74%   |
| Nokia               | 1         | 0.74%   |
| Google              | 1         | 0.74%   |
| Getac               | 1         | 0.74%   |
| Exo                 | 1         | 0.74%   |
| Digibras            | 1         | 0.74%   |
| Chuwi               | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Unknown                                   | 3         | 2.22%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW     | 2         | 1.48%   |
| HP Pavilion Notebook                      | 2         | 1.48%   |
| HP Laptop 15-bw0xx                        | 2         | 1.48%   |
| HP 15                                     | 2         | 1.48%   |
| ASUS X751LD                               | 2         | 1.48%   |
| Apple MacBookPro11,1                      | 2         | 1.48%   |
| Acer Swift SF314-42                       | 2         | 1.48%   |
| Toshiba Satellite A200                    | 1         | 0.74%   |
| Timi Redmi Book Pro 15 2022               | 1         | 0.74%   |
| Samsung 275E4E/275E5E                     | 1         | 0.74%   |
| Razer Blade 14 (2022) - RZ09-0427         | 1         | 0.74%   |
| Positivo Mobile                           | 1         | 0.74%   |
| Pine Microsystems Pine64 Pinebook Pro     | 1         | 0.74%   |
| Notebook NV4XMB,ME,MZ                     | 1         | 0.74%   |
| Notebook NH50_70RA                        | 1         | 0.74%   |
| Nokia Booklet 3G                          | 1         | 0.74%   |
| MSI Summit E13FlipEvo A12MT               | 1         | 0.74%   |
| MSI Prestige 15 A10SC                     | 1         | 0.74%   |
| MSI GV72 7RE                              | 1         | 0.74%   |
| MSI GF63 Thin 10SCXR                      | 1         | 0.74%   |
| MSI GE60 2OC\2OD\2OE                      | 1         | 0.74%   |
| MSI Bravo 15 A4DDR                        | 1         | 0.74%   |
| Lenovo Y520-15IKB 80YY                    | 1         | 0.74%   |
| Lenovo ThinkPad X260 20F5S08Q00           | 1         | 0.74%   |
| Lenovo ThinkPad X240 20AMA34HMN           | 1         | 0.74%   |
| Lenovo ThinkPad X201 3680BR4              | 1         | 0.74%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 1         | 0.74%   |
| Lenovo ThinkPad T520 42433ZG              | 1         | 0.74%   |
| Lenovo ThinkPad T490 20N20046US           | 1         | 0.74%   |
| Lenovo ThinkPad T480 20L6SA5Q00           | 1         | 0.74%   |
| Lenovo ThinkPad T480 20L6S37W04           | 1         | 0.74%   |
| Lenovo ThinkPad T460 20FMS0WN00           | 1         | 0.74%   |
| Lenovo ThinkPad T430 2349PS3              | 1         | 0.74%   |
| Lenovo ThinkPad T420 4236PG6              | 1         | 0.74%   |
| Lenovo ThinkPad T420 4180D81              | 1         | 0.74%   |
| Lenovo ThinkPad T420 4180A21              | 1         | 0.74%   |
| Lenovo ThinkPad T16 Gen 1 21CHCTO1WW      | 1         | 0.74%   |
| Lenovo ThinkPad T14s Gen 1 20UHCTO1WW     | 1         | 0.74%   |
| Lenovo ThinkPad T14s Gen 1 20T1S04V00     | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 23        | 17.04%  |
| Acer Aspire              | 10        | 7.41%   |
| Lenovo IdeaPad           | 9         | 6.67%   |
| ASUS VivoBook            | 8         | 5.93%   |
| Dell Latitude            | 6         | 4.44%   |
| HP Pavilion              | 5         | 3.7%    |
| HP Laptop                | 5         | 3.7%    |
| Dell Inspiron            | 4         | 2.96%   |
| Lenovo ThinkBook         | 3         | 2.22%   |
| Unknown                  | 3         | 2.22%   |
| HP Stream                | 2         | 1.48%   |
| HP ENVY                  | 2         | 1.48%   |
| HP 255                   | 2         | 1.48%   |
| HP 15                    | 2         | 1.48%   |
| Framework Laptop         | 2         | 1.48%   |
| ASUS X751LD              | 2         | 1.48%   |
| Apple MacBookPro11       | 2         | 1.48%   |
| Acer Swift               | 2         | 1.48%   |
| Toshiba Satellite        | 1         | 0.74%   |
| Timi Redmi               | 1         | 0.74%   |
| Samsung 275E4E           | 1         | 0.74%   |
| Razer Blade              | 1         | 0.74%   |
| Positivo Mobile          | 1         | 0.74%   |
| Pine Microsystems Pine64 | 1         | 0.74%   |
| Notebook NV4XMB          | 1         | 0.74%   |
| Notebook NH50            | 1         | 0.74%   |
| Nokia Booklet            | 1         | 0.74%   |
| MSI Summit               | 1         | 0.74%   |
| MSI Prestige             | 1         | 0.74%   |
| MSI GV72                 | 1         | 0.74%   |
| MSI GF63                 | 1         | 0.74%   |
| MSI GE60                 | 1         | 0.74%   |
| MSI Bravo                | 1         | 0.74%   |
| Lenovo Y520-15IKB        | 1         | 0.74%   |
| Lenovo Legion            | 1         | 0.74%   |
| Lenovo G50-70            | 1         | 0.74%   |
| Lenovo G50-45            | 1         | 0.74%   |
| Lenovo Ducati            | 1         | 0.74%   |
| HUAWEI KLVL-WXXW         | 1         | 0.74%   |
| HUAWEI HN-WX9X           | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 22        | 16.3%   |
| 2020    | 18        | 13.33%  |
| 2022    | 12        | 8.89%   |
| 2018    | 10        | 7.41%   |
| 2014    | 10        | 7.41%   |
| 2013    | 10        | 7.41%   |
| 2015    | 9         | 6.67%   |
| 2021    | 8         | 5.93%   |
| 2016    | 7         | 5.19%   |
| 2011    | 6         | 4.44%   |
| 2017    | 5         | 3.7%    |
| 2023    | 3         | 2.22%   |
| 2012    | 3         | 2.22%   |
| 2010    | 2         | 1.48%   |
| 2009    | 2         | 1.48%   |
| 2008    | 2         | 1.48%   |
| 2007    | 2         | 1.48%   |
| Unknown | 2         | 1.48%   |
| 2006    | 1         | 0.74%   |
| 2005    | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 135       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 135       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 134       | 99.26%  |
| Yes  | 1         | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 38        | 27.74%  |
| 3.01-4.0    | 28        | 20.44%  |
| 16.01-24.0  | 23        | 16.79%  |
| 8.01-16.0   | 23        | 16.79%  |
| 32.01-64.0  | 7         | 5.11%   |
| 24.01-32.0  | 7         | 5.11%   |
| 1.01-2.0    | 7         | 5.11%   |
| 0.51-1.0    | 2         | 1.46%   |
| 64.01-256.0 | 1         | 0.73%   |
| 0.01-0.5    | 1         | 0.73%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 51        | 36.17%  |
| 2.01-3.0   | 31        | 21.99%  |
| 0.51-1.0   | 17        | 12.06%  |
| 4.01-8.0   | 16        | 11.35%  |
| 3.01-4.0   | 16        | 11.35%  |
| 0.01-0.5   | 5         | 3.55%   |
| 8.01-16.0  | 4         | 2.84%   |
| 16.01-24.0 | 1         | 0.71%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 80%     |
| 2      | 23        | 17.04%  |
| 3      | 3         | 2.22%   |
| 0      | 1         | 0.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 77.04%  |
| Yes       | 31        | 22.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 70.37%  |
| No        | 40        | 29.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 96.3%   |
| No        | 5         | 3.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 84.44%  |
| No        | 21        | 15.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 21        | 15.56%  |
| Russia             | 15        | 11.11%  |
| Germany            | 13        | 9.63%   |
| India              | 9         | 6.67%   |
| UK                 | 5         | 3.7%    |
| Italy              | 5         | 3.7%    |
| Brazil             | 5         | 3.7%    |
| Ukraine            | 4         | 2.96%   |
| Switzerland        | 4         | 2.96%   |
| Denmark            | 4         | 2.96%   |
| Canada             | 4         | 2.96%   |
| France             | 3         | 2.22%   |
| Czechia            | 3         | 2.22%   |
| Vietnam            | 2         | 1.48%   |
| Turkey             | 2         | 1.48%   |
| Spain              | 2         | 1.48%   |
| Poland             | 2         | 1.48%   |
| Norway             | 2         | 1.48%   |
| Netherlands        | 2         | 1.48%   |
| Morocco            | 2         | 1.48%   |
| Indonesia          | 2         | 1.48%   |
| Greece             | 2         | 1.48%   |
| Bulgaria           | 2         | 1.48%   |
| Australia          | 2         | 1.48%   |
| Argentina          | 2         | 1.48%   |
| Uruguay            | 1         | 0.74%   |
| Thailand           | 1         | 0.74%   |
| Serbia             | 1         | 0.74%   |
| Portugal           | 1         | 0.74%   |
| Peru               | 1         | 0.74%   |
| New Zealand        | 1         | 0.74%   |
| Mexico             | 1         | 0.74%   |
| Latvia             | 1         | 0.74%   |
| Jordan             | 1         | 0.74%   |
| Honduras           | 1         | 0.74%   |
| Guatemala          | 1         | 0.74%   |
| Grenada            | 1         | 0.74%   |
| Ecuador            | 1         | 0.74%   |
| Dominican Republic | 1         | 0.74%   |
| Colombia           | 1         | 0.74%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Moscow                 | 6         | 4.35%   |
| St Petersburg          | 3         | 2.17%   |
| Spring Hill            | 2         | 1.45%   |
| Sao Paulo              | 2         | 1.45%   |
| Rome                   | 2         | 1.45%   |
| Meknes                 | 2         | 1.45%   |
| Hyderabad              | 2         | 1.45%   |
| Geneva                 | 2         | 1.45%   |
| Zarqa                  | 1         | 0.72%   |
| Yambol                 | 1         | 0.72%   |
| Wilen bei Wollerau     | 1         | 0.72%   |
| Weatherford            | 1         | 0.72%   |
| Warsaw                 | 1         | 0.72%   |
| Volgograd              | 1         | 0.72%   |
| Vlaardingen            | 1         | 0.72%   |
| Vienna                 | 1         | 0.72%   |
| Viby J                 | 1         | 0.72%   |
| Verkhnyaya Pyshma      | 1         | 0.72%   |
| Vancouver              | 1         | 0.72%   |
| Trujillo               | 1         | 0.72%   |
| Toulouse               | 1         | 0.72%   |
| Touget                 | 1         | 0.72%   |
| Toms River             | 1         | 0.72%   |
| Tegucigalpa            | 1         | 0.72%   |
| Syktyvkar              | 1         | 0.72%   |
| Sydney                 | 1         | 0.72%   |
| Surabaya               | 1         | 0.72%   |
| Sun Prairie            | 1         | 0.72%   |
| Stratford              | 1         | 0.72%   |
| Stezzano               | 1         | 0.72%   |
| Stavropol              | 1         | 0.72%   |
| Solone                 | 1         | 0.72%   |
| Sohren                 | 1         | 0.72%   |
| Sofia                  | 1         | 0.72%   |
| Smolensk               | 1         | 0.72%   |
| Sistranda              | 1         | 0.72%   |
| Saxtons River          | 1         | 0.72%   |
| Santo Domingo          | 1         | 0.72%   |
| San Miguel de Tucumán | 1         | 0.72%   |
| San Antonio            | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 31     | 17.83%  |
| Seagate                     | 19        | 20     | 12.1%   |
| WDC                         | 13        | 14     | 8.28%   |
| SanDisk                     | 13        | 14     | 8.28%   |
| Unknown                     | 12        | 18     | 7.64%   |
| SK hynix                    | 11        | 12     | 7.01%   |
| Intel                       | 7         | 8      | 4.46%   |
| HGST                        | 7         | 8      | 4.46%   |
| Kingston                    | 6         | 6      | 3.82%   |
| Toshiba                     | 5         | 5      | 3.18%   |
| Crucial                     | 5         | 6      | 3.18%   |
| Micron Technology           | 3         | 3      | 1.91%   |
| Hitachi                     | 3         | 3      | 1.91%   |
| Phison Electronics          | 2         | 2      | 1.27%   |
| Phison                      | 2         | 2      | 1.27%   |
| Patriot                     | 2         | 2      | 1.27%   |
| Lenovo                      | 2         | 2      | 1.27%   |
| KIOXIA                      | 2         | 2      | 1.27%   |
| Kingston Technology Company | 2         | 2      | 1.27%   |
| Apple                       | 2         | 2      | 1.27%   |
| XrayDisk                    | 1         | 1      | 0.64%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.64%   |
| Transcend                   | 1         | 1      | 0.64%   |
| PNY                         | 1         | 1      | 0.64%   |
| ORIGIN                      | 1         | 1      | 0.64%   |
| Micron/Crucial Technology   | 1         | 1      | 0.64%   |
| INNOVATION IT               | 1         | 1      | 0.64%   |
| IBM/Hitachi                 | 1         | 1      | 0.64%   |
| China                       | 1         | 1      | 0.64%   |
| BHT                         | 1         | 1      | 0.64%   |
| A-DATA Technology           | 1         | 1      | 0.64%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 3.05%   |
| Unknown MMC Card  64GB                             | 3         | 1.83%   |
| Unknown MMC Card  32GB                             | 3         | 1.83%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 1.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 3         | 1.83%   |
| HGST HTS545050A7E680 500GB                         | 3         | 1.83%   |
| Crucial CT500MX500SSD1 500GB                       | 3         | 1.83%   |
| Unknown MMC Card  128GB                            | 2         | 1.22%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1024GB         | 2         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.22%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 2         | 1.22%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 1.22%   |
| Samsung SSD 870 EVO 500GB                          | 2         | 1.22%   |
| Samsung SSD 850 EVO 500GB                          | 2         | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 1.22%   |
| Intel SSDPEKNW512G8 512GB                          | 2         | 1.22%   |
| HGST HTS541010B7E610 1TB                           | 2         | 1.22%   |
| HGST HTS541010A9E680 1TB                           | 2         | 1.22%   |
| XrayDisk 128GB                                     | 1         | 0.61%   |
| WDC WD5000LPCX-22VHAT0 500GB                       | 1         | 0.61%   |
| WDC WD5000LPCX-21VHAT0 500GB                       | 1         | 0.61%   |
| WDC WD3200BPVT-22JJ5T0 320GB                       | 1         | 0.61%   |
| WDC WD2500BEVT-22A23T0 250GB                       | 1         | 0.61%   |
| WDC WD1600BEVS-60VAT0 160GB                        | 1         | 0.61%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 0.61%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.61%   |
| WDC WD10JPVX-60JC3T0 1TB                           | 1         | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 1         | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 1         | 0.61%   |
| WDC WD Elements 320GB                              | 1         | 0.61%   |
| WDC PC SN530 SDBPNPZ-1T00-1014 1TB                 | 1         | 0.61%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB               | 1         | 0.61%   |
| Unknown USB DISK 3.2 1TB                           | 1         | 0.61%   |
| Unknown SD512  512MB                               | 1         | 0.61%   |
| Unknown SD16G  16GB                                | 1         | 0.61%   |
| Unknown SD/MMC/MS PRO 128GB                        | 1         | 0.61%   |
| Unknown MMC Card  8GB                              | 1         | 0.61%   |
| Unknown MMC Card  2GB                              | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 20     | 40.43%  |
| WDC                 | 10        | 10     | 21.28%  |
| HGST                | 7         | 8      | 14.89%  |
| Toshiba             | 4         | 4      | 8.51%   |
| Hitachi             | 3         | 3      | 6.38%   |
| XrayDisk            | 1         | 1      | 2.13%   |
| Unknown             | 1         | 1      | 2.13%   |
| Samsung Electronics | 1         | 1      | 2.13%   |
| IBM/Hitachi         | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 23.08%  |
| SanDisk             | 5         | 5      | 12.82%  |
| Kingston            | 5         | 5      | 12.82%  |
| Crucial             | 5         | 6      | 12.82%  |
| Patriot             | 2         | 2      | 5.13%   |
| Intel               | 2         | 2      | 5.13%   |
| Apple               | 2         | 2      | 5.13%   |
| Transcend           | 1         | 1      | 2.56%   |
| SK hynix            | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| ORIGIN              | 1         | 1      | 2.56%   |
| Lenovo              | 1         | 1      | 2.56%   |
| INNOVATION IT       | 1         | 1      | 2.56%   |
| China               | 1         | 1      | 2.56%   |
| BHT                 | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 57        | 65     | 37.5%   |
| HDD     | 46        | 49     | 30.26%  |
| SSD     | 36        | 41     | 23.68%  |
| MMC     | 11        | 15     | 7.24%   |
| Unknown | 2         | 3      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 75        | 86     | 50.34%  |
| NVMe | 57        | 65     | 38.26%  |
| MMC  | 11        | 15     | 7.38%   |
| SAS  | 6         | 7      | 4.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 54     | 57.32%  |
| 0.51-1.0   | 33        | 34     | 40.24%  |
| 3.01-4.0   | 1         | 1      | 1.22%   |
| 1.01-2.0   | 1         | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 41        | 29.93%  |
| 501-1000       | 33        | 24.09%  |
| 101-250        | 29        | 21.17%  |
| 51-100         | 8         | 5.84%   |
| Unknown        | 7         | 5.11%   |
| 1-20           | 6         | 4.38%   |
| 21-50          | 5         | 3.65%   |
| 1001-2000      | 5         | 3.65%   |
| More than 3000 | 2         | 1.46%   |
| 2001-3000      | 1         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 41        | 29.93%  |
| 101-250        | 29        | 21.17%  |
| 21-50          | 25        | 18.25%  |
| 51-100         | 15        | 10.95%  |
| 251-500        | 9         | 6.57%   |
| Unknown        | 7         | 5.11%   |
| 501-1000       | 6         | 4.38%   |
| 1001-2000      | 3         | 2.19%   |
| More than 3000 | 2         | 1.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB              | 2         | 2      | 11.76%  |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 5.88%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 5.88%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 5.88%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB     | 1         | 1      | 5.88%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 5.88%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 5.88%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 5.88%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 5.88%   |
| Crucial CT256MX100SSD1 256GB          | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 35.29%  |
| Hitachi             | 3         | 3      | 17.65%  |
| HGST                | 3         | 3      | 17.65%  |
| WDC                 | 1         | 1      | 5.88%   |
| Toshiba             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| IBM/Hitachi         | 1         | 1      | 5.88%   |
| Crucial             | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 6         | 6      | 40%     |
| Hitachi     | 3         | 3      | 20%     |
| HGST        | 3         | 3      | 20%     |
| WDC         | 1         | 1      | 6.67%   |
| Toshiba     | 1         | 1      | 6.67%   |
| IBM/Hitachi | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 88.24%  |
| SSD  | 2         | 2      | 11.76%  |

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
| Works    | 78        | 93     | 54.17%  |
| Detected | 49        | 63     | 34.03%  |
| Malfunc  | 17        | 17     | 11.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 71        | 46.1%   |
| AMD                                     | 26        | 16.88%  |
| Samsung Electronics                     | 19        | 12.34%  |
| SK hynix                                | 10        | 6.49%   |
| SanDisk                                 | 10        | 6.49%   |
| Phison Electronics                      | 4         | 2.6%    |
| Micron Technology                       | 3         | 1.95%   |
| Kingston Technology Company             | 3         | 1.95%   |
| KIOXIA                                  | 2         | 1.3%    |
| Toshiba America Info Systems            | 1         | 0.65%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.65%   |
| Shenzhen Unionmemory Information System | 1         | 0.65%   |
| Micron/Crucial Technology               | 1         | 0.65%   |
| Marvell Technology Group                | 1         | 0.65%   |
| Lenovo                                  | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                           | 24        | 15.09%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                            | 11        | 6.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                  | 9         | 5.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                 | 8         | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                | 5         | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                  | 5         | 3.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                          | 4         | 2.52%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                                     | 4         | 2.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                             | 4         | 2.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                              | 4         | 2.52%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                                 | 3         | 1.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                | 3         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                   | 3         | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                            | 3         | 1.89%   |
| Intel SSD 660P Series                                                                         | 3         | 1.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                                 | 3         | 1.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                        | 3         | 1.89%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                            | 2         | 1.26%   |
| SK hynix PC611 NVMe Solid State Drive                                                         | 2         | 1.26%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                         | 2         | 1.26%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                          | 2         | 1.26%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                           | 2         | 1.26%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                                   | 2         | 1.26%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                    | 2         | 1.26%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                                | 2         | 1.26%   |
| Intel SSD 670p Series [Keystone Harbor]                                                       | 2         | 1.26%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                         | 2         | 1.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                             | 2         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                              | 2         | 1.26%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                          | 1         | 0.63%   |
| SK hynix PC601 NVMe Solid State Drive                                                         | 1         | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                                         | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                                   | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                          | 1         | 0.63%   |
| Shenzhen Unionmemory Information System RPEYJ1T24MKN2QWY PCIe 4.0 NVMe SSD 1024GB (DRAM-less) | 1         | 0.63%   |
| Sandisk WD Black SN850X NVMe SSD                                                              | 1         | 0.63%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                                         | 1         | 0.63%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                                            | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                                 | 1         | 0.63%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                                           | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 85        | 54.84%  |
| NVMe | 57        | 36.77%  |
| IDE  | 7         | 4.52%   |
| RAID | 6         | 3.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 90        | 66.67%  |
| AMD    | 43        | 31.85%  |
| ARM    | 2         | 1.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.22%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 2.22%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 2.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 1.48%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.48%   |
| Intel Core i5-4278U CPU @ 2.60GHz             | 2         | 1.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.48%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.48%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 1.48%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.48%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.48%   |
| ARM Processor                                 | 2         | 1.48%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 2         | 1.48%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 1.48%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.48%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.48%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 1.48%   |
| Intel Pentium M processor 2.13GHz             | 1         | 0.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.74%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.74%   |
| Intel Pentium CPU N3520 @ 2.16GHz             | 1         | 0.74%   |
| Intel Genuine CPU 585 @ 2.16GHz               | 1         | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.74%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.74%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 20%     |
| Intel Core i7           | 20        | 14.81%  |
| Other                   | 14        | 10.37%  |
| Intel Core i3           | 14        | 10.37%  |
| AMD Ryzen 5             | 11        | 8.15%   |
| AMD Ryzen 7             | 10        | 7.41%   |
| Intel Celeron           | 9         | 6.67%   |
| AMD Ryzen 7 PRO         | 6         | 4.44%   |
| Intel Atom              | 5         | 3.7%    |
| Intel Pentium           | 3         | 2.22%   |
| Intel Core 2 Duo        | 2         | 1.48%   |
| AMD Ryzen 3             | 2         | 1.48%   |
| AMD A8                  | 2         | 1.48%   |
| Intel Pentium M         | 1         | 0.74%   |
| Intel Genuine           | 1         | 0.74%   |
| AMD Turion 64 X2 Mobile | 1         | 0.74%   |
| AMD Ryzen 9             | 1         | 0.74%   |
| AMD Ryzen 5 PRO         | 1         | 0.74%   |
| AMD E2                  | 1         | 0.74%   |
| AMD E1                  | 1         | 0.74%   |
| AMD C-60                | 1         | 0.74%   |
| AMD A6                  | 1         | 0.74%   |
| AMD A4                  | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 37.78%  |
| 4      | 44        | 32.59%  |
| 6      | 16        | 11.85%  |
| 8      | 14        | 10.37%  |
| 1      | 6         | 4.44%   |
| 14     | 2         | 1.48%   |
| 12     | 1         | 0.74%   |
| 10     | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 134       | 99.26%  |
| 2      | 1         | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 98        | 72.59%  |
| 1      | 37        | 27.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 126       | 93.33%  |
| Unknown        | 4         | 2.96%   |
| 32-bit         | 3         | 2.22%   |
| 64-bit         | 2         | 1.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 41.3%   |
| 0x40651    | 8         | 5.8%    |
| 0x0a404102 | 5         | 3.62%   |
| 0x406e3    | 4         | 2.9%    |
| 0x306a9    | 4         | 2.9%    |
| 0x08108102 | 4         | 2.9%    |
| 0x906ea    | 3         | 2.17%   |
| 0x806ec    | 3         | 2.17%   |
| 0x806e9    | 3         | 2.17%   |
| 0x30678    | 3         | 2.17%   |
| 0x206a7    | 3         | 2.17%   |
| 0x08600104 | 3         | 2.17%   |
| 0x06006705 | 3         | 2.17%   |
| 0x906e9    | 2         | 1.45%   |
| 0x906a3    | 2         | 1.45%   |
| 0x106c2    | 2         | 1.45%   |
| 0x0a50000c | 2         | 1.45%   |
| 0x08608103 | 2         | 1.45%   |
| 0x07030105 | 2         | 1.45%   |
| 0x05000119 | 2         | 1.45%   |
| 0xa0652    | 1         | 0.72%   |
| 0x806eb    | 1         | 0.72%   |
| 0x806ea    | 1         | 0.72%   |
| 0x806c1    | 1         | 0.72%   |
| 0x706e5    | 1         | 0.72%   |
| 0x406c4    | 1         | 0.72%   |
| 0x306d4    | 1         | 0.72%   |
| 0x30673    | 1         | 0.72%   |
| 0x20652    | 1         | 0.72%   |
| 0x106ca    | 1         | 0.72%   |
| 0x10661    | 1         | 0.72%   |
| 0x0a704103 | 1         | 0.72%   |
| 0x0a404101 | 1         | 0.72%   |
| 0x08608102 | 1         | 0.72%   |
| 0x08600106 | 1         | 0.72%   |
| 0x08600103 | 1         | 0.72%   |
| 0x08600102 | 1         | 0.72%   |
| 0x08108109 | 1         | 0.72%   |
| 0x0810100b | 1         | 0.72%   |
| 0x08101007 | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 17.78%  |
| Unknown          | 16        | 11.85%  |
| Haswell          | 12        | 8.89%   |
| Zen 2            | 7         | 5.19%   |
| Silvermont       | 7         | 5.19%   |
| Skylake          | 6         | 4.44%   |
| SandyBridge      | 6         | 4.44%   |
| Zen+             | 5         | 3.7%    |
| Excavator        | 5         | 3.7%    |
| Zen 3            | 4         | 2.96%   |
| TigerLake        | 4         | 2.96%   |
| IvyBridge        | 4         | 2.96%   |
| IceLake          | 4         | 2.96%   |
| Puma             | 3         | 2.22%   |
| Goldmont plus    | 3         | 2.22%   |
| Core             | 3         | 2.22%   |
| CometLake        | 3         | 2.22%   |
| Broadwell        | 3         | 2.22%   |
| Bonnell          | 3         | 2.22%   |
| Alderlake Hybrid | 3         | 2.22%   |
| Zen              | 2         | 1.48%   |
| Bobcat           | 2         | 1.48%   |
| Westmere         | 1         | 0.74%   |
| Penryn           | 1         | 0.74%   |
| P6               | 1         | 0.74%   |
| K8 Hammer        | 1         | 0.74%   |
| Jaguar           | 1         | 0.74%   |
| Goldmont         | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 87        | 52.41%  |
| AMD                              | 46        | 27.71%  |
| Nvidia                           | 32        | 19.28%  |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                          | 11        | 6.47%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 7         | 4.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 6         | 3.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 3.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 6         | 3.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 6         | 3.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 3.53%   |
| AMD Rembrandt [Radeon 680M]                                               | 6         | 3.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 5         | 2.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                  | 5         | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 2.94%   |
| AMD Lucienne                                                              | 5         | 2.94%   |
| Intel UHD Graphics 620                                                    | 4         | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.35%   |
| Intel HD Graphics 620                                                     | 3         | 1.76%   |
| Intel HD Graphics 5500                                                    | 3         | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.76%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 3         | 1.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 1.76%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.18%   |
| Intel HD Graphics 630                                                     | 2         | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.18%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.18%   |
| AMD Phoenix1                                                              | 2         | 1.18%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                       | 2         | 1.18%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter         | 1         | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.59%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.59%   |
| Nvidia GP107GLM [Quadro P600 Mobile]                                      | 1         | 0.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.59%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.59%   |
| Nvidia GM108M [GeForce 940M]                                              | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 41.48%  |
| 1 x AMD        | 38        | 28.15%  |
| Intel + Nvidia | 27        | 20%     |
| AMD + Nvidia   | 4         | 2.96%   |
| Other          | 3         | 2.22%   |
| 2 x AMD        | 2         | 1.48%   |
| Intel + AMD    | 2         | 1.48%   |
| 2 x Intel      | 1         | 0.74%   |
| 1 x SiS        | 1         | 0.74%   |
| 1 x Nvidia     | 1         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 109       | 80.74%  |
| Proprietary | 22        | 16.3%   |
| Unknown     | 4         | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 65.47%  |
| 0.01-0.5   | 17        | 12.23%  |
| 1.01-2.0   | 11        | 7.91%   |
| 0.51-1.0   | 9         | 6.47%   |
| 3.01-4.0   | 8         | 5.76%   |
| 7.01-8.0   | 2         | 1.44%   |
| 5.01-6.0   | 1         | 0.72%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 32        | 22.38%  |
| AU Optronics         | 28        | 19.58%  |
| BOE                  | 23        | 16.08%  |
| LG Display           | 18        | 12.59%  |
| Samsung Electronics  | 6         | 4.2%    |
| PANDA                | 4         | 2.8%    |
| Philips              | 3         | 2.1%    |
| LG Philips           | 3         | 2.1%    |
| Lenovo               | 3         | 2.1%    |
| Apple                | 3         | 2.1%    |
| TMX                  | 2         | 1.4%    |
| Sharp                | 2         | 1.4%    |
| Hewlett-Packard      | 2         | 1.4%    |
| AOC                  | 2         | 1.4%    |
| STD                  | 1         | 0.7%    |
| Quanta Display       | 1         | 0.7%    |
| Panasonic            | 1         | 0.7%    |
| InnoLux Display      | 1         | 0.7%    |
| InfoVision           | 1         | 0.7%    |
| Iiyama               | 1         | 0.7%    |
| Goldstar             | 1         | 0.7%    |
| Dell                 | 1         | 0.7%    |
| CSO                  | 1         | 0.7%    |
| CHR                  | 1         | 0.7%    |
| BOE Technology Group | 1         | 0.7%    |
| Unknown              | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.1%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.1%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.1%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.4%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.4%    |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 2         | 1.4%    |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                 | 2         | 1.4%    |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.7%    |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.7%    |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.7%    |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.7%    |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM029D 1280x720                      | 1         | 0.7%    |
| Quanta Display LCD Monitor QDS0015 1024x768 285x214mm 14.0-inch       | 1         | 0.7%    |
| Philips PHL 328P6A PHL0913 2560x1440 700x390mm 31.5-inch              | 1         | 0.7%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.7%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP003D 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 1         | 0.7%    |
| LG Philips LCD Monitor LPLE800 1280x800 304x190mm 14.1-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPLDC00 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD4601 1280x800 286x179mm 13.3-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0662 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 58        | 41.43%  |
| 1366x768 (WXGA)   | 38        | 27.14%  |
| 1920x1200 (WUXGA) | 8         | 5.71%   |
| 1600x900 (HD+)    | 6         | 4.29%   |
| 2560x1600         | 4         | 2.86%   |
| 2560x1440 (QHD)   | 4         | 2.86%   |
| 1280x800 (WXGA)   | 4         | 2.86%   |
| 2880x1800         | 3         | 2.14%   |
| 2160x1440         | 3         | 2.14%   |
| 3840x2160 (4K)    | 2         | 1.43%   |
| 2256x1504         | 2         | 1.43%   |
| 1024x600          | 2         | 1.43%   |
| 3440x1440         | 1         | 0.71%   |
| 3200x2000         | 1         | 0.71%   |
| 2288x1287         | 1         | 0.71%   |
| 1360x768          | 1         | 0.71%   |
| 1280x720 (HD)     | 1         | 0.71%   |
| 1024x768 (XGA)    | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 56        | 39.16%  |
| 14      | 27        | 18.88%  |
| 13      | 21        | 14.69%  |
| 11      | 6         | 4.2%    |
| 17      | 5         | 3.5%    |
| 24      | 4         | 2.8%    |
| 16      | 4         | 2.8%    |
| 12      | 4         | 2.8%    |
| 23      | 3         | 2.1%    |
| 10      | 2         | 1.4%    |
| Unknown | 2         | 1.4%    |
| 84      | 1         | 0.7%    |
| 39      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 33      | 1         | 0.7%    |
| 32      | 1         | 0.7%    |
| 31      | 1         | 0.7%    |
| 21      | 1         | 0.7%    |
| 18      | 1         | 0.7%    |
| 8       | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 67.13%  |
| 201-300     | 24        | 16.78%  |
| 501-600     | 7         | 4.9%    |
| 351-400     | 5         | 3.5%    |
| 701-800     | 3         | 2.1%    |
| 401-500     | 2         | 1.4%    |
| Unknown     | 2         | 1.4%    |
| 801-900     | 1         | 0.7%    |
| 601-700     | 1         | 0.7%    |
| 1501-2000   | 1         | 0.7%    |
| 101-200     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 104       | 77.61%  |
| 16/10   | 21        | 15.67%  |
| 3/2     | 6         | 4.48%   |
| 4/3     | 1         | 0.75%   |
| 21/9    | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 38.46%  |
| 81-90          | 39        | 27.27%  |
| 71-80          | 7         | 4.9%    |
| 51-60          | 6         | 4.2%    |
| 201-250        | 5         | 3.5%    |
| 111-120        | 5         | 3.5%    |
| 61-70          | 4         | 2.8%    |
| 351-500        | 4         | 2.8%    |
| 251-300        | 3         | 2.1%    |
| 121-130        | 3         | 2.1%    |
| 41-50          | 2         | 1.4%    |
| 131-140        | 2         | 1.4%    |
| 91-100         | 2         | 1.4%    |
| Unknown        | 2         | 1.4%    |
| More than 1000 | 1         | 0.7%    |
| 1-40           | 1         | 0.7%    |
| 141-150        | 1         | 0.7%    |
| 501-1000       | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 66        | 46.48%  |
| 101-120       | 33        | 23.24%  |
| 51-100        | 20        | 14.08%  |
| 161-240       | 17        | 11.97%  |
| More than 240 | 4         | 2.82%   |
| Unknown       | 2         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 116       | 85.93%  |
| 2     | 17        | 12.59%  |
| 0     | 2         | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 75        | 38.66%  |
| Intel                            | 56        | 28.87%  |
| Qualcomm Atheros                 | 22        | 11.34%  |
| Broadcom                         | 11        | 5.67%   |
| MediaTek                         | 6         | 3.09%   |
| Broadcom Limited                 | 5         | 2.58%   |
| Qualcomm                         | 4         | 2.06%   |
| Sierra Wireless                  | 3         | 1.55%   |
| Ralink Technology                | 3         | 1.55%   |
| Ralink                           | 2         | 1.03%   |
| Cypress Semiconductor            | 2         | 1.03%   |
| Xiaomi                           | 1         | 0.52%   |
| TP-Link                          | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |
| Marvell Technology Group         | 1         | 0.52%   |
| Huawei Technologies              | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 43        | 18.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 7.26%   |
| Intel Wi-Fi 6 AX200                                                    | 9         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 2.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 2.99%   |
| Intel Wireless 8265 / 8275                                             | 7         | 2.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 2.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 2.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.14%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 2.14%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.71%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 3         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.28%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3         | 1.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                        | 2         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.85%   |
| Intel Wireless 8260                                                    | 2         | 0.85%   |
| Intel Wireless 7260                                                    | 2         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                         | 2         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 0.85%   |
| Cypress K38231_03                                                      | 2         | 0.85%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                        | 2         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 55        | 40.44%  |
| Realtek Semiconductor | 31        | 22.79%  |
| Qualcomm Atheros      | 19        | 13.97%  |
| Broadcom              | 9         | 6.62%   |
| MediaTek              | 6         | 4.41%   |
| Qualcomm              | 4         | 2.94%   |
| Broadcom Limited      | 4         | 2.94%   |
| Sierra Wireless       | 3         | 2.21%   |
| Ralink Technology     | 3         | 2.21%   |
| Ralink                | 2         | 1.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 9         | 6.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 5.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 7         | 5.11%   |
| Intel Wireless 8265 / 8275                                           | 7         | 5.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 6         | 4.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 3.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 3.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 3.65%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 3.65%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 4         | 2.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 2.92%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 3         | 2.19%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 2.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 2.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 2.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 2         | 1.46%   |
| Ralink MT7601U Wireless Adapter                                      | 2         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.46%   |
| Intel Wireless 8260                                                  | 2         | 1.46%   |
| Intel Wireless 7260                                                  | 2         | 1.46%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 2         | 1.46%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.46%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.46%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.46%   |
| Broadcom BCM4311 802.11b/g WLAN                                      | 2         | 1.46%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                        | 1         | 0.73%   |
| Sierra Wireless EM7455                                               | 1         | 0.73%   |
| Sierra Wireless EM7305 Modem                                         | 1         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.73%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.73%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 62        | 64.58%  |
| Intel                            | 19        | 19.79%  |
| Qualcomm Atheros                 | 4         | 4.17%   |
| Broadcom                         | 3         | 3.13%   |
| Cypress Semiconductor            | 2         | 2.08%   |
| Xiaomi                           | 1         | 1.04%   |
| TP-Link                          | 1         | 1.04%   |
| Silicon Integrated Systems [SiS] | 1         | 1.04%   |
| Marvell Technology Group         | 1         | 1.04%   |
| Huawei Technologies              | 1         | 1.04%   |
| Broadcom Limited                 | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 43        | 44.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 17.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 5.21%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.13%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 2.08%   |
| Cypress K38231_03                                                      | 2         | 2.08%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 1.04%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 1.04%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 1         | 1.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 1.04%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 1.04%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 1.04%   |
| Intel Ethernet Connection I219-V                                       | 1         | 1.04%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 1.04%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1.04%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.04%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 1.04%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1.04%   |
| Huawei VTR-L09                                                         | 1         | 1.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 1         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.04%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 1         | 1.04%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 1.04%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 57.52%  |
| Ethernet | 95        | 42.04%  |
| Modem    | 1         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 84.78%  |
| Ethernet | 21        | 15.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 84        | 62.22%  |
| 1     | 44        | 32.59%  |
| 0     | 5         | 3.7%    |
| 3     | 2         | 1.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 79.71%  |
| Yes  | 28        | 20.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 37.93%  |
| Realtek Semiconductor           | 19        | 16.38%  |
| Lite-On Technology              | 9         | 7.76%   |
| Broadcom                        | 9         | 7.76%   |
| IMC Networks                    | 7         | 6.03%   |
| Foxconn / Hon Hai               | 6         | 5.17%   |
| USI                             | 4         | 3.45%   |
| Qualcomm Atheros Communications | 4         | 3.45%   |
| Realtek                         | 3         | 2.59%   |
| Cambridge Silicon Radio         | 2         | 1.72%   |
| Apple                           | 2         | 1.72%   |
| Toshiba                         | 1         | 0.86%   |
| SINO WEALTH                     | 1         | 0.86%   |
| Ralink                          | 1         | 0.86%   |
| Opticis                         | 1         | 0.86%   |
| MediaTek                        | 1         | 0.86%   |
| Foxconn International           | 1         | 0.86%   |
| Dell                            | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 10        | 8.62%   |
| Intel AX200 Bluetooth                               | 9         | 7.76%   |
| Intel Bluetooth Device                              | 8         | 6.9%    |
| Intel AX201 Bluetooth                               | 8         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 6.03%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 4.31%   |
| USI Bluetooth Device                                | 4         | 3.45%   |
| Intel Bluetooth wireless interface                  | 4         | 3.45%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 3.45%   |
| Realtek Bluetooth Radio                             | 3         | 2.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 2.59%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.59%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 2.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 2.59%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.72%   |
| Lite-On Bluetooth Device                            | 2         | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.72%   |
| Intel AX211 Bluetooth                               | 2         | 1.72%   |
| Intel AX210 Bluetooth                               | 2         | 1.72%   |
| IMC Networks Bluetooth Device                       | 2         | 1.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.72%   |
| Apple Bluetooth Host Controller                     | 2         | 1.72%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.86%   |
| SINO WEALTH Bluetooth Keyboard                      | 1         | 0.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.86%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.86%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.86%   |
| Opticis Bluetooth Radio                             | 1         | 0.86%   |
| MediaTek Wireless_Device                            | 1         | 0.86%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.86%   |
| IMC Networks Wireless_Device                        | 1         | 0.86%   |
| IMC Networks Bluetooth                              | 1         | 0.86%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.86%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 88        | 58.28%  |
| AMD                              | 44        | 29.14%  |
| Nvidia                           | 11        | 7.28%   |
| Texas Instruments                | 2         | 1.32%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Samson Technologies              | 1         | 0.66%   |
| Logitech                         | 1         | 0.66%   |
| JMTek                            | 1         | 0.66%   |
| Creative Technology              | 1         | 0.66%   |
| Corsair                          | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 29        | 14.15%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 7.32%   |
| Intel Sunrise Point-LP HD Audio                                            | 13        | 6.34%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 5.37%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 5.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 3.9%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.44%   |
| AMD High Definition Audio Controller                                       | 5         | 2.44%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 2.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.46%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.46%   |
| Texas Instruments PCM2912A Audio Codec                                     | 2         | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.98%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.98%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.98%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.98%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.49%   |
| Samson Technologies Meteor condenser microphone                            | 1         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.49%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 34        | 28.1%   |
| Samsung Electronics | 34        | 28.1%   |
| Micron Technology   | 21        | 17.36%  |
| Kingston            | 8         | 6.61%   |
| Unknown             | 5         | 4.13%   |
| A-DATA Technology   | 5         | 4.13%   |
| Ramaxel Technology  | 2         | 1.65%   |
| Nanya Technology    | 2         | 1.65%   |
| Crucial             | 2         | 1.65%   |
| Corsair             | 2         | 1.65%   |
| Unknown (ABCD)      | 1         | 0.83%   |
| Transcend           | 1         | 0.83%   |
| Team                | 1         | 0.83%   |
| Elpida              | 1         | 0.83%   |
| 4ea5                | 1         | 0.83%   |
| 48spaces            | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.55%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.55%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 2         | 1.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.55%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.55%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.78%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.78%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.78%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.78%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.78%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.78%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.78%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                       | 1         | 0.78%   |
| SK hynix RAM HMT451U6MFR8C-C9 8GB SODIMM DDR4 2133MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.78%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 45.54%  |
| DDR3   | 36        | 35.64%  |
| LPDDR5 | 6         | 5.94%   |
| LPDDR4 | 6         | 5.94%   |
| DDR2   | 3         | 2.97%   |
| DDR5   | 2         | 1.98%   |
| LPDDR3 | 1         | 0.99%   |
| DDR    | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 86.27%  |
| Row Of Chips | 12        | 11.76%  |
| DIMM         | 1         | 0.98%   |
| Unknown      | 1         | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 51        | 43.97%  |
| 4096  | 38        | 32.76%  |
| 16384 | 12        | 10.34%  |
| 2048  | 8         | 6.9%    |
| 1024  | 3         | 2.59%   |
| 512   | 3         | 2.59%   |
| 32768 | 1         | 0.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 23.85%  |
| 2667    | 24        | 22.02%  |
| 3200    | 19        | 17.43%  |
| 6400    | 6         | 5.5%    |
| 2400    | 6         | 5.5%    |
| 1334    | 6         | 5.5%    |
| 1333    | 5         | 4.59%   |
| 2133    | 3         | 2.75%   |
| 533     | 3         | 2.75%   |
| 3733    | 2         | 1.83%   |
| 667     | 2         | 1.83%   |
| 8400    | 1         | 0.92%   |
| 5600    | 1         | 0.92%   |
| 4800    | 1         | 0.92%   |
| 4267    | 1         | 0.92%   |
| 4266    | 1         | 0.92%   |
| 1867    | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 31.93%  |
| IMC Networks                           | 17        | 14.29%  |
| Quanta                                 | 10        | 8.4%    |
| Microdia                               | 9         | 7.56%   |
| Acer                                   | 8         | 6.72%   |
| Realtek Semiconductor                  | 7         | 5.88%   |
| Sunplus Innovation Technology          | 5         | 4.2%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.2%    |
| Bison Electronics                      | 5         | 4.2%    |
| Syntek                                 | 4         | 3.36%   |
| Suyin                                  | 3         | 2.52%   |
| Luxvisions Innotech Limited            | 3         | 2.52%   |
| SunplusIT                              | 1         | 0.84%   |
| Silicon Motion                         | 1         | 0.84%   |
| Logitech                               | 1         | 0.84%   |
| Intel                                  | 1         | 0.84%   |
| Alcor Micro                            | 1         | 0.84%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 11        | 9.17%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 5.83%   |
| Chicony HP Truevision HD camera               | 4         | 3.33%   |
| Syntek Integrated Camera                      | 3         | 2.5%    |
| Suyin HP Truevision HD                        | 3         | 2.5%    |
| Realtek USB Camera                            | 3         | 2.5%    |
| Quanta HD User Facing                         | 3         | 2.5%    |
| Microdia Integrated_Webcam_HD                 | 3         | 2.5%    |
| Chicony USB 2.0 Camera                        | 3         | 2.5%    |
| Chicony HD Webcam                             | 3         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.5%    |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.67%   |
| Quanta HP Webcam                              | 2         | 1.67%   |
| Microdia HP Integrated Webcam                 | 2         | 1.67%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 2         | 1.67%   |
| IMC Networks Integrated Camera                | 2         | 1.67%   |
| IMC Networks HD Camera                        | 2         | 1.67%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 1.67%   |
| Chicony USB2.0 Camera                         | 2         | 1.67%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.67%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.67%   |
| Chicony HD User Facing                        | 2         | 1.67%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.67%   |
| Acer Integrated RGB Camera                    | 2         | 1.67%   |
| Acer Integrated Camera                        | 2         | 1.67%   |
| Syntek EasyCamera                             | 1         | 0.83%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.83%   |
| Sunplus PC Camera                             | 1         | 0.83%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.83%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.83%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.83%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.83%   |
| Realtek Laptop Camera                         | 1         | 0.83%   |
| Realtek Integrated Webcam HD                  | 1         | 0.83%   |
| Realtek HD WebCam                             | 1         | 0.83%   |
| Quanta VGA WebCam                             | 1         | 0.83%   |
| Quanta USB2.0 HD UVC WebCam                   | 1         | 0.83%   |
| Quanta ov9734_techfront_camera                | 1         | 0.83%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.83%   |
| Quanta ACER HD User Facing                    | 1         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 45.45%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Validity Sensors           | 3         | 13.64%  |
| Upek                       | 3         | 13.64%  |
| Elan Microelectronics      | 2         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 22.73%  |
| Shenzhen Goodix  Fingerprint Device                    | 4         | 18.18%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 13.64%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 13.64%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 9.09%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 4.55%   |
| Synaptics UWP WBDI Device                              | 1         | 4.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |
| Elan ELAN:ARM-M4                                       | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 50%     |
| Lenovo      | 2         | 25%     |
| Broadcom    | 2         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 4         | 50%     |
| Lenovo Integrated Smart Card Reader            | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 12.5%   |
| Broadcom 58200                                 | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 92        | 67.65%  |
| 1     | 35        | 25.74%  |
| 2     | 8         | 5.88%   |
| 3     | 1         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 41.51%  |
| Graphics card            | 8         | 15.09%  |
| Chipcard                 | 8         | 15.09%  |
| Net/wireless             | 5         | 9.43%   |
| Multimedia controller    | 2         | 3.77%   |
| Communication controller | 2         | 3.77%   |
| Camera                   | 2         | 3.77%   |
| Sound                    | 1         | 1.89%   |
| Net/ethernet             | 1         | 1.89%   |
| Card reader              | 1         | 1.89%   |
| Bluetooth                | 1         | 1.89%   |

