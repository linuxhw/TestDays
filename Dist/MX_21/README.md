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

Total: 294

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | D34010WYK H14771-303        | Desktop     | [31485ae6ec](https://linux-hardware.org/?probe=31485ae6ec) | Feb 01, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [dd017ac78a](https://linux-hardware.org/?probe=dd017ac78a) | Jan 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a32a9ba13a](https://linux-hardware.org/?probe=a32a9ba13a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | Notebook    | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [554aa8592c](https://linux-hardware.org/?probe=554aa8592c) | Jan 28, 2023 |
| BESSTAR Te... | UM340                       | Desktop     | [77efbbb270](https://linux-hardware.org/?probe=77efbbb270) | Jan 27, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [e81c0bcfc4](https://linux-hardware.org/?probe=e81c0bcfc4) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7671c99c3c](https://linux-hardware.org/?probe=7671c99c3c) | Jan 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| HP            | 3396                        | Desktop     | [2085b91098](https://linux-hardware.org/?probe=2085b91098) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [d41fde4498](https://linux-hardware.org/?probe=d41fde4498) | Jan 15, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [9c3ea14006](https://linux-hardware.org/?probe=9c3ea14006) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | Notebook    | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| ASUSTek       | H81M-E                      | Desktop     | [165bb4a9ab](https://linux-hardware.org/?probe=165bb4a9ab) | Jan 06, 2023 |
| Toshiba       | Satellite M70               | Notebook    | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [21e5ad204d](https://linux-hardware.org/?probe=21e5ad204d) | Jan 04, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [00dddfca31](https://linux-hardware.org/?probe=00dddfca31) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [677feeeca9](https://linux-hardware.org/?probe=677feeeca9) | Jan 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [c3d5155637](https://linux-hardware.org/?probe=c3d5155637) | Jan 01, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [3a3375e173](https://linux-hardware.org/?probe=3a3375e173) | Dec 29, 2022 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [f422489705](https://linux-hardware.org/?probe=f422489705) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c195f58592](https://linux-hardware.org/?probe=c195f58592) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [148add29a4](https://linux-hardware.org/?probe=148add29a4) | Dec 24, 2022 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [70e125f0d0](https://linux-hardware.org/?probe=70e125f0d0) | Dec 23, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6487bbd7b7](https://linux-hardware.org/?probe=6487bbd7b7) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| SIRAGON       | AIO-5150                    | Desktop     | [90476603fa](https://linux-hardware.org/?probe=90476603fa) | Dec 04, 2022 |
| Acer          | Aspire ES1-732              | Notebook    | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.0-13-amd64            | 19        | 8.6%    |
| 5.10.0-9-amd64             | 18        | 8.14%   |
| 5.10.0-19-amd64            | 17        | 7.69%   |
| 5.14.0-4mx-amd64           | 16        | 7.24%   |
| 5.10.0-18-amd64            | 16        | 7.24%   |
| 5.10.0-20-amd64            | 13        | 5.88%   |
| 5.10.0-16-amd64            | 13        | 5.88%   |
| 5.16.0-5mx-amd64           | 12        | 5.43%   |
| 5.10.0-11-amd64            | 8         | 3.62%   |
| 5.18.0-4mx-amd64           | 6         | 2.71%   |
| 5.10.0-15-amd64            | 6         | 2.71%   |
| 5.10.0-14-amd64            | 6         | 2.71%   |
| 6.0.0-4mx-amd64            | 4         | 1.81%   |
| 5.19.0-2mx-amd64           | 4         | 1.81%   |
| 5.10.0-17-amd64            | 4         | 1.81%   |
| 5.10.0-10-amd64            | 4         | 1.81%   |
| 6.0.0-3mx-amd64            | 3         | 1.36%   |
| 5.16.0-6mx-amd64           | 3         | 1.36%   |
| 5.16.0-4mx-amd64           | 2         | 0.9%    |
| 5.16.0-18.1-liquorix-amd64 | 2         | 0.9%    |
| 5.14.0-3mx-amd64           | 2         | 0.9%    |
| 5.10.0-8-amd64             | 2         | 0.9%    |
| 5.10.0-21-amd64            | 2         | 0.9%    |
| 5.10.0-18-686-pae          | 2         | 0.9%    |
| 5.10.0-13-686-pae          | 2         | 0.9%    |
| 5.10.0-12-amd64            | 2         | 0.9%    |
| 5.10.0-11-686-pae          | 2         | 0.9%    |
| 6.1.0-2mx-amd64            | 1         | 0.45%   |
| 6.0.5-x64v1-xanmod1        | 1         | 0.45%   |
| 6.0.0-4mx-rt-amd64         | 1         | 0.45%   |
| 6.0.0-13.3-liquorix-amd64  | 1         | 0.45%   |
| 6.0.0-11.2-liquorix-amd64  | 1         | 0.45%   |
| 5.19.0-4.2-liquorix-amd64  | 1         | 0.45%   |
| 5.19.0-17.2-liquorix-amd64 | 1         | 0.45%   |
| 5.19.0-14.1-liquorix-amd64 | 1         | 0.45%   |
| 5.19.0-12.1-liquorix-amd64 | 1         | 0.45%   |
| 5.18.0-3-amd64             | 1         | 0.45%   |
| 5.18.0-0.deb11.4-amd64     | 1         | 0.45%   |
| 5.17.0-5.2-liquorix-amd64  | 1         | 0.45%   |
| 5.17.0-3mx-amd64           | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 132       | 61.97%  |
| 5.16.0   | 20        | 9.39%   |
| 5.14.0   | 19        | 8.92%   |
| 6.0.0    | 10        | 4.69%   |
| 5.19.0   | 8         | 3.76%   |
| 5.18.0   | 8         | 3.76%   |
| 5.17.0   | 5         | 2.35%   |
| 5.15.0   | 3         | 1.41%   |
| 4.19.0   | 2         | 0.94%   |
| 6.1.0    | 1         | 0.47%   |
| 6.0.5    | 1         | 0.47%   |
| 5.10.82  | 1         | 0.47%   |
| 5.10.52  | 1         | 0.47%   |
| 5.10.111 | 1         | 0.47%   |
| Unknown  | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 135       | 63.38%  |
| 5.16    | 20        | 9.39%   |
| 5.14    | 19        | 8.92%   |
| 6.0     | 11        | 5.16%   |
| 5.19    | 8         | 3.76%   |
| 5.18    | 8         | 3.76%   |
| 5.17    | 5         | 2.35%   |
| 5.15    | 3         | 1.41%   |
| 4.19    | 2         | 0.94%   |
| 6.1     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 196       | 96.08%  |
| i686   | 8         | 3.92%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 149       | 71.98%  |
| KDE5             | 45        | 21.74%  |
| Budgie           | 3         | 1.45%   |
| Unknown          | 3         | 1.45%   |
| lightdm-xsession | 2         | 0.97%   |
| GNOME            | 2         | 0.97%   |
| LXQt             | 1         | 0.48%   |
| i3               | 1         | 0.48%   |
| GNOME Classic    | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 202       | 99.02%  |
| Tty  | 2         | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 156       | 75.73%  |
| SDDM    | 43        | 20.87%  |
| SLiM    | 5         | 2.43%   |
| GDM     | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 95        | 46.12%  |
| de_DE   | 31        | 15.05%  |
| it_IT   | 13        | 6.31%   |
| en_GB   | 11        | 5.34%   |
| ru_RU   | 7         | 3.4%    |
| pl_PL   | 4         | 1.94%   |
| fr_FR   | 4         | 1.94%   |
| es_ES   | 4         | 1.94%   |
| Unknown | 4         | 1.94%   |
| pt_BR   | 3         | 1.46%   |
| en_NZ   | 3         | 1.46%   |
| en_AU   | 3         | 1.46%   |
| de_CH   | 3         | 1.46%   |
| tr_TR   | 2         | 0.97%   |
| nl_NL   | 2         | 0.97%   |
| hu_HU   | 2         | 0.97%   |
| fi_FI   | 2         | 0.97%   |
| bg_BG   | 2         | 0.97%   |
| sv_SE   | 1         | 0.49%   |
| sk_SK   | 1         | 0.49%   |
| nb_NO   | 1         | 0.49%   |
| id_ID   | 1         | 0.49%   |
| es_VE   | 1         | 0.49%   |
| es_UY   | 1         | 0.49%   |
| es_PE   | 1         | 0.49%   |
| es_MX   | 1         | 0.49%   |
| es_CO   | 1         | 0.49%   |
| es_AR   | 1         | 0.49%   |
| da_DK   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 132       | 64.71%  |
| BIOS | 72        | 35.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 173       | 83.98%  |
| Overlay  | 23        | 11.17%  |
| Btrfs    | 6         | 2.91%   |
| Xfs      | 1         | 0.49%   |
| Reiserfs | 1         | 0.49%   |
| F2fs     | 1         | 0.49%   |
| Ext3     | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 147       | 72.06%  |
| MBR     | 55        | 26.96%  |
| Unknown | 2         | 0.98%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 69.08%  |
| Yes       | 64        | 30.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 50.49%  |
| Yes       | 102       | 49.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 30        | 14.71%  |
| ASUSTek Computer            | 27        | 13.24%  |
| Hewlett-Packard             | 22        | 10.78%  |
| Dell                        | 22        | 10.78%  |
| Apple                       | 12        | 5.88%   |
| MSI                         | 11        | 5.39%   |
| Gigabyte Technology         | 11        | 5.39%   |
| Acer                        | 8         | 3.92%   |
| Sony                        | 7         | 3.43%   |
| Intel                       | 5         | 2.45%   |
| Toshiba                     | 4         | 1.96%   |
| ASRock                      | 4         | 1.96%   |
| Samsung Electronics         | 3         | 1.47%   |
| Medion                      | 3         | 1.47%   |
| Alienware                   | 3         | 1.47%   |
| ZOTAC                       | 2         | 0.98%   |
| Pegatron                    | 2         | 0.98%   |
| Fujitsu Siemens             | 2         | 0.98%   |
| Fujitsu                     | 2         | 0.98%   |
| Biostar                     | 2         | 0.98%   |
| win element                 | 1         | 0.49%   |
| Vulcan Electronics          | 1         | 0.49%   |
| TUXEDO                      | 1         | 0.49%   |
| Sun Microsystems            | 1         | 0.49%   |
| SIRAGON                     | 1         | 0.49%   |
| Shenzhen Wangang Technology | 1         | 0.49%   |
| SANTECH                     | 1         | 0.49%   |
| Notebook                    | 1         | 0.49%   |
| MP                          | 1         | 0.49%   |
| Microsoft                   | 1         | 0.49%   |
| Huanan                      | 1         | 0.49%   |
| GEO                         | 1         | 0.49%   |
| GALAX                       | 1         | 0.49%   |
| Framework                   | 1         | 0.49%   |
| Foxconn                     | 1         | 0.49%   |
| efirstview                  | 1         | 0.49%   |
| Chuwi                       | 1         | 0.49%   |
| BESSTAR Tech                | 1         | 0.49%   |
| AZW                         | 1         | 0.49%   |
| AOpen                       | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 3         | 1.47%   |
| Unknown                                      | 3         | 1.47%   |
| Dell OptiPlex 755                            | 2         | 0.98%   |
| ASUS ROG Maximus XIII HERO                   | 2         | 0.98%   |
| Apple MacBookAir7,2                          | 2         | 0.98%   |
| ZOTAC ZBOX-ECM73070C/53060C                  | 1         | 0.49%   |
| win element MoreFine S500+                   | 1         | 0.49%   |
| Vulcan Excursion XB                          | 1         | 0.49%   |
| TUXEDO N7x0WU                                | 1         | 0.49%   |
| Toshiba Satellite M70                        | 1         | 0.49%   |
| Toshiba Satellite L650                       | 1         | 0.49%   |
| Toshiba Satellite C845                       | 1         | 0.49%   |
| Toshiba PORTEGE Z30-C                        | 1         | 0.49%   |
| Sun Microsystems Sun Ultra 40 M2 Workstation | 1         | 0.49%   |
| Sony VPCYB3V1E                               | 1         | 0.49%   |
| Sony VPCSB1V9R                               | 1         | 0.49%   |
| Sony VPCF119FX                               | 1         | 0.49%   |
| Sony VPCEH2N1E                               | 1         | 0.49%   |
| Sony VPCEC3S1E                               | 1         | 0.49%   |
| Sony VGN-TZ3RXN_B                            | 1         | 0.49%   |
| Sony SVE1513Q1ESI                            | 1         | 0.49%   |
| SIRAGON AIO-5150                             | 1         | 0.49%   |
| Shenzhen Wangang AERO 2 Pro                  | 1         | 0.49%   |
| SANTECH X170KM-G                             | 1         | 0.49%   |
| Samsung NC210/NC110                          | 1         | 0.49%   |
| Samsung 350V5C/351V5C/3540VC/3440VC          | 1         | 0.49%   |
| Samsung 340XAA/350XAA/550XAA                 | 1         | 0.49%   |
| Pegatron FQ425AA-ABA a6655f                  | 1         | 0.49%   |
| Pegatron 2AD5                                | 1         | 0.49%   |
| Notebook PD5x_7xPNP_PNN_PNT                  | 1         | 0.49%   |
| MSI MS-7C91                                  | 1         | 0.49%   |
| MSI MS-7C37                                  | 1         | 0.49%   |
| MSI MS-7B98                                  | 1         | 0.49%   |
| MSI MS-7A63                                  | 1         | 0.49%   |
| MSI MS-7A34                                  | 1         | 0.49%   |
| MSI MS-7917                                  | 1         | 0.49%   |
| MSI MS-7758                                  | 1         | 0.49%   |
| MSI Modern 14 B11MOL                         | 1         | 0.49%   |
| MSI GV62 8RD                                 | 1         | 0.49%   |
| MSI GF63 Thin 9SC                            | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 14        | 6.86%   |
| Dell OptiPlex        | 6         | 2.94%   |
| HP Compaq            | 5         | 2.45%   |
| Dell Latitude        | 4         | 1.96%   |
| ASUS ROG             | 4         | 1.96%   |
| Toshiba Satellite    | 3         | 1.47%   |
| Lenovo IdeaPad       | 3         | 1.47%   |
| HP ProBook           | 3         | 1.47%   |
| HP EliteBook         | 3         | 1.47%   |
| Dell Vostro          | 3         | 1.47%   |
| Dell Precision       | 3         | 1.47%   |
| Dell Inspiron        | 3         | 1.47%   |
| ASUS All             | 3         | 1.47%   |
| Acer Aspire          | 3         | 1.47%   |
| Unknown              | 3         | 1.47%   |
| Lenovo IdeaCentre    | 2         | 0.98%   |
| HP Laptop            | 2         | 0.98%   |
| HP ENVY              | 2         | 0.98%   |
| Gigabyte B550M       | 2         | 0.98%   |
| ASUS TUF             | 2         | 0.98%   |
| ASUS P5GC-MX         | 2         | 0.98%   |
| ASUS ASUS            | 2         | 0.98%   |
| Apple MacBookPro11   | 2         | 0.98%   |
| Apple MacBookAir7    | 2         | 0.98%   |
| Alienware m15        | 2         | 0.98%   |
| Acer Swift           | 2         | 0.98%   |
| Acer Nitro           | 2         | 0.98%   |
| ZOTAC ZBOX-ECM73070C | 1         | 0.49%   |
| win element MoreFine | 1         | 0.49%   |
| Vulcan Excursion     | 1         | 0.49%   |
| TUXEDO N7x0WU        | 1         | 0.49%   |
| Toshiba PORTEGE      | 1         | 0.49%   |
| Sun Microsystems Sun | 1         | 0.49%   |
| Sony VPCYB3V1E       | 1         | 0.49%   |
| Sony VPCSB1V9R       | 1         | 0.49%   |
| Sony VPCF119FX       | 1         | 0.49%   |
| Sony VPCEH2N1E       | 1         | 0.49%   |
| Sony VPCEC3S1E       | 1         | 0.49%   |
| Sony VGN-TZ3RXN      | 1         | 0.49%   |
| Sony SVE1513Q1ESI    | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 30        | 14.71%  |
| 2020    | 19        | 9.31%   |
| 2018    | 18        | 8.82%   |
| 2019    | 15        | 7.35%   |
| 2015    | 14        | 6.86%   |
| 2011    | 13        | 6.37%   |
| 2010    | 13        | 6.37%   |
| 2016    | 12        | 5.88%   |
| 2012    | 12        | 5.88%   |
| 2013    | 11        | 5.39%   |
| 2022    | 9         | 4.41%   |
| 2007    | 8         | 3.92%   |
| 2014    | 7         | 3.43%   |
| 2009    | 7         | 3.43%   |
| 2017    | 6         | 2.94%   |
| 2008    | 5         | 2.45%   |
| 2006    | 2         | 0.98%   |
| 2005    | 2         | 0.98%   |
| Unknown | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 118       | 57.84%  |
| Desktop     | 66        | 32.35%  |
| Convertible | 7         | 3.43%   |
| Mini pc     | 6         | 2.94%   |
| All in one  | 4         | 1.96%   |
| Server      | 2         | 0.98%   |
| Tablet      | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 202       | 99.02%  |
| Enabled  | 2         | 0.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 55        | 26.96%  |
| 8.01-16.0   | 44        | 21.57%  |
| 16.01-24.0  | 34        | 16.67%  |
| 32.01-64.0  | 25        | 12.25%  |
| 3.01-4.0    | 25        | 12.25%  |
| 2.01-3.0    | 6         | 2.94%   |
| 1.01-2.0    | 6         | 2.94%   |
| 64.01-256.0 | 5         | 2.45%   |
| 24.01-32.0  | 2         | 0.98%   |
| 0.51-1.0    | 2         | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 66        | 30.56%  |
| 2.01-3.0   | 63        | 29.17%  |
| 3.01-4.0   | 36        | 16.67%  |
| 4.01-8.0   | 30        | 13.89%  |
| 0.51-1.0   | 12        | 5.56%   |
| 8.01-16.0  | 7         | 3.24%   |
| 16.01-24.0 | 1         | 0.46%   |
| 0.01-0.5   | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 115       | 55.29%  |
| 2      | 50        | 24.04%  |
| 3      | 27        | 12.98%  |
| 4      | 8         | 3.85%   |
| 8      | 3         | 1.44%   |
| 5      | 3         | 1.44%   |
| 0      | 2         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 131       | 64.22%  |
| Yes       | 73        | 35.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 176       | 86.27%  |
| No        | 28        | 13.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 79.02%  |
| No        | 43        | 20.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 61.27%  |
| No        | 79        | 38.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 54        | 26.21%  |
| Germany     | 31        | 15.05%  |
| Italy       | 19        | 9.22%   |
| Canada      | 8         | 3.88%   |
| Russia      | 7         | 3.4%    |
| Poland      | 6         | 2.91%   |
| Netherlands | 6         | 2.91%   |
| UK          | 5         | 2.43%   |
| France      | 5         | 2.43%   |
| Finland     | 5         | 2.43%   |
| Brazil      | 5         | 2.43%   |
| Spain       | 4         | 1.94%   |
| India       | 4         | 1.94%   |
| Australia   | 4         | 1.94%   |
| Switzerland | 3         | 1.46%   |
| New Zealand | 3         | 1.46%   |
| Venezuela   | 2         | 0.97%   |
| Turkey      | 2         | 0.97%   |
| Sweden      | 2         | 0.97%   |
| Serbia      | 2         | 0.97%   |
| Romania     | 2         | 0.97%   |
| Indonesia   | 2         | 0.97%   |
| Hungary     | 2         | 0.97%   |
| Bulgaria    | 2         | 0.97%   |
| Belgium     | 2         | 0.97%   |
| Austria     | 2         | 0.97%   |
| Vietnam     | 1         | 0.49%   |
| Uruguay     | 1         | 0.49%   |
| Slovakia    | 1         | 0.49%   |
| Peru        | 1         | 0.49%   |
| Norway      | 1         | 0.49%   |
| Mexico      | 1         | 0.49%   |
| Malaysia    | 1         | 0.49%   |
| Greece      | 1         | 0.49%   |
| Ghana       | 1         | 0.49%   |
| Estonia     | 1         | 0.49%   |
| Egypt       | 1         | 0.49%   |
| Denmark     | 1         | 0.49%   |
| Czechia     | 1         | 0.49%   |
| Colombia    | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| St Petersburg  | 4         | 1.88%   |
| Cambridge      | 3         | 1.41%   |
| Berlin         | 3         | 1.41%   |
| Amsterdam      | 3         | 1.41%   |
| Walled Lake    | 2         | 0.94%   |
| Vienna         | 2         | 0.94%   |
| Vasco da Gama  | 2         | 0.94%   |
| Rome           | 2         | 0.94%   |
| Portland       | 2         | 0.94%   |
| Orange         | 2         | 0.94%   |
| New York       | 2         | 0.94%   |
| Moscow         | 2         | 0.94%   |
| Montreal       | 2         | 0.94%   |
| Istanbul       | 2         | 0.94%   |
| Houston        | 2         | 0.94%   |
| Helsinki       | 2         | 0.94%   |
| Florence       | 2         | 0.94%   |
| Ettingen       | 2         | 0.94%   |
| Doesburg       | 2         | 0.94%   |
| Casale Litta   | 2         | 0.94%   |
| Canberra       | 2         | 0.94%   |
| Buffalo        | 2         | 0.94%   |
| Budapest       | 2         | 0.94%   |
| Zurich         | 1         | 0.47%   |
| Wilde          | 1         | 0.47%   |
| Wermelskirchen | 1         | 0.47%   |
| Waycross       | 1         | 0.47%   |
| Warsaw         | 1         | 0.47%   |
| Volos          | 1         | 0.47%   |
| Voghera        | 1         | 0.47%   |
| Vilhelmina     | 1         | 0.47%   |
| Vancouver      | 1         | 0.47%   |
| Vaidasoo       | 1         | 0.47%   |
| Uelzen         | 1         | 0.47%   |
| Twin Falls     | 1         | 0.47%   |
| Tupelo         | 1         | 0.47%   |
| Tuglie         | 1         | 0.47%   |
| Tucson         | 1         | 0.47%   |
| Toulouse       | 1         | 0.47%   |
| The Dalles     | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 55        | 84     | 17.52%  |
| Seagate                   | 42        | 58     | 13.38%  |
| WDC                       | 37        | 44     | 11.78%  |
| Kingston                  | 26        | 28     | 8.28%   |
| Crucial                   | 17        | 29     | 5.41%   |
| Toshiba                   | 16        | 17     | 5.1%    |
| Unknown                   | 13        | 16     | 4.14%   |
| SanDisk                   | 10        | 11     | 3.18%   |
| Hitachi                   | 10        | 12     | 3.18%   |
| SK hynix                  | 9         | 10     | 2.87%   |
| Intel                     | 7         | 9      | 2.23%   |
| Apple                     | 7         | 11     | 2.23%   |
| PNY                       | 6         | 7      | 1.91%   |
| Transcend                 | 5         | 5      | 1.59%   |
| SPCC                      | 4         | 4      | 1.27%   |
| Corsair                   | 4         | 4      | 1.27%   |
| Netac                     | 3         | 3      | 0.96%   |
| Micron Technology         | 3         | 3      | 0.96%   |
| LITEON                    | 3         | 3      | 0.96%   |
| Dogfish                   | 3         | 3      | 0.96%   |
| China                     | 3         | 3      | 0.96%   |
| Phison                    | 2         | 3      | 0.64%   |
| OCZ                       | 2         | 2      | 0.64%   |
| KIOXIA                    | 2         | 3      | 0.64%   |
| GOODRAM                   | 2         | 2      | 0.64%   |
| Apacer                    | 2         | 2      | 0.64%   |
| A-DATA Technology         | 2         | 2      | 0.64%   |
| Team                      | 1         | 1      | 0.32%   |
| Silicon Motion            | 1         | 1      | 0.32%   |
| SABRENT                   | 1         | 1      | 0.32%   |
| Phison Electronics        | 1         | 1      | 0.32%   |
| MMY                       | 1         | 1      | 0.32%   |
| Micron/Crucial Technology | 1         | 1      | 0.32%   |
| Maxtor                    | 1         | 1      | 0.32%   |
| JMicron Technology        | 1         | 1      | 0.32%   |
| Indilinx                  | 1         | 1      | 0.32%   |
| HGST                      | 1         | 1      | 0.32%   |
| Gigabyte Technology       | 1         | 1      | 0.32%   |
| GeIL                      | 1         | 1      | 0.32%   |
| Fujitsu                   | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD      | 6         | 1.71%   |
| Samsung SSD 980 PRO 1TB              | 5         | 1.43%   |
| Samsung SSD 850 EVO 250GB            | 5         | 1.43%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 1.14%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.14%   |
| Crucial CT120BX500SSD1 120GB         | 4         | 1.14%   |
| Unknown SD32G  32GB                  | 3         | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.86%   |
| SanDisk SDSSDA240G 240GB             | 3         | 0.86%   |
| Kingston SV300S37A240G 240GB SSD     | 3         | 0.86%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 0.86%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.86%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 0.86%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 0.86%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 2         | 0.57%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.57%   |
| Unknown SD/MMC/MS PRO 2GB            | 2         | 0.57%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.57%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.57%   |
| SPCC Solid State Disk 256GB          | 2         | 0.57%   |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 0.57%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.57%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.57%   |
| Seagate ST3500413AS 500GB            | 2         | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB       | 2         | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 0.57%   |
| Samsung SSD 970 PRO 512GB            | 2         | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.57%   |
| Samsung SSD 970 EVO 1TB              | 2         | 0.57%   |
| Samsung SSD 870 EVO 500GB            | 2         | 0.57%   |
| Samsung SSD 860 EVO M.2 500GB        | 2         | 0.57%   |
| Samsung SSD 860 250GB                | 2         | 0.57%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.57%   |
| Samsung SSD 850 EVO 1TB              | 2         | 0.57%   |
| Samsung SSD 840 Series 120GB         | 2         | 0.57%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.57%   |
| KIOXIA KBG40ZNV256G 256GB            | 2         | 0.57%   |
| Kingston OM8PCP3512F-AI1 512GB       | 2         | 0.57%   |
| Hitachi HTS54503 320GB               | 2         | 0.57%   |
| Dogfish SSD 128GB                    | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 58     | 42.42%  |
| WDC                 | 24        | 30     | 24.24%  |
| Toshiba             | 11        | 12     | 11.11%  |
| Hitachi             | 10        | 12     | 10.1%   |
| Samsung Electronics | 4         | 4      | 4.04%   |
| Unknown             | 2         | 2      | 2.02%   |
| SABRENT             | 1         | 1      | 1.01%   |
| Maxtor              | 1         | 1      | 1.01%   |
| HGST                | 1         | 1      | 1.01%   |
| Fujitsu             | 1         | 1      | 1.01%   |
| External            | 1         | 1      | 1.01%   |
| Apple               | 1         | 1      | 1.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 43     | 25.19%  |
| Kingston            | 18        | 19     | 13.74%  |
| Crucial             | 15        | 26     | 11.45%  |
| SanDisk             | 10        | 11     | 7.63%   |
| Apple               | 6         | 9      | 4.58%   |
| Transcend           | 5         | 5      | 3.82%   |
| PNY                 | 5         | 5      | 3.82%   |
| SPCC                | 4         | 4      | 3.05%   |
| Netac               | 3         | 3      | 2.29%   |
| LITEON              | 3         | 3      | 2.29%   |
| Dogfish             | 3         | 3      | 2.29%   |
| China               | 3         | 3      | 2.29%   |
| WDC                 | 2         | 2      | 1.53%   |
| Toshiba             | 2         | 2      | 1.53%   |
| OCZ                 | 2         | 2      | 1.53%   |
| GOODRAM             | 2         | 2      | 1.53%   |
| A-DATA Technology   | 2         | 2      | 1.53%   |
| SK hynix            | 1         | 1      | 0.76%   |
| MMY                 | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 1      | 0.76%   |
| Intel               | 1         | 1      | 0.76%   |
| Indilinx            | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| GeIL                | 1         | 1      | 0.76%   |
| CT1000MX            | 1         | 1      | 0.76%   |
| Corsair             | 1         | 1      | 0.76%   |
| Avant               | 1         | 1      | 0.76%   |
| ASMT                | 1         | 1      | 0.76%   |
| Apacer              | 1         | 1      | 0.76%   |
| Acer                | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 109       | 157    | 38.38%  |
| HDD     | 88        | 124    | 30.99%  |
| NVMe    | 74        | 100    | 26.06%  |
| MMC     | 11        | 13     | 3.87%   |
| Unknown | 2         | 3      | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 268    | 61.07%  |
| NVMe | 74        | 100    | 30.33%  |
| MMC  | 11        | 13     | 4.51%   |
| SAS  | 10        | 16     | 4.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 121       | 174    | 61.42%  |
| 0.51-1.0   | 50        | 69     | 25.38%  |
| 1.01-2.0   | 15        | 20     | 7.61%   |
| 3.01-4.0   | 4         | 4      | 2.03%   |
| 2.01-3.0   | 3         | 3      | 1.52%   |
| 4.01-10.0  | 3         | 10     | 1.52%   |
| 10.01-20.0 | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 60        | 28.44%  |
| 251-500        | 45        | 21.33%  |
| 501-1000       | 25        | 11.85%  |
| 51-100         | 18        | 8.53%   |
| 21-50          | 17        | 8.06%   |
| 1001-2000      | 16        | 7.58%   |
| 1-20           | 12        | 5.69%   |
| More than 3000 | 10        | 4.74%   |
| 2001-3000      | 8         | 3.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 76        | 35.19%  |
| 21-50          | 39        | 18.06%  |
| 101-250        | 35        | 16.2%   |
| 51-100         | 25        | 11.57%  |
| 251-500        | 17        | 7.87%   |
| 1001-2000      | 11        | 5.09%   |
| 501-1000       | 7         | 3.24%   |
| More than 3000 | 4         | 1.85%   |
| 2001-3000      | 2         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB              | 2         | 2      | 4.88%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 1      | 2.44%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.44%   |
| WDC WD5000AAKS-40V6A0 500GB                  | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.44%   |
| WDC WD10EADS-98M2B0 1TB                      | 1         | 1      | 2.44%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 1      | 2.44%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 2.44%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.44%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 2.44%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.44%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 2.44%   |
| Seagate ST380815AS 80GB                      | 1         | 1      | 2.44%   |
| Seagate ST3500413AS 500GB                    | 1         | 1      | 2.44%   |
| Seagate ST3360320AS 360GB                    | 1         | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB              | 1         | 1      | 2.44%   |
| Seagate ST320LT012-1DG14C 320GB              | 1         | 2      | 2.44%   |
| Seagate ST250DM000-1BD141 250GB              | 1         | 1      | 2.44%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 2.44%   |
| Seagate ST1000VM002-1CT162 1TB               | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 2      | 2.44%   |
| Samsung Electronics SSD 840 Series 120GB     | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.44%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 2.44%   |
| Maxtor 4K040H2 40GB                          | 1         | 1      | 2.44%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 2.44%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 2.44%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 2.44%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.44%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 2.44%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 2.44%   |
| Hitachi HDS721050CLA362 500GB                | 1         | 1      | 2.44%   |
| HGST HTS545050A7E380 500GB                   | 1         | 1      | 2.44%   |
| GOODRAM SSDPR-CL100-480-G3 480GB             | 1         | 1      | 2.44%   |
| Crucial CT1000MX500SSD4 1TB                  | 1         | 2      | 2.44%   |
| China SSD 512GB                              | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 35%     |
| WDC                 | 6         | 6      | 15%     |
| Samsung Electronics | 6         | 7      | 15%     |
| Hitachi             | 4         | 5      | 10%     |
| Toshiba             | 2         | 2      | 5%      |
| Maxtor              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| Intel               | 1         | 2      | 2.5%    |
| Indilinx            | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| GOODRAM             | 1         | 1      | 2.5%    |
| Crucial             | 1         | 2      | 2.5%    |
| China               | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 15     | 53.85%  |
| WDC     | 5         | 5      | 19.23%  |
| Hitachi | 4         | 5      | 15.38%  |
| Toshiba | 1         | 1      | 3.85%   |
| Maxtor  | 1         | 1      | 3.85%   |
| HGST    | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 28     | 64.1%   |
| SSD  | 13        | 15     | 33.33%  |
| NVMe | 1         | 2      | 2.56%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 174       | 319    | 73.11%  |
| Malfunc  | 39        | 45     | 16.39%  |
| Detected | 25        | 33     | 10.5%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 142       | 53.58%  |
| Samsung Electronics          | 31        | 11.7%   |
| AMD                          | 28        | 10.57%  |
| SanDisk                      | 11        | 4.15%   |
| Phison Electronics           | 9         | 3.4%    |
| SK hynix                     | 8         | 3.02%   |
| Kingston Technology Company  | 8         | 3.02%   |
| Nvidia                       | 5         | 1.89%   |
| ASMedia Technology           | 5         | 1.89%   |
| KIOXIA                       | 4         | 1.51%   |
| Micron/Crucial Technology    | 3         | 1.13%   |
| Micron Technology            | 2         | 0.75%   |
| Marvell Technology Group     | 2         | 0.75%   |
| Broadcom / LSI               | 2         | 0.75%   |
| ULi Electronics              | 1         | 0.38%   |
| Toshiba America Info Systems | 1         | 0.38%   |
| Silicon Motion               | 1         | 0.38%   |
| Silicon Image                | 1         | 0.38%   |
| LSI Logic / Symbios Logic    | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 5.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 4.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 4.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 3.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 8         | 2.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 2.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.68%   |
| Phison E12 NVMe Controller                                                     | 5         | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5         | 1.68%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.68%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.34%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.34%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.34%   |
| SK hynix BC511                                                                 | 3         | 1.01%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.01%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.01%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.01%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 1.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.01%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 3         | 1.01%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 3         | 1.01%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.01%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 151       | 57.2%   |
| NVMe | 74        | 28.03%  |
| IDE  | 26        | 9.85%   |
| RAID | 11        | 4.17%   |
| SCSI | 2         | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 79.41%  |
| AMD    | 42        | 20.59%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.47%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 1.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 1.47%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.47%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.47%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.98%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.98%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 2         | 0.98%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.98%   |
| Intel Core i5-9600K CPU @ 3.70GHz             | 2         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i5-5350U CPU @ 1.80GHz             | 2         | 0.98%   |
| Intel Core i5-3350P CPU @ 3.10GHz             | 2         | 0.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.98%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 0.98%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.98%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.98%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 0.98%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.98%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.98%   |
| Intel Xeon W-2123 CPU @ 3.60GHz               | 1         | 0.49%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 0.49%   |
| Intel Xeon CPU W3565 @ 3.20GHz                | 1         | 0.49%   |
| Intel Xeon CPU E5520 @ 2.27GHz                | 1         | 0.49%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.49%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium M processor 1.80GHz             | 1         | 0.49%   |
| Intel Pentium M processor 1.73GHz             | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1         | 0.49%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 1         | 0.49%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 1         | 0.49%   |
| Intel Pentium CPU 2030M @ 2.50GHz             | 1         | 0.49%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 39        | 19.12%  |
| Intel Core i5           | 34        | 16.67%  |
| Intel Core i3           | 25        | 12.25%  |
| Other                   | 18        | 8.82%   |
| AMD Ryzen 7             | 15        | 7.35%   |
| Intel Celeron           | 14        | 6.86%   |
| Intel Core 2 Duo        | 11        | 5.39%   |
| AMD Ryzen 5             | 7         | 3.43%   |
| Intel Xeon              | 5         | 2.45%   |
| Intel Atom              | 4         | 1.96%   |
| AMD Ryzen 3             | 4         | 1.96%   |
| AMD Ryzen 9             | 3         | 1.47%   |
| Intel Pentium Silver    | 2         | 0.98%   |
| Intel Pentium M         | 2         | 0.98%   |
| Intel Pentium           | 2         | 0.98%   |
| Intel Core i9           | 2         | 0.98%   |
| AMD Athlon II X4        | 2         | 0.98%   |
| Intel Pentium Dual-Core | 1         | 0.49%   |
| Intel Pentium Dual      | 1         | 0.49%   |
| Intel Genuine           | 1         | 0.49%   |
| Intel Core M            | 1         | 0.49%   |
| Intel Core 2            | 1         | 0.49%   |
| AMD Turion 64 X2 Mobile | 1         | 0.49%   |
| AMD Sempron             | 1         | 0.49%   |
| AMD Ryzen Threadripper  | 1         | 0.49%   |
| AMD Ryzen 5 PRO         | 1         | 0.49%   |
| AMD Phenom II X4        | 1         | 0.49%   |
| AMD Phenom              | 1         | 0.49%   |
| AMD E                   | 1         | 0.49%   |
| AMD Athlon              | 1         | 0.49%   |
| AMD A8                  | 1         | 0.49%   |
| AMD A10                 | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 38.73%  |
| 4      | 74        | 36.27%  |
| 8      | 22        | 10.78%  |
| 6      | 16        | 7.84%   |
| 12     | 6         | 2.94%   |
| 1      | 4         | 1.96%   |
| 14     | 2         | 0.98%   |
| 10     | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 201       | 98.53%  |
| 2      | 3         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 138       | 67.65%  |
| 1      | 66        | 32.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 200       | 98.04%  |
| 32-bit         | 4         | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 11.11%  |
| 0x306a9    | 15        | 7.25%   |
| 0x206a7    | 14        | 6.76%   |
| 0x806c1    | 8         | 3.86%   |
| 0x306c3    | 7         | 3.38%   |
| 0x20655    | 7         | 3.38%   |
| 0x1067a    | 7         | 3.38%   |
| 0x506e3    | 6         | 2.9%    |
| 0x406e3    | 6         | 2.9%    |
| 0x906ea    | 5         | 2.42%   |
| 0x806ea    | 5         | 2.42%   |
| 0x0a50000c | 5         | 2.42%   |
| 0x906ed    | 4         | 1.93%   |
| 0x806ec    | 4         | 1.93%   |
| 0x706a8    | 4         | 1.93%   |
| 0x6fd      | 4         | 1.93%   |
| 0x306d4    | 4         | 1.93%   |
| 0x08108109 | 4         | 1.93%   |
| 0xa0652    | 3         | 1.45%   |
| 0x906a3    | 3         | 1.45%   |
| 0x30678    | 3         | 1.45%   |
| 0x08701021 | 3         | 1.45%   |
| 0x08608103 | 3         | 1.45%   |
| 0xa0671    | 2         | 0.97%   |
| 0xa0653    | 2         | 0.97%   |
| 0x906e9    | 2         | 0.97%   |
| 0x906c0    | 2         | 0.97%   |
| 0x806e9    | 2         | 0.97%   |
| 0x706a1    | 2         | 0.97%   |
| 0x406c4    | 2         | 0.97%   |
| 0x40651    | 2         | 0.97%   |
| 0x306f2    | 2         | 0.97%   |
| 0x106e5    | 2         | 0.97%   |
| 0x08600106 | 2         | 0.97%   |
| 0x0800820d | 2         | 0.97%   |
| 0x010000db | 2         | 0.97%   |
| 0xa0655    | 1         | 0.48%   |
| 0x90672    | 1         | 0.48%   |
| 0x806eb    | 1         | 0.48%   |
| 0x806d1    | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 24        | 11.71%  |
| IvyBridge        | 16        | 7.8%    |
| SandyBridge      | 15        | 7.32%   |
| Haswell          | 15        | 7.32%   |
| Skylake          | 13        | 6.34%   |
| Zen 3            | 11        | 5.37%   |
| Westmere         | 10        | 4.88%   |
| Zen+             | 9         | 4.39%   |
| TigerLake        | 9         | 4.39%   |
| Penryn           | 8         | 3.9%    |
| Unknown          | 8         | 3.9%    |
| Zen 2            | 6         | 2.93%   |
| Silvermont       | 6         | 2.93%   |
| Goldmont plus    | 6         | 2.93%   |
| Core             | 6         | 2.93%   |
| CometLake        | 6         | 2.93%   |
| Icelake          | 5         | 2.44%   |
| Broadwell        | 5         | 2.44%   |
| Nehalem          | 4         | 1.95%   |
| K10              | 4         | 1.95%   |
| P6               | 3         | 1.46%   |
| Zen              | 2         | 0.98%   |
| Tremont          | 2         | 0.98%   |
| K8 Hammer        | 2         | 0.98%   |
| Goldmont         | 2         | 0.98%   |
| Bonnell          | 2         | 0.98%   |
| Alderlake Hybrid | 2         | 0.98%   |
| Puma             | 1         | 0.49%   |
| K8 & K10 hybrid  | 1         | 0.49%   |
| Excavator        | 1         | 0.49%   |
| Bobcat           | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 128       | 52.24%  |
| Nvidia                     | 66        | 26.94%  |
| AMD                        | 50        | 20.41%  |
| Matrox Electronics Systems | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 5.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.36%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.97%   |
| Intel HD Graphics 530                                                                    | 5         | 1.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.57%   |
| AMD Lucienne                                                                             | 4         | 1.57%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 1.18%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 3         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.18%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.18%   |
| Intel HD Graphics 620                                                                    | 3         | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.18%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.18%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.79%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.79%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.79%   |
| Intel HD Graphics 500                                                                    | 2         | 0.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.79%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 90        | 44.12%  |
| 1 x Nvidia     | 38        | 18.63%  |
| 1 x AMD        | 38        | 18.63%  |
| Intel + Nvidia | 24        | 11.76%  |
| Intel + AMD    | 6         | 2.94%   |
| 2 x AMD        | 3         | 1.47%   |
| AMD + Nvidia   | 3         | 1.47%   |
| 2 x Intel      | 1         | 0.49%   |
| 1 x Matrox     | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 165       | 78.95%  |
| Proprietary | 32        | 15.31%  |
| Unknown     | 12        | 5.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 64.25%  |
| 0.01-0.5   | 16        | 7.73%   |
| 0.51-1.0   | 15        | 7.25%   |
| 1.01-2.0   | 14        | 6.76%   |
| 7.01-8.0   | 13        | 6.28%   |
| 3.01-4.0   | 11        | 5.31%   |
| 8.01-16.0  | 3         | 1.45%   |
| 2.01-3.0   | 2         | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 26        | 11.76%  |
| AU Optronics            | 26        | 11.76%  |
| Chimei Innolux          | 20        | 9.05%   |
| BOE                     | 15        | 6.79%   |
| LG Display              | 14        | 6.33%   |
| Hewlett-Packard         | 11        | 4.98%   |
| Dell                    | 10        | 4.52%   |
| Lenovo                  | 9         | 4.07%   |
| Apple                   | 9         | 4.07%   |
| Goldstar                | 8         | 3.62%   |
| Acer                    | 7         | 3.17%   |
| Sony                    | 6         | 2.71%   |
| Chi Mei Optoelectronics | 6         | 2.71%   |
| PANDA                   | 5         | 2.26%   |
| Ancor Communications    | 5         | 2.26%   |
| Sharp                   | 4         | 1.81%   |
| Fujitsu Siemens         | 4         | 1.81%   |
| Eizo                    | 4         | 1.81%   |
| AOC                     | 3         | 1.36%   |
| Philips                 | 2         | 0.9%    |
| Panasonic               | 2         | 0.9%    |
| Medion                  | 2         | 0.9%    |
| Iiyama                  | 2         | 0.9%    |
| CPT                     | 2         | 0.9%    |
| BenQ                    | 2         | 0.9%    |
| Vizio                   | 1         | 0.45%   |
| Vestel Elektronik       | 1         | 0.45%   |
| Sunplus                 | 1         | 0.45%   |
| STA                     | 1         | 0.45%   |
| SAC                     | 1         | 0.45%   |
| RTK                     | 1         | 0.45%   |
| PRI                     | 1         | 0.45%   |
| Packard Bell            | 1         | 0.45%   |
| NEC Computers           | 1         | 0.45%   |
| MSI                     | 1         | 0.45%   |
| MiTAC                   | 1         | 0.45%   |
| LTM                     | 1         | 0.45%   |
| LG Philips              | 1         | 0.45%   |
| InfoVision              | 1         | 0.45%   |
| Hitachi                 | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch        | 2         | 0.88%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 2         | 0.88%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.88%   |
| Medion MD22322 MEB8101 2560x1440 699x393mm 31.6-inch                     | 2         | 0.88%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.88%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.88%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.88%   |
| Fujitsu Siemens B22W-7 LED FUS0838 1680x1050 474x296mm 22.0-inch         | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.88%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch           | 2         | 0.88%   |
| Vizio M220MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.44%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 1         | 0.44%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.44%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.44%   |
| Sony SDM-M81 SNY0480 1280x1024 359x287mm 18.1-inch                       | 1         | 0.44%   |
| Sony SDM-HS74P SNY3170 1280x1024 338x270mm 17.0-inch                     | 1         | 0.44%   |
| Sony SDM-HS53 SNY2250 1024x768 304x228mm 15.0-inch                       | 1         | 0.44%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.44%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.44%   |
| Sony CPD-200SX SNY0570 1920x1080 698x392mm 31.5-inch                     | 1         | 0.44%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.44%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.44%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.44%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.44%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch        | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch     | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM0286 1280x720 372x209mm 16.8-inch      | 1         | 0.44%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 1         | 0.44%   |
| Samsung Electronics SMB2030 SAM063C 1600x900 443x249mm 20.0-inch         | 1         | 0.44%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 1         | 0.44%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch        | 1         | 0.44%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch        | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 94        | 44.34%  |
| 1366x768 (WXGA)    | 35        | 16.51%  |
| 3840x2160 (4K)     | 16        | 7.55%   |
| 2560x1440 (QHD)    | 10        | 4.72%   |
| 1680x1050 (WSXGA+) | 8         | 3.77%   |
| 1280x1024 (SXGA)   | 8         | 3.77%   |
| 1600x900 (HD+)     | 5         | 2.36%   |
| 1280x800 (WXGA)    | 5         | 2.36%   |
| 1920x1200 (WUXGA)  | 4         | 1.89%   |
| 1440x900 (WXGA+)   | 4         | 1.89%   |
| 2880x1800          | 3         | 1.42%   |
| 2560x1080          | 3         | 1.42%   |
| 1360x768           | 3         | 1.42%   |
| 3440x1440          | 2         | 0.94%   |
| 2560x1600          | 2         | 0.94%   |
| 1280x720 (HD)      | 2         | 0.94%   |
| 1024x768 (XGA)     | 2         | 0.94%   |
| 3840x2400          | 1         | 0.47%   |
| 2736x1824          | 1         | 0.47%   |
| 2256x1504          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 1400x1050          | 1         | 0.47%   |
| 1024x600           | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 28.64%  |
| 23      | 17        | 7.73%   |
| 24      | 16        | 7.27%   |
| 13      | 16        | 7.27%   |
| 17      | 15        | 6.82%   |
| 27      | 14        | 6.36%   |
| 14      | 12        | 5.45%   |
| 21      | 10        | 4.55%   |
| 31      | 9         | 4.09%   |
| 11      | 8         | 3.64%   |
| 22      | 7         | 3.18%   |
| 34      | 5         | 2.27%   |
| 19      | 5         | 2.27%   |
| 84      | 3         | 1.36%   |
| 40      | 3         | 1.36%   |
| 26      | 2         | 0.91%   |
| 18      | 2         | 0.91%   |
| 16      | 2         | 0.91%   |
| 12      | 2         | 0.91%   |
| Unknown | 2         | 0.91%   |
| 54      | 1         | 0.45%   |
| 47      | 1         | 0.45%   |
| 46      | 1         | 0.45%   |
| 32      | 1         | 0.45%   |
| 25      | 1         | 0.45%   |
| 20      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 83        | 38.25%  |
| 501-600     | 46        | 21.2%   |
| 401-500     | 21        | 9.68%   |
| 201-300     | 21        | 9.68%   |
| 351-400     | 20        | 9.22%   |
| 601-700     | 9         | 4.15%   |
| 701-800     | 6         | 2.76%   |
| 801-900     | 3         | 1.38%   |
| 1501-2000   | 3         | 1.38%   |
| 1001-1500   | 3         | 1.38%   |
| Unknown     | 2         | 0.92%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 153       | 75.37%  |
| 16/10 | 29        | 14.29%  |
| 5/4   | 8         | 3.94%   |
| 21/9  | 5         | 2.46%   |
| 4/3   | 4         | 1.97%   |
| 3/2   | 4         | 1.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 28.77%  |
| 201-250        | 40        | 18.26%  |
| 81-90          | 23        | 10.5%   |
| 351-500        | 15        | 6.85%   |
| 301-350        | 15        | 6.85%   |
| 121-130        | 13        | 5.94%   |
| 151-200        | 11        | 5.02%   |
| 51-60          | 8         | 3.65%   |
| 251-300        | 8         | 3.65%   |
| 71-80          | 6         | 2.74%   |
| 501-1000       | 5         | 2.28%   |
| More than 1000 | 4         | 1.83%   |
| 141-150        | 3         | 1.37%   |
| Unknown        | 2         | 0.91%   |
| 61-70          | 1         | 0.46%   |
| 41-50          | 1         | 0.46%   |
| 91-100         | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 83        | 39.15%  |
| 121-160       | 61        | 28.77%  |
| 101-120       | 42        | 19.81%  |
| 161-240       | 11        | 5.19%   |
| More than 240 | 7         | 3.3%    |
| 1-50          | 6         | 2.83%   |
| Unknown       | 2         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 160       | 76.56%  |
| 2     | 33        | 15.79%  |
| 0     | 11        | 5.26%   |
| 3     | 5         | 2.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 106       | 33.23%  |
| Intel                             | 103       | 32.29%  |
| Qualcomm Atheros                  | 35        | 10.97%  |
| Broadcom                          | 17        | 5.33%   |
| TP-Link                           | 7         | 2.19%   |
| MediaTek                          | 7         | 2.19%   |
| Broadcom Limited                  | 7         | 2.19%   |
| Ralink Technology                 | 6         | 1.88%   |
| Marvell Technology Group          | 5         | 1.57%   |
| Nvidia                            | 4         | 1.25%   |
| Ralink                            | 3         | 0.94%   |
| Sierra Wireless                   | 2         | 0.63%   |
| Xiaomi                            | 1         | 0.31%   |
| Samsung Electronics               | 1         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.31%   |
| OPPO Electronics                  | 1         | 0.31%   |
| NetGear                           | 1         | 0.31%   |
| Microsoft                         | 1         | 0.31%   |
| Mercucys                          | 1         | 0.31%   |
| Linksys                           | 1         | 0.31%   |
| Lenovo                            | 1         | 0.31%   |
| JMicron Technology                | 1         | 0.31%   |
| Ericsson Business Mobile Networks | 1         | 0.31%   |
| Edimax Technology                 | 1         | 0.31%   |
| Dell                              | 1         | 0.31%   |
| AVM                               | 1         | 0.31%   |
| ASUSTek Computer                  | 1         | 0.31%   |
| ASIX Electronics                  | 1         | 0.31%   |
| Aquantia                          | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 19.62%  |
| Intel Wi-Fi 6 AX200                                               | 12        | 3.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 2.42%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.88%   |
| Intel Wireless 8260                                               | 6         | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.34%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.08%   |
| Intel Wireless 7260                                               | 4         | 1.08%   |
| Intel Wireless 3165                                               | 4         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 1.08%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.08%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.08%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.81%   |
| Intel Wireless 7265                                               | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.81%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.81%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 2         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 2         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 2         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 44.38%  |
| Realtek Semiconductor           | 30        | 16.85%  |
| Qualcomm Atheros                | 22        | 12.36%  |
| Broadcom                        | 10        | 5.62%   |
| MediaTek                        | 7         | 3.93%   |
| TP-Link                         | 6         | 3.37%   |
| Ralink Technology               | 6         | 3.37%   |
| Broadcom Limited                | 6         | 3.37%   |
| Ralink                          | 3         | 1.69%   |
| Sierra Wireless                 | 2         | 1.12%   |
| Qualcomm Atheros Communications | 1         | 0.56%   |
| NetGear                         | 1         | 0.56%   |
| Mercucys                        | 1         | 0.56%   |
| Linksys                         | 1         | 0.56%   |
| Edimax Technology               | 1         | 0.56%   |
| AVM                             | 1         | 0.56%   |
| ASUSTek Computer                | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 12        | 6.74%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.93%   |
| Intel Wireless 8260                                                     | 6         | 3.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.81%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.25%   |
| Intel Wireless 7260                                                     | 4         | 2.25%   |
| Intel Wireless 3165                                                     | 4         | 2.25%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.25%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 4         | 2.25%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.69%   |
| Intel Wireless 7265                                                     | 3         | 1.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.69%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.12%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 2         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.12%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.12%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.12%   |
| Intel Wireless 3160                                                     | 2         | 1.12%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.12%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.12%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 93        | 50.27%  |
| Intel                    | 47        | 25.41%  |
| Qualcomm Atheros         | 16        | 8.65%   |
| Broadcom                 | 10        | 5.41%   |
| Marvell Technology Group | 5         | 2.7%    |
| Nvidia                   | 4         | 2.16%   |
| Xiaomi                   | 1         | 0.54%   |
| TP-Link                  | 1         | 0.54%   |
| Samsung Electronics      | 1         | 0.54%   |
| OPPO Electronics         | 1         | 0.54%   |
| Microsoft                | 1         | 0.54%   |
| Lenovo                   | 1         | 0.54%   |
| JMicron Technology       | 1         | 0.54%   |
| Broadcom Limited         | 1         | 0.54%   |
| ASIX Electronics         | 1         | 0.54%   |
| Aquantia                 | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 38.22%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 4.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.62%   |
| Intel I211 Gigabit Network Connection                             | 4         | 2.09%   |
| Intel Ethernet Controller I225-V                                  | 4         | 2.09%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.57%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.57%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 1.05%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.05%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.05%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.05%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.05%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 1.05%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 175       | 51.47%  |
| WiFi     | 162       | 47.65%  |
| Modem    | 3         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 61.61%  |
| Ethernet | 81        | 38.39%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 114       | 55.61%  |
| 1     | 82        | 40%     |
| 3     | 5         | 2.44%   |
| 0     | 3         | 1.46%   |
| 4     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 149       | 72.33%  |
| Yes  | 57        | 27.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 48.03%  |
| Apple                           | 12        | 9.45%   |
| Qualcomm Atheros Communications | 11        | 8.66%   |
| Cambridge Silicon Radio         | 8         | 6.3%    |
| Realtek Semiconductor           | 7         | 5.51%   |
| Foxconn / Hon Hai               | 7         | 5.51%   |
| Broadcom                        | 6         | 4.72%   |
| Lite-On Technology              | 3         | 2.36%   |
| IMC Networks                    | 3         | 2.36%   |
| ASUSTek Computer                | 3         | 2.36%   |
| Hewlett-Packard                 | 2         | 1.57%   |
| Ralink                          | 1         | 0.79%   |
| MediaTek                        | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |
| Alps Electric                   | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 17.32%  |
| Intel Bluetooth Device                                                              | 14        | 11.02%  |
| Intel AX200 Bluetooth                                                               | 12        | 9.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 6.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 6.3%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 5.51%   |
| Realtek Bluetooth Radio                                                             | 6         | 4.72%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 3.94%   |
| Apple Bluetooth Host Controller                                                     | 4         | 3.15%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.36%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 2.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.57%   |
| Lite-On Wireless_Device                                                             | 2         | 1.57%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.57%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.57%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.57%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.79%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.79%   |
| MediaTek Wireless_Device                                                            | 1         | 0.79%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.79%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.79%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.79%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.79%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.79%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.79%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.79%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.79%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.79%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.79%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 156       | 52.35%  |
| Nvidia                     | 55        | 18.46%  |
| AMD                        | 52        | 17.45%  |
| C-Media Electronics        | 6         | 2.01%   |
| Creative Labs              | 5         | 1.68%   |
| Texas Instruments          | 2         | 0.67%   |
| ROCCAT                     | 2         | 0.67%   |
| Realtek Semiconductor      | 2         | 0.67%   |
| BEHRINGER International    | 2         | 0.67%   |
| Unknown                    | 1         | 0.34%   |
| TerraTec Electronic        | 1         | 0.34%   |
| Shenzhen Riitek Technology | 1         | 0.34%   |
| Schiit Audio               | 1         | 0.34%   |
| Razer USA                  | 1         | 0.34%   |
| Plantronics                | 1         | 0.34%   |
| Logitech                   | 1         | 0.34%   |
| LG Electronics             | 1         | 0.34%   |
| Lenovo                     | 1         | 0.34%   |
| JMTek                      | 1         | 0.34%   |
| GYROCOM C&C                | 1         | 0.34%   |
| GN Netcom                  | 1         | 0.34%   |
| Generalplus Technology     | 1         | 0.34%   |
| FIFINE 683 Microphone      | 1         | 0.34%   |
| Dell                       | 1         | 0.34%   |
| CMX Systems                | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 6.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 5.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 4.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 12        | 3.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.74%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 1.45%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.16%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.16%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.16%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.16%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4         | 1.16%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.87%   |
| Nvidia Audio device                                                                               | 3         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 3         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.87%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.87%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.87%   |
| Creative Labs CA0132 Sound Core3D [Sound Blaster Recon3D / Z-Series / Sound BlasterX AE-5 Plus]   | 3         | 0.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 21.7%   |
| SK hynix            | 39        | 16.6%   |
| Kingston            | 29        | 12.34%  |
| Unknown             | 26        | 11.06%  |
| Micron Technology   | 19        | 8.09%   |
| Crucial             | 13        | 5.53%   |
| Corsair             | 13        | 5.53%   |
| Ramaxel Technology  | 7         | 2.98%   |
| G.Skill             | 6         | 2.55%   |
| Elpida              | 5         | 2.13%   |
| Nanya Technology    | 4         | 1.7%    |
| A-DATA Technology   | 4         | 1.7%    |
| Unknown (ABCD)      | 3         | 1.28%   |
| Transcend           | 3         | 1.28%   |
| Unknown             | 3         | 1.28%   |
| Smart               | 2         | 0.85%   |
| Team                | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| Patriot             | 1         | 0.43%   |
| Innodisk            | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| ASint Technology    | 1         | 0.43%   |
| Apacer              | 1         | 0.43%   |
| 48spaces            | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 1.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.59%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 1.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.2%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.2%    |
| Unknown                                                          | 3         | 1.2%    |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.8%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 2         | 0.8%    |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 2         | 0.8%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.8%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.8%    |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.8%    |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.8%    |
| G.Skill RAM F4-4000C18-16GTZR 16GB DIMM DDR4 2133MT/s            | 2         | 0.8%    |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.8%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 2         | 0.8%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.4%    |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 88        | 43.35%  |
| DDR3    | 79        | 38.92%  |
| DDR2    | 11        | 5.42%   |
| LPDDR4  | 10        | 4.93%   |
| SDRAM   | 4         | 1.97%   |
| DDR     | 4         | 1.97%   |
| Unknown | 4         | 1.97%   |
| LPDDR3  | 1         | 0.49%   |
| DRAM    | 1         | 0.49%   |
| DDR5    | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 64.36%  |
| DIMM         | 62        | 30.69%  |
| Row Of Chips | 10        | 4.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 78        | 35.29%  |
| 4096  | 71        | 32.13%  |
| 2048  | 33        | 14.93%  |
| 16384 | 23        | 10.41%  |
| 1024  | 8         | 3.62%   |
| 32768 | 7         | 3.17%   |
| 512   | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 42        | 19.44%  |
| 3200    | 33        | 15.28%  |
| 2667    | 21        | 9.72%   |
| 1333    | 21        | 9.72%   |
| 2400    | 16        | 7.41%   |
| Unknown | 11        | 5.09%   |
| 2133    | 10        | 4.63%   |
| 667     | 9         | 4.17%   |
| 3600    | 8         | 3.7%    |
| 1334    | 7         | 3.24%   |
| 1067    | 4         | 1.85%   |
| 4267    | 3         | 1.39%   |
| 3400    | 3         | 1.39%   |
| 2666    | 3         | 1.39%   |
| 800     | 3         | 1.39%   |
| 3733    | 2         | 0.93%   |
| 2933    | 2         | 0.93%   |
| 2048    | 2         | 0.93%   |
| 333     | 2         | 0.93%   |
| 8400    | 1         | 0.46%   |
| 4800    | 1         | 0.46%   |
| 4266    | 1         | 0.46%   |
| 4199    | 1         | 0.46%   |
| 3466    | 1         | 0.46%   |
| 3266    | 1         | 0.46%   |
| 2000    | 1         | 0.46%   |
| 1867    | 1         | 0.46%   |
| 1866    | 1         | 0.46%   |
| 1800    | 1         | 0.46%   |
| 1639    | 1         | 0.46%   |
| 1066    | 1         | 0.46%   |
| 533     | 1         | 0.46%   |
| 166     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 44.44%  |
| Brother Industries | 3         | 33.33%  |
| Hewlett-Packard    | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon MF641C             | 2         | 22.22%  |
| HP LaserJet P2055 series | 1         | 11.11%  |
| HP LaserJet 1022         | 1         | 11.11%  |
| Canon MG5700 series      | 1         | 11.11%  |
| Canon LiDE 400           | 1         | 11.11%  |
| Brother MFC-7340         | 1         | 11.11%  |
| Brother HL-2150N series  | 1         | 11.11%  |
| Brother DCP-L2540DW      | 1         | 11.11%  |

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


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 20.33%  |
| Acer                                   | 13        | 10.57%  |
| Realtek Semiconductor                  | 11        | 8.94%   |
| Microdia                               | 11        | 8.94%   |
| Logitech                               | 7         | 5.69%   |
| IMC Networks                           | 7         | 5.69%   |
| Apple                                  | 7         | 5.69%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.88%   |
| Sunplus Innovation Technology          | 5         | 4.07%   |
| Quanta                                 | 4         | 3.25%   |
| Lite-On Technology                     | 4         | 3.25%   |
| Ricoh                                  | 3         | 2.44%   |
| Lenovo                                 | 3         | 2.44%   |
| Suyin                                  | 2         | 1.63%   |
| Silicon Motion                         | 2         | 1.63%   |
| Microsoft                              | 2         | 1.63%   |
| Alcor Micro                            | 2         | 1.63%   |
| Z-Star Microelectronics                | 1         | 0.81%   |
| Y Media                                | 1         | 0.81%   |
| Sonix Technology                       | 1         | 0.81%   |
| Primax Electronics                     | 1         | 0.81%   |
| Luxvisions Innotech Limited            | 1         | 0.81%   |
| LG Electronics                         | 1         | 0.81%   |
| Goodong Industry                       | 1         | 0.81%   |
| Generalplus Technology                 | 1         | 0.81%   |
| Arkmicro Technologies                  | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 5         | 4.03%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 3.23%   |
| Chicony Integrated Camera                           | 4         | 3.23%   |
| Acer Integrated Camera                              | 4         | 3.23%   |
| Chicony HD User Facing                              | 3         | 2.42%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 2.42%   |
| Acer BisonCam,NB Pro                                | 3         | 2.42%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.61%   |
| Realtek USB Camera                                  | 2         | 1.61%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.61%   |
| Quanta HD User Facing                               | 2         | 1.61%   |
| Microsoft LifeCam HD-3000                           | 2         | 1.61%   |
| Logitech Webcam C930e                               | 2         | 1.61%   |
| Logitech Webcam C270                                | 2         | 1.61%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.61%   |
| IMC Networks Integrated Camera                      | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.61%   |
| Apple Built-in iSight                               | 2         | 1.61%   |
| Acer HD Webcam                                      | 2         | 1.61%   |
| Acer BisonCam, NB Pro                               | 2         | 1.61%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.81%   |
| Y Media USB Camera                                  | 1         | 0.81%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.81%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.81%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.81%   |
| Sunplus HD 720P webcam                              | 1         | 0.81%   |
| Sunplus ASUS Webcam                                 | 1         | 0.81%   |
| Sonix USB Camera                                    | 1         | 0.81%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.81%   |
| Silicon Motion Web Camera                           | 1         | 0.81%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.81%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.81%   |
| Ricoh Integrated Webcam                             | 1         | 0.81%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.81%   |
| Realtek Realtek USB MIC                             | 1         | 0.81%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.81%   |
| Realtek Integrated Webcam HD                        | 1         | 0.81%   |
| Realtek Integrated Webcam                           | 1         | 0.81%   |
| Realtek EasyCamera                                  | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 25%     |
| Synaptics                  | 6         | 25%     |
| Shenzhen Goodix Technology | 4         | 16.67%  |
| AuthenTec                  | 4         | 16.67%  |
| Upek                       | 2         | 8.33%   |
| Microsoft                  | 1         | 4.17%   |
| Elan Microelectronics      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 12.5%   |
| Unknown                                                | 3         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 8.33%   |
| AuthenTec AES2810                                      | 2         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.17%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 4.17%   |
| Microsoft Fingerprint Reader                           | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.17%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 40%     |
| Alcor Micro           | 4         | 40%     |
| Advanced Card Systems | 2         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 4         | 40%     |
| Broadcom 5880                                  | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 10%     |
| Advanced Card Systems ACR38 SmartCard Reader   | 1         | 10%     |
| Advanced Card Systems ACR122U                  | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 144       | 68.25%  |
| 1     | 48        | 22.75%  |
| 2     | 16        | 7.58%   |
| 3     | 3         | 1.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 33        | 39.76%  |
| Fingerprint reader       | 24        | 28.92%  |
| Chipcard                 | 8         | 9.64%   |
| Multimedia controller    | 5         | 6.02%   |
| Unassigned class         | 3         | 3.61%   |
| Communication controller | 3         | 3.61%   |
| Net/wireless             | 2         | 2.41%   |
| Camera                   | 2         | 2.41%   |
| Sound                    | 1         | 1.2%    |
| Net/ethernet             | 1         | 1.2%    |
| Dvb card                 | 1         | 1.2%    |

