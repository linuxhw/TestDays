Kubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

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

Total: 866

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| Dell          | Latitude E7470              | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Acer          | Aspire A515-43              | [6aa1f3a294](https://linux-hardware.org/?probe=6aa1f3a294) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | [3e65346dfd](https://linux-hardware.org/?probe=3e65346dfd) | Nov 02, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [cde7923bf2](https://linux-hardware.org/?probe=cde7923bf2) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | [f65225d50a](https://linux-hardware.org/?probe=f65225d50a) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | [69f7a5ebed](https://linux-hardware.org/?probe=69f7a5ebed) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| Dell          | Latitude 7290               | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| Acer          | Aspire AV15-51              | [84064baf19](https://linux-hardware.org/?probe=84064baf19) | Oct 31, 2023 |
| Dell          | Latitude 5530               | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| HP            | Laptop 17-cp0xxx            | [9b3c09e73a](https://linux-hardware.org/?probe=9b3c09e73a) | Oct 27, 2023 |
| EXTRA Comp... | MS-1758                     | [eced546e79](https://linux-hardware.org/?probe=eced546e79) | Oct 26, 2023 |
| HP            | Pavilion 17                 | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| HP            | Pavilion g7                 | [3bd963fd9e](https://linux-hardware.org/?probe=3bd963fd9e) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| HP            | Pavilion Notebook           | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [55c5bbce9f](https://linux-hardware.org/?probe=55c5bbce9f) | Oct 23, 2023 |
| AZW           | SEi                         | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| HP            | ProBook 4340s               | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| Dell          | Latitude E7470              | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [4bfe18fe76](https://linux-hardware.org/?probe=4bfe18fe76) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [e83ad29e5e](https://linux-hardware.org/?probe=e83ad29e5e) | Oct 20, 2023 |
| HP            | G60                         | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Dell          | Precision 7520              | [bd78f68578](https://linux-hardware.org/?probe=bd78f68578) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| HP            | ZBook 15 G3                 | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| Dell          | Latitude E7470              | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | [92049beb26](https://linux-hardware.org/?probe=92049beb26) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | [3eff97b04d](https://linux-hardware.org/?probe=3eff97b04d) | Oct 15, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [f18ac93db8](https://linux-hardware.org/?probe=f18ac93db8) | Oct 13, 2023 |
| Dell          | Latitude 7490               | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| HP            | EliteBook 8770w             | [bf26581f5d](https://linux-hardware.org/?probe=bf26581f5d) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| Dell          | Vostro 5490                 | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Alienware     | m16 R1                      | [6ea5ba513f](https://linux-hardware.org/?probe=6ea5ba513f) | Oct 11, 2023 |
| Alienware     | m16 R1                      | [f9c4374e7c](https://linux-hardware.org/?probe=f9c4374e7c) | Oct 11, 2023 |
| Dell          | Latitude 5511               | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | Latitude 5530               | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [3ba4207fd0](https://linux-hardware.org/?probe=3ba4207fd0) | Oct 09, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| Medion        | E15302                      | [d26c76cedf](https://linux-hardware.org/?probe=d26c76cedf) | Oct 07, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [5ff0e17804](https://linux-hardware.org/?probe=5ff0e17804) | Oct 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [5b84610e15](https://linux-hardware.org/?probe=5b84610e15) | Oct 06, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [e796c2f9ba](https://linux-hardware.org/?probe=e796c2f9ba) | Oct 05, 2023 |
| Dell          | Latitude 7490               | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [2fdd309c6a](https://linux-hardware.org/?probe=2fdd309c6a) | Oct 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [f349819e0a](https://linux-hardware.org/?probe=f349819e0a) | Oct 02, 2023 |
| Google        | Blorb                       | [04e37bafe3](https://linux-hardware.org/?probe=04e37bafe3) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [122f1d4ca8](https://linux-hardware.org/?probe=122f1d4ca8) | Oct 02, 2023 |
| Schenker      | VIA 15 Pro (M22)            | [1919690674](https://linux-hardware.org/?probe=1919690674) | Oct 01, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| Alienware     | x15 R1                      | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| HP            | EliteBook 8770w             | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| Lenovo        | B480 20140                  | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Apple         | MacBookPro9,2               | [2691aa5f87](https://linux-hardware.org/?probe=2691aa5f87) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [c7142a0d96](https://linux-hardware.org/?probe=c7142a0d96) | Sep 20, 2023 |
| Toshiba       | Satellite Pro C70-B         | [a24c6808ba](https://linux-hardware.org/?probe=a24c6808ba) | Sep 20, 2023 |
| Dell          | Precision 7520              | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| Dell          | Precision 7520              | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| Dell          | Inspiron 5520               | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| HP            | Compaq 6820s                | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| Notebook      | P65_P67SA                   | [4d11ae0ff7](https://linux-hardware.org/?probe=4d11ae0ff7) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | Modern 15 A5M               | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| Dell          | Latitude 7490               | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Dell          | Latitude E6500              | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | Latitude E6500              | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| Dell          | XPS 9315                    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| MSI           | GL65 9SE                    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Dell          | Latitude E6520              | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| Schenker      | XMG PRO (E23)               | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| Dell          | XPS 15 9530                 | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Medion        | P651x series                | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| HP            | ZBook 15 G3                 | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Timi          | RedmiBook 14-APCS           | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Latitude 5530               | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| System76      | Galago Pro                  | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Dell          | Inspiron 16 7610            | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| HP            | G60                         | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| HP            | Presario CQ62               | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| Dell          | Latitude 7530               | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | G3 3779                     | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Fujitsu       | LIFEBOOK U757               | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Dell          | Latitude E5450              | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| Dell          | G3 3590                     | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | MacBookPro12,1              | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Dell          | Latitude 3310               | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Proline       | V1165C4                     | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Samsung       | 550XCJ/550XCR               | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| PC Special... | Initia Ii 15                | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Acer          | Nitro AN515-56              | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| Acer          | Aspire A317-53              | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Dell          | Latitude E6500              | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Dell          | G15 5525                    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Acer          | Aspire A317-53              | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire A515-45              | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Acer          | Aspire V3-772               | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| Acer          | Aspire V3-772               | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Acer          | Aspire A317-53              | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Fujitsu       | LIFEBOOK U748               | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| Notebook      | NLx0MU                      | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Dell          | Latitude E5530 non-vPro     | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Dell          | XPS 15 7590                 | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| Dell          | Latitude E6500              | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| Dell          | G3 3590                     | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Latitude 7490               | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| HP            | EliteBook 8470p             | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Dell          | Latitude 3570               | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Dell          | XPS 13 9300                 | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Razer         | Blade Pro 17 (2019)         | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| ASUSTek       | X750JB                      | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| Dell          | Inspiron 3593               | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| Acer          | Aspire M5-481T              | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Dell          | Inspiron 3793               | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Carbon Sys... | Iridium 14                  | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| Carbon Sys... | Iridium 14                  | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Unknown       | Unknown                     | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| HP            | Laptop 15-ef2xxx            | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| MSI           | Modern 15 A5M               | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Notebook      | NV4xPZ                      | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Carbon Sys... | Iridium 14                  | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | Latitude E6420              | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-52-generic    | 42        | 6.09%   |
| 5.15.0-56-generic    | 38        | 5.51%   |
| 5.15.0-58-generic    | 27        | 3.91%   |
| 5.15.0-53-generic    | 22        | 3.19%   |
| 5.15.0-48-generic    | 22        | 3.19%   |
| 5.15.0-60-generic    | 21        | 3.04%   |
| 5.15.0-47-generic    | 21        | 3.04%   |
| 6.2.0-34-generic     | 19        | 2.75%   |
| 6.2.0-26-generic     | 19        | 2.75%   |
| 5.15.0-43-generic    | 18        | 2.61%   |
| 5.15.0-46-generic    | 17        | 2.46%   |
| 5.15.0-41-generic    | 17        | 2.46%   |
| 5.15.0-25-generic    | 16        | 2.32%   |
| 5.19.0-32-generic    | 15        | 2.17%   |
| 5.15.0-40-generic    | 15        | 2.17%   |
| 5.19.0-46-generic    | 14        | 2.03%   |
| 5.19.0-35-generic    | 14        | 2.03%   |
| 6.2.0-33-generic     | 13        | 1.88%   |
| 5.15.0-50-generic    | 12        | 1.74%   |
| 5.15.0-27-generic    | 12        | 1.74%   |
| 5.19.0-41-generic    | 11        | 1.59%   |
| 5.15.0-67-generic    | 11        | 1.59%   |
| 5.19.0-38-generic    | 10        | 1.45%   |
| 5.15.0-33-generic    | 10        | 1.45%   |
| 6.2.0-32-generic     | 9         | 1.3%    |
| 5.19.0-42-generic    | 9         | 1.3%    |
| 5.15.0-57-generic    | 9         | 1.3%    |
| 5.19.0-43-generic    | 8         | 1.16%   |
| 5.15.0-71-generic    | 8         | 1.16%   |
| 5.19.0-50-generic    | 7         | 1.01%   |
| 5.15.0-39-generic    | 7         | 1.01%   |
| 5.15.0-78-generic    | 6         | 0.87%   |
| 5.15.0-72-generic    | 6         | 0.87%   |
| 5.15.0-69-generic    | 6         | 0.87%   |
| 6.2.0-36-generic     | 5         | 0.72%   |
| 5.19.0-45-generic    | 5         | 0.72%   |
| 5.15.0-87-generic    | 5         | 0.72%   |
| 5.15.0-75-generic    | 5         | 0.72%   |
| 5.15.0-43-lowlatency | 5         | 0.72%   |
| 5.15.0-37-generic    | 5         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 425       | 65.08%  |
| 5.19.0  | 102       | 15.62%  |
| 6.2.0   | 72        | 11.03%  |
| 5.17.0  | 8         | 1.23%   |
| 6.1.0   | 4         | 0.61%   |
| 6.0.0   | 4         | 0.61%   |
| 5.13.0  | 3         | 0.46%   |
| 6.2.2   | 2         | 0.31%   |
| 6.2.16  | 2         | 0.31%   |
| 6.0.7   | 2         | 0.31%   |
| 5.19.5  | 2         | 0.31%   |
| 6.5.7   | 1         | 0.15%   |
| 6.4.8   | 1         | 0.15%   |
| 6.4.10  | 1         | 0.15%   |
| 6.3.9   | 1         | 0.15%   |
| 6.3.8   | 1         | 0.15%   |
| 6.3.4   | 1         | 0.15%   |
| 6.3.0   | 1         | 0.15%   |
| 6.2.8   | 1         | 0.15%   |
| 6.1.9   | 1         | 0.15%   |
| 6.1.55  | 1         | 0.15%   |
| 6.1.12  | 1         | 0.15%   |
| 6.0.9   | 1         | 0.15%   |
| 6.0.6   | 1         | 0.15%   |
| 6.0.1   | 1         | 0.15%   |
| 5.19.2  | 1         | 0.15%   |
| 5.19.11 | 1         | 0.15%   |
| 5.18.6  | 1         | 0.15%   |
| 5.18.15 | 1         | 0.15%   |
| 5.18.10 | 1         | 0.15%   |
| 5.17.5  | 1         | 0.15%   |
| 5.17.4  | 1         | 0.15%   |
| 5.17.2  | 1         | 0.15%   |
| 5.16.2  | 1         | 0.15%   |
| 5.16.11 | 1         | 0.15%   |
| 5.15.65 | 1         | 0.15%   |
| 5.15.34 | 1         | 0.15%   |
| 5.14.0  | 1         | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 426       | 65.44%  |
| 5.19    | 106       | 16.28%  |
| 6.2     | 77        | 11.83%  |
| 5.17    | 11        | 1.69%   |
| 6.0     | 8         | 1.23%   |
| 6.1     | 7         | 1.08%   |
| 6.3     | 4         | 0.61%   |
| 5.18    | 3         | 0.46%   |
| 5.13    | 3         | 0.46%   |
| 6.4     | 2         | 0.31%   |
| 5.16    | 2         | 0.31%   |
| 6.5     | 1         | 0.15%   |
| 5.14    | 1         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 628       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 612       | 97.14%  |
| KDE        | 6         | 0.95%   |
| GNOME      | 6         | 0.95%   |
| XFCE       | 1         | 0.16%   |
| X-Cinnamon | 1         | 0.16%   |
| MATE       | 1         | 0.16%   |
| i3         | 1         | 0.16%   |
| GNUstep    | 1         | 0.16%   |
| Cinnamon   | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 598       | 94.62%  |
| Wayland | 26        | 4.11%   |
| Tty     | 8         | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 475       | 75.28%  |
| Unknown | 113       | 17.91%  |
| GDM3    | 28        | 4.44%   |
| LightDM | 13        | 2.06%   |
| SLiM    | 1         | 0.16%   |
| LXDM    | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 306       | 48.49%  |
| de_DE   | 56        | 8.87%   |
| ru_RU   | 31        | 4.91%   |
| it_IT   | 31        | 4.91%   |
| en_GB   | 29        | 4.6%    |
| fr_FR   | 22        | 3.49%   |
| es_ES   | 17        | 2.69%   |
| en_IN   | 16        | 2.54%   |
| pl_PL   | 13        | 2.06%   |
| pt_BR   | 11        | 1.74%   |
| en_AU   | 10        | 1.58%   |
| en_CA   | 9         | 1.43%   |
| hu_HU   | 6         | 0.95%   |
| cs_CZ   | 6         | 0.95%   |
| tr_TR   | 5         | 0.79%   |
| zh_CN   | 4         | 0.63%   |
| en_ZA   | 4         | 0.63%   |
| en_PH   | 4         | 0.63%   |
| en_NZ   | 4         | 0.63%   |
| Default | 4         | 0.63%   |
| es_MX   | 3         | 0.48%   |
| es_CO   | 3         | 0.48%   |
| es_AR   | 3         | 0.48%   |
| en_SG   | 3         | 0.48%   |
| C       | 3         | 0.48%   |
| nl_BE   | 2         | 0.32%   |
| fr_CH   | 2         | 0.32%   |
| fr_BE   | 2         | 0.32%   |
| fi_FI   | 2         | 0.32%   |
| es_CL   | 2         | 0.32%   |
| zh_TW   | 1         | 0.16%   |
| uk_UA   | 1         | 0.16%   |
| sv_SE   | 1         | 0.16%   |
| sl_SI   | 1         | 0.16%   |
| pt_PT   | 1         | 0.16%   |
| nb_NO   | 1         | 0.16%   |
| lt_LT   | 1         | 0.16%   |
| ko_KR   | 1         | 0.16%   |
| et_EE   | 1         | 0.16%   |
| es_VE   | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 383       | 60.41%  |
| BIOS | 251       | 39.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 543       | 85.65%  |
| Tmpfs   | 40        | 6.31%   |
| Btrfs   | 24        | 3.79%   |
| Overlay | 22        | 3.47%   |
| Xfs     | 3         | 0.47%   |
| Zfs     | 1         | 0.16%   |
| Ext2    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 449       | 71.04%  |
| Unknown | 148       | 23.42%  |
| MBR     | 35        | 5.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 584       | 92.99%  |
| Yes       | 44        | 7.01%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 392       | 62.22%  |
| Yes       | 238       | 37.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 160       | 25.48%  |
| Dell                           | 106       | 16.88%  |
| Hewlett-Packard                | 104       | 16.56%  |
| ASUSTek Computer               | 58        | 9.24%   |
| Acer                           | 46        | 7.32%   |
| MSI                            | 20        | 3.18%   |
| HUAWEI                         | 15        | 2.39%   |
| Apple                          | 12        | 1.91%   |
| Samsung Electronics            | 9         | 1.43%   |
| Toshiba                        | 7         | 1.11%   |
| Google                         | 7         | 1.11%   |
| Notebook                       | 6         | 0.96%   |
| TUXEDO                         | 5         | 0.8%    |
| Alienware                      | 5         | 0.8%    |
| Timi                           | 4         | 0.64%   |
| Gigabyte Technology            | 4         | 0.64%   |
| Fujitsu                        | 4         | 0.64%   |
| System76                       | 3         | 0.48%   |
| Sony                           | 3         | 0.48%   |
| Schenker                       | 3         | 0.48%   |
| Framework                      | 3         | 0.48%   |
| Razer                          | 2         | 0.32%   |
| Panasonic                      | 2         | 0.32%   |
| Medion                         | 2         | 0.32%   |
| LG Electronics                 | 2         | 0.32%   |
| HONOR                          | 2         | 0.32%   |
| Haier                          | 2         | 0.32%   |
| GPU Company                    | 2         | 0.32%   |
| Carbon Systems                 | 2         | 0.32%   |
| Unknown                        | 2         | 0.32%   |
| VALE                           | 1         | 0.16%   |
| TrekStor                       | 1         | 0.16%   |
| Thomson                        | 1         | 0.16%   |
| TerraQue                       | 1         | 0.16%   |
| Tactus                         | 1         | 0.16%   |
| Standard                       | 1         | 0.16%   |
| SLIMBOOK                       | 1         | 0.16%   |
| SK hynix                       | 1         | 0.16%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.16%   |
| SGIN                           | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 6         | 0.96%   |
| HUAWEI HVY-WXX9                        | 5         | 0.8%    |
| HP 255 G8 Notebook PC                  | 4         | 0.64%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.48%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 3         | 0.48%   |
| Lenovo IdeaPad 3 15ALC6 82KU           | 3         | 0.48%   |
| HP ProBook 6470b                       | 3         | 0.48%   |
| HP ProBook 440 G8 Notebook PC          | 3         | 0.48%   |
| HP Pavilion g6                         | 3         | 0.48%   |
| HP OMEN Laptop 15-en0xxx               | 3         | 0.48%   |
| HP Laptop 15-ef2xxx                    | 3         | 0.48%   |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.48%   |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.48%   |
| Dell XPS 15 9560                       | 3         | 0.48%   |
| Dell Latitude 7490                     | 3         | 0.48%   |
| Dell Latitude 5420                     | 3         | 0.48%   |
| Dell Latitude 3420                     | 3         | 0.48%   |
| Acer Aspire A515-45                    | 3         | 0.48%   |
| Timi TM1701                            | 2         | 0.32%   |
| MSI Modern 15 A5M                      | 2         | 0.32%   |
| Lenovo Z50-75 80EC                     | 2         | 0.32%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.32%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ       | 2         | 0.32%   |
| Lenovo Legion 5 15ACH6H 82JU           | 2         | 0.32%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 2         | 0.32%   |
| Lenovo IdeaPad 3 15ARE05 81W4          | 2         | 0.32%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 2         | 0.32%   |
| HUAWEI CREM-WXX9                       | 2         | 0.32%   |
| HP ZBook 15 G6                         | 2         | 0.32%   |
| HP ZBook 15 G3                         | 2         | 0.32%   |
| HP ProBook 6570b                       | 2         | 0.32%   |
| HP Pavilion Notebook                   | 2         | 0.32%   |
| HP Pavilion Laptop 15-eh1xxx           | 2         | 0.32%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 2         | 0.32%   |
| HP Pavilion dv6                        | 2         | 0.32%   |
| HP Notebook                            | 2         | 0.32%   |
| HP Laptop 17-cp0xxx                    | 2         | 0.32%   |
| HP Laptop 17-by3xxx                    | 2         | 0.32%   |
| HP Laptop 15-da0xxx                    | 2         | 0.32%   |
| HP EliteBook 8470p                     | 2         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 75        | 11.94%  |
| Lenovo IdeaPad      | 42        | 6.69%   |
| Dell Latitude       | 40        | 6.37%   |
| Acer Aspire         | 27        | 4.3%    |
| Dell Inspiron       | 22        | 3.5%    |
| HP Pavilion         | 20        | 3.18%   |
| HP ProBook          | 18        | 2.87%   |
| ASUS VivoBook       | 17        | 2.71%   |
| HP Laptop           | 16        | 2.55%   |
| HP EliteBook        | 15        | 2.39%   |
| Dell XPS            | 15        | 2.39%   |
| Lenovo Legion       | 12        | 1.91%   |
| Dell Precision      | 12        | 1.91%   |
| Lenovo ThinkBook    | 10        | 1.59%   |
| Acer Nitro          | 9         | 1.43%   |
| Dell Vostro         | 8         | 1.27%   |
| HP ZBook            | 7         | 1.11%   |
| Toshiba Satellite   | 6         | 0.96%   |
| ASUS ROG            | 6         | 0.96%   |
| Unknown             | 6         | 0.96%   |
| HUAWEI HVY-WXX9     | 5         | 0.8%    |
| HP OMEN             | 5         | 0.8%    |
| HP 255              | 5         | 0.8%    |
| ASUS ASUS           | 5         | 0.8%    |
| Lenovo Yoga         | 4         | 0.64%   |
| Fujitsu LIFEBOOK    | 4         | 0.64%   |
| Dell G3             | 4         | 0.64%   |
| Apple MacBookPro11  | 4         | 0.64%   |
| Acer Swift          | 4         | 0.64%   |
| MSI Modern          | 3         | 0.48%   |
| HP ENVY             | 3         | 0.48%   |
| Framework Laptop    | 3         | 0.48%   |
| Dell G15            | 3         | 0.48%   |
| Acer Predator       | 3         | 0.48%   |
| TUXEDO InfinityBook | 2         | 0.32%   |
| Timi TM1701         | 2         | 0.32%   |
| Schenker XMG        | 2         | 0.32%   |
| Razer Blade         | 2         | 0.32%   |
| Notebook PD5x       | 2         | 0.32%   |
| MSI Raider          | 2         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 126       | 20.06%  |
| 2020 | 92        | 14.65%  |
| 2022 | 73        | 11.62%  |
| 2019 | 56        | 8.92%   |
| 2012 | 49        | 7.8%    |
| 2018 | 35        | 5.57%   |
| 2017 | 30        | 4.78%   |
| 2014 | 29        | 4.62%   |
| 2013 | 28        | 4.46%   |
| 2016 | 26        | 4.14%   |
| 2011 | 24        | 3.82%   |
| 2015 | 18        | 2.87%   |
| 2010 | 14        | 2.23%   |
| 2023 | 13        | 2.07%   |
| 2008 | 6         | 0.96%   |
| 2007 | 6         | 0.96%   |
| 2009 | 3         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 628       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 545       | 86.23%  |
| Enabled  | 87        | 13.77%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 619       | 98.57%  |
| Yes  | 9         | 1.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 169       | 26.66%  |
| 16.01-24.0  | 159       | 25.08%  |
| 8.01-16.0   | 111       | 17.51%  |
| 32.01-64.0  | 88        | 13.88%  |
| 3.01-4.0    | 61        | 9.62%   |
| 24.01-32.0  | 20        | 3.15%   |
| 64.01-256.0 | 18        | 2.84%   |
| 2.01-3.0    | 4         | 0.63%   |
| 1.01-2.0    | 4         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 165       | 24.74%  |
| 2.01-3.0   | 163       | 24.44%  |
| 3.01-4.0   | 149       | 22.34%  |
| 1.01-2.0   | 135       | 20.24%  |
| 8.01-16.0  | 46        | 6.9%    |
| 16.01-24.0 | 5         | 0.75%   |
| 0.51-1.0   | 3         | 0.45%   |
| 24.01-32.0 | 1         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 426       | 66.98%  |
| 2      | 179       | 28.14%  |
| 3      | 23        | 3.62%   |
| 4      | 6         | 0.94%   |
| 0      | 2         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 506       | 80.45%  |
| Yes       | 123       | 19.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 466       | 73.97%  |
| No        | 164       | 26.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 625       | 99.52%  |
| No        | 3         | 0.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 548       | 86.44%  |
| No        | 86        | 13.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 115       | 18.23%  |
| Germany      | 74        | 11.73%  |
| Italy        | 47        | 7.45%   |
| Russia       | 38        | 6.02%   |
| France       | 33        | 5.23%   |
| UK           | 24        | 3.8%    |
| Poland       | 23        | 3.65%   |
| Spain        | 20        | 3.17%   |
| Brazil       | 18        | 2.85%   |
| India        | 16        | 2.54%   |
| Hungary      | 14        | 2.22%   |
| Canada       | 12        | 1.9%    |
| Czechia      | 11        | 1.74%   |
| Australia    | 9         | 1.43%   |
| Indonesia    | 8         | 1.27%   |
| Turkey       | 7         | 1.11%   |
| Switzerland  | 6         | 0.95%   |
| Sweden       | 6         | 0.95%   |
| Netherlands  | 6         | 0.95%   |
| Mexico       | 6         | 0.95%   |
| Belgium      | 6         | 0.95%   |
| Argentina    | 6         | 0.95%   |
| Slovenia     | 5         | 0.79%   |
| Philippines  | 5         | 0.79%   |
| China        | 5         | 0.79%   |
| South Africa | 4         | 0.63%   |
| Serbia       | 4         | 0.63%   |
| Portugal     | 4         | 0.63%   |
| New Zealand  | 4         | 0.63%   |
| Greece       | 4         | 0.63%   |
| Finland      | 4         | 0.63%   |
| Estonia      | 4         | 0.63%   |
| Denmark      | 4         | 0.63%   |
| Colombia     | 4         | 0.63%   |
| Bulgaria     | 4         | 0.63%   |
| Vietnam      | 3         | 0.48%   |
| UAE          | 3         | 0.48%   |
| Taiwan       | 3         | 0.48%   |
| South Korea  | 3         | 0.48%   |
| Singapore    | 3         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 13        | 1.99%   |
| Milan              | 11        | 1.68%   |
| Berlin             | 10        | 1.53%   |
| Warsaw             | 8         | 1.22%   |
| Paris              | 8         | 1.22%   |
| Budapest           | 7         | 1.07%   |
| St Petersburg      | 5         | 0.76%   |
| Prague             | 5         | 0.76%   |
| Cologne            | 5         | 0.76%   |
| Castro Valley      | 5         | 0.76%   |
| Bengaluru          | 5         | 0.76%   |
| Madrid             | 4         | 0.61%   |
| Hamburg            | 4         | 0.61%   |
| Adelaide           | 4         | 0.61%   |
| Wroclaw            | 3         | 0.46%   |
| Vladivostok        | 3         | 0.46%   |
| Vilnius            | 3         | 0.46%   |
| Vancouver          | 3         | 0.46%   |
| Turin              | 3         | 0.46%   |
| Tallinn            | 3         | 0.46%   |
| Sydney             | 3         | 0.46%   |
| Singapore          | 3         | 0.46%   |
| Sao Paulo          | 3         | 0.46%   |
| Poznan             | 3         | 0.46%   |
| Krakow             | 3         | 0.46%   |
| Jakarta            | 3         | 0.46%   |
| Houston            | 3         | 0.46%   |
| Frankfurt am Main  | 3         | 0.46%   |
| Dublin             | 3         | 0.46%   |
| Belgrade           | 3         | 0.46%   |
| Auckland           | 3         | 0.46%   |
| Amsterdam          | 3         | 0.46%   |
| Zurich             | 2         | 0.31%   |
| Zagreb             | 2         | 0.31%   |
| Washington         | 2         | 0.31%   |
| Vienna             | 2         | 0.31%   |
| Varna              | 2         | 0.31%   |
| Ufa                | 2         | 0.31%   |
| Trescore Balneario | 2         | 0.31%   |
| Taipei             | 2         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 151       | 199    | 18.37%  |
| WDC                         | 80        | 94     | 9.73%   |
| Seagate                     | 56        | 72     | 6.81%   |
| Kingston                    | 55        | 61     | 6.69%   |
| Sandisk                     | 54        | 74     | 6.57%   |
| SK hynix                    | 49        | 56     | 5.96%   |
| Toshiba                     | 43        | 55     | 5.23%   |
| Unknown                     | 39        | 49     | 4.74%   |
| Intel                       | 37        | 42     | 4.5%    |
| Micron Technology           | 28        | 31     | 3.41%   |
| Crucial                     | 26        | 29     | 3.16%   |
| KIOXIA                      | 21        | 23     | 2.55%   |
| HGST                        | 14        | 16     | 1.7%    |
| Hitachi                     | 12        | 12     | 1.46%   |
| China                       | 12        | 16     | 1.46%   |
| SPCC                        | 8         | 8      | 0.97%   |
| Unknown                     | 8         | 8      | 0.97%   |
| Apple                       | 7         | 8      | 0.85%   |
| A-DATA Technology           | 7         | 7      | 0.85%   |
| SSSTC                       | 6         | 6      | 0.73%   |
| Phison Electronics          | 6         | 6      | 0.73%   |
| LITEON                      | 6         | 6      | 0.73%   |
| Silicon Motion              | 5         | 5      | 0.61%   |
| Phison                      | 5         | 5      | 0.61%   |
| Micron/Crucial Technology   | 5         | 7      | 0.61%   |
| JMicron Technology          | 5         | 5      | 0.61%   |
| UMIS                        | 4         | 4      | 0.49%   |
| Patriot                     | 4         | 4      | 0.49%   |
| Kingston Technology Company | 4         | 4      | 0.49%   |
| Team                        | 3         | 3      | 0.36%   |
| PNY                         | 3         | 3      | 0.36%   |
| Netac                       | 3         | 3      | 0.36%   |
| Union Memory                | 2         | 2      | 0.24%   |
| Smart                       | 2         | 2      | 0.24%   |
| SABRENT                     | 2         | 4      | 0.24%   |
| Realtek Semiconductor       | 2         | 2      | 0.24%   |
| LITEONIT                    | 2         | 2      | 0.24%   |
| Inateck                     | 2         | 2      | 0.24%   |
| GOODRAM                     | 2         | 2      | 0.24%   |
| Emtec                       | 2         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD                    | 11        | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 10        | 1.15%   |
| Toshiba MQ01ABD100 1TB                             | 8         | 0.92%   |
| Samsung SSD 860 EVO 500GB                          | 8         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 8         | 0.92%   |
| Unknown                                            | 8         | 0.92%   |
| Unknown MMC Card  64GB                             | 7         | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                     | 7         | 0.8%    |
| Samsung SSD 970 EVO Plus 500GB                     | 7         | 0.8%    |
| Unknown MMC Card  128GB                            | 6         | 0.69%   |
| Toshiba MQ04ABF100 1TB                             | 6         | 0.69%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                 | 6         | 0.69%   |
| SanDisk NVMe SSD Drive 1TB                         | 6         | 0.69%   |
| Samsung SSD 980 PRO 1TB                            | 6         | 0.69%   |
| Kingston SA400S37240G 240GB SSD                    | 6         | 0.69%   |
| Seagate ST2000LM007-1R8174 2TB                     | 5         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 0.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 5         | 0.57%   |
| Samsung SSD 980 1TB                                | 5         | 0.57%   |
| Samsung SSD 970 EVO Plus 250GB                     | 5         | 0.57%   |
| Samsung SSD 850 EVO 250GB                          | 5         | 0.57%   |
| Unknown MMC Card  32GB                             | 4         | 0.46%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB             | 4         | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB                    | 4         | 0.46%   |
| Seagate ST2000LM015-2E8174 2TB                     | 4         | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                       | 4         | 0.46%   |
| Samsung SSD 850 EVO 500GB                          | 4         | 0.46%   |
| Phison PS5013 E13 NVMe Controller 256GB            | 4         | 0.46%   |
| Intel SSDPEKNW512GZL 512GB                         | 4         | 0.46%   |
| Intel SSDPEKNU512GZ 512GB                          | 4         | 0.46%   |
| HGST HTS721010A9E630 1TB                           | 4         | 0.46%   |
| China SSD 128GB                                    | 4         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 3         | 0.34%   |
| SPCC Solid State Disk 512GB                        | 3         | 0.34%   |
| SK hynix PC801 NVMe 1TB                            | 3         | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                      | 3         | 0.34%   |
| SK hynix BC711 HFM512GD3JX013N 512GB               | 3         | 0.34%   |
| Seagate ST9750420AS 752GB                          | 3         | 0.34%   |
| Seagate Expansion 1TB                              | 3         | 0.34%   |
| SanDisk SSD PLUS 240GB                             | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 70     | 38.57%  |
| WDC                 | 33        | 34     | 23.57%  |
| Toshiba             | 20        | 27     | 14.29%  |
| HGST                | 14        | 16     | 10%     |
| Hitachi             | 12        | 12     | 8.57%   |
| USB3.0              | 1         | 1      | 0.71%   |
| Unknown             | 1         | 1      | 0.71%   |
| Samsung Electronics | 1         | 1      | 0.71%   |
| KESU                | 1         | 1      | 0.71%   |
| HGST HTS            | 1         | 1      | 0.71%   |
| Fujitsu             | 1         | 1      | 0.71%   |
| External            | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 72     | 23.5%   |
| Kingston            | 31        | 35     | 13.25%  |
| SanDisk             | 24        | 33     | 10.26%  |
| Crucial             | 17        | 19     | 7.26%   |
| WDC                 | 13        | 21     | 5.56%   |
| China               | 11        | 15     | 4.7%    |
| Intel               | 7         | 9      | 2.99%   |
| SPCC                | 6         | 6      | 2.56%   |
| LITEON              | 6         | 6      | 2.56%   |
| A-DATA Technology   | 5         | 5      | 2.14%   |
| Toshiba             | 4         | 7      | 1.71%   |
| SK hynix            | 4         | 4      | 1.71%   |
| Patriot             | 4         | 4      | 1.71%   |
| Apple               | 4         | 4      | 1.71%   |
| Team                | 3         | 3      | 1.28%   |
| Micron Technology   | 3         | 3      | 1.28%   |
| Smart               | 2         | 2      | 0.85%   |
| SABRENT             | 2         | 4      | 0.85%   |
| Netac               | 2         | 2      | 0.85%   |
| LITEONIT            | 2         | 2      | 0.85%   |
| GOODRAM             | 2         | 2      | 0.85%   |
| Emtec               | 2         | 2      | 0.85%   |
| Corsair             | 2         | 2      | 0.85%   |
| Unknown             | 2         | 2      | 0.85%   |
| XUM                 | 1         | 1      | 0.43%   |
| VISIPRO             | 1         | 2      | 0.43%   |
| Verbatim            | 1         | 1      | 0.43%   |
| ShiJi               | 1         | 1      | 0.43%   |
| Ramos Technology    | 1         | 1      | 0.43%   |
| R580                | 1         | 1      | 0.43%   |
| PNY                 | 1         | 1      | 0.43%   |
| NGFF                | 1         | 1      | 0.43%   |
| LT                  | 1         | 1      | 0.43%   |
| Kimtigo             | 1         | 1      | 0.43%   |
| Intenso             | 1         | 2      | 0.43%   |
| HUSKY               | 1         | 2      | 0.43%   |
| HS-SSD-C100         | 1         | 1      | 0.43%   |
| HIKSEMI             | 1         | 1      | 0.43%   |
| Hewlett-Packard     | 1         | 1      | 0.43%   |
| Dogfish             | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 366       | 466    | 48.03%  |
| SSD     | 208       | 288    | 27.3%   |
| HDD     | 134       | 166    | 17.59%  |
| MMC     | 42        | 51     | 5.51%   |
| Unknown | 12        | 13     | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 363       | 462    | 50%     |
| SATA | 289       | 422    | 39.81%  |
| MMC  | 42        | 51     | 5.79%   |
| SAS  | 32        | 49     | 4.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 206       | 285    | 60.95%  |
| 0.51-1.0   | 100       | 131    | 29.59%  |
| 1.01-2.0   | 26        | 28     | 7.69%   |
| 3.01-4.0   | 3         | 7      | 0.89%   |
| 4.01-10.0  | 3         | 3      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 186       | 29.06%  |
| 101-250        | 146       | 22.81%  |
| 501-1000       | 129       | 20.16%  |
| 1001-2000      | 78        | 12.19%  |
| 51-100         | 33        | 5.16%   |
| 1-20           | 24        | 3.75%   |
| 2001-3000      | 19        | 2.97%   |
| More than 3000 | 17        | 2.66%   |
| 21-50          | 7         | 1.09%   |
| Unknown        | 1         | 0.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 151       | 23.27%  |
| 101-250        | 141       | 21.73%  |
| 21-50          | 94        | 14.48%  |
| 251-500        | 88        | 13.56%  |
| 51-100         | 88        | 13.56%  |
| 501-1000       | 50        | 7.7%    |
| 1001-2000      | 27        | 4.16%   |
| More than 3000 | 7         | 1.08%   |
| 2001-3000      | 2         | 0.31%   |
| Unknown        | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 5%      |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 2         | 2      | 5%      |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 2         | 2      | 5%      |
| Seagate ST2000LM007-1R8174 2TB                      | 2         | 2      | 5%      |
| SanDisk SSD PLUS 240GB                              | 2         | 2      | 5%      |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 2.5%    |
| VISIPRO SSD 256GB                                   | 1         | 2      | 2.5%    |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.5%    |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 2.5%    |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 2.5%    |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 2.5%    |
| Seagate ST2000LM015-2E8174 2TB                      | 1         | 1      | 2.5%    |
| SanDisk SSD U100 128GB                              | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 2.5%    |
| Samsung Electronics MZVLQ512HBLU-00B00 512GB        | 1         | 1      | 2.5%    |
| Samsung Electronics HM321HI 320GB                   | 1         | 1      | 2.5%    |
| R580 SSD 60GB                                       | 1         | 1      | 2.5%    |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 2.5%    |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.5%    |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 2.5%    |
| Hitachi HTS725050A7E630 500GB                       | 1         | 1      | 2.5%    |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.5%    |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.5%    |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.5%    |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 2.5%    |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.5%    |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.5%    |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 2.5%    |
| Crucial CT1050MX300SSD1 1050GB                      | 1         | 1      | 2.5%    |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 2.5%    |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 2.5%    |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 2.5%    |
| A-DATA Technology FALCON 1TB                        | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 6         | 6      | 15%     |
| Seagate             | 5         | 5      | 12.5%   |
| Hitachi             | 5         | 5      | 12.5%   |
| SK hynix            | 4         | 4      | 10%     |
| SanDisk             | 3         | 3      | 7.5%    |
| Samsung Electronics | 3         | 3      | 7.5%    |
| Crucial             | 3         | 3      | 7.5%    |
| HGST                | 2         | 2      | 5%      |
| A-DATA Technology   | 2         | 2      | 5%      |
| WDC                 | 1         | 1      | 2.5%    |
| VISIPRO             | 1         | 2      | 2.5%    |
| R580                | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| LITEON              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| BAITITON            | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 5         | 5      | 27.78%  |
| Seagate             | 5         | 5      | 27.78%  |
| Hitachi             | 5         | 5      | 27.78%  |
| HGST                | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 18     | 44.74%  |
| SSD  | 14        | 16     | 36.84%  |
| NVMe | 7         | 7      | 18.42%  |

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
| Works    | 372       | 501    | 54.15%  |
| Detected | 277       | 442    | 40.32%  |
| Malfunc  | 38        | 41     | 5.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 371       | 44.92%  |
| Samsung Electronics            | 99        | 11.99%  |
| AMD                            | 83        | 10.05%  |
| SanDisk                        | 64        | 7.75%   |
| SK hynix                       | 45        | 5.45%   |
| Kingston Technology Company    | 28        | 3.39%   |
| Micron Technology              | 25        | 3.03%   |
| Toshiba America Info Systems   | 22        | 2.66%   |
| KIOXIA                         | 18        | 2.18%   |
| Phison Electronics             | 14        | 1.69%   |
| Micron/Crucial Technology      | 14        | 1.69%   |
| Solid State Storage Technology | 8         | 0.97%   |
| Union Memory (Shenzhen)        | 6         | 0.73%   |
| Silicon Motion                 | 6         | 0.73%   |
| Realtek Semiconductor          | 5         | 0.61%   |
| Apple                          | 3         | 0.36%   |
| Shenzhen Longsys Electronics   | 2         | 0.24%   |
| Nvidia                         | 2         | 0.24%   |
| ADATA Technology               | 2         | 0.24%   |
| Zhaoxin                        | 1         | 0.12%   |
| Yangtze Memory Technologies    | 1         | 0.12%   |
| Seagate Technology             | 1         | 0.12%   |
| Netac Technology               | 1         | 0.12%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.12%   |
| Marvell Technology Group       | 1         | 0.12%   |
| Lenovo                         | 1         | 0.12%   |
| JMicron Technology             | 1         | 0.12%   |
| Unknown                        | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 76        | 8.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 51        | 5.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 50        | 5.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 43        | 4.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 42        | 4.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 3.82%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 27        | 3.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 26        | 2.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 24        | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 2.58%   |
| Intel Tiger Lake-LP SATA Controller                                            | 21        | 2.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 20        | 2.25%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 17        | 1.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 1.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 14        | 1.57%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 13        | 1.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 1.35%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 12        | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 1.35%   |
| Intel SSD 660P Series                                                          | 10        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.12%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 9         | 1.01%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 9         | 1.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.01%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 0.9%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 8         | 0.9%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 0.79%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 7         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 0.79%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 6         | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 0.67%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 5         | 0.56%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5         | 0.56%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 5         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 0.56%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 5         | 0.56%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 5         | 0.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 378       | 45%     |
| NVMe | 360       | 42.86%  |
| RAID | 87        | 10.36%  |
| IDE  | 15        | 1.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 474       | 75.48%  |
| AMD          | 153       | 24.36%  |
| CentaurHauls | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 20        | 3.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 18        | 2.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 18        | 2.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 16        | 2.55%   |
| Intel 12th Gen Core i7-12700H           | 14        | 2.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 13        | 2.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 1.91%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 12        | 1.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 11        | 1.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 10        | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 1.43%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 9         | 1.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 1.27%   |
| Intel 12th Gen Core i7-1255U            | 8         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 1.11%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 7         | 1.11%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 7         | 1.11%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 6         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 6         | 0.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 6         | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 5         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 5         | 0.8%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 5         | 0.8%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 5         | 0.8%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 5         | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 0.8%    |
| Intel Core i5-10300H CPU @ 2.50GHz      | 5         | 0.8%    |
| Intel 12th Gen Core i7-1260P            | 5         | 0.8%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 5         | 0.8%    |
| AMD Ryzen 9 5900HX with Radeon Graphics | 5         | 0.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 5         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 4         | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 0.64%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz | 4         | 0.64%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 4         | 0.64%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 4         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 146       | 23.25%  |
| Other                   | 126       | 20.06%  |
| Intel Core i5           | 126       | 20.06%  |
| AMD Ryzen 7             | 54        | 8.6%    |
| AMD Ryzen 5             | 39        | 6.21%   |
| Intel Celeron           | 26        | 4.14%   |
| Intel Core i3           | 18        | 2.87%   |
| Intel Core 2 Duo        | 9         | 1.43%   |
| AMD Ryzen 7 PRO         | 9         | 1.43%   |
| AMD Ryzen 3             | 9         | 1.43%   |
| Intel Pentium           | 8         | 1.27%   |
| AMD Ryzen 9             | 8         | 1.27%   |
| Intel Pentium Silver    | 5         | 0.8%    |
| Intel Core i9           | 5         | 0.8%    |
| AMD Athlon              | 5         | 0.8%    |
| AMD A8                  | 5         | 0.8%    |
| AMD A6                  | 5         | 0.8%    |
| AMD Ryzen 5 PRO         | 4         | 0.64%   |
| AMD E                   | 3         | 0.48%   |
| AMD A10                 | 3         | 0.48%   |
| Intel Core m3           | 2         | 0.32%   |
| AMD FX                  | 2         | 0.32%   |
| AMD Athlon II           | 2         | 0.32%   |
| Intel Xeon              | 1         | 0.16%   |
| Intel Core M            | 1         | 0.16%   |
| Intel Core 2            | 1         | 0.16%   |
| Intel Celeron Dual-Core | 1         | 0.16%   |
| Intel Atom              | 1         | 0.16%   |
| AMD Sempron             | 1         | 0.16%   |
| AMD PRO A10             | 1         | 0.16%   |
| AMD Athlon II Dual-Core | 1         | 0.16%   |
| AMD A4                  | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 217       | 34.55%  |
| 2      | 201       | 32.01%  |
| 8      | 80        | 12.74%  |
| 6      | 75        | 11.94%  |
| 14     | 21        | 3.34%   |
| 10     | 14        | 2.23%   |
| 12     | 13        | 2.07%   |
| 24     | 2         | 0.32%   |
| 16     | 2         | 0.32%   |
| 1      | 2         | 0.32%   |
| 5      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 628       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 542       | 85.9%   |
| 1      | 89        | 14.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 628       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 39.88%  |
| 0x806c1    | 34        | 5.3%    |
| 0x306a9    | 28        | 4.36%   |
| 0x906a3    | 27        | 4.21%   |
| 0x0a50000c | 25        | 3.89%   |
| 0x806ea    | 24        | 3.74%   |
| 0x906ea    | 16        | 2.49%   |
| 0x08608103 | 16        | 2.49%   |
| 0x806ec    | 14        | 2.18%   |
| 0x08600106 | 13        | 2.02%   |
| 0x406e3    | 11        | 1.71%   |
| 0x306c3    | 11        | 1.71%   |
| 0x206a7    | 9         | 1.4%    |
| 0x08108109 | 9         | 1.4%    |
| 0xa0652    | 8         | 1.25%   |
| 0x906a4    | 8         | 1.25%   |
| 0x806e9    | 8         | 1.25%   |
| 0x706a8    | 8         | 1.25%   |
| 0x08608102 | 7         | 1.09%   |
| 0x806d1    | 6         | 0.93%   |
| 0x806c2    | 6         | 0.93%   |
| 0x40651    | 6         | 0.93%   |
| 0x0a50000d | 6         | 0.93%   |
| 0x906e9    | 5         | 0.78%   |
| 0x706e5    | 5         | 0.78%   |
| 0x706a1    | 5         | 0.78%   |
| 0x506e3    | 4         | 0.62%   |
| 0x506c9    | 4         | 0.62%   |
| 0x40661    | 4         | 0.62%   |
| 0x0a404102 | 4         | 0.62%   |
| 0x08108102 | 4         | 0.62%   |
| 0x06006705 | 4         | 0.62%   |
| 0x906ed    | 3         | 0.47%   |
| 0x306d4    | 3         | 0.47%   |
| 0x20655    | 3         | 0.47%   |
| 0x20652    | 3         | 0.47%   |
| 0x1067a    | 3         | 0.47%   |
| 0x0a404101 | 3         | 0.47%   |
| 0x08600103 | 3         | 0.47%   |
| 0x03000027 | 3         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 118       | 18.76%  |
| TigerLake        | 60        | 9.54%   |
| Unknown          | 57        | 9.06%   |
| IvyBridge        | 53        | 8.43%   |
| Zen 3            | 43        | 6.84%   |
| Alderlake Hybrid | 42        | 6.68%   |
| Haswell          | 39        | 6.2%    |
| Skylake          | 28        | 4.45%   |
| Zen 2            | 24        | 3.82%   |
| SandyBridge      | 21        | 3.34%   |
| Goldmont plus    | 21        | 3.34%   |
| Zen+             | 20        | 3.18%   |
| IceLake          | 17        | 2.7%    |
| CometLake        | 16        | 2.54%   |
| Westmere         | 10        | 1.59%   |
| Broadwell        | 9         | 1.43%   |
| Excavator        | 7         | 1.11%   |
| Silvermont       | 6         | 0.95%   |
| Penryn           | 6         | 0.95%   |
| Core             | 6         | 0.95%   |
| Goldmont         | 5         | 0.79%   |
| Puma             | 3         | 0.48%   |
| Piledriver       | 3         | 0.48%   |
| K10 Llano        | 3         | 0.48%   |
| K10              | 3         | 0.48%   |
| Bobcat           | 3         | 0.48%   |
| Zen              | 2         | 0.32%   |
| Steamroller      | 2         | 0.32%   |
| Nehalem          | 1         | 0.16%   |
| K8 & K10 hybrid  | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 447       | 53.21%  |
| Nvidia  | 207       | 24.64%  |
| AMD     | 185       | 22.02%  |
| Zhaoxin | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 52        | 6.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 50        | 5.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 34        | 3.98%   |
| AMD Lucienne                                                                          | 29        | 3.39%   |
| Intel UHD Graphics 620                                                                | 28        | 3.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 28        | 3.27%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 28        | 3.27%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 24        | 2.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 23        | 2.69%   |
| Intel HD Graphics 620                                                                 | 20        | 2.34%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 20        | 2.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 20        | 2.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 18        | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 16        | 1.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 16        | 1.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 16        | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 15        | 1.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 14        | 1.64%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 12        | 1.4%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 10        | 1.17%   |
| Intel HD Graphics 630                                                                 | 10        | 1.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 1.17%   |
| AMD Rembrandt [Radeon 680M]                                                           | 10        | 1.17%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 9         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 9         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 8         | 0.94%   |
| Intel HD Graphics 530                                                                 | 8         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 0.94%   |
| Nvidia TU117M [GeForce MX450]                                                         | 7         | 0.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 7         | 0.82%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 7         | 0.82%   |
| Intel HD Graphics 5500                                                                | 7         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 6         | 0.7%    |
| Intel Iris Plus Graphics G7                                                           | 6         | 0.7%    |
| AMD Barcelo                                                                           | 6         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 5         | 0.58%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 5         | 0.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 0.58%   |
| Intel HD Graphics 500                                                                 | 5         | 0.58%   |
| Intel GeminiLake [UHD Graphics 605]                                                   | 5         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 264       | 41.97%  |
| Intel + Nvidia | 153       | 24.32%  |
| 1 x AMD        | 117       | 18.6%   |
| AMD + Nvidia   | 32        | 5.09%   |
| Intel + AMD    | 27        | 4.29%   |
| 1 x Nvidia     | 22        | 3.5%    |
| 2 x AMD        | 9         | 1.43%   |
| Other          | 3         | 0.48%   |
| 2 x Nvidia     | 1         | 0.16%   |
| 1 x Zhaoxin    | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 474       | 75%     |
| Proprietary | 146       | 23.1%   |
| Unknown     | 12        | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 456       | 71.92%  |
| 0.01-0.5   | 72        | 11.36%  |
| 1.01-2.0   | 42        | 6.62%   |
| 3.01-4.0   | 22        | 3.47%   |
| 0.51-1.0   | 21        | 3.31%   |
| 5.01-6.0   | 10        | 1.58%   |
| 7.01-8.0   | 9         | 1.42%   |
| 8.01-16.0  | 2         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 129       | 16.84%  |
| AU Optronics            | 123       | 16.06%  |
| Chimei Innolux          | 115       | 15.01%  |
| LG Display              | 99        | 12.92%  |
| Samsung Electronics     | 70        | 9.14%   |
| Goldstar                | 27        | 3.52%   |
| Dell                    | 25        | 3.26%   |
| Sharp                   | 24        | 3.13%   |
| Hewlett-Packard         | 17        | 2.22%   |
| Apple                   | 13        | 1.7%    |
| CSO                     | 12        | 1.57%   |
| Lenovo                  | 10        | 1.31%   |
| Philips                 | 9         | 1.17%   |
| Chi Mei Optoelectronics | 9         | 1.17%   |
| Acer                    | 9         | 1.17%   |
| InfoVision              | 8         | 1.04%   |
| PANDA                   | 7         | 0.91%   |
| BenQ                    | 7         | 0.91%   |
| ASUSTek Computer        | 7         | 0.91%   |
| Ancor Communications    | 5         | 0.65%   |
| AOC                     | 4         | 0.52%   |
| Sceptre Tech            | 3         | 0.39%   |
| Iiyama                  | 3         | 0.39%   |
| Sony                    | 2         | 0.26%   |
| SLD                     | 2         | 0.26%   |
| IBM                     | 2         | 0.26%   |
| HUAWEI                  | 2         | 0.26%   |
| HKC                     | 2         | 0.26%   |
| Vizio                   | 1         | 0.13%   |
| ViewSonic               | 1         | 0.13%   |
| TMX                     | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| NEC Computers           | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| Medion                  | 1         | 0.13%   |
| LG Philips              | 1         | 0.13%   |
| KIG                     | 1         | 0.13%   |
| Insignia                | 1         | 0.13%   |
| Grundig                 | 1         | 0.13%   |
| GreenWood               | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 9         | 1.16%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 9         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 8         | 1.03%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 8         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 6         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 6         | 0.77%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch     | 4         | 0.51%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 4         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 4         | 0.51%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 4         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 4         | 0.51%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                     | 4         | 0.51%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                     | 4         | 0.51%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 4         | 0.51%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 3         | 0.39%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch              | 3         | 0.39%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 3         | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 3         | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 3         | 0.39%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                     | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch          | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch          | 3         | 0.39%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                     | 3         | 0.39%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                     | 3         | 0.39%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 3         | 0.39%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO559C 1920x1080 309x174mm 14.0-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO409D 1920x1080 382x215mm 17.3-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.39%   |
| Acer G237HL ACR03DF 1920x1080 510x290mm 23.1-inch                         | 3         | 0.39%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                      | 2         | 0.26%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch                   | 2         | 0.26%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch            | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 359       | 51.43%  |
| 1366x768 (WXGA)    | 131       | 18.77%  |
| 2560x1440 (QHD)    | 36        | 5.16%   |
| 3840x2160 (4K)     | 29        | 4.15%   |
| 1920x1200 (WUXGA)  | 29        | 4.15%   |
| 1600x900 (HD+)     | 28        | 4.01%   |
| 2560x1600          | 19        | 2.72%   |
| 2880x1800          | 13        | 1.86%   |
| 1680x1050 (WSXGA+) | 7         | 1%      |
| 3440x1440          | 5         | 0.72%   |
| 2560x1080          | 5         | 0.72%   |
| 1440x900 (WXGA+)   | 5         | 0.72%   |
| 2240x1400          | 4         | 0.57%   |
| 2160x1440          | 4         | 0.57%   |
| 1280x800 (WXGA)    | 4         | 0.57%   |
| 2256x1504          | 3         | 0.43%   |
| 1280x1024 (SXGA)   | 3         | 0.43%   |
| 3840x2400          | 2         | 0.29%   |
| 3840x1080          | 2         | 0.29%   |
| 3072x1920          | 2         | 0.29%   |
| 2520x1680          | 2         | 0.29%   |
| 1024x768 (XGA)     | 2         | 0.29%   |
| 3200x1800 (QHD+)   | 1         | 0.14%   |
| 2160x1350          | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1600x1200          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 298       | 38.95%  |
| 14      | 102       | 13.33%  |
| 13      | 83        | 10.85%  |
| 17      | 62        | 8.1%    |
| 27      | 37        | 4.84%   |
| 24      | 35        | 4.58%   |
| 16      | 33        | 4.31%   |
| 23      | 24        | 3.14%   |
| 21      | 17        | 2.22%   |
| 34      | 10        | 1.31%   |
| 12      | 10        | 1.31%   |
| 11      | 9         | 1.18%   |
| 31      | 8         | 1.05%   |
| 22      | 5         | 0.65%   |
| 54      | 4         | 0.52%   |
| 20      | 4         | 0.52%   |
| 19      | 3         | 0.39%   |
| 72      | 2         | 0.26%   |
| 49      | 2         | 0.26%   |
| 25      | 2         | 0.26%   |
| 18      | 2         | 0.26%   |
| 84      | 1         | 0.13%   |
| 78      | 1         | 0.13%   |
| 65      | 1         | 0.13%   |
| 63      | 1         | 0.13%   |
| 60      | 1         | 0.13%   |
| 48      | 1         | 0.13%   |
| 42      | 1         | 0.13%   |
| 40      | 1         | 0.13%   |
| 32      | 1         | 0.13%   |
| 28      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 453       | 60%     |
| 501-600     | 89        | 11.79%  |
| 351-400     | 81        | 10.73%  |
| 201-300     | 64        | 8.48%   |
| 401-500     | 29        | 3.84%   |
| 601-700     | 12        | 1.59%   |
| 701-800     | 10        | 1.32%   |
| 1001-1500   | 10        | 1.32%   |
| 1501-2000   | 4         | 0.53%   |
| 801-900     | 1         | 0.13%   |
| 901-1000    | 1         | 0.13%   |
| Unknown     | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 531       | 81.69%  |
| 16/10   | 89        | 13.69%  |
| 21/9    | 11        | 1.69%   |
| 3/2     | 9         | 1.38%   |
| 5/4     | 3         | 0.46%   |
| 4/3     | 3         | 0.46%   |
| 32/9    | 2         | 0.31%   |
| 6/5     | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 305       | 40.24%  |
| 81-90          | 154       | 20.32%  |
| 201-250        | 67        | 8.84%   |
| 121-130        | 58        | 7.65%   |
| 301-350        | 38        | 5.01%   |
| 71-80          | 32        | 4.22%   |
| 111-120        | 25        | 3.3%    |
| 351-500        | 17        | 2.24%   |
| More than 1000 | 12        | 1.58%   |
| 61-70          | 9         | 1.19%   |
| 51-60          | 9         | 1.19%   |
| 151-200        | 9         | 1.19%   |
| 251-300        | 8         | 1.06%   |
| 501-1000       | 4         | 0.53%   |
| 141-150        | 3         | 0.4%    |
| 131-140        | 3         | 0.4%    |
| 91-100         | 3         | 0.4%    |
| 41-50          | 1         | 0.13%   |
| Unknown        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 348       | 46.9%   |
| 101-120       | 160       | 21.56%  |
| 51-100        | 109       | 14.69%  |
| 161-240       | 92        | 12.4%   |
| More than 240 | 22        | 2.96%   |
| 1-50          | 10        | 1.35%   |
| Unknown       | 1         | 0.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 473       | 74.37%  |
| 2     | 120       | 18.87%  |
| 3     | 26        | 4.09%   |
| 0     | 13        | 2.04%   |
| 4     | 4         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 361       | 36.5%   |
| Realtek Semiconductor             | 350       | 35.39%  |
| Qualcomm Atheros                  | 98        | 9.91%   |
| MediaTek                          | 48        | 4.85%   |
| Broadcom                          | 42        | 4.25%   |
| ASIX Electronics                  | 10        | 1.01%   |
| TP-Link                           | 8         | 0.81%   |
| Sierra Wireless                   | 6         | 0.61%   |
| Samsung Electronics               | 6         | 0.61%   |
| Lenovo                            | 6         | 0.61%   |
| Broadcom Limited                  | 6         | 0.61%   |
| Ralink Technology                 | 4         | 0.4%    |
| Qualcomm                          | 4         | 0.4%    |
| Marvell Technology Group          | 4         | 0.4%    |
| Ralink                            | 3         | 0.3%    |
| Hewlett-Packard                   | 3         | 0.3%    |
| DisplayLink                       | 3         | 0.3%    |
| Dell                              | 3         | 0.3%    |
| Xiaomi                            | 2         | 0.2%    |
| Nvidia                            | 2         | 0.2%    |
| JMicron Technology                | 2         | 0.2%    |
| Huawei Technologies               | 2         | 0.2%    |
| Google                            | 2         | 0.2%    |
| Ericsson Business Mobile Networks | 2         | 0.2%    |
| Apple                             | 2         | 0.2%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.1%    |
| Shenzhen Goodix Technology        | 1         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.1%    |
| NIIMBOT                           | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |
| D-Link System                     | 1         | 0.1%    |
| Belkin Components                 | 1         | 0.1%    |
| ASUSTek Computer                  | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 199       | 16.81%  |
| Intel Wi-Fi 6 AX201                                               | 43        | 3.63%   |
| Intel Wi-Fi 6 AX200                                               | 41        | 3.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 39        | 3.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 39        | 3.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 36        | 3.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 2.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 2.7%    |
| Intel Wireless 8265 / 8275                                        | 28        | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 2.11%   |
| Intel Wireless 7260                                               | 21        | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 17        | 1.44%   |
| Intel Wireless 8260                                               | 16        | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 1.35%   |
| Intel Wireless 7265                                               | 15        | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 15        | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 9         | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                      | 8         | 0.68%   |
| Intel Wireless 3165                                               | 8         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 0.59%   |
| Intel Ethernet Connection (16) I219-LM                            | 7         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.59%   |
| Intel Centrino Advanced-N 6235                                    | 7         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 0.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 6         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 346       | 52.5%   |
| Realtek Semiconductor             | 119       | 18.06%  |
| Qualcomm Atheros                  | 78        | 11.84%  |
| MediaTek                          | 48        | 7.28%   |
| Broadcom                          | 33        | 5.01%   |
| Sierra Wireless                   | 6         | 0.91%   |
| TP-Link                           | 4         | 0.61%   |
| Ralink Technology                 | 4         | 0.61%   |
| Qualcomm                          | 4         | 0.61%   |
| Broadcom Limited                  | 4         | 0.61%   |
| Ralink                            | 3         | 0.46%   |
| Dell                              | 3         | 0.46%   |
| Ericsson Business Mobile Networks | 2         | 0.3%    |
| Fibocom                           | 1         | 0.15%   |
| Edimax Technology                 | 1         | 0.15%   |
| D-Link System                     | 1         | 0.15%   |
| Belkin Components                 | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 43        | 6.45%   |
| Intel Wi-Fi 6 AX200                                            | 41        | 6.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 39        | 5.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 39        | 5.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 32        | 4.8%    |
| Intel Wireless 8265 / 8275                                     | 28        | 4.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 3.75%   |
| Intel Wireless 7260                                            | 21        | 3.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 2.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18        | 2.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 17        | 2.55%   |
| Intel Wireless 8260                                            | 16        | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 16        | 2.4%    |
| Intel Wireless 7265                                            | 15        | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13        | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 9         | 1.35%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 1.2%    |
| Intel Wireless 3165                                            | 8         | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 7         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 1.05%   |
| Intel Centrino Advanced-N 6235                                 | 7         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 0.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 5         | 0.75%   |
| Intel Wireless 3160                                            | 5         | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 0.75%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.6%    |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 286       | 57.78%  |
| Intel                      | 124       | 25.05%  |
| Qualcomm Atheros           | 23        | 4.65%   |
| Broadcom                   | 13        | 2.63%   |
| ASIX Electronics           | 10        | 2.02%   |
| Samsung Electronics        | 6         | 1.21%   |
| Lenovo                     | 6         | 1.21%   |
| TP-Link                    | 4         | 0.81%   |
| Marvell Technology Group   | 4         | 0.81%   |
| DisplayLink                | 3         | 0.61%   |
| Xiaomi                     | 2         | 0.4%    |
| Nvidia                     | 2         | 0.4%    |
| JMicron Technology         | 2         | 0.4%    |
| Huawei Technologies        | 2         | 0.4%    |
| Google                     | 2         | 0.4%    |
| Broadcom Limited           | 2         | 0.4%    |
| Apple                      | 2         | 0.4%    |
| ZTE WCDMA Technologies MSM | 1         | 0.2%    |
| Hewlett-Packard            | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 199       | 38.94%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 36        | 7.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 6.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 4.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.96%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 1.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 1.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 1.57%   |
| Intel Ethernet Connection (16) I219-LM                            | 7         | 1.37%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.17%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 1.17%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.98%   |
| Realtek Killer E3000 2.5GbE Controller                            | 5         | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.59%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.59%   |
| DisplayLink USB3.0 Dual Video Dock                                | 3         | 0.59%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 3         | 0.59%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.39%   |
| Lenovo USB-C to LAN                                               | 2         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.39%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 625       | 56.97%  |
| Ethernet | 466       | 42.48%  |
| Modem    | 3         | 0.27%   |
| Unknown  | 3         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 540       | 81.08%  |
| Ethernet | 126       | 18.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 419       | 66.72%  |
| 1     | 187       | 29.78%  |
| 0     | 16        | 2.55%   |
| 3     | 5         | 0.8%    |
| 4     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 451       | 71.47%  |
| Yes  | 180       | 28.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 298       | 53.6%   |
| Realtek Semiconductor           | 69        | 12.41%  |
| Qualcomm Atheros Communications | 40        | 7.19%   |
| IMC Networks                    | 32        | 5.76%   |
| Foxconn / Hon Hai               | 25        | 4.5%    |
| Lite-On Technology              | 23        | 4.14%   |
| Broadcom                        | 23        | 4.14%   |
| Apple                           | 9         | 1.62%   |
| Realtek                         | 6         | 1.08%   |
| Dell                            | 6         | 1.08%   |
| Toshiba                         | 5         | 0.9%    |
| Cambridge Silicon Radio         | 4         | 0.72%   |
| ASUSTek Computer                | 3         | 0.54%   |
| TP-Link                         | 2         | 0.36%   |
| Ralink                          | 2         | 0.36%   |
| Hewlett-Packard                 | 2         | 0.36%   |
| USI                             | 1         | 0.18%   |
| SINO WEALTH                     | 1         | 0.18%   |
| MediaTek                        | 1         | 0.18%   |
| Foxconn International           | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 86        | 15.47%  |
| Intel AX201 Bluetooth                               | 74        | 13.31%  |
| Realtek Bluetooth Radio                             | 56        | 10.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 40        | 7.19%   |
| Intel AX200 Bluetooth                               | 39        | 7.01%   |
| Intel Bluetooth Device                              | 34        | 6.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 3.24%   |
| IMC Networks Wireless_Device                        | 16        | 2.88%   |
| Lite-On Wireless_Device                             | 14        | 2.52%   |
| Intel AX210 Bluetooth                               | 12        | 2.16%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 2.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 1.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 1.8%    |
| IMC Networks Bluetooth Radio                        | 9         | 1.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.44%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.26%   |
| Broadcom HP Portable SoftSailing                    | 7         | 1.26%   |
| Apple Bluetooth Host Controller                     | 7         | 1.26%   |
| Realtek Bluetooth Radio                             | 6         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.08%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.54%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.54%   |
| IMC Networks Bluetooth Device                       | 3         | 0.54%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 3         | 0.54%   |
| TP-Link UB500 Adapter                               | 2         | 0.36%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.36%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.36%   |
| Lite-On Bluetooth Device                            | 2         | 0.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.36%   |
| IMC Networks Bluetooth                              | 2         | 0.36%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.36%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.36%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 0.36%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.36%   |
| USI Bluetooth Device                                | 1         | 0.18%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.18%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 470       | 56.9%   |
| AMD                       | 163       | 19.73%  |
| Nvidia                    | 119       | 14.41%  |
| C-Media Electronics       | 11        | 1.33%   |
| Lenovo                    | 7         | 0.85%   |
| Hewlett-Packard           | 6         | 0.73%   |
| GN Netcom                 | 6         | 0.73%   |
| Realtek Semiconductor     | 5         | 0.61%   |
| JMTek                     | 5         | 0.61%   |
| Razer USA                 | 3         | 0.36%   |
| Texas Instruments         | 2         | 0.24%   |
| Sennheiser Communications | 2         | 0.24%   |
| Logitech                  | 2         | 0.24%   |
| Focusrite-Novation        | 2         | 0.24%   |
| Corsair                   | 2         | 0.24%   |
| Apple                     | 2         | 0.24%   |
| ZOOM                      | 1         | 0.12%   |
| Zhaoxin                   | 1         | 0.12%   |
| TerraTec Electronic       | 1         | 0.12%   |
| Spreadtrum Communications | 1         | 0.12%   |
| Sony                      | 1         | 0.12%   |
| Silicon Motion            | 1         | 0.12%   |
| Princeton Technology      | 1         | 0.12%   |
| Plantronics               | 1         | 0.12%   |
| OS AS700 USB              | 1         | 0.12%   |
| KORG                      | 1         | 0.12%   |
| Fujitsu                   | 1         | 0.12%   |
| DisplayLink               | 1         | 0.12%   |
| Cyber Acoustics           | 1         | 0.12%   |
| Creative Technology       | 1         | 0.12%   |
| Conexant Systems          | 1         | 0.12%   |
| Blue Microphones          | 1         | 0.12%   |
| ASUSTek Computer          | 1         | 0.12%   |
| Arturia                   | 1         | 0.12%   |
| Alesis                    | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 122       | 12.16%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 81        | 8.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 71        | 7.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 60        | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 60        | 5.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 46        | 4.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 32        | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 29        | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 2.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 1.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 17        | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 1.6%    |
| Intel Comet Lake PCH cAVS                                                  | 16        | 1.6%    |
| Nvidia GA106 High Definition Audio Controller                              | 14        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 14        | 1.4%    |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 1.3%    |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 1.2%    |
| Intel CM238 HD Audio Controller                                            | 11        | 1.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 1.1%    |
| AMD FCH Azalia Controller                                                  | 11        | 1.1%    |
| Nvidia Audio device                                                        | 10        | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 10        | 1%      |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 1%      |
| Intel 8 Series HD Audio Controller                                         | 10        | 1%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 1%      |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 0.9%    |
| Intel Broadwell-U Audio Controller                                         | 9         | 0.9%    |
| Nvidia GK107 HDMI Audio Controller                                         | 8         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 0.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.6%    |
| Realtek Semiconductor USB Audio                                            | 5         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 168       | 30.49%  |
| SK hynix                           | 106       | 19.24%  |
| Micron Technology                  | 71        | 12.89%  |
| Crucial                            | 49        | 8.89%   |
| Kingston                           | 38        | 6.9%    |
| A-DATA Technology                  | 16        | 2.9%    |
| Unknown (ABCD)                     | 14        | 2.54%   |
| Unknown                            | 13        | 2.36%   |
| Elpida                             | 9         | 1.63%   |
| Unknown                            | 7         | 1.27%   |
| Ramaxel Technology                 | 6         | 1.09%   |
| Nanya Technology                   | 6         | 1.09%   |
| Corsair                            | 6         | 1.09%   |
| Transcend                          | 4         | 0.73%   |
| Smart                              | 4         | 0.73%   |
| Wilk                               | 3         | 0.54%   |
| Team                               | 2         | 0.36%   |
| Silicon Power                      | 2         | 0.36%   |
| GOODRAM                            | 2         | 0.36%   |
| G.Skill                            | 2         | 0.36%   |
| ff                                 | 2         | 0.36%   |
| 4ea5                               | 2         | 0.36%   |
| Unknown (8A02)                     | 1         | 0.18%   |
| Unknown (08C8)                     | 1         | 0.18%   |
| Teikon                             | 1         | 0.18%   |
| Super Talent                       | 1         | 0.18%   |
| Shenzhen Zhongteng                 | 1         | 0.18%   |
| Shenzhen WODPOSIT                  | 1         | 0.18%   |
| SHARETRONIC                        | 1         | 0.18%   |
| Qimonda                            | 1         | 0.18%   |
| Patriot                            | 1         | 0.18%   |
| Lexar                              | 1         | 0.18%   |
| Kimtigo Semiconductor (HK) Limited | 1         | 0.18%   |
| Imation                            | 1         | 0.18%   |
| Goldkey                            | 1         | 0.18%   |
| Gold Key                           | 1         | 0.18%   |
| Essencore Limited                  | 1         | 0.18%   |
| Atermiter                          | 1         | 0.18%   |
| ASint Technology                   | 1         | 0.18%   |
| Apacer                             | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 2.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 1.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 1.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 1.23%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 7         | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 1.23%   |
| Unknown                                                          | 7         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 1.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.88%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.7%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.7%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.7%    |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 4         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.7%    |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 4         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.53%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.53%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 0.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 3         | 0.53%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.53%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.53%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 275       | 61.66%  |
| DDR3    | 94        | 21.08%  |
| LPDDR4  | 35        | 7.85%   |
| DDR5    | 18        | 4.04%   |
| LPDDR5  | 10        | 2.24%   |
| LPDDR3  | 5         | 1.12%   |
| DDR2    | 5         | 1.12%   |
| SDRAM   | 3         | 0.67%   |
| Unknown | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 390       | 85.15%  |
| Row Of Chips | 57        | 12.45%  |
| Chip         | 5         | 1.09%   |
| Unknown      | 4         | 0.87%   |
| DIMM         | 2         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 220       | 44.99%  |
| 16384 | 111       | 22.7%   |
| 4096  | 107       | 21.88%  |
| 32768 | 23        | 4.7%    |
| 2048  | 23        | 4.7%    |
| 1024  | 5         | 1.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 168       | 35.82%  |
| 2667    | 84        | 17.91%  |
| 1600    | 71        | 15.14%  |
| 2400    | 40        | 8.53%   |
| 4800    | 17        | 3.62%   |
| 1333    | 15        | 3.2%    |
| 4267    | 13        | 2.77%   |
| 6400    | 9         | 1.92%   |
| 2133    | 9         | 1.92%   |
| 1334    | 9         | 1.92%   |
| 1867    | 7         | 1.49%   |
| 667     | 5         | 1.07%   |
| 4266    | 4         | 0.85%   |
| 3266    | 4         | 0.85%   |
| Unknown | 3         | 0.64%   |
| 8400    | 2         | 0.43%   |
| 2933    | 2         | 0.43%   |
| 2048    | 2         | 0.43%   |
| 7500    | 1         | 0.21%   |
| 5600    | 1         | 0.21%   |
| 4199    | 1         | 0.21%   |
| 2666    | 1         | 0.21%   |
| 1067    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 40%     |
| Hewlett-Packard    | 1         | 20%     |
| Canon              | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L3110 Series         | 1         | 20%     |
| Seiko Epson ET-2700 Series       | 1         | 20%     |
| HP LaserJet Professional P 1102w | 1         | 20%     |
| Canon iP2600 series              | 1         | 20%     |
| Brother HL-2230 series           | 1         | 20%     |

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
| Chicony Electronics                    | 120       | 20.24%  |
| IMC Networks                           | 70        | 11.8%   |
| Microdia                               | 67        | 11.3%   |
| Bison Electronics                      | 48        | 8.09%   |
| Quanta                                 | 47        | 7.93%   |
| Realtek Semiconductor                  | 44        | 7.42%   |
| Sunplus Innovation Technology          | 28        | 4.72%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.88%   |
| Acer                                   | 21        | 3.54%   |
| Syntek                                 | 16        | 2.7%    |
| Logitech                               | 16        | 2.7%    |
| Luxvisions Innotech Limited            | 14        | 2.36%   |
| Lite-On Technology                     | 12        | 2.02%   |
| Silicon Motion                         | 6         | 1.01%   |
| Apple                                  | 6         | 1.01%   |
| Y Media                                | 5         | 0.84%   |
| Suyin                                  | 4         | 0.67%   |
| Sonix Technology                       | 4         | 0.67%   |
| Samsung Electronics                    | 4         | 0.67%   |
| icSpring                               | 4         | 0.67%   |
| Alcor Micro                            | 3         | 0.51%   |
| Z-Star Microelectronics                | 2         | 0.34%   |
| SunplusIT                              | 2         | 0.34%   |
| Lenovo                                 | 2         | 0.34%   |
| Importek                               | 2         | 0.34%   |
| GEMBIRD                                | 2         | 0.34%   |
| YGTek                                  | 1         | 0.17%   |
| Xiaomi                                 | 1         | 0.17%   |
| USB Camera CS                          | 1         | 0.17%   |
| STEREOLABS                             | 1         | 0.17%   |
| SN0002                                 | 1         | 0.17%   |
| ShineTech                              | 1         | 0.17%   |
| Primax Electronics                     | 1         | 0.17%   |
| Pixart Imaging                         | 1         | 0.17%   |
| Novatek Microelectronics               | 1         | 0.17%   |
| Linux Foundation                       | 1         | 0.17%   |
| LG Electronics                         | 1         | 0.17%   |
| Huawei Technologies                    | 1         | 0.17%   |
| HRY                                    | 1         | 0.17%   |
| Goodong Industry                       | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                   | 37        | 6.23%   |
| Chicony Integrated Camera                                       | 37        | 6.23%   |
| IMC Networks Integrated Camera                                  | 27        | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 17        | 2.86%   |
| Realtek Integrated_Webcam_HD                                    | 16        | 2.69%   |
| Bison Integrated Camera                                         | 16        | 2.69%   |
| Chicony HD User Facing                                          | 12        | 2.02%   |
| Sunplus Integrated_Webcam_HD                                    | 11        | 1.85%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.85%   |
| Chicony HD Webcam                                               | 11        | 1.85%   |
| Syntek Integrated Camera                                        | 10        | 1.68%   |
| Quanta HD User Facing                                           | 10        | 1.68%   |
| Acer Integrated Camera                                          | 10        | 1.68%   |
| Microdia Integrated_Webcam_FHD                                  | 8         | 1.35%   |
| Chicony HP HD Camera                                            | 8         | 1.35%   |
| Bison HD Webcam                                                 | 7         | 1.18%   |
| IMC Networks HD Camera                                          | 6         | 1.01%   |
| Chicony Integrated Camera (1280x720@30)                         | 6         | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 1.01%   |
| Y Media USB Camera                                              | 5         | 0.84%   |
| Quanta HP Wide Vision HD Camera                                 | 5         | 0.84%   |
| Quanta ACER HD User Facing                                      | 5         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 5         | 0.84%   |
| Chicony HP Wide Vision HD Camera                                | 5         | 0.84%   |
| Chicony HP TrueVision HD Camera                                 | 5         | 0.84%   |
| Bison BisonCam,NB Pro                                           | 5         | 0.84%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 4         | 0.67%   |
| Realtek Integrated Webcam                                       | 4         | 0.67%   |
| Quanta HP HD Camera                                             | 4         | 0.67%   |
| Quanta HD Webcam                                                | 4         | 0.67%   |
| Microdia Webcam Vitade AF                                       | 4         | 0.67%   |
| Luxvisions Innotech Limited Integrated Camera                   | 4         | 0.67%   |
| Logitech C922 Pro Stream Webcam                                 | 4         | 0.67%   |
| Lite-On Integrated Camera                                       | 4         | 0.67%   |
| Lite-On HP HD Camera                                            | 4         | 0.67%   |
| icSpring camera                                                 | 4         | 0.67%   |
| Chicony USB2.0 Camera                                           | 4         | 0.67%   |
| Chicony HP Truevision HD                                        | 4         | 0.67%   |
| Chicony FJ Camera                                               | 4         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 36        | 28.57%  |
| Shenzhen Goodix Technology         | 34        | 26.98%  |
| Validity Sensors                   | 33        | 26.19%  |
| Elan Microelectronics              | 10        | 7.94%   |
| Upek                               | 4         | 3.17%   |
| LighTuning Technology              | 3         | 2.38%   |
| AuthenTec                          | 3         | 2.38%   |
| STMicroelectronics                 | 1         | 0.79%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.79%   |
| Focal-systems.Corp                 | 1         | 0.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 27        | 21.43%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 4.76%   |
| Elan ELAN:ARM-M4                                                           | 6         | 4.76%   |
| Validity Sensors VFS491                                                    | 5         | 3.97%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 3.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.17%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.17%   |
| Synaptics UWP WBDI Device                                                  | 3         | 2.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.38%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.59%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.59%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.59%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.59%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.59%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.59%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.79%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.79%   |
| Synaptics WBDI                                                             | 1         | 0.79%   |
| Synaptics UWP WBDI                                                         | 1         | 0.79%   |
| Synaptics TouchPad                                                         | 1         | 0.79%   |
| Synaptics  WBDI                                                            | 1         | 0.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.79%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.79%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.79%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.79%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.79%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.79%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.79%   |
| AuthenTec AES2810                                                          | 1         | 0.79%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 25        | 43.1%   |
| Alcor Micro           | 24        | 41.38%  |
| Upek                  | 4         | 6.9%    |
| O2 Micro              | 1         | 1.72%   |
| Lenovo                | 1         | 1.72%   |
| Clay Logic            | 1         | 1.72%   |
| Bit4id                | 1         | 1.72%   |
| Advanced Card Systems | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 41.38%  |
| Broadcom 58200                                                               | 9         | 15.52%  |
| Broadcom 5880                                                                | 8         | 13.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 8.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 6.9%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.72%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.72%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.72%   |
| Bit4id miniLector EVO                                                        | 1         | 1.72%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 389       | 60.5%   |
| 1     | 194       | 30.17%  |
| 2     | 54        | 8.4%    |
| 3     | 4         | 0.62%   |
| 9     | 1         | 0.16%   |
| 4     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 125       | 40.58%  |
| Chipcard                 | 52        | 16.88%  |
| Graphics card            | 35        | 11.36%  |
| Net/wireless             | 22        | 7.14%   |
| Camera                   | 22        | 7.14%   |
| Multimedia controller    | 20        | 6.49%   |
| Bluetooth                | 10        | 3.25%   |
| Sound                    | 6         | 1.95%   |
| Storage                  | 4         | 1.3%    |
| Communication controller | 4         | 1.3%    |
| Network                  | 3         | 0.97%   |
| Net/ethernet             | 2         | 0.65%   |
| Card reader              | 2         | 0.65%   |
| Modem                    | 1         | 0.32%   |

