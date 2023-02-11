MX 21 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 21.

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

Total: 190

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1d28352c0f](https://linux-hardware.org/?probe=1d28352c0f) | Jan 28, 2023 |
| HP            | Compaq nc6320 (RH569ET#A... | [bf4432a140](https://linux-hardware.org/?probe=bf4432a140) | Jan 28, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Acer          | Swift SF314-43              | [3d1f5b0ee9](https://linux-hardware.org/?probe=3d1f5b0ee9) | Jan 23, 2023 |
| AMI           | Intel                       | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [cb84c73399](https://linux-hardware.org/?probe=cb84c73399) | Jan 15, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge 031925U       | [95feaf21b4](https://linux-hardware.org/?probe=95feaf21b4) | Jan 07, 2023 |
| Toshiba       | Satellite M70               | [616dbdfa63](https://linux-hardware.org/?probe=616dbdfa63) | Jan 05, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Apple         | MacBookPro10,1              | [6c8ec40821](https://linux-hardware.org/?probe=6c8ec40821) | Dec 25, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [916375929d](https://linux-hardware.org/?probe=916375929d) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Gigabyte      | G5 KC                       | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| HP            | 15 Notebook PC              | [06e7a6dfe7](https://linux-hardware.org/?probe=06e7a6dfe7) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| Dell          | Vostro 15-3568              | [a583a55071](https://linux-hardware.org/?probe=a583a55071) | Dec 10, 2022 |
| Dell          | Vostro 15-3568              | [2e76f24d6a](https://linux-hardware.org/?probe=2e76f24d6a) | Dec 09, 2022 |
| Dell          | Vostro 15-3568              | [36b349ff7f](https://linux-hardware.org/?probe=36b349ff7f) | Dec 08, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| Acer          | Aspire ES1-732              | [7000f5ee26](https://linux-hardware.org/?probe=7000f5ee26) | Dec 04, 2022 |
| MSI           | GF63 Thin 9SC               | [057b0039b7](https://linux-hardware.org/?probe=057b0039b7) | Dec 01, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [b47217fa0c](https://linux-hardware.org/?probe=b47217fa0c) | Nov 25, 2022 |
| Apple         | MacBookPro10,1              | [3f08c2fb11](https://linux-hardware.org/?probe=3f08c2fb11) | Nov 25, 2022 |
| Sony          | VGN-TZ3RXN_B                | [5986f007c8](https://linux-hardware.org/?probe=5986f007c8) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Dell          | Latitude 3190               | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [9884754d7b](https://linux-hardware.org/?probe=9884754d7b) | Nov 14, 2022 |
| Dell          | Latitude 3190               | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| Dell          | Inspiron 3583               | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [48e0868598](https://linux-hardware.org/?probe=48e0868598) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [cb36e9d15c](https://linux-hardware.org/?probe=cb36e9d15c) | Nov 09, 2022 |
| Dell          | Latitude 3190               | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| ASUSTek       | X200CA                      | [91d85f8376](https://linux-hardware.org/?probe=91d85f8376) | Nov 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [9819da96f2](https://linux-hardware.org/?probe=9819da96f2) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| SANTECH       | X170KM-G                    | [073f9a1d24](https://linux-hardware.org/?probe=073f9a1d24) | Nov 01, 2022 |
| Vulcan Ele... | Excursion XB                | [30ceac1216](https://linux-hardware.org/?probe=30ceac1216) | Oct 31, 2022 |
| Dell          | Latitude 3190               | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [423ad57e72](https://linux-hardware.org/?probe=423ad57e72) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f8b4ce6c3f](https://linux-hardware.org/?probe=f8b4ce6c3f) | Oct 29, 2022 |
| Apple         | MacBookPro14,3              | [6383143b5b](https://linux-hardware.org/?probe=6383143b5b) | Oct 28, 2022 |
| Dell          | Latitude 3190               | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| win elemen... | MoreFine S500+              | [d34df28814](https://linux-hardware.org/?probe=d34df28814) | Oct 22, 2022 |
| Apple         | MacBookPro7,1               | [aa571dded9](https://linux-hardware.org/?probe=aa571dded9) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e33a95e0b0](https://linux-hardware.org/?probe=e33a95e0b0) | Oct 18, 2022 |
| Dell          | Latitude 3190               | [342d7acb67](https://linux-hardware.org/?probe=342d7acb67) | Oct 17, 2022 |
| Apple         | MacBookPro11,1              | [09af41cbf8](https://linux-hardware.org/?probe=09af41cbf8) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [b3267ce847](https://linux-hardware.org/?probe=b3267ce847) | Oct 15, 2022 |
| Apple         | MacBookPro11,1              | [209d243342](https://linux-hardware.org/?probe=209d243342) | Oct 15, 2022 |
| HP            | Laptop 17-ak0xx             | [67fbbc4074](https://linux-hardware.org/?probe=67fbbc4074) | Oct 11, 2022 |
| Medion        | E7424 MD60750               | [7c9ea600ad](https://linux-hardware.org/?probe=7c9ea600ad) | Oct 11, 2022 |
| Dell          | Latitude 3190               | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [f2c440fdf6](https://linux-hardware.org/?probe=f2c440fdf6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [8159009c50](https://linux-hardware.org/?probe=8159009c50) | Oct 05, 2022 |
| Google        | Setzer                      | [6bafaabd48](https://linux-hardware.org/?probe=6bafaabd48) | Oct 04, 2022 |
| Dell          | Vostro 3500                 | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| Dell          | Latitude 3190               | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Dell          | Latitude 7490               | [872aafeb50](https://linux-hardware.org/?probe=872aafeb50) | Oct 02, 2022 |
| HP            | 250 G6 Notebook PC          | [992cf7d019](https://linux-hardware.org/?probe=992cf7d019) | Sep 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [5b7d4c6b7a](https://linux-hardware.org/?probe=5b7d4c6b7a) | Sep 27, 2022 |
| Dell          | Precision 7520              | [a7b1df0888](https://linux-hardware.org/?probe=a7b1df0888) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| Acer          | Nitro AN515-54              | [6182e4ef84](https://linux-hardware.org/?probe=6182e4ef84) | Sep 25, 2022 |
| HP            | Pavilion g7                 | [22133612c0](https://linux-hardware.org/?probe=22133612c0) | Sep 25, 2022 |
| Lenovo        | V15-IGL 82C3                | [c2de0def85](https://linux-hardware.org/?probe=c2de0def85) | Sep 25, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | [de3a2e822c](https://linux-hardware.org/?probe=de3a2e822c) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [b4e36a92c7](https://linux-hardware.org/?probe=b4e36a92c7) | Sep 08, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [ac71ea732f](https://linux-hardware.org/?probe=ac71ea732f) | Sep 07, 2022 |
| MSI           | Modern 14 B11MOL            | [1ce0bfd512](https://linux-hardware.org/?probe=1ce0bfd512) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | [7702adff5d](https://linux-hardware.org/?probe=7702adff5d) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | System XPS 15Z              | [45a22d4855](https://linux-hardware.org/?probe=45a22d4855) | Aug 11, 2022 |
| Lenovo        | ThinkPad T560 20FJS0EP00    | [dda2c8f199](https://linux-hardware.org/?probe=dda2c8f199) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| Dell          | Precision 7720              | [9f17ade16f](https://linux-hardware.org/?probe=9f17ade16f) | Aug 08, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [68e632a5f6](https://linux-hardware.org/?probe=68e632a5f6) | Aug 08, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Dell          | Vostro 3550                 | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Acer          | Aspire 5520                 | [d49c27a24a](https://linux-hardware.org/?probe=d49c27a24a) | Jul 29, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| Acer          | Swift SF314-59              | [56424874b7](https://linux-hardware.org/?probe=56424874b7) | Jul 11, 2022 |
| Alienware     | 13 R2                       | [ec877e9a2e](https://linux-hardware.org/?probe=ec877e9a2e) | Jul 06, 2022 |
| Alienware     | m15                         | [9578c619e6](https://linux-hardware.org/?probe=9578c619e6) | Jul 06, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Unknown       | Unknown                     | [3b7ffa4a35](https://linux-hardware.org/?probe=3b7ffa4a35) | Jun 18, 2022 |
| Dell          | Inspiron 15-3552            | [d89b7877a0](https://linux-hardware.org/?probe=d89b7877a0) | Jun 17, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | ProBook 450 G1              | [623bb542e3](https://linux-hardware.org/?probe=623bb542e3) | Jun 15, 2022 |
| Apple         | MacBookAir7,2               | [fc34430f8d](https://linux-hardware.org/?probe=fc34430f8d) | Jun 15, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| Toshiba       | Satellite C845              | [12d9cc2076](https://linux-hardware.org/?probe=12d9cc2076) | Jun 11, 2022 |
| Lenovo        | S130-11IGM 81J1             | [851d5469e5](https://linux-hardware.org/?probe=851d5469e5) | Jun 08, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b7ff235a14](https://linux-hardware.org/?probe=b7ff235a14) | Jun 03, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| ASUSTek       | K55A                        | [0eb5e9ea50](https://linux-hardware.org/?probe=0eb5e9ea50) | May 29, 2022 |
| Sony          | VPCSB1V9R                   | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Medion        | E14304                      | [8d1a922b7b](https://linux-hardware.org/?probe=8d1a922b7b) | May 15, 2022 |
| HP            | Stream Laptop 14-cb0XX      | [3b0408920d](https://linux-hardware.org/?probe=3b0408920d) | May 13, 2022 |
| Acer          | Aspire A515-56              | [b728fa5844](https://linux-hardware.org/?probe=b728fa5844) | May 01, 2022 |
| Acer          | Nitro AN515-55              | [04b51fe1cf](https://linux-hardware.org/?probe=04b51fe1cf) | Apr 25, 2022 |
| Alienware     | m15 R7                      | [77727a1731](https://linux-hardware.org/?probe=77727a1731) | Apr 24, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4e8b5f940a](https://linux-hardware.org/?probe=4e8b5f940a) | Apr 23, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Acer          | Aspire A515-56              | [db6408f394](https://linux-hardware.org/?probe=db6408f394) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | 1101HA                      | [c3d2458d59](https://linux-hardware.org/?probe=c3d2458d59) | Apr 04, 2022 |
| ASUSTek       | ROG Strix G712LU_G712LU     | [288629b95d](https://linux-hardware.org/?probe=288629b95d) | Apr 04, 2022 |
| Lenovo        | ThinkPad T430 23427YU       | [07ada1e358](https://linux-hardware.org/?probe=07ada1e358) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [697f820432](https://linux-hardware.org/?probe=697f820432) | Apr 02, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Lenovo        | ThinkPad T440p 20AW002VB... | [e3ec03ac31](https://linux-hardware.org/?probe=e3ec03ac31) | Mar 29, 2022 |
| Framework     | Laptop                      | [a9f49dfe70](https://linux-hardware.org/?probe=a9f49dfe70) | Mar 24, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.10.0-9-amd64               | 14        | 10.45%  |
| 5.10.0-13-amd64              | 14        | 10.45%  |
| 5.10.0-18-amd64              | 11        | 8.21%   |
| 5.10.0-16-amd64              | 9         | 6.72%   |
| 5.14.0-4mx-amd64             | 8         | 5.97%   |
| 5.10.0-19-amd64              | 8         | 5.97%   |
| 5.16.0-5mx-amd64             | 6         | 4.48%   |
| 5.10.0-14-amd64              | 6         | 4.48%   |
| 5.10.0-11-amd64              | 6         | 4.48%   |
| 5.18.0-4mx-amd64             | 5         | 3.73%   |
| 6.0.0-4mx-amd64              | 4         | 2.99%   |
| 5.10.0-20-amd64              | 3         | 2.24%   |
| 5.10.0-17-amd64              | 3         | 2.24%   |
| 6.0.0-3mx-amd64              | 2         | 1.49%   |
| 5.19.0-2mx-amd64             | 2         | 1.49%   |
| 5.16.0-6mx-amd64             | 2         | 1.49%   |
| 5.10.0-8-amd64               | 2         | 1.49%   |
| 5.10.0-15-amd64              | 2         | 1.49%   |
| 5.10.0-13-686-pae            | 2         | 1.49%   |
| 5.10.0-11-686-pae            | 2         | 1.49%   |
| 5.10.0-10-amd64              | 2         | 1.49%   |
| 6.0.0-11.2-liquorix-amd64    | 1         | 0.75%   |
| 5.19.0-12.1-liquorix-amd64   | 1         | 0.75%   |
| 5.18.0-3-amd64               | 1         | 0.75%   |
| 5.18.0-0.deb11.4-amd64       | 1         | 0.75%   |
| 5.17.0-5.2-liquorix-amd64    | 1         | 0.75%   |
| 5.17.0-3mx-amd64             | 1         | 0.75%   |
| 5.17.0-2mx-amd64             | 1         | 0.75%   |
| 5.17.0-1-amd64               | 1         | 0.75%   |
| 5.16.0-4mx-amd64             | 1         | 0.75%   |
| 5.16.0-18.1-liquorix-amd64   | 1         | 0.75%   |
| 5.15.0-3mx-amd64             | 1         | 0.75%   |
| 5.10.82-hardened1-Rukhazon-0 | 1         | 0.75%   |
| 5.10.0-9-686-pae             | 1         | 0.75%   |
| 5.10.0-5mx-amd64             | 1         | 0.75%   |
| 5.10.0-21-amd64              | 1         | 0.75%   |
| 5.10.0-20-686-pae            | 1         | 0.75%   |
| 5.10.0-18-686-pae            | 1         | 0.75%   |
| 5.10.0-12-amd64              | 1         | 0.75%   |
| 5.10.0-11-686                | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 83        | 65.87%  |
| 5.16.0  | 10        | 7.94%   |
| 5.14.0  | 8         | 6.35%   |
| 6.0.0   | 7         | 5.56%   |
| 5.18.0  | 7         | 5.56%   |
| 5.17.0  | 4         | 3.17%   |
| 5.19.0  | 3         | 2.38%   |
| 5.15.0  | 1         | 0.79%   |
| 5.10.82 | 1         | 0.79%   |
| 4.19.0  | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 84        | 66.67%  |
| 5.16    | 10        | 7.94%   |
| 5.14    | 8         | 6.35%   |
| 6.0     | 7         | 5.56%   |
| 5.18    | 7         | 5.56%   |
| 5.17    | 4         | 3.17%   |
| 5.19    | 3         | 2.38%   |
| 5.15    | 1         | 0.79%   |
| 4.19    | 1         | 0.79%   |
| Unknown | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 111       | 94.07%  |
| i686   | 7         | 5.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 85        | 70.25%  |
| KDE5          | 26        | 21.49%  |
| Budgie        | 3         | 2.48%   |
| GNOME         | 2         | 1.65%   |
| Unknown       | 2         | 1.65%   |
| LXQt          | 1         | 0.83%   |
| i3            | 1         | 0.83%   |
| GNOME Classic | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 116       | 98.31%  |
| Tty  | 2         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 94        | 78.33%  |
| SDDM    | 24        | 20%     |
| SLiM    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 55        | 45.83%  |
| de_DE   | 18        | 15%     |
| it_IT   | 7         | 5.83%   |
| en_GB   | 7         | 5.83%   |
| ru_RU   | 4         | 3.33%   |
| Unknown | 4         | 3.33%   |
| fr_FR   | 3         | 2.5%    |
| en_AU   | 3         | 2.5%    |
| pt_BR   | 2         | 1.67%   |
| es_ES   | 2         | 1.67%   |
| en_NZ   | 2         | 1.67%   |
| bg_BG   | 2         | 1.67%   |
| tr_TR   | 1         | 0.83%   |
| sk_SK   | 1         | 0.83%   |
| pl_PL   | 1         | 0.83%   |
| nl_NL   | 1         | 0.83%   |
| nb_NO   | 1         | 0.83%   |
| id_ID   | 1         | 0.83%   |
| hu_HU   | 1         | 0.83%   |
| fi_FI   | 1         | 0.83%   |
| es_UY   | 1         | 0.83%   |
| es_PE   | 1         | 0.83%   |
| de_CH   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 87        | 73.73%  |
| BIOS | 31        | 26.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 81.67%  |
| Overlay | 17        | 14.17%  |
| Btrfs   | 4         | 3.33%   |
| F2fs    | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 89        | 75.42%  |
| MBR     | 28        | 23.73%  |
| Unknown | 1         | 0.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 73.33%  |
| Yes       | 32        | 26.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 64        | 53.78%  |
| Yes       | 55        | 46.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 20.34%  |
| Hewlett-Packard     | 14        | 11.86%  |
| Dell                | 14        | 11.86%  |
| ASUSTek Computer    | 13        | 11.02%  |
| Apple               | 8         | 6.78%   |
| Acer                | 8         | 6.78%   |
| Sony                | 7         | 5.93%   |
| Toshiba             | 4         | 3.39%   |
| MSI                 | 4         | 3.39%   |
| Samsung Electronics | 3         | 2.54%   |
| Alienware           | 3         | 2.54%   |
| Medion              | 2         | 1.69%   |
| Gigabyte Technology | 2         | 1.69%   |
| Fujitsu Siemens     | 2         | 1.69%   |
| win element         | 1         | 0.85%   |
| Vulcan Electronics  | 1         | 0.85%   |
| TUXEDO              | 1         | 0.85%   |
| SANTECH             | 1         | 0.85%   |
| Notebook            | 1         | 0.85%   |
| Framework           | 1         | 0.85%   |
| efirstview          | 1         | 0.85%   |
| Chuwi               | 1         | 0.85%   |
| AMI                 | 1         | 0.85%   |
| Unknown             | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                       | 2         | 1.69%   |
| Unknown                                   | 2         | 1.69%   |
| win element MoreFine S500+                | 1         | 0.85%   |
| Vulcan Excursion XB                       | 1         | 0.85%   |
| TUXEDO N7x0WU                             | 1         | 0.85%   |
| Toshiba Satellite M70                     | 1         | 0.85%   |
| Toshiba Satellite L650                    | 1         | 0.85%   |
| Toshiba Satellite C845                    | 1         | 0.85%   |
| Toshiba PORTEGE Z30-C                     | 1         | 0.85%   |
| Sony VPCYB3V1E                            | 1         | 0.85%   |
| Sony VPCSB1V9R                            | 1         | 0.85%   |
| Sony VPCF119FX                            | 1         | 0.85%   |
| Sony VPCEH2N1E                            | 1         | 0.85%   |
| Sony VPCEC3S1E                            | 1         | 0.85%   |
| Sony VGN-TZ3RXN_B                         | 1         | 0.85%   |
| Sony SVE1513Q1ESI                         | 1         | 0.85%   |
| SANTECH X170KM-G                          | 1         | 0.85%   |
| Samsung NC210/NC110                       | 1         | 0.85%   |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 0.85%   |
| Samsung 340XAA/350XAA/550XAA              | 1         | 0.85%   |
| Notebook PD5x_7xPNP_PNN_PNT               | 1         | 0.85%   |
| MSI Modern 14 B11MOL                      | 1         | 0.85%   |
| MSI GV62 8RD                              | 1         | 0.85%   |
| MSI GF63 Thin 9SC                         | 1         | 0.85%   |
| MSI Alpha 15 B5EEK                        | 1         | 0.85%   |
| Medion E7424 MD60750                      | 1         | 0.85%   |
| Medion E14304                             | 1         | 0.85%   |
| Lenovo V15-IGL 82C3                       | 1         | 0.85%   |
| Lenovo ThinkPad X200s 74695XG             | 1         | 0.85%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QV00BPUK | 1         | 0.85%   |
| Lenovo ThinkPad X1 Extreme 20MF000TIX     | 1         | 0.85%   |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 0.85%   |
| Lenovo ThinkPad T560 20FJS0EP00           | 1         | 0.85%   |
| Lenovo ThinkPad T500 2241VL9              | 1         | 0.85%   |
| Lenovo ThinkPad T480 20L50004MZ           | 1         | 0.85%   |
| Lenovo ThinkPad T440p 20AW002VBR          | 1         | 0.85%   |
| Lenovo ThinkPad T430 23427YU              | 1         | 0.85%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00A8GE    | 1         | 0.85%   |
| Lenovo ThinkPad L512 44444WG              | 1         | 0.85%   |
| Lenovo ThinkPad Edge 031925U              | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 14        | 11.86%  |
| Dell Latitude        | 4         | 3.39%   |
| Toshiba Satellite    | 3         | 2.54%   |
| Lenovo IdeaPad       | 3         | 2.54%   |
| HP EliteBook         | 3         | 2.54%   |
| Dell Vostro          | 3         | 2.54%   |
| Dell Inspiron        | 3         | 2.54%   |
| Acer Aspire          | 3         | 2.54%   |
| HP ProBook           | 2         | 1.69%   |
| HP Laptop            | 2         | 1.69%   |
| HP Compaq            | 2         | 1.69%   |
| Dell Precision       | 2         | 1.69%   |
| ASUS ROG             | 2         | 1.69%   |
| ASUS ASUS            | 2         | 1.69%   |
| Apple MacBookPro11   | 2         | 1.69%   |
| Apple MacBookAir7    | 2         | 1.69%   |
| Alienware m15        | 2         | 1.69%   |
| Acer Swift           | 2         | 1.69%   |
| Acer Nitro           | 2         | 1.69%   |
| Unknown              | 2         | 1.69%   |
| win element MoreFine | 1         | 0.85%   |
| Vulcan Excursion     | 1         | 0.85%   |
| TUXEDO N7x0WU        | 1         | 0.85%   |
| Toshiba PORTEGE      | 1         | 0.85%   |
| Sony VPCYB3V1E       | 1         | 0.85%   |
| Sony VPCSB1V9R       | 1         | 0.85%   |
| Sony VPCF119FX       | 1         | 0.85%   |
| Sony VPCEH2N1E       | 1         | 0.85%   |
| Sony VPCEC3S1E       | 1         | 0.85%   |
| Sony VGN-TZ3RXN      | 1         | 0.85%   |
| Sony SVE1513Q1ESI    | 1         | 0.85%   |
| SANTECH X170KM-G     | 1         | 0.85%   |
| Samsung NC210        | 1         | 0.85%   |
| Samsung 350V5C       | 1         | 0.85%   |
| Samsung 340XAA       | 1         | 0.85%   |
| Notebook PD5x        | 1         | 0.85%   |
| MSI Modern           | 1         | 0.85%   |
| MSI GV62             | 1         | 0.85%   |
| MSI GF63             | 1         | 0.85%   |
| MSI Alpha            | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 20        | 16.95%  |
| 2015    | 11        | 9.32%   |
| 2018    | 9         | 7.63%   |
| 2011    | 9         | 7.63%   |
| 2010    | 9         | 7.63%   |
| 2020    | 8         | 6.78%   |
| 2019    | 8         | 6.78%   |
| 2016    | 8         | 6.78%   |
| 2013    | 6         | 5.08%   |
| 2012    | 6         | 5.08%   |
| 2017    | 5         | 4.24%   |
| 2022    | 3         | 2.54%   |
| 2014    | 3         | 2.54%   |
| 2008    | 3         | 2.54%   |
| 2007    | 3         | 2.54%   |
| 2009    | 2         | 1.69%   |
| 2006    | 2         | 1.69%   |
| 2005    | 2         | 1.69%   |
| Unknown | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 118       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 117       | 99.15%  |
| Enabled  | 1         | 0.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 39        | 33.05%  |
| 16.01-24.0  | 22        | 18.64%  |
| 8.01-16.0   | 18        | 15.25%  |
| 3.01-4.0    | 16        | 13.56%  |
| 32.01-64.0  | 7         | 5.93%   |
| 1.01-2.0    | 6         | 5.08%   |
| 2.01-3.0    | 5         | 4.24%   |
| 64.01-256.0 | 2         | 1.69%   |
| 0.51-1.0    | 2         | 1.69%   |
| 24.01-32.0  | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 40        | 31.01%  |
| 2.01-3.0  | 34        | 26.36%  |
| 3.01-4.0  | 23        | 17.83%  |
| 4.01-8.0  | 18        | 13.95%  |
| 0.51-1.0  | 10        | 7.75%   |
| 8.01-16.0 | 3         | 2.33%   |
| 0.01-0.5  | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 66.94%  |
| 2      | 28        | 23.14%  |
| 3      | 9         | 7.44%   |
| 0      | 2         | 1.65%   |
| 4      | 1         | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 69.49%  |
| Yes       | 36        | 30.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 81.36%  |
| No        | 22        | 18.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 95.8%   |
| No        | 5         | 4.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 82.2%   |
| No        | 21        | 17.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 28        | 23.33%  |
| Germany     | 18        | 15%     |
| Italy       | 13        | 10.83%  |
| Canada      | 7         | 5.83%   |
| Netherlands | 4         | 3.33%   |
| Brazil      | 4         | 3.33%   |
| Russia      | 3         | 2.5%    |
| Poland      | 3         | 2.5%    |
| France      | 3         | 2.5%    |
| Australia   | 3         | 2.5%    |
| UK          | 2         | 1.67%   |
| Spain       | 2         | 1.67%   |
| Serbia      | 2         | 1.67%   |
| New Zealand | 2         | 1.67%   |
| India       | 2         | 1.67%   |
| Bulgaria    | 2         | 1.67%   |
| Belgium     | 2         | 1.67%   |
| Austria     | 2         | 1.67%   |
| Vietnam     | 1         | 0.83%   |
| Uruguay     | 1         | 0.83%   |
| Turkey      | 1         | 0.83%   |
| Switzerland | 1         | 0.83%   |
| Sweden      | 1         | 0.83%   |
| Slovakia    | 1         | 0.83%   |
| Romania     | 1         | 0.83%   |
| Peru        | 1         | 0.83%   |
| Norway      | 1         | 0.83%   |
| Malaysia    | 1         | 0.83%   |
| Indonesia   | 1         | 0.83%   |
| Hungary     | 1         | 0.83%   |
| Ghana       | 1         | 0.83%   |
| Finland     | 1         | 0.83%   |
| Egypt       | 1         | 0.83%   |
| Czechia     | 1         | 0.83%   |
| Belarus     | 1         | 0.83%   |
| Azerbaijan  | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Walled Lake                  | 2         | 1.57%   |
| Vienna                       | 2         | 1.57%   |
| St Petersburg                | 2         | 1.57%   |
| Rome                         | 2         | 1.57%   |
| Orange                       | 2         | 1.57%   |
| New York                     | 2         | 1.57%   |
| Montreal                     | 2         | 1.57%   |
| Florence                     | 2         | 1.57%   |
| Doesburg                     | 2         | 1.57%   |
| Casale Litta                 | 2         | 1.57%   |
| Canberra                     | 2         | 1.57%   |
| Cambridge                    | 2         | 1.57%   |
| Amsterdam                    | 2         | 1.57%   |
| Zurich                       | 1         | 0.79%   |
| Wermelskirchen               | 1         | 0.79%   |
| Waycross                     | 1         | 0.79%   |
| Warsaw                       | 1         | 0.79%   |
| Vasco da Gama                | 1         | 0.79%   |
| Vancouver                    | 1         | 0.79%   |
| Uelzen                       | 1         | 0.79%   |
| Tucson                       | 1         | 0.79%   |
| Toulouse                     | 1         | 0.79%   |
| The Dalles                   | 1         | 0.79%   |
| Taggia                       | 1         | 0.79%   |
| Tacoma                       | 1         | 0.79%   |
| Sydney                       | 1         | 0.79%   |
| Surprise                     | 1         | 0.79%   |
| Stroud                       | 1         | 0.79%   |
| Stockholm                    | 1         | 0.79%   |
| Stadtilm                     | 1         | 0.79%   |
| Soest                        | 1         | 0.79%   |
| Schaarbeek                   | 1         | 0.79%   |
| Saskatoon                    | 1         | 0.79%   |
| Sankt Georgen im Schwarzwald | 1         | 0.79%   |
| Saarlouis                    | 1         | 0.79%   |
| Ruda Śląska                | 1         | 0.79%   |
| Roseville                    | 1         | 0.79%   |
| Rochester                    | 1         | 0.79%   |
| Reinbek                      | 1         | 0.79%   |
| Raleigh                      | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 33     | 15.09%  |
| WDC                 | 17        | 17     | 10.69%  |
| Seagate             | 15        | 17     | 9.43%   |
| Kingston            | 13        | 14     | 8.18%   |
| Crucial             | 12        | 24     | 7.55%   |
| Unknown             | 10        | 12     | 6.29%   |
| Toshiba             | 9         | 9      | 5.66%   |
| SK hynix            | 8         | 9      | 5.03%   |
| Intel               | 6         | 8      | 3.77%   |
| Apple               | 6         | 9      | 3.77%   |
| Hitachi             | 5         | 6      | 3.14%   |
| Transcend           | 3         | 3      | 1.89%   |
| SPCC                | 3         | 3      | 1.89%   |
| SanDisk             | 3         | 4      | 1.89%   |
| PNY                 | 3         | 3      | 1.89%   |
| LITEON              | 3         | 3      | 1.89%   |
| Dogfish             | 3         | 3      | 1.89%   |
| Phison              | 2         | 3      | 1.26%   |
| Netac               | 2         | 2      | 1.26%   |
| Micron Technology   | 2         | 2      | 1.26%   |
| Team                | 1         | 1      | 0.63%   |
| SABRENT             | 1         | 1      | 0.63%   |
| OCZ                 | 1         | 1      | 0.63%   |
| KIOXIA              | 1         | 2      | 0.63%   |
| Indilinx            | 1         | 1      | 0.63%   |
| Gigabyte Technology | 1         | 1      | 0.63%   |
| GeIL                | 1         | 1      | 0.63%   |
| Fujitsu             | 1         | 1      | 0.63%   |
| Corsair             | 1         | 1      | 0.63%   |
| Unknown             | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown SD32G  32GB                  | 3         | 1.81%   |
| Samsung SSD 980 PRO 1TB              | 3         | 1.81%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.81%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 1.81%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 1.2%    |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.2%    |
| Samsung SSD 860 EVO 500GB            | 2         | 1.2%    |
| Samsung SSD 860 250GB                | 2         | 1.2%    |
| Samsung SSD 850 EVO 250GB            | 2         | 1.2%    |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 1.2%    |
| Kingston SA400S37480G 480GB SSD      | 2         | 1.2%    |
| Kingston OM8PCP3512F-AI1 512GB       | 2         | 1.2%    |
| Hitachi HTS54503 320GB               | 2         | 1.2%    |
| Dogfish SSD 128GB                    | 2         | 1.2%    |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.2%    |
| Crucial CT480BX500SSD1 480GB         | 2         | 1.2%    |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.2%    |
| Apple SSD SM0128G 121GB              | 2         | 1.2%    |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.6%    |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.6%    |
| WDC WD7500BPVT-75HXZT3 752GB         | 1         | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.6%    |
| WDC WD5000LPVX-08V0TT5 500GB         | 1         | 0.6%    |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.6%    |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.6%    |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.6%    |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.6%    |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.6%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.6%    |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB   | 1         | 0.6%    |
| WDC PC SN730 NVMe 1024GB             | 1         | 0.6%    |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 0.6%    |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 0.6%    |
| Unknown SDW32G  32GB                 | 1         | 0.6%    |
| Unknown SD08G  8GB                   | 1         | 0.6%    |
| Unknown SC64G  64GB                  | 1         | 0.6%    |
| Unknown NCard  32GB                  | 1         | 0.6%    |
| Unknown ISOCOM  64GB                 | 1         | 0.6%    |
| Unknown G1J38E  64GB                 | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 41.67%  |
| WDC                 | 9         | 9      | 25%     |
| Hitachi             | 5         | 6      | 13.89%  |
| Toshiba             | 4         | 4      | 11.11%  |
| Samsung Electronics | 1         | 1      | 2.78%   |
| SABRENT             | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 17     | 19.7%   |
| Crucial             | 11        | 22     | 16.67%  |
| Kingston            | 7         | 7      | 10.61%  |
| Apple               | 5         | 8      | 7.58%   |
| Transcend           | 3         | 3      | 4.55%   |
| SPCC                | 3         | 3      | 4.55%   |
| SanDisk             | 3         | 4      | 4.55%   |
| PNY                 | 3         | 3      | 4.55%   |
| LITEON              | 3         | 3      | 4.55%   |
| Dogfish             | 3         | 3      | 4.55%   |
| Toshiba             | 2         | 2      | 3.03%   |
| Netac               | 2         | 2      | 3.03%   |
| WDC                 | 1         | 1      | 1.52%   |
| SK hynix            | 1         | 1      | 1.52%   |
| OCZ                 | 1         | 1      | 1.52%   |
| Intel               | 1         | 1      | 1.52%   |
| Indilinx            | 1         | 1      | 1.52%   |
| Gigabyte Technology | 1         | 1      | 1.52%   |
| GeIL                | 1         | 1      | 1.52%   |
| Corsair             | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 56        | 85     | 38.62%  |
| NVMe | 42        | 58     | 28.97%  |
| HDD  | 36        | 39     | 24.83%  |
| MMC  | 11        | 13     | 7.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 123    | 59.09%  |
| NVMe | 42        | 58     | 31.82%  |
| MMC  | 11        | 13     | 8.33%   |
| SAS  | 1         | 1      | 0.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 88     | 74.16%  |
| 0.51-1.0   | 20        | 33     | 22.47%  |
| 1.01-2.0   | 2         | 2      | 2.25%   |
| 3.01-4.0   | 1         | 1      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 29.6%   |
| 251-500        | 28        | 22.4%   |
| 501-1000       | 16        | 12.8%   |
| 21-50          | 13        | 10.4%   |
| 51-100         | 12        | 9.6%    |
| 1-20           | 9         | 7.2%    |
| 1001-2000      | 6         | 4.8%    |
| More than 3000 | 2         | 1.6%    |
| 2001-3000      | 2         | 1.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 43.41%  |
| 21-50          | 21        | 16.28%  |
| 101-250        | 16        | 12.4%   |
| 51-100         | 16        | 12.4%   |
| 251-500        | 11        | 8.53%   |
| 1001-2000      | 4         | 3.1%    |
| 501-1000       | 4         | 3.1%    |
| More than 3000 | 1         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 6.25%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 6.25%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 6.25%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 6.25%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 6.25%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 6.25%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 6.25%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 6.25%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 6.25%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 6.25%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 6.25%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 6.25%   |
| Crucial CT1000MX500SSD4 1TB                  | 1         | 2      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 25%     |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Samsung Electronics | 2         | 2      | 12.5%   |
| Toshiba             | 1         | 1      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| Intel               | 1         | 2      | 6.25%   |
| Indilinx            | 1         | 1      | 6.25%   |
| Crucial             | 1         | 2      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| Hitachi | 3         | 3      | 33.33%  |
| WDC     | 2         | 2      | 22.22%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 56.25%  |
| SSD  | 6         | 7      | 37.5%   |
| NVMe | 1         | 2      | 6.25%   |

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
| Works    | 99        | 161    | 76.74%  |
| Malfunc  | 16        | 18     | 12.4%   |
| Detected | 14        | 16     | 10.85%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 81        | 58.27%  |
| Samsung Electronics          | 15        | 10.79%  |
| AMD                          | 8         | 5.76%   |
| SK hynix                     | 7         | 5.04%   |
| SanDisk                      | 7         | 5.04%   |
| Kingston Technology Company  | 6         | 4.32%   |
| Phison Electronics           | 3         | 2.16%   |
| Nvidia                       | 3         | 2.16%   |
| KIOXIA                       | 3         | 2.16%   |
| Micron Technology            | 2         | 1.44%   |
| Toshiba America Info Systems | 1         | 0.72%   |
| Silicon Image                | 1         | 0.72%   |
| Micron/Crucial Technology    | 1         | 0.72%   |
| Marvell Technology Group     | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 8.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 6.71%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 4.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.68%   |
| SK hynix BC511                                                                 | 3         | 2.01%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 2.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.01%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.01%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.01%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 1.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.34%   |
| Samsung Electronics SATA controller                                            | 2         | 1.34%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.34%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.34%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.34%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 1.34%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.34%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.34%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.34%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.67%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.67%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.67%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 81        | 58.27%  |
| NVMe | 42        | 30.22%  |
| IDE  | 11        | 7.91%   |
| RAID | 5         | 3.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 99        | 83.9%   |
| AMD    | 19        | 16.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 4         | 3.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 3         | 2.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 2.54%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 3         | 2.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 3         | 2.54%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 2         | 1.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 1.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 1.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 1.69%   |
| Intel Core i5-5350U CPU @ 1.80GHz        | 2         | 1.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 1.69%   |
| Intel Celeron CPU N3450 @ 1.10GHz        | 2         | 1.69%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 2         | 1.69%   |
| Intel 12th Gen Core i7-12700H            | 2         | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 1.69%   |
| AMD Ryzen 9 5900HX with Radeon Graphics  | 2         | 1.69%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 0.85%   |
| Intel Pentium M processor 1.80GHz        | 1         | 0.85%   |
| Intel Pentium M processor 1.73GHz        | 1         | 0.85%   |
| Intel Pentium CPU P6000 @ 1.87GHz        | 1         | 0.85%   |
| Intel Genuine CPU T2300 @ 1.66GHz        | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 0.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz       | 1         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 0.85%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz       | 1         | 0.85%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 0.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.85%   |
| Intel Core i7-3615QM CPU @ 2.30GHz       | 1         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 0.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 0.85%   |
| Intel Core i7-2630QM CPU @ 2.00GHz       | 1         | 0.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz        | 1         | 0.85%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 0.85%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.85%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz        | 1         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 27        | 22.88%  |
| Intel Core i5           | 21        | 17.8%   |
| Intel Core i3           | 12        | 10.17%  |
| Intel Celeron           | 12        | 10.17%  |
| Other                   | 11        | 9.32%   |
| AMD Ryzen 7             | 8         | 6.78%   |
| Intel Core 2 Duo        | 6         | 5.08%   |
| Intel Atom              | 4         | 3.39%   |
| Intel Pentium M         | 2         | 1.69%   |
| AMD Ryzen 9             | 2         | 1.69%   |
| AMD Ryzen 5             | 2         | 1.69%   |
| AMD Ryzen 3             | 2         | 1.69%   |
| Intel Pentium Silver    | 1         | 0.85%   |
| Intel Pentium           | 1         | 0.85%   |
| Intel Genuine           | 1         | 0.85%   |
| Intel Core 2            | 1         | 0.85%   |
| AMD Turion 64 X2 Mobile | 1         | 0.85%   |
| AMD Sempron             | 1         | 0.85%   |
| AMD E                   | 1         | 0.85%   |
| AMD A8                  | 1         | 0.85%   |
| AMD A10                 | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 56        | 47.46%  |
| 4      | 37        | 31.36%  |
| 8      | 11        | 9.32%   |
| 6      | 8         | 6.78%   |
| 1      | 4         | 3.39%   |
| 14     | 2         | 1.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 85        | 72.03%  |
| 1      | 33        | 27.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 114       | 96.61%  |
| 32-bit         | 4         | 3.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 11.57%  |
| 0x206a7    | 9         | 7.44%   |
| 0x306a9    | 7         | 5.79%   |
| 0x806c1    | 6         | 4.96%   |
| 0x406e3    | 6         | 4.96%   |
| 0x906ea    | 5         | 4.13%   |
| 0x0a50000c | 5         | 4.13%   |
| 0x806ea    | 4         | 3.31%   |
| 0x506e3    | 4         | 3.31%   |
| 0x20655    | 4         | 3.31%   |
| 0xa0652    | 3         | 2.48%   |
| 0x706a8    | 3         | 2.48%   |
| 0x306d4    | 3         | 2.48%   |
| 0x306c3    | 3         | 2.48%   |
| 0x30678    | 3         | 2.48%   |
| 0x1067a    | 3         | 2.48%   |
| 0x08608103 | 3         | 2.48%   |
| 0x906a3    | 2         | 1.65%   |
| 0x806e9    | 2         | 1.65%   |
| 0x706a1    | 2         | 1.65%   |
| 0x6fd      | 2         | 1.65%   |
| 0x406c4    | 2         | 1.65%   |
| 0xa0671    | 1         | 0.83%   |
| 0x906ed    | 1         | 0.83%   |
| 0x906e9    | 1         | 0.83%   |
| 0x906c0    | 1         | 0.83%   |
| 0x806ec    | 1         | 0.83%   |
| 0x806eb    | 1         | 0.83%   |
| 0x806d1    | 1         | 0.83%   |
| 0x6fb      | 1         | 0.83%   |
| 0x6e8      | 1         | 0.83%   |
| 0x6d8      | 1         | 0.83%   |
| 0x6d6      | 1         | 0.83%   |
| 0x506c9    | 1         | 0.83%   |
| 0x40661    | 1         | 0.83%   |
| 0x40651    | 1         | 0.83%   |
| 0x20652    | 1         | 0.83%   |
| 0x106e5    | 1         | 0.83%   |
| 0x106ca    | 1         | 0.83%   |
| 0x106c2    | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 16        | 13.56%  |
| Skylake          | 10        | 8.47%   |
| SandyBridge      | 10        | 8.47%   |
| IvyBridge        | 8         | 6.78%   |
| TigerLake        | 7         | 5.93%   |
| Zen 3            | 6         | 5.08%   |
| Westmere         | 6         | 5.08%   |
| Silvermont       | 5         | 4.24%   |
| Haswell          | 5         | 4.24%   |
| Goldmont plus    | 5         | 4.24%   |
| Unknown          | 5         | 4.24%   |
| Core             | 4         | 3.39%   |
| Zen+             | 3         | 2.54%   |
| Penryn           | 3         | 2.54%   |
| P6               | 3         | 2.54%   |
| Icelake          | 3         | 2.54%   |
| CometLake        | 3         | 2.54%   |
| Broadwell        | 3         | 2.54%   |
| Goldmont         | 2         | 1.69%   |
| Bonnell          | 2         | 1.69%   |
| Zen 2            | 1         | 0.85%   |
| Tremont          | 1         | 0.85%   |
| Puma             | 1         | 0.85%   |
| Nehalem          | 1         | 0.85%   |
| K8 Hammer        | 1         | 0.85%   |
| K8 & K10 hybrid  | 1         | 0.85%   |
| Excavator        | 1         | 0.85%   |
| Bobcat           | 1         | 0.85%   |
| Alderlake Hybrid | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 90        | 60.4%   |
| Nvidia | 36        | 24.16%  |
| AMD    | 23        | 15.44%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 5.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 5.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 4.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 3.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 3.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 2.55%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.55%   |
| Intel HD Graphics 530                                                                    | 4         | 2.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.55%   |
| AMD Lucienne                                                                             | 4         | 2.55%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.91%   |
| Intel HD Graphics 620                                                                    | 3         | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.27%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.27%   |
| Intel HD Graphics 6000                                                                   | 2         | 1.27%   |
| Intel HD Graphics 500                                                                    | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.27%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.27%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.27%   |
| Nvidia TU117M                                                                            | 1         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.64%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.64%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.64%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.64%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.64%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 52.54%  |
| Intel + Nvidia | 23        | 19.49%  |
| 1 x AMD        | 13        | 11.02%  |
| 1 x Nvidia     | 9         | 7.63%   |
| Intel + AMD    | 4         | 3.39%   |
| 2 x AMD        | 3         | 2.54%   |
| AMD + Nvidia   | 3         | 2.54%   |
| 2 x Intel      | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 83.61%  |
| Proprietary | 15        | 12.3%   |
| Unknown     | 5         | 4.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 79.17%  |
| 0.01-0.5   | 10        | 8.33%   |
| 0.51-1.0   | 6         | 5%      |
| 7.01-8.0   | 3         | 2.5%    |
| 3.01-4.0   | 3         | 2.5%    |
| 1.01-2.0   | 2         | 1.67%   |
| 2.01-3.0   | 1         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 18.18%  |
| Chimei Innolux          | 18        | 13.64%  |
| Samsung Electronics     | 14        | 10.61%  |
| BOE                     | 13        | 9.85%   |
| LG Display              | 12        | 9.09%   |
| Apple                   | 7         | 5.3%    |
| Chi Mei Optoelectronics | 6         | 4.55%   |
| PANDA                   | 5         | 3.79%   |
| Lenovo                  | 5         | 3.79%   |
| Hewlett-Packard         | 5         | 3.79%   |
| Sharp                   | 4         | 3.03%   |
| Goldstar                | 3         | 2.27%   |
| Sony                    | 2         | 1.52%   |
| CPT                     | 2         | 1.52%   |
| Ancor Communications    | 2         | 1.52%   |
| Sunplus                 | 1         | 0.76%   |
| STA                     | 1         | 0.76%   |
| Philips                 | 1         | 0.76%   |
| Panasonic               | 1         | 0.76%   |
| Packard Bell            | 1         | 0.76%   |
| LTM                     | 1         | 0.76%   |
| LG Philips              | 1         | 0.76%   |
| InfoVision              | 1         | 0.76%   |
| Eizo                    | 1         | 0.76%   |
| Dell                    | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 1.52%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 1.52%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 1.52%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 1.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch           | 2         | 1.52%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.76%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.76%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.76%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.76%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.76%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.76%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.76%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.76%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.76%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.76%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 530x300mm 24.0-inch        | 1         | 0.76%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.76%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch        | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 820x460mm 37.0-inch    | 1         | 0.76%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.76%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.76%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 1         | 0.76%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 0.76%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 0.76%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch             | 1         | 0.76%   |
| Packard Bell Viseo 230Ws PKB00C1 1920x1080 509x286mm 23.0-inch           | 1         | 0.76%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 0.76%   |
| LG Philips LCD Monitor LPLBB00 1024x768 304x228mm 15.0-inch              | 1         | 0.76%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 44.35%  |
| 1366x768 (WXGA)    | 32        | 25.81%  |
| 3840x2160 (4K)     | 8         | 6.45%   |
| 1280x800 (WXGA)    | 5         | 4.03%   |
| 1600x900 (HD+)     | 4         | 3.23%   |
| 2880x1800          | 3         | 2.42%   |
| 2560x1080          | 2         | 1.61%   |
| 1920x1200 (WUXGA)  | 2         | 1.61%   |
| 1440x900 (WXGA+)   | 2         | 1.61%   |
| 3840x2400          | 1         | 0.81%   |
| 2560x1600          | 1         | 0.81%   |
| 2560x1440 (QHD)    | 1         | 0.81%   |
| 2256x1504          | 1         | 0.81%   |
| 2160x1440          | 1         | 0.81%   |
| 1680x1050 (WSXGA+) | 1         | 0.81%   |
| 1400x1050          | 1         | 0.81%   |
| 1360x768           | 1         | 0.81%   |
| 1280x1024 (SXGA)   | 1         | 0.81%   |
| 1024x768 (XGA)     | 1         | 0.81%   |
| 1024x600           | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58        | 43.94%  |
| 13      | 14        | 10.61%  |
| 17      | 12        | 9.09%   |
| 14      | 11        | 8.33%   |
| 24      | 8         | 6.06%   |
| 11      | 7         | 5.3%    |
| 23      | 4         | 3.03%   |
| 21      | 3         | 2.27%   |
| 40      | 2         | 1.52%   |
| 34      | 2         | 1.52%   |
| 19      | 2         | 1.52%   |
| 84      | 1         | 0.76%   |
| 46      | 1         | 0.76%   |
| 32      | 1         | 0.76%   |
| 27      | 1         | 0.76%   |
| 25      | 1         | 0.76%   |
| 16      | 1         | 0.76%   |
| 12      | 1         | 0.76%   |
| 10      | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 73        | 55.73%  |
| 201-300     | 18        | 13.74%  |
| 351-400     | 15        | 11.45%  |
| 501-600     | 13        | 9.92%   |
| 401-500     | 4         | 3.05%   |
| 701-800     | 3         | 2.29%   |
| 801-900     | 2         | 1.53%   |
| 1501-2000   | 1         | 0.76%   |
| 1001-1500   | 1         | 0.76%   |
| Unknown     | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 93        | 79.49%  |
| 16/10 | 17        | 14.53%  |
| 4/3   | 2         | 1.71%   |
| 3/2   | 2         | 1.71%   |
| 21/9  | 2         | 1.71%   |
| 5/4   | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 44.7%   |
| 81-90          | 21        | 15.91%  |
| 201-250        | 12        | 9.09%   |
| 121-130        | 12        | 9.09%   |
| 51-60          | 7         | 5.3%    |
| 71-80          | 4         | 3.03%   |
| 351-500        | 3         | 2.27%   |
| 251-300        | 3         | 2.27%   |
| 151-200        | 3         | 2.27%   |
| 501-1000       | 3         | 2.27%   |
| More than 1000 | 1         | 0.76%   |
| 61-70          | 1         | 0.76%   |
| 41-50          | 1         | 0.76%   |
| 301-350        | 1         | 0.76%   |
| Unknown        | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 54        | 42.19%  |
| 51-100        | 29        | 22.66%  |
| 101-120       | 27        | 21.09%  |
| 161-240       | 9         | 7.03%   |
| More than 240 | 6         | 4.69%   |
| 1-50          | 2         | 1.56%   |
| Unknown       | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 93        | 76.23%  |
| 2     | 20        | 16.39%  |
| 0     | 6         | 4.92%   |
| 3     | 3         | 2.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 64        | 32.82%  |
| Intel                             | 62        | 31.79%  |
| Qualcomm Atheros                  | 25        | 12.82%  |
| Broadcom                          | 9         | 4.62%   |
| MediaTek                          | 6         | 3.08%   |
| Broadcom Limited                  | 6         | 3.08%   |
| Marvell Technology Group          | 5         | 2.56%   |
| TP-Link                           | 4         | 2.05%   |
| Sierra Wireless                   | 2         | 1.03%   |
| Nvidia                            | 2         | 1.03%   |
| Samsung Electronics               | 1         | 0.51%   |
| Ralink Technology                 | 1         | 0.51%   |
| Ralink                            | 1         | 0.51%   |
| Qualcomm Atheros Communications   | 1         | 0.51%   |
| NetGear                           | 1         | 0.51%   |
| Lenovo                            | 1         | 0.51%   |
| Ericsson Business Mobile Networks | 1         | 0.51%   |
| Dell                              | 1         | 0.51%   |
| ASUSTek Computer                  | 1         | 0.51%   |
| ASIX Electronics                  | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 41        | 17.67%  |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 3.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 7         | 3.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.16%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.16%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.16%   |
| Intel Wireless 8260                                                     | 5         | 2.16%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.29%   |
| Intel Wireless 7260                                                     | 3         | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.29%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.29%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.86%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.86%   |
| Intel Wireless 3165                                                     | 2         | 0.86%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.86%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.86%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.86%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.86%   |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.86%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                                    | 2         | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.86%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.86%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 48.03%  |
| Realtek Semiconductor           | 20        | 15.75%  |
| Qualcomm Atheros                | 18        | 14.17%  |
| Broadcom                        | 7         | 5.51%   |
| MediaTek                        | 6         | 4.72%   |
| Broadcom Limited                | 5         | 3.94%   |
| TP-Link                         | 3         | 2.36%   |
| Sierra Wireless                 | 2         | 1.57%   |
| Ralink Technology               | 1         | 0.79%   |
| Ralink                          | 1         | 0.79%   |
| Qualcomm Atheros Communications | 1         | 0.79%   |
| NetGear                         | 1         | 0.79%   |
| ASUSTek Computer                | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9         | 7.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.94%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.94%   |
| Intel Wireless 8260                                                     | 5         | 3.94%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 3.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 3.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2.36%   |
| Intel Wireless 7260                                                     | 3         | 2.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.36%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.36%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 1.57%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.57%   |
| Intel Wireless 3165                                                     | 2         | 1.57%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.57%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.79%   |
| Sierra Wireless EM7455                                                  | 1         | 0.79%   |
| Sierra Wireless EM7305                                                  | 1         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.79%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.79%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.79%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.79%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 57        | 57%     |
| Intel                    | 18        | 18%     |
| Qualcomm Atheros         | 10        | 10%     |
| Marvell Technology Group | 5         | 5%      |
| Broadcom                 | 3         | 3%      |
| Nvidia                   | 2         | 2%      |
| TP-Link                  | 1         | 1%      |
| Samsung Electronics      | 1         | 1%      |
| Lenovo                   | 1         | 1%      |
| Broadcom Limited         | 1         | 1%      |
| ASIX Electronics         | 1         | 1%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 40.2%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 6.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 6.86%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.96%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.96%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.96%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.96%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.96%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.96%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.96%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.96%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.98%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.98%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.98%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.98%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.98%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.98%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.98%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.98%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.98%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.98%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.98%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.98%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                            | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 53.77%  |
| Ethernet | 95        | 44.81%  |
| Modem    | 3         | 1.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 77.24%  |
| Ethernet | 28        | 22.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 73.11%  |
| 1     | 28        | 23.53%  |
| 0     | 3         | 2.52%   |
| 3     | 1         | 0.84%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 70.83%  |
| Yes  | 35        | 29.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 47.47%  |
| Qualcomm Atheros Communications | 10        | 10.1%   |
| Realtek Semiconductor           | 7         | 7.07%   |
| Apple                           | 7         | 7.07%   |
| Broadcom                        | 6         | 6.06%   |
| Foxconn / Hon Hai               | 5         | 5.05%   |
| Cambridge Silicon Radio         | 4         | 4.04%   |
| Lite-On Technology              | 3         | 3.03%   |
| IMC Networks                    | 3         | 3.03%   |
| Hewlett-Packard                 | 2         | 2.02%   |
| Ralink                          | 1         | 1.01%   |
| MediaTek                        | 1         | 1.01%   |
| Dell                            | 1         | 1.01%   |
| ASUSTek Computer                | 1         | 1.01%   |
| Alps Electric                   | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 16.16%  |
| Intel Bluetooth Device                                                              | 9         | 9.09%   |
| Intel AX200 Bluetooth                                                               | 9         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 8.08%   |
| Realtek Bluetooth Radio                                                             | 6         | 6.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 4.04%   |
| Apple Bluetooth Host Controller                                                     | 4         | 4.04%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 3.03%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.02%   |
| Lite-On Wireless_Device                                                             | 2         | 2.02%   |
| IMC Networks Wireless_Device                                                        | 2         | 2.02%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 2.02%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.01%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.01%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.01%   |
| MediaTek Wireless_Device                                                            | 1         | 1.01%   |
| Lite-On Bluetooth Radio                                                             | 1         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.01%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.01%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 1.01%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.01%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.01%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.01%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.01%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 1.01%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.01%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 96        | 62.75%  |
| Nvidia                  | 28        | 18.3%   |
| AMD                     | 19        | 12.42%  |
| Realtek Semiconductor   | 2         | 1.31%   |
| Texas Instruments       | 1         | 0.65%   |
| Plantronics             | 1         | 0.65%   |
| Logitech                | 1         | 0.65%   |
| Lenovo                  | 1         | 0.65%   |
| FIFINE 683 Microphone   | 1         | 0.65%   |
| CMX Systems             | 1         | 0.65%   |
| C-Media Electronics     | 1         | 0.65%   |
| BEHRINGER International | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 7.91%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 7.34%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 5.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 3.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.26%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 2.26%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.26%   |
| Nvidia Audio device                                                                               | 3         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.69%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 1.13%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.13%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.13%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.13%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.13%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.56%   |
| Plantronics BT600                                                                                 | 1         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.56%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 23.78%  |
| SK hynix            | 33        | 23.08%  |
| Unknown             | 16        | 11.19%  |
| Kingston            | 16        | 11.19%  |
| Micron Technology   | 13        | 9.09%   |
| Crucial             | 8         | 5.59%   |
| Unknown (ABCD)      | 3         | 2.1%    |
| Elpida              | 3         | 2.1%    |
| Corsair             | 3         | 2.1%    |
| Smart               | 2         | 1.4%    |
| Ramaxel Technology  | 2         | 1.4%    |
| Transcend           | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| PNY                 | 1         | 0.7%    |
| Nanya Technology    | 1         | 0.7%    |
| Innodisk            | 1         | 0.7%    |
| Avant               | 1         | 0.7%    |
| ASint Technology    | 1         | 0.7%    |
| A-DATA Technology   | 1         | 0.7%    |
| 48spaces            | 1         | 0.7%    |
| Unknown             | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 2.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 2.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.95%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 1.3%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.3%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.3%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.3%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 2         | 1.3%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 1.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.3%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.3%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.3%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.3%    |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.3%    |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 2         | 1.3%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.65%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.65%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.65%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.65%   |
| Smart RAM SF4641G8CK8IEGKSBG 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.65%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 50        | 41.67%  |
| DDR4   | 49        | 40.83%  |
| LPDDR4 | 7         | 5.83%   |
| DDR2   | 6         | 5%      |
| DDR    | 4         | 3.33%   |
| SDRAM  | 1         | 0.83%   |
| LPDDR3 | 1         | 0.83%   |
| DRAM   | 1         | 0.83%   |
| DDR5   | 1         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 113       | 94.17%  |
| Row Of Chips | 6         | 5%      |
| DIMM         | 1         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 52        | 39.1%   |
| 4096  | 43        | 32.33%  |
| 2048  | 19        | 14.29%  |
| 16384 | 10        | 7.52%   |
| 1024  | 6         | 4.51%   |
| 32768 | 2         | 1.5%    |
| 512   | 1         | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 30        | 23.08%  |
| 3200    | 22        | 16.92%  |
| 2667    | 15        | 11.54%  |
| 2400    | 14        | 10.77%  |
| 1333    | 9         | 6.92%   |
| Unknown | 9         | 6.92%   |
| 1334    | 7         | 5.38%   |
| 667     | 6         | 4.62%   |
| 2133    | 5         | 3.85%   |
| 1067    | 4         | 3.08%   |
| 4267    | 2         | 1.54%   |
| 8400    | 1         | 0.77%   |
| 4800    | 1         | 0.77%   |
| 4266    | 1         | 0.77%   |
| 4199    | 1         | 0.77%   |
| 2933    | 1         | 0.77%   |
| 533     | 1         | 0.77%   |
| 166     | 1         | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP LaserJet P2055 series | 1         | 25%     |
| HP LaserJet 1022         | 1         | 25%     |
| Canon LiDE 400           | 1         | 25%     |
| Brother DCP-L2540DW      | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 20.83%  |
| Microdia                               | 11        | 11.46%  |
| Acer                                   | 11        | 11.46%  |
| Realtek Semiconductor                  | 10        | 10.42%  |
| IMC Networks                           | 6         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.21%   |
| Sunplus Innovation Technology          | 4         | 4.17%   |
| Quanta                                 | 4         | 4.17%   |
| Apple                                  | 4         | 4.17%   |
| Ricoh                                  | 3         | 3.13%   |
| Lite-On Technology                     | 3         | 3.13%   |
| Lenovo                                 | 3         | 3.13%   |
| Suyin                                  | 2         | 2.08%   |
| Silicon Motion                         | 2         | 2.08%   |
| Alcor Micro                            | 2         | 2.08%   |
| Z-Star Microelectronics                | 1         | 1.04%   |
| Y Media                                | 1         | 1.04%   |
| Primax Electronics                     | 1         | 1.04%   |
| Luxvisions Innotech Limited            | 1         | 1.04%   |
| Logitech                               | 1         | 1.04%   |
| Goodong Industry                       | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 5         | 5.15%   |
| Chicony Integrated Camera                           | 4         | 4.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.09%   |
| Chicony HD User Facing                              | 3         | 3.09%   |
| Acer BisonCam,NB Pro                                | 3         | 3.09%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.06%   |
| Realtek USB Camera                                  | 2         | 2.06%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.06%   |
| Quanta HD User Facing                               | 2         | 2.06%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 2.06%   |
| IMC Networks Integrated Camera                      | 2         | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 2.06%   |
| Acer Integrated Camera                              | 2         | 2.06%   |
| Acer HD Webcam                                      | 2         | 2.06%   |
| Acer BisonCam, NB Pro                               | 2         | 2.06%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.03%   |
| Y Media USB Camera                                  | 1         | 1.03%   |
| Suyin Sony Visual Communication Camera              | 1         | 1.03%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.03%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.03%   |
| Sunplus ASUS Webcam                                 | 1         | 1.03%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 1.03%   |
| Silicon Motion Web Camera                           | 1         | 1.03%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.03%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.03%   |
| Ricoh Integrated Webcam                             | 1         | 1.03%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.03%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.03%   |
| Realtek Integrated Webcam HD                        | 1         | 1.03%   |
| Realtek Integrated Webcam                           | 1         | 1.03%   |
| Realtek EasyCamera                                  | 1         | 1.03%   |
| Realtek Built-In Video Camera                       | 1         | 1.03%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.03%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.03%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 1.03%   |
| Microdia Webcam Vitade AF                           | 1         | 1.03%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 1.03%   |
| Microdia Webcam                                     | 1         | 1.03%   |
| Microdia USB 2.0 Camera                             | 1         | 1.03%   |
| Microdia Sony Visual Communication Camera           | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 28.57%  |
| Synaptics                  | 5         | 23.81%  |
| AuthenTec                  | 4         | 19.05%  |
| Shenzhen Goodix Technology | 3         | 14.29%  |
| Upek                       | 2         | 9.52%   |
| Elan Microelectronics      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 9.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 9.52%   |
| AuthenTec AES2810                                      | 2         | 9.52%   |
| Unknown                                                | 2         | 9.52%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.76%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.76%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 40%     |
| Alcor Micro           | 4         | 40%     |
| Advanced Card Systems | 2         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 74        | 59.68%  |
| 1     | 35        | 28.23%  |
| 2     | 13        | 10.48%  |
| 3     | 2         | 1.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 26        | 41.94%  |
| Fingerprint reader       | 21        | 33.87%  |
| Chipcard                 | 8         | 12.9%   |
| Multimedia controller    | 3         | 4.84%   |
| Camera                   | 2         | 3.23%   |
| Net/ethernet             | 1         | 1.61%   |
| Communication controller | 1         | 1.61%   |

