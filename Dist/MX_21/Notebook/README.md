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

Total: 224

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | 255 G3                      | [49dccf5753](https://linux-hardware.org/?probe=49dccf5753) | Feb 26, 2023 |
| Dell          | Inspiron 3521               | [b6321ee5a4](https://linux-hardware.org/?probe=b6321ee5a4) | Feb 25, 2023 |
| Dell          | Inspiron 3521               | [efc95d4697](https://linux-hardware.org/?probe=efc95d4697) | Feb 25, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| ASUSTek       | UX330CAK                    | [419493491e](https://linux-hardware.org/?probe=419493491e) | Feb 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [0e9172bdd5](https://linux-hardware.org/?probe=0e9172bdd5) | Feb 21, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [adc356a0a8](https://linux-hardware.org/?probe=adc356a0a8) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d09dc2494a](https://linux-hardware.org/?probe=d09dc2494a) | Feb 21, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Medion        | E1239T MD60139              | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | ProBook 445 G1              | [bcd5c952f1](https://linux-hardware.org/?probe=bcd5c952f1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [aba30bb2d8](https://linux-hardware.org/?probe=aba30bb2d8) | Feb 17, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Linx          | LINX1010B                   | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| Dell          | Inspiron 5559               | [dcb95dba09](https://linux-hardware.org/?probe=dcb95dba09) | Feb 12, 2023 |
| Insyde        | CherryTrail                 | [86103b5293](https://linux-hardware.org/?probe=86103b5293) | Feb 12, 2023 |
| Medion        | P6634                       | [ec0002869f](https://linux-hardware.org/?probe=ec0002869f) | Feb 11, 2023 |
| Medion        | P6634                       | [15c3260ecf](https://linux-hardware.org/?probe=15c3260ecf) | Feb 11, 2023 |
| Acer          | Nitro AN515-55              | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| HP            | 450                         | [26d3505372](https://linux-hardware.org/?probe=26d3505372) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| ASUSTek       | GL752VW                     | [48f423dfae](https://linux-hardware.org/?probe=48f423dfae) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| HP            | ZBook 17 G3                 | [7e94a2328d](https://linux-hardware.org/?probe=7e94a2328d) | Feb 05, 2023 |
| Acer          | Aspire 4736Z                | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| HP            | EliteBook 2570p             | [43101dad89](https://linux-hardware.org/?probe=43101dad89) | Feb 02, 2023 |
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
| 5.10.0-13-amd64              | 15        | 9.43%   |
| 5.10.0-9-amd64               | 14        | 8.81%   |
| 5.10.0-21-amd64              | 12        | 7.55%   |
| 5.10.0-18-amd64              | 11        | 6.92%   |
| 5.10.0-16-amd64              | 9         | 5.66%   |
| 6.0.0-6mx-amd64              | 8         | 5.03%   |
| 5.14.0-4mx-amd64             | 8         | 5.03%   |
| 5.10.0-19-amd64              | 8         | 5.03%   |
| 5.16.0-5mx-amd64             | 6         | 3.77%   |
| 5.10.0-14-amd64              | 6         | 3.77%   |
| 5.10.0-11-amd64              | 6         | 3.77%   |
| 5.18.0-4mx-amd64             | 5         | 3.14%   |
| 6.0.0-4mx-amd64              | 4         | 2.52%   |
| 5.10.0-20-amd64              | 4         | 2.52%   |
| 5.10.0-17-amd64              | 3         | 1.89%   |
| 6.0.0-3mx-amd64              | 2         | 1.26%   |
| 5.19.0-2mx-amd64             | 2         | 1.26%   |
| 5.16.0-6mx-amd64             | 2         | 1.26%   |
| 5.10.0-8-amd64               | 2         | 1.26%   |
| 5.10.0-15-amd64              | 2         | 1.26%   |
| 5.10.0-13-686-pae            | 2         | 1.26%   |
| 5.10.0-11-686-pae            | 2         | 1.26%   |
| 5.10.0-10-amd64              | 2         | 1.26%   |
| 6.1.12-3-liquorix-amd64      | 1         | 0.63%   |
| 6.0.0-11.2-liquorix-amd64    | 1         | 0.63%   |
| 6.0.0-10.1-liquorix-amd64    | 1         | 0.63%   |
| 5.19.0-2mx-rt-amd64          | 1         | 0.63%   |
| 5.19.0-12.1-liquorix-amd64   | 1         | 0.63%   |
| 5.18.0-3-amd64               | 1         | 0.63%   |
| 5.18.0-0.deb11.4-amd64       | 1         | 0.63%   |
| 5.17.0-5.2-liquorix-amd64    | 1         | 0.63%   |
| 5.17.0-3mx-amd64             | 1         | 0.63%   |
| 5.17.0-2mx-amd64             | 1         | 0.63%   |
| 5.17.0-1-amd64               | 1         | 0.63%   |
| 5.16.0-4mx-amd64             | 1         | 0.63%   |
| 5.16.0-18.1-liquorix-amd64   | 1         | 0.63%   |
| 5.15.0-3mx-amd64             | 1         | 0.63%   |
| 5.10.82-hardened1-Rukhazon-0 | 1         | 0.63%   |
| 5.10.142-antix.2-amd64-smp   | 1         | 0.63%   |
| 5.10.0-9-686-pae             | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 96        | 63.58%  |
| 6.0.0    | 16        | 10.6%   |
| 5.16.0   | 10        | 6.62%   |
| 5.14.0   | 8         | 5.3%    |
| 5.18.0   | 7         | 4.64%   |
| 5.19.0   | 4         | 2.65%   |
| 5.17.0   | 4         | 2.65%   |
| 6.1.12   | 1         | 0.66%   |
| 5.15.0   | 1         | 0.66%   |
| 5.10.82  | 1         | 0.66%   |
| 5.10.142 | 1         | 0.66%   |
| 4.19.0   | 1         | 0.66%   |
| Unknown  | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 98        | 64.9%   |
| 6.0     | 16        | 10.6%   |
| 5.16    | 10        | 6.62%   |
| 5.14    | 8         | 5.3%    |
| 5.18    | 7         | 4.64%   |
| 5.19    | 4         | 2.65%   |
| 5.17    | 4         | 2.65%   |
| 6.1     | 1         | 0.66%   |
| 5.15    | 1         | 0.66%   |
| 4.19    | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 135       | 95.07%  |
| i686   | 7         | 4.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| XFCE             | 101       | 69.66%  |
| KDE5             | 33        | 22.76%  |
| Budgie           | 3         | 2.07%   |
| GNOME            | 2         | 1.38%   |
| Unknown          | 2         | 1.38%   |
| LXQt             | 1         | 0.69%   |
| lightdm-xsession | 1         | 0.69%   |
| i3               | 1         | 0.69%   |
| GNOME Classic    | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 140       | 98.59%  |
| Tty  | 2         | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 111       | 77.08%  |
| SDDM    | 31        | 21.53%  |
| SLiM    | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 70        | 48.61%  |
| de_DE   | 19        | 13.19%  |
| en_GB   | 9         | 6.25%   |
| it_IT   | 7         | 4.86%   |
| ru_RU   | 4         | 2.78%   |
| fr_FR   | 4         | 2.78%   |
| Unknown | 4         | 2.78%   |
| en_AU   | 3         | 2.08%   |
| de_CH   | 3         | 2.08%   |
| pt_BR   | 2         | 1.39%   |
| pl_PL   | 2         | 1.39%   |
| es_ES   | 2         | 1.39%   |
| en_NZ   | 2         | 1.39%   |
| bg_BG   | 2         | 1.39%   |
| tr_TR   | 1         | 0.69%   |
| sk_SK   | 1         | 0.69%   |
| nl_NL   | 1         | 0.69%   |
| nb_NO   | 1         | 0.69%   |
| id_ID   | 1         | 0.69%   |
| hu_HU   | 1         | 0.69%   |
| fi_FI   | 1         | 0.69%   |
| es_UY   | 1         | 0.69%   |
| es_PE   | 1         | 0.69%   |
| es_CO   | 1         | 0.69%   |
| en_CA   | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 106       | 74.65%  |
| BIOS | 36        | 25.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 119       | 82.64%  |
| Overlay | 19        | 13.19%  |
| Btrfs   | 5         | 3.47%   |
| F2fs    | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 108       | 76.06%  |
| MBR     | 33        | 23.24%  |
| Unknown | 1         | 0.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 75%     |
| Yes       | 36        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 81        | 56.64%  |
| Yes       | 62        | 43.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo                    | 27        | 19.01%  |
| Hewlett-Packard           | 23        | 16.2%   |
| Dell                      | 16        | 11.27%  |
| ASUSTek Computer          | 16        | 11.27%  |
| Acer                      | 11        | 7.75%   |
| Apple                     | 8         | 5.63%   |
| Sony                      | 7         | 4.93%   |
| Toshiba                   | 4         | 2.82%   |
| MSI                       | 4         | 2.82%   |
| Medion                    | 4         | 2.82%   |
| Samsung Electronics       | 3         | 2.11%   |
| Alienware                 | 3         | 2.11%   |
| Gigabyte Technology       | 2         | 1.41%   |
| Fujitsu Siemens           | 2         | 1.41%   |
| win element               | 1         | 0.7%    |
| Vulcan Electronics        | 1         | 0.7%    |
| TUXEDO                    | 1         | 0.7%    |
| SANTECH                   | 1         | 0.7%    |
| RTD Embedded Technologies | 1         | 0.7%    |
| Notebook                  | 1         | 0.7%    |
| Linx                      | 1         | 0.7%    |
| Framework                 | 1         | 0.7%    |
| efirstview                | 1         | 0.7%    |
| Chuwi                     | 1         | 0.7%    |
| AMI                       | 1         | 0.7%    |
| Unknown                   | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HP Laptop 17-ak0xx                        | 2         | 1.41%   |
| Apple MacBookAir7,2                       | 2         | 1.41%   |
| Acer Nitro AN515-55                       | 2         | 1.41%   |
| Unknown                                   | 2         | 1.41%   |
| win element MoreFine S500+                | 1         | 0.7%    |
| Vulcan Excursion XB                       | 1         | 0.7%    |
| TUXEDO N7x0WU                             | 1         | 0.7%    |
| Toshiba Satellite M70                     | 1         | 0.7%    |
| Toshiba Satellite L650                    | 1         | 0.7%    |
| Toshiba Satellite C845                    | 1         | 0.7%    |
| Toshiba PORTEGE Z30-C                     | 1         | 0.7%    |
| Sony VPCYB3V1E                            | 1         | 0.7%    |
| Sony VPCSB1V9R                            | 1         | 0.7%    |
| Sony VPCF119FX                            | 1         | 0.7%    |
| Sony VPCEH2N1E                            | 1         | 0.7%    |
| Sony VPCEC3S1E                            | 1         | 0.7%    |
| Sony VGN-TZ3RXN_B                         | 1         | 0.7%    |
| Sony SVE1513Q1ESI                         | 1         | 0.7%    |
| SANTECH X170KM-G                          | 1         | 0.7%    |
| Samsung NC210/NC110                       | 1         | 0.7%    |
| Samsung 350V5C/351V5C/3540VC/3440VC       | 1         | 0.7%    |
| Samsung 340XAA/350XAA/550XAA              | 1         | 0.7%    |
| RTD Embedded CMA34CR                      | 1         | 0.7%    |
| Notebook PD5x_7xPNP_PNN_PNT               | 1         | 0.7%    |
| MSI Modern 14 B11MOL                      | 1         | 0.7%    |
| MSI GV62 8RD                              | 1         | 0.7%    |
| MSI GF63 Thin 9SC                         | 1         | 0.7%    |
| MSI Alpha 15 B5EEK                        | 1         | 0.7%    |
| Medion P6634                              | 1         | 0.7%    |
| Medion E7424 MD60750                      | 1         | 0.7%    |
| Medion E14304                             | 1         | 0.7%    |
| Medion E1239T MD60139                     | 1         | 0.7%    |
| Linx LINX1010B                            | 1         | 0.7%    |
| Lenovo V15-IGL 82C3                       | 1         | 0.7%    |
| Lenovo ThinkPad X200s 74695XG             | 1         | 0.7%    |
| Lenovo ThinkPad X1 Extreme 2nd 20QV00BPUK | 1         | 0.7%    |
| Lenovo ThinkPad X1 Extreme 20MF000TIX     | 1         | 0.7%    |
| Lenovo ThinkPad W541 20EG0005MS           | 1         | 0.7%    |
| Lenovo ThinkPad T560 20FJS0EP00           | 1         | 0.7%    |
| Lenovo ThinkPad T500 2241VL9              | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 15        | 10.56%  |
| HP ProBook           | 5         | 3.52%   |
| HP EliteBook         | 5         | 3.52%   |
| Dell Inspiron        | 5         | 3.52%   |
| Acer Aspire          | 5         | 3.52%   |
| Lenovo IdeaPad       | 4         | 2.82%   |
| Dell Latitude        | 4         | 2.82%   |
| Toshiba Satellite    | 3         | 2.11%   |
| HP Laptop            | 3         | 2.11%   |
| Dell Vostro          | 3         | 2.11%   |
| Acer Nitro           | 3         | 2.11%   |
| Lenovo ThinkBook     | 2         | 1.41%   |
| HP Compaq            | 2         | 1.41%   |
| Dell Precision       | 2         | 1.41%   |
| ASUS VivoBook        | 2         | 1.41%   |
| ASUS ROG             | 2         | 1.41%   |
| ASUS ASUS            | 2         | 1.41%   |
| Apple MacBookPro11   | 2         | 1.41%   |
| Apple MacBookAir7    | 2         | 1.41%   |
| Alienware m15        | 2         | 1.41%   |
| Acer Swift           | 2         | 1.41%   |
| Unknown              | 2         | 1.41%   |
| win element MoreFine | 1         | 0.7%    |
| Vulcan Excursion     | 1         | 0.7%    |
| TUXEDO N7x0WU        | 1         | 0.7%    |
| Toshiba PORTEGE      | 1         | 0.7%    |
| Sony VPCYB3V1E       | 1         | 0.7%    |
| Sony VPCSB1V9R       | 1         | 0.7%    |
| Sony VPCF119FX       | 1         | 0.7%    |
| Sony VPCEH2N1E       | 1         | 0.7%    |
| Sony VPCEC3S1E       | 1         | 0.7%    |
| Sony VGN-TZ3RXN      | 1         | 0.7%    |
| Sony SVE1513Q1ESI    | 1         | 0.7%    |
| SANTECH X170KM-G     | 1         | 0.7%    |
| Samsung NC210        | 1         | 0.7%    |
| Samsung 350V5C       | 1         | 0.7%    |
| Samsung 340XAA       | 1         | 0.7%    |
| RTD Embedded CMA34CR | 1         | 0.7%    |
| Notebook PD5x        | 1         | 0.7%    |
| MSI Modern           | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 24        | 16.9%   |
| 2015    | 15        | 10.56%  |
| 2011    | 11        | 7.75%   |
| 2020    | 10        | 7.04%   |
| 2016    | 10        | 7.04%   |
| 2019    | 9         | 6.34%   |
| 2018    | 9         | 6.34%   |
| 2012    | 9         | 6.34%   |
| 2010    | 9         | 6.34%   |
| 2013    | 8         | 5.63%   |
| 2017    | 6         | 4.23%   |
| 2022    | 4         | 2.82%   |
| 2014    | 4         | 2.82%   |
| 2009    | 3         | 2.11%   |
| 2008    | 3         | 2.11%   |
| 2007    | 3         | 2.11%   |
| 2006    | 2         | 1.41%   |
| 2005    | 2         | 1.41%   |
| Unknown | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 142       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 141       | 99.3%   |
| Enabled  | 1         | 0.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 142       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 45        | 31.69%  |
| 8.01-16.0   | 25        | 17.61%  |
| 16.01-24.0  | 23        | 16.2%   |
| 3.01-4.0    | 22        | 15.49%  |
| 32.01-64.0  | 9         | 6.34%   |
| 1.01-2.0    | 8         | 5.63%   |
| 2.01-3.0    | 5         | 3.52%   |
| 64.01-256.0 | 2         | 1.41%   |
| 0.51-1.0    | 2         | 1.41%   |
| 24.01-32.0  | 1         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 48        | 31.37%  |
| 2.01-3.0  | 41        | 26.8%   |
| 3.01-4.0  | 29        | 18.95%  |
| 4.01-8.0  | 20        | 13.07%  |
| 0.51-1.0  | 11        | 7.19%   |
| 8.01-16.0 | 3         | 1.96%   |
| 0.01-0.5  | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 66.9%   |
| 2      | 34        | 23.45%  |
| 3      | 11        | 7.59%   |
| 0      | 2         | 1.38%   |
| 4      | 1         | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 68.31%  |
| Yes       | 45        | 31.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 80.28%  |
| No        | 28        | 19.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 95.1%   |
| No        | 7         | 4.9%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 81.69%  |
| No        | 26        | 18.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 32        | 22.22%  |
| Germany     | 19        | 13.19%  |
| Italy       | 14        | 9.72%   |
| Canada      | 8         | 5.56%   |
| Russia      | 5         | 3.47%   |
| Poland      | 4         | 2.78%   |
| Netherlands | 4         | 2.78%   |
| India       | 4         | 2.78%   |
| France      | 4         | 2.78%   |
| Brazil      | 4         | 2.78%   |
| Australia   | 4         | 2.78%   |
| UK          | 3         | 2.08%   |
| Switzerland | 3         | 2.08%   |
| Spain       | 2         | 1.39%   |
| Serbia      | 2         | 1.39%   |
| New Zealand | 2         | 1.39%   |
| Egypt       | 2         | 1.39%   |
| Bulgaria    | 2         | 1.39%   |
| Belgium     | 2         | 1.39%   |
| Bangladesh  | 2         | 1.39%   |
| Austria     | 2         | 1.39%   |
| Vietnam     | 1         | 0.69%   |
| Uruguay     | 1         | 0.69%   |
| Turkey      | 1         | 0.69%   |
| Tunisia     | 1         | 0.69%   |
| Sweden      | 1         | 0.69%   |
| Slovakia    | 1         | 0.69%   |
| Romania     | 1         | 0.69%   |
| Peru        | 1         | 0.69%   |
| Norway      | 1         | 0.69%   |
| Malaysia    | 1         | 0.69%   |
| Indonesia   | 1         | 0.69%   |
| Hungary     | 1         | 0.69%   |
| Greece      | 1         | 0.69%   |
| Ghana       | 1         | 0.69%   |
| Finland     | 1         | 0.69%   |
| Czechia     | 1         | 0.69%   |
| Croatia     | 1         | 0.69%   |
| Colombia    | 1         | 0.69%   |
| Belarus     | 1         | 0.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Warsaw         | 2         | 1.32%   |
| Walled Lake    | 2         | 1.32%   |
| Vienna         | 2         | 1.32%   |
| St Petersburg  | 2         | 1.32%   |
| Rome           | 2         | 1.32%   |
| Orange         | 2         | 1.32%   |
| New York       | 2         | 1.32%   |
| Moscow         | 2         | 1.32%   |
| Montreal       | 2         | 1.32%   |
| Milan          | 2         | 1.32%   |
| Florence       | 2         | 1.32%   |
| Doesburg       | 2         | 1.32%   |
| Dhaka          | 2         | 1.32%   |
| Casale Litta   | 2         | 1.32%   |
| Canberra       | 2         | 1.32%   |
| Cambridge      | 2         | 1.32%   |
| Cairo          | 2         | 1.32%   |
| Amsterdam      | 2         | 1.32%   |
| Zurich         | 1         | 0.66%   |
| Zeven          | 1         | 0.66%   |
| Yekaterinburg  | 1         | 0.66%   |
| Wermelskirchen | 1         | 0.66%   |
| Waycross       | 1         | 0.66%   |
| Vasco da Gama  | 1         | 0.66%   |
| Vancouver      | 1         | 0.66%   |
| Uelzen         | 1         | 0.66%   |
| Tunis          | 1         | 0.66%   |
| Tucson         | 1         | 0.66%   |
| Toulouse       | 1         | 0.66%   |
| Thessaloniki   | 1         | 0.66%   |
| The Dalles     | 1         | 0.66%   |
| Taggia         | 1         | 0.66%   |
| Tacoma         | 1         | 0.66%   |
| Sydney         | 1         | 0.66%   |
| Surprise       | 1         | 0.66%   |
| Stroud         | 1         | 0.66%   |
| Stockholm      | 1         | 0.66%   |
| Stadtilm       | 1         | 0.66%   |
| Soest          | 1         | 0.66%   |
| Slavonski Brod | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 13.54%  |
| WDC                 | 23        | 23     | 11.98%  |
| Seagate             | 18        | 20     | 9.38%   |
| Kingston            | 15        | 16     | 7.81%   |
| Crucial             | 14        | 27     | 7.29%   |
| Unknown             | 12        | 14     | 6.25%   |
| SK hynix            | 12        | 13     | 6.25%   |
| Toshiba             | 9         | 9      | 4.69%   |
| Intel               | 7         | 9      | 3.65%   |
| Apple               | 6         | 9      | 3.13%   |
| Hitachi             | 5         | 6      | 2.6%    |
| SPCC                | 4         | 4      | 2.08%   |
| Transcend           | 3         | 3      | 1.56%   |
| SanDisk             | 3         | 4      | 1.56%   |
| PNY                 | 3         | 3      | 1.56%   |
| LITEON              | 3         | 3      | 1.56%   |
| KIOXIA              | 3         | 4      | 1.56%   |
| HGST                | 3         | 3      | 1.56%   |
| Dogfish             | 3         | 3      | 1.56%   |
| Phison              | 2         | 3      | 1.04%   |
| Netac               | 2         | 2      | 1.04%   |
| Micron Technology   | 2         | 2      | 1.04%   |
| Unknown             | 2         | 2      | 1.04%   |
| Team                | 1         | 1      | 0.52%   |
| SWORDBILL           | 1         | 1      | 0.52%   |
| SABRENT             | 1         | 1      | 0.52%   |
| RENICE              | 1         | 1      | 0.52%   |
| Patriot             | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| Indilinx            | 1         | 1      | 0.52%   |
| Gigabyte Technology | 1         | 1      | 0.52%   |
| GeIL                | 1         | 1      | 0.52%   |
| Fujitsu             | 1         | 1      | 0.52%   |
| Corsair             | 1         | 1      | 0.52%   |
| Apacer              | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown SD32G  32GB                    | 3         | 1.51%   |
| SK hynix SKHynix_HFM512GD3HX015N 512GB | 3         | 1.51%   |
| Samsung SSD 980 PRO 1TB                | 3         | 1.51%   |
| Samsung SSD 860 EVO 500GB              | 3         | 1.51%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 1.51%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 1.51%   |
| Crucial CT480BX500SSD1 480GB           | 3         | 1.51%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 1.51%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 2         | 1.01%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 2         | 1.01%   |
| SPCC Solid State Disk 1TB              | 2         | 1.01%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 2         | 1.01%   |
| SK hynix HFM512GDJTNI-82A0A 512GB      | 2         | 1.01%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 1.01%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 1.01%   |
| Samsung SSD 860 250GB                  | 2         | 1.01%   |
| Samsung SSD 850 EVO 250GB              | 2         | 1.01%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 1.01%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 1.01%   |
| Kingston OM8PCP3512F-AI1 512GB         | 2         | 1.01%   |
| Intel SSDPEKNU512GZ 512GB              | 2         | 1.01%   |
| Hitachi HTS54503 320GB                 | 2         | 1.01%   |
| HGST HTS721010A9E630 1TB               | 2         | 1.01%   |
| Dogfish SSD 128GB                      | 2         | 1.01%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 1.01%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.01%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 1.01%   |
| Apple SSD SM0128G 121GB                | 2         | 1.01%   |
| Unknown                                | 2         | 1.01%   |
| WDC WDS100T1X0E-00AFY0 1TB             | 1         | 0.5%    |
| WDC WD7500BPVT-75HXZT3 752GB           | 1         | 0.5%    |
| WDC WD5000LPVX-75V0TT0 500GB           | 1         | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.5%    |
| WDC WD5000LPVX-08V0TT5 500GB           | 1         | 0.5%    |
| WDC WD5000LPLX-08ZNTT0 500GB           | 1         | 0.5%    |
| WDC WD5000LPLX-0 500GB                 | 1         | 0.5%    |
| WDC WD5000LPCX-22VHAT0 500GB           | 1         | 0.5%    |
| WDC WD3200BEVT-22ZCT0 320GB            | 1         | 0.5%    |
| WDC WD3200BEKT-75PVMT1 320GB           | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 20     | 39.13%  |
| WDC                 | 13        | 13     | 28.26%  |
| Hitachi             | 5         | 6      | 10.87%  |
| Toshiba             | 4         | 4      | 8.7%    |
| HGST                | 3         | 3      | 6.52%   |
| Samsung Electronics | 1         | 1      | 2.17%   |
| SABRENT             | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 17.95%  |
| Crucial             | 12        | 24     | 15.38%  |
| Kingston            | 9         | 9      | 11.54%  |
| Apple               | 5         | 8      | 6.41%   |
| SPCC                | 4         | 4      | 5.13%   |
| Transcend           | 3         | 3      | 3.85%   |
| SanDisk             | 3         | 4      | 3.85%   |
| PNY                 | 3         | 3      | 3.85%   |
| LITEON              | 3         | 3      | 3.85%   |
| Dogfish             | 3         | 3      | 3.85%   |
| WDC                 | 2         | 2      | 2.56%   |
| Toshiba             | 2         | 2      | 2.56%   |
| SK hynix            | 2         | 2      | 2.56%   |
| Netac               | 2         | 2      | 2.56%   |
| SWORDBILL           | 1         | 1      | 1.28%   |
| RENICE              | 1         | 1      | 1.28%   |
| Patriot             | 1         | 1      | 1.28%   |
| OCZ                 | 1         | 1      | 1.28%   |
| Intel               | 1         | 1      | 1.28%   |
| Indilinx            | 1         | 1      | 1.28%   |
| Gigabyte Technology | 1         | 1      | 1.28%   |
| GeIL                | 1         | 1      | 1.28%   |
| Corsair             | 1         | 1      | 1.28%   |
| Apacer              | 1         | 1      | 1.28%   |
| Unknown             | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 67        | 98     | 38.51%  |
| NVMe | 49        | 66     | 28.16%  |
| HDD  | 45        | 49     | 25.86%  |
| MMC  | 13        | 16     | 7.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 96        | 146    | 60.38%  |
| NVMe | 49        | 66     | 30.82%  |
| MMC  | 13        | 16     | 8.18%   |
| SAS  | 1         | 1      | 0.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 106    | 75.23%  |
| 0.51-1.0   | 25        | 39     | 22.94%  |
| 1.01-2.0   | 2         | 2      | 1.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 40        | 26.85%  |
| 251-500        | 35        | 23.49%  |
| 501-1000       | 21        | 14.09%  |
| 21-50          | 17        | 11.41%  |
| 51-100         | 13        | 8.72%   |
| 1-20           | 10        | 6.71%   |
| 1001-2000      | 8         | 5.37%   |
| More than 3000 | 3         | 2.01%   |
| 2001-3000      | 2         | 1.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 44.44%  |
| 21-50          | 24        | 15.69%  |
| 51-100         | 19        | 12.42%  |
| 101-250        | 17        | 11.11%  |
| 251-500        | 13        | 8.5%    |
| 501-1000       | 6         | 3.92%   |
| 1001-2000      | 4         | 2.61%   |
| More than 3000 | 1         | 0.65%   |
| 2001-3000      | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 5%      |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 5%      |
| Toshiba THNSNK256GCS8 SATA 256GB SSD         | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 5%      |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 5%      |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 5%      |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 5%      |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 5%      |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 5%      |
| RENICE X2 64GB SSD                           | 1         | 1      | 5%      |
| Kingston SA400S37120G 120GB SSD              | 1         | 1      | 5%      |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 5%      |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 5%      |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 5%      |
| Hitachi HTS543216L9SA00 160GB                | 1         | 1      | 5%      |
| Hitachi HTS541080G9SA00 80GB                 | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 5%      |
| Crucial CT1000MX500SSD4 1TB                  | 1         | 3      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 25%     |
| Hitachi             | 3         | 3      | 15%     |
| WDC                 | 2         | 2      | 10%     |
| Samsung Electronics | 2         | 2      | 10%     |
| HGST                | 2         | 2      | 10%     |
| Toshiba             | 1         | 1      | 5%      |
| RENICE              | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intel               | 1         | 2      | 5%      |
| Indilinx            | 1         | 1      | 5%      |
| Crucial             | 1         | 3      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| Hitachi | 3         | 3      | 25%     |
| WDC     | 2         | 2      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 60%     |
| SSD  | 7         | 9      | 35%     |
| NVMe | 1         | 2      | 5%      |

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
| Works    | 119       | 187    | 76.77%  |
| Malfunc  | 20        | 23     | 12.9%   |
| Detected | 16        | 19     | 10.32%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 96        | 57.83%  |
| Samsung Electronics          | 16        | 9.64%   |
| AMD                          | 13        | 7.83%   |
| SK hynix                     | 9         | 5.42%   |
| SanDisk                      | 8         | 4.82%   |
| Kingston Technology Company  | 6         | 3.61%   |
| KIOXIA                       | 4         | 2.41%   |
| Phison Electronics           | 3         | 1.81%   |
| Nvidia                       | 3         | 1.81%   |
| Toshiba America Info Systems | 2         | 1.2%    |
| Micron/Crucial Technology    | 2         | 1.2%    |
| Micron Technology            | 2         | 1.2%    |
| Silicon Image                | 1         | 0.6%    |
| Marvell Technology Group     | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 9.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 7.34%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 6.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 3.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 2.82%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 2.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.26%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 2.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 2.26%   |
| SK hynix BC511                                                                 | 3         | 1.69%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.69%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.69%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.13%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.13%   |
| Samsung Electronics SATA controller                                            | 2         | 1.13%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.13%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.13%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.13%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.13%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 1.13%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.13%   |
| Intel Non-Volatile memory controller                                           | 2         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.13%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.56%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 100       | 60.24%  |
| NVMe | 49        | 29.52%  |
| IDE  | 11        | 6.63%   |
| RAID | 6         | 3.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 82.39%  |
| AMD    | 25        | 17.61%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 4.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 2.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 2.11%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.11%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 3         | 2.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 2.11%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 2.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 2.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.41%   |
| Intel Core i5-5350U CPU @ 1.80GHz           | 2         | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.41%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.41%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 2         | 1.41%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 1.41%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.41%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 2         | 1.41%   |
| Intel 12th Gen Core i7-12700H               | 2         | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.41%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.41%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.41%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.7%    |
| Intel Pentium M processor 1.80GHz           | 1         | 0.7%    |
| Intel Pentium M processor 1.73GHz           | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.7%    |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.7%    |
| Intel Pentium CPU 2127U @ 1.90GHz           | 1         | 0.7%    |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.7%    |
| Intel Core i7-4980HQ CPU @ 2.80GHz          | 1         | 0.7%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.7%    |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 0.7%    |
| Intel Core i7-3612QE CPU @ 2.10GHz          | 1         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 30        | 21.13%  |
| Intel Core i5           | 27        | 19.01%  |
| Other                   | 14        | 9.86%   |
| Intel Core i3           | 14        | 9.86%   |
| Intel Celeron           | 12        | 8.45%   |
| AMD Ryzen 7             | 8         | 5.63%   |
| Intel Core 2 Duo        | 6         | 4.23%   |
| Intel Atom              | 6         | 4.23%   |
| AMD Ryzen 5             | 5         | 3.52%   |
| Intel Pentium M         | 2         | 1.41%   |
| Intel Pentium           | 2         | 1.41%   |
| AMD Ryzen 9             | 2         | 1.41%   |
| AMD Ryzen 3             | 2         | 1.41%   |
| Intel Pentium Silver    | 1         | 0.7%    |
| Intel Pentium Dual-Core | 1         | 0.7%    |
| Intel Genuine           | 1         | 0.7%    |
| Intel Core 2            | 1         | 0.7%    |
| AMD Turion 64 X2 Mobile | 1         | 0.7%    |
| AMD Sempron             | 1         | 0.7%    |
| AMD E2                  | 1         | 0.7%    |
| AMD E1                  | 1         | 0.7%    |
| AMD E                   | 1         | 0.7%    |
| AMD A8                  | 1         | 0.7%    |
| AMD A6                  | 1         | 0.7%    |
| AMD A10                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 47.18%  |
| 4      | 46        | 32.39%  |
| 8      | 11        | 7.75%   |
| 6      | 11        | 7.75%   |
| 1      | 5         | 3.52%   |
| 14     | 2         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 103       | 72.54%  |
| 1      | 39        | 27.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 97.18%  |
| 32-bit         | 4         | 2.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 9.66%   |
| 0x206a7    | 12        | 8.28%   |
| 0x306a9    | 10        | 6.9%    |
| 0x806c1    | 9         | 6.21%   |
| 0x406e3    | 8         | 5.52%   |
| 0x0a50000c | 7         | 4.83%   |
| 0x506e3    | 6         | 4.14%   |
| 0x906ea    | 5         | 3.45%   |
| 0xa0652    | 4         | 2.76%   |
| 0x806ea    | 4         | 2.76%   |
| 0x30678    | 4         | 2.76%   |
| 0x20655    | 4         | 2.76%   |
| 0x1067a    | 4         | 2.76%   |
| 0x08608103 | 4         | 2.76%   |
| 0x806e9    | 3         | 2.07%   |
| 0x706a8    | 3         | 2.07%   |
| 0x406c4    | 3         | 2.07%   |
| 0x306d4    | 3         | 2.07%   |
| 0x306c3    | 3         | 2.07%   |
| 0x906a3    | 2         | 1.38%   |
| 0x706a1    | 2         | 1.38%   |
| 0x6fd      | 2         | 1.38%   |
| 0x07030106 | 2         | 1.38%   |
| 0xa0671    | 1         | 0.69%   |
| 0x906ed    | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x906c0    | 1         | 0.69%   |
| 0x806ec    | 1         | 0.69%   |
| 0x806eb    | 1         | 0.69%   |
| 0x806d1    | 1         | 0.69%   |
| 0x6fb      | 1         | 0.69%   |
| 0x6e8      | 1         | 0.69%   |
| 0x6d8      | 1         | 0.69%   |
| 0x6d6      | 1         | 0.69%   |
| 0x506c9    | 1         | 0.69%   |
| 0x40661    | 1         | 0.69%   |
| 0x40651    | 1         | 0.69%   |
| 0x20652    | 1         | 0.69%   |
| 0x106e5    | 1         | 0.69%   |
| 0x106ca    | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 11.97%  |
| Skylake          | 14        | 9.86%   |
| SandyBridge      | 13        | 9.15%   |
| IvyBridge        | 11        | 7.75%   |
| TigerLake        | 10        | 7.04%   |
| Zen 3            | 8         | 5.63%   |
| Silvermont       | 7         | 4.93%   |
| Westmere         | 6         | 4.23%   |
| Unknown          | 6         | 4.23%   |
| Haswell          | 5         | 3.52%   |
| Goldmont plus    | 5         | 3.52%   |
| Penryn           | 4         | 2.82%   |
| Core             | 4         | 2.82%   |
| CometLake        | 4         | 2.82%   |
| Zen+             | 3         | 2.11%   |
| P6               | 3         | 2.11%   |
| Icelake          | 3         | 2.11%   |
| Broadwell        | 3         | 2.11%   |
| Puma             | 2         | 1.41%   |
| Goldmont         | 2         | 1.41%   |
| Excavator        | 2         | 1.41%   |
| Bonnell          | 2         | 1.41%   |
| Zen 2            | 1         | 0.7%    |
| Tremont          | 1         | 0.7%    |
| Piledriver       | 1         | 0.7%    |
| Nehalem          | 1         | 0.7%    |
| K8 Hammer        | 1         | 0.7%    |
| K8 & K10 hybrid  | 1         | 0.7%    |
| Bobcat           | 1         | 0.7%    |
| Alderlake Hybrid | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 107       | 60.45%  |
| Nvidia | 40        | 22.6%   |
| AMD    | 30        | 16.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 6.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 5.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 5.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 4.32%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 3.24%   |
| Intel HD Graphics 530                                                                    | 5         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.7%    |
| AMD Lucienne                                                                             | 5         | 2.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 2.16%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.16%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.16%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.62%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.62%   |
| Intel HD Graphics 620                                                                    | 3         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.08%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.08%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.08%   |
| Intel HD Graphics 6000                                                                   | 2         | 1.08%   |
| Intel HD Graphics 500                                                                    | 2         | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.08%   |
| Nvidia TU117M                                                                            | 1         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.54%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.54%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.54%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.54%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.54%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 75        | 52.82%  |
| Intel + Nvidia | 26        | 18.31%  |
| 1 x AMD        | 19        | 13.38%  |
| 1 x Nvidia     | 10        | 7.04%   |
| Intel + AMD    | 5         | 3.52%   |
| 2 x AMD        | 3         | 2.11%   |
| AMD + Nvidia   | 3         | 2.11%   |
| 2 x Intel      | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 123       | 84.25%  |
| Proprietary | 17        | 11.64%  |
| Unknown     | 6         | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 77.08%  |
| 0.01-0.5   | 13        | 9.03%   |
| 0.51-1.0   | 7         | 4.86%   |
| 3.01-4.0   | 5         | 3.47%   |
| 1.01-2.0   | 4         | 2.78%   |
| 7.01-8.0   | 3         | 2.08%   |
| 2.01-3.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 18.35%  |
| Chimei Innolux          | 27        | 17.09%  |
| Samsung Electronics     | 16        | 10.13%  |
| LG Display              | 15        | 9.49%   |
| BOE                     | 13        | 8.23%   |
| Hewlett-Packard         | 7         | 4.43%   |
| Apple                   | 7         | 4.43%   |
| PANDA                   | 6         | 3.8%    |
| Chi Mei Optoelectronics | 6         | 3.8%    |
| Lenovo                  | 5         | 3.16%   |
| Sharp                   | 4         | 2.53%   |
| Sony                    | 3         | 1.9%    |
| Goldstar                | 3         | 1.9%    |
| Ancor Communications    | 3         | 1.9%    |
| Dell                    | 2         | 1.27%   |
| CPT                     | 2         | 1.27%   |
| Sunplus                 | 1         | 0.63%   |
| STA                     | 1         | 0.63%   |
| Philips                 | 1         | 0.63%   |
| Panasonic               | 1         | 0.63%   |
| Packard Bell            | 1         | 0.63%   |
| NEC Computers           | 1         | 0.63%   |
| LTM                     | 1         | 0.63%   |
| LG Philips              | 1         | 0.63%   |
| InfoVision              | 1         | 0.63%   |
| Eizo                    | 1         | 0.63%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 1.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 1.9%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 1.27%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 2         | 1.27%   |
| Hewlett-Packard E240 HWP3265 1920x1080 527x296mm 23.8-inch               | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.27%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 1.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.27%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 1.27%   |
| Sunplus Monitor TV SPVFFFF 1360x768 708x398mm 32.0-inch                  | 1         | 0.63%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.63%   |
| Sony TV SNY3001 1920x1080                                                | 1         | 0.63%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.63%   |
| Sony LCD MS_0025 1920x1080 291x164mm 13.2-inch                           | 1         | 0.63%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP1445 3840x2160 346x194mm 15.6-inch                  | 1         | 0.63%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.63%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.63%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch        | 1         | 0.63%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.63%   |
| Samsung Electronics S22B300 SAM08C8 1920x1080 477x268mm 21.5-inch        | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC3854 1920x1080 382x215mm 17.3-inch    | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080                        | 1         | 0.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.63%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.63%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 1         | 0.63%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 0.63%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch             | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 68        | 45.95%  |
| 1366x768 (WXGA)    | 38        | 25.68%  |
| 3840x2160 (4K)     | 8         | 5.41%   |
| 1600x900 (HD+)     | 6         | 4.05%   |
| 1280x800 (WXGA)    | 5         | 3.38%   |
| 1920x1200 (WUXGA)  | 4         | 2.7%    |
| 2880x1800          | 3         | 2.03%   |
| 2560x1080          | 2         | 1.35%   |
| 1440x900 (WXGA+)   | 2         | 1.35%   |
| 1280x1024 (SXGA)   | 2         | 1.35%   |
| 3840x2400          | 1         | 0.68%   |
| 2560x1600          | 1         | 0.68%   |
| 2560x1440 (QHD)    | 1         | 0.68%   |
| 2256x1504          | 1         | 0.68%   |
| 2160x1440          | 1         | 0.68%   |
| 1680x1050 (WSXGA+) | 1         | 0.68%   |
| 1400x1050          | 1         | 0.68%   |
| 1360x768           | 1         | 0.68%   |
| 1024x768 (XGA)     | 1         | 0.68%   |
| 1024x600           | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 66        | 41.77%  |
| 13      | 17        | 10.76%  |
| 17      | 16        | 10.13%  |
| 14      | 14        | 8.86%   |
| 24      | 10        | 6.33%   |
| 11      | 7         | 4.43%   |
| 23      | 6         | 3.8%    |
| 21      | 3         | 1.9%    |
| 19      | 3         | 1.9%    |
| 40      | 2         | 1.27%   |
| 34      | 2         | 1.27%   |
| 12      | 2         | 1.27%   |
| 10      | 2         | 1.27%   |
| Unknown | 2         | 1.27%   |
| 84      | 1         | 0.63%   |
| 46      | 1         | 0.63%   |
| 32      | 1         | 0.63%   |
| 27      | 1         | 0.63%   |
| 25      | 1         | 0.63%   |
| 16      | 1         | 0.63%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 54.78%  |
| 201-300     | 21        | 13.38%  |
| 351-400     | 20        | 12.74%  |
| 501-600     | 17        | 10.83%  |
| 401-500     | 4         | 2.55%   |
| 701-800     | 3         | 1.91%   |
| 801-900     | 2         | 1.27%   |
| Unknown     | 2         | 1.27%   |
| 1501-2000   | 1         | 0.64%   |
| 1001-1500   | 1         | 0.64%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 113       | 80.71%  |
| 16/10 | 19        | 13.57%  |
| 5/4   | 2         | 1.43%   |
| 4/3   | 2         | 1.43%   |
| 3/2   | 2         | 1.43%   |
| 21/9  | 2         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 42.41%  |
| 81-90          | 25        | 15.82%  |
| 121-130        | 16        | 10.13%  |
| 201-250        | 15        | 9.49%   |
| 51-60          | 7         | 4.43%   |
| 71-80          | 5         | 3.16%   |
| 251-300        | 4         | 2.53%   |
| 151-200        | 4         | 2.53%   |
| 351-500        | 3         | 1.9%    |
| 501-1000       | 3         | 1.9%    |
| 61-70          | 2         | 1.27%   |
| 41-50          | 2         | 1.27%   |
| Unknown        | 2         | 1.27%   |
| More than 1000 | 1         | 0.63%   |
| 301-350        | 1         | 0.63%   |
| 91-100         | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 42.21%  |
| 101-120       | 34        | 22.08%  |
| 51-100        | 34        | 22.08%  |
| 161-240       | 11        | 7.14%   |
| More than 240 | 6         | 3.9%    |
| 1-50          | 2         | 1.3%    |
| Unknown       | 2         | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 112       | 76.71%  |
| 2     | 24        | 16.44%  |
| 0     | 7         | 4.79%   |
| 3     | 3         | 2.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 76        | 32.34%  |
| Intel                             | 76        | 32.34%  |
| Qualcomm Atheros                  | 31        | 13.19%  |
| Broadcom                          | 11        | 4.68%   |
| MediaTek                          | 7         | 2.98%   |
| Broadcom Limited                  | 6         | 2.55%   |
| TP-Link                           | 5         | 2.13%   |
| Marvell Technology Group          | 5         | 2.13%   |
| Sierra Wireless                   | 2         | 0.85%   |
| Ralink                            | 2         | 0.85%   |
| Nvidia                            | 2         | 0.85%   |
| Motorola PCS                      | 2         | 0.85%   |
| Sweex                             | 1         | 0.43%   |
| Samsung Electronics               | 1         | 0.43%   |
| Ralink Technology                 | 1         | 0.43%   |
| Qualcomm Atheros Communications   | 1         | 0.43%   |
| NetGear                           | 1         | 0.43%   |
| Lenovo                            | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| Dell                              | 1         | 0.43%   |
| ASUSTek Computer                  | 1         | 0.43%   |
| ASIX Electronics                  | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 48        | 17.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 10        | 3.62%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 3.62%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 2.54%   |
| Intel Wireless 8260                                                     | 7         | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 6         | 2.17%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.45%   |
| Intel Wireless 3165                                                     | 4         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.09%   |
| Intel Wireless 7260                                                     | 3         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.09%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.72%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 2         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.72%   |
| Intel Wireless 7265                                                     | 2         | 0.72%   |
| Intel Wireless 3160                                                     | 2         | 0.72%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 49.33%  |
| Realtek Semiconductor           | 22        | 14.67%  |
| Qualcomm Atheros                | 22        | 14.67%  |
| Broadcom                        | 8         | 5.33%   |
| MediaTek                        | 6         | 4%      |
| Broadcom Limited                | 5         | 3.33%   |
| TP-Link                         | 4         | 2.67%   |
| Sierra Wireless                 | 2         | 1.33%   |
| Ralink                          | 2         | 1.33%   |
| Sweex                           | 1         | 0.67%   |
| Ralink Technology               | 1         | 0.67%   |
| Qualcomm Atheros Communications | 1         | 0.67%   |
| NetGear                         | 1         | 0.67%   |
| ASUSTek Computer                | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 10        | 6.67%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 5.33%   |
| Intel Wireless 8260                                                     | 7         | 4.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.33%   |
| Intel Wireless 8265 / 8275                                              | 5         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.67%   |
| Intel Wireless 3165                                                     | 4         | 2.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 2%      |
| Intel Wireless 7260                                                     | 3         | 2%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.33%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 1.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.33%   |
| Intel Wireless 7265                                                     | 2         | 1.33%   |
| Intel Wireless 3160                                                     | 2         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.33%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.33%   |
| Sweex LW154 802.11bgn (1x1:1) Wireless Adapter [Realtek RTL8188SU]      | 1         | 0.67%   |
| Sierra Wireless EM7455                                                  | 1         | 0.67%   |
| Sierra Wireless EM7305                                                  | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.67%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 68        | 56.67%  |
| Intel                    | 21        | 17.5%   |
| Qualcomm Atheros         | 13        | 10.83%  |
| Marvell Technology Group | 5         | 4.17%   |
| Broadcom                 | 4         | 3.33%   |
| Nvidia                   | 2         | 1.67%   |
| TP-Link                  | 1         | 0.83%   |
| Samsung Electronics      | 1         | 0.83%   |
| Motorola PCS             | 1         | 0.83%   |
| MediaTek                 | 1         | 0.83%   |
| Lenovo                   | 1         | 0.83%   |
| Broadcom Limited         | 1         | 0.83%   |
| ASIX Electronics         | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 48        | 39.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 8.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 5.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 2.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 1.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.64%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.64%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.64%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.64%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.64%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.64%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.82%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.82%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.82%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.82%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.82%   |
| Motorola PCS moto g(8) plus                                                    | 1         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.82%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.82%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.82%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.82%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.82%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 53.75%  |
| Ethernet | 113       | 44.66%  |
| Modem    | 3         | 1.19%   |
| Unknown  | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 77.24%  |
| Ethernet | 33        | 22.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 103       | 72.03%  |
| 1     | 34        | 23.78%  |
| 0     | 4         | 2.8%    |
| 3     | 2         | 1.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 72.92%  |
| Yes  | 39        | 27.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 48.74%  |
| Qualcomm Atheros Communications | 13        | 10.92%  |
| Realtek Semiconductor           | 9         | 7.56%   |
| Broadcom                        | 7         | 5.88%   |
| Apple                           | 7         | 5.88%   |
| Foxconn / Hon Hai               | 5         | 4.2%    |
| Cambridge Silicon Radio         | 5         | 4.2%    |
| IMC Networks                    | 4         | 3.36%   |
| Lite-On Technology              | 3         | 2.52%   |
| Ralink                          | 2         | 1.68%   |
| Hewlett-Packard                 | 2         | 1.68%   |
| MediaTek                        | 1         | 0.84%   |
| Dell                            | 1         | 0.84%   |
| ASUSTek Computer                | 1         | 0.84%   |
| Alps Electric                   | 1         | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 18.49%  |
| Intel AX201 Bluetooth                                                               | 10        | 8.4%    |
| Intel AX200 Bluetooth                                                               | 10        | 8.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 7.56%   |
| Realtek Bluetooth Radio                                                             | 7         | 5.88%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 4.2%    |
| Apple Bluetooth Host Controller                                                     | 4         | 3.36%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.52%   |
| IMC Networks Wireless_Device                                                        | 3         | 2.52%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 2.52%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.68%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.68%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.68%   |
| Lite-On Wireless_Device                                                             | 2         | 1.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.68%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.68%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.84%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.84%   |
| MediaTek Wireless_Device                                                            | 1         | 0.84%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.84%   |
| Intel Bluetooth Device                                                              | 1         | 0.84%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.84%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.84%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.84%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.84%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.84%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.84%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.84%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.84%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.84%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 110       | 61.11%  |
| Nvidia                  | 31        | 17.22%  |
| AMD                     | 25        | 13.89%  |
| Realtek Semiconductor   | 2         | 1.11%   |
| Texas Instruments       | 1         | 0.56%   |
| Plantronics             | 1         | 0.56%   |
| Logitech                | 1         | 0.56%   |
| Lenovo                  | 1         | 0.56%   |
| Guillemot               | 1         | 0.56%   |
| Generalplus Technology  | 1         | 0.56%   |
| Focusrite-Novation      | 1         | 0.56%   |
| FIFINE 683 Microphone   | 1         | 0.56%   |
| Conexant Systems        | 1         | 0.56%   |
| CMX Systems             | 1         | 0.56%   |
| C-Media Electronics     | 1         | 0.56%   |
| BEHRINGER International | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 8.1%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 7.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 7.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 6.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.9%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.9%    |
| Nvidia Audio device                                                                               | 4         | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.43%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.43%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.95%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.95%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.48%   |
| Plantronics BT600                                                                                 | 1         | 0.48%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 44        | 25.43%  |
| Samsung Electronics | 40        | 23.12%  |
| Unknown             | 19        | 10.98%  |
| Kingston            | 17        | 9.83%   |
| Micron Technology   | 16        | 9.25%   |
| Crucial             | 9         | 5.2%    |
| Elpida              | 4         | 2.31%   |
| Unknown (ABCD)      | 3         | 1.73%   |
| Corsair             | 3         | 1.73%   |
| A-DATA Technology   | 3         | 1.73%   |
| Transcend           | 2         | 1.16%   |
| Smart               | 2         | 1.16%   |
| Ramaxel Technology  | 2         | 1.16%   |
| Team                | 1         | 0.58%   |
| PNY                 | 1         | 0.58%   |
| Nanya Technology    | 1         | 0.58%   |
| Innodisk            | 1         | 0.58%   |
| Hewlett-Packard     | 1         | 0.58%   |
| Avant               | 1         | 0.58%   |
| ASint Technology    | 1         | 0.58%   |
| 48spaces            | 1         | 0.58%   |
| Unknown             | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.7%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 2.16%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 2.16%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.62%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.08%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.08%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 1.08%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.08%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 1.08%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.08%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.08%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.08%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.08%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 1.08%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 2         | 1.08%   |
| A-DATA RAM Module 4GB SODIMM DDR3 1333MT/s                       | 2         | 1.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.54%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.54%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.54%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.54%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 0.54%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.54%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.54%   |
| Smart RAM SF4641G8CK8IEGKSBG 8192MB SODIMM DDR4 2400MT/s         | 1         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 63        | 43.15%  |
| DDR4   | 60        | 41.1%   |
| LPDDR4 | 7         | 4.79%   |
| DDR2   | 6         | 4.11%   |
| DDR    | 4         | 2.74%   |
| SDRAM  | 2         | 1.37%   |
| LPDDR3 | 2         | 1.37%   |
| DRAM   | 1         | 0.68%   |
| DDR5   | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 136       | 93.15%  |
| Row Of Chips | 9         | 6.16%   |
| DIMM         | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 59        | 37.34%  |
| 4096  | 53        | 33.54%  |
| 2048  | 23        | 14.56%  |
| 16384 | 14        | 8.86%   |
| 1024  | 6         | 3.8%    |
| 32768 | 2         | 1.27%   |
| 512   | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 40        | 25.32%  |
| 3200    | 29        | 18.35%  |
| 2667    | 17        | 10.76%  |
| 2400    | 15        | 9.49%   |
| 1333    | 11        | 6.96%   |
| 1334    | 10        | 6.33%   |
| Unknown | 9         | 5.7%    |
| 2133    | 6         | 3.8%    |
| 667     | 6         | 3.8%    |
| 1067    | 4         | 2.53%   |
| 4267    | 2         | 1.27%   |
| 4199    | 2         | 1.27%   |
| 8400    | 1         | 0.63%   |
| 4800    | 1         | 0.63%   |
| 4266    | 1         | 0.63%   |
| 2933    | 1         | 0.63%   |
| 1867    | 1         | 0.63%   |
| 533     | 1         | 0.63%   |
| 166     | 1         | 0.63%   |

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
| Chicony Electronics                    | 27        | 23.48%  |
| Microdia                               | 12        | 10.43%  |
| Acer                                   | 12        | 10.43%  |
| Realtek Semiconductor                  | 10        | 8.7%    |
| Cheng Uei Precision Industry (Foxlink) | 9         | 7.83%   |
| IMC Networks                           | 7         | 6.09%   |
| Quanta                                 | 5         | 4.35%   |
| Suyin                                  | 4         | 3.48%   |
| Sunplus Innovation Technology          | 4         | 3.48%   |
| Lite-On Technology                     | 4         | 3.48%   |
| Apple                                  | 4         | 3.48%   |
| Ricoh                                  | 3         | 2.61%   |
| Lenovo                                 | 3         | 2.61%   |
| Silicon Motion                         | 2         | 1.74%   |
| Luxvisions Innotech Limited            | 2         | 1.74%   |
| Alcor Micro                            | 2         | 1.74%   |
| Z-Star Microelectronics                | 1         | 0.87%   |
| Y Media                                | 1         | 0.87%   |
| Primax Electronics                     | 1         | 0.87%   |
| Logitech                               | 1         | 0.87%   |
| Goodong Industry                       | 1         | 0.87%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 5         | 4.31%   |
| Chicony Integrated Camera                           | 5         | 4.31%   |
| Quanta HD User Facing                               | 3         | 2.59%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 2.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 2.59%   |
| Chicony HD User Facing                              | 3         | 2.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 2.59%   |
| Acer Integrated Camera                              | 3         | 2.59%   |
| Acer BisonCam,NB Pro                                | 3         | 2.59%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.72%   |
| Realtek USB Camera                                  | 2         | 1.72%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.72%   |
| Lite-On HP HD Camera                                | 2         | 1.72%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.72%   |
| IMC Networks Integrated Camera                      | 2         | 1.72%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.72%   |
| Acer HD Webcam                                      | 2         | 1.72%   |
| Acer BisonCam, NB Pro                               | 2         | 1.72%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 0.86%   |
| Y Media USB Camera                                  | 1         | 0.86%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.86%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.86%   |
| Suyin HP Webcam                                     | 1         | 0.86%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.86%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.86%   |
| Sunplus ASUS Webcam                                 | 1         | 0.86%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.86%   |
| Silicon Motion Web Camera                           | 1         | 0.86%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.86%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.86%   |
| Ricoh Integrated Webcam                             | 1         | 0.86%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.86%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.86%   |
| Realtek Integrated Webcam HD                        | 1         | 0.86%   |
| Realtek Integrated Webcam                           | 1         | 0.86%   |
| Realtek EasyCamera                                  | 1         | 0.86%   |
| Realtek Built-In Video Camera                       | 1         | 0.86%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.86%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.86%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 29.17%  |
| Synaptics                  | 5         | 20.83%  |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| AuthenTec                  | 4         | 16.67%  |
| Upek                       | 2         | 8.33%   |
| Elan Microelectronics      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 5         | 20.83%  |
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 8.33%   |
| AuthenTec AES2810                                      | 2         | 8.33%   |
| Unknown                                                | 2         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.17%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.17%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 4.17%   |

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
| 0     | 92        | 62.16%  |
| 1     | 41        | 27.7%   |
| 2     | 13        | 8.78%   |
| 3     | 2         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 28        | 41.18%  |
| Fingerprint reader       | 24        | 35.29%  |
| Chipcard                 | 8         | 11.76%  |
| Multimedia controller    | 3         | 4.41%   |
| Camera                   | 2         | 2.94%   |
| Net/ethernet             | 1         | 1.47%   |
| Communication controller | 1         | 1.47%   |
| Bluetooth                | 1         | 1.47%   |

