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

Total: 903

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 83        | 13.65%  |
| Ubuntu 18.04       | 44        | 7.24%   |
| Ubuntu 22.04       | 28        | 4.61%   |
| Debian 11          | 20        | 3.29%   |
| Pop!_OS 22.04      | 15        | 2.47%   |
| OpenMandriva 4.2   | 12        | 1.97%   |
| Manjaro            | 11        | 1.81%   |
| Linux Mint 20.2    | 11        | 1.81%   |
| ArcoLinux Rolling  | 11        | 1.81%   |
| Arch               | 11        | 1.81%   |
| Linux Mint 20      | 10        | 1.64%   |
| Fedora 36          | 10        | 1.64%   |
| Debian 10          | 10        | 1.64%   |
| Ubuntu 19.04       | 9         | 1.48%   |
| Pop!_OS 21.10      | 9         | 1.48%   |
| Fedora 37          | 9         | 1.48%   |
| Arch Rolling       | 9         | 1.48%   |
| Zorin 16           | 8         | 1.32%   |
| Ubuntu 22.10       | 8         | 1.32%   |
| Pop!_OS 20.10      | 8         | 1.32%   |
| Linux Mint 21.1    | 8         | 1.32%   |
| Pop!_OS 20.04      | 7         | 1.15%   |
| OpenMandriva 4.3   | 7         | 1.15%   |
| Linux Mint 20.3    | 7         | 1.15%   |
| KDE neon 20.04     | 7         | 1.15%   |
| BlackPanther 18.1  | 7         | 1.15%   |
| Ubuntu 19.10       | 6         | 0.99%   |
| OpenMandriva 23.01 | 6         | 0.99%   |
| Linux Mint 21      | 6         | 0.99%   |
| Ubuntu 21.10       | 5         | 0.82%   |
| ROSA R11           | 5         | 0.82%   |
| ROSA R10           | 5         | 0.82%   |
| Lubuntu 20.04      | 5         | 0.82%   |
| Linux Mint 20.1    | 5         | 0.82%   |
| Linux Mint 19.3    | 5         | 0.82%   |
| Fedora 35          | 5         | 0.82%   |
| Fedora 33          | 5         | 0.82%   |
| Fedora 32          | 5         | 0.82%   |
| Zorin 15           | 4         | 0.66%   |
| Ubuntu 20.10       | 4         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 189       | 32.87%  |
| Linux Mint    | 59        | 10.26%  |
| Pop!_OS       | 39        | 6.78%   |
| Fedora        | 37        | 6.43%   |
| Debian        | 37        | 6.43%   |
| OpenMandriva  | 30        | 5.22%   |
| Manjaro       | 24        | 4.17%   |
| Arch          | 20        | 3.48%   |
| Kubuntu       | 14        | 2.43%   |
| Zorin         | 12        | 2.09%   |
| ROSA          | 12        | 2.09%   |
| ArcoLinux     | 11        | 1.91%   |
| Elementary    | 10        | 1.74%   |
| Lubuntu       | 8         | 1.39%   |
| KDE neon      | 8         | 1.39%   |
| BlackPanther  | 7         | 1.22%   |
| SteamOS       | 6         | 1.04%   |
| Ubuntu Unity  | 5         | 0.87%   |
| Endless       | 5         | 0.87%   |
| Xubuntu       | 4         | 0.7%    |
| Ubuntu Budgie | 4         | 0.7%    |
| openSUSE      | 4         | 0.7%    |
| Ubuntu MATE   | 3         | 0.52%   |
| Gentoo        | 3         | 0.52%   |
| Clear Linux   | 3         | 0.52%   |
| Peppermint    | 2         | 0.35%   |
| MX            | 2         | 0.35%   |
| LMDE          | 2         | 0.35%   |
| Kali          | 2         | 0.35%   |
| CentOS        | 2         | 0.35%   |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.23%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.79%   |
| 5.3.0-46-generic         | 10        | 1.49%   |
| 5.15.0-46-generic        | 8         | 1.19%   |
| 5.19.0-35-generic        | 7         | 1.04%   |
| 5.16.7-desktop-1omv4003  | 7         | 1.04%   |
| 5.15.0-56-generic        | 7         | 1.04%   |
| 5.4.0-52-generic         | 6         | 0.89%   |
| 5.15.0-52-generic        | 6         | 0.89%   |
| 4.18.16-desktop-1bP      | 6         | 0.89%   |
| 6.1.1-desktop-1omv2290   | 5         | 0.74%   |
| 5.4.0-91-generic         | 5         | 0.74%   |
| 5.4.0-48-generic         | 5         | 0.74%   |
| 5.19.0-29-generic        | 5         | 0.74%   |
| 5.15.0-67-generic        | 5         | 0.74%   |
| 5.11.0-27-generic        | 5         | 0.74%   |
| 6.2.6-desktop-1omv2390   | 4         | 0.6%    |
| 5.8.0-7630-generic       | 4         | 0.6%    |
| 5.8.0-43-generic         | 4         | 0.6%    |
| 5.4.0-72-generic         | 4         | 0.6%    |
| 5.4.0-47-generic         | 4         | 0.6%    |
| 5.4.0-31-generic         | 4         | 0.6%    |
| 5.4.0-29-generic         | 4         | 0.6%    |
| 5.4.0-26-generic         | 4         | 0.6%    |
| 5.3.0-28-generic         | 4         | 0.6%    |
| 5.19.0-38-generic        | 4         | 0.6%    |
| 5.15.0-60-generic        | 4         | 0.6%    |
| 5.15.0-48-generic        | 4         | 0.6%    |
| 4.18.0-15-generic        | 4         | 0.6%    |
| 6.0.6-76060006-generic   | 3         | 0.45%   |
| 6.0.12-76060006-generic  | 3         | 0.45%   |
| 5.8.0-53-generic         | 3         | 0.45%   |
| 5.8.0-41-generic         | 3         | 0.45%   |
| 5.4.0-77-generic         | 3         | 0.45%   |
| 5.4.0-7634-generic       | 3         | 0.45%   |
| 5.4.0-58-generic         | 3         | 0.45%   |
| 5.4.0-54-generic         | 3         | 0.45%   |
| 5.4.0-40-generic         | 3         | 0.45%   |
| 5.4.0-39-generic         | 3         | 0.45%   |
| 5.4.0-37-generic         | 3         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 115       | 18.23%  |
| 5.15.0  | 48        | 7.61%   |
| 4.15.0  | 36        | 5.71%   |
| 5.8.0   | 28        | 4.44%   |
| 5.19.0  | 27        | 4.28%   |
| 5.11.0  | 27        | 4.28%   |
| 5.3.0   | 26        | 4.12%   |
| 5.13.0  | 21        | 3.33%   |
| 5.10.0  | 19        | 3.01%   |
| 5.0.0   | 15        | 2.38%   |
| 5.10.14 | 12        | 1.9%    |
| 4.19.0  | 11        | 1.74%   |
| 4.18.0  | 11        | 1.74%   |
| 5.17.5  | 8         | 1.27%   |
| 5.16.7  | 7         | 1.11%   |
| 4.18.16 | 6         | 0.95%   |
| 6.1.1   | 5         | 0.79%   |
| 6.2.6   | 4         | 0.63%   |
| 6.0.6   | 4         | 0.63%   |
| 5.16.11 | 4         | 0.63%   |
| 4.9.60  | 4         | 0.63%   |
| 6.2.8   | 3         | 0.48%   |
| 6.2.0   | 3         | 0.48%   |
| 6.1.9   | 3         | 0.48%   |
| 6.0.12  | 3         | 0.48%   |
| 6.0.0   | 3         | 0.48%   |
| 5.8.14  | 3         | 0.48%   |
| 5.6.0   | 3         | 0.48%   |
| 5.18.0  | 3         | 0.48%   |
| 5.16.15 | 3         | 0.48%   |
| 5.15.12 | 3         | 0.48%   |
| 5.15.11 | 3         | 0.48%   |
| 5.12.4  | 3         | 0.48%   |
| 4.9.155 | 3         | 0.48%   |
| 4.10.0  | 3         | 0.48%   |
| 6.2.11  | 2         | 0.32%   |
| 6.1.11  | 2         | 0.32%   |
| 6.1.0   | 2         | 0.32%   |
| 6.0.9   | 2         | 0.32%   |
| 6.0.10  | 2         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 120       | 19.39%  |
| 5.15    | 64        | 10.34%  |
| 5.10    | 44        | 7.11%   |
| 4.15    | 36        | 5.82%   |
| 5.8     | 35        | 5.65%   |
| 5.19    | 34        | 5.49%   |
| 5.11    | 33        | 5.33%   |
| 5.3     | 27        | 4.36%   |
| 5.13    | 27        | 4.36%   |
| 6.0     | 19        | 3.07%   |
| 5.16    | 17        | 2.75%   |
| 4.18    | 17        | 2.75%   |
| 5.17    | 15        | 2.42%   |
| 5.0     | 15        | 2.42%   |
| 6.1     | 14        | 2.26%   |
| 6.2     | 13        | 2.1%    |
| 4.19    | 12        | 1.94%   |
| 4.9     | 11        | 1.78%   |
| 5.6     | 10        | 1.62%   |
| 5.18    | 10        | 1.62%   |
| 5.12    | 9         | 1.45%   |
| 5.7     | 7         | 1.13%   |
| 5.14    | 7         | 1.13%   |
| 5.9     | 5         | 0.81%   |
| 4.4     | 3         | 0.48%   |
| 4.10    | 3         | 0.48%   |
| 4.13    | 2         | 0.32%   |
| 4.12    | 2         | 0.32%   |
| 3.10    | 2         | 0.32%   |
| 6.3     | 1         | 0.16%   |
| 5.5     | 1         | 0.16%   |
| 5.2     | 1         | 0.16%   |
| 5       | 1         | 0.16%   |
| 4.14    | 1         | 0.16%   |
| 4.1     | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 531       | 96.02%  |
| i686    | 15        | 2.71%   |
| aarch64 | 7         | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 254       | 43.57%  |
| KDE5            | 94        | 16.12%  |
| Unknown         | 73        | 12.52%  |
| X-Cinnamon      | 41        | 7.03%   |
| XFCE            | 38        | 6.52%   |
| KDE             | 18        | 3.09%   |
| MATE            | 12        | 2.06%   |
| Pantheon        | 9         | 1.54%   |
| LXQt            | 9         | 1.54%   |
| Cinnamon        | 8         | 1.37%   |
| KDE4            | 6         | 1.03%   |
| Unity           | 5         | 0.86%   |
| i3              | 4         | 0.69%   |
| Budgie          | 4         | 0.69%   |
| GNOME Flashback | 3         | 0.51%   |
| GNOME Classic   | 2         | 0.34%   |
| LXDE            | 1         | 0.17%   |
| LeftWM          | 1         | 0.17%   |
| Enlightenment   | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 447       | 79.4%   |
| Wayland | 64        | 11.37%  |
| Unknown | 40        | 7.1%    |
| Tty     | 12        | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 301       | 52.53%  |
| SDDM    | 83        | 14.49%  |
| GDM     | 67        | 11.69%  |
| GDM3    | 50        | 8.73%   |
| LightDM | 43        | 7.5%    |
| TDM     | 19        | 3.32%   |
| KDM     | 6         | 1.05%   |
| LXDM    | 2         | 0.35%   |
| SLiM    | 1         | 0.17%   |
| MDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IE   | 270       | 47.12%  |
| en_GB   | 102       | 17.8%   |
| en_US   | 97        | 16.93%  |
| Unknown | 66        | 11.52%  |
| pl_PL   | 14        | 2.44%   |
| es_ES   | 3         | 0.52%   |
| C       | 3         | 0.52%   |
| en_IN   | 2         | 0.35%   |
| en_CA   | 2         | 0.35%   |
| bg_BG   | 2         | 0.35%   |
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
| de_DE   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 294       | 52.31%  |
| EFI  | 268       | 47.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 438       | 78.35%  |
| Btrfs               | 46        | 8.23%   |
| Overlay             | 37        | 6.62%   |
| Unknown             | 23        | 4.11%   |
| Xfs                 | 8         | 1.43%   |
| Zfs                 | 5         | 0.89%   |
| Fuse.fuse-overlayfs | 1         | 0.18%   |
| F2fs                | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 305       | 53.89%  |
| GPT     | 203       | 35.87%  |
| MBR     | 58        | 10.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 476       | 84.7%   |
| Yes       | 86        | 15.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 417       | 74.2%   |
| Yes       | 145       | 25.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Dell                                 | 119       | 21.6%   |
| Lenovo                               | 94        | 17.06%  |
| Hewlett-Packard                      | 66        | 11.98%  |
| ASUSTek Computer                     | 66        | 11.98%  |
| Gigabyte Technology                  | 28        | 5.08%   |
| Acer                                 | 22        | 3.99%   |
| MSI                                  | 20        | 3.63%   |
| Apple                                | 19        | 3.45%   |
| ASRock                               | 13        | 2.36%   |
| Toshiba                              | 12        | 2.18%   |
| Intel                                | 10        | 1.81%   |
| Samsung Electronics                  | 7         | 1.27%   |
| Medion                               | 5         | 0.91%   |
| Foxconn                              | 5         | 0.91%   |
| TUXEDO                               | 4         | 0.73%   |
| Timi                                 | 4         | 0.73%   |
| PC Specialist                        | 4         | 0.73%   |
| Valve                                | 3         | 0.54%   |
| Notebook                             | 3         | 0.54%   |
| Chuwi                                | 3         | 0.54%   |
| System76                             | 2         | 0.36%   |
| Shuttle                              | 2         | 0.36%   |
| Seco                                 | 2         | 0.36%   |
| Raspberry Pi Foundation              | 2         | 0.36%   |
| Packard Bell                         | 2         | 0.36%   |
| Nvidia                               | 2         | 0.36%   |
| HUAWEI                               | 2         | 0.36%   |
| Fujitsu Siemens                      | 2         | 0.36%   |
| Entroware                            | 2         | 0.36%   |
| eMachines                            | 2         | 0.36%   |
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

