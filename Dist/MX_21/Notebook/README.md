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

Total: 161

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-9-amd64               | 14        | 11.97%  |
| 5.10.0-13-amd64              | 14        | 11.97%  |
| 5.10.0-18-amd64              | 10        | 8.55%   |
| 5.10.0-16-amd64              | 9         | 7.69%   |
| 5.14.0-4mx-amd64             | 8         | 6.84%   |
| 5.16.0-5mx-amd64             | 6         | 5.13%   |
| 5.10.0-14-amd64              | 6         | 5.13%   |
| 5.10.0-11-amd64              | 6         | 5.13%   |
| 5.10.0-19-amd64              | 5         | 4.27%   |
| 5.18.0-4mx-amd64             | 4         | 3.42%   |
| 5.10.0-17-amd64              | 3         | 2.56%   |
| 6.0.0-3mx-amd64              | 2         | 1.71%   |
| 5.16.0-6mx-amd64             | 2         | 1.71%   |
| 5.10.0-8-amd64               | 2         | 1.71%   |
| 5.10.0-15-amd64              | 2         | 1.71%   |
| 5.10.0-13-686-pae            | 2         | 1.71%   |
| 5.10.0-11-686-pae            | 2         | 1.71%   |
| 5.10.0-10-amd64              | 2         | 1.71%   |
| 6.0.0-4mx-amd64              | 1         | 0.85%   |
| 5.19.0-2mx-amd64             | 1         | 0.85%   |
| 5.19.0-12.1-liquorix-amd64   | 1         | 0.85%   |
| 5.18.0-3-amd64               | 1         | 0.85%   |
| 5.18.0-0.deb11.4-amd64       | 1         | 0.85%   |
| 5.17.0-5.2-liquorix-amd64    | 1         | 0.85%   |
| 5.17.0-3mx-amd64             | 1         | 0.85%   |
| 5.17.0-2mx-amd64             | 1         | 0.85%   |
| 5.17.0-1-amd64               | 1         | 0.85%   |
| 5.16.0-4mx-amd64             | 1         | 0.85%   |
| 5.16.0-18.1-liquorix-amd64   | 1         | 0.85%   |
| 5.15.0-3mx-amd64             | 1         | 0.85%   |
| 5.10.82-hardened1-Rukhazon-0 | 1         | 0.85%   |
| 5.10.0-5mx-amd64             | 1         | 0.85%   |
| 5.10.0-18-686-pae            | 1         | 0.85%   |
| 5.10.0-12-amd64              | 1         | 0.85%   |
| 5.10.0-11-686                | 1         | 0.85%   |
| 4.19.0-6-amd64               | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 74        | 67.27%  |
| 5.16.0  | 10        | 9.09%   |
| 5.14.0  | 8         | 7.27%   |
| 5.18.0  | 6         | 5.45%   |
| 5.17.0  | 4         | 3.64%   |
| 6.0.0   | 3         | 2.73%   |
| 5.19.0  | 2         | 1.82%   |
| 5.15.0  | 1         | 0.91%   |
| 5.10.82 | 1         | 0.91%   |
| 4.19.0  | 1         | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 75        | 68.18%  |
| 5.16    | 10        | 9.09%   |
| 5.14    | 8         | 7.27%   |
| 5.18    | 6         | 5.45%   |
| 5.17    | 4         | 3.64%   |
| 6.0     | 3         | 2.73%   |
| 5.19    | 2         | 1.82%   |
| 5.15    | 1         | 0.91%   |
| 4.19    | 1         | 0.91%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 99        | 95.19%  |
| i686   | 5         | 4.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| XFCE          | 74        | 69.81%  |
| KDE5          | 22        | 20.75%  |
| Budgie        | 3         | 2.83%   |
| GNOME         | 2         | 1.89%   |
| Unknown       | 2         | 1.89%   |
| LXQt          | 1         | 0.94%   |
| i3            | 1         | 0.94%   |
| GNOME Classic | 1         | 0.94%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 102       | 98.08%  |
| Tty  | 2         | 1.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 84        | 80%     |
| SDDM    | 20        | 19.05%  |
| Unknown | 1         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 48.11%  |
| de_DE   | 16        | 15.09%  |
| it_IT   | 5         | 4.72%   |
| en_GB   | 5         | 4.72%   |
| ru_RU   | 4         | 3.77%   |
| fr_FR   | 3         | 2.83%   |
| Unknown | 3         | 2.83%   |
| pt_BR   | 2         | 1.89%   |
| es_ES   | 2         | 1.89%   |
| en_NZ   | 2         | 1.89%   |
| en_AU   | 2         | 1.89%   |
| tr_TR   | 1         | 0.94%   |
| sk_SK   | 1         | 0.94%   |
| pl_PL   | 1         | 0.94%   |
| nb_NO   | 1         | 0.94%   |
| id_ID   | 1         | 0.94%   |
| hu_HU   | 1         | 0.94%   |
| fi_FI   | 1         | 0.94%   |
| es_UY   | 1         | 0.94%   |
| es_PE   | 1         | 0.94%   |
| de_CH   | 1         | 0.94%   |
| bg_BG   | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 78        | 75%     |
| BIOS | 26        | 25%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 86        | 81.13%  |
| Overlay | 16        | 15.09%  |
| Btrfs   | 3         | 2.83%   |
| F2fs    | 1         | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 80        | 76.92%  |
| MBR     | 23        | 22.12%  |
| Unknown | 1         | 0.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 71.7%   |
| Yes       | 30        | 28.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 50.48%  |
| No        | 52        | 49.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 20        | 19.23%  |
| Dell                | 13        | 12.5%   |
| Hewlett-Packard     | 12        | 11.54%  |
| ASUSTek Computer    | 12        | 11.54%  |
| Apple               | 8         | 7.69%   |
| Sony                | 7         | 6.73%   |
| Acer                | 6         | 5.77%   |
| MSI                 | 4         | 3.85%   |
| Samsung Electronics | 3         | 2.88%   |
| Alienware           | 3         | 2.88%   |
| Medion              | 2         | 1.92%   |
| Gigabyte Technology | 2         | 1.92%   |
| Fujitsu Siemens     | 2         | 1.92%   |
| win element         | 1         | 0.96%   |
| Vulcan Electronics  | 1         | 0.96%   |
| TUXEDO              | 1         | 0.96%   |
| Toshiba             | 1         | 0.96%   |
| SANTECH             | 1         | 0.96%   |
| Notebook            | 1         | 0.96%   |
| Framework           | 1         | 0.96%   |
| efirstview          | 1         | 0.96%   |
| Chuwi               | 1         | 0.96%   |
| Unknown             | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Apple MacBookAir7,2                    | 2         | 1.92%   |
| Unknown                                | 2         | 1.92%   |
| win element MoreFine S500+             | 1         | 0.96%   |
| Vulcan Excursion XB                    | 1         | 0.96%   |
| TUXEDO N7x0WU                          | 1         | 0.96%   |
| Toshiba Satellite C845                 | 1         | 0.96%   |
| Sony VPCYB3V1E                         | 1         | 0.96%   |
| Sony VPCSB1V9R                         | 1         | 0.96%   |
| Sony VPCF119FX                         | 1         | 0.96%   |
| Sony VPCEH2N1E                         | 1         | 0.96%   |
| Sony VPCEC3S1E                         | 1         | 0.96%   |
| Sony VGN-TZ3RXN_B                      | 1         | 0.96%   |
| Sony SVE1513Q1ESI                      | 1         | 0.96%   |
| SANTECH X170KM-G                       | 1         | 0.96%   |
| Samsung NC210/NC110                    | 1         | 0.96%   |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 1         | 0.96%   |
| Samsung 340XAA/350XAA/550XAA           | 1         | 0.96%   |
| Notebook PD5x_7xPNP_PNN_PNT            | 1         | 0.96%   |
| MSI Modern 14 B11MOL                   | 1         | 0.96%   |
| MSI GV62 8RD                           | 1         | 0.96%   |
| MSI GF63 Thin 9SC                      | 1         | 0.96%   |
| MSI Alpha 15 B5EEK                     | 1         | 0.96%   |
| Medion E7424 MD60750                   | 1         | 0.96%   |
| Medion E14304                          | 1         | 0.96%   |
| Lenovo V15-IGL 82C3                    | 1         | 0.96%   |
| Lenovo ThinkPad X1 Extreme 20MF000TIX  | 1         | 0.96%   |
| Lenovo ThinkPad W541 20EG0005MS        | 1         | 0.96%   |
| Lenovo ThinkPad T560 20FJS0EP00        | 1         | 0.96%   |
| Lenovo ThinkPad T500 2241VL9           | 1         | 0.96%   |
| Lenovo ThinkPad T480 20L50004MZ        | 1         | 0.96%   |
| Lenovo ThinkPad T440p 20AW002VBR       | 1         | 0.96%   |
| Lenovo ThinkPad T430 23427YU           | 1         | 0.96%   |
| Lenovo ThinkPad T14s Gen 2i 20WM00A8GE | 1         | 0.96%   |
| Lenovo ThinkPad L512 44444WG           | 1         | 0.96%   |
| Lenovo ThinkPad E15 Gen 3 20YG008CUS   | 1         | 0.96%   |
| Lenovo ThinkBook 13s-IWL 20R9          | 1         | 0.96%   |
| Lenovo S130-11IGM 81J1                 | 1         | 0.96%   |
| Lenovo Legion 5 15ACH6H 82JU           | 1         | 0.96%   |
| Lenovo IdeaPad Y700-15ISK 80NV         | 1         | 0.96%   |
| Lenovo IdeaPad 5 15ITL05 82FG          | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 10        | 9.62%   |
| Dell Latitude        | 4         | 3.85%   |
| Lenovo IdeaPad       | 3         | 2.88%   |
| HP EliteBook         | 3         | 2.88%   |
| Dell Inspiron        | 3         | 2.88%   |
| HP ProBook           | 2         | 1.92%   |
| HP Laptop            | 2         | 1.92%   |
| Dell Vostro          | 2         | 1.92%   |
| Dell Precision       | 2         | 1.92%   |
| ASUS ROG             | 2         | 1.92%   |
| ASUS ASUS            | 2         | 1.92%   |
| Apple MacBookPro11   | 2         | 1.92%   |
| Apple MacBookAir7    | 2         | 1.92%   |
| Alienware m15        | 2         | 1.92%   |
| Acer Nitro           | 2         | 1.92%   |
| Acer Aspire          | 2         | 1.92%   |
| Unknown              | 2         | 1.92%   |
| win element MoreFine | 1         | 0.96%   |
| Vulcan Excursion     | 1         | 0.96%   |
| TUXEDO N7x0WU        | 1         | 0.96%   |
| Toshiba Satellite    | 1         | 0.96%   |
| Sony VPCYB3V1E       | 1         | 0.96%   |
| Sony VPCSB1V9R       | 1         | 0.96%   |
| Sony VPCF119FX       | 1         | 0.96%   |
| Sony VPCEH2N1E       | 1         | 0.96%   |
| Sony VPCEC3S1E       | 1         | 0.96%   |
| Sony VGN-TZ3RXN      | 1         | 0.96%   |
| Sony SVE1513Q1ESI    | 1         | 0.96%   |
| SANTECH X170KM-G     | 1         | 0.96%   |
| Samsung NC210        | 1         | 0.96%   |
| Samsung 350V5C       | 1         | 0.96%   |
| Samsung 340XAA       | 1         | 0.96%   |
| Notebook PD5x        | 1         | 0.96%   |
| MSI Modern           | 1         | 0.96%   |
| MSI GV62             | 1         | 0.96%   |
| MSI GF63             | 1         | 0.96%   |
| MSI Alpha            | 1         | 0.96%   |
| Medion E7424         | 1         | 0.96%   |
| Medion E14304        | 1         | 0.96%   |
| Lenovo V15-IGL       | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 18        | 17.31%  |
| 2015    | 11        | 10.58%  |
| 2018    | 9         | 8.65%   |
| 2011    | 9         | 8.65%   |
| 2020    | 8         | 7.69%   |
| 2010    | 7         | 6.73%   |
| 2013    | 6         | 5.77%   |
| 2019    | 5         | 4.81%   |
| 2017    | 5         | 4.81%   |
| 2016    | 5         | 4.81%   |
| 2012    | 5         | 4.81%   |
| 2022    | 3         | 2.88%   |
| 2014    | 3         | 2.88%   |
| 2008    | 3         | 2.88%   |
| 2007    | 3         | 2.88%   |
| 2009    | 1         | 0.96%   |
| 2006    | 1         | 0.96%   |
| 2005    | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 103       | 99.04%  |
| Enabled  | 1         | 0.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 31.73%  |
| 16.01-24.0  | 21        | 20.19%  |
| 8.01-16.0   | 16        | 15.38%  |
| 3.01-4.0    | 14        | 13.46%  |
| 32.01-64.0  | 7         | 6.73%   |
| 1.01-2.0    | 6         | 5.77%   |
| 2.01-3.0    | 3         | 2.88%   |
| 64.01-256.0 | 2         | 1.92%   |
| 24.01-32.0  | 1         | 0.96%   |
| 0.51-1.0    | 1         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 36        | 31.58%  |
| 2.01-3.0  | 30        | 26.32%  |
| 3.01-4.0  | 20        | 17.54%  |
| 4.01-8.0  | 15        | 13.16%  |
| 0.51-1.0  | 9         | 7.89%   |
| 8.01-16.0 | 3         | 2.63%   |
| 0.01-0.5  | 1         | 0.88%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 64.15%  |
| 2      | 27        | 25.47%  |
| 3      | 8         | 7.55%   |
| 0      | 2         | 1.89%   |
| 4      | 1         | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75        | 72.12%  |
| Yes       | 29        | 27.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 80.77%  |
| No        | 20        | 19.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 95.24%  |
| No        | 5         | 4.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 82.69%  |
| No        | 18        | 17.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 25        | 23.58%  |
| Germany     | 16        | 15.09%  |
| Italy       | 12        | 11.32%  |
| Canada      | 6         | 5.66%   |
| Brazil      | 4         | 3.77%   |
| Russia      | 3         | 2.83%   |
| France      | 3         | 2.83%   |
| Spain       | 2         | 1.89%   |
| Serbia      | 2         | 1.89%   |
| Poland      | 2         | 1.89%   |
| New Zealand | 2         | 1.89%   |
| Netherlands | 2         | 1.89%   |
| India       | 2         | 1.89%   |
| Belgium     | 2         | 1.89%   |
| Austria     | 2         | 1.89%   |
| Australia   | 2         | 1.89%   |
| Vietnam     | 1         | 0.94%   |
| Uruguay     | 1         | 0.94%   |
| UK          | 1         | 0.94%   |
| Turkey      | 1         | 0.94%   |
| Switzerland | 1         | 0.94%   |
| Slovakia    | 1         | 0.94%   |
| Romania     | 1         | 0.94%   |
| Peru        | 1         | 0.94%   |
| Norway      | 1         | 0.94%   |
| Malaysia    | 1         | 0.94%   |
| Indonesia   | 1         | 0.94%   |
| Hungary     | 1         | 0.94%   |
| Ghana       | 1         | 0.94%   |
| Finland     | 1         | 0.94%   |
| Egypt       | 1         | 0.94%   |
| Czechia     | 1         | 0.94%   |
| Bulgaria    | 1         | 0.94%   |
| Belarus     | 1         | 0.94%   |
| Azerbaijan  | 1         | 0.94%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Walled Lake    | 2         | 1.82%   |
| Vienna         | 2         | 1.82%   |
| St Petersburg  | 2         | 1.82%   |
| Orange         | 2         | 1.82%   |
| Montreal       | 2         | 1.82%   |
| Florence       | 2         | 1.82%   |
| Doesburg       | 2         | 1.82%   |
| Casale Litta   | 2         | 1.82%   |
| Canberra       | 2         | 1.82%   |
| Cambridge      | 2         | 1.82%   |
| Zurich         | 1         | 0.91%   |
| Wermelskirchen | 1         | 0.91%   |
| Waycross       | 1         | 0.91%   |
| Warsaw         | 1         | 0.91%   |
| Vasco da Gama  | 1         | 0.91%   |
| Vancouver      | 1         | 0.91%   |
| Uelzen         | 1         | 0.91%   |
| Tucson         | 1         | 0.91%   |
| Toulouse       | 1         | 0.91%   |
| Taggia         | 1         | 0.91%   |
| Tacoma         | 1         | 0.91%   |
| Sydney         | 1         | 0.91%   |
| Surprise       | 1         | 0.91%   |
| Stadtilm       | 1         | 0.91%   |
| Soest          | 1         | 0.91%   |
| Schaarbeek     | 1         | 0.91%   |
| Saskatoon      | 1         | 0.91%   |
| Saarlouis      | 1         | 0.91%   |
| Roseville      | 1         | 0.91%   |
| Rome           | 1         | 0.91%   |
| Rochester      | 1         | 0.91%   |
| Reinbek        | 1         | 0.91%   |
| Raleigh        | 1         | 0.91%   |
| Prague         | 1         | 0.91%   |
| Powder Springs | 1         | 0.91%   |
| Postbauer-Heng | 1         | 0.91%   |
| Portland       | 1         | 0.91%   |
| Plovdiv        | 1         | 0.91%   |
| Passau         | 1         | 0.91%   |
| Ottawa         | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 30     | 15.49%  |
| WDC                 | 17        | 17     | 11.97%  |
| Seagate             | 15        | 17     | 10.56%  |
| Crucial             | 11        | 21     | 7.75%   |
| Unknown             | 10        | 12     | 7.04%   |
| Kingston            | 10        | 10     | 7.04%   |
| SK hynix            | 7         | 8      | 4.93%   |
| Intel               | 6         | 8      | 4.23%   |
| Apple               | 6         | 8      | 4.23%   |
| Toshiba             | 5         | 5      | 3.52%   |
| Transcend           | 3         | 3      | 2.11%   |
| SanDisk             | 3         | 4      | 2.11%   |
| LITEON              | 3         | 3      | 2.11%   |
| Dogfish             | 3         | 3      | 2.11%   |
| SPCC                | 2         | 2      | 1.41%   |
| PNY                 | 2         | 2      | 1.41%   |
| Phison              | 2         | 2      | 1.41%   |
| Netac               | 2         | 2      | 1.41%   |
| Hitachi             | 2         | 3      | 1.41%   |
| Team                | 1         | 1      | 0.7%    |
| SABRENT             | 1         | 1      | 0.7%    |
| OCZ                 | 1         | 1      | 0.7%    |
| Micron Technology   | 1         | 1      | 0.7%    |
| KIOXIA              | 1         | 2      | 0.7%    |
| Indilinx            | 1         | 1      | 0.7%    |
| Gigabyte Technology | 1         | 1      | 0.7%    |
| GeIL                | 1         | 1      | 0.7%    |
| Fujitsu             | 1         | 1      | 0.7%    |
| Corsair             | 1         | 1      | 0.7%    |
| Unknown             | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown SD32G  32GB                  | 3         | 2.03%   |
| Samsung SSD 980 PRO 1TB              | 3         | 2.03%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.03%   |
| Crucial CT120BX500SSD1 120GB         | 3         | 2.03%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 1.35%   |
| SK hynix HFM512GDJTNI-82A0A 512GB    | 2         | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB       | 2         | 1.35%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.35%   |
| Samsung SSD 860 250GB                | 2         | 1.35%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 1.35%   |
| Kingston OM8PCP3512F-AI1 512GB       | 2         | 1.35%   |
| Dogfish SSD 128GB                    | 2         | 1.35%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 1.35%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 1.35%   |
| Apple SSD SM0128G 121GB              | 2         | 1.35%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.68%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.68%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 1         | 0.68%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.68%   |
| WDC WD5000LPVX-08V0TT5 500GB         | 1         | 0.68%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.68%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.68%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.68%   |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 0.68%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.68%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB   | 1         | 0.68%   |
| WDC PC SN730 NVMe 1024GB             | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-1T00-1032 1TB   | 1         | 0.68%   |
| WDC PC SN530 SDBPMPZ-512G-1001 512GB | 1         | 0.68%   |
| Unknown SDW32G  32GB                 | 1         | 0.68%   |
| Unknown SD08G  8GB                   | 1         | 0.68%   |
| Unknown SC64G  64GB                  | 1         | 0.68%   |
| Unknown NCard  32GB                  | 1         | 0.68%   |
| Unknown ISOCOM  64GB                 | 1         | 0.68%   |
| Unknown G1J38E  64GB                 | 1         | 0.68%   |
| Unknown ED2S5  128GB                 | 1         | 0.68%   |
| Unknown DA4064  64GB                 | 1         | 0.68%   |
| Unknown BJTD4R  32GB                 | 1         | 0.68%   |
| Transcend TS256GSSD370S 256GB        | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 17     | 50%     |
| WDC                 | 9         | 9      | 30%     |
| Toshiba             | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 3      | 6.67%   |
| Samsung Electronics | 1         | 1      | 3.33%   |
| Fujitsu             | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 20.69%  |
| Crucial             | 10        | 19     | 17.24%  |
| Kingston            | 5         | 5      | 8.62%   |
| Apple               | 5         | 7      | 8.62%   |
| Transcend           | 3         | 3      | 5.17%   |
| SanDisk             | 3         | 4      | 5.17%   |
| LITEON              | 3         | 3      | 5.17%   |
| Dogfish             | 3         | 3      | 5.17%   |
| SPCC                | 2         | 2      | 3.45%   |
| PNY                 | 2         | 2      | 3.45%   |
| Netac               | 2         | 2      | 3.45%   |
| WDC                 | 1         | 1      | 1.72%   |
| SK hynix            | 1         | 1      | 1.72%   |
| OCZ                 | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| Indilinx            | 1         | 1      | 1.72%   |
| Gigabyte Technology | 1         | 1      | 1.72%   |
| GeIL                | 1         | 1      | 1.72%   |
| Corsair             | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 49        | 74     | 38.28%  |
| NVMe | 38        | 52     | 29.69%  |
| HDD  | 30        | 33     | 23.44%  |
| MMC  | 11        | 13     | 8.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 68        | 107    | 57.63%  |
| NVMe | 38        | 51     | 32.2%   |
| MMC  | 11        | 13     | 9.32%   |
| SAS  | 1         | 1      | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 56        | 75     | 72.73%  |
| 0.51-1.0   | 19        | 30     | 24.68%  |
| 1.01-2.0   | 2         | 2      | 2.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 26.61%  |
| 251-500        | 24        | 22.02%  |
| 501-1000       | 15        | 13.76%  |
| 21-50          | 13        | 11.93%  |
| 51-100         | 10        | 9.17%   |
| 1-20           | 8         | 7.34%   |
| 1001-2000      | 6         | 5.5%    |
| More than 3000 | 2         | 1.83%   |
| 2001-3000      | 2         | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 46        | 41.07%  |
| 21-50          | 21        | 18.75%  |
| 51-100         | 13        | 11.61%  |
| 101-250        | 12        | 10.71%  |
| 251-500        | 11        | 9.82%   |
| 1001-2000      | 4         | 3.57%   |
| 501-1000       | 4         | 3.57%   |
| More than 3000 | 1         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 9.09%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 9.09%   |
| Seagate ST9320421AS 320GB                    | 1         | 1      | 9.09%   |
| Seagate ST9160821AS 160GB                    | 1         | 1      | 9.09%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 830 Series 128GB     | 1         | 1      | 9.09%   |
| Intel SSDPEKKF512G8L 512GB                   | 1         | 2      | 9.09%   |
| Indilinx IND-S325S120G 120GB SSD             | 1         | 1      | 9.09%   |
| Hitachi HTS545032B9A300 320GB                | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 36.36%  |
| WDC                 | 2         | 2      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Intel               | 1         | 2      | 9.09%   |
| Indilinx            | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| WDC     | 2         | 2      | 28.57%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 63.64%  |
| SSD  | 3         | 3      | 27.27%  |
| NVMe | 1         | 2      | 9.09%   |

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
| Works    | 88        | 144    | 77.88%  |
| Detected | 14        | 16     | 12.39%  |
| Malfunc  | 11        | 12     | 9.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 72        | 58.54%  |
| Samsung Electronics          | 14        | 11.38%  |
| SanDisk                      | 7         | 5.69%   |
| SK hynix                     | 6         | 4.88%   |
| Kingston Technology Company  | 5         | 4.07%   |
| AMD                          | 5         | 4.07%   |
| Phison Electronics           | 3         | 2.44%   |
| Nvidia                       | 3         | 2.44%   |
| KIOXIA                       | 3         | 2.44%   |
| Toshiba America Info Systems | 1         | 0.81%   |
| Silicon Image                | 1         | 0.81%   |
| Micron/Crucial Technology    | 1         | 0.81%   |
| Micron Technology            | 1         | 0.81%   |
| Marvell Technology Group     | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 9.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 3.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 3.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 3.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.05%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 4         | 3.05%   |
| SK hynix BC511                                                                 | 3         | 2.29%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 2.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.29%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 2.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 2.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.53%   |
| Samsung Electronics SATA controller                                            | 2         | 1.53%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.53%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.53%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.53%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.53%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.76%   |
| SK hynix Non-Volatile memory controller                                        | 1         | 0.76%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.76%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.76%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.76%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.76%   |
| Samsung Apple PCIe SSD                                                         | 1         | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.76%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.76%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                   | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 70        | 57.85%  |
| NVMe | 38        | 31.4%   |
| IDE  | 9         | 7.44%   |
| RAID | 4         | 3.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 89        | 85.58%  |
| AMD    | 15        | 14.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 4         | 3.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 3         | 2.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 3         | 2.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 2         | 1.92%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz       | 2         | 1.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 2         | 1.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 1.92%   |
| Intel Core i5-5350U CPU @ 1.80GHz        | 2         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 2         | 1.92%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 2         | 1.92%   |
| Intel 12th Gen Core i7-12700H            | 2         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 1.92%   |
| AMD Ryzen 9 5900HX with Radeon Graphics  | 2         | 1.92%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 1         | 0.96%   |
| Intel Pentium M processor 1.80GHz        | 1         | 0.96%   |
| Intel Genuine CPU T2300 @ 1.66GHz        | 1         | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 1         | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 1         | 0.96%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz       | 1         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 0.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 1         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 0.96%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz       | 1         | 0.96%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 1         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 1         | 0.96%   |
| Intel Core i7-3615QM CPU @ 2.30GHz       | 1         | 0.96%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 1         | 0.96%   |
| Intel Core i7-2640M CPU @ 2.80GHz        | 1         | 0.96%   |
| Intel Core i7-2630QM CPU @ 2.00GHz       | 1         | 0.96%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz        | 1         | 0.96%   |
| Intel Core i7 CPU M 620 @ 2.67GHz        | 1         | 0.96%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.96%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz        | 1         | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 1         | 0.96%   |
| Intel Core i5-4300M CPU @ 2.60GHz        | 1         | 0.96%   |
| Intel Core i5-4278U CPU @ 2.60GHz        | 1         | 0.96%   |
| Intel Core i5-3337U CPU @ 1.80GHz        | 1         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 26        | 25%     |
| Intel Core i5           | 20        | 19.23%  |
| Other                   | 11        | 10.58%  |
| Intel Core i3           | 10        | 9.62%   |
| Intel Celeron           | 10        | 9.62%   |
| AMD Ryzen 7             | 6         | 5.77%   |
| Intel Core 2 Duo        | 5         | 4.81%   |
| Intel Atom              | 4         | 3.85%   |
| AMD Ryzen 9             | 2         | 1.92%   |
| AMD Ryzen 5             | 2         | 1.92%   |
| Intel Pentium Silver    | 1         | 0.96%   |
| Intel Pentium M         | 1         | 0.96%   |
| Intel Genuine           | 1         | 0.96%   |
| AMD Turion 64 X2 Mobile | 1         | 0.96%   |
| AMD Sempron             | 1         | 0.96%   |
| AMD Ryzen 3             | 1         | 0.96%   |
| AMD E                   | 1         | 0.96%   |
| AMD A10                 | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 47.12%  |
| 4      | 34        | 32.69%  |
| 8      | 9         | 8.65%   |
| 6      | 7         | 6.73%   |
| 1      | 3         | 2.88%   |
| 14     | 2         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 78        | 75%     |
| 1      | 26        | 25%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 101       | 97.12%  |
| 32-bit         | 3         | 2.88%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 9.43%   |
| 0x206a7    | 9         | 8.49%   |
| 0x306a9    | 7         | 6.6%    |
| 0x806c1    | 6         | 5.66%   |
| 0x0a50000c | 5         | 4.72%   |
| 0x906ea    | 4         | 3.77%   |
| 0x806ea    | 4         | 3.77%   |
| 0x506e3    | 4         | 3.77%   |
| 0x406e3    | 4         | 3.77%   |
| 0xa0652    | 3         | 2.83%   |
| 0x306d4    | 3         | 2.83%   |
| 0x306c3    | 3         | 2.83%   |
| 0x30678    | 3         | 2.83%   |
| 0x20655    | 3         | 2.83%   |
| 0x906a3    | 2         | 1.89%   |
| 0x806e9    | 2         | 1.89%   |
| 0x706a8    | 2         | 1.89%   |
| 0x706a1    | 2         | 1.89%   |
| 0x6fd      | 2         | 1.89%   |
| 0x406c4    | 2         | 1.89%   |
| 0x1067a    | 2         | 1.89%   |
| 0x08608103 | 2         | 1.89%   |
| 0xa0671    | 1         | 0.94%   |
| 0x906ed    | 1         | 0.94%   |
| 0x906e9    | 1         | 0.94%   |
| 0x906c0    | 1         | 0.94%   |
| 0x806ec    | 1         | 0.94%   |
| 0x806eb    | 1         | 0.94%   |
| 0x806d1    | 1         | 0.94%   |
| 0x6fb      | 1         | 0.94%   |
| 0x6e8      | 1         | 0.94%   |
| 0x6d6      | 1         | 0.94%   |
| 0x506c9    | 1         | 0.94%   |
| 0x40661    | 1         | 0.94%   |
| 0x40651    | 1         | 0.94%   |
| 0x106e5    | 1         | 0.94%   |
| 0x106ca    | 1         | 0.94%   |
| 0x106c2    | 1         | 0.94%   |
| 0x0a50000b | 1         | 0.94%   |
| 0x08600106 | 1         | 0.94%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 14.42%  |
| SandyBridge      | 10        | 9.62%   |
| Skylake          | 8         | 7.69%   |
| IvyBridge        | 8         | 7.69%   |
| TigerLake        | 7         | 6.73%   |
| Zen 3            | 6         | 5.77%   |
| Silvermont       | 5         | 4.81%   |
| Haswell          | 5         | 4.81%   |
| Westmere         | 4         | 3.85%   |
| Goldmont plus    | 4         | 3.85%   |
| Icelake          | 3         | 2.88%   |
| Core             | 3         | 2.88%   |
| CometLake        | 3         | 2.88%   |
| Broadwell        | 3         | 2.88%   |
| Unknown          | 3         | 2.88%   |
| Zen+             | 2         | 1.92%   |
| Penryn           | 2         | 1.92%   |
| P6               | 2         | 1.92%   |
| Bonnell          | 2         | 1.92%   |
| Zen 2            | 1         | 0.96%   |
| Tremont          | 1         | 0.96%   |
| Nehalem          | 1         | 0.96%   |
| K8 Hammer        | 1         | 0.96%   |
| K8 & K10 hybrid  | 1         | 0.96%   |
| Goldmont         | 1         | 0.96%   |
| Excavator        | 1         | 0.96%   |
| Bobcat           | 1         | 0.96%   |
| Alderlake Hybrid | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 60.15%  |
| Nvidia | 34        | 25.56%  |
| AMD    | 19        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 6.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 5.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 5%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 3.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 2.86%   |
| Intel UHD Graphics 620                                                                   | 4         | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.86%   |
| Intel HD Graphics 530                                                                    | 4         | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 2.14%   |
| Intel HD Graphics 620                                                                    | 3         | 2.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 2.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 2.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 2.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 2.14%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 1.43%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.43%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.43%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.43%   |
| Intel HD Graphics 6000                                                                   | 2         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.43%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.43%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.43%   |
| AMD Lucienne                                                                             | 2         | 1.43%   |
| Nvidia TU117M                                                                            | 1         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.71%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.71%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.71%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.71%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.71%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.71%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                              | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 50.96%  |
| Intel + Nvidia | 22        | 21.15%  |
| 1 x Nvidia     | 9         | 8.65%   |
| 1 x AMD        | 9         | 8.65%   |
| Intel + AMD    | 4         | 3.85%   |
| 2 x AMD        | 3         | 2.88%   |
| AMD + Nvidia   | 3         | 2.88%   |
| 2 x Intel      | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 88        | 82.24%  |
| Proprietary | 14        | 13.08%  |
| Unknown     | 5         | 4.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 79.05%  |
| 0.01-0.5   | 9         | 8.57%   |
| 0.51-1.0   | 4         | 3.81%   |
| 7.01-8.0   | 3         | 2.86%   |
| 3.01-4.0   | 3         | 2.86%   |
| 1.01-2.0   | 2         | 1.9%    |
| 2.01-3.0   | 1         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 22        | 18.97%  |
| Chimei Innolux          | 15        | 12.93%  |
| Samsung Electronics     | 12        | 10.34%  |
| BOE                     | 12        | 10.34%  |
| LG Display              | 11        | 9.48%   |
| Apple                   | 7         | 6.03%   |
| Chi Mei Optoelectronics | 5         | 4.31%   |
| Sharp                   | 4         | 3.45%   |
| PANDA                   | 4         | 3.45%   |
| Hewlett-Packard         | 4         | 3.45%   |
| Lenovo                  | 3         | 2.59%   |
| Goldstar                | 3         | 2.59%   |
| Sony                    | 2         | 1.72%   |
| Ancor Communications    | 2         | 1.72%   |
| Sunplus                 | 1         | 0.86%   |
| STA                     | 1         | 0.86%   |
| Philips                 | 1         | 0.86%   |
| Panasonic               | 1         | 0.86%   |
| Packard Bell            | 1         | 0.86%   |
| LTM                     | 1         | 0.86%   |
| InfoVision              | 1         | 0.86%   |
| Eizo                    | 1         | 0.86%   |
| Dell                    | 1         | 0.86%   |
| CPT                     | 1         | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 1.72%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 1.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 2         | 1.72%   |
| Sunplus Monitor TV SPVFFFF 1920x1080 376x301mm 19.0-inch                 | 1         | 0.86%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                     | 1         | 0.86%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.86%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch    | 1         | 0.86%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 1         | 0.86%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.86%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch                  | 1         | 0.86%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch                  | 1         | 0.86%   |
| Samsung Electronics SyncMaster SAM0458 1360x768                          | 1         | 0.86%   |
| Samsung Electronics S24H85x SAM0E0C 2560x1440 527x296mm 23.8-inch        | 1         | 0.86%   |
| Samsung Electronics S23B300 SAM08AF 1920x1080 510x287mm 23.0-inch        | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC4650 1400x1050 304x228mm 15.0-inch    | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC4245 1280x800 331x207mm 15.4-inch     | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM7002 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch    | 1         | 0.86%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 1         | 0.86%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 1         | 0.86%   |
| PANDA LCD Monitor NCP0052 1920x1080 309x174mm 14.0-inch                  | 1         | 0.86%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 1         | 0.86%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 1         | 0.86%   |
| Packard Bell Viseo 230Ws PKB00C1 1920x1080 509x286mm 23.0-inch           | 1         | 0.86%   |
| LTM LCD_VGA LTM0659 1920x1080 886x498mm 40.0-inch                        | 1         | 0.86%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 0.86%   |
| LG Display LCD Monitor LGD06E2 1920x1080 344x194mm 15.5-inch             | 1         | 0.86%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch             | 1         | 0.86%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 1         | 0.86%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch             | 1         | 0.86%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch              | 1         | 0.86%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 1         | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 44.04%  |
| 1366x768 (WXGA)    | 28        | 25.69%  |
| 3840x2160 (4K)     | 8         | 7.34%   |
| 2880x1800          | 3         | 2.75%   |
| 1600x900 (HD+)     | 3         | 2.75%   |
| 1280x800 (WXGA)    | 3         | 2.75%   |
| 2560x1080          | 2         | 1.83%   |
| 1920x1200 (WUXGA)  | 2         | 1.83%   |
| 1440x900 (WXGA+)   | 2         | 1.83%   |
| 3840x2400          | 1         | 0.92%   |
| 2560x1600          | 1         | 0.92%   |
| 2560x1440 (QHD)    | 1         | 0.92%   |
| 2256x1504          | 1         | 0.92%   |
| 2160x1440          | 1         | 0.92%   |
| 1680x1050 (WSXGA+) | 1         | 0.92%   |
| 1400x1050          | 1         | 0.92%   |
| 1360x768           | 1         | 0.92%   |
| 1280x1024 (SXGA)   | 1         | 0.92%   |
| 1024x600           | 1         | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 50        | 43.1%   |
| 13      | 12        | 10.34%  |
| 17      | 11        | 9.48%   |
| 14      | 10        | 8.62%   |
| 11      | 7         | 6.03%   |
| 24      | 6         | 5.17%   |
| 23      | 4         | 3.45%   |
| 19      | 3         | 2.59%   |
| 34      | 2         | 1.72%   |
| 27      | 2         | 1.72%   |
| 21      | 2         | 1.72%   |
| 84      | 1         | 0.86%   |
| 46      | 1         | 0.86%   |
| 40      | 1         | 0.86%   |
| 25      | 1         | 0.86%   |
| 16      | 1         | 0.86%   |
| 10      | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 54.78%  |
| 201-300     | 16        | 13.91%  |
| 351-400     | 15        | 13.04%  |
| 501-600     | 12        | 10.43%  |
| 401-500     | 3         | 2.61%   |
| 701-800     | 2         | 1.74%   |
| 801-900     | 1         | 0.87%   |
| 1501-2000   | 1         | 0.87%   |
| 1001-1500   | 1         | 0.87%   |
| Unknown     | 1         | 0.87%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 82        | 78.85%  |
| 16/10 | 15        | 14.42%  |
| 5/4   | 2         | 1.92%   |
| 3/2   | 2         | 1.92%   |
| 21/9  | 2         | 1.92%   |
| 4/3   | 1         | 0.96%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 43.97%  |
| 81-90          | 19        | 16.38%  |
| 121-130        | 11        | 9.48%   |
| 201-250        | 9         | 7.76%   |
| 51-60          | 7         | 6.03%   |
| 151-200        | 4         | 3.45%   |
| 71-80          | 3         | 2.59%   |
| 251-300        | 3         | 2.59%   |
| 351-500        | 2         | 1.72%   |
| 301-350        | 2         | 1.72%   |
| 501-1000       | 2         | 1.72%   |
| More than 1000 | 1         | 0.86%   |
| 41-50          | 1         | 0.86%   |
| Unknown        | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 49        | 43.75%  |
| 101-120       | 24        | 21.43%  |
| 51-100        | 23        | 20.54%  |
| 161-240       | 8         | 7.14%   |
| More than 240 | 6         | 5.36%   |
| 1-50          | 1         | 0.89%   |
| Unknown       | 1         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 82        | 76.64%  |
| 2     | 17        | 15.89%  |
| 0     | 5         | 4.67%   |
| 3     | 3         | 2.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 57        | 33.33%  |
| Intel                    | 55        | 32.16%  |
| Qualcomm Atheros         | 23        | 13.45%  |
| Broadcom                 | 8         | 4.68%   |
| Marvell Technology Group | 5         | 2.92%   |
| Broadcom Limited         | 5         | 2.92%   |
| TP-Link                  | 4         | 2.34%   |
| MediaTek                 | 4         | 2.34%   |
| Nvidia                   | 2         | 1.17%   |
| Sierra Wireless          | 1         | 0.58%   |
| Samsung Electronics      | 1         | 0.58%   |
| Ralink Technology        | 1         | 0.58%   |
| Ralink                   | 1         | 0.58%   |
| NetGear                  | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| Dell                     | 1         | 0.58%   |
| ASUSTek Computer         | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 37        | 18.32%  |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 3.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.48%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.48%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.98%   |
| Intel Wireless 8260                                                     | 4         | 1.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.49%   |
| Intel Wireless 7260                                                     | 3         | 1.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.49%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.49%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.99%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.99%   |
| Intel Wireless 3165                                                     | 2         | 0.99%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.99%   |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.99%   |
| Intel Ethernet Connection (5) I219-LM                                   | 2         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 0.99%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.5%    |
| Sierra Wireless EM7455                                                  | 1         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.5%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 48.65%  |
| Realtek Semiconductor | 17        | 15.32%  |
| Qualcomm Atheros      | 17        | 15.32%  |
| Broadcom              | 6         | 5.41%   |
| Broadcom Limited      | 5         | 4.5%    |
| MediaTek              | 4         | 3.6%    |
| TP-Link               | 3         | 2.7%    |
| Sierra Wireless       | 1         | 0.9%    |
| Ralink Technology     | 1         | 0.9%    |
| Ralink                | 1         | 0.9%    |
| NetGear               | 1         | 0.9%    |
| ASUSTek Computer      | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 8         | 7.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.5%    |
| Intel Wireless 8265 / 8275                                              | 5         | 4.5%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 4.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.6%    |
| Intel Wireless 8260                                                     | 4         | 3.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.7%    |
| Intel Wireless 7260                                                     | 3         | 2.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 2.7%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 2         | 1.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.8%    |
| Intel Wireless 3165                                                     | 2         | 1.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.8%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.9%    |
| Sierra Wireless EM7455                                                  | 1         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.9%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.9%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.9%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.9%    |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.9%    |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.9%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.9%    |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 51        | 57.95%  |
| Intel                    | 15        | 17.05%  |
| Qualcomm Atheros         | 9         | 10.23%  |
| Marvell Technology Group | 5         | 5.68%   |
| Broadcom                 | 3         | 3.41%   |
| Nvidia                   | 2         | 2.27%   |
| TP-Link                  | 1         | 1.14%   |
| Samsung Electronics      | 1         | 1.14%   |
| Lenovo                   | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 37        | 41.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 7.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 6.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 2.22%   |
| Intel Ethernet Connection I219-V                                               | 2         | 2.22%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 2.22%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 2.22%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.22%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 1.11%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.11%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.11%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 1.11%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.11%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.11%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.11%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.11%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.11%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.11%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 1.11%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 1.11%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.11%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 1.11%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 1.11%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 1.11%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.11%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.11%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.11%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 1.11%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 1.11%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 54.05%  |
| Ethernet | 84        | 45.41%  |
| Modem    | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 75.23%  |
| Ethernet | 27        | 24.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 76        | 72.38%  |
| 1     | 25        | 23.81%  |
| 0     | 3         | 2.86%   |
| 3     | 1         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 72.38%  |
| Yes  | 29        | 27.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 48.86%  |
| Qualcomm Atheros Communications | 9         | 10.23%  |
| Realtek Semiconductor           | 7         | 7.95%   |
| Apple                           | 7         | 7.95%   |
| Broadcom                        | 5         | 5.68%   |
| Foxconn / Hon Hai               | 4         | 4.55%   |
| IMC Networks                    | 3         | 3.41%   |
| Cambridge Silicon Radio         | 3         | 3.41%   |
| Ralink                          | 1         | 1.14%   |
| MediaTek                        | 1         | 1.14%   |
| Lite-On Technology              | 1         | 1.14%   |
| Hewlett-Packard                 | 1         | 1.14%   |
| Dell                            | 1         | 1.14%   |
| ASUSTek Computer                | 1         | 1.14%   |
| Alps Electric                   | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 17.05%  |
| Intel AX201 Bluetooth                                                               | 8         | 9.09%   |
| Intel AX200 Bluetooth                                                               | 8         | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 7.95%   |
| Realtek Bluetooth Radio                                                             | 6         | 6.82%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 5.68%   |
| Apple Bluetooth Host Controller                                                     | 4         | 4.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 3.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 3.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.27%   |
| IMC Networks Wireless_Device                                                        | 2         | 2.27%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.14%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.14%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.14%   |
| MediaTek Wireless_Device                                                            | 1         | 1.14%   |
| Lite-On Wireless_Device                                                             | 1         | 1.14%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.14%   |
| Intel Bluetooth Device                                                              | 1         | 1.14%   |
| Intel AX210 Bluetooth                                                               | 1         | 1.14%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.14%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.14%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.14%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.14%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.14%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 1.14%   |
| Apple Bluetooth HCI                                                                 | 1         | 1.14%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 86        | 62.32%  |
| Nvidia                  | 27        | 19.57%  |
| AMD                     | 15        | 10.87%  |
| Realtek Semiconductor   | 2         | 1.45%   |
| Texas Instruments       | 1         | 0.72%   |
| Plantronics             | 1         | 0.72%   |
| Logitech                | 1         | 0.72%   |
| Lenovo                  | 1         | 0.72%   |
| FIFINE 683 Microphone   | 1         | 0.72%   |
| CMX Systems             | 1         | 0.72%   |
| C-Media Electronics     | 1         | 0.72%   |
| BEHRINGER International | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 7.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 6.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 6.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 4.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.16%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 2.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.9%    |
| Nvidia Audio device                                                                               | 3         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.9%    |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.9%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.9%    |
| Realtek Semiconductor USB Audio                                                                   | 2         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.27%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.27%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 1.27%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.63%   |
| Plantronics BT600                                                                                 | 1         | 0.63%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.63%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.63%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.63%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 28        | 22.95%  |
| Samsung Electronics | 28        | 22.95%  |
| Unknown             | 15        | 12.3%   |
| Kingston            | 13        | 10.66%  |
| Micron Technology   | 10        | 8.2%    |
| Crucial             | 8         | 6.56%   |
| Corsair             | 3         | 2.46%   |
| Unknown (ABCD)      | 2         | 1.64%   |
| Smart               | 2         | 1.64%   |
| Elpida              | 2         | 1.64%   |
| Transcend           | 1         | 0.82%   |
| Team                | 1         | 0.82%   |
| Ramaxel Technology  | 1         | 0.82%   |
| PNY                 | 1         | 0.82%   |
| Nanya Technology    | 1         | 0.82%   |
| Innodisk            | 1         | 0.82%   |
| Avant               | 1         | 0.82%   |
| ASint Technology    | 1         | 0.82%   |
| A-DATA Technology   | 1         | 0.82%   |
| 48spaces            | 1         | 0.82%   |
| Unknown             | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 3.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 2.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 2.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.27%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 2         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 1.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.52%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.52%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.52%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.52%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.52%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.52%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.52%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 1         | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR3 1333MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.76%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.76%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.76%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| Smart RAM SF4641G8CK8IEGKSBG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.76%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.76%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT351S6AFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 45        | 42.86%  |
| DDR3   | 43        | 40.95%  |
| LPDDR4 | 5         | 4.76%   |
| DDR2   | 5         | 4.76%   |
| DDR    | 3         | 2.86%   |
| SDRAM  | 1         | 0.95%   |
| LPDDR3 | 1         | 0.95%   |
| DRAM   | 1         | 0.95%   |
| DDR5   | 1         | 0.95%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 93.33%  |
| Row Of Chips | 6         | 5.71%   |
| DIMM         | 1         | 0.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 47        | 40.52%  |
| 4096  | 37        | 31.9%   |
| 2048  | 17        | 14.66%  |
| 16384 | 9         | 7.76%   |
| 1024  | 4         | 3.45%   |
| 32768 | 2         | 1.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 25        | 22.32%  |
| 3200    | 21        | 18.75%  |
| 2400    | 13        | 11.61%  |
| 2667    | 12        | 10.71%  |
| 1333    | 9         | 8.04%   |
| Unknown | 8         | 7.14%   |
| 2133    | 5         | 4.46%   |
| 1334    | 5         | 4.46%   |
| 667     | 5         | 4.46%   |
| 4267    | 2         | 1.79%   |
| 1067    | 2         | 1.79%   |
| 8400    | 1         | 0.89%   |
| 4800    | 1         | 0.89%   |
| 4199    | 1         | 0.89%   |
| 2933    | 1         | 0.89%   |
| 166     | 1         | 0.89%   |

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
| Chicony Electronics                    | 16        | 19.05%  |
| Microdia                               | 11        | 13.1%   |
| Acer                                   | 11        | 13.1%   |
| Realtek Semiconductor                  | 8         | 9.52%   |
| IMC Networks                           | 5         | 5.95%   |
| Sunplus Innovation Technology          | 4         | 4.76%   |
| Quanta                                 | 4         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.76%   |
| Ricoh                                  | 3         | 3.57%   |
| Lite-On Technology                     | 3         | 3.57%   |
| Apple                                  | 3         | 3.57%   |
| Suyin                                  | 2         | 2.38%   |
| Silicon Motion                         | 2         | 2.38%   |
| Z-Star Microelectronics                | 1         | 1.19%   |
| Y Media                                | 1         | 1.19%   |
| Primax Electronics                     | 1         | 1.19%   |
| Luxvisions Innotech Limited            | 1         | 1.19%   |
| Logitech                               | 1         | 1.19%   |
| Lenovo                                 | 1         | 1.19%   |
| Goodong Industry                       | 1         | 1.19%   |
| Alcor Micro                            | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 5         | 5.88%   |
| Chicony Integrated Camera                           | 3         | 3.53%   |
| Acer BisonCam,NB Pro                                | 3         | 3.53%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.35%   |
| Quanta HD User Facing                               | 2         | 2.35%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.35%   |
| IMC Networks Integrated Camera                      | 2         | 2.35%   |
| Chicony HD User Facing                              | 2         | 2.35%   |
| Acer Integrated Camera                              | 2         | 2.35%   |
| Acer HD Webcam                                      | 2         | 2.35%   |
| Acer BisonCam, NB Pro                               | 2         | 2.35%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.18%   |
| Y Media USB Camera                                  | 1         | 1.18%   |
| Suyin Sony Visual Communication Camera              | 1         | 1.18%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.18%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.18%   |
| Sunplus ASUS Webcam                                 | 1         | 1.18%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 1.18%   |
| Silicon Motion Web Camera                           | 1         | 1.18%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 1.18%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.18%   |
| Ricoh Integrated Webcam                             | 1         | 1.18%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.18%   |
| Realtek USB Camera                                  | 1         | 1.18%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.18%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.18%   |
| Realtek Integrated Webcam HD                        | 1         | 1.18%   |
| Realtek Integrated Webcam                           | 1         | 1.18%   |
| Realtek EasyCamera                                  | 1         | 1.18%   |
| Realtek Built-In Video Camera                       | 1         | 1.18%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.18%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.18%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 1.18%   |
| Microdia Webcam Vitade AF                           | 1         | 1.18%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 1.18%   |
| Microdia Webcam                                     | 1         | 1.18%   |
| Microdia USB 2.0 Camera                             | 1         | 1.18%   |
| Microdia Sony Visual Communication Camera           | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_2HDM              | 1         | 1.18%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Synaptics                  | 3         | 20%     |
| Shenzhen Goodix Technology | 3         | 20%     |
| Upek                       | 2         | 13.33%  |
| AuthenTec                  | 2         | 13.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 20%     |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 20%     |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 13.33%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 13.33%  |
| Upek TCS5B Fingerprint sensor                          | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| AuthenTec AES2810                                      | 1         | 6.67%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 6.67%   |
| Unknown                                                | 1         | 6.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 44.44%  |
| Alcor Micro           | 3         | 33.33%  |
| Advanced Card Systems | 2         | 22.22%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 66        | 60.55%  |
| 1     | 31        | 28.44%  |
| 2     | 11        | 10.09%  |
| 3     | 1         | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 24        | 47.06%  |
| Fingerprint reader    | 15        | 29.41%  |
| Chipcard              | 7         | 13.73%  |
| Multimedia controller | 3         | 5.88%   |
| Net/ethernet          | 1         | 1.96%   |
| Camera                | 1         | 1.96%   |

