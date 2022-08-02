Xubuntu 20.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 20.04.

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

Total: 1399

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| Apple         | MacBookPro12,1              | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Samsung       | R59P/R60P/R61P              | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| HP            | Laptop 14-bw0xx             | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| HP            | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Acer          | Aspire 7720                 | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Acer          | Aspire 7720                 | [d60aee8a9c](https://linux-hardware.org/?probe=d60aee8a9c) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| GPU Compan... | GWTN116-3                   | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Acer          | Aspire 7720                 | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Dell          | Inspiron N4010              | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Medion        | E15407                      | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| ASUSTek       | X510UA                      | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| HP            | Compaq 6820s                | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| Toshiba       | Satellite C70D-B            | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| ASUSTek       | K53SC                       | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| ASUSTek       | K53SC                       | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Dell          | Inspiron 3135               | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Dell          | Latitude 7480               | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | Compaq 6730s                | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Dell          | Latitude E6540              | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | Compaq 6730s                | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| ASUSTek       | K53SC                       | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| HP            | Pavilion dv6500             | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| MSI           | GX70 3CC                    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| GPU Compan... | GWTC116-2                   | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| ASUSTek       | X501A                       | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| Samsung       | R530/R730/R540              | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| Dell          | Inspiron 7437               | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion dv7                | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| HP            | Pavilion dv7                | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| Dell          | Vostro V130                 | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Gateway       | M-6307                      | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| Dell          | Inspiron 1764               | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| Sony          | VPCEB3E1E                   | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | ProBook 650 G3              | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| HP            | Pavilion 17                 | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| HP            | EliteBook 745 G3            | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Dell          | Studio 1450                 | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Dell          | Latitude D630               | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| HP            | G42                         | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| HP            | ProBook 440 G6              | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| HP            | Laptop 17-ca1xxx            | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| ASUSTek       | K50IJ                       | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [d735255913](https://linux-hardware.org/?probe=d735255913) | Jan 15, 2022 |
| Insyde        | Braswell                    | [a5bca1e5e8](https://linux-hardware.org/?probe=a5bca1e5e8) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Lenovo        | IdeaPad S415 Touch 20319    | [d59706fc52](https://linux-hardware.org/?probe=d59706fc52) | Jan 11, 2022 |
| ASUSTek       | K53SC                       | [b01004055c](https://linux-hardware.org/?probe=b01004055c) | Jan 11, 2022 |
| MOTION        | KEX00                       | [8e36590e72](https://linux-hardware.org/?probe=8e36590e72) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Alienware     | m15 R3                      | [8cff8c6d3f](https://linux-hardware.org/?probe=8cff8c6d3f) | Jan 09, 2022 |
| Acer          | Extensa 5620                | [41a1c7001c](https://linux-hardware.org/?probe=41a1c7001c) | Jan 08, 2022 |
| Sony          | SVF15A190X                  | [6d729a76af](https://linux-hardware.org/?probe=6d729a76af) | Jan 08, 2022 |
| Dell          | Latitude E6500              | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| Gateway       | NV53A                       | [2e67e3a86e](https://linux-hardware.org/?probe=2e67e3a86e) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| ASUSTek       | N550JV                      | [aefb321446](https://linux-hardware.org/?probe=aefb321446) | Jan 04, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| HP            | G60                         | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Dell          | Inspiron 5765               | [c3a91857b3](https://linux-hardware.org/?probe=c3a91857b3) | Jan 01, 2022 |
| Intel         | Crestline & ICH8M Chipse... | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| HP            | Laptop 17-cp0xxx            | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| HP            | EliteBook 8440p (VD484AV... | [ba4cf422e7](https://linux-hardware.org/?probe=ba4cf422e7) | Dec 27, 2021 |
| Toshiba       | Satellite C50-A-19U         | [6a61931dde](https://linux-hardware.org/?probe=6a61931dde) | Dec 26, 2021 |
| Acer          | Aspire A515-54G             | [00c1f1b6df](https://linux-hardware.org/?probe=00c1f1b6df) | Dec 26, 2021 |
| MSI           | GP76 Leopard 11UG           | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | [2ef30c62b5](https://linux-hardware.org/?probe=2ef30c62b5) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| HP            | Pavilion dv7                | [3b47550de1](https://linux-hardware.org/?probe=3b47550de1) | Dec 23, 2021 |
| HP            | Laptop 17-cn1xxx            | [c26a2c5c03](https://linux-hardware.org/?probe=c26a2c5c03) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| Google        | Nami                        | [045f17f15d](https://linux-hardware.org/?probe=045f17f15d) | Dec 22, 2021 |
| HP            | Laptop 17-cn1xxx            | [e3c5530718](https://linux-hardware.org/?probe=e3c5530718) | Dec 19, 2021 |
| ASUSTek       | E200HA                      | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Lenovo        | B50-30 20382                | [7c3c9b5cdd](https://linux-hardware.org/?probe=7c3c9b5cdd) | Dec 17, 2021 |
| Dell          | System XPS L502X            | [4588c107ed](https://linux-hardware.org/?probe=4588c107ed) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| Toshiba       | Satellite A105              | [4bddc587d8](https://linux-hardware.org/?probe=4bddc587d8) | Dec 15, 2021 |
| Gateway       | NV53A                       | [1912b6b8c5](https://linux-hardware.org/?probe=1912b6b8c5) | Dec 14, 2021 |
| ASUSTek       | X55U                        | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| HP            | Pavilion TS 11              | [1617abd2f4](https://linux-hardware.org/?probe=1617abd2f4) | Dec 12, 2021 |
| Dell          | Inspiron 13-5378            | [22b04adc28](https://linux-hardware.org/?probe=22b04adc28) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | [f0c57ccd03](https://linux-hardware.org/?probe=f0c57ccd03) | Dec 10, 2021 |
| HP            | EliteBook Folio 9470m       | [c505dc1521](https://linux-hardware.org/?probe=c505dc1521) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| Acer          | Aspire 5336                 | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| Acer          | Aspire A315-34              | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Dixonsxp      | Unknown                     | [9f1502866b](https://linux-hardware.org/?probe=9f1502866b) | Dec 03, 2021 |
| Dixonsxp      | Unknown                     | [093fef7eaa](https://linux-hardware.org/?probe=093fef7eaa) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [674712f2a1](https://linux-hardware.org/?probe=674712f2a1) | Dec 03, 2021 |
| Toshiba       | Satellite L870-196          | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| HP            | 2000                        | [f16b490828](https://linux-hardware.org/?probe=f16b490828) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| ASUSTek       | E203NAS                     | [c400f4df81](https://linux-hardware.org/?probe=c400f4df81) | Nov 30, 2021 |
| Samsung       | R530/R730/P590              | [0bbf67316b](https://linux-hardware.org/?probe=0bbf67316b) | Nov 28, 2021 |
| Acer          | Swift SF114-34              | [d0170808b3](https://linux-hardware.org/?probe=d0170808b3) | Nov 27, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [71d58a102c](https://linux-hardware.org/?probe=71d58a102c) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [d9b3bd7851](https://linux-hardware.org/?probe=d9b3bd7851) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| HP            | ProBook 640 G1              | [311cb04cc5](https://linux-hardware.org/?probe=311cb04cc5) | Nov 25, 2021 |
| HP            | Pavilion 17                 | [43944b4f78](https://linux-hardware.org/?probe=43944b4f78) | Nov 24, 2021 |
| HP            | Pavilion dv9700             | [5a583ec569](https://linux-hardware.org/?probe=5a583ec569) | Nov 24, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Alienware     | M17x                        | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | [65a59cf71c](https://linux-hardware.org/?probe=65a59cf71c) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | [55d87b9d59](https://linux-hardware.org/?probe=55d87b9d59) | Nov 22, 2021 |
| HP            | ProBook 640 G1              | [b75a64f96a](https://linux-hardware.org/?probe=b75a64f96a) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | ProBook 650 G3              | [def83e3614](https://linux-hardware.org/?probe=def83e3614) | Nov 19, 2021 |
| MSI           | GT75VR 7RE                  | [02a0e2b5c8](https://linux-hardware.org/?probe=02a0e2b5c8) | Nov 19, 2021 |
| ONE-NETBOO... | A1                          | [aff2f60770](https://linux-hardware.org/?probe=aff2f60770) | Nov 19, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [dfba89a8f0](https://linux-hardware.org/?probe=dfba89a8f0) | Nov 17, 2021 |
| Dell          | Latitude 7370               | [b43fadb11c](https://linux-hardware.org/?probe=b43fadb11c) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Apple         | MacBookPro8,1               | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| HP            | Pavilion TS 11              | [746f0808f4](https://linux-hardware.org/?probe=746f0808f4) | Nov 12, 2021 |
| Dell          | G15 5510                    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| ASUSTek       | X501A                       | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| HP            | ZBook 15 G3                 | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Lenovo        | ThinkPad T410 2537MT3       | [76965c829b](https://linux-hardware.org/?probe=76965c829b) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| System76      | Oryx Pro                    | [39d1d14e62](https://linux-hardware.org/?probe=39d1d14e62) | Nov 07, 2021 |
| HP            | Pavilion g6                 | [ed14748445](https://linux-hardware.org/?probe=ed14748445) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| Dell          | G3 3500                     | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Dell          | Precision M4600             | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [305cca4bc8](https://linux-hardware.org/?probe=305cca4bc8) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Nitro AN715-52              | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Toshiba       | Satellite P745              | [59b3468fb9](https://linux-hardware.org/?probe=59b3468fb9) | Nov 04, 2021 |
| HP            | ProBook 6450b               | [603fac0b2e](https://linux-hardware.org/?probe=603fac0b2e) | Nov 04, 2021 |
| Dell          | Latitude D630               | [f212896c99](https://linux-hardware.org/?probe=f212896c99) | Nov 04, 2021 |
| Dell          | Precision M4600             | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| Toshiba       | Satellite C70D-B            | [9fd353eaff](https://linux-hardware.org/?probe=9fd353eaff) | Nov 04, 2021 |
| ASUSTek       | T100TA                      | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| HP            | Compaq Presario CQ61        | [86dd6331fc](https://linux-hardware.org/?probe=86dd6331fc) | Nov 02, 2021 |
| HP            | Pavilion TS 11              | [29af280c0e](https://linux-hardware.org/?probe=29af280c0e) | Nov 01, 2021 |
| ASUSTek       | P2540UA                     | [f10ce209c4](https://linux-hardware.org/?probe=f10ce209c4) | Nov 01, 2021 |
| ASUSTek       | GL553VE                     | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| VIT           | P3400                       | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| Lenovo        | ThinkPad W510 431963G       | [5ce9661292](https://linux-hardware.org/?probe=5ce9661292) | Oct 28, 2021 |
| HP            | Compaq 6730s                | [8bc4483616](https://linux-hardware.org/?probe=8bc4483616) | Oct 27, 2021 |
| HP            | Pavilion g4                 | [90f6743fbd](https://linux-hardware.org/?probe=90f6743fbd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Alienware     | m17 R4                      | [5c569c3982](https://linux-hardware.org/?probe=5c569c3982) | Oct 24, 2021 |
| HP            | Compaq 6730s                | [587b440ce4](https://linux-hardware.org/?probe=587b440ce4) | Oct 24, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [68f1525bef](https://linux-hardware.org/?probe=68f1525bef) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [1146299277](https://linux-hardware.org/?probe=1146299277) | Oct 23, 2021 |
| HP            | Compaq Presario CQ61        | [cb8b850048](https://linux-hardware.org/?probe=cb8b850048) | Oct 23, 2021 |
| Sony          | VGN-NR11Z_T                 | [f76ae4b159](https://linux-hardware.org/?probe=f76ae4b159) | Oct 22, 2021 |
| HP            | kip                         | [18f48f3a5b](https://linux-hardware.org/?probe=18f48f3a5b) | Oct 22, 2021 |
| Lenovo        | ThinkPad W510 431963G       | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| HP            | Notebook                    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| Lenovo        | ThinkPad T420 4180AP3       | [6be3808b94](https://linux-hardware.org/?probe=6be3808b94) | Oct 21, 2021 |
| Lenovo        | IdeaPad U550 20034,3749     | [3bbec8b8fd](https://linux-hardware.org/?probe=3bbec8b8fd) | Oct 21, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | [8ad9f2f898](https://linux-hardware.org/?probe=8ad9f2f898) | Oct 20, 2021 |
| Apple         | MacBookPro11,1              | [7fb2681427](https://linux-hardware.org/?probe=7fb2681427) | Oct 20, 2021 |
| Lenovo        | B5400 s20278Q               | [c71ca98310](https://linux-hardware.org/?probe=c71ca98310) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| Samsung       | R530/R730/P590              | [e76e147759](https://linux-hardware.org/?probe=e76e147759) | Oct 19, 2021 |
| Lenovo        | B50-30 20382                | [235b6e8d1a](https://linux-hardware.org/?probe=235b6e8d1a) | Oct 18, 2021 |
| Acer          | Extensa 5630                | [4823b348aa](https://linux-hardware.org/?probe=4823b348aa) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Latitude E6440              | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 255 G7 Notebook PC          | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b9218a0347](https://linux-hardware.org/?probe=b9218a0347) | Oct 15, 2021 |
| Toshiba       | Satellite A100              | [ef126ad790](https://linux-hardware.org/?probe=ef126ad790) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| HP            | OMEN by Laptop              | [6163de66f1](https://linux-hardware.org/?probe=6163de66f1) | Oct 12, 2021 |
| eMachines     | G730                        | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| Dell          | Latitude 7370               | [348b718b2b](https://linux-hardware.org/?probe=348b718b2b) | Oct 11, 2021 |
| HP            | Notebook                    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| Dell          | Precision 5540              | [b59369e8e7](https://linux-hardware.org/?probe=b59369e8e7) | Oct 08, 2021 |
| Multilaser    | UB32X                       | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [399430cdbe](https://linux-hardware.org/?probe=399430cdbe) | Oct 06, 2021 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [d09fddd2b5](https://linux-hardware.org/?probe=d09fddd2b5) | Oct 06, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [697843fefc](https://linux-hardware.org/?probe=697843fefc) | Oct 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [9ba5143844](https://linux-hardware.org/?probe=9ba5143844) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| Sony          | VGN-NR38E_S                 | [8cb5fc39c1](https://linux-hardware.org/?probe=8cb5fc39c1) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK E752               | [5cccf30dd4](https://linux-hardware.org/?probe=5cccf30dd4) | Oct 01, 2021 |
| ASUSTek       | K53E                        | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [73a0747f86](https://linux-hardware.org/?probe=73a0747f86) | Sep 29, 2021 |
| Toshiba       | Satellite C55-A             | [97872be09f](https://linux-hardware.org/?probe=97872be09f) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | [c79d4daf0a](https://linux-hardware.org/?probe=c79d4daf0a) | Sep 28, 2021 |
| Dell          | Latitude E5530 non-vPro     | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| Dell          | Studio 1558                 | [05f781c843](https://linux-hardware.org/?probe=05f781c843) | Sep 25, 2021 |
| HP            | Compaq 6710b (GB889ET#AB... | [2fcbe348d6](https://linux-hardware.org/?probe=2fcbe348d6) | Sep 24, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Notebook                    | [0253eca654](https://linux-hardware.org/?probe=0253eca654) | Sep 22, 2021 |
| HP            | Notebook                    | [9afc140a7e](https://linux-hardware.org/?probe=9afc140a7e) | Sep 22, 2021 |
| ASUSTek       | T100HAN                     | [aabfa3e289](https://linux-hardware.org/?probe=aabfa3e289) | Sep 22, 2021 |
| HP            | Compaq CQ45                 | [87a47d3bc8](https://linux-hardware.org/?probe=87a47d3bc8) | Sep 20, 2021 |
| Clevo         | W760SUB                     | [8ae1ea1d6b](https://linux-hardware.org/?probe=8ae1ea1d6b) | Sep 20, 2021 |
| HP            | ProBook 4510s               | [721b35cbcb](https://linux-hardware.org/?probe=721b35cbcb) | Sep 19, 2021 |
| Lenovo        | G460 0677                   | [6f23b54ef5](https://linux-hardware.org/?probe=6f23b54ef5) | Sep 17, 2021 |
| Dell          | Latitude D630               | [260bb1528f](https://linux-hardware.org/?probe=260bb1528f) | Sep 15, 2021 |
| Dell          | Inspiron 3437               | [67069e48f0](https://linux-hardware.org/?probe=67069e48f0) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| HP            | 15                          | [d88dbb5aa3](https://linux-hardware.org/?probe=d88dbb5aa3) | Sep 12, 2021 |
| HP            | Pavilion dm4                | [a10c76835b](https://linux-hardware.org/?probe=a10c76835b) | Sep 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [bced59049e](https://linux-hardware.org/?probe=bced59049e) | Sep 11, 2021 |
| HP            | Pavilion dv6                | [e2ad40d8c1](https://linux-hardware.org/?probe=e2ad40d8c1) | Sep 10, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | [3abbaccc90](https://linux-hardware.org/?probe=3abbaccc90) | Sep 09, 2021 |
| MSI           | GF75 Thin 9SD               | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | ProBook 4510s               | [b2e4641005](https://linux-hardware.org/?probe=b2e4641005) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | [3ca698d670](https://linux-hardware.org/?probe=3ca698d670) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | [37bd4db385](https://linux-hardware.org/?probe=37bd4db385) | Sep 09, 2021 |
| Itautec       | Infoway a7420               | [282046f0c0](https://linux-hardware.org/?probe=282046f0c0) | Sep 09, 2021 |
| HP            | G60                         | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [7ff32b60eb](https://linux-hardware.org/?probe=7ff32b60eb) | Sep 05, 2021 |
| Dell          | Latitude E4310              | [5e7233f129](https://linux-hardware.org/?probe=5e7233f129) | Sep 05, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [631ee4fd97](https://linux-hardware.org/?probe=631ee4fd97) | Sep 05, 2021 |
| Apple         | MacBook9,1                  | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [441840f603](https://linux-hardware.org/?probe=441840f603) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Gateway       | NV57H                       | [5ccb66dc7c](https://linux-hardware.org/?probe=5ccb66dc7c) | Sep 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e47d2dc721](https://linux-hardware.org/?probe=e47d2dc721) | Sep 02, 2021 |
| Acer          | Aspire E1-772               | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ee916ec895](https://linux-hardware.org/?probe=ee916ec895) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| HP            | Notebook                    | [6afc243dea](https://linux-hardware.org/?probe=6afc243dea) | Sep 01, 2021 |
| Lenovo        | ThinkPad X395 20NLS0J400    | [cd2fa55d01](https://linux-hardware.org/?probe=cd2fa55d01) | Sep 01, 2021 |
| HP            | OMEN by Laptop              | [0631958800](https://linux-hardware.org/?probe=0631958800) | Aug 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | 15                          | [8e64e4a38f](https://linux-hardware.org/?probe=8e64e4a38f) | Aug 26, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | [932fb79537](https://linux-hardware.org/?probe=932fb79537) | Aug 26, 2021 |
| MSI           | PR601/VR603                 | [836a501df0](https://linux-hardware.org/?probe=836a501df0) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | [551749a1af](https://linux-hardware.org/?probe=551749a1af) | Aug 25, 2021 |
| Notebook      | W970SUW                     | [231346d40a](https://linux-hardware.org/?probe=231346d40a) | Aug 24, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | [74c2a834e7](https://linux-hardware.org/?probe=74c2a834e7) | Aug 23, 2021 |
| Dell          | Studio 1569                 | [600cbb330c](https://linux-hardware.org/?probe=600cbb330c) | Aug 23, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [08e78aa61d](https://linux-hardware.org/?probe=08e78aa61d) | Aug 23, 2021 |
| ASUSTek       | X501A                       | [e9784e8db3](https://linux-hardware.org/?probe=e9784e8db3) | Aug 21, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | [fb7ab1b2d1](https://linux-hardware.org/?probe=fb7ab1b2d1) | Aug 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [df5f5f1ab4](https://linux-hardware.org/?probe=df5f5f1ab4) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | [6651af56b1](https://linux-hardware.org/?probe=6651af56b1) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | [a0e952ee9c](https://linux-hardware.org/?probe=a0e952ee9c) | Aug 19, 2021 |
| Google        | Kip                         | [11ba4592bc](https://linux-hardware.org/?probe=11ba4592bc) | Aug 19, 2021 |
| HP            | ProBook 450 G3              | [37a5e6b984](https://linux-hardware.org/?probe=37a5e6b984) | Aug 18, 2021 |
| HP            | 255 G1                      | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | [a5b305d6f5](https://linux-hardware.org/?probe=a5b305d6f5) | Aug 18, 2021 |
| HP            | EliteBook 8470p             | [ce21a853bc](https://linux-hardware.org/?probe=ce21a853bc) | Aug 18, 2021 |
| Dell          | Latitude E5520              | [9e4e9c3dea](https://linux-hardware.org/?probe=9e4e9c3dea) | Aug 17, 2021 |
| Lenovo        | B5400 s20278Q               | [24ebde0d00](https://linux-hardware.org/?probe=24ebde0d00) | Aug 17, 2021 |
| Dell          | Latitude E4310              | [489bf81791](https://linux-hardware.org/?probe=489bf81791) | Aug 17, 2021 |
| Lenovo        | ThinkPad W540 20BHS0KY08    | [6ba4712f8d](https://linux-hardware.org/?probe=6ba4712f8d) | Aug 16, 2021 |
| Dell          | Vostro 3491                 | [0f23db87f7](https://linux-hardware.org/?probe=0f23db87f7) | Aug 16, 2021 |
| HP            | ProBook 6470b               | [f42e212309](https://linux-hardware.org/?probe=f42e212309) | Aug 14, 2021 |
| HP            | Compaq 8710w                | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| Lenovo        | ThinkPad W540 20BHS1HR00    | [514e20d875](https://linux-hardware.org/?probe=514e20d875) | Aug 14, 2021 |
| HP            | Compaq CQ58                 | [23b1aab5c3](https://linux-hardware.org/?probe=23b1aab5c3) | Aug 13, 2021 |
| Toshiba       | Satellite P205D             | [95f23ff5ec](https://linux-hardware.org/?probe=95f23ff5ec) | Aug 13, 2021 |
| Dell          | Vostro 3491                 | [125085e464](https://linux-hardware.org/?probe=125085e464) | Aug 12, 2021 |
| ASUSTek       | N550JV                      | [a0023fa7d2](https://linux-hardware.org/?probe=a0023fa7d2) | Aug 12, 2021 |
| HP            | EliteBook 840 G3            | [4a660bcb77](https://linux-hardware.org/?probe=4a660bcb77) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [adee49adad](https://linux-hardware.org/?probe=adee49adad) | Aug 10, 2021 |
| Toshiba       | Satellite P205D             | [827f451413](https://linux-hardware.org/?probe=827f451413) | Aug 07, 2021 |
| Toshiba       | Satellite P205D             | [a39bd5d78b](https://linux-hardware.org/?probe=a39bd5d78b) | Aug 07, 2021 |
| Toshiba       | Satellite A100              | [7d3f237f02](https://linux-hardware.org/?probe=7d3f237f02) | Aug 07, 2021 |
| UNOWHY        | Y13G010S4EI                 | [a642818617](https://linux-hardware.org/?probe=a642818617) | Aug 06, 2021 |
| Notebook      | P65_P67RGRERA               | [07d63d9efc](https://linux-hardware.org/?probe=07d63d9efc) | Aug 06, 2021 |
| Sony          | VPCF236FM                   | [01a2971d58](https://linux-hardware.org/?probe=01a2971d58) | Aug 06, 2021 |
| Acer          | Aspire ES1-111              | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| Lenovo        | G460 0677                   | [18dd5bf1b0](https://linux-hardware.org/?probe=18dd5bf1b0) | Aug 05, 2021 |
| Acer          | Swift SF314-54G             | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| HP            | 2000                        | [27633bfd4b](https://linux-hardware.org/?probe=27633bfd4b) | Aug 03, 2021 |
| Acer          | Swift SF314-54G             | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Lenovo        | G460 0677                   | [1563cdbde9](https://linux-hardware.org/?probe=1563cdbde9) | Aug 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fb919a9b90](https://linux-hardware.org/?probe=fb919a9b90) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | [fb839f1401](https://linux-hardware.org/?probe=fb839f1401) | Jul 30, 2021 |
| Lenovo        | ThinkPad T500 2241CG9       | [912d324ee3](https://linux-hardware.org/?probe=912d324ee3) | Jul 29, 2021 |
| Lenovo        | G50-70 20351                | [90e216200b](https://linux-hardware.org/?probe=90e216200b) | Jul 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [4e46cf5851](https://linux-hardware.org/?probe=4e46cf5851) | Jul 29, 2021 |
| Sony          | SVE1512C6EB                 | [e1ce6add06](https://linux-hardware.org/?probe=e1ce6add06) | Jul 28, 2021 |
| Dell          | XPS 13 9310                 | [0a30fad96c](https://linux-hardware.org/?probe=0a30fad96c) | Jul 27, 2021 |
| HP            | 15                          | [6b1274ba87](https://linux-hardware.org/?probe=6b1274ba87) | Jul 27, 2021 |
| HP            | 15                          | [28f688d410](https://linux-hardware.org/?probe=28f688d410) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [9a8bc84b14](https://linux-hardware.org/?probe=9a8bc84b14) | Jul 26, 2021 |
| HP            | Notebook                    | [75e72e2359](https://linux-hardware.org/?probe=75e72e2359) | Jul 24, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Dell          | XPS 13 9310                 | [a81a047059](https://linux-hardware.org/?probe=a81a047059) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | [3cc56271ad](https://linux-hardware.org/?probe=3cc56271ad) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | [46032a26c5](https://linux-hardware.org/?probe=46032a26c5) | Jul 23, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [a76718434c](https://linux-hardware.org/?probe=a76718434c) | Jul 23, 2021 |
| Toshiba       | PORTEGE R930                | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| Dell          | Latitude E6330              | [772c8f269b](https://linux-hardware.org/?probe=772c8f269b) | Jul 21, 2021 |
| HP            | Unknown                     | [3f71deefd5](https://linux-hardware.org/?probe=3f71deefd5) | Jul 20, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| HP            | Laptop 17-by4xxx            | [d66405d958](https://linux-hardware.org/?probe=d66405d958) | Jul 19, 2021 |
| Dell          | XPS 13 9310                 | [29e1b14111](https://linux-hardware.org/?probe=29e1b14111) | Jul 18, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [561ed2dd58](https://linux-hardware.org/?probe=561ed2dd58) | Jul 18, 2021 |
| HP            | Laptop 17-ca0xxx            | [838188303a](https://linux-hardware.org/?probe=838188303a) | Jul 17, 2021 |
| Samsung       | R530/R730/P530              | [f95d4bb8f5](https://linux-hardware.org/?probe=f95d4bb8f5) | Jul 17, 2021 |
| Lenovo        | ThinkPad E485 20KU001CGE    | [4a42a910a2](https://linux-hardware.org/?probe=4a42a910a2) | Jul 15, 2021 |
| Samsung       | RV415/RV515/E3415           | [ebbe4a088d](https://linux-hardware.org/?probe=ebbe4a088d) | Jul 15, 2021 |
| HP            | Laptop 17-ca0xxx            | [3f9fb487ad](https://linux-hardware.org/?probe=3f9fb487ad) | Jul 15, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [46fb536e9d](https://linux-hardware.org/?probe=46fb536e9d) | Jul 13, 2021 |
| Lenovo        | ThinkPad W530 24479Q7       | [1feeb254be](https://linux-hardware.org/?probe=1feeb254be) | Jul 12, 2021 |
| Dell          | Inspiron 5485               | [d97549e586](https://linux-hardware.org/?probe=d97549e586) | Jul 11, 2021 |
| Toshiba       | Satellite L300              | [6103626346](https://linux-hardware.org/?probe=6103626346) | Jul 11, 2021 |
| HP            | Pavilion dv6                | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| HP            | Laptop 17-by4xxx            | [bd9ce451e8](https://linux-hardware.org/?probe=bd9ce451e8) | Jul 07, 2021 |
| Acer          | AOD270                      | [c829f9921a](https://linux-hardware.org/?probe=c829f9921a) | Jul 05, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [d14f09dc2d](https://linux-hardware.org/?probe=d14f09dc2d) | Jul 03, 2021 |
| ASUSTek       | S551LN                      | [dc682f3aa6](https://linux-hardware.org/?probe=dc682f3aa6) | Jul 02, 2021 |
| ASUSTek       | S551LN                      | [fca2998afc](https://linux-hardware.org/?probe=fca2998afc) | Jul 02, 2021 |
| Sony          | SVE1512C6EB                 | [76ce4f7188](https://linux-hardware.org/?probe=76ce4f7188) | Jul 01, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [0854799759](https://linux-hardware.org/?probe=0854799759) | Jul 01, 2021 |
| Lenovo        | ThinkPad T61 7661V9Z        | [ca7c8358f6](https://linux-hardware.org/?probe=ca7c8358f6) | Jul 01, 2021 |
| HP            | EliteBook 8470p             | [e0e0307e93](https://linux-hardware.org/?probe=e0e0307e93) | Jun 30, 2021 |
| ASUSTek       | X501A                       | [0a17576c5f](https://linux-hardware.org/?probe=0a17576c5f) | Jun 30, 2021 |
| HP            | Notebook                    | [998cae7006](https://linux-hardware.org/?probe=998cae7006) | Jun 30, 2021 |
| HP            | Laptop 15-dw0xxx            | [d5ed944b9b](https://linux-hardware.org/?probe=d5ed944b9b) | Jun 29, 2021 |
| Login Info... | LOG-MB47II7                 | [a4a339a28c](https://linux-hardware.org/?probe=a4a339a28c) | Jun 29, 2021 |
| Login Info... | LOG-MB47II7                 | [ad2829b254](https://linux-hardware.org/?probe=ad2829b254) | Jun 29, 2021 |
| Dell          | Inspiron 7773               | [fb0644646a](https://linux-hardware.org/?probe=fb0644646a) | Jun 28, 2021 |
| Dell          | Inspiron 5485               | [6b66b2cf07](https://linux-hardware.org/?probe=6b66b2cf07) | Jun 27, 2021 |
| Dell          | Latitude E6400              | [8d3183f3b8](https://linux-hardware.org/?probe=8d3183f3b8) | Jun 27, 2021 |
| ASUSTek       | K53SD                       | [6e8a57b8cf](https://linux-hardware.org/?probe=6e8a57b8cf) | Jun 26, 2021 |
| HP            | G72                         | [1d1f4771a9](https://linux-hardware.org/?probe=1d1f4771a9) | Jun 26, 2021 |
| Dell          | Latitude E5410              | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| Acer          | Aspire 7250                 | [e0311af549](https://linux-hardware.org/?probe=e0311af549) | Jun 23, 2021 |
| Medion        | P17609                      | [663f74686e](https://linux-hardware.org/?probe=663f74686e) | Jun 22, 2021 |
| Medion        | P17609                      | [268469bcbb](https://linux-hardware.org/?probe=268469bcbb) | Jun 22, 2021 |
| Lenovo        | ThinkPad L412 44034KG       | [5834d217ea](https://linux-hardware.org/?probe=5834d217ea) | Jun 21, 2021 |
| HP            | EliteBook 850 G1            | [e93b924262](https://linux-hardware.org/?probe=e93b924262) | Jun 20, 2021 |
| Lenovo        | ThinkPad X230 23255JU       | [0a92a62b0e](https://linux-hardware.org/?probe=0a92a62b0e) | Jun 19, 2021 |
| Acer          | Aspire VN7-791              | [ec33c41167](https://linux-hardware.org/?probe=ec33c41167) | Jun 17, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7729db091d](https://linux-hardware.org/?probe=7729db091d) | Jun 17, 2021 |
| Apple         | MacBookAir1,1               | [8492ea1603](https://linux-hardware.org/?probe=8492ea1603) | Jun 15, 2021 |
| Apple         | MacBookAir1,1               | [79b77baeb0](https://linux-hardware.org/?probe=79b77baeb0) | Jun 15, 2021 |
| TUXEDO        | Unknown                     | [bb04e3d7e3](https://linux-hardware.org/?probe=bb04e3d7e3) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [aea22f2fcb](https://linux-hardware.org/?probe=aea22f2fcb) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [821204c4fa](https://linux-hardware.org/?probe=821204c4fa) | Jun 13, 2021 |
| Dell          | Latitude 7390               | [38724f6fd8](https://linux-hardware.org/?probe=38724f6fd8) | Jun 11, 2021 |
| HP            | Compaq 6730s                | [c2207a656d](https://linux-hardware.org/?probe=c2207a656d) | Jun 10, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [f14555d2b6](https://linux-hardware.org/?probe=f14555d2b6) | Jun 09, 2021 |
| ASUSTek       | X510UQ                      | [78ae37cf88](https://linux-hardware.org/?probe=78ae37cf88) | Jun 09, 2021 |
| Quanta        | QL3 TBD                     | [bdb6375793](https://linux-hardware.org/?probe=bdb6375793) | Jun 08, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | [7dd86b4c8f](https://linux-hardware.org/?probe=7dd86b4c8f) | Jun 07, 2021 |
| Sony          | VPCF236FM                   | [91ec4b799a](https://linux-hardware.org/?probe=91ec4b799a) | Jun 07, 2021 |
| HP            | EliteBook 840 G3            | [b16595a449](https://linux-hardware.org/?probe=b16595a449) | Jun 07, 2021 |
| Samsung       | 300E5K/300E5Q               | [5319df9212](https://linux-hardware.org/?probe=5319df9212) | Jun 06, 2021 |
| Dell          | XPS 13 9310                 | [64d9cfa382](https://linux-hardware.org/?probe=64d9cfa382) | Jun 06, 2021 |
| Dell          | XPS 13 9310                 | [b3d1e1b346](https://linux-hardware.org/?probe=b3d1e1b346) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4760acae27](https://linux-hardware.org/?probe=4760acae27) | Jun 06, 2021 |
| Acer          | AOD270                      | [bf1409a0a6](https://linux-hardware.org/?probe=bf1409a0a6) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [94cafae76b](https://linux-hardware.org/?probe=94cafae76b) | Jun 06, 2021 |
| ASUSTek       | X55U                        | [4a44c680de](https://linux-hardware.org/?probe=4a44c680de) | Jun 05, 2021 |
| HP            | G72                         | [dfae1b630a](https://linux-hardware.org/?probe=dfae1b630a) | Jun 05, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [6710e0bf1c](https://linux-hardware.org/?probe=6710e0bf1c) | Jun 03, 2021 |
| Dell          | Inspiron 1545               | [56dc35f6b4](https://linux-hardware.org/?probe=56dc35f6b4) | Jun 03, 2021 |
| Lenovo        | ThinkPad T430s 2356H9G      | [1c45dc94ec](https://linux-hardware.org/?probe=1c45dc94ec) | Jun 02, 2021 |
| HP            | Laptop 15-da0xxx            | [7fea036197](https://linux-hardware.org/?probe=7fea036197) | Jun 01, 2021 |
| HP            | Pavilion dv7                | [e2cabcdb94](https://linux-hardware.org/?probe=e2cabcdb94) | May 31, 2021 |
| Acer          | Aspire E5-772G              | [fdb63cb152](https://linux-hardware.org/?probe=fdb63cb152) | May 31, 2021 |
| Dell          | Inspiron 1545               | [f0d0f92fd9](https://linux-hardware.org/?probe=f0d0f92fd9) | May 31, 2021 |
| Acer          | Aspire E5-575               | [9756ce58fc](https://linux-hardware.org/?probe=9756ce58fc) | May 31, 2021 |
| Notebook      | N85_87HP6                   | [241e2fc9bd](https://linux-hardware.org/?probe=241e2fc9bd) | May 30, 2021 |
| ASUSTek       | E200HA                      | [c323a8132a](https://linux-hardware.org/?probe=c323a8132a) | May 29, 2021 |
| Lenovo        | ThinkPad T470 20HES0FX00    | [5adbf6a949](https://linux-hardware.org/?probe=5adbf6a949) | May 28, 2021 |
| HP            | Laptop 15-gw0xxx            | [756904bec1](https://linux-hardware.org/?probe=756904bec1) | May 27, 2021 |
| Acer          | Aspire E5-573               | [2427d069a8](https://linux-hardware.org/?probe=2427d069a8) | May 27, 2021 |
| Dell          | Latitude E6330              | [7f740d929f](https://linux-hardware.org/?probe=7f740d929f) | May 25, 2021 |
| Dell          | Latitude E6330              | [3dee60820b](https://linux-hardware.org/?probe=3dee60820b) | May 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [b71f289496](https://linux-hardware.org/?probe=b71f289496) | May 22, 2021 |
| Packard Be... | EasyNote NX69HR             | [1e6a01d9bd](https://linux-hardware.org/?probe=1e6a01d9bd) | May 21, 2021 |
| Toshiba       | Satellite S55-C             | [6b411d236a](https://linux-hardware.org/?probe=6b411d236a) | May 20, 2021 |
| HP            | 250 G7 Notebook PC          | [850cd6457d](https://linux-hardware.org/?probe=850cd6457d) | May 20, 2021 |
| Sony          | VPCF236FM                   | [5e0b431cb8](https://linux-hardware.org/?probe=5e0b431cb8) | May 19, 2021 |
| Schenker      | XMG CORE 14 XCO14L20        | [65baefcf59](https://linux-hardware.org/?probe=65baefcf59) | May 19, 2021 |
| Dell          | Latitude E6320              | [b9503f222c](https://linux-hardware.org/?probe=b9503f222c) | May 19, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [a177654d13](https://linux-hardware.org/?probe=a177654d13) | May 19, 2021 |
| Dell          | Precision M6500             | [e56c7ef208](https://linux-hardware.org/?probe=e56c7ef208) | May 18, 2021 |
| HP            | ProBook 445 G7              | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| Toshiba       | Satellite L500D             | [959bafa5bd](https://linux-hardware.org/?probe=959bafa5bd) | May 17, 2021 |
| Lenovo        | ThinkPad R61 8934F9U        | [1747f3d32a](https://linux-hardware.org/?probe=1747f3d32a) | May 17, 2021 |
| Sony          | VPCF236FM                   | [22921fb0b7](https://linux-hardware.org/?probe=22921fb0b7) | May 16, 2021 |
| Apple         | MacBookAir3,2               | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| Dell          | Latitude E6330              | [11ae9c15ac](https://linux-hardware.org/?probe=11ae9c15ac) | May 13, 2021 |
| ASUSTek       | 1215N                       | [2e4383bd79](https://linux-hardware.org/?probe=2e4383bd79) | May 13, 2021 |
| HP            | 15                          | [85eb4cc12d](https://linux-hardware.org/?probe=85eb4cc12d) | May 11, 2021 |
| Toshiba       | Satellite L500              | [1ddf49c752](https://linux-hardware.org/?probe=1ddf49c752) | May 10, 2021 |
| HP            | Compaq 6730s                | [3592dd32d6](https://linux-hardware.org/?probe=3592dd32d6) | May 10, 2021 |
| ASUSTek       | UX305FA                     | [17e30b0724](https://linux-hardware.org/?probe=17e30b0724) | May 09, 2021 |
| Acer          | Aspire 5740                 | [ed5c778d4f](https://linux-hardware.org/?probe=ed5c778d4f) | May 09, 2021 |
| Acer          | Swift SF114-32              | [75220f50b9](https://linux-hardware.org/?probe=75220f50b9) | May 08, 2021 |
| Toshiba       | Satellite P755              | [aabbaa4370](https://linux-hardware.org/?probe=aabbaa4370) | May 08, 2021 |
| ASUSTek       | T100HAN                     | [4c3fc6257c](https://linux-hardware.org/?probe=4c3fc6257c) | May 07, 2021 |
| Dell          | Inspiron 3442               | [c8a5492bbe](https://linux-hardware.org/?probe=c8a5492bbe) | May 06, 2021 |
| Dell          | Latitude D630               | [bfcc642ec6](https://linux-hardware.org/?probe=bfcc642ec6) | May 05, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Dell          | Inspiron 3442               | [3f22b7b8c7](https://linux-hardware.org/?probe=3f22b7b8c7) | May 02, 2021 |
| ASUSTek       | X553MA                      | [24844a899b](https://linux-hardware.org/?probe=24844a899b) | Apr 30, 2021 |
| ASUSTek       | X553MA                      | [2a6a48781c](https://linux-hardware.org/?probe=2a6a48781c) | Apr 29, 2021 |
| Lenovo        | ZHAOYANG K43c-80 81HX       | [de6628af88](https://linux-hardware.org/?probe=de6628af88) | Apr 27, 2021 |
| HP            | 15                          | [85c3bbf6d2](https://linux-hardware.org/?probe=85c3bbf6d2) | Apr 26, 2021 |
| HP            | 15                          | [8b59240afa](https://linux-hardware.org/?probe=8b59240afa) | Apr 26, 2021 |
| Dell          | Latitude E6540              | [a3f162170c](https://linux-hardware.org/?probe=a3f162170c) | Apr 26, 2021 |
| Lenovo        | ThinkPad X230 2320JPU       | [a3fbebddc1](https://linux-hardware.org/?probe=a3fbebddc1) | Apr 26, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | [8f49103dc5](https://linux-hardware.org/?probe=8f49103dc5) | Apr 24, 2021 |
| ASUSTek       | T100HAN                     | [fe82c2f357](https://linux-hardware.org/?probe=fe82c2f357) | Apr 23, 2021 |
| Lenovo        | V15-ADA 82C7                | [bf61694de7](https://linux-hardware.org/?probe=bf61694de7) | Apr 22, 2021 |
| Coradir       | Coradir/ES10IS5             | [74f5215b3f](https://linux-hardware.org/?probe=74f5215b3f) | Apr 20, 2021 |
| Lenovo        | B5400 s20278Q               | [48b8cfd930](https://linux-hardware.org/?probe=48b8cfd930) | Apr 20, 2021 |
| ASUSTek       | K52Jr                       | [685e2a3341](https://linux-hardware.org/?probe=685e2a3341) | Apr 20, 2021 |
| Dell          | Vostro V130                 | [36a06dbff2](https://linux-hardware.org/?probe=36a06dbff2) | Apr 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1c4386aedf](https://linux-hardware.org/?probe=1c4386aedf) | Apr 19, 2021 |
| Acer          | Aspire ES1-521              | [6e75e7c288](https://linux-hardware.org/?probe=6e75e7c288) | Apr 19, 2021 |
| Acer          | E1-510                      | [d5a5b71d6a](https://linux-hardware.org/?probe=d5a5b71d6a) | Apr 17, 2021 |
| Acer          | Acadia V1.40                | [46bad3ecf2](https://linux-hardware.org/?probe=46bad3ecf2) | Apr 17, 2021 |
| Dell          | Latitude E5440              | [3423e4a8a9](https://linux-hardware.org/?probe=3423e4a8a9) | Apr 17, 2021 |
| HUAWEI        | KPL-W0X                     | [1797098345](https://linux-hardware.org/?probe=1797098345) | Apr 16, 2021 |
| Lenovo        | V15-ADA 82C7                | [bc633becd7](https://linux-hardware.org/?probe=bc633becd7) | Apr 16, 2021 |
| ASUSTek       | T100HAN                     | [0751d8f0d6](https://linux-hardware.org/?probe=0751d8f0d6) | Apr 15, 2021 |
| MSI           | GS63 7RD                    | [0e3e856520](https://linux-hardware.org/?probe=0e3e856520) | Apr 15, 2021 |
| Acer          | E1-510                      | [a831e2fdb1](https://linux-hardware.org/?probe=a831e2fdb1) | Apr 15, 2021 |
| ASUSTek       | N53SV                       | [fa885b5df7](https://linux-hardware.org/?probe=fa885b5df7) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bfe9ff4cf7](https://linux-hardware.org/?probe=bfe9ff4cf7) | Apr 14, 2021 |
| ASUSTek       | T100HAN                     | [e24c5b97f6](https://linux-hardware.org/?probe=e24c5b97f6) | Apr 14, 2021 |
| ASUSTek       | N750JK                      | [38117d02be](https://linux-hardware.org/?probe=38117d02be) | Apr 11, 2021 |
| MSI           | GL62M 7REX                  | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| HP            | Pavilion dv6                | [8b9cd8bac1](https://linux-hardware.org/?probe=8b9cd8bac1) | Apr 07, 2021 |
| ASUSTek       | X302LA                      | [e1432d67a7](https://linux-hardware.org/?probe=e1432d67a7) | Apr 06, 2021 |
| Clevo         | M7x0S                       | [e3cc77148f](https://linux-hardware.org/?probe=e3cc77148f) | Apr 06, 2021 |
| Sony          | VPCF236FM                   | [c7f9905fe5](https://linux-hardware.org/?probe=c7f9905fe5) | Apr 05, 2021 |
| Medion        | E7216                       | [df0198f099](https://linux-hardware.org/?probe=df0198f099) | Apr 04, 2021 |
| Dell          | System XPS L702X            | [e15be45763](https://linux-hardware.org/?probe=e15be45763) | Apr 04, 2021 |
| Sony          | VPCF236FM                   | [cb5204d13b](https://linux-hardware.org/?probe=cb5204d13b) | Apr 04, 2021 |
| Lenovo        | ThinkPad R61 8934F9U        | [8e7e380b3b](https://linux-hardware.org/?probe=8e7e380b3b) | Apr 04, 2021 |
| Lenovo        | ThinkPad X200T 7453CTO      | [0e029ba8c4](https://linux-hardware.org/?probe=0e029ba8c4) | Apr 03, 2021 |
| Gateway       | NV57H                       | [2474e1aa77](https://linux-hardware.org/?probe=2474e1aa77) | Apr 03, 2021 |
| Lenovo        | ThinkPad W520 4284A95       | [2cc9f7db66](https://linux-hardware.org/?probe=2cc9f7db66) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| Dell          | Latitude E6330              | [ba3e536b64](https://linux-hardware.org/?probe=ba3e536b64) | Apr 02, 2021 |
| Dell          | Latitude D630               | [3a68abfa65](https://linux-hardware.org/?probe=3a68abfa65) | Mar 31, 2021 |
| ASUSTek       | T100HAN                     | [b16cab1e51](https://linux-hardware.org/?probe=b16cab1e51) | Mar 31, 2021 |
| Dell          | Latitude E6430              | [bf705c8135](https://linux-hardware.org/?probe=bf705c8135) | Mar 30, 2021 |
| Dell          | Inspiron N4030              | [1cc1db9dc1](https://linux-hardware.org/?probe=1cc1db9dc1) | Mar 30, 2021 |
| Lenovo        | ThinkPad X200T 7453CTO      | [815692ace4](https://linux-hardware.org/?probe=815692ace4) | Mar 28, 2021 |
| Toshiba       | Satellite C655D             | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell          | System XPS L502X            | [7986186fbc](https://linux-hardware.org/?probe=7986186fbc) | Mar 28, 2021 |
| Acer          | Ferrari IV                  | [60873d0a0e](https://linux-hardware.org/?probe=60873d0a0e) | Mar 27, 2021 |
| Toshiba       | Satellite E45W-C            | [8429536a24](https://linux-hardware.org/?probe=8429536a24) | Mar 27, 2021 |
| Direkt-Tek    | DTLAPY116-1                 | [e6ff85a54d](https://linux-hardware.org/?probe=e6ff85a54d) | Mar 26, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [51a3bc61bb](https://linux-hardware.org/?probe=51a3bc61bb) | Mar 25, 2021 |
| Acer          | Aspire V5-531               | [7aa91d503d](https://linux-hardware.org/?probe=7aa91d503d) | Mar 25, 2021 |
| Acer          | Aspire V5-531               | [15d116776f](https://linux-hardware.org/?probe=15d116776f) | Mar 25, 2021 |
| HP            | EliteBook 850 G3            | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Dell          | Latitude E4300              | [7734046382](https://linux-hardware.org/?probe=7734046382) | Mar 25, 2021 |
| Lenovo        | ThinkPad T495 20NJ0015SP    | [f5ed2fe938](https://linux-hardware.org/?probe=f5ed2fe938) | Mar 23, 2021 |
| Toshiba       | Satellite L300              | [7eb9b157fc](https://linux-hardware.org/?probe=7eb9b157fc) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire A317-52              | [bb22a21887](https://linux-hardware.org/?probe=bb22a21887) | Mar 22, 2021 |
| Acer          | Aspire A317-52              | [655572af16](https://linux-hardware.org/?probe=655572af16) | Mar 22, 2021 |
| Lenovo        | IdeaPad N585                | [081d063f0a](https://linux-hardware.org/?probe=081d063f0a) | Mar 22, 2021 |
| ASUSTek       | X51RL                       | [0451b6db0a](https://linux-hardware.org/?probe=0451b6db0a) | Mar 21, 2021 |
| ASUSTek       | X553MA                      | [01899b17ca](https://linux-hardware.org/?probe=01899b17ca) | Mar 20, 2021 |
| ASUSTek       | K52JT                       | [06ae75152b](https://linux-hardware.org/?probe=06ae75152b) | Mar 20, 2021 |
| Lenovo        | V560                        | [0f271bca24](https://linux-hardware.org/?probe=0f271bca24) | Mar 20, 2021 |
| Lenovo        | V560                        | [841e4c52d6](https://linux-hardware.org/?probe=841e4c52d6) | Mar 20, 2021 |
| Apple         | MacBookAir4,2               | [8a1a88952c](https://linux-hardware.org/?probe=8a1a88952c) | Mar 19, 2021 |
| Lenovo        | Z50-75 80EC                 | [9c2537edc4](https://linux-hardware.org/?probe=9c2537edc4) | Mar 18, 2021 |
| Lenovo        | Z50-75 80EC                 | [0fa936cf65](https://linux-hardware.org/?probe=0fa936cf65) | Mar 18, 2021 |
| HP            | ProBook 430 G5              | [45a9198d77](https://linux-hardware.org/?probe=45a9198d77) | Mar 18, 2021 |
| HP            | EliteBook 840 G2            | [946190bdea](https://linux-hardware.org/?probe=946190bdea) | Mar 18, 2021 |
| Toshiba       | Satellite L775              | [559738d7ef](https://linux-hardware.org/?probe=559738d7ef) | Mar 17, 2021 |
| Lenovo        | B50-70 20384                | [7e50de86dc](https://linux-hardware.org/?probe=7e50de86dc) | Mar 17, 2021 |
| Dell          | Latitude 7480               | [149339b634](https://linux-hardware.org/?probe=149339b634) | Mar 17, 2021 |
| ASUSTek       | K52JT                       | [f58f87e21c](https://linux-hardware.org/?probe=f58f87e21c) | Mar 16, 2021 |
| HP            | Laptop 14s-fq0xxx           | [10c1219043](https://linux-hardware.org/?probe=10c1219043) | Mar 15, 2021 |
| Notebook      | N14xWU                      | [0d11ae6b23](https://linux-hardware.org/?probe=0d11ae6b23) | Mar 15, 2021 |
| HP            | Laptop 15-dw0xxx            | [3a99165c4b](https://linux-hardware.org/?probe=3a99165c4b) | Mar 15, 2021 |
| ASUSTek       | UX305FA                     | [5cfa71c7c9](https://linux-hardware.org/?probe=5cfa71c7c9) | Mar 14, 2021 |
| Toshiba       | PORTEGE R930                | [6e5981a1c8](https://linux-hardware.org/?probe=6e5981a1c8) | Mar 14, 2021 |
| ASUSTek       | UX305FA                     | [4a8a3fbe80](https://linux-hardware.org/?probe=4a8a3fbe80) | Mar 14, 2021 |
| Dell          | Inspiron 5566               | [296f4ef1fc](https://linux-hardware.org/?probe=296f4ef1fc) | Mar 14, 2021 |
| Dell          | Inspiron 5566               | [9d9f8210f0](https://linux-hardware.org/?probe=9d9f8210f0) | Mar 14, 2021 |
| MSI           | GE76 Raider 10UH            | [33402f594e](https://linux-hardware.org/?probe=33402f594e) | Mar 13, 2021 |
| MSI           | GE76 Raider 10UH            | [791c8ef629](https://linux-hardware.org/?probe=791c8ef629) | Mar 13, 2021 |
| Dell          | Inspiron N4030              | [c46b3d0202](https://linux-hardware.org/?probe=c46b3d0202) | Mar 11, 2021 |
| Dell          | Latitude E6330              | [ac5ebc37a0](https://linux-hardware.org/?probe=ac5ebc37a0) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | [b69ca67a4f](https://linux-hardware.org/?probe=b69ca67a4f) | Mar 11, 2021 |
| HP            | 15                          | [08233bfc88](https://linux-hardware.org/?probe=08233bfc88) | Mar 10, 2021 |
| Acer          | Aspire A315-57G             | [f088cd5cf8](https://linux-hardware.org/?probe=f088cd5cf8) | Mar 08, 2021 |
| HP            | Pavilion 17                 | [4c4d69f2f4](https://linux-hardware.org/?probe=4c4d69f2f4) | Mar 08, 2021 |
| Toshiba       | TECRA M7                    | [a40f61b08a](https://linux-hardware.org/?probe=a40f61b08a) | Mar 08, 2021 |
| ASUSTek       | GL553VD                     | [a590a174be](https://linux-hardware.org/?probe=a590a174be) | Mar 07, 2021 |
| MSI           | MS-1727                     | [cb6654e18b](https://linux-hardware.org/?probe=cb6654e18b) | Mar 06, 2021 |
| Dell          | Latitude E6530              | [141e382738](https://linux-hardware.org/?probe=141e382738) | Mar 06, 2021 |
| HP            | Pavilion 15                 | [bf7c710709](https://linux-hardware.org/?probe=bf7c710709) | Mar 05, 2021 |
| Toshiba       | Satellite L350D             | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| HP            | Pavilion 15                 | [15bbeb15c3](https://linux-hardware.org/?probe=15bbeb15c3) | Mar 05, 2021 |
| Dell          | XPS 13 7390                 | [ff72c4978e](https://linux-hardware.org/?probe=ff72c4978e) | Mar 03, 2021 |
| Dell          | System XPS L502X            | [9b0f41d77e](https://linux-hardware.org/?probe=9b0f41d77e) | Mar 03, 2021 |
| Schenker      | XMG CORE 17(M20, RTX 206... | [18912b688f](https://linux-hardware.org/?probe=18912b688f) | Mar 03, 2021 |
| Medion        | WIM2220                     | [7f1eead610](https://linux-hardware.org/?probe=7f1eead610) | Mar 01, 2021 |
| Toshiba       | Satellite L300              | [97a2208e46](https://linux-hardware.org/?probe=97a2208e46) | Feb 28, 2021 |
| Dell          | Latitude E6330              | [64767019e5](https://linux-hardware.org/?probe=64767019e5) | Feb 28, 2021 |
| Toshiba       | Satellite L300              | [1d638916dd](https://linux-hardware.org/?probe=1d638916dd) | Feb 27, 2021 |
| ASUSTek       | X550EA                      | [3ccc6c99ce](https://linux-hardware.org/?probe=3ccc6c99ce) | Feb 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | [27cfc26b43](https://linux-hardware.org/?probe=27cfc26b43) | Feb 26, 2021 |
| Lenovo        | ThinkPad T480 20L5000AFR    | [8b1b96af72](https://linux-hardware.org/?probe=8b1b96af72) | Feb 26, 2021 |
| HP            | ProBook 6465b               | [a046d9bd06](https://linux-hardware.org/?probe=a046d9bd06) | Feb 25, 2021 |
| HP            | Pavilion dv6                | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| Gateway       | LT40                        | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | [97f3e486f0](https://linux-hardware.org/?probe=97f3e486f0) | Feb 22, 2021 |
| ASUSTek       | K43TK                       | [d004408c66](https://linux-hardware.org/?probe=d004408c66) | Feb 22, 2021 |
| HP            | Compaq 6735b                | [103297afaf](https://linux-hardware.org/?probe=103297afaf) | Feb 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S1G104    | [d4273cb949](https://linux-hardware.org/?probe=d4273cb949) | Feb 22, 2021 |
| Acer          | Aspire ES1-521              | [4d9a43cd2c](https://linux-hardware.org/?probe=4d9a43cd2c) | Feb 22, 2021 |
| Dell          | Latitude E6420              | [5c9fa0347d](https://linux-hardware.org/?probe=5c9fa0347d) | Feb 21, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f61ed1e295](https://linux-hardware.org/?probe=f61ed1e295) | Feb 20, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3a32460b92](https://linux-hardware.org/?probe=3a32460b92) | Feb 19, 2021 |
| ASUSTek       | 1015PE                      | [16f37f6676](https://linux-hardware.org/?probe=16f37f6676) | Feb 18, 2021 |
| Dell          | System XPS L502X            | [c5d51e09ab](https://linux-hardware.org/?probe=c5d51e09ab) | Feb 18, 2021 |
| Toshiba       | TECRA M7                    | [1754c58f4f](https://linux-hardware.org/?probe=1754c58f4f) | Feb 18, 2021 |
| HP            | Pavilion dv2500             | [fd5bd80a7d](https://linux-hardware.org/?probe=fd5bd80a7d) | Feb 18, 2021 |
| Dell          | Inspiron 3442               | [5d25709db0](https://linux-hardware.org/?probe=5d25709db0) | Feb 17, 2021 |
| HP            | Pavilion dv2500             | [532a81acd0](https://linux-hardware.org/?probe=532a81acd0) | Feb 17, 2021 |
| ASUSTek       | N550JK                      | [9d76fe4c9a](https://linux-hardware.org/?probe=9d76fe4c9a) | Feb 16, 2021 |
| HP            | Stream Notebook PC 11       | [1d94335b59](https://linux-hardware.org/?probe=1d94335b59) | Feb 16, 2021 |
| HP            | EliteBook 840 G2            | [299705d145](https://linux-hardware.org/?probe=299705d145) | Feb 15, 2021 |
| Acer          | Aspire ES1-521              | [a8669fea8d](https://linux-hardware.org/?probe=a8669fea8d) | Feb 15, 2021 |
| Apple         | MacBook3,1                  | [8248e0b63a](https://linux-hardware.org/?probe=8248e0b63a) | Feb 14, 2021 |
| Sony          | VGN-NR11Z_T                 | [6ff21c8f17](https://linux-hardware.org/?probe=6ff21c8f17) | Feb 13, 2021 |
| HP            | Pavilion Laptop 14-ce1xx... | [2a1ba44e02](https://linux-hardware.org/?probe=2a1ba44e02) | Feb 12, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [922c8b7dfd](https://linux-hardware.org/?probe=922c8b7dfd) | Feb 11, 2021 |
| Dell          | Latitude D830               | [77e54cbe3e](https://linux-hardware.org/?probe=77e54cbe3e) | Feb 10, 2021 |
| Lenovo        | ThinkPad X201 3680PKG       | [c93bf320d7](https://linux-hardware.org/?probe=c93bf320d7) | Feb 10, 2021 |
| Sony          | VPCEH1AFX                   | [9a652ce0c0](https://linux-hardware.org/?probe=9a652ce0c0) | Feb 10, 2021 |
| HP            | Notebook                    | [e9512b4333](https://linux-hardware.org/?probe=e9512b4333) | Feb 09, 2021 |
| HP            | Notebook                    | [1fa1c10289](https://linux-hardware.org/?probe=1fa1c10289) | Feb 09, 2021 |
| Dell          | Inspiron 5490               | [3644971313](https://linux-hardware.org/?probe=3644971313) | Feb 09, 2021 |
| ASUSTek       | K52JT                       | [f4015df0c9](https://linux-hardware.org/?probe=f4015df0c9) | Feb 08, 2021 |
| ASUSTek       | K56CM                       | [cdb06fd1e3](https://linux-hardware.org/?probe=cdb06fd1e3) | Feb 06, 2021 |
| ASUSTek       | K56CM                       | [177d8987e5](https://linux-hardware.org/?probe=177d8987e5) | Feb 06, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [75c312983b](https://linux-hardware.org/?probe=75c312983b) | Feb 06, 2021 |
| Sony          | SVF1421E2EW                 | [95111e84c2](https://linux-hardware.org/?probe=95111e84c2) | Feb 06, 2021 |
| Sony          | VGN-AR71S                   | [a5c6539aca](https://linux-hardware.org/?probe=a5c6539aca) | Feb 05, 2021 |
| Jumper        | EZbook                      | [084a3c40f3](https://linux-hardware.org/?probe=084a3c40f3) | Feb 05, 2021 |
| Lenovo        | ThinkPad X230 2320JPU       | [62582d4d7f](https://linux-hardware.org/?probe=62582d4d7f) | Feb 03, 2021 |
| Lenovo        | ThinkPad X230 2320JPU       | [0ee5585f96](https://linux-hardware.org/?probe=0ee5585f96) | Feb 03, 2021 |
| Dell          | System XPS L502X            | [1204db7bcd](https://linux-hardware.org/?probe=1204db7bcd) | Feb 03, 2021 |
| Dell          | System XPS L502X            | [7b564d8b8f](https://linux-hardware.org/?probe=7b564d8b8f) | Feb 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7954ba7fc4](https://linux-hardware.org/?probe=7954ba7fc4) | Feb 02, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [56f886b83b](https://linux-hardware.org/?probe=56f886b83b) | Feb 02, 2021 |
| Acer          | AOD257                      | [6516a78368](https://linux-hardware.org/?probe=6516a78368) | Feb 01, 2021 |
| Acer          | AOD257                      | [f435e31f67](https://linux-hardware.org/?probe=f435e31f67) | Feb 01, 2021 |
| Lenovo        | ThinkPad T510 4484Y1X       | [49bbbfe6d1](https://linux-hardware.org/?probe=49bbbfe6d1) | Feb 01, 2021 |
| HP            | ZBook 17 G2                 | [ccf18d4e4e](https://linux-hardware.org/?probe=ccf18d4e4e) | Jan 31, 2021 |
| Lenovo        | G500s 20245                 | [68cd2bf232](https://linux-hardware.org/?probe=68cd2bf232) | Jan 31, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [529126337c](https://linux-hardware.org/?probe=529126337c) | Jan 31, 2021 |
| HP            | Pavilion Sleekbook 15       | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| Dell          | Latitude D630               | [e4bd287d04](https://linux-hardware.org/?probe=e4bd287d04) | Jan 31, 2021 |
| Dell          | Inspiron 7720               | [557eb8d8f0](https://linux-hardware.org/?probe=557eb8d8f0) | Jan 29, 2021 |
| Dell          | Inspiron 7720               | [6239b8c7b8](https://linux-hardware.org/?probe=6239b8c7b8) | Jan 29, 2021 |
| Samsung       | Q330                        | [0120157b2e](https://linux-hardware.org/?probe=0120157b2e) | Jan 28, 2021 |
| HP            | Compaq 15                   | [863dcc43b8](https://linux-hardware.org/?probe=863dcc43b8) | Jan 27, 2021 |
| Toshiba       | Satellite C850-1GL          | [bc5255260e](https://linux-hardware.org/?probe=bc5255260e) | Jan 26, 2021 |
| Dell          | Latitude 7490               | [f7dfec504b](https://linux-hardware.org/?probe=f7dfec504b) | Jan 26, 2021 |
| Dell          | Inspiron 7720               | [923d51902b](https://linux-hardware.org/?probe=923d51902b) | Jan 25, 2021 |
| Clevo         | W760T/M740T/M760T           | [4b75664c6f](https://linux-hardware.org/?probe=4b75664c6f) | Jan 25, 2021 |
| HP            | Pavilion dv6                | [27d7eb5a92](https://linux-hardware.org/?probe=27d7eb5a92) | Jan 25, 2021 |
| Acer          | Aspire E5-571               | [2855a371c3](https://linux-hardware.org/?probe=2855a371c3) | Jan 24, 2021 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [22b00ab4e5](https://linux-hardware.org/?probe=22b00ab4e5) | Jan 23, 2021 |
| HP            | EliteBook 8560p             | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| HP            | Pavilion g7                 | [1e465cca1b](https://linux-hardware.org/?probe=1e465cca1b) | Jan 22, 2021 |
| Lenovo        | G500 20236                  | [ba6a60bdac](https://linux-hardware.org/?probe=ba6a60bdac) | Jan 20, 2021 |
| Dell          | Inspiron 5490               | [9dab1fde54](https://linux-hardware.org/?probe=9dab1fde54) | Jan 20, 2021 |
| Dell          | Latitude D430               | [e364de4914](https://linux-hardware.org/?probe=e364de4914) | Jan 19, 2021 |
| Dell          | Latitude D430               | [632ede8190](https://linux-hardware.org/?probe=632ede8190) | Jan 19, 2021 |
| ASUSTek       | N56VZ                       | [039ce9b983](https://linux-hardware.org/?probe=039ce9b983) | Jan 19, 2021 |
| HP            | Notebook                    | [5724cfe110](https://linux-hardware.org/?probe=5724cfe110) | Jan 19, 2021 |
| Medion        | WIM2220                     | [ac6c69073e](https://linux-hardware.org/?probe=ac6c69073e) | Jan 17, 2021 |
| Acer          | Aspire 5741                 | [15311207d3](https://linux-hardware.org/?probe=15311207d3) | Jan 17, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [3cbd0f0cda](https://linux-hardware.org/?probe=3cbd0f0cda) | Jan 17, 2021 |
| Sony          | VPCZ126GG                   | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Toshiba       | Satellite Pro C660          | [85263df56a](https://linux-hardware.org/?probe=85263df56a) | Jan 14, 2021 |
| Acer          | Aspire 5733                 | [a6c21535b6](https://linux-hardware.org/?probe=a6c21535b6) | Jan 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [80270e2d6e](https://linux-hardware.org/?probe=80270e2d6e) | Jan 13, 2021 |
| Dell          | Inspiron 5584               | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| ASUSTek       | BU401LG                     | [38da8474f2](https://linux-hardware.org/?probe=38da8474f2) | Jan 12, 2021 |
| Samsung       | RC410/RC510/RC710           | [3ddef39d9e](https://linux-hardware.org/?probe=3ddef39d9e) | Jan 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [33653bbaea](https://linux-hardware.org/?probe=33653bbaea) | Jan 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [71609aabd3](https://linux-hardware.org/?probe=71609aabd3) | Jan 11, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | Latitude E6400              | [83d8d95301](https://linux-hardware.org/?probe=83d8d95301) | Jan 10, 2021 |
| HP            | Laptop 15-ra0xx             | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| Toshiba       | Satellite L350D             | [679698e4f1](https://linux-hardware.org/?probe=679698e4f1) | Jan 09, 2021 |
| ASUSTek       | X553MA                      | [a8dacfffee](https://linux-hardware.org/?probe=a8dacfffee) | Jan 09, 2021 |
| Dell          | Latitude E6400              | [a12b8f8f80](https://linux-hardware.org/?probe=a12b8f8f80) | Jan 08, 2021 |
| Lenovo        | G460 20041                  | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| HP            | Pavilion dv6                | [f7f371d643](https://linux-hardware.org/?probe=f7f371d643) | Jan 05, 2021 |
| Samsung       | 530U3C/530U4C               | [5bc500f949](https://linux-hardware.org/?probe=5bc500f949) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [d1bdd46e5a](https://linux-hardware.org/?probe=d1bdd46e5a) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [dbab55b2da](https://linux-hardware.org/?probe=dbab55b2da) | Jan 04, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [49395e2b5a](https://linux-hardware.org/?probe=49395e2b5a) | Jan 04, 2021 |
| Acer          | Extensa 5230                | [4415e4e70d](https://linux-hardware.org/?probe=4415e4e70d) | Jan 04, 2021 |
| ASUSTek       | K55VD                       | [2df37718ac](https://linux-hardware.org/?probe=2df37718ac) | Jan 04, 2021 |
| AMI           | Intel                       | [0ea3da73ad](https://linux-hardware.org/?probe=0ea3da73ad) | Jan 04, 2021 |
| HP            | Elite x2 1012 G1 Tablet     | [b0b6d27ef9](https://linux-hardware.org/?probe=b0b6d27ef9) | Jan 03, 2021 |
| HP            | Elite x2 1012 G1 Tablet     | [39fa2bb12d](https://linux-hardware.org/?probe=39fa2bb12d) | Jan 03, 2021 |
| HP            | Pavilion dv7                | [69c177d931](https://linux-hardware.org/?probe=69c177d931) | Jan 02, 2021 |
| HP            | Pavilion dv7                | [35bda93da4](https://linux-hardware.org/?probe=35bda93da4) | Jan 02, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [492bf814a7](https://linux-hardware.org/?probe=492bf814a7) | Dec 31, 2020 |
| HP            | Notebook                    | [638aeddfe5](https://linux-hardware.org/?probe=638aeddfe5) | Dec 29, 2020 |
| Dell          | Inspiron 3541               | [dc6edaf97d](https://linux-hardware.org/?probe=dc6edaf97d) | Dec 29, 2020 |
| HP            | EliteBook 745 G6            | [abbb1bd093](https://linux-hardware.org/?probe=abbb1bd093) | Dec 28, 2020 |
| Notebook      | P9XXEN_EF_ED                | [e12068dde4](https://linux-hardware.org/?probe=e12068dde4) | Dec 28, 2020 |
| Dell          | Inspiron 7348               | [843004563b](https://linux-hardware.org/?probe=843004563b) | Dec 28, 2020 |
| HP            | Pavilion dv7                | [a076317396](https://linux-hardware.org/?probe=a076317396) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | [b5761576fc](https://linux-hardware.org/?probe=b5761576fc) | Dec 27, 2020 |
| Samsung       | RV415/RV515/E3415           | [567058f9d7](https://linux-hardware.org/?probe=567058f9d7) | Dec 27, 2020 |
| Clevo         | W35_37ET                    | [7623914c7d](https://linux-hardware.org/?probe=7623914c7d) | Dec 27, 2020 |
| Acer          | Aspire A515-43              | [cdd77b000b](https://linux-hardware.org/?probe=cdd77b000b) | Dec 27, 2020 |
| Acer          | Aspire A515-55              | [8dae06d8e5](https://linux-hardware.org/?probe=8dae06d8e5) | Dec 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [b47b8aade9](https://linux-hardware.org/?probe=b47b8aade9) | Dec 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [9c3c5c774e](https://linux-hardware.org/?probe=9c3c5c774e) | Dec 24, 2020 |
| Acer          | Extensa 5235                | [3ddcc1fd9e](https://linux-hardware.org/?probe=3ddcc1fd9e) | Dec 24, 2020 |
| Acer          | Extensa 5235                | [4b5b00203c](https://linux-hardware.org/?probe=4b5b00203c) | Dec 24, 2020 |
| Acer          | Extensa 5235                | [847b5cf2ab](https://linux-hardware.org/?probe=847b5cf2ab) | Dec 24, 2020 |
| HP            | EliteBook 8460p             | [084780fb78](https://linux-hardware.org/?probe=084780fb78) | Dec 23, 2020 |
| Acer          | Extensa 215-31              | [d3dd4986ae](https://linux-hardware.org/?probe=d3dd4986ae) | Dec 23, 2020 |
| HP            | ProBook 450 G5              | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| HP            | ProBook 430 G5              | [1937524c32](https://linux-hardware.org/?probe=1937524c32) | Dec 22, 2020 |
| HP            | Pavilion dv6                | [5e3b4a96ff](https://linux-hardware.org/?probe=5e3b4a96ff) | Dec 22, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Dell          | XPS L701X                   | [c730aaa61e](https://linux-hardware.org/?probe=c730aaa61e) | Dec 21, 2020 |
| HP            | Laptop 15-db1xxx            | [c7f70318f1](https://linux-hardware.org/?probe=c7f70318f1) | Dec 21, 2020 |
| HP            | Laptop 15-db1xxx            | [03cb85a270](https://linux-hardware.org/?probe=03cb85a270) | Dec 21, 2020 |
| HP            | Laptop 15-db0xxx            | [445ca5b97b](https://linux-hardware.org/?probe=445ca5b97b) | Dec 21, 2020 |
| ASUSTek       | P52F                        | [cffa620df7](https://linux-hardware.org/?probe=cffa620df7) | Dec 19, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [ca9265e9b1](https://linux-hardware.org/?probe=ca9265e9b1) | Dec 18, 2020 |
| Apple         | MacBookPro14,1              | [16916f679a](https://linux-hardware.org/?probe=16916f679a) | Dec 17, 2020 |
| HP            | EliteBook 2540p             | [0a896a3335](https://linux-hardware.org/?probe=0a896a3335) | Dec 17, 2020 |
| HP            | Pavilion dv7                | [efdb11d251](https://linux-hardware.org/?probe=efdb11d251) | Dec 17, 2020 |
| Sony          | VGN-AR41E                   | [52ca609559](https://linux-hardware.org/?probe=52ca609559) | Dec 17, 2020 |
| Sony          | VGN-AR41E                   | [8e8aaf9c2e](https://linux-hardware.org/?probe=8e8aaf9c2e) | Dec 17, 2020 |
| HP            | ZBook 17 G6                 | [d253ffd0f9](https://linux-hardware.org/?probe=d253ffd0f9) | Dec 16, 2020 |
| Acer          | Acadia V1.45                | [f03c43a6cc](https://linux-hardware.org/?probe=f03c43a6cc) | Dec 16, 2020 |
| Dell          | Inspiron 7348               | [3f25978672](https://linux-hardware.org/?probe=3f25978672) | Dec 15, 2020 |
| Dell          | Inspiron 7348               | [a83aeea4c8](https://linux-hardware.org/?probe=a83aeea4c8) | Dec 15, 2020 |
| Toshiba       | Satellite T110              | [a6aa049d77](https://linux-hardware.org/?probe=a6aa049d77) | Dec 14, 2020 |
| Dell          | Inspiron 5737               | [a91a5b0027](https://linux-hardware.org/?probe=a91a5b0027) | Dec 13, 2020 |
| Dell          | Latitude E5550              | [b515199940](https://linux-hardware.org/?probe=b515199940) | Dec 13, 2020 |
| Sony          | VGN-FZ31M                   | [a66ff4c9f1](https://linux-hardware.org/?probe=a66ff4c9f1) | Dec 13, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [2494a33ba4](https://linux-hardware.org/?probe=2494a33ba4) | Dec 13, 2020 |
| Dell          | Latitude E6420              | [e5430b607e](https://linux-hardware.org/?probe=e5430b607e) | Dec 13, 2020 |
| Dell          | Latitude E6420              | [5b197971ae](https://linux-hardware.org/?probe=5b197971ae) | Dec 13, 2020 |
| Lenovo        | G50-30 80G0                 | [9e347f10ee](https://linux-hardware.org/?probe=9e347f10ee) | Dec 12, 2020 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [dbfe4f7f45](https://linux-hardware.org/?probe=dbfe4f7f45) | Dec 12, 2020 |
| I-Life Dig... | ZED AIR PRO                 | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Medion        | E6228                       | [c9781fc6c2](https://linux-hardware.org/?probe=c9781fc6c2) | Dec 11, 2020 |
| Medion        | E6228                       | [dffd73069b](https://linux-hardware.org/?probe=dffd73069b) | Dec 11, 2020 |
| Apple         | MacBookAir3,2               | [da600a761d](https://linux-hardware.org/?probe=da600a761d) | Dec 10, 2020 |
| HP            | 15                          | [350e3446db](https://linux-hardware.org/?probe=350e3446db) | Dec 10, 2020 |
| Acer          | Aspire 5630                 | [3833d0f90a](https://linux-hardware.org/?probe=3833d0f90a) | Dec 10, 2020 |
| Dell          | Inspiron 1521               | [8c9ebdaf0f](https://linux-hardware.org/?probe=8c9ebdaf0f) | Dec 10, 2020 |
| ASUSTek       | X550MJ                      | [66ed5909f8](https://linux-hardware.org/?probe=66ed5909f8) | Dec 10, 2020 |
| Alienware     | m15 R3                      | [78038bb251](https://linux-hardware.org/?probe=78038bb251) | Dec 09, 2020 |
| ASUSTek       | P2540UA                     | [318bce5e19](https://linux-hardware.org/?probe=318bce5e19) | Dec 09, 2020 |
| Acer          | Aspire 9300                 | [07a152f778](https://linux-hardware.org/?probe=07a152f778) | Dec 08, 2020 |
| Medion        | Akoya S4220 MD99660         | [b07a7e906e](https://linux-hardware.org/?probe=b07a7e906e) | Dec 07, 2020 |
| HP            | Pavilion dv7                | [b9d9d59b79](https://linux-hardware.org/?probe=b9d9d59b79) | Dec 04, 2020 |
| Dell          | Latitude E5440              | [c88b8d642b](https://linux-hardware.org/?probe=c88b8d642b) | Dec 04, 2020 |
| Dell          | Latitude E5440              | [4ff22fe0e6](https://linux-hardware.org/?probe=4ff22fe0e6) | Dec 04, 2020 |
| Acer          | Aspire 5630                 | [ce8aa59be7](https://linux-hardware.org/?probe=ce8aa59be7) | Dec 04, 2020 |
| Acer          | Aspire A315-21              | [6c9e7e4bad](https://linux-hardware.org/?probe=6c9e7e4bad) | Dec 03, 2020 |
| HP            | Pavilion ZV6100 (EK857EA... | [07c5d7ba93](https://linux-hardware.org/?probe=07c5d7ba93) | Dec 03, 2020 |
| HP            | Pavilion 15                 | [ac2be8ed07](https://linux-hardware.org/?probe=ac2be8ed07) | Dec 02, 2020 |
| Fujitsu       | STYLISTIC Q704              | [caa54ddfda](https://linux-hardware.org/?probe=caa54ddfda) | Dec 02, 2020 |
| Dell          | Inspiron 1545               | [368f2012de](https://linux-hardware.org/?probe=368f2012de) | Dec 02, 2020 |
| Acer          | Aspire A315-21              | [ac50d99982](https://linux-hardware.org/?probe=ac50d99982) | Dec 02, 2020 |
| Alienware     | m15 R3                      | [0ead98cec4](https://linux-hardware.org/?probe=0ead98cec4) | Dec 01, 2020 |
| Lenovo        | Z50-70 20354                | [a03742bc98](https://linux-hardware.org/?probe=a03742bc98) | Dec 01, 2020 |
| Lenovo        | Z50-70 20354                | [1703cc2678](https://linux-hardware.org/?probe=1703cc2678) | Dec 01, 2020 |
| Medion        | E6228                       | [ea3b2898fd](https://linux-hardware.org/?probe=ea3b2898fd) | Nov 30, 2020 |
| HP            | Pavilion ZV6100 (EK857EA... | [93b1f4cfd7](https://linux-hardware.org/?probe=93b1f4cfd7) | Nov 28, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [8b7bafb647](https://linux-hardware.org/?probe=8b7bafb647) | Nov 28, 2020 |
| Samsung       | N150P/N210P                 | [0c58a0472f](https://linux-hardware.org/?probe=0c58a0472f) | Nov 28, 2020 |
| HP            | EliteBook 8460p             | [c3ba6d54c1](https://linux-hardware.org/?probe=c3ba6d54c1) | Nov 27, 2020 |
| Dell          | Latitude 7480               | [550fab0637](https://linux-hardware.org/?probe=550fab0637) | Nov 26, 2020 |
| Notebook      | N150CU                      | [d72b191f9e](https://linux-hardware.org/?probe=d72b191f9e) | Nov 26, 2020 |
| Clevo         | P170HMx                     | [7fb9c2c988](https://linux-hardware.org/?probe=7fb9c2c988) | Nov 26, 2020 |
| HP            | 15                          | [8cae83f5f4](https://linux-hardware.org/?probe=8cae83f5f4) | Nov 26, 2020 |
| Dell          | Vostro 5470                 | [7f0e50a415](https://linux-hardware.org/?probe=7f0e50a415) | Nov 25, 2020 |
| Lenovo        | G580 2689NHG                | [98ea230530](https://linux-hardware.org/?probe=98ea230530) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| MSI           | GT70                        | [a1b226924c](https://linux-hardware.org/?probe=a1b226924c) | Nov 23, 2020 |
| Lenovo        | ThinkPad T400 2765TDG       | [eda69b4a56](https://linux-hardware.org/?probe=eda69b4a56) | Nov 22, 2020 |
| Acer          | Extensa 2519                | [515d8fccc9](https://linux-hardware.org/?probe=515d8fccc9) | Nov 22, 2020 |
| Acer          | Aspire E1-571G              | [49a53faaa4](https://linux-hardware.org/?probe=49a53faaa4) | Nov 22, 2020 |
| Acer          | Aspire VN7-793G             | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| ASUSTek       | 1215B                       | [ade349b4c4](https://linux-hardware.org/?probe=ade349b4c4) | Nov 22, 2020 |
| ASUSTek       | N752VX                      | [4bd973e49c](https://linux-hardware.org/?probe=4bd973e49c) | Nov 22, 2020 |
| Acer          | Aspire E3-111               | [4d3a6bbf1f](https://linux-hardware.org/?probe=4d3a6bbf1f) | Nov 21, 2020 |
| HP            | Pavilion 15                 | [3ac387736a](https://linux-hardware.org/?probe=3ac387736a) | Nov 21, 2020 |
| ASUSTek       | 1215B                       | [fac0ef4c3c](https://linux-hardware.org/?probe=fac0ef4c3c) | Nov 21, 2020 |
| HP            | Pavilion 15                 | [5fbf0650cf](https://linux-hardware.org/?probe=5fbf0650cf) | Nov 21, 2020 |
| Acer          | Aspire 7720                 | [27460225c6](https://linux-hardware.org/?probe=27460225c6) | Nov 21, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | [3c4541bbf8](https://linux-hardware.org/?probe=3c4541bbf8) | Nov 21, 2020 |
| Dell          | Inspiron 5490               | [e07e0b4e45](https://linux-hardware.org/?probe=e07e0b4e45) | Nov 20, 2020 |
| Acer          | Aspire 9300                 | [13f5a3ccc7](https://linux-hardware.org/?probe=13f5a3ccc7) | Nov 20, 2020 |
| HP            | Laptop 17-by0xxx            | [a4d5dd679f](https://linux-hardware.org/?probe=a4d5dd679f) | Nov 20, 2020 |
| HP            | Laptop 17-by0xxx            | [9f67caa394](https://linux-hardware.org/?probe=9f67caa394) | Nov 20, 2020 |
| Dell          | Latitude E6430              | [a1d7b0f9ab](https://linux-hardware.org/?probe=a1d7b0f9ab) | Nov 20, 2020 |
| HP            | EliteBook 840 G1            | [03c7c3bfc7](https://linux-hardware.org/?probe=03c7c3bfc7) | Nov 20, 2020 |
| HP            | EliteBook 840 G1            | [d46cf5e259](https://linux-hardware.org/?probe=d46cf5e259) | Nov 20, 2020 |
| Lenovo        | ThinkPad R61 8935WFB        | [b82d043b71](https://linux-hardware.org/?probe=b82d043b71) | Nov 18, 2020 |
| Toshiba       | Satellite C650D             | [630b2da17a](https://linux-hardware.org/?probe=630b2da17a) | Nov 18, 2020 |
| Acer          | Aspire E1-532G              | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| HP            | Pavilion 15                 | [853af87cc9](https://linux-hardware.org/?probe=853af87cc9) | Nov 18, 2020 |
| HP            | Pavilion 15                 | [ff48c24c41](https://linux-hardware.org/?probe=ff48c24c41) | Nov 18, 2020 |
| Acer          | Aspire 5745                 | [2bcfe42ea3](https://linux-hardware.org/?probe=2bcfe42ea3) | Nov 17, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [1095dc2ac3](https://linux-hardware.org/?probe=1095dc2ac3) | Nov 17, 2020 |
| HP            | Laptop 15-da0xxx            | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [a8aff7471b](https://linux-hardware.org/?probe=a8aff7471b) | Nov 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [8a88ea0405](https://linux-hardware.org/?probe=8a88ea0405) | Nov 16, 2020 |
| Acer          | Lugano M                    | [464da49516](https://linux-hardware.org/?probe=464da49516) | Nov 15, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Acer          | Aspire 3100                 | [a572cc3368](https://linux-hardware.org/?probe=a572cc3368) | Nov 15, 2020 |
| Dell          | Latitude 5480               | [ed7aa46a28](https://linux-hardware.org/?probe=ed7aa46a28) | Nov 15, 2020 |
| Dell          | Latitude 5480               | [6ac2d1d34a](https://linux-hardware.org/?probe=6ac2d1d34a) | Nov 15, 2020 |
| Fujitsu       | FMVA0803F                   | [c9a2921775](https://linux-hardware.org/?probe=c9a2921775) | Nov 14, 2020 |
| Lenovo        | ThinkPad T430s 23539MU      | [52b1f1d052](https://linux-hardware.org/?probe=52b1f1d052) | Nov 12, 2020 |
| Acer          | Ferrari IV                  | [88cfdbff04](https://linux-hardware.org/?probe=88cfdbff04) | Nov 11, 2020 |
| Dynabook      | PORTEGE X30L-G              | [0499612b59](https://linux-hardware.org/?probe=0499612b59) | Nov 10, 2020 |
| Medion        | WIM2220                     | [f9bd17f677](https://linux-hardware.org/?probe=f9bd17f677) | Nov 08, 2020 |
| Toshiba       | Satellite L750              | [12f811448a](https://linux-hardware.org/?probe=12f811448a) | Nov 08, 2020 |
| HP            | Notebook                    | [c3d389a569](https://linux-hardware.org/?probe=c3d389a569) | Nov 08, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [2fd2c8389d](https://linux-hardware.org/?probe=2fd2c8389d) | Nov 08, 2020 |
| Medion        | WIM2220                     | [e1f3023c5f](https://linux-hardware.org/?probe=e1f3023c5f) | Nov 07, 2020 |
| Medion        | Akoya S4220 MD99660         | [7f1c16bcda](https://linux-hardware.org/?probe=7f1c16bcda) | Nov 06, 2020 |
| Toshiba       | Satellite L750              | [44061b6a41](https://linux-hardware.org/?probe=44061b6a41) | Nov 05, 2020 |
| ASUSTek       | E203NA                      | [83f3bbfada](https://linux-hardware.org/?probe=83f3bbfada) | Nov 05, 2020 |
| HP            | EliteBook 2760p             | [d1cad27e6f](https://linux-hardware.org/?probe=d1cad27e6f) | Nov 05, 2020 |
| Dell          | Inspiron 3542               | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| Packard Be... | EasyNote ENTG81BA           | [554b898a54](https://linux-hardware.org/?probe=554b898a54) | Nov 04, 2020 |
| ASUSTek       | X205TAW                     | [56c7b66e60](https://linux-hardware.org/?probe=56c7b66e60) | Nov 04, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [5a8d4603be](https://linux-hardware.org/?probe=5a8d4603be) | Nov 03, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4f17218d86](https://linux-hardware.org/?probe=4f17218d86) | Nov 03, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| HP            | EliteBook 820 G3            | [563415fbf4](https://linux-hardware.org/?probe=563415fbf4) | Oct 31, 2020 |
| Notebook      | NL40_50CU                   | [4497b97240](https://linux-hardware.org/?probe=4497b97240) | Oct 31, 2020 |
| Medion        | Akoya S4220 MD99660         | [bb717a9e21](https://linux-hardware.org/?probe=bb717a9e21) | Oct 31, 2020 |
| Notebook      | N13_N140ZU                  | [9994e807e6](https://linux-hardware.org/?probe=9994e807e6) | Oct 30, 2020 |
| ASUSTek       | K56CB                       | [913a11339e](https://linux-hardware.org/?probe=913a11339e) | Oct 30, 2020 |
| HP            | Pavilion dv6500             | [121844b238](https://linux-hardware.org/?probe=121844b238) | Oct 28, 2020 |
| Lenovo        | G505s 20255                 | [178a94abbf](https://linux-hardware.org/?probe=178a94abbf) | Oct 26, 2020 |
| Packard Be... | EasyNote TS11HR             | [4a9c6cd2af](https://linux-hardware.org/?probe=4a9c6cd2af) | Oct 26, 2020 |
| Acer          | Extensa 5230                | [b9b92019bc](https://linux-hardware.org/?probe=b9b92019bc) | Oct 25, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Toshiba       | Satellite P50t-B-113        | [6c087ce8ea](https://linux-hardware.org/?probe=6c087ce8ea) | Oct 24, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d1cf725e54](https://linux-hardware.org/?probe=d1cf725e54) | Oct 24, 2020 |
| Lenovo        | ThinkPad X230 2325TRN       | [4ff5dbb2c4](https://linux-hardware.org/?probe=4ff5dbb2c4) | Oct 23, 2020 |
| Acer          | Aspire 5733Z                | [3ac448e0a6](https://linux-hardware.org/?probe=3ac448e0a6) | Oct 23, 2020 |
| Dell          | Vostro 3350                 | [88e849444f](https://linux-hardware.org/?probe=88e849444f) | Oct 22, 2020 |
| Fujitsu Si... | AMILO La1703                | [89eeb34dbc](https://linux-hardware.org/?probe=89eeb34dbc) | Oct 22, 2020 |
| Fujitsu Si... | AMILO La1703                | [bdee704ce9](https://linux-hardware.org/?probe=bdee704ce9) | Oct 22, 2020 |
| Lenovo        | ThinkPad X220 42919L5       | [730e9b72a8](https://linux-hardware.org/?probe=730e9b72a8) | Oct 21, 2020 |
| ASUSTek       | N552VW                      | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Acer          | Aspire A515-55              | [aea22ab01a](https://linux-hardware.org/?probe=aea22ab01a) | Oct 20, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [039517f9b1](https://linux-hardware.org/?probe=039517f9b1) | Oct 19, 2020 |
| MouseCompu... | NG-N-i5730                  | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| Fujitsu       | LIFEBOOK U904               | [72afc70aea](https://linux-hardware.org/?probe=72afc70aea) | Oct 19, 2020 |
| ASUSTek       | X550EA                      | [27074cf7ae](https://linux-hardware.org/?probe=27074cf7ae) | Oct 18, 2020 |
| Dell          | Inspiron N5110              | [fe557d9bf0](https://linux-hardware.org/?probe=fe557d9bf0) | Oct 18, 2020 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [f7a51ece15](https://linux-hardware.org/?probe=f7a51ece15) | Oct 16, 2020 |
| HP            | 655                         | [8d521629e4](https://linux-hardware.org/?probe=8d521629e4) | Oct 16, 2020 |
| Positivo      | Mobile                      | [211c5d812f](https://linux-hardware.org/?probe=211c5d812f) | Oct 16, 2020 |
| Dynabook      | PORTEGE X30L-G              | [00ad2832f0](https://linux-hardware.org/?probe=00ad2832f0) | Oct 15, 2020 |
| HP            | Pavilion 15                 | [ded3ec96e6](https://linux-hardware.org/?probe=ded3ec96e6) | Oct 15, 2020 |
| HP            | Pavilion dv6                | [aa66ea4d86](https://linux-hardware.org/?probe=aa66ea4d86) | Oct 15, 2020 |
| Positivo      | Mobile                      | [bcbe9b6892](https://linux-hardware.org/?probe=bcbe9b6892) | Oct 14, 2020 |
| Lenovo        | G50-30 80G0                 | [b12687c62b](https://linux-hardware.org/?probe=b12687c62b) | Oct 12, 2020 |
| ASUSTek       | X540SA                      | [6694a38429](https://linux-hardware.org/?probe=6694a38429) | Oct 11, 2020 |
| OEGStone      | C4100/C5100                 | [b3a5e6dbc7](https://linux-hardware.org/?probe=b3a5e6dbc7) | Oct 11, 2020 |
| HP            | Compaq Presario CQ60        | [57c0796f7d](https://linux-hardware.org/?probe=57c0796f7d) | Oct 10, 2020 |
| HP            | Compaq Presario CQ60        | [ac0d496c41](https://linux-hardware.org/?probe=ac0d496c41) | Oct 10, 2020 |
| HP            | ENVY m7 Notebook            | [c3d45b395f](https://linux-hardware.org/?probe=c3d45b395f) | Oct 10, 2020 |
| HP            | Laptop 15-bs1xx             | [44119852e3](https://linux-hardware.org/?probe=44119852e3) | Oct 09, 2020 |
| Apple         | MacBookPro6,2               | [90be6b4795](https://linux-hardware.org/?probe=90be6b4795) | Oct 09, 2020 |
| ASUSTek       | K53E                        | [57d6280b99](https://linux-hardware.org/?probe=57d6280b99) | Oct 09, 2020 |
| HP            | Compaq 6510b                | [cf190a85ea](https://linux-hardware.org/?probe=cf190a85ea) | Oct 08, 2020 |
| Lenovo        | ThinkPad X220 42918F6       | [6a427182ad](https://linux-hardware.org/?probe=6a427182ad) | Oct 07, 2020 |
| ASUSTek       | X540SA                      | [b65be0bf44](https://linux-hardware.org/?probe=b65be0bf44) | Oct 07, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| HP            | Notebook                    | [5152b94329](https://linux-hardware.org/?probe=5152b94329) | Oct 07, 2020 |
| HP            | G72                         | [9ffd6f9800](https://linux-hardware.org/?probe=9ffd6f9800) | Oct 06, 2020 |
| Dell          | Latitude E6330              | [3eeb1d435a](https://linux-hardware.org/?probe=3eeb1d435a) | Oct 06, 2020 |
| Acer          | Aspire 7720                 | [37ee142080](https://linux-hardware.org/?probe=37ee142080) | Oct 05, 2020 |
| Toshiba       | STI NA 1402                 | [563e501126](https://linux-hardware.org/?probe=563e501126) | Oct 05, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| HP            | Laptop 15-bs1xx             | [55c36c93a4](https://linux-hardware.org/?probe=55c36c93a4) | Oct 03, 2020 |
| HP            | G62                         | [549f82b3ab](https://linux-hardware.org/?probe=549f82b3ab) | Oct 03, 2020 |
| HP            | G62                         | [d5f754a79b](https://linux-hardware.org/?probe=d5f754a79b) | Oct 03, 2020 |
| Toshiba       | STI NA 1402                 | [06bd99a96d](https://linux-hardware.org/?probe=06bd99a96d) | Oct 03, 2020 |
| HP            | EliteBook 8440p             | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | Pavilion g6                 | [877d5394f3](https://linux-hardware.org/?probe=877d5394f3) | Oct 02, 2020 |
| Sony          | VGN-AW11M_H                 | [93eb90689f](https://linux-hardware.org/?probe=93eb90689f) | Oct 02, 2020 |
| ASUSTek       | 1001P                       | [2d569d7877](https://linux-hardware.org/?probe=2d569d7877) | Sep 30, 2020 |
| HP            | Pavilion dv6                | [e579b3a47a](https://linux-hardware.org/?probe=e579b3a47a) | Sep 30, 2020 |
| ASUSTek       | K53E                        | [57b9033911](https://linux-hardware.org/?probe=57b9033911) | Sep 30, 2020 |
| Schenker      | VIA_14_SVI14E20             | [431de74e18](https://linux-hardware.org/?probe=431de74e18) | Sep 29, 2020 |
| HP            | Pavilion tx1000             | [45aaad469b](https://linux-hardware.org/?probe=45aaad469b) | Sep 29, 2020 |
| Acer          | Aspire SW3-013              | [40c00a9cd5](https://linux-hardware.org/?probe=40c00a9cd5) | Sep 27, 2020 |
| Acer          | Aspire SW3-013              | [2f3245e837](https://linux-hardware.org/?probe=2f3245e837) | Sep 27, 2020 |
| Acer          | Aspire SW3-013              | [271ab121ee](https://linux-hardware.org/?probe=271ab121ee) | Sep 27, 2020 |
| ASUSTek       | K53E                        | [04740b7dad](https://linux-hardware.org/?probe=04740b7dad) | Sep 26, 2020 |
| Dell          | Inspiron 3558               | [853e25d0f9](https://linux-hardware.org/?probe=853e25d0f9) | Sep 26, 2020 |
| Dell          | Inspiron 3558               | [175875ac7b](https://linux-hardware.org/?probe=175875ac7b) | Sep 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a6630164b8](https://linux-hardware.org/?probe=a6630164b8) | Sep 25, 2020 |
| Itautec       | W7655                       | [5878935978](https://linux-hardware.org/?probe=5878935978) | Sep 25, 2020 |
| Acer          | Extensa 5630                | [c405a4cab9](https://linux-hardware.org/?probe=c405a4cab9) | Sep 24, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6e5da39670](https://linux-hardware.org/?probe=6e5da39670) | Sep 24, 2020 |
| Notebook      | W65_67SJ                    | [da03090968](https://linux-hardware.org/?probe=da03090968) | Sep 23, 2020 |
| Lenovo        | S206                        | [b4d2c25f69](https://linux-hardware.org/?probe=b4d2c25f69) | Sep 22, 2020 |
| ASUSTek       | N752VX                      | [357b0ba973](https://linux-hardware.org/?probe=357b0ba973) | Sep 22, 2020 |
| HP            | Compaq 6510b                | [9b9a4b4614](https://linux-hardware.org/?probe=9b9a4b4614) | Sep 22, 2020 |
| Dell          | XPS L701X                   | [e825e50fce](https://linux-hardware.org/?probe=e825e50fce) | Sep 21, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e66100f134](https://linux-hardware.org/?probe=e66100f134) | Sep 21, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [f0cc956336](https://linux-hardware.org/?probe=f0cc956336) | Sep 21, 2020 |
| Dell          | Latitude E4300              | [b80743fa09](https://linux-hardware.org/?probe=b80743fa09) | Sep 21, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [3feb39014a](https://linux-hardware.org/?probe=3feb39014a) | Sep 20, 2020 |
| ASUSTek       | F5VL                        | [f385221573](https://linux-hardware.org/?probe=f385221573) | Sep 20, 2020 |
| HP            | ProBook 4540s               | [9423eb5acb](https://linux-hardware.org/?probe=9423eb5acb) | Sep 20, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [9bb6aefa2c](https://linux-hardware.org/?probe=9bb6aefa2c) | Sep 20, 2020 |
| HP            | Compaq 6510b                | [3487aab3a6](https://linux-hardware.org/?probe=3487aab3a6) | Sep 20, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [66d1e7ec35](https://linux-hardware.org/?probe=66d1e7ec35) | Sep 20, 2020 |
| Dell          | Latitude E6440              | [f58584fa2c](https://linux-hardware.org/?probe=f58584fa2c) | Sep 20, 2020 |
| Toshiba       | PORTEGE R930                | [bfbb7fc847](https://linux-hardware.org/?probe=bfbb7fc847) | Sep 19, 2020 |
| Lenovo        | ThinkPad T590 20N4004UMB    | [be3d2c8855](https://linux-hardware.org/?probe=be3d2c8855) | Sep 19, 2020 |
| HP            | Compaq 6510b                | [b7382d2141](https://linux-hardware.org/?probe=b7382d2141) | Sep 19, 2020 |
| Acer          | Aspire A515-44G             | [cf221f1b18](https://linux-hardware.org/?probe=cf221f1b18) | Sep 19, 2020 |
| HP            | ProBook 6550b               | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| HP            | Pavilion g7                 | [7a81ae667b](https://linux-hardware.org/?probe=7a81ae667b) | Sep 19, 2020 |
| HP            | Pavilion dv6700             | [e514981e11](https://linux-hardware.org/?probe=e514981e11) | Sep 19, 2020 |
| HP            | Pavilion g7                 | [767609618f](https://linux-hardware.org/?probe=767609618f) | Sep 19, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [f5941e6787](https://linux-hardware.org/?probe=f5941e6787) | Sep 17, 2020 |
| Dell          | Vostro 3550                 | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [d4d25586c0](https://linux-hardware.org/?probe=d4d25586c0) | Sep 16, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| Lenovo        | ThinkPad X220 42918F6       | [bea802e1b6](https://linux-hardware.org/?probe=bea802e1b6) | Sep 16, 2020 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [8178cca0f9](https://linux-hardware.org/?probe=8178cca0f9) | Sep 16, 2020 |
| Lenovo        | ThinkPad X220 42918F6       | [4693e5b345](https://linux-hardware.org/?probe=4693e5b345) | Sep 15, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [38af2c7f94](https://linux-hardware.org/?probe=38af2c7f94) | Sep 15, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | [d2d1e581b0](https://linux-hardware.org/?probe=d2d1e581b0) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40bde8d392](https://linux-hardware.org/?probe=40bde8d392) | Sep 11, 2020 |
| Dell          | Latitude E5500              | [eb1361e23c](https://linux-hardware.org/?probe=eb1361e23c) | Sep 11, 2020 |
| Acer          | Swift SF314-42              | [76836fadd2](https://linux-hardware.org/?probe=76836fadd2) | Sep 10, 2020 |
| HP            | ENVY m7 Notebook            | [6f870ff739](https://linux-hardware.org/?probe=6f870ff739) | Sep 10, 2020 |
| Positivo      | S14SL01                     | [3effdfe886](https://linux-hardware.org/?probe=3effdfe886) | Sep 09, 2020 |
| Google        | Auron_Yuna                  | [a4d1cd047b](https://linux-hardware.org/?probe=a4d1cd047b) | Sep 07, 2020 |
| Google        | Auron_Yuna                  | [676f8c83ec](https://linux-hardware.org/?probe=676f8c83ec) | Sep 07, 2020 |
| Dell          | Inspiron 7520               | [c234184be5](https://linux-hardware.org/?probe=c234184be5) | Sep 07, 2020 |
| ASUSTek       | X205TA                      | [84a01a41b1](https://linux-hardware.org/?probe=84a01a41b1) | Sep 06, 2020 |
| HP            | Compaq Presario CQ60        | [5a10409a8a](https://linux-hardware.org/?probe=5a10409a8a) | Sep 06, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| Lenovo        | G780                        | [386777b221](https://linux-hardware.org/?probe=386777b221) | Sep 05, 2020 |
| ASUSTek       | X205TA                      | [57a46b9db8](https://linux-hardware.org/?probe=57a46b9db8) | Sep 05, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| HP            | Compaq 6730b (KE717AV)      | [026b6d0abc](https://linux-hardware.org/?probe=026b6d0abc) | Sep 04, 2020 |
| Lenovo        | ThinkPad T480s 20L7001YU... | [a73e5916b6](https://linux-hardware.org/?probe=a73e5916b6) | Sep 04, 2020 |
| HP            | Pavilion g7                 | [7c130ac6c9](https://linux-hardware.org/?probe=7c130ac6c9) | Sep 04, 2020 |
| Fujitsu       | LIFEBOOK S762               | [7d6b9f9f5c](https://linux-hardware.org/?probe=7d6b9f9f5c) | Sep 04, 2020 |
| Compaq        | Presario CQ-23              | [ab765182a8](https://linux-hardware.org/?probe=ab765182a8) | Sep 02, 2020 |
| Lenovo        | IdeaPad S300 9803           | [ca3bc94ba8](https://linux-hardware.org/?probe=ca3bc94ba8) | Sep 01, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [f0e36418ea](https://linux-hardware.org/?probe=f0e36418ea) | Sep 01, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d038b4c40e](https://linux-hardware.org/?probe=d038b4c40e) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | [64ba8fde9d](https://linux-hardware.org/?probe=64ba8fde9d) | Aug 31, 2020 |
| Toshiba       | PORTEGE R930                | [b37b0d860d](https://linux-hardware.org/?probe=b37b0d860d) | Aug 31, 2020 |
| Toshiba       | Satellite Pro P200          | [0490fe7f0a](https://linux-hardware.org/?probe=0490fe7f0a) | Aug 30, 2020 |
| Toshiba       | Satellite Pro P200          | [ff2e799a8c](https://linux-hardware.org/?probe=ff2e799a8c) | Aug 30, 2020 |
| Dell          | Vostro V130                 | [b117f2985f](https://linux-hardware.org/?probe=b117f2985f) | Aug 30, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| HP            | ProBook 4540s               | [615e7d9dfa](https://linux-hardware.org/?probe=615e7d9dfa) | Aug 29, 2020 |
| Lenovo        | 3000 N500 423374G           | [2fcea8b22c](https://linux-hardware.org/?probe=2fcea8b22c) | Aug 28, 2020 |
| Lenovo        | 3000 N500 423374G           | [e7ae81e74c](https://linux-hardware.org/?probe=e7ae81e74c) | Aug 28, 2020 |
| Dell          | Inspiron 1525               | [a5642b7562](https://linux-hardware.org/?probe=a5642b7562) | Aug 28, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [c3ce30ea06](https://linux-hardware.org/?probe=c3ce30ea06) | Aug 27, 2020 |
| ASUSTek       | Zephyrus M15 GU502LU_GU5... | [eecce44ac2](https://linux-hardware.org/?probe=eecce44ac2) | Aug 27, 2020 |
| Dell          | Inspiron 7720               | [9f2a48a228](https://linux-hardware.org/?probe=9f2a48a228) | Aug 25, 2020 |
| Acer          | Aspire A315-42              | [5bad10f24c](https://linux-hardware.org/?probe=5bad10f24c) | Aug 24, 2020 |
| Fujitsu       | STYLISTIC Q704              | [dbabe28124](https://linux-hardware.org/?probe=dbabe28124) | Aug 24, 2020 |
| Acer          | Sabine Platform             | [6ce3231440](https://linux-hardware.org/?probe=6ce3231440) | Aug 23, 2020 |
| HP            | HDX 18                      | [14f2f4a2e9](https://linux-hardware.org/?probe=14f2f4a2e9) | Aug 23, 2020 |
| HP            | EliteBook 8570p             | [d54dcde59f](https://linux-hardware.org/?probe=d54dcde59f) | Aug 23, 2020 |
| Dell          | Inspiron 1525               | [25ba90f7f1](https://linux-hardware.org/?probe=25ba90f7f1) | Aug 23, 2020 |
| HP            | ProBook 4540s               | [d802ce490d](https://linux-hardware.org/?probe=d802ce490d) | Aug 23, 2020 |
| Acer          | Nitro AN515-43              | [4cf98e3cbe](https://linux-hardware.org/?probe=4cf98e3cbe) | Aug 22, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [7286ec156e](https://linux-hardware.org/?probe=7286ec156e) | Aug 21, 2020 |
| Samsung       | RF511/RF411/RF711           | [1e45d060b4](https://linux-hardware.org/?probe=1e45d060b4) | Aug 21, 2020 |
| HP            | Compaq 6735s                | [529e1a4543](https://linux-hardware.org/?probe=529e1a4543) | Aug 21, 2020 |
| HP            | Laptop 15-dw0xxx            | [edec3485d0](https://linux-hardware.org/?probe=edec3485d0) | Aug 21, 2020 |
| LG Electro... | P420-N.AE21G                | [6da1523a4e](https://linux-hardware.org/?probe=6da1523a4e) | Aug 21, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [f3b36c38ff](https://linux-hardware.org/?probe=f3b36c38ff) | Aug 19, 2020 |
| ASUSTek       | 1001P                       | [45fc7c3afb](https://linux-hardware.org/?probe=45fc7c3afb) | Aug 19, 2020 |
| HP            | Presario CQ57               | [618315e687](https://linux-hardware.org/?probe=618315e687) | Aug 19, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | [85145bb93c](https://linux-hardware.org/?probe=85145bb93c) | Aug 18, 2020 |
| HP            | Pavilion g6                 | [5e19a0ff8c](https://linux-hardware.org/?probe=5e19a0ff8c) | Aug 17, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| Positivo      | W253BUQ                     | [7c4e62a873](https://linux-hardware.org/?probe=7c4e62a873) | Aug 16, 2020 |
| Acer          | Aspire 4732Z                | [de0e2d7288](https://linux-hardware.org/?probe=de0e2d7288) | Aug 15, 2020 |
| Toshiba       | Satellite C650              | [4d6e3b95a0](https://linux-hardware.org/?probe=4d6e3b95a0) | Aug 15, 2020 |
| ASUSTek       | ZenBook UX434FAC_UX434FA    | [f644ab6ee2](https://linux-hardware.org/?probe=f644ab6ee2) | Aug 14, 2020 |
| Dell          | Latitude E5500              | [360533c325](https://linux-hardware.org/?probe=360533c325) | Aug 14, 2020 |
| MSI           | PR601/VR603                 | [fac6732273](https://linux-hardware.org/?probe=fac6732273) | Aug 14, 2020 |
| HP            | EliteBook 840 G1            | [998c9d10e0](https://linux-hardware.org/?probe=998c9d10e0) | Aug 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [4dfd05b279](https://linux-hardware.org/?probe=4dfd05b279) | Aug 13, 2020 |
| Dell          | Latitude E6430              | [f5187f4aef](https://linux-hardware.org/?probe=f5187f4aef) | Aug 12, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [3adcca1e19](https://linux-hardware.org/?probe=3adcca1e19) | Aug 11, 2020 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [6633d497ea](https://linux-hardware.org/?probe=6633d497ea) | Aug 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [a48c2316a3](https://linux-hardware.org/?probe=a48c2316a3) | Aug 09, 2020 |
| Toshiba       | Satellite C850D-11F         | [1a4440eb8a](https://linux-hardware.org/?probe=1a4440eb8a) | Aug 08, 2020 |
| Toshiba       | Satellite C850D-11F         | [0c919133d7](https://linux-hardware.org/?probe=0c919133d7) | Aug 08, 2020 |
| Acer          | Sabine Platform             | [dbbfd9b9be](https://linux-hardware.org/?probe=dbbfd9b9be) | Aug 07, 2020 |
| Toshiba       | Satellite C670D-11K         | [3c59ce7fed](https://linux-hardware.org/?probe=3c59ce7fed) | Aug 07, 2020 |
| Digibras      | NH4CU03                     | [6d195fc501](https://linux-hardware.org/?probe=6d195fc501) | Aug 06, 2020 |
| Digibras      | NH4CU03                     | [57b132081d](https://linux-hardware.org/?probe=57b132081d) | Aug 06, 2020 |
| Apple         | MacBook4,1                  | [a5dbd582ed](https://linux-hardware.org/?probe=a5dbd582ed) | Aug 04, 2020 |
| Dell          | Latitude D630               | [0505fb0e7c](https://linux-hardware.org/?probe=0505fb0e7c) | Aug 04, 2020 |
| HP            | Presario C700               | [db954beda7](https://linux-hardware.org/?probe=db954beda7) | Aug 04, 2020 |
| Apple         | MacBookPro10,1              | [9c24d40f13](https://linux-hardware.org/?probe=9c24d40f13) | Aug 03, 2020 |
| Fujitsu       | STYLISTIC Q704              | [52a7e36042](https://linux-hardware.org/?probe=52a7e36042) | Aug 02, 2020 |
| HP            | EliteBook 840 G3            | [42ee50d658](https://linux-hardware.org/?probe=42ee50d658) | Aug 02, 2020 |
| HP            | 250 G6 Notebook PC          | [9b0eb8f018](https://linux-hardware.org/?probe=9b0eb8f018) | Aug 01, 2020 |
| Acer          | Aspire 7720                 | [99c73340ba](https://linux-hardware.org/?probe=99c73340ba) | Jul 31, 2020 |
| HP            | 15                          | [337dcd22df](https://linux-hardware.org/?probe=337dcd22df) | Jul 30, 2020 |
| HP            | G42                         | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| Samsung       | RC410/RC510/RC710           | [ff0e1e29b9](https://linux-hardware.org/?probe=ff0e1e29b9) | Jul 28, 2020 |
| Positivo      | C14RV01                     | [0d536d2855](https://linux-hardware.org/?probe=0d536d2855) | Jul 28, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1020cd5f83](https://linux-hardware.org/?probe=1020cd5f83) | Jul 28, 2020 |
| HP            | Presario C700               | [d03a7b9127](https://linux-hardware.org/?probe=d03a7b9127) | Jul 28, 2020 |
| HP            | Presario C700               | [b6fdfa5ae6](https://linux-hardware.org/?probe=b6fdfa5ae6) | Jul 28, 2020 |
| HP            | Compaq 6535b                | [235208ffe1](https://linux-hardware.org/?probe=235208ffe1) | Jul 27, 2020 |
| Google        | Liara                       | [93778f0294](https://linux-hardware.org/?probe=93778f0294) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [4976009eba](https://linux-hardware.org/?probe=4976009eba) | Jul 26, 2020 |
| HP            | Pavilion dv4                | [ec2bd27559](https://linux-hardware.org/?probe=ec2bd27559) | Jul 25, 2020 |
| Acer          | Nitro AN515-51              | [9c0b965190](https://linux-hardware.org/?probe=9c0b965190) | Jul 25, 2020 |
| Multilaser    | PC231                       | [348ab5d244](https://linux-hardware.org/?probe=348ab5d244) | Jul 24, 2020 |
| Acer          | Sabine Platform             | [043e933c74](https://linux-hardware.org/?probe=043e933c74) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| Positivo      | N1103                       | [552c0c0605](https://linux-hardware.org/?probe=552c0c0605) | Jul 24, 2020 |
| HP            | Presario C700               | [afb4c089f1](https://linux-hardware.org/?probe=afb4c089f1) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | [9818a6e8d5](https://linux-hardware.org/?probe=9818a6e8d5) | Jul 24, 2020 |
| Lenovo        | G460 0677                   | [d22e5d2715](https://linux-hardware.org/?probe=d22e5d2715) | Jul 24, 2020 |
| ASUSTek       | X550CA                      | [24d8f4daa8](https://linux-hardware.org/?probe=24d8f4daa8) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | [a80a673e14](https://linux-hardware.org/?probe=a80a673e14) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [8973f15f3c](https://linux-hardware.org/?probe=8973f15f3c) | Jul 24, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [a308ee2a62](https://linux-hardware.org/?probe=a308ee2a62) | Jul 24, 2020 |
| Lenovo        | G400s VILG1                 | [0c8815e6d9](https://linux-hardware.org/?probe=0c8815e6d9) | Jul 24, 2020 |
| Lenovo        | G460 0677                   | [c43dd028ea](https://linux-hardware.org/?probe=c43dd028ea) | Jul 23, 2020 |
| HP            | Presario CQ56               | [93cc43e52e](https://linux-hardware.org/?probe=93cc43e52e) | Jul 23, 2020 |
| HP            | Presario CQ56               | [5eb29c4d14](https://linux-hardware.org/?probe=5eb29c4d14) | Jul 23, 2020 |
| HP            | Notebook                    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [644eeb1f68](https://linux-hardware.org/?probe=644eeb1f68) | Jul 22, 2020 |
| Dell          | Latitude E6520              | [de12c01408](https://linux-hardware.org/?probe=de12c01408) | Jul 21, 2020 |
| HP            | Pavilion DV9000 (RY715EA... | [b3c779f8be](https://linux-hardware.org/?probe=b3c779f8be) | Jul 21, 2020 |
| Toshiba       | Satellite C650              | [6d522083a5](https://linux-hardware.org/?probe=6d522083a5) | Jul 20, 2020 |
| HP            | Compaq Presario CQ60        | [79c11f4f35](https://linux-hardware.org/?probe=79c11f4f35) | Jul 19, 2020 |
| Google        | Liara                       | [c131819f50](https://linux-hardware.org/?probe=c131819f50) | Jul 18, 2020 |
| MSI           | CX61 2QF                    | [47f6147b6e](https://linux-hardware.org/?probe=47f6147b6e) | Jul 18, 2020 |
| ASUSTek       | X201EP                      | [d45bd20693](https://linux-hardware.org/?probe=d45bd20693) | Jul 18, 2020 |
| Lenovo        | ThinkPad W530 24479Q7       | [f4ce1f339d](https://linux-hardware.org/?probe=f4ce1f339d) | Jul 17, 2020 |
| HP            | Pavilion 15                 | [1b5882adc2](https://linux-hardware.org/?probe=1b5882adc2) | Jul 17, 2020 |
| Dell          | Vostro 3360                 | [22cf25df0d](https://linux-hardware.org/?probe=22cf25df0d) | Jul 17, 2020 |
| Toshiba       | Satellite U305              | [a08a02467a](https://linux-hardware.org/?probe=a08a02467a) | Jul 16, 2020 |
| Intel         | Crestline & ICH8M Chipse... | [acc1fde47a](https://linux-hardware.org/?probe=acc1fde47a) | Jul 15, 2020 |
| Apple         | MacBook7,1                  | [4a2c480573](https://linux-hardware.org/?probe=4a2c480573) | Jul 14, 2020 |
| Toshiba       | Satellite C650              | [f0caedbdd0](https://linux-hardware.org/?probe=f0caedbdd0) | Jul 14, 2020 |
| Dell          | Latitude D630               | [5347cbcf05](https://linux-hardware.org/?probe=5347cbcf05) | Jul 14, 2020 |
| Acer          | Aspire 5750G                | [0f840e8f40](https://linux-hardware.org/?probe=0f840e8f40) | Jul 13, 2020 |
| Acer          | Aspire 5750G                | [c77dba0448](https://linux-hardware.org/?probe=c77dba0448) | Jul 13, 2020 |
| Dell          | Latitude E6520              | [a339b5cccc](https://linux-hardware.org/?probe=a339b5cccc) | Jul 13, 2020 |
| Acer          | AOD257                      | [eb1b54bd86](https://linux-hardware.org/?probe=eb1b54bd86) | Jul 12, 2020 |
| ASUSTek       | 1005PE                      | [0f179f8719](https://linux-hardware.org/?probe=0f179f8719) | Jul 12, 2020 |
| HP            | 250 G7 Notebook PC          | [d78422bc37](https://linux-hardware.org/?probe=d78422bc37) | Jul 11, 2020 |
| Lenovo        | G460 0677                   | [c5a0c92162](https://linux-hardware.org/?probe=c5a0c92162) | Jul 11, 2020 |
| Dell          | Latitude D630               | [77fa436b56](https://linux-hardware.org/?probe=77fa436b56) | Jul 11, 2020 |
| Apple         | MacBook7,1                  | [214192cc63](https://linux-hardware.org/?probe=214192cc63) | Jul 10, 2020 |
| HP            | Pavilion Notebook           | [fdd8fdf7b1](https://linux-hardware.org/?probe=fdd8fdf7b1) | Jul 09, 2020 |
| Dell          | Latitude E7270              | [a4e36dcb8e](https://linux-hardware.org/?probe=a4e36dcb8e) | Jul 09, 2020 |
| Toshiba       | Satellite A100              | [6c87fe867b](https://linux-hardware.org/?probe=6c87fe867b) | Jul 07, 2020 |
| Dell          | Latitude E7270              | [360112322b](https://linux-hardware.org/?probe=360112322b) | Jul 07, 2020 |
| Dell          | Inspiron 5559               | [7faeeccd7e](https://linux-hardware.org/?probe=7faeeccd7e) | Jul 07, 2020 |
| HP            | G62                         | [ba604ce99d](https://linux-hardware.org/?probe=ba604ce99d) | Jul 06, 2020 |
| Acer          | Aspire ES1-512              | [35d93bfedf](https://linux-hardware.org/?probe=35d93bfedf) | Jul 04, 2020 |
| Dell          | Latitude E6420              | [f3a048144b](https://linux-hardware.org/?probe=f3a048144b) | Jul 04, 2020 |
| Lenovo        | ThinkPad L470 20J4002FMH    | [f5262493e1](https://linux-hardware.org/?probe=f5262493e1) | Jul 03, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [e37c3a0ba5](https://linux-hardware.org/?probe=e37c3a0ba5) | Jul 03, 2020 |
| HP            | Pavilion g4                 | [21261aa7d1](https://linux-hardware.org/?probe=21261aa7d1) | Jul 01, 2020 |
| Toshiba       | PORTEGE R30-A               | [2c94b496ce](https://linux-hardware.org/?probe=2c94b496ce) | Jun 29, 2020 |
| Toshiba       | Satellite C870D-11T         | [dc5b9f0738](https://linux-hardware.org/?probe=dc5b9f0738) | Jun 28, 2020 |
| HP            | ProBook 650 G1              | [51b7fb4eed](https://linux-hardware.org/?probe=51b7fb4eed) | Jun 28, 2020 |
| HP            | ProBook 6460b               | [f1ab7d5b8c](https://linux-hardware.org/?probe=f1ab7d5b8c) | Jun 28, 2020 |
| ASUSTek       | S551LB                      | [0a8aa9f0da](https://linux-hardware.org/?probe=0a8aa9f0da) | Jun 28, 2020 |
| ASUSTek       | S551LB                      | [667945db63](https://linux-hardware.org/?probe=667945db63) | Jun 28, 2020 |
| Intel         | HURONRIVER                  | [e748e1f03d](https://linux-hardware.org/?probe=e748e1f03d) | Jun 28, 2020 |
| Intel         | HURONRIVER                  | [319de108aa](https://linux-hardware.org/?probe=319de108aa) | Jun 28, 2020 |
| CAPTIVA       | Unknown                     | [a05874290f](https://linux-hardware.org/?probe=a05874290f) | Jun 26, 2020 |
| Unknown       | T3 MRD                      | [e713023e67](https://linux-hardware.org/?probe=e713023e67) | Jun 25, 2020 |
| Dell          | Studio 1535                 | [effa9a2180](https://linux-hardware.org/?probe=effa9a2180) | Jun 25, 2020 |
| HP            | 14                          | [4de0326f3b](https://linux-hardware.org/?probe=4de0326f3b) | Jun 24, 2020 |
| Dell          | Latitude E5510              | [f00a0fb5c0](https://linux-hardware.org/?probe=f00a0fb5c0) | Jun 24, 2020 |
| LIVEFAN       | Unknown                     | [e2374d060c](https://linux-hardware.org/?probe=e2374d060c) | Jun 23, 2020 |
| Dell          | Inspiron 5423               | [cf43eb493f](https://linux-hardware.org/?probe=cf43eb493f) | Jun 22, 2020 |
| HP            | 15                          | [aa5d7e28d3](https://linux-hardware.org/?probe=aa5d7e28d3) | Jun 21, 2020 |
| Dell          | Inspiron 11-3162            | [1591961f13](https://linux-hardware.org/?probe=1591961f13) | Jun 21, 2020 |
| HP            | EliteBook 745 G2            | [9e3d4f423a](https://linux-hardware.org/?probe=9e3d4f423a) | Jun 21, 2020 |
| HP            | EliteBook 745 G2            | [07027013e9](https://linux-hardware.org/?probe=07027013e9) | Jun 21, 2020 |
| Dell          | Latitude E6430              | [742518866d](https://linux-hardware.org/?probe=742518866d) | Jun 21, 2020 |
| Dell          | Latitude E6430              | [a3708e4a03](https://linux-hardware.org/?probe=a3708e4a03) | Jun 21, 2020 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [31741c6aa1](https://linux-hardware.org/?probe=31741c6aa1) | Jun 21, 2020 |
| MSI           | PR601/VR603                 | [76f39989ef](https://linux-hardware.org/?probe=76f39989ef) | Jun 21, 2020 |
| Unknown       | T3 MRD                      | [f6a1ada662](https://linux-hardware.org/?probe=f6a1ada662) | Jun 18, 2020 |
| Unknown       | T3 MRD                      | [998b0f0d52](https://linux-hardware.org/?probe=998b0f0d52) | Jun 18, 2020 |
| HP            | ProBook 6460b               | [4b0b074c7d](https://linux-hardware.org/?probe=4b0b074c7d) | Jun 17, 2020 |
| Dell          | Studio 1535                 | [dc7f250d15](https://linux-hardware.org/?probe=dc7f250d15) | Jun 17, 2020 |
| MSI           | PR601/VR603                 | [5d37279473](https://linux-hardware.org/?probe=5d37279473) | Jun 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0293417e94](https://linux-hardware.org/?probe=0293417e94) | Jun 17, 2020 |
| Dell          | Inspiron 3582               | [9ce1f0b968](https://linux-hardware.org/?probe=9ce1f0b968) | Jun 16, 2020 |
| ASUSTek       | F5RL                        | [6a1a56701c](https://linux-hardware.org/?probe=6a1a56701c) | Jun 15, 2020 |
| Acer          | Swift SF314-57G             | [3e717eb1c2](https://linux-hardware.org/?probe=3e717eb1c2) | Jun 14, 2020 |
| Lenovo        | 3000 V200 076433G           | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| Dell          | G3 3590                     | [f9e9753ae2](https://linux-hardware.org/?probe=f9e9753ae2) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Dell          | G3 3590                     | [d4035154be](https://linux-hardware.org/?probe=d4035154be) | Jun 12, 2020 |
| Dell          | Latitude D630               | [93500e7aa5](https://linux-hardware.org/?probe=93500e7aa5) | Jun 11, 2020 |
| HP            | ENVY m7 Notebook            | [7407e48fab](https://linux-hardware.org/?probe=7407e48fab) | Jun 11, 2020 |
| Acer          | Aspire ES1-523              | [ebd72429b9](https://linux-hardware.org/?probe=ebd72429b9) | Jun 10, 2020 |
| Samsung       | 270E5G/270E5U               | [36bfc8f6c5](https://linux-hardware.org/?probe=36bfc8f6c5) | Jun 10, 2020 |
| HP            | ENVY m7 Notebook            | [3927770241](https://linux-hardware.org/?probe=3927770241) | Jun 10, 2020 |
| Toshiba       | TECRA R940                  | [3c4e99be53](https://linux-hardware.org/?probe=3c4e99be53) | Jun 10, 2020 |
| Toshiba       | TECRA R940                  | [feceb292e9](https://linux-hardware.org/?probe=feceb292e9) | Jun 10, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2f9e1d63ca](https://linux-hardware.org/?probe=2f9e1d63ca) | Jun 10, 2020 |
| Fujitsu       | LIFEBOOK P772               | [0589b2e0a0](https://linux-hardware.org/?probe=0589b2e0a0) | Jun 10, 2020 |
| Fujitsu       | LIFEBOOK P772               | [957ad12749](https://linux-hardware.org/?probe=957ad12749) | Jun 09, 2020 |
| HP            | Pavilion dv7                | [618623cb06](https://linux-hardware.org/?probe=618623cb06) | Jun 08, 2020 |
| HP            | 250 G5 Notebook PC          | [bf878163f2](https://linux-hardware.org/?probe=bf878163f2) | Jun 07, 2020 |
| Lenovo        | ThinkPad T430 23499K1       | [ea30f4cbe1](https://linux-hardware.org/?probe=ea30f4cbe1) | Jun 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [9e464080d3](https://linux-hardware.org/?probe=9e464080d3) | Jun 04, 2020 |
| Dell          | Inspiron 1525               | [0185bed721](https://linux-hardware.org/?probe=0185bed721) | Jun 04, 2020 |
| HP            | EliteBook 8560p             | [867a7d511c](https://linux-hardware.org/?probe=867a7d511c) | Jun 04, 2020 |
| HP            | Pavilion 15                 | [c9413e0257](https://linux-hardware.org/?probe=c9413e0257) | Jun 04, 2020 |
| Acer          | Extensa 5220                | [355c030bd6](https://linux-hardware.org/?probe=355c030bd6) | Jun 03, 2020 |
| HP            | EliteBook 8560p             | [fdffe7ecc3](https://linux-hardware.org/?probe=fdffe7ecc3) | Jun 03, 2020 |
| Dell          | Inspiron 5755               | [af7730ea54](https://linux-hardware.org/?probe=af7730ea54) | Jun 03, 2020 |
| Apple         | MacBook5,2                  | [140ac80aa0](https://linux-hardware.org/?probe=140ac80aa0) | Jun 02, 2020 |
| Dell          | Latitude E6410              | [0bb101f56b](https://linux-hardware.org/?probe=0bb101f56b) | Jun 02, 2020 |
| Lenovo        | Yoga 2 11 20332             | [ae024bfee6](https://linux-hardware.org/?probe=ae024bfee6) | Jun 01, 2020 |
| Lenovo        | Yoga 2 11 20332             | [028577a611](https://linux-hardware.org/?probe=028577a611) | Jun 01, 2020 |
| Lenovo        | Yoga 2 11 20332             | [3ad2ae8185](https://linux-hardware.org/?probe=3ad2ae8185) | Jun 01, 2020 |
| Apple         | MacBookPro5,5               | [8774f73788](https://linux-hardware.org/?probe=8774f73788) | Jun 01, 2020 |
| HP            | Notebook                    | [f449afb80f](https://linux-hardware.org/?probe=f449afb80f) | May 31, 2020 |
| Lenovo        | ThinkPad R500 273232G       | [f739a36965](https://linux-hardware.org/?probe=f739a36965) | May 31, 2020 |
| Lenovo        | V330-14ARR 81B1             | [659d266fe7](https://linux-hardware.org/?probe=659d266fe7) | May 30, 2020 |
| Acer          | Aspire 5251                 | [bb2843d8ef](https://linux-hardware.org/?probe=bb2843d8ef) | May 30, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [b3a2d13cf4](https://linux-hardware.org/?probe=b3a2d13cf4) | May 30, 2020 |
| Positivo      | V142N_4G                    | [d802ce99e3](https://linux-hardware.org/?probe=d802ce99e3) | May 30, 2020 |
| Dell          | Latitude D630               | [f89cfc029e](https://linux-hardware.org/?probe=f89cfc029e) | May 29, 2020 |
| LIVEFAN       | Unknown                     | [529dcde0bb](https://linux-hardware.org/?probe=529dcde0bb) | May 29, 2020 |
| ASUSTek       | S500CA                      | [5ee4fa628a](https://linux-hardware.org/?probe=5ee4fa628a) | May 29, 2020 |
| HP            | EliteBook 6930p             | [1beb03698d](https://linux-hardware.org/?probe=1beb03698d) | May 27, 2020 |
| Apple         | MacBookPro8,2               | [92badc70b3](https://linux-hardware.org/?probe=92badc70b3) | May 27, 2020 |
| Lenovo        | ThinkPad W530 24479Q7       | [b0e7a334cf](https://linux-hardware.org/?probe=b0e7a334cf) | May 26, 2020 |
| Lenovo        | ThinkPad W530 24479Q7       | [288fd814c0](https://linux-hardware.org/?probe=288fd814c0) | May 26, 2020 |
| Dell          | Latitude E6330              | [8255a6bf31](https://linux-hardware.org/?probe=8255a6bf31) | May 26, 2020 |
| Samsung       | N150P/N210P/N220P           | [0cfc0d7106](https://linux-hardware.org/?probe=0cfc0d7106) | May 26, 2020 |
| Toshiba       | PORTEGE R600                | [705c8aa483](https://linux-hardware.org/?probe=705c8aa483) | May 25, 2020 |
| ASUSTek       | F5SL                        | [947c9e7acf](https://linux-hardware.org/?probe=947c9e7acf) | May 25, 2020 |
| ASUSTek       | F5SL                        | [f61f397a5c](https://linux-hardware.org/?probe=f61f397a5c) | May 25, 2020 |
| HP            | EliteBook 8460p             | [daa996c0be](https://linux-hardware.org/?probe=daa996c0be) | May 24, 2020 |
| Acer          | Prespa M                    | [890a8d820f](https://linux-hardware.org/?probe=890a8d820f) | May 24, 2020 |
| Acer          | TravelMate 6594e            | [defbcb9f08](https://linux-hardware.org/?probe=defbcb9f08) | May 24, 2020 |
| Toshiba       | Satellite L745              | [e4b4a942e4](https://linux-hardware.org/?probe=e4b4a942e4) | May 24, 2020 |
| HP            | Laptop 14-cf1xxx            | [40df9d3c34](https://linux-hardware.org/?probe=40df9d3c34) | May 24, 2020 |
| HP            | 250 G5 Notebook PC          | [5729788ce3](https://linux-hardware.org/?probe=5729788ce3) | May 24, 2020 |
| Lenovo        | ThinkPad E480 20KN001NMC    | [1dcc1bede5](https://linux-hardware.org/?probe=1dcc1bede5) | May 24, 2020 |
| Acer          | Aspire ES1-311              | [cb043c4b53](https://linux-hardware.org/?probe=cb043c4b53) | May 24, 2020 |
| Notebook      | N230WU                      | [4c723c24e5](https://linux-hardware.org/?probe=4c723c24e5) | May 23, 2020 |
| ASUSTek       | S500CA                      | [72ff9768d5](https://linux-hardware.org/?probe=72ff9768d5) | May 23, 2020 |
| HP            | ENVY 17                     | [0c49cafa69](https://linux-hardware.org/?probe=0c49cafa69) | May 23, 2020 |
| Medion        | E122X                       | [e371cad88d](https://linux-hardware.org/?probe=e371cad88d) | May 23, 2020 |
| Lenovo        | Flex 2-15 20405             | [07c8fff8c3](https://linux-hardware.org/?probe=07c8fff8c3) | May 23, 2020 |
| Lenovo        | ThinkPad T420 4178A53       | [9962738ccd](https://linux-hardware.org/?probe=9962738ccd) | May 22, 2020 |
| Lenovo        | ThinkPad T61 889701U        | [d23b6592e3](https://linux-hardware.org/?probe=d23b6592e3) | May 22, 2020 |
| Lenovo        | Y50-70 20378                | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| HP            | ENVY 17                     | [8ad079156b](https://linux-hardware.org/?probe=8ad079156b) | May 22, 2020 |
| Clevo         | P170HMx                     | [b396ced50a](https://linux-hardware.org/?probe=b396ced50a) | May 21, 2020 |
| HP            | Presario C700               | [272a600f69](https://linux-hardware.org/?probe=272a600f69) | May 21, 2020 |
| MSI           | GE65 Raider 9SE             | [25b78cf2ec](https://linux-hardware.org/?probe=25b78cf2ec) | May 20, 2020 |
| Acer          | Aspire E5-771G              | [f7b2da81eb](https://linux-hardware.org/?probe=f7b2da81eb) | May 20, 2020 |
| HP            | ENVY 17                     | [d23283d49c](https://linux-hardware.org/?probe=d23283d49c) | May 19, 2020 |
| HP            | Notebook                    | [035439ee14](https://linux-hardware.org/?probe=035439ee14) | May 18, 2020 |
| Toshiba       | Satellite Pro U400          | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| HP            | G42                         | [832933728c](https://linux-hardware.org/?probe=832933728c) | May 17, 2020 |
| Dell          | Inspiron 13-5368            | [3374aba2b6](https://linux-hardware.org/?probe=3374aba2b6) | May 17, 2020 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [603bccc705](https://linux-hardware.org/?probe=603bccc705) | May 16, 2020 |
| Lenovo        | IdeaPad Z470                | [bc8159c07e](https://linux-hardware.org/?probe=bc8159c07e) | May 16, 2020 |
| Acer          | Aspire_8950G                | [63d11ebb5a](https://linux-hardware.org/?probe=63d11ebb5a) | May 16, 2020 |
| Apple         | MacBookPro2,2               | [e36974f7cc](https://linux-hardware.org/?probe=e36974f7cc) | May 16, 2020 |
| Apple         | MacBookAir1,1               | [90d4b67805](https://linux-hardware.org/?probe=90d4b67805) | May 16, 2020 |
| ASUSTek       | X555LAB                     | [74c38f38a9](https://linux-hardware.org/?probe=74c38f38a9) | May 16, 2020 |
| Lenovo        | ThinkPad T480s 20L7001LM... | [b6a2b0bd14](https://linux-hardware.org/?probe=b6a2b0bd14) | May 16, 2020 |
| Razer         | Blade                       | [8f9c962e1a](https://linux-hardware.org/?probe=8f9c962e1a) | May 16, 2020 |
| ASUSTek       | X555LAB                     | [c8e1bcf62b](https://linux-hardware.org/?probe=c8e1bcf62b) | May 16, 2020 |
| HP            | Notebook                    | [17b0d4b1b2](https://linux-hardware.org/?probe=17b0d4b1b2) | May 16, 2020 |
| Acer          | Aspire 5741                 | [6ea2978d3e](https://linux-hardware.org/?probe=6ea2978d3e) | May 15, 2020 |
| Notebook      | W65_W67RB                   | [970c88b78b](https://linux-hardware.org/?probe=970c88b78b) | May 15, 2020 |
| Notebook      | W65_W67RB                   | [341206a6dd](https://linux-hardware.org/?probe=341206a6dd) | May 15, 2020 |
| Acer          | Extensa 5630                | [6131a1471a](https://linux-hardware.org/?probe=6131a1471a) | May 15, 2020 |
| Toshiba       | Satellite L505              | [7d745ed98a](https://linux-hardware.org/?probe=7d745ed98a) | May 14, 2020 |
| Toshiba       | Satellite L505              | [93a4312b88](https://linux-hardware.org/?probe=93a4312b88) | May 14, 2020 |
| Dell          | Precision M4800             | [72621ff337](https://linux-hardware.org/?probe=72621ff337) | May 13, 2020 |
| Lenovo        | G50-45 80E3                 | [18edcf9cc0](https://linux-hardware.org/?probe=18edcf9cc0) | May 12, 2020 |
| Dell          | Inspiron 11-3162            | [afa9d2d85a](https://linux-hardware.org/?probe=afa9d2d85a) | May 12, 2020 |
| ASUSTek       | 1015PE                      | [fe2737f573](https://linux-hardware.org/?probe=fe2737f573) | May 11, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [e9ce0e160a](https://linux-hardware.org/?probe=e9ce0e160a) | May 11, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [93c6b04873](https://linux-hardware.org/?probe=93c6b04873) | May 11, 2020 |
| Fujitsu Si... | LIFEBOOK C1410              | [af84a18545](https://linux-hardware.org/?probe=af84a18545) | May 11, 2020 |
| Fujitsu Si... | AMILO Xi 2550               | [ecbe56efa5](https://linux-hardware.org/?probe=ecbe56efa5) | May 11, 2020 |
| Fujitsu Si... | AMILO Xi 2550               | [20e12d59df](https://linux-hardware.org/?probe=20e12d59df) | May 11, 2020 |
| ASUSTek       | 1015PE                      | [556e006e89](https://linux-hardware.org/?probe=556e006e89) | May 11, 2020 |
| HP            | Pavilion dv6500             | [84a92bf084](https://linux-hardware.org/?probe=84a92bf084) | May 11, 2020 |
| Clevo         | M540SR VT6363A              | [88ab93ca71](https://linux-hardware.org/?probe=88ab93ca71) | May 11, 2020 |
| Clevo         | M540SR VT6363A              | [d0895133b1](https://linux-hardware.org/?probe=d0895133b1) | May 11, 2020 |
| Toshiba       | Satellite C50-A-1DV         | [c4f8923ec1](https://linux-hardware.org/?probe=c4f8923ec1) | May 11, 2020 |
| HP            | Pavilion g6                 | [383dfd1cc0](https://linux-hardware.org/?probe=383dfd1cc0) | May 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ac3a34c4c0](https://linux-hardware.org/?probe=ac3a34c4c0) | May 11, 2020 |
| Acer          | Extensa 5630                | [fdeefe8947](https://linux-hardware.org/?probe=fdeefe8947) | May 10, 2020 |
| Fujitsu Si... | LIFEBOOK C1410              | [ad96f73112](https://linux-hardware.org/?probe=ad96f73112) | May 10, 2020 |
| Lenovo        | G400s 20244                 | [c53de49fbc](https://linux-hardware.org/?probe=c53de49fbc) | May 10, 2020 |
| Apple         | MacBookAir1,1               | [779a5f09e3](https://linux-hardware.org/?probe=779a5f09e3) | May 09, 2020 |
| Medion        | E5217                       | [4b29f60f4e](https://linux-hardware.org/?probe=4b29f60f4e) | May 09, 2020 |
| MSI           | CX61 2QF                    | [01e152927b](https://linux-hardware.org/?probe=01e152927b) | May 09, 2020 |
| Apple         | MacBookAir1,1               | [506802bbae](https://linux-hardware.org/?probe=506802bbae) | May 09, 2020 |
| Samsung       | NC20/NB20                   | [085b83a79c](https://linux-hardware.org/?probe=085b83a79c) | May 09, 2020 |
| HP            | EliteBook 2570p             | [a91bfd9548](https://linux-hardware.org/?probe=a91bfd9548) | May 09, 2020 |
| HP            | EliteBook 2570p             | [eaa4095c1a](https://linux-hardware.org/?probe=eaa4095c1a) | May 09, 2020 |
| HP            | Compaq 6715b (RM179UA#AB... | [4296f094b5](https://linux-hardware.org/?probe=4296f094b5) | May 09, 2020 |
| HP            | Pavilion dm4                | [bd82108066](https://linux-hardware.org/?probe=bd82108066) | May 08, 2020 |
| ASUSTek       | E205SA                      | [a45b866546](https://linux-hardware.org/?probe=a45b866546) | May 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| HP            | Compaq 6715b (RM179UA#AB... | [7687cc3b72](https://linux-hardware.org/?probe=7687cc3b72) | May 08, 2020 |
| Acer          | Aspire ES1-111M             | [0bc279404d](https://linux-hardware.org/?probe=0bc279404d) | May 07, 2020 |
| ASUSTek       | 1015PN                      | [50334e7c7f](https://linux-hardware.org/?probe=50334e7c7f) | May 07, 2020 |
| ASUSTek       | 1015PN                      | [0088c78042](https://linux-hardware.org/?probe=0088c78042) | May 07, 2020 |
| Exo           | CloudbookE15                | [b9b02e2bec](https://linux-hardware.org/?probe=b9b02e2bec) | May 06, 2020 |
| ASUSTek       | E205SA                      | [82cb9394d8](https://linux-hardware.org/?probe=82cb9394d8) | May 06, 2020 |
| HP            | Unknown                     | [a264169708](https://linux-hardware.org/?probe=a264169708) | May 06, 2020 |
| Toshiba       | Satellite L755              | [118ae8d50e](https://linux-hardware.org/?probe=118ae8d50e) | May 06, 2020 |
| HP            | Notebook                    | [27e6f036c6](https://linux-hardware.org/?probe=27e6f036c6) | May 05, 2020 |
| Exo           | CloudbookE15                | [651f6e4a76](https://linux-hardware.org/?probe=651f6e4a76) | May 05, 2020 |
| Exo           | CloudbookE15                | [101bb597a7](https://linux-hardware.org/?probe=101bb597a7) | May 05, 2020 |
| Toshiba       | PORTEGE R930                | [cdcaff95eb](https://linux-hardware.org/?probe=cdcaff95eb) | May 04, 2020 |
| Dell          | Inspiron 5566               | [f5f2719121](https://linux-hardware.org/?probe=f5f2719121) | May 04, 2020 |
| ASUSTek       | X55A                        | [4b731fa568](https://linux-hardware.org/?probe=4b731fa568) | May 04, 2020 |
| Lenovo        | ThinkPad P53 20QN004WRT     | [c1903a008d](https://linux-hardware.org/?probe=c1903a008d) | May 03, 2020 |
| HP            | Pavilion 15                 | [40862aa266](https://linux-hardware.org/?probe=40862aa266) | May 02, 2020 |
| HP            | Laptop 14-cf1xxx            | [eb9a4676cb](https://linux-hardware.org/?probe=eb9a4676cb) | May 02, 2020 |
| Dell          | Precision 7740              | [98f79195c4](https://linux-hardware.org/?probe=98f79195c4) | May 01, 2020 |
| Acer          | Aspire 5742G                | [e43d2cdc83](https://linux-hardware.org/?probe=e43d2cdc83) | Apr 30, 2020 |
| Lenovo        | ThinkPad SL410 2842K3U      | [e3a8739ead](https://linux-hardware.org/?probe=e3a8739ead) | Apr 29, 2020 |
| Lenovo        | ThinkPad Edge E130 3358C... | [2bc6ee441e](https://linux-hardware.org/?probe=2bc6ee441e) | Apr 29, 2020 |
| HP            | Laptop 14-cf1xxx            | [12d882022e](https://linux-hardware.org/?probe=12d882022e) | Apr 29, 2020 |
| ASUSTek       | X401A1                      | [730d39b054](https://linux-hardware.org/?probe=730d39b054) | Apr 29, 2020 |
| HP            | EliteBook 2570p             | [8481b529ee](https://linux-hardware.org/?probe=8481b529ee) | Apr 28, 2020 |
| ASUSTek       | X205TA                      | [78415a9613](https://linux-hardware.org/?probe=78415a9613) | Apr 28, 2020 |
| Acer          | Aspire E1-531               | [c57cc50f1f](https://linux-hardware.org/?probe=c57cc50f1f) | Apr 28, 2020 |
| Acer          | Aspire E1-531               | [fcbff20d29](https://linux-hardware.org/?probe=fcbff20d29) | Apr 28, 2020 |
| Toshiba       | Satellite L755              | [ae82feb6e1](https://linux-hardware.org/?probe=ae82feb6e1) | Apr 28, 2020 |
| Toshiba       | Satellite L755              | [e869421a7f](https://linux-hardware.org/?probe=e869421a7f) | Apr 28, 2020 |
| HP            | OMEN by Laptop              | [afa4e06e15](https://linux-hardware.org/?probe=afa4e06e15) | Apr 27, 2020 |
| Acer          | Aspire ES1-111M             | [ffb05ac445](https://linux-hardware.org/?probe=ffb05ac445) | Apr 27, 2020 |
| Lenovo        | ThinkPad 11e 20D90020US     | [1d8bd2f104](https://linux-hardware.org/?probe=1d8bd2f104) | Apr 26, 2020 |
| Dell          | Latitude E6410              | [294557e292](https://linux-hardware.org/?probe=294557e292) | Apr 25, 2020 |
| HP            | EliteBook 8560p             | [7fe6ce5446](https://linux-hardware.org/?probe=7fe6ce5446) | Apr 24, 2020 |
| Acer          | Extensa 5235                | [b7739ceed9](https://linux-hardware.org/?probe=b7739ceed9) | Apr 23, 2020 |
| Toshiba       | dynabook BX/571KW           | [9ba95d923c](https://linux-hardware.org/?probe=9ba95d923c) | Apr 22, 2020 |
| Dell          | Latitude E6540              | [0a2c664d30](https://linux-hardware.org/?probe=0a2c664d30) | Apr 19, 2020 |
| Toshiba       | dynabook BX/571KW           | [b8dba9c83d](https://linux-hardware.org/?probe=b8dba9c83d) | Apr 13, 2020 |
| Dell          | Inspiron 5566               | [ede3c6ed12](https://linux-hardware.org/?probe=ede3c6ed12) | Apr 12, 2020 |
| Dell          | Latitude E6540              | [1daf9c5f1a](https://linux-hardware.org/?probe=1daf9c5f1a) | Apr 10, 2020 |
| Dell          | Latitude 3450               | [7b91402f3f](https://linux-hardware.org/?probe=7b91402f3f) | Apr 06, 2020 |
| Dell          | Latitude 3450               | [db82b8f83d](https://linux-hardware.org/?probe=db82b8f83d) | Apr 06, 2020 |
| Acer          | AOD260                      | [c3fe3f443d](https://linux-hardware.org/?probe=c3fe3f443d) | Apr 02, 2020 |
| HP            | ProBook 4540s               | [7d8a63ba3c](https://linux-hardware.org/?probe=7d8a63ba3c) | Feb 19, 2020 |
| ASUSTek       | GL753VD                     | [cc5e432717](https://linux-hardware.org/?probe=cc5e432717) | Feb 02, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 51        | 4.67%   |
| 5.11.0-27-generic   | 38        | 3.48%   |
| 5.4.0-29-generic    | 30        | 2.75%   |
| 5.4.0-58-generic    | 27        | 2.47%   |
| 5.4.0-65-generic    | 24        | 2.2%    |
| 5.4.0-52-generic    | 24        | 2.2%    |
| 5.4.0-47-generic    | 24        | 2.2%    |
| 5.4.0-54-generic    | 22        | 2.01%   |
| 5.4.0-48-generic    | 22        | 2.01%   |
| 5.4.0-31-generic    | 21        | 1.92%   |
| 5.4.0-40-generic    | 20        | 1.83%   |
| 5.4.0-42-lowlatency | 18        | 1.65%   |
| 5.4.0-26-generic    | 17        | 1.56%   |
| 5.4.0-37-generic    | 16        | 1.47%   |
| 5.4.0-89-generic    | 15        | 1.37%   |
| 5.4.0-66-generic    | 15        | 1.37%   |
| 5.8.0-53-generic    | 14        | 1.28%   |
| 5.8.0-43-generic    | 14        | 1.28%   |
| 5.4.0-33-generic    | 14        | 1.28%   |
| 5.4.0-67-generic    | 13        | 1.19%   |
| 5.4.0-56-generic    | 12        | 1.1%    |
| 5.4.0-29-lowlatency | 12        | 1.1%    |
| 5.13.0-30-generic   | 12        | 1.1%    |
| 5.8.0-59-generic    | 11        | 1.01%   |
| 5.8.0-55-generic    | 11        | 1.01%   |
| 5.4.0-65-lowlatency | 11        | 1.01%   |
| 5.4.0-53-generic    | 11        | 1.01%   |
| 5.11.0-37-generic   | 11        | 1.01%   |
| 5.4.0-77-generic    | 10        | 0.92%   |
| 5.4.0-72-generic    | 10        | 0.92%   |
| 5.4.0-70-generic    | 10        | 0.92%   |
| 5.4.0-58-lowlatency | 10        | 0.92%   |
| 5.11.0-38-generic   | 10        | 0.92%   |
| 5.4.0-91-generic    | 8         | 0.73%   |
| 5.4.0-90-generic    | 8         | 0.73%   |
| 5.4.0-81-generic    | 8         | 0.73%   |
| 5.4.0-80-generic    | 8         | 0.73%   |
| 5.4.0-60-generic    | 8         | 0.73%   |
| 5.4.0-45-generic    | 8         | 0.73%   |
| 5.4.0-107-generic   | 8         | 0.73%   |
| 5.13.0-39-generic   | 8         | 0.73%   |
| 5.13.0-35-generic   | 8         | 0.73%   |
| 5.11.0-34-generic   | 8         | 0.73%   |
| 5.11.0-25-generic   | 8         | 0.73%   |
| 5.8.0-48-generic    | 7         | 0.64%   |
| 5.8.0-44-generic    | 7         | 0.64%   |
| 5.4.0-74-generic    | 7         | 0.64%   |
| 5.4.0-73-generic    | 7         | 0.64%   |
| 5.4.0-64-generic    | 7         | 0.64%   |
| 5.4.0-59-generic    | 7         | 0.64%   |
| 5.4.0-40-lowlatency | 7         | 0.64%   |
| 5.4.0-26-lowlatency | 7         | 0.64%   |
| 5.11.0-44-generic   | 7         | 0.64%   |
| 5.11.0-43-generic   | 7         | 0.64%   |
| 5.11.0-40-generic   | 7         | 0.64%   |
| 5.4.0-62-generic    | 6         | 0.55%   |
| 5.4.0-51-generic    | 6         | 0.55%   |
| 5.4.0-48-lowlatency | 6         | 0.55%   |
| 5.4.0-37-lowlatency | 6         | 0.55%   |
| 5.4.0-31-lowlatency | 6         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 635       | 65.67%  |
| 5.11.0  | 127       | 13.13%  |
| 5.8.0   | 96        | 9.93%   |
| 5.13.0  | 72        | 7.45%   |
| 5.15.0  | 7         | 0.72%   |
| 5.10.0  | 5         | 0.52%   |
| 5.14.0  | 2         | 0.21%   |
| 4.4.254 | 2         | 0.21%   |
| 5.9.6   | 1         | 0.1%    |
| 5.9.0   | 1         | 0.1%    |
| 5.8.18  | 1         | 0.1%    |
| 5.7.7   | 1         | 0.1%    |
| 5.7.6   | 1         | 0.1%    |
| 5.7.0   | 1         | 0.1%    |
| 5.6.19  | 1         | 0.1%    |
| 5.6.0   | 1         | 0.1%    |
| 5.4.67  | 1         | 0.1%    |
| 5.4.107 | 1         | 0.1%    |
| 5.17.0  | 1         | 0.1%    |
| 5.15.36 | 1         | 0.1%    |
| 5.14.9  | 1         | 0.1%    |
| 5.14.8  | 1         | 0.1%    |
| 5.14.2  | 1         | 0.1%    |
| 5.12.12 | 1         | 0.1%    |
| 5.12.10 | 1         | 0.1%    |
| 5.11.11 | 1         | 0.1%    |
| 5.10.33 | 1         | 0.1%    |
| 5.10.11 | 1         | 0.1%    |
| 4.15.0  | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 637       | 65.87%  |
| 5.11    | 128       | 13.24%  |
| 5.8     | 97        | 10.03%  |
| 5.13    | 72        | 7.45%   |
| 5.15    | 8         | 0.83%   |
| 5.10    | 7         | 0.72%   |
| 5.14    | 5         | 0.52%   |
| 5.7     | 3         | 0.31%   |
| 5.9     | 2         | 0.21%   |
| 5.6     | 2         | 0.21%   |
| 5.12    | 2         | 0.21%   |
| 4.4     | 2         | 0.21%   |
| 5.17    | 1         | 0.1%    |
| 4.15    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 948       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 913       | 96.31%  |
| GNOME           | 23        | 2.43%   |
| i3              | 5         | 0.53%   |
| Unity           | 2         | 0.21%   |
| KDE5            | 2         | 0.21%   |
| MATE            | 1         | 0.11%   |
| ICEWM           | 1         | 0.11%   |
| GNOME Flashback | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 936       | 98.73%  |
| Tty     | 8         | 0.84%   |
| Wayland | 4         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 474       | 48.57%  |
| LightDM | 286       | 29.3%   |
| TDM     | 188       | 19.26%  |
| GDM     | 17        | 1.74%   |
| GDM3    | 9         | 0.92%   |
| SDDM    | 2         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 331       | 34.84%  |
| de_DE | 99        | 10.42%  |
| fr_FR | 94        | 9.89%   |
| pt_BR | 61        | 6.42%   |
| C     | 53        | 5.58%   |
| it_IT | 50        | 5.26%   |
| en_GB | 36        | 3.79%   |
| ru_RU | 31        | 3.26%   |
| es_ES | 25        | 2.63%   |
| pl_PL | 21        | 2.21%   |
| en_CA | 12        | 1.26%   |
| en_AU | 10        | 1.05%   |
| nl_NL | 9         | 0.95%   |
| es_AR | 9         | 0.95%   |
| cs_CZ | 9         | 0.95%   |
| en_IN | 8         | 0.84%   |
| ja_JP | 7         | 0.74%   |
| hu_HU | 7         | 0.74%   |
| es_MX | 6         | 0.63%   |
| sv_SE | 5         | 0.53%   |
| ru_UA | 4         | 0.42%   |
| fi_FI | 4         | 0.42%   |
| es_PE | 4         | 0.42%   |
| pt_PT | 3         | 0.32%   |
| fr_BE | 3         | 0.32%   |
| en_SG | 3         | 0.32%   |
| el_GR | 3         | 0.32%   |
| de_CH | 3         | 0.32%   |
| de_AT | 3         | 0.32%   |
| zh_CN | 2         | 0.21%   |
| uk_UA | 2         | 0.21%   |
| tr_TR | 2         | 0.21%   |
| nl_BE | 2         | 0.21%   |
| nb_NO | 2         | 0.21%   |
| lt_LT | 2         | 0.21%   |
| id_ID | 2         | 0.21%   |
| fr_CA | 2         | 0.21%   |
| es_CO | 2         | 0.21%   |
| es_CL | 2         | 0.21%   |
| en_ZA | 2         | 0.21%   |
| da_DK | 2         | 0.21%   |
| bg_BG | 2         | 0.21%   |
| sl_SI | 1         | 0.11%   |
| sk_SK | 1         | 0.11%   |
| es_VE | 1         | 0.11%   |
| es_NI | 1         | 0.11%   |
| es_EC | 1         | 0.11%   |
| es_CR | 1         | 0.11%   |
| en_PH | 1         | 0.11%   |
| en_NZ | 1         | 0.11%   |
| en_IL | 1         | 0.11%   |
| en_IE | 1         | 0.11%   |
| ar_EG | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 505       | 52.99%  |
| EFI  | 448       | 47.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 860       | 90.72%  |
| Overlay | 58        | 6.12%   |
| Btrfs   | 13        | 1.37%   |
| Zfs     | 7         | 0.74%   |
| Xfs     | 3         | 0.32%   |
| Ext2    | 3         | 0.32%   |
| Ext3    | 2         | 0.21%   |
| Unknown | 2         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 578       | 60.84%  |
| GPT     | 230       | 24.21%  |
| MBR     | 142       | 14.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 832       | 86.13%  |
| Yes       | 134       | 13.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 653       | 68.09%  |
| Yes       | 306       | 31.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 204       | 21.52%  |
| Lenovo                      | 179       | 18.88%  |
| Dell                        | 141       | 14.87%  |
| ASUSTek Computer            | 109       | 11.5%   |
| Acer                        | 81        | 8.54%   |
| Toshiba                     | 49        | 5.17%   |
| Samsung Electronics         | 21        | 2.22%   |
| Apple                       | 19        | 2%      |
| MSI                         | 15        | 1.58%   |
| Sony                        | 14        | 1.48%   |
| Notebook                    | 12        | 1.27%   |
| Medion                      | 12        | 1.27%   |
| Fujitsu                     | 7         | 0.74%   |
| Clevo                       | 7         | 0.74%   |
| Packard Bell                | 6         | 0.63%   |
| Fujitsu Siemens             | 6         | 0.63%   |
| Positivo                    | 5         | 0.53%   |
| HUAWEI                      | 4         | 0.42%   |
| TUXEDO                      | 3         | 0.32%   |
| Schenker                    | 3         | 0.32%   |
| GPU Company                 | 3         | 0.32%   |
| Google                      | 3         | 0.32%   |
| Gateway                     | 3         | 0.32%   |
| Dynabook                    | 3         | 0.32%   |
| Razer                       | 2         | 0.21%   |
| Multilaser                  | 2         | 0.21%   |
| Itautec                     | 2         | 0.21%   |
| Intel                       | 2         | 0.21%   |
| Exo                         | 2         | 0.21%   |
| AMI                         | 2         | 0.21%   |
| Alienware                   | 2         | 0.21%   |
| Unknown                     | 2         | 0.21%   |
| VIT                         | 1         | 0.11%   |
| UNOWHY                      | 1         | 0.11%   |
| System76                    | 1         | 0.11%   |
| Semp Toshiba                | 1         | 0.11%   |
| Quanta                      | 1         | 0.11%   |
| PLAISIO COMPUTERS SA        | 1         | 0.11%   |
| ONE-NETBOOK TECHNOLOGY      | 1         | 0.11%   |
| OEGStone                    | 1         | 0.11%   |
| MouseComputer               | 1         | 0.11%   |
| MOTION                      | 1         | 0.11%   |
| Login Informatica           | 1         | 0.11%   |
| LIVEFAN                     | 1         | 0.11%   |
| LG Electronics              | 1         | 0.11%   |
| Jumper                      | 1         | 0.11%   |
| Insyde                      | 1         | 0.11%   |
| I-Life Digital Technologies | 1         | 0.11%   |
| Dixonsxp                    | 1         | 0.11%   |
| Direkt-Tek                  | 1         | 0.11%   |
| Digibras                    | 1         | 0.11%   |
| Coradir                     | 1         | 0.11%   |
| Compaq                      | 1         | 0.11%   |
| Chuwi                       | 1         | 0.11%   |
| CAPTIVA                     | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Notebook                            | 11        | 1.16%   |
| Unknown                                | 9         | 0.95%   |
| Dell Latitude D630                     | 8         | 0.84%   |
| HP Pavilion dv6                        | 6         | 0.63%   |
| Dell Latitude E6430                    | 6         | 0.63%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.63%   |
| HP 15                                  | 5         | 0.53%   |
| HP Pavilion dv7                        | 4         | 0.42%   |
| HP EliteBook 8560p                     | 4         | 0.42%   |
| Dell Latitude E6330                    | 4         | 0.42%   |
| Toshiba Satellite A100                 | 3         | 0.32%   |
| Toshiba PORTEGE R930                   | 3         | 0.32%   |
| HP ProBook 4540s                       | 3         | 0.32%   |
| HP Presario C700                       | 3         | 0.32%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 3         | 0.32%   |
| HP Pavilion g7                         | 3         | 0.32%   |
| HP Pavilion g6                         | 3         | 0.32%   |
| HP Pavilion dv6500                     | 3         | 0.32%   |
| HP Pavilion 17                         | 3         | 0.32%   |
| HP Pavilion 15                         | 3         | 0.32%   |
| HP G42                                 | 3         | 0.32%   |
| HP 255 G7 Notebook PC                  | 3         | 0.32%   |
| Dell Latitude E6540                    | 3         | 0.32%   |
| Dell Latitude 7480                     | 3         | 0.32%   |
| Dell Inspiron 7720                     | 3         | 0.32%   |
| Dell Inspiron 5566                     | 3         | 0.32%   |
| ASUS X553MA                            | 3         | 0.32%   |
| ASUS T100HAN                           | 3         | 0.32%   |
| ASUS K53SC                             | 3         | 0.32%   |
| Acer Aspire 7720                       | 3         | 0.32%   |
| Toshiba Satellite L350D                | 2         | 0.21%   |
| Medion E6228                           | 2         | 0.21%   |
| Lenovo ThinkPad T495s 20QJCTO1WW       | 2         | 0.21%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 2         | 0.21%   |
| Lenovo IdeaPad 100-15IBY 80MJ          | 2         | 0.21%   |
| HUAWEI NBLK-WAX9X                      | 2         | 0.21%   |
| HUAWEI KPL-W0X                         | 2         | 0.21%   |
| HP ProBook 640 G1                      | 2         | 0.21%   |
| HP ProBook 430 G5                      | 2         | 0.21%   |
| HP Pavilion g4                         | 2         | 0.21%   |
| HP Pavilion dm4                        | 2         | 0.21%   |
| HP OMEN by Laptop                      | 2         | 0.21%   |
| HP Laptop 15-dw0xxx                    | 2         | 0.21%   |
| HP Laptop 15-da0xxx                    | 2         | 0.21%   |
| HP Laptop 15-bw0xx                     | 2         | 0.21%   |
| HP G72                                 | 2         | 0.21%   |
| HP G62                                 | 2         | 0.21%   |
| HP G60                                 | 2         | 0.21%   |
| HP EliteBook 8470p                     | 2         | 0.21%   |
| HP EliteBook 8460p                     | 2         | 0.21%   |
| HP EliteBook 840 G1                    | 2         | 0.21%   |
| HP EliteBook 2570p                     | 2         | 0.21%   |
| HP EliteBook 2540p                     | 2         | 0.21%   |
| HP Compaq Presario CQ61                | 2         | 0.21%   |
| HP Compaq Presario CQ60                | 2         | 0.21%   |
| HP Compaq 6730s                        | 2         | 0.21%   |
| HP Compaq 6510b                        | 2         | 0.21%   |
| HP 250 G7 Notebook PC                  | 2         | 0.21%   |
| HP 14                                  | 2         | 0.21%   |
| Exo CloudbookE15                       | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 110       | 11.6%   |
| Dell Latitude            | 62        | 6.54%   |
| Acer Aspire              | 55        | 5.8%    |
| HP Pavilion              | 48        | 5.06%   |
| Dell Inspiron            | 48        | 5.06%   |
| Toshiba Satellite        | 39        | 4.11%   |
| Lenovo IdeaPad           | 32        | 3.38%   |
| HP EliteBook             | 31        | 3.27%   |
| HP ProBook               | 22        | 2.32%   |
| ASUS VivoBook            | 22        | 2.32%   |
| HP Laptop                | 21        | 2.22%   |
| HP Compaq                | 19        | 2%      |
| HP Notebook              | 12        | 1.27%   |
| Dell Vostro              | 12        | 1.27%   |
| Acer Extensa             | 10        | 1.05%   |
| Unknown                  | 9         | 0.95%   |
| Packard Bell EasyNote    | 6         | 0.63%   |
| Dell XPS                 | 6         | 0.63%   |
| Toshiba PORTEGE          | 5         | 0.53%   |
| HP Presario              | 5         | 0.53%   |
| HP 255                   | 5         | 0.53%   |
| HP 15                    | 5         | 0.53%   |
| Fujitsu LIFEBOOK         | 5         | 0.53%   |
| Dell Precision           | 5         | 0.53%   |
| HP OMEN                  | 4         | 0.42%   |
| HP 250                   | 4         | 0.42%   |
| Fujitsu Siemens AMILO    | 4         | 0.42%   |
| Dell Studio              | 4         | 0.42%   |
| Acer Nitro               | 4         | 0.42%   |
| Samsung R530             | 3         | 0.32%   |
| Lenovo B590              | 3         | 0.32%   |
| HP ZBook                 | 3         | 0.32%   |
| HP Stream                | 3         | 0.32%   |
| HP G42                   | 3         | 0.32%   |
| HP ENVY                  | 3         | 0.32%   |
| ASUS X553MA              | 3         | 0.32%   |
| ASUS T100HAN             | 3         | 0.32%   |
| ASUS ROG                 | 3         | 0.32%   |
| ASUS K53SC               | 3         | 0.32%   |
| ASUS ASUS                | 3         | 0.32%   |
| Acer Swift               | 3         | 0.32%   |
| Toshiba TECRA            | 2         | 0.21%   |
| Schenker XMG             | 2         | 0.21%   |
| Samsung N150P            | 2         | 0.21%   |
| Razer Blade              | 2         | 0.21%   |
| Notebook W65             | 2         | 0.21%   |
| Medion E6228             | 2         | 0.21%   |
| Medion Akoya             | 2         | 0.21%   |
| Lenovo ThinkBook         | 2         | 0.21%   |
| Lenovo G460              | 2         | 0.21%   |
| Lenovo G400s             | 2         | 0.21%   |
| Lenovo 3000              | 2         | 0.21%   |
| Itautec Infoway          | 2         | 0.21%   |
| HUAWEI NBLK-WAX9X        | 2         | 0.21%   |
| HUAWEI KPL-W0X           | 2         | 0.21%   |
| HP G72                   | 2         | 0.21%   |
| HP G62                   | 2         | 0.21%   |
| HP G60                   | 2         | 0.21%   |
| HP 14                    | 2         | 0.21%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 96        | 10.13%  |
| 2011 | 94        | 9.92%   |
| 2019 | 78        | 8.23%   |
| 2010 | 75        | 7.91%   |
| 2013 | 73        | 7.7%    |
| 2008 | 65        | 6.86%   |
| 2020 | 58        | 6.12%   |
| 2017 | 58        | 6.12%   |
| 2014 | 58        | 6.12%   |
| 2007 | 57        | 6.01%   |
| 2018 | 54        | 5.7%    |
| 2016 | 45        | 4.75%   |
| 2015 | 42        | 4.43%   |
| 2009 | 38        | 4.01%   |
| 2021 | 37        | 3.9%    |
| 2006 | 14        | 1.48%   |
| 2022 | 3         | 0.32%   |
| 2005 | 3         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 948       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 869       | 91.19%  |
| Enabled  | 84        | 8.81%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 944       | 99.58%  |
| Yes  | 4         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 310       | 32.39%  |
| 4.01-8.0    | 236       | 24.66%  |
| 16.01-24.0  | 114       | 11.91%  |
| 8.01-16.0   | 113       | 11.81%  |
| 1.01-2.0    | 93        | 9.72%   |
| 32.01-64.0  | 34        | 3.55%   |
| 2.01-3.0    | 25        | 2.61%   |
| 0.51-1.0    | 15        | 1.57%   |
| 64.01-256.0 | 9         | 0.94%   |
| 24.01-32.0  | 7         | 0.73%   |
| 0.01-0.5    | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 485       | 47.04%  |
| 2.01-3.0   | 218       | 21.14%  |
| 0.51-1.0   | 135       | 13.09%  |
| 4.01-8.0   | 88        | 8.54%   |
| 3.01-4.0   | 78        | 7.57%   |
| 8.01-16.0  | 24        | 2.33%   |
| 24.01-32.0 | 1         | 0.1%    |
| 16.01-24.0 | 1         | 0.1%    |
| 0.01-0.5   | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 705       | 72.83%  |
| 2      | 219       | 22.62%  |
| 3      | 21        | 2.17%   |
| 0      | 17        | 1.76%   |
| 4      | 4         | 0.41%   |
| 7      | 1         | 0.1%    |
| 5      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 487       | 51.32%  |
| No        | 462       | 48.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 826       | 87.04%  |
| No        | 123       | 12.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 921       | 96.95%  |
| No        | 29        | 3.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 611       | 63.58%  |
| No        | 350       | 36.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 155       | 16.26%  |
| Germany             | 125       | 13.12%  |
| France              | 97        | 10.18%  |
| Brazil              | 64        | 6.72%   |
| Italy               | 54        | 5.67%   |
| Canada              | 42        | 4.41%   |
| Russia              | 39        | 4.09%   |
| UK                  | 36        | 3.78%   |
| Spain               | 36        | 3.78%   |
| Netherlands         | 29        | 3.04%   |
| Poland              | 25        | 2.62%   |
| Portugal            | 12        | 1.26%   |
| Czechia             | 12        | 1.26%   |
| Belgium             | 12        | 1.26%   |
| Argentina           | 12        | 1.26%   |
| Ukraine             | 11        | 1.15%   |
| Mexico              | 10        | 1.05%   |
| India               | 10        | 1.05%   |
| Finland             | 10        | 1.05%   |
| Australia           | 10        | 1.05%   |
| Greece              | 9         | 0.94%   |
| Japan               | 8         | 0.84%   |
| Indonesia           | 8         | 0.84%   |
| Bulgaria            | 8         | 0.84%   |
| Turkey              | 7         | 0.73%   |
| Sweden              | 7         | 0.73%   |
| Norway              | 7         | 0.73%   |
| Hungary             | 7         | 0.73%   |
| Austria             | 6         | 0.63%   |
| Denmark             | 5         | 0.52%   |
| Romania             | 4         | 0.42%   |
| Peru                | 4         | 0.42%   |
| Lithuania           | 4         | 0.42%   |
| Slovenia            | 3         | 0.31%   |
| Slovakia            | 3         | 0.31%   |
| Singapore           | 3         | 0.31%   |
| Serbia              | 3         | 0.31%   |
| Colombia            | 3         | 0.31%   |
| Chile               | 3         | 0.31%   |
| Belarus             | 3         | 0.31%   |
| Algeria             | 3         | 0.31%   |
| Thailand            | 2         | 0.21%   |
| Switzerland         | 2         | 0.21%   |
| South Africa        | 2         | 0.21%   |
| Philippines         | 2         | 0.21%   |
| Luxembourg          | 2         | 0.21%   |
| Iran                | 2         | 0.21%   |
| Estonia             | 2         | 0.21%   |
| Costa Rica          | 2         | 0.21%   |
| China               | 2         | 0.21%   |
| Zimbabwe            | 1         | 0.1%    |
| Venezuela           | 1         | 0.1%    |
| Uruguay             | 1         | 0.1%    |
| UAE                 | 1         | 0.1%    |
| Trinidad and Tobago | 1         | 0.1%    |
| Sudan               | 1         | 0.1%    |
| Sri Lanka           | 1         | 0.1%    |
| South Korea         | 1         | 0.1%    |
| Saudi Arabia        | 1         | 0.1%    |
| Puerto Rico         | 1         | 0.1%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Québec               | 17        | 1.7%    |
| Paris                 | 14        | 1.4%    |
| Warsaw                | 10        | 1%      |
| Hamburg               | 10        | 1%      |
| Berlin                | 9         | 0.9%    |
| Amsterdam             | 9         | 0.9%    |
| Rome                  | 8         | 0.8%    |
| Moscow                | 8         | 0.8%    |
| St Petersburg         | 7         | 0.7%    |
| Munich                | 7         | 0.7%    |
| Sao Paulo             | 6         | 0.6%    |
| Rio de Janeiro        | 6         | 0.6%    |
| Athens                | 6         | 0.6%    |
| Vienna                | 5         | 0.5%    |
| Sofia                 | 5         | 0.5%    |
| Pittsburgh            | 5         | 0.5%    |
| Madrid                | 5         | 0.5%    |
| Karlsruhe             | 5         | 0.5%    |
| Helsinki              | 5         | 0.5%    |
| Frankfurt am Main     | 5         | 0.5%    |
| Budapest              | 5         | 0.5%    |
| Barcelona             | 5         | 0.5%    |
| Toronto               | 4         | 0.4%    |
| Mannheim              | 4         | 0.4%    |
| Lisbon                | 4         | 0.4%    |
| Lima                  | 4         | 0.4%    |
| Leipzig               | 4         | 0.4%    |
| Kyiv                  | 4         | 0.4%    |
| Genoa                 | 4         | 0.4%    |
| Chicago               | 4         | 0.4%    |
| Yokohama              | 3         | 0.3%    |
| Wroclaw               | 3         | 0.3%    |
| Vilnius               | 3         | 0.3%    |
| Varna                 | 3         | 0.3%    |
| Sydney                | 3         | 0.3%    |
| Singapore             | 3         | 0.3%    |
| Shinjuku              | 3         | 0.3%    |
| Salvador              | 3         | 0.3%    |
| Poznan                | 3         | 0.3%    |
| Odense                | 3         | 0.3%    |
| Milan                 | 3         | 0.3%    |
| Levis                 | 3         | 0.3%    |
| León                 | 3         | 0.3%    |
| Krasnodar             | 3         | 0.3%    |
| Ghent                 | 3         | 0.3%    |
| Casalecchio di Reno   | 3         | 0.3%    |
| Bogotá               | 3         | 0.3%    |
| Bamberg               | 3         | 0.3%    |
| Ankara                | 3         | 0.3%    |
| Wilmington            | 2         | 0.2%    |
| Washington            | 2         | 0.2%    |
| Villejuif             | 2         | 0.2%    |
| Villecresnes          | 2         | 0.2%    |
| Vila Nova de Gaia     | 2         | 0.2%    |
| Suzano                | 2         | 0.2%    |
| Seattle               | 2         | 0.2%    |
| Sao Bernardo do Campo | 2         | 0.2%    |
| Saint Paul            | 2         | 0.2%    |
| Redmond               | 2         | 0.2%    |
| Recife                | 2         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 166       | 204    | 14.73%  |
| Seagate             | 162       | 194    | 14.37%  |
| WDC                 | 143       | 170    | 12.69%  |
| Toshiba             | 105       | 126    | 9.32%   |
| Unknown             | 86        | 105    | 7.63%   |
| Kingston            | 54        | 70     | 4.79%   |
| Hitachi             | 48        | 57     | 4.26%   |
| SanDisk             | 42        | 54     | 3.73%   |
| HGST                | 39        | 45     | 3.46%   |
| SK hynix            | 31        | 36     | 2.75%   |
| Crucial             | 31        | 37     | 2.75%   |
| Intel               | 27        | 41     | 2.4%    |
| Fujitsu             | 22        | 28     | 1.95%   |
| Micron Technology   | 17        | 18     | 1.51%   |
| A-DATA Technology   | 15        | 19     | 1.33%   |
| China               | 10        | 11     | 0.89%   |
| KIOXIA              | 8         | 9      | 0.71%   |
| Apple               | 8         | 11     | 0.71%   |
| LITEON              | 7         | 9      | 0.62%   |
| Intenso             | 6         | 6      | 0.53%   |
| Phison              | 5         | 8      | 0.44%   |
| OCZ                 | 5         | 5      | 0.44%   |
| LITEONIT            | 5         | 7      | 0.44%   |
| JMicron Technology  | 5         | 5      | 0.44%   |
| Transcend           | 4         | 4      | 0.35%   |
| PNY                 | 4         | 4      | 0.35%   |
| KingSpec            | 4         | 5      | 0.35%   |
| Apacer              | 4         | 5      | 0.35%   |
| Unknown             | 4         | 4      | 0.35%   |
| SSK                 | 3         | 3      | 0.27%   |
| SPCC                | 3         | 4      | 0.27%   |
| Patriot             | 3         | 3      | 0.27%   |
| Netac               | 3         | 3      | 0.27%   |
| Hewlett-Packard     | 3         | 2      | 0.27%   |
| Smartbuy            | 2         | 2      | 0.18%   |
| Silicon Motion      | 2         | 2      | 0.18%   |
| Mushkin             | 2         | 2      | 0.18%   |
| GOODRAM             | 2         | 2      | 0.18%   |
| Drevo               | 2         | 2      | 0.18%   |
| ASMT                | 2         | 4      | 0.18%   |
| ZTE                 | 1         | 1      | 0.09%   |
| ZTC-SM20            | 1         | 1      | 0.09%   |
| Zheino              | 1         | 1      | 0.09%   |
| XPG                 | 1         | 1      | 0.09%   |
| V-GeN               | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| TCSUNBOW            | 1         | 1      | 0.09%   |
| SUNEAST             | 1         | 2      | 0.09%   |
| SSSTC               | 1         | 1      | 0.09%   |
| SABRENT             | 1         | 1      | 0.09%   |
| Pioneer             | 1         | 1      | 0.09%   |
| OWC                 | 1         | 1      | 0.09%   |
| Londisk             | 1         | 1      | 0.09%   |
| Lexar               | 1         | 1      | 0.09%   |
| Lenovo              | 1         | 1      | 0.09%   |
| LDLC                | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.09%   |
| Kingmax             | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 22        | 1.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 1.28%   |
| Seagate ST500LT012-1DG142 500GB     | 13        | 1.11%   |
| Kingston SA400S37480G 480GB SSD     | 13        | 1.11%   |
| Unknown MMC Card  64GB              | 12        | 1.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 12        | 1.03%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 1.03%   |
| Samsung SSD 850 EVO 250GB           | 11        | 0.94%   |
| HGST HTS721010A9E630 1TB            | 11        | 0.94%   |
| Unknown MMC Card  128GB             | 9         | 0.77%   |
| Toshiba MQ01ABD100 1TB              | 9         | 0.77%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 0.77%   |
| Toshiba MQ01ABF050 500GB            | 8         | 0.68%   |
| SK hynix NVMe SSD Drive 256GB       | 8         | 0.68%   |
| Samsung NVMe SSD Drive 512GB        | 8         | 0.68%   |
| HGST HTS541010A9E680 1TB            | 8         | 0.68%   |
| Unknown MMC Card  16GB              | 7         | 0.6%    |
| Seagate ST9250315AS 250GB           | 7         | 0.6%    |
| Samsung SSD 860 EVO 500GB           | 7         | 0.6%    |
| Samsung SSD 860 EVO 1TB             | 7         | 0.6%    |
| Kingston SA400S37240G 240GB SSD     | 7         | 0.6%    |
| Kingston SA400S37120G 120GB SSD     | 7         | 0.6%    |
| Crucial CT500MX500SSD1 500GB        | 7         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB            | 6         | 0.51%   |
| Toshiba MQ04ABF100 1TB              | 6         | 0.51%   |
| Samsung HM321HI 320GB               | 6         | 0.51%   |
| Intel HBRPEKNX0202AO 32GB           | 6         | 0.51%   |
| Intel HBRPEKNX0202A 512GB           | 6         | 0.51%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 0.51%   |
| Seagate ST9500423AS 500GB           | 5         | 0.43%   |
| Seagate ST9320325AS 320GB           | 5         | 0.43%   |
| Kingston SV300S37A120G 120GB SSD    | 5         | 0.43%   |
| Hitachi HTS723232A7A364 320GB       | 5         | 0.43%   |
| Crucial CT240BX500SSD1 240GB        | 5         | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 4         | 0.34%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 4         | 0.34%   |
| WDC WD10SPZX-21Z10T0 1TB            | 4         | 0.34%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB  | 4         | 0.34%   |
| Unknown SD/MMC/MS PRO 64GB          | 4         | 0.34%   |
| Toshiba MQ01ABD050 500GB            | 4         | 0.34%   |
| Seagate ST9750420AS 752GB           | 4         | 0.34%   |
| Seagate ST9500420AS 500GB           | 4         | 0.34%   |
| Seagate ST9500325AS 500GB           | 4         | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 0.34%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 0.34%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 0.34%   |
| SanDisk SSD PLUS 240GB              | 4         | 0.34%   |
| SanDisk NVMe SSD Drive 512GB        | 4         | 0.34%   |
| SanDisk NVMe SSD Drive 256GB        | 4         | 0.34%   |
| Samsung MZVLB512HBJQ-000L7 512GB    | 4         | 0.34%   |
| Samsung HN-M500MBB 500GB            | 4         | 0.34%   |
| Kingston SA400S37960G 960GB SSD     | 4         | 0.34%   |
| Hitachi HTS545025B9A300 250GB       | 4         | 0.34%   |
| HGST HTS545050A7E680 500GB          | 4         | 0.34%   |
| HGST HTS545050A7E380 500GB          | 4         | 0.34%   |
| Unknown                             | 4         | 0.34%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 3         | 0.26%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 0.26%   |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 0.26%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 160       | 191    | 32.19%  |
| WDC                 | 110       | 132    | 22.13%  |
| Toshiba             | 84        | 103    | 16.9%   |
| Hitachi             | 48        | 57     | 9.66%   |
| HGST                | 39        | 45     | 7.85%   |
| Samsung Electronics | 26        | 32     | 5.23%   |
| Fujitsu             | 21        | 27     | 4.23%   |
| Unknown             | 4         | 4      | 0.8%    |
| SABRENT             | 1         | 1      | 0.2%    |
| Intenso             | 1         | 1      | 0.2%    |
| HGST HTS            | 1         | 1      | 0.2%    |
| CLOVER              | 1         | 1      | 0.2%    |
| ACASIS              | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 84        | 105    | 24.28%  |
| Kingston            | 47        | 62     | 13.58%  |
| SanDisk             | 31        | 41     | 8.96%   |
| Crucial             | 31        | 37     | 8.96%   |
| A-DATA Technology   | 13        | 17     | 3.76%   |
| Micron Technology   | 11        | 11     | 3.18%   |
| China               | 10        | 11     | 2.89%   |
| WDC                 | 9         | 9      | 2.6%    |
| Toshiba             | 9         | 9      | 2.6%    |
| SK hynix            | 8         | 8      | 2.31%   |
| LITEON              | 7         | 9      | 2.02%   |
| Intel               | 7         | 12     | 2.02%   |
| OCZ                 | 5         | 5      | 1.45%   |
| LITEONIT            | 5         | 7      | 1.45%   |
| Intenso             | 5         | 5      | 1.45%   |
| Apple               | 5         | 6      | 1.45%   |
| Unknown             | 4         | 5      | 1.16%   |
| Transcend           | 4         | 4      | 1.16%   |
| PNY                 | 4         | 4      | 1.16%   |
| Apacer              | 4         | 5      | 1.16%   |
| SPCC                | 3         | 4      | 0.87%   |
| Patriot             | 3         | 3      | 0.87%   |
| KingSpec            | 3         | 4      | 0.87%   |
| Smartbuy            | 2         | 2      | 0.58%   |
| Netac               | 2         | 2      | 0.58%   |
| Mushkin             | 2         | 2      | 0.58%   |
| Hewlett-Packard     | 2         | 2      | 0.58%   |
| GOODRAM             | 2         | 2      | 0.58%   |
| Drevo               | 2         | 2      | 0.58%   |
| ASMT                | 2         | 4      | 0.58%   |
| Zheino              | 1         | 1      | 0.29%   |
| USB3.0              | 1         | 1      | 0.29%   |
| TO Exter            | 1         | 1      | 0.29%   |
| TCSUNBOW            | 1         | 1      | 0.29%   |
| SUNEAST             | 1         | 2      | 0.29%   |
| Seagate             | 1         | 1      | 0.29%   |
| Pioneer             | 1         | 1      | 0.29%   |
| OWC                 | 1         | 1      | 0.29%   |
| Londisk             | 1         | 1      | 0.29%   |
| Lexar               | 1         | 1      | 0.29%   |
| LDLC                | 1         | 1      | 0.29%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.29%   |
| Kingmax             | 1         | 1      | 0.29%   |
| KingDian            | 1         | 1      | 0.29%   |
| Kingchuxing         | 1         | 2      | 0.29%   |
| INNOVATION IT       | 1         | 1      | 0.29%   |
| Gigabyte Technology | 1         | 3      | 0.29%   |
| EXBOM               | 1         | 1      | 0.29%   |
| Dogfish             | 1         | 2      | 0.29%   |
| ASMedia             | 1         | 1      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 485       | 596    | 44.29%  |
| SSD     | 325       | 424    | 29.68%  |
| NVMe    | 185       | 225    | 16.89%  |
| MMC     | 81        | 98     | 7.4%    |
| Unknown | 19        | 22     | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 744       | 988    | 70.72%  |
| NVMe | 183       | 222    | 17.4%   |
| MMC  | 81        | 98     | 7.7%    |
| SAS  | 44        | 57     | 4.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 577       | 736    | 72.03%  |
| 0.51-1.0   | 203       | 255    | 25.34%  |
| 1.01-2.0   | 17        | 19     | 2.12%   |
| 3.01-4.0   | 2         | 7      | 0.25%   |
| 4.01-10.0  | 1         | 2      | 0.12%   |
| 0          | 1         | 1      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 338       | 34.56%  |
| 251-500        | 269       | 27.51%  |
| 501-1000       | 133       | 13.6%   |
| 51-100         | 74        | 7.57%   |
| 21-50          | 60        | 6.13%   |
| 1-20           | 43        | 4.4%    |
| 1001-2000      | 37        | 3.78%   |
| 2001-3000      | 11        | 1.12%   |
| More than 3000 | 8         | 0.82%   |
| Unknown        | 5         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 428       | 42.29%  |
| 21-50          | 194       | 19.17%  |
| 101-250        | 146       | 14.43%  |
| 51-100         | 123       | 12.15%  |
| 251-500        | 70        | 6.92%   |
| 501-1000       | 30        | 2.96%   |
| 1001-2000      | 10        | 0.99%   |
| Unknown        | 5         | 0.49%   |
| More than 3000 | 3         | 0.3%    |
| 2001-3000      | 3         | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 4      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 3      | 4.17%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 3      | 2.78%   |
| Seagate ST9320325AS 320GB                           | 2         | 2      | 2.78%   |
| Hitachi HTS545050A7E380 500GB                       | 2         | 2      | 2.78%   |
| HGST HTS545050A7E680 500GB                          | 2         | 2      | 2.78%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1      | 1.39%   |
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 1      | 1.39%   |
| WDC WD1600BJKT-75F4T0 160GB                         | 1         | 1      | 1.39%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1      | 1.39%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 2      | 1.39%   |
| WDC WD10JPVT-08A1YT2 1TB                            | 1         | 1      | 1.39%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 1.39%   |
| Toshiba MK7575GSX 752GB                             | 1         | 1      | 1.39%   |
| Toshiba MK7559GSXP 752GB                            | 1         | 2      | 1.39%   |
| Toshiba MK5076GSX 500GB                             | 1         | 1      | 1.39%   |
| Toshiba MK5065GSX 500GB                             | 1         | 1      | 1.39%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 1.39%   |
| Toshiba MK3276GSX -63 320GB                         | 1         | 2      | 1.39%   |
| Toshiba MK3259GSXP 320GB                            | 1         | 1      | 1.39%   |
| Toshiba MK2552GSX 250GB                             | 1         | 1      | 1.39%   |
| SK hynix SC401 SATA 512GB SSD                       | 1         | 1      | 1.39%   |
| SK hynix SC308 SATA 512GB SSD                       | 1         | 1      | 1.39%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 1.39%   |
| Seagate ST980411ASG 80GB                            | 1         | 1      | 1.39%   |
| Seagate ST95005620AS 500GB                          | 1         | 1      | 1.39%   |
| Seagate ST9500423AS 500GB                           | 1         | 1      | 1.39%   |
| Seagate ST9500420ASG 500GB                          | 1         | 2      | 1.39%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 1.39%   |
| Seagate ST9320423AS 320GB                           | 1         | 1      | 1.39%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1         | 1      | 1.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 1.39%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 1.39%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 1.39%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 1.39%   |
| SanDisk SSD PLUS 480 GB                             | 1         | 1      | 1.39%   |
| Samsung Electronics SSD PM810 2.5 128GB             | 1         | 1      | 1.39%   |
| OCZ VERTEX3 256GB SSD                               | 1         | 1      | 1.39%   |
| OCZ AGILITY3 120GB SSD                              | 1         | 1      | 1.39%   |
| Mushkin MKNSSDCR480GB-7-A                           | 1         | 1      | 1.39%   |
| Micron Technology MTFDDAV256TBN-1AR1ZABHA 256GB SSD | 1         | 1      | 1.39%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD      | 1         | 1      | 1.39%   |
| LDLC SSD 480GB                                      | 1         | 1      | 1.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 1.39%   |
| Intel SSDPEKKW256G7 256GB                           | 1         | 1      | 1.39%   |
| Hitachi HTS725050A9A364 500GB                       | 1         | 1      | 1.39%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 1.39%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 1.39%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 1.39%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 1.39%   |
| HGST HTS721010A9E630 1TB                            | 1         | 2      | 1.39%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 1.39%   |
| Fujitsu MHZ2320BH G2 320GB                          | 1         | 1      | 1.39%   |
| Fujitsu MHZ2320BH G1 320GB                          | 1         | 1      | 1.39%   |
| Fujitsu MHZ2160BJ FFS G2 160GB                      | 1         | 2      | 1.39%   |
| Fujitsu MHY2250BH 250GB                             | 1         | 1      | 1.39%   |
| Crucial CT120M500SSD1 120GB                         | 1         | 1      | 1.39%   |
| China SSD 120GB                                     | 1         | 1      | 1.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 23     | 30.56%  |
| Toshiba             | 11        | 14     | 15.28%  |
| Hitachi             | 7         | 7      | 9.72%   |
| WDC                 | 6         | 7      | 8.33%   |
| HGST                | 4         | 5      | 5.56%   |
| Fujitsu             | 4         | 5      | 5.56%   |
| SK hynix            | 3         | 3      | 4.17%   |
| OCZ                 | 2         | 2      | 2.78%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| A-DATA Technology   | 2         | 3      | 2.78%   |
| SanDisk             | 1         | 1      | 1.39%   |
| Samsung Electronics | 1         | 1      | 1.39%   |
| Mushkin             | 1         | 1      | 1.39%   |
| LDLC                | 1         | 1      | 1.39%   |
| Kingston            | 1         | 1      | 1.39%   |
| Intel               | 1         | 1      | 1.39%   |
| Crucial             | 1         | 1      | 1.39%   |
| China               | 1         | 1      | 1.39%   |
| Apple               | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 22        | 23     | 40.74%  |
| Toshiba | 11        | 14     | 20.37%  |
| Hitachi | 7         | 7      | 12.96%  |
| WDC     | 6         | 7      | 11.11%  |
| HGST    | 4         | 5      | 7.41%   |
| Fujitsu | 4         | 5      | 7.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 61     | 75%     |
| SSD  | 16        | 17     | 22.22%  |
| NVMe | 2         | 2      | 2.78%   |

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
| Detected | 614       | 910    | 62.34%  |
| Works    | 299       | 375    | 30.36%  |
| Malfunc  | 72        | 80     | 7.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 684       | 68.33%  |
| AMD                              | 128       | 12.79%  |
| Samsung Electronics              | 60        | 5.99%   |
| SanDisk                          | 36        | 3.6%    |
| SK hynix                         | 19        | 1.9%    |
| KIOXIA                           | 11        | 1.1%    |
| Toshiba America Info Systems     | 10        | 1%      |
| Nvidia                           | 10        | 1%      |
| Kingston Technology Company      | 7         | 0.7%    |
| Silicon Integrated Systems [SiS] | 6         | 0.6%    |
| Micron Technology                | 6         | 0.6%    |
| Phison Electronics               | 5         | 0.5%    |
| VIA Technologies                 | 3         | 0.3%    |
| Silicon Motion                   | 3         | 0.3%    |
| Apple                            | 3         | 0.3%    |
| Silicon Image                    | 2         | 0.2%    |
| Realtek Semiconductor            | 2         | 0.2%    |
| Unknown                          | 1         | 0.1%    |
| Union Memory (Shenzhen)          | 1         | 0.1%    |
| Seagate Technology               | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| JMicron Technology               | 1         | 0.1%    |
| ADATA Technology                 | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 91        | 8.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 88        | 7.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 62        | 5.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 58        | 5.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 55        | 4.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 55        | 4.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 49        | 4.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 45        | 3.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 37        | 3.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 35        | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 30        | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 29        | 2.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 22        | 1.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 21        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 20        | 1.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 19        | 1.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 18        | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 15        | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 15        | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 14        | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 12        | 1.06%   |
| Samsung NVMe SSD Controller 980                                                        | 12        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 11        | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 11        | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 10        | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 10        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 10        | 0.88%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 8         | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 8         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 8         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 8         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                  | 7         | 0.62%   |
| Intel SSD 660P Series                                                                  | 7         | 0.62%   |
| Intel Non-Volatile memory controller                                                   | 7         | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 7         | 0.62%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 7         | 0.62%   |
| AMD SB600 IDE                                                                          | 7         | 0.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 6         | 0.53%   |
| SK hynix Gold P31 SSD                                                                  | 6         | 0.53%   |
| SanDisk Non-Volatile memory controller                                                 | 6         | 0.53%   |
| Micron Non-Volatile memory controller                                                  | 6         | 0.53%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 6         | 0.53%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 6         | 0.53%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 6         | 0.53%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 5         | 0.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 5         | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 0.44%   |
| Phison E12 NVMe Controller                                                             | 5         | 0.44%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 5         | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 5         | 0.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 5         | 0.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 5         | 0.44%   |
| AMD IXP SB4x0 IDE Controller                                                           | 5         | 0.44%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 4         | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 0.35%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 4         | 0.35%   |
| Intel SSD 600P Series                                                                  | 4         | 0.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 0.35%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 696       | 64.21%  |
| NVMe | 179       | 16.51%  |
| IDE  | 138       | 12.73%  |
| RAID | 71        | 6.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 784       | 82.7%   |
| AMD          | 163       | 17.19%  |
| CentaurHauls | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz               | 13        | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 11        | 1.16%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 11        | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 10        | 1.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 10        | 1.05%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 10        | 1.05%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 10        | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 9         | 0.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 9         | 0.95%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz            | 9         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 9         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 8         | 0.84%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 8         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 8         | 0.84%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 8         | 0.84%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 8         | 0.84%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 7         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 7         | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 7         | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 7         | 0.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 7         | 0.74%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 7         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 7         | 0.74%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 7         | 0.74%   |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 7         | 0.74%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz            | 7         | 0.74%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 7         | 0.74%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 7         | 0.74%   |
| Intel Atom CPU Z3735F @ 1.33GHz                 | 7         | 0.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 7         | 0.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 7         | 0.74%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 7         | 0.74%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 6         | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 6         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 6         | 0.63%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 6         | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 6         | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 6         | 0.63%   |
| Intel Core i5-3340M CPU @ 2.70GHz               | 6         | 0.63%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 6         | 0.63%   |
| Intel Core i3-2330M CPU @ 2.20GHz               | 6         | 0.63%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz            | 6         | 0.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 6         | 0.63%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 6         | 0.63%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 6         | 0.63%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz     | 5         | 0.53%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 5         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 5         | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 5         | 0.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 5         | 0.53%   |
| Intel Core i5 CPU M 540 @ 2.53GHz               | 5         | 0.53%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 5         | 0.53%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 5         | 0.53%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 5         | 0.53%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 5         | 0.53%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 4         | 0.42%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 4         | 0.42%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz          | 4         | 0.42%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz          | 4         | 0.42%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 4         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 203       | 21.39%  |
| Intel Core i7                  | 176       | 18.55%  |
| Intel Core i3                  | 90        | 9.48%   |
| Intel Core 2 Duo               | 86        | 9.06%   |
| Intel Celeron                  | 69        | 7.27%   |
| Intel Atom                     | 37        | 3.9%    |
| Other                          | 32        | 3.37%   |
| Intel Pentium                  | 31        | 3.27%   |
| AMD Ryzen 5                    | 20        | 2.11%   |
| Intel Pentium Dual-Core        | 16        | 1.69%   |
| AMD Ryzen 7                    | 15        | 1.58%   |
| Intel Pentium Dual             | 14        | 1.48%   |
| AMD A6                         | 14        | 1.48%   |
| Intel Core 2                   | 13        | 1.37%   |
| AMD E1                         | 12        | 1.26%   |
| AMD A8                         | 12        | 1.26%   |
| AMD Turion 64 X2 Mobile        | 9         | 0.95%   |
| AMD Ryzen 7 PRO                | 9         | 0.95%   |
| AMD E                          | 8         | 0.84%   |
| AMD A4                         | 8         | 0.84%   |
| AMD E2                         | 7         | 0.74%   |
| Intel Genuine                  | 6         | 0.63%   |
| Intel Pentium Silver           | 5         | 0.53%   |
| AMD A10                        | 5         | 0.53%   |
| AMD Ryzen 3                    | 4         | 0.42%   |
| AMD C-60                       | 4         | 0.42%   |
| AMD Athlon                     | 4         | 0.42%   |
| Intel Core i9                  | 3         | 0.32%   |
| AMD Turion 64 Mobile           | 3         | 0.32%   |
| Intel Core m7                  | 2         | 0.21%   |
| Intel Core m5                  | 2         | 0.21%   |
| Intel Celeron Dual-Core        | 2         | 0.21%   |
| AMD Turion                     | 2         | 0.21%   |
| AMD Sempron                    | 2         | 0.21%   |
| AMD C-50                       | 2         | 0.21%   |
| AMD Athlon X2                  | 2         | 0.21%   |
| AMD Athlon II                  | 2         | 0.21%   |
| Intel Xeon                     | 1         | 0.11%   |
| Intel Core m3                  | 1         | 0.11%   |
| Intel Core M                   | 1         | 0.11%   |
| Intel Celeron M                | 1         | 0.11%   |
| CentaurHauls VIA Nano          | 1         | 0.11%   |
| AMD V120                       | 1         | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.11%   |
| AMD Turion II                  | 1         | 0.11%   |
| AMD Turion Dual-Core           | 1         | 0.11%   |
| AMD Ryzen 9                    | 1         | 0.11%   |
| AMD Ryzen 5 PRO                | 1         | 0.11%   |
| AMD Ryzen 3 PRO                | 1         | 0.11%   |
| AMD PRO A10                    | 1         | 0.11%   |
| AMD Mobile Sempron             | 1         | 0.11%   |
| AMD C-70                       | 1         | 0.11%   |
| AMD C-30                       | 1         | 0.11%   |
| AMD Athlon II Dual-Core        | 1         | 0.11%   |
| AMD Athlon 64 X2               | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 587       | 61.92%  |
| 4      | 268       | 28.27%  |
| 1      | 36        | 3.8%    |
| 6      | 32        | 3.38%   |
| 8      | 24        | 2.53%   |
| 14     | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 948       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 578       | 60.97%  |
| 1      | 370       | 39.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 948       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 9.55%   |
| 0x206a7    | 86        | 8.93%   |
| 0x306a9    | 82        | 8.52%   |
| 0x6fd      | 44        | 4.57%   |
| 0x1067a    | 44        | 4.57%   |
| 0x20655    | 37        | 3.84%   |
| 0x306c3    | 30        | 3.12%   |
| 0x806ea    | 28        | 2.91%   |
| 0x406e3    | 27        | 2.8%    |
| 0x30678    | 27        | 2.8%    |
| 0x40651    | 26        | 2.7%    |
| 0x306d4    | 23        | 2.39%   |
| 0x806ec    | 22        | 2.28%   |
| 0x10676    | 22        | 2.28%   |
| 0x20652    | 21        | 2.18%   |
| 0x806e9    | 20        | 2.08%   |
| 0x406c4    | 18        | 1.87%   |
| 0x05000119 | 18        | 1.87%   |
| 0x806c1    | 17        | 1.77%   |
| 0xa0652    | 16        | 1.66%   |
| 0x906ea    | 14        | 1.45%   |
| 0x706a1    | 13        | 1.35%   |
| 0x706e5    | 12        | 1.25%   |
| 0x6f6      | 12        | 1.25%   |
| 0x106ca    | 12        | 1.25%   |
| 0x08108109 | 12        | 1.25%   |
| 0x07030105 | 12        | 1.25%   |
| 0x406c3    | 11        | 1.14%   |
| 0x08108102 | 11        | 1.14%   |
| 0x906e9    | 10        | 1.04%   |
| 0x0700010f | 10        | 1.04%   |
| 0x6fb      | 8         | 0.83%   |
| 0x906ed    | 7         | 0.73%   |
| 0x03000027 | 7         | 0.73%   |
| 0x6fa      | 6         | 0.62%   |
| 0x0810100b | 6         | 0.62%   |
| 0x706a8    | 5         | 0.52%   |
| 0x506e3    | 5         | 0.52%   |
| 0x506c9    | 5         | 0.52%   |
| 0x10661    | 5         | 0.52%   |
| 0x08600106 | 5         | 0.52%   |
| 0x06001119 | 5         | 0.52%   |
| 0x05000029 | 5         | 0.52%   |
| 0x806eb    | 4         | 0.42%   |
| 0x806d1    | 4         | 0.42%   |
| 0x30661    | 4         | 0.42%   |
| 0x0a50000c | 4         | 0.42%   |
| 0x02000057 | 4         | 0.42%   |
| 0x010000c8 | 4         | 0.42%   |
| 0x106e5    | 3         | 0.31%   |
| 0x08608103 | 3         | 0.31%   |
| 0x08600103 | 3         | 0.31%   |
| 0x07030106 | 3         | 0.31%   |
| 0x06006705 | 3         | 0.31%   |
| 0x02000032 | 3         | 0.31%   |
| 0x0a50000b | 2         | 0.21%   |
| 0x08200103 | 2         | 0.21%   |
| 0x08101007 | 2         | 0.21%   |
| 0x06006704 | 2         | 0.21%   |
| 0x06006110 | 2         | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 121       | 12.75%  |
| SandyBridge      | 89        | 9.38%   |
| IvyBridge        | 84        | 8.85%   |
| Core             | 76        | 8.01%   |
| Penryn           | 71        | 7.48%   |
| Westmere         | 64        | 6.74%   |
| Haswell          | 63        | 6.64%   |
| Silvermont       | 58        | 6.11%   |
| Skylake          | 35        | 3.69%   |
| Zen+             | 24        | 2.53%   |
| Bobcat           | 24        | 2.53%   |
| Broadwell        | 23        | 2.42%   |
| TigerLake        | 20        | 2.11%   |
| Goldmont plus    | 19        | 2%      |
| IceLake          | 18        | 1.9%    |
| Puma             | 17        | 1.79%   |
| CometLake        | 17        | 1.79%   |
| Bonnell          | 17        | 1.79%   |
| K8 Hammer        | 16        | 1.69%   |
| Zen 2            | 12        | 1.26%   |
| Zen              | 11        | 1.16%   |
| Jaguar           | 11        | 1.16%   |
| Excavator        | 11        | 1.16%   |
| Piledriver       | 7         | 0.74%   |
| K8 & K10 hybrid  | 7         | 0.74%   |
| K10 Llano        | 7         | 0.74%   |
| Zen 3            | 6         | 0.63%   |
| K10              | 5         | 0.53%   |
| Goldmont         | 5         | 0.53%   |
| Unknown          | 5         | 0.53%   |
| Nehalem          | 3         | 0.32%   |
| Steamroller      | 2         | 0.21%   |
| Alderlake Hybrid | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 690       | 60.42%  |
| Nvidia                           | 224       | 19.61%  |
| AMD                              | 222       | 19.44%  |
| VIA Technologies                 | 3         | 0.26%   |
| Silicon Integrated Systems [SiS] | 3         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 6.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 79        | 6.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 4.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 4.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 37        | 3.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 37        | 3.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 2.59%   |
| Intel UHD Graphics 620                                                                   | 30        | 2.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 2.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 2.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26        | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 1.92%   |
| Intel HD Graphics 620                                                                    | 19        | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 1.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 1.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.42%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 1.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.09%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 12        | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 1%      |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 12        | 1%      |
| AMD Renoir                                                                               | 12        | 1%      |
| Intel HD Graphics 630                                                                    | 11        | 0.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 11        | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.84%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 10        | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 0.75%   |
| Nvidia TU117M                                                                            | 7         | 0.59%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 7         | 0.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.5%    |
| Nvidia GT218M [GeForce 310M]                                                             | 6         | 0.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 0.5%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 0.5%    |
| AMD Wrestler [Radeon HD 7310]                                                            | 6         | 0.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.5%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 0.5%    |
| AMD Cezanne                                                                              | 6         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.42%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 5         | 0.42%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 5         | 0.42%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 5         | 0.42%   |
| Intel HD Graphics 500                                                                    | 5         | 0.42%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.42%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 5         | 0.42%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 5         | 0.42%   |
| Nvidia GT218M [NVS 3100M]                                                                | 4         | 0.33%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.33%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.33%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.33%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.33%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.33%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 4         | 0.33%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 4         | 0.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.33%   |
| Intel HD Graphics 530                                                                    | 4         | 0.33%   |
| Intel HD Graphics 515                                                                    | 4         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 506       | 53.38%  |
| 1 x AMD        | 163       | 17.19%  |
| Intel + Nvidia | 145       | 15.3%   |
| 1 x Nvidia     | 69        | 7.28%   |
| Intel + AMD    | 38        | 4.01%   |
| 2 x AMD        | 11        | 1.16%   |
| AMD + Nvidia   | 10        | 1.05%   |
| 1 x VIA        | 3         | 0.32%   |
| 1 x SiS        | 3         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 812       | 85.2%   |
| Proprietary | 110       | 11.54%  |
| Unknown     | 31        | 3.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 577       | 60.36%  |
| 0.01-0.5   | 159       | 16.63%  |
| 1.01-2.0   | 87        | 9.1%    |
| 0.51-1.0   | 72        | 7.53%   |
| 3.01-4.0   | 40        | 4.18%   |
| 5.01-6.0   | 12        | 1.26%   |
| 7.01-8.0   | 6         | 0.63%   |
| 2.01-3.0   | 2         | 0.21%   |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 196       | 18.92%  |
| LG Display              | 174       | 16.8%   |
| Samsung Electronics     | 143       | 13.8%   |
| Chimei Innolux          | 113       | 10.91%  |
| BOE                     | 96        | 9.27%   |
| Chi Mei Optoelectronics | 44        | 4.25%   |
| Lenovo                  | 33        | 3.19%   |
| LG Philips              | 24        | 2.32%   |
| Apple                   | 19        | 1.83%   |
| Goldstar                | 17        | 1.64%   |
| Dell                    | 17        | 1.64%   |
| Sharp                   | 14        | 1.35%   |
| Hewlett-Packard         | 13        | 1.25%   |
| InfoVision              | 11        | 1.06%   |
| HannStar                | 10        | 0.97%   |
| PANDA                   | 8         | 0.77%   |
| Acer                    | 8         | 0.77%   |
| Ancor Communications    | 7         | 0.68%   |
| Toshiba                 | 6         | 0.58%   |
| Iiyama                  | 5         | 0.48%   |
| BenQ                    | 5         | 0.48%   |
| Sony                    | 4         | 0.39%   |
| Philips                 | 4         | 0.39%   |
| LPL                     | 4         | 0.39%   |
| LGD                     | 4         | 0.39%   |
| CPT                     | 4         | 0.39%   |
| ViewSonic               | 3         | 0.29%   |
| Panasonic               | 3         | 0.29%   |
| Nvidia                  | 3         | 0.29%   |
| Fujitsu Siemens         | 3         | 0.29%   |
| CSO                     | 3         | 0.29%   |
| AOC                     | 3         | 0.29%   |
| Vizio                   | 2         | 0.19%   |
| MStar                   | 2         | 0.19%   |
| Lenovo Group Limited    | 2         | 0.19%   |
| InnoLux Display         | 2         | 0.19%   |
| Vestel Elektronik       | 1         | 0.1%    |
| Unknown (XXX)           | 1         | 0.1%    |
| UMC                     | 1         | 0.1%    |
| Sun                     | 1         | 0.1%    |
| SLD                     | 1         | 0.1%    |
| SKY                     | 1         | 0.1%    |
| Seiko/Epson             | 1         | 0.1%    |
| SDC                     | 1         | 0.1%    |
| Sceptre Tech            | 1         | 0.1%    |
| Quanta Display          | 1         | 0.1%    |
| OEM                     | 1         | 0.1%    |
| NSO                     | 1         | 0.1%    |
| NEC Computers           | 1         | 0.1%    |
| MTD                     | 1         | 0.1%    |
| MS_ Nvidia              | 1         | 0.1%    |
| MSI                     | 1         | 0.1%    |
| Medion                  | 1         | 0.1%    |
| Matrox                  | 1         | 0.1%    |
| LNG                     | 1         | 0.1%    |
| KDC                     | 1         | 0.1%    |
| IBM                     | 1         | 0.1%    |
| HRG                     | 1         | 0.1%    |
| GKK                     | 1         | 0.1%    |
| DENON                   | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 10        | 0.96%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 8         | 0.77%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 8         | 0.77%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.77%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.67%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.57%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.57%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.48%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 5         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 4         | 0.38%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.38%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 4         | 0.38%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 4         | 0.38%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 4         | 0.38%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO229E 1920x1080 309x174mm 14.0-inch           | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.38%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 4         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 3         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 3         | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.29%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch                 | 3         | 0.29%   |
| LPL LCD Monitor 1440x900                                                 | 3         | 0.29%   |
| LG Philips LP154WX4-TLAB LPL3D01 1280x800 331x207mm 15.4-inch            | 3         | 0.29%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch              | 3         | 0.29%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.29%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 3         | 0.29%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 3         | 0.29%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.29%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 3         | 0.29%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.29%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 3         | 0.29%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 370       | 37.07%  |
| 1920x1080 (FHD)    | 316       | 31.66%  |
| 1280x800 (WXGA)    | 85        | 8.52%   |
| 1600x900 (HD+)     | 66        | 6.61%   |
| 1440x900 (WXGA+)   | 43        | 4.31%   |
| 3840x2160 (4K)     | 30        | 3.01%   |
| 1680x1050 (WSXGA+) | 14        | 1.4%    |
| 1024x600           | 13        | 1.3%    |
| 2560x1440 (QHD)    | 11        | 1.1%    |
| 1920x1200 (WUXGA)  | 9         | 0.9%    |
| 1280x1024 (SXGA)   | 8         | 0.8%    |
| 2560x1600          | 4         | 0.4%    |
| 1360x768           | 4         | 0.4%    |
| 3200x1800 (QHD+)   | 3         | 0.3%    |
| 2880x1800          | 3         | 0.3%    |
| 3840x2400          | 2         | 0.2%    |
| 2560x1080          | 2         | 0.2%    |
| 2288x1287          | 2         | 0.2%    |
| 1920x540           | 2         | 0.2%    |
| 1024x768 (XGA)     | 2         | 0.2%    |
| 3840x1200          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 2304x1440          | 1         | 0.1%    |
| 1920x1280          | 1         | 0.1%    |
| 1680x945           | 1         | 0.1%    |
| 1600x1200          | 1         | 0.1%    |
| 1280x768           | 1         | 0.1%    |
| 1280x720 (HD)      | 1         | 0.1%    |
| 1024x576           | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 416       | 39.96%  |
| 14      | 151       | 14.51%  |
| 13      | 129       | 12.39%  |
| 17      | 89        | 8.55%   |
| 12      | 31        | 2.98%   |
| 24      | 29        | 2.79%   |
| 11      | 27        | 2.59%   |
| Unknown | 25        | 2.4%    |
| 21      | 21        | 2.02%   |
| 27      | 20        | 1.92%   |
| 10      | 15        | 1.44%   |
| 23      | 13        | 1.25%   |
| 18      | 13        | 1.25%   |
| 19      | 10        | 0.96%   |
| 22      | 8         | 0.77%   |
| 31      | 7         | 0.67%   |
| 16      | 6         | 0.58%   |
| 54      | 5         | 0.48%   |
| 84      | 3         | 0.29%   |
| 25      | 3         | 0.29%   |
| 72      | 2         | 0.19%   |
| 52      | 2         | 0.19%   |
| 40      | 2         | 0.19%   |
| 34      | 2         | 0.19%   |
| 32      | 2         | 0.19%   |
| 26      | 2         | 0.19%   |
| 20      | 2         | 0.19%   |
| 57      | 1         | 0.1%    |
| 48      | 1         | 0.1%    |
| 47      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 8       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 629       | 60.83%  |
| 201-300     | 130       | 12.57%  |
| 351-400     | 109       | 10.54%  |
| 501-600     | 61        | 5.9%    |
| 401-500     | 45        | 4.35%   |
| Unknown     | 25        | 2.42%   |
| 601-700     | 11        | 1.06%   |
| 1001-1500   | 10        | 0.97%   |
| 1501-2000   | 5         | 0.48%   |
| 701-800     | 4         | 0.39%   |
| 801-900     | 3         | 0.29%   |
| 101-200     | 1         | 0.1%    |
| 901-1000    | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 739       | 79.12%  |
| 16/10   | 154       | 16.49%  |
| Unknown | 20        | 2.14%   |
| 5/4     | 7         | 0.75%   |
| 3/2     | 5         | 0.54%   |
| 4/3     | 4         | 0.43%   |
| 21/9    | 2         | 0.21%   |
| 32/9    | 1         | 0.11%   |
| 3.20    | 1         | 0.11%   |
| 0.62    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 415       | 39.94%  |
| 81-90          | 232       | 22.33%  |
| 121-130        | 71        | 6.83%   |
| 201-250        | 60        | 5.77%   |
| 71-80          | 45        | 4.33%   |
| 61-70          | 31        | 2.98%   |
| 51-60          | 27        | 2.6%    |
| Unknown        | 25        | 2.41%   |
| 301-350        | 21        | 2.02%   |
| 131-140        | 18        | 1.73%   |
| 151-200        | 16        | 1.54%   |
| 41-50          | 15        | 1.44%   |
| More than 1000 | 13        | 1.25%   |
| 141-150        | 12        | 1.15%   |
| 351-500        | 11        | 1.06%   |
| 251-300        | 11        | 1.06%   |
| 501-1000       | 6         | 0.58%   |
| 91-100         | 5         | 0.48%   |
| 111-120        | 4         | 0.38%   |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 407       | 39.9%   |
| 121-160       | 331       | 32.45%  |
| 51-100        | 189       | 18.53%  |
| 161-240       | 40        | 3.92%   |
| Unknown       | 25        | 2.45%   |
| More than 240 | 15        | 1.47%   |
| 1-50          | 13        | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 805       | 83.25%  |
| 2     | 126       | 13.03%  |
| 0     | 26        | 2.69%   |
| 3     | 9         | 0.93%   |
| 4     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 486       | 31.66%  |
| Intel                             | 447       | 29.12%  |
| Qualcomm Atheros                  | 249       | 16.22%  |
| Broadcom                          | 140       | 9.12%   |
| Marvell Technology Group          | 34        | 2.21%   |
| Broadcom Limited                  | 26        | 1.69%   |
| Ralink                            | 20        | 1.3%    |
| TP-Link                           | 12        | 0.78%   |
| Samsung Electronics               | 11        | 0.72%   |
| Ralink Technology                 | 11        | 0.72%   |
| JMicron Technology                | 11        | 0.72%   |
| Nvidia                            | 9         | 0.59%   |
| Sierra Wireless                   | 7         | 0.46%   |
| MediaTek                          | 6         | 0.39%   |
| Ericsson Business Mobile Networks | 6         | 0.39%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.33%   |
| Huawei Technologies               | 5         | 0.33%   |
| Xiaomi                            | 4         | 0.26%   |
| Qualcomm Atheros Communications   | 4         | 0.26%   |
| Attansic Technology               | 4         | 0.26%   |
| Lenovo                            | 3         | 0.2%    |
| Fibocom                           | 3         | 0.2%    |
| DisplayLink                       | 3         | 0.2%    |
| Dell                              | 3         | 0.2%    |
| ASIX Electronics                  | 3         | 0.2%    |
| VIA Technologies                  | 2         | 0.13%   |
| Motorola PCS                      | 2         | 0.13%   |
| Edimax Technology                 | 2         | 0.13%   |
| AMD                               | 2         | 0.13%   |
| ZyDAS                             | 1         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.07%   |
| TRENDnet                          | 1         | 0.07%   |
| Toshiba                           | 1         | 0.07%   |
| Qualcomm                          | 1         | 0.07%   |
| Novatek Microelectronics          | 1         | 0.07%   |
| NetGear                           | 1         | 0.07%   |
| Linksys                           | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |
| HTC (High Tech Computer)          | 1         | 0.07%   |
| Hewlett-Packard                   | 1         | 0.07%   |
| AVM                               | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |
| Aquantia                          | 1         | 0.07%   |
| Apple                             | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 269       | 14.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 129       | 6.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 51        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 38        | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 1.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 1.67%   |
| Intel Wireless 8265 / 8275                                              | 31        | 1.67%   |
| Intel Wireless 7260                                                     | 30        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 30        | 1.61%   |
| Intel Wireless 7265                                                     | 25        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 1.29%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 1.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 19        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 17        | 0.91%   |
| Intel 82577LM Gigabit Network Connection                                | 17        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 0.86%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 0.81%   |
| Intel Ethernet Connection I217-LM                                       | 15        | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 0.75%   |
| Intel Wireless-AC 9260                                                  | 14        | 0.75%   |
| Intel Wireless 8260                                                     | 14        | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 0.75%   |
| Intel 82567LM Gigabit Network Connection                                | 14        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 13        | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 0.7%    |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.65%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.65%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 11        | 0.59%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 11        | 0.59%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 10        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 10        | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.54%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.54%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 10        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 9         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 9         | 0.48%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 9         | 0.48%   |
| Intel WiFi Link 5100                                                    | 9         | 0.48%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                                   | 9         | 0.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 0.48%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 9         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 8         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 8         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 8         | 0.43%   |
| Intel Wireless 3165                                                     | 8         | 0.43%   |
| Intel Wireless 3160                                                     | 8         | 0.43%   |
| Intel Ultimate N WiFi Link 5300                                         | 8         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 424       | 43.76%  |
| Qualcomm Atheros                | 215       | 22.19%  |
| Realtek Semiconductor           | 149       | 15.38%  |
| Broadcom                        | 99        | 10.22%  |
| Ralink                          | 20        | 2.06%   |
| Broadcom Limited                | 12        | 1.24%   |
| Ralink Technology               | 11        | 1.14%   |
| TP-Link                         | 10        | 1.03%   |
| Sierra Wireless                 | 7         | 0.72%   |
| Qualcomm Atheros Communications | 4         | 0.41%   |
| MediaTek                        | 4         | 0.41%   |
| Fibocom                         | 3         | 0.31%   |
| Edimax Technology               | 2         | 0.21%   |
| ZyDAS                           | 1         | 0.1%    |
| TRENDnet                        | 1         | 0.1%    |
| Qualcomm                        | 1         | 0.1%    |
| NetGear                         | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| Hewlett-Packard                 | 1         | 0.1%    |
| Dell                            | 1         | 0.1%    |
| AVM                             | 1         | 0.1%    |
| ASUSTek Computer                | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 43        | 4.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 4.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 38        | 3.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 3.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 3.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 3.16%   |
| Intel Wireless 8265 / 8275                                              | 31        | 3.16%   |
| Intel Wireless 7260                                                     | 30        | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 30        | 3.06%   |
| Intel Wireless 7265                                                     | 25        | 2.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 2.45%   |
| Intel Wi-Fi 6 AX200                                                     | 20        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.94%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 19        | 1.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 17        | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.63%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.63%   |
| Intel Wi-Fi 6 AX201                                                     | 15        | 1.53%   |
| Intel Wireless-AC 9260                                                  | 14        | 1.43%   |
| Intel Wireless 8260                                                     | 14        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 13        | 1.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 13        | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.33%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 1.22%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 1.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 11        | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 10        | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 10        | 1.02%   |
| Intel WiFi Link 5100                                                    | 9         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.92%   |
| Intel Wireless 3165                                                     | 8         | 0.82%   |
| Intel Wireless 3160                                                     | 8         | 0.82%   |
| Intel Ultimate N WiFi Link 5300                                         | 8         | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.61%   |
| Intel Centrino Wireless-N 100                                           | 6         | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 0.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 6         | 0.61%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 6         | 0.61%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 6         | 0.61%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.51%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 5         | 0.51%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 5         | 0.51%   |
| Realtek 802.11n WLAN Adapter                                            | 5         | 0.51%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 0.51%   |
| Broadcom BCM43225 802.11b/g/n                                           | 5         | 0.51%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.41%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 429       | 50.12%  |
| Intel                            | 193       | 22.55%  |
| Qualcomm Atheros                 | 63        | 7.36%   |
| Broadcom                         | 56        | 6.54%   |
| Marvell Technology Group         | 34        | 3.97%   |
| Broadcom Limited                 | 14        | 1.64%   |
| Samsung Electronics              | 11        | 1.29%   |
| JMicron Technology               | 11        | 1.29%   |
| Nvidia                           | 9         | 1.05%   |
| Silicon Integrated Systems [SiS] | 5         | 0.58%   |
| Xiaomi                           | 4         | 0.47%   |
| Attansic Technology              | 4         | 0.47%   |
| MediaTek                         | 3         | 0.35%   |
| Lenovo                           | 3         | 0.35%   |
| DisplayLink                      | 3         | 0.35%   |
| ASIX Electronics                 | 3         | 0.35%   |
| VIA Technologies                 | 2         | 0.23%   |
| TP-Link                          | 2         | 0.23%   |
| Motorola PCS                     | 2         | 0.23%   |
| Huawei Technologies              | 2         | 0.23%   |
| LG Electronics                   | 1         | 0.12%   |
| Aquantia                         | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 269       | 31.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 129       | 15%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 51        | 5.93%   |
| Intel 82577LM Gigabit Network Connection                                       | 17        | 1.98%   |
| Intel Ethernet Connection I217-LM                                              | 15        | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 1.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 14        | 1.63%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 11        | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 10        | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 9         | 1.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 9         | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 9         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 8         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 8         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                           | 8         | 0.93%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 8         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.81%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 6         | 0.7%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.7%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 6         | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 6         | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.7%    |
| Intel Ethernet Connection (10) I219-V                                          | 6         | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.58%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 5         | 0.58%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.58%   |
| Intel 82566MM Gigabit Network Connection                                       | 5         | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 5         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 4         | 0.47%   |
| Intel PRO/100 VE Network Connection                                            | 4         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 0.47%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 4         | 0.47%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.47%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 4         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.35%   |
| Nvidia MCP51 Ethernet Controller                                               | 3         | 0.35%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.35%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 3         | 0.35%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.35%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.35%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 0.35%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.35%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.35%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 0.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.23%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.23%   |
| Realtek Realtek Ethernet controller                                            | 2         | 0.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.23%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 921       | 52.21%  |
| Ethernet | 825       | 46.77%  |
| Modem    | 18        | 1.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 774       | 78.26%  |
| Ethernet | 215       | 21.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 776       | 81.6%   |
| 1     | 143       | 15.04%  |
| 0     | 27        | 2.84%   |
| 3     | 5         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 820       | 84.8%   |
| Yes  | 147       | 15.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 249       | 40.55%  |
| Qualcomm Atheros Communications | 72        | 11.73%  |
| Realtek Semiconductor           | 60        | 9.77%   |
| Broadcom                        | 57        | 9.28%   |
| Lite-On Technology              | 25        | 4.07%   |
| IMC Networks                    | 25        | 4.07%   |
| Dell                            | 23        | 3.75%   |
| Foxconn / Hon Hai               | 19        | 3.09%   |
| Hewlett-Packard                 | 18        | 2.93%   |
| Cambridge Silicon Radio         | 16        | 2.61%   |
| Apple                           | 16        | 2.61%   |
| Ralink                          | 10        | 1.63%   |
| Toshiba                         | 8         | 1.3%    |
| Chicony Electronics             | 3         | 0.49%   |
| Alps Electric                   | 3         | 0.49%   |
| Realtek                         | 2         | 0.33%   |
| Integrated System Solution      | 2         | 0.33%   |
| Taiyo Yuden                     | 1         | 0.16%   |
| Ralink Technology               | 1         | 0.16%   |
| Qcom                            | 1         | 0.16%   |
| MediaTek                        | 1         | 0.16%   |
| Foxconn International           | 1         | 0.16%   |
| ASUSTek Computer                | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 110       | 17.89%  |
| Intel AX201 Bluetooth                                                               | 43        | 6.99%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 37        | 6.02%   |
| Realtek Bluetooth Radio                                                             | 30        | 4.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 28        | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 22        | 3.58%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 22        | 3.58%   |
| Intel AX200 Bluetooth                                                               | 19        | 3.09%   |
| Intel Bluetooth Device                                                              | 18        | 2.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 16        | 2.6%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 14        | 2.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 11        | 1.79%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 1.63%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 9         | 1.46%   |
| Lite-On Bluetooth Device                                                            | 9         | 1.46%   |
| IMC Networks Bluetooth Device                                                       | 9         | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 8         | 1.3%    |
| Apple Bluetooth Host Controller                                                     | 8         | 1.3%    |
| Realtek RTL8723B Bluetooth                                                          | 7         | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 1.14%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.98%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.98%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 6         | 0.98%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.81%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 5         | 0.81%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 5         | 0.81%   |
| Intel AX210 Bluetooth                                                               | 4         | 0.65%   |
| Dell Wireless 360 Bluetooth                                                         | 4         | 0.65%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.65%   |
| Broadcom HP Portable Valentine                                                      | 4         | 0.65%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.65%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.65%   |
| Broadcom BCM2045 Bluetooth                                                          | 4         | 0.65%   |
| Toshiba Integrated Bluetooth HCI                                                    | 3         | 0.49%   |
| IMC Networks Bluetooth                                                              | 3         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.49%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.49%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 3         | 0.49%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.49%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.49%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.33%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.33%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.33%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.33%   |
| IMC Networks Bluetooth USB Host Controller                                          | 2         | 0.33%   |
| IMC Networks Bluetooth module                                                       | 2         | 0.33%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.33%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.33%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.33%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 0.33%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.33%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 749       | 67.24%  |
| AMD                              | 182       | 16.34%  |
| Nvidia                           | 112       | 10.05%  |
| C-Media Electronics              | 9         | 0.81%   |
| Logitech                         | 8         | 0.72%   |
| Silicon Integrated Systems [SiS] | 6         | 0.54%   |
| GN Netcom                        | 5         | 0.45%   |
| Realtek Semiconductor            | 4         | 0.36%   |
| Lenovo                           | 4         | 0.36%   |
| VIA Technologies                 | 3         | 0.27%   |
| Sennheiser Communications        | 3         | 0.27%   |
| Plantronics                      | 3         | 0.27%   |
| Generalplus Technology           | 3         | 0.27%   |
| Texas Instruments                | 2         | 0.18%   |
| Focusrite-Novation               | 2         | 0.18%   |
| ZOOM                             | 1         | 0.09%   |
| XMOS                             | 1         | 0.09%   |
| Textech International            | 1         | 0.09%   |
| TEAC                             | 1         | 0.09%   |
| QinHeng Electronics              | 1         | 0.09%   |
| PreSonus Audio Electronics       | 1         | 0.09%   |
| Native Instruments               | 1         | 0.09%   |
| KORG                             | 1         | 0.09%   |
| Elite Silicon                    | 1         | 0.09%   |
| Earth Computer Technologies      | 1         | 0.09%   |
| Digidesign                       | 1         | 0.09%   |
| Dell                             | 1         | 0.09%   |
| Creative Technology              | 1         | 0.09%   |
| Corsair                          | 1         | 0.09%   |
| Cambridge Silicon Radio          | 1         | 0.09%   |
| BEHRINGER International          | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |
| AKAI Professional M.I.           | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 104       | 7.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 83        | 6.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 69        | 5.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 67        | 5.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 63        | 4.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 56        | 4.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 56        | 4.21%   |
| AMD FCH Azalia Controller                                                                         | 54        | 4.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 32        | 2.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 32        | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 32        | 2.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 32        | 2.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 31        | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 2.33%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 30        | 2.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 1.73%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 22        | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 19        | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 1.43%   |
| AMD Wrestler HDMI Audio                                                                           | 18        | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 17        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 1.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 12        | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 7         | 0.53%   |
| AMD High Definition Audio Controller                                                              | 7         | 0.53%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 7         | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.45%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 0.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.38%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5         | 0.38%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.38%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.38%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 0.38%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.3%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.3%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 0.3%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.3%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 0.23%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.23%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.23%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.23%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.23%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 3         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 148       | 26.96%  |
| SK hynix                                         | 118       | 21.49%  |
| Unknown                                          | 71        | 12.93%  |
| Micron Technology                                | 58        | 10.56%  |
| Kingston                                         | 52        | 9.47%   |
| Ramaxel Technology                               | 17        | 3.1%    |
| Elpida                                           | 16        | 2.91%   |
| Crucial                                          | 16        | 2.91%   |
| A-DATA Technology                                | 9         | 1.64%   |
| Unknown (ABCD)                                   | 7         | 1.28%   |
| Smart                                            | 6         | 1.09%   |
| Nanya Technology                                 | 5         | 0.91%   |
| Goodram                                          | 4         | 0.73%   |
| Corsair                                          | 4         | 0.73%   |
| G.Skill                                          | 3         | 0.55%   |
| Teikon                                           | 2         | 0.36%   |
| V-GeN                                            | 1         | 0.18%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.18%   |
| Unknown (0x0043415455000000)                     | 1         | 0.18%   |
| Unifosa                                          | 1         | 0.18%   |
| Transcend                                        | 1         | 0.18%   |
| Smart Brazil                                     | 1         | 0.18%   |
| SHARETRONIC                                      | 1         | 0.18%   |
| Patriot                                          | 1         | 0.18%   |
| Memox                                            | 1         | 0.18%   |
| Avant                                            | 1         | 0.18%   |
| ASint Technology                                 | 1         | 0.18%   |
| Apacer                                           | 1         | 0.18%   |
| Unknown                                          | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 1.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 8         | 1.37%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 7         | 1.19%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 1.19%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.19%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 6         | 1.02%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.02%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 5         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 5         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 5         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.85%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 4         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.68%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.68%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.68%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.68%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                   | 3         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 3         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.51%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.51%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 3         | 0.51%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 0.51%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 3         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.51%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.51%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 3         | 0.51%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.51%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.51%   |
| Unknown RAM Module 8192MB SODIMM LPDDR3 1600MT/s                 | 2         | 0.34%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 2         | 0.34%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.34%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.34%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 2         | 0.34%   |
| SK hynix RAM HYMP112S64CP6-Y5 1024MB SODIMM DDR2 667MT/s         | 2         | 0.34%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.34%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 198       | 41.86%  |
| DDR4    | 182       | 38.48%  |
| DDR2    | 46        | 9.73%   |
| LPDDR4  | 15        | 3.17%   |
| LPDDR3  | 13        | 2.75%   |
| SDRAM   | 12        | 2.54%   |
| Unknown | 4         | 0.85%   |
| DRAM    | 2         | 0.42%   |
| DDR     | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 439       | 93.6%   |
| Row Of Chips | 23        | 4.9%    |
| Chip         | 4         | 0.85%   |
| DIMM         | 2         | 0.43%   |
| Unknown      | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 185       | 35.99%  |
| 8192  | 154       | 29.96%  |
| 2048  | 92        | 17.9%   |
| 16384 | 46        | 8.95%   |
| 1024  | 26        | 5.06%   |
| 32768 | 10        | 1.95%   |
| 512   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 125       | 25.25%  |
| 2667    | 103       | 20.81%  |
| 3200    | 50        | 10.1%   |
| 2400    | 35        | 7.07%   |
| 1334    | 35        | 7.07%   |
| 667     | 32        | 6.46%   |
| 1333    | 28        | 5.66%   |
| 2133    | 15        | 3.03%   |
| Unknown | 13        | 2.63%   |
| 1067    | 11        | 2.22%   |
| 4199    | 9         | 1.82%   |
| 800     | 9         | 1.82%   |
| 3266    | 8         | 1.62%   |
| 1066    | 5         | 1.01%   |
| 4267    | 4         | 0.81%   |
| 1867    | 3         | 0.61%   |
| 1866    | 3         | 0.61%   |
| 2048    | 2         | 0.4%    |
| 975     | 2         | 0.4%    |
| 533     | 2         | 0.4%    |
| 8400    | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 4         | 30.77%  |
| Canon                 | 3         | 23.08%  |
| Brother Industries    | 2         | 15.38%  |
| Seiko Epson           | 1         | 7.69%   |
| Prolific Technology   | 1         | 7.69%   |
| Lexmark International | 1         | 7.69%   |
| Kyocera               | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson L220 Series         | 1         | 7.69%   |
| Prolific PL2305 Parallel Port   | 1         | 7.69%   |
| Lexmark International E360d     | 1         | 7.69%   |
| Kyocera Mita FS-920             | 1         | 7.69%   |
| HP LaserJet P1005               | 1         | 7.69%   |
| HP LaserJet 1320                | 1         | 7.69%   |
| HP DeskJet F2100 Printer series | 1         | 7.69%   |
| HP DeskJet 3700 series          | 1         | 7.69%   |
| Canon TS3300 series             | 1         | 7.69%   |
| Canon LBP6230/6240              | 1         | 7.69%   |
| Canon LBP6000                   | 1         | 7.69%   |
| Brother MFC-L2710DW series      | 1         | 7.69%   |
| Brother HL-L2320D series        | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 50%     |
| HP ScanJet 3570c                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 237       | 29.19%  |
| IMC Networks                           | 65        | 8%      |
| Realtek Semiconductor                  | 59        | 7.27%   |
| Microdia                               | 58        | 7.14%   |
| Acer                                   | 57        | 7.02%   |
| Sunplus Innovation Technology          | 47        | 5.79%   |
| Suyin                                  | 44        | 5.42%   |
| Cheng Uei Precision Industry (Foxlink) | 32        | 3.94%   |
| Quanta                                 | 27        | 3.33%   |
| Lite-On Technology                     | 25        | 3.08%   |
| Apple                                  | 20        | 2.46%   |
| Alcor Micro                            | 18        | 2.22%   |
| Silicon Motion                         | 17        | 2.09%   |
| Syntek                                 | 16        | 1.97%   |
| Ricoh                                  | 15        | 1.85%   |
| Samsung Electronics                    | 9         | 1.11%   |
| Lenovo                                 | 8         | 0.99%   |
| Logitech                               | 7         | 0.86%   |
| Importek                               | 6         | 0.74%   |
| ALi                                    | 5         | 0.62%   |
| Z-Star Microelectronics                | 4         | 0.49%   |
| OmniVision Technologies                | 4         | 0.49%   |
| Luxvisions Innotech Limited            | 4         | 0.49%   |
| DigiTech                               | 4         | 0.49%   |
| Primax Electronics                     | 3         | 0.37%   |
| GEMBIRD                                | 3         | 0.37%   |
| Sunplus Technology                     | 2         | 0.25%   |
| icSpring                               | 2         | 0.25%   |
| Genesys Logic                          | 2         | 0.25%   |
| Unknown                                | 1         | 0.12%   |
| Tobii AB                               | 1         | 0.12%   |
| Sonix Technology                       | 1         | 0.12%   |
| Novatek Microelectronics               | 1         | 0.12%   |
| Microsoft                              | 1         | 0.12%   |
| Magic Control Technology               | 1         | 0.12%   |
| MacroSilicon                           | 1         | 0.12%   |
| Intel                                  | 1         | 0.12%   |
| Generalplus Technology                 | 1         | 0.12%   |
| DJJHNA29IE70D3                         | 1         | 0.12%   |
| Creative Technology                    | 1         | 0.12%   |
| ARC International                      | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 37        | 4.53%   |
| Realtek Integrated_Webcam_HD                                   | 17        | 2.08%   |
| Chicony USB 2.0 Camera                                         | 16        | 1.96%   |
| Microdia Integrated_Webcam_HD                                  | 15        | 1.84%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 1.84%   |
| IMC Networks Integrated Camera                                 | 14        | 1.71%   |
| Sunplus Integrated_Webcam_HD                                   | 12        | 1.47%   |
| Chicony TOSHIBA Web Camera - HD                                | 12        | 1.47%   |
| Chicony HP Truevision HD                                       | 12        | 1.47%   |
| Chicony HD WebCam                                              | 11        | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 11        | 1.35%   |
| Acer Lenovo EasyCamera                                         | 11        | 1.35%   |
| Lite-On Integrated Camera                                      | 10        | 1.22%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 10        | 1.22%   |
| Samsung Galaxy A5 (MTP)                                        | 9         | 1.1%    |
| Microdia Integrated Webcam                                     | 9         | 1.1%    |
| Lite-On HP HD Camera                                           | 9         | 1.1%    |
| Acer Integrated Camera                                         | 9         | 1.1%    |
| Syntek Lenovo EasyCamera                                       | 8         | 0.98%   |
| Suyin HP Truevision HD                                         | 8         | 0.98%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 8         | 0.98%   |
| Chicony Lenovo EasyCamera                                      | 8         | 0.98%   |
| Alcor Micro USB 2.0 PC cam                                     | 8         | 0.98%   |
| Chicony USB2.0 Camera                                          | 7         | 0.86%   |
| Chicony Integrated Camera (1280x720@30)                        | 7         | 0.86%   |
| Acer HD Webcam                                                 | 7         | 0.86%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 6         | 0.73%   |
| Quanta HP TrueVision HD Camera                                 | 6         | 0.73%   |
| IMC Networks UVC VGA Webcam                                    | 6         | 0.73%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 6         | 0.73%   |
| Acer BisonCam, NB Pro                                          | 6         | 0.73%   |
| Sunplus HD WebCam                                              | 5         | 0.61%   |
| Sunplus ASUS USB2.0 Webcam                                     | 5         | 0.61%   |
| Quanta HP Webcam                                               | 5         | 0.61%   |
| Chicony WebCam                                                 | 5         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 0.61%   |
| Chicony HP HD Webcam [Fixed]                                   | 5         | 0.61%   |
| Chicony HP HD Webcam                                           | 5         | 0.61%   |
| Chicony HP HD Camera                                           | 5         | 0.61%   |
| Chicony FJ Camera                                              | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 5         | 0.61%   |
| Apple Built-in iSight                                          | 5         | 0.61%   |
| Syntek Integrated Camera                                       | 4         | 0.49%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 4         | 0.49%   |
| Suyin Acer CrystalEye Webcam                                   | 4         | 0.49%   |
| Suyin 1.3M HD WebCam                                           | 4         | 0.49%   |
| Realtek USB Camera                                             | 4         | 0.49%   |
| Realtek Lenovo EasyCamera                                      | 4         | 0.49%   |
| Realtek Integrated Webcam HD                                   | 4         | 0.49%   |
| Realtek HP Truevision HD integrated webcam                     | 4         | 0.49%   |
| Realtek Acer 640 x 480 laptop camera                           | 4         | 0.49%   |
| OmniVision OV2640 Webcam                                       | 4         | 0.49%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 4         | 0.49%   |
| Microdia Dell Integrated HD Webcam                             | 4         | 0.49%   |
| IMC Networks USB Camera                                        | 4         | 0.49%   |
| IMC Networks Integrated Webcam                                 | 4         | 0.49%   |
| Chicony Webcam-101                                             | 4         | 0.49%   |
| Chicony VGA Webcam                                             | 4         | 0.49%   |
| Chicony HP TrueVision HD Camera                                | 4         | 0.49%   |
| Chicony HD WebCam (Asus N-series)                              | 4         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 70        | 41.67%  |
| Synaptics                  | 34        | 20.24%  |
| AuthenTec                  | 29        | 17.26%  |
| Upek                       | 10        | 5.95%   |
| Shenzhen Goodix Technology | 9         | 5.36%   |
| LighTuning Technology      | 7         | 4.17%   |
| STMicroelectronics         | 6         | 3.57%   |
| Elan Microelectronics      | 3         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 10.71%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 8.93%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.36%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 5.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 5.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.76%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 4.76%   |
| AuthenTec AES2810                                                          | 8         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 4.17%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 4.17%   |
| Validity Sensors VFS491                                                    | 6         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.57%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 3.57%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 3.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.38%   |
| AuthenTec AES1600                                                          | 4         | 2.38%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.79%   |
| Unknown                                                                    | 3         | 1.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.19%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.19%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.19%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.6%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.6%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.6%    |
| Synaptics WBDI Device                                                      | 1         | 0.6%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.6%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.6%    |
| Elan ELAN:ARM-M4                                                           | 1         | 0.6%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 33        | 35.87%  |
| Alcor Micro              | 25        | 27.17%  |
| O2 Micro                 | 15        | 16.3%   |
| Upek                     | 8         | 8.7%    |
| Lenovo                   | 8         | 8.7%    |
| Reiner SCT Kartensysteme | 1         | 1.09%   |
| OmniKey                  | 1         | 1.09%   |
| C3PO                     | 1         | 1.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 27.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 15.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 14.13%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 8         | 8.7%    |
| Broadcom 5880                                                                | 8         | 8.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 7.61%   |
| Broadcom 58200                                                               | 5         | 5.43%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 1.09%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 1.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.09%   |
| C3PO USB SMART CARD READER                                                   | 1         | 1.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 629       | 65.45%  |
| 1     | 271       | 28.2%   |
| 2     | 51        | 5.31%   |
| 3     | 6         | 0.62%   |
| 4     | 2         | 0.21%   |
| 10    | 1         | 0.1%    |
| 6     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 168       | 41.28%  |
| Chipcard                 | 88        | 21.62%  |
| Graphics card            | 56        | 13.76%  |
| Net/wireless             | 33        | 8.11%   |
| Bluetooth                | 13        | 3.19%   |
| Camera                   | 12        | 2.95%   |
| Card reader              | 10        | 2.46%   |
| Storage                  | 9         | 2.21%   |
| Flash memory             | 5         | 1.23%   |
| Net/ethernet             | 3         | 0.74%   |
| Multimedia controller    | 3         | 0.74%   |
| Communication controller | 3         | 0.74%   |
| Sound                    | 2         | 0.49%   |
| Network                  | 1         | 0.25%   |
| Modem                    | 1         | 0.25%   |

