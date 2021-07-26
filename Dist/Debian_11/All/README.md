Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 104       | 37.55%  |
| 5.10.0-7-amd64                 | 89        | 32.13%  |
| 5.10.0-6-amd64                 | 37        | 13.36%  |
| 5.11.22-1-pve                  | 4         | 1.44%   |
| 5.12.0-19.3-liquorix-amd64     | 2         | 0.72%   |
| 5.11.22-2-pve                  | 2         | 0.72%   |
| 5.10.0-8-686                   | 2         | 0.72%   |
| 5.10-sunxi64                   | 2         | 0.72%   |
| 5.9.0-arm-64                   | 1         | 0.36%   |
| 5.8.0-3-amd64                  | 1         | 0.36%   |
| 5.4.18-sunxi64                 | 1         | 0.36%   |
| 5.4.0-73-generic               | 1         | 0.36%   |
| 5.13.4-e5520                   | 1         | 0.36%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.36%   |
| 5.12.4                         | 1         | 0.36%   |
| 5.12.10                        | 1         | 0.36%   |
| 5.12.1                         | 1         | 0.36%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.36%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.36%   |
| 5.11.9+                        | 1         | 0.36%   |
| 5.11.15-terranz                | 1         | 0.36%   |
| 5.11.15-051115-generic         | 1         | 0.36%   |
| 5.11.14                        | 1         | 0.36%   |
| 5.11.0-rc6                     | 1         | 0.36%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.36%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.36%   |
| 5.10.40-ismynik                | 1         | 0.36%   |
| 5.10.35-rockchip64             | 1         | 0.36%   |
| 5.10.21-sunxi                  | 1         | 0.36%   |
| 5.10.12-sunxi                  | 1         | 0.36%   |
| 5.10.0-io7-amd64               | 1         | 0.36%   |
| 5.10.0-8-armmp                 | 1         | 0.36%   |
| 5.10.0-7-686-pae               | 1         | 0.36%   |
| 5.10.0-6-rt-amd64              | 1         | 0.36%   |
| 5.10.0-6-686                   | 1         | 0.36%   |
| 5.10.0-5-amd64                 | 1         | 0.36%   |
| 5.10.0-4-amd64                 | 1         | 0.36%   |
| 5.10.0-3-amd64                 | 1         | 0.36%   |
| 5.10.0-2-amd64                 | 1         | 0.36%   |
| 4.19.181-z580322               | 1         | 0.36%   |
| 4.19.0-16-amd64                | 1         | 0.36%   |
| 4.19.0-16-686-pae              | 1         | 0.36%   |
| 4.19.0-14-amd64                | 1         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 233       | 86.94%  |
| 5.11.22  | 6         | 2.24%   |
| 5.12.0   | 3         | 1.12%   |
| 5.11.0   | 3         | 1.12%   |
| 4.19.0   | 3         | 1.12%   |
| 5.11.15  | 2         | 0.75%   |
| 5.10     | 2         | 0.75%   |
| 5.9.0    | 1         | 0.37%   |
| 5.8.0    | 1         | 0.37%   |
| 5.4.18   | 1         | 0.37%   |
| 5.4.0    | 1         | 0.37%   |
| 5.13.4   | 1         | 0.37%   |
| 5.13.0   | 1         | 0.37%   |
| 5.12.4   | 1         | 0.37%   |
| 5.12.10  | 1         | 0.37%   |
| 5.12.1   | 1         | 0.37%   |
| 5.11.9   | 1         | 0.37%   |
| 5.11.14  | 1         | 0.37%   |
| 5.10.40  | 1         | 0.37%   |
| 5.10.35  | 1         | 0.37%   |
| 5.10.21  | 1         | 0.37%   |
| 5.10.12  | 1         | 0.37%   |
| 4.19.181 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 236       | 88.39%  |
| 5.11    | 13        | 4.87%   |
| 5.12    | 6         | 2.25%   |
| 4.19    | 4         | 1.5%    |
| 5.4     | 2         | 0.75%   |
| 5.13    | 2         | 0.75%   |
| 5       | 2         | 0.75%   |
| 5.9     | 1         | 0.37%   |
| 5.8     | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 255       | 95.51%  |
| i686    | 5         | 1.87%   |
| aarch64 | 5         | 1.87%   |
| armv7l  | 2         | 0.75%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 79        | 29.26%  |
| KDE5             | 56        | 20.74%  |
| XFCE             | 29        | 10.74%  |
| MATE             | 26        | 9.63%   |
| Unknown          | 23        | 8.52%   |
| i3               | 10        | 3.7%    |
| KDE              | 9         | 3.33%   |
| LXQt             | 7         | 2.59%   |
| Cinnamon         | 6         | 2.22%   |
| X-Cinnamon       | 5         | 1.85%   |
| LXDE             | 4         | 1.48%   |
| lightdm-xsession | 4         | 1.48%   |
| GNOME Flashback  | 3         | 1.11%   |
| sway             | 2         | 0.74%   |
| openbox          | 2         | 0.74%   |
| Trinity          | 1         | 0.37%   |
| GNUstep          | 1         | 0.37%   |
| default          | 1         | 0.37%   |
| Budgie           | 1         | 0.37%   |
| awesome          | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 173       | 64.31%  |
| Wayland | 60        | 22.3%   |
| Tty     | 26        | 9.67%   |
| Unknown | 10        | 3.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| TDM     | 77        | 28.62%  |
| GDM     | 75        | 27.88%  |
| SDDM    | 54        | 20.07%  |
| Unknown | 51        | 18.96%  |
| LightDM | 8         | 2.97%   |
| XDM     | 2         | 0.74%   |
| SLiM    | 2         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 116       | 43.28%  |
| fr_FR   | 19        | 7.09%   |
| en_GB   | 19        | 7.09%   |
| de_DE   | 16        | 5.97%   |
| ru_RU   | 10        | 3.73%   |
| es_ES   | 9         | 3.36%   |
| pt_BR   | 8         | 2.99%   |
| pl_PL   | 8         | 2.99%   |
| C       | 6         | 2.24%   |
| en_IN   | 5         | 1.87%   |
| Unknown | 5         | 1.87%   |
| it_IT   | 4         | 1.49%   |
| en_CA   | 4         | 1.49%   |
| tr_TR   | 3         | 1.12%   |
| nl_BE   | 3         | 1.12%   |
| hu_HU   | 3         | 1.12%   |
| en_AU   | 3         | 1.12%   |
| de_CH   | 3         | 1.12%   |
| ru_UA   | 2         | 0.75%   |
| ro_RO   | 2         | 0.75%   |
| pt_PT   | 2         | 0.75%   |
| ja_JP   | 2         | 0.75%   |
| en_SG   | 2         | 0.75%   |
| uk_UA   | 1         | 0.37%   |
| sv_SE   | 1         | 0.37%   |
| sr_RS   | 1         | 0.37%   |
| sk_SK   | 1         | 0.37%   |
| hr_HR   | 1         | 0.37%   |
| fi_FI   | 1         | 0.37%   |
| es_MX   | 1         | 0.37%   |
| es_EC   | 1         | 0.37%   |
| es_CO   | 1         | 0.37%   |
| es_AR   | 1         | 0.37%   |
| en_PH   | 1         | 0.37%   |
| en_HK   | 1         | 0.37%   |
| cs_CZ   | 1         | 0.37%   |
| ca_ES   | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 170       | 63.2%   |
| BIOS | 99        | 36.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 221       | 82.77%  |
| Btrfs   | 18        | 6.74%   |
| Overlay | 11        | 4.12%   |
| Zfs     | 7         | 2.62%   |
| Xfs     | 4         | 1.5%    |
| Ext3    | 4         | 1.5%    |
| Unknown | 2         | 0.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 183       | 68.03%  |
| MBR     | 55        | 20.45%  |
| Unknown | 31        | 11.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 216       | 80.6%   |
| Yes       | 52        | 19.4%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 71.64%  |
| Yes       | 76        | 28.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 56        | 20.97%  |
| ASUSTek Computer        | 39        | 14.61%  |
| Dell                    | 35        | 13.11%  |
| Hewlett-Packard         | 34        | 12.73%  |
| Gigabyte Technology     | 28        | 10.49%  |
| MSI                     | 14        | 5.24%   |
| ASRock                  | 12        | 4.49%   |
| Acer                    | 10        | 3.75%   |
| Intel                   | 4         | 1.5%    |
| Toshiba                 | 3         | 1.12%   |
| sunxi                   | 3         | 1.12%   |
| HUAWEI                  | 3         | 1.12%   |
| Apple                   | 3         | 1.12%   |
| Supermicro              | 2         | 0.75%   |
| Huanan                  | 2         | 0.75%   |
| Fujitsu                 | 2         | 0.75%   |
| Unknown                 | 2         | 0.75%   |
| UNOWHY                  | 1         | 0.37%   |
| Samsung Electronics     | 1         | 0.37%   |
| Raspberry Pi Foundation | 1         | 0.37%   |
| Protectli               | 1         | 0.37%   |
| Pine Microsystems       | 1         | 0.37%   |
| Pegatron                | 1         | 0.37%   |
| PC Specialist           | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| Monster                 | 1         | 0.37%   |
| Itautec                 | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| HARDKERNEL              | 1         | 0.37%   |
| Compulab                | 1         | 0.37%   |
| Chuwi                   | 1         | 0.37%   |
| Biostar                 | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ASUS All Series                               | 4         | 1.5%    |
| Unknown                                       | 4         | 1.5%    |
| Gigabyte B550I AORUS PRO AX                   | 3         | 1.12%   |
| ASRock B450M Pro4                             | 3         | 1.12%   |
| HUAWEI NBLK-WAX9X                             | 2         | 0.75%   |
| HP Z620 Workstation                           | 2         | 0.75%   |
| Gigabyte Z77-D3H                              | 2         | 0.75%   |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 0.75%   |
| Dell XPS 13 9310                              | 2         | 0.75%   |
| Dell Inspiron 3793                            | 2         | 0.75%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA       | 2         | 0.75%   |
| ASUS PRIME B450M-A                            | 2         | 0.75%   |
| UNOWHY Y13G002S4EI                            | 1         | 0.37%   |
| Toshiba Satellite U800W                       | 1         | 0.37%   |
| Toshiba Satellite S55-A                       | 1         | 0.37%   |
| Toshiba Satellite C45-A                       | 1         | 0.37%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.37%   |
| Supermicro SYS-5038MA-H24TRF                  | 1         | 0.37%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.37%   |
| Samsung 370E4K                                | 1         | 0.37%   |
| RPi Raspberry Pi 2 Model B Rev 1.1            | 1         | 0.37%   |
| Protectli FW6                                 | 1         | 0.37%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.37%   |
| Pegatron A15                                  | 1         | 0.37%   |
| PC Specialist NV4XMB,ME,MZ                    | 1         | 0.37%   |
| Panasonic CF-AX2LDCZMF                        | 1         | 0.37%   |
| MSI U90/U100                                  | 1         | 0.37%   |
| MSI MS-7C94                                   | 1         | 0.37%   |
| MSI MS-7C56                                   | 1         | 0.37%   |
| MSI MS-7B89                                   | 1         | 0.37%   |
| MSI MS-7A70                                   | 1         | 0.37%   |
| MSI MS-7A40                                   | 1         | 0.37%   |
| MSI MS-7995                                   | 1         | 0.37%   |
| MSI MS-7823                                   | 1         | 0.37%   |
| MSI MS-7759                                   | 1         | 0.37%   |
| MSI MS-7721                                   | 1         | 0.37%   |
| MSI MS-6712                                   | 1         | 0.37%   |
| MSI Modern 15 A11M                            | 1         | 0.37%   |
| MSI GF65 Thin 10UE                            | 1         | 0.37%   |
| MSI CX700                                     | 1         | 0.37%   |
| Monster ABRA A5 V15.2                         | 1         | 0.37%   |
| Lenovo Yoga 710-11ISK 80TX                    | 1         | 0.37%   |
| Lenovo Yoga 530-14IKB 81EK                    | 1         | 0.37%   |
| Lenovo Yoga 300-11IBR 80M1                    | 1         | 0.37%   |
| Lenovo ThinkPad Yoga 260 20FEA02WJP           | 1         | 0.37%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00         | 1         | 0.37%   |
| Lenovo ThinkPad X260 20F5S46R00               | 1         | 0.37%   |
| Lenovo ThinkPad X260 20F5S0JF00               | 1         | 0.37%   |
| Lenovo ThinkPad X230 2325AZ8                  | 1         | 0.37%   |
| Lenovo ThinkPad X201 3626ES3                  | 1         | 0.37%   |
| Lenovo ThinkPad X1 Tablet 20GGS02600          | 1         | 0.37%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS   | 1         | 0.37%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT      | 1         | 0.37%   |
| Lenovo ThinkPad T530 24296HG                  | 1         | 0.37%   |
| Lenovo ThinkPad T495 20NKS0PG00               | 1         | 0.37%   |
| Lenovo ThinkPad T495 20NJCTO1WW               | 1         | 0.37%   |
| Lenovo ThinkPad T490 20N2CTO1WW               | 1         | 0.37%   |
| Lenovo ThinkPad T480s 20L8S7HF00              | 1         | 0.37%   |
| Lenovo ThinkPad T480 20L5S1S000               | 1         | 0.37%   |
| Lenovo ThinkPad T480 20L50063EU               | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 40        | 14.98%  |
| Lenovo IdeaPad               | 9         | 3.37%   |
| Acer Aspire                  | 9         | 3.37%   |
| Dell XPS                     | 8         | 3%      |
| Dell Inspiron                | 8         | 3%      |
| ASUS PRIME                   | 8         | 3%      |
| HP EliteBook                 | 6         | 2.25%   |
| Dell Precision               | 6         | 2.25%   |
| Dell OptiPlex                | 6         | 2.25%   |
| ASUS ROG                     | 6         | 2.25%   |
| HP ProBook                   | 5         | 1.87%   |
| Dell Latitude                | 5         | 1.87%   |
| ASUS VivoBook                | 5         | 1.87%   |
| HP Compaq                    | 4         | 1.5%    |
| ASUS ZenBook                 | 4         | 1.5%    |
| ASUS All                     | 4         | 1.5%    |
| Unknown                      | 4         | 1.5%    |
| Toshiba Satellite            | 3         | 1.12%   |
| Lenovo Yoga                  | 3         | 1.12%   |
| Lenovo ThinkCentre           | 3         | 1.12%   |
| HP Laptop                    | 3         | 1.12%   |
| Gigabyte B550I               | 3         | 1.12%   |
| ASRock B450M                 | 3         | 1.12%   |
| HUAWEI NBLK-WAX9X            | 2         | 0.75%   |
| HP ZBook                     | 2         | 0.75%   |
| HP Z620                      | 2         | 0.75%   |
| HP ProLiant                  | 2         | 0.75%   |
| HP 250                       | 2         | 0.75%   |
| Gigabyte Z77-D3H             | 2         | 0.75%   |
| Gigabyte Z370                | 2         | 0.75%   |
| Gigabyte AERO                | 2         | 0.75%   |
| Fujitsu LIFEBOOK             | 2         | 0.75%   |
| Dell PowerEdge               | 2         | 0.75%   |
| UNOWHY Y13G002S4EI           | 1         | 0.37%   |
| Supermicro SYS-6019P-WT      | 1         | 0.37%   |
| Supermicro SYS-5038MA-H24TRF | 1         | 0.37%   |
| sunxi Banana                 | 1         | 0.37%   |
| Samsung 370E4K               | 1         | 0.37%   |
| RPi Raspberry                | 1         | 0.37%   |
| Protectli FW6                | 1         | 0.37%   |
| Pine Microsystems Pine64     | 1         | 0.37%   |
| Pegatron A15                 | 1         | 0.37%   |
| PC Specialist NV4XMB         | 1         | 0.37%   |
| Panasonic CF-AX2LDCZMF       | 1         | 0.37%   |
| MSI U90                      | 1         | 0.37%   |
| MSI MS-7C94                  | 1         | 0.37%   |
| MSI MS-7C56                  | 1         | 0.37%   |
| MSI MS-7B89                  | 1         | 0.37%   |
| MSI MS-7A70                  | 1         | 0.37%   |
| MSI MS-7A40                  | 1         | 0.37%   |
| MSI MS-7995                  | 1         | 0.37%   |
| MSI MS-7823                  | 1         | 0.37%   |
| MSI MS-7759                  | 1         | 0.37%   |
| MSI MS-7721                  | 1         | 0.37%   |
| MSI MS-6712                  | 1         | 0.37%   |
| MSI Modern                   | 1         | 0.37%   |
| MSI GF65                     | 1         | 0.37%   |
| MSI CX700                    | 1         | 0.37%   |
| Monster ABRA                 | 1         | 0.37%   |
| Lenovo G50-80                | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 63        | 23.6%   |
| 2021    | 45        | 16.85%  |
| 2019    | 38        | 14.23%  |
| 2018    | 27        | 10.11%  |
| 2012    | 15        | 5.62%   |
| 2016    | 13        | 4.87%   |
| 2014    | 12        | 4.49%   |
| 2013    | 12        | 4.49%   |
| 2015    | 7         | 2.62%   |
| Unknown | 7         | 2.62%   |
| 2017    | 6         | 2.25%   |
| 2011    | 6         | 2.25%   |
| 2010    | 4         | 1.5%    |
| 2008    | 4         | 1.5%    |
| 2009    | 3         | 1.12%   |
| 2007    | 2         | 0.75%   |
| 2006    | 1         | 0.37%   |
| 2004    | 1         | 0.37%   |
| 2001    | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 143       | 53.56%  |
| Desktop        | 99        | 37.08%  |
| Convertible    | 7         | 2.62%   |
| System on chip | 6         | 2.25%   |
| Server         | 4         | 1.5%    |
| Mini pc        | 3         | 1.12%   |
| Tablet         | 2         | 0.75%   |
| All in one     | 2         | 0.75%   |
| Phone          | 1         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 237       | 88.1%   |
| Enabled  | 32        | 11.9%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 266       | 99.63%  |
| Yes  | 1         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 80        | 29.96%  |
| 4.01-8.0        | 48        | 17.98%  |
| 8.01-16.0       | 46        | 17.23%  |
| 32.01-64.0      | 27        | 10.11%  |
| 3.01-4.0        | 27        | 10.11%  |
| 64.01-256.0     | 19        | 7.12%   |
| 1.01-2.0        | 9         | 3.37%   |
| 2.01-3.0        | 6         | 2.25%   |
| 24.01-32.0      | 2         | 0.75%   |
| More than 256.0 | 1         | 0.37%   |
| 0.51-1.0        | 1         | 0.37%   |
| 0.01-0.5        | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 63        | 23.16%  |
| 1.01-2.0    | 52        | 19.12%  |
| 4.01-8.0    | 44        | 16.18%  |
| 3.01-4.0    | 44        | 16.18%  |
| 8.01-16.0   | 26        | 9.56%   |
| 0.51-1.0    | 23        | 8.46%   |
| 0.01-0.5    | 9         | 3.31%   |
| 16.01-24.0  | 4         | 1.47%   |
| 32.01-64.0  | 3         | 1.1%    |
| 24.01-32.0  | 3         | 1.1%    |
| 64.01-256.0 | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 129       | 48.31%  |
| 2      | 80        | 29.96%  |
| 3      | 24        | 8.99%   |
| 4      | 16        | 5.99%   |
| 5      | 8         | 3%      |
| 8      | 5         | 1.87%   |
| 9      | 2         | 0.75%   |
| 0      | 2         | 0.75%   |
| 6      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 67.42%  |
| Yes       | 87        | 32.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 83.15%  |
| No        | 45        | 16.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 70.41%  |
| No        | 79        | 29.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 56.18%  |
| No        | 117       | 43.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country       | Computers | Percent |
|---------------|-----------|---------|
| USA           | 41        | 15.36%  |
| France        | 27        | 10.11%  |
| Germany       | 25        | 9.36%   |
| Russia        | 17        | 6.37%   |
| UK            | 13        | 4.87%   |
| Poland        | 13        | 4.87%   |
| Spain         | 12        | 4.49%   |
| Brazil        | 10        | 3.75%   |
| Ukraine       | 8         | 3%      |
| Netherlands   | 7         | 2.62%   |
| Canada        | 6         | 2.25%   |
| Switzerland   | 5         | 1.87%   |
| Mexico        | 5         | 1.87%   |
| Italy         | 5         | 1.87%   |
| India         | 5         | 1.87%   |
| Hungary       | 5         | 1.87%   |
| Thailand      | 4         | 1.5%    |
| Czechia       | 4         | 1.5%    |
| Australia     | 4         | 1.5%    |
| Turkey        | 3         | 1.12%   |
| Portugal      | 3         | 1.12%   |
| Greece        | 3         | 1.12%   |
| Ecuador       | 3         | 1.12%   |
| Bulgaria      | 3         | 1.12%   |
| Belgium       | 3         | 1.12%   |
| Austria       | 3         | 1.12%   |
| Argentina     | 3         | 1.12%   |
| Sweden        | 2         | 0.75%   |
| Norway        | 2         | 0.75%   |
| Japan         | 2         | 0.75%   |
| Finland       | 2         | 0.75%   |
| Croatia       | 2         | 0.75%   |
| Vietnam       | 1         | 0.37%   |
| Syria         | 1         | 0.37%   |
| Slovenia      | 1         | 0.37%   |
| Singapore     | 1         | 0.37%   |
| Serbia        | 1         | 0.37%   |
| Romania       | 1         | 0.37%   |
| Philippines   | 1         | 0.37%   |
| New Caledonia | 1         | 0.37%   |
| Mongolia      | 1         | 0.37%   |
| Madagascar    | 1         | 0.37%   |
| Kazakhstan    | 1         | 0.37%   |
| Indonesia     | 1         | 0.37%   |
| Denmark       | 1         | 0.37%   |
| Colombia      | 1         | 0.37%   |
| China         | 1         | 0.37%   |
| Belarus       | 1         | 0.37%   |
| Bangladesh    | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Paris          | 8         | 2.99%   |
| St Petersburg  | 5         | 1.87%   |
| Lyon           | 4         | 1.49%   |
| Kyiv           | 4         | 1.49%   |
| Ensenada       | 4         | 1.49%   |
| Bangkok        | 4         | 1.49%   |
| Warsaw         | 3         | 1.12%   |
| Vienna         | 3         | 1.12%   |
| Sofia          | 3         | 1.12%   |
| Mesa           | 3         | 1.12%   |
| London         | 3         | 1.12%   |
| Gloucester     | 3         | 1.12%   |
| Bengaluru      | 3         | 1.12%   |
| Waregem        | 2         | 0.75%   |
| Shizuoka       | 2         | 0.75%   |
| Rio de Janeiro | 2         | 0.75%   |
| Prague         | 2         | 0.75%   |
| Perm           | 2         | 0.75%   |
| Oleksandrivka  | 2         | 0.75%   |
| Noblesville    | 2         | 0.75%   |
| New York       | 2         | 0.75%   |
| Madrid         | 2         | 0.75%   |
| Lublin         | 2         | 0.75%   |
| Las Vegas      | 2         | 0.75%   |
| Kalamazoo      | 2         | 0.75%   |
| Hanover        | 2         | 0.75%   |
| Gorinchem      | 2         | 0.75%   |
| Cuenca         | 2         | 0.75%   |
| Berlin         | 2         | 0.75%   |
| Athens         | 2         | 0.75%   |
| Ankara         | 2         | 0.75%   |
| Érd           | 1         | 0.37%   |
| Zurich         | 1         | 0.37%   |
| Zaragoza       | 1         | 0.37%   |
| Zagreb         | 1         | 0.37%   |
| Woolloongabba  | 1         | 0.37%   |
| Woodstock      | 1         | 0.37%   |
| Waterloo       | 1         | 0.37%   |
| Vladivostok    | 1         | 0.37%   |
| Vitória       | 1         | 0.37%   |
| Vancouver      | 1         | 0.37%   |
| Valladolid     | 1         | 0.37%   |
| Valencia       | 1         | 0.37%   |
| Vaasa          | 1         | 0.37%   |
| Utrecht        | 1         | 0.37%   |
| Ulyanovsk      | 1         | 0.37%   |
| Turin          | 1         | 0.37%   |
| Toulouse       | 1         | 0.37%   |
| Toul           | 1         | 0.37%   |
| Toronto        | 1         | 0.37%   |
| Thonex         | 1         | 0.37%   |
| Thionville     | 1         | 0.37%   |
| The Hague      | 1         | 0.37%   |
| The Colony     | 1         | 0.37%   |
| Tarn??w        | 1         | 0.37%   |
| Sunnyvale      | 1         | 0.37%   |
| Stroud         | 1         | 0.37%   |
| Strasbourg     | 1         | 0.37%   |
| Stockholm      | 1         | 0.37%   |
| Stavanger      | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 70        | 96     | 17.28%  |
| WDC                 | 65        | 97     | 16.05%  |
| Seagate             | 55        | 83     | 13.58%  |
| Toshiba             | 30        | 42     | 7.41%   |
| Unknown             | 23        | 33     | 5.68%   |
| Kingston            | 20        | 24     | 4.94%   |
| Crucial             | 20        | 22     | 4.94%   |
| Intel               | 13        | 20     | 3.21%   |
| SanDisk             | 11        | 13     | 2.72%   |
| Hitachi             | 11        | 12     | 2.72%   |
| A-DATA Technology   | 10        | 14     | 2.47%   |
| SK Hynix            | 9         | 11     | 2.22%   |
| HGST                | 8         | 10     | 1.98%   |
| Transcend           | 4         | 5      | 0.99%   |
| Micron Technology   | 4         | 4      | 0.99%   |
| Patriot             | 3         | 3      | 0.74%   |
| LITEONIT            | 3         | 3      | 0.74%   |
| KIOXIA              | 3         | 3      | 0.74%   |
| Intenso             | 3         | 3      | 0.74%   |
| Gigabyte Technology | 3         | 3      | 0.74%   |
| China               | 3         | 3      | 0.74%   |
| SPCC                | 2         | 2      | 0.49%   |
| PNY                 | 2         | 2      | 0.49%   |
| Phison Electronics  | 2         | 2      | 0.49%   |
| Phison              | 2         | 5      | 0.49%   |
| LITEON              | 2         | 2      | 0.49%   |
| Lenovo              | 2         | 2      | 0.49%   |
| JMicron             | 2         | 2      | 0.49%   |
| Apple               | 2         | 2      | 0.49%   |
| ZTC                 | 1         | 1      | 0.25%   |
| XPG                 | 1         | 1      | 0.25%   |
| Union Memory        | 1         | 1      | 0.25%   |
| TrueNAS             | 1         | 1      | 0.25%   |
| Team                | 1         | 1      | 0.25%   |
| Silicon Motion      | 1         | 2      | 0.25%   |
| SABRENT             | 1         | 1      | 0.25%   |
| Maxtor              | 1         | 2      | 0.25%   |
| Maximus             | 1         | 1      | 0.25%   |
| MaxDigital          | 1         | 2      | 0.25%   |
| LDLC                | 1         | 1      | 0.25%   |
| KingDian            | 1         | 1      | 0.25%   |
| IBM-ESXS            | 1         | 2      | 0.25%   |
| Fujitsu             | 1         | 1      | 0.25%   |
| Corsair             | 1         | 1      | 0.25%   |
| ASUS-PHISON         | 1         | 1      | 0.25%   |
| Apacer              | 1         | 1      | 0.25%   |
| AMD                 | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 1TB                 | 9         | 1.92%   |
| Samsung SSD 860 EVO 1TB                      | 8         | 1.71%   |
| Samsung SSD 970 EVO Plus 500GB               | 5         | 1.07%   |
| Samsung SSD 850 EVO 500GB                    | 5         | 1.07%   |
| Samsung SSD 850 EVO 250GB                    | 5         | 1.07%   |
| Kingston SA400S37240G 240GB SSD              | 4         | 0.85%   |
| WDC WDS500G3X0C-00SJG0 500GB                 | 3         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD             | 3         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD             | 3         | 0.64%   |
| WDC WD10SPZX-21Z10T0 1TB                     | 3         | 0.64%   |
| Unknown DA4064  64GB                         | 3         | 0.64%   |
| Toshiba MQ04ABF100 1TB                       | 3         | 0.64%   |
| Toshiba HDWD110 1TB                          | 3         | 0.64%   |
| Seagate ST2000LX001-1RG174 2TB               | 3         | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB               | 3         | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 0.64%   |
| Samsung SSD 860 EVO 500GB                    | 3         | 0.64%   |
| Samsung SSD 860 EVO 250GB                    | 3         | 0.64%   |
| Samsung SSD 840 PRO Series 256GB             | 3         | 0.64%   |
| Kingston SV300S37A240G 240GB SSD             | 3         | 0.64%   |
| Hitachi HUS724040ALE641 4TB                  | 3         | 0.64%   |
| HGST HTS721010A9E630 1TB                     | 3         | 0.64%   |
| Crucial CT500P1SSD8 500GB                    | 3         | 0.64%   |
| Crucial CT500MX500SSD1 500GB                 | 3         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB                  | 3         | 0.64%   |
| WDC WDS500G2B0C-00PXH0 500GB                 | 2         | 0.43%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 2         | 0.43%   |
| WDC WD20EARX-00PASB0 2TB                     | 2         | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 2         | 0.43%   |
| WDC WD10EFRX-68FYTN0 1TB                     | 2         | 0.43%   |
| Unknown SL16G  16GB                          | 2         | 0.43%   |
| Unknown MMC Card  64GB                       | 2         | 0.43%   |
| Unknown MMC Card  32GB                       | 2         | 0.43%   |
| Toshiba MQ01ACF032 320GB                     | 2         | 0.43%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 0.43%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB      | 2         | 0.43%   |
| Toshiba DT01ACA300 3TB                       | 2         | 0.43%   |
| Toshiba DT01ACA200 2TB                       | 2         | 0.43%   |
| Seagate ST500DM002-1BD142 500GB              | 2         | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB               | 2         | 0.43%   |
| Seagate ST3000DM001-1CH166 3TB               | 2         | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB               | 2         | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB               | 2         | 0.43%   |
| Seagate ST1000DM010-2EP102 1TB               | 2         | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB               | 2         | 0.43%   |
| Seagate BUP Slim BL 2TB                      | 2         | 0.43%   |
| Seagate BarraCuda 120 SSD ZA250CM10003 250GB | 2         | 0.43%   |
| Seagate Backup+ Hub BK 4TB                   | 2         | 0.43%   |
| SanDisk SSD PLUS 240GB                       | 2         | 0.43%   |
| Sandisk NVMe SSD Drive 1TB                   | 2         | 0.43%   |
| Samsung SSD 970 EVO Plus 250GB               | 2         | 0.43%   |
| Samsung SSD 970 EVO 500GB                    | 2         | 0.43%   |
| Samsung SSD 970 EVO 1TB                      | 2         | 0.43%   |
| Samsung SSD 860 EVO 2TB                      | 2         | 0.43%   |
| Samsung HD103SJ 1TB                          | 2         | 0.43%   |
| Phison PCIe SSD 512GB                        | 2         | 0.43%   |
| KIOXIA KBG40ZNV1T02 1TB                      | 2         | 0.43%   |
| Kingston SV300S37A120G 120GB SSD             | 2         | 0.43%   |
| Kingston SUV500240G 240GB SSD                | 2         | 0.43%   |
| Kingston OM8PCP3512F-AI1 512GB               | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 68     | 35%     |
| WDC                 | 44        | 66     | 31.43%  |
| Toshiba             | 20        | 31     | 14.29%  |
| Hitachi             | 11        | 12     | 7.86%   |
| HGST                | 8         | 10     | 5.71%   |
| Samsung Electronics | 5         | 6      | 3.57%   |
| MaxDigital          | 1         | 2      | 0.71%   |
| IBM-ESXS            | 1         | 2      | 0.71%   |
| Fujitsu             | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 37        | 54     | 27.41%  |
| Kingston            | 15        | 19     | 11.11%  |
| Crucial             | 15        | 16     | 11.11%  |
| WDC                 | 10        | 13     | 7.41%   |
| SanDisk             | 7         | 8      | 5.19%   |
| A-DATA Technology   | 6         | 7      | 4.44%   |
| Transcend           | 4         | 5      | 2.96%   |
| Intel               | 4         | 4      | 2.96%   |
| Toshiba             | 3         | 4      | 2.22%   |
| Seagate             | 3         | 3      | 2.22%   |
| Patriot             | 3         | 3      | 2.22%   |
| LITEONIT            | 3         | 3      | 2.22%   |
| China               | 3         | 3      | 2.22%   |
| Intenso             | 2         | 2      | 1.48%   |
| ZTC                 | 1         | 1      | 0.74%   |
| Unknown             | 1         | 1      | 0.74%   |
| Union Memory        | 1         | 1      | 0.74%   |
| TrueNAS             | 1         | 1      | 0.74%   |
| Team                | 1         | 1      | 0.74%   |
| SPCC                | 1         | 1      | 0.74%   |
| SK Hynix            | 1         | 1      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| Micron Technology   | 1         | 1      | 0.74%   |
| Maxtor              | 1         | 2      | 0.74%   |
| Maximus             | 1         | 1      | 0.74%   |
| LITEON              | 1         | 1      | 0.74%   |
| LDLC                | 1         | 1      | 0.74%   |
| KingDian            | 1         | 1      | 0.74%   |
| JMicron             | 1         | 1      | 0.74%   |
| Gigabyte Technology | 1         | 1      | 0.74%   |
| ASUS-PHISON         | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |
| Apacer              | 1         | 1      | 0.74%   |
| AMD                 | 1         | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 124       | 165    | 32.72%  |
| HDD     | 119       | 198    | 31.4%   |
| NVMe    | 107       | 135    | 28.23%  |
| MMC     | 21        | 32     | 5.54%   |
| Unknown | 8         | 15     | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 348    | 55.18%  |
| NVMe | 106       | 134    | 32.32%  |
| MMC  | 21        | 32     | 6.4%    |
| SAS  | 20        | 31     | 6.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 121       | 175    | 48.21%  |
| 0.51-1.0   | 75        | 95     | 29.88%  |
| 1.01-2.0   | 30        | 36     | 11.95%  |
| 3.01-4.0   | 11        | 24     | 4.38%   |
| 2.01-3.0   | 6         | 10     | 2.39%   |
| 4.01-10.0  | 5         | 15     | 1.99%   |
| 10.01-20.0 | 3         | 8      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 62        | 23.05%  |
| 101-250        | 47        | 17.47%  |
| 501-1000       | 37        | 13.75%  |
| 1001-2000      | 32        | 11.9%   |
| More than 3000 | 27        | 10.04%  |
| 51-100         | 18        | 6.69%   |
| 1-20           | 17        | 6.32%   |
| 21-50          | 13        | 4.83%   |
| Unknown        | 9         | 3.35%   |
| 2001-3000      | 7         | 2.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 69        | 25.27%  |
| 101-250        | 46        | 16.85%  |
| 21-50          | 38        | 13.92%  |
| 51-100         | 30        | 10.99%  |
| 251-500        | 28        | 10.26%  |
| 501-1000       | 20        | 7.33%   |
| 1001-2000      | 14        | 5.13%   |
| More than 3000 | 9         | 3.3%    |
| Unknown        | 9         | 3.3%    |
| 2001-3000      | 7         | 2.56%   |
| 0              | 3         | 1.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYX-18WERA0 500GB                 | 1         | 2      | 2.38%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 2.38%   |
| WDC WD5000AAKS-22V1A0 500GB                  | 1         | 1      | 2.38%   |
| WDC WD5000AAJS-22A8B0 500GB                  | 1         | 1      | 2.38%   |
| WDC WD400BB-00DEA0 40GB                      | 1         | 1      | 2.38%   |
| WDC WD20EFRX-68EUZN0 2TB                     | 1         | 2      | 2.38%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 2.38%   |
| WDC WD1600AAJS-00L7A0 160GB                  | 1         | 1      | 2.38%   |
| WDC WD10EZEX-08WN4A0 1TB                     | 1         | 1      | 2.38%   |
| WDC WD10EZEX-00BN5A0 1TB                     | 1         | 1      | 2.38%   |
| WDC WD1001FALS-75J7B0 1TB                    | 1         | 1      | 2.38%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 2.38%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 2.38%   |
| Toshiba DT01ACA050 500GB                     | 1         | 1      | 2.38%   |
| SK Hynix PC401 NVMe 512GB                    | 1         | 2      | 2.38%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 2.38%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 2.38%   |
| Seagate ST32000542AS 2TB                     | 1         | 1      | 2.38%   |
| Seagate ST31500341AS 1TB                     | 1         | 1      | 2.38%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 2.38%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 1         | 1      | 2.38%   |
| Seagate ST1000DM003-1CH162 1TB               | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 120 GB                      | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 2.38%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 2.38%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.38%   |
| KingDian S280 240GB                          | 1         | 1      | 2.38%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 2.38%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 2.38%   |
| Intel SSDPEKKW010T7 1TB                      | 1         | 2      | 2.38%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 2.38%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 2.38%   |
| Hitachi HDS722525VLAT80 250GB                | 1         | 1      | 2.38%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 2.38%   |
| A-DATA Technology SU800 256GB SSD            | 1         | 2      | 2.38%   |
| A-DATA Technology SU630 480GB SSD            | 1         | 1      | 2.38%   |
| A-DATA Technology SSD DP900 128GB-DL3        | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 13     | 26.19%  |
| Seagate             | 10        | 10     | 23.81%  |
| Toshiba             | 5         | 5      | 11.9%   |
| Intel               | 3         | 4      | 7.14%   |
| Hitachi             | 3         | 3      | 7.14%   |
| A-DATA Technology   | 3         | 4      | 7.14%   |
| SK Hynix            | 1         | 2      | 2.38%   |
| SanDisk             | 1         | 1      | 2.38%   |
| Samsung Electronics | 1         | 2      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |
| KingDian            | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 11        | 13     | 36.67%  |
| Seagate | 10        | 10     | 33.33%  |
| Toshiba | 5         | 5      | 16.67%  |
| Hitachi | 3         | 3      | 10%     |
| HGST    | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 32     | 70.73%  |
| SSD  | 10        | 12     | 24.39%  |
| NVMe | 2         | 4      | 4.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500830AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 213       | 386    | 68.27%  |
| Detected | 58        | 110    | 18.59%  |
| Malfunc  | 40        | 48     | 12.82%  |
| Failed   | 1         | 1      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 169       | 50.6%   |
| AMD                          | 44        | 13.17%  |
| Samsung Electronics          | 37        | 11.08%  |
| Sandisk                      | 18        | 5.39%   |
| SK Hynix                     | 8         | 2.4%    |
| Phison Electronics           | 8         | 2.4%    |
| Toshiba America Info Systems | 7         | 2.1%    |
| Micron/Crucial Technology    | 6         | 1.8%    |
| Kingston Technology Company  | 5         | 1.5%    |
| ASMedia Technology           | 5         | 1.5%    |
| ADATA Technology             | 5         | 1.5%    |
| Broadcom / LSI               | 4         | 1.2%    |
| Micron Technology            | 3         | 0.9%    |
| Marvell Technology Group     | 3         | 0.9%    |
| KIOXIA                       | 3         | 0.9%    |
| Lenovo                       | 2         | 0.6%    |
| JMicron Technology           | 2         | 0.6%    |
| VIA Technologies             | 1         | 0.3%    |
| Silicon Motion               | 1         | 0.3%    |
| Seagate Technology           | 1         | 0.3%    |
| Lite-On Technology           | 1         | 0.3%    |
| Adaptec                      | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 32        | 8.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 7.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 4.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 3.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 3.39%   |
| AMD 400 Series Chipset SATA Controller                                         | 13        | 3.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 2.08%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.82%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 7         | 1.82%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.3%    |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.3%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 5         | 1.3%    |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 1.3%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 1.3%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.3%    |
| Intel SATA Controller [RAID mode]                                              | 4         | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 1.04%   |
| SK Hynix NVMe SSD Controller                                                   | 3         | 0.78%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 3         | 0.78%   |
| Samsung NVMe Controller                                                        | 3         | 0.78%   |
| Micron Non-Volatile memory controller                                          | 3         | 0.78%   |
| KIOXIA Non-Volatile memory controller                                          | 3         | 0.78%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.78%   |
| Intel SSD 600P Series                                                          | 3         | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.78%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 3         | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.78%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 3         | 0.78%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.52%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 2         | 0.52%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 0.52%   |
| Lenovo Non-Volatile memory controller                                          | 2         | 0.52%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 2         | 0.52%   |
| Intel SSD 660P Series                                                          | 2         | 0.52%   |
| Intel NVMe Optane Memory Series                                                | 2         | 0.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.52%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 0.52%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                            | 2         | 0.52%   |
| Intel C600/X79 series chipset IDE-r Controller                                 | 2         | 0.52%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 179       | 52.65%  |
| NVMe | 106       | 31.18%  |
| RAID | 27        | 7.94%   |
| IDE  | 22        | 6.47%   |
| SAS  | 6         | 1.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 202       | 75.66%  |
| AMD    | 58        | 21.72%  |
| ARM    | 7         | 2.62%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 8         | 3%      |
| Intel Core i5-3320M CPU @ 2.60GHz               | 7         | 2.62%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 2.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 5         | 1.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 5         | 1.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 5         | 1.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 5         | 1.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 5         | 1.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 4         | 1.5%    |
| ARM Processor                                   | 4         | 1.5%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 4         | 1.5%    |
| AMD Ryzen 7 3700X 8-Core Processor              | 4         | 1.5%    |
| Intel Pentium CPU N4200 @ 1.10GHz               | 3         | 1.12%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 3         | 1.12%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 3         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.12%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 3         | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 3         | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 1.12%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 3         | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.75%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 2         | 0.75%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 2         | 0.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 2         | 0.75%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 2         | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 0.75%   |
| Intel Core i7-10710U CPU @ 1.10GHz              | 2         | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 2         | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 0.75%   |
| Intel Core i5-7500 CPU @ 3.40GHz                | 2         | 0.75%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 2         | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2         | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz                | 2         | 0.75%   |
| Intel Core i5-2500K CPU @ 3.30GHz               | 2         | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 2         | 0.75%   |
| Intel Core i5 CPU 650 @ 3.20GHz                 | 2         | 0.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 0.75%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.75%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 2         | 0.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 0.75%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 0.75%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 0.75%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 2         | 0.75%   |
| AMD Ryzen 5 3600X 6-Core Processor              | 2         | 0.75%   |
| Intel Xeon W-2145 CPU @ 3.70GHz                 | 1         | 0.37%   |
| Intel Xeon Silver 4215R CPU @ 3.20GHz           | 1         | 0.37%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                | 1         | 0.37%   |
| Intel Xeon CPU W3503 @ 2.40GHz                  | 1         | 0.37%   |
| Intel Xeon CPU E5-2699 v4 @ 2.20GHz             | 1         | 0.37%   |
| Intel Xeon CPU E5-2697 v3 @ 2.60GHz             | 1         | 0.37%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz             | 1         | 0.37%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz              | 1         | 0.37%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz             | 1         | 0.37%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz              | 1         | 0.37%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz              | 1         | 0.37%   |
| Intel Xeon CPU E5-2420 0 @ 1.90GHz              | 1         | 0.37%   |
| Intel Xeon CPU E5-1650 0 @ 3.20GHz              | 1         | 0.37%   |
| Intel Pentium M processor 1600MHz               | 1         | 0.37%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 74        | 27.72%  |
| Intel Core i7          | 59        | 22.1%   |
| AMD Ryzen 5            | 22        | 8.24%   |
| Other                  | 17        | 6.37%   |
| Intel Xeon             | 12        | 4.49%   |
| Intel Core i3          | 11        | 4.12%   |
| Intel Celeron          | 11        | 4.12%   |
| AMD Ryzen 7            | 10        | 3.75%   |
| Intel Pentium          | 7         | 2.62%   |
| AMD Ryzen 7 PRO        | 6         | 2.25%   |
| Intel Core 2 Duo       | 5         | 1.87%   |
| AMD Ryzen 9            | 4         | 1.5%    |
| AMD Ryzen 3            | 4         | 1.5%    |
| Intel Atom             | 3         | 1.12%   |
| AMD Phenom II X4       | 2         | 0.75%   |
| Intel Xeon Silver      | 1         | 0.37%   |
| Intel Pentium M        | 1         | 0.37%   |
| Intel Pentium 4        | 1         | 0.37%   |
| Intel Core m7          | 1         | 0.37%   |
| Intel Core i9          | 1         | 0.37%   |
| Intel Core 2 Quad      | 1         | 0.37%   |
| Intel Core 2           | 1         | 0.37%   |
| Intel Celeron M        | 1         | 0.37%   |
| ARM BCM                | 1         | 0.37%   |
| ARM Allwinner          | 1         | 0.37%   |
| ARM AArch64            | 1         | 0.37%   |
| AMD Ryzen Threadripper | 1         | 0.37%   |
| AMD FX                 | 1         | 0.37%   |
| AMD Athlon XP          | 1         | 0.37%   |
| AMD Athlon X4          | 1         | 0.37%   |
| AMD Athlon II Neo      | 1         | 0.37%   |
| AMD A8                 | 1         | 0.37%   |
| AMD A6                 | 1         | 0.37%   |
| AMD A12                | 1         | 0.37%   |
| AMD A10                | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 111       | 41.57%  |
| 2      | 83        | 31.09%  |
| 6      | 36        | 13.48%  |
| 8      | 20        | 7.49%   |
| 1      | 7         | 2.62%   |
| 12     | 4         | 1.5%    |
| 16     | 3         | 1.12%   |
| 44     | 1         | 0.37%   |
| 32     | 1         | 0.37%   |
| 28     | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 261       | 97.75%  |
| 2      | 6         | 2.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 195       | 73.03%  |
| 1      | 72        | 26.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 258       | 96.63%  |
| 32-bit         | 5         | 1.87%   |
| 64-bit         | 2         | 0.75%   |
| Unknown        | 2         | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 21.85%  |
| 0x306a9    | 21        | 7.78%   |
| 0x206a7    | 15        | 5.56%   |
| 0x306c3    | 13        | 4.81%   |
| 0x08701021 | 12        | 4.44%   |
| 0x806c1    | 10        | 3.7%    |
| 0x806ea    | 8         | 2.96%   |
| 0x906ea    | 7         | 2.59%   |
| 0x706e5    | 7         | 2.59%   |
| 0x406e3    | 7         | 2.59%   |
| 0x906e9    | 6         | 2.22%   |
| 0x806e9    | 6         | 2.22%   |
| 0x306d4    | 6         | 2.22%   |
| 0x08108109 | 6         | 2.22%   |
| 0x806ec    | 5         | 1.85%   |
| 0x506e3    | 5         | 1.85%   |
| 0x506c9    | 5         | 1.85%   |
| 0x206d7    | 5         | 1.85%   |
| 0x08600106 | 5         | 1.85%   |
| 0xa0652    | 4         | 1.48%   |
| 0x806eb    | 4         | 1.48%   |
| 0x40651    | 3         | 1.11%   |
| 0x306f2    | 3         | 1.11%   |
| 0x20655    | 3         | 1.11%   |
| 0x06003106 | 3         | 1.11%   |
| 0xa0660    | 2         | 0.74%   |
| 0x706a8    | 2         | 0.74%   |
| 0x406c4    | 2         | 0.74%   |
| 0x0a201009 | 2         | 0.74%   |
| 0x08701013 | 2         | 0.74%   |
| 0x0800820d | 2         | 0.74%   |
| 0x08001138 | 2         | 0.74%   |
| 0x010000c8 | 2         | 0.74%   |
| 0xf29      | 1         | 0.37%   |
| 0xa0671    | 1         | 0.37%   |
| 0xa0653    | 1         | 0.37%   |
| 0x906ec    | 1         | 0.37%   |
| 0x706a1    | 1         | 0.37%   |
| 0x6fb      | 1         | 0.37%   |
| 0x6f6      | 1         | 0.37%   |
| 0x6d8      | 1         | 0.37%   |
| 0x695      | 1         | 0.37%   |
| 0x50657    | 1         | 0.37%   |
| 0x50654    | 1         | 0.37%   |
| 0x406f1    | 1         | 0.37%   |
| 0x406d8    | 1         | 0.37%   |
| 0x406c3    | 1         | 0.37%   |
| 0x106e5    | 1         | 0.37%   |
| 0x106c2    | 1         | 0.37%   |
| 0x106a5    | 1         | 0.37%   |
| 0x1067a    | 1         | 0.37%   |
| 0x10661    | 1         | 0.37%   |
| 0x0a50000b | 1         | 0.37%   |
| 0x08608103 | 1         | 0.37%   |
| 0x08600104 | 1         | 0.37%   |
| 0x08108102 | 1         | 0.37%   |
| 0x0800820b | 1         | 0.37%   |
| 0x06006705 | 1         | 0.37%   |
| 0x0600611a | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 49        | 18.35%  |
| Zen 2         | 26        | 9.74%   |
| IvyBridge     | 26        | 9.74%   |
| Haswell       | 22        | 8.24%   |
| Skylake       | 20        | 7.49%   |
| SandyBridge   | 20        | 7.49%   |
| Zen+          | 14        | 5.24%   |
| TigerLake     | 11        | 4.12%   |
| Unknown       | 9         | 3.37%   |
| CometLake     | 8         | 3%      |
| IceLake       | 7         | 2.62%   |
| Broadwell     | 7         | 2.62%   |
| Westmere      | 5         | 1.87%   |
| Goldmont      | 5         | 1.87%   |
| Core          | 5         | 1.87%   |
| Zen 3         | 4         | 1.5%    |
| Steamroller   | 4         | 1.5%    |
| Silvermont    | 4         | 1.5%    |
| Penryn        | 3         | 1.12%   |
| K10           | 3         | 1.12%   |
| Goldmont plus | 3         | 1.12%   |
| Zen           | 2         | 0.75%   |
| P6            | 2         | 0.75%   |
| Nehalem       | 2         | 0.75%   |
| Excavator     | 2         | 0.75%   |
| Piledriver    | 1         | 0.37%   |
| NetBurst      | 1         | 0.37%   |
| K6            | 1         | 0.37%   |
| Bonnell       | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 161       | 53.67%  |
| Nvidia                     | 76        | 25.33%  |
| AMD                        | 58        | 19.33%  |
| Matrox Electronics Systems | 3         | 1%      |
| ASPEED Technology          | 2         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 5.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.23%   |
| Intel UHD Graphics 620                                                                   | 12        | 3.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.26%   |
| AMD Picasso                                                                              | 9         | 2.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 2.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.61%   |
| AMD Renoir                                                                               | 8         | 2.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.28%   |
| Intel HD Graphics 620                                                                    | 6         | 1.95%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 5         | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 1.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.3%    |
| Intel HD Graphics 530                                                                    | 4         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.3%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 1.3%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.98%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.98%   |
| Intel HD Graphics 630                                                                    | 3         | 0.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.98%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2         | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.65%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.65%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.65%   |
| Nvidia GK104 [GeForce GTX 670]                                                           | 2         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.65%   |
| Nvidia G98 [Quadro NVS 295]                                                              | 2         | 0.65%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.65%   |
| Intel HD Graphics 515                                                                    | 2         | 0.65%   |
| Intel HD Graphics 500                                                                    | 2         | 0.65%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.65%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.65%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.33%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.33%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.33%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.33%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 124       | 46.1%   |
| 1 x AMD         | 47        | 17.47%  |
| 1 x Nvidia      | 43        | 15.99%  |
| Intel + Nvidia  | 31        | 11.52%  |
| Other           | 8         | 2.97%   |
| Intel + AMD     | 6         | 2.23%   |
| 2 x AMD         | 3         | 1.12%   |
| 1 x Matrox      | 2         | 0.74%   |
| 1 x ASPEED      | 2         | 0.74%   |
| AMD + Nvidia    | 2         | 0.74%   |
| Nvidia + Matrox | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 228       | 85.07%  |
| Proprietary | 28        | 10.45%  |
| Unknown     | 12        | 4.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 67.9%   |
| 1.01-2.0   | 21        | 7.75%   |
| 0.51-1.0   | 16        | 5.9%    |
| 0.01-0.5   | 15        | 5.54%   |
| 3.01-4.0   | 14        | 5.17%   |
| 7.01-8.0   | 12        | 4.43%   |
| 5.01-6.0   | 6         | 2.21%   |
| 2.01-3.0   | 2         | 0.74%   |
| 24.01-32.0 | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 41        | 13.9%   |
| Samsung Electronics  | 34        | 11.53%  |
| Chimei Innolux       | 28        | 9.49%   |
| BOE                  | 27        | 9.15%   |
| Dell                 | 23        | 7.8%    |
| LG Display           | 22        | 7.46%   |
| Goldstar             | 17        | 5.76%   |
| Ancor Communications | 11        | 3.73%   |
| Acer                 | 11        | 3.73%   |
| Hewlett-Packard      | 10        | 3.39%   |
| Sharp                | 9         | 3.05%   |
| Philips              | 8         | 2.71%   |
| BenQ                 | 7         | 2.37%   |
| Lenovo               | 6         | 2.03%   |
| AOC                  | 6         | 2.03%   |
| Unknown              | 3         | 1.02%   |
| Iiyama               | 3         | 1.02%   |
| ASUSTek Computer     | 3         | 1.02%   |
| Apple                | 3         | 1.02%   |
| LG Electronics       | 2         | 0.68%   |
| CPT                  | 2         | 0.68%   |
| ___                  | 1         | 0.34%   |
| ViewSonic            | 1         | 0.34%   |
| Vestel Elektronik    | 1         | 0.34%   |
| TEO                  | 1         | 0.34%   |
| Sony                 | 1         | 0.34%   |
| PANDA                | 1         | 0.34%   |
| ODH                  | 1         | 0.34%   |
| NCS                  | 1         | 0.34%   |
| Medion               | 1         | 0.34%   |
| JXG                  | 1         | 0.34%   |
| JVC                  | 1         | 0.34%   |
| JRY                  | 1         | 0.34%   |
| InfoVision           | 1         | 0.34%   |
| INFOTRONIC           | 1         | 0.34%   |
| Idek Iiyama          | 1         | 0.34%   |
| Hitachi              | 1         | 0.34%   |
| Eizo                 | 1         | 0.34%   |
| CSO                  | 1         | 0.34%   |
| Belinea              | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 1.31%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 0.98%   |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch           | 3         | 0.98%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.66%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.66%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 2         | 0.66%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 2         | 0.66%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch            | 2         | 0.66%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch             | 2         | 0.66%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.66%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 2         | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 2         | 0.66%   |
| Dell LCD Monitor U2312HM 1920x1080                                     | 2         | 0.66%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 2         | 0.66%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.66%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 0.66%   |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch | 2         | 0.66%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 2         | 0.66%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.33%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.33%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.33%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.33%   |
| TEO TL565 TEO5550 1024x768 304x228mm 15.0-inch                         | 1         | 0.33%   |
| Sony TV *00 SNY3F05 3840x2160 952x535mm 43.0-inch                      | 1         | 0.33%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.33%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP14E2 1920x1080 309x174mm 14.0-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 1         | 0.33%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.33%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch      | 1         | 0.33%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch      | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0521 1600x900 443x249mm 20.0-inch    | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch    | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch   | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0115 1280x1024 376x301mm 19.0-inch   | 1         | 0.33%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 1         | 0.33%   |
| Samsung Electronics SMB2430H SAM064D 1920x1080 531x299mm 24.0-inch     | 1         | 0.33%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.33%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.33%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 598x336mm 27.0-inch      | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 126       | 44.06%  |
| 1366x768 (WXGA)    | 45        | 15.73%  |
| 3840x2160 (4K)     | 19        | 6.64%   |
| 2560x1440 (QHD)    | 17        | 5.94%   |
| 1600x900 (HD+)     | 15        | 5.24%   |
| 1280x1024 (SXGA)   | 11        | 3.85%   |
| 1920x1200 (WUXGA)  | 10        | 3.5%    |
| 1680x1050 (WSXGA+) | 9         | 3.15%   |
| 1440x900 (WXGA+)   | 6         | 2.1%    |
| 1280x800 (WXGA)    | 5         | 1.75%   |
| Unknown            | 4         | 1.4%    |
| 2560x1600          | 2         | 0.7%    |
| 2288x1287          | 2         | 0.7%    |
| 1600x1200          | 2         | 0.7%    |
| 1024x768 (XGA)     | 2         | 0.7%    |
| 7680x4320          | 1         | 0.35%   |
| 5760x1080          | 1         | 0.35%   |
| 4480x1440          | 1         | 0.35%   |
| 3840x2400          | 1         | 0.35%   |
| 3440x1440          | 1         | 0.35%   |
| 3360x1080          | 1         | 0.35%   |
| 2560x1080          | 1         | 0.35%   |
| 2160x1440          | 1         | 0.35%   |
| 1920x540           | 1         | 0.35%   |
| 1792x768           | 1         | 0.35%   |
| 1024x600           | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 52        | 17.69%  |
| 13      | 41        | 13.95%  |
| 24      | 27        | 9.18%   |
| 14      | 27        | 9.18%   |
| 23      | 23        | 7.82%   |
| 27      | 20        | 6.8%    |
| 17      | 14        | 4.76%   |
| 21      | 12        | 4.08%   |
| Unknown | 11        | 3.74%   |
| 12      | 10        | 3.4%    |
| 19      | 8         | 2.72%   |
| 31      | 7         | 2.38%   |
| 18      | 7         | 2.38%   |
| 11      | 7         | 2.38%   |
| 20      | 4         | 1.36%   |
| 22      | 3         | 1.02%   |
| 142     | 2         | 0.68%   |
| 84      | 2         | 0.68%   |
| 47      | 2         | 0.68%   |
| 34      | 2         | 0.68%   |
| 29      | 2         | 0.68%   |
| 28      | 2         | 0.68%   |
| 25      | 2         | 0.68%   |
| 72      | 1         | 0.34%   |
| 55      | 1         | 0.34%   |
| 48      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 33      | 1         | 0.34%   |
| 16      | 1         | 0.34%   |
| 10      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 109       | 37.98%  |
| 501-600        | 62        | 21.6%   |
| 201-300        | 36        | 12.54%  |
| 401-500        | 32        | 11.15%  |
| 601-700        | 13        | 4.53%   |
| 351-400        | 11        | 3.83%   |
| Unknown        | 11        | 3.83%   |
| 1001-1500      | 4         | 1.39%   |
| 701-800        | 3         | 1.05%   |
| 1501-2000      | 3         | 1.05%   |
| More than 2000 | 2         | 0.7%    |
| 801-900        | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 205       | 75.93%  |
| 16/10   | 26        | 9.63%   |
| 5/4     | 10        | 3.7%    |
| Unknown | 10        | 3.7%    |
| 4/3     | 6         | 2.22%   |
| 3/2     | 6         | 2.22%   |
| 21/9    | 3         | 1.11%   |
| 1.00    | 2         | 0.74%   |
| 6/5     | 1         | 0.37%   |
| 1.96    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 17.99%  |
| 81-90          | 51        | 17.65%  |
| 201-250        | 49        | 16.96%  |
| 301-350        | 20        | 6.92%   |
| 71-80          | 18        | 6.23%   |
| 151-200        | 17        | 5.88%   |
| 351-500        | 14        | 4.84%   |
| 141-150        | 11        | 3.81%   |
| Unknown        | 11        | 3.81%   |
| 251-300        | 10        | 3.46%   |
| 61-70          | 9         | 3.11%   |
| 51-60          | 7         | 2.42%   |
| 121-130        | 7         | 2.42%   |
| More than 1000 | 6         | 2.08%   |
| 501-1000       | 4         | 1.38%   |
| 131-140        | 2         | 0.69%   |
| 41-50          | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 95        | 33.93%  |
| 51-100        | 92        | 32.86%  |
| 101-120       | 51        | 18.21%  |
| 161-240       | 20        | 7.14%   |
| Unknown       | 11        | 3.93%   |
| 1-50          | 6         | 2.14%   |
| More than 240 | 5         | 1.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 201       | 74.72%  |
| 2     | 46        | 17.1%   |
| 0     | 15        | 5.58%   |
| 3     | 6         | 2.23%   |
| 4     | 1         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 155       | 42.58%  |
| Realtek Semiconductor             | 124       | 34.07%  |
| Qualcomm Atheros                  | 37        | 10.16%  |
| Broadcom                          | 14        | 3.85%   |
| Marvell Technology Group          | 4         | 1.1%    |
| Ralink Technology                 | 3         | 0.82%   |
| Ralink                            | 3         | 0.82%   |
| Broadcom Limited                  | 3         | 0.82%   |
| Microchip Technology              | 2         | 0.55%   |
| Ericsson Business Mobile Networks | 2         | 0.55%   |
| Edimax Technology                 | 2         | 0.55%   |
| Dell                              | 2         | 0.55%   |
| Cypress Semiconductor             | 2         | 0.55%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.27%   |
| Xiaomi                            | 1         | 0.27%   |
| TP-Link                           | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| Qualcomm                          | 1         | 0.27%   |
| Microsoft                         | 1         | 0.27%   |
| IBM                               | 1         | 0.27%   |
| Huawei Technologies               | 1         | 0.27%   |
| Fibocom                           | 1         | 0.27%   |
| DisplayLink                       | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84        | 18.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 4.71%   |
| Intel Wi-Fi 6 AX200                                               | 17        | 3.81%   |
| Intel Wireless 8260                                               | 12        | 2.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 2.24%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.79%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 1.79%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.12%   |
| Intel Wireless 7265                                               | 5         | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.9%    |
| Intel Wireless 7260                                               | 4         | 0.9%    |
| Intel Wireless 3165                                               | 4         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.45%   |
| Realtek 802.11ac NIC                                              | 2         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.45%   |
| Intel Wireless-AC 9260                                            | 2         | 0.45%   |
| Intel Wireless 3160                                               | 2         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.45%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.45%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 2         | 0.45%   |
| Cypress K38231_03                                                 | 2         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.45%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.45%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 115       | 59.59%  |
| Qualcomm Atheros      | 30        | 15.54%  |
| Realtek Semiconductor | 27        | 13.99%  |
| Broadcom              | 6         | 3.11%   |
| Ralink Technology     | 3         | 1.55%   |
| Ralink                | 3         | 1.55%   |
| Edimax Technology     | 2         | 1.04%   |
| TP-Link               | 1         | 0.52%   |
| Sierra Wireless       | 1         | 0.52%   |
| Qualcomm              | 1         | 0.52%   |
| Microsoft             | 1         | 0.52%   |
| Fibocom               | 1         | 0.52%   |
| D-Link                | 1         | 0.52%   |
| Broadcom Limited      | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 17        | 8.76%   |
| Intel Wireless 8260                                                     | 12        | 6.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 5.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 4.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.12%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.12%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.58%   |
| Intel Wireless 7265                                                     | 5         | 2.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.06%   |
| Intel Wireless 7260                                                     | 4         | 2.06%   |
| Intel Wireless 3165                                                     | 4         | 2.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 1.03%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.03%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.03%   |
| Intel Wireless 3160                                                     | 2         | 1.03%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.03%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 2         | 1.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.03%   |
| TP-Link Archer T4U ver.3                                                | 1         | 0.52%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.52%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.52%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.52%   |
| Ralink RT5370 Wireless Adapter                                          | 1         | 0.52%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.52%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.52%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.52%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.52%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 1         | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.52%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 0.52%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 1         | 0.52%   |
| Intel Wireless Gigabit 17265                                            | 1         | 0.52%   |
| Intel WiFi Link 5100                                                    | 1         | 0.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.52%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                         | 1         | 0.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.52%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.52%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.52%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 110       | 46.22%  |
| Intel                    | 91        | 38.24%  |
| Broadcom                 | 12        | 5.04%   |
| Qualcomm Atheros         | 11        | 4.62%   |
| Marvell Technology Group | 4         | 1.68%   |
| Microchip Technology     | 2         | 0.84%   |
| Cypress Semiconductor    | 2         | 0.84%   |
| Broadcom Limited         | 2         | 0.84%   |
| Xiaomi                   | 1         | 0.42%   |
| IBM                      | 1         | 0.42%   |
| Huawei Technologies      | 1         | 0.42%   |
| DisplayLink              | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84        | 34.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 8.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 4.07%   |
| Intel I211 Gigabit Network Connection                             | 9         | 3.66%   |
| Intel Ethernet Connection (2) I219-V                              | 8         | 3.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.44%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.03%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.63%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.81%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.81%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.81%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.81%   |
| Cypress K38231_03                                                 | 2         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.81%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.81%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.41%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.41%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.41%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.41%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.41%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.41%   |
| Intel Ethernet Virtual Function 700 Series                        | 1         | 0.41%   |
| Intel Ethernet Controller XXV710 for 25GbE SFP28                  | 1         | 0.41%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1         | 0.41%   |
| Intel Ethernet Connection X722 for 1GbE                           | 1         | 0.41%   |
| Intel Ethernet Connection I354                                    | 1         | 0.41%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.41%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.41%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.41%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 222       | 53.49%  |
| WiFi     | 187       | 45.06%  |
| Modem    | 6         | 1.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 173       | 50.88%  |
| WiFi     | 166       | 48.82%  |
| Modem    | 1         | 0.29%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 140       | 52.43%  |
| 1     | 104       | 38.95%  |
| 3     | 11        | 4.12%   |
| 0     | 9         | 3.37%   |
| 13    | 1         | 0.37%   |
| 6     | 1         | 0.37%   |
| 4     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 203       | 75.75%  |
| Yes  | 65        | 24.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 57.24%  |
| Realtek Semiconductor           | 12        | 7.89%   |
| Qualcomm Atheros Communications | 12        | 7.89%   |
| Cambridge Silicon Radio         | 8         | 5.26%   |
| Broadcom                        | 8         | 5.26%   |
| Lite-On Technology              | 6         | 3.95%   |
| Realtek                         | 3         | 1.97%   |
| IMC Networks                    | 3         | 1.97%   |
| Foxconn / Hon Hai               | 3         | 1.97%   |
| ASUSTek Computer                | 3         | 1.97%   |
| Toshiba                         | 2         | 1.32%   |
| Apple                           | 2         | 1.32%   |
| Ralink                          | 1         | 0.66%   |
| Hewlett-Packard                 | 1         | 0.66%   |
| Dell                            | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 32        | 21.05%  |
| Intel AX200 Bluetooth                               | 17        | 11.18%  |
| Intel AX201 Bluetooth                               | 15        | 9.87%   |
| Intel Bluetooth Device                              | 11        | 7.24%   |
| Realtek Bluetooth Radio                             | 10        | 6.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 3.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 2.63%   |
| Realtek Bluetooth Radio                             | 3         | 1.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.97%   |
| Toshiba Bluetooth Device                            | 2         | 1.32%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.32%   |
| Lite-On Bluetooth Device                            | 2         | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.32%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.32%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.32%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.66%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.66%   |
| IMC Networks Bluetooth Device                       | 1         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.66%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.66%   |
| Dell BCM20702A0                                     | 1         | 0.66%   |
| Broadcom BCM2035 Bluetooth dongle                   | 1         | 0.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.66%   |
| ASUS Bluetooth Radio                                | 1         | 0.66%   |
| ASUS Bluetooth Adapter                              | 1         | 0.66%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.66%   |
| Apple Bluetooth Host Controller                     | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 193       | 53.76%  |
| AMD                        | 64        | 17.83%  |
| Nvidia                     | 58        | 16.16%  |
| C-Media Electronics        | 12        | 3.34%   |
| Generalplus Technology     | 4         | 1.11%   |
| Texas Instruments          | 3         | 0.84%   |
| Logitech                   | 3         | 0.84%   |
| GYROCOM C&C                | 3         | 0.84%   |
| Creative Labs              | 3         | 0.84%   |
| Samson Technologies        | 2         | 0.56%   |
| GN Netcom                  | 2         | 0.56%   |
| BEHRINGER International    | 2         | 0.56%   |
| VIA Technologies           | 1         | 0.28%   |
| ROCCAT                     | 1         | 0.28%   |
| Razer USA                  | 1         | 0.28%   |
| PreSonus Audio Electronics | 1         | 0.28%   |
| Plantronics                | 1         | 0.28%   |
| Hewlett-Packard            | 1         | 0.28%   |
| Hangzhou Worlde            | 1         | 0.28%   |
| Creative Technology        | 1         | 0.28%   |
| Blue Microphones           | 1         | 0.28%   |
| Alesis                     | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 6.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 6.28%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 19        | 4.59%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 19        | 4.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 3.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.66%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.17%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 9         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.69%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.45%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.45%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.21%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 0.97%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 0.97%   |
| Generalplus Technology USB Audio Device                                                           | 4         | 0.97%   |
| AMD FCH Azalia Controller                                                                         | 4         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.72%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 3         | 0.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.72%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.72%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.48%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.48%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.48%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.48%   |
| GYROCOM C&C Fiio E10                                                                              | 2         | 0.48%   |
| C-Media Electronics USB Audio Device                                                              | 2         | 0.48%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.48%   |
| C-Media Electronics Blue Snowball                                                                 | 2         | 0.48%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.48%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 55        | 19.5%   |
| Samsung Electronics | 51        | 18.09%  |
| Kingston            | 33        | 11.7%   |
| Crucial             | 26        | 9.22%   |
| Unknown             | 24        | 8.51%   |
| Micron Technology   | 22        | 7.8%    |
| Corsair             | 19        | 6.74%   |
| G.Skill             | 11        | 3.9%    |
| A-DATA Technology   | 11        | 3.9%    |
| Ramaxel Technology  | 6         | 2.13%   |
| Elpida              | 5         | 1.77%   |
| Team                | 4         | 1.42%   |
| Unknown (ABCD)      | 2         | 0.71%   |
| Nanya Technology    | 2         | 0.71%   |
| Kllisre             | 2         | 0.71%   |
| GOODRAM             | 2         | 0.71%   |
| V-Color             | 1         | 0.35%   |
| Unifosa             | 1         | 0.35%   |
| SMART Brazil        | 1         | 0.35%   |
| Smart               | 1         | 0.35%   |
| PNY                 | 1         | 0.35%   |
| Patriot             | 1         | 0.35%   |
| GeIL                | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 3         | 0.99%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.99%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.99%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.66%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.66%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.66%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.66%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.66%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.66%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.66%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.66%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.66%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.66%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 2         | 0.66%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s              | 2         | 0.66%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s              | 2         | 0.66%   |
| G.Skill RAM F4-3200C16-16GTZSK 16GB DIMM DDR4 3200MT/s           | 2         | 0.66%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.66%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.66%   |
| Crucial RAM CT102464BD160B.C16 8GB DIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s            | 2         | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 2         | 0.66%   |
| V-Color RAM TD4G16C11-H11 4GB DIMM DDR3 1333MT/s                 | 1         | 0.33%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                           | 1         | 0.33%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.33%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.33%   |
| Unknown RAM V02D4LF8GB5285282400 8192MB DIMM DDR4 2400MT/s       | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.33%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 1         | 0.33%   |
| Unknown RAM Module 512MB DIMM SDRAM 400MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4GB DIMM 800MT/s                              | 1         | 0.33%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.33%   |
| Unknown RAM Module 32GB DIMM DDR4 3200MT/s                       | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.33%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.33%   |
| Unknown RAM Module 256MB DIMM SDRAM 400MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.33%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.33%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 1         | 0.33%   |
| Unknown RAM Module 16GB DIMM DDR4 2400MT/s                       | 1         | 0.33%   |
| Unknown RAM CMA5-4GA03BALA1B00 8GB SODIMM DDR3 1600MT/s          | 1         | 0.33%   |
| Unknown RAM 7EH64AA# 8GB DIMM DDR4 2667MT/s                      | 1         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 1         | 0.33%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 0.33%   |
| Team RAM TEAMGROUP-UD3-1333 8GB DIMM DDR3 1333MT/s               | 1         | 0.33%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 126       | 53.39%  |
| DDR3    | 82        | 34.75%  |
| LPDDR3  | 8         | 3.39%   |
| LPDDR4  | 7         | 2.97%   |
| DDR2    | 6         | 2.54%   |
| Unknown | 4         | 1.69%   |
| SDRAM   | 3         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 129       | 54.66%  |
| DIMM         | 88        | 37.29%  |
| Row Of Chips | 16        | 6.78%   |
| Chip         | 2         | 0.85%   |
| RIMM         | 1         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 100       | 38.91%  |
| 4096  | 75        | 29.18%  |
| 16384 | 40        | 15.56%  |
| 2048  | 20        | 7.78%   |
| 32768 | 12        | 4.67%   |
| 1024  | 6         | 2.33%   |
| 512   | 2         | 0.78%   |
| 65536 | 1         | 0.39%   |
| 256   | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 59        | 22.26%  |
| 2667    | 47        | 17.74%  |
| 3200    | 37        | 13.96%  |
| 2400    | 25        | 9.43%   |
| 1333    | 23        | 8.68%   |
| 2133    | 19        | 7.17%   |
| 1334    | 8         | 3.02%   |
| 3600    | 6         | 2.26%   |
| 1867    | 5         | 1.89%   |
| 2933    | 4         | 1.51%   |
| 4267    | 3         | 1.13%   |
| 2666    | 3         | 1.13%   |
| 3466    | 2         | 0.75%   |
| 3000    | 2         | 0.75%   |
| 1866    | 2         | 0.75%   |
| 1067    | 2         | 0.75%   |
| 800     | 2         | 0.75%   |
| 667     | 2         | 0.75%   |
| 533     | 2         | 0.75%   |
| 400     | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 4266    | 1         | 0.38%   |
| 3533    | 1         | 0.38%   |
| 3500    | 1         | 0.38%   |
| 3066    | 1         | 0.38%   |
| 2465    | 1         | 0.38%   |
| 2000    | 1         | 0.38%   |
| 1800    | 1         | 0.38%   |
| 1066    | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 66.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung ML-1660 Series | 1         | 16.67%  |
| HP LaserJet P1006      | 1         | 16.67%  |
| HP LaserJet M101-M106  | 1         | 16.67%  |
| HP LaserJet 1200       | 1         | 16.67%  |
| HP ENVY 4520 series    | 1         | 16.67%  |
| Canon LiDE 400         | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 18.24%  |
| IMC Networks                           | 24        | 15.09%  |
| Microdia                               | 17        | 10.69%  |
| Acer                                   | 16        | 10.06%  |
| Realtek Semiconductor                  | 11        | 6.92%   |
| Logitech                               | 11        | 6.92%   |
| Lite-On Technology                     | 9         | 5.66%   |
| Quanta                                 | 7         | 4.4%    |
| Sunplus Innovation Technology          | 5         | 3.14%   |
| Apple                                  | 4         | 2.52%   |
| Suyin                                  | 3         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.89%   |
| Syntek                                 | 2         | 1.26%   |
| Samsung Electronics                    | 2         | 1.26%   |
| Generalplus Technology                 | 2         | 1.26%   |
| Z-Star Microelectronics                | 1         | 0.63%   |
| Xiongmai                               | 1         | 0.63%   |
| Razer USA                              | 1         | 0.63%   |
| Pixart Imaging                         | 1         | 0.63%   |
| Lenovo                                 | 1         | 0.63%   |
| Huawei Technologies                    | 1         | 0.63%   |
| Hewlett-Packard                        | 1         | 0.63%   |
| Genesys Logic                          | 1         | 0.63%   |
| eMPIA Technology                       | 1         | 0.63%   |
| DJKCVA19IE3NE8                         | 1         | 0.63%   |
| AVerMedia Technologies                 | 1         | 0.63%   |
| ARC International                      | 1         | 0.63%   |
| ALi                                    | 1         | 0.63%   |
| Alcor Micro                            | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 9         | 5.66%   |
| Chicony integrated camera                | 9         | 5.66%   |
| IMC Networks Integrated Camera           | 8         | 5.03%   |
| Acer Integrated Camera                   | 8         | 5.03%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 4.4%    |
| Realtek Integrated_Webcam_HD             | 5         | 3.14%   |
| Lite-On Integrated Camera                | 4         | 2.52%   |
| Chicony HP HD Camera                     | 4         | 2.52%   |
| Acer SunplusIT Integrated Camera         | 4         | 2.52%   |
| Microdia Webcam Vitade AF                | 3         | 1.89%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 1.89%   |
| Chicony HD WebCam                        | 3         | 1.89%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 1.26%   |
| Realtek EasyCamera                       | 2         | 1.26%   |
| Quanta HD Webcam                         | 2         | 1.26%   |
| Microdia USB Live camera                 | 2         | 1.26%   |
| Logitech HD Pro Webcam C920              | 2         | 1.26%   |
| Logitech C505 HD Webcam                  | 2         | 1.26%   |
| Lite-On HP HD Camera                     | 2         | 1.26%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 2         | 1.26%   |
| IMC Networks ov9734_azurewave_camera     | 2         | 1.26%   |
| Chicony Lenovo EasyCamera                | 2         | 1.26%   |
| Chicony HP HD Webcam                     | 2         | 1.26%   |
| Apple FaceTime HD Camera                 | 2         | 1.26%   |
| Z-Star Venus USB2.0 Camera               | 1         | 0.63%   |
| Xiongmai web camera                      | 1         | 0.63%   |
| Syntek USB 2.0 UVC PC Camera             | 1         | 0.63%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 0.63%   |
| Suyin HP TrueVision Full HD              | 1         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 0.63%   |
| Sunplus Laptop Integrated Webcam FHD     | 1         | 0.63%   |
| Sunplus Integrated_Webcam_HD             | 1         | 0.63%   |
| Sunplus Dell E5570 integrated webcam     | 1         | 0.63%   |
| Sunplus 1.3M HD WebCam                   | 1         | 0.63%   |
| Realtek Lenovo EasyCamera                | 1         | 0.63%   |
| Realtek Integrated Webcam                | 1         | 0.63%   |
| Realtek HD WebCam                        | 1         | 0.63%   |
| Realtek Acer 640 x 480 laptop camera     | 1         | 0.63%   |
| Razer USA Razer Kiyo                     | 1         | 0.63%   |
| Quanta VGA WebCam                        | 1         | 0.63%   |
| Quanta ov9734_techfront_camera           | 1         | 0.63%   |
| Quanta HP Webcam                         | 1         | 0.63%   |
| Quanta HP TrueVision HD Camera           | 1         | 0.63%   |
| Quanta HP HD Camera                      | 1         | 0.63%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_E4HD   | 1         | 0.63%   |
| Microdia Integrated Camera               | 1         | 0.63%   |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 0.63%   |
| Logitech Webcam C930e                    | 1         | 0.63%   |
| Logitech Webcam C270                     | 1         | 0.63%   |
| Logitech Webcam C260                     | 1         | 0.63%   |
| Logitech HD Webcam C910                  | 1         | 0.63%   |
| Logitech HD Webcam C615                  | 1         | 0.63%   |
| Logitech CrystalCam                      | 1         | 0.63%   |
| Logitech BRIO                            | 1         | 0.63%   |
| Lite-On TOSHIBA Web Camera - HD          | 1         | 0.63%   |
| Lite-On HP Webcam                        | 1         | 0.63%   |
| Lite-On HP Full-HD Camera                | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 15        | 40.54%  |
| Shenzhen Goodix Technology | 9         | 24.32%  |
| Validity Sensors           | 7         | 18.92%  |
| Elan Microelectronics      | 3         | 8.11%   |
| Upek                       | 2         | 5.41%   |
| AuthenTec                  | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 16.22%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 13.51%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 10.81%  |
| Shenzhen Goodix FingerPrint                                                | 4         | 10.81%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 8.11%   |
| Elan ELAN:Fingerprint                                                      | 3         | 8.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 5.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 5.41%   |
| Synaptics  WBDI                                                            | 1         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.7%    |
| Unknown                                                                    | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 7         | 33.33%  |
| Broadcom              | 5         | 23.81%  |
| Lenovo                | 4         | 19.05%  |
| Upek                  | 3         | 14.29%  |
| O2 Micro              | 1         | 4.76%   |
| Gemalto (was Gemplus) | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 33.33%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 19.05%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 14.29%  |
| Broadcom 58200                                                               | 3         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom 5880                                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 197       | 72.96%  |
| 1     | 50        | 18.52%  |
| 2     | 20        | 7.41%   |
| 5     | 2         | 0.74%   |
| 4     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 39.36%  |
| Graphics card            | 17        | 18.09%  |
| Chipcard                 | 17        | 18.09%  |
| Multimedia controller    | 6         | 6.38%   |
| Net/wireless             | 5         | 5.32%   |
| Communication controller | 5         | 5.32%   |
| Unassigned class         | 4         | 4.26%   |
| Storage                  | 1         | 1.06%   |
| Card reader              | 1         | 1.06%   |
| Bluetooth                | 1         | 1.06%   |

