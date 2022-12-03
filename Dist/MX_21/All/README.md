MX 21 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 21.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_21/Desktop/README.md) and [notebooks](/Dist/MX_21/Notebook/README.md).

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

Total: 240

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GF63 Thin 9SC               | Notebook    | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| HP            | 304Ah                       | Desktop     | [15db22accc](https://linux-hardware.org/?probe=15db22accc) | Nov 30, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | Notebook    | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [0f0d4f70b0](https://linux-hardware.org/?probe=0f0d4f70b0) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| GEO           | GeoFlex 340                 | Convertible | [6e930633c0](https://linux-hardware.org/?probe=6e930633c0) | Nov 18, 2022 |
| Dell          | 0J051K A00                  | Server      | [cb579ef51b](https://linux-hardware.org/?probe=cb579ef51b) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [1a0674de42](https://linux-hardware.org/?probe=1a0674de42) | Nov 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [f5305c9730](https://linux-hardware.org/?probe=f5305c9730) | Nov 04, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [9c72952af7](https://linux-hardware.org/?probe=9c72952af7) | Nov 04, 2022 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [c165c40a7e](https://linux-hardware.org/?probe=c165c40a7e) | Nov 03, 2022 |
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
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | Notebook    | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
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
| Lenovo        | 1046 NO DPK                 | Desktop     | [561b1c3324](https://linux-hardware.org/?probe=561b1c3324) | Mar 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d0b555e0ba](https://linux-hardware.org/?probe=d0b555e0ba) | Mar 17, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c8c2d7bba3](https://linux-hardware.org/?probe=c8c2d7bba3) | Mar 14, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | Desktop     | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | Desktop     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Dell          | Latitude 3190               | Notebook    | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
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
| ASUSTek       | X99-DELUXE                  | Desktop     | [4ffe151e7a](https://linux-hardware.org/?probe=4ffe151e7a) | Jan 29, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | Notebook    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | Notebook    | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | Notebook    | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | Notebook    | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ecaec39529](https://linux-hardware.org/?probe=ecaec39529) | Jan 05, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | Notebook    | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7cc374183b](https://linux-hardware.org/?probe=7cc374183b) | Dec 30, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9147191a67](https://linux-hardware.org/?probe=9147191a67) | Dec 24, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [78d4e04363](https://linux-hardware.org/?probe=78d4e04363) | Dec 16, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| GALAX         | B550M                       | Desktop     | [a6866c8a45](https://linux-hardware.org/?probe=a6866c8a45) | Dec 04, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bb58f4914e](https://linux-hardware.org/?probe=bb58f4914e) | Nov 21, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [fd5f409df8](https://linux-hardware.org/?probe=fd5f409df8) | Nov 14, 2021 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [a85cc99f78](https://linux-hardware.org/?probe=a85cc99f78) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | Notebook    | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| ASUSTek       | E402MA                      | Notebook    | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | Notebook    | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ee6a141211](https://linux-hardware.org/?probe=ee6a141211) | Oct 19, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [5d136cb09b](https://linux-hardware.org/?probe=5d136cb09b) | Aug 13, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-13-amd64            | 19        | 10.44%  |
| 5.10.0-9-amd64             | 18        | 9.89%   |
| 5.14.0-4mx-amd64           | 14        | 7.69%   |
| 5.10.0-18-amd64            | 14        | 7.69%   |
| 5.10.0-16-amd64            | 13        | 7.14%   |
| 5.16.0-5mx-amd64           | 11        | 6.04%   |
| 5.10.0-19-amd64            | 11        | 6.04%   |
| 5.10.0-11-amd64            | 8         | 4.4%    |
| 5.10.0-15-amd64            | 6         | 3.3%    |
| 5.10.0-14-amd64            | 6         | 3.3%    |
| 5.18.0-4mx-amd64           | 5         | 2.75%   |
| 5.10.0-17-amd64            | 4         | 2.2%    |
| 5.10.0-10-amd64            | 4         | 2.2%    |
| 6.0.0-3mx-amd64            | 3         | 1.65%   |
| 5.19.0-2mx-amd64           | 3         | 1.65%   |
| 5.16.0-6mx-amd64           | 3         | 1.65%   |
| 5.16.0-4mx-amd64           | 2         | 1.1%    |
| 5.16.0-18.1-liquorix-amd64 | 2         | 1.1%    |
| 5.14.0-3mx-amd64           | 2         | 1.1%    |
| 5.10.0-8-amd64             | 2         | 1.1%    |
| 5.10.0-18-686-pae          | 2         | 1.1%    |
| 5.10.0-13-686-pae          | 2         | 1.1%    |
| 5.10.0-12-amd64            | 2         | 1.1%    |
| 5.10.0-11-686-pae          | 2         | 1.1%    |
| 6.0.5-x64v1-xanmod1        | 1         | 0.55%   |
| 6.0.0-4mx-rt-amd64         | 1         | 0.55%   |
| 6.0.0-4mx-amd64            | 1         | 0.55%   |
| 5.19.0-4.2-liquorix-amd64  | 1         | 0.55%   |
| 5.19.0-17.2-liquorix-amd64 | 1         | 0.55%   |
| 5.19.0-12.1-liquorix-amd64 | 1         | 0.55%   |
| 5.18.0-3-amd64             | 1         | 0.55%   |
| 5.18.0-0.deb11.4-amd64     | 1         | 0.55%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 0.55%   |
| 5.17.0-3mx-amd64           | 1         | 0.55%   |
| 5.17.0-2mx-amd64           | 1         | 0.55%   |
| 5.17.0-1mx-amd64           | 1         | 0.55%   |
| 5.17.0-1-amd64             | 1         | 0.55%   |
| 5.16.0-rc5-hwmon-next+     | 1         | 0.55%   |
| 5.15.0-3mx-amd64           | 1         | 0.55%   |
| 5.15.0-2-amd64             | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 108       | 61.71%  |
| 5.16.0   | 19        | 10.86%  |
| 5.14.0   | 17        | 9.71%   |
| 5.18.0   | 7         | 4%      |
| 5.19.0   | 6         | 3.43%   |
| 6.0.0    | 5         | 2.86%   |
| 5.17.0   | 5         | 2.86%   |
| 5.15.0   | 3         | 1.71%   |
| 6.0.5    | 1         | 0.57%   |
| 5.10.82  | 1         | 0.57%   |
| 5.10.52  | 1         | 0.57%   |
| 5.10.111 | 1         | 0.57%   |
| 4.19.0   | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 111       | 63.43%  |
| 5.16    | 19        | 10.86%  |
| 5.14    | 17        | 9.71%   |
| 5.18    | 7         | 4%      |
| 6.0     | 6         | 3.43%   |
| 5.19    | 6         | 3.43%   |
| 5.17    | 5         | 2.86%   |
| 5.15    | 3         | 1.71%   |
| 4.19    | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 162       | 96.43%  |
| i686   | 6         | 3.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 123       | 72.35%  |
| KDE5             | 34        | 20%     |
| Budgie           | 3         | 1.76%   |
| Unknown          | 3         | 1.76%   |
| lightdm-xsession | 2         | 1.18%   |
| GNOME            | 2         | 1.18%   |
| LXQt             | 1         | 0.59%   |
| i3               | 1         | 0.59%   |
| GNOME Classic    | 1         | 0.59%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 166       | 98.81%  |
| Tty  | 2         | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 133       | 78.7%   |
| SDDM    | 32        | 18.93%  |
| SLiM    | 2         | 1.18%   |
| GDM     | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 79        | 46.47%  |
| de_DE   | 28        | 16.47%  |
| it_IT   | 8         | 4.71%   |
| en_GB   | 8         | 4.71%   |
| ru_RU   | 5         | 2.94%   |
| pl_PL   | 4         | 2.35%   |
| fr_FR   | 4         | 2.35%   |
| es_ES   | 4         | 2.35%   |
| pt_BR   | 3         | 1.76%   |
| en_NZ   | 3         | 1.76%   |
| de_CH   | 3         | 1.76%   |
| Unknown | 3         | 1.76%   |
| tr_TR   | 2         | 1.18%   |
| hu_HU   | 2         | 1.18%   |
| fi_FI   | 2         | 1.18%   |
| en_AU   | 2         | 1.18%   |
| sv_SE   | 1         | 0.59%   |
| sk_SK   | 1         | 0.59%   |
| nl_NL   | 1         | 0.59%   |
| nb_NO   | 1         | 0.59%   |
| id_ID   | 1         | 0.59%   |
| es_UY   | 1         | 0.59%   |
| es_PE   | 1         | 0.59%   |
| es_MX   | 1         | 0.59%   |
| es_CO   | 1         | 0.59%   |
| bg_BG   | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 111       | 66.07%  |
| BIOS | 57        | 33.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 140       | 82.35%  |
| Overlay  | 21        | 12.35%  |
| Btrfs    | 5         | 2.94%   |
| Xfs      | 1         | 0.59%   |
| Reiserfs | 1         | 0.59%   |
| F2fs     | 1         | 0.59%   |
| Ext3     | 1         | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 123       | 73.21%  |
| MBR     | 43        | 25.6%   |
| Unknown | 2         | 1.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 67.84%  |
| Yes       | 55        | 32.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 52.35%  |
| No        | 81        | 47.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 24        | 14.29%  |
| ASUSTek Computer            | 23        | 13.69%  |
| Hewlett-Packard             | 19        | 11.31%  |
| Dell                        | 18        | 10.71%  |
| Apple                       | 11        | 6.55%   |
| MSI                         | 9         | 5.36%   |
| Gigabyte Technology         | 8         | 4.76%   |
| Sony                        | 7         | 4.17%   |
| Acer                        | 6         | 3.57%   |
| Intel                       | 4         | 2.38%   |
| Samsung Electronics         | 3         | 1.79%   |
| Medion                      | 3         | 1.79%   |
| ASRock                      | 3         | 1.79%   |
| Alienware                   | 3         | 1.79%   |
| Fujitsu Siemens             | 2         | 1.19%   |
| Biostar                     | 2         | 1.19%   |
| ZOTAC                       | 1         | 0.6%    |
| win element                 | 1         | 0.6%    |
| Vulcan Electronics          | 1         | 0.6%    |
| TUXEDO                      | 1         | 0.6%    |
| Toshiba                     | 1         | 0.6%    |
| Sun Microsystems            | 1         | 0.6%    |
| Shenzhen Wangang Technology | 1         | 0.6%    |
| SANTECH                     | 1         | 0.6%    |
| Pegatron                    | 1         | 0.6%    |
| Notebook                    | 1         | 0.6%    |
| MP                          | 1         | 0.6%    |
| Microsoft                   | 1         | 0.6%    |
| Huanan                      | 1         | 0.6%    |
| GEO                         | 1         | 0.6%    |
| GALAX                       | 1         | 0.6%    |
| Fujitsu                     | 1         | 0.6%    |
| Framework                   | 1         | 0.6%    |
| Foxconn                     | 1         | 0.6%    |
| efirstview                  | 1         | 0.6%    |
| Chuwi                       | 1         | 0.6%    |
| AZW                         | 1         | 0.6%    |
| AOpen                       | 1         | 0.6%    |
| Unknown                     | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Dell OptiPlex 755                            | 2         | 1.19%   |
| ASUS All Series                              | 2         | 1.19%   |
| Apple MacBookAir7,2                          | 2         | 1.19%   |
| Unknown                                      | 2         | 1.19%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.6%    |
| win element MoreFine S500+                   | 1         | 0.6%    |
| Vulcan Excursion XB                          | 1         | 0.6%    |
| TUXEDO N7x0WU                                | 1         | 0.6%    |
| Toshiba Satellite C845                       | 1         | 0.6%    |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.6%    |
| Sony VPCYB3V1E                               | 1         | 0.6%    |
| Sony VPCSB1V9R                               | 1         | 0.6%    |
| Sony VPCF119FX                               | 1         | 0.6%    |
| Sony VPCEH2N1E                               | 1         | 0.6%    |
| Sony VPCEC3S1E                               | 1         | 0.6%    |
| Sony VGN-TZ3RXN_B                            | 1         | 0.6%    |
| Sony SVE1513Q1ESI                            | 1         | 0.6%    |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.6%    |
| SANTECH X170KM-G                             | 1         | 0.6%    |
| Samsung NC210/NC110                          | 1         | 0.6%    |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.6%    |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.6%    |
| Pegatron FQ425AA-ABA a6655f                  | 1         | 0.6%    |
| Notebook PD5x_7xPNP_PNN_PNT                  | 1         | 0.6%    |
| MSI MS-7C91                                  | 1         | 0.6%    |
| MSI MS-7C37                                  | 1         | 0.6%    |
| MSI MS-7A34                                  | 1         | 0.6%    |
| MSI MS-7917                                  | 1         | 0.6%    |
| MSI MS-7758                                  | 1         | 0.6%    |
| MSI Modern 14 B11MOL                         | 1         | 0.6%    |
| MSI GV62 8RD                                 | 1         | 0.6%    |
| MSI GF63 Thin 9SC                            | 1         | 0.6%    |
| MSI Alpha 15 B5EEK                           | 1         | 0.6%    |
| MP MS-7848                                   | 1         | 0.6%    |
| Microsoft Surface Pro 7                      | 1         | 0.6%    |
| Medion E7424 MD60750                         | 1         | 0.6%    |
| Medion E14304                                | 1         | 0.6%    |
| Medion Akoya P5330 E MD8876/2458             | 1         | 0.6%    |
| Lenovo Yoga 7 14ITL5 82BH                    | 1         | 0.6%    |
| Lenovo V15-IGL 82C3                          | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 5.95%   |
| Dell OptiPlex         | 4         | 2.38%   |
| Dell Latitude         | 4         | 2.38%   |
| Lenovo IdeaPad        | 3         | 1.79%   |
| HP ProBook            | 3         | 1.79%   |
| HP EliteBook          | 3         | 1.79%   |
| HP Compaq             | 3         | 1.79%   |
| Dell Inspiron         | 3         | 1.79%   |
| ASUS ROG              | 3         | 1.79%   |
| HP Laptop             | 2         | 1.19%   |
| HP ENVY               | 2         | 1.19%   |
| Gigabyte B550M        | 2         | 1.19%   |
| Dell Vostro           | 2         | 1.19%   |
| Dell Precision        | 2         | 1.19%   |
| ASUS TUF              | 2         | 1.19%   |
| ASUS P5GC-MX          | 2         | 1.19%   |
| ASUS ASUS             | 2         | 1.19%   |
| ASUS All              | 2         | 1.19%   |
| Apple MacBookPro11    | 2         | 1.19%   |
| Apple MacBookAir7     | 2         | 1.19%   |
| Alienware m15         | 2         | 1.19%   |
| Acer Nitro            | 2         | 1.19%   |
| Acer Aspire           | 2         | 1.19%   |
| Unknown               | 2         | 1.19%   |
| ZOTAC ZBOX-ECM73070C  | 1         | 0.6%    |
| win element MoreFine  | 1         | 0.6%    |
| Vulcan Excursion      | 1         | 0.6%    |
| TUXEDO N7x0WU         | 1         | 0.6%    |
| Toshiba Satellite     | 1         | 0.6%    |
| Sun Microsystems Sun  | 1         | 0.6%    |
| Sony VPCYB3V1E        | 1         | 0.6%    |
| Sony VPCSB1V9R        | 1         | 0.6%    |
| Sony VPCF119FX        | 1         | 0.6%    |
| Sony VPCEH2N1E        | 1         | 0.6%    |
| Sony VPCEC3S1E        | 1         | 0.6%    |
| Sony VGN-TZ3RXN       | 1         | 0.6%    |
| Sony SVE1513Q1ESI     | 1         | 0.6%    |
| Shenzhen Wangang AERO | 1         | 0.6%    |
| SANTECH X170KM-G      | 1         | 0.6%    |
| Samsung NC210         | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 27        | 16.07%  |
| 2020    | 19        | 11.31%  |
| 2018    | 14        | 8.33%   |
| 2015    | 14        | 8.33%   |
| 2011    | 12        | 7.14%   |
| 2019    | 11        | 6.55%   |
| 2010    | 11        | 6.55%   |
| 2013    | 9         | 5.36%   |
| 2012    | 8         | 4.76%   |
| 2007    | 8         | 4.76%   |
| 2016    | 7         | 4.17%   |
| 2017    | 6         | 3.57%   |
| 2014    | 6         | 3.57%   |
| 2022    | 5         | 2.98%   |
| 2009    | 4         | 2.38%   |
| 2008    | 4         | 2.38%   |
| 2006    | 1         | 0.6%    |
| 2005    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 104       | 61.9%   |
| Desktop     | 46        | 27.38%  |
| Convertible | 7         | 4.17%   |
| Mini pc     | 6         | 3.57%   |
| All in one  | 2         | 1.19%   |
| Server      | 2         | 1.19%   |
| Tablet      | 1         | 0.6%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 166       | 98.81%  |
| Enabled  | 2         | 1.19%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 168       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 45        | 26.79%  |
| 8.01-16.0   | 34        | 20.24%  |
| 16.01-24.0  | 29        | 17.26%  |
| 3.01-4.0    | 22        | 13.1%   |
| 32.01-64.0  | 21        | 12.5%   |
| 1.01-2.0    | 6         | 3.57%   |
| 2.01-3.0    | 4         | 2.38%   |
| 64.01-256.0 | 4         | 2.38%   |
| 24.01-32.0  | 2         | 1.19%   |
| 0.51-1.0    | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 58        | 32.58%  |
| 2.01-3.0   | 52        | 29.21%  |
| 3.01-4.0   | 27        | 15.17%  |
| 4.01-8.0   | 22        | 12.36%  |
| 0.51-1.0   | 10        | 5.62%   |
| 8.01-16.0  | 7         | 3.93%   |
| 16.01-24.0 | 1         | 0.56%   |
| 0.01-0.5   | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 94        | 54.97%  |
| 2      | 44        | 25.73%  |
| 3      | 22        | 12.87%  |
| 4      | 5         | 2.92%   |
| 8      | 2         | 1.17%   |
| 5      | 2         | 1.17%   |
| 0      | 2         | 1.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 113       | 67.26%  |
| Yes       | 55        | 32.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 84.52%  |
| No        | 26        | 15.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 79.88%  |
| No        | 34        | 20.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 63.1%   |
| No        | 62        | 36.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 45        | 26.47%  |
| Germany     | 26        | 15.29%  |
| Italy       | 15        | 8.82%   |
| Canada      | 7         | 4.12%   |
| Russia      | 5         | 2.94%   |
| Poland      | 5         | 2.94%   |
| Brazil      | 5         | 2.94%   |
| Spain       | 4         | 2.35%   |
| Netherlands | 4         | 2.35%   |
| India       | 4         | 2.35%   |
| France      | 4         | 2.35%   |
| UK          | 3         | 1.76%   |
| Switzerland | 3         | 1.76%   |
| New Zealand | 3         | 1.76%   |
| Finland     | 3         | 1.76%   |
| Australia   | 3         | 1.76%   |
| Turkey      | 2         | 1.18%   |
| Serbia      | 2         | 1.18%   |
| Indonesia   | 2         | 1.18%   |
| Hungary     | 2         | 1.18%   |
| Belgium     | 2         | 1.18%   |
| Austria     | 2         | 1.18%   |
| Vietnam     | 1         | 0.59%   |
| Venezuela   | 1         | 0.59%   |
| Uruguay     | 1         | 0.59%   |
| Sweden      | 1         | 0.59%   |
| Slovakia    | 1         | 0.59%   |
| Romania     | 1         | 0.59%   |
| Peru        | 1         | 0.59%   |
| Norway      | 1         | 0.59%   |
| Mexico      | 1         | 0.59%   |
| Malaysia    | 1         | 0.59%   |
| Greece      | 1         | 0.59%   |
| Ghana       | 1         | 0.59%   |
| Estonia     | 1         | 0.59%   |
| Egypt       | 1         | 0.59%   |
| Czechia     | 1         | 0.59%   |
| Colombia    | 1         | 0.59%   |
| Bulgaria    | 1         | 0.59%   |
| Belarus     | 1         | 0.59%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 4         | 2.3%    |
| Cambridge      | 3         | 1.72%   |
| Berlin         | 3         | 1.72%   |
| Walled Lake    | 2         | 1.15%   |
| Vienna         | 2         | 1.15%   |
| Vasco da Gama  | 2         | 1.15%   |
| Portland       | 2         | 1.15%   |
| Orange         | 2         | 1.15%   |
| Montreal       | 2         | 1.15%   |
| Istanbul       | 2         | 1.15%   |
| Helsinki       | 2         | 1.15%   |
| Florence       | 2         | 1.15%   |
| Ettingen       | 2         | 1.15%   |
| Doesburg       | 2         | 1.15%   |
| Casale Litta   | 2         | 1.15%   |
| Canberra       | 2         | 1.15%   |
| Buffalo        | 2         | 1.15%   |
| Budapest       | 2         | 1.15%   |
| Amsterdam      | 2         | 1.15%   |
| Zurich         | 1         | 0.57%   |
| Wermelskirchen | 1         | 0.57%   |
| Waycross       | 1         | 0.57%   |
| Warsaw         | 1         | 0.57%   |
| Volos          | 1         | 0.57%   |
| Voghera        | 1         | 0.57%   |
| Vilhelmina     | 1         | 0.57%   |
| Vancouver      | 1         | 0.57%   |
| Vaidasoo       | 1         | 0.57%   |
| Uelzen         | 1         | 0.57%   |
| Twin Falls     | 1         | 0.57%   |
| Tupelo         | 1         | 0.57%   |
| Tucson         | 1         | 0.57%   |
| Toulouse       | 1         | 0.57%   |
| Taggia         | 1         | 0.57%   |
| Tacoma         | 1         | 0.57%   |
| Sydney         | 1         | 0.57%   |
| Surprise       | 1         | 0.57%   |
| Stevens Point  | 1         | 0.57%   |
| Stadtilm       | 1         | 0.57%   |
| Soest          | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 68     | 18.43%  |
| Seagate             | 34        | 49     | 13.33%  |
| WDC                 | 33        | 38     | 12.94%  |
| Kingston            | 19        | 19     | 7.45%   |
| Crucial             | 15        | 25     | 5.88%   |
| Unknown             | 11        | 13     | 4.31%   |
| Toshiba             | 9         | 9      | 3.53%   |
| SK hynix            | 8         | 9      | 3.14%   |
| SanDisk             | 7         | 8      | 2.75%   |
| Apple               | 7         | 10     | 2.75%   |
| Intel               | 6         | 8      | 2.35%   |
| Hitachi             | 6         | 8      | 2.35%   |
| Transcend           | 4         | 4      | 1.57%   |
| PNY                 | 4         | 5      | 1.57%   |
| Corsair             | 4         | 4      | 1.57%   |
| SPCC                | 3         | 3      | 1.18%   |
| Netac               | 3         | 3      | 1.18%   |
| LITEON              | 3         | 3      | 1.18%   |
| Dogfish             | 3         | 3      | 1.18%   |
| Phison              | 2         | 2      | 0.78%   |
| OCZ                 | 2         | 2      | 0.78%   |
| Micron Technology   | 2         | 2      | 0.78%   |
| KIOXIA              | 2         | 3      | 0.78%   |
| GOODRAM             | 2         | 2      | 0.78%   |
| Apacer              | 2         | 2      | 0.78%   |
| A-DATA Technology   | 2         | 2      | 0.78%   |
| Team                | 1         | 1      | 0.39%   |
| Silicon Motion      | 1         | 1      | 0.39%   |
| SABRENT             | 1         | 1      | 0.39%   |
| MMY                 | 1         | 1      | 0.39%   |
| Maxtor              | 1         | 1      | 0.39%   |
| JMicron Technology  | 1         | 1      | 0.39%   |
| Indilinx            | 1         | 1      | 0.39%   |
| Gigabyte Technology | 1         | 1      | 0.39%   |
| GeIL                | 1         | 1      | 0.39%   |
| Fujitsu             | 1         | 1      | 0.39%   |
| CT1000MX            | 1         | 1      | 0.39%   |
| Avant               | 1         | 1      | 0.39%   |
| ASMT                | 1         | 1      | 0.39%   |
| Acer                | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD      | 6         | 2.12%   |
| Samsung SSD 980 PRO 1TB              | 4         | 1.41%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 1.41%   |
| Samsung SSD 850 EVO 250GB            | 4         | 1.41%   |
| Crucial CT120BX500SSD1 120GB         | 4         | 1.41%   |
| Unknown SD32G  32GB                  | 3         | 1.06%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 1.06%   |
| Samsung SSD 860 EVO 500GB            | 3         | 1.06%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.06%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.06%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.71%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.71%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.71%   |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 0.71%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.71%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.71%   |
| Seagate ST3500413AS 500GB            | 2         | 0.71%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.71%   |
| Samsung SSD 970 EVO 1TB              | 2         | 0.71%   |
| Samsung SSD 860 EVO M.2 500GB        | 2         | 0.71%   |
| Samsung SSD 860 250GB                | 2         | 0.71%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.71%   |
| Samsung SSD 850 EVO 1TB              | 2         | 0.71%   |
| KIOXIA KBG40ZNV256G 256GB            | 2         | 0.71%   |
| Kingston SV300S37A240G 240GB SSD     | 2         | 0.71%   |
| Kingston OM8PCP3512F-AI1 512GB       | 2         | 0.71%   |
| Dogfish SSD 128GB                    | 2         | 0.71%   |
| Crucial CT500P2SSD8 500GB            | 2         | 0.71%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.71%   |
| Corsair MP400 2TB                    | 2         | 0.71%   |
| Apple SSD SM0128G 121GB              | 2         | 0.71%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.35%   |
| WDC WD800AAJS-60M0A0 80GB            | 1         | 0.35%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 1         | 0.35%   |
| WDC WD60EZRZ-00RWYB1 6TB             | 1         | 0.35%   |
| WDC WD60EFRX-68L0BN1 6TB             | 1         | 0.35%   |
| WDC WD5002AALX-00J37A0 500GB         | 1         | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 49     | 45.95%  |
| WDC                 | 20        | 24     | 27.03%  |
| Toshiba             | 6         | 6      | 8.11%   |
| Hitachi             | 6         | 8      | 8.11%   |
| Samsung Electronics | 4         | 4      | 5.41%   |
| Unknown             | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |
| Fujitsu             | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 36     | 25.93%  |
| Kingston            | 14        | 14     | 12.96%  |
| Crucial             | 13        | 22     | 12.04%  |
| SanDisk             | 7         | 8      | 6.48%   |
| Apple               | 6         | 8      | 5.56%   |
| Transcend           | 4         | 4      | 3.7%    |
| SPCC                | 3         | 3      | 2.78%   |
| PNY                 | 3         | 3      | 2.78%   |
| Netac               | 3         | 3      | 2.78%   |
| LITEON              | 3         | 3      | 2.78%   |
| Dogfish             | 3         | 3      | 2.78%   |
| WDC                 | 2         | 2      | 1.85%   |
| OCZ                 | 2         | 2      | 1.85%   |
| GOODRAM             | 2         | 2      | 1.85%   |
| A-DATA Technology   | 2         | 2      | 1.85%   |
| SK hynix            | 1         | 1      | 0.93%   |
| MMY                 | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| Intel               | 1         | 1      | 0.93%   |
| Indilinx            | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |
| GeIL                | 1         | 1      | 0.93%   |
| CT1000MX            | 1         | 1      | 0.93%   |
| Corsair             | 1         | 1      | 0.93%   |
| Avant               | 1         | 1      | 0.93%   |
| ASMT                | 1         | 1      | 0.93%   |
| Apacer              | 1         | 1      | 0.93%   |
| Acer                | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 89        | 128    | 38.36%  |
| HDD     | 68        | 95     | 29.31%  |
| NVMe    | 63        | 82     | 27.16%  |
| MMC     | 11        | 13     | 4.74%   |
| Unknown | 1         | 1      | 0.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 122       | 215    | 60.4%   |
| NVMe | 63        | 81     | 31.19%  |
| MMC  | 11        | 13     | 5.45%   |
| SAS  | 6         | 10     | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 143    | 64.1%   |
| 0.51-1.0   | 40        | 53     | 25.64%  |
| 1.01-2.0   | 11        | 15     | 7.05%   |
| 3.01-4.0   | 2         | 2      | 1.28%   |
| 4.01-10.0  | 2         | 9      | 1.28%   |
| 2.01-3.0   | 1         | 1      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 27.17%  |
| 251-500        | 36        | 20.81%  |
| 501-1000       | 23        | 13.29%  |
| 21-50          | 15        | 8.67%   |
| 51-100         | 15        | 8.67%   |
| 1001-2000      | 14        | 8.09%   |
| 1-20           | 10        | 5.78%   |
| More than 3000 | 9         | 5.2%    |
| 2001-3000      | 4         | 2.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 35.03%  |
| 21-50          | 32        | 18.08%  |
| 101-250        | 27        | 15.25%  |
| 51-100         | 21        | 11.86%  |
| 251-500        | 15        | 8.47%   |
| 1001-2000      | 9         | 5.08%   |
| 501-1000       | 6         | 3.39%   |
| More than 3000 | 4         | 2.26%   |
| 2001-3000      | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 2         | 2      | 6.25%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 3.13%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 3.13%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 3.13%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 3.13%   |
| WDC WD10EADS-98M2B0 1TB                      | 1         | 1      | 3.13%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 3.13%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.13%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 3.13%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 3.13%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 3.13%   |
| Seagate ST380815AS 80GB                      | 1         | 1      | 3.13%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 3.13%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 3.13%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 3.13%   |
| Seagate ST320LT012-1DG14C 320GB              | 1         | 2      | 3.13%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 3.13%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 3.13%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 3.13%   |
| Maxtor 4K040H2 40GB                          | 1         | 1      | 3.13%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 3.13%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.13%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 3.13%   |
| Hitachi HDS721050CLA362 500GB                | 1         | 1      | 3.13%   |
| GOODRAM SSDPR-CL100-480-G3 480GB             | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 41.94%  |
| WDC                 | 6         | 6      | 19.35%  |
| Samsung Electronics | 5         | 6      | 16.13%  |
| Hitachi             | 2         | 3      | 6.45%   |
| Toshiba             | 1         | 1      | 3.23%   |
| Maxtor              | 1         | 1      | 3.23%   |
| Intel               | 1         | 2      | 3.23%   |
| Indilinx            | 1         | 1      | 3.23%   |
| GOODRAM             | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 14     | 59.09%  |
| WDC     | 5         | 5      | 22.73%  |
| Hitachi | 2         | 3      | 9.09%   |
| Toshiba | 1         | 1      | 4.55%   |
| Maxtor  | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 70%     |
| SSD  | 8         | 9      | 26.67%  |
| NVMe | 1         | 2      | 3.33%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 143       | 257    | 73.71%  |
| Malfunc  | 30        | 35     | 15.46%  |
| Detected | 21        | 27     | 10.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 116       | 53.46%  |
| Samsung Electronics          | 27        | 12.44%  |
| AMD                          | 20        | 9.22%   |
| SanDisk                      | 11        | 5.07%   |
| Phison Electronics           | 8         | 3.69%   |
| SK hynix                     | 7         | 3.23%   |
| Nvidia                       | 5         | 2.3%    |
| Kingston Technology Company  | 5         | 2.3%    |
| KIOXIA                       | 4         | 1.84%   |
| ASMedia Technology           | 4         | 1.84%   |
| Micron/Crucial Technology    | 2         | 0.92%   |
| Broadcom / LSI               | 2         | 0.92%   |
| ULi Electronics              | 1         | 0.46%   |
| Toshiba America Info Systems | 1         | 0.46%   |
| Silicon Motion               | 1         | 0.46%   |
| Silicon Image                | 1         | 0.46%   |
| Micron Technology            | 1         | 0.46%   |
| Marvell Technology Group     | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 5.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 4.51%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 11        | 4.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 3.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 2.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 2.05%   |
| Phison E12 NVMe Controller                                                       | 5         | 2.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 2.05%   |
| AMD 500 Series Chipset SATA Controller                                           | 5         | 2.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.64%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.64%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.64%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 4         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.64%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 1.64%   |
| SK hynix BC511                                                                   | 3         | 1.23%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 1.23%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.23%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 3         | 1.23%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 3         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 3         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.82%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.82%   |
| Samsung Electronics SATA controller                                              | 2         | 0.82%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.82%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 0.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.82%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 118       | 55.14%  |
| NVMe | 63        | 29.44%  |
| IDE  | 22        | 10.28%  |
| RAID | 10        | 4.67%   |
| SCSI | 1         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 135       | 80.36%  |
| AMD    | 33        | 19.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 2.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 1.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.19%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 1.19%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.19%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 1.19%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.19%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 2         | 1.19%   |
| Intel Core i5-3350P CPU @ 3.10GHz             | 2         | 1.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.19%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.19%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.19%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.19%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.19%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.19%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.19%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 1.19%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 0.6%    |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.6%    |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.6%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.6%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.6%    |
| Intel Pentium M processor 1.80GHz             | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.6%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 1         | 0.6%    |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.6%    |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1         | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.6%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.6%    |
| Intel Core i7-4980HQ CPU @ 2.80GHz            | 1         | 0.6%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 33        | 19.64%  |
| Intel Core i5           | 31        | 18.45%  |
| Intel Core i3           | 20        | 11.9%   |
| Other                   | 16        | 9.52%   |
| Intel Celeron           | 12        | 7.14%   |
| AMD Ryzen 7             | 12        | 7.14%   |
| Intel Core 2 Duo        | 10        | 5.95%   |
| AMD Ryzen 5             | 6         | 3.57%   |
| Intel Atom              | 4         | 2.38%   |
| Intel Xeon              | 3         | 1.79%   |
| AMD Ryzen 9             | 3         | 1.79%   |
| Intel Pentium Silver    | 2         | 1.19%   |
| AMD Ryzen 3             | 2         | 1.19%   |
| Intel Pentium M         | 1         | 0.6%    |
| Intel Pentium Dual-Core | 1         | 0.6%    |
| Intel Pentium Dual      | 1         | 0.6%    |
| Intel Genuine           | 1         | 0.6%    |
| Intel Core i9           | 1         | 0.6%    |
| AMD Turion 64 X2 Mobile | 1         | 0.6%    |
| AMD Sempron             | 1         | 0.6%    |
| AMD Ryzen Threadripper  | 1         | 0.6%    |
| AMD Ryzen 5 PRO         | 1         | 0.6%    |
| AMD Phenom II X4        | 1         | 0.6%    |
| AMD Phenom              | 1         | 0.6%    |
| AMD E                   | 1         | 0.6%    |
| AMD Athlon              | 1         | 0.6%    |
| AMD A10                 | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 39.88%  |
| 4      | 59        | 35.12%  |
| 8      | 16        | 9.52%   |
| 6      | 15        | 8.93%   |
| 12     | 5         | 2.98%   |
| 1      | 3         | 1.79%   |
| 14     | 2         | 1.19%   |
| 10     | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 166       | 98.81%  |
| 2      | 2         | 1.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 116       | 69.05%  |
| 1      | 52        | 30.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 165       | 98.21%  |
| 32-bit         | 3         | 1.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 10%     |
| 0x306a9    | 12        | 7.06%   |
| 0x206a7    | 12        | 7.06%   |
| 0x806c1    | 8         | 4.71%   |
| 0x506e3    | 6         | 3.53%   |
| 0x20655    | 6         | 3.53%   |
| 0x1067a    | 6         | 3.53%   |
| 0x306c3    | 5         | 2.94%   |
| 0x0a50000c | 5         | 2.94%   |
| 0x906ea    | 4         | 2.35%   |
| 0x806ec    | 4         | 2.35%   |
| 0x806ea    | 4         | 2.35%   |
| 0x6fd      | 4         | 2.35%   |
| 0x406e3    | 4         | 2.35%   |
| 0xa0652    | 3         | 1.76%   |
| 0x906ed    | 3         | 1.76%   |
| 0x906a3    | 3         | 1.76%   |
| 0x706a8    | 3         | 1.76%   |
| 0x306d4    | 3         | 1.76%   |
| 0x30678    | 3         | 1.76%   |
| 0x08701021 | 3         | 1.76%   |
| 0xa0671    | 2         | 1.18%   |
| 0xa0653    | 2         | 1.18%   |
| 0x906c0    | 2         | 1.18%   |
| 0x806e9    | 2         | 1.18%   |
| 0x706a1    | 2         | 1.18%   |
| 0x406c4    | 2         | 1.18%   |
| 0x306f2    | 2         | 1.18%   |
| 0x106e5    | 2         | 1.18%   |
| 0x08608103 | 2         | 1.18%   |
| 0x08600106 | 2         | 1.18%   |
| 0x08108109 | 2         | 1.18%   |
| 0x0800820d | 2         | 1.18%   |
| 0xa0655    | 1         | 0.59%   |
| 0x906e9    | 1         | 0.59%   |
| 0x806eb    | 1         | 0.59%   |
| 0x806d1    | 1         | 0.59%   |
| 0x706e5    | 1         | 0.59%   |
| 0x6fb      | 1         | 0.59%   |
| 0x6e8      | 1         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 11.83%  |
| SandyBridge      | 13        | 7.69%   |
| IvyBridge        | 13        | 7.69%   |
| Haswell          | 12        | 7.1%    |
| Zen 3            | 10        | 5.92%   |
| Skylake          | 10        | 5.92%   |
| TigerLake        | 9         | 5.33%   |
| Westmere         | 8         | 4.73%   |
| Penryn           | 7         | 4.14%   |
| Zen+             | 6         | 3.55%   |
| Zen 2            | 6         | 3.55%   |
| Silvermont       | 6         | 3.55%   |
| CometLake        | 6         | 3.55%   |
| Icelake          | 5         | 2.96%   |
| Goldmont plus    | 5         | 2.96%   |
| Core             | 5         | 2.96%   |
| Unknown          | 4         | 2.37%   |
| Nehalem          | 3         | 1.78%   |
| Broadwell        | 3         | 1.78%   |
| Zen              | 2         | 1.18%   |
| Tremont          | 2         | 1.18%   |
| P6               | 2         | 1.18%   |
| K8 Hammer        | 2         | 1.18%   |
| K10              | 2         | 1.18%   |
| Bonnell          | 2         | 1.18%   |
| Alderlake Hybrid | 2         | 1.18%   |
| K8 & K10 hybrid  | 1         | 0.59%   |
| Goldmont         | 1         | 0.59%   |
| Excavator        | 1         | 0.59%   |
| Bobcat           | 1         | 0.59%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 109       | 53.43%  |
| Nvidia                     | 55        | 26.96%  |
| AMD                        | 39        | 19.12%  |
| Matrox Electronics Systems | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 5.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 4.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 4.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.84%   |
| Intel HD Graphics 530                                                                    | 5         | 2.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.37%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.9%    |
| Intel UHD Graphics 620                                                                   | 4         | 1.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.42%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 1.42%   |
| Intel HD Graphics 620                                                                    | 3         | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.42%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.42%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.42%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.95%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.95%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.95%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.95%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.95%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.95%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.95%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.95%   |
| AMD Renoir                                                                               | 2         | 0.95%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 0.95%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 2         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 44.64%  |
| 1 x Nvidia     | 29        | 17.26%  |
| 1 x AMD        | 28        | 16.67%  |
| Intel + Nvidia | 23        | 13.69%  |
| Intel + AMD    | 5         | 2.98%   |
| 2 x AMD        | 3         | 1.79%   |
| AMD + Nvidia   | 3         | 1.79%   |
| 2 x Intel      | 1         | 0.6%    |
| 1 x Matrox     | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 133       | 77.33%  |
| Proprietary | 28        | 16.28%  |
| Unknown     | 11        | 6.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 66.86%  |
| 0.01-0.5   | 14        | 8.28%   |
| 7.01-8.0   | 12        | 7.1%    |
| 0.51-1.0   | 10        | 5.92%   |
| 1.01-2.0   | 9         | 5.33%   |
| 3.01-4.0   | 8         | 4.73%   |
| 8.01-16.0  | 2         | 1.18%   |
| 2.01-3.0   | 1         | 0.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 13.11%  |
| Samsung Electronics     | 20        | 10.93%  |
| Chimei Innolux          | 17        | 9.29%   |
| BOE                     | 14        | 7.65%   |
| LG Display              | 13        | 7.1%    |
| Hewlett-Packard         | 9         | 4.92%   |
| Apple                   | 8         | 4.37%   |
| Goldstar                | 7         | 3.83%   |
| Dell                    | 7         | 3.83%   |
| Acer                    | 6         | 3.28%   |
| Lenovo                  | 5         | 2.73%   |
| Chi Mei Optoelectronics | 5         | 2.73%   |
| Sharp                   | 4         | 2.19%   |
| PANDA                   | 4         | 2.19%   |
| Fujitsu Siemens         | 4         | 2.19%   |
| Ancor Communications    | 4         | 2.19%   |
| Sony                    | 3         | 1.64%   |
| AOC                     | 3         | 1.64%   |
| Philips                 | 2         | 1.09%   |
| Medion                  | 2         | 1.09%   |
| Iiyama                  | 2         | 1.09%   |
| Eizo                    | 2         | 1.09%   |
| Vizio                   | 1         | 0.55%   |
| Vestel Elektronik       | 1         | 0.55%   |
| Sunplus                 | 1         | 0.55%   |
| STA                     | 1         | 0.55%   |
| SAC                     | 1         | 0.55%   |
| PRI                     | 1         | 0.55%   |
| Panasonic               | 1         | 0.55%   |
| Packard Bell            | 1         | 0.55%   |
| NEC Computers           | 1         | 0.55%   |
| MSI                     | 1         | 0.55%   |
| MiTAC                   | 1         | 0.55%   |
| LTM                     | 1         | 0.55%   |
| InfoVision              | 1         | 0.55%   |
| Hitachi                 | 1         | 0.55%   |
| Grundig                 | 1         | 0.55%   |
| Gigabyte Technology     | 1         | 0.55%   |
| CPT                     | 1         | 0.55%   |
| BenQ                    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 1.08%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 1.08%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 1.08%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 1.08%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 1.08%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 1.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 1.08%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.54%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.54%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.54%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.54%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.54%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch    | 1         | 0.54%   |
| Sony CPD-200SX SNY0570 1920x1080 698x392mm 31.5-inch                     | 1         | 0.54%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.54%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.54%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.54%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch     | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch      | 1         | 0.54%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch         | 1         | 0.54%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.54%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch        | 1         | 0.54%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch    | 1         | 0.54%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 697x392mm 31.5-inch        | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 77        | 44.25%  |
| 1366x768 (WXGA)    | 31        | 17.82%  |
| 3840x2160 (4K)     | 15        | 8.62%   |
| 2560x1440 (QHD)    | 7         | 4.02%   |
| 1680x1050 (WSXGA+) | 7         | 4.02%   |
| 1920x1200 (WUXGA)  | 4         | 2.3%    |
| 1600x900 (HD+)     | 4         | 2.3%    |
| 1280x1024 (SXGA)   | 4         | 2.3%    |
| 2880x1800          | 3         | 1.72%   |
| 2560x1080          | 3         | 1.72%   |
| 1440x900 (WXGA+)   | 3         | 1.72%   |
| 1360x768           | 3         | 1.72%   |
| 1280x800 (WXGA)    | 3         | 1.72%   |
| 3440x1440          | 2         | 1.15%   |
| 3840x2400          | 1         | 0.57%   |
| 2736x1824          | 1         | 0.57%   |
| 2560x1600          | 1         | 0.57%   |
| 2256x1504          | 1         | 0.57%   |
| 2160x1440          | 1         | 0.57%   |
| 1400x1050          | 1         | 0.57%   |
| 1280x720 (HD)      | 1         | 0.57%   |
| 1024x600           | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 54        | 29.83%  |
| 23      | 14        | 7.73%   |
| 13      | 14        | 7.73%   |
| 17      | 13        | 7.18%   |
| 27      | 12        | 6.63%   |
| 24      | 11        | 6.08%   |
| 14      | 11        | 6.08%   |
| 11      | 8         | 4.42%   |
| 31      | 6         | 3.31%   |
| 22      | 6         | 3.31%   |
| 21      | 6         | 3.31%   |
| 34      | 5         | 2.76%   |
| 19      | 4         | 2.21%   |
| 84      | 3         | 1.66%   |
| 26      | 2         | 1.1%    |
| 16      | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |
| 54      | 1         | 0.55%   |
| 46      | 1         | 0.55%   |
| 40      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |
| 20      | 1         | 0.55%   |
| 18      | 1         | 0.55%   |
| 12      | 1         | 0.55%   |
| 10      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 39.89%  |
| 501-600     | 37        | 20.79%  |
| 201-300     | 19        | 10.67%  |
| 351-400     | 17        | 9.55%   |
| 401-500     | 15        | 8.43%   |
| 601-700     | 6         | 3.37%   |
| 701-800     | 5         | 2.81%   |
| 1501-2000   | 3         | 1.69%   |
| 1001-1500   | 2         | 1.12%   |
| Unknown     | 2         | 1.12%   |
| 801-900     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 127       | 75.6%   |
| 16/10 | 26        | 15.48%  |
| 5/4   | 5         | 2.98%   |
| 21/9  | 5         | 2.98%   |
| 3/2   | 3         | 1.79%   |
| 4/3   | 2         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 54        | 29.83%  |
| 201-250        | 29        | 16.02%  |
| 81-90          | 21        | 11.6%   |
| 301-350        | 13        | 7.18%   |
| 121-130        | 12        | 6.63%   |
| 351-500        | 11        | 6.08%   |
| 51-60          | 8         | 4.42%   |
| 251-300        | 8         | 4.42%   |
| 151-200        | 8         | 4.42%   |
| 71-80          | 5         | 2.76%   |
| More than 1000 | 4         | 2.21%   |
| 141-150        | 2         | 1.1%    |
| 501-1000       | 2         | 1.1%    |
| Unknown        | 2         | 1.1%    |
| 41-50          | 1         | 0.55%   |
| 91-100         | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 63        | 36.21%  |
| 121-160       | 55        | 31.61%  |
| 101-120       | 34        | 19.54%  |
| 161-240       | 10        | 5.75%   |
| More than 240 | 7         | 4.02%   |
| 1-50          | 3         | 1.72%   |
| Unknown       | 2         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 131       | 76.16%  |
| 2     | 26        | 15.12%  |
| 0     | 10        | 5.81%   |
| 3     | 5         | 2.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 89        | 33.97%  |
| Intel                    | 84        | 32.06%  |
| Qualcomm Atheros         | 29        | 11.07%  |
| Broadcom                 | 14        | 5.34%   |
| TP-Link                  | 7         | 2.67%   |
| Broadcom Limited         | 6         | 2.29%   |
| Ralink Technology        | 5         | 1.91%   |
| MediaTek                 | 5         | 1.91%   |
| Marvell Technology Group | 5         | 1.91%   |
| Nvidia                   | 4         | 1.53%   |
| Xiaomi                   | 1         | 0.38%   |
| Sierra Wireless          | 1         | 0.38%   |
| Samsung Electronics      | 1         | 0.38%   |
| Ralink                   | 1         | 0.38%   |
| NetGear                  | 1         | 0.38%   |
| Microsoft                | 1         | 0.38%   |
| Mercucys                 | 1         | 0.38%   |
| Linksys                  | 1         | 0.38%   |
| Lenovo                   | 1         | 0.38%   |
| Edimax Technology        | 1         | 0.38%   |
| Dell                     | 1         | 0.38%   |
| AVM                      | 1         | 0.38%   |
| ASUSTek Computer         | 1         | 0.38%   |
| Aquantia                 | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 62        | 20.33%  |
| Intel Wi-Fi 6 AX200                                                     | 11        | 3.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 2.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 8         | 2.62%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.64%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.64%   |
| Intel Wireless 8260                                                     | 5         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.31%   |
| Intel Wireless 3165                                                     | 4         | 1.31%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 1.31%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.98%   |
| Intel Wireless 7260                                                     | 3         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.98%   |
| Intel I211 Gigabit Network Connection                                   | 3         | 0.98%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.98%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 2         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.66%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.66%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.66%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 2         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.66%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.66%   |
| Intel Wireless 7265                                                     | 2         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 44.97%  |
| Realtek Semiconductor | 25        | 16.78%  |
| Qualcomm Atheros      | 19        | 12.75%  |
| Broadcom              | 8         | 5.37%   |
| TP-Link               | 6         | 4.03%   |
| Broadcom Limited      | 6         | 4.03%   |
| Ralink Technology     | 5         | 3.36%   |
| MediaTek              | 5         | 3.36%   |
| Sierra Wireless       | 1         | 0.67%   |
| Ralink                | 1         | 0.67%   |
| NetGear               | 1         | 0.67%   |
| Mercucys              | 1         | 0.67%   |
| Linksys               | 1         | 0.67%   |
| Edimax Technology     | 1         | 0.67%   |
| AVM                   | 1         | 0.67%   |
| ASUSTek Computer      | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 11        | 7.38%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 4.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.36%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.36%   |
| Intel Wireless 8260                                                     | 5         | 3.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.68%   |
| Intel Wireless 3165                                                     | 4         | 2.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 2.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 2.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.01%   |
| Intel Wireless 7260                                                     | 3         | 2.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.01%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 1.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.34%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.34%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 2         | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.34%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.34%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 1.34%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.34%   |
| Intel Wireless 7265                                                     | 2         | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.34%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.34%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.34%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.67%   |
| Sierra Wireless EM7455                                                  | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.67%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 79        | 53.02%  |
| Intel                    | 34        | 22.82%  |
| Qualcomm Atheros         | 13        | 8.72%   |
| Broadcom                 | 8         | 5.37%   |
| Marvell Technology Group | 5         | 3.36%   |
| Nvidia                   | 4         | 2.68%   |
| Xiaomi                   | 1         | 0.67%   |
| TP-Link                  | 1         | 0.67%   |
| Samsung Electronics      | 1         | 0.67%   |
| Microsoft                | 1         | 0.67%   |
| Lenovo                   | 1         | 0.67%   |
| Aquantia                 | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 62        | 40%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 5.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 8         | 5.16%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.94%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.94%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.29%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 1.29%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 2         | 1.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.29%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.29%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.29%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.29%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.29%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.29%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 1.29%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 2         | 1.29%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.65%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.65%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.65%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.65%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.65%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                              | 1         | 0.65%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.65%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 142       | 51.08%  |
| WiFi     | 135       | 48.56%  |
| Modem    | 1         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 63.22%  |
| Ethernet | 64        | 36.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 91        | 53.85%  |
| 1     | 71        | 42.01%  |
| 3     | 3         | 1.78%   |
| 0     | 3         | 1.78%   |
| 4     | 1         | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 72.78%  |
| Yes  | 46        | 27.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 49.07%  |
| Apple                           | 11        | 10.19%  |
| Qualcomm Atheros Communications | 9         | 8.33%   |
| Realtek Semiconductor           | 7         | 6.48%   |
| Cambridge Silicon Radio         | 6         | 5.56%   |
| Foxconn / Hon Hai               | 5         | 4.63%   |
| Broadcom                        | 5         | 4.63%   |
| IMC Networks                    | 3         | 2.78%   |
| ASUSTek Computer                | 3         | 2.78%   |
| Ralink                          | 1         | 0.93%   |
| MediaTek                        | 1         | 0.93%   |
| Lite-On Technology              | 1         | 0.93%   |
| Hewlett-Packard                 | 1         | 0.93%   |
| Dell                            | 1         | 0.93%   |
| Alps Electric                   | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 16.67%  |
| Intel AX201 Bluetooth                                                               | 11        | 10.19%  |
| Intel AX200 Bluetooth                                                               | 11        | 10.19%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 6.48%   |
| Realtek Bluetooth Radio                                                             | 6         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 4.63%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 3.7%    |
| Apple Bluetooth Host Controller                                                     | 4         | 3.7%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 2.78%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.85%   |
| Intel Bluetooth Device                                                              | 2         | 1.85%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.85%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.93%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.93%   |
| MediaTek Wireless_Device                                                            | 1         | 0.93%   |
| Lite-On Wireless_Device                                                             | 1         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.93%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.93%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.93%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.93%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.93%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.93%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.93%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.93%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.93%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.93%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.93%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.93%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 130       | 53.72%  |
| Nvidia                     | 45        | 18.6%   |
| AMD                        | 39        | 16.12%  |
| C-Media Electronics        | 4         | 1.65%   |
| ROCCAT                     | 2         | 0.83%   |
| Realtek Semiconductor      | 2         | 0.83%   |
| Creative Labs              | 2         | 0.83%   |
| BEHRINGER International    | 2         | 0.83%   |
| Unknown                    | 1         | 0.41%   |
| Texas Instruments          | 1         | 0.41%   |
| TerraTec Electronic        | 1         | 0.41%   |
| Shenzhen Riitek Technology | 1         | 0.41%   |
| Schiit Audio               | 1         | 0.41%   |
| Razer USA                  | 1         | 0.41%   |
| Plantronics                | 1         | 0.41%   |
| Logitech                   | 1         | 0.41%   |
| LG Electronics             | 1         | 0.41%   |
| Lenovo                     | 1         | 0.41%   |
| JMTek                      | 1         | 0.41%   |
| GYROCOM C&C                | 1         | 0.41%   |
| GN Netcom                  | 1         | 0.41%   |
| FIFINE 683 Microphone      | 1         | 0.41%   |
| Dell                       | 1         | 0.41%   |
| CMX Systems                | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 6.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 5.42%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 3.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 3.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.81%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.81%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 1.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.44%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.44%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.44%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4         | 1.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.08%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.08%   |
| Nvidia Audio device                                                                               | 3         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.08%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 1.08%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 1.08%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 1.08%   |
| ROCCAT Khan AIMO                                                                                  | 2         | 0.72%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.72%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 20.53%  |
| SK hynix            | 33        | 17.37%  |
| Kingston            | 24        | 12.63%  |
| Unknown             | 21        | 11.05%  |
| Micron Technology   | 16        | 8.42%   |
| Crucial             | 11        | 5.79%   |
| Corsair             | 11        | 5.79%   |
| G.Skill             | 5         | 2.63%   |
| Elpida              | 4         | 2.11%   |
| Ramaxel Technology  | 3         | 1.58%   |
| Nanya Technology    | 3         | 1.58%   |
| A-DATA Technology   | 3         | 1.58%   |
| Unknown             | 3         | 1.58%   |
| Unknown (ABCD)      | 2         | 1.05%   |
| Transcend           | 2         | 1.05%   |
| Smart               | 2         | 1.05%   |
| Team                | 1         | 0.53%   |
| PNY                 | 1         | 0.53%   |
| Patriot             | 1         | 0.53%   |
| Innodisk            | 1         | 0.53%   |
| Avant               | 1         | 0.53%   |
| ASint Technology    | 1         | 0.53%   |
| Apacer              | 1         | 0.53%   |
| 48spaces            | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 1.95%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 1.46%   |
| Unknown                                                          | 3         | 1.46%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.98%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.98%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.98%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.98%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.98%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.98%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.98%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.98%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.98%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 0.98%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.49%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.49%   |
| Transcend RAM JM800QLU-2G 2GB DIMM DDR2 2048MT/s                 | 1         | 0.49%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.49%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.49%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.49%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 45.18%  |
| DDR3    | 62        | 37.35%  |
| DDR2    | 11        | 6.63%   |
| LPDDR4  | 8         | 4.82%   |
| DDR     | 3         | 1.81%   |
| SDRAM   | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |
| LPDDR3  | 1         | 0.6%    |
| DRAM    | 1         | 0.6%    |
| DDR5    | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 110       | 66.27%  |
| DIMM         | 46        | 27.71%  |
| Row Of Chips | 10        | 6.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 35.71%  |
| 4096  | 59        | 32.42%  |
| 2048  | 27        | 14.84%  |
| 16384 | 19        | 10.44%  |
| 32768 | 6         | 3.3%    |
| 1024  | 6         | 3.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 18.18%  |
| 3200    | 31        | 17.61%  |
| 1333    | 18        | 10.23%  |
| 2667    | 16        | 9.09%   |
| 2400    | 15        | 8.52%   |
| Unknown | 10        | 5.68%   |
| 2133    | 9         | 5.11%   |
| 667     | 7         | 3.98%   |
| 3600    | 6         | 3.41%   |
| 1334    | 5         | 2.84%   |
| 4267    | 3         | 1.7%    |
| 3733    | 2         | 1.14%   |
| 3400    | 2         | 1.14%   |
| 2933    | 2         | 1.14%   |
| 2666    | 2         | 1.14%   |
| 2048    | 2         | 1.14%   |
| 1067    | 2         | 1.14%   |
| 800     | 2         | 1.14%   |
| 333     | 2         | 1.14%   |
| 8400    | 1         | 0.57%   |
| 4800    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 3466    | 1         | 0.57%   |
| 1866    | 1         | 0.57%   |
| 1800    | 1         | 0.57%   |
| 1639    | 1         | 0.57%   |
| 166     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 3         | 37.5%   |
| Brother Industries | 3         | 37.5%   |
| Hewlett-Packard    | 2         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 12.5%   |
| HP LaserJet 1022         | 1         | 12.5%   |
| Canon MG5700 series      | 1         | 12.5%   |
| Canon MF641C             | 1         | 12.5%   |
| Canon LiDE 400           | 1         | 12.5%   |
| Brother MFC-7340         | 1         | 12.5%   |
| Brother HL-2150N series  | 1         | 12.5%   |
| Brother DCP-L2540DW      | 1         | 12.5%   |

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


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 18.1%   |
| Acer                                   | 12        | 11.43%  |
| Microdia                               | 11        | 10.48%  |
| Realtek Semiconductor                  | 9         | 8.57%   |
| Logitech                               | 6         | 5.71%   |
| IMC Networks                           | 6         | 5.71%   |
| Sunplus Innovation Technology          | 5         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.76%   |
| Apple                                  | 5         | 4.76%   |
| Quanta                                 | 4         | 3.81%   |
| Lite-On Technology                     | 4         | 3.81%   |
| Ricoh                                  | 3         | 2.86%   |
| Suyin                                  | 2         | 1.9%    |
| Silicon Motion                         | 2         | 1.9%    |
| Microsoft                              | 2         | 1.9%    |
| Z-Star Microelectronics                | 1         | 0.95%   |
| Y Media                                | 1         | 0.95%   |
| Primax Electronics                     | 1         | 0.95%   |
| Luxvisions Innotech Limited            | 1         | 0.95%   |
| LG Electronics                         | 1         | 0.95%   |
| Lenovo                                 | 1         | 0.95%   |
| Goodong Industry                       | 1         | 0.95%   |
| Generalplus Technology                 | 1         | 0.95%   |
| Arkmicro Technologies                  | 1         | 0.95%   |
| Alcor Micro                            | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 5         | 4.72%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 2.83%   |
| Chicony Integrated Camera                           | 3         | 2.83%   |
| Acer Integrated Camera                              | 3         | 2.83%   |
| Acer BisonCam,NB Pro                                | 3         | 2.83%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.89%   |
| Realtek USB Camera                                  | 2         | 1.89%   |
| Quanta HD User Facing                               | 2         | 1.89%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.89%   |
| Logitech Webcam C930e                               | 2         | 1.89%   |
| Logitech Webcam C270                                | 2         | 1.89%   |
| IMC Networks Integrated Camera                      | 2         | 1.89%   |
| Chicony HD User Facing                              | 2         | 1.89%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.89%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.89%   |
| Apple Built-in iSight                               | 2         | 1.89%   |
| Acer HD Webcam                                      | 2         | 1.89%   |
| Acer BisonCam, NB Pro                               | 2         | 1.89%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.94%   |
| Y Media USB Camera                                  | 1         | 0.94%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.94%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.94%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.94%   |
| Sunplus HD 720P webcam                              | 1         | 0.94%   |
| Sunplus ASUS Webcam                                 | 1         | 0.94%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.94%   |
| Silicon Motion Web Camera                           | 1         | 0.94%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.94%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.94%   |
| Ricoh Integrated Webcam                             | 1         | 0.94%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.94%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.94%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.94%   |
| Realtek Integrated Webcam HD                        | 1         | 0.94%   |
| Realtek Integrated Webcam                           | 1         | 0.94%   |
| Realtek EasyCamera                                  | 1         | 0.94%   |
| Realtek Built-In Video Camera                       | 1         | 0.94%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.94%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.94%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 27.78%  |
| Synaptics                  | 4         | 22.22%  |
| Shenzhen Goodix Technology | 4         | 22.22%  |
| Upek                       | 2         | 11.11%  |
| AuthenTec                  | 2         | 11.11%  |
| Microsoft                  | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 16.67%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 11.11%  |
| Unknown                                                | 2         | 11.11%  |
| Upek TCS5B Fingerprint sensor                          | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.56%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.56%   |
| Microsoft Fingerprint Reader                           | 1         | 5.56%   |
| AuthenTec AES2810                                      | 1         | 5.56%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 44.44%  |
| Alcor Micro           | 3         | 33.33%  |
| Advanced Card Systems | 2         | 22.22%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 3         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 11.11%  |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 11.11%  |
| Advanced Card Systems ACR122U                  | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 116       | 66.67%  |
| 1     | 42        | 24.14%  |
| 2     | 14        | 8.05%   |
| 3     | 2         | 1.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 30        | 42.86%  |
| Fingerprint reader       | 18        | 25.71%  |
| Chipcard                 | 7         | 10%     |
| Multimedia controller    | 5         | 7.14%   |
| Unassigned class         | 3         | 4.29%   |
| Net/wireless             | 2         | 2.86%   |
| Sound                    | 1         | 1.43%   |
| Net/ethernet             | 1         | 1.43%   |
| Dvb card                 | 1         | 1.43%   |
| Communication controller | 1         | 1.43%   |
| Camera                   | 1         | 1.43%   |

