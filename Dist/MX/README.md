MX - Tested Hardware & Statistics
---------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX/Desktop/README.md) and [notebooks](/Dist/MX/Notebook/README.md).

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

Total: 535

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | Notebook    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c60d9aa72d](https://linux-hardware.org/?probe=c60d9aa72d) | Oct 31, 2022 |
| Vulcan Ele... | Excursion XB                | Notebook    | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Biostar       | H61MH                       | Desktop     | [f505de310c](https://linux-hardware.org/?probe=f505de310c) | Oct 27, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [226e4471e1](https://linux-hardware.org/?probe=226e4471e1) | Oct 27, 2022 |
| Lenovo        | 318E NOK                    | Desktop     | [6b190bfb4f](https://linux-hardware.org/?probe=6b190bfb4f) | Oct 25, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [fa925dcefb](https://linux-hardware.org/?probe=fa925dcefb) | Oct 24, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [59dabaff86](https://linux-hardware.org/?probe=59dabaff86) | Oct 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [c389b44ab5](https://linux-hardware.org/?probe=c389b44ab5) | Oct 21, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [b6c2cf5b2e](https://linux-hardware.org/?probe=b6c2cf5b2e) | Oct 17, 2022 |
| Dell          | Latitude 3190               | Notebook    | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1f6ff0e213](https://linux-hardware.org/?probe=1f6ff0e213) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| Pegatron      | NARRA3                      | Desktop     | [1588e60c57](https://linux-hardware.org/?probe=1588e60c57) | Oct 12, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | Notebook    | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Lenovo        | ThinkPad T420 4236TL7       | Notebook    | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [bb43eb5333](https://linux-hardware.org/?probe=bb43eb5333) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | Notebook    | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f97d2b97ad](https://linux-hardware.org/?probe=f97d2b97ad) | Oct 01, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [72bb90ea71](https://linux-hardware.org/?probe=72bb90ea71) | Sep 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | Notebook    | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8e429edcd6](https://linux-hardware.org/?probe=8e429edcd6) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HP            | 1632                        | Desktop     | [8309a8acf0](https://linux-hardware.org/?probe=8309a8acf0) | Sep 10, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | Notebook    | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | Notebook    | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [1a577be107](https://linux-hardware.org/?probe=1a577be107) | Sep 04, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | Notebook    | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Biostar       | A780L3B                     | Desktop     | [62782d600f](https://linux-hardware.org/?probe=62782d600f) | Aug 14, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [83e026f682](https://linux-hardware.org/?probe=83e026f682) | Aug 12, 2022 |
| Acer          | Extensa 5630                | Notebook    | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | Notebook    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | Notebook    | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| MP            | MS-7848                     | Desktop     | [f7696965e0](https://linux-hardware.org/?probe=f7696965e0) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [85782181c7](https://linux-hardware.org/?probe=85782181c7) | Jul 21, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| UMAX          | VisionBook-N12R             | Notebook    | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Dell          | 0DR845                      | Desktop     | [4c4a530cc5](https://linux-hardware.org/?probe=4c4a530cc5) | Jul 06, 2022 |
| Alienware     | 13 R2                       | Notebook    | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | Notebook    | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [77c632ea8e](https://linux-hardware.org/?probe=77c632ea8e) | Jul 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [5a66940742](https://linux-hardware.org/?probe=5a66940742) | Jun 23, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [bc8030c1d5](https://linux-hardware.org/?probe=bc8030c1d5) | Jun 22, 2022 |
| Dell          | 0DR845                      | Desktop     | [56b4af8d26](https://linux-hardware.org/?probe=56b4af8d26) | Jun 20, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | Notebook    | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | Notebook    | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | Notebook    | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | Notebook    | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c21cd1f8f3](https://linux-hardware.org/?probe=c21cd1f8f3) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [b57b3a635c](https://linux-hardware.org/?probe=b57b3a635c) | Jun 02, 2022 |
| Dell          | Latitude D520               | Notebook    | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | Notebook    | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| AZW           | SER                         | Mini pc     | [9da3c6ca34](https://linux-hardware.org/?probe=9da3c6ca34) | May 18, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | Notebook    | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [b627953ad4](https://linux-hardware.org/?probe=b627953ad4) | May 11, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Intel         | V1.3                        | Desktop     | [a01993f2fa](https://linux-hardware.org/?probe=a01993f2fa) | Apr 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [51cc264c62](https://linux-hardware.org/?probe=51cc264c62) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [03878be4ec](https://linux-hardware.org/?probe=03878be4ec) | Apr 20, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [208972e3b5](https://linux-hardware.org/?probe=208972e3b5) | Apr 19, 2022 |
| ASRock        | N3150M                      | Desktop     | [0ee71f6582](https://linux-hardware.org/?probe=0ee71f6582) | Apr 19, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [1127f26185](https://linux-hardware.org/?probe=1127f26185) | Apr 17, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [7cc89d3cba](https://linux-hardware.org/?probe=7cc89d3cba) | Apr 14, 2022 |
| Sun Micros... | Sun Ultra 40 M2 Workstat... | Server      | [5cd6adf199](https://linux-hardware.org/?probe=5cd6adf199) | Apr 14, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [084e2350e9](https://linux-hardware.org/?probe=084e2350e9) | Apr 05, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [5de0fab8f2](https://linux-hardware.org/?probe=5de0fab8f2) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [83dab83528](https://linux-hardware.org/?probe=83dab83528) | Apr 01, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | Notebook    | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | Notebook    | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Gigabyte      | P35-DS3P                    | Desktop     | [9c4373296f](https://linux-hardware.org/?probe=9c4373296f) | Mar 21, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Acer          | Extensa 5630                | Notebook    | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4521c22268](https://linux-hardware.org/?probe=4521c22268) | Mar 06, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ecc5ad7332](https://linux-hardware.org/?probe=ecc5ad7332) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [e58223cc60](https://linux-hardware.org/?probe=e58223cc60) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [23c722f6cf](https://linux-hardware.org/?probe=23c722f6cf) | Feb 18, 2022 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f4fec6a5be](https://linux-hardware.org/?probe=f4fec6a5be) | Feb 17, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7c66c1b404](https://linux-hardware.org/?probe=7c66c1b404) | Feb 09, 2022 |
| Sony          | SVE1513Q1ESI                | Notebook    | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | Notebook    | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | Notebook    | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [d0ba3786b2](https://linux-hardware.org/?probe=d0ba3786b2) | Feb 03, 2022 |
| HP            | ProBook 6460b               | Notebook    | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Intel         | H81                         | Desktop     | [c1763fe2cf](https://linux-hardware.org/?probe=c1763fe2cf) | Jan 29, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Acer          | Spin SP111-31               | Convertible | [21bfc2a904](https://linux-hardware.org/?probe=21bfc2a904) | Jan 16, 2022 |
| IBM           | 8183B2U                     | Desktop     | [d070680dfb](https://linux-hardware.org/?probe=d070680dfb) | Jan 14, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [52e09bab91](https://linux-hardware.org/?probe=52e09bab91) | Jan 02, 2022 |
| HP            | 2000                        | Notebook    | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | Notebook    | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | Notebook    | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| ECS           | A55F-M3                     | Desktop     | [5439a8e37c](https://linux-hardware.org/?probe=5439a8e37c) | Nov 27, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | Notebook    | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | Notebook    | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| MSI           | B460M PRO                   | Desktop     | [ae3e01fef8](https://linux-hardware.org/?probe=ae3e01fef8) | Oct 31, 2021 |
| ECS           | A55F-M3                     | Desktop     | [27e84aca95](https://linux-hardware.org/?probe=27e84aca95) | Oct 31, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | Notebook    | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | Notebook    | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | Notebook    | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cbff9b4baf](https://linux-hardware.org/?probe=cbff9b4baf) | Oct 21, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [1e6b01d3bd](https://linux-hardware.org/?probe=1e6b01d3bd) | Oct 21, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [08e803937e](https://linux-hardware.org/?probe=08e803937e) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [c11bd1c981](https://linux-hardware.org/?probe=c11bd1c981) | Oct 11, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Sony          | SVT13115FBS                 | Notebook    | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| GreatWall     | U320                        | Desktop     | [483d23be23](https://linux-hardware.org/?probe=483d23be23) | Oct 06, 2021 |
| GreatWall     | U320                        | Desktop     | [043d1121f4](https://linux-hardware.org/?probe=043d1121f4) | Oct 06, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | Notebook    | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [3549222788](https://linux-hardware.org/?probe=3549222788) | Oct 02, 2021 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [536f6d67e3](https://linux-hardware.org/?probe=536f6d67e3) | Oct 02, 2021 |
| Intel         | Unknown                     | Desktop     | [e97eb92439](https://linux-hardware.org/?probe=e97eb92439) | Oct 01, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [8699437e9e](https://linux-hardware.org/?probe=8699437e9e) | Oct 01, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | Notebook    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | Notebook    | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [ad42fa5d08](https://linux-hardware.org/?probe=ad42fa5d08) | Oct 01, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [2bf98ef81c](https://linux-hardware.org/?probe=2bf98ef81c) | Sep 24, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | Notebook    | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | Notebook    | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Dell          | 0P611C A00                  | Desktop     | [eadaa5e6cb](https://linux-hardware.org/?probe=eadaa5e6cb) | Aug 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Pixus         | Rise                        | Notebook    | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | Notebook    | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [3c5ac88729](https://linux-hardware.org/?probe=3c5ac88729) | Aug 08, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [6949bed845](https://linux-hardware.org/?probe=6949bed845) | Aug 05, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [e94701caeb](https://linux-hardware.org/?probe=e94701caeb) | Aug 03, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [bc56fe50dd](https://linux-hardware.org/?probe=bc56fe50dd) | Jul 24, 2021 |
| Acer          | Aspire E5-574G              | Notebook    | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| ASRock        | H170M Pro4                  | Desktop     | [f291edbc4a](https://linux-hardware.org/?probe=f291edbc4a) | Jul 18, 2021 |
| Dell          | Vostro 5515                 | Notebook    | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | Notebook    | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [192043ebbd](https://linux-hardware.org/?probe=192043ebbd) | Jul 12, 2021 |
| Acer          | Aspire one                  | Notebook    | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [b85b636b73](https://linux-hardware.org/?probe=b85b636b73) | Jun 26, 2021 |
| Medion        | P6669 MD60147               | Notebook    | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | Notebook    | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | Notebook    | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [bae9a4e960](https://linux-hardware.org/?probe=bae9a4e960) | May 16, 2021 |
| Irbis         | TW94                        | Notebook    | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [ac4ce770fc](https://linux-hardware.org/?probe=ac4ce770fc) | May 10, 2021 |
| Dell          | Latitude E6320              | Notebook    | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [506efba999](https://linux-hardware.org/?probe=506efba999) | May 02, 2021 |
| Acer          | Extensa 5620                | Notebook    | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | Notebook    | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | Notebook    | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | Notebook    | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [6d6b869b27](https://linux-hardware.org/?probe=6d6b869b27) | Apr 08, 2021 |
| HP            | Falco                       | Notebook    | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [4959cfd244](https://linux-hardware.org/?probe=4959cfd244) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | Notebook    | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| ASUSTek       | P5K-E                       | Desktop     | [f0c435ead1](https://linux-hardware.org/?probe=f0c435ead1) | Apr 01, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8d8771e1ef](https://linux-hardware.org/?probe=8d8771e1ef) | Mar 30, 2021 |
| Dell          | 0W7H8C A02                  | Server      | [1a32b081a7](https://linux-hardware.org/?probe=1a32b081a7) | Mar 30, 2021 |
| Dell          | 0XR1GT A00                  | Desktop     | [04145c0b36](https://linux-hardware.org/?probe=04145c0b36) | Mar 29, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4c93424ea5](https://linux-hardware.org/?probe=4c93424ea5) | Mar 26, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d77d6984e4](https://linux-hardware.org/?probe=d77d6984e4) | Mar 19, 2021 |
| MSI           | MS-7210 100                 | Desktop     | [e8723eb58b](https://linux-hardware.org/?probe=e8723eb58b) | Mar 17, 2021 |
| HP            | ZBook 17 G6                 | Notebook    | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [dcc5bdef7d](https://linux-hardware.org/?probe=dcc5bdef7d) | Mar 12, 2021 |
| Dell          | Latitude E5470              | Notebook    | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | Notebook    | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | Notebook    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | Notebook    | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | Notebook    | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | Notebook    | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | Notebook    | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [d58331ce9b](https://linux-hardware.org/?probe=d58331ce9b) | Feb 23, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [94f0202173](https://linux-hardware.org/?probe=94f0202173) | Feb 23, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [ce881d4659](https://linux-hardware.org/?probe=ce881d4659) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [6543fc448e](https://linux-hardware.org/?probe=6543fc448e) | Feb 23, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [ce0076fd09](https://linux-hardware.org/?probe=ce0076fd09) | Feb 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | Notebook    | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | Notebook    | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Medion        | E1235T MD99743              | Tablet      | [314aa4d200](https://linux-hardware.org/?probe=314aa4d200) | Feb 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | Notebook    | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | Notebook    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | Notebook    | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [4789c5df48](https://linux-hardware.org/?probe=4789c5df48) | Feb 06, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | Notebook    | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | Notebook    | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | Notebook    | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | Notebook    | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [2e54aedb9e](https://linux-hardware.org/?probe=2e54aedb9e) | Jan 14, 2021 |
| Dell          | Latitude D430               | Notebook    | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [50e5d36672](https://linux-hardware.org/?probe=50e5d36672) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [62ab746796](https://linux-hardware.org/?probe=62ab746796) | Jan 14, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f6a8e9eaf5](https://linux-hardware.org/?probe=f6a8e9eaf5) | Jan 14, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [00e4deffa2](https://linux-hardware.org/?probe=00e4deffa2) | Jan 14, 2021 |
| Dell          | Latitude E5520              | Notebook    | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | Notebook    | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | Notebook    | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | Notebook    | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [98c8e4f3a6](https://linux-hardware.org/?probe=98c8e4f3a6) | Dec 20, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [5783b64146](https://linux-hardware.org/?probe=5783b64146) | Dec 11, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | Notebook    | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [d3e3aa3011](https://linux-hardware.org/?probe=d3e3aa3011) | Nov 28, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [b51d9808ea](https://linux-hardware.org/?probe=b51d9808ea) | Nov 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6a65eeffd1](https://linux-hardware.org/?probe=6a65eeffd1) | Nov 27, 2020 |
| HP            | 1905                        | Desktop     | [03a91e7ecc](https://linux-hardware.org/?probe=03a91e7ecc) | Nov 27, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b7fec4788f](https://linux-hardware.org/?probe=b7fec4788f) | Nov 25, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4f8648d28](https://linux-hardware.org/?probe=d4f8648d28) | Nov 24, 2020 |
| Intel         | MAHOBAY                     | Desktop     | [282590eccb](https://linux-hardware.org/?probe=282590eccb) | Nov 24, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | Notebook    | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [e3ca7996d2](https://linux-hardware.org/?probe=e3ca7996d2) | Nov 13, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | Notebook    | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7bb20fa67](https://linux-hardware.org/?probe=a7bb20fa67) | Nov 08, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | Notebook    | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [c4f4df2ec5](https://linux-hardware.org/?probe=c4f4df2ec5) | Oct 31, 2020 |
| Dell          | 0D28YY A00                  | Desktop     | [584335af3e](https://linux-hardware.org/?probe=584335af3e) | Oct 29, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| Dell          | Latitude 5175               | Tablet      | [5144248c79](https://linux-hardware.org/?probe=5144248c79) | Oct 19, 2020 |
| HP            | Compaq 8510p (KM229AV)      | Notebook    | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | Notebook    | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Hometech      | Wi11T                       | Tablet      | [78d63aeadc](https://linux-hardware.org/?probe=78d63aeadc) | Sep 30, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Dell          | 0M9KCM A02                  | Desktop     | [3e66c830f8](https://linux-hardware.org/?probe=3e66c830f8) | Sep 22, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | Notebook    | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2151aadf5](https://linux-hardware.org/?probe=a2151aadf5) | Sep 14, 2020 |
| HP            | 838B 0100                   | All in one  | [c3133d1a1c](https://linux-hardware.org/?probe=c3133d1a1c) | Sep 09, 2020 |
| HP            | 8265                        | Desktop     | [38f924e8f9](https://linux-hardware.org/?probe=38f924e8f9) | Sep 07, 2020 |
| Teclast       | F5                          | Convertible | [1003072bc5](https://linux-hardware.org/?probe=1003072bc5) | Sep 06, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | Notebook    | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | Notebook    | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | Notebook    | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [f138fd7e0c](https://linux-hardware.org/?probe=f138fd7e0c) | Aug 09, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [e01126d9bd](https://linux-hardware.org/?probe=e01126d9bd) | Aug 06, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [7a48a3ced3](https://linux-hardware.org/?probe=7a48a3ced3) | Aug 06, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2f71e9b242](https://linux-hardware.org/?probe=2f71e9b242) | Aug 03, 2020 |
| HP            | 3031h                       | Desktop     | [205dd10b09](https://linux-hardware.org/?probe=205dd10b09) | Jul 29, 2020 |
| HP            | 3031h                       | Desktop     | [22ebc88fac](https://linux-hardware.org/?probe=22ebc88fac) | Jul 29, 2020 |
| HP            | Pavilion dv7                | Notebook    | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | Notebook    | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [2233b1466b](https://linux-hardware.org/?probe=2233b1466b) | Jul 06, 2020 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [c70f8ee92e](https://linux-hardware.org/?probe=c70f8ee92e) | Jul 06, 2020 |
| Sony          | VPCF23P1E                   | Notebook    | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | Notebook    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | Notebook    | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | Notebook    | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| MSI           | 970A-G43                    | Desktop     | [ada20a047e](https://linux-hardware.org/?probe=ada20a047e) | May 27, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | Notebook    | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [901dfafdbf](https://linux-hardware.org/?probe=901dfafdbf) | May 21, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | Notebook    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [34335c5fb5](https://linux-hardware.org/?probe=34335c5fb5) | Apr 24, 2020 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a7d4e8b1e4](https://linux-hardware.org/?probe=a7d4e8b1e4) | Apr 10, 2020 |
| Samsung       | R780/R778                   | Notebook    | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [0357ef50d4](https://linux-hardware.org/?probe=0357ef50d4) | Apr 05, 2020 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [60ae29c5ac](https://linux-hardware.org/?probe=60ae29c5ac) | Apr 04, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [893f6857b2](https://linux-hardware.org/?probe=893f6857b2) | Apr 04, 2020 |
| ASUSTek       | Z97-E                       | Desktop     | [42c2810369](https://linux-hardware.org/?probe=42c2810369) | Apr 03, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ec1375a9f8](https://linux-hardware.org/?probe=ec1375a9f8) | Apr 02, 2020 |
| MSI           | 760GM-P23                   | Desktop     | [67de432cb4](https://linux-hardware.org/?probe=67de432cb4) | Apr 01, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [67d9f2023b](https://linux-hardware.org/?probe=67d9f2023b) | Apr 01, 2020 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [104b035076](https://linux-hardware.org/?probe=104b035076) | Apr 01, 2020 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [27d1900fba](https://linux-hardware.org/?probe=27d1900fba) | Mar 28, 2020 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [617031b37d](https://linux-hardware.org/?probe=617031b37d) | Mar 28, 2020 |
| Clevo         | P150HMx                     | Notebook    | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [73690787f9](https://linux-hardware.org/?probe=73690787f9) | Mar 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| Dell          | 0F373D A00                  | Desktop     | [2155b32aa1](https://linux-hardware.org/?probe=2155b32aa1) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | Notebook    | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | Notebook    | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | Notebook    | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1243c4a0d9](https://linux-hardware.org/?probe=1243c4a0d9) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | Notebook    | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| HP            | 1790                        | Desktop     | [68a167efd3](https://linux-hardware.org/?probe=68a167efd3) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | Notebook    | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | Notebook    | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [296f21e934](https://linux-hardware.org/?probe=296f21e934) | Mar 03, 2020 |
| Acer          | Aspire 8943G                | Notebook    | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| ASUSTek       | M4A77T                      | Desktop     | [75d0b42f08](https://linux-hardware.org/?probe=75d0b42f08) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | Notebook    | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | Notebook    | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | Notebook    | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | Notebook    | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [ed464b4172](https://linux-hardware.org/?probe=ed464b4172) | Jan 23, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [f703814098](https://linux-hardware.org/?probe=f703814098) | Jan 23, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [e0d3030787](https://linux-hardware.org/?probe=e0d3030787) | Jan 18, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | Notebook    | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [83dca94e72](https://linux-hardware.org/?probe=83dca94e72) | Jan 17, 2020 |
| ASRock        | K8A780LM                    | Desktop     | [a5e0479887](https://linux-hardware.org/?probe=a5e0479887) | Jan 16, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | Notebook    | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [811669dbdd](https://linux-hardware.org/?probe=811669dbdd) | Jan 13, 2020 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [03401edcb4](https://linux-hardware.org/?probe=03401edcb4) | Jan 13, 2020 |
| ASRock        | X370 Gaming X               | Desktop     | [8a0171b4b0](https://linux-hardware.org/?probe=8a0171b4b0) | Jan 13, 2020 |
| Gateway       | SX2185                      | Desktop     | [74f9db3262](https://linux-hardware.org/?probe=74f9db3262) | Jan 13, 2020 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [f10553e785](https://linux-hardware.org/?probe=f10553e785) | Jan 13, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| Dell          | 088DT1 A01                  | Desktop     | [3c957a3758](https://linux-hardware.org/?probe=3c957a3758) | Dec 23, 2019 |
| HP            | Pavilion g6                 | Notebook    | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [2a979257ab](https://linux-hardware.org/?probe=2a979257ab) | Dec 21, 2019 |
| MSI           | MS-7199                     | Desktop     | [8fe7e9e6a6](https://linux-hardware.org/?probe=8fe7e9e6a6) | Dec 21, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [b7165ade10](https://linux-hardware.org/?probe=b7165ade10) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | Notebook    | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | Notebook    | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [c96e6bc37c](https://linux-hardware.org/?probe=c96e6bc37c) | Dec 02, 2019 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [02ae0c5f5b](https://linux-hardware.org/?probe=02ae0c5f5b) | Dec 02, 2019 |
| MSI           | MS-N033                     | Notebook    | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | Notebook    | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| MSI           | B75MA-E33                   | Desktop     | [a08cc9782c](https://linux-hardware.org/?probe=a08cc9782c) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | Notebook    | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | Notebook    | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| Gigabyte      | P43-ES3G                    | Desktop     | [96fa353482](https://linux-hardware.org/?probe=96fa353482) | Nov 07, 2019 |
| Radiant Sy... | P845                        | Mini pc     | [585b07ffaf](https://linux-hardware.org/?probe=585b07ffaf) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | Notebook    | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | Notebook    | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [431ea0cbed](https://linux-hardware.org/?probe=431ea0cbed) | Oct 25, 2019 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | Notebook    | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Dell          | 0F8096                      | Desktop     | [d1f6910c12](https://linux-hardware.org/?probe=d1f6910c12) | Oct 20, 2019 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [f4fcd6e28c](https://linux-hardware.org/?probe=f4fcd6e28c) | Oct 20, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| ZOTAC         | ZBOX-ID18                   | Mini pc     | [4c4d77145b](https://linux-hardware.org/?probe=4c4d77145b) | Oct 20, 2019 |
| ZOTAC         | ZBOX-BI320                  | Mini pc     | [71373d2071](https://linux-hardware.org/?probe=71373d2071) | Oct 20, 2019 |
| ASRock        | H81M-ITX                    | Desktop     | [c5f47f2f27](https://linux-hardware.org/?probe=c5f47f2f27) | Oct 20, 2019 |
| HP            | Pavilion g6                 | Notebook    | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [13dbc6f66d](https://linux-hardware.org/?probe=13dbc6f66d) | Oct 06, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | Notebook    | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | Notebook    | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | Notebook    | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [6a9aa2dd84](https://linux-hardware.org/?probe=6a9aa2dd84) | Jul 22, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [e42fd626b2](https://linux-hardware.org/?probe=e42fd626b2) | Apr 23, 2019 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [8469904453](https://linux-hardware.org/?probe=8469904453) | Apr 17, 2019 |
| ASUSTek       | K55VM                       | Notebook    | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [c68bd6bce7](https://linux-hardware.org/?probe=c68bd6bce7) | Feb 23, 2019 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Acer          | Aspire C22-760              | All in one  | [ff0b5db4bf](https://linux-hardware.org/?probe=ff0b5db4bf) | Dec 18, 2018 |
| Acer          | Aspire C22-760              | All in one  | [7909d2b661](https://linux-hardware.org/?probe=7909d2b661) | Nov 09, 2018 |
| Toshiba       | Satellite C70-B             | Notebook    | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | Notebook    | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| MX 21          | 153       | 38.25%  |
| MX 19          | 139       | 34.75%  |
| MX 20          | 74        | 18.5%   |
| MX 18          | 27        | 6.75%   |
| MX 17          | 4         | 1%      |
| MX 22          | 1         | 0.25%   |
| MX 16-migrated | 1         | 0.25%   |
| MX 16          | 1         | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MX   | 389       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 4.19.0-6-amd64             | 57        | 13.26%  |
| 5.10.0-5mx-amd64           | 20        | 4.65%   |
| 5.10.0-9-amd64             | 18        | 4.19%   |
| 5.10.0-13-amd64            | 18        | 4.19%   |
| 5.8.0-3-amd64              | 15        | 3.49%   |
| 5.6.0-2-amd64              | 15        | 3.49%   |
| 5.10.0-18-amd64            | 14        | 3.26%   |
| 5.14.0-4mx-amd64           | 13        | 3.02%   |
| 5.10.0-16-amd64            | 13        | 3.02%   |
| 5.16.0-5mx-amd64           | 11        | 2.56%   |
| 4.19.0-14-amd64            | 10        | 2.33%   |
| 4.19.0-13-amd64            | 10        | 2.33%   |
| 4.19.0-17-amd64            | 9         | 2.09%   |
| 5.10.0-11-amd64            | 8         | 1.86%   |
| 4.19.0-16-amd64            | 8         | 1.86%   |
| 4.19.0-5-amd64             | 7         | 1.63%   |
| 5.10.0-15-amd64            | 6         | 1.4%    |
| 5.10.0-14-amd64            | 6         | 1.4%    |
| 4.19.0-1-amd64             | 6         | 1.4%    |
| 5.18.0-4mx-amd64           | 5         | 1.16%   |
| 5.10.0-8mx-amd64           | 5         | 1.16%   |
| 4.19.0-18-amd64            | 5         | 1.16%   |
| 4.19.0-12-amd64            | 5         | 1.16%   |
| 5.8.16-antix.1-amd64-smp   | 4         | 0.93%   |
| 5.4.0-3-amd64              | 4         | 0.93%   |
| 5.10.0-17-amd64            | 4         | 0.93%   |
| 5.10.0-10-amd64            | 4         | 0.93%   |
| 4.19.0-11-amd64            | 4         | 0.93%   |
| 4.15.0-1-amd64             | 4         | 0.93%   |
| 5.2.21-antix.2-amd64-smp   | 3         | 0.7%    |
| 5.16.0-6mx-amd64           | 3         | 0.7%    |
| 4.19.0-9-amd64             | 3         | 0.7%    |
| 5.6.10-antix.1-amd64-smp   | 2         | 0.47%   |
| 5.5.0-9.1-liquorix-amd64   | 2         | 0.47%   |
| 5.4.7-antix.1-amd64-smp    | 2         | 0.47%   |
| 5.3.0-10.1-liquorix-amd64  | 2         | 0.47%   |
| 5.19.0-2mx-amd64           | 2         | 0.47%   |
| 5.16.0-4mx-amd64           | 2         | 0.47%   |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.47%   |
| 5.15.0-1mx-amd64           | 2         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.19.0   | 131       | 31.8%   |
| 5.10.0   | 129       | 31.31%  |
| 5.16.0   | 19        | 4.61%   |
| 5.6.0    | 17        | 4.13%   |
| 5.14.0   | 16        | 3.88%   |
| 5.8.0    | 15        | 3.64%   |
| 5.4.0    | 8         | 1.94%   |
| 5.18.0   | 7         | 1.7%    |
| 5.5.0    | 6         | 1.46%   |
| 4.15.0   | 6         | 1.46%   |
| 5.19.0   | 5         | 1.21%   |
| 5.17.0   | 5         | 1.21%   |
| 5.15.0   | 5         | 1.21%   |
| 5.8.16   | 4         | 0.97%   |
| 5.3.0    | 4         | 0.97%   |
| 5.2.21   | 4         | 0.97%   |
| 5.6.10   | 3         | 0.73%   |
| 5.4.7    | 2         | 0.49%   |
| 5.11.0   | 2         | 0.49%   |
| 4.9.193  | 2         | 0.49%   |
| 4.18.0   | 2         | 0.49%   |
| 6.0.5    | 1         | 0.24%   |
| 5.9.1    | 1         | 0.24%   |
| 5.7.0    | 1         | 0.24%   |
| 5.4.10   | 1         | 0.24%   |
| 5.3.10   | 1         | 0.24%   |
| 5.2.8    | 1         | 0.24%   |
| 5.2.15   | 1         | 0.24%   |
| 5.2.0    | 1         | 0.24%   |
| 5.13.0   | 1         | 0.24%   |
| 5.10.82  | 1         | 0.24%   |
| 5.10.52  | 1         | 0.24%   |
| 5.10.111 | 1         | 0.24%   |
| 5.10.1   | 1         | 0.24%   |
| 5.1.2    | 1         | 0.24%   |
| 5.0.0    | 1         | 0.24%   |
| 4.9.91   | 1         | 0.24%   |
| 4.9.246  | 1         | 0.24%   |
| 4.9.189  | 1         | 0.24%   |
| 4.19.174 | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 133       | 32.28%  |
| 4.19    | 132       | 32.04%  |
| 5.6     | 20        | 4.85%   |
| 5.8     | 19        | 4.61%   |
| 5.16    | 19        | 4.61%   |
| 5.14    | 16        | 3.88%   |
| 5.4     | 11        | 2.67%   |
| 5.2     | 7         | 1.7%    |
| 5.18    | 7         | 1.7%    |
| 5.5     | 6         | 1.46%   |
| 4.15    | 6         | 1.46%   |
| 5.3     | 5         | 1.21%   |
| 5.19    | 5         | 1.21%   |
| 5.17    | 5         | 1.21%   |
| 5.15    | 5         | 1.21%   |
| 4.9     | 5         | 1.21%   |
| 5.11    | 2         | 0.49%   |
| 4.18    | 2         | 0.49%   |
| 6.0     | 1         | 0.24%   |
| 5.9     | 1         | 0.24%   |
| 5.7     | 1         | 0.24%   |
| 5.13    | 1         | 0.24%   |
| 5.1     | 1         | 0.24%   |
| 5.0     | 1         | 0.24%   |
| 3.16    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 368       | 94.36%  |
| i686   | 22        | 5.64%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 292       | 73.55%  |
| KDE5             | 60        | 15.11%  |
| Unknown          | 8         | 2.02%   |
| Budgie           | 7         | 1.76%   |
| i3               | 5         | 1.26%   |
| MATE             | 4         | 1.01%   |
| LXQt             | 4         | 1.01%   |
| GNOME            | 3         | 0.76%   |
| X-Cinnamon       | 2         | 0.5%    |
| lightdm-xsession | 2         | 0.5%    |
| Cinnamon         | 2         | 0.5%    |
| Trinity          | 1         | 0.25%   |
| spectrwm         | 1         | 0.25%   |
| LXDE             | 1         | 0.25%   |
| KDE4             | 1         | 0.25%   |
| KDE              | 1         | 0.25%   |
| GNOME Flashback  | 1         | 0.25%   |
| GNOME Classic    | 1         | 0.25%   |
| fluxbox          | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 386       | 99.23%  |
| Tty  | 3         | 0.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 320       | 81.22%  |
| SDDM    | 50        | 12.69%  |
| TDM     | 13        | 3.3%    |
| SLiM    | 8         | 2.03%   |
| Unknown | 2         | 0.51%   |
| GDM     | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 137       | 33.83%  |
| Unknown | 102       | 25.19%  |
| de_DE   | 41        | 10.12%  |
| en_GB   | 19        | 4.69%   |
| sk_SK   | 12        | 2.96%   |
| it_IT   | 11        | 2.72%   |
| es_ES   | 11        | 2.72%   |
| ru_RU   | 9         | 2.22%   |
| pt_BR   | 9         | 2.22%   |
| pl_PL   | 7         | 1.73%   |
| fr_FR   | 7         | 1.73%   |
| tr_TR   | 5         | 1.23%   |
| en_AU   | 4         | 0.99%   |
| en_NZ   | 3         | 0.74%   |
| en_IE   | 3         | 0.74%   |
| de_CH   | 3         | 0.74%   |
| uk_UA   | 2         | 0.49%   |
| hu_HU   | 2         | 0.49%   |
| fi_FI   | 2         | 0.49%   |
| es_MX   | 2         | 0.49%   |
| es_CO   | 2         | 0.49%   |
| zh_CN   | 1         | 0.25%   |
| sv_SE   | 1         | 0.25%   |
| nl_NL   | 1         | 0.25%   |
| nb_NO   | 1         | 0.25%   |
| id_ID   | 1         | 0.25%   |
| fr_CH   | 1         | 0.25%   |
| fr_BE   | 1         | 0.25%   |
| es_VE   | 1         | 0.25%   |
| es_UY   | 1         | 0.25%   |
| es_PE   | 1         | 0.25%   |
| cs_CZ   | 1         | 0.25%   |
| bg_BG   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 198       | 50.9%   |
| BIOS | 191       | 49.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 340       | 86.96%  |
| Overlay  | 35        | 8.95%   |
| Btrfs    | 9         | 2.3%    |
| Xfs      | 2         | 0.51%   |
| Unknown  | 2         | 0.51%   |
| Reiserfs | 1         | 0.26%   |
| F2fs     | 1         | 0.26%   |
| Ext3     | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 242       | 61.89%  |
| MBR     | 142       | 36.32%  |
| Unknown | 7         | 1.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 292       | 73.18%  |
| Yes       | 107       | 26.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 52.43%  |
| Yes       | 186       | 47.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 60        | 15.42%  |
| ASUSTek Computer            | 54        | 13.88%  |
| Hewlett-Packard             | 50        | 12.85%  |
| Dell                        | 46        | 11.83%  |
| Acer                        | 24        | 6.17%   |
| Gigabyte Technology         | 23        | 5.91%   |
| MSI                         | 21        | 5.4%    |
| ASRock                      | 12        | 3.08%   |
| Apple                       | 12        | 3.08%   |
| Intel                       | 9         | 2.31%   |
| Toshiba                     | 8         | 2.06%   |
| Sony                        | 8         | 2.06%   |
| Medion                      | 7         | 1.8%    |
| Samsung Electronics         | 5         | 1.29%   |
| Fujitsu Siemens             | 4         | 1.03%   |
| ZOTAC                       | 3         | 0.77%   |
| Alienware                   | 3         | 0.77%   |
| Notebook                    | 2         | 0.51%   |
| Google                      | 2         | 0.51%   |
| Clevo                       | 2         | 0.51%   |
| Biostar                     | 2         | 0.51%   |
| Unknown                     | 2         | 0.51%   |
| win element                 | 1         | 0.26%   |
| Vulcan Electronics          | 1         | 0.26%   |
| UMAX                        | 1         | 0.26%   |
| TUXEDO                      | 1         | 0.26%   |
| Teclast                     | 1         | 0.26%   |
| Sun Microsystems            | 1         | 0.26%   |
| Shenzhen Wangang Technology | 1         | 0.26%   |
| SANTECH                     | 1         | 0.26%   |
| Radiant Systems             | 1         | 0.26%   |
| Pixus                       | 1         | 0.26%   |
| Pegatron                    | 1         | 0.26%   |
| Panasonic                   | 1         | 0.26%   |
| Packard Bell                | 1         | 0.26%   |
| MP                          | 1         | 0.26%   |
| Microsoft                   | 1         | 0.26%   |
| Irbis                       | 1         | 0.26%   |
| IBM                         | 1         | 0.26%   |
| Huanan                      | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Unknown                                      | 5         | 1.29%   |
| ASUS All Series                              | 4         | 1.03%   |
| MSI MS-7A34                                  | 2         | 0.51%   |
| HP Stream Laptop 14-cb0XX                    | 2         | 0.51%   |
| HP ProBook 650 G1                            | 2         | 0.51%   |
| Dell Studio 540                              | 2         | 0.51%   |
| Dell OptiPlex 9010                           | 2         | 0.51%   |
| Dell OptiPlex 755                            | 2         | 0.51%   |
| ASUS PRIME B450M-A                           | 2         | 0.51%   |
| ASRock K8A780LM                              | 2         | 0.51%   |
| Apple MacBookAir7,2                          | 2         | 0.51%   |
| ZOTAC ZBOX-ID18                              | 1         | 0.26%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.26%   |
| ZOTAC ZBOX-BI320                             | 1         | 0.26%   |
| win element MoreFine S500+                   | 1         | 0.26%   |
| Vulcan Excursion XB                          | 1         | 0.26%   |
| UMAX VisionBook-N12R                         | 1         | 0.26%   |
| TUXEDO N7x0WU                                | 1         | 0.26%   |
| Toshiba Satellite P875                       | 1         | 0.26%   |
| Toshiba Satellite L850-CJK                   | 1         | 0.26%   |
| Toshiba Satellite C845                       | 1         | 0.26%   |
| Toshiba Satellite C70-B                      | 1         | 0.26%   |
| Toshiba Satellite C660                       | 1         | 0.26%   |
| Toshiba Satellite C50-A-12K                  | 1         | 0.26%   |
| Toshiba Satellite A300                       | 1         | 0.26%   |
| Toshiba PORTEGE R705                         | 1         | 0.26%   |
| Teclast F5                                   | 1         | 0.26%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.26%   |
| Sony VPCSB1V9R                               | 1         | 0.26%   |
| Sony VPCF23P1E                               | 1         | 0.26%   |
| Sony VPCF119FX                               | 1         | 0.26%   |
| Sony VPCEH2N1E                               | 1         | 0.26%   |
| Sony VPCEC3S1E                               | 1         | 0.26%   |
| Sony VGN-NR310FH                             | 1         | 0.26%   |
| Sony SVT13115FBS                             | 1         | 0.26%   |
| Sony SVE1513Q1ESI                            | 1         | 0.26%   |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.26%   |
| SANTECH X170KM-G                             | 1         | 0.26%   |
| Samsung R780/R778                            | 1         | 0.26%   |
| Samsung NC210/NC110                          | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 37        | 9.51%   |
| Acer Aspire             | 14        | 3.6%    |
| Dell Latitude           | 13        | 3.34%   |
| Dell OptiPlex           | 10        | 2.57%   |
| Dell Inspiron           | 9         | 2.31%   |
| Toshiba Satellite       | 7         | 1.8%    |
| HP ProBook              | 7         | 1.8%    |
| HP Pavilion             | 7         | 1.8%    |
| Lenovo IdeaPad          | 6         | 1.54%   |
| HP EliteBook            | 5         | 1.29%   |
| ASUS TUF                | 5         | 1.29%   |
| ASUS ROG                | 5         | 1.29%   |
| ASUS PRIME              | 5         | 1.29%   |
| Unknown                 | 5         | 1.29%   |
| HP Laptop               | 4         | 1.03%   |
| Dell Vostro             | 4         | 1.03%   |
| ASUS All                | 4         | 1.03%   |
| HP Spectre              | 3         | 0.77%   |
| HP ENVY                 | 3         | 0.77%   |
| HP Compaq               | 3         | 0.77%   |
| MSI MS-7A34             | 2         | 0.51%   |
| Medion Akoya            | 2         | 0.51%   |
| Lenovo B590             | 2         | 0.51%   |
| HP ZBook                | 2         | 0.51%   |
| HP Stream               | 2         | 0.51%   |
| Gigabyte Z390           | 2         | 0.51%   |
| Gigabyte B550M          | 2         | 0.51%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.51%   |
| Dell Studio             | 2         | 0.51%   |
| Dell Precision          | 2         | 0.51%   |
| ASUS ZenBook            | 2         | 0.51%   |
| ASUS VivoBook           | 2         | 0.51%   |
| ASUS P5GC-MX            | 2         | 0.51%   |
| ASRock K8A780LM         | 2         | 0.51%   |
| Apple MacBookPro11      | 2         | 0.51%   |
| Apple MacBookAir7       | 2         | 0.51%   |
| Alienware m15           | 2         | 0.51%   |
| Acer Swift              | 2         | 0.51%   |
| Acer Nitro              | 2         | 0.51%   |
| Acer Extensa            | 2         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 40        | 10.28%  |
| 2011    | 36        | 9.25%   |
| 2012    | 32        | 8.23%   |
| 2010    | 32        | 8.23%   |
| 2021    | 30        | 7.71%   |
| 2013    | 29        | 7.46%   |
| 2020    | 27        | 6.94%   |
| 2019    | 22        | 5.66%   |
| 2017    | 22        | 5.66%   |
| 2015    | 21        | 5.4%    |
| 2014    | 21        | 5.4%    |
| 2016    | 19        | 4.88%   |
| 2008    | 18        | 4.63%   |
| 2007    | 13        | 3.34%   |
| 2009    | 11        | 2.83%   |
| 2006    | 6         | 1.54%   |
| 2022    | 5         | 1.29%   |
| 2005    | 4         | 1.03%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 233       | 59.9%   |
| Desktop     | 121       | 31.11%  |
| Convertible | 11        | 2.83%   |
| Mini pc     | 10        | 2.57%   |
| Tablet      | 7         | 1.8%    |
| All in one  | 4         | 1.03%   |
| Server      | 3         | 0.77%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 387       | 99.49%  |
| Enabled  | 2         | 0.51%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 385       | 98.97%  |
| Yes  | 4         | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 93        | 23.79%  |
| 8.01-16.0   | 80        | 20.46%  |
| 3.01-4.0    | 67        | 17.14%  |
| 16.01-24.0  | 67        | 17.14%  |
| 32.01-64.0  | 33        | 8.44%   |
| 1.01-2.0    | 28        | 7.16%   |
| 2.01-3.0    | 9         | 2.3%    |
| 0.51-1.0    | 6         | 1.53%   |
| 24.01-32.0  | 5         | 1.28%   |
| 64.01-256.0 | 3         | 0.77%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 151       | 36.21%  |
| 2.01-3.0   | 101       | 24.22%  |
| 3.01-4.0   | 59        | 14.15%  |
| 0.51-1.0   | 46        | 11.03%  |
| 4.01-8.0   | 42        | 10.07%  |
| 8.01-16.0  | 12        | 2.88%   |
| 0.01-0.5   | 5         | 1.2%    |
| 16.01-24.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 228       | 57.14%  |
| 2      | 107       | 26.82%  |
| 3      | 38        | 9.52%   |
| 4      | 11        | 2.76%   |
| 5      | 8         | 2.01%   |
| 0      | 5         | 1.25%   |
| 8      | 1         | 0.25%   |
| 6      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 236       | 60.36%  |
| Yes       | 155       | 39.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 87.92%  |
| No        | 47        | 12.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 297       | 76.15%  |
| No        | 93        | 23.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 56.41%  |
| No        | 170       | 43.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 92        | 23.59%  |
| Germany     | 43        | 11.03%  |
| UK          | 19        | 4.87%   |
| Italy       | 19        | 4.87%   |
| Slovakia    | 17        | 4.36%   |
| Spain       | 14        | 3.59%   |
| Russia      | 13        | 3.33%   |
| Canada      | 13        | 3.33%   |
| Brazil      | 12        | 3.08%   |
| France      | 11        | 2.82%   |
| Poland      | 10        | 2.56%   |
| India       | 10        | 2.56%   |
| Netherlands | 9         | 2.31%   |
| Australia   | 8         | 2.05%   |
| Finland     | 7         | 1.79%   |
| Austria     | 7         | 1.79%   |
| Ukraine     | 5         | 1.28%   |
| Turkey      | 5         | 1.28%   |
| Serbia      | 5         | 1.28%   |
| Mexico      | 5         | 1.28%   |
| Switzerland | 4         | 1.03%   |
| Sweden      | 4         | 1.03%   |
| Indonesia   | 4         | 1.03%   |
| Thailand    | 3         | 0.77%   |
| New Zealand | 3         | 0.77%   |
| Hungary     | 3         | 0.77%   |
| Czechia     | 3         | 0.77%   |
| Colombia    | 3         | 0.77%   |
| Belgium     | 3         | 0.77%   |
| Vietnam     | 2         | 0.51%   |
| Venezuela   | 2         | 0.51%   |
| Romania     | 2         | 0.51%   |
| Portugal    | 2         | 0.51%   |
| Philippines | 2         | 0.51%   |
| Norway      | 2         | 0.51%   |
| Greece      | 2         | 0.51%   |
| Denmark     | 2         | 0.51%   |
| China       | 2         | 0.51%   |
| Chile       | 2         | 0.51%   |
| Belarus     | 2         | 0.51%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Bratislava       | 16        | 3.98%   |
| Vienna           | 7         | 1.74%   |
| Berlin           | 7         | 1.74%   |
| Warsaw           | 3         | 0.75%   |
| St Petersburg    | 3         | 0.75%   |
| Patna            | 3         | 0.75%   |
| Oxford           | 3         | 0.75%   |
| Munich           | 3         | 0.75%   |
| Montreal         | 3         | 0.75%   |
| Madrid           | 3         | 0.75%   |
| Los Angeles      | 3         | 0.75%   |
| Istanbul         | 3         | 0.75%   |
| Helsinki         | 3         | 0.75%   |
| Cambridge        | 3         | 0.75%   |
| Buffalo          | 3         | 0.75%   |
| Bogotá          | 3         | 0.75%   |
| Belgrade         | 3         | 0.75%   |
| Barcelona        | 3         | 0.75%   |
| Walled Lake      | 2         | 0.5%    |
| Vasco da Gama    | 2         | 0.5%    |
| Valencia         | 2         | 0.5%    |
| Tacoma           | 2         | 0.5%    |
| Sydney           | 2         | 0.5%    |
| Rome             | 2         | 0.5%    |
| Prague           | 2         | 0.5%    |
| Portland         | 2         | 0.5%    |
| Orange           | 2         | 0.5%    |
| Nashville        | 2         | 0.5%    |
| Moscow           | 2         | 0.5%    |
| Minsk            | 2         | 0.5%    |
| Milan            | 2         | 0.5%    |
| Melbourne        | 2         | 0.5%    |
| Ho Chi Minh City | 2         | 0.5%    |
| Hamburg          | 2         | 0.5%    |
| Ettingen         | 2         | 0.5%    |
| Doesburg         | 2         | 0.5%    |
| Dnipro           | 2         | 0.5%    |
| Centreville      | 2         | 0.5%    |
| Casale Litta     | 2         | 0.5%    |
| Canberra         | 2         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 89        | 103    | 15.29%  |
| Samsung Electronics | 84        | 115    | 14.43%  |
| Seagate             | 81        | 105    | 13.92%  |
| Kingston            | 40        | 41     | 6.87%   |
| Crucial             | 34        | 51     | 5.84%   |
| Toshiba             | 30        | 36     | 5.15%   |
| SanDisk             | 26        | 30     | 4.47%   |
| Unknown             | 25        | 32     | 4.3%    |
| Hitachi             | 25        | 31     | 4.3%    |
| SK hynix            | 14        | 15     | 2.41%   |
| Intel               | 14        | 21     | 2.41%   |
| A-DATA Technology   | 11        | 13     | 1.89%   |
| HGST                | 8         | 13     | 1.37%   |
| PNY                 | 6         | 7      | 1.03%   |
| GOODRAM             | 6         | 7      | 1.03%   |
| Apple               | 6         | 9      | 1.03%   |
| Transcend           | 5         | 5      | 0.86%   |
| Maxtor              | 5         | 6      | 0.86%   |
| Corsair             | 5         | 5      | 0.86%   |
| SPCC                | 4         | 4      | 0.69%   |
| Micron Technology   | 4         | 8      | 0.69%   |
| LITEON              | 4         | 4      | 0.69%   |
| Fujitsu             | 3         | 3      | 0.52%   |
| Dogfish             | 3         | 3      | 0.52%   |
| Team                | 2         | 2      | 0.34%   |
| Phison              | 2         | 2      | 0.34%   |
| OCZ                 | 2         | 2      | 0.34%   |
| Netac               | 2         | 2      | 0.34%   |
| Mushkin             | 2         | 2      | 0.34%   |
| KIOXIA              | 2         | 3      | 0.34%   |
| KingSpec            | 2         | 2      | 0.34%   |
| KingFast            | 2         | 2      | 0.34%   |
| KingDian            | 2         | 2      | 0.34%   |
| Intenso             | 2         | 2      | 0.34%   |
| Indilinx            | 2         | 4      | 0.34%   |
| Gigabyte Technology | 2         | 2      | 0.34%   |
| ASMT                | 2         | 4      | 0.34%   |
| Unknown             | 2         | 2      | 0.34%   |
| ZTC                 | 1         | 1      | 0.17%   |
| Yeyian              | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB        | 9         | 1.41%   |
| Kingston SA400S37480G 480GB SSD  | 8         | 1.26%   |
| Kingston SA400S37240G 240GB SSD  | 7         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB   | 6         | 0.94%   |
| Samsung SSD 850 EVO 250GB        | 6         | 0.94%   |
| Crucial CT120BX500SSD1 120GB     | 6         | 0.94%   |
| Seagate ST2000DM008-2FR102 2TB   | 5         | 0.78%   |
| Samsung SSD 970 EVO Plus 1TB     | 5         | 0.78%   |
| Kingston SV300S37A120G 120GB SSD | 5         | 0.78%   |
| Toshiba DT01ACA100 1TB           | 4         | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB   | 4         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB   | 4         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB   | 4         | 0.63%   |
| Samsung SSD 980 PRO 1TB          | 4         | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 4         | 0.63%   |
| Hitachi HTS543232A7A384 320GB    | 4         | 0.63%   |
| Crucial CT500MX500SSD1 500GB     | 4         | 0.63%   |
| A-DATA SP600 32GB SSD            | 4         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB         | 3         | 0.47%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 3         | 0.47%   |
| Unknown SD32G  32GB              | 3         | 0.47%   |
| Toshiba MQ01ABF050 500GB         | 3         | 0.47%   |
| Seagate ST500DM002-1BD142 500GB  | 3         | 0.47%   |
| Seagate ST3500413AS 500GB        | 3         | 0.47%   |
| SanDisk SDSSDA120G 120GB         | 3         | 0.47%   |
| Samsung SSD 970 EVO 1TB          | 3         | 0.47%   |
| Samsung SSD 860 EVO 1TB          | 3         | 0.47%   |
| Samsung SSD 850 EVO 500GB        | 3         | 0.47%   |
| Samsung SSD 840 EVO 250GB        | 3         | 0.47%   |
| Samsung SSD 830 Series 128GB     | 3         | 0.47%   |
| Intel SSDPEKNW512G8 512GB        | 3         | 0.47%   |
| HGST HTS541010A9E680 1TB         | 3         | 0.47%   |
| Crucial CT240BX500SSD1 240GB     | 3         | 0.47%   |
| Crucial CT1000MX500SSD1 1TB      | 3         | 0.47%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 2         | 0.31%   |
| WDC WDS100T1X0E-00AFY0 1TB       | 2         | 0.31%   |
| WDC WD60EZRZ-00RWYB1 6TB         | 2         | 0.31%   |
| WDC WD60EFRX-68L0BN1 6TB         | 2         | 0.31%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 0.31%   |
| WDC WD5000LPCX-24VHAT0 500GB     | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 81        | 104    | 36.32%  |
| WDC                 | 66        | 78     | 29.6%   |
| Hitachi             | 25        | 31     | 11.21%  |
| Toshiba             | 23        | 29     | 10.31%  |
| Samsung Electronics | 8         | 10     | 3.59%   |
| HGST                | 8         | 13     | 3.59%   |
| Maxtor              | 5         | 6      | 2.24%   |
| Fujitsu             | 3         | 3      | 1.35%   |
| Unknown             | 1         | 1      | 0.45%   |
| SABRENT             | 1         | 1      | 0.45%   |
| IBM/Hitachi         | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 52        | 66     | 21.4%   |
| Kingston            | 33        | 34     | 13.58%  |
| Crucial             | 31        | 42     | 12.76%  |
| SanDisk             | 24        | 27     | 9.88%   |
| WDC                 | 10        | 11     | 4.12%   |
| A-DATA Technology   | 10        | 12     | 4.12%   |
| GOODRAM             | 6         | 7      | 2.47%   |
| Transcend           | 5         | 5      | 2.06%   |
| SK hynix            | 5         | 5      | 2.06%   |
| PNY                 | 5         | 5      | 2.06%   |
| Intel               | 5         | 9      | 2.06%   |
| Apple               | 5         | 7      | 2.06%   |
| SPCC                | 4         | 4      | 1.65%   |
| LITEON              | 4         | 4      | 1.65%   |
| Micron Technology   | 3         | 7      | 1.23%   |
| Dogfish             | 3         | 3      | 1.23%   |
| Toshiba             | 2         | 2      | 0.82%   |
| OCZ                 | 2         | 2      | 0.82%   |
| Netac               | 2         | 2      | 0.82%   |
| KingSpec            | 2         | 2      | 0.82%   |
| KingFast            | 2         | 2      | 0.82%   |
| KingDian            | 2         | 2      | 0.82%   |
| Intenso             | 2         | 2      | 0.82%   |
| Indilinx            | 2         | 4      | 0.82%   |
| Gigabyte Technology | 2         | 2      | 0.82%   |
| ASMT                | 2         | 4      | 0.82%   |
| ZTC                 | 1         | 1      | 0.41%   |
| Yeyian              | 1         | 1      | 0.41%   |
| WDC WDS1            | 1         | 1      | 0.41%   |
| Teclast             | 1         | 1      | 0.41%   |
| Team                | 1         | 1      | 0.41%   |
| Smart               | 1         | 1      | 0.41%   |
| Phison              | 1         | 1      | 0.41%   |
| Patriot             | 1         | 1      | 0.41%   |
| Mushkin             | 1         | 1      | 0.41%   |
| MMY                 | 1         | 1      | 0.41%   |
| LITEONIT            | 1         | 1      | 0.41%   |
| HS-SSD-C100         | 1         | 1      | 0.41%   |
| GeIL                | 1         | 1      | 0.41%   |
| CT1000MX            | 1         | 1      | 0.41%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 207       | 290    | 40.12%  |
| HDD     | 190       | 278    | 36.82%  |
| NVMe    | 89        | 116    | 17.25%  |
| MMC     | 28        | 37     | 5.43%   |
| Unknown | 2         | 2      | 0.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 310       | 554    | 70.94%  |
| NVMe | 89        | 116    | 20.37%  |
| MMC  | 28        | 37     | 6.41%   |
| SAS  | 10        | 16     | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 259       | 369    | 63.64%  |
| 0.51-1.0   | 105       | 144    | 25.8%   |
| 1.01-2.0   | 24        | 30     | 5.9%    |
| 3.01-4.0   | 8         | 9      | 1.97%   |
| 2.01-3.0   | 7         | 8      | 1.72%   |
| 4.01-10.0  | 4         | 8      | 0.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 112       | 27.59%  |
| 251-500        | 74        | 18.23%  |
| 501-1000       | 60        | 14.78%  |
| 51-100         | 46        | 11.33%  |
| 21-50          | 32        | 7.88%   |
| 1001-2000      | 32        | 7.88%   |
| More than 3000 | 19        | 4.68%   |
| 1-20           | 19        | 4.68%   |
| 2001-3000      | 10        | 2.46%   |
| Unknown        | 2         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 150       | 36.5%   |
| 21-50          | 60        | 14.6%   |
| 101-250        | 60        | 14.6%   |
| 51-100         | 49        | 11.92%  |
| 251-500        | 44        | 10.71%  |
| 501-1000       | 20        | 4.87%   |
| 1001-2000      | 14        | 3.41%   |
| More than 3000 | 7         | 1.7%    |
| 2001-3000      | 5         | 1.22%   |
| Unknown        | 2         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 3         | 3      | 3.26%   |
| Toshiba MK7575GSX 752GB             | 2         | 3      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 2.17%   |
| Indilinx IND-S325S120G 120GB SSD    | 2         | 4      | 2.17%   |
| A-DATA Technology SU650 240GB SSD   | 2         | 2      | 2.17%   |
| WDC WDS100T2B0A-00SM50 1TB SSD      | 1         | 1      | 1.09%   |
| WDC WD5003ABYX-01WERA1 500GB        | 1         | 1      | 1.09%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.09%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 1      | 1.09%   |
| WDC WD5000AAKS-40V6A0 500GB         | 1         | 1      | 1.09%   |
| WDC WD3200LPVX-22V0TT0 320GB        | 1         | 1      | 1.09%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 1.09%   |
| WDC WD3200BEKT-60PVMT0 320GB        | 1         | 1      | 1.09%   |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 1      | 1.09%   |
| WDC WD20EARX-00PASB0 2TB            | 1         | 1      | 1.09%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 1         | 1      | 1.09%   |
| WDC WD1600BEVT-22A23T0 160GB        | 1         | 1      | 1.09%   |
| WDC WD1600AVVS-63L2B0 160GB         | 1         | 1      | 1.09%   |
| WDC WD15EADS-11P8B2 1TB             | 1         | 1      | 1.09%   |
| WDC WD10EZEX-75WN4A0 1TB            | 1         | 1      | 1.09%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 1.09%   |
| WDC WD10EAVS-00D7B1 1TB             | 1         | 1      | 1.09%   |
| WDC WD10EADS-98M2B0 1TB             | 1         | 1      | 1.09%   |
| WDC WD10EADS-00M2B0 1TB             | 1         | 1      | 1.09%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.09%   |
| Toshiba MK6465GSX 640GB             | 1         | 1      | 1.09%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 1.09%   |
| Toshiba MK2565GSX 250GB             | 1         | 1      | 1.09%   |
| SPCC Solid State Disk 512GB         | 1         | 1      | 1.09%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 1.09%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.09%   |
| Seagate ST9320421AS 320GB           | 1         | 1      | 1.09%   |
| Seagate ST9160821AS 160GB           | 1         | 1      | 1.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 1.09%   |
| Seagate ST500LM021-1KJ152 500GB     | 1         | 1      | 1.09%   |
| Seagate ST380815AS 80GB             | 1         | 1      | 1.09%   |
| Seagate ST3750330NS 752GB           | 1         | 1      | 1.09%   |
| Seagate ST3500820AS 500GB           | 1         | 1      | 1.09%   |
| Seagate ST3500413AS 500GB           | 1         | 1      | 1.09%   |
| Seagate ST3360320AS 360GB           | 1         | 1      | 1.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 26.67%  |
| WDC                 | 19        | 19     | 21.11%  |
| Hitachi             | 10        | 11     | 11.11%  |
| Samsung Electronics | 7         | 10     | 7.78%   |
| Toshiba             | 6         | 7      | 6.67%   |
| Maxtor              | 4         | 4      | 4.44%   |
| Crucial             | 4         | 9      | 4.44%   |
| HGST                | 3         | 4      | 3.33%   |
| Indilinx            | 2         | 4      | 2.22%   |
| Fujitsu             | 2         | 2      | 2.22%   |
| A-DATA Technology   | 2         | 2      | 2.22%   |
| SPCC                | 1         | 1      | 1.11%   |
| SanDisk             | 1         | 1      | 1.11%   |
| Kingston            | 1         | 1      | 1.11%   |
| Intenso             | 1         | 1      | 1.11%   |
| Intel               | 1         | 2      | 1.11%   |
| IBM/Hitachi         | 1         | 1      | 1.11%   |
| GOODRAM             | 1         | 1      | 1.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 26     | 34.29%  |
| WDC                 | 18        | 18     | 25.71%  |
| Hitachi             | 10        | 11     | 14.29%  |
| Toshiba             | 6         | 7      | 8.57%   |
| Maxtor              | 4         | 4      | 5.71%   |
| HGST                | 3         | 4      | 4.29%   |
| Samsung Electronics | 2         | 4      | 2.86%   |
| Fujitsu             | 2         | 2      | 2.86%   |
| IBM/Hitachi         | 1         | 1      | 1.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 67        | 77     | 77.01%  |
| SSD  | 18        | 21     | 20.69%  |
| NVMe | 2         | 8      | 2.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB   | 2         | 2      | 66.67%  |
| Seagate ST3500418AS 500GB | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| Seagate | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 317       | 550    | 70.29%  |
| Malfunc  | 83        | 106    | 18.4%   |
| Detected | 48        | 63     | 10.64%  |
| Failed   | 3         | 4      | 0.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 270       | 58.82%  |
| AMD                          | 62        | 13.51%  |
| Samsung Electronics          | 37        | 8.06%   |
| SanDisk                      | 14        | 3.05%   |
| Nvidia                       | 11        | 2.4%    |
| SK hynix                     | 8         | 1.74%   |
| Phison Electronics           | 8         | 1.74%   |
| ASMedia Technology           | 8         | 1.74%   |
| Kingston Technology Company  | 7         | 1.53%   |
| JMicron Technology           | 7         | 1.53%   |
| Micron/Crucial Technology    | 4         | 0.87%   |
| Marvell Technology Group     | 4         | 0.87%   |
| KIOXIA                       | 4         | 0.87%   |
| Toshiba America Info Systems | 3         | 0.65%   |
| Silicon Motion               | 3         | 0.65%   |
| ULi Electronics              | 2         | 0.44%   |
| VIA Technologies             | 1         | 0.22%   |
| Silicon Image                | 1         | 0.22%   |
| Micron Technology            | 1         | 0.22%   |
| Lenovo                       | 1         | 0.22%   |
| Hewlett-Packard              | 1         | 0.22%   |
| Broadcom / LSI               | 1         | 0.22%   |
| ADATA Technology             | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 7.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 4.87%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 20        | 3.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 17        | 3.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 16        | 3%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 13        | 2.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 2.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 1.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 8         | 1.5%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 8         | 1.5%    |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 7         | 1.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 1.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.12%   |
| Phison E12 NVMe Controller                                                     | 6         | 1.12%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.12%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 1.12%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 0.94%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5         | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 5         | 0.94%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 5         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 0.75%   |
| Intel SSD 660P Series                                                          | 4         | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.75%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 286       | 61.37%  |
| NVMe | 88        | 18.88%  |
| IDE  | 65        | 13.95%  |
| RAID | 26        | 5.58%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 310       | 79.69%  |
| AMD          | 78        | 20.05%  |
| CentaurHauls | 1         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 1.54%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 6         | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 1.29%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 4         | 1.03%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 4         | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.03%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 4         | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 0.77%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 3         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.77%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 0.77%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 3         | 0.77%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 3         | 0.77%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 0.77%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3         | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 0.77%   |
| AMD Ryzen 5 1600X Six-Core Processor    | 3         | 0.77%   |
| Intel Pentium CPU G3240 @ 3.10GHz       | 2         | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 0.51%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 2         | 0.51%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.51%   |
| Intel Core i7-5820K CPU @ 3.30GHz       | 2         | 0.51%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.51%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 2         | 0.51%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.51%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.51%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.51%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 2         | 0.51%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 83        | 21.34%  |
| Intel Core i7           | 74        | 19.02%  |
| Intel Core i3           | 30        | 7.71%   |
| Intel Celeron           | 28        | 7.2%    |
| Other                   | 21        | 5.4%    |
| Intel Core 2 Duo        | 19        | 4.88%   |
| AMD Ryzen 7             | 19        | 4.88%   |
| Intel Atom              | 18        | 4.63%   |
| AMD Ryzen 5             | 16        | 4.11%   |
| Intel Pentium           | 7         | 1.8%    |
| Intel Xeon              | 5         | 1.29%   |
| Intel Core 2 Quad       | 5         | 1.29%   |
| Intel Pentium Dual-Core | 3         | 0.77%   |
| AMD Turion 64 X2 Mobile | 3         | 0.77%   |
| AMD Sempron             | 3         | 0.77%   |
| AMD Ryzen 3             | 3         | 0.77%   |
| AMD Phenom II X4        | 3         | 0.77%   |
| AMD E1                  | 3         | 0.77%   |
| AMD Athlon II X2        | 3         | 0.77%   |
| AMD A6                  | 3         | 0.77%   |
| AMD A4                  | 3         | 0.77%   |
| Intel Pentium Silver    | 2         | 0.51%   |
| Intel Pentium 4         | 2         | 0.51%   |
| Intel Core i9           | 2         | 0.51%   |
| Intel Celeron M         | 2         | 0.51%   |
| AMD Ryzen 9             | 2         | 0.51%   |
| AMD Phenom II X6        | 2         | 0.51%   |
| AMD E                   | 2         | 0.51%   |
| AMD Athlon 64 X2        | 2         | 0.51%   |
| AMD A8                  | 2         | 0.51%   |
| AMD A10                 | 2         | 0.51%   |
| Intel Pentium M         | 1         | 0.26%   |
| Intel Pentium Gold      | 1         | 0.26%   |
| Intel Pentium Dual      | 1         | 0.26%   |
| Intel Pentium D         | 1         | 0.26%   |
| Intel Genuine           | 1         | 0.26%   |
| Intel Core m5           | 1         | 0.26%   |
| Intel Core Duo          | 1         | 0.26%   |
| Intel Core 2 Extreme    | 1         | 0.26%   |
| Intel Core 2            | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 178       | 45.76%  |
| 4      | 131       | 33.68%  |
| 6      | 30        | 7.71%   |
| 8      | 26        | 6.68%   |
| 1      | 17        | 4.37%   |
| 12     | 4         | 1.03%   |
| 14     | 2         | 0.51%   |
| 10     | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 387       | 99.49%  |
| 2      | 2         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 242       | 62.21%  |
| 1      | 147       | 37.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 377       | 96.67%  |
| 32-bit         | 13        | 3.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 47        | 11.93%  |
| 0x206a7    | 31        | 7.87%   |
| 0x306a9    | 26        | 6.6%    |
| 0x306c3    | 18        | 4.57%   |
| 0x1067a    | 13        | 3.3%    |
| 0x20655    | 12        | 3.05%   |
| 0x806c1    | 11        | 2.79%   |
| 0x406e3    | 11        | 2.79%   |
| 0x806ea    | 9         | 2.28%   |
| 0x40651    | 9         | 2.28%   |
| 0x906ea    | 8         | 2.03%   |
| 0x506e3    | 8         | 2.03%   |
| 0x806e9    | 7         | 1.78%   |
| 0x306d4    | 7         | 1.78%   |
| 0x30678    | 7         | 1.78%   |
| 0x08701021 | 7         | 1.78%   |
| 0x406c4    | 6         | 1.52%   |
| 0x906e9    | 5         | 1.27%   |
| 0x706a1    | 5         | 1.27%   |
| 0x20652    | 5         | 1.27%   |
| 0x0800820d | 5         | 1.27%   |
| 0xa0671    | 4         | 1.02%   |
| 0xa0653    | 4         | 1.02%   |
| 0x906ed    | 4         | 1.02%   |
| 0x806ec    | 4         | 1.02%   |
| 0x706a8    | 4         | 1.02%   |
| 0x6fd      | 4         | 1.02%   |
| 0x106c2    | 4         | 1.02%   |
| 0x10676    | 4         | 1.02%   |
| 0x0a50000c | 4         | 1.02%   |
| 0x03000027 | 4         | 1.02%   |
| 0xa0652    | 3         | 0.76%   |
| 0x906a3    | 3         | 0.76%   |
| 0x706e5    | 3         | 0.76%   |
| 0x6fb      | 3         | 0.76%   |
| 0x506c9    | 3         | 0.76%   |
| 0x406c3    | 3         | 0.76%   |
| 0x30661    | 3         | 0.76%   |
| 0x106e5    | 3         | 0.76%   |
| 0x106ca    | 3         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 11.57%  |
| SandyBridge      | 38        | 9.77%   |
| Haswell          | 33        | 8.48%   |
| IvyBridge        | 31        | 7.97%   |
| Penryn           | 22        | 5.66%   |
| Skylake          | 20        | 5.14%   |
| Westmere         | 18        | 4.63%   |
| Silvermont       | 18        | 4.63%   |
| TigerLake        | 12        | 3.08%   |
| Zen+             | 11        | 2.83%   |
| Zen 2            | 11        | 2.83%   |
| K10              | 10        | 2.57%   |
| Bonnell          | 10        | 2.57%   |
| Zen 3            | 9         | 2.31%   |
| Goldmont plus    | 9         | 2.31%   |
| Core             | 9         | 2.31%   |
| Zen              | 8         | 2.06%   |
| K8 Hammer        | 8         | 2.06%   |
| Icelake          | 8         | 2.06%   |
| CometLake        | 8         | 2.06%   |
| Broadwell        | 7         | 1.8%    |
| Unknown          | 7         | 1.8%    |
| P6               | 5         | 1.29%   |
| Nehalem          | 5         | 1.29%   |
| NetBurst         | 4         | 1.03%   |
| K10 Llano        | 4         | 1.03%   |
| Puma             | 3         | 0.77%   |
| Jaguar           | 3         | 0.77%   |
| Goldmont         | 3         | 0.77%   |
| Excavator        | 3         | 0.77%   |
| Bobcat           | 2         | 0.51%   |
| Tremont          | 1         | 0.26%   |
| Steamroller      | 1         | 0.26%   |
| K8 & K10 hybrid  | 1         | 0.26%   |
| Bulldozer        | 1         | 0.26%   |
| Alderlake Hybrid | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 243       | 53.17%  |
| Nvidia           | 117       | 25.6%   |
| AMD              | 96        | 21.01%  |
| VIA Technologies | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 6.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 4.41%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.52%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 2.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.89%   |
| Intel HD Graphics 620                                                                    | 8         | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 1.68%   |
| Intel HD Graphics 530                                                                    | 7         | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.47%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 5         | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.05%   |
| Intel HD Graphics 630                                                                    | 5         | 1.05%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.05%   |
| AMD Cezanne                                                                              | 5         | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 0.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 0.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.63%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.63%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 180       | 45.92%  |
| 1 x Nvidia     | 72        | 18.37%  |
| 1 x AMD        | 72        | 18.37%  |
| Intel + Nvidia | 41        | 10.46%  |
| Intel + AMD    | 13        | 3.32%   |
| 2 x AMD        | 7         | 1.79%   |
| AMD + Nvidia   | 4         | 1.02%   |
| 3 x AMD        | 1         | 0.26%   |
| 2 x Intel      | 1         | 0.26%   |
| 1 x VIA        | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 323       | 81.77%  |
| Proprietary | 55        | 13.92%  |
| Unknown     | 17        | 4.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 241       | 61.01%  |
| 0.01-0.5   | 44        | 11.14%  |
| 1.01-2.0   | 36        | 9.11%   |
| 0.51-1.0   | 33        | 8.35%   |
| 3.01-4.0   | 18        | 4.56%   |
| 7.01-8.0   | 15        | 3.8%    |
| 5.01-6.0   | 4         | 1.01%   |
| 2.01-3.0   | 2         | 0.51%   |
| 8.01-16.0  | 2         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 57        | 13.77%  |
| AU Optronics            | 54        | 13.04%  |
| LG Display              | 38        | 9.18%   |
| Chimei Innolux          | 35        | 8.45%   |
| BOE                     | 30        | 7.25%   |
| Goldstar                | 24        | 5.8%    |
| Dell                    | 17        | 4.11%   |
| Acer                    | 15        | 3.62%   |
| Lenovo                  | 14        | 3.38%   |
| Hewlett-Packard         | 14        | 3.38%   |
| Chi Mei Optoelectronics | 11        | 2.66%   |
| Apple                   | 8         | 1.93%   |
| Ancor Communications    | 8         | 1.93%   |
| Philips                 | 6         | 1.45%   |
| PANDA                   | 6         | 1.45%   |
| AOC                     | 5         | 1.21%   |
| ViewSonic               | 4         | 0.97%   |
| Sony                    | 4         | 0.97%   |
| Sharp                   | 4         | 0.97%   |
| InfoVision              | 4         | 0.97%   |
| Iiyama                  | 4         | 0.97%   |
| HannStar                | 4         | 0.97%   |
| Fujitsu Siemens         | 4         | 0.97%   |
| Vizio                   | 3         | 0.72%   |
| Vestel Elektronik       | 3         | 0.72%   |
| LG Philips              | 3         | 0.72%   |
| Eizo                    | 3         | 0.72%   |
| BenQ                    | 3         | 0.72%   |
| ASUSTek Computer        | 3         | 0.72%   |
| Sceptre Tech            | 2         | 0.48%   |
| Medion                  | 2         | 0.48%   |
| CPT                     | 2         | 0.48%   |
| Videoseven              | 1         | 0.24%   |
| Sunplus                 | 1         | 0.24%   |
| SANYO                   | 1         | 0.24%   |
| SAC                     | 1         | 0.24%   |
| RIS                     | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| Packard Bell            | 1         | 0.24%   |
| NEC Computers           | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 1.92%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.96%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 3         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.72%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 2         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.48%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.48%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.48%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.48%   |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                    | 2         | 0.48%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.48%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 2         | 0.48%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.48%   |
| Goldstar 32 FHD GSM76FF 1920x1080 698x392mm 31.5-inch                    | 2         | 0.48%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.48%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.48%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.48%   |
| BOE LCD Monitor BOE06A7 1920x1080 294x165mm 13.3-inch                    | 2         | 0.48%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 166       | 41.4%   |
| 1366x768 (WXGA)    | 88        | 21.95%  |
| 3840x2160 (4K)     | 23        | 5.74%   |
| 1600x900 (HD+)     | 17        | 4.24%   |
| 1680x1050 (WSXGA+) | 15        | 3.74%   |
| 2560x1440 (QHD)    | 14        | 3.49%   |
| 1280x1024 (SXGA)   | 12        | 2.99%   |
| 1280x800 (WXGA)    | 11        | 2.74%   |
| 1600x1200          | 9         | 2.24%   |
| 1440x900 (WXGA+)   | 9         | 2.24%   |
| 1024x600           | 7         | 1.75%   |
| 1920x1200 (WUXGA)  | 6         | 1.5%    |
| 2560x1080          | 5         | 1.25%   |
| 3440x1440          | 3         | 0.75%   |
| 1360x768           | 3         | 0.75%   |
| 2880x1800          | 2         | 0.5%    |
| 1400x1050          | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 3000x2000          | 1         | 0.25%   |
| 2736x1824          | 1         | 0.25%   |
| 2560x1600          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 2160x1440          | 1         | 0.25%   |
| 2048x1536          | 1         | 0.25%   |
| 1280x720 (HD)      | 1         | 0.25%   |
| 1024x768 (XGA)     | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 114       | 27.67%  |
| 13      | 37        | 8.98%   |
| 14      | 31        | 7.52%   |
| 23      | 26        | 6.31%   |
| 21      | 25        | 6.07%   |
| 27      | 24        | 5.83%   |
| 24      | 24        | 5.83%   |
| 17      | 24        | 5.83%   |
| 19      | 12        | 2.91%   |
| 11      | 10        | 2.43%   |
| 31      | 9         | 2.18%   |
| 22      | 9         | 2.18%   |
| 18      | 9         | 2.18%   |
| 34      | 8         | 1.94%   |
| 20      | 8         | 1.94%   |
| 12      | 8         | 1.94%   |
| 10      | 8         | 1.94%   |
| 84      | 7         | 1.7%    |
| 65      | 2         | 0.49%   |
| 26      | 2         | 0.49%   |
| 25      | 2         | 0.49%   |
| 16      | 2         | 0.49%   |
| 72      | 1         | 0.24%   |
| 54      | 1         | 0.24%   |
| 49      | 1         | 0.24%   |
| 46      | 1         | 0.24%   |
| 43      | 1         | 0.24%   |
| 42      | 1         | 0.24%   |
| 40      | 1         | 0.24%   |
| 39      | 1         | 0.24%   |
| 37      | 1         | 0.24%   |
| 32      | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 162       | 39.9%   |
| 501-600     | 72        | 17.73%  |
| 401-500     | 53        | 13.05%  |
| 201-300     | 45        | 11.08%  |
| 351-400     | 36        | 8.87%   |
| 601-700     | 10        | 2.46%   |
| 701-800     | 9         | 2.22%   |
| 1501-2000   | 8         | 1.97%   |
| 1001-1500   | 5         | 1.23%   |
| 801-900     | 3         | 0.74%   |
| 901-1000    | 2         | 0.49%   |
| Unknown     | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 299       | 77.86%  |
| 16/10 | 46        | 11.98%  |
| 5/4   | 13        | 3.39%   |
| 4/3   | 12        | 3.13%   |
| 21/9  | 8         | 2.08%   |
| 3/2   | 6         | 1.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 27.38%  |
| 201-250        | 72        | 17.6%   |
| 81-90          | 55        | 13.45%  |
| 151-200        | 26        | 6.36%   |
| 301-350        | 24        | 5.87%   |
| 121-130        | 20        | 4.89%   |
| 351-500        | 18        | 4.4%    |
| 71-80          | 14        | 3.42%   |
| More than 1000 | 12        | 2.93%   |
| 51-60          | 10        | 2.44%   |
| 251-300        | 10        | 2.44%   |
| 141-150        | 10        | 2.44%   |
| 41-50          | 8         | 1.96%   |
| 61-70          | 7         | 1.71%   |
| 501-1000       | 6         | 1.47%   |
| 111-120        | 2         | 0.49%   |
| 131-140        | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |
| Unknown        | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 149       | 37.53%  |
| 101-120       | 112       | 28.21%  |
| 121-160       | 101       | 25.44%  |
| 161-240       | 18        | 4.53%   |
| More than 240 | 9         | 2.27%   |
| 1-50          | 7         | 1.76%   |
| Unknown       | 1         | 0.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 325       | 82.49%  |
| 2     | 52        | 13.2%   |
| 0     | 12        | 3.05%   |
| 3     | 5         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 202       | 34.3%   |
| Intel                             | 188       | 31.92%  |
| Qualcomm Atheros                  | 77        | 13.07%  |
| Broadcom                          | 35        | 5.94%   |
| TP-Link                           | 10        | 1.7%    |
| Nvidia                            | 9         | 1.53%   |
| Ralink Technology                 | 8         | 1.36%   |
| Marvell Technology Group          | 8         | 1.36%   |
| Broadcom Limited                  | 8         | 1.36%   |
| MediaTek                          | 6         | 1.02%   |
| Ralink                            | 5         | 0.85%   |
| Sierra Wireless                   | 3         | 0.51%   |
| Huawei Technologies               | 3         | 0.51%   |
| ASIX Electronics                  | 3         | 0.51%   |
| Ericsson Business Mobile Networks | 2         | 0.34%   |
| Edimax Technology                 | 2         | 0.34%   |
| Attansic Technology               | 2         | 0.34%   |
| ASUSTek Computer                  | 2         | 0.34%   |
| Xiaomi                            | 1         | 0.17%   |
| VIA Technologies                  | 1         | 0.17%   |
| U-Blox                            | 1         | 0.17%   |
| Samsung Electronics               | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| NetGear                           | 1         | 0.17%   |
| Microsoft                         | 1         | 0.17%   |
| Mercucys                          | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| Hewlett-Packard                   | 1         | 0.17%   |
| Google                            | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| D-Link System                     | 1         | 0.17%   |
| AVM                               | 1         | 0.17%   |
| Aquantia                          | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 140       | 20.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 3.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 2.15%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 1.87%   |
| Intel Wireless 8265 / 8275                                              | 12        | 1.72%   |
| Intel Wireless 7260                                                     | 12        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 1.43%   |
| Intel Wireless 8260                                                     | 10        | 1.43%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.43%   |
| Intel Wireless 3165                                                     | 9         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.15%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 1.15%   |
| Intel I211 Gigabit Network Connection                                   | 7         | 1%      |
| Intel Centrino Advanced-N 6200                                          | 7         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 0.86%   |
| Intel Wireless 7265                                                     | 6         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 5         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                       | 4         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.57%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.57%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                    | 4         | 0.57%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.57%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 45.14%  |
| Qualcomm Atheros      | 57        | 17.87%  |
| Realtek Semiconductor | 52        | 16.3%   |
| Broadcom              | 22        | 6.9%    |
| TP-Link               | 9         | 2.82%   |
| Ralink Technology     | 8         | 2.51%   |
| Broadcom Limited      | 6         | 1.88%   |
| Ralink                | 5         | 1.57%   |
| MediaTek              | 5         | 1.57%   |
| Sierra Wireless       | 3         | 0.94%   |
| Edimax Technology     | 2         | 0.63%   |
| ASUSTek Computer      | 2         | 0.63%   |
| NetGear               | 1         | 0.31%   |
| Mercucys              | 1         | 0.31%   |
| Hewlett-Packard       | 1         | 0.31%   |
| AVM                   | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 5.31%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 4.38%   |
| Intel Wireless 8265 / 8275                                              | 12        | 3.75%   |
| Intel Wireless 7260                                                     | 12        | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 10        | 3.13%   |
| Intel Wireless 8260                                                     | 10        | 3.13%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.13%   |
| Intel Wireless 3165                                                     | 9         | 2.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.5%    |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.88%   |
| Intel Wireless 7265                                                     | 6         | 1.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 1.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 5         | 1.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.25%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.25%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.25%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.94%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.94%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.94%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.63%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 2         | 0.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 182       | 50.7%   |
| Intel                    | 97        | 27.02%  |
| Qualcomm Atheros         | 28        | 7.8%    |
| Broadcom                 | 16        | 4.46%   |
| Nvidia                   | 9         | 2.51%   |
| Marvell Technology Group | 8         | 2.23%   |
| ASIX Electronics         | 3         | 0.84%   |
| Broadcom Limited         | 2         | 0.56%   |
| Attansic Technology      | 2         | 0.56%   |
| Xiaomi                   | 1         | 0.28%   |
| VIA Technologies         | 1         | 0.28%   |
| TP-Link                  | 1         | 0.28%   |
| Samsung Electronics      | 1         | 0.28%   |
| Qualcomm                 | 1         | 0.28%   |
| Microsoft                | 1         | 0.28%   |
| MediaTek                 | 1         | 0.28%   |
| Lenovo                   | 1         | 0.28%   |
| JMicron Technology       | 1         | 0.28%   |
| Huawei Technologies      | 1         | 0.28%   |
| D-Link System            | 1         | 0.28%   |
| Aquantia                 | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 140       | 37.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 6.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 4.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 13        | 3.51%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 2.16%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 2.16%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.08%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.08%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.08%   |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 1.08%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 1.08%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 1.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.81%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.54%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.54%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.54%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.54%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.54%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 342       | 52.94%  |
| WiFi     | 297       | 45.98%  |
| Modem    | 6         | 0.93%   |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 238       | 59.35%  |
| Ethernet | 162       | 40.4%   |
| Unknown  | 1         | 0.25%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 222       | 56.92%  |
| 1     | 151       | 38.72%  |
| 0     | 9         | 2.31%   |
| 3     | 7         | 1.79%   |
| 12    | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 332       | 84.69%  |
| Yes  | 60        | 15.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 105       | 46.67%  |
| Qualcomm Atheros Communications | 19        | 8.44%   |
| Broadcom                        | 19        | 8.44%   |
| Realtek Semiconductor           | 18        | 8%      |
| Cambridge Silicon Radio         | 13        | 5.78%   |
| Apple                           | 12        | 5.33%   |
| IMC Networks                    | 9         | 4%      |
| Lite-On Technology              | 6         | 2.67%   |
| Foxconn / Hon Hai               | 6         | 2.67%   |
| Hewlett-Packard                 | 5         | 2.22%   |
| ASUSTek Computer                | 4         | 1.78%   |
| Toshiba                         | 3         | 1.33%   |
| Dell                            | 3         | 1.33%   |
| Ralink                          | 1         | 0.44%   |
| MediaTek                        | 1         | 0.44%   |
| Alps Electric                   | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 48        | 21.33%  |
| Intel AX201 Bluetooth                                                               | 16        | 7.11%   |
| Intel AX200 Bluetooth                                                               | 14        | 6.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 5.78%   |
| Realtek Bluetooth Radio                                                             | 10        | 4.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 4.44%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.67%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 2.67%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 2.67%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.78%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.78%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 1.78%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.33%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.89%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.89%   |
| Intel Bluetooth Device                                                              | 2         | 0.89%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.89%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.89%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.89%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.89%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.44%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.44%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.44%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.44%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.44%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.44%   |
| MediaTek Wireless_Device                                                            | 1         | 0.44%   |
| Lite-On Wireless_Device                                                             | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 293       | 54.56%  |
| Nvidia                     | 96        | 17.88%  |
| AMD                        | 96        | 17.88%  |
| C-Media Electronics        | 8         | 1.49%   |
| Creative Labs              | 7         | 1.3%    |
| JMTek                      | 3         | 0.56%   |
| GN Netcom                  | 3         | 0.56%   |
| Texas Instruments          | 2         | 0.37%   |
| ROCCAT                     | 2         | 0.37%   |
| Realtek Semiconductor      | 2         | 0.37%   |
| Logitech                   | 2         | 0.37%   |
| Focusrite-Novation         | 2         | 0.37%   |
| BEHRINGER International    | 2         | 0.37%   |
| VIA Technologies           | 1         | 0.19%   |
| Unknown                    | 1         | 0.19%   |
| ULi Electronics            | 1         | 0.19%   |
| TerraTec Electronic        | 1         | 0.19%   |
| Tenx Technology            | 1         | 0.19%   |
| SteelSeries ApS            | 1         | 0.19%   |
| Shenzhen Riitek Technology | 1         | 0.19%   |
| Schiit Audio               | 1         | 0.19%   |
| Razer USA                  | 1         | 0.19%   |
| Plantronics                | 1         | 0.19%   |
| Microsoft                  | 1         | 0.19%   |
| Mark of the Unicorn        | 1         | 0.19%   |
| LG Electronics             | 1         | 0.19%   |
| Lenovo                     | 1         | 0.19%   |
| Kingston Technology        | 1         | 0.19%   |
| Fortemedia                 | 1         | 0.19%   |
| FIFINE 683 Microphone      | 1         | 0.19%   |
| Dell                       | 1         | 0.19%   |
| CMX Systems                | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 37        | 5.99%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 4.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 3.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 3.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 2.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 2.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 1.94%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 10        | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 1.46%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.46%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.13%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 0.97%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.81%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 85        | 18.89%  |
| SK hynix                     | 72        | 16%     |
| Unknown                      | 65        | 14.44%  |
| Kingston                     | 57        | 12.67%  |
| Micron Technology            | 40        | 8.89%   |
| Corsair                      | 24        | 5.33%   |
| Crucial                      | 23        | 5.11%   |
| G.Skill                      | 14        | 3.11%   |
| Ramaxel Technology           | 8         | 1.78%   |
| A-DATA Technology            | 8         | 1.78%   |
| Elpida                       | 7         | 1.56%   |
| Unknown (ABCD)               | 6         | 1.33%   |
| Nanya Technology             | 6         | 1.33%   |
| Smart                        | 5         | 1.11%   |
| Transcend                    | 4         | 0.89%   |
| Unknown                      | 4         | 0.89%   |
| Patriot                      | 3         | 0.67%   |
| Teikon                       | 2         | 0.44%   |
| Team                         | 2         | 0.44%   |
| PNY                          | 2         | 0.44%   |
| Apacer                       | 2         | 0.44%   |
| Unknown (F301)               | 1         | 0.22%   |
| TRS STAR                     | 1         | 0.22%   |
| RZX                          | 1         | 0.22%   |
| Patriot Memory (PDP Systems) | 1         | 0.22%   |
| OCZ                          | 1         | 0.22%   |
| Innodisk                     | 1         | 0.22%   |
| High Bridge                  | 1         | 0.22%   |
| Axiom                        | 1         | 0.22%   |
| Avant                        | 1         | 0.22%   |
| ASint Technology             | 1         | 0.22%   |
| 48spaces                     | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.01%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 1.01%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.81%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.81%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.81%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 4         | 0.81%   |
| Unknown                                                          | 4         | 0.81%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 3         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 3         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 3         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.61%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.61%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 3         | 0.61%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.41%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.41%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 2         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 2         | 0.41%   |
| Unknown RAM Module 1024MB DIMM DDR 333MT/s                       | 2         | 0.41%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 2         | 0.41%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 2         | 0.41%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 2         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.41%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.41%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.41%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 172       | 44.22%  |
| DDR4    | 131       | 33.68%  |
| DDR2    | 30        | 7.71%   |
| LPDDR4  | 14        | 3.6%    |
| Unknown | 13        | 3.34%   |
| DDR     | 10        | 2.57%   |
| SDRAM   | 9         | 2.31%   |
| LPDDR3  | 6         | 1.54%   |
| DRAM    | 3         | 0.77%   |
| DDR5    | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 249       | 64.18%  |
| DIMM         | 120       | 30.93%  |
| Row Of Chips | 15        | 3.87%   |
| Chip         | 3         | 0.77%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 160       | 37.12%  |
| 8192  | 124       | 28.77%  |
| 2048  | 76        | 17.63%  |
| 16384 | 37        | 8.58%   |
| 1024  | 25        | 5.8%    |
| 32768 | 6         | 1.39%   |
| 512   | 3         | 0.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 100       | 23.36%  |
| 1333    | 44        | 10.28%  |
| 3200    | 40        | 9.35%   |
| 2667    | 37        | 8.64%   |
| 2400    | 30        | 7.01%   |
| 1334    | 24        | 5.61%   |
| Unknown | 22        | 5.14%   |
| 2133    | 19        | 4.44%   |
| 667     | 17        | 3.97%   |
| 800     | 12        | 2.8%    |
| 3600    | 8         | 1.87%   |
| 1067    | 8         | 1.87%   |
| 1867    | 6         | 1.4%    |
| 3466    | 5         | 1.17%   |
| 3000    | 5         | 1.17%   |
| 4267    | 4         | 0.93%   |
| 3266    | 4         | 0.93%   |
| 2933    | 4         | 0.93%   |
| 333     | 4         | 0.93%   |
| 4199    | 3         | 0.7%    |
| 2666    | 3         | 0.7%    |
| 2048    | 3         | 0.7%    |
| 1800    | 3         | 0.7%    |
| 1639    | 3         | 0.7%    |
| 533     | 3         | 0.7%    |
| 49926   | 2         | 0.47%   |
| 8400    | 2         | 0.47%   |
| 3733    | 2         | 0.47%   |
| 3400    | 2         | 0.47%   |
| 400     | 2         | 0.47%   |
| 4800    | 1         | 0.23%   |
| 3100    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 1777    | 1         | 0.23%   |
| 666     | 1         | 0.23%   |
| 200     | 1         | 0.23%   |
| 166     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 3         | 25%     |
| Brother Industries    | 3         | 25%     |
| Canon                 | 2         | 16.67%  |
| Seiko Epson           | 1         | 8.33%   |
| Samsung Electronics   | 1         | 8.33%   |
| Lexmark International | 1         | 8.33%   |
| Konica Minolta        | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Brother DCP-L2540DW                | 2         | 16.67%  |
| Seiko Epson L380 Series            | 1         | 8.33%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 8.33%   |
| Lexmark International CS417dn      | 1         | 8.33%   |
| Konica Minolta 206                 | 1         | 8.33%   |
| HP LaserJet P2055 series           | 1         | 8.33%   |
| HP LaserJet M101-M106              | 1         | 8.33%   |
| HP LaserJet 1022                   | 1         | 8.33%   |
| Canon MF641C                       | 1         | 8.33%   |
| Canon LiDE 400                     | 1         | 8.33%   |
| Brother MFC-7340                   | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 25%     |
| Canon CanoScan LiDE 700F           | 1         | 25%     |
| Canon CanoScan LIDE 25             | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 21.55%  |
| Acer                                   | 23        | 9.91%   |
| Realtek Semiconductor                  | 19        | 8.19%   |
| Sunplus Innovation Technology          | 16        | 6.9%    |
| Microdia                               | 15        | 6.47%   |
| Logitech                               | 12        | 5.17%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.17%   |
| IMC Networks                           | 11        | 4.74%   |
| Quanta                                 | 9         | 3.88%   |
| Lite-On Technology                     | 9         | 3.88%   |
| Suyin                                  | 7         | 3.02%   |
| Lenovo                                 | 6         | 2.59%   |
| Microsoft                              | 5         | 2.16%   |
| Apple                                  | 5         | 2.16%   |
| Z-Star Microelectronics                | 3         | 1.29%   |
| Syntek                                 | 3         | 1.29%   |
| Silicon Motion                         | 3         | 1.29%   |
| Ricoh                                  | 3         | 1.29%   |
| Luxvisions Innotech Limited            | 2         | 0.86%   |
| Generalplus Technology                 | 2         | 0.86%   |
| Alcor Micro                            | 2         | 0.86%   |
| Y Media                                | 1         | 0.43%   |
| Xiongmai                               | 1         | 0.43%   |
| WaveRider Communications               | 1         | 0.43%   |
| Trust                                  | 1         | 0.43%   |
| Sunplus Technology                     | 1         | 0.43%   |
| Samsung Electronics                    | 1         | 0.43%   |
| Primax Electronics                     | 1         | 0.43%   |
| LG Electronics                         | 1         | 0.43%   |
| Importek                               | 1         | 0.43%   |
| icSpring                               | 1         | 0.43%   |
| Huawei Technologies                    | 1         | 0.43%   |
| Goodong Industry                       | 1         | 0.43%   |
| GEMBIRD                                | 1         | 0.43%   |
| Cubeternet                             | 1         | 0.43%   |
| Arkmicro Technologies                  | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                   | 11        | 4.72%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 2.15%   |
| Realtek Integrated_Webcam_HD                                | 5         | 2.15%   |
| Microdia Integrated_Webcam_HD                               | 5         | 2.15%   |
| Lite-On Integrated Camera                                   | 5         | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 5         | 2.15%   |
| Acer Integrated Camera                                      | 5         | 2.15%   |
| Microsoft LifeCam HD-3000                                   | 4         | 1.72%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.72%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.72%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.72%   |
| Acer BisonCam, NB Pro                                       | 4         | 1.72%   |
| Syntek EasyCamera                                           | 3         | 1.29%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.29%   |
| Sunplus ASUS Webcam                                         | 3         | 1.29%   |
| Logitech Webcam C270                                        | 3         | 1.29%   |
| Lenovo Integrated Webcam [R5U877]                           | 3         | 1.29%   |
| Chicony HD WebCam                                           | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 3         | 1.29%   |
| Apple Built-in iSight                                       | 3         | 1.29%   |
| Acer BisonCam,NB Pro                                        | 3         | 1.29%   |
| Sunplus HD WebCam                                           | 2         | 0.86%   |
| Ricoh USB2.0 Camera                                         | 2         | 0.86%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 0.86%   |
| Realtek USB Camera                                          | 2         | 0.86%   |
| Realtek MTD camera                                          | 2         | 0.86%   |
| Quanta VGA WebCam                                           | 2         | 0.86%   |
| Quanta HD User Facing                                       | 2         | 0.86%   |
| Microdia USB 2.0 Camera                                     | 2         | 0.86%   |
| Microdia Integrated Webcam                                  | 2         | 0.86%   |
| Logitech Webcam C930e                                       | 2         | 0.86%   |
| Logitech Webcam C200                                        | 2         | 0.86%   |
| Lenovo Integrated Webcam                                    | 2         | 0.86%   |
| IMC Networks Integrated Camera                              | 2         | 0.86%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 0.86%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 0.86%   |
| Chicony HD User Facing                                      | 2         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 0.86%   |
| Acer SunplusIT INC. Integrated Camera                       | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 34.88%  |
| Synaptics                  | 8         | 18.6%   |
| Upek                       | 6         | 13.95%  |
| Shenzhen Goodix Technology | 5         | 11.63%  |
| AuthenTec                  | 4         | 9.3%    |
| LighTuning Technology      | 2         | 4.65%   |
| STMicroelectronics         | 1         | 2.33%   |
| Microsoft                  | 1         | 2.33%   |
| Elan Microelectronics      | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 9.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 9.3%    |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 6.98%   |
| Validity Sensors Synaptics WBDI                            | 3         | 6.98%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 6.98%   |
| Unknown                                                    | 3         | 6.98%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 4.65%   |
| Upek TCS5B Fingerprint sensor                              | 2         | 4.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.65%   |
| AuthenTec AES2810                                          | 2         | 4.65%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.33%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.33%   |
| Microsoft Fingerprint Reader                               | 1         | 2.33%   |
| LighTuning Fingerprint Reader                              | 1         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.33%   |
| Elan ELAN:Fingerprint                                      | 1         | 2.33%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 7         | 38.89%  |
| Broadcom              | 6         | 33.33%  |
| Lenovo                | 3         | 16.67%  |
| O2 Micro              | 1         | 5.56%   |
| Advanced Card Systems | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 38.89%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 16.67%  |
| Broadcom 5880                                                                | 3         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Advanced Card Systems ACR122U                                                | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 277       | 69.6%   |
| 1     | 90        | 22.61%  |
| 2     | 26        | 6.53%   |
| 3     | 5         | 1.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 59        | 40.14%  |
| Fingerprint reader       | 43        | 29.25%  |
| Chipcard                 | 16        | 10.88%  |
| Multimedia controller    | 10        | 6.8%    |
| Communication controller | 5         | 3.4%    |
| Net/wireless             | 4         | 2.72%   |
| Unassigned class         | 3         | 2.04%   |
| Storage                  | 3         | 2.04%   |
| Sound                    | 1         | 0.68%   |
| Dvb card                 | 1         | 0.68%   |
| Camera                   | 1         | 0.68%   |
| Bluetooth                | 1         | 0.68%   |

