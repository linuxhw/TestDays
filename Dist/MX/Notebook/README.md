MX - Tested Hardware & Statistics (Notebooks)
---------------------------------------------

A project to collect tested hardware configurations for MX.

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

Total: 369

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
| Dell          | Latitude 7480               | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
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
| Lenovo        | ThinkPad T420 4236TL7       | [8a639f4457](https://linux-hardware.org/?probe=8a639f4457) | Oct 10, 2022 |
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
| ASUSTek       | ASUSPRO P3540FA_P3540FA     | [f8f2a6263a](https://linux-hardware.org/?probe=f8f2a6263a) | Sep 04, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Lenovo        | ThinkPad T500 2241VL9       | [35c8369d91](https://linux-hardware.org/?probe=35c8369d91) | Aug 25, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| win elemen... | MoreFine S500+              | [295b2926da](https://linux-hardware.org/?probe=295b2926da) | Aug 19, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| win elemen... | MoreFine S500+              | [abdf1d084a](https://linux-hardware.org/?probe=abdf1d084a) | Aug 18, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Acer          | Extensa 5630                | [9ea053d8e8](https://linux-hardware.org/?probe=9ea053d8e8) | Aug 12, 2022 |
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
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
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
| Acer          | Extensa 5630                | [32cab1f9fc](https://linux-hardware.org/?probe=32cab1f9fc) | Mar 14, 2022 |
| Dell          | Latitude 3190               | [964420352c](https://linux-hardware.org/?probe=964420352c) | Feb 28, 2022 |
| Dell          | XPS 17 9710                 | [7147fe2d5c](https://linux-hardware.org/?probe=7147fe2d5c) | Feb 26, 2022 |
| ASUSTek       | 1101HA                      | [b234cc741f](https://linux-hardware.org/?probe=b234cc741f) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | [851badde2e](https://linux-hardware.org/?probe=851badde2e) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| Sony          | SVE1513Q1ESI                | [77e599ef9f](https://linux-hardware.org/?probe=77e599ef9f) | Feb 08, 2022 |
| Dell          | Latitude E4310              | [50190cb420](https://linux-hardware.org/?probe=50190cb420) | Feb 06, 2022 |
| efirstview    | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| HP            | ProBook 6460b               | [5f936a65be](https://linux-hardware.org/?probe=5f936a65be) | Feb 02, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Sony          | VPCEH2N1E                   | [17a4bc1847](https://linux-hardware.org/?probe=17a4bc1847) | Jan 22, 2022 |
| Fujitsu Si... | LIFEBOOK E8010              | [82d1bc5db0](https://linux-hardware.org/?probe=82d1bc5db0) | Jan 22, 2022 |
| MSI           | Alpha 15 B5EEK              | [882906d968](https://linux-hardware.org/?probe=882906d968) | Jan 17, 2022 |
| Alienware     | 13 R2                       | [65c1ae9026](https://linux-hardware.org/?probe=65c1ae9026) | Jan 14, 2022 |
| HP            | EliteBook 840 G3            | [58cff543b5](https://linux-hardware.org/?probe=58cff543b5) | Jan 06, 2022 |
| HP            | EliteBook 8440p             | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Lenovo        | G400s VILG1                 | [1cd4b24f16](https://linux-hardware.org/?probe=1cd4b24f16) | Jan 04, 2022 |
| Gigabyte      | P15FV5                      | [164348e568](https://linux-hardware.org/?probe=164348e568) | Jan 03, 2022 |
| HP            | 2000                        | [5d64fe5b92](https://linux-hardware.org/?probe=5d64fe5b92) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [4fe24b4f44](https://linux-hardware.org/?probe=4fe24b4f44) | Dec 26, 2021 |
| ASUSTek       | X550CC                      | [b0cde813b9](https://linux-hardware.org/?probe=b0cde813b9) | Dec 23, 2021 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [63d7055c5e](https://linux-hardware.org/?probe=63d7055c5e) | Dec 18, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [49692045a2](https://linux-hardware.org/?probe=49692045a2) | Dec 16, 2021 |
| Toshiba       | Satellite L850-CJK          | [0dc076ad15](https://linux-hardware.org/?probe=0dc076ad15) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21180cbdad](https://linux-hardware.org/?probe=21180cbdad) | Dec 04, 2021 |
| Lenovo        | B590 20208                  | [ed08d6bdd9](https://linux-hardware.org/?probe=ed08d6bdd9) | Nov 30, 2021 |
| Lenovo        | Unknown                     | [5b1b00738d](https://linux-hardware.org/?probe=5b1b00738d) | Nov 28, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [649434f9b8](https://linux-hardware.org/?probe=649434f9b8) | Nov 23, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [791ae651bb](https://linux-hardware.org/?probe=791ae651bb) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [b105aaabf5](https://linux-hardware.org/?probe=b105aaabf5) | Nov 14, 2021 |
| HP            | Compaq Presario CQ60        | [9d83baca33](https://linux-hardware.org/?probe=9d83baca33) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c277967769](https://linux-hardware.org/?probe=c277967769) | Nov 11, 2021 |
| Dell          | Inspiron 3576               | [ad9fb758a6](https://linux-hardware.org/?probe=ad9fb758a6) | Nov 09, 2021 |
| Apple         | MacBook3,1                  | [25964b9256](https://linux-hardware.org/?probe=25964b9256) | Nov 08, 2021 |
| Google        | Akemi                       | [7408ab9056](https://linux-hardware.org/?probe=7408ab9056) | Nov 06, 2021 |
| Google        | Akemi                       | [dc4808bd56](https://linux-hardware.org/?probe=dc4808bd56) | Nov 06, 2021 |
| HP            | EliteBook 850 G3            | [cd26ab6e8f](https://linux-hardware.org/?probe=cd26ab6e8f) | Nov 05, 2021 |
| Dell          | Latitude 3190               | [592b613273](https://linux-hardware.org/?probe=592b613273) | Nov 01, 2021 |
| ASUSTek       | E402MA                      | [4c2453c6a2](https://linux-hardware.org/?probe=4c2453c6a2) | Oct 26, 2021 |
| Dell          | Latitude E7450              | [91837758ac](https://linux-hardware.org/?probe=91837758ac) | Oct 26, 2021 |
| Sony          | VPCEC3S1E                   | [2af79ba873](https://linux-hardware.org/?probe=2af79ba873) | Oct 25, 2021 |
| Dell          | Latitude 3190               | [d08efa2ef3](https://linux-hardware.org/?probe=d08efa2ef3) | Oct 25, 2021 |
| Lenovo        | ThinkPad L520 78595VG       | [4aff5a6a0c](https://linux-hardware.org/?probe=4aff5a6a0c) | Oct 24, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| Fujitsu Si... | AMILO Xa 1526               | [00863fcea8](https://linux-hardware.org/?probe=00863fcea8) | Oct 16, 2021 |
| Sony          | SVT13115FBS                 | [381872f3b9](https://linux-hardware.org/?probe=381872f3b9) | Oct 09, 2021 |
| Lenovo        | ThinkPad T530 2394CJ9       | [b36a94241d](https://linux-hardware.org/?probe=b36a94241d) | Oct 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Lenovo        | ThinkPad L490 20Q5S0PR00    | [bbf6b89f02](https://linux-hardware.org/?probe=bbf6b89f02) | Oct 01, 2021 |
| Acer          | Aspire 4820T                | [a91911ca90](https://linux-hardware.org/?probe=a91911ca90) | Oct 01, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [8c1a085f29](https://linux-hardware.org/?probe=8c1a085f29) | Sep 20, 2021 |
| Lenovo        | ThinkPad P51 20HJS0TP00     | [2774c819ea](https://linux-hardware.org/?probe=2774c819ea) | Sep 18, 2021 |
| Lenovo        | B40-45 20394                | [627672a7ec](https://linux-hardware.org/?probe=627672a7ec) | Sep 16, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [e76ffa7805](https://linux-hardware.org/?probe=e76ffa7805) | Sep 06, 2021 |
| GTZS          | Unknown                     | [3df799f341](https://linux-hardware.org/?probe=3df799f341) | Sep 05, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| Chuwi         | GemiBook Pro                | [f8735054b4](https://linux-hardware.org/?probe=f8735054b4) | Sep 02, 2021 |
| Pixus         | Rise                        | [4479b88c1c](https://linux-hardware.org/?probe=4479b88c1c) | Aug 12, 2021 |
| Acer          | TravelMate 5360             | [f444dec794](https://linux-hardware.org/?probe=f444dec794) | Aug 12, 2021 |
| Lenovo        | ThinkPad T420 4236MBU       | [7e0b868c64](https://linux-hardware.org/?probe=7e0b868c64) | Jul 29, 2021 |
| Acer          | Aspire E5-574G              | [b09280946d](https://linux-hardware.org/?probe=b09280946d) | Jul 21, 2021 |
| Dell          | Vostro 5515                 | [f4ae054fc8](https://linux-hardware.org/?probe=f4ae054fc8) | Jul 15, 2021 |
| Dell          | Latitude 3340               | [c47b83476b](https://linux-hardware.org/?probe=c47b83476b) | Jul 12, 2021 |
| Acer          | Aspire one                  | [2c266e91ae](https://linux-hardware.org/?probe=2c266e91ae) | Jul 09, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c4ebb4c114](https://linux-hardware.org/?probe=c4ebb4c114) | Jun 04, 2021 |
| Dell          | Vostro 3460                 | [da200f9e64](https://linux-hardware.org/?probe=da200f9e64) | May 29, 2021 |
| Medion        | E6234                       | [313ec752ab](https://linux-hardware.org/?probe=313ec752ab) | May 24, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [4ed89e1092](https://linux-hardware.org/?probe=4ed89e1092) | May 22, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [57a69c7c0d](https://linux-hardware.org/?probe=57a69c7c0d) | May 20, 2021 |
| HP            | Mini 110-3500               | [f94c828225](https://linux-hardware.org/?probe=f94c828225) | May 19, 2021 |
| ASUSTek       | N56VZ                       | [c69cd5aceb](https://linux-hardware.org/?probe=c69cd5aceb) | May 18, 2021 |
| Irbis         | TW94                        | [dc56e23810](https://linux-hardware.org/?probe=dc56e23810) | May 15, 2021 |
| Dell          | Latitude E6320              | [fa8bcef5a9](https://linux-hardware.org/?probe=fa8bcef5a9) | May 09, 2021 |
| Acer          | Extensa 5620                | [a06636ba79](https://linux-hardware.org/?probe=a06636ba79) | Apr 24, 2021 |
| Dell          | 0UW744??????                | [32c3521a2e](https://linux-hardware.org/?probe=32c3521a2e) | Apr 22, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [73f2bd0075](https://linux-hardware.org/?probe=73f2bd0075) | Apr 16, 2021 |
| Lenovo        | ThinkPad T440s 20AQ007SG... | [75e60ebdf4](https://linux-hardware.org/?probe=75e60ebdf4) | Apr 16, 2021 |
| Intel         | ChiefRiver                  | [5e0db0f704](https://linux-hardware.org/?probe=5e0db0f704) | Apr 14, 2021 |
| eMachines     | E727                        | [048da4f23b](https://linux-hardware.org/?probe=048da4f23b) | Apr 12, 2021 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [7159579bb8](https://linux-hardware.org/?probe=7159579bb8) | Apr 12, 2021 |
| ASUSTek       | G751JT                      | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| HP            | Falco                       | [9bb0bf9ac8](https://linux-hardware.org/?probe=9bb0bf9ac8) | Apr 07, 2021 |
| ASUSTek       | 1025C                       | [33d6531353](https://linux-hardware.org/?probe=33d6531353) | Apr 06, 2021 |
| HP            | ZBook 17 G6                 | [046176e590](https://linux-hardware.org/?probe=046176e590) | Mar 16, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| HP            | Notebook                    | [113644885d](https://linux-hardware.org/?probe=113644885d) | Mar 04, 2021 |
| Acer          | AOD255                      | [f8501e519f](https://linux-hardware.org/?probe=f8501e519f) | Mar 03, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| Lenovo        | ThinkPad E425 1198CTO       | [67304f1ffa](https://linux-hardware.org/?probe=67304f1ffa) | Feb 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [6f34bc4f67](https://linux-hardware.org/?probe=6f34bc4f67) | Feb 19, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7552dacfb9](https://linux-hardware.org/?probe=7552dacfb9) | Feb 17, 2021 |
| HP            | Mini 110-3500               | [bb5cf4031b](https://linux-hardware.org/?probe=bb5cf4031b) | Feb 13, 2021 |
| HP            | Notebook                    | [69f70d7a09](https://linux-hardware.org/?probe=69f70d7a09) | Feb 10, 2021 |
| HP            | 15                          | [437cb08f68](https://linux-hardware.org/?probe=437cb08f68) | Feb 08, 2021 |
| Apple         | MacBook7,1                  | [a6324a9e06](https://linux-hardware.org/?probe=a6324a9e06) | Feb 05, 2021 |
| Clevo         | P170EM                      | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [b6ebe98655](https://linux-hardware.org/?probe=b6ebe98655) | Feb 01, 2021 |
| HP            | ProBook 650 G1              | [9021b90504](https://linux-hardware.org/?probe=9021b90504) | Jan 22, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a147ddbe9d](https://linux-hardware.org/?probe=a147ddbe9d) | Jan 20, 2021 |
| HP            | Mini 110-3500               | [3c2a01636e](https://linux-hardware.org/?probe=3c2a01636e) | Jan 19, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| Dell          | Latitude E5520              | [1d46b26326](https://linux-hardware.org/?probe=1d46b26326) | Jan 03, 2021 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | Aspire ES1-511              | [7f351d7c49](https://linux-hardware.org/?probe=7f351d7c49) | Dec 30, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5de3914984](https://linux-hardware.org/?probe=5de3914984) | Dec 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [ebb2dc7bff](https://linux-hardware.org/?probe=ebb2dc7bff) | Dec 15, 2020 |
| Lenovo        | ThinkPad X220 4291WMQ       | [165b895e27](https://linux-hardware.org/?probe=165b895e27) | Dec 01, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| Acer          | Aspire E5-571G              | [7f5f7e9fff](https://linux-hardware.org/?probe=7f5f7e9fff) | Nov 17, 2020 |
| Toshiba       | Satellite A300              | [309a3f69e8](https://linux-hardware.org/?probe=309a3f69e8) | Nov 16, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [554dfc3cfe](https://linux-hardware.org/?probe=554dfc3cfe) | Nov 12, 2020 |
| Lenovo        | ThinkPad T410 2537G99       | [2dc30b7928](https://linux-hardware.org/?probe=2dc30b7928) | Nov 12, 2020 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fe6cbf555a](https://linux-hardware.org/?probe=fe6cbf555a) | Nov 08, 2020 |
| Dell          | Inspiron 14-3452            | [96e87a665b](https://linux-hardware.org/?probe=96e87a665b) | Nov 01, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [470c0ca72b](https://linux-hardware.org/?probe=470c0ca72b) | Oct 23, 2020 |
| HP            | Compaq 8510p (KM229AV)      | [30634ffde6](https://linux-hardware.org/?probe=30634ffde6) | Oct 12, 2020 |
| Acer          | Aspire SW5-015              | [b125bdb89e](https://linux-hardware.org/?probe=b125bdb89e) | Oct 07, 2020 |
| HP            | Pavilion 15                 | [8e6632f1a3](https://linux-hardware.org/?probe=8e6632f1a3) | Oct 06, 2020 |
| Lenovo        | V145-15AST 81MT             | [7155397289](https://linux-hardware.org/?probe=7155397289) | Oct 03, 2020 |
| Lenovo        | ThinkPad T400 2768WGB       | [995b1a3a3d](https://linux-hardware.org/?probe=995b1a3a3d) | Sep 29, 2020 |
| Toshiba       | Satellite C660              | [a5f308c899](https://linux-hardware.org/?probe=a5f308c899) | Sep 21, 2020 |
| Lenovo        | ThinkPad T60 20085TG        | [31cd0f06c2](https://linux-hardware.org/?probe=31cd0f06c2) | Sep 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [356bacc97a](https://linux-hardware.org/?probe=356bacc97a) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [c36d170750](https://linux-hardware.org/?probe=c36d170750) | Aug 27, 2020 |
| HP            | ZBook 15 G4                 | [00d13faf2a](https://linux-hardware.org/?probe=00d13faf2a) | Aug 27, 2020 |
| Acer          | Aspire A114-32              | [7f178a7089](https://linux-hardware.org/?probe=7f178a7089) | Aug 20, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9b4d2c057e](https://linux-hardware.org/?probe=9b4d2c057e) | Aug 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [57e274292b](https://linux-hardware.org/?probe=57e274292b) | Aug 16, 2020 |
| Acer          | Aspire 7520                 | [d878dbb71e](https://linux-hardware.org/?probe=d878dbb71e) | Aug 13, 2020 |
| HP            | Pavilion dv7                | [3494105666](https://linux-hardware.org/?probe=3494105666) | Jul 28, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [c0d166e020](https://linux-hardware.org/?probe=c0d166e020) | Jul 27, 2020 |
| HP            | ProBook 650 G1              | [9a488079c3](https://linux-hardware.org/?probe=9a488079c3) | Jul 23, 2020 |
| Sony          | VPCF23P1E                   | [2e0915f8a9](https://linux-hardware.org/?probe=2e0915f8a9) | Jun 18, 2020 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [54a69351ae](https://linux-hardware.org/?probe=54a69351ae) | Jun 17, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [b93dafce99](https://linux-hardware.org/?probe=b93dafce99) | Jun 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS4YA00    | [72150af905](https://linux-hardware.org/?probe=72150af905) | Jun 06, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| Acer          | Aspire A315-41              | [665b2837c7](https://linux-hardware.org/?probe=665b2837c7) | May 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c85746245d](https://linux-hardware.org/?probe=c85746245d) | May 26, 2020 |
| Lenovo        | B590 20206                  | [8f4a7e2b6e](https://linux-hardware.org/?probe=8f4a7e2b6e) | May 26, 2020 |
| Lenovo        | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| Samsung       | R780/R778                   | [eb0bb63c6d](https://linux-hardware.org/?probe=eb0bb63c6d) | Apr 09, 2020 |
| Clevo         | P150HMx                     | [196b689717](https://linux-hardware.org/?probe=196b689717) | Mar 27, 2020 |
| Dell          | Latitude E7440              | [c6fe81343e](https://linux-hardware.org/?probe=c6fe81343e) | Mar 26, 2020 |
| ASUSTek       | X455LAB                     | [4a5174a726](https://linux-hardware.org/?probe=4a5174a726) | Mar 24, 2020 |
| Notebook      | W65_W67RZ1                  | [aaffd10ebf](https://linux-hardware.org/?probe=aaffd10ebf) | Mar 24, 2020 |
| Dell          | Inspiron 13-5378            | [242a7e4fdc](https://linux-hardware.org/?probe=242a7e4fdc) | Mar 24, 2020 |
| Clevo         | P150HMx                     | [8f9823569b](https://linux-hardware.org/?probe=8f9823569b) | Mar 24, 2020 |
| Dell          | Inspiron N5010              | [8654fde26b](https://linux-hardware.org/?probe=8654fde26b) | Mar 24, 2020 |
| Medion        | Akoya E1318T                | [d6be35c8af](https://linux-hardware.org/?probe=d6be35c8af) | Mar 20, 2020 |
| Dell          | Latitude 3190               | [1bab98d664](https://linux-hardware.org/?probe=1bab98d664) | Mar 20, 2020 |
| HP            | EliteBook 8560p             | [e5925f1349](https://linux-hardware.org/?probe=e5925f1349) | Mar 07, 2020 |
| Acer          | Aspire 8943G                | [f8e194e907](https://linux-hardware.org/?probe=f8e194e907) | Mar 01, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [370f5d5063](https://linux-hardware.org/?probe=370f5d5063) | Feb 26, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T11... | [9c888bfdde](https://linux-hardware.org/?probe=9c888bfdde) | Feb 11, 2020 |
| Lenovo        | ThinkPad X201 3680MY9       | [26a7c0e493](https://linux-hardware.org/?probe=26a7c0e493) | Feb 09, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [8865e9546b](https://linux-hardware.org/?probe=8865e9546b) | Feb 03, 2020 |
| Lenovo        | ThinkPad W510 4875W17       | [f4779c95ce](https://linux-hardware.org/?probe=f4779c95ce) | Feb 03, 2020 |
| Acer          | Swift SF314-54G             | [48912b8dc6](https://linux-hardware.org/?probe=48912b8dc6) | Jan 19, 2020 |
| ASUSTek       | TUF Gaming FX505GT_TUF50... | [0abd5b1d73](https://linux-hardware.org/?probe=0abd5b1d73) | Jan 18, 2020 |
| Toshiba       | Satellite P875              | [b267e93d40](https://linux-hardware.org/?probe=b267e93d40) | Jan 15, 2020 |
| Toshiba       | Satellite P875              | [7e579fcba2](https://linux-hardware.org/?probe=7e579fcba2) | Jan 15, 2020 |
| MSI           | GP63 Leopard 8RD            | [0a8865c437](https://linux-hardware.org/?probe=0a8865c437) | Jan 13, 2020 |
| Packard Be... | EasyNote TE11HC             | [aa52528043](https://linux-hardware.org/?probe=aa52528043) | Jan 13, 2020 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [ba3b839fa4](https://linux-hardware.org/?probe=ba3b839fa4) | Jan 12, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [7f8e86e96b](https://linux-hardware.org/?probe=7f8e86e96b) | Jan 12, 2020 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Toshiba       | Satellite C50-A-12K         | [a413f419ef](https://linux-hardware.org/?probe=a413f419ef) | Dec 17, 2019 |
| Dell          | G3 3579                     | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| MSI           | MS-N033                     | [a5ee4c1dc1](https://linux-hardware.org/?probe=a5ee4c1dc1) | Nov 17, 2019 |
| ASUSTek       | 1005HA                      | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Lenovo        | ThinkPad X301 2776LBU       | [993b5f104a](https://linux-hardware.org/?probe=993b5f104a) | Nov 17, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| HP            | ProBook 4440s               | [fc67acaa63](https://linux-hardware.org/?probe=fc67acaa63) | Oct 29, 2019 |
| HP            | Laptop 14-cm0xxx            | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| MSI           | GP63 Leopard 8RD            | [df3af7b333](https://linux-hardware.org/?probe=df3af7b333) | Oct 23, 2019 |
| HP            | EliteBook 8540w             | [ea8ef5afc7](https://linux-hardware.org/?probe=ea8ef5afc7) | Oct 23, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| Lenovo        | ThinkPad X220 4291F52       | [e024139431](https://linux-hardware.org/?probe=e024139431) | Aug 29, 2019 |
| Lenovo        | ThinkPad X201s 5413A19      | [673c3629dc](https://linux-hardware.org/?probe=673c3629dc) | Aug 22, 2019 |
| Panasonic     | CF-C1BT02EGE                | [acbec08287](https://linux-hardware.org/?probe=acbec08287) | Aug 15, 2019 |
| MSI           | GP63 Leopard 8RD            | [bf82fba8fd](https://linux-hardware.org/?probe=bf82fba8fd) | Apr 29, 2019 |
| ASUSTek       | K55VM                       | [e967dd6404](https://linux-hardware.org/?probe=e967dd6404) | Mar 27, 2019 |
| MSI           | GP63 Leopard 8RD            | [67b484c4a0](https://linux-hardware.org/?probe=67b484c4a0) | Jan 19, 2019 |
| Toshiba       | Satellite C70-B             | [9b54677f2e](https://linux-hardware.org/?probe=9b54677f2e) | Oct 27, 2018 |
| MSI           | GP63 Leopard 8RD            | [ec89febb0c](https://linux-hardware.org/?probe=ec89febb0c) | Oct 27, 2018 |
| Dell          | Inspiron ME051              | [f789720dc4](https://linux-hardware.org/?probe=f789720dc4) | Nov 26, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MX 21 | 118       | 44.7%   |
| MX 19 | 87        | 32.95%  |
| MX 20 | 43        | 16.29%  |
| MX 18 | 13        | 4.92%   |
| MX 17 | 2         | 0.76%   |
| MX 16 | 1         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| MX   | 256       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 4.19.0-6-amd64           | 34        | 11.85%  |
| 5.10.0-9-amd64           | 14        | 4.88%   |
| 5.10.0-13-amd64          | 14        | 4.88%   |
| 5.10.0-5mx-amd64         | 13        | 4.53%   |
| 5.10.0-18-amd64          | 11        | 3.83%   |
| 5.8.0-3-amd64            | 9         | 3.14%   |
| 5.10.0-16-amd64          | 9         | 3.14%   |
| 5.14.0-4mx-amd64         | 8         | 2.79%   |
| 5.10.0-19-amd64          | 8         | 2.79%   |
| 4.19.0-13-amd64          | 7         | 2.44%   |
| 5.16.0-5mx-amd64         | 6         | 2.09%   |
| 5.10.0-14-amd64          | 6         | 2.09%   |
| 5.10.0-11-amd64          | 6         | 2.09%   |
| 4.19.0-16-amd64          | 6         | 2.09%   |
| 4.19.0-14-amd64          | 6         | 2.09%   |
| 5.6.0-2-amd64            | 5         | 1.74%   |
| 5.18.0-4mx-amd64         | 5         | 1.74%   |
| 6.0.0-4mx-amd64          | 4         | 1.39%   |
| 4.19.0-5-amd64           | 4         | 1.39%   |
| 4.19.0-17-amd64          | 4         | 1.39%   |
| 4.19.0-11-amd64          | 4         | 1.39%   |
| 5.10.0-8mx-amd64         | 3         | 1.05%   |
| 5.10.0-20-amd64          | 3         | 1.05%   |
| 5.10.0-17-amd64          | 3         | 1.05%   |
| 4.19.0-9-amd64           | 3         | 1.05%   |
| 4.19.0-12-amd64          | 3         | 1.05%   |
| 4.19.0-1-amd64           | 3         | 1.05%   |
| 6.0.0-3mx-amd64          | 2         | 0.7%    |
| 5.8.16-antix.1-amd64-smp | 2         | 0.7%    |
| 5.6.10-antix.1-amd64-smp | 2         | 0.7%    |
| 5.4.0-3-amd64            | 2         | 0.7%    |
| 5.19.0-2mx-amd64         | 2         | 0.7%    |
| 5.16.0-6mx-amd64         | 2         | 0.7%    |
| 5.10.0-8-amd64           | 2         | 0.7%    |
| 5.10.0-15-amd64          | 2         | 0.7%    |
| 5.10.0-13-686-pae        | 2         | 0.7%    |
| 5.10.0-11-686-pae        | 2         | 0.7%    |
| 5.10.0-10-amd64          | 2         | 0.7%    |
| 4.19.0-8-amd64           | 2         | 0.7%    |
| 4.19.0-16-686-pae        | 2         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 99        | 36.13%  |
| 4.19.0   | 83        | 30.29%  |
| 5.16.0   | 10        | 3.65%   |
| 5.8.0    | 9         | 3.28%   |
| 5.14.0   | 8         | 2.92%   |
| 6.0.0    | 7         | 2.55%   |
| 5.6.0    | 7         | 2.55%   |
| 5.18.0   | 7         | 2.55%   |
| 5.4.0    | 6         | 2.19%   |
| 5.17.0   | 4         | 1.46%   |
| 5.19.0   | 3         | 1.09%   |
| 5.8.16   | 2         | 0.73%   |
| 5.6.10   | 2         | 0.73%   |
| 5.3.0    | 2         | 0.73%   |
| 5.2.21   | 2         | 0.73%   |
| 5.15.0   | 2         | 0.73%   |
| 4.9.193  | 2         | 0.73%   |
| 4.15.0   | 2         | 0.73%   |
| 5.9.1    | 1         | 0.36%   |
| 5.7.0    | 1         | 0.36%   |
| 5.5.0    | 1         | 0.36%   |
| 5.3.10   | 1         | 0.36%   |
| 5.2.8    | 1         | 0.36%   |
| 5.2.0    | 1         | 0.36%   |
| 5.13.0   | 1         | 0.36%   |
| 5.11.0   | 1         | 0.36%   |
| 5.10.82  | 1         | 0.36%   |
| 5.10.1   | 1         | 0.36%   |
| 5.1.2    | 1         | 0.36%   |
| 5.0.0    | 1         | 0.36%   |
| 4.9.246  | 1         | 0.36%   |
| 4.19.174 | 1         | 0.36%   |
| 4.18.0   | 1         | 0.36%   |
| 3.16.0   | 1         | 0.36%   |
| Unknown  | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 101       | 36.86%  |
| 4.19    | 84        | 30.66%  |
| 5.8     | 11        | 4.01%   |
| 5.16    | 10        | 3.65%   |
| 5.6     | 9         | 3.28%   |
| 5.14    | 8         | 2.92%   |
| 6.0     | 7         | 2.55%   |
| 5.18    | 7         | 2.55%   |
| 5.4     | 6         | 2.19%   |
| 5.2     | 4         | 1.46%   |
| 5.17    | 4         | 1.46%   |
| 5.3     | 3         | 1.09%   |
| 5.19    | 3         | 1.09%   |
| 4.9     | 3         | 1.09%   |
| 5.15    | 2         | 0.73%   |
| 4.15    | 2         | 0.73%   |
| 5.9     | 1         | 0.36%   |
| 5.7     | 1         | 0.36%   |
| 5.5     | 1         | 0.36%   |
| 5.13    | 1         | 0.36%   |
| 5.11    | 1         | 0.36%   |
| 5.1     | 1         | 0.36%   |
| 5.0     | 1         | 0.36%   |
| 4.18    | 1         | 0.36%   |
| 3.16    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 240       | 93.39%  |
| i686   | 17        | 6.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 187       | 71.37%  |
| KDE5            | 42        | 16.03%  |
| Budgie          | 7         | 2.67%   |
| Unknown         | 6         | 2.29%   |
| i3              | 5         | 1.91%   |
| MATE            | 2         | 0.76%   |
| LXQt            | 2         | 0.76%   |
| GNOME           | 2         | 0.76%   |
| Cinnamon        | 2         | 0.76%   |
| X-Cinnamon      | 1         | 0.38%   |
| Trinity         | 1         | 0.38%   |
| spectrwm        | 1         | 0.38%   |
| LXDE            | 1         | 0.38%   |
| GNOME Flashback | 1         | 0.38%   |
| GNOME Classic   | 1         | 0.38%   |
| fluxbox         | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 253       | 98.83%  |
| Tty  | 3         | 1.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 208       | 80%     |
| SDDM    | 36        | 13.85%  |
| TDM     | 9         | 3.46%   |
| SLiM    | 6         | 2.31%   |
| Unknown | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 94        | 35.61%  |
| Unknown | 57        | 21.59%  |
| de_DE   | 27        | 10.23%  |
| en_GB   | 16        | 6.06%   |
| it_IT   | 10        | 3.79%   |
| ru_RU   | 9         | 3.41%   |
| sk_SK   | 6         | 2.27%   |
| pt_BR   | 5         | 1.89%   |
| fr_FR   | 5         | 1.89%   |
| es_ES   | 4         | 1.52%   |
| en_AU   | 4         | 1.52%   |
| pl_PL   | 3         | 1.14%   |
| tr_TR   | 2         | 0.76%   |
| nl_NL   | 2         | 0.76%   |
| en_NZ   | 2         | 0.76%   |
| en_IE   | 2         | 0.76%   |
| bg_BG   | 2         | 0.76%   |
| zh_CN   | 1         | 0.38%   |
| uk_UA   | 1         | 0.38%   |
| nb_NO   | 1         | 0.38%   |
| id_ID   | 1         | 0.38%   |
| hu_HU   | 1         | 0.38%   |
| fr_BE   | 1         | 0.38%   |
| fi_FI   | 1         | 0.38%   |
| es_VE   | 1         | 0.38%   |
| es_UY   | 1         | 0.38%   |
| es_PE   | 1         | 0.38%   |
| es_MX   | 1         | 0.38%   |
| es_CO   | 1         | 0.38%   |
| de_CH   | 1         | 0.38%   |
| cs_CZ   | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 145       | 56.64%  |
| BIOS | 111       | 43.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 220       | 85.27%  |
| Overlay | 29        | 11.24%  |
| Btrfs   | 6         | 2.33%   |
| Xfs     | 1         | 0.39%   |
| F2fs    | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 163       | 63.42%  |
| MBR     | 90        | 35.02%  |
| Unknown | 4         | 1.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 206       | 79.23%  |
| Yes       | 54        | 20.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 151       | 58.75%  |
| Yes       | 106       | 41.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 58        | 22.66%  |
| Hewlett-Packard     | 39        | 15.23%  |
| Dell                | 31        | 12.11%  |
| ASUSTek Computer    | 27        | 10.55%  |
| Acer                | 24        | 9.38%   |
| Toshiba             | 11        | 4.3%    |
| Sony                | 10        | 3.91%   |
| Apple               | 9         | 3.52%   |
| MSI                 | 6         | 2.34%   |
| Samsung Electronics | 5         | 1.95%   |
| Medion              | 5         | 1.95%   |
| Fujitsu Siemens     | 3         | 1.17%   |
| Alienware           | 3         | 1.17%   |
| Notebook            | 2         | 0.78%   |
| Google              | 2         | 0.78%   |
| Gigabyte Technology | 2         | 0.78%   |
| Clevo               | 2         | 0.78%   |
| Unknown             | 2         | 0.78%   |
| win element         | 1         | 0.39%   |
| Vulcan Electronics  | 1         | 0.39%   |
| UMAX                | 1         | 0.39%   |
| TUXEDO              | 1         | 0.39%   |
| SANTECH             | 1         | 0.39%   |
| Pixus               | 1         | 0.39%   |
| Panasonic           | 1         | 0.39%   |
| Packard Bell        | 1         | 0.39%   |
| Irbis               | 1         | 0.39%   |
| Intel               | 1         | 0.39%   |
| Framework           | 1         | 0.39%   |
| eMachines           | 1         | 0.39%   |
| efirstview          | 1         | 0.39%   |
| Chuwi               | 1         | 0.39%   |
| AMI                 | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 4         | 1.56%   |
| HP Stream Laptop 14-cb0XX           | 2         | 0.78%   |
| HP ProBook 650 G1                   | 2         | 0.78%   |
| ASUS X200CA                         | 2         | 0.78%   |
| Apple MacBookAir7,2                 | 2         | 0.78%   |
| win element MoreFine S500+          | 1         | 0.39%   |
| Vulcan Excursion XB                 | 1         | 0.39%   |
| UMAX VisionBook-N12R                | 1         | 0.39%   |
| TUXEDO N7x0WU                       | 1         | 0.39%   |
| Toshiba Satellite P875              | 1         | 0.39%   |
| Toshiba Satellite M70               | 1         | 0.39%   |
| Toshiba Satellite L850-CJK          | 1         | 0.39%   |
| Toshiba Satellite L650              | 1         | 0.39%   |
| Toshiba Satellite C845              | 1         | 0.39%   |
| Toshiba Satellite C70-B             | 1         | 0.39%   |
| Toshiba Satellite C660              | 1         | 0.39%   |
| Toshiba Satellite C50-A-12K         | 1         | 0.39%   |
| Toshiba Satellite A300              | 1         | 0.39%   |
| Toshiba PORTEGE Z30-C               | 1         | 0.39%   |
| Toshiba PORTEGE R705                | 1         | 0.39%   |
| Sony VPCYB3V1E                      | 1         | 0.39%   |
| Sony VPCSB1V9R                      | 1         | 0.39%   |
| Sony VPCF23P1E                      | 1         | 0.39%   |
| Sony VPCF119FX                      | 1         | 0.39%   |
| Sony VPCEH2N1E                      | 1         | 0.39%   |
| Sony VPCEC3S1E                      | 1         | 0.39%   |
| Sony VGN-TZ3RXN_B                   | 1         | 0.39%   |
| Sony VGN-NR310FH                    | 1         | 0.39%   |
| Sony SVT13115FBS                    | 1         | 0.39%   |
| Sony SVE1513Q1ESI                   | 1         | 0.39%   |
| SANTECH X170KM-G                    | 1         | 0.39%   |
| Samsung R780/R778                   | 1         | 0.39%   |
| Samsung NC210/NC110                 | 1         | 0.39%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 1         | 0.39%   |
| Samsung 340XAA/350XAA/550XAA        | 1         | 0.39%   |
| Samsung 305E4A/305E5A/305E7A        | 1         | 0.39%   |
| Pixus Rise                          | 1         | 0.39%   |
| Panasonic CF-C1BT02EGE              | 1         | 0.39%   |
| Packard Bell EasyNote TE11HC        | 1         | 0.39%   |
| Notebook W65_W67RZ1                 | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 41        | 16.02%  |
| Acer Aspire          | 14        | 5.47%   |
| Dell Latitude        | 12        | 4.69%   |
| Toshiba Satellite    | 9         | 3.52%   |
| Dell Inspiron        | 8         | 3.13%   |
| HP Pavilion          | 7         | 2.73%   |
| Lenovo IdeaPad       | 6         | 2.34%   |
| HP ProBook           | 6         | 2.34%   |
| HP EliteBook         | 5         | 1.95%   |
| Dell Vostro          | 5         | 1.95%   |
| HP Laptop            | 4         | 1.56%   |
| Unknown              | 4         | 1.56%   |
| HP Compaq            | 3         | 1.17%   |
| ASUS VivoBook        | 3         | 1.17%   |
| ASUS TUF             | 3         | 1.17%   |
| Acer Swift           | 3         | 1.17%   |
| Toshiba PORTEGE      | 2         | 0.78%   |
| Lenovo B590          | 2         | 0.78%   |
| HP ZBook             | 2         | 0.78%   |
| HP Stream            | 2         | 0.78%   |
| HP 15                | 2         | 0.78%   |
| Dell Precision       | 2         | 0.78%   |
| ASUS X200CA          | 2         | 0.78%   |
| ASUS ROG             | 2         | 0.78%   |
| ASUS ASUS            | 2         | 0.78%   |
| Apple MacBookPro11   | 2         | 0.78%   |
| Apple MacBookAir7    | 2         | 0.78%   |
| Alienware m15        | 2         | 0.78%   |
| Acer Nitro           | 2         | 0.78%   |
| Acer Extensa         | 2         | 0.78%   |
| win element MoreFine | 1         | 0.39%   |
| Vulcan Excursion     | 1         | 0.39%   |
| UMAX VisionBook-N12R | 1         | 0.39%   |
| TUXEDO N7x0WU        | 1         | 0.39%   |
| Sony VPCYB3V1E       | 1         | 0.39%   |
| Sony VPCSB1V9R       | 1         | 0.39%   |
| Sony VPCF23P1E       | 1         | 0.39%   |
| Sony VPCF119FX       | 1         | 0.39%   |
| Sony VPCEH2N1E       | 1         | 0.39%   |
| Sony VPCEC3S1E       | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 26        | 10.16%  |
| 2021    | 24        | 9.38%   |
| 2018    | 24        | 9.38%   |
| 2010    | 24        | 9.38%   |
| 2012    | 21        | 8.2%    |
| 2013    | 18        | 7.03%   |
| 2016    | 16        | 6.25%   |
| 2015    | 16        | 6.25%   |
| 2019    | 15        | 5.86%   |
| 2020    | 13        | 5.08%   |
| 2014    | 13        | 5.08%   |
| 2017    | 12        | 4.69%   |
| 2008    | 10        | 3.91%   |
| 2009    | 7         | 2.73%   |
| 2007    | 6         | 2.34%   |
| 2006    | 4         | 1.56%   |
| 2022    | 3         | 1.17%   |
| 2005    | 3         | 1.17%   |
| Unknown | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 256       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 255       | 99.61%  |
| Enabled  | 1         | 0.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 252       | 98.44%  |
| Yes  | 4         | 1.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 74        | 28.79%  |
| 3.01-4.0    | 50        | 19.46%  |
| 8.01-16.0   | 46        | 17.9%   |
| 16.01-24.0  | 36        | 14.01%  |
| 1.01-2.0    | 20        | 7.78%   |
| 32.01-64.0  | 12        | 4.67%   |
| 2.01-3.0    | 10        | 3.89%   |
| 0.51-1.0    | 5         | 1.95%   |
| 24.01-32.0  | 2         | 0.78%   |
| 64.01-256.0 | 2         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 101       | 36.46%  |
| 2.01-3.0  | 65        | 23.47%  |
| 3.01-4.0  | 42        | 15.16%  |
| 0.51-1.0  | 32        | 11.55%  |
| 4.01-8.0  | 28        | 10.11%  |
| 8.01-16.0 | 6         | 2.17%   |
| 0.01-0.5  | 3         | 1.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 189       | 72.41%  |
| 2      | 54        | 20.69%  |
| 3      | 13        | 4.98%   |
| 0      | 3         | 1.15%   |
| 4      | 2         | 0.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 64.59%  |
| Yes       | 91        | 35.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 85.94%  |
| No        | 36        | 14.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 96.89%  |
| No        | 8         | 3.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 75.88%  |
| No        | 62        | 24.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 52        | 20.16%  |
| Germany     | 31        | 12.02%  |
| Italy       | 16        | 6.2%    |
| UK          | 13        | 5.04%   |
| Canada      | 11        | 4.26%   |
| Russia      | 9         | 3.49%   |
| Netherlands | 9         | 3.49%   |
| Brazil      | 8         | 3.1%    |
| Spain       | 7         | 2.71%   |
| Slovakia    | 7         | 2.71%   |
| India       | 7         | 2.71%   |
| France      | 7         | 2.71%   |
| Poland      | 6         | 2.33%   |
| Austria     | 6         | 2.33%   |
| Australia   | 5         | 1.94%   |
| Ukraine     | 4         | 1.55%   |
| Mexico      | 4         | 1.55%   |
| Thailand    | 3         | 1.16%   |
| Finland     | 3         | 1.16%   |
| Czechia     | 3         | 1.16%   |
| Belgium     | 3         | 1.16%   |
| Vietnam     | 2         | 0.78%   |
| Turkey      | 2         | 0.78%   |
| Sweden      | 2         | 0.78%   |
| Serbia      | 2         | 0.78%   |
| Romania     | 2         | 0.78%   |
| Portugal    | 2         | 0.78%   |
| Norway      | 2         | 0.78%   |
| New Zealand | 2         | 0.78%   |
| Indonesia   | 2         | 0.78%   |
| Hungary     | 2         | 0.78%   |
| Colombia    | 2         | 0.78%   |
| China       | 2         | 0.78%   |
| Bulgaria    | 2         | 0.78%   |
| Belarus     | 2         | 0.78%   |
| Venezuela   | 1         | 0.39%   |
| Uruguay     | 1         | 0.39%   |
| Syria       | 1         | 0.39%   |
| Switzerland | 1         | 0.39%   |
| Philippines | 1         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Vienna           | 6         | 2.23%   |
| Bratislava       | 6         | 2.23%   |
| Berlin           | 4         | 1.49%   |
| St Petersburg    | 3         | 1.12%   |
| Rome             | 3         | 1.12%   |
| Munich           | 3         | 1.12%   |
| Montreal         | 3         | 1.12%   |
| Los Angeles      | 3         | 1.12%   |
| Amsterdam        | 3         | 1.12%   |
| Warsaw           | 2         | 0.74%   |
| Walled Lake      | 2         | 0.74%   |
| Prague           | 2         | 0.74%   |
| Patna            | 2         | 0.74%   |
| Oxford           | 2         | 0.74%   |
| Orange           | 2         | 0.74%   |
| New York         | 2         | 0.74%   |
| Moscow           | 2         | 0.74%   |
| Minsk            | 2         | 0.74%   |
| Madrid           | 2         | 0.74%   |
| Istanbul         | 2         | 0.74%   |
| Ho Chi Minh City | 2         | 0.74%   |
| Florence         | 2         | 0.74%   |
| Doesburg         | 2         | 0.74%   |
| Dnipro           | 2         | 0.74%   |
| Casale Litta     | 2         | 0.74%   |
| Canberra         | 2         | 0.74%   |
| Cambridge        | 2         | 0.74%   |
| Calgary          | 2         | 0.74%   |
| Buffalo          | 2         | 0.74%   |
| Budapest         | 2         | 0.74%   |
| Bogotá          | 2         | 0.74%   |
| Zurich           | 1         | 0.37%   |
| Xalapa           | 1         | 0.37%   |
| Wermelskirchen   | 1         | 0.37%   |
| Wentzville       | 1         | 0.37%   |
| Waycross         | 1         | 0.37%   |
| Vasco da Gama    | 1         | 0.37%   |
| Vancouver        | 1         | 0.37%   |
| Valencia         | 1         | 0.37%   |
| Uelzen           | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 58     | 13.07%  |
| WDC                 | 38        | 39     | 11.55%  |
| Seagate             | 30        | 33     | 9.12%   |
| Kingston            | 25        | 26     | 7.6%    |
| Toshiba             | 23        | 24     | 6.99%   |
| Crucial             | 21        | 35     | 6.38%   |
| Unknown             | 20        | 25     | 6.08%   |
| SanDisk             | 15        | 17     | 4.56%   |
| SK hynix            | 13        | 14     | 3.95%   |
| Hitachi             | 13        | 14     | 3.95%   |
| Intel               | 11        | 16     | 3.34%   |
| HGST                | 8         | 13     | 2.43%   |
| Apple               | 6         | 9      | 1.82%   |
| PNY                 | 5         | 5      | 1.52%   |
| Micron Technology   | 5         | 9      | 1.52%   |
| Transcend           | 4         | 4      | 1.22%   |
| SPCC                | 4         | 4      | 1.22%   |
| Phison              | 3         | 4      | 0.91%   |
| LITEON              | 3         | 3      | 0.91%   |
| Dogfish             | 3         | 3      | 0.91%   |
| A-DATA Technology   | 3         | 5      | 0.91%   |
| Team                | 2         | 2      | 0.61%   |
| Netac               | 2         | 2      | 0.61%   |
| KingSpec            | 2         | 2      | 0.61%   |
| KingDian            | 2         | 2      | 0.61%   |
| Indilinx            | 2         | 4      | 0.61%   |
| Fujitsu             | 2         | 2      | 0.61%   |
| Corsair             | 2         | 2      | 0.61%   |
| Unknown             | 2         | 2      | 0.61%   |
| ZTC                 | 1         | 1      | 0.3%    |
| Yeyian              | 1         | 1      | 0.3%    |
| Smart               | 1         | 1      | 0.3%    |
| SABRENT             | 1         | 1      | 0.3%    |
| Phison Electronics  | 1         | 2      | 0.3%    |
| Patriot             | 1         | 1      | 0.3%    |
| OCZ                 | 1         | 1      | 0.3%    |
| LITEONIT            | 1         | 1      | 0.3%    |
| Lexar               | 1         | 1      | 0.3%    |
| Lenovo              | 1         | 1      | 0.3%    |
| KIOXIA              | 1         | 2      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 1.76%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.76%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.17%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 1.17%   |
| Crucial CT120BX500SSD1 120GB         | 4         | 1.17%   |
| Unknown SD32G  32GB                  | 3         | 0.88%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.88%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 0.88%   |
| Samsung SSD 980 PRO 1TB              | 3         | 0.88%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.88%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 0.88%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 0.88%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.88%   |
| Intel SSDPEKNW512G8 512GB            | 3         | 0.88%   |
| HGST HTS541010A9E680 1TB             | 3         | 0.88%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 0.59%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.59%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.59%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.59%   |
| Unknown BJTD4R  32GB                 | 2         | 0.59%   |
| Toshiba MQ01ABD075 752GB             | 2         | 0.59%   |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 0.59%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 2         | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.59%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.59%   |
| Samsung SSD 860 250GB                | 2         | 0.59%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 2         | 0.59%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.59%   |
| Kingston SA400M8240G 240GB SSD       | 2         | 0.59%   |
| Kingston OM8PCP3512F-AI1 512GB       | 2         | 0.59%   |
| Intel SSDSA2BW120G3H 120GB           | 2         | 0.59%   |
| Indilinx IND-S325S120G 120GB SSD     | 2         | 0.59%   |
| Hitachi HTS54503 320GB               | 2         | 0.59%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.59%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.59%   |
| Dogfish SSD 128GB                    | 2         | 0.59%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.59%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.59%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 33     | 31.25%  |
| WDC                 | 26        | 26     | 27.08%  |
| Toshiba             | 13        | 14     | 13.54%  |
| Hitachi             | 13        | 14     | 13.54%  |
| HGST                | 8         | 13     | 8.33%   |
| Samsung Electronics | 3         | 4      | 3.13%   |
| Fujitsu             | 2         | 2      | 2.08%   |
| SABRENT             | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 33     | 17.24%  |
| Crucial             | 20        | 33     | 13.79%  |
| Kingston            | 19        | 19     | 13.1%   |
| SanDisk             | 14        | 16     | 9.66%   |
| PNY                 | 5         | 5      | 3.45%   |
| Apple               | 5         | 8      | 3.45%   |
| Transcend           | 4         | 4      | 2.76%   |
| Toshiba             | 4         | 4      | 2.76%   |
| SPCC                | 4         | 4      | 2.76%   |
| SK hynix            | 4         | 4      | 2.76%   |
| WDC                 | 3         | 3      | 2.07%   |
| Micron Technology   | 3         | 7      | 2.07%   |
| LITEON              | 3         | 3      | 2.07%   |
| Intel               | 3         | 6      | 2.07%   |
| Dogfish             | 3         | 3      | 2.07%   |
| A-DATA Technology   | 3         | 5      | 2.07%   |
| Netac               | 2         | 2      | 1.38%   |
| KingSpec            | 2         | 2      | 1.38%   |
| KingDian            | 2         | 2      | 1.38%   |
| Indilinx            | 2         | 4      | 1.38%   |
| Corsair             | 2         | 2      | 1.38%   |
| ZTC                 | 1         | 1      | 0.69%   |
| Yeyian              | 1         | 1      | 0.69%   |
| Team                | 1         | 1      | 0.69%   |
| Smart               | 1         | 1      | 0.69%   |
| Phison              | 1         | 1      | 0.69%   |
| Patriot             | 1         | 1      | 0.69%   |
| OCZ                 | 1         | 1      | 0.69%   |
| LITEONIT            | 1         | 1      | 0.69%   |
| KingFast            | 1         | 1      | 0.69%   |
| Intenso             | 1         | 1      | 0.69%   |
| GOODRAM             | 1         | 1      | 0.69%   |
| Gigabyte Technology | 1         | 1      | 0.69%   |
| GeIL                | 1         | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 127       | 182    | 41.5%   |
| HDD     | 95        | 107    | 31.05%  |
| NVMe    | 59        | 78     | 19.28%  |
| MMC     | 24        | 29     | 7.84%   |
| Unknown | 1         | 1      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 191       | 287    | 68.95%  |
| NVMe | 59        | 78     | 21.3%   |
| MMC  | 24        | 29     | 8.66%   |
| SAS  | 3         | 3      | 1.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 215    | 74.88%  |
| 0.51-1.0   | 49        | 69     | 22.79%  |
| 1.01-2.0   | 3         | 3      | 1.4%    |
| 3.01-4.0   | 2         | 2      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 32.21%  |
| 251-500        | 50        | 18.73%  |
| 501-1000       | 36        | 13.48%  |
| 51-100         | 35        | 13.11%  |
| 21-50          | 24        | 8.99%   |
| 1-20           | 17        | 6.37%   |
| 1001-2000      | 11        | 4.12%   |
| More than 3000 | 3         | 1.12%   |
| 2001-3000      | 3         | 1.12%   |
| Unknown        | 2         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 116       | 42.34%  |
| 21-50          | 42        | 15.33%  |
| 51-100         | 39        | 14.23%  |
| 101-250        | 34        | 12.41%  |
| 251-500        | 23        | 8.39%   |
| 501-1000       | 11        | 4.01%   |
| 1001-2000      | 5         | 1.82%   |
| More than 3000 | 2         | 0.73%   |
| Unknown        | 2         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 3         | 3      | 6.98%   |
| Indilinx IND-S325S120G 120GB SSD             | 2         | 4      | 4.65%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.33%   |
| WDC WD5000BPVT-60HXZT3 500GB                 | 1         | 1      | 2.33%   |
| WDC WD3200LPVX-22V0TT0 320GB                 | 1         | 1      | 2.33%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 2.33%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 1      | 2.33%   |
| WDC WD1600BEVT-22ZCT0 160GB                  | 1         | 1      | 2.33%   |
| WDC WD1600BEVT-22A23T0 160GB                 | 1         | 1      | 2.33%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 2.33%   |
| Toshiba MK7575GSX 752GB                      | 1         | 2      | 2.33%   |
| Toshiba MK5059GSXP 500GB                     | 1         | 1      | 2.33%   |
| Toshiba MK2565GSX 250GB                      | 1         | 1      | 2.33%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.33%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 2.33%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 2.33%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 2.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 2.33%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 2.33%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD          | 1         | 1      | 2.33%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.33%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 2.33%   |
| Samsung Electronics HS122JC 120GB            | 1         | 2      | 2.33%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 2.33%   |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 2.33%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 2.33%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 2.33%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 2.33%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 2.33%   |
| Hitachi HTS543216L9SA02 160GB                | 1         | 1      | 2.33%   |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 2.33%   |
| Hitachi HTS542516K9SA00 160GB                | 1         | 1      | 2.33%   |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 2.33%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 2.33%   |
| HGST HTS545032A7E380 320GB                   | 1         | 1      | 2.33%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 2.33%   |
| Fujitsu MHZ2160BH G2 160GB                   | 1         | 1      | 2.33%   |
| Crucial CT512M550SSD1 512GB                  | 1         | 1      | 2.33%   |
| Crucial CT1000MX500SSD4 1TB                  | 1         | 2      | 2.33%   |
| A-DATA Technology SU650 240GB SSD            | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 20.93%  |
| WDC                 | 7         | 7      | 16.28%  |
| Hitachi             | 7         | 7      | 16.28%  |
| Toshiba             | 4         | 5      | 9.3%    |
| Samsung Electronics | 3         | 4      | 6.98%   |
| HGST                | 3         | 4      | 6.98%   |
| Kingston            | 2         | 2      | 4.65%   |
| Indilinx            | 2         | 4      | 4.65%   |
| Crucial             | 2         | 3      | 4.65%   |
| SanDisk             | 1         | 1      | 2.33%   |
| Intel               | 1         | 2      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 29.03%  |
| WDC                 | 7         | 7      | 22.58%  |
| Hitachi             | 7         | 7      | 22.58%  |
| Toshiba             | 3         | 4      | 9.68%   |
| HGST                | 3         | 4      | 9.68%   |
| Samsung Electronics | 1         | 2      | 3.23%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 34     | 72.09%  |
| SSD  | 11        | 14     | 25.58%  |
| NVMe | 1         | 2      | 2.33%   |

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
| Works    | 206       | 312    | 73.84%  |
| Malfunc  | 42        | 50     | 15.05%  |
| Detected | 31        | 35     | 11.11%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 187       | 66.55%  |
| AMD                          | 26        | 9.25%   |
| Samsung Electronics          | 20        | 7.12%   |
| SanDisk                      | 10        | 3.56%   |
| SK hynix                     | 8         | 2.85%   |
| Nvidia                       | 6         | 2.14%   |
| Kingston Technology Company  | 6         | 2.14%   |
| Phison Electronics           | 4         | 1.42%   |
| KIOXIA                       | 4         | 1.42%   |
| Toshiba America Info Systems | 3         | 1.07%   |
| Micron Technology            | 2         | 0.71%   |
| Silicon Motion               | 1         | 0.36%   |
| Silicon Image                | 1         | 0.36%   |
| Micron/Crucial Technology    | 1         | 0.36%   |
| Marvell Technology Group     | 1         | 0.36%   |
| Lenovo                       | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 25        | 8.28%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 7.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 18        | 5.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 4.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 2.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 2.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 1.99%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.66%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 1.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.32%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.32%   |
| Intel SSD 660P Series                                                            | 4         | 1.32%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.32%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 3         | 0.99%   |
| SK hynix BC511                                                                   | 3         | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.99%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 0.99%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.99%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.66%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.66%   |
| Samsung Electronics SATA controller                                              | 2         | 0.66%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.66%   |
| Nvidia MCP67 AHCI Controller                                                     | 2         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 189       | 65.4%   |
| NVMe | 59        | 20.42%  |
| IDE  | 23        | 7.96%   |
| RAID | 18        | 6.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 217       | 84.77%  |
| AMD    | 39        | 15.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz       | 6         | 2.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 1.95%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 1.95%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 5         | 1.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 1.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 4         | 1.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 1.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 1.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.17%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.17%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 3         | 1.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 1.17%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 3         | 1.17%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 1.17%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 3         | 1.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 0.78%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz      | 2         | 0.78%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.78%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.78%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.78%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.78%   |
| Intel Core i7 CPU M 620 @ 2.67GHz       | 2         | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 0.78%   |
| Intel Core i5-5350U CPU @ 1.80GHz       | 2         | 0.78%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 2         | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.78%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 60        | 23.44%  |
| Intel Core i5           | 58        | 22.66%  |
| Intel Celeron           | 26        | 10.16%  |
| Intel Core i3           | 21        | 8.2%    |
| Other                   | 13        | 5.08%   |
| Intel Core 2 Duo        | 13        | 5.08%   |
| Intel Atom              | 13        | 5.08%   |
| AMD Ryzen 7             | 11        | 4.3%    |
| Intel Pentium           | 4         | 1.56%   |
| AMD Ryzen 5             | 4         | 1.56%   |
| AMD Turion 64 X2 Mobile | 3         | 1.17%   |
| AMD Ryzen 3             | 3         | 1.17%   |
| AMD E                   | 3         | 1.17%   |
| AMD A8                  | 3         | 1.17%   |
| AMD A6                  | 3         | 1.17%   |
| Intel Pentium M         | 2         | 0.78%   |
| Intel Core 2            | 2         | 0.78%   |
| AMD Ryzen 9             | 2         | 0.78%   |
| AMD E1                  | 2         | 0.78%   |
| AMD A4                  | 2         | 0.78%   |
| Intel Pentium Silver    | 1         | 0.39%   |
| Intel Pentium Dual-Core | 1         | 0.39%   |
| Intel Genuine           | 1         | 0.39%   |
| Intel Core Duo          | 1         | 0.39%   |
| Intel Celeron M         | 1         | 0.39%   |
| AMD Sempron             | 1         | 0.39%   |
| AMD Athlon 64 X2        | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 147       | 57.42%  |
| 4      | 71        | 27.73%  |
| 8      | 13        | 5.08%   |
| 6      | 12        | 4.69%   |
| 1      | 11        | 4.3%    |
| 14     | 2         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 256       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 178       | 69.53%  |
| 1      | 78        | 30.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 246       | 95.72%  |
| 32-bit         | 11        | 4.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 12.26%  |
| 0x206a7    | 21        | 8.05%   |
| 0x306a9    | 19        | 7.28%   |
| 0x406e3    | 13        | 4.98%   |
| 0x20655    | 10        | 3.83%   |
| 0x906ea    | 8         | 3.07%   |
| 0x806c1    | 8         | 3.07%   |
| 0x40651    | 8         | 3.07%   |
| 0x306c3    | 8         | 3.07%   |
| 0x806ea    | 7         | 2.68%   |
| 0x306d4    | 7         | 2.68%   |
| 0x1067a    | 6         | 2.3%    |
| 0x806e9    | 5         | 1.92%   |
| 0x406c4    | 5         | 1.92%   |
| 0x30678    | 5         | 1.92%   |
| 0x20652    | 5         | 1.92%   |
| 0x0a50000c | 5         | 1.92%   |
| 0x806ec    | 4         | 1.53%   |
| 0x706a8    | 4         | 1.53%   |
| 0x706a1    | 4         | 1.53%   |
| 0x506e3    | 4         | 1.53%   |
| 0x106c2    | 4         | 1.53%   |
| 0x08608103 | 4         | 1.53%   |
| 0xa0652    | 3         | 1.15%   |
| 0x906e9    | 3         | 1.15%   |
| 0x6fd      | 3         | 1.15%   |
| 0x106ca    | 3         | 1.15%   |
| 0x10676    | 3         | 1.15%   |
| 0x03000027 | 3         | 1.15%   |
| 0x906ed    | 2         | 0.77%   |
| 0x906a3    | 2         | 0.77%   |
| 0x706e5    | 2         | 0.77%   |
| 0x6d8      | 2         | 0.77%   |
| 0x506c9    | 2         | 0.77%   |
| 0x30661    | 2         | 0.77%   |
| 0x106e5    | 2         | 0.77%   |
| 0x08108102 | 2         | 0.77%   |
| 0x0810100b | 2         | 0.77%   |
| 0x07030105 | 2         | 0.77%   |
| 0x0700010f | 2         | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 34        | 13.28%  |
| SandyBridge      | 26        | 10.16%  |
| IvyBridge        | 22        | 8.59%   |
| Skylake          | 18        | 7.03%   |
| Haswell          | 17        | 6.64%   |
| Westmere         | 16        | 6.25%   |
| Silvermont       | 13        | 5.08%   |
| Penryn           | 10        | 3.91%   |
| TigerLake        | 9         | 3.52%   |
| Bonnell          | 9         | 3.52%   |
| Goldmont plus    | 8         | 3.13%   |
| Core             | 7         | 2.73%   |
| Broadwell        | 7         | 2.73%   |
| Zen 3            | 6         | 2.34%   |
| Unknown          | 6         | 2.34%   |
| P6               | 5         | 1.95%   |
| IceLake          | 5         | 1.95%   |
| Zen+             | 4         | 1.56%   |
| Puma             | 4         | 1.56%   |
| K8 Hammer        | 4         | 1.56%   |
| Zen              | 3         | 1.17%   |
| K10 Llano        | 3         | 1.17%   |
| Goldmont         | 3         | 1.17%   |
| CometLake        | 3         | 1.17%   |
| Bobcat           | 3         | 1.17%   |
| Zen 2            | 2         | 0.78%   |
| Nehalem          | 2         | 0.78%   |
| Jaguar           | 2         | 0.78%   |
| Excavator        | 2         | 0.78%   |
| Tremont          | 1         | 0.39%   |
| K8 & K10 hybrid  | 1         | 0.39%   |
| Alderlake Hybrid | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 194       | 62.18%  |
| Nvidia | 63        | 20.19%  |
| AMD    | 55        | 17.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 6.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 21        | 6.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 3.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.74%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 2.13%   |
| Intel HD Graphics 620                                                                    | 7         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.52%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.52%   |
| Intel HD Graphics 530                                                                    | 5         | 1.52%   |
| AMD Lucienne                                                                             | 5         | 1.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.22%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.22%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.22%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.91%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.91%   |
| Intel HD Graphics 500                                                                    | 3         | 0.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.91%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.91%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.91%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.91%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 0.91%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.61%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.61%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.61%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 2         | 0.61%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 142       | 55.47%  |
| Intel + Nvidia | 41        | 16.02%  |
| 1 x AMD        | 34        | 13.28%  |
| 1 x Nvidia     | 17        | 6.64%   |
| Intel + AMD    | 10        | 3.91%   |
| 2 x AMD        | 7         | 2.73%   |
| AMD + Nvidia   | 4         | 1.56%   |
| 2 x Intel      | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 235       | 90.04%  |
| Proprietary | 18        | 6.9%    |
| Unknown     | 8         | 3.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 74.9%   |
| 0.01-0.5   | 30        | 11.58%  |
| 0.51-1.0   | 15        | 5.79%   |
| 1.01-2.0   | 13        | 5.02%   |
| 7.01-8.0   | 3         | 1.16%   |
| 3.01-4.0   | 3         | 1.16%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 19.71%  |
| LG Display              | 36        | 12.9%   |
| Chimei Innolux          | 36        | 12.9%   |
| Samsung Electronics     | 30        | 10.75%  |
| BOE                     | 28        | 10.04%  |
| Lenovo                  | 14        | 5.02%   |
| Chi Mei Optoelectronics | 13        | 4.66%   |
| Apple                   | 8         | 2.87%   |
| PANDA                   | 7         | 2.51%   |
| Hewlett-Packard         | 7         | 2.51%   |
| Goldstar                | 5         | 1.79%   |
| Sharp                   | 4         | 1.43%   |
| LG Philips              | 4         | 1.43%   |
| InfoVision              | 4         | 1.43%   |
| HannStar                | 4         | 1.43%   |
| Dell                    | 4         | 1.43%   |
| CPT                     | 3         | 1.08%   |
| Ancor Communications    | 3         | 1.08%   |
| Sony                    | 2         | 0.72%   |
| Philips                 | 2         | 0.72%   |
| Vizio                   | 1         | 0.36%   |
| Sunplus                 | 1         | 0.36%   |
| STA                     | 1         | 0.36%   |
| Panasonic               | 1         | 0.36%   |
| Packard Bell            | 1         | 0.36%   |
| LTM                     | 1         | 0.36%   |
| InnoLux Display         | 1         | 0.36%   |
| Eizo                    | 1         | 0.36%   |
| AOC                     | 1         | 0.36%   |
| Acer                    | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 1.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 1.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.08%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.72%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.72%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.72%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 2         | 0.72%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.72%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 0.72%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 2         | 0.72%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.72%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                    | 2         | 0.72%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 2         | 0.72%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                    | 2         | 0.72%   |
| BOE LCD Monitor BOE05DF 1366x768 293x165mm 13.2-inch                     | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 220x130mm 10.1-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch           | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 380x210mm 17.1-inch           | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO01EE 1600x900 344x193mm 15.5-inch            | 2         | 0.72%   |
| Vizio E320VA VIZ0071 1360x768 697x392mm 31.5-inch                        | 1         | 0.36%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.36%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 105       | 39.18%  |
| 1366x768 (WXGA)    | 88        | 32.84%  |
| 1600x900 (HD+)     | 14        | 5.22%   |
| 1280x800 (WXGA)    | 13        | 4.85%   |
| 3840x2160 (4K)     | 9         | 3.36%   |
| 1024x600           | 7         | 2.61%   |
| 1440x900 (WXGA+)   | 5         | 1.87%   |
| 1680x1050 (WSXGA+) | 4         | 1.49%   |
| 2880x1800          | 3         | 1.12%   |
| 2560x1440 (QHD)    | 3         | 1.12%   |
| 2560x1080          | 3         | 1.12%   |
| 1920x1200 (WUXGA)  | 3         | 1.12%   |
| 1280x1024 (SXGA)   | 3         | 1.12%   |
| 1400x1050          | 2         | 0.75%   |
| 3840x2400          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 2256x1504          | 1         | 0.37%   |
| 2160x1440          | 1         | 0.37%   |
| 1360x768           | 1         | 0.37%   |
| 1024x768 (XGA)     | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 117       | 42.09%  |
| 13      | 36        | 12.95%  |
| 14      | 32        | 11.51%  |
| 17      | 21        | 7.55%   |
| 24      | 10        | 3.6%    |
| 11      | 10        | 3.6%    |
| 10      | 8         | 2.88%   |
| 12      | 7         | 2.52%   |
| 23      | 6         | 2.16%   |
| 19      | 4         | 1.44%   |
| 34      | 3         | 1.08%   |
| 27      | 3         | 1.08%   |
| 21      | 3         | 1.08%   |
| 20      | 3         | 1.08%   |
| 40      | 2         | 0.72%   |
| 32      | 2         | 0.72%   |
| 18      | 2         | 0.72%   |
| 16      | 2         | 0.72%   |
| 84      | 1         | 0.36%   |
| 46      | 1         | 0.36%   |
| 43      | 1         | 0.36%   |
| 37      | 1         | 0.36%   |
| 26      | 1         | 0.36%   |
| 25      | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 163       | 58.84%  |
| 201-300     | 42        | 15.16%  |
| 351-400     | 31        | 11.19%  |
| 501-600     | 20        | 7.22%   |
| 401-500     | 9         | 3.25%   |
| 701-800     | 5         | 1.81%   |
| 801-900     | 3         | 1.08%   |
| 1501-2000   | 1         | 0.36%   |
| 1001-1500   | 1         | 0.36%   |
| 901-1000    | 1         | 0.36%   |
| Unknown     | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 209       | 82.61%  |
| 16/10 | 31        | 12.25%  |
| 3/2   | 4         | 1.58%   |
| 5/4   | 3         | 1.19%   |
| 4/3   | 3         | 1.19%   |
| 21/9  | 3         | 1.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 118       | 42.45%  |
| 81-90          | 57        | 20.5%   |
| 121-130        | 20        | 7.19%   |
| 201-250        | 15        | 5.4%    |
| 71-80          | 11        | 3.96%   |
| 51-60          | 10        | 3.6%    |
| 41-50          | 8         | 2.88%   |
| 151-200        | 8         | 2.88%   |
| 61-70          | 7         | 2.52%   |
| 351-500        | 5         | 1.8%    |
| 251-300        | 5         | 1.8%    |
| 501-1000       | 5         | 1.8%    |
| 301-350        | 3         | 1.08%   |
| 141-150        | 2         | 0.72%   |
| More than 1000 | 1         | 0.36%   |
| 131-140        | 1         | 0.36%   |
| 111-120        | 1         | 0.36%   |
| Unknown        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 38.24%  |
| 101-120       | 88        | 32.35%  |
| 51-100        | 57        | 20.96%  |
| 161-240       | 14        | 5.15%   |
| More than 240 | 6         | 2.21%   |
| 1-50          | 2         | 0.74%   |
| Unknown       | 1         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 211       | 81.15%  |
| 2     | 39        | 15%     |
| 0     | 7         | 2.69%   |
| 3     | 3         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 136       | 32.54%  |
| Realtek Semiconductor             | 129       | 30.86%  |
| Qualcomm Atheros                  | 67        | 16.03%  |
| Broadcom                          | 26        | 6.22%   |
| MediaTek                          | 7         | 1.67%   |
| Marvell Technology Group          | 7         | 1.67%   |
| Broadcom Limited                  | 7         | 1.67%   |
| TP-Link                           | 5         | 1.2%    |
| Nvidia                            | 5         | 1.2%    |
| Sierra Wireless                   | 4         | 0.96%   |
| Ralink                            | 3         | 0.72%   |
| Huawei Technologies               | 3         | 0.72%   |
| Ericsson Business Mobile Networks | 3         | 0.72%   |
| Ralink Technology                 | 2         | 0.48%   |
| Attansic Technology               | 2         | 0.48%   |
| ASIX Electronics                  | 2         | 0.48%   |
| Samsung Electronics               | 1         | 0.24%   |
| Qualcomm Atheros Communications   | 1         | 0.24%   |
| Qualcomm                          | 1         | 0.24%   |
| NetGear                           | 1         | 0.24%   |
| Lenovo                            | 1         | 0.24%   |
| JMicron Technology                | 1         | 0.24%   |
| Hewlett-Packard                   | 1         | 0.24%   |
| Google                            | 1         | 0.24%   |
| Dell                              | 1         | 0.24%   |
| ASUSTek Computer                  | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 81        | 15.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 22        | 4.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 3.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 2.16%   |
| Intel Wireless 7260                                                     | 11        | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 10        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 9         | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.57%   |
| Intel Wireless 8260                                                     | 8         | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.57%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 1.57%   |
| Intel Wireless 3165                                                     | 7         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.37%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.98%   |
| Intel Wireless 7265                                                     | 5         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.98%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.78%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.78%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 130       | 48.15%  |
| Qualcomm Atheros                | 52        | 19.26%  |
| Realtek Semiconductor           | 41        | 15.19%  |
| Broadcom                        | 19        | 7.04%   |
| MediaTek                        | 6         | 2.22%   |
| Broadcom Limited                | 5         | 1.85%   |
| TP-Link                         | 4         | 1.48%   |
| Sierra Wireless                 | 4         | 1.48%   |
| Ralink                          | 3         | 1.11%   |
| Ralink Technology               | 2         | 0.74%   |
| Qualcomm Atheros Communications | 1         | 0.37%   |
| NetGear                         | 1         | 0.37%   |
| Hewlett-Packard                 | 1         | 0.37%   |
| ASUSTek Computer                | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 16        | 5.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 4.06%   |
| Intel Wireless 7260                                                     | 11        | 4.06%   |
| Intel Wireless 8265 / 8275                                              | 10        | 3.69%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 3.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.95%   |
| Intel Wireless 8260                                                     | 8         | 2.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.95%   |
| Intel Wireless 3165                                                     | 7         | 2.58%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.58%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.85%   |
| Intel Wireless 7265                                                     | 5         | 1.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.48%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.11%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.11%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.11%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.74%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.74%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 114       | 50%     |
| Intel                    | 56        | 24.56%  |
| Qualcomm Atheros         | 24        | 10.53%  |
| Broadcom                 | 9         | 3.95%   |
| Marvell Technology Group | 7         | 3.07%   |
| Nvidia                   | 5         | 2.19%   |
| Broadcom Limited         | 2         | 0.88%   |
| Attansic Technology      | 2         | 0.88%   |
| ASIX Electronics         | 2         | 0.88%   |
| TP-Link                  | 1         | 0.44%   |
| Samsung Electronics      | 1         | 0.44%   |
| Qualcomm                 | 1         | 0.44%   |
| MediaTek                 | 1         | 0.44%   |
| Lenovo                   | 1         | 0.44%   |
| JMicron Technology       | 1         | 0.44%   |
| Huawei Technologies      | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 81        | 35.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 9.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 4.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 3.9%    |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 3.46%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.73%   |
| Intel Ethernet Connection I219-V                                               | 4         | 1.73%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.73%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.3%    |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.3%    |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 1.3%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.87%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.87%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.87%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.87%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.87%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.87%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.87%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.87%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.87%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.43%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.43%   |
| Qualcomm FP3                                                                   | 1         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 249       | 52.31%  |
| Ethernet | 219       | 46.01%  |
| Modem    | 7         | 1.47%   |
| Unknown  | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 76.6%   |
| Ethernet | 61        | 23.02%  |
| Unknown  | 1         | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 205       | 79.77%  |
| 1     | 45        | 17.51%  |
| 0     | 6         | 2.33%   |
| 3     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 212       | 81.85%  |
| Yes  | 47        | 18.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 44.5%   |
| Qualcomm Atheros Communications | 19        | 9.5%    |
| Broadcom                        | 19        | 9.5%    |
| Realtek Semiconductor           | 17        | 8.5%    |
| Lite-On Technology              | 8         | 4%      |
| IMC Networks                    | 8         | 4%      |
| Cambridge Silicon Radio         | 8         | 4%      |
| Apple                           | 8         | 4%      |
| Hewlett-Packard                 | 6         | 3%      |
| Foxconn / Hon Hai               | 6         | 3%      |
| Toshiba                         | 3         | 1.5%    |
| Dell                            | 3         | 1.5%    |
| Ralink                          | 2         | 1%      |
| Alps Electric                   | 2         | 1%      |
| MediaTek                        | 1         | 0.5%    |
| ASUSTek Computer                | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 41        | 20.5%   |
| Intel Bluetooth Device                                                              | 14        | 7%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 6%      |
| Realtek Bluetooth Radio                                                             | 10        | 5%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 5%      |
| Intel AX200 Bluetooth                                                               | 10        | 5%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 4%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 3%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.5%    |
| Apple Bluetooth Host Controller                                                     | 5         | 2.5%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2%      |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 2%      |
| IMC Networks Bluetooth Radio                                                        | 4         | 2%      |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 2%      |
| Lite-On Bluetooth Device                                                            | 3         | 1.5%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.5%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 1.5%    |
| Ralink RT3290 Bluetooth                                                             | 2         | 1%      |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1%      |
| Lite-On Wireless_Device                                                             | 2         | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1%      |
| Intel AX210 Bluetooth                                                               | 2         | 1%      |
| IMC Networks Wireless_Device                                                        | 2         | 1%      |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1%      |
| Dell DW375 Bluetooth Module                                                         | 2         | 1%      |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1%      |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1%      |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.5%    |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.5%    |
| Toshiba BCM43142A0                                                                  | 1         | 0.5%    |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.5%    |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.5%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.5%    |
| MediaTek Wireless_Device                                                            | 1         | 0.5%    |
| Lite-On Bluetooth Radio                                                             | 1         | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.5%    |
| IMC Networks Bluetooth Device                                                       | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 211       | 67.2%   |
| Nvidia                  | 44        | 14.01%  |
| AMD                     | 44        | 14.01%  |
| Realtek Semiconductor   | 2         | 0.64%   |
| GN Netcom               | 2         | 0.64%   |
| C-Media Electronics     | 2         | 0.64%   |
| Texas Instruments       | 1         | 0.32%   |
| SteelSeries ApS         | 1         | 0.32%   |
| Plantronics             | 1         | 0.32%   |
| Mark of the Unicorn     | 1         | 0.32%   |
| Logitech                | 1         | 0.32%   |
| Lenovo                  | 1         | 0.32%   |
| FIFINE 683 Microphone   | 1         | 0.32%   |
| CMX Systems             | 1         | 0.32%   |
| BEHRINGER International | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 7.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 7.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 5.41%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 18        | 4.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 3.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 3.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.7%    |
| AMD FCH Azalia Controller                                                                         | 10        | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.16%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.35%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.08%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Nvidia Audio device                                                                               | 3         | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.81%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.81%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 75        | 24.12%  |
| SK hynix            | 68        | 21.86%  |
| Unknown             | 33        | 10.61%  |
| Micron Technology   | 32        | 10.29%  |
| Kingston            | 32        | 10.29%  |
| Crucial             | 15        | 4.82%   |
| Ramaxel Technology  | 8         | 2.57%   |
| Unknown (ABCD)      | 6         | 1.93%   |
| Elpida              | 6         | 1.93%   |
| A-DATA Technology   | 6         | 1.93%   |
| Smart               | 4         | 1.29%   |
| Corsair             | 4         | 1.29%   |
| Transcend           | 3         | 0.96%   |
| Nanya Technology    | 3         | 0.96%   |
| Teikon              | 2         | 0.64%   |
| Team                | 2         | 0.64%   |
| Unknown             | 2         | 0.64%   |
| Unknown (F301)      | 1         | 0.32%   |
| TRS STAR            | 1         | 0.32%   |
| PNY                 | 1         | 0.32%   |
| Patriot             | 1         | 0.32%   |
| Innodisk            | 1         | 0.32%   |
| High Bridge         | 1         | 0.32%   |
| Avant               | 1         | 0.32%   |
| ASint Technology    | 1         | 0.32%   |
| Apacer              | 1         | 0.32%   |
| 48spaces            | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 1.19%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.19%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.19%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 1.19%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.19%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.19%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 1.19%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 4         | 1.19%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.89%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 0.89%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.89%   |
| Samsung RAM M471B5273BH1-CF8 4GB SODIMM DDR3 1067MT/s            | 3         | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.89%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.89%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.89%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 0.59%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.59%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.59%   |
| SK hynix RAM HMT851S6AMR6A-PB 4096MB Chip DDR3 1600MT/s          | 2         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.59%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.59%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.59%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.59%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 128       | 49.61%  |
| DDR4    | 84        | 32.56%  |
| DDR2    | 17        | 6.59%   |
| LPDDR4  | 11        | 4.26%   |
| DDR     | 6         | 2.33%   |
| SDRAM   | 4         | 1.55%   |
| LPDDR3  | 3         | 1.16%   |
| DRAM    | 3         | 1.16%   |
| DDR5    | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 242       | 94.16%  |
| Row Of Chips | 9         | 3.5%    |
| Chip         | 3         | 1.17%   |
| DIMM         | 2         | 0.78%   |
| Unknown      | 1         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 110       | 38.19%  |
| 8192  | 87        | 30.21%  |
| 2048  | 50        | 17.36%  |
| 16384 | 23        | 7.99%   |
| 1024  | 15        | 5.21%   |
| 32768 | 2         | 0.69%   |
| 512   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 79        | 27.82%  |
| 2667    | 36        | 12.68%  |
| 3200    | 27        | 9.51%   |
| 1334    | 27        | 9.51%   |
| 2400    | 25        | 8.8%    |
| 1333    | 17        | 5.99%   |
| Unknown | 17        | 5.99%   |
| 667     | 12        | 4.23%   |
| 2133    | 9         | 3.17%   |
| 1067    | 9         | 3.17%   |
| 800     | 4         | 1.41%   |
| 4267    | 3         | 1.06%   |
| 4199    | 3         | 1.06%   |
| 3266    | 3         | 1.06%   |
| 1867    | 3         | 1.06%   |
| 533     | 3         | 1.06%   |
| 8400    | 2         | 0.7%    |
| 4800    | 1         | 0.35%   |
| 4266    | 1         | 0.35%   |
| 2933    | 1         | 0.35%   |
| 666     | 1         | 0.35%   |
| 166     | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 20%     |
| HP LaserJet P2055 series           | 1         | 20%     |
| HP LaserJet 1022                   | 1         | 20%     |
| Canon LiDE 400                     | 1         | 20%     |
| Brother DCP-L2540DW                | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 50%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 23.7%   |
| Acer                                   | 22        | 10.43%  |
| Realtek Semiconductor                  | 20        | 9.48%   |
| Microdia                               | 17        | 8.06%   |
| Sunplus Innovation Technology          | 14        | 6.64%   |
| IMC Networks                           | 12        | 5.69%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.69%   |
| Quanta                                 | 8         | 3.79%   |
| Lite-On Technology                     | 8         | 3.79%   |
| Lenovo                                 | 8         | 3.79%   |
| Suyin                                  | 7         | 3.32%   |
| Apple                                  | 5         | 2.37%   |
| Ricoh                                  | 4         | 1.9%    |
| Z-Star Microelectronics                | 3         | 1.42%   |
| Syntek                                 | 3         | 1.42%   |
| Silicon Motion                         | 3         | 1.42%   |
| Alcor Micro                            | 3         | 1.42%   |
| Luxvisions Innotech Limited            | 2         | 0.95%   |
| Y Media                                | 1         | 0.47%   |
| Xiongmai                               | 1         | 0.47%   |
| WaveRider Communications               | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| Primax Electronics                     | 1         | 0.47%   |
| Logitech                               | 1         | 0.47%   |
| Importek                               | 1         | 0.47%   |
| icSpring                               | 1         | 0.47%   |
| Goodong Industry                       | 1         | 0.47%   |
| Cubeternet                             | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 12        | 5.66%   |
| Microdia Integrated_Webcam_HD                               | 6         | 2.83%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 6         | 2.83%   |
| Sunplus Integrated_Webcam_HD                                | 5         | 2.36%   |
| Realtek Integrated_Webcam_HD                                | 5         | 2.36%   |
| Lite-On Integrated Camera                                   | 5         | 2.36%   |
| Lenovo Integrated Webcam [R5U877]                           | 4         | 1.89%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.89%   |
| Chicony TOSHIBA Web Camera - HD                             | 4         | 1.89%   |
| Chicony HP TrueVision HD Camera                             | 4         | 1.89%   |
| Acer BisonCam, NB Pro                                       | 4         | 1.89%   |
| Syntek EasyCamera                                           | 3         | 1.42%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 3         | 1.42%   |
| Sunplus ASUS Webcam                                         | 3         | 1.42%   |
| Realtek USB2.0 HD UVC WebCam                                | 3         | 1.42%   |
| Realtek USB Camera                                          | 3         | 1.42%   |
| Lenovo Integrated Webcam                                    | 3         | 1.42%   |
| Chicony HD User Facing                                      | 3         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 3         | 1.42%   |
| Acer Lenovo EasyCamera                                      | 3         | 1.42%   |
| Acer Integrated Camera                                      | 3         | 1.42%   |
| Acer HD Webcam                                              | 3         | 1.42%   |
| Acer BisonCam,NB Pro                                        | 3         | 1.42%   |
| Sunplus HD WebCam                                           | 2         | 0.94%   |
| Ricoh USB2.0 Camera                                         | 2         | 0.94%   |
| Realtek Integrated Webcam HD                                | 2         | 0.94%   |
| Quanta VGA WebCam                                           | 2         | 0.94%   |
| Quanta HP Wide Vision HD Camera                             | 2         | 0.94%   |
| Quanta HD User Facing                                       | 2         | 0.94%   |
| Microdia USB 2.0 Camera                                     | 2         | 0.94%   |
| Microdia Integrated Webcam                                  | 2         | 0.94%   |
| IMC Networks Integrated Camera                              | 2         | 0.94%   |
| Chicony VGA Webcam                                          | 2         | 0.94%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 0.94%   |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 0.94%   |
| Chicony HD WebCam                                           | 2         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 0.94%   |
| Apple Built-in iSight                                       | 2         | 0.94%   |
| Alcor Micro USB Camera                                      | 2         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 34.78%  |
| Synaptics                  | 9         | 19.57%  |
| Upek                       | 7         | 15.22%  |
| AuthenTec                  | 6         | 13.04%  |
| Shenzhen Goodix Technology | 4         | 8.7%    |
| LighTuning Technology      | 2         | 4.35%   |
| STMicroelectronics         | 1         | 2.17%   |
| Elan Microelectronics      | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 10.87%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 8.7%    |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 6.52%   |
| Validity Sensors Synaptics WBDI                            | 3         | 6.52%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 6.52%   |
| AuthenTec AES2810                                          | 3         | 6.52%   |
| Unknown                                                    | 3         | 6.52%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 4.35%   |
| Upek TCS5B Fingerprint sensor                              | 2         | 4.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 2         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.17%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.17%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 2.17%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.17%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.17%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.17%   |
| LighTuning Fingerprint Reader                              | 1         | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 2.17%   |
| Elan ELAN:Fingerprint                                      | 1         | 2.17%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 8         | 38.1%   |
| Broadcom              | 7         | 33.33%  |
| Lenovo                | 3         | 14.29%  |
| Advanced Card Systems | 2         | 9.52%   |
| O2 Micro              | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 38.1%   |
| Broadcom 5880                                                                | 4         | 19.05%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 9.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 4.76%   |
| Advanced Card Systems ACR122U                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 158       | 59.85%  |
| 1     | 79        | 29.92%  |
| 2     | 25        | 9.47%   |
| 3     | 2         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 51        | 38.93%  |
| Fingerprint reader       | 46        | 35.11%  |
| Chipcard                 | 18        | 13.74%  |
| Multimedia controller    | 5         | 3.82%   |
| Storage                  | 3         | 2.29%   |
| Net/wireless             | 2         | 1.53%   |
| Communication controller | 2         | 1.53%   |
| Camera                   | 2         | 1.53%   |
| Net/ethernet             | 1         | 0.76%   |
| Bluetooth                | 1         | 0.76%   |

