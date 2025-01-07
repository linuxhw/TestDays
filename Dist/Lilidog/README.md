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

Total: 113

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Lilidog 23 | 42        | 44.21%  |
| Lilidog 22 | 40        | 42.11%  |
| Lilidog 24 | 11        | 11.58%  |
| Lilidog 12 | 2         | 2.11%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lilidog | 90        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.5.0-0.deb12.4-amd64    | 9         | 8.74%   |
| 5.10.0-16-amd64          | 6         | 5.83%   |
| 6.1.0-9-amd64            | 5         | 4.85%   |
| 5.10.0-18-amd64          | 5         | 4.85%   |
| 5.10.0-15-amd64          | 5         | 4.85%   |
| 6.6.13+bpo-amd64         | 4         | 3.88%   |
| 6.1.0-10-amd64           | 4         | 3.88%   |
| 5.10.0-13-amd64          | 4         | 3.88%   |
| 6.11.5+bpo-amd64         | 3         | 2.91%   |
| 6.1.0-18-amd64           | 3         | 2.91%   |
| 5.10.0-21-amd64          | 3         | 2.91%   |
| 5.10.0-20-amd64          | 3         | 2.91%   |
| 6.7.12+bpo-amd64         | 2         | 1.94%   |
| 6.5.0-0.deb12.1-amd64    | 2         | 1.94%   |
| 6.1.0-7-amd64            | 2         | 1.94%   |
| 6.1.0-25-amd64           | 2         | 1.94%   |
| 6.1.0-23-amd64           | 2         | 1.94%   |
| 6.1.0-21-amd64           | 2         | 1.94%   |
| 6.1.0-20-amd64           | 2         | 1.94%   |
| 6.1.0-16-amd64           | 2         | 1.94%   |
| 6.1.0-11-amd64           | 2         | 1.94%   |
| 6.0.8-x64v1-xanmod1      | 2         | 1.94%   |
| 5.10.0-14-amd64          | 2         | 1.94%   |
| 6.8.9-5-liquorix-amd64   | 1         | 0.97%   |
| 6.4.5-1-liquorix-amd64   | 1         | 0.97%   |
| 6.4.0-0.deb12.2-amd64    | 1         | 0.97%   |
| 6.2.12-x64v1-xanmod1     | 1         | 0.97%   |
| 6.2.11-x64v1-xanmod1     | 1         | 0.97%   |
| 6.12.1-1-liquorix-amd64  | 1         | 0.97%   |
| 6.11.10+bpo-amd64        | 1         | 0.97%   |
| 6.10.11+bpo-amd64        | 1         | 0.97%   |
| 6.1.0-7.2-liquorix-amd64 | 1         | 0.97%   |
| 6.1.0-28-amd64           | 1         | 0.97%   |
| 6.1.0-25-686-pae         | 1         | 0.97%   |
| 6.1.0-18-686-pae         | 1         | 0.97%   |
| 6.1.0-13-amd64           | 1         | 0.97%   |
| 6.1.0-13-686-pae         | 1         | 0.97%   |
| 6.1.0-0.deb11.6-amd64    | 1         | 0.97%   |
| 6.0.10-x64v1-xanmod1     | 1         | 0.97%   |
| 6.0.0-5-amd64            | 1         | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 32        | 32%     |
| 5.10.0  | 29        | 29%     |
| 6.5.0   | 11        | 11%     |
| 6.6.13  | 4         | 4%      |
| 6.0.0   | 4         | 4%      |
| 6.11.5  | 3         | 3%      |
| 6.7.12  | 2         | 2%      |
| 6.0.8   | 2         | 2%      |
| 5.19.0  | 2         | 2%      |
| 6.8.9   | 1         | 1%      |
| 6.4.5   | 1         | 1%      |
| 6.4.0   | 1         | 1%      |
| 6.2.12  | 1         | 1%      |
| 6.2.11  | 1         | 1%      |
| 6.12.1  | 1         | 1%      |
| 6.11.10 | 1         | 1%      |
| 6.10.11 | 1         | 1%      |
| 6.0.10  | 1         | 1%      |
| 5.18.0  | 1         | 1%      |
| 5.17.0  | 1         | 1%      |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 32        | 32%     |
| 5.10    | 29        | 29%     |
| 6.5     | 11        | 11%     |
| 6.0     | 7         | 7%      |
| 6.6     | 4         | 4%      |
| 6.11    | 4         | 4%      |
| 6.7     | 2         | 2%      |
| 6.4     | 2         | 2%      |
| 6.2     | 2         | 2%      |
| 5.19    | 2         | 2%      |
| 6.8     | 1         | 1%      |
| 6.12    | 1         | 1%      |
| 6.10    | 1         | 1%      |
| 5.18    | 1         | 1%      |
| 5.17    | 1         | 1%      |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 87        | 96.67%  |
| i686   | 3         | 3.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| lightdm-xsession | 61        | 64.21%  |
| openbox          | 32        | 33.68%  |
| XFCE             | 1         | 1.05%   |
| dk               | 1         | 1.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 90        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 90        | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 53        | 58.24%  |
| de_DE | 6         | 6.59%   |
| es_ES | 5         | 5.49%   |
| en_GB | 5         | 5.49%   |
| pl_PL | 4         | 4.4%    |
| ru_RU | 3         | 3.3%    |
| es_MX | 3         | 3.3%    |
| es_CO | 2         | 2.2%    |
| es_AR | 2         | 2.2%    |
| pt_BR | 1         | 1.1%    |
| it_IT | 1         | 1.1%    |
| fi_FI | 1         | 1.1%    |
| es_CL | 1         | 1.1%    |
| en_IE | 1         | 1.1%    |
| en_CA | 1         | 1.1%    |
| en_AU | 1         | 1.1%    |
| cs_CZ | 1         | 1.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 50        | 55.56%  |
| BIOS | 40        | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 66        | 70.97%  |
| Overlay | 19        | 20.43%  |
| Btrfs   | 7         | 7.53%   |
| Xfs     | 1         | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 58        | 63.74%  |
| MBR  | 33        | 36.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 61.7%   |
| Yes       | 36        | 38.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 81.11%  |
| Yes       | 17        | 18.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 15        | 16.67%  |
| Lenovo                               | 13        | 14.44%  |
| Dell                                 | 13        | 14.44%  |
| Acer                                 | 11        | 12.22%  |
| ASUSTek Computer                     | 7         | 7.78%   |
| Apple                                | 6         | 6.67%   |
| Gigabyte Technology                  | 3         | 3.33%   |
| Toshiba                              | 2         | 2.22%   |
| Panasonic                            | 2         | 2.22%   |
| Google                               | 2         | 2.22%   |
| TUXEDO                               | 1         | 1.11%   |
| Sony                                 | 1         | 1.11%   |
| Shenzhen Meigao Electronic Equipment | 1         | 1.11%   |
| Samsung Electronics                  | 1         | 1.11%   |
| PC Specialist                        | 1         | 1.11%   |
| Matsushita Electric Industrial       | 1         | 1.11%   |
| Inventec                             | 1         | 1.11%   |
| Intel                                | 1         | 1.11%   |
| GPU Company                          | 1         | 1.11%   |
| Foxconn                              | 1         | 1.11%   |
| Fanless Mini PC                      | 1         | 1.11%   |
| eMachines                            | 1         | 1.11%   |
| Biostar                              | 1         | 1.11%   |
| BANGHO                               | 1         | 1.11%   |
| AZW                                  | 1         | 1.11%   |
| Unknown                              | 1         | 1.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Acer Aspire E5-573                          | 2         | 2.22%   |
| Acer AOD255E                                | 2         | 2.22%   |
| TUXEDO N8xEJEK                              | 1         | 1.11%   |
| Toshiba Satellite Pro L450                  | 1         | 1.11%   |
| Toshiba Satellite P200                      | 1         | 1.11%   |
| Sony VPCF23P1E                              | 1         | 1.11%   |
| Shenzhen Meigao Electronic Equipment UM560  | 1         | 1.11%   |
| Samsung 750QFG                              | 1         | 1.11%   |
| PC Specialist P65_67RSRP                    | 1         | 1.11%   |
| Panasonic CFMX4-1                           | 1         | 1.11%   |
| Panasonic CF-31ATXAX1M                      | 1         | 1.11%   |
| Matsushita Electric Industrial CF-52GDN30AG | 1         | 1.11%   |
| Lenovo Yoga Slim 7 14ARE05 82A2             | 1         | 1.11%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 1.11%   |
| Lenovo ThinkPad X280 20KES63G00             | 1         | 1.11%   |
| Lenovo ThinkPad X131e 33722WU               | 1         | 1.11%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW  | 1         | 1.11%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS24900    | 1         | 1.11%   |
| Lenovo ThinkPad T430s 2356GUU               | 1         | 1.11%   |
| Lenovo ThinkPad T400 6474WPU                | 1         | 1.11%   |
| Lenovo Legion T7 34IMZ5 90Q800AJMH          | 1         | 1.11%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 1         | 1.11%   |
| Lenovo IdeaPad 1 14ADA05 82GW               | 1         | 1.11%   |
| Lenovo G500 20236                           | 1         | 1.11%   |
| Lenovo 3000 G410                            | 1         | 1.11%   |
| Inventec Dell Thin Client Desktop 5060      | 1         | 1.11%   |
| Intel NUC11BTMi7                            | 1         | 1.11%   |
| HP Z600 Workstation                         | 1         | 1.11%   |
| HP t520 Flexible Series TC                  | 1         | 1.11%   |
| HP ProBook 6560b                            | 1         | 1.11%   |
| HP ProBook 450 G5                           | 1         | 1.11%   |
| HP Pavilion 11 x360 PC                      | 1         | 1.11%   |
| HP Laptop 15s-fq1xxx                        | 1         | 1.11%   |
| HP G62                                      | 1         | 1.11%   |
| HP EliteDesk 800 G1 SFF                     | 1         | 1.11%   |
| HP EliteDesk 800 G1 DM                      | 1         | 1.11%   |
| HP EliteDesk 705 G2 MINI                    | 1         | 1.11%   |
| HP All-in-One Desktop 27-cb1xxx             | 1         | 1.11%   |
| HP 630                                      | 1         | 1.11%   |
| HP 510 Notebook PC (RU962AA#ABE)            | 1         | 1.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 6         | 6.67%   |
| Acer Aspire                                 | 6         | 6.67%   |
| Dell Latitude                               | 5         | 5.56%   |
| Dell OptiPlex                               | 4         | 4.44%   |
| HP EliteDesk                                | 3         | 3.33%   |
| Toshiba Satellite                           | 2         | 2.22%   |
| Lenovo IdeaPad                              | 2         | 2.22%   |
| HP ProBook                                  | 2         | 2.22%   |
| Dell Inspiron                               | 2         | 2.22%   |
| ASUS VivoBook                               | 2         | 2.22%   |
| ASUS PRIME                                  | 2         | 2.22%   |
| Acer AOD255E                                | 2         | 2.22%   |
| TUXEDO N8xEJEK                              | 1         | 1.11%   |
| Sony VPCF23P1E                              | 1         | 1.11%   |
| Shenzhen Meigao Electronic Equipment UM560  | 1         | 1.11%   |
| Samsung 750QFG                              | 1         | 1.11%   |
| PC Specialist P65                           | 1         | 1.11%   |
| Panasonic CFMX4-1                           | 1         | 1.11%   |
| Panasonic CF-31ATXAX1M                      | 1         | 1.11%   |
| Matsushita Electric Industrial CF-52GDN30AG | 1         | 1.11%   |
| Lenovo Yoga                                 | 1         | 1.11%   |
| Lenovo Y520-15IKBN                          | 1         | 1.11%   |
| Lenovo Legion                               | 1         | 1.11%   |
| Lenovo G500                                 | 1         | 1.11%   |
| Lenovo 3000                                 | 1         | 1.11%   |
| Inventec Dell                               | 1         | 1.11%   |
| Intel NUC11BTMi7                            | 1         | 1.11%   |
| HP Z600                                     | 1         | 1.11%   |
| HP t520                                     | 1         | 1.11%   |
| HP Pavilion                                 | 1         | 1.11%   |
| HP Laptop                                   | 1         | 1.11%   |
| HP G62                                      | 1         | 1.11%   |
| HP All-in-One                               | 1         | 1.11%   |
| HP 630                                      | 1         | 1.11%   |
| HP 510                                      | 1         | 1.11%   |
| HP 435                                      | 1         | 1.11%   |
| HP 2B2C                                     | 1         | 1.11%   |
| GPU Company GWNR71517                       | 1         | 1.11%   |
| Google Sand                                 | 1         | 1.11%   |
| Google Auron                                | 1         | 1.11%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2010 | 11        | 12.22%  |
| 2018 | 7         | 7.78%   |
| 2012 | 7         | 7.78%   |
| 2011 | 7         | 7.78%   |
| 2022 | 6         | 6.67%   |
| 2021 | 6         | 6.67%   |
| 2017 | 6         | 6.67%   |
| 2014 | 6         | 6.67%   |
| 2019 | 5         | 5.56%   |
| 2015 | 5         | 5.56%   |
| 2013 | 5         | 5.56%   |
| 2007 | 5         | 5.56%   |
| 2008 | 4         | 4.44%   |
| 2020 | 3         | 3.33%   |
| 2016 | 3         | 3.33%   |
| 2009 | 2         | 2.22%   |
| 2023 | 1         | 1.11%   |
| 2006 | 1         | 1.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 53        | 58.89%  |
| Desktop     | 26        | 28.89%  |
| Mini pc     | 6         | 6.67%   |
| All in one  | 3         | 3.33%   |
| Tablet      | 1         | 1.11%   |
| Convertible | 1         | 1.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 88        | 97.78%  |
| Enabled  | 2         | 2.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 87        | 96.67%  |
| Yes  | 3         | 3.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 27        | 29.67%  |
| 3.01-4.0    | 22        | 24.18%  |
| 16.01-24.0  | 15        | 16.48%  |
| 8.01-16.0   | 10        | 10.99%  |
| 32.01-64.0  | 5         | 5.49%   |
| 1.01-2.0    | 4         | 4.4%    |
| 2.01-3.0    | 3         | 3.3%    |
| 0.51-1.0    | 2         | 2.2%    |
| 24.01-32.0  | 1         | 1.1%    |
| 64.01-256.0 | 1         | 1.1%    |
| 0.01-0.5    | 1         | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 53        | 55.21%  |
| 1.01-2.0  | 30        | 31.25%  |
| 2.01-3.0  | 8         | 8.33%   |
| 0.01-0.5  | 3         | 3.13%   |
| 3.01-4.0  | 1         | 1.04%   |
| 8.01-16.0 | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 62        | 66.67%  |
| 2      | 19        | 20.43%  |
| 3      | 8         | 8.6%    |
| 4      | 4         | 4.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 57        | 62.64%  |
| Yes       | 34        | 37.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 87.91%  |
| No        | 11        | 12.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 83.33%  |
| No        | 15        | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 54        | 58.7%   |
| No        | 38        | 41.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 24        | 26.67%  |
| Germany     | 10        | 11.11%  |
| UK          | 6         | 6.67%   |
| Spain       | 6         | 6.67%   |
| Poland      | 6         | 6.67%   |
| Argentina   | 4         | 4.44%   |
| Netherlands | 3         | 3.33%   |
| Italy       | 3         | 3.33%   |
| Romania     | 2         | 2.22%   |
| Mexico      | 2         | 2.22%   |
| Finland     | 2         | 2.22%   |
| Colombia    | 2         | 2.22%   |
| Canada      | 2         | 2.22%   |
| Belgium     | 2         | 2.22%   |
| Vietnam     | 1         | 1.11%   |
| Ukraine     | 1         | 1.11%   |
| Thailand    | 1         | 1.11%   |
| Taiwan      | 1         | 1.11%   |
| Russia      | 1         | 1.11%   |
| Portugal    | 1         | 1.11%   |
| Kenya       | 1         | 1.11%   |
| Indonesia   | 1         | 1.11%   |
| Honduras    | 1         | 1.11%   |
| France      | 1         | 1.11%   |
| Czechia     | 1         | 1.11%   |
| Chile       | 1         | 1.11%   |
| Bulgaria    | 1         | 1.11%   |
| Brazil      | 1         | 1.11%   |
| Austria     | 1         | 1.11%   |
| Australia   | 1         | 1.11%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Travelers Rest              | 5         | 5.43%   |
| Fayetteville                | 5         | 5.43%   |
| Charlotte                   | 4         | 4.35%   |
| San Nicolás de los Arroyos | 2         | 2.17%   |
| Milan                       | 2         | 2.17%   |
| Medellín                   | 2         | 2.17%   |
| Helsinki                    | 2         | 2.17%   |
| Egan                        | 2         | 2.17%   |
| Denver                      | 2         | 2.17%   |
| Barcelona                   | 2         | 2.17%   |
| Zduny                       | 1         | 1.09%   |
| Zapopan                     | 1         | 1.09%   |
| Wroclaw                     | 1         | 1.09%   |
| Workum                      | 1         | 1.09%   |
| Worcester                   | 1         | 1.09%   |
| Viña del Mar               | 1         | 1.09%   |
| Vienna                      | 1         | 1.09%   |
| Uelzen                      | 1         | 1.09%   |
| Stockton-on-Tees            | 1         | 1.09%   |
| Stockport                   | 1         | 1.09%   |
| Stabroek                    | 1         | 1.09%   |
| St Petersburg               | 1         | 1.09%   |
| Sofia                       | 1         | 1.09%   |
| Sevastopol                  | 1         | 1.09%   |
| Schiedam                    | 1         | 1.09%   |
| Rzeszów                    | 1         | 1.09%   |
| Rumia                       | 1         | 1.09%   |
| Rome                        | 1         | 1.09%   |
| Rio Ceballos                | 1         | 1.09%   |
| Rinteln                     | 1         | 1.09%   |
| Rincon de Soto              | 1         | 1.09%   |
| Ratchathewi                 | 1         | 1.09%   |
| Poznan                      | 1         | 1.09%   |
| Poricany                    | 1         | 1.09%   |
| Palembang                   | 1         | 1.09%   |
| Ossa de Montiel             | 1         | 1.09%   |
| Oradea                      | 1         | 1.09%   |
| Norderstedt                 | 1         | 1.09%   |
| Neu-Isenburg                | 1         | 1.09%   |
| Nairobi                     | 1         | 1.09%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 28     | 18.11%  |
| Kingston            | 15        | 18     | 11.81%  |
| WDC                 | 13        | 21     | 10.24%  |
| Samsung Electronics | 13        | 17     | 10.24%  |
| Toshiba             | 8         | 9      | 6.3%    |
| SanDisk             | 7         | 9      | 5.51%   |
| Crucial             | 7         | 8      | 5.51%   |
| Hitachi             | 4         | 5      | 3.15%   |
| Micron Technology   | 3         | 4      | 2.36%   |
| Unknown             | 2         | 2      | 1.57%   |
| SK hynix            | 2         | 2      | 1.57%   |
| Intel               | 2         | 2      | 1.57%   |
| Apacer              | 2         | 2      | 1.57%   |
| A-DATA Technology   | 2         | 2      | 1.57%   |
| Wibtek              | 1         | 1      | 0.79%   |
| USB30               | 1         | 1      | 0.79%   |
| SSK                 | 1         | 2      | 0.79%   |
| SPCC                | 1         | 1      | 0.79%   |
| Silicon Motion      | 1         | 1      | 0.79%   |
| PNY                 | 1         | 1      | 0.79%   |
| Phison              | 1         | 2      | 0.79%   |
| OWC                 | 1         | 2      | 0.79%   |
| Mushkin             | 1         | 1      | 0.79%   |
| Lexar               | 1         | 1      | 0.79%   |
| KIOXIA              | 1         | 3      | 0.79%   |
| KingSpec            | 1         | 1      | 0.79%   |
| KingFast            | 1         | 1      | 0.79%   |
| JMicron Technology  | 1         | 1      | 0.79%   |
| Integral            | 1         | 2      | 0.79%   |
| Hikvision           | 1         | 1      | 0.79%   |
| GOODRAM             | 1         | 1      | 0.79%   |
| Fanxiang            | 1         | 1      | 0.79%   |
| China               | 1         | 1      | 0.79%   |
| Blackpcs            | 1         | 1      | 0.79%   |
| ASMedia             | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |
| AMD                 | 1         | 1      | 0.79%   |
| Unknown             | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 6         | 4.51%   |
| Toshiba MQ04ABF100 1TB               | 3         | 2.26%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 2.26%   |
| Toshiba DT01ACA100 1TB               | 2         | 1.5%    |
| SK hynix C2S3T/480G 480GB SSD        | 2         | 1.5%    |
| Seagate ST500LT012-9WS142 500GB      | 2         | 1.5%    |
| Seagate ST500DM002-1BD142 500GB      | 2         | 1.5%    |
| Seagate ST31000528AS 1TB             | 2         | 1.5%    |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.5%    |
| Seagate Expansion 1TB                | 2         | 1.5%    |
| SanDisk SSD PLUS 480GB               | 2         | 1.5%    |
| Samsung SSD 970 EVO Plus 1TB         | 2         | 1.5%    |
| Samsung SSD 850 EVO 250GB            | 2         | 1.5%    |
| Crucial CT250MX500SSD1 250GB         | 2         | 1.5%    |
| Wibtek W800S 512GB SSD               | 1         | 0.75%   |
| WDC WDSN740-SDDPNQD-512G-1004 512GB  | 1         | 0.75%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.75%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 0.75%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.75%   |
| WDC WD800JD-75MSA3 80GB              | 1         | 0.75%   |
| WDC WD600UE-22KVT0 64GB              | 1         | 0.75%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.75%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.75%   |
| WDC WD50 00AAKX-08U6AA0 500GB        | 1         | 0.75%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.75%   |
| WDC WD10SPCX-60KHST0 1TB             | 1         | 0.75%   |
| WDC WD10EZEX-60M2NA0 1TB             | 1         | 0.75%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 0.75%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB | 1         | 0.75%   |
| USB30 Disk 240GB                     | 1         | 0.75%   |
| Unknown NCard  32GB                  | 1         | 0.75%   |
| Unknown DA4064  64GB                 | 1         | 0.75%   |
| Toshiba MQ01ABF050 500GB             | 1         | 0.75%   |
| Toshiba MK6034GSX 64GB               | 1         | 0.75%   |
| Toshiba MK1665GSX 160GB              | 1         | 0.75%   |
| SSK Disk 1TB                         | 1         | 0.75%   |
| SPCC Solid State Disk 256GB          | 1         | 0.75%   |
| Silicon Motion NE-128 128GB          | 1         | 0.75%   |
| Seagate ST9500420AS 500GB            | 1         | 0.75%   |
| Seagate ST9320325ASG 320GB           | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 23        | 28     | 51.11%  |
| WDC     | 8         | 10     | 17.78%  |
| Toshiba | 8         | 9      | 17.78%  |
| Hitachi | 4         | 5      | 8.89%   |
| ASMedia | 1         | 1      | 2.22%   |
| Apple   | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 16     | 22.03%  |
| Samsung Electronics | 9         | 10     | 15.25%  |
| Crucial             | 7         | 8      | 11.86%  |
| SanDisk             | 6         | 6      | 10.17%  |
| WDC                 | 2         | 3      | 3.39%   |
| SK hynix            | 2         | 2      | 3.39%   |
| Micron Technology   | 2         | 3      | 3.39%   |
| Apacer              | 2         | 2      | 3.39%   |
| A-DATA Technology   | 2         | 2      | 3.39%   |
| Wibtek              | 1         | 1      | 1.69%   |
| USB30               | 1         | 1      | 1.69%   |
| SPCC                | 1         | 1      | 1.69%   |
| PNY                 | 1         | 1      | 1.69%   |
| OWC                 | 1         | 2      | 1.69%   |
| Mushkin             | 1         | 1      | 1.69%   |
| KingSpec            | 1         | 1      | 1.69%   |
| KingFast            | 1         | 1      | 1.69%   |
| Integral            | 1         | 2      | 1.69%   |
| GOODRAM             | 1         | 1      | 1.69%   |
| Fanxiang            | 1         | 1      | 1.69%   |
| China               | 1         | 1      | 1.69%   |
| Blackpcs            | 1         | 1      | 1.69%   |
| AMD                 | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 51        | 68     | 44.74%  |
| HDD     | 39        | 54     | 34.21%  |
| NVMe    | 20        | 30     | 17.54%  |
| MMC     | 3         | 6      | 2.63%   |
| Unknown | 1         | 1      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 111    | 70.91%  |
| NVMe | 19        | 28     | 17.27%  |
| SAS  | 10        | 14     | 9.09%   |
| MMC  | 3         | 6      | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 63        | 82     | 70%     |
| 0.51-1.0   | 21        | 33     | 23.33%  |
| 1.01-2.0   | 5         | 6      | 5.56%   |
| 4.01-10.0  | 1         | 1      | 1.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 31.25%  |
| 251-500        | 21        | 21.88%  |
| 1-20           | 17        | 17.71%  |
| 501-1000       | 10        | 10.42%  |
| 1001-2000      | 7         | 7.29%   |
| 51-100         | 7         | 7.29%   |
| 21-50          | 3         | 3.13%   |
| More than 3000 | 1         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 74        | 78.72%  |
| 21-50     | 8         | 8.51%   |
| 101-250   | 4         | 4.26%   |
| 251-500   | 3         | 3.19%   |
| 51-100    | 3         | 3.19%   |
| 1001-2000 | 1         | 1.06%   |
| 501-1000  | 1         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA100 1TB             | 2         | 2      | 10.53%  |
| Seagate ST500LT012-9WS142 500GB    | 2         | 3      | 10.53%  |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 2      | 5.26%   |
| WDC WD800JD-75MSA3 80GB            | 1         | 1      | 5.26%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 2      | 5.26%   |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 5.26%   |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 5.26%   |
| Seagate ST9500420AS 500GB          | 1         | 1      | 5.26%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 5.26%   |
| Seagate ST1000DM010-2EP102 1TB     | 1         | 1      | 5.26%   |
| Seagate ST1000DM003-1CH162 1TB     | 1         | 1      | 5.26%   |
| SanDisk SSD PLUS 480GB             | 1         | 1      | 5.26%   |
| SanDisk SDSA6MM-016G-1006 16GB SSD | 1         | 1      | 5.26%   |
| OWC Mercury EXTREME Pro 6G SSD     | 1         | 2      | 5.26%   |
| Mushkin MKNSSDCR120GB              | 1         | 1      | 5.26%   |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 5.26%   |
| Crucial CT1000MX500SSD1 1TB        | 1         | 2      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 7      | 31.58%  |
| Toshiba  | 4         | 4      | 21.05%  |
| WDC      | 3         | 5      | 15.79%  |
| SanDisk  | 2         | 2      | 10.53%  |
| OWC      | 1         | 2      | 5.26%   |
| Mushkin  | 1         | 1      | 5.26%   |
| Kingston | 1         | 1      | 5.26%   |
| Crucial  | 1         | 2      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 50%     |
| Toshiba | 4         | 4      | 33.33%  |
| WDC     | 2         | 3      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 14     | 63.16%  |
| SSD  | 7         | 10     | 36.84%  |

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
| Works    | 76        | 113    | 69.72%  |
| Malfunc  | 19        | 24     | 17.43%  |
| Detected | 12        | 19     | 11.01%  |
| Failed   | 2         | 3      | 1.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 70        | 67.96%  |
| AMD                          | 13        | 12.62%  |
| Samsung Electronics          | 5         | 4.85%   |
| SanDisk                      | 4         | 3.88%   |
| Nvidia                       | 2         | 1.94%   |
| Kingston Technology Company  | 2         | 1.94%   |
| Silicon Motion               | 1         | 0.97%   |
| Shenzhen Longsys Electronics | 1         | 0.97%   |
| Phison Electronics           | 1         | 0.97%   |
| Micron Technology            | 1         | 0.97%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.97%   |
| Marvell Technology Group     | 1         | 0.97%   |
| KIOXIA                       | 1         | 0.97%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                                              | Computers | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                                                | 10        | 8.2%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 6         | 4.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 5         | 4.1%    |
| Intel Volume Management Device NVMe RAID Controller                                                                | 4         | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 4         | 3.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 4         | 3.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 4         | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]                                     | 4         | 3.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 3         | 2.46%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 3         | 2.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 3         | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 3         | 2.46%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)                                          | 2         | 1.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 2         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                                                 | 2         | 1.64%   |
| Intel SATA Controller [RAID mode]                                                                                  | 2         | 1.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                                                  | 2         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 2         | 1.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 2         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                                                     | 2         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 2         | 1.64%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                                                   | 2         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                                                  | 2         | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                                               | 2         | 1.64%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 1         | 0.82%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 1         | 0.82%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                                            | 1         | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                                               | 1         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 1         | 0.82%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 1         | 0.82%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                                                           | 1         | 0.82%   |
| Nvidia MCP61 SATA Controller                                                                                       | 1         | 0.82%   |
| Nvidia MCP61 IDE                                                                                                   | 1         | 0.82%   |
| Micron 2210 NVMe SSD [Cobain]                                                                                      | 1         | 0.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 1         | 0.82%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                                                          | 1         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 1         | 0.82%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                                               | 1         | 0.82%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                                               | 1         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                                                                | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 67        | 59.29%  |
| NVMe | 19        | 16.81%  |
| IDE  | 16        | 14.16%  |
| RAID | 11        | 9.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 74        | 82.22%  |
| AMD    | 16        | 17.78%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 2.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 2.22%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 2.22%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 2.22%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 2.22%   |
| Intel Celeron CPU N2807 @ 1.58GHz           | 2         | 2.22%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 2.22%   |
| Intel Xeon CPU E5640 @ 2.67GHz              | 1         | 1.11%   |
| Intel Xeon CPU E5-2643 0 @ 3.30GHz          | 1         | 1.11%   |
| Intel Pentium Gold G6405 CPU @ 4.10GHz      | 1         | 1.11%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 1.11%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.11%   |
| Intel Pentium D CPU 2.80GHz                 | 1         | 1.11%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.11%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.11%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.11%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.11%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.11%   |
| Intel Core i7-4785T CPU @ 2.20GHz           | 1         | 1.11%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.11%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 1         | 1.11%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 1.11%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 1         | 1.11%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 1         | 1.11%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 1         | 1.11%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 1.11%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 1.11%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 1.11%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1         | 1.11%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.11%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1         | 1.11%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.11%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1         | 1.11%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 18        | 20%     |
| Intel Core i7           | 12        | 13.33%  |
| Other                   | 9         | 10%     |
| Intel Core 2 Duo        | 9         | 10%     |
| Intel Celeron           | 7         | 7.78%   |
| Intel Core i3           | 6         | 6.67%   |
| Intel Atom              | 5         | 5.56%   |
| AMD Ryzen 5             | 4         | 4.44%   |
| Intel Xeon              | 2         | 2.22%   |
| Intel Pentium           | 2         | 2.22%   |
| AMD GX                  | 2         | 2.22%   |
| Intel Pentium Gold      | 1         | 1.11%   |
| Intel Pentium Dual-Core | 1         | 1.11%   |
| Intel Pentium Dual      | 1         | 1.11%   |
| Intel Pentium D         | 1         | 1.11%   |
| Intel Celeron M         | 1         | 1.11%   |
| AMD Ryzen 7             | 1         | 1.11%   |
| AMD PRO A10             | 1         | 1.11%   |
| AMD Phenom II           | 1         | 1.11%   |
| AMD FX                  | 1         | 1.11%   |
| AMD E                   | 1         | 1.11%   |
| AMD Athlon II Dual-Core | 1         | 1.11%   |
| AMD Athlon II           | 1         | 1.11%   |
| AMD A4                  | 1         | 1.11%   |
| AMD A12                 | 1         | 1.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 46        | 51.11%  |
| 4      | 25        | 27.78%  |
| 6      | 6         | 6.67%   |
| 1      | 5         | 5.56%   |
| 8      | 3         | 3.33%   |
| 12     | 2         | 2.22%   |
| 3      | 2         | 2.22%   |
| 10     | 1         | 1.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 89        | 98.89%  |
| 2      | 1         | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 52        | 57.78%  |
| 1      | 38        | 42.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 88        | 97.78%  |
| 32-bit         | 2         | 2.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 30.53%  |
| 0x1067a    | 5         | 5.26%   |
| 0x306a9    | 4         | 4.21%   |
| 0x206a7    | 3         | 3.16%   |
| 0x20655    | 3         | 3.16%   |
| 0x106ca    | 3         | 3.16%   |
| 0x906ea    | 2         | 2.11%   |
| 0x906e9    | 2         | 2.11%   |
| 0x806ea    | 2         | 2.11%   |
| 0x806c1    | 2         | 2.11%   |
| 0x706e5    | 2         | 2.11%   |
| 0x406e3    | 2         | 2.11%   |
| 0x40651    | 2         | 2.11%   |
| 0x306d4    | 2         | 2.11%   |
| 0x306c3    | 2         | 2.11%   |
| 0x30678    | 2         | 2.11%   |
| 0x0600611a | 2         | 2.11%   |
| 0x010000c8 | 2         | 2.11%   |
| 0xf44      | 1         | 1.05%   |
| 0xa0671    | 1         | 1.05%   |
| 0xa0653    | 1         | 1.05%   |
| 0x906ed    | 1         | 1.05%   |
| 0x906c0    | 1         | 1.05%   |
| 0x906a4    | 1         | 1.05%   |
| 0x90675    | 1         | 1.05%   |
| 0x806d1    | 1         | 1.05%   |
| 0x6fd      | 1         | 1.05%   |
| 0x6fa      | 1         | 1.05%   |
| 0x6d8      | 1         | 1.05%   |
| 0x506e3    | 1         | 1.05%   |
| 0x506c9    | 1         | 1.05%   |
| 0x206d7    | 1         | 1.05%   |
| 0x206c2    | 1         | 1.05%   |
| 0x106c2    | 1         | 1.05%   |
| 0x10676    | 1         | 1.05%   |
| 0x0a50000d | 1         | 1.05%   |
| 0x08600106 | 1         | 1.05%   |
| 0x08108109 | 1         | 1.05%   |
| 0x0810100b | 1         | 1.05%   |
| 0x07030105 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 10        | 10.99%  |
| Penryn           | 7         | 7.69%   |
| IvyBridge        | 7         | 7.69%   |
| Haswell          | 7         | 7.69%   |
| SandyBridge      | 6         | 6.59%   |
| Westmere         | 5         | 5.49%   |
| Bonnell          | 5         | 5.49%   |
| Icelake          | 4         | 4.4%    |
| Core             | 4         | 4.4%    |
| Skylake          | 3         | 3.3%    |
| Silvermont       | 3         | 3.3%    |
| K10              | 3         | 3.3%    |
| Excavator        | 3         | 3.3%    |
| Unknown          | 3         | 3.3%    |
| Zen 3            | 2         | 2.2%    |
| Zen              | 2         | 2.2%    |
| TigerLake        | 2         | 2.2%    |
| Puma             | 2         | 2.2%    |
| Broadwell        | 2         | 2.2%    |
| Alderlake Hybrid | 2         | 2.2%    |
| Zen+             | 1         | 1.1%    |
| Zen 2            | 1         | 1.1%    |
| Tremont          | 1         | 1.1%    |
| Piledriver       | 1         | 1.1%    |
| P6               | 1         | 1.1%    |
| NetBurst         | 1         | 1.1%    |
| Goldmont         | 1         | 1.1%    |
| CometLake        | 1         | 1.1%    |
| Bobcat           | 1         | 1.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 62        | 59.62%  |
| AMD    | 24        | 23.08%  |
| Nvidia | 18        | 17.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 7         | 6.42%   |
| Intel UHD Graphics 620                                                        | 4         | 3.67%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 3.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 2.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 2.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 2.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 3         | 2.75%   |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 2.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 2.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller       | 3         | 2.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 2         | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 2         | 1.83%   |
| Intel HD Graphics 630                                                         | 2         | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.83%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 2         | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 2         | 1.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                               | 1         | 0.92%   |
| Nvidia MCP89 [GeForce 320M]                                                   | 1         | 0.92%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 1         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 1         | 0.92%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                      | 1         | 0.92%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 1         | 0.92%   |
| Nvidia GM108M [GeForce 930MX]                                                 | 1         | 0.92%   |
| Nvidia GF119 [GeForce GT 705]                                                 | 1         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.92%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 1         | 0.92%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.92%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                             | 1         | 0.92%   |
| Nvidia GA102 [GeForce RTX 3080]                                               | 1         | 0.92%   |
| Nvidia G84M [GeForce 8600M GT]                                                | 1         | 0.92%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                        | 1         | 0.92%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 0.92%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 1         | 0.92%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.92%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.92%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                     | 1         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 42        | 45.65%  |
| 1 x AMD        | 20        | 21.74%  |
| 1 x Nvidia     | 10        | 10.87%  |
| Intel + Nvidia | 9         | 9.78%   |
| 2 x Intel      | 7         | 7.61%   |
| Intel + AMD    | 3         | 3.26%   |
| 2 x AMD        | 1         | 1.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 87        | 95.6%   |
| Unknown     | 3         | 3.3%    |
| Proprietary | 1         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 57.61%  |
| 0.01-0.5   | 20        | 21.74%  |
| 3.01-4.0   | 5         | 5.43%   |
| 1.01-2.0   | 5         | 5.43%   |
| 0.51-1.0   | 4         | 4.35%   |
| 7.01-8.0   | 3         | 3.26%   |
| 2.01-3.0   | 1         | 1.09%   |
| 8.01-16.0  | 1         | 1.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 18        | 20.45%  |
| LG Display              | 12        | 13.64%  |
| Samsung Electronics     | 7         | 7.95%   |
| Chimei Innolux          | 5         | 5.68%   |
| Lenovo                  | 4         | 4.55%   |
| Chi Mei Optoelectronics | 4         | 4.55%   |
| BOE                     | 4         | 4.55%   |
| Dell                    | 3         | 3.41%   |
| Zoran                   | 2         | 2.27%   |
| Sceptre Tech            | 2         | 2.27%   |
| LG Philips              | 2         | 2.27%   |
| Insignia                | 2         | 2.27%   |
| Hewlett-Packard         | 2         | 2.27%   |
| Goldstar                | 2         | 2.27%   |
| Apple                   | 2         | 2.27%   |
| Vizio                   | 1         | 1.14%   |
| Sony                    | 1         | 1.14%   |
| Sharp                   | 1         | 1.14%   |
| SAC                     | 1         | 1.14%   |
| Philips                 | 1         | 1.14%   |
| Packard Bell            | 1         | 1.14%   |
| Mi                      | 1         | 1.14%   |
| MGN                     | 1         | 1.14%   |
| JDI                     | 1         | 1.14%   |
| InfoVision              | 1         | 1.14%   |
| HUAWEI                  | 1         | 1.14%   |
| EQV                     | 1         | 1.14%   |
| eMachines               | 1         | 1.14%   |
| BenQ                    | 1         | 1.14%   |
| ASUSTek Computer        | 1         | 1.14%   |
| AOC                     | 1         | 1.14%   |
| Acer                    | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Zoran HDMI TV ZRN0294 1360x768 500x281mm 22.6-inch                      | 2         | 2.27%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch           | 2         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 2.27%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch           | 2         | 2.27%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch           | 2         | 2.27%   |
| Vizio E320-B2 VIZ0095 1360x768 477x268mm 21.5-inch                      | 1         | 1.14%   |
| Sony TV SNY0101 1360x768                                                | 1         | 1.14%   |
| Sharp LCD Monitor SHP1416 1366x768 309x174mm 14.0-inch                  | 1         | 1.14%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch    | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch    | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 1.14%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch   | 1         | 1.14%   |
| Samsung Electronics C32R50x SAM7001 1920x1080 698x393mm 31.5-inch       | 1         | 1.14%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch       | 1         | 1.14%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                   | 1         | 1.14%   |
| Philips 221V PHL0888 1920x1080 477x268mm 21.5-inch                      | 1         | 1.14%   |
| Packard Bell Maestro225DXL PKB02F2 1920x1080 477x268mm 21.5-inch        | 1         | 1.14%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                        | 1         | 1.14%   |
| MGN MAGNA TV MGN0021 1920x1080 575x323mm 26.0-inch                      | 1         | 1.14%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch             | 1         | 1.14%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch             | 1         | 1.14%   |
| LG Display LP101WSB-TLN1 LGD026E 1024x600 224x126mm 10.1-inch           | 1         | 1.14%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD05D5 1920x1080 344x194mm 15.5-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch            | 1         | 1.14%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD0338 1600x900 344x194mm 15.5-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch             | 1         | 1.14%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch             | 1         | 1.14%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch                | 1         | 1.14%   |
| Lenovo LCD Monitor LEN4037 1280x800 303x190mm 14.1-inch                 | 1         | 1.14%   |
| Lenovo L29w-30 LEN66E5 2560x1080 673x284mm 28.8-inch                    | 1         | 1.14%   |
| Lenovo L24i-10 LEN65D6 1920x1080 527x296mm 23.8-inch                    | 1         | 1.14%   |
| JDI LAM125M007D JDI1402 1920x1080 277x156mm 12.5-inch                   | 1         | 1.14%   |
| Insignia NS-32D220NA18 BBY0050 1680x1050 708x398mm 32.0-inch            | 1         | 1.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 36        | 42.86%  |
| 1366x768 (WXGA)    | 20        | 23.81%  |
| 1280x800 (WXGA)    | 5         | 5.95%   |
| 1600x900 (HD+)     | 4         | 4.76%   |
| 1360x768           | 4         | 4.76%   |
| 1024x600           | 4         | 4.76%   |
| 2560x1440 (QHD)    | 3         | 3.57%   |
| 3840x2160 (4K)     | 2         | 2.38%   |
| 1680x1050 (WSXGA+) | 2         | 2.38%   |
| 2560x1080          | 1         | 1.19%   |
| 1920x1200 (WUXGA)  | 1         | 1.19%   |
| 1440x900 (WXGA+)   | 1         | 1.19%   |
| 1024x768 (XGA)     | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 27.27%  |
| 14      | 11        | 12.5%   |
| 24      | 6         | 6.82%   |
| 21      | 6         | 6.82%   |
| 17      | 5         | 5.68%   |
| 10      | 5         | 5.68%   |
| 31      | 4         | 4.55%   |
| 23      | 4         | 4.55%   |
| 22      | 3         | 3.41%   |
| 13      | 3         | 3.41%   |
| 11      | 3         | 3.41%   |
| 34      | 2         | 2.27%   |
| 32      | 2         | 2.27%   |
| 27      | 2         | 2.27%   |
| 12      | 2         | 2.27%   |
| 84      | 1         | 1.14%   |
| 54      | 1         | 1.14%   |
| 28      | 1         | 1.14%   |
| 26      | 1         | 1.14%   |
| 16      | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 39.77%  |
| 501-600     | 13        | 14.77%  |
| 201-300     | 12        | 13.64%  |
| 401-500     | 9         | 10.23%  |
| 351-400     | 7         | 7.95%   |
| 601-700     | 5         | 5.68%   |
| 701-800     | 4         | 4.55%   |
| 1501-2000   | 1         | 1.14%   |
| 1001-1500   | 1         | 1.14%   |
| Unknown     | 1         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 71        | 85.54%  |
| 16/10 | 9         | 10.84%  |
| 21/9  | 2         | 2.41%   |
| 4/3   | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 24        | 27.27%  |
| 201-250        | 17        | 19.32%  |
| 81-90          | 13        | 14.77%  |
| 351-500        | 7         | 7.95%   |
| 41-50          | 5         | 5.68%   |
| 121-130        | 4         | 4.55%   |
| 51-60          | 3         | 3.41%   |
| More than 1000 | 2         | 2.27%   |
| 61-70          | 2         | 2.27%   |
| 301-350        | 2         | 2.27%   |
| 251-300        | 2         | 2.27%   |
| 151-200        | 2         | 2.27%   |
| 71-80          | 1         | 1.14%   |
| 131-140        | 1         | 1.14%   |
| 111-120        | 1         | 1.14%   |
| 501-1000       | 1         | 1.14%   |
| Unknown        | 1         | 1.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 28        | 31.82%  |
| 101-120 | 26        | 29.55%  |
| 121-160 | 25        | 28.41%  |
| 1-50    | 4         | 4.55%   |
| 161-240 | 4         | 4.55%   |
| Unknown | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 82        | 89.13%  |
| 2     | 6         | 6.52%   |
| 0     | 4         | 4.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 44        | 31.21%  |
| Intel                           | 36        | 25.53%  |
| Qualcomm Atheros                | 24        | 17.02%  |
| Broadcom                        | 17        | 12.06%  |
| Qualcomm Atheros Communications | 3         | 2.13%   |
| MediaTek                        | 3         | 2.13%   |
| Ralink Technology               | 2         | 1.42%   |
| Marvell Technology Group        | 2         | 1.42%   |
| Broadcom Limited                | 2         | 1.42%   |
| Samsung Electronics             | 1         | 0.71%   |
| Research In Motion              | 1         | 0.71%   |
| Ralink                          | 1         | 0.71%   |
| Prolific Technology             | 1         | 0.71%   |
| Nvidia                          | 1         | 0.71%   |
| ICS Advent                      | 1         | 0.71%   |
| Dell                            | 1         | 0.71%   |
| Cal-Comp Electronic             | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 16.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 2.38%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 1.79%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3         | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 1.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 3         | 1.79%   |
| Intel Wireless 8265 / 8275                                             | 3         | 1.79%   |
| Intel Wireless 8260                                                    | 3         | 1.79%   |
| Intel Wireless 7260                                                    | 3         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 1.19%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 1.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 2         | 1.19%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                    | 2         | 1.19%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.19%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 1.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.19%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 1.19%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 2         | 1.19%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.6%    |
| Research In Motion BlackBerry                                          | 1         | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.6%    |
| Realtek RTL8191SEvA Wireless LAN Controller                            | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1         | 0.6%    |
| Realtek RTL8187B Wireless Adapter                                      | 1         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.6%    |
| Realtek 802.11ac NIC                                                   | 1         | 0.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 1         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 1         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 1         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 34.62%  |
| Qualcomm Atheros                | 20        | 25.64%  |
| Realtek Semiconductor           | 12        | 15.38%  |
| Broadcom                        | 11        | 14.1%   |
| Qualcomm Atheros Communications | 3         | 3.85%   |
| Ralink Technology               | 2         | 2.56%   |
| MediaTek                        | 2         | 2.56%   |
| Ralink                          | 1         | 1.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 7.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 5.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 3         | 3.85%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 3         | 3.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 3         | 3.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 3         | 3.85%   |
| Intel Wireless 8265 / 8275                                                            | 3         | 3.85%   |
| Intel Wireless 8260                                                                   | 3         | 3.85%   |
| Intel Wireless 7260                                                                   | 3         | 3.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 2.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 2.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 2         | 2.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 2         | 2.56%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 2.56%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 2         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.28%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                           | 1         | 1.28%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.28%   |
| Realtek RTL8187B Wireless Adapter                                                     | 1         | 1.28%   |
| Realtek 802.11ac NIC                                                                  | 1         | 1.28%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                 | 1         | 1.28%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 1.28%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.28%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.28%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 1.28%   |
| Intel Wireless 7265                                                                   | 1         | 1.28%   |
| Intel WiFi Link 5100                                                                  | 1         | 1.28%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 1         | 1.28%   |
| Intel Wi-Fi 6 AX201 160MHz                                                            | 1         | 1.28%   |
| Intel Wi-Fi 6 AX200                                                                   | 1         | 1.28%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 1         | 1.28%   |
| Intel Raptor Lake PCH CNVi WiFi                                                       | 1         | 1.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 1         | 1.28%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 39        | 45.88%  |
| Intel                    | 22        | 25.88%  |
| Broadcom                 | 9         | 10.59%  |
| Qualcomm Atheros         | 7         | 8.24%   |
| Marvell Technology Group | 2         | 2.35%   |
| Broadcom Limited         | 2         | 2.35%   |
| Research In Motion       | 1         | 1.18%   |
| Nvidia                   | 1         | 1.18%   |
| MediaTek                 | 1         | 1.18%   |
| ICS Advent               | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 28        | 32.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 9.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 3.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 2.35%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 2.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 2.35%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.35%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 2.35%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 2.35%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 2.35%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 2         | 2.35%   |
| Research In Motion BlackBerry                                          | 1         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1.18%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 1.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 1.18%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.18%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 1.18%   |
| MediaTek TANK2                                                         | 1         | 1.18%   |
| Intel PRO/100 VE Network Connection                                    | 1         | 1.18%   |
| Intel NM10/ICH7 Family LAN Controller                                  | 1         | 1.18%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 1.18%   |
| Intel Ethernet Controller I225-V                                       | 1         | 1.18%   |
| Intel Ethernet Controller I225-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 1.18%   |
| Intel Ethernet Connection (14) I219-V                                  | 1         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 1.18%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1         | 1.18%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 1         | 1.18%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 1.18%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 1         | 1.18%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 1         | 1.18%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.18%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 1.18%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.18%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 1         | 1.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 80        | 50%     |
| WiFi     | 75        | 46.88%  |
| Modem    | 5         | 3.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 53        | 55.21%  |
| Ethernet | 43        | 44.79%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 60        | 65.93%  |
| 1     | 29        | 31.87%  |
| 3     | 1         | 1.1%    |
| 0     | 1         | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 61        | 67.03%  |
| Yes  | 30        | 32.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 31.48%  |
| Qualcomm Atheros Communications | 7         | 12.96%  |
| Apple                           | 6         | 11.11%  |
| Lite-On Technology              | 5         | 9.26%   |
| Realtek Semiconductor           | 4         | 7.41%   |
| IMC Networks                    | 3         | 5.56%   |
| Broadcom                        | 3         | 5.56%   |
| MediaTek                        | 2         | 3.7%    |
| Dell                            | 2         | 3.7%    |
| Toshiba                         | 1         | 1.85%   |
| Ralink                          | 1         | 1.85%   |
| Hewlett-Packard                 | 1         | 1.85%   |
| Foxconn / Hon Hai               | 1         | 1.85%   |
| Cambridge Silicon Radio         | 1         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 9         | 16.67%  |
| Intel AX201 Bluetooth                               | 4         | 7.41%   |
| Realtek Bluetooth Radio                             | 3         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 5.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 5.56%   |
| MediaTek Wireless_Device                            | 2         | 3.7%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 3.7%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 3.7%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 3.7%    |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.85%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.85%   |
| Lite-On Bluetooth USB Host Controller               | 1         | 1.85%   |
| Lite-On Bluetooth Radio                             | 1         | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.85%   |
| Intel AX211 Bluetooth                               | 1         | 1.85%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.85%   |
| IMC Networks Bluetooth Device                       | 1         | 1.85%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.85%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.85%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.85%   |
| Broadcom BCM20702A0                                 | 1         | 1.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.85%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.85%   |
| Apple Bluetooth Host Controller                     | 1         | 1.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 72        | 62.61%  |
| AMD                   | 22        | 19.13%  |
| Nvidia                | 13        | 11.3%   |
| Texas Instruments     | 1         | 0.87%   |
| SAVITECH              | 1         | 0.87%   |
| Roland                | 1         | 0.87%   |
| Realtek Semiconductor | 1         | 0.87%   |
| JMTek                 | 1         | 0.87%   |
| Huawei Technologies   | 1         | 0.87%   |
| C-Media Electronics   | 1         | 0.87%   |
| Anlya.cn              | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 4.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 6         | 4.38%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 6         | 4.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 3.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 3.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 2.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 2.19%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.19%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 2.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.46%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.46%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.46%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.46%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.46%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.73%   |
| SAVITECH USB HIFI Audio                                                    | 1         | 0.73%   |
| Roland QUAD-CAPTURE                                                        | 1         | 0.73%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.73%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.73%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.73%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| SK hynix                     | 19        | 16.96%  |
| Unknown                      | 16        | 14.29%  |
| Samsung Electronics          | 15        | 13.39%  |
| Crucial                      | 12        | 10.71%  |
| Kingston                     | 11        | 9.82%   |
| Micron Technology            | 9         | 8.04%   |
| A-DATA Technology            | 5         | 4.46%   |
| Elpida                       | 4         | 3.57%   |
| Corsair                      | 4         | 3.57%   |
| Timetec                      | 3         | 2.68%   |
| Ramaxel Technology           | 2         | 1.79%   |
| Nanya Technology             | 2         | 1.79%   |
| Unknown (0xFFFF000000000000) | 1         | 0.89%   |
| Unknown (08C8)               | 1         | 0.89%   |
| Toshiba                      | 1         | 0.89%   |
| Team                         | 1         | 0.89%   |
| SK_Hynix                     | 1         | 0.89%   |
| Patriot                      | 1         | 0.89%   |
| Infineon                     | 1         | 0.89%   |
| G.Skill                      | 1         | 0.89%   |
| ASint Technology             | 1         | 0.89%   |
| Unknown                      | 1         | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                      | 3         | 2.5%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.67%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 1.67%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s            | 2         | 1.67%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s  | 2         | 1.67%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                     | 2         | 1.67%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                     | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3                              | 1         | 0.83%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                            | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3                              | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2                              | 1         | 0.83%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR3 667MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                      | 1         | 0.83%   |
| Unknown (0xFFFF000000000000) RAM Module 2GB SODIMM DDR2 667MT/s | 1         | 0.83%   |
| Unknown (08C8) RAM LMKUFG68AHFHD-32A 16GB DIMM DDR4 3200MT/s    | 1         | 0.83%   |
| Toshiba RAM 8HTF12864HDY-800G1 4096MB SODIMM 1066MT/s           | 1         | 0.83%   |
| Toshiba RAM 64T128020EDL2.5C2 4096MB SODIMM 1066MT/s            | 1         | 0.83%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                   | 1         | 0.83%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s              | 1         | 0.83%   |
| SK_Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.83%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR4 3200MT/s            | 1         | 0.83%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1067MT/s                    | 1         | 0.83%   |
| SK hynix RAM Module 2GB SODIMM DDR2 533MT/s                     | 1         | 0.83%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1334MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                 | 1         | 0.83%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s            | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1333MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s          | 1         | 0.83%   |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s       | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 39        | 44.83%  |
| DDR4    | 27        | 31.03%  |
| DDR2    | 13        | 14.94%  |
| LPDDR4  | 5         | 5.75%   |
| SDRAM   | 1         | 1.15%   |
| LPDDR3  | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 65.91%  |
| DIMM         | 21        | 23.86%  |
| Row Of Chips | 6         | 6.82%   |
| Unknown      | 2         | 2.27%   |
| Chip         | 1         | 1.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 31        | 32.63%  |
| 8192  | 30        | 31.58%  |
| 2048  | 19        | 20%     |
| 1024  | 6         | 6.32%   |
| 16384 | 4         | 4.21%   |
| 32768 | 3         | 3.16%   |
| 512   | 2         | 2.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 24        | 24.74%  |
| 3200    | 10        | 10.31%  |
| 667     | 10        | 10.31%  |
| 2667    | 8         | 8.25%   |
| 2400    | 6         | 6.19%   |
| 1333    | 6         | 6.19%   |
| 1067    | 5         | 5.15%   |
| 1334    | 3         | 3.09%   |
| 533     | 3         | 3.09%   |
| 4267    | 2         | 2.06%   |
| 3733    | 2         | 2.06%   |
| 1800    | 2         | 2.06%   |
| 1066    | 2         | 2.06%   |
| Unknown | 2         | 2.06%   |
| 8400    | 1         | 1.03%   |
| 4266    | 1         | 1.03%   |
| 3600    | 1         | 1.03%   |
| 3066    | 1         | 1.03%   |
| 2733    | 1         | 1.03%   |
| 2666    | 1         | 1.03%   |
| 2267    | 1         | 1.03%   |
| 2133    | 1         | 1.03%   |
| 1867    | 1         | 1.03%   |
| 1866    | 1         | 1.03%   |
| 975     | 1         | 1.03%   |
| 800     | 1         | 1.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 50%     |
| Hewlett-Packard     | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 2         | 50%     |
| HP DeskJet F4200 series               | 1         | 25%     |
| HP DeskJet 2130 series                | 1         | 25%     |

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
| Chicony Electronics                    | 16        | 32.65%  |
| Microdia                               | 4         | 8.16%   |
| Apple                                  | 4         | 8.16%   |
| Sunplus Innovation Technology          | 3         | 6.12%   |
| Realtek Semiconductor                  | 3         | 6.12%   |
| Quanta                                 | 2         | 4.08%   |
| Logitech                               | 2         | 4.08%   |
| IMC Networks                           | 2         | 4.08%   |
| Bison Electronics                      | 2         | 4.08%   |
| ALi                                    | 2         | 4.08%   |
| Syntek                                 | 1         | 2.04%   |
| Suyin                                  | 1         | 2.04%   |
| SunplusIT                              | 1         | 2.04%   |
| Sonix Technology                       | 1         | 2.04%   |
| Ricoh                                  | 1         | 2.04%   |
| Primax Electronics                     | 1         | 2.04%   |
| Luxvisions Innotech Limited            | 1         | 2.04%   |
| Lite-On Technology                     | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 2.04%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                              | 3         | 6.12%   |
| Chicony HD WebCam                                   | 3         | 6.12%   |
| Chicony HD WebCam (Acer)                            | 2         | 4.08%   |
| Apple Built-in iSight                               | 2         | 4.08%   |
| Syntek Integrated Camera                            | 1         | 2.04%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 2.04%   |
| SunplusIT 1080p FHD Camera                          | 1         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 2.04%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 2.04%   |
| Sunplus HD WebCam                                   | 1         | 2.04%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 2.04%   |
| Ricoh USB2.0 Camera                                 | 1         | 2.04%   |
| Realtek Lenovo EasyCamera                           | 1         | 2.04%   |
| Realtek EasyCamera                                  | 1         | 2.04%   |
| Realtek 2SF022                                      | 1         | 2.04%   |
| Quanta HP 2.0MP High Definition Webcam              | 1         | 2.04%   |
| Quanta HD User Facing                               | 1         | 2.04%   |
| Primax webcam                                       | 1         | 2.04%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 2.04%   |
| Microdia Integrated_Webcam_HD                       | 1         | 2.04%   |
| Microdia Integrated Webcam                          | 1         | 2.04%   |
| Microdia Dell Integrated HD Webcam                  | 1         | 2.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 2.04%   |
| Logitech Logitech Webcam C160                       | 1         | 2.04%   |
| Logitech HD Pro Webcam C920                         | 1         | 2.04%   |
| Lite-On Integrated Camera                           | 1         | 2.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 2.04%   |
| IMC Networks Integrated Camera                      | 1         | 2.04%   |
| Chicony WebCam                                      | 1         | 2.04%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 2.04%   |
| Chicony Integrated Camera (1280x720@30)             | 1         | 2.04%   |
| Chicony Integrated Camera                           | 1         | 2.04%   |
| Chicony HP Integrated Webcam                        | 1         | 2.04%   |
| Chicony HP HD Camera                                | 1         | 2.04%   |
| Chicony EasyCamera                                  | 1         | 2.04%   |
| Chicony Camera                                      | 1         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 1         | 2.04%   |
| Bison Integrated Camera                             | 1         | 2.04%   |
| Bison BisonCam, NB Pro                              | 1         | 2.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 1         | 2.04%   |

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
| Focal-systems.Corp FT9201Fingerprint.Ì  | 1         | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model         | Computers | Percent |
|---------------|-----------|---------|
| Broadcom 5880 | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 69        | 75.82%  |
| 1     | 20        | 21.98%  |
| 2     | 2         | 2.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 10        | 41.67%  |
| Fingerprint reader       | 5         | 20.83%  |
| Multimedia controller    | 2         | 8.33%   |
| Camera                   | 2         | 8.33%   |
| Storage                  | 1         | 4.17%   |
| Net/wireless             | 1         | 4.17%   |
| Communication controller | 1         | 4.17%   |
| Chipcard                 | 1         | 4.17%   |
| Bluetooth                | 1         | 4.17%   |

