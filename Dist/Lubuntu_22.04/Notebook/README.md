Lubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 22.04.

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

Total: 299

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Hampoo        | I2W6_AP135 Reserved         | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| ASUSTek       | K50IJ                       | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| Dixonsxp      | Unknown                     | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| HP            | Compaq Presario CQ40        | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| Acer          | Aspire A314-23P             | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| Insyde        | Braswell                    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| Getac         | X500G3                      | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| HP            | Laptop 14-ck0xxx            | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| ASUSTek       | X451MA                      | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Dell          | Precision 3570              | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| HP            | 15                          | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| HP            | 2000                        | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| HP            | 255 G2                      | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| ASUSTek       | X75VD                       | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| Packard Be... | EasyNote TJ65               | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Compal        | PBL20                       | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| HP            | Pavilion g7                 | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Toshiba       | Satellite L875D             | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron 5720               | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| HP            | Pavilion 15                 | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| Dell          | Inspiron 5576               | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Google        | Pyro                        | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| Dell          | Precision 3570              | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 240 G3                      | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Dell          | Latitude E6430              | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| ASUSTek       | X450CC                      | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| Dell          | XPS 13 9305                 | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| Apple         | MacBook4,1                  | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| HP            | Laptop 15-bs2xx             | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| Dell          | Latitude 5290               | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| GPU Compan... | GWTN116-3                   | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion 15                 | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| HP            | Laptop 17-ak0xx             | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| Dell          | Latitude 5290               | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| Dell          | Latitude 7480               | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| MSI           | S12T 3M/S12 3M              | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Google        | Celes                       | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| HP            | Notebook                    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Acer          | Aspire A515-45              | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Acer          | AO756                       | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| Dell          | Latitude E6410              | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Acer          | Aspire ES1-711              | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Google        | Celes                       | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Google        | Candy                       | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Acer          | Swift SF314-54G             | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| HP            | 2000                        | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| Apple         | MacBookPro8,1               | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| GPU Compan... | GWTC116-2                   | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| Unknown       | Unknown                     | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Toshiba       | Satellite Pro S500          | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| Lenovo        | G50-45 80E3                 | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| Acer          | Aspire E1-571               | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Google        | Apel                        | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Fujitsu       | LIFEBOOK U904               | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Packard Be... | EasyNote TS44HR             | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Gateway       | NE46R                       | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| Dell          | Inspiron 11-3168            | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| HP            | ProBook 4730s               | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Acer          | Aspire 7250G                | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| Dell          | Vostro 3360                 | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| Prestigio     | PSB141C01BFH                | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| Intel         | W7650                       | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| OEM           | Unknown                     | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Dell          | Precision 3510              | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Google        | Celes                       | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Sony          | VPCEB15FM                   | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| HP            | 245 G2                      | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| HP            | 245 G2                      | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| Lenovo        | G50-30 80G0                 | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| Google        | Bobba360                    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Gateway       | Sonic-C                     | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Dell          | Latitude XT                 | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| Intel         | W7650                       | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| Apple         | MacBookPro8,1               | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | Pavilion g6                 | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| HP            | Pavilion g6                 | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Google        | Terra                       | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Intel         | W7650                       | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| Apple         | MacBookPro14,1              | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Apple         | MacBookPro14,1              | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Google        | Bobba360                    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Dell          | Latitude 7480               | [817415642f](https://linux-hardware.org/?probe=817415642f) | Apr 26, 2022 |
| HP            | Pavilion dv4                | [7bd955f313](https://linux-hardware.org/?probe=7bd955f313) | Apr 18, 2022 |
| Apple         | MacBookPro8,1               | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| Intel         | W7650                       | [9144ca0d30](https://linux-hardware.org/?probe=9144ca0d30) | Apr 15, 2022 |
| Intel         | W7650                       | [df2f2041d1](https://linux-hardware.org/?probe=df2f2041d1) | Feb 18, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-43-generic | 23        | 9.54%   |
| 5.15.0-56-generic | 14        | 5.81%   |
| 5.15.0-25-generic | 12        | 4.98%   |
| 6.2.0-34-generic  | 9         | 3.73%   |
| 5.15.0-58-generic | 9         | 3.73%   |
| 5.15.0-60-generic | 8         | 3.32%   |
| 5.15.0-30-generic | 8         | 3.32%   |
| 5.19.0-41-generic | 7         | 2.9%    |
| 5.19.0-32-generic | 7         | 2.9%    |
| 5.15.0-47-generic | 7         | 2.9%    |
| 5.15.0-46-generic | 7         | 2.9%    |
| 6.2.0-26-generic  | 6         | 2.49%   |
| 5.19.0-35-generic | 6         | 2.49%   |
| 5.15.0-52-generic | 6         | 2.49%   |
| 5.15.0-27-generic | 6         | 2.49%   |
| 5.19.0-43-generic | 5         | 2.07%   |
| 5.15.0-53-generic | 5         | 2.07%   |
| 6.2.0-33-generic  | 4         | 1.66%   |
| 5.19.0-46-generic | 4         | 1.66%   |
| 5.19.0-40-generic | 4         | 1.66%   |
| 5.19.0-38-generic | 4         | 1.66%   |
| 5.15.0-73-generic | 4         | 1.66%   |
| 5.15.0-71-generic | 4         | 1.66%   |
| 5.15.0-57-generic | 4         | 1.66%   |
| 5.15.0-50-generic | 4         | 1.66%   |
| 5.15.0-41-generic | 4         | 1.66%   |
| 6.2.0-35-generic  | 3         | 1.24%   |
| 6.2.0-31-generic  | 3         | 1.24%   |
| 5.19.0-42-generic | 3         | 1.24%   |
| 5.15.0-79-generic | 3         | 1.24%   |
| 5.15.0-67-generic | 3         | 1.24%   |
| 5.15.0-48-generic | 3         | 1.24%   |
| 5.15.0-40-generic | 3         | 1.24%   |
| 5.15.0-35-generic | 3         | 1.24%   |
| 5.19.0-50-generic | 2         | 0.83%   |
| 5.19.0-45-generic | 2         | 0.83%   |
| 5.15.0-83-generic | 2         | 0.83%   |
| 5.15.0-78-generic | 2         | 0.83%   |
| 5.15.0-76-generic | 2         | 0.83%   |
| 5.15.0-70-generic | 2         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 147       | 65.33%  |
| 5.19.0  | 45        | 20%     |
| 6.2.0   | 26        | 11.56%  |
| 6.4.12  | 1         | 0.44%   |
| 6.1.12  | 1         | 0.44%   |
| 6.0.12  | 1         | 0.44%   |
| 5.4.0   | 1         | 0.44%   |
| 5.19.8  | 1         | 0.44%   |
| 5.18.0  | 1         | 0.44%   |
| 5.14.0  | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 147       | 65.33%  |
| 5.19    | 46        | 20.44%  |
| 6.2     | 26        | 11.56%  |
| 6.4     | 1         | 0.44%   |
| 6.1     | 1         | 0.44%   |
| 6.0     | 1         | 0.44%   |
| 5.4     | 1         | 0.44%   |
| 5.18    | 1         | 0.44%   |
| 5.14    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 220       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXQt       | 213       | 96.82%  |
| LXDE       | 4         | 1.82%   |
| X-Cinnamon | 2         | 0.91%   |
| KDE5       | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 217       | 98.64%  |
| Tty  | 3         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 195       | 87.84%  |
| Unknown | 13        | 5.86%   |
| LightDM | 10        | 4.5%    |
| GDM3    | 4         | 1.8%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Notebooks | Percent |
|--------|-----------|---------|
| en_US  | 67        | 30.32%  |
| fr_FR  | 22        | 9.95%   |
| it_IT  | 16        | 7.24%   |
| en_GB  | 16        | 7.24%   |
| C      | 13        | 5.88%   |
| de_DE  | 12        | 5.43%   |
| ru_RU  | 8         | 3.62%   |
| pt_BR  | 8         | 3.62%   |
| pl_PL  | 7         | 3.17%   |
| en_AG  | 7         | 3.17%   |
| es_MX  | 5         | 2.26%   |
| en_AU  | 4         | 1.81%   |
| nl_BE  | 3         | 1.36%   |
| es_CO  | 3         | 1.36%   |
| en_CA  | 3         | 1.36%   |
| tr_TR  | 2         | 0.9%    |
| sk_SK  | 2         | 0.9%    |
| es_ES  | 2         | 0.9%    |
| es_CR  | 2         | 0.9%    |
| es_AR  | 2         | 0.9%    |
| en_PH  | 2         | 0.9%    |
| vi_VN  | 1         | 0.45%   |
| nl_NL  | 1         | 0.45%   |
| lzh_TW | 1         | 0.45%   |
| ja_JP  | 1         | 0.45%   |
| hu_HU  | 1         | 0.45%   |
| fr_CA  | 1         | 0.45%   |
| fi_FI  | 1         | 0.45%   |
| es_EC  | 1         | 0.45%   |
| es_CL  | 1         | 0.45%   |
| en_ZA  | 1         | 0.45%   |
| en_DE  | 1         | 0.45%   |
| el_GR  | 1         | 0.45%   |
| de_CH  | 1         | 0.45%   |
| da_DK  | 1         | 0.45%   |
| aa_DJ  | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 134       | 60.63%  |
| EFI  | 87        | 39.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 188       | 83.93%  |
| Tmpfs   | 17        | 7.59%   |
| Overlay | 15        | 6.7%    |
| Btrfs   | 2         | 0.89%   |
| Xfs     | 1         | 0.45%   |
| Ext2    | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 123       | 55.16%  |
| MBR     | 66        | 29.6%   |
| Unknown | 34        | 15.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 202       | 90.99%  |
| Yes       | 20        | 9.01%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 74.77%  |
| Yes       | 56        | 25.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 41        | 18.64%  |
| Hewlett-Packard     | 37        | 16.82%  |
| Dell                | 26        | 11.82%  |
| Acer                | 21        | 9.55%   |
| ASUSTek Computer    | 14        | 6.36%   |
| Google              | 11        | 5%      |
| Toshiba             | 7         | 3.18%   |
| Apple               | 7         | 3.18%   |
| Unknown             | 5         | 2.27%   |
| Sony                | 4         | 1.82%   |
| Mediacom            | 4         | 1.82%   |
| Fujitsu             | 4         | 1.82%   |
| Samsung Electronics | 3         | 1.36%   |
| Thomson             | 2         | 0.91%   |
| Positivo            | 2         | 0.91%   |
| Packard Bell        | 2         | 0.91%   |
| Intel               | 2         | 0.91%   |
| HUAWEI              | 2         | 0.91%   |
| Hampoo              | 2         | 0.91%   |
| GPU Company         | 2         | 0.91%   |
| Getac               | 2         | 0.91%   |
| Gateway             | 2         | 0.91%   |
| TrekStor            | 1         | 0.45%   |
| SGIN                | 1         | 0.45%   |
| Pretech             | 1         | 0.45%   |
| Prestigio           | 1         | 0.45%   |
| Panasonic           | 1         | 0.45%   |
| OEM                 | 1         | 0.45%   |
| MSI                 | 1         | 0.45%   |
| Mini PC             | 1         | 0.45%   |
| Kiano               | 1         | 0.45%   |
| Insyde              | 1         | 0.45%   |
| IFSA                | 1         | 0.45%   |
| Fujitsu Siemens     | 1         | 0.45%   |
| eMachines           | 1         | 0.45%   |
| Dixonsxp            | 1         | 0.45%   |
| Compal              | 1         | 0.45%   |
| Chuwi               | 1         | 0.45%   |
| AXIOO               | 1         | 0.45%   |
| Alienware           | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 3.18%   |
| Mediacom WinPad 11,6 FullHD- WPU11         | 3         | 1.36%   |
| HP Pavilion 15                             | 3         | 1.36%   |
| HP Notebook                                | 3         | 1.36%   |
| Apple MacBookPro8,1                        | 3         | 1.36%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.91%   |
| Lenovo G50-30 80G0                         | 2         | 0.91%   |
| HP Pavilion g6                             | 2         | 0.91%   |
| HP 255 G2                                  | 2         | 0.91%   |
| HP 2000                                    | 2         | 0.91%   |
| Fujitsu LIFEBOOK A3510                     | 2         | 0.91%   |
| Apple MacBook4,1                           | 2         | 0.91%   |
| Acer Aspire SW3-013                        | 2         | 0.91%   |
| Acer Aspire A314-23P                       | 2         | 0.91%   |
| TrekStor SurfTab wintron 7.0 ST70416-6     | 1         | 0.45%   |
| Toshiba Satellite Radius P55W-B            | 1         | 0.45%   |
| Toshiba Satellite Pro S500                 | 1         | 0.45%   |
| Toshiba Satellite P770                     | 1         | 0.45%   |
| Toshiba Satellite P70-A                    | 1         | 0.45%   |
| Toshiba Satellite L875D                    | 1         | 0.45%   |
| Toshiba Satellite L40                      | 1         | 0.45%   |
| Toshiba Satellite C660                     | 1         | 0.45%   |
| Thomson NEO14-4W64                         | 1         | 0.45%   |
| Thomson N14C4WH64                          | 1         | 0.45%   |
| Sony VPCEH2E1R                             | 1         | 0.45%   |
| Sony VPCEB15FM                             | 1         | 0.45%   |
| Sony VGN-SZ71WN_C                          | 1         | 0.45%   |
| Sony SVE14A2V1EW                           | 1         | 0.45%   |
| SGIN laptop                                | 1         | 0.45%   |
| Samsung N150P/N210P/N220P                  | 1         | 0.45%   |
| Samsung N150/N210/N220                     | 1         | 0.45%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 1         | 0.45%   |
| Pretech EVE 1801 3G ES1049EG               | 1         | 0.45%   |
| Prestigio PSB141C01BFH                     | 1         | 0.45%   |
| Positivo Q232A                             | 1         | 0.45%   |
| Positivo i500pro                           | 1         | 0.45%   |
| Panasonic CF-F9KWPZFFE                     | 1         | 0.45%   |
| Packard Bell EasyNote TS44HR               | 1         | 0.45%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.45%   |
| MSI S12T 3M/S12 3M                         | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 16        | 7.27%   |
| Acer Aspire            | 16        | 7.27%   |
| Lenovo ThinkPad        | 15        | 6.82%   |
| Dell Latitude          | 10        | 4.55%   |
| HP Pavilion            | 9         | 4.09%   |
| Toshiba Satellite      | 7         | 3.18%   |
| Unknown                | 7         | 3.18%   |
| HP Laptop              | 5         | 2.27%   |
| Dell Inspiron          | 5         | 2.27%   |
| HP ProBook             | 4         | 1.82%   |
| Fujitsu LIFEBOOK       | 4         | 1.82%   |
| Dell XPS               | 4         | 1.82%   |
| Mediacom WinPad        | 3         | 1.36%   |
| HP Notebook            | 3         | 1.36%   |
| Dell Precision         | 3         | 1.36%   |
| Apple MacBookPro8      | 3         | 1.36%   |
| Packard Bell EasyNote  | 2         | 0.91%   |
| Lenovo G50-30          | 2         | 0.91%   |
| HP EliteBook           | 2         | 0.91%   |
| HP Compaq              | 2         | 0.91%   |
| HP 255                 | 2         | 0.91%   |
| HP 2000                | 2         | 0.91%   |
| HP 15                  | 2         | 0.91%   |
| Dell Vostro            | 2         | 0.91%   |
| Apple MacBook4         | 2         | 0.91%   |
| TrekStor SurfTab       | 1         | 0.45%   |
| Thomson NEO14-4W64     | 1         | 0.45%   |
| Thomson N14C4WH64      | 1         | 0.45%   |
| Sony VPCEH2E1R         | 1         | 0.45%   |
| Sony VPCEB15FM         | 1         | 0.45%   |
| Sony VGN-SZ71WN        | 1         | 0.45%   |
| Sony SVE14A2V1EW       | 1         | 0.45%   |
| SGIN laptop            | 1         | 0.45%   |
| Samsung N150P          | 1         | 0.45%   |
| Samsung N150           | 1         | 0.45%   |
| Samsung 300V3A         | 1         | 0.45%   |
| Pretech EVE            | 1         | 0.45%   |
| Prestigio PSB141C01BFH | 1         | 0.45%   |
| Positivo Q232A         | 1         | 0.45%   |
| Positivo i500pro       | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 24        | 10.91%  |
| 2013 | 23        | 10.45%  |
| 2012 | 21        | 9.55%   |
| 2016 | 17        | 7.73%   |
| 2015 | 16        | 7.27%   |
| 2010 | 16        | 7.27%   |
| 2021 | 14        | 6.36%   |
| 2022 | 13        | 5.91%   |
| 2014 | 12        | 5.45%   |
| 2019 | 11        | 5%      |
| 2008 | 11        | 5%      |
| 2017 | 9         | 4.09%   |
| 2020 | 8         | 3.64%   |
| 2009 | 8         | 3.64%   |
| 2007 | 7         | 3.18%   |
| 2023 | 5         | 2.27%   |
| 2018 | 5         | 2.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 220       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 208       | 93.27%  |
| Enabled  | 15        | 6.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 208       | 94.55%  |
| Yes  | 12        | 5.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 84        | 37.84%  |
| 4.01-8.0    | 57        | 25.68%  |
| 1.01-2.0    | 33        | 14.86%  |
| 8.01-16.0   | 21        | 9.46%   |
| 16.01-24.0  | 12        | 5.41%   |
| 2.01-3.0    | 8         | 3.6%    |
| 32.01-64.0  | 4         | 1.8%    |
| 24.01-32.0  | 1         | 0.45%   |
| 64.01-256.0 | 1         | 0.45%   |
| 0.51-1.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 113       | 48.92%  |
| 0.51-1.0  | 51        | 22.08%  |
| 2.01-3.0  | 47        | 20.35%  |
| 4.01-8.0  | 9         | 3.9%    |
| 3.01-4.0  | 9         | 3.9%    |
| 8.01-16.0 | 1         | 0.43%   |
| 0.01-0.5  | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 177       | 79.37%  |
| 2      | 38        | 17.04%  |
| 3      | 6         | 2.69%   |
| 0      | 2         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 122       | 55.45%  |
| Yes       | 98        | 44.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 76.47%  |
| No        | 52        | 23.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 90.45%  |
| No        | 21        | 9.55%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 64.57%  |
| No        | 79        | 35.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 37        | 16.82%  |
| France       | 24        | 10.91%  |
| Italy        | 20        | 9.09%   |
| Germany      | 20        | 9.09%   |
| Russia       | 12        | 5.45%   |
| UK           | 9         | 4.09%   |
| Poland       | 9         | 4.09%   |
| Brazil       | 8         | 3.64%   |
| Canada       | 5         | 2.27%   |
| Belgium      | 5         | 2.27%   |
| Ukraine      | 4         | 1.82%   |
| Mexico       | 4         | 1.82%   |
| Vietnam      | 3         | 1.36%   |
| Turkey       | 3         | 1.36%   |
| Slovakia     | 3         | 1.36%   |
| Netherlands  | 3         | 1.36%   |
| Hungary      | 3         | 1.36%   |
| Costa Rica   | 3         | 1.36%   |
| Colombia     | 3         | 1.36%   |
| Australia    | 3         | 1.36%   |
| UAE          | 2         | 0.91%   |
| Sweden       | 2         | 0.91%   |
| Spain        | 2         | 0.91%   |
| South Africa | 2         | 0.91%   |
| Portugal     | 2         | 0.91%   |
| Philippines  | 2         | 0.91%   |
| Indonesia    | 2         | 0.91%   |
| Finland      | 2         | 0.91%   |
| Czechia      | 2         | 0.91%   |
| Argentina    | 2         | 0.91%   |
| Thailand     | 1         | 0.45%   |
| Taiwan       | 1         | 0.45%   |
| Switzerland  | 1         | 0.45%   |
| Peru         | 1         | 0.45%   |
| Pakistan     | 1         | 0.45%   |
| Malaysia     | 1         | 0.45%   |
| Latvia       | 1         | 0.45%   |
| Kenya        | 1         | 0.45%   |
| Japan        | 1         | 0.45%   |
| Israel       | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Paris                  | 7         | 3.07%   |
| Moscow                 | 4         | 1.75%   |
| Bruhl                  | 4         | 1.75%   |
| Milan                  | 3         | 1.32%   |
| Kyiv                   | 3         | 1.32%   |
| Ghent                  | 3         | 1.32%   |
| Sarospatak             | 2         | 0.88%   |
| Rome                   | 2         | 0.88%   |
| Porto Alegre           | 2         | 0.88%   |
| Milano                 | 2         | 0.88%   |
| Lyon                   | 2         | 0.88%   |
| Lansing                | 2         | 0.88%   |
| Ho Chi Minh City       | 2         | 0.88%   |
| Heredia                | 2         | 0.88%   |
| Eugene                 | 2         | 0.88%   |
| Dubai                  | 2         | 0.88%   |
| Columbus               | 2         | 0.88%   |
| Bratislava             | 2         | 0.88%   |
| Bogotá                | 2         | 0.88%   |
| Zizur Mayor            | 1         | 0.44%   |
| Zawiercie              | 1         | 0.44%   |
| Zagreb                 | 1         | 0.44%   |
| Yoshkar-Ola            | 1         | 0.44%   |
| Yorkville              | 1         | 0.44%   |
| Yerevan                | 1         | 0.44%   |
| Yekaterinburg          | 1         | 0.44%   |
| Wolfhagen              | 1         | 0.44%   |
| West Stockbridge       | 1         | 0.44%   |
| Wattignies-la-Victoire | 1         | 0.44%   |
| Warsaw                 | 1         | 0.44%   |
| Warendorf              | 1         | 0.44%   |
| Waipahu                | 1         | 0.44%   |
| Vrbov                  | 1         | 0.44%   |
| Volzhskiy              | 1         | 0.44%   |
| Vesilahti              | 1         | 0.44%   |
| Verona                 | 1         | 0.44%   |
| Valenciennes           | 1         | 0.44%   |
| Uberlândia            | 1         | 0.44%   |
| Tychy                  | 1         | 0.44%   |
| Trabuco Canyon         | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Unknown                   | 42        | 59     | 17.07%  |
| WDC                       | 33        | 38     | 13.41%  |
| Seagate                   | 27        | 31     | 10.98%  |
| Samsung Electronics       | 20        | 30     | 8.13%   |
| Toshiba                   | 18        | 19     | 7.32%   |
| Hitachi                   | 12        | 15     | 4.88%   |
| SanDisk                   | 10        | 10     | 4.07%   |
| Kingston                  | 9         | 9      | 3.66%   |
| SK hynix                  | 6         | 6      | 2.44%   |
| Micron Technology         | 6         | 7      | 2.44%   |
| HGST                      | 6         | 7      | 2.44%   |
| Crucial                   | 5         | 5      | 2.03%   |
| Transcend                 | 4         | 5      | 1.63%   |
| A-DATA Technology         | 4         | 4      | 1.63%   |
| Unknown                   | 4         | 4      | 1.63%   |
| SPCC                      | 3         | 4      | 1.22%   |
| Intel                     | 3         | 3      | 1.22%   |
| UMIS                      | 2         | 2      | 0.81%   |
| Silicon Motion            | 2         | 2      | 0.81%   |
| LITEON                    | 2         | 2      | 0.81%   |
| GOODRAM                   | 2         | 2      | 0.81%   |
| Fujitsu                   | 2         | 2      | 0.81%   |
| China                     | 2         | 2      | 0.81%   |
| Apacer                    | 2         | 2      | 0.81%   |
| W800S                     | 1         | 1      | 0.41%   |
| Teclast                   | 1         | 1      | 0.41%   |
| Rogueware                 | 1         | 1      | 0.41%   |
| PNY                       | 1         | 1      | 0.41%   |
| Plextor                   | 1         | 1      | 0.41%   |
| Phison                    | 1         | 1      | 0.41%   |
| NGFF                      | 1         | 1      | 0.41%   |
| Netac                     | 1         | 1      | 0.41%   |
| Micron/Crucial Technology | 1         | 1      | 0.41%   |
| Lexar                     | 1         | 1      | 0.41%   |
| Leqixiang                 | 1         | 1      | 0.41%   |
| Lenovo                    | 1         | 1      | 0.41%   |
| LDLC                      | 1         | 2      | 0.41%   |
| KINGPOWER                 | 1         | 1      | 0.41%   |
| Kingmax                   | 1         | 1      | 0.41%   |
| Intenso                   | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  64GB             | 7         | 2.68%   |
| Unknown NCard  32GB                | 5         | 1.92%   |
| Unknown MMC Card  32GB             | 5         | 1.92%   |
| Seagate ST9500325AS 500GB          | 5         | 1.92%   |
| SanDisk DF4032  32GB               | 5         | 1.92%   |
| Unknown DA4032  32GB               | 4         | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 1.53%   |
| Unknown                            | 4         | 1.53%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 1.15%   |
| Unknown SD/MMC/MS PRO 16GB         | 3         | 1.15%   |
| Unknown MMC Card  16GB             | 3         | 1.15%   |
| Toshiba MQ01ABF050 500GB           | 3         | 1.15%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 1.15%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 1.15%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.77%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 2         | 0.77%   |
| WDC WD10SPZX-24Z10 1TB             | 2         | 0.77%   |
| Unknown SC64G  64GB                | 2         | 0.77%   |
| Unknown SC256  256GB               | 2         | 0.77%   |
| Unknown MMC64G  64GB               | 2         | 0.77%   |
| Unknown DA4064  64GB               | 2         | 0.77%   |
| Toshiba MQ01ABD075 752GB           | 2         | 0.77%   |
| Toshiba MQ01ABD050 500GB           | 2         | 0.77%   |
| SPCC Solid State Disk 120GB        | 2         | 0.77%   |
| SK hynix HBG4e  32GB               | 2         | 0.77%   |
| Seagate ST1000LM048-2E7172 1TB     | 2         | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.77%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.77%   |
| Samsung HM160HI 160GB              | 2         | 0.77%   |
| Samsung HM121HI 120GB              | 2         | 0.77%   |
| Micron 2450_MTFDKBA512TFK 512GB    | 2         | 0.77%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.77%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.38%   |
| WDC WDS500G2B0A 500GB SSD          | 1         | 0.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 0.38%   |
| WDC WDS250G2B0A 250GB SSD          | 1         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.38%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.38%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.38%   |
| WDC WD5000LPSX-22A6WT0 500GB       | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 28     | 28.13%  |
| Seagate             | 27        | 31     | 28.13%  |
| Toshiba             | 15        | 16     | 15.63%  |
| Hitachi             | 12        | 15     | 12.5%   |
| HGST                | 6         | 7      | 6.25%   |
| Samsung Electronics | 4         | 9      | 4.17%   |
| Unknown             | 3         | 3      | 3.13%   |
| Fujitsu             | 2         | 2      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 15.28%  |
| Kingston            | 8         | 8      | 11.11%  |
| SanDisk             | 5         | 5      | 6.94%   |
| WDC                 | 4         | 6      | 5.56%   |
| Transcend           | 4         | 5      | 5.56%   |
| Crucial             | 4         | 4      | 5.56%   |
| A-DATA Technology   | 4         | 4      | 5.56%   |
| Toshiba             | 3         | 3      | 4.17%   |
| SPCC                | 3         | 4      | 4.17%   |
| Intel               | 3         | 3      | 4.17%   |
| Micron Technology   | 2         | 2      | 2.78%   |
| LITEON              | 2         | 2      | 2.78%   |
| GOODRAM             | 2         | 2      | 2.78%   |
| Apacer              | 2         | 2      | 2.78%   |
| W800S               | 1         | 1      | 1.39%   |
| Teclast             | 1         | 1      | 1.39%   |
| Rogueware           | 1         | 1      | 1.39%   |
| PNY                 | 1         | 1      | 1.39%   |
| Plextor             | 1         | 1      | 1.39%   |
| NGFF                | 1         | 1      | 1.39%   |
| Netac               | 1         | 1      | 1.39%   |
| Lexar               | 1         | 1      | 1.39%   |
| Leqixiang           | 1         | 1      | 1.39%   |
| Lenovo              | 1         | 1      | 1.39%   |
| KINGPOWER           | 1         | 1      | 1.39%   |
| Kingmax             | 1         | 1      | 1.39%   |
| HUSKY               | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| BHT                 | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 94        | 111    | 38.68%  |
| SSD     | 70        | 77     | 28.81%  |
| MMC     | 50        | 68     | 20.58%  |
| NVMe    | 25        | 31     | 10.29%  |
| Unknown | 4         | 5      | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 157       | 186    | 65.69%  |
| MMC  | 50        | 68     | 20.92%  |
| NVMe | 25        | 31     | 10.46%  |
| SAS  | 7         | 7      | 2.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 141    | 76.07%  |
| 0.51-1.0   | 36        | 44     | 22.09%  |
| 1.01-2.0   | 2         | 2      | 1.23%   |
| 3.01-4.0   | 1         | 1      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 77        | 34.38%  |
| 251-500        | 55        | 24.55%  |
| 501-1000       | 23        | 10.27%  |
| 1-20           | 22        | 9.82%   |
| 51-100         | 22        | 9.82%   |
| 21-50          | 18        | 8.04%   |
| More than 3000 | 3         | 1.34%   |
| 1001-2000      | 2         | 0.89%   |
| 2001-3000      | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 120       | 52.86%  |
| 21-50          | 48        | 21.15%  |
| 51-100         | 25        | 11.01%  |
| 101-250        | 20        | 8.81%   |
| 251-500        | 6         | 2.64%   |
| 501-1000       | 3         | 1.32%   |
| More than 3000 | 2         | 0.88%   |
| 1001-2000      | 2         | 0.88%   |
| Unknown        | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 11.43%  |
| Seagate ST9500325AS 500GB          | 2         | 2      | 5.71%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 5.71%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 2.86%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 2.86%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 2.86%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.86%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 2.86%   |
| Transcend TS256GSSD720 256GB       | 1         | 1      | 2.86%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 2.86%   |
| Toshiba MK2556GSY 250GB            | 1         | 1      | 2.86%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2.86%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.86%   |
| Seagate ST320LT012-9WS14C 320GB    | 1         | 1      | 2.86%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 2.86%   |
| Seagate ST1000DM003-1SB102 1TB     | 1         | 1      | 2.86%   |
| Samsung Electronics HM121HI 120GB  | 1         | 6      | 2.86%   |
| Plextor PX-128M6M 128GB SSD        | 1         | 1      | 2.86%   |
| NGFF 2280 512GB SSD                | 1         | 1      | 2.86%   |
| Kingmax SSD 120GB                  | 1         | 1      | 2.86%   |
| Intel SSDSC2KW512G8 512GB          | 1         | 1      | 2.86%   |
| Intel SSDSA2M080G2LE 80GB          | 1         | 1      | 2.86%   |
| Hitachi HTS722080K9SA00 80GB       | 1         | 1      | 2.86%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 2.86%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.86%   |
| HGST HTS725032A7E630 320GB         | 1         | 1      | 2.86%   |
| Fujitsu MHY2120BH 120GB            | 1         | 1      | 2.86%   |
| Apacer 16GB SATA Flash Drive SSD   | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 40%     |
| WDC                 | 5         | 5      | 14.29%  |
| Toshiba             | 3         | 3      | 8.57%   |
| Hitachi             | 3         | 3      | 8.57%   |
| Intel               | 2         | 2      | 5.71%   |
| Transcend           | 1         | 1      | 2.86%   |
| Samsung Electronics | 1         | 6      | 2.86%   |
| Plextor             | 1         | 1      | 2.86%   |
| NGFF                | 1         | 1      | 2.86%   |
| Kingmax             | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Fujitsu             | 1         | 1      | 2.86%   |
| Apacer              | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 50%     |
| WDC                 | 5         | 5      | 17.86%  |
| Toshiba             | 3         | 3      | 10.71%  |
| Hitachi             | 3         | 3      | 10.71%  |
| Samsung Electronics | 1         | 6      | 3.57%   |
| HGST                | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 33     | 80%     |
| SSD  | 7         | 7      | 20%     |

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
| Detected | 123       | 164    | 53.25%  |
| Works    | 73        | 88     | 31.6%   |
| Malfunc  | 35        | 40     | 15.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 148       | 72.91%  |
| AMD                              | 27        | 13.3%   |
| Samsung Electronics              | 5         | 2.46%   |
| Micron Technology                | 5         | 2.46%   |
| SK hynix                         | 3         | 1.48%   |
| SanDisk                          | 3         | 1.48%   |
| Union Memory (Shenzhen)          | 2         | 0.99%   |
| Silicon Motion                   | 2         | 0.99%   |
| Nvidia                           | 2         | 0.99%   |
| Micron/Crucial Technology        | 2         | 0.99%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Silicon Image                    | 1         | 0.49%   |
| Phison Electronics               | 1         | 0.49%   |
| Kingston Technology Company      | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 25        | 11.36%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 9.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 5.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 5%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 4.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 4.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 3.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 7         | 3.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 2.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 2.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 1.36%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 3         | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.91%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.91%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.91%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.91%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                            | 1         | 0.45%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 0.45%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.45%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.45%   |
| Silicon Image SiI 3531 [SATALink/SATARaid] Serial ATA Controller                 | 1         | 0.45%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1         | 0.45%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 1         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 163       | 76.53%  |
| NVMe | 24        | 11.27%  |
| IDE  | 19        | 8.92%   |
| RAID | 7         | 3.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 187       | 85%     |
| AMD    | 33        | 15%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU N3060 @ 1.60GHz           | 8         | 3.64%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 7         | 3.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 2.27%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 5         | 2.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.82%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 1.82%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 4         | 1.82%   |
| Intel Atom CPU N450 @ 1.66GHz               | 4         | 1.82%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 3         | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.36%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 3         | 1.36%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 3         | 1.36%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.36%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.36%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 3         | 1.36%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 2         | 0.91%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.91%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 0.91%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 2         | 0.91%   |
| Intel Core i5-9300HF CPU @ 2.40GHz          | 2         | 0.91%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.91%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 0.91%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.91%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 2         | 0.91%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 0.91%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 0.91%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 2         | 0.91%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 0.91%   |
| Intel Core 2 Duo CPU T5450 @ 1.66GHz        | 2         | 0.91%   |
| Intel Celeron N4500 @ 1.10GHz               | 2         | 0.91%   |
| Intel Celeron N4120 CPU @ 1.10GHz           | 2         | 0.91%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 2         | 0.91%   |
| Intel Celeron CPU B815 @ 1.60GHz            | 2         | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 0.91%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 0.91%   |
| AMD Ryzen 5 7520U with Radeon Graphics      | 2         | 0.91%   |
| AMD E1-2100 APU with Radeon HD Graphics     | 2         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 20%     |
| Intel Celeron           | 44        | 20%     |
| Intel Core i7           | 21        | 9.55%   |
| Intel Atom              | 21        | 9.55%   |
| Intel Core 2 Duo        | 18        | 8.18%   |
| Intel Core i3           | 17        | 7.73%   |
| Intel Pentium           | 8         | 3.64%   |
| AMD A6                  | 6         | 2.73%   |
| Other                   | 5         | 2.27%   |
| AMD E2                  | 4         | 1.82%   |
| Intel Pentium Dual-Core | 3         | 1.36%   |
| Intel Pentium Dual      | 3         | 1.36%   |
| AMD Ryzen 7             | 3         | 1.36%   |
| AMD Ryzen 5             | 3         | 1.36%   |
| AMD E1                  | 3         | 1.36%   |
| AMD E                   | 3         | 1.36%   |
| Intel Core 2            | 2         | 0.91%   |
| AMD A8                  | 2         | 0.91%   |
| AMD A4                  | 2         | 0.91%   |
| Intel Pentium Silver    | 1         | 0.45%   |
| Intel Celeron Dual-Core | 1         | 0.45%   |
| AMD Ryzen 9             | 1         | 0.45%   |
| AMD Ryzen 7 PRO         | 1         | 0.45%   |
| AMD C-60                | 1         | 0.45%   |
| AMD Athlon II           | 1         | 0.45%   |
| AMD Athlon              | 1         | 0.45%   |
| AMD A10                 | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 144       | 65.45%  |
| 4      | 61        | 27.73%  |
| 1      | 7         | 3.18%   |
| 8      | 5         | 2.27%   |
| 10     | 2         | 0.91%   |
| 6      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 220       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 53.18%  |
| 2      | 103       | 46.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 40.54%  |
| 0x306a9    | 16        | 7.21%   |
| 0x206a7    | 11        | 4.95%   |
| 0x406c3    | 8         | 3.6%    |
| 0x706a8    | 6         | 2.7%    |
| 0x406c4    | 5         | 2.25%   |
| 0x30678    | 5         | 2.25%   |
| 0x20655    | 5         | 2.25%   |
| 0x0700010f | 5         | 2.25%   |
| 0x6fd      | 4         | 1.8%    |
| 0x40651    | 4         | 1.8%    |
| 0x1067a    | 4         | 1.8%    |
| 0x05000119 | 4         | 1.8%    |
| 0x806ec    | 3         | 1.35%   |
| 0x806ea    | 3         | 1.35%   |
| 0x706a1    | 3         | 1.35%   |
| 0x506c9    | 3         | 1.35%   |
| 0x406e3    | 3         | 1.35%   |
| 0x0a50000c | 3         | 1.35%   |
| 0x06006705 | 3         | 1.35%   |
| 0x906c0    | 2         | 0.9%    |
| 0x906a4    | 2         | 0.9%    |
| 0x806c1    | 2         | 0.9%    |
| 0x706e5    | 2         | 0.9%    |
| 0x306c3    | 2         | 0.9%    |
| 0x106ca    | 2         | 0.9%    |
| 0x08a00008 | 2         | 0.9%    |
| 0x06006704 | 2         | 0.9%    |
| 0x06001119 | 2         | 0.9%    |
| 0x906ed    | 1         | 0.45%   |
| 0x806eb    | 1         | 0.45%   |
| 0x806e9    | 1         | 0.45%   |
| 0x6fb      | 1         | 0.45%   |
| 0x6fa      | 1         | 0.45%   |
| 0x6f6      | 1         | 0.45%   |
| 0x506e3    | 1         | 0.45%   |
| 0x306d4    | 1         | 0.45%   |
| 0x20652    | 1         | 0.45%   |
| 0x10676    | 1         | 0.45%   |
| 0x0a50000b | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Silvermont       | 38        | 17.27%  |
| IvyBridge        | 22        | 10%     |
| SandyBridge      | 20        | 9.09%   |
| Penryn           | 15        | 6.82%   |
| Goldmont plus    | 14        | 6.36%   |
| Westmere         | 13        | 5.91%   |
| KabyLake         | 12        | 5.45%   |
| Haswell          | 12        | 5.45%   |
| Core             | 12        | 5.45%   |
| Excavator        | 7         | 3.18%   |
| Jaguar           | 6         | 2.73%   |
| Goldmont         | 6         | 2.73%   |
| Skylake          | 5         | 2.27%   |
| Bonnell          | 5         | 2.27%   |
| Unknown          | 5         | 2.27%   |
| Zen 3            | 4         | 1.82%   |
| Piledriver       | 4         | 1.82%   |
| Broadwell        | 4         | 1.82%   |
| Bobcat           | 4         | 1.82%   |
| Tremont          | 3         | 1.36%   |
| TigerLake        | 2         | 0.91%   |
| Puma             | 2         | 0.91%   |
| IceLake          | 2         | 0.91%   |
| Alderlake Hybrid | 2         | 0.91%   |
| K10              | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 173       | 69.48%  |
| AMD    | 45        | 18.07%  |
| Nvidia | 31        | 12.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 9.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 8.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 7.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 5.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 4.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 4.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.63%   |
| Intel HD Graphics 500                                                                    | 6         | 2.26%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 2.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.5%    |
| Intel UHD Graphics 620                                                                   | 3         | 1.13%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.13%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.13%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.13%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.13%   |
| AMD Mendocino                                                                            | 3         | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.75%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 0.75%   |
| Nvidia G96CM [GeForce GT 120M]                                                           | 2         | 0.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.75%   |
| Intel HD Graphics 630                                                                    | 2         | 0.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.75%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.75%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 2         | 0.75%   |
| AMD Trinity 2 [Radeon HD 7520G]                                                          | 2         | 0.75%   |
| AMD Lucienne                                                                             | 2         | 0.75%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                                  | 2         | 0.75%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 0.75%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                                        | 1         | 0.38%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 142       | 64.55%  |
| 1 x AMD        | 28        | 12.73%  |
| Intel + Nvidia | 17        | 7.73%   |
| 1 x Nvidia     | 12        | 5.45%   |
| Intel + AMD    | 9         | 4.09%   |
| 2 x AMD        | 6         | 2.73%   |
| Other          | 4         | 1.82%   |
| AMD + Nvidia   | 2         | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 209       | 95%     |
| Proprietary | 8         | 3.64%   |
| Unknown     | 3         | 1.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 79.19%  |
| 0.01-0.5   | 24        | 10.86%  |
| 1.01-2.0   | 13        | 5.88%   |
| 0.51-1.0   | 5         | 2.26%   |
| 3.01-4.0   | 2         | 0.9%    |
| 5.01-6.0   | 1         | 0.45%   |
| 2.01-3.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 20.44%  |
| LG Display              | 41        | 18.22%  |
| BOE                     | 31        | 13.78%  |
| Samsung Electronics     | 25        | 11.11%  |
| Chimei Innolux          | 24        | 10.67%  |
| Apple                   | 8         | 3.56%   |
| Lenovo                  | 6         | 2.67%   |
| Sharp                   | 5         | 2.22%   |
| CPT                     | 5         | 2.22%   |
| Chi Mei Optoelectronics | 4         | 1.78%   |
| Acer                    | 4         | 1.78%   |
| Toshiba                 | 3         | 1.33%   |
| Goldstar                | 3         | 1.33%   |
| LG Philips              | 2         | 0.89%   |
| InfoVision              | 2         | 0.89%   |
| Hewlett-Packard         | 2         | 0.89%   |
| ViewSonic               | 1         | 0.44%   |
| Panasonic               | 1         | 0.44%   |
| LLL                     | 1         | 0.44%   |
| JVC                     | 1         | 0.44%   |
| JDI                     | 1         | 0.44%   |
| Insignia                | 1         | 0.44%   |
| InnoLux Display         | 1         | 0.44%   |
| Dell                    | 1         | 0.44%   |
| CS_                     | 1         | 0.44%   |
| CMN                     | 1         | 0.44%   |
| BenQ                    | 1         | 0.44%   |
| ASUSTek Computer        | 1         | 0.44%   |
| AOC                     | 1         | 0.44%   |
| Ancor Communications    | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 6         | 2.67%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 4         | 1.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.33%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 3         | 1.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.89%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.89%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch               | 2         | 0.89%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 2         | 0.89%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                  | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.89%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                  | 2         | 0.89%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                  | 2         | 0.89%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 0.89%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 2         | 0.89%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 2         | 0.89%   |
| ViewSonic VA2932 SERIES VSCFF3B 2560x1080 673x284mm 28.8-inch         | 1         | 0.44%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 1         | 0.44%   |
| Toshiba LCD Monitor LCD5860 1280x800 261x163mm 12.1-inch              | 1         | 0.44%   |
| Toshiba LCD Monitor LCD2306 1280x800 287x180mm 13.3-inch              | 1         | 0.44%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch               | 1         | 0.44%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.44%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 1         | 0.44%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM052A 1920x1080 510x290mm 23.1-inch  | 1         | 0.44%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4750 1680x1050 365x228mm 16.9-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch  | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 106       | 47.96%  |
| 1920x1080 (FHD)    | 46        | 20.81%  |
| 1280x800 (WXGA)    | 24        | 10.86%  |
| 1600x900 (HD+)     | 18        | 8.14%   |
| 3840x2160 (4K)     | 6         | 2.71%   |
| 2560x1440 (QHD)    | 3         | 1.36%   |
| 1440x900 (WXGA+)   | 3         | 1.36%   |
| 3200x1800 (QHD+)   | 2         | 0.9%    |
| 2160x1440          | 2         | 0.9%    |
| 1920x1200 (WUXGA)  | 2         | 0.9%    |
| 1680x1050 (WSXGA+) | 2         | 0.9%    |
| 1024x600           | 2         | 0.9%    |
| 3000x2000          | 1         | 0.45%   |
| 2560x1080          | 1         | 0.45%   |
| 1920x540           | 1         | 0.45%   |
| 1528x1222          | 1         | 0.45%   |
| 1360x768           | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 74        | 32.89%  |
| 14      | 38        | 16.89%  |
| 13      | 32        | 14.22%  |
| 11      | 19        | 8.44%   |
| 17      | 18        | 8%      |
| 12      | 12        | 5.33%   |
| 27      | 4         | 1.78%   |
| 10      | 4         | 1.78%   |
| 24      | 3         | 1.33%   |
| 23      | 3         | 1.33%   |
| 21      | 3         | 1.33%   |
| 84      | 2         | 0.89%   |
| 28      | 2         | 0.89%   |
| 19      | 2         | 0.89%   |
| Unknown | 2         | 0.89%   |
| 72      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 44      | 1         | 0.44%   |
| 22      | 1         | 0.44%   |
| 18      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |
| 9       | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 127       | 56.44%  |
| 201-300     | 51        | 22.67%  |
| 351-400     | 20        | 8.89%   |
| 501-600     | 9         | 4%      |
| 401-500     | 7         | 3.11%   |
| 601-700     | 3         | 1.33%   |
| 1501-2000   | 3         | 1.33%   |
| Unknown     | 2         | 0.89%   |
| 101-200     | 1         | 0.44%   |
| 1001-1500   | 1         | 0.44%   |
| 901-1000    | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 170       | 81.73%  |
| 16/10   | 30        | 14.42%  |
| 3/2     | 5         | 2.4%    |
| 4/3     | 1         | 0.48%   |
| 21/9    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 32.89%  |
| 81-90          | 64        | 28.44%  |
| 51-60          | 19        | 8.44%   |
| 121-130        | 17        | 7.56%   |
| 61-70          | 12        | 5.33%   |
| 201-250        | 8         | 3.56%   |
| 71-80          | 6         | 2.67%   |
| 41-50          | 5         | 2.22%   |
| More than 1000 | 4         | 1.78%   |
| 301-350        | 4         | 1.78%   |
| 251-300        | 3         | 1.33%   |
| 151-200        | 2         | 0.89%   |
| 131-140        | 2         | 0.89%   |
| Unknown        | 2         | 0.89%   |
| 351-500        | 1         | 0.44%   |
| 141-150        | 1         | 0.44%   |
| 501-1000       | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 111       | 50%     |
| 121-160       | 67        | 30.18%  |
| 51-100        | 26        | 11.71%  |
| 161-240       | 10        | 4.5%    |
| More than 240 | 3         | 1.35%   |
| 1-50          | 3         | 1.35%   |
| Unknown       | 2         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 197       | 89.14%  |
| 2     | 19        | 8.6%    |
| 0     | 4         | 1.81%   |
| 3     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 107       | 32.23%  |
| Intel                             | 83        | 25%     |
| Qualcomm Atheros                  | 55        | 16.57%  |
| Broadcom                          | 27        | 8.13%   |
| Marvell Technology Group          | 9         | 2.71%   |
| Ralink                            | 6         | 1.81%   |
| Samsung Electronics               | 5         | 1.51%   |
| MediaTek                          | 4         | 1.2%    |
| Broadcom Limited                  | 4         | 1.2%    |
| ASIX Electronics                  | 4         | 1.2%    |
| TP-Link                           | 3         | 0.9%    |
| Ralink Technology                 | 3         | 0.9%    |
| OPPO Electronics                  | 3         | 0.9%    |
| Xiaomi                            | 2         | 0.6%    |
| Qualcomm Atheros Communications   | 2         | 0.6%    |
| Qualcomm                          | 2         | 0.6%    |
| Spreadtrum Communications         | 1         | 0.3%    |
| Sierra Wireless                   | 1         | 0.3%    |
| Nvidia                            | 1         | 0.3%    |
| NetGear                           | 1         | 0.3%    |
| Motorola PCS                      | 1         | 0.3%    |
| Microsoft                         | 1         | 0.3%    |
| Micro Star International          | 1         | 0.3%    |
| JMicron Technology                | 1         | 0.3%    |
| ICS Advent                        | 1         | 0.3%    |
| Ericsson Business Mobile Networks | 1         | 0.3%    |
| Dresden Elektronik                | 1         | 0.3%    |
| Dell                              | 1         | 0.3%    |
| ASUSTek Computer                  | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 11.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 7.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2.49%   |
| Intel Wireless 7265                                               | 10        | 2.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.49%   |
| Intel Wireless 7260                                               | 9         | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.25%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 1%      |
| Realtek 802.11n WLAN Adapter                                      | 4         | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 1%      |
| Intel Wireless 8265 / 8275                                        | 4         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 1%      |
| Intel Centrino Wireless-N 2230                                    | 4         | 1%      |
| Intel Centrino Advanced-N 6200                                    | 4         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.75%   |
| OPPO RMX2027                                                      | 3         | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.75%   |
| Intel Wireless 3165                                               | 3         | 0.75%   |
| Intel Wireless 3160                                               | 3         | 0.75%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.75%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 77        | 35.98%  |
| Qualcomm Atheros                  | 49        | 22.9%   |
| Realtek Semiconductor             | 43        | 20.09%  |
| Broadcom                          | 19        | 8.88%   |
| Ralink                            | 6         | 2.8%    |
| MediaTek                          | 4         | 1.87%   |
| Ralink Technology                 | 3         | 1.4%    |
| TP-Link                           | 2         | 0.93%   |
| Qualcomm Atheros Communications   | 2         | 0.93%   |
| Broadcom Limited                  | 2         | 0.93%   |
| Sierra Wireless                   | 1         | 0.47%   |
| NetGear                           | 1         | 0.47%   |
| Microsoft                         | 1         | 0.47%   |
| Micro Star International          | 1         | 0.47%   |
| Ericsson Business Mobile Networks | 1         | 0.47%   |
| Dell                              | 1         | 0.47%   |
| ASUSTek Computer                  | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 5.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 4.65%   |
| Intel Wireless 7265                                            | 10        | 4.65%   |
| Intel Wireless 7260                                            | 9         | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 3.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.33%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.86%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 4         | 1.86%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.86%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.4%    |
| Intel Wireless 3165                                            | 3         | 1.4%    |
| Intel Wireless 3160                                            | 3         | 1.4%    |
| Intel Wi-Fi 6 AX200                                            | 3         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.4%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.93%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.93%   |
| Intel Wireless 8260                                            | 2         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 89        | 48.37%  |
| Intel                     | 33        | 17.93%  |
| Qualcomm Atheros          | 16        | 8.7%    |
| Broadcom                  | 13        | 7.07%   |
| Marvell Technology Group  | 9         | 4.89%   |
| Samsung Electronics       | 5         | 2.72%   |
| ASIX Electronics          | 4         | 2.17%   |
| OPPO Electronics          | 3         | 1.63%   |
| Xiaomi                    | 2         | 1.09%   |
| Qualcomm                  | 2         | 1.09%   |
| Broadcom Limited          | 2         | 1.09%   |
| TP-Link                   | 1         | 0.54%   |
| Spreadtrum Communications | 1         | 0.54%   |
| Nvidia                    | 1         | 0.54%   |
| Motorola PCS              | 1         | 0.54%   |
| JMicron Technology        | 1         | 0.54%   |
| ICS Advent                | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 45        | 24.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 32        | 17.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 5.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 3.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 3.24%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 3.24%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 2.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 2.16%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 1.62%   |
| OPPO RMX2027                                                                   | 3         | 1.62%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 1.62%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.62%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.62%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 1.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.08%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 1.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 1.08%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.08%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.08%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 1.08%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.54%   |
| Spreadtrum meizu C9                                                            | 1         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.54%   |
| Realtek RTL8150 Fast Ethernet Adapter                                          | 1         | 0.54%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                               | 1         | 0.54%   |
| Qualcomm Redmi Note 8                                                          | 1         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.54%   |
| Nvidia MCP89 Ethernet                                                          | 1         | 0.54%   |
| Motorola PCS motorola one macro                                                | 1         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.54%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 54.05%  |
| Ethernet | 169       | 45.68%  |
| Modem    | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 152       | 70.7%   |
| Ethernet | 63        | 29.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 141       | 64.09%  |
| 1     | 53        | 24.09%  |
| 0     | 24        | 10.91%  |
| 3     | 2         | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 75.23%  |
| Yes  | 55        | 24.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 33.79%  |
| Realtek Semiconductor           | 22        | 15.17%  |
| Qualcomm Atheros Communications | 18        | 12.41%  |
| Broadcom                        | 10        | 6.9%    |
| Lite-On Technology              | 8         | 5.52%   |
| IMC Networks                    | 6         | 4.14%   |
| Apple                           | 6         | 4.14%   |
| Foxconn / Hon Hai               | 5         | 3.45%   |
| Ralink                          | 4         | 2.76%   |
| Hewlett-Packard                 | 4         | 2.76%   |
| Dell                            | 4         | 2.76%   |
| Cambridge Silicon Radio         | 3         | 2.07%   |
| Toshiba                         | 2         | 1.38%   |
| Alps Electric                   | 2         | 1.38%   |
| Syntek                          | 1         | 0.69%   |
| ASUSTek Computer                | 1         | 0.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 20.55%  |
| Realtek Bluetooth Radio                                                             | 14        | 9.59%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 6.16%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 3.42%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 3.42%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 2.74%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.74%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 2.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.05%   |
| Intel Bluetooth Device                                                              | 3         | 2.05%   |
| Intel AX201 Bluetooth                                                               | 3         | 2.05%   |
| Intel AX200 Bluetooth                                                               | 3         | 2.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.05%   |
| Apple Bluetooth Host Controller                                                     | 3         | 2.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.37%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.37%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.37%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.37%   |
| Apple Bluetooth HCI                                                                 | 2         | 1.37%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.68%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.68%   |
| Syntek 802.11g + Bluetooth Wireless Adapter                                         | 1         | 0.68%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.68%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.68%   |
| Lite-On Wireless_Device                                                             | 1         | 0.68%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.68%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.68%   |
| Lite-On BCM20702A0                                                                  | 1         | 0.68%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.68%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.68%   |
| IMC Networks Bluetooth                                                              | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth                                               | 1         | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 168       | 75%     |
| AMD                  | 36        | 16.07%  |
| Nvidia               | 15        | 6.7%    |
| MosArt Semiconductor | 1         | 0.45%   |
| JMTek                | 1         | 0.45%   |
| GN Netcom            | 1         | 0.45%   |
| EGO SYStems          | 1         | 0.45%   |
| C-Media Electronics  | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 10.45%  |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 5.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 5.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 4.85%   |
| AMD FCH Azalia Controller                                                                         | 13        | 4.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 4.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 3.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 3.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 3.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.99%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 2.24%   |
| AMD High Definition Audio Controller                                                              | 6         | 2.24%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.49%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.49%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.12%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.12%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.12%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.75%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 23.67%  |
| SK hynix            | 39        | 23.08%  |
| Unknown             | 20        | 11.83%  |
| Micron Technology   | 18        | 10.65%  |
| Nanya Technology    | 7         | 4.14%   |
| Kingston            | 7         | 4.14%   |
| Unknown (ABCD)      | 6         | 3.55%   |
| Elpida              | 6         | 3.55%   |
| Ramaxel Technology  | 3         | 1.78%   |
| Unknown             | 3         | 1.78%   |
| Smart               | 2         | 1.18%   |
| fef5                | 2         | 1.18%   |
| Crucial             | 2         | 1.18%   |
| Corsair             | 2         | 1.18%   |
| A-DATA Technology   | 2         | 1.18%   |
| Transcend           | 1         | 0.59%   |
| Toshiba             | 1         | 0.59%   |
| PUSKILL             | 1         | 0.59%   |
| Novatech            | 1         | 0.59%   |
| Kllisre             | 1         | 0.59%   |
| Kingmax             | 1         | 0.59%   |
| HMD                 | 1         | 0.59%   |
| G.Skill             | 1         | 0.59%   |
| Apacer              | 1         | 0.59%   |
| AMD                 | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.76%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 4         | 2.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.21%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 2.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.21%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 1.66%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.66%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.66%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 3         | 1.66%   |
| Unknown                                                          | 3         | 1.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 1.1%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.1%    |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 2         | 1.1%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.1%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.1%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.1%    |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 1.1%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.1%    |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 2         | 1.1%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 1.1%    |
| Micron RAM 4ATF51264HZ-372J1 4GB Row Of Chips DDR4 1866MT/s      | 2         | 1.1%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 1.1%    |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 1.1%    |
| Elpida RAM EBJ20UF8BDU0-GN-F 2GB SODIMM DDR3 1600MT/s            | 2         | 1.1%    |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.55%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.55%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2                        | 1         | 0.55%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 0.55%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s           | 1         | 0.55%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.55%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 79        | 52.32%  |
| DDR4    | 34        | 22.52%  |
| LPDDR4  | 13        | 8.61%   |
| DDR2    | 12        | 7.95%   |
| SDRAM   | 4         | 2.65%   |
| LPDDR5  | 4         | 2.65%   |
| LPDDR3  | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| DDR5    | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 87.16%  |
| Row Of Chips | 11        | 7.43%   |
| Unknown      | 5         | 3.38%   |
| DIMM         | 3         | 2.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 31.33%  |
| 8192  | 46        | 27.71%  |
| 2048  | 46        | 27.71%  |
| 1024  | 13        | 7.83%   |
| 16384 | 6         | 3.61%   |
| 32768 | 2         | 1.2%    |
| 512   | 1         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 33.33%  |
| 2400    | 16        | 10.06%  |
| 3200    | 13        | 8.18%   |
| 1333    | 12        | 7.55%   |
| 1334    | 9         | 5.66%   |
| 667     | 9         | 5.66%   |
| 2667    | 8         | 5.03%   |
| 1066    | 7         | 4.4%    |
| 3266    | 4         | 2.52%   |
| 1067    | 4         | 2.52%   |
| 6400    | 3         | 1.89%   |
| 1866    | 3         | 1.89%   |
| Unknown | 3         | 1.89%   |
| 4267    | 2         | 1.26%   |
| 2133    | 2         | 1.26%   |
| 2048    | 2         | 1.26%   |
| 975     | 2         | 1.26%   |
| 5500    | 1         | 0.63%   |
| 4800    | 1         | 0.63%   |
| 4199    | 1         | 0.63%   |
| 2933    | 1         | 0.63%   |
| 1867    | 1         | 0.63%   |
| 800     | 1         | 0.63%   |
| 533     | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model             | Notebooks | Percent |
|-------------------|-----------|---------|
| HP LaserJet P1102 | 1         | 50%     |
| Canon MF3110      | 1         | 50%     |

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
| Chicony Electronics                    | 49        | 28.16%  |
| Realtek Semiconductor                  | 18        | 10.34%  |
| Microdia                               | 17        | 9.77%   |
| Sunplus Innovation Technology          | 11        | 6.32%   |
| Syntek                                 | 10        | 5.75%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.02%   |
| IMC Networks                           | 6         | 3.45%   |
| Bison Electronics                      | 6         | 3.45%   |
| Apple                                  | 6         | 3.45%   |
| Alcor Micro                            | 6         | 3.45%   |
| Suyin                                  | 5         | 2.87%   |
| Quanta                                 | 5         | 2.87%   |
| Lite-On Technology                     | 5         | 2.87%   |
| ALi                                    | 4         | 2.3%    |
| Lenovo                                 | 3         | 1.72%   |
| Z-Star Microelectronics                | 2         | 1.15%   |
| Silicon Motion                         | 2         | 1.15%   |
| icSpring                               | 2         | 1.15%   |
| GEMBIRD                                | 2         | 1.15%   |
| Y Media                                | 1         | 0.57%   |
| USB Camera CS                          | 1         | 0.57%   |
| SunplusIT                              | 1         | 0.57%   |
| Ricoh                                  | 1         | 0.57%   |
| Logitech                               | 1         | 0.57%   |
| Cubeternet                             | 1         | 0.57%   |
| BKX-Usb2.0 2MP Camera                  | 1         | 0.57%   |
| Acer                                   | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 10        | 5.71%   |
| Chicony HP TrueVision HD Camera                         | 6         | 3.43%   |
| Alcor Micro USB 2.0 Camera                              | 5         | 2.86%   |
| Sunplus HD WebCam                                       | 4         | 2.29%   |
| Microdia Integrated Webcam                              | 4         | 2.29%   |
| Chicony HD WebCam                                       | 4         | 2.29%   |
| Syntek USB Camera Device                                | 3         | 1.71%   |
| Realtek USB Camera                                      | 3         | 1.71%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.71%   |
| Microdia Integrated_Webcam_HD                           | 3         | 1.71%   |
| Chicony VGA WebCam                                      | 3         | 1.71%   |
| Chicony HP Truevision HD                                | 3         | 1.71%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 3         | 1.71%   |
| Bison Lenovo EasyCamera                                 | 3         | 1.71%   |
| Apple FaceTime HD Camera                                | 3         | 1.71%   |
| ALi WebCam                                              | 3         | 1.71%   |
| Z-Star Webcam                                           | 2         | 1.14%   |
| Syntek Lenovo EasyCamera                                | 2         | 1.14%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.14%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.14%   |
| Realtek Integrated Webcam HD                            | 2         | 1.14%   |
| Realtek HP Truevision HD                                | 2         | 1.14%   |
| Microdia Lenovo EasyCamera                              | 2         | 1.14%   |
| Microdia HP Webcam-50                                   | 2         | 1.14%   |
| Lenovo Integrated Webcam                                | 2         | 1.14%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 1.14%   |
| icSpring camera                                         | 2         | 1.14%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 2         | 1.14%   |
| Chicony FJ Camera                                       | 2         | 1.14%   |
| Chicony EasyCamera                                      | 2         | 1.14%   |
| Chicony ACER HD User Facing                             | 2         | 1.14%   |
| Chicony 720p HD Camera                                  | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 2         | 1.14%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 1.14%   |
| Y Media USB Camera                                      | 1         | 0.57%   |
| USB Camera CS USB Camera CS                             | 1         | 0.57%   |
| Syntek USB2.0 Camera                                    | 1         | 0.57%   |
| Syntek Sonix USB 2.0 Camera                             | 1         | 0.57%   |
| Syntek Integrated Camera                                | 1         | 0.57%   |
| Syntek HD WebCam                                        | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 26.32%  |
| Upek                       | 5         | 26.32%  |
| AuthenTec                  | 4         | 21.05%  |
| STMicroelectronics         | 2         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| LighTuning Technology      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 26.32%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5.26%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                           | 1         | 5.26%   |
| AuthenTec AES2810                                      | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 46.15%  |
| Alcor Micro           | 4         | 30.77%  |
| O2 Micro              | 1         | 7.69%   |
| Lenovo                | 1         | 7.69%   |
| Gemalto (was Gemplus) | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Broadcom 5880                                    | 3         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader              | 3         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor   | 2         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader             | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader              | 1         | 7.69%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1         | 7.69%   |
| Broadcom 58200                                   | 1         | 7.69%   |
| Alcor Micro Watchdata W 1981                     | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 161       | 73.18%  |
| 1     | 50        | 22.73%  |
| 2     | 7         | 3.18%   |
| 4     | 1         | 0.45%   |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 18        | 26.09%  |
| Graphics card         | 12        | 17.39%  |
| Chipcard              | 12        | 17.39%  |
| Bluetooth             | 7         | 10.14%  |
| Camera                | 6         | 8.7%    |
| Net/wireless          | 5         | 7.25%   |
| Storage               | 2         | 2.9%    |
| Network               | 2         | 2.9%    |
| Multimedia controller | 2         | 2.9%    |
| Dvb card              | 2         | 2.9%    |
| Net/ethernet          | 1         | 1.45%   |

