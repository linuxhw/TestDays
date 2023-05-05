Linux in Hong Kong - Tested Hardware & Statistics (Desktops)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hong Kong.

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

Total: 213

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell       | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| ASUSTek    | PRIME H670-PLUS D4          | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Gigabyte   | X570S AERO G                | [30e0bd8317](https://linux-hardware.org/?probe=30e0bd8317) | Apr 02, 2023 |
| MSI        | B450 TOMAHAWK               | [4757b31751](https://linux-hardware.org/?probe=4757b31751) | Mar 19, 2023 |
| ASUSTek    | P8H61-M LX PLUS             | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| MSI        | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| ASUSTek    | PRIME H610M-K D4            | [601836815c](https://linux-hardware.org/?probe=601836815c) | Feb 22, 2023 |
| Gigabyte   | GA-880GMA-UD2H              | [c1936488f5](https://linux-hardware.org/?probe=c1936488f5) | Feb 20, 2023 |
| Gigabyte   | X670 AORUS ELITE AX         | [ee4e2b3cde](https://linux-hardware.org/?probe=ee4e2b3cde) | Feb 19, 2023 |
| MSI        | MPG X570 GAMING PRO CARB... | [81c1e35182](https://linux-hardware.org/?probe=81c1e35182) | Jan 24, 2023 |
| Gigabyte   | H97N-WIFI                   | [a18f404d39](https://linux-hardware.org/?probe=a18f404d39) | Jan 17, 2023 |
| ASUSTek    | M4A78                       | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| ASUSTek    | M4A78                       | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell       | 042P49 A02                  | [dc81fac0f7](https://linux-hardware.org/?probe=dc81fac0f7) | Jan 04, 2023 |
| MSI        | MPG X570 GAMING PRO CARB... | [ecf944f539](https://linux-hardware.org/?probe=ecf944f539) | Dec 31, 2022 |
| ASUSTek    | PRIME H610M-K D4            | [0031785936](https://linux-hardware.org/?probe=0031785936) | Dec 31, 2022 |
| ASUSTek    | PRIME H610M-K D4            | [4bd2096c80](https://linux-hardware.org/?probe=4bd2096c80) | Dec 31, 2022 |
| MSI        | MPG X570 GAMING PRO CARB... | [7b3c89637b](https://linux-hardware.org/?probe=7b3c89637b) | Dec 30, 2022 |
| Lenovo     | 3753 SDK0T76479 WIN 3423... | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Lenovo     | 3753 SDK0T76479 WIN 3423... | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [895a345eb9](https://linux-hardware.org/?probe=895a345eb9) | Nov 02, 2022 |
| Gigabyte   | B450 I AORUS PRO WIFI-CF    | [9d9d3a4967](https://linux-hardware.org/?probe=9d9d3a4967) | Nov 02, 2022 |
| MSI        | MAG B660M MORTAR WIFI DD... | [115e9027d0](https://linux-hardware.org/?probe=115e9027d0) | Nov 01, 2022 |
| ASRock     | H470M-STX                   | [02f3177542](https://linux-hardware.org/?probe=02f3177542) | Oct 26, 2022 |
| MSI        | MAG B550M MORTAR WIFI       | [ce7a9a3171](https://linux-hardware.org/?probe=ce7a9a3171) | Oct 23, 2022 |
| Lenovo     | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek    | TUF Gaming Z690-PLUS D4     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| ASRock     | AB350M Pro4                 | [6207d55486](https://linux-hardware.org/?probe=6207d55486) | Oct 05, 2022 |
| MSI        | B75MA-E33                   | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| HP         | 18E7                        | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| ASUSTek    | PRIME B660M-K D4            | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| Unknown    | Apple iPad Pro (9.7-inch... | [822d20fcdb](https://linux-hardware.org/?probe=822d20fcdb) | Sep 25, 2022 |
| Unknown    | Apple iPad Pro (9.7-inch... | [92f244ac1c](https://linux-hardware.org/?probe=92f244ac1c) | Sep 25, 2022 |
| MSI        | H81M-P33                    | [7e4f539e70](https://linux-hardware.org/?probe=7e4f539e70) | Sep 24, 2022 |
| MSI        | H81M-P33                    | [64cd74457e](https://linux-hardware.org/?probe=64cd74457e) | Sep 24, 2022 |
| ASRock     | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| ASRock     | Z490 PG Velocita            | [eac045585b](https://linux-hardware.org/?probe=eac045585b) | Sep 23, 2022 |
| Huanan     | X99-TF                      | [657d78e891](https://linux-hardware.org/?probe=657d78e891) | Sep 21, 2022 |
| ASUSTek    | PRIME H310M-E R2.0          | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Dell       | 0427JK A00                  | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| Dell       | 0200DY A03                  | [e0e14cd1f2](https://linux-hardware.org/?probe=e0e14cd1f2) | Aug 19, 2022 |
| ASUSTek    | ROG STRIX B660-I GAMING ... | [58b22885a8](https://linux-hardware.org/?probe=58b22885a8) | Aug 18, 2022 |
| ASUSTek    | PRIME Z590M-PLUS            | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| MSI        | MAG B660M MORTAR WIFI DD... | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| ASRock     | B450M-HDV R4.0              | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| Huanan     | X99-TF                      | [55b43de5a6](https://linux-hardware.org/?probe=55b43de5a6) | Jul 17, 2022 |
| Soyo       | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| Gigabyte   | X570 AORUS PRO WIFI         | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Huanan     | X99-TF                      | [04dc5246af](https://linux-hardware.org/?probe=04dc5246af) | Jun 18, 2022 |
| Lenovo     | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Huanan     | X99-TF                      | [4e5364e832](https://linux-hardware.org/?probe=4e5364e832) | Jun 08, 2022 |
| Gigabyte   | HA65M-UD3H-B3               | [d368918a0b](https://linux-hardware.org/?probe=d368918a0b) | May 13, 2022 |
| Gigabyte   | X570 AORUS PRO WIFI         | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| Gigabyte   | GA-880GMA-UD2H              | [09d9f58ee7](https://linux-hardware.org/?probe=09d9f58ee7) | May 02, 2022 |
| MSI        | H87I                        | [af4a26a5ea](https://linux-hardware.org/?probe=af4a26a5ea) | Apr 30, 2022 |
| Gigabyte   | B660M DS3H AX DDR4          | [0633ac7757](https://linux-hardware.org/?probe=0633ac7757) | Apr 26, 2022 |
| Gigabyte   | B660M DS3H AX DDR4          | [56902c7998](https://linux-hardware.org/?probe=56902c7998) | Apr 26, 2022 |
| Gigabyte   | B660M DS3H AX DDR4          | [abed3ae34d](https://linux-hardware.org/?probe=abed3ae34d) | Apr 12, 2022 |
| ASUSTek    | VM62                        | [ae684cdf71](https://linux-hardware.org/?probe=ae684cdf71) | Apr 05, 2022 |
| ASRock     | H410M-ITX/ac                | [ae936790c9](https://linux-hardware.org/?probe=ae936790c9) | Apr 03, 2022 |
| MSI        | MAG B550M MORTAR            | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Dell       | 0Y3R3K A03                  | [b772cf9d86](https://linux-hardware.org/?probe=b772cf9d86) | Mar 26, 2022 |
| ASUSTek    | PRIME Z590-A                | [7320ed668a](https://linux-hardware.org/?probe=7320ed668a) | Mar 12, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [99d3e16ede](https://linux-hardware.org/?probe=99d3e16ede) | Mar 12, 2022 |
| Unknown    | Intel X79                   | [e947d6af7f](https://linux-hardware.org/?probe=e947d6af7f) | Mar 11, 2022 |
| MSI        | MPG X570 GAMING PRO CARB... | [4d16610cf3](https://linux-hardware.org/?probe=4d16610cf3) | Mar 10, 2022 |
| MSI        | B450M PRO-VDH PLUS          | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte   | X570 AORUS ELITE            | [0b9a7acb84](https://linux-hardware.org/?probe=0b9a7acb84) | Feb 27, 2022 |
| MSI        | B75MA-P45                   | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Dell       | 0Y5DDC A00                  | [3c7daed552](https://linux-hardware.org/?probe=3c7daed552) | Feb 22, 2022 |
| ASUSTek    | TUF Gaming B550M-PLUS       | [6e5689a733](https://linux-hardware.org/?probe=6e5689a733) | Jan 28, 2022 |
| ASRock     | Z270M-ITX/ac                | [4c32bf6d7b](https://linux-hardware.org/?probe=4c32bf6d7b) | Jan 18, 2022 |
| HP         | 8597                        | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [83ff6966e1](https://linux-hardware.org/?probe=83ff6966e1) | Dec 24, 2021 |
| ASUSTek    | Z170 PRO GAMING             | [c5fa4a0cec](https://linux-hardware.org/?probe=c5fa4a0cec) | Dec 24, 2021 |
| ASRock     | H410M-ITX/ac                | [99c341562a](https://linux-hardware.org/?probe=99c341562a) | Dec 21, 2021 |
| Gigabyte   | B450 AORUS PRO WIFI-CF      | [d01abdcb39](https://linux-hardware.org/?probe=d01abdcb39) | Dec 19, 2021 |
| MSI        | 870-G45                     | [e6317a2b91](https://linux-hardware.org/?probe=e6317a2b91) | Dec 19, 2021 |
| Unknown    | Intel X79                   | [985655e4b3](https://linux-hardware.org/?probe=985655e4b3) | Dec 11, 2021 |
| Unknown    | Intel X79                   | [6f32192557](https://linux-hardware.org/?probe=6f32192557) | Dec 08, 2021 |
| Supermicro | X9DRi-LN4+/X9DR3-LN4+       | [bd8742e075](https://linux-hardware.org/?probe=bd8742e075) | Dec 08, 2021 |
| MSI        | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| Supermicro | C2SBC-Q                     | [1099e48366](https://linux-hardware.org/?probe=1099e48366) | Nov 28, 2021 |
| MSI        | MAG B550M MORTAR WIFI       | [58d43162d2](https://linux-hardware.org/?probe=58d43162d2) | Nov 28, 2021 |
| Gigabyte   | H310M S2H x.x               | [fc59694424](https://linux-hardware.org/?probe=fc59694424) | Nov 17, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [35b58ec233](https://linux-hardware.org/?probe=35b58ec233) | Nov 16, 2021 |
| Seco       | C40 C                       | [27bff03d0c](https://linux-hardware.org/?probe=27bff03d0c) | Nov 08, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [9bcd3d5479](https://linux-hardware.org/?probe=9bcd3d5479) | Oct 29, 2021 |
| Gigabyte   | X570 AORUS PRO WIFI         | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| MSI        | B450 TOMAHAWK MAX II        | [aedfc53de6](https://linux-hardware.org/?probe=aedfc53de6) | Oct 20, 2021 |
| MSI        | H61M-P23                    | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| MSI        | MEG X570 GODLIKE            | [1440e244f6](https://linux-hardware.org/?probe=1440e244f6) | Aug 26, 2021 |
| Gigabyte   | B365M GAMING HD             | [d920558127](https://linux-hardware.org/?probe=d920558127) | Aug 14, 2021 |
| Gigabyte   | X570 AORUS ELITE            | [5cd377c0e0](https://linux-hardware.org/?probe=5cd377c0e0) | Aug 13, 2021 |
| Gigabyte   | B75M-D2P                    | [5e54c2a102](https://linux-hardware.org/?probe=5e54c2a102) | Aug 12, 2021 |
| HP         | 2B38                        | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP         | 2B38                        | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock     | H410M-HDV                   | [58b70e282d](https://linux-hardware.org/?probe=58b70e282d) | Jul 14, 2021 |
| Gigabyte   | B365M GAMING HD             | [66cf378cf1](https://linux-hardware.org/?probe=66cf378cf1) | Jul 10, 2021 |
| Gigabyte   | B85M-DS3H-A                 | [6496f18326](https://linux-hardware.org/?probe=6496f18326) | Jul 02, 2021 |
| Gigabyte   | B85M-DS3H-A                 | [71da4978c9](https://linux-hardware.org/?probe=71da4978c9) | Jun 29, 2021 |
| Gigabyte   | B365M GAMING HD             | [ed911e7e8c](https://linux-hardware.org/?probe=ed911e7e8c) | Jun 26, 2021 |
| Gigabyte   | B365M GAMING HD             | [8785d98b0b](https://linux-hardware.org/?probe=8785d98b0b) | Jun 19, 2021 |
| ASUSTek    | PRIME Z390-P                | [54e520ac17](https://linux-hardware.org/?probe=54e520ac17) | Jun 17, 2021 |
| ASUSTek    | TUF Gaming Z490-PLUS        | [76219e9cca](https://linux-hardware.org/?probe=76219e9cca) | Jun 09, 2021 |
| ASRock     | H410M-HDV                   | [bcb80080a5](https://linux-hardware.org/?probe=bcb80080a5) | Jun 06, 2021 |
| HP         | 18E7                        | [9844f6635c](https://linux-hardware.org/?probe=9844f6635c) | May 30, 2021 |
| ASUSTek    | VM62                        | [486aeb5b89](https://linux-hardware.org/?probe=486aeb5b89) | May 25, 2021 |
| Gigabyte   | F2A88XN-WIFI                | [c22e6d8669](https://linux-hardware.org/?probe=c22e6d8669) | May 25, 2021 |
| Dell       | 0D02VH A01                  | [e19475cd4c](https://linux-hardware.org/?probe=e19475cd4c) | May 22, 2021 |
| ASUSTek    | PRIME X399-A                | [a201bdfc36](https://linux-hardware.org/?probe=a201bdfc36) | May 19, 2021 |
| ASUSTek    | M4A78-VM                    | [3313d34c41](https://linux-hardware.org/?probe=3313d34c41) | May 15, 2021 |
| ASUSTek    | Z8NA-D6                     | [1b777c6f08](https://linux-hardware.org/?probe=1b777c6f08) | May 02, 2021 |
| ASUSTek    | Z8NA-D6                     | [4c7956a34c](https://linux-hardware.org/?probe=4c7956a34c) | May 02, 2021 |
| MSI        | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP         | 1632                        | [adf9ebb679](https://linux-hardware.org/?probe=adf9ebb679) | Mar 25, 2021 |
| MSI        | B450I GAMING PLUS AC        | [6a4196e0aa](https://linux-hardware.org/?probe=6a4196e0aa) | Mar 23, 2021 |
| MSI        | B450M-A PRO MAX             | [dc64c81c35](https://linux-hardware.org/?probe=dc64c81c35) | Mar 23, 2021 |
| ASUSTek    | B85M-G R2.0                 | [71ef988016](https://linux-hardware.org/?probe=71ef988016) | Mar 21, 2021 |
| ASRock     | H410M-HDV                   | [e44a5ce779](https://linux-hardware.org/?probe=e44a5ce779) | Mar 14, 2021 |
| MSI        | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| ASUSTek    | P8H61-M LX PLUS             | [b94539c6dc](https://linux-hardware.org/?probe=b94539c6dc) | Mar 01, 2021 |
| ASUSTek    | B85M-G R2.0                 | [b2cb174b9a](https://linux-hardware.org/?probe=b2cb174b9a) | Mar 01, 2021 |
| Lenovo     | MAHOBAY NOK                 | [e3c14a6397](https://linux-hardware.org/?probe=e3c14a6397) | Feb 25, 2021 |
| Dell       | 0D02VH A01                  | [87c36a9322](https://linux-hardware.org/?probe=87c36a9322) | Feb 23, 2021 |
| ASUSTek    | VM45                        | [03eeb85521](https://linux-hardware.org/?probe=03eeb85521) | Feb 21, 2021 |
| ASUSTek    | VM65-K                      | [6b97cf71eb](https://linux-hardware.org/?probe=6b97cf71eb) | Feb 18, 2021 |
| ASUSTek    | VM65-K                      | [4f0bcd1276](https://linux-hardware.org/?probe=4f0bcd1276) | Feb 17, 2021 |
| ASUSTek    | VM40B                       | [6c0bf22f39](https://linux-hardware.org/?probe=6c0bf22f39) | Feb 17, 2021 |
| Dell       | 0D02VH A01                  | [ebc5645105](https://linux-hardware.org/?probe=ebc5645105) | Feb 11, 2021 |
| Lenovo     | IdeaCentre K330             | [78ce34058b](https://linux-hardware.org/?probe=78ce34058b) | Feb 11, 2021 |
| ASUSTek    | ROG STRIX B450-I GAMING     | [39bc70ca5d](https://linux-hardware.org/?probe=39bc70ca5d) | Jan 13, 2021 |
| ASRock     | H410M-HDV                   | [d2420f233b](https://linux-hardware.org/?probe=d2420f233b) | Jan 10, 2021 |
| MSI        | H97 GAMING 3                | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| Dell       | 0TP412                      | [f0e56aacff](https://linux-hardware.org/?probe=f0e56aacff) | Jan 05, 2021 |
| ASRock     | Z390 Phantom Gaming-ITX/... | [cf7386e848](https://linux-hardware.org/?probe=cf7386e848) | Dec 18, 2020 |
| ASUSTek    | H97M-PLUS                   | [1d6b7df7b4](https://linux-hardware.org/?probe=1d6b7df7b4) | Dec 08, 2020 |
| Gigabyte   | X570 AORUS ELITE            | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| Dell       | 0D02VH A01                  | [8309aa39cf](https://linux-hardware.org/?probe=8309aa39cf) | Nov 30, 2020 |
| Gigabyte   | B450M DS3H-CF               | [37d5acae7d](https://linux-hardware.org/?probe=37d5acae7d) | Nov 27, 2020 |
| ASUSTek    | 970 PRO GAMING/AURA         | [97c485886b](https://linux-hardware.org/?probe=97c485886b) | Nov 25, 2020 |
| Dell       | 0D02VH A01                  | [8f55b945a1](https://linux-hardware.org/?probe=8f55b945a1) | Nov 20, 2020 |
| ASUSTek    | 970 PRO GAMING/AURA         | [de597aa847](https://linux-hardware.org/?probe=de597aa847) | Nov 20, 2020 |
| ASUSTek    | 970 PRO GAMING/AURA         | [f5aa8c9150](https://linux-hardware.org/?probe=f5aa8c9150) | Nov 20, 2020 |
| ASUSTek    | H110I-PLUS                  | [a3c484b8ee](https://linux-hardware.org/?probe=a3c484b8ee) | Nov 16, 2020 |
| ASUSTek    | H97M-PLUS                   | [f90977870e](https://linux-hardware.org/?probe=f90977870e) | Nov 04, 2020 |
| Gigabyte   | Z370 HD3P-CF                | [1af7b2b551](https://linux-hardware.org/?probe=1af7b2b551) | Oct 13, 2020 |
| ASUSTek    | H110I-PLUS                  | [e292456297](https://linux-hardware.org/?probe=e292456297) | Sep 17, 2020 |
| Lenovo     | SHARKBAY SDK0E50510 WIN     | [e7b41f62a4](https://linux-hardware.org/?probe=e7b41f62a4) | Sep 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [20bdbc68b7](https://linux-hardware.org/?probe=20bdbc68b7) | Sep 12, 2020 |
| ASUSTek    | H81M-E                      | [43b8c677bc](https://linux-hardware.org/?probe=43b8c677bc) | Sep 10, 2020 |
| Lenovo     | MAHOBAY NOK                 | [d95b985658](https://linux-hardware.org/?probe=d95b985658) | Sep 01, 2020 |
| Foxconn    | 2ADA                        | [24cad8bed5](https://linux-hardware.org/?probe=24cad8bed5) | Aug 28, 2020 |
| Foxconn    | 2ADA                        | [3d4c2a283d](https://linux-hardware.org/?probe=3d4c2a283d) | Aug 28, 2020 |
| ASRock     | B450 Gaming-ITX/ac          | [e27db6fb31](https://linux-hardware.org/?probe=e27db6fb31) | Aug 24, 2020 |
| HP         | 802E                        | [653b11eec3](https://linux-hardware.org/?probe=653b11eec3) | Aug 11, 2020 |
| HP         | 802E                        | [6f32afeb2b](https://linux-hardware.org/?probe=6f32afeb2b) | Aug 10, 2020 |
| HP         | 802E                        | [25d8ddc0bb](https://linux-hardware.org/?probe=25d8ddc0bb) | Aug 10, 2020 |
| Gigabyte   | B150M-D3H-CF                | [50dc692a9e](https://linux-hardware.org/?probe=50dc692a9e) | Jul 23, 2020 |
| Gigabyte   | Z170X-Gaming 5 Modified ... | [a62f520dc3](https://linux-hardware.org/?probe=a62f520dc3) | Jul 18, 2020 |
| MSI        | B450M MORTAR MAX            | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| HP         | 1998                        | [255863fefb](https://linux-hardware.org/?probe=255863fefb) | Jun 01, 2020 |
| Lenovo     | ThinkCentre M90p 3269A12    | [b159b440f2](https://linux-hardware.org/?probe=b159b440f2) | Jun 01, 2020 |
| Lenovo     | ThinkCentre M90p 3269A12    | [4181637bf3](https://linux-hardware.org/?probe=4181637bf3) | Jun 01, 2020 |
| Biostar    | H110MHC                     | [98d1029698](https://linux-hardware.org/?probe=98d1029698) | May 26, 2020 |
| ASUSTek    | B150M-C                     | [2229b866b3](https://linux-hardware.org/?probe=2229b866b3) | May 26, 2020 |
| ASUSTek    | H110I-PLUS                  | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| ASUSTek    | H110I-PLUS                  | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| ASUSTek    | STRIX H270F GAMING          | [c30a3e0ddd](https://linux-hardware.org/?probe=c30a3e0ddd) | May 11, 2020 |
| Dell       | 0C2KJT A00                  | [179a82277c](https://linux-hardware.org/?probe=179a82277c) | May 01, 2020 |
| MSI        | 2A9C                        | [23df26e5de](https://linux-hardware.org/?probe=23df26e5de) | Apr 25, 2020 |
| Acer       | Aspire XC-710 V:1.1         | [664ac5b85b](https://linux-hardware.org/?probe=664ac5b85b) | Apr 24, 2020 |
| MSI        | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| ASUSTek    | H110I-PLUS                  | [f504649d96](https://linux-hardware.org/?probe=f504649d96) | Apr 11, 2020 |
| ASUSTek    | H110I-PLUS                  | [3916938374](https://linux-hardware.org/?probe=3916938374) | Apr 11, 2020 |
| Gigabyte   | Z87-HD3                     | [52a7dab5ac](https://linux-hardware.org/?probe=52a7dab5ac) | Apr 09, 2020 |
| ASUSTek    | H110I-PLUS                  | [9c72670aa1](https://linux-hardware.org/?probe=9c72670aa1) | Apr 05, 2020 |
| ASUSTek    | H110I-PLUS                  | [37fb7cae94](https://linux-hardware.org/?probe=37fb7cae94) | Mar 30, 2020 |
| MSI        | B360M FIRE                  | [8bb021d2a6](https://linux-hardware.org/?probe=8bb021d2a6) | Mar 27, 2020 |
| ASUSTek    | H110I-PLUS                  | [18b565a861](https://linux-hardware.org/?probe=18b565a861) | Mar 26, 2020 |
| ASUSTek    | H110I-PLUS                  | [abce376627](https://linux-hardware.org/?probe=abce376627) | Mar 24, 2020 |
| ASUSTek    | H110I-PLUS                  | [e6860a26ae](https://linux-hardware.org/?probe=e6860a26ae) | Mar 24, 2020 |
| ASUSTek    | H110I-PLUS                  | [5f2e14b65b](https://linux-hardware.org/?probe=5f2e14b65b) | Mar 16, 2020 |
| ASUSTek    | H110I-PLUS                  | [1bcf8a4701](https://linux-hardware.org/?probe=1bcf8a4701) | Mar 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [bd55777a4f](https://linux-hardware.org/?probe=bd55777a4f) | Mar 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [137262daa3](https://linux-hardware.org/?probe=137262daa3) | Mar 05, 2020 |
| ASUSTek    | H110I-PLUS                  | [047acafb1a](https://linux-hardware.org/?probe=047acafb1a) | Feb 28, 2020 |
| ASUSTek    | H110I-PLUS                  | [e8315b1469](https://linux-hardware.org/?probe=e8315b1469) | Feb 28, 2020 |
| ASUSTek    | H110I-PLUS                  | [04e5b85d84](https://linux-hardware.org/?probe=04e5b85d84) | Feb 28, 2020 |
| Gigabyte   | Z390 GAMING X-CF            | [310ae04477](https://linux-hardware.org/?probe=310ae04477) | Feb 27, 2020 |
| ASUSTek    | H110I-PLUS                  | [046814376c](https://linux-hardware.org/?probe=046814376c) | Feb 20, 2020 |
| ASUSTek    | H110I-PLUS                  | [a417965167](https://linux-hardware.org/?probe=a417965167) | Feb 19, 2020 |
| Intel      | DH77DF AAG40293-301         | [ac00169b1c](https://linux-hardware.org/?probe=ac00169b1c) | Feb 14, 2020 |
| ASUSTek    | H110I-PLUS                  | [cef9a00862](https://linux-hardware.org/?probe=cef9a00862) | Feb 12, 2020 |
| ASUSTek    | H110I-PLUS                  | [dcc65f9ee3](https://linux-hardware.org/?probe=dcc65f9ee3) | Feb 11, 2020 |
| ASUSTek    | H110I-PLUS                  | [900a11f8b3](https://linux-hardware.org/?probe=900a11f8b3) | Feb 10, 2020 |
| Gigabyte   | GA-MA78GM-S2HP              | [20d5a3bd6a](https://linux-hardware.org/?probe=20d5a3bd6a) | Feb 01, 2020 |
| Gigabyte   | Z77N-WIFI                   | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| Gigabyte   | P55A-UD3                    | [7168fd0137](https://linux-hardware.org/?probe=7168fd0137) | Jan 11, 2020 |
| ASUSTek    | Z8NA-D6                     | [b2d6dabaa7](https://linux-hardware.org/?probe=b2d6dabaa7) | Dec 23, 2019 |
| MSI        | X470 GAMING PRO CARBON      | [e3b6ce369a](https://linux-hardware.org/?probe=e3b6ce369a) | Dec 23, 2019 |
| Intel      | DZ68DB AAG27985-101         | [15f84fa3f2](https://linux-hardware.org/?probe=15f84fa3f2) | Oct 26, 2019 |
| Gigabyte   | GA-MA78GM-S2HP              | [3392a03f3c](https://linux-hardware.org/?probe=3392a03f3c) | Oct 03, 2019 |
| Gigabyte   | B150M-D3H-CF                | [4302e84025](https://linux-hardware.org/?probe=4302e84025) | Sep 24, 2019 |
| ASUSTek    | B150M-A                     | [e8ccb234ed](https://linux-hardware.org/?probe=e8ccb234ed) | Aug 30, 2019 |
| ASRock     | B75M R2.0                   | [1479826c17](https://linux-hardware.org/?probe=1479826c17) | Aug 28, 2019 |
| Hardkernel | ODROID-H2                   | [26d6c60ad5](https://linux-hardware.org/?probe=26d6c60ad5) | Jul 06, 2019 |
| Gigabyte   | GA-MA78GM-S2HP              | [ea2ad2bc4d](https://linux-hardware.org/?probe=ea2ad2bc4d) | Jun 05, 2019 |
| Dell       | 0CRH6C A01                  | [23dcf2aff6](https://linux-hardware.org/?probe=23dcf2aff6) | Apr 08, 2019 |
| ASUSTek    | B150M-A                     | [61bb547684](https://linux-hardware.org/?probe=61bb547684) | Apr 08, 2019 |
| ASUSTek    | B150M-A                     | [8549b6dfd8](https://linux-hardware.org/?probe=8549b6dfd8) | Apr 08, 2019 |
| ASRock     | Z270 Killer SLI             | [a03ea38833](https://linux-hardware.org/?probe=a03ea38833) | Jul 06, 2018 |
| Gigabyte   | GA-M56S-S3                  | [17f0958960](https://linux-hardware.org/?probe=17f0958960) | Oct 06, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 17       | 11.56%  |
| Ubuntu 18.04      | 13       | 8.84%   |
| OpenMandriva 4.2  | 10       | 6.8%    |
| Ubuntu 22.04      | 8        | 5.44%   |
| Arch Rolling      | 8        | 5.44%   |
| Debian 11         | 7        | 4.76%   |
| Pop!_OS 22.04     | 6        | 4.08%   |
| OpenMandriva 4.3  | 5        | 3.4%    |
| KDE neon 20.04    | 5        | 3.4%    |
| Ubuntu 19.10      | 4        | 2.72%   |
| Fedora 35         | 4        | 2.72%   |
| Ubuntu 20.10      | 3        | 2.04%   |
| ArcoLinux Rolling | 3        | 2.04%   |
| Ubuntu 21.10      | 2        | 1.36%   |
| Ubuntu 19.04      | 2        | 1.36%   |
| Slackware 15.0    | 2        | 1.36%   |
| PostmarketOS Edge | 2        | 1.36%   |
| Pop!_OS 20.10     | 2        | 1.36%   |
| Parrot 4.9        | 2        | 1.36%   |
| Gentoo 2.7        | 2        | 1.36%   |
| Fedora 31         | 2        | 1.36%   |
| Elementary 5.1.7  | 2        | 1.36%   |
| CentOS 8          | 2        | 1.36%   |
| Zorin 15          | 1        | 0.68%   |
| Xubuntu 18.04     | 1        | 0.68%   |
| Ubuntu MATE 20.04 | 1        | 0.68%   |
| Ubuntu 22.10      | 1        | 0.68%   |
| Ubuntu 21.04      | 1        | 0.68%   |
| SteamOS 3.3       | 1        | 0.68%   |
| Slackware 14.2    | 1        | 0.68%   |
| ROSA R8.1         | 1        | 0.68%   |
| Pop!_OS 21.04     | 1        | 0.68%   |
| OpenMandriva 4.50 | 1        | 0.68%   |
| Manjaro 22.0.0    | 1        | 0.68%   |
| Manjaro 21.1.0    | 1        | 0.68%   |
| Manjaro 21.0.6    | 1        | 0.68%   |
| Manjaro 20.0.3    | 1        | 0.68%   |
| Lubuntu 18.04     | 1        | 0.68%   |
| Linux Mint 20.3   | 1        | 0.68%   |
| Linux Mint 20     | 1        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 47       | 33.1%   |
| OpenMandriva | 16       | 11.27%  |
| Fedora       | 10       | 7.04%   |
| Pop!_OS      | 9        | 6.34%   |
| Arch         | 9        | 6.34%   |
| Debian       | 7        | 4.93%   |
| KDE neon     | 5        | 3.52%   |
| Manjaro      | 4        | 2.82%   |
| Slackware    | 3        | 2.11%   |
| Gentoo       | 3        | 2.11%   |
| Elementary   | 3        | 2.11%   |
| CentOS       | 3        | 2.11%   |
| ArcoLinux    | 3        | 2.11%   |
| PostmarketOS | 2        | 1.41%   |
| Parrot       | 2        | 1.41%   |
| Linux Mint   | 2        | 1.41%   |
| Kubuntu      | 2        | 1.41%   |
| EndeavourOS  | 2        | 1.41%   |
| Clear Linux  | 2        | 1.41%   |
| Zorin        | 1        | 0.7%    |
| Xubuntu      | 1        | 0.7%    |
| Ubuntu MATE  | 1        | 0.7%    |
| SteamOS      | 1        | 0.7%    |
| ROSA         | 1        | 0.7%    |
| Lubuntu      | 1        | 0.7%    |
| Kali         | 1        | 0.7%    |
| Artix        | 1        | 0.7%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002            | 9        | 5.36%   |
| 5.16.7-desktop-1omv4003             | 5        | 2.98%   |
| 5.4.0-42-generic                    | 3        | 1.79%   |
| 6.1.1-arch1-1                       | 2        | 1.19%   |
| 5.5.0-1parrot1-amd64                | 2        | 1.19%   |
| 5.4.0-56-generic                    | 2        | 1.19%   |
| 5.4.0-47-generic                    | 2        | 1.19%   |
| 5.4.0-33-generic                    | 2        | 1.19%   |
| 5.4.0-109-generic                   | 2        | 1.19%   |
| 5.3.0-46-generic                    | 2        | 1.19%   |
| 5.19.0-76051900-generic             | 2        | 1.19%   |
| 5.15.0-46-generic                   | 2        | 1.19%   |
| 5.13.0-35-generic                   | 2        | 1.19%   |
| 5.11.0-43-generic                   | 2        | 1.19%   |
| 5.0.0-25-generic                    | 2        | 1.19%   |
| 4.15.0-88-generic                   | 2        | 1.19%   |
| 6.2.9-060209-generic                | 1        | 0.6%    |
| 6.2.8-200.fc37.x86_64               | 1        | 0.6%    |
| 6.2.6-arch1-1                       | 1        | 0.6%    |
| 6.1.5-arch2-1                       | 1        | 0.6%    |
| 6.1.10-arch1-1                      | 1        | 0.6%    |
| 6.1.0-0.deb11.6-amd64               | 1        | 0.6%    |
| 6.0.12-76060006-generic             | 1        | 0.6%    |
| 6.0.1-arch2-1                       | 1        | 0.6%    |
| 6.0.0-rc6-g4954dfcf85a8-dirty       | 1        | 0.6%    |
| 6.0.0-rc1-14001-ga907b05f09bf-dirty | 1        | 0.6%    |
| 5.9.16-050916-generic               | 1        | 0.6%    |
| 5.9.12-artix1-1                     | 1        | 0.6%    |
| 5.9.0-kali1-amd64                   | 1        | 0.6%    |
| 5.8.7-arch1-1                       | 1        | 0.6%    |
| 5.8.13-100.fc31.x86_64              | 1        | 0.6%    |
| 5.8.0-7642-generic                  | 1        | 0.6%    |
| 5.8.0-7630-generic                  | 1        | 0.6%    |
| 5.8.0-60-generic                    | 1        | 0.6%    |
| 5.8.0-59-generic                    | 1        | 0.6%    |
| 5.8.0-55-generic                    | 1        | 0.6%    |
| 5.8.0-50-generic                    | 1        | 0.6%    |
| 5.8.0-44-generic                    | 1        | 0.6%    |
| 5.8.0-38-generic                    | 1        | 0.6%    |
| 5.8.0-36-generic                    | 1        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 20       | 12.82%  |
| 5.15.0  | 10       | 6.41%   |
| 5.8.0   | 9        | 5.77%   |
| 5.10.14 | 9        | 5.77%   |
| 5.3.0   | 7        | 4.49%   |
| 5.13.0  | 7        | 4.49%   |
| 5.11.0  | 7        | 4.49%   |
| 4.15.0  | 6        | 3.85%   |
| 5.16.7  | 5        | 3.21%   |
| 5.10.0  | 5        | 3.21%   |
| 5.0.0   | 5        | 3.21%   |
| 5.19.0  | 3        | 1.92%   |
| 5.17.5  | 3        | 1.92%   |
| 4.18.0  | 3        | 1.92%   |
| 6.1.1   | 2        | 1.28%   |
| 6.0.0   | 2        | 1.28%   |
| 5.5.0   | 2        | 1.28%   |
| 5.14.14 | 2        | 1.28%   |
| 6.2.9   | 1        | 0.64%   |
| 6.2.8   | 1        | 0.64%   |
| 6.2.6   | 1        | 0.64%   |
| 6.1.5   | 1        | 0.64%   |
| 6.1.10  | 1        | 0.64%   |
| 6.1.0   | 1        | 0.64%   |
| 6.0.12  | 1        | 0.64%   |
| 6.0.1   | 1        | 0.64%   |
| 5.9.16  | 1        | 0.64%   |
| 5.9.12  | 1        | 0.64%   |
| 5.9.0   | 1        | 0.64%   |
| 5.8.7   | 1        | 0.64%   |
| 5.8.13  | 1        | 0.64%   |
| 5.7.7   | 1        | 0.64%   |
| 5.7.0   | 1        | 0.64%   |
| 5.6.14  | 1        | 0.64%   |
| 5.6.0   | 1        | 0.64%   |
| 5.5.10  | 1        | 0.64%   |
| 5.19.13 | 1        | 0.64%   |
| 5.19.10 | 1        | 0.64%   |
| 5.18.5  | 1        | 0.64%   |
| 5.18.2  | 1        | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 20       | 13.16%  |
| 5.10    | 18       | 11.84%  |
| 5.15    | 16       | 10.53%  |
| 5.8     | 11       | 7.24%   |
| 5.13    | 9        | 5.92%   |
| 5.16    | 8        | 5.26%   |
| 5.11    | 8        | 5.26%   |
| 5.3     | 7        | 4.61%   |
| 4.15    | 6        | 3.95%   |
| 5.19    | 5        | 3.29%   |
| 5.17    | 5        | 3.29%   |
| 5.0     | 5        | 3.29%   |
| 6.0     | 4        | 2.63%   |
| 6.2     | 3        | 1.97%   |
| 6.1     | 3        | 1.97%   |
| 5.9     | 3        | 1.97%   |
| 5.5     | 3        | 1.97%   |
| 5.18    | 3        | 1.97%   |
| 4.18    | 3        | 1.97%   |
| 5.7     | 2        | 1.32%   |
| 5.6     | 2        | 1.32%   |
| 5.14    | 2        | 1.32%   |
| 5.12    | 2        | 1.32%   |
| 4.9     | 1        | 0.66%   |
| 4.4     | 1        | 0.66%   |
| 4.17    | 1        | 0.66%   |
| 3.10    | 1        | 0.66%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 135      | 97.83%  |
| aarch64 | 2        | 1.45%   |
| i686    | 1        | 0.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 61       | 42.07%  |
| KDE5       | 32       | 22.07%  |
| Unknown    | 24       | 16.55%  |
| XFCE       | 8        | 5.52%   |
| KDE        | 4        | 2.76%   |
| Pantheon   | 3        | 2.07%   |
| MATE       | 3        | 2.07%   |
| X-Cinnamon | 2        | 1.38%   |
| sway       | 2        | 1.38%   |
| openbox    | 1        | 0.69%   |
| LXDE       | 1        | 0.69%   |
| KDE4       | 1        | 0.69%   |
| i3         | 1        | 0.69%   |
| Deepin     | 1        | 0.69%   |
| awesome    | 1        | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 109      | 75.17%  |
| Wayland | 21       | 14.48%  |
| Unknown | 10       | 6.9%    |
| Tty     | 5        | 3.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 70       | 48.95%  |
| SDDM    | 33       | 23.08%  |
| GDM3    | 16       | 11.19%  |
| GDM     | 11       | 7.69%   |
| LightDM | 7        | 4.9%    |
| TDM     | 2        | 1.4%    |
| Ly      | 2        | 1.4%    |
| XDM     | 1        | 0.7%    |
| KDM     | 1        | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 51       | 35.42%  |
| en_HK   | 45       | 31.25%  |
| Unknown | 14       | 9.72%   |
| zh_CN   | 11       | 7.64%   |
| zh_TW   | 10       | 6.94%   |
| zh_HK   | 4        | 2.78%   |
| en_GB   | 4        | 2.78%   |
| C       | 3        | 2.08%   |
| en_AU   | 2        | 1.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 76       | 53.52%  |
| BIOS | 66       | 46.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 106      | 75.18%  |
| Btrfs   | 14       | 9.93%   |
| Overlay | 9        | 6.38%   |
| Xfs     | 6        | 4.26%   |
| Zfs     | 3        | 2.13%   |
| F2fs    | 1        | 0.71%   |
| Ext3    | 1        | 0.71%   |
| Unknown | 1        | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 64       | 45.71%  |
| GPT     | 61       | 43.57%  |
| MBR     | 15       | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 79.02%  |
| Yes       | 30       | 20.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 97       | 68.31%  |
| Yes       | 45       | 31.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 35       | 25.36%  |
| MSI                 | 26       | 18.84%  |
| Gigabyte Technology | 25       | 18.12%  |
| ASRock              | 14       | 10.14%  |
| Dell                | 10       | 7.25%   |
| Lenovo              | 7        | 5.07%   |
| Hewlett-Packard     | 7        | 5.07%   |
| Unknown             | 3        | 2.17%   |
| Supermicro          | 2        | 1.45%   |
| Intel               | 2        | 1.45%   |
| Soyo                | 1        | 0.72%   |
| Seco                | 1        | 0.72%   |
| Huanan              | 1        | 0.72%   |
| Hardkernel          | 1        | 0.72%   |
| Foxconn             | 1        | 0.72%   |
| Biostar             | 1        | 0.72%   |
| Acer                | 1        | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Desktops | Percent |
|----------------------------------------------|----------|---------|
| MSI MS-7C94                                  | 3        | 2.17%   |
| ASUS H110I-PLUS                              | 3        | 2.17%   |
| ASUS All Series                              | 3        | 2.17%   |
| Unknown                                      | 3        | 2.17%   |
| MSI MS-7D42                                  | 2        | 1.45%   |
| MSI MS-7C02                                  | 2        | 1.45%   |
| MSI MS-7B93                                  | 2        | 1.45%   |
| HP ProDesk 600 G1 SFF                        | 2        | 1.45%   |
| Gigabyte X570 AORUS ELITE                    | 2        | 1.45%   |
| ASUS Z8NA-D6                                 | 2        | 1.45%   |
| ASUS VM65                                    | 2        | 1.45%   |
| ASUS VM62                                    | 2        | 1.45%   |
| ASRock H410M-ITX/ac                          | 2        | 1.45%   |
| ASRock H410M-HDV                             | 2        | 1.45%   |
| Supermicro PIO-617R-TLN4F+-ST031             | 1        | 0.72%   |
| Supermicro C2SBC-Q                           | 1        | 0.72%   |
| Soyo SY-A68M FS V2.0                         | 1        | 0.72%   |
| Seco C40                                     | 1        | 0.72%   |
| MSI Pro 3130 Small Form Factor PC            | 1        | 0.72%   |
| MSI MS-7D31                                  | 1        | 0.72%   |
| MSI MS-7C52                                  | 1        | 0.72%   |
| MSI MS-7C34                                  | 1        | 0.72%   |
| MSI MS-7B89                                  | 1        | 0.72%   |
| MSI MS-7B78                                  | 1        | 0.72%   |
| MSI MS-7B53                                  | 1        | 0.72%   |
| MSI MS-7A40                                  | 1        | 0.72%   |
| MSI MS-7A38                                  | 1        | 0.72%   |
| MSI MS-7918                                  | 1        | 0.72%   |
| MSI MS-7851                                  | 1        | 0.72%   |
| MSI MS-7817                                  | 1        | 0.72%   |
| MSI MS-7808                                  | 1        | 0.72%   |
| MSI MS-7798                                  | 1        | 0.72%   |
| MSI MS-7680                                  | 1        | 0.72%   |
| MSI MS-7599                                  | 1        | 0.72%   |
| MSI KT541AA-UUB a6528hk                      | 1        | 0.72%   |
| Lenovo ZHENGJIUZHE REN9000K-34IMZ 90Q90022CP | 1        | 0.72%   |
| Lenovo ThinkCentre M93 10A4A05GJP            | 1        | 0.72%   |
| Lenovo ThinkCentre M92p 3227D13              | 1        | 0.72%   |
| Lenovo ThinkCentre M90p 3269A12              | 1        | 0.72%   |
| Lenovo ThinkCentre M73 10AYCTO1WW            | 1        | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| ASUS PRIME                       | 8        | 5.8%    |
| Lenovo ThinkCentre               | 4        | 2.9%    |
| Dell OptiPlex                    | 4        | 2.9%    |
| MSI MS-7C94                      | 3        | 2.17%   |
| HP ProDesk                       | 3        | 2.17%   |
| Gigabyte X570                    | 3        | 2.17%   |
| Dell Precision                   | 3        | 2.17%   |
| ASUS TUF                         | 3        | 2.17%   |
| ASUS H110I-PLUS                  | 3        | 2.17%   |
| ASUS All                         | 3        | 2.17%   |
| Unknown                          | 3        | 2.17%   |
| MSI MS-7D42                      | 2        | 1.45%   |
| MSI MS-7C02                      | 2        | 1.45%   |
| MSI MS-7B93                      | 2        | 1.45%   |
| Gigabyte B450                    | 2        | 1.45%   |
| Dell Inspiron                    | 2        | 1.45%   |
| ASUS Z8NA-D6                     | 2        | 1.45%   |
| ASUS VM65                        | 2        | 1.45%   |
| ASUS VM62                        | 2        | 1.45%   |
| ASUS ROG                         | 2        | 1.45%   |
| ASRock H410M-ITX                 | 2        | 1.45%   |
| ASRock H410M-HDV                 | 2        | 1.45%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1        | 0.72%   |
| Supermicro C2SBC-Q               | 1        | 0.72%   |
| Soyo SY-A68M                     | 1        | 0.72%   |
| Seco C40                         | 1        | 0.72%   |
| MSI Pro                          | 1        | 0.72%   |
| MSI MS-7D31                      | 1        | 0.72%   |
| MSI MS-7C52                      | 1        | 0.72%   |
| MSI MS-7C34                      | 1        | 0.72%   |
| MSI MS-7B89                      | 1        | 0.72%   |
| MSI MS-7B78                      | 1        | 0.72%   |
| MSI MS-7B53                      | 1        | 0.72%   |
| MSI MS-7A40                      | 1        | 0.72%   |
| MSI MS-7A38                      | 1        | 0.72%   |
| MSI MS-7918                      | 1        | 0.72%   |
| MSI MS-7851                      | 1        | 0.72%   |
| MSI MS-7817                      | 1        | 0.72%   |
| MSI MS-7808                      | 1        | 0.72%   |
| MSI MS-7798                      | 1        | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 16       | 11.59%  |
| 2019    | 15       | 10.87%  |
| 2020    | 13       | 9.42%   |
| 2013    | 13       | 9.42%   |
| 2021    | 12       | 8.7%    |
| 2016    | 11       | 7.97%   |
| 2014    | 10       | 7.25%   |
| 2010    | 9        | 6.52%   |
| 2015    | 7        | 5.07%   |
| 2011    | 7        | 5.07%   |
| 2022    | 6        | 4.35%   |
| 2012    | 5        | 3.62%   |
| 2017    | 4        | 2.9%    |
| 2009    | 3        | 2.17%   |
| 2008    | 3        | 2.17%   |
| Unknown | 2        | 1.45%   |
| 2023    | 1        | 0.72%   |
| 2007    | 1        | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 138      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 134      | 97.1%   |
| Enabled  | 4        | 2.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 138      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 37       | 26.06%  |
| 8.01-16.0   | 27       | 19.01%  |
| 32.01-64.0  | 26       | 18.31%  |
| 4.01-8.0    | 17       | 11.97%  |
| 64.01-256.0 | 17       | 11.97%  |
| 3.01-4.0    | 12       | 8.45%   |
| 24.01-32.0  | 3        | 2.11%   |
| 1.01-2.0    | 2        | 1.41%   |
| 2.01-3.0    | 1        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 41       | 26.62%  |
| 2.01-3.0   | 37       | 24.03%  |
| 4.01-8.0   | 28       | 18.18%  |
| 3.01-4.0   | 19       | 12.34%  |
| 8.01-16.0  | 12       | 7.79%   |
| 0.51-1.0   | 10       | 6.49%   |
| 16.01-24.0 | 3        | 1.95%   |
| 0.01-0.5   | 3        | 1.95%   |
| 32.01-64.0 | 1        | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 41.67%  |
| 2      | 39       | 27.08%  |
| 3      | 22       | 15.28%  |
| 5      | 8        | 5.56%   |
| 4      | 7        | 4.86%   |
| 9      | 2        | 1.39%   |
| 6      | 2        | 1.39%   |
| 0      | 2        | 1.39%   |
| 11     | 1        | 0.69%   |
| 7      | 1        | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 69.06%  |
| Yes       | 43       | 30.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 134      | 97.1%   |
| No        | 4        | 2.9%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 76       | 53.15%  |
| No        | 67       | 46.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 72       | 50.7%   |
| Yes       | 70       | 49.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Desktops | Percent |
|-----------|----------|---------|
| Hong Kong | 138      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Central          | 74       | 50.68%  |
| Tuen Mun         | 9        | 6.16%   |
| Kowloon          | 8        | 5.48%   |
| Hong Kong        | 5        | 3.42%   |
| Ngau Wu Tok      | 4        | 2.74%   |
| Tseung Kwan O    | 3        | 2.05%   |
| To Kwa Wan       | 3        | 2.05%   |
| Tai Po           | 3        | 2.05%   |
| Ma On Shan Tsuen | 3        | 2.05%   |
| Hung Hom         | 3        | 2.05%   |
| Yuen Long        | 2        | 1.37%   |
| Wanchai          | 2        | 1.37%   |
| Quarry Bay       | 2        | 1.37%   |
| Kwu Tung         | 2        | 1.37%   |
| Ho Man Tin       | 2        | 1.37%   |
| Cheung Sha Lan   | 2        | 1.37%   |
| Wong Tai Sin     | 1        | 0.68%   |
| Tung Chung       | 1        | 0.68%   |
| Tsuen Wan        | 1        | 0.68%   |
| Tsimshatsui      | 1        | 0.68%   |
| Tai Wan To       | 1        | 0.68%   |
| Tai Kok Tsui     | 1        | 0.68%   |
| Sheung Shui      | 1        | 0.68%   |
| Shatin           | 1        | 0.68%   |
| Sham Shui Po     | 1        | 0.68%   |
| Sha Tin Wai      | 1        | 0.68%   |
| Sai Kung         | 1        | 0.68%   |
| North Point      | 1        | 0.68%   |
| Ma Wan           | 1        | 0.68%   |
| Ma On Shan       | 1        | 0.68%   |
| Lai Chi Kok      | 1        | 0.68%   |
| Kwun Hang        | 1        | 0.68%   |
| Kowloon Bay      | 1        | 0.68%   |
| Fo Tan           | 1        | 0.68%   |
| Chai Wan         | 1        | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 43       | 64     | 16.67%  |
| WDC                         | 36       | 62     | 13.95%  |
| Samsung Electronics         | 23       | 39     | 8.91%   |
| Toshiba                     | 21       | 30     | 8.14%   |
| SanDisk                     | 14       | 16     | 5.43%   |
| A-DATA Technology           | 14       | 20     | 5.43%   |
| Kingston                    | 11       | 13     | 4.26%   |
| Crucial                     | 9        | 14     | 3.49%   |
| Silicon Motion              | 8        | 10     | 3.1%    |
| Hitachi                     | 7        | 12     | 2.71%   |
| Transcend                   | 4        | 5      | 1.55%   |
| SK hynix                    | 4        | 8      | 1.55%   |
| LITEON                      | 4        | 4      | 1.55%   |
| Intel                       | 4        | 8      | 1.55%   |
| HGST                        | 4        | 5      | 1.55%   |
| Fujitsu                     | 4        | 9      | 1.55%   |
| Phison                      | 3        | 6      | 1.16%   |
| JMicron Technology          | 3        | 6      | 1.16%   |
| Hikvision                   | 3        | 3      | 1.16%   |
| DOGGO                       | 3        | 3      | 1.16%   |
| Unknown                     | 2        | 2      | 0.78%   |
| Team                        | 2        | 2      | 0.78%   |
| Plextor                     | 2        | 2      | 0.78%   |
| Netac                       | 2        | 2      | 0.78%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.78%   |
| Lite-On                     | 2        | 4      | 0.78%   |
| Gigabyte Technology         | 2        | 5      | 0.78%   |
| ZHITAI                      | 1        | 2      | 0.39%   |
| Yangtze Memory Technologies | 1        | 1      | 0.39%   |
| XPG                         | 1        | 1      | 0.39%   |
| tigo                        | 1        | 1      | 0.39%   |
| SPCC                        | 1        | 1      | 0.39%   |
| PNY                         | 1        | 1      | 0.39%   |
| OCZ                         | 1        | 1      | 0.39%   |
| Micron/Crucial Technology   | 1        | 1      | 0.39%   |
| Micron Technology           | 1        | 1      | 0.39%   |
| Maxtor                      | 1        | 1      | 0.39%   |
| Maxmemory                   | 1        | 2      | 0.39%   |
| Lexar                       | 1        | 1      | 0.39%   |
| KIOXIA-EXCERIA              | 1        | 2      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                           | 6        | 2.08%   |
| Samsung SSD 860 EVO 1TB                          | 5        | 1.74%   |
| A-DATA SP550 240GB SSD                           | 5        | 1.74%   |
| WDC WD10EZEX-08WN4A0 1TB                         | 4        | 1.39%   |
| Toshiba DT01ACA050 500GB                         | 4        | 1.39%   |
| WDC WD30EZRX-00D8PB0 3TB                         | 3        | 1.04%   |
| Toshiba DT01ACA300 3TB                           | 3        | 1.04%   |
| Seagate ST500DM002-1BD142 500GB                  | 3        | 1.04%   |
| Seagate ST3500413AS 500GB                        | 3        | 1.04%   |
| Seagate ST2000DM008-2FR102 2TB                   | 3        | 1.04%   |
| Kingston SA400S37480G 480GB SSD                  | 3        | 1.04%   |
| JMicron Generic 1TB                              | 3        | 1.04%   |
| Fujitsu F300 480GB                               | 3        | 1.04%   |
| DOGGO DQ-60G SSD                                 | 3        | 1.04%   |
| Crucial CT500MX500SSD1 500GB                     | 3        | 1.04%   |
| WDC WDS200T2B0A 2TB SSD                          | 2        | 0.69%   |
| SK hynix SC311 SATA 128GB SSD                    | 2        | 0.69%   |
| Silicon Motion NVMe SSD Drive 512GB              | 2        | 0.69%   |
| Silicon Motion NVMe SSD Drive 1024GB             | 2        | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB                   | 2        | 0.69%   |
| Seagate ST3500418AS 500GB                        | 2        | 0.69%   |
| Seagate ST3250318AS 250GB                        | 2        | 0.69%   |
| Seagate ST3250310AS 250GB                        | 2        | 0.69%   |
| Seagate ST320LT007-9ZV142 320GB                  | 2        | 0.69%   |
| Seagate ST3160815AS 160GB                        | 2        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                   | 2        | 0.69%   |
| Seagate ST1000DM003-1SB102 1TB                   | 2        | 0.69%   |
| Seagate ST1000DM003-1ER162 1TB                   | 2        | 0.69%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB            | 2        | 0.69%   |
| SanDisk NVMe SSD Drive 1TB                       | 2        | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB                     | 2        | 0.69%   |
| Samsung SSD 860 EVO 250GB                        | 2        | 0.69%   |
| Samsung SSD 850 EVO 250GB                        | 2        | 0.69%   |
| Samsung NVMe SSD Drive 512GB                     | 2        | 0.69%   |
| Netac SSD 240GB                                  | 2        | 0.69%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1TB | 2        | 0.69%   |
| LITEON CV6-CQ128 128GB SSD                       | 2        | 0.69%   |
| Lite-On NVMe SSD Drive 512GB                     | 2        | 0.69%   |
| Intel SSDPEKNW020T8 2TB                          | 2        | 0.69%   |
| Hitachi HDT721010SLA360 1TB                      | 2        | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Desktops | Drives | Percent |
|--------------------|----------|--------|---------|
| Seagate            | 43       | 64     | 40.57%  |
| WDC                | 24       | 46     | 22.64%  |
| Toshiba            | 21       | 30     | 19.81%  |
| Hitachi            | 7        | 12     | 6.6%    |
| HGST               | 4        | 5      | 3.77%   |
| JMicron Technology | 3        | 6      | 2.83%   |
| Unknown            | 1        | 1      | 0.94%   |
| Maxtor             | 1        | 1      | 0.94%   |
| HGST HTS           | 1        | 1      | 0.94%   |
| Fujitsu            | 1        | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 13       | 23     | 15.12%  |
| A-DATA Technology   | 11       | 17     | 12.79%  |
| Kingston            | 8        | 10     | 9.3%    |
| WDC                 | 7        | 7      | 8.14%   |
| Crucial             | 7        | 12     | 8.14%   |
| SanDisk             | 5        | 5      | 5.81%   |
| Transcend           | 4        | 5      | 4.65%   |
| LITEON              | 3        | 3      | 3.49%   |
| Fujitsu             | 3        | 8      | 3.49%   |
| DOGGO               | 3        | 3      | 3.49%   |
| Team                | 2        | 2      | 2.33%   |
| SK hynix            | 2        | 6      | 2.33%   |
| Netac               | 2        | 2      | 2.33%   |
| ZHITAI              | 1        | 1      | 1.16%   |
| tigo                | 1        | 1      | 1.16%   |
| SPCC                | 1        | 1      | 1.16%   |
| PNY                 | 1        | 1      | 1.16%   |
| Plextor             | 1        | 1      | 1.16%   |
| OCZ                 | 1        | 1      | 1.16%   |
| Micron Technology   | 1        | 1      | 1.16%   |
| Lexar               | 1        | 1      | 1.16%   |
| Intel               | 1        | 3      | 1.16%   |
| Hikvision           | 1        | 1      | 1.16%   |
| Dogfish             | 1        | 1      | 1.16%   |
| Corsair             | 1        | 1      | 1.16%   |
| Colorful            | 1        | 1      | 1.16%   |
| China               | 1        | 1      | 1.16%   |
| Apacer              | 1        | 3      | 1.16%   |
| Aoluska             | 1        | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 86       | 167    | 39.81%  |
| SSD     | 73       | 123    | 33.8%   |
| NVMe    | 54       | 90     | 25%     |
| Unknown | 2        | 3      | 0.93%   |
| MMC     | 1        | 1      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 116      | 275    | 63.74%  |
| NVMe | 54       | 90     | 29.67%  |
| SAS  | 11       | 18     | 6.04%   |
| MMC  | 1        | 1      | 0.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 83       | 141    | 49.11%  |
| 0.51-1.0   | 46       | 70     | 27.22%  |
| 1.01-2.0   | 16       | 22     | 9.47%   |
| 2.01-3.0   | 10       | 16     | 5.92%   |
| 3.01-4.0   | 7        | 28     | 4.14%   |
| 4.01-10.0  | 6        | 10     | 3.55%   |
| 10.01-20.0 | 1        | 3      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 32       | 21.48%  |
| 501-1000       | 21       | 14.09%  |
| 251-500        | 20       | 13.42%  |
| 51-100         | 17       | 11.41%  |
| More than 3000 | 16       | 10.74%  |
| 1001-2000      | 16       | 10.74%  |
| Unknown        | 11       | 7.38%   |
| 2001-3000      | 10       | 6.71%   |
| 1-20           | 6        | 4.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 55       | 34.38%  |
| 101-250        | 25       | 15.63%  |
| 251-500        | 16       | 10%     |
| 21-50          | 14       | 8.75%   |
| 501-1000       | 11       | 6.88%   |
| Unknown        | 11       | 6.88%   |
| 51-100         | 10       | 6.25%   |
| 1001-2000      | 8        | 5%      |
| 2001-3000      | 6        | 3.75%   |
| More than 3000 | 4        | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Desktops | Drives | Percent |
|-------------------------------------------|----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD          | 1        | 1      | 5.56%   |
| WDC WD30EZRX-00D8PB0 3TB                  | 1        | 1      | 5.56%   |
| WDC WD10EZEX-60WN4A1 1TB                  | 1        | 1      | 5.56%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 1        | 1      | 5.56%   |
| WDC WD10EALS-00Z8A0 1TB                   | 1        | 2      | 5.56%   |
| Toshiba MK1252GSX 120GB                   | 1        | 1      | 5.56%   |
| Toshiba DT01ACA100 1TB                    | 1        | 1      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB           | 1        | 1      | 5.56%   |
| Seagate ST3500418AS 500GB                 | 1        | 1      | 5.56%   |
| Seagate ST3250310AS 250GB                 | 1        | 1      | 5.56%   |
| Seagate ST3160815AS 160GB                 | 1        | 1      | 5.56%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB       | 1        | 1      | 5.56%   |
| LITEON IT LCS-128L9S-11 2.5 7mm 128GB SSD | 1        | 1      | 5.56%   |
| Kingston SA400S37480G 480GB SSD           | 1        | 1      | 5.56%   |
| Intel SSDPEKKW128G7 128GB                 | 1        | 1      | 5.56%   |
| Hitachi HTS542512K9SA00 120GB             | 1        | 1      | 5.56%   |
| HGST HTS 541010A9E680 1TB                 | 1        | 1      | 5.56%   |
| Crucial CT500MX500SSD1 500GB              | 1        | 2      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 5        | 5      | 29.41%  |
| WDC      | 4        | 6      | 23.53%  |
| Toshiba  | 2        | 2      | 11.76%  |
| LITEON   | 1        | 1      | 5.88%   |
| Kingston | 1        | 1      | 5.88%   |
| Intel    | 1        | 1      | 5.88%   |
| Hitachi  | 1        | 1      | 5.88%   |
| HGST HTS | 1        | 1      | 5.88%   |
| Crucial  | 1        | 2      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Seagate  | 5        | 5      | 41.67%  |
| WDC      | 3        | 5      | 25%     |
| Toshiba  | 2        | 2      | 16.67%  |
| Hitachi  | 1        | 1      | 8.33%   |
| HGST HTS | 1        | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 14     | 68.75%  |
| SSD  | 4        | 5      | 25%     |
| NVMe | 1        | 1      | 6.25%   |

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
| Detected | 73       | 189    | 47.71%  |
| Works    | 64       | 175    | 41.83%  |
| Malfunc  | 16       | 20     | 10.46%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 100      | 46.08%  |
| AMD                           | 35       | 16.13%  |
| SanDisk                       | 14       | 6.45%   |
| Samsung Electronics           | 13       | 5.99%   |
| ASMedia Technology            | 11       | 5.07%   |
| Silicon Motion                | 9        | 4.15%   |
| Phison Electronics            | 5        | 2.3%    |
| ADATA Technology              | 5        | 2.3%    |
| Micron/Crucial Technology     | 3        | 1.38%   |
| MAXIO Technology (Hangzhou)   | 3        | 1.38%   |
| Marvell Technology Group      | 3        | 1.38%   |
| Kingston Technology Company   | 3        | 1.38%   |
| Yangtze Memory Technologies   | 2        | 0.92%   |
| SK hynix                      | 2        | 0.92%   |
| Lite-On Technology            | 2        | 0.92%   |
| JMicron Technology            | 2        | 0.92%   |
| VIA Technologies              | 1        | 0.46%   |
| Nvidia                        | 1        | 0.46%   |
| LSI Logic / Symbios Logic     | 1        | 0.46%   |
| KIOXIA                        | 1        | 0.46%   |
| Integrated Technology Express | 1        | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 21       | 8.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 12       | 4.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12       | 4.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 11       | 4.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10       | 3.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8        | 3.17%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 2.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7        | 2.78%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 2.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6        | 2.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 5        | 1.98%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5        | 1.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5        | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5        | 1.98%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 5        | 1.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4        | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 1.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.59%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 1.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3        | 1.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3        | 1.19%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 3        | 1.19%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 3        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3        | 1.19%   |
| Yangtze Memory Non-Volatile memory controller                                           | 2        | 0.79%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2        | 0.79%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 2        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.79%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2        | 0.79%   |
| Phison E12 NVMe Controller                                                              | 2        | 0.79%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 2        | 0.79%   |
| Lite-On Non-Volatile memory controller                                                  | 2        | 0.79%   |
| Intel SSD 660P Series                                                                   | 2        | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 129      | 62.32%  |
| NVMe | 54       | 26.09%  |
| IDE  | 14       | 6.76%   |
| RAID | 9        | 4.35%   |
| SAS  | 1        | 0.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 100      | 72.46%  |
| AMD     | 36       | 26.09%  |
| Unknown | 2        | 1.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel Core i7-6700 CPU @ 3.40GHz       | 4        | 2.88%   |
| AMD Ryzen 5 3600 6-Core Processor      | 4        | 2.88%   |
| Intel Core i7-7700K CPU @ 4.20GHz      | 3        | 2.16%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 3        | 2.16%   |
| Intel Core i5-6400 CPU @ 2.70GHz       | 3        | 2.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 3        | 2.16%   |
| Intel Core i3-10100 CPU @ 3.60GHz      | 3        | 2.16%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 3        | 2.16%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 3        | 2.16%   |
| AMD Ryzen 7 3700X 8-Core Processor     | 3        | 2.16%   |
| Intel Xeon CPU X5675 @ 3.07GHz         | 2        | 1.44%   |
| Intel Core i7-9700K CPU @ 3.60GHz      | 2        | 1.44%   |
| Intel Core i7-9700 CPU @ 3.00GHz       | 2        | 1.44%   |
| Intel Core i7-8700 CPU @ 3.20GHz       | 2        | 1.44%   |
| Intel Core i7-2600 CPU @ 3.40GHz       | 2        | 1.44%   |
| Intel Core i5-8400 CPU @ 2.80GHz       | 2        | 1.44%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 2        | 1.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 2        | 1.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 2        | 1.44%   |
| Intel 12th Gen Core i7-12700K          | 2        | 1.44%   |
| Intel 12th Gen Core i5-12600K          | 2        | 1.44%   |
| Intel 11th Gen Core i7-11700 @ 2.50GHz | 2        | 1.44%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 2        | 1.44%   |
| AMD Ryzen 5 2600X Six-Core Processor   | 2        | 1.44%   |
|                                        | 2        | 1.44%   |
| Intel Xeon CPU X5650 @ 2.67GHz         | 1        | 0.72%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz    | 1        | 0.72%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz    | 1        | 0.72%   |
| Intel Xeon CPU E5-1650 v2 @ 3.50GHz    | 1        | 0.72%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz   | 1        | 0.72%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz    | 1        | 0.72%   |
| Intel Xeon CPU E3-1220 V2 @ 3.10GHz    | 1        | 0.72%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz | 1        | 0.72%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz | 1        | 0.72%   |
| Intel Pentium CPU G640 @ 2.80GHz       | 1        | 0.72%   |
| Intel Pentium CPU G620T @ 2.20GHz      | 1        | 0.72%   |
| Intel Pentium CPU G4560 @ 3.50GHz      | 1        | 0.72%   |
| Intel Pentium CPU G4400 @ 3.30GHz      | 1        | 0.72%   |
| Intel Pentium CPU G3250T @ 2.80GHz     | 1        | 0.72%   |
| Intel Pentium CPU G2020 @ 2.90GHz      | 1        | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 23       | 16.55%  |
| Intel Core i5          | 22       | 15.83%  |
| Other                  | 17       | 12.23%  |
| Intel Core i3          | 13       | 9.35%   |
| AMD Ryzen 5            | 12       | 8.63%   |
| Intel Xeon             | 9        | 6.47%   |
| AMD Ryzen 7            | 9        | 6.47%   |
| Intel Pentium          | 6        | 4.32%   |
| Intel Celeron          | 5        | 3.6%    |
| AMD Ryzen 9            | 5        | 3.6%    |
| AMD Phenom II X4       | 3        | 2.16%   |
| Intel Core i9          | 2        | 1.44%   |
| Intel Pentium Gold     | 1        | 0.72%   |
| Intel Pentium Dual     | 1        | 0.72%   |
| Intel Core 2 Quad      | 1        | 0.72%   |
| Intel Core 2 Extreme   | 1        | 0.72%   |
| Intel Core 2 Duo       | 1        | 0.72%   |
| AMD Ryzen Threadripper | 1        | 0.72%   |
| AMD Ryzen Embedded     | 1        | 0.72%   |
| AMD Phenom II X6       | 1        | 0.72%   |
| AMD FX                 | 1        | 0.72%   |
| AMD Athlon II X4       | 1        | 0.72%   |
| AMD Athlon 64 X2       | 1        | 0.72%   |
| AMD A8                 | 1        | 0.72%   |
| AMD A10                | 1        | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 50       | 35.97%  |
| 2       | 27       | 19.42%  |
| 8       | 20       | 14.39%  |
| 6       | 20       | 14.39%  |
| 12      | 11       | 7.91%   |
| 16      | 4        | 2.88%   |
| 10      | 3        | 2.16%   |
| Unknown | 2        | 1.44%   |
| 24      | 1        | 0.72%   |
| 3       | 1        | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 132      | 95.65%  |
| 2       | 4        | 2.9%    |
| Unknown | 2        | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 87       | 62.59%  |
| 1       | 50       | 35.97%  |
| Unknown | 2        | 1.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 138      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 23.08%  |
| 0x306c3    | 12       | 8.39%   |
| 0x90672    | 8        | 5.59%   |
| 0x306a9    | 7        | 4.9%    |
| 0x206a7    | 7        | 4.9%    |
| 0x506e3    | 6        | 4.2%    |
| 0x906ed    | 5        | 3.5%    |
| 0x906ea    | 5        | 3.5%    |
| 0x0800820d | 4        | 2.8%    |
| 0xa0653    | 3        | 2.1%    |
| 0x906e9    | 3        | 2.1%    |
| 0x806e9    | 3        | 2.1%    |
| 0x40651    | 3        | 2.1%    |
| 0x0a50000c | 3        | 2.1%    |
| 0x0a201009 | 3        | 2.1%    |
| 0x08701013 | 3        | 2.1%    |
| 0xa0671    | 2        | 1.4%    |
| 0x90675    | 2        | 1.4%    |
| 0x306e4    | 2        | 1.4%    |
| 0x206c2    | 2        | 1.4%    |
| 0x20652    | 2        | 1.4%    |
| 0x0a201016 | 2        | 1.4%    |
| 0x08701021 | 2        | 1.4%    |
| 0x06003106 | 2        | 1.4%    |
| 0x010000c8 | 2        | 1.4%    |
| 0xa0655    | 1        | 0.7%    |
| 0x906eb    | 1        | 0.7%    |
| 0x706a1    | 1        | 0.7%    |
| 0x6fd      | 1        | 0.7%    |
| 0x20655    | 1        | 0.7%    |
| 0x106e5    | 1        | 0.7%    |
| 0x1067a    | 1        | 0.7%    |
| 0x10677    | 1        | 0.7%    |
| 0x0a601201 | 1        | 0.7%    |
| 0x0a50000d | 1        | 0.7%    |
| 0x0a20120a | 1        | 0.7%    |
| 0x08108109 | 1        | 0.7%    |
| 0x0810100b | 1        | 0.7%    |
| 0x08001137 | 1        | 0.7%    |
| 0x06000852 | 1        | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 20       | 14.29%  |
| KabyLake         | 19       | 13.57%  |
| Zen 3            | 10       | 7.14%   |
| IvyBridge        | 10       | 7.14%   |
| Zen 2            | 9        | 6.43%   |
| Skylake          | 9        | 6.43%   |
| Alderlake Hybrid | 9        | 6.43%   |
| SandyBridge      | 8        | 5.71%   |
| Unknown          | 8        | 5.71%   |
| CometLake        | 7        | 5%      |
| Zen+             | 6        | 4.29%   |
| Westmere         | 6        | 4.29%   |
| K10              | 5        | 3.57%   |
| Zen              | 2        | 1.43%   |
| Steamroller      | 2        | 1.43%   |
| Penryn           | 2        | 1.43%   |
| Icelake          | 2        | 1.43%   |
| Core             | 2        | 1.43%   |
| Piledriver       | 1        | 0.71%   |
| Nehalem          | 1        | 0.71%   |
| K8 Hammer        | 1        | 0.71%   |
| Goldmont plus    | 1        | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 62       | 40.52%  |
| Intel             | 57       | 37.25%  |
| AMD               | 33       | 21.57%  |
| ASPEED Technology | 1        | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 6.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 3.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 3.23%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 4        | 2.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 2.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 2.58%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 4        | 2.58%   |
| Intel HD Graphics 530                                                       | 4        | 2.58%   |
| Intel AlderLake-S GT1                                                       | 4        | 2.58%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 2.58%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 2.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4        | 2.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3        | 1.94%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.94%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.94%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.94%   |
| Intel HD Graphics 610                                                       | 3        | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3        | 1.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3        | 1.94%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.29%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2        | 1.29%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.29%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 2        | 1.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2        | 1.29%   |
| Intel HD Graphics 620                                                       | 2        | 1.29%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.29%   |
| AMD RS780 [Radeon HD 3200]                                                  | 2        | 1.29%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.29%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.29%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 2        | 1.29%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.65%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1        | 0.65%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.65%   |
| Nvidia GT200GL [Quadro FX 5800]                                             | 1        | 0.65%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1        | 0.65%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 54       | 38.85%  |
| 1 x Intel      | 45       | 32.37%  |
| 1 x AMD        | 28       | 20.14%  |
| Intel + Nvidia | 5        | 3.6%    |
| AMD + Nvidia   | 3        | 2.16%   |
| Other          | 2        | 1.44%   |
| 2 x AMD        | 1        | 0.72%   |
| 1 x ASPEED     | 1        | 0.72%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 97       | 69.29%  |
| Proprietary | 34       | 24.29%  |
| Unknown     | 9        | 6.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 68       | 47.55%  |
| 7.01-8.0   | 18       | 12.59%  |
| 0.51-1.0   | 16       | 11.19%  |
| 1.01-2.0   | 13       | 9.09%   |
| 3.01-4.0   | 9        | 6.29%   |
| 0.01-0.5   | 7        | 4.9%    |
| 5.01-6.0   | 6        | 4.2%    |
| 2.01-3.0   | 2        | 1.4%    |
| 8.01-16.0  | 2        | 1.4%    |
| 4.01-5.0   | 1        | 0.7%    |
| 16.01-24.0 | 1        | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 16       | 10.74%  |
| Goldstar             | 14       | 9.4%    |
| Dell                 | 14       | 9.4%    |
| AOC                  | 14       | 9.4%    |
| Philips              | 10       | 6.71%   |
| Ancor Communications | 8        | 5.37%   |
| Unknown              | 6        | 4.03%   |
| BenQ                 | 6        | 4.03%   |
| AMO                  | 6        | 4.03%   |
| Acer                 | 6        | 4.03%   |
| ViewSonic            | 5        | 3.36%   |
| ASUSTek Computer     | 5        | 3.36%   |
| Hewlett-Packard      | 4        | 2.68%   |
| Lenovo               | 3        | 2.01%   |
| IPS                  | 3        | 2.01%   |
| SKY                  | 2        | 1.34%   |
| RTK                  | 2        | 1.34%   |
| HSO                  | 2        | 1.34%   |
| AUS                  | 2        | 1.34%   |
| Xiaomi               | 1        | 0.67%   |
| Xiangye              | 1        | 0.67%   |
| Unknown (AAA)        | 1        | 0.67%   |
| Toshiba              | 1        | 0.67%   |
| TCT                  | 1        | 0.67%   |
| SKG                  | 1        | 0.67%   |
| SAC                  | 1        | 0.67%   |
| PDA                  | 1        | 0.67%   |
| PANDA                | 1        | 0.67%   |
| Mi                   | 1        | 0.67%   |
| LYC                  | 1        | 0.67%   |
| LG Electronics       | 1        | 0.67%   |
| HPN                  | 1        | 0.67%   |
| Hitachi              | 1        | 0.67%   |
| HDC                  | 1        | 0.67%   |
| GET                  | 1        | 0.67%   |
| GEN                  | 1        | 0.67%   |
| FST                  | 1        | 0.67%   |
| Founder              | 1        | 0.67%   |
| Eizo                 | 1        | 0.67%   |
| Unknown              | 1        | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| AMO HS241P AMO2800 3840x2160 620x350mm 28.0-inch                        | 4        | 2.6%    |
| Unknown LCD Monitor XMD Mi TV 1360x768                                  | 3        | 1.95%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 3        | 1.95%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch                 | 2        | 1.3%    |
| Lenovo LEN L24e-20 LEN65DF 1920x1080 527x296mm 23.8-inch                | 2        | 1.3%    |
| IPS LCD Monitor IPS2700 2560x1440 597x336mm 27.0-inch                   | 2        | 1.3%    |
| HSO B2431M HSO2431 3840x2160 520x290mm 23.4-inch                        | 2        | 1.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 2        | 1.3%    |
| AOC Q2790 AOC2790 2560x1440 597x336mm 27.0-inch                         | 2        | 1.3%    |
| Xiaomi Mi TV XMD004A 1920x1080 708x398mm 32.0-inch                      | 1        | 0.65%   |
| Xiangye XE2400 XYE2380 3840x2160 520x310mm 23.8-inch                    | 1        | 0.65%   |
| ViewSonic VX2260WM VSCFC21 1920x1080 477x268mm 21.5-inch                | 1        | 0.65%   |
| ViewSonic VX2239 SERIES VSC5225 1920x1080 480x270mm 21.7-inch           | 1        | 0.65%   |
| ViewSonic VG921m VSC301E 1280x1024 380x300mm 19.1-inch                  | 1        | 0.65%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch           | 1        | 0.65%   |
| ViewSonic VA1616wSERIES VSC0021 1366x768 348x197mm 15.7-inch            | 1        | 0.65%   |
| Unknown LCD Monitor hp f1523 1024x768                                   | 1        | 0.65%   |
| Unknown LCD Monitor GBT G32QC A 2560x1440                               | 1        | 0.65%   |
| Unknown LCD Monitor FST V22T-1R LED 1920x1080                           | 1        | 0.65%   |
| Unknown (AAA) U270 AAA2700 3840x2160 596x335mm 26.9-inch                | 1        | 0.65%   |
| Toshiba TV TSB2634 1920x1080 697x392mm 31.5-inch                        | 1        | 0.65%   |
| TCT DP1080P60 TCT0270 2560x1600 520x290mm 23.4-inch                     | 1        | 0.65%   |
| SKY TV MONITOR SKY0030 3840x2160 708x398mm 32.0-inch                    | 1        | 0.65%   |
| SKY M16U1 SKY0156 3840x2160 345x194mm 15.6-inch                         | 1        | 0.65%   |
| SKG PMO G270-CQK SKG2712 2560x1440 530x280mm 23.6-inch                  | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch    | 1        | 0.65%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 408x225mm 18.3-inch     | 1        | 0.65%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch       | 1        | 0.65%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 521x293mm 23.5-inch       | 1        | 0.65%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch       | 1        | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1        | 0.65%   |
| Samsung Electronics S22C650 SAM09DB 1920x1080 477x268mm 21.5-inch       | 1        | 0.65%   |
| Samsung Electronics S22C300 SAM0A1F 1920x1080 477x268mm 21.5-inch       | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM720D 3840x2160 1872x1053mm 84.6-inch | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 886x498mm 40.0-inch   | 1        | 0.65%   |
| Samsung Electronics LCD Monitor SAM03DD 1680x1050                       | 1        | 0.65%   |
| Samsung Electronics LCD Monitor S27B550 1920x1080                       | 1        | 0.65%   |
| Samsung Electronics LCD Monitor S24D300 3840x1080                       | 1        | 0.65%   |
| Samsung Electronics LCD Monitor S22F350 1920x1080                       | 1        | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 42.75%  |
| 3840x2160 (4K)     | 26       | 18.84%  |
| 2560x1440 (QHD)    | 12       | 8.7%    |
| 1440x900 (WXGA+)   | 7        | 5.07%   |
| 1680x1050 (WSXGA+) | 5        | 3.62%   |
| 1366x768 (WXGA)    | 5        | 3.62%   |
| Unknown            | 4        | 2.9%    |
| 3840x1080          | 3        | 2.17%   |
| 1360x768           | 3        | 2.17%   |
| 1280x1024 (SXGA)   | 3        | 2.17%   |
| 3440x1440          | 2        | 1.45%   |
| 2560x1600          | 2        | 1.45%   |
| 2560x1080          | 2        | 1.45%   |
| 1024x768 (XGA)     | 2        | 1.45%   |
| 5120x1440          | 1        | 0.72%   |
| 3200x1080          | 1        | 0.72%   |
| 1920x1200 (WUXGA)  | 1        | 0.72%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 22       | 15.28%  |
| 24      | 19       | 13.19%  |
| 27      | 18       | 12.5%   |
| 21      | 18       | 12.5%   |
| Unknown | 17       | 11.81%  |
| 31      | 9        | 6.25%   |
| 18      | 8        | 5.56%   |
| 28      | 5        | 3.47%   |
| 19      | 5        | 3.47%   |
| 40      | 3        | 2.08%   |
| 34      | 3        | 2.08%   |
| 22      | 3        | 2.08%   |
| 15      | 3        | 2.08%   |
| 84      | 2        | 1.39%   |
| 65      | 1        | 0.69%   |
| 58      | 1        | 0.69%   |
| 57      | 1        | 0.69%   |
| 48      | 1        | 0.69%   |
| 32      | 1        | 0.69%   |
| 26      | 1        | 0.69%   |
| 25      | 1        | 0.69%   |
| 17      | 1        | 0.69%   |
| 16      | 1        | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 39.86%  |
| 401-500     | 32       | 23.19%  |
| Unknown     | 17       | 12.32%  |
| 601-700     | 15       | 10.87%  |
| 701-800     | 5        | 3.62%   |
| 301-350     | 5        | 3.62%   |
| 801-900     | 3        | 2.17%   |
| 1001-1500   | 3        | 2.17%   |
| 1501-2000   | 2        | 1.45%   |
| 351-400     | 1        | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 89       | 68.46%  |
| 16/10   | 16       | 12.31%  |
| Unknown | 16       | 12.31%  |
| 21/9    | 3        | 2.31%   |
| 6/5     | 2        | 1.54%   |
| 5/4     | 1        | 0.77%   |
| 4/3     | 1        | 0.77%   |
| 32/9    | 1        | 0.77%   |
| 0.56    | 1        | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 51       | 36.69%  |
| 301-350        | 24       | 17.27%  |
| Unknown        | 17       | 12.23%  |
| 351-500        | 13       | 9.35%   |
| 151-200        | 11       | 7.91%   |
| More than 1000 | 5        | 3.6%    |
| 251-300        | 5        | 3.6%    |
| 141-150        | 5        | 3.6%    |
| 501-1000       | 4        | 2.88%   |
| 101-110        | 3        | 2.16%   |
| 131-140        | 1        | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 74       | 53.62%  |
| 101-120       | 30       | 21.74%  |
| Unknown       | 17       | 12.32%  |
| 161-240       | 8        | 5.8%    |
| 1-50          | 4        | 2.9%    |
| 121-160       | 4        | 2.9%    |
| More than 240 | 1        | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 107      | 77.54%  |
| 2     | 21       | 15.22%  |
| 0     | 9        | 6.52%   |
| 3     | 1        | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 78       | 40%     |
| Intel                                  | 76       | 38.97%  |
| TP-Link                                | 8        | 4.1%    |
| Broadcom                               | 7        | 3.59%   |
| Qualcomm Atheros                       | 6        | 3.08%   |
| Ralink Technology                      | 4        | 2.05%   |
| Microsoft                              | 3        | 1.54%   |
| MediaTek                               | 3        | 1.54%   |
| Xiaomi                                 | 1        | 0.51%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.51%   |
| SEGGER                                 | 1        | 0.51%   |
| Samsung Electronics                    | 1        | 0.51%   |
| PEAK-System Technik                    | 1        | 0.51%   |
| Nvidia                                 | 1        | 0.51%   |
| National Semiconductor                 | 1        | 0.51%   |
| D-Link                                 | 1        | 0.51%   |
| Belkin Components                      | 1        | 0.51%   |
| Aquantia                               | 1        | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61       | 25.63%  |
| Intel Wi-Fi 6 AX200                                               | 14       | 5.88%   |
| Intel I211 Gigabit Network Connection                             | 11       | 4.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 4.2%    |
| Intel Ethernet Connection (2) I219-V                              | 7        | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 2.94%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 6        | 2.52%   |
| Intel Ethernet Controller I225-V                                  | 5        | 2.1%    |
| Intel Ethernet Connection I217-LM                                 | 5        | 2.1%    |
| Microsoft Xbox Wireless Adapter for Windows                       | 3        | 1.26%   |
| Intel Wireless 7260                                               | 3        | 1.26%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 1.26%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.26%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2        | 0.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.84%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2        | 0.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.84%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 2        | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 0.84%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 0.84%   |
| Realtek 802.11ac NIC                                              | 2        | 0.84%   |
| Ralink RT5370 Wireless Adapter                                    | 2        | 0.84%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.84%   |
| Intel Wireless-AC 9260                                            | 2        | 0.84%   |
| Intel Wireless 8265 / 8275                                        | 2        | 0.84%   |
| Intel Wireless 7265                                               | 2        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.84%   |
| Intel Ethernet Connection I217-V                                  | 2        | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.84%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 47       | 56.63%  |
| Realtek Semiconductor | 11       | 13.25%  |
| TP-Link               | 8        | 9.64%   |
| Ralink Technology     | 4        | 4.82%   |
| Broadcom              | 4        | 4.82%   |
| Microsoft             | 3        | 3.61%   |
| MediaTek              | 3        | 3.61%   |
| Qualcomm Atheros      | 2        | 2.41%   |
| Belkin Components     | 1        | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 14       | 16.87%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 7        | 8.43%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 6        | 7.23%   |
| Microsoft Xbox Wireless Adapter for Windows                            | 3        | 3.61%   |
| Intel Wireless 7260                                                    | 3        | 3.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 3        | 3.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 2.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2        | 2.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 2.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 2        | 2.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 2        | 2.41%   |
| Realtek 802.11ac NIC                                                   | 2        | 2.41%   |
| Ralink RT5370 Wireless Adapter                                         | 2        | 2.41%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 2.41%   |
| Intel Wireless-AC 9260                                                 | 2        | 2.41%   |
| Intel Wireless 8265 / 8275                                             | 2        | 2.41%   |
| Intel Wireless 7265                                                    | 2        | 2.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 2        | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 2.41%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 2.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 1        | 1.2%    |
| TP-Link RTL8812AU Archer T4U 802.11ac                                  | 1        | 1.2%    |
| TP-Link Archer T4U ver.3                                               | 1        | 1.2%    |
| TP-Link 802.11n NIC                                                    | 1        | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.2%    |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)              | 1        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 1        | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 1        | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.2%    |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                     | 1        | 1.2%    |
| MediaTek 802.11 n WLAN                                                 | 1        | 1.2%    |
| Intel Wireless 3160                                                    | 1        | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 1        | 1.2%    |
| Intel Centrino Wireless-N 2230                                         | 1        | 1.2%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                          | 1        | 1.2%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 1        | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                          | 1        | 1.2%    |
| Belkin Components F5D8053 N Wireless USB Adapter v3000 [Ralink RT2870] | 1        | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 78       | 53.06%  |
| Intel                                  | 55       | 37.41%  |
| Qualcomm Atheros                       | 4        | 2.72%   |
| Broadcom                               | 3        | 2.04%   |
| Xiaomi                                 | 1        | 0.68%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.68%   |
| Samsung Electronics                    | 1        | 0.68%   |
| Nvidia                                 | 1        | 0.68%   |
| National Semiconductor                 | 1        | 0.68%   |
| D-Link                                 | 1        | 0.68%   |
| Aquantia                               | 1        | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61       | 39.87%  |
| Intel I211 Gigabit Network Connection                             | 11       | 7.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10       | 6.54%   |
| Intel Ethernet Connection (2) I219-V                              | 7        | 4.58%   |
| Intel Ethernet Controller I225-V                                  | 5        | 3.27%   |
| Intel Ethernet Connection I217-LM                                 | 5        | 3.27%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 1.96%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.96%   |
| Intel 82574L Gigabit Network Connection                           | 3        | 1.96%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 2        | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2        | 1.31%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2        | 1.31%   |
| Intel Ethernet Connection I217-V                                  | 2        | 1.31%   |
| Intel Ethernet Connection (7) I219-V                              | 2        | 1.31%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 1.31%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2        | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.65%   |
| Sony Ericsson Mobile AB XQ-CC54                                   | 1        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1        | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1        | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.65%   |
| Nvidia MCP65 Ethernet                                             | 1        | 0.65%   |
| National DP83815 (MacPhyter) Ethernet Controller                  | 1        | 0.65%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.65%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 1        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.65%   |
| Intel Ethernet Connection (2) I218-V                              | 1        | 0.65%   |
| Intel Ethernet Connection (17) I219-LM                            | 1        | 0.65%   |
| Intel Ethernet Connection (14) I219-V                             | 1        | 0.65%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.65%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.65%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.65%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1        | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.65%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1        | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 134      | 63.21%  |
| WiFi     | 76       | 35.85%  |
| Modem    | 1        | 0.47%   |
| Unknown  | 1        | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 115      | 76.16%  |
| WiFi     | 36       | 23.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 72       | 51.06%  |
| 2     | 57       | 40.43%  |
| 3     | 4        | 2.84%   |
| 0     | 4        | 2.84%   |
| 4     | 2        | 1.42%   |
| 8     | 1        | 0.71%   |
| 7     | 1        | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 134      | 96.4%   |
| Yes  | 5        | 3.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 45       | 61.64%  |
| Cambridge Silicon Radio         | 15       | 20.55%  |
| Broadcom                        | 3        | 4.11%   |
| Realtek Semiconductor           | 2        | 2.74%   |
| ASUSTek Computer                | 2        | 2.74%   |
| SINO WEALTH                     | 1        | 1.37%   |
| Qualcomm Atheros Communications | 1        | 1.37%   |
| Micro Star International        | 1        | 1.37%   |
| MediaTek                        | 1        | 1.37%   |
| Lite-On Technology              | 1        | 1.37%   |
| Apple                           | 1        | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15       | 20.55%  |
| Intel AX200 Bluetooth                               | 14       | 19.18%  |
| Intel Bluetooth wireless interface                  | 8        | 10.96%  |
| Intel Wireless-AC 3168 Bluetooth                    | 7        | 9.59%   |
| Intel AX201 Bluetooth                               | 7        | 9.59%   |
| Realtek Bluetooth Radio                             | 2        | 2.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 2.74%   |
| Intel Bluetooth Device                              | 2        | 2.74%   |
| Intel AX210 Bluetooth                               | 2        | 2.74%   |
| ASUS Bluetooth Radio                                | 2        | 2.74%   |
| SINO WEALTH RK Bluetooth Keyboar                    | 1        | 1.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 1.37%   |
| Micro Star International Bluetooth Dongle           | 1        | 1.37%   |
| MediaTek Wireless_Device                            | 1        | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1        | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 1.37%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1        | 1.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1        | 1.37%   |
| Broadcom Bluetooth Controller                       | 1        | 1.37%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle  | 1        | 1.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1        | 1.37%   |
| Apple Bluetooth Host Controller                     | 1        | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 99       | 43.42%  |
| Nvidia                               | 60       | 26.32%  |
| AMD                                  | 45       | 19.74%  |
| C-Media Electronics                  | 8        | 3.51%   |
| Focusrite-Novation                   | 2        | 0.88%   |
| FiiO Electronics Technology          | 2        | 0.88%   |
| Creative Labs                        | 2        | 0.88%   |
| XMOS                                 | 1        | 0.44%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.44%   |
| Texas Instruments                    | 1        | 0.44%   |
| Sony                                 | 1        | 0.44%   |
| SAVITECH                             | 1        | 0.44%   |
| Micro Star International             | 1        | 0.44%   |
| Lynx                                 | 1        | 0.44%   |
| Logitech                             | 1        | 0.44%   |
| JMTek                                | 1        | 0.44%   |
| AudioQuest                           | 1        | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 15       | 5.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12       | 4.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 12       | 4.48%   |
| Intel Alder Lake-S HD Audio Controller                                     | 11       | 4.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 10       | 3.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8        | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8        | 2.99%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 2.61%   |
| Intel 200 Series PCH HD Audio                                              | 7        | 2.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 2.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 6        | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6        | 2.24%   |
| AMD Family 17h/19h HD Audio Controller                                     | 6        | 2.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 1.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 5        | 1.87%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5        | 1.87%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5        | 1.87%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5        | 1.87%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.49%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 1.49%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4        | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.49%   |
| AMD Navi 10 HDMI Audio                                                     | 4        | 1.49%   |
| Nvidia TU104 HD Audio Controller                                           | 3        | 1.12%   |
| Nvidia GP108 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3        | 1.12%   |
| Nvidia GP104 High Definition Audio Controller                              | 3        | 1.12%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.12%   |
| Intel Sunrise Point-LP HD Audio                                            | 3        | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 3        | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3        | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 3        | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3        | 1.12%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.75%   |
| Nvidia GF106 High Definition Audio Controller                              | 2        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2        | 0.75%   |
| Intel HD Graphics SGPC                                                     | 2        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 22       | 26.19%  |
| Corsair             | 12       | 14.29%  |
| A-DATA Technology   | 9        | 10.71%  |
| Samsung Electronics | 7        | 8.33%   |
| SK hynix            | 5        | 5.95%   |
| Unknown             | 4        | 4.76%   |
| G.Skill             | 4        | 4.76%   |
| Crucial             | 4        | 4.76%   |
| Team                | 3        | 3.57%   |
| Micron Technology   | 3        | 3.57%   |
| Ramaxel Technology  | 2        | 2.38%   |
| Unknown (0x0AFD)    | 1        | 1.19%   |
| Transcend           | 1        | 1.19%   |
| Nanya Technology    | 1        | 1.19%   |
| Kingmax             | 1        | 1.19%   |
| Juhor               | 1        | 1.19%   |
| GLOWAY              | 1        | 1.19%   |
| Essencore Limited   | 1        | 1.19%   |
| Apacer              | 1        | 1.19%   |
| Unknown             | 1        | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s      | 2        | 2.2%    |
| Kingston RAM KY7N41-MIE 8GB DIMM DDR4 2666MT/s            | 2        | 2.2%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s       | 2        | 2.2%    |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s     | 2        | 2.2%    |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s  | 2        | 2.2%    |
| Corsair RAM CM4X16GC3600C18K2D 16GB DIMM DDR4 3600MT/s    | 2        | 2.2%    |
| A-DATA RAM Module 4GB DIMM DDR3 1333MT/s                  | 2        | 2.2%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 1        | 1.1%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR2 800MT/s               | 1        | 1.1%    |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 1        | 1.1%    |
| Unknown (0x0AFD) RAM SED2666U1932 32GB DIMM DDR4 2667MT/s | 1        | 1.1%    |
| Transcend RAM TS256MLQ72V6U 2GB DIMM DDR2 667MT/s         | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s        | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s        | 1        | 1.1%    |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s        | 1        | 1.1%    |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 1        | 1.1%    |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                | 1        | 1.1%    |
| SK hynix RAM HMCG66MEBUA084N 8GB DIMM DDR5 4800MT/s       | 1        | 1.1%    |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1        | 1.1%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 1        | 1.1%    |
| Samsung RAM M471B1G73DH0-YK0 8GB SODIMM DDR3 1600MT/s     | 1        | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 1        | 1.1%    |
| Samsung RAM M471A1G43EB1-CPB 8GB SODIMM DDR4 2133MT/s     | 1        | 1.1%    |
| Samsung RAM M378B5773DH0-CK0 2GB DIMM DDR3 1600MT/s       | 1        | 1.1%    |
| Samsung RAM M378B5773CH0-CK0 2048MB DIMM DDR3 1600MT/s    | 1        | 1.1%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.1%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.1%    |
| Samsung RAM M323R2GA3BB0-CQKOD 16GB DIMM 4800MT/s         | 1        | 1.1%    |
| Ramaxel RAM RMR5040MM58F9F1600 4096MB DIMM DDR3 1600MT/s  | 1        | 1.1%    |
| Ramaxel RAM RMR1870ED48E8F1333 2048MB DIMM DDR3 1333MT/s  | 1        | 1.1%    |
| Nanya RAM NT2GC64B88G0NF-DI 2GB DIMM DDR3 1600MT/s        | 1        | 1.1%    |
| Micron RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s     | 1        | 1.1%    |
| Micron RAM 4ATF1G64AZ-3G2E1 8GB DIMM DDR4 3200MT/s        | 1        | 1.1%    |
| Micron RAM 16ATF4G64AZ-3G2F1 32GB DIMM DDR4 3200MT/s      | 1        | 1.1%    |
| Kingston RAM KP223C-ELD 2GB DIMM DDR3 1600MT/s            | 1        | 1.1%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 1        | 1.1%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s       | 1        | 1.1%    |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s          | 1        | 1.1%    |
| Kingston RAM HX426C16FB/8 8GB DIMM DDR4 2667MT/s          | 1        | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 50       | 64.1%   |
| DDR3    | 19       | 24.36%  |
| DDR5    | 3        | 3.85%   |
| SDRAM   | 2        | 2.56%   |
| DDR2    | 2        | 2.56%   |
| Unknown | 2        | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 70       | 89.74%  |
| SODIMM | 8        | 10.26%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 27       | 32.93%  |
| 16384 | 23       | 28.05%  |
| 4096  | 15       | 18.29%  |
| 32768 | 9        | 10.98%  |
| 2048  | 7        | 8.54%   |
| 1024  | 1        | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3200  | 13       | 15.85%  |
| 2667  | 11       | 13.41%  |
| 1600  | 11       | 13.41%  |
| 3600  | 7        | 8.54%   |
| 1333  | 7        | 8.54%   |
| 2400  | 6        | 7.32%   |
| 3000  | 4        | 4.88%   |
| 2133  | 4        | 4.88%   |
| 4800  | 3        | 3.66%   |
| 3466  | 3        | 3.66%   |
| 2666  | 3        | 3.66%   |
| 800   | 2        | 2.44%   |
| 5808  | 1        | 1.22%   |
| 4199  | 1        | 1.22%   |
| 3866  | 1        | 1.22%   |
| 3800  | 1        | 1.22%   |
| 3007  | 1        | 1.22%   |
| 1866  | 1        | 1.22%   |
| 1800  | 1        | 1.22%   |
| 667   | 1        | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Hewlett-Packard    | 1        | 25%     |
| Fuji Xerox         | 1        | 25%     |
| Canon              | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| HP LaserJet P2035           | 1        | 25%     |
| Fuji Xerox DocuPrint P158 b | 1        | 25%     |
| Canon MP160                 | 1        | 25%     |
| Brother HL-L2320D series    | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Mustek Systems | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 8        | 40%     |
| Microdia                      | 2        | 10%     |
| Z-Star Microelectronics       | 1        | 5%      |
| Sunplus Innovation Technology | 1        | 5%      |
| SN0002                        | 1        | 5%      |
| Nokia Mobile Phones           | 1        | 5%      |
| Google                        | 1        | 5%      |
| Essential Products            | 1        | 5%      |
| eMPIA Technology              | 1        | 5%      |
| Cubeternet                    | 1        | 5%      |
| ARC International             | 1        | 5%      |
| A4Tech                        | 1        | 5%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 4        | 19.05%  |
| Logitech B525 HD Webcam                 | 2        | 9.52%   |
| Z-Star Sirius USB2.0 Camera             | 1        | 4.76%   |
| Sunplus SPCA2650 PC Camera              | 1        | 4.76%   |
| SN0002 2K USB Camera                    | 1        | 4.76%   |
| Nokia Mobile Phones Lumia 640 Phone     | 1        | 4.76%   |
| Microdia USB 2.0 Camera                 | 1        | 4.76%   |
| Microdia HP Integrated Webcam           | 1        | 4.76%   |
| Logitech C920 PRO HD Webcam             | 1        | 4.76%   |
| Logitech BRIO Ultra HD Webcam           | 1        | 4.76%   |
| Google Nexus/Pixel Device (PTP + debug) | 1        | 4.76%   |
| Google Nexus/Pixel Device (MTP + debug) | 1        | 4.76%   |
| Essential Products PH-1                 | 1        | 4.76%   |
| eMPIA M035 Compact Web Cam              | 1        | 4.76%   |
| Cubeternet GL-UPC822 UVC WebCam         | 1        | 4.76%   |
| ARC International Camera                | 1        | 4.76%   |
| A4Tech FHD 1080P PC Camera              | 1        | 4.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Advanced Card Systems | 2        | 66.67%  |
| Yubico.com            | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Advanced Card Systems ACR1281 1S Dual Reader | 2        | 66.67%  |
| Yubico.com Yubikey 4 U2F+CCID                | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 113      | 78.47%  |
| 1     | 25       | 17.36%  |
| 2     | 4        | 2.78%   |
| 4     | 2        | 1.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 13       | 32.5%   |
| Graphics card            | 11       | 27.5%   |
| Communication controller | 7        | 17.5%   |
| Unassigned class         | 2        | 5%      |
| Chipcard                 | 2        | 5%      |
| Storage/ata              | 1        | 2.5%    |
| Sound                    | 1        | 2.5%    |
| Net/ethernet             | 1        | 2.5%    |
| Camera                   | 1        | 2.5%    |
| Bluetooth                | 1        | 2.5%    |

