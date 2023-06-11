Linux in Ireland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ireland/Desktop/README.md) and [notebooks](/Location/Ireland/Notebook/README.md).

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

Total: 933

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Lenovo        | ThinkPad T590 20N5S2NC0F    | Notebook    | [581602e921](https://linux-hardware.org/?probe=581602e921) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [476a44deee](https://linux-hardware.org/?probe=476a44deee) | Jun 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3d29012888](https://linux-hardware.org/?probe=3d29012888) | Jun 04, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [8678eeac9b](https://linux-hardware.org/?probe=8678eeac9b) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| HP            | 0AECh D                     | Desktop     | [30868178ea](https://linux-hardware.org/?probe=30868178ea) | May 26, 2023 |
| HP            | ZBook 15                    | Notebook    | [def4482b86](https://linux-hardware.org/?probe=def4482b86) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [a3798147d9](https://linux-hardware.org/?probe=a3798147d9) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [f2655b5798](https://linux-hardware.org/?probe=f2655b5798) | May 24, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [2bed616680](https://linux-hardware.org/?probe=2bed616680) | May 23, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [785f4bad86](https://linux-hardware.org/?probe=785f4bad86) | May 23, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [ca85d5aafa](https://linux-hardware.org/?probe=ca85d5aafa) | May 21, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46b31c9243](https://linux-hardware.org/?probe=46b31c9243) | May 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [c223c83063](https://linux-hardware.org/?probe=c223c83063) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [983ec204ab](https://linux-hardware.org/?probe=983ec204ab) | May 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [8a7ed180c0](https://linux-hardware.org/?probe=8a7ed180c0) | May 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3ba3358e4d](https://linux-hardware.org/?probe=3ba3358e4d) | May 02, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| Dell          | Latitude E5520              | Notebook    | [43e2d970b5](https://linux-hardware.org/?probe=43e2d970b5) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [f543ce6c65](https://linux-hardware.org/?probe=f543ce6c65) | Apr 29, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [f2b702b631](https://linux-hardware.org/?probe=f2b702b631) | Apr 28, 2023 |
| Dell          | Latitude 7420               | Notebook    | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| Dell          | 040DDP A00                  | Desktop     | [8595139862](https://linux-hardware.org/?probe=8595139862) | Apr 25, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [84ae892fb4](https://linux-hardware.org/?probe=84ae892fb4) | Apr 19, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [030eff02bb](https://linux-hardware.org/?probe=030eff02bb) | Apr 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88b9080a8c](https://linux-hardware.org/?probe=88b9080a8c) | Apr 17, 2023 |
| Dell          | Latitude 7420               | Notebook    | [1b2360944e](https://linux-hardware.org/?probe=1b2360944e) | Apr 17, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [690ed7960a](https://linux-hardware.org/?probe=690ed7960a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [12f634cf42](https://linux-hardware.org/?probe=12f634cf42) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63574c5adf](https://linux-hardware.org/?probe=63574c5adf) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [beeb850c3b](https://linux-hardware.org/?probe=beeb850c3b) | Apr 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f2d5671ba5](https://linux-hardware.org/?probe=f2d5671ba5) | Apr 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [13d6602e92](https://linux-hardware.org/?probe=13d6602e92) | Apr 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ab9916feea](https://linux-hardware.org/?probe=ab9916feea) | Apr 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7e97eb6308](https://linux-hardware.org/?probe=7e97eb6308) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8e927ead89](https://linux-hardware.org/?probe=8e927ead89) | Mar 30, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [889ef05f86](https://linux-hardware.org/?probe=889ef05f86) | Mar 30, 2023 |
| Dell          | 0TP412                      | Desktop     | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [2aff972d11](https://linux-hardware.org/?probe=2aff972d11) | Mar 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [4f8515b9ed](https://linux-hardware.org/?probe=4f8515b9ed) | Mar 27, 2023 |
| HP            | 0B54h D                     | Desktop     | [3edc678017](https://linux-hardware.org/?probe=3edc678017) | Mar 26, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [b49dbdfa77](https://linux-hardware.org/?probe=b49dbdfa77) | Mar 25, 2023 |
| Timi          | A35S                        | Notebook    | [92022a5fa2](https://linux-hardware.org/?probe=92022a5fa2) | Mar 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [0550174a08](https://linux-hardware.org/?probe=0550174a08) | Mar 23, 2023 |
| HP            | 8715                        | Mini pc     | [9ce704a4b9](https://linux-hardware.org/?probe=9ce704a4b9) | Mar 23, 2023 |
| MSI           | GP72 7RE                    | Notebook    | [729f2297cb](https://linux-hardware.org/?probe=729f2297cb) | Mar 23, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Dell          | Latitude 7420               | Notebook    | [ac9a26d11c](https://linux-hardware.org/?probe=ac9a26d11c) | Mar 20, 2023 |
| HP            | 83E9                        | Desktop     | [a93c800fa1](https://linux-hardware.org/?probe=a93c800fa1) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Samsung       | 940XFG                      | Notebook    | [566a4046f6](https://linux-hardware.org/?probe=566a4046f6) | Mar 18, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [9d0ac027df](https://linux-hardware.org/?probe=9d0ac027df) | Mar 14, 2023 |
| Google        | Reks                        | Notebook    | [56296236c5](https://linux-hardware.org/?probe=56296236c5) | Mar 12, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [f6da200721](https://linux-hardware.org/?probe=f6da200721) | Mar 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [56e5783575](https://linux-hardware.org/?probe=56e5783575) | Mar 11, 2023 |
| HP            | ProBook 4330s               | Notebook    | [00d887061a](https://linux-hardware.org/?probe=00d887061a) | Mar 10, 2023 |
| Google        | Reks                        | Notebook    | [f877db79d3](https://linux-hardware.org/?probe=f877db79d3) | Mar 09, 2023 |
| Intel         | ArcherCity                  | Server      | [3ddb00da94](https://linux-hardware.org/?probe=3ddb00da94) | Mar 08, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [a541fe5881](https://linux-hardware.org/?probe=a541fe5881) | Mar 07, 2023 |
| Dell          | Latitude 7420               | Notebook    | [00ef839a27](https://linux-hardware.org/?probe=00ef839a27) | Mar 06, 2023 |
| Dell          | Latitude 7420               | Notebook    | [18b4bfe200](https://linux-hardware.org/?probe=18b4bfe200) | Mar 06, 2023 |
| Dell          | 0JC474                      | Desktop     | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [8078d7ca28](https://linux-hardware.org/?probe=8078d7ca28) | Mar 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [d70aeca173](https://linux-hardware.org/?probe=d70aeca173) | Mar 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a23a00a71e](https://linux-hardware.org/?probe=a23a00a71e) | Mar 02, 2023 |
| Dell          | Latitude 7420               | Notebook    | [49bdd8711f](https://linux-hardware.org/?probe=49bdd8711f) | Mar 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [2b007293f7](https://linux-hardware.org/?probe=2b007293f7) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd415a086a](https://linux-hardware.org/?probe=bd415a086a) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dcaa80ec62](https://linux-hardware.org/?probe=dcaa80ec62) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Intel         | NUC7i5BNB J31144-313        | Mini pc     | [91405b88cc](https://linux-hardware.org/?probe=91405b88cc) | Feb 27, 2023 |
| Dell          | Latitude 7420               | Notebook    | [d3af27a0ac](https://linux-hardware.org/?probe=d3af27a0ac) | Feb 27, 2023 |
| HP            | 655                         | Notebook    | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d032f0a547](https://linux-hardware.org/?probe=d032f0a547) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [b6f7c77e33](https://linux-hardware.org/?probe=b6f7c77e33) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [bb18722cf2](https://linux-hardware.org/?probe=bb18722cf2) | Feb 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1d62ae4e43](https://linux-hardware.org/?probe=1d62ae4e43) | Feb 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [813066eda5](https://linux-hardware.org/?probe=813066eda5) | Feb 19, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [0496d0bbcf](https://linux-hardware.org/?probe=0496d0bbcf) | Feb 18, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [ba5a46ec10](https://linux-hardware.org/?probe=ba5a46ec10) | Feb 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [fdab522500](https://linux-hardware.org/?probe=fdab522500) | Feb 17, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [dd863b4bdf](https://linux-hardware.org/?probe=dd863b4bdf) | Feb 17, 2023 |
| Foxconn       | H67M-S/H67M-V/H67M          | Desktop     | [78dc1c5856](https://linux-hardware.org/?probe=78dc1c5856) | Feb 17, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [8de835c5da](https://linux-hardware.org/?probe=8de835c5da) | Feb 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fb6daef60c](https://linux-hardware.org/?probe=fb6daef60c) | Feb 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3206e7be82](https://linux-hardware.org/?probe=3206e7be82) | Feb 16, 2023 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [4891d8306b](https://linux-hardware.org/?probe=4891d8306b) | Feb 15, 2023 |
| ASUSTek       | PN53                        | Mini pc     | [73f7fb3f85](https://linux-hardware.org/?probe=73f7fb3f85) | Feb 15, 2023 |
| Dell          | G15 5520                    | Notebook    | [a5966eaac0](https://linux-hardware.org/?probe=a5966eaac0) | Feb 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [cc77f75f3d](https://linux-hardware.org/?probe=cc77f75f3d) | Feb 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [011e8929fa](https://linux-hardware.org/?probe=011e8929fa) | Feb 15, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [e689bce0ca](https://linux-hardware.org/?probe=e689bce0ca) | Feb 14, 2023 |
| Dell          | 051FJ8 A00                  | Desktop     | [bc1c7ec97f](https://linux-hardware.org/?probe=bc1c7ec97f) | Feb 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7e81f35584](https://linux-hardware.org/?probe=7e81f35584) | Feb 13, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [b1b8672218](https://linux-hardware.org/?probe=b1b8672218) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [08820689e8](https://linux-hardware.org/?probe=08820689e8) | Feb 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c17ac89917](https://linux-hardware.org/?probe=c17ac89917) | Feb 11, 2023 |
| MSI           | X470 GAMING PRO             | Desktop     | [a53ab3e915](https://linux-hardware.org/?probe=a53ab3e915) | Feb 10, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [181833b556](https://linux-hardware.org/?probe=181833b556) | Feb 09, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [6a589cafec](https://linux-hardware.org/?probe=6a589cafec) | Feb 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [43b52ad56f](https://linux-hardware.org/?probe=43b52ad56f) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [275ce1a7fc](https://linux-hardware.org/?probe=275ce1a7fc) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef988ae85](https://linux-hardware.org/?probe=aef988ae85) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0f24e9c32c](https://linux-hardware.org/?probe=0f24e9c32c) | Feb 04, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a838bfb720](https://linux-hardware.org/?probe=a838bfb720) | Feb 04, 2023 |
| Shenzhen W... | AERO 5 Lite Mini PC         | Mini pc     | [cd8f74acd2](https://linux-hardware.org/?probe=cd8f74acd2) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [50727dbbde](https://linux-hardware.org/?probe=50727dbbde) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0b0eaa5c48](https://linux-hardware.org/?probe=0b0eaa5c48) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe2d2d279](https://linux-hardware.org/?probe=2fe2d2d279) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0323a2bd47](https://linux-hardware.org/?probe=0323a2bd47) | Jan 27, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [a0493c6731](https://linux-hardware.org/?probe=a0493c6731) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [8ae5c7adec](https://linux-hardware.org/?probe=8ae5c7adec) | Jan 25, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b87a9b3447](https://linux-hardware.org/?probe=b87a9b3447) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7b23698a1e](https://linux-hardware.org/?probe=7b23698a1e) | Jan 24, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [09735072af](https://linux-hardware.org/?probe=09735072af) | Jan 23, 2023 |
| Dell          | Latitude 7420               | Notebook    | [dc99eb6c92](https://linux-hardware.org/?probe=dc99eb6c92) | Jan 23, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [7fb655b498](https://linux-hardware.org/?probe=7fb655b498) | Jan 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [397b4da9ab](https://linux-hardware.org/?probe=397b4da9ab) | Jan 21, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [93932bdc92](https://linux-hardware.org/?probe=93932bdc92) | Jan 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ad3ad8258](https://linux-hardware.org/?probe=2ad3ad8258) | Jan 20, 2023 |
| Dell          | G5 5590                     | Notebook    | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude 5510               | Notebook    | [c9738f8691](https://linux-hardware.org/?probe=c9738f8691) | Jan 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [b5b4cde08e](https://linux-hardware.org/?probe=b5b4cde08e) | Jan 18, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [fa1a881ee9](https://linux-hardware.org/?probe=fa1a881ee9) | Jan 17, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6941e3520e](https://linux-hardware.org/?probe=6941e3520e) | Jan 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [24d62d6974](https://linux-hardware.org/?probe=24d62d6974) | Jan 17, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [5905971b70](https://linux-hardware.org/?probe=5905971b70) | Jan 16, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [389b01b49a](https://linux-hardware.org/?probe=389b01b49a) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c3d300ccc](https://linux-hardware.org/?probe=4c3d300ccc) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1ad37ae4cc](https://linux-hardware.org/?probe=1ad37ae4cc) | Jan 13, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [d390e11930](https://linux-hardware.org/?probe=d390e11930) | Jan 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [a181d83115](https://linux-hardware.org/?probe=a181d83115) | Jan 11, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4ce659b05d](https://linux-hardware.org/?probe=4ce659b05d) | Jan 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| Star Labs     | Lite                        | Notebook    | [6614e226df](https://linux-hardware.org/?probe=6614e226df) | Jan 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef797585c](https://linux-hardware.org/?probe=aef797585c) | Jan 09, 2023 |
| Dell          | Latitude 7420               | Notebook    | [cd159088a3](https://linux-hardware.org/?probe=cd159088a3) | Jan 09, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [e85dcf8a22](https://linux-hardware.org/?probe=e85dcf8a22) | Jan 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [ec306ce0f9](https://linux-hardware.org/?probe=ec306ce0f9) | Jan 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [81269f2363](https://linux-hardware.org/?probe=81269f2363) | Jan 04, 2023 |
| Dell          | 0JP3NX A00                  | Desktop     | [21b5ec2d81](https://linux-hardware.org/?probe=21b5ec2d81) | Jan 03, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [1b8d741ea3](https://linux-hardware.org/?probe=1b8d741ea3) | Jan 03, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a51048ad0a](https://linux-hardware.org/?probe=a51048ad0a) | Jan 01, 2023 |
| Samsung       | 940XFG                      | Notebook    | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e7ac43e8c3](https://linux-hardware.org/?probe=e7ac43e8c3) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4d613961a4](https://linux-hardware.org/?probe=4d613961a4) | Dec 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1780cf9c13](https://linux-hardware.org/?probe=1780cf9c13) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c93684da4d](https://linux-hardware.org/?probe=c93684da4d) | Dec 29, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c9cadd190](https://linux-hardware.org/?probe=5c9cadd190) | Dec 28, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5ea84f62cb](https://linux-hardware.org/?probe=5ea84f62cb) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3fc3ad1b46](https://linux-hardware.org/?probe=3fc3ad1b46) | Dec 25, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [afb738446f](https://linux-hardware.org/?probe=afb738446f) | Dec 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [91a9d07c9f](https://linux-hardware.org/?probe=91a9d07c9f) | Dec 22, 2022 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0b63acf3b2](https://linux-hardware.org/?probe=0b63acf3b2) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [660c9e5023](https://linux-hardware.org/?probe=660c9e5023) | Dec 20, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [54fbda3732](https://linux-hardware.org/?probe=54fbda3732) | Dec 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [da494e2be3](https://linux-hardware.org/?probe=da494e2be3) | Dec 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1bd00059e2](https://linux-hardware.org/?probe=1bd00059e2) | Dec 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7236ad8a5d](https://linux-hardware.org/?probe=7236ad8a5d) | Dec 17, 2022 |
| Dell          | Latitude 7420               | Notebook    | [60f07d5a45](https://linux-hardware.org/?probe=60f07d5a45) | Dec 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2991f8736b](https://linux-hardware.org/?probe=2991f8736b) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [69776fdb13](https://linux-hardware.org/?probe=69776fdb13) | Dec 16, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [09c89a9bef](https://linux-hardware.org/?probe=09c89a9bef) | Dec 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed707b6698](https://linux-hardware.org/?probe=ed707b6698) | Dec 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c91212b8ed](https://linux-hardware.org/?probe=c91212b8ed) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [88196a712d](https://linux-hardware.org/?probe=88196a712d) | Dec 07, 2022 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [57e8e4ab79](https://linux-hardware.org/?probe=57e8e4ab79) | Dec 06, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [b85ac74a3f](https://linux-hardware.org/?probe=b85ac74a3f) | Dec 05, 2022 |
| Dell          | Latitude 7290               | Notebook    | [3f0e476980](https://linux-hardware.org/?probe=3f0e476980) | Dec 04, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Toshiba       | Satellite C50D-A-138        | Notebook    | [ccda846d5e](https://linux-hardware.org/?probe=ccda846d5e) | Dec 03, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [9887f68589](https://linux-hardware.org/?probe=9887f68589) | Dec 03, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [7bdc87a5cc](https://linux-hardware.org/?probe=7bdc87a5cc) | Dec 02, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [d17ff52554](https://linux-hardware.org/?probe=d17ff52554) | Dec 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [080e04d17d](https://linux-hardware.org/?probe=080e04d17d) | Dec 02, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c4ae439087](https://linux-hardware.org/?probe=c4ae439087) | Nov 30, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5c395ef8a4](https://linux-hardware.org/?probe=5c395ef8a4) | Nov 26, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [0c97f1e481](https://linux-hardware.org/?probe=0c97f1e481) | Nov 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [587e23a674](https://linux-hardware.org/?probe=587e23a674) | Nov 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4ac6dbf9b](https://linux-hardware.org/?probe=a4ac6dbf9b) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c3cacc3ed6](https://linux-hardware.org/?probe=c3cacc3ed6) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [11dbbdfcc1](https://linux-hardware.org/?probe=11dbbdfcc1) | Nov 15, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [02aab6ab70](https://linux-hardware.org/?probe=02aab6ab70) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | Notebook    | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [74a1e6875a](https://linux-hardware.org/?probe=74a1e6875a) | Nov 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c03daa3621](https://linux-hardware.org/?probe=c03daa3621) | Nov 08, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a5700bebdf](https://linux-hardware.org/?probe=a5700bebdf) | Nov 03, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5d89464b05](https://linux-hardware.org/?probe=5d89464b05) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a4354f496c](https://linux-hardware.org/?probe=a4354f496c) | Nov 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [5cf615d5b2](https://linux-hardware.org/?probe=5cf615d5b2) | Nov 02, 2022 |
| MSI           | Z170M MORTAR                | Desktop     | [041dbc2c18](https://linux-hardware.org/?probe=041dbc2c18) | Oct 31, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | Notebook    | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [8b457c11e8](https://linux-hardware.org/?probe=8b457c11e8) | Oct 23, 2022 |
| Dell          | Latitude E6440              | Notebook    | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [ac2c9383c0](https://linux-hardware.org/?probe=ac2c9383c0) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| Dell          | Latitude 7400               | Notebook    | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | Notebook    | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [e464adc2d9](https://linux-hardware.org/?probe=e464adc2d9) | Oct 11, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | Notebook    | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | 21D0                        | Desktop     | [6815e2bba2](https://linux-hardware.org/?probe=6815e2bba2) | Oct 04, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [26df10ca7d](https://linux-hardware.org/?probe=26df10ca7d) | Oct 02, 2022 |
| Timi          | TM1709                      | Notebook    | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | Notebook    | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [172fd1874d](https://linux-hardware.org/?probe=172fd1874d) | Sep 20, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [da0b586e04](https://linux-hardware.org/?probe=da0b586e04) | Sep 20, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b389a760a8](https://linux-hardware.org/?probe=b389a760a8) | Sep 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [4feb69184d](https://linux-hardware.org/?probe=4feb69184d) | Sep 02, 2022 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [bfee1a862f](https://linux-hardware.org/?probe=bfee1a862f) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Pavilion m6                 | Notebook    | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | Notebook    | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [296fc14c83](https://linux-hardware.org/?probe=296fc14c83) | Aug 26, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34d2d4f66e](https://linux-hardware.org/?probe=34d2d4f66e) | Aug 24, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [caf9167ca7](https://linux-hardware.org/?probe=caf9167ca7) | Aug 16, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6d1b561c11](https://linux-hardware.org/?probe=6d1b561c11) | Aug 16, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | Notebook    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | Notebook    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | Notebook    | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Dell          | 0JP3NX A00                  | Desktop     | [531e4340a6](https://linux-hardware.org/?probe=531e4340a6) | Aug 07, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd2dbeaa0e](https://linux-hardware.org/?probe=bd2dbeaa0e) | Aug 02, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d83f785b08](https://linux-hardware.org/?probe=d83f785b08) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [033c284273](https://linux-hardware.org/?probe=033c284273) | Jul 19, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8d0399bc8d](https://linux-hardware.org/?probe=8d0399bc8d) | Jul 17, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ef61582503](https://linux-hardware.org/?probe=ef61582503) | Jul 16, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e9be99b44d](https://linux-hardware.org/?probe=e9be99b44d) | Jul 14, 2022 |
| Jumper        | EZbook                      | Notebook    | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | Notebook    | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [028b64776a](https://linux-hardware.org/?probe=028b64776a) | Jun 15, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [eef8a87283](https://linux-hardware.org/?probe=eef8a87283) | Jun 15, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [674cb88747](https://linux-hardware.org/?probe=674cb88747) | Jun 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| ASUSTek       | Maximus VII IMPACT          | Desktop     | [8b0844f325](https://linux-hardware.org/?probe=8b0844f325) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [522da9476b](https://linux-hardware.org/?probe=522da9476b) | May 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [8471800bb3](https://linux-hardware.org/?probe=8471800bb3) | May 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [0d7682cb61](https://linux-hardware.org/?probe=0d7682cb61) | May 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [373e009d3b](https://linux-hardware.org/?probe=373e009d3b) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [6836f79bdf](https://linux-hardware.org/?probe=6836f79bdf) | May 08, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [41cc4d30d4](https://linux-hardware.org/?probe=41cc4d30d4) | May 08, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | H55M-E23                    | Desktop     | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5e1b40c8b5](https://linux-hardware.org/?probe=5e1b40c8b5) | Apr 25, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | Notebook    | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [346c9b6c59](https://linux-hardware.org/?probe=346c9b6c59) | Apr 14, 2022 |
| Dell          | Latitude E6520              | Notebook    | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [92e810b1dd](https://linux-hardware.org/?probe=92e810b1dd) | Apr 13, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [714baddf6f](https://linux-hardware.org/?probe=714baddf6f) | Apr 06, 2022 |
| Lenovo        | 312A SDK0J40700 WIN 3258... | Desktop     | [a645768047](https://linux-hardware.org/?probe=a645768047) | Apr 05, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | Notebook    | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3e5267891f](https://linux-hardware.org/?probe=3e5267891f) | Apr 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0f98a36a43](https://linux-hardware.org/?probe=0f98a36a43) | Mar 30, 2022 |
| Dell          | Latitude E5440              | Notebook    | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [949d5ffcf5](https://linux-hardware.org/?probe=949d5ffcf5) | Mar 26, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [c185ef78b1](https://linux-hardware.org/?probe=c185ef78b1) | Mar 22, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [45c6461d6c](https://linux-hardware.org/?probe=45c6461d6c) | Mar 22, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [e117237c38](https://linux-hardware.org/?probe=e117237c38) | Mar 21, 2022 |
| Rockchip      | Unknown                     | Soc         | [fcef507e8e](https://linux-hardware.org/?probe=fcef507e8e) | Mar 18, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5723ec8b7](https://linux-hardware.org/?probe=f5723ec8b7) | Mar 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [27548876c6](https://linux-hardware.org/?probe=27548876c6) | Mar 11, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4c4afb883e](https://linux-hardware.org/?probe=4c4afb883e) | Mar 09, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0eaf02ff7d](https://linux-hardware.org/?probe=0eaf02ff7d) | Mar 07, 2022 |
| Dell          | Latitude 9420               | Notebook    | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [34b97f062b](https://linux-hardware.org/?probe=34b97f062b) | Mar 01, 2022 |
| HP            | 21D0                        | Desktop     | [448912eeb9](https://linux-hardware.org/?probe=448912eeb9) | Feb 24, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6dd3795cad](https://linux-hardware.org/?probe=6dd3795cad) | Feb 24, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | Notebook    | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ace22bd471](https://linux-hardware.org/?probe=ace22bd471) | Feb 11, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb5bd32928](https://linux-hardware.org/?probe=bb5bd32928) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2c93e69093](https://linux-hardware.org/?probe=2c93e69093) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [45922e4586](https://linux-hardware.org/?probe=45922e4586) | Feb 04, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [3ecad8d7e4](https://linux-hardware.org/?probe=3ecad8d7e4) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | Notebook    | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | 0X4H68 A00                  | Desktop     | [0e6a0c4725](https://linux-hardware.org/?probe=0e6a0c4725) | Jan 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASRock        | Z68 Pro3                    | Desktop     | [4cdd6daf44](https://linux-hardware.org/?probe=4cdd6daf44) | Jan 19, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c8932dbfd0](https://linux-hardware.org/?probe=c8932dbfd0) | Jan 15, 2022 |
| Intel         | DG45ID AAE46743-302         | Desktop     | [ab40e8dd7d](https://linux-hardware.org/?probe=ab40e8dd7d) | Jan 14, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8c319cd6fc](https://linux-hardware.org/?probe=8c319cd6fc) | Jan 11, 2022 |
| Notebook      | P15SM                       | Notebook    | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4fad903d2a](https://linux-hardware.org/?probe=4fad903d2a) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | Notebook    | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [4894e2c956](https://linux-hardware.org/?probe=4894e2c956) | Jan 02, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aea80bda1f](https://linux-hardware.org/?probe=aea80bda1f) | Jan 01, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4161b37157](https://linux-hardware.org/?probe=4161b37157) | Dec 30, 2021 |
| Lenovo        | ThinkPad X220 4291W99       | Notebook    | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [296af779e4](https://linux-hardware.org/?probe=296af779e4) | Dec 20, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7230ad27b7](https://linux-hardware.org/?probe=7230ad27b7) | Dec 19, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [7b6327d329](https://linux-hardware.org/?probe=7b6327d329) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | Notebook    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | Notebook    | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Nvidia        | Tegra                       | Soc         | [30c09e0585](https://linux-hardware.org/?probe=30c09e0585) | Dec 17, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [69b4695e8d](https://linux-hardware.org/?probe=69b4695e8d) | Dec 04, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [bfead2c865](https://linux-hardware.org/?probe=bfead2c865) | Dec 04, 2021 |
| Acer          | AOD255                      | Notebook    | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | Notebook    | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bb51358294](https://linux-hardware.org/?probe=bb51358294) | Nov 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | Notebook    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [00ac329183](https://linux-hardware.org/?probe=00ac329183) | Oct 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [3e574fa012](https://linux-hardware.org/?probe=3e574fa012) | Oct 25, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | Notebook    | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4add26ac8c](https://linux-hardware.org/?probe=4add26ac8c) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| HP            | 21D0                        | Desktop     | [1dbb2b4a2d](https://linux-hardware.org/?probe=1dbb2b4a2d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | Notebook    | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [74cbbcac9f](https://linux-hardware.org/?probe=74cbbcac9f) | Oct 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| MSI           | MS-7270                     | Desktop     | [4281e009bb](https://linux-hardware.org/?probe=4281e009bb) | Oct 05, 2021 |
| HP            | 1998                        | Desktop     | [74a28b051a](https://linux-hardware.org/?probe=74a28b051a) | Oct 03, 2021 |
| Apple         | MacBookPro5,3               | Notebook    | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [5acbf68626](https://linux-hardware.org/?probe=5acbf68626) | Sep 25, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | Notebook    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [7500e17316](https://linux-hardware.org/?probe=7500e17316) | Sep 11, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | Notebook    | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [feec038877](https://linux-hardware.org/?probe=feec038877) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | Notebook    | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f1b601400c](https://linux-hardware.org/?probe=f1b601400c) | Sep 01, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [88012fdf33](https://linux-hardware.org/?probe=88012fdf33) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | Notebook    | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | Notebook    | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| MSI           | B450 GAMING PLUS            | Desktop     | [f5d2b51d19](https://linux-hardware.org/?probe=f5d2b51d19) | Aug 16, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Dell          | 0X9M3X A01                  | Desktop     | [b5b9c80c53](https://linux-hardware.org/?probe=b5b9c80c53) | Aug 14, 2021 |
| Sony          | VPCCB35FG                   | Notebook    | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1ea279df08](https://linux-hardware.org/?probe=1ea279df08) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | Notebook    | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [32e0ae8af0](https://linux-hardware.org/?probe=32e0ae8af0) | Aug 03, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [f8c48b22e6](https://linux-hardware.org/?probe=f8c48b22e6) | Aug 02, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [69869dec40](https://linux-hardware.org/?probe=69869dec40) | Jul 27, 2021 |
| Dell          | Studio XPS 1640             | Notebook    | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| ASRock        | J4105M                      | Desktop     | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | Desktop     | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Dell          | Latitude 7370               | Notebook    | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | Notebook    | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| ASRock        | Z77 Extreme3                | Desktop     | [ecd7ec8f36](https://linux-hardware.org/?probe=ecd7ec8f36) | Jul 02, 2021 |
| Entroware     | Apollo                      | Notebook    | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [27fea5c8cb](https://linux-hardware.org/?probe=27fea5c8cb) | Jun 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [1ccc05a479](https://linux-hardware.org/?probe=1ccc05a479) | Jun 09, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f8241fa3ce](https://linux-hardware.org/?probe=f8241fa3ce) | Jun 08, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | Notebook    | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | Notebook    | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [6c770833c9](https://linux-hardware.org/?probe=6c770833c9) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | Notebook    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | Notebook    | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | 07F37C A01                  | Desktop     | [baba8a29ac](https://linux-hardware.org/?probe=baba8a29ac) | Jun 02, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | Notebook    | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| MSI           | MS-7270                     | Desktop     | [7cc66e3a90](https://linux-hardware.org/?probe=7cc66e3a90) | May 29, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3c83289b45](https://linux-hardware.org/?probe=3c83289b45) | May 28, 2021 |
| HP            | Pavilion 15                 | Notebook    | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | Notebook    | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 3397                        | Desktop     | [ae9a8581c5](https://linux-hardware.org/?probe=ae9a8581c5) | May 23, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [f7c5833c2a](https://linux-hardware.org/?probe=f7c5833c2a) | May 23, 2021 |
| HP            | 15                          | Notebook    | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | Notebook    | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [6f9a85a086](https://linux-hardware.org/?probe=6f9a85a086) | May 21, 2021 |
| Shuttle       | FS35V4                      | Desktop     | [acd3144c20](https://linux-hardware.org/?probe=acd3144c20) | May 21, 2021 |
| HP            | 18E5                        | Desktop     | [6cbae0f799](https://linux-hardware.org/?probe=6cbae0f799) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ea97f7d05d](https://linux-hardware.org/?probe=ea97f7d05d) | May 20, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [824ec14630](https://linux-hardware.org/?probe=824ec14630) | May 20, 2021 |
| Entroware     | Proteus                     | Notebook    | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | Notebook    | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [452f706571](https://linux-hardware.org/?probe=452f706571) | May 07, 2021 |
| HP            | HDX 18                      | Notebook    | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| ASRock        | Z490M Pro4                  | Desktop     | [d1d4f84e0a](https://linux-hardware.org/?probe=d1d4f84e0a) | May 03, 2021 |
| HP            | EliteBook Folio G1          | Notebook    | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [fe576d54b4](https://linux-hardware.org/?probe=fe576d54b4) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e651f5da2c](https://linux-hardware.org/?probe=e651f5da2c) | Apr 23, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [be651d63a0](https://linux-hardware.org/?probe=be651d63a0) | Apr 19, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0ceacbca21](https://linux-hardware.org/?probe=0ceacbca21) | Apr 17, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | Notebook    | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [8253ac8502](https://linux-hardware.org/?probe=8253ac8502) | Apr 10, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2e946e600e](https://linux-hardware.org/?probe=2e946e600e) | Apr 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [93033ed87e](https://linux-hardware.org/?probe=93033ed87e) | Apr 04, 2021 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [6b926d1195](https://linux-hardware.org/?probe=6b926d1195) | Apr 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [6917221b5b](https://linux-hardware.org/?probe=6917221b5b) | Apr 02, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [9e21f67ab7](https://linux-hardware.org/?probe=9e21f67ab7) | Mar 28, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | Notebook    | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | Notebook    | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [1b571fd1c4](https://linux-hardware.org/?probe=1b571fd1c4) | Mar 18, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [e5a6c9dcb9](https://linux-hardware.org/?probe=e5a6c9dcb9) | Mar 17, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| Pegatron      | 2A94h                       | Desktop     | [b035a149a3](https://linux-hardware.org/?probe=b035a149a3) | Mar 02, 2021 |
| Medion        | MS-7646                     | Desktop     | [5ca2e128b6](https://linux-hardware.org/?probe=5ca2e128b6) | Feb 24, 2021 |
| HP            | Pavilion m6                 | Notebook    | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | Notebook    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f2450a3b0](https://linux-hardware.org/?probe=8f2450a3b0) | Feb 20, 2021 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [878e82f1a3](https://linux-hardware.org/?probe=878e82f1a3) | Feb 19, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | Notebook    | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [78c7860103](https://linux-hardware.org/?probe=78c7860103) | Feb 10, 2021 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [8647ccdbef](https://linux-hardware.org/?probe=8647ccdbef) | Feb 10, 2021 |
| MSI           | 2AE0                        | Desktop     | [374ff27ab8](https://linux-hardware.org/?probe=374ff27ab8) | Feb 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6ef4606f95](https://linux-hardware.org/?probe=6ef4606f95) | Feb 09, 2021 |
| HP            | 1495                        | Desktop     | [d8d36f4b2b](https://linux-hardware.org/?probe=d8d36f4b2b) | Feb 08, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [51ede3687a](https://linux-hardware.org/?probe=51ede3687a) | Feb 05, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Samsung       | Galaxy TabPro S             | Tablet      | [4e4ef907a0](https://linux-hardware.org/?probe=4e4ef907a0) | Feb 05, 2021 |
| Dell          | 0HY9JP A02                  | Desktop     | [6c4261b08f](https://linux-hardware.org/?probe=6c4261b08f) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4502d7365](https://linux-hardware.org/?probe=d4502d7365) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2c59be484e](https://linux-hardware.org/?probe=2c59be484e) | Jan 22, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [1dbf9cced7](https://linux-hardware.org/?probe=1dbf9cced7) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [9ce5eab595](https://linux-hardware.org/?probe=9ce5eab595) | Jan 16, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [192f01dd70](https://linux-hardware.org/?probe=192f01dd70) | Jan 16, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | Notebook    | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | Notebook    | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [54b2f4c522](https://linux-hardware.org/?probe=54b2f4c522) | Jan 11, 2021 |
| MSI           | X470 GAMING PRO             | Desktop     | [d7528e4806](https://linux-hardware.org/?probe=d7528e4806) | Jan 09, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | Notebook    | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Intel         | NUC10i3FNB K61362-302       | Mini pc     | [59440917d2](https://linux-hardware.org/?probe=59440917d2) | Jan 01, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [b6ffae8f7a](https://linux-hardware.org/?probe=b6ffae8f7a) | Dec 27, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Dell          | System XPS L502X            | Notebook    | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [d1e772d769](https://linux-hardware.org/?probe=d1e772d769) | Dec 11, 2020 |
| Acer          | Aspire 5551                 | Notebook    | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | Notebook    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| MSI           | MS-7270                     | Desktop     | [b4e45eae99](https://linux-hardware.org/?probe=b4e45eae99) | Nov 26, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | Notebook    | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | Notebook    | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | Notebook    | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | Notebook    | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | Notebook    | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | Notebook    | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | Notebook    | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d8379e8abb](https://linux-hardware.org/?probe=d8379e8abb) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | Notebook    | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | Notebook    | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| MSI           | MS-7270                     | Desktop     | [c70e52b025](https://linux-hardware.org/?probe=c70e52b025) | Nov 13, 2020 |
| Dell          | Latitude E6420              | Notebook    | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| HP            | 1495                        | Desktop     | [a250ea93d5](https://linux-hardware.org/?probe=a250ea93d5) | Nov 10, 2020 |
| Notebook      | NL40_50CU                   | Notebook    | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| MSI           | MS-7270                     | Desktop     | [97556dedc3](https://linux-hardware.org/?probe=97556dedc3) | Nov 05, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [eac2b32ee0](https://linux-hardware.org/?probe=eac2b32ee0) | Nov 04, 2020 |
| System76      | Galago Pro                  | Notebook    | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | Notebook    | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Dell          | Dimension 5100              | Desktop     | [f18393d9aa](https://linux-hardware.org/?probe=f18393d9aa) | Nov 03, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3be1cd15b1](https://linux-hardware.org/?probe=3be1cd15b1) | Oct 30, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | Notebook    | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | Notebook    | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| Apple         | Mac-F2238AC8                | All in one  | [e9e4822309](https://linux-hardware.org/?probe=e9e4822309) | Oct 28, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | Notebook    | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | Notebook    | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| HP            | 1497                        | Desktop     | [dea5079fad](https://linux-hardware.org/?probe=dea5079fad) | Oct 19, 2020 |
| Dell          | 0RY206                      | Desktop     | [4e0283b4c8](https://linux-hardware.org/?probe=4e0283b4c8) | Oct 18, 2020 |
| Dell          | 0RY206                      | Desktop     | [5d45dd253e](https://linux-hardware.org/?probe=5d45dd253e) | Oct 18, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| HP            | 1497                        | Desktop     | [8dd5fc52bd](https://linux-hardware.org/?probe=8dd5fc52bd) | Oct 15, 2020 |
| Nvidia        | Tegra                       | Soc         | [9b157b83a5](https://linux-hardware.org/?probe=9b157b83a5) | Oct 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [bd7a8f0f96](https://linux-hardware.org/?probe=bd7a8f0f96) | Oct 15, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Dell          | Dimension 5100              | Desktop     | [5b80714363](https://linux-hardware.org/?probe=5b80714363) | Oct 14, 2020 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ab8c149b9f](https://linux-hardware.org/?probe=ab8c149b9f) | Oct 14, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [08619ece44](https://linux-hardware.org/?probe=08619ece44) | Oct 14, 2020 |
| Apple         | MacBook5,1                  | Notebook    | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d245d1c5a5](https://linux-hardware.org/?probe=d245d1c5a5) | Oct 06, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [d1cf757d40](https://linux-hardware.org/?probe=d1cf757d40) | Oct 05, 2020 |
| HP            | 1495                        | Desktop     | [2389a49dc0](https://linux-hardware.org/?probe=2389a49dc0) | Oct 05, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [1e8497692d](https://linux-hardware.org/?probe=1e8497692d) | Oct 02, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [c2148ec054](https://linux-hardware.org/?probe=c2148ec054) | Oct 01, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [c22330bac3](https://linux-hardware.org/?probe=c22330bac3) | Sep 26, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a2c5c1ea67](https://linux-hardware.org/?probe=a2c5c1ea67) | Sep 18, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [3eba500997](https://linux-hardware.org/?probe=3eba500997) | Sep 15, 2020 |
| HP            | G70                         | Notebook    | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [20c0d6785b](https://linux-hardware.org/?probe=20c0d6785b) | Sep 11, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [253e97e06c](https://linux-hardware.org/?probe=253e97e06c) | Sep 10, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | Notebook    | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | Notebook    | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| Unknown       | RS780-SB700 Unknox          | Desktop     | [a084e40027](https://linux-hardware.org/?probe=a084e40027) | Aug 30, 2020 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [f5a642ebbb](https://linux-hardware.org/?probe=f5a642ebbb) | Aug 28, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [f710d270fe](https://linux-hardware.org/?probe=f710d270fe) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [f25aa5934e](https://linux-hardware.org/?probe=f25aa5934e) | Aug 19, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [ebb3d9d7aa](https://linux-hardware.org/?probe=ebb3d9d7aa) | Aug 15, 2020 |
| Gigabyte      | G1.Sniper                   | Desktop     | [8d1bc7ce18](https://linux-hardware.org/?probe=8d1bc7ce18) | Aug 15, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [e1529e585d](https://linux-hardware.org/?probe=e1529e585d) | Aug 14, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [a20482ea67](https://linux-hardware.org/?probe=a20482ea67) | Aug 12, 2020 |
| ASUSTek       | ZN241IC                     | All in one  | [46c001d058](https://linux-hardware.org/?probe=46c001d058) | Aug 10, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [92a135b7d2](https://linux-hardware.org/?probe=92a135b7d2) | Aug 09, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [c3fbdc22c8](https://linux-hardware.org/?probe=c3fbdc22c8) | Aug 09, 2020 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [4a551e8c6b](https://linux-hardware.org/?probe=4a551e8c6b) | Aug 09, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Dell          | 0T568R A00                  | Desktop     | [fb620a31fc](https://linux-hardware.org/?probe=fb620a31fc) | Aug 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [5101109869](https://linux-hardware.org/?probe=5101109869) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [cb782efc58](https://linux-hardware.org/?probe=cb782efc58) | Aug 07, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| HP            | 8648                        | Desktop     | [e034f483fc](https://linux-hardware.org/?probe=e034f483fc) | Aug 06, 2020 |
| Dell          | 0P4T42 A00                  | All in one  | [4924eefd27](https://linux-hardware.org/?probe=4924eefd27) | Aug 03, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [b5911c66d7](https://linux-hardware.org/?probe=b5911c66d7) | Aug 02, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | Notebook    | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | Notebook    | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | Notebook    | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [0e300aa2a8](https://linux-hardware.org/?probe=0e300aa2a8) | Jul 30, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | Notebook    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | Notebook    | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9b5d494924](https://linux-hardware.org/?probe=9b5d494924) | Jul 25, 2020 |
| Dell          | Latitude 5480               | Notebook    | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [4615574555](https://linux-hardware.org/?probe=4615574555) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | Notebook    | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 8425                        | Desktop     | [25fd18c4f7](https://linux-hardware.org/?probe=25fd18c4f7) | Jul 19, 2020 |
| HP            | 255 G2                      | Notebook    | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | Notebook    | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [f504426c40](https://linux-hardware.org/?probe=f504426c40) | Jul 04, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [332ba4769f](https://linux-hardware.org/?probe=332ba4769f) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | Notebook    | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [0c0f90ba39](https://linux-hardware.org/?probe=0c0f90ba39) | Jun 27, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [124cdbcc52](https://linux-hardware.org/?probe=124cdbcc52) | Jun 27, 2020 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [92adc3c517](https://linux-hardware.org/?probe=92adc3c517) | Jun 25, 2020 |
| MSI           | X570-A PRO                  | Desktop     | [60c99711b8](https://linux-hardware.org/?probe=60c99711b8) | Jun 23, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d79300ba76](https://linux-hardware.org/?probe=d79300ba76) | Jun 18, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | Notebook    | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | Notebook    | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| MSI           | MEG X399 CREATION           | Desktop     | [89214de087](https://linux-hardware.org/?probe=89214de087) | Jun 12, 2020 |
| SLIMBOOK      | PROX15                      | Notebook    | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | Notebook    | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Lenovo        | ThinkCentre M58 7373BVU     | Desktop     | [5c40e26f41](https://linux-hardware.org/?probe=5c40e26f41) | Jun 09, 2020 |
| Dell          | Latitude E5420              | Notebook    | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [a1615f709d](https://linux-hardware.org/?probe=a1615f709d) | Jun 07, 2020 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7b570e8172](https://linux-hardware.org/?probe=7b570e8172) | Jun 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | Notebook    | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | Notebook    | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [1538853c0c](https://linux-hardware.org/?probe=1538853c0c) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | Notebook    | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | Notebook    | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [cdcb59b3fb](https://linux-hardware.org/?probe=cdcb59b3fb) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [495a29d64c](https://linux-hardware.org/?probe=495a29d64c) | May 22, 2020 |
| Packard Be... | P5N-E SLI                   | Desktop     | [1c2ca9c7de](https://linux-hardware.org/?probe=1c2ca9c7de) | May 22, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | Notebook    | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [932b22c52a](https://linux-hardware.org/?probe=932b22c52a) | May 16, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [02b85cc578](https://linux-hardware.org/?probe=02b85cc578) | May 16, 2020 |
| Lenovo        | ThinkPad T520 424329U       | Notebook    | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | Notebook    | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [deca13654e](https://linux-hardware.org/?probe=deca13654e) | May 13, 2020 |
| Intel         | DQ57TM AAE92694-401         | Desktop     | [c2abb26814](https://linux-hardware.org/?probe=c2abb26814) | May 11, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | Notebook    | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | Notebook    | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [db25140369](https://linux-hardware.org/?probe=db25140369) | May 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Sony UK       | Raspberry Pi 3 Model B      | Soc         | [52f0b7d3fa](https://linux-hardware.org/?probe=52f0b7d3fa) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | Notebook    | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | Notebook    | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | 0FH884                      | Desktop     | [1f7976ed89](https://linux-hardware.org/?probe=1f7976ed89) | Apr 30, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [473467f488](https://linux-hardware.org/?probe=473467f488) | Apr 29, 2020 |
| Dell          | XPS M1530                   | Notebook    | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | Notebook    | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | Notebook    | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [306c5d73fb](https://linux-hardware.org/?probe=306c5d73fb) | Apr 27, 2020 |
| Dell          | 0FH884                      | Desktop     | [9fd393aab9](https://linux-hardware.org/?probe=9fd393aab9) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | Notebook    | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| ABIT          | KN9                         | Desktop     | [6254e80aba](https://linux-hardware.org/?probe=6254e80aba) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | Notebook    | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | Notebook    | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | Notebook    | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | Notebook    | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| ABIT          | KN9                         | Desktop     | [be7c3f4dc9](https://linux-hardware.org/?probe=be7c3f4dc9) | Apr 14, 2020 |
| Dell          | Latitude E5450              | Notebook    | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | Notebook    | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | Notebook    | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d882ce78cd](https://linux-hardware.org/?probe=d882ce78cd) | Apr 09, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | Notebook    | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | Notebook    | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [79ceb06042](https://linux-hardware.org/?probe=79ceb06042) | Apr 05, 2020 |
| HP            | Pavilion dv6                | Notebook    | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| ASUSTek       | Z87-K                       | Desktop     | [2ccf545fb8](https://linux-hardware.org/?probe=2ccf545fb8) | Apr 03, 2020 |
| Dell          | 0P301D A00                  | Desktop     | [5996aa0d7b](https://linux-hardware.org/?probe=5996aa0d7b) | Apr 02, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | Notebook    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| ASUSTek       | Z87-PRO                     | Desktop     | [cf7a7cb442](https://linux-hardware.org/?probe=cf7a7cb442) | Mar 21, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Lenovo        | ThinkCentre A70 7844Q2G     | Desktop     | [7a3df56f82](https://linux-hardware.org/?probe=7a3df56f82) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b5c9d31ae9](https://linux-hardware.org/?probe=b5c9d31ae9) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [3a37c7a548](https://linux-hardware.org/?probe=3a37c7a548) | Mar 11, 2020 |
| Lenovo        | ThinkStation D20 415892G    | Desktop     | [6672072cc5](https://linux-hardware.org/?probe=6672072cc5) | Mar 03, 2020 |
| ABIT          | KN9                         | Desktop     | [dafc30ae16](https://linux-hardware.org/?probe=dafc30ae16) | Mar 02, 2020 |
| ABIT          | KN9                         | Desktop     | [e26e7f08ca](https://linux-hardware.org/?probe=e26e7f08ca) | Feb 23, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [11d467ac47](https://linux-hardware.org/?probe=11d467ac47) | Feb 22, 2020 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [e53a35010c](https://linux-hardware.org/?probe=e53a35010c) | Feb 22, 2020 |
| Dell          | Precision M6300             | Notebook    | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | Notebook    | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | Notebook    | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | Notebook    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ec722fbbfe](https://linux-hardware.org/?probe=ec722fbbfe) | Feb 01, 2020 |
| HP            | 1998                        | Desktop     | [edb9bba986](https://linux-hardware.org/?probe=edb9bba986) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | Notebook    | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | Notebook    | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [0c3d1fcefe](https://linux-hardware.org/?probe=0c3d1fcefe) | Dec 05, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | Notebook    | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [ab7afebfb6](https://linux-hardware.org/?probe=ab7afebfb6) | Nov 26, 2019 |
| MSI           | Z77 MPower                  | Desktop     | [77c87b6b71](https://linux-hardware.org/?probe=77c87b6b71) | Nov 26, 2019 |
| System76      | Galago Pro                  | Notebook    | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | Notebook    | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | Notebook    | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | Notebook    | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | Notebook    | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Seco          | C40 C                       | Desktop     | [a3f6f85e6a](https://linux-hardware.org/?probe=a3f6f85e6a) | Sep 15, 2019 |
| Alienware     | 17 R4                       | Notebook    | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | Notebook    | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Seco          | C40 C                       | Desktop     | [16208d3700](https://linux-hardware.org/?probe=16208d3700) | Sep 04, 2019 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Seco          | C40 C                       | Desktop     | [3a7afd413f](https://linux-hardware.org/?probe=3a7afd413f) | Aug 28, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | Notebook    | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| ASUSTek       | K5130                       | Desktop     | [72b7a5b445](https://linux-hardware.org/?probe=72b7a5b445) | Aug 08, 2019 |
| Acer          | Aspire E1-572               | Notebook    | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| DFI           | INF P35                     | Desktop     | [7987560cdc](https://linux-hardware.org/?probe=7987560cdc) | Aug 02, 2019 |
| DFI           | INF P35                     | Desktop     | [0379ced795](https://linux-hardware.org/?probe=0379ced795) | Aug 02, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [b7db1f6d08](https://linux-hardware.org/?probe=b7db1f6d08) | Jul 27, 2019 |
| MiTAC         | PD14TI AAPD14TI-101         | Desktop     | [bf4c96625e](https://linux-hardware.org/?probe=bf4c96625e) | Jul 27, 2019 |
| Advent        | Roma                        | Notebook    | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [649ff143ad](https://linux-hardware.org/?probe=649ff143ad) | Jul 08, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | Notebook    | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | Notebook    | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93d8ad05a1](https://linux-hardware.org/?probe=93d8ad05a1) | Jun 30, 2019 |
| AMI           | Aptio CRB                   | Mini pc     | [8f87769d12](https://linux-hardware.org/?probe=8f87769d12) | Jun 19, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [de0cc0ab6f](https://linux-hardware.org/?probe=de0cc0ab6f) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | Notebook    | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| Dell          | 0FJ030                      | Desktop     | [c3dfb2bea5](https://linux-hardware.org/?probe=c3dfb2bea5) | Jun 05, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [71dd964fb5](https://linux-hardware.org/?probe=71dd964fb5) | Jun 04, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| ASRock        | G31M-S                      | Desktop     | [213f2f20b6](https://linux-hardware.org/?probe=213f2f20b6) | May 24, 2019 |
| Dell          | 0Y2MRG A00                  | Desktop     | [f32755062c](https://linux-hardware.org/?probe=f32755062c) | May 23, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | Notebook    | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | Notebook    | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | Notebook    | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| Dell          | 03NVJ6 A02                  | Desktop     | [915e0bab53](https://linux-hardware.org/?probe=915e0bab53) | May 12, 2019 |
| ASUSTek       | S550CA                      | Notebook    | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | Notebook    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | Notebook    | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b0dcc92563](https://linux-hardware.org/?probe=b0dcc92563) | Apr 03, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | Notebook    | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6bae84797a](https://linux-hardware.org/?probe=6bae84797a) | Mar 22, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9e86bfbcc2](https://linux-hardware.org/?probe=9e86bfbcc2) | Mar 22, 2019 |
| Shuttle       | FS35V4                      | Desktop     | [03af7dbe17](https://linux-hardware.org/?probe=03af7dbe17) | Mar 20, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2bf103dd36](https://linux-hardware.org/?probe=2bf103dd36) | Feb 23, 2019 |
| Dell          | 0P7V82 A00                  | All in one  | [2907768caa](https://linux-hardware.org/?probe=2907768caa) | Feb 23, 2019 |
| Dell          | 0CRH6C A00                  | Desktop     | [300a99b1d0](https://linux-hardware.org/?probe=300a99b1d0) | Feb 10, 2019 |
| eMachines     | eM350                       | Notebook    | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | Notebook    | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Shuttle       | XS35V3                      | Desktop     | [ae76390fb4](https://linux-hardware.org/?probe=ae76390fb4) | Jan 18, 2019 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1cfe678b48](https://linux-hardware.org/?probe=1cfe678b48) | Jan 16, 2019 |
| Toshiba       | Satellite Pro C660          | Notebook    | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | Notebook    | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [2311962133](https://linux-hardware.org/?probe=2311962133) | Sep 30, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [6a91010c14](https://linux-hardware.org/?probe=6a91010c14) | Jul 07, 2018 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [e5e3ed1c7c](https://linux-hardware.org/?probe=e5e3ed1c7c) | Jun 01, 2018 |
| Dell          | Latitude E6230              | Notebook    | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1d52b52b65](https://linux-hardware.org/?probe=1d52b52b65) | Feb 28, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [1b14483855](https://linux-hardware.org/?probe=1b14483855) | Feb 23, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbe4f7f994](https://linux-hardware.org/?probe=bbe4f7f994) | Feb 11, 2018 |
| Acer          | Aspire E5-575G              | Notebook    | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [b32d7f9bc2](https://linux-hardware.org/?probe=b32d7f9bc2) | Jan 12, 2018 |
| Dell          | Latitude E6230              | Notebook    | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | Notebook    | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [7cf734ce05](https://linux-hardware.org/?probe=7cf734ce05) | Nov 04, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ireland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 83        | 13.24%  |
| Ubuntu 18.04       | 44        | 7.02%   |
| Ubuntu 22.04       | 29        | 4.63%   |
| Debian 11          | 23        | 3.67%   |
| Pop!_OS 22.04      | 16        | 2.55%   |
| OpenMandriva 4.2   | 12        | 1.91%   |
| Manjaro            | 12        | 1.91%   |
| Linux Mint 20.2    | 11        | 1.75%   |
| ArcoLinux Rolling  | 11        | 1.75%   |
| Arch               | 11        | 1.75%   |
| Ubuntu 22.10       | 10        | 1.59%   |
| Linux Mint 20      | 10        | 1.59%   |
| Fedora 37          | 10        | 1.59%   |
| Fedora 36          | 10        | 1.59%   |
| Debian 10          | 10        | 1.59%   |
| Arch Rolling       | 10        | 1.59%   |
| Ubuntu 19.04       | 9         | 1.44%   |
| Pop!_OS 21.10      | 9         | 1.44%   |
| Zorin 16           | 8         | 1.28%   |
| Pop!_OS 20.10      | 8         | 1.28%   |
| Linux Mint 21.1    | 8         | 1.28%   |
| Pop!_OS 20.04      | 7         | 1.12%   |
| OpenMandriva 4.3   | 7         | 1.12%   |
| OpenMandriva 23.01 | 7         | 1.12%   |
| Linux Mint 21      | 7         | 1.12%   |
| Linux Mint 20.3    | 7         | 1.12%   |
| KDE neon 20.04     | 7         | 1.12%   |
| BlackPanther 18.1  | 7         | 1.12%   |
| Ubuntu 19.10       | 6         | 0.96%   |
| Ubuntu 21.10       | 5         | 0.8%    |
| ROSA R11           | 5         | 0.8%    |
| ROSA R10           | 5         | 0.8%    |
| Lubuntu 20.04      | 5         | 0.8%    |
| Linux Mint 20.1    | 5         | 0.8%    |
| Linux Mint 19.3    | 5         | 0.8%    |
| Fedora 35          | 5         | 0.8%    |
| Fedora 33          | 5         | 0.8%    |
| Fedora 32          | 5         | 0.8%    |
| Zorin 15           | 4         | 0.64%   |
| Ubuntu 23.04       | 4         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 193       | 32.66%  |
| Linux Mint    | 60        | 10.15%  |
| Pop!_OS       | 40        | 6.77%   |
| Debian        | 40        | 6.77%   |
| Fedora        | 39        | 6.6%    |
| OpenMandriva  | 31        | 5.25%   |
| Manjaro       | 25        | 4.23%   |
| Arch          | 21        | 3.55%   |
| Kubuntu       | 14        | 2.37%   |
| Zorin         | 12        | 2.03%   |
| ROSA          | 12        | 2.03%   |
| ArcoLinux     | 11        | 1.86%   |
| Elementary    | 10        | 1.69%   |
| Lubuntu       | 8         | 1.35%   |
| KDE neon      | 8         | 1.35%   |
| BlackPanther  | 7         | 1.18%   |
| SteamOS       | 6         | 1.02%   |
| Ubuntu Unity  | 5         | 0.85%   |
| Endless       | 5         | 0.85%   |
| Xubuntu       | 4         | 0.68%   |
| Ubuntu Budgie | 4         | 0.68%   |
| openSUSE      | 4         | 0.68%   |
| Gentoo        | 4         | 0.68%   |
| Ubuntu MATE   | 3         | 0.51%   |
| Clear Linux   | 3         | 0.51%   |
| Peppermint    | 2         | 0.34%   |
| MX            | 2         | 0.34%   |
| LMDE          | 2         | 0.34%   |
| Kali          | 2         | 0.34%   |
| CentOS        | 2         | 0.34%   |
| Trisquel      | 1         | 0.17%   |
| Solus         | 1         | 0.17%   |
| Rocky Linux   | 1         | 0.17%   |
| RHEL          | 1         | 0.17%   |
| Redcore       | 1         | 0.17%   |
| Reborn OS     | 1         | 0.17%   |
| Nobara        | 1         | 0.17%   |
| Linux Lite    | 1         | 0.17%   |
| Garuda Linux  | 1         | 0.17%   |
| Feren OS      | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.16%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.73%   |
| 5.3.0-46-generic         | 10        | 1.44%   |
| 5.15.0-46-generic        | 8         | 1.15%   |
| 5.19.0-35-generic        | 7         | 1.01%   |
| 5.16.7-desktop-1omv4003  | 7         | 1.01%   |
| 5.15.0-56-generic        | 7         | 1.01%   |
| 6.1.1-desktop-1omv2290   | 6         | 0.86%   |
| 5.4.0-52-generic         | 6         | 0.86%   |
| 5.15.0-52-generic        | 6         | 0.86%   |
| 4.18.16-desktop-1bP      | 6         | 0.86%   |
| 5.4.0-91-generic         | 5         | 0.72%   |
| 5.4.0-48-generic         | 5         | 0.72%   |
| 5.19.0-29-generic        | 5         | 0.72%   |
| 5.15.0-67-generic        | 5         | 0.72%   |
| 5.11.0-27-generic        | 5         | 0.72%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.58%   |
| 6.2.0-20-generic         | 4         | 0.58%   |
| 5.8.0-7630-generic       | 4         | 0.58%   |
| 5.8.0-43-generic         | 4         | 0.58%   |
| 5.4.0-72-generic         | 4         | 0.58%   |
| 5.4.0-47-generic         | 4         | 0.58%   |
| 5.4.0-31-generic         | 4         | 0.58%   |
| 5.4.0-29-generic         | 4         | 0.58%   |
| 5.4.0-26-generic         | 4         | 0.58%   |
| 5.3.0-28-generic         | 4         | 0.58%   |
| 5.19.0-38-generic        | 4         | 0.58%   |
| 5.15.0-60-generic        | 4         | 0.58%   |
| 5.15.0-48-generic        | 4         | 0.58%   |
| 4.18.0-15-generic        | 4         | 0.58%   |
| 6.2.6-76060206-generic   | 3         | 0.43%   |
| 6.0.6-76060006-generic   | 3         | 0.43%   |
| 6.0.12-76060006-generic  | 3         | 0.43%   |
| 5.8.0-53-generic         | 3         | 0.43%   |
| 5.8.0-41-generic         | 3         | 0.43%   |
| 5.4.0-77-generic         | 3         | 0.43%   |
| 5.4.0-7634-generic       | 3         | 0.43%   |
| 5.4.0-58-generic         | 3         | 0.43%   |
| 5.4.0-54-generic         | 3         | 0.43%   |
| 5.4.0-40-generic         | 3         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 115       | 17.64%  |
| 5.15.0  | 49        | 7.52%   |
| 4.15.0  | 36        | 5.52%   |
| 5.19.0  | 30        | 4.6%    |
| 5.8.0   | 28        | 4.29%   |
| 5.11.0  | 27        | 4.14%   |
| 5.3.0   | 26        | 3.99%   |
| 5.10.0  | 22        | 3.37%   |
| 5.13.0  | 21        | 3.22%   |
| 5.0.0   | 15        | 2.3%    |
| 5.10.14 | 12        | 1.84%   |
| 4.19.0  | 11        | 1.69%   |
| 4.18.0  | 11        | 1.69%   |
| 5.17.5  | 8         | 1.23%   |
| 6.2.6   | 7         | 1.07%   |
| 5.16.7  | 7         | 1.07%   |
| 6.2.0   | 6         | 0.92%   |
| 6.1.1   | 6         | 0.92%   |
| 4.18.16 | 6         | 0.92%   |
| 6.0.6   | 4         | 0.61%   |
| 5.16.11 | 4         | 0.61%   |
| 4.9.60  | 4         | 0.61%   |
| 6.2.8   | 3         | 0.46%   |
| 6.1.9   | 3         | 0.46%   |
| 6.1.0   | 3         | 0.46%   |
| 6.0.9   | 3         | 0.46%   |
| 6.0.12  | 3         | 0.46%   |
| 6.0.0   | 3         | 0.46%   |
| 5.8.14  | 3         | 0.46%   |
| 5.6.0   | 3         | 0.46%   |
| 5.18.0  | 3         | 0.46%   |
| 5.16.15 | 3         | 0.46%   |
| 5.15.12 | 3         | 0.46%   |
| 5.15.11 | 3         | 0.46%   |
| 5.12.4  | 3         | 0.46%   |
| 4.9.155 | 3         | 0.46%   |
| 4.10.0  | 3         | 0.46%   |
| 6.2.11  | 2         | 0.31%   |
| 6.1.11  | 2         | 0.31%   |
| 6.0.10  | 2         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 120       | 18.78%  |
| 5.15    | 65        | 10.17%  |
| 5.10    | 47        | 7.36%   |
| 5.19    | 37        | 5.79%   |
| 4.15    | 36        | 5.63%   |
| 5.8     | 35        | 5.48%   |
| 5.11    | 33        | 5.16%   |
| 5.3     | 27        | 4.23%   |
| 5.13    | 27        | 4.23%   |
| 6.0     | 20        | 3.13%   |
| 6.2     | 19        | 2.97%   |
| 6.1     | 19        | 2.97%   |
| 5.16    | 17        | 2.66%   |
| 4.18    | 17        | 2.66%   |
| 5.17    | 15        | 2.35%   |
| 5.0     | 15        | 2.35%   |
| 4.19    | 12        | 1.88%   |
| 4.9     | 11        | 1.72%   |
| 5.6     | 10        | 1.56%   |
| 5.18    | 10        | 1.56%   |
| 5.12    | 9         | 1.41%   |
| 5.7     | 7         | 1.1%    |
| 5.14    | 7         | 1.1%    |
| 5.9     | 5         | 0.78%   |
| 4.4     | 3         | 0.47%   |
| 4.10    | 3         | 0.47%   |
| 6.3     | 2         | 0.31%   |
| 4.13    | 2         | 0.31%   |
| 4.12    | 2         | 0.31%   |
| 3.10    | 2         | 0.31%   |
| 5.5     | 1         | 0.16%   |
| 5.2     | 1         | 0.16%   |
| 5       | 1         | 0.16%   |
| 4.14    | 1         | 0.16%   |
| 4.1     | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 546       | 95.96%  |
| i686    | 15        | 2.64%   |
| aarch64 | 8         | 1.41%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 264       | 43.93%  |
| KDE5            | 97        | 16.14%  |
| Unknown         | 73        | 12.15%  |
| X-Cinnamon      | 42        | 6.99%   |
| XFCE            | 39        | 6.49%   |
| KDE             | 18        | 3%      |
| MATE            | 12        | 2%      |
| Pantheon        | 9         | 1.5%    |
| LXQt            | 9         | 1.5%    |
| Cinnamon        | 8         | 1.33%   |
| KDE4            | 6         | 1%      |
| Unity           | 5         | 0.83%   |
| i3              | 4         | 0.67%   |
| Budgie          | 4         | 0.67%   |
| GNOME Flashback | 3         | 0.5%    |
| LXDE            | 2         | 0.33%   |
| GNOME Classic   | 2         | 0.33%   |
| X-Generic       | 1         | 0.17%   |
| LeftWM          | 1         | 0.17%   |
| Enlightenment   | 1         | 0.17%   |
| BunsenLabs      | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 455       | 78.58%  |
| Wayland | 72        | 12.44%  |
| Unknown | 40        | 6.91%   |
| Tty     | 12        | 2.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 307       | 52.03%  |
| SDDM    | 87        | 14.75%  |
| GDM     | 69        | 11.69%  |
| GDM3    | 53        | 8.98%   |
| LightDM | 45        | 7.63%   |
| TDM     | 19        | 3.22%   |
| KDM     | 6         | 1.02%   |
| LXDM    | 2         | 0.34%   |
| SLiM    | 1         | 0.17%   |
| MDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 280       | 47.38%  |
| en_GB   | 107       | 18.1%   |
| en_US   | 98        | 16.58%  |
| Unknown | 66        | 11.17%  |
| pl_PL   | 14        | 2.37%   |
| C       | 4         | 0.68%   |
| es_ES   | 3         | 0.51%   |
| en_IN   | 2         | 0.34%   |
| en_CA   | 2         | 0.34%   |
| bg_BG   | 2         | 0.34%   |
| zh_CN   | 1         | 0.17%   |
| ru_RU   | 1         | 0.17%   |
| pt_PT   | 1         | 0.17%   |
| pt_BR   | 1         | 0.17%   |
| lt_LT   | 1         | 0.17%   |
| it_IT   | 1         | 0.17%   |
| ga_IE   | 1         | 0.17%   |
| fr_FR   | 1         | 0.17%   |
| fr_BE   | 1         | 0.17%   |
| en_ZA   | 1         | 0.17%   |
| en_DE   | 1         | 0.17%   |
| en_BW   | 1         | 0.17%   |
| de_DE   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 300       | 51.9%   |
| EFI  | 278       | 48.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 448       | 77.64%  |
| Btrfs               | 50        | 8.67%   |
| Overlay             | 38        | 6.59%   |
| Unknown             | 23        | 3.99%   |
| Xfs                 | 8         | 1.39%   |
| Zfs                 | 5         | 0.87%   |
| Tmpfs               | 3         | 0.52%   |
| Fuse.fuse-overlayfs | 1         | 0.17%   |
| F2fs                | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 311       | 53.16%  |
| GPT     | 215       | 36.75%  |
| MBR     | 59        | 10.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 490       | 84.78%  |
| Yes       | 88        | 15.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 429       | 74.22%  |
| Yes       | 149       | 25.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 122       | 21.52%  |
| Lenovo                               | 99        | 17.46%  |
| Hewlett-Packard                      | 68        | 11.99%  |
| ASUSTek Computer                     | 67        | 11.82%  |
| Gigabyte Technology                  | 28        | 4.94%   |
| Acer                                 | 23        | 4.06%   |
| MSI                                  | 21        | 3.7%    |
| Apple                                | 19        | 3.35%   |
| ASRock                               | 13        | 2.29%   |
| Toshiba                              | 12        | 2.12%   |
| Intel                                | 11        | 1.94%   |
| Samsung Electronics                  | 7         | 1.23%   |
| Medion                               | 5         | 0.88%   |
| Foxconn                              | 5         | 0.88%   |
| TUXEDO                               | 4         | 0.71%   |
| Timi                                 | 4         | 0.71%   |
| PC Specialist                        | 4         | 0.71%   |
| Valve                                | 3         | 0.53%   |
| Raspberry Pi Foundation              | 3         | 0.53%   |
| Notebook                             | 3         | 0.53%   |
| HUAWEI                               | 3         | 0.53%   |
| Chuwi                                | 3         | 0.53%   |
| System76                             | 2         | 0.35%   |
| Shuttle                              | 2         | 0.35%   |
| Seco                                 | 2         | 0.35%   |
| Packard Bell                         | 2         | 0.35%   |
| Nvidia                               | 2         | 0.35%   |
| Fujitsu Siemens                      | 2         | 0.35%   |
| Entroware                            | 2         | 0.35%   |
| eMachines                            | 2         | 0.35%   |
| Star Labs                            | 1         | 0.18%   |
| Sony UK                              | 1         | 0.18%   |
| Sony                                 | 1         | 0.18%   |
| SLIMBOOK                             | 1         | 0.18%   |
| Shenzhen Wangang Technology          | 1         | 0.18%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.18%   |
| Schenker                             | 1         | 0.18%   |
| Rockchip                             | 1         | 0.18%   |
| Pine Microsystems                    | 1         | 0.18%   |
| Pegatron                             | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell Latitude 7420                | 8         | 1.41%   |
| Dell OptiPlex 7010                | 7         | 1.23%   |
| ASUS All Series                   | 7         | 1.23%   |
| Lenovo Yoga 6 13ALC7 82UD         | 5         | 0.88%   |
| Gigabyte B450M DS3H               | 4         | 0.71%   |
| Valve Jupiter                     | 3         | 0.53%   |
| Lenovo V145-15AST 81MT            | 3         | 0.53%   |
| HP Compaq 8200 Elite SFF PC       | 3         | 0.53%   |
| Dell OptiPlex 790                 | 3         | 0.53%   |
| Dell OptiPlex 780                 | 3         | 0.53%   |
| Dell OptiPlex 7020                | 3         | 0.53%   |
| Dell Latitude E7240               | 3         | 0.53%   |
| Dell Inspiron 13-5378             | 3         | 0.53%   |
| ASUS ROG STRIX B450-F GAMING      | 3         | 0.53%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.35%   |
| Seco C40                          | 2         | 0.35%   |
| RPi Raspberry Pi                  | 2         | 0.35%   |
| Nvidia Tegra                      | 2         | 0.35%   |
| MSI MS-7C37                       | 2         | 0.35%   |
| MSI MS-7B79                       | 2         | 0.35%   |
| Lenovo ThinkStation D20 415892G   | 2         | 0.35%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.35%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.35%   |
| HUAWEI NBLK-WAX9X                 | 2         | 0.35%   |
| HP Pavilion g6                    | 2         | 0.35%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.35%   |
| HP Notebook                       | 2         | 0.35%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.35%   |
| Gigabyte X570 AORUS ULTRA         | 2         | 0.35%   |
| Gigabyte A320M-S2H                | 2         | 0.35%   |
| Foxconn Pro 3500 Series           | 2         | 0.35%   |
| Dell XPS 9320                     | 2         | 0.35%   |
| Dell XPS 13 9310                  | 2         | 0.35%   |
| Dell XPS 13 9300                  | 2         | 0.35%   |
| Dell XPS 13 7390                  | 2         | 0.35%   |
| Dell Precision 5550               | 2         | 0.35%   |
| Dell Latitude E6230               | 2         | 0.35%   |
| Dell Inspiron 7577                | 2         | 0.35%   |
| Dell Inspiron 5570                | 2         | 0.35%   |
| ASUS X501A1                       | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 44        | 7.76%   |
| Dell Latitude       | 39        | 6.88%   |
| Dell OptiPlex       | 24        | 4.23%   |
| Dell Inspiron       | 22        | 3.88%   |
| Acer Aspire         | 16        | 2.82%   |
| Lenovo IdeaPad      | 15        | 2.65%   |
| Dell XPS            | 14        | 2.47%   |
| HP Pavilion         | 13        | 2.29%   |
| HP EliteBook        | 13        | 2.29%   |
| Dell Precision      | 10        | 1.76%   |
| Toshiba Satellite   | 9         | 1.59%   |
| Lenovo Yoga         | 9         | 1.59%   |
| HP Compaq           | 8         | 1.41%   |
| ASUS TUF            | 8         | 1.41%   |
| Lenovo ThinkCentre  | 7         | 1.23%   |
| ASUS PRIME          | 7         | 1.23%   |
| ASUS All            | 7         | 1.23%   |
| ASUS ROG            | 6         | 1.06%   |
| HP EliteDesk        | 4         | 0.71%   |
| Gigabyte B450M      | 4         | 0.71%   |
| Dell Vostro         | 4         | 0.71%   |
| Valve Jupiter       | 3         | 0.53%   |
| RPi Raspberry       | 3         | 0.53%   |
| Lenovo V145-15AST   | 3         | 0.53%   |
| Lenovo ThinkBook    | 3         | 0.53%   |
| HP ProBook          | 3         | 0.53%   |
| HP Presario         | 3         | 0.53%   |
| HP Laptop           | 3         | 0.53%   |
| Foxconn Pro         | 3         | 0.53%   |
| ASUS Zenbook        | 3         | 0.53%   |
| Apple MacBookPro5   | 3         | 0.53%   |
| Acer Nitro          | 3         | 0.53%   |
| TUXEDO Pulse        | 2         | 0.35%   |
| TUXEDO InfinityBook | 2         | 0.35%   |
| Toshiba TECRA       | 2         | 0.35%   |
| Seco C40            | 2         | 0.35%   |
| Nvidia Tegra        | 2         | 0.35%   |
| MSI MS-7C37         | 2         | 0.35%   |
| MSI MS-7B79         | 2         | 0.35%   |
| Lenovo ThinkStation | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 59        | 10.41%  |
| 2020    | 53        | 9.35%   |
| 2018    | 51        | 8.99%   |
| 2013    | 48        | 8.47%   |
| 2012    | 43        | 7.58%   |
| 2017    | 42        | 7.41%   |
| 2011    | 40        | 7.05%   |
| 2021    | 31        | 5.47%   |
| 2010    | 29        | 5.11%   |
| 2015    | 28        | 4.94%   |
| 2008    | 26        | 4.59%   |
| 2022    | 25        | 4.41%   |
| 2016    | 22        | 3.88%   |
| 2014    | 21        | 3.7%    |
| 2009    | 19        | 3.35%   |
| 2007    | 10        | 1.76%   |
| 2006    | 7         | 1.23%   |
| Unknown | 7         | 1.23%   |
| 2005    | 3         | 0.53%   |
| 2023    | 2         | 0.35%   |
| 2003    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 337       | 59.44%  |
| Desktop        | 180       | 31.75%  |
| Convertible    | 14        | 2.47%   |
| Mini pc        | 13        | 2.29%   |
| All in one     | 11        | 1.94%   |
| System on chip | 7         | 1.23%   |
| Tablet         | 3         | 0.53%   |
| Phone          | 1         | 0.18%   |
| Server         | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 519       | 90.89%  |
| Enabled  | 52        | 9.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 565       | 99.65%  |
| Yes  | 2         | 0.35%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 23.32%  |
| 16.01-24.0  | 122       | 21.07%  |
| 8.01-16.0   | 109       | 18.83%  |
| 3.01-4.0    | 95        | 16.41%  |
| 32.01-64.0  | 63        | 10.88%  |
| 1.01-2.0    | 19        | 3.28%   |
| 64.01-256.0 | 16        | 2.76%   |
| 24.01-32.0  | 9         | 1.55%   |
| 2.01-3.0    | 5         | 0.86%   |
| 0.51-1.0    | 5         | 0.86%   |
| 0.01-0.5    | 1         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 206       | 32.44%  |
| 2.01-3.0   | 158       | 24.88%  |
| 4.01-8.0   | 101       | 15.91%  |
| 3.01-4.0   | 91        | 14.33%  |
| 0.51-1.0   | 42        | 6.61%   |
| 8.01-16.0  | 27        | 4.25%   |
| 0.01-0.5   | 6         | 0.94%   |
| 16.01-24.0 | 3         | 0.47%   |
| 32.01-64.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 360       | 60.1%   |
| 2      | 140       | 23.37%  |
| 3      | 42        | 7.01%   |
| 4      | 25        | 4.17%   |
| 5      | 13        | 2.17%   |
| 7      | 6         | 1%      |
| 6      | 4         | 0.67%   |
| 0      | 4         | 0.67%   |
| 10     | 2         | 0.33%   |
| 11     | 1         | 0.17%   |
| 9      | 1         | 0.17%   |
| 8      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 357       | 61.98%  |
| Yes       | 219       | 38.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 493       | 86.34%  |
| No        | 78        | 13.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 480       | 83.62%  |
| No        | 94        | 16.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 382       | 66.2%   |
| No        | 195       | 33.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 567       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Dublin         | 330       | 55.37%  |
| Cork           | 34        | 5.7%    |
| Limerick       | 20        | 3.36%   |
| Galway         | 19        | 3.19%   |
| Naas           | 12        | 2.01%   |
| Ennis          | 7         | 1.17%   |
| Drogheda       | 7         | 1.17%   |
| Portlaoise     | 6         | 1.01%   |
| Gorey          | 6         | 1.01%   |
| Enniscorthy    | 6         | 1.01%   |
| Athlone        | 6         | 1.01%   |
| Sligo          | 5         | 0.84%   |
| Nenagh         | 5         | 0.84%   |
| Navan          | 5         | 0.84%   |
| Wexford        | 4         | 0.67%   |
| Tuam           | 4         | 0.67%   |
| Loughrea       | 4         | 0.67%   |
| Kilkenny       | 4         | 0.67%   |
| Kenmare        | 4         | 0.67%   |
| Dún Laoghaire | 4         | 0.67%   |
| Waterford      | 3         | 0.5%    |
| Maynooth       | 3         | 0.5%    |
| Lucan          | 3         | 0.5%    |
| Cobh           | 3         | 0.5%    |
| Cavan          | 3         | 0.5%    |
| Ballina        | 3         | 0.5%    |
| Westport       | 2         | 0.34%   |
| Tullamore      | 2         | 0.34%   |
| Swords         | 2         | 0.34%   |
| Oranmore       | 2         | 0.34%   |
| Mallow         | 2         | 0.34%   |
| Letterkenny    | 2         | 0.34%   |
| Killorglin     | 2         | 0.34%   |
| Kildare        | 2         | 0.34%   |
| Edenderry      | 2         | 0.34%   |
| Donegal        | 2         | 0.34%   |
| Clonakilty     | 2         | 0.34%   |
| Clane          | 2         | 0.34%   |
| Carrigaline    | 2         | 0.34%   |
| Bray           | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 144       | 212    | 17.2%   |
| WDC                         | 136       | 235    | 16.25%  |
| Seagate                     | 101       | 169    | 12.07%  |
| Toshiba                     | 47        | 64     | 5.62%   |
| Unknown                     | 45        | 59     | 5.38%   |
| SanDisk                     | 45        | 61     | 5.38%   |
| Crucial                     | 44        | 57     | 5.26%   |
| Hitachi                     | 37        | 50     | 4.42%   |
| Kingston                    | 24        | 35     | 2.87%   |
| SK hynix                    | 17        | 19     | 2.03%   |
| Intel                       | 17        | 21     | 2.03%   |
| Micron Technology           | 16        | 17     | 1.91%   |
| KIOXIA                      | 15        | 17     | 1.79%   |
| HGST                        | 14        | 15     | 1.67%   |
| A-DATA Technology           | 10        | 15     | 1.19%   |
| Phison                      | 7         | 12     | 0.84%   |
| Fujitsu                     | 7         | 9      | 0.84%   |
| LITEON                      | 6         | 6      | 0.72%   |
| Apple                       | 6         | 7      | 0.72%   |
| Verbatim                    | 5         | 5      | 0.6%    |
| China                       | 5         | 10     | 0.6%    |
| Transcend                   | 4         | 4      | 0.48%   |
| Silicon Motion              | 4         | 9      | 0.48%   |
| PNY                         | 4         | 4      | 0.48%   |
| KingSpec                    | 4         | 4      | 0.48%   |
| OCZ                         | 3         | 3      | 0.36%   |
| Netac                       | 3         | 3      | 0.36%   |
| Micron/Crucial Technology   | 3         | 6      | 0.36%   |
| LITEONIT                    | 3         | 3      | 0.36%   |
| Kingston Technology Company | 3         | 3      | 0.36%   |
| KingDian                    | 3         | 14     | 0.36%   |
| ASMT                        | 3         | 5      | 0.36%   |
| Union Memory                | 2         | 2      | 0.24%   |
| Team                        | 2         | 2      | 0.24%   |
| SABRENT                     | 2         | 3      | 0.24%   |
| QNAP                        | 2         | 12     | 0.24%   |
| Patriot                     | 2         | 2      | 0.24%   |
| Maxtor                      | 2         | 2      | 0.24%   |
| JMicron Technology          | 2         | 2      | 0.24%   |
| Integral                    | 2         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 11        | 1.18%   |
| Crucial CT1000MX500SSD1 1TB                        | 9         | 0.96%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                     | 8         | 0.86%   |
| Unknown MMC Card  32GB                             | 7         | 0.75%   |
| Seagate ST1000DM010-2EP102 1TB                     | 7         | 0.75%   |
| Samsung SSD 860 EVO 500GB                          | 7         | 0.75%   |
| Crucial CT500MX500SSD1 500GB                       | 7         | 0.75%   |
| Unknown MMC Card  64GB                             | 6         | 0.64%   |
| Toshiba MQ01ABD100 1TB                             | 6         | 0.64%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB             | 6         | 0.64%   |
| Seagate ST8000DM004-2CX188 8TB                     | 6         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                       | 6         | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB                     | 6         | 0.64%   |
| Samsung SSD 850 EVO 250GB                          | 6         | 0.64%   |
| Samsung SSD 840 EVO 250GB                          | 6         | 0.64%   |
| Samsung NVMe SSD Drive 500GB                       | 6         | 0.64%   |
| Samsung NVMe SSD Drive 256GB                       | 6         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 5         | 0.54%   |
| WDC WD10EURX-83UY4Y0 1TB                           | 5         | 0.54%   |
| Verbatim Vi550 S3 SSD 128GB                        | 5         | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                    | 5         | 0.54%   |
| Samsung SSD 850 EVO 500GB                          | 5         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 0.54%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.54%   |
| Kingston SA400S37240G 240GB SSD                    | 5         | 0.54%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 4         | 0.43%   |
| Seagate ST3500312CS 500GB                          | 4         | 0.43%   |
| Seagate ST2000DL003-9VT166 2TB                     | 4         | 0.43%   |
| Seagate Expansion Desk 4TB                         | 4         | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                   | 4         | 0.43%   |
| Hitachi HTS723232A7A364 320GB                      | 4         | 0.43%   |
| HGST HTS721010A9E630 1TB                           | 4         | 0.43%   |
| HGST HTS545050A7E680 500GB                         | 4         | 0.43%   |
| Crucial M4-CT128M4SSD2 128GB                       | 4         | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 3         | 0.32%   |
| WDC WD3200AAJS-60Z0A0 320GB                        | 3         | 0.32%   |
| WDC WD20EZRX-00D8PB0 2TB                           | 3         | 0.32%   |
| WDC WD10EALX-009BA0 1TB                            | 3         | 0.32%   |
| Unknown SL16G  16GB                                | 3         | 0.32%   |
| Unknown SD/MMC/MS PRO 64GB                         | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 107       | 195    | 32.82%  |
| Seagate             | 99        | 166    | 30.37%  |
| Hitachi             | 37        | 50     | 11.35%  |
| Toshiba             | 32        | 44     | 9.82%   |
| HGST                | 14        | 15     | 4.29%   |
| Samsung Electronics | 11        | 14     | 3.37%   |
| Fujitsu             | 7         | 9      | 2.15%   |
| Apple               | 4         | 4      | 1.23%   |
| Unknown             | 3         | 3      | 0.92%   |
| QNAP                | 2         | 12     | 0.61%   |
| Maxtor              | 2         | 2      | 0.61%   |
| USB3.0              | 1         | 1      | 0.31%   |
| SABRENT             | 1         | 2      | 0.31%   |
| LaCie               | 1         | 1      | 0.31%   |
| KESU                | 1         | 1      | 0.31%   |
| Inateck             | 1         | 1      | 0.31%   |
| FNK TECH            | 1         | 1      | 0.31%   |
| ExcelStor           | 1         | 2      | 0.31%   |
| ASMT                | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 100    | 26.69%  |
| Crucial             | 41        | 54     | 15.41%  |
| SanDisk             | 26        | 30     | 9.77%   |
| Kingston            | 23        | 33     | 8.65%   |
| WDC                 | 13        | 19     | 4.89%   |
| A-DATA Technology   | 7         | 11     | 2.63%   |
| Intel               | 6         | 6      | 2.26%   |
| Verbatim            | 5         | 5      | 1.88%   |
| LITEON              | 5         | 5      | 1.88%   |
| China               | 5         | 10     | 1.88%   |
| PNY                 | 4         | 4      | 1.5%    |
| Micron Technology   | 4         | 4      | 1.5%    |
| KingSpec            | 4         | 4      | 1.5%    |
| Transcend           | 3         | 3      | 1.13%   |
| Toshiba             | 3         | 5      | 1.13%   |
| OCZ                 | 3         | 3      | 1.13%   |
| Netac               | 3         | 3      | 1.13%   |
| LITEONIT            | 3         | 3      | 1.13%   |
| KingDian            | 3         | 14     | 1.13%   |
| Apple               | 3         | 3      | 1.13%   |
| Team                | 2         | 2      | 0.75%   |
| SK hynix            | 2         | 2      | 0.75%   |
| Patriot             | 2         | 2      | 0.75%   |
| Integral            | 2         | 2      | 0.75%   |
| FORESEE             | 2         | 2      | 0.75%   |
| ASMT                | 2         | 4      | 0.75%   |
| Zheino              | 1         | 1      | 0.38%   |
| W800S               | 1         | 2      | 0.38%   |
| TCSUNBOW            | 1         | 1      | 0.38%   |
| StoreJet            | 1         | 2      | 0.38%   |
| Star                | 1         | 1      | 0.38%   |
| SPCC                | 1         | 1      | 0.38%   |
| SABRENT             | 1         | 1      | 0.38%   |
| Plextor             | 1         | 1      | 0.38%   |
| Palit               | 1         | 1      | 0.38%   |
| JMicron Technology  | 1         | 1      | 0.38%   |
| Hikvision           | 1         | 1      | 0.38%   |
| Hewlett-Packard     | 1         | 2      | 0.38%   |
| GOODRAM             | 1         | 1      | 0.38%   |
| faspeed             | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 263       | 524    | 35.35%  |
| SSD     | 236       | 357    | 31.72%  |
| NVMe    | 192       | 273    | 25.81%  |
| MMC     | 42        | 59     | 5.65%   |
| Unknown | 11        | 11     | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 411       | 852    | 60.8%   |
| NVMe | 192       | 273    | 28.4%   |
| MMC  | 42        | 59     | 6.21%   |
| SAS  | 31        | 40     | 4.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 306       | 505    | 57.52%  |
| 0.51-1.0   | 152       | 232    | 28.57%  |
| 1.01-2.0   | 34        | 52     | 6.39%   |
| 3.01-4.0   | 18        | 36     | 3.38%   |
| 2.01-3.0   | 11        | 24     | 2.07%   |
| 4.01-10.0  | 9         | 29     | 1.69%   |
| 10.01-20.0 | 2         | 3      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 153       | 25.46%  |
| 101-250        | 147       | 24.46%  |
| 501-1000       | 76        | 12.65%  |
| 51-100         | 50        | 8.32%   |
| 1-20           | 45        | 7.49%   |
| 1001-2000      | 41        | 6.82%   |
| More than 3000 | 32        | 5.32%   |
| 21-50          | 22        | 3.66%   |
| Unknown        | 21        | 3.49%   |
| 2001-3000      | 14        | 2.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 240       | 38.22%  |
| 21-50          | 93        | 14.81%  |
| 101-250        | 84        | 13.38%  |
| 51-100         | 78        | 12.42%  |
| 501-1000       | 39        | 6.21%   |
| 251-500        | 38        | 6.05%   |
| Unknown        | 21        | 3.34%   |
| More than 3000 | 15        | 2.39%   |
| 1001-2000      | 11        | 1.75%   |
| 2001-3000      | 9         | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                        | 3         | 8      | 4.62%   |
| Seagate ST2000DL003-9VT166 2TB                 | 3         | 5      | 4.62%   |
| WDC WD2500AAKX-753CA1 250GB                    | 2         | 4      | 3.08%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 3.08%   |
| Western Digital SN730 500GB                    | 1         | 2      | 1.54%   |
| WDC WD7500BPKX-00HPJT0 752GB                   | 1         | 1      | 1.54%   |
| WDC WD5000LPCX-24VHAT0 500GB                   | 1         | 1      | 1.54%   |
| WDC WD5000HHTZ-04N21V0 500GB                   | 1         | 2      | 1.54%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 1.54%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 2      | 1.54%   |
| WDC WD400JB-00FMA0 40GB                        | 1         | 2      | 1.54%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.54%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.54%   |
| WDC WD2500BEKT-75A25T0 250GB                   | 1         | 1      | 1.54%   |
| WDC WD2500AAKX-603CA0 250GB                    | 1         | 1      | 1.54%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 2      | 1.54%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.54%   |
| WDC WD1001FALS-00E8B0 1TB                      | 1         | 2      | 1.54%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.54%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.54%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 1.54%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 1.54%   |
| Toshiba DT01ACA050 500GB                       | 1         | 3      | 1.54%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 1.54%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 1.54%   |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 1      | 1.54%   |
| Seagate ST3500418AS 500GB                      | 1         | 2      | 1.54%   |
| Seagate ST31500541AS 1TB                       | 1         | 1      | 1.54%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 1.54%   |
| Seagate ST31000333AS 1TB                       | 1         | 2      | 1.54%   |
| Seagate ST3000DM001-1ER166 3TB                 | 1         | 1      | 1.54%   |
| SanDisk SSD PLUS 480GB                         | 1         | 1      | 1.54%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.54%   |
| Samsung Electronics SSD 970 EVO Plus 2TB       | 1         | 1      | 1.54%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.54%   |
| Samsung Electronics HD103SI 1TB                | 1         | 1      | 1.54%   |
| Netac SSD 128GB                                | 1         | 1      | 1.54%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 1.54%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.54%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 30     | 24.19%  |
| Seagate             | 11        | 15     | 17.74%  |
| Hitachi             | 10        | 13     | 16.13%  |
| Toshiba             | 5         | 7      | 8.06%   |
| Samsung Electronics | 3         | 3      | 4.84%   |
| Micron Technology   | 3         | 3      | 4.84%   |
| SanDisk             | 2         | 2      | 3.23%   |
| HGST                | 2         | 2      | 3.23%   |
| Western Digital     | 1         | 2      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| Maxtor              | 1         | 1      | 1.61%   |
| JMicron Technology  | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Inateck             | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 1      | 1.61%   |
| DRVEO               | 1         | 1      | 1.61%   |
| China               | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 30     | 30.61%  |
| Seagate             | 11        | 15     | 22.45%  |
| Hitachi             | 10        | 13     | 20.41%  |
| Toshiba             | 5         | 7      | 10.2%   |
| Samsung Electronics | 2         | 2      | 4.08%   |
| HGST                | 2         | 2      | 4.08%   |
| Maxtor              | 1         | 1      | 2.04%   |
| Inateck             | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 73     | 75%     |
| SSD  | 10        | 10     | 19.23%  |
| NVMe | 3         | 4      | 5.77%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 50%     |
| KingDian S400 120GB         | 1         | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 50%     |
| KingDian | 1         | 4      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 353       | 694    | 56.39%  |
| Works    | 221       | 438    | 35.3%   |
| Malfunc  | 50        | 87     | 7.99%   |
| Failed   | 2         | 5      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 359       | 50.85%  |
| AMD                          | 104       | 14.73%  |
| Samsung Electronics          | 71        | 10.06%  |
| SanDisk                      | 36        | 5.1%    |
| SK hynix                     | 15        | 2.12%   |
| Toshiba America Info Systems | 14        | 1.98%   |
| Nvidia                       | 14        | 1.98%   |
| KIOXIA                       | 14        | 1.98%   |
| Micron Technology            | 12        | 1.7%    |
| ASMedia Technology           | 11        | 1.56%   |
| Marvell Technology Group     | 10        | 1.42%   |
| Phison Electronics           | 8         | 1.13%   |
| Micron/Crucial Technology    | 6         | 0.85%   |
| JMicron Technology           | 5         | 0.71%   |
| Union Memory (Shenzhen)      | 4         | 0.57%   |
| Silicon Motion               | 4         | 0.57%   |
| LSI Logic / Symbios Logic    | 4         | 0.57%   |
| Kingston Technology Company  | 4         | 0.57%   |
| Realtek Semiconductor        | 2         | 0.28%   |
| ULi Electronics              | 1         | 0.14%   |
| Transcend                    | 1         | 0.14%   |
| Silicon Image                | 1         | 0.14%   |
| Seagate Technology           | 1         | 0.14%   |
| O2 Micro                     | 1         | 0.14%   |
| Lite-On Technology           | 1         | 0.14%   |
| Broadcom / LSI               | 1         | 0.14%   |
| ADATA Technology             | 1         | 0.14%   |
| Adaptec                      | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 82        | 10.09%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 45        | 5.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 37        | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22        | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 21        | 2.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16        | 1.97%   |
| Samsung NVMe SSD Controller 980                                                         | 15        | 1.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15        | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 1.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 14        | 1.72%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 13        | 1.6%    |
| Micron NVMe Storage Controller                                                          | 12        | 1.48%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 12        | 1.48%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11        | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 11        | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.23%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 9         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 1.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 8         | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8         | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 0.98%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 0.86%   |
| SanDisk Non-Volatile memory controller                                                  | 6         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 0.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 401       | 56.16%  |
| NVMe | 193       | 27.03%  |
| IDE  | 73        | 10.22%  |
| RAID | 43        | 6.02%   |
| SCSI | 4         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 423       | 74.47%  |
| AMD    | 137       | 24.12%  |
| ARM    | 8         | 1.41%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 13        | 2.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.4%    |
| ARM Processor                                 | 8         | 1.4%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.23%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 1.05%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 6         | 1.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.7%    |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.7%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.7%    |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.53%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.53%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.53%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.53%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 3         | 0.53%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.53%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.53%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.53%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.53%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.53%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 117       | 20.49%  |
| Intel Core i7           | 111       | 19.44%  |
| Other                   | 56        | 9.81%   |
| Intel Core i3           | 42        | 7.36%   |
| AMD Ryzen 5             | 31        | 5.43%   |
| Intel Celeron           | 26        | 4.55%   |
| Intel Core 2 Duo        | 25        | 4.38%   |
| AMD Ryzen 7             | 24        | 4.2%    |
| AMD Ryzen 9             | 12        | 2.1%    |
| Intel Atom              | 10        | 1.75%   |
| Intel Xeon              | 9         | 1.58%   |
| Intel Pentium           | 9         | 1.58%   |
| Intel Core 2 Quad       | 8         | 1.4%    |
| AMD FX                  | 6         | 1.05%   |
| AMD Athlon 64 X2        | 6         | 1.05%   |
| AMD Ryzen 3             | 5         | 0.88%   |
| Intel Pentium Dual-Core | 4         | 0.7%    |
| AMD A8                  | 4         | 0.7%    |
| AMD A6                  | 4         | 0.7%    |
| Intel Pentium 4         | 3         | 0.53%   |
| Intel Core 2            | 3         | 0.53%   |
| AMD Ryzen 7 PRO         | 3         | 0.53%   |
| AMD Ryzen 5 PRO         | 3         | 0.53%   |
| AMD E1                  | 3         | 0.53%   |
| AMD Athlon II X4        | 3         | 0.53%   |
| Intel Pentium Silver    | 2         | 0.35%   |
| Intel Core m3           | 2         | 0.35%   |
| Intel Core i9           | 2         | 0.35%   |
| Intel Celeron Dual-Core | 2         | 0.35%   |
| AMD Ryzen Threadripper  | 2         | 0.35%   |
| AMD Ryzen Embedded      | 2         | 0.35%   |
| AMD PRO A10             | 2         | 0.35%   |
| AMD Phenom II X6        | 2         | 0.35%   |
| AMD Phenom II X4        | 2         | 0.35%   |
| AMD E2                  | 2         | 0.35%   |
| AMD A4                  | 2         | 0.35%   |
| AMD A10                 | 2         | 0.35%   |
| Intel Xeon Platinum     | 1         | 0.18%   |
| Intel Pentium M         | 1         | 0.18%   |
| Intel Pentium III       | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 236       | 41.48%  |
| 2       | 207       | 36.38%  |
| 6       | 44        | 7.73%   |
| 8       | 35        | 6.15%   |
| 1       | 17        | 2.99%   |
| 12      | 16        | 2.81%   |
| 14      | 5         | 0.88%   |
| 3       | 3         | 0.53%   |
| 10      | 2         | 0.35%   |
| 96      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |
| 16      | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 561       | 98.94%  |
| 2      | 6         | 1.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 380       | 66.67%  |
| 1       | 189       | 33.16%  |
| Unknown | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 549       | 96.49%  |
| Unknown        | 17        | 2.99%   |
| 32-bit         | 3         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 28.35%  |
| 0x306a9    | 37        | 6.28%   |
| 0x206a7    | 27        | 4.58%   |
| 0x306c3    | 23        | 3.9%    |
| 0x1067a    | 22        | 3.74%   |
| 0x806ec    | 18        | 3.06%   |
| 0x806e9    | 18        | 3.06%   |
| 0x806c1    | 16        | 2.72%   |
| 0x806ea    | 14        | 2.38%   |
| 0x406e3    | 12        | 2.04%   |
| 0x906ea    | 10        | 1.7%    |
| 0x906e9    | 10        | 1.7%    |
| 0x40651    | 10        | 1.7%    |
| 0x10676    | 8         | 1.36%   |
| 0xa0652    | 7         | 1.19%   |
| 0x406c4    | 7         | 1.19%   |
| 0x30678    | 7         | 1.19%   |
| 0x08701021 | 7         | 1.19%   |
| 0x08108109 | 7         | 1.19%   |
| 0x506e3    | 6         | 1.02%   |
| 0x306d4    | 6         | 1.02%   |
| 0x0a50000c | 6         | 1.02%   |
| 0x20655    | 5         | 0.85%   |
| 0x08108102 | 5         | 0.85%   |
| 0x0810100b | 5         | 0.85%   |
| 0x0800820d | 5         | 0.85%   |
| 0x06006705 | 5         | 0.85%   |
| 0xa0653    | 4         | 0.68%   |
| 0x6fd      | 4         | 0.68%   |
| 0x6fb      | 4         | 0.68%   |
| 0x206c2    | 4         | 0.68%   |
| 0x0600611a | 4         | 0.68%   |
| 0x906a3    | 3         | 0.51%   |
| 0x806d1    | 3         | 0.51%   |
| 0x706e5    | 3         | 0.51%   |
| 0x706a8    | 3         | 0.51%   |
| 0x106ca    | 3         | 0.51%   |
| 0x08701013 | 3         | 0.51%   |
| 0x08608103 | 3         | 0.51%   |
| 0x08600106 | 3         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 15.67%  |
| IvyBridge        | 49        | 8.63%   |
| Haswell          | 42        | 7.39%   |
| SandyBridge      | 39        | 6.87%   |
| Penryn           | 31        | 5.46%   |
| Unknown          | 31        | 5.46%   |
| TigerLake        | 27        | 4.75%   |
| Skylake          | 26        | 4.58%   |
| Zen 2            | 25        | 4.4%    |
| Zen+             | 23        | 4.05%   |
| Silvermont       | 19        | 3.35%   |
| Westmere         | 17        | 2.99%   |
| Core             | 15        | 2.64%   |
| CometLake        | 13        | 2.29%   |
| Zen              | 12        | 2.11%   |
| Excavator        | 11        | 1.94%   |
| Zen 3            | 10        | 1.76%   |
| K10              | 10        | 1.76%   |
| K8 Hammer        | 9         | 1.58%   |
| Piledriver       | 8         | 1.41%   |
| IceLake          | 8         | 1.41%   |
| Goldmont plus    | 8         | 1.41%   |
| Broadwell        | 8         | 1.41%   |
| Nehalem          | 6         | 1.06%   |
| Bonnell          | 5         | 0.88%   |
| Puma             | 4         | 0.7%    |
| P6               | 4         | 0.7%    |
| NetBurst         | 4         | 0.7%    |
| Bobcat           | 4         | 0.7%    |
| Alderlake Hybrid | 4         | 0.7%    |
| Jaguar           | 3         | 0.53%   |
| Goldmont         | 2         | 0.35%   |
| Steamroller      | 1         | 0.18%   |
| Bulldozer        | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 324       | 49.24%  |
| Nvidia            | 172       | 26.14%  |
| AMD               | 161       | 24.47%  |
| ASPEED Technology | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 3.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 3.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 3.38%   |
| Intel HD Graphics 620                                                                    | 18        | 2.64%   |
| Intel UHD Graphics 620                                                                   | 16        | 2.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 2.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 1.76%   |
| Intel HD Graphics 630                                                                    | 11        | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.32%   |
| AMD Renoir                                                                               | 9         | 1.32%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 1.17%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 8         | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.03%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.03%   |
| AMD Lucienne                                                                             | 7         | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 0.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.88%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.88%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 0.88%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 0.88%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.73%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 243       | 42.26%  |
| 1 x AMD        | 130       | 22.61%  |
| 1 x Nvidia     | 95        | 16.52%  |
| Intel + Nvidia | 65        | 11.3%   |
| 2 x AMD        | 13        | 2.26%   |
| AMD + Nvidia   | 11        | 1.91%   |
| Other          | 8         | 1.39%   |
| Intel + AMD    | 7         | 1.22%   |
| 2 x Nvidia     | 1         | 0.17%   |
| 2 x Intel      | 1         | 0.17%   |
| 1 x ASPEED     | 1         | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 459       | 79.69%  |
| Proprietary | 87        | 15.1%   |
| Unknown     | 30        | 5.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 331       | 56.2%   |
| 0.01-0.5   | 66        | 11.21%  |
| 1.01-2.0   | 54        | 9.17%   |
| 3.01-4.0   | 48        | 8.15%   |
| 0.51-1.0   | 43        | 7.3%    |
| 7.01-8.0   | 22        | 3.74%   |
| 5.01-6.0   | 16        | 2.72%   |
| 2.01-3.0   | 4         | 0.68%   |
| 8.01-16.0  | 4         | 0.68%   |
| 16.01-24.0 | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 73        | 11.61%  |
| Dell                    | 69        | 10.97%  |
| BOE                     | 69        | 10.97%  |
| LG Display              | 59        | 9.38%   |
| Samsung Electronics     | 53        | 8.43%   |
| Chimei Innolux          | 36        | 5.72%   |
| Hewlett-Packard         | 21        | 3.34%   |
| Sharp                   | 20        | 3.18%   |
| Acer                    | 20        | 3.18%   |
| BenQ                    | 18        | 2.86%   |
| Apple                   | 17        | 2.7%    |
| Philips                 | 16        | 2.54%   |
| Goldstar                | 16        | 2.54%   |
| ViewSonic               | 13        | 2.07%   |
| Lenovo                  | 13        | 2.07%   |
| AOC                     | 12        | 1.91%   |
| Iiyama                  | 11        | 1.75%   |
| Chi Mei Optoelectronics | 8         | 1.27%   |
| PANDA                   | 7         | 1.11%   |
| Sony                    | 5         | 0.79%   |
| Vestel Elektronik       | 4         | 0.64%   |
| LG Philips              | 4         | 0.64%   |
| InfoVision              | 4         | 0.64%   |
| Ancor Communications    | 4         | 0.64%   |
| ___                     | 3         | 0.48%   |
| Unknown                 | 3         | 0.48%   |
| Toshiba                 | 3         | 0.48%   |
| MSI                     | 3         | 0.48%   |
| HannStar                | 3         | 0.48%   |
| CSO                     | 3         | 0.48%   |
| Valve                   | 2         | 0.32%   |
| OEM                     | 2         | 0.32%   |
| MiTAC                   | 2         | 0.32%   |
| HKC                     | 2         | 0.32%   |
| CPT                     | 2         | 0.32%   |
| BOE Technology Group    | 2         | 0.32%   |
| ASUSTek Computer        | 2         | 0.32%   |
| Unknown                 | 2         | 0.32%   |
| WIT                     | 1         | 0.16%   |
| Targa Visionary         | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 9         | 1.36%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 8         | 1.21%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                    | 8         | 1.21%   |
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                 | 5         | 0.76%   |
| BOE LCD Monitor BOE0964 1920x1200 286x179mm 13.3-inch                | 5         | 0.76%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch | 4         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 4         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch | 4         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.61%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 4         | 0.61%   |
| ___ LCDTV16 ___9000 1360x768                                         | 3         | 0.45%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 3         | 0.45%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 3         | 0.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 3         | 0.45%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.45%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.45%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 0.45%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                     | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 3         | 0.45%   |
| BenQ G2222HDL BNQ7859 1920x1080 477x268mm 21.5-inch                  | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.45%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.3%    |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.3%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.3%    |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.3%    |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.3%    |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 610x350mm 27.7-inch    | 2         | 0.3%    |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch  | 2         | 0.3%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch | 2         | 0.3%    |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch    | 2         | 0.3%    |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch              | 2         | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 2         | 0.3%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.3%    |
| LG Philips LCD Monitor LPLA104 1440x900 367x230mm 17.1-inch          | 2         | 0.3%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.3%    |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch         | 2         | 0.3%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 273       | 45.5%   |
| 1366x768 (WXGA)    | 98        | 16.33%  |
| 3840x2160 (4K)     | 37        | 6.17%   |
| 2560x1440 (QHD)    | 35        | 5.83%   |
| 1920x1200 (WUXGA)  | 22        | 3.67%   |
| 1600x900 (HD+)     | 20        | 3.33%   |
| 1440x900 (WXGA+)   | 17        | 2.83%   |
| 1280x1024 (SXGA)   | 15        | 2.5%    |
| 1280x800 (WXGA)    | 13        | 2.17%   |
| 3440x1440          | 10        | 1.67%   |
| 1360x768           | 8         | 1.33%   |
| Unknown            | 8         | 1.33%   |
| 1680x1050 (WSXGA+) | 6         | 1%      |
| 3840x1080          | 4         | 0.67%   |
| 2560x1600          | 4         | 0.67%   |
| 800x1280           | 3         | 0.5%    |
| 3840x2400          | 3         | 0.5%    |
| 1600x1200          | 3         | 0.5%    |
| 1024x600           | 3         | 0.5%    |
| 3456x2160          | 2         | 0.33%   |
| 3200x1800 (QHD+)   | 2         | 0.33%   |
| 2560x1080          | 2         | 0.33%   |
| 1920x540           | 2         | 0.33%   |
| 1024x768 (XGA)     | 2         | 0.33%   |
| 6400x2160          | 1         | 0.17%   |
| 5280x2560          | 1         | 0.17%   |
| 4480x1440          | 1         | 0.17%   |
| 3600x1080          | 1         | 0.17%   |
| 2880x1800          | 1         | 0.17%   |
| 2256x1504          | 1         | 0.17%   |
| 2160x1440          | 1         | 0.17%   |
| 1280x960           | 1         | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 164       | 25.99%  |
| 14      | 62        | 9.83%   |
| 27      | 60        | 9.51%   |
| 13      | 54        | 8.56%   |
| 24      | 45        | 7.13%   |
| 21      | 39        | 6.18%   |
| 23      | 38        | 6.02%   |
| Unknown | 28        | 4.44%   |
| 17      | 27        | 4.28%   |
| 12      | 16        | 2.54%   |
| 19      | 15        | 2.38%   |
| 34      | 12        | 1.9%    |
| 31      | 11        | 1.74%   |
| 84      | 7         | 1.11%   |
| 18      | 7         | 1.11%   |
| 11      | 6         | 0.95%   |
| 72      | 5         | 0.79%   |
| 32      | 5         | 0.79%   |
| 20      | 5         | 0.79%   |
| 25      | 3         | 0.48%   |
| 22      | 3         | 0.48%   |
| 10      | 3         | 0.48%   |
| 49      | 2         | 0.32%   |
| 40      | 2         | 0.32%   |
| 29      | 2         | 0.32%   |
| 16      | 2         | 0.32%   |
| 7       | 2         | 0.32%   |
| 65      | 1         | 0.16%   |
| 46      | 1         | 0.16%   |
| 35      | 1         | 0.16%   |
| 33      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 3       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 245       | 39.39%  |
| 501-600     | 131       | 21.06%  |
| 401-500     | 63        | 10.13%  |
| 201-300     | 62        | 9.97%   |
| 351-400     | 32        | 5.14%   |
| Unknown     | 28        | 4.5%    |
| 601-700     | 21        | 3.38%   |
| 701-800     | 18        | 2.89%   |
| 1501-2000   | 12        | 1.93%   |
| 1001-1500   | 4         | 0.64%   |
| 801-900     | 3         | 0.48%   |
| 1-100       | 3         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 418       | 76.42%  |
| 16/10   | 65        | 11.88%  |
| Unknown | 22        | 4.02%   |
| 5/4     | 15        | 2.74%   |
| 21/9    | 13        | 2.38%   |
| 4/3     | 6         | 1.1%    |
| 3/2     | 4         | 0.73%   |
| 0.67    | 2         | 0.37%   |
| 6/5     | 1         | 0.18%   |
| 32/9    | 1         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 160       | 25.4%   |
| 201-250        | 101       | 16.03%  |
| 81-90          | 83        | 13.17%  |
| 301-350        | 62        | 9.84%   |
| 71-80          | 34        | 5.4%    |
| 351-500        | 30        | 4.76%   |
| 151-200        | 29        | 4.6%    |
| Unknown        | 28        | 4.44%   |
| 251-300        | 19        | 3.02%   |
| 61-70          | 15        | 2.38%   |
| 121-130        | 15        | 2.38%   |
| 141-150        | 14        | 2.22%   |
| More than 1000 | 13        | 2.06%   |
| 51-60          | 6         | 0.95%   |
| 111-120        | 5         | 0.79%   |
| 501-1000       | 5         | 0.79%   |
| 131-140        | 4         | 0.63%   |
| 41-50          | 3         | 0.48%   |
| 1-40           | 3         | 0.48%   |
| 91-100         | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 185       | 30.53%  |
| 51-100        | 177       | 29.21%  |
| 101-120       | 143       | 23.6%   |
| 161-240       | 44        | 7.26%   |
| Unknown       | 28        | 4.62%   |
| More than 240 | 15        | 2.48%   |
| 1-50          | 14        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 443       | 75.47%  |
| 2     | 98        | 16.7%   |
| 0     | 27        | 4.6%    |
| 3     | 18        | 3.07%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 312       | 34.63%  |
| Realtek Semiconductor             | 284       | 31.52%  |
| Qualcomm Atheros                  | 83        | 9.21%   |
| Broadcom                          | 59        | 6.55%   |
| Ralink Technology                 | 17        | 1.89%   |
| TP-Link                           | 13        | 1.44%   |
| Nvidia                            | 13        | 1.44%   |
| MediaTek                          | 12        | 1.33%   |
| Broadcom Limited                  | 12        | 1.33%   |
| Ralink                            | 11        | 1.22%   |
| Marvell Technology Group          | 10        | 1.11%   |
| Microsoft                         | 7         | 0.78%   |
| Lenovo                            | 6         | 0.67%   |
| Samsung Electronics               | 5         | 0.55%   |
| OPPO Electronics                  | 5         | 0.55%   |
| Ericsson Business Mobile Networks | 5         | 0.55%   |
| ASIX Electronics                  | 5         | 0.55%   |
| NetGear                           | 3         | 0.33%   |
| DisplayLink                       | 3         | 0.33%   |
| Xiaomi                            | 2         | 0.22%   |
| Qualcomm Atheros Communications   | 2         | 0.22%   |
| Qualcomm                          | 2         | 0.22%   |
| Microchip Technology              | 2         | 0.22%   |
| ICS Advent                        | 2         | 0.22%   |
| Huawei Technologies               | 2         | 0.22%   |
| Dell                              | 2         | 0.22%   |
| Belkin Components                 | 2         | 0.22%   |
| Xilinx                            | 1         | 0.11%   |
| Van Ooijen Technische Informatica | 1         | 0.11%   |
| ULi Electronics                   | 1         | 0.11%   |
| Toshiba                           | 1         | 0.11%   |
| T & A Mobile Phones               | 1         | 0.11%   |
| Standard Microsystems             | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.11%   |
| NetXen Incorporated               | 1         | 0.11%   |
| LSI                               | 1         | 0.11%   |
| LG Electronics                    | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| IMC Networks                      | 1         | 0.11%   |
| HMD Global                        | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 175       | 16.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 3.76%   |
| Intel Wi-Fi 6 AX200                                               | 37        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 3.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 2.54%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 18        | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 17        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14        | 1.32%   |
| Intel Wireless 7260                                               | 14        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.13%   |
| Realtek 802.11ac NIC                                              | 11        | 1.03%   |
| Intel Wireless 8260                                               | 11        | 1.03%   |
| Intel Wireless 7265                                               | 11        | 1.03%   |
| Intel I211 Gigabit Network Connection                             | 10        | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 10        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.85%   |
| Intel Wireless-AC 9260                                            | 9         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                   | 8         | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.75%   |
| Intel Wireless 3165                                               | 8         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 7         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                    | 6         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.56%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 243       | 47.37%  |
| Realtek Semiconductor           | 78        | 15.2%   |
| Qualcomm Atheros                | 74        | 14.42%  |
| Broadcom                        | 41        | 7.99%   |
| Ralink Technology               | 17        | 3.31%   |
| TP-Link                         | 13        | 2.53%   |
| Ralink                          | 11        | 2.14%   |
| MediaTek                        | 11        | 2.14%   |
| Microsoft                       | 6         | 1.17%   |
| Broadcom Limited                | 4         | 0.78%   |
| NetGear                         | 3         | 0.58%   |
| Qualcomm Atheros Communications | 2         | 0.39%   |
| Qualcomm                        | 2         | 0.39%   |
| Dell                            | 2         | 0.39%   |
| Belkin Components               | 2         | 0.39%   |
| LG Electronics                  | 1         | 0.19%   |
| IMC Networks                    | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |
| Apple                           | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 37        | 7.14%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 3.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 3.67%   |
| Intel Wireless 8265 / 8275                                              | 18        | 3.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 3.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 2.7%    |
| Intel Wireless 7260                                                     | 14        | 2.7%    |
| Realtek 802.11ac NIC                                                    | 11        | 2.12%   |
| Intel Wireless 8260                                                     | 11        | 2.12%   |
| Intel Wireless 7265                                                     | 11        | 2.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.74%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.74%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.54%   |
| Intel Wireless 3165                                                     | 8         | 1.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 7         | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.35%   |
| Ralink RT5370 Wireless Adapter                                          | 6         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.97%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 5         | 0.97%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 5         | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.77%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 4         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 247       | 47.59%  |
| Intel                         | 158       | 30.44%  |
| Broadcom                      | 26        | 5.01%   |
| Qualcomm Atheros              | 17        | 3.28%   |
| Nvidia                        | 13        | 2.5%    |
| Marvell Technology Group      | 10        | 1.93%   |
| Broadcom Limited              | 9         | 1.73%   |
| Lenovo                        | 6         | 1.16%   |
| OPPO Electronics              | 5         | 0.96%   |
| ASIX Electronics              | 5         | 0.96%   |
| Samsung Electronics           | 3         | 0.58%   |
| DisplayLink                   | 3         | 0.58%   |
| Xiaomi                        | 2         | 0.39%   |
| ICS Advent                    | 2         | 0.39%   |
| Xilinx                        | 1         | 0.19%   |
| ULi Electronics               | 1         | 0.19%   |
| T & A Mobile Phones           | 1         | 0.19%   |
| Standard Microsystems         | 1         | 0.19%   |
| OnePlus Technology (Shenzhen) | 1         | 0.19%   |
| NetXen Incorporated           | 1         | 0.19%   |
| Microsoft                     | 1         | 0.19%   |
| Microchip Technology          | 1         | 0.19%   |
| JMicron Technology            | 1         | 0.19%   |
| Huawei Technologies           | 1         | 0.19%   |
| HMD Global                    | 1         | 0.19%   |
| ADMtek                        | 1         | 0.19%   |
| 3Com                          | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 175       | 33.14%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 7.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 6.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 5.11%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 10        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 1.52%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.52%   |
| Nvidia MCP79 Ethernet                                             | 7         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 1.14%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 5         | 0.95%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.95%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.76%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.57%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.57%   |
| Intel Ethernet Controller I225-LM                                 | 3         | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.57%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.57%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 3         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.57%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 493       | 49.85%  |
| WiFi     | 478       | 48.33%  |
| Modem    | 18        | 1.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 353       | 58.93%  |
| Ethernet | 246       | 41.07%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 328       | 57.34%  |
| 1     | 221       | 38.64%  |
| 3     | 11        | 1.92%   |
| 0     | 10        | 1.75%   |
| 6     | 1         | 0.17%   |
| 4     | 1         | 0.17%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 501       | 86.83%  |
| Yes  | 76        | 13.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 196       | 50.65%  |
| Realtek Semiconductor           | 32        | 8.27%   |
| Cambridge Silicon Radio         | 23        | 5.94%   |
| Broadcom                        | 22        | 5.68%   |
| Qualcomm Atheros Communications | 20        | 5.17%   |
| IMC Networks                    | 20        | 5.17%   |
| Apple                           | 17        | 4.39%   |
| Lite-On Technology              | 13        | 3.36%   |
| Dell                            | 8         | 2.07%   |
| ASUSTek Computer                | 7         | 1.81%   |
| Foxconn / Hon Hai               | 6         | 1.55%   |
| Hewlett-Packard                 | 5         | 1.29%   |
| Toshiba                         | 4         | 1.03%   |
| Realtek                         | 3         | 0.78%   |
| TP-Link                         | 2         | 0.52%   |
| Foxconn International           | 2         | 0.52%   |
| Belkin Components               | 2         | 0.52%   |
| Ralink                          | 1         | 0.26%   |
| MediaTek                        | 1         | 0.26%   |
| ISSC                            | 1         | 0.26%   |
| Edimax Technology               | 1         | 0.26%   |
| Conwise Technology              | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 72        | 18.56%  |
| Intel AX201 Bluetooth                               | 39        | 10.05%  |
| Intel AX200 Bluetooth                               | 34        | 8.76%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 5.93%   |
| Realtek Bluetooth Radio                             | 21        | 5.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 5.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 2.84%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 2.06%   |
| Intel Bluetooth Device                              | 8         | 2.06%   |
| Apple Bluetooth Host Controller                     | 8         | 2.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.55%   |
| Intel AX210 Bluetooth                               | 6         | 1.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.29%   |
| IMC Networks Bluetooth Device                       | 5         | 1.29%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.03%   |
| IMC Networks Wireless_Device                        | 4         | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.03%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 1.03%   |
| Apple Bluetooth HCI                                 | 4         | 1.03%   |
| Realtek Bluetooth Radio                             | 3         | 0.77%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.77%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.77%   |
| TP-Link UB500 Adapter                               | 2         | 0.52%   |
| Toshiba Bluetooth Device                            | 2         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.52%   |
| Lite-On Wireless_Device                             | 2         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.52%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 404       | 50.19%  |
| AMD                                             | 172       | 21.37%  |
| Nvidia                                          | 131       | 16.27%  |
| Plantronics                                     | 11        | 1.37%   |
| Realtek Semiconductor                           | 10        | 1.24%   |
| Creative Labs                                   | 7         | 0.87%   |
| Logitech                                        | 6         | 0.75%   |
| GN Netcom                                       | 6         | 0.75%   |
| C-Media Electronics                             | 6         | 0.75%   |
| Creative Technology                             | 5         | 0.62%   |
| Lenovo                                          | 4         | 0.5%    |
| Kingston Technology                             | 4         | 0.5%    |
| RODE Microphones                                | 3         | 0.37%   |
| Texas Instruments                               | 2         | 0.25%   |
| Sony                                            | 2         | 0.25%   |
| Micronas                                        | 2         | 0.25%   |
| JMTek                                           | 2         | 0.25%   |
| Ensoniq                                         | 2         | 0.25%   |
| Blue Microphones                                | 2         | 0.25%   |
| VIA Technologies                                | 1         | 0.12%   |
| ULi Electronics                                 | 1         | 0.12%   |
| Turtle Beach                                    | 1         | 0.12%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.12%   |
| SAVITECH                                        | 1         | 0.12%   |
| Razer USA                                       | 1         | 0.12%   |
| No brand                                        | 1         | 0.12%   |
| Native Instruments                              | 1         | 0.12%   |
| M-Audio                                         | 1         | 0.12%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.12%   |
| Huawei Technologies                             | 1         | 0.12%   |
| Guangzhou FiiO Electronics                      | 1         | 0.12%   |
| Giga-Byte Technology                            | 1         | 0.12%   |
| Focusrite-Novation                              | 1         | 0.12%   |
| ESS Technology                                  | 1         | 0.12%   |
| DSEA A/S                                        | 1         | 0.12%   |
| Corsair                                         | 1         | 0.12%   |
| Conexant Systems                                | 1         | 0.12%   |
| BEHRINGER International                         | 1         | 0.12%   |
| AudioQuest                                      | 1         | 0.12%   |
| AUDIOLAB                                        | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 55        | 5.78%   |
| AMD Family 17h/19h HD Audio Controller                                            | 54        | 5.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 44        | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 42        | 4.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 26        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 25        | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 21        | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 19        | 2%      |
| AMD Starship/Matisse HD Audio Controller                                          | 18        | 1.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 18        | 1.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 16        | 1.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 16        | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                        | 15        | 1.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 15        | 1.58%   |
| AMD FCH Azalia Controller                                                         | 15        | 1.58%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 15        | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 13        | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 13        | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                          | 13        | 1.37%   |
| Nvidia GP106 High Definition Audio Controller                                     | 12        | 1.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                             | 12        | 1.26%   |
| Intel 8 Series HD Audio Controller                                                | 12        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                         | 11        | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 1.16%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11        | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 11        | 1.16%   |
| Realtek Semiconductor USB Audio                                                   | 10        | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                     | 10        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 10        | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9         | 0.95%   |
| Nvidia GM204 High Definition Audio Controller                                     | 8         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 8         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 8         | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8         | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8         | 0.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 8         | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8         | 0.84%   |
| Plantronics Poly Voyager Focus 2 Series                                           | 7         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 71        | 20.76%  |
| SK hynix            | 63        | 18.42%  |
| Micron Technology   | 36        | 10.53%  |
| Crucial             | 33        | 9.65%   |
| Unknown             | 32        | 9.36%   |
| Corsair             | 30        | 8.77%   |
| Kingston            | 29        | 8.48%   |
| Ramaxel Technology  | 8         | 2.34%   |
| G.Skill             | 8         | 2.34%   |
| Elpida              | 5         | 1.46%   |
| Unknown (ABCD)      | 4         | 1.17%   |
| Team                | 3         | 0.88%   |
| Patriot             | 3         | 0.88%   |
| Nanya Technology    | 3         | 0.88%   |
| Apacer              | 2         | 0.58%   |
| A-DATA Technology   | 2         | 0.58%   |
| A Force             | 2         | 0.58%   |
| Transcend           | 1         | 0.29%   |
| Toshiba             | 1         | 0.29%   |
| SHARETRONIC         | 1         | 0.29%   |
| OSV                 | 1         | 0.29%   |
| Infineon            | 1         | 0.29%   |
| CSX                 | 1         | 0.29%   |
| 4ea5                | 1         | 0.29%   |
| Unknown             | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 1.62%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.35%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 1.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.81%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.81%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 3         | 0.81%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 0.81%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 3         | 0.81%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 0.81%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.54%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.54%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 2         | 0.54%   |
| SK hynix RAM HMT451U6BFR8A-PB 4096MB DIMM DDR3 1648MT/s          | 2         | 0.54%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.54%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.54%   |
| SK hynix RAM HMT351U6CFR8C-H9 4096MB DIMM DDR3 1600MT/s          | 2         | 0.54%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.54%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.54%   |
| SK hynix RAM H54G56CYRBX247N 8GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.54%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.54%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.54%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.54%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.54%   |
| Ramaxel RAM RMSA3230KE68H9F2133 4GB SODIMM DDR4 2133MT/s         | 2         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 135       | 45.3%   |
| DDR3    | 90        | 30.2%   |
| LPDDR4  | 17        | 5.7%    |
| DDR2    | 14        | 4.7%    |
| Unknown | 13        | 4.36%   |
| SDRAM   | 10        | 3.36%   |
| LPDDR3  | 7         | 2.35%   |
| DDR5    | 6         | 2.01%   |
| DDR     | 3         | 1.01%   |
| DRAM    | 2         | 0.67%   |
| LPDDR5  | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 172       | 57.53%  |
| DIMM         | 96        | 32.11%  |
| Row Of Chips | 24        | 8.03%   |
| Chip         | 4         | 1.34%   |
| Unknown      | 3         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 123       | 37.85%  |
| 4096  | 83        | 25.54%  |
| 16384 | 50        | 15.38%  |
| 2048  | 40        | 12.31%  |
| 32768 | 13        | 4%      |
| 1024  | 12        | 3.69%   |
| 128   | 2         | 0.62%   |
| 512   | 1         | 0.31%   |
| 256   | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 60        | 18.46%  |
| 2667    | 42        | 12.92%  |
| 3200    | 41        | 12.62%  |
| 2400    | 30        | 9.23%   |
| 2133    | 21        | 6.46%   |
| 1333    | 17        | 5.23%   |
| 800     | 12        | 3.69%   |
| 667     | 10        | 3.08%   |
| 4267    | 9         | 2.77%   |
| 1334    | 8         | 2.46%   |
| 3600    | 7         | 2.15%   |
| 3266    | 7         | 2.15%   |
| 4800    | 6         | 1.85%   |
| 1867    | 6         | 1.85%   |
| 1067    | 5         | 1.54%   |
| Unknown | 5         | 1.54%   |
| 8400    | 3         | 0.92%   |
| 3533    | 3         | 0.92%   |
| 1866    | 3         | 0.92%   |
| 1800    | 3         | 0.92%   |
| 533     | 3         | 0.92%   |
| 4266    | 2         | 0.62%   |
| 4199    | 2         | 0.62%   |
| 3400    | 2         | 0.62%   |
| 1648    | 2         | 0.62%   |
| 1066    | 2         | 0.62%   |
| 975     | 2         | 0.62%   |
| 6400    | 1         | 0.31%   |
| 5200    | 1         | 0.31%   |
| 3800    | 1         | 0.31%   |
| 3733    | 1         | 0.31%   |
| 3000    | 1         | 0.31%   |
| 2933    | 1         | 0.31%   |
| 2733    | 1         | 0.31%   |
| 2666    | 1         | 0.31%   |
| 2267    | 1         | 0.31%   |
| 2048    | 1         | 0.31%   |
| 1639    | 1         | 0.31%   |
| 400     | 1         | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| STMicroelectronics  | 2         | 28.57%  |
| Canon               | 2         | 28.57%  |
| Brother Industries  | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 28.57%  |
| Samsung M2070 Series                                      | 1         | 14.29%  |
| Canon TS5300 series                                       | 1         | 14.29%  |
| Canon PIXMA MG2500 Series                                 | 1         | 14.29%  |
| Brother MFC-L2700DW                                       | 1         | 14.29%  |
| Brother HL-L2340D series                                  | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 85        | 23.29%  |
| Realtek Semiconductor                  | 40        | 10.96%  |
| Microdia                               | 34        | 9.32%   |
| IMC Networks                           | 32        | 8.77%   |
| Logitech                               | 25        | 6.85%   |
| Sunplus Innovation Technology          | 23        | 6.3%    |
| Quanta                                 | 17        | 4.66%   |
| Apple                                  | 15        | 4.11%   |
| Acer                                   | 15        | 4.11%   |
| Bison Electronics                      | 13        | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 2.47%   |
| Suyin                                  | 6         | 1.64%   |
| Samsung Electronics                    | 6         | 1.64%   |
| ALi                                    | 5         | 1.37%   |
| Syntek                                 | 4         | 1.1%    |
| Silicon Motion                         | 4         | 1.1%    |
| Microsoft                              | 4         | 1.1%    |
| Lite-On Technology                     | 4         | 1.1%    |
| Ricoh                                  | 3         | 0.82%   |
| Generalplus Technology                 | 2         | 0.55%   |
| Creative Technology                    | 2         | 0.55%   |
| Z-Star Microelectronics                | 1         | 0.27%   |
| Y Media                                | 1         | 0.27%   |
| WaveRider Communications               | 1         | 0.27%   |
| USB3.0 HD Audio Capture                | 1         | 0.27%   |
| Trust                                  | 1         | 0.27%   |
| SunplusIT                              | 1         | 0.27%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.27%   |
| Razer USA                              | 1         | 0.27%   |
| Nikon                                  | 1         | 0.27%   |
| MacroSilicon                           | 1         | 0.27%   |
| Luxvisions Innotech Limited            | 1         | 0.27%   |
| Lenovo                                 | 1         | 0.27%   |
| GenesysLogic Technology                | 1         | 0.27%   |
| GEMBIRD                                | 1         | 0.27%   |
| DigiTech                               | 1         | 0.27%   |
| ARC International                      | 1         | 0.27%   |
| Alcor Micro                            | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 20        | 5.43%   |
| Microdia Integrated_Webcam_HD              | 16        | 4.35%   |
| Realtek Integrated_Webcam_HD               | 15        | 4.08%   |
| Logitech HD Pro Webcam C920                | 11        | 2.99%   |
| IMC Networks Integrated Camera             | 11        | 2.99%   |
| Apple Built-in iSight                      | 10        | 2.72%   |
| Sunplus Integrated_Webcam_FHD              | 8         | 2.17%   |
| Chicony USB2.0 Camera                      | 7         | 1.9%    |
| Chicony HD WebCam                          | 7         | 1.9%    |
| Samsung Galaxy series, misc. (MTP mode)    | 6         | 1.63%   |
| IMC Networks USB2.0 HD UVC WebCam          | 6         | 1.63%   |
| Acer Integrated Camera                     | 6         | 1.63%   |
| Sunplus Integrated_Webcam_HD               | 5         | 1.36%   |
| Microdia Integrated Webcam                 | 5         | 1.36%   |
| Bison Integrated Camera                    | 5         | 1.36%   |
| Realtek Integrated Webcam HD               | 4         | 1.09%   |
| Chicony HP Wide Vision HD Camera           | 4         | 1.09%   |
| Realtek USB2.0 HD UVC WebCam               | 3         | 0.82%   |
| Microsoft LifeCam HD-3000                  | 3         | 0.82%   |
| Logitech Webcam C270                       | 3         | 0.82%   |
| Lite-On HP HD Camera                       | 3         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam               | 3         | 0.82%   |
| Chicony Lenovo EasyCamera                  | 3         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)    | 3         | 0.82%   |
| Chicony HP HD Camera                       | 3         | 0.82%   |
| Chicony EasyCamera                         | 3         | 0.82%   |
| Apple FaceTime HD Camera (Built-in)        | 3         | 0.82%   |
| ALi WebCam                                 | 3         | 0.82%   |
| Syntek Integrated Camera                   | 2         | 0.54%   |
| Syntek EasyCamera                          | 2         | 0.54%   |
| Suyin HP Truevision HD                     | 2         | 0.54%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 2         | 0.54%   |
| Sunplus HP HD Webcam [Fixed]               | 2         | 0.54%   |
| Realtek USB Camera                         | 2         | 0.54%   |
| Realtek Integrated Webcam                  | 2         | 0.54%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.54%   |
| Realtek HD WebCam                          | 2         | 0.54%   |
| Realtek EasyCamera                         | 2         | 0.54%   |
| Quanta USB2.0 HD UVC WebCam                | 2         | 0.54%   |
| Quanta ov9734_techfront_camera             | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 26        | 32.91%  |
| Validity Sensors           | 21        | 26.58%  |
| Shenzhen Goodix Technology | 18        | 22.78%  |
| Upek                       | 4         | 5.06%   |
| Elan Microelectronics      | 3         | 3.8%    |
| AuthenTec                  | 3         | 3.8%    |
| LighTuning Technology      | 2         | 2.53%   |
| STMicroelectronics         | 1         | 1.27%   |
| Focal-systems.Corp         | 1         | 1.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                         | 8         | 10.13%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 7.59%   |
| Shenzhen Goodix FingerPrint                                | 6         | 7.59%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 6.33%   |
| Unknown                                                    | 5         | 6.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 5.06%   |
| Shenzhen Goodix  Fingerprint Device                        | 4         | 5.06%   |
| Synaptics  WBDI                                            | 3         | 3.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 3.8%    |
| AuthenTec Fingerprint Sensor                               | 3         | 3.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 2.53%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 2.53%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 2.53%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 2.53%   |
| Validity Sensors Synaptics WBDI                            | 2         | 2.53%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 2.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 2.53%   |
| Elan ELAN:Fingerprint                                      | 2         | 2.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.27%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.27%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.27%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.27%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.27%   |
| Synaptics WBDI                                             | 1         | 1.27%   |
| Synaptics UWP WBDI Device                                  | 1         | 1.27%   |
| Synaptics UWP WBDI                                         | 1         | 1.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.27%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.27%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.27%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.27%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 29        | 60.42%  |
| Alcor Micro                       | 8         | 16.67%  |
| Upek                              | 5         | 10.42%  |
| O2 Micro                          | 4         | 8.33%   |
| Lenovo                            | 1         | 2.08%   |
| Free Software Initiative of Japan | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 14        | 29.17%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 10.42%  |
| Broadcom 5880                                                                | 5         | 10.42%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.08%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.08%   |
| Free Software Initiative of Japan Gnuk Token                                 | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 369       | 63.18%  |
| 1     | 164       | 28.08%  |
| 2     | 42        | 7.19%   |
| 3     | 8         | 1.37%   |
| 5     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 78        | 30%     |
| Net/wireless             | 54        | 20.77%  |
| Graphics card            | 43        | 16.54%  |
| Chipcard                 | 42        | 16.15%  |
| Multimedia controller    | 12        | 4.62%   |
| Communication controller | 7         | 2.69%   |
| Camera                   | 7         | 2.69%   |
| Storage                  | 5         | 1.92%   |
| Card reader              | 3         | 1.15%   |
| Bluetooth                | 3         | 1.15%   |
| Net/ethernet             | 2         | 0.77%   |
| Unassigned class         | 1         | 0.38%   |
| Storage/ata              | 1         | 0.38%   |
| Sound                    | 1         | 0.38%   |
| Modem                    | 1         | 0.38%   |

