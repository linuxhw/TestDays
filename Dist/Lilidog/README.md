Lilidog - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lilidog.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lilidog/Desktop/README.md) and [notebooks](/Dist/Lilidog/Notebook/README.md).

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

Total: 134

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| IBM           | ThinkPad X40 2372CTO        | Notebook    | [a832f7a219](https://linux-hardware.org/?probe=a832f7a219) | Dec 01, 2025 |
| Dell          | Inspiron 3793               | Notebook    | [bb1769967f](https://linux-hardware.org/?probe=bb1769967f) | Sep 12, 2025 |
| Apple         | MacBookPro5,5               | Notebook    | [cb373add53](https://linux-hardware.org/?probe=cb373add53) | Aug 18, 2025 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [d21316063c](https://linux-hardware.org/?probe=d21316063c) | Jul 24, 2025 |
| HP            | Laptop 17-cp3xxx            | Notebook    | [ff1918b4ca](https://linux-hardware.org/?probe=ff1918b4ca) | Jul 19, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [f0e44791fa](https://linux-hardware.org/?probe=f0e44791fa) | Jul 16, 2025 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [7bb3e85cb0](https://linux-hardware.org/?probe=7bb3e85cb0) | Jun 18, 2025 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [9b71167788](https://linux-hardware.org/?probe=9b71167788) | May 28, 2025 |
| Fujitsu       | FJNB037                     | Desktop     | [2ceab1a853](https://linux-hardware.org/?probe=2ceab1a853) | May 18, 2025 |
| Acer          | Aspire A517-51G             | Notebook    | [655e1be608](https://linux-hardware.org/?probe=655e1be608) | May 16, 2025 |
| Dell          | 0NNNCT A01                  | Desktop     | [13c4e5ccdc](https://linux-hardware.org/?probe=13c4e5ccdc) | May 08, 2025 |
| ISONIC        | ISO-A1005                   | Notebook    | [cd33e5e059](https://linux-hardware.org/?probe=cd33e5e059) | Apr 28, 2025 |
| Dell          | 0GX832 A01                  | Desktop     | [f4982347a9](https://linux-hardware.org/?probe=f4982347a9) | Apr 20, 2025 |
| ASUSTek       | M51BC                       | Desktop     | [ae7ae68e47](https://linux-hardware.org/?probe=ae7ae68e47) | Apr 05, 2025 |
| Dell          | 0M5DCD A00                  | Desktop     | [2105132fb3](https://linux-hardware.org/?probe=2105132fb3) | Mar 31, 2025 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [c009571cd5](https://linux-hardware.org/?probe=c009571cd5) | Feb 18, 2025 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [f874682cbc](https://linux-hardware.org/?probe=f874682cbc) | Feb 06, 2025 |
| Lenovo        | ThinkPad T430 2347AY1       | Notebook    | [43852e7efc](https://linux-hardware.org/?probe=43852e7efc) | Feb 05, 2025 |
| Lenovo        | ThinkPad T430 2347AY1       | Notebook    | [18582f3738](https://linux-hardware.org/?probe=18582f3738) | Feb 05, 2025 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0de40805d4](https://linux-hardware.org/?probe=0de40805d4) | Jan 22, 2025 |
| Google        | Gnawty                      | Notebook    | [a49ee8c814](https://linux-hardware.org/?probe=a49ee8c814) | Jan 22, 2025 |
| AZW           | S5 V01                      | Mini pc     | [21aaa2d92a](https://linux-hardware.org/?probe=21aaa2d92a) | Jan 05, 2025 |
| Acer          | Nitro AN515-54              | Notebook    | [071a512314](https://linux-hardware.org/?probe=071a512314) | Dec 17, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6c0c6a08b7](https://linux-hardware.org/?probe=6c0c6a08b7) | Dec 15, 2024 |
| Samsung       | 750QFG                      | Convertible | [1234d66aee](https://linux-hardware.org/?probe=1234d66aee) | Dec 13, 2024 |
| Lenovo        | ThinkPad X131e 33722WU      | Notebook    | [1e06ef890d](https://linux-hardware.org/?probe=1e06ef890d) | Dec 04, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [963aca3a61](https://linux-hardware.org/?probe=963aca3a61) | Nov 22, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [022c2f84fc](https://linux-hardware.org/?probe=022c2f84fc) | Nov 10, 2024 |
| Lenovo        | 3000 G410                   | Notebook    | [cf7fd7d924](https://linux-hardware.org/?probe=cf7fd7d924) | Oct 28, 2024 |
| Lenovo        | 3000 G410                   | Notebook    | [294011f6db](https://linux-hardware.org/?probe=294011f6db) | Oct 28, 2024 |
| Acer          | Aspire XC-330               | Desktop     | [25b998dd59](https://linux-hardware.org/?probe=25b998dd59) | Oct 06, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [7df5552411](https://linux-hardware.org/?probe=7df5552411) | Sep 11, 2024 |
| HP            | 2B2C                        | Desktop     | [8cc39031cb](https://linux-hardware.org/?probe=8cc39031cb) | Aug 29, 2024 |
| PC Special... | P65_67RSRP                  | Notebook    | [45ef7521c8](https://linux-hardware.org/?probe=45ef7521c8) | Aug 18, 2024 |
| Dell          | Latitude E6530              | Notebook    | [829814779a](https://linux-hardware.org/?probe=829814779a) | Jul 25, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9b33f3fab6](https://linux-hardware.org/?probe=9b33f3fab6) | Jul 14, 2024 |
| HP            | 0B54h D                     | Desktop     | [24348ad5a4](https://linux-hardware.org/?probe=24348ad5a4) | Jun 25, 2024 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [9cc57cd7ff](https://linux-hardware.org/?probe=9cc57cd7ff) | Jun 20, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [1fc3d8e29b](https://linux-hardware.org/?probe=1fc3d8e29b) | Jun 03, 2024 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [760c95f432](https://linux-hardware.org/?probe=760c95f432) | May 15, 2024 |
| Matsushita... | CF-52GDN30AG                | Notebook    | [19d09b44b2](https://linux-hardware.org/?probe=19d09b44b2) | May 11, 2024 |
| Toshiba       | Satellite P200              | Notebook    | [f9f88ee996](https://linux-hardware.org/?probe=f9f88ee996) | May 03, 2024 |
| Acer          | Aspire E5-573               | Notebook    | [1060cb82e8](https://linux-hardware.org/?probe=1060cb82e8) | May 01, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [6d235ddbaf](https://linux-hardware.org/?probe=6d235ddbaf) | Apr 29, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [419fb8dfca](https://linux-hardware.org/?probe=419fb8dfca) | Apr 28, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a154dad3b7](https://linux-hardware.org/?probe=a154dad3b7) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6006e10996](https://linux-hardware.org/?probe=6006e10996) | Apr 20, 2024 |
| HP            | 1825                        | Desktop     | [3d90cc7481](https://linux-hardware.org/?probe=3d90cc7481) | Mar 31, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [14060f87a1](https://linux-hardware.org/?probe=14060f87a1) | Mar 12, 2024 |
| HP            | 630                         | Notebook    | [4aee0c5868](https://linux-hardware.org/?probe=4aee0c5868) | Mar 10, 2024 |
| HP            | 510 Notebook PC (RU962AA... | Notebook    | [94571f879e](https://linux-hardware.org/?probe=94571f879e) | Mar 02, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [207f92c903](https://linux-hardware.org/?probe=207f92c903) | Feb 18, 2024 |
| Dell          | Latitude E5420              | Notebook    | [1cdafef139](https://linux-hardware.org/?probe=1cdafef139) | Feb 07, 2024 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [1d8dbbd8af](https://linux-hardware.org/?probe=1d8dbbd8af) | Jan 29, 2024 |
| Acer          | Aspire E1-470               | Notebook    | [732a523ea8](https://linux-hardware.org/?probe=732a523ea8) | Jan 28, 2024 |
| ASUSTek       | X550VC                      | Notebook    | [90ebdf4197](https://linux-hardware.org/?probe=90ebdf4197) | Jan 22, 2024 |
| HP            | ProBook 6560b               | Notebook    | [6d2bbcc556](https://linux-hardware.org/?probe=6d2bbcc556) | Jan 21, 2024 |
| HP            | 1998                        | Desktop     | [b193235ba4](https://linux-hardware.org/?probe=b193235ba4) | Jan 17, 2024 |
| Lenovo        | ThinkPad T430s 2356GUU      | Notebook    | [df4e542b16](https://linux-hardware.org/?probe=df4e542b16) | Jan 15, 2024 |
| PC Special... | P65_67RSRP                  | Notebook    | [f2af84bdfc](https://linux-hardware.org/?probe=f2af84bdfc) | Jan 13, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [6d15625c9b](https://linux-hardware.org/?probe=6d15625c9b) | Jan 05, 2024 |
| Lenovo        | ThinkPad X280 20KES63G00    | Notebook    | [a5688cc794](https://linux-hardware.org/?probe=a5688cc794) | Dec 24, 2023 |
| Toshiba       | Satellite Pro L450          | Notebook    | [8da0c619f3](https://linux-hardware.org/?probe=8da0c619f3) | Dec 24, 2023 |
| Acer          | AOD270                      | Notebook    | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [5bf09e9b79](https://linux-hardware.org/?probe=5bf09e9b79) | Nov 29, 2023 |
| Sony          | VPCF23P1E                   | Notebook    | [0bfcf70f1a](https://linux-hardware.org/?probe=0bfcf70f1a) | Nov 21, 2023 |
| Google        | Sand                        | Notebook    | [97e4755fe5](https://linux-hardware.org/?probe=97e4755fe5) | Nov 07, 2023 |
| Dell          | Inspiron 1318               | Notebook    | [2ac81db219](https://linux-hardware.org/?probe=2ac81db219) | Oct 14, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [5dab721f9a](https://linux-hardware.org/?probe=5dab721f9a) | Aug 21, 2023 |
| HP            | 435                         | Notebook    | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [6f8ca5724f](https://linux-hardware.org/?probe=6f8ca5724f) | Aug 10, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Google        | Auron_Yuna                  | Notebook    | [abff7f6ed0](https://linux-hardware.org/?probe=abff7f6ed0) | Jul 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9d0c95f893](https://linux-hardware.org/?probe=9d0c95f893) | Jul 18, 2023 |
| Dell          | Latitude 7414               | Notebook    | [184c56a43a](https://linux-hardware.org/?probe=184c56a43a) | Jul 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| TUXEDO        | N8xEJEK                     | Notebook    | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Google        | Sand                        | Notebook    | [e6d70635d6](https://linux-hardware.org/?probe=e6d70635d6) | May 30, 2023 |
| HP            | G62                         | Notebook    | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [bd50784a0b](https://linux-hardware.org/?probe=bd50784a0b) | May 05, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4d91f9900d](https://linux-hardware.org/?probe=4d91f9900d) | Apr 25, 2023 |
| Dell          | 0GM819                      | Desktop     | [744413006e](https://linux-hardware.org/?probe=744413006e) | Apr 20, 2023 |
| Google        | Sand                        | Notebook    | [044ac39e57](https://linux-hardware.org/?probe=044ac39e57) | Apr 11, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [d985b7fa11](https://linux-hardware.org/?probe=d985b7fa11) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [061b0673b4](https://linux-hardware.org/?probe=061b0673b4) | Mar 12, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [266ef88c0c](https://linux-hardware.org/?probe=266ef88c0c) | Jan 25, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [910de59ed9](https://linux-hardware.org/?probe=910de59ed9) | Jan 25, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [d50f9357b4](https://linux-hardware.org/?probe=d50f9357b4) | Jan 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [fece850cae](https://linux-hardware.org/?probe=fece850cae) | Jan 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a16b955eed](https://linux-hardware.org/?probe=a16b955eed) | Jan 15, 2023 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| HP            | 89E8 0100                   | All in one  | [0e9567b0a5](https://linux-hardware.org/?probe=0e9567b0a5) | Dec 21, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9b1f8e9a10](https://linux-hardware.org/?probe=9b1f8e9a10) | Dec 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Dell          | Latitude 7390               | Notebook    | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| HP            | 805B                        | Desktop     | [111fb196ff](https://linux-hardware.org/?probe=111fb196ff) | Nov 16, 2022 |
| Dell          | 0DF42J A00                  | Desktop     | [52e8355edf](https://linux-hardware.org/?probe=52e8355edf) | Nov 12, 2022 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [b74e119c7e](https://linux-hardware.org/?probe=b74e119c7e) | Nov 05, 2022 |
| Biostar       | A320MH                      | Desktop     | [d01d91204f](https://linux-hardware.org/?probe=d01d91204f) | Oct 27, 2022 |
| Biostar       | A320MH                      | Desktop     | [768dff7065](https://linux-hardware.org/?probe=768dff7065) | Oct 27, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| Lenovo        | 374F SDK0R32862 WIN 3258... | Desktop     | [b30ac8d979](https://linux-hardware.org/?probe=b30ac8d979) | Oct 05, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [8e80ccea19](https://linux-hardware.org/?probe=8e80ccea19) | Oct 01, 2022 |
| Acer          | V5-131                      | Notebook    | [7a218d1ae7](https://linux-hardware.org/?probe=7a218d1ae7) | Sep 14, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [66f5acc518](https://linux-hardware.org/?probe=66f5acc518) | Sep 10, 2022 |
| Dell          | 0GM819                      | Desktop     | [7778e245a9](https://linux-hardware.org/?probe=7778e245a9) | Sep 06, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [209e0387a9](https://linux-hardware.org/?probe=209e0387a9) | Aug 27, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [5bfd5ddd59](https://linux-hardware.org/?probe=5bfd5ddd59) | Aug 26, 2022 |
| HP            | 805B                        | Desktop     | [602a9470ab](https://linux-hardware.org/?probe=602a9470ab) | Aug 22, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b7173a46ac](https://linux-hardware.org/?probe=b7173a46ac) | Aug 21, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [c9be76cad8](https://linux-hardware.org/?probe=c9be76cad8) | Aug 21, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [5846b57c77](https://linux-hardware.org/?probe=5846b57c77) | Aug 09, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [d5f490187d](https://linux-hardware.org/?probe=d5f490187d) | Jul 19, 2022 |
| Inventec      | 0W63N3 A01                  | Mini pc     | [de75a91d9f](https://linux-hardware.org/?probe=de75a91d9f) | Jul 09, 2022 |
| Acer          | V5-131                      | Notebook    | [620f2657d4](https://linux-hardware.org/?probe=620f2657d4) | Jul 07, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| Panasonic     | CF-31ATXAX1M                | Notebook    | [46be7cc40c](https://linux-hardware.org/?probe=46be7cc40c) | Jul 06, 2022 |
| Acer          | AOD255E                     | Notebook    | [01c9e4194b](https://linux-hardware.org/?probe=01c9e4194b) | Jul 06, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Acer          | AOD255E                     | Notebook    | [1737f8b906](https://linux-hardware.org/?probe=1737f8b906) | Jun 26, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [f8a734d114](https://linux-hardware.org/?probe=f8a734d114) | Jun 20, 2022 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [8fb623d313](https://linux-hardware.org/?probe=8fb623d313) | Jun 17, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [89a074e539](https://linux-hardware.org/?probe=89a074e539) | Jun 02, 2022 |
| eMachines     | EL1352                      | Desktop     | [562e729c18](https://linux-hardware.org/?probe=562e729c18) | May 15, 2022 |
| HP            | 212B                        | Desktop     | [d6deb6ed52](https://linux-hardware.org/?probe=d6deb6ed52) | May 04, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [ce7e91802e](https://linux-hardware.org/?probe=ce7e91802e) | May 03, 2022 |
| HP            | 21EF                        | Desktop     | [f619d0dfc0](https://linux-hardware.org/?probe=f619d0dfc0) | Apr 14, 2022 |
| Dell          | 0HJ054                      | Desktop     | [77ae3bc631](https://linux-hardware.org/?probe=77ae3bc631) | Apr 11, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [3df5028c64](https://linux-hardware.org/?probe=3df5028c64) | Apr 10, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Lilidog 23 | 43        | 38.39%  |
| Lilidog 22 | 40        | 35.71%  |
| Lilidog 12 | 17        | 15.18%  |
| Lilidog 24 | 11        | 9.82%   |
| Lilidog 13 | 1         | 0.89%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 105       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.5.0-0.deb12.4-amd64    | 9         | 7.38%   |
| 5.10.0-16-amd64          | 6         | 4.92%   |
| 6.1.0-9-amd64            | 5         | 4.1%    |
| 5.10.0-18-amd64          | 5         | 4.1%    |
| 5.10.0-15-amd64          | 5         | 4.1%    |
| 6.6.13+bpo-amd64         | 4         | 3.28%   |
| 6.1.0-10-amd64           | 4         | 3.28%   |
| 5.10.0-13-amd64          | 4         | 3.28%   |
| 6.11.5+bpo-amd64         | 3         | 2.46%   |
| 6.1.0-28-amd64           | 3         | 2.46%   |
| 6.1.0-18-amd64           | 3         | 2.46%   |
| 5.10.0-21-amd64          | 3         | 2.46%   |
| 5.10.0-20-amd64          | 3         | 2.46%   |
| 6.7.12+bpo-amd64         | 2         | 1.64%   |
| 6.5.0-0.deb12.1-amd64    | 2         | 1.64%   |
| 6.12.9+bpo-amd64         | 2         | 1.64%   |
| 6.12.32+bpo-amd64        | 2         | 1.64%   |
| 6.12.12+bpo-amd64        | 2         | 1.64%   |
| 6.10.11+bpo-amd64        | 2         | 1.64%   |
| 6.1.0-7-amd64            | 2         | 1.64%   |
| 6.1.0-25-amd64           | 2         | 1.64%   |
| 6.1.0-23-amd64           | 2         | 1.64%   |
| 6.1.0-21-amd64           | 2         | 1.64%   |
| 6.1.0-20-amd64           | 2         | 1.64%   |
| 6.1.0-16-amd64           | 2         | 1.64%   |
| 6.1.0-11-amd64           | 2         | 1.64%   |
| 6.0.8-x64v1-xanmod1      | 2         | 1.64%   |
| 5.10.0-14-amd64          | 2         | 1.64%   |
| 6.8.9-5-liquorix-amd64   | 1         | 0.82%   |
| 6.4.5-1-liquorix-amd64   | 1         | 0.82%   |
| 6.4.0-0.deb12.2-amd64    | 1         | 0.82%   |
| 6.2.12-x64v1-xanmod1     | 1         | 0.82%   |
| 6.2.11-x64v1-xanmod1     | 1         | 0.82%   |
| 6.13.8-4-liquorix-amd64  | 1         | 0.82%   |
| 6.12.43+deb13-amd64      | 1         | 0.82%   |
| 6.12.1-1-liquorix-amd64  | 1         | 0.82%   |
| 6.11.10+bpo-amd64        | 1         | 0.82%   |
| 6.1.0-7.2-liquorix-amd64 | 1         | 0.82%   |
| 6.1.0-38-amd64           | 1         | 0.82%   |
| 6.1.0-37-amd64           | 1         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 42        | 35.29%  |
| 5.10.0  | 29        | 24.37%  |
| 6.5.0   | 11        | 9.24%   |
| 6.6.13  | 4         | 3.36%   |
| 6.0.0   | 4         | 3.36%   |
| 6.11.5  | 3         | 2.52%   |
| 6.7.12  | 2         | 1.68%   |
| 6.12.9  | 2         | 1.68%   |
| 6.12.32 | 2         | 1.68%   |
| 6.12.12 | 2         | 1.68%   |
| 6.10.11 | 2         | 1.68%   |
| 6.0.8   | 2         | 1.68%   |
| 5.19.0  | 2         | 1.68%   |
| 6.8.9   | 1         | 0.84%   |
| 6.4.5   | 1         | 0.84%   |
| 6.4.0   | 1         | 0.84%   |
| 6.2.12  | 1         | 0.84%   |
| 6.2.11  | 1         | 0.84%   |
| 6.13.8  | 1         | 0.84%   |
| 6.12.43 | 1         | 0.84%   |
| 6.12.1  | 1         | 0.84%   |
| 6.11.10 | 1         | 0.84%   |
| 6.0.10  | 1         | 0.84%   |
| 5.18.0  | 1         | 0.84%   |
| 5.17.0  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 42        | 35.59%  |
| 5.10    | 29        | 24.58%  |
| 6.5     | 11        | 9.32%   |
| 6.12    | 7         | 5.93%   |
| 6.0     | 7         | 5.93%   |
| 6.6     | 4         | 3.39%   |
| 6.11    | 4         | 3.39%   |
| 6.7     | 2         | 1.69%   |
| 6.4     | 2         | 1.69%   |
| 6.2     | 2         | 1.69%   |
| 6.10    | 2         | 1.69%   |
| 5.19    | 2         | 1.69%   |
| 6.8     | 1         | 0.85%   |
| 6.13    | 1         | 0.85%   |
| 5.18    | 1         | 0.85%   |
| 5.17    | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 96.19%  |
| i686   | 4         | 3.81%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 65        | 58.56%  |
| openbox          | 42        | 37.84%  |
| i3               | 2         | 1.8%    |
| XFCE             | 1         | 0.9%    |
| dk               | 1         | 0.9%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 105       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 105       | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 63        | 59.43%  |
| de_DE | 7         | 6.6%    |
| es_ES | 5         | 4.72%   |
| pl_PL | 4         | 3.77%   |
| en_GB | 4         | 3.77%   |
| ru_RU | 3         | 2.83%   |
| es_MX | 3         | 2.83%   |
| es_AR | 3         | 2.83%   |
| pt_BR | 2         | 1.89%   |
| es_CO | 2         | 1.89%   |
| en_CA | 2         | 1.89%   |
| it_IT | 1         | 0.94%   |
| fr_FR | 1         | 0.94%   |
| fi_FI | 1         | 0.94%   |
| es_VE | 1         | 0.94%   |
| es_CL | 1         | 0.94%   |
| en_IE | 1         | 0.94%   |
| en_AU | 1         | 0.94%   |
| cs_CZ | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 58        | 55.24%  |
| BIOS | 47        | 44.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 80        | 72.73%  |
| Overlay | 21        | 19.09%  |
| Btrfs   | 8         | 7.27%   |
| Xfs     | 1         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 68        | 63.55%  |
| MBR  | 39        | 36.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 61.82%  |
| Yes       | 42        | 38.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 80%     |
| Yes       | 21        | 20%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 16        | 15.24%  |
| Hewlett-Packard                      | 16        | 15.24%  |
| Dell                                 | 15        | 14.29%  |
| Acer                                 | 12        | 11.43%  |
| ASUSTek Computer                     | 8         | 7.62%   |
| Apple                                | 8         | 7.62%   |
| Toshiba                              | 3         | 2.86%   |
| Google                               | 3         | 2.86%   |
| Gigabyte Technology                  | 3         | 2.86%   |
| Panasonic                            | 2         | 1.9%    |
| TUXEDO                               | 1         | 0.95%   |
| Sony                                 | 1         | 0.95%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.95%   |
| Samsung Electronics                  | 1         | 0.95%   |
| PC Specialist                        | 1         | 0.95%   |
| MSI                                  | 1         | 0.95%   |
| Matsushita Electric Industrial       | 1         | 0.95%   |
| ISONIC                               | 1         | 0.95%   |
| Inventec                             | 1         | 0.95%   |
| Intel                                | 1         | 0.95%   |
| IBM                                  | 1         | 0.95%   |
| GPU Company                          | 1         | 0.95%   |
| Fujitsu                              | 1         | 0.95%   |
| Foxconn                              | 1         | 0.95%   |
| Fanless Mini PC                      | 1         | 0.95%   |
| eMachines                            | 1         | 0.95%   |
| Biostar                              | 1         | 0.95%   |
| BANGHO                               | 1         | 0.95%   |
| Unknown                              | 1         | 0.95%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Acer Aspire E5-573                          | 2         | 1.9%    |
| Acer AOD255E                                | 2         | 1.9%    |
| TUXEDO N8xEJEK                              | 1         | 0.95%   |
| Toshiba Satellite Pro L450                  | 1         | 0.95%   |
| Toshiba Satellite P200                      | 1         | 0.95%   |
| Toshiba PORTEGE Z30-C                       | 1         | 0.95%   |
| Sony VPCF23P1E                              | 1         | 0.95%   |
| Shenzhen Meigao Electronic Equipment UM560  | 1         | 0.95%   |
| Samsung 750QFG                              | 1         | 0.95%   |
| PC Specialist P65_67RSRP                    | 1         | 0.95%   |
| Panasonic CFMX4-1                           | 1         | 0.95%   |
| Panasonic CF-31ATXAX1M                      | 1         | 0.95%   |
| MSI MS-7E06                                 | 1         | 0.95%   |
| Matsushita Electric Industrial CF-52GDN30AG | 1         | 0.95%   |
| Lenovo Yoga Slim 7 14ARE05 82A2             | 1         | 0.95%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.95%   |
| Lenovo ThinkPad X280 20KES63G00             | 1         | 0.95%   |
| Lenovo ThinkPad X131e 33722WU               | 1         | 0.95%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW  | 1         | 0.95%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900    | 1         | 0.95%   |
| Lenovo ThinkPad T430s 2356GUU               | 1         | 0.95%   |
| Lenovo ThinkPad T430 2347AY1                | 1         | 0.95%   |
| Lenovo ThinkPad T400 6474WPU                | 1         | 0.95%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH          | 1         | 0.95%   |
| Lenovo IdeaPad Z460 20059                   | 1         | 0.95%   |
| Lenovo IdeaPad D330-10IGM 81H3              | 1         | 0.95%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 1         | 0.95%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 1         | 0.95%   |
| Lenovo G500 20236                           | 1         | 0.95%   |
| Lenovo 3000 G410                            | 1         | 0.95%   |
| ISONIC ISO-A1005                            | 1         | 0.95%   |
| Inventec Dell Thin Client Desktop 5060      | 1         | 0.95%   |
| Intel NUC11BTMi7                            | 1         | 0.95%   |
| IBM ThinkPad X40 2372CTO                    | 1         | 0.95%   |
| HP Z600 Workstation                         | 1         | 0.95%   |
| HP t520 Flexible Series TC                  | 1         | 0.95%   |
| HP ProBook 6560b                            | 1         | 0.95%   |
| HP ProBook 450 G5                           | 1         | 0.95%   |
| HP Pavilion 11 x360 PC                      | 1         | 0.95%   |
| HP Laptop 17-cp3xxx                         | 1         | 0.95%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 7         | 6.67%   |
| Acer Aspire                                 | 7         | 6.67%   |
| Dell OptiPlex                               | 5         | 4.76%   |
| Dell Latitude                               | 5         | 4.76%   |
| Lenovo IdeaPad                              | 4         | 3.81%   |
| HP EliteDesk                                | 3         | 2.86%   |
| Toshiba Satellite                           | 2         | 1.9%    |
| HP ProBook                                  | 2         | 1.9%    |
| HP Laptop                                   | 2         | 1.9%    |
| Dell Inspiron                               | 2         | 1.9%    |
| ASUS VivoBook                               | 2         | 1.9%    |
| ASUS PRIME                                  | 2         | 1.9%    |
| Acer AOD255E                                | 2         | 1.9%    |
| TUXEDO N8xEJEK                              | 1         | 0.95%   |
| Toshiba PORTEGE                             | 1         | 0.95%   |
| Sony VPCF23P1E                              | 1         | 0.95%   |
| Shenzhen Meigao Electronic Equipment UM560  | 1         | 0.95%   |
| Samsung 750QFG                              | 1         | 0.95%   |
| PC Specialist P65                           | 1         | 0.95%   |
| Panasonic CFMX4-1                           | 1         | 0.95%   |
| Panasonic CF-31ATXAX1M                      | 1         | 0.95%   |
| MSI MS-7E06                                 | 1         | 0.95%   |
| Matsushita Electric Industrial CF-52GDN30AG | 1         | 0.95%   |
| Lenovo Yoga                                 | 1         | 0.95%   |
| Lenovo Y520-15IKBN                          | 1         | 0.95%   |
| Lenovo Legion                               | 1         | 0.95%   |
| Lenovo G500                                 | 1         | 0.95%   |
| Lenovo 3000                                 | 1         | 0.95%   |
| ISONIC ISO-A1005                            | 1         | 0.95%   |
| Inventec Dell                               | 1         | 0.95%   |
| Intel NUC11BTMi7                            | 1         | 0.95%   |
| IBM ThinkPad                                | 1         | 0.95%   |
| HP Z600                                     | 1         | 0.95%   |
| HP t520                                     | 1         | 0.95%   |
| HP Pavilion                                 | 1         | 0.95%   |
| HP G62                                      | 1         | 0.95%   |
| HP All-in-One                               | 1         | 0.95%   |
| HP 630                                      | 1         | 0.95%   |
| HP 510                                      | 1         | 0.95%   |
| HP 435                                      | 1         | 0.95%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 14        | 13.33%  |
| 2018 | 10        | 9.52%   |
| 2012 | 8         | 7.62%   |
| 2011 | 8         | 7.62%   |
| 2017 | 7         | 6.67%   |
| 2022 | 6         | 5.71%   |
| 2021 | 6         | 5.71%   |
| 2014 | 6         | 5.71%   |
| 2007 | 6         | 5.71%   |
| 2019 | 5         | 4.76%   |
| 2015 | 5         | 4.76%   |
| 2013 | 5         | 4.76%   |
| 2016 | 4         | 3.81%   |
| 2008 | 4         | 3.81%   |
| 2020 | 3         | 2.86%   |
| 2009 | 3         | 2.86%   |
| 2023 | 2         | 1.9%    |
| 2006 | 2         | 1.9%    |
| 2024 | 1         | 0.95%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 62        | 59.05%  |
| Desktop     | 32        | 30.48%  |
| Mini pc     | 5         | 4.76%   |
| All in one  | 3         | 2.86%   |
| Tablet      | 2         | 1.9%    |
| Convertible | 1         | 0.95%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 103       | 98.1%   |
| Enabled  | 2         | 1.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 101       | 96.19%  |
| Yes  | 4         | 3.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 29        | 27.1%   |
| 3.01-4.0    | 26        | 24.3%   |
| 16.01-24.0  | 16        | 14.95%  |
| 8.01-16.0   | 11        | 10.28%  |
| 32.01-64.0  | 9         | 8.41%   |
| 1.01-2.0    | 6         | 5.61%   |
| 2.01-3.0    | 4         | 3.74%   |
| 0.51-1.0    | 3         | 2.8%    |
| 24.01-32.0  | 1         | 0.93%   |
| 64.01-256.0 | 1         | 0.93%   |
| 0.01-0.5    | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 59        | 52.68%  |
| 1.01-2.0  | 36        | 32.14%  |
| 2.01-3.0  | 10        | 8.93%   |
| 0.01-0.5  | 4         | 3.57%   |
| 3.01-4.0  | 2         | 1.79%   |
| 8.01-16.0 | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 65.74%  |
| 2      | 22        | 20.37%  |
| 3      | 10        | 9.26%   |
| 4      | 4         | 3.7%    |
| 6      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 68        | 64.15%  |
| Yes       | 38        | 35.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 85.85%  |
| No        | 15        | 14.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 83.81%  |
| No        | 17        | 16.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 56.07%  |
| No        | 47        | 43.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 27.62%  |
| Germany     | 11        | 10.48%  |
| Spain       | 6         | 5.71%   |
| Poland      | 6         | 5.71%   |
| UK          | 5         | 4.76%   |
| Argentina   | 5         | 4.76%   |
| Italy       | 4         | 3.81%   |
| France      | 4         | 3.81%   |
| Netherlands | 3         | 2.86%   |
| Canada      | 3         | 2.86%   |
| Romania     | 2         | 1.9%    |
| Mexico      | 2         | 1.9%    |
| Indonesia   | 2         | 1.9%    |
| Finland     | 2         | 1.9%    |
| Colombia    | 2         | 1.9%    |
| Brazil      | 2         | 1.9%    |
| Belgium     | 2         | 1.9%    |
| Vietnam     | 1         | 0.95%   |
| Venezuela   | 1         | 0.95%   |
| Ukraine     | 1         | 0.95%   |
| Türkiye    | 1         | 0.95%   |
| Thailand    | 1         | 0.95%   |
| Taiwan      | 1         | 0.95%   |
| Russia      | 1         | 0.95%   |
| Portugal    | 1         | 0.95%   |
| Kenya       | 1         | 0.95%   |
| Honduras    | 1         | 0.95%   |
| Czechia     | 1         | 0.95%   |
| Chile       | 1         | 0.95%   |
| Bulgaria    | 1         | 0.95%   |
| Austria     | 1         | 0.95%   |
| Australia   | 1         | 0.95%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 4.67%   |
| Fayetteville                | 5         | 4.67%   |
| Charlotte                   | 5         | 4.67%   |
| Milan                       | 3         | 2.8%    |
| San Nicolás de los Arroyos | 2         | 1.87%   |
| Morgantown                  | 2         | 1.87%   |
| Medellín                   | 2         | 1.87%   |
| Iuka                        | 2         | 1.87%   |
| Helsinki                    | 2         | 1.87%   |
| Egan                        | 2         | 1.87%   |
| Denver                      | 2         | 1.87%   |
| Breilly                     | 2         | 1.87%   |
| Barcelona                   | 2         | 1.87%   |
| Zduny                       | 1         | 0.93%   |
| Zapopan                     | 1         | 0.93%   |
| Wroclaw                     | 1         | 0.93%   |
| Workum                      | 1         | 0.93%   |
| Worcester                   | 1         | 0.93%   |
| Walla Walla                 | 1         | 0.93%   |
| Viña del Mar               | 1         | 0.93%   |
| Vienna                      | 1         | 0.93%   |
| Uelzen                      | 1         | 0.93%   |
| Surakarta                   | 1         | 0.93%   |
| Stockton-on-Tees            | 1         | 0.93%   |
| Stockport                   | 1         | 0.93%   |
| Stabroek                    | 1         | 0.93%   |
| St Petersburg               | 1         | 0.93%   |
| Sofia                       | 1         | 0.93%   |
| Sevastopol                  | 1         | 0.93%   |
| Schiedam                    | 1         | 0.93%   |
| Rzeszów                    | 1         | 0.93%   |
| Rumia                       | 1         | 0.93%   |
| Rosny-sous-Bois             | 1         | 0.93%   |
| Rome                        | 1         | 0.93%   |
| Rio Ceballos                | 1         | 0.93%   |
| Rinteln                     | 1         | 0.93%   |
| Rincon de Soto              | 1         | 0.93%   |
| Ratchathewi                 | 1         | 0.93%   |
| Poznan                      | 1         | 0.93%   |
| Poricany                    | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 34     | 18.67%  |
| Samsung Electronics | 18        | 25     | 12%     |
| Kingston            | 16        | 20     | 10.67%  |
| WDC                 | 13        | 21     | 8.67%   |
| Toshiba             | 10        | 11     | 6.67%   |
| SanDisk             | 9         | 11     | 6%      |
| Hitachi             | 7         | 8      | 4.67%   |
| Crucial             | 6         | 7      | 4%      |
| Unknown             | 4         | 5      | 2.67%   |
| Micron Technology   | 3         | 4      | 2%      |
| SK hynix            | 2         | 2      | 1.33%   |
| KingSpec            | 2         | 2      | 1.33%   |
| Intel               | 2         | 2      | 1.33%   |
| China               | 2         | 2      | 1.33%   |
| Apple               | 2         | 3      | 1.33%   |
| Apacer              | 2         | 2      | 1.33%   |
| A-DATA Technology   | 2         | 2      | 1.33%   |
| Wibtek              | 1         | 1      | 0.67%   |
| USB30               | 1         | 1      | 0.67%   |
| SSK                 | 1         | 2      | 0.67%   |
| SPCC                | 1         | 1      | 0.67%   |
| Silicon Motion      | 1         | 1      | 0.67%   |
| PNY                 | 1         | 1      | 0.67%   |
| Phison              | 1         | 2      | 0.67%   |
| OWC                 | 1         | 2      | 0.67%   |
| Mushkin             | 1         | 1      | 0.67%   |
| Lexar               | 1         | 1      | 0.67%   |
| KIOXIA              | 1         | 3      | 0.67%   |
| KingFast            | 1         | 1      | 0.67%   |
| JMicron Technology  | 1         | 1      | 0.67%   |
| Intenso             | 1         | 1      | 0.67%   |
| Integral            | 1         | 2      | 0.67%   |
| Hikvision           | 1         | 1      | 0.67%   |
| GOODRAM             | 1         | 1      | 0.67%   |
| Fanxiang            | 1         | 1      | 0.67%   |
| Blackpcs            | 1         | 1      | 0.67%   |
| ASMedia             | 1         | 1      | 0.67%   |
| AMD                 | 1         | 1      | 0.67%   |
| Unknown             | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 7         | 4.4%    |
| Toshiba MQ04ABF100 1TB               | 3         | 1.89%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 1.89%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.89%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.26%   |
| Toshiba DT01ACA100 1TB               | 2         | 1.26%   |
| SK hynix C2S3T/480G 480GB            | 2         | 1.26%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 1.26%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.26%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.26%   |
| Seagate ST31000528AS 1TB             | 2         | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.26%   |
| Seagate Expansion 2TB                | 2         | 1.26%   |
| SanDisk SSD PLUS 480GB               | 2         | 1.26%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.26%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.26%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.26%   |
| Wibtek W800S 512GB                   | 1         | 0.63%   |
| WDC WDSN740-SDDPNQD-512G-1004 512GB  | 1         | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB         | 1         | 0.63%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.63%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.63%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 0.63%   |
| WDC WD600UE-22KVT0 64GB              | 1         | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.63%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.63%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 0.63%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.63%   |
| WDC WD10SPCX-60KHST0 1TB             | 1         | 0.63%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 0.63%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 0.63%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.63%   |
| USB30 Disk 120GB                     | 1         | 0.63%   |
| Unknown SN256  256GB                 | 1         | 0.63%   |
| Unknown NCard  32GB                  | 1         | 0.63%   |
| Unknown HAG2e  16GB                  | 1         | 0.63%   |
| Unknown DA4128  128GB                | 1         | 0.63%   |
| Unknown DA4064  64GB                 | 1         | 0.63%   |
| Toshiba MK6034GSX 64GB               | 1         | 0.63%   |
| Toshiba MK3261GSY 320GB              | 1         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 27        | 33     | 49.09%  |
| Toshiba | 10        | 11     | 18.18%  |
| WDC     | 8         | 10     | 14.55%  |
| Hitachi | 7         | 8      | 12.73%  |
| SSK     | 1         | 2      | 1.82%   |
| ASMedia | 1         | 1      | 1.82%   |
| Apple   | 1         | 1      | 1.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 19     | 22.39%  |
| Samsung Electronics | 11        | 11     | 16.42%  |
| SanDisk             | 7         | 7      | 10.45%  |
| Crucial             | 6         | 7      | 8.96%   |
| WDC                 | 2         | 3      | 2.99%   |
| SK hynix            | 2         | 2      | 2.99%   |
| Micron Technology   | 2         | 3      | 2.99%   |
| KingSpec            | 2         | 2      | 2.99%   |
| China               | 2         | 2      | 2.99%   |
| Apacer              | 2         | 2      | 2.99%   |
| A-DATA Technology   | 2         | 2      | 2.99%   |
| Wibtek              | 1         | 1      | 1.49%   |
| USB30               | 1         | 1      | 1.49%   |
| SPCC                | 1         | 1      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| OWC                 | 1         | 2      | 1.49%   |
| Mushkin             | 1         | 1      | 1.49%   |
| KingFast            | 1         | 1      | 1.49%   |
| Intenso             | 1         | 1      | 1.49%   |
| Integral            | 1         | 2      | 1.49%   |
| GOODRAM             | 1         | 1      | 1.49%   |
| Fanxiang            | 1         | 1      | 1.49%   |
| Blackpcs            | 1         | 1      | 1.49%   |
| Apple               | 1         | 2      | 1.49%   |
| AMD                 | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 59        | 77     | 44.36%  |
| HDD     | 46        | 66     | 34.59%  |
| NVMe    | 21        | 35     | 15.79%  |
| MMC     | 5         | 9      | 3.76%   |
| Unknown | 2         | 2      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 129    | 69.77%  |
| NVMe | 21        | 33     | 16.28%  |
| SAS  | 13        | 18     | 10.08%  |
| MMC  | 5         | 9      | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 76        | 101    | 71.7%   |
| 0.51-1.0   | 20        | 29     | 18.87%  |
| 1.01-2.0   | 8         | 10     | 7.55%   |
| 4.01-10.0  | 2         | 3      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 32.46%  |
| 251-500        | 23        | 20.18%  |
| 1-20           | 20        | 17.54%  |
| 501-1000       | 12        | 10.53%  |
| 51-100         | 9         | 7.89%   |
| 1001-2000      | 8         | 7.02%   |
| 21-50          | 4         | 3.51%   |
| More than 3000 | 1         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 85        | 77.27%  |
| 21-50     | 12        | 10.91%  |
| 101-250   | 4         | 3.64%   |
| 251-500   | 3         | 2.73%   |
| 51-100    | 3         | 2.73%   |
| 501-1000  | 2         | 1.82%   |
| 1001-2000 | 1         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB             | 2         | 2      | 9.09%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 3      | 9.09%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 2      | 4.55%   |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 4.55%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 2      | 4.55%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 4.55%   |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 4.55%   |
| Seagate ST9500423AS 500GB          | 1         | 1      | 4.55%   |
| Seagate ST9500420AS 500GB          | 1         | 1      | 4.55%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 4.55%   |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1      | 4.55%   |
| Seagate ST1000DM003-1CH162 1TB     | 1         | 1      | 4.55%   |
| SanDisk SSD PLUS 480GB             | 1         | 1      | 4.55%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 4.55%   |
| OWC Mercury EXTREME Pro 6G SSD     | 1         | 2      | 4.55%   |
| Mushkin MKNSSDCR120GB              | 1         | 1      | 4.55%   |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 4.55%   |
| Hitachi HDS721010CLA332 1TB        | 1         | 1      | 4.55%   |
| Crucial CT1000MX500SSD1 1TB        | 1         | 2      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 8         | 9      | 36.36%  |
| Toshiba  | 4         | 4      | 18.18%  |
| WDC      | 3         | 5      | 13.64%  |
| SanDisk  | 2         | 2      | 9.09%   |
| OWC      | 1         | 2      | 4.55%   |
| Mushkin  | 1         | 1      | 4.55%   |
| Kingston | 1         | 1      | 4.55%   |
| Hitachi  | 1         | 1      | 4.55%   |
| Crucial  | 1         | 2      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 53.33%  |
| Toshiba | 4         | 4      | 26.67%  |
| WDC     | 2         | 3      | 13.33%  |
| Hitachi | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 17     | 68.18%  |
| SSD  | 7         | 10     | 31.82%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |
| Seagate ST31000528AS 1TB  | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 3      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 87        | 132    | 67.97%  |
| Malfunc  | 22        | 27     | 17.19%  |
| Detected | 17        | 27     | 13.28%  |
| Failed   | 2         | 3      | 1.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 80        | 67.23%  |
| AMD                          | 14        | 11.76%  |
| Samsung Electronics          | 9         | 7.56%   |
| SanDisk                      | 5         | 4.2%    |
| Nvidia                       | 3         | 2.52%   |
| Silicon Motion               | 1         | 0.84%   |
| Shenzhen Longsys Electronics | 1         | 0.84%   |
| Phison Electronics           | 1         | 0.84%   |
| Micron Technology            | 1         | 0.84%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.84%   |
| Marvell Technology Group     | 1         | 0.84%   |
| KIOXIA                       | 1         | 0.84%   |
| Kingston Technology Company  | 1         | 0.84%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 10        | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 7         | 5%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 6         | 4.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 5         | 3.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 5         | 3.57%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 4         | 2.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 4         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 4         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 4         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 4         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 4         | 2.86%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 3         | 2.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 3         | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 3         | 2.14%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                                                       | 2         | 1.43%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 2         | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 1.43%   |
| Intel SATA Controller [RAID mode]                                                                                  | 2         | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 2         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 2         | 1.43%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2         | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 2         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 2         | 1.43%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 1         | 0.71%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 1         | 0.71%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                                                         | 1         | 0.71%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                                                      | 1         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 0.71%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 1         | 0.71%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                                           | 1         | 0.71%   |
| Nvidia MCP79 AHCI Controller                                                                                       | 1         | 0.71%   |
| Nvidia MCP61 SATA Controller                                                                                       | 1         | 0.71%   |
| Nvidia MCP61 IDE                                                                                                   | 1         | 0.71%   |
| Micron 2210 NVMe SSD [Cobain]                                                                                      | 1         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 1         | 0.71%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                                                          | 1         | 0.71%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 78        | 60.94%  |
| NVMe | 21        | 16.41%  |
| IDE  | 18        | 14.06%  |
| RAID | 11        | 8.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 88        | 83.81%  |
| AMD    | 17        | 16.19%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 1.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 1.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.9%    |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.9%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 1.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.9%    |
| Intel Celeron CPU N2807 @ 1.58GHz           | 2         | 1.9%    |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 1.9%    |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1         | 0.95%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz          | 1         | 0.95%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz         | 1         | 0.95%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.95%   |
| Intel Pentium M processor 1.50GHz           | 1         | 0.95%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1         | 0.95%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.95%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 0.95%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 0.95%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.95%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.95%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.95%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.95%   |
| Intel Core i7-4785T CPU @ 2.20GHz           | 1         | 0.95%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.95%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 0.95%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.95%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 0.95%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 0.95%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.95%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 0.95%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 0.95%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.95%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 0.95%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.95%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 20.95%  |
| Intel Core i7           | 13        | 12.38%  |
| Intel Core 2 Duo        | 10        | 9.52%   |
| Other                   | 9         | 8.57%   |
| Intel Core i3           | 8         | 7.62%   |
| Intel Celeron           | 8         | 7.62%   |
| Intel Atom              | 6         | 5.71%   |
| AMD Ryzen 5             | 4         | 3.81%   |
| Intel Xeon              | 3         | 2.86%   |
| Intel Pentium           | 2         | 1.9%    |
| AMD GX                  | 2         | 1.9%    |
| AMD FX                  | 2         | 1.9%    |
| Intel Pentium Silver    | 1         | 0.95%   |
| Intel Pentium M         | 1         | 0.95%   |
| Intel Pentium Gold      | 1         | 0.95%   |
| Intel Pentium Dual-Core | 1         | 0.95%   |
| Intel Pentium Dual      | 1         | 0.95%   |
| Intel Pentium D         | 1         | 0.95%   |
| Intel Core 2            | 1         | 0.95%   |
| Intel Celeron M         | 1         | 0.95%   |
| AMD Ryzen 7             | 1         | 0.95%   |
| AMD PRO A10             | 1         | 0.95%   |
| AMD Phenom II           | 1         | 0.95%   |
| AMD E                   | 1         | 0.95%   |
| AMD Athlon II Dual-Core | 1         | 0.95%   |
| AMD Athlon II           | 1         | 0.95%   |
| AMD A4                  | 1         | 0.95%   |
| AMD A12                 | 1         | 0.95%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 55        | 52.38%  |
| 4      | 26        | 24.76%  |
| 6      | 8         | 7.62%   |
| 1      | 6         | 5.71%   |
| 8      | 4         | 3.81%   |
| 12     | 2         | 1.9%    |
| 3      | 2         | 1.9%    |
| 14     | 1         | 0.95%   |
| 10     | 1         | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 99.05%  |
| 2      | 1         | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 58.1%   |
| 1      | 44        | 41.9%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 102       | 97.14%  |
| 32-bit         | 3         | 2.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 32.14%  |
| 0x1067a    | 6         | 5.36%   |
| 0x306a9    | 5         | 4.46%   |
| 0x20655    | 5         | 4.46%   |
| 0x906ea    | 3         | 2.68%   |
| 0x206a7    | 3         | 2.68%   |
| 0x106ca    | 3         | 2.68%   |
| 0x906e9    | 2         | 1.79%   |
| 0x806ea    | 2         | 1.79%   |
| 0x806c1    | 2         | 1.79%   |
| 0x706e5    | 2         | 1.79%   |
| 0x6d8      | 2         | 1.79%   |
| 0x406e3    | 2         | 1.79%   |
| 0x40651    | 2         | 1.79%   |
| 0x306d4    | 2         | 1.79%   |
| 0x306c3    | 2         | 1.79%   |
| 0x30678    | 2         | 1.79%   |
| 0x0600611a | 2         | 1.79%   |
| 0x010000c8 | 2         | 1.79%   |
| 0xf44      | 1         | 0.89%   |
| 0xb0671    | 1         | 0.89%   |
| 0xa0671    | 1         | 0.89%   |
| 0xa0653    | 1         | 0.89%   |
| 0x906ed    | 1         | 0.89%   |
| 0x906c0    | 1         | 0.89%   |
| 0x906a4    | 1         | 0.89%   |
| 0x90675    | 1         | 0.89%   |
| 0x806e9    | 1         | 0.89%   |
| 0x806d1    | 1         | 0.89%   |
| 0x706a1    | 1         | 0.89%   |
| 0x6fd      | 1         | 0.89%   |
| 0x6fa      | 1         | 0.89%   |
| 0x6f2      | 1         | 0.89%   |
| 0x506e3    | 1         | 0.89%   |
| 0x506c9    | 1         | 0.89%   |
| 0x206d7    | 1         | 0.89%   |
| 0x206c2    | 1         | 0.89%   |
| 0x106c2    | 1         | 0.89%   |
| 0x10676    | 1         | 0.89%   |
| 0x0a50000d | 1         | 0.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 12        | 11.32%  |
| IvyBridge        | 9         | 8.49%   |
| Penryn           | 8         | 7.55%   |
| Westmere         | 7         | 6.6%    |
| Haswell          | 7         | 6.6%    |
| SandyBridge      | 6         | 5.66%   |
| Bonnell          | 6         | 5.66%   |
| Core             | 5         | 4.72%   |
| Skylake          | 4         | 3.77%   |
| Silvermont       | 4         | 3.77%   |
| IceLake          | 4         | 3.77%   |
| K10              | 3         | 2.83%   |
| Excavator        | 3         | 2.83%   |
| Alderlake Hybrid | 3         | 2.83%   |
| Unknown          | 3         | 2.83%   |
| Zen 3            | 2         | 1.89%   |
| Zen              | 2         | 1.89%   |
| TigerLake        | 2         | 1.89%   |
| Puma             | 2         | 1.89%   |
| Piledriver       | 2         | 1.89%   |
| P6               | 2         | 1.89%   |
| Broadwell        | 2         | 1.89%   |
| Zen+             | 1         | 0.94%   |
| Zen 2            | 1         | 0.94%   |
| Tremont          | 1         | 0.94%   |
| NetBurst         | 1         | 0.94%   |
| Goldmont plus    | 1         | 0.94%   |
| Goldmont         | 1         | 0.94%   |
| CometLake        | 1         | 0.94%   |
| Bobcat           | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 73        | 59.84%  |
| AMD    | 26        | 21.31%  |
| Nvidia | 23        | 18.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 6.3%    |
| Intel Core Processor Integrated Graphics Controller                         | 5         | 3.94%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 4         | 3.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 4         | 3.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller     | 4         | 3.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.15%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 3         | 2.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 2.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 2.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 3         | 2.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.36%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.57%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 1.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 2         | 1.57%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2         | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.57%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2         | 1.57%   |
| AMD Barcelo                                                                 | 2         | 1.57%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1         | 0.79%   |
| Nvidia MCP89 [GeForce 320M]                                                 | 1         | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.79%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1         | 0.79%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                    | 1         | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.79%   |
| Nvidia GM108M [GeForce 930MX]                                               | 1         | 0.79%   |
| Nvidia GF119 [GeForce GT 705]                                               | 1         | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.79%   |
| Nvidia GF108M [GeForce GT 540M]                                             | 1         | 0.79%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.79%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 1         | 0.79%   |
| Nvidia G84M [GeForce 8600M GT]                                              | 1         | 0.79%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 45.37%  |
| 1 x AMD        | 21        | 19.44%  |
| 1 x Nvidia     | 13        | 12.04%  |
| Intel + Nvidia | 11        | 10.19%  |
| 2 x Intel      | 9         | 8.33%   |
| Intel + AMD    | 3         | 2.78%   |
| 2 x AMD        | 2         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 96.23%  |
| Unknown     | 3         | 2.83%   |
| Proprietary | 1         | 0.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 58.33%  |
| 0.01-0.5   | 21        | 19.44%  |
| 1.01-2.0   | 7         | 6.48%   |
| 3.01-4.0   | 5         | 4.63%   |
| 0.51-1.0   | 5         | 4.63%   |
| 7.01-8.0   | 4         | 3.7%    |
| 4.01-5.0   | 1         | 0.93%   |
| 2.01-3.0   | 1         | 0.93%   |
| 8.01-16.0  | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 18.63%  |
| LG Display              | 15        | 14.71%  |
| Samsung Electronics     | 10        | 9.8%    |
| Chimei Innolux          | 6         | 5.88%   |
| BOE                     | 5         | 4.9%    |
| Dell                    | 4         | 3.92%   |
| Chi Mei Optoelectronics | 4         | 3.92%   |
| Lenovo                  | 3         | 2.94%   |
| Apple                   | 3         | 2.94%   |
| Zoran                   | 2         | 1.96%   |
| Toshiba                 | 2         | 1.96%   |
| Sceptre Tech            | 2         | 1.96%   |
| LG Philips              | 2         | 1.96%   |
| Insignia                | 2         | 1.96%   |
| HUAWEI                  | 2         | 1.96%   |
| Hewlett-Packard         | 2         | 1.96%   |
| Goldstar                | 2         | 1.96%   |
| BenQ                    | 2         | 1.96%   |
| Vizio                   | 1         | 0.98%   |
| Sony                    | 1         | 0.98%   |
| Sharp                   | 1         | 0.98%   |
| SAC                     | 1         | 0.98%   |
| Philips                 | 1         | 0.98%   |
| Packard Bell            | 1         | 0.98%   |
| Mi                      | 1         | 0.98%   |
| MGN                     | 1         | 0.98%   |
| JDI                     | 1         | 0.98%   |
| InfoVision              | 1         | 0.98%   |
| EQV                     | 1         | 0.98%   |
| eMachines               | 1         | 0.98%   |
| ASUSTek Computer        | 1         | 0.98%   |
| AOC                     | 1         | 0.98%   |
| Acer                    | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                      | 2         | 1.96%   |
| Toshiba TV TSB0206 1920x1080                                            | 2         | 1.96%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch          | 2         | 1.96%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 2         | 1.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch           | 2         | 1.96%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 2         | 1.96%   |
| Vizio D24h-C1 VIZ0095 1360x768 521x293mm 23.5-inch                      | 1         | 0.98%   |
| Sony TV SNY0101 1360x768                                                | 1         | 0.98%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                  | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch    | 1         | 0.98%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch    | 1         | 0.98%   |
| Samsung Electronics SA300/SA350 SAM078F 1920x1080 477x268mm 21.5-inch   | 1         | 0.98%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch        | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch    | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.98%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch   | 1         | 0.98%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch       | 1         | 0.98%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 0.98%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                   | 1         | 0.98%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                      | 1         | 0.98%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch        | 1         | 0.98%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                        | 1         | 0.98%   |
| MGN MAGNA TV MGN0021 1920x1080 575x323mm 26.0-inch                      | 1         | 0.98%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch             | 1         | 0.98%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch             | 1         | 0.98%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch           | 1         | 0.98%   |
| LG Display LCD Monitor LGD069A 1920x1080 340x190mm 15.3-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD05D5 1920x1080 344x194mm 15.5-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 0.98%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD0386 1366x768 309x174mm 14.0-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch             | 1         | 0.98%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 0.98%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 41        | 41.84%  |
| 1366x768 (WXGA)    | 24        | 24.49%  |
| 1600x900 (HD+)     | 6         | 6.12%   |
| 1280x800 (WXGA)    | 6         | 6.12%   |
| 1360x768           | 4         | 4.08%   |
| 1024x600           | 4         | 4.08%   |
| 3840x2160 (4K)     | 3         | 3.06%   |
| 2560x1440 (QHD)    | 3         | 3.06%   |
| 1680x1050 (WSXGA+) | 2         | 2.04%   |
| 1280x1024 (SXGA)   | 2         | 2.04%   |
| 1920x1200 (WUXGA)  | 1         | 1.02%   |
| 1440x900 (WXGA+)   | 1         | 1.02%   |
| 1024x768 (XGA)     | 1         | 1.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 23.53%  |
| 14      | 13        | 12.75%  |
| 17      | 8         | 7.84%   |
| 24      | 7         | 6.86%   |
| 21      | 7         | 6.86%   |
| 13      | 5         | 4.9%    |
| 10      | 5         | 4.9%    |
| 31      | 4         | 3.92%   |
| 23      | 4         | 3.92%   |
| 11      | 4         | 3.92%   |
| 34      | 3         | 2.94%   |
| 22      | 3         | 2.94%   |
| 74      | 2         | 1.96%   |
| 32      | 2         | 1.96%   |
| 27      | 2         | 1.96%   |
| 12      | 2         | 1.96%   |
| 84      | 1         | 0.98%   |
| 54      | 1         | 0.98%   |
| 26      | 1         | 0.98%   |
| 19      | 1         | 0.98%   |
| 18      | 1         | 0.98%   |
| 16      | 1         | 0.98%   |
| Unknown | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 37.25%  |
| 201-300     | 15        | 14.71%  |
| 501-600     | 14        | 13.73%  |
| 401-500     | 11        | 10.78%  |
| 351-400     | 10        | 9.8%    |
| 701-800     | 5         | 4.9%    |
| 601-700     | 4         | 3.92%   |
| 1501-2000   | 3         | 2.94%   |
| 1001-1500   | 1         | 0.98%   |
| Unknown     | 1         | 0.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 80        | 82.47%  |
| 16/10 | 12        | 12.37%  |
| 5/4   | 2         | 2.06%   |
| 21/9  | 2         | 2.06%   |
| 4/3   | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 23.53%  |
| 201-250        | 19        | 18.63%  |
| 81-90          | 15        | 14.71%  |
| 351-500        | 8         | 7.84%   |
| 121-130        | 6         | 5.88%   |
| 41-50          | 5         | 4.9%    |
| More than 1000 | 4         | 3.92%   |
| 51-60          | 4         | 3.92%   |
| 71-80          | 3         | 2.94%   |
| 151-200        | 3         | 2.94%   |
| 61-70          | 2         | 1.96%   |
| 301-350        | 2         | 1.96%   |
| 141-150        | 2         | 1.96%   |
| 251-300        | 1         | 0.98%   |
| 131-140        | 1         | 0.98%   |
| 111-120        | 1         | 0.98%   |
| 501-1000       | 1         | 0.98%   |
| Unknown        | 1         | 0.98%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 32        | 31.37%  |
| 51-100  | 31        | 30.39%  |
| 121-160 | 28        | 27.45%  |
| 1-50    | 6         | 5.88%   |
| 161-240 | 4         | 3.92%   |
| Unknown | 1         | 0.98%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 90.65%  |
| 2     | 6         | 5.61%   |
| 0     | 4         | 3.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 50        | 30.12%  |
| Intel                           | 45        | 27.11%  |
| Qualcomm Atheros                | 25        | 15.06%  |
| Broadcom                        | 22        | 13.25%  |
| Ralink Technology               | 3         | 1.81%   |
| Qualcomm Atheros Communications | 3         | 1.81%   |
| Nvidia                          | 2         | 1.2%    |
| MediaTek                        | 2         | 1.2%    |
| Marvell Technology Group        | 2         | 1.2%    |
| Broadcom Limited                | 2         | 1.2%    |
| Samsung Electronics             | 1         | 0.6%    |
| Research In Motion              | 1         | 0.6%    |
| Ralink                          | 1         | 0.6%    |
| Prolific Technology             | 1         | 0.6%    |
| ICS Advent                      | 1         | 0.6%    |
| Huawei Technologies             | 1         | 0.6%    |
| Fibocom                         | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| D-Link                          | 1         | 0.6%    |
| Cal-Comp Electronic             | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 14.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 5.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 3.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 2.51%   |
| Intel Wireless 8265 / 8275                                             | 4         | 2.01%   |
| Intel Wireless 8260                                                    | 4         | 2.01%   |
| Intel Wireless 7260                                                    | 4         | 2.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 2.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 1.51%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 1.51%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3         | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 1.51%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 1.01%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.01%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 1.01%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 1.01%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 1.01%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.01%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 2         | 1.01%   |
| Intel Ethernet Controller I225-V                                       | 2         | 1.01%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.01%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 2         | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.5%    |
| Research In Motion BlackBerry                                          | 1         | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.5%    |
| Realtek RTL8191SEvA Wireless LAN Controller                            | 1         | 0.5%    |
| Realtek RTL8187B Wireless Adapter                                      | 1         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.5%    |
| Realtek 802.11ac NIC                                                   | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 37.23%  |
| Qualcomm Atheros                | 21        | 22.34%  |
| Realtek Semiconductor           | 14        | 14.89%  |
| Broadcom                        | 14        | 14.89%  |
| Ralink Technology               | 3         | 3.19%   |
| Qualcomm Atheros Communications | 3         | 3.19%   |
| Ralink                          | 1         | 1.06%   |
| MediaTek                        | 1         | 1.06%   |
| Fibocom                         | 1         | 1.06%   |
| D-Link                          | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 6.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 5         | 5.32%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 4.26%   |
| Intel Wireless 8260                                                                   | 4         | 4.26%   |
| Intel Wireless 7260                                                                   | 4         | 4.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 3         | 3.19%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 3.19%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 3.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.19%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 3         | 3.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 3         | 3.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 2.13%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 2         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.13%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.13%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 2         | 2.13%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 2         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.06%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 1.06%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 1.06%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 1.06%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 1.06%   |
| Intel Wireless 7265                                                                   | 1         | 1.06%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.06%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.06%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 1.06%   |
| Intel Raptor Lake PCH CNVi WiFi                                                       | 1         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.06%   |
| Intel Jasper Lake PCH CNVi WiFi                                                       | 1         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 43        | 43.43%  |
| Intel                    | 27        | 27.27%  |
| Broadcom                 | 12        | 12.12%  |
| Qualcomm Atheros         | 7         | 7.07%   |
| Nvidia                   | 2         | 2.02%   |
| Marvell Technology Group | 2         | 2.02%   |
| Broadcom Limited         | 2         | 2.02%   |
| Samsung Electronics      | 1         | 1.01%   |
| Research In Motion       | 1         | 1.01%   |
| MediaTek                 | 1         | 1.01%   |
| ICS Advent               | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 28.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 10.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 4.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 3.03%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 3.03%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 2.02%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 2.02%   |
| Intel Ethernet Controller I225-V                                       | 2         | 2.02%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.02%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 2.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 1.01%   |
| Research In Motion BlackBerry                                          | 1         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.01%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.01%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.01%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.01%   |
| MediaTek A015                                                          | 1         | 1.01%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.01%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1         | 1.01%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.01%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.01%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.01%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.01%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.01%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 1.01%   |
| Intel 82541GI Gigabit Ethernet Controller                              | 1         | 1.01%   |
| ICS Advent 10/100M LAN                                                 | 1         | 1.01%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 49.19%  |
| WiFi     | 88        | 47.57%  |
| Modem    | 6         | 3.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 61        | 55.96%  |
| Ethernet | 48        | 44.04%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 68        | 64.15%  |
| 1     | 34        | 32.08%  |
| 3     | 2         | 1.89%   |
| 0     | 2         | 1.89%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 64.15%  |
| Yes  | 38        | 35.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 35%     |
| Apple                           | 8         | 13.33%  |
| Qualcomm Atheros Communications | 7         | 11.67%  |
| Lite-On Technology              | 5         | 8.33%   |
| Realtek Semiconductor           | 4         | 6.67%   |
| IMC Networks                    | 3         | 5%      |
| Broadcom                        | 3         | 5%      |
| Dell                            | 2         | 3.33%   |
| Toshiba                         | 1         | 1.67%   |
| Ralink                          | 1         | 1.67%   |
| MediaTek                        | 1         | 1.67%   |
| Hewlett-Packard                 | 1         | 1.67%   |
| Foxconn / Hon Hai               | 1         | 1.67%   |
| Cambridge Silicon Radio         | 1         | 1.67%   |
| Unknown                         | 1         | 1.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 18.33%  |
| Intel AX201 Bluetooth                               | 4         | 6.67%   |
| Realtek Bluetooth Radio                             | 3         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 5%      |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 5%      |
| Apple Bluetooth Host Controller                     | 3         | 5%      |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.33%   |
| Intel Bluetooth Device                              | 2         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 3.33%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 3.33%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.67%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.67%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.67%   |
| MediaTek Wireless_Device                            | 1         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.67%   |
| Lite-On Bluetooth USB Host Controller               | 1         | 1.67%   |
| Lite-On Bluetooth Radio                             | 1         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.67%   |
| Intel AX210 Bluetooth                               | 1         | 1.67%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.67%   |
| IMC Networks Bluetooth Device                       | 1         | 1.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.67%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.67%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.67%   |
| Broadcom BCM20702A0                                 | 1         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.67%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.67%   |
| Unknown                                             | 1         | 1.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 85        | 62.5%   |
| AMD                   | 25        | 18.38%  |
| Nvidia                | 17        | 12.5%   |
| C-Media Electronics   | 2         | 1.47%   |
| Texas Instruments     | 1         | 0.74%   |
| SAVITECH              | 1         | 0.74%   |
| Roland                | 1         | 0.74%   |
| Realtek Semiconductor | 1         | 0.74%   |
| JMTek                 | 1         | 0.74%   |
| Huawei Technologies   | 1         | 0.74%   |
| Anlya.cn              | 1         | 0.74%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 9         | 5.7%    |
| Intel Sunrise Point-LP HD Audio                                                   | 8         | 5.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7         | 4.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 6         | 3.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 6         | 3.8%    |
| AMD Ryzen HD Audio Controller                                                     | 6         | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 5         | 3.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 4         | 2.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 4         | 2.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 4         | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 4         | 2.53%   |
| AMD Kabini HDMI/DP Audio                                                          | 4         | 2.53%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 1.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 3         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                             | 3         | 1.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 3         | 1.9%    |
| Intel 8 Series HD Audio Controller                                                | 3         | 1.9%    |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 3         | 1.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 1.9%    |
| AMD FCH Azalia Controller                                                         | 3         | 1.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 3         | 1.9%    |
| Nvidia GF108 High Definition Audio Controller                                     | 2         | 1.27%   |
| Nvidia GA104 High Definition Audio Controller                                     | 2         | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 2         | 1.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 2         | 1.27%   |
| Intel Broadwell-U Audio Controller                                                | 2         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 2         | 1.27%   |
| Intel 200 Series PCH HD Audio                                                     | 2         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 2         | 1.27%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2         | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 2         | 1.27%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 2         | 1.27%   |
| Texas Instruments PCM2902 Audio Codec                                             | 1         | 0.63%   |
| SAVITECH SA9123 USB Audio                                                         | 1         | 0.63%   |
| Roland QUAD-CAPTURE                                                               | 1         | 0.63%   |
| Realtek Semiconductor USB Audio                                                   | 1         | 0.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.63%   |
| Nvidia MCP89 High Definition Audio                                                | 1         | 0.63%   |
| Nvidia MCP79 High Definition Audio                                                | 1         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 24        | 18.32%  |
| Samsung Electronics          | 21        | 16.03%  |
| Unknown                      | 17        | 12.98%  |
| Kingston                     | 14        | 10.69%  |
| Crucial                      | 13        | 9.92%   |
| Micron Technology            | 10        | 7.63%   |
| Corsair                      | 5         | 3.82%   |
| A-DATA Technology            | 5         | 3.82%   |
| Elpida                       | 4         | 3.05%   |
| Timetec                      | 3         | 2.29%   |
| Nanya Technology             | 3         | 2.29%   |
| Ramaxel Technology           | 2         | 1.53%   |
| Unknown (0xFFFF000000000000) | 1         | 0.76%   |
| Unknown (08C8)               | 1         | 0.76%   |
| Toshiba                      | 1         | 0.76%   |
| Team                         | 1         | 0.76%   |
| SK_Hynix                     | 1         | 0.76%   |
| Patriot                      | 1         | 0.76%   |
| Infineon                     | 1         | 0.76%   |
| G.Skill                      | 1         | 0.76%   |
| ASint Technology             | 1         | 0.76%   |
| Unknown                      | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 3         | 2.11%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.41%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 1.41%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s            | 2         | 1.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s     | 2         | 1.41%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 1.41%   |
| Crucial RAM BLS16G4S26BFSD.16FD 16GB SODIMM DDR4 2667MT/s       | 2         | 1.41%   |
| Unknown RAM Module 512MB SODIMM DDR                             | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                     | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                            | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                              | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                      | 1         | 0.7%    |
| Unknown (0xFFFF000000000000) RAM Module 2GB SODIMM DDR2 667MT/s | 1         | 0.7%    |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s    | 1         | 0.7%    |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s              | 1         | 0.7%    |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s               | 1         | 0.7%    |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                   | 1         | 0.7%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s              | 1         | 0.7%    |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.7%    |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s            | 1         | 0.7%    |
| SK hynix RAM Module 8GB DIMM DDR3 1866MT/s                      | 1         | 0.7%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                    | 1         | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.7%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s          | 1         | 0.7%    |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s          | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                 | 1         | 0.7%    |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s          | 1         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 45        | 43.27%  |
| DDR4    | 29        | 27.88%  |
| DDR2    | 14        | 13.46%  |
| LPDDR4  | 7         | 6.73%   |
| SDRAM   | 4         | 3.85%   |
| DDR     | 2         | 1.92%   |
| LPDDR3  | 1         | 0.96%   |
| DDR5    | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 64.71%  |
| DIMM         | 26        | 25.49%  |
| Row Of Chips | 7         | 6.86%   |
| Unknown      | 2         | 1.96%   |
| Chip         | 1         | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 31.25%  |
| 4096  | 34        | 30.36%  |
| 2048  | 21        | 18.75%  |
| 1024  | 8         | 7.14%   |
| 16384 | 7         | 6.25%   |
| 512   | 4         | 3.57%   |
| 32768 | 3         | 2.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 26        | 23.01%  |
| 3200    | 11        | 9.73%   |
| 2667    | 10        | 8.85%   |
| 667     | 10        | 8.85%   |
| 2400    | 6         | 5.31%   |
| 1333    | 6         | 5.31%   |
| 1067    | 6         | 5.31%   |
| 1334    | 3         | 2.65%   |
| 533     | 3         | 2.65%   |
| Unknown | 3         | 2.65%   |
| 4267    | 2         | 1.77%   |
| 4199    | 2         | 1.77%   |
| 3733    | 2         | 1.77%   |
| 2133    | 2         | 1.77%   |
| 1867    | 2         | 1.77%   |
| 1866    | 2         | 1.77%   |
| 1800    | 2         | 1.77%   |
| 1066    | 2         | 1.77%   |
| 800     | 2         | 1.77%   |
| 8400    | 1         | 0.88%   |
| 6000    | 1         | 0.88%   |
| 4266    | 1         | 0.88%   |
| 3600    | 1         | 0.88%   |
| 3466    | 1         | 0.88%   |
| 3066    | 1         | 0.88%   |
| 2733    | 1         | 0.88%   |
| 2666    | 1         | 0.88%   |
| 2267    | 1         | 0.88%   |
| 1639    | 1         | 0.88%   |
| 975     | 1         | 0.88%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Hewlett-Packard     | 2         | 40%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 2         | 40%     |
| HP DeskJet F4200 series               | 1         | 20%     |
| HP DeskJet 2130 series                | 1         | 20%     |
| Brother HL-5370DW series              | 1         | 20%     |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 35.09%  |
| Apple                                  | 5         | 8.77%   |
| Realtek Semiconductor                  | 4         | 7.02%   |
| Microdia                               | 4         | 7.02%   |
| Sunplus Innovation Technology          | 3         | 5.26%   |
| Quanta                                 | 2         | 3.51%   |
| Logitech                               | 2         | 3.51%   |
| IMC Networks                           | 2         | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.51%   |
| Bison Electronics                      | 2         | 3.51%   |
| ALi                                    | 2         | 3.51%   |
| Syntek                                 | 1         | 1.75%   |
| Suyin                                  | 1         | 1.75%   |
| SunplusIT                              | 1         | 1.75%   |
| Sonix Technology                       | 1         | 1.75%   |
| Ricoh                                  | 1         | 1.75%   |
| Primax Electronics                     | 1         | 1.75%   |
| Luxvisions Innotech Limited            | 1         | 1.75%   |
| Lite-On Technology                     | 1         | 1.75%   |
| Importek                               | 1         | 1.75%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                   | 5         | 8.62%   |
| Chicony USB 2.0 Camera                              | 3         | 5.17%   |
| Apple Built-in iSight                               | 3         | 5.17%   |
| Chicony HD WebCam (Acer)                            | 2         | 3.45%   |
| Syntek Integrated Camera                            | 1         | 1.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.72%   |
| SunplusIT 1080p FHD Camera                          | 1         | 1.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.72%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.72%   |
| Sunplus HD WebCam                                   | 1         | 1.72%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.72%   |
| Ricoh USB2.0 Camera                                 | 1         | 1.72%   |
| Realtek USB2.0 camera                               | 1         | 1.72%   |
| Realtek TOSHIBA Web Camera                          | 1         | 1.72%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.72%   |
| Realtek Intergrated Camera 5M                       | 1         | 1.72%   |
| Realtek HP Webcam-101                               | 1         | 1.72%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 1.72%   |
| Quanta HD User Facing                               | 1         | 1.72%   |
| Primax webcam                                       | 1         | 1.72%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 1.72%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.72%   |
| Microdia Integrated Webcam                          | 1         | 1.72%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 1.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.72%   |
| Logitech Logitech Webcam C160                       | 1         | 1.72%   |
| Logitech HD Pro Webcam C920                         | 1         | 1.72%   |
| Lite-On Integrated Camera                           | 1         | 1.72%   |
| Importek 1.3Mega Web Camera                         | 1         | 1.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.72%   |
| IMC Networks Integrated Camera                      | 1         | 1.72%   |
| Chicony WebCam                                      | 1         | 1.72%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 1.72%   |
| Chicony Lenovo EasyCamera                           | 1         | 1.72%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 1.72%   |
| Chicony Integrated Camera                           | 1         | 1.72%   |
| Chicony HP Integrated Webcam                        | 1         | 1.72%   |
| Chicony HP HD Camera                                | 1         | 1.72%   |
| Chicony FJ Camera                                   | 1         | 1.72%   |
| Chicony EasyCamera                                  | 1         | 1.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| LighTuning Technology | 2         | 40%     |
| Validity Sensors      | 1         | 20%     |
| Synaptics             | 1         | 20%     |
| Focal-systems.Corp    | 1         | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| LighTuning ES603 Swipe Fingerprint Sensor  | 2         | 40%     |
| Validity Sensors VFS495 Fingerprint Reader | 1         | 20%     |
| Synaptics Prometheus Fingerprint Reader    | 1         | 20%     |
| Focal-systems.Corp FT9201Fingerprint.      | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Lenovo   | 1         | 50%     |
| Broadcom | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Broadcom 5880                       | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 76.19%  |
| 1     | 23        | 21.9%   |
| 2     | 2         | 1.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 11        | 40.74%  |
| Fingerprint reader       | 5         | 18.52%  |
| Multimedia controller    | 3         | 11.11%  |
| Chipcard                 | 2         | 7.41%   |
| Camera                   | 2         | 7.41%   |
| Storage                  | 1         | 3.7%    |
| Net/wireless             | 1         | 3.7%    |
| Communication controller | 1         | 3.7%    |
| Bluetooth                | 1         | 3.7%    |

