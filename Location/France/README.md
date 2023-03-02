Linux in France - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in France.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/France/Desktop/README.md) and [notebooks](/Location/France/Notebook/README.md).

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

Total: 11913

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [a637650ff7](https://linux-hardware.org/?probe=a637650ff7) | Mar 01, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| MSI           | MAG B365M MORTAR            | Desktop     | [26f53549dd](https://linux-hardware.org/?probe=26f53549dd) | Feb 28, 2023 |
| Acer          | Aspire X3995                | Desktop     | [eccac5b752](https://linux-hardware.org/?probe=eccac5b752) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [17605a6808](https://linux-hardware.org/?probe=17605a6808) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [2b434f0b1d](https://linux-hardware.org/?probe=2b434f0b1d) | Feb 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [00cd14a724](https://linux-hardware.org/?probe=00cd14a724) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Timi          | TM1701                      | Notebook    | [ab658664bb](https://linux-hardware.org/?probe=ab658664bb) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [e338b721af](https://linux-hardware.org/?probe=e338b721af) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [0264556bba](https://linux-hardware.org/?probe=0264556bba) | Feb 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [371a95fb3d](https://linux-hardware.org/?probe=371a95fb3d) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S23... | Notebook    | [3cd99ed8f4](https://linux-hardware.org/?probe=3cd99ed8f4) | Feb 28, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [594ff7091b](https://linux-hardware.org/?probe=594ff7091b) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| HP            | 3047h                       | Desktop     | [db6be92c4f](https://linux-hardware.org/?probe=db6be92c4f) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [05d3c9f96c](https://linux-hardware.org/?probe=05d3c9f96c) | Feb 27, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [dd74cb518b](https://linux-hardware.org/?probe=dd74cb518b) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f70d3317a2](https://linux-hardware.org/?probe=f70d3317a2) | Feb 27, 2023 |
| Dell          | Latitude 5400               | Notebook    | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| HP            | Pavilion m6                 | Notebook    | [1e9d802ab6](https://linux-hardware.org/?probe=1e9d802ab6) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | Notebook    | [c49b50f583](https://linux-hardware.org/?probe=c49b50f583) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | Notebook    | [4083a9232f](https://linux-hardware.org/?probe=4083a9232f) | Feb 27, 2023 |
| HP            | Pavilion m6                 | Notebook    | [0d35b0b080](https://linux-hardware.org/?probe=0d35b0b080) | Feb 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [37d2aab670](https://linux-hardware.org/?probe=37d2aab670) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G50-80 80L0                 | Notebook    | [19727a16be](https://linux-hardware.org/?probe=19727a16be) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e763fc25e7](https://linux-hardware.org/?probe=e763fc25e7) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [4cd492ee3e](https://linux-hardware.org/?probe=4cd492ee3e) | Feb 26, 2023 |
| ASRock        | B85 Pro4                    | Desktop     | [0b4daba4fb](https://linux-hardware.org/?probe=0b4daba4fb) | Feb 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [ead0312777](https://linux-hardware.org/?probe=ead0312777) | Feb 26, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [3fe348fb3f](https://linux-hardware.org/?probe=3fe348fb3f) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Dell          | Latitude E5450              | Notebook    | [62ce48db27](https://linux-hardware.org/?probe=62ce48db27) | Feb 26, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | Notebook    | [d0b043c11b](https://linux-hardware.org/?probe=d0b043c11b) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9471b0f763](https://linux-hardware.org/?probe=9471b0f763) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [08d12e1049](https://linux-hardware.org/?probe=08d12e1049) | Feb 26, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [5634c4795c](https://linux-hardware.org/?probe=5634c4795c) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | ENVY 17                     | Notebook    | [dea1551bf3](https://linux-hardware.org/?probe=dea1551bf3) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [1b7321e88d](https://linux-hardware.org/?probe=1b7321e88d) | Feb 26, 2023 |
| HP            | ENVY 17                     | Notebook    | [0f347a1b6c](https://linux-hardware.org/?probe=0f347a1b6c) | Feb 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [887241ec59](https://linux-hardware.org/?probe=887241ec59) | Feb 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [724039adf2](https://linux-hardware.org/?probe=724039adf2) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | 3398                        | Desktop     | [5e7ae4c866](https://linux-hardware.org/?probe=5e7ae4c866) | Feb 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3142c6a90c](https://linux-hardware.org/?probe=3142c6a90c) | Feb 25, 2023 |
| HP            | 18E7                        | Desktop     | [7b52dfac52](https://linux-hardware.org/?probe=7b52dfac52) | Feb 25, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9894743527](https://linux-hardware.org/?probe=9894743527) | Feb 25, 2023 |
| HP            | 3047h                       | Desktop     | [8f7d5acf1f](https://linux-hardware.org/?probe=8f7d5acf1f) | Feb 25, 2023 |
| Dell          | XPS 9315                    | Notebook    | [86fea0e08a](https://linux-hardware.org/?probe=86fea0e08a) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [c99ef001e4](https://linux-hardware.org/?probe=c99ef001e4) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [7089ab33b3](https://linux-hardware.org/?probe=7089ab33b3) | Feb 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [15cf7c7cd7](https://linux-hardware.org/?probe=15cf7c7cd7) | Feb 24, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [4d45d5880b](https://linux-hardware.org/?probe=4d45d5880b) | Feb 23, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| T-bao         | MINI PC                     | Desktop     | [68ba9fc610](https://linux-hardware.org/?probe=68ba9fc610) | Feb 23, 2023 |
| Packard Be... | ONETWO L5700                | All in one  | [6ec6a6661d](https://linux-hardware.org/?probe=6ec6a6661d) | Feb 22, 2023 |
| HP            | Spectre                     | Convertible | [2366c11489](https://linux-hardware.org/?probe=2366c11489) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [8fde9cab5c](https://linux-hardware.org/?probe=8fde9cab5c) | Feb 22, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ce8874cff4](https://linux-hardware.org/?probe=ce8874cff4) | Feb 22, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [2b16b06c7f](https://linux-hardware.org/?probe=2b16b06c7f) | Feb 22, 2023 |
| AZW           | U59                         | Desktop     | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [51b83f1e27](https://linux-hardware.org/?probe=51b83f1e27) | Feb 22, 2023 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [2dffc350dd](https://linux-hardware.org/?probe=2dffc350dd) | Feb 22, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [40205862f6](https://linux-hardware.org/?probe=40205862f6) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Foxconn       | Lucknow                     | Desktop     | [3ca9a4f66e](https://linux-hardware.org/?probe=3ca9a4f66e) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| Notebook      | N8xEJEK                     | Notebook    | [1548ea7cab](https://linux-hardware.org/?probe=1548ea7cab) | Feb 21, 2023 |
| Notebook      | N8xEJEK                     | Notebook    | [a8a28d6f2b](https://linux-hardware.org/?probe=a8a28d6f2b) | Feb 21, 2023 |
| ASUSTek       | X55VD                       | Notebook    | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9978852d07](https://linux-hardware.org/?probe=9978852d07) | Feb 21, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [4fc47f45be](https://linux-hardware.org/?probe=4fc47f45be) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | Desktop     | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| Dell          | Vostro 15 7510              | Notebook    | [df764baed8](https://linux-hardware.org/?probe=df764baed8) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9aee694156](https://linux-hardware.org/?probe=9aee694156) | Feb 21, 2023 |
| ASUSTek       | K70IC                       | Notebook    | [e5aad61a1b](https://linux-hardware.org/?probe=e5aad61a1b) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| ASUSTek       | UX410UQK                    | Notebook    | [0a23974b1b](https://linux-hardware.org/?probe=0a23974b1b) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [082f5559c7](https://linux-hardware.org/?probe=082f5559c7) | Feb 20, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [e26b379150](https://linux-hardware.org/?probe=e26b379150) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | Desktop     | [2a403bdb2b](https://linux-hardware.org/?probe=2a403bdb2b) | Feb 20, 2023 |
| Gigabyte      | 945P-S3                     | Desktop     | [2cdcb107ab](https://linux-hardware.org/?probe=2cdcb107ab) | Feb 20, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [53ba72d592](https://linux-hardware.org/?probe=53ba72d592) | Feb 20, 2023 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [32b47345a6](https://linux-hardware.org/?probe=32b47345a6) | Feb 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [a5124a64e6](https://linux-hardware.org/?probe=a5124a64e6) | Feb 19, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [7e45218236](https://linux-hardware.org/?probe=7e45218236) | Feb 19, 2023 |
| HP            | 2B56                        | All in one  | [25c4d7a993](https://linux-hardware.org/?probe=25c4d7a993) | Feb 19, 2023 |
| ASUSTek       | G10AC                       | Desktop     | [8a367bb885](https://linux-hardware.org/?probe=8a367bb885) | Feb 19, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [b999af6719](https://linux-hardware.org/?probe=b999af6719) | Feb 19, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [54807bcb6c](https://linux-hardware.org/?probe=54807bcb6c) | Feb 18, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [24e71c037b](https://linux-hardware.org/?probe=24e71c037b) | Feb 18, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| Sony          | VGN-NW21MF_W                | Notebook    | [e46cfcff64](https://linux-hardware.org/?probe=e46cfcff64) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| IP3 Tech      | Cherry Trail CR             | Desktop     | [0ff2dc2202](https://linux-hardware.org/?probe=0ff2dc2202) | Feb 17, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [8da7f7cbdc](https://linux-hardware.org/?probe=8da7f7cbdc) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [4a3d5fee69](https://linux-hardware.org/?probe=4a3d5fee69) | Feb 17, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | Notebook    | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [7c5f2f584e](https://linux-hardware.org/?probe=7c5f2f584e) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53055b0d6e](https://linux-hardware.org/?probe=53055b0d6e) | Feb 16, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [078d55d158](https://linux-hardware.org/?probe=078d55d158) | Feb 16, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| MSI           | H61M-E33                    | Desktop     | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| Dell          | Precision 5570              | Notebook    | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Shenzhen W... | AERO 3                      | Mini pc     | [6c8324859d](https://linux-hardware.org/?probe=6c8324859d) | Feb 16, 2023 |
| Dell          | Latitude 7330               | Notebook    | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [a9e4d33e06](https://linux-hardware.org/?probe=a9e4d33e06) | Feb 16, 2023 |
| Dell          | Precision 5750              | Notebook    | [7b814aee7c](https://linux-hardware.org/?probe=7b814aee7c) | Feb 16, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [676c244c1d](https://linux-hardware.org/?probe=676c244c1d) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| Dell          | Inspiron 7405 2n1           | Convertible | [3041828966](https://linux-hardware.org/?probe=3041828966) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| Dell          | Precision 5570              | Notebook    | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| Shenzhen W... | AERO 3                      | Mini pc     | [9cbb805c11](https://linux-hardware.org/?probe=9cbb805c11) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Supermicro    | X7DCL                       | Desktop     | [49e545591c](https://linux-hardware.org/?probe=49e545591c) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e1d323e96f](https://linux-hardware.org/?probe=e1d323e96f) | Feb 15, 2023 |
| ASUSTek       | PRIME Z590-V                | Desktop     | [4d00371a70](https://linux-hardware.org/?probe=4d00371a70) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [b9301138cc](https://linux-hardware.org/?probe=b9301138cc) | Feb 14, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [542f27e209](https://linux-hardware.org/?probe=542f27e209) | Feb 14, 2023 |
| HP            | 805D                        | Desktop     | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5d2153f4f2](https://linux-hardware.org/?probe=5d2153f4f2) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS4AN00    | Notebook    | [ec8fbb6350](https://linux-hardware.org/?probe=ec8fbb6350) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| Lenovo        | 30BE SDK0K17763 WIN 1801... | Desktop     | [837c0bcb6a](https://linux-hardware.org/?probe=837c0bcb6a) | Feb 14, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [2914a1866d](https://linux-hardware.org/?probe=2914a1866d) | Feb 14, 2023 |
| Google        | Lulu                        | Notebook    | [15fa093522](https://linux-hardware.org/?probe=15fa093522) | Feb 14, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4ccd4c2da2](https://linux-hardware.org/?probe=4ccd4c2da2) | Feb 14, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Thomson       | N17V3C4WH128                | Notebook    | [57eacd1a37](https://linux-hardware.org/?probe=57eacd1a37) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [6cf7a75c9e](https://linux-hardware.org/?probe=6cf7a75c9e) | Feb 13, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [36bf8af789](https://linux-hardware.org/?probe=36bf8af789) | Feb 13, 2023 |
| MSI           | MS-B9181                    | Desktop     | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Dell          | Latitude E6320              | Notebook    | [32ad32fb45](https://linux-hardware.org/?probe=32ad32fb45) | Feb 13, 2023 |
| ASRock        | E350M1                      | Desktop     | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5b93510482](https://linux-hardware.org/?probe=5b93510482) | Feb 13, 2023 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [24d20958ab](https://linux-hardware.org/?probe=24d20958ab) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [2032f6e202](https://linux-hardware.org/?probe=2032f6e202) | Feb 13, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [eec95070bb](https://linux-hardware.org/?probe=eec95070bb) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| ASUSTek       | G771JM                      | Notebook    | [af72d8c72f](https://linux-hardware.org/?probe=af72d8c72f) | Feb 12, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [7d57fccbf0](https://linux-hardware.org/?probe=7d57fccbf0) | Feb 12, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [68db95ee9b](https://linux-hardware.org/?probe=68db95ee9b) | Feb 12, 2023 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [3a16a28774](https://linux-hardware.org/?probe=3a16a28774) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a74e071a54](https://linux-hardware.org/?probe=a74e071a54) | Feb 12, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [861c0d497e](https://linux-hardware.org/?probe=861c0d497e) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| Acer          | Aspire E5-574G              | Notebook    | [cdbd2ad757](https://linux-hardware.org/?probe=cdbd2ad757) | Feb 12, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [121fcf8fd6](https://linux-hardware.org/?probe=121fcf8fd6) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [9e28099913](https://linux-hardware.org/?probe=9e28099913) | Feb 11, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [350850e668](https://linux-hardware.org/?probe=350850e668) | Feb 11, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [523c719e5b](https://linux-hardware.org/?probe=523c719e5b) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [d4e29128dd](https://linux-hardware.org/?probe=d4e29128dd) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7001PF... | Notebook    | [f6d2fc27d1](https://linux-hardware.org/?probe=f6d2fc27d1) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | Notebook    | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [d9707b086e](https://linux-hardware.org/?probe=d9707b086e) | Feb 10, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [200c5bc81b](https://linux-hardware.org/?probe=200c5bc81b) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | Notebook    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [9da08e5265](https://linux-hardware.org/?probe=9da08e5265) | Feb 10, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [df85a15b13](https://linux-hardware.org/?probe=df85a15b13) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [756bc1fc3b](https://linux-hardware.org/?probe=756bc1fc3b) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [769b226f8e](https://linux-hardware.org/?probe=769b226f8e) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | Notebook    | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [077853b2db](https://linux-hardware.org/?probe=077853b2db) | Feb 09, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [57a1d5072b](https://linux-hardware.org/?probe=57a1d5072b) | Feb 09, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [fca49121d5](https://linux-hardware.org/?probe=fca49121d5) | Feb 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1f4b88ad7f](https://linux-hardware.org/?probe=1f4b88ad7f) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a77dd320a8](https://linux-hardware.org/?probe=a77dd320a8) | Feb 09, 2023 |
| Dell          | Precision 5570              | Notebook    | [52cd3af211](https://linux-hardware.org/?probe=52cd3af211) | Feb 09, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [546ea7c2e8](https://linux-hardware.org/?probe=546ea7c2e8) | Feb 09, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [77dafc35f5](https://linux-hardware.org/?probe=77dafc35f5) | Feb 09, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [afaaed1c36](https://linux-hardware.org/?probe=afaaed1c36) | Feb 09, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9d947022b0](https://linux-hardware.org/?probe=9d947022b0) | Feb 09, 2023 |
| Lenovo        | ThinkPad L512 2550WC7       | Notebook    | [8b8efe2813](https://linux-hardware.org/?probe=8b8efe2813) | Feb 09, 2023 |
| Dell          | Precision M6500             | Notebook    | [dcabcd8d63](https://linux-hardware.org/?probe=dcabcd8d63) | Feb 09, 2023 |
| Sony          | VGN-NS38E_S                 | Notebook    | [891c180950](https://linux-hardware.org/?probe=891c180950) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [cc92542e21](https://linux-hardware.org/?probe=cc92542e21) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Intel         | NUC5i3RYB H41000-506        | Mini pc     | [afe1fd72e6](https://linux-hardware.org/?probe=afe1fd72e6) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Dell          | 0NC2VH A01                  | Desktop     | [85ab2e4223](https://linux-hardware.org/?probe=85ab2e4223) | Feb 08, 2023 |
| EXTRA Comp... | A9100                       | Notebook    | [67278c37d9](https://linux-hardware.org/?probe=67278c37d9) | Feb 08, 2023 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [fcd6a27cd6](https://linux-hardware.org/?probe=fcd6a27cd6) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [190d8c3b40](https://linux-hardware.org/?probe=190d8c3b40) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [b07e05a4ed](https://linux-hardware.org/?probe=b07e05a4ed) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [c01a8b01f0](https://linux-hardware.org/?probe=c01a8b01f0) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [b7fb43ba75](https://linux-hardware.org/?probe=b7fb43ba75) | Feb 07, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [22ba7d722f](https://linux-hardware.org/?probe=22ba7d722f) | Feb 07, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [b4cafb34f7](https://linux-hardware.org/?probe=b4cafb34f7) | Feb 07, 2023 |
| HP            | Pavilion 17                 | Notebook    | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Dell          | Precision 5570              | Notebook    | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [cd59ace4d1](https://linux-hardware.org/?probe=cd59ace4d1) | Feb 07, 2023 |
| Toshiba       | Satellite C870-196          | Notebook    | [85ded7d8d0](https://linux-hardware.org/?probe=85ded7d8d0) | Feb 06, 2023 |
| ASUSTek       | K72JT                       | Notebook    | [9620d41f62](https://linux-hardware.org/?probe=9620d41f62) | Feb 06, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b666459988](https://linux-hardware.org/?probe=b666459988) | Feb 06, 2023 |
| Dell          | Inspiron 7791 2n1           | Convertible | [dee03d9aff](https://linux-hardware.org/?probe=dee03d9aff) | Feb 06, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [02260ca8b3](https://linux-hardware.org/?probe=02260ca8b3) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
| Dell          | 06JWJY A00                  | Desktop     | [9745edaf8e](https://linux-hardware.org/?probe=9745edaf8e) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [6519e2ca2f](https://linux-hardware.org/?probe=6519e2ca2f) | Feb 06, 2023 |
| Dell          | Latitude 5520               | Notebook    | [e9782f4262](https://linux-hardware.org/?probe=e9782f4262) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | Notebook    | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [9a05c88c59](https://linux-hardware.org/?probe=9a05c88c59) | Feb 06, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [0bd327136a](https://linux-hardware.org/?probe=0bd327136a) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | Notebook    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [6217fdc070](https://linux-hardware.org/?probe=6217fdc070) | Feb 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2891f201f0](https://linux-hardware.org/?probe=2891f201f0) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| HP            | 0A64h                       | Desktop     | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [6dd8a1b58a](https://linux-hardware.org/?probe=6dd8a1b58a) | Feb 05, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [b8675ca2ee](https://linux-hardware.org/?probe=b8675ca2ee) | Feb 05, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [bc0593280c](https://linux-hardware.org/?probe=bc0593280c) | Feb 05, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [99dc5ad30d](https://linux-hardware.org/?probe=99dc5ad30d) | Feb 05, 2023 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [6e00c72683](https://linux-hardware.org/?probe=6e00c72683) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| ASUSTek       | P5V-VM DH                   | Desktop     | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [d2981f72e6](https://linux-hardware.org/?probe=d2981f72e6) | Feb 05, 2023 |
| Sony          | VPCEH1E1E                   | Notebook    | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Google        | Rabbid                      | Notebook    | [e309afd2d9](https://linux-hardware.org/?probe=e309afd2d9) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | Desktop     | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| HP            | 3396                        | Desktop     | [96a3376aa0](https://linux-hardware.org/?probe=96a3376aa0) | Feb 05, 2023 |
| Sony          | VGN-Z31MN_B                 | Notebook    | [bfb9a55ce9](https://linux-hardware.org/?probe=bfb9a55ce9) | Feb 05, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [e409f042e2](https://linux-hardware.org/?probe=e409f042e2) | Feb 05, 2023 |
| Google        | Rabbid                      | Notebook    | [3afddd7ab1](https://linux-hardware.org/?probe=3afddd7ab1) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | Desktop     | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F5S65B0J    | Notebook    | [cca484a94e](https://linux-hardware.org/?probe=cca484a94e) | Feb 04, 2023 |
| ASUSTek       | Basswood                    | Desktop     | [7de223a121](https://linux-hardware.org/?probe=7de223a121) | Feb 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a3cab7679b](https://linux-hardware.org/?probe=a3cab7679b) | Feb 04, 2023 |
| ASUSTek       | UX331UA                     | Notebook    | [4b5a781cb4](https://linux-hardware.org/?probe=4b5a781cb4) | Feb 04, 2023 |
| HP            | 1589                        | Desktop     | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [e12e1d2598](https://linux-hardware.org/?probe=e12e1d2598) | Feb 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [9765b77a43](https://linux-hardware.org/?probe=9765b77a43) | Feb 04, 2023 |
| Dell          | Precision 5570              | Notebook    | [11d65e48fa](https://linux-hardware.org/?probe=11d65e48fa) | Feb 04, 2023 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8b60b63594](https://linux-hardware.org/?probe=8b60b63594) | Feb 04, 2023 |
| Dell          | Precision 5570              | Notebook    | [5378f40d0d](https://linux-hardware.org/?probe=5378f40d0d) | Feb 04, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Intel         | D33217GKE G76540-203        | Desktop     | [0f43f169d1](https://linux-hardware.org/?probe=0f43f169d1) | Feb 03, 2023 |
| Dell          | G3 3500                     | Notebook    | [a25e0c9862](https://linux-hardware.org/?probe=a25e0c9862) | Feb 03, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [49d8a19239](https://linux-hardware.org/?probe=49d8a19239) | Feb 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [001a819e3d](https://linux-hardware.org/?probe=001a819e3d) | Feb 03, 2023 |
| HP            | Laptop 14s-fq2xxx           | Notebook    | [f63797ea26](https://linux-hardware.org/?probe=f63797ea26) | Feb 03, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | Notebook    | [cc7e8a75d3](https://linux-hardware.org/?probe=cc7e8a75d3) | Feb 03, 2023 |
| Dell          | 05WNJ2 A02                  | Desktop     | [4619f572c5](https://linux-hardware.org/?probe=4619f572c5) | Feb 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [9b453ade5b](https://linux-hardware.org/?probe=9b453ade5b) | Feb 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [2d0b0d4330](https://linux-hardware.org/?probe=2d0b0d4330) | Feb 02, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [795ee67158](https://linux-hardware.org/?probe=795ee67158) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [1fddf279a5](https://linux-hardware.org/?probe=1fddf279a5) | Feb 02, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [b35d6e3a08](https://linux-hardware.org/?probe=b35d6e3a08) | Feb 02, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [cc717bffbe](https://linux-hardware.org/?probe=cc717bffbe) | Feb 02, 2023 |
| Dell          | 0HFG24 A02                  | Server      | [a05562bc52](https://linux-hardware.org/?probe=a05562bc52) | Feb 02, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5ee874041a](https://linux-hardware.org/?probe=5ee874041a) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | Notebook    | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| ASUSTek       | K8N-DL                      | Desktop     | [dde5c844f2](https://linux-hardware.org/?probe=dde5c844f2) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [e477495ef6](https://linux-hardware.org/?probe=e477495ef6) | Feb 01, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [61da73a065](https://linux-hardware.org/?probe=61da73a065) | Feb 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4644d239d7](https://linux-hardware.org/?probe=4644d239d7) | Feb 01, 2023 |
| Lenovo        | ThinkPad T400 6473PMG       | Notebook    | [07cba1c44b](https://linux-hardware.org/?probe=07cba1c44b) | Feb 01, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [f7a88d0dea](https://linux-hardware.org/?probe=f7a88d0dea) | Feb 01, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [b7361dbc53](https://linux-hardware.org/?probe=b7361dbc53) | Feb 01, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [81b19ff917](https://linux-hardware.org/?probe=81b19ff917) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | Notebook    | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| Lenovo        | 3181 NO DPK                 | Mini pc     | [d4c01d094b](https://linux-hardware.org/?probe=d4c01d094b) | Feb 01, 2023 |
| Dell          | 02P9X9 A04                  | Server      | [bda0eb6835](https://linux-hardware.org/?probe=bda0eb6835) | Feb 01, 2023 |
| HP            | Notebook                    | Notebook    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Dell          | G3 3500                     | Notebook    | [4b519ab8a8](https://linux-hardware.org/?probe=4b519ab8a8) | Jan 31, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [463b7f859f](https://linux-hardware.org/?probe=463b7f859f) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [05a6fd1857](https://linux-hardware.org/?probe=05a6fd1857) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [9ce51b923e](https://linux-hardware.org/?probe=9ce51b923e) | Jan 31, 2023 |
| Dell          | Latitude 7410               | Notebook    | [fd07971a70](https://linux-hardware.org/?probe=fd07971a70) | Jan 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [01c7dbecde](https://linux-hardware.org/?probe=01c7dbecde) | Jan 31, 2023 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [0b0b0a2686](https://linux-hardware.org/?probe=0b0b0a2686) | Jan 31, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [37999411ed](https://linux-hardware.org/?probe=37999411ed) | Jan 31, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [60967eaaaf](https://linux-hardware.org/?probe=60967eaaaf) | Jan 31, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | Notebook    | [1086813401](https://linux-hardware.org/?probe=1086813401) | Jan 30, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | Notebook    | [0b43f40c2a](https://linux-hardware.org/?probe=0b43f40c2a) | Jan 30, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [532f5a8dbe](https://linux-hardware.org/?probe=532f5a8dbe) | Jan 30, 2023 |
| Dell          | 0TP412                      | Desktop     | [5db177340d](https://linux-hardware.org/?probe=5db177340d) | Jan 30, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [7bc39da7c1](https://linux-hardware.org/?probe=7bc39da7c1) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | Notebook    | [970a402846](https://linux-hardware.org/?probe=970a402846) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | Notebook    | [c2d425d254](https://linux-hardware.org/?probe=c2d425d254) | Jan 30, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [529b411b46](https://linux-hardware.org/?probe=529b411b46) | Jan 30, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | Desktop     | [b7917146d8](https://linux-hardware.org/?probe=b7917146d8) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7983249b4c](https://linux-hardware.org/?probe=7983249b4c) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Dell          | Latitude 7390               | Notebook    | [b154892be4](https://linux-hardware.org/?probe=b154892be4) | Jan 30, 2023 |
| HP            | ENVY Laptop 13-ah1xxx       | Notebook    | [360756b46a](https://linux-hardware.org/?probe=360756b46a) | Jan 30, 2023 |
| HP            | 0A64h                       | Desktop     | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4fb612b680](https://linux-hardware.org/?probe=4fb612b680) | Jan 29, 2023 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [ff186606cd](https://linux-hardware.org/?probe=ff186606cd) | Jan 29, 2023 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [d4f05f2d34](https://linux-hardware.org/?probe=d4f05f2d34) | Jan 29, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [cac5b8faa5](https://linux-hardware.org/?probe=cac5b8faa5) | Jan 29, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [4b1e1bc7e1](https://linux-hardware.org/?probe=4b1e1bc7e1) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| MSI           | CR700                       | Notebook    | [35d1ff1eac](https://linux-hardware.org/?probe=35d1ff1eac) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [90644628b4](https://linux-hardware.org/?probe=90644628b4) | Jan 29, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [b9a38b7494](https://linux-hardware.org/?probe=b9a38b7494) | Jan 29, 2023 |
| Dell          | 0F8098                      | Desktop     | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| ASUSTek       | X550LB                      | Notebook    | [9590dd2f30](https://linux-hardware.org/?probe=9590dd2f30) | Jan 28, 2023 |
| Dell          | Latitude 7280               | Notebook    | [358f4c431f](https://linux-hardware.org/?probe=358f4c431f) | Jan 28, 2023 |
| Dell          | Latitude 7280               | Notebook    | [903e0489c4](https://linux-hardware.org/?probe=903e0489c4) | Jan 28, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6e55ab69b8](https://linux-hardware.org/?probe=6e55ab69b8) | Jan 28, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [c7fc79b5f1](https://linux-hardware.org/?probe=c7fc79b5f1) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | Notebook    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| MSI           | H410M PRO                   | Desktop     | [d8c1dc4e25](https://linux-hardware.org/?probe=d8c1dc4e25) | Jan 28, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [4e17616aaf](https://linux-hardware.org/?probe=4e17616aaf) | Jan 28, 2023 |
| MSI           | H410M PRO                   | Desktop     | [72f5a735fb](https://linux-hardware.org/?probe=72f5a735fb) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [be17d6fd70](https://linux-hardware.org/?probe=be17d6fd70) | Jan 27, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [e9d671848c](https://linux-hardware.org/?probe=e9d671848c) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| ASUSTek       | K73E                        | Notebook    | [66e0036452](https://linux-hardware.org/?probe=66e0036452) | Jan 27, 2023 |
| ASUSTek       | K73E                        | Notebook    | [91f049a01d](https://linux-hardware.org/?probe=91f049a01d) | Jan 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| Acer          | Aspire X1700                | Desktop     | [beab94f1ee](https://linux-hardware.org/?probe=beab94f1ee) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [117d80ff4d](https://linux-hardware.org/?probe=117d80ff4d) | Jan 27, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [6aa78b855a](https://linux-hardware.org/?probe=6aa78b855a) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| HP            | 805D                        | Desktop     | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [b1371b8883](https://linux-hardware.org/?probe=b1371b8883) | Jan 26, 2023 |
| HP            | 625                         | Notebook    | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Gigabyte      | EX38-DS4                    | Desktop     | [4d5b828cfc](https://linux-hardware.org/?probe=4d5b828cfc) | Jan 25, 2023 |
| HP            | 1495                        | Desktop     | [d600418bf6](https://linux-hardware.org/?probe=d600418bf6) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Intel         | B75                         | Desktop     | [20853a8c8d](https://linux-hardware.org/?probe=20853a8c8d) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [7996de313e](https://linux-hardware.org/?probe=7996de313e) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [3f4e15d14a](https://linux-hardware.org/?probe=3f4e15d14a) | Jan 25, 2023 |
| MSI           | H110M GAMING                | Desktop     | [2622dcb32e](https://linux-hardware.org/?probe=2622dcb32e) | Jan 25, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [fc7e90e419](https://linux-hardware.org/?probe=fc7e90e419) | Jan 25, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [d08118920b](https://linux-hardware.org/?probe=d08118920b) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [148b797f1a](https://linux-hardware.org/?probe=148b797f1a) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| ASUSTek       | X301A1                      | Notebook    | [f9ea8894f0](https://linux-hardware.org/?probe=f9ea8894f0) | Jan 25, 2023 |
| Sony          | VGN-NW21MF_W                | Notebook    | [dd4ac0a026](https://linux-hardware.org/?probe=dd4ac0a026) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [41c91fdc7b](https://linux-hardware.org/?probe=41c91fdc7b) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [199569e288](https://linux-hardware.org/?probe=199569e288) | Jan 24, 2023 |
| HP            | ProBook 6570b               | Notebook    | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [f57750e125](https://linux-hardware.org/?probe=f57750e125) | Jan 24, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1c843535db](https://linux-hardware.org/?probe=1c843535db) | Jan 24, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [da95f58140](https://linux-hardware.org/?probe=da95f58140) | Jan 23, 2023 |
| Dell          | Precision 3551              | Notebook    | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| MSI           | Stealth GS66 12UH           | Notebook    | [9e79dca70b](https://linux-hardware.org/?probe=9e79dca70b) | Jan 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [8b280b4152](https://linux-hardware.org/?probe=8b280b4152) | Jan 23, 2023 |
| Dell          | Inspiron 7537               | Notebook    | [9181895f24](https://linux-hardware.org/?probe=9181895f24) | Jan 23, 2023 |
| Dell          | Latitude E4310              | Notebook    | [c32e006e62](https://linux-hardware.org/?probe=c32e006e62) | Jan 23, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [b80dda96de](https://linux-hardware.org/?probe=b80dda96de) | Jan 23, 2023 |
| Dell          | Latitude E4310              | Notebook    | [5045d5e911](https://linux-hardware.org/?probe=5045d5e911) | Jan 23, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [e0da886a95](https://linux-hardware.org/?probe=e0da886a95) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad X200 7458VL3       | Notebook    | [3a91fa2c72](https://linux-hardware.org/?probe=3a91fa2c72) | Jan 23, 2023 |
| MSI           | MS-7388                     | Desktop     | [4d5146a81f](https://linux-hardware.org/?probe=4d5146a81f) | Jan 22, 2023 |
| MSI           | PX60 6QE                    | Notebook    | [d820232c9c](https://linux-hardware.org/?probe=d820232c9c) | Jan 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [30b3f2f346](https://linux-hardware.org/?probe=30b3f2f346) | Jan 22, 2023 |
| HP            | ProBook 4330s               | Notebook    | [f96c2452d3](https://linux-hardware.org/?probe=f96c2452d3) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | Notebook    | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Dell          | Latitude E5470              | Notebook    | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| HP            | 625                         | Notebook    | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [893ebdd842](https://linux-hardware.org/?probe=893ebdd842) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | Notebook    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [8cb76e0d6d](https://linux-hardware.org/?probe=8cb76e0d6d) | Jan 22, 2023 |
| Dell          | G15 5510                    | Notebook    | [7cee6347e3](https://linux-hardware.org/?probe=7cee6347e3) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [dfb621ce10](https://linux-hardware.org/?probe=dfb621ce10) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [e1d7b236d3](https://linux-hardware.org/?probe=e1d7b236d3) | Jan 22, 2023 |
| Danew         | Dbook 131                   | Notebook    | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [941c11250c](https://linux-hardware.org/?probe=941c11250c) | Jan 21, 2023 |
| HP            | 625                         | Notebook    | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [9a0a65b69a](https://linux-hardware.org/?probe=9a0a65b69a) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| Dell          | G7 7700                     | Notebook    | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [f6f1f5e32b](https://linux-hardware.org/?probe=f6f1f5e32b) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B560M-E          | Desktop     | [0bbafaf9fe](https://linux-hardware.org/?probe=0bbafaf9fe) | Jan 21, 2023 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [5b41a33a67](https://linux-hardware.org/?probe=5b41a33a67) | Jan 21, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [0f3a750cdc](https://linux-hardware.org/?probe=0f3a750cdc) | Jan 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [22b030cc5c](https://linux-hardware.org/?probe=22b030cc5c) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [69bf20ee28](https://linux-hardware.org/?probe=69bf20ee28) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [dfd88e113a](https://linux-hardware.org/?probe=dfd88e113a) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | Notebook    | [5b271fa3eb](https://linux-hardware.org/?probe=5b271fa3eb) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | Notebook    | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [6134837cfe](https://linux-hardware.org/?probe=6134837cfe) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3525b1f86](https://linux-hardware.org/?probe=e3525b1f86) | Jan 21, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| MSI           | CR650                       | Notebook    | [3d3a46f5c6](https://linux-hardware.org/?probe=3d3a46f5c6) | Jan 20, 2023 |
| MSI           | CR650                       | Notebook    | [7d3b1f25c4](https://linux-hardware.org/?probe=7d3b1f25c4) | Jan 20, 2023 |
| ASRock        | A520M-HDVP/DASH             | Desktop     | [72421e0506](https://linux-hardware.org/?probe=72421e0506) | Jan 20, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Latitude 7410               | Notebook    | [488f794ad5](https://linux-hardware.org/?probe=488f794ad5) | Jan 20, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [91dea34a76](https://linux-hardware.org/?probe=91dea34a76) | Jan 20, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [3041b852df](https://linux-hardware.org/?probe=3041b852df) | Jan 20, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [08502cda27](https://linux-hardware.org/?probe=08502cda27) | Jan 20, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [beaa2fdddb](https://linux-hardware.org/?probe=beaa2fdddb) | Jan 20, 2023 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | Desktop     | [bb1826bf63](https://linux-hardware.org/?probe=bb1826bf63) | Jan 20, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ccf1934924](https://linux-hardware.org/?probe=ccf1934924) | Jan 20, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [110d9cb0f9](https://linux-hardware.org/?probe=110d9cb0f9) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [105b2daa8e](https://linux-hardware.org/?probe=105b2daa8e) | Jan 20, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [57a7b7d914](https://linux-hardware.org/?probe=57a7b7d914) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| Dell          | Precision 3551              | Notebook    | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c08f2e5961](https://linux-hardware.org/?probe=c08f2e5961) | Jan 19, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [6f50700657](https://linux-hardware.org/?probe=6f50700657) | Jan 19, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b7f8407c8f](https://linux-hardware.org/?probe=b7f8407c8f) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [e000402b1c](https://linux-hardware.org/?probe=e000402b1c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [ae0457cc50](https://linux-hardware.org/?probe=ae0457cc50) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [79e6461b99](https://linux-hardware.org/?probe=79e6461b99) | Jan 19, 2023 |
| Toshiba       | Satellite C70-A             | Notebook    | [ffaa715bdd](https://linux-hardware.org/?probe=ffaa715bdd) | Jan 19, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [9c0b3ef63b](https://linux-hardware.org/?probe=9c0b3ef63b) | Jan 19, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | Notebook    | [39f2ca64d4](https://linux-hardware.org/?probe=39f2ca64d4) | Jan 19, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [d2ecbd7302](https://linux-hardware.org/?probe=d2ecbd7302) | Jan 18, 2023 |
| Dell          | Vostro 1720                 | Notebook    | [1d06cb4ad8](https://linux-hardware.org/?probe=1d06cb4ad8) | Jan 18, 2023 |
| ASUSTek       | UX32VD                      | Notebook    | [7851952137](https://linux-hardware.org/?probe=7851952137) | Jan 18, 2023 |
| ASUSTek       | X411UN                      | Notebook    | [fad0f7ce44](https://linux-hardware.org/?probe=fad0f7ce44) | Jan 18, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [3dba9611d3](https://linux-hardware.org/?probe=3dba9611d3) | Jan 18, 2023 |
| Gigabyte      | P15FV5                      | Notebook    | [5a03ba32c0](https://linux-hardware.org/?probe=5a03ba32c0) | Jan 18, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [04d0c02d29](https://linux-hardware.org/?probe=04d0c02d29) | Jan 18, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [8e511beda6](https://linux-hardware.org/?probe=8e511beda6) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| Dell          | Inspiron 7537               | Notebook    | [95cc108754](https://linux-hardware.org/?probe=95cc108754) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [f7efc3545d](https://linux-hardware.org/?probe=f7efc3545d) | Jan 18, 2023 |
| MSI           | H310M PRO-M2                | Desktop     | [6bdc0bc1c7](https://linux-hardware.org/?probe=6bdc0bc1c7) | Jan 17, 2023 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [b1caf1d323](https://linux-hardware.org/?probe=b1caf1d323) | Jan 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Toshiba       | Satellite L655D             | Notebook    | [38b26485d3](https://linux-hardware.org/?probe=38b26485d3) | Jan 17, 2023 |
| Lenovo        | ThinkPad T61 766112G        | Notebook    | [fb772cc0cf](https://linux-hardware.org/?probe=fb772cc0cf) | Jan 17, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ad9172f4a9](https://linux-hardware.org/?probe=ad9172f4a9) | Jan 17, 2023 |
| Dell          | Latitude E5540              | Notebook    | [e8e30eb563](https://linux-hardware.org/?probe=e8e30eb563) | Jan 17, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5a0f8a7ea6](https://linux-hardware.org/?probe=5a0f8a7ea6) | Jan 17, 2023 |
| Dell          | Vostro 1720                 | Notebook    | [d02dee9ab2](https://linux-hardware.org/?probe=d02dee9ab2) | Jan 17, 2023 |
| Dell          | Inspiron 14 5418            | Notebook    | [e3bfdaa6a4](https://linux-hardware.org/?probe=e3bfdaa6a4) | Jan 17, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [851c4f03fc](https://linux-hardware.org/?probe=851c4f03fc) | Jan 17, 2023 |
| Dell          | Latitude 5410               | Notebook    | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| MSI           | GP70 2OD                    | Notebook    | [7405037963](https://linux-hardware.org/?probe=7405037963) | Jan 17, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [6c3aa30aa8](https://linux-hardware.org/?probe=6c3aa30aa8) | Jan 17, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [d501532972](https://linux-hardware.org/?probe=d501532972) | Jan 17, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [68ae2ab1d0](https://linux-hardware.org/?probe=68ae2ab1d0) | Jan 17, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [4abc3c8796](https://linux-hardware.org/?probe=4abc3c8796) | Jan 17, 2023 |
| Dell          | Studio 1735                 | Notebook    | [96d3df9639](https://linux-hardware.org/?probe=96d3df9639) | Jan 17, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [41839ed038](https://linux-hardware.org/?probe=41839ed038) | Jan 17, 2023 |
| Dell          | 01D4TT A00                  | Desktop     | [509404e50f](https://linux-hardware.org/?probe=509404e50f) | Jan 17, 2023 |
| Google        | Lulu                        | Notebook    | [b0e2a5a9b3](https://linux-hardware.org/?probe=b0e2a5a9b3) | Jan 16, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [8e4a061e95](https://linux-hardware.org/?probe=8e4a061e95) | Jan 16, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [fd843f48f5](https://linux-hardware.org/?probe=fd843f48f5) | Jan 16, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [8bdec78777](https://linux-hardware.org/?probe=8bdec78777) | Jan 16, 2023 |
| Dell          | 0T4VP9 A00                  | All in one  | [6f705f4121](https://linux-hardware.org/?probe=6f705f4121) | Jan 16, 2023 |
| Packard Be... | ONETWO S3220                | All in one  | [89fb0c5d06](https://linux-hardware.org/?probe=89fb0c5d06) | Jan 16, 2023 |
| Samsung       | R530/R730/P530              | Notebook    | [e6752958eb](https://linux-hardware.org/?probe=e6752958eb) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| MSI           | H61M-P20                    | Desktop     | [bf79928a7a](https://linux-hardware.org/?probe=bf79928a7a) | Jan 16, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [ce91a77f1c](https://linux-hardware.org/?probe=ce91a77f1c) | Jan 16, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7100a33e7e](https://linux-hardware.org/?probe=7100a33e7e) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | Compaq 15                   | Notebook    | [ddfd4fd188](https://linux-hardware.org/?probe=ddfd4fd188) | Jan 15, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Toshiba       | TECRA A11                   | Notebook    | [3d58fc9423](https://linux-hardware.org/?probe=3d58fc9423) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [456d3efd73](https://linux-hardware.org/?probe=456d3efd73) | Jan 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [f1e7eba4ca](https://linux-hardware.org/?probe=f1e7eba4ca) | Jan 15, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [239512c0c1](https://linux-hardware.org/?probe=239512c0c1) | Jan 15, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [45da89106d](https://linux-hardware.org/?probe=45da89106d) | Jan 15, 2023 |
| Acer          | Aspire 7250                 | Notebook    | [bcb2916be8](https://linux-hardware.org/?probe=bcb2916be8) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| AZW           | SER V01                     | Mini pc     | [37a326ed20](https://linux-hardware.org/?probe=37a326ed20) | Jan 15, 2023 |
| Dell          | Inspiron 5749               | Notebook    | [445264f815](https://linux-hardware.org/?probe=445264f815) | Jan 15, 2023 |
| Packard Be... | EasyNote ML65               | Notebook    | [e3599cb723](https://linux-hardware.org/?probe=e3599cb723) | Jan 15, 2023 |
| Dell          | 0M863N A01                  | Desktop     | [4d7e5c21fc](https://linux-hardware.org/?probe=4d7e5c21fc) | Jan 15, 2023 |
| Dell          | Inspiron 5370               | Notebook    | [78b4039791](https://linux-hardware.org/?probe=78b4039791) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | Notebook    | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2265827caa](https://linux-hardware.org/?probe=2265827caa) | Jan 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ab05084e01](https://linux-hardware.org/?probe=ab05084e01) | Jan 14, 2023 |
| Toshiba       | TECRA A11                   | Notebook    | [758daba5e5](https://linux-hardware.org/?probe=758daba5e5) | Jan 14, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0b375cb78b](https://linux-hardware.org/?probe=0b375cb78b) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | ThinkPad T420 42363C4       | Notebook    | [089518e186](https://linux-hardware.org/?probe=089518e186) | Jan 14, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [a14f62fa30](https://linux-hardware.org/?probe=a14f62fa30) | Jan 14, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [32026c5c05](https://linux-hardware.org/?probe=32026c5c05) | Jan 14, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [67d3d3c57a](https://linux-hardware.org/?probe=67d3d3c57a) | Jan 14, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [5d2c7b7ded](https://linux-hardware.org/?probe=5d2c7b7ded) | Jan 14, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Lenovo        | ThinkPad L510 2873A17       | Notebook    | [13f5fd23e5](https://linux-hardware.org/?probe=13f5fd23e5) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9774dee993](https://linux-hardware.org/?probe=9774dee993) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [56c9afafb4](https://linux-hardware.org/?probe=56c9afafb4) | Jan 14, 2023 |
| AZW           | SER V01                     | Mini pc     | [95376108b7](https://linux-hardware.org/?probe=95376108b7) | Jan 14, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [d09a603b10](https://linux-hardware.org/?probe=d09a603b10) | Jan 14, 2023 |
| HP            | 8054                        | Desktop     | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| Acer          | Aspire 5935                 | Notebook    | [40a8c82828](https://linux-hardware.org/?probe=40a8c82828) | Jan 14, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [1a25eeba6f](https://linux-hardware.org/?probe=1a25eeba6f) | Jan 14, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [04381152c2](https://linux-hardware.org/?probe=04381152c2) | Jan 14, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [a153e6f458](https://linux-hardware.org/?probe=a153e6f458) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [ed18454667](https://linux-hardware.org/?probe=ed18454667) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [5de8333ea3](https://linux-hardware.org/?probe=5de8333ea3) | Jan 14, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [3a330d3173](https://linux-hardware.org/?probe=3a330d3173) | Jan 13, 2023 |
| Dell          | 0JWGHC A02                  | All in one  | [3c361f58e8](https://linux-hardware.org/?probe=3c361f58e8) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | Notebook    | [3df12b0c9c](https://linux-hardware.org/?probe=3df12b0c9c) | Jan 13, 2023 |
| HP            | ProBook 4540s               | Notebook    | [9b33dc4291](https://linux-hardware.org/?probe=9b33dc4291) | Jan 13, 2023 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [d4e1fd3279](https://linux-hardware.org/?probe=d4e1fd3279) | Jan 13, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [940dcb54ef](https://linux-hardware.org/?probe=940dcb54ef) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| ASUSTek       | A7K                         | Notebook    | [5307ba44c0](https://linux-hardware.org/?probe=5307ba44c0) | Jan 13, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [f6e2ab2124](https://linux-hardware.org/?probe=f6e2ab2124) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [a399f30ea9](https://linux-hardware.org/?probe=a399f30ea9) | Jan 13, 2023 |
| ASUSTek       | X751LJ                      | Notebook    | [2cbaf315da](https://linux-hardware.org/?probe=2cbaf315da) | Jan 13, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [83bed4df76](https://linux-hardware.org/?probe=83bed4df76) | Jan 13, 2023 |
| ASUSTek       | A7K                         | Notebook    | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Teclast       | F6 Plus                     | Notebook    | [27cd155156](https://linux-hardware.org/?probe=27cd155156) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [73ca27df51](https://linux-hardware.org/?probe=73ca27df51) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| HP            | Notebook                    | Notebook    | [1baf122d48](https://linux-hardware.org/?probe=1baf122d48) | Jan 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [22749c467f](https://linux-hardware.org/?probe=22749c467f) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [ece6bd7a3c](https://linux-hardware.org/?probe=ece6bd7a3c) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c331071e8a](https://linux-hardware.org/?probe=c331071e8a) | Jan 13, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | Notebook    | [343813c285](https://linux-hardware.org/?probe=343813c285) | Jan 13, 2023 |
| ASUSTek       | H110S2                      | Desktop     | [d783389831](https://linux-hardware.org/?probe=d783389831) | Jan 13, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [91b0444e5e](https://linux-hardware.org/?probe=91b0444e5e) | Jan 12, 2023 |
| HP            | 21EF                        | Desktop     | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| HP            | 21EF                        | Desktop     | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| Intel         | DN2800MT AAG81515-900       | Desktop     | [546f31d89f](https://linux-hardware.org/?probe=546f31d89f) | Jan 12, 2023 |
| HP            | 15                          | Notebook    | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [4272389a24](https://linux-hardware.org/?probe=4272389a24) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [190d9b58b8](https://linux-hardware.org/?probe=190d9b58b8) | Jan 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [219ffa8cfd](https://linux-hardware.org/?probe=219ffa8cfd) | Jan 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [552d9fd542](https://linux-hardware.org/?probe=552d9fd542) | Jan 12, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [24461e4b9f](https://linux-hardware.org/?probe=24461e4b9f) | Jan 12, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [22bd8d5315](https://linux-hardware.org/?probe=22bd8d5315) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| Dell          | 0KM5PX A06                  | Server      | [63b5c2f7fb](https://linux-hardware.org/?probe=63b5c2f7fb) | Jan 12, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [7df180ed97](https://linux-hardware.org/?probe=7df180ed97) | Jan 12, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [ea76077171](https://linux-hardware.org/?probe=ea76077171) | Jan 11, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | Notebook    | [4128f195f0](https://linux-hardware.org/?probe=4128f195f0) | Jan 11, 2023 |
| Intel         | DQ77KB AAG81483-500         | Desktop     | [0e8844064e](https://linux-hardware.org/?probe=0e8844064e) | Jan 11, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| HP            | Notebook                    | Notebook    | [3ece4717c4](https://linux-hardware.org/?probe=3ece4717c4) | Jan 11, 2023 |
| Pine Micro... | Pine64 PinePhonePro (DT)    | Phone       | [a3cfc48f91](https://linux-hardware.org/?probe=a3cfc48f91) | Jan 11, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [a3dacf19d0](https://linux-hardware.org/?probe=a3dacf19d0) | Jan 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [d1b9dbaae0](https://linux-hardware.org/?probe=d1b9dbaae0) | Jan 11, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [ff44388b68](https://linux-hardware.org/?probe=ff44388b68) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | Notebook    | [47d808cdc7](https://linux-hardware.org/?probe=47d808cdc7) | Jan 10, 2023 |
| Lenovo        | ThinkPad X270 20HN0015FR    | Notebook    | [e303c543ba](https://linux-hardware.org/?probe=e303c543ba) | Jan 10, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [28df55cca2](https://linux-hardware.org/?probe=28df55cca2) | Jan 10, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [27ab381a1d](https://linux-hardware.org/?probe=27ab381a1d) | Jan 10, 2023 |
| Lenovo        | ThinkPad X201 3680AQ1       | Notebook    | [4a65277a98](https://linux-hardware.org/?probe=4a65277a98) | Jan 10, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f70bd958b7](https://linux-hardware.org/?probe=f70bd958b7) | Jan 10, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [937414941b](https://linux-hardware.org/?probe=937414941b) | Jan 10, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [21bfdfce4b](https://linux-hardware.org/?probe=21bfdfce4b) | Jan 10, 2023 |
| Dell          | 0V0D45 A01                  | All in one  | [673bece511](https://linux-hardware.org/?probe=673bece511) | Jan 10, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4f6e8d1ac5](https://linux-hardware.org/?probe=4f6e8d1ac5) | Jan 10, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [b0475049e8](https://linux-hardware.org/?probe=b0475049e8) | Jan 10, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0b9c1c2841](https://linux-hardware.org/?probe=0b9c1c2841) | Jan 09, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [1f77d36501](https://linux-hardware.org/?probe=1f77d36501) | Jan 09, 2023 |
| ASUSTek       | X301A1                      | Notebook    | [c98ae98676](https://linux-hardware.org/?probe=c98ae98676) | Jan 09, 2023 |
| Gigabyte      | B560I AORUS PRO AX          | Desktop     | [bd760b375b](https://linux-hardware.org/?probe=bd760b375b) | Jan 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [6746287398](https://linux-hardware.org/?probe=6746287398) | Jan 09, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| HP            | 802F                        | Desktop     | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [971ce3c690](https://linux-hardware.org/?probe=971ce3c690) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| Dell          | Precision 5560              | Notebook    | [cb05d14e97](https://linux-hardware.org/?probe=cb05d14e97) | Jan 09, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [8d02a61d53](https://linux-hardware.org/?probe=8d02a61d53) | Jan 09, 2023 |
| ASUSTek       | K50C                        | Notebook    | [266dd917fe](https://linux-hardware.org/?probe=266dd917fe) | Jan 08, 2023 |
| ASUSTek       | S301LA                      | Notebook    | [9745e5ae33](https://linux-hardware.org/?probe=9745e5ae33) | Jan 08, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [7ada807633](https://linux-hardware.org/?probe=7ada807633) | Jan 08, 2023 |
| HP            | 0A98h                       | Desktop     | [a26fc3d5f4](https://linux-hardware.org/?probe=a26fc3d5f4) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [474907a53e](https://linux-hardware.org/?probe=474907a53e) | Jan 08, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [df436102d6](https://linux-hardware.org/?probe=df436102d6) | Jan 08, 2023 |
| Framework     | Laptop                      | Notebook    | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [e8611b7b9b](https://linux-hardware.org/?probe=e8611b7b9b) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | Desktop     | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [faf4eff378](https://linux-hardware.org/?probe=faf4eff378) | Jan 08, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [4cf1c4b702](https://linux-hardware.org/?probe=4cf1c4b702) | Jan 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [d94d0c7025](https://linux-hardware.org/?probe=d94d0c7025) | Jan 08, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a763320a37](https://linux-hardware.org/?probe=a763320a37) | Jan 08, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [128fe1567d](https://linux-hardware.org/?probe=128fe1567d) | Jan 08, 2023 |
| MSI           | CR62 6M                     | Notebook    | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [f090331efa](https://linux-hardware.org/?probe=f090331efa) | Jan 07, 2023 |
| HP            | Compaq 6910p                | Notebook    | [8ba65cb6b5](https://linux-hardware.org/?probe=8ba65cb6b5) | Jan 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | Notebook    | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ff51bb2dd9](https://linux-hardware.org/?probe=ff51bb2dd9) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4291T4Y       | Notebook    | [b1c7c505b2](https://linux-hardware.org/?probe=b1c7c505b2) | Jan 07, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [d6f1a60435](https://linux-hardware.org/?probe=d6f1a60435) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [1530f96142](https://linux-hardware.org/?probe=1530f96142) | Jan 07, 2023 |
| Dell          | Latitude E6410              | Notebook    | [f664cab1c4](https://linux-hardware.org/?probe=f664cab1c4) | Jan 07, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [c840cf9ca5](https://linux-hardware.org/?probe=c840cf9ca5) | Jan 07, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [a2910be7b2](https://linux-hardware.org/?probe=a2910be7b2) | Jan 07, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [c3aacdc606](https://linux-hardware.org/?probe=c3aacdc606) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | Notebook    | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| MSI           | PRO B660M-B DDR4            | Desktop     | [cceab9ef33](https://linux-hardware.org/?probe=cceab9ef33) | Jan 07, 2023 |
| Framework     | Laptop                      | Notebook    | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| Dell          | 04MFRM A02                  | Desktop     | [7b29154637](https://linux-hardware.org/?probe=7b29154637) | Jan 07, 2023 |
| Toshiba       | Satellite Pro C850-10N      | Notebook    | [8f013ca042](https://linux-hardware.org/?probe=8f013ca042) | Jan 07, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [91c410b89a](https://linux-hardware.org/?probe=91c410b89a) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [3a51845b72](https://linux-hardware.org/?probe=3a51845b72) | Jan 07, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [d4111f62a5](https://linux-hardware.org/?probe=d4111f62a5) | Jan 07, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [38bc046bdd](https://linux-hardware.org/?probe=38bc046bdd) | Jan 07, 2023 |
| Lenovo        | IdeaPad S300 9803           | Notebook    | [1f31e39066](https://linux-hardware.org/?probe=1f31e39066) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [41e6bde836](https://linux-hardware.org/?probe=41e6bde836) | Jan 06, 2023 |
| Lenovo        | ThinkPad X200s 7469A98      | Notebook    | [475d16af35](https://linux-hardware.org/?probe=475d16af35) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [7fd8978322](https://linux-hardware.org/?probe=7fd8978322) | Jan 06, 2023 |
| ASRock        | H370M Pro4                  | Desktop     | [69d73f2269](https://linux-hardware.org/?probe=69d73f2269) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX563FD_UX563FD     | Convertible | [13e393ab7c](https://linux-hardware.org/?probe=13e393ab7c) | Jan 06, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [a4b5bc192d](https://linux-hardware.org/?probe=a4b5bc192d) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [cd1fc92879](https://linux-hardware.org/?probe=cd1fc92879) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [aa4288024c](https://linux-hardware.org/?probe=aa4288024c) | Jan 05, 2023 |
| HP            | Notebook                    | Notebook    | [e63dc1a81a](https://linux-hardware.org/?probe=e63dc1a81a) | Jan 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [892ada8934](https://linux-hardware.org/?probe=892ada8934) | Jan 05, 2023 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [a2038e788c](https://linux-hardware.org/?probe=a2038e788c) | Jan 05, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| HP            | 3397                        | Desktop     | [ef794d730d](https://linux-hardware.org/?probe=ef794d730d) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| Dell          | Precision 7520              | Notebook    | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| HP            | 8055                        | Desktop     | [5f51faab6e](https://linux-hardware.org/?probe=5f51faab6e) | Jan 05, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [84b31ee7de](https://linux-hardware.org/?probe=84b31ee7de) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [4ed6689d7c](https://linux-hardware.org/?probe=4ed6689d7c) | Jan 05, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [03f117a662](https://linux-hardware.org/?probe=03f117a662) | Jan 05, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [4ff5066793](https://linux-hardware.org/?probe=4ff5066793) | Jan 05, 2023 |
| Dell          | 0TP412                      | Desktop     | [b608bcbdcf](https://linux-hardware.org/?probe=b608bcbdcf) | Jan 04, 2023 |
| HP            | ProBook 470 G2              | Notebook    | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| ASUSTek       | PN62                        | Mini pc     | [cbc4213c79](https://linux-hardware.org/?probe=cbc4213c79) | Jan 04, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [7931ef67b2](https://linux-hardware.org/?probe=7931ef67b2) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [113e1b51b7](https://linux-hardware.org/?probe=113e1b51b7) | Jan 04, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [1e25e7059a](https://linux-hardware.org/?probe=1e25e7059a) | Jan 04, 2023 |
| ASUSTek       | N73SV                       | Notebook    | [2cba5c99c4](https://linux-hardware.org/?probe=2cba5c99c4) | Jan 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [192e7fac1d](https://linux-hardware.org/?probe=192e7fac1d) | Jan 03, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [f560abfd7f](https://linux-hardware.org/?probe=f560abfd7f) | Jan 03, 2023 |
| HP            | ProBook 6570b               | Notebook    | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| Dell          | Latitude 7410               | Notebook    | [028f9b0434](https://linux-hardware.org/?probe=028f9b0434) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | Desktop     | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [fac5053200](https://linux-hardware.org/?probe=fac5053200) | Jan 03, 2023 |
| HP            | 339A                        | Desktop     | [c35711cb53](https://linux-hardware.org/?probe=c35711cb53) | Jan 03, 2023 |
| HP            | 339A                        | Desktop     | [2a4cb6de27](https://linux-hardware.org/?probe=2a4cb6de27) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | Stream Notebook             | Notebook    | [0cacfea12c](https://linux-hardware.org/?probe=0cacfea12c) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [1fa699405c](https://linux-hardware.org/?probe=1fa699405c) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | Notebook    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [c6feaa89a0](https://linux-hardware.org/?probe=c6feaa89a0) | Jan 01, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| Dell          | System Inspiron N411Z       | Notebook    | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [aba076d86d](https://linux-hardware.org/?probe=aba076d86d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | Notebook    | [c13c5e3d0d](https://linux-hardware.org/?probe=c13c5e3d0d) | Jan 01, 2023 |
| Foxconn       | 2ACA                        | Desktop     | [505262a4b1](https://linux-hardware.org/?probe=505262a4b1) | Jan 01, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [12629ba25d](https://linux-hardware.org/?probe=12629ba25d) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| HP            | Pavilion dv6                | Notebook    | [30ec83dbd4](https://linux-hardware.org/?probe=30ec83dbd4) | Dec 31, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [9db6f0fda7](https://linux-hardware.org/?probe=9db6f0fda7) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [dde4bcd574](https://linux-hardware.org/?probe=dde4bcd574) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d44828a455](https://linux-hardware.org/?probe=d44828a455) | Dec 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [afa28ba4f3](https://linux-hardware.org/?probe=afa28ba4f3) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6de26a316e](https://linux-hardware.org/?probe=6de26a316e) | Dec 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [80abf89bc6](https://linux-hardware.org/?probe=80abf89bc6) | Dec 30, 2022 |
| MSI           | H61M-P22                    | Desktop     | [23b5356c0a](https://linux-hardware.org/?probe=23b5356c0a) | Dec 30, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [1d8b5f0509](https://linux-hardware.org/?probe=1d8b5f0509) | Dec 30, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [b4a7d759f7](https://linux-hardware.org/?probe=b4a7d759f7) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [47f838ca34](https://linux-hardware.org/?probe=47f838ca34) | Dec 30, 2022 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [d3daa756b4](https://linux-hardware.org/?probe=d3daa756b4) | Dec 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [6cf8d26754](https://linux-hardware.org/?probe=6cf8d26754) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| ASUSTek       | G1                          | Notebook    | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Toshiba       | Satellite C870-13V          | Notebook    | [5ad370d470](https://linux-hardware.org/?probe=5ad370d470) | Dec 29, 2022 |
| Acer          | Aspire 4820TG               | Notebook    | [77721c13c4](https://linux-hardware.org/?probe=77721c13c4) | Dec 29, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [9c4eab8774](https://linux-hardware.org/?probe=9c4eab8774) | Dec 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Shenzhen W... | TANK56                      | Notebook    | [4cd3e6c8e4](https://linux-hardware.org/?probe=4cd3e6c8e4) | Dec 29, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [6ece20ec58](https://linux-hardware.org/?probe=6ece20ec58) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [499c91958a](https://linux-hardware.org/?probe=499c91958a) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [8b16a66b73](https://linux-hardware.org/?probe=8b16a66b73) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [b915fc0d47](https://linux-hardware.org/?probe=b915fc0d47) | Dec 28, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [74c1f3a4c2](https://linux-hardware.org/?probe=74c1f3a4c2) | Dec 28, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| ASUSTek       | X555BP                      | Notebook    | [6ddc84aa0d](https://linux-hardware.org/?probe=6ddc84aa0d) | Dec 28, 2022 |
| Dell          | 0YXT71 A01                  | Desktop     | [ed5e31a6bc](https://linux-hardware.org/?probe=ed5e31a6bc) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [2966924363](https://linux-hardware.org/?probe=2966924363) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [f3e27d230f](https://linux-hardware.org/?probe=f3e27d230f) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30T-A              | Notebook    | [cab72e8a11](https://linux-hardware.org/?probe=cab72e8a11) | Dec 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | G56JR                       | Notebook    | [3acee33976](https://linux-hardware.org/?probe=3acee33976) | Dec 27, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [31f25029c1](https://linux-hardware.org/?probe=31f25029c1) | Dec 27, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [6fbb0cbd09](https://linux-hardware.org/?probe=6fbb0cbd09) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [838cda532a](https://linux-hardware.org/?probe=838cda532a) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Notebook      | L14xMU                      | Notebook    | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [f7c9b3538e](https://linux-hardware.org/?probe=f7c9b3538e) | Dec 26, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [ebf2a443c2](https://linux-hardware.org/?probe=ebf2a443c2) | Dec 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| ASUSTek       | K61IC                       | Notebook    | [4c34b8d5a1](https://linux-hardware.org/?probe=4c34b8d5a1) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [e47f890444](https://linux-hardware.org/?probe=e47f890444) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [c288ade12d](https://linux-hardware.org/?probe=c288ade12d) | Dec 26, 2022 |
| Dell          | 0H21J3 A07                  | Server      | [93e8563379](https://linux-hardware.org/?probe=93e8563379) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| HP            | 2AF7                        | Desktop     | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | Notebook    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| MSI           | CR700                       | Notebook    | [92b97fec48](https://linux-hardware.org/?probe=92b97fec48) | Dec 25, 2022 |
| Intel         | NUC6CAYB J23203-405         | Mini pc     | [964f42356a](https://linux-hardware.org/?probe=964f42356a) | Dec 25, 2022 |
| MSI           | CR700                       | Notebook    | [df25c10894](https://linux-hardware.org/?probe=df25c10894) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [5497596ef1](https://linux-hardware.org/?probe=5497596ef1) | Dec 25, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [26c346f0ab](https://linux-hardware.org/?probe=26c346f0ab) | Dec 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [08af6df0dd](https://linux-hardware.org/?probe=08af6df0dd) | Dec 25, 2022 |
| HP            | ENVY 17                     | Notebook    | [f3458ee7d5](https://linux-hardware.org/?probe=f3458ee7d5) | Dec 25, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [513af674c0](https://linux-hardware.org/?probe=513af674c0) | Dec 25, 2022 |
| HP            | ENVY Notebook               | Notebook    | [16af8b4da3](https://linux-hardware.org/?probe=16af8b4da3) | Dec 25, 2022 |
| Lenovo        | ThinkPad L530 24781P9       | Notebook    | [fd8de03405](https://linux-hardware.org/?probe=fd8de03405) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [9d8bce4c41](https://linux-hardware.org/?probe=9d8bce4c41) | Dec 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1762f53462](https://linux-hardware.org/?probe=1762f53462) | Dec 25, 2022 |
| Lenovo        | ThinkPad X220 4291UUC       | Notebook    | [6307be520e](https://linux-hardware.org/?probe=6307be520e) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a1f4999c28](https://linux-hardware.org/?probe=a1f4999c28) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [8df9791e32](https://linux-hardware.org/?probe=8df9791e32) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2b71327126](https://linux-hardware.org/?probe=2b71327126) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | Notebook    | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [dab48b870c](https://linux-hardware.org/?probe=dab48b870c) | Dec 23, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0d1532282f](https://linux-hardware.org/?probe=0d1532282f) | Dec 23, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| Acer          | E1-510                      | Notebook    | [463c668d4e](https://linux-hardware.org/?probe=463c668d4e) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| ASRock        | H270 Pro4                   | Desktop     | [548ba72d05](https://linux-hardware.org/?probe=548ba72d05) | Dec 23, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [bc197d71d8](https://linux-hardware.org/?probe=bc197d71d8) | Dec 23, 2022 |
| Danew         | Dbook 131                   | Notebook    | [25dbe464cd](https://linux-hardware.org/?probe=25dbe464cd) | Dec 23, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [33a03f23cc](https://linux-hardware.org/?probe=33a03f23cc) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Dell          | Inspiron 1546               | Notebook    | [7812af7998](https://linux-hardware.org/?probe=7812af7998) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [7794581d04](https://linux-hardware.org/?probe=7794581d04) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion 17                 | Notebook    | [65dcf1eead](https://linux-hardware.org/?probe=65dcf1eead) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [4a49555de6](https://linux-hardware.org/?probe=4a49555de6) | Dec 22, 2022 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [8cb7f41543](https://linux-hardware.org/?probe=8cb7f41543) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | Notebook    | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [de140c1edd](https://linux-hardware.org/?probe=de140c1edd) | Dec 22, 2022 |
| HP            | 81C9                        | Desktop     | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| MSI           | H97M-G43                    | Desktop     | [a34bd69442](https://linux-hardware.org/?probe=a34bd69442) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| Acer          | ERC410M                     | Desktop     | [e25233896a](https://linux-hardware.org/?probe=e25233896a) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| Gigabyte      | H170M-DS3H-CF               | Desktop     | [714dafad38](https://linux-hardware.org/?probe=714dafad38) | Dec 21, 2022 |
| MSI           | MAG B560M MORTAR            | Desktop     | [9b1e668d0a](https://linux-hardware.org/?probe=9b1e668d0a) | Dec 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [fd0cb86f82](https://linux-hardware.org/?probe=fd0cb86f82) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [827c7f9bd3](https://linux-hardware.org/?probe=827c7f9bd3) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | Notebook    | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [c0f4dfeb74](https://linux-hardware.org/?probe=c0f4dfeb74) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | Notebook    | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [df4a754b5d](https://linux-hardware.org/?probe=df4a754b5d) | Dec 19, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1e7aff6742](https://linux-hardware.org/?probe=1e7aff6742) | Dec 19, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [a16ed79c3d](https://linux-hardware.org/?probe=a16ed79c3d) | Dec 19, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [16f09c5918](https://linux-hardware.org/?probe=16f09c5918) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M70E 0830W4E    | Desktop     | [199c8776ef](https://linux-hardware.org/?probe=199c8776ef) | Dec 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f29071b4a8](https://linux-hardware.org/?probe=f29071b4a8) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| HP            | ProBook 4720s               | Notebook    | [cd684d5dbe](https://linux-hardware.org/?probe=cd684d5dbe) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [72eccc0663](https://linux-hardware.org/?probe=72eccc0663) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [83887c3224](https://linux-hardware.org/?probe=83887c3224) | Dec 18, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [ed996739df](https://linux-hardware.org/?probe=ed996739df) | Dec 18, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ed5d3570ef](https://linux-hardware.org/?probe=ed5d3570ef) | Dec 17, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| Acer          | Aspire A317-51K             | Notebook    | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| Toshiba       | Satellite C50D-A-12M        | Notebook    | [fa522940dd](https://linux-hardware.org/?probe=fa522940dd) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [a38c2f49be](https://linux-hardware.org/?probe=a38c2f49be) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| HP            | Notebook                    | Notebook    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [25b640f2ed](https://linux-hardware.org/?probe=25b640f2ed) | Dec 16, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [00c328990f](https://linux-hardware.org/?probe=00c328990f) | Dec 16, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [1a8c883ac5](https://linux-hardware.org/?probe=1a8c883ac5) | Dec 16, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [3d5598a5eb](https://linux-hardware.org/?probe=3d5598a5eb) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [655350654a](https://linux-hardware.org/?probe=655350654a) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [e80c6cf1e1](https://linux-hardware.org/?probe=e80c6cf1e1) | Dec 16, 2022 |
| Gigabyte      | H310M S2H                   | Desktop     | [2c008886c6](https://linux-hardware.org/?probe=2c008886c6) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [ff5206e8e0](https://linux-hardware.org/?probe=ff5206e8e0) | Dec 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [1da4bd3e02](https://linux-hardware.org/?probe=1da4bd3e02) | Dec 15, 2022 |
| HP            | Presario CQ62               | Notebook    | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| ZOTAC         | ION                         | Desktop     | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [94d4fe9a93](https://linux-hardware.org/?probe=94d4fe9a93) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [51ea57e65f](https://linux-hardware.org/?probe=51ea57e65f) | Dec 15, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [31bf14c8d8](https://linux-hardware.org/?probe=31bf14c8d8) | Dec 15, 2022 |
| HP            | 2AFB                        | Desktop     | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [8f21b4e9c9](https://linux-hardware.org/?probe=8f21b4e9c9) | Dec 14, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [b3c5f73f5a](https://linux-hardware.org/?probe=b3c5f73f5a) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [02067db7ad](https://linux-hardware.org/?probe=02067db7ad) | Dec 14, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [902c809015](https://linux-hardware.org/?probe=902c809015) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| ASRock        | FM2A78 Pro4+                | Desktop     | [cb63c9ad7f](https://linux-hardware.org/?probe=cb63c9ad7f) | Dec 14, 2022 |
| Dell          | 0H8367                      | Desktop     | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Toshiba       | PORTEGE R830                | Notebook    | [0d5af64ca4](https://linux-hardware.org/?probe=0d5af64ca4) | Dec 14, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [9bc1aec0dc](https://linux-hardware.org/?probe=9bc1aec0dc) | Dec 14, 2022 |
| Dell          | Latitude E7450              | Notebook    | [196b96ea5e](https://linux-hardware.org/?probe=196b96ea5e) | Dec 14, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| HP            | 304Ah                       | Desktop     | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| Intel         | DH61AG AAG23736-505         | Desktop     | [352a377398](https://linux-hardware.org/?probe=352a377398) | Dec 13, 2022 |
| ASUSTek       | X705UAP                     | Notebook    | [8080afc7d4](https://linux-hardware.org/?probe=8080afc7d4) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| Medion        | H61H2-LM3                   | Desktop     | [af98dc76b3](https://linux-hardware.org/?probe=af98dc76b3) | Dec 12, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [349781adbb](https://linux-hardware.org/?probe=349781adbb) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [8370a57760](https://linux-hardware.org/?probe=8370a57760) | Dec 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1717      | 19.39%  |
| Ubuntu 18.04       | 553       | 6.25%   |
| Ubuntu 22.04       | 453       | 5.12%   |
| OpenMandriva 4.2   | 358       | 4.04%   |
| Debian 11          | 333       | 3.76%   |
| OpenMandriva 4.3   | 287       | 3.24%   |
| Xubuntu 20.04      | 195       | 2.2%    |
| Linux Mint 20.3    | 178       | 2.01%   |
| Debian 10          | 134       | 1.51%   |
| Arch Rolling       | 133       | 1.5%    |
| OpenMandriva 23.01 | 127       | 1.43%   |
| Arch               | 124       | 1.4%    |
| Ubuntu 21.10       | 122       | 1.38%   |
| Ubuntu 20.10       | 109       | 1.23%   |
| Ubuntu 21.04       | 106       | 1.2%    |
| Linux Mint 20.2    | 106       | 1.2%    |
| Linux Mint 20.1    | 106       | 1.2%    |
| Manjaro            | 88        | 0.99%   |
| Fedora 33          | 88        | 0.99%   |
| Linux Mint 19.3    | 87        | 0.98%   |
| Ubuntu 19.10       | 85        | 0.96%   |
| Kubuntu 20.04      | 82        | 0.93%   |
| Zorin 16           | 80        | 0.9%    |
| Xubuntu 18.04      | 77        | 0.87%   |
| Linux Mint 20      | 76        | 0.86%   |
| Linux Mint 21      | 74        | 0.84%   |
| Fedora 34          | 74        | 0.84%   |
| Ubuntu 19.04       | 71        | 0.8%    |
| KDE neon 20.04     | 71        | 0.8%    |
| Fedora 35          | 70        | 0.79%   |
| Fedora 32          | 69        | 0.78%   |
| Ubuntu MATE 20.04  | 63        | 0.71%   |
| Fedora 36          | 63        | 0.71%   |
| Pop!_OS 22.04      | 58        | 0.65%   |
| Lubuntu 20.04      | 57        | 0.64%   |
| Fedora 37          | 54        | 0.61%   |
| Pop!_OS 21.04      | 50        | 0.56%   |
| OpenMandriva 4.50  | 50        | 0.56%   |
| Pop!_OS 20.04      | 49        | 0.55%   |
| Ubuntu 22.10       | 47        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3192      | 38.05%  |
| OpenMandriva  | 838       | 9.99%   |
| Linux Mint    | 678       | 8.08%   |
| Debian        | 564       | 6.72%   |
| Fedora        | 393       | 4.69%   |
| Xubuntu       | 355       | 4.23%   |
| Arch          | 251       | 2.99%   |
| Manjaro       | 233       | 2.78%   |
| Pop!_OS       | 217       | 2.59%   |
| Kubuntu       | 198       | 2.36%   |
| ROSA          | 173       | 2.06%   |
| Zorin         | 125       | 1.49%   |
| Ubuntu MATE   | 118       | 1.41%   |
| Lubuntu       | 103       | 1.23%   |
| KDE neon      | 88        | 1.05%   |
| Ubuntu Unity  | 67        | 0.8%    |
| openSUSE      | 65        | 0.77%   |
| Gentoo        | 56        | 0.67%   |
| Kali          | 51        | 0.61%   |
| Endless       | 51        | 0.61%   |
| Elementary    | 47        | 0.56%   |
| ArcoLinux     | 47        | 0.56%   |
| Ubuntu Budgie | 43        | 0.51%   |
| LMDE          | 34        | 0.41%   |
| EndeavourOS   | 34        | 0.41%   |
| BlackPanther  | 32        | 0.38%   |
| CentOS        | 28        | 0.33%   |
| SteamOS       | 23        | 0.27%   |
| Ubuntu Studio | 22        | 0.26%   |
| Parrot        | 20        | 0.24%   |
| Mageia        | 19        | 0.23%   |
| Clear Linux   | 19        | 0.23%   |
| MX            | 13        | 0.15%   |
| Kaisen        | 11        | 0.13%   |
| Manjaro-ARM   | 10        | 0.12%   |
| Artix         | 10        | 0.12%   |
| NixOS         | 9         | 0.11%   |
| Devuan        | 9         | 0.11%   |
| Raspbian      | 8         | 0.1%    |
| Nobara        | 8         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 341       | 3.52%   |
| 5.16.7-desktop-1omv4003  | 268       | 2.77%   |
| 5.4.0-42-generic         | 128       | 1.32%   |
| 5.15.0-56-generic        | 121       | 1.25%   |
| 6.1.1-desktop-1omv2290   | 112       | 1.16%   |
| 5.4.0-58-generic         | 99        | 1.02%   |
| 5.15.0-58-generic        | 95        | 0.98%   |
| 5.15.0-52-generic        | 94        | 0.97%   |
| 5.4.0-52-generic         | 81        | 0.84%   |
| 5.11.0-38-generic        | 76        | 0.78%   |
| 5.11.0-27-generic        | 76        | 0.78%   |
| 5.15.0-48-generic        | 74        | 0.76%   |
| 5.4.0-26-generic         | 72        | 0.74%   |
| 5.8.0-43-generic         | 69        | 0.71%   |
| 5.4.0-48-generic         | 69        | 0.71%   |
| 5.15.0-46-generic        | 66        | 0.68%   |
| 5.11.0-37-generic        | 66        | 0.68%   |
| 5.4.0-65-generic         | 65        | 0.67%   |
| 5.8.0-50-generic         | 63        | 0.65%   |
| 5.15.0-43-generic        | 60        | 0.62%   |
| 5.11.0-40-generic        | 57        | 0.59%   |
| 5.4.0-29-generic         | 55        | 0.57%   |
| 5.13.0-28-generic        | 55        | 0.57%   |
| 5.8.0-44-generic         | 54        | 0.56%   |
| 5.4.0-91-generic         | 54        | 0.56%   |
| 5.4.0-54-generic         | 54        | 0.56%   |
| 5.15.0-47-generic        | 54        | 0.56%   |
| 5.8.0-48-generic         | 53        | 0.55%   |
| 5.4.0-37-generic         | 53        | 0.55%   |
| 5.13.0-39-generic        | 52        | 0.54%   |
| 5.11.0-43-generic        | 51        | 0.53%   |
| 5.4.0-81-generic         | 48        | 0.5%    |
| 5.15.0-53-generic        | 48        | 0.5%    |
| 5.11.0-34-generic        | 48        | 0.5%    |
| 5.8.0-59-generic         | 46        | 0.48%   |
| 5.15.0-41-generic        | 46        | 0.48%   |
| 5.4.0-31-generic         | 45        | 0.46%   |
| 5.13.0-40-generic        | 45        | 0.46%   |
| 5.8.0-53-generic         | 42        | 0.43%   |
| 5.13.0-27-generic        | 42        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1755      | 19.27%  |
| 5.15.0  | 873       | 9.59%   |
| 5.11.0  | 630       | 6.92%   |
| 5.8.0   | 612       | 6.72%   |
| 5.13.0  | 515       | 5.66%   |
| 4.15.0  | 434       | 4.77%   |
| 5.10.0  | 357       | 3.92%   |
| 5.10.14 | 344       | 3.78%   |
| 5.3.0   | 288       | 3.16%   |
| 5.16.7  | 270       | 2.97%   |
| 5.0.0   | 164       | 1.8%    |
| 4.18.0  | 137       | 1.5%    |
| 4.19.0  | 128       | 1.41%   |
| 6.1.1   | 126       | 1.38%   |
| 5.19.0  | 124       | 1.36%   |
| 5.14.0  | 42        | 0.46%   |
| 6.0.0   | 37        | 0.41%   |
| 4.9.20  | 35        | 0.38%   |
| 5.11.12 | 33        | 0.36%   |
| 5.18.12 | 32        | 0.35%   |
| 5.18.0  | 31        | 0.34%   |
| 5.17.5  | 30        | 0.33%   |
| 4.18.16 | 29        | 0.32%   |
| 5.16.0  | 28        | 0.31%   |
| 4.4.0   | 28        | 0.31%   |
| 5.9.0   | 25        | 0.27%   |
| 5.12.4  | 23        | 0.25%   |
| 4.9.60  | 23        | 0.25%   |
| 5.19.12 | 22        | 0.24%   |
| 5.16.13 | 20        | 0.22%   |
| 5.13.19 | 19        | 0.21%   |
| 6.0.12  | 18        | 0.2%    |
| 5.9.16  | 18        | 0.2%    |
| 5.9.11  | 18        | 0.2%    |
| 5.7.0   | 18        | 0.2%    |
| 5.6.0   | 18        | 0.2%    |
| 5.17.1  | 17        | 0.19%   |
| 5.17.0  | 17        | 0.19%   |
| 4.9.0   | 17        | 0.19%   |
| 5.13.12 | 16        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4      | 1850      | 20.57%  |
| 5.15     | 1064      | 11.83%  |
| 5.10     | 845       | 9.4%    |
| 5.11     | 724       | 8.05%   |
| 5.8      | 701       | 7.8%    |
| 5.13     | 598       | 6.65%   |
| 4.15     | 435       | 4.84%   |
| 5.16     | 393       | 4.37%   |
| 5.3      | 329       | 3.66%   |
| 5.19     | 214       | 2.38%   |
| 6.1      | 203       | 2.26%   |
| 5.0      | 177       | 1.97%   |
| 4.18     | 169       | 1.88%   |
| 4.19     | 145       | 1.61%   |
| 6.0      | 137       | 1.52%   |
| 5.18     | 128       | 1.42%   |
| 5.14     | 128       | 1.42%   |
| 5.9      | 119       | 1.32%   |
| 4.9      | 119       | 1.32%   |
| 5.17     | 105       | 1.17%   |
| 5.6      | 82        | 0.91%   |
| 5.7      | 73        | 0.81%   |
| 5.12     | 70        | 0.78%   |
| 5.5      | 39        | 0.43%   |
| 4.4      | 32        | 0.36%   |
| 4.1      | 24        | 0.27%   |
| 3.10     | 15        | 0.17%   |
| 5.2      | 13        | 0.14%   |
| 4.14     | 12        | 0.13%   |
| 4.12     | 9         | 0.1%    |
| 4.20     | 7         | 0.08%   |
| 4.13     | 7         | 0.08%   |
| 5.1      | 6         | 0.07%   |
| 6.2      | 4         | 0.04%   |
| 4.10     | 4         | 0.04%   |
| 4.8      | 3         | 0.03%   |
| 4.17     | 2         | 0.02%   |
| 3.4      | 2         | 0.02%   |
| 5        | 1         | 0.01%   |
| 4.9.273~ | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7884      | 96.61%  |
| i686    | 213       | 2.61%   |
| aarch64 | 43        | 0.53%   |
| armv7l  | 17        | 0.21%   |
| armv8l  | 2         | 0.02%   |
| armv6l  | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3752      | 44.33%  |
| KDE5              | 1470      | 17.37%  |
| Unknown           | 866       | 10.23%  |
| XFCE              | 748       | 8.84%   |
| X-Cinnamon        | 481       | 5.68%   |
| MATE              | 316       | 3.73%   |
| Cinnamon          | 125       | 1.48%   |
| KDE4              | 115       | 1.36%   |
| KDE               | 115       | 1.36%   |
| LXQt              | 112       | 1.32%   |
| Unity             | 68        | 0.8%    |
| i3                | 66        | 0.78%   |
| Budgie            | 51        | 0.6%    |
| Pantheon          | 49        | 0.58%   |
| LXDE              | 38        | 0.45%   |
| GNOME Flashback   | 24        | 0.28%   |
| GNOME Classic     | 13        | 0.15%   |
| Deepin            | 11        | 0.13%   |
| sway              | 6         | 0.07%   |
| qtile             | 5         | 0.06%   |
| bspwm             | 5         | 0.06%   |
| awesome           | 4         | 0.05%   |
| Trinity           | 3         | 0.04%   |
| i3-with-shmlog    | 3         | 0.04%   |
| Openbox           | 2         | 0.02%   |
| lightdm-xsession  | 2         | 0.02%   |
| ICEWM             | 2         | 0.02%   |
| Enlightenment     | 2         | 0.02%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xmonad            | 1         | 0.01%   |
| wmaker-common     | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| LeftWM            | 1         | 0.01%   |
| Hyprland          | 1         | 0.01%   |
| GNUstep           | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |
| dwm-sc            | 1         | 0.01%   |
| DWM               | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6600      | 78.7%   |
| Wayland | 1123      | 13.39%  |
| Unknown | 426       | 5.08%   |
| Tty     | 237       | 2.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3281      | 38.72%  |
| GDM     | 1487      | 17.55%  |
| SDDM    | 1464      | 17.28%  |
| LightDM | 924       | 10.9%   |
| GDM3    | 840       | 9.91%   |
| TDM     | 334       | 3.94%   |
| KDM     | 111       | 1.31%   |
| XDM     | 11        | 0.13%   |
| Ly      | 8         | 0.09%   |
| SLiM    | 6         | 0.07%   |
| NODM    | 3         | 0.04%   |
| LXDM    | 3         | 0.04%   |
| WDM     | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| fr_FR       | 5759      | 69.34%  |
| en_US       | 1374      | 16.54%  |
| Unknown     | 745       | 8.97%   |
| en_GB       | 135       | 1.63%   |
| C           | 90        | 1.08%   |
| de_DE       | 24        | 0.29%   |
| ru_RU       | 22        | 0.26%   |
| es_ES       | 15        | 0.18%   |
| it_IT       | 14        | 0.17%   |
| nl_NL       | 12        | 0.14%   |
| fr_CH       | 11        | 0.13%   |
| pl_PL       | 10        | 0.12%   |
| fr_CA       | 9         | 0.11%   |
| pt_PT       | 7         | 0.08%   |
| fr_BE       | 7         | 0.08%   |
| POSIX       | 6         | 0.07%   |
| ru_UA       | 4         | 0.05%   |
| en_IE       | 4         | 0.05%   |
| en_AU       | 4         | 0.05%   |
| C.UTF8      | 4         | 0.05%   |
| sv_SE       | 3         | 0.04%   |
| pt_BR       | 3         | 0.04%   |
| fr_FR.UTF8  | 3         | 0.04%   |
| en_IN       | 3         | 0.04%   |
| hu_HU       | 2         | 0.02%   |
| fr_LU       | 2         | 0.02%   |
| en_DK       | 2         | 0.02%   |
| en_CA       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| cs_CZ       | 2         | 0.02%   |
| tr_TR       | 1         | 0.01%   |
| sr_RS@latin | 1         | 0.01%   |
| sr_RS       | 1         | 0.01%   |
| sk_SK       | 1         | 0.01%   |
| ro_RO       | 1         | 0.01%   |
| nb_NO       | 1         | 0.01%   |
| fr_FR.utf-8 | 1         | 0.01%   |
| fi_FI       | 1         | 0.01%   |
| eu_ES       | 1         | 0.01%   |
| es_VE       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4283      | 51.52%  |
| BIOS | 4030      | 48.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6641      | 79.84%  |
| Overlay  | 795       | 9.56%   |
| Btrfs    | 483       | 5.81%   |
| Unknown  | 221       | 2.66%   |
| Xfs      | 82        | 0.99%   |
| Zfs      | 46        | 0.55%   |
| Ext2     | 15        | 0.18%   |
| F2fs     | 13        | 0.16%   |
| Ext3     | 13        | 0.16%   |
| Tmpfs    | 3         | 0.04%   |
| Reiserfs | 3         | 0.04%   |
| Rootfs   | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |
| Aufs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3538      | 42.36%  |
| Unknown | 3507      | 41.98%  |
| MBR     | 1308      | 15.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6744      | 81.16%  |
| Yes       | 1566      | 18.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5577      | 67.19%  |
| Yes       | 2723      | 32.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1656      | 20.3%   |
| Dell                    | 1188      | 14.56%  |
| Hewlett-Packard         | 1036      | 12.7%   |
| Lenovo                  | 914       | 11.21%  |
| MSI                     | 691       | 8.47%   |
| Gigabyte Technology     | 470       | 5.76%   |
| Acer                    | 414       | 5.08%   |
| ASRock                  | 201       | 2.46%   |
| Toshiba                 | 149       | 1.83%   |
| Apple                   | 146       | 1.79%   |
| Intel                   | 119       | 1.46%   |
| Packard Bell            | 92        | 1.13%   |
| Notebook                | 83        | 1.02%   |
| HUAWEI                  | 70        | 0.86%   |
| Samsung Electronics     | 64        | 0.78%   |
| Unknown                 | 62        | 0.76%   |
| Sony                    | 55        | 0.67%   |
| Foxconn                 | 47        | 0.58%   |
| Pegatron                | 40        | 0.49%   |
| Fujitsu                 | 37        | 0.45%   |
| Raspberry Pi Foundation | 35        | 0.43%   |
| eMachines               | 34        | 0.42%   |
| Medion                  | 30        | 0.37%   |
| TUXEDO                  | 27        | 0.33%   |
| Supermicro              | 24        | 0.29%   |
| Timi                    | 22        | 0.27%   |
| Alienware               | 21        | 0.26%   |
| Thomson                 | 20        | 0.25%   |
| Microsoft               | 20        | 0.25%   |
| Clevo                   | 20        | 0.25%   |
| Valve                   | 19        | 0.23%   |
| Fujitsu Siemens         | 19        | 0.23%   |
| AZW                     | 19        | 0.23%   |
| UNOWHY                  | 18        | 0.22%   |
| Shuttle                 | 14        | 0.17%   |
| Chuwi                   | 14        | 0.17%   |
| PC Specialist           | 13        | 0.16%   |
| ECS                     | 13        | 0.16%   |
| BESSTAR Tech            | 13        | 0.16%   |
| Razer                   | 12        | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| ASUS All Series           | 117       | 1.43%   |
| Unknown                   | 81        | 0.99%   |
| HP Notebook               | 37        | 0.45%   |
| Gigabyte B450M DS3H       | 29        | 0.36%   |
| HP Pavilion dv6           | 25        | 0.31%   |
| HP Pavilion 17            | 23        | 0.28%   |
| HP Pavilion dv7           | 22        | 0.27%   |
| Dell OptiPlex 390         | 20        | 0.25%   |
| Valve Jupiter             | 19        | 0.23%   |
| Dell OptiPlex 7010        | 18        | 0.22%   |
| HP Pavilion g7            | 17        | 0.21%   |
| Dell XPS 13 9310          | 17        | 0.21%   |
| MSI MS-7C91               | 16        | 0.2%    |
| Dell OptiPlex 9020        | 16        | 0.2%    |
| ASUS S551LN               | 16        | 0.2%    |
| HP Pavilion Notebook      | 15        | 0.18%   |
| Dell XPS 13 9380          | 15        | 0.18%   |
| Dell XPS 13 7390          | 15        | 0.18%   |
| ASUS PRIME A320M-K        | 15        | 0.18%   |
| MSI MS-7C37               | 14        | 0.17%   |
| MSI MS-7C02               | 14        | 0.17%   |
| Dell Latitude E6420       | 14        | 0.17%   |
| MSI MS-7817               | 13        | 0.16%   |
| MSI MS-7816               | 13        | 0.16%   |
| HP EliteBook 840 G2       | 13        | 0.16%   |
| Gigabyte 970A-DS3P        | 13        | 0.16%   |
| Dell XPS 15 7590          | 13        | 0.16%   |
| Dell OptiPlex 3020        | 13        | 0.16%   |
| MSI MS-7758               | 12        | 0.15%   |
| MSI MS-7693               | 12        | 0.15%   |
| HP Pavilion 15            | 12        | 0.15%   |
| HP EliteBook 840 G3       | 12        | 0.15%   |
| HP Compaq Elite 8300 SFF  | 12        | 0.15%   |
| Gigabyte B450 AORUS ELITE | 12        | 0.15%   |
| Dell XPS 15 9570          | 12        | 0.15%   |
| Dell Latitude 5420        | 12        | 0.15%   |
| ASUS PRIME B450M-A        | 12        | 0.15%   |
| HUAWEI NBLK-WAX9X         | 11        | 0.13%   |
| HUAWEI HVY-WXX9           | 11        | 0.13%   |
| HP ProBook 650 G1         | 11        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 449       | 5.5%    |
| Dell Latitude         | 335       | 4.11%   |
| Acer Aspire           | 274       | 3.36%   |
| HP Pavilion           | 222       | 2.72%   |
| Dell Precision        | 207       | 2.54%   |
| Dell OptiPlex         | 176       | 2.16%   |
| Dell XPS              | 167       | 2.05%   |
| Dell Inspiron         | 161       | 1.97%   |
| HP EliteBook          | 152       | 1.86%   |
| Lenovo IdeaPad        | 140       | 1.72%   |
| ASUS PRIME            | 136       | 1.67%   |
| Toshiba Satellite     | 125       | 1.53%   |
| HP ProBook            | 120       | 1.47%   |
| ASUS All              | 117       | 1.43%   |
| HP Compaq             | 112       | 1.37%   |
| ASUS ROG              | 109       | 1.34%   |
| ASUS VivoBook         | 108       | 1.32%   |
| Lenovo ThinkCentre    | 86        | 1.05%   |
| Unknown               | 81        | 0.99%   |
| ASUS TUF              | 79        | 0.97%   |
| HP Laptop             | 67        | 0.82%   |
| ASUS ZenBook          | 54        | 0.66%   |
| Packard Bell EasyNote | 48        | 0.59%   |
| Dell Vostro           | 46        | 0.56%   |
| Acer Swift            | 42        | 0.51%   |
| HP Notebook           | 37        | 0.45%   |
| Lenovo Legion         | 36        | 0.44%   |
| RPi Raspberry         | 35        | 0.43%   |
| HP ENVY               | 35        | 0.43%   |
| Gigabyte B450M        | 34        | 0.42%   |
| Lenovo Yoga           | 33        | 0.4%    |
| HP ZBook              | 31        | 0.38%   |
| Dell PowerEdge        | 26        | 0.32%   |
| Packard Bell IMEDIA   | 25        | 0.31%   |
| Acer Nitro            | 25        | 0.31%   |
| HP EliteDesk          | 24        | 0.29%   |
| ASUS P8Z77-V          | 24        | 0.29%   |
| ASUS ASUS             | 24        | 0.29%   |
| HP ProDesk            | 23        | 0.28%   |
| Gigabyte B450         | 22        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 785       | 9.62%   |
| 2020    | 747       | 9.16%   |
| 2019    | 738       | 9.05%   |
| 2012    | 658       | 8.07%   |
| 2013    | 611       | 7.49%   |
| 2011    | 537       | 6.58%   |
| 2021    | 489       | 5.99%   |
| 2017    | 486       | 5.96%   |
| 2015    | 486       | 5.96%   |
| 2014    | 470       | 5.76%   |
| 2010    | 441       | 5.41%   |
| 2016    | 409       | 5.01%   |
| 2009    | 363       | 4.45%   |
| 2008    | 361       | 4.43%   |
| 2007    | 191       | 2.34%   |
| 2022    | 167       | 2.05%   |
| 2006    | 95        | 1.16%   |
| Unknown | 53        | 0.65%   |
| 2005    | 47        | 0.58%   |
| 2004    | 12        | 0.15%   |
| 2003    | 6         | 0.07%   |
| 2002    | 2         | 0.02%   |
| 2001    | 2         | 0.02%   |
| 2023    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4514      | 55.34%  |
| Desktop        | 3132      | 38.4%   |
| Convertible    | 128       | 1.57%   |
| Mini pc        | 118       | 1.45%   |
| All in one     | 94        | 1.15%   |
| Server         | 64        | 0.78%   |
| System on chip | 48        | 0.59%   |
| Tablet         | 48        | 0.59%   |
| Phone          | 10        | 0.12%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7513      | 91.52%  |
| Enabled  | 696       | 8.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8139      | 99.77%  |
| Yes  | 19        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1813      | 21.93%  |
| 3.01-4.0        | 1799      | 21.76%  |
| 16.01-24.0      | 1713      | 20.72%  |
| 8.01-16.0       | 1406      | 17.01%  |
| 32.01-64.0      | 680       | 8.23%   |
| 1.01-2.0        | 336       | 4.06%   |
| 64.01-256.0     | 177       | 2.14%   |
| 2.01-3.0        | 137       | 1.66%   |
| 24.01-32.0      | 120       | 1.45%   |
| 0.51-1.0        | 61        | 0.74%   |
| 0.01-0.5        | 11        | 0.13%   |
| More than 256.0 | 8         | 0.1%    |
| Unknown         | 5         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3229      | 36.09%  |
| 2.01-3.0    | 2186      | 24.43%  |
| 4.01-8.0    | 1238      | 13.84%  |
| 3.01-4.0    | 1120      | 12.52%  |
| 0.51-1.0    | 613       | 6.85%   |
| 8.01-16.0   | 355       | 3.97%   |
| 0.01-0.5    | 120       | 1.34%   |
| 16.01-24.0  | 47        | 0.53%   |
| 24.01-32.0  | 16        | 0.18%   |
| 32.01-64.0  | 14        | 0.16%   |
| Unknown     | 9         | 0.1%    |
| 64.01-256.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4891      | 58.46%  |
| 2       | 2117      | 25.3%   |
| 3       | 683       | 8.16%   |
| 4       | 321       | 3.84%   |
| 5       | 145       | 1.73%   |
| 0       | 76        | 0.91%   |
| 6       | 69        | 0.82%   |
| 7       | 37        | 0.44%   |
| 8       | 12        | 0.14%   |
| 9       | 5         | 0.06%   |
| Unknown | 4         | 0.05%   |
| 22      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 11      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4563      | 55.45%  |
| Yes       | 3666      | 44.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7154      | 87.5%   |
| No        | 1022      | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6008      | 73.09%  |
| No        | 2212      | 26.91%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4594      | 55.63%  |
| No        | 3664      | 44.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| France  | 8157      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Paris            | 1269      | 14.45%  |
| Lyon             | 173       | 1.97%   |
| Marseille        | 149       | 1.7%    |
| Toulouse         | 127       | 1.45%   |
| Nantes           | 103       | 1.17%   |
| Strasbourg       | 91        | 1.04%   |
| Montpellier      | 81        | 0.92%   |
| Rennes           | 70        | 0.8%    |
| Lille            | 65        | 0.74%   |
| Bordeaux         | 65        | 0.74%   |
| Roubaix          | 64        | 0.73%   |
| Grenoble         | 62        | 0.71%   |
| Nice             | 59        | 0.67%   |
| Clichy-sous-Bois | 58        | 0.66%   |
| Brest            | 45        | 0.51%   |
| Tours            | 40        | 0.46%   |
| La Rochelle      | 36        | 0.41%   |
| Villeurbanne     | 34        | 0.39%   |
| Toulon           | 34        | 0.39%   |
| Rouen            | 33        | 0.38%   |
| Poitiers         | 30        | 0.34%   |
| Caen             | 30        | 0.34%   |
| Nîmes           | 28        | 0.32%   |
| Argenteuil       | 28        | 0.32%   |
| Aix-en-Provence  | 28        | 0.32%   |
| Metz             | 27        | 0.31%   |
| Limoges          | 26        | 0.3%    |
| Clermont-Ferrand | 26        | 0.3%    |
| Cergy            | 26        | 0.3%    |
| Versailles       | 25        | 0.28%   |
| Pau              | 25        | 0.28%   |
| Nancy            | 24        | 0.27%   |
| Besançon        | 24        | 0.27%   |
| Angers           | 24        | 0.27%   |
| Amiens           | 24        | 0.27%   |
| Perpignan        | 22        | 0.25%   |
| Dijon            | 22        | 0.25%   |
| Aubervilliers    | 22        | 0.25%   |
| Saint-Denis      | 20        | 0.23%   |
| Orléans         | 20        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1904      | 2878   | 15.9%   |
| Samsung Electronics         | 1840      | 2799   | 15.37%  |
| WDC                         | 1736      | 2631   | 14.5%   |
| Crucial                     | 836       | 1146   | 6.98%   |
| Toshiba                     | 776       | 1022   | 6.48%   |
| SanDisk                     | 589       | 736    | 4.92%   |
| Kingston                    | 582       | 706    | 4.86%   |
| Unknown                     | 445       | 592    | 3.72%   |
| Hitachi                     | 380       | 476    | 3.17%   |
| SK hynix                    | 338       | 407    | 2.82%   |
| HGST                        | 315       | 414    | 2.63%   |
| Intel                       | 260       | 321    | 2.17%   |
| Micron Technology           | 205       | 245    | 1.71%   |
| PNY                         | 150       | 181    | 1.25%   |
| Maxtor                      | 100       | 128    | 0.84%   |
| LDLC                        | 92        | 136    | 0.77%   |
| KIOXIA                      | 91        | 103    | 0.76%   |
| Phison                      | 80        | 98     | 0.67%   |
| China                       | 80        | 97     | 0.67%   |
| Transcend                   | 71        | 82     | 0.59%   |
| Corsair                     | 69        | 82     | 0.58%   |
| Apple                       | 60        | 77     | 0.5%    |
| Micron/Crucial Technology   | 52        | 69     | 0.43%   |
| OCZ                         | 48        | 66     | 0.4%    |
| Fujitsu                     | 47        | 64     | 0.39%   |
| LITEON                      | 45        | 50     | 0.38%   |
| SPCC                        | 44        | 56     | 0.37%   |
| A-DATA Technology           | 38        | 46     | 0.32%   |
| JMicron Technology          | 36        | 43     | 0.3%    |
| LITEONIT                    | 32        | 34     | 0.27%   |
| Unknown                     | 27        | 32     | 0.23%   |
| Silicon Motion              | 26        | 36     | 0.22%   |
| Emtec                       | 21        | 24     | 0.18%   |
| Gigabyte Technology         | 20        | 24     | 0.17%   |
| ASMT                        | 20        | 23     | 0.17%   |
| Phison Electronics          | 17        | 20     | 0.14%   |
| Kingston Technology Company | 17        | 18     | 0.14%   |
| Intenso                     | 16        | 18     | 0.13%   |
| Patriot                     | 15        | 21     | 0.13%   |
| KingSpec                    | 15        | 18     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Crucial CT240BX500SSD1 240GB       | 137       | 1.04%   |
| Samsung SSD 860 EVO 500GB          | 133       | 1.01%   |
| Crucial CT500MX500SSD1 500GB       | 121       | 0.92%   |
| HGST HTS721010A9E630 1TB           | 107       | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB     | 103       | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 98        | 0.74%   |
| Kingston SA400S37240G 240GB SSD    | 95        | 0.72%   |
| Toshiba MQ01ABD100 1TB             | 94        | 0.71%   |
| Samsung SSD 850 EVO 250GB          | 91        | 0.69%   |
| Seagate ST500DM002-1BD142 500GB    | 85        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB     | 81        | 0.62%   |
| Samsung SSD 850 EVO 500GB          | 81        | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB     | 80        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB        | 73        | 0.55%   |
| Unknown MMC Card  32GB             | 68        | 0.52%   |
| Samsung SSD 860 EVO 1TB            | 68        | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB     | 64        | 0.49%   |
| Crucial CT480BX500SSD1 480GB       | 60        | 0.46%   |
| Samsung SSD 860 EVO 250GB          | 59        | 0.45%   |
| Toshiba MQ04ABF100 1TB             | 58        | 0.44%   |
| Seagate ST1000DM003-1ER162 1TB     | 57        | 0.43%   |
| Kingston SA400S37120G 120GB SSD    | 57        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB     | 56        | 0.43%   |
| Unknown MMC Card  64GB             | 55        | 0.42%   |
| Samsung NVMe SSD Drive 512GB       | 55        | 0.42%   |
| Unknown SD/MMC/MS PRO 16GB         | 54        | 0.41%   |
| HGST HTS541010A9E680 1TB           | 53        | 0.4%    |
| Samsung SSD 870 QVO 1TB            | 52        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 51        | 0.39%   |
| Seagate ST2000DM001-1CH164 2TB     | 51        | 0.39%   |
| Kingston SA400S37480G 480GB SSD    | 49        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD   | 48        | 0.36%   |
| Samsung NVMe SSD Drive 500GB       | 47        | 0.36%   |
| PNY CS900 120GB SSD                | 47        | 0.36%   |
| Samsung SSD 860 QVO 1TB            | 46        | 0.35%   |
| PNY CS900 240GB SSD                | 45        | 0.34%   |
| SanDisk NVMe SSD Drive 512GB       | 44        | 0.33%   |
| Crucial CT120BX500SSD1 120GB       | 44        | 0.33%   |
| Seagate ST9500325AS 500GB          | 41        | 0.31%   |
| Seagate ST500LT012-1DG142 500GB    | 41        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1877      | 2815   | 36.38%  |
| WDC                 | 1438      | 2230   | 27.87%  |
| Toshiba             | 595       | 768    | 11.53%  |
| Hitachi             | 380       | 476    | 7.37%   |
| HGST                | 314       | 412    | 6.09%   |
| Samsung Electronics | 237       | 354    | 4.59%   |
| Maxtor              | 100       | 128    | 1.94%   |
| Unknown             | 61        | 70     | 1.18%   |
| Fujitsu             | 46        | 63     | 0.89%   |
| JMicron Technology  | 18        | 23     | 0.35%   |
| Apple               | 18        | 20     | 0.35%   |
| SABRENT             | 11        | 11     | 0.21%   |
| Hewlett-Packard     | 8         | 14     | 0.16%   |
| ASMT                | 8         | 10     | 0.16%   |
| Magnetic Data       | 6         | 6      | 0.12%   |
| IBM/Hitachi         | 5         | 6      | 0.1%    |
| ASMedia             | 5         | 5      | 0.1%    |
| USB3.0              | 3         | 3      | 0.06%   |
| LaCie               | 3         | 3      | 0.06%   |
| Intenso             | 3         | 4      | 0.06%   |
| HGST HTS            | 3         | 4      | 0.06%   |
| ASMT109x            | 3         | 4      | 0.06%   |
| USB                 | 2         | 3      | 0.04%   |
| RSH-319             | 2         | 3      | 0.04%   |
| PHD 3.0             | 2         | 2      | 0.04%   |
| Storeva             | 1         | 1      | 0.02%   |
| SILICONMOTION       | 1         | 1      | 0.02%   |
| QEMU                | 1         | 1      | 0.02%   |
| MDT                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| ICY BOX             | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| DELLBOSS            | 1         | 1      | 0.02%   |
| APPLE HD            | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1010      | 1426   | 25.07%  |
| Crucial             | 751       | 1030   | 18.64%  |
| Kingston            | 482       | 586    | 11.96%  |
| SanDisk             | 404       | 499    | 10.03%  |
| PNY                 | 137       | 164    | 3.4%    |
| WDC                 | 127       | 149    | 3.15%   |
| Intel               | 109       | 126    | 2.71%   |
| Micron Technology   | 89        | 117    | 2.21%   |
| SK hynix            | 85        | 105    | 2.11%   |
| China               | 77        | 94     | 1.91%   |
| Transcend           | 67        | 78     | 1.66%   |
| LDLC                | 66        | 87     | 1.64%   |
| Toshiba             | 48        | 63     | 1.19%   |
| OCZ                 | 47        | 62     | 1.17%   |
| SPCC                | 39        | 51     | 0.97%   |
| LITEON              | 38        | 41     | 0.94%   |
| Apple               | 37        | 49     | 0.92%   |
| Corsair             | 36        | 42     | 0.89%   |
| LITEONIT            | 32        | 34     | 0.79%   |
| A-DATA Technology   | 31        | 39     | 0.77%   |
| Emtec               | 18        | 20     | 0.45%   |
| KingSpec            | 15        | 18     | 0.37%   |
| Patriot             | 14        | 19     | 0.35%   |
| Unknown             | 14        | 17     | 0.35%   |
| Intenso             | 12        | 13     | 0.3%    |
| Plextor             | 11        | 13     | 0.27%   |
| ASMT                | 11        | 12     | 0.27%   |
| TEXTORM             | 10        | 11     | 0.25%   |
| Dogfish             | 10        | 16     | 0.25%   |
| BHT                 | 10        | 13     | 0.25%   |
| Netac               | 9         | 10     | 0.22%   |
| KingDian            | 9         | 14     | 0.22%   |
| Apacer              | 8         | 8      | 0.2%    |
| Verbatim            | 7         | 7      | 0.17%   |
| BAITITON            | 7         | 7      | 0.17%   |
| Unknown             | 6         | 10     | 0.15%   |
| TCSUNBOW            | 6         | 9      | 0.15%   |
| Seagate             | 6         | 6      | 0.15%   |
| JMicron Technology  | 6         | 7      | 0.15%   |
| GOODRAM             | 6         | 8      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4317      | 7448   | 40.45%  |
| SSD     | 3504      | 5219   | 32.83%  |
| NVMe    | 2291      | 3110   | 21.47%  |
| MMC     | 390       | 528    | 3.65%   |
| Unknown | 171       | 247    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6275      | 12313  | 66.9%   |
| NVMe | 2286      | 3097   | 24.37%  |
| SAS  | 428       | 614    | 4.56%   |
| MMC  | 390       | 528    | 4.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4633      | 7336   | 56.5%   |
| 0.51-1.0   | 2487      | 3605   | 30.33%  |
| 1.01-2.0   | 648       | 1020   | 7.9%    |
| 3.01-4.0   | 190       | 303    | 2.32%   |
| 2.01-3.0   | 133       | 205    | 1.62%   |
| 4.01-10.0  | 93        | 158    | 1.13%   |
| 10.01-20.0 | 16        | 40     | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2166      | 25.22%  |
| 251-500        | 1921      | 22.37%  |
| 501-1000       | 1369      | 15.94%  |
| 1-20           | 710       | 8.27%   |
| 1001-2000      | 691       | 8.05%   |
| 51-100         | 475       | 5.53%   |
| More than 3000 | 388       | 4.52%   |
| 21-50          | 319       | 3.71%   |
| Unknown        | 289       | 3.37%   |
| 2001-3000      | 260       | 3.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3249      | 36.62%  |
| 21-50          | 1362      | 15.35%  |
| 101-250        | 1146      | 12.92%  |
| 51-100         | 1023      | 11.53%  |
| 251-500        | 721       | 8.13%   |
| 501-1000       | 552       | 6.22%   |
| 1001-2000      | 292       | 3.29%   |
| Unknown        | 289       | 3.26%   |
| More than 3000 | 128       | 1.44%   |
| 2001-3000      | 107       | 1.21%   |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 19        | 23     | 1.89%   |
| Seagate ST500DM002-1BD142 500GB       | 12        | 13     | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 12        | 12     | 1.2%    |
| HGST HTS541010A9E680 1TB              | 12        | 13     | 1.2%    |
| Toshiba MQ01ABD100 1TB                | 11        | 13     | 1.1%    |
| Seagate ST9500325AS 500GB             | 11        | 12     | 1.1%    |
| Seagate ST500LM021-1KJ152 500GB       | 11        | 13     | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB              | 8         | 8      | 0.8%    |
| Seagate ST500LT012-1DG142 500GB       | 8         | 8      | 0.8%    |
| Seagate ST2000DM001-1CH164 2TB        | 8         | 9      | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB        | 8         | 8      | 0.8%    |
| WDC WD10EADS-22M2B0 1TB               | 6         | 6      | 0.6%    |
| Seagate ST31000524AS 1TB              | 6         | 6      | 0.6%    |
| Samsung Electronics HD103SJ 1TB       | 6         | 7      | 0.6%    |
| Kingston SV300S37A120G 120GB SSD      | 6         | 8      | 0.6%    |
| HGST HTS725050A7E630 500GB            | 6         | 8      | 0.6%    |
| Crucial CT525MX300SSD1 528GB          | 6         | 6      | 0.6%    |
| Toshiba MQ01ABD050 500GB              | 5         | 5      | 0.5%    |
| Toshiba DT01ACA100 1TB                | 5         | 6      | 0.5%    |
| Seagate ST320LT007-9ZV142 320GB       | 5         | 6      | 0.5%    |
| Seagate ST31000528AS 1TB              | 5         | 5      | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB        | 5         | 5      | 0.5%    |
| LDLC SSD 120GB                        | 5         | 7      | 0.5%    |
| Hitachi HTS727575A9E364 752GB         | 5         | 5      | 0.5%    |
| Hitachi HTS547575A9E384 752GB         | 5         | 5      | 0.5%    |
| Hitachi HTS545050B9A300 500GB         | 5         | 5      | 0.5%    |
| HGST HTS545050A7E680 500GB            | 5         | 5      | 0.5%    |
| WDC WD6400AAKS-22A7B2 640GB           | 4         | 6      | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB           | 4         | 5      | 0.4%    |
| WDC WD3200AAKS-00L9A0 320GB           | 4         | 4      | 0.4%    |
| WDC WD10EADS-65L5B1 1TB               | 4         | 4      | 0.4%    |
| WDC WD10EADS-00M2B0 1TB               | 4         | 6      | 0.4%    |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 0.4%    |
| Toshiba MK5055GSX 500GB               | 4         | 4      | 0.4%    |
| Toshiba MK3265GSX 320GB               | 4         | 5      | 0.4%    |
| SK hynix HFS256G39TND-N210A 256GB SSD | 4         | 4      | 0.4%    |
| Seagate ST3500320AS 500GB             | 4         | 4      | 0.4%    |
| Seagate ST3250310AS 250GB             | 4         | 4      | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB        | 4         | 4      | 0.4%    |
| Seagate ST1000LM048-2E7172 1TB        | 4         | 4      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 241       | 277    | 24.47%  |
| WDC                 | 214       | 260    | 21.73%  |
| Hitachi             | 89        | 98     | 9.04%   |
| Samsung Electronics | 73        | 81     | 7.41%   |
| Toshiba             | 72        | 83     | 7.31%   |
| HGST                | 55        | 62     | 5.58%   |
| Crucial             | 35        | 38     | 3.55%   |
| Maxtor              | 32        | 36     | 3.25%   |
| Kingston            | 28        | 31     | 2.84%   |
| Intel               | 28        | 30     | 2.84%   |
| SK hynix            | 24        | 30     | 2.44%   |
| SanDisk             | 21        | 24     | 2.13%   |
| Fujitsu             | 8         | 8      | 0.81%   |
| OCZ                 | 7         | 8      | 0.71%   |
| LDLC                | 7         | 9      | 0.71%   |
| Micron Technology   | 6         | 8      | 0.61%   |
| LITEONIT            | 4         | 4      | 0.41%   |
| Corsair             | 4         | 5      | 0.41%   |
| A-DATA Technology   | 4         | 4      | 0.41%   |
| China               | 3         | 3      | 0.3%    |
| Apacer              | 3         | 3      | 0.3%    |
| SPCC                | 2         | 2      | 0.2%    |
| Netac               | 2         | 2      | 0.2%    |
| LITEON              | 2         | 2      | 0.2%    |
| KingSpec            | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 2      | 0.2%    |
| Dogfish             | 2         | 2      | 0.2%    |
| Apple               | 2         | 2      | 0.2%    |
| Unknown             | 1         | 1      | 0.1%    |
| TEXTORM             | 1         | 1      | 0.1%    |
| TakeMS              | 1         | 1      | 0.1%    |
| Phison              | 1         | 1      | 0.1%    |
| OCZ-VERTEX          | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| Intenso             | 1         | 1      | 0.1%    |
| INNOVATION IT       | 1         | 1      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |
| ASENNO              | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 241       | 277    | 31.88%  |
| WDC                 | 209       | 255    | 27.65%  |
| Hitachi             | 89        | 98     | 11.77%  |
| Toshiba             | 68        | 79     | 8.99%   |
| HGST                | 55        | 62     | 7.28%   |
| Samsung Electronics | 47        | 52     | 6.22%   |
| Maxtor              | 32        | 36     | 4.23%   |
| Fujitsu             | 8         | 8      | 1.06%   |
| Hewlett-Packard     | 2         | 2      | 0.26%   |
| Unknown             | 1         | 1      | 0.13%   |
| Magnetic Data       | 1         | 1      | 0.13%   |
| IBM/Hitachi         | 1         | 1      | 0.13%   |
| ASMT                | 1         | 1      | 0.13%   |
| Apple               | 1         | 1      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 701       | 874    | 75.62%  |
| SSD     | 205       | 231    | 22.11%  |
| NVMe    | 20        | 23     | 2.16%   |
| Unknown | 1         | 1      | 0.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                     | 2         | 3      | 6.9%    |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 6.9%    |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 6.9%    |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 3.45%   |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 3.45%   |
| WDC WD20EARS-00J99B0 2TB                         | 1         | 2      | 3.45%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 3.45%   |
| WDC WD10EALX-759BA1 1TB                          | 1         | 1      | 3.45%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 3.45%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 3.45%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 3.45%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 2      | 3.45%   |
| SK hynix HFS128G39TND-N210A 128GB SSD            | 1         | 1      | 3.45%   |
| Seagate ST3500418ASQ 500GB                       | 1         | 1      | 3.45%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 3.45%   |
| Seagate ST3300657SS 304GB                        | 1         | 2      | 3.45%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 3.45%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 3.45%   |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 3.45%   |
| Samsung Electronics HD753LJ 752GB                | 1         | 1      | 3.45%   |
| Samsung Electronics HD501LJ 500GB                | 1         | 1      | 3.45%   |
| Kingston SMS200S360G 64GB SSD                    | 1         | 1      | 3.45%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 3.45%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 3.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 11     | 31.03%  |
| Samsung Electronics | 6         | 10     | 20.69%  |
| Toshiba             | 5         | 6      | 17.24%  |
| Seagate             | 5         | 6      | 17.24%  |
| HGST                | 2         | 2      | 6.9%    |
| SK hynix            | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 4033      | 6997   | 44.86%  |
| Detected | 4024      | 8388   | 44.76%  |
| Malfunc  | 903       | 1129   | 10.04%  |
| Failed   | 29        | 37     | 0.32%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5594      | 55.37%  |
| AMD                              | 1429      | 14.14%  |
| Samsung Electronics              | 767       | 7.59%   |
| SanDisk                          | 366       | 3.62%   |
| SK hynix                         | 246       | 2.43%   |
| Nvidia                           | 193       | 1.91%   |
| Toshiba America Info Systems     | 155       | 1.53%   |
| Marvell Technology Group         | 154       | 1.52%   |
| Phison Electronics               | 148       | 1.46%   |
| Micron/Crucial Technology        | 140       | 1.39%   |
| ASMedia Technology               | 131       | 1.3%    |
| JMicron Technology               | 130       | 1.29%   |
| Micron Technology                | 124       | 1.23%   |
| Kingston Technology Company      | 122       | 1.21%   |
| KIOXIA                           | 86        | 0.85%   |
| VIA Technologies                 | 52        | 0.51%   |
| Silicon Motion                   | 38        | 0.38%   |
| Broadcom / LSI                   | 25        | 0.25%   |
| LSI Logic / Symbios Logic        | 23        | 0.23%   |
| Silicon Image                    | 21        | 0.21%   |
| Silicon Integrated Systems [SiS] | 20        | 0.2%    |
| Lite-On Technology               | 19        | 0.19%   |
| Union Memory (Shenzhen)          | 18        | 0.18%   |
| Solid State Storage Technology   | 12        | 0.12%   |
| ADATA Technology                 | 11        | 0.11%   |
| Adaptec                          | 11        | 0.11%   |
| Seagate Technology               | 9         | 0.09%   |
| Yangtze Memory Technologies      | 8         | 0.08%   |
| Realtek Semiconductor            | 6         | 0.06%   |
| Lenovo                           | 6         | 0.06%   |
| Integrated Technology Express    | 6         | 0.06%   |
| Hewlett-Packard                  | 6         | 0.06%   |
| Apple                            | 5         | 0.05%   |
| Shenzhen Longsys Electronics     | 4         | 0.04%   |
| O2 Micro                         | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| Promise Technology               | 2         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.02%   |
| Transcend                        | 1         | 0.01%   |
| Tekram Technology                | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 944       | 8.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 439       | 3.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 378       | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 360       | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 338       | 2.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 273       | 2.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 220       | 1.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 214       | 1.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 208       | 1.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 206       | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 194       | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 190       | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 187       | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 186       | 1.59%   |
| Samsung NVMe SSD Controller 980                                                | 176       | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 169       | 1.45%   |
| Intel SATA Controller [RAID mode]                                              | 166       | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 164       | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 148       | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 144       | 1.23%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 140       | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 131       | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 127       | 1.09%   |
| Micron Non-Volatile memory controller                                          | 124       | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 121       | 1.03%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 120       | 1.03%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 120       | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 114       | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 102       | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                         | 102       | 0.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 99        | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 99        | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 98        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 97        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 94        | 0.8%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 89        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 89        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 88        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 85        | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 78        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5853      | 57.26%  |
| NVMe | 2312      | 22.62%  |
| IDE  | 1228      | 12.01%  |
| RAID | 777       | 7.6%    |
| SAS  | 31        | 0.3%    |
| SCSI | 20        | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6305      | 77.3%   |
| AMD                   | 1787      | 21.91%  |
| ARM                   | 56        | 0.69%   |
| QUALCOMM              | 4         | 0.05%   |
| CentaurHauls          | 3         | 0.04%   |
| Marvell Semiconductor | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 112       | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 77        | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 70        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 70        | 0.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 66        | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 66        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 60        | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 59        | 0.72%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 58        | 0.71%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 55        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 55        | 0.67%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 52        | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 50        | 0.61%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 49        | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 47        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 47        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 47        | 0.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 47        | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 45        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 44        | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 44        | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 40        | 0.49%   |
| ARM Processor                                 | 40        | 0.49%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 38        | 0.46%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 37        | 0.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 36        | 0.44%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 35        | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 34        | 0.42%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 33        | 0.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 32        | 0.39%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 32        | 0.39%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 31        | 0.38%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 31        | 0.38%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 30        | 0.37%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 30        | 0.37%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 0.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 29        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1831      | 22.41%  |
| Intel Core i7           | 1502      | 18.39%  |
| Intel Core i3           | 647       | 7.92%   |
| Other                   | 525       | 6.43%   |
| AMD Ryzen 5             | 406       | 4.97%   |
| Intel Core 2 Duo        | 372       | 4.55%   |
| Intel Celeron           | 362       | 4.43%   |
| AMD Ryzen 7             | 310       | 3.79%   |
| Intel Pentium           | 238       | 2.91%   |
| Intel Xeon              | 209       | 2.56%   |
| Intel Atom              | 164       | 2.01%   |
| Intel Pentium Dual-Core | 111       | 1.36%   |
| AMD FX                  | 90        | 1.1%    |
| Intel Core 2 Quad       | 88        | 1.08%   |
| AMD Ryzen 9             | 88        | 1.08%   |
| AMD Ryzen 3             | 74        | 0.91%   |
| Intel Pentium Dual      | 65        | 0.8%    |
| AMD A4                  | 64        | 0.78%   |
| AMD E1                  | 60        | 0.73%   |
| AMD Athlon II X2        | 60        | 0.73%   |
| Intel Core 2            | 59        | 0.72%   |
| AMD Athlon 64 X2        | 54        | 0.66%   |
| Intel Core i9           | 53        | 0.65%   |
| AMD A8                  | 48        | 0.59%   |
| AMD A6                  | 48        | 0.59%   |
| AMD E2                  | 42        | 0.51%   |
| AMD Phenom II X4        | 39        | 0.48%   |
| AMD Ryzen 7 PRO         | 38        | 0.47%   |
| AMD E                   | 36        | 0.44%   |
| Intel Pentium 4         | 31        | 0.38%   |
| Intel Genuine           | 27        | 0.33%   |
| AMD Athlon              | 27        | 0.33%   |
| AMD Ryzen 5 PRO         | 21        | 0.26%   |
| Intel Pentium Silver    | 20        | 0.24%   |
| Intel Pentium D         | 20        | 0.24%   |
| AMD Athlon 64           | 19        | 0.23%   |
| AMD A10                 | 17        | 0.21%   |
| AMD Sempron             | 16        | 0.2%    |
| AMD Ryzen Threadripper  | 15        | 0.18%   |
| AMD Athlon II           | 15        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3248      | 39.72%  |
| 4       | 3097      | 37.87%  |
| 6       | 766       | 9.37%   |
| 8       | 528       | 6.46%   |
| 1       | 226       | 2.76%   |
| 12      | 110       | 1.35%   |
| 3       | 46        | 0.56%   |
| Unknown | 35        | 0.43%   |
| 10      | 30        | 0.37%   |
| 16      | 28        | 0.34%   |
| 14      | 23        | 0.28%   |
| 20      | 12        | 0.15%   |
| 32      | 9         | 0.11%   |
| 24      | 8         | 0.1%    |
| 64      | 4         | 0.05%   |
| 40      | 2         | 0.02%   |
| 104     | 1         | 0.01%   |
| 48      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8074      | 98.92%  |
| 2       | 80        | 0.98%   |
| Unknown | 5         | 0.06%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5094      | 62.27%  |
| 1       | 3049      | 37.27%  |
| Unknown | 35        | 0.43%   |
| 4       | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7991      | 97.77%  |
| Unknown        | 112       | 1.37%   |
| 32-bit         | 66        | 0.81%   |
| 64-bit         | 4         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1549      | 18.41%  |
| 0x306a9    | 485       | 5.76%   |
| 0x206a7    | 485       | 5.76%   |
| 0x306c3    | 479       | 5.69%   |
| 0x1067a    | 342       | 4.06%   |
| 0x906ea    | 268       | 3.18%   |
| 0x506e3    | 224       | 2.66%   |
| 0x806c1    | 214       | 2.54%   |
| 0x806ec    | 199       | 2.36%   |
| 0x806ea    | 172       | 2.04%   |
| 0x40651    | 163       | 1.94%   |
| 0x306d4    | 159       | 1.89%   |
| 0x906e9    | 155       | 1.84%   |
| 0x406e3    | 149       | 1.77%   |
| 0x806e9    | 144       | 1.71%   |
| 0x20655    | 133       | 1.58%   |
| 0x6fd      | 127       | 1.51%   |
| 0x010000c8 | 97        | 1.15%   |
| 0x08108109 | 96        | 1.14%   |
| 0x10676    | 90        | 1.07%   |
| 0x08701021 | 90        | 1.07%   |
| 0x08600106 | 85        | 1.01%   |
| 0xa0652    | 76        | 0.9%    |
| 0x406c4    | 75        | 0.89%   |
| 0x0800820d | 74        | 0.88%   |
| 0x30678    | 70        | 0.83%   |
| 0x906ed    | 68        | 0.81%   |
| 0x106e5    | 62        | 0.74%   |
| 0x0a50000c | 57        | 0.68%   |
| 0x706e5    | 56        | 0.67%   |
| 0x06001119 | 54        | 0.64%   |
| 0x06000852 | 53        | 0.63%   |
| 0x506c9    | 52        | 0.62%   |
| 0x08701013 | 52        | 0.62%   |
| 0x07030105 | 51        | 0.61%   |
| 0x806eb    | 50        | 0.59%   |
| 0x6fb      | 49        | 0.58%   |
| 0x406c3    | 49        | 0.58%   |
| 0x806d1    | 48        | 0.57%   |
| 0x706a1    | 48        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1310      | 16.04%  |
| Haswell          | 798       | 9.77%   |
| SandyBridge      | 573       | 7.02%   |
| IvyBridge        | 569       | 6.97%   |
| Penryn           | 496       | 6.07%   |
| Skylake          | 487       | 5.96%   |
| Zen 2            | 351       | 4.3%    |
| Core             | 283       | 3.47%   |
| TigerLake        | 256       | 3.14%   |
| Zen+             | 254       | 3.11%   |
| Silvermont       | 243       | 2.98%   |
| Westmere         | 225       | 2.76%   |
| Broadwell        | 208       | 2.55%   |
| Unknown          | 199       | 2.44%   |
| K10              | 186       | 2.28%   |
| CometLake        | 181       | 2.22%   |
| Zen 3            | 174       | 2.13%   |
| Piledriver       | 143       | 1.75%   |
| Zen              | 141       | 1.73%   |
| Icelake          | 131       | 1.6%    |
| K8 Hammer        | 115       | 1.41%   |
| Nehalem          | 106       | 1.3%    |
| Goldmont plus    | 99        | 1.21%   |
| Bobcat           | 80        | 0.98%   |
| Puma             | 75        | 0.92%   |
| Excavator        | 74        | 0.91%   |
| Bonnell          | 69        | 0.85%   |
| Alderlake Hybrid | 69        | 0.85%   |
| Goldmont         | 66        | 0.81%   |
| NetBurst         | 56        | 0.69%   |
| Jaguar           | 46        | 0.56%   |
| K10 Llano        | 25        | 0.31%   |
| P6               | 23        | 0.28%   |
| Steamroller      | 14        | 0.17%   |
| K8 & K10 hybrid  | 12        | 0.15%   |
| Bulldozer        | 12        | 0.15%   |
| Tremont          | 10        | 0.12%   |
| K6               | 5         | 0.06%   |
| Sapphire Rapids  | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4603      | 47.53%  |
| Nvidia                                       | 2987      | 30.84%  |
| AMD                                          | 1996      | 20.61%  |
| Matrox Electronics Systems                   | 47        | 0.49%   |
| ASPEED Technology                            | 24        | 0.25%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.12%   |
| VIA Technologies                             | 9         | 0.09%   |
| ATI Technologies                             | 3         | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| Red Hat                                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 392       | 3.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 308       | 3.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 241       | 2.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 217       | 2.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 187       | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 180       | 1.81%   |
| Intel UHD Graphics 620                                                                   | 174       | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 164       | 1.65%   |
| Intel HD Graphics 530                                                                    | 164       | 1.65%   |
| Intel HD Graphics 620                                                                    | 159       | 1.6%    |
| AMD Renoir                                                                               | 159       | 1.6%    |
| Intel HD Graphics 5500                                                                   | 156       | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 155       | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 154       | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 152       | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 151       | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 145       | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 139       | 1.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 119       | 1.2%    |
| Intel HD Graphics 630                                                                    | 111       | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 100       | 1%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 98        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 97        | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 87        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 87        | 0.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 82        | 0.82%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 80        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 79        | 0.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 78        | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 67        | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 64        | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 64        | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 63        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 60        | 0.6%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 58        | 0.58%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 57        | 0.57%   |
| Intel HD Graphics 500                                                                    | 52        | 0.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 51        | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 50        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 50        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 3156      | 38.38%  |
| 1 x Nvidia           | 1709      | 20.78%  |
| 1 x AMD              | 1571      | 19.1%   |
| Intel + Nvidia       | 1151      | 14%     |
| Intel + AMD          | 196       | 2.38%   |
| 2 x AMD              | 120       | 1.46%   |
| AMD + Nvidia         | 110       | 1.34%   |
| Other                | 69        | 0.84%   |
| 1 x Matrox           | 42        | 0.51%   |
| 2 x Nvidia           | 26        | 0.32%   |
| 1 x ASPEED           | 21        | 0.26%   |
| 2 x Intel            | 14        | 0.17%   |
| 1 x SiS              | 12        | 0.15%   |
| 1 x VIA              | 9         | 0.11%   |
| Nvidia + Matrox      | 4         | 0.05%   |
| 3 x AMD              | 2         | 0.02%   |
| Intel + 2 x Nvidia   | 2         | 0.02%   |
| AMD + ASPEED         | 2         | 0.02%   |
| 3 x Nvidia           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.01%   |
| 1 x XGI              | 1         | 0.01%   |
| 1 x S3 Graphics      | 1         | 0.01%   |
| 1 x Red Hat          | 1         | 0.01%   |
| Nvidia + ASPEED      | 1         | 0.01%   |
| Intel + 2 x AMD      | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6503      | 78.55%  |
| Proprietary | 1414      | 17.08%  |
| Unknown     | 362       | 4.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4362      | 52.12%  |
| 0.01-0.5   | 1117      | 13.35%  |
| 1.01-2.0   | 1054      | 12.59%  |
| 0.51-1.0   | 708       | 8.46%   |
| 3.01-4.0   | 530       | 6.33%   |
| 7.01-8.0   | 256       | 3.06%   |
| 5.01-6.0   | 182       | 2.17%   |
| 8.01-16.0  | 77        | 0.92%   |
| 2.01-3.0   | 69        | 0.82%   |
| 16.01-24.0 | 9         | 0.11%   |
| 4.01-5.0   | 5         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1135      | 12.62%  |
| AU Optronics            | 1099      | 12.22%  |
| LG Display              | 709       | 7.88%   |
| Chimei Innolux          | 699       | 7.77%   |
| BOE                     | 634       | 7.05%   |
| Dell                    | 473       | 5.26%   |
| Iiyama                  | 467       | 5.19%   |
| Hewlett-Packard         | 361       | 4.01%   |
| Acer                    | 314       | 3.49%   |
| Goldstar                | 309       | 3.44%   |
| Ancor Communications    | 249       | 2.77%   |
| Philips                 | 231       | 2.57%   |
| AOC                     | 199       | 2.21%   |
| Sharp                   | 184       | 2.05%   |
| BenQ                    | 177       | 1.97%   |
| Lenovo                  | 151       | 1.68%   |
| Chi Mei Optoelectronics | 142       | 1.58%   |
| Apple                   | 134       | 1.49%   |
| ViewSonic               | 112       | 1.25%   |
| ASUSTek Computer        | 71        | 0.79%   |
| PANDA                   | 70        | 0.78%   |
| InfoVision              | 65        | 0.72%   |
| LG Philips              | 63        | 0.7%    |
| Sony                    | 48        | 0.53%   |
| HannStar                | 47        | 0.52%   |
| Unknown                 | 46        | 0.51%   |
| Packard Bell            | 33        | 0.37%   |
| LG Electronics          | 31        | 0.34%   |
| Idek Iiyama             | 31        | 0.34%   |
| Fujitsu Siemens         | 30        | 0.33%   |
| Vestel Elektronik       | 28        | 0.31%   |
| NEC Computers           | 24        | 0.27%   |
| Toshiba                 | 23        | 0.26%   |
| Eizo                    | 23        | 0.26%   |
| Medion                  | 22        | 0.24%   |
| Hitachi                 | 21        | 0.23%   |
| Panasonic               | 20        | 0.22%   |
| CSO                     | 20        | 0.22%   |
| MSI                     | 18        | 0.2%    |
| Denver                  | 18        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 45        | 0.48%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                     | 41        | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 40        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 33        | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 30        | 0.32%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                          | 28        | 0.3%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 28        | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 26        | 0.28%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 26        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 25        | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 24        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 24        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 23        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 23        | 0.25%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 23        | 0.25%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 21        | 0.23%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 20        | 0.22%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 20        | 0.22%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 20        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 19        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 19        | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 18        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 18        | 0.19%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 17        | 0.18%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 17        | 0.18%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 17        | 0.18%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.18%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 16        | 0.17%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 16        | 0.17%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 16        | 0.17%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                    | 15        | 0.16%   |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                      | 15        | 0.16%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 15        | 0.16%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                         | 15        | 0.16%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 15        | 0.16%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 15        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3868      | 45.33%  |
| 1366x768 (WXGA)    | 1246      | 14.6%   |
| 1600x900 (HD+)     | 541       | 6.34%   |
| 3840x2160 (4K)     | 395       | 4.63%   |
| 2560x1440 (QHD)    | 358       | 4.2%    |
| 1680x1050 (WSXGA+) | 341       | 4%      |
| 1280x1024 (SXGA)   | 328       | 3.84%   |
| 1440x900 (WXGA+)   | 264       | 3.09%   |
| 1920x1200 (WUXGA)  | 260       | 3.05%   |
| 1280x800 (WXGA)    | 187       | 2.19%   |
| Unknown            | 111       | 1.3%    |
| 3440x1440          | 61        | 0.71%   |
| 1360x768           | 54        | 0.63%   |
| 3840x1080          | 51        | 0.6%    |
| 2560x1080          | 49        | 0.57%   |
| 2560x1600          | 39        | 0.46%   |
| 1600x1200          | 32        | 0.38%   |
| 1024x600           | 32        | 0.38%   |
| 2880x1800          | 27        | 0.32%   |
| 2160x1440          | 26        | 0.3%    |
| 1024x768 (XGA)     | 25        | 0.29%   |
| 3840x2400          | 22        | 0.26%   |
| 800x1280           | 20        | 0.23%   |
| 1920x540           | 17        | 0.2%    |
| 3200x1800 (QHD+)   | 12        | 0.14%   |
| 2288x1287          | 10        | 0.12%   |
| 3840x1600          | 9         | 0.11%   |
| 4480x1440          | 8         | 0.09%   |
| 3000x2000          | 8         | 0.09%   |
| 3200x1080          | 7         | 0.08%   |
| 2736x1824          | 7         | 0.08%   |
| 3600x1080          | 6         | 0.07%   |
| 1680x945           | 6         | 0.07%   |
| 5760x2160          | 5         | 0.06%   |
| 5760x1080          | 5         | 0.06%   |
| 3840x1200          | 5         | 0.06%   |
| 1280x720 (HD)      | 5         | 0.06%   |
| 2048x1152          | 4         | 0.05%   |
| 1920x515           | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1977      | 22.07%  |
| 17      | 874       | 9.76%   |
| 13      | 777       | 8.68%   |
| 24      | 728       | 8.13%   |
| 23      | 711       | 7.94%   |
| 27      | 643       | 7.18%   |
| 14      | 533       | 5.95%   |
| 21      | 525       | 5.86%   |
| Unknown | 432       | 4.82%   |
| 19      | 316       | 3.53%   |
| 22      | 231       | 2.58%   |
| 12      | 160       | 1.79%   |
| 20      | 142       | 1.59%   |
| 18      | 138       | 1.54%   |
| 31      | 103       | 1.15%   |
| 34      | 90        | 1%      |
| 11      | 71        | 0.79%   |
| 84      | 60        | 0.67%   |
| 16      | 58        | 0.65%   |
| 10      | 47        | 0.52%   |
| 72      | 41        | 0.46%   |
| 25      | 41        | 0.46%   |
| 40      | 37        | 0.41%   |
| 32      | 37        | 0.41%   |
| 54      | 29        | 0.32%   |
| 26      | 21        | 0.23%   |
| 33      | 19        | 0.21%   |
| 46      | 12        | 0.13%   |
| 48      | 9         | 0.1%    |
| 52      | 8         | 0.09%   |
| 65      | 7         | 0.08%   |
| 49      | 7         | 0.08%   |
| 29      | 7         | 0.08%   |
| 142     | 6         | 0.07%   |
| 39      | 6         | 0.07%   |
| 37      | 6         | 0.07%   |
| 43      | 5         | 0.06%   |
| 42      | 5         | 0.06%   |
| 38      | 5         | 0.06%   |
| 35      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2967      | 33.83%  |
| 501-600        | 1910      | 21.78%  |
| 401-500        | 1158      | 13.2%   |
| 351-400        | 993       | 11.32%  |
| 201-300        | 712       | 8.12%   |
| Unknown        | 432       | 4.93%   |
| 601-700        | 187       | 2.13%   |
| 701-800        | 148       | 1.69%   |
| 1501-2000      | 103       | 1.17%   |
| 1001-1500      | 82        | 0.93%   |
| 801-900        | 60        | 0.68%   |
| 901-1000       | 8         | 0.09%   |
| More than 2000 | 6         | 0.07%   |
| 1-100          | 3         | 0.03%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5964      | 73.92%  |
| 16/10   | 1103      | 13.67%  |
| Unknown | 347       | 4.3%    |
| 5/4     | 308       | 3.82%   |
| 21/9    | 108       | 1.34%   |
| 3/2     | 84        | 1.04%   |
| 4/3     | 79        | 0.98%   |
| 6/5     | 18        | 0.22%   |
| 0.62    | 18        | 0.22%   |
| 32/9    | 15        | 0.19%   |
| 1.00    | 6         | 0.07%   |
| 3.20    | 4         | 0.05%   |
| 3.73    | 3         | 0.04%   |
| 0.67    | 3         | 0.04%   |
| 11/10   | 2         | 0.02%   |
| 0.56    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1987      | 22.44%  |
| 201-250        | 1754      | 19.81%  |
| 81-90          | 938       | 10.59%  |
| 301-350        | 665       | 7.51%   |
| 151-200        | 632       | 7.14%   |
| 121-130        | 611       | 6.9%    |
| Unknown        | 432       | 4.88%   |
| 71-80          | 384       | 4.34%   |
| 251-300        | 272       | 3.07%   |
| 351-500        | 256       | 2.89%   |
| 141-150        | 238       | 2.69%   |
| More than 1000 | 163       | 1.84%   |
| 61-70          | 138       | 1.56%   |
| 131-140        | 113       | 1.28%   |
| 501-1000       | 94        | 1.06%   |
| 51-60          | 71        | 0.8%    |
| 41-50          | 48        | 0.54%   |
| 111-120        | 39        | 0.44%   |
| 91-100         | 15        | 0.17%   |
| 1-40           | 5         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3114      | 36.15%  |
| 101-120       | 2191      | 25.43%  |
| 121-160       | 2148      | 24.93%  |
| 161-240       | 444       | 5.15%   |
| Unknown       | 432       | 5.01%   |
| More than 240 | 158       | 1.83%   |
| 1-50          | 128       | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6470      | 77.63%  |
| 2     | 1310      | 15.72%  |
| 0     | 400       | 4.8%    |
| 3     | 145       | 1.74%   |
| 4     | 7         | 0.08%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4370      | 35.98%  |
| Intel                             | 3880      | 31.95%  |
| Qualcomm Atheros                  | 1468      | 12.09%  |
| Broadcom                          | 691       | 5.69%   |
| Marvell Technology Group          | 176       | 1.45%   |
| Nvidia                            | 143       | 1.18%   |
| Broadcom Limited                  | 140       | 1.15%   |
| Ralink                            | 136       | 1.12%   |
| MediaTek                          | 111       | 0.91%   |
| TP-Link                           | 95        | 0.78%   |
| Ralink Technology                 | 72        | 0.59%   |
| NetGear                           | 68        | 0.56%   |
| ASIX Electronics                  | 59        | 0.49%   |
| Samsung Electronics               | 55        | 0.45%   |
| Dell                              | 44        | 0.36%   |
| D-Link System                     | 37        | 0.3%    |
| Xiaomi                            | 34        | 0.28%   |
| DisplayLink                       | 27        | 0.22%   |
| Huawei Technologies               | 26        | 0.21%   |
| Ericsson Business Mobile Networks | 26        | 0.21%   |
| D-Link                            | 26        | 0.21%   |
| VIA Technologies                  | 25        | 0.21%   |
| Sierra Wireless                   | 24        | 0.2%    |
| Aquantia                          | 23        | 0.19%   |
| Qualcomm                          | 22        | 0.18%   |
| Microsoft                         | 22        | 0.18%   |
| Lenovo                            | 21        | 0.17%   |
| JMicron Technology                | 21        | 0.17%   |
| Belkin Components                 | 21        | 0.17%   |
| Qualcomm Atheros Communications   | 16        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.12%   |
| Attansic Technology               | 14        | 0.12%   |
| Hewlett-Packard                   | 12        | 0.1%    |
| OPPO                              | 11        | 0.09%   |
| Guillemot                         | 11        | 0.09%   |
| Google                            | 11        | 0.09%   |
| ASUSTek Computer                  | 11        | 0.09%   |
| Edimax Technology                 | 10        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.07%   |
| Microchip Technology              | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3019      | 21.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 433       | 3.04%   |
| Intel Wi-Fi 6 AX200                                               | 342       | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 298       | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 272       | 1.91%   |
| Intel Wireless 8265 / 8275                                        | 219       | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 205       | 1.44%   |
| Intel Wi-Fi 6 AX201                                               | 199       | 1.4%    |
| Intel Wireless 7265                                               | 197       | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 175       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 174       | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 166       | 1.17%   |
| Intel Wireless 8260                                               | 159       | 1.12%   |
| Intel Wireless 7260                                               | 157       | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 144       | 1.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 140       | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 138       | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 131       | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 129       | 0.91%   |
| Intel Ethernet Connection (2) I219-V                              | 125       | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 122       | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 117       | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 115       | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 114       | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 112       | 0.79%   |
| Intel Wireless 3165                                               | 106       | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 103       | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 92        | 0.65%   |
| Intel Wireless-AC 9260                                            | 88        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 86        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 84        | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 84        | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 79        | 0.55%   |
| Intel Ethernet Connection (7) I219-V                              | 78        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 77        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 71        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                     | 71        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 68        | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 66        | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 63        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2878      | 45.92%  |
| Qualcomm Atheros                      | 1123      | 17.92%  |
| Realtek Semiconductor                 | 1055      | 16.83%  |
| Broadcom                              | 419       | 6.68%   |
| Ralink                                | 136       | 2.17%   |
| TP-Link                               | 89        | 1.42%   |
| MediaTek                              | 82        | 1.31%   |
| Broadcom Limited                      | 81        | 1.29%   |
| Ralink Technology                     | 72        | 1.15%   |
| NetGear                               | 64        | 1.02%   |
| D-Link                                | 25        | 0.4%    |
| Sierra Wireless                       | 24        | 0.38%   |
| Microsoft                             | 22        | 0.35%   |
| Dell                                  | 21        | 0.34%   |
| Belkin Components                     | 21        | 0.34%   |
| D-Link System                         | 20        | 0.32%   |
| Marvell Technology Group              | 17        | 0.27%   |
| Qualcomm Atheros Communications       | 16        | 0.26%   |
| Qualcomm                              | 13        | 0.21%   |
| Guillemot                             | 11        | 0.18%   |
| ASUSTek Computer                      | 11        | 0.18%   |
| Edimax Technology                     | 10        | 0.16%   |
| Fibocom                               | 7         | 0.11%   |
| Ericsson Business Mobile Networks     | 7         | 0.11%   |
| Hewlett-Packard                       | 6         | 0.1%    |
| Sagem                                 | 5         | 0.08%   |
| IMC Networks                          | 5         | 0.08%   |
| TRENDnet                              | 4         | 0.06%   |
| Gemtek                                | 4         | 0.06%   |
| Accton Technology                     | 3         | 0.05%   |
| ZyDAS                                 | 2         | 0.03%   |
| Toshiba                               | 2         | 0.03%   |
| Linksys                               | 2         | 0.03%   |
| Fujitsu Siemens Computers             | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| Z-Com                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Tenda                                 | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 342       | 5.42%   |
| Intel Wireless 8265 / 8275                                              | 219       | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 205       | 3.25%   |
| Intel Wi-Fi 6 AX201                                                     | 199       | 3.16%   |
| Intel Wireless 7265                                                     | 197       | 3.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 175       | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 174       | 2.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 166       | 2.63%   |
| Intel Wireless 8260                                                     | 159       | 2.52%   |
| Intel Wireless 7260                                                     | 157       | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 144       | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 140       | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 131       | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 122       | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 115       | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 114       | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 112       | 1.78%   |
| Intel Wireless 3165                                                     | 106       | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 103       | 1.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 92        | 1.46%   |
| Intel Wireless-AC 9260                                                  | 88        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 86        | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 79        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 71        | 1.13%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 63        | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 60        | 0.95%   |
| Intel Wireless 3160                                                     | 58        | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 58        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 57        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 56        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 55        | 0.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 54        | 0.86%   |
| Intel WiFi Link 5100                                                    | 52        | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 52        | 0.82%   |
| Intel Centrino Wireless-N 2230                                          | 50        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 49        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 47        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 46        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 46        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 44        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3977      | 52.14%  |
| Intel                            | 1976      | 25.91%  |
| Qualcomm Atheros                 | 508       | 6.66%   |
| Broadcom                         | 338       | 4.43%   |
| Marvell Technology Group         | 159       | 2.08%   |
| Nvidia                           | 143       | 1.87%   |
| Broadcom Limited                 | 62        | 0.81%   |
| ASIX Electronics                 | 59        | 0.77%   |
| Samsung Electronics              | 54        | 0.71%   |
| Xiaomi                           | 34        | 0.45%   |
| MediaTek                         | 27        | 0.35%   |
| DisplayLink                      | 27        | 0.35%   |
| Aquantia                         | 23        | 0.3%    |
| VIA Technologies                 | 22        | 0.29%   |
| Lenovo                           | 21        | 0.28%   |
| JMicron Technology               | 21        | 0.28%   |
| Huawei Technologies              | 20        | 0.26%   |
| D-Link System                    | 17        | 0.22%   |
| Attansic Technology              | 14        | 0.18%   |
| Silicon Integrated Systems [SiS] | 13        | 0.17%   |
| OPPO                             | 11        | 0.14%   |
| Google                           | 11        | 0.14%   |
| Qualcomm                         | 9         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 7         | 0.09%   |
| ICS Advent                       | 7         | 0.09%   |
| TP-Link                          | 6         | 0.08%   |
| Microchip Technology             | 5         | 0.07%   |
| Apple                            | 5         | 0.07%   |
| NetGear                          | 4         | 0.05%   |
| Motorola PCS                     | 4         | 0.05%   |
| Mellanox Technologies            | 4         | 0.05%   |
| 3Com                             | 4         | 0.05%   |
| QLogic                           | 3         | 0.04%   |
| Linksys                          | 3         | 0.04%   |
| HTC (High Tech Computer)         | 3         | 0.04%   |
| Dell                             | 2         | 0.03%   |
| Cypress Semiconductor            | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.01%   |
| ULi Electronics                  | 1         | 0.01%   |
| Tehuti Networks                  | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3019      | 38.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 433       | 5.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 298       | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 272       | 3.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 138       | 1.77%   |
| Intel I211 Gigabit Network Connection                             | 129       | 1.65%   |
| Intel Ethernet Connection (2) I219-V                              | 125       | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 117       | 1.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 84        | 1.08%   |
| Intel 82579V Gigabit Network Connection                           | 84        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                              | 78        | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 77        | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 71        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 68        | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 66        | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 58        | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 57        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 55        | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 55        | 0.7%    |
| Nvidia MCP61 Ethernet                                             | 52        | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 52        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                              | 50        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 49        | 0.63%   |
| Intel Ethernet Controller I225-V                                  | 48        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 44        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 43        | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 41        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 41        | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 41        | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 40        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 39        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 38        | 0.49%   |
| Intel 82567LM Gigabit Network Connection                          | 37        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 36        | 0.46%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 36        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 35        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 35        | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 35        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7147      | 53.8%   |
| WiFi     | 6003      | 45.19%  |
| Modem    | 119       | 0.9%    |
| Unknown  | 15        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4439      | 52.18%  |
| Ethernet | 4068      | 47.82%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4474      | 54.58%  |
| 1     | 3378      | 41.21%  |
| 3     | 153       | 1.87%   |
| 0     | 151       | 1.84%   |
| 4     | 30        | 0.37%   |
| 5     | 5         | 0.06%   |
| 8     | 3         | 0.04%   |
| 6     | 3         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5397      | 64.3%   |
| Yes  | 2997      | 35.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2306      | 49.7%   |
| Realtek Semiconductor           | 365       | 7.87%   |
| IMC Networks                    | 309       | 6.66%   |
| Cambridge Silicon Radio         | 302       | 6.51%   |
| Qualcomm Atheros Communications | 272       | 5.86%   |
| Broadcom                        | 225       | 4.85%   |
| Apple                           | 143       | 3.08%   |
| Lite-On Technology              | 138       | 2.97%   |
| Foxconn / Hon Hai               | 127       | 2.74%   |
| ASUSTek Computer                | 89        | 1.92%   |
| Dell                            | 81        | 1.75%   |
| Realtek                         | 44        | 0.95%   |
| Toshiba                         | 37        | 0.8%    |
| Hewlett-Packard                 | 37        | 0.8%    |
| Ralink                          | 32        | 0.69%   |
| Ralink Technology               | 19        | 0.41%   |
| MediaTek                        | 17        | 0.37%   |
| Belkin Components               | 15        | 0.32%   |
| Marvell Semiconductor           | 13        | 0.28%   |
| Foxconn International           | 13        | 0.28%   |
| Alps Electric                   | 13        | 0.28%   |
| TP-Link                         | 10        | 0.22%   |
| Integrated System Solution      | 6         | 0.13%   |
| USI                             | 5         | 0.11%   |
| Chicony Electronics             | 5         | 0.11%   |
| HTC (High Tech Computer)        | 3         | 0.06%   |
| Fujitsu                         | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| TRENDnet                        | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 852       | 18.35%  |
| Intel AX201 Bluetooth                               | 457       | 9.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 350       | 7.54%   |
| Intel AX200 Bluetooth                               | 319       | 6.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 302       | 6.51%   |
| Realtek Bluetooth Radio                             | 238       | 5.13%   |
| IMC Networks Bluetooth Device                       | 120       | 2.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 102       | 2.2%    |
| IMC Networks Bluetooth Radio                        | 95        | 2.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 90        | 1.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 79        | 1.7%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 72        | 1.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 57        | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 54        | 1.16%   |
| Apple Bluetooth Host Controller                     | 51        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 50        | 1.08%   |
| Intel Bluetooth Device                              | 50        | 1.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 49        | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 47        | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 46        | 0.99%   |
| Apple Bluetooth USB Host Controller                 | 45        | 0.97%   |
| Intel AX210 Bluetooth                               | 41        | 0.88%   |
| Lite-On Bluetooth Device                            | 39        | 0.84%   |
| Dell DW375 Bluetooth Module                         | 36        | 0.78%   |
| Realtek 802.11ac WLAN Adapter                       | 34        | 0.73%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 33        | 0.71%   |
| Ralink RT3290 Bluetooth                             | 32        | 0.69%   |
| IMC Networks Wireless_Device                        | 31        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 29        | 0.62%   |
| Foxconn / Hon Hai Wireless_Device                   | 28        | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 25        | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 25        | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 24        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 22        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.43%   |
| Apple Bluetooth HCI                                 | 20        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth Device                | 19        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5971      | 52.25%  |
| AMD                              | 2143      | 18.75%  |
| Nvidia                           | 2132      | 18.66%  |
| C-Media Electronics              | 166       | 1.45%   |
| Logitech                         | 106       | 0.93%   |
| Creative Labs                    | 75        | 0.66%   |
| Realtek Semiconductor            | 64        | 0.56%   |
| GN Netcom                        | 62        | 0.54%   |
| JMTek                            | 42        | 0.37%   |
| Texas Instruments                | 41        | 0.36%   |
| Kingston Technology              | 41        | 0.36%   |
| Corsair                          | 41        | 0.36%   |
| Plantronics                      | 40        | 0.35%   |
| VIA Technologies                 | 35        | 0.31%   |
| Focusrite-Novation               | 28        | 0.25%   |
| SteelSeries ApS                  | 25        | 0.22%   |
| Silicon Integrated Systems [SiS] | 19        | 0.17%   |
| Razer USA                        | 19        | 0.17%   |
| Lenovo                           | 19        | 0.17%   |
| Generalplus Technology           | 18        | 0.16%   |
| Hewlett-Packard                  | 15        | 0.13%   |
| Sennheiser Communications        | 13        | 0.11%   |
| XMOS                             | 12        | 0.11%   |
| DSEA A/S                         | 11        | 0.1%    |
| Creative Technology              | 11        | 0.1%    |
| ASUSTek Computer                 | 11        | 0.1%    |
| M-Audio                          | 9         | 0.08%   |
| Sony                             | 8         | 0.07%   |
| RODE Microphones                 | 8         | 0.07%   |
| BEHRINGER International          | 8         | 0.07%   |
| Ensoniq                          | 7         | 0.06%   |
| Dell                             | 7         | 0.06%   |
| Tenx Technology                  | 6         | 0.05%   |
| PreSonus Audio Electronics       | 6         | 0.05%   |
| GYROCOM C&C                      | 6         | 0.05%   |
| Alesis                           | 6         | 0.05%   |
| Yamaha                           | 5         | 0.04%   |
| Turtle Beach                     | 5         | 0.04%   |
| Micro Star International         | 5         | 0.04%   |
| Medeli Electronics               | 5         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 564       | 4.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 542       | 4.05%   |
| AMD Family 17h/19h HD Audio Controller                                     | 530       | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 516       | 3.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 475       | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 373       | 2.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 357       | 2.67%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 301       | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 294       | 2.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 280       | 2.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 269       | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 265       | 1.98%   |
| AMD FCH Azalia Controller                                                  | 258       | 1.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 255       | 1.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 251       | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 234       | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 206       | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 202       | 1.51%   |
| Intel 8 Series HD Audio Controller                                         | 191       | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 188       | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 186       | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 182       | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 174       | 1.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 172       | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 166       | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                               | 157       | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 149       | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                   | 135       | 1.01%   |
| Nvidia High Definition Audio Controller                                    | 126       | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 126       | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 125       | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 124       | 0.93%   |
| Nvidia TU106 High Definition Audio Controller                              | 112       | 0.84%   |
| Nvidia GP106 High Definition Audio Controller                              | 105       | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 99        | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 99        | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 97        | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 96        | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 93        | 0.7%    |
| Intel CM238 HD Audio Controller                                            | 92        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1336      | 21.99%  |
| SK hynix            | 1196      | 19.68%  |
| Unknown             | 623       | 10.25%  |
| Kingston            | 623       | 10.25%  |
| Micron Technology   | 582       | 9.58%   |
| Corsair             | 411       | 6.76%   |
| Crucial             | 390       | 6.42%   |
| G.Skill             | 292       | 4.81%   |
| Elpida              | 91        | 1.5%    |
| Ramaxel Technology  | 87        | 1.43%   |
| Nanya Technology    | 85        | 1.4%    |
| A-DATA Technology   | 59        | 0.97%   |
| Unknown (ABCD)      | 55        | 0.91%   |
| Transcend           | 31        | 0.51%   |
| Unknown             | 25        | 0.41%   |
| Team                | 16        | 0.26%   |
| Patriot             | 16        | 0.26%   |
| PNY                 | 15        | 0.25%   |
| Unifosa             | 12        | 0.2%    |
| Timetec             | 8         | 0.13%   |
| ASint Technology    | 8         | 0.13%   |
| Unknown (0x0C97)    | 6         | 0.1%    |
| Qimonda             | 6         | 0.1%    |
| Toshiba             | 5         | 0.08%   |
| TEXTORM             | 5         | 0.08%   |
| Apacer              | 5         | 0.08%   |
| Hewlett-Packard     | 4         | 0.07%   |
| V-Color             | 3         | 0.05%   |
| Swissbit            | 3         | 0.05%   |
| Silicon Power       | 3         | 0.05%   |
| SHARETRONIC         | 3         | 0.05%   |
| OCZ                 | 3         | 0.05%   |
| Lexar               | 3         | 0.05%   |
| Innodisk            | 3         | 0.05%   |
| Unknown (F301)      | 2         | 0.03%   |
| Unknown (07FB)      | 2         | 0.03%   |
| Ramos Technology    | 2         | 0.03%   |
| Kllisre             | 2         | 0.03%   |
| KLEVV               | 2         | 0.03%   |
| Goldkey             | 2         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 55        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 54        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 51        | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 50        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 48        | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 46        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 43        | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 40        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 37        | 0.57%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 36        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 36        | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 34        | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 30        | 0.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 30        | 0.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 30        | 0.46%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 26        | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.4%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.39%   |
| Unknown                                                          | 25        | 0.39%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 21        | 0.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 19        | 0.29%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.29%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.29%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.28%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 18        | 0.28%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.28%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 18        | 0.28%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 17        | 0.26%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 17        | 0.26%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s             | 17        | 0.26%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 16        | 0.25%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.25%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 16        | 0.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2300      | 43.48%  |
| DDR3    | 1923      | 36.35%  |
| DDR2    | 311       | 5.88%   |
| SDRAM   | 183       | 3.46%   |
| LPDDR4  | 179       | 3.38%   |
| Unknown | 154       | 2.91%   |
| LPDDR3  | 120       | 2.27%   |
| DDR     | 57        | 1.08%   |
| DDR5    | 28        | 0.53%   |
| LPDDR5  | 24        | 0.45%   |
| DRAM    | 9         | 0.17%   |
| RAM     | 1         | 0.02%   |
| EEPROM  | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2910      | 55.51%  |
| DIMM         | 1972      | 37.62%  |
| Row Of Chips | 316       | 6.03%   |
| Chip         | 20        | 0.38%   |
| Unknown      | 9         | 0.17%   |
| FB-DIMM      | 8         | 0.15%   |
| RIMM         | 7         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2017      | 35.15%  |
| 4096  | 1785      | 31.11%  |
| 2048  | 839       | 14.62%  |
| 16384 | 690       | 12.03%  |
| 1024  | 261       | 4.55%   |
| 32768 | 101       | 1.76%   |
| 512   | 38        | 0.66%   |
| 65536 | 3         | 0.05%   |
| 256   | 3         | 0.05%   |
| 1     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1239      | 21.75%  |
| 2667    | 785       | 13.78%  |
| 3200    | 735       | 12.9%   |
| 2400    | 402       | 7.06%   |
| 1333    | 399       | 7%      |
| 2133    | 293       | 5.14%   |
| 1334    | 174       | 3.05%   |
| 667     | 168       | 2.95%   |
| 800     | 150       | 2.63%   |
| 1867    | 116       | 2.04%   |
| 3600    | 108       | 1.9%    |
| Unknown | 101       | 1.77%   |
| 4267    | 80        | 1.4%    |
| 1066    | 80        | 1.4%    |
| 1067    | 68        | 1.19%   |
| 3266    | 65        | 1.14%   |
| 2933    | 45        | 0.79%   |
| 1866    | 45        | 0.79%   |
| 3000    | 44        | 0.77%   |
| 2048    | 44        | 0.77%   |
| 2666    | 38        | 0.67%   |
| 4199    | 33        | 0.58%   |
| 3400    | 33        | 0.58%   |
| 533     | 33        | 0.58%   |
| 4800    | 31        | 0.54%   |
| 1800    | 31        | 0.54%   |
| 3466    | 29        | 0.51%   |
| 6400    | 25        | 0.44%   |
| 400     | 22        | 0.39%   |
| 3733    | 21        | 0.37%   |
| 975     | 19        | 0.33%   |
| 2800    | 18        | 0.32%   |
| 3800    | 16        | 0.28%   |
| 333     | 14        | 0.25%   |
| 4266    | 13        | 0.23%   |
| 3666    | 13        | 0.23%   |
| 2465    | 12        | 0.21%   |
| 1639    | 12        | 0.21%   |
| 3866    | 10        | 0.18%   |
| 2000    | 10        | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 105       | 44.3%   |
| Canon                 | 39        | 16.46%  |
| Brother Industries    | 34        | 14.35%  |
| Samsung Electronics   | 28        | 11.81%  |
| Seiko Epson           | 17        | 7.17%   |
| Prolific Technology   | 3         | 1.27%   |
| STMicroelectronics    | 2         | 0.84%   |
| Ricoh                 | 2         | 0.84%   |
| QinHeng Electronics   | 2         | 0.84%   |
| Xiaomi                | 1         | 0.42%   |
| Xerox                 | 1         | 0.42%   |
| Lexmark International | 1         | 0.42%   |
| Kyocera               | 1         | 0.42%   |
| Apple                 | 1         | 0.42%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 9         | 3.78%   |
| HP ENVY 4520 series                                       | 9         | 3.78%   |
| HP DeskJet 3630 series                                    | 9         | 3.78%   |
| HP DeskJet 2700 series                                    | 9         | 3.78%   |
| HP ENVY Photo 6200 series                                 | 6         | 2.52%   |
| Canon PIXMA MG3600 Series                                 | 6         | 2.52%   |
| HP ENVY 5000 series                                       | 4         | 1.68%   |
| HP DeskJet Plus 4100 series                               | 4         | 1.68%   |
| HP DeskJet 3700 series                                    | 4         | 1.68%   |
| HP DeskJet 2620 All-in-One Printer                        | 4         | 1.68%   |
| Brother HL-2030 Laser Printer                             | 4         | 1.68%   |
| Seiko Epson XP-243 245 247 Series                         | 3         | 1.26%   |
| Samsung M2020 Series                                      | 3         | 1.26%   |
| Prolific PL2305 Parallel Port                             | 3         | 1.26%   |
| HP OfficeJet 3830 series                                  | 3         | 1.26%   |
| HP Deskjet 3050A                                          | 3         | 1.26%   |
| Canon PIXMA MG2500 Series                                 | 3         | 1.26%   |
| Brother Printer                                           | 3         | 1.26%   |
| Brother MFC-L2710DW series                                | 3         | 1.26%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 0.84%   |
| Seiko Epson XP-255 257 Series                             | 2         | 0.84%   |
| Seiko Epson XP-2100 Series                                | 2         | 0.84%   |
| Seiko Epson WF-2830 Series                                | 2         | 0.84%   |
| Samsung SCX-3400 Series                                   | 2         | 0.84%   |
| Samsung SCX-3200 Series                                   | 2         | 0.84%   |
| Samsung CLX-3180 Series                                   | 2         | 0.84%   |
| Samsung CLX-3170 Series                                   | 2         | 0.84%   |
| QinHeng CH340S                                            | 2         | 0.84%   |
| HP OfficeJet Pro 69                                       | 2         | 0.84%   |
| HP ENVY 5540 series                                       | 2         | 0.84%   |
| HP ENVY 4500 series                                       | 2         | 0.84%   |
| HP DeskJet F4200 series                                   | 2         | 0.84%   |
| HP DeskJet 5550                                           | 2         | 0.84%   |
| HP Deskjet 3070 B611 series                               | 2         | 0.84%   |
| HP Deskjet 1510                                           | 2         | 0.84%   |
| Canon TS5100 series                                       | 2         | 0.84%   |
| Canon PIXMA MP270 All-In-One Printer                      | 2         | 0.84%   |
| Canon PIXMA MG3500 Series                                 | 2         | 0.84%   |
| Canon iP7200 series                                       | 2         | 0.84%   |
| Brother MFC-J5335DW                                       | 2         | 0.84%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 52        | 62.65%  |
| Seiko Epson     | 20        | 24.1%   |
| Hewlett-Packard | 8         | 9.64%   |
| AGFA-Gevaert NV | 3         | 3.61%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                 | 9         | 10.84%  |
| Canon CanoScan LiDE 110                                       | 9         | 10.84%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 8         | 9.64%   |
| Canon CanoScan LIDE 25                                        | 7         | 8.43%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4         | 4.82%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3         | 3.61%   |
| Canon CanoScan LiDE 200                                       | 3         | 3.61%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2         | 2.41%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2         | 2.41%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2         | 2.41%   |
| HP ScanJet 3570c                                              | 2         | 2.41%   |
| Canon CanoScan N650U/N656U                                    | 2         | 2.41%   |
| Canon CanoScan LiDE 60                                        | 2         | 2.41%   |
| Canon CanoScan LiDE 220                                       | 2         | 2.41%   |
| Canon CanoScan LiDE 210                                       | 2         | 2.41%   |
| AGFA-Gevaert NV SnapScan e20                                  | 2         | 2.41%   |
| Seiko Epson Scanner                                           | 1         | 1.2%    |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                   | 1         | 1.2%    |
| Seiko Epson GT-F700 [Perfection V350]                         | 1         | 1.2%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1         | 1.2%    |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1         | 1.2%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 1         | 1.2%    |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 1.2%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 1         | 1.2%    |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1         | 1.2%    |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1         | 1.2%    |
| HP ScanJet G4010                                              | 1         | 1.2%    |
| HP ScanJet 5200c                                              | 1         | 1.2%    |
| HP ScanJet 4570c                                              | 1         | 1.2%    |
| HP ScanJet 3500c                                              | 1         | 1.2%    |
| HP ScanJet 2300c                                              | 1         | 1.2%    |
| HP PSC 1200                                                   | 1         | 1.2%    |
| Canon CanoScan LiDE 70                                        | 1         | 1.2%    |
| Canon CanoScan LiDE 120                                       | 1         | 1.2%    |
| Canon CanoScan 9000F Mark II                                  | 1         | 1.2%    |
| Canon CanoScan 4400F                                          | 1         | 1.2%    |
| Canon CanoScan 4200F                                          | 1         | 1.2%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 1.2%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1042      | 21.52%  |
| IMC Networks                           | 494       | 10.2%   |
| Microdia                               | 449       | 9.27%   |
| Realtek Semiconductor                  | 420       | 8.67%   |
| Acer                                   | 348       | 7.19%   |
| Logitech                               | 327       | 6.75%   |
| Sunplus Innovation Technology          | 276       | 5.7%    |
| Suyin                                  | 174       | 3.59%   |
| Cheng Uei Precision Industry (Foxlink) | 172       | 3.55%   |
| Quanta                                 | 154       | 3.18%   |
| Apple                                  | 136       | 2.81%   |
| Lite-On Technology                     | 110       | 2.27%   |
| Syntek                                 | 94        | 1.94%   |
| Alcor Micro                            | 58        | 1.2%    |
| Samsung Electronics                    | 51        | 1.05%   |
| Microsoft                              | 49        | 1.01%   |
| Luxvisions Innotech Limited            | 47        | 0.97%   |
| Ricoh                                  | 45        | 0.93%   |
| Silicon Motion                         | 42        | 0.87%   |
| Guillemot                              | 24        | 0.5%    |
| Sonix Technology                       | 23        | 0.47%   |
| Lenovo                                 | 21        | 0.43%   |
| Z-Star Microelectronics                | 18        | 0.37%   |
| Primax Electronics                     | 18        | 0.37%   |
| Importek                               | 15        | 0.31%   |
| GEMBIRD                                | 15        | 0.31%   |
| DigiTech                               | 14        | 0.29%   |
| Creative Technology                    | 14        | 0.29%   |
| Generalplus Technology                 | 13        | 0.27%   |
| ARC International                      | 13        | 0.27%   |
| ALi                                    | 11        | 0.23%   |
| Hewlett-Packard                        | 10        | 0.21%   |
| KYE Systems (Mouse Systems)            | 7         | 0.14%   |
| Bison Electronics                      | 7         | 0.14%   |
| 2M UVC CAMERA                          | 7         | 0.14%   |
| OmniVision Technologies                | 6         | 0.12%   |
| icSpring                               | 6         | 0.12%   |
| Cubeternet                             | 6         | 0.12%   |
| Y Media                                | 5         | 0.1%    |
| Jieli Technology                       | 5         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 220       | 4.52%   |
| Realtek Integrated_Webcam_HD             | 183       | 3.76%   |
| Chicony Integrated Camera                | 160       | 3.29%   |
| IMC Networks USB2.0 HD UVC WebCam        | 114       | 2.34%   |
| Chicony HD Webcam                        | 103       | 2.12%   |
| IMC Networks Integrated Camera           | 89        | 1.83%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 87        | 1.79%   |
| Acer Integrated Camera                   | 81        | 1.66%   |
| Logitech Webcam C270                     | 71        | 1.46%   |
| Sunplus Integrated_Webcam_HD             | 68        | 1.4%    |
| Samsung Galaxy A5 (MTP)                  | 51        | 1.05%   |
| Acer HD Webcam                           | 49        | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam            | 47        | 0.97%   |
| Realtek USB Camera                       | 46        | 0.94%   |
| Chicony USB2.0 Camera                    | 46        | 0.94%   |
| Apple Built-in iSight                    | 45        | 0.92%   |
| Chicony HP HD Camera                     | 44        | 0.9%    |
| Syntek Integrated Camera                 | 41        | 0.84%   |
| Chicony USB2.0 HD UVC WebCam             | 41        | 0.84%   |
| Sunplus Asus Webcam                      | 40        | 0.82%   |
| Chicony TOSHIBA Web Camera - HD          | 40        | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE                | 40        | 0.82%   |
| Microdia Integrated Webcam               | 39        | 0.8%    |
| Acer BisonCam,NB Pro                     | 38        | 0.78%   |
| Logitech HD Pro Webcam C920              | 36        | 0.74%   |
| Chicony HP Truevision HD                 | 36        | 0.74%   |
| Chicony USB 2.0 Camera                   | 35        | 0.72%   |
| Chicony HP HD Webcam                     | 35        | 0.72%   |
| Realtek USB2.0 HD UVC WebCam             | 33        | 0.68%   |
| Lite-On Integrated Camera                | 33        | 0.68%   |
| Chicony HP Truevision HD camera          | 33        | 0.68%   |
| Acer BisonCam, NB Pro                    | 33        | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 29        | 0.6%    |
| Logitech HD Webcam C525                  | 29        | 0.6%    |
| Sunplus HD WebCam                        | 27        | 0.55%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 27        | 0.55%   |
| Acer Lenovo EasyCamera                   | 27        | 0.55%   |
| Chicony VGA Webcam                       | 26        | 0.53%   |
| Quanta HP HD Camera                      | 25        | 0.51%   |
| IMC Networks UVC VGA Webcam              | 25        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 280       | 35.04%  |
| Synaptics                  | 182       | 22.78%  |
| Shenzhen Goodix Technology | 151       | 18.9%   |
| AuthenTec                  | 62        | 7.76%   |
| Elan Microelectronics      | 44        | 5.51%   |
| LighTuning Technology      | 38        | 4.76%   |
| Upek                       | 30        | 3.75%   |
| STMicroelectronics         | 11        | 1.38%   |
| Focal-systems.Corp         | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 77        | 9.64%   |
| Shenzhen Goodix  Fingerprint Device                                        | 76        | 9.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 64        | 8.01%   |
| Unknown                                                                    | 55        | 6.88%   |
| Shenzhen Goodix FingerPrint                                                | 39        | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 4.51%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 4.13%   |
| Elan ELAN:Fingerprint                                                      | 33        | 4.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 3.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 3.25%   |
| Validity Sensors VFS491                                                    | 23        | 2.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 2.88%   |
| AuthenTec AES2810                                                          | 22        | 2.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 2.13%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 2.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2%      |
| AuthenTec AES1600                                                          | 14        | 1.75%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.63%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 1.63%   |
| AuthenTec Fingerprint Sensor                                               | 13        | 1.63%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 1.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.5%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 12        | 1.5%    |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.38%   |
| Synaptics  WBDI                                                            | 10        | 1.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.13%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.13%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 1.13%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.88%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.63%   |
| Synaptics WBDI Device                                                      | 5         | 0.63%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.38%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.38%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 219       | 53.28%  |
| Alcor Micro               | 84        | 20.44%  |
| O2 Micro                  | 33        | 8.03%   |
| Upek                      | 17        | 4.14%   |
| Lenovo                    | 16        | 3.89%   |
| Hewlett-Packard           | 9         | 2.19%   |
| Gemalto (was Gemplus)     | 9         | 2.19%   |
| Aladdin Knowledge Systems | 5         | 1.22%   |
| Yubico.com                | 3         | 0.73%   |
| Clay Logic                | 3         | 0.73%   |
| Chicony Electronics       | 3         | 0.73%   |
| SCM Microsystems          | 2         | 0.49%   |
| Feitian Technologies      | 2         | 0.49%   |
| ST-Ericsson               | 1         | 0.24%   |
| SpringCard                | 1         | 0.24%   |
| Realtek Semiconductor     | 1         | 0.24%   |
| OmniKey                   | 1         | 0.24%   |
| Cherry                    | 1         | 0.24%   |
| Advanced Card Systems     | 1         | 0.24%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 83        | 20.19%  |
| Broadcom BCM5880 Secure Applications Processor                               | 74        | 18%     |
| Broadcom 58200                                                               | 66        | 16.06%  |
| Broadcom 5880                                                                | 45        | 10.95%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 33        | 8.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 30        | 7.3%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 4.14%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 3.89%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 9         | 2.19%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 1.46%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 1.22%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 3         | 0.73%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.73%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 0.73%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.49%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.49%   |
| ST-Ericsson Chipcard Reader                                                  | 1         | 0.24%   |
| SpringCard Two                                                               | 1         | 0.24%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.24%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.24%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.24%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.24%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.24%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.24%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.24%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.24%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.24%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.24%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.24%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5955      | 71.24%  |
| 1     | 1907      | 22.81%  |
| 2     | 388       | 4.64%   |
| 3     | 73        | 0.87%   |
| 4     | 21        | 0.25%   |
| 5     | 7         | 0.08%   |
| 6     | 3         | 0.04%   |
| 8     | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 789       | 27.04%  |
| Graphics card            | 713       | 24.43%  |
| Chipcard                 | 372       | 12.75%  |
| Net/wireless             | 311       | 10.66%  |
| Multimedia controller    | 133       | 4.56%   |
| Communication controller | 119       | 4.08%   |
| Camera                   | 95        | 3.26%   |
| Bluetooth                | 81        | 2.78%   |
| Unassigned class         | 70        | 2.4%    |
| Storage                  | 53        | 1.82%   |
| Sound                    | 46        | 1.58%   |
| Card reader              | 40        | 1.37%   |
| Net/ethernet             | 28        | 0.96%   |
| Modem                    | 20        | 0.69%   |
| Network                  | 14        | 0.48%   |
| Storage/raid             | 7         | 0.24%   |
| Firewire controller      | 7         | 0.24%   |
| Dvb card                 | 5         | 0.17%   |
| Storage/ide              | 4         | 0.14%   |
| Flash memory             | 3         | 0.1%    |
| Wireless                 | 2         | 0.07%   |
| Unclassified device      | 2         | 0.07%   |
| Tv card                  | 2         | 0.07%   |
| Storage/nvme             | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |

