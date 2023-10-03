Linux in South Africa - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Africa.

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

Total: 966

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-55              | [e6d8dfa4a1](https://linux-hardware.org/?probe=e6d8dfa4a1) | Sep 29, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [3847c20962](https://linux-hardware.org/?probe=3847c20962) | Sep 21, 2023 |
| HP            | ProBook 450 G1              | [4e5ae95013](https://linux-hardware.org/?probe=4e5ae95013) | Sep 20, 2023 |
| Dell          | Inspiron 16 5620            | [0f12c482a1](https://linux-hardware.org/?probe=0f12c482a1) | Sep 20, 2023 |
| Lenovo        | ThinkPad T570 20H90011ZA    | [f59a257ab5](https://linux-hardware.org/?probe=f59a257ab5) | Sep 14, 2023 |
| Dell          | Inspiron 16 5620            | [4de6e83768](https://linux-hardware.org/?probe=4de6e83768) | Sep 11, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [d3d6e283d0](https://linux-hardware.org/?probe=d3d6e283d0) | Sep 10, 2023 |
| Dell          | Latitude E6330              | [2a3c06d056](https://linux-hardware.org/?probe=2a3c06d056) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [2fc59172dd](https://linux-hardware.org/?probe=2fc59172dd) | Sep 09, 2023 |
| Apple         | MacBookPro9,2               | [f3bdad3061](https://linux-hardware.org/?probe=f3bdad3061) | Sep 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e65692f205](https://linux-hardware.org/?probe=e65692f205) | Sep 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [d4335c9520](https://linux-hardware.org/?probe=d4335c9520) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d627b8c625](https://linux-hardware.org/?probe=d627b8c625) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [54930549e6](https://linux-hardware.org/?probe=54930549e6) | Aug 28, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [d0f87a58ec](https://linux-hardware.org/?probe=d0f87a58ec) | Aug 23, 2023 |
| HP            | 250 G7 Notebook PC          | [cb4da51551](https://linux-hardware.org/?probe=cb4da51551) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Dell          | Latitude 5490               | [058fba578a](https://linux-hardware.org/?probe=058fba578a) | Aug 20, 2023 |
| Dell          | Latitude E6330              | [7e196f2365](https://linux-hardware.org/?probe=7e196f2365) | Aug 19, 2023 |
| Dell          | Latitude D630               | [e8f61a39e7](https://linux-hardware.org/?probe=e8f61a39e7) | Aug 17, 2023 |
| Dell          | G3 3579                     | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [b99e595bfc](https://linux-hardware.org/?probe=b99e595bfc) | Aug 12, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [1fa34106f1](https://linux-hardware.org/?probe=1fa34106f1) | Aug 11, 2023 |
| Dell          | G3 3590                     | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| Dell          | Precision 7740              | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [779c23fe06](https://linux-hardware.org/?probe=779c23fe06) | Aug 05, 2023 |
| Acer          | Nitro AN515-55              | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| Lenovo        | V510-15IKB 80WQ             | [a3ff56579a](https://linux-hardware.org/?probe=a3ff56579a) | Aug 03, 2023 |
| Dell          | G3 3590                     | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell          | G3 3590                     | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Toshiba       | Satellite C850-F74T         | [7756db419e](https://linux-hardware.org/?probe=7756db419e) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | [b464dbd11c](https://linux-hardware.org/?probe=b464dbd11c) | Jul 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [3f4e603493](https://linux-hardware.org/?probe=3f4e603493) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Dell          | Inspiron 15-3567            | [b84e3b9a04](https://linux-hardware.org/?probe=b84e3b9a04) | Jul 19, 2023 |
| CONNEX        | L1415-BAY                   | [8f5663e9c8](https://linux-hardware.org/?probe=8f5663e9c8) | Jul 18, 2023 |
| Dell          | Latitude E6410              | [78131f9d4b](https://linux-hardware.org/?probe=78131f9d4b) | Jul 14, 2023 |
| Dell          | Latitude E6530              | [25cbd87821](https://linux-hardware.org/?probe=25cbd87821) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8890be41ec](https://linux-hardware.org/?probe=8890be41ec) | Jul 10, 2023 |
| HP            | ProBook 455 G6              | [f4b853f43e](https://linux-hardware.org/?probe=f4b853f43e) | Jul 01, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Acer          | Aspire A315-58              | [faff66ca26](https://linux-hardware.org/?probe=faff66ca26) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| HP            | ProBook 450 G1              | [cadc656340](https://linux-hardware.org/?probe=cadc656340) | Jun 25, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | Aspire V5-471G              | [f82fbc50e3](https://linux-hardware.org/?probe=f82fbc50e3) | Jun 20, 2023 |
| Dell          | XPS 17 9710                 | [d5ac5e48ce](https://linux-hardware.org/?probe=d5ac5e48ce) | Jun 18, 2023 |
| Lenovo        | ThinkPad T430 2349S33       | [c8c46af444](https://linux-hardware.org/?probe=c8c46af444) | Jun 18, 2023 |
| I-Life Dig... | ZED Air Plus                | [c8bb1a5e0e](https://linux-hardware.org/?probe=c8bb1a5e0e) | Jun 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e2357f72af](https://linux-hardware.org/?probe=e2357f72af) | Jun 17, 2023 |
| Proline       | V1165C4                     | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude 5490               | [1e6933ec61](https://linux-hardware.org/?probe=1e6933ec61) | Jun 13, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | [f9bc4694e4](https://linux-hardware.org/?probe=f9bc4694e4) | May 28, 2023 |
| Lenovo        | ThinkPad T560 20FJS0CX00    | [cf7d5b7149](https://linux-hardware.org/?probe=cf7d5b7149) | May 27, 2023 |
| Toshiba       | Satellite Pro C650          | [50fc04b16c](https://linux-hardware.org/?probe=50fc04b16c) | May 25, 2023 |
| Acer          | Aspire V3-731               | [d07d017c32](https://linux-hardware.org/?probe=d07d017c32) | May 24, 2023 |
| Lenovo        | ThinkPad X250 20CLS65E00    | [e65932f3a9](https://linux-hardware.org/?probe=e65932f3a9) | May 23, 2023 |
| HP            | Pavilion 15                 | [7afbe545bc](https://linux-hardware.org/?probe=7afbe545bc) | May 21, 2023 |
| Apple         | MacBookPro15,1              | [438d9b5e18](https://linux-hardware.org/?probe=438d9b5e18) | May 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [1fdf5742d0](https://linux-hardware.org/?probe=1fdf5742d0) | May 21, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [36d4349090](https://linux-hardware.org/?probe=36d4349090) | May 20, 2023 |
| Dell          | Latitude E6530              | [632b8094e3](https://linux-hardware.org/?probe=632b8094e3) | May 15, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [1e7e92e7e8](https://linux-hardware.org/?probe=1e7e92e7e8) | May 15, 2023 |
| Dell          | Latitude E6520              | [e4d8abe098](https://linux-hardware.org/?probe=e4d8abe098) | May 15, 2023 |
| Dell          | Latitude E6520              | [78aaf99b7b](https://linux-hardware.org/?probe=78aaf99b7b) | May 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [afde593648](https://linux-hardware.org/?probe=afde593648) | May 10, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [1d74519195](https://linux-hardware.org/?probe=1d74519195) | May 04, 2023 |
| Dell          | Latitude E6400              | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [4cd1484039](https://linux-hardware.org/?probe=4cd1484039) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [0796e35c73](https://linux-hardware.org/?probe=0796e35c73) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Acer          | AOHAPPY                     | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| Acer          | Aspire A315-54K             | [4c3d8d685a](https://linux-hardware.org/?probe=4c3d8d685a) | Apr 20, 2023 |
| Dell          | Latitude E5510              | [7e57f9e0f0](https://linux-hardware.org/?probe=7e57f9e0f0) | Apr 20, 2023 |
| Dell          | Latitude E5510              | [08e03aa4d8](https://linux-hardware.org/?probe=08e03aa4d8) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| Dell          | Latitude E6330              | [936f8f8810](https://linux-hardware.org/?probe=936f8f8810) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Dell          | Latitude 3510               | [48fe09d0a3](https://linux-hardware.org/?probe=48fe09d0a3) | Apr 12, 2023 |
| Dell          | Latitude 3510               | [582f6705cb](https://linux-hardware.org/?probe=582f6705cb) | Apr 12, 2023 |
| Dell          | Vostro 2521                 | [fdb9903ab4](https://linux-hardware.org/?probe=fdb9903ab4) | Apr 09, 2023 |
| HP            | Victus by Gaming Laptop ... | [6ad0f579b6](https://linux-hardware.org/?probe=6ad0f579b6) | Apr 05, 2023 |
| ASUSTek       | E201NA                      | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| HP            | EliteBook 2540p             | [6aae8ca2a0](https://linux-hardware.org/?probe=6aae8ca2a0) | Mar 30, 2023 |
| Clevo         | W150HNM/W170HN              | [8a86bbf31c](https://linux-hardware.org/?probe=8a86bbf31c) | Mar 29, 2023 |
| Apple         | MacBook5,1                  | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| Dell          | XPS L421X                   | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [2ab659150c](https://linux-hardware.org/?probe=2ab659150c) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [96f3739077](https://linux-hardware.org/?probe=96f3739077) | Mar 15, 2023 |
| Acer          | Swift SF114-34              | [aee5d96875](https://linux-hardware.org/?probe=aee5d96875) | Mar 14, 2023 |
| Dell          | G15 5510                    | [fa6a50c541](https://linux-hardware.org/?probe=fa6a50c541) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5c45eb6864](https://linux-hardware.org/?probe=5c45eb6864) | Mar 12, 2023 |
| Proline       | V146SH                      | [460deab2ea](https://linux-hardware.org/?probe=460deab2ea) | Mar 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [53649dddb6](https://linux-hardware.org/?probe=53649dddb6) | Mar 10, 2023 |
| HP            | ProBook 4530s               | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Latitude E7470              | [51b40c1604](https://linux-hardware.org/?probe=51b40c1604) | Mar 09, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [5b98ac00da](https://linux-hardware.org/?probe=5b98ac00da) | Mar 09, 2023 |
| Lenovo        | ThinkPad T500 2241BU3       | [6cd14d1366](https://linux-hardware.org/?probe=6cd14d1366) | Mar 08, 2023 |
| Lenovo        | ThinkPad T500 2241BU3       | [da7eb1619d](https://linux-hardware.org/?probe=da7eb1619d) | Mar 07, 2023 |
| HP            | 620                         | [d272a54b5d](https://linux-hardware.org/?probe=d272a54b5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [0f0f44b0ee](https://linux-hardware.org/?probe=0f0f44b0ee) | Mar 05, 2023 |
| HP            | ProBook 4540s               | [a52b9c7637](https://linux-hardware.org/?probe=a52b9c7637) | Feb 27, 2023 |
| HP            | ProBook 4540s               | [45e989b539](https://linux-hardware.org/?probe=45e989b539) | Feb 27, 2023 |
| HP            | 620                         | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude 5490               | [ccde867e7d](https://linux-hardware.org/?probe=ccde867e7d) | Feb 24, 2023 |
| HP            | ProBook 4540s               | [079a5f512d](https://linux-hardware.org/?probe=079a5f512d) | Feb 20, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [fcbec20556](https://linux-hardware.org/?probe=fcbec20556) | Feb 17, 2023 |
| Lenovo        | ThinkPad T410 25376B8       | [fc0430b8fe](https://linux-hardware.org/?probe=fc0430b8fe) | Feb 14, 2023 |
| Lenovo        | ThinkPad Edge 057872G       | [98ed3bb274](https://linux-hardware.org/?probe=98ed3bb274) | Feb 13, 2023 |
| Lenovo        | ThinkPad P51 20HH0002ZA     | [db1061d4db](https://linux-hardware.org/?probe=db1061d4db) | Feb 07, 2023 |
| Getac         | S410G4                      | [81b80297ab](https://linux-hardware.org/?probe=81b80297ab) | Feb 06, 2023 |
| Getac         | S410G4                      | [1d8e6ad383](https://linux-hardware.org/?probe=1d8e6ad383) | Feb 06, 2023 |
| Lenovo        | G50-80 80E5                 | [baf04bdc65](https://linux-hardware.org/?probe=baf04bdc65) | Feb 05, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cfaa43cc81](https://linux-hardware.org/?probe=cfaa43cc81) | Feb 04, 2023 |
| HP            | EliteBook 840 G1            | [9b91cecab9](https://linux-hardware.org/?probe=9b91cecab9) | Jan 31, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a69331d2ea](https://linux-hardware.org/?probe=a69331d2ea) | Jan 27, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | [a0c1ab03da](https://linux-hardware.org/?probe=a0c1ab03da) | Jan 27, 2023 |
| Dell          | Latitude E6430              | [ac467a864d](https://linux-hardware.org/?probe=ac467a864d) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | [c4a4bd6895](https://linux-hardware.org/?probe=c4a4bd6895) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4c6da4840e](https://linux-hardware.org/?probe=4c6da4840e) | Jan 23, 2023 |
| HP            | Pavilion dv6                | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| HP            | Pavilion dv6                | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion dv6                | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Acer          | Aspire ES1-533              | [96f20a9e2f](https://linux-hardware.org/?probe=96f20a9e2f) | Jan 18, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| Acer          | Aspire A515-52              | [217353eb32](https://linux-hardware.org/?probe=217353eb32) | Jan 13, 2023 |
| Dell          | G7 7790                     | [bdaed261a4](https://linux-hardware.org/?probe=bdaed261a4) | Jan 12, 2023 |
| Panasonic     | CF-19ADNAXDY                | [a3b2e995a5](https://linux-hardware.org/?probe=a3b2e995a5) | Jan 08, 2023 |
| HP            | 255 G5 Notebook PC          | [69969b5a27](https://linux-hardware.org/?probe=69969b5a27) | Jan 07, 2023 |
| HP            | Laptop 15-da0xxx            | [5905bea3a2](https://linux-hardware.org/?probe=5905bea3a2) | Jan 06, 2023 |
| HP            | ProBook 450 G0              | [eb2116c5e2](https://linux-hardware.org/?probe=eb2116c5e2) | Jan 03, 2023 |
| Acer          | Aspire R7-572G              | [56e5de8317](https://linux-hardware.org/?probe=56e5de8317) | Jan 03, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ceb89aefed](https://linux-hardware.org/?probe=ceb89aefed) | Dec 30, 2022 |
| Acer          | Aspire A315-53              | [9c28036440](https://linux-hardware.org/?probe=9c28036440) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | ZBook Fury 16 G9 Mobile ... | [6c67e1435e](https://linux-hardware.org/?probe=6c67e1435e) | Dec 29, 2022 |
| HP            | G62                         | [05ad917600](https://linux-hardware.org/?probe=05ad917600) | Dec 28, 2022 |
| HP            | Compaq CQ58                 | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| Dell          | Inspiron 15 7510            | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| Dell          | MXG071                      | [b999ae7bba](https://linux-hardware.org/?probe=b999ae7bba) | Dec 19, 2022 |
| Dell          | MXG071                      | [587b5fb932](https://linux-hardware.org/?probe=587b5fb932) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [9768b1fe82](https://linux-hardware.org/?probe=9768b1fe82) | Dec 16, 2022 |
| MECER         | CA11Q5_PRO                  | [b8d784f0ef](https://linux-hardware.org/?probe=b8d784f0ef) | Dec 16, 2022 |
| MECER         | CA11Q5_PRO                  | [e2e6c34fde](https://linux-hardware.org/?probe=e2e6c34fde) | Dec 16, 2022 |
| Apple         | MacBookAir7,1               | [facc218586](https://linux-hardware.org/?probe=facc218586) | Dec 15, 2022 |
| LG Electro... | C500                        | [078e13cadd](https://linux-hardware.org/?probe=078e13cadd) | Dec 08, 2022 |
| Panasonic     | CF-19ADNAXDY                | [51120805b1](https://linux-hardware.org/?probe=51120805b1) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | [7a809e9dbd](https://linux-hardware.org/?probe=7a809e9dbd) | Dec 02, 2022 |
| Standard      | Unknown                     | [723d9c3551](https://linux-hardware.org/?probe=723d9c3551) | Nov 30, 2022 |
| MECER         | YA13Q20-DP_PRO              | [c51a900a73](https://linux-hardware.org/?probe=c51a900a73) | Nov 23, 2022 |
| Apple         | MacBookAir7,1               | [f735b3e731](https://linux-hardware.org/?probe=f735b3e731) | Nov 23, 2022 |
| MECER         | YA13Q20-DP_PRO              | [81cdfb4100](https://linux-hardware.org/?probe=81cdfb4100) | Nov 20, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Unknown                     | [1a144cae82](https://linux-hardware.org/?probe=1a144cae82) | Nov 13, 2022 |
| Intel         | (R) Education Tablet        | [13286af46e](https://linux-hardware.org/?probe=13286af46e) | Nov 10, 2022 |
| RIZZEN        | NOVABOOK R40                | [84890252a6](https://linux-hardware.org/?probe=84890252a6) | Nov 10, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c62cbe8eb5](https://linux-hardware.org/?probe=c62cbe8eb5) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| Dell          | Latitude E6420              | [032920f109](https://linux-hardware.org/?probe=032920f109) | Nov 02, 2022 |
| Acer          | Aspire E1-571               | [d81e8b3ea2](https://linux-hardware.org/?probe=d81e8b3ea2) | Nov 01, 2022 |
| Dell          | Vostro 3500                 | [a3abf820e1](https://linux-hardware.org/?probe=a3abf820e1) | Oct 31, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| Dell          | Vostro 3500                 | [53754d84e7](https://linux-hardware.org/?probe=53754d84e7) | Oct 29, 2022 |
| HP            | Laptop 15-dw3xxx            | [99ac55823d](https://linux-hardware.org/?probe=99ac55823d) | Oct 29, 2022 |
| MSI           | GF63 Thin 10SC              | [2b22722ce8](https://linux-hardware.org/?probe=2b22722ce8) | Oct 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | [a5c7ddd00c](https://linux-hardware.org/?probe=a5c7ddd00c) | Oct 25, 2022 |
| Mustek        | Z140C                       | [9188dbd3a5](https://linux-hardware.org/?probe=9188dbd3a5) | Oct 23, 2022 |
| HP            | 2000                        | [6bb35d5fe9](https://linux-hardware.org/?probe=6bb35d5fe9) | Oct 21, 2022 |
| HP            | Unknown                     | [3b5effbcc5](https://linux-hardware.org/?probe=3b5effbcc5) | Oct 20, 2022 |
| LG Electro... | C500                        | [f688cc0536](https://linux-hardware.org/?probe=f688cc0536) | Oct 18, 2022 |
| Mustek        | Z140C                       | [02a81c2c1f](https://linux-hardware.org/?probe=02a81c2c1f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | [2a1c89201f](https://linux-hardware.org/?probe=2a1c89201f) | Oct 12, 2022 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | [e952835a2f](https://linux-hardware.org/?probe=e952835a2f) | Oct 12, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | [9f2e301993](https://linux-hardware.org/?probe=9f2e301993) | Oct 10, 2022 |
| HP            | Compaq 6710b (GB887EA#AC... | [af662698b9](https://linux-hardware.org/?probe=af662698b9) | Oct 10, 2022 |
| Intel         | (R) Education Tablet        | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [62e134c294](https://linux-hardware.org/?probe=62e134c294) | Oct 09, 2022 |
| Dell          | Latitude E5250              | [aeb221e727](https://linux-hardware.org/?probe=aeb221e727) | Oct 01, 2022 |
| Dell          | Latitude E5250              | [43f7cf1b59](https://linux-hardware.org/?probe=43f7cf1b59) | Oct 01, 2022 |
| Acer          | TMP453-MG                   | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [2ad6238f03](https://linux-hardware.org/?probe=2ad6238f03) | Sep 25, 2022 |
| ASUSTek       | X200MA                      | [753d8c4211](https://linux-hardware.org/?probe=753d8c4211) | Sep 24, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [b7f6ab8ad0](https://linux-hardware.org/?probe=b7f6ab8ad0) | Sep 23, 2022 |
| Toshiba       | Satellite C850-F21B         | [6d336c1e89](https://linux-hardware.org/?probe=6d336c1e89) | Sep 23, 2022 |
| Toshiba       | Satellite C850-F21B         | [dc1e853bbf](https://linux-hardware.org/?probe=dc1e853bbf) | Sep 23, 2022 |
| Dell          | Latitude E6540              | [d13fb4e622](https://linux-hardware.org/?probe=d13fb4e622) | Sep 19, 2022 |
| Dell          | Inspiron N5050              | [db02122f3d](https://linux-hardware.org/?probe=db02122f3d) | Sep 14, 2022 |
| MSI           | GP73 Leopard 8RE            | [21744558cb](https://linux-hardware.org/?probe=21744558cb) | Sep 12, 2022 |
| Dell          | XPS 17 9720                 | [b85068c001](https://linux-hardware.org/?probe=b85068c001) | Sep 07, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [758f8d2184](https://linux-hardware.org/?probe=758f8d2184) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6566bc7d09](https://linux-hardware.org/?probe=6566bc7d09) | Sep 01, 2022 |
| Acer          | TMP453-MG                   | [63efab9aef](https://linux-hardware.org/?probe=63efab9aef) | Aug 30, 2022 |
| HP            | EliteBook 840 G3            | [81b8b0400d](https://linux-hardware.org/?probe=81b8b0400d) | Aug 14, 2022 |
| Acer          | Aspire A315-53              | [d7550029db](https://linux-hardware.org/?probe=d7550029db) | Aug 12, 2022 |
| Intel         | (R) Education Tablet        | [a9b5863c1a](https://linux-hardware.org/?probe=a9b5863c1a) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dc6f7b4c01](https://linux-hardware.org/?probe=dc6f7b4c01) | Aug 09, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3a348c35e7](https://linux-hardware.org/?probe=3a348c35e7) | Aug 09, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0ad516c20b](https://linux-hardware.org/?probe=0ad516c20b) | Aug 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [2d4b30ec72](https://linux-hardware.org/?probe=2d4b30ec72) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Lenovo        | ThinkPad T540p 20BFA06P0... | [2f51f6572f](https://linux-hardware.org/?probe=2f51f6572f) | Aug 06, 2022 |
| Acer          | Aspire A315-53              | [0012f5d4c5](https://linux-hardware.org/?probe=0012f5d4c5) | Aug 01, 2022 |
| HP            | ProBook 4310s               | [d15b493637](https://linux-hardware.org/?probe=d15b493637) | Jul 31, 2022 |
| Acer          | Aspire A315-53              | [28b8a96420](https://linux-hardware.org/?probe=28b8a96420) | Jul 31, 2022 |
| HP            | Laptop 15-bs1xx             | [8fe6a402e7](https://linux-hardware.org/?probe=8fe6a402e7) | Jul 30, 2022 |
| Lenovo        | ThinkPad T540p 20BFA06P0... | [824d231d52](https://linux-hardware.org/?probe=824d231d52) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Dell          | Latitude E5450              | [b3e3c79dae](https://linux-hardware.org/?probe=b3e3c79dae) | Jul 22, 2022 |
| Dell          | Latitude E5450              | [c0e1145ccf](https://linux-hardware.org/?probe=c0e1145ccf) | Jul 21, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [69bd4cdcd9](https://linux-hardware.org/?probe=69bd4cdcd9) | Jul 19, 2022 |
| Acer          | TMP453-MG                   | [797f0ea7fe](https://linux-hardware.org/?probe=797f0ea7fe) | Jul 18, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [baa6fdeed9](https://linux-hardware.org/?probe=baa6fdeed9) | Jul 13, 2022 |
| MSI           | Prestige 14Evo A11M         | [292a5032e3](https://linux-hardware.org/?probe=292a5032e3) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| Dell          | Latitude E6500              | [e1ad93da4a](https://linux-hardware.org/?probe=e1ad93da4a) | Jul 11, 2022 |
| Dell          | Inspiron 3543               | [0a4fd044e4](https://linux-hardware.org/?probe=0a4fd044e4) | Jul 10, 2022 |
| MSI           | Prestige 14Evo A11M         | [670abf3d2b](https://linux-hardware.org/?probe=670abf3d2b) | Jul 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [274f459142](https://linux-hardware.org/?probe=274f459142) | Jul 07, 2022 |
| Dell          | Latitude E6400              | [1c5025c952](https://linux-hardware.org/?probe=1c5025c952) | Jul 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Acer          | Aspire A515-51G             | [4178b8c79f](https://linux-hardware.org/?probe=4178b8c79f) | Jun 28, 2022 |
| Acer          | Aspire A515-51G             | [1571a4ab8e](https://linux-hardware.org/?probe=1571a4ab8e) | Jun 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| HP            | Pavilion dv7                | [6338462156](https://linux-hardware.org/?probe=6338462156) | Jun 27, 2022 |
| Acer          | TMP453-MG                   | [e2790ebf7e](https://linux-hardware.org/?probe=e2790ebf7e) | Jun 23, 2022 |
| Acer          | TMP453-MG                   | [c99aceab3b](https://linux-hardware.org/?probe=c99aceab3b) | Jun 23, 2022 |
| Dell          | Latitude 5490               | [f0726860d4](https://linux-hardware.org/?probe=f0726860d4) | Jun 23, 2022 |
| Acer          | Swift SF314-54              | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Dell          | Latitude E6540              | [93f049609f](https://linux-hardware.org/?probe=93f049609f) | Jun 16, 2022 |
| Lenovo        | V15-IIL 82C5                | [bf09de57ad](https://linux-hardware.org/?probe=bf09de57ad) | Jun 14, 2022 |
| Intel         | (R) Education Tablet        | [a776aa706c](https://linux-hardware.org/?probe=a776aa706c) | Jun 13, 2022 |
| Intel         | (R) Education Tablet        | [8c47e36905](https://linux-hardware.org/?probe=8c47e36905) | Jun 13, 2022 |
| HP            | Laptop 15-bs0xx             | [a5474363da](https://linux-hardware.org/?probe=a5474363da) | Jun 12, 2022 |
| Lenovo        | E50-70 80JA                 | [2eb0d9bb23](https://linux-hardware.org/?probe=2eb0d9bb23) | Jun 11, 2022 |
| Lenovo        | E50-70 80JA                 | [1391106844](https://linux-hardware.org/?probe=1391106844) | Jun 10, 2022 |
| Dell          | Inspiron 3542               | [cf46fd5c4e](https://linux-hardware.org/?probe=cf46fd5c4e) | Jun 03, 2022 |
| Dell          | Inspiron 3542               | [94db4f10be](https://linux-hardware.org/?probe=94db4f10be) | Jun 03, 2022 |
| Dell          | G5 5590                     | [4e53892479](https://linux-hardware.org/?probe=4e53892479) | Jun 02, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [d0dbd3d75e](https://linux-hardware.org/?probe=d0dbd3d75e) | Jun 01, 2022 |
| Dell          | Latitude E6400              | [d70c53a9df](https://linux-hardware.org/?probe=d70c53a9df) | May 31, 2022 |
| Dell          | Vostro 5481                 | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Dell          | Latitude 3410               | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1eecb7a012](https://linux-hardware.org/?probe=1eecb7a012) | May 26, 2022 |
| HP            | 635                         | [79aa62cc98](https://linux-hardware.org/?probe=79aa62cc98) | May 25, 2022 |
| HP            | 635                         | [f97ec34a67](https://linux-hardware.org/?probe=f97ec34a67) | May 24, 2022 |
| LG Electro... | C500                        | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| Lenovo        | G505 20240                  | [6c4aff8f5f](https://linux-hardware.org/?probe=6c4aff8f5f) | May 18, 2022 |
| Dell          | Precision 3520              | [9e2b1878d1](https://linux-hardware.org/?probe=9e2b1878d1) | May 18, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8026841674](https://linux-hardware.org/?probe=8026841674) | May 15, 2022 |
| Dell          | Inspiron 3580               | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | OMEN by Laptop              | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| HP            | Pavilion dv7                | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| Standard      | Unknown                     | [74971ae227](https://linux-hardware.org/?probe=74971ae227) | May 04, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| ASUSTek       | G75VX                       | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| Dell          | Latitude 5490               | [9445f416cb](https://linux-hardware.org/?probe=9445f416cb) | Apr 30, 2022 |
| Dell          | Latitude 5520               | [d35917a603](https://linux-hardware.org/?probe=d35917a603) | Apr 29, 2022 |
| Dell          | Latitude 5520               | [9851c7847d](https://linux-hardware.org/?probe=9851c7847d) | Apr 29, 2022 |
| HP            | Pavilion dv7                | [fd2d8cc4f6](https://linux-hardware.org/?probe=fd2d8cc4f6) | Apr 29, 2022 |
| HP            | ProBook 4310s               | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | [009a9c8ce0](https://linux-hardware.org/?probe=009a9c8ce0) | Apr 25, 2022 |
| Acer          | Aspire E1-571               | [4a76d57188](https://linux-hardware.org/?probe=4a76d57188) | Apr 23, 2022 |
| Acer          | Aspire E1-571               | [ee546b53aa](https://linux-hardware.org/?probe=ee546b53aa) | Apr 23, 2022 |
| Proline       | V146A                       | [30cc5fb7c1](https://linux-hardware.org/?probe=30cc5fb7c1) | Apr 22, 2022 |
| Acer          | Swift SF314-42              | [b0dc5471af](https://linux-hardware.org/?probe=b0dc5471af) | Apr 22, 2022 |
| HP            | Laptop 15-bw0xx             | [b251d7f8e6](https://linux-hardware.org/?probe=b251d7f8e6) | Apr 20, 2022 |
| Acer          | Swift SF314-42              | [a8af23856d](https://linux-hardware.org/?probe=a8af23856d) | Apr 20, 2022 |
| Toshiba       | Satellite C850-F31Q         | [e7a2a2ff69](https://linux-hardware.org/?probe=e7a2a2ff69) | Apr 19, 2022 |
| MECER         | YA13Q20-DP_PRO              | [d4cf4e840f](https://linux-hardware.org/?probe=d4cf4e840f) | Apr 18, 2022 |
| Dell          | Inspiron 3521               | [00dc9c3cca](https://linux-hardware.org/?probe=00dc9c3cca) | Apr 18, 2022 |
| Dell          | Latitude 3550               | [03ed6ab7b4](https://linux-hardware.org/?probe=03ed6ab7b4) | Apr 16, 2022 |
| HP            | Presario CQ57               | [110b597e47](https://linux-hardware.org/?probe=110b597e47) | Apr 14, 2022 |
| Dell          | Latitude 3550               | [6947850074](https://linux-hardware.org/?probe=6947850074) | Apr 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6565c955db](https://linux-hardware.org/?probe=6565c955db) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f6c87488b0](https://linux-hardware.org/?probe=f6c87488b0) | Apr 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [48f70d4c5a](https://linux-hardware.org/?probe=48f70d4c5a) | Apr 05, 2022 |
| Dell          | XPS 13 9380                 | [1395229a99](https://linux-hardware.org/?probe=1395229a99) | Apr 04, 2022 |
| Dell          | Latitude 5500               | [798c0e5fa4](https://linux-hardware.org/?probe=798c0e5fa4) | Apr 02, 2022 |
| CONNEX        | L1470                       | [6c1aaac1ee](https://linux-hardware.org/?probe=6c1aaac1ee) | Apr 02, 2022 |
| Lenovo        | G500 20236                  | [9ebbf23e28](https://linux-hardware.org/?probe=9ebbf23e28) | Apr 01, 2022 |
| Lenovo        | G500 20236                  | [95d2d82ede](https://linux-hardware.org/?probe=95d2d82ede) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | [00630dc1b2](https://linux-hardware.org/?probe=00630dc1b2) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 41786KG       | [373ac41605](https://linux-hardware.org/?probe=373ac41605) | Apr 01, 2022 |
| ASUSTek       | UL80VT                      | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| ASUSTek       | GL753VD                     | [af3543aaed](https://linux-hardware.org/?probe=af3543aaed) | Mar 31, 2022 |
| HUAWEI        | BOHB-WAX9                   | [cb353468c2](https://linux-hardware.org/?probe=cb353468c2) | Mar 28, 2022 |
| ASUSTek       | X555UB                      | [e0b9178226](https://linux-hardware.org/?probe=e0b9178226) | Mar 28, 2022 |
| HP            | Pavilion g6                 | [79ebe026b7](https://linux-hardware.org/?probe=79ebe026b7) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | [74a1c6bd00](https://linux-hardware.org/?probe=74a1c6bd00) | Mar 26, 2022 |
| Dell          | Inspiron M5040              | [e352bc299f](https://linux-hardware.org/?probe=e352bc299f) | Mar 26, 2022 |
| Dell          | Latitude E5540              | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Lenovo        | G500 20236                  | [da34cf7e5c](https://linux-hardware.org/?probe=da34cf7e5c) | Mar 24, 2022 |
| ASUSTek       | Strix GL704GV_GL704GV       | [87c17cc6e1](https://linux-hardware.org/?probe=87c17cc6e1) | Mar 22, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [26a88b6d1f](https://linux-hardware.org/?probe=26a88b6d1f) | Mar 21, 2022 |
| Dell          | Latitude 5420               | [b1a1e20ab3](https://linux-hardware.org/?probe=b1a1e20ab3) | Mar 21, 2022 |
| Lenovo        | ThinkPad 20LB000DZA         | [e4b122e82a](https://linux-hardware.org/?probe=e4b122e82a) | Mar 21, 2022 |
| Lenovo        | ThinkPad 20LB000DZA         | [879224cf79](https://linux-hardware.org/?probe=879224cf79) | Mar 20, 2022 |
| Lenovo        | ThinkPad T520 424067G       | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| Dell          | Latitude 3550               | [947e147577](https://linux-hardware.org/?probe=947e147577) | Mar 13, 2022 |
| Dell          | Latitude 3550               | [afffe18667](https://linux-hardware.org/?probe=afffe18667) | Mar 13, 2022 |
| Dell          | Inspiron 3543               | [e6d7592af0](https://linux-hardware.org/?probe=e6d7592af0) | Mar 10, 2022 |
| HP            | Laptop 15-dw3xxx            | [65026cfb9e](https://linux-hardware.org/?probe=65026cfb9e) | Mar 09, 2022 |
| HP            | Laptop 15-dw3xxx            | [7557102b76](https://linux-hardware.org/?probe=7557102b76) | Mar 08, 2022 |
| HP            | Laptop 14 14s-dq1008ni      | [8184627283](https://linux-hardware.org/?probe=8184627283) | Mar 07, 2022 |
| Acer          | TMP453-MG                   | [87bcae98bc](https://linux-hardware.org/?probe=87bcae98bc) | Mar 07, 2022 |
| Dell          | Latitude E6430              | [0e9a8aa6cc](https://linux-hardware.org/?probe=0e9a8aa6cc) | Mar 06, 2022 |
| ASUSTek       | X555LAB                     | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| Acer          | Aspire VN7-591G             | [57452c9459](https://linux-hardware.org/?probe=57452c9459) | Mar 03, 2022 |
| Dell          | Inspiron 3543               | [f10ea4bbca](https://linux-hardware.org/?probe=f10ea4bbca) | Mar 02, 2022 |
| Dell          | Precision 3520              | [4b9a52ac5c](https://linux-hardware.org/?probe=4b9a52ac5c) | Feb 24, 2022 |
| ASUSTek       | X555LAB                     | [9e1f07c164](https://linux-hardware.org/?probe=9e1f07c164) | Feb 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8e2cd5844e](https://linux-hardware.org/?probe=8e2cd5844e) | Feb 21, 2022 |
| Acer          | TMP453-MG                   | [4b25f5d025](https://linux-hardware.org/?probe=4b25f5d025) | Feb 19, 2022 |
| Dell          | Latitude D630               | [e427bda7a4](https://linux-hardware.org/?probe=e427bda7a4) | Feb 17, 2022 |
| Dell          | Latitude D630               | [bca39271ba](https://linux-hardware.org/?probe=bca39271ba) | Feb 17, 2022 |
| Fujitsu       | LIFEBOOK E751               | [5ca51d5bb5](https://linux-hardware.org/?probe=5ca51d5bb5) | Feb 17, 2022 |
| Dell          | Inspiron 5521               | [e0b1929884](https://linux-hardware.org/?probe=e0b1929884) | Feb 17, 2022 |
| Acer          | Predator G9-793             | [45ec93214f](https://linux-hardware.org/?probe=45ec93214f) | Feb 16, 2022 |
| Sony          | VPCEH38FG                   | [15472f67f5](https://linux-hardware.org/?probe=15472f67f5) | Feb 15, 2022 |
| Lenovo        | G560 20042                  | [5c4a8043b1](https://linux-hardware.org/?probe=5c4a8043b1) | Feb 15, 2022 |
| Dell          | Inspiron 5521               | [aee089a0aa](https://linux-hardware.org/?probe=aee089a0aa) | Feb 14, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [456d12240c](https://linux-hardware.org/?probe=456d12240c) | Feb 11, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [305921eee8](https://linux-hardware.org/?probe=305921eee8) | Feb 11, 2022 |
| System76      | Oryx Pro                    | [f8437eee6d](https://linux-hardware.org/?probe=f8437eee6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | [80b214a273](https://linux-hardware.org/?probe=80b214a273) | Feb 10, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [b29422e3cd](https://linux-hardware.org/?probe=b29422e3cd) | Feb 10, 2022 |
| Acer          | TMP453-MG                   | [4e741a6acc](https://linux-hardware.org/?probe=4e741a6acc) | Feb 08, 2022 |
| HP            | EliteBook 2540p             | [006afe98fe](https://linux-hardware.org/?probe=006afe98fe) | Feb 07, 2022 |
| HP            | 635                         | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| Dell          | Inspiron 3537               | [66fb2bc907](https://linux-hardware.org/?probe=66fb2bc907) | Feb 06, 2022 |
| HP            | ENVY TS 15                  | [becd915336](https://linux-hardware.org/?probe=becd915336) | Feb 04, 2022 |
| Dell          | Inspiron 15-3567            | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [3df622872c](https://linux-hardware.org/?probe=3df622872c) | Feb 03, 2022 |
| HP            | ProBook 4530s               | [4a1bfbe60f](https://linux-hardware.org/?probe=4a1bfbe60f) | Feb 01, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Dell          | Latitude E6220              | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Toshiba       | TECRA A10                   | [bdaff089b2](https://linux-hardware.org/?probe=bdaff089b2) | Jan 28, 2022 |
| Dell          | Latitude D630               | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b58afceea](https://linux-hardware.org/?probe=3b58afceea) | Jan 21, 2022 |
| WinSome       | A14C .B005                  | [d685b78944](https://linux-hardware.org/?probe=d685b78944) | Jan 19, 2022 |
| Dell          | Latitude D630               | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c9dbc0c289](https://linux-hardware.org/?probe=c9dbc0c289) | Jan 14, 2022 |
| HP            | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Dell          | Inspiron 15-3567            | [e36e312cf4](https://linux-hardware.org/?probe=e36e312cf4) | Jan 09, 2022 |
| HP            | Laptop 15-bs1xx             | [d187087325](https://linux-hardware.org/?probe=d187087325) | Jan 09, 2022 |
| HP            | 2000                        | [3c3f60019b](https://linux-hardware.org/?probe=3c3f60019b) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 1294BL5         | [2cd6f5fbb0](https://linux-hardware.org/?probe=2cd6f5fbb0) | Jan 01, 2022 |
| Acer          | TravelMate P255             | [1efdd6ce09](https://linux-hardware.org/?probe=1efdd6ce09) | Dec 26, 2021 |
| Dell          | Latitude 3540               | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| Dell          | Latitude E6430              | [c5ac7574f0](https://linux-hardware.org/?probe=c5ac7574f0) | Dec 22, 2021 |
| HP            | ZBook 15u G3                | [6d1e6100ef](https://linux-hardware.org/?probe=6d1e6100ef) | Dec 21, 2021 |
| Acer          | Aspire VN7-572G             | [895dca26b0](https://linux-hardware.org/?probe=895dca26b0) | Dec 21, 2021 |
| Toshiba       | TECRA A10                   | [e5b76a4673](https://linux-hardware.org/?probe=e5b76a4673) | Dec 21, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | [0b0d4dd23f](https://linux-hardware.org/?probe=0b0d4dd23f) | Dec 21, 2021 |
| Lenovo        | ThinkPad E580 20KS001QZA    | [202290bb62](https://linux-hardware.org/?probe=202290bb62) | Dec 20, 2021 |
| Lenovo        | ThinkPad E580 20KS001QZA    | [8a131f560b](https://linux-hardware.org/?probe=8a131f560b) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | [15e7aaf611](https://linux-hardware.org/?probe=15e7aaf611) | Dec 17, 2021 |
| Acer          | TravelMate 6594             | [d706658ff8](https://linux-hardware.org/?probe=d706658ff8) | Dec 15, 2021 |
| Dell          | Inspiron 1525               | [b93d5f0c9c](https://linux-hardware.org/?probe=b93d5f0c9c) | Dec 14, 2021 |
| Dell          | Inspiron 3537               | [f1213e164f](https://linux-hardware.org/?probe=f1213e164f) | Dec 13, 2021 |
| Sony          | VPCP116KG                   | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| HP            | EliteBook 2570p             | [1e9841c0eb](https://linux-hardware.org/?probe=1e9841c0eb) | Dec 12, 2021 |
| TCL Commun... | 8085                        | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Precision M6800             | [da95c95a07](https://linux-hardware.org/?probe=da95c95a07) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d0e3422cba](https://linux-hardware.org/?probe=d0e3422cba) | Dec 08, 2021 |
| Dell          | Precision M6800             | [3a4d66818c](https://linux-hardware.org/?probe=3a4d66818c) | Dec 07, 2021 |
| HP            | Laptop 15-bs1xx             | [b6c9f34c4c](https://linux-hardware.org/?probe=b6c9f34c4c) | Dec 07, 2021 |
| Dell          | Precision M6800             | [3b4f2f0a57](https://linux-hardware.org/?probe=3b4f2f0a57) | Dec 06, 2021 |
| HP            | 255 G8 Notebook PC          | [a700683a6f](https://linux-hardware.org/?probe=a700683a6f) | Dec 05, 2021 |
| Dell          | Latitude 5590               | [5f9747af05](https://linux-hardware.org/?probe=5f9747af05) | Dec 04, 2021 |
| Acer          | Predator G9-793             | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Lenovo        | ThinkPad T580 20L90024ZA    | [6b8493406e](https://linux-hardware.org/?probe=6b8493406e) | Nov 28, 2021 |
| Lenovo        | ThinkPad T580 20L90024ZA    | [4a398efa1b](https://linux-hardware.org/?probe=4a398efa1b) | Nov 28, 2021 |
| HP            | ProBook 4310s               | [9f467df8a8](https://linux-hardware.org/?probe=9f467df8a8) | Nov 27, 2021 |
| HP            | ProBook 4310s               | [6d339b7843](https://linux-hardware.org/?probe=6d339b7843) | Nov 27, 2021 |
| LattePanda    | Delta                       | [5950a5a8ac](https://linux-hardware.org/?probe=5950a5a8ac) | Nov 24, 2021 |
| Dell          | Inspiron N5110              | [ea27790fc4](https://linux-hardware.org/?probe=ea27790fc4) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| HP            | Notebook                    | [12d501a930](https://linux-hardware.org/?probe=12d501a930) | Nov 17, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [7114246672](https://linux-hardware.org/?probe=7114246672) | Nov 15, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [2cb8a3b9ff](https://linux-hardware.org/?probe=2cb8a3b9ff) | Nov 15, 2021 |
| HP            | Presario CQ56               | [a514e96472](https://linux-hardware.org/?probe=a514e96472) | Nov 15, 2021 |
| MSI           | CR72 7ML                    | [9fdd485636](https://linux-hardware.org/?probe=9fdd485636) | Nov 12, 2021 |
| MSI           | CR72 7ML                    | [1165c3e22f](https://linux-hardware.org/?probe=1165c3e22f) | Nov 12, 2021 |
| Acer          | Aspire V3-571               | [0c1d65f646](https://linux-hardware.org/?probe=0c1d65f646) | Nov 08, 2021 |
| Dell          | Inspiron 5721               | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| Dell          | Studio 1735                 | [6a444456ef](https://linux-hardware.org/?probe=6a444456ef) | Nov 06, 2021 |
| Gigabyte      | P17FV5                      | [379e023c65](https://linux-hardware.org/?probe=379e023c65) | Nov 04, 2021 |
| HP            | ProBook 4310s               | [bb95a3f04d](https://linux-hardware.org/?probe=bb95a3f04d) | Nov 03, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [293a751aaf](https://linux-hardware.org/?probe=293a751aaf) | Nov 02, 2021 |
| Gigabyte      | P17FV5                      | [7304aa43c3](https://linux-hardware.org/?probe=7304aa43c3) | Nov 02, 2021 |
| Apple         | MacBook4,1                  | [4a72082fdb](https://linux-hardware.org/?probe=4a72082fdb) | Nov 01, 2021 |
| Packard Be... | ENTE11HC                    | [e31fe4eef0](https://linux-hardware.org/?probe=e31fe4eef0) | Nov 01, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| HP            | ProBook 450 G3              | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | Inspiron 3537               | [b0f6309320](https://linux-hardware.org/?probe=b0f6309320) | Oct 31, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| ASUSTek       | X58C                        | [fdd83a3517](https://linux-hardware.org/?probe=fdd83a3517) | Oct 28, 2021 |
| Dell          | Latitude E5570              | [e7a049a026](https://linux-hardware.org/?probe=e7a049a026) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d43c3cb973](https://linux-hardware.org/?probe=d43c3cb973) | Oct 27, 2021 |
| HP            | Presario CQ56               | [10acff551d](https://linux-hardware.org/?probe=10acff551d) | Oct 25, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [eaf7694813](https://linux-hardware.org/?probe=eaf7694813) | Oct 24, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [44b5186950](https://linux-hardware.org/?probe=44b5186950) | Oct 24, 2021 |
| Dell          | Vostro 15-3568              | [4a961ff6da](https://linux-hardware.org/?probe=4a961ff6da) | Oct 22, 2021 |
| HP            | Laptop 15-dw3xxx            | [9bde1214a9](https://linux-hardware.org/?probe=9bde1214a9) | Oct 22, 2021 |
| Dell          | Latitude E6430              | [b127732e59](https://linux-hardware.org/?probe=b127732e59) | Oct 19, 2021 |
| MSI           | GF65 Thin 10SDR             | [0a048a009d](https://linux-hardware.org/?probe=0a048a009d) | Oct 15, 2021 |
| Lenovo        | E50-80 80J2                 | [c3d31689ec](https://linux-hardware.org/?probe=c3d31689ec) | Oct 11, 2021 |
| Apple         | MacBookPro8,2               | [a3f3c59edc](https://linux-hardware.org/?probe=a3f3c59edc) | Oct 11, 2021 |
| Acer          | Aspire VN7-792G             | [4985d6b90c](https://linux-hardware.org/?probe=4985d6b90c) | Oct 10, 2021 |
| Apple         | MacBookPro9,2               | [d804de918d](https://linux-hardware.org/?probe=d804de918d) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [080e5a9a9f](https://linux-hardware.org/?probe=080e5a9a9f) | Oct 06, 2021 |
| Lenovo        | G50-80 80E5                 | [d9b26b9fec](https://linux-hardware.org/?probe=d9b26b9fec) | Oct 06, 2021 |
| HP            | EliteBook 850 G3            | [cb307dd929](https://linux-hardware.org/?probe=cb307dd929) | Oct 06, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f85d75b229](https://linux-hardware.org/?probe=f85d75b229) | Oct 05, 2021 |
| HP            | 650                         | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| Acer          | Aspire A315-31              | [65388cbcfc](https://linux-hardware.org/?probe=65388cbcfc) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | [97dde270fa](https://linux-hardware.org/?probe=97dde270fa) | Oct 03, 2021 |
| MSI           | Modern 14 B11MO             | [e8f13facfd](https://linux-hardware.org/?probe=e8f13facfd) | Oct 03, 2021 |
| HP            | Laptop 15-bs0xx             | [e9dd5491e8](https://linux-hardware.org/?probe=e9dd5491e8) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | [44d29122aa](https://linux-hardware.org/?probe=44d29122aa) | Sep 28, 2021 |
| MSI           | Modern 14 B11MO             | [9f5c2e0fde](https://linux-hardware.org/?probe=9f5c2e0fde) | Sep 27, 2021 |
| Acer          | Aspire A315-31              | [7af0b1b5dd](https://linux-hardware.org/?probe=7af0b1b5dd) | Sep 27, 2021 |
| Acer          | TravelMate P255             | [c6b7f1d5d9](https://linux-hardware.org/?probe=c6b7f1d5d9) | Sep 26, 2021 |
| Acer          | Aspire VN7-792G             | [b555c8cd95](https://linux-hardware.org/?probe=b555c8cd95) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d9796386e](https://linux-hardware.org/?probe=9d9796386e) | Sep 21, 2021 |
| Acer          | Aspire V3-571G              | [33781ae35f](https://linux-hardware.org/?probe=33781ae35f) | Sep 21, 2021 |
| Acer          | Extensa 2511                | [b38f9bfa33](https://linux-hardware.org/?probe=b38f9bfa33) | Sep 16, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| Dell          | Precision 7550              | [42890f7542](https://linux-hardware.org/?probe=42890f7542) | Sep 10, 2021 |
| Dell          | Precision 7550              | [a4a1a56132](https://linux-hardware.org/?probe=a4a1a56132) | Sep 09, 2021 |
| Apple         | MacBookPro8,1               | [03445cb511](https://linux-hardware.org/?probe=03445cb511) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| Dell          | XPS 13 9310                 | [1ee958abc3](https://linux-hardware.org/?probe=1ee958abc3) | Sep 08, 2021 |
| HP            | Presario CQ56               | [b5666dc71b](https://linux-hardware.org/?probe=b5666dc71b) | Sep 08, 2021 |
| Packard Be... | EasyNote TK85               | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Dell          | Latitude 7480               | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | ProBook 450 G5              | [beefff4447](https://linux-hardware.org/?probe=beefff4447) | Sep 06, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| ASUSTek       | G551JM                      | [4309f5e034](https://linux-hardware.org/?probe=4309f5e034) | Sep 04, 2021 |
| ASUSTek       | G551JM                      | [0dad1d056d](https://linux-hardware.org/?probe=0dad1d056d) | Sep 04, 2021 |
| Dell          | Latitude E6430              | [866d479f07](https://linux-hardware.org/?probe=866d479f07) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | Notebook                    | [552535c21e](https://linux-hardware.org/?probe=552535c21e) | Sep 02, 2021 |
| HP            | Notebook                    | [0405b5aa6c](https://linux-hardware.org/?probe=0405b5aa6c) | Sep 02, 2021 |
| HP            | ProBook 450 G5              | [1579919ebb](https://linux-hardware.org/?probe=1579919ebb) | Sep 01, 2021 |
| HP            | EliteBook 8730w             | [93ee7aecde](https://linux-hardware.org/?probe=93ee7aecde) | Aug 31, 2021 |
| HP            | EliteBook 8730w             | [c99d13438f](https://linux-hardware.org/?probe=c99d13438f) | Aug 30, 2021 |
| HP            | EliteBook 850 G6            | [87f2a544c5](https://linux-hardware.org/?probe=87f2a544c5) | Aug 30, 2021 |
| Mustek        | W35xSS_370SS                | [ee70b31c91](https://linux-hardware.org/?probe=ee70b31c91) | Aug 24, 2021 |
| Dell          | Inspiron 7577               | [82ff6985ce](https://linux-hardware.org/?probe=82ff6985ce) | Aug 18, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [d9923e15e0](https://linux-hardware.org/?probe=d9923e15e0) | Aug 18, 2021 |
| Packard Be... | EasyNote TK85               | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| Gigabyte      | Q2006                       | [16503fc58a](https://linux-hardware.org/?probe=16503fc58a) | Aug 16, 2021 |
| Dell          | Latitude E6430              | [31491d6a83](https://linux-hardware.org/?probe=31491d6a83) | Aug 15, 2021 |
| Dell          | Latitude 5580               | [1c57f7bb76](https://linux-hardware.org/?probe=1c57f7bb76) | Aug 15, 2021 |
| HP            | Pavilion dv4                | [bc1ab4b47e](https://linux-hardware.org/?probe=bc1ab4b47e) | Aug 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [1f6745d6bb](https://linux-hardware.org/?probe=1f6745d6bb) | Aug 11, 2021 |
| Notebook      | W54_55SU1,SUW               | [a771e9b877](https://linux-hardware.org/?probe=a771e9b877) | Aug 11, 2021 |
| Apple         | MacBookPro7,1               | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| HP            | Pavilion dv4                | [34b7ad0d24](https://linux-hardware.org/?probe=34b7ad0d24) | Aug 09, 2021 |
| HP            | ZBook 15u G3                | [e1a51f61f1](https://linux-hardware.org/?probe=e1a51f61f1) | Aug 08, 2021 |
| Lenovo        | ThinkPad T440p 2000CT0      | [574392d159](https://linux-hardware.org/?probe=574392d159) | Aug 07, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| HP            | Laptop 15-dw2xxx            | [80d1826ee1](https://linux-hardware.org/?probe=80d1826ee1) | Aug 02, 2021 |
| Acer          | Aspire ES1-512              | [ac364c0278](https://linux-hardware.org/?probe=ac364c0278) | Aug 01, 2021 |
| Acer          | Aspire ES1-512              | [161731059f](https://linux-hardware.org/?probe=161731059f) | Aug 01, 2021 |
| HP            | Presario CQ56               | [b2f6fbae75](https://linux-hardware.org/?probe=b2f6fbae75) | Jul 29, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Samsung       | N150P/N210P/N220P           | [f126b121e0](https://linux-hardware.org/?probe=f126b121e0) | Jul 23, 2021 |
| Dell          | XPS 13 9310                 | [bcb7059afa](https://linux-hardware.org/?probe=bcb7059afa) | Jul 19, 2021 |
| Samsung       | RC410/RC510/RC710           | [f9f770c055](https://linux-hardware.org/?probe=f9f770c055) | Jul 17, 2021 |
| Samsung       | RC410/RC510/RC710           | [f2f4a48775](https://linux-hardware.org/?probe=f2f4a48775) | Jul 17, 2021 |
| ASUSTek       | X550CL                      | [3a09584428](https://linux-hardware.org/?probe=3a09584428) | Jul 16, 2021 |
| Dell          | Latitude 5590               | [71d3a5a5d7](https://linux-hardware.org/?probe=71d3a5a5d7) | Jul 16, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [662ed28f07](https://linux-hardware.org/?probe=662ed28f07) | Jul 16, 2021 |
| HP            | 250 G7 Notebook PC          | [846febb191](https://linux-hardware.org/?probe=846febb191) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | [96ce85594c](https://linux-hardware.org/?probe=96ce85594c) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | [8e96e56dc3](https://linux-hardware.org/?probe=8e96e56dc3) | Jul 14, 2021 |
| Apple         | MacBookPro9,2               | [f1ca4c9fb2](https://linux-hardware.org/?probe=f1ca4c9fb2) | Jul 12, 2021 |
| Dell          | G7 7790                     | [9c6ab51434](https://linux-hardware.org/?probe=9c6ab51434) | Jul 11, 2021 |
| Acer          | Aspire 5715Z                | [8459bc8e66](https://linux-hardware.org/?probe=8459bc8e66) | Jul 11, 2021 |
| Acer          | Aspire 5715Z                | [77bd0c29ea](https://linux-hardware.org/?probe=77bd0c29ea) | Jul 10, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [94137d1697](https://linux-hardware.org/?probe=94137d1697) | Jul 08, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c27edc6b7e](https://linux-hardware.org/?probe=c27edc6b7e) | Jul 07, 2021 |
| Dell          | Latitude E7440              | [c7aa70ad78](https://linux-hardware.org/?probe=c7aa70ad78) | Jul 07, 2021 |
| HP            | Laptop 15-bs0xx             | [76b81b25d9](https://linux-hardware.org/?probe=76b81b25d9) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d23e2c3398](https://linux-hardware.org/?probe=d23e2c3398) | Jul 01, 2021 |
| Dell          | Inspiron 1564               | [37f6c092f2](https://linux-hardware.org/?probe=37f6c092f2) | Jun 30, 2021 |
| Lenovo        | ThinkPad Edge 057872G       | [8bc64e956d](https://linux-hardware.org/?probe=8bc64e956d) | Jun 25, 2021 |
| Dell          | Inspiron 15-3567            | [b18b2ef77a](https://linux-hardware.org/?probe=b18b2ef77a) | Jun 20, 2021 |
| Acer          | TravelMate 8571             | [5ebead6e64](https://linux-hardware.org/?probe=5ebead6e64) | Jun 20, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [d1c7b5962a](https://linux-hardware.org/?probe=d1c7b5962a) | Jun 19, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [592d026476](https://linux-hardware.org/?probe=592d026476) | Jun 19, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4154f6bf31](https://linux-hardware.org/?probe=4154f6bf31) | Jun 14, 2021 |
| Dell          | XPS 13 9310                 | [278fd058ed](https://linux-hardware.org/?probe=278fd058ed) | Jun 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| Acer          | Aspire E1-571               | [c0ba4bd856](https://linux-hardware.org/?probe=c0ba4bd856) | Jun 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [54fa44f208](https://linux-hardware.org/?probe=54fa44f208) | Jun 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d0ad3d400](https://linux-hardware.org/?probe=5d0ad3d400) | Jun 08, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d13e2fdb32](https://linux-hardware.org/?probe=d13e2fdb32) | Jun 05, 2021 |
| HP            | ProBook 6560b               | [f9ee7c5367](https://linux-hardware.org/?probe=f9ee7c5367) | Jun 01, 2021 |
| HP            | ProBook 6560b               | [523614fee6](https://linux-hardware.org/?probe=523614fee6) | May 31, 2021 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d507f88a47](https://linux-hardware.org/?probe=d507f88a47) | May 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [fbf4582983](https://linux-hardware.org/?probe=fbf4582983) | May 25, 2021 |
| Packard Be... | EasyNote TS44HR             | [85bcf858c5](https://linux-hardware.org/?probe=85bcf858c5) | May 25, 2021 |
| Apple         | MacBookPro16,1              | [2bddf8b98a](https://linux-hardware.org/?probe=2bddf8b98a) | May 23, 2021 |
| Acer          | TMP453-MG                   | [07291bacfe](https://linux-hardware.org/?probe=07291bacfe) | May 22, 2021 |
| Dell          | Latitude E7440              | [ef82f4635d](https://linux-hardware.org/?probe=ef82f4635d) | May 21, 2021 |
| Dell          | Latitude E7440              | [211f0afc76](https://linux-hardware.org/?probe=211f0afc76) | May 21, 2021 |
| HP            | Compaq Presario C700        | [78d8d0ea55](https://linux-hardware.org/?probe=78d8d0ea55) | May 21, 2021 |
| HP            | Compaq Presario C700        | [46f488f882](https://linux-hardware.org/?probe=46f488f882) | May 21, 2021 |
| HP            | Laptop 15-db0xxx            | [2947241fec](https://linux-hardware.org/?probe=2947241fec) | May 19, 2021 |
| ASUSTek       | X550VX                      | [6b634edf3a](https://linux-hardware.org/?probe=6b634edf3a) | May 19, 2021 |
| ASUSTek       | U80A                        | [1a763007d1](https://linux-hardware.org/?probe=1a763007d1) | May 18, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [c83a466f92](https://linux-hardware.org/?probe=c83a466f92) | May 17, 2021 |
| ASUSTek       | U80A                        | [b3134204a7](https://linux-hardware.org/?probe=b3134204a7) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a035be3ea2](https://linux-hardware.org/?probe=a035be3ea2) | May 16, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [bc6920fa56](https://linux-hardware.org/?probe=bc6920fa56) | May 16, 2021 |
| HP            | ProBook 430 G3              | [08de893a8a](https://linux-hardware.org/?probe=08de893a8a) | May 16, 2021 |
| HP            | ProBook 430 G3              | [20657f6556](https://linux-hardware.org/?probe=20657f6556) | May 16, 2021 |
| Lenovo        | IdeaPad Y560                | [a51abd79ce](https://linux-hardware.org/?probe=a51abd79ce) | May 14, 2021 |
| Dell          | Inspiron 15-3567            | [d42792c1a7](https://linux-hardware.org/?probe=d42792c1a7) | May 14, 2021 |
| Google        | Treeya                      | [5dfc619144](https://linux-hardware.org/?probe=5dfc619144) | May 09, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [dc9c7088dd](https://linux-hardware.org/?probe=dc9c7088dd) | May 08, 2021 |
| Lenovo        | ThinkPad T440 20B7S0JF0L    | [9cf4893825](https://linux-hardware.org/?probe=9cf4893825) | May 08, 2021 |
| Standard      | Unknown                     | [e9a891227f](https://linux-hardware.org/?probe=e9a891227f) | May 05, 2021 |
| Standard      | Unknown                     | [713ab93267](https://linux-hardware.org/?probe=713ab93267) | May 04, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5fe6b07786](https://linux-hardware.org/?probe=5fe6b07786) | May 04, 2021 |
| Standard      | Unknown                     | [c3b8d0e386](https://linux-hardware.org/?probe=c3b8d0e386) | May 04, 2021 |
| Toshiba       | Satellite L300              | [2b7b781f75](https://linux-hardware.org/?probe=2b7b781f75) | May 02, 2021 |
| HP            | Compaq CQ58                 | [d1bde8c0f4](https://linux-hardware.org/?probe=d1bde8c0f4) | May 02, 2021 |
| HP            | Compaq CQ58                 | [e6efc8f997](https://linux-hardware.org/?probe=e6efc8f997) | May 02, 2021 |
| HP            | Pavilion dv7                | [98693d2a86](https://linux-hardware.org/?probe=98693d2a86) | May 01, 2021 |
| HP            | Pavilion dv7                | [bd65b55f0a](https://linux-hardware.org/?probe=bd65b55f0a) | May 01, 2021 |
| HP            | ProBook 430 G5              | [18081fbf4f](https://linux-hardware.org/?probe=18081fbf4f) | May 01, 2021 |
| Acer          | Aspire 4315                 | [159c0c0abe](https://linux-hardware.org/?probe=159c0c0abe) | Apr 30, 2021 |
| CONNEX        | L1420                       | [048b79fa6b](https://linux-hardware.org/?probe=048b79fa6b) | Apr 30, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [2a4fa34857](https://linux-hardware.org/?probe=2a4fa34857) | Apr 30, 2021 |
| Dell          | Latitude E6400              | [2ea2bb4954](https://linux-hardware.org/?probe=2ea2bb4954) | Apr 30, 2021 |
| Acer          | Aspire 4315                 | [b05c255870](https://linux-hardware.org/?probe=b05c255870) | Apr 30, 2021 |
| Sony          | VGN-CR343N_B                | [9ac5c739ff](https://linux-hardware.org/?probe=9ac5c739ff) | Apr 29, 2021 |
| HP            | EliteBook 850 G3            | [945ffd0849](https://linux-hardware.org/?probe=945ffd0849) | Apr 28, 2021 |
| Toshiba       | Satellite L300              | [c52eca34ae](https://linux-hardware.org/?probe=c52eca34ae) | Apr 28, 2021 |
| Acer          | Aspire E1-571               | [b9694847a3](https://linux-hardware.org/?probe=b9694847a3) | Apr 26, 2021 |
| PINNACLEMI... | P65_P67RGRERA               | [15933445a2](https://linux-hardware.org/?probe=15933445a2) | Apr 25, 2021 |
| PINNACLEMI... | P65_P67RGRERA               | [b0ccc7e7a7](https://linux-hardware.org/?probe=b0ccc7e7a7) | Apr 25, 2021 |
| HP            | ENVY TS 15                  | [7ee12f0f12](https://linux-hardware.org/?probe=7ee12f0f12) | Apr 24, 2021 |
| HP            | ENVY TS 15                  | [1e93ee4ada](https://linux-hardware.org/?probe=1e93ee4ada) | Apr 23, 2021 |
| HP            | 255 G7 Notebook PC          | [4f1fd4db18](https://linux-hardware.org/?probe=4f1fd4db18) | Apr 22, 2021 |
| CONNEX        | L1420                       | [eb5985fa85](https://linux-hardware.org/?probe=eb5985fa85) | Apr 21, 2021 |
| CONNEX        | L1420                       | [4abc009f2e](https://linux-hardware.org/?probe=4abc009f2e) | Apr 21, 2021 |
| HP            | Pavilion dv6500             | [cb77a79ee8](https://linux-hardware.org/?probe=cb77a79ee8) | Apr 18, 2021 |
| HP            | Laptop 15-bs0xx             | [50ce0817b2](https://linux-hardware.org/?probe=50ce0817b2) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [2d9245f497](https://linux-hardware.org/?probe=2d9245f497) | Apr 14, 2021 |
| Apple         | MacBookPro16,1              | [3842dcb196](https://linux-hardware.org/?probe=3842dcb196) | Apr 06, 2021 |
| Apple         | MacBookPro16,1              | [8730828ebe](https://linux-hardware.org/?probe=8730828ebe) | Apr 06, 2021 |
| Apple         | MacBookPro9,2               | [6c925ae270](https://linux-hardware.org/?probe=6c925ae270) | Apr 05, 2021 |
| ASUSTek       | X101CH                      | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| HP            | 255 G2                      | [f8dcdf927f](https://linux-hardware.org/?probe=f8dcdf927f) | Apr 04, 2021 |
| Lenovo        | ThinkPad Edge E530 3259T... | [6faba40178](https://linux-hardware.org/?probe=6faba40178) | Mar 30, 2021 |
| Apple         | MacBookPro16,1              | [e5efa4cc6a](https://linux-hardware.org/?probe=e5efa4cc6a) | Mar 29, 2021 |
| HP            | 255 G7 Notebook PC          | [e5a505d84f](https://linux-hardware.org/?probe=e5a505d84f) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [90f8531811](https://linux-hardware.org/?probe=90f8531811) | Mar 23, 2021 |
| HP            | ProBook 4520s               | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| HP            | ProBook 4520s               | [d94784890e](https://linux-hardware.org/?probe=d94784890e) | Mar 22, 2021 |
| Apple         | MacBookPro16,1              | [1e05fafe6d](https://linux-hardware.org/?probe=1e05fafe6d) | Mar 21, 2021 |
| HP            | Pavilion g7                 | [ccc49b1cd4](https://linux-hardware.org/?probe=ccc49b1cd4) | Mar 21, 2021 |
| Packard Be... | ENTE11HC                    | [7c208291a7](https://linux-hardware.org/?probe=7c208291a7) | Mar 19, 2021 |
| Apple         | MacBookPro16,1              | [471d1e9f3d](https://linux-hardware.org/?probe=471d1e9f3d) | Mar 18, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [01aac2b2b5](https://linux-hardware.org/?probe=01aac2b2b5) | Mar 17, 2021 |
| Lenovo        | ThinkPad T410 25374A5       | [ff1dee8695](https://linux-hardware.org/?probe=ff1dee8695) | Mar 15, 2021 |
| Apple         | MacBookPro9,2               | [e5b4868f6d](https://linux-hardware.org/?probe=e5b4868f6d) | Mar 15, 2021 |
| Lenovo        | ThinkPad T420 4236EJ8       | [15fd4b07d7](https://linux-hardware.org/?probe=15fd4b07d7) | Mar 14, 2021 |
| Dell          | Latitude E5420              | [89b141dfe7](https://linux-hardware.org/?probe=89b141dfe7) | Mar 11, 2021 |
| Dell          | Latitude E5420              | [1d9f651a21](https://linux-hardware.org/?probe=1d9f651a21) | Mar 11, 2021 |
| YiFang        | NXM1012BCP                  | [321104f919](https://linux-hardware.org/?probe=321104f919) | Mar 02, 2021 |
| YiFang        | NXM1012BCP                  | [689a0a7984](https://linux-hardware.org/?probe=689a0a7984) | Mar 02, 2021 |
| Packard Be... | ENTE11HC                    | [e96028c294](https://linux-hardware.org/?probe=e96028c294) | Mar 01, 2021 |
| HP            | Notebook                    | [aa01f63a6a](https://linux-hardware.org/?probe=aa01f63a6a) | Feb 28, 2021 |
| HP            | Notebook                    | [36d62b8339](https://linux-hardware.org/?probe=36d62b8339) | Feb 28, 2021 |
| Lenovo        | V510-14IKB 80WR             | [fc338623ab](https://linux-hardware.org/?probe=fc338623ab) | Feb 27, 2021 |
| MSI           | Bravo 15 A4DDR              | [9bec1814a1](https://linux-hardware.org/?probe=9bec1814a1) | Feb 24, 2021 |
| HP            | Pavilion dv7                | [8592f4c025](https://linux-hardware.org/?probe=8592f4c025) | Feb 23, 2021 |
| HP            | EliteBook 850 G3            | [0159818f3c](https://linux-hardware.org/?probe=0159818f3c) | Feb 22, 2021 |
| Acer          | TravelMate P643-M           | [096216b249](https://linux-hardware.org/?probe=096216b249) | Feb 22, 2021 |
| Lenovo        | ThinkPad T410 25376B8       | [de7bf8efee](https://linux-hardware.org/?probe=de7bf8efee) | Feb 20, 2021 |
| HP            | EliteBook 2740p             | [13520f47b2](https://linux-hardware.org/?probe=13520f47b2) | Feb 19, 2021 |
| Acer          | Aspire VN7-591G             | [bc2d4ed095](https://linux-hardware.org/?probe=bc2d4ed095) | Feb 18, 2021 |
| HP            | ProBook 650 G1              | [239d40566e](https://linux-hardware.org/?probe=239d40566e) | Feb 18, 2021 |
| HP            | 255 G2                      | [00f7f8adc6](https://linux-hardware.org/?probe=00f7f8adc6) | Feb 16, 2021 |
| HP            | 255 G2                      | [e7c30a1f46](https://linux-hardware.org/?probe=e7c30a1f46) | Feb 16, 2021 |
| Acer          | TravelMate 6594             | [8d386ea5a9](https://linux-hardware.org/?probe=8d386ea5a9) | Feb 15, 2021 |
| Purism        | Librem 13 v4                | [af4ad81769](https://linux-hardware.org/?probe=af4ad81769) | Feb 13, 2021 |
| HP            | 620                         | [101229cb11](https://linux-hardware.org/?probe=101229cb11) | Feb 09, 2021 |
| HP            | Laptop 15-da0xxx            | [b01bec9bdc](https://linux-hardware.org/?probe=b01bec9bdc) | Feb 09, 2021 |
| HP            | 530                         | [cd817322c7](https://linux-hardware.org/?probe=cd817322c7) | Feb 08, 2021 |
| HP            | ProBook 6460b               | [1591c890ac](https://linux-hardware.org/?probe=1591c890ac) | Feb 07, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Lenovo        | ThinkPad E580 20KS000EZA    | [086c30adbd](https://linux-hardware.org/?probe=086c30adbd) | Feb 03, 2021 |
| Dell          | Latitude 5590               | [196742e426](https://linux-hardware.org/?probe=196742e426) | Feb 02, 2021 |
| HP            | ProBook 430 G5              | [88a8fe1d45](https://linux-hardware.org/?probe=88a8fe1d45) | Feb 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [2d403e6b99](https://linux-hardware.org/?probe=2d403e6b99) | Jan 31, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [e3fd95697c](https://linux-hardware.org/?probe=e3fd95697c) | Jan 31, 2021 |
| HP            | EliteBook 850 G3            | [492e34ec5b](https://linux-hardware.org/?probe=492e34ec5b) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| Mustek        | W650SR                      | [093806c2aa](https://linux-hardware.org/?probe=093806c2aa) | Jan 20, 2021 |
| HP            | 530 Notebook PC(KD092AA#... | [f551313213](https://linux-hardware.org/?probe=f551313213) | Jan 20, 2021 |
| Lenovo        | ThinkPad T410 25374A5       | [5d131c8a55](https://linux-hardware.org/?probe=5d131c8a55) | Jan 19, 2021 |
| Mustek        | W650SR                      | [df9d2e0b6e](https://linux-hardware.org/?probe=df9d2e0b6e) | Jan 19, 2021 |
| ASUSTek       | K52F                        | [8852b30ffb](https://linux-hardware.org/?probe=8852b30ffb) | Jan 15, 2021 |
| ASUSTek       | K52F                        | [f939607deb](https://linux-hardware.org/?probe=f939607deb) | Jan 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a3e5bd489](https://linux-hardware.org/?probe=5a3e5bd489) | Jan 12, 2021 |
| Mustek        | W650SR                      | [959dcafda5](https://linux-hardware.org/?probe=959dcafda5) | Jan 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b6b5391249](https://linux-hardware.org/?probe=b6b5391249) | Jan 12, 2021 |
| Dell          | Precision 7750              | [9cae2308d3](https://linux-hardware.org/?probe=9cae2308d3) | Jan 12, 2021 |
| Dell          | Precision 7750              | [4480bd05df](https://linux-hardware.org/?probe=4480bd05df) | Jan 12, 2021 |
| Lenovo        | ThinkPad W530 24472L5       | [3b79402144](https://linux-hardware.org/?probe=3b79402144) | Jan 12, 2021 |
| Acer          | TravelMate 6594             | [134cac6028](https://linux-hardware.org/?probe=134cac6028) | Jan 11, 2021 |
| Acer          | TravelMate 6594             | [d015dcdb11](https://linux-hardware.org/?probe=d015dcdb11) | Jan 11, 2021 |
| Dell          | Inspiron 3537               | [1912a7c4ea](https://linux-hardware.org/?probe=1912a7c4ea) | Jan 07, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [6a1e524903](https://linux-hardware.org/?probe=6a1e524903) | Jan 06, 2021 |
| Dell          | Inspiron 3537               | [02eda08f03](https://linux-hardware.org/?probe=02eda08f03) | Jan 06, 2021 |
| Dell          | Inspiron 3580               | [ecabe519f7](https://linux-hardware.org/?probe=ecabe519f7) | Jan 06, 2021 |
| HP            | 530 Notebook PC(KD092AA#... | [5c3ff90c04](https://linux-hardware.org/?probe=5c3ff90c04) | Jan 04, 2021 |
| Sony          | VPCCB17FG                   | [9e2a14cddd](https://linux-hardware.org/?probe=9e2a14cddd) | Jan 02, 2021 |
| Dell          | XPS 13 9300                 | [0d6592676a](https://linux-hardware.org/?probe=0d6592676a) | Jan 02, 2021 |
| Dell          | System XPS L502X            | [acfba5cf21](https://linux-hardware.org/?probe=acfba5cf21) | Jan 01, 2021 |
| Dell          | G3 3579                     | [3f9b834132](https://linux-hardware.org/?probe=3f9b834132) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [32c6bfaacf](https://linux-hardware.org/?probe=32c6bfaacf) | Dec 29, 2020 |
| Dell          | Inspiron 3580               | [1fb2f225a2](https://linux-hardware.org/?probe=1fb2f225a2) | Dec 26, 2020 |
| HP            | 15                          | [e9ea153217](https://linux-hardware.org/?probe=e9ea153217) | Dec 23, 2020 |
| HP            | 15                          | [df1bd71a5b](https://linux-hardware.org/?probe=df1bd71a5b) | Dec 23, 2020 |
| Dell          | Inspiron N5110              | [79dc0bb6e5](https://linux-hardware.org/?probe=79dc0bb6e5) | Dec 21, 2020 |
| HP            | 530 Notebook PC(KD092AA#... | [6b5a6b87d0](https://linux-hardware.org/?probe=6b5a6b87d0) | Dec 20, 2020 |
| Acer          | Aspire A315-54K             | [4a57537b9c](https://linux-hardware.org/?probe=4a57537b9c) | Dec 17, 2020 |
| Lenovo        | ThinkPad T560 20FJS3CR00    | [f027e7d759](https://linux-hardware.org/?probe=f027e7d759) | Dec 15, 2020 |
| HP            | ProBook 450 G2              | [f874634860](https://linux-hardware.org/?probe=f874634860) | Dec 15, 2020 |
| HP            | 250 G6 Notebook PC          | [724522a6d1](https://linux-hardware.org/?probe=724522a6d1) | Dec 14, 2020 |
| Apple         | MacBookPro7,1               | [fe895f311c](https://linux-hardware.org/?probe=fe895f311c) | Dec 13, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [4f4c7dcb90](https://linux-hardware.org/?probe=4f4c7dcb90) | Dec 12, 2020 |
| Unknown       | Unknown                     | [ef997b1269](https://linux-hardware.org/?probe=ef997b1269) | Dec 12, 2020 |
| Unknown       | Unknown                     | [a49b1a585c](https://linux-hardware.org/?probe=a49b1a585c) | Dec 12, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [c4d727c0fe](https://linux-hardware.org/?probe=c4d727c0fe) | Dec 12, 2020 |
| Lenovo        | ThinkPad T560 20FJS3CR00    | [a2a24647bc](https://linux-hardware.org/?probe=a2a24647bc) | Dec 10, 2020 |
| HP            | 530 Notebook PC(KD092AA#... | [795405460c](https://linux-hardware.org/?probe=795405460c) | Dec 10, 2020 |
| Acer          | TravelMate 6594             | [ae03da366b](https://linux-hardware.org/?probe=ae03da366b) | Dec 02, 2020 |
| Toshiba       | Satellite L655              | [084b1edabe](https://linux-hardware.org/?probe=084b1edabe) | Nov 28, 2020 |
| Razer         | Blade                       | [e18d620129](https://linux-hardware.org/?probe=e18d620129) | Nov 26, 2020 |
| MSI           | GF65 Thin 10SDR             | [d7689a3ea9](https://linux-hardware.org/?probe=d7689a3ea9) | Nov 26, 2020 |
| Lenovo        | ThinkPad W530 24475FG       | [1cb4ed8103](https://linux-hardware.org/?probe=1cb4ed8103) | Nov 26, 2020 |
| Lenovo        | ThinkPad W530 24475FG       | [4661924b42](https://linux-hardware.org/?probe=4661924b42) | Nov 25, 2020 |
| MSI           | GF65 Thin 10SDR             | [20666074cc](https://linux-hardware.org/?probe=20666074cc) | Nov 25, 2020 |
| MSI           | GF65 Thin 10SDR             | [aa40dc132e](https://linux-hardware.org/?probe=aa40dc132e) | Nov 24, 2020 |
| MSI           | GF65 Thin 10SDR             | [e330dc888c](https://linux-hardware.org/?probe=e330dc888c) | Nov 24, 2020 |
| Dell          | System XPS L502X            | [cb6a73b345](https://linux-hardware.org/?probe=cb6a73b345) | Nov 22, 2020 |
| Lenovo        | ThinkPad W530 24472L5       | [eb70db095c](https://linux-hardware.org/?probe=eb70db095c) | Nov 21, 2020 |
| Toshiba       | Satellite L300              | [14ba3c1b1e](https://linux-hardware.org/?probe=14ba3c1b1e) | Nov 21, 2020 |
| MSI           | GF65 Thin 10SDR             | [7459ea254f](https://linux-hardware.org/?probe=7459ea254f) | Nov 20, 2020 |
| MSI           | GF65 Thin 10SDR             | [ccd5e2e9b7](https://linux-hardware.org/?probe=ccd5e2e9b7) | Nov 20, 2020 |
| Acer          | TMP453-MG                   | [78f12b69b1](https://linux-hardware.org/?probe=78f12b69b1) | Nov 20, 2020 |
| Acer          | Aspire A515-51              | [9d17b487c9](https://linux-hardware.org/?probe=9d17b487c9) | Nov 19, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [8d5d3ceb39](https://linux-hardware.org/?probe=8d5d3ceb39) | Nov 19, 2020 |
| HP            | ProBook 4740s               | [52eecd895e](https://linux-hardware.org/?probe=52eecd895e) | Nov 19, 2020 |
| HP            | Laptop 15-db0xxx            | [2bc5d144a7](https://linux-hardware.org/?probe=2bc5d144a7) | Nov 15, 2020 |
| Lenovo        | ThinkPad T410 25374A5       | [5872fcfdcc](https://linux-hardware.org/?probe=5872fcfdcc) | Nov 10, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [c8b05a074e](https://linux-hardware.org/?probe=c8b05a074e) | Nov 08, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [2f2b8ffce4](https://linux-hardware.org/?probe=2f2b8ffce4) | Nov 07, 2020 |
| Acer          | TMP453-MG                   | [1d55620e4d](https://linux-hardware.org/?probe=1d55620e4d) | Nov 05, 2020 |
| HP            | ProBook 430 G5              | [47fa01cd3c](https://linux-hardware.org/?probe=47fa01cd3c) | Nov 05, 2020 |
| HP            | 530                         | [1b2646e26e](https://linux-hardware.org/?probe=1b2646e26e) | Nov 04, 2020 |
| Packard Be... | EasyNote ENTG81BA           | [554b898a54](https://linux-hardware.org/?probe=554b898a54) | Nov 04, 2020 |
| Dell          | Precision M2800             | [bffd355a04](https://linux-hardware.org/?probe=bffd355a04) | Nov 03, 2020 |
| Dell          | Precision 7740              | [77dfb73496](https://linux-hardware.org/?probe=77dfb73496) | Nov 02, 2020 |
| HP            | Notebook                    | [e7ef3fa0c5](https://linux-hardware.org/?probe=e7ef3fa0c5) | Oct 29, 2020 |
| Dell          | Inspiron 1564               | [181df38a9d](https://linux-hardware.org/?probe=181df38a9d) | Oct 28, 2020 |
| Dell          | G3 3590                     | [26424b5cc7](https://linux-hardware.org/?probe=26424b5cc7) | Oct 22, 2020 |
| HP            | Compaq nc6320 (RH367ET#A... | [558f06c315](https://linux-hardware.org/?probe=558f06c315) | Oct 22, 2020 |
| Dell          | Precision 7740              | [703a5701df](https://linux-hardware.org/?probe=703a5701df) | Oct 19, 2020 |
| Dell          | G3 3590                     | [4506998df7](https://linux-hardware.org/?probe=4506998df7) | Oct 19, 2020 |
| Dell          | G3 3590                     | [e373695d27](https://linux-hardware.org/?probe=e373695d27) | Oct 19, 2020 |
| HP            | Pavilion g7                 | [09258aec8a](https://linux-hardware.org/?probe=09258aec8a) | Oct 18, 2020 |
| HP            | Laptop 15-db0xxx            | [a4ff2b6824](https://linux-hardware.org/?probe=a4ff2b6824) | Oct 14, 2020 |
| HP            | Laptop 15-db0xxx            | [79804afa01](https://linux-hardware.org/?probe=79804afa01) | Oct 14, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [365a05297a](https://linux-hardware.org/?probe=365a05297a) | Oct 10, 2020 |
| HP            | Pavilion g7                 | [1efaadf26c](https://linux-hardware.org/?probe=1efaadf26c) | Oct 10, 2020 |
| ASUSTek       | X540LA                      | [258c7e5c59](https://linux-hardware.org/?probe=258c7e5c59) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c37e90e5ba](https://linux-hardware.org/?probe=c37e90e5ba) | Oct 02, 2020 |
| HP            | Pavilion g7                 | [9230541054](https://linux-hardware.org/?probe=9230541054) | Sep 27, 2020 |
| Dell          | XPS 15 9570                 | [356de884b8](https://linux-hardware.org/?probe=356de884b8) | Sep 26, 2020 |
| Dell          | XPS 15 9570                 | [4d17cc2498](https://linux-hardware.org/?probe=4d17cc2498) | Sep 26, 2020 |
| ASUSTek       | X541UAK                     | [3c6317b054](https://linux-hardware.org/?probe=3c6317b054) | Sep 25, 2020 |
| Lenovo        | ThinkPad E490 20N8000GZA    | [a2cab9674f](https://linux-hardware.org/?probe=a2cab9674f) | Sep 21, 2020 |
| Acer          | TravelMate 5730             | [263c747308](https://linux-hardware.org/?probe=263c747308) | Sep 20, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [158b2e89af](https://linux-hardware.org/?probe=158b2e89af) | Sep 20, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [38c0fd0b5e](https://linux-hardware.org/?probe=38c0fd0b5e) | Sep 20, 2020 |
| HP            | 650                         | [530347b45b](https://linux-hardware.org/?probe=530347b45b) | Sep 15, 2020 |
| HP            | 650                         | [fa6359ea31](https://linux-hardware.org/?probe=fa6359ea31) | Sep 15, 2020 |
| Packard Be... | DOA150                      | [e8e13f5c29](https://linux-hardware.org/?probe=e8e13f5c29) | Sep 15, 2020 |
| HP            | Laptop 15-bs1xx             | [54f64b9271](https://linux-hardware.org/?probe=54f64b9271) | Sep 14, 2020 |
| HP            | Laptop 15-bs1xx             | [a2c238595d](https://linux-hardware.org/?probe=a2c238595d) | Sep 14, 2020 |
| Lenovo        | ThinkPad T560 20FJS2QH00    | [b8a2c9ffb6](https://linux-hardware.org/?probe=b8a2c9ffb6) | Sep 12, 2020 |
| Acer          | Aspire A315-33              | [ba7f97b25f](https://linux-hardware.org/?probe=ba7f97b25f) | Sep 11, 2020 |
| Lenovo        | Z50-75 80EC                 | [4b6d8031d3](https://linux-hardware.org/?probe=4b6d8031d3) | Sep 09, 2020 |
| Dell          | Inspiron 3558               | [c532a136d9](https://linux-hardware.org/?probe=c532a136d9) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK AH532              | [813ee792ff](https://linux-hardware.org/?probe=813ee792ff) | Sep 07, 2020 |
| Dell          | G5 5587                     | [9e3a5fe32f](https://linux-hardware.org/?probe=9e3a5fe32f) | Sep 07, 2020 |
| Lenovo        | ThinkPad T560 20FJS2QH00    | [eb58725fb3](https://linux-hardware.org/?probe=eb58725fb3) | Sep 07, 2020 |
| HP            | Laptop 15-rb0xx             | [2ef696d3c4](https://linux-hardware.org/?probe=2ef696d3c4) | Sep 04, 2020 |
| Alienware     | 15 R3                       | [99d1babb0c](https://linux-hardware.org/?probe=99d1babb0c) | Sep 04, 2020 |
| Dell          | Inspiron 15-3567            | [d7fbcdbfbe](https://linux-hardware.org/?probe=d7fbcdbfbe) | Sep 03, 2020 |
| Lenovo        | ThinkPad E460 20ET000BZA    | [9594512da6](https://linux-hardware.org/?probe=9594512da6) | Aug 31, 2020 |
| HP            | ProBook 430 G5              | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Acer          | Aspire 7750G                | [91041cbcfb](https://linux-hardware.org/?probe=91041cbcfb) | Aug 28, 2020 |
| Acer          | Aspire 7750G                | [072119fece](https://linux-hardware.org/?probe=072119fece) | Aug 28, 2020 |
| Dell          | Latitude E5510              | [b5daf24624](https://linux-hardware.org/?probe=b5daf24624) | Aug 26, 2020 |
| Toshiba       | Satellite L300              | [d910a7c7f6](https://linux-hardware.org/?probe=d910a7c7f6) | Aug 25, 2020 |
| Gigabyte      | Q1532P                      | [7a2e9494a2](https://linux-hardware.org/?probe=7a2e9494a2) | Aug 24, 2020 |
| Dell          | XPS 15 7590                 | [1ecbfe31cc](https://linux-hardware.org/?probe=1ecbfe31cc) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [d475ab6b1f](https://linux-hardware.org/?probe=d475ab6b1f) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [25f98c006e](https://linux-hardware.org/?probe=25f98c006e) | Aug 23, 2020 |
| Dell          | Latitude E6530              | [c2d9b7b8f9](https://linux-hardware.org/?probe=c2d9b7b8f9) | Aug 23, 2020 |
| Toshiba       | Satellite L300              | [5f5af9383f](https://linux-hardware.org/?probe=5f5af9383f) | Aug 18, 2020 |
| Dell          | Inspiron 15-3567            | [d074e75c19](https://linux-hardware.org/?probe=d074e75c19) | Aug 15, 2020 |
| Dell          | Latitude E5510              | [48dc8dde92](https://linux-hardware.org/?probe=48dc8dde92) | Aug 15, 2020 |
| Lenovo        | ThinkPad T520 42405GG       | [b56a1ac043](https://linux-hardware.org/?probe=b56a1ac043) | Aug 13, 2020 |
| Acer          | TravelMate 5730             | [348008255f](https://linux-hardware.org/?probe=348008255f) | Aug 12, 2020 |
| ASUSTek       | X540SA                      | [ae4f0e030f](https://linux-hardware.org/?probe=ae4f0e030f) | Aug 11, 2020 |
| Dell          | System XPS L502X            | [9621996153](https://linux-hardware.org/?probe=9621996153) | Aug 11, 2020 |
| Acer          | Aspire A315-33              | [2e6e1fee7d](https://linux-hardware.org/?probe=2e6e1fee7d) | Aug 11, 2020 |
| HP            | Laptop 15-rb0xx             | [c336e9c30d](https://linux-hardware.org/?probe=c336e9c30d) | Aug 10, 2020 |
| HP            | EliteBook 8530p             | [de121e336e](https://linux-hardware.org/?probe=de121e336e) | Aug 10, 2020 |
| HP            | EliteBook 8530p             | [87b8fdd5d0](https://linux-hardware.org/?probe=87b8fdd5d0) | Aug 10, 2020 |
| ASUSTek       | X541UAK                     | [81676db3c8](https://linux-hardware.org/?probe=81676db3c8) | Aug 10, 2020 |
| HP            | EliteBook 2560p             | [d3dfb613fb](https://linux-hardware.org/?probe=d3dfb613fb) | Aug 07, 2020 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [cc43288bbf](https://linux-hardware.org/?probe=cc43288bbf) | Aug 04, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2970... | [9fe0854fe1](https://linux-hardware.org/?probe=9fe0854fe1) | Jul 27, 2020 |
| HP            | Pavilion 15                 | [a0ce170236](https://linux-hardware.org/?probe=a0ce170236) | Jul 27, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7efc08bc3f](https://linux-hardware.org/?probe=7efc08bc3f) | Jul 27, 2020 |
| Mustek        | W150HNM/W170HN              | [cb2e9bf05e](https://linux-hardware.org/?probe=cb2e9bf05e) | Jul 26, 2020 |
| HP            | ENVY 17                     | [fe4340900e](https://linux-hardware.org/?probe=fe4340900e) | Jul 24, 2020 |
| Dell          | XPS 15 7590                 | [cf0e22a73b](https://linux-hardware.org/?probe=cf0e22a73b) | Jul 23, 2020 |
| HP            | Compaq 6730b (FU498ES#AC... | [eafb860249](https://linux-hardware.org/?probe=eafb860249) | Jul 18, 2020 |
| HP            | Compaq 6730b (FU498ES#AC... | [6589c077c1](https://linux-hardware.org/?probe=6589c077c1) | Jul 18, 2020 |
| Acer          | Aspire ES1-531              | [12daf0c779](https://linux-hardware.org/?probe=12daf0c779) | Jul 15, 2020 |
| Acer          | Aspire ES1-531              | [c715d782a7](https://linux-hardware.org/?probe=c715d782a7) | Jul 15, 2020 |
| Dell          | Inspiron 1564               | [6f2fd1c5f5](https://linux-hardware.org/?probe=6f2fd1c5f5) | Jul 13, 2020 |
| HP            | Laptop 15-da1xxx            | [2bafa31949](https://linux-hardware.org/?probe=2bafa31949) | Jul 11, 2020 |
| HP            | EliteBook 8460p             | [690be1abd1](https://linux-hardware.org/?probe=690be1abd1) | Jul 07, 2020 |
| HP            | EliteBook 8460p             | [0a23e6ddb9](https://linux-hardware.org/?probe=0a23e6ddb9) | Jul 07, 2020 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [9d9e59f8a7](https://linux-hardware.org/?probe=9d9e59f8a7) | Jul 06, 2020 |
| HP            | Laptop 15-rb0xx             | [5453a2ab1e](https://linux-hardware.org/?probe=5453a2ab1e) | Jul 06, 2020 |
| PINNACLEMI... | W54_55_94_95_97AU,AUQ       | [10e802c9d2](https://linux-hardware.org/?probe=10e802c9d2) | Jul 05, 2020 |
| PINNACLEMI... | W54_55_94_95_97AU,AUQ       | [d2a15517ae](https://linux-hardware.org/?probe=d2a15517ae) | Jul 05, 2020 |
| Acer          | Aspire ES1-531              | [fcfe22c7f7](https://linux-hardware.org/?probe=fcfe22c7f7) | Jul 04, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [811c58d180](https://linux-hardware.org/?probe=811c58d180) | Jul 03, 2020 |
| HP            | ProBook 450 G3              | [cf66568c1a](https://linux-hardware.org/?probe=cf66568c1a) | Jul 01, 2020 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [f86d13d08b](https://linux-hardware.org/?probe=f86d13d08b) | Jun 30, 2020 |
| ASUSTek       | GL552VW                     | [680865d570](https://linux-hardware.org/?probe=680865d570) | Jun 28, 2020 |
| ASUSTek       | GL552VW                     | [4bd631ea1e](https://linux-hardware.org/?probe=4bd631ea1e) | Jun 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2970... | [7998eb3c9d](https://linux-hardware.org/?probe=7998eb3c9d) | Jun 26, 2020 |
| Acer          | Aspire A315-33              | [6f89973e83](https://linux-hardware.org/?probe=6f89973e83) | Jun 26, 2020 |
| Acer          | Aspire E1-571               | [846c2cfcc2](https://linux-hardware.org/?probe=846c2cfcc2) | Jun 25, 2020 |
| Dell          | Inspiron 15-3567            | [ba23c3d53b](https://linux-hardware.org/?probe=ba23c3d53b) | Jun 21, 2020 |
| HP            | ProBook 4530s               | [9a3677462f](https://linux-hardware.org/?probe=9a3677462f) | Jun 15, 2020 |
| Dell          | Vostro 5581                 | [9cca353931](https://linux-hardware.org/?probe=9cca353931) | Jun 14, 2020 |
| HP            | ProBook 450 G3              | [7c8e952de0](https://linux-hardware.org/?probe=7c8e952de0) | Jun 12, 2020 |
| Dell          | Inspiron 15-3567            | [723f40770e](https://linux-hardware.org/?probe=723f40770e) | Jun 12, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [210e0bbd91](https://linux-hardware.org/?probe=210e0bbd91) | Jun 10, 2020 |
| Dell          | Latitude E5470              | [8e2c9531ee](https://linux-hardware.org/?probe=8e2c9531ee) | Jun 08, 2020 |
| HP            | Pavilion dv6                | [75bb7f58f7](https://linux-hardware.org/?probe=75bb7f58f7) | Jun 07, 2020 |
| Dell          | Inspiron 15-3567            | [042de23941](https://linux-hardware.org/?probe=042de23941) | Jun 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | [e132acbd84](https://linux-hardware.org/?probe=e132acbd84) | Jun 05, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [231469ed54](https://linux-hardware.org/?probe=231469ed54) | Jun 04, 2020 |
| ASUSTek       | F3E                         | [017dbb9885](https://linux-hardware.org/?probe=017dbb9885) | Jun 02, 2020 |
| ASUSTek       | F3E                         | [94392b7fbe](https://linux-hardware.org/?probe=94392b7fbe) | Jun 02, 2020 |
| HP            | Unknown                     | [c9eaaa02f0](https://linux-hardware.org/?probe=c9eaaa02f0) | Jun 02, 2020 |
| Dell          | Inspiron 15-3567            | [8517d04de8](https://linux-hardware.org/?probe=8517d04de8) | Jun 02, 2020 |
| Dell          | Inspiron 15-3567            | [2542efac1a](https://linux-hardware.org/?probe=2542efac1a) | Jun 02, 2020 |
| Apple         | MacBookPro14,1              | [0ecb29970a](https://linux-hardware.org/?probe=0ecb29970a) | May 31, 2020 |
| Apple         | MacBookPro14,1              | [28fa9f025a](https://linux-hardware.org/?probe=28fa9f025a) | May 31, 2020 |
| HP            | 635                         | [4c1e9766eb](https://linux-hardware.org/?probe=4c1e9766eb) | May 30, 2020 |
| Acer          | Swift SF714-52T             | [225373558d](https://linux-hardware.org/?probe=225373558d) | May 28, 2020 |
| Acer          | Swift SF714-52T             | [45777f6233](https://linux-hardware.org/?probe=45777f6233) | May 28, 2020 |
| HP            | Compaq 615                  | [b5764f8ab1](https://linux-hardware.org/?probe=b5764f8ab1) | May 28, 2020 |
| Acer          | TravelMate 5730             | [cbd537f7c5](https://linux-hardware.org/?probe=cbd537f7c5) | May 26, 2020 |
| ASUSTek       | X541NA                      | [2b1ef7d7ca](https://linux-hardware.org/?probe=2b1ef7d7ca) | May 26, 2020 |
| MSI           | GE62 2QF                    | [321d1bd5a9](https://linux-hardware.org/?probe=321d1bd5a9) | May 24, 2020 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [d691e2d0c5](https://linux-hardware.org/?probe=d691e2d0c5) | May 24, 2020 |
| HP            | ProBook 4520s               | [a82abd4f97](https://linux-hardware.org/?probe=a82abd4f97) | May 24, 2020 |
| HP            | ProBook 4520s               | [ad874f6c98](https://linux-hardware.org/?probe=ad874f6c98) | May 24, 2020 |
| Dell          | G3 3579                     | [ec47395462](https://linux-hardware.org/?probe=ec47395462) | May 23, 2020 |
| Dell          | G3 3579                     | [c1b7c40099](https://linux-hardware.org/?probe=c1b7c40099) | May 23, 2020 |
| HP            | ProBook 430 G5              | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | X541NA                      | [8664f78348](https://linux-hardware.org/?probe=8664f78348) | May 18, 2020 |
| Dell          | Inspiron 1564               | [f8beaacc00](https://linux-hardware.org/?probe=f8beaacc00) | May 18, 2020 |
| HP            | Pavilion dv6                | [6e5db16a3d](https://linux-hardware.org/?probe=6e5db16a3d) | May 17, 2020 |
| HP            | Laptop 15-da0xxx            | [f8d707f73e](https://linux-hardware.org/?probe=f8d707f73e) | May 16, 2020 |
| Dell          | Inspiron 1564               | [64684a4b90](https://linux-hardware.org/?probe=64684a4b90) | May 16, 2020 |
| Acer          | Aspire A315-54              | [64bc1caac9](https://linux-hardware.org/?probe=64bc1caac9) | May 14, 2020 |
| Acer          | Aspire A315-54              | [22538b9f97](https://linux-hardware.org/?probe=22538b9f97) | May 13, 2020 |
| HP            | 250 G4 Notebook PC          | [2406267563](https://linux-hardware.org/?probe=2406267563) | May 12, 2020 |
| HP            | 250 G4 Notebook PC          | [7e8fdf4b86](https://linux-hardware.org/?probe=7e8fdf4b86) | May 11, 2020 |
| ASUSTek       | X541NA                      | [0f64cb0bb2](https://linux-hardware.org/?probe=0f64cb0bb2) | May 11, 2020 |
| ASUSTek       | X541NA                      | [8f1e4e6ac0](https://linux-hardware.org/?probe=8f1e4e6ac0) | May 11, 2020 |
| ASUSTek       | Strix GL504GM_GL504GM       | [877b1afb6f](https://linux-hardware.org/?probe=877b1afb6f) | May 10, 2020 |
| Acer          | Aspire E1-571               | [81745dc737](https://linux-hardware.org/?probe=81745dc737) | May 07, 2020 |
| Dell          | Vostro 3550                 | [aeb508b54b](https://linux-hardware.org/?probe=aeb508b54b) | May 07, 2020 |
| Dell          | Inspiron 3521               | [621dd13569](https://linux-hardware.org/?probe=621dd13569) | May 07, 2020 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [927efeb75f](https://linux-hardware.org/?probe=927efeb75f) | May 06, 2020 |
| Dell          | G3 3779                     | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Acer          | Aspire A315-54K             | [45fad98669](https://linux-hardware.org/?probe=45fad98669) | May 04, 2020 |
| Gigabyte      | P65                         | [8fbc34fb32](https://linux-hardware.org/?probe=8fbc34fb32) | May 04, 2020 |
| Dell          | Inspiron 1545               | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| HP            | Unknown                     | [e161ed1b13](https://linux-hardware.org/?probe=e161ed1b13) | May 01, 2020 |
| Acer          | Aspire A315-54              | [9007ac437f](https://linux-hardware.org/?probe=9007ac437f) | Apr 30, 2020 |
| Acer          | Aspire A315-54              | [e56e6a57f6](https://linux-hardware.org/?probe=e56e6a57f6) | Apr 30, 2020 |
| ASUSTek       | ASUS Gaming FX570UD         | [29954f450a](https://linux-hardware.org/?probe=29954f450a) | Apr 28, 2020 |
| Dell          | Inspiron 1545               | [fed3b2695a](https://linux-hardware.org/?probe=fed3b2695a) | Apr 27, 2020 |
| Dell          | Inspiron N5010              | [a70e19ee19](https://linux-hardware.org/?probe=a70e19ee19) | Apr 27, 2020 |
| HP            | Laptop 15-da0xxx            | [7eee20d7e5](https://linux-hardware.org/?probe=7eee20d7e5) | Apr 26, 2020 |
| Dell          | Inspiron 1545               | [a1b6c234ed](https://linux-hardware.org/?probe=a1b6c234ed) | Apr 25, 2020 |
| Dell          | Latitude E6510              | [f15cdfeb6c](https://linux-hardware.org/?probe=f15cdfeb6c) | Apr 15, 2020 |
| HP            | ProBook 430 G5              | [a1f59e373b](https://linux-hardware.org/?probe=a1f59e373b) | Apr 10, 2020 |
| Dell          | Vostro 5471                 | [031fe22aec](https://linux-hardware.org/?probe=031fe22aec) | Apr 08, 2020 |
| eMachines     | E725                        | [b4f225dd7c](https://linux-hardware.org/?probe=b4f225dd7c) | Apr 04, 2020 |
| HP            | Compaq nc6320 (EY396EA#A... | [737a6eaa7d](https://linux-hardware.org/?probe=737a6eaa7d) | Apr 02, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [65f353ed24](https://linux-hardware.org/?probe=65f353ed24) | Apr 01, 2020 |
| HP            | ProBook 4320s               | [b78e8287b3](https://linux-hardware.org/?probe=b78e8287b3) | Mar 27, 2020 |
| HP            | ProBook 450 G6              | [9e4d8ea0ce](https://linux-hardware.org/?probe=9e4d8ea0ce) | Mar 27, 2020 |
| Acer          | Aspire E1-571               | [628116088e](https://linux-hardware.org/?probe=628116088e) | Mar 26, 2020 |
| HP            | Laptop 15-bs1xx             | [b3f0c20207](https://linux-hardware.org/?probe=b3f0c20207) | Mar 23, 2020 |
| Dell          | Inspiron 3593               | [683e249eac](https://linux-hardware.org/?probe=683e249eac) | Mar 11, 2020 |
| Acer          | Aspire E1-571               | [2152fb6549](https://linux-hardware.org/?probe=2152fb6549) | Mar 10, 2020 |
| Acer          | TravelMate 5760             | [dca1c692d7](https://linux-hardware.org/?probe=dca1c692d7) | Mar 08, 2020 |
| Acer          | Aspire E5-773G              | [b51ba53e10](https://linux-hardware.org/?probe=b51ba53e10) | Mar 06, 2020 |
| Dell          | Latitude E4310              | [234ba00176](https://linux-hardware.org/?probe=234ba00176) | Feb 27, 2020 |
| Acer          | Aspire E5-773G              | [01210c0b0e](https://linux-hardware.org/?probe=01210c0b0e) | Feb 22, 2020 |
| Acer          | Aspire 5100                 | [1312407631](https://linux-hardware.org/?probe=1312407631) | Feb 17, 2020 |
| HP            | ProBook 4530s               | [639dbf3714](https://linux-hardware.org/?probe=639dbf3714) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [0d6a51d929](https://linux-hardware.org/?probe=0d6a51d929) | Feb 16, 2020 |
| Dell          | Vostro 3550                 | [edfe8875af](https://linux-hardware.org/?probe=edfe8875af) | Feb 12, 2020 |
| Dell          | XPS 13 9360                 | [56f48226c5](https://linux-hardware.org/?probe=56f48226c5) | Feb 11, 2020 |
| Dell          | System XPS L702X            | [ea0d918dbc](https://linux-hardware.org/?probe=ea0d918dbc) | Feb 09, 2020 |
| HP            | Pavilion dv6                | [170bcb6796](https://linux-hardware.org/?probe=170bcb6796) | Feb 08, 2020 |
| Dell          | Latitude E6420              | [abf8099af0](https://linux-hardware.org/?probe=abf8099af0) | Feb 07, 2020 |
| Dell          | Inspiron 15-3567            | [451bf983c1](https://linux-hardware.org/?probe=451bf983c1) | Jan 29, 2020 |
| ADSC          | A21R                        | [e753f5a358](https://linux-hardware.org/?probe=e753f5a358) | Jan 25, 2020 |
| ADSC          | A21R                        | [80b05fc52a](https://linux-hardware.org/?probe=80b05fc52a) | Jan 25, 2020 |
| Lenovo        | ThinkPad X250 20CLS65E00    | [23d14de0c7](https://linux-hardware.org/?probe=23d14de0c7) | Jan 24, 2020 |
| Dell          | Vostro 3700                 | [a2fcc4ac0b](https://linux-hardware.org/?probe=a2fcc4ac0b) | Jan 15, 2020 |
| Toshiba       | Satellite Pro C850-F84U     | [43c5790730](https://linux-hardware.org/?probe=43c5790730) | Jan 15, 2020 |
| Toshiba       | Satellite Pro C850-F84U     | [19597039c1](https://linux-hardware.org/?probe=19597039c1) | Jan 14, 2020 |
| Apple         | MacBook2,1                  | [9f544e3b8a](https://linux-hardware.org/?probe=9f544e3b8a) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [713c4952d3](https://linux-hardware.org/?probe=713c4952d3) | Jan 14, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4bcdaf5509](https://linux-hardware.org/?probe=4bcdaf5509) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| Dell          | Inspiron 15-3567            | [41c1bfbdd4](https://linux-hardware.org/?probe=41c1bfbdd4) | Jan 03, 2020 |
| ASUSTek       | Strix GL704GV_GL704GV       | [772f70fa79](https://linux-hardware.org/?probe=772f70fa79) | Jan 01, 2020 |
| Acer          | TMP455-MG                   | [9f0083c2b2](https://linux-hardware.org/?probe=9f0083c2b2) | Dec 28, 2019 |
| ASUSTek       | Strix GL704GV_GL704GV       | [a47d005445](https://linux-hardware.org/?probe=a47d005445) | Dec 26, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7605fc1d79](https://linux-hardware.org/?probe=7605fc1d79) | Dec 23, 2019 |
| Dell          | Inspiron 15-3567            | [86a1799786](https://linux-hardware.org/?probe=86a1799786) | Dec 22, 2019 |
| Acer          | TMP455-MG                   | [e7cf026b7b](https://linux-hardware.org/?probe=e7cf026b7b) | Dec 22, 2019 |
| Panasonic     | FZ55-1                      | [c6b0fb17ab](https://linux-hardware.org/?probe=c6b0fb17ab) | Dec 17, 2019 |
| Dell          | Inspiron 15-3573            | [4aa36c1dd5](https://linux-hardware.org/?probe=4aa36c1dd5) | Dec 10, 2019 |
| Dell          | G3 3779                     | [716cb93844](https://linux-hardware.org/?probe=716cb93844) | Dec 06, 2019 |
| HP            | ZBook 15 G6                 | [bdd15b19b1](https://linux-hardware.org/?probe=bdd15b19b1) | Dec 06, 2019 |
| HP            | Notebook                    | [832aafeb1a](https://linux-hardware.org/?probe=832aafeb1a) | Dec 06, 2019 |
| Acer          | TravelMate 6594             | [da5eb48dbb](https://linux-hardware.org/?probe=da5eb48dbb) | Nov 27, 2019 |
| Dell          | Inspiron N5050              | [f4cae8af59](https://linux-hardware.org/?probe=f4cae8af59) | Nov 19, 2019 |
| HP            | Notebook                    | [b9f3d1de04](https://linux-hardware.org/?probe=b9f3d1de04) | Nov 15, 2019 |
| HP            | Notebook                    | [ee3c3a87f9](https://linux-hardware.org/?probe=ee3c3a87f9) | Nov 15, 2019 |
| Lenovo        | V510-14IKB 80WR             | [649bc0e8ee](https://linux-hardware.org/?probe=649bc0e8ee) | Nov 13, 2019 |
| Lenovo        | V510-14IKB 80WR             | [a21f74c946](https://linux-hardware.org/?probe=a21f74c946) | Nov 13, 2019 |
| HP            | Notebook                    | [6b5304d567](https://linux-hardware.org/?probe=6b5304d567) | Nov 12, 2019 |
| HP            | Notebook                    | [5cc3eb5066](https://linux-hardware.org/?probe=5cc3eb5066) | Nov 11, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [689eb23f13](https://linux-hardware.org/?probe=689eb23f13) | Oct 29, 2019 |
| HP            | ProBook 6560b               | [791c17d2af](https://linux-hardware.org/?probe=791c17d2af) | Oct 26, 2019 |
| CONNEX        | L1470                       | [5e59b4f83c](https://linux-hardware.org/?probe=5e59b4f83c) | Oct 16, 2019 |
| Acer          | Aspire E1-571               | [5ae5b431d6](https://linux-hardware.org/?probe=5ae5b431d6) | Oct 14, 2019 |
| HP            | ProBook 6560b               | [113596c5ef](https://linux-hardware.org/?probe=113596c5ef) | Oct 12, 2019 |
| HP            | Notebook                    | [01242805f0](https://linux-hardware.org/?probe=01242805f0) | Oct 08, 2019 |
| HP            | ProBook 6550b               | [10745db434](https://linux-hardware.org/?probe=10745db434) | Sep 30, 2019 |
| Lenovo        | ThinkPad X201 3680L11       | [c448add7bc](https://linux-hardware.org/?probe=c448add7bc) | Sep 30, 2019 |
| HP            | ProBook 6560b               | [a94a53c453](https://linux-hardware.org/?probe=a94a53c453) | Sep 17, 2019 |
| HP            | ProBook 6560b               | [a95e0f0396](https://linux-hardware.org/?probe=a95e0f0396) | Sep 10, 2019 |
| HP            | ProBook 6560b               | [544a98fd56](https://linux-hardware.org/?probe=544a98fd56) | Sep 09, 2019 |
| Dell          | Inspiron 1525               | [ebb2371a06](https://linux-hardware.org/?probe=ebb2371a06) | Aug 28, 2019 |
| Dell          | Inspiron 1525               | [cdb9ea2eb6](https://linux-hardware.org/?probe=cdb9ea2eb6) | Aug 28, 2019 |
| HP            | ProBook 450 G0              | [4aea7a651a](https://linux-hardware.org/?probe=4aea7a651a) | Aug 27, 2019 |
| HP            | ProBook 450 G2              | [43a52eb758](https://linux-hardware.org/?probe=43a52eb758) | Aug 24, 2019 |
| ASUSTek       | GL553VE                     | [46d0739d29](https://linux-hardware.org/?probe=46d0739d29) | Aug 20, 2019 |
| Lenovo        | ThinkPad T440s 20AQ006LZ... | [4e682ac524](https://linux-hardware.org/?probe=4e682ac524) | Jul 24, 2019 |
| Dell          | Latitude E6410              | [d588cd38c2](https://linux-hardware.org/?probe=d588cd38c2) | Jul 20, 2019 |
| Dell          | Vostro 3350                 | [02a2ac15de](https://linux-hardware.org/?probe=02a2ac15de) | Jul 18, 2019 |
| Lenovo        | ThinkPad L520 5017BB3       | [916fa6f088](https://linux-hardware.org/?probe=916fa6f088) | Jul 14, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [3a996cf854](https://linux-hardware.org/?probe=3a996cf854) | Jul 08, 2019 |
| Dell          | Vostro 3350                 | [3f908b8c67](https://linux-hardware.org/?probe=3f908b8c67) | Jul 02, 2019 |
| HP            | ProBook 4520s               | [bd68794cbe](https://linux-hardware.org/?probe=bd68794cbe) | Jun 19, 2019 |
| HP            | ProBook 4520s               | [bf38f0dbfe](https://linux-hardware.org/?probe=bf38f0dbfe) | Jun 18, 2019 |
| Toshiba       | Satellite L50-A0381         | [8618f4a1cf](https://linux-hardware.org/?probe=8618f4a1cf) | Jun 08, 2019 |
| HP            | EliteBook 8530w (FU462EA... | [e05fe6b4ab](https://linux-hardware.org/?probe=e05fe6b4ab) | May 18, 2019 |
| HP            | EliteBook 8530w (FU462EA... | [224acb078e](https://linux-hardware.org/?probe=224acb078e) | May 17, 2019 |
| HP            | 250 G6 Notebook PC          | [f6ca1a1782](https://linux-hardware.org/?probe=f6ca1a1782) | May 14, 2019 |
| Lenovo        | ThinkPad Edge E530c 3366... | [86e834e0d5](https://linux-hardware.org/?probe=86e834e0d5) | May 07, 2019 |
| Lenovo        | G500 20236                  | [2cc1e7b6e9](https://linux-hardware.org/?probe=2cc1e7b6e9) | May 07, 2019 |
| Apple         | MacBook2,1                  | [06a8da4be5](https://linux-hardware.org/?probe=06a8da4be5) | May 05, 2019 |
| Apple         | MacBook2,1                  | [c98f5d17c5](https://linux-hardware.org/?probe=c98f5d17c5) | May 05, 2019 |
| HP            | ProBook 4530s               | [93916c5a59](https://linux-hardware.org/?probe=93916c5a59) | Apr 12, 2019 |
| HP            | 635                         | [c98b3f711e](https://linux-hardware.org/?probe=c98b3f711e) | Apr 11, 2019 |
| ASUSTek       | Strix GL504GM_GL504GM       | [b1a967e21d](https://linux-hardware.org/?probe=b1a967e21d) | Apr 09, 2019 |
| HP            | 2000                        | [32c8e8239c](https://linux-hardware.org/?probe=32c8e8239c) | Feb 16, 2019 |
| Lenovo        | ThinkPad T410 2537BU0       | [1c48341762](https://linux-hardware.org/?probe=1c48341762) | Dec 18, 2018 |
| Lenovo        | ThinkPad T410 2537BU0       | [f9c9eb5f06](https://linux-hardware.org/?probe=f9c9eb5f06) | Dec 18, 2018 |
| Toshiba       | Satellite C850-F117         | [94f8199a4b](https://linux-hardware.org/?probe=94f8199a4b) | Dec 13, 2018 |
| Dell          | Latitude E6400              | [837615c7fb](https://linux-hardware.org/?probe=837615c7fb) | Nov 30, 2018 |
| Dell          | Latitude E6400              | [e92097f8a8](https://linux-hardware.org/?probe=e92097f8a8) | Nov 29, 2018 |
| Dell          | Latitude E6400              | [c6d1868c6a](https://linux-hardware.org/?probe=c6d1868c6a) | Nov 29, 2018 |
| HP            | Notebook                    | [176d8ea47b](https://linux-hardware.org/?probe=176d8ea47b) | Oct 19, 2018 |
| HP            | Notebook                    | [798c678ca4](https://linux-hardware.org/?probe=798c678ca4) | Oct 19, 2018 |
| Purism        | Librem 15 v3                | [02e23b6024](https://linux-hardware.org/?probe=02e23b6024) | May 21, 2018 |
| Lenovo        | ThinkPad W520 4284B82       | [ec9f5a20b2](https://linux-hardware.org/?probe=ec9f5a20b2) | Mar 05, 2018 |
| Samsung       | 300E4C/300E5C/300E7C        | [d126f4661a](https://linux-hardware.org/?probe=d126f4661a) | Jan 09, 2018 |
| Samsung       | 300E4C/300E5C/300E7C        | [87968fc7d7](https://linux-hardware.org/?probe=87968fc7d7) | Mar 13, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/South_Africa/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 102       | 15.25%  |
| Ubuntu 22.04       | 40        | 5.98%   |
| Ubuntu 18.04       | 38        | 5.68%   |
| Zorin 16           | 26        | 3.89%   |
| KDE neon 20.04     | 20        | 2.99%   |
| Linux Mint 20.3    | 18        | 2.69%   |
| Pop!_OS 21.04      | 14        | 2.09%   |
| Pop!_OS 20.04      | 13        | 1.94%   |
| Linux Mint 20.2    | 12        | 1.79%   |
| Zorin 15           | 11        | 1.64%   |
| Ubuntu 21.04       | 11        | 1.64%   |
| Linux Mint 20.1    | 11        | 1.64%   |
| Arch Rolling       | 11        | 1.64%   |
| Pop!_OS 22.04      | 10        | 1.49%   |
| OpenMandriva 4.2   | 10        | 1.49%   |
| Linux Mint 21.1    | 10        | 1.49%   |
| Linux Mint 19.3    | 10        | 1.49%   |
| Manjaro            | 9         | 1.35%   |
| Ubuntu 19.10       | 8         | 1.2%    |
| Ubuntu 19.04       | 8         | 1.2%    |
| Pop!_OS 20.10      | 8         | 1.2%    |
| Debian 11          | 8         | 1.2%    |
| ArcoLinux Rolling  | 8         | 1.2%    |
| Ubuntu 20.10       | 7         | 1.05%   |
| Linux Mint 20      | 7         | 1.05%   |
| Fedora 37          | 7         | 1.05%   |
| Fedora 35          | 7         | 1.05%   |
| Fedora 34          | 7         | 1.05%   |
| Ubuntu 22.10       | 6         | 0.9%    |
| Linux Mint 21      | 6         | 0.9%    |
| Kubuntu 20.04      | 6         | 0.9%    |
| Ubuntu 23.04       | 5         | 0.75%   |
| OpenMandriva 4.3   | 5         | 0.75%   |
| OpenMandriva 23.01 | 5         | 0.75%   |
| Linux Mint 19.1    | 5         | 0.75%   |
| Arch               | 5         | 0.75%   |
| Ubuntu 21.10       | 4         | 0.6%    |
| Pop!_OS 21.10      | 4         | 0.6%    |
| Linux Mint 19      | 4         | 0.6%    |
| Kubuntu 22.04      | 4         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 221       | 34.53%  |
| Linux Mint    | 82        | 12.81%  |
| Pop!_OS       | 49        | 7.66%   |
| Zorin         | 37        | 5.78%   |
| Fedora        | 29        | 4.53%   |
| KDE neon      | 24        | 3.75%   |
| OpenMandriva  | 23        | 3.59%   |
| Kubuntu       | 17        | 2.66%   |
| Debian        | 16        | 2.5%    |
| Arch          | 16        | 2.5%    |
| Manjaro       | 13        | 2.03%   |
| Kali          | 11        | 1.72%   |
| ArcoLinux     | 8         | 1.25%   |
| Xubuntu       | 7         | 1.09%   |
| openSUSE      | 7         | 1.09%   |
| Endless       | 7         | 1.09%   |
| Elementary    | 7         | 1.09%   |
| Clear Linux   | 6         | 0.94%   |
| Ubuntu Unity  | 5         | 0.78%   |
| Lubuntu       | 4         | 0.63%   |
| Ubuntu Budgie | 3         | 0.47%   |
| ROSA          | 3         | 0.47%   |
| RHEL          | 3         | 0.47%   |
| Parrot        | 3         | 0.47%   |
| Gentoo        | 3         | 0.47%   |
| Garuda Linux  | 3         | 0.47%   |
| Slackware     | 2         | 0.31%   |
| Rocky Linux   | 2         | 0.31%   |
| MX            | 2         | 0.31%   |
| LMDE          | 2         | 0.31%   |
| CentOS        | 2         | 0.31%   |
| BuildRoot     | 2         | 0.31%   |
| Archcraft     | 2         | 0.31%   |
| AlmaLinux     | 2         | 0.31%   |
| Xero          | 1         | 0.16%   |
| UbuntuDDE     | 1         | 0.16%   |
| Ubuntu Studio | 1         | 0.16%   |
| TUXEDO OS     | 1         | 0.16%   |
| Storm OS      | 1         | 0.16%   |
| PureOS        | 1         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.02%   |
| 5.10.14-desktop-1omv4002 | 10        | 1.35%   |
| 5.4.0-58-generic         | 9         | 1.21%   |
| 5.11.0-38-generic        | 9         | 1.21%   |
| 5.4.0-40-generic         | 8         | 1.08%   |
| 5.4.0-72-generic         | 7         | 0.94%   |
| 5.4.0-52-generic         | 7         | 0.94%   |
| 5.4.0-29-generic         | 7         | 0.94%   |
| 5.15.0-52-generic        | 7         | 0.94%   |
| 5.13.0-7614-generic      | 7         | 0.94%   |
| 5.13.0-39-generic        | 7         | 0.94%   |
| 5.11.0-27-generic        | 7         | 0.94%   |
| 5.8.0-43-generic         | 6         | 0.81%   |
| 5.4.0-33-generic         | 6         | 0.81%   |
| 5.4.0-26-generic         | 6         | 0.81%   |
| 5.3.0-28-generic         | 6         | 0.81%   |
| 5.13.0-28-generic        | 6         | 0.81%   |
| 5.0.0-37-generic         | 6         | 0.81%   |
| 6.1.1-desktop-1omv2290   | 5         | 0.67%   |
| 5.8.0-7630-generic       | 5         | 0.67%   |
| 5.4.0-73-generic         | 5         | 0.67%   |
| 5.4.0-56-generic         | 5         | 0.67%   |
| 5.3.0-51-generic         | 5         | 0.67%   |
| 5.19.0-38-generic        | 5         | 0.67%   |
| 5.16.7-desktop-1omv4003  | 5         | 0.67%   |
| 5.15.0-56-generic        | 5         | 0.67%   |
| 5.15.0-48-generic        | 5         | 0.67%   |
| 5.15.0-41-generic        | 5         | 0.67%   |
| 5.11.0-37-generic        | 5         | 0.67%   |
| 6.2.6-76060206-generic   | 4         | 0.54%   |
| 5.8.0-7642-generic       | 4         | 0.54%   |
| 5.8.0-63-generic         | 4         | 0.54%   |
| 5.4.0-91-generic         | 4         | 0.54%   |
| 5.4.0-77-generic         | 4         | 0.54%   |
| 5.4.0-7642-generic       | 4         | 0.54%   |
| 5.4.0-7634-generic       | 4         | 0.54%   |
| 5.4.0-31-generic         | 4         | 0.54%   |
| 5.4.0-113-generic        | 4         | 0.54%   |
| 5.15.0-53-generic        | 4         | 0.54%   |
| 5.13.0-40-generic        | 4         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 138       | 20.06%  |
| 5.15.0  | 60        | 8.72%   |
| 5.11.0  | 55        | 7.99%   |
| 5.8.0   | 47        | 6.83%   |
| 5.13.0  | 46        | 6.69%   |
| 4.15.0  | 35        | 5.09%   |
| 5.3.0   | 31        | 4.51%   |
| 5.19.0  | 25        | 3.63%   |
| 5.10.0  | 18        | 2.62%   |
| 5.0.0   | 16        | 2.33%   |
| 6.2.0   | 13        | 1.89%   |
| 4.18.0  | 11        | 1.6%    |
| 5.10.14 | 10        | 1.45%   |
| 6.1.1   | 7         | 1.02%   |
| 5.14.0  | 7         | 1.02%   |
| 6.2.6   | 6         | 0.87%   |
| 5.17.5  | 6         | 0.87%   |
| 5.16.7  | 6         | 0.87%   |
| 4.19.0  | 4         | 0.58%   |
| 6.4.12  | 3         | 0.44%   |
| 6.1.7   | 3         | 0.44%   |
| 5.16.18 | 3         | 0.44%   |
| 5.15.15 | 3         | 0.44%   |
| 5.14.9  | 3         | 0.44%   |
| 6.4.11  | 2         | 0.29%   |
| 6.1.0   | 2         | 0.29%   |
| 6.0.15  | 2         | 0.29%   |
| 6.0.12  | 2         | 0.29%   |
| 5.18.19 | 2         | 0.29%   |
| 5.18.16 | 2         | 0.29%   |
| 5.17.9  | 2         | 0.29%   |
| 5.16.11 | 2         | 0.29%   |
| 5.14.21 | 2         | 0.29%   |
| 5.12.5  | 2         | 0.29%   |
| 6.5.1   | 1         | 0.15%   |
| 6.4.8   | 1         | 0.15%   |
| 6.4.3   | 1         | 0.15%   |
| 6.4.0   | 1         | 0.15%   |
| 6.3.9   | 1         | 0.15%   |
| 6.3.4   | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 140       | 20.65%  |
| 5.15    | 72        | 10.62%  |
| 5.11    | 59        | 8.7%    |
| 5.8     | 52        | 7.67%   |
| 5.13    | 51        | 7.52%   |
| 5.10    | 35        | 5.16%   |
| 4.15    | 35        | 5.16%   |
| 5.3     | 33        | 4.87%   |
| 5.19    | 28        | 4.13%   |
| 6.2     | 26        | 3.83%   |
| 5.0     | 16        | 2.36%   |
| 6.1     | 15        | 2.21%   |
| 5.16    | 14        | 2.06%   |
| 5.14    | 14        | 2.06%   |
| 5.17    | 11        | 1.62%   |
| 4.18    | 11        | 1.62%   |
| 6.0     | 10        | 1.47%   |
| 5.18    | 9         | 1.33%   |
| 6.4     | 8         | 1.18%   |
| 5.7     | 6         | 0.88%   |
| 5.6     | 6         | 0.88%   |
| 5.9     | 5         | 0.74%   |
| 4.19    | 5         | 0.74%   |
| 6.3     | 3         | 0.44%   |
| 5.5     | 3         | 0.44%   |
| 5.12    | 3         | 0.44%   |
| 6.5     | 1         | 0.15%   |
| 5.2     | 1         | 0.15%   |
| 4.9     | 1         | 0.15%   |
| 4.16    | 1         | 0.15%   |
| 4.13    | 1         | 0.15%   |
| 4.12    | 1         | 0.15%   |
| 4.1     | 1         | 0.15%   |
| 3.10    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 597       | 97.39%  |
| i686   | 16        | 2.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 312       | 48.83%  |
| KDE5             | 94        | 14.71%  |
| X-Cinnamon       | 60        | 9.39%   |
| Unknown          | 51        | 7.98%   |
| XFCE             | 41        | 6.42%   |
| KDE              | 21        | 3.29%   |
| MATE             | 14        | 2.19%   |
| Pantheon         | 7         | 1.1%    |
| Cinnamon         | 7         | 1.1%    |
| Unity            | 5         | 0.78%   |
| LXDE             | 4         | 0.63%   |
| Deepin           | 4         | 0.63%   |
| LXQt             | 3         | 0.47%   |
| KDE4             | 3         | 0.47%   |
| Budgie           | 3         | 0.47%   |
| lightdm-xsession | 2         | 0.31%   |
| i3               | 2         | 0.31%   |
| GNOME Flashback  | 2         | 0.31%   |
| Awesome          | 2         | 0.31%   |
| GNOME Classic    | 1         | 0.16%   |
| bspwm            | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 503       | 78.59%  |
| Wayland | 107       | 16.72%  |
| Unknown | 20        | 3.13%   |
| Tty     | 10        | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 368       | 57.14%  |
| GDM3    | 90        | 13.98%  |
| SDDM    | 74        | 11.49%  |
| LightDM | 52        | 8.07%   |
| GDM     | 47        | 7.3%    |
| TDM     | 11        | 1.71%   |
| KDM     | 2         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_ZA   | 421       | 66.4%   |
| en_US   | 119       | 18.77%  |
| Unknown | 41        | 6.47%   |
| en_GB   | 40        | 6.31%   |
| C       | 7         | 1.1%    |
| fr_FR   | 3         | 0.47%   |
| en_ZW   | 1         | 0.16%   |
| en_BW   | 1         | 0.16%   |
| de_DE   | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 333       | 52.94%  |
| EFI  | 296       | 47.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 503       | 80.22%  |
| Btrfs   | 44        | 7.02%   |
| Overlay | 31        | 4.94%   |
| Tmpfs   | 14        | 2.23%   |
| Xfs     | 12        | 1.91%   |
| Unknown | 12        | 1.91%   |
| Zfs     | 8         | 1.28%   |
| Aufs    | 2         | 0.32%   |
| Ext2    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 402       | 63.61%  |
| GPT     | 185       | 29.27%  |
| MBR     | 45        | 7.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 566       | 90.56%  |
| Yes       | 59        | 9.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 470       | 75.32%  |
| Yes       | 154       | 24.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Dell                        | 144       | 23.49%  |
| Hewlett-Packard             | 143       | 23.33%  |
| Lenovo                      | 114       | 18.6%   |
| ASUSTek Computer            | 53        | 8.65%   |
| Acer                        | 53        | 8.65%   |
| Apple                       | 17        | 2.77%   |
| Toshiba                     | 11        | 1.79%   |
| MSI                         | 8         | 1.31%   |
| Samsung Electronics         | 7         | 1.14%   |
| Packard Bell                | 5         | 0.82%   |
| Standard                    | 4         | 0.65%   |
| Sony                        | 4         | 0.65%   |
| Mustek                      | 4         | 0.65%   |
| MECER                       | 4         | 0.65%   |
| Gigabyte Technology         | 4         | 0.65%   |
| CONNEX                      | 4         | 0.65%   |
| Proline                     | 3         | 0.49%   |
| Fujitsu                     | 3         | 0.49%   |
| Purism                      | 2         | 0.33%   |
| PINNACLEMICRO               | 2         | 0.33%   |
| Panasonic                   | 2         | 0.33%   |
| I-Life Digital Technologies | 2         | 0.33%   |
| HUAWEI                      | 2         | 0.33%   |
| YiFang                      | 1         | 0.16%   |
| WinSome                     | 1         | 0.16%   |
| TCL Communication           | 1         | 0.16%   |
| System76                    | 1         | 0.16%   |
| RIZZEN                      | 1         | 0.16%   |
| Razer                       | 1         | 0.16%   |
| Notebook                    | 1         | 0.16%   |
| LG Electronics              | 1         | 0.16%   |
| LattePanda                  | 1         | 0.16%   |
| Intel                       | 1         | 0.16%   |
| Google                      | 1         | 0.16%   |
| Getac                       | 1         | 0.16%   |
| Fujitsu Siemens             | 1         | 0.16%   |
| eMachines                   | 1         | 0.16%   |
| Clevo                       | 1         | 0.16%   |
| Alienware                   | 1         | 0.16%   |
| ADSC                        | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Inspiron 15-3567                | 10        | 1.63%   |
| Unknown                              | 9         | 1.47%   |
| Lenovo IdeaPad 110-15IBR 80T7        | 5         | 0.82%   |
| HP ProBook 4530s                     | 5         | 0.82%   |
| Dell Latitude E6400                  | 5         | 0.82%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.82%   |
| Acer Aspire E1-571                   | 5         | 0.82%   |
| HP Pavilion dv7                      | 4         | 0.65%   |
| HP Notebook                          | 4         | 0.65%   |
| HP Laptop 15-da0xxx                  | 4         | 0.65%   |
| HP 635                               | 4         | 0.65%   |
| Dell XPS 13 9310                     | 4         | 0.65%   |
| Dell Latitude E6430                  | 4         | 0.65%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 3         | 0.49%   |
| Lenovo G500 20236                    | 3         | 0.49%   |
| HP ProBook 4520s                     | 3         | 0.49%   |
| HP Pavilion dv6                      | 3         | 0.49%   |
| HP Laptop 15-dw3xxx                  | 3         | 0.49%   |
| HP Laptop 15-bs1xx                   | 3         | 0.49%   |
| HP Laptop 15-bs0xx                   | 3         | 0.49%   |
| HP EliteBook 840 G3                  | 3         | 0.49%   |
| HP 620                               | 3         | 0.49%   |
| Dell Latitude E6530                  | 3         | 0.49%   |
| Dell Latitude E6420                  | 3         | 0.49%   |
| Dell Latitude D630                   | 3         | 0.49%   |
| Dell Latitude 5490                   | 3         | 0.49%   |
| Dell Inspiron 3580                   | 3         | 0.49%   |
| Apple MacBookPro9,2                  | 3         | 0.49%   |
| Apple MacBookPro16,1                 | 3         | 0.49%   |
| Acer Aspire A315-54K                 | 3         | 0.49%   |
| Toshiba Satellite L655               | 2         | 0.33%   |
| Samsung 300E4C/300E5C/300E7C         | 2         | 0.33%   |
| Panasonic CF-19ADNAXDY               | 2         | 0.33%   |
| MECER YA13Q20-DP_PRO                 | 2         | 0.33%   |
| Lenovo V510-14IKB 80WR               | 2         | 0.33%   |
| Lenovo ThinkPad X250 20CLS65E00      | 2         | 0.33%   |
| Lenovo ThinkPad T410 25376B8         | 2         | 0.33%   |
| Lenovo ThinkPad Edge E540 20C600HHZA | 2         | 0.33%   |
| Lenovo IdeaPad S145-15AST 81N3       | 2         | 0.33%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 55        | 8.97%   |
| Lenovo ThinkPad        | 54        | 8.81%   |
| Dell Inspiron          | 43        | 7.01%   |
| Lenovo IdeaPad         | 39        | 6.36%   |
| Acer Aspire            | 35        | 5.71%   |
| HP ProBook             | 32        | 5.22%   |
| HP Laptop              | 20        | 3.26%   |
| HP EliteBook           | 20        | 3.26%   |
| ASUS VivoBook          | 18        | 2.94%   |
| HP Pavilion            | 16        | 2.61%   |
| Dell XPS               | 13        | 2.12%   |
| Toshiba Satellite      | 10        | 1.63%   |
| Dell Vostro            | 10        | 1.63%   |
| Unknown                | 9         | 1.47%   |
| HP Compaq              | 8         | 1.31%   |
| Dell Precision         | 7         | 1.14%   |
| Acer TravelMate        | 7         | 1.14%   |
| HP 250                 | 6         | 0.98%   |
| Dell G3                | 6         | 0.98%   |
| HP ZBook               | 5         | 0.82%   |
| HP 255                 | 5         | 0.82%   |
| HP Notebook            | 4         | 0.65%   |
| HP 635                 | 4         | 0.65%   |
| ASUS ASUS              | 4         | 0.65%   |
| Acer Swift             | 4         | 0.65%   |
| Packard Bell EasyNote  | 3         | 0.49%   |
| Lenovo G500            | 3         | 0.49%   |
| HP ENVY                | 3         | 0.49%   |
| HP 620                 | 3         | 0.49%   |
| HP 530                 | 3         | 0.49%   |
| Fujitsu LIFEBOOK       | 3         | 0.49%   |
| Dell System            | 3         | 0.49%   |
| ASUS ROG               | 3         | 0.49%   |
| Apple MacBookPro9      | 3         | 0.49%   |
| Apple MacBookPro16     | 3         | 0.49%   |
| Samsung 300E4C         | 2         | 0.33%   |
| Purism Librem          | 2         | 0.33%   |
| Panasonic CF-19ADNAXDY | 2         | 0.33%   |
| MECER YA13Q20-DP       | 2         | 0.33%   |
| Lenovo Yoga            | 2         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 70        | 11.42%  |
| 2011 | 62        | 10.11%  |
| 2012 | 51        | 8.32%   |
| 2016 | 47        | 7.67%   |
| 2013 | 47        | 7.67%   |
| 2020 | 46        | 7.5%    |
| 2019 | 45        | 7.34%   |
| 2017 | 41        | 6.69%   |
| 2010 | 37        | 6.04%   |
| 2021 | 34        | 5.55%   |
| 2008 | 34        | 5.55%   |
| 2015 | 30        | 4.89%   |
| 2014 | 25        | 4.08%   |
| 2009 | 16        | 2.61%   |
| 2007 | 13        | 2.12%   |
| 2022 | 11        | 1.79%   |
| 2006 | 3         | 0.49%   |
| 2023 | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 613       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 545       | 87.48%  |
| Enabled  | 78        | 12.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 609       | 99.35%  |
| Yes  | 4         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 161       | 25.84%  |
| 3.01-4.0    | 153       | 24.56%  |
| 16.01-24.0  | 96        | 15.41%  |
| 8.01-16.0   | 93        | 14.93%  |
| 1.01-2.0    | 45        | 7.22%   |
| 32.01-64.0  | 39        | 6.26%   |
| 2.01-3.0    | 17        | 2.73%   |
| 24.01-32.0  | 7         | 1.12%   |
| 64.01-256.0 | 7         | 1.12%   |
| 0.51-1.0    | 5         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 248       | 36.05%  |
| 2.01-3.0   | 189       | 27.47%  |
| 4.01-8.0   | 91        | 13.23%  |
| 3.01-4.0   | 74        | 10.76%  |
| 0.51-1.0   | 42        | 6.1%    |
| 8.01-16.0  | 35        | 5.09%   |
| 16.01-24.0 | 4         | 0.58%   |
| 0.01-0.5   | 3         | 0.44%   |
| 32.01-64.0 | 1         | 0.15%   |
| 24.01-32.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 436       | 69.76%  |
| 2      | 158       | 25.28%  |
| 3      | 16        | 2.56%   |
| 0      | 11        | 1.76%   |
| 4      | 4         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 324       | 52.51%  |
| Yes       | 293       | 47.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 536       | 87.44%  |
| No        | 77        | 12.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 594       | 96.9%   |
| No        | 19        | 3.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 482       | 77.24%  |
| No        | 142       | 22.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| South Africa | 613       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Johannesburg     | 176       | 26.43%  |
| Cape Town        | 163       | 24.47%  |
| Pretoria         | 72        | 10.81%  |
| Durban           | 31        | 4.65%   |
| Port Elizabeth   | 21        | 3.15%   |
| Centurion        | 14        | 2.1%    |
| Sandton          | 9         | 1.35%   |
| East London      | 9         | 1.35%   |
| Pietermaritzburg | 8         | 1.2%    |
| Somerset West    | 6         | 0.9%    |
| Potchefstroom    | 6         | 0.9%    |
| Benoni           | 6         | 0.9%    |
| Roodepoort       | 5         | 0.75%   |
| Midrand          | 5         | 0.75%   |
| Bloemfontein     | 5         | 0.75%   |
| Thabazimbi       | 4         | 0.6%    |
| Stellenbosch     | 4         | 0.6%    |
| Randburg         | 4         | 0.6%    |
| Polokwane        | 4         | 0.6%    |
| Boksburg         | 4         | 0.6%    |
| Bellville        | 4         | 0.6%    |
| Alberton         | 4         | 0.6%    |
| White River      | 3         | 0.45%   |
| Port Alfred      | 3         | 0.45%   |
| Middelburg       | 3         | 0.45%   |
| Klerksdorp       | 3         | 0.45%   |
| Hermanus         | 3         | 0.45%   |
| George           | 3         | 0.45%   |
| Edenvale         | 3         | 0.45%   |
| Witbank          | 2         | 0.3%    |
| Vanderbijlpark   | 2         | 0.3%    |
| Tzaneen          | 2         | 0.3%    |
| Standerton       | 2         | 0.3%    |
| Sabie            | 2         | 0.3%    |
| Oudtshoorn       | 2         | 0.3%    |
| Nelspruit        | 2         | 0.3%    |
| Mokopane         | 2         | 0.3%    |
| Louis Trichardt  | 2         | 0.3%    |
| Lichtenburg      | 2         | 0.3%    |
| Kempton Park     | 2         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 131       | 155    | 16.93%  |
| Seagate                   | 115       | 167    | 14.86%  |
| Toshiba                   | 90        | 107    | 11.63%  |
| Samsung Electronics       | 73        | 93     | 9.43%   |
| Unknown                   | 48        | 60     | 6.2%    |
| Hitachi                   | 34        | 45     | 4.39%   |
| HGST                      | 27        | 33     | 3.49%   |
| SanDisk                   | 26        | 36     | 3.36%   |
| Kingston                  | 25        | 29     | 3.23%   |
| SK hynix                  | 21        | 24     | 2.71%   |
| Intel                     | 16        | 21     | 2.07%   |
| Silicon Motion            | 15        | 23     | 1.94%   |
| A-DATA Technology         | 14        | 20     | 1.81%   |
| Transcend                 | 13        | 16     | 1.68%   |
| Crucial                   | 13        | 13     | 1.68%   |
| Micron Technology         | 9         | 10     | 1.16%   |
| TO Exter                  | 8         | 9      | 1.03%   |
| Apple                     | 8         | 10     | 1.03%   |
| KIOXIA                    | 5         | 5      | 0.65%   |
| Fujitsu                   | 5         | 6      | 0.65%   |
| Netac                     | 4         | 4      | 0.52%   |
| Hikvision                 | 4         | 4      | 0.52%   |
| Hewlett-Packard           | 4         | 5      | 0.52%   |
| LITEONIT                  | 3         | 4      | 0.39%   |
| LITEON                    | 3         | 3      | 0.39%   |
| HS-SSD-E100               | 3         | 4      | 0.39%   |
| Gigabyte Technology       | 3         | 4      | 0.39%   |
| External                  | 3         | 3      | 0.39%   |
| Apacer                    | 3         | 4      | 0.39%   |
| Unknown                   | 3         | 3      | 0.39%   |
| Rogueware                 | 2         | 2      | 0.26%   |
| Plextor                   | 2         | 2      | 0.26%   |
| Phison                    | 2         | 2      | 0.26%   |
| Patriot                   | 2         | 2      | 0.26%   |
| Mushkin                   | 2         | 4      | 0.26%   |
| Micron/Crucial Technology | 2         | 2      | 0.26%   |
| Lexar                     | 2         | 2      | 0.26%   |
| Kingmax                   | 2         | 2      | 0.26%   |
| JMicron Technology        | 2         | 2      | 0.26%   |
| HS-SSD-C100               | 2         | 3      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 28        | 3.49%   |
| Toshiba MQ01ABF050 500GB               | 17        | 2.12%   |
| Unknown MMC Card  32GB                 | 14        | 1.75%   |
| Toshiba MQ04ABF100 1TB                 | 14        | 1.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 12        | 1.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 11        | 1.37%   |
| Toshiba MQ01ABD100 1TB                 | 10        | 1.25%   |
| HGST HTS721010A9E630 1TB               | 9         | 1.12%   |
| Toshiba MQ01ACF050 500GB               | 8         | 1%      |
| TO Exter nal USB 3.0 120GB             | 8         | 1%      |
| Seagate ST500LT012-1DG142 500GB        | 8         | 1%      |
| HGST HTS541010A9E680 1TB               | 8         | 1%      |
| WDC WD10SPZX-60Z10T0 1TB               | 7         | 0.87%   |
| Unknown MMC Card  64GB                 | 7         | 0.87%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 7         | 0.87%   |
| Samsung NVMe SSD Drive 512GB           | 7         | 0.87%   |
| Hitachi HTS543232A7A384 320GB          | 6         | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 5         | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 5         | 0.62%   |
| Toshiba NVMe SSD Drive 512GB           | 5         | 0.62%   |
| WDC WD10SPZX-00Z10T0 1TB               | 4         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB               | 4         | 0.5%    |
| SK hynix NVMe SSD Drive 256GB          | 4         | 0.5%    |
| Seagate ST9500423AS 500GB              | 4         | 0.5%    |
| Seagate ST9320325AS 320GB              | 4         | 0.5%    |
| Seagate ST500LM030-2E717D 500GB        | 4         | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB         | 4         | 0.5%    |
| Intel NVMe SSD Drive 512GB             | 4         | 0.5%    |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 3         | 0.37%   |
| WDC WD5000BUCT-63PUZY0 500GB           | 3         | 0.37%   |
| WDC WD3200BEKT-60V5T1 320GB            | 3         | 0.37%   |
| WDC WD10SPZX-24Z10 1TB                 | 3         | 0.37%   |
| WDC WD10JPVX-75JC3T0 1TB               | 3         | 0.37%   |
| WDC WD10JPVX-60JC3T0 1TB               | 3         | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB               | 3         | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB            | 3         | 0.37%   |
| Unknown SC16G  16GB                    | 3         | 0.37%   |
| Unknown MMC Card  16GB                 | 3         | 0.37%   |
| Unknown MMC Card  128GB                | 3         | 0.37%   |
| Transcend TS256GSSD230S 256GB          | 3         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 111       | 156    | 30.49%  |
| WDC                 | 99        | 116    | 27.2%   |
| Toshiba             | 73        | 86     | 20.05%  |
| Hitachi             | 34        | 45     | 9.34%   |
| HGST                | 27        | 33     | 7.42%   |
| Fujitsu             | 5         | 6      | 1.37%   |
| Samsung Electronics | 4         | 4      | 1.1%    |
| Unknown             | 3         | 3      | 0.82%   |
| External            | 3         | 3      | 0.82%   |
| Apple               | 3         | 3      | 0.82%   |
| HGST HTS            | 2         | 2      | 0.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 45     | 17.5%   |
| WDC                 | 27        | 33     | 13.5%   |
| Kingston            | 18        | 22     | 9%      |
| SanDisk             | 16        | 19     | 8%      |
| Transcend           | 12        | 15     | 6%      |
| Crucial             | 11        | 11     | 5.5%    |
| A-DATA Technology   | 11        | 17     | 5.5%    |
| TO Exter            | 8         | 9      | 4%      |
| Toshiba             | 6         | 7      | 3%      |
| Micron Technology   | 5         | 6      | 2.5%    |
| SK hynix            | 4         | 5      | 2%      |
| Seagate             | 4         | 8      | 2%      |
| Netac               | 4         | 4      | 2%      |
| Intel               | 4         | 6      | 2%      |
| LITEONIT            | 3         | 4      | 1.5%    |
| Apacer              | 3         | 4      | 1.5%    |
| Rogueware           | 2         | 2      | 1%      |
| Plextor             | 2         | 2      | 1%      |
| LITEON              | 2         | 2      | 1%      |
| Lexar               | 2         | 2      | 1%      |
| Kingmax             | 2         | 2      | 1%      |
| Hewlett-Packard     | 2         | 2      | 1%      |
| Gigabyte Technology | 2         | 3      | 1%      |
| Corsair             | 2         | 4      | 1%      |
| China               | 2         | 2      | 1%      |
| Union Memory        | 1         | 1      | 0.5%    |
| StoreJet            | 1         | 1      | 0.5%    |
| Radeon              | 1         | 1      | 0.5%    |
| Patriot             | 1         | 1      | 0.5%    |
| OCZ                 | 1         | 1      | 0.5%    |
| Neo Forza           | 1         | 1      | 0.5%    |
| MyDigitalSSD        | 1         | 1      | 0.5%    |
| Hypertec            | 1         | 1      | 0.5%    |
| HS-SSD-E100         | 1         | 1      | 0.5%    |
| Hikvision           | 1         | 1      | 0.5%    |
| AFOX                | 1         | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 356       | 457    | 48.24%  |
| SSD     | 183       | 247    | 24.8%   |
| NVMe    | 140       | 190    | 18.97%  |
| MMC     | 46        | 60     | 6.23%   |
| Unknown | 13        | 17     | 1.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 481       | 681    | 68.52%  |
| NVMe | 140       | 190    | 19.94%  |
| MMC  | 46        | 60     | 6.55%   |
| SAS  | 35        | 40     | 4.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 342       | 464    | 63.81%  |
| 0.51-1.0   | 180       | 224    | 33.58%  |
| 1.01-2.0   | 10        | 10     | 1.87%   |
| 3.01-4.0   | 3         | 5      | 0.56%   |
| 4.01-10.0  | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 185       | 28.16%  |
| 101-250        | 157       | 23.9%   |
| 501-1000       | 121       | 18.42%  |
| 1001-2000      | 54        | 8.22%   |
| 51-100         | 40        | 6.09%   |
| 1-20           | 35        | 5.33%   |
| 21-50          | 25        | 3.81%   |
| More than 3000 | 15        | 2.28%   |
| 2001-3000      | 14        | 2.13%   |
| Unknown        | 11        | 1.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 226       | 32.75%  |
| 21-50          | 139       | 20.14%  |
| 51-100         | 95        | 13.77%  |
| 101-250        | 88        | 12.75%  |
| 251-500        | 68        | 9.86%   |
| 501-1000       | 43        | 6.23%   |
| 1001-2000      | 12        | 1.74%   |
| Unknown        | 11        | 1.59%   |
| 2001-3000      | 5         | 0.72%   |
| More than 3000 | 3         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                | 3         | 4      | 9.09%   |
| Seagate ST320LT007-9ZV142 320GB       | 3         | 3      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 4      | 9.09%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 6.06%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 3.03%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 3.03%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 3.03%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 3.03%   |
| Toshiba MK5065GSXF 500GB              | 1         | 1      | 3.03%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD | 1         | 1      | 3.03%   |
| Seagate ST9500423AS 500GB             | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB             | 1         | 3      | 3.03%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 3.03%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 3.03%   |
| Micron Technology 1100 SATA 256GB SSD | 1         | 1      | 3.03%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 3.03%   |
| Kingston SH103S3240G 240GB SSD        | 1         | 1      | 3.03%   |
| Intel SSDSCKKF240H6L 240GB            | 1         | 2      | 3.03%   |
| Intel SSDSC2BF240A4L 240GB            | 1         | 2      | 3.03%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 3.03%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 1      | 3.03%   |
| Hitachi HTS542512K9SA00 120GB         | 1         | 1      | 3.03%   |
| HGST HTS725050A7E630 500GB            | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 12        | 16     | 37.5%   |
| Toshiba           | 5         | 6      | 15.63%  |
| WDC               | 3         | 3      | 9.38%   |
| Hitachi           | 3         | 3      | 9.38%   |
| HGST              | 3         | 3      | 9.38%   |
| Kingston          | 2         | 2      | 6.25%   |
| Intel             | 2         | 4      | 6.25%   |
| SK hynix          | 1         | 1      | 3.13%   |
| Micron Technology | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 16     | 46.15%  |
| Toshiba | 5         | 6      | 19.23%  |
| WDC     | 3         | 3      | 11.54%  |
| Hitachi | 3         | 3      | 11.54%  |
| HGST    | 3         | 3      | 11.54%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 31     | 81.25%  |
| SSD  | 6         | 8      | 18.75%  |

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
| Detected | 441       | 692    | 68.58%  |
| Works    | 170       | 240    | 26.44%  |
| Malfunc  | 32        | 39     | 4.98%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 500       | 72.89%  |
| AMD                              | 39        | 5.69%   |
| Samsung Electronics              | 35        | 5.1%    |
| Toshiba America Info Systems     | 17        | 2.48%   |
| SK hynix                         | 17        | 2.48%   |
| Silicon Motion                   | 17        | 2.48%   |
| SanDisk                          | 14        | 2.04%   |
| Kingston Technology Company      | 7         | 1.02%   |
| KIOXIA                           | 6         | 0.87%   |
| Apple                            | 5         | 0.73%   |
| Phison Electronics               | 4         | 0.58%   |
| Nvidia                           | 4         | 0.58%   |
| Micron/Crucial Technology        | 4         | 0.58%   |
| Micron Technology                | 4         | 0.58%   |
| ADATA Technology                 | 4         | 0.58%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.29%   |
| Union Memory (Shenzhen)          | 1         | 0.15%   |
| Solid State Storage Technology   | 1         | 0.15%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |
| Shenzhen Longsys Electronics     | 1         | 0.15%   |
| Lite-On Technology               | 1         | 0.15%   |
| Lenovo                           | 1         | 0.15%   |
| Biwin Storage Technology         | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 74        | 9.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 70        | 9.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 49        | 6.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 39        | 5.23%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 28        | 3.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 21        | 2.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 21        | 2.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 21        | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 18        | 2.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 18        | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 18        | 2.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 17        | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 16        | 2.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 15        | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 15        | 2.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 13        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 13        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 13        | 1.74%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 12        | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 12        | 1.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 10        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 10        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 9         | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 9         | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 8         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 8         | 1.07%   |
| Samsung NVMe SSD Controller 980                                                        | 7         | 0.94%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 7         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 7         | 0.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 6         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 5         | 0.67%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 5         | 0.67%   |
| Intel SSD 660P Series                                                                  | 5         | 0.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 5         | 0.67%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 5         | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 0.67%   |
| SK hynix BC511 NVMe SSD                                                                | 4         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 0.54%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 4         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 439       | 61.57%  |
| NVMe | 142       | 19.92%  |
| RAID | 86        | 12.06%  |
| IDE  | 46        | 6.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 559       | 91.19%  |
| AMD    | 54        | 8.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 2.12%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 12        | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 11        | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 11        | 1.79%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 11        | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 10        | 1.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 10        | 1.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 1.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 10        | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 9         | 1.47%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 9         | 1.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 8         | 1.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 1.31%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 1.31%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 1.31%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 8         | 1.31%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 8         | 1.31%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 8         | 1.31%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 7         | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.98%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 6         | 0.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 6         | 0.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 6         | 0.98%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 6         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 6         | 0.98%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 6         | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.82%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 5         | 0.82%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 5         | 0.82%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz    | 5         | 0.82%   |
| Intel Celeron CPU N3050 @ 1.60GHz       | 5         | 0.82%   |
| AMD E-450 APU with Radeon HD Graphics   | 5         | 0.82%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 4         | 0.65%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 4         | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 166       | 27.08%  |
| Intel Core i7           | 164       | 26.75%  |
| Intel Core i3           | 62        | 10.11%  |
| Intel Celeron           | 57        | 9.3%    |
| Other                   | 36        | 5.87%   |
| Intel Core 2 Duo        | 34        | 5.55%   |
| Intel Atom              | 15        | 2.45%   |
| AMD Ryzen 7             | 14        | 2.28%   |
| Intel Pentium           | 7         | 1.14%   |
| AMD Ryzen 5             | 7         | 1.14%   |
| AMD E                   | 7         | 1.14%   |
| AMD A4                  | 5         | 0.82%   |
| Intel Core i9           | 4         | 0.65%   |
| Intel Genuine           | 3         | 0.49%   |
| Intel Celeron Dual-Core | 3         | 0.49%   |
| AMD E2                  | 3         | 0.49%   |
| Intel Pentium Dual-Core | 2         | 0.33%   |
| Intel Pentium Dual      | 2         | 0.33%   |
| Intel Core Duo          | 2         | 0.33%   |
| Intel Core 2            | 2         | 0.33%   |
| AMD Ryzen 9             | 2         | 0.33%   |
| AMD E1                  | 2         | 0.33%   |
| AMD A6                  | 2         | 0.33%   |
| Intel Pentium Silver    | 1         | 0.16%   |
| Intel Celeron M         | 1         | 0.16%   |
| AMD Turion II Dual-Core | 1         | 0.16%   |
| AMD Turion 64 Mobile    | 1         | 0.16%   |
| AMD Ryzen 7 PRO         | 1         | 0.16%   |
| AMD Ryzen 5 PRO         | 1         | 0.16%   |
| AMD Ryzen 3             | 1         | 0.16%   |
| AMD FX                  | 1         | 0.16%   |
| AMD Athlon X2           | 1         | 0.16%   |
| AMD Athlon II           | 1         | 0.16%   |
| AMD Athlon 64 X2        | 1         | 0.16%   |
| AMD A10                 | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 370       | 60.36%  |
| 4      | 167       | 27.24%  |
| 6      | 30        | 4.89%   |
| 8      | 26        | 4.24%   |
| 1      | 13        | 2.12%   |
| 10     | 3         | 0.49%   |
| 16     | 2         | 0.33%   |
| 14     | 1         | 0.16%   |
| 3      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 613       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 457       | 74.43%  |
| 1      | 157       | 25.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 603       | 98.05%  |
| 32-bit         | 6         | 0.98%   |
| Unknown        | 6         | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 190       | 29.5%   |
| 0x206a7    | 50        | 7.76%   |
| 0x306a9    | 32        | 4.97%   |
| 0x406e3    | 31        | 4.81%   |
| 0x806e9    | 30        | 4.66%   |
| 0x806ea    | 21        | 3.26%   |
| 0x20655    | 21        | 3.26%   |
| 0x906ea    | 18        | 2.8%    |
| 0x306d4    | 17        | 2.64%   |
| 0x1067a    | 17        | 2.64%   |
| 0x806c1    | 16        | 2.48%   |
| 0x406c4    | 16        | 2.48%   |
| 0x306c3    | 16        | 2.48%   |
| 0x806ec    | 15        | 2.33%   |
| 0x40651    | 12        | 1.86%   |
| 0x906e9    | 10        | 1.55%   |
| 0x06006705 | 9         | 1.4%    |
| 0xa0652    | 8         | 1.24%   |
| 0x6fd      | 8         | 1.24%   |
| 0x506e3    | 8         | 1.24%   |
| 0x506c9    | 7         | 1.09%   |
| 0x806eb    | 6         | 0.93%   |
| 0x406c3    | 6         | 0.93%   |
| 0x20652    | 6         | 0.93%   |
| 0x10676    | 5         | 0.78%   |
| 0x706e5    | 4         | 0.62%   |
| 0x10661    | 4         | 0.62%   |
| 0x906ed    | 3         | 0.47%   |
| 0x806d1    | 3         | 0.47%   |
| 0x706a8    | 3         | 0.47%   |
| 0x706a1    | 3         | 0.47%   |
| 0x30678    | 3         | 0.47%   |
| 0x0a50000c | 3         | 0.47%   |
| 0x05000119 | 3         | 0.47%   |
| 0x6f6      | 2         | 0.31%   |
| 0x6ec      | 2         | 0.31%   |
| 0x30661    | 2         | 0.31%   |
| 0x106e5    | 2         | 0.31%   |
| 0x106ca    | 2         | 0.31%   |
| 0x106c2    | 2         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 132       | 21.53%  |
| SandyBridge      | 67        | 10.93%  |
| IvyBridge        | 47        | 7.67%   |
| Skylake          | 44        | 7.18%   |
| Haswell          | 41        | 6.69%   |
| Westmere         | 37        | 6.04%   |
| Penryn           | 32        | 5.22%   |
| Silvermont       | 31        | 5.06%   |
| Broadwell        | 24        | 3.92%   |
| TigerLake        | 23        | 3.75%   |
| Core             | 20        | 3.26%   |
| Icelake          | 12        | 1.96%   |
| Excavator        | 11        | 1.79%   |
| Goldmont         | 10        | 1.63%   |
| Zen 3            | 9         | 1.47%   |
| Goldmont plus    | 9         | 1.47%   |
| CometLake        | 9         | 1.47%   |
| Unknown          | 9         | 1.47%   |
| Bobcat           | 8         | 1.31%   |
| Zen 2            | 6         | 0.98%   |
| Bonnell          | 6         | 0.98%   |
| Alderlake Hybrid | 5         | 0.82%   |
| Zen+             | 4         | 0.65%   |
| P6               | 3         | 0.49%   |
| Zen              | 2         | 0.33%   |
| Nehalem          | 2         | 0.33%   |
| K8 Hammer        | 2         | 0.33%   |
| K10              | 2         | 0.33%   |
| Jaguar           | 2         | 0.33%   |
| Tremont          | 1         | 0.16%   |
| Steamroller      | 1         | 0.16%   |
| Puma             | 1         | 0.16%   |
| K8 & K10 hybrid  | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 523       | 67.92%  |
| Nvidia                           | 147       | 19.09%  |
| AMD                              | 99        | 12.86%  |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 62        | 7.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 45        | 5.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 4.16%   |
| Intel HD Graphics 620                                                                    | 32        | 4.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 3.9%    |
| Intel UHD Graphics 620                                                                   | 29        | 3.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 3.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 3.15%   |
| Intel HD Graphics 5500                                                                   | 23        | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 2.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 22        | 2.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 2.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 2.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 1.51%   |
| Intel HD Graphics 630                                                                    | 11        | 1.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 10        | 1.26%   |
| Intel HD Graphics 500                                                                    | 9         | 1.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 1.01%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.88%   |
| Nvidia GM108M [GeForce MX130]                                                            | 7         | 0.88%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.88%   |
| Intel HD Graphics 530                                                                    | 7         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.76%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.76%   |
| AMD Renoir                                                                               | 6         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.63%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 5         | 0.63%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 373       | 60.75%  |
| Intel + Nvidia | 114       | 18.57%  |
| 1 x AMD        | 52        | 8.47%   |
| Intel + AMD    | 35        | 5.7%    |
| 1 x Nvidia     | 26        | 4.23%   |
| AMD + Nvidia   | 7         | 1.14%   |
| 2 x AMD        | 5         | 0.81%   |
| 2 x Intel      | 1         | 0.16%   |
| 1 x SiS        | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 527       | 85%     |
| Proprietary | 82        | 13.23%  |
| Unknown     | 11        | 1.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 457       | 72.08%  |
| 1.01-2.0   | 64        | 10.09%  |
| 0.01-0.5   | 42        | 6.62%   |
| 3.01-4.0   | 27        | 4.26%   |
| 0.51-1.0   | 21        | 3.31%   |
| 5.01-6.0   | 13        | 2.05%   |
| 7.01-8.0   | 5         | 0.79%   |
| 2.01-3.0   | 5         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 129       | 17.48%  |
| LG Display              | 110       | 14.91%  |
| BOE                     | 108       | 14.63%  |
| Chimei Innolux          | 92        | 12.47%  |
| Samsung Electronics     | 84        | 11.38%  |
| Dell                    | 49        | 6.64%   |
| Goldstar                | 26        | 3.52%   |
| Chi Mei Optoelectronics | 26        | 3.52%   |
| Apple                   | 17        | 2.3%    |
| Sharp                   | 14        | 1.9%    |
| Lenovo                  | 14        | 1.9%    |
| LG Philips              | 9         | 1.22%   |
| Philips                 | 6         | 0.81%   |
| PANDA                   | 6         | 0.81%   |
| Hewlett-Packard         | 5         | 0.68%   |
| AOC                     | 4         | 0.54%   |
| Toshiba                 | 3         | 0.41%   |
| SKY                     | 3         | 0.41%   |
| Fujitsu Siemens         | 3         | 0.41%   |
| Quanta Display          | 2         | 0.27%   |
| Panasonic               | 2         | 0.27%   |
| VST                     | 1         | 0.14%   |
| VIE                     | 1         | 0.14%   |
| Unknown                 | 1         | 0.14%   |
| Tatung                  | 1         | 0.14%   |
| STD                     | 1         | 0.14%   |
| Sony                    | 1         | 0.14%   |
| SLD                     | 1         | 0.14%   |
| SKK                     | 1         | 0.14%   |
| SKG                     | 1         | 0.14%   |
| SEEYOO                  | 1         | 0.14%   |
| Olevia                  | 1         | 0.14%   |
| MStar                   | 1         | 0.14%   |
| Microsoft               | 1         | 0.14%   |
| LTM                     | 1         | 0.14%   |
| KDC                     | 1         | 0.14%   |
| KDB                     | 1         | 0.14%   |
| InnoLux Display         | 1         | 0.14%   |
| InfoVision              | 1         | 0.14%   |
| HKC                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 13        | 1.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 10        | 1.33%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 9         | 1.19%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 8         | 1.06%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 0.93%   |
| LG Display LCD Monitor LGD02AC 1366x768 340x190mm 15.3-inch              | 6         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 6         | 0.8%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.66%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 5         | 0.66%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 4         | 0.53%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 4         | 0.53%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.53%   |
| Dell SE2419HR DELF113 1920x1080 527x296mm 23.8-inch                      | 4         | 0.53%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                       | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.53%   |
| Samsung Electronics S19A33x SAM7120 1366x768 410x230mm 18.5-inch         | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4845 1280x800 331x207mm 15.4-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.4%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 3         | 0.4%    |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 3         | 0.4%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.4%    |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 3         | 0.4%    |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch              | 3         | 0.4%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 3         | 0.4%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 3         | 0.4%    |
| Goldstar W2343 GSM5700 1920x1080 474x296mm 22.0-inch                     | 3         | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 3         | 0.4%    |
| Dell S3220DGF DELD0F2 2560x1440 697x392mm 31.5-inch                      | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 3         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 285       | 41.24%  |
| 1920x1080 (FHD)    | 230       | 33.29%  |
| 1280x800 (WXGA)    | 38        | 5.5%    |
| 1600x900 (HD+)     | 37        | 5.35%   |
| 1920x1200 (WUXGA)  | 16        | 2.32%   |
| 3840x2160 (4K)     | 14        | 2.03%   |
| 2560x1440 (QHD)    | 14        | 2.03%   |
| 1440x900 (WXGA+)   | 13        | 1.88%   |
| 1680x1050 (WSXGA+) | 8         | 1.16%   |
| 1280x1024 (SXGA)   | 7         | 1.01%   |
| 1360x768           | 4         | 0.58%   |
| 1024x768 (XGA)     | 4         | 0.58%   |
| 3072x1920          | 3         | 0.43%   |
| 2880x1800          | 3         | 0.43%   |
| 2560x1080          | 3         | 0.43%   |
| 1024x600           | 3         | 0.43%   |
| 3840x1080          | 2         | 0.29%   |
| 1600x1200          | 2         | 0.29%   |
| 2880x1920          | 1         | 0.14%   |
| 2288x1287          | 1         | 0.14%   |
| 1x1                | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1680x945           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 382       | 51.07%  |
| 13      | 66        | 8.82%   |
| 14      | 58        | 7.75%   |
| 17      | 55        | 7.35%   |
| 23      | 33        | 4.41%   |
| 24      | 27        | 3.61%   |
| 21      | 15        | 2.01%   |
| 27      | 13        | 1.74%   |
| 18      | 10        | 1.34%   |
| 12      | 10        | 1.34%   |
| 31      | 9         | 1.2%    |
| Unknown | 9         | 1.2%    |
| 19      | 8         | 1.07%   |
| 22      | 7         | 0.94%   |
| 20      | 7         | 0.94%   |
| 16      | 6         | 0.8%    |
| 11      | 6         | 0.8%    |
| 10      | 4         | 0.53%   |
| 72      | 3         | 0.4%    |
| 40      | 3         | 0.4%    |
| 34      | 3         | 0.4%    |
| 48      | 2         | 0.27%   |
| 32      | 2         | 0.27%   |
| 86      | 1         | 0.13%   |
| 84      | 1         | 0.13%   |
| 64      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 479       | 64.64%  |
| 501-600     | 66        | 8.91%   |
| 351-400     | 59        | 7.96%   |
| 201-300     | 48        | 6.48%   |
| 401-500     | 47        | 6.34%   |
| 601-700     | 10        | 1.35%   |
| Unknown     | 9         | 1.21%   |
| 1001-1500   | 8         | 1.08%   |
| 701-800     | 5         | 0.67%   |
| 801-900     | 4         | 0.54%   |
| 1501-2000   | 4         | 0.54%   |
| 101-200     | 1         | 0.13%   |
| 1-100       | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 531       | 83.75%  |
| 16/10   | 78        | 12.3%   |
| 4/3     | 7         | 1.1%    |
| 5/4     | 5         | 0.79%   |
| 3/2     | 4         | 0.63%   |
| 32/9    | 3         | 0.47%   |
| 21/9    | 3         | 0.47%   |
| 0.56    | 1         | 0.16%   |
| 0.00    | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 381       | 51.35%  |
| 81-90          | 104       | 14.02%  |
| 201-250        | 71        | 9.57%   |
| 121-130        | 48        | 6.47%   |
| 71-80          | 20        | 2.7%    |
| 151-200        | 18        | 2.43%   |
| 351-500        | 14        | 1.89%   |
| 141-150        | 14        | 1.89%   |
| 301-350        | 13        | 1.75%   |
| 61-70          | 10        | 1.35%   |
| Unknown        | 10        | 1.35%   |
| More than 1000 | 9         | 1.21%   |
| 501-1000       | 7         | 0.94%   |
| 51-60          | 6         | 0.81%   |
| 111-120        | 6         | 0.81%   |
| 251-300        | 4         | 0.54%   |
| 41-50          | 3         | 0.4%    |
| 131-140        | 2         | 0.27%   |
| 1-40           | 1         | 0.13%   |
| 91-100         | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 300       | 41.55%  |
| 121-160       | 218       | 30.19%  |
| 51-100        | 153       | 21.19%  |
| 161-240       | 21        | 2.91%   |
| 1-50          | 13        | 1.8%    |
| Unknown       | 9         | 1.25%   |
| More than 240 | 8         | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 473       | 74.49%  |
| 2     | 136       | 21.42%  |
| 3     | 16        | 2.52%   |
| 0     | 9         | 1.42%   |
| 4     | 1         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 342       | 33.14%  |
| Intel                             | 302       | 29.26%  |
| Qualcomm Atheros                  | 153       | 14.83%  |
| Broadcom                          | 72        | 6.98%   |
| Dell                              | 28        | 2.71%   |
| Broadcom Limited                  | 15        | 1.45%   |
| Samsung Electronics               | 14        | 1.36%   |
| Ralink                            | 12        | 1.16%   |
| Huawei Technologies               | 12        | 1.16%   |
| Marvell Technology Group          | 11        | 1.07%   |
| MediaTek                          | 7         | 0.68%   |
| Ericsson Business Mobile Networks | 7         | 0.68%   |
| JMicron Technology                | 6         | 0.58%   |
| TP-Link                           | 5         | 0.48%   |
| Sierra Wireless                   | 5         | 0.48%   |
| Hewlett-Packard                   | 5         | 0.48%   |
| ASIX Electronics                  | 5         | 0.48%   |
| Apple                             | 4         | 0.39%   |
| Xiaomi                            | 2         | 0.19%   |
| Spreadtrum Communications         | 2         | 0.19%   |
| Nvidia                            | 2         | 0.19%   |
| Lenovo                            | 2         | 0.19%   |
| Arduino SA                        | 2         | 0.19%   |
| ZyXEL Communications              | 1         | 0.1%    |
| ZyDAS                             | 1         | 0.1%    |
| U-Blox                            | 1         | 0.1%    |
| TRENDnet                          | 1         | 0.1%    |
| Toshiba                           | 1         | 0.1%    |
| Texas Instruments                 | 1         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.1%    |
| Ralink Technology                 | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| Microchip Technology              | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| HMD Global                        | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Exar                              | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| Attansic Technology               | 1         | 0.1%    |
| ASUSTek Computer                  | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 202       | 16.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 6.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 35        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 29        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 28        | 2.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28        | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 26        | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 19        | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 1.36%   |
| Intel Wireless 8260                                               | 17        | 1.36%   |
| Intel Wi-Fi 6 AX201                                               | 17        | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 1.2%    |
| Intel Wi-Fi 6 AX200                                               | 15        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.2%    |
| Intel Centrino Advanced-N 6200                                    | 14        | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 1.04%   |
| Intel Wireless 7265                                               | 12        | 0.96%   |
| Intel Wireless 3165                                               | 11        | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.8%    |
| Realtek 802.11n WLAN Adapter                                      | 10        | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 10        | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 10        | 0.8%    |
| Intel Wireless 3160                                               | 10        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 10        | 0.8%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 10        | 0.8%    |
| Intel Centrino Ultimate-N 6300                                    | 10        | 0.8%    |
| Broadcom BCM43228 802.11a/b/g/n                                   | 10        | 0.8%    |
| Intel Wireless 7260                                               | 9         | 0.72%   |
| Intel WiFi Link 5100                                              | 9         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.72%   |
| Intel Centrino Wireless-N 2230                                    | 8         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 287       | 45.56%  |
| Qualcomm Atheros                | 139       | 22.06%  |
| Realtek Semiconductor           | 93        | 14.76%  |
| Broadcom                        | 54        | 8.57%   |
| Dell                            | 14        | 2.22%   |
| Ralink                          | 12        | 1.9%    |
| Broadcom Limited                | 8         | 1.27%   |
| MediaTek                        | 6         | 0.95%   |
| Sierra Wireless                 | 5         | 0.79%   |
| TP-Link                         | 4         | 0.63%   |
| ZyXEL Communications            | 1         | 0.16%   |
| ZyDAS                           | 1         | 0.16%   |
| TRENDnet                        | 1         | 0.16%   |
| Ralink Technology               | 1         | 0.16%   |
| Qualcomm Atheros Communications | 1         | 0.16%   |
| Linksys                         | 1         | 0.16%   |
| Fibocom                         | 1         | 0.16%   |
| ASUSTek Computer                | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 35        | 5.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 4.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 28        | 4.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 26        | 4.11%   |
| Intel Wireless 8265 / 8275                                              | 19        | 3%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 2.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 2.69%   |
| Intel Wireless 8260                                                     | 17        | 2.69%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 2.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 17        | 2.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 15        | 2.37%   |
| Intel Wi-Fi 6 AX200                                                     | 15        | 2.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 2.37%   |
| Intel Centrino Advanced-N 6200                                          | 14        | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 2.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 2.05%   |
| Intel Wireless 7265                                                     | 12        | 1.9%    |
| Intel Wireless 3165                                                     | 11        | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.58%   |
| Realtek 802.11n WLAN Adapter                                            | 10        | 1.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 1.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 1.58%   |
| Intel Wireless 3160                                                     | 10        | 1.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 10        | 1.58%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 10        | 1.58%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 1.58%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 10        | 1.58%   |
| Intel Wireless 7260                                                     | 9         | 1.42%   |
| Intel WiFi Link 5100                                                    | 9         | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 1.42%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.26%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 7         | 1.11%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                    | 7         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.95%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 5         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.79%   |
| Intel Ultimate N WiFi Link 5300                                         | 5         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 315       | 55.17%  |
| Intel                            | 131       | 22.94%  |
| Broadcom                         | 29        | 5.08%   |
| Qualcomm Atheros                 | 27        | 4.73%   |
| Samsung Electronics              | 14        | 2.45%   |
| Marvell Technology Group         | 11        | 1.93%   |
| Broadcom Limited                 | 8         | 1.4%    |
| JMicron Technology               | 6         | 1.05%   |
| Huawei Technologies              | 5         | 0.88%   |
| ASIX Electronics                 | 5         | 0.88%   |
| Apple                            | 4         | 0.7%    |
| Xiaomi                           | 2         | 0.35%   |
| Spreadtrum Communications        | 2         | 0.35%   |
| Nvidia                           | 2         | 0.35%   |
| Lenovo                           | 2         | 0.35%   |
| TP-Link                          | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Microchip Technology             | 1         | 0.18%   |
| MediaTek                         | 1         | 0.18%   |
| HMD Global                       | 1         | 0.18%   |
| Hewlett-Packard                  | 1         | 0.18%   |
| DisplayLink                      | 1         | 0.18%   |
| Attansic Technology              | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 202       | 35.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 82        | 14.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 28        | 4.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 19        | 3.29%   |
| Intel 82577LM Gigabit Network Connection                             | 14        | 2.43%   |
| Intel Ethernet Connection I219-LM                                    | 13        | 2.25%   |
| Intel 82567LM Gigabit Network Connection                             | 9         | 1.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 9         | 1.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 7         | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 7         | 1.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 7         | 1.21%   |
| Intel Ethernet Connection I217-LM                                    | 7         | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                                | 7         | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 6         | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                    | 5         | 0.87%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 5         | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 5         | 0.87%   |
| Intel Ethernet Connection I218-LM                                    | 5         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                | 5         | 0.87%   |
| Intel 82579V Gigabit Network Connection                              | 5         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 5         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 4         | 0.69%   |
| Intel Ethernet Connection (7) I219-LM                                | 4         | 0.69%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                    | 4         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                        | 4         | 0.69%   |
| Apple iBridge                                                        | 4         | 0.69%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                     | 3         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 3         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                           | 3         | 0.52%   |
| Intel Ethernet Connection I219-V                                     | 3         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                | 3         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                 | 3         | 0.52%   |
| Intel 82562GT 10/100 Network Connection                              | 3         | 0.52%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 3         | 0.52%   |
| Huawei E353/E3131                                                    | 3         | 0.52%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express             | 3         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2         | 0.35%   |
| Spreadtrum realme Phone                                              | 2         | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 594       | 50.9%   |
| Ethernet | 536       | 45.93%  |
| Modem    | 37        | 3.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 496       | 75.27%  |
| Ethernet | 162       | 24.58%  |
| Modem    | 1         | 0.15%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 499       | 81.4%   |
| 1     | 89        | 14.52%  |
| 0     | 22        | 3.59%   |
| 3     | 3         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 594       | 96.9%   |
| Yes  | 19        | 3.1%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 191       | 39.22%  |
| Qualcomm Atheros Communications | 65        | 13.35%  |
| Realtek Semiconductor           | 51        | 10.47%  |
| Broadcom                        | 26        | 5.34%   |
| Lite-On Technology              | 25        | 5.13%   |
| IMC Networks                    | 23        | 4.72%   |
| Hewlett-Packard                 | 22        | 4.52%   |
| Foxconn / Hon Hai               | 21        | 4.31%   |
| Dell                            | 21        | 4.31%   |
| Ralink                          | 10        | 2.05%   |
| Apple                           | 10        | 2.05%   |
| Toshiba                         | 8         | 1.64%   |
| Cambridge Silicon Radio         | 4         | 0.82%   |
| ASUSTek Computer                | 3         | 0.62%   |
| Alps Electric                   | 2         | 0.41%   |
| Realtek                         | 1         | 0.21%   |
| Mobile Action Technology        | 1         | 0.21%   |
| Logitech                        | 1         | 0.21%   |
| Foxconn International           | 1         | 0.21%   |
| Askey Computer                  | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 81        | 16.63%  |
| Intel AX201 Bluetooth                               | 35        | 7.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 30        | 6.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 5.75%   |
| Realtek Bluetooth Radio                             | 26        | 5.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 3.9%    |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 3.08%   |
| Intel AX200 Bluetooth                               | 14        | 2.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 2.26%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 2.26%   |
| Ralink RT3290 Bluetooth                             | 10        | 2.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 2.05%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 2.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 1.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.64%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 1.64%   |
| Lite-On Bluetooth Device                            | 7         | 1.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 1.03%   |
| IMC Networks Bluetooth Device                       | 5         | 1.03%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.03%   |
| Realtek RTL8723B Bluetooth                          | 4         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.82%   |
| Intel Bluetooth Device                              | 4         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.82%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.62%   |
| IMC Networks Wireless_Device                        | 3         | 0.62%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 3         | 0.62%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 0.62%   |
| Dell Wireless 360 Bluetooth                         | 3         | 0.62%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 0.62%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.62%   |
| Apple Bluetooth Host Controller                     | 3         | 0.62%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.41%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 541       | 73.91%  |
| Nvidia                           | 75        | 10.25%  |
| AMD                              | 67        | 9.15%   |
| C-Media Electronics              | 7         | 0.96%   |
| Logitech                         | 6         | 0.82%   |
| Corsair                          | 4         | 0.55%   |
| Apple                            | 4         | 0.55%   |
| Realtek Semiconductor            | 3         | 0.41%   |
| Lenovo                           | 3         | 0.41%   |
| GN Netcom                        | 2         | 0.27%   |
| Generalplus Technology           | 2         | 0.27%   |
| Conexant Systems                 | 2         | 0.27%   |
| Xiaomi                           | 1         | 0.14%   |
| Tenx Technology                  | 1         | 0.14%   |
| Syntek                           | 1         | 0.14%   |
| Steinberg Soft-und Hardware      | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Schiit Audio                     | 1         | 0.14%   |
| Razer USA                        | 1         | 0.14%   |
| Magic Control Technology         | 1         | 0.14%   |
| M-Audio                          | 1         | 0.14%   |
| JMTek                            | 1         | 0.14%   |
| Hewlett-Packard                  | 1         | 0.14%   |
| Focusrite-Novation               | 1         | 0.14%   |
| Creative Technology              | 1         | 0.14%   |
| Cooler Master                    | 1         | 0.14%   |
| ASUSTek Computer                 | 1         | 0.14%   |
| Afatech                          | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 98        | 11.58%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 63        | 7.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 51        | 6.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 39        | 4.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 28        | 3.31%   |
| Intel Cannon Lake PCH cAVS                                                                        | 26        | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 2.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 2.84%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 2.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 2.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 2.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 2.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 19        | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 2.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 1.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 1.3%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.3%    |
| Intel CM238 HD Audio Controller                                                                   | 11        | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 10        | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.18%   |
| AMD High Definition Audio Controller                                                              | 10        | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.59%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 0.59%   |
| AMD FCH Azalia Controller                                                                         | 5         | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.47%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| SK hynix                       | 98        | 27.53%  |
| Samsung Electronics            | 90        | 25.28%  |
| Kingston                       | 40        | 11.24%  |
| Micron Technology              | 34        | 9.55%   |
| Crucial                        | 19        | 5.34%   |
| Unknown                        | 15        | 4.21%   |
| Transcend                      | 9         | 2.53%   |
| Elpida                         | 8         | 2.25%   |
| Ramaxel Technology             | 7         | 1.97%   |
| Nanya Technology               | 7         | 1.97%   |
| A-DATA Technology              | 7         | 1.97%   |
| Corsair                        | 5         | 1.4%    |
| G.Skill                        | 4         | 1.12%   |
| Unknown (ABCD)                 | 3         | 0.84%   |
| Patriot                        | 3         | 0.84%   |
| Essencore Limited              | 2         | 0.56%   |
| Neo Forza                      | 1         | 0.28%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.28%   |
| KLEVV                          | 1         | 0.28%   |
| Innodisk                       | 1         | 0.28%   |
| Essencore                      | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 2.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 2.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 6         | 1.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 1.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 1.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.35%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.35%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.08%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.08%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.08%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.81%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 3         | 0.81%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.81%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.81%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 3         | 0.81%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 3         | 0.81%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.81%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.54%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s            | 2         | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.54%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 0.54%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.54%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s          | 2         | 0.54%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.54%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 129       | 49.43%  |
| DDR3    | 102       | 39.08%  |
| LPDDR4  | 14        | 5.36%   |
| DDR2    | 6         | 2.3%    |
| LPDDR3  | 4         | 1.53%   |
| DDR5    | 3         | 1.15%   |
| SDRAM   | 2         | 0.77%   |
| Unknown | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 249       | 92.22%  |
| Row Of Chips | 16        | 5.93%   |
| Chip         | 3         | 1.11%   |
| DIMM         | 1         | 0.37%   |
| Unknown      | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 105       | 34.31%  |
| 4096  | 95        | 31.05%  |
| 16384 | 47        | 15.36%  |
| 2048  | 45        | 14.71%  |
| 32768 | 7         | 2.29%   |
| 1024  | 6         | 1.96%   |
| 512   | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 77        | 25.67%  |
| 1600    | 65        | 21.67%  |
| 3200    | 41        | 13.67%  |
| 2400    | 23        | 7.67%   |
| 2133    | 21        | 7%      |
| 1334    | 21        | 7%      |
| 1333    | 15        | 5%      |
| 3266    | 8         | 2.67%   |
| 4267    | 5         | 1.67%   |
| 4800    | 3         | 1%      |
| 1067    | 3         | 1%      |
| 975     | 3         | 1%      |
| 667     | 3         | 1%      |
| 2933    | 2         | 0.67%   |
| 2048    | 2         | 0.67%   |
| 1066    | 2         | 0.67%   |
| 8400    | 1         | 0.33%   |
| 1867    | 1         | 0.33%   |
| 1776    | 1         | 0.33%   |
| 800     | 1         | 0.33%   |
| 533     | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 4         | 44.44%  |
| Hewlett-Packard       | 2         | 22.22%  |
| Samsung Electronics   | 1         | 11.11%  |
| Lexmark International | 1         | 11.11%  |
| Brother Industries    | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series                  | 2         | 22.22%  |
| Samsung M267x 287x Series                  | 1         | 11.11%  |
| Lexmark International InkJet Color Printer | 1         | 11.11%  |
| HP Officejet J4500 series                  | 1         | 11.11%  |
| HP LaserJet 1022                           | 1         | 11.11%  |
| Canon MF210 Series                         | 1         | 11.11%  |
| Canon G4000 series                         | 1         | 11.11%  |
| Brother MFC-L2700DW                        | 1         | 11.11%  |

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


| Vendor                                            | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 106       | 18.76%  |
| Microdia                                          | 64        | 11.33%  |
| Realtek Semiconductor                             | 53        | 9.38%   |
| IMC Networks                                      | 42        | 7.43%   |
| Sunplus Innovation Technology                     | 41        | 7.26%   |
| Quanta                                            | 30        | 5.31%   |
| Bison Electronics                                 | 28        | 4.96%   |
| Cheng Uei Precision Industry (Foxlink)            | 24        | 4.25%   |
| Apple                                             | 20        | 3.54%   |
| Acer                                              | 17        | 3.01%   |
| Syntek                                            | 16        | 2.83%   |
| Lite-On Technology                                | 16        | 2.83%   |
| Suyin                                             | 15        | 2.65%   |
| Samsung Electronics                               | 15        | 2.65%   |
| Luxvisions Innotech Limited                       | 9         | 1.59%   |
| Ricoh                                             | 8         | 1.42%   |
| Silicon Motion                                    | 7         | 1.24%   |
| Alcor Micro                                       | 7         | 1.24%   |
| Primax Electronics                                | 5         | 0.88%   |
| Microsoft                                         | 5         | 0.88%   |
| Logitech                                          | 5         | 0.88%   |
| Sonix Technology                                  | 4         | 0.71%   |
| Lenovo                                            | 4         | 0.71%   |
| icSpring                                          | 4         | 0.71%   |
| Z-Star Microelectronics                           | 3         | 0.53%   |
| Importek                                          | 3         | 0.53%   |
| GEMBIRD                                           | 3         | 0.53%   |
| LG Electronics                                    | 2         | 0.35%   |
| ALi                                               | 2         | 0.35%   |
| Y Media                                           | 1         | 0.18%   |
| Sunplus Technology                                | 1         | 0.18%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 0.18%   |
| Spreadtrum Communications                         | 1         | 0.18%   |
| OPPO Electronics                                  | 1         | 0.18%   |
| OmniVision Technologies                           | 1         | 0.18%   |
| DigiTech                                          | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 25        | 4.42%   |
| Realtek Integrated_Webcam_HD                  | 18        | 3.19%   |
| Sunplus Integrated_Webcam_HD                  | 17        | 3.01%   |
| Samsung Galaxy series, misc. (MTP mode)       | 15        | 2.65%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 14        | 2.48%   |
| Chicony Integrated Camera                     | 14        | 2.48%   |
| Microdia Integrated Webcam                    | 11        | 1.95%   |
| IMC Networks Integrated Camera                | 10        | 1.77%   |
| IMC Networks USB2.0 HD UVC WebCam             | 9         | 1.59%   |
| Chicony EasyCamera                            | 8         | 1.42%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR            | 8         | 1.42%   |
| Sunplus HD WebCam                             | 7         | 1.24%   |
| Quanta VGA Webcam                             | 7         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 7         | 1.24%   |
| Syntek EasyCamera                             | 6         | 1.06%   |
| Realtek Integrated Webcam HD                  | 6         | 1.06%   |
| Quanta HP HD Camera                           | 6         | 1.06%   |
| Chicony HP TrueVision HD Camera               | 6         | 1.06%   |
| Bison Integrated Camera                       | 6         | 1.06%   |
| Acer Integrated Camera                        | 6         | 1.06%   |
| Realtek Integrated Webcam                     | 5         | 0.88%   |
| Realtek HP Truevision HD                      | 5         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_HD          | 5         | 0.88%   |
| Lite-On HP HD Camera                          | 5         | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                 | 5         | 0.88%   |
| Chicony HD WebCam                             | 5         | 0.88%   |
| Apple FaceTime HD Camera                      | 5         | 0.88%   |
| Acer EasyCamera                               | 5         | 0.88%   |
| Syntek Lenovo EasyCamera                      | 4         | 0.71%   |
| Syntek Integrated Camera                      | 4         | 0.71%   |
| Suyin HP TrueVision HD Integrated Webcam      | 4         | 0.71%   |
| Sonix USB2.0 HD UVC WebCam                    | 4         | 0.71%   |
| Quanta HP Webcam                              | 4         | 0.71%   |
| Quanta HD User Facing                         | 4         | 0.71%   |
| icSpring camera                               | 4         | 0.71%   |
| Chicony VGA WebCam                            | 4         | 0.71%   |
| Chicony Integrated IR Camera                  | 4         | 0.71%   |
| Chicony Integrated HP HD Webcam               | 4         | 0.71%   |
| Chicony HP Webcam                             | 4         | 0.71%   |
| Chicony HP HD Camera                          | 4         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 63        | 51.22%  |
| Synaptics                  | 19        | 15.45%  |
| Upek                       | 12        | 9.76%   |
| Shenzhen Goodix Technology | 12        | 9.76%   |
| AuthenTec                  | 9         | 7.32%   |
| LighTuning Technology      | 5         | 4.07%   |
| Focal-systems.Corp         | 2         | 1.63%   |
| STMicroelectronics         | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 16        | 13.01%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 11        | 8.94%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 9         | 7.32%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 8         | 6.5%    |
| Validity Sensors VFS471 Fingerprint Reader                | 7         | 5.69%   |
| Validity Sensors VFS451 Fingerprint Reader                | 5         | 4.07%   |
| Shenzhen Goodix Fingerprint Reader                        | 5         | 4.07%   |
| Validity Sensors Synaptics WBDI                           | 4         | 3.25%   |
| Validity Sensors Fingerprint scanner                      | 4         | 3.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 4         | 3.25%   |
| Synaptics Fingerprint reader [HP G6]                      | 4         | 3.25%   |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 3.25%   |
| Validity Sensors VFS491                                   | 3         | 2.44%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 3         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 3         | 2.44%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 3         | 2.44%   |
| Shenzhen Goodix FingerPrint                               | 3         | 2.44%   |
| AuthenTec AES2810                                         | 3         | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 3         | 2.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 1.63%   |
| Focal-systems.Corp FT9201Fingerprint.                     | 2         | 1.63%   |
| AuthenTec Fingerprint Sensor                              | 2         | 1.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 0.81%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 0.81%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 0.81%   |
| Validity Sensors VFS300 Fingerprint Reader                | 1         | 0.81%   |
| Upek TCS5B Fingerprint sensor                             | 1         | 0.81%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 1         | 0.81%   |
| Synaptics WBDI                                            | 1         | 0.81%   |
| Synaptics  WBDI                                           | 1         | 0.81%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 0.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 0.81%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 0.81%   |
| LighTuning Fingerprint Sensor                             | 1         | 0.81%   |
| LighTuning Fingerprint Reader                             | 1         | 0.81%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 0.81%   |
| AuthenTec AES1600                                         | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 46        | 73.02%  |
| O2 Micro    | 5         | 7.94%   |
| Lenovo      | 5         | 7.94%   |
| Alcor Micro | 5         | 7.94%   |
| Upek        | 2         | 3.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 25.4%   |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 20.63%  |
| Broadcom 5880                                                                | 10        | 15.87%  |
| Broadcom 58200                                                               | 7         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 7.94%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 7.94%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 7.94%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 373       | 59.58%  |
| 1     | 200       | 31.95%  |
| 2     | 46        | 7.35%   |
| 3     | 6         | 0.96%   |
| 9     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 122       | 39.23%  |
| Chipcard                 | 58        | 18.65%  |
| Graphics card            | 48        | 15.43%  |
| Net/wireless             | 27        | 8.68%   |
| Multimedia controller    | 13        | 4.18%   |
| Bluetooth                | 13        | 4.18%   |
| Storage                  | 7         | 2.25%   |
| Camera                   | 7         | 2.25%   |
| Communication controller | 5         | 1.61%   |
| Sound                    | 3         | 0.96%   |
| Modem                    | 3         | 0.96%   |
| Card reader              | 2         | 0.64%   |
| Unassigned class         | 1         | 0.32%   |
| Network                  | 1         | 0.32%   |
| Flash memory             | 1         | 0.32%   |