![Model](./images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Dell Latitude 7420                | 8         | 1.45%   |
| Dell OptiPlex 7010                | 7         | 1.27%   |
| ASUS All Series                   | 7         | 1.27%   |
| Lenovo Yoga 6 13ALC7 82UD         | 5         | 0.91%   |
| Gigabyte B450M DS3H               | 4         | 0.73%   |
| Valve Jupiter                     | 3         | 0.54%   |
| Lenovo V145-15AST 81MT            | 3         | 0.54%   |
| HP Compaq 8200 Elite SFF PC       | 3         | 0.54%   |
| Dell OptiPlex 790                 | 3         | 0.54%   |
| Dell OptiPlex 780                 | 3         | 0.54%   |
| Dell OptiPlex 7020                | 3         | 0.54%   |
| Dell Latitude E7240               | 3         | 0.54%   |
| Dell Inspiron 13-5378             | 3         | 0.54%   |
| ASUS ROG STRIX B450-F GAMING      | 3         | 0.54%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.36%   |
| Seco C40                          | 2         | 0.36%   |
| RPi Raspberry Pi                  | 2         | 0.36%   |
| Nvidia Tegra                      | 2         | 0.36%   |
| MSI MS-7B79                       | 2         | 0.36%   |
| Lenovo ThinkStation D20 415892G   | 2         | 0.36%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.36%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.36%   |
| HP Pavilion g6                    | 2         | 0.36%   |
| HP OMEN by Laptop 15-dc0xxx       | 2         | 0.36%   |
| HP Notebook                       | 2         | 0.36%   |
| HP EliteDesk 800 G1 SFF           | 2         | 0.36%   |
| Gigabyte X570 AORUS ULTRA         | 2         | 0.36%   |
| Gigabyte A320M-S2H                | 2         | 0.36%   |
| Foxconn Pro 3500 Series           | 2         | 0.36%   |
| Dell XPS 9320                     | 2         | 0.36%   |
| Dell XPS 13 9310                  | 2         | 0.36%   |
| Dell XPS 13 9300                  | 2         | 0.36%   |
| Dell XPS 13 7390                  | 2         | 0.36%   |
| Dell Precision 5550               | 2         | 0.36%   |
| Dell Latitude E6230               | 2         | 0.36%   |
| Dell Inspiron 7577                | 2         | 0.36%   |
| ASUS X501A1                       | 2         | 0.36%   |
| ASUS TUF Gaming X570-PLUS         | 2         | 0.36%   |
| ASUS P8P67 PRO                    | 2         | 0.36%   |
| ASUS M5A78L/USB3                  | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 41        | 7.44%   |
| Dell Latitude       | 39        | 7.08%   |
| Dell OptiPlex       | 24        | 4.36%   |
| Dell Inspiron       | 20        | 3.63%   |
| Acer Aspire         | 16        | 2.9%    |
| Lenovo IdeaPad      | 15        | 2.72%   |
| HP Pavilion         | 13        | 2.36%   |
| HP EliteBook        | 13        | 2.36%   |
| Dell XPS            | 13        | 2.36%   |
| Dell Precision      | 10        | 1.81%   |
| Toshiba Satellite   | 9         | 1.63%   |
| Lenovo Yoga         | 9         | 1.63%   |
| HP Compaq           | 8         | 1.45%   |
| Lenovo ThinkCentre  | 7         | 1.27%   |
| ASUS TUF            | 7         | 1.27%   |
| ASUS PRIME          | 7         | 1.27%   |
| ASUS All            | 7         | 1.27%   |
| ASUS ROG            | 6         | 1.09%   |
| HP EliteDesk        | 4         | 0.73%   |
| Gigabyte B450M      | 4         | 0.73%   |
| Dell Vostro         | 4         | 0.73%   |
| Valve Jupiter       | 3         | 0.54%   |
| Lenovo V145-15AST   | 3         | 0.54%   |
| Lenovo ThinkBook    | 3         | 0.54%   |
| HP ProBook          | 3         | 0.54%   |
| HP Presario         | 3         | 0.54%   |
| HP Laptop           | 3         | 0.54%   |
| Foxconn Pro         | 3         | 0.54%   |
| ASUS Zenbook        | 3         | 0.54%   |
| Apple MacBookPro5   | 3         | 0.54%   |
| TUXEDO Pulse        | 2         | 0.36%   |
| TUXEDO InfinityBook | 2         | 0.36%   |
| Toshiba TECRA       | 2         | 0.36%   |
| Seco C40            | 2         | 0.36%   |
| RPi Raspberry       | 2         | 0.36%   |
| Nvidia Tegra        | 2         | 0.36%   |
| MSI MS-7B79         | 2         | 0.36%   |
| Lenovo ThinkStation | 2         | 0.36%   |
| Intel DESKTOP       | 2         | 0.36%   |
| HP ProDesk          | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 55        | 9.98%   |
| 2020    | 53        | 9.62%   |
| 2018    | 50        | 9.07%   |
| 2013    | 48        | 8.71%   |
| 2012    | 42        | 7.62%   |
| 2017    | 40        | 7.26%   |
| 2011    | 40        | 7.26%   |
| 2021    | 31        | 5.63%   |
| 2010    | 28        | 5.08%   |
| 2015    | 26        | 4.72%   |
| 2008    | 26        | 4.72%   |
| 2022    | 23        | 4.17%   |
| 2016    | 22        | 3.99%   |
| 2014    | 20        | 3.63%   |
| 2009    | 19        | 3.45%   |
| 2007    | 10        | 1.81%   |
| 2006    | 7         | 1.27%   |
| Unknown | 6         | 1.09%   |
| 2005    | 3         | 0.54%   |
| 2023    | 1         | 0.18%   |
| 2003    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 326       | 59.17%  |
| Desktop        | 177       | 32.12%  |
| Convertible    | 14        | 2.54%   |
| Mini pc        | 12        | 2.18%   |
| All in one     | 11        | 2%      |
| System on chip | 6         | 1.09%   |
| Tablet         | 3         | 0.54%   |
| Phone          | 1         | 0.18%   |
| Server         | 1         | 0.18%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 503       | 90.63%  |
| Enabled  | 52        | 9.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 549       | 99.64%  |
| Yes  | 2         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 131       | 23.27%  |
| 16.01-24.0  | 119       | 21.14%  |
| 8.01-16.0   | 108       | 19.18%  |
| 3.01-4.0    | 94        | 16.7%   |
| 32.01-64.0  | 59        | 10.48%  |
| 1.01-2.0    | 19        | 3.37%   |
| 64.01-256.0 | 15        | 2.66%   |
| 24.01-32.0  | 8         | 1.42%   |
| 2.01-3.0    | 5         | 0.89%   |
| 0.51-1.0    | 4         | 0.71%   |
| 0.01-0.5    | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 205       | 33.23%  |
| 2.01-3.0   | 153       | 24.8%   |
| 4.01-8.0   | 95        | 15.4%   |
| 3.01-4.0   | 88        | 14.26%  |
| 0.51-1.0   | 42        | 6.81%   |
| 8.01-16.0  | 25        | 4.05%   |
| 0.01-0.5   | 5         | 0.81%   |
| 16.01-24.0 | 3         | 0.49%   |
| 32.01-64.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 349       | 59.97%  |
| 2      | 139       | 23.88%  |
| 3      | 41        | 7.04%   |
| 4      | 22        | 3.78%   |
| 5      | 12        | 2.06%   |
| 7      | 6         | 1.03%   |
| 6      | 4         | 0.69%   |
| 0      | 4         | 0.69%   |
| 10     | 2         | 0.34%   |
| 11     | 1         | 0.17%   |
| 9      | 1         | 0.17%   |
| 8      | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 349       | 62.43%  |
| Yes       | 210       | 37.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 86.31%  |
| No        | 76        | 13.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 467       | 83.69%  |
| No        | 91        | 16.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 65.78%  |
| No        | 192       | 34.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ireland | 551       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Dublin         | 321       | 55.34%  |
| Cork           | 35        | 6.03%   |
| Limerick       | 21        | 3.62%   |
| Galway         | 17        | 2.93%   |
| Naas           | 12        | 2.07%   |
| Portlaoise     | 7         | 1.21%   |
| Ennis          | 7         | 1.21%   |
| Gorey          | 6         | 1.03%   |
| Drogheda       | 6         | 1.03%   |
| Athlone        | 6         | 1.03%   |
| Sligo          | 5         | 0.86%   |
| Navan          | 5         | 0.86%   |
| Enniscorthy    | 5         | 0.86%   |
| Wexford        | 4         | 0.69%   |
| Tuam           | 4         | 0.69%   |
| Nenagh         | 4         | 0.69%   |
| Lucan          | 4         | 0.69%   |
| Kilkenny       | 4         | 0.69%   |
| Kenmare        | 4         | 0.69%   |
| Waterford      | 3         | 0.52%   |
| Loughrea       | 3         | 0.52%   |
| Dún Laoghaire | 3         | 0.52%   |
| Cobh           | 3         | 0.52%   |
| Cavan          | 3         | 0.52%   |
| Westport       | 2         | 0.34%   |
| Tullamore      | 2         | 0.34%   |
| Swords         | 2         | 0.34%   |
| Oranmore       | 2         | 0.34%   |
| Maynooth       | 2         | 0.34%   |
| Mallow         | 2         | 0.34%   |
| Letterkenny    | 2         | 0.34%   |
| Killorglin     | 2         | 0.34%   |
| Kildare        | 2         | 0.34%   |
| Edenderry      | 2         | 0.34%   |
| Dundalk        | 2         | 0.34%   |
| Donegal        | 2         | 0.34%   |
| Clonmel        | 2         | 0.34%   |
| Clonakilty     | 2         | 0.34%   |
| Clane          | 2         | 0.34%   |
| Carrigaline    | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 138       | 201    | 16.95%  |
| WDC                         | 133       | 231    | 16.34%  |
| Seagate                     | 99        | 165    | 12.16%  |
| Toshiba                     | 46        | 63     | 5.65%   |
| SanDisk                     | 45        | 61     | 5.53%   |
| Unknown                     | 43        | 55     | 5.28%   |
| Crucial                     | 41        | 52     | 5.04%   |
| Hitachi                     | 37        | 50     | 4.55%   |
| Kingston                    | 24        | 35     | 2.95%   |
| SK hynix                    | 17        | 18     | 2.09%   |
| Intel                       | 17        | 21     | 2.09%   |
| KIOXIA                      | 15        | 17     | 1.84%   |
| Micron Technology           | 14        | 15     | 1.72%   |
| HGST                        | 14        | 15     | 1.72%   |
| A-DATA Technology           | 10        | 15     | 1.23%   |
| Phison                      | 7         | 12     | 0.86%   |
| Fujitsu                     | 7         | 8      | 0.86%   |
| LITEON                      | 6         | 6      | 0.74%   |
| Apple                       | 6         | 7      | 0.74%   |
| Verbatim                    | 5         | 5      | 0.61%   |
| China                       | 5         | 9      | 0.61%   |
| Silicon Motion              | 4         | 9      | 0.49%   |
| PNY                         | 4         | 4      | 0.49%   |
| KingSpec                    | 4         | 4      | 0.49%   |
| OCZ                         | 3         | 3      | 0.37%   |
| Netac                       | 3         | 3      | 0.37%   |
| Micron/Crucial Technology   | 3         | 6      | 0.37%   |
| LITEONIT                    | 3         | 3      | 0.37%   |
| Kingston Technology Company | 3         | 3      | 0.37%   |
| KingDian                    | 3         | 13     | 0.37%   |
| ASMT                        | 3         | 5      | 0.37%   |
| Union Memory                | 2         | 2      | 0.25%   |
| Transcend                   | 2         | 2      | 0.25%   |
| Team                        | 2         | 2      | 0.25%   |
| QNAP                        | 2         | 12     | 0.25%   |
| Patriot                     | 2         | 2      | 0.25%   |
| Maxtor                      | 2         | 2      | 0.25%   |
| JMicron Technology          | 2         | 2      | 0.25%   |
| Integral                    | 2         | 2      | 0.25%   |
| FORESEE                     | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB       | 11        | 1.21%   |
| Crucial CT1000MX500SSD1 1TB            | 9         | 0.99%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 8         | 0.88%   |
| Unknown MMC Card  32GB                 | 7         | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB         | 7         | 0.77%   |
| Samsung SSD 860 EVO 500GB              | 7         | 0.77%   |
| Unknown MMC Card  64GB                 | 6         | 0.66%   |
| Toshiba MQ01ABD100 1TB                 | 6         | 0.66%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 6         | 0.66%   |
| Seagate ST8000DM004-2CX188 8TB         | 6         | 0.66%   |
| SanDisk NVMe SSD Drive 512GB           | 6         | 0.66%   |
| Samsung SSD 970 EVO Plus 500GB         | 6         | 0.66%   |
| Samsung SSD 850 EVO 250GB              | 6         | 0.66%   |
| Samsung SSD 840 EVO 250GB              | 6         | 0.66%   |
| Samsung NVMe SSD Drive 500GB           | 6         | 0.66%   |
| Samsung NVMe SSD Drive 256GB           | 6         | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB               | 5         | 0.55%   |
| WDC WD10EURX-83UY4Y0 1TB               | 5         | 0.55%   |
| Verbatim Vi550 S3 SSD 128GB            | 5         | 0.55%   |
| Seagate ST500DM002-1BD142 500GB        | 5         | 0.55%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.55%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.55%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 0.55%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 4         | 0.44%   |
| Seagate ST3500312CS 500GB              | 4         | 0.44%   |
| Seagate ST2000DL003-9VT166 2TB         | 4         | 0.44%   |
| Seagate Expansion Desk 8TB             | 4         | 0.44%   |
| Kingston SV300S37A120G 120GB SSD       | 4         | 0.44%   |
| Hitachi HTS723232A7A364 320GB          | 4         | 0.44%   |
| HGST HTS721010A9E630 1TB               | 4         | 0.44%   |
| HGST HTS545050A7E680 500GB             | 4         | 0.44%   |
| Crucial M4-CT128M4SSD2 128GB           | 4         | 0.44%   |
| Crucial CT500MX500SSD1 500GB           | 4         | 0.44%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 3         | 0.33%   |
| WDC WD3200AAJS-60Z0A0 320GB            | 3         | 0.33%   |
| WDC WD20EZRX-00D8PB0 2TB               | 3         | 0.33%   |
| WDC WD10EALX-009BA0 1TB                | 3         | 0.33%   |
| Unknown SD/MMC/MS PRO 249GB            | 3         | 0.33%   |
| Unknown MMC Card  7GB                  | 3         | 0.33%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 105       | 192    | 32.51%  |
| Seagate             | 97        | 162    | 30.03%  |
| Hitachi             | 37        | 50     | 11.46%  |
| Toshiba             | 32        | 44     | 9.91%   |
| HGST                | 14        | 15     | 4.33%   |
| Samsung Electronics | 11        | 14     | 3.41%   |
| Fujitsu             | 7         | 8      | 2.17%   |
| Apple               | 4         | 4      | 1.24%   |
| Unknown             | 3         | 3      | 0.93%   |
| QNAP                | 2         | 12     | 0.62%   |
| Maxtor              | 2         | 2      | 0.62%   |
| USB3.0              | 1         | 1      | 0.31%   |
| SABRENT             | 1         | 2      | 0.31%   |
| LaCie               | 1         | 1      | 0.31%   |
| KESU                | 1         | 1      | 0.31%   |
| JMicron Technology  | 1         | 1      | 0.31%   |
| Inateck             | 1         | 1      | 0.31%   |
| FNK TECH            | 1         | 1      | 0.31%   |
| ExcelStor           | 1         | 2      | 0.31%   |
| ASMT                | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 71        | 97     | 27.52%  |
| Crucial             | 38        | 49     | 14.73%  |
| SanDisk             | 26        | 30     | 10.08%  |
| Kingston            | 23        | 33     | 8.91%   |
| WDC                 | 12        | 18     | 4.65%   |
| A-DATA Technology   | 7         | 11     | 2.71%   |
| Intel               | 6         | 6      | 2.33%   |
| Verbatim            | 5         | 5      | 1.94%   |
| LITEON              | 5         | 5      | 1.94%   |
| China               | 5         | 9      | 1.94%   |
| PNY                 | 4         | 4      | 1.55%   |
| KingSpec            | 4         | 4      | 1.55%   |
| Toshiba             | 3         | 5      | 1.16%   |
| OCZ                 | 3         | 3      | 1.16%   |
| Netac               | 3         | 3      | 1.16%   |
| Micron Technology   | 3         | 3      | 1.16%   |
| LITEONIT            | 3         | 3      | 1.16%   |
| KingDian            | 3         | 13     | 1.16%   |
| Apple               | 3         | 3      | 1.16%   |
| Transcend           | 2         | 2      | 0.78%   |
| Team                | 2         | 2      | 0.78%   |
| SK hynix            | 2         | 2      | 0.78%   |
| Patriot             | 2         | 2      | 0.78%   |
| Integral            | 2         | 2      | 0.78%   |
| FORESEE             | 2         | 2      | 0.78%   |
| ASMT                | 2         | 4      | 0.78%   |
| Zheino              | 1         | 1      | 0.39%   |
| W800S               | 1         | 2      | 0.39%   |
| TCSUNBOW            | 1         | 1      | 0.39%   |
| StoreJet            | 1         | 2      | 0.39%   |
| Star                | 1         | 1      | 0.39%   |
| SPCC                | 1         | 1      | 0.39%   |
| Plextor             | 1         | 1      | 0.39%   |
| Palit               | 1         | 1      | 0.39%   |
| Hikvision           | 1         | 1      | 0.39%   |
| Hewlett-Packard     | 1         | 2      | 0.39%   |
| GOODRAM             | 1         | 1      | 0.39%   |
| faspeed             | 1         | 1      | 0.39%   |
| Emtec               | 1         | 2      | 0.39%   |
| DRVEO               | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 259       | 517    | 35.87%  |
| SSD     | 230       | 342    | 31.86%  |
| NVMe    | 182       | 259    | 25.21%  |
| MMC     | 40        | 55     | 5.54%   |
| Unknown | 11        | 11     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 403       | 831    | 61.53%  |
| NVMe | 182       | 259    | 27.79%  |
| MMC  | 40        | 55     | 6.11%   |
| SAS  | 30        | 39     | 4.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 299       | 484    | 56.74%  |
| 0.51-1.0   | 153       | 230    | 29.03%  |
| 1.01-2.0   | 36        | 63     | 6.83%   |
| 3.01-4.0   | 14        | 30     | 2.66%   |
| 4.01-10.0  | 14        | 36     | 2.66%   |
| 2.01-3.0   | 10        | 14     | 1.9%    |
| 10.01-20.0 | 1         | 2      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 145       | 24.79%  |
| 101-250        | 143       | 24.44%  |
| 501-1000       | 76        | 12.99%  |
| 51-100         | 50        | 8.55%   |
| 1-20           | 43        | 7.35%   |
| 1001-2000      | 40        | 6.84%   |
| More than 3000 | 32        | 5.47%   |
| 21-50          | 21        | 3.59%   |
| Unknown        | 21        | 3.59%   |
| 2001-3000      | 14        | 2.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 229       | 37.48%  |
| 21-50          | 90        | 14.73%  |
| 101-250        | 83        | 13.58%  |
| 51-100         | 77        | 12.6%   |
| 501-1000       | 39        | 6.38%   |
| 251-500        | 37        | 6.06%   |
| Unknown        | 21        | 3.44%   |
| More than 3000 | 15        | 2.45%   |
| 1001-2000      | 11        | 1.8%    |
| 2001-3000      | 9         | 1.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10EALX-009BA0 1TB                        | 3         | 8      | 4.84%   |
| Seagate ST2000DL003-9VT166 2TB                 | 3         | 5      | 4.84%   |
| WDC WD2500AAKX-753CA1 250GB                    | 2         | 4      | 3.23%   |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 3.23%   |
| WDC WD7500BPKX-00HPJT0 752GB                   | 1         | 1      | 1.61%   |
| WDC WD5000HHTZ-04N21V0 500GB                   | 1         | 2      | 1.61%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 1.61%   |
| WDC WD5000AAKX-001CA0 500GB                    | 1         | 2      | 1.61%   |
| WDC WD400JB-00FMA0 40GB                        | 1         | 2      | 1.61%   |
| WDC WD3200AVJS-63B6A0 320GB                    | 1         | 1      | 1.61%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 1.61%   |
| WDC WD2500BEKT-75A25T0 250GB                   | 1         | 1      | 1.61%   |
| WDC WD2500AAKX-603CA0 250GB                    | 1         | 1      | 1.61%   |
| WDC WD20EZRZ-00Z5HB0 2TB                       | 1         | 2      | 1.61%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.61%   |
| WDC WD1001FALS-00E8B0 1TB                      | 1         | 2      | 1.61%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 1.61%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.61%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 1.61%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 1.61%   |
| Toshiba DT01ACA050 500GB                       | 1         | 3      | 1.61%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 1.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 1         | 1      | 1.61%   |
| Seagate ST4000DX001-1CE168 4TB                 | 1         | 1      | 1.61%   |
| Seagate ST3500418AS 500GB                      | 1         | 2      | 1.61%   |
| Seagate ST31500541AS 1TB                       | 1         | 1      | 1.61%   |
| Seagate ST3120026A 120GB                       | 1         | 1      | 1.61%   |
| Seagate ST31000333AS 1TB                       | 1         | 2      | 1.61%   |
| Seagate ST3000DM001-1ER166 3TB                 | 1         | 1      | 1.61%   |
| SanDisk SSD PLUS 480GB                         | 1         | 1      | 1.61%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 970 EVO Plus 2TB       | 1         | 1      | 1.61%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 1.61%   |
| Samsung Electronics HD103SI 1TB                | 1         | 1      | 1.61%   |
| Netac SSD 128GB                                | 1         | 1      | 1.61%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.61%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.61%   |
| Maxtor STM3250310AS 250GB                      | 1         | 1      | 1.61%   |
| JMicron Technology Generic 1TB                 | 1         | 1      | 1.61%   |
| Intel SSDSA2M080G2GC 80GB                      | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 29     | 23.73%  |
| Seagate             | 11        | 15     | 18.64%  |
| Hitachi             | 10        | 13     | 16.95%  |
| Toshiba             | 5         | 7      | 8.47%   |
| Samsung Electronics | 3         | 3      | 5.08%   |
| SanDisk             | 2         | 2      | 3.39%   |
| Micron Technology   | 2         | 2      | 3.39%   |
| HGST                | 2         | 2      | 3.39%   |
| Netac               | 1         | 1      | 1.69%   |
| Maxtor              | 1         | 1      | 1.69%   |
| JMicron Technology  | 1         | 1      | 1.69%   |
| Intel               | 1         | 1      | 1.69%   |
| Inateck             | 1         | 1      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |
| DRVEO               | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 1      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 29     | 28.57%  |
| Seagate             | 11        | 15     | 22.45%  |
| Hitachi             | 10        | 13     | 20.41%  |
| Toshiba             | 5         | 7      | 10.2%   |
| Samsung Electronics | 2         | 2      | 4.08%   |
| HGST                | 2         | 2      | 4.08%   |
| Maxtor              | 1         | 1      | 2.04%   |
| JMicron Technology  | 1         | 1      | 2.04%   |
| Inateck             | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 73     | 79.17%  |
| SSD  | 8         | 8      | 16.67%  |
| NVMe | 2         | 2      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 50%     |
| KingDian S400 120GB SSD     | 1         | 4      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 50%     |
| KingDian | 1         | 4      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 344       | 672    | 56.67%  |
| Works    | 214       | 424    | 35.26%  |
| Malfunc  | 47        | 83     | 7.74%   |
| Failed   | 2         | 5      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 350       | 51.4%   |
| AMD                          | 102       | 14.98%  |
| Samsung Electronics          | 65        | 9.54%   |
| SanDisk                      | 35        | 5.14%   |
| SK hynix                     | 15        | 2.2%    |
| Nvidia                       | 14        | 2.06%   |
| KIOXIA                       | 14        | 2.06%   |
| Toshiba America Info Systems | 13        | 1.91%   |
| Micron Technology            | 11        | 1.62%   |
| Marvell Technology Group     | 9         | 1.32%   |
| ASMedia Technology           | 9         | 1.32%   |
| Phison Electronics           | 8         | 1.17%   |
| Micron/Crucial Technology    | 6         | 0.88%   |
| JMicron Technology           | 5         | 0.73%   |
| Union Memory (Shenzhen)      | 4         | 0.59%   |
| Silicon Motion               | 4         | 0.59%   |
| Kingston Technology Company  | 4         | 0.59%   |
| LSI Logic / Symbios Logic    | 3         | 0.44%   |
| Realtek Semiconductor        | 2         | 0.29%   |
| ULi Electronics              | 1         | 0.15%   |
| Silicon Image                | 1         | 0.15%   |
| Seagate Technology           | 1         | 0.15%   |
| O2 Micro                     | 1         | 0.15%   |
| Lite-On Technology           | 1         | 0.15%   |
| Broadcom / LSI               | 1         | 0.15%   |
| ADATA Technology             | 1         | 0.15%   |
| Adaptec                      | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 80        | 10.15%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 41        | 5.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 34        | 4.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 22        | 2.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 21        | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20        | 2.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 17        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16        | 2.03%   |
| Samsung NVMe SSD Controller 980                                                         | 15        | 1.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15        | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 1.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 14        | 1.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 12        | 1.52%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 12        | 1.52%   |
| Micron NVMe Storage Controller                                                          | 11        | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 11        | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 11        | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 11        | 1.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 10        | 1.27%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 9         | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 9         | 1.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 9         | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.02%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 7         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 0.89%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 7         | 0.89%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 0.89%   |
| SanDisk Non-Volatile memory controller                                                  | 6         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                            | 6         | 0.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 0.76%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 6         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 0.76%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 390       | 56.44%  |
| NVMe | 183       | 26.48%  |
| IDE  | 73        | 10.56%  |
| RAID | 42        | 6.08%   |
| SCSI | 3         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 411       | 74.46%  |
| AMD    | 134       | 24.28%  |
| ARM    | 7         | 1.27%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 13        | 2.34%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.26%   |
| ARM Processor                                 | 7         | 1.26%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7         | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 6         | 1.08%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 6         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 0.9%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.72%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 0.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 4         | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.72%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 4         | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.54%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 0.54%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.54%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 3         | 0.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.54%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 3         | 0.54%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 3         | 0.54%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.54%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 0.54%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 0.54%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 114       | 20.54%  |
| Intel Core i7           | 106       | 19.1%   |
| Other                   | 53        | 9.55%   |
| Intel Core i3           | 42        | 7.57%   |
| AMD Ryzen 5             | 31        | 5.59%   |
| Intel Celeron           | 26        | 4.68%   |
| Intel Core 2 Duo        | 25        | 4.5%    |
| AMD Ryzen 7             | 22        | 3.96%   |
| AMD Ryzen 9             | 11        | 1.98%   |
| Intel Atom              | 10        | 1.8%    |
| Intel Xeon              | 8         | 1.44%   |
| Intel Pentium           | 8         | 1.44%   |
| Intel Core 2 Quad       | 8         | 1.44%   |
| AMD FX                  | 6         | 1.08%   |
| AMD Athlon 64 X2        | 6         | 1.08%   |
| AMD Ryzen 3             | 5         | 0.9%    |
| Intel Pentium Dual-Core | 4         | 0.72%   |
| AMD A8                  | 4         | 0.72%   |
| AMD A6                  | 4         | 0.72%   |
| Intel Pentium 4         | 3         | 0.54%   |
| Intel Core 2            | 3         | 0.54%   |
| AMD Ryzen 7 PRO         | 3         | 0.54%   |
| AMD Ryzen 5 PRO         | 3         | 0.54%   |
| AMD E1                  | 3         | 0.54%   |
| AMD Athlon II X4        | 3         | 0.54%   |
| Intel Pentium Silver    | 2         | 0.36%   |
| Intel Core m3           | 2         | 0.36%   |
| Intel Core i9           | 2         | 0.36%   |
| Intel Celeron Dual-Core | 2         | 0.36%   |
| AMD Ryzen Threadripper  | 2         | 0.36%   |
| AMD Ryzen Embedded      | 2         | 0.36%   |
| AMD PRO A10             | 2         | 0.36%   |
| AMD Phenom II X6        | 2         | 0.36%   |
| AMD Phenom II X4        | 2         | 0.36%   |
| AMD E2                  | 2         | 0.36%   |
| AMD A4                  | 2         | 0.36%   |
| AMD A10                 | 2         | 0.36%   |
| Intel Xeon Platinum     | 1         | 0.18%   |
| Intel Pentium M         | 1         | 0.18%   |
| Intel Pentium III       | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 227       | 41.05%  |
| 2       | 205       | 37.07%  |
| 6       | 44        | 7.96%   |
| 8       | 34        | 6.15%   |
| 1       | 17        | 3.07%   |
| 12      | 12        | 2.17%   |
| 14      | 5         | 0.9%    |
| 3       | 3         | 0.54%   |
| 10      | 2         | 0.36%   |
| 96      | 1         | 0.18%   |
| 32      | 1         | 0.18%   |
| 16      | 1         | 0.18%   |
| Unknown | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 546       | 99.09%  |
| 2      | 5         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 366       | 66.06%  |
| 1       | 187       | 33.75%  |
| Unknown | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 533       | 96.38%  |
| Unknown        | 17        | 3.07%   |
| 32-bit         | 3         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 157       | 27.45%  |
| 0x306a9    | 37        | 6.47%   |
| 0x206a7    | 27        | 4.72%   |
| 0x306c3    | 22        | 3.85%   |
| 0x1067a    | 22        | 3.85%   |
| 0x806e9    | 18        | 3.15%   |
| 0x806ec    | 17        | 2.97%   |
| 0x806c1    | 16        | 2.8%    |
| 0x806ea    | 13        | 2.27%   |
| 0x906ea    | 10        | 1.75%   |
| 0x906e9    | 10        | 1.75%   |
| 0x406e3    | 10        | 1.75%   |
| 0x40651    | 10        | 1.75%   |
| 0x10676    | 8         | 1.4%    |
| 0xa0652    | 7         | 1.22%   |
| 0x406c4    | 7         | 1.22%   |
| 0x30678    | 7         | 1.22%   |
| 0x08701021 | 7         | 1.22%   |
| 0x08108109 | 7         | 1.22%   |
| 0x506e3    | 6         | 1.05%   |
| 0x306d4    | 6         | 1.05%   |
| 0x0a50000c | 6         | 1.05%   |
| 0x20655    | 5         | 0.87%   |
| 0x08108102 | 5         | 0.87%   |
| 0x0810100b | 5         | 0.87%   |
| 0x0800820d | 5         | 0.87%   |
| 0x06006705 | 5         | 0.87%   |
| 0xa0653    | 4         | 0.7%    |
| 0x6fd      | 4         | 0.7%    |
| 0x6fb      | 4         | 0.7%    |
| 0x206c2    | 4         | 0.7%    |
| 0x0600611a | 4         | 0.7%    |
| 0x906a3    | 3         | 0.52%   |
| 0x806d1    | 3         | 0.52%   |
| 0x706e5    | 3         | 0.52%   |
| 0x706a8    | 3         | 0.52%   |
| 0x106ca    | 3         | 0.52%   |
| 0x08701013 | 3         | 0.52%   |
| 0x08608103 | 3         | 0.52%   |
| 0x08600106 | 3         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 84        | 15.22%  |
| IvyBridge        | 49        | 8.88%   |
| Haswell          | 40        | 7.25%   |
| SandyBridge      | 39        | 7.07%   |
| Penryn           | 31        | 5.62%   |
| Unknown          | 28        | 5.07%   |
| TigerLake        | 27        | 4.89%   |
| Zen 2            | 24        | 4.35%   |
| Skylake          | 24        | 4.35%   |
| Zen+             | 22        | 3.99%   |
| Silvermont       | 19        | 3.44%   |
| Westmere         | 16        | 2.9%    |
| Core             | 15        | 2.72%   |
| CometLake        | 13        | 2.36%   |
| Zen              | 12        | 2.17%   |
| Excavator        | 11        | 1.99%   |
| Zen 3            | 10        | 1.81%   |
| K10              | 10        | 1.81%   |
| K8 Hammer        | 9         | 1.63%   |
| Piledriver       | 8         | 1.45%   |
| IceLake          | 8         | 1.45%   |
| Goldmont plus    | 8         | 1.45%   |
| Broadwell        | 8         | 1.45%   |
| Nehalem          | 6         | 1.09%   |
| Bonnell          | 5         | 0.91%   |
| Puma             | 4         | 0.72%   |
| P6               | 4         | 0.72%   |
| NetBurst         | 4         | 0.72%   |
| Bobcat           | 4         | 0.72%   |
| Jaguar           | 3         | 0.54%   |
| Alderlake Hybrid | 3         | 0.54%   |
| Goldmont         | 2         | 0.36%   |
| Steamroller      | 1         | 0.18%   |
| Bulldozer        | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 314       | 49.22%  |
| Nvidia            | 167       | 26.18%  |
| AMD               | 156       | 24.45%  |
| ASPEED Technology | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 3.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 3.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 3.48%   |
| Intel HD Graphics 620                                                                    | 18        | 2.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 15        | 2.27%   |
| Intel UHD Graphics 620                                                                   | 14        | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 1.82%   |
| Intel HD Graphics 630                                                                    | 11        | 1.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.36%   |
| AMD Renoir                                                                               | 9         | 1.36%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 9         | 1.36%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 8         | 1.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 1.06%   |
| AMD Lucienne                                                                             | 7         | 1.06%   |
| Intel HD Graphics 5500                                                                   | 6         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.91%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6         | 0.91%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 5         | 0.76%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 0.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 0.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 237       | 42.4%   |
| 1 x AMD        | 128       | 22.9%   |
| 1 x Nvidia     | 93        | 16.64%  |
| Intel + Nvidia | 63        | 11.27%  |
| 2 x AMD        | 13        | 2.33%   |
| AMD + Nvidia   | 10        | 1.79%   |
| Other          | 7         | 1.25%   |
| Intel + AMD    | 5         | 0.89%   |
| 2 x Nvidia     | 1         | 0.18%   |
| 2 x Intel      | 1         | 0.18%   |
| 1 x ASPEED     | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 448       | 80%     |
| Proprietary | 84        | 15%     |
| Unknown     | 28        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 319       | 55.67%  |
| 0.01-0.5   | 66        | 11.52%  |
| 1.01-2.0   | 53        | 9.25%   |
| 3.01-4.0   | 46        | 8.03%   |
| 0.51-1.0   | 43        | 7.5%    |
| 7.01-8.0   | 22        | 3.84%   |
| 5.01-6.0   | 15        | 2.62%   |
| 2.01-3.0   | 4         | 0.7%    |
| 8.01-16.0  | 4         | 0.7%    |
| 16.01-24.0 | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 11.27%  |
| Dell                    | 67        | 10.95%  |
| BOE                     | 65        | 10.62%  |
| LG Display              | 58        | 9.48%   |
| Samsung Electronics     | 52        | 8.5%    |
| Chimei Innolux          | 36        | 5.88%   |
| Hewlett-Packard         | 21        | 3.43%   |
| Sharp                   | 20        | 3.27%   |
| Acer                    | 20        | 3.27%   |
| Apple                   | 17        | 2.78%   |
| Philips                 | 16        | 2.61%   |
| Goldstar                | 16        | 2.61%   |
| BenQ                    | 16        | 2.61%   |
| ViewSonic               | 13        | 2.12%   |
| Lenovo                  | 12        | 1.96%   |
| AOC                     | 12        | 1.96%   |
| Iiyama                  | 11        | 1.8%    |
| Chi Mei Optoelectronics | 8         | 1.31%   |
| PANDA                   | 7         | 1.14%   |
| Sony                    | 5         | 0.82%   |
| LG Philips              | 4         | 0.65%   |
| InfoVision              | 4         | 0.65%   |
| Ancor Communications    | 4         | 0.65%   |
| ___                     | 3         | 0.49%   |
| Vestel Elektronik       | 3         | 0.49%   |
| Unknown                 | 3         | 0.49%   |
| Toshiba                 | 3         | 0.49%   |
| MSI                     | 3         | 0.49%   |
| HannStar                | 3         | 0.49%   |
| CSO                     | 3         | 0.49%   |
| Valve                   | 2         | 0.33%   |
| OEM                     | 2         | 0.33%   |
| MiTAC                   | 2         | 0.33%   |
| HKC                     | 2         | 0.33%   |
| CPT                     | 2         | 0.33%   |
| BOE Technology Group    | 2         | 0.33%   |
| ASUSTek Computer        | 2         | 0.33%   |
| Unknown                 | 2         | 0.33%   |
| WIT                     | 1         | 0.16%   |
| Targa Visionary         | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                  | 9         | 1.4%    |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch              | 8         | 1.25%   |
| Dell P2217H DELA0D8 1920x1080 476x267mm 21.5-inch                      | 8         | 1.25%   |
| Iiyama PLT2336 IVM5628 1920x1080 509x286mm 23.0-inch                   | 5         | 0.78%   |
| BOE LCD Monitor BOE0964 1920x1200 286x179mm 13.3-inch                  | 5         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 4         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch   | 4         | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 4         | 0.62%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 4         | 0.62%   |
| ___ LCD TV ___9000 1360x768                                            | 3         | 0.47%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 3         | 0.47%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                     | 3         | 0.47%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 3         | 0.47%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3         | 0.47%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 3         | 0.47%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch            | 3         | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 3         | 0.47%   |
| Dell P2014H DEL4097 1600x900 434x236mm 19.4-inch                       | 3         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch       | 3         | 0.47%   |
| BenQ G2222HDL BNQ7859 1920x1080 477x268mm 21.5-inch                    | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 3         | 0.47%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch         | 3         | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 2         | 0.31%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch                | 2         | 0.31%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 2         | 0.31%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 2         | 0.31%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                | 2         | 0.31%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 2         | 0.31%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2         | 0.31%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch      | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch   | 2         | 0.31%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch      | 2         | 0.31%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 2         | 0.31%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 2         | 0.31%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 2         | 0.31%   |
| LG Philips LCD Monitor LPLA104 1440x900 367x230mm 17.1-inch            | 2         | 0.31%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch          | 2         | 0.31%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch           | 2         | 0.31%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 2         | 0.31%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 2         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 264       | 45.28%  |
| 1366x768 (WXGA)    | 97        | 16.64%  |
| 3840x2160 (4K)     | 34        | 5.83%   |
| 2560x1440 (QHD)    | 33        | 5.66%   |
| 1920x1200 (WUXGA)  | 21        | 3.6%    |
| 1600x900 (HD+)     | 20        | 3.43%   |
| 1440x900 (WXGA+)   | 17        | 2.92%   |
| 1280x1024 (SXGA)   | 14        | 2.4%    |
| 1280x800 (WXGA)    | 13        | 2.23%   |
| 3440x1440          | 10        | 1.72%   |
| 1360x768           | 8         | 1.37%   |
| Unknown            | 8         | 1.37%   |
| 1680x1050 (WSXGA+) | 6         | 1.03%   |
| 3840x1080          | 4         | 0.69%   |
| 2560x1600          | 4         | 0.69%   |
| 800x1280           | 3         | 0.51%   |
| 3840x2400          | 3         | 0.51%   |
| 1600x1200          | 3         | 0.51%   |
| 1024x600           | 3         | 0.51%   |
| 3456x2160          | 2         | 0.34%   |
| 3200x1800 (QHD+)   | 2         | 0.34%   |
| 2560x1080          | 2         | 0.34%   |
| 1920x540           | 2         | 0.34%   |
| 1024x768 (XGA)     | 2         | 0.34%   |
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

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 158       | 25.77%  |
| 14      | 62        | 10.11%  |
| 27      | 59        | 9.62%   |
| 13      | 51        | 8.32%   |
| 24      | 44        | 7.18%   |
| 21      | 38        | 6.2%    |
| 23      | 36        | 5.87%   |
| Unknown | 29        | 4.73%   |
| 17      | 27        | 4.4%    |
| 12      | 16        | 2.61%   |
| 19      | 14        | 2.28%   |
| 34      | 12        | 1.96%   |
| 31      | 11        | 1.79%   |
| 18      | 7         | 1.14%   |
| 84      | 6         | 0.98%   |
| 11      | 6         | 0.98%   |
| 72      | 5         | 0.82%   |
| 20      | 5         | 0.82%   |
| 32      | 4         | 0.65%   |
| 25      | 3         | 0.49%   |
| 22      | 3         | 0.49%   |
| 10      | 3         | 0.49%   |
| 49      | 2         | 0.33%   |
| 40      | 2         | 0.33%   |
| 29      | 2         | 0.33%   |
| 7       | 2         | 0.33%   |
| 65      | 1         | 0.16%   |
| 46      | 1         | 0.16%   |
| 35      | 1         | 0.16%   |
| 33      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 16      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 236       | 39.07%  |
| 501-600     | 127       | 21.03%  |
| 401-500     | 62        | 10.26%  |
| 201-300     | 61        | 10.1%   |
| 351-400     | 31        | 5.13%   |
| Unknown     | 29        | 4.8%    |
| 601-700     | 21        | 3.48%   |
| 701-800     | 17        | 2.81%   |
| 1501-2000   | 11        | 1.82%   |
| 1001-1500   | 4         | 0.66%   |
| 801-900     | 3         | 0.5%    |
| 1-100       | 2         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 404       | 76.08%  |
| 16/10   | 64        | 12.05%  |
| Unknown | 22        | 4.14%   |
| 5/4     | 14        | 2.64%   |
| 21/9    | 13        | 2.45%   |
| 4/3     | 6         | 1.13%   |
| 3/2     | 4         | 0.75%   |
| 0.67    | 2         | 0.38%   |
| 32/9    | 1         | 0.19%   |
| 0.62    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 156       | 25.45%  |
| 201-250        | 96        | 15.66%  |
| 81-90          | 81        | 13.21%  |
| 301-350        | 61        | 9.95%   |
| 71-80          | 33        | 5.38%   |
| 151-200        | 30        | 4.89%   |
| 351-500        | 29        | 4.73%   |
| Unknown        | 29        | 4.73%   |
| 251-300        | 19        | 3.1%    |
| 61-70          | 15        | 2.45%   |
| 121-130        | 15        | 2.45%   |
| 141-150        | 14        | 2.28%   |
| More than 1000 | 12        | 1.96%   |
| 51-60          | 6         | 0.98%   |
| 501-1000       | 5         | 0.82%   |
| 131-140        | 4         | 0.65%   |
| 41-50          | 3         | 0.49%   |
| 1-40           | 2         | 0.33%   |
| 111-120        | 2         | 0.33%   |
| 91-100         | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 175       | 29.76%  |
| 51-100        | 173       | 29.42%  |
| 101-120       | 141       | 23.98%  |
| 161-240       | 42        | 7.14%   |
| Unknown       | 29        | 4.93%   |
| More than 240 | 14        | 2.38%   |
| 1-50          | 14        | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 431       | 75.61%  |
| 2     | 95        | 16.67%  |
| 0     | 25        | 4.39%   |
| 3     | 18        | 3.16%   |
| 4     | 1         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 303       | 34.55%  |
| Realtek Semiconductor             | 276       | 31.47%  |
| Qualcomm Atheros                  | 81        | 9.24%   |
| Broadcom                          | 58        | 6.61%   |
| Ralink Technology                 | 16        | 1.82%   |
| Nvidia                            | 13        | 1.48%   |
| TP-Link                           | 12        | 1.37%   |
| MediaTek                          | 12        | 1.37%   |
| Broadcom Limited                  | 12        | 1.37%   |
| Ralink                            | 11        | 1.25%   |
| Marvell Technology Group          | 10        | 1.14%   |
| Microsoft                         | 7         | 0.8%    |
| Samsung Electronics               | 5         | 0.57%   |
| OPPO Electronics                  | 5         | 0.57%   |
| Lenovo                            | 5         | 0.57%   |
| Ericsson Business Mobile Networks | 5         | 0.57%   |
| ASIX Electronics                  | 5         | 0.57%   |
| NetGear                           | 3         | 0.34%   |
| DisplayLink                       | 3         | 0.34%   |
| Xiaomi                            | 2         | 0.23%   |
| Qualcomm Atheros Communications   | 2         | 0.23%   |
| Qualcomm                          | 2         | 0.23%   |
| Microchip Technology              | 2         | 0.23%   |
| ICS Advent                        | 2         | 0.23%   |
| Huawei Technologies               | 2         | 0.23%   |
| Dell                              | 2         | 0.23%   |
| Belkin Components                 | 2         | 0.23%   |
| Xilinx                            | 1         | 0.11%   |
| Van Ooijen Technische Informatica | 1         | 0.11%   |
| ULi Electronics                   | 1         | 0.11%   |
| Toshiba                           | 1         | 0.11%   |
| T & A Mobile Phones               | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.11%   |
| NetXen Incorporated               | 1         | 0.11%   |
| LSI                               | 1         | 0.11%   |
| LG Electronics                    | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| IMC Networks                      | 1         | 0.11%   |
| HMD Global                        | 1         | 0.11%   |
| Hewlett-Packard                   | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 171       | 16.54%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 3.87%   |
| Intel Wi-Fi 6 AX200                                               | 36        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 3.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 2.61%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 1.74%   |
| Intel Wireless 8265 / 8275                                        | 18        | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 17        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14        | 1.35%   |
| Intel Wireless 7260                                               | 13        | 1.26%   |
| Realtek 802.11ac NIC                                              | 11        | 1.06%   |
| Intel Wireless 7265                                               | 11        | 1.06%   |
| Intel Wireless 8260                                               | 10        | 0.97%   |
| Intel I211 Gigabit Network Connection                             | 10        | 0.97%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.87%   |
| Intel Wireless-AC 9260                                            | 9         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 9         | 0.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.77%   |
| Intel Wireless 3165                                               | 8         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 6         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                    | 6         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 6         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 234       | 46.99%  |
| Realtek Semiconductor           | 76        | 15.26%  |
| Qualcomm Atheros                | 72        | 14.46%  |
| Broadcom                        | 41        | 8.23%   |
| Ralink Technology               | 16        | 3.21%   |
| TP-Link                         | 12        | 2.41%   |
| Ralink                          | 11        | 2.21%   |
| MediaTek                        | 11        | 2.21%   |
| Microsoft                       | 6         | 1.2%    |
| Broadcom Limited                | 4         | 0.8%    |
| NetGear                         | 3         | 0.6%    |
| Qualcomm Atheros Communications | 2         | 0.4%    |
| Qualcomm                        | 2         | 0.4%    |
| Dell                            | 2         | 0.4%    |
| Belkin Components               | 2         | 0.4%    |
| LG Electronics                  | 1         | 0.2%    |
| IMC Networks                    | 1         | 0.2%    |
| ASUSTek Computer                | 1         | 0.2%    |
| Apple                           | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 36        | 7.16%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 3.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 3.58%   |
| Intel Wireless 8265 / 8275                                              | 18        | 3.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 3.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 2.78%   |
| Intel Wireless 7260                                                     | 13        | 2.58%   |
| Realtek 802.11ac NIC                                                    | 11        | 2.19%   |
| Intel Wireless 7265                                                     | 11        | 2.19%   |
| Intel Wireless 8260                                                     | 10        | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.79%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.79%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.59%   |
| Intel Wireless 3165                                                     | 8         | 1.59%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.39%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 6         | 1.19%   |
| Ralink RT5370 Wireless Adapter                                          | 6         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.19%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.99%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 5         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.99%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 5         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.8%    |
| Ralink RT2561/RT61 802.11g PCI                                          | 4         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 240       | 47.62%  |
| Intel                         | 153       | 30.36%  |
| Broadcom                      | 25        | 4.96%   |
| Qualcomm Atheros              | 17        | 3.37%   |
| Nvidia                        | 13        | 2.58%   |
| Marvell Technology Group      | 10        | 1.98%   |
| Broadcom Limited              | 9         | 1.79%   |
| OPPO Electronics              | 5         | 0.99%   |
| Lenovo                        | 5         | 0.99%   |
| ASIX Electronics              | 5         | 0.99%   |
| Samsung Electronics           | 3         | 0.6%    |
| DisplayLink                   | 3         | 0.6%    |
| Xiaomi                        | 2         | 0.4%    |
| ICS Advent                    | 2         | 0.4%    |
| Xilinx                        | 1         | 0.2%    |
| ULi Electronics               | 1         | 0.2%    |
| T & A Mobile Phones           | 1         | 0.2%    |
| OnePlus Technology (Shenzhen) | 1         | 0.2%    |
| NetXen Incorporated           | 1         | 0.2%    |
| Microsoft                     | 1         | 0.2%    |
| Microchip Technology          | 1         | 0.2%    |
| JMicron Technology            | 1         | 0.2%    |
| Huawei Technologies           | 1         | 0.2%    |
| HMD Global                    | 1         | 0.2%    |
| ADMtek                        | 1         | 0.2%    |
| 3Com                          | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 171       | 33.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 40        | 7.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 6.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 10        | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.95%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 1.36%   |
| Nvidia MCP79 Ethernet                                             | 7         | 1.36%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 1.17%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 5         | 0.97%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.78%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 3         | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.58%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.58%   |
| Intel Ethernet Controller I225-LM                                 | 3         | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.58%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.58%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.58%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.58%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 3         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.58%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 479       | 49.79%  |
| WiFi     | 465       | 48.34%  |
| Modem    | 18        | 1.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 343       | 58.93%  |
| Ethernet | 239       | 41.07%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 316       | 56.94%  |
| 1     | 217       | 39.1%   |
| 3     | 11        | 1.98%   |
| 0     | 9         | 1.62%   |
| 6     | 1         | 0.18%   |
| 4     | 1         | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 488       | 86.99%  |
| Yes  | 73        | 13.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 188       | 50.27%  |
| Realtek Semiconductor           | 32        | 8.56%   |
| Cambridge Silicon Radio         | 23        | 6.15%   |
| Broadcom                        | 23        | 6.15%   |
| Qualcomm Atheros Communications | 19        | 5.08%   |
| IMC Networks                    | 19        | 5.08%   |
| Apple                           | 17        | 4.55%   |
| Lite-On Technology              | 13        | 3.48%   |
| Dell                            | 8         | 2.14%   |
| ASUSTek Computer                | 7         | 1.87%   |
| Hewlett-Packard                 | 5         | 1.34%   |
| Foxconn / Hon Hai               | 5         | 1.34%   |
| Toshiba                         | 4         | 1.07%   |
| Realtek                         | 2         | 0.53%   |
| Foxconn International           | 2         | 0.53%   |
| Belkin Components               | 2         | 0.53%   |
| TP-Link                         | 1         | 0.27%   |
| Ralink                          | 1         | 0.27%   |
| MediaTek                        | 1         | 0.27%   |
| Edimax Technology               | 1         | 0.27%   |
| Conwise Technology              | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 69        | 18.4%   |
| Intel AX201 Bluetooth                               | 39        | 10.4%   |
| Intel AX200 Bluetooth                               | 33        | 8.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 6.13%   |
| Realtek Bluetooth Radio                             | 21        | 5.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 5.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 3.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 2.13%   |
| IMC Networks Bluetooth Radio                        | 8         | 2.13%   |
| Apple Bluetooth Host Controller                     | 8         | 2.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.6%    |
| Intel AX210 Bluetooth                               | 6         | 1.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.33%   |
| IMC Networks Bluetooth Device                       | 5         | 1.33%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.07%   |
| Intel Bluetooth Device                              | 4         | 1.07%   |
| IMC Networks Wireless_Device                        | 4         | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 1.07%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 1.07%   |
| Apple Bluetooth HCI                                 | 4         | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.8%    |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 0.8%    |
| Dell DW375 Bluetooth Module                         | 3         | 0.8%    |
| Apple Bluetooth USB Host Controller                 | 3         | 0.8%    |
| Toshiba Bluetooth Device                            | 2         | 0.53%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.53%   |
| Lite-On Wireless_Device                             | 2         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.53%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 393       | 50.26%  |
| AMD                                             | 169       | 21.61%  |
| Nvidia                                          | 127       | 16.24%  |
| Plantronics                                     | 11        | 1.41%   |
| Realtek Semiconductor                           | 10        | 1.28%   |
| Logitech                                        | 6         | 0.77%   |
| GN Netcom                                       | 6         | 0.77%   |
| Creative Labs                                   | 6         | 0.77%   |
| C-Media Electronics                             | 6         | 0.77%   |
| Creative Technology                             | 5         | 0.64%   |
| RODE Microphones                                | 3         | 0.38%   |
| Lenovo                                          | 3         | 0.38%   |
| Kingston Technology                             | 3         | 0.38%   |
| Texas Instruments                               | 2         | 0.26%   |
| Sony                                            | 2         | 0.26%   |
| JMTek                                           | 2         | 0.26%   |
| Ensoniq                                         | 2         | 0.26%   |
| Blue Microphones                                | 2         | 0.26%   |
| VIA Technologies                                | 1         | 0.13%   |
| ULi Electronics                                 | 1         | 0.13%   |
| Turtle Beach                                    | 1         | 0.13%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.13%   |
| SAVITECH                                        | 1         | 0.13%   |
| Razer USA                                       | 1         | 0.13%   |
| No brand                                        | 1         | 0.13%   |
| Native Instruments                              | 1         | 0.13%   |
| Micronas                                        | 1         | 0.13%   |
| M-Audio                                         | 1         | 0.13%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.13%   |
| Huawei Technologies                             | 1         | 0.13%   |
| Giga-Byte Technology                            | 1         | 0.13%   |
| Focusrite-Novation                              | 1         | 0.13%   |
| FiiO Electronics Technology                     | 1         | 0.13%   |
| ESS Technology                                  | 1         | 0.13%   |
| Corsair                                         | 1         | 0.13%   |
| Conexant Systems                                | 1         | 0.13%   |
| BEHRINGER International                         | 1         | 0.13%   |
| AudioQuest                                      | 1         | 0.13%   |
| AUDIOLAB                                        | 1         | 0.13%   |
| Audio-Technica                                  | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 52        | 5.63%   |
| Intel Sunrise Point-LP HD Audio                                                   | 51        | 5.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 44        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 42        | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 26        | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 23        | 2.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 21        | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 18        | 1.95%   |
| AMD Starship/Matisse HD Audio Controller                                          | 17        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 17        | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17        | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 16        | 1.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 16        | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 15        | 1.62%   |
| AMD FCH Azalia Controller                                                         | 15        | 1.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 15        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                        | 14        | 1.52%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 13        | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                          | 13        | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 12        | 1.3%    |
| Intel Haswell-ULT HD Audio Controller                                             | 12        | 1.3%    |
| Intel 8 Series HD Audio Controller                                                | 12        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 11        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                                     | 11        | 1.19%   |
| Intel Comet Lake PCH cAVS                                                         | 11        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 11        | 1.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 11        | 1.19%   |
| Realtek Semiconductor USB Audio                                                   | 10        | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                     | 10        | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                     | 9         | 0.97%   |
| Nvidia GM204 High Definition Audio Controller                                     | 8         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 8         | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 8         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 8         | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 8         | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 8         | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 8         | 0.87%   |
| Plantronics Poly Voyager Focus 2 Series                                           | 7         | 0.76%   |
| Nvidia MCP79 High Definition Audio                                                | 7         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 69        | 20.85%  |
| SK hynix            | 59        | 17.82%  |
| Micron Technology   | 34        | 10.27%  |
| Unknown             | 32        | 9.67%   |
| Crucial             | 32        | 9.67%   |
| Kingston            | 29        | 8.76%   |
| Corsair             | 29        | 8.76%   |
| G.Skill             | 8         | 2.42%   |
| Ramaxel Technology  | 7         | 2.11%   |
| Elpida              | 5         | 1.51%   |
| Unknown (ABCD)      | 4         | 1.21%   |
| Team                | 3         | 0.91%   |
| Patriot             | 3         | 0.91%   |
| Nanya Technology    | 3         | 0.91%   |
| Apacer              | 2         | 0.6%    |
| A-DATA Technology   | 2         | 0.6%    |
| A Force             | 2         | 0.6%    |
| Transcend           | 1         | 0.3%    |
| Toshiba             | 1         | 0.3%    |
| SHARETRONIC         | 1         | 0.3%    |
| OSV                 | 1         | 0.3%    |
| Infineon            | 1         | 0.3%    |
| CSX                 | 1         | 0.3%    |
| 4ea5                | 1         | 0.3%    |
| Unknown             | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 1.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.12%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.84%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.84%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 3         | 0.84%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.84%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 3         | 0.84%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 0.84%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.56%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.56%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 0.56%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 2         | 0.56%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s             | 2         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 2         | 0.56%   |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.56%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.56%   |
| SK hynix RAM H54G56CYRBX247N 2GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.56%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.56%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 131       | 45.33%  |
| DDR3    | 86        | 29.76%  |
| LPDDR4  | 17        | 5.88%   |
| DDR2    | 14        | 4.84%   |
| Unknown | 12        | 4.15%   |
| SDRAM   | 10        | 3.46%   |
| LPDDR3  | 7         | 2.42%   |
| DDR5    | 6         | 2.08%   |
| DDR     | 3         | 1.04%   |
| DRAM    | 2         | 0.69%   |
| LPDDR5  | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 165       | 56.9%   |
| DIMM         | 94        | 32.41%  |
| Row Of Chips | 24        | 8.28%   |
| Chip         | 4         | 1.38%   |
| Unknown      | 3         | 1.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 116       | 36.83%  |
| 4096  | 83        | 26.35%  |
| 16384 | 48        | 15.24%  |
| 2048  | 40        | 12.7%   |
| 32768 | 12        | 3.81%   |
| 1024  | 12        | 3.81%   |
| 128   | 2         | 0.63%   |
| 512   | 1         | 0.32%   |
| 256   | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 57        | 18.04%  |
| 2667    | 41        | 12.97%  |
| 3200    | 40        | 12.66%  |
| 2400    | 29        | 9.18%   |
| 2133    | 20        | 6.33%   |
| 1333    | 16        | 5.06%   |
| 800     | 12        | 3.8%    |
| 667     | 10        | 3.16%   |
| 4267    | 9         | 2.85%   |
| 1334    | 8         | 2.53%   |
| 3600    | 7         | 2.22%   |
| 3266    | 7         | 2.22%   |
| 1867    | 6         | 1.9%    |
| 4800    | 5         | 1.58%   |
| 1067    | 5         | 1.58%   |
| Unknown | 5         | 1.58%   |
| 8400    | 3         | 0.95%   |
| 3466    | 3         | 0.95%   |
| 1866    | 3         | 0.95%   |
| 1800    | 3         | 0.95%   |
| 533     | 3         | 0.95%   |
| 4266    | 2         | 0.63%   |
| 4199    | 2         | 0.63%   |
| 3400    | 2         | 0.63%   |
| 1648    | 2         | 0.63%   |
| 1066    | 2         | 0.63%   |
| 975     | 2         | 0.63%   |
| 6400    | 1         | 0.32%   |
| 5200    | 1         | 0.32%   |
| 3800    | 1         | 0.32%   |
| 3733    | 1         | 0.32%   |
| 3000    | 1         | 0.32%   |
| 2933    | 1         | 0.32%   |
| 2733    | 1         | 0.32%   |
| 2666    | 1         | 0.32%   |
| 2267    | 1         | 0.32%   |
| 2048    | 1         | 0.32%   |
| 1639    | 1         | 0.32%   |
| 400     | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| STMicroelectronics  | 2         | 28.57%  |
| Canon               | 2         | 28.57%  |
| Brother Industries  | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 80        | 22.73%  |
| Realtek Semiconductor                  | 40        | 11.36%  |
| IMC Networks                           | 32        | 9.09%   |
| Microdia                               | 31        | 8.81%   |
| Logitech                               | 24        | 6.82%   |
| Sunplus Innovation Technology          | 22        | 6.25%   |
| Quanta                                 | 16        | 4.55%   |
| Apple                                  | 15        | 4.26%   |
| Acer                                   | 15        | 4.26%   |
| Bison Electronics                      | 12        | 3.41%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 2.56%   |
| Suyin                                  | 6         | 1.7%    |
| Samsung Electronics                    | 6         | 1.7%    |
| ALi                                    | 5         | 1.42%   |
| Syntek                                 | 4         | 1.14%   |
| Silicon Motion                         | 4         | 1.14%   |
| Microsoft                              | 4         | 1.14%   |
| Lite-On Technology                     | 4         | 1.14%   |
| Ricoh                                  | 3         | 0.85%   |
| Generalplus Technology                 | 2         | 0.57%   |
| Creative Technology                    | 2         | 0.57%   |
| Z-Star Microelectronics                | 1         | 0.28%   |
| Y Media                                | 1         | 0.28%   |
| WaveRider Communications               | 1         | 0.28%   |
| USB3.0 HD Audio Capture                | 1         | 0.28%   |
| Trust                                  | 1         | 0.28%   |
| SunplusIT                              | 1         | 0.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.28%   |
| Razer USA                              | 1         | 0.28%   |
| Nikon                                  | 1         | 0.28%   |
| MacroSilicon                           | 1         | 0.28%   |
| Luxvisions Innotech Limited            | 1         | 0.28%   |
| Lenovo                                 | 1         | 0.28%   |
| GenesysLogic Technology                | 1         | 0.28%   |
| GEMBIRD                                | 1         | 0.28%   |
| DigiTech                               | 1         | 0.28%   |
| Alcor Micro                            | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Chicony Integrated Camera                  | 18        | 5.07%   |
| Realtek Integrated_Webcam_HD               | 14        | 3.94%   |
| Microdia Integrated_Webcam_HD              | 14        | 3.94%   |
| IMC Networks Integrated Camera             | 11        | 3.1%    |
| Apple Built-in iSight                      | 10        | 2.82%   |
| Logitech HD Pro Webcam C920                | 9         | 2.54%   |
| Sunplus Integrated_Webcam_FHD              | 8         | 2.25%   |
| Chicony HD WebCam                          | 8         | 2.25%   |
| Chicony USB2.0 Camera                      | 7         | 1.97%   |
| Samsung Galaxy series, misc. (MTP mode)    | 6         | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam          | 6         | 1.69%   |
| Microdia Integrated Webcam                 | 5         | 1.41%   |
| Bison Integrated Camera                    | 5         | 1.41%   |
| Acer Integrated Camera                     | 5         | 1.41%   |
| Sunplus Integrated_Webcam_HD               | 4         | 1.13%   |
| Realtek Integrated Webcam HD               | 4         | 1.13%   |
| Chicony HP Wide Vision HD Camera           | 4         | 1.13%   |
| Realtek USB2.0 HD UVC WebCam               | 3         | 0.85%   |
| Microsoft LifeCam HD-3000                  | 3         | 0.85%   |
| Microdia USB 2.0 Camera                    | 3         | 0.85%   |
| Logitech Webcam C270                       | 3         | 0.85%   |
| Lite-On HP HD Camera                       | 3         | 0.85%   |
| Chicony USB2.0 HD UVC WebCam               | 3         | 0.85%   |
| Chicony Lenovo EasyCamera                  | 3         | 0.85%   |
| Chicony HP HD Camera                       | 3         | 0.85%   |
| Chicony EasyCamera                         | 3         | 0.85%   |
| Apple FaceTime HD Camera (Built-in)        | 3         | 0.85%   |
| ALi WebCam                                 | 3         | 0.85%   |
| Syntek Integrated Camera                   | 2         | 0.56%   |
| Syntek EasyCamera                          | 2         | 0.56%   |
| Suyin HP Truevision HD                     | 2         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_FHD       | 2         | 0.56%   |
| Sunplus HP HD Webcam [Fixed]               | 2         | 0.56%   |
| Realtek Integrated Webcam                  | 2         | 0.56%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.56%   |
| Realtek HD WebCam                          | 2         | 0.56%   |
| Realtek EasyCamera                         | 2         | 0.56%   |
| Quanta USB2.0 HD UVC WebCam                | 2         | 0.56%   |
| Quanta HP Wide Vision HD Camera            | 2         | 0.56%   |
| Quanta HP Webcam                           | 2         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 24        | 32%     |
| Validity Sensors           | 20        | 26.67%  |
| Shenzhen Goodix Technology | 17        | 22.67%  |
| Upek                       | 4         | 5.33%   |
| Elan Microelectronics      | 3         | 4%      |
| AuthenTec                  | 3         | 4%      |
| LighTuning Technology      | 2         | 2.67%   |
| STMicroelectronics         | 1         | 1.33%   |
| Focal-systems.Corp         | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                         | 8         | 10.67%  |
| Shenzhen Goodix FingerPrint                                | 6         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 6.67%   |
| Unknown                                                    | 5         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 5.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 4%      |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 4%      |
| AuthenTec Fingerprint Sensor                               | 3         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 2.67%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 2.67%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 2.67%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 2.67%   |
| Validity Sensors Synaptics WBDI                            | 2         | 2.67%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 2.67%   |
| Synaptics  WBDI                                            | 2         | 2.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 2.67%   |
| Elan ELAN:Fingerprint                                      | 2         | 2.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.33%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.33%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.33%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.33%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.33%   |
| Synaptics WBDI                                             | 1         | 1.33%   |
| Synaptics UWP WBDI                                         | 1         | 1.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 1.33%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.33%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 29        | 63.04%  |
| Alcor Micro | 7         | 15.22%  |
| Upek        | 5         | 10.87%  |
| O2 Micro    | 4         | 8.7%    |
| Lenovo      | 1         | 2.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 14        | 30.43%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 15.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.04%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 10.87%  |
| Broadcom 5880                                                                | 5         | 10.87%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 8.7%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.17%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 361       | 63.56%  |
| 1     | 160       | 28.17%  |
| 2     | 37        | 6.51%   |
| 3     | 9         | 1.58%   |
| 5     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 74        | 29.72%  |
| Net/wireless             | 52        | 20.88%  |
| Chipcard                 | 41        | 16.47%  |
| Graphics card            | 40        | 16.06%  |
| Multimedia controller    | 12        | 4.82%   |
| Communication controller | 7         | 2.81%   |
| Camera                   | 7         | 2.81%   |
| Storage                  | 5         | 2.01%   |
| Card reader              | 3         | 1.2%    |
| Bluetooth                | 3         | 1.2%    |
| Net/ethernet             | 2         | 0.8%    |
| Unassigned class         | 1         | 0.4%    |
| Sound                    | 1         | 0.4%    |
| Modem                    | 1         | 0.4%    |

