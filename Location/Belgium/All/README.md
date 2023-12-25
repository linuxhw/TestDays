Linux in Belgium - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belgium/Desktop/README.md) and [notebooks](/Location/Belgium/Notebook/README.md).

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

Total: 3157

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [bdb39d60de](https://linux-hardware.org/?probe=bdb39d60de) | Dec 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [ef80f96d40](https://linux-hardware.org/?probe=ef80f96d40) | Dec 23, 2023 |
| Danew         | Dbook 131                   | Notebook    | [a3880bd02c](https://linux-hardware.org/?probe=a3880bd02c) | Dec 23, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [9ff527cfd0](https://linux-hardware.org/?probe=9ff527cfd0) | Dec 22, 2023 |
| Danew         | Dbook 131                   | Notebook    | [0568c9bdbf](https://linux-hardware.org/?probe=0568c9bdbf) | Dec 22, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [6e4bcb9311](https://linux-hardware.org/?probe=6e4bcb9311) | Dec 21, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [c7acd610c0](https://linux-hardware.org/?probe=c7acd610c0) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [45d168f910](https://linux-hardware.org/?probe=45d168f910) | Dec 17, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [74584680bb](https://linux-hardware.org/?probe=74584680bb) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [b935091ecd](https://linux-hardware.org/?probe=b935091ecd) | Dec 17, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [14b5a5a3ca](https://linux-hardware.org/?probe=14b5a5a3ca) | Dec 17, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [88afe6fd6a](https://linux-hardware.org/?probe=88afe6fd6a) | Dec 17, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [1c2f8035bb](https://linux-hardware.org/?probe=1c2f8035bb) | Dec 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [60e69d071e](https://linux-hardware.org/?probe=60e69d071e) | Dec 17, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [41fd53bbff](https://linux-hardware.org/?probe=41fd53bbff) | Dec 16, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [0462d406ad](https://linux-hardware.org/?probe=0462d406ad) | Dec 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [a2e31b8b20](https://linux-hardware.org/?probe=a2e31b8b20) | Dec 15, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [f595f75af9](https://linux-hardware.org/?probe=f595f75af9) | Dec 15, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [8b05ff3549](https://linux-hardware.org/?probe=8b05ff3549) | Dec 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [971233beec](https://linux-hardware.org/?probe=971233beec) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| AZW           | EQ                          | Desktop     | [b6aa615ccf](https://linux-hardware.org/?probe=b6aa615ccf) | Dec 14, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [1415106440](https://linux-hardware.org/?probe=1415106440) | Dec 14, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2c8846a637](https://linux-hardware.org/?probe=2c8846a637) | Dec 12, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [9c7a40207b](https://linux-hardware.org/?probe=9c7a40207b) | Dec 11, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [f24c11f324](https://linux-hardware.org/?probe=f24c11f324) | Dec 11, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [78562df77d](https://linux-hardware.org/?probe=78562df77d) | Dec 11, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [96ea36be06](https://linux-hardware.org/?probe=96ea36be06) | Dec 10, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2b2da67e8f](https://linux-hardware.org/?probe=2b2da67e8f) | Dec 09, 2023 |
| Unknown       | NY-02                       | Notebook    | [d894eced77](https://linux-hardware.org/?probe=d894eced77) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [cf832dba27](https://linux-hardware.org/?probe=cf832dba27) | Dec 08, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [be2c5bcf98](https://linux-hardware.org/?probe=be2c5bcf98) | Dec 07, 2023 |
| Unknown       | NY-02                       | Notebook    | [8d1cd2ab24](https://linux-hardware.org/?probe=8d1cd2ab24) | Dec 07, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [665a5984d2](https://linux-hardware.org/?probe=665a5984d2) | Dec 07, 2023 |
| Medion        | B550A4-EM                   | Desktop     | [bd40049c5d](https://linux-hardware.org/?probe=bd40049c5d) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [b118593b9d](https://linux-hardware.org/?probe=b118593b9d) | Dec 06, 2023 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [cf4258942d](https://linux-hardware.org/?probe=cf4258942d) | Dec 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [d4ece1c445](https://linux-hardware.org/?probe=d4ece1c445) | Dec 06, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [ee4cab6d84](https://linux-hardware.org/?probe=ee4cab6d84) | Dec 06, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [6c6c722015](https://linux-hardware.org/?probe=6c6c722015) | Dec 06, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a47e6e3616](https://linux-hardware.org/?probe=a47e6e3616) | Dec 05, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a0912ee339](https://linux-hardware.org/?probe=a0912ee339) | Dec 05, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | Notebook    | [a8c094f376](https://linux-hardware.org/?probe=a8c094f376) | Dec 04, 2023 |
| AZW           | EQ                          | Desktop     | [c2dedbf2f3](https://linux-hardware.org/?probe=c2dedbf2f3) | Dec 04, 2023 |
| Medion        | MS-7848                     | Desktop     | [e13ee73f9e](https://linux-hardware.org/?probe=e13ee73f9e) | Dec 04, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [5412eafff1](https://linux-hardware.org/?probe=5412eafff1) | Dec 03, 2023 |
| AZW           | MINI S 10                   | Desktop     | [2775dce4a8](https://linux-hardware.org/?probe=2775dce4a8) | Dec 03, 2023 |
| AZW           | MINI S 10                   | Desktop     | [ca55c41f60](https://linux-hardware.org/?probe=ca55c41f60) | Dec 03, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [856a01d874](https://linux-hardware.org/?probe=856a01d874) | Dec 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b4a66e7840](https://linux-hardware.org/?probe=b4a66e7840) | Dec 02, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [1767ff70e0](https://linux-hardware.org/?probe=1767ff70e0) | Dec 01, 2023 |
| Unknown       | HX90                        | Desktop     | [e4bfb6b06a](https://linux-hardware.org/?probe=e4bfb6b06a) | Nov 29, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [8ed2e1621c](https://linux-hardware.org/?probe=8ed2e1621c) | Nov 29, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0d6a4cd900](https://linux-hardware.org/?probe=0d6a4cd900) | Nov 28, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [1fda4e1f6d](https://linux-hardware.org/?probe=1fda4e1f6d) | Nov 28, 2023 |
| PIONEERPOS    | STEALTH-ASTERIX             | Desktop     | [5f429c0aca](https://linux-hardware.org/?probe=5f429c0aca) | Nov 28, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [f8cdbfddcd](https://linux-hardware.org/?probe=f8cdbfddcd) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| AZW           | MINI S                      | Desktop     | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [6418e60f5a](https://linux-hardware.org/?probe=6418e60f5a) | Nov 27, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [597c5faf3a](https://linux-hardware.org/?probe=597c5faf3a) | Nov 27, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [22a88185d6](https://linux-hardware.org/?probe=22a88185d6) | Nov 26, 2023 |
| HP            | 3397                        | Desktop     | [a846952acf](https://linux-hardware.org/?probe=a846952acf) | Nov 26, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [2d09c86fa7](https://linux-hardware.org/?probe=2d09c86fa7) | Nov 26, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [2009f6493b](https://linux-hardware.org/?probe=2009f6493b) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [f8eb14af89](https://linux-hardware.org/?probe=f8eb14af89) | Nov 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1462624ea](https://linux-hardware.org/?probe=d1462624ea) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| ASRock        | B760M PG SONIC WiFi         | Desktop     | [48b39eec4f](https://linux-hardware.org/?probe=48b39eec4f) | Nov 23, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [1ad50e2862](https://linux-hardware.org/?probe=1ad50e2862) | Nov 23, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [8cf21a227b](https://linux-hardware.org/?probe=8cf21a227b) | Nov 22, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [e1abb4721b](https://linux-hardware.org/?probe=e1abb4721b) | Nov 21, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | Notebook    | [2fe5c073ce](https://linux-hardware.org/?probe=2fe5c073ce) | Nov 19, 2023 |
| Lenovo        | ThinkPad E520 11437UG       | Notebook    | [422931d9a6](https://linux-hardware.org/?probe=422931d9a6) | Nov 19, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6d6dcd50b3](https://linux-hardware.org/?probe=6d6dcd50b3) | Nov 19, 2023 |
| HP            | Pavilion 17                 | Notebook    | [00c2d45d1d](https://linux-hardware.org/?probe=00c2d45d1d) | Nov 19, 2023 |
| Acer          | Predator G3620              | Desktop     | [16a30abb8e](https://linux-hardware.org/?probe=16a30abb8e) | Nov 19, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | Notebook    | [fd99bf5f2a](https://linux-hardware.org/?probe=fd99bf5f2a) | Nov 18, 2023 |
| ASRock        | Z270 Gaming K4              | Desktop     | [6a19659d85](https://linux-hardware.org/?probe=6a19659d85) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | Desktop     | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c7e379951a](https://linux-hardware.org/?probe=c7e379951a) | Nov 18, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [43e84fe856](https://linux-hardware.org/?probe=43e84fe856) | Nov 17, 2023 |
| Lenovo        | B70-80 80MR                 | Notebook    | [84f08f46f0](https://linux-hardware.org/?probe=84f08f46f0) | Nov 15, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [3c8c80409b](https://linux-hardware.org/?probe=3c8c80409b) | Nov 15, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [1f783e1865](https://linux-hardware.org/?probe=1f783e1865) | Nov 14, 2023 |
| Lenovo        | ThinkPad X250 20CLS2P703    | Notebook    | [b15506a2b9](https://linux-hardware.org/?probe=b15506a2b9) | Nov 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b806051ada](https://linux-hardware.org/?probe=b806051ada) | Nov 14, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [1c5e9077a8](https://linux-hardware.org/?probe=1c5e9077a8) | Nov 12, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [3595c8f9d1](https://linux-hardware.org/?probe=3595c8f9d1) | Nov 12, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [03a619e930](https://linux-hardware.org/?probe=03a619e930) | Nov 11, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [6885ccb289](https://linux-hardware.org/?probe=6885ccb289) | Nov 11, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8bdbf5b0d9](https://linux-hardware.org/?probe=8bdbf5b0d9) | Nov 11, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [bad6c674dd](https://linux-hardware.org/?probe=bad6c674dd) | Nov 11, 2023 |
| Lenovo        | ThinkPad P50s 20FL000EMS    | Notebook    | [81d1c107cc](https://linux-hardware.org/?probe=81d1c107cc) | Nov 11, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fd132476fe](https://linux-hardware.org/?probe=fd132476fe) | Nov 09, 2023 |
| Fujitsu Si... | LIFEBOOK S7220              | Notebook    | [52f980a58c](https://linux-hardware.org/?probe=52f980a58c) | Nov 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [94289ec884](https://linux-hardware.org/?probe=94289ec884) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | Notebook    | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [598b5837e5](https://linux-hardware.org/?probe=598b5837e5) | Nov 07, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [479317e80f](https://linux-hardware.org/?probe=479317e80f) | Nov 07, 2023 |
| Dell          | Latitude 5590               | Notebook    | [0290e5fd1a](https://linux-hardware.org/?probe=0290e5fd1a) | Nov 06, 2023 |
| Unknown       | HX90                        | Desktop     | [bc832d475f](https://linux-hardware.org/?probe=bc832d475f) | Nov 06, 2023 |
| Unknown       | HX90                        | Desktop     | [91269ec2b8](https://linux-hardware.org/?probe=91269ec2b8) | Nov 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e56fc59b28](https://linux-hardware.org/?probe=e56fc59b28) | Nov 06, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [ce42858c1f](https://linux-hardware.org/?probe=ce42858c1f) | Nov 06, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [67a67e246c](https://linux-hardware.org/?probe=67a67e246c) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [247cc16161](https://linux-hardware.org/?probe=247cc16161) | Nov 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5c50c142b3](https://linux-hardware.org/?probe=5c50c142b3) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5e5e97717a](https://linux-hardware.org/?probe=5e5e97717a) | Nov 04, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [1636a231b2](https://linux-hardware.org/?probe=1636a231b2) | Nov 04, 2023 |
| ASUSTek       | M4N68T-M                    | Desktop     | [582304a8c5](https://linux-hardware.org/?probe=582304a8c5) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [ebf86ce161](https://linux-hardware.org/?probe=ebf86ce161) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [5eada91f48](https://linux-hardware.org/?probe=5eada91f48) | Nov 04, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [18f018a8ae](https://linux-hardware.org/?probe=18f018a8ae) | Nov 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [602a2268e2](https://linux-hardware.org/?probe=602a2268e2) | Nov 02, 2023 |
| ASRock        | B760M PG SONIC WiFi         | Desktop     | [71e1e69f30](https://linux-hardware.org/?probe=71e1e69f30) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| AMI           | Intel                       | Desktop     | [8685e22886](https://linux-hardware.org/?probe=8685e22886) | Nov 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e57ba14bc9](https://linux-hardware.org/?probe=e57ba14bc9) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [826dc000ff](https://linux-hardware.org/?probe=826dc000ff) | Nov 01, 2023 |
| AMI           | Intel                       | Desktop     | [fa89237919](https://linux-hardware.org/?probe=fa89237919) | Nov 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [031a3670bd](https://linux-hardware.org/?probe=031a3670bd) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [34fe4c8733](https://linux-hardware.org/?probe=34fe4c8733) | Nov 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7c07fc9bbe](https://linux-hardware.org/?probe=7c07fc9bbe) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f1d5844389](https://linux-hardware.org/?probe=f1d5844389) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [40deedc435](https://linux-hardware.org/?probe=40deedc435) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [57d643d36b](https://linux-hardware.org/?probe=57d643d36b) | Oct 31, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b62cfa508b](https://linux-hardware.org/?probe=b62cfa508b) | Oct 30, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [17de10e607](https://linux-hardware.org/?probe=17de10e607) | Oct 29, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [ad21a28397](https://linux-hardware.org/?probe=ad21a28397) | Oct 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [b26c6bcd4b](https://linux-hardware.org/?probe=b26c6bcd4b) | Oct 28, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [77541125c0](https://linux-hardware.org/?probe=77541125c0) | Oct 28, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [166a51fa8d](https://linux-hardware.org/?probe=166a51fa8d) | Oct 27, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [637a5897b7](https://linux-hardware.org/?probe=637a5897b7) | Oct 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| ASUSTek       | P6X58-E-WS                  | Desktop     | [abb9f306b8](https://linux-hardware.org/?probe=abb9f306b8) | Oct 25, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [0d52b12158](https://linux-hardware.org/?probe=0d52b12158) | Oct 25, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [274089a92c](https://linux-hardware.org/?probe=274089a92c) | Oct 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3dcdf62e73](https://linux-hardware.org/?probe=3dcdf62e73) | Oct 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [948da1d335](https://linux-hardware.org/?probe=948da1d335) | Oct 22, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [38d48bd5b5](https://linux-hardware.org/?probe=38d48bd5b5) | Oct 22, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [3056eeecf5](https://linux-hardware.org/?probe=3056eeecf5) | Oct 21, 2023 |
| EUROCOM       | Tornado F5                  | Notebook    | [25b7095754](https://linux-hardware.org/?probe=25b7095754) | Oct 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [f8330df761](https://linux-hardware.org/?probe=f8330df761) | Oct 20, 2023 |
| ASRock        | Z270 Gaming K4              | Desktop     | [7de6bcb3b6](https://linux-hardware.org/?probe=7de6bcb3b6) | Oct 19, 2023 |
| LG Electro... | 16T90R-K.ADB9U1             | Convertible | [81f32f2ac2](https://linux-hardware.org/?probe=81f32f2ac2) | Oct 19, 2023 |
| AMI           | Intel                       | Convertible | [38a3df30fe](https://linux-hardware.org/?probe=38a3df30fe) | Oct 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [18922baf01](https://linux-hardware.org/?probe=18922baf01) | Oct 15, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [79a68614cb](https://linux-hardware.org/?probe=79a68614cb) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | Desktop     | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| Dell          | Precision 7720              | Notebook    | [574a292adb](https://linux-hardware.org/?probe=574a292adb) | Oct 14, 2023 |
| Acer          | Aspire C24-963              | All in one  | [2e9ddbb840](https://linux-hardware.org/?probe=2e9ddbb840) | Oct 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [00fc33d73e](https://linux-hardware.org/?probe=00fc33d73e) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [ef43db2db3](https://linux-hardware.org/?probe=ef43db2db3) | Oct 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [86ca92698e](https://linux-hardware.org/?probe=86ca92698e) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fb98eb2395](https://linux-hardware.org/?probe=fb98eb2395) | Oct 11, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [3ceccfff97](https://linux-hardware.org/?probe=3ceccfff97) | Oct 11, 2023 |
| MSI           | H81M-E33                    | Desktop     | [471e20b9ee](https://linux-hardware.org/?probe=471e20b9ee) | Oct 11, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [d7418fb673](https://linux-hardware.org/?probe=d7418fb673) | Oct 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [598f31dfeb](https://linux-hardware.org/?probe=598f31dfeb) | Oct 10, 2023 |
| ASRock        | Z270 Gaming K4              | Desktop     | [450e9268be](https://linux-hardware.org/?probe=450e9268be) | Oct 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f95efe1e80](https://linux-hardware.org/?probe=f95efe1e80) | Oct 09, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [c28744fe41](https://linux-hardware.org/?probe=c28744fe41) | Oct 08, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d2698f8b84](https://linux-hardware.org/?probe=d2698f8b84) | Oct 08, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [1423f1793b](https://linux-hardware.org/?probe=1423f1793b) | Oct 07, 2023 |
| Biostar       | B760MZ-E PRO                | Desktop     | [ba4b48ac1b](https://linux-hardware.org/?probe=ba4b48ac1b) | Oct 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [fc37084670](https://linux-hardware.org/?probe=fc37084670) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9948b7ed73](https://linux-hardware.org/?probe=9948b7ed73) | Oct 05, 2023 |
| Dell          | Latitude E6530              | Notebook    | [a426b30b67](https://linux-hardware.org/?probe=a426b30b67) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [3670f5ea70](https://linux-hardware.org/?probe=3670f5ea70) | Oct 02, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [b9b34bef50](https://linux-hardware.org/?probe=b9b34bef50) | Oct 02, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [8cb6a92a75](https://linux-hardware.org/?probe=8cb6a92a75) | Oct 01, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [bb5a34d03f](https://linux-hardware.org/?probe=bb5a34d03f) | Oct 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [951a03d2ad](https://linux-hardware.org/?probe=951a03d2ad) | Sep 30, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [7f47d1f656](https://linux-hardware.org/?probe=7f47d1f656) | Sep 30, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [a343a1c573](https://linux-hardware.org/?probe=a343a1c573) | Sep 30, 2023 |
| Getac         | T800G2                      | Tablet      | [ede8155598](https://linux-hardware.org/?probe=ede8155598) | Sep 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| Packard Be... | EasyNote TK36               | Notebook    | [1e8f79c726](https://linux-hardware.org/?probe=1e8f79c726) | Sep 29, 2023 |
| Alienware     | x14                         | Notebook    | [048d5f6f2a](https://linux-hardware.org/?probe=048d5f6f2a) | Sep 28, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [0f2958c5a1](https://linux-hardware.org/?probe=0f2958c5a1) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [64dcffc72f](https://linux-hardware.org/?probe=64dcffc72f) | Sep 26, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [0c17f26ed8](https://linux-hardware.org/?probe=0c17f26ed8) | Sep 25, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [7c0b883934](https://linux-hardware.org/?probe=7c0b883934) | Sep 24, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [450edd6547](https://linux-hardware.org/?probe=450edd6547) | Sep 24, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [c545236a4c](https://linux-hardware.org/?probe=c545236a4c) | Sep 22, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [0314ce541e](https://linux-hardware.org/?probe=0314ce541e) | Sep 22, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [6f6fbfc86f](https://linux-hardware.org/?probe=6f6fbfc86f) | Sep 20, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [ff02c716c1](https://linux-hardware.org/?probe=ff02c716c1) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [b21eddb040](https://linux-hardware.org/?probe=b21eddb040) | Sep 19, 2023 |
| HP            | 82A2                        | Desktop     | [cc179a17a8](https://linux-hardware.org/?probe=cc179a17a8) | Sep 18, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | Notebook    | [54aa39a845](https://linux-hardware.org/?probe=54aa39a845) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [3faff3c0aa](https://linux-hardware.org/?probe=3faff3c0aa) | Sep 18, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [502aab1a11](https://linux-hardware.org/?probe=502aab1a11) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [47e95a92cc](https://linux-hardware.org/?probe=47e95a92cc) | Sep 17, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ac1361d323](https://linux-hardware.org/?probe=ac1361d323) | Sep 17, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [5fe7196179](https://linux-hardware.org/?probe=5fe7196179) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [93356dbebb](https://linux-hardware.org/?probe=93356dbebb) | Sep 17, 2023 |
| HP            | 1905                        | Desktop     | [688c5ddf16](https://linux-hardware.org/?probe=688c5ddf16) | Sep 17, 2023 |
| HP            | 1905                        | Desktop     | [562179ca0e](https://linux-hardware.org/?probe=562179ca0e) | Sep 17, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [81a1d404e3](https://linux-hardware.org/?probe=81a1d404e3) | Sep 15, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [e1ac878fa3](https://linux-hardware.org/?probe=e1ac878fa3) | Sep 15, 2023 |
| Dell          | Latitude 5501               | Notebook    | [1608104990](https://linux-hardware.org/?probe=1608104990) | Sep 14, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7d22cd1af1](https://linux-hardware.org/?probe=7d22cd1af1) | Sep 11, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [c78162f5fd](https://linux-hardware.org/?probe=c78162f5fd) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [45261be082](https://linux-hardware.org/?probe=45261be082) | Sep 10, 2023 |
| HP            | 620                         | Notebook    | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [4dfd50fada](https://linux-hardware.org/?probe=4dfd50fada) | Sep 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b65fb1e357](https://linux-hardware.org/?probe=b65fb1e357) | Sep 09, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [7c51242294](https://linux-hardware.org/?probe=7c51242294) | Sep 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e48cab52a7](https://linux-hardware.org/?probe=e48cab52a7) | Sep 05, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7d3f9fa0e5](https://linux-hardware.org/?probe=7d3f9fa0e5) | Sep 04, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [0b3868c6bc](https://linux-hardware.org/?probe=0b3868c6bc) | Sep 04, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| HP            | 843B                        | Desktop     | [d0cef21578](https://linux-hardware.org/?probe=d0cef21578) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| Acer          | TravelMate 8372             | Notebook    | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b9765f73b1](https://linux-hardware.org/?probe=b9765f73b1) | Sep 02, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [d7fcde026e](https://linux-hardware.org/?probe=d7fcde026e) | Sep 02, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [e7a06bde4e](https://linux-hardware.org/?probe=e7a06bde4e) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [905ee212e5](https://linux-hardware.org/?probe=905ee212e5) | Sep 01, 2023 |
| Acer          | TravelMate 5760G            | Notebook    | [1a0a1749fc](https://linux-hardware.org/?probe=1a0a1749fc) | Sep 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [4cb96ee770](https://linux-hardware.org/?probe=4cb96ee770) | Sep 01, 2023 |
| Maxtang       | BYT30                       | Desktop     | [6f7fa1fde6](https://linux-hardware.org/?probe=6f7fa1fde6) | Aug 31, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6cd62bfac4](https://linux-hardware.org/?probe=6cd62bfac4) | Aug 31, 2023 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [189647b3df](https://linux-hardware.org/?probe=189647b3df) | Aug 31, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [abfe7c3f74](https://linux-hardware.org/?probe=abfe7c3f74) | Aug 30, 2023 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [193a50f761](https://linux-hardware.org/?probe=193a50f761) | Aug 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [92492caa13](https://linux-hardware.org/?probe=92492caa13) | Aug 29, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [4cb158cafc](https://linux-hardware.org/?probe=4cb158cafc) | Aug 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [844b4e4dc2](https://linux-hardware.org/?probe=844b4e4dc2) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [1afaed6ffa](https://linux-hardware.org/?probe=1afaed6ffa) | Aug 28, 2023 |
| HP            | 1905                        | Desktop     | [c1758c3a05](https://linux-hardware.org/?probe=c1758c3a05) | Aug 26, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [69824bbd6d](https://linux-hardware.org/?probe=69824bbd6d) | Aug 26, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [499c14b0f7](https://linux-hardware.org/?probe=499c14b0f7) | Aug 26, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [ac61c512ef](https://linux-hardware.org/?probe=ac61c512ef) | Aug 25, 2023 |
| Dell          | Studio 1735                 | Notebook    | [5932ab2004](https://linux-hardware.org/?probe=5932ab2004) | Aug 25, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [43686cdaa0](https://linux-hardware.org/?probe=43686cdaa0) | Aug 25, 2023 |
| Unknown       | HX90                        | Desktop     | [305cd9a7ed](https://linux-hardware.org/?probe=305cd9a7ed) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [d366a928cc](https://linux-hardware.org/?probe=d366a928cc) | Aug 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [5057058532](https://linux-hardware.org/?probe=5057058532) | Aug 23, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [659ac11761](https://linux-hardware.org/?probe=659ac11761) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [05c761f480](https://linux-hardware.org/?probe=05c761f480) | Aug 22, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [1824f3c712](https://linux-hardware.org/?probe=1824f3c712) | Aug 19, 2023 |
| Dell          | 0CT017                      | Desktop     | [3bb33d455c](https://linux-hardware.org/?probe=3bb33d455c) | Aug 18, 2023 |
| Dell          | 0200DY A00                  | Desktop     | [9b94c2313c](https://linux-hardware.org/?probe=9b94c2313c) | Aug 18, 2023 |
| Dell          | 0CT017                      | Desktop     | [5f628eeffa](https://linux-hardware.org/?probe=5f628eeffa) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| ASUSTek       | M3A76-CM                    | Desktop     | [031a6edf78](https://linux-hardware.org/?probe=031a6edf78) | Aug 16, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [927eacb30f](https://linux-hardware.org/?probe=927eacb30f) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [4c4e9222ce](https://linux-hardware.org/?probe=4c4e9222ce) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [166b18583b](https://linux-hardware.org/?probe=166b18583b) | Aug 15, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [488c1edd8d](https://linux-hardware.org/?probe=488c1edd8d) | Aug 13, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6e7a8f72dd](https://linux-hardware.org/?probe=6e7a8f72dd) | Aug 10, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [d45603bb4e](https://linux-hardware.org/?probe=d45603bb4e) | Aug 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [584974f252](https://linux-hardware.org/?probe=584974f252) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5a0ec66589](https://linux-hardware.org/?probe=5a0ec66589) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [db2732f0e8](https://linux-hardware.org/?probe=db2732f0e8) | Aug 04, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [38f7c8653b](https://linux-hardware.org/?probe=38f7c8653b) | Aug 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [deeafc23f9](https://linux-hardware.org/?probe=deeafc23f9) | Aug 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [9b314ec48b](https://linux-hardware.org/?probe=9b314ec48b) | Aug 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1fa056944b](https://linux-hardware.org/?probe=1fa056944b) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [c74f4bde19](https://linux-hardware.org/?probe=c74f4bde19) | Aug 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [6eb487950f](https://linux-hardware.org/?probe=6eb487950f) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1fe93c22b0](https://linux-hardware.org/?probe=1fe93c22b0) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [4e2e9f1f7f](https://linux-hardware.org/?probe=4e2e9f1f7f) | Jul 31, 2023 |
| Dell          | 0M863N A00                  | Desktop     | [3c403d83cc](https://linux-hardware.org/?probe=3c403d83cc) | Jul 30, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [42bf6e1e48](https://linux-hardware.org/?probe=42bf6e1e48) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | Notebook    | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| HP            | 530                         | Notebook    | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [edbd410baa](https://linux-hardware.org/?probe=edbd410baa) | Jul 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d54ad601d0](https://linux-hardware.org/?probe=d54ad601d0) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Unknown       | HX90                        | Desktop     | [ba2a06600a](https://linux-hardware.org/?probe=ba2a06600a) | Jul 25, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [64595670db](https://linux-hardware.org/?probe=64595670db) | Jul 25, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [73f6f39c67](https://linux-hardware.org/?probe=73f6f39c67) | Jul 25, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ab11ab8316](https://linux-hardware.org/?probe=ab11ab8316) | Jul 25, 2023 |
| Unknown       | HX90                        | Desktop     | [25aeb91b82](https://linux-hardware.org/?probe=25aeb91b82) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [77ee44a9fe](https://linux-hardware.org/?probe=77ee44a9fe) | Jul 23, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [dec408556d](https://linux-hardware.org/?probe=dec408556d) | Jul 21, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [59cf8541b4](https://linux-hardware.org/?probe=59cf8541b4) | Jul 20, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [ceda2054b7](https://linux-hardware.org/?probe=ceda2054b7) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [2986780209](https://linux-hardware.org/?probe=2986780209) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [97c2950df7](https://linux-hardware.org/?probe=97c2950df7) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [140d426127](https://linux-hardware.org/?probe=140d426127) | Jul 18, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [4d18b60338](https://linux-hardware.org/?probe=4d18b60338) | Jul 18, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e790be3f6e](https://linux-hardware.org/?probe=e790be3f6e) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [6d96bf0f5b](https://linux-hardware.org/?probe=6d96bf0f5b) | Jul 09, 2023 |
| HP            | 620                         | Notebook    | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [f32ffc678f](https://linux-hardware.org/?probe=f32ffc678f) | Jul 07, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [3ad05bcf55](https://linux-hardware.org/?probe=3ad05bcf55) | Jul 06, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Dell          | Precision 7520              | Notebook    | [1bffd04c84](https://linux-hardware.org/?probe=1bffd04c84) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| Dell          | Precision 5560              | Notebook    | [5f8f3c917f](https://linux-hardware.org/?probe=5f8f3c917f) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b4560fc1c1](https://linux-hardware.org/?probe=b4560fc1c1) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [6df0ae15e1](https://linux-hardware.org/?probe=6df0ae15e1) | Jul 01, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [d4a008aefb](https://linux-hardware.org/?probe=d4a008aefb) | Jun 30, 2023 |
| Dell          | Latitude 5440               | Notebook    | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| VALE          | Notebook Slim S132          | Notebook    | [3e381e10f7](https://linux-hardware.org/?probe=3e381e10f7) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [39f7adb927](https://linux-hardware.org/?probe=39f7adb927) | Jun 30, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [b8327a4d00](https://linux-hardware.org/?probe=b8327a4d00) | Jun 30, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1f5a11092b](https://linux-hardware.org/?probe=1f5a11092b) | Jun 28, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [88cdeeac94](https://linux-hardware.org/?probe=88cdeeac94) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| Acer          | Aspire F5-771G              | Notebook    | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [601d7611be](https://linux-hardware.org/?probe=601d7611be) | Jun 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [50c975ae08](https://linux-hardware.org/?probe=50c975ae08) | Jun 13, 2023 |
| Emdoor        | AG958                       | Notebook    | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Dell          | Latitude 5510               | Notebook    | [78bd1ae0e0](https://linux-hardware.org/?probe=78bd1ae0e0) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [fd8a08639d](https://linux-hardware.org/?probe=fd8a08639d) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5a4cf4d2e3](https://linux-hardware.org/?probe=5a4cf4d2e3) | May 23, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [a7794f4f9e](https://linux-hardware.org/?probe=a7794f4f9e) | May 21, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| HP            | Elite x2 1013 G3            | Tablet      | [0da06960ac](https://linux-hardware.org/?probe=0da06960ac) | May 19, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| HP            | 620                         | Notebook    | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | Desktop     | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| Emdoor        | AG958                       | Notebook    | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [0a23198016](https://linux-hardware.org/?probe=0a23198016) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| Medion        | E2292                       | Convertible | [116727a473](https://linux-hardware.org/?probe=116727a473) | May 11, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [5384ed47e6](https://linux-hardware.org/?probe=5384ed47e6) | May 10, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [c182a0679c](https://linux-hardware.org/?probe=c182a0679c) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [434f1425a4](https://linux-hardware.org/?probe=434f1425a4) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [9a4e4763d4](https://linux-hardware.org/?probe=9a4e4763d4) | May 09, 2023 |
| MSI           | Katana 17 B12UCXK           | Notebook    | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Dell          | Latitude 7390               | Notebook    | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [f41852fa6e](https://linux-hardware.org/?probe=f41852fa6e) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [7b5d49d859](https://linux-hardware.org/?probe=7b5d49d859) | May 07, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [370f9304b6](https://linux-hardware.org/?probe=370f9304b6) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [9d5ca00c7c](https://linux-hardware.org/?probe=9d5ca00c7c) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [6bea90b569](https://linux-hardware.org/?probe=6bea90b569) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [6353d110f5](https://linux-hardware.org/?probe=6353d110f5) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [db0ab14831](https://linux-hardware.org/?probe=db0ab14831) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [2e02937097](https://linux-hardware.org/?probe=2e02937097) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [051da44921](https://linux-hardware.org/?probe=051da44921) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [68c7b6891b](https://linux-hardware.org/?probe=68c7b6891b) | May 06, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c490e68d59](https://linux-hardware.org/?probe=c490e68d59) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [29636a9923](https://linux-hardware.org/?probe=29636a9923) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| Medion        | P6630                       | Notebook    | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Dell          | Latitude 5521               | Notebook    | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | Notebook    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f8aee85cd4](https://linux-hardware.org/?probe=f8aee85cd4) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d138bfdf52](https://linux-hardware.org/?probe=d138bfdf52) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f4d7a6ed92](https://linux-hardware.org/?probe=f4d7a6ed92) | Apr 28, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [15b900cf50](https://linux-hardware.org/?probe=15b900cf50) | Apr 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [d5b1ec921a](https://linux-hardware.org/?probe=d5b1ec921a) | Apr 27, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | Notebook    | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [d7e9027e6a](https://linux-hardware.org/?probe=d7e9027e6a) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| Dell          | Latitude E6330              | Notebook    | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | Notebook    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [841c2f241b](https://linux-hardware.org/?probe=841c2f241b) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [a6b3ac3ff2](https://linux-hardware.org/?probe=a6b3ac3ff2) | Apr 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [38aeb226af](https://linux-hardware.org/?probe=38aeb226af) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [7230f64c9b](https://linux-hardware.org/?probe=7230f64c9b) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [a7f312ea0a](https://linux-hardware.org/?probe=a7f312ea0a) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [f1afe43806](https://linux-hardware.org/?probe=f1afe43806) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6ac02f43f2](https://linux-hardware.org/?probe=6ac02f43f2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| HP            | 0A5Ch                       | Desktop     | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [43d0d0a55e](https://linux-hardware.org/?probe=43d0d0a55e) | Apr 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | Notebook    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| MSI           | B150M BAZOOKA               | Desktop     | [ce60e4a299](https://linux-hardware.org/?probe=ce60e4a299) | Apr 08, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [269e742eb7](https://linux-hardware.org/?probe=269e742eb7) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| HP            | 620                         | Notebook    | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| Medion        | BTDD-EAIO                   | All in one  | [2bbf3378ef](https://linux-hardware.org/?probe=2bbf3378ef) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [8eb8bb5119](https://linux-hardware.org/?probe=8eb8bb5119) | Apr 03, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Clevo         | P170HMx                     | Notebook    | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [0aefaba90e](https://linux-hardware.org/?probe=0aefaba90e) | Apr 03, 2023 |
| HP            | 8430 1000                   | All in one  | [380754e2f6](https://linux-hardware.org/?probe=380754e2f6) | Apr 02, 2023 |
| HP            | 3397                        | Desktop     | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| AZW           | Speed S                     | Notebook    | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [12319c9ee3](https://linux-hardware.org/?probe=12319c9ee3) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [98cd4ea3a6](https://linux-hardware.org/?probe=98cd4ea3a6) | Apr 01, 2023 |
| HP            | Pavilion g7                 | Notebook    | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | Notebook    | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Medion        | P8614                       | Notebook    | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeeac5db0f](https://linux-hardware.org/?probe=eeeac5db0f) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [311e49c553](https://linux-hardware.org/?probe=311e49c553) | Mar 23, 2023 |
| Alienware     | m17 R3                      | Notebook    | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7622701d31](https://linux-hardware.org/?probe=7622701d31) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [846f31de3e](https://linux-hardware.org/?probe=846f31de3e) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [2ef61db0a6](https://linux-hardware.org/?probe=2ef61db0a6) | Mar 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5a70cf923e](https://linux-hardware.org/?probe=5a70cf923e) | Mar 18, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [1825764856](https://linux-hardware.org/?probe=1825764856) | Mar 17, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [68b65fda4c](https://linux-hardware.org/?probe=68b65fda4c) | Mar 15, 2023 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [13a4e703dc](https://linux-hardware.org/?probe=13a4e703dc) | Mar 14, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cde6fff1ad](https://linux-hardware.org/?probe=cde6fff1ad) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [2c01c1fd0e](https://linux-hardware.org/?probe=2c01c1fd0e) | Mar 11, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [dfbb481b02](https://linux-hardware.org/?probe=dfbb481b02) | Mar 11, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a63cd6d4aa](https://linux-hardware.org/?probe=a63cd6d4aa) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [72eed5b458](https://linux-hardware.org/?probe=72eed5b458) | Mar 08, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [1563e26ae3](https://linux-hardware.org/?probe=1563e26ae3) | Mar 07, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [44b690055c](https://linux-hardware.org/?probe=44b690055c) | Mar 07, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d595ae284e](https://linux-hardware.org/?probe=d595ae284e) | Mar 07, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [c3e39b21f9](https://linux-hardware.org/?probe=c3e39b21f9) | Mar 05, 2023 |
| Acer          | Aspire 6530G                | Notebook    | [a4077c8432](https://linux-hardware.org/?probe=a4077c8432) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| Toshiba       | Satellite C855-112          | Notebook    | [8635f2eecd](https://linux-hardware.org/?probe=8635f2eecd) | Mar 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [d850dacb6a](https://linux-hardware.org/?probe=d850dacb6a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ac3640b913](https://linux-hardware.org/?probe=ac3640b913) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a877190b1c](https://linux-hardware.org/?probe=a877190b1c) | Mar 02, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [639a660b02](https://linux-hardware.org/?probe=639a660b02) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | F70SL                       | Notebook    | [5870cf8326](https://linux-hardware.org/?probe=5870cf8326) | Mar 01, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b1d7964fc7](https://linux-hardware.org/?probe=b1d7964fc7) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0710c7be6e](https://linux-hardware.org/?probe=0710c7be6e) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [4acd4aa811](https://linux-hardware.org/?probe=4acd4aa811) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [41330b2783](https://linux-hardware.org/?probe=41330b2783) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e257e205bf](https://linux-hardware.org/?probe=e257e205bf) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [950130a7b4](https://linux-hardware.org/?probe=950130a7b4) | Feb 23, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [c2117fed20](https://linux-hardware.org/?probe=c2117fed20) | Feb 22, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [abfe4c823a](https://linux-hardware.org/?probe=abfe4c823a) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [da5050e2f8](https://linux-hardware.org/?probe=da5050e2f8) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [9eca2efc88](https://linux-hardware.org/?probe=9eca2efc88) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [4a92de7e43](https://linux-hardware.org/?probe=4a92de7e43) | Feb 17, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [2a14385869](https://linux-hardware.org/?probe=2a14385869) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [9c458e5a66](https://linux-hardware.org/?probe=9c458e5a66) | Feb 11, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [99fd12250b](https://linux-hardware.org/?probe=99fd12250b) | Feb 10, 2023 |
| Teclast       | F15S                        | Notebook    | [951ded8432](https://linux-hardware.org/?probe=951ded8432) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [997020aeb0](https://linux-hardware.org/?probe=997020aeb0) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [c90f2404df](https://linux-hardware.org/?probe=c90f2404df) | Feb 08, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [ee53c6f627](https://linux-hardware.org/?probe=ee53c6f627) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [870ba1caa7](https://linux-hardware.org/?probe=870ba1caa7) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Medion        | P6624                       | Notebook    | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [62e1e79469](https://linux-hardware.org/?probe=62e1e79469) | Feb 03, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a630801a13](https://linux-hardware.org/?probe=a630801a13) | Feb 03, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [72bdb7165c](https://linux-hardware.org/?probe=72bdb7165c) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Google        | Pantheon                    | Notebook    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f6be582448](https://linux-hardware.org/?probe=f6be582448) | Jan 30, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [358b908129](https://linux-hardware.org/?probe=358b908129) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [f5311b2134](https://linux-hardware.org/?probe=f5311b2134) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [4afdd5b9fc](https://linux-hardware.org/?probe=4afdd5b9fc) | Jan 28, 2023 |
| Acer          | Peppy                       | Notebook    | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [77a6b88d58](https://linux-hardware.org/?probe=77a6b88d58) | Jan 27, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [218f278cab](https://linux-hardware.org/?probe=218f278cab) | Jan 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [85ad9c7e62](https://linux-hardware.org/?probe=85ad9c7e62) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [37c4aa5f03](https://linux-hardware.org/?probe=37c4aa5f03) | Jan 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [19bb445ee4](https://linux-hardware.org/?probe=19bb445ee4) | Jan 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [6228476153](https://linux-hardware.org/?probe=6228476153) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| HP            | 843B                        | Desktop     | [2af17234ba](https://linux-hardware.org/?probe=2af17234ba) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9476823c0b](https://linux-hardware.org/?probe=9476823c0b) | Jan 19, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | Notebook    | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f3b27e21a7](https://linux-hardware.org/?probe=f3b27e21a7) | Jan 16, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [c06c7eedaf](https://linux-hardware.org/?probe=c06c7eedaf) | Jan 16, 2023 |
| Medion        | MS-7501                     | Desktop     | [abd269d539](https://linux-hardware.org/?probe=abd269d539) | Jan 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9fe6c51640](https://linux-hardware.org/?probe=9fe6c51640) | Jan 15, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [406649acdf](https://linux-hardware.org/?probe=406649acdf) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [bbecf2579c](https://linux-hardware.org/?probe=bbecf2579c) | Jan 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60c16871ac](https://linux-hardware.org/?probe=60c16871ac) | Jan 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8193577e0b](https://linux-hardware.org/?probe=8193577e0b) | Jan 11, 2023 |
| HP            | Pavilion dv6000 (RY604EA... | Notebook    | [a8ec5eb86a](https://linux-hardware.org/?probe=a8ec5eb86a) | Jan 11, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Dell          | XPS L521X                   | Notebook    | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0f1543c21d](https://linux-hardware.org/?probe=0f1543c21d) | Jan 09, 2023 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [7cafa98138](https://linux-hardware.org/?probe=7cafa98138) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d1eaa576e7](https://linux-hardware.org/?probe=d1eaa576e7) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [4673ec60ea](https://linux-hardware.org/?probe=4673ec60ea) | Jan 07, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [cbd020e86f](https://linux-hardware.org/?probe=cbd020e86f) | Jan 07, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [bb893b2d93](https://linux-hardware.org/?probe=bb893b2d93) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [89eccb038f](https://linux-hardware.org/?probe=89eccb038f) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [458cb8c4de](https://linux-hardware.org/?probe=458cb8c4de) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a84d0d7b42](https://linux-hardware.org/?probe=a84d0d7b42) | Jan 06, 2023 |
| Medion        | S4214                       | Notebook    | [58131e715e](https://linux-hardware.org/?probe=58131e715e) | Jan 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f029a8cdb](https://linux-hardware.org/?probe=9f029a8cdb) | Jan 06, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [b1911d1ae5](https://linux-hardware.org/?probe=b1911d1ae5) | Jan 01, 2023 |
| Dell          | System XPS L702X            | Notebook    | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | Notebook    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Acer          | Aspire M3920                | Desktop     | [49cb4f51a8](https://linux-hardware.org/?probe=49cb4f51a8) | Dec 28, 2022 |
| Dell          | Latitude 5580               | Notebook    | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bf50da5153](https://linux-hardware.org/?probe=bf50da5153) | Dec 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| HP            | 0AACh                       | Desktop     | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Stream x360 Convertible ... | Convertible | [e01713ca07](https://linux-hardware.org/?probe=e01713ca07) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [355d32cbac](https://linux-hardware.org/?probe=355d32cbac) | Dec 24, 2022 |
| HP            | 0AACh                       | Desktop     | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | Notebook    | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [59d46f37db](https://linux-hardware.org/?probe=59d46f37db) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [60683b36c2](https://linux-hardware.org/?probe=60683b36c2) | Dec 20, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [d854f4c5ad](https://linux-hardware.org/?probe=d854f4c5ad) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [835cdeea5e](https://linux-hardware.org/?probe=835cdeea5e) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | Notebook    | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [3684f593d4](https://linux-hardware.org/?probe=3684f593d4) | Dec 18, 2022 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [15f724ada5](https://linux-hardware.org/?probe=15f724ada5) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | Notebook    | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | Notebook    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e008a86cd5](https://linux-hardware.org/?probe=e008a86cd5) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | Notebook    | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [d1b6c31805](https://linux-hardware.org/?probe=d1b6c31805) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | Notebook    | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7ba193202d](https://linux-hardware.org/?probe=7ba193202d) | Dec 08, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [5e5a1fd920](https://linux-hardware.org/?probe=5e5a1fd920) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [185bfcb7fa](https://linux-hardware.org/?probe=185bfcb7fa) | Dec 04, 2022 |
| HP            | Pavilion Laptop             | Notebook    | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | Notebook    | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [cccf492c06](https://linux-hardware.org/?probe=cccf492c06) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4c7e1d5bc4](https://linux-hardware.org/?probe=4c7e1d5bc4) | Dec 01, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [bb49870780](https://linux-hardware.org/?probe=bb49870780) | Nov 28, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | Notebook    | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [62e12083b5](https://linux-hardware.org/?probe=62e12083b5) | Nov 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [495d972ae3](https://linux-hardware.org/?probe=495d972ae3) | Nov 23, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [66383ce902](https://linux-hardware.org/?probe=66383ce902) | Nov 22, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [0354f9cb0e](https://linux-hardware.org/?probe=0354f9cb0e) | Nov 21, 2022 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c6b206401a](https://linux-hardware.org/?probe=c6b206401a) | Nov 21, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d7ee80553a](https://linux-hardware.org/?probe=d7ee80553a) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [f55a45b87f](https://linux-hardware.org/?probe=f55a45b87f) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e3d6c78ed4](https://linux-hardware.org/?probe=e3d6c78ed4) | Nov 20, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | Notebook    | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9876aa0fd](https://linux-hardware.org/?probe=c9876aa0fd) | Nov 16, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [f56f2c6a53](https://linux-hardware.org/?probe=f56f2c6a53) | Nov 14, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [eeaa5c82ea](https://linux-hardware.org/?probe=eeaa5c82ea) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [929685d936](https://linux-hardware.org/?probe=929685d936) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | Notebook    | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion 17                 | Notebook    | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [4e35f6b15e](https://linux-hardware.org/?probe=4e35f6b15e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [3e390c5fb3](https://linux-hardware.org/?probe=3e390c5fb3) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [0f4bdc1677](https://linux-hardware.org/?probe=0f4bdc1677) | Nov 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [ff19454b61](https://linux-hardware.org/?probe=ff19454b61) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e7254fb467](https://linux-hardware.org/?probe=e7254fb467) | Nov 04, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| Dell          | Latitude 5580               | Notebook    | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | Notebook    | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [95e2a1e7d9](https://linux-hardware.org/?probe=95e2a1e7d9) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [4eff9900f2](https://linux-hardware.org/?probe=4eff9900f2) | Oct 28, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [6cfd4bdb14](https://linux-hardware.org/?probe=6cfd4bdb14) | Oct 28, 2022 |
| PC Special... | Recoil II                   | Notebook    | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | Notebook    | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [76fa0d836f](https://linux-hardware.org/?probe=76fa0d836f) | Oct 25, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b0377a420](https://linux-hardware.org/?probe=8b0377a420) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [f82a2d8d8e](https://linux-hardware.org/?probe=f82a2d8d8e) | Oct 23, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [25295c680c](https://linux-hardware.org/?probe=25295c680c) | Oct 23, 2022 |
| ASUSTek       | P9X79 WS                    | Desktop     | [86f91e4898](https://linux-hardware.org/?probe=86f91e4898) | Oct 23, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | Notebook    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [aa8a459961](https://linux-hardware.org/?probe=aa8a459961) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9d471dbf37](https://linux-hardware.org/?probe=9d471dbf37) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [f6c1e8e061](https://linux-hardware.org/?probe=f6c1e8e061) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Shuttle       | FS81                        | Desktop     | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| ASUSTek       | GD30CI                      | Desktop     | [e002a9ef5c](https://linux-hardware.org/?probe=e002a9ef5c) | Oct 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [870d58dd75](https://linux-hardware.org/?probe=870d58dd75) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [73f8df6ec6](https://linux-hardware.org/?probe=73f8df6ec6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | Notebook    | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | Notebook    | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b26ceb2206](https://linux-hardware.org/?probe=b26ceb2206) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bc86477fff](https://linux-hardware.org/?probe=bc86477fff) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [b419239d57](https://linux-hardware.org/?probe=b419239d57) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | Notebook    | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [03dc83a686](https://linux-hardware.org/?probe=03dc83a686) | Oct 05, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Notebook      | W330SU2                     | Notebook    | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| Dell          | Latitude 5530               | Notebook    | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | Notebook    | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [d09f4c4501](https://linux-hardware.org/?probe=d09f4c4501) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [a978086f1b](https://linux-hardware.org/?probe=a978086f1b) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Lenovo        | B570e 476025G               | Notebook    | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [90871c217b](https://linux-hardware.org/?probe=90871c217b) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [b8e79c9c77](https://linux-hardware.org/?probe=b8e79c9c77) | Sep 16, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [2600793890](https://linux-hardware.org/?probe=2600793890) | Sep 15, 2022 |
| Medion        | MS-7857                     | Desktop     | [98a978898c](https://linux-hardware.org/?probe=98a978898c) | Sep 14, 2022 |
| Medion        | MS-7857                     | Desktop     | [54237e3276](https://linux-hardware.org/?probe=54237e3276) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [ddac4b0175](https://linux-hardware.org/?probe=ddac4b0175) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [864a5abac7](https://linux-hardware.org/?probe=864a5abac7) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [857e841fb7](https://linux-hardware.org/?probe=857e841fb7) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 302       | 13.64%  |
| Ubuntu 18.04                 | 141       | 6.37%   |
| Ubuntu 22.04                 | 131       | 5.92%   |
| Debian 11                    | 53        | 2.39%   |
| Zorin 16                     | 52        | 2.35%   |
| ArcoLinux Rolling            | 51        | 2.3%    |
| OpenMandriva 4.2             | 45        | 2.03%   |
| OpenMandriva 4.3             | 40        | 1.81%   |
| Fedora 36                    | 33        | 1.49%   |
| Arch Rolling                 | 33        | 1.49%   |
| Ubuntu 20.10                 | 31        | 1.4%    |
| Linux Mint 20.3              | 30        | 1.36%   |
| Linux Mint 20.1              | 29        | 1.31%   |
| Manjaro                      | 28        | 1.26%   |
| Fedora 38                    | 28        | 1.26%   |
| Ubuntu 19.10                 | 27        | 1.22%   |
| openSUSE Tumbleweed-XXXXXXXX | 27        | 1.22%   |
| Linux Mint 19.3              | 26        | 1.17%   |
| Fedora 35                    | 26        | 1.17%   |
| Arch                         | 26        | 1.17%   |
| Xubuntu 20.04                | 25        | 1.13%   |
| Pop!_OS 22.04                | 25        | 1.13%   |
| Linux Mint 20.2              | 24        | 1.08%   |
| Linux Mint 21                | 23        | 1.04%   |
| Fedora 34                    | 21        | 0.95%   |
| Debian 12                    | 21        | 0.95%   |
| Ubuntu 19.04                 | 20        | 0.9%    |
| Pop!_OS 20.04                | 20        | 0.9%    |
| Linux Mint 21.2              | 20        | 0.9%    |
| Linux Mint 20                | 19        | 0.86%   |
| Fedora 37                    | 19        | 0.86%   |
| OpenMandriva 23.03           | 18        | 0.81%   |
| OpenMandriva 23.01           | 18        | 0.81%   |
| Ubuntu 21.10                 | 17        | 0.77%   |
| Ubuntu 21.04                 | 17        | 0.77%   |
| OpenMandriva 23.08           | 17        | 0.77%   |
| Pop!_OS 21.04                | 16        | 0.72%   |
| KDE neon 20.04               | 16        | 0.72%   |
| Fedora 33                    | 16        | 0.72%   |
| EndeavourOS Rolling          | 16        | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 703       | 34.38%  |
| Linux Mint    | 195       | 9.54%   |
| OpenMandriva  | 147       | 7.19%   |
| Fedora        | 141       | 6.89%   |
| Debian        | 109       | 5.33%   |
| Pop!_OS       | 71        | 3.47%   |
| Zorin         | 64        | 3.13%   |
| Manjaro       | 64        | 3.13%   |
| Arch          | 57        | 2.79%   |
| Xubuntu       | 56        | 2.74%   |
| ArcoLinux     | 52        | 2.54%   |
| Kubuntu       | 43        | 2.1%    |
| openSUSE      | 37        | 1.81%   |
| ROSA          | 30        | 1.47%   |
| KDE neon      | 25        | 1.22%   |
| Elementary    | 21        | 1.03%   |
| Ubuntu Unity  | 18        | 0.88%   |
| Lubuntu       | 18        | 0.88%   |
| EndeavourOS   | 18        | 0.88%   |
| Ubuntu MATE   | 17        | 0.83%   |
| Gentoo        | 17        | 0.83%   |
| Kali          | 12        | 0.59%   |
| CentOS        | 12        | 0.59%   |
| Endless       | 11        | 0.54%   |
| LMDE          | 10        | 0.49%   |
| BlackPanther  | 8         | 0.39%   |
| SteamOS       | 7         | 0.34%   |
| MX            | 7         | 0.34%   |
| Garuda Linux  | 7         | 0.34%   |
| Clear Linux   | 7         | 0.34%   |
| Ubuntu Budgie | 6         | 0.29%   |
| Ubuntu Studio | 5         | 0.24%   |
| Nobara        | 5         | 0.24%   |
| NixOS         | 3         | 0.15%   |
| LinuxFX       | 3         | 0.15%   |
| Rocky Linux   | 2         | 0.1%    |
| Raspbian      | 2         | 0.1%    |
| Peppermint    | 2         | 0.1%    |
| Parrot        | 2         | 0.1%    |
| Kaisen        | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 44        | 1.73%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.49%   |
| 5.4.0-42-generic         | 29        | 1.14%   |
| 5.15.0-56-generic        | 23        | 0.9%    |
| 5.4.0-58-generic         | 22        | 0.87%   |
| 5.4.0-48-generic         | 21        | 0.83%   |
| 5.3.0-42-generic         | 20        | 0.79%   |
| 6.2.6-desktop-1omv2390   | 18        | 0.71%   |
| 5.15.0-46-generic        | 18        | 0.71%   |
| 5.15.0-58-generic        | 17        | 0.67%   |
| 5.15.0-52-generic        | 17        | 0.67%   |
| 6.1.1-desktop-1omv2290   | 15        | 0.59%   |
| 5.8.0-48-generic         | 15        | 0.59%   |
| 5.8.0-43-generic         | 15        | 0.59%   |
| 5.4.0-65-generic         | 15        | 0.59%   |
| 5.15.0-48-generic        | 15        | 0.59%   |
| 6.2.0-26-generic         | 14        | 0.55%   |
| 5.4.0-66-generic         | 14        | 0.55%   |
| 5.4.0-29-generic         | 14        | 0.55%   |
| 5.3.0-46-generic         | 14        | 0.55%   |
| 5.11.0-38-generic        | 14        | 0.55%   |
| 6.4.11-desktop-1omv2390  | 13        | 0.51%   |
| 5.4.0-74-generic         | 13        | 0.51%   |
| 5.4.0-52-generic         | 13        | 0.51%   |
| 5.4.0-40-generic         | 13        | 0.51%   |
| 5.4.0-37-generic         | 12        | 0.47%   |
| 5.4.0-26-generic         | 12        | 0.47%   |
| 5.19.0-35-generic        | 12        | 0.47%   |
| 5.15.0-53-generic        | 12        | 0.47%   |
| 5.15.0-47-generic        | 12        | 0.47%   |
| 5.15.0-41-generic        | 12        | 0.47%   |
| 5.13.0-28-generic        | 12        | 0.47%   |
| 5.10.0-21-amd64          | 12        | 0.47%   |
| 5.4.0-91-generic         | 11        | 0.43%   |
| 5.15.0-88-generic        | 11        | 0.43%   |
| 5.11.0-43-generic        | 11        | 0.43%   |
| 5.11.0-41-generic        | 11        | 0.43%   |
| 5.8.0-53-generic         | 10        | 0.39%   |
| 5.4.0-54-generic         | 10        | 0.39%   |
| 5.13.0-39-generic        | 10        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 354       | 14.93%  |
| 5.15.0  | 231       | 9.74%   |
| 5.8.0   | 118       | 4.98%   |
| 5.11.0  | 108       | 4.56%   |
| 4.15.0  | 107       | 4.51%   |
| 5.13.0  | 87        | 3.67%   |
| 5.3.0   | 83        | 3.5%    |
| 5.10.0  | 66        | 2.78%   |
| 5.19.0  | 64        | 2.7%    |
| 6.2.0   | 56        | 2.36%   |
| 5.0.0   | 51        | 2.15%   |
| 5.10.14 | 44        | 1.86%   |
| 5.16.7  | 38        | 1.6%    |
| 4.18.0  | 37        | 1.56%   |
| 6.1.0   | 27        | 1.14%   |
| 6.2.6   | 22        | 0.93%   |
| 4.19.0  | 16        | 0.67%   |
| 6.1.1   | 15        | 0.63%   |
| 6.5.0   | 14        | 0.59%   |
| 6.4.11  | 13        | 0.55%   |
| 6.0.0   | 10        | 0.42%   |
| 4.18.16 | 10        | 0.42%   |
| 6.0.12  | 9         | 0.38%   |
| 5.17.5  | 9         | 0.38%   |
| 4.9.20  | 9         | 0.38%   |
| 6.2.11  | 8         | 0.34%   |
| 5.14.10 | 8         | 0.34%   |
| 6.5.5   | 7         | 0.3%    |
| 6.1.12  | 7         | 0.3%    |
| 5.18.12 | 7         | 0.3%    |
| 5.17.0  | 7         | 0.3%    |
| 5.9.11  | 6         | 0.25%   |
| 5.8.5   | 6         | 0.25%   |
| 5.16.0  | 6         | 0.25%   |
| 5.14.0  | 6         | 0.25%   |
| 5.13.12 | 6         | 0.25%   |
| 4.9.60  | 6         | 0.25%   |
| 4.4.0   | 6         | 0.25%   |
| 3.10.0  | 6         | 0.25%   |
| 6.6.7   | 5         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 383       | 16.57%  |
| 5.15    | 286       | 12.38%  |
| 5.10    | 144       | 6.23%   |
| 5.8     | 140       | 6.06%   |
| 5.11    | 135       | 5.84%   |
| 6.2     | 112       | 4.85%   |
| 4.15    | 107       | 4.63%   |
| 5.13    | 106       | 4.59%   |
| 5.3     | 92        | 3.98%   |
| 5.19    | 88        | 3.81%   |
| 5.16    | 75        | 3.25%   |
| 6.1     | 66        | 2.86%   |
| 5.0     | 57        | 2.47%   |
| 6.5     | 52        | 2.25%   |
| 6.0     | 49        | 2.12%   |
| 4.18    | 48        | 2.08%   |
| 5.17    | 40        | 1.73%   |
| 6.4     | 37        | 1.6%    |
| 5.18    | 33        | 1.43%   |
| 5.14    | 30        | 1.3%    |
| 6.3     | 27        | 1.17%   |
| 5.9     | 26        | 1.13%   |
| 4.9     | 26        | 1.13%   |
| 5.12    | 24        | 1.04%   |
| 4.19    | 23        | 1%      |
| 5.6     | 22        | 0.95%   |
| 6.6     | 21        | 0.91%   |
| 5.5     | 13        | 0.56%   |
| 5.7     | 12        | 0.52%   |
| 4.4     | 6         | 0.26%   |
| 3.10    | 6         | 0.26%   |
| 4.13    | 5         | 0.22%   |
| 5.2     | 4         | 0.17%   |
| 5.1     | 4         | 0.17%   |
| 4.12    | 3         | 0.13%   |
| 5.15.96 | 2         | 0.09%   |
| 4.17    | 2         | 0.09%   |
| 4.1     | 2         | 0.09%   |
| 4.2     | 1         | 0.04%   |
| 4.10    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1881      | 97.01%  |
| i686    | 41        | 2.11%   |
| aarch64 | 14        | 0.72%   |
| armv7l  | 2         | 0.1%    |
| armv6l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 895       | 42.95%  |
| KDE5             | 331       | 15.88%  |
| Unknown          | 247       | 11.85%  |
| XFCE             | 169       | 8.11%   |
| X-Cinnamon       | 151       | 7.25%   |
| MATE             | 61        | 2.93%   |
| KDE              | 37        | 1.78%   |
| LXQt             | 30        | 1.44%   |
| Cinnamon         | 23        | 1.1%    |
| i3               | 21        | 1.01%   |
| Pantheon         | 20        | 0.96%   |
| Unity            | 18        | 0.86%   |
| KDE4             | 14        | 0.67%   |
| Budgie           | 12        | 0.58%   |
| Hyprland         | 7         | 0.34%   |
| sway             | 6         | 0.29%   |
| LXDE             | 5         | 0.24%   |
| GNOME Flashback  | 5         | 0.24%   |
| Deepin           | 5         | 0.24%   |
| LeftWM           | 4         | 0.19%   |
| lightdm-xsession | 3         | 0.14%   |
| bspwm            | 3         | 0.14%   |
| awesome          | 3         | 0.14%   |
| Trinity          | 2         | 0.1%    |
| qtile            | 2         | 0.1%    |
| Openbox          | 2         | 0.1%    |
| icewm            | 2         | 0.1%    |
| chadwm           | 2         | 0.1%    |
| xmonad           | 1         | 0.05%   |
| spectrwm         | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1499      | 74.13%  |
| Wayland | 349       | 17.26%  |
| Unknown | 141       | 6.97%   |
| Tty     | 33        | 1.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 939       | 45.72%  |
| SDDM    | 328       | 15.97%  |
| GDM     | 257       | 12.51%  |
| GDM3    | 252       | 12.27%  |
| LightDM | 192       | 9.35%   |
| TDM     | 68        | 3.31%   |
| KDM     | 13        | 0.63%   |
| XDM     | 4         | 0.19%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 667       | 33.04%  |
| fr_BE      | 365       | 18.08%  |
| nl_BE      | 326       | 16.15%  |
| Unknown    | 226       | 11.19%  |
| fr_FR      | 108       | 5.35%   |
| en_GB      | 102       | 5.05%   |
| nl_NL      | 92        | 4.56%   |
| C          | 34        | 1.68%   |
| de_DE      | 15        | 0.74%   |
| de_BE      | 11        | 0.54%   |
| pl_PL      | 10        | 0.5%    |
| en_IE      | 10        | 0.5%    |
| ru_RU      | 6         | 0.3%    |
| es_ES      | 5         | 0.25%   |
| it_IT      | 4         | 0.2%    |
| ro_RO      | 3         | 0.15%   |
| pt_PT      | 3         | 0.15%   |
| POSIX      | 3         | 0.15%   |
| C.UTF8     | 3         | 0.15%   |
| fr_LU      | 2         | 0.1%    |
| en_US.UTF8 | 2         | 0.1%    |
| en_CA      | 2         | 0.1%    |
| en_BE      | 2         | 0.1%    |
| tt_RU      | 1         | 0.05%   |
| tr_TR      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| pl_PL.UTF8 | 1         | 0.05%   |
| nl_BE.UTF8 | 1         | 0.05%   |
| nl_AW      | 1         | 0.05%   |
| li_BE      | 1         | 0.05%   |
| ku_TR      | 1         | 0.05%   |
| it_CH      | 1         | 0.05%   |
| hu_HU      | 1         | 0.05%   |
| fr_FR.UTF8 | 1         | 0.05%   |
| fr_CH      | 1         | 0.05%   |
| en_ZA      | 1         | 0.05%   |
| en_NZ      | 1         | 0.05%   |
| en_IN      | 1         | 0.05%   |
| en_DK      | 1         | 0.05%   |
| en_BW      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1028      | 51.61%  |
| BIOS | 964       | 48.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1498      | 74.27%  |
| Btrfs    | 207       | 10.26%  |
| Overlay  | 150       | 7.44%   |
| Unknown  | 64        | 3.17%   |
| Tmpfs    | 48        | 2.38%   |
| Xfs      | 29        | 1.44%   |
| Zfs      | 10        | 0.5%    |
| Ext2     | 8         | 0.4%    |
| Reiserfs | 1         | 0.05%   |
| F2fs     | 1         | 0.05%   |
| Ext3     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 981       | 49.03%  |
| GPT     | 805       | 40.23%  |
| MBR     | 215       | 10.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1636      | 82.21%  |
| Yes       | 354       | 17.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1384      | 70.04%  |
| Yes       | 592       | 29.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 314       | 16.21%  |
| Hewlett-Packard         | 298       | 15.38%  |
| Lenovo                  | 254       | 13.11%  |
| Dell                    | 250       | 12.91%  |
| MSI                     | 134       | 6.92%   |
| Acer                    | 111       | 5.73%   |
| Gigabyte Technology     | 106       | 5.47%   |
| Medion                  | 62        | 3.2%    |
| ASRock                  | 54        | 2.79%   |
| Apple                   | 48        | 2.48%   |
| Intel                   | 34        | 1.76%   |
| Toshiba                 | 33        | 1.7%    |
| Sony                    | 26        | 1.34%   |
| Packard Bell            | 24        | 1.24%   |
| Notebook                | 22        | 1.14%   |
| Unknown                 | 16        | 0.83%   |
| Fujitsu                 | 14        | 0.72%   |
| Raspberry Pi Foundation | 12        | 0.62%   |
| TUXEDO                  | 10        | 0.52%   |
| Valve                   | 8         | 0.41%   |
| Samsung Electronics     | 8         | 0.41%   |
| Fujitsu Siemens         | 6         | 0.31%   |
| Foxconn                 | 6         | 0.31%   |
| Supermicro              | 5         | 0.26%   |
| AZW                     | 5         | 0.26%   |
| AMI                     | 5         | 0.26%   |
| Alienware               | 5         | 0.26%   |
| PC Specialist           | 4         | 0.21%   |
| Microsoft               | 4         | 0.21%   |
| Pegatron                | 3         | 0.15%   |
| HUAWEI                  | 3         | 0.15%   |
| Google                  | 3         | 0.15%   |
| Clevo                   | 3         | 0.15%   |
| BESSTAR Tech            | 3         | 0.15%   |
| Teclast                 | 2         | 0.1%    |
| Shuttle                 | 2         | 0.1%    |
| Razer                   | 2         | 0.1%    |
| Panasonic               | 2         | 0.1%    |
| Nvidia                  | 2         | 0.1%    |
| YJKC                    | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 26        | 1.34%   |
| Unknown                          | 20        | 1.03%   |
| Valve Jupiter                    | 8         | 0.41%   |
| HP Pavilion g7                   | 7         | 0.36%   |
| ASRock B450M Pro4                | 7         | 0.36%   |
| HP ProBook 650 G1                | 6         | 0.31%   |
| HP Pavilion Notebook             | 6         | 0.31%   |
| HP EliteBook 850 G8 Notebook PC  | 6         | 0.31%   |
| MSI MS-7C37                      | 5         | 0.26%   |
| MSI MS-7B86                      | 5         | 0.26%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.26%   |
| HP ProBook 6570b                 | 5         | 0.26%   |
| HP Pavilion dv7                  | 5         | 0.26%   |
| HP Pavilion dv6                  | 5         | 0.26%   |
| Dell XPS 15 9560                 | 5         | 0.26%   |
| Dell XPS 13 7390                 | 5         | 0.26%   |
| Dell OptiPlex 780                | 5         | 0.26%   |
| Dell Latitude 5530               | 5         | 0.26%   |
| Toshiba Satellite C660           | 4         | 0.21%   |
| RPi Raspberry Pi                 | 4         | 0.21%   |
| MSI MS-7C91                      | 4         | 0.21%   |
| MSI MS-7A38                      | 4         | 0.21%   |
| HP Pavilion Laptop 15-eh1xxx     | 4         | 0.21%   |
| HP Pavilion Laptop 15-cw0xxx     | 4         | 0.21%   |
| HP Pavilion 17                   | 4         | 0.21%   |
| HP Laptop 15-db0xxx              | 4         | 0.21%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.21%   |
| Gigabyte X570 AORUS MASTER       | 4         | 0.21%   |
| Gigabyte Spring Peak             | 4         | 0.21%   |
| Gigabyte GB-BRR7H-4800           | 4         | 0.21%   |
| Gigabyte B550I AORUS PRO AX      | 4         | 0.21%   |
| Dell XPS 15 9570                 | 4         | 0.21%   |
| Dell XPS 13 9370                 | 4         | 0.21%   |
| Dell OptiPlex 3010               | 4         | 0.21%   |
| Dell Latitude 5520               | 4         | 0.21%   |
| ASUS UNLOCK INSTALL              | 4         | 0.21%   |
| ASUS ROG STRIX X570-E GAMING     | 4         | 0.21%   |
| ASUS PRIME X570-PRO              | 4         | 0.21%   |
| MSI MS-7A34                      | 3         | 0.15%   |
| MSI MS-7850                      | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 130       | 6.71%   |
| Dell Latitude         | 90        | 4.65%   |
| Acer Aspire           | 84        | 4.34%   |
| HP EliteBook          | 63        | 3.25%   |
| HP Pavilion           | 62        | 3.2%    |
| HP ProBook            | 44        | 2.27%   |
| Dell XPS              | 42        | 2.17%   |
| Lenovo IdeaPad        | 38        | 1.96%   |
| ASUS PRIME            | 38        | 1.96%   |
| HP Compaq             | 36        | 1.86%   |
| Dell OptiPlex         | 36        | 1.86%   |
| ASUS ROG              | 36        | 1.86%   |
| Toshiba Satellite     | 29        | 1.5%    |
| Dell Precision        | 28        | 1.45%   |
| Dell Inspiron         | 26        | 1.34%   |
| ASUS All              | 26        | 1.34%   |
| HP Laptop             | 20        | 1.03%   |
| ASUS TUF              | 20        | 1.03%   |
| Unknown               | 20        | 1.03%   |
| Lenovo Yoga           | 18        | 0.93%   |
| Lenovo Legion         | 16        | 0.83%   |
| Packard Bell EasyNote | 14        | 0.72%   |
| Medion Akoya          | 14        | 0.72%   |
| ASUS VivoBook         | 13        | 0.67%   |
| RPi Raspberry         | 12        | 0.62%   |
| Lenovo ThinkCentre    | 12        | 0.62%   |
| HP ZBook              | 12        | 0.62%   |
| Dell Vostro           | 11        | 0.57%   |
| HP ENVY               | 10        | 0.52%   |
| Gigabyte X570         | 9         | 0.46%   |
| Valve Jupiter         | 8         | 0.41%   |
| Acer Nitro            | 8         | 0.41%   |
| Lenovo IdeaCentre     | 7         | 0.36%   |
| HP ProDesk            | 7         | 0.36%   |
| Fujitsu ESPRIMO       | 7         | 0.36%   |
| ASRock B450M          | 7         | 0.36%   |
| Lenovo ThinkBook      | 6         | 0.31%   |
| Gigabyte B550         | 6         | 0.31%   |
| Dell Studio           | 6         | 0.31%   |
| MSI MS-7C37           | 5         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 186       | 9.6%    |
| 2020    | 183       | 9.45%   |
| 2019    | 168       | 8.67%   |
| 2012    | 148       | 7.64%   |
| 2013    | 140       | 7.23%   |
| 2011    | 133       | 6.87%   |
| 2017    | 117       | 6.04%   |
| 2014    | 115       | 5.94%   |
| 2021    | 112       | 5.78%   |
| 2016    | 93        | 4.8%    |
| 2015    | 93        | 4.8%    |
| 2010    | 87        | 4.49%   |
| 2008    | 84        | 4.34%   |
| 2009    | 76        | 3.92%   |
| 2022    | 73        | 3.77%   |
| 2007    | 56        | 2.89%   |
| 2006    | 26        | 1.34%   |
| 2023    | 22        | 1.14%   |
| Unknown | 19        | 0.98%   |
| 2005    | 4         | 0.21%   |
| 2004    | 2         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1084      | 55.96%  |
| Desktop        | 704       | 36.34%  |
| Convertible    | 56        | 2.89%   |
| Mini pc        | 27        | 1.39%   |
| All in one     | 23        | 1.19%   |
| System on chip | 17        | 0.88%   |
| Tablet         | 13        | 0.67%   |
| Server         | 13        | 0.67%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1787      | 91.08%  |
| Enabled  | 175       | 8.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1933      | 99.79%  |
| Yes  | 4         | 0.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 432       | 21.74%  |
| 16.01-24.0      | 432       | 21.74%  |
| 8.01-16.0       | 361       | 18.17%  |
| 3.01-4.0        | 332       | 16.71%  |
| 32.01-64.0      | 216       | 10.87%  |
| 64.01-256.0     | 62        | 3.12%   |
| 1.01-2.0        | 62        | 3.12%   |
| 24.01-32.0      | 40        | 2.01%   |
| 2.01-3.0        | 26        | 1.31%   |
| 0.51-1.0        | 17        | 0.86%   |
| More than 256.0 | 4         | 0.2%    |
| 0.01-0.5        | 3         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 725       | 32.7%   |
| 2.01-3.0    | 560       | 25.26%  |
| 4.01-8.0    | 333       | 15.02%  |
| 3.01-4.0    | 296       | 13.35%  |
| 0.51-1.0    | 139       | 6.27%   |
| 8.01-16.0   | 110       | 4.96%   |
| 0.01-0.5    | 34        | 1.53%   |
| 16.01-24.0  | 11        | 0.5%    |
| 24.01-32.0  | 7         | 0.32%   |
| 64.01-256.0 | 1         | 0.05%   |
| Unknown     | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1146      | 56.85%  |
| 2       | 508       | 25.2%   |
| 3       | 161       | 7.99%   |
| 4       | 96        | 4.76%   |
| 5       | 46        | 2.28%   |
| 6       | 24        | 1.19%   |
| 0       | 18        | 0.89%   |
| 8       | 5         | 0.25%   |
| 9       | 4         | 0.2%    |
| 7       | 4         | 0.2%    |
| 16      | 1         | 0.05%   |
| 11      | 1         | 0.05%   |
| 10      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1122      | 57.39%  |
| Yes       | 833       | 42.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1735      | 89.11%  |
| No        | 212       | 10.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1475      | 75.68%  |
| No        | 474       | 24.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1168      | 59.32%  |
| No        | 801       | 40.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belgium | 1937      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Brussels       | 282       | 13.07%  |
| Antwerp        | 132       | 6.12%   |
| Ghent          | 85        | 3.94%   |
| Liège         | 66        | 3.06%   |
| Ixelles-Elsene | 45        | 2.09%   |
| Mechelen       | 33        | 1.53%   |
| Leuven         | 30        | 1.39%   |
| Bruges         | 23        | 1.07%   |
| Turnhout       | 22        | 1.02%   |
| Hasselt        | 20        | 0.93%   |
| Schaarbeek     | 18        | 0.83%   |
| Anderlecht     | 18        | 0.83%   |
| Namur          | 17        | 0.79%   |
| Mons           | 17        | 0.79%   |
| Uccle          | 16        | 0.74%   |
| Aalst          | 16        | 0.74%   |
| Mortsel        | 14        | 0.65%   |
| La Louvière   | 14        | 0.65%   |
| Lier           | 13        | 0.6%    |
| Etterbeek      | 13        | 0.6%    |
| Wilrijk        | 12        | 0.56%   |
| Sint-Niklaas   | 12        | 0.56%   |
| Jette          | 12        | 0.56%   |
| Charleroi      | 12        | 0.56%   |
| Seraing        | 11        | 0.51%   |
| Roeselare      | 11        | 0.51%   |
| Kontich        | 11        | 0.51%   |
| Gavere         | 11        | 0.51%   |
| Duffel         | 11        | 0.51%   |
| Deurne         | 11        | 0.51%   |
| Boom           | 11        | 0.51%   |
| Waregem        | 10        | 0.46%   |
| Tournai        | 10        | 0.46%   |
| Sint-Truiden   | 10        | 0.46%   |
| Kanne          | 10        | 0.46%   |
| Heusden-Zolder | 10        | 0.46%   |
| Edegem         | 10        | 0.46%   |
| Bilzen         | 10        | 0.46%   |
| Vilvoorde      | 9         | 0.42%   |
| Langdorp       | 9         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 598       | 1098   | 20.84%  |
| WDC                         | 418       | 717    | 14.56%  |
| Seagate                     | 406       | 696    | 14.15%  |
| Toshiba                     | 182       | 247    | 6.34%   |
| Kingston                    | 153       | 237    | 5.33%   |
| Sandisk                     | 132       | 174    | 4.6%    |
| Crucial                     | 109       | 155    | 3.8%    |
| Unknown                     | 107       | 146    | 3.73%   |
| Hitachi                     | 87        | 118    | 3.03%   |
| SK hynix                    | 86        | 108    | 3%      |
| Intel                       | 82        | 100    | 2.86%   |
| Micron Technology           | 55        | 63     | 1.92%   |
| HGST                        | 48        | 69     | 1.67%   |
| Apple                       | 25        | 32     | 0.87%   |
| LITEON                      | 21        | 28     | 0.73%   |
| KIOXIA                      | 21        | 23     | 0.73%   |
| Phison                      | 19        | 22     | 0.66%   |
| Micron/Crucial Technology   | 19        | 29     | 0.66%   |
| China                       | 19        | 23     | 0.66%   |
| Intenso                     | 18        | 27     | 0.63%   |
| Maxtor                      | 16        | 20     | 0.56%   |
| Corsair                     | 16        | 17     | 0.56%   |
| A-DATA Technology           | 15        | 20     | 0.52%   |
| Fujitsu                     | 14        | 20     | 0.49%   |
| OCZ                         | 13        | 16     | 0.45%   |
| Phison Electronics          | 12        | 14     | 0.42%   |
| PNY                         | 11        | 12     | 0.38%   |
| Kingston Technology Company | 10        | 10     | 0.35%   |
| Silicon Motion              | 9         | 15     | 0.31%   |
| LaCie                       | 9         | 12     | 0.31%   |
| Transcend                   | 8         | 13     | 0.28%   |
| LITEONIT                    | 8         | 11     | 0.28%   |
| GOODRAM                     | 7         | 11     | 0.24%   |
| ASMT                        | 7         | 7      | 0.24%   |
| LDLC                        | 6         | 7      | 0.21%   |
| KingSpec                    | 5         | 5      | 0.17%   |
| Union Memory                | 4         | 8      | 0.14%   |
| SSSTC                       | 4         | 4      | 0.14%   |
| KingFast                    | 4         | 4      | 0.14%   |
| JMicron Technology          | 4         | 6      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 38        | 1.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 32        | 0.98%   |
| Samsung SSD 850 EVO 250GB                           | 29        | 0.89%   |
| Samsung NVMe SSD Drive 1TB                          | 28        | 0.86%   |
| Samsung SSD 850 EVO 500GB                           | 26        | 0.8%    |
| Samsung SSD 860 EVO 250GB                           | 23        | 0.7%    |
| Samsung NVMe SSD Drive 512GB                        | 23        | 0.7%    |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB                      | 22        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 22        | 0.67%   |
| Samsung SSD 860 EVO 1TB                             | 21        | 0.64%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.61%   |
| Toshiba DT01ACA100 1TB                              | 18        | 0.55%   |
| Samsung SSD 870 EVO 1TB                             | 17        | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB                      | 16        | 0.49%   |
| Samsung SSD 870 QVO 1TB                             | 16        | 0.49%   |
| Samsung SSD 840 EVO 250GB                           | 16        | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 15        | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                     | 15        | 0.46%   |
| Seagate Expansion 1TB                               | 15        | 0.46%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.46%   |
| Kingston SA400S37240G 240GB SSD                     | 15        | 0.46%   |
| Intel NVMe SSD Drive 512GB                          | 15        | 0.46%   |
| Unknown MMC Card  32GB                              | 14        | 0.43%   |
| HGST HTS721010A9E630 1TB                            | 14        | 0.43%   |
| Unknown MMC Card  64GB                              | 13        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.4%    |
| Seagate ST9500325AS 500GB                           | 13        | 0.4%    |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB                      | 13        | 0.4%    |
| Crucial CT500MX500SSD1 500GB                        | 13        | 0.4%    |
| Unknown MMC Card  128GB                             | 12        | 0.37%   |
| Seagate ST1000DM010-2EP102 1TB                      | 12        | 0.37%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.37%   |
| Crucial CT480BX500SSD1 480GB                        | 12        | 0.37%   |
| Unknown SD/MMC/MS PRO 128GB                         | 11        | 0.34%   |
| Seagate ST3500418AS 500GB                           | 11        | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB                        | 11        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 394       | 676    | 35.4%   |
| WDC                 | 347       | 606    | 31.18%  |
| Toshiba             | 132       | 174    | 11.86%  |
| Hitachi             | 87        | 118    | 7.82%   |
| HGST                | 48        | 69     | 4.31%   |
| Samsung Electronics | 40        | 65     | 3.59%   |
| Maxtor              | 16        | 20     | 1.44%   |
| Fujitsu             | 14        | 19     | 1.26%   |
| Unknown             | 11        | 21     | 0.99%   |
| Apple               | 7         | 7      | 0.63%   |
| LaCie               | 2         | 2      | 0.18%   |
| Intenso             | 2         | 5      | 0.18%   |
| Hewlett-Packard     | 2         | 4      | 0.18%   |
| XrayDisk            | 1         | 1      | 0.09%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| SINTECHI            | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| Lenovo              | 1         | 2      | 0.09%   |
| KESU                | 1         | 3      | 0.09%   |
| IET                 | 1         | 3      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| Dell                | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 337       | 597    | 35.32%  |
| Kingston            | 121       | 189    | 12.68%  |
| Crucial             | 93        | 134    | 9.75%   |
| SanDisk             | 72        | 97     | 7.55%   |
| WDC                 | 49        | 60     | 5.14%   |
| Intel               | 27        | 31     | 2.83%   |
| SK hynix            | 23        | 35     | 2.41%   |
| Toshiba             | 22        | 28     | 2.31%   |
| Micron Technology   | 21        | 25     | 2.2%    |
| China               | 19        | 23     | 1.99%   |
| LITEON              | 18        | 25     | 1.89%   |
| Intenso             | 15        | 20     | 1.57%   |
| OCZ                 | 13        | 16     | 1.36%   |
| Apple               | 12        | 17     | 1.26%   |
| PNY                 | 9         | 10     | 0.94%   |
| Corsair             | 9         | 10     | 0.94%   |
| LITEONIT            | 8         | 11     | 0.84%   |
| A-DATA Technology   | 8         | 12     | 0.84%   |
| Transcend           | 7         | 12     | 0.73%   |
| GOODRAM             | 7         | 11     | 0.73%   |
| ASMT                | 7         | 7      | 0.73%   |
| KingSpec            | 4         | 4      | 0.42%   |
| SPCC                | 3         | 4      | 0.31%   |
| Phison              | 3         | 3      | 0.31%   |
| FORESEE             | 3         | 3      | 0.31%   |
| Emtec               | 3         | 3      | 0.31%   |
| Zheino              | 2         | 2      | 0.21%   |
| Verbatim            | 2         | 2      | 0.21%   |
| Seagate             | 2         | 2      | 0.21%   |
| Reeinno             | 2         | 4      | 0.21%   |
| Plextor             | 2         | 2      | 0.21%   |
| Patriot             | 2         | 3      | 0.21%   |
| KingFast            | 2         | 2      | 0.21%   |
| JMicron Technology  | 2         | 3      | 0.21%   |
| Unknown             | 2         | 2      | 0.21%   |
| WDC WDS             | 1         | 1      | 0.1%    |
| Vaseky              | 1         | 1      | 0.1%    |
| tigo                | 1         | 1      | 0.1%    |
| Teclast             | 1         | 1      | 0.1%    |
| OWC                 | 1         | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 932       | 1802   | 36.03%  |
| SSD     | 838       | 1436   | 32.39%  |
| NVMe    | 691       | 1057   | 26.71%  |
| MMC     | 86        | 103    | 3.32%   |
| Unknown | 40        | 62     | 1.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1403      | 3063   | 60.81%  |
| NVMe | 690       | 1055   | 29.91%  |
| SAS  | 128       | 239    | 5.55%   |
| MMC  | 86        | 103    | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1079      | 1809   | 56.7%   |
| 0.51-1.0   | 517       | 880    | 27.17%  |
| 1.01-2.0   | 166       | 288    | 8.72%   |
| 3.01-4.0   | 69        | 126    | 3.63%   |
| 4.01-10.0  | 37        | 64     | 1.94%   |
| 2.01-3.0   | 30        | 48     | 1.58%   |
| 10.01-20.0 | 5         | 23     | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 544       | 25.75%  |
| 251-500        | 471       | 22.29%  |
| 501-1000       | 298       | 14.1%   |
| 1001-2000      | 189       | 8.94%   |
| More than 3000 | 138       | 6.53%   |
| 1-20           | 128       | 6.06%   |
| 51-100         | 124       | 5.87%   |
| Unknown        | 79        | 3.74%   |
| 2001-3000      | 78        | 3.69%   |
| 21-50          | 64        | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 782       | 35.48%  |
| 21-50          | 331       | 15.02%  |
| 101-250        | 299       | 13.57%  |
| 51-100         | 219       | 9.94%   |
| 251-500        | 179       | 8.12%   |
| 501-1000       | 138       | 6.26%   |
| 1001-2000      | 95        | 4.31%   |
| Unknown        | 79        | 3.58%   |
| 2001-3000      | 42        | 1.91%   |
| More than 3000 | 40        | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 6         | 26     | 3.31%   |
| Seagate ST9500325AS 500GB                      | 4         | 4      | 2.21%   |
| Seagate ST3500418AS 500GB                      | 4         | 11     | 2.21%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 2         | 2      | 1.1%    |
| Toshiba MQ01ABD075 752GB                       | 2         | 2      | 1.1%    |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 1.1%    |
| Seagate ST4000DM000-1F2168 4TB                 | 2         | 4      | 1.1%    |
| Seagate ST320LT007-9ZV142 320GB                | 2         | 8      | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 7      | 1.1%    |
| Samsung Electronics SSD 970 EVO 1TB            | 2         | 4      | 1.1%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.1%    |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 1.1%    |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 1.1%    |
| Hitachi HTS545050A7E380 500GB                  | 2         | 4      | 1.1%    |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 1.1%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                 | 1         | 1      | 0.55%   |
| WDC WD6400AAKS-00A7B0 640GB                    | 1         | 1      | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.55%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 1         | 1      | 0.55%   |
| WDC WD5000AAKX-753CA1 500GB                    | 1         | 1      | 0.55%   |
| WDC WD5000AAKX-07U6AA0 500GB                   | 1         | 1      | 0.55%   |
| WDC WD5000AAKS-22A7B0 500GB                    | 1         | 1      | 0.55%   |
| WDC WD5000AADS-00S9B0 500GB                    | 1         | 1      | 0.55%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 1      | 0.55%   |
| WDC WD3200BPVT-55JJ5T0 320GB                   | 1         | 1      | 0.55%   |
| WDC WD3200BPVT-22ZEST0 320GB                   | 1         | 1      | 0.55%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 1         | 1      | 0.55%   |
| WDC WD3200BEKT-75PVMT1 320GB                   | 1         | 6      | 0.55%   |
| WDC WD3200BEKT-60PVMT0 320GB                   | 1         | 1      | 0.55%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.55%   |
| WDC WD1600JS-60MHB5 160GB                      | 1         | 1      | 0.55%   |
| WDC WD10SPCX-60HWST0 1TB                       | 1         | 1      | 0.55%   |
| WDC WD10EZRX-00L4HB0 1TB                       | 1         | 1      | 0.55%   |
| WDC WD10EZRX-00A8LB0 1TB                       | 1         | 1      | 0.55%   |
| WDC WD10EARS-22Y5B1 1TB                        | 1         | 1      | 0.55%   |
| WDC WD10EARS-00Y5B1 1TB                        | 1         | 2      | 0.55%   |
| WDC WD10EALX-009BA0 1TB                        | 1         | 1      | 0.55%   |
| WDC WD10EALS-00Z8A0 1TB                        | 1         | 1      | 0.55%   |
| WDC WD10EADS-65M2B0 1TB                        | 1         | 1      | 0.55%   |
| WDC WD10EADS-00P8B0 1TB                        | 1         | 1      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 97     | 27.49%  |
| WDC                 | 26        | 36     | 15.2%   |
| Samsung Electronics | 15        | 20     | 8.77%   |
| Hitachi             | 15        | 18     | 8.77%   |
| Toshiba             | 13        | 13     | 7.6%    |
| Intel               | 8         | 9      | 4.68%   |
| Crucial             | 7         | 8      | 4.09%   |
| SK hynix            | 6         | 10     | 3.51%   |
| HGST                | 6         | 6      | 3.51%   |
| SanDisk             | 5         | 5      | 2.92%   |
| Kingston            | 5         | 10     | 2.92%   |
| Micron Technology   | 4         | 4      | 2.34%   |
| Maxtor              | 4         | 5      | 2.34%   |
| Fujitsu             | 4         | 8      | 2.34%   |
| A-DATA Technology   | 2         | 2      | 1.17%   |
| SPCC                | 1         | 1      | 0.58%   |
| OCZ                 | 1         | 1      | 0.58%   |
| LITEON              | 1         | 1      | 0.58%   |
| KingFast            | 1         | 1      | 0.58%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 97     | 39.5%   |
| WDC                 | 24        | 34     | 20.17%  |
| Hitachi             | 15        | 18     | 12.61%  |
| Toshiba             | 12        | 12     | 10.08%  |
| Samsung Electronics | 7         | 9      | 5.88%   |
| HGST                | 6         | 6      | 5.04%   |
| Maxtor              | 4         | 5      | 3.36%   |
| Fujitsu             | 4         | 8      | 3.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 115       | 189    | 69.28%  |
| SSD  | 43        | 55     | 25.9%   |
| NVMe | 8         | 11     | 4.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BUCT-63TWBY0 320GB                 | 1         | 1      | 25%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 25%     |
| Hitachi HDS721010DLE630 1TB                  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 2      | 25%     |
| Hitachi             | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1145      | 2615   | 54.19%  |
| Works    | 802       | 1585   | 37.96%  |
| Malfunc  | 162       | 255    | 7.67%   |
| Failed   | 4         | 5      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1317      | 52.79%  |
| AMD                              | 327       | 13.11%  |
| Samsung Electronics              | 290       | 11.62%  |
| SanDisk                          | 87        | 3.49%   |
| SK hynix                         | 61        | 2.44%   |
| Kingston Technology Company      | 42        | 1.68%   |
| Micron/Crucial Technology        | 37        | 1.48%   |
| Phison Electronics               | 35        | 1.4%    |
| Micron Technology                | 34        | 1.36%   |
| ASMedia Technology               | 34        | 1.36%   |
| Marvell Technology Group         | 33        | 1.32%   |
| JMicron Technology               | 32        | 1.28%   |
| Toshiba America Info Systems     | 31        | 1.24%   |
| Nvidia                           | 25        | 1%      |
| KIOXIA                           | 20        | 0.8%    |
| Union Memory (Shenzhen)          | 9         | 0.36%   |
| Silicon Motion                   | 9         | 0.36%   |
| ADATA Technology                 | 9         | 0.36%   |
| Solid State Storage Technology   | 7         | 0.28%   |
| Seagate Technology               | 7         | 0.28%   |
| Silicon Image                    | 5         | 0.2%    |
| LSI Logic / Symbios Logic        | 5         | 0.2%    |
| Broadcom / LSI                   | 5         | 0.2%    |
| Apple                            | 5         | 0.2%    |
| Lite-On Technology               | 4         | 0.16%   |
| VIA Technologies                 | 3         | 0.12%   |
| Realtek Semiconductor            | 3         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.12%   |
| Hewlett-Packard                  | 3         | 0.12%   |
| Transcend                        | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Adaptec                          | 2         | 0.08%   |
| PMC-Sierra                       | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Areca Technology                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 223       | 7.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 165       | 5.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 98        | 3.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 92        | 3.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 73        | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 66        | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 58        | 2.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 52        | 1.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 50        | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 47        | 1.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 46        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 46        | 1.6%    |
| Intel SATA Controller [RAID mode]                                              | 40        | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 39        | 1.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 38        | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 36        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 36        | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 35        | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                         | 35        | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 1.11%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 32        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 32        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 29        | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 28        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 28        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 27        | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 27        | 0.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 0.87%   |
| Intel SSD 660P Series                                                          | 21        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 21        | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 20        | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 20        | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                             | 18        | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 18        | 0.62%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 17        | 0.59%   |
| Intel Tiger Lake-LP SATA Controller                                            | 17        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1390      | 54.85%  |
| NVMe | 695       | 27.43%  |
| IDE  | 244       | 9.63%   |
| RAID | 189       | 7.46%   |
| SAS  | 14        | 0.55%   |
| SCSI | 2         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1500      | 77.44%  |
| AMD     | 420       | 21.68%  |
| ARM     | 15        | 0.77%   |
| Unknown | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 28        | 1.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 26        | 1.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 22        | 1.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 22        | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor       | 22        | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 18        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 17        | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 17        | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 16        | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 14        | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 14        | 0.72%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 13        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 13        | 0.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 12        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 12        | 0.62%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 12        | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 12        | 0.62%   |
| ARM Processor                           | 12        | 0.62%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 11        | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 11        | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 0.57%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 11        | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 10        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 10        | 0.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.52%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 10        | 0.52%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 10        | 0.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 9         | 0.46%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 9         | 0.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.46%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 9         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 9         | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 9         | 0.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 9         | 0.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.46%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 9         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 444       | 22.9%   |
| Intel Core i5           | 424       | 21.87%  |
| Other                   | 161       | 8.3%    |
| Intel Core i3           | 132       | 6.81%   |
| AMD Ryzen 5             | 104       | 5.36%   |
| Intel Core 2 Duo        | 96        | 4.95%   |
| AMD Ryzen 7             | 89        | 4.59%   |
| Intel Celeron           | 56        | 2.89%   |
| AMD Ryzen 9             | 49        | 2.53%   |
| Intel Xeon              | 35        | 1.81%   |
| Intel Pentium           | 32        | 1.65%   |
| Intel Atom              | 25        | 1.29%   |
| Intel Pentium Dual-Core | 23        | 1.19%   |
| Intel Core 2            | 21        | 1.08%   |
| Intel Core 2 Quad       | 19        | 0.98%   |
| AMD Ryzen 7 PRO         | 15        | 0.77%   |
| Intel Core i9           | 13        | 0.67%   |
| AMD Ryzen 5 PRO         | 13        | 0.67%   |
| AMD E1                  | 13        | 0.67%   |
| AMD Ryzen 3             | 12        | 0.62%   |
| AMD E                   | 10        | 0.52%   |
| AMD A8                  | 10        | 0.52%   |
| AMD A4                  | 10        | 0.52%   |
| Intel Genuine           | 9         | 0.46%   |
| AMD FX                  | 9         | 0.46%   |
| AMD A6                  | 9         | 0.46%   |
| Intel Pentium Dual      | 8         | 0.41%   |
| AMD A10                 | 8         | 0.41%   |
| Intel Pentium Silver    | 7         | 0.36%   |
| AMD Phenom II X4        | 7         | 0.36%   |
| AMD Athlon II X2        | 6         | 0.31%   |
| Intel Pentium 4         | 5         | 0.26%   |
| AMD Phenom              | 5         | 0.26%   |
| AMD Ryzen Threadripper  | 4         | 0.21%   |
| AMD Athlon II X4        | 4         | 0.21%   |
| AMD Athlon 64 X2        | 4         | 0.21%   |
| Intel Xeon Silver       | 3         | 0.15%   |
| Intel Celeron M         | 3         | 0.15%   |
| ARM BCM                 | 3         | 0.15%   |
| AMD Turion 64 X2 Mobile | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 722       | 37.2%   |
| 2       | 714       | 36.79%  |
| 6       | 199       | 10.25%  |
| 8       | 154       | 7.93%   |
| 12      | 57        | 2.94%   |
| 1       | 29        | 1.49%   |
| 10      | 22        | 1.13%   |
| 16      | 14        | 0.72%   |
| 14      | 8         | 0.41%   |
| Unknown | 7         | 0.36%   |
| 3       | 6         | 0.31%   |
| 24      | 3         | 0.15%   |
| 64      | 2         | 0.1%    |
| 32      | 2         | 0.1%    |
| 128     | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1916      | 98.92%  |
| 2       | 17        | 0.88%   |
| Unknown | 3         | 0.15%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1339      | 69.02%  |
| 1       | 594       | 30.62%  |
| Unknown | 7         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1891      | 97.27%  |
| Unknown        | 39        | 2.01%   |
| 32-bit         | 13        | 0.67%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 554       | 27.13%  |
| 0x306a9    | 116       | 5.68%   |
| 0x206a7    | 106       | 5.19%   |
| 0x306c3    | 100       | 4.9%    |
| 0x1067a    | 64        | 3.13%   |
| 0x906e9    | 50        | 2.45%   |
| 0x906ea    | 47        | 2.3%    |
| 0x806ea    | 47        | 2.3%    |
| 0x806ec    | 43        | 2.11%   |
| 0x40651    | 37        | 1.81%   |
| 0x806c1    | 36        | 1.76%   |
| 0x506e3    | 36        | 1.76%   |
| 0x20655    | 34        | 1.67%   |
| 0x806e9    | 32        | 1.57%   |
| 0x08701021 | 31        | 1.52%   |
| 0x406e3    | 30        | 1.47%   |
| 0x306d4    | 30        | 1.47%   |
| 0x6fd      | 27        | 1.32%   |
| 0x10676    | 22        | 1.08%   |
| 0x0a50000c | 20        | 0.98%   |
| 0xa0652    | 19        | 0.93%   |
| 0x08600106 | 18        | 0.88%   |
| 0x30678    | 16        | 0.78%   |
| 0x106e5    | 15        | 0.73%   |
| 0x08701013 | 15        | 0.73%   |
| 0x08608103 | 15        | 0.73%   |
| 0x08108109 | 15        | 0.73%   |
| 0x6f6      | 14        | 0.69%   |
| 0x806eb    | 13        | 0.64%   |
| 0x6fb      | 13        | 0.64%   |
| 0x0800820d | 13        | 0.64%   |
| 0x20652    | 12        | 0.59%   |
| 0x206d7    | 11        | 0.54%   |
| 0x08600103 | 11        | 0.54%   |
| 0x010000c8 | 11        | 0.54%   |
| 0x806d1    | 10        | 0.49%   |
| 0x0a201009 | 10        | 0.49%   |
| 0x05000119 | 10        | 0.49%   |
| 0x906a3    | 9         | 0.44%   |
| 0x0810100b | 9         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 325       | 16.76%  |
| Haswell          | 182       | 9.39%   |
| IvyBridge        | 148       | 7.63%   |
| SandyBridge      | 147       | 7.58%   |
| Zen 2            | 110       | 5.67%   |
| Penryn           | 106       | 5.47%   |
| Skylake          | 95        | 4.9%    |
| Unknown          | 89        | 4.59%   |
| Core             | 75        | 3.87%   |
| Zen 3            | 63        | 3.25%   |
| Westmere         | 61        | 3.15%   |
| TigerLake        | 56        | 2.89%   |
| Zen+             | 47        | 2.42%   |
| CometLake        | 46        | 2.37%   |
| Silvermont       | 44        | 2.27%   |
| Broadwell        | 44        | 2.27%   |
| Alderlake Hybrid | 41        | 2.11%   |
| Zen              | 30        | 1.55%   |
| K10              | 30        | 1.55%   |
| Nehalem          | 27        | 1.39%   |
| Icelake          | 25        | 1.29%   |
| Piledriver       | 19        | 0.98%   |
| Goldmont plus    | 18        | 0.93%   |
| Bobcat           | 17        | 0.88%   |
| Excavator        | 15        | 0.77%   |
| Puma             | 13        | 0.67%   |
| Jaguar           | 12        | 0.62%   |
| Bonnell          | 11        | 0.57%   |
| K8 Hammer        | 10        | 0.52%   |
| P6               | 8         | 0.41%   |
| NetBurst         | 8         | 0.41%   |
| Goldmont         | 5         | 0.26%   |
| Tremont          | 4         | 0.21%   |
| K8 & K10 hybrid  | 3         | 0.15%   |
| Steamroller      | 2         | 0.1%    |
| K10 Llano        | 2         | 0.1%    |
| Gracemont        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1087      | 47.51%  |
| Nvidia                           | 709       | 30.99%  |
| AMD                              | 478       | 20.89%  |
| Matrox Electronics Systems       | 9         | 0.39%   |
| ASPEED Technology                | 3         | 0.13%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 91        | 3.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91        | 3.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 52        | 2.21%   |
| Intel UHD Graphics 620                                                                   | 52        | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 1.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 39        | 1.66%   |
| Intel HD Graphics 630                                                                    | 37        | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 36        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 35        | 1.49%   |
| Intel HD Graphics 620                                                                    | 35        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 32        | 1.36%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 29        | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 27        | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 23        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 0.98%   |
| Intel HD Graphics 530                                                                    | 22        | 0.93%   |
| AMD Lucienne                                                                             | 22        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 20        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 20        | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 19        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 18        | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 18        | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.68%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 15        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 14        | 0.59%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.55%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 12        | 0.51%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 12        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 761       | 38.83%  |
| 1 x Nvidia         | 423       | 21.58%  |
| 1 x AMD            | 377       | 19.23%  |
| Intel + Nvidia     | 253       | 12.91%  |
| Intel + AMD        | 53        | 2.7%    |
| AMD + Nvidia       | 30        | 1.53%   |
| Other              | 21        | 1.07%   |
| 2 x AMD            | 20        | 1.02%   |
| 1 x Matrox         | 9         | 0.46%   |
| 2 x Intel          | 4         | 0.2%    |
| 2 x Nvidia         | 3         | 0.15%   |
| 1 x ASPEED         | 2         | 0.1%    |
| 1 x VIA            | 1         | 0.05%   |
| 1 x SiS            | 1         | 0.05%   |
| Nvidia + ASPEED    | 1         | 0.05%   |
| Intel + 2 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1520      | 76.5%   |
| Proprietary | 370       | 18.62%  |
| Unknown     | 97        | 4.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1076      | 53.48%  |
| 1.01-2.0   | 239       | 11.88%  |
| 0.01-0.5   | 232       | 11.53%  |
| 0.51-1.0   | 156       | 7.75%   |
| 3.01-4.0   | 112       | 5.57%   |
| 7.01-8.0   | 99        | 4.92%   |
| 5.01-6.0   | 49        | 2.44%   |
| 8.01-16.0  | 30        | 1.49%   |
| 2.01-3.0   | 13        | 0.65%   |
| 16.01-24.0 | 6         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 301       | 14.22%  |
| AU Optronics            | 294       | 13.89%  |
| LG Display              | 206       | 9.74%   |
| Chimei Innolux          | 144       | 6.81%   |
| BOE                     | 128       | 6.05%   |
| Dell                    | 117       | 5.53%   |
| Iiyama                  | 89        | 4.21%   |
| Goldstar                | 83        | 3.92%   |
| Philips                 | 71        | 3.36%   |
| Hewlett-Packard         | 70        | 3.31%   |
| AOC                     | 48        | 2.27%   |
| BenQ                    | 47        | 2.22%   |
| Acer                    | 47        | 2.22%   |
| Sharp                   | 45        | 2.13%   |
| Apple                   | 39        | 1.84%   |
| Medion                  | 36        | 1.7%    |
| Lenovo                  | 34        | 1.61%   |
| Chi Mei Optoelectronics | 32        | 1.51%   |
| Ancor Communications    | 28        | 1.32%   |
| Sony                    | 16        | 0.76%   |
| Unknown                 | 15        | 0.71%   |
| InfoVision              | 13        | 0.61%   |
| Fujitsu Siemens         | 13        | 0.61%   |
| ASUSTek Computer        | 11        | 0.52%   |
| Eizo                    | 10        | 0.47%   |
| PANDA                   | 9         | 0.43%   |
| LG Philips              | 9         | 0.43%   |
| CSO                     | 9         | 0.43%   |
| Vestel Elektronik       | 8         | 0.38%   |
| Valve                   | 7         | 0.33%   |
| Panasonic               | 7         | 0.33%   |
| MSI                     | 7         | 0.33%   |
| Idek Iiyama             | 7         | 0.33%   |
| NEC Computers           | 6         | 0.28%   |
| LG Electronics          | 6         | 0.28%   |
| Gigabyte Technology     | 6         | 0.28%   |
| Arnos Instruments       | 6         | 0.28%   |
| ViewSonic               | 5         | 0.24%   |
| Seiko/Epson             | 5         | 0.24%   |
| Packard Bell            | 5         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 18        | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 14        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 11        | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 10        | 0.45%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 9         | 0.4%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 9         | 0.4%    |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch        | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.36%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 7         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 7         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 7         | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 6         | 0.27%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 6         | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 6         | 0.27%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 6         | 0.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.27%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 6         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.27%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                          | 6         | 0.27%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch         | 5         | 0.22%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 5         | 0.22%   |
| Medion MD 20430 MED36A2 1920x1080 521x293mm 23.5-inch                     | 5         | 0.22%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 5         | 0.22%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 5         | 0.22%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                         | 5         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 5         | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO149E 1600x900 382x214mm 17.2-inch             | 5         | 0.22%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 5         | 0.22%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 4         | 0.18%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.18%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 4         | 0.18%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch       | 4         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 904       | 44.58%  |
| 1366x768 (WXGA)    | 239       | 11.79%  |
| 3840x2160 (4K)     | 150       | 7.4%    |
| 1600x900 (HD+)     | 128       | 6.31%   |
| 2560x1440 (QHD)    | 122       | 6.02%   |
| 1680x1050 (WSXGA+) | 75        | 3.7%    |
| 1280x1024 (SXGA)   | 63        | 3.11%   |
| 1440x900 (WXGA+)   | 54        | 2.66%   |
| 1920x1200 (WUXGA)  | 52        | 2.56%   |
| 1280x800 (WXGA)    | 37        | 1.82%   |
| Unknown            | 26        | 1.28%   |
| 3440x1440          | 24        | 1.18%   |
| 3840x1080          | 18        | 0.89%   |
| 2560x1600          | 16        | 0.79%   |
| 2560x1080          | 12        | 0.59%   |
| 1360x768           | 10        | 0.49%   |
| 3840x2400          | 9         | 0.44%   |
| 1600x1200          | 8         | 0.39%   |
| 800x1280           | 7         | 0.35%   |
| 2880x1800          | 7         | 0.35%   |
| 1024x600           | 7         | 0.35%   |
| 3200x1800 (QHD+)   | 6         | 0.3%    |
| 1680x945           | 5         | 0.25%   |
| 1024x768 (XGA)     | 5         | 0.25%   |
| 2736x1824          | 4         | 0.2%    |
| 5760x1080          | 3         | 0.15%   |
| 1920x1280          | 3         | 0.15%   |
| 3840x1600          | 2         | 0.1%    |
| 2960x1050          | 2         | 0.1%    |
| 2880x1620          | 2         | 0.1%    |
| 2288x1287          | 2         | 0.1%    |
| 2256x1504          | 2         | 0.1%    |
| 2048x1152          | 2         | 0.1%    |
| 1920x540           | 2         | 0.1%    |
| 1280x960           | 2         | 0.1%    |
| 7680x2160          | 1         | 0.05%   |
| 6320x1800          | 1         | 0.05%   |
| 5120x1440          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 516       | 24.23%  |
| 27      | 191       | 8.97%   |
| 17      | 189       | 8.87%   |
| 24      | 167       | 7.84%   |
| 13      | 162       | 7.61%   |
| 23      | 143       | 6.71%   |
| 14      | 118       | 5.54%   |
| Unknown | 114       | 5.35%   |
| 21      | 110       | 5.16%   |
| 19      | 55        | 2.58%   |
| 22      | 40        | 1.88%   |
| 31      | 36        | 1.69%   |
| 34      | 33        | 1.55%   |
| 18      | 31        | 1.46%   |
| 20      | 30        | 1.41%   |
| 12      | 28        | 1.31%   |
| 11      | 18        | 0.85%   |
| 16      | 17        | 0.8%    |
| 25      | 15        | 0.7%    |
| 72      | 13        | 0.61%   |
| 10      | 12        | 0.56%   |
| 84      | 11        | 0.52%   |
| 32      | 11        | 0.52%   |
| 54      | 9         | 0.42%   |
| 40      | 8         | 0.38%   |
| 7       | 6         | 0.28%   |
| 49      | 5         | 0.23%   |
| 29      | 4         | 0.19%   |
| 65      | 3         | 0.14%   |
| 63      | 3         | 0.14%   |
| 46      | 3         | 0.14%   |
| 33      | 3         | 0.14%   |
| 26      | 3         | 0.14%   |
| 142     | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 48      | 2         | 0.09%   |
| 43      | 2         | 0.09%   |
| 42      | 2         | 0.09%   |
| 39      | 2         | 0.09%   |
| 37      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 707       | 33.65%  |
| 501-600        | 461       | 21.94%  |
| 351-400        | 232       | 11.04%  |
| 401-500        | 221       | 10.52%  |
| 201-300        | 161       | 7.66%   |
| Unknown        | 114       | 5.43%   |
| 601-700        | 78        | 3.71%   |
| 701-800        | 47        | 2.24%   |
| 1001-1500      | 30        | 1.43%   |
| 1501-2000      | 24        | 1.14%   |
| 801-900        | 13        | 0.62%   |
| 1-100          | 7         | 0.33%   |
| 901-1000       | 4         | 0.19%   |
| More than 2000 | 2         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1407      | 74.09%  |
| 16/10   | 252       | 13.27%  |
| Unknown | 94        | 4.95%   |
| 5/4     | 58        | 3.05%   |
| 21/9    | 36        | 1.9%    |
| 4/3     | 16        | 0.84%   |
| 3/2     | 14        | 0.74%   |
| 6/5     | 6         | 0.32%   |
| 0.67    | 6         | 0.32%   |
| 32/9    | 5         | 0.26%   |
| 1.00    | 3         | 0.16%   |
| 3.73    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 513       | 24.39%  |
| 201-250        | 359       | 17.07%  |
| 301-350        | 195       | 9.27%   |
| 81-90          | 187       | 8.89%   |
| 121-130        | 149       | 7.09%   |
| 151-200        | 127       | 6.04%   |
| Unknown        | 114       | 5.42%   |
| 71-80          | 95        | 4.52%   |
| 351-500        | 88        | 4.18%   |
| 251-300        | 67        | 3.19%   |
| More than 1000 | 47        | 2.23%   |
| 141-150        | 33        | 1.57%   |
| 131-140        | 26        | 1.24%   |
| 61-70          | 25        | 1.19%   |
| 501-1000       | 24        | 1.14%   |
| 51-60          | 18        | 0.86%   |
| 111-120        | 15        | 0.71%   |
| 41-50          | 12        | 0.57%   |
| 1-40           | 7         | 0.33%   |
| 91-100         | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 653       | 31.82%  |
| 121-160       | 563       | 27.44%  |
| 101-120       | 494       | 24.07%  |
| 161-240       | 138       | 6.73%   |
| Unknown       | 114       | 5.56%   |
| More than 240 | 55        | 2.68%   |
| 1-50          | 35        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1541      | 77.28%  |
| 2     | 312       | 15.65%  |
| 0     | 103       | 5.17%   |
| 3     | 37        | 1.86%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1041      | 35.66%  |
| Realtek Semiconductor             | 1000      | 34.26%  |
| Qualcomm Atheros                  | 310       | 10.62%  |
| Broadcom                          | 158       | 5.41%   |
| TP-Link                           | 35        | 1.2%    |
| Broadcom Limited                  | 35        | 1.2%    |
| MediaTek                          | 33        | 1.13%   |
| Marvell Technology Group          | 33        | 1.13%   |
| Ralink                            | 25        | 0.86%   |
| Nvidia                            | 24        | 0.82%   |
| D-Link System                     | 17        | 0.58%   |
| ASIX Electronics                  | 17        | 0.58%   |
| Ralink Technology                 | 16        | 0.55%   |
| DisplayLink                       | 13        | 0.45%   |
| Lenovo                            | 10        | 0.34%   |
| Dell                              | 10        | 0.34%   |
| Sierra Wireless                   | 8         | 0.27%   |
| Microsoft                         | 8         | 0.27%   |
| IMC Networks                      | 8         | 0.27%   |
| Ericsson Business Mobile Networks | 7         | 0.24%   |
| D-Link                            | 7         | 0.24%   |
| ASUSTek Computer                  | 7         | 0.24%   |
| Hewlett-Packard                   | 6         | 0.21%   |
| Microchip Technology              | 5         | 0.17%   |
| Linksys                           | 5         | 0.17%   |
| JMicron Technology                | 5         | 0.17%   |
| Aquantia                          | 5         | 0.17%   |
| Sitecom Europe                    | 4         | 0.14%   |
| Samsung Electronics               | 4         | 0.14%   |
| Qualcomm Atheros Communications   | 4         | 0.14%   |
| Qualcomm                          | 4         | 0.14%   |
| Fibocom                           | 4         | 0.14%   |
| Xiaomi                            | 3         | 0.1%    |
| Arduino SA                        | 3         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| OPPO Electronics                  | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| MosChip Semiconductor             | 2         | 0.07%   |
| Huawei Technologies               | 2         | 0.07%   |
| Google                            | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 683       | 19.58%  |
| Intel Wi-Fi 6 AX200                                               | 121       | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 65        | 1.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 1.81%   |
| Intel I211 Gigabit Network Connection                             | 56        | 1.61%   |
| Intel Wireless 7260                                               | 52        | 1.49%   |
| Intel Wireless 8265 / 8275                                        | 50        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 48        | 1.38%   |
| Intel Wireless 7265                                               | 42        | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 42        | 1.2%    |
| Intel Wireless 8260                                               | 40        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 37        | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 35        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 33        | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 32        | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.86%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 28        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 0.75%   |
| Intel Wireless-AC 9260                                            | 25        | 0.72%   |
| Intel Ethernet Controller I225-V                                  | 25        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 22        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.54%   |
| Intel Centrino Wireless-N 2230                                    | 19        | 0.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 17        | 0.49%   |
| Intel Wireless 3165                                               | 17        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 793       | 51.19%  |
| Qualcomm Atheros                      | 242       | 15.62%  |
| Realtek Semiconductor                 | 198       | 12.78%  |
| Broadcom                              | 105       | 6.78%   |
| MediaTek                              | 29        | 1.87%   |
| TP-Link                               | 25        | 1.61%   |
| Ralink                                | 25        | 1.61%   |
| Broadcom Limited                      | 19        | 1.23%   |
| Ralink Technology                     | 16        | 1.03%   |
| D-Link System                         | 14        | 0.9%    |
| Sierra Wireless                       | 8         | 0.52%   |
| IMC Networks                          | 8         | 0.52%   |
| D-Link                                | 7         | 0.45%   |
| ASUSTek Computer                      | 7         | 0.45%   |
| Microsoft                             | 6         | 0.39%   |
| Dell                                  | 6         | 0.39%   |
| Linksys                               | 5         | 0.32%   |
| Sitecom Europe                        | 4         | 0.26%   |
| Qualcomm Atheros Communications       | 4         | 0.26%   |
| Qualcomm                              | 4         | 0.26%   |
| Fibocom                               | 4         | 0.26%   |
| Marvell Technology Group              | 3         | 0.19%   |
| Ericsson Business Mobile Networks     | 3         | 0.19%   |
| Edimax Technology                     | 2         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.13%   |
| Z-Com                                 | 1         | 0.06%   |
| Texas Instruments                     | 1         | 0.06%   |
| Tenda                                 | 1         | 0.06%   |
| Panasonic (Matsushita)                | 1         | 0.06%   |
| NetGear                               | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| Guillemot                             | 1         | 0.06%   |
| Gemtek                                | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |
| AVM                                   | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 121       | 7.76%   |
| Intel Wireless 7260                                            | 52        | 3.33%   |
| Intel Wireless 8265 / 8275                                     | 50        | 3.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 48        | 3.08%   |
| Intel Wireless 7265                                            | 42        | 2.69%   |
| Intel Wi-Fi 6 AX201                                            | 42        | 2.69%   |
| Intel Wireless 8260                                            | 40        | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 37        | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 35        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 33        | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 32        | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 30        | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 28        | 1.79%   |
| Intel Wireless-AC 9260                                         | 25        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24        | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 22        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.22%   |
| Intel Centrino Wireless-N 2230                                 | 19        | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.09%   |
| Intel Wireless 3165                                            | 17        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 0.96%   |
| Intel WiFi Link 5100                                           | 15        | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 0.96%   |
| Intel Centrino Advanced-N 6235                                 | 15        | 0.96%   |
| Intel Centrino Advanced-N 6200                                 | 15        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 13        | 0.83%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 13        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 11        | 0.71%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 921       | 49.84%  |
| Intel                                  | 561       | 30.36%  |
| Qualcomm Atheros                       | 118       | 6.39%   |
| Broadcom                               | 73        | 3.95%   |
| Marvell Technology Group               | 30        | 1.62%   |
| Nvidia                                 | 24        | 1.3%    |
| ASIX Electronics                       | 17        | 0.92%   |
| Broadcom Limited                       | 16        | 0.87%   |
| DisplayLink                            | 13        | 0.7%    |
| Lenovo                                 | 10        | 0.54%   |
| TP-Link                                | 9         | 0.49%   |
| JMicron Technology                     | 5         | 0.27%   |
| Hewlett-Packard                        | 5         | 0.27%   |
| Aquantia                               | 5         | 0.27%   |
| Microchip Technology                   | 4         | 0.22%   |
| MediaTek                               | 4         | 0.22%   |
| Xiaomi                                 | 3         | 0.16%   |
| Samsung Electronics                    | 3         | 0.16%   |
| D-Link System                          | 3         | 0.16%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.11%   |
| OPPO Electronics                       | 2         | 0.11%   |
| Motorola PCS                           | 2         | 0.11%   |
| MosChip Semiconductor                  | 2         | 0.11%   |
| Google                                 | 2         | 0.11%   |
| Attansic Technology                    | 2         | 0.11%   |
| Apple                                  | 2         | 0.11%   |
| ADMtek                                 | 2         | 0.11%   |
| VIA Technologies                       | 1         | 0.05%   |
| Tehuti Networks                        | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OpenMoko                               | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| IBM                                    | 1         | 0.05%   |
| Huawei Technologies                    | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 683       | 36%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 4.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 4.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 65        | 3.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 3.32%   |
| Intel I211 Gigabit Network Connection                             | 56        | 2.95%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 1.37%   |
| Intel Ethernet Controller I225-V                                  | 25        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 20        | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 1%      |
| Intel Ethernet Connection I218-LM                                 | 19        | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.9%    |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 14        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                             | 12        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 11        | 0.58%   |
| Intel 82574L Gigabit Network Connection                           | 11        | 0.58%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 10        | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.53%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 9         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 9         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.42%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 8         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 7         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1729      | 53.43%  |
| WiFi     | 1476      | 45.61%  |
| Modem    | 26        | 0.8%    |
| Unknown  | 5         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1078      | 52.56%  |
| Ethernet | 973       | 47.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1111      | 57.03%  |
| 1     | 736       | 37.78%  |
| 3     | 53        | 2.72%   |
| 0     | 36        | 1.85%   |
| 4     | 6         | 0.31%   |
| 5     | 3         | 0.15%   |
| 6     | 2         | 0.1%    |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1357      | 67.28%  |
| Yes  | 660       | 32.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 620       | 52.23%  |
| Realtek Semiconductor           | 97        | 8.17%   |
| Qualcomm Atheros Communications | 62        | 5.22%   |
| Broadcom                        | 56        | 4.72%   |
| Cambridge Silicon Radio         | 54        | 4.55%   |
| IMC Networks                    | 49        | 4.13%   |
| Foxconn / Hon Hai               | 43        | 3.62%   |
| Apple                           | 41        | 3.45%   |
| Lite-On Technology              | 29        | 2.44%   |
| ASUSTek Computer                | 29        | 2.44%   |
| Dell                            | 26        | 2.19%   |
| Hewlett-Packard                 | 24        | 2.02%   |
| Toshiba                         | 12        | 1.01%   |
| Belkin Components               | 8         | 0.67%   |
| MediaTek                        | 6         | 0.51%   |
| Ralink                          | 5         | 0.42%   |
| Alps Electric                   | 5         | 0.42%   |
| TP-Link                         | 4         | 0.34%   |
| Foxconn International           | 4         | 0.34%   |
| Ralink Technology               | 3         | 0.25%   |
| Marvell Semiconductor           | 3         | 0.25%   |
| USI                             | 1         | 0.08%   |
| Realtek                         | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| Logitech                        | 1         | 0.08%   |
| Integrated System Solution      | 1         | 0.08%   |
| HTC (High Tech Computer)        | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 209       | 17.56%  |
| Intel AX200 Bluetooth                               | 119       | 10%     |
| Intel AX201 Bluetooth                               | 101       | 8.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 79        | 6.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 54        | 4.54%   |
| Realtek Bluetooth Radio                             | 48        | 4.03%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 2.44%   |
| Intel Bluetooth Device                              | 28        | 2.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 27        | 2.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 2.1%    |
| IMC Networks Bluetooth Radio                        | 19        | 1.6%    |
| Apple Bluetooth Host Controller                     | 18        | 1.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 1.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 1.34%   |
| Intel AX210 Bluetooth                               | 15        | 1.26%   |
| IMC Networks Bluetooth Device                       | 15        | 1.26%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.18%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 1.09%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 12        | 1.01%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 11        | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.84%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.84%   |
| Broadcom HP Portable SoftSailing                    | 10        | 0.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.84%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 9         | 0.76%   |
| Dell BCM20702A0 Bluetooth Module                    | 8         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.59%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.5%    |
| Lite-On Bluetooth Device                            | 6         | 0.5%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.5%    |
| Broadcom BCM2045 Bluetooth                          | 6         | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.5%    |
| Toshiba Bluetooth Device                            | 5         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1441      | 51.43%  |
| Nvidia                               | 532       | 18.99%  |
| AMD                                  | 510       | 18.2%   |
| C-Media Electronics                  | 47        | 1.68%   |
| Logitech                             | 23        | 0.82%   |
| Creative Labs                        | 17        | 0.61%   |
| Kingston Technology                  | 16        | 0.57%   |
| Hewlett-Packard                      | 14        | 0.5%    |
| GN Netcom                            | 14        | 0.5%    |
| Realtek Semiconductor                | 13        | 0.46%   |
| Corsair                              | 12        | 0.43%   |
| Plantronics                          | 10        | 0.36%   |
| Focusrite-Novation                   | 9         | 0.32%   |
| ASUSTek Computer                     | 9         | 0.32%   |
| SteelSeries ApS                      | 8         | 0.29%   |
| JMTek                                | 8         | 0.29%   |
| Razer USA                            | 7         | 0.25%   |
| Texas Instruments                    | 6         | 0.21%   |
| RODE Microphones                     | 6         | 0.21%   |
| Generalplus Technology               | 6         | 0.21%   |
| VIA Technologies                     | 5         | 0.18%   |
| Micro Star International             | 5         | 0.18%   |
| Audio-Technica                       | 5         | 0.18%   |
| Roland                               | 4         | 0.14%   |
| DSEA A/S                             | 4         | 0.14%   |
| Blue Microphones                     | 4         | 0.14%   |
| Astro Gaming                         | 4         | 0.14%   |
| Lenovo                               | 3         | 0.11%   |
| Dell                                 | 3         | 0.11%   |
| Trust                                | 2         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| Sony                                 | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.07%   |
| OPPO Electronics                     | 2         | 0.07%   |
| M-Audio                              | 2         | 0.07%   |
| Harman International                 | 2         | 0.07%   |
| GYROCOM C&C                          | 2         | 0.07%   |
| FIFINE Microphones                   | 2         | 0.07%   |
| Creative Technology                  | 2         | 0.07%   |
| BEHRINGER International              | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 151       | 4.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 146       | 4.47%   |
| Intel Sunrise Point-LP HD Audio                                            | 143       | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 127       | 3.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 97        | 2.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 95        | 2.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 85        | 2.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 76        | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 73        | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 71        | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 66        | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 56        | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 56        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 50        | 1.53%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 1.47%   |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 44        | 1.35%   |
| Intel 200 Series PCH HD Audio                                              | 44        | 1.35%   |
| AMD FCH Azalia Controller                                                  | 44        | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 43        | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 40        | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 37        | 1.13%   |
| Intel Comet Lake PCH cAVS                                                  | 36        | 1.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.07%   |
| Nvidia GK107 HDMI Audio Controller                                         | 34        | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 34        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 32        | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 31        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 31        | 0.95%   |
| Intel CM238 HD Audio Controller                                            | 31        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 30        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 30        | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 30        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 29        | 0.89%   |
| Nvidia GP104 High Definition Audio Controller                              | 29        | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 28        | 0.86%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 26        | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 288       | 23.53%  |
| SK hynix            | 223       | 18.22%  |
| Kingston            | 153       | 12.5%   |
| Corsair             | 122       | 9.97%   |
| Micron Technology   | 116       | 9.48%   |
| Unknown             | 86        | 7.03%   |
| Crucial             | 67        | 5.47%   |
| G.Skill             | 45        | 3.68%   |
| Elpida              | 25        | 2.04%   |
| Ramaxel Technology  | 19        | 1.55%   |
| Nanya Technology    | 19        | 1.55%   |
| A-DATA Technology   | 13        | 1.06%   |
| Unknown (ABCD)      | 9         | 0.74%   |
| Unknown             | 7         | 0.57%   |
| Unifosa             | 6         | 0.49%   |
| Transcend           | 4         | 0.33%   |
| Timetec             | 2         | 0.16%   |
| Team                | 2         | 0.16%   |
| Patriot             | 2         | 0.16%   |
| GOODRAM             | 2         | 0.16%   |
| Unknown (0x8551)    | 1         | 0.08%   |
| Unknown (0x0DD5)    | 1         | 0.08%   |
| Unknown (09D5)      | 1         | 0.08%   |
| TRS STAR            | 1         | 0.08%   |
| TakeMS              | 1         | 0.08%   |
| Qimonda             | 1         | 0.08%   |
| PNY                 | 1         | 0.08%   |
| OCZ                 | 1         | 0.08%   |
| J&A Information     | 1         | 0.08%   |
| GeIL                | 1         | 0.08%   |
| Corsair SerNum0     | 1         | 0.08%   |
| Aeneon              | 1         | 0.08%   |
| A-DA                | 1         | 0.08%   |
| A Force             | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 15        | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.68%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.68%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.68%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 7         | 0.53%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 7         | 0.53%   |
| Unknown                                                          | 7         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.46%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.46%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 6         | 0.46%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 5         | 0.38%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.38%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.38%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 5         | 0.38%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 5         | 0.38%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.38%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 5         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 525       | 48.03%  |
| DDR3    | 357       | 32.66%  |
| DDR2    | 59        | 5.4%    |
| SDRAM   | 39        | 3.57%   |
| LPDDR3  | 30        | 2.74%   |
| LPDDR4  | 27        | 2.47%   |
| Unknown | 22        | 2.01%   |
| DDR5    | 19        | 1.74%   |
| LPDDR5  | 11        | 1.01%   |
| DDR     | 4         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 634       | 59.03%  |
| DIMM         | 363       | 33.8%   |
| Row Of Chips | 68        | 6.33%   |
| Chip         | 5         | 0.47%   |
| FB-DIMM      | 2         | 0.19%   |
| RIMM         | 1         | 0.09%   |
| Unknown      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 446       | 38.32%  |
| 4096  | 299       | 25.69%  |
| 16384 | 205       | 17.61%  |
| 2048  | 132       | 11.34%  |
| 32768 | 41        | 3.52%   |
| 1024  | 34        | 2.92%   |
| 512   | 6         | 0.52%   |
| 8     | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 235       | 19.92%  |
| 3200    | 195       | 16.53%  |
| 2667    | 156       | 13.22%  |
| 2400    | 85        | 7.2%    |
| 1333    | 74        | 6.27%   |
| 2133    | 67        | 5.68%   |
| 1334    | 36        | 3.05%   |
| 667     | 32        | 2.71%   |
| 3600    | 29        | 2.46%   |
| 800     | 24        | 2.03%   |
| 1867    | 17        | 1.44%   |
| 1067    | 15        | 1.27%   |
| Unknown | 15        | 1.27%   |
| 3400    | 13        | 1.1%    |
| 1800    | 13        | 1.1%    |
| 4800    | 12        | 1.02%   |
| 4267    | 11        | 0.93%   |
| 2048    | 11        | 0.93%   |
| 6400    | 9         | 0.76%   |
| 3866    | 9         | 0.76%   |
| 3533    | 9         | 0.76%   |
| 3266    | 9         | 0.76%   |
| 2666    | 9         | 0.76%   |
| 3000    | 8         | 0.68%   |
| 3534    | 6         | 0.51%   |
| 1066    | 6         | 0.51%   |
| 3666    | 5         | 0.42%   |
| 975     | 5         | 0.42%   |
| 533     | 5         | 0.42%   |
| 4199    | 4         | 0.34%   |
| 3733    | 4         | 0.34%   |
| 2933    | 4         | 0.34%   |
| 1866    | 4         | 0.34%   |
| 8400    | 3         | 0.25%   |
| 6000    | 3         | 0.25%   |
| 5200    | 3         | 0.25%   |
| 3800    | 3         | 0.25%   |
| 3100    | 3         | 0.25%   |
| 1639    | 3         | 0.25%   |
| 1331    | 3         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 41.54%  |
| Brother Industries  | 14        | 21.54%  |
| Canon               | 9         | 13.85%  |
| Seiko Epson         | 6         | 9.23%   |
| Samsung Electronics | 4         | 6.15%   |
| Kyocera             | 2         | 3.08%   |
| Ricoh               | 1         | 1.54%   |
| Prolific Technology | 1         | 1.54%   |
| Dymo-CoStar         | 1         | 1.54%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                                   | 2         | 2.99%   |
| Samsung ML-1660 Series                                     | 2         | 2.99%   |
| HP ENVY 4500 series                                        | 2         | 2.99%   |
| HP DeskJet 3630 series                                     | 2         | 2.99%   |
| Seiko Epson XP-2200 Series                                 | 1         | 1.49%   |
| Seiko Epson WF-3010 Series                                 | 1         | 1.49%   |
| Seiko Epson ET-8550 Series                                 | 1         | 1.49%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.49%   |
| Samsung SCX-472x Series                                    | 1         | 1.49%   |
| Samsung ML-1640 Series Laser Printer                       | 1         | 1.49%   |
| Ricoh SP C250SF                                            | 1         | 1.49%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.49%   |
| Kyocera TASKalfa 250ci                                     | 1         | 1.49%   |
| Kyocera FS-C5150DN                                         | 1         | 1.49%   |
| HP OfficeJet Pro 6960                                      | 1         | 1.49%   |
| HP OfficeJet Pro 69                                        | 1         | 1.49%   |
| HP Officejet 2620 series                                   | 1         | 1.49%   |
| HP LaserJet Professional P 1102w                           | 1         | 1.49%   |
| HP LaserJet Pro M148f-M149f                                | 1         | 1.49%   |
| HP LaserJet P4015                                          | 1         | 1.49%   |
| HP LaserJet CP1525nw/x                                     | 1         | 1.49%   |
| HP LaserJet CM1415fnw                                      | 1         | 1.49%   |
| HP LaserJet 3015                                           | 1         | 1.49%   |
| HP LaserJet 1020                                           | 1         | 1.49%   |
| HP LaserJet 1015                                           | 1         | 1.49%   |
| HP EWS UPD                                                 | 1         | 1.49%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.49%   |
| HP ENVY 6000 series                                        | 1         | 1.49%   |
| HP ENVY 5540 series                                        | 1         | 1.49%   |
| HP ENVY 4520 series                                        | 1         | 1.49%   |
| HP Deskjet F4500 series                                    | 1         | 1.49%   |
| HP DeskJet F300 series                                     | 1         | 1.49%   |
| HP DeskJet 5650c                                           | 1         | 1.49%   |
| HP DeskJet 5150c                                           | 1         | 1.49%   |
| HP DeskJet 4100 series                                     | 1         | 1.49%   |
| HP DeskJet 3700 series                                     | 1         | 1.49%   |
| HP DeskJet 2620 All-in-One Printer                         | 1         | 1.49%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.49%   |
| Canon TS6300 series                                        | 1         | 1.49%   |
| Canon TS5300 series                                        | 1         | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 7         | 33.33%  |
| Hewlett-Packard | 7         | 33.33%  |
| Canon           | 6         | 28.57%  |
| AGFA-Gevaert NV | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 2         | 9.52%   |
| Canon CanoScan LiDE 210                                 | 2         | 9.52%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]        | 1         | 4.76%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.76%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 4.76%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1         | 4.76%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 4.76%   |
| HP ScanJet G4010                                        | 1         | 4.76%   |
| HP scanjet 8270                                         | 1         | 4.76%   |
| HP ScanJet 4370                                         | 1         | 4.76%   |
| HP ScanJet 3800c                                        | 1         | 4.76%   |
| HP ScanJet 3670                                         | 1         | 4.76%   |
| HP ScanJet 3400cse                                      | 1         | 4.76%   |
| HP Scanjet 200                                          | 1         | 4.76%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 4.76%   |
| Canon CanoScan LiDE 110                                 | 1         | 4.76%   |
| Canon CanoScan 8800F                                    | 1         | 4.76%   |
| Canon CanoScan 3200F                                    | 1         | 4.76%   |
| AGFA-Gevaert NV Snapscan e40                            | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 270       | 22.59%  |
| Microdia                               | 123       | 10.29%  |
| Realtek Semiconductor                  | 91        | 7.62%   |
| Logitech                               | 84        | 7.03%   |
| IMC Networks                           | 84        | 7.03%   |
| Bison Electronics                      | 66        | 5.52%   |
| Sunplus Innovation Technology          | 53        | 4.44%   |
| Quanta                                 | 48        | 4.02%   |
| Suyin                                  | 44        | 3.68%   |
| Lite-On Technology                     | 40        | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 3.26%   |
| Apple                                  | 39        | 3.26%   |
| Syntek                                 | 34        | 2.85%   |
| Acer                                   | 21        | 1.76%   |
| Luxvisions Innotech Limited            | 17        | 1.42%   |
| Alcor Micro                            | 17        | 1.42%   |
| Ricoh                                  | 14        | 1.17%   |
| Samsung Electronics                    | 10        | 0.84%   |
| Silicon Motion                         | 6         | 0.5%    |
| Generalplus Technology                 | 6         | 0.5%    |
| Trust                                  | 5         | 0.42%   |
| Sonix Technology                       | 5         | 0.42%   |
| Primax Electronics                     | 5         | 0.42%   |
| Lenovo                                 | 5         | 0.42%   |
| Jieli Technology                       | 5         | 0.42%   |
| ALi                                    | 5         | 0.42%   |
| Microsoft                              | 4         | 0.33%   |
| Importek                               | 4         | 0.33%   |
| Creative Technology                    | 4         | 0.33%   |
| Z-Star Microelectronics                | 3         | 0.25%   |
| WaveRider Communications               | 3         | 0.25%   |
| Sunplus Technology                     | 2         | 0.17%   |
| STEREOLABS                             | 2         | 0.17%   |
| Pixart Imaging                         | 2         | 0.17%   |
| OPPO Electronics                       | 2         | 0.17%   |
| Novatek Microelectronics               | 2         | 0.17%   |
| KYE Systems (Mouse Systems)            | 2         | 0.17%   |
| icSpring                               | 2         | 0.17%   |
| Hewlett-Packard                        | 2         | 0.17%   |
| GEMBIRD                                | 2         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 41        | 3.41%   |
| Chicony Integrated Camera                | 41        | 3.41%   |
| Microdia Integrated_Webcam_HD            | 38        | 3.16%   |
| IMC Networks Integrated Camera           | 34        | 2.82%   |
| Bison Integrated Camera                  | 26        | 2.16%   |
| Syntek Integrated Camera                 | 23        | 1.91%   |
| Chicony HD Webcam                        | 21        | 1.74%   |
| Quanta HP HD Camera                      | 17        | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam        | 17        | 1.41%   |
| Microdia Integrated Webcam               | 16        | 1.33%   |
| Chicony HP HD Camera                     | 15        | 1.25%   |
| Lite-On HP HD Camera                     | 14        | 1.16%   |
| Logitech HD Webcam C525                  | 13        | 1.08%   |
| Lite-On Integrated Camera                | 13        | 1.08%   |
| Chicony HP HD Webcam                     | 13        | 1.08%   |
| Apple Built-in iSight                    | 13        | 1.08%   |
| Chicony USB2.0 Camera                    | 12        | 1%      |
| Chicony HP Wide Vision HD Camera         | 12        | 1%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 12        | 1%      |
| Realtek USB Camera                       | 11        | 0.91%   |
| Sunplus HD WebCam                        | 10        | 0.83%   |
| Samsung Galaxy series, misc. (MTP mode)  | 10        | 0.83%   |
| Microdia Camera                          | 9         | 0.75%   |
| Logitech Webcam C270                     | 9         | 0.75%   |
| Chicony USB2.0 HD UVC WebCam             | 9         | 0.75%   |
| Chicony TOSHIBA Web Camera - HD          | 9         | 0.75%   |
| Chicony EasyCamera                       | 9         | 0.75%   |
| Bison HD Webcam                          | 9         | 0.75%   |
| Apple FaceTime HD Camera (Built-in)      | 9         | 0.75%   |
| Acer BisonCam,NB Pro                     | 9         | 0.75%   |
| Logitech HD Pro Webcam C920              | 8         | 0.66%   |
| Chicony Integrated Camera (1280x720@30)  | 8         | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 7         | 0.58%   |
| Microdia Laptop_Integrated_Webcam_2M     | 7         | 0.58%   |
| Logitech C922 Pro Stream Webcam          | 7         | 0.58%   |
| Chicony USB2.0 VGA UVC WebCam            | 7         | 0.58%   |
| Chicony Integrated HP HD Webcam          | 7         | 0.58%   |
| Chicony HP TrueVision HD Camera          | 7         | 0.58%   |
| Sunplus Integrated_Webcam_HD             | 6         | 0.5%    |
| Sunplus FHD Camera Microphone            | 6         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 94        | 37.45%  |
| Validity Sensors                   | 85        | 33.86%  |
| Shenzhen Goodix Technology         | 25        | 9.96%   |
| AuthenTec                          | 15        | 5.98%   |
| LighTuning Technology              | 10        | 3.98%   |
| Upek                               | 8         | 3.19%   |
| STMicroelectronics                 | 7         | 2.79%   |
| Elan Microelectronics              | 4         | 1.59%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.8%    |
| DigitalPersona                     | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 11.55%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 10.76%  |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 4.78%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 3.98%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 3.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 3.19%   |
| Synaptics WBDI                                                             | 8         | 3.19%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 3.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.19%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 2.79%   |
| Synaptics  WBDI                                                            | 7         | 2.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.79%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.39%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.39%   |
| Validity Sensors VFS491                                                    | 5         | 1.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.99%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.99%   |
| AuthenTec AES2810                                                          | 5         | 1.99%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.59%   |
| Synaptics WBDI Device                                                      | 4         | 1.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.2%    |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.2%    |
| Synaptics UWP WBDI                                                         | 3         | 1.2%    |
| Synaptics TouchPad                                                         | 3         | 1.2%    |
| LighTuning Fingerprint Reader                                              | 3         | 1.2%    |
| Elan ELAN:ARM-M4                                                           | 3         | 1.2%    |
| AuthenTec AES1600                                                          | 3         | 1.2%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.8%    |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 2         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.8%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.4%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.4%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 69        | 33.01%  |
| Alcor Micro                       | 58        | 27.75%  |
| VASCO Data Security International | 23        | 11%     |
| Realtek Semiconductor             | 17        | 8.13%   |
| O2 Micro                          | 13        | 6.22%   |
| Lenovo                            | 11        | 5.26%   |
| Advanced Card Systems             | 5         | 2.39%   |
| OmniKey                           | 3         | 1.44%   |
| Upek                              | 2         | 0.96%   |
| Yubico.com                        | 1         | 0.48%   |
| SCM Microsystems                  | 1         | 0.48%   |
| Integrated Technology Express     | 1         | 0.48%   |
| Gemalto (was Gemplus)             | 1         | 0.48%   |
| Feitian Technologies              | 1         | 0.48%   |
| Clay Logic                        | 1         | 0.48%   |
| Chicony Electronics               | 1         | 0.48%   |
| Cherry                            | 1         | 0.48%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 56        | 26.79%  |
| Broadcom 58200                                                               | 26        | 12.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 8.61%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 17        | 8.13%   |
| Broadcom 5880                                                                | 16        | 7.66%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 13        | 6.22%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 5.26%   |
| VASCO Data Security International DIGIPASS 870                               | 10        | 4.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 4.78%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 4.31%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.44%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 0.96%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.96%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.96%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.48%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.48%   |
| OmniKey CardMan 4321                                                         | 1         | 0.48%   |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.48%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.48%   |
| Feitian Technologies SCR301                                                  | 1         | 0.48%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.48%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.48%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.48%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.48%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1299      | 64.5%   |
| 1     | 568       | 28.2%   |
| 2     | 112       | 5.56%   |
| 3     | 23        | 1.14%   |
| 4     | 7         | 0.35%   |
| 6     | 2         | 0.1%    |
| 5     | 2         | 0.1%    |
| 8     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 246       | 28.91%  |
| Graphics card            | 183       | 21.5%   |
| Chipcard                 | 143       | 16.8%   |
| Net/wireless             | 73        | 8.58%   |
| Multimedia controller    | 48        | 5.64%   |
| Communication controller | 27        | 3.17%   |
| Camera                   | 22        | 2.59%   |
| Card reader              | 20        | 2.35%   |
| Unassigned class         | 18        | 2.12%   |
| Bluetooth                | 18        | 2.12%   |
| Sound                    | 13        | 1.53%   |
| Storage                  | 12        | 1.41%   |
| Net/ethernet             | 11        | 1.29%   |
| Network                  | 6         | 0.71%   |
| Flash memory             | 4         | 0.47%   |
| Modem                    | 3         | 0.35%   |
| Dvb card                 | 2         | 0.24%   |
| Storage/raid             | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |

