openSUSE - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

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

Total: 2363

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a4ed7efef9](https://linux-hardware.org/?probe=a4ed7efef9) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5eebfea632](https://linux-hardware.org/?probe=5eebfea632) | Dec 01, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [961f58c143](https://linux-hardware.org/?probe=961f58c143) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0461e6b5d2](https://linux-hardware.org/?probe=0461e6b5d2) | Dec 01, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [4951da34da](https://linux-hardware.org/?probe=4951da34da) | Nov 30, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [a41d7dbfb1](https://linux-hardware.org/?probe=a41d7dbfb1) | Nov 29, 2022 |
| VA_IP3        | GMLR_V1                     | Mini pc     | [ac6676f125](https://linux-hardware.org/?probe=ac6676f125) | Nov 29, 2022 |
| Supermicro    | X8DTG-D                     | Server      | [9e977b651e](https://linux-hardware.org/?probe=9e977b651e) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [944ade9560](https://linux-hardware.org/?probe=944ade9560) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [cc1637d7e2](https://linux-hardware.org/?probe=cc1637d7e2) | Nov 27, 2022 |
| Lenovo        | ThinkPad X260 20F6005HUS    | Notebook    | [6418eda1a9](https://linux-hardware.org/?probe=6418eda1a9) | Nov 27, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [a034af6b70](https://linux-hardware.org/?probe=a034af6b70) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [ed2e9cfb4f](https://linux-hardware.org/?probe=ed2e9cfb4f) | Nov 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| HP            | 212B                        | Desktop     | [3ac96bbb45](https://linux-hardware.org/?probe=3ac96bbb45) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| Dell          | Latitude 5401               | Notebook    | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Timi          | TM1612                      | Notebook    | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [be2c23e33c](https://linux-hardware.org/?probe=be2c23e33c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [8b8ac358e4](https://linux-hardware.org/?probe=8b8ac358e4) | Nov 21, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [2890235d49](https://linux-hardware.org/?probe=2890235d49) | Nov 21, 2022 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [d9a74ee60a](https://linux-hardware.org/?probe=d9a74ee60a) | Nov 20, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [4f3c7d5501](https://linux-hardware.org/?probe=4f3c7d5501) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [05c9ad6f4a](https://linux-hardware.org/?probe=05c9ad6f4a) | Nov 19, 2022 |
| Dell          | Latitude 5414               | Notebook    | [a408bec327](https://linux-hardware.org/?probe=a408bec327) | Nov 18, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| HP            | 8055                        | Desktop     | [4195a9765a](https://linux-hardware.org/?probe=4195a9765a) | Nov 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [b678f31b24](https://linux-hardware.org/?probe=b678f31b24) | Nov 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [371368cfe7](https://linux-hardware.org/?probe=371368cfe7) | Nov 16, 2022 |
| HP            | Compaq 6830s                | Notebook    | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | Notebook    | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [3b6d611387](https://linux-hardware.org/?probe=3b6d611387) | Nov 14, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [3eb034e033](https://linux-hardware.org/?probe=3eb034e033) | Nov 13, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [18b42b8ead](https://linux-hardware.org/?probe=18b42b8ead) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b2dbd8f602](https://linux-hardware.org/?probe=b2dbd8f602) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59a0a26e78](https://linux-hardware.org/?probe=59a0a26e78) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59d3c93814](https://linux-hardware.org/?probe=59d3c93814) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dc0e46c7b3](https://linux-hardware.org/?probe=dc0e46c7b3) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [75f7a51f9e](https://linux-hardware.org/?probe=75f7a51f9e) | Nov 12, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Lenovo        | ThinkPad T530 2394D56       | Notebook    | [3d44b768e5](https://linux-hardware.org/?probe=3d44b768e5) | Nov 12, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [4e0b0368b8](https://linux-hardware.org/?probe=4e0b0368b8) | Nov 12, 2022 |
| Samsung       | 730QDA                      | Convertible | [a7a2ca6941](https://linux-hardware.org/?probe=a7a2ca6941) | Nov 12, 2022 |
| Toshiba       | IS 1422+                    | Notebook    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [13286af46e](https://linux-hardware.org/?probe=13286af46e) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| HP            | ZBook 17                    | Notebook    | [e866fa1319](https://linux-hardware.org/?probe=e866fa1319) | Nov 09, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [776a9bc0b6](https://linux-hardware.org/?probe=776a9bc0b6) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [be071c7456](https://linux-hardware.org/?probe=be071c7456) | Nov 08, 2022 |
| HP            | ZBook 17                    | Notebook    | [af26e94623](https://linux-hardware.org/?probe=af26e94623) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e13f29fc81](https://linux-hardware.org/?probe=e13f29fc81) | Nov 07, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [912bfcc57e](https://linux-hardware.org/?probe=912bfcc57e) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [0f119b6000](https://linux-hardware.org/?probe=0f119b6000) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [e872fcb5f7](https://linux-hardware.org/?probe=e872fcb5f7) | Nov 06, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b5470f4f19](https://linux-hardware.org/?probe=b5470f4f19) | Nov 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [ec3bc58f50](https://linux-hardware.org/?probe=ec3bc58f50) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c177c82021](https://linux-hardware.org/?probe=c177c82021) | Nov 05, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [99e32a37ff](https://linux-hardware.org/?probe=99e32a37ff) | Nov 04, 2022 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [2d2c00b163](https://linux-hardware.org/?probe=2d2c00b163) | Nov 04, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [011d776675](https://linux-hardware.org/?probe=011d776675) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [7255a61579](https://linux-hardware.org/?probe=7255a61579) | Nov 03, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b3613b84ad](https://linux-hardware.org/?probe=b3613b84ad) | Nov 02, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [40cedc7d2c](https://linux-hardware.org/?probe=40cedc7d2c) | Nov 02, 2022 |
| HP            | 829B                        | All in one  | [23122cba32](https://linux-hardware.org/?probe=23122cba32) | Nov 01, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0131299a9e](https://linux-hardware.org/?probe=0131299a9e) | Nov 01, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | Notebook    | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [453d856b8d](https://linux-hardware.org/?probe=453d856b8d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| Dell          | Latitude E6430              | Notebook    | [cb4eb1f556](https://linux-hardware.org/?probe=cb4eb1f556) | Oct 28, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Radxa         | Zero                        | Soc         | [e35d41a9a6](https://linux-hardware.org/?probe=e35d41a9a6) | Oct 27, 2022 |
| Dell          | Latitude 9420               | Notebook    | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| MSI           | X58 Pro                     | Desktop     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5fa9b60268](https://linux-hardware.org/?probe=5fa9b60268) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [3a60ac01f4](https://linux-hardware.org/?probe=3a60ac01f4) | Oct 23, 2022 |
| MSI           | X58 Pro                     | Desktop     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [fbc271b648](https://linux-hardware.org/?probe=fbc271b648) | Oct 22, 2022 |
| Lenovo        | 3111 NOK                    | Desktop     | [185e1ca963](https://linux-hardware.org/?probe=185e1ca963) | Oct 21, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [4c699ac628](https://linux-hardware.org/?probe=4c699ac628) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| HP            | ZBook 17                    | Notebook    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| Sony          | VPCEL3S1R                   | Notebook    | [5c37559c2d](https://linux-hardware.org/?probe=5c37559c2d) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [a078a2f2ae](https://linux-hardware.org/?probe=a078a2f2ae) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [e4769fb9e0](https://linux-hardware.org/?probe=e4769fb9e0) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [76bb60e5ee](https://linux-hardware.org/?probe=76bb60e5ee) | Oct 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [79c4c3b21f](https://linux-hardware.org/?probe=79c4c3b21f) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [b11fa8e1dd](https://linux-hardware.org/?probe=b11fa8e1dd) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI           | Prestige 14 A11SCS          | Notebook    | [e552920463](https://linux-hardware.org/?probe=e552920463) | Oct 13, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61eb97192e](https://linux-hardware.org/?probe=61eb97192e) | Oct 12, 2022 |
| Toshiba       | Satellite P55t-A            | Notebook    | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| Lenovo        | ThinkPad T430 2347DS3       | Notebook    | [970542656e](https://linux-hardware.org/?probe=970542656e) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| Gateway       | NV54 Series                 | Notebook    | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7d71e688f4](https://linux-hardware.org/?probe=7d71e688f4) | Oct 08, 2022 |
| ASUSTek       | F3Sv                        | Notebook    | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [b8f7c25d91](https://linux-hardware.org/?probe=b8f7c25d91) | Oct 07, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [9ef16d569e](https://linux-hardware.org/?probe=9ef16d569e) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Acer          | S50-54                      | Notebook    | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| Dell          | Latitude 3340               | Notebook    | [100b89b0a9](https://linux-hardware.org/?probe=100b89b0a9) | Oct 04, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [daec61299a](https://linux-hardware.org/?probe=daec61299a) | Oct 03, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Acer          | S50-54                      | Notebook    | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [9121550ca1](https://linux-hardware.org/?probe=9121550ca1) | Oct 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6e3b616977](https://linux-hardware.org/?probe=6e3b616977) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bf657c61f5](https://linux-hardware.org/?probe=bf657c61f5) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c82f3311d](https://linux-hardware.org/?probe=2c82f3311d) | Sep 28, 2022 |
| Dell          | Latitude E5250              | Notebook    | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [911a73323d](https://linux-hardware.org/?probe=911a73323d) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd63352b24](https://linux-hardware.org/?probe=fd63352b24) | Sep 24, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| Timi          | A35S                        | Notebook    | [a57a688f31](https://linux-hardware.org/?probe=a57a688f31) | Sep 21, 2022 |
| Dell          | Latitude 7400               | Notebook    | [466bd310ef](https://linux-hardware.org/?probe=466bd310ef) | Sep 21, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ed6f75ec9f](https://linux-hardware.org/?probe=ed6f75ec9f) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [167d69530f](https://linux-hardware.org/?probe=167d69530f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d3b972d870](https://linux-hardware.org/?probe=d3b972d870) | Sep 19, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [959330d9c1](https://linux-hardware.org/?probe=959330d9c1) | Sep 19, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [2daced0309](https://linux-hardware.org/?probe=2daced0309) | Sep 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [42f1c1aee1](https://linux-hardware.org/?probe=42f1c1aee1) | Sep 17, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c0e411a96d](https://linux-hardware.org/?probe=c0e411a96d) | Sep 13, 2022 |
| MSI           | X58 Pro                     | Desktop     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6d70631176](https://linux-hardware.org/?probe=6d70631176) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [921b9580f4](https://linux-hardware.org/?probe=921b9580f4) | Sep 09, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| MSI           | P67A-C45                    | Desktop     | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [068c169aa0](https://linux-hardware.org/?probe=068c169aa0) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [312e65fd07](https://linux-hardware.org/?probe=312e65fd07) | Sep 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8c4261ac4f](https://linux-hardware.org/?probe=8c4261ac4f) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ede97805ec](https://linux-hardware.org/?probe=ede97805ec) | Sep 02, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e5ae0e72ca](https://linux-hardware.org/?probe=e5ae0e72ca) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2615743a16](https://linux-hardware.org/?probe=2615743a16) | Sep 02, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| HP            | ZBook 17                    | Notebook    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| Google        | Eldrid                      | Notebook    | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [0a454665e0](https://linux-hardware.org/?probe=0a454665e0) | Aug 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| HP            | 802F                        | Desktop     | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP            | 802F                        | Desktop     | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [57727c2af7](https://linux-hardware.org/?probe=57727c2af7) | Aug 23, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [a9f2cced08](https://linux-hardware.org/?probe=a9f2cced08) | Aug 22, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [9590ddbb06](https://linux-hardware.org/?probe=9590ddbb06) | Aug 22, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c956ba84ed](https://linux-hardware.org/?probe=c956ba84ed) | Aug 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [68fa656563](https://linux-hardware.org/?probe=68fa656563) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [20a816d976](https://linux-hardware.org/?probe=20a816d976) | Aug 21, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [b0579e2127](https://linux-hardware.org/?probe=b0579e2127) | Aug 19, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [8620d444d4](https://linux-hardware.org/?probe=8620d444d4) | Aug 19, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5893f7215e](https://linux-hardware.org/?probe=5893f7215e) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [1ef086a230](https://linux-hardware.org/?probe=1ef086a230) | Aug 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [fd64b105a4](https://linux-hardware.org/?probe=fd64b105a4) | Aug 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [73f2db9159](https://linux-hardware.org/?probe=73f2db9159) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [36a169c447](https://linux-hardware.org/?probe=36a169c447) | Aug 11, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [42f35776a6](https://linux-hardware.org/?probe=42f35776a6) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0aada24b1e](https://linux-hardware.org/?probe=0aada24b1e) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [37f87e94fc](https://linux-hardware.org/?probe=37f87e94fc) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [904bd1db44](https://linux-hardware.org/?probe=904bd1db44) | Aug 06, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e2f0ef440](https://linux-hardware.org/?probe=2e2f0ef440) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [80007c0939](https://linux-hardware.org/?probe=80007c0939) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [abe955b96f](https://linux-hardware.org/?probe=abe955b96f) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [8ffda4cfe7](https://linux-hardware.org/?probe=8ffda4cfe7) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [24fa962b0b](https://linux-hardware.org/?probe=24fa962b0b) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [af32973765](https://linux-hardware.org/?probe=af32973765) | Jul 26, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [7f2dde6f76](https://linux-hardware.org/?probe=7f2dde6f76) | Jul 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b874a0aa8e](https://linux-hardware.org/?probe=b874a0aa8e) | Jul 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| HP            | 8715                        | Mini pc     | [75c873bb8e](https://linux-hardware.org/?probe=75c873bb8e) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Biostar       | B450MH                      | Desktop     | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | Desktop     | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [5a6d4e8ba4](https://linux-hardware.org/?probe=5a6d4e8ba4) | Jul 21, 2022 |
| HP            | 158B                        | Desktop     | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b128b9e7a](https://linux-hardware.org/?probe=7b128b9e7a) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [03d7fde009](https://linux-hardware.org/?probe=03d7fde009) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge 0328A11       | Notebook    | [4305889043](https://linux-hardware.org/?probe=4305889043) | Jul 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [084f1e11d2](https://linux-hardware.org/?probe=084f1e11d2) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [b6d23c8307](https://linux-hardware.org/?probe=b6d23c8307) | Jul 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| HP            | 829E                        | Mini pc     | [27c2c68afb](https://linux-hardware.org/?probe=27c2c68afb) | Jul 13, 2022 |
| Jumper        | EZbook                      | Notebook    | [2515427610](https://linux-hardware.org/?probe=2515427610) | Jul 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ef6695e9f9](https://linux-hardware.org/?probe=ef6695e9f9) | Jul 12, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [fdae528732](https://linux-hardware.org/?probe=fdae528732) | Jul 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ddd990405d](https://linux-hardware.org/?probe=ddd990405d) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| ASUSTek       | P5Q3                        | Desktop     | [5fb3e2b502](https://linux-hardware.org/?probe=5fb3e2b502) | Jul 10, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c29a7cd884](https://linux-hardware.org/?probe=c29a7cd884) | Jul 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42cc0cf38e](https://linux-hardware.org/?probe=42cc0cf38e) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [1e39d0bba8](https://linux-hardware.org/?probe=1e39d0bba8) | Jul 06, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [2311c99a80](https://linux-hardware.org/?probe=2311c99a80) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [6512ee623f](https://linux-hardware.org/?probe=6512ee623f) | Jul 05, 2022 |
| Multilaser    | PC150                       | Notebook    | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6cbbc0b707](https://linux-hardware.org/?probe=6cbbc0b707) | Jul 03, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [80fbf3aee4](https://linux-hardware.org/?probe=80fbf3aee4) | Jul 02, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [153a698b74](https://linux-hardware.org/?probe=153a698b74) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [97dfd06a92](https://linux-hardware.org/?probe=97dfd06a92) | Jul 01, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [e46c1314b2](https://linux-hardware.org/?probe=e46c1314b2) | Jul 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [bec2a7697f](https://linux-hardware.org/?probe=bec2a7697f) | Jun 30, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [bde570c9f5](https://linux-hardware.org/?probe=bde570c9f5) | Jun 30, 2022 |
| HP            | ENVY TS 17                  | Notebook    | [7b5d021513](https://linux-hardware.org/?probe=7b5d021513) | Jun 29, 2022 |
| Framework     | Laptop                      | Notebook    | [d4cd42f3af](https://linux-hardware.org/?probe=d4cd42f3af) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a9ddf668c4](https://linux-hardware.org/?probe=a9ddf668c4) | Jun 28, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [2fac0d5ea2](https://linux-hardware.org/?probe=2fac0d5ea2) | Jun 28, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [2818c11c12](https://linux-hardware.org/?probe=2818c11c12) | Jun 28, 2022 |
| Dell          | 0J3C2F A03                  | Desktop     | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [e272328867](https://linux-hardware.org/?probe=e272328867) | Jun 26, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8d5e06f168](https://linux-hardware.org/?probe=8d5e06f168) | Jun 26, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [9a39e5ea0d](https://linux-hardware.org/?probe=9a39e5ea0d) | Jun 26, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [78a37e2d4c](https://linux-hardware.org/?probe=78a37e2d4c) | Jun 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f1b7197958](https://linux-hardware.org/?probe=f1b7197958) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [a00111330b](https://linux-hardware.org/?probe=a00111330b) | Jun 24, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [c3c9ce7e40](https://linux-hardware.org/?probe=c3c9ce7e40) | Jun 23, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [1d719d4b2d](https://linux-hardware.org/?probe=1d719d4b2d) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [9a2d492e07](https://linux-hardware.org/?probe=9a2d492e07) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f51215fa91](https://linux-hardware.org/?probe=f51215fa91) | Jun 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc0719c813](https://linux-hardware.org/?probe=cc0719c813) | Jun 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [52276b3971](https://linux-hardware.org/?probe=52276b3971) | Jun 16, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [74770880f9](https://linux-hardware.org/?probe=74770880f9) | Jun 15, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [f14133e69e](https://linux-hardware.org/?probe=f14133e69e) | Jun 14, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [1908660d1a](https://linux-hardware.org/?probe=1908660d1a) | Jun 13, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bde09cf3b5](https://linux-hardware.org/?probe=bde09cf3b5) | Jun 13, 2022 |
| MSI           | Raider GE76 12UH            | Notebook    | [c29e79e22d](https://linux-hardware.org/?probe=c29e79e22d) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | Notebook    | [02e4c63249](https://linux-hardware.org/?probe=02e4c63249) | Jun 12, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a1069bbb9d](https://linux-hardware.org/?probe=a1069bbb9d) | Jun 12, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | 2129                        | Desktop     | [1e716f8086](https://linux-hardware.org/?probe=1e716f8086) | Jun 12, 2022 |
| HP            | 2129                        | Desktop     | [ad6f94da2e](https://linux-hardware.org/?probe=ad6f94da2e) | Jun 11, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bca7de0216](https://linux-hardware.org/?probe=bca7de0216) | Jun 11, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| HP            | 87C3                        | Desktop     | [1383f85e70](https://linux-hardware.org/?probe=1383f85e70) | Jun 09, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [06e496124a](https://linux-hardware.org/?probe=06e496124a) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [fd421da52b](https://linux-hardware.org/?probe=fd421da52b) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [0970e891ee](https://linux-hardware.org/?probe=0970e891ee) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [3b33a1b625](https://linux-hardware.org/?probe=3b33a1b625) | Jun 07, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [325cde32e5](https://linux-hardware.org/?probe=325cde32e5) | Jun 06, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [6abee365c1](https://linux-hardware.org/?probe=6abee365c1) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f496dbb19](https://linux-hardware.org/?probe=8f496dbb19) | Jun 06, 2022 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [5a7eff8826](https://linux-hardware.org/?probe=5a7eff8826) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [fab0ffc01e](https://linux-hardware.org/?probe=fab0ffc01e) | Jun 03, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [c50bbae3e1](https://linux-hardware.org/?probe=c50bbae3e1) | Jun 02, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [9b84f171eb](https://linux-hardware.org/?probe=9b84f171eb) | Jun 01, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [11882c80d6](https://linux-hardware.org/?probe=11882c80d6) | May 30, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7fe5175e37](https://linux-hardware.org/?probe=7fe5175e37) | May 30, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| Dell          | Latitude 7320               | Notebook    | [63c6f252ab](https://linux-hardware.org/?probe=63c6f252ab) | May 30, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [7167a72758](https://linux-hardware.org/?probe=7167a72758) | May 30, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [91508b9375](https://linux-hardware.org/?probe=91508b9375) | May 29, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [e2e854cde1](https://linux-hardware.org/?probe=e2e854cde1) | May 28, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b9f38d3572](https://linux-hardware.org/?probe=b9f38d3572) | May 28, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [640f9226a1](https://linux-hardware.org/?probe=640f9226a1) | May 26, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8dcce6eadb](https://linux-hardware.org/?probe=8dcce6eadb) | May 24, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [401023c3b3](https://linux-hardware.org/?probe=401023c3b3) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0fe6809527](https://linux-hardware.org/?probe=0fe6809527) | May 20, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [54f43d3430](https://linux-hardware.org/?probe=54f43d3430) | May 20, 2022 |
| HP            | 8591                        | Desktop     | [60c5d4f8ca](https://linux-hardware.org/?probe=60c5d4f8ca) | May 19, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [2864dc6f0a](https://linux-hardware.org/?probe=2864dc6f0a) | May 19, 2022 |
| HP            | 2820h                       | Desktop     | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [c32e65738e](https://linux-hardware.org/?probe=c32e65738e) | May 18, 2022 |
| HP            | 8591                        | Desktop     | [fd05ae27e7](https://linux-hardware.org/?probe=fd05ae27e7) | May 18, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1575ec23a](https://linux-hardware.org/?probe=d1575ec23a) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | 81B7 1001                   | All in one  | [d99babe70f](https://linux-hardware.org/?probe=d99babe70f) | May 15, 2022 |
| Dell          | 03V7GF A00                  | Desktop     | [1be2673e23](https://linux-hardware.org/?probe=1be2673e23) | May 14, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e01bfd360d](https://linux-hardware.org/?probe=e01bfd360d) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [07e54c3c41](https://linux-hardware.org/?probe=07e54c3c41) | May 12, 2022 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [2e8f888ca3](https://linux-hardware.org/?probe=2e8f888ca3) | May 11, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | Notebook    | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Positivo      | DA18HV1 POSITIVO            | Desktop     | [9d5e3583e2](https://linux-hardware.org/?probe=9d5e3583e2) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Dell          | 0XNJ2Y A00                  | Desktop     | [52e1e36724](https://linux-hardware.org/?probe=52e1e36724) | May 11, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [2591f59c80](https://linux-hardware.org/?probe=2591f59c80) | May 11, 2022 |
| EVGA          | 132-YW-E178-FTW 1           | Desktop     | [f9b1fe2224](https://linux-hardware.org/?probe=f9b1fe2224) | May 10, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [2091818d85](https://linux-hardware.org/?probe=2091818d85) | May 10, 2022 |
| Sony          | VPCF23S1E                   | Notebook    | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [b1d92dcb4e](https://linux-hardware.org/?probe=b1d92dcb4e) | May 10, 2022 |
| HP            | Notebook                    | Notebook    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [d2b0694da5](https://linux-hardware.org/?probe=d2b0694da5) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | Notebook    | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| Lenovo        | ThinkPad E555 20DH000WGE    | Notebook    | [75920152df](https://linux-hardware.org/?probe=75920152df) | May 10, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [feafca0464](https://linux-hardware.org/?probe=feafca0464) | May 10, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fe92976577](https://linux-hardware.org/?probe=fe92976577) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [730c246f44](https://linux-hardware.org/?probe=730c246f44) | May 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [99078d316d](https://linux-hardware.org/?probe=99078d316d) | May 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f60ba0abd7](https://linux-hardware.org/?probe=f60ba0abd7) | May 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9a7b248f26](https://linux-hardware.org/?probe=9a7b248f26) | May 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bf8ea76f0a](https://linux-hardware.org/?probe=bf8ea76f0a) | May 10, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| Clevo         | W55xEU                      | Notebook    | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [a3c1257116](https://linux-hardware.org/?probe=a3c1257116) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [8caf6e2b66](https://linux-hardware.org/?probe=8caf6e2b66) | May 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [fdc78a778b](https://linux-hardware.org/?probe=fdc78a778b) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4242d236c5](https://linux-hardware.org/?probe=4242d236c5) | May 09, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [cc42e8d5e5](https://linux-hardware.org/?probe=cc42e8d5e5) | May 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| ASRock        | A88M-G                      | Desktop     | [d67df6ff7d](https://linux-hardware.org/?probe=d67df6ff7d) | May 09, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [b438c97dca](https://linux-hardware.org/?probe=b438c97dca) | May 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [cc53668d3f](https://linux-hardware.org/?probe=cc53668d3f) | May 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [bdfe0722a7](https://linux-hardware.org/?probe=bdfe0722a7) | May 09, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [27b384c114](https://linux-hardware.org/?probe=27b384c114) | May 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d427368abd](https://linux-hardware.org/?probe=d427368abd) | May 08, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [899a0e8999](https://linux-hardware.org/?probe=899a0e8999) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | Notebook    | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [10eb959775](https://linux-hardware.org/?probe=10eb959775) | Apr 30, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [89def966af](https://linux-hardware.org/?probe=89def966af) | Apr 30, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [9b128bc47e](https://linux-hardware.org/?probe=9b128bc47e) | Apr 30, 2022 |
| PCWare        | IPX4105G Pro                | Desktop     | [073d789fc4](https://linux-hardware.org/?probe=073d789fc4) | Apr 29, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0b88a7422d](https://linux-hardware.org/?probe=0b88a7422d) | Apr 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c07e06f794](https://linux-hardware.org/?probe=c07e06f794) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [127862c3f7](https://linux-hardware.org/?probe=127862c3f7) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [e2461ef9a7](https://linux-hardware.org/?probe=e2461ef9a7) | Apr 27, 2022 |
| Acer          | Aspire 3810TZ               | Notebook    | [cba19ea352](https://linux-hardware.org/?probe=cba19ea352) | Apr 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [593ee8ccf3](https://linux-hardware.org/?probe=593ee8ccf3) | Apr 27, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [5850b85224](https://linux-hardware.org/?probe=5850b85224) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [26727e92e4](https://linux-hardware.org/?probe=26727e92e4) | Apr 22, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [29a508398a](https://linux-hardware.org/?probe=29a508398a) | Apr 22, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4f27720e96](https://linux-hardware.org/?probe=4f27720e96) | Apr 21, 2022 |
| Acer          | Extensa 2519                | Notebook    | [ae1a90a282](https://linux-hardware.org/?probe=ae1a90a282) | Apr 21, 2022 |
| HP            | Notebook                    | Notebook    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | Notebook    | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4151908bf](https://linux-hardware.org/?probe=f4151908bf) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [90486ad164](https://linux-hardware.org/?probe=90486ad164) | Apr 15, 2022 |
| HP            | 17E2                        | Mini pc     | [a7bb99026f](https://linux-hardware.org/?probe=a7bb99026f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [80572def69](https://linux-hardware.org/?probe=80572def69) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [191880e24b](https://linux-hardware.org/?probe=191880e24b) | Apr 14, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8619f35452](https://linux-hardware.org/?probe=8619f35452) | Apr 13, 2022 |
| Dell          | Precision 5530              | Notebook    | [3c4cc67cc4](https://linux-hardware.org/?probe=3c4cc67cc4) | Apr 13, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [3775d7e528](https://linux-hardware.org/?probe=3775d7e528) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [8645c57fcc](https://linux-hardware.org/?probe=8645c57fcc) | Apr 09, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [00d95f7a3a](https://linux-hardware.org/?probe=00d95f7a3a) | Apr 09, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [7e54067e6a](https://linux-hardware.org/?probe=7e54067e6a) | Apr 08, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [c40867ec67](https://linux-hardware.org/?probe=c40867ec67) | Apr 08, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [9a2939bd71](https://linux-hardware.org/?probe=9a2939bd71) | Apr 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [ff290845fe](https://linux-hardware.org/?probe=ff290845fe) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | Notebook    | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| HP            | 0A9Ch                       | Desktop     | [5a415a150f](https://linux-hardware.org/?probe=5a415a150f) | Apr 05, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [c1419a6f3c](https://linux-hardware.org/?probe=c1419a6f3c) | Apr 03, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | Desktop     | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ff7f2845b0](https://linux-hardware.org/?probe=ff7f2845b0) | Apr 01, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6eb9c66f7d](https://linux-hardware.org/?probe=6eb9c66f7d) | Mar 31, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [787cb334c2](https://linux-hardware.org/?probe=787cb334c2) | Mar 28, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8392d5c3fe](https://linux-hardware.org/?probe=8392d5c3fe) | Mar 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [5c424251c8](https://linux-hardware.org/?probe=5c424251c8) | Mar 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b9aec6129a](https://linux-hardware.org/?probe=b9aec6129a) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3429bc98ac](https://linux-hardware.org/?probe=3429bc98ac) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e862658aa](https://linux-hardware.org/?probe=9e862658aa) | Mar 22, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b632c4a0c5](https://linux-hardware.org/?probe=b632c4a0c5) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [73734bbce5](https://linux-hardware.org/?probe=73734bbce5) | Mar 19, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [651e0fb5eb](https://linux-hardware.org/?probe=651e0fb5eb) | Mar 16, 2022 |
| ASRock        | Z370 Gaming K6              | Desktop     | [90bedd5ff6](https://linux-hardware.org/?probe=90bedd5ff6) | Mar 14, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [2e45a56117](https://linux-hardware.org/?probe=2e45a56117) | Mar 14, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [704438d05e](https://linux-hardware.org/?probe=704438d05e) | Mar 13, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [571547ee1d](https://linux-hardware.org/?probe=571547ee1d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [7ce09d403d](https://linux-hardware.org/?probe=7ce09d403d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [ec1783840e](https://linux-hardware.org/?probe=ec1783840e) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [31b0bbe97f](https://linux-hardware.org/?probe=31b0bbe97f) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [ef67eef250](https://linux-hardware.org/?probe=ef67eef250) | Mar 13, 2022 |
| Microsoft     | Surface Book                | Tablet      | [00d499f50c](https://linux-hardware.org/?probe=00d499f50c) | Mar 13, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [8ec8e7be46](https://linux-hardware.org/?probe=8ec8e7be46) | Mar 12, 2022 |
| ASRock        | H61M-S1 PLUS                | Desktop     | [56c15fcbf6](https://linux-hardware.org/?probe=56c15fcbf6) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [2e7a87521b](https://linux-hardware.org/?probe=2e7a87521b) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [a610ee6ad5](https://linux-hardware.org/?probe=a610ee6ad5) | Mar 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [cbff798f89](https://linux-hardware.org/?probe=cbff798f89) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [02e748e3ac](https://linux-hardware.org/?probe=02e748e3ac) | Mar 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c9b7431269](https://linux-hardware.org/?probe=c9b7431269) | Mar 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f118a17b6e](https://linux-hardware.org/?probe=f118a17b6e) | Mar 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [d549055064](https://linux-hardware.org/?probe=d549055064) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | 2129                        | Desktop     | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [37d07ec6df](https://linux-hardware.org/?probe=37d07ec6df) | Mar 02, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [dc25902f7e](https://linux-hardware.org/?probe=dc25902f7e) | Feb 28, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f4a068f57c](https://linux-hardware.org/?probe=f4a068f57c) | Feb 27, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e3931f1fb](https://linux-hardware.org/?probe=2e3931f1fb) | Feb 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [f904e185fb](https://linux-hardware.org/?probe=f904e185fb) | Feb 25, 2022 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [f8f8968f19](https://linux-hardware.org/?probe=f8f8968f19) | Feb 22, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cd61ef5a5d](https://linux-hardware.org/?probe=cd61ef5a5d) | Feb 20, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [100666467c](https://linux-hardware.org/?probe=100666467c) | Feb 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [450f779085](https://linux-hardware.org/?probe=450f779085) | Feb 20, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [686b1350c9](https://linux-hardware.org/?probe=686b1350c9) | Feb 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [24ec19a092](https://linux-hardware.org/?probe=24ec19a092) | Feb 17, 2022 |
| MSI           | CX600                       | Notebook    | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Teclast       | F5                          | Convertible | [ab28d730e6](https://linux-hardware.org/?probe=ab28d730e6) | Feb 15, 2022 |
| MSI           | A55M-P33                    | Desktop     | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [47ff2c9673](https://linux-hardware.org/?probe=47ff2c9673) | Feb 15, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [787eacd33c](https://linux-hardware.org/?probe=787eacd33c) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [91d1953478](https://linux-hardware.org/?probe=91d1953478) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [119cc6c1b1](https://linux-hardware.org/?probe=119cc6c1b1) | Feb 13, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [33abf3e568](https://linux-hardware.org/?probe=33abf3e568) | Feb 11, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [8c571a917d](https://linux-hardware.org/?probe=8c571a917d) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c2729fb959](https://linux-hardware.org/?probe=c2729fb959) | Feb 10, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [34a6010fb2](https://linux-hardware.org/?probe=34a6010fb2) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [e995276798](https://linux-hardware.org/?probe=e995276798) | Feb 07, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [1b0a32e129](https://linux-hardware.org/?probe=1b0a32e129) | Feb 06, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | 2B4B                        | Desktop     | [4205ceb454](https://linux-hardware.org/?probe=4205ceb454) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [af71ad30ed](https://linux-hardware.org/?probe=af71ad30ed) | Jan 30, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [373b062fd0](https://linux-hardware.org/?probe=373b062fd0) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [9cc991a921](https://linux-hardware.org/?probe=9cc991a921) | Jan 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [533df9d207](https://linux-hardware.org/?probe=533df9d207) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [093d240f55](https://linux-hardware.org/?probe=093d240f55) | Jan 28, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [50b28ab929](https://linux-hardware.org/?probe=50b28ab929) | Jan 26, 2022 |
| MSI           | Pulse GL66 11UDK            | Notebook    | [06d5ba6ef3](https://linux-hardware.org/?probe=06d5ba6ef3) | Jan 26, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [cf7b776431](https://linux-hardware.org/?probe=cf7b776431) | Jan 24, 2022 |
| Getac         | V200-G2                     | Notebook    | [6d9b456d5f](https://linux-hardware.org/?probe=6d9b456d5f) | Jan 24, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c07dc3a8ee](https://linux-hardware.org/?probe=c07dc3a8ee) | Jan 24, 2022 |
| ASUSTek       | SABERTOOTH 55i              | Desktop     | [5c67654acf](https://linux-hardware.org/?probe=5c67654acf) | Jan 23, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [170a3c500e](https://linux-hardware.org/?probe=170a3c500e) | Jan 21, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [a8eefb04f1](https://linux-hardware.org/?probe=a8eefb04f1) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d195d57aa4](https://linux-hardware.org/?probe=d195d57aa4) | Jan 21, 2022 |
| Sony          | VPCYB15AB                   | Notebook    | [1d7c8aa76a](https://linux-hardware.org/?probe=1d7c8aa76a) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a30f5fabcd](https://linux-hardware.org/?probe=a30f5fabcd) | Jan 18, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [f55512e3bc](https://linux-hardware.org/?probe=f55512e3bc) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| MSI           | P67A-C45                    | Desktop     | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [99d2f2253d](https://linux-hardware.org/?probe=99d2f2253d) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [2000988c8b](https://linux-hardware.org/?probe=2000988c8b) | Jan 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [30b86e16bf](https://linux-hardware.org/?probe=30b86e16bf) | Jan 10, 2022 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [af7d37f35c](https://linux-hardware.org/?probe=af7d37f35c) | Jan 10, 2022 |
| HP            | 2B29                        | Desktop     | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| Dell          | Latitude XT2                | Notebook    | [65adc4cb22](https://linux-hardware.org/?probe=65adc4cb22) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [85fc03c636](https://linux-hardware.org/?probe=85fc03c636) | Jan 08, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [5d8b5e0c8e](https://linux-hardware.org/?probe=5d8b5e0c8e) | Jan 07, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [4a33da1bc1](https://linux-hardware.org/?probe=4a33da1bc1) | Jan 06, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [39b60e131a](https://linux-hardware.org/?probe=39b60e131a) | Jan 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [c7bf784225](https://linux-hardware.org/?probe=c7bf784225) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [896b348390](https://linux-hardware.org/?probe=896b348390) | Jan 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bfd3b013ad](https://linux-hardware.org/?probe=bfd3b013ad) | Jan 02, 2022 |
| MSI           | C847IS-P33                  | Desktop     | [1ea085e13d](https://linux-hardware.org/?probe=1ea085e13d) | Jan 02, 2022 |
| Toshiba       | AS 1301                     | Notebook    | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [6a29278e3f](https://linux-hardware.org/?probe=6a29278e3f) | Dec 31, 2021 |
| Dell          | 0RY007                      | Desktop     | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b29f429221](https://linux-hardware.org/?probe=b29f429221) | Dec 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [86da0c348f](https://linux-hardware.org/?probe=86da0c348f) | Dec 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [c152f8c702](https://linux-hardware.org/?probe=c152f8c702) | Dec 27, 2021 |
| Dell          | Studio 1737                 | Notebook    | [6b5362714f](https://linux-hardware.org/?probe=6b5362714f) | Dec 27, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [5f62a9d831](https://linux-hardware.org/?probe=5f62a9d831) | Dec 26, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81f1473127](https://linux-hardware.org/?probe=81f1473127) | Dec 26, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [e62e9c50d0](https://linux-hardware.org/?probe=e62e9c50d0) | Dec 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a1b975a4e1](https://linux-hardware.org/?probe=a1b975a4e1) | Dec 26, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [f74478e98e](https://linux-hardware.org/?probe=f74478e98e) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [491f8d7813](https://linux-hardware.org/?probe=491f8d7813) | Dec 21, 2021 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [b2108dd133](https://linux-hardware.org/?probe=b2108dd133) | Dec 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f86ef0f23](https://linux-hardware.org/?probe=1f86ef0f23) | Dec 19, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| MSI           | A55M-P33                    | Desktop     | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bb01b911cd](https://linux-hardware.org/?probe=bb01b911cd) | Dec 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| Google        | Pantheon                    | Notebook    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [8f1556eb30](https://linux-hardware.org/?probe=8f1556eb30) | Dec 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [b5a9d168a5](https://linux-hardware.org/?probe=b5a9d168a5) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [0fca0b679f](https://linux-hardware.org/?probe=0fca0b679f) | Dec 16, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [452044c67e](https://linux-hardware.org/?probe=452044c67e) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [4dc9e683af](https://linux-hardware.org/?probe=4dc9e683af) | Dec 15, 2021 |
| Biostar       | X370GT5                     | Desktop     | [40849a76de](https://linux-hardware.org/?probe=40849a76de) | Dec 14, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [3ad9c4f3dc](https://linux-hardware.org/?probe=3ad9c4f3dc) | Dec 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [696d4a24cd](https://linux-hardware.org/?probe=696d4a24cd) | Dec 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3d396a7f28](https://linux-hardware.org/?probe=3d396a7f28) | Dec 13, 2021 |
| HP            | Elite Dragonfly             | Convertible | [d25e8dec93](https://linux-hardware.org/?probe=d25e8dec93) | Dec 13, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [68bef1611d](https://linux-hardware.org/?probe=68bef1611d) | Dec 13, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [8febc9ddd7](https://linux-hardware.org/?probe=8febc9ddd7) | Dec 13, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2ed0c9dfd](https://linux-hardware.org/?probe=e2ed0c9dfd) | Dec 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Dell          | Inspiron 15 3510            | Notebook    | [7d97420d98](https://linux-hardware.org/?probe=7d97420d98) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [176194b06f](https://linux-hardware.org/?probe=176194b06f) | Dec 10, 2021 |
| Google        | Kip                         | Notebook    | [0e5291c891](https://linux-hardware.org/?probe=0e5291c891) | Dec 09, 2021 |
| Google        | Kip                         | Notebook    | [9bbfc62162](https://linux-hardware.org/?probe=9bbfc62162) | Dec 09, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [25179417ad](https://linux-hardware.org/?probe=25179417ad) | Dec 09, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [543d2dfef7](https://linux-hardware.org/?probe=543d2dfef7) | Dec 07, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| HP            | 0A9Ch                       | Desktop     | [9bbd755279](https://linux-hardware.org/?probe=9bbd755279) | Dec 07, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [4d4c80773b](https://linux-hardware.org/?probe=4d4c80773b) | Dec 07, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| HP            | 2B4B                        | Desktop     | [efc81a48f3](https://linux-hardware.org/?probe=efc81a48f3) | Dec 05, 2021 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [7bb538c6f0](https://linux-hardware.org/?probe=7bb538c6f0) | Dec 05, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [b6e4b7efdc](https://linux-hardware.org/?probe=b6e4b7efdc) | Dec 04, 2021 |
| Lenovo        | ThinkPad E495 20NE001GGE    | Notebook    | [31e9125d85](https://linux-hardware.org/?probe=31e9125d85) | Dec 03, 2021 |
| Lenovo        | ThinkPad E495 20NE001GGE    | Notebook    | [3b230e73b3](https://linux-hardware.org/?probe=3b230e73b3) | Dec 03, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7b1d555cc3](https://linux-hardware.org/?probe=7b1d555cc3) | Dec 03, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [3da13c5e1b](https://linux-hardware.org/?probe=3da13c5e1b) | Nov 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [e4f4713ac2](https://linux-hardware.org/?probe=e4f4713ac2) | Nov 29, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [65ba69012d](https://linux-hardware.org/?probe=65ba69012d) | Nov 28, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [403ada1042](https://linux-hardware.org/?probe=403ada1042) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b58c73a493](https://linux-hardware.org/?probe=b58c73a493) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f6ab5c54f6](https://linux-hardware.org/?probe=f6ab5c54f6) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| Dell          | 0RW199                      | Desktop     | [f00caa69eb](https://linux-hardware.org/?probe=f00caa69eb) | Nov 26, 2021 |
| Dell          | Precision M4800             | Notebook    | [c81b76f119](https://linux-hardware.org/?probe=c81b76f119) | Nov 25, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [4eb53d4335](https://linux-hardware.org/?probe=4eb53d4335) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [995eaf8345](https://linux-hardware.org/?probe=995eaf8345) | Nov 25, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a6b3b8877b](https://linux-hardware.org/?probe=a6b3b8877b) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7546b1e030](https://linux-hardware.org/?probe=7546b1e030) | Nov 24, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [5ee25c6894](https://linux-hardware.org/?probe=5ee25c6894) | Nov 23, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7995f7e3a8](https://linux-hardware.org/?probe=7995f7e3a8) | Nov 23, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [c31b46e5b5](https://linux-hardware.org/?probe=c31b46e5b5) | Nov 22, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1cc474712f](https://linux-hardware.org/?probe=1cc474712f) | Nov 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [933eda02dc](https://linux-hardware.org/?probe=933eda02dc) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [8d8d873287](https://linux-hardware.org/?probe=8d8d873287) | Nov 20, 2021 |
| ASRock        | J5040-ITX                   | Desktop     | [0c072ca601](https://linux-hardware.org/?probe=0c072ca601) | Nov 19, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [50dfc9f261](https://linux-hardware.org/?probe=50dfc9f261) | Nov 19, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [4f96b5ad58](https://linux-hardware.org/?probe=4f96b5ad58) | Nov 19, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6d345c2500](https://linux-hardware.org/?probe=6d345c2500) | Nov 18, 2021 |
| Lenovo        | ThinkPad E495 20NES01600    | Notebook    | [aacc57f134](https://linux-hardware.org/?probe=aacc57f134) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [f2e77fa439](https://linux-hardware.org/?probe=f2e77fa439) | Nov 17, 2021 |
| Dell          | 03015M A09                  | Server      | [c685a0033b](https://linux-hardware.org/?probe=c685a0033b) | Nov 17, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6444d420e3](https://linux-hardware.org/?probe=6444d420e3) | Nov 16, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [ce05c5de33](https://linux-hardware.org/?probe=ce05c5de33) | Nov 15, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [2c7f2bbe1e](https://linux-hardware.org/?probe=2c7f2bbe1e) | Nov 14, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP            | Pavilion dv6                | Notebook    | [30c1df8961](https://linux-hardware.org/?probe=30c1df8961) | Nov 13, 2021 |
| Samsung       | 550XDA                      | Notebook    | [69fe372895](https://linux-hardware.org/?probe=69fe372895) | Nov 12, 2021 |
| Samsung       | 550XDA                      | Notebook    | [61a4dbe6b6](https://linux-hardware.org/?probe=61a4dbe6b6) | Nov 12, 2021 |
| HP            | 844C                        | Desktop     | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [f042aedbd9](https://linux-hardware.org/?probe=f042aedbd9) | Nov 12, 2021 |
| Dell          | 0W844P A02                  | Server      | [a8902b24dd](https://linux-hardware.org/?probe=a8902b24dd) | Nov 12, 2021 |
| Dell          | Latitude E5440              | Notebook    | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f52dc0680](https://linux-hardware.org/?probe=3f52dc0680) | Nov 09, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [be3123eae1](https://linux-hardware.org/?probe=be3123eae1) | Nov 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [cf717529eb](https://linux-hardware.org/?probe=cf717529eb) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Acer          | Spin SP313-51N              | Convertible | [7f5392b700](https://linux-hardware.org/?probe=7f5392b700) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b05955d022](https://linux-hardware.org/?probe=b05955d022) | Nov 06, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [377a49cece](https://linux-hardware.org/?probe=377a49cece) | Nov 06, 2021 |
| Dell          | G3 3590                     | Notebook    | [aa237dfc61](https://linux-hardware.org/?probe=aa237dfc61) | Nov 06, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| Biostar       | H77MU3                      | Desktop     | [620dd98d14](https://linux-hardware.org/?probe=620dd98d14) | Nov 05, 2021 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [30831977d2](https://linux-hardware.org/?probe=30831977d2) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [f761a8dfa1](https://linux-hardware.org/?probe=f761a8dfa1) | Nov 03, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [276bfdb97e](https://linux-hardware.org/?probe=276bfdb97e) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [18ac20be04](https://linux-hardware.org/?probe=18ac20be04) | Nov 03, 2021 |
| Dell          | Precision 7530              | Notebook    | [6a1961e13d](https://linux-hardware.org/?probe=6a1961e13d) | Nov 03, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [f9fbde199a](https://linux-hardware.org/?probe=f9fbde199a) | Nov 02, 2021 |
| Dell          | 0KP561                      | Desktop     | [e0c7723977](https://linux-hardware.org/?probe=e0c7723977) | Nov 02, 2021 |
| Dell          | 0KP561                      | Desktop     | [904f09d033](https://linux-hardware.org/?probe=904f09d033) | Nov 02, 2021 |
| MSI           | X58 Pro                     | Desktop     | [e37a1a6dd3](https://linux-hardware.org/?probe=e37a1a6dd3) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7599b9831d](https://linux-hardware.org/?probe=7599b9831d) | Nov 01, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [eacc1e3f66](https://linux-hardware.org/?probe=eacc1e3f66) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e04a41fc30](https://linux-hardware.org/?probe=e04a41fc30) | Oct 31, 2021 |
| HP            | ZBook 14 G2                 | Notebook    | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [0c14ffd402](https://linux-hardware.org/?probe=0c14ffd402) | Oct 30, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [d4c089bc2f](https://linux-hardware.org/?probe=d4c089bc2f) | Oct 30, 2021 |
| ASUSTek       | X751LK                      | Notebook    | [b2cda34b7e](https://linux-hardware.org/?probe=b2cda34b7e) | Oct 30, 2021 |
| ZOTAC         | ZBOX-MA320                  | Mini pc     | [514267f2d8](https://linux-hardware.org/?probe=514267f2d8) | Oct 29, 2021 |
| IP3 Tech      | rev1.0                      | All in one  | [9032726ea4](https://linux-hardware.org/?probe=9032726ea4) | Oct 28, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [66fa4360dd](https://linux-hardware.org/?probe=66fa4360dd) | Oct 27, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | Notebook    | [65eac6abc6](https://linux-hardware.org/?probe=65eac6abc6) | Oct 27, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [2b89909a49](https://linux-hardware.org/?probe=2b89909a49) | Oct 25, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [382b33add2](https://linux-hardware.org/?probe=382b33add2) | Oct 25, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| Dell          | 0KP561                      | Desktop     | [08bbb7d29e](https://linux-hardware.org/?probe=08bbb7d29e) | Oct 22, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [9d090ad177](https://linux-hardware.org/?probe=9d090ad177) | Oct 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [a4ff2480e6](https://linux-hardware.org/?probe=a4ff2480e6) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [20be8bd8e7](https://linux-hardware.org/?probe=20be8bd8e7) | Oct 21, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Fujitsu       | D2619 S26361-D2619-A14 W... | Server      | [43c0756ba6](https://linux-hardware.org/?probe=43c0756ba6) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| ASUSTek       | Q324UAK                     | Convertible | [a8334894c5](https://linux-hardware.org/?probe=a8334894c5) | Oct 19, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [c3c2bded72](https://linux-hardware.org/?probe=c3c2bded72) | Oct 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [d111902eac](https://linux-hardware.org/?probe=d111902eac) | Oct 18, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [fb267ca5ae](https://linux-hardware.org/?probe=fb267ca5ae) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [872ae76863](https://linux-hardware.org/?probe=872ae76863) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [d1cdbd537e](https://linux-hardware.org/?probe=d1cdbd537e) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [10b4482e0f](https://linux-hardware.org/?probe=10b4482e0f) | Oct 12, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [50c28abba1](https://linux-hardware.org/?probe=50c28abba1) | Oct 11, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [f7a8acd7c5](https://linux-hardware.org/?probe=f7a8acd7c5) | Oct 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c37f278d59](https://linux-hardware.org/?probe=c37f278d59) | Oct 11, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [15e808f714](https://linux-hardware.org/?probe=15e808f714) | Oct 10, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | Notebook    | [4bb69f9fcc](https://linux-hardware.org/?probe=4bb69f9fcc) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [778b409af2](https://linux-hardware.org/?probe=778b409af2) | Oct 09, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [6db404b73c](https://linux-hardware.org/?probe=6db404b73c) | Oct 08, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [eb4d7c93c0](https://linux-hardware.org/?probe=eb4d7c93c0) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [ff4e1fdb3a](https://linux-hardware.org/?probe=ff4e1fdb3a) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [c439170645](https://linux-hardware.org/?probe=c439170645) | Oct 05, 2021 |
| HP            | 8591                        | Desktop     | [2de119b3d7](https://linux-hardware.org/?probe=2de119b3d7) | Oct 05, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [a9f8d1f512](https://linux-hardware.org/?probe=a9f8d1f512) | Oct 05, 2021 |
| HP            | Elite Dragonfly             | Convertible | [48cabedb1e](https://linux-hardware.org/?probe=48cabedb1e) | Oct 04, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| HP            | G61                         | Notebook    | [98ef6e48b5](https://linux-hardware.org/?probe=98ef6e48b5) | Oct 03, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e54f43704](https://linux-hardware.org/?probe=0e54f43704) | Oct 02, 2021 |
| Google        | Pantheon                    | Notebook    | [72ded95fab](https://linux-hardware.org/?probe=72ded95fab) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f0b874d4f2](https://linux-hardware.org/?probe=f0b874d4f2) | Oct 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [eabcfa676f](https://linux-hardware.org/?probe=eabcfa676f) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [33a2f5f274](https://linux-hardware.org/?probe=33a2f5f274) | Oct 02, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | Notebook    | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [3147ae8c58](https://linux-hardware.org/?probe=3147ae8c58) | Oct 01, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| ASRock        | H110M-G/M.2                 | Desktop     | [fa98bc9cc1](https://linux-hardware.org/?probe=fa98bc9cc1) | Oct 01, 2021 |
| HP            | 8591                        | Desktop     | [16548ed5fc](https://linux-hardware.org/?probe=16548ed5fc) | Sep 30, 2021 |
| HP            | 8591                        | Desktop     | [187edb6508](https://linux-hardware.org/?probe=187edb6508) | Sep 30, 2021 |
| Chuwi         | UBook X                     | Convertible | [b227e694f7](https://linux-hardware.org/?probe=b227e694f7) | Sep 29, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [7024087dbd](https://linux-hardware.org/?probe=7024087dbd) | Sep 26, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b1c787f5e6](https://linux-hardware.org/?probe=b1c787f5e6) | Sep 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [39d644c56a](https://linux-hardware.org/?probe=39d644c56a) | Sep 26, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | Notebook    | [6c7308609b](https://linux-hardware.org/?probe=6c7308609b) | Sep 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [22d4ba7e2e](https://linux-hardware.org/?probe=22d4ba7e2e) | Sep 25, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [82ad91793d](https://linux-hardware.org/?probe=82ad91793d) | Sep 25, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [fca13979bf](https://linux-hardware.org/?probe=fca13979bf) | Sep 22, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Timi          | A35S                        | Notebook    | [c10b3fac0b](https://linux-hardware.org/?probe=c10b3fac0b) | Sep 22, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [59490b03a0](https://linux-hardware.org/?probe=59490b03a0) | Sep 21, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| Dell          | Precision M6700             | Notebook    | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| VS Company    | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [9e88464633](https://linux-hardware.org/?probe=9e88464633) | Sep 20, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d48766cb68](https://linux-hardware.org/?probe=d48766cb68) | Sep 19, 2021 |
| Google        | Pantheon                    | Notebook    | [eaa5a17c4b](https://linux-hardware.org/?probe=eaa5a17c4b) | Sep 19, 2021 |
| Medion        | S15449                      | Notebook    | [8f1110e14a](https://linux-hardware.org/?probe=8f1110e14a) | Sep 18, 2021 |
| HP            | ZBook 17                    | Notebook    | [df2e227740](https://linux-hardware.org/?probe=df2e227740) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [783d480732](https://linux-hardware.org/?probe=783d480732) | Sep 16, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [84d5715b05](https://linux-hardware.org/?probe=84d5715b05) | Sep 16, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [2a08044752](https://linux-hardware.org/?probe=2a08044752) | Sep 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e3c2042fa](https://linux-hardware.org/?probe=8e3c2042fa) | Sep 16, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [47d1d04589](https://linux-hardware.org/?probe=47d1d04589) | Sep 16, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [5f33450a0d](https://linux-hardware.org/?probe=5f33450a0d) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [66385493ae](https://linux-hardware.org/?probe=66385493ae) | Sep 15, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [1e2e03c85c](https://linux-hardware.org/?probe=1e2e03c85c) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| MSI           | X370 GAMING PRO             | Desktop     | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| Medion        | S15449                      | Notebook    | [03b29809eb](https://linux-hardware.org/?probe=03b29809eb) | Sep 11, 2021 |
| MSI           | GE72 7RD                    | Notebook    | [d02699b3f9](https://linux-hardware.org/?probe=d02699b3f9) | Sep 11, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [e5b03fa6d6](https://linux-hardware.org/?probe=e5b03fa6d6) | Sep 10, 2021 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [db9571e8ce](https://linux-hardware.org/?probe=db9571e8ce) | Sep 09, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [522f36731e](https://linux-hardware.org/?probe=522f36731e) | Sep 07, 2021 |
| Dell          | Precision M3800             | Notebook    | [5dba4d3bce](https://linux-hardware.org/?probe=5dba4d3bce) | Sep 07, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [9a46145cf4](https://linux-hardware.org/?probe=9a46145cf4) | Sep 06, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [d4adebf878](https://linux-hardware.org/?probe=d4adebf878) | Sep 06, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 988       | 61.9%   |
| openSUSE Leap-15.2           | 211       | 13.22%  |
| openSUSE Leap-15.3           | 128       | 8.02%   |
| openSUSE Leap-15.1           | 122       | 7.64%   |
| openSUSE Leap-15.4           | 64        | 4.01%   |
| openSUSE Leap-15.0           | 48        | 3.01%   |
| openSUSE Microos-XXXXXXXX    | 16        | 1%      |
| openSUSE 13.2                | 5         | 0.31%   |
| openSUSE Leap-42.2           | 3         | 0.19%   |
| openSUSE                     | 3         | 0.19%   |
| openSUSE Leap-42.3           | 2         | 0.13%   |
| openSUSE Leap-15.5           | 2         | 0.13%   |
| openSUSE 42.3                | 2         | 0.13%   |
| openSUSE Leap-42.1           | 1         | 0.06%   |
| openSUSE 13.1                | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 1546      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.4-1-default             | 49        | 2.65%   |
| 4.12.14-lp151.28.44-default  | 43        | 2.32%   |
| 5.6.0-1-default              | 31        | 1.67%   |
| 6.0.8-1-default              | 28        | 1.51%   |
| 5.19.2-1-default             | 24        | 1.3%    |
| 4.18.15-1-default            | 23        | 1.24%   |
| 5.3.18-lp152.63-default      | 22        | 1.19%   |
| 5.14.21-150400.22-default    | 22        | 1.19%   |
| 5.16.11-1-default            | 20        | 1.08%   |
| 5.14.14-1-default            | 20        | 1.08%   |
| 5.6.2-1-default              | 19        | 1.03%   |
| 5.17.1-1-default             | 19        | 1.03%   |
| 5.3.18-lp152.57-default      | 18        | 0.97%   |
| 5.3.18-59.37-default         | 18        | 0.97%   |
| 5.17.9-1-default             | 18        | 0.97%   |
| 5.11.6-1-default             | 18        | 0.97%   |
| 5.8.4-1-default              | 17        | 0.92%   |
| 5.3.18-lp152.41-default      | 17        | 0.92%   |
| 5.19.8-1-default             | 17        | 0.92%   |
| 5.18.6-1-default             | 17        | 0.92%   |
| 5.10.7-1-default             | 17        | 0.92%   |
| 5.3.18-lp152.36-default      | 16        | 0.86%   |
| 5.14.21-150400.24.21-default | 16        | 0.86%   |
| 6.0.3-1-default              | 15        | 0.81%   |
| 5.10.16-1-default            | 15        | 0.81%   |
| 5.6.12-1-default             | 14        | 0.76%   |
| 5.3.18-lp152.50-default      | 14        | 0.76%   |
| 5.13.8-1-default             | 14        | 0.76%   |
| 4.12.14-lp151.28.48-default  | 14        | 0.76%   |
| 5.3.18-59.27-default         | 13        | 0.7%    |
| 5.3.18-59.19-default         | 13        | 0.7%    |
| 5.14.6-1-default             | 13        | 0.7%    |
| 5.8.10-1-default             | 12        | 0.65%   |
| 5.3.18-lp152.66-default      | 12        | 0.65%   |
| 5.15.12-1-default            | 12        | 0.65%   |
| 5.14.21-150400.24.18-default | 12        | 0.65%   |
| 5.12.9-1-default             | 12        | 0.65%   |
| 6.0.6-1-default              | 11        | 0.59%   |
| 5.8.0-1-default              | 11        | 0.59%   |
| 5.3.18-lp152.47-default      | 11        | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 309       | 17.3%   |
| 4.12.14 | 157       | 8.79%   |
| 5.14.21 | 63        | 3.53%   |
| 5.17.4  | 49        | 2.74%   |
| 5.6.0   | 33        | 1.85%   |
| 5.14.14 | 30        | 1.68%   |
| 6.0.8   | 28        | 1.57%   |
| 5.19.2  | 24        | 1.34%   |
| 4.18.15 | 23        | 1.29%   |
| 5.6.2   | 21        | 1.18%   |
| 5.17.1  | 20        | 1.12%   |
| 5.16.11 | 20        | 1.12%   |
| 5.12.4  | 19        | 1.06%   |
| 5.11.6  | 19        | 1.06%   |
| 5.8.4   | 18        | 1.01%   |
| 5.17.9  | 18        | 1.01%   |
| 5.14.6  | 18        | 1.01%   |
| 5.10.7  | 18        | 1.01%   |
| 5.19.8  | 17        | 0.95%   |
| 5.18.6  | 17        | 0.95%   |
| 6.0.3   | 16        | 0.9%    |
| 5.12.9  | 15        | 0.84%   |
| 5.12.0  | 15        | 0.84%   |
| 5.10.16 | 15        | 0.84%   |
| 5.9.1   | 14        | 0.78%   |
| 5.6.12  | 14        | 0.78%   |
| 5.13.8  | 14        | 0.78%   |
| 5.18.9  | 13        | 0.73%   |
| 5.8.10  | 12        | 0.67%   |
| 5.8.0   | 12        | 0.67%   |
| 5.16.0  | 12        | 0.67%   |
| 5.15.12 | 12        | 0.67%   |
| 6.0.6   | 11        | 0.62%   |
| 5.3.12  | 11        | 0.62%   |
| 5.15.8  | 11        | 0.62%   |
| 5.15.5  | 11        | 0.62%   |
| 5.14.2  | 11        | 0.62%   |
| 6.0.7   | 10        | 0.56%   |
| 5.9.14  | 10        | 0.56%   |
| 5.18.11 | 10        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 330       | 18.94%  |
| 4.12    | 157       | 9.01%   |
| 5.14    | 150       | 8.61%   |
| 5.17    | 112       | 6.43%   |
| 6.0     | 86        | 4.94%   |
| 5.6     | 82        | 4.71%   |
| 5.16    | 77        | 4.42%   |
| 5.18    | 74        | 4.25%   |
| 5.12    | 72        | 4.13%   |
| 5.8     | 70        | 4.02%   |
| 5.10    | 68        | 3.9%    |
| 5.19    | 66        | 3.79%   |
| 5.11    | 59        | 3.39%   |
| 5.15    | 58        | 3.33%   |
| 5.13    | 49        | 2.81%   |
| 5.9     | 40        | 2.3%    |
| 5.7     | 36        | 2.07%   |
| 5.5     | 33        | 1.89%   |
| 4.18    | 27        | 1.55%   |
| 5.4     | 21        | 1.21%   |
| 5.0     | 14        | 0.8%    |
| 5.2     | 13        | 0.75%   |
| 4.17    | 11        | 0.63%   |
| 4.4     | 9         | 0.52%   |
| 5.1     | 5         | 0.29%   |
| 4.20    | 5         | 0.29%   |
| 4.3     | 4         | 0.23%   |
| 3.16    | 4         | 0.23%   |
| 4.19    | 3         | 0.17%   |
| 6.1     | 2         | 0.11%   |
| 4.16    | 2         | 0.11%   |
| 4.7     | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |
| 3.12    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1528      | 98.77%  |
| i686    | 13        | 0.84%   |
| aarch64 | 6         | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 820       | 51.15%  |
| GNOME         | 263       | 16.41%  |
| KDE           | 212       | 13.23%  |
| Unknown       | 132       | 8.23%   |
| XFCE          | 82        | 5.12%   |
| MATE          | 19        | 1.19%   |
| X-Cinnamon    | 16        | 1%      |
| Cinnamon      | 10        | 0.62%   |
| KDE4          | 9         | 0.56%   |
| LXQt          | 7         | 0.44%   |
| ICEWM         | 5         | 0.31%   |
| Budgie        | 5         | 0.31%   |
| LXDE          | 4         | 0.25%   |
| WindowMaker   | 2         | 0.12%   |
| sway          | 2         | 0.12%   |
| Pantheon      | 2         | 0.12%   |
| i3            | 2         | 0.12%   |
| GNOME Classic | 2         | 0.12%   |
| Deepin        | 2         | 0.12%   |
| plasma5       | 1         | 0.06%   |
| openbox       | 1         | 0.06%   |
| Herbstluftwm  | 1         | 0.06%   |
| fvwm2         | 1         | 0.06%   |
| default       | 1         | 0.06%   |
| custom        | 1         | 0.06%   |
| awesome       | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1281      | 80.36%  |
| Wayland     | 242       | 15.18%  |
| Unknown     | 39        | 2.45%   |
| Tty         | 30        | 1.88%   |
| Unspecified | 2         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 582       | 36.65%  |
| LightDM | 550       | 34.63%  |
| SDDM    | 347       | 21.85%  |
| XDM     | 100       | 6.3%    |
| GDM     | 9         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 527       | 32.98%  |
| de_DE   | 194       | 12.14%  |
| Unknown | 177       | 11.08%  |
| POSIX   | 151       | 9.45%   |
| en_GB   | 107       | 6.7%    |
| pt_BR   | 65        | 4.07%   |
| ru_RU   | 60        | 3.75%   |
| es_ES   | 48        | 3%      |
| fr_FR   | 36        | 2.25%   |
| it_IT   | 33        | 2.07%   |
| pl_PL   | 24        | 1.5%    |
| nl_NL   | 19        | 1.19%   |
| pt_PT   | 18        | 1.13%   |
| zh_CN   | 10        | 0.63%   |
| cs_CZ   | 9         | 0.56%   |
| hu_HU   | 8         | 0.5%    |
| fi_FI   | 8         | 0.5%    |
| es_MX   | 6         | 0.38%   |
| es_AR   | 6         | 0.38%   |
| C       | 6         | 0.38%   |
| sv_SE   | 5         | 0.31%   |
| en_IN   | 5         | 0.31%   |
| tr_TR   | 4         | 0.25%   |
| nn_NO   | 4         | 0.25%   |
| nl_BE   | 4         | 0.25%   |
| nb_NO   | 4         | 0.25%   |
| en_IE   | 4         | 0.25%   |
| en_DE   | 4         | 0.25%   |
| en_AU   | 4         | 0.25%   |
| hr_HR   | 3         | 0.19%   |
| cv_RU   | 3         | 0.19%   |
| bg_BG   | 3         | 0.19%   |
| sk_SK   | 2         | 0.13%   |
| ru_UA   | 2         | 0.13%   |
| ja_JP   | 2         | 0.13%   |
| en_PH   | 2         | 0.13%   |
| en_NL   | 2         | 0.13%   |
| en_FI   | 2         | 0.13%   |
| en_CH   | 2         | 0.13%   |
| en_CA   | 2         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1009      | 64.64%  |
| BIOS | 552       | 35.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Btrfs    | 1060      | 67.73%  |
| Ext4     | 352       | 22.49%  |
| Xfs      | 72        | 4.6%    |
| Unknown  | 61        | 3.9%    |
| Overlay  | 13        | 0.83%   |
| Tmpfs    | 2         | 0.13%   |
| Ext3     | 2         | 0.13%   |
| Reiserfs | 1         | 0.06%   |
| F2fs     | 1         | 0.06%   |
| Ext2     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 895       | 56.79%  |
| Unknown | 521       | 33.06%  |
| MBR     | 160       | 10.15%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1309      | 82.9%   |
| Yes       | 270       | 17.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1113      | 70.85%  |
| Yes       | 458       | 29.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 248       | 16.04%  |
| Lenovo                  | 236       | 15.27%  |
| Hewlett-Packard         | 225       | 14.55%  |
| Dell                    | 187       | 12.1%   |
| Gigabyte Technology     | 124       | 8.02%   |
| MSI                     | 117       | 7.57%   |
| ASRock                  | 72        | 4.66%   |
| Acer                    | 64        | 4.14%   |
| Apple                   | 35        | 2.26%   |
| Toshiba                 | 19        | 1.23%   |
| Fujitsu                 | 19        | 1.23%   |
| TUXEDO                  | 16        | 1.03%   |
| Intel                   | 13        | 0.84%   |
| HUAWEI                  | 12        | 0.78%   |
| Sony                    | 11        | 0.71%   |
| Samsung Electronics     | 11        | 0.71%   |
| Supermicro              | 9         | 0.58%   |
| Biostar                 | 8         | 0.52%   |
| Pegatron                | 6         | 0.39%   |
| Medion                  | 6         | 0.39%   |
| Fujitsu Siemens         | 6         | 0.39%   |
| Notebook                | 5         | 0.32%   |
| Foxconn                 | 5         | 0.32%   |
| Alienware               | 5         | 0.32%   |
| Unknown                 | 5         | 0.32%   |
| Raspberry Pi Foundation | 4         | 0.26%   |
| Positivo                | 4         | 0.26%   |
| Timi                    | 3         | 0.19%   |
| Microsoft               | 3         | 0.19%   |
| LG Electronics          | 3         | 0.19%   |
| Google                  | 3         | 0.19%   |
| Clevo                   | 3         | 0.19%   |
| BESSTAR Tech            | 3         | 0.19%   |
| Avell High Performance  | 3         | 0.19%   |
| SLIMBOOK                | 2         | 0.13%   |
| Shuttle                 | 2         | 0.13%   |
| Semp Toshiba            | 2         | 0.13%   |
| Razer                   | 2         | 0.13%   |
| Getac                   | 2         | 0.13%   |
| Gateway                 | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| ASUS All Series                 | 19        | 1.23%   |
| Unknown                         | 10        | 0.65%   |
| MSI MS-7B86                     | 7         | 0.45%   |
| HP Notebook                     | 7         | 0.45%   |
| Dell OptiPlex 9020              | 7         | 0.45%   |
| MSI MS-7B89                     | 6         | 0.39%   |
| Dell Precision 5530             | 6         | 0.39%   |
| ASRock B450M Pro4               | 6         | 0.39%   |
| MSI MS-7C37                     | 5         | 0.32%   |
| HP Pavilion dv6                 | 5         | 0.32%   |
| Gigabyte B450M DS3H             | 5         | 0.32%   |
| Gigabyte 970A-DS3P              | 5         | 0.32%   |
| Dell Latitude 7490              | 5         | 0.32%   |
| ASUS TUF Gaming X570-PLUS       | 5         | 0.32%   |
| MSI MS-7C02                     | 4         | 0.26%   |
| MSI MS-7B79                     | 4         | 0.26%   |
| MSI MS-7A34                     | 4         | 0.26%   |
| HP Pavilion g6                  | 4         | 0.26%   |
| HP Pavilion dv7                 | 4         | 0.26%   |
| HP Laptop 17-ca0xxx             | 4         | 0.26%   |
| Gigabyte X570 AORUS MASTER      | 4         | 0.26%   |
| Gigabyte B450 AORUS M           | 4         | 0.26%   |
| Dell XPS 15 9560                | 4         | 0.26%   |
| ASUS M5A78L-M/USB3              | 4         | 0.26%   |
| Apple MacBookPro9,2             | 4         | 0.26%   |
| TUXEDO Pulse 15 Gen1            | 3         | 0.19%   |
| MSI MS-7A33                     | 3         | 0.19%   |
| Lenovo ThinkBook 14 G3 ACL 21A2 | 3         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM   | 3         | 0.19%   |
| HP Z840 Workstation             | 3         | 0.19%   |
| HP Z620 Workstation             | 3         | 0.19%   |
| HP ProLiant MicroServer         | 3         | 0.19%   |
| HP Laptop 15-bs0xx              | 3         | 0.19%   |
| HP Compaq Presario CQ40         | 3         | 0.19%   |
| Dell XPS 8700                   | 3         | 0.19%   |
| Dell XPS 15 9510                | 3         | 0.19%   |
| Dell Latitude E7470             | 3         | 0.19%   |
| Dell Latitude E6430             | 3         | 0.19%   |
| Dell Inspiron 5584              | 3         | 0.19%   |
| ASUS ROG STRIX X570-E GAMING    | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 132       | 8.54%   |
| Dell Inspiron      | 45        | 2.91%   |
| Dell Latitude      | 42        | 2.72%   |
| Acer Aspire        | 39        | 2.52%   |
| HP Pavilion        | 35        | 2.26%   |
| Lenovo IdeaPad     | 34        | 2.2%    |
| HP EliteBook       | 34        | 2.2%    |
| ASUS ROG           | 31        | 2.01%   |
| ASUS PRIME         | 31        | 2.01%   |
| ASUS TUF           | 27        | 1.75%   |
| Dell XPS           | 25        | 1.62%   |
| Dell OptiPlex      | 25        | 1.62%   |
| Dell Precision     | 21        | 1.36%   |
| HP Laptop          | 19        | 1.23%   |
| ASUS All           | 19        | 1.23%   |
| Toshiba Satellite  | 18        | 1.16%   |
| Lenovo Yoga        | 18        | 1.16%   |
| HP ProBook         | 17        | 1.1%    |
| HP ZBook           | 16        | 1.03%   |
| HP ENVY            | 15        | 0.97%   |
| Lenovo ThinkCentre | 14        | 0.91%   |
| ASUS VivoBook      | 14        | 0.91%   |
| HP Compaq          | 13        | 0.84%   |
| Gigabyte X570      | 12        | 0.78%   |
| Dell PowerEdge     | 11        | 0.71%   |
| Unknown            | 10        | 0.65%   |
| Fujitsu LIFEBOOK   | 9         | 0.58%   |
| HP OMEN            | 8         | 0.52%   |
| ASRock B450M       | 8         | 0.52%   |
| MSI MS-7B86        | 7         | 0.45%   |
| HP Notebook        | 7         | 0.45%   |
| Gigabyte B550      | 7         | 0.45%   |
| Gigabyte B450M     | 7         | 0.45%   |
| Gigabyte B450      | 7         | 0.45%   |
| Dell Vostro        | 7         | 0.45%   |
| ASUS ZenBook       | 7         | 0.45%   |
| ASUS M5A78L-M      | 7         | 0.45%   |
| Acer Swift         | 7         | 0.45%   |
| MSI MS-7B89        | 6         | 0.39%   |
| Fujitsu ESPRIMO    | 6         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 180       | 11.64%  |
| 2019 | 170       | 11%     |
| 2018 | 168       | 10.87%  |
| 2017 | 132       | 8.54%   |
| 2021 | 122       | 7.89%   |
| 2012 | 112       | 7.24%   |
| 2013 | 110       | 7.12%   |
| 2015 | 93        | 6.02%   |
| 2011 | 88        | 5.69%   |
| 2014 | 83        | 5.37%   |
| 2016 | 82        | 5.3%    |
| 2010 | 65        | 4.2%    |
| 2009 | 48        | 3.1%    |
| 2008 | 38        | 2.46%   |
| 2022 | 26        | 1.68%   |
| 2007 | 16        | 1.03%   |
| 2006 | 7         | 0.45%   |
| 2005 | 3         | 0.19%   |
| 2004 | 2         | 0.13%   |
| 2000 | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 781       | 50.52%  |
| Desktop        | 639       | 41.33%  |
| Convertible    | 51        | 3.3%    |
| Mini pc        | 24        | 1.55%   |
| Server         | 21        | 1.36%   |
| All in one     | 18        | 1.16%   |
| Tablet         | 6         | 0.39%   |
| System on chip | 5         | 0.32%   |
| Firewall       | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1349      | 85.98%  |
| Enabled  | 220       | 14.02%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1541      | 99.68%  |
| Yes  | 5         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 403       | 25.77%  |
| 4.01-8.0        | 340       | 21.74%  |
| 8.01-16.0       | 308       | 19.69%  |
| 32.01-64.0      | 222       | 14.19%  |
| 3.01-4.0        | 141       | 9.02%   |
| 64.01-256.0     | 64        | 4.09%   |
| 24.01-32.0      | 35        | 2.24%   |
| 1.01-2.0        | 22        | 1.41%   |
| 2.01-3.0        | 11        | 0.7%    |
| Unknown         | 10        | 0.64%   |
| 0.51-1.0        | 6         | 0.38%   |
| More than 256.0 | 1         | 0.06%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 422       | 25.04%  |
| 4.01-8.0   | 405       | 24.04%  |
| 1.01-2.0   | 372       | 22.08%  |
| 3.01-4.0   | 271       | 16.08%  |
| 8.01-16.0  | 109       | 6.47%   |
| 0.51-1.0   | 61        | 3.62%   |
| 16.01-24.0 | 15        | 0.89%   |
| 0.01-0.5   | 13        | 0.77%   |
| Unknown    | 10        | 0.59%   |
| 24.01-32.0 | 6         | 0.36%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 767       | 48.36%  |
| 2       | 441       | 27.81%  |
| 3       | 170       | 10.72%  |
| 4       | 96        | 6.05%   |
| 5       | 52        | 3.28%   |
| 6       | 31        | 1.95%   |
| 7       | 15        | 0.95%   |
| 8       | 3         | 0.19%   |
| 0       | 3         | 0.19%   |
| 13      | 2         | 0.13%   |
| 10      | 2         | 0.13%   |
| 35      | 1         | 0.06%   |
| 16      | 1         | 0.06%   |
| 9       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 976       | 62.72%  |
| Yes       | 580       | 37.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1369      | 88.49%  |
| No        | 178       | 11.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1132      | 72.94%  |
| No        | 420       | 27.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 969       | 61.92%  |
| No        | 596       | 38.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 277       | 17.86%  |
| Germany     | 276       | 17.79%  |
| Brazil      | 93        | 6%      |
| Russia      | 76        | 4.9%    |
| France      | 57        | 3.68%   |
| Italy       | 55        | 3.55%   |
| UK          | 54        | 3.48%   |
| Netherlands | 53        | 3.42%   |
| Spain       | 40        | 2.58%   |
| Switzerland | 37        | 2.39%   |
| Poland      | 34        | 2.19%   |
| Canada      | 32        | 2.06%   |
| India       | 27        | 1.74%   |
| Sweden      | 26        | 1.68%   |
| Austria     | 24        | 1.55%   |
| Mexico      | 22        | 1.42%   |
| Belgium     | 22        | 1.42%   |
| Australia   | 21        | 1.35%   |
| China       | 20        | 1.29%   |
| Czechia     | 19        | 1.23%   |
| Hungary     | 17        | 1.1%    |
| Norway      | 16        | 1.03%   |
| Finland     | 16        | 1.03%   |
| Portugal    | 15        | 0.97%   |
| Ukraine     | 14        | 0.9%    |
| Turkey      | 12        | 0.77%   |
| Romania     | 12        | 0.77%   |
| Serbia      | 11        | 0.71%   |
| Bulgaria    | 11        | 0.71%   |
| Greece      | 9         | 0.58%   |
| Chile       | 8         | 0.52%   |
| Belarus     | 8         | 0.52%   |
| Argentina   | 8         | 0.52%   |
| Peru        | 7         | 0.45%   |
| Croatia     | 7         | 0.45%   |
| Luxembourg  | 6         | 0.39%   |
| Japan       | 6         | 0.39%   |
| Israel      | 6         | 0.39%   |
| Indonesia   | 6         | 0.39%   |
| Thailand    | 5         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 23        | 1.41%   |
| Berlin            | 23        | 1.41%   |
| Vienna            | 15        | 0.92%   |
| Rio de Janeiro    | 13        | 0.8%    |
| Paris             | 12        | 0.74%   |
| Munich            | 12        | 0.74%   |
| Zurich            | 11        | 0.67%   |
| Sao Paulo         | 11        | 0.67%   |
| Amsterdam         | 11        | 0.67%   |
| Littleton         | 10        | 0.61%   |
| Budapest          | 10        | 0.61%   |
| Prague            | 9         | 0.55%   |
| Neuchatel         | 9         | 0.55%   |
| Frankfurt am Main | 9         | 0.55%   |
| Warsaw            | 8         | 0.49%   |
| Rome              | 8         | 0.49%   |
| Riverton          | 8         | 0.49%   |
| Milan             | 8         | 0.49%   |
| Madrid            | 8         | 0.49%   |
| Los Angeles       | 8         | 0.49%   |
| Sydney            | 7         | 0.43%   |
| St Petersburg     | 7         | 0.43%   |
| Sofia             | 7         | 0.43%   |
| Montreal          | 7         | 0.43%   |
| Hamburg           | 7         | 0.43%   |
| Gothenburg        | 7         | 0.43%   |
| Bengaluru         | 7         | 0.43%   |
| Belgrade          | 7         | 0.43%   |
| Schrobenhausen    | 6         | 0.37%   |
| Houston           | 6         | 0.37%   |
| Halle             | 6         | 0.37%   |
| The Hague         | 5         | 0.31%   |
| Santiago          | 5         | 0.31%   |
| San Jose          | 5         | 0.31%   |
| Minsk             | 5         | 0.31%   |
| Lisbon            | 5         | 0.31%   |
| Leipzig           | 5         | 0.31%   |
| Haßfurt          | 5         | 0.31%   |
| Hanau             | 5         | 0.31%   |
| Essen             | 5         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 519       | 797    | 20.13%  |
| Seagate                   | 390       | 703    | 15.13%  |
| WDC                       | 388       | 654    | 15.05%  |
| Toshiba                   | 162       | 210    | 6.28%   |
| Kingston                  | 137       | 177    | 5.31%   |
| SanDisk                   | 125       | 152    | 4.85%   |
| Crucial                   | 107       | 144    | 4.15%   |
| Intel                     | 73        | 88     | 2.83%   |
| SK hynix                  | 65        | 90     | 2.52%   |
| Unknown                   | 61        | 91     | 2.37%   |
| Hitachi                   | 51        | 62     | 1.98%   |
| HGST                      | 46        | 64     | 1.78%   |
| A-DATA Technology         | 34        | 46     | 1.32%   |
| Micron Technology         | 29        | 38     | 1.12%   |
| PNY                       | 23        | 31     | 0.89%   |
| Phison                    | 23        | 31     | 0.89%   |
| KIOXIA                    | 17        | 17     | 0.66%   |
| Intenso                   | 16        | 22     | 0.62%   |
| SPCC                      | 15        | 19     | 0.58%   |
| Silicon Motion            | 15        | 16     | 0.58%   |
| Apple                     | 15        | 18     | 0.58%   |
| China                     | 13        | 14     | 0.5%    |
| Hewlett-Packard           | 12        | 17     | 0.47%   |
| Fujitsu                   | 12        | 15     | 0.47%   |
| Transcend                 | 11        | 12     | 0.43%   |
| LITEON                    | 11        | 12     | 0.43%   |
| Corsair                   | 11        | 12     | 0.43%   |
| OCZ                       | 8         | 13     | 0.31%   |
| GOODRAM                   | 8         | 8      | 0.31%   |
| XPG                       | 7         | 9      | 0.27%   |
| Micron/Crucial Technology | 7         | 13     | 0.27%   |
| Team                      | 6         | 6      | 0.23%   |
| Phison Electronics        | 6         | 10     | 0.23%   |
| Maxtor                    | 6         | 6      | 0.23%   |
| LITEONIT                  | 6         | 6      | 0.23%   |
| JMicron Technology        | 6         | 6      | 0.23%   |
| SABRENT                   | 5         | 6      | 0.19%   |
| Plextor                   | 5         | 6      | 0.19%   |
| Mushkin                   | 5         | 8      | 0.19%   |
| Gigabyte Technology       | 5         | 10     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                         | 41        | 1.39%   |
| Samsung SSD 850 EVO 250GB                         | 30        | 1.02%   |
| Samsung SSD 860 EVO 1TB                           | 25        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 22        | 0.75%   |
| Seagate ST2000DM008-2FR102 2TB                    | 20        | 0.68%   |
| HGST HTS721010A9E630 1TB                          | 19        | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB                      | 18        | 0.61%   |
| Samsung SSD 850 EVO 500GB                         | 18        | 0.61%   |
| Kingston SA400S37240G 240GB SSD                   | 18        | 0.61%   |
| Crucial CT500MX500SSD1 500GB                      | 18        | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB                    | 17        | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 16        | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 15        | 0.51%   |
| Samsung SSD 970 EVO 500GB                         | 15        | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB                    | 14        | 0.48%   |
| Samsung SSD 860 EVO 250GB                         | 14        | 0.48%   |
| Samsung NVMe SSD Drive 1TB                        | 14        | 0.48%   |
| Kingston SA400S37120G 120GB SSD                   | 14        | 0.48%   |
| Unknown SD/MMC/MS PRO 8GB                         | 13        | 0.44%   |
| Seagate ST2000DM001-1ER164 2TB                    | 13        | 0.44%   |
| Seagate ST1000DM010-2EP102 1TB                    | 13        | 0.44%   |
| Samsung SSD 860 QVO 1TB                           | 13        | 0.44%   |
| Samsung SSD 850 PRO 256GB                         | 13        | 0.44%   |
| Samsung SSD 840 EVO 250GB                         | 13        | 0.44%   |
| Samsung NVMe SSD Drive 500GB                      | 13        | 0.44%   |
| Toshiba MQ04ABF100 1TB                            | 12        | 0.41%   |
| Seagate ST500DM002-1BD142 500GB                   | 12        | 0.41%   |
| Seagate ST3500418AS 500GB                         | 12        | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB                    | 12        | 0.41%   |
| Samsung NVMe SSD Drive 512GB                      | 12        | 0.41%   |
| Kingston SA400S37480G 480GB SSD                   | 12        | 0.41%   |
| Crucial CT240BX500SSD1 240GB                      | 12        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 11        | 0.37%   |
| Toshiba MQ01ABD100 1TB                            | 11        | 0.37%   |
| Toshiba DT01ACA100 1TB                            | 11        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                       | 11        | 0.37%   |
| Toshiba DT01ACA200 2TB                            | 10        | 0.34%   |
| Seagate Expansion Desk 8TB                        | 10        | 0.34%   |
| Seagate Expansion 1TB                             | 10        | 0.34%   |
| Samsung SSD 970 EVO 1TB                           | 10        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 384       | 685    | 37.8%   |
| WDC                 | 305       | 514    | 30.02%  |
| Toshiba             | 117       | 154    | 11.52%  |
| Samsung Electronics | 54        | 81     | 5.31%   |
| Hitachi             | 51        | 62     | 5.02%   |
| HGST                | 46        | 64     | 4.53%   |
| Unknown             | 14        | 15     | 1.38%   |
| Fujitsu             | 12        | 15     | 1.18%   |
| Maxtor              | 5         | 5      | 0.49%   |
| Hewlett-Packard     | 5         | 8      | 0.49%   |
| Apple               | 5         | 7      | 0.49%   |
| WD MediaMax         | 2         | 2      | 0.2%    |
| JMicron Technology  | 2         | 2      | 0.2%    |
| Intenso             | 2         | 7      | 0.2%    |
| ASMT                | 2         | 3      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| USB                 | 1         | 1      | 0.1%    |
| UD0401              | 1         | 1      | 0.1%    |
| Synology            | 1         | 1      | 0.1%    |
| MaxDigital          | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 2      | 0.1%    |
| Inateck             | 1         | 1      | 0.1%    |
| IBM-207x            | 1         | 8      | 0.1%    |
| DELLBOSS            | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 270       | 394    | 29.61%  |
| Kingston            | 101       | 133    | 11.07%  |
| Crucial             | 95        | 127    | 10.42%  |
| SanDisk             | 92        | 110    | 10.09%  |
| WDC                 | 62        | 77     | 6.8%    |
| A-DATA Technology   | 24        | 31     | 2.63%   |
| Intel               | 21        | 25     | 2.3%    |
| PNY                 | 18        | 22     | 1.97%   |
| Toshiba             | 17        | 21     | 1.86%   |
| SK hynix            | 17        | 27     | 1.86%   |
| Micron Technology   | 15        | 23     | 1.64%   |
| China               | 13        | 14     | 1.43%   |
| Intenso             | 12        | 12     | 1.32%   |
| LITEON              | 11        | 12     | 1.21%   |
| SPCC                | 10        | 14     | 1.1%    |
| Transcend           | 8         | 9      | 0.88%   |
| OCZ                 | 8         | 13     | 0.88%   |
| Apple               | 8         | 9      | 0.88%   |
| GOODRAM             | 7         | 7      | 0.77%   |
| Corsair             | 7         | 7      | 0.77%   |
| Seagate             | 6         | 7      | 0.66%   |
| LITEONIT            | 6         | 6      | 0.66%   |
| Team                | 5         | 5      | 0.55%   |
| Plextor             | 4         | 5      | 0.44%   |
| Patriot             | 4         | 4      | 0.44%   |
| Mushkin             | 4         | 6      | 0.44%   |
| KingSpec            | 4         | 9      | 0.44%   |
| Hewlett-Packard     | 4         | 6      | 0.44%   |
| TO Exter            | 3         | 3      | 0.33%   |
| Pioneer             | 3         | 7      | 0.33%   |
| JMicron Technology  | 3         | 3      | 0.33%   |
| Biostar             | 3         | 5      | 0.33%   |
| Smart               | 2         | 2      | 0.22%   |
| Netac               | 2         | 2      | 0.22%   |
| MyDigitalSSD        | 2         | 2      | 0.22%   |
| Gigabyte Technology | 2         | 4      | 0.22%   |
| GALAX               | 2         | 2      | 0.22%   |
| Apacer              | 2         | 4      | 0.22%   |
| Advantech           | 2         | 2      | 0.22%   |
| Unknown             | 2         | 2      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 809       | 1642   | 35.8%   |
| SSD     | 777       | 1208   | 34.38%  |
| NVMe    | 606       | 862    | 26.81%  |
| MMC     | 45        | 65     | 1.99%   |
| Unknown | 23        | 33     | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1183      | 2749   | 61.42%  |
| NVMe | 603       | 855    | 31.31%  |
| SAS  | 95        | 141    | 4.93%   |
| MMC  | 45        | 65     | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 871       | 1424   | 50.32%  |
| 0.51-1.0   | 515       | 829    | 29.75%  |
| 1.01-2.0   | 184       | 322    | 10.63%  |
| 2.01-3.0   | 61        | 93     | 3.52%   |
| 3.01-4.0   | 54        | 88     | 3.12%   |
| 4.01-10.0  | 42        | 85     | 2.43%   |
| 10.01-20.0 | 4         | 9      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 469       | 29.08%  |
| 1001-2000      | 346       | 21.45%  |
| 501-1000       | 235       | 14.57%  |
| 2001-3000      | 217       | 13.45%  |
| 251-500        | 156       | 9.67%   |
| 101-250        | 99        | 6.14%   |
| Unknown        | 39        | 2.42%   |
| 51-100         | 25        | 1.55%   |
| 1-20           | 16        | 0.99%   |
| 21-50          | 11        | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 317       | 18.87%  |
| 251-500        | 304       | 18.1%   |
| 501-1000       | 235       | 13.99%  |
| 51-100         | 222       | 13.21%  |
| 1001-2000      | 217       | 12.92%  |
| More than 3000 | 103       | 6.13%   |
| 1-20           | 95        | 5.65%   |
| 2001-3000      | 81        | 4.82%   |
| 21-50          | 67        | 3.99%   |
| Unknown        | 39        | 2.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 5         | 7      | 2.18%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 1.75%   |
| Samsung Electronics SSD 840 EVO 120GB | 4         | 5      | 1.75%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.75%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 3      | 1.31%   |
| Seagate ST2000DM001-1CH164 2TB        | 3         | 4      | 1.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 1.31%   |
| Seagate ST1000DM003-1SB102 1TB        | 3         | 3      | 1.31%   |
| Samsung Electronics HD501LJ 500GB     | 3         | 4      | 1.31%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2         | 3      | 0.87%   |
| WDC WD10JFCX-68N6GN0 1TB              | 2         | 3      | 0.87%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.87%   |
| Toshiba MK5055GSX 500GB               | 2         | 3      | 0.87%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.87%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.87%   |
| Seagate ST31000528AS 1TB              | 2         | 5      | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 0.87%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 2         | 2      | 0.87%   |
| Samsung Electronics HN-M500MBB 500GB  | 2         | 2      | 0.87%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 0.87%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 3      | 0.87%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3      | 0.87%   |
| Kingston SMS200S3240G 240GB SSD       | 2         | 2      | 0.87%   |
| Kingston SHFS37A120G 120GB SSD        | 2         | 2      | 0.87%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.87%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 0.87%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.87%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 0.87%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 0.44%   |
| XPG GAMMIX S41 512GB                  | 1         | 1      | 0.44%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.44%   |
| WDC WD800AAJS-75M0A0 80GB             | 1         | 1      | 0.44%   |
| WDC WD7500AAKS-00RBA0 752GB           | 1         | 1      | 0.44%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 0.44%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.44%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 0.44%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.44%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 0.44%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.44%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 1      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 74     | 26.34%  |
| WDC                 | 36        | 42     | 16.07%  |
| Samsung Electronics | 30        | 37     | 13.39%  |
| Toshiba             | 22        | 31     | 9.82%   |
| Kingston            | 10        | 14     | 4.46%   |
| Hitachi             | 10        | 11     | 4.46%   |
| Crucial             | 8         | 9      | 3.57%   |
| HGST                | 7         | 7      | 3.13%   |
| SanDisk             | 6         | 6      | 2.68%   |
| Intel               | 6         | 7      | 2.68%   |
| Maxtor              | 3         | 3      | 1.34%   |
| SK hynix            | 2         | 2      | 0.89%   |
| OCZ                 | 2         | 2      | 0.89%   |
| LITEONIT            | 2         | 2      | 0.89%   |
| Fujitsu             | 2         | 3      | 0.89%   |
| Corsair             | 2         | 2      | 0.89%   |
| XrayDisk            | 1         | 1      | 0.45%   |
| XPG                 | 1         | 1      | 0.45%   |
| WD MediaMax         | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| SuperTalent         | 1         | 1      | 0.45%   |
| SSSTC               | 1         | 1      | 0.45%   |
| SPCC                | 1         | 1      | 0.45%   |
| Phison              | 1         | 1      | 0.45%   |
| Patriot             | 1         | 1      | 0.45%   |
| Micron Technology   | 1         | 1      | 0.45%   |
| LEQIXIANG           | 1         | 1      | 0.45%   |
| KingFast            | 1         | 1      | 0.45%   |
| Intenso             | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| GOODRAM             | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| A-DATA Technology   | 1         | 2      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 74     | 37.82%  |
| WDC                 | 35        | 41     | 22.44%  |
| Toshiba             | 21        | 30     | 13.46%  |
| Samsung Electronics | 16        | 22     | 10.26%  |
| Hitachi             | 10        | 11     | 6.41%   |
| HGST                | 7         | 7      | 4.49%   |
| Maxtor              | 3         | 3      | 1.92%   |
| Fujitsu             | 2         | 3      | 1.28%   |
| WD MediaMax         | 1         | 1      | 0.64%   |
| Hewlett-Packard     | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 141       | 194    | 68.12%  |
| SSD  | 55        | 65     | 26.57%  |
| NVMe | 11        | 11     | 5.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1         | 3      | 33.33%  |
| Hitachi HDS721025CLA382 250GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 3      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 973       | 2072   | 55.13%  |
| Detected | 589       | 1463   | 33.37%  |
| Malfunc  | 200       | 270    | 11.33%  |
| Failed   | 3         | 5      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 935       | 43.92%  |
| AMD                              | 422       | 19.82%  |
| Samsung Electronics              | 237       | 11.13%  |
| SanDisk                          | 83        | 3.9%    |
| ASMedia Technology               | 53        | 2.49%   |
| SK hynix                         | 48        | 2.25%   |
| Kingston Technology Company      | 42        | 1.97%   |
| Phison Electronics               | 41        | 1.93%   |
| Toshiba America Info Systems     | 33        | 1.55%   |
| Marvell Technology Group         | 27        | 1.27%   |
| JMicron Technology               | 23        | 1.08%   |
| Nvidia                           | 22        | 1.03%   |
| Silicon Motion                   | 21        | 0.99%   |
| Micron/Crucial Technology        | 19        | 0.89%   |
| Micron Technology                | 15        | 0.7%    |
| KIOXIA                           | 15        | 0.7%    |
| LSI Logic / Symbios Logic        | 14        | 0.66%   |
| ADATA Technology                 | 14        | 0.66%   |
| Broadcom / LSI                   | 11        | 0.52%   |
| Realtek Semiconductor            | 7         | 0.33%   |
| Silicon Image                    | 5         | 0.23%   |
| VIA Technologies                 | 4         | 0.19%   |
| Union Memory (Shenzhen)          | 4         | 0.19%   |
| Seagate Technology               | 4         | 0.19%   |
| Adaptec                          | 4         | 0.19%   |
| Solid State Storage Technology   | 3         | 0.14%   |
| Shenzhen Longsys Electronics     | 3         | 0.14%   |
| Lite-On Technology               | 3         | 0.14%   |
| Lenovo                           | 3         | 0.14%   |
| Yangtze Memory Technologies      | 2         | 0.09%   |
| Promise Technology               | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.09%   |
| Apple                            | 2         | 0.09%   |
| Tekram Technology                | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| ATTO Technology                  | 1         | 0.05%   |
| 3ware                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 292       | 11.93%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 139       | 5.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 83        | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 80        | 3.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 71        | 2.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 62        | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 53        | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 49        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 48        | 1.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 46        | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 41        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 40        | 1.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 34        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 33        | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 32        | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 31        | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 31        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                | 30        | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 30        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 29        | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 28        | 1.14%   |
| Phison E12 NVMe Controller                                                     | 26        | 1.06%   |
| Intel SSD 660P Series                                                          | 26        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 24        | 0.98%   |
| AMD 300 Series Chipset SATA Controller                                         | 24        | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 23        | 0.94%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 22        | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 22        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 21        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 20        | 0.82%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 18        | 0.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 0.65%   |
| AMD X370 Series Chipset SATA Controller                                        | 16        | 0.65%   |
| Micron Non-Volatile memory controller                                          | 15        | 0.61%   |
| JMicron JMB363 SATA/IDE Controller                                             | 15        | 0.61%   |
| Intel SATA Controller [RAID mode]                                              | 15        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1206      | 56.99%  |
| NVMe | 597       | 28.21%  |
| IDE  | 169       | 7.99%   |
| RAID | 122       | 5.77%   |
| SAS  | 11        | 0.52%   |
| SCSI | 11        | 0.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1031      | 66.69%  |
| AMD    | 509       | 32.92%  |
| ARM    | 6         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 1.03%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 16        | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 0.97%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 15        | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.9%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 14        | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.84%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 13        | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.71%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 11        | 0.71%   |
| AMD FX-8350 Eight-Core Processor              | 11        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.65%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 10        | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.58%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 9         | 0.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 8         | 0.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 8         | 0.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.52%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 8         | 0.52%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 8         | 0.52%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.52%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 7         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 340       | 21.96%  |
| Intel Core i5           | 315       | 20.35%  |
| AMD Ryzen 5             | 142       | 9.17%   |
| AMD Ryzen 7             | 111       | 7.17%   |
| Other                   | 90        | 5.81%   |
| Intel Core i3           | 74        | 4.78%   |
| Intel Xeon              | 56        | 3.62%   |
| Intel Core 2 Duo        | 43        | 2.78%   |
| AMD Ryzen 9             | 43        | 2.78%   |
| Intel Celeron           | 35        | 2.26%   |
| AMD FX                  | 35        | 2.26%   |
| Intel Pentium           | 21        | 1.36%   |
| AMD Ryzen 3             | 20        | 1.29%   |
| Intel Core i9           | 16        | 1.03%   |
| AMD Ryzen 7 PRO         | 16        | 1.03%   |
| AMD Phenom II X4        | 14        | 0.9%    |
| AMD A8                  | 14        | 0.9%    |
| Intel Pentium Dual-Core | 12        | 0.78%   |
| Intel Atom              | 12        | 0.78%   |
| AMD A10                 | 11        | 0.71%   |
| AMD Athlon              | 10        | 0.65%   |
| AMD A6                  | 10        | 0.65%   |
| AMD Ryzen 5 PRO         | 9         | 0.58%   |
| AMD Phenom II X6        | 8         | 0.52%   |
| Intel Pentium Silver    | 7         | 0.45%   |
| Intel Core 2 Quad       | 7         | 0.45%   |
| AMD Athlon II X2        | 7         | 0.45%   |
| AMD A4                  | 6         | 0.39%   |
| Intel Core 2            | 5         | 0.32%   |
| AMD Ryzen Threadripper  | 5         | 0.32%   |
| AMD Opteron             | 5         | 0.32%   |
| AMD E2                  | 5         | 0.32%   |
| Intel Genuine           | 3         | 0.19%   |
| AMD E                   | 3         | 0.19%   |
| Intel Pentium Dual      | 2         | 0.13%   |
| Intel Core m3           | 2         | 0.13%   |
| Intel Core M            | 2         | 0.13%   |
| AMD Turion II Neo       | 2         | 0.13%   |
| AMD Ryzen 3 PRO         | 2         | 0.13%   |
| AMD EPYC                | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 574       | 37.03%  |
| 2       | 494       | 31.87%  |
| 6       | 199       | 12.84%  |
| 8       | 169       | 10.9%   |
| 12      | 30        | 1.94%   |
| 16      | 21        | 1.35%   |
| 1       | 21        | 1.35%   |
| 3       | 11        | 0.71%   |
| 10      | 8         | 0.52%   |
| 32      | 4         | 0.26%   |
| Unknown | 4         | 0.26%   |
| 40      | 3         | 0.19%   |
| 24      | 3         | 0.19%   |
| 14      | 3         | 0.19%   |
| 20      | 2         | 0.13%   |
| 64      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 44      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1514      | 97.87%  |
| 2       | 26        | 1.68%   |
| 4       | 4         | 0.26%   |
| Unknown | 3         | 0.19%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1151      | 74.26%  |
| 1       | 394       | 25.42%  |
| Unknown | 4         | 0.26%   |
| 8       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1489      | 95.94%  |
| Unknown        | 55        | 3.54%   |
| 32-bit         | 7         | 0.45%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 8.88%   |
| 0x306c3    | 89        | 5.65%   |
| 0x206a7    | 87        | 5.52%   |
| 0x306a9    | 83        | 5.27%   |
| 0x506e3    | 53        | 3.36%   |
| 0x906ea    | 50        | 3.17%   |
| 0x806c1    | 47        | 2.98%   |
| 0x406e3    | 47        | 2.98%   |
| 0x08701021 | 43        | 2.73%   |
| 0x806ec    | 41        | 2.6%    |
| 0x806ea    | 37        | 2.35%   |
| 0x906e9    | 36        | 2.28%   |
| 0x0800820d | 36        | 2.28%   |
| 0x806e9    | 34        | 2.16%   |
| 0x0a50000c | 34        | 2.16%   |
| 0x1067a    | 33        | 2.09%   |
| 0x40651    | 30        | 1.9%    |
| 0x306d4    | 30        | 1.9%    |
| 0x08600106 | 27        | 1.71%   |
| 0x08108109 | 27        | 1.71%   |
| 0x06000852 | 26        | 1.65%   |
| 0x20655    | 21        | 1.33%   |
| 0x010000c8 | 20        | 1.27%   |
| 0x08701013 | 17        | 1.08%   |
| 0x08001138 | 17        | 1.08%   |
| 0x0a201009 | 16        | 1.02%   |
| 0x08600104 | 16        | 1.02%   |
| 0x08108102 | 15        | 0.95%   |
| 0x08608103 | 14        | 0.89%   |
| 0x806eb    | 13        | 0.82%   |
| 0x06001119 | 13        | 0.82%   |
| 0x706a8    | 12        | 0.76%   |
| 0x08001137 | 12        | 0.76%   |
| 0x706a1    | 11        | 0.7%    |
| 0x6fd      | 11        | 0.7%    |
| 0x0810100b | 11        | 0.7%    |
| 0x06006705 | 11        | 0.7%    |
| 0x906ed    | 10        | 0.63%   |
| 0x706e5    | 10        | 0.63%   |
| 0x306f2    | 10        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 250       | 16.14%  |
| Haswell          | 147       | 9.49%   |
| Zen 2            | 119       | 7.68%   |
| Skylake          | 113       | 7.3%    |
| IvyBridge        | 100       | 6.46%   |
| SandyBridge      | 95        | 6.13%   |
| Zen+             | 84        | 5.42%   |
| Zen 3            | 73        | 4.71%   |
| Zen              | 60        | 3.87%   |
| Penryn           | 50        | 3.23%   |
| TigerLake        | 47        | 3.03%   |
| Piledriver       | 43        | 2.78%   |
| K10              | 40        | 2.58%   |
| Broadwell        | 35        | 2.26%   |
| Westmere         | 34        | 2.19%   |
| Unknown          | 30        | 1.94%   |
| CometLake        | 27        | 1.74%   |
| IceLake          | 26        | 1.68%   |
| Core             | 26        | 1.68%   |
| Goldmont plus    | 23        | 1.48%   |
| Nehalem          | 19        | 1.23%   |
| Excavator        | 19        | 1.23%   |
| Silvermont       | 11        | 0.71%   |
| Alderlake Hybrid | 11        | 0.71%   |
| Bulldozer        | 8         | 0.52%   |
| Bobcat           | 8         | 0.52%   |
| Steamroller      | 7         | 0.45%   |
| Puma             | 7         | 0.45%   |
| Jaguar           | 7         | 0.45%   |
| Bonnell          | 7         | 0.45%   |
| K10 Llano        | 6         | 0.39%   |
| Goldmont         | 5         | 0.32%   |
| K8 Hammer        | 4         | 0.26%   |
| P6               | 3         | 0.19%   |
| K8 & K10 hybrid  | 3         | 0.19%   |
| Tremont          | 1         | 0.06%   |
| NetBurst         | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 760       | 41.85%  |
| AMD                        | 530       | 29.19%  |
| Nvidia                     | 507       | 27.92%  |
| Matrox Electronics Systems | 13        | 0.72%   |
| ASPEED Technology          | 3         | 0.17%   |
| S3 Graphics                | 2         | 0.11%   |
| VIA Technologies           | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 62        | 3.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 59        | 3.14%   |
| AMD Renoir                                                                            | 54        | 2.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 52        | 2.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 48        | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 44        | 2.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 42        | 2.24%   |
| Intel UHD Graphics 620                                                                | 39        | 2.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 38        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 36        | 1.92%   |
| Intel HD Graphics 620                                                                 | 36        | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 36        | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 35        | 1.86%   |
| Intel HD Graphics 530                                                                 | 32        | 1.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 32        | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 31        | 1.65%   |
| Intel HD Graphics 630                                                                 | 31        | 1.65%   |
| Intel HD Graphics 5500                                                                | 24        | 1.28%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 22        | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 21        | 1.12%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 21        | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                                   | 20        | 1.07%   |
| AMD Lucienne                                                                          | 18        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 16        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 16        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 14        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 13        | 0.69%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 13        | 0.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 13        | 0.69%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 13        | 0.69%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 13        | 0.69%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 12        | 0.64%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 11        | 0.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 11        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 10        | 0.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 10        | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 9         | 0.48%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 9         | 0.48%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 9         | 0.48%   |
| Nvidia GK208B [GeForce GT 730]                                                        | 9         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 520       | 33.48%  |
| 1 x AMD            | 434       | 27.95%  |
| 1 x Nvidia         | 280       | 18.03%  |
| Intel + Nvidia     | 184       | 11.85%  |
| Intel + AMD        | 36        | 2.32%   |
| AMD + Nvidia       | 31        | 2%      |
| 2 x AMD            | 30        | 1.93%   |
| 1 x Matrox         | 10        | 0.64%   |
| Other              | 8         | 0.52%   |
| 2 x Nvidia         | 7         | 0.45%   |
| 2 x Intel          | 3         | 0.19%   |
| Nvidia + ASPEED    | 3         | 0.19%   |
| 1 x S3 Graphics    | 2         | 0.13%   |
| Nvidia + Matrox    | 2         | 0.13%   |
| 1 x VIA            | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |
| AMD + Matrox       | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1236      | 78.88%  |
| Proprietary | 298       | 19.02%  |
| Unknown     | 33        | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 719       | 45.54%  |
| 1.01-2.0   | 205       | 12.98%  |
| 0.01-0.5   | 192       | 12.16%  |
| 3.01-4.0   | 135       | 8.55%   |
| 0.51-1.0   | 119       | 7.54%   |
| 7.01-8.0   | 114       | 7.22%   |
| 5.01-6.0   | 44        | 2.79%   |
| 8.01-16.0  | 32        | 2.03%   |
| 2.01-3.0   | 12        | 0.76%   |
| 16.01-24.0 | 6         | 0.38%   |
| 4.01-5.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 224       | 12.4%   |
| AU Optronics            | 197       | 10.9%   |
| LG Display              | 144       | 7.97%   |
| Dell                    | 139       | 7.69%   |
| Chimei Innolux          | 135       | 7.47%   |
| BOE                     | 127       | 7.03%   |
| Goldstar                | 109       | 6.03%   |
| Hewlett-Packard         | 78        | 4.32%   |
| Ancor Communications    | 62        | 3.43%   |
| Acer                    | 60        | 3.32%   |
| BenQ                    | 59        | 3.27%   |
| AOC                     | 46        | 2.55%   |
| Lenovo                  | 40        | 2.21%   |
| Philips                 | 37        | 2.05%   |
| Sharp                   | 33        | 1.83%   |
| Apple                   | 30        | 1.66%   |
| Iiyama                  | 20        | 1.11%   |
| ASUSTek Computer        | 19        | 1.05%   |
| ViewSonic               | 15        | 0.83%   |
| PANDA                   | 15        | 0.83%   |
| InfoVision              | 15        | 0.83%   |
| Fujitsu Siemens         | 14        | 0.77%   |
| Unknown                 | 13        | 0.72%   |
| Chi Mei Optoelectronics | 12        | 0.66%   |
| LG Electronics          | 11        | 0.61%   |
| Eizo                    | 10        | 0.55%   |
| Vizio                   | 8         | 0.44%   |
| Sony                    | 8         | 0.44%   |
| Sceptre Tech            | 7         | 0.39%   |
| LG Philips              | 7         | 0.39%   |
| Panasonic               | 6         | 0.33%   |
| NEC Computers           | 5         | 0.28%   |
| CSO                     | 5         | 0.28%   |
| Pixio                   | 4         | 0.22%   |
| MSI                     | 4         | 0.22%   |
| Medion                  | 4         | 0.22%   |
| HannStar                | 4         | 0.22%   |
| CPT                     | 4         | 0.22%   |
| Toshiba                 | 3         | 0.17%   |
| TMX                     | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 9         | 0.47%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                  | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 9         | 0.47%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.42%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 7         | 0.37%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch    | 6         | 0.31%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 6         | 0.31%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 6         | 0.31%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 6         | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6         | 0.31%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 6         | 0.31%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 5         | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 5         | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.26%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch              | 5         | 0.26%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                     | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 5         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 5         | 0.26%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 4         | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 4         | 0.21%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch    | 4         | 0.21%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch    | 4         | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch              | 4         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 4         | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 0.21%   |
| Hewlett-Packard 27fh HPN354A 1920x1080 598x336mm 27.0-inch           | 4         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 4         | 0.21%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 4         | 0.21%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                   | 4         | 0.21%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                     | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 840       | 48.41%  |
| 1366x768 (WXGA)    | 208       | 11.99%  |
| 2560x1440 (QHD)    | 123       | 7.09%   |
| 3840x2160 (4K)     | 113       | 6.51%   |
| 1600x900 (HD+)     | 65        | 3.75%   |
| 1920x1200 (WUXGA)  | 48        | 2.77%   |
| 1680x1050 (WSXGA+) | 45        | 2.59%   |
| 1280x1024 (SXGA)   | 44        | 2.54%   |
| 1440x900 (WXGA+)   | 33        | 1.9%    |
| 1280x800 (WXGA)    | 31        | 1.79%   |
| 2560x1080          | 28        | 1.61%   |
| Unknown            | 25        | 1.44%   |
| 3440x1440          | 21        | 1.21%   |
| 3840x1080          | 15        | 0.86%   |
| 1024x768 (XGA)     | 13        | 0.75%   |
| 2560x1600          | 9         | 0.52%   |
| 2880x1800          | 7         | 0.4%    |
| 3200x1800 (QHD+)   | 6         | 0.35%   |
| 1360x768           | 6         | 0.35%   |
| 3840x1200          | 4         | 0.23%   |
| 2160x1440          | 4         | 0.23%   |
| 1024x600           | 4         | 0.23%   |
| 3840x2400          | 3         | 0.17%   |
| 1600x1200          | 3         | 0.17%   |
| 1280x720 (HD)      | 3         | 0.17%   |
| 3840x1600          | 2         | 0.12%   |
| 3456x2160          | 2         | 0.12%   |
| 2048x1536          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |
| 1280x960           | 2         | 0.12%   |
| 8960x2160          | 1         | 0.06%   |
| 800x1280           | 1         | 0.06%   |
| 7680x1440          | 1         | 0.06%   |
| 7280x2160          | 1         | 0.06%   |
| 6520x1440          | 1         | 0.06%   |
| 640x480            | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5520x1080          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 3840x2560          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 398       | 22.03%  |
| 27      | 197       | 10.9%   |
| 24      | 148       | 8.19%   |
| 14      | 148       | 8.19%   |
| 13      | 134       | 7.42%   |
| 21      | 121       | 6.7%    |
| 23      | 112       | 6.2%    |
| 17      | 96        | 5.31%   |
| Unknown | 73        | 4.04%   |
| 19      | 47        | 2.6%    |
| 31      | 41        | 2.27%   |
| 12      | 41        | 2.27%   |
| 34      | 35        | 1.94%   |
| 22      | 31        | 1.72%   |
| 18      | 28        | 1.55%   |
| 20      | 20        | 1.11%   |
| 32      | 16        | 0.89%   |
| 11      | 13        | 0.72%   |
| 25      | 12        | 0.66%   |
| 26      | 11        | 0.61%   |
| 84      | 10        | 0.55%   |
| 72      | 9         | 0.5%    |
| 29      | 8         | 0.44%   |
| 16      | 8         | 0.44%   |
| 54      | 7         | 0.39%   |
| 40      | 4         | 0.22%   |
| 28      | 4         | 0.22%   |
| 10      | 4         | 0.22%   |
| 74      | 3         | 0.17%   |
| 52      | 3         | 0.17%   |
| 49      | 3         | 0.17%   |
| 42      | 3         | 0.17%   |
| 37      | 3         | 0.17%   |
| 60      | 2         | 0.11%   |
| 48      | 2         | 0.11%   |
| 35      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |
| 142     | 1         | 0.06%   |
| 69      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 609       | 34.37%  |
| 501-600        | 428       | 24.15%  |
| 401-500        | 216       | 12.19%  |
| 201-300        | 129       | 7.28%   |
| 351-400        | 128       | 7.22%   |
| 601-700        | 78        | 4.4%    |
| Unknown        | 73        | 4.12%   |
| 701-800        | 52        | 2.93%   |
| 1501-2000      | 23        | 1.3%    |
| 1001-1500      | 20        | 1.13%   |
| 801-900        | 10        | 0.56%   |
| 901-1000       | 3         | 0.17%   |
| 101-200        | 2         | 0.11%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1227      | 76.35%  |
| 16/10   | 181       | 11.26%  |
| Unknown | 63        | 3.92%   |
| 21/9    | 41        | 2.55%   |
| 5/4     | 38        | 2.36%   |
| 4/3     | 29        | 1.8%    |
| 3/2     | 15        | 0.93%   |
| 6/5     | 5         | 0.31%   |
| 2.65    | 3         | 0.19%   |
| 32/9    | 2         | 0.12%   |
| 3.20    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 399       | 22.3%   |
| 201-250        | 321       | 17.94%  |
| 81-90          | 225       | 12.58%  |
| 301-350        | 202       | 11.29%  |
| 351-500        | 102       | 5.7%    |
| 151-200        | 100       | 5.59%   |
| 121-130        | 75        | 4.19%   |
| Unknown        | 73        | 4.08%   |
| 251-300        | 72        | 4.02%   |
| 71-80          | 60        | 3.35%   |
| More than 1000 | 39        | 2.18%   |
| 61-70          | 36        | 2.01%   |
| 141-150        | 34        | 1.9%    |
| 501-1000       | 15        | 0.84%   |
| 51-60          | 13        | 0.73%   |
| 131-140        | 9         | 0.5%    |
| 41-50          | 5         | 0.28%   |
| 91-100         | 5         | 0.28%   |
| 111-120        | 3         | 0.17%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 591       | 34.1%   |
| 121-160       | 477       | 27.52%  |
| 101-120       | 411       | 23.72%  |
| 161-240       | 109       | 6.29%   |
| Unknown       | 73        | 4.21%   |
| More than 240 | 43        | 2.48%   |
| 1-50          | 29        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1188      | 74.81%  |
| 2     | 321       | 20.21%  |
| 0     | 43        | 2.71%   |
| 3     | 33        | 2.08%   |
| 4     | 3         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 848       | 36.73%  |
| Intel                             | 819       | 35.47%  |
| Qualcomm Atheros                  | 205       | 8.88%   |
| Broadcom                          | 120       | 5.2%    |
| MediaTek                          | 36        | 1.56%   |
| TP-Link                           | 23        | 1%      |
| Broadcom Limited                  | 22        | 0.95%   |
| Ralink Technology                 | 21        | 0.91%   |
| Ralink                            | 20        | 0.87%   |
| Nvidia                            | 18        | 0.78%   |
| ASIX Electronics                  | 18        | 0.78%   |
| Marvell Technology Group          | 16        | 0.69%   |
| Sierra Wireless                   | 8         | 0.35%   |
| DisplayLink                       | 8         | 0.35%   |
| Lenovo                            | 6         | 0.26%   |
| Edimax Technology                 | 6         | 0.26%   |
| D-Link                            | 6         | 0.26%   |
| Aquantia                          | 6         | 0.26%   |
| Samsung Electronics               | 5         | 0.22%   |
| NetGear                           | 5         | 0.22%   |
| Microsoft                         | 5         | 0.22%   |
| Hewlett-Packard                   | 5         | 0.22%   |
| Ericsson Business Mobile Networks | 5         | 0.22%   |
| Dell                              | 5         | 0.22%   |
| Qualcomm Atheros Communications   | 4         | 0.17%   |
| Motorola PCS                      | 3         | 0.13%   |
| Microchip Technology              | 3         | 0.13%   |
| Linksys                           | 3         | 0.13%   |
| ICS Advent                        | 3         | 0.13%   |
| D-Link System                     | 3         | 0.13%   |
| Cypress Semiconductor             | 3         | 0.13%   |
| AVM                               | 3         | 0.13%   |
| Xiaomi                            | 2         | 0.09%   |
| VIA Technologies                  | 2         | 0.09%   |
| Texas Instruments                 | 2         | 0.09%   |
| NetXen Incorporated               | 2         | 0.09%   |
| Mellanox Technologies             | 2         | 0.09%   |
| JMicron Technology                | 2         | 0.09%   |
| Huawei Technologies               | 2         | 0.09%   |
| HMD Global                        | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 621       | 22.47%  |
| Intel Wi-Fi 6 AX200                                               | 114       | 4.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 2.24%   |
| Intel I211 Gigabit Network Connection                             | 61        | 2.21%   |
| Intel Wireless 8265 / 8275                                        | 54        | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 1.74%   |
| Intel Wireless 8260                                               | 44        | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 43        | 1.56%   |
| Intel Wireless 7260                                               | 43        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 1.3%    |
| Intel Wi-Fi 6 AX201                                               | 36        | 1.3%    |
| Intel Wireless-AC 9260                                            | 33        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.12%   |
| Intel Wireless 7265                                               | 31        | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 27        | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 24        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24        | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 17        | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 15        | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.54%   |
| Intel Wireless 3160                                               | 14        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.51%   |
| Intel Centrino Ultimate-N 6300                                    | 14        | 0.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 608       | 51.22%  |
| Realtek Semiconductor           | 186       | 15.67%  |
| Qualcomm Atheros                | 157       | 13.23%  |
| Broadcom                        | 78        | 6.57%   |
| MediaTek                        | 31        | 2.61%   |
| Ralink Technology               | 21        | 1.77%   |
| Ralink                          | 20        | 1.68%   |
| TP-Link                         | 15        | 1.26%   |
| Broadcom Limited                | 14        | 1.18%   |
| Sierra Wireless                 | 8         | 0.67%   |
| Edimax Technology               | 6         | 0.51%   |
| NetGear                         | 5         | 0.42%   |
| D-Link                          | 5         | 0.42%   |
| Qualcomm Atheros Communications | 4         | 0.34%   |
| Microsoft                       | 4         | 0.34%   |
| Linksys                         | 3         | 0.25%   |
| Dell                            | 3         | 0.25%   |
| AVM                             | 3         | 0.25%   |
| Marvell Technology Group        | 2         | 0.17%   |
| Hewlett-Packard                 | 2         | 0.17%   |
| D-Link System                   | 2         | 0.17%   |
| ASUSTek Computer                | 2         | 0.17%   |
| ZyXEL Communications            | 1         | 0.08%   |
| Xiaomi                          | 1         | 0.08%   |
| Realtek                         | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| Intersil                        | 1         | 0.08%   |
| IMC Networks                    | 1         | 0.08%   |
| BUFFALO                         | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 114       | 9.53%   |
| Intel Wireless 8265 / 8275                                     | 54        | 4.52%   |
| Intel Wireless 8260                                            | 44        | 3.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 43        | 3.6%    |
| Intel Wireless 7260                                            | 43        | 3.6%    |
| Intel Wi-Fi 6 AX201                                            | 36        | 3.01%   |
| Intel Wireless-AC 9260                                         | 33        | 2.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.59%   |
| Intel Wireless 7265                                            | 31        | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 27        | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 24        | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 24        | 2.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 1.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.42%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 1.25%   |
| Intel Wireless 3160                                            | 14        | 1.17%   |
| Intel Centrino Ultimate-N 6300                                 | 14        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13        | 1.09%   |
| Intel Wireless 3165                                            | 12        | 1%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 0.92%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.75%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 0.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 8         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.59%   |
| Realtek 802.11ac NIC                                           | 6         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 777       | 51.66%  |
| Intel                                  | 471       | 31.32%  |
| Qualcomm Atheros                       | 65        | 4.32%   |
| Broadcom                               | 59        | 3.92%   |
| Nvidia                                 | 18        | 1.2%    |
| ASIX Electronics                       | 18        | 1.2%    |
| Marvell Technology Group               | 14        | 0.93%   |
| TP-Link                                | 8         | 0.53%   |
| DisplayLink                            | 8         | 0.53%   |
| Broadcom Limited                       | 8         | 0.53%   |
| Lenovo                                 | 6         | 0.4%    |
| Aquantia                               | 6         | 0.4%    |
| Samsung Electronics                    | 5         | 0.33%   |
| MediaTek                               | 5         | 0.33%   |
| Motorola PCS                           | 3         | 0.2%    |
| ICS Advent                             | 3         | 0.2%    |
| Cypress Semiconductor                  | 3         | 0.2%    |
| VIA Technologies                       | 2         | 0.13%   |
| NetXen Incorporated                    | 2         | 0.13%   |
| JMicron Technology                     | 2         | 0.13%   |
| Huawei Technologies                    | 2         | 0.13%   |
| HMD Global                             | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Solarflare Communications              | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| MosChip Semiconductor                  | 1         | 0.07%   |
| Microsoft                              | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| IBM                                    | 1         | 0.07%   |
| Google                                 | 1         | 0.07%   |
| Foxconn / Hon Hai                      | 1         | 0.07%   |
| Emulex                                 | 1         | 0.07%   |
| D-Link System                          | 1         | 0.07%   |
| D-Link                                 | 1         | 0.07%   |
| Chelsio Communications                 | 1         | 0.07%   |
| ADMtek                                 | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 621       | 40.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 67        | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 4.03%   |
| Intel I211 Gigabit Network Connection                             | 61        | 3.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 3.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 2.34%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 17        | 1.1%    |
| Intel Ethernet Connection I217-V                                  | 17        | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 1.04%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 12        | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.78%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.78%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.71%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.58%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.52%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.39%   |
| Intel Ethernet Connection (2) I218-LM                             | 6         | 0.39%   |
| Intel Ethernet Connection (11) I219-V                             | 6         | 0.39%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.39%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 6         | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1368      | 54.22%  |
| WiFi     | 1129      | 44.75%  |
| Modem    | 18        | 0.71%   |
| Unknown  | 8         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 838       | 50.57%  |
| Ethernet | 818       | 49.37%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 844       | 54.45%  |
| 1     | 605       | 39.03%  |
| 3     | 60        | 3.87%   |
| 0     | 19        | 1.23%   |
| 4     | 16        | 1.03%   |
| 5     | 4         | 0.26%   |
| 8     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1319      | 83.43%  |
| Yes  | 262       | 16.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 490       | 49.95%  |
| Realtek Semiconductor           | 92        | 9.38%   |
| Cambridge Silicon Radio         | 80        | 8.15%   |
| Qualcomm Atheros Communications | 67        | 6.83%   |
| Broadcom                        | 46        | 4.69%   |
| Lite-On Technology              | 37        | 3.77%   |
| Apple                           | 35        | 3.57%   |
| IMC Networks                    | 33        | 3.36%   |
| Foxconn / Hon Hai               | 26        | 2.65%   |
| ASUSTek Computer                | 18        | 1.83%   |
| Hewlett-Packard                 | 9         | 0.92%   |
| Dell                            | 9         | 0.92%   |
| Realtek                         | 7         | 0.71%   |
| Toshiba                         | 5         | 0.51%   |
| MediaTek                        | 5         | 0.51%   |
| Unknown                         | 3         | 0.31%   |
| Belkin Components               | 3         | 0.31%   |
| Marvell Semiconductor           | 2         | 0.2%    |
| HTC (High Tech Computer)        | 2         | 0.2%    |
| Foxconn International           | 2         | 0.2%    |
| USI                             | 1         | 0.1%    |
| TP-Link                         | 1         | 0.1%    |
| SINO WEALTH                     | 1         | 0.1%    |
| Ralink Technology               | 1         | 0.1%    |
| Ralink                          | 1         | 0.1%    |
| Qcom                            | 1         | 0.1%    |
| Mobile Action Technology        | 1         | 0.1%    |
| Integrated System Solution      | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 176       | 17.9%   |
| Intel AX200 Bluetooth                                                               | 108       | 10.99%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 80        | 8.14%   |
| Intel AX201 Bluetooth                                                               | 69        | 7.02%   |
| Realtek Bluetooth Radio                                                             | 59        | 6%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 50        | 5.09%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 34        | 3.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 32        | 3.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 26        | 2.64%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 22        | 2.24%   |
| Apple Bluetooth Host Controller                                                     | 18        | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 1.53%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 1.32%   |
| Intel AX210 Bluetooth                                                               | 12        | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.12%   |
| IMC Networks Wireless_Device                                                        | 10        | 1.02%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 0.92%   |
| Realtek Bluetooth Radio                                                             | 7         | 0.71%   |
| Lite-On Wireless_Device                                                             | 7         | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 7         | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 7         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.61%   |
| Lite-On Bluetooth Device                                                            | 6         | 0.61%   |
| IMC Networks Bluetooth Device                                                       | 6         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.51%   |
| MediaTek Wireless_Device                                                            | 5         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 0.51%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 5         | 0.51%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.41%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.41%   |
| ASUS Bluetooth Adapter                                                              | 4         | 0.41%   |
| ASUS ASUS USB-BT500                                                                 | 4         | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 978       | 44.7%   |
| AMD                         | 577       | 26.37%  |
| Nvidia                      | 324       | 14.81%  |
| C-Media Electronics         | 44        | 2.01%   |
| Creative Labs               | 25        | 1.14%   |
| Logitech                    | 21        | 0.96%   |
| Texas Instruments           | 17        | 0.78%   |
| Realtek Semiconductor       | 13        | 0.59%   |
| Creative Technology         | 11        | 0.5%    |
| Kingston Technology         | 10        | 0.46%   |
| JMTek                       | 9         | 0.41%   |
| GN Netcom                   | 8         | 0.37%   |
| Generalplus Technology      | 8         | 0.37%   |
| Razer USA                   | 7         | 0.32%   |
| Sennheiser Communications   | 6         | 0.27%   |
| Plantronics                 | 6         | 0.27%   |
| Lenovo                      | 6         | 0.27%   |
| ASUSTek Computer            | 6         | 0.27%   |
| Yamaha                      | 5         | 0.23%   |
| RODE Microphones            | 5         | 0.23%   |
| M-Audio                     | 5         | 0.23%   |
| Hewlett-Packard             | 5         | 0.23%   |
| Corsair                     | 5         | 0.23%   |
| BEHRINGER International     | 5         | 0.23%   |
| SteelSeries ApS             | 4         | 0.18%   |
| Samson Technologies         | 4         | 0.18%   |
| Focusrite-Novation          | 4         | 0.18%   |
| VIA Technologies            | 3         | 0.14%   |
| SAVITECH                    | 3         | 0.14%   |
| FiiO Electronics Technology | 3         | 0.14%   |
| Dell                        | 3         | 0.14%   |
| Apple                       | 3         | 0.14%   |
| ZOOM                        | 2         | 0.09%   |
| Huawei Technologies         | 2         | 0.09%   |
| Fry's Electronics           | 2         | 0.09%   |
| ESS Technology              | 2         | 0.09%   |
| Conexant Systems            | 2         | 0.09%   |
| Blue Microphones            | 2         | 0.09%   |
| XMOS                        | 1         | 0.05%   |
| TerraTec Electronic         | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 179       | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 129       | 4.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 106       | 3.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 93        | 3.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 89        | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 84        | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 84        | 3.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 74        | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 73        | 2.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 62        | 2.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 60        | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 59        | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 59        | 2.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 2.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 47        | 1.73%   |
| AMD FCH Azalia Controller                                                  | 40        | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 38        | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.37%   |
| Intel 8 Series HD Audio Controller                                         | 35        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 34        | 1.25%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 32        | 1.18%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 1.11%   |
| AMD Navi 10 HDMI Audio                                                     | 30        | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 29        | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 1%      |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 24        | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 23        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 22        | 0.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 22        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 21        | 0.77%   |
| Intel CM238 HD Audio Controller                                            | 21        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 20        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 20        | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 19        | 0.7%    |
| Intel Comet Lake PCH cAVS                                                  | 18        | 0.66%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 16        | 0.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 290       | 22.53%  |
| SK hynix                                | 201       | 15.62%  |
| Kingston                                | 162       | 12.59%  |
| Micron Technology                       | 133       | 10.33%  |
| Unknown                                 | 106       | 8.24%   |
| Crucial                                 | 91        | 7.07%   |
| Corsair                                 | 78        | 6.06%   |
| G.Skill                                 | 68        | 5.28%   |
| Ramaxel Technology                      | 18        | 1.4%    |
| A-DATA Technology                       | 18        | 1.4%    |
| Elpida                                  | 16        | 1.24%   |
| Patriot                                 | 14        | 1.09%   |
| Unknown (ABCD)                          | 11        | 0.85%   |
| Nanya Technology                        | 10        | 0.78%   |
| Smart                                   | 8         | 0.62%   |
| Team                                    | 7         | 0.54%   |
| Transcend                               | 6         | 0.47%   |
| Avant                                   | 6         | 0.47%   |
| GOODRAM                                 | 4         | 0.31%   |
| Unknown                                 | 4         | 0.31%   |
| AMD                                     | 3         | 0.23%   |
| Teikon                                  | 2         | 0.16%   |
| Lexar                                   | 2         | 0.16%   |
| ASint Technology                        | 2         | 0.16%   |
| Unknown (0x02BA)                        | 1         | 0.08%   |
| Unknown (07FB)                          | 1         | 0.08%   |
| Unknown (000004B30000)                  | 1         | 0.08%   |
| Unifosa                                 | 1         | 0.08%   |
| Toshiba                                 | 1         | 0.08%   |
| TakeMS                                  | 1         | 0.08%   |
| Super Talent                            | 1         | 0.08%   |
| Smart Modular                           | 1         | 0.08%   |
| Smart Brazil                            | 1         | 0.08%   |
| Silicon Power Computer & Communications | 1         | 0.08%   |
| Silicon Power                           | 1         | 0.08%   |
| SanDisk                                 | 1         | 0.08%   |
| Qimonda                                 | 1         | 0.08%   |
| Princeton                               | 1         | 0.08%   |
| pqi                                     | 1         | 0.08%   |
| PNY                                     | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 15        | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1.09%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.8%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 9         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 8         | 0.58%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 8         | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 7         | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 7         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 7         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.44%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 6         | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.44%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 6         | 0.44%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 6         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 5         | 0.36%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.36%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.36%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 5         | 0.36%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 5         | 0.36%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 574       | 52.37%  |
| DDR3    | 344       | 31.39%  |
| LPDDR4  | 40        | 3.65%   |
| DDR2    | 40        | 3.65%   |
| Unknown | 35        | 3.19%   |
| LPDDR3  | 30        | 2.74%   |
| SDRAM   | 19        | 1.73%   |
| DDR     | 6         | 0.55%   |
| LPDDR5  | 4         | 0.36%   |
| DRAM    | 2         | 0.18%   |
| DDR5    | 2         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 586       | 53.27%  |
| DIMM         | 429       | 39%     |
| Row Of Chips | 70        | 6.36%   |
| Chip         | 11        | 1%      |
| RIMM         | 2         | 0.18%   |
| FB-DIMM      | 2         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 486       | 40.5%   |
| 4096  | 341       | 28.42%  |
| 16384 | 181       | 15.08%  |
| 2048  | 115       | 9.58%   |
| 32768 | 43        | 3.58%   |
| 1024  | 31        | 2.58%   |
| 512   | 2         | 0.17%   |
| 128   | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 228       | 19.02%  |
| 2667    | 182       | 15.18%  |
| 3200    | 175       | 14.6%   |
| 2400    | 96        | 8.01%   |
| 1333    | 88        | 7.34%   |
| 2133    | 79        | 6.59%   |
| 3600    | 40        | 3.34%   |
| 1334    | 36        | 3%      |
| 1867    | 23        | 1.92%   |
| 800     | 23        | 1.92%   |
| 667     | 22        | 1.83%   |
| 4267    | 16        | 1.33%   |
| 3266    | 16        | 1.33%   |
| 3466    | 12        | 1%      |
| 3400    | 12        | 1%      |
| 1067    | 12        | 1%      |
| Unknown | 12        | 1%      |
| 2666    | 11        | 0.92%   |
| 1066    | 11        | 0.92%   |
| 3800    | 9         | 0.75%   |
| 1866    | 8         | 0.67%   |
| 4266    | 7         | 0.58%   |
| 3000    | 7         | 0.58%   |
| 8400    | 6         | 0.5%    |
| 2933    | 6         | 0.5%    |
| 2048    | 6         | 0.5%    |
| 2800    | 5         | 0.42%   |
| 975     | 5         | 0.42%   |
| 4199    | 4         | 0.33%   |
| 3666    | 4         | 0.33%   |
| 6400    | 3         | 0.25%   |
| 3866    | 3         | 0.25%   |
| 3733    | 3         | 0.25%   |
| 533     | 3         | 0.25%   |
| 333     | 3         | 0.25%   |
| 4800    | 2         | 0.17%   |
| 3334    | 2         | 0.17%   |
| 3151    | 2         | 0.17%   |
| 3007    | 2         | 0.17%   |
| 1800    | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 43.75%  |
| Samsung Electronics | 8         | 16.67%  |
| Brother Industries  | 7         | 14.58%  |
| Seiko Epson         | 5         | 10.42%  |
| Canon               | 3         | 6.25%   |
| Prolific Technology | 2         | 4.17%   |
| Pantum              | 1         | 2.08%   |
| Kyocera             | 1         | 2.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                        | 2         | 4.08%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 4.08%   |
| Prolific PL2305 Parallel Port                   | 2         | 4.08%   |
| HP Officejet 4500 G510g-m                       | 2         | 4.08%   |
| HP Color LaserJet CP1215                        | 2         | 4.08%   |
| Seiko Epson XP-243 245 247 Series               | 1         | 2.04%   |
| Seiko Epson XP-230 Series                       | 1         | 2.04%   |
| Seiko Epson L3160 Series                        | 1         | 2.04%   |
| Seiko Epson L1300 Series                        | 1         | 2.04%   |
| Samsung SCX-4200 series                         | 1         | 2.04%   |
| Samsung SCX-3400 Series                         | 1         | 2.04%   |
| Samsung ML-191x/ML-252x Laser Printer           | 1         | 2.04%   |
| Samsung ML-1865                                 | 1         | 2.04%   |
| Samsung M267x 287x Series                       | 1         | 2.04%   |
| Samsung M2020 Series                            | 1         | 2.04%   |
| Pantum P2500W-series                            | 1         | 2.04%   |
| Kyocera FS-1030D printer                        | 1         | 2.04%   |
| HP Smart Tank Plus 550 series                   | 1         | 2.04%   |
| HP Smart Install                                | 1         | 2.04%   |
| HP OfficeJet 5200 series                        | 1         | 2.04%   |
| HP Officejet 4620 series                        | 1         | 2.04%   |
| HP LaserJet Professional P 1102w                | 1         | 2.04%   |
| HP LaserJet P1102                               | 1         | 2.04%   |
| HP LaserJet 1320                                | 1         | 2.04%   |
| HP LaserJet 1020                                | 1         | 2.04%   |
| HP LaserJet 1018                                | 1         | 2.04%   |
| HP ENVY 4520 series                             | 1         | 2.04%   |
| HP ENVY 4500 series                             | 1         | 2.04%   |
| HP Deskjet Ink Advant K209a-z                   | 1         | 2.04%   |
| HP DeskJet 6940 series                          | 1         | 2.04%   |
| HP DeskJet 5940                                 | 1         | 2.04%   |
| HP DeskJet 3630 series                          | 1         | 2.04%   |
| HP DeskJet 2700 series                          | 1         | 2.04%   |
| HP DeskJet 2620 All-in-One Printer              | 1         | 2.04%   |
| Canon TR7500 series                             | 1         | 2.04%   |
| Canon G3020 series                              | 1         | 2.04%   |
| Canon CanoScan LiDE 300                         | 1         | 2.04%   |
| Brother Printer                                 | 1         | 2.04%   |
| Brother MFC-J485DW                              | 1         | 2.04%   |
| Brother MFC-7360N                               | 1         | 2.04%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 42.86%  |
| Seiko Epson     | 3         | 21.43%  |
| Hewlett-Packard | 2         | 14.29%  |
| AGFA-Gevaert NV | 2         | 14.29%  |
| Mustek Systems  | 1         | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                             | 3         | 21.43%  |
| Seiko Epson Scanner                                 | 1         | 7.14%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1         | 7.14%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 7.14%   |
| Mustek Systems ScanExpress A3 USB                   | 1         | 7.14%   |
| HP ScanJet 5300c/5370c                              | 1         | 7.14%   |
| HP ScanJet 3970c                                    | 1         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1         | 7.14%   |
| Canon CanoScan N1240U/LiDE 30                       | 1         | 7.14%   |
| Canon CanoScan LiDE 110                             | 1         | 7.14%   |
| AGFA-Gevaert NV SnapScan e20                        | 1         | 7.14%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                  | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 221       | 24.15%  |
| IMC Networks                           | 85        | 9.29%   |
| Logitech                               | 83        | 9.07%   |
| Microdia                               | 82        | 8.96%   |
| Acer                                   | 70        | 7.65%   |
| Realtek Semiconductor                  | 67        | 7.32%   |
| Sunplus Innovation Technology          | 48        | 5.25%   |
| Quanta                                 | 47        | 5.14%   |
| Cheng Uei Precision Industry (Foxlink) | 30        | 3.28%   |
| Apple                                  | 25        | 2.73%   |
| Lite-On Technology                     | 21        | 2.3%    |
| Suyin                                  | 16        | 1.75%   |
| Luxvisions Innotech Limited            | 16        | 1.75%   |
| Syntek                                 | 14        | 1.53%   |
| Microsoft                              | 9         | 0.98%   |
| Silicon Motion                         | 8         | 0.87%   |
| Lenovo                                 | 6         | 0.66%   |
| Samsung Electronics                    | 5         | 0.55%   |
| Alcor Micro                            | 5         | 0.55%   |
| Ricoh                                  | 4         | 0.44%   |
| Z-Star Microelectronics                | 3         | 0.33%   |
| Sonix Technology                       | 3         | 0.33%   |
| Primax Electronics                     | 3         | 0.33%   |
| Hewlett-Packard                        | 3         | 0.33%   |
| Generalplus Technology                 | 3         | 0.33%   |
| Unknown                                | 2         | 0.22%   |
| Trust                                  | 2         | 0.22%   |
| Tobii Technology AB                    | 2         | 0.22%   |
| SunplusIT                              | 2         | 0.22%   |
| LG Electronics                         | 2         | 0.22%   |
| DJKANA19IDX53W                         | 2         | 0.22%   |
| Cubeternet                             | 2         | 0.22%   |
| Creative Technology                    | 2         | 0.22%   |
| Arkmicro Technologies                  | 2         | 0.22%   |
| ARC International                      | 2         | 0.22%   |
| Y Media                                | 1         | 0.11%   |
| Unknown (3730304231393931415053)       | 1         | 0.11%   |
| Sweex                                  | 1         | 0.11%   |
| SJ-180517-N                            | 1         | 0.11%   |
| Philips (or NXP)                       | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 54        | 5.84%   |
| IMC Networks Integrated Camera                      | 35        | 3.78%   |
| Microdia Integrated_Webcam_HD                       | 34        | 3.68%   |
| Logitech Webcam C270                                | 25        | 2.7%    |
| Realtek Integrated_Webcam_HD                        | 24        | 2.59%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 24        | 2.59%   |
| Chicony HD Webcam                                   | 24        | 2.59%   |
| Acer Integrated Camera                              | 19        | 2.05%   |
| Chicony HP HD Camera                                | 16        | 1.73%   |
| Sunplus Integrated_Webcam_HD                        | 15        | 1.62%   |
| Apple Built-in iSight                               | 12        | 1.3%    |
| Quanta HP HD Camera                                 | 10        | 1.08%   |
| Realtek Integrated Webcam HD                        | 9         | 0.97%   |
| Logitech HD Pro Webcam C920                         | 9         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 0.97%   |
| Chicony HP HD Webcam                                | 9         | 0.97%   |
| Syntek Integrated Camera                            | 8         | 0.86%   |
| Lite-On Integrated Camera                           | 8         | 0.86%   |
| Chicony USB2.0 Camera                               | 8         | 0.86%   |
| Acer HD Webcam                                      | 8         | 0.86%   |
| Acer BisonCam, NB Pro                               | 8         | 0.86%   |
| Quanta HD User Facing                               | 7         | 0.76%   |
| Microdia Integrated Webcam                          | 7         | 0.76%   |
| Realtek USB Camera                                  | 6         | 0.65%   |
| Quanta VGA WebCam                                   | 6         | 0.65%   |
| Logitech HD Webcam C615                             | 6         | 0.65%   |
| Logitech C922 Pro Stream Webcam                     | 6         | 0.65%   |
| Chicony USB 2.0 Camera                              | 6         | 0.65%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 0.65%   |
| Chicony HP Truevision HD                            | 6         | 0.65%   |
| Chicony HD User Facing                              | 6         | 0.65%   |
| Apple FaceTime HD Camera                            | 6         | 0.65%   |
| Acer EasyCamera                                     | 6         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)             | 5         | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.54%   |
| Microdia USB 2.0 Camera                             | 5         | 0.54%   |
| Microdia Sonix USB 2.0 Camera                       | 5         | 0.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.54%   |
| Luxvisions Innotech Limited HP HD Camera            | 5         | 0.54%   |
| Logitech Webcam C310                                | 5         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 77        | 39.69%  |
| Synaptics                  | 71        | 36.6%   |
| Shenzhen Goodix Technology | 22        | 11.34%  |
| Upek                       | 9         | 4.64%   |
| Elan Microelectronics      | 6         | 3.09%   |
| AuthenTec                  | 6         | 3.09%   |
| LighTuning Technology      | 2         | 1.03%   |
| STMicroelectronics         | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 11.34%  |
| Unknown                                                                    | 22        | 11.34%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 10.82%  |
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 7.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 5.67%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 5.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.64%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 3.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.09%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.58%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.06%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.06%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.06%   |
| Validity Sensors VFS491                                                    | 3         | 1.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.55%   |
| Synaptics WBDI Device                                                      | 3         | 1.55%   |
| Synaptics  WBDI                                                            | 3         | 1.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.03%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 1.03%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.03%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.03%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.03%   |
| AuthenTec AES1600                                                          | 2         | 1.03%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.52%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.52%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.52%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.52%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 32        | 39.02%  |
| Broadcom                   | 28        | 34.15%  |
| Gemalto (was Gemplus)      | 6         | 7.32%   |
| Upek                       | 4         | 4.88%   |
| O2 Micro                   | 3         | 3.66%   |
| Hewlett-Packard            | 3         | 3.66%   |
| Lenovo                     | 2         | 2.44%   |
| Yubico.com                 | 1         | 1.22%   |
| Watchdata                  | 1         | 1.22%   |
| Clay Logic                 | 1         | 1.22%   |
| Athena Smartcard Solutions | 1         | 1.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 36.59%  |
| Broadcom 5880                                                                | 12        | 14.63%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 8.54%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 6.1%    |
| Broadcom 58200                                                               | 5         | 6.1%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.66%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 3         | 3.66%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.44%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.22%   |
| Watchdata USB Key                                                            | 1         | 1.22%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 1.22%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.22%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.22%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.22%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1122      | 70.21%  |
| 1     | 375       | 23.47%  |
| 2     | 85        | 5.32%   |
| 3     | 14        | 0.88%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 193       | 34.04%  |
| Graphics card            | 111       | 19.58%  |
| Chipcard                 | 72        | 12.7%   |
| Net/wireless             | 60        | 10.58%  |
| Sound                    | 25        | 4.41%   |
| Multimedia controller    | 24        | 4.23%   |
| Camera                   | 18        | 3.17%   |
| Unassigned class         | 16        | 2.82%   |
| Communication controller | 13        | 2.29%   |
| Card reader              | 9         | 1.59%   |
| Storage                  | 7         | 1.23%   |
| Network                  | 5         | 0.88%   |
| Bluetooth                | 5         | 0.88%   |
| Net/ethernet             | 4         | 0.71%   |
| Firewire controller      | 3         | 0.53%   |
| Modem                    | 1         | 0.18%   |
| Flash memory             | 1         | 0.18%   |

