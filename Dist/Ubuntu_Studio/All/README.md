Ubuntu Studio - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Studio/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Studio/Notebook/README.md).

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

Total: 296

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3728 SDK0J40709 WIN 3259... | Desktop     | [04c0c560d4](https://linux-hardware.org/?probe=04c0c560d4) | Jan 03, 2025 |
| MSI           | Prestige 13 AI+ Evo A2VM... | Notebook    | [e0ef8014cc](https://linux-hardware.org/?probe=e0ef8014cc) | Dec 31, 2024 |
| ASUSTek       | N750JV                      | Notebook    | [39dd282ac2](https://linux-hardware.org/?probe=39dd282ac2) | Dec 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [ee3d394ad4](https://linux-hardware.org/?probe=ee3d394ad4) | Dec 22, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [0a76d54f2a](https://linux-hardware.org/?probe=0a76d54f2a) | Dec 11, 2024 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [27824c7505](https://linux-hardware.org/?probe=27824c7505) | Dec 09, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [9e14504376](https://linux-hardware.org/?probe=9e14504376) | Dec 02, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [0dc0dd7a62](https://linux-hardware.org/?probe=0dc0dd7a62) | Nov 20, 2024 |
| MSI           | Z370 PC PRO                 | Desktop     | [518166326c](https://linux-hardware.org/?probe=518166326c) | Nov 11, 2024 |
| ASRock        | H97M Pro4                   | Desktop     | [c694317e1f](https://linux-hardware.org/?probe=c694317e1f) | Nov 08, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7ae1cb1ad0](https://linux-hardware.org/?probe=7ae1cb1ad0) | Nov 01, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [a1c6d79081](https://linux-hardware.org/?probe=a1c6d79081) | Oct 23, 2024 |
| Sony          | VPCCB3C5E                   | Notebook    | [32c8a0fd43](https://linux-hardware.org/?probe=32c8a0fd43) | Oct 23, 2024 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [1bf6907ed6](https://linux-hardware.org/?probe=1bf6907ed6) | Oct 20, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [8132169207](https://linux-hardware.org/?probe=8132169207) | Oct 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [d875e5f8df](https://linux-hardware.org/?probe=d875e5f8df) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ffd8af5438](https://linux-hardware.org/?probe=ffd8af5438) | Sep 25, 2024 |
| Lenovo        | ThinkCentre M58p 7220RY8    | Desktop     | [9a160a771d](https://linux-hardware.org/?probe=9a160a771d) | Sep 16, 2024 |
| Alienware     | 01NYPT A00                  | Desktop     | [953351e395](https://linux-hardware.org/?probe=953351e395) | Aug 31, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [ce7cf8209e](https://linux-hardware.org/?probe=ce7cf8209e) | Aug 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [7d197b82ba](https://linux-hardware.org/?probe=7d197b82ba) | Aug 29, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b6ee09c245](https://linux-hardware.org/?probe=b6ee09c245) | Aug 14, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [53a28ccde0](https://linux-hardware.org/?probe=53a28ccde0) | Aug 14, 2024 |
| Lenovo        | ThinkPad T450s 20BWS0X00... | Notebook    | [a6f146c7b7](https://linux-hardware.org/?probe=a6f146c7b7) | Aug 09, 2024 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [a1636d9c36](https://linux-hardware.org/?probe=a1636d9c36) | Aug 01, 2024 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [337a3488ce](https://linux-hardware.org/?probe=337a3488ce) | Aug 01, 2024 |
| HP            | 2B16                        | Desktop     | [f8836660b7](https://linux-hardware.org/?probe=f8836660b7) | Jul 24, 2024 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [0b60161050](https://linux-hardware.org/?probe=0b60161050) | Jul 24, 2024 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [93e318f098](https://linux-hardware.org/?probe=93e318f098) | Jul 24, 2024 |
| Dell          | Precision 5520              | Notebook    | [d7b6062639](https://linux-hardware.org/?probe=d7b6062639) | Jul 21, 2024 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [e3507bd66f](https://linux-hardware.org/?probe=e3507bd66f) | Jul 08, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [34e04923f3](https://linux-hardware.org/?probe=34e04923f3) | Jun 28, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [54b86a5399](https://linux-hardware.org/?probe=54b86a5399) | Jun 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [a3ffc85576](https://linux-hardware.org/?probe=a3ffc85576) | Jun 21, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [0bf1e098c0](https://linux-hardware.org/?probe=0bf1e098c0) | Jun 19, 2024 |
| Lenovo        | IdeaPad Slim 3 16IAH8 83... | Notebook    | [ae3b8db2e7](https://linux-hardware.org/?probe=ae3b8db2e7) | Jun 18, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [eec5a148c0](https://linux-hardware.org/?probe=eec5a148c0) | Jun 14, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [fb0d42ccdd](https://linux-hardware.org/?probe=fb0d42ccdd) | Jun 13, 2024 |
| Dell          | Latitude 3450               | Notebook    | [c7b7155c10](https://linux-hardware.org/?probe=c7b7155c10) | Jun 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [1d8af97b78](https://linux-hardware.org/?probe=1d8af97b78) | May 15, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [87a9fcc5ab](https://linux-hardware.org/?probe=87a9fcc5ab) | May 12, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [134f7ad848](https://linux-hardware.org/?probe=134f7ad848) | May 10, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [4ccd0953dd](https://linux-hardware.org/?probe=4ccd0953dd) | May 09, 2024 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [a62c895461](https://linux-hardware.org/?probe=a62c895461) | Apr 26, 2024 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [25245adc43](https://linux-hardware.org/?probe=25245adc43) | Apr 26, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1572659f68](https://linux-hardware.org/?probe=1572659f68) | Apr 24, 2024 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [0d6a3363b8](https://linux-hardware.org/?probe=0d6a3363b8) | Apr 15, 2024 |
| ASUSTek       | P5WDG2 WS Pro               | Desktop     | [c370aff195](https://linux-hardware.org/?probe=c370aff195) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [b3cf1a2d4e](https://linux-hardware.org/?probe=b3cf1a2d4e) | Apr 05, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [ddd85b18e6](https://linux-hardware.org/?probe=ddd85b18e6) | Apr 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [cf518d2630](https://linux-hardware.org/?probe=cf518d2630) | Mar 10, 2024 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [bf844ef78f](https://linux-hardware.org/?probe=bf844ef78f) | Mar 09, 2024 |
| Lenovo        | ThinkPad L540 20AV004VGE    | Notebook    | [05d6a4d686](https://linux-hardware.org/?probe=05d6a4d686) | Feb 03, 2024 |
| Dell          | Latitude E6420              | Notebook    | [f4dcc8c239](https://linux-hardware.org/?probe=f4dcc8c239) | Jan 26, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [efa0303d01](https://linux-hardware.org/?probe=efa0303d01) | Jan 24, 2024 |
| Dell          | Inspiron 3482               | Notebook    | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| ASUSTek       | P5G41-M                     | Desktop     | [cbab9e248d](https://linux-hardware.org/?probe=cbab9e248d) | Dec 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| Intel         | Unknown                     | Desktop     | [3ae9554945](https://linux-hardware.org/?probe=3ae9554945) | Dec 05, 2023 |
| Dell          | 0PRR48 A01                  | Desktop     | [0942eb512e](https://linux-hardware.org/?probe=0942eb512e) | Nov 30, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
| Dell          | System XPS L502X            | Notebook    | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Gigabyte      | H270-HD3P-CF                | Desktop     | [43fedd61b1](https://linux-hardware.org/?probe=43fedd61b1) | Oct 23, 2023 |
| Gigabyte      | H270-HD3P-CF                | Desktop     | [22baba8799](https://linux-hardware.org/?probe=22baba8799) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | Notebook    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [188b107eb5](https://linux-hardware.org/?probe=188b107eb5) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e1caa679f](https://linux-hardware.org/?probe=7e1caa679f) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a57428971](https://linux-hardware.org/?probe=5a57428971) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bab5438645](https://linux-hardware.org/?probe=bab5438645) | Sep 22, 2023 |
| HP            | 829A                        | Mini pc     | [52aac4ac46](https://linux-hardware.org/?probe=52aac4ac46) | Sep 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [794f6d999a](https://linux-hardware.org/?probe=794f6d999a) | Sep 12, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [69bf752a4a](https://linux-hardware.org/?probe=69bf752a4a) | Sep 06, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [17136ed242](https://linux-hardware.org/?probe=17136ed242) | Aug 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fcfb9cd970](https://linux-hardware.org/?probe=fcfb9cd970) | Aug 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c3490914f6](https://linux-hardware.org/?probe=c3490914f6) | Aug 26, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [499c14b0f7](https://linux-hardware.org/?probe=499c14b0f7) | Aug 26, 2023 |
| Toshiba       | Satellite A505              | Notebook    | [a7b1465809](https://linux-hardware.org/?probe=a7b1465809) | Aug 25, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | Notebook    | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [50ee937fb2](https://linux-hardware.org/?probe=50ee937fb2) | Aug 02, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [c04f6d6467](https://linux-hardware.org/?probe=c04f6d6467) | Aug 01, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [d3718d1a8d](https://linux-hardware.org/?probe=d3718d1a8d) | Jul 16, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [60e43d39b2](https://linux-hardware.org/?probe=60e43d39b2) | Jul 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97ebfed554](https://linux-hardware.org/?probe=97ebfed554) | Jul 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [57d511fdb3](https://linux-hardware.org/?probe=57d511fdb3) | Jun 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV03     | Notebook    | [c2a4d4d2c0](https://linux-hardware.org/?probe=c2a4d4d2c0) | Jun 17, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5a1b8d9fd3](https://linux-hardware.org/?probe=5a1b8d9fd3) | Jun 04, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | Notebook    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [bffa46ef83](https://linux-hardware.org/?probe=bffa46ef83) | May 07, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [cbf9d11153](https://linux-hardware.org/?probe=cbf9d11153) | May 07, 2023 |
| ECS           | H410-SF110                  | Desktop     | [5e5011bdd3](https://linux-hardware.org/?probe=5e5011bdd3) | May 07, 2023 |
| HP            | 1495                        | Desktop     | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| DEPO Compu... | MS-7846                     | Desktop     | [bf72733735](https://linux-hardware.org/?probe=bf72733735) | Apr 13, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [2743830739](https://linux-hardware.org/?probe=2743830739) | Apr 11, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6347cdcf9c](https://linux-hardware.org/?probe=6347cdcf9c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3ce456f3c8](https://linux-hardware.org/?probe=3ce456f3c8) | Mar 25, 2023 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | Desktop     | [a2c287936d](https://linux-hardware.org/?probe=a2c287936d) | Mar 24, 2023 |
| Lenovo        | ThinkPad X250 20CL001LMB    | Notebook    | [d78880e600](https://linux-hardware.org/?probe=d78880e600) | Mar 17, 2023 |
| HP            | Pavilion dv8                | Notebook    | [105a616a39](https://linux-hardware.org/?probe=105a616a39) | Mar 14, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [8553f4abea](https://linux-hardware.org/?probe=8553f4abea) | Mar 13, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [7d9e6e46db](https://linux-hardware.org/?probe=7d9e6e46db) | Mar 13, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [257b3941af](https://linux-hardware.org/?probe=257b3941af) | Mar 10, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | TP300UA                     | Notebook    | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| Dell          | Latitude 5511               | Notebook    | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c63c663181](https://linux-hardware.org/?probe=c63c663181) | Jan 30, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| HP            | 1497                        | Desktop     | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [db3b391bd0](https://linux-hardware.org/?probe=db3b391bd0) | Jan 20, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [3140672f28](https://linux-hardware.org/?probe=3140672f28) | Jan 10, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [f36c085389](https://linux-hardware.org/?probe=f36c085389) | Dec 25, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [9d689be2ab](https://linux-hardware.org/?probe=9d689be2ab) | Dec 11, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [a888eb38b3](https://linux-hardware.org/?probe=a888eb38b3) | Dec 01, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [78defd6c12](https://linux-hardware.org/?probe=78defd6c12) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [b76898d624](https://linux-hardware.org/?probe=b76898d624) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [5147db88ea](https://linux-hardware.org/?probe=5147db88ea) | Nov 14, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
| HP            | 09F8h                       | Desktop     | [f1107e91f2](https://linux-hardware.org/?probe=f1107e91f2) | Nov 01, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | Desktop     | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [55771f0c33](https://linux-hardware.org/?probe=55771f0c33) | Oct 18, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [7e0028c2fa](https://linux-hardware.org/?probe=7e0028c2fa) | Oct 18, 2022 |
| Gigabyte      | X79S-UP5                    | Desktop     | [62f59af32c](https://linux-hardware.org/?probe=62f59af32c) | Oct 15, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2dc3febd4d](https://linux-hardware.org/?probe=2dc3febd4d) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [5b39dcf114](https://linux-hardware.org/?probe=5b39dcf114) | Sep 19, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [b1d97f239e](https://linux-hardware.org/?probe=b1d97f239e) | Sep 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de37b9cf96](https://linux-hardware.org/?probe=de37b9cf96) | Sep 13, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [d6d8f577e0](https://linux-hardware.org/?probe=d6d8f577e0) | Sep 12, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [07428c96e1](https://linux-hardware.org/?probe=07428c96e1) | Sep 11, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a23b4a8cd4](https://linux-hardware.org/?probe=a23b4a8cd4) | Aug 27, 2022 |
| HP            | 18E7                        | Desktop     | [698520133f](https://linux-hardware.org/?probe=698520133f) | Aug 22, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [45491460bc](https://linux-hardware.org/?probe=45491460bc) | Aug 12, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| HP            | G62                         | Notebook    | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| AZW           | SER V01                     | Mini pc     | [0bf81855b6](https://linux-hardware.org/?probe=0bf81855b6) | Jul 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e45e0b0c90](https://linux-hardware.org/?probe=e45e0b0c90) | Jun 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6023bfb4cc](https://linux-hardware.org/?probe=6023bfb4cc) | Jun 09, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [a4aa661ab1](https://linux-hardware.org/?probe=a4aa661ab1) | Jun 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bcd22d5d0e](https://linux-hardware.org/?probe=bcd22d5d0e) | May 20, 2022 |
| Getac         | S400G3                      | Notebook    | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b2bddaf1b1](https://linux-hardware.org/?probe=b2bddaf1b1) | Apr 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [02b0c35fed](https://linux-hardware.org/?probe=02b0c35fed) | Apr 27, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [cebf5b3135](https://linux-hardware.org/?probe=cebf5b3135) | Apr 17, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [aff1557d72](https://linux-hardware.org/?probe=aff1557d72) | Apr 11, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [a87f9de14e](https://linux-hardware.org/?probe=a87f9de14e) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | Notebook    | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | Notebook    | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [82f706b315](https://linux-hardware.org/?probe=82f706b315) | Feb 11, 2022 |
| Google        | Nami                        | Notebook    | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | Notebook    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [7f94c66f93](https://linux-hardware.org/?probe=7f94c66f93) | Jan 09, 2022 |
| AZW           | GK35                        | Desktop     | [ed1be3dbf7](https://linux-hardware.org/?probe=ed1be3dbf7) | Jan 07, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| Toshiba       | Satellite C855              | Notebook    | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | Notebook    | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Acer          | Aspire U5-710               | All in one  | [c2ff1a33ee](https://linux-hardware.org/?probe=c2ff1a33ee) | Jun 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| HP            | 1495                        | Desktop     | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| Intel Clie... | LAPBC510                    | Notebook    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| HP            | 158A                        | Desktop     | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ef264215af](https://linux-hardware.org/?probe=ef264215af) | Apr 24, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | Notebook    | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [43cb3af3a5](https://linux-hardware.org/?probe=43cb3af3a5) | Apr 12, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | Desktop     | [4cd56bcfa1](https://linux-hardware.org/?probe=4cd56bcfa1) | Apr 02, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [5ff7a11404](https://linux-hardware.org/?probe=5ff7a11404) | Mar 28, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7b7a266de6](https://linux-hardware.org/?probe=7b7a266de6) | Mar 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [d9f29b65da](https://linux-hardware.org/?probe=d9f29b65da) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| Sony          | VGN-NS31M_W                 | Notebook    | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [387cfadf45](https://linux-hardware.org/?probe=387cfadf45) | Feb 06, 2021 |
| IBM           | 8188PPV                     | Desktop     | [6d4f098a65](https://linux-hardware.org/?probe=6d4f098a65) | Jan 31, 2021 |
| Dell          | 02YRK5 A01                  | Desktop     | [6a2d5cd538](https://linux-hardware.org/?probe=6a2d5cd538) | Jan 30, 2021 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [e74dbb590d](https://linux-hardware.org/?probe=e74dbb590d) | Jan 21, 2021 |
| Intel         | DQ965GF AAD41676-402        | Desktop     | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [13edd89415](https://linux-hardware.org/?probe=13edd89415) | Jan 11, 2021 |
| ASUSTek       | U56E                        | Notebook    | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [a8ebb648f7](https://linux-hardware.org/?probe=a8ebb648f7) | Jan 03, 2021 |
| Acer          | Aspire X3400                | Desktop     | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| Packard Be... | WMCP78M                     | Desktop     | [6a6c4577d4](https://linux-hardware.org/?probe=6a6c4577d4) | Dec 31, 2020 |
| HP            | 1850                        | Desktop     | [b86e749745](https://linux-hardware.org/?probe=b86e749745) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4332bc902d](https://linux-hardware.org/?probe=4332bc902d) | Dec 21, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [2291f0c106](https://linux-hardware.org/?probe=2291f0c106) | Dec 08, 2020 |
| Dell          | 04YP6J A02                  | Desktop     | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505443aeb1](https://linux-hardware.org/?probe=505443aeb1) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [73e35c07b8](https://linux-hardware.org/?probe=73e35c07b8) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [3b24badd98](https://linux-hardware.org/?probe=3b24badd98) | Dec 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | Latitude E6530              | Notebook    | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| ASUSTek       | CS-B                        | Desktop     | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Dell          | Latitude E7250              | Notebook    | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | Notebook    | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| HP            | 3047h                       | Desktop     | [a23efe0e20](https://linux-hardware.org/?probe=a23efe0e20) | Oct 26, 2020 |
| ASRock        | H55M/USB3                   | Desktop     | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| Dell          | 0F8098                      | Desktop     | [a2217fa6a7](https://linux-hardware.org/?probe=a2217fa6a7) | Sep 25, 2020 |
| Dell          | 0F8098                      | Desktop     | [2c747bcc47](https://linux-hardware.org/?probe=2c747bcc47) | Sep 25, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | Notebook    | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | Notebook    | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| HP            | Compaq 8510p                | Notebook    | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [d2851c54e9](https://linux-hardware.org/?probe=d2851c54e9) | Aug 18, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [96ba8dc0e8](https://linux-hardware.org/?probe=96ba8dc0e8) | Jul 31, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [d21c458a4f](https://linux-hardware.org/?probe=d21c458a4f) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [957ec007de](https://linux-hardware.org/?probe=957ec007de) | Jun 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cb240b6e7e](https://linux-hardware.org/?probe=cb240b6e7e) | Jun 05, 2020 |
| HP            | Notebook                    | Notebook    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [8271aeba33](https://linux-hardware.org/?probe=8271aeba33) | Mar 19, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | Notebook    | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | Notebook    | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 85        | 34%     |
| Ubuntu Studio 22.04 | 74        | 29.6%   |
| Ubuntu Studio 24.04 | 26        | 10.4%   |
| Ubuntu Studio 23.04 | 13        | 5.2%    |
| Ubuntu Studio 20.10 | 13        | 5.2%    |
| Ubuntu Studio 22.10 | 10        | 4%      |
| Ubuntu Studio 23.10 | 9         | 3.6%    |
| Ubuntu Studio 21.10 | 7         | 2.8%    |
| Ubuntu Studio 21.04 | 5         | 2%      |
| Ubuntu Studio 18.04 | 3         | 1.2%    |
| Ubuntu Studio 24.10 | 2         | 0.8%    |
| Ubuntu Studio 19.10 | 2         | 0.8%    |
| Ubuntu Studio 16.04 | 1         | 0.4%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 247       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.8.0-47-lowlatency    | 7         | 2.71%   |
| 6.8.0-31-lowlatency    | 6         | 2.33%   |
| 6.2.0-1009-lowlatency  | 6         | 2.33%   |
| 5.15.0-56-lowlatency   | 5         | 1.94%   |
| 5.15.0-46-lowlatency   | 5         | 1.94%   |
| 5.13.0-28-lowlatency   | 5         | 1.94%   |
| 6.2.0-1003-lowlatency  | 4         | 1.55%   |
| 5.4.0-52-lowlatency    | 4         | 1.55%   |
| 5.4.0-42-lowlatency    | 4         | 1.55%   |
| 6.8.0-41-lowlatency    | 3         | 1.16%   |
| 6.5.0-28-lowlatency    | 3         | 1.16%   |
| 6.5.0-27-lowlatency    | 3         | 1.16%   |
| 6.2.0-1012-lowlatency  | 3         | 1.16%   |
| 5.8.0-55-lowlatency    | 3         | 1.16%   |
| 5.8.0-50-lowlatency    | 3         | 1.16%   |
| 5.8.0-44-lowlatency    | 3         | 1.16%   |
| 5.8.0-25-lowlatency    | 3         | 1.16%   |
| 5.4.0-65-lowlatency    | 3         | 1.16%   |
| 5.4.0-26-lowlatency    | 3         | 1.16%   |
| 5.19.0-1007-lowlatency | 3         | 1.16%   |
| 5.15.0-67-lowlatency   | 3         | 1.16%   |
| 5.15.0-58-lowlatency   | 3         | 1.16%   |
| 5.15.0-52-lowlatency   | 3         | 1.16%   |
| 5.15.0-50-lowlatency   | 3         | 1.16%   |
| 5.15.0-48-lowlatency   | 3         | 1.16%   |
| 5.15.0-47-lowlatency   | 3         | 1.16%   |
| 5.11.0-44-lowlatency   | 3         | 1.16%   |
| 5.11.0-34-lowlatency   | 3         | 1.16%   |
| 6.8.0-45-lowlatency    | 2         | 0.78%   |
| 6.8.0-39-lowlatency    | 2         | 0.78%   |
| 6.8.0-35-lowlatency    | 2         | 0.78%   |
| 6.5.0-41-lowlatency    | 2         | 0.78%   |
| 6.5.0-25-lowlatency    | 2         | 0.78%   |
| 6.5.0-15-lowlatency    | 2         | 0.78%   |
| 6.5.0-13-lowlatency    | 2         | 0.78%   |
| 6.2.0-1018-lowlatency  | 2         | 0.78%   |
| 6.2.0-1014-lowlatency  | 2         | 0.78%   |
| 5.8.0-48-lowlatency    | 2         | 0.78%   |
| 5.8.0-29-lowlatency    | 2         | 0.78%   |
| 5.4.0-94-lowlatency    | 2         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 56        | 22.4%   |
| 5.4.0   | 53        | 21.2%   |
| 6.8.0   | 28        | 11.2%   |
| 5.8.0   | 23        | 9.2%    |
| 6.2.0   | 22        | 8.8%    |
| 6.5.0   | 17        | 6.8%    |
| 5.11.0  | 15        | 6%      |
| 5.19.0  | 14        | 5.6%    |
| 5.13.0  | 10        | 4%      |
| 4.15.0  | 3         | 1.2%    |
| 6.11.0  | 2         | 0.8%    |
| 5.3.0   | 2         | 0.8%    |
| 6.2.8   | 1         | 0.4%    |
| 5.7.6   | 1         | 0.4%    |
| 5.17.1  | 1         | 0.4%    |
| 5.15.6  | 1         | 0.4%    |
| 4.4.0   | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 57        | 22.8%   |
| 5.4     | 53        | 21.2%   |
| 6.8     | 28        | 11.2%   |
| 6.2     | 23        | 9.2%    |
| 5.8     | 23        | 9.2%    |
| 6.5     | 17        | 6.8%    |
| 5.11    | 15        | 6%      |
| 5.19    | 14        | 5.6%    |
| 5.13    | 10        | 4%      |
| 4.15    | 3         | 1.2%    |
| 6.11    | 2         | 0.8%    |
| 5.3     | 2         | 0.8%    |
| 5.7     | 1         | 0.4%    |
| 5.17    | 1         | 0.4%    |
| 4.4     | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 245       | 99.19%  |
| i686    | 1         | 0.4%    |
| aarch64 | 1         | 0.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 142       | 57.26%  |
| XFCE            | 83        | 33.47%  |
| GNOME           | 13        | 5.24%   |
| LXQt            | 3         | 1.21%   |
| MATE            | 2         | 0.81%   |
| KDE6            | 2         | 0.81%   |
| KDE             | 1         | 0.4%    |
| GNOME Flashback | 1         | 0.4%    |
| Cinnamon        | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 228       | 91.94%  |
| Wayland | 16        | 6.45%   |
| Tty     | 4         | 1.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 135       | 54.66%  |
| LightDM | 50        | 20.24%  |
| TDM     | 49        | 19.84%  |
| GDM     | 11        | 4.45%   |
| LXDM    | 1         | 0.4%    |
| GDM3    | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 107       | 43.15%  |
| fr_FR      | 28        | 11.29%  |
| de_DE      | 16        | 6.45%   |
| en_GB      | 14        | 5.65%   |
| C          | 11        | 4.44%   |
| it_IT      | 9         | 3.63%   |
| ru_RU      | 8         | 3.23%   |
| pt_BR      | 6         | 2.42%   |
| es_ES      | 6         | 2.42%   |
| en_CA      | 6         | 2.42%   |
| en_AU      | 3         | 1.21%   |
| nl_NL      | 2         | 0.81%   |
| hu_HU      | 2         | 0.81%   |
| es_MX      | 2         | 0.81%   |
| es_AR      | 2         | 0.81%   |
| en_IE      | 2         | 0.81%   |
| en_AG      | 2         | 0.81%   |
| Unknown    | 2         | 0.81%   |
| tr_TR      | 1         | 0.4%    |
| sv_SE      | 1         | 0.4%    |
| sk_SK      | 1         | 0.4%    |
| nl_BE      | 1         | 0.4%    |
| nb_NO      | 1         | 0.4%    |
| fr_FR.UTF8 | 1         | 0.4%    |
| fr_CH      | 1         | 0.4%    |
| fr_BE      | 1         | 0.4%    |
| es_NI      | 1         | 0.4%    |
| es_GT      | 1         | 0.4%    |
| es_CR      | 1         | 0.4%    |
| en_NZ      | 1         | 0.4%    |
| en_NG      | 1         | 0.4%    |
| en_IL      | 1         | 0.4%    |
| en_DE      | 1         | 0.4%    |
| de_CH      | 1         | 0.4%    |
| de_AT      | 1         | 0.4%    |
| ca_ES      | 1         | 0.4%    |
| ca_AD      | 1         | 0.4%    |
| bg_BG      | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 150       | 60.73%  |
| BIOS | 97        | 39.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 234       | 94.74%  |
| Overlay | 10        | 4.05%   |
| Xfs     | 1         | 0.4%    |
| Ext3    | 1         | 0.4%    |
| Ext2    | 1         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 170       | 68.83%  |
| MBR  | 77        | 31.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 197       | 78.8%   |
| Yes       | 53        | 21.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 56.85%  |
| Yes       | 107       | 43.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 46        | 18.62%  |
| Lenovo                               | 39        | 15.79%  |
| Hewlett-Packard                      | 32        | 12.96%  |
| Dell                                 | 32        | 12.96%  |
| Gigabyte Technology                  | 19        | 7.69%   |
| Acer                                 | 10        | 4.05%   |
| MSI                                  | 9         | 3.64%   |
| Apple                                | 9         | 3.64%   |
| Toshiba                              | 4         | 1.62%   |
| Intel                                | 4         | 1.62%   |
| Fujitsu                              | 4         | 1.62%   |
| ASRock                               | 4         | 1.62%   |
| Unknown                              | 3         | 1.21%   |
| Sony                                 | 2         | 0.81%   |
| Samsung Electronics                  | 2         | 0.81%   |
| HUAWEI                               | 2         | 0.81%   |
| AZW                                  | 2         | 0.81%   |
| win element                          | 1         | 0.4%    |
| System76                             | 1         | 0.4%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.4%    |
| Razer                                | 1         | 0.4%    |
| Raspberry Pi Foundation              | 1         | 0.4%    |
| Pegatron                             | 1         | 0.4%    |
| Packard Bell                         | 1         | 0.4%    |
| Microsoft                            | 1         | 0.4%    |
| Medion                               | 1         | 0.4%    |
| Intel Client Systems                 | 1         | 0.4%    |
| IBM                                  | 1         | 0.4%    |
| GPU Company                          | 1         | 0.4%    |
| Google                               | 1         | 0.4%    |
| Getac                                | 1         | 0.4%    |
| Foxconn                              | 1         | 0.4%    |
| ECS                                  | 1         | 0.4%    |
| DEPO Computers                       | 1         | 0.4%    |
| COM1                                 | 1         | 0.4%    |
| Clevo                                | 1         | 0.4%    |
| Avell High Performance               | 1         | 0.4%    |
| ATOPNUC                              | 1         | 0.4%    |
| ARDOR GAMING                         | 1         | 0.4%    |
| Alienware                            | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.62%   |
| Unknown                                    | 4         | 1.62%   |
| HP Pavilion dv6                            | 3         | 1.21%   |
| Lenovo G50-45 80E3                         | 2         | 0.81%   |
| HP EliteBook 840 G3                        | 2         | 0.81%   |
| Dell OptiPlex 790                          | 2         | 0.81%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.81%   |
| ASUS PRIME X570-PRO                        | 2         | 0.81%   |
| ASUS M4A785-M                              | 2         | 0.81%   |
| Apple iMac18,3                             | 2         | 0.81%   |
| win element MoreFine S500+                 | 1         | 0.4%    |
| Toshiba Satellite L755D                    | 1         | 0.4%    |
| Toshiba Satellite L505                     | 1         | 0.4%    |
| Toshiba Satellite C855                     | 1         | 0.4%    |
| Toshiba Satellite A505                     | 1         | 0.4%    |
| System76 Thelio                            | 1         | 0.4%    |
| Sony VPCCB3C5E                             | 1         | 0.4%    |
| Sony VGN-NS31M_W                           | 1         | 0.4%    |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.4%    |
| Samsung 730QCJ/730QCR                      | 1         | 0.4%    |
| Samsung 305V4A/305V5A                      | 1         | 0.4%    |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.4%    |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.4%    |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.4%    |
| Packard Bell IMEDIA S3220                  | 1         | 0.4%    |
| MSI Prestige 13 AI+ Evo A2VMG              | 1         | 0.4%    |
| MSI PC Primescan AC                        | 1         | 0.4%    |
| MSI MS-7E06                                | 1         | 0.4%    |
| MSI MS-7E02                                | 1         | 0.4%    |
| MSI MS-7C95                                | 1         | 0.4%    |
| MSI MS-7A57                                | 1         | 0.4%    |
| MSI MS-7752                                | 1         | 0.4%    |
| MSI MS-7693                                | 1         | 0.4%    |
| MSI Alpha 15 A4DEK                         | 1         | 0.4%    |
| Microsoft Surface Laptop 3                 | 1         | 0.4%    |
| Medion MD34207/C746                        | 1         | 0.4%    |
| Lenovo ZIWB2                               | 1         | 0.4%    |
| Lenovo ThinkPad X250 20CL001LMB            | 1         | 0.4%    |
| Lenovo ThinkPad X230 2333A86               | 1         | 0.4%    |
| Lenovo ThinkPad X230 2325AJG               | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 19        | 7.69%   |
| Lenovo IdeaPad                             | 9         | 3.64%   |
| Dell OptiPlex                              | 9         | 3.64%   |
| Dell Inspiron                              | 9         | 3.64%   |
| HP Compaq                                  | 8         | 3.24%   |
| ASUS ROG                                   | 8         | 3.24%   |
| Dell Latitude                              | 7         | 2.83%   |
| Acer Aspire                                | 7         | 2.83%   |
| HP EliteBook                               | 6         | 2.43%   |
| HP Pavilion                                | 5         | 2.02%   |
| Dell Precision                             | 5         | 2.02%   |
| Toshiba Satellite                          | 4         | 1.62%   |
| ASUS PRIME                                 | 4         | 1.62%   |
| ASUS All                                   | 4         | 1.62%   |
| Unknown                                    | 4         | 1.62%   |
| Fujitsu ESPRIMO                            | 3         | 1.21%   |
| ASUS TUF                                   | 3         | 1.21%   |
| ASUS ASUS                                  | 3         | 1.21%   |
| Lenovo ThinkCentre                         | 2         | 0.81%   |
| Lenovo Legion                              | 2         | 0.81%   |
| Lenovo IdeaCentre                          | 2         | 0.81%   |
| Lenovo G50-45                              | 2         | 0.81%   |
| HP ZBook                                   | 2         | 0.81%   |
| Gigabyte X570                              | 2         | 0.81%   |
| ASUS VivoBook                              | 2         | 0.81%   |
| ASUS P8P67                                 | 2         | 0.81%   |
| ASUS M4A785-M                              | 2         | 0.81%   |
| Apple iMac18                               | 2         | 0.81%   |
| Acer Nitro                                 | 2         | 0.81%   |
| win element MoreFine                       | 1         | 0.4%    |
| System76 Thelio                            | 1         | 0.4%    |
| Sony VPCCB3C5E                             | 1         | 0.4%    |
| Sony VGN-NS31M                             | 1         | 0.4%    |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.4%    |
| Samsung 730QCJ                             | 1         | 0.4%    |
| Samsung 305V4A                             | 1         | 0.4%    |
| Razer Blade                                | 1         | 0.4%    |
| RPi Raspberry                              | 1         | 0.4%    |
| Pegatron FL368AA-UUZ                       | 1         | 0.4%    |
| Packard Bell IMEDIA                        | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 27        | 10.93%  |
| 2019 | 20        | 8.1%    |
| 2014 | 19        | 7.69%   |
| 2016 | 18        | 7.29%   |
| 2018 | 17        | 6.88%   |
| 2011 | 17        | 6.88%   |
| 2013 | 16        | 6.48%   |
| 2012 | 16        | 6.48%   |
| 2021 | 15        | 6.07%   |
| 2015 | 14        | 5.67%   |
| 2008 | 14        | 5.67%   |
| 2022 | 12        | 4.86%   |
| 2017 | 11        | 4.45%   |
| 2009 | 11        | 4.45%   |
| 2010 | 8         | 3.24%   |
| 2023 | 4         | 1.62%   |
| 2007 | 4         | 1.62%   |
| 2005 | 3         | 1.21%   |
| 2024 | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 119       | 48.18%  |
| Desktop        | 109       | 44.13%  |
| All in one     | 7         | 2.83%   |
| Mini pc        | 6         | 2.43%   |
| Convertible    | 3         | 1.21%   |
| Tablet         | 2         | 0.81%   |
| System on chip | 1         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 231       | 93.52%  |
| Enabled  | 16        | 6.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 245       | 99.19%  |
| Yes  | 2         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 71        | 28.51%  |
| 16.01-24.0  | 53        | 21.29%  |
| 8.01-16.0   | 44        | 17.67%  |
| 32.01-64.0  | 34        | 13.65%  |
| 3.01-4.0    | 21        | 8.43%   |
| 64.01-256.0 | 14        | 5.62%   |
| 24.01-32.0  | 5         | 2.01%   |
| 1.01-2.0    | 4         | 1.61%   |
| 2.01-3.0    | 3         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 66        | 26.19%  |
| 1.01-2.0   | 66        | 26.19%  |
| 4.01-8.0   | 52        | 20.63%  |
| 3.01-4.0   | 42        | 16.67%  |
| 8.01-16.0  | 19        | 7.54%   |
| 0.51-1.0   | 4         | 1.59%   |
| 32.01-64.0 | 1         | 0.4%    |
| 24.01-32.0 | 1         | 0.4%    |
| 16.01-24.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 134       | 53.82%  |
| 2      | 78        | 31.33%  |
| 3      | 16        | 6.43%   |
| 4      | 7         | 2.81%   |
| 5      | 5         | 2.01%   |
| 7      | 4         | 1.61%   |
| 0      | 2         | 0.8%    |
| 16     | 1         | 0.4%    |
| 11     | 1         | 0.4%    |
| 10     | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148       | 59.68%  |
| Yes       | 100       | 40.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 89.11%  |
| No        | 27        | 10.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 75.71%  |
| No        | 60        | 24.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 60.73%  |
| No        | 97        | 39.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 66        | 26.72%  |
| France       | 28        | 11.34%  |
| Germany      | 26        | 10.53%  |
| Italy        | 14        | 5.67%   |
| Canada       | 10        | 4.05%   |
| Russia       | 9         | 3.64%   |
| UK           | 8         | 3.24%   |
| Spain        | 8         | 3.24%   |
| Brazil       | 8         | 3.24%   |
| Mexico       | 5         | 2.02%   |
| Belgium      | 5         | 2.02%   |
| Austria      | 5         | 2.02%   |
| Australia    | 5         | 2.02%   |
| Sweden       | 4         | 1.62%   |
| Netherlands  | 4         | 1.62%   |
| Switzerland  | 3         | 1.21%   |
| Norway       | 3         | 1.21%   |
| Turkey       | 2         | 0.81%   |
| Taiwan       | 2         | 0.81%   |
| Romania      | 2         | 0.81%   |
| Ivory Coast  | 2         | 0.81%   |
| Israel       | 2         | 0.81%   |
| Hungary      | 2         | 0.81%   |
| Costa Rica   | 2         | 0.81%   |
| Bulgaria     | 2         | 0.81%   |
| Argentina    | 2         | 0.81%   |
| Yemen        | 1         | 0.4%    |
| Sri Lanka    | 1         | 0.4%    |
| South Africa | 1         | 0.4%    |
| Slovakia     | 1         | 0.4%    |
| Poland       | 1         | 0.4%    |
| Philippines  | 1         | 0.4%    |
| Peru         | 1         | 0.4%    |
| Nigeria      | 1         | 0.4%    |
| Nicaragua    | 1         | 0.4%    |
| New Zealand  | 1         | 0.4%    |
| Luxembourg   | 1         | 0.4%    |
| Kenya        | 1         | 0.4%    |
| Ireland      | 1         | 0.4%    |
| Indonesia    | 1         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Stockholm     | 4         | 1.59%   |
| Paris         | 4         | 1.59%   |
| Madrid        | 4         | 1.59%   |
| Vienna        | 3         | 1.19%   |
| Munich        | 3         | 1.19%   |
| Montreal      | 3         | 1.19%   |
| Houston       | 3         | 1.19%   |
| Turin         | 2         | 0.79%   |
| Toronto       | 2         | 0.79%   |
| Stuttgart     | 2         | 0.79%   |
| San Francisco | 2         | 0.79%   |
| Moscow        | 2         | 0.79%   |
| Mississauga   | 2         | 0.79%   |
| Mexico City   | 2         | 0.79%   |
| Hamburg       | 2         | 0.79%   |
| Groningen     | 2         | 0.79%   |
| Fürth        | 2         | 0.79%   |
| Denver        | 2         | 0.79%   |
| Chicago       | 2         | 0.79%   |
| Budapest      | 2         | 0.79%   |
| Bucharest     | 2         | 0.79%   |
| Béziers      | 2         | 0.79%   |
| Abidjan       | 2         | 0.79%   |
| Zele          | 1         | 0.4%    |
| Zanesville    | 1         | 0.4%    |
| Yonkers       | 1         | 0.4%    |
| Yekaterinburg | 1         | 0.4%    |
| Wroclaw       | 1         | 0.4%    |
| Woonsocket    | 1         | 0.4%    |
| Woodland Park | 1         | 0.4%    |
| Wilmington    | 1         | 0.4%    |
| Wildenfels    | 1         | 0.4%    |
| West Mifflin  | 1         | 0.4%    |
| Warner Robins | 1         | 0.4%    |
| Villetaneuse  | 1         | 0.4%    |
| Villefontaine | 1         | 0.4%    |
| Viborg        | 1         | 0.4%    |
| Verviers      | 1         | 0.4%    |
| Verdal        | 1         | 0.4%    |
| Velleron      | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 61        | 76     | 15.8%   |
| WDC                         | 60        | 74     | 15.54%  |
| Seagate                     | 48        | 76     | 12.44%  |
| SanDisk                     | 23        | 24     | 5.96%   |
| Toshiba                     | 22        | 23     | 5.7%    |
| Hitachi                     | 15        | 16     | 3.89%   |
| Kingston                    | 14        | 15     | 3.63%   |
| SK hynix                    | 13        | 15     | 3.37%   |
| Crucial                     | 12        | 13     | 3.11%   |
| Intel                       | 10        | 16     | 2.59%   |
| Unknown                     | 7         | 7      | 1.81%   |
| Micron Technology           | 7         | 7      | 1.81%   |
| PNY                         | 6         | 7      | 1.55%   |
| Phison                      | 5         | 5      | 1.3%    |
| HGST                        | 5         | 6      | 1.3%    |
| Apple                       | 4         | 6      | 1.04%   |
| UMIS                        | 3         | 3      | 0.78%   |
| Team                        | 3         | 3      | 0.78%   |
| SPCC                        | 3         | 3      | 0.78%   |
| Kingston Technology Company | 3         | 4      | 0.78%   |
| JMicron Technology          | 3         | 3      | 0.78%   |
| Intenso                     | 3         | 3      | 0.78%   |
| China                       | 3         | 3      | 0.78%   |
| ASMT                        | 3         | 3      | 0.78%   |
| A-DATA Technology           | 3         | 4      | 0.78%   |
| Unknown                     | 3         | 3      | 0.78%   |
| Silicon Motion              | 2         | 2      | 0.52%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.52%   |
| LITEON                      | 2         | 2      | 0.52%   |
| Lexar                       | 2         | 5      | 0.52%   |
| KIOXIA                      | 2         | 2      | 0.52%   |
| Fujitsu                     | 2         | 2      | 0.52%   |
| Corsair                     | 2         | 3      | 0.52%   |
| BHT                         | 2         | 2      | 0.52%   |
| XrayDisk                    | 1         | 1      | 0.26%   |
| XPG                         | 1         | 1      | 0.26%   |
| Wibtek                      | 1         | 1      | 0.26%   |
| USB 3.0                     | 1         | 2      | 0.26%   |
| USB                         | 1         | 1      | 0.26%   |
| Union Memory                | 1         | 1      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 0.93%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 0.93%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 0.93%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 0.93%   |
| Samsung SSD 860 EVO 500GB                 | 4         | 0.93%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 3         | 0.7%    |
| Toshiba DT01ACA100 1TB                    | 3         | 0.7%    |
| Toshiba DT01ACA050 500GB                  | 3         | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB            | 3         | 0.7%    |
| Seagate Expansion Desk 5TB                | 3         | 0.7%    |
| Seagate Expansion 1TB                     | 3         | 0.7%    |
| Samsung SSD 850 EVO 500GB                 | 3         | 0.7%    |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.7%    |
| Crucial CT500MX500SSD1 500GB              | 3         | 0.7%    |
| Crucial CT1000MX500SSD1 1TB               | 3         | 0.7%    |
| Unknown                                   | 3         | 0.7%    |
| WDC WD20EZRX-00D8PB0 2TB                  | 2         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 2         | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 2         | 0.46%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.46%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.46%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 0.46%   |
| Toshiba HDWD130 3TB                       | 2         | 0.46%   |
| Team T253X6001T 1024GB SSD                | 2         | 0.46%   |
| SPCC Solid State Disk 256GB               | 2         | 0.46%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 0.46%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB            | 2         | 0.46%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.46%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 500GB            | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB              | 2         | 0.46%   |
| Samsung SSD 960 PRO 512GB                 | 2         | 0.46%   |
| Samsung SSD 860 EVO 1TB                   | 2         | 0.46%   |
| Samsung MZ7TD256HAFV-000L7 256GB SSD      | 2         | 0.46%   |
| Samsung HD753LJ 752GB                     | 2         | 0.46%   |
| PNY CS900 1TB SSD                         | 2         | 0.46%   |
| Phison Sabrent 1TB                        | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 56     | 30.26%  |
| Seagate             | 46        | 71     | 30.26%  |
| Toshiba             | 21        | 22     | 13.82%  |
| Hitachi             | 15        | 16     | 9.87%   |
| Samsung Electronics | 5         | 5      | 3.29%   |
| HGST                | 5         | 6      | 3.29%   |
| JMicron Technology  | 2         | 2      | 1.32%   |
| Fujitsu             | 2         | 2      | 1.32%   |
| ASMT                | 2         | 2      | 1.32%   |
| Apple               | 2         | 2      | 1.32%   |
| USB 3.0             | 1         | 2      | 0.66%   |
| Unknown             | 1         | 1      | 0.66%   |
| TO Exter            | 1         | 1      | 0.66%   |
| Maxtor              | 1         | 1      | 0.66%   |
| Inateck             | 1         | 1      | 0.66%   |
| External            | 1         | 1      | 0.66%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 38     | 25.19%  |
| SanDisk             | 18        | 19     | 13.74%  |
| Kingston            | 13        | 14     | 9.92%   |
| Crucial             | 10        | 11     | 7.63%   |
| WDC                 | 7         | 9      | 5.34%   |
| PNY                 | 6         | 7      | 4.58%   |
| SK hynix            | 4         | 5      | 3.05%   |
| SPCC                | 3         | 3      | 2.29%   |
| Micron Technology   | 3         | 3      | 2.29%   |
| Intenso             | 3         | 3      | 2.29%   |
| China               | 3         | 3      | 2.29%   |
| Team                | 2         | 2      | 1.53%   |
| BHT                 | 2         | 2      | 1.53%   |
| A-DATA Technology   | 2         | 2      | 1.53%   |
| XrayDisk            | 1         | 1      | 0.76%   |
| Wibtek              | 1         | 1      | 0.76%   |
| Toshiba             | 1         | 1      | 0.76%   |
| Seagate             | 1         | 1      | 0.76%   |
| SCY                 | 1         | 1      | 0.76%   |
| Reeinno             | 1         | 1      | 0.76%   |
| Patriot             | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 1      | 0.76%   |
| NGFF                | 1         | 1      | 0.76%   |
| LITEONIT            | 1         | 1      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| Lexar               | 1         | 1      | 0.76%   |
| Leven               | 1         | 1      | 0.76%   |
| KingSpec            | 1         | 1      | 0.76%   |
| Intel               | 1         | 1      | 0.76%   |
| Integral            | 1         | 1      | 0.76%   |
| Fanxiang            | 1         | 1      | 0.76%   |
| EDGE eMe            | 1         | 1      | 0.76%   |
| Dogfish             | 1         | 1      | 0.76%   |
| Corsair             | 1         | 1      | 0.76%   |
| ASMT                | 1         | 1      | 0.76%   |
| Apple               | 1         | 1      | 0.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 121       | 191    | 36.45%  |
| SSD     | 110       | 143    | 33.13%  |
| NVMe    | 86        | 117    | 25.9%   |
| MMC     | 10        | 11     | 3.01%   |
| Unknown | 5         | 5      | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 185       | 310    | 60.86%  |
| NVMe | 86        | 116    | 28.29%  |
| SAS  | 23        | 30     | 7.57%   |
| MMC  | 10        | 11     | 3.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 169    | 52.55%  |
| 0.51-1.0   | 74        | 89     | 29.02%  |
| 1.01-2.0   | 24        | 32     | 9.41%   |
| 4.01-10.0  | 9         | 26     | 3.53%   |
| 3.01-4.0   | 8         | 10     | 3.14%   |
| 2.01-3.0   | 5         | 7      | 1.96%   |
| 10.01-20.0 | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 26.59%  |
| 251-500        | 48        | 19.05%  |
| 501-1000       | 45        | 17.86%  |
| 1001-2000      | 36        | 14.29%  |
| More than 3000 | 22        | 8.73%   |
| 51-100         | 13        | 5.16%   |
| 21-50          | 11        | 4.37%   |
| 1-20           | 7         | 2.78%   |
| 2001-3000      | 3         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 72        | 28.46%  |
| 21-50          | 44        | 17.39%  |
| 101-250        | 38        | 15.02%  |
| 251-500        | 28        | 11.07%  |
| 51-100         | 24        | 9.49%   |
| 501-1000       | 19        | 7.51%   |
| More than 3000 | 12        | 4.74%   |
| 1001-2000      | 11        | 4.35%   |
| 2001-3000      | 5         | 1.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 6.12%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 3      | 4.08%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 4.08%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.04%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 2.04%   |
| WDC WD5000AAKS-00TMA0 500GB                         | 1         | 1      | 2.04%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 2.04%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 2.04%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 2.04%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 2.04%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 2.04%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 2.04%   |
| WDC WD10EAVS-32D7B1 1TB                             | 1         | 1      | 2.04%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 2.04%   |
| UMIS RPITJ512VME2OWD 512GB                          | 1         | 1      | 2.04%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.04%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 2.04%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 2.04%   |
| SSSTC CL1-4D512 512GB                               | 1         | 1      | 2.04%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 2      | 2.04%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.04%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 2.04%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 2.04%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.04%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 2.04%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 2.04%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1         | 1      | 2.04%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 2.04%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 970 EVO 1TB                 | 1         | 1      | 2.04%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 2.04%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 2.04%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 2.04%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.04%   |
| KingSpec P3-256 256GB                               | 1         | 1      | 2.04%   |
| Intel SSDSCKKF180H6H 180GB                          | 1         | 1      | 2.04%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS547564A9E384 640GB                       | 1         | 1      | 2.04%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.04%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 17     | 25%     |
| WDC                 | 10        | 11     | 20.83%  |
| Samsung Electronics | 8         | 9      | 16.67%  |
| Hitachi             | 6         | 6      | 12.5%   |
| Toshiba             | 3         | 3      | 6.25%   |
| A-DATA Technology   | 2         | 2      | 4.17%   |
| UMIS                | 1         | 1      | 2.08%   |
| SSSTC               | 1         | 1      | 2.08%   |
| SK hynix            | 1         | 2      | 2.08%   |
| Micron Technology   | 1         | 1      | 2.08%   |
| KingSpec            | 1         | 1      | 2.08%   |
| Intel               | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 17     | 33.33%  |
| WDC                 | 10        | 11     | 27.78%  |
| Hitachi             | 6         | 6      | 16.67%  |
| Samsung Electronics | 4         | 4      | 11.11%  |
| Toshiba             | 3         | 3      | 8.33%   |
| HGST                | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 42     | 73.91%  |
| SSD  | 8         | 10     | 17.39%  |
| NVMe | 4         | 4      | 8.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 50%     |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 213       | 366    | 72.95%  |
| Malfunc  | 46        | 56     | 15.75%  |
| Detected | 30        | 42     | 10.27%  |
| Failed   | 2         | 2      | 0.68%   |
| Fixed    | 1         | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 167       | 50.15%  |
| AMD                            | 56        | 16.82%  |
| Samsung Electronics            | 30        | 9.01%   |
| Sandisk                        | 13        | 3.9%    |
| SK hynix                       | 9         | 2.7%    |
| Phison Electronics             | 8         | 2.4%    |
| Marvell Technology Group       | 6         | 1.8%    |
| ASMedia Technology             | 6         | 1.8%    |
| Union Memory (Shenzhen)        | 4         | 1.2%    |
| Micron Technology              | 4         | 1.2%    |
| Kingston Technology Company    | 4         | 1.2%    |
| Silicon Motion                 | 3         | 0.9%    |
| Nvidia                         | 3         | 0.9%    |
| Realtek Semiconductor          | 2         | 0.6%    |
| Micron/Crucial Technology      | 2         | 0.6%    |
| MAXIO Technology (Hangzhou)    | 2         | 0.6%    |
| JMicron Technology             | 2         | 0.6%    |
| VIA Technologies               | 1         | 0.3%    |
| Toshiba America Info Systems   | 1         | 0.3%    |
| Solid State Storage Technology | 1         | 0.3%    |
| Silicon Image                  | 1         | 0.3%    |
| Shenzhen Longsys Electronics   | 1         | 0.3%    |
| Seagate Technology             | 1         | 0.3%    |
| LSI Logic / Symbios Logic      | 1         | 0.3%    |
| Lite-On Technology             | 1         | 0.3%    |
| KIOXIA                         | 1         | 0.3%    |
| Apple                          | 1         | 0.3%    |
| ADATA Technology               | 1         | 0.3%    |
| Adaptec                        | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 37        | 9.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 3.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 3.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 3.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 2.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.57%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 6         | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.57%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 1.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.31%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 1.31%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 1.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.31%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 4         | 1.04%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.04%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.78%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 3         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.78%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.78%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.78%   |
| AMD FCH IDE Controller                                                         | 3         | 0.78%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.52%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 190       | 56.89%  |
| NVMe | 87        | 26.05%  |
| IDE  | 34        | 10.18%  |
| RAID | 19        | 5.69%   |
| SAS  | 3         | 0.9%    |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 179       | 72.47%  |
| AMD    | 67        | 27.13%  |
| ARM    | 1         | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 4         | 1.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 4         | 1.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1.21%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.21%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.21%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.21%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 3         | 1.21%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.21%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 2         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.81%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.81%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.81%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 2         | 0.81%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 0.81%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.81%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.81%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.81%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.81%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.81%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2         | 0.81%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 2         | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 2         | 0.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.81%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 2         | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 0.81%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 2         | 0.81%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 0.81%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.81%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 2         | 0.81%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 2         | 0.81%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 2         | 0.81%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 2         | 0.81%   |
| AMD Phenom II X4 945 Processor          | 2         | 0.81%   |
| AMD FX-8350 Eight-Core Processor        | 2         | 0.81%   |
| Intel Xeon W-2150B CPU @ 3.00GHz        | 1         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i5          | 58        | 23.48%  |
| Intel Core i7          | 57        | 23.08%  |
| Other                  | 17        | 6.88%   |
| AMD Ryzen 5            | 16        | 6.48%   |
| Intel Core i3          | 15        | 6.07%   |
| AMD Ryzen 7            | 11        | 4.45%   |
| Intel Core 2 Duo       | 7         | 2.83%   |
| Intel Celeron          | 7         | 2.83%   |
| AMD Ryzen 9            | 7         | 2.83%   |
| Intel Core i9          | 5         | 2.02%   |
| Intel Xeon             | 4         | 1.62%   |
| AMD Phenom II X4       | 4         | 1.62%   |
| AMD FX                 | 4         | 1.62%   |
| Intel Core 2 Quad      | 3         | 1.21%   |
| AMD Ryzen 3            | 3         | 1.21%   |
| AMD E                  | 3         | 1.21%   |
| Intel Pentium 4        | 2         | 0.81%   |
| Intel Pentium          | 2         | 0.81%   |
| AMD Athlon II X2       | 2         | 0.81%   |
| AMD A8                 | 2         | 0.81%   |
| AMD A4                 | 2         | 0.81%   |
| Intel Pentium Dual     | 1         | 0.4%    |
| Intel Pentium D        | 1         | 0.4%    |
| Intel Genuine          | 1         | 0.4%    |
| Intel Core 2           | 1         | 0.4%    |
| Intel Core             | 1         | 0.4%    |
| AMD Ryzen Threadripper | 1         | 0.4%    |
| AMD Ryzen 5 PRO        | 1         | 0.4%    |
| AMD Ryzen 3 PRO        | 1         | 0.4%    |
| AMD E2                 | 1         | 0.4%    |
| AMD E1                 | 1         | 0.4%    |
| AMD Athlon X4          | 1         | 0.4%    |
| AMD Athlon II X4       | 1         | 0.4%    |
| AMD Athlon Dual Core   | 1         | 0.4%    |
| AMD Athlon 64 X2       | 1         | 0.4%    |
| AMD A6                 | 1         | 0.4%    |
| AMD A10                | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 96        | 38.87%  |
| 2      | 84        | 34.01%  |
| 6      | 29        | 11.74%  |
| 8      | 19        | 7.69%   |
| 10     | 5         | 2.02%   |
| 16     | 4         | 1.62%   |
| 12     | 4         | 1.62%   |
| 1      | 3         | 1.21%   |
| 14     | 2         | 0.81%   |
| 32     | 1         | 0.4%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 246       | 99.6%   |
| 2      | 1         | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 171       | 69.23%  |
| 1      | 76        | 30.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 246       | 99.6%   |
| 32-bit         | 1         | 0.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 30.52%  |
| 0x306c3    | 14        | 5.62%   |
| 0x206a7    | 14        | 5.62%   |
| 0x306a9    | 13        | 5.22%   |
| 0x906ea    | 9         | 3.61%   |
| 0x306d4    | 6         | 2.41%   |
| 0x506e3    | 5         | 2.01%   |
| 0x08600104 | 5         | 2.01%   |
| 0x806ea    | 4         | 1.61%   |
| 0x806c1    | 4         | 1.61%   |
| 0x0a50000c | 4         | 1.61%   |
| 0x08701021 | 4         | 1.61%   |
| 0xa0652    | 3         | 1.2%    |
| 0x906e9    | 3         | 1.2%    |
| 0x706e5    | 3         | 1.2%    |
| 0x406e3    | 3         | 1.2%    |
| 0x40651    | 3         | 1.2%    |
| 0x106e5    | 3         | 1.2%    |
| 0x10676    | 3         | 1.2%    |
| 0x0a50000d | 3         | 1.2%    |
| 0x08600106 | 3         | 1.2%    |
| 0x08108109 | 3         | 1.2%    |
| 0x010000c8 | 3         | 1.2%    |
| 0xf41      | 2         | 0.8%    |
| 0xa0655    | 2         | 0.8%    |
| 0x906ed    | 2         | 0.8%    |
| 0x6fd      | 2         | 0.8%    |
| 0x206d7    | 2         | 0.8%    |
| 0x106a5    | 2         | 0.8%    |
| 0x07030105 | 2         | 0.8%    |
| 0x010000b6 | 2         | 0.8%    |
| 0xf65      | 1         | 0.4%    |
| 0x906ec    | 1         | 0.4%    |
| 0x906a4    | 1         | 0.4%    |
| 0x906a3    | 1         | 0.4%    |
| 0x90675    | 1         | 0.4%    |
| 0x806ec    | 1         | 0.4%    |
| 0x806e9    | 1         | 0.4%    |
| 0x706a1    | 1         | 0.4%    |
| 0x6fb      | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 12.55%  |
| Haswell          | 26        | 10.53%  |
| Zen 2            | 20        | 8.1%    |
| Skylake          | 20        | 8.1%    |
| SandyBridge      | 20        | 8.1%    |
| IvyBridge        | 15        | 6.07%   |
| Zen 3            | 10        | 4.05%   |
| Penryn           | 9         | 3.64%   |
| Broadwell        | 9         | 3.64%   |
| Alderlake Hybrid | 9         | 3.64%   |
| Nehalem          | 6         | 2.43%   |
| K10              | 6         | 2.43%   |
| Zen+             | 5         | 2.02%   |
| Westmere         | 5         | 2.02%   |
| TigerLake        | 5         | 2.02%   |
| Piledriver       | 5         | 2.02%   |
| IceLake          | 5         | 2.02%   |
| Core             | 5         | 2.02%   |
| CometLake        | 5         | 2.02%   |
| Unknown          | 5         | 2.02%   |
| Puma             | 4         | 1.62%   |
| NetBurst         | 3         | 1.21%   |
| K10 Llano        | 3         | 1.21%   |
| Excavator        | 3         | 1.21%   |
| Zen              | 2         | 0.81%   |
| K8 Hammer        | 2         | 0.81%   |
| Goldmont plus    | 2         | 0.81%   |
| Goldmont         | 2         | 0.81%   |
| Bobcat           | 2         | 0.81%   |
| Steamroller      | 1         | 0.4%    |
| Silvermont       | 1         | 0.4%    |
| Lunarlake Hybrid | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 132       | 44.9%   |
| Nvidia | 92        | 31.29%  |
| AMD    | 70        | 23.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 12        | 3.96%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 11        | 3.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 2.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 8         | 2.64%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 2.64%   |
| Intel HD Graphics 5500                                                      | 7         | 2.31%   |
| Intel HD Graphics 530                                                       | 7         | 2.31%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 6         | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 1.98%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6         | 1.98%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.65%   |
| Intel HD Graphics 630                                                       | 5         | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 1.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 1.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 4         | 1.32%   |
| Intel UHD Graphics 620                                                      | 4         | 1.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.32%   |
| Intel Iris Plus Graphics G7                                                 | 4         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.32%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 0.99%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3         | 0.99%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3         | 0.99%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 0.99%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 0.99%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 3         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.66%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.66%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.66%   |
| Nvidia GF108M [GeForce GT 525M]                                             | 2         | 0.66%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 2         | 0.66%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 2         | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 36.69%  |
| 1 x Nvidia     | 53        | 21.37%  |
| 1 x AMD        | 53        | 21.37%  |
| Intel + Nvidia | 30        | 12.1%   |
| AMD + Nvidia   | 8         | 3.23%   |
| 2 x AMD        | 5         | 2.02%   |
| Intel + AMD    | 4         | 1.61%   |
| 2 x Nvidia     | 2         | 0.81%   |
| Other          | 1         | 0.4%    |
| 2 x Intel      | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 194       | 78.23%  |
| Proprietary | 50        | 20.16%  |
| Unknown     | 4         | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 43.37%  |
| 0.01-0.5   | 34        | 13.65%  |
| 1.01-2.0   | 31        | 12.45%  |
| 0.51-1.0   | 27        | 10.84%  |
| 3.01-4.0   | 19        | 7.63%   |
| 7.01-8.0   | 10        | 4.02%   |
| 8.01-16.0  | 9         | 3.61%   |
| 5.01-6.0   | 7         | 2.81%   |
| 16.01-24.0 | 2         | 0.8%    |
| 32.01-64.0 | 1         | 0.4%    |
| 2.01-3.0   | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 37        | 13.26%  |
| AU Optronics            | 29        | 10.39%  |
| LG Display              | 24        | 8.6%    |
| Goldstar                | 19        | 6.81%   |
| BOE                     | 19        | 6.81%   |
| Chimei Innolux          | 17        | 6.09%   |
| Hewlett-Packard         | 16        | 5.73%   |
| Dell                    | 15        | 5.38%   |
| Philips                 | 12        | 4.3%    |
| Acer                    | 11        | 3.94%   |
| Ancor Communications    | 8         | 2.87%   |
| Apple                   | 7         | 2.51%   |
| BenQ                    | 6         | 2.15%   |
| Sharp                   | 5         | 1.79%   |
| Lenovo                  | 5         | 1.79%   |
| ASUSTek Computer        | 4         | 1.43%   |
| AOC                     | 3         | 1.08%   |
| ViewSonic               | 2         | 0.72%   |
| Unknown                 | 2         | 0.72%   |
| Sony                    | 2         | 0.72%   |
| ONN                     | 2         | 0.72%   |
| Iiyama                  | 2         | 0.72%   |
| Hitachi                 | 2         | 0.72%   |
| Hannspree               | 2         | 0.72%   |
| Fujitsu Siemens         | 2         | 0.72%   |
| Eizo                    | 2         | 0.72%   |
| Chi Mei Optoelectronics | 2         | 0.72%   |
| Westinghouse            | 1         | 0.36%   |
| VIE                     | 1         | 0.36%   |
| UGD                     | 1         | 0.36%   |
| TVT                     | 1         | 0.36%   |
| TCH                     | 1         | 0.36%   |
| Targa Visionary         | 1         | 0.36%   |
| Seiki                   | 1         | 0.36%   |
| Onkyo                   | 1         | 0.36%   |
| NEC Computers           | 1         | 0.36%   |
| MSI                     | 1         | 0.36%   |
| Medion                  | 1         | 0.36%   |
| LOE                     | 1         | 0.36%   |
| LG Philips              | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 0.68%   |
| ONN 100002487 ONN0101 1920x1080 517x323mm 24.0-inch                   | 2         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.68%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.68%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 0.68%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.68%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.68%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.68%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch         | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 0.68%   |
| Apple iMac APPAE11 3840x2160 597x336mm 27.0-inch                      | 2         | 0.68%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.68%   |
| Westinghouse SK-26H730S WDE15CC 1366x768 575x323mm 26.0-inch          | 1         | 0.34%   |
| ViewSonic VX2758-C-MH VSC35DD 1920x1080 597x336mm 27.0-inch           | 1         | 0.34%   |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.34%   |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.34%   |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.34%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.34%   |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.34%   |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.34%   |
| TCH HDMI TCH5600 1920x1080 344x194mm 15.5-inch                        | 1         | 0.34%   |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.34%   |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.34%   |
| Sony TV  *00 SNY8004 3840x2160 1220x680mm 55.0-inch                   | 1         | 0.34%   |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.34%   |
| Sharp LQ134N1JW54 SHP154F 1920x1200 288x180mm 13.4-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.34%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.34%   |
| Seiki SE19HE01 SEK078A 1366x768 410x230mm 18.5-inch                   | 1         | 0.34%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.34%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.34%   |
| Samsung Electronics T22D390 SAM0B6B 1920x1080 477x268mm 21.5-inch     | 1         | 0.34%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch  | 1         | 0.34%   |
| Samsung Electronics SyncMaster SAM0484 1920x1080 520x320mm 24.0-inch  | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 130       | 49.24%  |
| 1366x768 (WXGA)    | 39        | 14.77%  |
| 3840x2160 (4K)     | 22        | 8.33%   |
| 1280x1024 (SXGA)   | 12        | 4.55%   |
| 1680x1050 (WSXGA+) | 11        | 4.17%   |
| 1920x1200 (WUXGA)  | 10        | 3.79%   |
| 2560x1440 (QHD)    | 8         | 3.03%   |
| 1600x900 (HD+)     | 7         | 2.65%   |
| 1440x900 (WXGA+)   | 4         | 1.52%   |
| 1280x800 (WXGA)    | 3         | 1.14%   |
| 3440x1440          | 2         | 0.76%   |
| 2880x1800          | 2         | 0.76%   |
| 1360x768           | 2         | 0.76%   |
| Unknown            | 2         | 0.76%   |
| 5760x2160          | 1         | 0.38%   |
| 3280x1080          | 1         | 0.38%   |
| 2560x1600          | 1         | 0.38%   |
| 2496x1664          | 1         | 0.38%   |
| 2288x1287          | 1         | 0.38%   |
| 2160x1440          | 1         | 0.38%   |
| 1920x540           | 1         | 0.38%   |
| 1600x1200          | 1         | 0.38%   |
| 1400x1050          | 1         | 0.38%   |
| 1024x768 (XGA)     | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 65        | 23.3%   |
| 27      | 26        | 9.32%   |
| 21      | 24        | 8.6%    |
| 24      | 23        | 8.24%   |
| 13      | 22        | 7.89%   |
| 23      | 20        | 7.17%   |
| 17      | 16        | 5.73%   |
| 14      | 14        | 5.02%   |
| 31      | 11        | 3.94%   |
| 22      | 9         | 3.23%   |
| 19      | 9         | 3.23%   |
| 18      | 6         | 2.15%   |
| 12      | 5         | 1.79%   |
| 84      | 4         | 1.43%   |
| 20      | 4         | 1.43%   |
| 16      | 4         | 1.43%   |
| Unknown | 3         | 1.08%   |
| 32      | 2         | 0.72%   |
| 26      | 2         | 0.72%   |
| 142     | 1         | 0.36%   |
| 72      | 1         | 0.36%   |
| 65      | 1         | 0.36%   |
| 54      | 1         | 0.36%   |
| 52      | 1         | 0.36%   |
| 50      | 1         | 0.36%   |
| 43      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 34      | 1         | 0.36%   |
| 11      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 96        | 35.29%  |
| 501-600        | 64        | 23.53%  |
| 401-500        | 46        | 16.91%  |
| 201-300        | 18        | 6.62%   |
| 351-400        | 17        | 6.25%   |
| 601-700        | 13        | 4.78%   |
| 1501-2000      | 5         | 1.84%   |
| 1001-1500      | 4         | 1.47%   |
| 701-800        | 3         | 1.1%    |
| Unknown        | 3         | 1.1%    |
| More than 2000 | 1         | 0.37%   |
| 801-900        | 1         | 0.37%   |
| 901-1000       | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 192       | 76.8%   |
| 16/10   | 37        | 14.8%   |
| 5/4     | 10        | 4%      |
| 3/2     | 3         | 1.2%    |
| Unknown | 3         | 1.2%    |
| 4/3     | 2         | 0.8%    |
| 6/5     | 1         | 0.4%    |
| 21/9    | 1         | 0.4%    |
| 1.00    | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 65        | 23.72%  |
| 201-250        | 60        | 21.9%   |
| 81-90          | 27        | 9.85%   |
| 301-350        | 27        | 9.85%   |
| 151-200        | 15        | 5.47%   |
| 351-500        | 14        | 5.11%   |
| 141-150        | 13        | 4.74%   |
| More than 1000 | 10        | 3.65%   |
| 251-300        | 10        | 3.65%   |
| 71-80          | 9         | 3.28%   |
| 121-130        | 8         | 2.92%   |
| 61-70          | 5         | 1.82%   |
| 111-120        | 3         | 1.09%   |
| Unknown        | 3         | 1.09%   |
| 131-140        | 2         | 0.73%   |
| 501-1000       | 2         | 0.73%   |
| 51-60          | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 102       | 38.64%  |
| 121-160       | 65        | 24.62%  |
| 101-120       | 65        | 24.62%  |
| 161-240       | 21        | 7.95%   |
| 1-50          | 5         | 1.89%   |
| More than 240 | 3         | 1.14%   |
| Unknown       | 3         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 193       | 77.51%  |
| 2     | 51        | 20.48%  |
| 3     | 4         | 1.61%   |
| 0     | 1         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 136       | 35.88%  |
| Realtek Semiconductor             | 129       | 34.04%  |
| Qualcomm Atheros                  | 37        | 9.76%   |
| Broadcom                          | 19        | 5.01%   |
| MediaTek                          | 8         | 2.11%   |
| TP-Link                           | 4         | 1.06%   |
| Ralink                            | 4         | 1.06%   |
| Broadcom Limited                  | 4         | 1.06%   |
| ASIX Electronics                  | 4         | 1.06%   |
| Ralink Technology                 | 3         | 0.79%   |
| Nvidia                            | 3         | 0.79%   |
| Qualcomm Atheros Communications   | 2         | 0.53%   |
| Marvell Technology Group          | 2         | 0.53%   |
| Lenovo                            | 2         | 0.53%   |
| Ericsson Business Mobile Networks | 2         | 0.53%   |
| DisplayLink                       | 2         | 0.53%   |
| Aquantia                          | 2         | 0.53%   |
| ZyDAS                             | 1         | 0.26%   |
| Xiaomi                            | 1         | 0.26%   |
| Wacom                             | 1         | 0.26%   |
| Sierra Wireless                   | 1         | 0.26%   |
| Samsung Electronics               | 1         | 0.26%   |
| NetGear                           | 1         | 0.26%   |
| Motorola PCS                      | 1         | 0.26%   |
| Microsoft                         | 1         | 0.26%   |
| InterBiometrics                   | 1         | 0.26%   |
| Input Club                        | 1         | 0.26%   |
| ICS Advent                        | 1         | 0.26%   |
| Huawei Technologies               | 1         | 0.26%   |
| Hewlett-Packard                   | 1         | 0.26%   |
| Google                            | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| ASUSTek Computer                  | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 92        | 20.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 4.22%   |
| Intel Wireless 7265                                                    | 12        | 2.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.56%   |
| Intel Wireless 8260                                                    | 7         | 1.56%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.56%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 1.56%   |
| Intel Wireless 8265 / 8275                                             | 6         | 1.33%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.11%   |
| Intel Wireless 7260                                                    | 5         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 1.11%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5         | 1.11%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.11%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 1.11%   |
| Realtek 802.11ac NIC                                                   | 4         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4         | 0.89%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.89%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 4         | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.67%   |
| Intel Wireless 3165                                                    | 3         | 0.67%   |
| Intel WiFi Link 5100                                                   | 3         | 0.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 0.67%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 3         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 48.97%  |
| Realtek Semiconductor           | 30        | 15.46%  |
| Qualcomm Atheros                | 28        | 14.43%  |
| Broadcom                        | 13        | 6.7%    |
| MediaTek                        | 7         | 3.61%   |
| TP-Link                         | 4         | 2.06%   |
| Ralink                          | 4         | 2.06%   |
| Ralink Technology               | 3         | 1.55%   |
| Qualcomm Atheros Communications | 2         | 1.03%   |
| Broadcom Limited                | 2         | 1.03%   |
| ZyDAS                           | 1         | 0.52%   |
| Wacom                           | 1         | 0.52%   |
| Sierra Wireless                 | 1         | 0.52%   |
| NetGear                         | 1         | 0.52%   |
| Microsoft                       | 1         | 0.52%   |
| ASUSTek Computer                | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 12        | 6.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 7         | 3.59%   |
| Intel Wireless 8260                                                           | 7         | 3.59%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 3.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 3.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 3.59%   |
| Intel Wireless 8265 / 8275                                                    | 6         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 2.56%   |
| Intel Wireless 7260                                                           | 5         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 2.56%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 5         | 2.56%   |
| Realtek 802.11ac NIC                                                          | 4         | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 2.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 4         | 2.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 4         | 2.05%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 4         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.54%   |
| Intel Wireless 3165                                                           | 3         | 1.54%   |
| Intel WiFi Link 5100                                                          | 3         | 1.54%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 3         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 3         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 1.54%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 2         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.03%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2         | 1.03%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.03%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 1.03%   |
| Intel Wireless 3160                                                           | 2         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 2         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 2         | 1.03%   |
| ZyDAS ZD1211B 802.11g                                                         | 1         | 0.51%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                                      | 1         | 0.51%   |
| TP-Link 802.11ac WLAN Adapter                                                 | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 113       | 46.5%   |
| Intel                    | 85        | 34.98%  |
| Qualcomm Atheros         | 12        | 4.94%   |
| Broadcom                 | 10        | 4.12%   |
| ASIX Electronics         | 4         | 1.65%   |
| Nvidia                   | 3         | 1.23%   |
| Marvell Technology Group | 2         | 0.82%   |
| Lenovo                   | 2         | 0.82%   |
| DisplayLink              | 2         | 0.82%   |
| Broadcom Limited         | 2         | 0.82%   |
| Aquantia                 | 2         | 0.82%   |
| Xiaomi                   | 1         | 0.41%   |
| Samsung Electronics      | 1         | 0.41%   |
| Motorola PCS             | 1         | 0.41%   |
| MediaTek                 | 1         | 0.41%   |
| ICS Advent               | 1         | 0.41%   |
| Hewlett-Packard          | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 92        | 37.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 7.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 3.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 9         | 3.63%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.82%   |
| Intel Ethernet Controller I225-V                                               | 6         | 2.42%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 2.02%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 2.02%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.61%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 1.21%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.21%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 1.21%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.81%   |
| Realtek Killer E2600 GbE Controller                                            | 2         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.81%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.81%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.81%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.81%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.81%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.81%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.4%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.4%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.4%    |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.4%    |
| Motorola PCS moto g play - 2023                                                | 1         | 0.4%    |
| MediaTek Infinix SMART 5                                                       | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 221       | 53.38%  |
| WiFi     | 186       | 44.93%  |
| Modem    | 7         | 1.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 50.74%  |
| Ethernet | 133       | 49.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 141       | 57.09%  |
| 1     | 98        | 39.68%  |
| 3     | 5         | 2.02%   |
| 0     | 3         | 1.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 185       | 74.3%   |
| Yes  | 64        | 25.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 50%     |
| Realtek Semiconductor           | 12        | 7.89%   |
| Qualcomm Atheros Communications | 10        | 6.58%   |
| Cambridge Silicon Radio         | 8         | 5.26%   |
| Broadcom                        | 8         | 5.26%   |
| Apple                           | 8         | 5.26%   |
| IMC Networks                    | 6         | 3.95%   |
| MediaTek                        | 5         | 3.29%   |
| ASUSTek Computer                | 4         | 2.63%   |
| Realtek                         | 2         | 1.32%   |
| Ralink Technology               | 2         | 1.32%   |
| Lite-On Technology              | 2         | 1.32%   |
| Hewlett-Packard                 | 2         | 1.32%   |
| Foxconn / Hon Hai               | 2         | 1.32%   |
| Dell                            | 2         | 1.32%   |
| TP-Link                         | 1         | 0.66%   |
| Ralink                          | 1         | 0.66%   |
| Foxconn International           | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 33        | 21.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 7.24%   |
| Intel AX201 Bluetooth                               | 9         | 5.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 5.26%   |
| Intel AX200 Bluetooth                               | 7         | 4.61%   |
| Realtek Bluetooth Radio                             | 6         | 3.95%   |
| MediaTek Wireless_Device                            | 5         | 3.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 3.29%   |
| Intel AX211 Bluetooth                               | 5         | 3.29%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 2.63%   |
| Apple Bluetooth USB Host Controller                 | 4         | 2.63%   |
| Intel AX210 Bluetooth                               | 3         | 1.97%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.97%   |
| Apple Bluetooth Host Controller                     | 3         | 1.97%   |
| Realtek Bluetooth Radio                             | 2         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.32%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.32%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.32%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.66%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.66%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.66%   |
| Ralink CSR BS8510                                   | 1         | 0.66%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.66%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.66%   |
| Intel Bluetooth Device                              | 1         | 0.66%   |
| IMC Networks Wireless_Device                        | 1         | 0.66%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.66%   |
| IMC Networks Bluetooth Device                       | 1         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 173       | 41.79%  |
| AMD                                  | 80        | 19.32%  |
| Nvidia                               | 75        | 18.12%  |
| C-Media Electronics                  | 8         | 1.93%   |
| Yamaha                               | 5         | 1.21%   |
| Texas Instruments                    | 5         | 1.21%   |
| M-Audio                              | 4         | 0.97%   |
| Logitech                             | 4         | 0.97%   |
| JMTek                                | 4         | 0.97%   |
| Focusrite-Novation                   | 4         | 0.97%   |
| PreSonus Audio Electronics           | 3         | 0.72%   |
| Plantronics                          | 3         | 0.72%   |
| Mackie Designs                       | 3         | 0.72%   |
| ASUSTek Computer                     | 3         | 0.72%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.48%   |
| QinHeng Electronics                  | 2         | 0.48%   |
| Generalplus Technology               | 2         | 0.48%   |
| Creative Technology                  | 2         | 0.48%   |
| BEHRINGER International              | 2         | 0.48%   |
| ZOOM                                 | 1         | 0.24%   |
| Yealink Network Technology           | 1         | 0.24%   |
| Xilinx                               | 1         | 0.24%   |
| Textech International                | 1         | 0.24%   |
| Tenx Technology                      | 1         | 0.24%   |
| TEAC                                 | 1         | 0.24%   |
| Studiologic                          | 1         | 0.24%   |
| SteelSeries ApS                      | 1         | 0.24%   |
| Samson Technologies                  | 1         | 0.24%   |
| Realtek Semiconductor                | 1         | 0.24%   |
| Razer USA                            | 1         | 0.24%   |
| MIDITECH                             | 1         | 0.24%   |
| Medeli Electronics                   | 1         | 0.24%   |
| Mark of the Unicorn                  | 1         | 0.24%   |
| Lenovo                               | 1         | 0.24%   |
| KTMicro                              | 1         | 0.24%   |
| Jieli Technology                     | 1         | 0.24%   |
| Harman                               | 1         | 0.24%   |
| Evolution Electronics                | 1         | 0.24%   |
| ESI Audiotechnik                     | 1         | 0.24%   |
| Ensoniq                              | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                        | 26        | 5.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 17        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 17        | 3.48%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 16        | 3.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14        | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13        | 2.66%   |
| Intel Sunrise Point-LP HD Audio                                                   | 13        | 2.66%   |
| Intel Cannon Lake PCH cAVS                                                        | 13        | 2.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 11        | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                          | 11        | 2.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 10        | 2.04%   |
| AMD FCH Azalia Controller                                                         | 10        | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 9         | 1.84%   |
| Intel Broadwell-U Audio Controller                                                | 9         | 1.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9         | 1.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8         | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 7         | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7         | 1.43%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 6         | 1.23%   |
| Intel 8 Series HD Audio Controller                                                | 6         | 1.23%   |
| Intel 200 Series PCH HD Audio                                                     | 6         | 1.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 6         | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 1.02%   |
| Nvidia GA106 High Definition Audio Controller                                     | 5         | 1.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 5         | 1.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 5         | 1.02%   |
| Intel Haswell-ULT HD Audio Controller                                             | 5         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 1.02%   |
| Nvidia GP108 High Definition Audio Controller                                     | 4         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4         | 0.82%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4         | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                         | 4         | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 0.82%   |
| Texas Instruments PCM2902 Audio Codec                                             | 3         | 0.61%   |
| PreSonus Audio Electronics Studio 24c                                             | 3         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3         | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                | 3         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 23.05%  |
| SK hynix            | 59        | 20%     |
| Kingston            | 35        | 11.86%  |
| Micron Technology   | 27        | 9.15%   |
| Unknown             | 23        | 7.8%    |
| Crucial             | 17        | 5.76%   |
| Corsair             | 15        | 5.08%   |
| G.Skill             | 11        | 3.73%   |
| Patriot             | 6         | 2.03%   |
| Ramaxel Technology  | 5         | 1.69%   |
| Nanya Technology    | 3         | 1.02%   |
| Elpida              | 3         | 1.02%   |
| A-DATA Technology   | 3         | 1.02%   |
| Unknown             | 3         | 1.02%   |
| Transcend           | 2         | 0.68%   |
| Timetec             | 2         | 0.68%   |
| Wodposit            | 1         | 0.34%   |
| Unifosa             | 1         | 0.34%   |
| Smart               | 1         | 0.34%   |
| S                   | 1         | 0.34%   |
| PNY                 | 1         | 0.34%   |
| OCZ                 | 1         | 0.34%   |
| M                   | 1         | 0.34%   |
| HBS                 | 1         | 0.34%   |
| Goldkey             | 1         | 0.34%   |
| CSX                 | 1         | 0.34%   |
| Avant               | 1         | 0.34%   |
| Aeneon              | 1         | 0.34%   |
| 0194808980CE        | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 6         | 1.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 4         | 1.24%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s      | 4         | 1.24%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 3         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 0.93%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s    | 3         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s    | 3         | 0.93%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.93%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 3         | 0.93%   |
| Patriot RAM 3200 C16 Series 4GB DIMM DDR4 3600MT/s        | 3         | 0.93%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s      | 3         | 0.93%   |
| Unknown                                                   | 3         | 0.93%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                   | 2         | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                  | 2         | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 2         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 0.62%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.62%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s    | 2         | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 2         | 0.62%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s               | 2         | 0.62%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 0.62%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s    | 2         | 0.62%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s     | 2         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 2         | 0.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.62%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 2         | 0.62%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s    | 2         | 0.62%   |
| Patriot RAM 2400 C15 Series 8GB SODIMM DDR4 2667MT/s      | 2         | 0.62%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM 1600MT/s            | 2         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 2         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.62%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 2         | 0.62%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s    | 2         | 0.62%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2667MT/s    | 1         | 0.31%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                      | 1         | 0.31%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.31%   |
| Unknown RAM Module 512MB DIMM DDR 533MT/s                 | 1         | 0.31%   |
| Unknown RAM Module 512MB DIMM DDR                         | 1         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 105       | 41.67%  |
| DDR3    | 101       | 40.08%  |
| DDR2    | 16        | 6.35%   |
| Unknown | 8         | 3.17%   |
| SDRAM   | 6         | 2.38%   |
| LPDDR5  | 4         | 1.59%   |
| DDR5    | 4         | 1.59%   |
| LPDDR4  | 3         | 1.19%   |
| DDR     | 3         | 1.19%   |
| LPDDR3  | 2         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 52%     |
| DIMM         | 99        | 39.6%   |
| Row Of Chips | 15        | 6%      |
| Chip         | 2         | 0.8%    |
| Unknown      | 2         | 0.8%    |
| RIMM         | 1         | 0.4%    |
| FB-DIMM      | 1         | 0.4%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 105       | 36.84%  |
| 4096  | 84        | 29.47%  |
| 16384 | 36        | 12.63%  |
| 2048  | 30        | 10.53%  |
| 32768 | 16        | 5.61%   |
| 1024  | 11        | 3.86%   |
| 512   | 2         | 0.7%    |
| 256   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 67        | 24.63%  |
| 3200    | 30        | 11.03%  |
| 2667    | 28        | 10.29%  |
| 2400    | 18        | 6.62%   |
| 1333    | 16        | 5.88%   |
| 2133    | 13        | 4.78%   |
| 3600    | 11        | 4.04%   |
| 1334    | 11        | 4.04%   |
| 667     | 8         | 2.94%   |
| 1866    | 6         | 2.21%   |
| 800     | 6         | 2.21%   |
| Unknown | 6         | 2.21%   |
| 1867    | 4         | 1.47%   |
| 1800    | 4         | 1.47%   |
| 1066    | 4         | 1.47%   |
| 6400    | 3         | 1.1%    |
| 4267    | 3         | 1.1%    |
| 2933    | 3         | 1.1%    |
| 1067    | 3         | 1.1%    |
| 5600    | 2         | 0.74%   |
| 4199    | 2         | 0.74%   |
| 3400    | 2         | 0.74%   |
| 3266    | 2         | 0.74%   |
| 2666    | 2         | 0.74%   |
| 533     | 2         | 0.74%   |
| 8533    | 1         | 0.37%   |
| 7200    | 1         | 0.37%   |
| 4802    | 1         | 0.37%   |
| 3866    | 1         | 0.37%   |
| 3800    | 1         | 0.37%   |
| 3733    | 1         | 0.37%   |
| 3500    | 1         | 0.37%   |
| 3467    | 1         | 0.37%   |
| 3466    | 1         | 0.37%   |
| 3000    | 1         | 0.37%   |
| 2934    | 1         | 0.37%   |
| 2800    | 1         | 0.37%   |
| 2465    | 1         | 0.37%   |
| 1639    | 1         | 0.37%   |
| 1632    | 1         | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Ricoh           | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Ricoh Aficio SP 100SU | 1         | 20%     |
| HP OfficeJet Pro 6960 | 1         | 20%     |
| HP OfficeJet 6950     | 1         | 20%     |
| HP LaserJet 1022      | 1         | 20%     |
| Canon LiDE 400        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LiDE 60 | 1         | 33.33%  |
| Canon CanoScan FB630U  | 1         | 33.33%  |
| Canon CanoScan 4200F   | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27        | 17.88%  |
| IMC Networks                           | 11        | 7.28%   |
| Realtek Semiconductor                  | 10        | 6.62%   |
| Logitech                               | 10        | 6.62%   |
| Microdia                               | 9         | 5.96%   |
| Bison Electronics                      | 8         | 5.3%    |
| Syntek                                 | 7         | 4.64%   |
| Suyin                                  | 7         | 4.64%   |
| Sunplus Innovation Technology          | 7         | 4.64%   |
| Lite-On Technology                     | 6         | 3.97%   |
| Quanta                                 | 5         | 3.31%   |
| Apple                                  | 5         | 3.31%   |
| Sonix Technology                       | 3         | 1.99%   |
| Microsoft                              | 3         | 1.99%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.99%   |
| Xiongmai                               | 2         | 1.32%   |
| Samsung Electronics                    | 2         | 1.32%   |
| Ricoh                                  | 2         | 1.32%   |
| Philips (or NXP)                       | 2         | 1.32%   |
| Intel                                  | 2         | 1.32%   |
| ViewSonic                              | 1         | 0.66%   |
| ViewQuest Technologies                 | 1         | 0.66%   |
| Trust                                  | 1         | 0.66%   |
| Sweex                                  | 1         | 0.66%   |
| Sunplus IT                             | 1         | 0.66%   |
| Silicon Motion                         | 1         | 0.66%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.66%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.66%   |
| Razer USA                              | 1         | 0.66%   |
| OmniVision Technologies                | 1         | 0.66%   |
| MacroSilicon                           | 1         | 0.66%   |
| Luxvisions Innotech Limited            | 1         | 0.66%   |
| Jieli Technology                       | 1         | 0.66%   |
| Importek                               | 1         | 0.66%   |
| Huawei Technologies                    | 1         | 0.66%   |
| HRY                                    | 1         | 0.66%   |
| Generalplus Technology                 | 1         | 0.66%   |
| Dynex                                  | 1         | 0.66%   |
| Dell                                   | 1         | 0.66%   |
| Acer                                   | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                          | 7         | 4.61%   |
| Chicony integrated camera                         | 7         | 4.61%   |
| Bison Integrated Camera                           | 5         | 3.29%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 4         | 2.63%   |
| IMC Networks Integrated Camera                    | 4         | 2.63%   |
| Sunplus Integrated_Webcam_HD                      | 3         | 1.97%   |
| Sonix USB2.0 HD UVC WebCam                        | 3         | 1.97%   |
| Realtek Lenovo EasyCamera                         | 3         | 1.97%   |
| Microdia Integrated_Webcam_HD                     | 3         | 1.97%   |
| Logitech Webcam C270                              | 3         | 1.97%   |
| Lite-On Integrated Camera                         | 3         | 1.97%   |
| Chicony Integrated Camera [ThinkPad]              | 3         | 1.97%   |
| Chicony HD Webcam                                 | 3         | 1.97%   |
| Chicony HD User Facing                            | 3         | 1.97%   |
| Xiongmai web camera                               | 2         | 1.32%   |
| Suyin USB 2.0 Camera                              | 2         | 1.32%   |
| Suyin Asus Integrated Webcam                      | 2         | 1.32%   |
| Sunplus HD WebCam                                 | 2         | 1.32%   |
| Samsung Galaxy series, misc. (MTP mode)           | 2         | 1.32%   |
| Realtek Integrated_Webcam_HD                      | 2         | 1.32%   |
| Lite-On HP HD Webcam                              | 2         | 1.32%   |
| Intel RealSense 3D Camera (Front F200)            | 2         | 1.32%   |
| Chicony HP HD Camera                              | 2         | 1.32%   |
| Apple FaceTime HD Camera (Built-in)               | 2         | 1.32%   |
| Apple FaceTime HD Camera                          | 2         | 1.32%   |
| ViewSonic PC Camera                               | 1         | 0.66%   |
| ViewQuest Ability GABB Webcam                     | 1         | 0.66%   |
| Trust Canyon CNS-CWC6 Webcam                      | 1         | 0.66%   |
| Sweex WC060 Series HD Webcam                      | 1         | 0.66%   |
| Suyin HP Webcam                                   | 1         | 0.66%   |
| Suyin HP TrueVision HD Integrated Webcam          | 1         | 0.66%   |
| Suyin HP TrueVision HD                            | 1         | 0.66%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 1         | 0.66%   |
| Sunplus HD 720P webcam                            | 1         | 0.66%   |
| Sunplus Dell HD Webcam                            | 1         | 0.66%   |
| Silicon Motion WebCam SCB-1100N                   | 1         | 0.66%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera   | 1         | 0.66%   |
| SHENZHEN AONI ELECTRONIC NexiGo N930AF FHD Webcam | 1         | 0.66%   |
| Ricoh USB2.0 Camera                               | 1         | 0.66%   |
| Ricoh Sony Vaio Integrated Webcam                 | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 50%     |
| Synaptics                  | 5         | 19.23%  |
| Shenzhen Goodix Technology | 4         | 15.38%  |
| Samsung Electronics        | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |
| Focal-systems.Corp         | 1         | 3.85%   |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 4         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 11.54%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 7.69%   |
| Validity Sensors Fingerprint scanner              | 2         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 7.69%   |
| Shenzhen Goodix  Fingerprint Device               | 2         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.85%   |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 3.85%   |
| Synaptics Prometheus Fingerprint Reader           | 1         | 3.85%   |
| Synaptics Fingerprint reader [HP G6]              | 1         | 3.85%   |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 3.85%   |
| Focal-systems.Corp FT9201Fingerprint.Ì         | 1         | 3.85%   |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 5         | 41.67%  |
| Upek                | 3         | 25%     |
| Alcor Micro         | 2         | 16.67%  |
| Lenovo              | 1         | 8.33%   |
| Chicony Electronics | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 177       | 71.37%  |
| 1     | 60        | 24.19%  |
| 2     | 10        | 4.03%   |
| 3     | 1         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 26        | 32.91%  |
| Graphics card            | 13        | 16.46%  |
| Net/wireless             | 11        | 13.92%  |
| Chipcard                 | 10        | 12.66%  |
| Multimedia controller    | 5         | 6.33%   |
| Camera                   | 3         | 3.8%    |
| Sound                    | 2         | 2.53%   |
| Communication controller | 2         | 2.53%   |
| Card reader              | 2         | 2.53%   |
| Unassigned class         | 1         | 1.27%   |
| Storage                  | 1         | 1.27%   |
| Net/ethernet             | 1         | 1.27%   |
| Modem                    | 1         | 1.27%   |
| Bluetooth                | 1         | 1.27%   |

