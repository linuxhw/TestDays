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

Total: 189

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Artix Rolling  | 79        | 57.25%  |
| Artix          | 54        | 39.13%  |
| Artix 20230710 | 1         | 0.72%   |
| Artix 20220713 | 1         | 0.72%   |
| Artix 20220123 | 1         | 0.72%   |
| Artix 20201207 | 1         | 0.72%   |
| Artix 20201128 | 1         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 132       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Notebooks | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 6         | 3.85%   |
| 6.3.2-artix1-1     | 4         | 2.56%   |
| 6.0.7-artix1-1     | 3         | 1.92%   |
| 5.7.6-artix1-1     | 3         | 1.92%   |
| 6.3.3-artix1-1     | 2         | 1.28%   |
| 6.3.1-artix1-1     | 2         | 1.28%   |
| 6.1.8-artix1-1     | 2         | 1.28%   |
| 6.1.6-artix1-1     | 2         | 1.28%   |
| 6.1.10-zen1-1-zen  | 2         | 1.28%   |
| 6.0.12-artix1-1    | 2         | 1.28%   |
| 5.7.12-artix1-1    | 2         | 1.28%   |
| 5.19.12-artix1-1   | 2         | 1.28%   |
| 5.18.6-artix1-1    | 2         | 1.28%   |
| 5.18.10-artix1-1   | 2         | 1.28%   |
| 5.18.0-artix1-1    | 2         | 1.28%   |
| 5.17.1-artix1-1    | 2         | 1.28%   |
| 5.16.8-artix1-2    | 2         | 1.28%   |
| 5.16.10-artix1-1   | 2         | 1.28%   |
| 5.15.12-artix1-1   | 2         | 1.28%   |
| 5.14.16-artix1-1   | 2         | 1.28%   |
| 5.13.8-artix1-1    | 2         | 1.28%   |
| 5.12.8-artix1-1    | 2         | 1.28%   |
| 5.12.12-zen1-1-zen | 2         | 1.28%   |
| 5.12.12-artix1-1   | 2         | 1.28%   |
| 5.11.6-artix1-1    | 2         | 1.28%   |
| 5.10.6-artix1-1    | 2         | 1.28%   |
| 5.10.4-artix2-1    | 2         | 1.28%   |
| 5.10.16-artix1-1   | 2         | 1.28%   |
| 6.4.8-lqx1-1-lqx   | 1         | 0.64%   |
| 6.4.4-zen1-1-zen   | 1         | 0.64%   |
| 6.4.2-artix1-1     | 1         | 0.64%   |
| 6.4.1              | 1         | 0.64%   |
| 6.3.6-artix1-1     | 1         | 0.64%   |
| 6.3.4-artix1-1     | 1         | 0.64%   |
| 6.3.1-zen1-1-zen   | 1         | 0.64%   |
| 6.2.13-artix1-1    | 1         | 0.64%   |
| 6.2.0-zen1-1-zen   | 1         | 0.64%   |
| 6.1.32-1-lts       | 1         | 0.64%   |
| 6.1.3-273-tkg-bmq  | 1         | 0.64%   |
| 6.1.20-1-lts       | 1         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 4.49%   |
| 6.3.2   | 4         | 2.56%   |
| 6.1.10  | 4         | 2.56%   |
| 6.0.7   | 4         | 2.56%   |
| 5.12.12 | 4         | 2.56%   |
| 6.3.1   | 3         | 1.92%   |
| 5.7.6   | 3         | 1.92%   |
| 5.17.1  | 3         | 1.92%   |
| 5.15.12 | 3         | 1.92%   |
| 5.12.8  | 3         | 1.92%   |
| 6.3.3   | 2         | 1.28%   |
| 6.1.8   | 2         | 1.28%   |
| 6.1.6   | 2         | 1.28%   |
| 6.0.12  | 2         | 1.28%   |
| 5.9.0   | 2         | 1.28%   |
| 5.8.14  | 2         | 1.28%   |
| 5.7.12  | 2         | 1.28%   |
| 5.19.12 | 2         | 1.28%   |
| 5.18.6  | 2         | 1.28%   |
| 5.18.10 | 2         | 1.28%   |
| 5.18.0  | 2         | 1.28%   |
| 5.16.8  | 2         | 1.28%   |
| 5.16.10 | 2         | 1.28%   |
| 5.14.16 | 2         | 1.28%   |
| 5.13.8  | 2         | 1.28%   |
| 5.12.14 | 2         | 1.28%   |
| 5.11.6  | 2         | 1.28%   |
| 5.10.6  | 2         | 1.28%   |
| 5.10.4  | 2         | 1.28%   |
| 5.10.16 | 2         | 1.28%   |
| 6.4.8   | 1         | 0.64%   |
| 6.4.4   | 1         | 0.64%   |
| 6.4.2   | 1         | 0.64%   |
| 6.4.1   | 1         | 0.64%   |
| 6.3.6   | 1         | 0.64%   |
| 6.3.4   | 1         | 0.64%   |
| 6.2.13  | 1         | 0.64%   |
| 6.2.0   | 1         | 0.64%   |
| 6.1.32  | 1         | 0.64%   |
| 6.1.3   | 1         | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 13        | 8.67%   |
| 6.1     | 12        | 8%      |
| 5.18    | 12        | 8%      |
| 5.12    | 12        | 8%      |
| 6.3     | 11        | 7.33%   |
| 5.9     | 11        | 7.33%   |
| 5.10    | 11        | 7.33%   |
| 6.0     | 8         | 5.33%   |
| 5.17    | 8         | 5.33%   |
| 5.16    | 8         | 5.33%   |
| 5.11    | 8         | 5.33%   |
| 5.7     | 6         | 4%      |
| 5.19    | 6         | 4%      |
| 5.8     | 5         | 3.33%   |
| 6.4     | 4         | 2.67%   |
| 5.14    | 4         | 2.67%   |
| 5.13    | 4         | 2.67%   |
| 6.2     | 2         | 1.33%   |
| 6.0.5   | 1         | 0.67%   |
| 5.6     | 1         | 0.67%   |
| 5.5     | 1         | 0.67%   |
| 5.4     | 1         | 0.67%   |
| 4.19    | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 132       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 33        | 23.57%  |
| XFCE           | 24        | 17.14%  |
| Unknown        | 24        | 17.14%  |
| GNOME          | 15        | 10.71%  |
| X-Cinnamon     | 8         | 5.71%   |
| MATE           | 7         | 5%      |
| LXQt           | 5         | 3.57%   |
| KDE            | 4         | 2.86%   |
| i3             | 4         | 2.86%   |
| LXDE           | 3         | 2.14%   |
| Cinnamon       | 3         | 2.14%   |
| sway           | 2         | 1.43%   |
| bspwm          | 2         | 1.43%   |
| xmonad         | 1         | 0.71%   |
| xinitrc        | 1         | 0.71%   |
| sway-dbus      | 1         | 0.71%   |
| nxde           | 1         | 0.71%   |
| awesomeminimal | 1         | 0.71%   |
| awesome        | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 92        | 67.65%  |
| Wayland | 17        | 12.5%   |
| Tty     | 17        | 12.5%   |
| Unknown | 10        | 7.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 37.5%   |
| LightDM | 43        | 31.62%  |
| SDDM    | 36        | 26.47%  |
| XDM     | 2         | 1.47%   |
| SLiM    | 1         | 0.74%   |
| Ly      | 1         | 0.74%   |
| LXDM    | 1         | 0.74%   |
| GDM     | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 66        | 48.18%  |
| Unknown | 18        | 13.14%  |
| ru_RU   | 8         | 5.84%   |
| en_GB   | 8         | 5.84%   |
| C       | 7         | 5.11%   |
| fr_FR   | 4         | 2.92%   |
| pl_PL   | 2         | 1.46%   |
| it_IT   | 2         | 1.46%   |
| es_ES   | 2         | 1.46%   |
| en_CA   | 2         | 1.46%   |
| en_AG   | 2         | 1.46%   |
| vi_VN   | 1         | 0.73%   |
| uk_UA   | 1         | 0.73%   |
| tr_TR   | 1         | 0.73%   |
| ro_RO   | 1         | 0.73%   |
| pt_PT   | 1         | 0.73%   |
| pt_BR   | 1         | 0.73%   |
| fi_FI   | 1         | 0.73%   |
| es_MX   | 1         | 0.73%   |
| es_GT   | 1         | 0.73%   |
| es_CO   | 1         | 0.73%   |
| en_NZ   | 1         | 0.73%   |
| en_IN   | 1         | 0.73%   |
| en_AU   | 1         | 0.73%   |
| el_GR   | 1         | 0.73%   |
| de_DE   | 1         | 0.73%   |
| cs_CZ   | 1         | 0.73%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 92        | 69.17%  |
| BIOS | 41        | 30.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 74.63%  |
| Btrfs   | 26        | 19.4%   |
| Xfs     | 3         | 2.24%   |
| F2fs    | 3         | 2.24%   |
| Overlay | 2         | 1.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 94        | 70.68%  |
| Unknown | 20        | 15.04%  |
| MBR     | 19        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 84.21%  |
| Yes       | 21        | 15.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 73.48%  |
| Yes       | 35        | 26.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 36        | 27.27%  |
| Hewlett-Packard        | 20        | 15.15%  |
| Dell                   | 17        | 12.88%  |
| ASUSTek Computer       | 15        | 11.36%  |
| Acer                   | 14        | 10.61%  |
| Samsung Electronics    | 3         | 2.27%   |
| MSI                    | 3         | 2.27%   |
| HUAWEI                 | 3         | 2.27%   |
| Gigabyte Technology    | 3         | 2.27%   |
| Apple                  | 3         | 2.27%   |
| Timi                   | 2         | 1.52%   |
| Notebook               | 2         | 1.52%   |
| GPD                    | 2         | 1.52%   |
| UNOWHY                 | 1         | 0.76%   |
| Toshiba                | 1         | 0.76%   |
| Quanta                 | 1         | 0.76%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.76%   |
| MOTILE                 | 1         | 0.76%   |
| LG Electronics         | 1         | 0.76%   |
| HONOR                  | 1         | 0.76%   |
| Fujitsu                | 1         | 0.76%   |
| AXIOO                  | 1         | 0.76%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                                  | 2         | 1.52%   |
| Lenovo IdeaPad 5 15IIL05 81YK                         | 2         | 1.52%   |
| HP 15                                                 | 2         | 1.52%   |
| GPD P2 MAX                                            | 2         | 1.52%   |
| Dell Precision M6600                                  | 2         | 1.52%   |
| Dell Precision 7550                                   | 2         | 1.52%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA               | 2         | 1.52%   |
| Apple MacBookAir7,2                                   | 2         | 1.52%   |
| Acer Nitro AN515-52                                   | 2         | 1.52%   |
| UNOWHY Y13G010S4EI                                    | 1         | 0.76%   |
| Toshiba Satellite P775                                | 1         | 0.76%   |
| Samsung R425D/R525D                                   | 1         | 0.76%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                   | 1         | 0.76%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.76%   |
| Quanta SWH                                            | 1         | 0.76%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro                   | 1         | 0.76%   |
| Notebook N141CU                                       | 1         | 0.76%   |
| Notebook N130BU                                       | 1         | 0.76%   |
| MSI Modern 15 A11M                                    | 1         | 0.76%   |
| MSI GP72 7RDX                                         | 1         | 0.76%   |
| MSI GF65 Thin 10SDR                                   | 1         | 0.76%   |
| MOTILE M141                                           | 1         | 0.76%   |
| LG 17Z990-R.AAC9U1                                    | 1         | 0.76%   |
| Lenovo ThinkPad W520 4284W2U                          | 1         | 0.76%   |
| Lenovo ThinkPad W500 4063CJ5                          | 1         | 0.76%   |
| Lenovo ThinkPad T480s 20L8S3D400                      | 1         | 0.76%   |
| Lenovo ThinkPad T480 MFG_IN_GO                        | 1         | 0.76%   |
| Lenovo ThinkPad T440s 20ARS0MV00                      | 1         | 0.76%   |
| Lenovo ThinkPad T430 2350BC6                          | 1         | 0.76%   |
| Lenovo ThinkPad T430 2347H76                          | 1         | 0.76%   |
| Lenovo ThinkPad T430 2344BZU                          | 1         | 0.76%   |
| Lenovo ThinkPad T430 23427YU                          | 1         | 0.76%   |
| Lenovo ThinkPad T420 4236H45                          | 1         | 0.76%   |
| Lenovo ThinkPad T420 4180AG3                          | 1         | 0.76%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00                  | 1         | 0.76%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800                  | 1         | 0.76%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH                   | 1         | 0.76%   |
| Lenovo ThinkPad L15 Gen 1 20U7S06Y00                  | 1         | 0.76%   |
| Lenovo ThinkPad Edge E431 6277C4P                     | 1         | 0.76%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK                  | 1         | 0.76%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 18        | 13.64%  |
| Lenovo IdeaPad                  | 10        | 7.58%   |
| Acer Aspire                     | 9         | 6.82%   |
| HP Laptop                       | 6         | 4.55%   |
| Dell Precision                  | 6         | 4.55%   |
| Dell Inspiron                   | 6         | 4.55%   |
| Dell Latitude                   | 4         | 3.03%   |
| HP 250                          | 3         | 2.27%   |
| ASUS VivoBook                   | 3         | 2.27%   |
| ASUS ASUS                       | 3         | 2.27%   |
| Acer Nitro                      | 3         | 2.27%   |
| Timi RedmiBook                  | 2         | 1.52%   |
| HP Pavilion                     | 2         | 1.52%   |
| HP 255                          | 2         | 1.52%   |
| HP 15                           | 2         | 1.52%   |
| GPD P2                          | 2         | 1.52%   |
| Apple MacBookAir7               | 2         | 1.52%   |
| UNOWHY Y13G010S4EI              | 1         | 0.76%   |
| Toshiba Satellite               | 1         | 0.76%   |
| Samsung R425D                   | 1         | 0.76%   |
| Samsung 350V5C                  | 1         | 0.76%   |
| Samsung 300E5EV                 | 1         | 0.76%   |
| Quanta SWH                      | 1         | 0.76%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.76%   |
| Notebook N141CU                 | 1         | 0.76%   |
| Notebook N130BU                 | 1         | 0.76%   |
| MSI Modern                      | 1         | 0.76%   |
| MSI GP72                        | 1         | 0.76%   |
| MSI GF65                        | 1         | 0.76%   |
| MOTILE M141                     | 1         | 0.76%   |
| LG 17Z990-R.AAC9U1              | 1         | 0.76%   |
| Lenovo ThinkBook                | 1         | 0.76%   |
| Lenovo S20-30                   | 1         | 0.76%   |
| Lenovo Legion                   | 1         | 0.76%   |
| Lenovo LaVie                    | 1         | 0.76%   |
| Lenovo G400s                    | 1         | 0.76%   |
| Lenovo B590                     | 1         | 0.76%   |
| Lenovo B570e                    | 1         | 0.76%   |
| Lenovo B50-80                   | 1         | 0.76%   |
| HUAWEI WRT-WX9                  | 1         | 0.76%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 28        | 21.21%  |
| 2019 | 15        | 11.36%  |
| 2018 | 15        | 11.36%  |
| 2011 | 13        | 9.85%   |
| 2013 | 10        | 7.58%   |
| 2014 | 9         | 6.82%   |
| 2012 | 9         | 6.82%   |
| 2017 | 8         | 6.06%   |
| 2021 | 7         | 5.3%    |
| 2015 | 7         | 5.3%    |
| 2016 | 4         | 3.03%   |
| 2022 | 3         | 2.27%   |
| 2010 | 3         | 2.27%   |
| 2009 | 1         | 0.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 132       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 131       | 99.24%  |
| Enabled  | 1         | 0.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 99.24%  |
| Yes  | 1         | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 42        | 31.58%  |
| 8.01-16.0   | 29        | 21.8%   |
| 16.01-24.0  | 26        | 19.55%  |
| 3.01-4.0    | 19        | 14.29%  |
| 32.01-64.0  | 6         | 4.51%   |
| 1.01-2.0    | 5         | 3.76%   |
| 24.01-32.0  | 3         | 2.26%   |
| 64.01-256.0 | 3         | 2.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 38        | 25.5%   |
| 1.01-2.0   | 34        | 22.82%  |
| 4.01-8.0   | 33        | 22.15%  |
| 3.01-4.0   | 20        | 13.42%  |
| 0.51-1.0   | 15        | 10.07%  |
| 8.01-16.0  | 6         | 4.03%   |
| 0.01-0.5   | 2         | 1.34%   |
| 16.01-24.0 | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 78.2%   |
| 2      | 26        | 19.55%  |
| 3      | 3         | 2.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 71.97%  |
| Yes       | 37        | 28.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 78.03%  |
| No        | 29        | 21.97%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 98.48%  |
| No        | 2         | 1.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 81.34%  |
| No        | 25        | 18.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 26        | 19.55%  |
| Russia      | 15        | 11.28%  |
| India       | 7         | 5.26%   |
| Brazil      | 7         | 5.26%   |
| UK          | 5         | 3.76%   |
| Turkey      | 5         | 3.76%   |
| Germany     | 5         | 3.76%   |
| France      | 5         | 3.76%   |
| Indonesia   | 4         | 3.01%   |
| Canada      | 4         | 3.01%   |
| Ukraine     | 3         | 2.26%   |
| Spain       | 3         | 2.26%   |
| Romania     | 3         | 2.26%   |
| Poland      | 3         | 2.26%   |
| Netherlands | 3         | 2.26%   |
| Italy       | 3         | 2.26%   |
| Switzerland | 2         | 1.5%    |
| Portugal    | 2         | 1.5%    |
| Pakistan    | 2         | 1.5%    |
| Czechia     | 2         | 1.5%    |
| Bulgaria    | 2         | 1.5%    |
| Bangladesh  | 2         | 1.5%    |
| Argentina   | 2         | 1.5%    |
| Vietnam     | 1         | 0.75%   |
| Uzbekistan  | 1         | 0.75%   |
| Sweden      | 1         | 0.75%   |
| Peru        | 1         | 0.75%   |
| Lithuania   | 1         | 0.75%   |
| Japan       | 1         | 0.75%   |
| Israel      | 1         | 0.75%   |
| Iran        | 1         | 0.75%   |
| Guatemala   | 1         | 0.75%   |
| Greece      | 1         | 0.75%   |
| Finland     | 1         | 0.75%   |
| Colombia    | 1         | 0.75%   |
| China       | 1         | 0.75%   |
| Chile       | 1         | 0.75%   |
| Belarus     | 1         | 0.75%   |
| Azerbaijan  | 1         | 0.75%   |
| Australia   | 1         | 0.75%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| St Petersburg      | 3         | 2.14%   |
| Paris              | 3         | 2.14%   |
| Jakarta            | 3         | 2.14%   |
| Sorocaba           | 2         | 1.43%   |
| San Ramon          | 2         | 1.43%   |
| Samara             | 2         | 1.43%   |
| Rio de Janeiro     | 2         | 1.43%   |
| Prague             | 2         | 1.43%   |
| Omaha              | 2         | 1.43%   |
| Neuchatel          | 2         | 1.43%   |
| Moscow             | 2         | 1.43%   |
| Mira               | 2         | 1.43%   |
| Milton             | 2         | 1.43%   |
| Los Angeles        | 2         | 1.43%   |
| Frankfurt am Main  | 2         | 1.43%   |
| Dnipro             | 2         | 1.43%   |
| Ankara             | 2         | 1.43%   |
| Amsterdam          | 2         | 1.43%   |
| Zaporizhzhya       | 1         | 0.71%   |
| Woodbridge         | 1         | 0.71%   |
| Wigan              | 1         | 0.71%   |
| Wem                | 1         | 0.71%   |
| Vilnius            | 1         | 0.71%   |
| Vichy              | 1         | 0.71%   |
| Varna              | 1         | 0.71%   |
| Vancouver          | 1         | 0.71%   |
| Toronto            | 1         | 0.71%   |
| Tokyo              | 1         | 0.71%   |
| Timișoara         | 1         | 0.71%   |
| Tel Aviv           | 1         | 0.71%   |
| Tejgaon            | 1         | 0.71%   |
| Taunsa             | 1         | 0.71%   |
| Tashkent           | 1         | 0.71%   |
| Tampere            | 1         | 0.71%   |
| Syeverodonets'k    | 1         | 0.71%   |
| Surgut             | 1         | 0.71%   |
| Sun Prairie        | 1         | 0.71%   |
| Stuttgart          | 1         | 0.71%   |
| Stockholm          | 1         | 0.71%   |
| Soriano nel Cimino | 1         | 0.71%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 31        | 40     | 19.02%  |
| Seagate                      | 18        | 18     | 11.04%  |
| WDC                          | 15        | 18     | 9.2%    |
| Toshiba                      | 13        | 13     | 7.98%   |
| SanDisk                      | 9         | 9      | 5.52%   |
| Kingston                     | 7         | 8      | 4.29%   |
| Intel                        | 7         | 9      | 4.29%   |
| HGST                         | 7         | 7      | 4.29%   |
| SK hynix                     | 5         | 11     | 3.07%   |
| Phison Electronics           | 5         | 8      | 3.07%   |
| Hitachi                      | 5         | 6      | 3.07%   |
| Crucial                      | 4         | 6      | 2.45%   |
| China                        | 4         | 4      | 2.45%   |
| Unknown                      | 3         | 3      | 1.84%   |
| Micron Technology            | 3         | 3      | 1.84%   |
| Apple                        | 3         | 4      | 1.84%   |
| WALRAM                       | 2         | 2      | 1.23%   |
| A-DATA Technology            | 2         | 2      | 1.23%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.61%   |
| Timetec                      | 1         | 2      | 0.61%   |
| SPCC                         | 1         | 1      | 0.61%   |
| Solid State Storage          | 1         | 1      | 0.61%   |
| Silicon Motion               | 1         | 1      | 0.61%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.61%   |
| PNY                          | 1         | 1      | 0.61%   |
| Phison                       | 1         | 1      | 0.61%   |
| Patriot                      | 1         | 1      | 0.61%   |
| Micron/Crucial Technology    | 1         | 1      | 0.61%   |
| LITEON                       | 1         | 1      | 0.61%   |
| Lite-On                      | 1         | 1      | 0.61%   |
| Linux                        | 1         | 1      | 0.61%   |
| Lenovo                       | 1         | 1      | 0.61%   |
| LDLC                         | 1         | 5      | 0.61%   |
| JMicron Technology           | 1         | 1      | 0.61%   |
| Intenso                      | 1         | 1      | 0.61%   |
| Hewlett-Packard              | 1         | 1      | 0.61%   |
| AGI                          | 1         | 1      | 0.61%   |
| Unknown                      | 1         | 1      | 0.61%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 5         | 2.92%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 2.34%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 1.75%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.75%   |
| Phison E12 NVMe Controller 2TB                      | 3         | 1.75%   |
| China SATA SSD 960GB                                | 3         | 1.75%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.17%   |
| WALRAM 240G                                         | 2         | 1.17%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.17%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.17%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                | 2         | 1.17%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 1.17%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 1.17%   |
| Phison PCIe SSD 2TB                                 | 2         | 1.17%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                 | 2         | 1.17%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 1.17%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.17%   |
| HGST HTS545050A7E680 500GB                          | 2         | 1.17%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.17%   |
| Apple SSD SM0256G 256GB                             | 2         | 1.17%   |
| WDC WDS500G2B0A 500GB SSD                           | 1         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.58%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                      | 1         | 0.58%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.58%   |
| WDC WD5000LPVX-55V0TT0 500GB                        | 1         | 0.58%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 0.58%   |
| WDC WD50 00LPVX-75V0TT0 500GB                       | 1         | 0.58%   |
| WDC WD3200LPVT-00FMCT0 320GB                        | 1         | 0.58%   |
| WDC WD3200BEKT-60F3T1 320GB                         | 1         | 0.58%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.58%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.58%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.58%   |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 0.58%   |
| Unknown MMC Card  128GB                             | 1         | 0.58%   |
| Unknown DA4064  64GB                                | 1         | 0.58%   |
| Union Memory (Shenzhen) UMIS RPEYJ512VMM2QWY 512GB  | 1         | 0.58%   |
| Toshiba THNSNH128GMCT 128GB SSD                     | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 18     | 33.33%  |
| WDC     | 12        | 14     | 22.22%  |
| Toshiba | 11        | 11     | 20.37%  |
| HGST    | 7         | 7      | 12.96%  |
| Hitachi | 5         | 6      | 9.26%   |
| Unknown | 1         | 1      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 25.58%  |
| Kingston            | 4         | 4      | 9.3%    |
| Crucial             | 4         | 6      | 9.3%    |
| China               | 4         | 4      | 9.3%    |
| WDC                 | 3         | 4      | 6.98%   |
| Apple               | 3         | 4      | 6.98%   |
| Micron Technology   | 2         | 2      | 4.65%   |
| Toshiba             | 1         | 1      | 2.33%   |
| SPCC                | 1         | 1      | 2.33%   |
| SK hynix            | 1         | 1      | 2.33%   |
| SanDisk             | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| Patriot             | 1         | 1      | 2.33%   |
| Linux               | 1         | 1      | 2.33%   |
| LDLC                | 1         | 5      | 2.33%   |
| Intenso             | 1         | 1      | 2.33%   |
| Intel               | 1         | 1      | 2.33%   |
| Hewlett-Packard     | 1         | 1      | 2.33%   |
| AGI                 | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 53        | 79     | 34.42%  |
| HDD     | 53        | 57     | 34.42%  |
| SSD     | 41        | 52     | 26.62%  |
| Unknown | 5         | 6      | 3.25%   |
| MMC     | 2         | 2      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 89        | 111    | 60.54%  |
| NVMe | 53        | 79     | 36.05%  |
| SAS  | 3         | 4      | 2.04%   |
| MMC  | 2         | 2      | 1.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 67     | 61.96%  |
| 0.51-1.0   | 31        | 37     | 33.7%   |
| 1.01-2.0   | 3         | 4      | 3.26%   |
| 4.01-10.0  | 1         | 1      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 40        | 29.2%   |
| 101-250        | 35        | 25.55%  |
| 501-1000       | 19        | 13.87%  |
| 1001-2000      | 15        | 10.95%  |
| Unknown        | 8         | 5.84%   |
| 51-100         | 6         | 4.38%   |
| 1-20           | 5         | 3.65%   |
| More than 3000 | 4         | 2.92%   |
| 21-50          | 3         | 2.19%   |
| 2001-3000      | 2         | 1.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 40        | 27.4%   |
| 101-250        | 28        | 19.18%  |
| 51-100         | 19        | 13.01%  |
| 21-50          | 17        | 11.64%  |
| 251-500        | 15        | 10.27%  |
| 501-1000       | 11        | 7.53%   |
| Unknown        | 8         | 5.48%   |
| 1001-2000      | 6         | 4.11%   |
| More than 3000 | 1         | 0.68%   |
| 2001-3000      | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 10.53%  |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 10.53%  |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 5.26%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 5.26%   |
| WDC WD3200BEKT-60F3T1 320GB                      | 1         | 1      | 5.26%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 5.26%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 5.26%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.26%   |
| LDLC SSD 120GB                                   | 1         | 3      | 5.26%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 5.26%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 5.26%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 26.32%  |
| WDC                 | 4         | 4      | 21.05%  |
| Seagate             | 3         | 3      | 15.79%  |
| HGST                | 3         | 3      | 15.79%  |
| Hitachi             | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| LDLC                | 1         | 3      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 5      | 29.41%  |
| WDC     | 4         | 4      | 23.53%  |
| Seagate | 3         | 3      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Hitachi | 2         | 2      | 11.76%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 17     | 89.47%  |
| SSD  | 2         | 4      | 10.53%  |

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
| Works    | 72        | 94     | 50.7%   |
| Detected | 51        | 81     | 35.92%  |
| Malfunc  | 19        | 21     | 13.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 85        | 52.8%   |
| Samsung Electronics            | 22        | 13.66%  |
| AMD                            | 20        | 12.42%  |
| SanDisk                        | 8         | 4.97%   |
| Phison Electronics             | 5         | 3.11%   |
| SK hynix                       | 4         | 2.48%   |
| Kingston Technology Company    | 3         | 1.86%   |
| Union Memory (Shenzhen)        | 2         | 1.24%   |
| ADATA Technology               | 2         | 1.24%   |
| Toshiba America Info Systems   | 1         | 0.62%   |
| Solid State Storage Technology | 1         | 0.62%   |
| Silicon Motion                 | 1         | 0.62%   |
| Shenzhen Longsys Electronics   | 1         | 0.62%   |
| Nvidia                         | 1         | 0.62%   |
| Micron/Crucial Technology      | 1         | 0.62%   |
| Micron Technology              | 1         | 0.62%   |
| Marvell Technology Group       | 1         | 0.62%   |
| Lite-On Technology             | 1         | 0.62%   |
| Lenovo                         | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 18        | 10.78%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 14        | 8.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 11        | 6.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 11        | 6.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 10        | 5.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 8         | 4.79%   |
| Samsung NVMe SSD Controller 980                                              | 6         | 3.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 4         | 2.4%    |
| Phison E12 NVMe Controller                                                   | 4         | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 4         | 2.4%    |
| Intel Volume Management Device NVMe RAID Controller                          | 4         | 2.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 4         | 2.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 4         | 2.4%    |
| SK hynix PC611 NVMe Solid State Drive                                        | 3         | 1.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 3         | 1.8%    |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 3         | 1.8%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                             | 3         | 1.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 3         | 1.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 3         | 1.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 3         | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                               | 2         | 1.2%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                        | 2         | 1.2%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 2         | 1.2%    |
| Intel SSD 660P Series                                                        | 2         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.2%    |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                        | 1         | 0.6%    |
| Union Memory (Shenzhen) AH631 PCIe 3.0 NVMe SSD 512GB                        | 1         | 0.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.6%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 0.6%    |
| SK hynix BC511 NVMe SSD                                                      | 1         | 0.6%    |
| Silicon Motion Non-Volatile memory controller                                | 1         | 0.6%    |
| Shenzhen Longsys Non-Volatile memory controller                              | 1         | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                             | 1         | 0.6%    |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.6%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 1         | 0.6%    |
| Micron 2210 NVMe SSD [Cobain]                                                | 1         | 0.6%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                   | 1         | 0.6%    |
| Lite-On Non-Volatile memory controller                                       | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 58.64%  |
| NVMe | 54        | 33.33%  |
| RAID | 12        | 7.41%   |
| IDE  | 1         | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 104       | 78.79%  |
| AMD    | 28        | 21.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 3.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.26%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 1.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.5%    |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 1.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.5%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.5%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.5%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.5%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 1.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.5%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.5%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.5%    |
| AMD Athlon Gold 3150U with Radeon Graphics    | 2         | 1.5%    |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.75%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.75%   |
| Intel Pentium CPU B970 @ 2.30GHz              | 1         | 0.75%   |
| Intel Pentium CPU A1018 @ 2.10GHz             | 1         | 0.75%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.75%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.75%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.75%   |
| Intel Core i7-9750HF CPU @ 2.60GHz            | 1         | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 26.52%  |
| Intel Core i7           | 28        | 21.21%  |
| Intel Core i3           | 11        | 8.33%   |
| AMD Ryzen 7             | 10        | 7.58%   |
| Other                   | 9         | 6.82%   |
| Intel Celeron           | 8         | 6.06%   |
| AMD Ryzen 5             | 6         | 4.55%   |
| Intel Pentium           | 4         | 3.03%   |
| AMD Ryzen 3             | 3         | 2.27%   |
| Intel Core m3           | 2         | 1.52%   |
| Intel Core i9           | 2         | 1.52%   |
| AMD Athlon              | 2         | 1.52%   |
| Intel Xeon              | 1         | 0.76%   |
| Intel Pentium Silver    | 1         | 0.76%   |
| Intel Pentium Dual-Core | 1         | 0.76%   |
| Intel Core 2 Duo        | 1         | 0.76%   |
| Intel Atom              | 1         | 0.76%   |
| AMD Ryzen 9             | 1         | 0.76%   |
| AMD Ryzen 7 PRO         | 1         | 0.76%   |
| AMD Ryzen 5 PRO         | 1         | 0.76%   |
| AMD Phenom II           | 1         | 0.76%   |
| AMD E1                  | 1         | 0.76%   |
| AMD A6                  | 1         | 0.76%   |
| AMD A10                 | 1         | 0.76%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 44.7%   |
| 4      | 46        | 34.85%  |
| 8      | 12        | 9.09%   |
| 6      | 12        | 9.09%   |
| 14     | 1         | 0.76%   |
| 12     | 1         | 0.76%   |
| 10     | 1         | 0.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 80.3%   |
| 1      | 26        | 19.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 132       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 24.44%  |
| 0x306a9    | 10        | 7.41%   |
| 0x206a7    | 9         | 6.67%   |
| 0xa0652    | 6         | 4.44%   |
| 0x806ec    | 5         | 3.7%    |
| 0x806e9    | 5         | 3.7%    |
| 0x40651    | 5         | 3.7%    |
| 0x306d4    | 5         | 3.7%    |
| 0x08600106 | 5         | 3.7%    |
| 0x806ea    | 4         | 2.96%   |
| 0x806c1    | 4         | 2.96%   |
| 0x706e5    | 4         | 2.96%   |
| 0x906ea    | 3         | 2.22%   |
| 0x906e9    | 3         | 2.22%   |
| 0x706a1    | 3         | 2.22%   |
| 0x08108109 | 3         | 2.22%   |
| 0x30678    | 2         | 1.48%   |
| 0x1067a    | 2         | 1.48%   |
| 0x08600103 | 2         | 1.48%   |
| 0x08108102 | 2         | 1.48%   |
| 0x08101007 | 2         | 1.48%   |
| 0x906ed    | 1         | 0.74%   |
| 0x806eb    | 1         | 0.74%   |
| 0x806d1    | 1         | 0.74%   |
| 0x806c2    | 1         | 0.74%   |
| 0x506e3    | 1         | 0.74%   |
| 0x506c9    | 1         | 0.74%   |
| 0x406e3    | 1         | 0.74%   |
| 0x306c3    | 1         | 0.74%   |
| 0x20655    | 1         | 0.74%   |
| 0x0a50000c | 1         | 0.74%   |
| 0x08701013 | 1         | 0.74%   |
| 0x08608103 | 1         | 0.74%   |
| 0x08600104 | 1         | 0.74%   |
| 0x0810100b | 1         | 0.74%   |
| 0x08001137 | 1         | 0.74%   |
| 0x0700010b | 1         | 0.74%   |
| 0x06003109 | 1         | 0.74%   |
| 0x010000c8 | 1         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 22.73%  |
| IvyBridge        | 15        | 11.36%  |
| SandyBridge      | 12        | 9.09%   |
| Zen 2            | 10        | 7.58%   |
| Haswell          | 7         | 5.3%    |
| CometLake        | 7         | 5.3%    |
| Zen+             | 6         | 4.55%   |
| TigerLake        | 6         | 4.55%   |
| Broadwell        | 6         | 4.55%   |
| Unknown          | 5         | 3.79%   |
| Zen              | 4         | 3.03%   |
| Silvermont       | 4         | 3.03%   |
| IceLake          | 4         | 3.03%   |
| Goldmont plus    | 3         | 2.27%   |
| Skylake          | 2         | 1.52%   |
| Penryn           | 2         | 1.52%   |
| Zen 3            | 1         | 0.76%   |
| Westmere         | 1         | 0.76%   |
| Steamroller      | 1         | 0.76%   |
| Puma             | 1         | 0.76%   |
| K10              | 1         | 0.76%   |
| Jaguar           | 1         | 0.76%   |
| Goldmont         | 1         | 0.76%   |
| Bonnell          | 1         | 0.76%   |
| Alderlake Hybrid | 1         | 0.76%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 97        | 59.15%  |
| Nvidia | 34        | 20.73%  |
| AMD    | 33        | 20.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 13        | 7.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 10        | 6.02%   |
| AMD Renoir                                                                | 8         | 4.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 7         | 4.22%   |
| Intel UHD Graphics 620                                                    | 6         | 3.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 3.61%   |
| Intel HD Graphics 620                                                     | 6         | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 3.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 6         | 3.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 4         | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.41%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.41%   |
| Intel HD Graphics 5500                                                    | 4         | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 2.41%   |
| Nvidia TU117M                                                             | 3         | 1.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 1.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.81%   |
| AMD Lucienne                                                              | 3         | 1.81%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.2%    |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.2%    |
| Intel UHD Graphics 615                                                    | 2         | 1.2%    |
| Intel HD Graphics 630                                                     | 2         | 1.2%    |
| Intel HD Graphics 6000                                                    | 2         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.2%    |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.2%    |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.6%    |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.6%    |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.6%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.6%    |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.6%    |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.6%    |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.6%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.6%    |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.6%    |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 49.62%  |
| Intel + Nvidia | 27        | 20.3%   |
| 1 x AMD        | 27        | 20.3%   |
| 1 x Nvidia     | 6         | 4.51%   |
| Intel + AMD    | 4         | 3.01%   |
| 2 x AMD        | 2         | 1.5%    |
| AMD + Nvidia   | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 111       | 84.09%  |
| Proprietary | 20        | 15.15%  |
| Unknown     | 1         | 0.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 66.92%  |
| 1.01-2.0   | 15        | 11.28%  |
| 0.01-0.5   | 12        | 9.02%   |
| 0.51-1.0   | 6         | 4.51%   |
| 3.01-4.0   | 5         | 3.76%   |
| 5.01-6.0   | 3         | 2.26%   |
| 7.01-8.0   | 2         | 1.5%    |
| 2.01-3.0   | 1         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 19.08%  |
| BOE                     | 24        | 15.79%  |
| LG Display              | 22        | 14.47%  |
| Chimei Innolux          | 20        | 13.16%  |
| Samsung Electronics     | 11        | 7.24%   |
| Chi Mei Optoelectronics | 5         | 3.29%   |
| Goldstar                | 4         | 2.63%   |
| Dell                    | 4         | 2.63%   |
| PANDA                   | 3         | 1.97%   |
| InfoVision              | 3         | 1.97%   |
| ASUSTek Computer        | 3         | 1.97%   |
| Apple                   | 3         | 1.97%   |
| Sharp                   | 2         | 1.32%   |
| Lenovo                  | 2         | 1.32%   |
| Hewlett-Packard         | 2         | 1.32%   |
| BenQ                    | 2         | 1.32%   |
| ViewSonic               | 1         | 0.66%   |
| Sony                    | 1         | 0.66%   |
| Philips                 | 1         | 0.66%   |
| MSI                     | 1         | 0.66%   |
| LGD                     | 1         | 0.66%   |
| KDC                     | 1         | 0.66%   |
| HUAWEI                  | 1         | 0.66%   |
| HKC                     | 1         | 0.66%   |
| CSO                     | 1         | 0.66%   |
| Aosiman                 | 1         | 0.66%   |
| AOC                     | 1         | 0.66%   |
| Ancor Communications    | 1         | 0.66%   |
| Acer                    | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 4         | 2.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.97%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 3         | 1.97%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 1.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.32%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.32%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.32%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.32%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                      | 2         | 1.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 1.32%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.32%   |
| ViewSonic VA2256 Series VSC3136 1920x1080 476x268mm 21.5-inch             | 1         | 0.66%   |
| Sony BW8 MS_9001 2560x1600                                                | 1         | 0.66%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.66%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.66%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.66%   |
| Samsung Electronics SMB1630N SAM0630 1360x768 344x194mm 15.5-inch         | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.66%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.66%   |
| PANDA LCD Monitor NCP0054 1920x1080 344x194mm 15.5-inch                   | 1         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.66%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.66%   |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                    | 1         | 0.66%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.66%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.66%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 1         | 0.66%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 45.52%  |
| 1366x768 (WXGA)    | 51        | 35.17%  |
| 1600x900 (HD+)     | 6         | 4.14%   |
| 3840x2160 (4K)     | 5         | 3.45%   |
| 2560x1600          | 4         | 2.76%   |
| 2560x1440 (QHD)    | 4         | 2.76%   |
| 1440x900 (WXGA+)   | 4         | 2.76%   |
| 3440x1440          | 1         | 0.69%   |
| 3072x1920          | 1         | 0.69%   |
| 2160x1440          | 1         | 0.69%   |
| 1920x1200 (WUXGA)  | 1         | 0.69%   |
| 1680x1050 (WSXGA+) | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 67        | 44.37%  |
| 14      | 22        | 14.57%  |
| 13      | 20        | 13.25%  |
| 17      | 9         | 5.96%   |
| 21      | 8         | 5.3%    |
| 27      | 6         | 3.97%   |
| 24      | 5         | 3.31%   |
| 16      | 3         | 1.99%   |
| 23      | 2         | 1.32%   |
| 11      | 2         | 1.32%   |
| 34      | 1         | 0.66%   |
| 28      | 1         | 0.66%   |
| 20      | 1         | 0.66%   |
| 19      | 1         | 0.66%   |
| 12      | 1         | 0.66%   |
| 8       | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 66.89%  |
| 351-400     | 14        | 9.27%   |
| 501-600     | 11        | 7.28%   |
| 401-500     | 10        | 6.62%   |
| 201-300     | 9         | 5.96%   |
| 601-700     | 3         | 1.99%   |
| 701-800     | 1         | 0.66%   |
| 101-200     | 1         | 0.66%   |
| Unknown     | 1         | 0.66%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 117       | 89.31%  |
| 16/10   | 10        | 7.63%   |
| 3/2     | 1         | 0.76%   |
| 21/9    | 1         | 0.76%   |
| 0.62    | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 68        | 45.03%  |
| 81-90          | 36        | 23.84%  |
| 201-250        | 13        | 8.61%   |
| 121-130        | 8         | 5.3%    |
| 71-80          | 6         | 3.97%   |
| 301-350        | 6         | 3.97%   |
| 151-200        | 3         | 1.99%   |
| 51-60          | 2         | 1.32%   |
| 351-500        | 2         | 1.32%   |
| 111-120        | 2         | 1.32%   |
| 61-70          | 1         | 0.66%   |
| 1-40           | 1         | 0.66%   |
| 251-300        | 1         | 0.66%   |
| 131-140        | 1         | 0.66%   |
| Unknown        | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 66        | 45.83%  |
| 101-120       | 48        | 33.33%  |
| 51-100        | 20        | 13.89%  |
| 161-240       | 7         | 4.86%   |
| More than 240 | 2         | 1.39%   |
| Unknown       | 1         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 110       | 81.48%  |
| 2     | 24        | 17.78%  |
| 0     | 1         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 83        | 38.79%  |
| Intel                    | 72        | 33.64%  |
| Qualcomm Atheros         | 23        | 10.75%  |
| Broadcom                 | 12        | 5.61%   |
| Broadcom Limited         | 4         | 1.87%   |
| MediaTek                 | 3         | 1.4%    |
| Samsung Electronics      | 2         | 0.93%   |
| Ralink                   | 2         | 0.93%   |
| Qualcomm                 | 2         | 0.93%   |
| Xiaomi                   | 1         | 0.47%   |
| TP-Link                  | 1         | 0.47%   |
| Sierra Wireless          | 1         | 0.47%   |
| Ralink Technology        | 1         | 0.47%   |
| OPPO Electronics         | 1         | 0.47%   |
| Marvell Technology Group | 1         | 0.47%   |
| Linksys                  | 1         | 0.47%   |
| Lenovo                   | 1         | 0.47%   |
| Huawei Technologies      | 1         | 0.47%   |
| ASIX Electronics         | 1         | 0.47%   |
| Apple                    | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 20.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 6.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 4.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 3.15%   |
| Intel Wireless 8265 / 8275                                        | 8         | 3.15%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 3.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.36%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 2.36%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.57%   |
| Intel Wireless 7265                                               | 4         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.18%   |
| Intel Wireless 7260                                               | 3         | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.18%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.18%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.18%   |
| Realtek 802.11ac NIC                                              | 2         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.79%   |
| Intel Wireless 3165                                               | 2         | 0.79%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.79%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.39%   |
| Sierra Wireless MC7710                                            | 1         | 0.39%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 49.64%  |
| Realtek Semiconductor | 25        | 18.25%  |
| Qualcomm Atheros      | 20        | 14.6%   |
| Broadcom              | 11        | 8.03%   |
| Broadcom Limited      | 4         | 2.92%   |
| MediaTek              | 3         | 2.19%   |
| Ralink                | 2         | 1.46%   |
| TP-Link               | 1         | 0.73%   |
| Sierra Wireless       | 1         | 0.73%   |
| Ralink Technology     | 1         | 0.73%   |
| Qualcomm              | 1         | 0.73%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.76%   |
| Intel Wireless 8265 / 8275                                     | 8         | 5.76%   |
| Intel Wi-Fi 6 AX200                                            | 8         | 5.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 5.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 5.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 4.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 4.32%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 3.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 3.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.88%   |
| Intel Wireless 7265                                            | 4         | 2.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.16%   |
| Intel Wireless 7260                                            | 3         | 2.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 2.16%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 2.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.16%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.16%   |
| Realtek 802.11ac NIC                                           | 2         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.44%   |
| Intel Wireless 3165                                            | 2         | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.44%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.72%   |
| Sierra Wireless MC7710                                         | 1         | 0.72%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                 | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.72%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.72%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.72%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 74        | 66.07%  |
| Intel                    | 22        | 19.64%  |
| Qualcomm Atheros         | 5         | 4.46%   |
| Xiaomi                   | 1         | 0.89%   |
| Samsung Electronics      | 1         | 0.89%   |
| Qualcomm                 | 1         | 0.89%   |
| OPPO Electronics         | 1         | 0.89%   |
| Marvell Technology Group | 1         | 0.89%   |
| Linksys                  | 1         | 0.89%   |
| Lenovo                   | 1         | 0.89%   |
| Huawei Technologies      | 1         | 0.89%   |
| Broadcom                 | 1         | 0.89%   |
| ASIX Electronics         | 1         | 0.89%   |
| Apple                    | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 45.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 14.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 9.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.63%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.88%   |
| Qualcomm A0001                                                    | 1         | 0.88%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.88%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.88%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.88%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.88%   |
| Huawei E353/E3131                                                 | 1         | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.88%   |
| ASIX AX88772                                                      | 1         | 0.88%   |
| Apple iPad 4/Mini1                                                | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 55.56%  |
| Ethernet | 103       | 44.02%  |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 79.29%  |
| Ethernet | 29        | 20.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 94        | 70.68%  |
| 1     | 36        | 27.07%  |
| 3     | 2         | 1.5%    |
| 0     | 1         | 0.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 80.88%  |
| Yes  | 26        | 19.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 50%     |
| Realtek Semiconductor           | 19        | 17.27%  |
| Broadcom                        | 10        | 9.09%   |
| Qualcomm Atheros Communications | 6         | 5.45%   |
| Lite-On Technology              | 4         | 3.64%   |
| IMC Networks                    | 3         | 2.73%   |
| Foxconn / Hon Hai               | 3         | 2.73%   |
| Apple                           | 3         | 2.73%   |
| Realtek                         | 2         | 1.82%   |
| Cambridge Silicon Radio         | 2         | 1.82%   |
| Ralink                          | 1         | 0.91%   |
| MediaTek                        | 1         | 0.91%   |
| ASUSTek Computer                | 1         | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 14.41%  |
| Intel AX201 Bluetooth                               | 15        | 13.51%  |
| Realtek Bluetooth Radio                             | 12        | 10.81%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 7.21%   |
| Intel AX200 Bluetooth                               | 8         | 7.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.6%    |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 3.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.7%    |
| Realtek Bluetooth Radio                             | 2         | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.8%    |
| IMC Networks Wireless_Device                        | 2         | 1.8%    |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 1.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.8%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.8%    |
| Apple Bluetooth USB Host Controller                 | 2         | 1.8%    |
| Realtek RTL8821A Bluetooth                          | 1         | 0.9%    |
| Realtek RTL8723B Bluetooth                          | 1         | 0.9%    |
| Realtek Bluetooth 5.1 Radio                         | 1         | 0.9%    |
| Ralink RT3290 Bluetooth                             | 1         | 0.9%    |
| MediaTek Wireless_Device                            | 1         | 0.9%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.9%    |
| Intel Bluetooth Device                              | 1         | 0.9%    |
| Intel AX210 Bluetooth                               | 1         | 0.9%    |
| IMC Networks Bluetooth Device                       | 1         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.9%    |
| Broadcom HP Portable Valentine                      | 1         | 0.9%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.9%    |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.9%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.9%    |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.9%    |
| Apple Bluetooth Host Controller                     | 1         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 103       | 60.95%  |
| AMD                   | 30        | 17.75%  |
| Nvidia                | 21        | 12.43%  |
| Realtek Semiconductor | 3         | 1.78%   |
| C-Media Electronics   | 3         | 1.78%   |
| Texas Instruments     | 1         | 0.59%   |
| Plantronics           | 1         | 0.59%   |
| Lenovo                | 1         | 0.59%   |
| Harman                | 1         | 0.59%   |
| GN Netcom             | 1         | 0.59%   |
| DSEA A/S              | 1         | 0.59%   |
| Corsair               | 1         | 0.59%   |
| ASUSTek Computer      | 1         | 0.59%   |
| Arylic                | 1         | 0.59%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 21        | 10.05%  |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 7.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 7.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 5.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 5.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 4.31%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 3.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 2.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.87%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.87%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 2.87%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.91%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.91%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.44%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.44%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.96%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.96%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.96%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.48%   |
| Realtek Semiconductor TX-384Khz Hifi Type-C Audio                          | 1         | 0.48%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.48%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.48%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.48%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.48%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.48%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 29.37%  |
| SK hynix            | 33        | 23.08%  |
| Kingston            | 15        | 10.49%  |
| Micron Technology   | 13        | 9.09%   |
| Unknown             | 6         | 4.2%    |
| A-DATA Technology   | 4         | 2.8%    |
| Unknown             | 4         | 2.8%    |
| Smart               | 3         | 2.1%    |
| Silicon Power       | 3         | 2.1%    |
| Ramaxel Technology  | 3         | 2.1%    |
| Nanya Technology    | 3         | 2.1%    |
| Crucial             | 3         | 2.1%    |
| Unknown (ABCD)      | 2         | 1.4%    |
| Team                | 2         | 1.4%    |
| Corsair             | 2         | 1.4%    |
| Smart Brazil        | 1         | 0.7%    |
| Patriot             | 1         | 0.7%    |
| Elpida              | 1         | 0.7%    |
| ASint Technology    | 1         | 0.7%    |
| AMD                 | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 3.36%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 2.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 2.68%   |
| Unknown                                                          | 4         | 2.68%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.01%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 2.01%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.34%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.34%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.34%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.34%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.34%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.34%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.34%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.67%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.67%   |
| Unknown RAM DDR4 NB 16G 16GB SODIMM DDR4 2667MT/s                | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.67%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.67%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.67%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s     | 1         | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.67%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 51.33%  |
| DDR3    | 43        | 38.05%  |
| LPDDR4  | 4         | 3.54%   |
| LPDDR3  | 4         | 3.54%   |
| SDRAM   | 2         | 1.77%   |
| DDR5    | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 86.84%  |
| Row Of Chips | 12        | 10.53%  |
| DIMM         | 1         | 0.88%   |
| Chip         | 1         | 0.88%   |
| Unknown      | 1         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 49        | 37.69%  |
| 8192  | 45        | 34.62%  |
| 16384 | 19        | 14.62%  |
| 2048  | 11        | 8.46%   |
| 32768 | 5         | 3.85%   |
| 1024  | 1         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 38        | 30.89%  |
| 3200  | 27        | 21.95%  |
| 2667  | 23        | 18.7%   |
| 2400  | 12        | 9.76%   |
| 1333  | 6         | 4.88%   |
| 1334  | 4         | 3.25%   |
| 2133  | 3         | 2.44%   |
| 4199  | 2         | 1.63%   |
| 3266  | 2         | 1.63%   |
| 4800  | 1         | 0.81%   |
| 4267  | 1         | 0.81%   |
| 3400  | 1         | 0.81%   |
| 1067  | 1         | 0.81%   |
| 1066  | 1         | 0.81%   |
| 800   | 1         | 0.81%   |

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
| Chicony Electronics                    | 28        | 24.14%  |
| IMC Networks                           | 13        | 11.21%  |
| Quanta                                 | 11        | 9.48%   |
| Realtek Semiconductor                  | 10        | 8.62%   |
| Bison Electronics                      | 9         | 7.76%   |
| Microdia                               | 7         | 6.03%   |
| Suyin                                  | 6         | 5.17%   |
| Alcor Micro                            | 5         | 4.31%   |
| Syntek                                 | 4         | 3.45%   |
| Silicon Motion                         | 4         | 3.45%   |
| Luxvisions Innotech Limited            | 4         | 3.45%   |
| Sunplus Innovation Technology          | 3         | 2.59%   |
| Sonix Technology                       | 3         | 2.59%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.59%   |
| Acer                                   | 3         | 2.59%   |
| Lite-On Technology                     | 1         | 0.86%   |
| LG Electronics                         | 1         | 0.86%   |
| Lenovo                                 | 1         | 0.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                       | 7         | 6.03%   |
| Chicony HD WebCam                                    | 6         | 5.17%   |
| Chicony integrated camera                            | 5         | 4.31%   |
| Realtek Integrated_Webcam_HD                         | 4         | 3.45%   |
| Bison Integrated Camera                              | 4         | 3.45%   |
| Syntek EasyCamera                                    | 3         | 2.59%   |
| Sonix USB2.0 HD UVC WebCam                           | 3         | 2.59%   |
| Quanta HP TrueVision HD Camera                       | 3         | 2.59%   |
| Microdia Integrated Webcam                           | 3         | 2.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 2.59%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 2.59%   |
| Suyin HP Webcam                                      | 2         | 1.72%   |
| Silicon Motion 300k Pixel Camera                     | 2         | 1.72%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 1.72%   |
| Realtek HD WebCam                                    | 2         | 1.72%   |
| Quanta VGA WebCam                                    | 2         | 1.72%   |
| Quanta HP Webcam                                     | 2         | 1.72%   |
| Quanta HD Webcam                                     | 2         | 1.72%   |
| Microdia Integrated_Webcam_HD                        | 2         | 1.72%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.72%   |
| Chicony USB2.0 Camera                                | 2         | 1.72%   |
| Chicony thinkpad t430s camera                        | 2         | 1.72%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.72%   |
| Syntek Integrated Camera                             | 1         | 0.86%   |
| Suyin USB Webcam                                     | 1         | 0.86%   |
| Suyin NEC HD WebCam                                  | 1         | 0.86%   |
| Suyin Laptop_Integrated_Webcam_HD                    | 1         | 0.86%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.86%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.86%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.86%   |
| Sunplus HD WebCam                                    | 1         | 0.86%   |
| Silicon Motion WebCam SCB-0355N                      | 1         | 0.86%   |
| Silicon Motion WebCam SC-10HDD12636N                 | 1         | 0.86%   |
| Realtek Integrated Webcam                            | 1         | 0.86%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.86%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 0.86%   |
| Quanta HD User Facing                                | 1         | 0.86%   |
| Microdia WebCam SC-13HDL12639P                       | 1         | 0.86%   |
| Microdia Integrated_Webcam_FHD                       | 1         | 0.86%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 5         | 41.67%  |
| Validity Sensors           | 3         | 25%     |
| Synaptics                  | 3         | 25%     |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 4         | 33.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 25%     |
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 16.67%  |
| Validity Sensors VFS491                           | 1         | 8.33%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 8.33%   |
| AuthenTec AES2810                                 | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| Alcor Micro | 2         | 25%     |
| Lenovo      | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 25%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Broadcom 58200                                                               | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 89        | 65.93%  |
| 1     | 39        | 28.89%  |
| 2     | 6         | 4.44%   |
| 3     | 1         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 21.82%  |
| Net/wireless             | 7         | 12.73%  |
| Graphics card            | 7         | 12.73%  |
| Chipcard                 | 7         | 12.73%  |
| Multimedia controller    | 6         | 10.91%  |
| Camera                   | 5         | 9.09%   |
| Bluetooth                | 4         | 7.27%   |
| Communication controller | 3         | 5.45%   |
| Storage                  | 2         | 3.64%   |
| Network                  | 1         | 1.82%   |
| Dvb card                 | 1         | 1.82%   |

