Linux in Turkey - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Turkey/Desktop/README.md) and [notebooks](/Location/Turkey/Notebook/README.md).

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

Total: 2714

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1525               | Notebook    | [6b0747dcb4](https://linux-hardware.org/?probe=6b0747dcb4) | Sep 07, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [56a481c501](https://linux-hardware.org/?probe=56a481c501) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [44c55bd588](https://linux-hardware.org/?probe=44c55bd588) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [d5abd666d9](https://linux-hardware.org/?probe=d5abd666d9) | Sep 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [9bc8520da8](https://linux-hardware.org/?probe=9bc8520da8) | Sep 04, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [4a93cea12b](https://linux-hardware.org/?probe=4a93cea12b) | Sep 04, 2023 |
| Monster       | Huma H5 V3.2                | Notebook    | [75d95e264e](https://linux-hardware.org/?probe=75d95e264e) | Sep 04, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [e1fdce5232](https://linux-hardware.org/?probe=e1fdce5232) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [56520c8e8d](https://linux-hardware.org/?probe=56520c8e8d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | Notebook    | [13ea608a94](https://linux-hardware.org/?probe=13ea608a94) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [78037f5e38](https://linux-hardware.org/?probe=78037f5e38) | Sep 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [04acccf8e2](https://linux-hardware.org/?probe=04acccf8e2) | Sep 02, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [17206d19f9](https://linux-hardware.org/?probe=17206d19f9) | Sep 01, 2023 |
| HP            | Pavilion 13                 | Notebook    | [ccf98e410b](https://linux-hardware.org/?probe=ccf98e410b) | Sep 01, 2023 |
| HP            | Pavilion 13                 | Notebook    | [b3e756ad21](https://linux-hardware.org/?probe=b3e756ad21) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| HP            | 82DD 0001                   | All in one  | [4d67f21aa7](https://linux-hardware.org/?probe=4d67f21aa7) | Aug 31, 2023 |
| Dell          | Precision 7730              | Notebook    | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9ed00c6987](https://linux-hardware.org/?probe=9ed00c6987) | Aug 30, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [8c492a4b3d](https://linux-hardware.org/?probe=8c492a4b3d) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | Notebook    | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | Notebook    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [7423f83594](https://linux-hardware.org/?probe=7423f83594) | Aug 27, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [bb8b8a594d](https://linux-hardware.org/?probe=bb8b8a594d) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d526f12390](https://linux-hardware.org/?probe=d526f12390) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Dell          | Vostro 5468                 | Notebook    | [2ee2b86d87](https://linux-hardware.org/?probe=2ee2b86d87) | Aug 27, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [b59ee89595](https://linux-hardware.org/?probe=b59ee89595) | Aug 26, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [95ff13464e](https://linux-hardware.org/?probe=95ff13464e) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | Notebook    | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1bd1add449](https://linux-hardware.org/?probe=1bd1add449) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [ab538d0486](https://linux-hardware.org/?probe=ab538d0486) | Aug 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [c86d5e890a](https://linux-hardware.org/?probe=c86d5e890a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a1d2ccf421](https://linux-hardware.org/?probe=a1d2ccf421) | Aug 22, 2023 |
| Acer          | TravelMate P215-52G         | Notebook    | [e8673e8d9c](https://linux-hardware.org/?probe=e8673e8d9c) | Aug 21, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ccecca0639](https://linux-hardware.org/?probe=ccecca0639) | Aug 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c62fc8773a](https://linux-hardware.org/?probe=c62fc8773a) | Aug 21, 2023 |
| Pegatron      | A15                         | Notebook    | [624757036f](https://linux-hardware.org/?probe=624757036f) | Aug 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [45830a7769](https://linux-hardware.org/?probe=45830a7769) | Aug 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d4ba2c046d](https://linux-hardware.org/?probe=d4ba2c046d) | Aug 20, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [19ecc69fc4](https://linux-hardware.org/?probe=19ecc69fc4) | Aug 19, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [caae17275e](https://linux-hardware.org/?probe=caae17275e) | Aug 17, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [684ece88c0](https://linux-hardware.org/?probe=684ece88c0) | Aug 17, 2023 |
| HP            | 3032h                       | Desktop     | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8ddf822ac7](https://linux-hardware.org/?probe=8ddf822ac7) | Aug 16, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [b0c33014c5](https://linux-hardware.org/?probe=b0c33014c5) | Aug 15, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [4b88db67fc](https://linux-hardware.org/?probe=4b88db67fc) | Aug 15, 2023 |
| MSI           | H510M PRO                   | Desktop     | [df350cd466](https://linux-hardware.org/?probe=df350cd466) | Aug 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGS... | Notebook    | [52f2042a47](https://linux-hardware.org/?probe=52f2042a47) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | Notebook    | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | Notebook    | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Lenovo        | ThinkPad L520 5017BW5       | Notebook    | [1a9bbdc058](https://linux-hardware.org/?probe=1a9bbdc058) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [a1c6469145](https://linux-hardware.org/?probe=a1c6469145) | Aug 11, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3c239efc46](https://linux-hardware.org/?probe=3c239efc46) | Aug 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [c7c0f2ad91](https://linux-hardware.org/?probe=c7c0f2ad91) | Aug 10, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aaa92df1c](https://linux-hardware.org/?probe=6aaa92df1c) | Aug 10, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| Dell          | Latitude E7270              | Notebook    | [e7209c4bb7](https://linux-hardware.org/?probe=e7209c4bb7) | Aug 06, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f29d0b0571](https://linux-hardware.org/?probe=f29d0b0571) | Aug 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [1db8a01118](https://linux-hardware.org/?probe=1db8a01118) | Aug 03, 2023 |
| Lenovo        | ThinkPad T400 6475R1G       | Notebook    | [481e1aa044](https://linux-hardware.org/?probe=481e1aa044) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [363bee1696](https://linux-hardware.org/?probe=363bee1696) | Aug 03, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [80498caa0d](https://linux-hardware.org/?probe=80498caa0d) | Aug 03, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [33674f8b81](https://linux-hardware.org/?probe=33674f8b81) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [00311486d2](https://linux-hardware.org/?probe=00311486d2) | Aug 01, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| Unknown       | HP Chromebook 14            | Notebook    | [ef963f6148](https://linux-hardware.org/?probe=ef963f6148) | Jul 31, 2023 |
| Google        | Snow                        | Notebook    | [422a01e612](https://linux-hardware.org/?probe=422a01e612) | Jul 31, 2023 |
| Google        | Peach Pit Rev 6+            | Notebook    | [18fff1679c](https://linux-hardware.org/?probe=18fff1679c) | Jul 31, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7486c0a60b](https://linux-hardware.org/?probe=7486c0a60b) | Jul 31, 2023 |
| Google        | Mighty                      | Notebook    | [6ed9cfe2d0](https://linux-hardware.org/?probe=6ed9cfe2d0) | Jul 31, 2023 |
| Google        | cozmo                       | Soc         | [d77d083f89](https://linux-hardware.org/?probe=d77d083f89) | Jul 31, 2023 |
| Google        | Hana                        | Soc         | [3f818b53ed](https://linux-hardware.org/?probe=3f818b53ed) | Jul 31, 2023 |
| Google        | Hana                        | Soc         | [b6d842b749](https://linux-hardware.org/?probe=b6d842b749) | Jul 31, 2023 |
| Google        | Hanawl                      | Soc         | [08995c0e52](https://linux-hardware.org/?probe=08995c0e52) | Jul 31, 2023 |
| Google        | Kevin                       | Soc         | [19b1046480](https://linux-hardware.org/?probe=19b1046480) | Jul 31, 2023 |
| MSI           | U90/U100                    | Notebook    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Google        | Kevin                       | Notebook    | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [54462345a7](https://linux-hardware.org/?probe=54462345a7) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| I-Life Dig... | ZED Air CX7                 | Notebook    | [2c897f0413](https://linux-hardware.org/?probe=2c897f0413) | Jul 30, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2c6149347b](https://linux-hardware.org/?probe=2c6149347b) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | Notebook    | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| HP            | 250 G3                      | Notebook    | [49b5a143cf](https://linux-hardware.org/?probe=49b5a143cf) | Jul 28, 2023 |
| HP            | 82DD 0001                   | All in one  | [e6da7743f0](https://linux-hardware.org/?probe=e6da7743f0) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [1d4e6c23cf](https://linux-hardware.org/?probe=1d4e6c23cf) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6d6fe6a05b](https://linux-hardware.org/?probe=6d6fe6a05b) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [c2cf59f878](https://linux-hardware.org/?probe=c2cf59f878) | Jul 25, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [b54465e0da](https://linux-hardware.org/?probe=b54465e0da) | Jul 23, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [83d48bc8eb](https://linux-hardware.org/?probe=83d48bc8eb) | Jul 22, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [7387b87abf](https://linux-hardware.org/?probe=7387b87abf) | Jul 21, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [4b7b13a46d](https://linux-hardware.org/?probe=4b7b13a46d) | Jul 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [d688be2c92](https://linux-hardware.org/?probe=d688be2c92) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56a9ce9630](https://linux-hardware.org/?probe=56a9ce9630) | Jul 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [c659d8d6b5](https://linux-hardware.org/?probe=c659d8d6b5) | Jul 17, 2023 |
| Dell          | Latitude D610               | Notebook    | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [bf4a6e7eea](https://linux-hardware.org/?probe=bf4a6e7eea) | Jul 15, 2023 |
| Dell          | G3 3779                     | Notebook    | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | Notebook    | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [be97a731d4](https://linux-hardware.org/?probe=be97a731d4) | Jul 13, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a86a73b50c](https://linux-hardware.org/?probe=a86a73b50c) | Jul 13, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Unknown       | Unknown                     | Soc         | [4bd4266d4b](https://linux-hardware.org/?probe=4bd4266d4b) | Jul 13, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [61ac758cca](https://linux-hardware.org/?probe=61ac758cca) | Jul 10, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| ASUSTek       | X550DP                      | Notebook    | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Dell          | Latitude E6220              | Notebook    | [5e17659f32](https://linux-hardware.org/?probe=5e17659f32) | Jul 09, 2023 |
| Monster       | ABRA A5 V17.3               | Notebook    | [2b65146842](https://linux-hardware.org/?probe=2b65146842) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [c93db722a7](https://linux-hardware.org/?probe=c93db722a7) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d8206bf6c6](https://linux-hardware.org/?probe=d8206bf6c6) | Jul 05, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [53bd77d836](https://linux-hardware.org/?probe=53bd77d836) | Jul 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| Google        | Lick                        | Notebook    | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [36fed79d81](https://linux-hardware.org/?probe=36fed79d81) | Jul 01, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [969994628c](https://linux-hardware.org/?probe=969994628c) | Jun 30, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [53a5b9567e](https://linux-hardware.org/?probe=53a5b9567e) | Jun 30, 2023 |
| ASUSTek       | K501UX                      | Notebook    | [a7fb172b7d](https://linux-hardware.org/?probe=a7fb172b7d) | Jun 30, 2023 |
| Monster       | TULPAR T7 V21.7             | Notebook    | [046803a297](https://linux-hardware.org/?probe=046803a297) | Jun 30, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [5a88d6945d](https://linux-hardware.org/?probe=5a88d6945d) | Jun 29, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c6edbe5681](https://linux-hardware.org/?probe=c6edbe5681) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HP            | G62                         | Notebook    | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [76dd0fc5f1](https://linux-hardware.org/?probe=76dd0fc5f1) | Jun 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [38ae545c1c](https://linux-hardware.org/?probe=38ae545c1c) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | Notebook    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [4f5e2f9201](https://linux-hardware.org/?probe=4f5e2f9201) | Jun 21, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1595a5adbd](https://linux-hardware.org/?probe=1595a5adbd) | Jun 20, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [0cb6da57db](https://linux-hardware.org/?probe=0cb6da57db) | Jun 19, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [17a4ba54ac](https://linux-hardware.org/?probe=17a4ba54ac) | Jun 19, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4681ff2f7d](https://linux-hardware.org/?probe=4681ff2f7d) | Jun 19, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [e7f63885d1](https://linux-hardware.org/?probe=e7f63885d1) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [8fe751618d](https://linux-hardware.org/?probe=8fe751618d) | Jun 18, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [337d8e9d36](https://linux-hardware.org/?probe=337d8e9d36) | Jun 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [fe97518345](https://linux-hardware.org/?probe=fe97518345) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| Dell          | Latitude E6410              | Notebook    | [5eff7cff21](https://linux-hardware.org/?probe=5eff7cff21) | Jun 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [05923edc6b](https://linux-hardware.org/?probe=05923edc6b) | Jun 15, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [e37a7072fd](https://linux-hardware.org/?probe=e37a7072fd) | Jun 13, 2023 |
| MSI           | H510M PRO                   | Desktop     | [08e44766fe](https://linux-hardware.org/?probe=08e44766fe) | Jun 13, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [6febc3ef2e](https://linux-hardware.org/?probe=6febc3ef2e) | Jun 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dc3b9443ef](https://linux-hardware.org/?probe=dc3b9443ef) | Jun 13, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [aac5cdbb4f](https://linux-hardware.org/?probe=aac5cdbb4f) | Jun 12, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [c31b0e5f30](https://linux-hardware.org/?probe=c31b0e5f30) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [95bc101c80](https://linux-hardware.org/?probe=95bc101c80) | Jun 09, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [3371099509](https://linux-hardware.org/?probe=3371099509) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [53cb8df21f](https://linux-hardware.org/?probe=53cb8df21f) | Jun 06, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ba0e7c7d59](https://linux-hardware.org/?probe=ba0e7c7d59) | Jun 04, 2023 |
| Acer          | AO722                       | Notebook    | [b8f2636f02](https://linux-hardware.org/?probe=b8f2636f02) | Jun 04, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [5ee3eec233](https://linux-hardware.org/?probe=5ee3eec233) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Hometech      | Alfa 470C                   | Notebook    | [ee3bd9eb81](https://linux-hardware.org/?probe=ee3bd9eb81) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [a7c067f896](https://linux-hardware.org/?probe=a7c067f896) | Jun 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [d61bd0903e](https://linux-hardware.org/?probe=d61bd0903e) | Jun 02, 2023 |
| Dell          | G3 3579                     | Notebook    | [4e5b0f9800](https://linux-hardware.org/?probe=4e5b0f9800) | May 31, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f6f91b620c](https://linux-hardware.org/?probe=f6f91b620c) | May 31, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [5bf801ac1f](https://linux-hardware.org/?probe=5bf801ac1f) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [a0697218cc](https://linux-hardware.org/?probe=a0697218cc) | May 27, 2023 |
| Monster       | Huma H5 V3.1                | Notebook    | [ed569fe821](https://linux-hardware.org/?probe=ed569fe821) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| IX1401        | Unknown                     | Notebook    | [f1799b6c3a](https://linux-hardware.org/?probe=f1799b6c3a) | May 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [54bddcb324](https://linux-hardware.org/?probe=54bddcb324) | May 24, 2023 |
| ASUSTek       | Maximus V GENE              | Desktop     | [64085de9fe](https://linux-hardware.org/?probe=64085de9fe) | May 24, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [0c665ebdd8](https://linux-hardware.org/?probe=0c665ebdd8) | May 23, 2023 |
| Casper        | EXCALIBUR G770              | Notebook    | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S3XR00    | Notebook    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Medion        | E6224                       | Notebook    | [65c26a4a09](https://linux-hardware.org/?probe=65c26a4a09) | May 23, 2023 |
| Medion        | E6224                       | Notebook    | [8e10b22b1f](https://linux-hardware.org/?probe=8e10b22b1f) | May 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [8b3acda484](https://linux-hardware.org/?probe=8b3acda484) | May 22, 2023 |
| ASUSTek       | X555LNB                     | Notebook    | [a1aa3cf4b2](https://linux-hardware.org/?probe=a1aa3cf4b2) | May 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [3a448141db](https://linux-hardware.org/?probe=3a448141db) | May 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [3e94769b79](https://linux-hardware.org/?probe=3e94769b79) | May 20, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [6bce5f1ff0](https://linux-hardware.org/?probe=6bce5f1ff0) | May 20, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [e33e3678c6](https://linux-hardware.org/?probe=e33e3678c6) | May 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cb9ac11e18](https://linux-hardware.org/?probe=cb9ac11e18) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [d07aa12d74](https://linux-hardware.org/?probe=d07aa12d74) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | Notebook    | [d2908ee6a9](https://linux-hardware.org/?probe=d2908ee6a9) | May 17, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [5553ae2ec9](https://linux-hardware.org/?probe=5553ae2ec9) | May 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [f297fbda85](https://linux-hardware.org/?probe=f297fbda85) | May 16, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [ce2cf2a89a](https://linux-hardware.org/?probe=ce2cf2a89a) | May 15, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [c585628bc8](https://linux-hardware.org/?probe=c585628bc8) | May 14, 2023 |
| Unknown       | Unknown                     | Phone       | [1276781281](https://linux-hardware.org/?probe=1276781281) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | Notebook    | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| ASUSTek       | S451LB                      | Notebook    | [f43e2b2679](https://linux-hardware.org/?probe=f43e2b2679) | May 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Acer          | Aspire A315-58G             | Notebook    | [996701dcbd](https://linux-hardware.org/?probe=996701dcbd) | May 12, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [71f2dc616d](https://linux-hardware.org/?probe=71f2dc616d) | May 12, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6b9e3d06b1](https://linux-hardware.org/?probe=6b9e3d06b1) | May 11, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [68720e9d6b](https://linux-hardware.org/?probe=68720e9d6b) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| HT            | C20C WSTKA001               | Notebook    | [a7ffbb2fe3](https://linux-hardware.org/?probe=a7ffbb2fe3) | May 07, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [93aaae065b](https://linux-hardware.org/?probe=93aaae065b) | May 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [2a8bbbef3d](https://linux-hardware.org/?probe=2a8bbbef3d) | May 06, 2023 |
| Monster       | ABRA A5 V16.4               | Notebook    | [a5507638d0](https://linux-hardware.org/?probe=a5507638d0) | May 06, 2023 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [fff5650658](https://linux-hardware.org/?probe=fff5650658) | May 05, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [e788d3fee0](https://linux-hardware.org/?probe=e788d3fee0) | May 04, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [c68576fce8](https://linux-hardware.org/?probe=c68576fce8) | Apr 30, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1c67ba3f8a](https://linux-hardware.org/?probe=1c67ba3f8a) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8c4ba894b4](https://linux-hardware.org/?probe=8c4ba894b4) | Apr 28, 2023 |
| Supermicro    | X12SPL-F                    | Server      | [8382988ca9](https://linux-hardware.org/?probe=8382988ca9) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | Notebook    | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | Desktop     | [8cbd1dce35](https://linux-hardware.org/?probe=8cbd1dce35) | Apr 26, 2023 |
| IBM           | P4M900/VT8251/DME1737       | Desktop     | [ef0df72346](https://linux-hardware.org/?probe=ef0df72346) | Apr 26, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [f9671dc0a4](https://linux-hardware.org/?probe=f9671dc0a4) | Apr 26, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [2b0ee4d542](https://linux-hardware.org/?probe=2b0ee4d542) | Apr 26, 2023 |
| HP            | 240 G8                      | Notebook    | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | Notebook    | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2d0269750e](https://linux-hardware.org/?probe=2d0269750e) | Apr 24, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [6a6beb844d](https://linux-hardware.org/?probe=6a6beb844d) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [66d61baf71](https://linux-hardware.org/?probe=66d61baf71) | Apr 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [bb1a40d839](https://linux-hardware.org/?probe=bb1a40d839) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [8b18bb529f](https://linux-hardware.org/?probe=8b18bb529f) | Apr 21, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [6d24ab2a04](https://linux-hardware.org/?probe=6d24ab2a04) | Apr 20, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [990cf467d8](https://linux-hardware.org/?probe=990cf467d8) | Apr 19, 2023 |
| Intel         | NUC5CPYB H61145-407         | Mini pc     | [43fc15779a](https://linux-hardware.org/?probe=43fc15779a) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [10e8cc92f1](https://linux-hardware.org/?probe=10e8cc92f1) | Apr 19, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [1e59096b86](https://linux-hardware.org/?probe=1e59096b86) | Apr 19, 2023 |
| Lenovo        | Unknown                     | Notebook    | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Biostar       | G31D-M7                     | Desktop     | [bb518a8623](https://linux-hardware.org/?probe=bb518a8623) | Apr 14, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [6e07b5d9d1](https://linux-hardware.org/?probe=6e07b5d9d1) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | Yoga 710-14IKB 80V4         | Convertible | [a23067158f](https://linux-hardware.org/?probe=a23067158f) | Apr 14, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [62dd8e069f](https://linux-hardware.org/?probe=62dd8e069f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Sony          | VPCEB3J1E                   | Notebook    | [1405405cbb](https://linux-hardware.org/?probe=1405405cbb) | Apr 11, 2023 |
| HP            | 18E6                        | Desktop     | [d7cf5918eb](https://linux-hardware.org/?probe=d7cf5918eb) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2a108e9eed](https://linux-hardware.org/?probe=2a108e9eed) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c2e1cb3f46](https://linux-hardware.org/?probe=c2e1cb3f46) | Apr 09, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [023591084f](https://linux-hardware.org/?probe=023591084f) | Apr 07, 2023 |
| Dell          | 057FFP A01                  | Desktop     | [683dea4da0](https://linux-hardware.org/?probe=683dea4da0) | Apr 07, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5349814c06](https://linux-hardware.org/?probe=5349814c06) | Apr 07, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [5d0731fb7a](https://linux-hardware.org/?probe=5d0731fb7a) | Apr 05, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| Acer          | Aspire 5220                 | Notebook    | [d22076fd54](https://linux-hardware.org/?probe=d22076fd54) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b55be43d4c](https://linux-hardware.org/?probe=b55be43d4c) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [78bda6a16c](https://linux-hardware.org/?probe=78bda6a16c) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [38dc8922e4](https://linux-hardware.org/?probe=38dc8922e4) | Apr 03, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [9148a1d487](https://linux-hardware.org/?probe=9148a1d487) | Apr 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [282031e979](https://linux-hardware.org/?probe=282031e979) | Mar 30, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [920f4a2dc2](https://linux-hardware.org/?probe=920f4a2dc2) | Mar 30, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [31a96824ea](https://linux-hardware.org/?probe=31a96824ea) | Mar 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| Pegatron      | IPMIP-H55-GEN               | Desktop     | [7dcf9e9b51](https://linux-hardware.org/?probe=7dcf9e9b51) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASUSTek       | E502NA                      | Notebook    | [a116400859](https://linux-hardware.org/?probe=a116400859) | Mar 27, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d7b97732fa](https://linux-hardware.org/?probe=d7b97732fa) | Mar 26, 2023 |
| Monster       | TULPAR T7 V19.5             | Notebook    | [4a4933c183](https://linux-hardware.org/?probe=4a4933c183) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [d2ebb46bea](https://linux-hardware.org/?probe=d2ebb46bea) | Mar 25, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| HP            | Pavilion dv6                | Notebook    | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [de7c54aec1](https://linux-hardware.org/?probe=de7c54aec1) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [fdea1b7da5](https://linux-hardware.org/?probe=fdea1b7da5) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [ad5218c0bf](https://linux-hardware.org/?probe=ad5218c0bf) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [32ba732ef0](https://linux-hardware.org/?probe=32ba732ef0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| Lenovo        | Flex 2-15                   | Notebook    | [6bea7b508e](https://linux-hardware.org/?probe=6bea7b508e) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [66f69d578c](https://linux-hardware.org/?probe=66f69d578c) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | Notebook    | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [d5b197e7f2](https://linux-hardware.org/?probe=d5b197e7f2) | Mar 12, 2023 |
| HP            | 0A64h                       | Desktop     | [14de22ae05](https://linux-hardware.org/?probe=14de22ae05) | Mar 11, 2023 |
| Toshiba       | Satellite C55-A-1K4         | Notebook    | [3ba10eda08](https://linux-hardware.org/?probe=3ba10eda08) | Mar 11, 2023 |
| MSI           | Alpha 15 A3DC               | Notebook    | [feabd7f5bf](https://linux-hardware.org/?probe=feabd7f5bf) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [44db3bc5ec](https://linux-hardware.org/?probe=44db3bc5ec) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [96e374345a](https://linux-hardware.org/?probe=96e374345a) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b5f8598cfd](https://linux-hardware.org/?probe=b5f8598cfd) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | Notebook    | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [e55325be18](https://linux-hardware.org/?probe=e55325be18) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [39805e4790](https://linux-hardware.org/?probe=39805e4790) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [d12e99f5d2](https://linux-hardware.org/?probe=d12e99f5d2) | Mar 09, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| Sony          | SVD11225CXB                 | Notebook    | [b5b755e185](https://linux-hardware.org/?probe=b5b755e185) | Mar 07, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [8961f32cc5](https://linux-hardware.org/?probe=8961f32cc5) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [d1a37d82cb](https://linux-hardware.org/?probe=d1a37d82cb) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [80ee932665](https://linux-hardware.org/?probe=80ee932665) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [c112aacdb6](https://linux-hardware.org/?probe=c112aacdb6) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [ccd91fb0c7](https://linux-hardware.org/?probe=ccd91fb0c7) | Mar 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1ccfddfbc0](https://linux-hardware.org/?probe=1ccfddfbc0) | Mar 04, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [4cb64cfa8f](https://linux-hardware.org/?probe=4cb64cfa8f) | Mar 03, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [e230d5c136](https://linux-hardware.org/?probe=e230d5c136) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | Notebook    | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [e0864b4a50](https://linux-hardware.org/?probe=e0864b4a50) | Mar 02, 2023 |
| HP            | 15                          | Notebook    | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| Unknown       | Unknown                     | Phone       | [a9c7699598](https://linux-hardware.org/?probe=a9c7699598) | Feb 28, 2023 |
| ASUSTek       | X55A                        | Notebook    | [1429627725](https://linux-hardware.org/?probe=1429627725) | Feb 28, 2023 |
| Alienware     | 15 R2                       | Notebook    | [5e29609544](https://linux-hardware.org/?probe=5e29609544) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | Notebook    | [68a816d082](https://linux-hardware.org/?probe=68a816d082) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | Notebook    | [bbb8c4e905](https://linux-hardware.org/?probe=bbb8c4e905) | Feb 28, 2023 |
| Casper        | H510 001 G10a               | Desktop     | [95a9cfbf0b](https://linux-hardware.org/?probe=95a9cfbf0b) | Feb 27, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [72034abe27](https://linux-hardware.org/?probe=72034abe27) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7ff7ca240](https://linux-hardware.org/?probe=c7ff7ca240) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [246492391c](https://linux-hardware.org/?probe=246492391c) | Feb 23, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [29673d3e8f](https://linux-hardware.org/?probe=29673d3e8f) | Feb 22, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [be36fee6eb](https://linux-hardware.org/?probe=be36fee6eb) | Feb 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [40468a72ce](https://linux-hardware.org/?probe=40468a72ce) | Feb 20, 2023 |
| ASUSTek       | V161GAR                     | All in one  | [e8277425a5](https://linux-hardware.org/?probe=e8277425a5) | Feb 20, 2023 |
| ASUSTek       | M3N78-VM                    | Desktop     | [c124cec382](https://linux-hardware.org/?probe=c124cec382) | Feb 19, 2023 |
| Sony          | VPCCB16FG                   | Notebook    | [0a6224bcc3](https://linux-hardware.org/?probe=0a6224bcc3) | Feb 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [3543a34ca0](https://linux-hardware.org/?probe=3543a34ca0) | Feb 19, 2023 |
| HP            | Notebook                    | Notebook    | [2d03543f4c](https://linux-hardware.org/?probe=2d03543f4c) | Feb 18, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [75db698bfd](https://linux-hardware.org/?probe=75db698bfd) | Feb 18, 2023 |
| Casper        | H510 001 G10a               | Desktop     | [56402bade6](https://linux-hardware.org/?probe=56402bade6) | Feb 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [02d91d3f00](https://linux-hardware.org/?probe=02d91d3f00) | Feb 17, 2023 |
| Lenovo        | ThinkPad X220 4291ZD8       | Notebook    | [9dbad47bf0](https://linux-hardware.org/?probe=9dbad47bf0) | Feb 16, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [63789621e0](https://linux-hardware.org/?probe=63789621e0) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [514bbe20b5](https://linux-hardware.org/?probe=514bbe20b5) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [f0d6ada218](https://linux-hardware.org/?probe=f0d6ada218) | Feb 15, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ef50e45214](https://linux-hardware.org/?probe=ef50e45214) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Pegatron      | H36ST                       | Notebook    | [2b0e74ca00](https://linux-hardware.org/?probe=2b0e74ca00) | Feb 13, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [18cd6aad2c](https://linux-hardware.org/?probe=18cd6aad2c) | Feb 11, 2023 |
| HP            | 15                          | Notebook    | [162c6f9186](https://linux-hardware.org/?probe=162c6f9186) | Feb 11, 2023 |
| Lenovo        | ThinkPad X280 20KES2WC06    | Notebook    | [794dcaf42d](https://linux-hardware.org/?probe=794dcaf42d) | Feb 11, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [ea2304bdfe](https://linux-hardware.org/?probe=ea2304bdfe) | Feb 10, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [c3a837a320](https://linux-hardware.org/?probe=c3a837a320) | Feb 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a410a7b784](https://linux-hardware.org/?probe=a410a7b784) | Feb 09, 2023 |
| Timi          | TM1701                      | Notebook    | [b3015735e6](https://linux-hardware.org/?probe=b3015735e6) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | Notebook    | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | Notebook    | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [1d05e35623](https://linux-hardware.org/?probe=1d05e35623) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [ffce390164](https://linux-hardware.org/?probe=ffce390164) | Feb 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [7fd90f29c1](https://linux-hardware.org/?probe=7fd90f29c1) | Feb 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e1fc422565](https://linux-hardware.org/?probe=e1fc422565) | Feb 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [234f1c81c2](https://linux-hardware.org/?probe=234f1c81c2) | Feb 07, 2023 |
| Packard Be... | SJV50MV                     | Notebook    | [930ac749ca](https://linux-hardware.org/?probe=930ac749ca) | Feb 07, 2023 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [f632cba0a7](https://linux-hardware.org/?probe=f632cba0a7) | Feb 07, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f1e58aba53](https://linux-hardware.org/?probe=f1e58aba53) | Feb 06, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [295fd70d70](https://linux-hardware.org/?probe=295fd70d70) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [5b16a4a572](https://linux-hardware.org/?probe=5b16a4a572) | Feb 05, 2023 |
| Packard Be... | SJV50MV                     | Notebook    | [ff862a12ae](https://linux-hardware.org/?probe=ff862a12ae) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.3             | Notebook    | [82f58f57c0](https://linux-hardware.org/?probe=82f58f57c0) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.1             | Notebook    | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [a694854d87](https://linux-hardware.org/?probe=a694854d87) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | Notebook    | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| HP            | Notebook                    | Notebook    | [82068da14b](https://linux-hardware.org/?probe=82068da14b) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [2d4aa2e1a0](https://linux-hardware.org/?probe=2d4aa2e1a0) | Feb 01, 2023 |
| Toshiba       | Satellite R630              | Notebook    | [52ffe609b8](https://linux-hardware.org/?probe=52ffe609b8) | Jan 31, 2023 |
| Dell          | Latitude E6530              | Notebook    | [140543c98c](https://linux-hardware.org/?probe=140543c98c) | Jan 31, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [3be362b4aa](https://linux-hardware.org/?probe=3be362b4aa) | Jan 31, 2023 |
| Sony          | VPCCB16FG                   | Notebook    | [837588c9eb](https://linux-hardware.org/?probe=837588c9eb) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Sony          | VPCCB16FG                   | Notebook    | [7307480466](https://linux-hardware.org/?probe=7307480466) | Jan 29, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [d4a5012f93](https://linux-hardware.org/?probe=d4a5012f93) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [e789456756](https://linux-hardware.org/?probe=e789456756) | Jan 28, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [cba2528a29](https://linux-hardware.org/?probe=cba2528a29) | Jan 28, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [0cda1a95a2](https://linux-hardware.org/?probe=0cda1a95a2) | Jan 28, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| HP            | ProBook 6460b               | Notebook    | [81a1748477](https://linux-hardware.org/?probe=81a1748477) | Jan 25, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [c66369d864](https://linux-hardware.org/?probe=c66369d864) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7572089dc3](https://linux-hardware.org/?probe=7572089dc3) | Jan 23, 2023 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [a7219ed5ef](https://linux-hardware.org/?probe=a7219ed5ef) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b37f2fcaba](https://linux-hardware.org/?probe=b37f2fcaba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [0e29c1dd04](https://linux-hardware.org/?probe=0e29c1dd04) | Jan 22, 2023 |
| MSI           | H510M PRO                   | Desktop     | [309f1bc61b](https://linux-hardware.org/?probe=309f1bc61b) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [395d565464](https://linux-hardware.org/?probe=395d565464) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [fcce46f618](https://linux-hardware.org/?probe=fcce46f618) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [f79928ed4d](https://linux-hardware.org/?probe=f79928ed4d) | Jan 21, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [54cf7414fd](https://linux-hardware.org/?probe=54cf7414fd) | Jan 20, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [787c98df69](https://linux-hardware.org/?probe=787c98df69) | Jan 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d828f8f4a8](https://linux-hardware.org/?probe=d828f8f4a8) | Jan 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [282b1007ac](https://linux-hardware.org/?probe=282b1007ac) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8c8cf26214](https://linux-hardware.org/?probe=8c8cf26214) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | ThinkPad SL500 2746A18      | Notebook    | [5535380e6c](https://linux-hardware.org/?probe=5535380e6c) | Jan 16, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [0a323f0cb8](https://linux-hardware.org/?probe=0a323f0cb8) | Jan 15, 2023 |
| Monster       | TULPAR T5 V19.2             | Notebook    | [46bd0385fa](https://linux-hardware.org/?probe=46bd0385fa) | Jan 15, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [6ff8ef1eb3](https://linux-hardware.org/?probe=6ff8ef1eb3) | Jan 15, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [4332a351bf](https://linux-hardware.org/?probe=4332a351bf) | Jan 13, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [fc41631096](https://linux-hardware.org/?probe=fc41631096) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [14d0dddfc9](https://linux-hardware.org/?probe=14d0dddfc9) | Jan 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [eb61471644](https://linux-hardware.org/?probe=eb61471644) | Jan 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2a71b87b09](https://linux-hardware.org/?probe=2a71b87b09) | Jan 11, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [46dfb4ddef](https://linux-hardware.org/?probe=46dfb4ddef) | Jan 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [93ffaa0920](https://linux-hardware.org/?probe=93ffaa0920) | Jan 11, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [805d82d697](https://linux-hardware.org/?probe=805d82d697) | Jan 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [010a4fc9bd](https://linux-hardware.org/?probe=010a4fc9bd) | Jan 10, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [401e0c3743](https://linux-hardware.org/?probe=401e0c3743) | Jan 10, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [179af39858](https://linux-hardware.org/?probe=179af39858) | Jan 08, 2023 |
| ODM           | MS-16K2                     | Notebook    | [f9a7d267e5](https://linux-hardware.org/?probe=f9a7d267e5) | Jan 08, 2023 |
| MSI           | GF63 8RC                    | Notebook    | [9222c5a0a6](https://linux-hardware.org/?probe=9222c5a0a6) | Jan 08, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [fba9812651](https://linux-hardware.org/?probe=fba9812651) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ef45fa4056](https://linux-hardware.org/?probe=ef45fa4056) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [36c97306ae](https://linux-hardware.org/?probe=36c97306ae) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [0ee14d767d](https://linux-hardware.org/?probe=0ee14d767d) | Jan 06, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [0990a5e3e8](https://linux-hardware.org/?probe=0990a5e3e8) | Jan 05, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [78a3773180](https://linux-hardware.org/?probe=78a3773180) | Jan 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [c7d37a7616](https://linux-hardware.org/?probe=c7d37a7616) | Jan 04, 2023 |
| Monster       | Huma H5 V3.2                | Notebook    | [cab22e2b7b](https://linux-hardware.org/?probe=cab22e2b7b) | Jan 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [113d6b92d1](https://linux-hardware.org/?probe=113d6b92d1) | Jan 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [7783f397ec](https://linux-hardware.org/?probe=7783f397ec) | Jan 03, 2023 |
| MSI           | 880GMA-E45                  | Desktop     | [f55d2f2c90](https://linux-hardware.org/?probe=f55d2f2c90) | Jan 03, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [b1d353931a](https://linux-hardware.org/?probe=b1d353931a) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [20e752831c](https://linux-hardware.org/?probe=20e752831c) | Jan 01, 2023 |
| Dell          | G3 3500                     | Notebook    | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| Dell          | Latitude 5521               | Notebook    | [32d3e87886](https://linux-hardware.org/?probe=32d3e87886) | Dec 25, 2022 |
| Hometech      | Alfa 420C                   | Notebook    | [9dcf2c28b3](https://linux-hardware.org/?probe=9dcf2c28b3) | Dec 23, 2022 |
| Hometech      | Alfa 420C                   | Notebook    | [5a4f33dd7b](https://linux-hardware.org/?probe=5a4f33dd7b) | Dec 22, 2022 |
| Monster       | ABRA A5 V18.1               | Notebook    | [d151d1eb82](https://linux-hardware.org/?probe=d151d1eb82) | Dec 21, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [12bb45433d](https://linux-hardware.org/?probe=12bb45433d) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [87d3186549](https://linux-hardware.org/?probe=87d3186549) | Dec 20, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d79e681980](https://linux-hardware.org/?probe=d79e681980) | Dec 19, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [72bfd0a0f6](https://linux-hardware.org/?probe=72bfd0a0f6) | Dec 19, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [7d5ca26325](https://linux-hardware.org/?probe=7d5ca26325) | Dec 19, 2022 |
| Dell          | Latitude 5521               | Notebook    | [3d3be9c8e9](https://linux-hardware.org/?probe=3d3be9c8e9) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| Pegatron      | H36FF                       | Notebook    | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [58eac3b208](https://linux-hardware.org/?probe=58eac3b208) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [8641a184ad](https://linux-hardware.org/?probe=8641a184ad) | Dec 17, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Lenovo        | Flex 2-15                   | Notebook    | [38670ac27c](https://linux-hardware.org/?probe=38670ac27c) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Pegatron      | IPXSB-H61                   | Desktop     | [84c0b45a3b](https://linux-hardware.org/?probe=84c0b45a3b) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [e4f2e85204](https://linux-hardware.org/?probe=e4f2e85204) | Dec 14, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6dec5de4a9](https://linux-hardware.org/?probe=6dec5de4a9) | Dec 13, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b822420d6d](https://linux-hardware.org/?probe=b822420d6d) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [9ba738605c](https://linux-hardware.org/?probe=9ba738605c) | Dec 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [bb540dbfb1](https://linux-hardware.org/?probe=bb540dbfb1) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2a7f909902](https://linux-hardware.org/?probe=2a7f909902) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [92f4bd5ee1](https://linux-hardware.org/?probe=92f4bd5ee1) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f8e78fbf31](https://linux-hardware.org/?probe=f8e78fbf31) | Dec 06, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ab7d61cced](https://linux-hardware.org/?probe=ab7d61cced) | Dec 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cf810b2e09](https://linux-hardware.org/?probe=cf810b2e09) | Dec 04, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [97a1793680](https://linux-hardware.org/?probe=97a1793680) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [02f4319195](https://linux-hardware.org/?probe=02f4319195) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [77ad02b5bd](https://linux-hardware.org/?probe=77ad02b5bd) | Nov 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [291b53ea79](https://linux-hardware.org/?probe=291b53ea79) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [ceda4dbb46](https://linux-hardware.org/?probe=ceda4dbb46) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | Notebook    | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [a116300d12](https://linux-hardware.org/?probe=a116300d12) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [a30ad69ac2](https://linux-hardware.org/?probe=a30ad69ac2) | Nov 27, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [ef46869de3](https://linux-hardware.org/?probe=ef46869de3) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4246d4813a](https://linux-hardware.org/?probe=4246d4813a) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [76f6ba932f](https://linux-hardware.org/?probe=76f6ba932f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [6d87497f34](https://linux-hardware.org/?probe=6d87497f34) | Nov 23, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [f02593fc75](https://linux-hardware.org/?probe=f02593fc75) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [5f040880ce](https://linux-hardware.org/?probe=5f040880ce) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [aecddcf17e](https://linux-hardware.org/?probe=aecddcf17e) | Nov 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Acer          | TravelMate 5360             | Notebook    | [c2dfb8625b](https://linux-hardware.org/?probe=c2dfb8625b) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [af679e6195](https://linux-hardware.org/?probe=af679e6195) | Nov 17, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d3d2afd2c3](https://linux-hardware.org/?probe=d3d2afd2c3) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [15087fec90](https://linux-hardware.org/?probe=15087fec90) | Nov 16, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [9a588b78c3](https://linux-hardware.org/?probe=9a588b78c3) | Nov 16, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [930beb6857](https://linux-hardware.org/?probe=930beb6857) | Nov 16, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [70071adfb0](https://linux-hardware.org/?probe=70071adfb0) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca24381492](https://linux-hardware.org/?probe=ca24381492) | Nov 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [1cb724a4d5](https://linux-hardware.org/?probe=1cb724a4d5) | Nov 15, 2022 |
| MSI           | Z97I GAMING AC              | Desktop     | [b0a5c0251f](https://linux-hardware.org/?probe=b0a5c0251f) | Nov 15, 2022 |
| Pegatron      | IPXSB-H61                   | Desktop     | [9de70711ef](https://linux-hardware.org/?probe=9de70711ef) | Nov 15, 2022 |
| HP            | 530                         | Notebook    | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [700e2ffc46](https://linux-hardware.org/?probe=700e2ffc46) | Nov 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b966d9e8c9](https://linux-hardware.org/?probe=b966d9e8c9) | Nov 13, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [052f42f29a](https://linux-hardware.org/?probe=052f42f29a) | Nov 12, 2022 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| Monster       | ABRA A5 V15.6               | Notebook    | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [02944a1b38](https://linux-hardware.org/?probe=02944a1b38) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5a5633f611](https://linux-hardware.org/?probe=5a5633f611) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [ac916f47fc](https://linux-hardware.org/?probe=ac916f47fc) | Nov 08, 2022 |
| Monster       | TULPAR T7 V21.7             | Notebook    | [1106dc2d92](https://linux-hardware.org/?probe=1106dc2d92) | Nov 07, 2022 |
| ASUSTek       | UX490UAR                    | Notebook    | [dc90947100](https://linux-hardware.org/?probe=dc90947100) | Nov 07, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [32bb86a1e6](https://linux-hardware.org/?probe=32bb86a1e6) | Nov 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [c91e77c03a](https://linux-hardware.org/?probe=c91e77c03a) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [8c532d2ad0](https://linux-hardware.org/?probe=8c532d2ad0) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| XDO.AI        | Pantera Pico PC             | Desktop     | [faf3c3a1ae](https://linux-hardware.org/?probe=faf3c3a1ae) | Nov 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [aa9fe4c05c](https://linux-hardware.org/?probe=aa9fe4c05c) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | Notebook    | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [2c3ddc79ce](https://linux-hardware.org/?probe=2c3ddc79ce) | Nov 04, 2022 |
| HP            | Pavilion 15                 | Notebook    | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [c2d1799732](https://linux-hardware.org/?probe=c2d1799732) | Oct 29, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2ca56cb740](https://linux-hardware.org/?probe=2ca56cb740) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [b086433e61](https://linux-hardware.org/?probe=b086433e61) | Oct 26, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| Lenovo        | ThinkPad 10 20C3S0X000      | Tablet      | [f17ef87aca](https://linux-hardware.org/?probe=f17ef87aca) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ffe63e6795](https://linux-hardware.org/?probe=ffe63e6795) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [b0700ec521](https://linux-hardware.org/?probe=b0700ec521) | Oct 24, 2022 |
| Monster       | HUMA H4 V4.1                | Notebook    | [06a31b0132](https://linux-hardware.org/?probe=06a31b0132) | Oct 24, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [5d01101cee](https://linux-hardware.org/?probe=5d01101cee) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| Monster       | ABRA A5 V15.2               | Notebook    | [cb1a5559dc](https://linux-hardware.org/?probe=cb1a5559dc) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [9dffa26de0](https://linux-hardware.org/?probe=9dffa26de0) | Oct 20, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Monster       | TULPAR T5 V21.6             | Notebook    | [eaeb6f6610](https://linux-hardware.org/?probe=eaeb6f6610) | Oct 17, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [210d7fdd5d](https://linux-hardware.org/?probe=210d7fdd5d) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [cf556bb7f7](https://linux-hardware.org/?probe=cf556bb7f7) | Oct 16, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a8a52af0f4](https://linux-hardware.org/?probe=a8a52af0f4) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Pegatron      | 2A84h                       | Desktop     | [5b46511238](https://linux-hardware.org/?probe=5b46511238) | Oct 15, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [adbd1fa089](https://linux-hardware.org/?probe=adbd1fa089) | Oct 14, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [b8ba7e41c8](https://linux-hardware.org/?probe=b8ba7e41c8) | Oct 14, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [c0fefb30fe](https://linux-hardware.org/?probe=c0fefb30fe) | Oct 12, 2022 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [82d2063927](https://linux-hardware.org/?probe=82d2063927) | Oct 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bf2c25a350](https://linux-hardware.org/?probe=bf2c25a350) | Oct 12, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [517cb3cb75](https://linux-hardware.org/?probe=517cb3cb75) | Oct 11, 2022 |
| ASUSTek       | Vivobook Slate T3300KA_T... | Tablet      | [cf1735bf9e](https://linux-hardware.org/?probe=cf1735bf9e) | Oct 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [09225a1f01](https://linux-hardware.org/?probe=09225a1f01) | Oct 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [a2979dfe6d](https://linux-hardware.org/?probe=a2979dfe6d) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e9928bbd81](https://linux-hardware.org/?probe=e9928bbd81) | Oct 10, 2022 |
| HP            | 81C5 MVB                    | Desktop     | [1f08f2d239](https://linux-hardware.org/?probe=1f08f2d239) | Oct 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [582de9d5d6](https://linux-hardware.org/?probe=582de9d5d6) | Oct 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f1b7cbae01](https://linux-hardware.org/?probe=f1b7cbae01) | Oct 09, 2022 |
| HP            | 340S G7                     | Notebook    | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [92998a2fa1](https://linux-hardware.org/?probe=92998a2fa1) | Oct 07, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [3f310e92ed](https://linux-hardware.org/?probe=3f310e92ed) | Oct 07, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [87936d87c6](https://linux-hardware.org/?probe=87936d87c6) | Oct 06, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2109e3f7b1](https://linux-hardware.org/?probe=2109e3f7b1) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | Notebook    | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [5794de3528](https://linux-hardware.org/?probe=5794de3528) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [ed89b0d272](https://linux-hardware.org/?probe=ed89b0d272) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| MSI           | H110M GAMING                | Desktop     | [379aaceaab](https://linux-hardware.org/?probe=379aaceaab) | Oct 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [bd8ce563ff](https://linux-hardware.org/?probe=bd8ce563ff) | Oct 03, 2022 |
| MSI           | A75A-G35                    | Desktop     | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Casper        | C15B                        | Desktop     | [be4c7469a6](https://linux-hardware.org/?probe=be4c7469a6) | Oct 01, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c6e67f7643](https://linux-hardware.org/?probe=c6e67f7643) | Oct 01, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5f1d0e6142](https://linux-hardware.org/?probe=5f1d0e6142) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [70a80b4201](https://linux-hardware.org/?probe=70a80b4201) | Sep 30, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [f0d1b90e89](https://linux-hardware.org/?probe=f0d1b90e89) | Sep 29, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [36ff9b8bcb](https://linux-hardware.org/?probe=36ff9b8bcb) | Sep 29, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [2e6164b675](https://linux-hardware.org/?probe=2e6164b675) | Sep 28, 2022 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [04589a6a6c](https://linux-hardware.org/?probe=04589a6a6c) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [98742c4135](https://linux-hardware.org/?probe=98742c4135) | Sep 27, 2022 |
| MSI           | B560M PRO                   | Desktop     | [5949440926](https://linux-hardware.org/?probe=5949440926) | Sep 26, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Dell          | Precision 7550              | Notebook    | [347372a20a](https://linux-hardware.org/?probe=347372a20a) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [23f17e2f91](https://linux-hardware.org/?probe=23f17e2f91) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Casper        | NIRVANA DESKTOP             | Desktop     | [7cdffad4a2](https://linux-hardware.org/?probe=7cdffad4a2) | Sep 18, 2022 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [d401319e57](https://linux-hardware.org/?probe=d401319e57) | Sep 17, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| HP            | EliteBook 1040 G4           | Notebook    | [9b4136a781](https://linux-hardware.org/?probe=9b4136a781) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [5ae6fea41e](https://linux-hardware.org/?probe=5ae6fea41e) | Sep 13, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [788cf883c5](https://linux-hardware.org/?probe=788cf883c5) | Sep 10, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [ce084887f1](https://linux-hardware.org/?probe=ce084887f1) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [be18103b06](https://linux-hardware.org/?probe=be18103b06) | Sep 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [57235f1260](https://linux-hardware.org/?probe=57235f1260) | Sep 05, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [7d505ec2d3](https://linux-hardware.org/?probe=7d505ec2d3) | Sep 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4071a8ff9b](https://linux-hardware.org/?probe=4071a8ff9b) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | Notebook    | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5ba264dfb2](https://linux-hardware.org/?probe=5ba264dfb2) | Sep 01, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [169c9af937](https://linux-hardware.org/?probe=169c9af937) | Sep 01, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [7a5978071e](https://linux-hardware.org/?probe=7a5978071e) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6462d2370f](https://linux-hardware.org/?probe=6462d2370f) | Aug 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [eb79e6b28e](https://linux-hardware.org/?probe=eb79e6b28e) | Aug 31, 2022 |
| HUAWEI        | CREF-XX                     | Notebook    | [4ea2674cd8](https://linux-hardware.org/?probe=4ea2674cd8) | Aug 31, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [05c3d5d7b7](https://linux-hardware.org/?probe=05c3d5d7b7) | Aug 30, 2022 |
| Monster       | Huma H5 V3.2                | Notebook    | [ea050f24db](https://linux-hardware.org/?probe=ea050f24db) | Aug 29, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1337a4c8e9](https://linux-hardware.org/?probe=1337a4c8e9) | Aug 28, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [41459260b8](https://linux-hardware.org/?probe=41459260b8) | Aug 27, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [e05d9e51d5](https://linux-hardware.org/?probe=e05d9e51d5) | Aug 27, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [11867009b0](https://linux-hardware.org/?probe=11867009b0) | Aug 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [909b7dcd37](https://linux-hardware.org/?probe=909b7dcd37) | Aug 26, 2022 |
| Acer          | TravelMate 5742G            | Notebook    | [37418dc2c7](https://linux-hardware.org/?probe=37418dc2c7) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| Timi          | TM1701                      | Notebook    | [4591dee526](https://linux-hardware.org/?probe=4591dee526) | Aug 21, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [e762245df3](https://linux-hardware.org/?probe=e762245df3) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | Notebook    | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1f85d6a1b9](https://linux-hardware.org/?probe=1f85d6a1b9) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ccea67d380](https://linux-hardware.org/?probe=ccea67d380) | Aug 19, 2022 |
| Toshiba       | QOSMIO X70-B                | Notebook    | [9d599f3d84](https://linux-hardware.org/?probe=9d599f3d84) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| Dell          | Latitude 3510               | Notebook    | [97e3f5102d](https://linux-hardware.org/?probe=97e3f5102d) | Aug 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [c0c3232fad](https://linux-hardware.org/?probe=c0c3232fad) | Aug 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZC_GZ3... | Tablet      | [76550f7aef](https://linux-hardware.org/?probe=76550f7aef) | Aug 15, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [dd375c139f](https://linux-hardware.org/?probe=dd375c139f) | Aug 14, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7cd120b2e1](https://linux-hardware.org/?probe=7cd120b2e1) | Aug 14, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [db33232b90](https://linux-hardware.org/?probe=db33232b90) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [f0c5f6a834](https://linux-hardware.org/?probe=f0c5f6a834) | Aug 07, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ba034abead](https://linux-hardware.org/?probe=ba034abead) | Aug 07, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | Desktop     | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Monster       | ABRA A5 V13.1               | Notebook    | [557923ae7f](https://linux-hardware.org/?probe=557923ae7f) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [55af061736](https://linux-hardware.org/?probe=55af061736) | Aug 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [705f31df94](https://linux-hardware.org/?probe=705f31df94) | Aug 05, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [9edf66f0ec](https://linux-hardware.org/?probe=9edf66f0ec) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [06852d59ac](https://linux-hardware.org/?probe=06852d59ac) | Aug 04, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [057187b6c9](https://linux-hardware.org/?probe=057187b6c9) | Aug 04, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | Notebook    | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| Sony          | SVE1113M1EW                 | Notebook    | [7a18b67232](https://linux-hardware.org/?probe=7a18b67232) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [110c94eb72](https://linux-hardware.org/?probe=110c94eb72) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | Notebook    | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | Notebook    | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| HP            | 81C6 MVB 0C                 | Server      | [7f5bd87d2e](https://linux-hardware.org/?probe=7f5bd87d2e) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [ef6984a3a9](https://linux-hardware.org/?probe=ef6984a3a9) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Acer          | Veriton ES2740G V:1.0       | Desktop     | [e14aeaaca3](https://linux-hardware.org/?probe=e14aeaaca3) | Jul 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| Monster       | ABRA A5 V16.6               | Notebook    | [d26a2b3f0a](https://linux-hardware.org/?probe=d26a2b3f0a) | Jul 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8bf5cae166](https://linux-hardware.org/?probe=8bf5cae166) | Jul 23, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | Notebook    | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ARCELIK       | 1S7-GNB1586B1I5             | Notebook    | [e9a81688b3](https://linux-hardware.org/?probe=e9a81688b3) | Jul 20, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [f74458bf19](https://linux-hardware.org/?probe=f74458bf19) | Jul 19, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [720cc9c1ce](https://linux-hardware.org/?probe=720cc9c1ce) | Jul 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [b85c907afc](https://linux-hardware.org/?probe=b85c907afc) | Jul 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [5528f26010](https://linux-hardware.org/?probe=5528f26010) | Jul 19, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [2ddc53797a](https://linux-hardware.org/?probe=2ddc53797a) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Pegatron      | D15K                        | Notebook    | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| ASUSTek       | X553SA                      | Notebook    | [f28ef11fe2](https://linux-hardware.org/?probe=f28ef11fe2) | Jul 15, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [2ba7d6af57](https://linux-hardware.org/?probe=2ba7d6af57) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [06992e615b](https://linux-hardware.org/?probe=06992e615b) | Jul 15, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [d25b4ecc69](https://linux-hardware.org/?probe=d25b4ecc69) | Jul 11, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [9d74a4a9cb](https://linux-hardware.org/?probe=9d74a4a9cb) | Jul 10, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [09bdb4be6a](https://linux-hardware.org/?probe=09bdb4be6a) | Jul 08, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f4d2c6bb1e](https://linux-hardware.org/?probe=f4d2c6bb1e) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| Pegatron      | H36FF                       | Notebook    | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [825362cafe](https://linux-hardware.org/?probe=825362cafe) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [f852861149](https://linux-hardware.org/?probe=f852861149) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6b942bfd10](https://linux-hardware.org/?probe=6b942bfd10) | Jul 05, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [ab366fcbe6](https://linux-hardware.org/?probe=ab366fcbe6) | Jul 05, 2022 |
| HP            | 83EE                        | Desktop     | [a49f00b158](https://linux-hardware.org/?probe=a49f00b158) | Jul 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [cea4b92a7d](https://linux-hardware.org/?probe=cea4b92a7d) | Jul 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [0ffa87cfad](https://linux-hardware.org/?probe=0ffa87cfad) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| HP            | 84DE                        | All in one  | [8af29f9d6c](https://linux-hardware.org/?probe=8af29f9d6c) | Jul 04, 2022 |
| ASUSTek       | X553SA                      | Notebook    | [e3cd0aa8d4](https://linux-hardware.org/?probe=e3cd0aa8d4) | Jul 02, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [63da8fa3b9](https://linux-hardware.org/?probe=63da8fa3b9) | Jul 02, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [d352a1c731](https://linux-hardware.org/?probe=d352a1c731) | Jul 02, 2022 |
| ASUSTek       | H61M-PRO                    | Desktop     | [48464c0df0](https://linux-hardware.org/?probe=48464c0df0) | Jun 30, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | 340S G7                     | Notebook    | [6695a6a5ed](https://linux-hardware.org/?probe=6695a6a5ed) | Jun 28, 2022 |
| HP            | 84DE                        | All in one  | [edb267564a](https://linux-hardware.org/?probe=edb267564a) | Jun 27, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [052965926e](https://linux-hardware.org/?probe=052965926e) | Jun 26, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d306afd176](https://linux-hardware.org/?probe=d306afd176) | Jun 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f3742fcee5](https://linux-hardware.org/?probe=f3742fcee5) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | Notebook    | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [1860dff362](https://linux-hardware.org/?probe=1860dff362) | Jun 23, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [6e34269277](https://linux-hardware.org/?probe=6e34269277) | Jun 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d4896fb036](https://linux-hardware.org/?probe=d4896fb036) | Jun 21, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Alienware     | m17 R3                      | Notebook    | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f2b6d46056](https://linux-hardware.org/?probe=f2b6d46056) | Jun 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [df832fa379](https://linux-hardware.org/?probe=df832fa379) | Jun 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [afc1d78a8f](https://linux-hardware.org/?probe=afc1d78a8f) | Jun 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [14500170b0](https://linux-hardware.org/?probe=14500170b0) | Jun 16, 2022 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [e808d94139](https://linux-hardware.org/?probe=e808d94139) | Jun 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| Dell          | Precision 7550              | Notebook    | [bffea13d72](https://linux-hardware.org/?probe=bffea13d72) | Jun 14, 2022 |
| Monster       | HUMA H5 V2.2                | Notebook    | [062a54a327](https://linux-hardware.org/?probe=062a54a327) | Jun 13, 2022 |
| ASUSTek       | P5G41T-M                    | Desktop     | [0fd96bfcf3](https://linux-hardware.org/?probe=0fd96bfcf3) | Jun 12, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f58bb7a98a](https://linux-hardware.org/?probe=f58bb7a98a) | Jun 11, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 233       | 11.87%  |
| Ubuntu 18.04        | 170       | 8.66%   |
| Ubuntu 22.04        | 118       | 6.01%   |
| Arch Rolling        | 53        | 2.7%    |
| OpenMandriva 4.3    | 43        | 2.19%   |
| Debian 11           | 38        | 1.94%   |
| ArcoLinux Rolling   | 37        | 1.88%   |
| Fedora 37           | 35        | 1.78%   |
| Fedora 36           | 34        | 1.73%   |
| Fedora 38           | 33        | 1.68%   |
| Arch                | 33        | 1.68%   |
| Zorin 16            | 30        | 1.53%   |
| Manjaro             | 29        | 1.48%   |
| Fedora 33           | 26        | 1.32%   |
| Linux Mint 21.1     | 25        | 1.27%   |
| KDE neon 20.04      | 25        | 1.27%   |
| Pop!_OS 22.04       | 24        | 1.22%   |
| EndeavourOS Rolling | 23        | 1.17%   |
| Linux Mint 20.3     | 22        | 1.12%   |
| Fedora 35           | 22        | 1.12%   |
| OpenMandriva 23.01  | 21        | 1.07%   |
| Linux Mint 20.1     | 19        | 0.97%   |
| Ubuntu 21.10        | 18        | 0.92%   |
| Linux Mint 20       | 18        | 0.92%   |
| Linux Mint 21       | 17        | 0.87%   |
| Elementary 6.1      | 17        | 0.87%   |
| ROSA R10            | 16        | 0.82%   |
| Fedora 34           | 16        | 0.82%   |
| Linux Mint 20.2     | 14        | 0.71%   |
| Ubuntu 23.04        | 13        | 0.66%   |
| Ubuntu 22.10        | 13        | 0.66%   |
| Ubuntu 20.10        | 13        | 0.66%   |
| Zorin 15            | 12        | 0.61%   |
| Ubuntu 21.04        | 12        | 0.61%   |
| Pop!_OS 21.10       | 12        | 0.61%   |
| Pop!_OS 20.04       | 12        | 0.61%   |
| Debian 10           | 12        | 0.61%   |
| Ubuntu Unity 16.04  | 11        | 0.56%   |
| Ubuntu 19.10        | 11        | 0.56%   |
| Ubuntu 19.04        | 11        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 617       | 32.84%  |
| Fedora        | 159       | 8.46%   |
| Linux Mint    | 140       | 7.45%   |
| OpenMandriva  | 97        | 5.16%   |
| Arch          | 84        | 4.47%   |
| Debian        | 75        | 3.99%   |
| Manjaro       | 64        | 3.41%   |
| Pop!_OS       | 59        | 3.14%   |
| Pardus        | 54        | 2.87%   |
| Zorin         | 43        | 2.29%   |
| KDE neon      | 41        | 2.18%   |
| ArcoLinux     | 40        | 2.13%   |
| ROSA          | 33        | 1.76%   |
| Kubuntu       | 33        | 1.76%   |
| Elementary    | 30        | 1.6%    |
| Kali          | 29        | 1.54%   |
| Endless       | 27        | 1.44%   |
| EndeavourOS   | 24        | 1.28%   |
| Xubuntu       | 23        | 1.22%   |
| Lubuntu       | 17        | 0.9%    |
| openSUSE      | 16        | 0.85%   |
| Ubuntu Unity  | 13        | 0.69%   |
| Ubuntu MATE   | 13        | 0.69%   |
| Gentoo        | 11        | 0.59%   |
| Xero          | 10        | 0.53%   |
| PostmarketOS  | 8         | 0.43%   |
| Garuda Linux  | 8         | 0.43%   |
| Clear Linux   | 8         | 0.43%   |
| MX            | 7         | 0.37%   |
| LMDE          | 7         | 0.37%   |
| Artix         | 6         | 0.32%   |
| Parrot        | 5         | 0.27%   |
| Nobara        | 5         | 0.27%   |
| Deepin        | 5         | 0.27%   |
| CentOS        | 5         | 0.27%   |
| SteamOS       | 4         | 0.21%   |
| BlackPanther  | 4         | 0.21%   |
| Archman       | 4         | 0.21%   |
| Void Linux    | 3         | 0.16%   |
| Ubuntu Budgie | 3         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 41        | 1.93%   |
| 5.4.0-42-generic         | 25        | 1.18%   |
| 5.4.0-58-generic         | 22        | 1.04%   |
| 6.1.1-desktop-1omv2290   | 21        | 0.99%   |
| 5.15.0-56-generic        | 21        | 0.99%   |
| 5.15.0-58-generic        | 20        | 0.94%   |
| 5.0.0-37-generic         | 15        | 0.71%   |
| 5.4.0-48-generic         | 14        | 0.66%   |
| 5.4.0-26-generic         | 14        | 0.66%   |
| 5.15.0-52-generic        | 14        | 0.66%   |
| 4.18.0-15-generic        | 14        | 0.66%   |
| 5.3.0-40-generic         | 13        | 0.61%   |
| 5.15.0-48-generic        | 13        | 0.61%   |
| 5.10.0-21-amd64          | 13        | 0.61%   |
| 5.19.0-32-generic        | 12        | 0.57%   |
| 5.15.0-43-generic        | 12        | 0.57%   |
| 6.2.0-26-generic         | 11        | 0.52%   |
| 5.8.0-43-generic         | 11        | 0.52%   |
| 5.8.0-14-generic         | 11        | 0.52%   |
| 5.3.0-46-generic         | 11        | 0.52%   |
| 5.15.0-46-generic        | 11        | 0.52%   |
| 5.11.0-27-generic        | 11        | 0.52%   |
| 5.10.14-desktop-1omv4002 | 11        | 0.52%   |
| 5.4.0-37-generic         | 10        | 0.47%   |
| 5.4.0-29-generic         | 10        | 0.47%   |
| 5.15.0-27-generic        | 10        | 0.47%   |
| 5.13.0-39-generic        | 10        | 0.47%   |
| 5.13.0-30-generic        | 10        | 0.47%   |
| 6.2.6-desktop-1omv2390   | 9         | 0.42%   |
| 6.2.0-20-generic         | 9         | 0.42%   |
| 5.8.0-48-generic         | 9         | 0.42%   |
| 5.4.0-74-generic         | 9         | 0.42%   |
| 5.4.0-73-generic         | 9         | 0.42%   |
| 5.4.0-47-generic         | 9         | 0.42%   |
| 5.4.0-33-generic         | 9         | 0.42%   |
| 5.3.0-42-generic         | 9         | 0.42%   |
| 5.3.0-28-generic         | 9         | 0.42%   |
| 5.15.0-53-generic        | 9         | 0.42%   |
| 5.13.0-28-generic        | 9         | 0.42%   |
| 5.8.0-63-generic         | 8         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 283       | 13.9%   |
| 5.15.0  | 181       | 8.89%   |
| 5.8.0   | 94        | 4.62%   |
| 5.10.0  | 91        | 4.47%   |
| 4.15.0  | 86        | 4.22%   |
| 5.11.0  | 85        | 4.17%   |
| 5.13.0  | 76        | 3.73%   |
| 5.3.0   | 65        | 3.19%   |
| 5.19.0  | 59        | 2.9%    |
| 5.0.0   | 57        | 2.8%    |
| 4.18.0  | 46        | 2.26%   |
| 5.16.7  | 43        | 2.11%   |
| 6.2.0   | 34        | 1.67%   |
| 4.19.0  | 28        | 1.38%   |
| 6.1.1   | 25        | 1.23%   |
| 6.1.0   | 22        | 1.08%   |
| 6.2.6   | 19        | 0.93%   |
| 5.10.14 | 12        | 0.59%   |
| 6.4.12  | 11        | 0.54%   |
| 6.0.12  | 11        | 0.54%   |
| 5.17.5  | 11        | 0.54%   |
| 4.9.60  | 10        | 0.49%   |
| 6.4.11  | 9         | 0.44%   |
| 5.6.0   | 9         | 0.44%   |
| 6.3.8   | 8         | 0.39%   |
| 5.14.0  | 8         | 0.39%   |
| 6.4.6   | 7         | 0.34%   |
| 6.4.3   | 7         | 0.34%   |
| 6.2.9   | 7         | 0.34%   |
| 6.2.10  | 7         | 0.34%   |
| 5.17.1  | 7         | 0.34%   |
| 5.11.11 | 7         | 0.34%   |
| 6.3.0   | 5         | 0.25%   |
| 6.2.8   | 5         | 0.25%   |
| 6.2.12  | 5         | 0.25%   |
| 6.0.9   | 5         | 0.25%   |
| 6.0.8   | 5         | 0.25%   |
| 6.0.2   | 5         | 0.25%   |
| 6.0.0   | 5         | 0.25%   |
| 5.9.16  | 5         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 300       | 15.03%  |
| 5.15    | 242       | 12.12%  |
| 5.10    | 138       | 6.91%   |
| 5.11    | 116       | 5.81%   |
| 5.8     | 111       | 5.56%   |
| 6.1     | 94        | 4.71%   |
| 6.2     | 92        | 4.61%   |
| 5.13    | 88        | 4.41%   |
| 4.15    | 86        | 4.31%   |
| 5.19    | 81        | 4.06%   |
| 5.16    | 77        | 3.86%   |
| 5.3     | 76        | 3.81%   |
| 5.0     | 59        | 2.96%   |
| 6.4     | 51        | 2.56%   |
| 6.0     | 49        | 2.45%   |
| 4.18    | 49        | 2.45%   |
| 6.3     | 36        | 1.8%    |
| 5.18    | 33        | 1.65%   |
| 5.17    | 32        | 1.6%    |
| 4.19    | 30        | 1.5%    |
| 5.9     | 29        | 1.45%   |
| 4.9     | 23        | 1.15%   |
| 5.14    | 20        | 1%      |
| 5.6     | 17        | 0.85%   |
| 5.7     | 16        | 0.8%    |
| 5.12    | 16        | 0.8%    |
| 5.5     | 5         | 0.25%   |
| 4.4     | 5         | 0.25%   |
| 5.2     | 4         | 0.2%    |
| 5.1     | 4         | 0.2%    |
| 6.5     | 3         | 0.15%   |
| 4.14    | 3         | 0.15%   |
| 4.1     | 3         | 0.15%   |
| 4.13    | 2         | 0.1%    |
| 4.10    | 2         | 0.1%    |
| 6.0.5   | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.12    | 1         | 0.05%   |
| 3.4     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1715      | 96.19%  |
| i686    | 46        | 2.58%   |
| aarch64 | 13        | 0.73%   |
| armv7l  | 9         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 839       | 44.79%  |
| KDE5             | 294       | 15.7%   |
| Unknown          | 219       | 11.69%  |
| XFCE             | 188       | 10.04%  |
| X-Cinnamon       | 94        | 5.02%   |
| MATE             | 43        | 2.3%    |
| KDE              | 38        | 2.03%   |
| Pantheon         | 30        | 1.6%    |
| LXQt             | 18        | 0.96%   |
| Cinnamon         | 18        | 0.96%   |
| KDE4             | 17        | 0.91%   |
| Unity            | 13        | 0.69%   |
| i3               | 11        | 0.59%   |
| LXDE             | 10        | 0.53%   |
| sway             | 7         | 0.37%   |
| Hyprland         | 6         | 0.32%   |
| Deepin           | 6         | 0.32%   |
| Trinity          | 4         | 0.21%   |
| Budgie           | 4         | 0.21%   |
| DWM              | 3         | 0.16%   |
| openbox          | 2         | 0.11%   |
| bspwm            | 2         | 0.11%   |
| xmonad           | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| lightdm-xsession | 1         | 0.05%   |
| GNOME Flashback  | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| default          | 1         | 0.05%   |
| awesome          | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1383      | 75.08%  |
| Wayland | 335       | 18.19%  |
| Unknown | 91        | 4.94%   |
| Tty     | 33        | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 898       | 47.94%  |
| SDDM    | 260       | 13.88%  |
| GDM     | 236       | 12.6%   |
| GDM3    | 212       | 11.32%  |
| LightDM | 180       | 9.61%   |
| TDM     | 62        | 3.31%   |
| KDM     | 17        | 0.91%   |
| XDM     | 2         | 0.11%   |
| SLiM    | 2         | 0.11%   |
| Ly      | 2         | 0.11%   |
| LXDM    | 2         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 815       | 44.78%  |
| tr_TR       | 684       | 37.58%  |
| Unknown     | 196       | 10.77%  |
| en_GB       | 50        | 2.75%   |
| C           | 30        | 1.65%   |
| ru_RU       | 16        | 0.88%   |
| de_DE       | 5         | 0.27%   |
| POSIX       | 3         | 0.16%   |
| ar_EG       | 3         | 0.16%   |
| zh_CN       | 1         | 0.05%   |
| tr_TR.UTF8  | 1         | 0.05%   |
| tr_CY       | 1         | 0.05%   |
| ru_UA       | 1         | 0.05%   |
| nl_BE       | 1         | 0.05%   |
| fr_FR       | 1         | 0.05%   |
| fa_IR       | 1         | 0.05%   |
| es_ES       | 1         | 0.05%   |
| en_US.UTF8  | 1         | 0.05%   |
| en_US-UTF-8 | 1         | 0.05%   |
| en_NZ       | 1         | 0.05%   |
| en_IE       | 1         | 0.05%   |
| en_GB.UTF8  | 1         | 0.05%   |
| en_DK       | 1         | 0.05%   |
| en_CA       | 1         | 0.05%   |
| en_AU       | 1         | 0.05%   |
| en_150      | 1         | 0.05%   |
| de_AT       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 971       | 53.21%  |
| BIOS | 854       | 46.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1367      | 74.21%  |
| Btrfs   | 220       | 11.94%  |
| Overlay | 116       | 6.3%    |
| Unknown | 60        | 3.26%   |
| Tmpfs   | 30        | 1.63%   |
| Xfs     | 19        | 1.03%   |
| Ext2    | 14        | 0.76%   |
| Zfs     | 10        | 0.54%   |
| F2fs    | 2         | 0.11%   |
| Ext3    | 2         | 0.11%   |
| Aufs    | 2         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 954       | 52.02%  |
| GPT     | 706       | 38.5%   |
| MBR     | 174       | 9.49%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1552      | 85.56%  |
| Yes       | 262       | 14.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1207      | 65.88%  |
| Yes       | 625       | 34.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 315       | 17.68%  |
| Lenovo                      | 276       | 15.49%  |
| Hewlett-Packard             | 233       | 13.08%  |
| Dell                        | 135       | 7.58%   |
| MSI                         | 122       | 6.85%   |
| Acer                        | 106       | 5.95%   |
| Gigabyte Technology         | 95        | 5.33%   |
| Monster                     | 56        | 3.14%   |
| Toshiba                     | 52        | 2.92%   |
| Apple                       | 46        | 2.58%   |
| HUAWEI                      | 41        | 2.3%    |
| Samsung Electronics         | 32        | 1.8%    |
| Casper                      | 32        | 1.8%    |
| Sony                        | 30        | 1.68%   |
| Unknown                     | 24        | 1.35%   |
| Pegatron                    | 18        | 1.01%   |
| Packard Bell                | 17        | 0.95%   |
| Intel                       | 14        | 0.79%   |
| ASRock                      | 12        | 0.67%   |
| Clevo                       | 11        | 0.62%   |
| Hometech                    | 10        | 0.56%   |
| Google                      | 10        | 0.56%   |
| Foxconn                     | 8         | 0.45%   |
| ECS                         | 7         | 0.39%   |
| Fujitsu                     | 5         | 0.28%   |
| ARCELIK                     | 5         | 0.28%   |
| Vestel                      | 4         | 0.22%   |
| Raspberry Pi Foundation     | 4         | 0.22%   |
| Notebook                    | 4         | 0.22%   |
| Alienware                   | 4         | 0.22%   |
| Huanan                      | 3         | 0.17%   |
| Fujitsu Siemens             | 3         | 0.17%   |
| AMI                         | 3         | 0.17%   |
| Valve                       | 2         | 0.11%   |
| Quanta                      | 2         | 0.11%   |
| Nvidia                      | 2         | 0.11%   |
| Medion                      | 2         | 0.11%   |
| LG Electronics              | 2         | 0.11%   |
| Insyde                      | 2         | 0.11%   |
| I-Life Digital Technologies | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 33        | 1.85%   |
| HP Pavilion g6                       | 20        | 1.12%   |
| Casper NIRVANA NOTEBOOK              | 10        | 0.56%   |
| HP Pavilion dv6                      | 9         | 0.51%   |
| ASUS All Series                      | 9         | 0.51%   |
| HP Notebook                          | 8         | 0.45%   |
| HP Pavilion 15                       | 7         | 0.39%   |
| HP 15                                | 7         | 0.39%   |
| Gigabyte B450M S2H                   | 7         | 0.39%   |
| ASUS X550VX                          | 7         | 0.39%   |
| HUAWEI BOD-WXX9                      | 6         | 0.34%   |
| Acer Aspire 5750G                    | 6         | 0.34%   |
| MSI MS-7C02                          | 5         | 0.28%   |
| Lenovo V15 G2 ALC 82KD               | 5         | 0.28%   |
| HUAWEI NBLK-WAX9X                    | 5         | 0.28%   |
| HUAWEI KLVL-WXX9                     | 5         | 0.28%   |
| HUAWEI BOHK-WAX9X                    | 5         | 0.28%   |
| HP Pavilion Notebook                 | 5         | 0.28%   |
| HP 250 G3                            | 5         | 0.28%   |
| Gigabyte G31M-ES2L                   | 5         | 0.28%   |
| Gigabyte A320M-S2H                   | 5         | 0.28%   |
| Dell Inspiron 7577                   | 5         | 0.28%   |
| Dell Inspiron 3542                   | 5         | 0.28%   |
| Casper EXCALIBUR G770                | 5         | 0.28%   |
| ASUS X555UB                          | 5         | 0.28%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.28%   |
| ASUS N550JV                          | 5         | 0.28%   |
| Apple MacBookAir7,2                  | 5         | 0.28%   |
| Acer Nitro AN515-58                  | 5         | 0.28%   |
| Toshiba Satellite L655               | 4         | 0.22%   |
| Pegatron IPXSB-H61                   | 4         | 0.22%   |
| MSI MS-7A34                          | 4         | 0.22%   |
| MSI MS-7817                          | 4         | 0.22%   |
| MSI MS-7693                          | 4         | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV        | 4         | 0.22%   |
| Lenovo IdeaPad S145-15API 81UT       | 4         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 4         | 0.22%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 4         | 0.22%   |
| HP Pavilion Gaming Laptop 15-cx0xxx  | 4         | 0.22%   |
| HP G62                               | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 100       | 5.61%   |
| HP Pavilion           | 68        | 3.82%   |
| Lenovo IdeaPad        | 66        | 3.7%    |
| Dell Inspiron         | 59        | 3.31%   |
| Acer Aspire           | 58        | 3.25%   |
| Toshiba Satellite     | 48        | 2.69%   |
| Unknown               | 33        | 1.85%   |
| Dell Latitude         | 30        | 1.68%   |
| ASUS PRIME            | 30        | 1.68%   |
| Monster ABRA          | 29        | 1.63%   |
| HP Laptop             | 28        | 1.57%   |
| ASUS VivoBook         | 25        | 1.4%    |
| ASUS ROG              | 22        | 1.23%   |
| HP ProBook            | 21        | 1.18%   |
| HP EliteBook          | 20        | 1.12%   |
| ASUS TUF              | 20        | 1.12%   |
| Acer Nitro            | 17        | 0.95%   |
| Packard Bell EasyNote | 16        | 0.9%    |
| Monster TULPAR        | 16        | 0.9%    |
| Casper NIRVANA        | 16        | 0.9%    |
| Dell Vostro           | 15        | 0.84%   |
| Lenovo Yoga           | 14        | 0.79%   |
| HP 250                | 14        | 0.79%   |
| Lenovo Legion         | 13        | 0.73%   |
| Gigabyte B450M        | 11        | 0.62%   |
| Monster HUMA          | 10        | 0.56%   |
| Acer Swift            | 10        | 0.56%   |
| Dell Precision        | 9         | 0.51%   |
| Dell G3               | 9         | 0.51%   |
| ASUS All              | 9         | 0.51%   |
| Lenovo ThinkBook      | 8         | 0.45%   |
| HP Notebook           | 8         | 0.45%   |
| HP Compaq             | 8         | 0.45%   |
| HP ENVY               | 7         | 0.39%   |
| HP 15                 | 7         | 0.39%   |
| Dell XPS              | 7         | 0.39%   |
| Casper EXCALIBUR      | 7         | 0.39%   |
| ASUS X550VX           | 7         | 0.39%   |
| ASUS ASUS             | 7         | 0.39%   |
| Acer TravelMate       | 7         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 184       | 10.33%  |
| 2018    | 172       | 9.65%   |
| 2019    | 168       | 9.43%   |
| 2017    | 131       | 7.35%   |
| 2011    | 130       | 7.3%    |
| 2021    | 120       | 6.73%   |
| 2012    | 117       | 6.57%   |
| 2013    | 107       | 6%      |
| 2010    | 107       | 6%      |
| 2016    | 94        | 5.27%   |
| 2015    | 94        | 5.27%   |
| 2014    | 92        | 5.16%   |
| 2009    | 61        | 3.42%   |
| 2022    | 59        | 3.31%   |
| 2008    | 56        | 3.14%   |
| 2007    | 31        | 1.74%   |
| Unknown | 23        | 1.29%   |
| 2006    | 17        | 0.95%   |
| 2023    | 11        | 0.62%   |
| 2005    | 6         | 0.34%   |
| 2004    | 1         | 0.06%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1257      | 70.54%  |
| Desktop        | 430       | 24.13%  |
| Convertible    | 26        | 1.46%   |
| All in one     | 21        | 1.18%   |
| Tablet         | 14        | 0.79%   |
| Mini pc        | 14        | 0.79%   |
| System on chip | 12        | 0.67%   |
| Server         | 5         | 0.28%   |
| Phone          | 3         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1680      | 92.92%  |
| Enabled  | 128       | 7.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1779      | 99.83%  |
| Yes  | 3         | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 462       | 25.6%   |
| 16.01-24.0      | 351       | 19.45%  |
| 3.01-4.0        | 346       | 19.17%  |
| 8.01-16.0       | 331       | 18.34%  |
| 32.01-64.0      | 108       | 5.98%   |
| 1.01-2.0        | 104       | 5.76%   |
| 2.01-3.0        | 39        | 2.16%   |
| 64.01-256.0     | 27        | 1.5%    |
| 24.01-32.0      | 23        | 1.27%   |
| 0.51-1.0        | 13        | 0.72%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 649       | 32.65%  |
| 2.01-3.0   | 526       | 26.46%  |
| 3.01-4.0   | 311       | 15.64%  |
| 4.01-8.0   | 287       | 14.44%  |
| 0.51-1.0   | 111       | 5.58%   |
| 8.01-16.0  | 72        | 3.62%   |
| 0.01-0.5   | 22        | 1.11%   |
| 16.01-24.0 | 6         | 0.3%    |
| 24.01-32.0 | 2         | 0.1%    |
| 32.01-64.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1144      | 62.68%  |
| 2      | 505       | 27.67%  |
| 3      | 104       | 5.7%    |
| 4      | 36        | 1.97%   |
| 5      | 14        | 0.77%   |
| 0      | 13        | 0.71%   |
| 7      | 6         | 0.33%   |
| 6      | 3         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1203      | 66.91%  |
| Yes       | 595       | 33.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1528      | 85.46%  |
| No        | 260       | 14.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1468      | 82.15%  |
| No        | 319       | 17.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1210      | 67.15%  |
| No        | 592       | 32.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Turkey  | 1782      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Istanbul            | 678       | 35.8%   |
| Ankara              | 265       | 13.99%  |
| Izmir               | 174       | 9.19%   |
| Antalya             | 92        | 4.86%   |
| Bursa               | 87        | 4.59%   |
| Adana               | 33        | 1.74%   |
| Konya               | 28        | 1.48%   |
| Kayseri             | 25        | 1.32%   |
| İzmit              | 24        | 1.27%   |
| Kosekoy             | 22        | 1.16%   |
| Balıkesir          | 21        | 1.11%   |
| Gaziantep           | 19        | 1%      |
| Mersin              | 16        | 0.84%   |
| Denizli             | 16        | 0.84%   |
| Aydin               | 16        | 0.84%   |
| Samsun              | 15        | 0.79%   |
| Antakya             | 15        | 0.79%   |
| Mugla               | 14        | 0.74%   |
| Tekirdağ           | 11        | 0.58%   |
| Magnesia ad Sipylum | 11        | 0.58%   |
| Yalova              | 9         | 0.48%   |
| Trabzon             | 9         | 0.48%   |
| Kartal              | 9         | 0.48%   |
| Ordu                | 8         | 0.42%   |
| Kırklareli         | 8         | 0.42%   |
| Adapazarı          | 8         | 0.42%   |
| Eskişehir          | 7         | 0.37%   |
| Van                 | 6         | 0.32%   |
| Sisli               | 6         | 0.32%   |
| Malatya             | 6         | 0.32%   |
| Erzurum             | 6         | 0.32%   |
| Diyarbakır         | 6         | 0.32%   |
| Çanakkale          | 6         | 0.32%   |
| Batman              | 6         | 0.32%   |
| Zonguldak           | 5         | 0.26%   |
| Osmaniye            | 5         | 0.26%   |
| OEdemis             | 5         | 0.26%   |
| Cankaya             | 5         | 0.26%   |
| Ulus                | 4         | 0.21%   |
| Tarsus              | 4         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 374       | 530    | 14.88%  |
| Seagate                     | 341       | 430    | 13.56%  |
| WDC                         | 326       | 460    | 12.97%  |
| SanDisk                     | 226       | 269    | 8.99%   |
| Toshiba                     | 206       | 240    | 8.19%   |
| Kingston                    | 138       | 187    | 5.49%   |
| Unknown                     | 97        | 122    | 3.86%   |
| HGST                        | 63        | 71     | 2.51%   |
| SK hynix                    | 60        | 75     | 2.39%   |
| Hitachi                     | 60        | 66     | 2.39%   |
| Micron Technology           | 52        | 59     | 2.07%   |
| Intel                       | 46        | 59     | 1.83%   |
| Crucial                     | 42        | 52     | 1.67%   |
| China                       | 37        | 44     | 1.47%   |
| A-DATA Technology           | 37        | 42     | 1.47%   |
| Apple                       | 25        | 35     | 0.99%   |
| KIOXIA                      | 24        | 28     | 0.95%   |
| Corsair                     | 23        | 30     | 0.91%   |
| Phison                      | 19        | 19     | 0.76%   |
| KIOXIA-EXCERIA              | 18        | 21     | 0.72%   |
| Kingston Technology Company | 14        | 16     | 0.56%   |
| Fujitsu                     | 14        | 14     | 0.56%   |
| OCZ                         | 12        | 14     | 0.48%   |
| HS-SSD-C100                 | 12        | 12     | 0.48%   |
| Phison Electronics          | 11        | 11     | 0.44%   |
| Micron/Crucial Technology   | 11        | 12     | 0.44%   |
| JAMESDONKEY                 | 11        | 11     | 0.44%   |
| Silicon Motion              | 9         | 10     | 0.36%   |
| Netac                       | 9         | 10     | 0.36%   |
| Lexar                       | 8         | 14     | 0.32%   |
| UMIS                        | 7         | 9      | 0.28%   |
| Team                        | 7         | 7      | 0.28%   |
| LITEON                      | 7         | 8      | 0.28%   |
| JMicron Technology          | 7         | 7      | 0.28%   |
| Gigabyte Technology         | 7         | 13     | 0.28%   |
| Transcend                   | 6         | 6      | 0.24%   |
| Realtek Semiconductor       | 6         | 7      | 0.24%   |
| Pioneer                     | 6         | 20     | 0.24%   |
| KingSpec                    | 6         | 6      | 0.24%   |
| Unknown                     | 6         | 6      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 43        | 1.6%    |
| SanDisk SSD PLUS 240GB                                | 34        | 1.27%   |
| HGST HTS721010A9E630 1TB                              | 32        | 1.19%   |
| Unknown MMC Card  32GB                                | 26        | 0.97%   |
| Toshiba MQ04ABF100 1TB                                | 24        | 0.89%   |
| Toshiba MQ01ABD100 1TB                                | 22        | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 22        | 0.82%   |
| Toshiba MQ01ABF050 500GB                              | 19        | 0.71%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 18        | 0.67%   |
| Samsung SSD 860 EVO 250GB                             | 17        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                       | 16        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 15        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                        | 15        | 0.56%   |
| Samsung NVMe SSD Drive 512GB                          | 15        | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 14        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                       | 14        | 0.52%   |
| SanDisk SSD PLUS 120GB                                | 14        | 0.52%   |
| Kingston SV300S37A120G 120GB SSD                      | 13        | 0.48%   |
| Seagate ST9500325AS 500GB                             | 12        | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB                        | 12        | 0.45%   |
| SanDisk NVMe SSD Drive 256GB                          | 12        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 12        | 0.45%   |
| A-DATA SU650 120GB SSD                                | 12        | 0.45%   |
| Toshiba TR200 240GB SSD                               | 11        | 0.41%   |
| Kingston SA400S37240G 240GB SSD                       | 11        | 0.41%   |
| Intel NVMe SSD Drive 512GB                            | 11        | 0.41%   |
| Toshiba MQ01ABD075 752GB                              | 10        | 0.37%   |
| Seagate ST3500418AS 500GB                             | 10        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB                        | 10        | 0.37%   |
| Seagate Expansion 2TB                                 | 10        | 0.37%   |
| SanDisk SSD PLUS 480GB                                | 10        | 0.37%   |
| Samsung SSD 860 EVO 500GB                             | 10        | 0.37%   |
| Kingston SA400S37120G 120GB SSD                       | 10        | 0.37%   |
| HGST HTS541010A9E680 1TB                              | 10        | 0.37%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 9         | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 9         | 0.34%   |
| Unknown MMC Card  64GB                                | 9         | 0.34%   |
| Unknown MMC Card  128GB                               | 9         | 0.34%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 9         | 0.34%   |
| SanDisk NVMe SSD Drive 512GB                          | 9         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 335       | 419     | 34.11%  |
| WDC                 | 259       | 370     | 26.37%  |
| Toshiba             | 155       | 171     | 15.78%  |
| Samsung Electronics | 71        | 93      | 7.23%   |
| HGST                | 63        | 71      | 6.42%   |
| Hitachi             | 60        | 66      | 6.11%   |
| Fujitsu             | 14        | 14      | 1.43%   |
| Unknown             | 6         | 9       | 0.61%   |
| Apple               | 5         | 9       | 0.51%   |
| Maxtor              | 4         | 4       | 0.41%   |
| Pioneer             | 2         | 10      | 0.2%    |
| Intenso             | 2         | 3       | 0.2%    |
| SABRENT             | 1         | 1       | 0.1%    |
| Initio              | 1         | Unknown | 0.1%    |
| External            | 1         | 1       | 0.1%    |
| ExcelStor           | 1         | 1       | 0.1%    |
| China               | 1         | 1       | 0.1%    |
| 128MB               | 1         | 1       | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 152       | 184    | 19.22%  |
| Samsung Electronics | 139       | 187    | 17.57%  |
| Kingston            | 109       | 150    | 13.78%  |
| WDC                 | 46        | 55     | 5.82%   |
| China               | 33        | 37     | 4.17%   |
| Crucial             | 32        | 40     | 4.05%   |
| A-DATA Technology   | 27        | 30     | 3.41%   |
| Toshiba             | 25        | 27     | 3.16%   |
| Corsair             | 19        | 21     | 2.4%    |
| Micron Technology   | 18        | 22     | 2.28%   |
| KIOXIA-EXCERIA      | 14        | 17     | 1.77%   |
| OCZ                 | 12        | 14     | 1.52%   |
| Apple               | 12        | 14     | 1.52%   |
| SK hynix            | 11        | 14     | 1.39%   |
| JAMESDONKEY         | 10        | 10     | 1.26%   |
| Intel               | 10        | 16     | 1.26%   |
| Netac               | 9         | 10     | 1.14%   |
| Seagate             | 7         | 8      | 0.88%   |
| LITEON              | 7         | 8      | 0.88%   |
| Lexar               | 7         | 13     | 0.88%   |
| Team                | 6         | 6      | 0.76%   |
| KingSpec            | 6         | 6      | 0.76%   |
| Gigabyte Technology | 5         | 10     | 0.63%   |
| SPCC                | 4         | 4      | 0.51%   |
| Pioneer             | 4         | 10     | 0.51%   |
| LITEONIT            | 4         | 5      | 0.51%   |
| HS-SSD-C100         | 4         | 4      | 0.51%   |
| Hewlett-Packard     | 4         | 4      | 0.51%   |
| EZCOOL              | 4         | 5      | 0.51%   |
| Transcend           | 3         | 3      | 0.38%   |
| Patriot             | 3         | 4      | 0.38%   |
| KingFast            | 3         | 5      | 0.38%   |
| JMicron Technology  | 3         | 3      | 0.38%   |
| GOODRAM             | 3         | 6      | 0.38%   |
| 2.5"                | 3         | 3      | 0.38%   |
| TwinMOS             | 2         | 2      | 0.25%   |
| PNY                 | 2         | 2      | 0.25%   |
| KingDian            | 2         | 2      | 0.25%   |
| JD                  | 2         | 2      | 0.25%   |
| Indilinx            | 2         | 4      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 873       | 1244   | 37.71%  |
| SSD     | 716       | 997    | 30.93%  |
| NVMe    | 594       | 808    | 25.66%  |
| MMC     | 93        | 116    | 4.02%   |
| Unknown | 39        | 50     | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1306      | 2199   | 63.43%  |
| NVMe | 594       | 807    | 28.85%  |
| MMC  | 93        | 116    | 4.52%   |
| SAS  | 66        | 93     | 3.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1005      | 1483   | 64.42%  |
| 0.51-1.0   | 458       | 615    | 29.36%  |
| 1.01-2.0   | 67        | 100    | 4.29%   |
| 3.01-4.0   | 15        | 23     | 0.96%   |
| 2.01-3.0   | 9         | 13     | 0.58%   |
| 4.01-10.0  | 6         | 7      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 561       | 29.33%  |
| 251-500        | 431       | 22.53%  |
| 501-1000       | 251       | 13.12%  |
| 51-100         | 155       | 8.1%    |
| 1-20           | 146       | 7.63%   |
| 1001-2000      | 141       | 7.37%   |
| 21-50          | 113       | 5.91%   |
| 2001-3000      | 45        | 2.35%   |
| More than 3000 | 43        | 2.25%   |
| Unknown        | 27        | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 790       | 40.06%  |
| 21-50          | 387       | 19.62%  |
| 101-250        | 238       | 12.07%  |
| 51-100         | 235       | 11.92%  |
| 251-500        | 137       | 6.95%   |
| 501-1000       | 97        | 4.92%   |
| 1001-2000      | 34        | 1.72%   |
| Unknown        | 27        | 1.37%   |
| More than 3000 | 14        | 0.71%   |
| 2001-3000      | 13        | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 7         | 7      | 3.61%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 2.58%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 6      | 2.06%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 2.06%   |
| Kingston SV300S37A120G 120GB SSD      | 4         | 5      | 2.06%   |
| HGST HTS721010A9E630 1TB              | 4         | 5      | 2.06%   |
| Toshiba MQ01ABF050 500GB              | 3         | 4      | 1.55%   |
| Toshiba MQ01ABD050 500GB              | 3         | 4      | 1.55%   |
| SanDisk SSD PLUS 240GB                | 3         | 3      | 1.55%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 1.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 3      | 1.03%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 2         | 2      | 1.03%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 1.03%   |
| Toshiba MQ02ABD100H 1TB               | 2         | 3      | 1.03%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 1.03%   |
| Toshiba MK3252GSX 320GB               | 2         | 2      | 1.03%   |
| Toshiba DT01ACA050 500GB              | 2         | 2      | 1.03%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 1.03%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.03%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.03%   |
| Seagate ST3500630AS 500GB             | 2         | 2      | 1.03%   |
| Seagate ST1000LM014-SSHD-8GB          | 2         | 2      | 1.03%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 3      | 1.03%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 3      | 1.03%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 4      | 1.03%   |
| Samsung Electronics HD161HJ 160GB     | 2         | 2      | 1.03%   |
| Kingston SVP200S37A120G 120GB SSD     | 2         | 2      | 1.03%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 1.03%   |
| JMicron Technology Tech 250GB         | 2         | 2      | 1.03%   |
| Indilinx IND-S325S120G 120GB SSD      | 2         | 4      | 1.03%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 1.03%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 2      | 1.03%   |
| Fujitsu MHY2120BH 120GB               | 2         | 2      | 1.03%   |
| 2.5" SATA SSD 3TG6-P 2TB              | 2         | 2      | 1.03%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.52%   |
| WDC WD7500BPVT-55HXZT3 752GB          | 1         | 1      | 0.52%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.52%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB           | 1         | 2      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 54     | 24.08%  |
| Toshiba             | 27        | 30     | 14.14%  |
| WDC                 | 23        | 28     | 12.04%  |
| Hitachi             | 16        | 16     | 8.38%   |
| Samsung Electronics | 14        | 18     | 7.33%   |
| HGST                | 11        | 12     | 5.76%   |
| SanDisk             | 10        | 11     | 5.24%   |
| Kingston            | 10        | 11     | 5.24%   |
| A-DATA Technology   | 8         | 8      | 4.19%   |
| Fujitsu             | 3         | 3      | 1.57%   |
| China               | 3         | 3      | 1.57%   |
| SK hynix            | 2         | 3      | 1.05%   |
| Maxtor              | 2         | 2      | 1.05%   |
| JMicron Technology  | 2         | 2      | 1.05%   |
| Indilinx            | 2         | 4      | 1.05%   |
| Crucial             | 2         | 2      | 1.05%   |
| 2.5"                | 2         | 2      | 1.05%   |
| SSD-S400            | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 2      | 0.52%   |
| LITEONIT            | 1         | 2      | 0.52%   |
| LITEON              | 1         | 1      | 0.52%   |
| JD                  | 1         | 1      | 0.52%   |
| Intenso             | 1         | 1      | 0.52%   |
| Intel               | 1         | 1      | 0.52%   |
| Apple               | 1         | 2      | 0.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 46        | 54     | 33.82%  |
| Toshiba             | 27        | 30     | 19.85%  |
| WDC                 | 20        | 24     | 14.71%  |
| Hitachi             | 16        | 16     | 11.76%  |
| HGST                | 11        | 12     | 8.09%   |
| Samsung Electronics | 10        | 12     | 7.35%   |
| Fujitsu             | 3         | 3      | 2.21%   |
| Maxtor              | 2         | 2      | 1.47%   |
| Apple               | 1         | 2      | 0.74%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 127       | 155    | 69.78%  |
| SSD     | 49        | 59     | 26.92%  |
| NVMe    | 4         | 4      | 2.2%    |
| Unknown | 2         | 2      | 1.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 25%     |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 25%     |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1109      | 1885   | 57.02%  |
| Works    | 654       | 1106   | 33.62%  |
| Malfunc  | 178       | 220    | 9.15%   |
| Failed   | 4         | 4      | 0.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1200      | 55.15%  |
| AMD                              | 286       | 13.14%  |
| Samsung Electronics              | 198       | 9.1%    |
| SanDisk                          | 91        | 4.18%   |
| SK hynix                         | 47        | 2.16%   |
| Kingston Technology Company      | 42        | 1.93%   |
| Phison Electronics               | 37        | 1.7%    |
| Micron Technology                | 33        | 1.52%   |
| KIOXIA                           | 32        | 1.47%   |
| Nvidia                           | 23        | 1.06%   |
| Toshiba America Info Systems     | 22        | 1.01%   |
| Micron/Crucial Technology        | 20        | 0.92%   |
| Marvell Technology Group         | 18        | 0.83%   |
| JMicron Technology               | 18        | 0.83%   |
| Silicon Motion                   | 15        | 0.69%   |
| ADATA Technology                 | 15        | 0.69%   |
| ASMedia Technology               | 14        | 0.64%   |
| Union Memory (Shenzhen)          | 13        | 0.6%    |
| Silicon Integrated Systems [SiS] | 12        | 0.55%   |
| Realtek Semiconductor            | 10        | 0.46%   |
| Apple                            | 7         | 0.32%   |
| Yangtze Memory Technologies      | 4         | 0.18%   |
| VIA Technologies                 | 4         | 0.18%   |
| Lite-On Technology               | 3         | 0.14%   |
| Innodisk                         | 3         | 0.14%   |
| Transcend                        | 2         | 0.09%   |
| Solid State Storage Technology   | 2         | 0.09%   |
| LSI Logic / Symbios Logic        | 2         | 0.09%   |
| ULi Electronics                  | 1         | 0.05%   |
| Promise Technology               | 1         | 0.05%   |
| OCZ Technology Group             | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 203       | 8.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 110       | 4.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 101       | 4.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 86        | 3.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 79        | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 63        | 2.55%   |
| Samsung NVMe SSD Controller 980                                                         | 55        | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 51        | 2.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 51        | 2.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 51        | 2.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 50        | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 46        | 1.86%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 45        | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 42        | 1.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 39        | 1.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 37        | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 36        | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 36        | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 35        | 1.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 31        | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 29        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 28        | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 25        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 24        | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 22        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 22        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 22        | 0.89%   |
| Intel SSD 660P Series                                                                   | 20        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 19        | 0.77%   |
| Phison PS5013 E13 NVMe Controller                                                       | 18        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 17        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 17        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 17        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 16        | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 15        | 0.61%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 15        | 0.61%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 15        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1291      | 58.28%  |
| NVMe | 596       | 26.91%  |
| IDE  | 220       | 9.93%   |
| RAID | 106       | 4.79%   |
| SCSI | 2         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1360      | 76.32%  |
| AMD          | 398       | 22.33%  |
| ARM          | 22        | 1.23%   |
| CentaurHauls | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 1.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 28        | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 22        | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 20        | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 0.95%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 0.9%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 16        | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 14        | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 0.78%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 0.73%   |
| ARM Processor                                 | 13        | 0.73%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 0.73%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 12        | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.62%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 11        | 0.62%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 11        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.62%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 11        | 0.62%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 10        | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 10        | 0.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 0.56%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 10        | 0.56%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 10        | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.5%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 9         | 0.5%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 432       | 24.22%  |
| Intel Core i7           | 347       | 19.45%  |
| Other                   | 142       | 7.96%   |
| AMD Ryzen 5             | 134       | 7.51%   |
| Intel Core i3           | 124       | 6.95%   |
| AMD Ryzen 7             | 86        | 4.82%   |
| Intel Celeron           | 72        | 4.04%   |
| Intel Core 2 Duo        | 69        | 3.87%   |
| Intel Atom              | 40        | 2.24%   |
| Intel Pentium           | 39        | 2.19%   |
| AMD Ryzen 3             | 26        | 1.46%   |
| Intel Xeon              | 22        | 1.23%   |
| Intel Pentium Dual-Core | 22        | 1.23%   |
| Intel Core 2 Quad       | 20        | 1.12%   |
| AMD FX                  | 20        | 1.12%   |
| Intel Pentium Dual      | 16        | 0.9%    |
| AMD A8                  | 16        | 0.9%    |
| Intel Core 2            | 14        | 0.78%   |
| AMD A10                 | 13        | 0.73%   |
| Intel Core i9           | 7         | 0.39%   |
| AMD Ryzen 9             | 7         | 0.39%   |
| AMD Phenom II X4        | 7         | 0.39%   |
| AMD A6                  | 7         | 0.39%   |
| AMD A4                  | 7         | 0.39%   |
| Intel Pentium Silver    | 6         | 0.34%   |
| AMD Ryzen 7 PRO         | 6         | 0.34%   |
| AMD Ryzen 5 PRO         | 6         | 0.34%   |
| AMD Athlon 64 X2        | 5         | 0.28%   |
| Intel Pentium 4         | 4         | 0.22%   |
| Intel Genuine           | 4         | 0.22%   |
| AMD Athlon II X3        | 4         | 0.22%   |
| AMD Athlon II X2        | 4         | 0.22%   |
| AMD Athlon              | 4         | 0.22%   |
| AMD A12                 | 4         | 0.22%   |
| AMD Phenom II X6        | 3         | 0.17%   |
| AMD Phenom              | 3         | 0.17%   |
| AMD E2                  | 3         | 0.17%   |
| AMD C-60                | 3         | 0.17%   |
| AMD Athlon II X4        | 3         | 0.17%   |
| Intel Xeon Silver       | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 752       | 42.15%  |
| 4      | 628       | 35.2%   |
| 6      | 204       | 11.43%  |
| 8      | 109       | 6.11%   |
| 1      | 33        | 1.85%   |
| 14     | 15        | 0.84%   |
| 12     | 13        | 0.73%   |
| 3      | 13        | 0.73%   |
| 10     | 12        | 0.67%   |
| 24     | 2         | 0.11%   |
| 64     | 1         | 0.06%   |
| 20     | 1         | 0.06%   |
| 16     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1776      | 99.66%  |
| 2      | 6         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1261      | 70.76%  |
| 1      | 519       | 29.12%  |
| 8      | 2         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1729      | 96.81%  |
| Unknown        | 41        | 2.3%    |
| 32-bit         | 15        | 0.84%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 484       | 26.2%   |
| 0x206a7    | 96        | 5.2%    |
| 0x306a9    | 94        | 5.09%   |
| 0x306c3    | 57        | 3.09%   |
| 0x1067a    | 52        | 2.82%   |
| 0x906e9    | 51        | 2.76%   |
| 0x40651    | 42        | 2.27%   |
| 0x806ea    | 41        | 2.22%   |
| 0x906ea    | 40        | 2.17%   |
| 0x806e9    | 36        | 1.95%   |
| 0x806ec    | 35        | 1.89%   |
| 0x306d4    | 34        | 1.84%   |
| 0xa0652    | 33        | 1.79%   |
| 0x806c1    | 33        | 1.79%   |
| 0x406e3    | 33        | 1.79%   |
| 0x506e3    | 32        | 1.73%   |
| 0x20655    | 31        | 1.68%   |
| 0x6fd      | 25        | 1.35%   |
| 0x08108109 | 25        | 1.35%   |
| 0x30678    | 21        | 1.14%   |
| 0x08108102 | 21        | 1.14%   |
| 0x406c4    | 20        | 1.08%   |
| 0x08608103 | 20        | 1.08%   |
| 0x08600106 | 20        | 1.08%   |
| 0x706e5    | 19        | 1.03%   |
| 0x20652    | 18        | 0.97%   |
| 0x10676    | 17        | 0.92%   |
| 0x0a50000c | 17        | 0.92%   |
| 0x506c9    | 14        | 0.76%   |
| 0x08701021 | 14        | 0.76%   |
| 0x06000852 | 13        | 0.7%    |
| 0x0800820d | 12        | 0.65%   |
| 0x906a3    | 11        | 0.6%    |
| 0x0a50000d | 11        | 0.6%    |
| 0x08001138 | 10        | 0.54%   |
| 0x06006705 | 10        | 0.54%   |
| 0x010000c8 | 10        | 0.54%   |
| 0x6f6      | 9         | 0.49%   |
| 0x406c3    | 9         | 0.49%   |
| 0x08600104 | 9         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 292       | 16.37%  |
| SandyBridge      | 131       | 7.34%   |
| Haswell          | 129       | 7.23%   |
| IvyBridge        | 124       | 6.95%   |
| Penryn           | 91        | 5.1%    |
| Skylake          | 88        | 4.93%   |
| Unknown          | 88        | 4.93%   |
| Zen 2            | 76        | 4.26%   |
| Zen+             | 74        | 4.15%   |
| Westmere         | 66        | 3.7%    |
| Silvermont       | 61        | 3.42%   |
| CometLake        | 60        | 3.36%   |
| Core             | 58        | 3.25%   |
| TigerLake        | 53        | 2.97%   |
| Broadwell        | 46        | 2.58%   |
| Zen 3            | 43        | 2.41%   |
| IceLake          | 40        | 2.24%   |
| Zen              | 37        | 2.07%   |
| Piledriver       | 30        | 1.68%   |
| K10              | 28        | 1.57%   |
| Alderlake Hybrid | 25        | 1.4%    |
| Excavator        | 22        | 1.23%   |
| Goldmont plus    | 20        | 1.12%   |
| Goldmont         | 17        | 0.95%   |
| Puma             | 15        | 0.84%   |
| Bonnell          | 14        | 0.78%   |
| Nehalem          | 13        | 0.73%   |
| Bobcat           | 9         | 0.5%    |
| K8 Hammer        | 8         | 0.45%   |
| P6               | 6         | 0.34%   |
| K10 Llano        | 6         | 0.34%   |
| NetBurst         | 5         | 0.28%   |
| Steamroller      | 3         | 0.17%   |
| Bulldozer        | 3         | 0.17%   |
| Tremont          | 1         | 0.06%   |
| K6               | 1         | 0.06%   |
| Jaguar           | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1072      | 45.68%  |
| Nvidia                           | 683       | 29.1%   |
| AMD                              | 576       | 24.54%  |
| Silicon Integrated Systems [SiS] | 10        | 0.43%   |
| VIA Technologies                 | 3         | 0.13%   |
| Matrox Electronics Systems       | 2         | 0.09%   |
| ASPEED Technology                | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 100       | 4.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 3.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 55        | 2.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 2.21%   |
| Intel HD Graphics 620                                                                    | 49        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 49        | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 48        | 1.96%   |
| Intel UHD Graphics 620                                                                   | 46        | 1.88%   |
| AMD Renoir                                                                               | 46        | 1.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 42        | 1.72%   |
| Intel HD Graphics 630                                                                    | 41        | 1.68%   |
| Intel HD Graphics 5500                                                                   | 37        | 1.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 37        | 1.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 35        | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 1.35%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 33        | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.31%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 1.19%   |
| AMD Lucienne                                                                             | 29        | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 28        | 1.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 1.02%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 0.98%   |
| Intel HD Graphics 530                                                                    | 24        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 22        | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 0.9%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 0.82%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 20        | 0.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 20        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 19        | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                             | 19        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 18        | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.74%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 17        | 0.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 15        | 0.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 522       | 29.1%   |
| Intel + Nvidia  | 411       | 22.91%  |
| 1 x AMD         | 355       | 19.79%  |
| 1 x Nvidia      | 236       | 13.15%  |
| Intel + AMD     | 125       | 6.97%   |
| 2 x AMD         | 61        | 3.4%    |
| AMD + Nvidia    | 36        | 2.01%   |
| Other           | 26        | 1.45%   |
| 1 x SiS         | 10        | 0.56%   |
| 2 x Intel       | 3         | 0.17%   |
| 1 x VIA         | 3         | 0.17%   |
| 2 x Nvidia      | 2         | 0.11%   |
| 1 x Matrox      | 2         | 0.11%   |
| Intel + 2 x AMD | 1         | 0.06%   |
| 1 x ASPEED      | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1385      | 76.43%  |
| Proprietary | 350       | 19.32%  |
| Unknown     | 77        | 4.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 949       | 51.49%  |
| 1.01-2.0   | 272       | 14.76%  |
| 0.51-1.0   | 180       | 9.77%   |
| 0.01-0.5   | 180       | 9.77%   |
| 3.01-4.0   | 154       | 8.36%   |
| 5.01-6.0   | 46        | 2.5%    |
| 7.01-8.0   | 32        | 1.74%   |
| 8.01-16.0  | 18        | 0.98%   |
| 2.01-3.0   | 10        | 0.54%   |
| 4.01-5.0   | 1         | 0.05%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 276       | 14.92%  |
| LG Display              | 226       | 12.22%  |
| BOE                     | 218       | 11.78%  |
| Samsung Electronics     | 206       | 11.14%  |
| Chimei Innolux          | 189       | 10.22%  |
| Goldstar                | 64        | 3.46%   |
| Philips                 | 61        | 3.3%    |
| Dell                    | 45        | 2.43%   |
| Apple                   | 42        | 2.27%   |
| Ancor Communications    | 39        | 2.11%   |
| AOC                     | 36        | 1.95%   |
| Lenovo                  | 34        | 1.84%   |
| Hewlett-Packard         | 33        | 1.78%   |
| Chi Mei Optoelectronics | 33        | 1.78%   |
| Acer                    | 33        | 1.78%   |
| ViewSonic               | 30        | 1.62%   |
| PANDA                   | 30        | 1.62%   |
| ASUSTek Computer        | 25        | 1.35%   |
| Sharp                   | 21        | 1.14%   |
| BenQ                    | 19        | 1.03%   |
| LG Philips              | 11        | 0.59%   |
| MSI                     | 10        | 0.54%   |
| InfoVision              | 9         | 0.49%   |
| CPT                     | 9         | 0.49%   |
| Vestel Elektronik       | 7         | 0.38%   |
| Unknown                 | 7         | 0.38%   |
| Sony                    | 7         | 0.38%   |
| LG Electronics          | 7         | 0.38%   |
| SAC                     | 6         | 0.32%   |
| LGD                     | 6         | 0.32%   |
| AGO                     | 6         | 0.32%   |
| SANYO                   | 5         | 0.27%   |
| KTC                     | 5         | 0.27%   |
| HKC                     | 5         | 0.27%   |
| Unknown                 | 5         | 0.27%   |
| VIE                     | 4         | 0.22%   |
| Plain Tree Systems      | 4         | 0.22%   |
| Mi                      | 4         | 0.22%   |
| HannStar                | 4         | 0.22%   |
| CSO                     | 4         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 23        | 1.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 19        | 1.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 18        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 17        | 0.9%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 14        | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.74%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 14        | 0.74%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.64%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 11        | 0.58%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 11        | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.48%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.42%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 8         | 0.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 8         | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 7         | 0.37%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 7         | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 7         | 0.37%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 7         | 0.37%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.37%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                            | 6         | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 6         | 0.32%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 6         | 0.32%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 6         | 0.32%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 6         | 0.32%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 0.32%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.32%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 6         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 822       | 46.63%  |
| 1366x768 (WXGA)    | 483       | 27.4%   |
| 3840x2160 (4K)     | 57        | 3.23%   |
| 2560x1440 (QHD)    | 49        | 2.78%   |
| 1440x900 (WXGA+)   | 43        | 2.44%   |
| 1280x800 (WXGA)    | 41        | 2.33%   |
| 1600x900 (HD+)     | 37        | 2.1%    |
| 1280x1024 (SXGA)   | 31        | 1.76%   |
| 1680x1050 (WSXGA+) | 25        | 1.42%   |
| Unknown            | 24        | 1.36%   |
| 1920x1200 (WUXGA)  | 23        | 1.3%    |
| 2560x1600          | 17        | 0.96%   |
| 2160x1440          | 14        | 0.79%   |
| 1360x768           | 11        | 0.62%   |
| 2560x1080          | 10        | 0.57%   |
| 1024x600           | 9         | 0.51%   |
| 3840x1080          | 7         | 0.4%    |
| 3440x1440          | 7         | 0.4%    |
| 2880x1800          | 7         | 0.4%    |
| 3200x1800 (QHD+)   | 5         | 0.28%   |
| 1920x540           | 4         | 0.23%   |
| 1024x768 (XGA)     | 4         | 0.23%   |
| 1680x945           | 3         | 0.17%   |
| 800x1280           | 2         | 0.11%   |
| 4480x1440          | 2         | 0.11%   |
| 3840x2400          | 2         | 0.11%   |
| 3000x2000          | 2         | 0.11%   |
| 2520x1680          | 2         | 0.11%   |
| 800x600            | 1         | 0.06%   |
| 7920x1440          | 1         | 0.06%   |
| 6000x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 3840x2560          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3750x1280          | 1         | 0.06%   |
| 3360x1050          | 1         | 0.06%   |
| 3240x2160          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 3046x1050          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 772       | 41.77%  |
| 13      | 170       | 9.2%    |
| 23      | 112       | 6.06%   |
| 21      | 98        | 5.3%    |
| 14      | 94        | 5.09%   |
| 27      | 80        | 4.33%   |
| 17      | 76        | 4.11%   |
| Unknown | 75        | 4.06%   |
| 24      | 72        | 3.9%    |
| 18      | 48        | 2.6%    |
| 19      | 33        | 1.79%   |
| 12      | 30        | 1.62%   |
| 11      | 25        | 1.35%   |
| 16      | 22        | 1.19%   |
| 31      | 17        | 0.92%   |
| 20      | 17        | 0.92%   |
| 34      | 16        | 0.87%   |
| 10      | 15        | 0.81%   |
| 22      | 13        | 0.7%    |
| 84      | 9         | 0.49%   |
| 72      | 8         | 0.43%   |
| 54      | 5         | 0.27%   |
| 26      | 5         | 0.27%   |
| 40      | 4         | 0.22%   |
| 32      | 4         | 0.22%   |
| 57      | 3         | 0.16%   |
| 46      | 3         | 0.16%   |
| 33      | 3         | 0.16%   |
| 29      | 3         | 0.16%   |
| 28      | 3         | 0.16%   |
| 60      | 2         | 0.11%   |
| 43      | 2         | 0.11%   |
| 36      | 2         | 0.11%   |
| 7       | 2         | 0.11%   |
| 65      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |
| 25      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 957       | 52.24%  |
| 501-600     | 244       | 13.32%  |
| 401-500     | 210       | 11.46%  |
| 201-300     | 162       | 8.84%   |
| 351-400     | 86        | 4.69%   |
| Unknown     | 75        | 4.09%   |
| 601-700     | 31        | 1.69%   |
| 701-800     | 25        | 1.36%   |
| 1501-2000   | 17        | 0.93%   |
| 1001-1500   | 17        | 0.93%   |
| 801-900     | 4         | 0.22%   |
| 901-1000    | 2         | 0.11%   |
| 1-100       | 2         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1360      | 81.15%  |
| 16/10   | 158       | 9.43%   |
| Unknown | 66        | 3.94%   |
| 3/2     | 29        | 1.73%   |
| 5/4     | 24        | 1.43%   |
| 4/3     | 20        | 1.19%   |
| 21/9    | 16        | 0.95%   |
| 0.67    | 2         | 0.12%   |
| 6/5     | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 774       | 42.16%  |
| 201-250        | 251       | 13.67%  |
| 81-90          | 198       | 10.78%  |
| 301-350        | 82        | 4.47%   |
| 151-200        | 78        | 4.25%   |
| Unknown        | 75        | 4.08%   |
| 71-80          | 72        | 3.92%   |
| 141-150        | 57        | 3.1%    |
| 121-130        | 52        | 2.83%   |
| 351-500        | 46        | 2.51%   |
| More than 1000 | 31        | 1.69%   |
| 51-60          | 25        | 1.36%   |
| 61-70          | 23        | 1.25%   |
| 251-300        | 18        | 0.98%   |
| 111-120        | 17        | 0.93%   |
| 41-50          | 15        | 0.82%   |
| 501-1000       | 11        | 0.6%    |
| 91-100         | 5         | 0.27%   |
| 131-140        | 4         | 0.22%   |
| 1-40           | 2         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 589       | 32.47%  |
| 101-120       | 527       | 29.05%  |
| 51-100        | 469       | 25.85%  |
| 161-240       | 105       | 5.79%   |
| Unknown       | 75        | 4.13%   |
| 1-50          | 28        | 1.54%   |
| More than 240 | 21        | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1502      | 82.44%  |
| 2     | 229       | 12.57%  |
| 0     | 82        | 4.5%    |
| 3     | 9         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1149      | 41.18%  |
| Intel                                  | 697       | 24.98%  |
| Qualcomm Atheros                       | 371       | 13.3%   |
| Broadcom                               | 169       | 6.06%   |
| Ralink Technology                      | 61        | 2.19%   |
| Broadcom Limited                       | 35        | 1.25%   |
| MediaTek                               | 33        | 1.18%   |
| Ralink                                 | 32        | 1.15%   |
| Marvell Technology Group               | 31        | 1.11%   |
| TP-Link                                | 22        | 0.79%   |
| ASUSTek Computer                       | 21        | 0.75%   |
| Qualcomm Atheros Communications        | 19        | 0.68%   |
| Nvidia                                 | 19        | 0.68%   |
| Samsung Electronics                    | 17        | 0.61%   |
| Xiaomi                                 | 13        | 0.47%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.47%   |
| ASIX Electronics                       | 7         | 0.25%   |
| Ericsson Business Mobile Networks      | 6         | 0.22%   |
| ZyXEL Communications                   | 5         | 0.18%   |
| JMicron Technology                     | 5         | 0.18%   |
| Huawei Technologies                    | 5         | 0.18%   |
| Apple                                  | 4         | 0.14%   |
| Microchip Technology                   | 3         | 0.11%   |
| ICS Advent                             | 3         | 0.11%   |
| Dell                                   | 3         | 0.11%   |
| Aquantia                               | 3         | 0.11%   |
| Tenda                                  | 2         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.07%   |
| Sierra Wireless                        | 2         | 0.07%   |
| Qualcomm                               | 2         | 0.07%   |
| OPPO Electronics                       | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| Lenovo                                 | 2         | 0.07%   |
| Attansic Technology                    | 2         | 0.07%   |
| Accton Technology                      | 2         | 0.07%   |
| Wilocity                               | 1         | 0.04%   |
| VIA Technologies                       | 1         | 0.04%   |
| ULi Electronics                        | 1         | 0.04%   |
| U-Blox                                 | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 789       | 24.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 177       | 5.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 67        | 2.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 65        | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 59        | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 52        | 1.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 51        | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 45        | 1.41%   |
| Intel Wi-Fi 6 AX201                                               | 45        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 45        | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 44        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 40        | 1.26%   |
| Intel Wireless 7265                                               | 39        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 35        | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34        | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 31        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 31        | 0.97%   |
| Intel Wireless 8265 / 8275                                        | 30        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 29        | 0.91%   |
| Ralink MT7601U Wireless Adapter                                   | 28        | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 25        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 24        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 22        | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 21        | 0.66%   |
| Intel Wireless 3165                                               | 21        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.63%   |
| Intel Wireless 7260                                               | 20        | 0.63%   |
| Intel Wireless 3160                                               | 19        | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.56%   |
| Intel Wireless 8260                                               | 17        | 0.53%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 15        | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 14        | 0.44%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 14        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 604       | 38.82%  |
| Realtek Semiconductor             | 299       | 19.22%  |
| Qualcomm Atheros                  | 286       | 18.38%  |
| Broadcom                          | 130       | 8.35%   |
| Ralink Technology                 | 61        | 3.92%   |
| Ralink                            | 32        | 2.06%   |
| MediaTek                          | 32        | 2.06%   |
| Broadcom Limited                  | 24        | 1.54%   |
| ASUSTek Computer                  | 21        | 1.35%   |
| TP-Link                           | 20        | 1.29%   |
| Qualcomm Atheros Communications   | 19        | 1.22%   |
| ZyXEL Communications              | 5         | 0.32%   |
| Ericsson Business Mobile Networks | 4         | 0.26%   |
| Marvell Technology Group          | 3         | 0.19%   |
| Tenda                             | 2         | 0.13%   |
| Sierra Wireless                   | 2         | 0.13%   |
| Dell                              | 2         | 0.13%   |
| Accton Technology                 | 2         | 0.13%   |
| Wilocity                          | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |
| Linksys                           | 1         | 0.06%   |
| IMC Networks                      | 1         | 0.06%   |
| Fibocom                           | 1         | 0.06%   |
| Edimax Technology                 | 1         | 0.06%   |
| Belkin Components                 | 1         | 0.06%   |
| AirTies Wireless Networks         | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 67        | 4.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 65        | 4.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 59        | 3.78%   |
| Intel Wi-Fi 6 AX200                                            | 52        | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 51        | 3.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 2.88%   |
| Intel Wi-Fi 6 AX201                                            | 45        | 2.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 45        | 2.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 44        | 2.82%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 40        | 2.56%   |
| Intel Wireless 7265                                            | 39        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34        | 2.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 31        | 1.99%   |
| Intel Wireless 8265 / 8275                                     | 30        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 29        | 1.86%   |
| Ralink MT7601U Wireless Adapter                                | 28        | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25        | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 25        | 1.6%    |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 1.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 1.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 21        | 1.35%   |
| Intel Wireless 3165                                            | 21        | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.28%   |
| Intel Wireless 7260                                            | 20        | 1.28%   |
| Intel Wireless 3160                                            | 19        | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.15%   |
| Intel Wireless 8260                                            | 17        | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 15        | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 14        | 0.9%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 14        | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                | 14        | 0.9%    |
| Intel Wireless-AC 9260                                         | 14        | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 14        | 0.9%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12        | 0.77%   |
| Intel WiFi Link 5100                                           | 12        | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1046      | 65.91%  |
| Intel                                  | 194       | 12.22%  |
| Qualcomm Atheros                       | 127       | 8%      |
| Broadcom                               | 67        | 4.22%   |
| Marvell Technology Group               | 28        | 1.76%   |
| Nvidia                                 | 18        | 1.13%   |
| Samsung Electronics                    | 17        | 1.07%   |
| Xiaomi                                 | 13        | 0.82%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.76%   |
| Broadcom Limited                       | 11        | 0.69%   |
| ASIX Electronics                       | 7         | 0.44%   |
| JMicron Technology                     | 5         | 0.32%   |
| Huawei Technologies                    | 5         | 0.32%   |
| Apple                                  | 4         | 0.25%   |
| Microchip Technology                   | 3         | 0.19%   |
| ICS Advent                             | 3         | 0.19%   |
| Aquantia                               | 3         | 0.19%   |
| TP-Link                                | 2         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.13%   |
| Qualcomm                               | 2         | 0.13%   |
| OPPO Electronics                       | 2         | 0.13%   |
| Motorola PCS                           | 2         | 0.13%   |
| Attansic Technology                    | 2         | 0.13%   |
| VIA Technologies                       | 1         | 0.06%   |
| ULi Electronics                        | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Standard Microsystems                  | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Mellanox Technologies                  | 1         | 0.06%   |
| MediaTek                               | 1         | 0.06%   |
| LSI                                    | 1         | 0.06%   |
| Lenovo                                 | 1         | 0.06%   |
| Insyde Software                        | 1         | 0.06%   |
| HTC (High Tech Computer)               | 1         | 0.06%   |
| Davicom Semiconductor                  | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 789       | 49.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 177       | 10.99%  |
| Realtek RTL8125 2.5GbE Controller                                              | 31        | 1.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 22        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 22        | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 20        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                                           | 17        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 16        | 0.99%   |
| Intel I211 Gigabit Network Connection                                          | 14        | 0.87%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 12        | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 12        | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 12        | 0.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 11        | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 11        | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 11        | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 11        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 10        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 10        | 0.62%   |
| Intel 82579V Gigabit Network Connection                                        | 10        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 9         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 9         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 8         | 0.5%    |
| Intel I210 Gigabit Network Connection                                          | 8         | 0.5%    |
| Intel Ethernet Connection I217-LM                                              | 8         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.43%   |
| Nvidia MCP61 Ethernet                                                          | 7         | 0.43%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.43%   |
| Intel Ethernet Connection I217-V                                               | 7         | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 7         | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 6         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 6         | 0.37%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 6         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.31%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.31%   |
| Nvidia MCP79 Ethernet                                                          | 5         | 0.31%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1523      | 50.65%  |
| WiFi     | 1468      | 48.82%  |
| Modem    | 13        | 0.43%   |
| Unknown  | 3         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1202      | 66.85%  |
| Ethernet | 596       | 33.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1101      | 61.65%  |
| 1     | 614       | 34.38%  |
| 0     | 51        | 2.86%   |
| 3     | 14        | 0.78%   |
| 4     | 3         | 0.17%   |
| 16    | 1         | 0.06%   |
| 7     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1751      | 98.04%  |
| Yes  | 35        | 1.96%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 495       | 40.54%  |
| Realtek Semiconductor           | 140       | 11.47%  |
| Qualcomm Atheros Communications | 111       | 9.09%   |
| IMC Networks                    | 96        | 7.86%   |
| Cambridge Silicon Radio         | 69        | 5.65%   |
| Broadcom                        | 51        | 4.18%   |
| Lite-On Technology              | 45        | 3.69%   |
| Foxconn / Hon Hai               | 36        | 2.95%   |
| Apple                           | 36        | 2.95%   |
| Toshiba                         | 23        | 1.88%   |
| Realtek                         | 23        | 1.88%   |
| ASUSTek Computer                | 23        | 1.88%   |
| Ralink                          | 21        | 1.72%   |
| Dell                            | 13        | 1.06%   |
| Hewlett-Packard                 | 11        | 0.9%    |
| TP-Link                         | 7         | 0.57%   |
| MediaTek                        | 6         | 0.49%   |
| Ralink Technology               | 3         | 0.25%   |
| Foxconn International           | 3         | 0.25%   |
| Alps Electric                   | 3         | 0.25%   |
| Marvell Semiconductor           | 2         | 0.16%   |
| Qcom                            | 1         | 0.08%   |
| Logitech                        | 1         | 0.08%   |
| Integrated System Solution      | 1         | 0.08%   |
| HTC (High Tech Computer)        | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 165       | 13.5%   |
| Intel AX201 Bluetooth                               | 108       | 8.84%   |
| Realtek Bluetooth Radio                             | 92        | 7.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 79        | 6.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 69        | 5.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 55        | 4.5%    |
| Intel AX200 Bluetooth                               | 51        | 4.17%   |
| Intel Bluetooth Device                              | 44        | 3.6%    |
| IMC Networks Bluetooth Radio                        | 33        | 2.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 27        | 2.21%   |
| Realtek 802.11ac WLAN Adapter                       | 23        | 1.88%   |
| Ralink RT3290 Bluetooth                             | 21        | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.64%   |
| Apple Bluetooth Host Controller                     | 19        | 1.55%   |
| IMC Networks Bluetooth Device                       | 18        | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 14        | 1.15%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.06%   |
| Lite-On Bluetooth Device                            | 13        | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 1.06%   |
| IMC Networks Bluetooth USB Host Controller          | 12        | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 11        | 0.9%    |
| IMC Networks Wireless_Device                        | 10        | 0.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.82%   |
| IMC Networks Bluetooth                              | 9         | 0.74%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 8         | 0.65%   |
| TP-Link UB5A Adapter                                | 7         | 0.57%   |
| Realtek RTL8821A Bluetooth                          | 7         | 0.57%   |
| ASUS BT-253 Bluetooth Adapter                       | 7         | 0.57%   |
| Lite-On Wireless_Device                             | 6         | 0.49%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.49%   |
| Toshiba Askey Bluetooth Module                      | 5         | 0.41%   |
| MediaTek Wireless_Device                            | 5         | 0.41%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1302      | 55.15%  |
| AMD                                             | 512       | 21.69%  |
| Nvidia                                          | 406       | 17.2%   |
| C-Media Electronics                             | 23        | 0.97%   |
| Silicon Integrated Systems [SiS]                | 12        | 0.51%   |
| Barco Display Systems                           | 9         | 0.38%   |
| Kingston Technology                             | 7         | 0.3%    |
| Logitech                                        | 6         | 0.25%   |
| Generalplus Technology                          | 6         | 0.25%   |
| Creative Labs                                   | 6         | 0.25%   |
| VIA Technologies                                | 5         | 0.21%   |
| Tenx Technology                                 | 5         | 0.21%   |
| JMTek                                           | 5         | 0.21%   |
| Apple                                           | 5         | 0.21%   |
| Yamaha                                          | 3         | 0.13%   |
| Texas Instruments                               | 3         | 0.13%   |
| Realtek Semiconductor                           | 3         | 0.13%   |
| GN Netcom                                       | 3         | 0.13%   |
| SteelSeries ApS                                 | 2         | 0.08%   |
| M-Audio                                         | 2         | 0.08%   |
| LG Electronics                                  | 2         | 0.08%   |
| GYROCOM C&C                                     | 2         | 0.08%   |
| Focusrite-Novation                              | 2         | 0.08%   |
| DSEA A/S                                        | 2         | 0.08%   |
| Creative Technology                             | 2         | 0.08%   |
| ASUSTek Computer                                | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.04%   |
| ULi Electronics                                 | 1         | 0.04%   |
| Trust                                           | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.04%   |
| Sony                                            | 1         | 0.04%   |
| RODE Microphones                                | 1         | 0.04%   |
| Native Instruments                              | 1         | 0.04%   |
| Micro Star International                        | 1         | 0.04%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.04%   |
| Hewlett-Packard                                 | 1         | 0.04%   |
| Google                                          | 1         | 0.04%   |
| Global Sun Technology                           | 1         | 0.04%   |
| Evolution Electronics                           | 1         | 0.04%   |
| Earth Computer Technologies                     | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 186       | 6.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 144       | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 124       | 4.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 123       | 4.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 97        | 3.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 72        | 2.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 72        | 2.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 65        | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 63        | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 60        | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 55        | 1.95%   |
| Intel 8 Series HD Audio Controller                                         | 55        | 1.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 53        | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 52        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 49        | 1.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 48        | 1.7%    |
| Nvidia GF108 High Definition Audio Controller                              | 48        | 1.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 46        | 1.63%   |
| Intel Comet Lake PCH cAVS                                                  | 46        | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 46        | 1.63%   |
| Intel Broadwell-U Audio Controller                                         | 44        | 1.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 43        | 1.52%   |
| AMD FCH Azalia Controller                                                  | 41        | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 38        | 1.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 35        | 1.24%   |
| Intel CM238 HD Audio Controller                                            | 31        | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                              | 30        | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 30        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 29        | 1.03%   |
| Intel 200 Series PCH HD Audio                                              | 28        | 0.99%   |
| Nvidia Audio device                                                        | 26        | 0.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 25        | 0.89%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 25        | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                   | 25        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 24        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 23        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 23        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 21        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 281       | 25.5%   |
| SK hynix            | 174       | 15.79%  |
| Kingston            | 155       | 14.07%  |
| Micron Technology   | 107       | 9.71%   |
| Unknown             | 105       | 9.53%   |
| Crucial             | 56        | 5.08%   |
| Corsair             | 38        | 3.45%   |
| A-DATA Technology   | 33        | 2.99%   |
| G.Skill             | 32        | 2.9%    |
| Ramaxel Technology  | 21        | 1.91%   |
| Nanya Technology    | 16        | 1.45%   |
| Elpida              | 11        | 1%      |
| Unknown             | 11        | 1%      |
| Goldkey             | 7         | 0.64%   |
| Team                | 6         | 0.54%   |
| Unknown (ABCD)      | 5         | 0.45%   |
| Transcend           | 5         | 0.45%   |
| Timetec             | 4         | 0.36%   |
| Apacer              | 4         | 0.36%   |
| Neo Forza           | 3         | 0.27%   |
| Kllisre             | 2         | 0.18%   |
| Hikvision           | 2         | 0.18%   |
| ChangXin Memory     | 2         | 0.18%   |
| Avant               | 2         | 0.18%   |
| ASint Technology    | 2         | 0.18%   |
| AMD                 | 2         | 0.18%   |
| Unknown (F288)      | 1         | 0.09%   |
| Unknown (0x4509)    | 1         | 0.09%   |
| Unknown (0x29E)     | 1         | 0.09%   |
| Unknown (0B38)      | 1         | 0.09%   |
| Unknown (07FB)      | 1         | 0.09%   |
| Unifosa             | 1         | 0.09%   |
| pqi                 | 1         | 0.09%   |
| Patriot             | 1         | 0.09%   |
| Lexar Co Limited    | 1         | 0.09%   |
| Innodisk            | 1         | 0.09%   |
| Golden Empire       | 1         | 0.09%   |
| Gold Key            | 1         | 0.09%   |
| ff                  | 1         | 0.09%   |
| A-DA                | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 17        | 1.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 13        | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 12        | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 12        | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 12        | 1.02%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 11        | 0.93%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 11        | 0.93%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 11        | 0.93%   |
| Unknown                                                     | 11        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 9         | 0.76%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 8         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 8         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 8         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 8         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 7         | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 7         | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 7         | 0.59%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s        | 7         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 6         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 6         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 6         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 6         | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.51%   |
| Crucial RAM CT8G4SFS8266.M8FD 8192MB SODIMM DDR4 2667MT/s   | 6         | 0.51%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s        | 6         | 0.51%   |
| Unknown RAM Module 2GB DIMM 800MT/s                         | 5         | 0.42%   |
| Unknown RAM Module 1GB SODIMM DDR2                          | 5         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 5         | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s    | 5         | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 5         | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 5         | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 5         | 0.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 5         | 0.42%   |
| G.Skill RAM F4-3000C16-8GVRB 8GB DIMM DDR4 3200MT/s         | 5         | 0.42%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                   | 4         | 0.34%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 4         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 484       | 51.88%  |
| DDR3    | 291       | 31.19%  |
| LPDDR4  | 32        | 3.43%   |
| DDR2    | 29        | 3.11%   |
| Unknown | 28        | 3%      |
| SDRAM   | 23        | 2.47%   |
| LPDDR3  | 18        | 1.93%   |
| DDR5    | 10        | 1.07%   |
| LPDDR5  | 7         | 0.75%   |
| DDR     | 7         | 0.75%   |
| DRAM    | 3         | 0.32%   |
| EEPROM  | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 651       | 70.38%  |
| DIMM         | 196       | 21.19%  |
| Row Of Chips | 72        | 7.78%   |
| Unknown      | 4         | 0.43%   |
| Chip         | 2         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 424       | 40.93%  |
| 4096    | 290       | 27.99%  |
| 16384   | 128       | 12.36%  |
| 2048    | 120       | 11.58%  |
| 1024    | 34        | 3.28%   |
| 32768   | 31        | 2.99%   |
| 512     | 4         | 0.39%   |
| 65536   | 1         | 0.1%    |
| 1536    | 1         | 0.1%    |
| 256     | 1         | 0.1%    |
| 1       | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 200       | 19.86%  |
| 1600    | 193       | 19.17%  |
| 2667    | 176       | 17.48%  |
| 2400    | 83        | 8.24%   |
| 1333    | 46        | 4.57%   |
| 2133    | 44        | 4.37%   |
| 1334    | 36        | 3.57%   |
| Unknown | 31        | 3.08%   |
| 667     | 23        | 2.28%   |
| 3600    | 20        | 1.99%   |
| 800     | 17        | 1.69%   |
| 1067    | 16        | 1.59%   |
| 1867    | 13        | 1.29%   |
| 4199    | 12        | 1.19%   |
| 4800    | 8         | 0.79%   |
| 4267    | 7         | 0.7%    |
| 3000    | 7         | 0.7%    |
| 6400    | 6         | 0.6%    |
| 4266    | 6         | 0.6%    |
| 2800    | 6         | 0.6%    |
| 3733    | 5         | 0.5%    |
| 3400    | 5         | 0.5%    |
| 1066    | 5         | 0.5%    |
| 3266    | 4         | 0.4%    |
| 1866    | 4         | 0.4%    |
| 400     | 4         | 0.4%    |
| 8400    | 3         | 0.3%    |
| 3866    | 3         | 0.3%    |
| 3466    | 2         | 0.2%    |
| 2933    | 2         | 0.2%    |
| 2048    | 2         | 0.2%    |
| 1639    | 2         | 0.2%    |
| 533     | 2         | 0.2%    |
| 50410   | 1         | 0.1%    |
| 6000    | 1         | 0.1%    |
| 5808    | 1         | 0.1%    |
| 5500    | 1         | 0.1%    |
| 4133    | 1         | 0.1%    |
| 3800    | 1         | 0.1%    |
| 3151    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 32.43%  |
| Canon               | 12        | 32.43%  |
| Seiko Epson         | 6         | 16.22%  |
| Zebra               | 3         | 8.11%   |
| Samsung Electronics | 2         | 5.41%   |
| QinHeng Electronics | 1         | 2.7%    |
| Brother Industries  | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Zebra TLP2844                        | 2         | 5.26%   |
| Seiko Epson L3110 Series             | 2         | 5.26%   |
| HP Officejet 4500 G510g-m            | 2         | 5.26%   |
| HP LaserJet P2055 series             | 2         | 5.26%   |
| Canon LBP6030w/6018w                 | 2         | 5.26%   |
| Canon LBP6020                        | 2         | 5.26%   |
| Canon E410 series                    | 2         | 5.26%   |
| Zebra Zebra GC420d Label Printer     | 1         | 2.63%   |
| Seiko Epson L405 Series              | 1         | 2.63%   |
| Seiko Epson L210 Series              | 1         | 2.63%   |
| Seiko Epson FX-2190IIN               | 1         | 2.63%   |
| Seiko Epson ET-2710 Series           | 1         | 2.63%   |
| Samsung ML-216x Series Laser Printer | 1         | 2.63%   |
| Samsung M2020 Series                 | 1         | 2.63%   |
| QinHeng CH340S                       | 1         | 2.63%   |
| HP LaserJet P1102                    | 1         | 2.63%   |
| HP LaserJet M101-M106                | 1         | 2.63%   |
| HP LaserJet 1020                     | 1         | 2.63%   |
| HP LaserJet 1010                     | 1         | 2.63%   |
| HP DeskJet F2100 Printer series      | 1         | 2.63%   |
| HP DeskJet 3830 series               | 1         | 2.63%   |
| HP DeskJet 2600 series               | 1         | 2.63%   |
| HP DeskJet 2130 series               | 1         | 2.63%   |
| HP Deskjet 1050 J410                 | 1         | 2.63%   |
| Canon PIXMA MX340                    | 1         | 2.63%   |
| Canon PIXMA MG3000 series            | 1         | 2.63%   |
| Canon LBP6000                        | 1         | 2.63%   |
| Canon G3020 series                   | 1         | 2.63%   |
| Canon G3010 series                   | 1         | 2.63%   |
| Canon E460 series                    | 1         | 2.63%   |
| Brother DCP-1510                     | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 50%     |
| Canon          | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 50%     |
| Canon CanoScan LiDE 210            | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 292       | 23.21%  |
| IMC Networks                           | 145       | 11.53%  |
| Realtek Semiconductor                  | 111       | 8.82%   |
| Bison Electronics                      | 102       | 8.11%   |
| Microdia                               | 79        | 6.28%   |
| Quanta                                 | 70        | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 5.09%   |
| Sunplus Innovation Technology          | 44        | 3.5%    |
| Syntek                                 | 41        | 3.26%   |
| Apple                                  | 37        | 2.94%   |
| Suyin                                  | 34        | 2.7%    |
| Silicon Motion                         | 23        | 1.83%   |
| Luxvisions Innotech Limited            | 23        | 1.83%   |
| Alcor Micro                            | 22        | 1.75%   |
| Acer                                   | 19        | 1.51%   |
| Logitech                               | 18        | 1.43%   |
| Lite-On Technology                     | 17        | 1.35%   |
| Z-Star Microelectronics                | 14        | 1.11%   |
| Ricoh                                  | 12        | 0.95%   |
| Samsung Electronics                    | 10        | 0.79%   |
| Importek                               | 8         | 0.64%   |
| ALi                                    | 7         | 0.56%   |
| Sonix Technology                       | 5         | 0.4%    |
| SunplusIT                              | 3         | 0.24%   |
| Shinetech                              | 3         | 0.24%   |
| Novatek Microelectronics               | 3         | 0.24%   |
| LG Electronics                         | 3         | 0.24%   |
| Lenovo                                 | 3         | 0.24%   |
| Jieli Technology                       | 3         | 0.24%   |
| HYGD-220628-A                          | 3         | 0.24%   |
| Genesys Logic                          | 3         | 0.24%   |
| Foxconn / Hon Hai                      | 3         | 0.24%   |
| Arkmicro Technologies                  | 3         | 0.24%   |
| Sunplus Technology                     | 2         | 0.16%   |
| Primax Electronics                     | 2         | 0.16%   |
| Microsoft                              | 2         | 0.16%   |
| MacroSilicon                           | 2         | 0.16%   |
| Generalplus Technology                 | 2         | 0.16%   |
| GEMBIRD                                | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 40        | 3.17%   |
| Microdia Integrated_Webcam_HD                                 | 36        | 2.85%   |
| IMC Networks Integrated Camera                                | 35        | 2.77%   |
| Chicony HD Webcam                                             | 34        | 2.69%   |
| Bison Integrated Camera                                       | 30        | 2.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 27        | 2.14%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 27        | 2.14%   |
| Realtek Integrated_Webcam_HD                                  | 25        | 1.98%   |
| Syntek Integrated Camera                                      | 24        | 1.9%    |
| Chicony USB2.0 VGA UVC WebCam                                 | 19        | 1.5%    |
| Quanta HD User Facing                                         | 15        | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                                  | 15        | 1.19%   |
| IMC Networks HD Camera                                        | 14        | 1.11%   |
| Bison HD Webcam                                               | 14        | 1.11%   |
| Realtek USB2.0 VGA UVC WebCam                                 | 13        | 1.03%   |
| Chicony USB2.0 Camera                                         | 13        | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                               | 13        | 1.03%   |
| Chicony USB 2.0 Camera                                        | 12        | 0.95%   |
| Chicony HP HD Camera                                          | 12        | 0.95%   |
| Bison BisonCam, NB Pro                                        | 12        | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                               | 11        | 0.87%   |
| Sunplus Integrated_Webcam_HD                                  | 10        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)                       | 10        | 0.79%   |
| Chicony Lenovo EasyCamera                                     | 10        | 0.79%   |
| Chicony HP Webcam                                             | 10        | 0.79%   |
| Chicony EasyCamera                                            | 10        | 0.79%   |
| Realtek USB Camera                                            | 9         | 0.71%   |
| Lite-On Integrated Camera                                     | 9         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 9         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera              | 9         | 0.71%   |
| Apple FaceTime HD Camera (Built-in)                           | 9         | 0.71%   |
| Syntek EasyCamera                                             | 8         | 0.63%   |
| Realtek Integrated Webcam                                     | 8         | 0.63%   |
| Quanta USB HD Webcam                                          | 8         | 0.63%   |
| Quanta ov9734_techfront_camera                                | 8         | 0.63%   |
| Quanta HP TrueVision HD Camera                                | 8         | 0.63%   |
| IMC Networks EasyCamera                                       | 8         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 8         | 0.63%   |
| Bison SunplusIT Integrated Camera                             | 8         | 0.63%   |
| Bison BisonCam,NB Pro                                         | 8         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 64        | 35.36%  |
| Synaptics                          | 43        | 23.76%  |
| Validity Sensors                   | 37        | 20.44%  |
| LighTuning Technology              | 14        | 7.73%   |
| AuthenTec                          | 9         | 4.97%   |
| Upek                               | 8         | 4.42%   |
| Elan Microelectronics              | 5         | 2.76%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 47        | 25.97%  |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 8.84%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 5.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 4.42%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 4.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.31%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.31%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 3.31%   |
| Synaptics  WBDI                                                            | 6         | 3.31%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 3.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.31%   |
| Synaptics WBDI                                                             | 5         | 2.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.76%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.21%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.66%   |
| Synaptics UWP WBDI                                                         | 3         | 1.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.66%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.66%   |
| AuthenTec AES2810                                                          | 3         | 1.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.66%   |
| AuthenTec AES1600                                                          | 3         | 1.66%   |
| Validity Sensors VFS491                                                    | 2         | 1.1%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.1%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.1%    |
| Elan ELAN:ARM-M4                                                           | 2         | 1.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.55%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.55%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.55%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.55%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.55%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 18        | 38.3%   |
| Alcor Micro           | 16        | 34.04%  |
| Advanced Card Systems | 6         | 12.77%  |
| Upek                  | 2         | 4.26%   |
| O2 Micro              | 2         | 4.26%   |
| Gemalto (was Gemplus) | 2         | 4.26%   |
| Lenovo                | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 34.04%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 14.89%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 12.77%  |
| Broadcom 58200                                                               | 3         | 6.38%   |
| Advanced Card Systems ACR39U                                                 | 3         | 6.38%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 6.38%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.26%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 4.26%   |
| Broadcom 5880                                                                | 2         | 4.26%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1271      | 69.49%  |
| 1     | 443       | 24.22%  |
| 2     | 96        | 5.25%   |
| 3     | 11        | 0.6%    |
| 4     | 5         | 0.27%   |
| 6     | 2         | 0.11%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 197       | 29.49%  |
| Fingerprint reader       | 181       | 27.1%   |
| Net/wireless             | 59        | 8.83%   |
| Multimedia controller    | 44        | 6.59%   |
| Chipcard                 | 39        | 5.84%   |
| Camera                   | 37        | 5.54%   |
| Bluetooth                | 32        | 4.79%   |
| Communication controller | 28        | 4.19%   |
| Net/ethernet             | 13        | 1.95%   |
| Sound                    | 12        | 1.8%    |
| Storage                  | 9         | 1.35%   |
| Network                  | 5         | 0.75%   |
| Unassigned class         | 4         | 0.6%    |
| Flash memory             | 2         | 0.3%    |
| Card reader              | 2         | 0.3%    |
| Wireless                 | 1         | 0.15%   |
| Storage/raid             | 1         | 0.15%   |
| Storage/ide              | 1         | 0.15%   |
| Modem                    | 1         | 0.15%   |

