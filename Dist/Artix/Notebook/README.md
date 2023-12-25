Artix - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Artix.

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

Total: 212

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6440              | [cf0bb02399](https://linux-hardware.org/?probe=cf0bb02399) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [82fd570b21](https://linux-hardware.org/?probe=82fd570b21) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b706d26f30](https://linux-hardware.org/?probe=b706d26f30) | Dec 07, 2023 |
| HP            | Victus by Gaming Laptop ... | [f150b37e9f](https://linux-hardware.org/?probe=f150b37e9f) | Dec 03, 2023 |
| Acer          | Nitro AN515-54              | [59580145e5](https://linux-hardware.org/?probe=59580145e5) | Nov 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e55e321a2e](https://linux-hardware.org/?probe=e55e321a2e) | Nov 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | [7814bb818a](https://linux-hardware.org/?probe=7814bb818a) | Oct 23, 2023 |
| Apple         | MacBookPro10,2              | [f83f9bba48](https://linux-hardware.org/?probe=f83f9bba48) | Oct 15, 2023 |
| HP            | Grunt                       | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| Dell          | Precision 7560              | [7cffa06ab3](https://linux-hardware.org/?probe=7cffa06ab3) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [58552d0532](https://linux-hardware.org/?probe=58552d0532) | Sep 30, 2023 |
| Dell          | Latitude 5431               | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | [e28cf08ffe](https://linux-hardware.org/?probe=e28cf08ffe) | Sep 24, 2023 |
| Lenovo        | ThinkPad T480 20L50018US    | [46ee09f5bd](https://linux-hardware.org/?probe=46ee09f5bd) | Sep 21, 2023 |
| Timi          | A30                         | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| HP            | ProBook 455 G7              | [7ae653c6c1](https://linux-hardware.org/?probe=7ae653c6c1) | Sep 05, 2023 |
| HP            | 15                          | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| Dell          | Inspiron 15 3511            | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Dell          | Inspiron 15 3511            | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| Acer          | Aspire S5-371               | [210e2bbe4d](https://linux-hardware.org/?probe=210e2bbe4d) | Aug 16, 2023 |
| Acer          | Aspire S5-371               | [c5b4372bbf](https://linux-hardware.org/?probe=c5b4372bbf) | Aug 16, 2023 |
| HP            | 255 G8 Notebook PC          | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| Lenovo        | ThinkPad Edge E431 6277C... | [6c542a6490](https://linux-hardware.org/?probe=6c542a6490) | Aug 03, 2023 |
| Dell          | Inspiron 15-3552            | [3b317edaf6](https://linux-hardware.org/?probe=3b317edaf6) | Jul 25, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [25f87e7de3](https://linux-hardware.org/?probe=25f87e7de3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T420 4180AG3       | [21fe808c05](https://linux-hardware.org/?probe=21fe808c05) | Jul 02, 2023 |
| ASUSTek       | K53E                        | [8e1f4ee31f](https://linux-hardware.org/?probe=8e1f4ee31f) | Jun 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [8649d41483](https://linux-hardware.org/?probe=8649d41483) | Jun 15, 2023 |
| Notebook      | N141CU                      | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| GPD           | P2 MAX                      | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| ASUSTek       | GL702ZC                     | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [429d4451c9](https://linux-hardware.org/?probe=429d4451c9) | May 16, 2023 |
| HP            | EliteBook 2560p             | [2a50b288f8](https://linux-hardware.org/?probe=2a50b288f8) | May 15, 2023 |
| Lenovo        | S20-30 20421                | [cc4f992884](https://linux-hardware.org/?probe=cc4f992884) | May 12, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [ea808c2e80](https://linux-hardware.org/?probe=ea808c2e80) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [382b81c0d1](https://linux-hardware.org/?probe=382b81c0d1) | May 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Dell          | G3 3500                     | [aa79addc8c](https://linux-hardware.org/?probe=aa79addc8c) | Mar 29, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [6c74aa3736](https://linux-hardware.org/?probe=6c74aa3736) | Mar 02, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [245d23aff3](https://linux-hardware.org/?probe=245d23aff3) | Feb 26, 2023 |
| HP            | 245 G8 Notebook PC          | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HUAWEI        | KPR-WX9                     | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| ONE-NETBOO... | One-Mix3 Pro                | [9869b4dd9c](https://linux-hardware.org/?probe=9869b4dd9c) | Feb 15, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | [84411df81a](https://linux-hardware.org/?probe=84411df81a) | Feb 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| Lenovo        | B50-80 80EW                 | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| Toshiba       | Satellite P775              | [4ac7834c5f](https://linux-hardware.org/?probe=4ac7834c5f) | Jan 16, 2023 |
| Toshiba       | Satellite P775              | [99e632c9a9](https://linux-hardware.org/?probe=99e632c9a9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T430 23427YU       | [3ca2dd056d](https://linux-hardware.org/?probe=3ca2dd056d) | Jan 16, 2023 |
| HONOR         | BMH-WCX9                    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | GL702ZC                     | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Acer          | Aspire A315-56              | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| ASUSTek       | N53SV                       | [f42473e3f6](https://linux-hardware.org/?probe=f42473e3f6) | Nov 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| Samsung       | R425D/R525D                 | [85d17374e7](https://linux-hardware.org/?probe=85d17374e7) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| HP            | Pavilion 15                 | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| MSI           | GF65 Thin 10SDR             | [debce2faa6](https://linux-hardware.org/?probe=debce2faa6) | Oct 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| HP            | Pavilion g4                 | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Acer          | Predator PH315-51           | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a37633e1e2](https://linux-hardware.org/?probe=a37633e1e2) | Aug 24, 2022 |
| Dell          | Inspiron 5520               | [6b03bfc62e](https://linux-hardware.org/?probe=6b03bfc62e) | Aug 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| Dell          | Inspiron 3541               | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Latitude E7440              | [deea307e9b](https://linux-hardware.org/?probe=deea307e9b) | Jul 27, 2022 |
| Dell          | Latitude E7440              | [e2d8510882](https://linux-hardware.org/?probe=e2d8510882) | Jul 27, 2022 |
| Acer          | Aspire A315-23              | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
| MOTILE        | M141                        | [59c616a04e](https://linux-hardware.org/?probe=59c616a04e) | Jun 30, 2022 |
| HUAWEI        | WRT-WX9                     | [8ddbebd4b1](https://linux-hardware.org/?probe=8ddbebd4b1) | Jun 28, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Timi          | RedmiBook 14 II             | [a4b535cdee](https://linux-hardware.org/?probe=a4b535cdee) | Jun 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0MV0... | [3c23c9dfc6](https://linux-hardware.org/?probe=3c23c9dfc6) | Jun 08, 2022 |
| ASUSTek       | X553MA                      | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Dell          | Precision M6600             | [bb044c066c](https://linux-hardware.org/?probe=bb044c066c) | Jun 05, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | [dfacdafc7f](https://linux-hardware.org/?probe=dfacdafc7f) | May 11, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | [9792863fc7](https://linux-hardware.org/?probe=9792863fc7) | May 08, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | [bba77106b4](https://linux-hardware.org/?probe=bba77106b4) | May 08, 2022 |
| HP            | 15                          | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek       | GX501VIK                    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 246                         | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| HP            | Laptop 14s-dq2xxx           | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook      | N141CU                      | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer          | Aspire V3-472PG             | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP            | Laptop 15-ef1xxx            | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| ASUSTek       | 1225C                       | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| HP            | Laptop 15-ef1xxx            | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| MSI           | Modern 15 A11M              | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell          | Latitude E6440              | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek       | K50IE                       | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi          | RedmiBook 14 II             | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP            | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi          | RedmiBook 14 II             | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi          | RedmiBook 14 II             | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Acer          | Swift SF314-59              | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer          | Swift SF314-59              | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer          | Aspire E5-575               | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell          | Precision M6600             | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| ASUSTek       | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| GPD           | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP            | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Dell          | Inspiron 3442               | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo        | LaVie Z 20FF0012US          | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP            | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| Apple         | MacBookAir7,2               | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP            | 250 G7 Notebook PC          | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP            | 250 G7 Notebook PC          | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell          | Precision 7550              | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell          | Precision 7550              | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| UNOWHY        | Y13G010S4EI                 | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| HP            | Laptop 17z-ca300            | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| Acer          | Aspire V3-572PG             | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Apple         | MacBookAir7,2               | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI           | GP72 7RDX                   | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta        | SWH                         | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Precision 7550              | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Acer          | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| ASUSTek       | K53SC                       | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek       | K53SC                       | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| HP            | ProBook 450 G6              | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell          | Precision 5520              | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASUSTek       | E402NA                      | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Acer          | Aspire A315-53              | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Dell          | Precision 7550              | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| Dell          | Latitude E6530              | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP            | 250 G4 Notebook PC          | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD           | P2 MAX                      | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Sony          | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer          | Aspire A315-53              | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell          | Inspiron 5570               | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| HP            | 255 G7 Notebook PC          | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Dell          | Precision 7550              | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| Dell          | Precision 7550              | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| Dell          | Precision 7550              | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| Acer          | Nitro AN515-51              | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Gigabyte      | AERO 15-X9                  | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| Gigabyte      | AERO 15-X9                  | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| Acer          | Aspire E5-575G              | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| Dell          | Precision 3540              | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Lenovo        | B590 20206                  | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 89        | 57.05%  |
| Artix          | 60        | 38.46%  |
| Artix 20230710 | 2         | 1.28%   |
| Artix 20230814 | 1         | 0.64%   |
| Artix 20220713 | 1         | 0.64%   |
| Artix 20220123 | 1         | 0.64%   |
| Artix 20201207 | 1         | 0.64%   |
| Artix 20201128 | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 150       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 6         | 3.45%   |
| 6.3.2-artix1-1     | 4         | 2.3%    |
| 6.5.7-artix1-1     | 3         | 1.72%   |
| 6.5.5-artix1-1     | 3         | 1.72%   |
| 6.4.10-artix1-1    | 3         | 1.72%   |
| 6.0.7-artix1-1     | 3         | 1.72%   |
| 5.7.6-artix1-1     | 3         | 1.72%   |
| 6.5.2-artix1-1     | 2         | 1.15%   |
| 6.3.3-artix1-1     | 2         | 1.15%   |
| 6.3.1-artix1-1     | 2         | 1.15%   |
| 6.1.8-artix1-1     | 2         | 1.15%   |
| 6.1.6-artix1-1     | 2         | 1.15%   |
| 6.1.10-zen1-1-zen  | 2         | 1.15%   |
| 6.0.12-artix1-1    | 2         | 1.15%   |
| 5.7.12-artix1-1    | 2         | 1.15%   |
| 5.19.12-artix1-1   | 2         | 1.15%   |
| 5.18.6-artix1-1    | 2         | 1.15%   |
| 5.18.10-artix1-1   | 2         | 1.15%   |
| 5.18.0-artix1-1    | 2         | 1.15%   |
| 5.17.1-artix1-1    | 2         | 1.15%   |
| 5.16.8-artix1-2    | 2         | 1.15%   |
| 5.16.10-artix1-1   | 2         | 1.15%   |
| 5.15.12-artix1-1   | 2         | 1.15%   |
| 5.14.16-artix1-1   | 2         | 1.15%   |
| 5.13.8-artix1-1    | 2         | 1.15%   |
| 5.12.8-artix1-1    | 2         | 1.15%   |
| 5.12.12-zen1-1-zen | 2         | 1.15%   |
| 5.12.12-artix1-1   | 2         | 1.15%   |
| 5.11.6-artix1-1    | 2         | 1.15%   |
| 5.10.6-artix1-1    | 2         | 1.15%   |
| 5.10.4-artix2-1    | 2         | 1.15%   |
| 5.10.16-artix1-1   | 2         | 1.15%   |
| 6.6.4-artix1-1     | 1         | 0.57%   |
| 6.6.3-artix1-1     | 1         | 0.57%   |
| 6.5.5-zen1-1-zen   | 1         | 0.57%   |
| 6.4.8-lqx1-1-lqx   | 1         | 0.57%   |
| 6.4.4-zen1-1-zen   | 1         | 0.57%   |
| 6.4.2-artix1-1     | 1         | 0.57%   |
| 6.4.12-zen1-1-zen  | 1         | 0.57%   |
| 6.4.1              | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 4.02%   |
| 6.5.5   | 4         | 2.3%    |
| 6.3.2   | 4         | 2.3%    |
| 6.1.10  | 4         | 2.3%    |
| 6.0.7   | 4         | 2.3%    |
| 5.12.12 | 4         | 2.3%    |
| 6.5.7   | 3         | 1.72%   |
| 6.4.10  | 3         | 1.72%   |
| 6.3.1   | 3         | 1.72%   |
| 5.7.6   | 3         | 1.72%   |
| 5.17.1  | 3         | 1.72%   |
| 5.15.12 | 3         | 1.72%   |
| 5.12.8  | 3         | 1.72%   |
| 6.5.2   | 2         | 1.15%   |
| 6.3.3   | 2         | 1.15%   |
| 6.1.8   | 2         | 1.15%   |
| 6.1.6   | 2         | 1.15%   |
| 6.0.12  | 2         | 1.15%   |
| 5.9.0   | 2         | 1.15%   |
| 5.8.14  | 2         | 1.15%   |
| 5.7.12  | 2         | 1.15%   |
| 5.19.12 | 2         | 1.15%   |
| 5.18.6  | 2         | 1.15%   |
| 5.18.10 | 2         | 1.15%   |
| 5.18.0  | 2         | 1.15%   |
| 5.16.8  | 2         | 1.15%   |
| 5.16.10 | 2         | 1.15%   |
| 5.14.16 | 2         | 1.15%   |
| 5.13.8  | 2         | 1.15%   |
| 5.12.14 | 2         | 1.15%   |
| 5.11.6  | 2         | 1.15%   |
| 5.10.6  | 2         | 1.15%   |
| 5.10.4  | 2         | 1.15%   |
| 5.10.16 | 2         | 1.15%   |
| 6.6.4   | 1         | 0.57%   |
| 6.6.3   | 1         | 0.57%   |
| 6.4.8   | 1         | 0.57%   |
| 6.4.4   | 1         | 0.57%   |
| 6.4.2   | 1         | 0.57%   |
| 6.4.12  | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 15        | 8.93%   |
| 5.15    | 13        | 7.74%   |
| 5.18    | 12        | 7.14%   |
| 5.12    | 12        | 7.14%   |
| 6.3     | 11        | 6.55%   |
| 5.9     | 11        | 6.55%   |
| 5.10    | 11        | 6.55%   |
| 6.5     | 9         | 5.36%   |
| 6.4     | 8         | 4.76%   |
| 6.0     | 8         | 4.76%   |
| 5.17    | 8         | 4.76%   |
| 5.16    | 8         | 4.76%   |
| 5.11    | 8         | 4.76%   |
| 5.7     | 6         | 3.57%   |
| 5.19    | 6         | 3.57%   |
| 5.8     | 5         | 2.98%   |
| 5.14    | 4         | 2.38%   |
| 5.13    | 4         | 2.38%   |
| 6.6     | 2         | 1.19%   |
| 6.2     | 2         | 1.19%   |
| 6.0.5   | 1         | 0.6%    |
| 5.6     | 1         | 0.6%    |
| 5.5     | 1         | 0.6%    |
| 5.4     | 1         | 0.6%    |
| 4.19    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 150       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 42        | 26.58%  |
| XFCE           | 27        | 17.09%  |
| Unknown        | 26        | 16.46%  |
| GNOME          | 15        | 9.49%   |
| X-Cinnamon     | 8         | 5.06%   |
| MATE           | 7         | 4.43%   |
| LXQt           | 5         | 3.16%   |
| i3             | 5         | 3.16%   |
| LXDE           | 4         | 2.53%   |
| KDE            | 4         | 2.53%   |
| Sway           | 3         | 1.9%    |
| Cinnamon       | 3         | 1.9%    |
| bspwm          | 2         | 1.27%   |
| xmonad         | 1         | 0.63%   |
| xinitrc        | 1         | 0.63%   |
| sway-dbus      | 1         | 0.63%   |
| nxde           | 1         | 0.63%   |
| Hyprland       | 1         | 0.63%   |
| awesomeminimal | 1         | 0.63%   |
| awesome        | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 106       | 68.83%  |
| Wayland | 18        | 11.69%  |
| Tty     | 18        | 11.69%  |
| Unknown | 12        | 7.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 39.61%  |
| LightDM | 47        | 30.52%  |
| SDDM    | 39        | 25.32%  |
| XDM     | 2         | 1.3%    |
| Ly      | 2         | 1.3%    |
| SLiM    | 1         | 0.65%   |
| LXDM    | 1         | 0.65%   |
| GDM     | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 75        | 48.39%  |
| Unknown | 20        | 12.9%   |
| C       | 9         | 5.81%   |
| ru_RU   | 8         | 5.16%   |
| en_GB   | 8         | 5.16%   |
| fr_FR   | 4         | 2.58%   |
| pl_PL   | 3         | 1.94%   |
| es_ES   | 3         | 1.94%   |
| pt_BR   | 2         | 1.29%   |
| it_IT   | 2         | 1.29%   |
| en_CA   | 2         | 1.29%   |
| en_AU   | 2         | 1.29%   |
| en_AG   | 2         | 1.29%   |
| de_DE   | 2         | 1.29%   |
| vi_VN   | 1         | 0.65%   |
| uk_UA   | 1         | 0.65%   |
| tr_TR   | 1         | 0.65%   |
| ro_RO   | 1         | 0.65%   |
| pt_PT   | 1         | 0.65%   |
| fi_FI   | 1         | 0.65%   |
| es_MX   | 1         | 0.65%   |
| es_GT   | 1         | 0.65%   |
| es_CO   | 1         | 0.65%   |
| en_NZ   | 1         | 0.65%   |
| en_IN   | 1         | 0.65%   |
| el_GR   | 1         | 0.65%   |
| cs_CZ   | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 101       | 66.89%  |
| BIOS | 50        | 33.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 113       | 74.34%  |
| Btrfs   | 31        | 20.39%  |
| Xfs     | 3         | 1.97%   |
| F2fs    | 3         | 1.97%   |
| Overlay | 2         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 103       | 68.21%  |
| Unknown | 27        | 17.88%  |
| MBR     | 21        | 13.91%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 126       | 83.44%  |
| Yes       | 25        | 16.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 76%     |
| Yes       | 36        | 24%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 39        | 26%     |
| Hewlett-Packard        | 25        | 16.67%  |
| Dell                   | 21        | 14%     |
| ASUSTek Computer       | 17        | 11.33%  |
| Acer                   | 16        | 10.67%  |
| Apple                  | 4         | 2.67%   |
| Timi                   | 3         | 2%      |
| Samsung Electronics    | 3         | 2%      |
| MSI                    | 3         | 2%      |
| HUAWEI                 | 3         | 2%      |
| Gigabyte Technology    | 3         | 2%      |
| Notebook               | 2         | 1.33%   |
| GPD                    | 2         | 1.33%   |
| UNOWHY                 | 1         | 0.67%   |
| Toshiba                | 1         | 0.67%   |
| Quanta                 | 1         | 0.67%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.67%   |
| MOTILE                 | 1         | 0.67%   |
| LG Electronics         | 1         | 0.67%   |
| HONOR                  | 1         | 0.67%   |
| Fujitsu                | 1         | 0.67%   |
| AXIOO                  | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP 15                                                 | 3         | 2%      |
| Timi RedmiBook 14 II                                  | 2         | 1.33%   |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 1.33%   |
| HP Laptop 15s-eq2xxx                                  | 2         | 1.33%   |
| GPD P2 MAX                                            | 2         | 1.33%   |
| Dell Precision M6600                                  | 2         | 1.33%   |
| Dell Precision 7550                                   | 2         | 1.33%   |
| Dell Latitude E6440                                   | 2         | 1.33%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA               | 2         | 1.33%   |
| Apple MacBookAir7,2                                   | 2         | 1.33%   |
| Acer Nitro AN515-52                                   | 2         | 1.33%   |
| UNOWHY Y13G010S4EI                                    | 1         | 0.67%   |
| Toshiba Satellite P775                                | 1         | 0.67%   |
| Timi A30                                              | 1         | 0.67%   |
| Samsung R425D/R525D                                   | 1         | 0.67%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.67%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.67%   |
| Quanta SWH                                            | 1         | 0.67%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.67%   |
| Notebook N141CU                                       | 1         | 0.67%   |
| Notebook N130BU                                       | 1         | 0.67%   |
| MSI Modern 15 A11M                                    | 1         | 0.67%   |
| MSI GP72 7RDX                                         | 1         | 0.67%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.67%   |
| MOTILE M141                                           | 1         | 0.67%   |
| LG 17Z990-R.AAC9U1                                    | 1         | 0.67%   |
| Lenovo ThinkPad W520 4284W2U                          | 1         | 0.67%   |
| Lenovo ThinkPad W500 4063CJ5                          | 1         | 0.67%   |
| Lenovo ThinkPad T480s 20L8S3D400                      | 1         | 0.67%   |
| Lenovo ThinkPad T480 MFG_IN_GO                        | 1         | 0.67%   |
| Lenovo ThinkPad T480 20L50018US                       | 1         | 0.67%   |
| Lenovo ThinkPad T440s 20ARS0MV00                      | 1         | 0.67%   |
| Lenovo ThinkPad T430 2350BC6                          | 1         | 0.67%   |
| Lenovo ThinkPad T430 2347H76                          | 1         | 0.67%   |
| Lenovo ThinkPad T430 2344BZU                          | 1         | 0.67%   |
| Lenovo ThinkPad T430 23427YU                          | 1         | 0.67%   |
| Lenovo ThinkPad T420 4236H45                          | 1         | 0.67%   |
| Lenovo ThinkPad T420 4180AG3                          | 1         | 0.67%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00                  | 1         | 0.67%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800                  | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 20        | 13.33%  |
| Lenovo IdeaPad                  | 11        | 7.33%   |
| Acer Aspire                     | 11        | 7.33%   |
| HP Laptop                       | 7         | 4.67%   |
| Dell Precision                  | 7         | 4.67%   |
| Dell Inspiron                   | 7         | 4.67%   |
| Dell Latitude                   | 6         | 4%      |
| ASUS VivoBook                   | 5         | 3.33%   |
| HP 250                          | 3         | 2%      |
| HP 15                           | 3         | 2%      |
| ASUS ASUS                       | 3         | 2%      |
| Acer Nitro                      | 3         | 2%      |
| Timi RedmiBook                  | 2         | 1.33%   |
| HP ProBook                      | 2         | 1.33%   |
| HP Pavilion                     | 2         | 1.33%   |
| HP 255                          | 2         | 1.33%   |
| GPD P2                          | 2         | 1.33%   |
| Apple MacBookAir7               | 2         | 1.33%   |
| UNOWHY Y13G010S4EI              | 1         | 0.67%   |
| Toshiba Satellite               | 1         | 0.67%   |
| Timi A30                        | 1         | 0.67%   |
| Samsung R425D                   | 1         | 0.67%   |
| Samsung 350V5C                  | 1         | 0.67%   |
| Samsung 300E5EV                 | 1         | 0.67%   |
| Quanta SWH                      | 1         | 0.67%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.67%   |
| Notebook N141CU                 | 1         | 0.67%   |
| Notebook N130BU                 | 1         | 0.67%   |
| MSI Modern                      | 1         | 0.67%   |
| MSI GP72                        | 1         | 0.67%   |
| MSI GF65                        | 1         | 0.67%   |
| MOTILE M141                     | 1         | 0.67%   |
| LG 17Z990-R.AAC9U1              | 1         | 0.67%   |
| Lenovo ThinkBook                | 1         | 0.67%   |
| Lenovo S20-30                   | 1         | 0.67%   |
| Lenovo Legion                   | 1         | 0.67%   |
| Lenovo LaVie                    | 1         | 0.67%   |
| Lenovo G400s                    | 1         | 0.67%   |
| Lenovo B590                     | 1         | 0.67%   |
| Lenovo B570e                    | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 31        | 20.67%  |
| 2018 | 16        | 10.67%  |
| 2019 | 15        | 10%     |
| 2021 | 13        | 8.67%   |
| 2011 | 13        | 8.67%   |
| 2013 | 12        | 8%      |
| 2014 | 9         | 6%      |
| 2012 | 9         | 6%      |
| 2017 | 8         | 5.33%   |
| 2015 | 7         | 4.67%   |
| 2022 | 5         | 3.33%   |
| 2016 | 5         | 3.33%   |
| 2010 | 3         | 2%      |
| 2007 | 3         | 2%      |
| 2009 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 150       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 148       | 98.67%  |
| Enabled  | 2         | 1.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 148       | 98.67%  |
| Yes  | 2         | 1.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 32.45%  |
| 8.01-16.0   | 32        | 21.19%  |
| 16.01-24.0  | 27        | 17.88%  |
| 3.01-4.0    | 22        | 14.57%  |
| 32.01-64.0  | 9         | 5.96%   |
| 1.01-2.0    | 5         | 3.31%   |
| 64.01-256.0 | 4         | 2.65%   |
| 24.01-32.0  | 3         | 1.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 43        | 25.75%  |
| 1.01-2.0   | 39        | 23.35%  |
| 4.01-8.0   | 38        | 22.75%  |
| 3.01-4.0   | 22        | 13.17%  |
| 0.51-1.0   | 15        | 8.98%   |
| 8.01-16.0  | 7         | 4.19%   |
| 0.01-0.5   | 2         | 1.2%    |
| 16.01-24.0 | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 120       | 79.47%  |
| 2      | 27        | 17.88%  |
| 3      | 4         | 2.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 110       | 73.33%  |
| Yes       | 40        | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 75.33%  |
| No        | 37        | 24.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 98%     |
| No        | 3         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 80.26%  |
| No        | 30        | 19.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country         | Notebooks | Percent |
|-----------------|-----------|---------|
| USA             | 30        | 19.87%  |
| Russia          | 15        | 9.93%   |
| Brazil          | 8         | 5.3%    |
| India           | 7         | 4.64%   |
| Germany         | 6         | 3.97%   |
| UK              | 5         | 3.31%   |
| Turkey          | 5         | 3.31%   |
| Poland          | 5         | 3.31%   |
| Italy           | 5         | 3.31%   |
| France          | 5         | 3.31%   |
| Spain           | 4         | 2.65%   |
| Romania         | 4         | 2.65%   |
| Indonesia       | 4         | 2.65%   |
| Canada          | 4         | 2.65%   |
| Ukraine         | 3         | 1.99%   |
| Switzerland     | 3         | 1.99%   |
| Netherlands     | 3         | 1.99%   |
| Bulgaria        | 3         | 1.99%   |
| Portugal        | 2         | 1.32%   |
| Pakistan        | 2         | 1.32%   |
| Czechia         | 2         | 1.32%   |
| Bangladesh      | 2         | 1.32%   |
| Australia       | 2         | 1.32%   |
| Argentina       | 2         | 1.32%   |
| Vietnam         | 1         | 0.66%   |
| Uzbekistan      | 1         | 0.66%   |
| Sweden          | 1         | 0.66%   |
| Slovakia        | 1         | 0.66%   |
| Peru            | 1         | 0.66%   |
| North Macedonia | 1         | 0.66%   |
| Lithuania       | 1         | 0.66%   |
| Japan           | 1         | 0.66%   |
| Israel          | 1         | 0.66%   |
| Iran            | 1         | 0.66%   |
| Guatemala       | 1         | 0.66%   |
| Greece          | 1         | 0.66%   |
| Finland         | 1         | 0.66%   |
| Croatia         | 1         | 0.66%   |
| Colombia        | 1         | 0.66%   |
| China           | 1         | 0.66%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| St Petersburg     | 3         | 1.9%    |
| Paris             | 3         | 1.9%    |
| Los Angeles       | 3         | 1.9%    |
| Jakarta           | 3         | 1.9%    |
| Warsaw            | 2         | 1.27%   |
| Sorocaba          | 2         | 1.27%   |
| Sofia             | 2         | 1.27%   |
| San Ramon         | 2         | 1.27%   |
| Samara            | 2         | 1.27%   |
| Rio de Janeiro    | 2         | 1.27%   |
| Prague            | 2         | 1.27%   |
| Omaha             | 2         | 1.27%   |
| Neuchatel         | 2         | 1.27%   |
| Moscow            | 2         | 1.27%   |
| Mira              | 2         | 1.27%   |
| Milton            | 2         | 1.27%   |
| Iasi              | 2         | 1.27%   |
| Frankfurt am Main | 2         | 1.27%   |
| Dnipro            | 2         | 1.27%   |
| Brisbane          | 2         | 1.27%   |
| Ankara            | 2         | 1.27%   |
| Amsterdam         | 2         | 1.27%   |
| Zurich            | 1         | 0.63%   |
| Zaporizhzhya      | 1         | 0.63%   |
| Zagreb            | 1         | 0.63%   |
| Woodbridge        | 1         | 0.63%   |
| Wigan             | 1         | 0.63%   |
| Wem               | 1         | 0.63%   |
| Vilnius           | 1         | 0.63%   |
| Vichy             | 1         | 0.63%   |
| Varna             | 1         | 0.63%   |
| Vancouver         | 1         | 0.63%   |
| Toronto           | 1         | 0.63%   |
| Tokyo             | 1         | 0.63%   |
| Timișoara        | 1         | 0.63%   |
| Tel Aviv          | 1         | 0.63%   |
| Tejgaon           | 1         | 0.63%   |
| Taunsa            | 1         | 0.63%   |
| Tashkent          | 1         | 0.63%   |
| Tampere           | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 34        | 43     | 18.38%  |
| Seagate                      | 18        | 18     | 9.73%   |
| WDC                          | 15        | 18     | 8.11%   |
| Toshiba                      | 13        | 13     | 7.03%   |
| Sandisk                      | 11        | 11     | 5.95%   |
| Kingston                     | 8         | 9      | 4.32%   |
| Intel                        | 8         | 10     | 4.32%   |
| HGST                         | 8         | 8      | 4.32%   |
| Crucial                      | 8         | 10     | 4.32%   |
| SK hynix                     | 6         | 12     | 3.24%   |
| Unknown                      | 5         | 5      | 2.7%    |
| Phison Electronics           | 5         | 8      | 2.7%    |
| Hitachi                      | 5         | 6      | 2.7%    |
| Micron Technology            | 4         | 4      | 2.16%   |
| China                        | 4         | 4      | 2.16%   |
| Apple                        | 3         | 4      | 1.62%   |
| WALRAM                       | 2         | 2      | 1.08%   |
| Solid State Storage          | 2         | 2      | 1.08%   |
| Micron/Crucial Technology    | 2         | 2      | 1.08%   |
| LITEON                       | 2         | 2      | 1.08%   |
| A-DATA Technology            | 2         | 2      | 1.08%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.54%   |
| Timetec                      | 1         | 2      | 0.54%   |
| SPCC                         | 1         | 1      | 0.54%   |
| Silicon Motion               | 1         | 1      | 0.54%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.54%   |
| PNY                          | 1         | 1      | 0.54%   |
| Phison                       | 1         | 1      | 0.54%   |
| Patriot                      | 1         | 1      | 0.54%   |
| Lite-On                      | 1         | 1      | 0.54%   |
| Linux                        | 1         | 1      | 0.54%   |
| Lenovo                       | 1         | 1      | 0.54%   |
| LDLC                         | 1         | 5      | 0.54%   |
| KIOXIA                       | 1         | 1      | 0.54%   |
| JMicron Technology           | 1         | 1      | 0.54%   |
| Intenso                      | 1         | 1      | 0.54%   |
| Hewlett-Packard              | 1         | 1      | 0.54%   |
| Dogfish                      | 1         | 1      | 0.54%   |
| AGI                          | 1         | 1      | 0.54%   |
| ADATA Technology             | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 2.59%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 2.07%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 1.55%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.55%   |
| Phison E12 NVMe Controller 512GB                    | 3         | 1.55%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 1.55%   |
| China SATA SSD 960GB                                | 3         | 1.55%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.04%   |
| WALRAM 240G                                         | 2         | 1.04%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.04%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.04%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 2         | 1.04%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 1.04%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 1.04%   |
| Phison PCIe SSD 4TB                                 | 2         | 1.04%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 2         | 1.04%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.04%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.04%   |
| HGST HTS545050A7E680 500GB                          | 2         | 1.04%   |
| HGST HTS541010A9E680 1TB                            | 2         | 1.04%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.04%   |
| Apple SSD SM0256G 256GB                             | 2         | 1.04%   |
| WDC WDS500G2B0A 500GB SSD                           | 1         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.52%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                      | 1         | 0.52%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.52%   |
| WDC WD5000LPVX-55V0TT0 500GB                        | 1         | 0.52%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 0.52%   |
| WDC WD50 00LPVX-75V0TT0 500GB                       | 1         | 0.52%   |
| WDC WD3200LPVT-00FMCT0 320GB                        | 1         | 0.52%   |
| WDC WD3200BEKT-60F3T1 320GB                         | 1         | 0.52%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.52%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.52%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.52%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 0.52%   |
| Unknown MMC Card  64GB                              | 1         | 0.52%   |
| Unknown MMC Card  32GB                              | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 18     | 32.73%  |
| WDC     | 12        | 14     | 21.82%  |
| Toshiba | 11        | 11     | 20%     |
| HGST    | 8         | 8      | 14.55%  |
| Hitachi | 5         | 6      | 9.09%   |
| Unknown | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 22.45%  |
| Crucial             | 8         | 10     | 16.33%  |
| Kingston            | 4         | 4      | 8.16%   |
| China               | 4         | 4      | 8.16%   |
| WDC                 | 3         | 4      | 6.12%   |
| Apple               | 3         | 4      | 6.12%   |
| Micron Technology   | 2         | 2      | 4.08%   |
| Toshiba             | 1         | 1      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| SK hynix            | 1         | 1      | 2.04%   |
| SanDisk             | 1         | 1      | 2.04%   |
| PNY                 | 1         | 1      | 2.04%   |
| Patriot             | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| Linux               | 1         | 1      | 2.04%   |
| LDLC                | 1         | 5      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| Intel               | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Dogfish             | 1         | 1      | 2.04%   |
| AGI                 | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 64        | 92     | 36.78%  |
| HDD     | 54        | 58     | 31.03%  |
| SSD     | 47        | 58     | 27.01%  |
| Unknown | 5         | 6      | 2.87%   |
| MMC     | 4         | 4      | 2.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 118    | 57.49%  |
| NVMe | 64        | 92     | 38.32%  |
| MMC  | 4         | 4      | 2.4%    |
| SAS  | 3         | 4      | 1.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 69     | 59.6%   |
| 0.51-1.0   | 35        | 41     | 35.35%  |
| 1.01-2.0   | 4         | 5      | 4.04%   |
| 4.01-10.0  | 1         | 1      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 43        | 27.74%  |
| 101-250        | 43        | 27.74%  |
| 501-1000       | 22        | 14.19%  |
| 1001-2000      | 16        | 10.32%  |
| Unknown        | 8         | 5.16%   |
| More than 3000 | 6         | 3.87%   |
| 1-20           | 6         | 3.87%   |
| 51-100         | 6         | 3.87%   |
| 21-50          | 3         | 1.94%   |
| 2001-3000      | 2         | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 28.05%  |
| 101-250        | 29        | 17.68%  |
| 51-100         | 21        | 12.8%   |
| 21-50          | 20        | 12.2%   |
| 251-500        | 17        | 10.37%  |
| 501-1000       | 12        | 7.32%   |
| 1001-2000      | 8         | 4.88%   |
| Unknown        | 8         | 4.88%   |
| More than 3000 | 1         | 0.61%   |
| 2001-3000      | 1         | 0.61%   |
| 0              | 1         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 10%     |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 10%     |
| HGST HTS541010A9E680 1TB                         | 2         | 2      | 10%     |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 5%      |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 5%      |
| WDC WD3200BEKT-60F3T1 320GB                      | 1         | 1      | 5%      |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 5%      |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 5%      |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 5%      |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5%      |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 5%      |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5%      |
| LDLC SSD 120GB                                   | 1         | 3      | 5%      |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 5%      |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 25%     |
| WDC                 | 4         | 4      | 20%     |
| HGST                | 4         | 4      | 20%     |
| Seagate             | 3         | 3      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| Samsung Electronics | 1         | 1      | 5%      |
| LDLC                | 1         | 3      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 27.78%  |
| WDC     | 4         | 4      | 22.22%  |
| HGST    | 4         | 4      | 22.22%  |
| Seagate | 3         | 3      | 16.67%  |
| Hitachi | 2         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 18     | 90%     |
| SSD  | 2         | 4      | 10%     |

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
| Works    | 79        | 103    | 48.77%  |
| Detected | 63        | 93     | 38.89%  |
| Malfunc  | 20        | 22     | 12.35%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 95        | 51.08%  |
| Samsung Electronics            | 25        | 13.44%  |
| AMD                            | 23        | 12.37%  |
| SanDisk                        | 10        | 5.38%   |
| SK hynix                       | 5         | 2.69%   |
| Phison Electronics             | 5         | 2.69%   |
| Kingston Technology Company    | 4         | 2.15%   |
| ADATA Technology               | 3         | 1.61%   |
| Union Memory (Shenzhen)        | 2         | 1.08%   |
| Solid State Storage Technology | 2         | 1.08%   |
| Micron/Crucial Technology      | 2         | 1.08%   |
| Micron Technology              | 2         | 1.08%   |
| Toshiba America Info Systems   | 1         | 0.54%   |
| Silicon Motion                 | 1         | 0.54%   |
| Shenzhen Longsys Electronics   | 1         | 0.54%   |
| Nvidia                         | 1         | 0.54%   |
| Marvell Technology Group       | 1         | 0.54%   |
| Lite-On Technology             | 1         | 0.54%   |
| Lenovo                         | 1         | 0.54%   |
| KIOXIA                         | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 21        | 10.88%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 15        | 7.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 12        | 6.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 11        | 5.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 10        | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 10        | 5.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 8         | 4.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 5         | 2.59%   |
| Intel Volume Management Device NVMe RAID Controller                          | 5         | 2.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 4         | 2.07%   |
| Phison E12 NVMe Controller                                                   | 4         | 2.07%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 4         | 2.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 4         | 2.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 4         | 2.07%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 4         | 2.07%   |
| SK hynix PC611 NVMe Solid State Drive                                        | 3         | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 3         | 1.55%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 3         | 1.55%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 3         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 1.55%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 2         | 1.04%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 2         | 1.04%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                        | 2         | 1.04%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 2         | 1.04%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 2         | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                          | 2         | 1.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                      | 2         | 1.04%   |
| Intel SSD 660P Series                                                        | 2         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.04%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB              | 1         | 0.52%   |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                        | 1         | 0.52%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)          | 1         | 0.52%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                           | 1         | 0.52%   |
| SK hynix BC511 NVMe SSD                                                      | 1         | 0.52%   |
| Silicon Motion Non-Volatile memory controller                                | 1         | 0.52%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                       | 1         | 0.52%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                   | 1         | 0.52%   |
| Sandisk WD Black SN850X NVMe SSD                                             | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 104       | 55.91%  |
| NVMe | 65        | 34.95%  |
| RAID | 15        | 8.06%   |
| IDE  | 2         | 1.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 77.33%  |
| AMD    | 34        | 22.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 2.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.99%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.32%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.32%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.32%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.32%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.32%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.32%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.32%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.32%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.32%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 1.32%   |
| AMD Athlon Gold 3150U with Radeon Graphics    | 2         | 1.32%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.66%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.66%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.66%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.66%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.66%   |
| Intel Pentium CPU B970 @ 2.30GHz              | 1         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 24%     |
| Intel Core i7           | 31        | 20.67%  |
| Other                   | 14        | 9.33%   |
| Intel Core i3           | 12        | 8%      |
| AMD Ryzen 7             | 10        | 6.67%   |
| AMD Ryzen 5             | 9         | 6%      |
| Intel Celeron           | 8         | 5.33%   |
| Intel Pentium           | 5         | 3.33%   |
| AMD Ryzen 3             | 5         | 3.33%   |
| Intel Core m3           | 2         | 1.33%   |
| Intel Core i9           | 2         | 1.33%   |
| Intel Core 2 Duo        | 2         | 1.33%   |
| AMD Athlon              | 2         | 1.33%   |
| Intel Xeon              | 1         | 0.67%   |
| Intel Pentium Silver    | 1         | 0.67%   |
| Intel Pentium Dual-Core | 1         | 0.67%   |
| Intel Atom              | 1         | 0.67%   |
| AMD Ryzen 9             | 1         | 0.67%   |
| AMD Ryzen 7 PRO         | 1         | 0.67%   |
| AMD Ryzen 5 PRO         | 1         | 0.67%   |
| AMD Phenom II           | 1         | 0.67%   |
| AMD E1                  | 1         | 0.67%   |
| AMD A6                  | 1         | 0.67%   |
| AMD A4                  | 1         | 0.67%   |
| AMD A10                 | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 44.67%  |
| 4      | 52        | 34.67%  |
| 8      | 14        | 9.33%   |
| 6      | 13        | 8.67%   |
| 12     | 2         | 1.33%   |
| 14     | 1         | 0.67%   |
| 10     | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 120       | 80%     |
| 1      | 30        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 150       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 30.07%  |
| 0x306a9    | 10        | 6.54%   |
| 0x206a7    | 9         | 5.88%   |
| 0xa0652    | 6         | 3.92%   |
| 0x806ec    | 5         | 3.27%   |
| 0x806e9    | 5         | 3.27%   |
| 0x806c1    | 5         | 3.27%   |
| 0x40651    | 5         | 3.27%   |
| 0x306d4    | 5         | 3.27%   |
| 0x08600106 | 5         | 3.27%   |
| 0x806ea    | 4         | 2.61%   |
| 0x706e5    | 4         | 2.61%   |
| 0x906ea    | 3         | 1.96%   |
| 0x906e9    | 3         | 1.96%   |
| 0x706a1    | 3         | 1.96%   |
| 0x08108109 | 3         | 1.96%   |
| 0x30678    | 2         | 1.31%   |
| 0x1067a    | 2         | 1.31%   |
| 0x08608103 | 2         | 1.31%   |
| 0x08600103 | 2         | 1.31%   |
| 0x08108102 | 2         | 1.31%   |
| 0x08101007 | 2         | 1.31%   |
| 0x906ed    | 1         | 0.65%   |
| 0x906a3    | 1         | 0.65%   |
| 0x806eb    | 1         | 0.65%   |
| 0x806d1    | 1         | 0.65%   |
| 0x806c2    | 1         | 0.65%   |
| 0x506e3    | 1         | 0.65%   |
| 0x506c9    | 1         | 0.65%   |
| 0x406e3    | 1         | 0.65%   |
| 0x306c3    | 1         | 0.65%   |
| 0x20655    | 1         | 0.65%   |
| 0x0a50000c | 1         | 0.65%   |
| 0x08701013 | 1         | 0.65%   |
| 0x08600109 | 1         | 0.65%   |
| 0x08600104 | 1         | 0.65%   |
| 0x0810100b | 1         | 0.65%   |
| 0x08001137 | 1         | 0.65%   |
| 0x0700010b | 1         | 0.65%   |
| 0x06006705 | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 20.67%  |
| IvyBridge        | 16        | 10.67%  |
| SandyBridge      | 12        | 8%      |
| Zen 2            | 11        | 7.33%   |
| Zen+             | 9         | 6%      |
| TigerLake        | 8         | 5.33%   |
| Haswell          | 8         | 5.33%   |
| CometLake        | 7         | 4.67%   |
| Broadwell        | 7         | 4.67%   |
| Unknown          | 7         | 4.67%   |
| Silvermont       | 5         | 3.33%   |
| IceLake          | 5         | 3.33%   |
| Zen              | 4         | 2.67%   |
| Skylake          | 3         | 2%      |
| Penryn           | 3         | 2%      |
| Goldmont plus    | 3         | 2%      |
| Alderlake Hybrid | 2         | 1.33%   |
| Zen 3            | 1         | 0.67%   |
| Westmere         | 1         | 0.67%   |
| Steamroller      | 1         | 0.67%   |
| Puma             | 1         | 0.67%   |
| K10              | 1         | 0.67%   |
| Jaguar           | 1         | 0.67%   |
| Goldmont         | 1         | 0.67%   |
| Excavator        | 1         | 0.67%   |
| Bonnell          | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 108       | 58.38%  |
| AMD    | 39        | 21.08%  |
| Nvidia | 38        | 20.54%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 14        | 7.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 5.32%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 9         | 4.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 9         | 4.79%   |
| Intel UHD Graphics 620                                                    | 7         | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 3.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 3.72%   |
| Intel HD Graphics 620                                                     | 6         | 3.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 3.19%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 2.66%   |
| Intel HD Graphics 5500                                                    | 5         | 2.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 4         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.13%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.13%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 4         | 2.13%   |
| AMD Lucienne                                                              | 4         | 2.13%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.6%    |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.06%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.06%   |
| Intel UHD Graphics 615                                                    | 2         | 1.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.06%   |
| Intel HD Graphics 630                                                     | 2         | 1.06%   |
| Intel HD Graphics 6000                                                    | 2         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.06%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 2         | 1.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.06%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.06%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.53%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.53%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.53%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.53%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.53%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.53%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 73        | 48.34%  |
| 1 x AMD        | 33        | 21.85%  |
| Intel + Nvidia | 30        | 19.87%  |
| 1 x Nvidia     | 7         | 4.64%   |
| Intel + AMD    | 4         | 2.65%   |
| 2 x AMD        | 2         | 1.32%   |
| 2 x Intel      | 1         | 0.66%   |
| AMD + Nvidia   | 1         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 126       | 84%     |
| Proprietary | 23        | 15.33%  |
| Unknown     | 1         | 0.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 68.87%  |
| 1.01-2.0   | 15        | 9.93%   |
| 0.01-0.5   | 15        | 9.93%   |
| 0.51-1.0   | 6         | 3.97%   |
| 3.01-4.0   | 5         | 3.31%   |
| 5.01-6.0   | 3         | 1.99%   |
| 7.01-8.0   | 2         | 1.32%   |
| 2.01-3.0   | 1         | 0.66%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 19.32%  |
| BOE                     | 28        | 15.91%  |
| Chimei Innolux          | 25        | 14.2%   |
| LG Display              | 24        | 13.64%  |
| Samsung Electronics     | 13        | 7.39%   |
| Chi Mei Optoelectronics | 5         | 2.84%   |
| Goldstar                | 4         | 2.27%   |
| Dell                    | 4         | 2.27%   |
| Apple                   | 4         | 2.27%   |
| PANDA                   | 3         | 1.7%    |
| Lenovo                  | 3         | 1.7%    |
| InfoVision              | 3         | 1.7%    |
| Hewlett-Packard         | 3         | 1.7%    |
| ASUSTek Computer        | 3         | 1.7%    |
| Sharp                   | 2         | 1.14%   |
| Philips                 | 2         | 1.14%   |
| BenQ                    | 2         | 1.14%   |
| Acer                    | 2         | 1.14%   |
| ViewSonic               | 1         | 0.57%   |
| Unknown                 | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| MSI                     | 1         | 0.57%   |
| LGD                     | 1         | 0.57%   |
| KDC                     | 1         | 0.57%   |
| HUAWEI                  | 1         | 0.57%   |
| HKC                     | 1         | 0.57%   |
| CSO                     | 1         | 0.57%   |
| Aosiman                 | 1         | 0.57%   |
| AOC                     | 1         | 0.57%   |
| Ancor Communications    | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 4         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.7%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 3         | 1.7%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 1.14%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 1.14%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.14%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.14%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.14%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.14%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                      | 2         | 1.14%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO499F 1920x1080 344x194mm 15.5-inch            | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 1.14%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.14%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.57%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 1         | 0.57%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                             | 1         | 0.57%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.57%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.57%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.57%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.57%   |
| Samsung Electronics LS27A800U SAM71A1 3840x2160 597x336mm 27.0-inch       | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch     | 1         | 0.57%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.57%   |
| Philips PHL 240B9 PHL0966 1920x1200 518x324mm 24.1-inch                   | 1         | 0.57%   |
| PANDA LCD Monitor NCP0054 1920x1080 344x194mm 15.5-inch                   | 1         | 0.57%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.57%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.57%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                   | 1         | 0.57%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.57%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.57%   |
| LG Display LCD Monitor LGD06D6 1920x1080 309x174mm 14.0-inch              | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 46.06%  |
| 1366x768 (WXGA)    | 56        | 33.94%  |
| 3840x2160 (4K)     | 6         | 3.64%   |
| 1600x900 (HD+)     | 6         | 3.64%   |
| 2560x1600          | 5         | 3.03%   |
| 2560x1440 (QHD)    | 4         | 2.42%   |
| 1440x900 (WXGA+)   | 4         | 2.42%   |
| 3456x2160          | 1         | 0.61%   |
| 3440x1440          | 1         | 0.61%   |
| 3072x1920          | 1         | 0.61%   |
| 2288x1287          | 1         | 0.61%   |
| 2160x1440          | 1         | 0.61%   |
| 1920x1200 (WUXGA)  | 1         | 0.61%   |
| 1680x1050 (WSXGA+) | 1         | 0.61%   |
| 1280x800 (WXGA)    | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 77        | 44%     |
| 14      | 27        | 15.43%  |
| 13      | 23        | 13.14%  |
| 17      | 9         | 5.14%   |
| 27      | 8         | 4.57%   |
| 21      | 8         | 4.57%   |
| 24      | 7         | 4%      |
| 16      | 3         | 1.71%   |
| 11      | 3         | 1.71%   |
| 23      | 2         | 1.14%   |
| 142     | 1         | 0.57%   |
| 34      | 1         | 0.57%   |
| 28      | 1         | 0.57%   |
| 20      | 1         | 0.57%   |
| 19      | 1         | 0.57%   |
| 12      | 1         | 0.57%   |
| 8       | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 116       | 66.67%  |
| 501-600        | 15        | 8.62%   |
| 351-400        | 14        | 8.05%   |
| 201-300        | 12        | 6.9%    |
| 401-500        | 10        | 5.75%   |
| 601-700        | 3         | 1.72%   |
| More than 2000 | 1         | 0.57%   |
| 701-800        | 1         | 0.57%   |
| 101-200        | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 132       | 87.42%  |
| 16/10   | 14        | 9.27%   |
| 3/2     | 1         | 0.66%   |
| 21/9    | 1         | 0.66%   |
| 1.00    | 1         | 0.66%   |
| 0.62    | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 44.83%  |
| 81-90          | 41        | 23.56%  |
| 201-250        | 13        | 7.47%   |
| 71-80          | 8         | 4.6%    |
| 301-350        | 8         | 4.6%    |
| 121-130        | 8         | 4.6%    |
| 51-60          | 3         | 1.72%   |
| 251-300        | 3         | 1.72%   |
| 151-200        | 3         | 1.72%   |
| 351-500        | 2         | 1.15%   |
| 111-120        | 2         | 1.15%   |
| More than 1000 | 1         | 0.57%   |
| 61-70          | 1         | 0.57%   |
| 1-40           | 1         | 0.57%   |
| 131-140        | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 76        | 45.24%  |
| 101-120       | 52        | 30.95%  |
| 51-100        | 24        | 14.29%  |
| 161-240       | 10        | 5.95%   |
| More than 240 | 4         | 2.38%   |
| 1-50          | 1         | 0.6%    |
| Unknown       | 1         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 123       | 80.39%  |
| 2     | 29        | 18.95%  |
| 0     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 94        | 39.33%  |
| Intel                    | 79        | 33.05%  |
| Qualcomm Atheros         | 25        | 10.46%  |
| Broadcom                 | 13        | 5.44%   |
| MediaTek                 | 4         | 1.67%   |
| Broadcom Limited         | 4         | 1.67%   |
| Samsung Electronics      | 3         | 1.26%   |
| Ralink                   | 2         | 0.84%   |
| Qualcomm                 | 2         | 0.84%   |
| Xiaomi                   | 1         | 0.42%   |
| TP-Link                  | 1         | 0.42%   |
| Sierra Wireless          | 1         | 0.42%   |
| Ralink Technology        | 1         | 0.42%   |
| OPPO Electronics         | 1         | 0.42%   |
| Marvell Technology Group | 1         | 0.42%   |
| Linksys                  | 1         | 0.42%   |
| Lenovo                   | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| Dell                     | 1         | 0.42%   |
| ASIX Electronics         | 1         | 0.42%   |
| Aquantia                 | 1         | 0.42%   |
| Apple                    | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 55        | 19.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 17        | 5.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12        | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 11        | 3.86%   |
| Intel Wireless 8265 / 8275                                           | 9         | 3.16%   |
| Intel Wi-Fi 6 AX200                                                  | 9         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 8         | 2.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 7         | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 2.46%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 1.4%    |
| Intel Wireless 7265                                                  | 4         | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                                | 4         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.05%   |
| Intel Wireless 7260                                                  | 3         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.05%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.05%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2         | 0.7%    |
| Realtek 802.11ac NIC                                                 | 2         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 0.7%    |
| Intel Wireless 3165                                                  | 2         | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2         | 0.7%    |
| Intel Ethernet Connection I217-LM                                    | 2         | 0.7%    |
| Intel Ethernet Connection (11) I219-LM                               | 2         | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 0.7%    |
| Intel Centrino Ultimate-N 6300                                       | 2         | 0.7%    |
| Intel Centrino Advanced-N 6235                                       | 2         | 0.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 48.39%  |
| Realtek Semiconductor | 31        | 20%     |
| Qualcomm Atheros      | 22        | 14.19%  |
| Broadcom              | 12        | 7.74%   |
| MediaTek              | 4         | 2.58%   |
| Broadcom Limited      | 4         | 2.58%   |
| Ralink                | 2         | 1.29%   |
| TP-Link               | 1         | 0.65%   |
| Sierra Wireless       | 1         | 0.65%   |
| Ralink Technology     | 1         | 0.65%   |
| Qualcomm              | 1         | 0.65%   |
| Dell                  | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12        | 7.64%   |
| Intel Wireless 8265 / 8275                                           | 9         | 5.73%   |
| Intel Wi-Fi 6 AX200                                                  | 9         | 5.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 8         | 5.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 4.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 4.46%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 3.82%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 3.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 3.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 3.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 2.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 4         | 2.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 4         | 2.55%   |
| Intel Wireless 7265                                                  | 4         | 2.55%   |
| Broadcom BCM43142 802.11b/g/n                                        | 4         | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.91%   |
| Intel Wireless 7260                                                  | 3         | 1.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.91%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 1.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.91%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.91%   |
| Realtek 802.11ac NIC                                                 | 2         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.27%   |
| Intel Wireless 3165                                                  | 2         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 2         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.27%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 2         | 1.27%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.64%   |
| Sierra Wireless MC7750                                               | 1         | 0.64%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                       | 1         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.64%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.64%   |
| Realtek 802.11n WLAN Adapter                                         | 1         | 0.64%   |
| Ralink RT5370 Wireless Adapter                                       | 1         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 79        | 63.71%  |
| Intel                    | 27        | 21.77%  |
| Qualcomm Atheros         | 5         | 4.03%   |
| Broadcom                 | 2         | 1.61%   |
| Xiaomi                   | 1         | 0.81%   |
| Samsung Electronics      | 1         | 0.81%   |
| Qualcomm                 | 1         | 0.81%   |
| OPPO Electronics         | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| Linksys                  | 1         | 0.81%   |
| Lenovo                   | 1         | 0.81%   |
| Huawei Technologies      | 1         | 0.81%   |
| ASIX Electronics         | 1         | 0.81%   |
| Aquantia                 | 1         | 0.81%   |
| Apple                    | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 43.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 13.49%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 8.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 5.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 3.17%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.59%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.59%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.79%   |
| Qualcomm A0001                                                    | 1         | 0.79%   |
| OPPO RMX3623                                                      | 1         | 0.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.79%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.79%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.79%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.79%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.79%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.79%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.79%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.79%   |
| Huawei E353/E3131                                                 | 1         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.79%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.79%   |
| ASIX AX88772                                                      | 1         | 0.79%   |
| Aquantia SANLink3 10GbE SFP+ Network Adapter                      | 1         | 0.79%   |
| Apple iPad 4/Mini1                                                | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 56.11%  |
| Ethernet | 113       | 43.13%  |
| Modem    | 2         | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 127       | 79.38%  |
| Ethernet | 33        | 20.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 102       | 67.55%  |
| 1     | 45        | 29.8%   |
| 3     | 3         | 1.99%   |
| 0     | 1         | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 126       | 81.82%  |
| Yes  | 28        | 18.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 47.97%  |
| Realtek Semiconductor           | 22        | 17.89%  |
| Broadcom                        | 10        | 8.13%   |
| Qualcomm Atheros Communications | 7         | 5.69%   |
| IMC Networks                    | 6         | 4.88%   |
| Lite-On Technology              | 5         | 4.07%   |
| Apple                           | 4         | 3.25%   |
| Foxconn / Hon Hai               | 3         | 2.44%   |
| Realtek                         | 2         | 1.63%   |
| Cambridge Silicon Radio         | 2         | 1.63%   |
| Ralink                          | 1         | 0.81%   |
| MediaTek                        | 1         | 0.81%   |
| ASUSTek Computer                | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 13.71%  |
| Intel AX201 Bluetooth                               | 16        | 12.9%   |
| Realtek Bluetooth Radio                             | 13        | 10.48%  |
| Intel AX200 Bluetooth                               | 9         | 7.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 6.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 3.23%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 3.23%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 2.42%   |
| IMC Networks Wireless_Device                        | 3         | 2.42%   |
| Realtek Bluetooth Radio                             | 2         | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.61%   |
| Intel Bluetooth Device                              | 2         | 1.61%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.61%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 1.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.61%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.61%   |
| Apple Bluetooth Host Controller                     | 2         | 1.61%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.81%   |
| Realtek Bluetooth 5.1 Radio                         | 1         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.81%   |
| MediaTek Wireless_Device                            | 1         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.81%   |
| Intel AX210 Bluetooth                               | 1         | 0.81%   |
| IMC Networks Bluetooth Device                       | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.81%   |
| Broadcom HP Portable Valentine                      | 1         | 0.81%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.81%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.81%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 115       | 59.28%  |
| AMD                    | 36        | 18.56%  |
| Nvidia                 | 25        | 12.89%  |
| Realtek Semiconductor  | 3         | 1.55%   |
| C-Media Electronics    | 3         | 1.55%   |
| Texas Instruments      | 1         | 0.52%   |
| Plantronics            | 1         | 0.52%   |
| Lenovo                 | 1         | 0.52%   |
| Hewlett-Packard        | 1         | 0.52%   |
| Harman                 | 1         | 0.52%   |
| GN Netcom              | 1         | 0.52%   |
| Generalplus Technology | 1         | 0.52%   |
| DSEA A/S               | 1         | 0.52%   |
| Corsair                | 1         | 0.52%   |
| ASUSTek Computer       | 1         | 0.52%   |
| Arylic                 | 1         | 0.52%   |
| Apple                  | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 26        | 10.74%  |
| Intel Sunrise Point-LP HD Audio                                            | 18        | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 6.61%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 5.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 4.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 3.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 2.89%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 2.89%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.48%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.65%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.65%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.24%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.24%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.83%   |
| Nvidia Audio device                                                        | 2         | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.83%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.83%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.83%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.41%   |
| Realtek Semiconductor USB Condenser Microphone                             | 1         | 0.41%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.41%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.41%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.41%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 30.19%  |
| SK hynix            | 36        | 22.64%  |
| Kingston            | 16        | 10.06%  |
| Micron Technology   | 15        | 9.43%   |
| Unknown             | 7         | 4.4%    |
| A-DATA Technology   | 4         | 2.52%   |
| Unknown             | 4         | 2.52%   |
| Team                | 3         | 1.89%   |
| Smart               | 3         | 1.89%   |
| Silicon Power       | 3         | 1.89%   |
| Ramaxel Technology  | 3         | 1.89%   |
| Nanya Technology    | 3         | 1.89%   |
| Crucial             | 3         | 1.89%   |
| Corsair             | 3         | 1.89%   |
| Unknown (ABCD)      | 2         | 1.26%   |
| Smart Brazil        | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Elpida              | 1         | 0.63%   |
| Avant               | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |
| AMD                 | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 3.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 2.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 2.42%   |
| Unknown                                                          | 4         | 2.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.82%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 1.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.82%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.21%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.21%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.21%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.21%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.21%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.21%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.21%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.21%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.21%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.21%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.21%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.61%   |
| Unknown RAM DDR4 NB 16G 16GB SODIMM DDR4 2667MT/s                | 1         | 0.61%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.61%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 1         | 0.61%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.61%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.61%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.61%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s     | 1         | 0.61%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 65        | 52%     |
| DDR3    | 46        | 36.8%   |
| LPDDR4  | 4         | 3.2%    |
| LPDDR3  | 4         | 3.2%    |
| SDRAM   | 2         | 1.6%    |
| DDR5    | 2         | 1.6%    |
| DDR2    | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 88.1%   |
| Row Of Chips | 12        | 9.52%   |
| DIMM         | 1         | 0.79%   |
| Chip         | 1         | 0.79%   |
| Unknown      | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 53        | 36.81%  |
| 8192  | 47        | 32.64%  |
| 16384 | 23        | 15.97%  |
| 2048  | 12        | 8.33%   |
| 32768 | 8         | 5.56%   |
| 1024  | 1         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 41        | 29.93%  |
| 3200  | 32        | 23.36%  |
| 2667  | 27        | 19.71%  |
| 2400  | 11        | 8.03%   |
| 1333  | 7         | 5.11%   |
| 1334  | 4         | 2.92%   |
| 2133  | 3         | 2.19%   |
| 4800  | 2         | 1.46%   |
| 4199  | 2         | 1.46%   |
| 3266  | 2         | 1.46%   |
| 4267  | 1         | 0.73%   |
| 3400  | 1         | 0.73%   |
| 2933  | 1         | 0.73%   |
| 1066  | 1         | 0.73%   |
| 800   | 1         | 0.73%   |
| 667   | 1         | 0.73%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Brother HL-L3270CDW series | 1         | 100%    |

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
| Chicony Electronics                    | 30        | 22.9%   |
| IMC Networks                           | 16        | 12.21%  |
| Quanta                                 | 14        | 10.69%  |
| Realtek Semiconductor                  | 12        | 9.16%   |
| Microdia                               | 9         | 6.87%   |
| Bison Electronics                      | 9         | 6.87%   |
| Suyin                                  | 6         | 4.58%   |
| Alcor Micro                            | 5         | 3.82%   |
| Syntek                                 | 4         | 3.05%   |
| Sunplus Innovation Technology          | 4         | 3.05%   |
| Sonix Technology                       | 4         | 3.05%   |
| Silicon Motion                         | 4         | 3.05%   |
| Luxvisions Innotech Limited            | 4         | 3.05%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.29%   |
| Acer                                   | 3         | 2.29%   |
| Lite-On Technology                     | 1         | 0.76%   |
| LG Electronics                         | 1         | 0.76%   |
| Lenovo                                 | 1         | 0.76%   |
| Apple                                  | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                      | 9         | 6.87%   |
| Chicony HD WebCam                                   | 6         | 4.58%   |
| Chicony integrated camera                           | 5         | 3.82%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 3.05%   |
| Realtek Integrated_Webcam_HD                        | 4         | 3.05%   |
| Microdia Integrated Webcam                          | 4         | 3.05%   |
| Bison Integrated Camera                             | 4         | 3.05%   |
| Syntek EasyCamera                                   | 3         | 2.29%   |
| Quanta HP TrueVision HD Camera                      | 3         | 2.29%   |
| Microdia Integrated_Webcam_HD                       | 3         | 2.29%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 2.29%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 2.29%   |
| Suyin HP Webcam                                     | 2         | 1.53%   |
| Sunplus HD WebCam                                   | 2         | 1.53%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 1.53%   |
| Realtek USB2.0 HD UVC WebCam                        | 2         | 1.53%   |
| Realtek HD WebCam                                   | 2         | 1.53%   |
| Quanta VGA WebCam                                   | 2         | 1.53%   |
| Quanta USB2.0 VGA UVC WebCam                        | 2         | 1.53%   |
| Quanta HP Webcam                                    | 2         | 1.53%   |
| Quanta HD Webcam                                    | 2         | 1.53%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.53%   |
| Chicony thinkpad t430s camera                       | 2         | 1.53%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.53%   |
| Chicony HP TrueVision HD Camera                     | 2         | 1.53%   |
| Bison Lenovo EasyCamera                             | 2         | 1.53%   |
| Syntek Integrated Camera                            | 1         | 0.76%   |
| Suyin USB Webcam                                    | 1         | 0.76%   |
| Suyin NEC HD WebCam                                 | 1         | 0.76%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.76%   |
| Suyin 1.3M HD WebCam                                | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.76%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 0.76%   |
| Silicon Motion WebCam SC-10HDD12636N                | 1         | 0.76%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.76%   |
| Realtek Integrated Webcam                           | 1         | 0.76%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 0.76%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.76%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 6         | 37.5%   |
| Synaptics                  | 5         | 31.25%  |
| Validity Sensors           | 3         | 18.75%  |
| STMicroelectronics         | 1         | 6.25%   |
| AuthenTec                  | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                       | 5         | 31.25%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 18.75%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 12.5%   |
| Validity Sensors VFS491                                   | 1         | 6.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 6.25%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 6.25%   |
| AuthenTec AES2810                                         | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 70%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 20%     |
| Broadcom 58200                                                               | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom 5880                                                                | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 101       | 66.01%  |
| 1     | 45        | 29.41%  |
| 2     | 6         | 3.92%   |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 24.59%  |
| Graphics card            | 8         | 13.11%  |
| Chipcard                 | 8         | 13.11%  |
| Net/wireless             | 7         | 11.48%  |
| Multimedia controller    | 6         | 9.84%   |
| Camera                   | 5         | 8.2%    |
| Bluetooth                | 4         | 6.56%   |
| Communication controller | 3         | 4.92%   |
| Storage                  | 2         | 3.28%   |
| Network                  | 1         | 1.64%   |
| Net/ethernet             | 1         | 1.64%   |
| Dvb card                 | 1         | 1.64%   |

