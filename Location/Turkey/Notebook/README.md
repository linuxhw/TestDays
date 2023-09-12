Linux in Turkey - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Turkey.

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

Total: 1946

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 1525               | [6b0747dcb4](https://linux-hardware.org/?probe=6b0747dcb4) | Sep 07, 2023 |
| Dell          | Inspiron 1525               | [56a481c501](https://linux-hardware.org/?probe=56a481c501) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0692b6f878](https://linux-hardware.org/?probe=0692b6f878) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [a1c2c12b6f](https://linux-hardware.org/?probe=a1c2c12b6f) | Sep 06, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| Dell          | Latitude 3190               | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dda5b7f9c9](https://linux-hardware.org/?probe=dda5b7f9c9) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| Monster       | Huma H5 V3.2                | [75d95e264e](https://linux-hardware.org/?probe=75d95e264e) | Sep 04, 2023 |
| Acer          | Aspire ES1-533              | [9c788645a1](https://linux-hardware.org/?probe=9c788645a1) | Sep 03, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3900a91c0b](https://linux-hardware.org/?probe=3900a91c0b) | Sep 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 16ARH7 ... | [13ea608a94](https://linux-hardware.org/?probe=13ea608a94) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [d00f64dfcf](https://linux-hardware.org/?probe=d00f64dfcf) | Sep 02, 2023 |
| Apple         | MacBook5,1                  | [78037f5e38](https://linux-hardware.org/?probe=78037f5e38) | Sep 02, 2023 |
| Dell          | G3 3779                     | [56fa43078f](https://linux-hardware.org/?probe=56fa43078f) | Sep 02, 2023 |
| Apple         | MacBookPro11,2              | [04acccf8e2](https://linux-hardware.org/?probe=04acccf8e2) | Sep 02, 2023 |
| Casper        | EXCALIBUR G770              | [9224e20101](https://linux-hardware.org/?probe=9224e20101) | Sep 01, 2023 |
| HP            | Pavilion 13                 | [ccf98e410b](https://linux-hardware.org/?probe=ccf98e410b) | Sep 01, 2023 |
| HP            | Pavilion 13                 | [b3e756ad21](https://linux-hardware.org/?probe=b3e756ad21) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| Dell          | Precision 7730              | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| Dell          | Inspiron 15 3511            | [3713bc7b70](https://linux-hardware.org/?probe=3713bc7b70) | Aug 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [8c492a4b3d](https://linux-hardware.org/?probe=8c492a4b3d) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| Dell          | G5 5505                     | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| ASUSTek       | GL753VD                     | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| Apple         | MacBookAir7,2               | [bb8b8a594d](https://linux-hardware.org/?probe=bb8b8a594d) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [c437fa21b3](https://linux-hardware.org/?probe=c437fa21b3) | Aug 27, 2023 |
| HUAWEI        | HN-WX9X                     | [d526f12390](https://linux-hardware.org/?probe=d526f12390) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [0bda6b93da](https://linux-hardware.org/?probe=0bda6b93da) | Aug 27, 2023 |
| Dell          | Vostro 5468                 | [2ee2b86d87](https://linux-hardware.org/?probe=2ee2b86d87) | Aug 27, 2023 |
| HP            | Laptop 14-em0xxx            | [b59ee89595](https://linux-hardware.org/?probe=b59ee89595) | Aug 26, 2023 |
| HUAWEI        | HN-WX9X                     | [95ff13464e](https://linux-hardware.org/?probe=95ff13464e) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| HP            | Laptop 15-da2xxx            | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [ab538d0486](https://linux-hardware.org/?probe=ab538d0486) | Aug 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [c86d5e890a](https://linux-hardware.org/?probe=c86d5e890a) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [a1d2ccf421](https://linux-hardware.org/?probe=a1d2ccf421) | Aug 22, 2023 |
| Acer          | TravelMate P215-52G         | [e8673e8d9c](https://linux-hardware.org/?probe=e8673e8d9c) | Aug 21, 2023 |
| HP            | Pavilion g6                 | [ccecca0639](https://linux-hardware.org/?probe=ccecca0639) | Aug 21, 2023 |
| Apple         | MacBookAir7,2               | [c62fc8773a](https://linux-hardware.org/?probe=c62fc8773a) | Aug 21, 2023 |
| Pegatron      | A15                         | [624757036f](https://linux-hardware.org/?probe=624757036f) | Aug 20, 2023 |
| HP            | Pavilion g6                 | [45830a7769](https://linux-hardware.org/?probe=45830a7769) | Aug 20, 2023 |
| HP            | Pavilion g6                 | [d4ba2c046d](https://linux-hardware.org/?probe=d4ba2c046d) | Aug 20, 2023 |
| Acer          | Aspire A715-51G             | [19ecc69fc4](https://linux-hardware.org/?probe=19ecc69fc4) | Aug 19, 2023 |
| Dell          | XPS 17 9730                 | [e9ddab2ebc](https://linux-hardware.org/?probe=e9ddab2ebc) | Aug 18, 2023 |
| ASUSTek       | N53SV                       | [684ece88c0](https://linux-hardware.org/?probe=684ece88c0) | Aug 17, 2023 |
| ASUSTek       | N53SV                       | [8ddf822ac7](https://linux-hardware.org/?probe=8ddf822ac7) | Aug 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGS... | [52f2042a47](https://linux-hardware.org/?probe=52f2042a47) | Aug 14, 2023 |
| ASUSTek       | GL752VW                     | [17d837907e](https://linux-hardware.org/?probe=17d837907e) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | [a65f824e07](https://linux-hardware.org/?probe=a65f824e07) | Aug 14, 2023 |
| Sony          | SVE1712W1EB                 | [2da924ecb2](https://linux-hardware.org/?probe=2da924ecb2) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ab5728ee52](https://linux-hardware.org/?probe=ab5728ee52) | Aug 13, 2023 |
| Monster       | ABRA A5 V17.2               | [0049202ca7](https://linux-hardware.org/?probe=0049202ca7) | Aug 13, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| Sony          | SVE1712W1EB                 | [e65db8d147](https://linux-hardware.org/?probe=e65db8d147) | Aug 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [3a7d1d1f9b](https://linux-hardware.org/?probe=3a7d1d1f9b) | Aug 11, 2023 |
| Sony          | SVE1712W1EB                 | [6f323e0954](https://linux-hardware.org/?probe=6f323e0954) | Aug 11, 2023 |
| Lenovo        | ThinkPad L520 5017BW5       | [1a9bbdc058](https://linux-hardware.org/?probe=1a9bbdc058) | Aug 11, 2023 |
| MSI           | Bravo 15 C7VE               | [a58ca66b2f](https://linux-hardware.org/?probe=a58ca66b2f) | Aug 06, 2023 |
| MSI           | Bravo 15 C7VE               | [52bf9ffa35](https://linux-hardware.org/?probe=52bf9ffa35) | Aug 06, 2023 |
| Dell          | Latitude E7270              | [e7209c4bb7](https://linux-hardware.org/?probe=e7209c4bb7) | Aug 06, 2023 |
| HP            | Laptop 15-ra0xx             | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Lenovo        | ThinkPad T400 6475R1G       | [481e1aa044](https://linux-hardware.org/?probe=481e1aa044) | Aug 03, 2023 |
| Dell          | Inspiron 3542               | [33674f8b81](https://linux-hardware.org/?probe=33674f8b81) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [e1a79e094e](https://linux-hardware.org/?probe=e1a79e094e) | Aug 01, 2023 |
| Packard Be... | EasyNote TJ65               | [e5193cc5d3](https://linux-hardware.org/?probe=e5193cc5d3) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| Unknown       | HP Chromebook 14            | [ef963f6148](https://linux-hardware.org/?probe=ef963f6148) | Jul 31, 2023 |
| Google        | Snow                        | [422a01e612](https://linux-hardware.org/?probe=422a01e612) | Jul 31, 2023 |
| Google        | Peach Pit Rev 6+            | [18fff1679c](https://linux-hardware.org/?probe=18fff1679c) | Jul 31, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7486c0a60b](https://linux-hardware.org/?probe=7486c0a60b) | Jul 31, 2023 |
| Google        | Mighty                      | [6ed9cfe2d0](https://linux-hardware.org/?probe=6ed9cfe2d0) | Jul 31, 2023 |
| MSI           | U90/U100                    | [015b95ba2a](https://linux-hardware.org/?probe=015b95ba2a) | Jul 31, 2023 |
| Google        | Kevin                       | [ca1037f6ca](https://linux-hardware.org/?probe=ca1037f6ca) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [961a4eebbd](https://linux-hardware.org/?probe=961a4eebbd) | Jul 31, 2023 |
| Toshiba       | Satellite L755              | [9e9caad8ea](https://linux-hardware.org/?probe=9e9caad8ea) | Jul 31, 2023 |
| I-Life Dig... | ZED Air CX7                 | [2c897f0413](https://linux-hardware.org/?probe=2c897f0413) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Apple         | MacBookPro8,2               | [ffda715e5e](https://linux-hardware.org/?probe=ffda715e5e) | Jul 30, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [f7dce38938](https://linux-hardware.org/?probe=f7dce38938) | Jul 28, 2023 |
| HP            | 250 G3                      | [49b5a143cf](https://linux-hardware.org/?probe=49b5a143cf) | Jul 28, 2023 |
| Casper        | EXCALIBUR G770              | [1b416b9f01](https://linux-hardware.org/?probe=1b416b9f01) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| HP            | Pavilion g6                 | [6d6fe6a05b](https://linux-hardware.org/?probe=6d6fe6a05b) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| ASUSTek       | K52JT                       | [c2cf59f878](https://linux-hardware.org/?probe=c2cf59f878) | Jul 25, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| Apple         | MacBook5,1                  | [83d48bc8eb](https://linux-hardware.org/?probe=83d48bc8eb) | Jul 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [fd59d670e2](https://linux-hardware.org/?probe=fd59d670e2) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [6a903d2c2f](https://linux-hardware.org/?probe=6a903d2c2f) | Jul 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [13ba381894](https://linux-hardware.org/?probe=13ba381894) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| Dell          | Latitude D610               | [791cabd713](https://linux-hardware.org/?probe=791cabd713) | Jul 16, 2023 |
| Dell          | G3 3779                     | [87b8ecffa4](https://linux-hardware.org/?probe=87b8ecffa4) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| Dell          | Inspiron 7577               | [a9b5963254](https://linux-hardware.org/?probe=a9b5963254) | Jul 13, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| Apple         | MacBookAir3,2               | [cbfc272e87](https://linux-hardware.org/?probe=cbfc272e87) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [a14d8855bc](https://linux-hardware.org/?probe=a14d8855bc) | Jul 10, 2023 |
| ASUSTek       | X550DP                      | [4cfcff7d7e](https://linux-hardware.org/?probe=4cfcff7d7e) | Jul 10, 2023 |
| Dell          | Latitude E6220              | [5e17659f32](https://linux-hardware.org/?probe=5e17659f32) | Jul 09, 2023 |
| Monster       | ABRA A5 V17.3               | [2b65146842](https://linux-hardware.org/?probe=2b65146842) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ae008e5343](https://linux-hardware.org/?probe=ae008e5343) | Jul 07, 2023 |
| Apple         | MacBookPro8,3               | [c93db722a7](https://linux-hardware.org/?probe=c93db722a7) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | [d1a5adf1ef](https://linux-hardware.org/?probe=d1a5adf1ef) | Jul 06, 2023 |
| Toshiba       | Satellite L755              | [cda93de5a6](https://linux-hardware.org/?probe=cda93de5a6) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d8206bf6c6](https://linux-hardware.org/?probe=d8206bf6c6) | Jul 05, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [53bd77d836](https://linux-hardware.org/?probe=53bd77d836) | Jul 05, 2023 |
| Google        | Lick                        | [f2b9397a8b](https://linux-hardware.org/?probe=f2b9397a8b) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [19a254cdee](https://linux-hardware.org/?probe=19a254cdee) | Jul 03, 2023 |
| ASUSTek       | X553MA                      | [969994628c](https://linux-hardware.org/?probe=969994628c) | Jun 30, 2023 |
| ASUSTek       | X553MA                      | [53a5b9567e](https://linux-hardware.org/?probe=53a5b9567e) | Jun 30, 2023 |
| ASUSTek       | K501UX                      | [a7fb172b7d](https://linux-hardware.org/?probe=a7fb172b7d) | Jun 30, 2023 |
| Monster       | TULPAR T7 V21.7             | [046803a297](https://linux-hardware.org/?probe=046803a297) | Jun 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c6edbe5681](https://linux-hardware.org/?probe=c6edbe5681) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HP            | G62                         | [e8187f4fb6](https://linux-hardware.org/?probe=e8187f4fb6) | Jun 24, 2023 |
| Apple         | MacBookPro9,2               | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [6609cc4a31](https://linux-hardware.org/?probe=6609cc4a31) | Jun 22, 2023 |
| Acer          | Nitro AN515-58              | [cbf5b19c76](https://linux-hardware.org/?probe=cbf5b19c76) | Jun 21, 2023 |
| Casper        | EXCALIBUR G770              | [9fef8732b6](https://linux-hardware.org/?probe=9fef8732b6) | Jun 21, 2023 |
| Toshiba       | Satellite L755              | [eea8633642](https://linux-hardware.org/?probe=eea8633642) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1595a5adbd](https://linux-hardware.org/?probe=1595a5adbd) | Jun 20, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [f49534dfa4](https://linux-hardware.org/?probe=f49534dfa4) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | [d09c902c57](https://linux-hardware.org/?probe=d09c902c57) | Jun 19, 2023 |
| Apple         | MacBookPro11,2              | [6e1e0b2f1c](https://linux-hardware.org/?probe=6e1e0b2f1c) | Jun 19, 2023 |
| Apple         | MacBook5,1                  | [4681ff2f7d](https://linux-hardware.org/?probe=4681ff2f7d) | Jun 19, 2023 |
| Acer          | Aspire 5750G                | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| Acer          | Aspire A515-57              | [e7f63885d1](https://linux-hardware.org/?probe=e7f63885d1) | Jun 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [fe97518345](https://linux-hardware.org/?probe=fe97518345) | Jun 17, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [d5ba369651](https://linux-hardware.org/?probe=d5ba369651) | Jun 17, 2023 |
| Dell          | Latitude E6410              | [5eff7cff21](https://linux-hardware.org/?probe=5eff7cff21) | Jun 15, 2023 |
| Sony          | SVE1513B1EW                 | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dc3b9443ef](https://linux-hardware.org/?probe=dc3b9443ef) | Jun 13, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Toshiba       | Satellite R630              | [aac5cdbb4f](https://linux-hardware.org/?probe=aac5cdbb4f) | Jun 12, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [d71e612bbb](https://linux-hardware.org/?probe=d71e612bbb) | Jun 11, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1de48a4515](https://linux-hardware.org/?probe=1de48a4515) | Jun 10, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | [c31b0e5f30](https://linux-hardware.org/?probe=c31b0e5f30) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| ASUSTek       | GL752VW                     | [662e292b55](https://linux-hardware.org/?probe=662e292b55) | Jun 06, 2023 |
| ASUSTek       | GL752VW                     | [024a1f80a1](https://linux-hardware.org/?probe=024a1f80a1) | Jun 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [53cb8df21f](https://linux-hardware.org/?probe=53cb8df21f) | Jun 06, 2023 |
| Acer          | AO722                       | [b8f2636f02](https://linux-hardware.org/?probe=b8f2636f02) | Jun 04, 2023 |
| Hometech      | Alfa 470C                   | [ee3bd9eb81](https://linux-hardware.org/?probe=ee3bd9eb81) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3a51aa06b9](https://linux-hardware.org/?probe=3a51aa06b9) | Jun 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [a7c067f896](https://linux-hardware.org/?probe=a7c067f896) | Jun 02, 2023 |
| Dell          | G3 3579                     | [4e5b0f9800](https://linux-hardware.org/?probe=4e5b0f9800) | May 31, 2023 |
| Apple         | MacBook5,1                  | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| Toshiba       | Satellite R630              | [5bf801ac1f](https://linux-hardware.org/?probe=5bf801ac1f) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5839982a52](https://linux-hardware.org/?probe=5839982a52) | May 29, 2023 |
| HP            | Laptop 15-bs1xx             | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| Dell          | Latitude 5430               | [a0697218cc](https://linux-hardware.org/?probe=a0697218cc) | May 27, 2023 |
| Monster       | Huma H5 V3.1                | [ed569fe821](https://linux-hardware.org/?probe=ed569fe821) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| IX1401        | Unknown                     | [f1799b6c3a](https://linux-hardware.org/?probe=f1799b6c3a) | May 24, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [0c665ebdd8](https://linux-hardware.org/?probe=0c665ebdd8) | May 23, 2023 |
| Casper        | EXCALIBUR G770              | [ef088af2df](https://linux-hardware.org/?probe=ef088af2df) | May 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S3XR00    | [0f80e19e5b](https://linux-hardware.org/?probe=0f80e19e5b) | May 23, 2023 |
| Medion        | E6224                       | [65c26a4a09](https://linux-hardware.org/?probe=65c26a4a09) | May 23, 2023 |
| Medion        | E6224                       | [8e10b22b1f](https://linux-hardware.org/?probe=8e10b22b1f) | May 23, 2023 |
| Lenovo        | Unknown                     | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Acer          | Nitro AN515-45              | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| ASUSTek       | X555LNB                     | [a1aa3cf4b2](https://linux-hardware.org/?probe=a1aa3cf4b2) | May 22, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3a448141db](https://linux-hardware.org/?probe=3a448141db) | May 21, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [6bce5f1ff0](https://linux-hardware.org/?probe=6bce5f1ff0) | May 20, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cb9ac11e18](https://linux-hardware.org/?probe=cb9ac11e18) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | [d07aa12d74](https://linux-hardware.org/?probe=d07aa12d74) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | [d2908ee6a9](https://linux-hardware.org/?probe=d2908ee6a9) | May 17, 2023 |
| HP            | Pavilion dv6                | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| ASUSTek       | S451LB                      | [f43e2b2679](https://linux-hardware.org/?probe=f43e2b2679) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Acer          | Aspire A315-58G             | [996701dcbd](https://linux-hardware.org/?probe=996701dcbd) | May 12, 2023 |
| HP            | Victus by Gaming Laptop ... | [6b9e3d06b1](https://linux-hardware.org/?probe=6b9e3d06b1) | May 11, 2023 |
| HP            | 250 G6 Notebook PC          | [a7cc3561af](https://linux-hardware.org/?probe=a7cc3561af) | May 10, 2023 |
| HUAWEI        | KLVL-WXX9                   | [68720e9d6b](https://linux-hardware.org/?probe=68720e9d6b) | May 10, 2023 |
| Acer          | Extensa 215-54              | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Acer          | Extensa 215-54              | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| HP            | Laptop 15-da0xxx            | [6a93900fb9](https://linux-hardware.org/?probe=6a93900fb9) | May 07, 2023 |
| HT            | C20C WSTKA001               | [a7ffbb2fe3](https://linux-hardware.org/?probe=a7ffbb2fe3) | May 07, 2023 |
| HUAWEI        | CREM-WXX9                   | [93aaae065b](https://linux-hardware.org/?probe=93aaae065b) | May 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [2a8bbbef3d](https://linux-hardware.org/?probe=2a8bbbef3d) | May 06, 2023 |
| Monster       | ABRA A5 V16.4               | [a5507638d0](https://linux-hardware.org/?probe=a5507638d0) | May 06, 2023 |
| Packard Be... | EasyNote TE69HW             | [fff5650658](https://linux-hardware.org/?probe=fff5650658) | May 05, 2023 |
| Acer          | Nitro AN515-58              | [e788d3fee0](https://linux-hardware.org/?probe=e788d3fee0) | May 04, 2023 |
| Apple         | MacBook5,1                  | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [6f6a016997](https://linux-hardware.org/?probe=6f6a016997) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Monster       | TULPAR T5 V21.7             | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [8c4ba894b4](https://linux-hardware.org/?probe=8c4ba894b4) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [69d1f17b35](https://linux-hardware.org/?probe=69d1f17b35) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [f9671dc0a4](https://linux-hardware.org/?probe=f9671dc0a4) | Apr 26, 2023 |
| HP            | 240 G8                      | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| HP            | ProBook 4540s               | [854f17fcac](https://linux-hardware.org/?probe=854f17fcac) | Apr 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [bb1a40d839](https://linux-hardware.org/?probe=bb1a40d839) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8b18bb529f](https://linux-hardware.org/?probe=8b18bb529f) | Apr 21, 2023 |
| Lenovo        | Unknown                     | [99a0c76ea9](https://linux-hardware.org/?probe=99a0c76ea9) | Apr 18, 2023 |
| Lenovo        | Unknown                     | [653cf225b8](https://linux-hardware.org/?probe=653cf225b8) | Apr 17, 2023 |
| HUAWEI        | HVY-WXX9                    | [3d14cefd78](https://linux-hardware.org/?probe=3d14cefd78) | Apr 17, 2023 |
| ASUSTek       | X55A                        | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [cc0b87e611](https://linux-hardware.org/?probe=cc0b87e611) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [8152bff1b3](https://linux-hardware.org/?probe=8152bff1b3) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| Sony          | VPCEB3J1E                   | [1405405cbb](https://linux-hardware.org/?probe=1405405cbb) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [11ecb91fec](https://linux-hardware.org/?probe=11ecb91fec) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | [396850fd22](https://linux-hardware.org/?probe=396850fd22) | Apr 09, 2023 |
| ASUSTek       | GL552VW                     | [ab450c0ddd](https://linux-hardware.org/?probe=ab450c0ddd) | Apr 06, 2023 |
| Acer          | Aspire A315-42              | [5d0731fb7a](https://linux-hardware.org/?probe=5d0731fb7a) | Apr 05, 2023 |
| Acer          | Extensa 215-54              | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| Acer          | Aspire 5220                 | [d22076fd54](https://linux-hardware.org/?probe=d22076fd54) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b55be43d4c](https://linux-hardware.org/?probe=b55be43d4c) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [e6a732e9b0](https://linux-hardware.org/?probe=e6a732e9b0) | Apr 03, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [78bda6a16c](https://linux-hardware.org/?probe=78bda6a16c) | Apr 03, 2023 |
| Valve         | Jupiter                     | [38dc8922e4](https://linux-hardware.org/?probe=38dc8922e4) | Apr 03, 2023 |
| HP            | Pavilion 15                 | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [804bf25c27](https://linux-hardware.org/?probe=804bf25c27) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6eb533f1d7](https://linux-hardware.org/?probe=6eb533f1d7) | Apr 01, 2023 |
| Toshiba       | Satellite L655              | [d527726a1c](https://linux-hardware.org/?probe=d527726a1c) | Mar 31, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6915349237](https://linux-hardware.org/?probe=6915349237) | Mar 31, 2023 |
| HP            | 250 G6 Notebook PC          | [159d154fca](https://linux-hardware.org/?probe=159d154fca) | Mar 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b960038661](https://linux-hardware.org/?probe=b960038661) | Mar 27, 2023 |
| ASUSTek       | X540UP                      | [39802560c1](https://linux-hardware.org/?probe=39802560c1) | Mar 27, 2023 |
| ASUSTek       | E502NA                      | [a116400859](https://linux-hardware.org/?probe=a116400859) | Mar 27, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [d7b97732fa](https://linux-hardware.org/?probe=d7b97732fa) | Mar 26, 2023 |
| Monster       | TULPAR T7 V19.5             | [4a4933c183](https://linux-hardware.org/?probe=4a4933c183) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [31788e7103](https://linux-hardware.org/?probe=31788e7103) | Mar 25, 2023 |
| Dell          | Vostro 5581                 | [d2ebb46bea](https://linux-hardware.org/?probe=d2ebb46bea) | Mar 25, 2023 |
| HONOR         | BBR-WAX9                    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [54cda388d8](https://linux-hardware.org/?probe=54cda388d8) | Mar 22, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5207701ff8](https://linux-hardware.org/?probe=5207701ff8) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Lenovo        | Unknown                     | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| ASUSTek       | TP500LB                     | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ac5495bdb4](https://linux-hardware.org/?probe=ac5495bdb4) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [45d6f54263](https://linux-hardware.org/?probe=45d6f54263) | Mar 19, 2023 |
| Acer          | Aspire 5935                 | [0634ed91ba](https://linux-hardware.org/?probe=0634ed91ba) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [88b7883383](https://linux-hardware.org/?probe=88b7883383) | Mar 19, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [32ba732ef0](https://linux-hardware.org/?probe=32ba732ef0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [3a565fb944](https://linux-hardware.org/?probe=3a565fb944) | Mar 18, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [e7e152095b](https://linux-hardware.org/?probe=e7e152095b) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [d79a6ae160](https://linux-hardware.org/?probe=d79a6ae160) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [691f338c53](https://linux-hardware.org/?probe=691f338c53) | Mar 17, 2023 |
| Lenovo        | Flex 2-15                   | [6bea7b508e](https://linux-hardware.org/?probe=6bea7b508e) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [66f69d578c](https://linux-hardware.org/?probe=66f69d578c) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Monster       | ABRA A7 V11.3               | [724a9e65d8](https://linux-hardware.org/?probe=724a9e65d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite C55-A-1K4         | [3ba10eda08](https://linux-hardware.org/?probe=3ba10eda08) | Mar 11, 2023 |
| MSI           | Alpha 15 A3DC               | [feabd7f5bf](https://linux-hardware.org/?probe=feabd7f5bf) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [44db3bc5ec](https://linux-hardware.org/?probe=44db3bc5ec) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [96e374345a](https://linux-hardware.org/?probe=96e374345a) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5f8598cfd](https://linux-hardware.org/?probe=b5f8598cfd) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [4745f71e81](https://linux-hardware.org/?probe=4745f71e81) | Mar 10, 2023 |
| Monster       | HUMA H4 V5.1                | [98c29f81d8](https://linux-hardware.org/?probe=98c29f81d8) | Mar 10, 2023 |
| HUAWEI        | HN-WX9X                     | [e55325be18](https://linux-hardware.org/?probe=e55325be18) | Mar 09, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [5535b412ed](https://linux-hardware.org/?probe=5535b412ed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | [39805e4790](https://linux-hardware.org/?probe=39805e4790) | Mar 09, 2023 |
| ASUSTek       | UX32LN                      | [d12e99f5d2](https://linux-hardware.org/?probe=d12e99f5d2) | Mar 09, 2023 |
| Acer          | Aspire A315-58              | [f4de2d1a2a](https://linux-hardware.org/?probe=f4de2d1a2a) | Mar 08, 2023 |
| Sony          | SVD11225CXB                 | [b5b755e185](https://linux-hardware.org/?probe=b5b755e185) | Mar 07, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [8961f32cc5](https://linux-hardware.org/?probe=8961f32cc5) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [d1a37d82cb](https://linux-hardware.org/?probe=d1a37d82cb) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [80ee932665](https://linux-hardware.org/?probe=80ee932665) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [c112aacdb6](https://linux-hardware.org/?probe=c112aacdb6) | Mar 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [ccd91fb0c7](https://linux-hardware.org/?probe=ccd91fb0c7) | Mar 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [4cb64cfa8f](https://linux-hardware.org/?probe=4cb64cfa8f) | Mar 03, 2023 |
| Dell          | Inspiron 3542               | [e230d5c136](https://linux-hardware.org/?probe=e230d5c136) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0864b4a50](https://linux-hardware.org/?probe=e0864b4a50) | Mar 02, 2023 |
| HP            | 15                          | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| ASUSTek       | X55A                        | [1429627725](https://linux-hardware.org/?probe=1429627725) | Feb 28, 2023 |
| Alienware     | 15 R2                       | [5e29609544](https://linux-hardware.org/?probe=5e29609544) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | [68a816d082](https://linux-hardware.org/?probe=68a816d082) | Feb 28, 2023 |
| Dell          | Venue 11 Pro 7130           | [bbb8c4e905](https://linux-hardware.org/?probe=bbb8c4e905) | Feb 28, 2023 |
| Lenovo        | G510 20238                  | [2dd6ac17cf](https://linux-hardware.org/?probe=2dd6ac17cf) | Feb 26, 2023 |
| HP            | 250 G6 Notebook PC          | [af6a897a26](https://linux-hardware.org/?probe=af6a897a26) | Feb 26, 2023 |
| Lenovo        | G510 20238                  | [2954f1a3c5](https://linux-hardware.org/?probe=2954f1a3c5) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [7858955f02](https://linux-hardware.org/?probe=7858955f02) | Feb 24, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7ff7ca240](https://linux-hardware.org/?probe=c7ff7ca240) | Feb 24, 2023 |
| Dell          | Inspiron 13-7359            | [39d95063c3](https://linux-hardware.org/?probe=39d95063c3) | Feb 23, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [be36fee6eb](https://linux-hardware.org/?probe=be36fee6eb) | Feb 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [40468a72ce](https://linux-hardware.org/?probe=40468a72ce) | Feb 20, 2023 |
| Sony          | VPCCB16FG                   | [0a6224bcc3](https://linux-hardware.org/?probe=0a6224bcc3) | Feb 19, 2023 |
| Valve         | Jupiter                     | [3543a34ca0](https://linux-hardware.org/?probe=3543a34ca0) | Feb 19, 2023 |
| HP            | Notebook                    | [2d03543f4c](https://linux-hardware.org/?probe=2d03543f4c) | Feb 18, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [75db698bfd](https://linux-hardware.org/?probe=75db698bfd) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [02d91d3f00](https://linux-hardware.org/?probe=02d91d3f00) | Feb 17, 2023 |
| Lenovo        | ThinkPad X220 4291ZD8       | [9dbad47bf0](https://linux-hardware.org/?probe=9dbad47bf0) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [514bbe20b5](https://linux-hardware.org/?probe=514bbe20b5) | Feb 15, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Pegatron      | H36ST                       | [2b0e74ca00](https://linux-hardware.org/?probe=2b0e74ca00) | Feb 13, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [a4b4558244](https://linux-hardware.org/?probe=a4b4558244) | Feb 12, 2023 |
| Toshiba       | PORTEGE Z830                | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [18cd6aad2c](https://linux-hardware.org/?probe=18cd6aad2c) | Feb 11, 2023 |
| HP            | 15                          | [162c6f9186](https://linux-hardware.org/?probe=162c6f9186) | Feb 11, 2023 |
| Lenovo        | ThinkPad X280 20KES2WC06    | [794dcaf42d](https://linux-hardware.org/?probe=794dcaf42d) | Feb 11, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [a410a7b784](https://linux-hardware.org/?probe=a410a7b784) | Feb 09, 2023 |
| Timi          | TM1701                      | [b3015735e6](https://linux-hardware.org/?probe=b3015735e6) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [edc2a0bc35](https://linux-hardware.org/?probe=edc2a0bc35) | Feb 09, 2023 |
| Monster       | TULPAR T7 V5.x              | [8d1a082e35](https://linux-hardware.org/?probe=8d1a082e35) | Feb 09, 2023 |
| Sony          | VPCEH1M1E                   | [43f51d50c1](https://linux-hardware.org/?probe=43f51d50c1) | Feb 09, 2023 |
| HUAWEI        | BOD-WXX9                    | [1d05e35623](https://linux-hardware.org/?probe=1d05e35623) | Feb 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [ffce390164](https://linux-hardware.org/?probe=ffce390164) | Feb 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [7fd90f29c1](https://linux-hardware.org/?probe=7fd90f29c1) | Feb 08, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e1fc422565](https://linux-hardware.org/?probe=e1fc422565) | Feb 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [234f1c81c2](https://linux-hardware.org/?probe=234f1c81c2) | Feb 07, 2023 |
| Packard Be... | SJV50MV                     | [930ac749ca](https://linux-hardware.org/?probe=930ac749ca) | Feb 07, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [295fd70d70](https://linux-hardware.org/?probe=295fd70d70) | Feb 05, 2023 |
| ASUSTek       | UX32LN                      | [5b16a4a572](https://linux-hardware.org/?probe=5b16a4a572) | Feb 05, 2023 |
| Packard Be... | SJV50MV                     | [ff862a12ae](https://linux-hardware.org/?probe=ff862a12ae) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.3             | [82f58f57c0](https://linux-hardware.org/?probe=82f58f57c0) | Feb 04, 2023 |
| Monster       | TULPAR T5 V20.1             | [b224ac6a46](https://linux-hardware.org/?probe=b224ac6a46) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8c9b8348a4](https://linux-hardware.org/?probe=8c9b8348a4) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | [d839e9036f](https://linux-hardware.org/?probe=d839e9036f) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.1               | [ed1785494a](https://linux-hardware.org/?probe=ed1785494a) | Feb 02, 2023 |
| HP            | Notebook                    | [82068da14b](https://linux-hardware.org/?probe=82068da14b) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| Toshiba       | Satellite R630              | [52ffe609b8](https://linux-hardware.org/?probe=52ffe609b8) | Jan 31, 2023 |
| Dell          | Latitude E6530              | [140543c98c](https://linux-hardware.org/?probe=140543c98c) | Jan 31, 2023 |
| Sony          | VPCCB16FG                   | [837588c9eb](https://linux-hardware.org/?probe=837588c9eb) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Sony          | VPCCB16FG                   | [7307480466](https://linux-hardware.org/?probe=7307480466) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [e789456756](https://linux-hardware.org/?probe=e789456756) | Jan 28, 2023 |
| ASUSTek       | X550VX                      | [37d2157b37](https://linux-hardware.org/?probe=37d2157b37) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| HP            | ProBook 6460b               | [81a1748477](https://linux-hardware.org/?probe=81a1748477) | Jan 25, 2023 |
| Toshiba       | QOSMIO X70-B                | [a7219ed5ef](https://linux-hardware.org/?probe=a7219ed5ef) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d03b7c0a68](https://linux-hardware.org/?probe=d03b7c0a68) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b37f2fcaba](https://linux-hardware.org/?probe=b37f2fcaba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [0e29c1dd04](https://linux-hardware.org/?probe=0e29c1dd04) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [395d565464](https://linux-hardware.org/?probe=395d565464) | Jan 22, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [fcce46f618](https://linux-hardware.org/?probe=fcce46f618) | Jan 21, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [f79928ed4d](https://linux-hardware.org/?probe=f79928ed4d) | Jan 21, 2023 |
| ASUSTek       | X556UQK                     | [54cf7414fd](https://linux-hardware.org/?probe=54cf7414fd) | Jan 20, 2023 |
| HP            | Pavilion g6                 | [d828f8f4a8](https://linux-hardware.org/?probe=d828f8f4a8) | Jan 19, 2023 |
| HP            | Pavilion g6                 | [282b1007ac](https://linux-hardware.org/?probe=282b1007ac) | Jan 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [6a47296f0c](https://linux-hardware.org/?probe=6a47296f0c) | Jan 19, 2023 |
| Acer          | Nitro AN515-46              | [1de96d005a](https://linux-hardware.org/?probe=1de96d005a) | Jan 16, 2023 |
| Acer          | Nitro AN515-46              | [f0eab1c81a](https://linux-hardware.org/?probe=f0eab1c81a) | Jan 16, 2023 |
| Lenovo        | ThinkPad SL500 2746A18      | [5535380e6c](https://linux-hardware.org/?probe=5535380e6c) | Jan 16, 2023 |
| Casper        | NIRVANA NOTEBOOK            | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| Monster       | TULPAR T5 V19.2             | [46bd0385fa](https://linux-hardware.org/?probe=46bd0385fa) | Jan 15, 2023 |
| Acer          | Swift SF314-43              | [e292f699eb](https://linux-hardware.org/?probe=e292f699eb) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | [4332a351bf](https://linux-hardware.org/?probe=4332a351bf) | Jan 13, 2023 |
| Acer          | Aspire A315-58              | [fc41631096](https://linux-hardware.org/?probe=fc41631096) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Apple         | MacBookPro9,2               | [2a71b87b09](https://linux-hardware.org/?probe=2a71b87b09) | Jan 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [93ffaa0920](https://linux-hardware.org/?probe=93ffaa0920) | Jan 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [010a4fc9bd](https://linux-hardware.org/?probe=010a4fc9bd) | Jan 10, 2023 |
| ASUSTek       | K55VD                       | [401e0c3743](https://linux-hardware.org/?probe=401e0c3743) | Jan 10, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [179af39858](https://linux-hardware.org/?probe=179af39858) | Jan 08, 2023 |
| ODM           | MS-16K2                     | [f9a7d267e5](https://linux-hardware.org/?probe=f9a7d267e5) | Jan 08, 2023 |
| MSI           | GF63 8RC                    | [9222c5a0a6](https://linux-hardware.org/?probe=9222c5a0a6) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [ef45fa4056](https://linux-hardware.org/?probe=ef45fa4056) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| HP            | Laptop 15-bw0xx             | [36c97306ae](https://linux-hardware.org/?probe=36c97306ae) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c47405aaf4](https://linux-hardware.org/?probe=c47405aaf4) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Apple         | MacBook5,1                  | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [c7d37a7616](https://linux-hardware.org/?probe=c7d37a7616) | Jan 04, 2023 |
| Monster       | Huma H5 V3.2                | [cab22e2b7b](https://linux-hardware.org/?probe=cab22e2b7b) | Jan 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [113d6b92d1](https://linux-hardware.org/?probe=113d6b92d1) | Jan 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [7783f397ec](https://linux-hardware.org/?probe=7783f397ec) | Jan 03, 2023 |
| HUAWEI        | MACH-WX9                    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [b1d353931a](https://linux-hardware.org/?probe=b1d353931a) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| HUAWEI        | KLVL-WXX9                   | [20e752831c](https://linux-hardware.org/?probe=20e752831c) | Jan 01, 2023 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Packard Be... | EasyNote TE69HW             | [9613dfc76b](https://linux-hardware.org/?probe=9613dfc76b) | Dec 28, 2022 |
| Dell          | Inspiron 3521               | [9d544fbcd4](https://linux-hardware.org/?probe=9d544fbcd4) | Dec 26, 2022 |
| ASUSTek       | GL752VW                     | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| Dell          | Latitude 5521               | [32d3e87886](https://linux-hardware.org/?probe=32d3e87886) | Dec 25, 2022 |
| Hometech      | Alfa 420C                   | [9dcf2c28b3](https://linux-hardware.org/?probe=9dcf2c28b3) | Dec 23, 2022 |
| Hometech      | Alfa 420C                   | [5a4f33dd7b](https://linux-hardware.org/?probe=5a4f33dd7b) | Dec 22, 2022 |
| Monster       | ABRA A5 V18.1               | [d151d1eb82](https://linux-hardware.org/?probe=d151d1eb82) | Dec 21, 2022 |
| HP            | Pavilion Power Laptop 15... | [12bb45433d](https://linux-hardware.org/?probe=12bb45433d) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4906017260](https://linux-hardware.org/?probe=4906017260) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [085b8c23b4](https://linux-hardware.org/?probe=085b8c23b4) | Dec 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [87d3186549](https://linux-hardware.org/?probe=87d3186549) | Dec 20, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [d79e681980](https://linux-hardware.org/?probe=d79e681980) | Dec 19, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [72bfd0a0f6](https://linux-hardware.org/?probe=72bfd0a0f6) | Dec 19, 2022 |
| Dell          | Latitude 5521               | [3d3be9c8e9](https://linux-hardware.org/?probe=3d3be9c8e9) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| Pegatron      | H36FF                       | [f27fc61f18](https://linux-hardware.org/?probe=f27fc61f18) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| Pegatron      | H36FF                       | [692955be3d](https://linux-hardware.org/?probe=692955be3d) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [df49d0114f](https://linux-hardware.org/?probe=df49d0114f) | Dec 17, 2022 |
| Acer          | Aspire A315-41G             | [8641a184ad](https://linux-hardware.org/?probe=8641a184ad) | Dec 17, 2022 |
| Toshiba       | Satellite C660              | [5d14354a02](https://linux-hardware.org/?probe=5d14354a02) | Dec 16, 2022 |
| Lenovo        | Flex 2-15                   | [38670ac27c](https://linux-hardware.org/?probe=38670ac27c) | Dec 16, 2022 |
| HP            | Laptop 14-cm0xxx            | [a5bdc5f3c9](https://linux-hardware.org/?probe=a5bdc5f3c9) | Dec 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Monster       | HUMA H4 V4.1                | [e4f2e85204](https://linux-hardware.org/?probe=e4f2e85204) | Dec 14, 2022 |
| Acer          | Aspire A515-41G             | [fb7da9e239](https://linux-hardware.org/?probe=fb7da9e239) | Dec 10, 2022 |
| HP            | 250 G8 Notebook PC          | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| Toshiba       | Satellite C660              | [27f508f09e](https://linux-hardware.org/?probe=27f508f09e) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| Toshiba       | Satellite L655              | [741c3e22b7](https://linux-hardware.org/?probe=741c3e22b7) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [92f4bd5ee1](https://linux-hardware.org/?probe=92f4bd5ee1) | Dec 06, 2022 |
| Dell          | Inspiron 15-3567            | [ab7d61cced](https://linux-hardware.org/?probe=ab7d61cced) | Dec 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cf810b2e09](https://linux-hardware.org/?probe=cf810b2e09) | Dec 04, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| HP            | Pavilion 13 x360 PC         | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Dell          | Inspiron 15-3567            | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | [02f4319195](https://linux-hardware.org/?probe=02f4319195) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | [77ad02b5bd](https://linux-hardware.org/?probe=77ad02b5bd) | Nov 29, 2022 |
| Toshiba       | Satellite C660              | [ca7c59284c](https://linux-hardware.org/?probe=ca7c59284c) | Nov 28, 2022 |
| Dell          | G3 3500                     | [291b53ea79](https://linux-hardware.org/?probe=291b53ea79) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [415a8f0d8b](https://linux-hardware.org/?probe=415a8f0d8b) | Nov 27, 2022 |
| Lenovo        | V15-IIL 82C5                | [ceda4dbb46](https://linux-hardware.org/?probe=ceda4dbb46) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | [a116300d12](https://linux-hardware.org/?probe=a116300d12) | Nov 27, 2022 |
| Notebook      | NL40_50CU                   | [a30ad69ac2](https://linux-hardware.org/?probe=a30ad69ac2) | Nov 27, 2022 |
| Toshiba       | Satellite C660              | [9da0a974dd](https://linux-hardware.org/?probe=9da0a974dd) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| MSI           | Modern 14 B5M               | [bf3c55e13b](https://linux-hardware.org/?probe=bf3c55e13b) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [408158ed97](https://linux-hardware.org/?probe=408158ed97) | Nov 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [dce27f6d43](https://linux-hardware.org/?probe=dce27f6d43) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [ef46869de3](https://linux-hardware.org/?probe=ef46869de3) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [f02593fc75](https://linux-hardware.org/?probe=f02593fc75) | Nov 23, 2022 |
| HP            | Pavilion g6                 | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | ZBook 15 G2                 | [5f040880ce](https://linux-hardware.org/?probe=5f040880ce) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | Pavilion g6                 | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| Acer          | TravelMate 5360             | [c2dfb8625b](https://linux-hardware.org/?probe=c2dfb8625b) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [af679e6195](https://linux-hardware.org/?probe=af679e6195) | Nov 17, 2022 |
| Apple         | MacBook5,1                  | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d3d2afd2c3](https://linux-hardware.org/?probe=d3d2afd2c3) | Nov 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [450e658685](https://linux-hardware.org/?probe=450e658685) | Nov 16, 2022 |
| Lenovo        | Z50-70 20354                | [15087fec90](https://linux-hardware.org/?probe=15087fec90) | Nov 16, 2022 |
| Acer          | Aspire 5720Z                | [930beb6857](https://linux-hardware.org/?probe=930beb6857) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| HP            | EliteBook Folio 1040 G2     | [3f95d3f191](https://linux-hardware.org/?probe=3f95d3f191) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [1cb724a4d5](https://linux-hardware.org/?probe=1cb724a4d5) | Nov 15, 2022 |
| HP            | 530                         | [337ff0c5ea](https://linux-hardware.org/?probe=337ff0c5ea) | Nov 15, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [700e2ffc46](https://linux-hardware.org/?probe=700e2ffc46) | Nov 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9506350a75](https://linux-hardware.org/?probe=9506350a75) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b966d9e8c9](https://linux-hardware.org/?probe=b966d9e8c9) | Nov 13, 2022 |
| Toshiba       | Satellite C870-D7K          | [b2f60a1b4d](https://linux-hardware.org/?probe=b2f60a1b4d) | Nov 11, 2022 |
| Monster       | ABRA A5 V15.6               | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| Acer          | Nitro AN515-46              | [741209999d](https://linux-hardware.org/?probe=741209999d) | Nov 10, 2022 |
| HP            | ZBook 15 G2                 | [02944a1b38](https://linux-hardware.org/?probe=02944a1b38) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Monster       | TULPAR T7 V21.7             | [1106dc2d92](https://linux-hardware.org/?probe=1106dc2d92) | Nov 07, 2022 |
| ASUSTek       | UX490UAR                    | [dc90947100](https://linux-hardware.org/?probe=dc90947100) | Nov 07, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [80dbecb998](https://linux-hardware.org/?probe=80dbecb998) | Nov 04, 2022 |
| HP            | Pavilion 15                 | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
| HP            | ZBook 15 G2                 | [7254a9a2fc](https://linux-hardware.org/?probe=7254a9a2fc) | Nov 01, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [73aa3e4a7e](https://linux-hardware.org/?probe=73aa3e4a7e) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| MSI           | Prestige 14 A10SC           | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [c2d1799732](https://linux-hardware.org/?probe=c2d1799732) | Oct 29, 2022 |
| Apple         | MacBookPro5,3               | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| MSI           | Prestige 14 A10SC           | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Monster       | HUMA H4 V4.1                | [b086433e61](https://linux-hardware.org/?probe=b086433e61) | Oct 26, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| Acer          | Aspire A715-42G             | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Monster       | HUMA H4 V4.1                | [06a31b0132](https://linux-hardware.org/?probe=06a31b0132) | Oct 24, 2022 |
| Monster       | TULPAR T7                   | [5d01101cee](https://linux-hardware.org/?probe=5d01101cee) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| Monster       | ABRA A5 V15.2               | [cb1a5559dc](https://linux-hardware.org/?probe=cb1a5559dc) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Dell          | Latitude E6220              | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Monster       | TULPAR T5 V21.6             | [eaeb6f6610](https://linux-hardware.org/?probe=eaeb6f6610) | Oct 17, 2022 |
| Acer          | Aspire 5750G                | [f7e44be1b5](https://linux-hardware.org/?probe=f7e44be1b5) | Oct 17, 2022 |
| HUAWEI        | BOD-WXX9                    | [cf556bb7f7](https://linux-hardware.org/?probe=cf556bb7f7) | Oct 16, 2022 |
| HUAWEI        | BOD-WXX9                    | [a8a52af0f4](https://linux-hardware.org/?probe=a8a52af0f4) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| ASUSTek       | X550VX                      | [adbd1fa089](https://linux-hardware.org/?probe=adbd1fa089) | Oct 14, 2022 |
| MSI           | GS40 6QE Phantom            | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| ASUSTek       | X550VX                      | [c0fefb30fe](https://linux-hardware.org/?probe=c0fefb30fe) | Oct 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bf2c25a350](https://linux-hardware.org/?probe=bf2c25a350) | Oct 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [09225a1f01](https://linux-hardware.org/?probe=09225a1f01) | Oct 10, 2022 |
| Apple         | MacBookPro8,1               | [36e033aa01](https://linux-hardware.org/?probe=36e033aa01) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [582de9d5d6](https://linux-hardware.org/?probe=582de9d5d6) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [f1b7cbae01](https://linux-hardware.org/?probe=f1b7cbae01) | Oct 09, 2022 |
| HP            | 340S G7                     | [7baf4edd11](https://linux-hardware.org/?probe=7baf4edd11) | Oct 09, 2022 |
| HP            | Pavilion g6                 | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| Toshiba       | Satellite L655              | [3f310e92ed](https://linux-hardware.org/?probe=3f310e92ed) | Oct 07, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2109e3f7b1](https://linux-hardware.org/?probe=2109e3f7b1) | Oct 06, 2022 |
| Toshiba       | Satellite C855-1WX          | [78c5bb7120](https://linux-hardware.org/?probe=78c5bb7120) | Oct 06, 2022 |
| HP            | Laptop 15-ra0xx             | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | [5794de3528](https://linux-hardware.org/?probe=5794de3528) | Oct 06, 2022 |
| HP            | ElitePad 1000 G2            | [ed89b0d272](https://linux-hardware.org/?probe=ed89b0d272) | Oct 05, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [bd8ce563ff](https://linux-hardware.org/?probe=bd8ce563ff) | Oct 03, 2022 |
| HUAWEI        | HVY-WXX9                    | [4ce296ba38](https://linux-hardware.org/?probe=4ce296ba38) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | [5f1d0e6142](https://linux-hardware.org/?probe=5f1d0e6142) | Sep 30, 2022 |
| Dell          | Inspiron 15-3567            | [70a80b4201](https://linux-hardware.org/?probe=70a80b4201) | Sep 30, 2022 |
| Apple         | MacBookPro15,2              | [2e6164b675](https://linux-hardware.org/?probe=2e6164b675) | Sep 28, 2022 |
| Toshiba       | QOSMIO X70-B                | [04589a6a6c](https://linux-hardware.org/?probe=04589a6a6c) | Sep 27, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [91bd22b430](https://linux-hardware.org/?probe=91bd22b430) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Dell          | Precision 7550              | [347372a20a](https://linux-hardware.org/?probe=347372a20a) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [23f17e2f91](https://linux-hardware.org/?probe=23f17e2f91) | Sep 19, 2022 |
| Dell          | Vostro 3500                 | [f114799ded](https://linux-hardware.org/?probe=f114799ded) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | [fd0bcfd41d](https://linux-hardware.org/?probe=fd0bcfd41d) | Sep 17, 2022 |
| Acer          | Aspire A515-41G             | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| HP            | EliteBook 1040 G4           | [9b4136a781](https://linux-hardware.org/?probe=9b4136a781) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [a901769629](https://linux-hardware.org/?probe=a901769629) | Sep 12, 2022 |
| ASUSTek       | N61Vn                       | [788cf883c5](https://linux-hardware.org/?probe=788cf883c5) | Sep 10, 2022 |
| Toshiba       | Satellite A200              | [ce084887f1](https://linux-hardware.org/?probe=ce084887f1) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [2f23958df0](https://linux-hardware.org/?probe=2f23958df0) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | [be18103b06](https://linux-hardware.org/?probe=be18103b06) | Sep 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [dce2728dad](https://linux-hardware.org/?probe=dce2728dad) | Sep 07, 2022 |
| HUAWEI        | KLVL-WXXW                   | [60ebd510a4](https://linux-hardware.org/?probe=60ebd510a4) | Sep 07, 2022 |
| Acer          | Swift SF314-43              | [57235f1260](https://linux-hardware.org/?probe=57235f1260) | Sep 05, 2022 |
| Acer          | Swift SF314-43              | [7d505ec2d3](https://linux-hardware.org/?probe=7d505ec2d3) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9a637495](https://linux-hardware.org/?probe=aa9a637495) | Sep 02, 2022 |
| Apple         | MacBookAir7,2               | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [7a5978071e](https://linux-hardware.org/?probe=7a5978071e) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [eb79e6b28e](https://linux-hardware.org/?probe=eb79e6b28e) | Aug 31, 2022 |
| HUAWEI        | CREF-XX                     | [4ea2674cd8](https://linux-hardware.org/?probe=4ea2674cd8) | Aug 31, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| Monster       | Huma H5 V3.2                | [ea050f24db](https://linux-hardware.org/?probe=ea050f24db) | Aug 29, 2022 |
| ASUSTek       | X542URR                     | [11867009b0](https://linux-hardware.org/?probe=11867009b0) | Aug 26, 2022 |
| ASUSTek       | X542URR                     | [909b7dcd37](https://linux-hardware.org/?probe=909b7dcd37) | Aug 26, 2022 |
| Acer          | TravelMate 5742G            | [37418dc2c7](https://linux-hardware.org/?probe=37418dc2c7) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| Timi          | TM1701                      | [4591dee526](https://linux-hardware.org/?probe=4591dee526) | Aug 21, 2022 |
| ASUSTek       | X550LN                      | [e762245df3](https://linux-hardware.org/?probe=e762245df3) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Toshiba       | QOSMIO X70-B                | [9d599f3d84](https://linux-hardware.org/?probe=9d599f3d84) | Aug 18, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| Dell          | Latitude 3510               | [97e3f5102d](https://linux-hardware.org/?probe=97e3f5102d) | Aug 15, 2022 |
| HP            | Laptop 15-da1xxx            | [dd375c139f](https://linux-hardware.org/?probe=dd375c139f) | Aug 14, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Acer          | Aspire 5732Z                | [20746ad23d](https://linux-hardware.org/?probe=20746ad23d) | Aug 09, 2022 |
| ASUSTek       | X555UB                      | [db33232b90](https://linux-hardware.org/?probe=db33232b90) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| ASUSTek       | N550JV                      | [f0c5f6a834](https://linux-hardware.org/?probe=f0c5f6a834) | Aug 07, 2022 |
| HUAWEI        | KLVD-WXX9                   | [ba034abead](https://linux-hardware.org/?probe=ba034abead) | Aug 07, 2022 |
| ASUSTek       | X555LN                      | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Monster       | ABRA A5 V13.1               | [557923ae7f](https://linux-hardware.org/?probe=557923ae7f) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| ASUSTek       | X556UQK                     | [55af061736](https://linux-hardware.org/?probe=55af061736) | Aug 05, 2022 |
| HP            | Pavilion Notebook           | [705f31df94](https://linux-hardware.org/?probe=705f31df94) | Aug 05, 2022 |
| Samsung       | NC210/NC110                 | [438dc4ea93](https://linux-hardware.org/?probe=438dc4ea93) | Aug 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [9edf66f0ec](https://linux-hardware.org/?probe=9edf66f0ec) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [06852d59ac](https://linux-hardware.org/?probe=06852d59ac) | Aug 04, 2022 |
| HUAWEI        | HVY-WXX9                    | [057187b6c9](https://linux-hardware.org/?probe=057187b6c9) | Aug 04, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| Sony          | SVE1113M1EW                 | [7a18b67232](https://linux-hardware.org/?probe=7a18b67232) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [110c94eb72](https://linux-hardware.org/?probe=110c94eb72) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [c291b32941](https://linux-hardware.org/?probe=c291b32941) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Dell          | Inspiron 14 5401            | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| Monster       | ABRA A5 V16.6               | [d26a2b3f0a](https://linux-hardware.org/?probe=d26a2b3f0a) | Jul 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [8bf5cae166](https://linux-hardware.org/?probe=8bf5cae166) | Jul 23, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f9e9de55c0](https://linux-hardware.org/?probe=f9e9de55c0) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ARCELIK       | 1S7-GNB1586B1I5             | [e9a81688b3](https://linux-hardware.org/?probe=e9a81688b3) | Jul 20, 2022 |
| ASUSTek       | X555LN                      | [f74458bf19](https://linux-hardware.org/?probe=f74458bf19) | Jul 19, 2022 |
| ASUSTek       | X555LN                      | [720cc9c1ce](https://linux-hardware.org/?probe=720cc9c1ce) | Jul 19, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [5528f26010](https://linux-hardware.org/?probe=5528f26010) | Jul 19, 2022 |
| ASUSTek       | X556UQK                     | [2ddc53797a](https://linux-hardware.org/?probe=2ddc53797a) | Jul 19, 2022 |
| Pegatron      | D15K                        | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| ASUSTek       | X553SA                      | [f28ef11fe2](https://linux-hardware.org/?probe=f28ef11fe2) | Jul 15, 2022 |
| HP            | Laptop 15-ra0xx             | [2ba7d6af57](https://linux-hardware.org/?probe=2ba7d6af57) | Jul 15, 2022 |
| Dell          | Vostro 15 3510              | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d25b4ecc69](https://linux-hardware.org/?probe=d25b4ecc69) | Jul 11, 2022 |
| Sony          | SVE1513R1EB                 | [9d74a4a9cb](https://linux-hardware.org/?probe=9d74a4a9cb) | Jul 10, 2022 |
| HUAWEI        | BOD-WXX9                    | [f4d2c6bb1e](https://linux-hardware.org/?probe=f4d2c6bb1e) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| Pegatron      | H36FF                       | [87eac99d1b](https://linux-hardware.org/?probe=87eac99d1b) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | [f852861149](https://linux-hardware.org/?probe=f852861149) | Jul 06, 2022 |
| Apple         | MacBookAir7,2               | [6b942bfd10](https://linux-hardware.org/?probe=6b942bfd10) | Jul 05, 2022 |
| ASUSTek       | G550JK                      | [ab366fcbe6](https://linux-hardware.org/?probe=ab366fcbe6) | Jul 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bcbbd7f228](https://linux-hardware.org/?probe=bcbbd7f228) | Jul 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | X553SA                      | [e3cd0aa8d4](https://linux-hardware.org/?probe=e3cd0aa8d4) | Jul 02, 2022 |
| Sony          | SVE1513R1EB                 | [d352a1c731](https://linux-hardware.org/?probe=d352a1c731) | Jul 02, 2022 |
| HUAWEI        | BOD-WXX9                    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | 340S G7                     | [6695a6a5ed](https://linux-hardware.org/?probe=6695a6a5ed) | Jun 28, 2022 |
| HUAWEI        | BOD-WXX9                    | [d306afd176](https://linux-hardware.org/?probe=d306afd176) | Jun 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [f3742fcee5](https://linux-hardware.org/?probe=f3742fcee5) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Apple         | MacBook5,1                  | [1860dff362](https://linux-hardware.org/?probe=1860dff362) | Jun 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8a530af324](https://linux-hardware.org/?probe=8a530af324) | Jun 21, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d4896fb036](https://linux-hardware.org/?probe=d4896fb036) | Jun 21, 2022 |
| Apple         | MacBook5,1                  | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| Acer          | Aspire ES1-571              | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Alienware     | m17 R3                      | [ea3305a8af](https://linux-hardware.org/?probe=ea3305a8af) | Jun 20, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [f2b6d46056](https://linux-hardware.org/?probe=f2b6d46056) | Jun 18, 2022 |
| Dell          | Inspiron N5010              | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| HUAWEI        | BOM-WXX9                    | [afc1d78a8f](https://linux-hardware.org/?probe=afc1d78a8f) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Nokia         | Booklet 3G                  | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| Dell          | Precision 7550              | [bffea13d72](https://linux-hardware.org/?probe=bffea13d72) | Jun 14, 2022 |
| Monster       | HUMA H5 V2.2                | [062a54a327](https://linux-hardware.org/?probe=062a54a327) | Jun 13, 2022 |
| HUAWEI        | BOM-WXX9                    | [f58bb7a98a](https://linux-hardware.org/?probe=f58bb7a98a) | Jun 11, 2022 |
| HUAWEI        | KLVL-WXX9                   | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Dell          | Inspiron 3542               | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| ASUSTek       | X553MA                      | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Monster       | TULPAR T7                   | [d7001b6ceb](https://linux-hardware.org/?probe=d7001b6ceb) | Jun 05, 2022 |
| Acer          | Swift SF314-41G             | [aad6ae85d1](https://linux-hardware.org/?probe=aad6ae85d1) | Jun 04, 2022 |
| ASUSTek       | N61Vg                       | [5593b63d10](https://linux-hardware.org/?probe=5593b63d10) | Jun 04, 2022 |
| Acer          | AO722                       | [73850c23ac](https://linux-hardware.org/?probe=73850c23ac) | Jun 02, 2022 |
| Monster       | ABRA A5 V15.8               | [a284d50bb9](https://linux-hardware.org/?probe=a284d50bb9) | Jun 01, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [96bc0699c3](https://linux-hardware.org/?probe=96bc0699c3) | May 28, 2022 |
| HP            | 250 G3                      | [bddc428262](https://linux-hardware.org/?probe=bddc428262) | May 28, 2022 |
| HP            | 250 G3                      | [911bf39209](https://linux-hardware.org/?probe=911bf39209) | May 28, 2022 |
| Hometech      | Alfa 430C                   | [4f0e4e240d](https://linux-hardware.org/?probe=4f0e4e240d) | May 26, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2b5ef1dbe5](https://linux-hardware.org/?probe=2b5ef1dbe5) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [647e502881](https://linux-hardware.org/?probe=647e502881) | May 25, 2022 |
| Monster       | TULPAR T5 V14.1             | [0db0bd7aa8](https://linux-hardware.org/?probe=0db0bd7aa8) | May 25, 2022 |
| Toshiba       | Satellite L40               | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [21c0d575b0](https://linux-hardware.org/?probe=21c0d575b0) | May 23, 2022 |
| Toshiba       | Satellite A100              | [a789d51565](https://linux-hardware.org/?probe=a789d51565) | May 23, 2022 |
| Dell          | Inspiron 15-3552            | [a97b4f8a75](https://linux-hardware.org/?probe=a97b4f8a75) | May 22, 2022 |
| Sony          | SVS1512U1RW                 | [491818d2e0](https://linux-hardware.org/?probe=491818d2e0) | May 18, 2022 |
| HP            | EliteBook 2570p             | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Clevo         | M540SS                      | [9860619027](https://linux-hardware.org/?probe=9860619027) | May 15, 2022 |
| Clevo         | M540SS                      | [e2fa8573fb](https://linux-hardware.org/?probe=e2fa8573fb) | May 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [0a28329f7a](https://linux-hardware.org/?probe=0a28329f7a) | May 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [ea8ce36bef](https://linux-hardware.org/?probe=ea8ce36bef) | May 12, 2022 |
| HP            | Pavilion dv6                | [9e5da14b9f](https://linux-hardware.org/?probe=9e5da14b9f) | May 11, 2022 |
| Sony          | SVE14A2V2ES                 | [59435d662a](https://linux-hardware.org/?probe=59435d662a) | May 11, 2022 |
| Sony          | SVE1513R1EB                 | [c378efbd3d](https://linux-hardware.org/?probe=c378efbd3d) | May 11, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [0e3079b5a1](https://linux-hardware.org/?probe=0e3079b5a1) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [65e46938b9](https://linux-hardware.org/?probe=65e46938b9) | May 10, 2022 |
| Acer          | AO722                       | [645156f92d](https://linux-hardware.org/?probe=645156f92d) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| HP            | Pavilion g6                 | [267b134fdd](https://linux-hardware.org/?probe=267b134fdd) | May 09, 2022 |
| HP            | Pavilion 13 x360 PC         | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8c1fedaa4b](https://linux-hardware.org/?probe=8c1fedaa4b) | May 06, 2022 |
| Vestel        | V Note 1341                 | [d5a260dc00](https://linux-hardware.org/?probe=d5a260dc00) | May 05, 2022 |
| MSI           | Prestige 15 A12UC           | [2b86e2ca60](https://linux-hardware.org/?probe=2b86e2ca60) | May 04, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| ASUSTek       | X550VC                      | [16223d208e](https://linux-hardware.org/?probe=16223d208e) | Apr 30, 2022 |
| Dell          | Latitude 7390               | [bbf3908118](https://linux-hardware.org/?probe=bbf3908118) | Apr 30, 2022 |
| Sony          | SVE1513R1EB                 | [d1e0096b2d](https://linux-hardware.org/?probe=d1e0096b2d) | Apr 29, 2022 |
| HP            | ProBook 4510s               | [d020eac67a](https://linux-hardware.org/?probe=d020eac67a) | Apr 27, 2022 |
| Apple         | MacBookAir7,2               | [17a853c8ff](https://linux-hardware.org/?probe=17a853c8ff) | Apr 27, 2022 |
| Lenovo        | ThinkPad E15 20RDS03500     | [6aa4c36808](https://linux-hardware.org/?probe=6aa4c36808) | Apr 26, 2022 |
| Sony          | SVE1513R1EB                 | [5275d17d40](https://linux-hardware.org/?probe=5275d17d40) | Apr 24, 2022 |
| Acer          | Aspire A515-56G             | [492dd679be](https://linux-hardware.org/?probe=492dd679be) | Apr 24, 2022 |
| Acer          | Aspire A515-56G             | [5fc4dbeaad](https://linux-hardware.org/?probe=5fc4dbeaad) | Apr 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce3b387afa](https://linux-hardware.org/?probe=ce3b387afa) | Apr 21, 2022 |
| Dell          | Inspiron 15-3567            | [8cbc7d1caf](https://linux-hardware.org/?probe=8cbc7d1caf) | Apr 20, 2022 |
| HP            | Laptop 15-da1xxx            | [85f9b41fe4](https://linux-hardware.org/?probe=85f9b41fe4) | Apr 19, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [dc9ac2e9b6](https://linux-hardware.org/?probe=dc9ac2e9b6) | Apr 15, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b40d10cb81](https://linux-hardware.org/?probe=b40d10cb81) | Apr 14, 2022 |
| ASUSTek       | UX310UQK                    | [5064c36f02](https://linux-hardware.org/?probe=5064c36f02) | Apr 14, 2022 |
| Monster       | ABRA A5 V15.8               | [28f1e82585](https://linux-hardware.org/?probe=28f1e82585) | Apr 13, 2022 |
| Toshiba       | Satellite L50-C             | [2366b7b28d](https://linux-hardware.org/?probe=2366b7b28d) | Apr 12, 2022 |
| Acer          | Aspire 5742G                | [b3cef97540](https://linux-hardware.org/?probe=b3cef97540) | Apr 12, 2022 |
| Acer          | Aspire E5-571               | [b6c1c28521](https://linux-hardware.org/?probe=b6c1c28521) | Apr 11, 2022 |
| Sony          | SVF1521GSTB                 | [5537b2189d](https://linux-hardware.org/?probe=5537b2189d) | Apr 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2fa2ca8320](https://linux-hardware.org/?probe=2fa2ca8320) | Apr 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b86cec3f38](https://linux-hardware.org/?probe=b86cec3f38) | Apr 10, 2022 |
| Monster       | ABRA A5 V12.1               | [4b45daf3b2](https://linux-hardware.org/?probe=4b45daf3b2) | Apr 10, 2022 |
| Lenovo        | IdeaPad-510-15IKB 80SV      | [840239190e](https://linux-hardware.org/?probe=840239190e) | Apr 09, 2022 |
| Dell          | Latitude E5440              | [18290ab7b0](https://linux-hardware.org/?probe=18290ab7b0) | Apr 08, 2022 |
| Acer          | Aspire A515-44              | [9dfd75a7dd](https://linux-hardware.org/?probe=9dfd75a7dd) | Apr 07, 2022 |
| ASUSTek       | GL752VW                     | [0dbc471fee](https://linux-hardware.org/?probe=0dbc471fee) | Apr 07, 2022 |
| ASUSTek       | K52Jc                       | [645adad8a7](https://linux-hardware.org/?probe=645adad8a7) | Apr 06, 2022 |
| Dell          | G3 3579                     | [9994b24cef](https://linux-hardware.org/?probe=9994b24cef) | Apr 06, 2022 |
| ASUSTek       | N61Vg                       | [96372fecb5](https://linux-hardware.org/?probe=96372fecb5) | Apr 05, 2022 |
| HP            | Victus by Laptop 16         | [62650f5d20](https://linux-hardware.org/?probe=62650f5d20) | Apr 04, 2022 |
| MSI           | GS75 Stealth 9SF            | [048bb1c397](https://linux-hardware.org/?probe=048bb1c397) | Apr 03, 2022 |
| MSI           | Modern 15 A5M               | [ea091854ed](https://linux-hardware.org/?probe=ea091854ed) | Apr 01, 2022 |
| MSI           | Modern 15 A5M               | [ae491737c7](https://linux-hardware.org/?probe=ae491737c7) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| ASUSTek       | N550JV                      | [6096184486](https://linux-hardware.org/?probe=6096184486) | Mar 31, 2022 |
| Apple         | MacBookAir7,2               | [d42d4a24cd](https://linux-hardware.org/?probe=d42d4a24cd) | Mar 30, 2022 |
| LG Electro... | P1-JSUVT                    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| ASUSTek       | N550JK                      | [a3ecefa43f](https://linux-hardware.org/?probe=a3ecefa43f) | Mar 26, 2022 |
| ASUSTek       | X542UR                      | [4d4477bd16](https://linux-hardware.org/?probe=4d4477bd16) | Mar 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS09Y19    | [2602549f95](https://linux-hardware.org/?probe=2602549f95) | Mar 25, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [a56ed819d1](https://linux-hardware.org/?probe=a56ed819d1) | Mar 25, 2022 |
| Unknown       | Unknown                     | [46344218a6](https://linux-hardware.org/?probe=46344218a6) | Mar 22, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [8883dc7315](https://linux-hardware.org/?probe=8883dc7315) | Mar 22, 2022 |
| Casper        | EXCALIBUR G900              | [d4902562f0](https://linux-hardware.org/?probe=d4902562f0) | Mar 21, 2022 |
| ASUSTek       | GL752VW                     | [39746d7497](https://linux-hardware.org/?probe=39746d7497) | Mar 20, 2022 |
| Apple         | MacBookPro10,1              | [6da9c9f35d](https://linux-hardware.org/?probe=6da9c9f35d) | Mar 19, 2022 |
| HP            | Pavilion g6                 | [0fe350f296](https://linux-hardware.org/?probe=0fe350f296) | Mar 19, 2022 |
| ASUSTek       | GL752VW                     | [6d64c8e4de](https://linux-hardware.org/?probe=6d64c8e4de) | Mar 19, 2022 |
| AMI           | Cherry Trail CR             | [ad3e8cb6c8](https://linux-hardware.org/?probe=ad3e8cb6c8) | Mar 19, 2022 |
| AMI           | Cherry Trail CR             | [9ad3eef70b](https://linux-hardware.org/?probe=9ad3eef70b) | Mar 19, 2022 |
| HP            | Pavilion g6                 | [d943b94c21](https://linux-hardware.org/?probe=d943b94c21) | Mar 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [591f5cdcc0](https://linux-hardware.org/?probe=591f5cdcc0) | Mar 18, 2022 |
| HP            | Pavilion g6                 | [67e332bb9f](https://linux-hardware.org/?probe=67e332bb9f) | Mar 18, 2022 |
| Dell          | XPS 13 9360                 | [962a1f764e](https://linux-hardware.org/?probe=962a1f764e) | Mar 18, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [0cd9c29dd0](https://linux-hardware.org/?probe=0cd9c29dd0) | Mar 18, 2022 |
| HP            | Victus by Laptop 16         | [cbf47a2c89](https://linux-hardware.org/?probe=cbf47a2c89) | Mar 18, 2022 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [b8fa124867](https://linux-hardware.org/?probe=b8fa124867) | Mar 17, 2022 |
| Dell          | Inspiron 5593               | [421906c2ff](https://linux-hardware.org/?probe=421906c2ff) | Mar 17, 2022 |
| Dell          | Inspiron 5593               | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [1ac160aea7](https://linux-hardware.org/?probe=1ac160aea7) | Mar 15, 2022 |
| Insyde        | i101c                       | [1d1171c005](https://linux-hardware.org/?probe=1d1171c005) | Mar 15, 2022 |
| ASUSTek       | GL502VSK                    | [f9f75e4f3d](https://linux-hardware.org/?probe=f9f75e4f3d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | [b2695cc80d](https://linux-hardware.org/?probe=b2695cc80d) | Mar 13, 2022 |
| Sony          | SVE14A2V2ES                 | [4b2203862a](https://linux-hardware.org/?probe=4b2203862a) | Mar 11, 2022 |
| Sony          | SVE14A2V2ES                 | [1575f2f0be](https://linux-hardware.org/?probe=1575f2f0be) | Mar 11, 2022 |
| Acer          | Swift SF314-42              | [160a8dd021](https://linux-hardware.org/?probe=160a8dd021) | Mar 10, 2022 |
| Acer          | AO722                       | [fc0bccc42d](https://linux-hardware.org/?probe=fc0bccc42d) | Mar 09, 2022 |
| Sony          | SVE14A2V2ES                 | [ef603529f2](https://linux-hardware.org/?probe=ef603529f2) | Mar 08, 2022 |
| Unknown       | Unknown                     | [3e6993a459](https://linux-hardware.org/?probe=3e6993a459) | Mar 08, 2022 |
| Sony          | SVE14A2V2ES                 | [35fe0c18bc](https://linux-hardware.org/?probe=35fe0c18bc) | Mar 07, 2022 |
| ASUSTek       | UX31E                       | [2b8b852d07](https://linux-hardware.org/?probe=2b8b852d07) | Mar 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e60367127e](https://linux-hardware.org/?probe=e60367127e) | Mar 07, 2022 |
| HP            | Notebook                    | [a15666c682](https://linux-hardware.org/?probe=a15666c682) | Mar 07, 2022 |
| HP            | Notebook                    | [85eb96edd4](https://linux-hardware.org/?probe=85eb96edd4) | Mar 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [0456c09970](https://linux-hardware.org/?probe=0456c09970) | Mar 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [d3b3f1e5d2](https://linux-hardware.org/?probe=d3b3f1e5d2) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d09a669d80](https://linux-hardware.org/?probe=d09a669d80) | Mar 03, 2022 |
| Clevo         | E512xQ/E4129                | [7aff97f14f](https://linux-hardware.org/?probe=7aff97f14f) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [65a9b832d2](https://linux-hardware.org/?probe=65a9b832d2) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [738744d850](https://linux-hardware.org/?probe=738744d850) | Mar 01, 2022 |
| Clevo         | M540SS                      | [50fafbe5e8](https://linux-hardware.org/?probe=50fafbe5e8) | Mar 01, 2022 |
| ASUSTek       | UX303UB                     | [f62c829839](https://linux-hardware.org/?probe=f62c829839) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [60d1c44981](https://linux-hardware.org/?probe=60d1c44981) | Feb 28, 2022 |
| ASUSTek       | X556UQK                     | [9c482a1888](https://linux-hardware.org/?probe=9c482a1888) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| Dell          | Latitude E5440              | [9e496b4990](https://linux-hardware.org/?probe=9e496b4990) | Feb 27, 2022 |
| ASUSTek       | UX490UAR                    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| ASUSTek       | X510UNR                     | [a24f9785ac](https://linux-hardware.org/?probe=a24f9785ac) | Feb 25, 2022 |
| Monster       | ABRA A5 V16.6               | [61707e5a4b](https://linux-hardware.org/?probe=61707e5a4b) | Feb 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [baa1d24da5](https://linux-hardware.org/?probe=baa1d24da5) | Feb 24, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| Dell          | Inspiron 15-3567            | [c8723d2dd9](https://linux-hardware.org/?probe=c8723d2dd9) | Feb 21, 2022 |
| Dell          | Inspiron 15-3567            | [45529bb469](https://linux-hardware.org/?probe=45529bb469) | Feb 21, 2022 |
| HP            | Pavilion g6                 | [d894476c06](https://linux-hardware.org/?probe=d894476c06) | Feb 21, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [3a8cec53c9](https://linux-hardware.org/?probe=3a8cec53c9) | Feb 20, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [cd97a5dfb4](https://linux-hardware.org/?probe=cd97a5dfb4) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [298655060c](https://linux-hardware.org/?probe=298655060c) | Feb 18, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [f988c3bfdc](https://linux-hardware.org/?probe=f988c3bfdc) | Feb 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [c4b7901caa](https://linux-hardware.org/?probe=c4b7901caa) | Feb 18, 2022 |
| Dell          | Precision 5530              | [5650039a15](https://linux-hardware.org/?probe=5650039a15) | Feb 18, 2022 |
| ASUSTek       | X55A                        | [1ed422d0e2](https://linux-hardware.org/?probe=1ed422d0e2) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [1fa5e259f5](https://linux-hardware.org/?probe=1fa5e259f5) | Feb 16, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [92ccebcc90](https://linux-hardware.org/?probe=92ccebcc90) | Feb 16, 2022 |
| Apple         | MacBookPro16,3              | [ee62794632](https://linux-hardware.org/?probe=ee62794632) | Feb 16, 2022 |
| Apple         | MacBookPro16,3              | [a651af2ee1](https://linux-hardware.org/?probe=a651af2ee1) | Feb 15, 2022 |
| Sony          | SVF1521QSTB                 | [f74068fef9](https://linux-hardware.org/?probe=f74068fef9) | Feb 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2289e255e7](https://linux-hardware.org/?probe=2289e255e7) | Feb 13, 2022 |
| ASUSTek       | ZenBook UX334FLC_UX334FL    | [d74ad9fc94](https://linux-hardware.org/?probe=d74ad9fc94) | Feb 13, 2022 |
| MSI           | PL62 7RC                    | [1cba3daad7](https://linux-hardware.org/?probe=1cba3daad7) | Feb 13, 2022 |
| HP            | Pavilion 15                 | [fe001e576b](https://linux-hardware.org/?probe=fe001e576b) | Feb 13, 2022 |
| Dell          | Inspiron N5110              | [a87e7380d9](https://linux-hardware.org/?probe=a87e7380d9) | Feb 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| HP            | ProBook 4510s               | [1ec304f4f6](https://linux-hardware.org/?probe=1ec304f4f6) | Feb 10, 2022 |
| Sony          | SVE1711V1EB                 | [28da9a136f](https://linux-hardware.org/?probe=28da9a136f) | Feb 10, 2022 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [30b9a925de](https://linux-hardware.org/?probe=30b9a925de) | Feb 10, 2022 |
| Sony          | SVE1711V1EB                 | [ce823abe6e](https://linux-hardware.org/?probe=ce823abe6e) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Acer          | VAG70_HC                    | [89df31dc20](https://linux-hardware.org/?probe=89df31dc20) | Feb 09, 2022 |
| Dell          | Inspiron 3542               | [f3f3b08d89](https://linux-hardware.org/?probe=f3f3b08d89) | Feb 09, 2022 |
| HP            | Pavilion 15                 | [5de6e1ed8f](https://linux-hardware.org/?probe=5de6e1ed8f) | Feb 08, 2022 |
| Acer          | Aspire A315-41G             | [84a6cc3fad](https://linux-hardware.org/?probe=84a6cc3fad) | Feb 08, 2022 |
| Acer          | Nitro AN515-51              | [1308425490](https://linux-hardware.org/?probe=1308425490) | Feb 08, 2022 |
| Lenovo        | Yoga 500-14IBD 80N4         | [277f7ae4fd](https://linux-hardware.org/?probe=277f7ae4fd) | Feb 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [b4cfe297d4](https://linux-hardware.org/?probe=b4cfe297d4) | Feb 08, 2022 |
| Lenovo        | ThinkPad X230 23257R2       | [4fa07e0a61](https://linux-hardware.org/?probe=4fa07e0a61) | Feb 08, 2022 |
| Acer          | Aspire A315-41G             | [370a0709e9](https://linux-hardware.org/?probe=370a0709e9) | Feb 07, 2022 |
| HUAWEI        | KLVL-WXX9                   | [837b0e80ef](https://linux-hardware.org/?probe=837b0e80ef) | Feb 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [aec471416a](https://linux-hardware.org/?probe=aec471416a) | Feb 07, 2022 |
| Fujitsu       | LIFEBOOK A544               | [0892485b4b](https://linux-hardware.org/?probe=0892485b4b) | Feb 07, 2022 |
| HP            | Notebook                    | [69071da574](https://linux-hardware.org/?probe=69071da574) | Feb 06, 2022 |
| HP            | Compaq 6730s                | [8d1fa47bb0](https://linux-hardware.org/?probe=8d1fa47bb0) | Feb 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [4b20e9f979](https://linux-hardware.org/?probe=4b20e9f979) | Feb 04, 2022 |
| MSI           | GF63 Thin 9SC               | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [2c3e69a6d2](https://linux-hardware.org/?probe=2c3e69a6d2) | Feb 04, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [cbb1e33af4](https://linux-hardware.org/?probe=cbb1e33af4) | Feb 03, 2022 |
| Toshiba       | Satellite L50-B             | [3fde135a0c](https://linux-hardware.org/?probe=3fde135a0c) | Feb 03, 2022 |
| Toshiba       | Satellite L50-B             | [28c4fcaddd](https://linux-hardware.org/?probe=28c4fcaddd) | Feb 03, 2022 |
| Casper        | EXCALIBUR G860              | [dfa7d6bf8c](https://linux-hardware.org/?probe=dfa7d6bf8c) | Feb 03, 2022 |
| Dell          | Inspiron 7577               | [9ab100b85c](https://linux-hardware.org/?probe=9ab100b85c) | Feb 02, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e14121100b](https://linux-hardware.org/?probe=e14121100b) | Feb 02, 2022 |
| Insyde        | i101c                       | [375f7e61b2](https://linux-hardware.org/?probe=375f7e61b2) | Feb 02, 2022 |
| ASUSTek       | X555UB                      | [b12edb18d5](https://linux-hardware.org/?probe=b12edb18d5) | Feb 01, 2022 |
| Packard Be... | EasyNote ENTG81BA           | [10f68b4c82](https://linux-hardware.org/?probe=10f68b4c82) | Jan 31, 2022 |
| Dell          | Inspiron 3542               | [e975782c15](https://linux-hardware.org/?probe=e975782c15) | Jan 31, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [051abf292f](https://linux-hardware.org/?probe=051abf292f) | Jan 30, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4d4ffcb92f](https://linux-hardware.org/?probe=4d4ffcb92f) | Jan 30, 2022 |
| Casper        | EXCALIBUR G860              | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| HP            | Pavilion g7                 | [02214b67ab](https://linux-hardware.org/?probe=02214b67ab) | Jan 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [0316d10862](https://linux-hardware.org/?probe=0316d10862) | Jan 29, 2022 |
| ASUSTek       | TAICHI21                    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| Unknown       | ASUS Google Nexus 7 (Pro... | [b51e5807f8](https://linux-hardware.org/?probe=b51e5807f8) | Jan 28, 2022 |
| HP            | Pavilion g7                 | [64f1eb2dbe](https://linux-hardware.org/?probe=64f1eb2dbe) | Jan 28, 2022 |
| Monster       | HUMA H4 V4.1                | [5d7886a578](https://linux-hardware.org/?probe=5d7886a578) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| ASUSTek       | X555LN                      | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| ASUSTek       | X510UNR                     | [89bbc4800a](https://linux-hardware.org/?probe=89bbc4800a) | Jan 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [08deab0e09](https://linux-hardware.org/?probe=08deab0e09) | Jan 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [a6d89f6ae1](https://linux-hardware.org/?probe=a6d89f6ae1) | Jan 21, 2022 |
| HP            | Notebook                    | [782c51f796](https://linux-hardware.org/?probe=782c51f796) | Jan 17, 2022 |
| Apple         | MacBookPro16,2              | [f02e2c390e](https://linux-hardware.org/?probe=f02e2c390e) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [7345361fc2](https://linux-hardware.org/?probe=7345361fc2) | Jan 16, 2022 |
| Dell          | Latitude 5480               | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| ASUSTek       | X550VX                      | [96b0a9dbdc](https://linux-hardware.org/?probe=96b0a9dbdc) | Jan 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a9f451830b](https://linux-hardware.org/?probe=a9f451830b) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [13ba6fba7f](https://linux-hardware.org/?probe=13ba6fba7f) | Jan 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [51586040b8](https://linux-hardware.org/?probe=51586040b8) | Jan 08, 2022 |
| Packard Be... | EasyNote TK85               | [5cd2548a30](https://linux-hardware.org/?probe=5cd2548a30) | Jan 07, 2022 |
| Packard Be... | EasyNote TK85               | [5e77633e52](https://linux-hardware.org/?probe=5e77633e52) | Jan 07, 2022 |
| Lenovo        | S145-15API 81UT             | [74b342a9fe](https://linux-hardware.org/?probe=74b342a9fe) | Jan 07, 2022 |
| Lenovo        | S145-15API 81UT             | [ed7ca5bcb0](https://linux-hardware.org/?probe=ed7ca5bcb0) | Jan 07, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8a3b6c72a9](https://linux-hardware.org/?probe=8a3b6c72a9) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| MSI           | Modern 15 A5M               | [1a46d371ef](https://linux-hardware.org/?probe=1a46d371ef) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| Lenovo        | V145-15AST 81MT             | [121a750c5b](https://linux-hardware.org/?probe=121a750c5b) | Jan 03, 2022 |
| Monster       | ABRA A5 V11.1               | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| ASUSTek       | X550VX                      | [768a6d9805](https://linux-hardware.org/?probe=768a6d9805) | Jan 01, 2022 |
| Dell          | G3 3500                     | [0852686847](https://linux-hardware.org/?probe=0852686847) | Dec 31, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | [57a3728f0d](https://linux-hardware.org/?probe=57a3728f0d) | Dec 29, 2021 |
| HP            | Pavilion 13 x360 PC         | [1db92ff50e](https://linux-hardware.org/?probe=1db92ff50e) | Dec 29, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [6a4ffab5ad](https://linux-hardware.org/?probe=6a4ffab5ad) | Dec 27, 2021 |
| Acer          | Aspire A315-34              | [feb833c87a](https://linux-hardware.org/?probe=feb833c87a) | Dec 27, 2021 |
| MSI           | Delta 15 A5EFK              | [e874b85848](https://linux-hardware.org/?probe=e874b85848) | Dec 26, 2021 |
| Monster       | ABRA A5 V11.1               | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| Schenker      | XMG CORE 15(M20, RTX 206... | [f4c47d6284](https://linux-hardware.org/?probe=f4c47d6284) | Dec 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [a53f185048](https://linux-hardware.org/?probe=a53f185048) | Dec 22, 2021 |
| I-Life Dig... | ZED AIR                     | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| HUAWEI        | HVY-WXX9                    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Monster       | MARKUT M7 V1.x              | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [16efe9685d](https://linux-hardware.org/?probe=16efe9685d) | Dec 17, 2021 |
| Sony          | SVF1521L6EW                 | [64160de19b](https://linux-hardware.org/?probe=64160de19b) | Dec 17, 2021 |
| Toshiba       | Satellite C50-B             | [2c70113bf8](https://linux-hardware.org/?probe=2c70113bf8) | Dec 16, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [21ea8cfa3b](https://linux-hardware.org/?probe=21ea8cfa3b) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| Lenovo        | G580 20150                  | [6ff1581ca6](https://linux-hardware.org/?probe=6ff1581ca6) | Dec 14, 2021 |
| ASUSTek       | X550VX                      | [86609a281d](https://linux-hardware.org/?probe=86609a281d) | Dec 13, 2021 |
| Acer          | TravelMate 5730             | [874aa641a7](https://linux-hardware.org/?probe=874aa641a7) | Dec 12, 2021 |
| Sony          | VGN-NR430E                  | [305865a785](https://linux-hardware.org/?probe=305865a785) | Dec 12, 2021 |
| Sony          | VGN-NR430E                  | [3ca106703d](https://linux-hardware.org/?probe=3ca106703d) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b328ed77b4](https://linux-hardware.org/?probe=b328ed77b4) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [db73d74107](https://linux-hardware.org/?probe=db73d74107) | Dec 07, 2021 |
| Dell          | Latitude E7440              | [bb71f679cf](https://linux-hardware.org/?probe=bb71f679cf) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [cd47b9ae21](https://linux-hardware.org/?probe=cd47b9ae21) | Dec 05, 2021 |
| ASUSTek       | X200MA                      | [2d2f3a474e](https://linux-hardware.org/?probe=2d2f3a474e) | Dec 05, 2021 |
| HP            | Compaq 6510b (GR691EA#AB... | [4d657211eb](https://linux-hardware.org/?probe=4d657211eb) | Dec 04, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Pegatron      | D15K                        | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| HUAWEI        | HVY-WXX9                    | [af5cb748c4](https://linux-hardware.org/?probe=af5cb748c4) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5410966f9e](https://linux-hardware.org/?probe=5410966f9e) | Nov 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e5179d69bf](https://linux-hardware.org/?probe=e5179d69bf) | Nov 25, 2021 |
| I-Life Dig... | ZED AIR                     | [3d7ed5f519](https://linux-hardware.org/?probe=3d7ed5f519) | Nov 24, 2021 |
| I-Life Dig... | ZED AIR                     | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Lenovo        | G580 20150                  | [baade6ba54](https://linux-hardware.org/?probe=baade6ba54) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | [b7718027af](https://linux-hardware.org/?probe=b7718027af) | Nov 22, 2021 |
| Gigabyte      | AERO 15 KD                  | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [7443e6aedb](https://linux-hardware.org/?probe=7443e6aedb) | Nov 21, 2021 |
| HP            | Pavilion Notebook           | [ca1ccc6e65](https://linux-hardware.org/?probe=ca1ccc6e65) | Nov 20, 2021 |
| Dell          | Vostro 3500                 | [442f6acee6](https://linux-hardware.org/?probe=442f6acee6) | Nov 20, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Turkey/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 163       | 11.65%  |
| Ubuntu 18.04                 | 116       | 8.29%   |
| Ubuntu 22.04                 | 88        | 6.29%   |
| Arch Rolling                 | 32        | 2.29%   |
| Fedora 37                    | 28        | 2%      |
| Debian 11                    | 28        | 2%      |
| Fedora 36                    | 27        | 1.93%   |
| Fedora 38                    | 26        | 1.86%   |
| ArcoLinux Rolling            | 26        | 1.86%   |
| Arch                         | 26        | 1.86%   |
| OpenMandriva 4.3             | 24        | 1.72%   |
| Pop!_OS 22.04                | 22        | 1.57%   |
| Manjaro                      | 22        | 1.57%   |
| Zorin 16                     | 20        | 1.43%   |
| Linux Mint 21.1              | 19        | 1.36%   |
| Fedora 33                    | 18        | 1.29%   |
| EndeavourOS Rolling          | 18        | 1.29%   |
| Ubuntu 21.10                 | 16        | 1.14%   |
| OpenMandriva 23.01           | 16        | 1.14%   |
| Fedora 35                    | 16        | 1.14%   |
| Linux Mint 20.3              | 14        | 1%      |
| KDE neon 20.04               | 13        | 0.93%   |
| Fedora 34                    | 13        | 0.93%   |
| Elementary 6.1               | 13        | 0.93%   |
| Linux Mint 20.2              | 12        | 0.86%   |
| Linux Mint 20.1              | 12        | 0.86%   |
| Ubuntu 22.10                 | 11        | 0.79%   |
| Ubuntu 21.04                 | 11        | 0.79%   |
| Linux Mint 21                | 11        | 0.79%   |
| Linux Mint 20                | 11        | 0.79%   |
| Zorin 15                     | 10        | 0.71%   |
| ROSA R10                     | 10        | 0.71%   |
| Pop!_OS 21.10                | 10        | 0.71%   |
| Linux Mint 19.3              | 10        | 0.71%   |
| Ubuntu Unity 16.04           | 9         | 0.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 0.64%   |
| Debian 12                    | 9         | 0.64%   |
| Xubuntu 20.04                | 8         | 0.57%   |
| Ubuntu 23.04                 | 8         | 0.57%   |
| Ubuntu 20.10                 | 8         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 434       | 32.63%  |
| Fedora        | 119       | 8.95%   |
| Linux Mint    | 101       | 7.59%   |
| OpenMandriva  | 58        | 4.36%   |
| Arch          | 57        | 4.29%   |
| Debian        | 54        | 4.06%   |
| Pop!_OS       | 49        | 3.68%   |
| Manjaro       | 48        | 3.61%   |
| Pardus        | 33        | 2.48%   |
| Zorin         | 31        | 2.33%   |
| ArcoLinux     | 29        | 2.18%   |
| Kubuntu       | 25        | 1.88%   |
| Kali          | 25        | 1.88%   |
| ROSA          | 22        | 1.65%   |
| KDE neon      | 21        | 1.58%   |
| Elementary    | 21        | 1.58%   |
| EndeavourOS   | 19        | 1.43%   |
| Endless       | 18        | 1.35%   |
| Xubuntu       | 17        | 1.28%   |
| Lubuntu       | 13        | 0.98%   |
| Ubuntu MATE   | 11        | 0.83%   |
| openSUSE      | 11        | 0.83%   |
| Gentoo        | 11        | 0.83%   |
| Ubuntu Unity  | 10        | 0.75%   |
| Clear Linux   | 7         | 0.53%   |
| Garuda Linux  | 6         | 0.45%   |
| Xero          | 5         | 0.38%   |
| PostmarketOS  | 5         | 0.38%   |
| LMDE          | 5         | 0.38%   |
| Deepin        | 5         | 0.38%   |
| Artix         | 5         | 0.38%   |
| Parrot        | 4         | 0.3%    |
| MX            | 4         | 0.3%    |
| Archman       | 4         | 0.3%    |
| Ubuntu Budgie | 3         | 0.23%   |
| SteamOS       | 3         | 0.23%   |
| Nobara        | 3         | 0.23%   |
| Void Linux    | 2         | 0.15%   |
| Solus         | 2         | 0.15%   |
| RHEL          | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003 | 23        | 1.52%   |
| 5.4.0-58-generic        | 18        | 1.19%   |
| 6.1.1-desktop-1omv2290  | 16        | 1.06%   |
| 5.4.0-42-generic        | 16        | 1.06%   |
| 5.15.0-58-generic       | 16        | 1.06%   |
| 5.3.0-40-generic        | 12        | 0.79%   |
| 5.15.0-56-generic       | 12        | 0.79%   |
| 5.15.0-52-generic       | 11        | 0.73%   |
| 6.2.0-26-generic        | 10        | 0.66%   |
| 5.15.0-43-generic       | 10        | 0.66%   |
| 5.4.0-37-generic        | 9         | 0.6%    |
| 5.4.0-26-generic        | 9         | 0.6%    |
| 5.19.0-32-generic       | 9         | 0.6%    |
| 5.0.0-37-generic        | 9         | 0.6%    |
| 5.4.0-74-generic        | 8         | 0.53%   |
| 5.4.0-48-generic        | 8         | 0.53%   |
| 5.4.0-47-generic        | 8         | 0.53%   |
| 5.3.0-28-generic        | 8         | 0.53%   |
| 5.15.0-48-generic       | 8         | 0.53%   |
| 5.15.0-46-generic       | 8         | 0.53%   |
| 5.13.0-30-generic       | 8         | 0.53%   |
| 5.13.0-28-generic       | 8         | 0.53%   |
| 4.18.0-15-generic       | 8         | 0.53%   |
| 5.8.0-44-generic        | 7         | 0.46%   |
| 5.8.0-14-generic        | 7         | 0.46%   |
| 5.19.0-35-generic       | 7         | 0.46%   |
| 5.15.0-53-generic       | 7         | 0.46%   |
| 5.15.0-47-generic       | 7         | 0.46%   |
| 5.15.0-27-generic       | 7         | 0.46%   |
| 5.13.0-39-generic       | 7         | 0.46%   |
| 5.11.0-27-generic       | 7         | 0.46%   |
| 5.10.0-21-amd64         | 7         | 0.46%   |
| 4.18.0-25-generic       | 7         | 0.46%   |
| 6.2.6-desktop-1omv2390  | 6         | 0.4%    |
| 6.2.6-76060206-generic  | 6         | 0.4%    |
| 6.2.0-20-generic        | 6         | 0.4%    |
| 5.8.0-63-generic        | 6         | 0.4%    |
| 5.4.0-73-generic        | 6         | 0.4%    |
| 5.4.0-65-generic        | 6         | 0.4%    |
| 5.4.0-54-generic        | 6         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 197       | 13.61%  |
| 5.15.0  | 130       | 8.98%   |
| 4.15.0  | 62        | 4.28%   |
| 5.8.0   | 61        | 4.22%   |
| 5.11.0  | 61        | 4.22%   |
| 5.10.0  | 61        | 4.22%   |
| 5.13.0  | 52        | 3.59%   |
| 5.3.0   | 49        | 3.39%   |
| 5.19.0  | 45        | 3.11%   |
| 5.0.0   | 38        | 2.63%   |
| 4.18.0  | 31        | 2.14%   |
| 6.2.0   | 26        | 1.8%    |
| 5.16.7  | 25        | 1.73%   |
| 6.1.0   | 19        | 1.31%   |
| 6.1.1   | 18        | 1.24%   |
| 6.2.6   | 16        | 1.11%   |
| 4.19.0  | 16        | 1.11%   |
| 6.0.12  | 11        | 0.76%   |
| 6.4.12  | 10        | 0.69%   |
| 5.17.5  | 9         | 0.62%   |
| 5.6.0   | 7         | 0.48%   |
| 5.17.1  | 7         | 0.48%   |
| 5.14.0  | 7         | 0.48%   |
| 6.4.6   | 6         | 0.41%   |
| 6.4.11  | 6         | 0.41%   |
| 6.3.8   | 6         | 0.41%   |
| 5.10.14 | 6         | 0.41%   |
| 4.9.60  | 6         | 0.41%   |
| 6.2.9   | 5         | 0.35%   |
| 6.2.8   | 5         | 0.35%   |
| 6.0.8   | 5         | 0.35%   |
| 6.0.2   | 5         | 0.35%   |
| 5.18.13 | 5         | 0.35%   |
| 5.11.11 | 5         | 0.35%   |
| 6.2.12  | 4         | 0.28%   |
| 6.2.10  | 4         | 0.28%   |
| 5.9.16  | 4         | 0.28%   |
| 5.7.0   | 4         | 0.28%   |
| 5.18.0  | 4         | 0.28%   |
| 5.16.0  | 4         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 211       | 14.91%  |
| 5.15    | 175       | 12.37%  |
| 5.10    | 93        | 6.57%   |
| 5.11    | 81        | 5.72%   |
| 5.8     | 73        | 5.16%   |
| 6.1     | 71        | 5.02%   |
| 6.2     | 70        | 4.95%   |
| 5.13    | 64        | 4.52%   |
| 4.15    | 62        | 4.38%   |
| 5.19    | 58        | 4.1%    |
| 5.3     | 54        | 3.82%   |
| 5.16    | 51        | 3.6%    |
| 6.0     | 43        | 3.04%   |
| 5.0     | 40        | 2.83%   |
| 6.4     | 36        | 2.54%   |
| 4.18    | 32        | 2.26%   |
| 5.17    | 26        | 1.84%   |
| 5.18    | 25        | 1.77%   |
| 6.3     | 24        | 1.7%    |
| 5.9     | 23        | 1.63%   |
| 4.19    | 16        | 1.13%   |
| 5.14    | 15        | 1.06%   |
| 4.9     | 15        | 1.06%   |
| 5.12    | 13        | 0.92%   |
| 5.7     | 12        | 0.85%   |
| 5.6     | 12        | 0.85%   |
| 5.5     | 4         | 0.28%   |
| 5.2     | 4         | 0.28%   |
| 5.1     | 4         | 0.28%   |
| 4.4     | 2         | 0.14%   |
| 6.5     | 1         | 0.07%   |
| 6.0.5   | 1         | 0.07%   |
| 4.16    | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 4.10    | 1         | 0.07%   |
| 4.1     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1216      | 96.66%  |
| i686    | 35        | 2.78%   |
| armv7l  | 5         | 0.4%    |
| aarch64 | 2         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 613       | 46.4%   |
| KDE5             | 193       | 14.61%  |
| Unknown          | 144       | 10.9%   |
| XFCE             | 133       | 10.07%  |
| X-Cinnamon       | 69        | 5.22%   |
| MATE             | 32        | 2.42%   |
| KDE              | 22        | 1.67%   |
| Pantheon         | 21        | 1.59%   |
| LXQt             | 14        | 1.06%   |
| KDE4             | 12        | 0.91%   |
| Cinnamon         | 11        | 0.83%   |
| Unity            | 10        | 0.76%   |
| i3               | 9         | 0.68%   |
| LXDE             | 8         | 0.61%   |
| sway             | 5         | 0.38%   |
| Deepin           | 4         | 0.3%    |
| Trinity          | 3         | 0.23%   |
| Hyprland         | 3         | 0.23%   |
| DWM              | 3         | 0.23%   |
| Budgie           | 3         | 0.23%   |
| bspwm            | 2         | 0.15%   |
| xmonad           | 1         | 0.08%   |
| qtile            | 1         | 0.08%   |
| openbox          | 1         | 0.08%   |
| lightdm-xsession | 1         | 0.08%   |
| GNOME Flashback  | 1         | 0.08%   |
| GNOME Classic    | 1         | 0.08%   |
| awesome          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 963       | 74.08%  |
| Wayland | 259       | 19.92%  |
| Unknown | 62        | 4.77%   |
| Tty     | 16        | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 626       | 47.1%   |
| GDM     | 187       | 14.07%  |
| SDDM    | 166       | 12.49%  |
| GDM3    | 155       | 11.66%  |
| LightDM | 130       | 9.78%   |
| TDM     | 48        | 3.61%   |
| KDM     | 12        | 0.9%    |
| XDM     | 2         | 0.15%   |
| SLiM    | 1         | 0.08%   |
| Ly      | 1         | 0.08%   |
| LXDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 591       | 46.14%  |
| tr_TR       | 466       | 36.38%  |
| Unknown     | 132       | 10.3%   |
| en_GB       | 35        | 2.73%   |
| C           | 19        | 1.48%   |
| ru_RU       | 14        | 1.09%   |
| de_DE       | 4         | 0.31%   |
| POSIX       | 2         | 0.16%   |
| ar_EG       | 2         | 0.16%   |
| zh_CN       | 1         | 0.08%   |
| tr_TR.UTF8  | 1         | 0.08%   |
| tr_CY       | 1         | 0.08%   |
| ru_UA       | 1         | 0.08%   |
| nl_BE       | 1         | 0.08%   |
| fr_FR       | 1         | 0.08%   |
| fa_IR       | 1         | 0.08%   |
| en_US.UTF8  | 1         | 0.08%   |
| en_US-UTF-8 | 1         | 0.08%   |
| en_NZ       | 1         | 0.08%   |
| en_IE       | 1         | 0.08%   |
| en_GB.UTF8  | 1         | 0.08%   |
| en_DK       | 1         | 0.08%   |
| en_CA       | 1         | 0.08%   |
| en_150      | 1         | 0.08%   |
| de_AT       | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 730       | 56.63%  |
| BIOS | 559       | 43.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 968       | 74.58%  |
| Btrfs   | 161       | 12.4%   |
| Overlay | 75        | 5.78%   |
| Unknown | 36        | 2.77%   |
| Tmpfs   | 19        | 1.46%   |
| Xfs     | 14        | 1.08%   |
| Ext2    | 11        | 0.85%   |
| Zfs     | 8         | 0.62%   |
| F2fs    | 2         | 0.15%   |
| Ext3    | 2         | 0.15%   |
| Aufs    | 2         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 666       | 51.35%  |
| GPT     | 516       | 39.78%  |
| MBR     | 115       | 8.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1124      | 87.74%  |
| Yes       | 157       | 12.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 864       | 66.98%  |
| Yes       | 426       | 33.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 247       | 19.65%  |
| Hewlett-Packard             | 205       | 16.31%  |
| ASUSTek Computer            | 165       | 13.13%  |
| Dell                        | 126       | 10.02%  |
| Acer                        | 98        | 7.8%    |
| Monster                     | 56        | 4.46%   |
| Toshiba                     | 52        | 4.14%   |
| HUAWEI                      | 41        | 3.26%   |
| MSI                         | 37        | 2.94%   |
| Apple                       | 33        | 2.63%   |
| Samsung Electronics         | 32        | 2.55%   |
| Sony                        | 30        | 2.39%   |
| Casper                      | 23        | 1.83%   |
| Packard Bell                | 17        | 1.35%   |
| Clevo                       | 11        | 0.88%   |
| Pegatron                    | 10        | 0.8%    |
| Unknown                     | 10        | 0.8%    |
| Hometech                    | 9         | 0.72%   |
| Google                      | 6         | 0.48%   |
| ARCELIK                     | 5         | 0.4%    |
| Notebook                    | 4         | 0.32%   |
| Alienware                   | 4         | 0.32%   |
| Fujitsu                     | 3         | 0.24%   |
| Valve                       | 2         | 0.16%   |
| Quanta                      | 2         | 0.16%   |
| Medion                      | 2         | 0.16%   |
| LG Electronics              | 2         | 0.16%   |
| Intel                       | 2         | 0.16%   |
| Insyde                      | 2         | 0.16%   |
| I-Life Digital Technologies | 2         | 0.16%   |
| HT                          | 2         | 0.16%   |
| HONOR                       | 2         | 0.16%   |
| Vestel                      | 1         | 0.08%   |
| Timi                        | 1         | 0.08%   |
| System76                    | 1         | 0.08%   |
| Schenker                    | 1         | 0.08%   |
| Razer                       | 1         | 0.08%   |
| Pine Microsystems           | 1         | 0.08%   |
| ODM                         | 1         | 0.08%   |
| Nokia                       | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Pavilion g6                       | 20        | 1.59%   |
| Unknown                              | 17        | 1.35%   |
| HP Pavilion dv6                      | 9         | 0.72%   |
| Casper NIRVANA NOTEBOOK              | 9         | 0.72%   |
| HP Notebook                          | 8         | 0.64%   |
| HP Pavilion 15                       | 7         | 0.56%   |
| HP 15                                | 7         | 0.56%   |
| ASUS X550VX                          | 7         | 0.56%   |
| HUAWEI BOD-WXX9                      | 6         | 0.48%   |
| Acer Aspire 5750G                    | 6         | 0.48%   |
| Lenovo V15 G2 ALC 82KD               | 5         | 0.4%    |
| HUAWEI NBLK-WAX9X                    | 5         | 0.4%    |
| HUAWEI KLVL-WXX9                     | 5         | 0.4%    |
| HUAWEI BOHK-WAX9X                    | 5         | 0.4%    |
| HP Pavilion Notebook                 | 5         | 0.4%    |
| HP 250 G3                            | 5         | 0.4%    |
| Dell Inspiron 7577                   | 5         | 0.4%    |
| Dell Inspiron 3542                   | 5         | 0.4%    |
| Casper EXCALIBUR G770                | 5         | 0.4%    |
| ASUS X555UB                          | 5         | 0.4%    |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 5         | 0.4%    |
| ASUS N550JV                          | 5         | 0.4%    |
| Apple MacBookAir7,2                  | 5         | 0.4%    |
| Acer Nitro AN515-58                  | 5         | 0.4%    |
| Toshiba Satellite L655               | 4         | 0.32%   |
| Lenovo Legion Y530-15ICH 81FV        | 4         | 0.32%   |
| Lenovo IdeaPad S145-15API 81UT       | 4         | 0.32%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 4         | 0.32%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 4         | 0.32%   |
| HP Pavilion Gaming Laptop 15-cx0xxx  | 4         | 0.32%   |
| HP G62                               | 4         | 0.32%   |
| HP ElitePad 1000 G2                  | 4         | 0.32%   |
| Dell Inspiron MM061                  | 4         | 0.32%   |
| Dell Inspiron 3580                   | 4         | 0.32%   |
| Dell G3 3500                         | 4         | 0.32%   |
| ASUS X556UQK                         | 4         | 0.32%   |
| ASUS X542URR                         | 4         | 0.32%   |
| Toshiba Satellite R630               | 3         | 0.24%   |
| Toshiba Satellite C650               | 3         | 0.24%   |
| Toshiba Satellite A300               | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 98        | 7.8%    |
| HP Pavilion           | 67        | 5.33%   |
| Lenovo IdeaPad        | 65        | 5.17%   |
| Dell Inspiron         | 59        | 4.69%   |
| Acer Aspire           | 56        | 4.46%   |
| Toshiba Satellite     | 48        | 3.82%   |
| Dell Latitude         | 30        | 2.39%   |
| Monster ABRA          | 29        | 2.31%   |
| HP Laptop             | 28        | 2.23%   |
| ASUS VivoBook         | 24        | 1.91%   |
| HP ProBook            | 20        | 1.59%   |
| HP EliteBook          | 20        | 1.59%   |
| Unknown               | 17        | 1.35%   |
| Packard Bell EasyNote | 16        | 1.27%   |
| Monster TULPAR        | 16        | 1.27%   |
| Acer Nitro            | 15        | 1.19%   |
| HP 250                | 14        | 1.11%   |
| Lenovo Legion         | 13        | 1.03%   |
| Dell Vostro           | 12        | 0.95%   |
| Casper NIRVANA        | 12        | 0.95%   |
| Monster HUMA          | 10        | 0.8%    |
| Acer Swift            | 10        | 0.8%    |
| Dell G3               | 9         | 0.72%   |
| ASUS ROG              | 9         | 0.72%   |
| HP Notebook           | 8         | 0.64%   |
| Lenovo ThinkBook      | 7         | 0.56%   |
| HP 15                 | 7         | 0.56%   |
| Dell Precision        | 7         | 0.56%   |
| Casper EXCALIBUR      | 7         | 0.56%   |
| ASUS X550VX           | 7         | 0.56%   |
| ASUS TUF              | 7         | 0.56%   |
| ASUS ASUS             | 7         | 0.56%   |
| Acer TravelMate       | 7         | 0.56%   |
| Lenovo Yoga           | 6         | 0.48%   |
| HUAWEI BOD-WXX9       | 6         | 0.48%   |
| Hometech ALFA         | 6         | 0.48%   |
| Dell XPS              | 6         | 0.48%   |
| Apple MacBookPro8     | 6         | 0.48%   |
| Lenovo V15            | 5         | 0.4%    |
| HUAWEI NBLK-WAX9X     | 5         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 135       | 10.74%  |
| 2019    | 127       | 10.1%   |
| 2018    | 109       | 8.67%   |
| 2021    | 101       | 8.04%   |
| 2011    | 98        | 7.8%    |
| 2017    | 80        | 6.36%   |
| 2012    | 77        | 6.13%   |
| 2016    | 75        | 5.97%   |
| 2015    | 75        | 5.97%   |
| 2013    | 74        | 5.89%   |
| 2014    | 72        | 5.73%   |
| 2010    | 72        | 5.73%   |
| 2022    | 45        | 3.58%   |
| 2009    | 41        | 3.26%   |
| 2008    | 31        | 2.47%   |
| 2007    | 14        | 1.11%   |
| 2006    | 11        | 0.88%   |
| Unknown | 8         | 0.64%   |
| 2023    | 7         | 0.56%   |
| 2005    | 5         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1257      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1172      | 91.56%  |
| Enabled  | 108       | 8.44%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1254      | 99.76%  |
| Yes  | 3         | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 374       | 29.47%  |
| 3.01-4.0    | 258       | 20.33%  |
| 16.01-24.0  | 225       | 17.73%  |
| 8.01-16.0   | 221       | 17.42%  |
| 1.01-2.0    | 67        | 5.28%   |
| 32.01-64.0  | 62        | 4.89%   |
| 2.01-3.0    | 31        | 2.44%   |
| 64.01-256.0 | 13        | 1.02%   |
| 24.01-32.0  | 11        | 0.87%   |
| 0.51-1.0    | 7         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 440       | 31.32%  |
| 2.01-3.0   | 383       | 27.26%  |
| 3.01-4.0   | 225       | 16.01%  |
| 4.01-8.0   | 214       | 15.23%  |
| 0.51-1.0   | 74        | 5.27%   |
| 8.01-16.0  | 51        | 3.63%   |
| 0.01-0.5   | 13        | 0.93%   |
| 16.01-24.0 | 4         | 0.28%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 895       | 69.92%  |
| 2      | 342       | 26.72%  |
| 3      | 27        | 2.11%   |
| 0      | 7         | 0.55%   |
| 4      | 6         | 0.47%   |
| 5      | 2         | 0.16%   |
| 6      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 824       | 65.09%  |
| Yes       | 442       | 34.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1051      | 83.21%  |
| No        | 212       | 16.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1229      | 97.77%  |
| No        | 28        | 2.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1027      | 80.74%  |
| No        | 245       | 19.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Turkey  | 1257      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Istanbul            | 482       | 35.68%  |
| Ankara              | 194       | 14.36%  |
| Izmir               | 130       | 9.62%   |
| Antalya             | 73        | 5.4%    |
| Bursa               | 58        | 4.29%   |
| Adana               | 25        | 1.85%   |
| Kosekoy             | 17        | 1.26%   |
| Gaziantep           | 17        | 1.26%   |
| Konya               | 16        | 1.18%   |
| İzmit              | 16        | 1.18%   |
| Balıkesir          | 16        | 1.18%   |
| Kayseri             | 14        | 1.04%   |
| Denizli             | 13        | 0.96%   |
| Antakya             | 12        | 0.89%   |
| Mersin              | 11        | 0.81%   |
| Tekirdağ           | 9         | 0.67%   |
| Samsun              | 9         | 0.67%   |
| Mugla               | 9         | 0.67%   |
| Magnesia ad Sipylum | 8         | 0.59%   |
| Yalova              | 7         | 0.52%   |
| Kartal              | 7         | 0.52%   |
| Aydin               | 7         | 0.52%   |
| Sisli               | 6         | 0.44%   |
| Ordu                | 6         | 0.44%   |
| Diyarbakır         | 6         | 0.44%   |
| Batman              | 6         | 0.44%   |
| Adapazarı          | 6         | 0.44%   |
| Çanakkale          | 5         | 0.37%   |
| Trabzon             | 4         | 0.3%    |
| Osmaniye            | 4         | 0.3%    |
| Isparta             | 4         | 0.3%    |
| Eskişehir          | 4         | 0.3%    |
| Erzurum             | 4         | 0.3%    |
| Umraniye            | 3         | 0.22%   |
| Tarsus              | 3         | 0.22%   |
| Sanliurfa           | 3         | 0.22%   |
| OEdemis             | 3         | 0.22%   |
| Maltepe             | 3         | 0.22%   |
| Malatya             | 3         | 0.22%   |
| Kırklareli         | 3         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 245       | 324    | 15.11%  |
| WDC                         | 180       | 233    | 11.1%   |
| Seagate                     | 170       | 201    | 10.49%  |
| Toshiba                     | 157       | 187    | 9.69%   |
| SanDisk                     | 138       | 156    | 8.51%   |
| Kingston                    | 88        | 127    | 5.43%   |
| Unknown                     | 65        | 80     | 4.01%   |
| SK hynix                    | 56        | 71     | 3.45%   |
| HGST                        | 56        | 63     | 3.45%   |
| Micron Technology           | 47        | 54     | 2.9%    |
| Hitachi                     | 45        | 49     | 2.78%   |
| Intel                       | 40        | 51     | 2.47%   |
| Crucial                     | 25        | 31     | 1.54%   |
| Apple                       | 20        | 26     | 1.23%   |
| A-DATA Technology           | 20        | 23     | 1.23%   |
| China                       | 18        | 24     | 1.11%   |
| KIOXIA                      | 16        | 18     | 0.99%   |
| Phison                      | 14        | 14     | 0.86%   |
| Fujitsu                     | 13        | 13     | 0.8%    |
| KIOXIA-EXCERIA              | 12        | 14     | 0.74%   |
| Corsair                     | 12        | 12     | 0.74%   |
| Micron/Crucial Technology   | 9         | 10     | 0.56%   |
| Kingston Technology Company | 9         | 9      | 0.56%   |
| HS-SSD-C100                 | 9         | 9      | 0.56%   |
| OCZ                         | 7         | 7      | 0.43%   |
| UMIS                        | 6         | 8      | 0.37%   |
| Silicon Motion              | 6         | 7      | 0.37%   |
| Pioneer                     | 6         | 20     | 0.37%   |
| Netac                       | 6         | 7      | 0.37%   |
| LITEON                      | 6         | 7      | 0.37%   |
| JMicron Technology          | 6         | 6      | 0.37%   |
| Lexar                       | 5         | 11     | 0.31%   |
| Gigabyte Technology         | 5         | 11     | 0.31%   |
| Unknown                     | 5         | 5      | 0.31%   |
| Union Memory (Shenzhen)     | 4         | 6      | 0.25%   |
| Union Memory                | 4         | 8      | 0.25%   |
| Transcend                   | 4         | 4      | 0.25%   |
| Team                        | 4         | 4      | 0.25%   |
| SPCC                        | 4         | 4      | 0.25%   |
| Phison Electronics          | 4         | 4      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 36        | 2.14%   |
| HGST HTS721010A9E630 1TB                              | 28        | 1.66%   |
| Toshiba MQ04ABF100 1TB                                | 23        | 1.36%   |
| Toshiba MQ01ABD100 1TB                                | 21        | 1.25%   |
| SanDisk SSD PLUS 240GB                                | 19        | 1.13%   |
| Toshiba MQ01ABF050 500GB                              | 18        | 1.07%   |
| Unknown MMC Card  32GB                                | 16        | 0.95%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 16        | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 16        | 0.95%   |
| Samsung NVMe SSD Drive 512GB                          | 14        | 0.83%   |
| Seagate ST500LT012-1DG142 500GB                       | 13        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 13        | 0.77%   |
| Seagate ST1000LM049-2GH172 1TB                        | 11        | 0.65%   |
| SanDisk SSD PLUS 120GB                                | 11        | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 10        | 0.59%   |
| HGST HTS541010A9E680 1TB                              | 10        | 0.59%   |
| Toshiba TR200 240GB SSD                               | 9         | 0.53%   |
| Seagate ST9500325AS 500GB                             | 9         | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                          | 9         | 0.53%   |
| SanDisk NVMe SSD Drive 256GB                          | 9         | 0.53%   |
| Kingston SA400S37240G 240GB SSD                       | 9         | 0.53%   |
| Intel NVMe SSD Drive 512GB                            | 9         | 0.53%   |
| Toshiba MQ01ABD075 752GB                              | 8         | 0.47%   |
| SK hynix NVMe SSD Drive 512GB                         | 8         | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 8         | 0.47%   |
| Seagate ST1000LM048-2E7172 1TB                        | 7         | 0.42%   |
| Samsung SSD 860 EVO 500GB                             | 7         | 0.42%   |
| Samsung SSD 860 EVO 250GB                             | 7         | 0.42%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                   | 7         | 0.42%   |
| Kingston SA400S37120G 120GB SSD                       | 7         | 0.42%   |
| HGST HTS545050A7E680 500GB                            | 7         | 0.42%   |
| SK hynix NVMe SSD Drive 256GB                         | 6         | 0.36%   |
| Phison 311CD0512GB                                    | 6         | 0.36%   |
| Micron NVMe SSD Drive 512GB                           | 6         | 0.36%   |
| KIOXIA-EXCERIA SATA SSD 240GB                         | 6         | 0.36%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB               | 6         | 0.36%   |
| WDC WD10SPZX-75Z10T2 1TB                              | 5         | 0.3%    |
| WDC WD10SPZX-21Z10T0 1TB                              | 5         | 0.3%    |
| WDC WD10SPZX-08Z10 1TB                                | 5         | 0.3%    |
| WDC WD10JPCX-24UE4T0 1TB                              | 5         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 192    | 29.96%  |
| WDC                 | 129       | 168    | 23.29%  |
| Toshiba             | 117       | 131    | 21.12%  |
| HGST                | 56        | 63     | 10.11%  |
| Hitachi             | 45        | 49     | 8.12%   |
| Samsung Electronics | 18        | 18     | 3.25%   |
| Fujitsu             | 13        | 13     | 2.35%   |
| Unknown             | 4         | 4      | 0.72%   |
| Pioneer             | 2         | 10     | 0.36%   |
| SABRENT             | 1         | 1      | 0.18%   |
| Intenso             | 1         | 1      | 0.18%   |
| External            | 1         | 1      | 0.18%   |
| Apple               | 1         | 2      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 91        | 106    | 18.42%  |
| Samsung Electronics | 89        | 112    | 18.02%  |
| Kingston            | 63        | 96     | 12.75%  |
| WDC                 | 28        | 33     | 5.67%   |
| Crucial             | 18        | 23     | 3.64%   |
| Toshiba             | 17        | 18     | 3.44%   |
| Micron Technology   | 17        | 21     | 3.44%   |
| China               | 15        | 18     | 3.04%   |
| A-DATA Technology   | 14        | 16     | 2.83%   |
| Corsair             | 12        | 12     | 2.43%   |
| Apple               | 11        | 13     | 2.23%   |
| SK hynix            | 10        | 13     | 2.02%   |
| KIOXIA-EXCERIA      | 8         | 10     | 1.62%   |
| Intel               | 8         | 14     | 1.62%   |
| Seagate             | 7         | 8      | 1.42%   |
| OCZ                 | 7         | 7      | 1.42%   |
| Netac               | 6         | 7      | 1.21%   |
| LITEON              | 6         | 7      | 1.21%   |
| SPCC                | 4         | 4      | 0.81%   |
| Pioneer             | 4         | 10     | 0.81%   |
| LITEONIT            | 4         | 5      | 0.81%   |
| Lexar               | 4         | 10     | 0.81%   |
| KingSpec            | 4         | 4      | 0.81%   |
| JAMESDONKEY         | 4         | 4      | 0.81%   |
| Team                | 3         | 3      | 0.61%   |
| Patriot             | 3         | 4      | 0.61%   |
| KingFast            | 3         | 5      | 0.61%   |
| JMicron Technology  | 3         | 3      | 0.61%   |
| HS-SSD-C100         | 3         | 3      | 0.61%   |
| Gigabyte Technology | 3         | 8      | 0.61%   |
| EZCOOL              | 3         | 4      | 0.61%   |
| TwinMOS             | 2         | 2      | 0.4%    |
| Indilinx            | 2         | 4      | 0.4%    |
| GOODRAM             | 2         | 5      | 0.4%    |
| WDC WDS2            | 1         | 1      | 0.2%    |
| Transcend           | 1         | 1      | 0.2%    |
| TO Exter            | 1         | 3      | 0.2%    |
| PNY                 | 1         | 1      | 0.2%    |
| Mushkin             | 1         | 2      | 0.2%    |
| Leven               | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 537       | 653    | 34.8%   |
| NVMe    | 458       | 620    | 29.68%  |
| SSD     | 458       | 632    | 29.68%  |
| MMC     | 64        | 78     | 4.15%   |
| Unknown | 26        | 33     | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 870       | 1263   | 60.71%  |
| NVMe | 458       | 620    | 31.96%  |
| MMC  | 64        | 78     | 4.47%   |
| SAS  | 41        | 55     | 2.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 647       | 887    | 67.05%  |
| 0.51-1.0   | 296       | 363    | 30.67%  |
| 1.01-2.0   | 19        | 32     | 1.97%   |
| 4.01-10.0  | 2         | 2      | 0.21%   |
| 3.01-4.0   | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 408       | 30.16%  |
| 251-500        | 318       | 23.5%   |
| 501-1000       | 184       | 13.6%   |
| 51-100         | 110       | 8.13%   |
| 1-20           | 100       | 7.39%   |
| 1001-2000      | 95        | 7.02%   |
| 21-50          | 82        | 6.06%   |
| 2001-3000      | 25        | 1.85%   |
| Unknown        | 16        | 1.18%   |
| More than 3000 | 15        | 1.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 565       | 40.33%  |
| 21-50          | 291       | 20.77%  |
| 101-250        | 175       | 12.49%  |
| 51-100         | 166       | 11.85%  |
| 251-500        | 89        | 6.35%   |
| 501-1000       | 68        | 4.85%   |
| 1001-2000      | 20        | 1.43%   |
| Unknown        | 16        | 1.14%   |
| 2001-3000      | 6         | 0.43%   |
| More than 3000 | 5         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                | 4         | 4      | 3.51%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 6      | 3.51%   |
| HGST HTS721010A9E630 1TB              | 4         | 5      | 3.51%   |
| Toshiba MQ01ABF050 500GB              | 3         | 4      | 2.63%   |
| Toshiba MQ01ABD050 500GB              | 3         | 4      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB        | 3         | 3      | 2.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 3      | 1.75%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 1.75%   |
| Toshiba MQ02ABD100H 1TB               | 2         | 3      | 1.75%   |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 1.75%   |
| Toshiba MK3252GSX 320GB               | 2         | 2      | 1.75%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.75%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.75%   |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 1.75%   |
| JMicron Technology Tech 250GB         | 2         | 2      | 1.75%   |
| Indilinx IND-S325S120G 120GB SSD      | 2         | 4      | 1.75%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 1.75%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 2      | 1.75%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 1.75%   |
| Fujitsu MHY2120BH 120GB               | 2         | 2      | 1.75%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.88%   |
| WDC WD7500BPVT-55HXZT3 752GB          | 1         | 1      | 0.88%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.88%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB          | 1         | 1      | 0.88%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 0.88%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 0.88%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 0.88%   |
| Toshiba MQ01ABF050M 500GB             | 1         | 1      | 0.88%   |
| Toshiba MK4058GSX 400GB               | 1         | 1      | 0.88%   |
| Toshiba MK3265GSX 320GB               | 1         | 1      | 0.88%   |
| Toshiba MK3263GSXN 320GB              | 1         | 1      | 0.88%   |
| Toshiba MK1665GSX 160GB               | 1         | 1      | 0.88%   |
| Toshiba MK1011GAH 100GB               | 1         | 1      | 0.88%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 2      | 0.88%   |
| SK hynix HFS256G32MND-2200A 256GB SSD | 1         | 1      | 0.88%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 0.88%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 0.88%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 0.88%   |
| Seagate ST9160821AS 160GB             | 1         | 1      | 0.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 24        | 27     | 21.05%  |
| Seagate             | 20        | 22     | 17.54%  |
| Hitachi             | 14        | 14     | 12.28%  |
| WDC                 | 10        | 11     | 8.77%   |
| HGST                | 10        | 11     | 8.77%   |
| SanDisk             | 6         | 7      | 5.26%   |
| Samsung Electronics | 5         | 7      | 4.39%   |
| A-DATA Technology   | 5         | 5      | 4.39%   |
| Kingston            | 3         | 3      | 2.63%   |
| Fujitsu             | 3         | 3      | 2.63%   |
| SK hynix            | 2         | 3      | 1.75%   |
| JMicron Technology  | 2         | 2      | 1.75%   |
| Indilinx            | 2         | 4      | 1.75%   |
| China               | 2         | 2      | 1.75%   |
| LITEONIT            | 1         | 2      | 0.88%   |
| LITEON              | 1         | 1      | 0.88%   |
| JD                  | 1         | 1      | 0.88%   |
| Intel               | 1         | 1      | 0.88%   |
| Crucial             | 1         | 1      | 0.88%   |
| Apple               | 1         | 2      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 24        | 27     | 29.63%  |
| Seagate             | 20        | 22     | 24.69%  |
| Hitachi             | 14        | 14     | 17.28%  |
| HGST                | 10        | 11     | 12.35%  |
| WDC                 | 7         | 7      | 8.64%   |
| Fujitsu             | 3         | 3      | 3.7%    |
| Samsung Electronics | 2         | 2      | 2.47%   |
| Apple               | 1         | 2      | 1.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 79        | 88     | 70.54%  |
| SSD     | 28        | 36     | 25%     |
| NVMe    | 3         | 3      | 2.68%   |
| Unknown | 2         | 2      | 1.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 33.33%  |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB          | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| HGST                | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 770       | 1174   | 56.74%  |
| Works    | 475       | 710    | 35%     |
| Malfunc  | 109       | 129    | 8.03%   |
| Failed   | 3         | 3      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 891       | 59.32%  |
| Samsung Electronics              | 154       | 10.25%  |
| AMD                              | 131       | 8.72%   |
| SanDisk                          | 66        | 4.39%   |
| SK hynix                         | 44        | 2.93%   |
| Kingston Technology Company      | 34        | 2.26%   |
| Micron Technology                | 29        | 1.93%   |
| KIOXIA                           | 25        | 1.66%   |
| Phison Electronics               | 21        | 1.4%    |
| Toshiba America Info Systems     | 19        | 1.26%   |
| Micron/Crucial Technology        | 15        | 1%      |
| Union Memory (Shenzhen)          | 12        | 0.8%    |
| Silicon Integrated Systems [SiS] | 11        | 0.73%   |
| Silicon Motion                   | 9         | 0.6%    |
| Nvidia                           | 9         | 0.6%    |
| ADATA Technology                 | 8         | 0.53%   |
| Apple                            | 7         | 0.47%   |
| Yangtze Memory Technologies      | 4         | 0.27%   |
| Realtek Semiconductor            | 4         | 0.27%   |
| Lite-On Technology               | 3         | 0.2%    |
| Transcend                        | 2         | 0.13%   |
| Marvell Technology Group         | 2         | 0.13%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| OCZ Technology Group             | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 119       | 7.48%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 104       | 6.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 98        | 6.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 76        | 4.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 64        | 4.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 50        | 3.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 50        | 3.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 49        | 3.08%   |
| Samsung NVMe SSD Controller 980                                                  | 45        | 2.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 45        | 2.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 42        | 2.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 37        | 2.33%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 36        | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 33        | 2.07%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 33        | 2.07%   |
| Intel Volume Management Device NVMe RAID Controller                              | 29        | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 24        | 1.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 21        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 18        | 1.13%   |
| Intel SSD 660P Series                                                            | 17        | 1.07%   |
| Intel Tiger Lake-LP SATA Controller                                              | 16        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 15        | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 15        | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 14        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 13        | 0.82%   |
| SK hynix BC511 NVMe SSD                                                          | 12        | 0.75%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 12        | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                                | 12        | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 12        | 0.75%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 12        | 0.75%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 11        | 0.69%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 11        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 11        | 0.69%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 10        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 928       | 60.26%  |
| NVMe | 458       | 29.74%  |
| RAID | 81        | 5.26%   |
| IDE  | 73        | 4.74%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1024      | 81.46%  |
| AMD    | 226       | 17.98%  |
| ARM    | 7         | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 2.31%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 2.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 1.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 1.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 1.75%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 22        | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 1.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 20        | 1.59%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.35%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 17        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 1.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 1.27%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 16        | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 1.19%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 1.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 1.11%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 14        | 1.11%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 1.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 1.11%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 1.03%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 1.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 11        | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 11        | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 11        | 0.88%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 10        | 0.8%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 10        | 0.8%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 0.8%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 10        | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.72%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 9         | 0.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.72%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 9         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 9         | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 0.72%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 9         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 353       | 28.08%  |
| Intel Core i7           | 289       | 22.99%  |
| Other                   | 108       | 8.59%   |
| Intel Core i3           | 83        | 6.6%    |
| AMD Ryzen 5             | 76        | 6.05%   |
| AMD Ryzen 7             | 59        | 4.69%   |
| Intel Core 2 Duo        | 52        | 4.14%   |
| Intel Celeron           | 52        | 4.14%   |
| Intel Atom              | 30        | 2.39%   |
| Intel Pentium           | 21        | 1.67%   |
| AMD Ryzen 3             | 15        | 1.19%   |
| AMD A8                  | 14        | 1.11%   |
| Intel Pentium Dual-Core | 11        | 0.88%   |
| Intel Core 2            | 11        | 0.88%   |
| AMD A10                 | 10        | 0.8%    |
| Intel Pentium Dual      | 9         | 0.72%   |
| AMD Ryzen 7 PRO         | 6         | 0.48%   |
| AMD A6                  | 6         | 0.48%   |
| Intel Pentium Silver    | 5         | 0.4%    |
| Intel Genuine           | 4         | 0.32%   |
| Intel Core i9           | 4         | 0.32%   |
| AMD A4                  | 4         | 0.32%   |
| AMD A12                 | 4         | 0.32%   |
| AMD Ryzen 9             | 3         | 0.24%   |
| AMD Ryzen 5 PRO         | 3         | 0.24%   |
| AMD E2                  | 3         | 0.24%   |
| AMD C-60                | 3         | 0.24%   |
| Intel Pentium M         | 2         | 0.16%   |
| Intel Core M            | 2         | 0.16%   |
| AMD E                   | 2         | 0.16%   |
| Intel Xeon              | 1         | 0.08%   |
| Intel Pentium 4         | 1         | 0.08%   |
| Intel Core              | 1         | 0.08%   |
| Intel Celeron M         | 1         | 0.08%   |
| Intel Celeron Dual-Core | 1         | 0.08%   |
| AMD Turion II Neo       | 1         | 0.08%   |
| AMD Turion 64 X2 Mobile | 1         | 0.08%   |
| AMD Mobile Athlon 64    | 1         | 0.08%   |
| AMD E1                  | 1         | 0.08%   |
| AMD C-70                | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 606       | 48.21%  |
| 4      | 425       | 33.81%  |
| 6      | 116       | 9.23%   |
| 8      | 69        | 5.49%   |
| 1      | 17        | 1.35%   |
| 14     | 12        | 0.95%   |
| 10     | 10        | 0.8%    |
| 12     | 2         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1256      | 99.92%  |
| 2      | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 987       | 78.52%  |
| 1      | 269       | 21.4%   |
| 8      | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1223      | 97.14%  |
| Unknown        | 24        | 1.91%   |
| 32-bit         | 11        | 0.87%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 346       | 26.62%  |
| 0x206a7    | 74        | 5.69%   |
| 0x306a9    | 70        | 5.38%   |
| 0x40651    | 41        | 3.15%   |
| 0x806ea    | 37        | 2.85%   |
| 0x306d4    | 34        | 2.62%   |
| 0x906ea    | 33        | 2.54%   |
| 0xa0652    | 32        | 2.46%   |
| 0x806ec    | 32        | 2.46%   |
| 0x806e9    | 32        | 2.46%   |
| 0x806c1    | 32        | 2.46%   |
| 0x406e3    | 31        | 2.38%   |
| 0x306c3    | 29        | 2.23%   |
| 0x20655    | 28        | 2.15%   |
| 0x1067a    | 28        | 2.15%   |
| 0x906e9    | 27        | 2.08%   |
| 0x08108102 | 21        | 1.62%   |
| 0x08608103 | 20        | 1.54%   |
| 0x506e3    | 19        | 1.46%   |
| 0x30678    | 19        | 1.46%   |
| 0x08108109 | 18        | 1.38%   |
| 0x706e5    | 16        | 1.23%   |
| 0x6fd      | 16        | 1.23%   |
| 0x0a50000c | 16        | 1.23%   |
| 0x08600106 | 16        | 1.23%   |
| 0x406c4    | 15        | 1.15%   |
| 0x20652    | 15        | 1.15%   |
| 0x906a3    | 10        | 0.77%   |
| 0x506c9    | 10        | 0.77%   |
| 0x06006705 | 10        | 0.77%   |
| 0x08600103 | 9         | 0.69%   |
| 0x806eb    | 8         | 0.62%   |
| 0x806d1    | 8         | 0.62%   |
| 0x10676    | 8         | 0.62%   |
| 0x08600104 | 8         | 0.62%   |
| 0x07030105 | 8         | 0.62%   |
| 0x906a4    | 7         | 0.54%   |
| 0x106ca    | 7         | 0.54%   |
| 0x0a50000d | 7         | 0.54%   |
| 0x706a8    | 6         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 232       | 18.46%  |
| SandyBridge      | 99        | 7.88%   |
| IvyBridge        | 91        | 7.24%   |
| Haswell          | 90        | 7.16%   |
| Skylake          | 69        | 5.49%   |
| Unknown          | 62        | 4.93%   |
| Westmere         | 56        | 4.46%   |
| TigerLake        | 50        | 3.98%   |
| Penryn           | 49        | 3.9%    |
| Zen+             | 47        | 3.74%   |
| Silvermont       | 46        | 3.66%   |
| CometLake        | 44        | 3.5%    |
| Broadwell        | 44        | 3.5%    |
| Zen 2            | 41        | 3.26%   |
| Core             | 36        | 2.86%   |
| IceLake          | 32        | 2.55%   |
| Zen 3            | 25        | 1.99%   |
| Excavator        | 21        | 1.67%   |
| Alderlake Hybrid | 18        | 1.43%   |
| Goldmont plus    | 17        | 1.35%   |
| Puma             | 15        | 1.19%   |
| Bonnell          | 13        | 1.03%   |
| Goldmont         | 11        | 0.88%   |
| Zen              | 9         | 0.72%   |
| Bobcat           | 9         | 0.72%   |
| Nehalem          | 7         | 0.56%   |
| Piledriver       | 6         | 0.48%   |
| P6               | 6         | 0.48%   |
| K8 Hammer        | 4         | 0.32%   |
| K10 Llano        | 4         | 0.32%   |
| Steamroller      | 1         | 0.08%   |
| NetBurst         | 1         | 0.08%   |
| K10              | 1         | 0.08%   |
| Jaguar           | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 905       | 50.36%  |
| Nvidia                           | 499       | 27.77%  |
| AMD                              | 384       | 21.37%  |
| Silicon Integrated Systems [SiS] | 9         | 0.5%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 85        | 4.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 84        | 4.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 52        | 2.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 49        | 2.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 47        | 2.51%   |
| Intel HD Graphics 620                                                                    | 45        | 2.4%    |
| Intel UHD Graphics 620                                                                   | 42        | 2.24%   |
| AMD Renoir                                                                               | 41        | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 40        | 2.13%   |
| Intel HD Graphics 5500                                                                   | 37        | 1.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 36        | 1.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 35        | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 1.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 32        | 1.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 29        | 1.55%   |
| AMD Lucienne                                                                             | 29        | 1.55%   |
| Intel HD Graphics 630                                                                    | 28        | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 24        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 22        | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 1.17%   |
| Intel HD Graphics 530                                                                    | 21        | 1.12%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 1.12%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 19        | 1.01%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 1.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 18        | 0.96%   |
| Nvidia GM108M [GeForce 840M]                                                             | 18        | 0.96%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 17        | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 16        | 0.85%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 15        | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.8%    |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 13        | 0.69%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 13        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 394       | 31.22%  |
| 1 x Intel      | 393       | 31.14%  |
| 1 x AMD        | 180       | 14.26%  |
| Intel + AMD    | 117       | 9.27%   |
| 1 x Nvidia     | 70        | 5.55%   |
| 2 x AMD        | 53        | 4.2%    |
| AMD + Nvidia   | 34        | 2.69%   |
| 1 x SiS        | 9         | 0.71%   |
| Other          | 8         | 0.63%   |
| 2 x Intel      | 3         | 0.24%   |
| 2 x Nvidia     | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1001      | 78.2%   |
| Proprietary | 238       | 18.59%  |
| Unknown     | 41        | 3.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 716       | 55.25%  |
| 1.01-2.0   | 203       | 15.66%  |
| 0.01-0.5   | 135       | 10.42%  |
| 0.51-1.0   | 114       | 8.8%    |
| 3.01-4.0   | 89        | 6.87%   |
| 5.01-6.0   | 26        | 2.01%   |
| 7.01-8.0   | 6         | 0.46%   |
| 2.01-3.0   | 5         | 0.39%   |
| 8.01-16.0  | 2         | 0.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 261       | 19.49%  |
| LG Display              | 222       | 16.58%  |
| BOE                     | 214       | 15.98%  |
| Chimei Innolux          | 180       | 13.44%  |
| Samsung Electronics     | 124       | 9.26%   |
| Chi Mei Optoelectronics | 33        | 2.46%   |
| Apple                   | 32        | 2.39%   |
| PANDA                   | 29        | 2.17%   |
| Lenovo                  | 24        | 1.79%   |
| Sharp                   | 17        | 1.27%   |
| Goldstar                | 17        | 1.27%   |
| Dell                    | 16        | 1.19%   |
| Philips                 | 15        | 1.12%   |
| ViewSonic               | 14        | 1.05%   |
| ASUSTek Computer        | 13        | 0.97%   |
| LG Philips              | 11        | 0.82%   |
| Hewlett-Packard         | 11        | 0.82%   |
| CPT                     | 9         | 0.67%   |
| AOC                     | 9         | 0.67%   |
| Ancor Communications    | 9         | 0.67%   |
| Acer                    | 8         | 0.6%    |
| InfoVision              | 7         | 0.52%   |
| LGD                     | 6         | 0.45%   |
| BenQ                    | 6         | 0.45%   |
| Vestel Elektronik       | 4         | 0.3%    |
| MSI                     | 4         | 0.3%    |
| HannStar                | 4         | 0.3%    |
| CSO                     | 4         | 0.3%    |
| Unknown                 | 3         | 0.22%   |
| Valve                   | 2         | 0.15%   |
| Sony                    | 2         | 0.15%   |
| JDI                     | 2         | 0.15%   |
| CS_                     | 2         | 0.15%   |
| VIE                     | 1         | 0.07%   |
| Unknown (XXX)           | 1         | 0.07%   |
| Toshiba                 | 1         | 0.07%   |
| Sun                     | 1         | 0.07%   |
| STA                     | 1         | 0.07%   |
| SNN                     | 1         | 0.07%   |
| SANYO                   | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 23        | 1.7%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 19        | 1.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 17        | 1.25%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 1.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 14        | 1.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 14        | 1.03%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 1.03%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 14        | 1.03%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.89%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 11        | 0.81%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 11        | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.59%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 8         | 0.59%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 8         | 0.59%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 8         | 0.59%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 7         | 0.52%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 7         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 7         | 0.52%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                    | 7         | 0.52%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 7         | 0.52%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 6         | 0.44%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 6         | 0.44%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 6         | 0.44%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 6         | 0.44%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 6         | 0.44%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.37%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 5         | 0.37%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 5         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 572       | 45.18%  |
| 1366x768 (WXGA)    | 448       | 35.39%  |
| 1280x800 (WXGA)    | 41        | 3.24%   |
| 3840x2160 (4K)     | 25        | 1.97%   |
| 1600x900 (HD+)     | 25        | 1.97%   |
| 1440x900 (WXGA+)   | 22        | 1.74%   |
| 2560x1440 (QHD)    | 21        | 1.66%   |
| 1920x1200 (WUXGA)  | 17        | 1.34%   |
| 2160x1440          | 13        | 1.03%   |
| 2560x1600          | 12        | 0.95%   |
| 1024x600           | 9         | 0.71%   |
| Unknown            | 8         | 0.63%   |
| 1680x1050 (WSXGA+) | 7         | 0.55%   |
| 2880x1800          | 6         | 0.47%   |
| 3200x1800 (QHD+)   | 5         | 0.39%   |
| 3840x1080          | 3         | 0.24%   |
| 1680x945           | 3         | 0.24%   |
| 1280x1024 (SXGA)   | 3         | 0.24%   |
| 800x1280           | 2         | 0.16%   |
| 3840x2400          | 2         | 0.16%   |
| 3000x2000          | 2         | 0.16%   |
| 2560x1080          | 2         | 0.16%   |
| 2520x1680          | 2         | 0.16%   |
| 1920x540           | 2         | 0.16%   |
| 1360x768           | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 800x600            | 1         | 0.08%   |
| 3840x2560          | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 3046x1050          | 1         | 0.08%   |
| 2880x1620          | 1         | 0.08%   |
| 2806x900           | 1         | 0.08%   |
| 2646x1024          | 1         | 0.08%   |
| 2288x1287          | 1         | 0.08%   |
| 1280x720 (HD)      | 1         | 0.08%   |
| 1280x1080          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 756       | 56.42%  |
| 13      | 152       | 11.34%  |
| 14      | 88        | 6.57%   |
| 17      | 57        | 4.25%   |
| 23      | 39        | 2.91%   |
| 24      | 31        | 2.31%   |
| 27      | 30        | 2.24%   |
| 12      | 25        | 1.87%   |
| 16      | 22        | 1.64%   |
| 21      | 21        | 1.57%   |
| 18      | 18        | 1.34%   |
| Unknown | 18        | 1.34%   |
| 11      | 17        | 1.27%   |
| 10      | 14        | 1.04%   |
| 31      | 9         | 0.67%   |
| 19      | 9         | 0.67%   |
| 84      | 4         | 0.3%    |
| 32      | 4         | 0.3%    |
| 22      | 4         | 0.3%    |
| 20      | 3         | 0.22%   |
| 57      | 2         | 0.15%   |
| 46      | 2         | 0.15%   |
| 40      | 2         | 0.15%   |
| 34      | 2         | 0.15%   |
| 28      | 2         | 0.15%   |
| 7       | 2         | 0.15%   |
| 72      | 1         | 0.07%   |
| 54      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 911       | 68.39%  |
| 201-300     | 138       | 10.36%  |
| 501-600     | 96        | 7.21%   |
| 351-400     | 77        | 5.78%   |
| 401-500     | 54        | 4.05%   |
| Unknown     | 18        | 1.35%   |
| 601-700     | 15        | 1.13%   |
| 701-800     | 8         | 0.6%    |
| 1501-2000   | 5         | 0.38%   |
| 1001-1500   | 5         | 0.38%   |
| 801-900     | 2         | 0.15%   |
| 1-100       | 2         | 0.15%   |
| 901-1000    | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1039      | 86.8%   |
| 16/10   | 109       | 9.11%   |
| 3/2     | 20        | 1.67%   |
| Unknown | 16        | 1.34%   |
| 4/3     | 5         | 0.42%   |
| 5/4     | 3         | 0.25%   |
| 21/9    | 2         | 0.17%   |
| 0.67    | 2         | 0.17%   |
| 6/5     | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 760       | 56.89%  |
| 81-90          | 184       | 13.77%  |
| 201-250        | 80        | 5.99%   |
| 71-80          | 57        | 4.27%   |
| 121-130        | 52        | 3.89%   |
| 301-350        | 31        | 2.32%   |
| 61-70          | 23        | 1.72%   |
| 151-200        | 19        | 1.42%   |
| 351-500        | 18        | 1.35%   |
| 141-150        | 18        | 1.35%   |
| Unknown        | 18        | 1.35%   |
| 51-60          | 17        | 1.27%   |
| 111-120        | 15        | 1.12%   |
| 41-50          | 14        | 1.05%   |
| More than 1000 | 8         | 0.6%    |
| 251-300        | 6         | 0.45%   |
| 501-1000       | 6         | 0.45%   |
| 91-100         | 5         | 0.37%   |
| 131-140        | 3         | 0.22%   |
| 1-40           | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 562       | 42.64%  |
| 101-120       | 415       | 31.49%  |
| 51-100        | 214       | 16.24%  |
| 161-240       | 84        | 6.37%   |
| Unknown       | 18        | 1.37%   |
| More than 240 | 17        | 1.29%   |
| 1-50          | 8         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1063      | 82.53%  |
| 2     | 172       | 13.35%  |
| 0     | 47        | 3.65%   |
| 3     | 6         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 820       | 39.39%  |
| Intel                                  | 550       | 26.42%  |
| Qualcomm Atheros                       | 315       | 15.13%  |
| Broadcom                               | 147       | 7.06%   |
| MediaTek                               | 32        | 1.54%   |
| Broadcom Limited                       | 29        | 1.39%   |
| Ralink                                 | 27        | 1.3%    |
| Marvell Technology Group               | 27        | 1.3%    |
| Ralink Technology                      | 21        | 1.01%   |
| Silicon Integrated Systems [SiS]       | 12        | 0.58%   |
| Samsung Electronics                    | 12        | 0.58%   |
| Xiaomi                                 | 10        | 0.48%   |
| TP-Link                                | 9         | 0.43%   |
| Nvidia                                 | 7         | 0.34%   |
| Qualcomm Atheros Communications        | 6         | 0.29%   |
| ASUSTek Computer                       | 6         | 0.29%   |
| ASIX Electronics                       | 6         | 0.29%   |
| Ericsson Business Mobile Networks      | 5         | 0.24%   |
| JMicron Technology                     | 4         | 0.19%   |
| Dell                                   | 3         | 0.14%   |
| ZyXEL Communications                   | 2         | 0.1%    |
| Qualcomm                               | 2         | 0.1%    |
| Lenovo                                 | 2         | 0.1%    |
| ICS Advent                             | 2         | 0.1%    |
| Huawei Technologies                    | 2         | 0.1%    |
| Attansic Technology                    | 2         | 0.1%    |
| Apple                                  | 2         | 0.1%    |
| U-Blox                                 | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Sierra Wireless                        | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| LSI                                    | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| IMC Networks                           | 1         | 0.05%   |
| Hex/ProfiCNC                           | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |
| Fibocom                                | 1         | 0.05%   |
| Espressi                               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 523       | 21.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 152       | 6.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 63        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 62        | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 56        | 2.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 49        | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 45        | 1.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 45        | 1.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 43        | 1.79%   |
| Intel Wi-Fi 6 AX201                                               | 42        | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 37        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 37        | 1.54%   |
| Intel Wireless 7265                                               | 35        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32        | 1.33%   |
| Intel Wireless 8265 / 8275                                        | 29        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                     | 24        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 22        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 22        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 21        | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 21        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 20        | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 0.83%   |
| Intel Wireless 7260                                               | 18        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.75%   |
| Intel Wireless 3160                                               | 17        | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.67%   |
| Intel Wireless 3165                                               | 16        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.63%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 14        | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.58%   |
| Intel Wireless 8260                                               | 14        | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 13        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 13        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.5%    |
| Intel WiFi Link 5100                                              | 12        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 532       | 41.05%  |
| Qualcomm Atheros                  | 263       | 20.29%  |
| Realtek Semiconductor             | 248       | 19.14%  |
| Broadcom                          | 120       | 9.26%   |
| MediaTek                          | 31        | 2.39%   |
| Ralink                            | 27        | 2.08%   |
| Ralink Technology                 | 21        | 1.62%   |
| Broadcom Limited                  | 20        | 1.54%   |
| TP-Link                           | 7         | 0.54%   |
| Qualcomm Atheros Communications   | 6         | 0.46%   |
| ASUSTek Computer                  | 6         | 0.46%   |
| Ericsson Business Mobile Networks | 3         | 0.23%   |
| ZyXEL Communications              | 2         | 0.15%   |
| Dell                              | 2         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.08%   |
| Sierra Wireless                   | 1         | 0.08%   |
| Marvell Technology Group          | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| IMC Networks                      | 1         | 0.08%   |
| Fibocom                           | 1         | 0.08%   |
| Belkin Components                 | 1         | 0.08%   |
| Accton Technology                 | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 63        | 4.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 62        | 4.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 56        | 4.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 49        | 3.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 3.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 45        | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 43        | 3.31%   |
| Intel Wi-Fi 6 AX201                                            | 42        | 3.23%   |
| Intel Wi-Fi 6 AX200                                            | 37        | 2.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 37        | 2.85%   |
| Intel Wireless 7265                                            | 35        | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 32        | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32        | 2.46%   |
| Intel Wireless 8265 / 8275                                     | 29        | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 28        | 2.16%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 1.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 1.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 21        | 1.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 21        | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 20        | 1.54%   |
| Intel Wireless 7260                                            | 18        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.39%   |
| Intel Wireless 3160                                            | 17        | 1.31%   |
| Intel Wireless 3165                                            | 16        | 1.23%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 14        | 1.08%   |
| Intel Wireless 8260                                            | 14        | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 13        | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 13        | 1%      |
| Intel WiFi Link 5100                                           | 12        | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 0.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 11        | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 0.85%   |
| Ralink MT7601U Wireless Adapter                                | 10        | 0.77%   |
| Intel Wireless-AC 9260                                         | 10        | 0.77%   |
| Intel Centrino Wireless-N 2230                                 | 10        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 0.77%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 9         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 731       | 67.75%  |
| Intel                                  | 100       | 9.27%   |
| Qualcomm Atheros                       | 93        | 8.62%   |
| Broadcom                               | 50        | 4.63%   |
| Marvell Technology Group               | 26        | 2.41%   |
| Samsung Electronics                    | 12        | 1.11%   |
| Silicon Integrated Systems [SiS]       | 11        | 1.02%   |
| Xiaomi                                 | 10        | 0.93%   |
| Broadcom Limited                       | 9         | 0.83%   |
| Nvidia                                 | 6         | 0.56%   |
| ASIX Electronics                       | 6         | 0.56%   |
| JMicron Technology                     | 4         | 0.37%   |
| TP-Link                                | 2         | 0.19%   |
| Qualcomm                               | 2         | 0.19%   |
| ICS Advent                             | 2         | 0.19%   |
| Huawei Technologies                    | 2         | 0.19%   |
| Attansic Technology                    | 2         | 0.19%   |
| Apple                                  | 2         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.09%   |
| Motorola PCS                           | 1         | 0.09%   |
| Microchip Technology                   | 1         | 0.09%   |
| MediaTek                               | 1         | 0.09%   |
| LSI                                    | 1         | 0.09%   |
| Lenovo                                 | 1         | 0.09%   |
| Davicom Semiconductor                  | 1         | 0.09%   |
| Aquantia                               | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 523       | 48.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 152       | 14.01%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20        | 1.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 16        | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 15        | 1.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 15        | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                              | 14        | 1.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 12        | 1.11%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 11        | 1.01%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 11        | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 1.01%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 11        | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 9         | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 9         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 9         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 8         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 8         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 7         | 0.65%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 6         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 6         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 6         | 0.55%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 6         | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 5         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 5         | 0.46%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 0.46%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 4         | 0.37%   |
| Intel Ethernet Connection (13) I219-V                                          | 4         | 0.37%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 0.37%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 4         | 0.37%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 4         | 0.37%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1229      | 53.69%  |
| Ethernet | 1046      | 45.7%   |
| Modem    | 13        | 0.57%   |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1036      | 80.75%  |
| Ethernet | 247       | 19.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 987       | 78.4%   |
| 1     | 238       | 18.9%   |
| 0     | 31        | 2.46%   |
| 3     | 3         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1237      | 98.1%   |
| Yes  | 24        | 1.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 427       | 41.34%  |
| Realtek Semiconductor           | 125       | 12.1%   |
| Qualcomm Atheros Communications | 101       | 9.78%   |
| IMC Networks                    | 93        | 9%      |
| Broadcom                        | 49        | 4.74%   |
| Lite-On Technology              | 45        | 4.36%   |
| Foxconn / Hon Hai               | 36        | 3.48%   |
| Apple                           | 24        | 2.32%   |
| Toshiba                         | 23        | 2.23%   |
| Realtek                         | 23        | 2.23%   |
| Ralink                          | 21        | 2.03%   |
| Cambridge Silicon Radio         | 15        | 1.45%   |
| Dell                            | 13        | 1.26%   |
| Hewlett-Packard                 | 11        | 1.06%   |
| ASUSTek Computer                | 11        | 1.06%   |
| MediaTek                        | 5         | 0.48%   |
| Ralink Technology               | 3         | 0.29%   |
| Foxconn International           | 3         | 0.29%   |
| Alps Electric                   | 3         | 0.29%   |
| Qcom                            | 1         | 0.1%    |
| Marvell Semiconductor           | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 144       | 13.93%  |
| Intel AX201 Bluetooth                               | 100       | 9.67%   |
| Realtek Bluetooth Radio                             | 84        | 8.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 70        | 6.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 51        | 4.93%   |
| Intel AX200 Bluetooth                               | 37        | 3.58%   |
| Intel Bluetooth Device                              | 32        | 3.09%   |
| IMC Networks Bluetooth Radio                        | 32        | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 2.22%   |
| Realtek 802.11ac WLAN Adapter                       | 23        | 2.22%   |
| Ralink RT3290 Bluetooth                             | 21        | 2.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.93%   |
| IMC Networks Bluetooth Device                       | 17        | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 1.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 1.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 14        | 1.35%   |
| Apple Bluetooth Host Controller                     | 14        | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.26%   |
| Lite-On Bluetooth Device                            | 13        | 1.26%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 12        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.16%   |
| IMC Networks Bluetooth USB Host Controller          | 12        | 1.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.06%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 11        | 1.06%   |
| IMC Networks Wireless_Device                        | 10        | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 10        | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 0.87%   |
| Apple Bluetooth USB Host Controller                 | 9         | 0.87%   |
| IMC Networks Bluetooth                              | 8         | 0.77%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 8         | 0.77%   |
| ASUS BT-253 Bluetooth Adapter                       | 7         | 0.68%   |
| Lite-On Wireless_Device                             | 6         | 0.58%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.58%   |
| Toshiba Askey Bluetooth Module                      | 5         | 0.48%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.48%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 989       | 63.48%  |
| AMD                                          | 269       | 17.27%  |
| Nvidia                                       | 244       | 15.66%  |
| Silicon Integrated Systems [SiS]             | 11        | 0.71%   |
| C-Media Electronics                          | 5         | 0.32%   |
| Kingston Technology                          | 4         | 0.26%   |
| Barco Display Systems                        | 4         | 0.26%   |
| Apple                                        | 4         | 0.26%   |
| Realtek Semiconductor                        | 3         | 0.19%   |
| Logitech                                     | 3         | 0.19%   |
| LG Electronics                               | 2         | 0.13%   |
| GYROCOM C&C                                  | 2         | 0.13%   |
| GN Netcom                                    | 2         | 0.13%   |
| DSEA A/S                                     | 2         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| Yamaha                                       | 1         | 0.06%   |
| Trust                                        | 1         | 0.06%   |
| Texas Instruments                            | 1         | 0.06%   |
| Tenx Technology                              | 1         | 0.06%   |
| Hewlett-Packard                              | 1         | 0.06%   |
| Google                                       | 1         | 0.06%   |
| Generalplus Technology                       | 1         | 0.06%   |
| DigiTech                                     | 1         | 0.06%   |
| Creative Technology                          | 1         | 0.06%   |
| CMX Systems                                  | 1         | 0.06%   |
| BEHRINGER International                      | 1         | 0.06%   |
| Audient                                      | 1         | 0.06%   |
| A4Tech                                       | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 155       | 8.2%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 134       | 7.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 106       | 5.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 85        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 84        | 4.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 63        | 3.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 53        | 2.8%    |
| Intel 8 Series HD Audio Controller                                                                | 53        | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 52        | 2.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 48        | 2.54%   |
| Intel Broadwell-U Audio Controller                                                                | 44        | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 43        | 2.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 42        | 2.22%   |
| Intel Comet Lake PCH cAVS                                                                         | 41        | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 36        | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33        | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 33        | 1.75%   |
| Intel CM238 HD Audio Controller                                                                   | 31        | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 29        | 1.53%   |
| AMD FCH Azalia Controller                                                                         | 29        | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 26        | 1.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 26        | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 1.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 23        | 1.22%   |
| Nvidia Audio device                                                                               | 22        | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 0.9%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 16        | 0.85%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 16        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 14        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 14        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 0.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 13        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 252       | 31.11%  |
| SK hynix            | 163       | 20.12%  |
| Kingston            | 97        | 11.98%  |
| Micron Technology   | 87        | 10.74%  |
| Unknown             | 56        | 6.91%   |
| Crucial             | 39        | 4.81%   |
| A-DATA Technology   | 21        | 2.59%   |
| Ramaxel Technology  | 20        | 2.47%   |
| Nanya Technology    | 14        | 1.73%   |
| Elpida              | 8         | 0.99%   |
| Corsair             | 8         | 0.99%   |
| Unknown             | 5         | 0.62%   |
| Unknown (ABCD)      | 4         | 0.49%   |
| Transcend           | 4         | 0.49%   |
| Timetec             | 4         | 0.49%   |
| Goldkey             | 3         | 0.37%   |
| G.Skill             | 3         | 0.37%   |
| Apacer              | 3         | 0.37%   |
| Team                | 2         | 0.25%   |
| ChangXin Memory     | 2         | 0.25%   |
| Unknown (F288)      | 1         | 0.12%   |
| Unknown (0x4509)    | 1         | 0.12%   |
| Unknown (0B38)      | 1         | 0.12%   |
| Unifosa             | 1         | 0.12%   |
| pqi                 | 1         | 0.12%   |
| Patriot             | 1         | 0.12%   |
| Lexar Co Limited    | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| Hikvision           | 1         | 0.12%   |
| ff                  | 1         | 0.12%   |
| Avant               | 1         | 0.12%   |
| ASint Technology    | 1         | 0.12%   |
| AMD                 | 1         | 0.12%   |
| 4ea5                | 1         | 0.12%   |
| 48spaces            | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 17        | 1.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 13        | 1.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 12        | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 12        | 1.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 11        | 1.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 11        | 1.28%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 11        | 1.28%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 9         | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 9         | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 8         | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 8         | 0.93%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 7         | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 7         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 7         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 7         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 7         | 0.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 7         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR3                           | 6         | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 6         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 6         | 0.7%    |
| Crucial RAM CT8G4SFS8266.M8FD 8192MB SODIMM DDR4 2667MT/s    | 6         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2                           | 5         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 5         | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s     | 5         | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 5         | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 5         | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 5         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s  | 5         | 0.58%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 5         | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 5         | 0.58%   |
| Unknown                                                      | 5         | 0.58%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 4         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 4         | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 4         | 0.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 4         | 0.47%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s       | 4         | 0.47%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s        | 4         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 355       | 52.51%  |
| DDR3    | 219       | 32.4%   |
| LPDDR4  | 28        | 4.14%   |
| DDR2    | 21        | 3.11%   |
| LPDDR3  | 16        | 2.37%   |
| SDRAM   | 14        | 2.07%   |
| DDR5    | 8         | 1.18%   |
| DDR     | 7         | 1.04%   |
| LPDDR5  | 3         | 0.44%   |
| DRAM    | 3         | 0.44%   |
| Unknown | 2         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 603       | 89.87%  |
| Row Of Chips | 61        | 9.09%   |
| Unknown      | 4         | 0.6%    |
| DIMM         | 2         | 0.3%    |
| Chip         | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 307       | 40.88%  |
| 4096    | 228       | 30.36%  |
| 16384   | 85        | 11.32%  |
| 2048    | 81        | 10.79%  |
| 1024    | 24        | 3.2%    |
| 32768   | 21        | 2.8%    |
| 512     | 2         | 0.27%   |
| 1536    | 1         | 0.13%   |
| 256     | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 160       | 22.16%  |
| 3200    | 155       | 21.47%  |
| 1600    | 151       | 20.91%  |
| 2400    | 60        | 8.31%   |
| 1334    | 35        | 4.85%   |
| 2133    | 32        | 4.43%   |
| 1333    | 22        | 3.05%   |
| Unknown | 22        | 3.05%   |
| 667     | 15        | 2.08%   |
| 4199    | 12        | 1.66%   |
| 1067    | 12        | 1.66%   |
| 4800    | 8         | 1.11%   |
| 4266    | 6         | 0.83%   |
| 4267    | 5         | 0.69%   |
| 800     | 5         | 0.69%   |
| 8400    | 3         | 0.42%   |
| 3266    | 3         | 0.42%   |
| 1867    | 3         | 0.42%   |
| 6400    | 2         | 0.28%   |
| 3733    | 2         | 0.28%   |
| 1066    | 2         | 0.28%   |
| 533     | 2         | 0.28%   |
| 5500    | 1         | 0.14%   |
| 2048    | 1         | 0.14%   |
| 1866    | 1         | 0.14%   |
| 1639    | 1         | 0.14%   |
| 975     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 33.33%  |
| Canon               | 4         | 33.33%  |
| Seiko Epson         | 2         | 16.67%  |
| Samsung Electronics | 1         | 8.33%   |
| QinHeng Electronics | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Officejet 4500 G510g-m            | 2         | 16.67%  |
| Canon LBP6030w/6018w                 | 2         | 16.67%  |
| Seiko Epson L3110 Series             | 1         | 8.33%   |
| Seiko Epson FX-2190IIN               | 1         | 8.33%   |
| Samsung ML-216x Series Laser Printer | 1         | 8.33%   |
| QinHeng CH340S                       | 1         | 8.33%   |
| HP DeskJet 2600 series               | 1         | 8.33%   |
| HP Deskjet 1050 J410                 | 1         | 8.33%   |
| Canon PIXMA MX340                    | 1         | 8.33%   |
| Canon LBP6020                        | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 278       | 24.19%  |
| IMC Networks                           | 139       | 12.1%   |
| Realtek Semiconductor                  | 109       | 9.49%   |
| Bison Electronics                      | 99        | 8.62%   |
| Microdia                               | 75        | 6.53%   |
| Quanta                                 | 68        | 5.92%   |
| Cheng Uei Precision Industry (Foxlink) | 63        | 5.48%   |
| Sunplus Innovation Technology          | 43        | 3.74%   |
| Syntek                                 | 36        | 3.13%   |
| Suyin                                  | 34        | 2.96%   |
| Apple                                  | 27        | 2.35%   |
| Silicon Motion                         | 22        | 1.91%   |
| Luxvisions Innotech Limited            | 21        | 1.83%   |
| Acer                                   | 18        | 1.57%   |
| Lite-On Technology                     | 17        | 1.48%   |
| Alcor Micro                            | 17        | 1.48%   |
| Ricoh                                  | 12        | 1.04%   |
| Importek                               | 8         | 0.7%    |
| Z-Star Microelectronics                | 7         | 0.61%   |
| ALi                                    | 7         | 0.61%   |
| Samsung Electronics                    | 5         | 0.44%   |
| Sonix Technology                       | 4         | 0.35%   |
| Logitech                               | 4         | 0.35%   |
| SunplusIT                              | 3         | 0.26%   |
| Lenovo                                 | 3         | 0.26%   |
| HYGD-220628-A                          | 3         | 0.26%   |
| Foxconn / Hon Hai                      | 3         | 0.26%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Primax Electronics                     | 2         | 0.17%   |
| LG Electronics                         | 2         | 0.17%   |
| DigiTech                               | 2         | 0.17%   |
| Tripath Technology                     | 1         | 0.09%   |
| ShineTech                              | 1         | 0.09%   |
| Shine-optics                           | 1         | 0.09%   |
| Philips (or NXP)                       | 1         | 0.09%   |
| Novatek Microelectronics               | 1         | 0.09%   |
| Nokia Mobile Phones                    | 1         | 0.09%   |
| MacroSilicon                           | 1         | 0.09%   |
| Intel                                  | 1         | 0.09%   |
| icSpring                               | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                     | 38        | 3.3%    |
| Microdia Integrated_Webcam_HD                                 | 36        | 3.13%   |
| IMC Networks Integrated Camera                                | 34        | 2.95%   |
| Chicony HD Webcam                                             | 34        | 2.95%   |
| Bison Integrated Camera                                       | 28        | 2.43%   |
| IMC Networks USB2.0 VGA UVC WebCam                            | 27        | 2.34%   |
| Realtek Integrated_Webcam_HD                                  | 25        | 2.17%   |
| IMC Networks USB2.0 HD UVC WebCam                             | 24        | 2.08%   |
| Syntek Integrated Camera                                      | 19        | 1.65%   |
| Chicony USB2.0 VGA UVC WebCam                                 | 19        | 1.65%   |
| Quanta HD User Facing                                         | 14        | 1.22%   |
| IMC Networks HD Camera                                        | 14        | 1.22%   |
| Bison HD Webcam                                               | 14        | 1.22%   |
| Realtek USB2.0 VGA UVC WebCam                                 | 13        | 1.13%   |
| Chicony USB2.0 HD UVC WebCam                                  | 13        | 1.13%   |
| Chicony USB2.0 Camera                                         | 13        | 1.13%   |
| Chicony USB 2.0 Camera                                        | 12        | 1.04%   |
| Bison BisonCam, NB Pro                                        | 12        | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                               | 11        | 0.95%   |
| Chicony HP HD Camera                                          | 11        | 0.95%   |
| Sunplus Integrated_Webcam_HD                                  | 10        | 0.87%   |
| Chicony Lenovo EasyCamera                                     | 10        | 0.87%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                               | 10        | 0.87%   |
| Realtek USB Camera                                            | 9         | 0.78%   |
| Lite-On Integrated Camera                                     | 9         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD       | 9         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera              | 9         | 0.78%   |
| Syntek EasyCamera                                             | 8         | 0.69%   |
| Realtek Integrated Webcam                                     | 8         | 0.69%   |
| Quanta USB HD Webcam                                          | 8         | 0.69%   |
| Quanta ov9734_techfront_camera                                | 8         | 0.69%   |
| Quanta HP TrueVision HD Camera                                | 8         | 0.69%   |
| Chicony EasyCamera                                            | 8         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 8         | 0.69%   |
| Bison SunplusIT Integrated Camera                             | 8         | 0.69%   |
| Bison BisonCam,NB Pro                                         | 8         | 0.69%   |
| Apple FaceTime HD Camera                                      | 8         | 0.69%   |
| Sunplus Asus Webcam                                           | 7         | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 7         | 0.61%   |
| IMC Networks ov9734_azurewave_camera                          | 7         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Shenzhen Goodix Technology         | 61        | 36.31%  |
| Synaptics                          | 36        | 21.43%  |
| Validity Sensors                   | 34        | 20.24%  |
| LighTuning Technology              | 14        | 8.33%   |
| AuthenTec                          | 9         | 5.36%   |
| Upek                               | 8         | 4.76%   |
| Elan Microelectronics              | 5         | 2.98%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                             | 47        | 27.98%  |
| Shenzhen Goodix Fingerprint Reader                              | 13        | 7.74%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 10        | 5.95%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 8         | 4.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 8         | 4.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 6         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 6         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 6         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 2.98%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 2.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 5         | 2.98%   |
| Validity Sensors Fingerprint scanner                            | 4         | 2.38%   |
| Synaptics WBDI                                                  | 4         | 2.38%   |
| Synaptics  WBDI                                                 | 4         | 2.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 3         | 1.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 3         | 1.79%   |
| Elan ELAN:Fingerprint                                           | 3         | 1.79%   |
| AuthenTec AES2810                                               | 3         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 1.79%   |
| AuthenTec AES1600                                               | 3         | 1.79%   |
| Validity Sensors VFS491                                         | 2         | 1.19%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 1.19%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 1.19%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 1.19%   |
| Elan ELAN:ARM-M4                                                | 2         | 1.19%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 0.6%    |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 0.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 0.6%    |
| Synaptics UWP WBDI Device                                       | 1         | 0.6%    |
| Synaptics UWP WBDI                                              | 1         | 0.6%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 0.6%    |
| Shenzhen Goodix FingerPrint                                     | 1         | 0.6%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 0.6%    |
| LighTuning Fingerprint Reader                                   | 1         | 0.6%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 18        | 45%     |
| Alcor Micro           | 13        | 32.5%   |
| Advanced Card Systems | 3         | 7.5%    |
| Upek                  | 2         | 5%      |
| O2 Micro              | 2         | 5%      |
| Lenovo                | 1         | 2.5%    |
| Gemalto (was Gemplus) | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 32.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 17.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 15%     |
| Broadcom 58200                                                               | 3         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5%      |
| Broadcom 5880                                                                | 2         | 5%      |
| Advanced Card Systems ACR39U                                                 | 2         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.5%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.5%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 826       | 63.78%  |
| 1     | 365       | 28.19%  |
| 2     | 88        | 6.8%    |
| 3     | 8         | 0.62%   |
| 4     | 5         | 0.39%   |
| 6     | 2         | 0.15%   |
| 5     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 169       | 29.65%  |
| Fingerprint reader       | 168       | 29.47%  |
| Net/wireless             | 46        | 8.07%   |
| Chipcard                 | 34        | 5.96%   |
| Camera                   | 34        | 5.96%   |
| Multimedia controller    | 32        | 5.61%   |
| Bluetooth                | 31        | 5.44%   |
| Communication controller | 20        | 3.51%   |
| Net/ethernet             | 11        | 1.93%   |
| Storage                  | 9         | 1.58%   |
| Sound                    | 9         | 1.58%   |
| Flash memory             | 2         | 0.35%   |
| Card reader              | 2         | 0.35%   |
| Wireless                 | 1         | 0.18%   |
| Network                  | 1         | 0.18%   |
| Modem                    | 1         | 0.18%   |

