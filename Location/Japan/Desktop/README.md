Linux in Japan - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

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

Total: 708

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | B460M Pro4                  | [1f3b96d1a0](https://linux-hardware.org/?probe=1f3b96d1a0) | Apr 01, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [393fc00a5d](https://linux-hardware.org/?probe=393fc00a5d) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASUSTek       | A88XM-A                     | [405e95a907](https://linux-hardware.org/?probe=405e95a907) | Mar 28, 2023 |
| MSI           | B450M MORTAR MAX            | [29c85678af](https://linux-hardware.org/?probe=29c85678af) | Mar 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [922d8a7941](https://linux-hardware.org/?probe=922d8a7941) | Mar 26, 2023 |
| MSI           | MEG B550 UNIFY              | [492a70f1c3](https://linux-hardware.org/?probe=492a70f1c3) | Mar 26, 2023 |
| HP            | 158A                        | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| MSI           | B450M MORTAR MAX            | [641481dd1d](https://linux-hardware.org/?probe=641481dd1d) | Mar 21, 2023 |
| HP            | 158A                        | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| MSI           | B450M MORTAR MAX            | [9d859cb8bd](https://linux-hardware.org/?probe=9d859cb8bd) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASRock        | 4X4-4000 Series             | [3718d345ca](https://linux-hardware.org/?probe=3718d345ca) | Mar 18, 2023 |
| Lenovo        | ThinkCentre A58 7522M4J     | [ba0a303be5](https://linux-hardware.org/?probe=ba0a303be5) | Mar 17, 2023 |
| HP            | 806A                        | [2203b83131](https://linux-hardware.org/?probe=2203b83131) | Mar 13, 2023 |
| Unknown       | HX90                        | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| Gigabyte      | P55-UD3R                    | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| ASUSTek       | B85M-G                      | [70f4bed81b](https://linux-hardware.org/?probe=70f4bed81b) | Mar 08, 2023 |
| ASUSTek       | PRO H410M-C                 | [a97c12b513](https://linux-hardware.org/?probe=a97c12b513) | Mar 08, 2023 |
| Wistron       | ProLiant ML110 G5           | [a36361538b](https://linux-hardware.org/?probe=a36361538b) | Mar 07, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [f85824345a](https://linux-hardware.org/?probe=f85824345a) | Mar 06, 2023 |
| Gigabyte      | GA-E7AUM-DS2H               | [825b26708c](https://linux-hardware.org/?probe=825b26708c) | Mar 04, 2023 |
| ASUSTek       | PRO H410M-C                 | [b0076c9250](https://linux-hardware.org/?probe=b0076c9250) | Mar 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ed5432e979](https://linux-hardware.org/?probe=ed5432e979) | Mar 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [3887cb1418](https://linux-hardware.org/?probe=3887cb1418) | Feb 26, 2023 |
| Gigabyte      | B85N PHOENIX                | [5fe00f35c4](https://linux-hardware.org/?probe=5fe00f35c4) | Feb 25, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [7864921f8d](https://linux-hardware.org/?probe=7864921f8d) | Feb 25, 2023 |
| ASUSTek       | PRO H410M-C                 | [d6edc5401d](https://linux-hardware.org/?probe=d6edc5401d) | Feb 22, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | SABERTOOTH Z77              | [b8b41b7a6e](https://linux-hardware.org/?probe=b8b41b7a6e) | Feb 19, 2023 |
| HP            | 158A                        | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| Gigabyte      | B450M S2H                   | [eb04bfdc84](https://linux-hardware.org/?probe=eb04bfdc84) | Feb 14, 2023 |
| ASUSTek       | H110M-A/M.2                 | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| ASUSTek       | PRIME A320M-A               | [9de02793ea](https://linux-hardware.org/?probe=9de02793ea) | Feb 04, 2023 |
| ASRock        | Z87M Extreme4               | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| NEC Comput... | MS9666 011                  | [26a38770fe](https://linux-hardware.org/?probe=26a38770fe) | Feb 02, 2023 |
| Wistron       | ProLiant ML110 G5           | [4af666d5b3](https://linux-hardware.org/?probe=4af666d5b3) | Feb 02, 2023 |
| BESSTAR Te... | HM90                        | [3f958de9bb](https://linux-hardware.org/?probe=3f958de9bb) | Feb 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [e2721d08d6](https://linux-hardware.org/?probe=e2721d08d6) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| MSI           | H110M PRO-VH                | [7068e861ba](https://linux-hardware.org/?probe=7068e861ba) | Jan 21, 2023 |
| Unknown       | HX90                        | [2b034e44e2](https://linux-hardware.org/?probe=2b034e44e2) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | [b781eb32d2](https://linux-hardware.org/?probe=b781eb32d2) | Jan 18, 2023 |
| HC            | HCAR357-MI V1.0             | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| ASUSTek       | J1900I-C                    | [6a2ef2080d](https://linux-hardware.org/?probe=6a2ef2080d) | Jan 09, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [99e2769927](https://linux-hardware.org/?probe=99e2769927) | Jan 07, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d3bab9b69b](https://linux-hardware.org/?probe=d3bab9b69b) | Jan 02, 2023 |
| HP            | 2B36                        | [4b363628a9](https://linux-hardware.org/?probe=4b363628a9) | Dec 30, 2022 |
| HP            | 2B36                        | [be6670b1ad](https://linux-hardware.org/?probe=be6670b1ad) | Dec 30, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| ASRock        | X570M Pro4                  | [71d2c76079](https://linux-hardware.org/?probe=71d2c76079) | Dec 28, 2022 |
| HP            | 18E7                        | [260119e159](https://linux-hardware.org/?probe=260119e159) | Dec 25, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| ASUSTek       | H170-PRO                    | [3d866a7ec8](https://linux-hardware.org/?probe=3d866a7ec8) | Dec 19, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [17618a8281](https://linux-hardware.org/?probe=17618a8281) | Dec 18, 2022 |
| HP            | 8054                        | [98d0f316b3](https://linux-hardware.org/?probe=98d0f316b3) | Dec 18, 2022 |
| MSI           | MS-7360                     | [2f5a9baf11](https://linux-hardware.org/?probe=2f5a9baf11) | Dec 18, 2022 |
| Dell          | 042P49 A02                  | [8b97211b80](https://linux-hardware.org/?probe=8b97211b80) | Dec 11, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [7d6b3699e7](https://linux-hardware.org/?probe=7d6b3699e7) | Dec 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [c22c7dfa5c](https://linux-hardware.org/?probe=c22c7dfa5c) | Dec 09, 2022 |
| ASRock        | Z370 Pro4                   | [769fed352d](https://linux-hardware.org/?probe=769fed352d) | Dec 06, 2022 |
| ASRock        | A320M-HDV R4.0              | [eeb0795100](https://linux-hardware.org/?probe=eeb0795100) | Dec 05, 2022 |
| ASUSTek       | X99-PRO                     | [6906303697](https://linux-hardware.org/?probe=6906303697) | Nov 25, 2022 |
| Biostar       | X470GTA                     | [83dcb407ba](https://linux-hardware.org/?probe=83dcb407ba) | Nov 23, 2022 |
| ASRock        | Z370 Pro4                   | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| Gigabyte      | B660M DS3H DDR4             | [4956957df8](https://linux-hardware.org/?probe=4956957df8) | Nov 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [14318910c1](https://linux-hardware.org/?probe=14318910c1) | Nov 18, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [c4bf12a3e5](https://linux-hardware.org/?probe=c4bf12a3e5) | Nov 18, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [4ba72d9f3b](https://linux-hardware.org/?probe=4ba72d9f3b) | Nov 16, 2022 |
| MSI           | Z590 PRO WIFI               | [c53f301391](https://linux-hardware.org/?probe=c53f301391) | Nov 16, 2022 |
| HP            | 83EE                        | [182682b17c](https://linux-hardware.org/?probe=182682b17c) | Nov 16, 2022 |
| HP            | 83EE                        | [65d7bade6e](https://linux-hardware.org/?probe=65d7bade6e) | Nov 16, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [4488e0a71a](https://linux-hardware.org/?probe=4488e0a71a) | Nov 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [07a9b0efe0](https://linux-hardware.org/?probe=07a9b0efe0) | Nov 10, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [09c5b6e39e](https://linux-hardware.org/?probe=09c5b6e39e) | Nov 06, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [573a028791](https://linux-hardware.org/?probe=573a028791) | Nov 03, 2022 |
| Dell          | 0WMJ54 A01                  | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [1627ad94ef](https://linux-hardware.org/?probe=1627ad94ef) | Oct 27, 2022 |
| ASUSTek       | PRO H410M-C                 | [00e64f6075](https://linux-hardware.org/?probe=00e64f6075) | Oct 25, 2022 |
| ASUSTek       | PRIME H610M-A D4            | [daa76e4b78](https://linux-hardware.org/?probe=daa76e4b78) | Oct 25, 2022 |
| ASRock        | Z370 Pro4                   | [cd2e9dd7af](https://linux-hardware.org/?probe=cd2e9dd7af) | Oct 23, 2022 |
| ASRock        | Z370 Pro4                   | [5962a98f24](https://linux-hardware.org/?probe=5962a98f24) | Oct 23, 2022 |
| HP            | 18E7                        | [db33d9c2c2](https://linux-hardware.org/?probe=db33d9c2c2) | Oct 18, 2022 |
| ASUSTek       | PRIME B365M-K               | [5fb0a15135](https://linux-hardware.org/?probe=5fb0a15135) | Oct 18, 2022 |
| ASRock        | X300-ITX                    | [a391ce99bf](https://linux-hardware.org/?probe=a391ce99bf) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | 2AF7                        | [e5cd1d0cce](https://linux-hardware.org/?probe=e5cd1d0cce) | Oct 15, 2022 |
| ASUSTek       | PRO H410M-C                 | [13581dc0a2](https://linux-hardware.org/?probe=13581dc0a2) | Oct 13, 2022 |
| Dell          | 0Y2MRG A00                  | [2e8206e823](https://linux-hardware.org/?probe=2e8206e823) | Oct 12, 2022 |
| Dell          | 0Y2MRG A00                  | [5eab8a8351](https://linux-hardware.org/?probe=5eab8a8351) | Oct 12, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [55bb52409c](https://linux-hardware.org/?probe=55bb52409c) | Oct 12, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [dd3d3724d6](https://linux-hardware.org/?probe=dd3d3724d6) | Oct 10, 2022 |
| ASUSTek       | F2A85-M PRO                 | [571cb4bb05](https://linux-hardware.org/?probe=571cb4bb05) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| MSI           | X470 GAMING PLUS            | [efe1609ac0](https://linux-hardware.org/?probe=efe1609ac0) | Sep 24, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | [11ea16f0d6](https://linux-hardware.org/?probe=11ea16f0d6) | Sep 22, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b48eda0e37](https://linux-hardware.org/?probe=b48eda0e37) | Sep 18, 2022 |
| Gigabyte      | G31M-ES2L                   | [e074efb108](https://linux-hardware.org/?probe=e074efb108) | Sep 18, 2022 |
| Gigabyte      | G31M-ES2L                   | [4b8841b706](https://linux-hardware.org/?probe=4b8841b706) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [e633838a51](https://linux-hardware.org/?probe=e633838a51) | Sep 15, 2022 |
| Gigabyte      | Z77X-UP7                    | [3bdc70035e](https://linux-hardware.org/?probe=3bdc70035e) | Sep 11, 2022 |
| ASRock        | H370 Pro4                   | [f6b34cb2b6](https://linux-hardware.org/?probe=f6b34cb2b6) | Sep 10, 2022 |
| ASRock        | B450 Pro4                   | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Intel         | D34010WYB H14771-304        | [47d9609ba8](https://linux-hardware.org/?probe=47d9609ba8) | Sep 01, 2022 |
| Intel         | D34010WYB H14771-304        | [fd34481bf8](https://linux-hardware.org/?probe=fd34481bf8) | Sep 01, 2022 |
| HP            | 18E7                        | [613d55d0e9](https://linux-hardware.org/?probe=613d55d0e9) | Aug 27, 2022 |
| Biostar       | B660MX-E                    | [4fa9d132c2](https://linux-hardware.org/?probe=4fa9d132c2) | Aug 26, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [05a337504b](https://linux-hardware.org/?probe=05a337504b) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| ASUSTek       | P7H55-M                     | [7596762e80](https://linux-hardware.org/?probe=7596762e80) | Aug 17, 2022 |
| ASUSTek       | P7H55-M                     | [bbcdb246aa](https://linux-hardware.org/?probe=bbcdb246aa) | Aug 16, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [79b28d4c5f](https://linux-hardware.org/?probe=79b28d4c5f) | Aug 16, 2022 |
| ASUSTek       | P7H55-M                     | [5106d4eda8](https://linux-hardware.org/?probe=5106d4eda8) | Aug 15, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [e59ee250ad](https://linux-hardware.org/?probe=e59ee250ad) | Aug 13, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [4ec9a5896d](https://linux-hardware.org/?probe=4ec9a5896d) | Aug 12, 2022 |
| ASRock        | B450 Pro4                   | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Gigabyte      | EP45-UD3R                   | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| Gigabyte      | Z170X-UD3-CF                | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| MSI           | MEG X570 UNIFY              | [9be9a3e83b](https://linux-hardware.org/?probe=9be9a3e83b) | Aug 01, 2022 |
| ASUSTek       | M4N78                       | [870702db59](https://linux-hardware.org/?probe=870702db59) | Jul 29, 2022 |
| ASRock        | A88M-ITX/ac                 | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| ASRock        | H470M Pro4                  | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b63e85ff7e](https://linux-hardware.org/?probe=b63e85ff7e) | Jul 25, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| GALAX         | H310M-A V2                  | [db46aaa3aa](https://linux-hardware.org/?probe=db46aaa3aa) | Jul 24, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [a09d9de883](https://linux-hardware.org/?probe=a09d9de883) | Jul 23, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | [a81e48e206](https://linux-hardware.org/?probe=a81e48e206) | Jul 15, 2022 |
| ASRock        | AMCP7A-ION                  | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| ASRock        | A300M-STX                   | [8cf2a64c6b](https://linux-hardware.org/?probe=8cf2a64c6b) | Jul 10, 2022 |
| HP            | 158A                        | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| MSI           | A520M-A PRO                 | [85fe785be5](https://linux-hardware.org/?probe=85fe785be5) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| ASUSTek       | PRO H410M-C                 | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| MSI           | Creator X299                | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b841edf2b7](https://linux-hardware.org/?probe=b841edf2b7) | Jun 19, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| ASUSTek       | X99-A                       | [2f722cf462](https://linux-hardware.org/?probe=2f722cf462) | Jun 17, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| Intel         | DB75EN AAG39650-400         | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| MSI           | H510I PRO WIFI              | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [0d24b53837](https://linux-hardware.org/?probe=0d24b53837) | Jun 02, 2022 |
| ASUSTek       | P5Q SE                      | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | VM60                        | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [ca67455f28](https://linux-hardware.org/?probe=ca67455f28) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| Gigabyte      | Z77X-UP7                    | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| MouseCompu... | B360M-ITX                   | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| HP            | 158A                        | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | PRO H410M-C                 | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Unknown       | MSL01 Series                | [1c66319969](https://linux-hardware.org/?probe=1c66319969) | May 11, 2022 |
| MouseCompu... | X99-S01                     | [69ac1048e9](https://linux-hardware.org/?probe=69ac1048e9) | May 11, 2022 |
| Gigabyte      | G31M-S2L                    | [78b1868a67](https://linux-hardware.org/?probe=78b1868a67) | May 08, 2022 |
| ASUSTek       | PRIME B365M-A               | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| ASRock        | QC5000-ITX/WiFi             | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| HP            | 158A                        | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [b07e1c97aa](https://linux-hardware.org/?probe=b07e1c97aa) | Apr 29, 2022 |
| MSI           | H510I PRO WIFI              | [5e6c23c3b5](https://linux-hardware.org/?probe=5e6c23c3b5) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | [f6df392394](https://linux-hardware.org/?probe=f6df392394) | Apr 27, 2022 |
| Dell          | 0NW73C A01                  | [430f7b0e3a](https://linux-hardware.org/?probe=430f7b0e3a) | Apr 23, 2022 |
| ASRock        | P5B-DE                      | [b9b6d17274](https://linux-hardware.org/?probe=b9b6d17274) | Apr 23, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0ad6471ecf](https://linux-hardware.org/?probe=0ad6471ecf) | Apr 16, 2022 |
| Gigabyte      | EP45-UD3P                   | [973d2cc2f1](https://linux-hardware.org/?probe=973d2cc2f1) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3fade276ac](https://linux-hardware.org/?probe=3fade276ac) | Apr 13, 2022 |
| MSI           | H170A PC MATE               | [404f32fc8a](https://linux-hardware.org/?probe=404f32fc8a) | Apr 11, 2022 |
| MSI           | B350I PRO AC                | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| ASUSTek       | H170 PRO GAMING             | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| Gigabyte      | AX370-Gaming K7             | [2759f18a1f](https://linux-hardware.org/?probe=2759f18a1f) | Apr 04, 2022 |
| ASUSTek       | H170 PRO GAMING             | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| ASUSTek       | PB50                        | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| Gigabyte      | AX370-Gaming K7             | [20aac26c6d](https://linux-hardware.org/?probe=20aac26c6d) | Mar 31, 2022 |
| ASRock        | FM2A88X-ITX+                | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [5c3993ef06](https://linux-hardware.org/?probe=5c3993ef06) | Mar 14, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b170ce8fbe](https://linux-hardware.org/?probe=b170ce8fbe) | Mar 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| HP            | 18E7                        | [07d0861eff](https://linux-hardware.org/?probe=07d0861eff) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9483d7b48e](https://linux-hardware.org/?probe=9483d7b48e) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2c1109afb8](https://linux-hardware.org/?probe=2c1109afb8) | Feb 21, 2022 |
| ASRock        | AB350M-HDV                  | [4675d06ffb](https://linux-hardware.org/?probe=4675d06ffb) | Feb 19, 2022 |
| NEC Comput... | IH81M                       | [5e60991665](https://linux-hardware.org/?probe=5e60991665) | Feb 18, 2022 |
| Unknown       | Unknown                     | [15ae5870b9](https://linux-hardware.org/?probe=15ae5870b9) | Feb 16, 2022 |
| Unknown       | Unknown                     | [e55e0df499](https://linux-hardware.org/?probe=e55e0df499) | Feb 16, 2022 |
| ASUSTek       | M4A87TD/USB3                | [041b4e9976](https://linux-hardware.org/?probe=041b4e9976) | Feb 16, 2022 |
| ASUSTek       | P7H55-M                     | [b2414fb6fc](https://linux-hardware.org/?probe=b2414fb6fc) | Feb 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [efcb060233](https://linux-hardware.org/?probe=efcb060233) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [1ee503a497](https://linux-hardware.org/?probe=1ee503a497) | Feb 13, 2022 |
| MSI           | X570-A PRO                  | [976cefe591](https://linux-hardware.org/?probe=976cefe591) | Feb 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [a5d02d3a03](https://linux-hardware.org/?probe=a5d02d3a03) | Feb 13, 2022 |
| MouseCompu... | B75H2-M2                    | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASUSTek       | P5Q                         | [bc3f44c0b9](https://linux-hardware.org/?probe=bc3f44c0b9) | Feb 10, 2022 |
| ASRock        | B550M Steel Legend          | [0c54ad1557](https://linux-hardware.org/?probe=0c54ad1557) | Feb 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [218f370835](https://linux-hardware.org/?probe=218f370835) | Feb 10, 2022 |
| ASRock        | H55DE3                      | [7d4fb5775f](https://linux-hardware.org/?probe=7d4fb5775f) | Feb 09, 2022 |
| ASRock        | B250M-HDV                   | [fcaddfe60e](https://linux-hardware.org/?probe=fcaddfe60e) | Feb 09, 2022 |
| MCJ           | H67H2-M4                    | [3814208f36](https://linux-hardware.org/?probe=3814208f36) | Feb 08, 2022 |
| MSI           | H510I PRO WIFI              | [b9c77d9df2](https://linux-hardware.org/?probe=b9c77d9df2) | Feb 08, 2022 |
| Dell          | 04YP6J A01                  | [61cc7bdcc2](https://linux-hardware.org/?probe=61cc7bdcc2) | Feb 06, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek       | P8Z77-M                     | [cb5f618a4b](https://linux-hardware.org/?probe=cb5f618a4b) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | [0c1b8480b6](https://linux-hardware.org/?probe=0c1b8480b6) | Jan 31, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| ASRock        | B450M Pro4                  | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| Gigabyte      | H81M-S                      | [9418716c6b](https://linux-hardware.org/?probe=9418716c6b) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [57fe150494](https://linux-hardware.org/?probe=57fe150494) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI           | H510I PRO WIFI              | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| ASUSTek       | N3150I-C                    | [ae91e3cc7b](https://linux-hardware.org/?probe=ae91e3cc7b) | Jan 13, 2022 |
| Gigabyte      | GA-970A-D3                  | [7539f3648f](https://linux-hardware.org/?probe=7539f3648f) | Jan 09, 2022 |
| ASUSTek       | P8H61-I                     | [261ea10bf8](https://linux-hardware.org/?probe=261ea10bf8) | Jan 08, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| HP            | 83EE                        | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [526e490544](https://linux-hardware.org/?probe=526e490544) | Dec 17, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [7d976b30fc](https://linux-hardware.org/?probe=7d976b30fc) | Dec 17, 2021 |
| ASRock        | B550 TW                     | [83c53ad524](https://linux-hardware.org/?probe=83c53ad524) | Dec 17, 2021 |
| HP            | 8054                        | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASUSTek       | P5Q                         | [dac259cc34](https://linux-hardware.org/?probe=dac259cc34) | Dec 13, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [3e6b2c12f8](https://linux-hardware.org/?probe=3e6b2c12f8) | Dec 05, 2021 |
| MSI           | X470 GAMING PLUS            | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| MSI           | H510I PRO WIFI              | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| ASUSTek       | P8H61-I                     | [bb8c25b299](https://linux-hardware.org/?probe=bb8c25b299) | Nov 20, 2021 |
| MouseCompu... | B75M-D3V-JP                 | [161d355bcc](https://linux-hardware.org/?probe=161d355bcc) | Nov 18, 2021 |
| MouseCompu... | B360M                       | [cab585062a](https://linux-hardware.org/?probe=cab585062a) | Nov 13, 2021 |
| ASUSTek       | H97-PRO                     | [99f09523d8](https://linux-hardware.org/?probe=99f09523d8) | Nov 12, 2021 |
| ASUSTek       | H170-PRO                    | [f3a3f86928](https://linux-hardware.org/?probe=f3a3f86928) | Nov 12, 2021 |
| HP            | 3047h                       | [192742e5a6](https://linux-hardware.org/?probe=192742e5a6) | Nov 12, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | 3047h                       | [935aac64ef](https://linux-hardware.org/?probe=935aac64ef) | Nov 11, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [982fbc9995](https://linux-hardware.org/?probe=982fbc9995) | Nov 10, 2021 |
| MouseCompu... | Z490M-S01                   | [bd810f8122](https://linux-hardware.org/?probe=bd810f8122) | Nov 10, 2021 |
| Gigabyte      | B85M-HD3                    | [80a8e89f7e](https://linux-hardware.org/?probe=80a8e89f7e) | Nov 06, 2021 |
| Gigabyte      | B85M-HD3                    | [834bf06329](https://linux-hardware.org/?probe=834bf06329) | Nov 03, 2021 |
| Dell          | 0P301D A02                  | [26462404f4](https://linux-hardware.org/?probe=26462404f4) | Oct 30, 2021 |
| HP            | 3047h                       | [afa4f5c1d0](https://linux-hardware.org/?probe=afa4f5c1d0) | Oct 28, 2021 |
| HP            | 3047h                       | [d5e5504f54](https://linux-hardware.org/?probe=d5e5504f54) | Oct 28, 2021 |
| ASRock        | Z370 Pro4                   | [a0bf764d45](https://linux-hardware.org/?probe=a0bf764d45) | Oct 25, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | [1d14b9b944](https://linux-hardware.org/?probe=1d14b9b944) | Oct 24, 2021 |
| Gigabyte      | H87N-WIFI                   | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| EPSON DIRE... | ST170E                      | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | [4efe80812c](https://linux-hardware.org/?probe=4efe80812c) | Oct 16, 2021 |
| ASRock        | B450M Pro4                  | [5ed3b7e62d](https://linux-hardware.org/?probe=5ed3b7e62d) | Oct 13, 2021 |
| ASRock        | H67DE                       | [491ac17e42](https://linux-hardware.org/?probe=491ac17e42) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| Gigabyte      | Z77X-UD5H                   | [e1543ea8f8](https://linux-hardware.org/?probe=e1543ea8f8) | Oct 09, 2021 |
| ASUSTek       | M51AC                       | [0d9722a373](https://linux-hardware.org/?probe=0d9722a373) | Oct 05, 2021 |
| ASUSTek       | B85M-G                      | [0d05812341](https://linux-hardware.org/?probe=0d05812341) | Oct 02, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| ASRock        | H67DE                       | [296abe4896](https://linux-hardware.org/?probe=296abe4896) | Sep 28, 2021 |
| ASRock        | H67DE                       | [e663e151d6](https://linux-hardware.org/?probe=e663e151d6) | Sep 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | [8b3dfbb8a4](https://linux-hardware.org/?probe=8b3dfbb8a4) | Sep 25, 2021 |
| Gigabyte      | Z77X-UD5H                   | [b613f0c8a9](https://linux-hardware.org/?probe=b613f0c8a9) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Gigabyte      | B75M-D2P                    | [617e5dd237](https://linux-hardware.org/?probe=617e5dd237) | Sep 08, 2021 |
| EPSON DIRE... | ST150E                      | [22d7fff01c](https://linux-hardware.org/?probe=22d7fff01c) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | [5736465e27](https://linux-hardware.org/?probe=5736465e27) | Aug 27, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Biostar       | Hi-Fi A85W                  | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| EPSON DIRE... | ST150E                      | [797ec7ec81](https://linux-hardware.org/?probe=797ec7ec81) | Aug 24, 2021 |
| ASRock        | B450 Steel Legend           | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| ASRock        | B550M Steel Legend          | [68496a4cb7](https://linux-hardware.org/?probe=68496a4cb7) | Aug 18, 2021 |
| ASRock        | N3150M                      | [932c7baf1a](https://linux-hardware.org/?probe=932c7baf1a) | Aug 17, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| MSI           | Z170A GAMING PRO CARBON     | [ab538f5af7](https://linux-hardware.org/?probe=ab538f5af7) | Aug 15, 2021 |
| ASUSTek       | SABERTOOTH X79              | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| ASRock        | Z370 Pro4                   | [5b7a8411f5](https://linux-hardware.org/?probe=5b7a8411f5) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| NEC Comput... | MS-7770HH                   | [7ca677a33c](https://linux-hardware.org/?probe=7ca677a33c) | Aug 03, 2021 |
| Gigabyte      | B450M S2H                   | [0401734340](https://linux-hardware.org/?probe=0401734340) | Jul 31, 2021 |
| ASRock        | B550M Steel Legend          | [1e02007526](https://linux-hardware.org/?probe=1e02007526) | Jul 30, 2021 |
| MSI           | H510I PRO WIFI              | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| ASRock        | A300M-STX                   | [161a673775](https://linux-hardware.org/?probe=161a673775) | Jul 28, 2021 |
| ASRock        | A300M-STX                   | [264959862d](https://linux-hardware.org/?probe=264959862d) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| HP            | 18E7                        | [c0cddf4243](https://linux-hardware.org/?probe=c0cddf4243) | Jul 23, 2021 |
| Unknown       | XH61X000.100                | [6604251e58](https://linux-hardware.org/?probe=6604251e58) | Jul 23, 2021 |
| ASRock        | FM2A88X-ITX+                | [93a813bbba](https://linux-hardware.org/?probe=93a813bbba) | Jul 22, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| HP            | 1906                        | [6cd7c6ec7f](https://linux-hardware.org/?probe=6cd7c6ec7f) | Jul 20, 2021 |
| ASRock        | 880GM-LE                    | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| ASRock        | X300M-STX                   | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| HP            | 18E7                        | [03d84525e8](https://linux-hardware.org/?probe=03d84525e8) | Jul 13, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [d6410ac1a0](https://linux-hardware.org/?probe=d6410ac1a0) | Jul 11, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1b63a19bd1](https://linux-hardware.org/?probe=1b63a19bd1) | Jul 08, 2021 |
| ASRock        | Z370 Pro4                   | [673b1c670f](https://linux-hardware.org/?probe=673b1c670f) | Jul 08, 2021 |
| ASRock        | Z370 Pro4                   | [14789c0301](https://linux-hardware.org/?probe=14789c0301) | Jul 07, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| HP            | 1906                        | [95bfd2283b](https://linux-hardware.org/?probe=95bfd2283b) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASUSTek       | PRIME H570-PLUS             | [be23e213b9](https://linux-hardware.org/?probe=be23e213b9) | Jun 26, 2021 |
| ASRock        | Z390 Pro4                   | [6c86be2586](https://linux-hardware.org/?probe=6c86be2586) | Jun 24, 2021 |
| MSI           | H510I PRO WIFI              | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c2285d9014](https://linux-hardware.org/?probe=c2285d9014) | Jun 22, 2021 |
| ASRock        | X470 Master SLI             | [76096c0075](https://linux-hardware.org/?probe=76096c0075) | Jun 19, 2021 |
| MSI           | H510I PRO WIFI              | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASRock        | X470 Master SLI             | [03b329894a](https://linux-hardware.org/?probe=03b329894a) | Jun 18, 2021 |
| ASRock        | X570 Steel Legend           | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| ASUSTek       | M4A87TD/USB3                | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| ASUSTek       | Z170M-PLUS                  | [4c0e4ebaa4](https://linux-hardware.org/?probe=4c0e4ebaa4) | Jun 16, 2021 |
| ASUSTek       | PRIME Z370-A                | [0b50c157fe](https://linux-hardware.org/?probe=0b50c157fe) | Jun 14, 2021 |
| ASRock        | X300M-STX                   | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| ECS           | G41T-M2                     | [3005be6650](https://linux-hardware.org/?probe=3005be6650) | Jun 04, 2021 |
| Intel         | D945GNT AAC96315-402        | [36fb4e2aba](https://linux-hardware.org/?probe=36fb4e2aba) | May 29, 2021 |
| ASRock        | FM2A88X-ITX+                | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| ASUSTek       | PRIME X299-A                | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Gigabyte      | EP45-UD3R                   | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Gigabyte      | EG41MF-US2H                 | [f416a7a6b3](https://linux-hardware.org/?probe=f416a7a6b3) | May 09, 2021 |
| Gigabyte      | B75M-D3H                    | [aa1f42a8a9](https://linux-hardware.org/?probe=aa1f42a8a9) | May 08, 2021 |
| ASRock        | H310CM-HDV/M.2              | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| HP            | 3047h                       | [3de6f89fae](https://linux-hardware.org/?probe=3de6f89fae) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| ASRock        | X300M-STX                   | [0f15e44442](https://linux-hardware.org/?probe=0f15e44442) | Apr 26, 2021 |
| ASRock        | P5B-DE                      | [04084bd0ef](https://linux-hardware.org/?probe=04084bd0ef) | Apr 24, 2021 |
| ASUSTek       | N3150I-C                    | [4cfbe212a4](https://linux-hardware.org/?probe=4cfbe212a4) | Apr 22, 2021 |
| Gigabyte      | B75M-D3H                    | [af34567550](https://linux-hardware.org/?probe=af34567550) | Apr 17, 2021 |
| MSI           | MAG B550M MORTAR            | [b7991a35ba](https://linux-hardware.org/?probe=b7991a35ba) | Apr 16, 2021 |
| ASUSTek       | P5Q-EM                      | [a7ed7cc477](https://linux-hardware.org/?probe=a7ed7cc477) | Apr 14, 2021 |
| ASUSTek       | P4V800D-X                   | [c469d16946](https://linux-hardware.org/?probe=c469d16946) | Apr 09, 2021 |
| ASUSTek       | PRO H410M-C                 | [a5b2555cc2](https://linux-hardware.org/?probe=a5b2555cc2) | Apr 06, 2021 |
| ASRock        | AB350 Pro4                  | [ba17a463a7](https://linux-hardware.org/?probe=ba17a463a7) | Apr 03, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [a579757204](https://linux-hardware.org/?probe=a579757204) | Apr 03, 2021 |
| ASUSTek       | P7P55D-E                    | [52b2fb4ebb](https://linux-hardware.org/?probe=52b2fb4ebb) | Mar 22, 2021 |
| ASRock        | X300M-STX                   | [d5722fd82b](https://linux-hardware.org/?probe=d5722fd82b) | Mar 22, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [e5ce81269b](https://linux-hardware.org/?probe=e5ce81269b) | Mar 22, 2021 |
| ASRock        | X370 Pro4                   | [6c6d145ad3](https://linux-hardware.org/?probe=6c6d145ad3) | Mar 20, 2021 |
| ASRock        | FM2A88X+ Killer             | [64164ccce2](https://linux-hardware.org/?probe=64164ccce2) | Mar 19, 2021 |
| ASRock        | X300M-STX                   | [b36b41329b](https://linux-hardware.org/?probe=b36b41329b) | Mar 14, 2021 |
| ASUSTek       | P7H55-M                     | [cff1baf251](https://linux-hardware.org/?probe=cff1baf251) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| HP            | 212B                        | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Biostar       | Hi-Fi A88ZN                 | [72cff94e15](https://linux-hardware.org/?probe=72cff94e15) | Mar 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [bca1731a58](https://linux-hardware.org/?probe=bca1731a58) | Mar 08, 2021 |
| HP            | 212B                        | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| MSI           | C236A WORKSTATION           | [dc9e6c2670](https://linux-hardware.org/?probe=dc9e6c2670) | Mar 03, 2021 |
| MSI           | MEG X570 GODLIKE            | [3d2e576c95](https://linux-hardware.org/?probe=3d2e576c95) | Mar 03, 2021 |
| MSI           | B450I GAMING PLUS AC        | [aa41662477](https://linux-hardware.org/?probe=aa41662477) | Mar 02, 2021 |
| ASUSTek       | M3A78-EM                    | [c08f9a30dc](https://linux-hardware.org/?probe=c08f9a30dc) | Feb 28, 2021 |
| ASUSTek       | Rampage IV GENE             | [16cf45ce16](https://linux-hardware.org/?probe=16cf45ce16) | Feb 28, 2021 |
| Dell          | 0T1D10 A01                  | [3577c78a56](https://linux-hardware.org/?probe=3577c78a56) | Feb 27, 2021 |
| Gigabyte      | H110M-S2PH-CF               | [501d2317f9](https://linux-hardware.org/?probe=501d2317f9) | Feb 26, 2021 |
| ASUSTek       | PRIME X570-P                | [7e4e426453](https://linux-hardware.org/?probe=7e4e426453) | Feb 22, 2021 |
| Biostar       | B450GT3                     | [18e0346ed0](https://linux-hardware.org/?probe=18e0346ed0) | Feb 22, 2021 |
| MSI           | C236A WORKSTATION           | [9e2effbe63](https://linux-hardware.org/?probe=9e2effbe63) | Feb 22, 2021 |
| ASRock        | A300M-STX                   | [5c5b3ce155](https://linux-hardware.org/?probe=5c5b3ce155) | Feb 19, 2021 |
| MSI           | A78M-E35 V2                 | [173e28a6b2](https://linux-hardware.org/?probe=173e28a6b2) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a2e399875d](https://linux-hardware.org/?probe=a2e399875d) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | [c364bd22bf](https://linux-hardware.org/?probe=c364bd22bf) | Feb 14, 2021 |
| Biostar       | X470NH                      | [b4ae665275](https://linux-hardware.org/?probe=b4ae665275) | Feb 13, 2021 |
| ASRock        | B75M R2.0                   | [6b1142fdaa](https://linux-hardware.org/?probe=6b1142fdaa) | Feb 13, 2021 |
| Gigabyte      | H67A-D3H-B3                 | [b384cb32dc](https://linux-hardware.org/?probe=b384cb32dc) | Feb 13, 2021 |
| MSI           | H270I GAMING PRO AC         | [dcae892f29](https://linux-hardware.org/?probe=dcae892f29) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [168dfeabe8](https://linux-hardware.org/?probe=168dfeabe8) | Feb 08, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [256969ebac](https://linux-hardware.org/?probe=256969ebac) | Feb 07, 2021 |
| ASRock        | A300M-STX                   | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Biostar       | B450GT                      | [2cb5b97972](https://linux-hardware.org/?probe=2cb5b97972) | Feb 02, 2021 |
| ASRock        | B450 Pro4                   | [ebe6b1d494](https://linux-hardware.org/?probe=ebe6b1d494) | Feb 02, 2021 |
| Wistron       | J361Y                       | [347eb6b747](https://linux-hardware.org/?probe=347eb6b747) | Jan 31, 2021 |
| NEC Comput... | IS8XM                       | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| HP            | 0A54h                       | [9f8677d69a](https://linux-hardware.org/?probe=9f8677d69a) | Jan 23, 2021 |
| ASRock        | A300M-STX                   | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| HP            | 0A54h                       | [6b91501381](https://linux-hardware.org/?probe=6b91501381) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Acer          | Aspire XC-602 V1.0          | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| Gigabyte      | G33-DS3R                    | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c77878fdf4](https://linux-hardware.org/?probe=c77878fdf4) | Jan 12, 2021 |
| Gigabyte      | 970A-D3P                    | [5cea01c3c1](https://linux-hardware.org/?probe=5cea01c3c1) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3b66143d43](https://linux-hardware.org/?probe=3b66143d43) | Jan 11, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [293bb6fc26](https://linux-hardware.org/?probe=293bb6fc26) | Jan 10, 2021 |
| Dell          | 0R7935 A03                  | [1d936da792](https://linux-hardware.org/?probe=1d936da792) | Jan 09, 2021 |
| Acer          | Aspire XC-602 V1.0          | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| HP            | 158A                        | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| MSI           | Creator X299                | [b66f2c1d16](https://linux-hardware.org/?probe=b66f2c1d16) | Jan 06, 2021 |
| ASRock        | J5005-ITX                   | [81bba5a535](https://linux-hardware.org/?probe=81bba5a535) | Jan 04, 2021 |
| Unknown       | Unknown                     | [34d77cfa6e](https://linux-hardware.org/?probe=34d77cfa6e) | Jan 03, 2021 |
| Unknown       | Unknown                     | [07fb95c682](https://linux-hardware.org/?probe=07fb95c682) | Jan 03, 2021 |
| Acer          | Aspire XC-602 V1.0          | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| ASRock        | H110 Pro BTC+               | [f56caad73c](https://linux-hardware.org/?probe=f56caad73c) | Jan 02, 2021 |
| ASRock        | A300M-STX                   | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| ASRock        | H470M-ITX/ac                | [c6ea824e48](https://linux-hardware.org/?probe=c6ea824e48) | Dec 31, 2020 |
| ASRock        | B360M-ITX/ac                | [8e0bce5edb](https://linux-hardware.org/?probe=8e0bce5edb) | Dec 30, 2020 |
| Gateway       | G33M05G1 MP                 | [460acf5c52](https://linux-hardware.org/?probe=460acf5c52) | Dec 30, 2020 |
| MSI           | FM2-A75IA-E53               | [ec03bb47a4](https://linux-hardware.org/?probe=ec03bb47a4) | Dec 28, 2020 |
| ASRock        | FM2A85X-ITX                 | [5401d7dd29](https://linux-hardware.org/?probe=5401d7dd29) | Dec 23, 2020 |
| ASRock        | B360M-ITX/ac                | [39d7373b8e](https://linux-hardware.org/?probe=39d7373b8e) | Dec 23, 2020 |
| ASUSTek       | Maximus VIII GENE           | [ca0c3d2795](https://linux-hardware.org/?probe=ca0c3d2795) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | [97e9570360](https://linux-hardware.org/?probe=97e9570360) | Dec 21, 2020 |
| HP            | 158A                        | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| FIC           | PTM33 PCB                   | [0e1437dede](https://linux-hardware.org/?probe=0e1437dede) | Dec 18, 2020 |
| Supermicro    | X9DA7/E                     | [7d84e25468](https://linux-hardware.org/?probe=7d84e25468) | Dec 14, 2020 |
| ASRock        | Z390 Pro4                   | [d988af7e73](https://linux-hardware.org/?probe=d988af7e73) | Dec 13, 2020 |
| Intel         | D945GNT AAC96315-402        | [bf27b4bfee](https://linux-hardware.org/?probe=bf27b4bfee) | Dec 12, 2020 |
| NEC Comput... | MS9666 012                  | [9cc98a743f](https://linux-hardware.org/?probe=9cc98a743f) | Dec 11, 2020 |
| Dell          | 002KVM A01                  | [bee5c78b3b](https://linux-hardware.org/?probe=bee5c78b3b) | Dec 08, 2020 |
| Gigabyte      | Z77X-UD3H                   | [772f864f4e](https://linux-hardware.org/?probe=772f864f4e) | Dec 05, 2020 |
| MSI           | H270 PC MATE                | [35866ce8fb](https://linux-hardware.org/?probe=35866ce8fb) | Dec 02, 2020 |
| ASRock        | B550 Taichi                 | [dd9ebdf6b5](https://linux-hardware.org/?probe=dd9ebdf6b5) | Dec 02, 2020 |
| MSI           | H270 PC MATE                | [3151fefb19](https://linux-hardware.org/?probe=3151fefb19) | Dec 02, 2020 |
| Gateway       | G33M05G1 MP                 | [8ec0050494](https://linux-hardware.org/?probe=8ec0050494) | Dec 01, 2020 |
| Dell          | 0NW73C A01                  | [1ddf8958ef](https://linux-hardware.org/?probe=1ddf8958ef) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | [ca9077ede2](https://linux-hardware.org/?probe=ca9077ede2) | Nov 27, 2020 |
| ASRock        | B550 Taichi                 | [047af22dea](https://linux-hardware.org/?probe=047af22dea) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | [9148a1a402](https://linux-hardware.org/?probe=9148a1a402) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | [054642cdd4](https://linux-hardware.org/?probe=054642cdd4) | Nov 25, 2020 |
| Dell          | 0R7935 A03                  | [92a6a98f06](https://linux-hardware.org/?probe=92a6a98f06) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | [a826e1045e](https://linux-hardware.org/?probe=a826e1045e) | Nov 22, 2020 |
| ASUSTek       | B85M-E                      | [3a74151cb6](https://linux-hardware.org/?probe=3a74151cb6) | Nov 22, 2020 |
| Gateway       | IPISB-VR                    | [9a9f3b244c](https://linux-hardware.org/?probe=9a9f3b244c) | Nov 21, 2020 |
| Gigabyte      | GA-880GM-USB3               | [8d591fed02](https://linux-hardware.org/?probe=8d591fed02) | Nov 21, 2020 |
| ASRock        | H310CM-HDV/M.2              | [da70709a86](https://linux-hardware.org/?probe=da70709a86) | Nov 20, 2020 |
| Gateway       | SX2370                      | [69a18194ba](https://linux-hardware.org/?probe=69a18194ba) | Nov 19, 2020 |
| ASRock        | B460M Pro4                  | [ac90684a5f](https://linux-hardware.org/?probe=ac90684a5f) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | [300e280e8c](https://linux-hardware.org/?probe=300e280e8c) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | [7344b2e1a1](https://linux-hardware.org/?probe=7344b2e1a1) | Nov 12, 2020 |
| HP            | 0B4Ch D                     | [64fbbc3a2c](https://linux-hardware.org/?probe=64fbbc3a2c) | Nov 08, 2020 |
| ASRock        | H110 Pro BTC+               | [fa4cc0d2b6](https://linux-hardware.org/?probe=fa4cc0d2b6) | Nov 07, 2020 |
| HP            | 0B4Ch D                     | [595b65bc4b](https://linux-hardware.org/?probe=595b65bc4b) | Nov 07, 2020 |
| ECS           | H77H2-M4                    | [e2dc1539b4](https://linux-hardware.org/?probe=e2dc1539b4) | Nov 06, 2020 |
| ASRock        | H110 Pro BTC+               | [38482fe4b4](https://linux-hardware.org/?probe=38482fe4b4) | Nov 04, 2020 |
| NEC Comput... | IS8XM                       | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| HP            | 0AECh D                     | [84f95d0a66](https://linux-hardware.org/?probe=84f95d0a66) | Nov 04, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | [7b86aebf60](https://linux-hardware.org/?probe=7b86aebf60) | Nov 03, 2020 |
| Dell          | 0F428D A00                  | [e70707332f](https://linux-hardware.org/?probe=e70707332f) | Nov 01, 2020 |
| Dell          | 0F428D A00                  | [86139a47f6](https://linux-hardware.org/?probe=86139a47f6) | Nov 01, 2020 |
| HP            | 0B4Ch D                     | [5621053db7](https://linux-hardware.org/?probe=5621053db7) | Nov 01, 2020 |
| ASRock        | 939A785GMH/128M             | [e5b7c1b0d3](https://linux-hardware.org/?probe=e5b7c1b0d3) | Oct 30, 2020 |
| Shuttle       | FS61                        | [c8b13a3e56](https://linux-hardware.org/?probe=c8b13a3e56) | Oct 25, 2020 |
| Shuttle       | FS61                        | [0e89874393](https://linux-hardware.org/?probe=0e89874393) | Oct 25, 2020 |
| ASUSTek       | P5Q-EM                      | [2b7dc5564c](https://linux-hardware.org/?probe=2b7dc5564c) | Oct 24, 2020 |
| ASRock        | H110M-ITX                   | [c6e251789a](https://linux-hardware.org/?probe=c6e251789a) | Oct 24, 2020 |
| ASRock        | B460M Pro4                  | [40a43c769a](https://linux-hardware.org/?probe=40a43c769a) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [70b6395f2f](https://linux-hardware.org/?probe=70b6395f2f) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ba5634435e](https://linux-hardware.org/?probe=ba5634435e) | Oct 17, 2020 |
| Supermicro    | C7B75                       | [34cb26f10c](https://linux-hardware.org/?probe=34cb26f10c) | Oct 14, 2020 |
| Pegatron      | IPM41G                      | [fa3b72447f](https://linux-hardware.org/?probe=fa3b72447f) | Oct 12, 2020 |
| Pegatron      | IPM41G                      | [4d26fb41ea](https://linux-hardware.org/?probe=4d26fb41ea) | Oct 12, 2020 |
| Lenovo        | MAHOBAY                     | [467a3d55ed](https://linux-hardware.org/?probe=467a3d55ed) | Oct 09, 2020 |
| ECS           | G43T-3L                     | [7cf090fb8f](https://linux-hardware.org/?probe=7cf090fb8f) | Oct 08, 2020 |
| ECS           | G43T-3L                     | [3533b87774](https://linux-hardware.org/?probe=3533b87774) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | [26497a27c8](https://linux-hardware.org/?probe=26497a27c8) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | [969cdedc18](https://linux-hardware.org/?probe=969cdedc18) | Oct 08, 2020 |
| Unknown       | Unknown                     | [89eee20d80](https://linux-hardware.org/?probe=89eee20d80) | Oct 05, 2020 |
| ECS           | G43T-3L                     | [b97fcd2011](https://linux-hardware.org/?probe=b97fcd2011) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| MSI           | H270 PC MATE                | [3c5eb42494](https://linux-hardware.org/?probe=3c5eb42494) | Sep 30, 2020 |
| Gigabyte      | H97-D3H-CF                  | [121f0b68c0](https://linux-hardware.org/?probe=121f0b68c0) | Sep 29, 2020 |
| ASUSTek       | P8H77-V                     | [954984a1e5](https://linux-hardware.org/?probe=954984a1e5) | Sep 23, 2020 |
| MSI           | B450 TOMAHAWK               | [21822dbd0d](https://linux-hardware.org/?probe=21822dbd0d) | Sep 19, 2020 |
| MSI           | B450 TOMAHAWK               | [692295c2b0](https://linux-hardware.org/?probe=692295c2b0) | Sep 19, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [988b8ec0f7](https://linux-hardware.org/?probe=988b8ec0f7) | Sep 14, 2020 |
| Foxconn       | A7DA-S/A7DA                 | [7974b8af2f](https://linux-hardware.org/?probe=7974b8af2f) | Sep 11, 2020 |
| HP            | 0AECh D                     | [acc13196ef](https://linux-hardware.org/?probe=acc13196ef) | Sep 11, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| ASRock        | X79 Extreme4                | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ECS           | G31T-M                      | [5b10fa37b2](https://linux-hardware.org/?probe=5b10fa37b2) | Sep 09, 2020 |
| ASRock        | Z170 Extreme4               | [688b4a3ae6](https://linux-hardware.org/?probe=688b4a3ae6) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | [b9e6801288](https://linux-hardware.org/?probe=b9e6801288) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | [176ca21f28](https://linux-hardware.org/?probe=176ca21f28) | Sep 06, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| Dell          | 0NW73C A01                  | [6d64ca0ffc](https://linux-hardware.org/?probe=6d64ca0ffc) | Aug 29, 2020 |
| Unknown       | XH61X000.100                | [1173d1c86c](https://linux-hardware.org/?probe=1173d1c86c) | Aug 16, 2020 |
| MSI           | B450M BAZOOKA PLUS          | [abd9798aa8](https://linux-hardware.org/?probe=abd9798aa8) | Aug 15, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | [729d1212fc](https://linux-hardware.org/?probe=729d1212fc) | Aug 09, 2020 |
| Intel         | D945GNT AAC96315-402        | [58a4a2906c](https://linux-hardware.org/?probe=58a4a2906c) | Aug 09, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| Fujitsu       | D3523-Ax S26361-D3523-Ax    | [b5164ce426](https://linux-hardware.org/?probe=b5164ce426) | Aug 06, 2020 |
| Unknown       | Unknown                     | [e94665aec0](https://linux-hardware.org/?probe=e94665aec0) | Jul 31, 2020 |
| Acer          | F690GVM                     | [71f0df745c](https://linux-hardware.org/?probe=71f0df745c) | Jul 30, 2020 |
| ASRock        | H55M-GE                     | [374978dac5](https://linux-hardware.org/?probe=374978dac5) | Jul 29, 2020 |
| ASRock        | H55M-GE                     | [235e00b675](https://linux-hardware.org/?probe=235e00b675) | Jul 29, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [bb8dec90c6](https://linux-hardware.org/?probe=bb8dec90c6) | Jul 27, 2020 |
| Dell          | 0Y7WYT A00                  | [efc2b837a2](https://linux-hardware.org/?probe=efc2b837a2) | Jul 26, 2020 |
| Dell          | 0WMJ54 A01                  | [0eeeb834c1](https://linux-hardware.org/?probe=0eeeb834c1) | Jul 23, 2020 |
| HP            | 158A                        | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| AOpen         | AX4SG-N 918AT10202          | [44e42d5468](https://linux-hardware.org/?probe=44e42d5468) | Jul 19, 2020 |
| ASUSTek       | M3A78-EM                    | [c21bfaa19a](https://linux-hardware.org/?probe=c21bfaa19a) | Jul 18, 2020 |
| Intel         | D510MO AAE76523-403         | [a8297ffb6c](https://linux-hardware.org/?probe=a8297ffb6c) | Jul 17, 2020 |
| Shuttle       | FG41 V20                    | [a714d062a3](https://linux-hardware.org/?probe=a714d062a3) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [faca3dbfa3](https://linux-hardware.org/?probe=faca3dbfa3) | Jul 15, 2020 |
| ASRock        | X470 Master SLI             | [efa706ee83](https://linux-hardware.org/?probe=efa706ee83) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [4f60404fb3](https://linux-hardware.org/?probe=4f60404fb3) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| HP            | 0A54h                       | [944573af57](https://linux-hardware.org/?probe=944573af57) | Jul 13, 2020 |
| HP            | 158A                        | [f5c2d58594](https://linux-hardware.org/?probe=f5c2d58594) | Jul 13, 2020 |
| HP            | 158A                        | [52e8f357cc](https://linux-hardware.org/?probe=52e8f357cc) | Jul 10, 2020 |
| Foxconn       | 2ADA                        | [004f2e3d8b](https://linux-hardware.org/?probe=004f2e3d8b) | Jul 10, 2020 |
| EPSON DIRE... | ST170E                      | [fa44f643d1](https://linux-hardware.org/?probe=fa44f643d1) | Jul 09, 2020 |
| Lenovo        | SHARKBAY NOK                | [31285675c8](https://linux-hardware.org/?probe=31285675c8) | Jul 09, 2020 |
| ASUSTek       | K8V-X SE                    | [3348cccfcf](https://linux-hardware.org/?probe=3348cccfcf) | Jul 07, 2020 |
| NEC Comput... | MS-7594VH                   | [7bb53810f4](https://linux-hardware.org/?probe=7bb53810f4) | Jul 04, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [f8d281db4b](https://linux-hardware.org/?probe=f8d281db4b) | Jul 04, 2020 |
| ASRock        | B450M Pro4                  | [96bbacdb7a](https://linux-hardware.org/?probe=96bbacdb7a) | Jul 04, 2020 |
| Dell          | 0MF252                      | [682081179d](https://linux-hardware.org/?probe=682081179d) | Jul 03, 2020 |
| MSI           | AM1I                        | [b67361f132](https://linux-hardware.org/?probe=b67361f132) | Jul 03, 2020 |
| MSI           | AM1I                        | [34352c7324](https://linux-hardware.org/?probe=34352c7324) | Jul 03, 2020 |
| Gigabyte      | Z390 UD                     | [52981221fb](https://linux-hardware.org/?probe=52981221fb) | Jul 02, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [13aec875c0](https://linux-hardware.org/?probe=13aec875c0) | Jun 28, 2020 |
| Gigabyte      | G33-DS3R                    | [ba90c2bc8a](https://linux-hardware.org/?probe=ba90c2bc8a) | Jun 28, 2020 |
| ASUSTek       | Rampage Formula             | [d6042911d7](https://linux-hardware.org/?probe=d6042911d7) | Jun 26, 2020 |
| ASUSTek       | Rampage Formula             | [0cef269aa8](https://linux-hardware.org/?probe=0cef269aa8) | Jun 26, 2020 |
| Intel         | DH61BE AAG14062-206         | [13043e1664](https://linux-hardware.org/?probe=13043e1664) | Jun 26, 2020 |
| ASRock        | Z87 Extreme4                | [78ee2fc419](https://linux-hardware.org/?probe=78ee2fc419) | Jun 24, 2020 |
| Gigabyte      | 970A-DS3P                   | [7d3ab72cf8](https://linux-hardware.org/?probe=7d3ab72cf8) | Jun 23, 2020 |
| ASUSTek       | P5B-E Plus                  | [03c7fbadbe](https://linux-hardware.org/?probe=03c7fbadbe) | Jun 22, 2020 |
| Gigabyte      | Z390 UD                     | [637edc299c](https://linux-hardware.org/?probe=637edc299c) | Jun 20, 2020 |
| Fujitsu       | FJNB04F                     | [15202a6cae](https://linux-hardware.org/?probe=15202a6cae) | Jun 19, 2020 |
| Fujitsu       | FJNB04F                     | [199eca36a2](https://linux-hardware.org/?probe=199eca36a2) | Jun 19, 2020 |
| ASRock        | B460M Pro4                  | [9b0c21ddaf](https://linux-hardware.org/?probe=9b0c21ddaf) | Jun 19, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [216109b0bf](https://linux-hardware.org/?probe=216109b0bf) | Jun 19, 2020 |
| Pegatron      | IPMSB-H61                   | [6182092aa0](https://linux-hardware.org/?probe=6182092aa0) | Jun 18, 2020 |
| ASRock        | J4105M                      | [a1620f0637](https://linux-hardware.org/?probe=a1620f0637) | Jun 18, 2020 |
| MSI           | H67MA-E45                   | [e54c477ff4](https://linux-hardware.org/?probe=e54c477ff4) | Jun 17, 2020 |
| MSI           | H67MA-E45                   | [7ec2ad02d1](https://linux-hardware.org/?probe=7ec2ad02d1) | Jun 17, 2020 |
| Gigabyte      | G33-DS3R                    | [94cd0685d0](https://linux-hardware.org/?probe=94cd0685d0) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | [c713e8fe0a](https://linux-hardware.org/?probe=c713e8fe0a) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | [24ba426f14](https://linux-hardware.org/?probe=24ba426f14) | Jun 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a01cc45fc9](https://linux-hardware.org/?probe=a01cc45fc9) | Jun 15, 2020 |
| Gigabyte      | G33-DS3R                    | [7608803f5f](https://linux-hardware.org/?probe=7608803f5f) | Jun 14, 2020 |
| ASRock        | H67DE3                      | [7a70672456](https://linux-hardware.org/?probe=7a70672456) | Jun 13, 2020 |
| ASRock        | H67DE3                      | [cc6d5aa5c4](https://linux-hardware.org/?probe=cc6d5aa5c4) | Jun 13, 2020 |
| ASUSTek       | VM42                        | [0e8e6fd4f6](https://linux-hardware.org/?probe=0e8e6fd4f6) | Jun 13, 2020 |
| HP            | 18E7                        | [5d52f06e43](https://linux-hardware.org/?probe=5d52f06e43) | Jun 11, 2020 |
| ASRock        | X370 Gaming K4              | [75f3ae6145](https://linux-hardware.org/?probe=75f3ae6145) | Jun 10, 2020 |
| Foxconn       | A7DA-S/A7DA                 | [0811f5f8ff](https://linux-hardware.org/?probe=0811f5f8ff) | Jun 09, 2020 |
| ASUSTek       | K8V-X SE                    | [8480b7d838](https://linux-hardware.org/?probe=8480b7d838) | Jun 06, 2020 |
| HP            | 805A                        | [ff57395238](https://linux-hardware.org/?probe=ff57395238) | Jun 05, 2020 |
| Gigabyte      | GA-MA69G-S3H                | [09e6763a1e](https://linux-hardware.org/?probe=09e6763a1e) | Jun 04, 2020 |
| Dell          | 0CKCXH A04                  | [0b782c6457](https://linux-hardware.org/?probe=0b782c6457) | Jun 03, 2020 |
| HP            | 18E7                        | [98c9458523](https://linux-hardware.org/?probe=98c9458523) | Jun 02, 2020 |
| Gigabyte      | GA-MA69G-S3H                | [b67c33afab](https://linux-hardware.org/?probe=b67c33afab) | Jun 01, 2020 |
| Gateway       | IPISB-VR                    | [9fcd287a96](https://linux-hardware.org/?probe=9fcd287a96) | May 31, 2020 |
| Gateway       | IPISB-VR                    | [fbb92a7b21](https://linux-hardware.org/?probe=fbb92a7b21) | May 31, 2020 |
| MSI           | H110M GAMING                | [58c02952ac](https://linux-hardware.org/?probe=58c02952ac) | May 31, 2020 |
| ASUSTek       | H87I-PLUS                   | [f830159e63](https://linux-hardware.org/?probe=f830159e63) | May 30, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4cdd92c012](https://linux-hardware.org/?probe=4cdd92c012) | May 29, 2020 |
| Supermicro    | X9DA7/E                     | [c1586ca94e](https://linux-hardware.org/?probe=c1586ca94e) | May 27, 2020 |
| HP            | 18E7                        | [e85c8c8c1f](https://linux-hardware.org/?probe=e85c8c8c1f) | May 27, 2020 |
| MouseCompu... | B360M                       | [33e415ae9c](https://linux-hardware.org/?probe=33e415ae9c) | May 25, 2020 |
| Onkyo         | ONKYOPC                     | [cc90a61c2f](https://linux-hardware.org/?probe=cc90a61c2f) | May 24, 2020 |
| ASUSTek       | P8H77-V LE                  | [7b5401d05e](https://linux-hardware.org/?probe=7b5401d05e) | May 22, 2020 |
| ASRock        | J5005-ITX                   | [e3f18b5738](https://linux-hardware.org/?probe=e3f18b5738) | May 21, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [ab3c4986e4](https://linux-hardware.org/?probe=ab3c4986e4) | May 21, 2020 |
| NEC Comput... | MS-7777N1                   | [5cea911946](https://linux-hardware.org/?probe=5cea911946) | May 18, 2020 |
| NEC Comput... | MS-7777N1                   | [0afcb9ba8d](https://linux-hardware.org/?probe=0afcb9ba8d) | May 17, 2020 |
| ASUSTek       | P5E                         | [67df8c58c9](https://linux-hardware.org/?probe=67df8c58c9) | May 16, 2020 |
| ASUSTek       | P6T                         | [90b5a63736](https://linux-hardware.org/?probe=90b5a63736) | May 16, 2020 |
| ASUSTek       | P5E                         | [140c3b0db8](https://linux-hardware.org/?probe=140c3b0db8) | May 11, 2020 |
| HP            | 158A                        | [5af55dbc63](https://linux-hardware.org/?probe=5af55dbc63) | May 09, 2020 |
| MSI           | MEG X570 ACE                | [dc7e369d45](https://linux-hardware.org/?probe=dc7e369d45) | May 08, 2020 |
| ASRock        | B450M Pro4                  | [01445b6224](https://linux-hardware.org/?probe=01445b6224) | May 07, 2020 |
| ASRock        | 970 Extreme3                | [5391547134](https://linux-hardware.org/?probe=5391547134) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | [a36a61fc42](https://linux-hardware.org/?probe=a36a61fc42) | May 05, 2020 |
| ASUSTek       | P8B75-M                     | [64b3255738](https://linux-hardware.org/?probe=64b3255738) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | [0e1b63c36e](https://linux-hardware.org/?probe=0e1b63c36e) | May 05, 2020 |
| ASRock        | X370 Gaming K4              | [9b591e104f](https://linux-hardware.org/?probe=9b591e104f) | May 04, 2020 |
| ASUSTek       | P8B75-M                     | [38669e151b](https://linux-hardware.org/?probe=38669e151b) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | [7e39b26e35](https://linux-hardware.org/?probe=7e39b26e35) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | [a622ca867c](https://linux-hardware.org/?probe=a622ca867c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | [a258fe9d3c](https://linux-hardware.org/?probe=a258fe9d3c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | [5c757ca851](https://linux-hardware.org/?probe=5c757ca851) | Apr 17, 2020 |
| MouseCompu... | Z170-S01                    | [48ca5fe277](https://linux-hardware.org/?probe=48ca5fe277) | Apr 15, 2020 |
| MouseCompu... | Z170-S01                    | [9157166443](https://linux-hardware.org/?probe=9157166443) | Apr 15, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [6169eb8c91](https://linux-hardware.org/?probe=6169eb8c91) | Apr 14, 2020 |
| ASRock        | H310CM-HDV/M.2              | [253ee15233](https://linux-hardware.org/?probe=253ee15233) | Apr 12, 2020 |
| MCJ           | H55M-P33                    | [cb5e96a31a](https://linux-hardware.org/?probe=cb5e96a31a) | Apr 08, 2020 |
| ASUSTek       | F1A75-V PRO                 | [abe59477d7](https://linux-hardware.org/?probe=abe59477d7) | Apr 05, 2020 |
| ASUSTek       | F1A75-V PRO                 | [41eee8b868](https://linux-hardware.org/?probe=41eee8b868) | Apr 04, 2020 |
| ASRock        | H310M-STX                   | [5fbe6e4ee6](https://linux-hardware.org/?probe=5fbe6e4ee6) | Apr 01, 2020 |
| ASRock        | H310M-STX                   | [4a58d0cf1f](https://linux-hardware.org/?probe=4a58d0cf1f) | Apr 01, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [6fc123427e](https://linux-hardware.org/?probe=6fc123427e) | Mar 21, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [ec5fdd7cf2](https://linux-hardware.org/?probe=ec5fdd7cf2) | Mar 21, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [95d96a6705](https://linux-hardware.org/?probe=95d96a6705) | Mar 14, 2020 |
| ASUSTek       | P8Z77-V LX                  | [edda861710](https://linux-hardware.org/?probe=edda861710) | Mar 01, 2020 |
| ECS           | G31T-M                      | [b765a7fa7f](https://linux-hardware.org/?probe=b765a7fa7f) | Feb 11, 2020 |
| ASRock        | H87M Pro4                   | [ca641865e0](https://linux-hardware.org/?probe=ca641865e0) | Feb 06, 2020 |
| ASUSTek       | PRIME H310M-A               | [2e4119c423](https://linux-hardware.org/?probe=2e4119c423) | Jan 30, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [043ccd92f3](https://linux-hardware.org/?probe=043ccd92f3) | Jan 29, 2020 |
| ASRock        | A88M-G                      | [3949599c5d](https://linux-hardware.org/?probe=3949599c5d) | Jan 28, 2020 |
| HP            | 0A54h                       | [356168fec6](https://linux-hardware.org/?probe=356168fec6) | Jan 28, 2020 |
| ASRock        | A88M-G                      | [bb36145452](https://linux-hardware.org/?probe=bb36145452) | Jan 25, 2020 |
| ASRock        | A88M-G                      | [07e625051c](https://linux-hardware.org/?probe=07e625051c) | Jan 25, 2020 |
| Gateway       | RS780                       | [09cf381b3c](https://linux-hardware.org/?probe=09cf381b3c) | Jan 25, 2020 |
| Gateway       | RS780                       | [3fe382995a](https://linux-hardware.org/?probe=3fe382995a) | Jan 13, 2020 |
| ASUSTek       | X99-A                       | [67389da431](https://linux-hardware.org/?probe=67389da431) | Jan 04, 2020 |
| Gateway       | RS780                       | [3b7741a3a0](https://linux-hardware.org/?probe=3b7741a3a0) | Jan 04, 2020 |
| ASUSTek       | X99-A                       | [8893153b1b](https://linux-hardware.org/?probe=8893153b1b) | Jan 01, 2020 |
| Gigabyte      | 965G-DS3                    | [a7a0b9ab30](https://linux-hardware.org/?probe=a7a0b9ab30) | Dec 28, 2019 |
| ASRock        | J3160DC-ITX                 | [b41206f2fd](https://linux-hardware.org/?probe=b41206f2fd) | Dec 22, 2019 |
| Fujitsu       | JIH61Y3                     | [5a7487a856](https://linux-hardware.org/?probe=5a7487a856) | Dec 21, 2019 |
| Gigabyte      | Z97X-UD3H-CF                | [a66e24484e](https://linux-hardware.org/?probe=a66e24484e) | Dec 19, 2019 |
| Wistron       | JIB65Y                      | [ed496b7bdf](https://linux-hardware.org/?probe=ed496b7bdf) | Dec 19, 2019 |
| ECS           | G31T-M                      | [7052a98f3b](https://linux-hardware.org/?probe=7052a98f3b) | Dec 19, 2019 |
| ASUSTek       | PRIME Z390-A                | [91947835b4](https://linux-hardware.org/?probe=91947835b4) | Dec 04, 2019 |
| Gigabyte      | 970A-D3P                    | [65bd7a0352](https://linux-hardware.org/?probe=65bd7a0352) | Nov 30, 2019 |
| ASRock        | H87M Pro4                   | [54341a6439](https://linux-hardware.org/?probe=54341a6439) | Nov 26, 2019 |
| MSI           | AM1I                        | [e6dcc8ef69](https://linux-hardware.org/?probe=e6dcc8ef69) | Nov 11, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | [91ed990d94](https://linux-hardware.org/?probe=91ed990d94) | Oct 28, 2019 |
| NEC Comput... | MS-7594VH                   | [9ddd905922](https://linux-hardware.org/?probe=9ddd905922) | Oct 27, 2019 |
| ECS           | G31T-M                      | [21dce1ded7](https://linux-hardware.org/?probe=21dce1ded7) | Oct 26, 2019 |
| ASUSTek       | PRIME H370-A                | [7b0b66861a](https://linux-hardware.org/?probe=7b0b66861a) | Oct 12, 2019 |
| HP            | 2ADE                        | [eba5a305b7](https://linux-hardware.org/?probe=eba5a305b7) | Oct 07, 2019 |
| ASUSTek       | PRIME X299-A                | [049af64f1e](https://linux-hardware.org/?probe=049af64f1e) | Oct 04, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9db5f37aab](https://linux-hardware.org/?probe=9db5f37aab) | Oct 03, 2019 |
| ASRock        | H77 Pro4/MVP                | [306e5b04f7](https://linux-hardware.org/?probe=306e5b04f7) | Sep 28, 2019 |
| ASRock        | Z87 Killer                  | [ee533a4daf](https://linux-hardware.org/?probe=ee533a4daf) | Sep 26, 2019 |
| ECS           | G31T-M                      | [5cefc9e8d2](https://linux-hardware.org/?probe=5cefc9e8d2) | Sep 24, 2019 |
| Gigabyte      | H81M-DS2                    | [2d44575da5](https://linux-hardware.org/?probe=2d44575da5) | Sep 23, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [f9ce29fec6](https://linux-hardware.org/?probe=f9ce29fec6) | Sep 19, 2019 |
| ASUSTek       | PRIME Z390-A                | [a9d1c2f51c](https://linux-hardware.org/?probe=a9d1c2f51c) | Sep 18, 2019 |
| ASUSTek       | PRIME Z390-A                | [a6ed7aa983](https://linux-hardware.org/?probe=a6ed7aa983) | Sep 18, 2019 |
| ASUSTek       | M4A78-VM                    | [fc5bd8749b](https://linux-hardware.org/?probe=fc5bd8749b) | Sep 17, 2019 |
| ASRock        | Z87 Killer                  | [3918b7d23a](https://linux-hardware.org/?probe=3918b7d23a) | Sep 14, 2019 |
| ECS           | A75F-M2                     | [f891e8f1d5](https://linux-hardware.org/?probe=f891e8f1d5) | Sep 06, 2019 |
| ASRock        | Z87 Killer                  | [a1d5416305](https://linux-hardware.org/?probe=a1d5416305) | Sep 01, 2019 |
| ECS           | G31T-M                      | [78a1016ee6](https://linux-hardware.org/?probe=78a1016ee6) | Aug 30, 2019 |
| ASUSTek       | PRIME X299-A                | [4ad9989703](https://linux-hardware.org/?probe=4ad9989703) | Aug 28, 2019 |
| ASRock        | Z87 Killer                  | [16e84b9fb7](https://linux-hardware.org/?probe=16e84b9fb7) | Aug 24, 2019 |
| ASUSTek       | GL12CP                      | [0b7ad9054f](https://linux-hardware.org/?probe=0b7ad9054f) | Aug 19, 2019 |
| ASUSTek       | PRIME X299-A                | [1f914d8603](https://linux-hardware.org/?probe=1f914d8603) | Aug 15, 2019 |
| Fujitsu       | JIH61Y3                     | [0bdef2ed89](https://linux-hardware.org/?probe=0bdef2ed89) | Aug 15, 2019 |
| ASUSTek       | GL12CP                      | [314f1278b8](https://linux-hardware.org/?probe=314f1278b8) | Aug 13, 2019 |
| ASUSTek       | GL12CP                      | [7e8a4409ab](https://linux-hardware.org/?probe=7e8a4409ab) | Aug 13, 2019 |
| NEC Comput... | MS9666 012                  | [e0ccec3cb3](https://linux-hardware.org/?probe=e0ccec3cb3) | Aug 08, 2019 |
| HP            | 158B                        | [f588fb7831](https://linux-hardware.org/?probe=f588fb7831) | Aug 05, 2019 |
| Gigabyte      | G41M-Combo                  | [7a7a55bb9f](https://linux-hardware.org/?probe=7a7a55bb9f) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | [63f518652d](https://linux-hardware.org/?probe=63f518652d) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | [2985c7f780](https://linux-hardware.org/?probe=2985c7f780) | Jul 27, 2019 |
| HP            | 1589                        | [2eeb0dcbef](https://linux-hardware.org/?probe=2eeb0dcbef) | Jul 18, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8d70085277](https://linux-hardware.org/?probe=8d70085277) | Jul 16, 2019 |
| MCJ           | CO.,LTD                     | [0cca59b833](https://linux-hardware.org/?probe=0cca59b833) | Jul 13, 2019 |
| MCJ           | CO.,LTD                     | [262f82967e](https://linux-hardware.org/?probe=262f82967e) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c77e3987e8](https://linux-hardware.org/?probe=c77e3987e8) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [03894447bb](https://linux-hardware.org/?probe=03894447bb) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | [ef1765e325](https://linux-hardware.org/?probe=ef1765e325) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | [f457a91893](https://linux-hardware.org/?probe=f457a91893) | Jul 12, 2019 |
| ASUSTek       | M4A88T-I DELUXE             | [7011e7619b](https://linux-hardware.org/?probe=7011e7619b) | Jul 04, 2019 |
| ASRock        | H77 Pro4/MVP                | [3ac82eca46](https://linux-hardware.org/?probe=3ac82eca46) | Jun 29, 2019 |
| NEC Comput... | MS-7594VH                   | [e61c26fd4c](https://linux-hardware.org/?probe=e61c26fd4c) | Jun 25, 2019 |
| ASUSTek       | X99-E-10G WS                | [f7605b7f95](https://linux-hardware.org/?probe=f7605b7f95) | Jun 18, 2019 |
| ASUSTek       | H110M-A/M.2                 | [6e8096d588](https://linux-hardware.org/?probe=6e8096d588) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [4cf90e52e8](https://linux-hardware.org/?probe=4cf90e52e8) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [279621d15c](https://linux-hardware.org/?probe=279621d15c) | May 20, 2019 |
| Dell          | 0XPDFK A01                  | [b545ad5544](https://linux-hardware.org/?probe=b545ad5544) | May 10, 2019 |
| Dell          | 0XPDFK A01                  | [d4c3d2990b](https://linux-hardware.org/?probe=d4c3d2990b) | May 09, 2019 |
| Onkyo         | ONKYOPC 0A                  | [d298e61165](https://linux-hardware.org/?probe=d298e61165) | May 04, 2019 |
| ASRock        | X370 Gaming K4              | [f3883ffe3f](https://linux-hardware.org/?probe=f3883ffe3f) | May 03, 2019 |
| ASUSTek       | PRIME H370M-PLUS            | [d92d4f0666](https://linux-hardware.org/?probe=d92d4f0666) | May 02, 2019 |
| HP            | 3398                        | [915f8eec67](https://linux-hardware.org/?probe=915f8eec67) | Apr 30, 2019 |
| Gigabyte      | A320M-HD2-CF                | [740fc92339](https://linux-hardware.org/?probe=740fc92339) | Apr 26, 2019 |
| Dell          | 09KPNV A00                  | [ac628634d2](https://linux-hardware.org/?probe=ac628634d2) | Mar 30, 2019 |
| MCJ           | H55-S01                     | [24d0907973](https://linux-hardware.org/?probe=24d0907973) | Mar 21, 2019 |
| Dell          | 0J584C A00                  | [7f79951f35](https://linux-hardware.org/?probe=7f79951f35) | Mar 10, 2019 |
| Gigabyte      | M61P-S3                     | [b6505655d3](https://linux-hardware.org/?probe=b6505655d3) | Feb 22, 2019 |
| Gigabyte      | M61P-S3                     | [d1f1dd8c96](https://linux-hardware.org/?probe=d1f1dd8c96) | Feb 19, 2019 |
| ASUSTek       | M3A78-EM                    | [0120bc4801](https://linux-hardware.org/?probe=0120bc4801) | Feb 04, 2019 |
| Pegatron      | 2AB5                        | [c87217d642](https://linux-hardware.org/?probe=c87217d642) | Feb 03, 2019 |
| Intel         | DG965RY AAD41691-205        | [15252dcf05](https://linux-hardware.org/?probe=15252dcf05) | Jan 20, 2019 |
| MCJ           | H55-S01                     | [f694a85c3b](https://linux-hardware.org/?probe=f694a85c3b) | Jan 20, 2019 |
| MCJ           | H55-S01                     | [b72a8388df](https://linux-hardware.org/?probe=b72a8388df) | Jan 20, 2019 |
| Gigabyte      | B450 AORUS M                | [7d4741d740](https://linux-hardware.org/?probe=7d4741d740) | Nov 17, 2018 |
| MSI           | P67A-S40                    | [4104f2eabe](https://linux-hardware.org/?probe=4104f2eabe) | Nov 12, 2018 |
| Dell          | 0WJ771                      | [1a6e39d574](https://linux-hardware.org/?probe=1a6e39d574) | Dec 07, 2017 |
| ASRock        | 990FX Extreme4              | [b1702d4023](https://linux-hardware.org/?probe=b1702d4023) | Apr 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Japan/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 103      | 20.4%   |
| Ubuntu 18.04       | 57       | 11.29%  |
| Ubuntu 22.04       | 28       | 5.54%   |
| OpenMandriva 4.3   | 27       | 5.35%   |
| OpenMandriva 4.2   | 18       | 3.56%   |
| Xubuntu 20.04      | 16       | 3.17%   |
| Debian 11          | 14       | 2.77%   |
| Xubuntu 18.04      | 10       | 1.98%   |
| Ubuntu 21.10       | 9        | 1.78%   |
| Arch Rolling       | 9        | 1.78%   |
| Ubuntu 20.10       | 8        | 1.58%   |
| OpenMandriva 23.01 | 8        | 1.58%   |
| Ubuntu 19.04       | 7        | 1.39%   |
| BlackPanther 18.1  | 7        | 1.39%   |
| Ubuntu 21.04       | 6        | 1.19%   |
| OpenMandriva 4.50  | 6        | 1.19%   |
| Fedora 34          | 6        | 1.19%   |
| Arch               | 6        | 1.19%   |
| Zorin 16           | 5        | 0.99%   |
| Pop!_OS 22.04      | 5        | 0.99%   |
| Pop!_OS 21.04      | 5        | 0.99%   |
| Linux Mint 20.3    | 5        | 0.99%   |
| Linux Mint 19.3    | 5        | 0.99%   |
| Fedora 36          | 5        | 0.99%   |
| ROSA R11           | 4        | 0.79%   |
| Lubuntu 20.04      | 4        | 0.79%   |
| Linux Mint 20      | 4        | 0.79%   |
| KDE neon 20.04     | 4        | 0.79%   |
| Fedora 33          | 4        | 0.79%   |
| Fedora 32          | 4        | 0.79%   |
| ArcoLinux Rolling  | 4        | 0.79%   |
| Zorin 15           | 3        | 0.59%   |
| Ubuntu 22.10       | 3        | 0.59%   |
| Ubuntu 19.10       | 3        | 0.59%   |
| Ubuntu 16.04       | 3        | 0.59%   |
| OpenMandriva 23.03 | 3        | 0.59%   |
| Manjaro            | 3        | 0.59%   |
| Linux Mint 21.1    | 3        | 0.59%   |
| Linux Mint 21      | 3        | 0.59%   |
| Kubuntu 20.04      | 3        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 217      | 45.88%  |
| OpenMandriva  | 59       | 12.47%  |
| Xubuntu       | 25       | 5.29%   |
| Linux Mint    | 23       | 4.86%   |
| Fedora        | 21       | 4.44%   |
| Debian        | 19       | 4.02%   |
| Arch          | 15       | 3.17%   |
| Pop!_OS       | 13       | 2.75%   |
| Zorin         | 9        | 1.9%    |
| ROSA          | 8        | 1.69%   |
| Manjaro       | 7        | 1.48%   |
| BlackPanther  | 7        | 1.48%   |
| Lubuntu       | 4        | 0.85%   |
| Kubuntu       | 4        | 0.85%   |
| KDE neon      | 4        | 0.85%   |
| Elementary    | 4        | 0.85%   |
| ArcoLinux     | 4        | 0.85%   |
| openSUSE      | 3        | 0.63%   |
| Gentoo        | 3        | 0.63%   |
| Ubuntu Unity  | 2        | 0.42%   |
| Ubuntu MATE   | 2        | 0.42%   |
| Slackware     | 2        | 0.42%   |
| Parrot        | 2        | 0.42%   |
| Endless       | 2        | 0.42%   |
| Clear Linux   | 2        | 0.42%   |
| CentOS        | 2        | 0.42%   |
| Ubuntu Budgie | 1        | 0.21%   |
| Rocky Linux   | 1        | 0.21%   |
| RHEL          | 1        | 0.21%   |
| Redcore       | 1        | 0.21%   |
| Nobara        | 1        | 0.21%   |
| Kali          | 1        | 0.21%   |
| EndeavourOS   | 1        | 0.21%   |
| BunsenLabs    | 1        | 0.21%   |
| BigLinux      | 1        | 0.21%   |
| Artix         | 1        | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.16.7-desktop-1omv4003  | 26       | 4.63%   |
| 5.10.14-desktop-1omv4002 | 17       | 3.02%   |
| 5.4.0-42-generic         | 10       | 1.78%   |
| 5.4.0-40-generic         | 9        | 1.6%    |
| 5.4.0-33-generic         | 9        | 1.6%    |
| 5.4.0-58-generic         | 8        | 1.42%   |
| 5.4.0-37-generic         | 8        | 1.42%   |
| 5.4.0-52-generic         | 7        | 1.25%   |
| 5.15.0-56-generic        | 7        | 1.25%   |
| 4.18.16-desktop-1bP      | 7        | 1.25%   |
| 6.1.1-desktop-1omv2290   | 6        | 1.07%   |
| 5.4.0-54-generic         | 6        | 1.07%   |
| 5.4.0-29-generic         | 5        | 0.89%   |
| 5.13.0-40-generic        | 5        | 0.89%   |
| 5.13.0-30-generic        | 5        | 0.89%   |
| 5.11.0-38-generic        | 5        | 0.89%   |
| 5.4.0-66-generic         | 4        | 0.71%   |
| 5.15.0-50-generic        | 4        | 0.71%   |
| 5.15.0-46-generic        | 4        | 0.71%   |
| 5.13.0-39-generic        | 4        | 0.71%   |
| 5.10.0-16-amd64          | 4        | 0.71%   |
| 5.0.0-29-generic         | 4        | 0.71%   |
| 4.15.0-72-generic        | 4        | 0.71%   |
| 4.15.0-48-generic        | 4        | 0.71%   |
| 5.8.0-59-generic         | 3        | 0.53%   |
| 5.8.0-55-generic         | 3        | 0.53%   |
| 5.8.0-50-generic         | 3        | 0.53%   |
| 5.8.0-43-generic         | 3        | 0.53%   |
| 5.4.0-99-generic         | 3        | 0.53%   |
| 5.4.0-67-generic         | 3        | 0.53%   |
| 5.4.0-39-generic         | 3        | 0.53%   |
| 5.4.0-31-generic         | 3        | 0.53%   |
| 5.3.0-28-generic         | 3        | 0.53%   |
| 5.3.0-26-generic         | 3        | 0.53%   |
| 5.19.0-35-generic        | 3        | 0.53%   |
| 5.15.0-67-generic        | 3        | 0.53%   |
| 5.15.0-52-generic        | 3        | 0.53%   |
| 5.15.0-47-generic        | 3        | 0.53%   |
| 5.13.0-28-generic        | 3        | 0.53%   |
| 5.12.4-desktop-1omv4050  | 3        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 111      | 21.47%  |
| 4.15.0  | 48       | 9.28%   |
| 5.15.0  | 40       | 7.74%   |
| 5.13.0  | 29       | 5.61%   |
| 5.8.0   | 27       | 5.22%   |
| 5.11.0  | 27       | 5.22%   |
| 5.16.7  | 26       | 5.03%   |
| 5.10.14 | 18       | 3.48%   |
| 5.3.0   | 16       | 3.09%   |
| 5.10.0  | 16       | 3.09%   |
| 5.0.0   | 16       | 3.09%   |
| 5.19.0  | 9        | 1.74%   |
| 6.1.1   | 7        | 1.35%   |
| 4.18.16 | 7        | 1.35%   |
| 4.18.0  | 5        | 0.97%   |
| 6.0.8   | 3        | 0.58%   |
| 5.3.18  | 3        | 0.58%   |
| 5.12.4  | 3        | 0.58%   |
| 4.4.0   | 3        | 0.58%   |
| 6.2.6   | 2        | 0.39%   |
| 6.2.2   | 2        | 0.39%   |
| 6.1.4   | 2        | 0.39%   |
| 6.1.12  | 2        | 0.39%   |
| 6.0.6   | 2        | 0.39%   |
| 6.0.0   | 2        | 0.39%   |
| 5.9.0   | 2        | 0.39%   |
| 5.7.9   | 2        | 0.39%   |
| 5.19.10 | 2        | 0.39%   |
| 5.16.13 | 2        | 0.39%   |
| 5.15.2  | 2        | 0.39%   |
| 5.15.15 | 2        | 0.39%   |
| 5.14.0  | 2        | 0.39%   |
| 4.9.60  | 2        | 0.39%   |
| 4.19.0  | 2        | 0.39%   |
| 6.2.8   | 1        | 0.19%   |
| 6.0.3   | 1        | 0.19%   |
| 6.0.2   | 1        | 0.19%   |
| 6.0.16  | 1        | 0.19%   |
| 6.0.12  | 1        | 0.19%   |
| 6.0.10  | 1        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 112      | 21.88%  |
| 5.15    | 49       | 9.57%   |
| 4.15    | 48       | 9.38%   |
| 5.10    | 40       | 7.81%   |
| 5.13    | 34       | 6.64%   |
| 5.8     | 31       | 6.05%   |
| 5.16    | 29       | 5.66%   |
| 5.11    | 29       | 5.66%   |
| 5.3     | 19       | 3.71%   |
| 5.0     | 18       | 3.52%   |
| 5.19    | 15       | 2.93%   |
| 6.0     | 12       | 2.34%   |
| 4.18    | 12       | 2.34%   |
| 6.1     | 11       | 2.15%   |
| 5.9     | 7        | 1.37%   |
| 5.12    | 6        | 1.17%   |
| 6.2     | 5        | 0.98%   |
| 5.7     | 4        | 0.78%   |
| 5.6     | 4        | 0.78%   |
| 5.17    | 4        | 0.78%   |
| 5.14    | 4        | 0.78%   |
| 5.5     | 3        | 0.59%   |
| 5.2     | 3        | 0.59%   |
| 5.18    | 3        | 0.59%   |
| 4.9     | 3        | 0.59%   |
| 4.4     | 3        | 0.59%   |
| 4.19    | 3        | 0.59%   |
| 3.10    | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 455      | 97.85%  |
| i686   | 10       | 2.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 221      | 46.23%  |
| KDE5                     | 85       | 17.78%  |
| Unknown                  | 62       | 12.97%  |
| XFCE                     | 36       | 7.53%   |
| X-Cinnamon               | 21       | 4.39%   |
| KDE                      | 9        | 1.88%   |
| MATE                     | 7        | 1.46%   |
| LXQt                     | 6        | 1.26%   |
| Pantheon                 | 4        | 0.84%   |
| KDE4                     | 4        | 0.84%   |
| Budgie                   | 4        | 0.84%   |
| LXDE                     | 3        | 0.63%   |
| Unity                    | 2        | 0.42%   |
| sway                     | 2        | 0.42%   |
| GNOME Classic            | 2        | 0.42%   |
| Cinnamon                 | 2        | 0.42%   |
| awesome                  | 2        | 0.42%   |
| XSession                 | 1        | 0.21%   |
| Openbox                  | 1        | 0.21%   |
| i3                       | 1        | 0.21%   |
| Deepin                   | 1        | 0.21%   |
| BunsenLabs               | 1        | 0.21%   |
| /usr/bin/openbox-session | 1        | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 362      | 76.21%  |
| Wayland | 57       | 12%     |
| Unknown | 41       | 8.63%   |
| Tty     | 15       | 3.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 256      | 53.11%  |
| SDDM    | 84       | 17.43%  |
| GDM3    | 59       | 12.24%  |
| GDM     | 39       | 8.09%   |
| LightDM | 25       | 5.19%   |
| TDM     | 8        | 1.66%   |
| KDM     | 3        | 0.62%   |
| NODM    | 2        | 0.41%   |
| LXDM    | 2        | 0.41%   |
| GREETD  | 2        | 0.41%   |
| XDM     | 1        | 0.21%   |
| SLiM    | 1        | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| ja_JP       | 249      | 53.09%  |
| en_US       | 111      | 23.67%  |
| Unknown     | 62       | 13.22%  |
| pt_BR       | 12       | 2.56%   |
| zh_CN       | 8        | 1.71%   |
| en_GB       | 8        | 1.71%   |
| it_IT       | 2        | 0.43%   |
| en_AU       | 2        | 0.43%   |
| en_AG       | 2        | 0.43%   |
| C           | 2        | 0.43%   |
| UTF-8       | 1        | 0.21%   |
| sr_RS       | 1        | 0.21%   |
| sk_SK       | 1        | 0.21%   |
| ru_RU       | 1        | 0.21%   |
| ja_JP.utf-8 | 1        | 0.21%   |
| fr_FR       | 1        | 0.21%   |
| fr_CA       | 1        | 0.21%   |
| es_ES       | 1        | 0.21%   |
| en_IN       | 1        | 0.21%   |
| de_DE       | 1        | 0.21%   |
| af_ZA       | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 288      | 61.28%  |
| EFI  | 182      | 38.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 363      | 77.07%  |
| Overlay | 51       | 10.83%  |
| Btrfs   | 23       | 4.88%   |
| Xfs     | 14       | 2.97%   |
| Unknown | 12       | 2.55%   |
| Zfs     | 4        | 0.85%   |
| Jfs     | 2        | 0.42%   |
| F2fs    | 1        | 0.21%   |
| Ext3    | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 289      | 61.23%  |
| GPT     | 142      | 30.08%  |
| MBR     | 41       | 8.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 354      | 74.68%  |
| Yes       | 120      | 25.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 315      | 66.18%  |
| Yes       | 161      | 33.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 113      | 24.46%  |
| ASRock              | 91       | 19.7%   |
| Gigabyte Technology | 63       | 13.64%  |
| MSI                 | 44       | 9.52%   |
| Hewlett-Packard     | 28       | 6.06%   |
| Dell                | 22       | 4.76%   |
| MouseComputer       | 10       | 2.16%   |
| NEC Computers       | 9        | 1.95%   |
| Lenovo              | 8        | 1.73%   |
| Intel               | 8        | 1.73%   |
| Biostar             | 8        | 1.73%   |
| ECS                 | 7        | 1.52%   |
| Unknown             | 7        | 1.52%   |
| Fujitsu             | 6        | 1.3%    |
| MCJ                 | 4        | 0.87%   |
| Gateway             | 4        | 0.87%   |
| Wistron             | 3        | 0.65%   |
| Shuttle             | 3        | 0.65%   |
| Pegatron            | 3        | 0.65%   |
| Foxconn             | 3        | 0.65%   |
| Supermicro          | 2        | 0.43%   |
| Onkyo               | 2        | 0.43%   |
| EPSON DIRECT        | 2        | 0.43%   |
| Acer                | 2        | 0.43%   |
| XFX                 | 1        | 0.22%   |
| UNITCOM             | 1        | 0.22%   |
| IBM                 | 1        | 0.22%   |
| Huanan              | 1        | 0.22%   |
| HC                  | 1        | 0.22%   |
| GALAX               | 1        | 0.22%   |
| FIC                 | 1        | 0.22%   |
| BESSTAR Tech        | 1        | 0.22%   |
| Apple               | 1        | 0.22%   |
| AOpen               | 1        | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 11       | 2.38%   |
| Unknown                                    | 7        | 1.52%   |
| HP ProDesk 600 G1 SFF                      | 5        | 1.08%   |
| ASRock Z87 Killer                          | 4        | 0.87%   |
| ASRock B450M Pro4                          | 4        | 0.87%   |
| NEC Computers Express5800/S70 [N8100-9021] | 3        | 0.65%   |
| MSI MS-7A40                                | 3        | 0.65%   |
| HP Z620 Workstation                        | 3        | 0.65%   |
| ECS G31T-M                                 | 3        | 0.65%   |
| Dell Precision WorkStation T3500           | 3        | 0.65%   |
| Dell OptiPlex 3020                         | 3        | 0.65%   |
| ASUS P7H55-M                               | 3        | 0.65%   |
| ASRock Prime Series                        | 3        | 0.65%   |
| ASRock J5005-ITX                           | 3        | 0.65%   |
| ASRock B460M Pro4                          | 3        | 0.65%   |
| ASRock B450 Pro4                           | 3        | 0.65%   |
| ASRock B450 Gaming-ITX/ac                  | 3        | 0.65%   |
| ASRock A300M-STX                           | 3        | 0.65%   |
| Onkyo ONKYOPC                              | 2        | 0.43%   |
| MSI MS-7D16                                | 2        | 0.43%   |
| MSI MS-7C95                                | 2        | 0.43%   |
| MSI MS-7C94                                | 2        | 0.43%   |
| MSI MS-7C37                                | 2        | 0.43%   |
| MSI MS-7C35                                | 2        | 0.43%   |
| MSI MS-7C02                                | 2        | 0.43%   |
| MSI MS-7B79                                | 2        | 0.43%   |
| MSI MS-7A72                                | 2        | 0.43%   |
| MSI MS-7865                                | 2        | 0.43%   |
| MouseComputer B360M                        | 2        | 0.43%   |
| HP ProDesk 600 G4 SFF                      | 2        | 0.43%   |
| HP Compaq dc7700p Small Form Factor        | 2        | 0.43%   |
| Gigabyte Z77X-UD3H                         | 2        | 0.43%   |
| Gigabyte Z170X-Gaming 3                    | 2        | 0.43%   |
| Gigabyte H67A-D3H-B3                       | 2        | 0.43%   |
| Gigabyte GA-MA69G-S3H                      | 2        | 0.43%   |
| Gigabyte G33-DS3R                          | 2        | 0.43%   |
| Gigabyte EP45-UD3R                         | 2        | 0.43%   |
| Gigabyte 970A-D3P                          | 2        | 0.43%   |
| Fujitsu PRIMERGY TX1310 M1                 | 2        | 0.43%   |
| Dell OptiPlex 3010                         | 2        | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 23       | 4.98%   |
| ASUS TUF                  | 13       | 2.81%   |
| ASUS All                  | 11       | 2.38%   |
| ASUS ROG                  | 9        | 1.95%   |
| HP ProDesk                | 8        | 1.73%   |
| Dell OptiPlex             | 8        | 1.73%   |
| ASRock B450               | 7        | 1.52%   |
| Unknown                   | 7        | 1.52%   |
| Lenovo ThinkCentre        | 6        | 1.3%    |
| HP Compaq                 | 6        | 1.3%    |
| Dell Vostro               | 6        | 1.3%    |
| ASUS P8Z77-V              | 5        | 1.08%   |
| ASRock Z87                | 5        | 1.08%   |
| Gigabyte Z390             | 4        | 0.87%   |
| Dell Precision            | 4        | 0.87%   |
| ASRock Prime              | 4        | 0.87%   |
| ASRock B450M              | 4        | 0.87%   |
| NEC Computers Express5800 | 3        | 0.65%   |
| MSI MS-7A40               | 3        | 0.65%   |
| HP Z620                   | 3        | 0.65%   |
| ECS G31T-M                | 3        | 0.65%   |
| ASUS P7H55-M              | 3        | 0.65%   |
| ASRock X370               | 3        | 0.65%   |
| ASRock J5005-ITX          | 3        | 0.65%   |
| ASRock B460M              | 3        | 0.65%   |
| ASRock A300M-STX          | 3        | 0.65%   |
| Onkyo ONKYOPC             | 2        | 0.43%   |
| MSI MS-7D16               | 2        | 0.43%   |
| MSI MS-7C95               | 2        | 0.43%   |
| MSI MS-7C94               | 2        | 0.43%   |
| MSI MS-7C37               | 2        | 0.43%   |
| MSI MS-7C35               | 2        | 0.43%   |
| MSI MS-7C02               | 2        | 0.43%   |
| MSI MS-7B79               | 2        | 0.43%   |
| MSI MS-7A72               | 2        | 0.43%   |
| MSI MS-7865               | 2        | 0.43%   |
| MouseComputer B360M       | 2        | 0.43%   |
| HP EliteDesk              | 2        | 0.43%   |
| Gigabyte Z77X-UD3H        | 2        | 0.43%   |
| Gigabyte Z170X-Gaming     | 2        | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 56       | 12.12%  |
| 2013 | 49       | 10.61%  |
| 2012 | 49       | 10.61%  |
| 2020 | 40       | 8.66%   |
| 2019 | 30       | 6.49%   |
| 2010 | 28       | 6.06%   |
| 2016 | 27       | 5.84%   |
| 2009 | 25       | 5.41%   |
| 2021 | 24       | 5.19%   |
| 2011 | 22       | 4.76%   |
| 2015 | 20       | 4.33%   |
| 2014 | 20       | 4.33%   |
| 2017 | 19       | 4.11%   |
| 2008 | 18       | 3.9%    |
| 2007 | 18       | 3.9%    |
| 2006 | 8        | 1.73%   |
| 2005 | 5        | 1.08%   |
| 2022 | 3        | 0.65%   |
| 2003 | 1        | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 462      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 446      | 96.33%  |
| Enabled  | 17       | 3.67%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 462      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 107      | 22.38%  |
| 16.01-24.0      | 105      | 21.97%  |
| 32.01-64.0      | 71       | 14.85%  |
| 3.01-4.0        | 67       | 14.02%  |
| 4.01-8.0        | 66       | 13.81%  |
| 64.01-256.0     | 25       | 5.23%   |
| 24.01-32.0      | 15       | 3.14%   |
| 1.01-2.0        | 14       | 2.93%   |
| 2.01-3.0        | 6        | 1.26%   |
| More than 256.0 | 1        | 0.21%   |
| 0.51-1.0        | 1        | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 218      | 41.52%  |
| 2.01-3.0   | 103      | 19.62%  |
| 3.01-4.0   | 61       | 11.62%  |
| 4.01-8.0   | 53       | 10.1%   |
| 0.51-1.0   | 49       | 9.33%   |
| 8.01-16.0  | 23       | 4.38%   |
| 16.01-24.0 | 8        | 1.52%   |
| 0.01-0.5   | 6        | 1.14%   |
| 24.01-32.0 | 3        | 0.57%   |
| 32.01-64.0 | 1        | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 198      | 41.08%  |
| 2      | 141      | 29.25%  |
| 3      | 69       | 14.32%  |
| 4      | 39       | 8.09%   |
| 5      | 18       | 3.73%   |
| 6      | 7        | 1.45%   |
| 7      | 5        | 1.04%   |
| 0      | 3        | 0.62%   |
| 11     | 1        | 0.21%   |
| 9      | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 277      | 59.06%  |
| No        | 192      | 40.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 461      | 99.78%  |
| No        | 1        | 0.22%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 309      | 66.17%  |
| Yes       | 158      | 33.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 327      | 69.13%  |
| Yes       | 146      | 30.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Japan   | 462      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Tokyo       | 32       | 6.52%   |
| Yokohama    | 26       | 5.3%    |
| Osaka       | 23       | 4.68%   |
| Shinjuku    | 16       | 3.26%   |
| Nagoya      | 15       | 3.05%   |
| Minato-ku   | 11       | 2.24%   |
| Sapporo     | 9        | 1.83%   |
| Fukuoka     | 9        | 1.83%   |
| Tsukuba     | 8        | 1.63%   |
| Saitama     | 7        | 1.43%   |
| Niigata     | 6        | 1.22%   |
| Minatomirai | 6        | 1.22%   |
| Okayama     | 5        | 1.02%   |
| Miyazaki    | 5        | 1.02%   |
| Kobe        | 5        | 1.02%   |
| Kawasaki    | 5        | 1.02%   |
| Hiroshima   | 5        | 1.02%   |
| Toyokawa    | 4        | 0.81%   |
| Takamatsu   | 4        | 0.81%   |
| Okazaki     | 4        | 0.81%   |
| Mito        | 4        | 0.81%   |
| Matsudo     | 4        | 0.81%   |
| Maebashi    | 4        | 0.81%   |
| Kumamoto    | 4        | 0.81%   |
| Koto        | 4        | 0.81%   |
| Kochi       | 4        | 0.81%   |
| Honcho      | 4        | 0.81%   |
| Gifu City   | 4        | 0.81%   |
| Chiba       | 4        | 0.81%   |
| Toyama      | 3        | 0.61%   |
| Tokushima   | 3        | 0.61%   |
| Taito       | 3        | 0.61%   |
| Suita       | 3        | 0.61%   |
| Shibuya     | 3        | 0.61%   |
| Setagaya-ku | 3        | 0.61%   |
| Nagasaki    | 3        | 0.61%   |
| Nagano      | 3        | 0.61%   |
| Morioka     | 3        | 0.61%   |
| Kyoto       | 3        | 0.61%   |
| Kohoku-ku   | 3        | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 162      | 258    | 19.47%  |
| WDC                         | 149      | 259    | 17.91%  |
| Samsung Electronics         | 77       | 112    | 9.25%   |
| Hitachi                     | 53       | 70     | 6.37%   |
| Crucial                     | 52       | 72     | 6.25%   |
| Toshiba                     | 47       | 65     | 5.65%   |
| SanDisk                     | 38       | 57     | 4.57%   |
| Intel                       | 31       | 44     | 3.73%   |
| A-DATA Technology           | 22       | 24     | 2.64%   |
| SPCC                        | 17       | 22     | 2.04%   |
| Phison                      | 12       | 17     | 1.44%   |
| Kingston                    | 12       | 14     | 1.44%   |
| Unknown                     | 10       | 13     | 1.2%    |
| HGST                        | 10       | 12     | 1.2%    |
| Transcend                   | 8        | 10     | 0.96%   |
| Silicon Motion              | 7        | 14     | 0.84%   |
| Plextor                     | 6        | 8      | 0.72%   |
| OCZ                         | 6        | 6      | 0.72%   |
| Micron/Crucial Technology   | 6        | 8      | 0.72%   |
| Dogfish                     | 6        | 6      | 0.72%   |
| Unknown                     | 6        | 7      | 0.72%   |
| Micron Technology           | 5        | 6      | 0.6%    |
| China                       | 5        | 8      | 0.6%    |
| Patriot                     | 4        | 4      | 0.48%   |
| Maxtor                      | 4        | 6      | 0.48%   |
| KIOXIA-EXCERIA              | 4        | 4      | 0.48%   |
| Green House                 | 4        | 5      | 0.48%   |
| Teclast                     | 3        | 3      | 0.36%   |
| Phison Electronics          | 3        | 4      | 0.36%   |
| Lexar                       | 3        | 4      | 0.36%   |
| KLEVV                       | 3        | 8      | 0.36%   |
| Hewlett-Packard             | 3        | 4      | 0.36%   |
| Zheino                      | 2        | 2      | 0.24%   |
| Team                        | 2        | 2      | 0.24%   |
| Netac                       | 2        | 2      | 0.24%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.24%   |
| MARVELL                     | 2        | 4      | 0.24%   |
| KingDian                    | 2        | 2      | 0.24%   |
| JMicron Technology          | 2        | 2      | 0.24%   |
| Fujitsu                     | 2        | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB             | 16       | 1.68%   |
| Seagate ST4000DM004-2CV104 4TB     | 10       | 1.05%   |
| Crucial CT500MX500SSD1 500GB       | 10       | 1.05%   |
| Crucial CT240BX500SSD1 240GB       | 9        | 0.94%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 8        | 0.84%   |
| Toshiba DT01ACA200 2TB             | 8        | 0.84%   |
| Seagate ST2000DM001-1CH164 2TB     | 8        | 0.84%   |
| Seagate ST500DM002-1BD142 500GB    | 7        | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB     | 7        | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB     | 7        | 0.73%   |
| WDC WD20EZRX-00DC0B0 2TB           | 6        | 0.63%   |
| Seagate ST3500418AS 500GB          | 6        | 0.63%   |
| Seagate ST2000DM006-2DM164 2TB     | 6        | 0.63%   |
| Unknown                            | 6        | 0.63%   |
| WDC WD10EZEX-00BN5A0 1TB           | 5        | 0.52%   |
| WDC WD10EADS-22M2B0 1TB            | 5        | 0.52%   |
| WDC WD10EADS-00L5B1 1TB            | 5        | 0.52%   |
| SPCC Solid State Disk 512GB        | 5        | 0.52%   |
| SPCC Solid State Disk 256GB        | 5        | 0.52%   |
| Seagate ST2000DM005-2CW102 2TB     | 5        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB     | 5        | 0.52%   |
| SanDisk SD6SF1M128G1022I 128GB SSD | 5        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB     | 5        | 0.52%   |
| Samsung SSD 860 EVO 250GB          | 5        | 0.52%   |
| Kingston SV300S37A120G 120GB SSD   | 5        | 0.52%   |
| Crucial CT525MX300SSD1 528GB       | 5        | 0.52%   |
| Crucial CT120BX500SSD1 120GB       | 5        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB        | 5        | 0.52%   |
| WDC WD5000AZLX-60K2TA0 500GB       | 4        | 0.42%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 4        | 0.42%   |
| WDC WD10EADS-00M2B0 1TB            | 4        | 0.42%   |
| Seagate ST9500325AS 500GB          | 4        | 0.42%   |
| Seagate ST8000DM004-2CX188 8TB     | 4        | 0.42%   |
| Seagate ST3160318AS 160GB          | 4        | 0.42%   |
| Seagate ST31000528AS 1TB           | 4        | 0.42%   |
| Seagate ST250DM000-1BD141 250GB    | 4        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB     | 4        | 0.42%   |
| Seagate Expansion+ 2TB             | 4        | 0.42%   |
| Samsung SSD 860 EVO 500GB          | 4        | 0.42%   |
| Samsung SSD 840 Series 120GB       | 4        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 158      | 250    | 36.74%  |
| WDC                 | 134      | 217    | 31.16%  |
| Hitachi             | 53       | 70     | 12.33%  |
| Toshiba             | 43       | 59     | 10%     |
| Samsung Electronics | 17       | 19     | 3.95%   |
| HGST                | 10       | 12     | 2.33%   |
| Maxtor              | 4        | 6      | 0.93%   |
| Hewlett-Packard     | 3        | 4      | 0.7%    |
| MARVELL             | 2        | 4      | 0.47%   |
| Fujitsu             | 2        | 2      | 0.47%   |
| StoreJet            | 1        | 1      | 0.23%   |
| Quantum             | 1        | 1      | 0.23%   |
| KESU                | 1        | 1      | 0.23%   |
| ASMT                | 1        | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 49       | 67     | 16.5%   |
| Samsung Electronics | 44       | 59     | 14.81%  |
| SanDisk             | 28       | 37     | 9.43%   |
| A-DATA Technology   | 19       | 21     | 6.4%    |
| Intel               | 18       | 23     | 6.06%   |
| WDC                 | 17       | 26     | 5.72%   |
| SPCC                | 16       | 21     | 5.39%   |
| Kingston            | 12       | 14     | 4.04%   |
| Transcend           | 7        | 9      | 2.36%   |
| Plextor             | 6        | 8      | 2.02%   |
| OCZ                 | 6        | 6      | 2.02%   |
| Dogfish             | 6        | 6      | 2.02%   |
| Unknown             | 6        | 7      | 2.02%   |
| China               | 5        | 8      | 1.68%   |
| Toshiba             | 4        | 5      | 1.35%   |
| Green House         | 4        | 5      | 1.35%   |
| Unknown             | 3        | 3      | 1.01%   |
| Seagate             | 3        | 5      | 1.01%   |
| Micron Technology   | 3        | 4      | 1.01%   |
| Lexar               | 3        | 4      | 1.01%   |
| KLEVV               | 3        | 8      | 1.01%   |
| Teclast             | 2        | 2      | 0.67%   |
| Team                | 2        | 2      | 0.67%   |
| Patriot             | 2        | 2      | 0.67%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.67%   |
| KingDian            | 2        | 2      | 0.67%   |
| BUFFALO             | 2        | 3      | 0.67%   |
| Apple               | 2        | 2      | 0.67%   |
| Apacer              | 2        | 2      | 0.67%   |
| AEGO                | 2        | 2      | 0.67%   |
| Zheino              | 1        | 1      | 0.34%   |
| XSTAR               | 1        | 1      | 0.34%   |
| TCSUNBOW            | 1        | 1      | 0.34%   |
| SUNEAST             | 1        | 1      | 0.34%   |
| SATA3 51            | 1        | 2      | 0.34%   |
| Palit               | 1        | 1      | 0.34%   |
| Netac               | 1        | 1      | 0.34%   |
| MARSHAL             | 1        | 1      | 0.34%   |
| LuminouTek          | 1        | 1      | 0.34%   |
| Lite-On             | 1        | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 335      | 647    | 48.48%  |
| SSD     | 244      | 383    | 35.31%  |
| NVMe    | 100      | 167    | 14.47%  |
| Unknown | 11       | 20     | 1.59%   |
| MMC     | 1        | 1      | 0.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 431      | 1010   | 77.38%  |
| NVMe | 100      | 166    | 17.95%  |
| SAS  | 25       | 41     | 4.49%   |
| MMC  | 1        | 1      | 0.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 320      | 552    | 50.55%  |
| 0.51-1.0   | 137      | 201    | 21.64%  |
| 1.01-2.0   | 91       | 130    | 14.38%  |
| 3.01-4.0   | 34       | 54     | 5.37%   |
| 4.01-10.0  | 28       | 58     | 4.42%   |
| 2.01-3.0   | 21       | 33     | 3.32%   |
| 10.01-20.0 | 2        | 2      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 128      | 26.12%  |
| 251-500        | 82       | 16.73%  |
| 501-1000       | 64       | 13.06%  |
| More than 3000 | 49       | 10%     |
| 1001-2000      | 43       | 8.78%   |
| 1-20           | 34       | 6.94%   |
| 2001-3000      | 31       | 6.33%   |
| 51-100         | 26       | 5.31%   |
| Unknown        | 25       | 5.1%    |
| 21-50          | 8        | 1.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 194      | 37.89%  |
| 21-50          | 76       | 14.84%  |
| 101-250        | 52       | 10.16%  |
| 51-100         | 46       | 8.98%   |
| 251-500        | 34       | 6.64%   |
| 501-1000       | 32       | 6.25%   |
| 1001-2000      | 25       | 4.88%   |
| Unknown        | 25       | 4.88%   |
| More than 3000 | 19       | 3.71%   |
| 2001-3000      | 9        | 1.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB            | 5        | 5      | 10%     |
| SanDisk SD6SF1M128G1022I 128GB SSD | 5        | 5      | 10%     |
| Seagate ST9500325AS 500GB          | 3        | 4      | 6%      |
| Seagate ST2000DM001-1CH164 2TB     | 2        | 2      | 4%      |
| WDC WD5000LPLX-66ZNTT0 500GB       | 1        | 1      | 2%      |
| WDC WD40EZRZ-00GXCB0 4TB           | 1        | 1      | 2%      |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 2      | 2%      |
| WDC WD30EZRX-00D8PB0 3TB           | 1        | 1      | 2%      |
| WDC WD25EZRX-00MMMB0 2TB           | 1        | 1      | 2%      |
| WDC WD10EALX-009BA0 1TB            | 1        | 1      | 2%      |
| WDC WD10EACS-00D6B0 1TB            | 1        | 2      | 2%      |
| Transcend TS240GSSD220S 240GB      | 1        | 1      | 2%      |
| SPCC Solid State DiskB28 128GB     | 1        | 1      | 2%      |
| SPCC Solid State Disk 512GB        | 1        | 2      | 2%      |
| Seagate ST9320320AS 320GB          | 1        | 1      | 2%      |
| Seagate ST3500418AS 500GB          | 1        | 1      | 2%      |
| Seagate ST3320820AS 320GB          | 1        | 1      | 2%      |
| Seagate ST3250310AS 250GB          | 1        | 2      | 2%      |
| Seagate ST3120026A 120GB           | 1        | 1      | 2%      |
| Seagate ST31000528AS 1TB           | 1        | 1      | 2%      |
| Seagate ST31000333AS 1TB           | 1        | 1      | 2%      |
| Seagate ST3000VM002-1ET166 3TB     | 1        | 1      | 2%      |
| Seagate ST250DM000-1BD141 250GB    | 1        | 1      | 2%      |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 2%      |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 1      | 2%      |
| Seagate ST2000DX001-1NS164 2TB     | 1        | 1      | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 2%      |
| Seagate ST1000DM003-1ER162 1TB     | 1        | 1      | 2%      |
| Kingston SV300S37A120G 120GB SSD   | 1        | 1      | 2%      |
| Hitachi HTS727575A9E364 752GB      | 1        | 1      | 2%      |
| Hitachi HTS541080G9SA00 80GB       | 1        | 1      | 2%      |
| Hitachi HDT725032VLA360 320GB      | 1        | 1      | 2%      |
| Hitachi HDT721032SLA360 320GB      | 1        | 1      | 2%      |
| Hitachi HDT721010SLA360 1TB        | 1        | 1      | 2%      |
| Hitachi HDS721010DLE630 1TB        | 1        | 1      | 2%      |
| Hitachi HDS721010CLA332 1TB        | 1        | 1      | 2%      |
| Crucial CT480M500SSD1 480GB        | 1        | 1      | 2%      |
| Corsair CSSD-F60GB2 64GB           | 1        | 1      | 2%      |
| A-DATA Technology SP900 256GB SSD  | 1        | 1      | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 18       | 21     | 37.5%   |
| WDC               | 12       | 14     | 25%     |
| Hitachi           | 6        | 7      | 12.5%   |
| SanDisk           | 5        | 5      | 10.42%  |
| SPCC              | 2        | 3      | 4.17%   |
| Transcend         | 1        | 1      | 2.08%   |
| Kingston          | 1        | 1      | 2.08%   |
| Crucial           | 1        | 1      | 2.08%   |
| Corsair           | 1        | 1      | 2.08%   |
| A-DATA Technology | 1        | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 18       | 21     | 50%     |
| WDC     | 12       | 14     | 33.33%  |
| Hitachi | 6        | 7      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 31       | 42     | 72.09%  |
| SSD  | 12       | 13     | 27.91%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 309      | 824    | 62.42%  |
| Works    | 148      | 339    | 29.9%   |
| Malfunc  | 38       | 55     | 7.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 313      | 47.07%  |
| AMD                              | 141      | 21.2%   |
| ASMedia Technology               | 38       | 5.71%   |
| Samsung Electronics              | 26       | 3.91%   |
| Marvell Technology Group         | 22       | 3.31%   |
| JMicron Technology               | 19       | 2.86%   |
| SanDisk                          | 17       | 2.56%   |
| Phison Electronics               | 17       | 2.56%   |
| Silicon Motion                   | 10       | 1.5%    |
| Micron/Crucial Technology        | 10       | 1.5%    |
| VIA Technologies                 | 9        | 1.35%   |
| Nvidia                           | 7        | 1.05%   |
| ADATA Technology                 | 5        | 0.75%   |
| Broadcom / LSI                   | 4        | 0.6%    |
| Seagate Technology               | 3        | 0.45%   |
| Micron Technology                | 3        | 0.45%   |
| Adaptec                          | 3        | 0.45%   |
| Silicon Image                    | 2        | 0.3%    |
| Realtek Semiconductor            | 2        | 0.3%    |
| MAXIO Technology (Hangzhou)      | 2        | 0.3%    |
| KIOXIA                           | 2        | 0.3%    |
| HighPoint Technologies           | 2        | 0.3%    |
| Yangtze Memory Technologies      | 1        | 0.15%   |
| ULi Electronics                  | 1        | 0.15%   |
| Toshiba America Info Systems     | 1        | 0.15%   |
| SK hynix                         | 1        | 0.15%   |
| Silicon Integrated Systems [SiS] | 1        | 0.15%   |
| Promise Technology               | 1        | 0.15%   |
| LSI Logic / Symbios Logic        | 1        | 0.15%   |
| Kingston Technology Company      | 1        | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 81       | 9.53%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 33       | 3.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 33       | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32       | 3.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 29       | 3.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25       | 2.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 23       | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21       | 2.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 20       | 2.35%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20       | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 19       | 2.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 16       | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16       | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16       | 1.88%   |
| Intel SATA Controller [RAID mode]                                                       | 14       | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 12       | 1.41%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 12       | 1.41%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 1.41%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10       | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 10       | 1.18%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 9        | 1.06%   |
| AMD FCH IDE Controller                                                                  | 9        | 1.06%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 8        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 0.94%   |
| AMD 300 Series Chipset SATA Controller                                                  | 8        | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 0.82%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 7        | 0.82%   |
| JMicron JMB368 IDE controller                                                           | 7        | 0.82%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 7        | 0.82%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 7        | 0.82%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 0.82%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 6        | 0.71%   |
| Phison E12 NVMe Controller                                                              | 6        | 0.71%   |
| Intel SSD 660P Series                                                                   | 6        | 0.71%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6        | 0.71%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 6        | 0.71%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 367      | 57.34%  |
| IDE  | 125      | 19.53%  |
| NVMe | 102      | 15.94%  |
| RAID | 35       | 5.47%   |
| SAS  | 6        | 0.94%   |
| SCSI | 5        | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 315      | 68.18%  |
| AMD    | 147      | 31.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 12       | 2.59%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 10       | 2.16%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9        | 1.94%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.72%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 7        | 1.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 6        | 1.29%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 5        | 1.08%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 5        | 1.08%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 1.08%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 5        | 1.08%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 1.08%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 5        | 1.08%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 5        | 1.08%   |
| AMD Athlon 200GE with Radeon Vega Graphics  | 5        | 1.08%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 4        | 0.86%   |
| Intel Core i5-4570TE CPU @ 2.70GHz          | 4        | 0.86%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.86%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.86%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 0.86%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 4        | 0.86%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 4        | 0.86%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 4        | 0.86%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 0.86%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 0.86%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 4        | 0.86%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 3        | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.65%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 3        | 0.65%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.65%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 3        | 0.65%   |
| Intel Core i5-6600 CPU @ 3.30GHz            | 3        | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.65%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.65%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3        | 0.65%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3        | 0.65%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 0.65%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 0.65%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 3        | 0.65%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz       | 3        | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 80       | 17.28%  |
| Intel Core i5           | 66       | 14.25%  |
| Intel Core i3           | 35       | 7.56%   |
| AMD Ryzen 7             | 33       | 7.13%   |
| AMD Ryzen 5             | 33       | 7.13%   |
| Intel Xeon              | 29       | 6.26%   |
| Intel Core 2 Duo        | 20       | 4.32%   |
| Intel Celeron           | 17       | 3.67%   |
| Intel Core 2 Quad       | 12       | 2.59%   |
| Other                   | 10       | 2.16%   |
| AMD Ryzen 9             | 10       | 2.16%   |
| Intel Core 2            | 9        | 1.94%   |
| AMD Athlon              | 9        | 1.94%   |
| Intel Pentium           | 8        | 1.73%   |
| Intel Core i9           | 8        | 1.73%   |
| AMD A10                 | 8        | 1.73%   |
| AMD Ryzen 3             | 6        | 1.3%    |
| AMD Phenom II X4        | 6        | 1.3%    |
| AMD FX                  | 6        | 1.3%    |
| Intel Pentium 4         | 5        | 1.08%   |
| AMD Athlon 64 X2        | 5        | 1.08%   |
| AMD A8                  | 5        | 1.08%   |
| Intel Pentium Gold      | 4        | 0.86%   |
| Intel Pentium Dual-Core | 4        | 0.86%   |
| Intel Pentium Silver    | 3        | 0.65%   |
| Intel Atom              | 3        | 0.65%   |
| AMD Sempron             | 2        | 0.43%   |
| AMD Ryzen Threadripper  | 2        | 0.43%   |
| AMD Phenom II X6        | 2        | 0.43%   |
| AMD Phenom              | 2        | 0.43%   |
| AMD Athlon II X4        | 2        | 0.43%   |
| AMD Athlon II X2        | 2        | 0.43%   |
| AMD Athlon Dual Core    | 2        | 0.43%   |
| AMD Athlon 64           | 2        | 0.43%   |
| AMD A6                  | 2        | 0.43%   |
| AMD A4                  | 2        | 0.43%   |
| AMD A12                 | 2        | 0.43%   |
| Intel Pentium Dual      | 1        | 0.22%   |
| Intel Pentium D         | 1        | 0.22%   |
| Intel Core 2 Extreme    | 1        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 171      | 36.93%  |
| 2      | 132      | 28.51%  |
| 6      | 71       | 15.33%  |
| 8      | 50       | 10.8%   |
| 1      | 12       | 2.59%   |
| 16     | 9        | 1.94%   |
| 12     | 6        | 1.3%    |
| 10     | 4        | 0.86%   |
| 3      | 4        | 0.86%   |
| 20     | 2        | 0.43%   |
| 32     | 1        | 0.22%   |
| 14     | 1        | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 456      | 98.7%   |
| 2      | 6        | 1.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 282      | 60.91%  |
| 1      | 181      | 39.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 457      | 98.49%  |
| Unknown        | 4        | 0.86%   |
| 32-bit         | 3        | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 103      | 21.41%  |
| 0x306c3    | 34       | 7.07%   |
| 0x306a9    | 33       | 6.86%   |
| 0x08701021 | 24       | 4.99%   |
| 0x1067a    | 23       | 4.78%   |
| 0x206a7    | 21       | 4.37%   |
| 0x906ea    | 18       | 3.74%   |
| 0x506e3    | 17       | 3.53%   |
| 0x906e9    | 11       | 2.29%   |
| 0x906ed    | 8        | 1.66%   |
| 0x106e5    | 8        | 1.66%   |
| 0x06003106 | 8        | 1.66%   |
| 0x0800820d | 7        | 1.46%   |
| 0x306f2    | 6        | 1.25%   |
| 0x010000db | 6        | 1.25%   |
| 0xa0655    | 5        | 1.04%   |
| 0x6fb      | 5        | 1.04%   |
| 0x206d7    | 5        | 1.04%   |
| 0x0a201016 | 5        | 1.04%   |
| 0x06001119 | 5        | 1.04%   |
| 0xa0653    | 4        | 0.83%   |
| 0x706a1    | 4        | 0.83%   |
| 0x6f6      | 4        | 0.83%   |
| 0x50654    | 4        | 0.83%   |
| 0x306e4    | 4        | 0.83%   |
| 0x10676    | 4        | 0.83%   |
| 0x08101016 | 4        | 0.83%   |
| 0x0810100b | 4        | 0.83%   |
| 0x010000c8 | 4        | 0.83%   |
| 0x906eb    | 3        | 0.62%   |
| 0x206c2    | 3        | 0.62%   |
| 0x20655    | 3        | 0.62%   |
| 0x0a50000c | 3        | 0.62%   |
| 0x08701013 | 3        | 0.62%   |
| 0x08600106 | 3        | 0.62%   |
| 0x08108109 | 3        | 0.62%   |
| 0x08001138 | 3        | 0.62%   |
| 0x0600063e | 3        | 0.62%   |
| 0x03000027 | 3        | 0.62%   |
| 0xf43      | 2        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 52       | 11.23%  |
| Haswell          | 48       | 10.37%  |
| IvyBridge        | 43       | 9.29%   |
| Zen 2            | 38       | 8.21%   |
| Penryn           | 32       | 6.91%   |
| SandyBridge      | 30       | 6.48%   |
| Skylake          | 25       | 5.4%    |
| Zen              | 21       | 4.54%   |
| Zen+             | 17       | 3.67%   |
| Zen 3            | 17       | 3.67%   |
| Core             | 17       | 3.67%   |
| K10              | 16       | 3.46%   |
| CometLake        | 15       | 3.24%   |
| Nehalem          | 12       | 2.59%   |
| Westmere         | 10       | 2.16%   |
| K8 Hammer        | 10       | 2.16%   |
| Steamroller      | 8        | 1.73%   |
| Piledriver       | 8        | 1.73%   |
| NetBurst         | 7        | 1.51%   |
| Unknown          | 7        | 1.51%   |
| Silvermont       | 5        | 1.08%   |
| Goldmont plus    | 4        | 0.86%   |
| Bulldozer        | 4        | 0.86%   |
| K10 Llano        | 3        | 0.65%   |
| Jaguar           | 3        | 0.65%   |
| Bonnell          | 3        | 0.65%   |
| Alderlake Hybrid | 3        | 0.65%   |
| Excavator        | 2        | 0.43%   |
| Icelake          | 1        | 0.22%   |
| Broadwell        | 1        | 0.22%   |
| Bobcat           | 1        | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 192      | 39.02%  |
| AMD                        | 160      | 32.52%  |
| Intel                      | 138      | 28.05%  |
| VIA Technologies           | 1        | 0.2%    |
| Matrox Electronics Systems | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18       | 3.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17       | 3.32%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13       | 2.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13       | 2.54%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12       | 2.34%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12       | 2.34%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 11       | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 2.15%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11       | 2.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11       | 2.15%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 10       | 1.95%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9        | 1.76%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 9        | 1.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 8        | 1.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8        | 1.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 7        | 1.37%   |
| Intel HD Graphics 530                                                                    | 7        | 1.37%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7        | 1.37%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6        | 1.17%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 6        | 1.17%   |
| Intel HD Graphics 630                                                                    | 6        | 1.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6        | 1.17%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 1.17%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5        | 0.98%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 5        | 0.98%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 5        | 0.98%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 5        | 0.98%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 5        | 0.98%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5        | 0.98%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 5        | 0.98%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 5        | 0.98%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 4        | 0.78%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 4        | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 0.78%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 4        | 0.78%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 4        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 0.78%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 4        | 0.78%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 173      | 37.12%  |
| 1 x AMD                  | 145      | 31.12%  |
| 1 x Intel                | 120      | 25.75%  |
| 2 x AMD                  | 6        | 1.29%   |
| 2 x Nvidia               | 5        | 1.07%   |
| AMD + Nvidia             | 5        | 1.07%   |
| Intel + Nvidia           | 4        | 0.86%   |
| Intel + 2 x Nvidia       | 2        | 0.43%   |
| Other                    | 1        | 0.21%   |
| 1 x VIA                  | 1        | 0.21%   |
| Intel + 2 x AMD          | 1        | 0.21%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.21%   |
| Intel + AMD              | 1        | 0.21%   |
| AMD + Matrox             | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 358      | 75.69%  |
| Proprietary | 101      | 21.35%  |
| Unknown     | 14       | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 177      | 36.88%  |
| 0.01-0.5   | 75       | 15.63%  |
| 0.51-1.0   | 65       | 13.54%  |
| 1.01-2.0   | 64       | 13.33%  |
| 3.01-4.0   | 40       | 8.33%   |
| 7.01-8.0   | 28       | 5.83%   |
| 5.01-6.0   | 15       | 3.13%   |
| 8.01-16.0  | 9        | 1.88%   |
| 16.01-24.0 | 5        | 1.04%   |
| 2.01-3.0   | 2        | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Dell                 | 43       | 8.7%    |
| IOD                  | 42       | 8.5%    |
| Goldstar             | 39       | 7.89%   |
| BenQ                 | 33       | 6.68%   |
| Mitsubishi           | 29       | 5.87%   |
| Iiyama               | 29       | 5.87%   |
| Acer                 | 28       | 5.67%   |
| Hewlett-Packard      | 21       | 4.25%   |
| Eizo                 | 21       | 4.25%   |
| Philips              | 19       | 3.85%   |
| Unknown              | 16       | 3.24%   |
| Samsung Electronics  | 14       | 2.83%   |
| Sharp                | 13       | 2.63%   |
| AOC                  | 13       | 2.63%   |
| Ancor Communications | 13       | 2.63%   |
| NEC Computers        | 11       | 2.23%   |
| Sony                 | 9        | 1.82%   |
| Lenovo               | 7        | 1.42%   |
| Idek Iiyama          | 7        | 1.42%   |
| Panasonic            | 6        | 1.21%   |
| LG Electronics       | 6        | 1.21%   |
| ViewSonic            | 5        | 1.01%   |
| Toshiba              | 5        | 1.01%   |
| Fujitsu              | 5        | 1.01%   |
| ASUSTek Computer     | 5        | 1.01%   |
| Onkyo                | 4        | 0.81%   |
| Hitachi              | 4        | 0.81%   |
| Unknown (XXX)        | 3        | 0.61%   |
| Unknown              | 3        | 0.61%   |
| ___                  | 2        | 0.4%    |
| SKY                  | 2        | 0.4%    |
| PTF                  | 2        | 0.4%    |
| Pixio                | 2        | 0.4%    |
| MPI                  | 2        | 0.4%    |
| LYC                  | 2        | 0.4%    |
| HKM                  | 2        | 0.4%    |
| BUFFALO              | 2        | 0.4%    |
| VFV                  | 1        | 0.2%    |
| TOL                  | 1        | 0.2%    |
| SOT                  | 1        | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 28E850 AOC0CCD 2560x1440 480x270mm 21.7-inch                     | 5        | 0.93%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch          | 4        | 0.75%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                  | 4        | 0.75%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 4        | 0.75%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 3        | 0.56%   |
| Mitsubishi MDT241WG MEL478E 1920x1200 520x320mm 24.0-inch            | 3        | 0.56%   |
| IOD EX-LD2071T IOD150D 1920x1080 458x258mm 20.7-inch                 | 3        | 0.56%   |
| Iiyama PL2390 IVM562D 1920x1080 509x286mm 23.0-inch                  | 3        | 0.56%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                     | 3        | 0.56%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch     | 3        | 0.56%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                    | 3        | 0.56%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                      | 3        | 0.56%   |
| Unknown                                                              | 3        | 0.56%   |
| ___ LCD TV ___9000 1360x768                                          | 2        | 0.37%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch           | 2        | 0.37%   |
| Unknown LCD Monitor Mitsubishi RDT233WLM 1920x1080                   | 2        | 0.37%   |
| SKY TV-monitor SKY1901 3840x2160 1210x680mm 54.6-inch                | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch | 2        | 0.37%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 2        | 0.37%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 2        | 0.37%   |
| Onkyo LA21TW ONK5060 1920x1080 478x269mm 21.6-inch                   | 2        | 0.37%   |
| Mitsubishi RDT234WLM MEL4887 1920x1080 509x286mm 23.0-inch           | 2        | 0.37%   |
| Mitsubishi RDT194S MEL4685 1280x1024 376x301mm 19.0-inch             | 2        | 0.37%   |
| Mitsubishi RDT1714VM MEL4764 1280x1024 338x270mm 17.0-inch           | 2        | 0.37%   |
| Mitsubishi MEL-TV(WXGA) MEL332E 1920x540                             | 2        | 0.37%   |
| LYC L2106 LYC0001 1920x1080 480x260mm 21.5-inch                      | 2        | 0.37%   |
| IOD LCD-RDT242XP IOD1891 1920x1080 527x296mm 23.8-inch               | 2        | 0.37%   |
| IOD KH2750V-UHD IOD1B2A 3840x2160 598x336mm 27.0-inch                | 2        | 0.37%   |
| Iiyama PL3291 IVM7605 1920x1080 698x393mm 31.5-inch                  | 2        | 0.37%   |
| Iiyama PL2875UH IVM710F 3840x2160 621x341mm 27.9-inch                | 2        | 0.37%   |
| Iiyama PL2390 IVM562E 1920x1080 509x286mm 23.0-inch                  | 2        | 0.37%   |
| HKM JAPANNEXT MNT HKM3200 3840x2160 698x393mm 31.5-inch              | 2        | 0.37%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 2        | 0.37%   |
| Hewlett-Packard LCD Monitor ZR2440w                                  | 2        | 0.37%   |
| Goldstar W2753 GSM56F7 1920x1080 598x336mm 27.0-inch                 | 2        | 0.37%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch                 | 2        | 0.37%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch             | 2        | 0.37%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 2        | 0.37%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 2        | 0.37%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 221      | 44.74%  |
| 3840x2160 (4K)     | 51       | 10.32%  |
| 1280x1024 (SXGA)   | 50       | 10.12%  |
| 2560x1440 (QHD)    | 29       | 5.87%   |
| 1920x1200 (WUXGA)  | 28       | 5.67%   |
| 1680x1050 (WSXGA+) | 17       | 3.44%   |
| Unknown            | 16       | 3.24%   |
| 1440x900 (WXGA+)   | 12       | 2.43%   |
| 1600x1200          | 8        | 1.62%   |
| 1920x540           | 7        | 1.42%   |
| 1360x768           | 6        | 1.21%   |
| 1024x768 (XGA)     | 6        | 1.21%   |
| 2560x1080          | 5        | 1.01%   |
| 3840x1080          | 4        | 0.81%   |
| 1400x1050          | 4        | 0.81%   |
| 1600x900 (HD+)     | 3        | 0.61%   |
| 1366x768 (WXGA)    | 3        | 0.61%   |
| 1280x720 (HD)      | 3        | 0.61%   |
| 3520x1080          | 2        | 0.4%    |
| 3440x1440          | 2        | 0.4%    |
| 3200x1200          | 2        | 0.4%    |
| 1360x765           | 2        | 0.4%    |
| 800x480            | 1        | 0.2%    |
| 7680x2160          | 1        | 0.2%    |
| 7360x1200          | 1        | 0.2%    |
| 640x480            | 1        | 0.2%    |
| 5760x1200          | 1        | 0.2%    |
| 4480x1080          | 1        | 0.2%    |
| 3200x2160          | 1        | 0.2%    |
| 3200x1080          | 1        | 0.2%    |
| 2560x1600          | 1        | 0.2%    |
| 2560x1024          | 1        | 0.2%    |
| 2048x1152          | 1        | 0.2%    |
| 1792x1344          | 1        | 0.2%    |
| 1280x960           | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 69       | 14.14%  |
| 27      | 65       | 13.32%  |
| 24      | 64       | 13.11%  |
| 23      | 61       | 12.5%   |
| 21      | 61       | 12.5%   |
| 19      | 34       | 6.97%   |
| 17      | 26       | 5.33%   |
| 31      | 18       | 3.69%   |
| 20      | 18       | 3.69%   |
| 22      | 9        | 1.84%   |
| 15      | 8        | 1.64%   |
| 34      | 6        | 1.23%   |
| 18      | 6        | 1.23%   |
| 72      | 5        | 1.02%   |
| 54      | 5        | 1.02%   |
| 42      | 4        | 0.82%   |
| 37      | 4        | 0.82%   |
| 84      | 3        | 0.61%   |
| 40      | 3        | 0.61%   |
| 14      | 3        | 0.61%   |
| 43      | 2        | 0.41%   |
| 32      | 2        | 0.41%   |
| 30      | 2        | 0.41%   |
| 26      | 2        | 0.41%   |
| 25      | 2        | 0.41%   |
| 74      | 1        | 0.2%    |
| 64      | 1        | 0.2%    |
| 49      | 1        | 0.2%    |
| 48      | 1        | 0.2%    |
| 39      | 1        | 0.2%    |
| 35      | 1        | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 182      | 37.92%  |
| 401-500     | 102      | 21.25%  |
| Unknown     | 69       | 14.38%  |
| 301-350     | 31       | 6.46%   |
| 351-400     | 27       | 5.63%   |
| 601-700     | 26       | 5.42%   |
| 801-900     | 9        | 1.88%   |
| 1501-2000   | 9        | 1.88%   |
| 701-800     | 8        | 1.67%   |
| 1001-1500   | 8        | 1.67%   |
| 901-1000    | 6        | 1.25%   |
| 201-300     | 3        | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 277      | 59.44%  |
| Unknown | 58       | 12.45%  |
| 16/10   | 56       | 12.02%  |
| 5/4     | 44       | 9.44%   |
| 4/3     | 15       | 3.22%   |
| 21/9    | 7        | 1.5%    |
| 32/9    | 4        | 0.86%   |
| 1.00    | 2        | 0.43%   |
| 6/5     | 1        | 0.21%   |
| 3/2     | 1        | 0.21%   |
| 1.96    | 1        | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 135      | 27.72%  |
| 151-200        | 83       | 17.04%  |
| Unknown        | 69       | 14.17%  |
| 301-350        | 65       | 13.35%  |
| 251-300        | 35       | 7.19%   |
| 351-500        | 29       | 5.95%   |
| 141-150        | 28       | 5.75%   |
| More than 1000 | 16       | 3.29%   |
| 501-1000       | 14       | 2.87%   |
| 101-110        | 9        | 1.85%   |
| 91-100         | 2        | 0.41%   |
| 131-140        | 1        | 0.21%   |
| 121-130        | 1        | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 264      | 55.7%   |
| 101-120 | 92       | 19.41%  |
| Unknown | 69       | 14.56%  |
| 121-160 | 26       | 5.49%   |
| 161-240 | 12       | 2.53%   |
| 1-50    | 11       | 2.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 387      | 81.82%  |
| 2     | 59       | 12.47%  |
| 0     | 19       | 4.02%   |
| 3     | 5        | 1.06%   |
| 4     | 2        | 0.42%   |
| 6     | 1        | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 271      | 42.68%  |
| Intel                            | 201      | 31.65%  |
| Qualcomm Atheros                 | 36       | 5.67%   |
| Broadcom                         | 26       | 4.09%   |
| BUFFALO                          | 15       | 2.36%   |
| TP-Link                          | 13       | 2.05%   |
| PLANEX                           | 12       | 1.89%   |
| Marvell Technology Group         | 9        | 1.42%   |
| Nvidia                           | 6        | 0.94%   |
| MediaTek                         | 5        | 0.79%   |
| VIA Technologies                 | 4        | 0.63%   |
| Elecom                           | 4        | 0.63%   |
| ASIX Electronics                 | 4        | 0.63%   |
| Broadcom Limited                 | 3        | 0.47%   |
| Aquantia                         | 3        | 0.47%   |
| Logitec                          | 2        | 0.31%   |
| Huawei Technologies              | 2        | 0.31%   |
| Wilocity                         | 1        | 0.16%   |
| vivo                             | 1        | 0.16%   |
| ULi Electronics                  | 1        | 0.16%   |
| U-Blox                           | 1        | 0.16%   |
| Silicon Integrated Systems [SiS] | 1        | 0.16%   |
| Samsung Electronics              | 1        | 0.16%   |
| Ralink Technology                | 1        | 0.16%   |
| Qualcomm Atheros Communications  | 1        | 0.16%   |
| Padix (Rockfire)                 | 1        | 0.16%   |
| NetGear                          | 1        | 0.16%   |
| Netchip Technology               | 1        | 0.16%   |
| NEC Computers                    | 1        | 0.16%   |
| LSI                              | 1        | 0.16%   |
| JMicron Technology               | 1        | 0.16%   |
| Edimax Technology                | 1        | 0.16%   |
| Corega K.K.                      | 1        | 0.16%   |
| ASUSTek Computer                 | 1        | 0.16%   |
| ADMtek                           | 1        | 0.16%   |
| 3Com                             | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 217      | 30.69%  |
| Intel Ethernet Connection (2) I219-V                              | 29       | 4.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 3.96%   |
| Intel I211 Gigabit Network Connection                             | 22       | 3.11%   |
| Intel Wi-Fi 6 AX200                                               | 21       | 2.97%   |
| Intel Ethernet Connection (7) I219-V                              | 18       | 2.55%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 1.98%   |
| Intel Ethernet Connection I217-V                                  | 11       | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 11       | 1.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 10       | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 8        | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.13%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 7        | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.85%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 0.85%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 0.85%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.71%   |
| BUFFALO 802.11ac WLAN Adapter                                     | 5        | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 0.57%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.57%   |
| Intel Ethernet Connection (11) I219-V                             | 4        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 0.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 0.42%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 0.42%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.42%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.42%   |
| Realtek 802.11ac NIC                                              | 3        | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3        | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 57       | 33.53%  |
| Realtek Semiconductor           | 32       | 18.82%  |
| Qualcomm Atheros                | 17       | 10%     |
| BUFFALO                         | 15       | 8.82%   |
| TP-Link                         | 13       | 7.65%   |
| PLANEX                          | 12       | 7.06%   |
| Broadcom                        | 7        | 4.12%   |
| MediaTek                        | 5        | 2.94%   |
| Elecom                          | 3        | 1.76%   |
| Logitec                         | 2        | 1.18%   |
| Wilocity                        | 1        | 0.59%   |
| Ralink Technology               | 1        | 0.59%   |
| Qualcomm Atheros Communications | 1        | 0.59%   |
| NetGear                         | 1        | 0.59%   |
| NEC Computers                   | 1        | 0.59%   |
| Edimax Technology               | 1        | 0.59%   |
| ASUSTek Computer                | 1        | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                | 21       | 12.21%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 11       | 6.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 10       | 5.81%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 7        | 4.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 6        | 3.49%   |
| BUFFALO 802.11ac WLAN Adapter                                      | 5        | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 4        | 2.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 4        | 2.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 4        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 4        | 2.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 3        | 1.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 3        | 1.74%   |
| Realtek 802.11ac NIC                                               | 3        | 1.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 3        | 1.74%   |
| PLANEX GW-USValue-EZ 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3        | 1.74%   |
| PLANEX GW-USNano2 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 3        | 1.74%   |
| Intel Wireless 7260                                                | 3        | 1.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 3        | 1.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2        | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 2        | 1.16%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 2        | 1.16%   |
| PLANEX GW-900D                                                     | 2        | 1.16%   |
| Intel Wireless-AC 9260                                             | 2        | 1.16%   |
| Intel Wireless 8265 / 8275                                         | 2        | 1.16%   |
| Intel Wireless 8260                                                | 2        | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 2        | 1.16%   |
| Intel Centrino Wireless-N 2230                                     | 2        | 1.16%   |
| Elecom WDC-150SU2M                                                 | 2        | 1.16%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]            | 2        | 1.16%   |
| BUFFALO 802.11 n WLAN                                              | 2        | 1.16%   |
| Broadcom BCM43228 802.11a/b/g/n                                    | 2        | 1.16%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                 | 1        | 0.58%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 1        | 0.58%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 1        | 0.58%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                              | 1        | 0.58%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                         | 1        | 0.58%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1        | 0.58%   |
| TP-Link 802.11ac NIC                                               | 1        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 257      | 50.59%  |
| Intel                            | 170      | 33.46%  |
| Qualcomm Atheros                 | 22       | 4.33%   |
| Broadcom                         | 20       | 3.94%   |
| Marvell Technology Group         | 9        | 1.77%   |
| Nvidia                           | 6        | 1.18%   |
| VIA Technologies                 | 4        | 0.79%   |
| ASIX Electronics                 | 4        | 0.79%   |
| Broadcom Limited                 | 3        | 0.59%   |
| Aquantia                         | 3        | 0.59%   |
| Huawei Technologies              | 2        | 0.39%   |
| Silicon Integrated Systems [SiS] | 1        | 0.2%    |
| Samsung Electronics              | 1        | 0.2%    |
| Netchip Technology               | 1        | 0.2%    |
| JMicron Technology               | 1        | 0.2%    |
| Elecom                           | 1        | 0.2%    |
| Corega K.K.                      | 1        | 0.2%    |
| ADMtek                           | 1        | 0.2%    |
| 3Com                             | 1        | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 217      | 41.18%  |
| Intel Ethernet Connection (2) I219-V                              | 29       | 5.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 28       | 5.31%   |
| Intel I211 Gigabit Network Connection                             | 22       | 4.17%   |
| Intel Ethernet Connection (7) I219-V                              | 18       | 3.42%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 2.66%   |
| Intel Ethernet Connection I217-V                                  | 11       | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 1.71%   |
| Intel Ethernet Controller I225-V                                  | 8        | 1.52%   |
| Intel Ethernet Connection I217-LM                                 | 8        | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 1.33%   |
| Intel Ethernet Connection (2) I218-V                              | 6        | 1.14%   |
| Intel 82574L Gigabit Network Connection                           | 6        | 1.14%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 5        | 0.95%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4        | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.76%   |
| Intel Ethernet Connection (12) I219-V                             | 4        | 0.76%   |
| Intel Ethernet Connection (11) I219-V                             | 4        | 0.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.57%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 3        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.57%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.57%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.57%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 3        | 0.57%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 3        | 0.57%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 2        | 0.38%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2        | 0.38%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 461      | 73.52%  |
| WiFi     | 158      | 25.2%   |
| Modem    | 6        | 0.96%   |
| Unknown  | 2        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 401      | 82.51%  |
| WiFi     | 85       | 17.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 330      | 71.27%  |
| 2     | 109      | 23.54%  |
| 3     | 20       | 4.32%   |
| 4     | 3        | 0.65%   |
| 0     | 1        | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 354      | 75%     |
| Yes  | 118      | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 61       | 40.13%  |
| Intel                           | 52       | 34.21%  |
| Realtek Semiconductor           | 9        | 5.92%   |
| TP-Link                         | 5        | 3.29%   |
| Qualcomm Atheros Communications | 5        | 3.29%   |
| MediaTek                        | 4        | 2.63%   |
| ASUSTek Computer                | 4        | 2.63%   |
| IMC Networks                    | 2        | 1.32%   |
| Broadcom                        | 2        | 1.32%   |
| Apple                           | 2        | 1.32%   |
| Realtek                         | 1        | 0.66%   |
| Lite-On Technology              | 1        | 0.66%   |
| Foxconn / Hon Hai               | 1        | 0.66%   |
| Creative Technology             | 1        | 0.66%   |
| BUFFALO                         | 1        | 0.66%   |
| Actions                         | 1        | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 61       | 40.13%  |
| Intel AX200 Bluetooth                               | 20       | 13.16%  |
| Intel Wireless-AC 3168 Bluetooth                    | 11       | 7.24%   |
| Realtek Bluetooth Radio                             | 8        | 5.26%   |
| Intel Bluetooth wireless interface                  | 7        | 4.61%   |
| TP-Link UB500 Adapter                               | 5        | 3.29%   |
| MediaTek Wireless_Device                            | 4        | 2.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4        | 2.63%   |
| Intel AX210 Bluetooth                               | 4        | 2.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2        | 1.32%   |
| Intel AX201 Bluetooth                               | 2        | 1.32%   |
| IMC Networks Bluetooth Device                       | 2        | 1.32%   |
| ASUS BCM20702A0                                     | 2        | 1.32%   |
| Apple Bluetooth Host Controller                     | 2        | 1.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1        | 0.66%   |
| Realtek Bluetooth Radio                             | 1        | 0.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 0.66%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.66%   |
| Lite-On Bluetooth Device                            | 1        | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 0.66%   |
| Creative Bluetooth Audio W2                         | 1        | 0.66%   |
| BUFFALO Bluetooth Radio                             | 1        | 0.66%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 0.66%   |
| ASUS Bluetooth Radio                                | 1        | 0.66%   |
| ASUS Bluetooth Device                               | 1        | 0.66%   |
| Actions general adapter                             | 1        | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 298      | 38.3%   |
| AMD                                             | 200      | 25.71%  |
| Nvidia                                          | 165      | 21.21%  |
| C-Media Electronics                             | 19       | 2.44%   |
| Creative Technology                             | 13       | 1.67%   |
| Texas Instruments                               | 12       | 1.54%   |
| VIA Technologies                                | 11       | 1.41%   |
| Harman                                          | 9        | 1.16%   |
| Creative Labs                                   | 6        | 0.77%   |
| Yamaha                                          | 4        | 0.51%   |
| JMTek                                           | 4        | 0.51%   |
| TOWA Electronics                                | 3        | 0.39%   |
| Sony                                            | 3        | 0.39%   |
| Generalplus Technology                          | 3        | 0.39%   |
| XMOS                                            | 2        | 0.26%   |
| Roland                                          | 2        | 0.26%   |
| Onkyo                                           | 2        | 0.26%   |
| GN Netcom                                       | 2        | 0.26%   |
| Elitegroup Computer Systems (ECS)               | 2        | 0.26%   |
| ASUSTek Computer                                | 2        | 0.26%   |
| ULi Electronics                                 | 1        | 0.13%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.13%   |
| SteelSeries ApS                                 | 1        | 0.13%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.13%   |
| RME                                             | 1        | 0.13%   |
| Realtek Semiconductor                           | 1        | 0.13%   |
| Razer USA                                       | 1        | 0.13%   |
| RATOC System                                    | 1        | 0.13%   |
| Rasteme                                         | 1        | 0.13%   |
| Philips (or NXP)                                | 1        | 0.13%   |
| Medeli Electronics                              | 1        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.13%   |
| Focusrite-Novation                              | 1        | 0.13%   |
| DSEA A/S                                        | 1        | 0.13%   |
| BEHRINGER International                         | 1        | 0.13%   |
| Astro Gaming                                    | 1        | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                          | 42       | 4.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 33       | 3.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 31       | 3.43%   |
| AMD Family 17h/19h HD Audio Controller                                            | 28       | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 27       | 2.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 26       | 2.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 26       | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                        | 24       | 2.66%   |
| Intel 200 Series PCH HD Audio                                                     | 24       | 2.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 23       | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 22       | 2.44%   |
| AMD FCH Azalia Controller                                                         | 20       | 2.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 20       | 2.21%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 18       | 1.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 17       | 1.88%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 17       | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17       | 1.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 17       | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 15       | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 14       | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 13       | 1.44%   |
| Nvidia TU116 High Definition Audio Controller                                     | 12       | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 12       | 1.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 12       | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12       | 1.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 10       | 1.11%   |
| Nvidia GK107 HDMI Audio Controller                                                | 10       | 1.11%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 10       | 1.11%   |
| AMD Navi 10 HDMI Audio                                                            | 9        | 1%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 9        | 1%      |
| Nvidia GP104 High Definition Audio Controller                                     | 8        | 0.89%   |
| Harman JBL Pebbles                                                                | 8        | 0.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 8        | 0.89%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller       | 7        | 0.78%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                 | 7        | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                                     | 7        | 0.78%   |
| Nvidia GK106 HDMI Audio Controller                                                | 7        | 0.78%   |
| Nvidia GA102 High Definition Audio Controller                                     | 7        | 0.78%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 7        | 0.78%   |
| Intel Alder Lake-S HD Audio Controller                                            | 7        | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 28       | 14.07%  |
| Crucial             | 27       | 13.57%  |
| Kingston            | 26       | 13.07%  |
| Team                | 13       | 6.53%   |
| Corsair             | 13       | 6.53%   |
| A-DATA Technology   | 13       | 6.53%   |
| Samsung Electronics | 11       | 5.53%   |
| G.Skill             | 10       | 5.03%   |
| Micron Technology   | 9        | 4.52%   |
| SK hynix            | 8        | 4.02%   |
| Panram              | 7        | 3.52%   |
| Silicon Power       | 5        | 2.51%   |
| Nanya Technology    | 5        | 2.51%   |
| KLEVV               | 5        | 2.51%   |
| Transcend           | 3        | 1.51%   |
| Unknown             | 3        | 1.51%   |
| SanMax              | 2        | 1.01%   |
| V-Color             | 1        | 0.5%    |
| Unknown (8AD3)      | 1        | 0.5%    |
| Unknown (0x09EE)    | 1        | 0.5%    |
| UMAX                | 1        | 0.5%    |
| Ramos Technology    | 1        | 0.5%    |
| Patriot             | 1        | 0.5%    |
| Kingmax             | 1        | 0.5%    |
| GeIL                | 1        | 0.5%    |
| Essencore Limited   | 1        | 0.5%    |
| Elpida              | 1        | 0.5%    |
| Century Micro       | 1        | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s     | 4        | 1.93%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 3        | 1.45%   |
| Nanya RAM M2X4G64CB8HG9N-DG 4GB DIMM DDR3 1600MT/s        | 3        | 1.45%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s        | 3        | 1.45%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 3        | 1.45%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2667MT/s        | 3        | 1.45%   |
| Crucial RAM CT16G4DFRA32A.C8FE 16384MB DIMM DDR4 3200MT/s | 3        | 1.45%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s    | 3        | 1.45%   |
| Unknown                                                   | 3        | 1.45%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2        | 0.97%   |
| Unknown RAM Module 1GB DIMM 800MT/s                       | 2        | 0.97%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3600MT/s       | 2        | 0.97%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 2        | 0.97%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2933MT/s     | 2        | 0.97%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s        | 2        | 0.97%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s      | 2        | 0.97%   |
| Silicon Power RAM DCLT8GN128S 8192MB DIMM DDR3 1600MT/s   | 2        | 0.97%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 0.97%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s    | 2        | 0.97%   |
| Kingston RAM CBD26D4U9S8ME-8 8GB DIMM DDR4 2667MT/s       | 2        | 0.97%   |
| Kingston RAM 9905622-057.A00G 4GB DIMM DDR4 2133MT/s      | 2        | 0.97%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s        | 2        | 0.97%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s     | 2        | 0.97%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s  | 2        | 0.97%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s     | 2        | 0.97%   |
| A-DATA RAM Module 8GB DIMM DDR4 3200MT/s                  | 2        | 0.97%   |
| A-DATA RAM Module 32GB DIMM DDR4 3200MT/s                 | 2        | 0.97%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s        | 1        | 0.48%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                 | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM SDRAM                         | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                 | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                 | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                 | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 1        | 0.48%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM 667MT/s                 | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 1        | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                  | 1        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 111      | 59.68%  |
| DDR3    | 51       | 27.42%  |
| SDRAM   | 9        | 4.84%   |
| Unknown | 9        | 4.84%   |
| DDR2    | 5        | 2.69%   |
| DDR     | 1        | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 173      | 94.02%  |
| SODIMM | 10       | 5.43%   |
| RIMM   | 1        | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 69       | 36.32%  |
| 16384 | 40       | 21.05%  |
| 4096  | 38       | 20%     |
| 2048  | 19       | 10%     |
| 32768 | 16       | 8.42%   |
| 1024  | 8        | 4.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 16.58%  |
| 3200    | 29       | 15.03%  |
| 2667    | 28       | 14.51%  |
| 2400    | 16       | 8.29%   |
| 2133    | 11       | 5.7%    |
| 3600    | 10       | 5.18%   |
| 2666    | 9        | 4.66%   |
| 1333    | 9        | 4.66%   |
| 800     | 8        | 4.15%   |
| Unknown | 6        | 3.11%   |
| 2933    | 5        | 2.59%   |
| 3800    | 4        | 2.07%   |
| 3400    | 4        | 2.07%   |
| 667     | 4        | 2.07%   |
| 1866    | 3        | 1.55%   |
| 1800    | 3        | 1.55%   |
| 1066    | 2        | 1.04%   |
| 533     | 2        | 1.04%   |
| 4133    | 1        | 0.52%   |
| 3534    | 1        | 0.52%   |
| 3100    | 1        | 0.52%   |
| 3007    | 1        | 0.52%   |
| 3000    | 1        | 0.52%   |
| 2733    | 1        | 0.52%   |
| 2000    | 1        | 0.52%   |
| 1867    | 1        | 0.52%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 4        | 36.36%  |
| Brother Industries | 4        | 36.36%  |
| Seiko Epson        | 2        | 18.18%  |
| Hewlett-Packard    | 1        | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Brother HL-1440 Laser Printer | 2        | 18.18%  |
| Seiko Epson XP-100 Series     | 1        | 9.09%   |
| Seiko Epson EP-306 Series     | 1        | 9.09%   |
| HP ENVY 5000 series           | 1        | 9.09%   |
| Canon TS5300 series           | 1        | 9.09%   |
| Canon PIXMA iX6850 Printer    | 1        | 9.09%   |
| Canon PIXMA iP4600 Printer    | 1        | 9.09%   |
| Canon iP2700 series           | 1        | 9.09%   |
| Brother HL-L2360D series      | 1        | 9.09%   |
| Brother HL-52x0 series        | 1        | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 50%     |
| Canon       | 1        | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 50%     |
| Canon CanoScan LiDE 100                                       | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 26%     |
| Sunplus Innovation Technology | 4        | 8%      |
| Elecom                        | 4        | 8%      |
| Microsoft                     | 3        | 6%      |
| MacroSilicon                  | 3        | 6%      |
| Microdia                      | 2        | 4%      |
| Generalplus Technology        | 2        | 4%      |
| Cubeternet                    | 2        | 4%      |
| Z-Star Microelectronics       | 1        | 2%      |
| WaveRider Communications      | 1        | 2%      |
| Syntek                        | 1        | 2%      |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 2%      |
| Samsung Electronics           | 1        | 2%      |
| Ruision                       | 1        | 2%      |
| OmniVision Technologies       | 1        | 2%      |
| Jieli Technology              | 1        | 2%      |
| Huawei Technologies           | 1        | 2%      |
| HD USB Camera                 | 1        | 2%      |
| GEMBIRD                       | 1        | 2%      |
| Etron Technology              | 1        | 2%      |
| eMeet                         | 1        | 2%      |
| Chicony Electronics           | 1        | 2%      |
| BUFFALO                       | 1        | 2%      |
| Apple                         | 1        | 2%      |
| Alcor Micro                   | 1        | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 5        | 9.8%    |
| MacroSilicon USB Video                         | 3        | 5.88%   |
| Microdia Webcam Vitade AF                      | 2        | 3.92%   |
| Logitech HD Pro Webcam C920                    | 2        | 3.92%   |
| Generalplus 808 Camera #9 (web-cam mode)       | 2        | 3.92%   |
| Elecom UCAM-DLE300T                            | 2        | 3.92%   |
| Z-Star Venus USB2.0 Camera                     | 1        | 1.96%   |
| WaveRider USB 2.0 Camera                       | 1        | 1.96%   |
| Syntek BUFFALO BSW20K06H USB PC Camera         | 1        | 1.96%   |
| Sunplus WEMISS CM-A1                           | 1        | 1.96%   |
| Sunplus SPCA2281 Web Camera                    | 1        | 1.96%   |
| Sunplus SPCA2085 PC Camera                     | 1        | 1.96%   |
| Sunplus FHD Camera                             | 1        | 1.96%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 1.96%   |
| Samsung Galaxy A5 (MTP)                        | 1        | 1.96%   |
| Ruision UVC Camera                             | 1        | 1.96%   |
| OmniVision OV511+ Webcam                       | 1        | 1.96%   |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 1.96%   |
| Microsoft LifeCam HD-3000                      | 1        | 1.96%   |
| Microsoft LifeCam Cinema                       | 1        | 1.96%   |
| Logitech Webcam C310                           | 1        | 1.96%   |
| Logitech QuickCam Orbit/Sphere AF              | 1        | 1.96%   |
| Logitech HD Webcam C910                        | 1        | 1.96%   |
| Logitech HD Webcam C615                        | 1        | 1.96%   |
| Logitech C922 Pro Stream Webcam                | 1        | 1.96%   |
| Logitech BRIO Ultra HD Webcam                  | 1        | 1.96%   |
| Jieli USB PHY 2.0                              | 1        | 1.96%   |
| Huawei UVC Camera                              | 1        | 1.96%   |
| HD USB Camera HD USB Camera                    | 1        | 1.96%   |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 1.96%   |
| Etron BUFFALO BSW32KM03 USB PC Camera          | 1        | 1.96%   |
| eMeet HD Webcam C960                           | 1        | 1.96%   |
| Elecom UCAM-DLB200TA                           | 1        | 1.96%   |
| Elecom ELECOM 5MP Webcam                       | 1        | 1.96%   |
| Cubeternet WebCam                              | 1        | 1.96%   |
| Cubeternet USB2.0 Camera                       | 1        | 1.96%   |
| Chicony FJ Camera                              | 1        | 1.96%   |
| BUFFALO USB 2.0 Camera                         | 1        | 1.96%   |
| BUFFALO BUFFALO BSWHD06M USB Camera            | 1        | 1.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                | 1        | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 2        | 40%     |
| Elan Microelectronics | 2        | 40%     |
| Synaptics             | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader        | 2        | 40%     |
| Elan fingerprint sensor [FeinTech FPS00200]  | 2        | 40%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 2        | 40%     |
| Alcor Micro      | 2        | 40%     |
| Yubico.com       | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 40%     |
| Alcor Micro AU9540 Smartcard Reader                    | 2        | 40%     |
| Yubico.com Yubikey 4/5 U2F+CCID                        | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 388      | 82.38%  |
| 1     | 73       | 15.5%   |
| 2     | 8        | 1.7%    |
| 8     | 1        | 0.21%   |
| 7     | 1        | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 25       | 26.88%  |
| Graphics card            | 20       | 21.51%  |
| Multimedia controller    | 11       | 11.83%  |
| Unassigned class         | 8        | 8.6%    |
| Communication controller | 7        | 7.53%   |
| Fingerprint reader       | 5        | 5.38%   |
| Sound                    | 4        | 4.3%    |
| Modem                    | 3        | 3.23%   |
| Chipcard                 | 2        | 2.15%   |
| Bluetooth                | 2        | 2.15%   |
| Storage/raid             | 1        | 1.08%   |
| Storage/nvme             | 1        | 1.08%   |
| Storage/ata              | 1        | 1.08%   |
| Network                  | 1        | 1.08%   |
| Net/ethernet             | 1        | 1.08%   |
| Camera                   | 1        | 1.08%   |

