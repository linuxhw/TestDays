Zorin 16 - Tested Hardware & Statistics (Desktops)
--------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | H110M-DGS R3.0              | [d7b8815296](https://linux-hardware.org/?probe=d7b8815296) | Feb 28, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | [61f8410abd](https://linux-hardware.org/?probe=61f8410abd) | Feb 28, 2022 |
| BESSTAR Te... | TL50                        | [54383b0005](https://linux-hardware.org/?probe=54383b0005) | Feb 28, 2022 |
| HP            | 821D                        | [fdfcbe172a](https://linux-hardware.org/?probe=fdfcbe172a) | Feb 28, 2022 |
| Acer          | Aspire TC-875 V:1.0         | [47018f3ae4](https://linux-hardware.org/?probe=47018f3ae4) | Feb 28, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [f455a7b7a5](https://linux-hardware.org/?probe=f455a7b7a5) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [52c633564d](https://linux-hardware.org/?probe=52c633564d) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [74461b0659](https://linux-hardware.org/?probe=74461b0659) | Feb 27, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [cef4c5a609](https://linux-hardware.org/?probe=cef4c5a609) | Feb 27, 2022 |
| MSI           | B85M-E45                    | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | [821b101c53](https://linux-hardware.org/?probe=821b101c53) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [e1ba37c64a](https://linux-hardware.org/?probe=e1ba37c64a) | Feb 27, 2022 |
| Gigabyte      | EP43T-UD3L                  | [5d56069677](https://linux-hardware.org/?probe=5d56069677) | Feb 27, 2022 |
| Gigabyte      | N3160TN                     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME H510M-D               | [5e8e80fa4c](https://linux-hardware.org/?probe=5e8e80fa4c) | Feb 25, 2022 |
| Intel         | X79M-S                      | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [c9447d244f](https://linux-hardware.org/?probe=c9447d244f) | Feb 24, 2022 |
| Gigabyte      | Z87-HD3                     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [d685366566](https://linux-hardware.org/?probe=d685366566) | Feb 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [e3ae28a6a2](https://linux-hardware.org/?probe=e3ae28a6a2) | Feb 24, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | [40de7f3fd4](https://linux-hardware.org/?probe=40de7f3fd4) | Feb 23, 2022 |
| Medion        | MS-7707                     | [563fc4ee5a](https://linux-hardware.org/?probe=563fc4ee5a) | Feb 23, 2022 |
| Medion        | MS-7707                     | [f3b9e8796b](https://linux-hardware.org/?probe=f3b9e8796b) | Feb 23, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b83fdc23d3](https://linux-hardware.org/?probe=b83fdc23d3) | Feb 23, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [8efe63496f](https://linux-hardware.org/?probe=8efe63496f) | Feb 22, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [979289afcb](https://linux-hardware.org/?probe=979289afcb) | Feb 21, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [62fc974ec7](https://linux-hardware.org/?probe=62fc974ec7) | Feb 21, 2022 |
| Dell          | 0HN7XN A01                  | [a2949c69ea](https://linux-hardware.org/?probe=a2949c69ea) | Feb 21, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [435006f81f](https://linux-hardware.org/?probe=435006f81f) | Feb 20, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [9264e93f98](https://linux-hardware.org/?probe=9264e93f98) | Feb 20, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f091d19c91](https://linux-hardware.org/?probe=f091d19c91) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [1990e2040f](https://linux-hardware.org/?probe=1990e2040f) | Feb 19, 2022 |
| ASUSTek       | P5E-VM DO                   | [bcbc783948](https://linux-hardware.org/?probe=bcbc783948) | Feb 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [c545739154](https://linux-hardware.org/?probe=c545739154) | Feb 18, 2022 |
| ASUSTek       | P5E-VM DO                   | [c204579cc4](https://linux-hardware.org/?probe=c204579cc4) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [bccc2f8988](https://linux-hardware.org/?probe=bccc2f8988) | Feb 18, 2022 |
| Gigabyte      | H270M-DS3H-CF               | [43a7b2c585](https://linux-hardware.org/?probe=43a7b2c585) | Feb 18, 2022 |
| MSI           | B360M PRO-VDH               | [dfb03c38d4](https://linux-hardware.org/?probe=dfb03c38d4) | Feb 18, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [b06467c5df](https://linux-hardware.org/?probe=b06467c5df) | Feb 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | [497a009b81](https://linux-hardware.org/?probe=497a009b81) | Feb 15, 2022 |
| ASUSTek       | P8P67                       | [e52f9b0748](https://linux-hardware.org/?probe=e52f9b0748) | Feb 15, 2022 |
| HP            | 2B15A                       | [ca58e13d8f](https://linux-hardware.org/?probe=ca58e13d8f) | Feb 15, 2022 |
| Pegatron      | 2AC2                        | [092df404d4](https://linux-hardware.org/?probe=092df404d4) | Feb 15, 2022 |
| ASUSTek       | PRIME X370-PRO              | [54a56f3b09](https://linux-hardware.org/?probe=54a56f3b09) | Feb 15, 2022 |
| Intel         | X79M-S                      | [b655865606](https://linux-hardware.org/?probe=b655865606) | Feb 14, 2022 |
| IBM           | 81077AG                     | [934878ed63](https://linux-hardware.org/?probe=934878ed63) | Feb 14, 2022 |
| ASUSTek       | P8H61-M EVO                 | [40ed7abcc5](https://linux-hardware.org/?probe=40ed7abcc5) | Feb 14, 2022 |
| ASRock        | X299 Taichi                 | [cb4047cf07](https://linux-hardware.org/?probe=cb4047cf07) | Feb 13, 2022 |
| ASUSTek       | P8H61-M EVO                 | [94bcb91d02](https://linux-hardware.org/?probe=94bcb91d02) | Feb 13, 2022 |
| ASRock        | 970A-G                      | [7b3694013f](https://linux-hardware.org/?probe=7b3694013f) | Feb 13, 2022 |
| HP            | 0B54h D                     | [c9f9611ea4](https://linux-hardware.org/?probe=c9f9611ea4) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [d97414cfe4](https://linux-hardware.org/?probe=d97414cfe4) | Feb 12, 2022 |
| Dell          | 0T10XW A01                  | [a9034f065e](https://linux-hardware.org/?probe=a9034f065e) | Feb 11, 2022 |
| Dell          | 0T10XW A01                  | [c0cce21524](https://linux-hardware.org/?probe=c0cce21524) | Feb 11, 2022 |
| Intel         | H61                         | [e06357425a](https://linux-hardware.org/?probe=e06357425a) | Feb 11, 2022 |
| MSI           | A75A-G35                    | [47677a6e5f](https://linux-hardware.org/?probe=47677a6e5f) | Feb 11, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [b79b4aaf10](https://linux-hardware.org/?probe=b79b4aaf10) | Feb 11, 2022 |
| HP            | 198E                        | [f4781dd683](https://linux-hardware.org/?probe=f4781dd683) | Feb 10, 2022 |
| ASUSTek       | TUF GAMING Z690-PLUS WIF... | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| Dell          | 096JG8 A01                  | [c56c62ab01](https://linux-hardware.org/?probe=c56c62ab01) | Feb 10, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [961be2a608](https://linux-hardware.org/?probe=961be2a608) | Feb 09, 2022 |
| MSI           | MPG Z590 GAMING FORCE       | [4ab26645c2](https://linux-hardware.org/?probe=4ab26645c2) | Feb 09, 2022 |
| HP            | 8350                        | [31f2f10b25](https://linux-hardware.org/?probe=31f2f10b25) | Feb 08, 2022 |
| HP            | 1906                        | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| MSI           | 2AE0                        | [7026cf0c86](https://linux-hardware.org/?probe=7026cf0c86) | Feb 07, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | [cec6148a23](https://linux-hardware.org/?probe=cec6148a23) | Feb 07, 2022 |
| MSI           | B85M-E45                    | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [c5db8c7811](https://linux-hardware.org/?probe=c5db8c7811) | Feb 06, 2022 |
| Lenovo        | ThinkCentre M91p 4480B2G    | [96e92c90a5](https://linux-hardware.org/?probe=96e92c90a5) | Feb 06, 2022 |
| Gigabyte      | G1.Sniper Z97               | [5ef683a8ed](https://linux-hardware.org/?probe=5ef683a8ed) | Feb 06, 2022 |
| ASUSTek       | TUF GAMING X570-PRO WIFI... | [81b3cfa233](https://linux-hardware.org/?probe=81b3cfa233) | Feb 06, 2022 |
| Acer          | Aspire TC-115               | [03188d20fc](https://linux-hardware.org/?probe=03188d20fc) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [80cf2c4065](https://linux-hardware.org/?probe=80cf2c4065) | Feb 04, 2022 |
| ASUSTek       | Maximus V GENE              | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Dell          | 0HN7XN A01                  | [5bb62c21b7](https://linux-hardware.org/?probe=5bb62c21b7) | Feb 03, 2022 |
| ASUSTek       | M4A785-M                    | [421c016644](https://linux-hardware.org/?probe=421c016644) | Feb 02, 2022 |
| Gigabyte      | B450 AORUS M                | [b76b53bf53](https://linux-hardware.org/?probe=b76b53bf53) | Feb 01, 2022 |
| Gigabyte      | B450 AORUS M                | [45f03f7991](https://linux-hardware.org/?probe=45f03f7991) | Jan 31, 2022 |
| Gigabyte      | B450 AORUS M                | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Dell          | 0HN7XN A01                  | [af1d1e8c47](https://linux-hardware.org/?probe=af1d1e8c47) | Jan 30, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | [7450ea2cad](https://linux-hardware.org/?probe=7450ea2cad) | Jan 30, 2022 |
| ASRock        | H81M-DGS                    | [05fc3bd63b](https://linux-hardware.org/?probe=05fc3bd63b) | Jan 29, 2022 |
| HP            | 3047h                       | [48f624cbea](https://linux-hardware.org/?probe=48f624cbea) | Jan 29, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [bcdcd2eeb6](https://linux-hardware.org/?probe=bcdcd2eeb6) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | 2AE0                        | [1a55336eb9](https://linux-hardware.org/?probe=1a55336eb9) | Jan 28, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| Wortmann      | TERRA_PC                    | [4fea20e2bf](https://linux-hardware.org/?probe=4fea20e2bf) | Jan 28, 2022 |
| Dell          | 0Y2MRG A00                  | [1a1b794c06](https://linux-hardware.org/?probe=1a1b794c06) | Jan 28, 2022 |
| Gigabyte      | Z270N-WIFI-CF               | [78f310c42a](https://linux-hardware.org/?probe=78f310c42a) | Jan 27, 2022 |
| ASRock        | G31M-S                      | [e579ce1757](https://linux-hardware.org/?probe=e579ce1757) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [2c70e74055](https://linux-hardware.org/?probe=2c70e74055) | Jan 26, 2022 |
| Intel         | DH55PJ AAE93812-303         | [6a692a4e11](https://linux-hardware.org/?probe=6a692a4e11) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Dell          | 07KY25 A00                  | [102d10e806](https://linux-hardware.org/?probe=102d10e806) | Jan 26, 2022 |
| MSI           | H97 GAMING 3                | [75f4b47111](https://linux-hardware.org/?probe=75f4b47111) | Jan 26, 2022 |
| Dell          | 06NWYK A01                  | [dbc44c9f4a](https://linux-hardware.org/?probe=dbc44c9f4a) | Jan 25, 2022 |
| HP            | 1497                        | [a32eadf3ab](https://linux-hardware.org/?probe=a32eadf3ab) | Jan 25, 2022 |
| Dell          | 06NWYK A01                  | [693f4a0a48](https://linux-hardware.org/?probe=693f4a0a48) | Jan 25, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | [e521380180](https://linux-hardware.org/?probe=e521380180) | Jan 25, 2022 |
| ASUSTek       | Q87T                        | [1bcaa6dedf](https://linux-hardware.org/?probe=1bcaa6dedf) | Jan 24, 2022 |
| Foxconn       | 2ABF                        | [e5723eaa42](https://linux-hardware.org/?probe=e5723eaa42) | Jan 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a0034083eb](https://linux-hardware.org/?probe=a0034083eb) | Jan 22, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [2a8b893eb6](https://linux-hardware.org/?probe=2a8b893eb6) | Jan 22, 2022 |
| Foxconn       | 2ABF                        | [af38735785](https://linux-hardware.org/?probe=af38735785) | Jan 22, 2022 |
| MSI           | A75A-G35                    | [e2148dff19](https://linux-hardware.org/?probe=e2148dff19) | Jan 22, 2022 |
| Dell          | 0CU409                      | [8fc6c3decf](https://linux-hardware.org/?probe=8fc6c3decf) | Jan 21, 2022 |
| Dell          | 0CU409                      | [953718318f](https://linux-hardware.org/?probe=953718318f) | Jan 21, 2022 |
| Gigabyte      | F2A58M-DS2                  | [a89dd04d3a](https://linux-hardware.org/?probe=a89dd04d3a) | Jan 20, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | [586012f45e](https://linux-hardware.org/?probe=586012f45e) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [2ab8f0375c](https://linux-hardware.org/?probe=2ab8f0375c) | Jan 20, 2022 |
| Dell          | 09NY2R A00                  | [5308c77880](https://linux-hardware.org/?probe=5308c77880) | Jan 19, 2022 |
| ASUSTek       | H81M-K                      | [637ad5d9e4](https://linux-hardware.org/?probe=637ad5d9e4) | Jan 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [ffaca9cabf](https://linux-hardware.org/?probe=ffaca9cabf) | Jan 18, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [940b702411](https://linux-hardware.org/?probe=940b702411) | Jan 16, 2022 |
| MSI           | H61M-P25                    | [3433cb58a1](https://linux-hardware.org/?probe=3433cb58a1) | Jan 14, 2022 |
| HP            | 3047h                       | [9a81422518](https://linux-hardware.org/?probe=9a81422518) | Jan 14, 2022 |
| MSI           | MS-7053                     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| MSI           | MS-7053                     | [61c46371e7](https://linux-hardware.org/?probe=61c46371e7) | Jan 13, 2022 |
| MSI           | H61M-P25                    | [c745684371](https://linux-hardware.org/?probe=c745684371) | Jan 13, 2022 |
| MSI           | H61M-P25                    | [f4fa2b39ad](https://linux-hardware.org/?probe=f4fa2b39ad) | Jan 13, 2022 |
| EVGA          | 152-HR-E979                 | [669c7a3ef6](https://linux-hardware.org/?probe=669c7a3ef6) | Jan 12, 2022 |
| EVGA          | 152-HR-E979                 | [075a31a3c5](https://linux-hardware.org/?probe=075a31a3c5) | Jan 12, 2022 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [368df270dc](https://linux-hardware.org/?probe=368df270dc) | Jan 11, 2022 |
| Gigabyte      | F2A58M-DS2                  | [b7ee3c3e93](https://linux-hardware.org/?probe=b7ee3c3e93) | Jan 11, 2022 |
| ASUSTek       | P8H61-I R2.0                | [5b08de311b](https://linux-hardware.org/?probe=5b08de311b) | Jan 10, 2022 |
| Dell          | 06NWYK A01                  | [98c10ce544](https://linux-hardware.org/?probe=98c10ce544) | Jan 10, 2022 |
| ASRock        | G31M-S                      | [1006244941](https://linux-hardware.org/?probe=1006244941) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6759388aa1](https://linux-hardware.org/?probe=6759388aa1) | Jan 09, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [6a368aefbd](https://linux-hardware.org/?probe=6a368aefbd) | Jan 09, 2022 |
| ASUSTek       | PRIME H310M-K               | [3b4d6e5abd](https://linux-hardware.org/?probe=3b4d6e5abd) | Jan 08, 2022 |
| ASRock        | G31M-S                      | [b33a983889](https://linux-hardware.org/?probe=b33a983889) | Jan 08, 2022 |
| MSI           | H61M-P25                    | [5f095c2bf8](https://linux-hardware.org/?probe=5f095c2bf8) | Jan 08, 2022 |
| Dell          | 042P49 A02                  | [b2a3538121](https://linux-hardware.org/?probe=b2a3538121) | Jan 08, 2022 |
| ASRock        | AM1B-ITX                    | [c374329271](https://linux-hardware.org/?probe=c374329271) | Jan 07, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [e51ad2ec06](https://linux-hardware.org/?probe=e51ad2ec06) | Jan 07, 2022 |
| Dell          | 0YXT71 A02                  | [682c40786b](https://linux-hardware.org/?probe=682c40786b) | Jan 07, 2022 |
| Gigabyte      | H61M-S2PV                   | [398f9ebe03](https://linux-hardware.org/?probe=398f9ebe03) | Jan 06, 2022 |
| Gigabyte      | H61M-S2PV                   | [a46fcf64bb](https://linux-hardware.org/?probe=a46fcf64bb) | Jan 06, 2022 |
| ASUSTek       | Benicia                     | [5459dba29c](https://linux-hardware.org/?probe=5459dba29c) | Jan 06, 2022 |
| Dell          | 0GDG8Y A00                  | [e89e415451](https://linux-hardware.org/?probe=e89e415451) | Jan 05, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [fc860fdb7a](https://linux-hardware.org/?probe=fc860fdb7a) | Jan 05, 2022 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [dad1a9143d](https://linux-hardware.org/?probe=dad1a9143d) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [5694489e55](https://linux-hardware.org/?probe=5694489e55) | Jan 05, 2022 |
| MSI           | H61MU-E35                   | [c9ece2a64e](https://linux-hardware.org/?probe=c9ece2a64e) | Jan 05, 2022 |
| Gigabyte      | H370M D3H-CF                | [ab12119d4f](https://linux-hardware.org/?probe=ab12119d4f) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | [1ad802006b](https://linux-hardware.org/?probe=1ad802006b) | Jan 05, 2022 |
| ASUSTek       | TUF GAMING B460M-PLUS       | [32d0fda197](https://linux-hardware.org/?probe=32d0fda197) | Jan 05, 2022 |
| MSI           | H61M-P25                    | [16e6027ba2](https://linux-hardware.org/?probe=16e6027ba2) | Jan 04, 2022 |
| MSI           | H61MU-E35                   | [2c3f24c851](https://linux-hardware.org/?probe=2c3f24c851) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [3679d16bdb](https://linux-hardware.org/?probe=3679d16bdb) | Jan 04, 2022 |
| HP            | 3047h                       | [8faa43060a](https://linux-hardware.org/?probe=8faa43060a) | Jan 04, 2022 |
| MSI           | H61M-P25                    | [004392f0ef](https://linux-hardware.org/?probe=004392f0ef) | Jan 04, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b838b1e1cc](https://linux-hardware.org/?probe=b838b1e1cc) | Jan 04, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [d2a528221c](https://linux-hardware.org/?probe=d2a528221c) | Jan 03, 2022 |
| ASRock        | B450M Steel Legend          | [81a98f588a](https://linux-hardware.org/?probe=81a98f588a) | Jan 02, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Acer          | Aspire M3970                | [e10ce7d132](https://linux-hardware.org/?probe=e10ce7d132) | Dec 31, 2021 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [5b97adba13](https://linux-hardware.org/?probe=5b97adba13) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| HP            | 1998                        | [07bdd01c09](https://linux-hardware.org/?probe=07bdd01c09) | Dec 31, 2021 |
| Dell          | 088DT1 A01                  | [2599126547](https://linux-hardware.org/?probe=2599126547) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | [1c32c6a027](https://linux-hardware.org/?probe=1c32c6a027) | Dec 30, 2021 |
| MSI           | H81M-P33                    | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| ASRock        | Z87 Pro4                    | [2a8588f61e](https://linux-hardware.org/?probe=2a8588f61e) | Dec 29, 2021 |
| Gigabyte      | Z97-HD3                     | [5536599b58](https://linux-hardware.org/?probe=5536599b58) | Dec 28, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [127916f66f](https://linux-hardware.org/?probe=127916f66f) | Dec 28, 2021 |
| ASUSTek       | H81-PLUS                    | [60ba71333c](https://linux-hardware.org/?probe=60ba71333c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [cb83ad3d6c](https://linux-hardware.org/?probe=cb83ad3d6c) | Dec 27, 2021 |
| Intel         | Cherry Trail CR H91596-3... | [76e7cab82a](https://linux-hardware.org/?probe=76e7cab82a) | Dec 26, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [39f562f189](https://linux-hardware.org/?probe=39f562f189) | Dec 25, 2021 |
| Dell          | 0VNP2H A00                  | [e64f51e52a](https://linux-hardware.org/?probe=e64f51e52a) | Dec 24, 2021 |
| Gigabyte      | H57M-USB3                   | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| Gigabyte      | Z170X-Gaming 7              | [5c4ae9536f](https://linux-hardware.org/?probe=5c4ae9536f) | Dec 24, 2021 |
| Gigabyte      | EG41MFT-US2H                | [2bfb4702c3](https://linux-hardware.org/?probe=2bfb4702c3) | Dec 23, 2021 |
| Gigabyte      | EG41MFT-US2H                | [b29d64341c](https://linux-hardware.org/?probe=b29d64341c) | Dec 23, 2021 |
| ASUSTek       | TUF GAMING X570-PRO WIFI... | [69d74c89b4](https://linux-hardware.org/?probe=69d74c89b4) | Dec 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [4453e33b88](https://linux-hardware.org/?probe=4453e33b88) | Dec 22, 2021 |
| ASRock        | B450 Pro4                   | [0832f6d0fd](https://linux-hardware.org/?probe=0832f6d0fd) | Dec 22, 2021 |
| ASUSTek       | P8Z77-M                     | [667e676c78](https://linux-hardware.org/?probe=667e676c78) | Dec 21, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [200701934f](https://linux-hardware.org/?probe=200701934f) | Dec 21, 2021 |
| ASRock        | A320M-DVS R4.0              | [c38dcdb848](https://linux-hardware.org/?probe=c38dcdb848) | Dec 21, 2021 |
| Dell          | 03NVJ6 A02                  | [685819bc74](https://linux-hardware.org/?probe=685819bc74) | Dec 20, 2021 |
| ASRock        | B450M-HDV R4.0              | [210f1589c4](https://linux-hardware.org/?probe=210f1589c4) | Dec 20, 2021 |
| ASRock        | B450M Pro4                  | [b40c57df26](https://linux-hardware.org/?probe=b40c57df26) | Dec 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [09d76b803c](https://linux-hardware.org/?probe=09d76b803c) | Dec 20, 2021 |
| Intel         | B75                         | [9178fa9053](https://linux-hardware.org/?probe=9178fa9053) | Dec 19, 2021 |
| ASRock        | B450M-HDV R4.0              | [35182a65bb](https://linux-hardware.org/?probe=35182a65bb) | Dec 19, 2021 |
| Lenovo        | SHARKBAY 31900058 STD       | [717b852409](https://linux-hardware.org/?probe=717b852409) | Dec 19, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [38a4bbf8d3](https://linux-hardware.org/?probe=38a4bbf8d3) | Dec 19, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f86ed2049c](https://linux-hardware.org/?probe=f86ed2049c) | Dec 19, 2021 |
| Dell          | 0HY9JP A02                  | [063c3ec5d2](https://linux-hardware.org/?probe=063c3ec5d2) | Dec 19, 2021 |
| ASUSTek       | P5Q PRO TURBO               | [4c845a464c](https://linux-hardware.org/?probe=4c845a464c) | Dec 19, 2021 |
| Acer          | Aspire XC-330               | [1803a4622c](https://linux-hardware.org/?probe=1803a4622c) | Dec 19, 2021 |
| ASUSTek       | Benicia                     | [e572d5ceff](https://linux-hardware.org/?probe=e572d5ceff) | Dec 19, 2021 |
| Shuttle       | FH61V                       | [39d341d8be](https://linux-hardware.org/?probe=39d341d8be) | Dec 19, 2021 |
| MSI           | MS-7053                     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| Unknown       | C51GM-M                     | [91386c4f7c](https://linux-hardware.org/?probe=91386c4f7c) | Dec 17, 2021 |
| Lenovo        | ThinkCentre M57e 9489W1U    | [ba5156ef68](https://linux-hardware.org/?probe=ba5156ef68) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [49e9492dd4](https://linux-hardware.org/?probe=49e9492dd4) | Dec 17, 2021 |
| Dell          | 0Y2K8N A01                  | [2e29930670](https://linux-hardware.org/?probe=2e29930670) | Dec 17, 2021 |
| Gigabyte      | H270M-DS3H-CF               | [dfbadf6708](https://linux-hardware.org/?probe=dfbadf6708) | Dec 17, 2021 |
| Intel         | B75                         | [95258dab55](https://linux-hardware.org/?probe=95258dab55) | Dec 17, 2021 |
| Unknown       | C51GM-M                     | [cd4d96fefa](https://linux-hardware.org/?probe=cd4d96fefa) | Dec 17, 2021 |
| Acer          | Aspire XC-330               | [61dd8de51b](https://linux-hardware.org/?probe=61dd8de51b) | Dec 16, 2021 |
| Dell          | 0D24M8 A01                  | [a306863279](https://linux-hardware.org/?probe=a306863279) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | [2acaeac0de](https://linux-hardware.org/?probe=2acaeac0de) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [2c39bc3721](https://linux-hardware.org/?probe=2c39bc3721) | Dec 14, 2021 |
| HP            | 18E5                        | [88f87a7a1b](https://linux-hardware.org/?probe=88f87a7a1b) | Dec 14, 2021 |
| ASUSTek       | AM1M-A                      | [5113655631](https://linux-hardware.org/?probe=5113655631) | Dec 14, 2021 |
| ASUSTek       | VM40B                       | [c53952beab](https://linux-hardware.org/?probe=c53952beab) | Dec 14, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [788c6b0550](https://linux-hardware.org/?probe=788c6b0550) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [b471a79340](https://linux-hardware.org/?probe=b471a79340) | Dec 13, 2021 |
| Dell          | 0M5DCD A00                  | [447bffefc3](https://linux-hardware.org/?probe=447bffefc3) | Dec 13, 2021 |
| Intel         | DQ87PG AAG74154-403         | [e2a6d57861](https://linux-hardware.org/?probe=e2a6d57861) | Dec 13, 2021 |
| Intel         | B75                         | [652828f7b9](https://linux-hardware.org/?probe=652828f7b9) | Dec 13, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | [6b33adaacf](https://linux-hardware.org/?probe=6b33adaacf) | Dec 13, 2021 |
| ASUSTek       | PRIME B350M-A               | [aa92a82326](https://linux-hardware.org/?probe=aa92a82326) | Dec 13, 2021 |
| ASUSTek       | P5QC                        | [8e659f2b89](https://linux-hardware.org/?probe=8e659f2b89) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [abb6a94373](https://linux-hardware.org/?probe=abb6a94373) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [d9e04ee743](https://linux-hardware.org/?probe=d9e04ee743) | Dec 12, 2021 |
| Gigabyte      | H97M-D3H                    | [1d768c3c63](https://linux-hardware.org/?probe=1d768c3c63) | Dec 12, 2021 |
| ASRock        | B450M Pro4                  | [6a8480268d](https://linux-hardware.org/?probe=6a8480268d) | Dec 12, 2021 |
| Dell          | 02YYK5 A01                  | [1301218290](https://linux-hardware.org/?probe=1301218290) | Dec 11, 2021 |
| HP            | 339A                        | [7081fc45a3](https://linux-hardware.org/?probe=7081fc45a3) | Dec 11, 2021 |
| HP            | 304Ah                       | [6d87535158](https://linux-hardware.org/?probe=6d87535158) | Dec 10, 2021 |
| eMachines     | EL1850G                     | [ccd7758cbe](https://linux-hardware.org/?probe=ccd7758cbe) | Dec 10, 2021 |
| ASUSTek       | NARRA3                      | [028ad01454](https://linux-hardware.org/?probe=028ad01454) | Dec 09, 2021 |
| Biostar       | A320MH                      | [fbbe7a436a](https://linux-hardware.org/?probe=fbbe7a436a) | Dec 09, 2021 |
| Biostar       | A320MH                      | [3870a17dfe](https://linux-hardware.org/?probe=3870a17dfe) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [0e19f8e2ae](https://linux-hardware.org/?probe=0e19f8e2ae) | Dec 09, 2021 |
| MSI           | MAG B560M MORTAR WIFI       | [a37d2cc42f](https://linux-hardware.org/?probe=a37d2cc42f) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [1a5b0a8d39](https://linux-hardware.org/?probe=1a5b0a8d39) | Dec 09, 2021 |
| MSI           | 970 GAMING                  | [f4d8f580dc](https://linux-hardware.org/?probe=f4d8f580dc) | Dec 09, 2021 |
| ASUSTek       | NARRA3                      | [c64aed90a9](https://linux-hardware.org/?probe=c64aed90a9) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| HP            | 87C3                        | [16cc7e0bcb](https://linux-hardware.org/?probe=16cc7e0bcb) | Dec 07, 2021 |
| HP            | 339A                        | [50c24f7d34](https://linux-hardware.org/?probe=50c24f7d34) | Dec 07, 2021 |
| HP            | 81B4 01                     | [1477bd5a44](https://linux-hardware.org/?probe=1477bd5a44) | Dec 07, 2021 |
| Dell          | 0T656F A01                  | [552210319c](https://linux-hardware.org/?probe=552210319c) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [2ce114a1c7](https://linux-hardware.org/?probe=2ce114a1c7) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [49fe509dd2](https://linux-hardware.org/?probe=49fe509dd2) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [e6b7b57ea7](https://linux-hardware.org/?probe=e6b7b57ea7) | Dec 04, 2021 |
| Dell          | 0G254H A00                  | [11897b38da](https://linux-hardware.org/?probe=11897b38da) | Dec 03, 2021 |
| HP            | 2B44                        | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [e39465a63b](https://linux-hardware.org/?probe=e39465a63b) | Dec 03, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ad90caf60d](https://linux-hardware.org/?probe=ad90caf60d) | Dec 03, 2021 |
| Pegatron      | JESSE                       | [9091bacc33](https://linux-hardware.org/?probe=9091bacc33) | Dec 03, 2021 |
| ASUSTek       | LEONITE                     | [704345be69](https://linux-hardware.org/?probe=704345be69) | Dec 03, 2021 |
| Biostar       | A780L3C                     | [a50e3d0532](https://linux-hardware.org/?probe=a50e3d0532) | Dec 02, 2021 |
| Foxconn       | 2A8C                        | [8d24862bd6](https://linux-hardware.org/?probe=8d24862bd6) | Dec 02, 2021 |
| Biostar       | A780L3C                     | [497f29a343](https://linux-hardware.org/?probe=497f29a343) | Dec 02, 2021 |
| Dell          | 0WR7PY A02                  | [1255f30eea](https://linux-hardware.org/?probe=1255f30eea) | Dec 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [bd33efb6f7](https://linux-hardware.org/?probe=bd33efb6f7) | Dec 01, 2021 |
| HP            | 339A                        | [4a377796cf](https://linux-hardware.org/?probe=4a377796cf) | Dec 01, 2021 |
| Dell          | 0PU052                      | [a943d9f217](https://linux-hardware.org/?probe=a943d9f217) | Dec 01, 2021 |
| Dell          | 0WR7PY A02                  | [d51c794107](https://linux-hardware.org/?probe=d51c794107) | Nov 30, 2021 |
| Dell          | 0WMJ54 A01                  | [5fa96d5863](https://linux-hardware.org/?probe=5fa96d5863) | Nov 30, 2021 |
| HP            | 8299                        | [6eb5c6d54a](https://linux-hardware.org/?probe=6eb5c6d54a) | Nov 30, 2021 |
| Medion        | MS-7707                     | [3d0a46f2ef](https://linux-hardware.org/?probe=3d0a46f2ef) | Nov 30, 2021 |
| ASRock        | H67DE3                      | [d710784470](https://linux-hardware.org/?probe=d710784470) | Nov 30, 2021 |
| HP            | 8299                        | [7bd1df0e4d](https://linux-hardware.org/?probe=7bd1df0e4d) | Nov 29, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [24b15affa6](https://linux-hardware.org/?probe=24b15affa6) | Nov 29, 2021 |
| ASUSTek       | P8Z77-V LX                  | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| ECS           | GeForce6100PM-M2            | [032a2baaca](https://linux-hardware.org/?probe=032a2baaca) | Nov 28, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [382bfc4a86](https://linux-hardware.org/?probe=382bfc4a86) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [cd296f933b](https://linux-hardware.org/?probe=cd296f933b) | Nov 28, 2021 |
| Gigabyte      | G31M-ES2L                   | [44c0cf428f](https://linux-hardware.org/?probe=44c0cf428f) | Nov 28, 2021 |
| MSI           | X370 GAMING PLUS            | [0b71d2652d](https://linux-hardware.org/?probe=0b71d2652d) | Nov 27, 2021 |
| Dell          | 0VNP2H A00                  | [803e55fd86](https://linux-hardware.org/?probe=803e55fd86) | Nov 27, 2021 |
| ASUSTek       | M4A78T-E                    | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [ae57475767](https://linux-hardware.org/?probe=ae57475767) | Nov 27, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [3925ce16ae](https://linux-hardware.org/?probe=3925ce16ae) | Nov 27, 2021 |
| Lenovo        | 36E7 SDK0J40700 WIN 3258... | [cd58d98b6a](https://linux-hardware.org/?probe=cd58d98b6a) | Nov 27, 2021 |
| ASRock        | B450M Pro4                  | [bb642022a6](https://linux-hardware.org/?probe=bb642022a6) | Nov 27, 2021 |
| ASRock        | ALiveNF6G-DVI               | [2761f434e8](https://linux-hardware.org/?probe=2761f434e8) | Nov 26, 2021 |
| Dell          | 0VNP2H A00                  | [fe9de9a896](https://linux-hardware.org/?probe=fe9de9a896) | Nov 25, 2021 |
| HP            | 18E7                        | [7385ca30d4](https://linux-hardware.org/?probe=7385ca30d4) | Nov 23, 2021 |
| Pegatron      | 2A86E01                     | [b57d9ec4a4](https://linux-hardware.org/?probe=b57d9ec4a4) | Nov 23, 2021 |
| Gigabyte      | H61N-USB3                   | [83e388363c](https://linux-hardware.org/?probe=83e388363c) | Nov 23, 2021 |
| Dell          | 0PU052                      | [a41541bab5](https://linux-hardware.org/?probe=a41541bab5) | Nov 23, 2021 |
| Gigabyte      | G41MT-S2                    | [8031417427](https://linux-hardware.org/?probe=8031417427) | Nov 23, 2021 |
| Intel         | DB65AL AAG12530-309         | [44c8025eee](https://linux-hardware.org/?probe=44c8025eee) | Nov 23, 2021 |
| MSI           | B360M PRO-VD                | [e1f68c6698](https://linux-hardware.org/?probe=e1f68c6698) | Nov 22, 2021 |
| Gigabyte      | H77M-D3H                    | [2819a870a8](https://linux-hardware.org/?probe=2819a870a8) | Nov 22, 2021 |
| HP            | 0AA4h                       | [22c6e4fffd](https://linux-hardware.org/?probe=22c6e4fffd) | Nov 22, 2021 |
| ASRock        | P67 Extreme6                | [54cd91039c](https://linux-hardware.org/?probe=54cd91039c) | Nov 22, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [fa922e6e20](https://linux-hardware.org/?probe=fa922e6e20) | Nov 22, 2021 |
| ASRock        | 775i945GZ                   | [8d3cfee95d](https://linux-hardware.org/?probe=8d3cfee95d) | Nov 22, 2021 |
| ASRock        | ALiveNF6G-DVI               | [23a839f917](https://linux-hardware.org/?probe=23a839f917) | Nov 21, 2021 |
| ASUSTek       | PRIME Z590M-PLUS            | [ae91e01910](https://linux-hardware.org/?probe=ae91e01910) | Nov 21, 2021 |
| Dell          | 03NVJ6 A02                  | [00a8a0ab87](https://linux-hardware.org/?probe=00a8a0ab87) | Nov 21, 2021 |
| Gigabyte      | B450M GAMING                | [2355c29da1](https://linux-hardware.org/?probe=2355c29da1) | Nov 21, 2021 |
| Gigabyte      | H55M-UD2H                   | [16e0d2d71a](https://linux-hardware.org/?probe=16e0d2d71a) | Nov 21, 2021 |
| Dell          | 0KWVT8 A00                  | [a6f003d198](https://linux-hardware.org/?probe=a6f003d198) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [24c2fc6f7b](https://linux-hardware.org/?probe=24c2fc6f7b) | Nov 20, 2021 |
| LattePanda    | Alpha                       | [4aa879f7ac](https://linux-hardware.org/?probe=4aa879f7ac) | Nov 20, 2021 |
| ASRock        | B450M Pro4 R2.0             | [8a53d67102](https://linux-hardware.org/?probe=8a53d67102) | Nov 19, 2021 |
| MSI           | 970 GAMING                  | [ac8f38525e](https://linux-hardware.org/?probe=ac8f38525e) | Nov 19, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| Dell          | 0KWVT8 A00                  | [93b90c3da4](https://linux-hardware.org/?probe=93b90c3da4) | Nov 18, 2021 |
| ASRock        | G31M-VS2                    | [8bc6042d3f](https://linux-hardware.org/?probe=8bc6042d3f) | Nov 17, 2021 |
| ASRock        | X370M-HDV                   | [a991fee412](https://linux-hardware.org/?probe=a991fee412) | Nov 17, 2021 |
| Dell          | 0GXM1W A01                  | [7e9f638277](https://linux-hardware.org/?probe=7e9f638277) | Nov 17, 2021 |
| ASUSTek       | P5KPL-AM                    | [0cae2ebf49](https://linux-hardware.org/?probe=0cae2ebf49) | Nov 16, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [bb50b7d97c](https://linux-hardware.org/?probe=bb50b7d97c) | Nov 16, 2021 |
| MSI           | 2A9C                        | [80ef0caf18](https://linux-hardware.org/?probe=80ef0caf18) | Nov 15, 2021 |
| MSI           | 2A9C                        | [44e1dcea05](https://linux-hardware.org/?probe=44e1dcea05) | Nov 15, 2021 |
| Gigabyte      | H170-D3HP-CF                | [e90a1881c7](https://linux-hardware.org/?probe=e90a1881c7) | Nov 14, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [a92c32b60a](https://linux-hardware.org/?probe=a92c32b60a) | Nov 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [542b1538bf](https://linux-hardware.org/?probe=542b1538bf) | Nov 14, 2021 |
| HP            | 8653 A                      | [88b53507c9](https://linux-hardware.org/?probe=88b53507c9) | Nov 13, 2021 |
| HP            | 3048h                       | [200317605d](https://linux-hardware.org/?probe=200317605d) | Nov 13, 2021 |
| Dell          | 0GXM1W A02                  | [d446993ec9](https://linux-hardware.org/?probe=d446993ec9) | Nov 13, 2021 |
| ASUSTek       | P5G41T-M LX3                | [8977322809](https://linux-hardware.org/?probe=8977322809) | Nov 13, 2021 |
| HP            | 1790                        | [e86cdf904a](https://linux-hardware.org/?probe=e86cdf904a) | Nov 12, 2021 |
| ASUSTek       | M5A78L LE                   | [d342b54224](https://linux-hardware.org/?probe=d342b54224) | Nov 12, 2021 |
| HP            | 339A                        | [6dc037bf1f](https://linux-hardware.org/?probe=6dc037bf1f) | Nov 11, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [d0eae9ef10](https://linux-hardware.org/?probe=d0eae9ef10) | Nov 11, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [7a2464824d](https://linux-hardware.org/?probe=7a2464824d) | Nov 11, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | [c8e4265515](https://linux-hardware.org/?probe=c8e4265515) | Nov 11, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [eece1d5528](https://linux-hardware.org/?probe=eece1d5528) | Nov 11, 2021 |
| ASUSTek       | H81M-P PLUS                 | [1841ab2aff](https://linux-hardware.org/?probe=1841ab2aff) | Nov 10, 2021 |
| ASUSTek       | A68HM-PLUS                  | [0e688f660f](https://linux-hardware.org/?probe=0e688f660f) | Nov 10, 2021 |
| ASUSTek       | M5A97                       | [20a705fd56](https://linux-hardware.org/?probe=20a705fd56) | Nov 10, 2021 |
| HP            | 8653 A                      | [f84c67582a](https://linux-hardware.org/?probe=f84c67582a) | Nov 09, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [e7579f2fcf](https://linux-hardware.org/?probe=e7579f2fcf) | Nov 09, 2021 |
| HP            | 1790                        | [6030cabe49](https://linux-hardware.org/?probe=6030cabe49) | Nov 09, 2021 |
| HP            | 1825                        | [7cf6c3590a](https://linux-hardware.org/?probe=7cf6c3590a) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [886c08185e](https://linux-hardware.org/?probe=886c08185e) | Nov 08, 2021 |
| Gigabyte      | B75M-D3H                    | [e141b2d36a](https://linux-hardware.org/?probe=e141b2d36a) | Nov 08, 2021 |
| Foxconn       | H61M/H61M-S                 | [62ae26dca0](https://linux-hardware.org/?probe=62ae26dca0) | Nov 07, 2021 |
| Dell          | 0HY9JP A00                  | [05c38bf92c](https://linux-hardware.org/?probe=05c38bf92c) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [f57575ffaf](https://linux-hardware.org/?probe=f57575ffaf) | Nov 06, 2021 |
| Dell          | 0VNP2H A02                  | [5402226d98](https://linux-hardware.org/?probe=5402226d98) | Nov 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | [e6e813115f](https://linux-hardware.org/?probe=e6e813115f) | Nov 06, 2021 |
| HP            | 0A98h                       | [110c37e799](https://linux-hardware.org/?probe=110c37e799) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| Dell          | 0NKW6Y A00                  | [82a09e132d](https://linux-hardware.org/?probe=82a09e132d) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [4be9b40ea1](https://linux-hardware.org/?probe=4be9b40ea1) | Nov 05, 2021 |
| ASUSTek       | PRIME H410M-A               | [173116149c](https://linux-hardware.org/?probe=173116149c) | Nov 05, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [1383828428](https://linux-hardware.org/?probe=1383828428) | Nov 05, 2021 |
| Gigabyte      | Z97X-UD7 TH-CF              | [f5ee7a26d5](https://linux-hardware.org/?probe=f5ee7a26d5) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [3e4d5dd09d](https://linux-hardware.org/?probe=3e4d5dd09d) | Nov 05, 2021 |
| Foxconn       | H61M/H61M-S                 | [7f3894059d](https://linux-hardware.org/?probe=7f3894059d) | Nov 04, 2021 |
| HP            | 18E4                        | [3069846b25](https://linux-hardware.org/?probe=3069846b25) | Nov 04, 2021 |
| MSI           | G41M-P23                    | [82e51e3f78](https://linux-hardware.org/?probe=82e51e3f78) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | [d7a405763d](https://linux-hardware.org/?probe=d7a405763d) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [2d26d5b578](https://linux-hardware.org/?probe=2d26d5b578) | Nov 02, 2021 |
| ASUSTek       | P8Z77-V LX                  | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| ASUSTek       | M11AD                       | [0cb5032c53](https://linux-hardware.org/?probe=0cb5032c53) | Nov 02, 2021 |
| Gigabyte      | GA-E6010N                   | [3c81474040](https://linux-hardware.org/?probe=3c81474040) | Nov 01, 2021 |
| Gigabyte      | GA-E6010N                   | [2a2aaffd43](https://linux-hardware.org/?probe=2a2aaffd43) | Nov 01, 2021 |
| ASRock        | FM2A55M-HD+                 | [42cd4d28bd](https://linux-hardware.org/?probe=42cd4d28bd) | Nov 01, 2021 |
| eMachines     | EL1850G                     | [01dbf1b5ec](https://linux-hardware.org/?probe=01dbf1b5ec) | Oct 31, 2021 |
| MSI           | P55-CD53                    | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Unknown       | Unknown                     | [75cc8a67e9](https://linux-hardware.org/?probe=75cc8a67e9) | Oct 31, 2021 |
| ASRock        | B85M-HDS                    | [111e98ddef](https://linux-hardware.org/?probe=111e98ddef) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [6cee757cf0](https://linux-hardware.org/?probe=6cee757cf0) | Oct 31, 2021 |
| ASUSTek       | P8H61-M LE/CSM R2.0         | [96c9053284](https://linux-hardware.org/?probe=96c9053284) | Oct 31, 2021 |
| Dell          | 06NWYK A01                  | [497c824fd5](https://linux-hardware.org/?probe=497c824fd5) | Oct 31, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [0981774043](https://linux-hardware.org/?probe=0981774043) | Oct 30, 2021 |
| ASRock        | B85M-HDS                    | [69dd0cf598](https://linux-hardware.org/?probe=69dd0cf598) | Oct 30, 2021 |
| Dell          | 06NWYK A01                  | [1d0625eb89](https://linux-hardware.org/?probe=1d0625eb89) | Oct 30, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [867e533368](https://linux-hardware.org/?probe=867e533368) | Oct 30, 2021 |
| ASUSTek       | P5K SE/EPU                  | [80adff7646](https://linux-hardware.org/?probe=80adff7646) | Oct 30, 2021 |
| Dell          | 0GY6Y8 A02                  | [1a267b14d3](https://linux-hardware.org/?probe=1a267b14d3) | Oct 29, 2021 |
| Dell          | 0GY6Y8 A02                  | [5b4cea000b](https://linux-hardware.org/?probe=5b4cea000b) | Oct 29, 2021 |
| ASRock        | B450 Gaming K4              | [b67ec8af25](https://linux-hardware.org/?probe=b67ec8af25) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [4e19df8e3c](https://linux-hardware.org/?probe=4e19df8e3c) | Oct 29, 2021 |
| Dell          | 0VNP2H A02                  | [c220480b4c](https://linux-hardware.org/?probe=c220480b4c) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [a73fabcd4c](https://linux-hardware.org/?probe=a73fabcd4c) | Oct 28, 2021 |
| Gigabyte      | X570 AORUS ELITE            | [528cec41bc](https://linux-hardware.org/?probe=528cec41bc) | Oct 28, 2021 |
| Alienware     | 08PG26 A00                  | [bb2fd997ab](https://linux-hardware.org/?probe=bb2fd997ab) | Oct 28, 2021 |
| ASRock        | FM2A88X Extreme6+           | [b676d9030a](https://linux-hardware.org/?probe=b676d9030a) | Oct 28, 2021 |
| MSI           | MAG B550M MORTAR            | [08819513f2](https://linux-hardware.org/?probe=08819513f2) | Oct 27, 2021 |
| MSI           | MAG B550M MORTAR            | [4207c6eaac](https://linux-hardware.org/?probe=4207c6eaac) | Oct 27, 2021 |
| ASUSTek       | PRIME Z270-P                | [dfb2070b53](https://linux-hardware.org/?probe=dfb2070b53) | Oct 26, 2021 |
| Alienware     | 08PG26 A00                  | [7d6b559bf8](https://linux-hardware.org/?probe=7d6b559bf8) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| ASRock        | FM2A55M-HD+                 | [a1cf5282ba](https://linux-hardware.org/?probe=a1cf5282ba) | Oct 25, 2021 |
| ASRock        | H110M-HDS R3.0              | [718ad346b7](https://linux-hardware.org/?probe=718ad346b7) | Oct 25, 2021 |
| MSI           | 2AE0                        | [64a3b3ae41](https://linux-hardware.org/?probe=64a3b3ae41) | Oct 24, 2021 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [cc46a59d6c](https://linux-hardware.org/?probe=cc46a59d6c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Dell          | 0VHXCD A00                  | [7c99a6ed29](https://linux-hardware.org/?probe=7c99a6ed29) | Oct 22, 2021 |
| ASRock        | 970 Pro3 R2.0               | [915961c057](https://linux-hardware.org/?probe=915961c057) | Oct 22, 2021 |
| Biostar       | A68N-5100                   | [bc5b7a2417](https://linux-hardware.org/?probe=bc5b7a2417) | Oct 22, 2021 |
| MSI           | Z68A-G43                    | [b781916d8e](https://linux-hardware.org/?probe=b781916d8e) | Oct 22, 2021 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [baee5192b6](https://linux-hardware.org/?probe=baee5192b6) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| HP            | 1589                        | [49c747efad](https://linux-hardware.org/?probe=49c747efad) | Oct 21, 2021 |
| Unknown       | Phitronics G41-M3           | [a6ccedb5bd](https://linux-hardware.org/?probe=a6ccedb5bd) | Oct 20, 2021 |
| Unknown       | Phitronics G41-M3           | [fbe886aee7](https://linux-hardware.org/?probe=fbe886aee7) | Oct 20, 2021 |
| Unknown       | Unknown                     | [8c412b3b5b](https://linux-hardware.org/?probe=8c412b3b5b) | Oct 20, 2021 |
| Gigabyte      | B75M-D2V                    | [9fc60b0ba8](https://linux-hardware.org/?probe=9fc60b0ba8) | Oct 19, 2021 |
| HP            | 2B38                        | [2cf327f158](https://linux-hardware.org/?probe=2cf327f158) | Oct 18, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [2f5f509752](https://linux-hardware.org/?probe=2f5f509752) | Oct 18, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [a7ea75f7c5](https://linux-hardware.org/?probe=a7ea75f7c5) | Oct 18, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | [9f22e32d08](https://linux-hardware.org/?probe=9f22e32d08) | Oct 17, 2021 |
| ASUSTek       | P6T                         | [69397b40d4](https://linux-hardware.org/?probe=69397b40d4) | Oct 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [058d7e8e3e](https://linux-hardware.org/?probe=058d7e8e3e) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [ce2e0740c8](https://linux-hardware.org/?probe=ce2e0740c8) | Oct 17, 2021 |
| ASUSTek       | H81M-PLUS                   | [a3dbbf3c03](https://linux-hardware.org/?probe=a3dbbf3c03) | Oct 17, 2021 |
| Lenovo        | SHARKBAY NOK                | [5de4ff60b0](https://linux-hardware.org/?probe=5de4ff60b0) | Oct 16, 2021 |
| Gigabyte      | H61M-S2PV                   | [e3806f5c09](https://linux-hardware.org/?probe=e3806f5c09) | Oct 16, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [a89127ff6a](https://linux-hardware.org/?probe=a89127ff6a) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [7de05cdbc3](https://linux-hardware.org/?probe=7de05cdbc3) | Oct 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [66b0e77a10](https://linux-hardware.org/?probe=66b0e77a10) | Oct 15, 2021 |
| Dell          | 0VHXCD A00                  | [ccd75d2752](https://linux-hardware.org/?probe=ccd75d2752) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H WIFI-CF          | [c0beced761](https://linux-hardware.org/?probe=c0beced761) | Oct 14, 2021 |
| ASUSTek       | M5A78L                      | [a027b0f5ba](https://linux-hardware.org/?probe=a027b0f5ba) | Oct 12, 2021 |
| HP            | 81C7 MVB 0C                 | [23d528f392](https://linux-hardware.org/?probe=23d528f392) | Oct 12, 2021 |
| ASUSTek       | M5A78L                      | [071d7e45a0](https://linux-hardware.org/?probe=071d7e45a0) | Oct 11, 2021 |
| Biostar       | G41-M7                      | [94efede651](https://linux-hardware.org/?probe=94efede651) | Oct 10, 2021 |
| ASUSTek       | P7H55-M PRO                 | [1892bf50b9](https://linux-hardware.org/?probe=1892bf50b9) | Oct 09, 2021 |
| HP            | 81C7 MVB 0C                 | [5bfcd88031](https://linux-hardware.org/?probe=5bfcd88031) | Oct 09, 2021 |
| Biostar       | G41-M7                      | [4f1889a1de](https://linux-hardware.org/?probe=4f1889a1de) | Oct 09, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [f0a1062216](https://linux-hardware.org/?probe=f0a1062216) | Oct 09, 2021 |
| Dell          | 0VHXCD A00                  | [7a2b25ff42](https://linux-hardware.org/?probe=7a2b25ff42) | Oct 08, 2021 |
| Dell          | 04Y8V0 A01                  | [453beab8c3](https://linux-hardware.org/?probe=453beab8c3) | Oct 08, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [c9d3dce156](https://linux-hardware.org/?probe=c9d3dce156) | Oct 08, 2021 |
| ASUSTek       | CM5570                      | [75b8bca0fa](https://linux-hardware.org/?probe=75b8bca0fa) | Oct 07, 2021 |
| HP            | 8591                        | [22dca8a98c](https://linux-hardware.org/?probe=22dca8a98c) | Oct 07, 2021 |
| Dell          | 0VHXCD A00                  | [7f81996b23](https://linux-hardware.org/?probe=7f81996b23) | Oct 07, 2021 |
| Dell          | 0D6H9T A02                  | [42b9320d55](https://linux-hardware.org/?probe=42b9320d55) | Oct 06, 2021 |
| Gigabyte      | H61M-S2PV                   | [ed77d40eeb](https://linux-hardware.org/?probe=ed77d40eeb) | Oct 05, 2021 |
| ASUSTek       | STRIX Z270E GAMING          | [173104cfcf](https://linux-hardware.org/?probe=173104cfcf) | Oct 04, 2021 |
| ASUSTek       | PRIME B360M-K               | [163b47753d](https://linux-hardware.org/?probe=163b47753d) | Oct 03, 2021 |
| MSI           | B150M MORTAR                | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B560M AORUS ELITE           | [2c73a09463](https://linux-hardware.org/?probe=2c73a09463) | Oct 03, 2021 |
| Gigabyte      | H81M-S2PV                   | [a02538183c](https://linux-hardware.org/?probe=a02538183c) | Oct 01, 2021 |
| Gigabyte      | 970A-UD3P                   | [10d8a84245](https://linux-hardware.org/?probe=10d8a84245) | Oct 01, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | [2a8da86d79](https://linux-hardware.org/?probe=2a8da86d79) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [b6eca9083a](https://linux-hardware.org/?probe=b6eca9083a) | Oct 01, 2021 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | [415f0d9244](https://linux-hardware.org/?probe=415f0d9244) | Oct 01, 2021 |
| Dell          | 0HN7XN A00                  | [cc8a68bbd6](https://linux-hardware.org/?probe=cc8a68bbd6) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [8137456421](https://linux-hardware.org/?probe=8137456421) | Sep 30, 2021 |
| ASRock        | Z490 Extreme4               | [3411428e31](https://linux-hardware.org/?probe=3411428e31) | Sep 30, 2021 |
| Dell          | 0HN7XN A00                  | [5f56956871](https://linux-hardware.org/?probe=5f56956871) | Sep 30, 2021 |
| ASRock        | H61M-VG4                    | [33c6d2d214](https://linux-hardware.org/?probe=33c6d2d214) | Sep 30, 2021 |
| Lenovo        | IdeaCentre K330             | [ed6e765fea](https://linux-hardware.org/?probe=ed6e765fea) | Sep 29, 2021 |
| Gigabyte      | J4005ND2P-CF                | [699985f9e6](https://linux-hardware.org/?probe=699985f9e6) | Sep 28, 2021 |
| Gigabyte      | J4005ND2P-CF                | [d82bdfcf17](https://linux-hardware.org/?probe=d82bdfcf17) | Sep 28, 2021 |
| ASUSTek       | PRIME B450M-A               | [d5b8eb94d7](https://linux-hardware.org/?probe=d5b8eb94d7) | Sep 28, 2021 |
| Dell          | 0TNXNR A01                  | [781c19cc33](https://linux-hardware.org/?probe=781c19cc33) | Sep 27, 2021 |
| Dell          | 0D6H9T A02                  | [30e914656e](https://linux-hardware.org/?probe=30e914656e) | Sep 27, 2021 |
| Unknown       | Unknown                     | [0625659706](https://linux-hardware.org/?probe=0625659706) | Sep 27, 2021 |
| Dell          | 0TP406                      | [39f9e67ae2](https://linux-hardware.org/?probe=39f9e67ae2) | Sep 26, 2021 |
| HP            | 18E7                        | [94f692683b](https://linux-hardware.org/?probe=94f692683b) | Sep 26, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [4bc5eb3bbc](https://linux-hardware.org/?probe=4bc5eb3bbc) | Sep 25, 2021 |
| eMachines     | EL1850G                     | [f5b47069bb](https://linux-hardware.org/?probe=f5b47069bb) | Sep 25, 2021 |
| Lenovo        | ThinkCentre M58 3231W2Y     | [a2da2733ac](https://linux-hardware.org/?probe=a2da2733ac) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [5cc1a01b2f](https://linux-hardware.org/?probe=5cc1a01b2f) | Sep 25, 2021 |
| Gigabyte      | GA-78LMT-USB3               | [2b341862f1](https://linux-hardware.org/?probe=2b341862f1) | Sep 25, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | [65ebe53761](https://linux-hardware.org/?probe=65ebe53761) | Sep 25, 2021 |
| MSI           | B75MA-P45                   | [663af51c43](https://linux-hardware.org/?probe=663af51c43) | Sep 24, 2021 |
| MSI           | B75MA-P45                   | [4d4844cfbe](https://linux-hardware.org/?probe=4d4844cfbe) | Sep 24, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [dc87018670](https://linux-hardware.org/?probe=dc87018670) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8617cbbc27](https://linux-hardware.org/?probe=8617cbbc27) | Sep 24, 2021 |
| ASRock        | 775VM800                    | [e07158e4ab](https://linux-hardware.org/?probe=e07158e4ab) | Sep 24, 2021 |
| HP            | 18E7                        | [29fa39d7e9](https://linux-hardware.org/?probe=29fa39d7e9) | Sep 23, 2021 |
| ASRock        | 880GMH/U3S3                 | [ec55312287](https://linux-hardware.org/?probe=ec55312287) | Sep 23, 2021 |
| Gigabyte      | B75M-D3H                    | [cb23f25d7f](https://linux-hardware.org/?probe=cb23f25d7f) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [74410f0d0c](https://linux-hardware.org/?probe=74410f0d0c) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ad81766325](https://linux-hardware.org/?probe=ad81766325) | Sep 23, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [bc7d0dc232](https://linux-hardware.org/?probe=bc7d0dc232) | Sep 22, 2021 |
| Lenovo        | ThinkCentre M81 0385AW6     | [529a9f4c74](https://linux-hardware.org/?probe=529a9f4c74) | Sep 22, 2021 |
| HP            | 213D A01                    | [8d4dd8359c](https://linux-hardware.org/?probe=8d4dd8359c) | Sep 21, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [3354edcb58](https://linux-hardware.org/?probe=3354edcb58) | Sep 21, 2021 |
| Gigabyte      | B75M-D3H                    | [3ef59689e6](https://linux-hardware.org/?probe=3ef59689e6) | Sep 21, 2021 |
| MSI           | H81M-E33                    | [5ef84c22e6](https://linux-hardware.org/?probe=5ef84c22e6) | Sep 20, 2021 |
| MSI           | H81M-E33                    | [db96085729](https://linux-hardware.org/?probe=db96085729) | Sep 20, 2021 |
| ASUSTek       | PRIME B450-PLUS             | [a0b7d0cf25](https://linux-hardware.org/?probe=a0b7d0cf25) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c05636068f](https://linux-hardware.org/?probe=c05636068f) | Sep 20, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1a012b3021](https://linux-hardware.org/?probe=1a012b3021) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [b9259e3604](https://linux-hardware.org/?probe=b9259e3604) | Sep 20, 2021 |
| ASUSTek       | M5A78L-M LX V2              | [9eb1254056](https://linux-hardware.org/?probe=9eb1254056) | Sep 19, 2021 |
| Gigabyte      | Z77-D3H                     | [c86625aa34](https://linux-hardware.org/?probe=c86625aa34) | Sep 19, 2021 |
| HP            | 2B28                        | [14681c925a](https://linux-hardware.org/?probe=14681c925a) | Sep 19, 2021 |
| Sapphire T... | PURE PLATINUM 970A-PLUS     | [d64d86eced](https://linux-hardware.org/?probe=d64d86eced) | Sep 19, 2021 |
| ASRock        | FM2A58M-DG3+                | [183fc0dd5e](https://linux-hardware.org/?probe=183fc0dd5e) | Sep 18, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [bc3e2da7f3](https://linux-hardware.org/?probe=bc3e2da7f3) | Sep 18, 2021 |
| Gigabyte      | A320M-S2H-CF                | [e8f361170f](https://linux-hardware.org/?probe=e8f361170f) | Sep 18, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [30f36dc15d](https://linux-hardware.org/?probe=30f36dc15d) | Sep 17, 2021 |
| ASRock        | B450 Pro4                   | [042032eec7](https://linux-hardware.org/?probe=042032eec7) | Sep 16, 2021 |
| Intel         | X99                         | [814b3326d1](https://linux-hardware.org/?probe=814b3326d1) | Sep 15, 2021 |
| NCR           | Talladega                   | [95445fa221](https://linux-hardware.org/?probe=95445fa221) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [93a071ca7e](https://linux-hardware.org/?probe=93a071ca7e) | Sep 14, 2021 |
| Foxconn       | 17A0                        | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| MSI           | B75MA-P45                   | [874dcada55](https://linux-hardware.org/?probe=874dcada55) | Sep 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [b3b1991c64](https://linux-hardware.org/?probe=b3b1991c64) | Sep 14, 2021 |
| ASUSTek       | NARRA3                      | [93db4618cc](https://linux-hardware.org/?probe=93db4618cc) | Sep 14, 2021 |
| ASUSTek       | Benicia                     | [2a764dd662](https://linux-hardware.org/?probe=2a764dd662) | Sep 13, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [6928772253](https://linux-hardware.org/?probe=6928772253) | Sep 12, 2021 |
| ASUSTek       | Maximus VIII RANGER         | [93a0d7ac6a](https://linux-hardware.org/?probe=93a0d7ac6a) | Sep 12, 2021 |
| HP            | 339A                        | [9284a70a92](https://linux-hardware.org/?probe=9284a70a92) | Sep 12, 2021 |
| ASUSTek       | P5Q                         | [8693b86435](https://linux-hardware.org/?probe=8693b86435) | Sep 12, 2021 |
| NCR           | Talladega                   | [6de6d8c2a3](https://linux-hardware.org/?probe=6de6d8c2a3) | Sep 12, 2021 |
| ASUSTek       | NARRA3                      | [6b02d3fa6f](https://linux-hardware.org/?probe=6b02d3fa6f) | Sep 11, 2021 |
| Gigabyte      | 970A-DS3P                   | [8b0f703471](https://linux-hardware.org/?probe=8b0f703471) | Sep 11, 2021 |
| Lenovo        | SDK0E50519 WIN              | [7c58527193](https://linux-hardware.org/?probe=7c58527193) | Sep 11, 2021 |
| Intel         | X79M-S                      | [95d22f6e90](https://linux-hardware.org/?probe=95d22f6e90) | Sep 11, 2021 |
| ASUSTek       | P5GC-MX/1333                | [1ff7b16ce4](https://linux-hardware.org/?probe=1ff7b16ce4) | Sep 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [dab9a23b27](https://linux-hardware.org/?probe=dab9a23b27) | Sep 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [34e6b7697f](https://linux-hardware.org/?probe=34e6b7697f) | Sep 09, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [5ce713a2f7](https://linux-hardware.org/?probe=5ce713a2f7) | Sep 09, 2021 |
| ASUSTek       | NARRA3                      | [52b22746e0](https://linux-hardware.org/?probe=52b22746e0) | Sep 09, 2021 |
| HP            | 2187 A01                    | [0c11e3b726](https://linux-hardware.org/?probe=0c11e3b726) | Sep 09, 2021 |
| MSI           | B450M MORTAR MAX            | [f40c6b596c](https://linux-hardware.org/?probe=f40c6b596c) | Sep 08, 2021 |
| Dell          | 09KPNV A01                  | [f3c9b271f1](https://linux-hardware.org/?probe=f3c9b271f1) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [7dbf053877](https://linux-hardware.org/?probe=7dbf053877) | Sep 08, 2021 |
| MSI           | H81M-P33                    | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [17c58396b6](https://linux-hardware.org/?probe=17c58396b6) | Sep 08, 2021 |
| MSI           | B450M MORTAR MAX            | [dfe73847d3](https://linux-hardware.org/?probe=dfe73847d3) | Sep 08, 2021 |
| Dell          | 0D28YY A03                  | [3eb7b9cb7b](https://linux-hardware.org/?probe=3eb7b9cb7b) | Sep 08, 2021 |
| ASUSTek       | P5G41T-M LX3                | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Unknown       | Unknown                     | [b00795951c](https://linux-hardware.org/?probe=b00795951c) | Sep 07, 2021 |
| MSI           | B560M PRO-VDH               | [807eed7553](https://linux-hardware.org/?probe=807eed7553) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [3f08533d5f](https://linux-hardware.org/?probe=3f08533d5f) | Sep 06, 2021 |
| ASRock        | Q1900M                      | [d342919044](https://linux-hardware.org/?probe=d342919044) | Sep 06, 2021 |
| Intel         | X79M-S                      | [e45160873d](https://linux-hardware.org/?probe=e45160873d) | Sep 06, 2021 |
| ASUSTek       | M5A97                       | [28754f0456](https://linux-hardware.org/?probe=28754f0456) | Sep 06, 2021 |
| Gigabyte      | G31M-ES2L                   | [d94c35ce11](https://linux-hardware.org/?probe=d94c35ce11) | Sep 05, 2021 |
| MSI           | IONA                        | [8a4454604a](https://linux-hardware.org/?probe=8a4454604a) | Sep 05, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [791768dfbd](https://linux-hardware.org/?probe=791768dfbd) | Sep 04, 2021 |
| MSI           | IONA                        | [b775cef84a](https://linux-hardware.org/?probe=b775cef84a) | Sep 04, 2021 |
| ASUSTek       | NARRA3                      | [920ab9b385](https://linux-hardware.org/?probe=920ab9b385) | Sep 04, 2021 |
| Gigabyte      | Z490 AORUS ELITE            | [149099265c](https://linux-hardware.org/?probe=149099265c) | Sep 04, 2021 |
| Intel         | DQ77MK AAG39642-500         | [391c101a92](https://linux-hardware.org/?probe=391c101a92) | Sep 04, 2021 |
| HP            | 2B4B                        | [d36296bddf](https://linux-hardware.org/?probe=d36296bddf) | Sep 04, 2021 |
| ASUSTek       | Z170I PRO GAMING            | [9e6ccaa1f3](https://linux-hardware.org/?probe=9e6ccaa1f3) | Sep 04, 2021 |
| Biostar       | X470NH                      | [f0449b9946](https://linux-hardware.org/?probe=f0449b9946) | Sep 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | [126d9974b1](https://linux-hardware.org/?probe=126d9974b1) | Sep 03, 2021 |
| HP            | 1497                        | [fd4cf5c840](https://linux-hardware.org/?probe=fd4cf5c840) | Sep 01, 2021 |
| Gigabyte      | B460M DS3H                  | [ef23780b19](https://linux-hardware.org/?probe=ef23780b19) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [baa289fe51](https://linux-hardware.org/?probe=baa289fe51) | Aug 31, 2021 |
| Positivo      | POS-PIH81DI                 | [cc326a093e](https://linux-hardware.org/?probe=cc326a093e) | Aug 31, 2021 |
| HP            | 339A                        | [5a5ab8d1c2](https://linux-hardware.org/?probe=5a5ab8d1c2) | Aug 31, 2021 |
| HP            | 339A                        | [c0043e4c4c](https://linux-hardware.org/?probe=c0043e4c4c) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [4c711d446d](https://linux-hardware.org/?probe=4c711d446d) | Aug 31, 2021 |
| ASUSTek       | TUF GAMING B550-PLUS        | [efb9bccc60](https://linux-hardware.org/?probe=efb9bccc60) | Aug 31, 2021 |
| Intel         | DQ77MK AAG39642-500         | [000d760a55](https://linux-hardware.org/?probe=000d760a55) | Aug 30, 2021 |
| Positivo      | POS-PIH81DI                 | [3b05a7b317](https://linux-hardware.org/?probe=3b05a7b317) | Aug 30, 2021 |
| MSI           | Z87-G43                     | [a219ff197d](https://linux-hardware.org/?probe=a219ff197d) | Aug 29, 2021 |
| MSI           | MPG X570 GAMING PLUS        | [01a43874df](https://linux-hardware.org/?probe=01a43874df) | Aug 28, 2021 |
| ASUSTek       | PRIME A320M-K               | [f7a948129f](https://linux-hardware.org/?probe=f7a948129f) | Aug 28, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | [5cd3f43e28](https://linux-hardware.org/?probe=5cd3f43e28) | Aug 28, 2021 |
| Gigabyte      | A320M-S2H-CF                | [6ed5f8c32b](https://linux-hardware.org/?probe=6ed5f8c32b) | Aug 27, 2021 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [b01269fbc1](https://linux-hardware.org/?probe=b01269fbc1) | Aug 27, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [51661e959e](https://linux-hardware.org/?probe=51661e959e) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3a7eb89cd8](https://linux-hardware.org/?probe=3a7eb89cd8) | Aug 25, 2021 |
| HP            | 802E                        | [3ee51e8a56](https://linux-hardware.org/?probe=3ee51e8a56) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [314859d762](https://linux-hardware.org/?probe=314859d762) | Aug 25, 2021 |
| ASUSTek       | P8Z77-V LX                  | [faaf8bc158](https://linux-hardware.org/?probe=faaf8bc158) | Aug 25, 2021 |
| Dell          | 088DT1 A01                  | [8620323354](https://linux-hardware.org/?probe=8620323354) | Aug 25, 2021 |
| Dell          | 0TP406                      | [72a3d9ac12](https://linux-hardware.org/?probe=72a3d9ac12) | Aug 25, 2021 |
| HP            | 2B4B                        | [4c5411522b](https://linux-hardware.org/?probe=4c5411522b) | Aug 25, 2021 |
| Gigabyte      | B85M-D3H                    | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| ASUSTek       | P8Z77-V LE                  | [a720e3326a](https://linux-hardware.org/?probe=a720e3326a) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | [e6f053c5be](https://linux-hardware.org/?probe=e6f053c5be) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [15175b4f4f](https://linux-hardware.org/?probe=15175b4f4f) | Aug 22, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | [02ccc1eb70](https://linux-hardware.org/?probe=02ccc1eb70) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | [372a125910](https://linux-hardware.org/?probe=372a125910) | Aug 22, 2021 |
| Lenovo        | Unknown                     | [b4e9579228](https://linux-hardware.org/?probe=b4e9579228) | Aug 21, 2021 |
| Lenovo        | Unknown                     | [12088eed17](https://linux-hardware.org/?probe=12088eed17) | Aug 21, 2021 |
| MSI           | B450M PRO-M2 MAX            | [68c6a2734b](https://linux-hardware.org/?probe=68c6a2734b) | Aug 21, 2021 |
| Intel         | DB75EN AAG39650-303         | [4bbb9f60f9](https://linux-hardware.org/?probe=4bbb9f60f9) | Aug 20, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [63cbb9e7fd](https://linux-hardware.org/?probe=63cbb9e7fd) | Aug 19, 2021 |
| MSI           | Z97 XPOWER AC               | [c68138439d](https://linux-hardware.org/?probe=c68138439d) | Aug 19, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [d78450d852](https://linux-hardware.org/?probe=d78450d852) | Aug 19, 2021 |
| Acer          | Aspire XC-605G              | [8bb6f8ef72](https://linux-hardware.org/?probe=8bb6f8ef72) | Aug 18, 2021 |
| ASUSTek       | B85M-G R2.0                 | [daf6bf889f](https://linux-hardware.org/?probe=daf6bf889f) | Aug 18, 2021 |
| MSI           | Z270-A PRO                  | [3be5b7f90e](https://linux-hardware.org/?probe=3be5b7f90e) | Aug 18, 2021 |
| Gigabyte      | B550M DS3H                  | [4b687b4c17](https://linux-hardware.org/?probe=4b687b4c17) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [97b71d18de](https://linux-hardware.org/?probe=97b71d18de) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [06872ddde7](https://linux-hardware.org/?probe=06872ddde7) | Aug 16, 2021 |
| ASUSTek       | Z97-C                       | [a1f448c1f6](https://linux-hardware.org/?probe=a1f448c1f6) | Aug 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | [fb7eb46b29](https://linux-hardware.org/?probe=fb7eb46b29) | Aug 11, 2021 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [fb8a0b07d1](https://linux-hardware.org/?probe=fb8a0b07d1) | Aug 10, 2021 |
| ASUSTek       | M5A97 LE R2.0               | [4d9eaaf5a8](https://linux-hardware.org/?probe=4d9eaaf5a8) | Aug 09, 2021 |
| Gigabyte      | B550M H                     | [b26c567912](https://linux-hardware.org/?probe=b26c567912) | Aug 03, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [9c841a04d6](https://linux-hardware.org/?probe=9c841a04d6) | Aug 01, 2021 |
| Gigabyte      | H61M-USB3-B3                | [3c2020fbb6](https://linux-hardware.org/?probe=3c2020fbb6) | Jul 30, 2021 |
| Gigabyte      | H61M-USB3-B3                | [b3bbc6d937](https://linux-hardware.org/?probe=b3bbc6d937) | Jul 30, 2021 |
| Dell          | 0V8WGR A00                  | [2cf38ffd15](https://linux-hardware.org/?probe=2cf38ffd15) | Jul 14, 2021 |
| ASUSTek       | P8H61-M LE                  | [b0270beb17](https://linux-hardware.org/?probe=b0270beb17) | Jul 11, 2021 |
| ASUSTek       | P8H61-M LE                  | [896e6feb8a](https://linux-hardware.org/?probe=896e6feb8a) | Jul 11, 2021 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [20bf622c31](https://linux-hardware.org/?probe=20bf622c31) | Jun 25, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [35605881d6](https://linux-hardware.org/?probe=35605881d6) | Jun 23, 2021 |
| MSI           | 2AE0                        | [bce75d51cd](https://linux-hardware.org/?probe=bce75d51cd) | Jun 23, 2021 |
| MSI           | 2AE0                        | [0412c710eb](https://linux-hardware.org/?probe=0412c710eb) | Jun 22, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [b9d86eb932](https://linux-hardware.org/?probe=b9d86eb932) | Jun 17, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [71de5617aa](https://linux-hardware.org/?probe=71de5617aa) | Jun 17, 2021 |
| ASUSTek       | PRIME X570-P                | [bca1e1b92f](https://linux-hardware.org/?probe=bca1e1b92f) | Jun 16, 2021 |
| ASUSTek       | PRIME X570-P                | [b3f6c76103](https://linux-hardware.org/?probe=b3f6c76103) | Jun 16, 2021 |
| Gigabyte      | B85-HD3                     | [c73931b3ff](https://linux-hardware.org/?probe=c73931b3ff) | Jun 13, 2021 |
| HP            | 843C                        | [ccff6e4f39](https://linux-hardware.org/?probe=ccff6e4f39) | Jun 08, 2021 |
| ASRock        | 990FX Extreme6              | [fc3b27abac](https://linux-hardware.org/?probe=fc3b27abac) | Jun 03, 2021 |
| HP            | 8591                        | [6f71430d88](https://linux-hardware.org/?probe=6f71430d88) | Jun 01, 2021 |
| HP            | 8591                        | [fc12c57885](https://linux-hardware.org/?probe=fc12c57885) | Jun 01, 2021 |
| ASRock        | 990FX Extreme6              | [0a228b18c1](https://linux-hardware.org/?probe=0a228b18c1) | May 30, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [0144616bb9](https://linux-hardware.org/?probe=0144616bb9) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [9890da0efd](https://linux-hardware.org/?probe=9890da0efd) | May 27, 2021 |
| Gigabyte      | 945GCM-S2L                  | [61e1972b06](https://linux-hardware.org/?probe=61e1972b06) | May 27, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [887dbc1614](https://linux-hardware.org/?probe=887dbc1614) | May 24, 2021 |
| Biostar       | A320MH                      | [db3a18e1c3](https://linux-hardware.org/?probe=db3a18e1c3) | May 23, 2021 |
| Biostar       | A320MH                      | [ccb22fc057](https://linux-hardware.org/?probe=ccb22fc057) | May 23, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0c314899c1](https://linux-hardware.org/?probe=0c314899c1) | May 23, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c41eec9cd3](https://linux-hardware.org/?probe=c41eec9cd3) | May 21, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [ca773b28ee](https://linux-hardware.org/?probe=ca773b28ee) | May 19, 2021 |
| ASUSTek       | P8H61-I R2.0                | [c641f2aee4](https://linux-hardware.org/?probe=c641f2aee4) | May 16, 2021 |
| ASUSTek       | P8H61-I R2.0                | [500443b449](https://linux-hardware.org/?probe=500443b449) | May 16, 2021 |
| Lenovo        | Annapurna CRB NOK           | [7d4224df3f](https://linux-hardware.org/?probe=7d4224df3f) | May 13, 2021 |
| Lenovo        | Annapurna CRB NOK           | [adef2ac504](https://linux-hardware.org/?probe=adef2ac504) | May 13, 2021 |
| Dell          | 06D7TR A00                  | [1ccb5b0600](https://linux-hardware.org/?probe=1ccb5b0600) | May 01, 2021 |
| Pegatron      | Benicia                     | [df847c36d5](https://linux-hardware.org/?probe=df847c36d5) | Apr 25, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [7f46cdb7ab](https://linux-hardware.org/?probe=7f46cdb7ab) | Apr 24, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [b00e95f3db](https://linux-hardware.org/?probe=b00e95f3db) | Apr 22, 2021 |
| ASUSTek       | P5K                         | [0149b6c450](https://linux-hardware.org/?probe=0149b6c450) | Apr 22, 2021 |
| Dell          | 0PGKWF A02                  | [f963717b2c](https://linux-hardware.org/?probe=f963717b2c) | Apr 18, 2021 |
| Acer          | Aspire XC-605G              | [79d3d3a05e](https://linux-hardware.org/?probe=79d3d3a05e) | Mar 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.11.0-38-generic          | 61       | 13.74%  |
| 5.11.0-27-generic          | 56       | 12.61%  |
| 5.11.0-40-generic          | 48       | 10.81%  |
| 5.11.0-41-generic          | 39       | 8.78%   |
| 5.11.0-43-generic          | 36       | 8.11%   |
| 5.11.0-37-generic          | 35       | 7.88%   |
| 5.11.0-34-generic          | 31       | 6.98%   |
| 5.13.0-28-generic          | 30       | 6.76%   |
| 5.13.0-27-generic          | 25       | 5.63%   |
| 5.13.0-30-generic          | 16       | 3.6%    |
| 5.11.0-44-generic          | 14       | 3.15%   |
| 5.11.0-36-generic          | 12       | 2.7%    |
| 5.8.0-53-generic           | 7        | 1.58%   |
| 5.11.0-46-generic          | 6        | 1.35%   |
| 5.8.0-55-generic           | 5        | 1.13%   |
| 5.8.0-50-generic           | 5        | 1.13%   |
| 5.11.0-25-generic          | 4        | 0.9%    |
| 5.8.0-59-generic           | 3        | 0.68%   |
| 5.8.0-49-generic           | 3        | 0.68%   |
| 5.8.0-63-generic           | 2        | 0.45%   |
| 5.13.0-25-generic          | 2        | 0.45%   |
| 5.8.0-45-generic           | 1        | 0.23%   |
| 5.15.13-051513-generic     | 1        | 0.23%   |
| 5.15.0-10.2-liquorix-amd64 | 1        | 0.23%   |
| 5.14.0-1010-oem            | 1        | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11.0  | 329      | 77.23%  |
| 5.13.0  | 69       | 16.2%   |
| 5.8.0   | 25       | 5.87%   |
| 5.15.13 | 1        | 0.23%   |
| 5.15.0  | 1        | 0.23%   |
| 5.14.0  | 1        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.11    | 329      | 77.23%  |
| 5.13    | 69       | 16.2%   |
| 5.8     | 25       | 5.87%   |
| 5.15    | 2        | 0.47%   |
| 5.14    | 1        | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 416      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| GNOME    | 388      | 93.05%  |
| XFCE     | 24       | 5.76%   |
| Unknown  | 3        | 0.72%   |
| MATE     | 1        | 0.24%   |
| Cinnamon | 1        | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 415      | 99.76%  |
| Wayland | 1        | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 362      | 86.81%  |
| GDM3    | 27       | 6.47%   |
| GDM     | 27       | 6.47%   |
| TDM     | 1        | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 170      | 40.87%  |
| de_DE       | 48       | 11.54%  |
| en_GB       | 34       | 8.17%   |
| pt_BR       | 24       | 5.77%   |
| pl_PL       | 13       | 3.13%   |
| es_ES       | 11       | 2.64%   |
| en_CA       | 10       | 2.4%    |
| it_IT       | 9        | 2.16%   |
| en_IN       | 9        | 2.16%   |
| nl_NL       | 8        | 1.92%   |
| fr_FR       | 8        | 1.92%   |
| ru_RU       | 6        | 1.44%   |
| hu_HU       | 5        | 1.2%    |
| es_MX       | 5        | 1.2%    |
| es_AR       | 5        | 1.2%    |
| pt_PT       | 4        | 0.96%   |
| en_ZA       | 4        | 0.96%   |
| en_AU       | 4        | 0.96%   |
| tr_TR       | 3        | 0.72%   |
| cs_CZ       | 3        | 0.72%   |
| sv_SE       | 2        | 0.48%   |
| sl_SI       | 2        | 0.48%   |
| nl_BE       | 2        | 0.48%   |
| ja_JP       | 2        | 0.48%   |
| fr_CA       | 2        | 0.48%   |
| es_CL       | 2        | 0.48%   |
| en_NZ       | 2        | 0.48%   |
| el_GR       | 2        | 0.48%   |
| de_CH       | 2        | 0.48%   |
| zh_TW       | 1        | 0.24%   |
| zh_CN       | 1        | 0.24%   |
| sr_RS@latin | 1        | 0.24%   |
| sr_RS       | 1        | 0.24%   |
| sk_SK       | 1        | 0.24%   |
| ru_UA       | 1        | 0.24%   |
| nb_NO       | 1        | 0.24%   |
| he_IL       | 1        | 0.24%   |
| fr_CH       | 1        | 0.24%   |
| es_PE       | 1        | 0.24%   |
| es_PA       | 1        | 0.24%   |
| es_NI       | 1        | 0.24%   |
| es_GT       | 1        | 0.24%   |
| en_SG       | 1        | 0.24%   |
| C           | 1        | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 242      | 57.89%  |
| EFI  | 176      | 42.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 390      | 93.75%  |
| Zfs      | 8        | 1.92%   |
| Overlay  | 8        | 1.92%   |
| Btrfs    | 6        | 1.44%   |
| Xfs      | 1        | 0.24%   |
| Reiserfs | 1        | 0.24%   |
| Ext3     | 1        | 0.24%   |
| Ext2     | 1        | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 386      | 92.57%  |
| GPT     | 25       | 6%      |
| MBR     | 6        | 1.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 402      | 96.4%   |
| Yes       | 15       | 3.6%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 366      | 87.77%  |
| Yes       | 51       | 12.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 107      | 25.72%  |
| Gigabyte Technology         | 71       | 17.07%  |
| Dell                        | 46       | 11.06%  |
| MSI                         | 41       | 9.86%   |
| ASRock                      | 38       | 9.13%   |
| Hewlett-Packard             | 37       | 8.89%   |
| Lenovo                      | 20       | 4.81%   |
| Intel                       | 13       | 3.13%   |
| Foxconn                     | 6        | 1.44%   |
| Biostar                     | 6        | 1.44%   |
| Fujitsu                     | 5        | 1.2%    |
| Acer                        | 5        | 1.2%    |
| Pegatron                    | 3        | 0.72%   |
| Unknown                     | 3        | 0.72%   |
| ECS                         | 2        | 0.48%   |
| Wortmann AG                 | 1        | 0.24%   |
| Shuttle                     | 1        | 0.24%   |
| Sapphire Technology Limited | 1        | 0.24%   |
| Positivo                    | 1        | 0.24%   |
| NCR                         | 1        | 0.24%   |
| Medion                      | 1        | 0.24%   |
| LattePanda                  | 1        | 0.24%   |
| IBM                         | 1        | 0.24%   |
| EVGA                        | 1        | 0.24%   |
| eMachines                   | 1        | 0.24%   |
| BESSTAR Tech                | 1        | 0.24%   |
| Apple                       | 1        | 0.24%   |
| Alienware                   | 1        | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 11       | 2.64%   |
| Dell OptiPlex 990                        | 5        | 1.2%    |
| Dell OptiPlex 790                        | 5        | 1.2%    |
| Dell OptiPlex 7010                       | 5        | 1.2%    |
| MSI MS-7817                              | 4        | 0.96%   |
| Unknown                                  | 4        | 0.96%   |
| MSI MS-7C02                              | 3        | 0.72%   |
| Intel X79M-S                             | 3        | 0.72%   |
| Gigabyte A320M-S2H                       | 3        | 0.72%   |
| ASUS P8Z77-V LX                          | 3        | 0.72%   |
| ASUS M5A78L-M/USB3                       | 3        | 0.72%   |
| ASRock B450M Pro4                        | 3        | 0.72%   |
| MSI MS-7B89                              | 2        | 0.48%   |
| MSI MS-7693                              | 2        | 0.48%   |
| Intel DQ77MK-R01                         | 2        | 0.48%   |
| HP ProDesk 600 G1 SFF                    | 2        | 0.48%   |
| HP Compaq Pro 6300 SFF                   | 2        | 0.48%   |
| HP Compaq 6200 Pro SFF PC                | 2        | 0.48%   |
| Gigabyte X570 AORUS MASTER               | 2        | 0.48%   |
| Gigabyte X570 AORUS ELITE                | 2        | 0.48%   |
| Gigabyte G31M-ES2L                       | 2        | 0.48%   |
| Gigabyte B75M-D3H                        | 2        | 0.48%   |
| Gigabyte B560M AORUS ELITE               | 2        | 0.48%   |
| Gigabyte B450 AORUS M                    | 2        | 0.48%   |
| Gigabyte 970A-DS3P                       | 2        | 0.48%   |
| Dell XPS420                              | 2        | 0.48%   |
| Dell Precision T1600                     | 2        | 0.48%   |
| Dell OptiPlex 7040                       | 2        | 0.48%   |
| Dell OptiPlex 380                        | 2        | 0.48%   |
| Dell OptiPlex 3010                       | 2        | 0.48%   |
| Dell Inspiron 3847                       | 2        | 0.48%   |
| Biostar A320MH                           | 2        | 0.48%   |
| ASUS UNLOCK INSTALL                      | 2        | 0.48%   |
| ASUS TUF GAMING X570-PLUS                | 2        | 0.48%   |
| ASUS PRIME B450M-GAMING/BR               | 2        | 0.48%   |
| ASUS PRIME B360M-K                       | 2        | 0.48%   |
| ASUS P5G41T-M LX3                        | 2        | 0.48%   |
| ASUS M5A97 R2.0                          | 2        | 0.48%   |
| ASUS M5A97 LE R2.0                       | 2        | 0.48%   |
| ASUS A68HM-PLUS                          | 2        | 0.48%   |
| ASRock B450 Pro4                         | 2        | 0.48%   |
| Wortmann AG TERRA_PC                     | 1        | 0.24%   |
| Shuttle XH61V                            | 1        | 0.24%   |
| Sapphire Limited PURE PLATINUM 970A-PLUS | 1        | 0.24%   |
| Positivo POS-PIH81DI                     | 1        | 0.24%   |
| Pegatron NY537AA-ABA 300-1025            | 1        | 0.24%   |
| Pegatron NE502AV-ABA a6750t              | 1        | 0.24%   |
| Pegatron h8-1217c                        | 1        | 0.24%   |
| NCR xxxx-xxxx-xxxx                       | 1        | 0.24%   |
| MSI WE136AA-UUZ p6337ch                  | 1        | 0.24%   |
| MSI Pro 3515 Series                      | 1        | 0.24%   |
| MSI p6745nl                              | 1        | 0.24%   |
| MSI MS-7D19                              | 1        | 0.24%   |
| MSI MS-7D18                              | 1        | 0.24%   |
| MSI MS-7D17                              | 1        | 0.24%   |
| MSI MS-7D06                              | 1        | 0.24%   |
| MSI MS-7C94                              | 1        | 0.24%   |
| MSI MS-7C80                              | 1        | 0.24%   |
| MSI MS-7C79                              | 1        | 0.24%   |
| MSI MS-7C56                              | 1        | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 30       | 7.21%   |
| ASUS PRIME             | 16       | 3.85%   |
| Lenovo ThinkCentre     | 12       | 2.88%   |
| ASUS All               | 11       | 2.64%   |
| HP Compaq              | 9        | 2.16%   |
| ASUS ROG               | 9        | 2.16%   |
| ASUS TUF               | 6        | 1.44%   |
| HP EliteDesk           | 5        | 1.2%    |
| Gigabyte X570          | 5        | 1.2%    |
| Gigabyte B450          | 5        | 1.2%    |
| ASUS M5A97             | 5        | 1.2%    |
| ASUS M5A78L-M          | 5        | 1.2%    |
| ASRock B450M           | 5        | 1.2%    |
| Acer Aspire            | 5        | 1.2%    |
| MSI MS-7817            | 4        | 0.96%   |
| Fujitsu ESPRIMO        | 4        | 0.96%   |
| Dell Precision         | 4        | 0.96%   |
| Dell Inspiron          | 4        | 0.96%   |
| ASUS P8Z77-V           | 4        | 0.96%   |
| ASUS P8H61-M           | 4        | 0.96%   |
| Unknown                | 4        | 0.96%   |
| MSI MS-7C02            | 3        | 0.72%   |
| Lenovo IdeaCentre      | 3        | 0.72%   |
| Intel X79M-S           | 3        | 0.72%   |
| HP ProDesk             | 3        | 0.72%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.72%   |
| Gigabyte B450M         | 3        | 0.72%   |
| Gigabyte A320M-S2H     | 3        | 0.72%   |
| Dell XPS               | 3        | 0.72%   |
| ASUS P5G41T-M          | 3        | 0.72%   |
| ASRock B450            | 3        | 0.72%   |
| MSI MS-7B89            | 2        | 0.48%   |
| MSI MS-7693            | 2        | 0.48%   |
| Intel DQ77MK-R01       | 2        | 0.48%   |
| HP t620                | 2        | 0.48%   |
| HP 290                 | 2        | 0.48%   |
| Gigabyte G31M-ES2L     | 2        | 0.48%   |
| Gigabyte B75M-D3H      | 2        | 0.48%   |
| Gigabyte B560M         | 2        | 0.48%   |
| Gigabyte B550M         | 2        | 0.48%   |
| Gigabyte 970A-DS3P     | 2        | 0.48%   |
| Foxconn Pro            | 2        | 0.48%   |
| Dell XPS420            | 2        | 0.48%   |
| Dell Vostro            | 2        | 0.48%   |
| Biostar A320MH         | 2        | 0.48%   |
| ASUS UNLOCK            | 2        | 0.48%   |
| ASUS P5Q               | 2        | 0.48%   |
| ASUS P5KPL-AM          | 2        | 0.48%   |
| ASUS P5K               | 2        | 0.48%   |
| ASUS Maximus           | 2        | 0.48%   |
| ASUS M5A78L            | 2        | 0.48%   |
| ASUS A68HM-PLUS        | 2        | 0.48%   |
| Wortmann AG TERRA      | 1        | 0.24%   |
| Shuttle XH61V          | 1        | 0.24%   |
| Sapphire Limited PURE  | 1        | 0.24%   |
| Positivo POS-PIH81DI   | 1        | 0.24%   |
| Pegatron NY537AA-ABA   | 1        | 0.24%   |
| Pegatron NE502AV-ABA   | 1        | 0.24%   |
| Pegatron h8-1217c      | 1        | 0.24%   |
| NCR xxxx-xxxx-xxxx     | 1        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 47       | 11.3%   |
| 2013 | 46       | 11.06%  |
| 2018 | 44       | 10.58%  |
| 2011 | 40       | 9.62%   |
| 2014 | 38       | 9.13%   |
| 2019 | 30       | 7.21%   |
| 2020 | 24       | 5.77%   |
| 2009 | 21       | 5.05%   |
| 2010 | 20       | 4.81%   |
| 2017 | 19       | 4.57%   |
| 2016 | 19       | 4.57%   |
| 2008 | 19       | 4.57%   |
| 2021 | 18       | 4.33%   |
| 2015 | 13       | 3.13%   |
| 2007 | 12       | 2.88%   |
| 2006 | 3        | 0.72%   |
| 2005 | 2        | 0.48%   |
| 2022 | 1        | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 416      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 395      | 94.5%   |
| Enabled  | 23       | 5.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 416      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 111      | 26.3%   |
| 8.01-16.0   | 103      | 24.41%  |
| 4.01-8.0    | 63       | 14.93%  |
| 3.01-4.0    | 58       | 13.74%  |
| 32.01-64.0  | 55       | 13.03%  |
| 1.01-2.0    | 12       | 2.84%   |
| 64.01-256.0 | 10       | 2.37%   |
| 24.01-32.0  | 6        | 1.42%   |
| 2.01-3.0    | 4        | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 196      | 44.95%  |
| 2.01-3.0   | 132      | 30.28%  |
| 3.01-4.0   | 53       | 12.16%  |
| 4.01-8.0   | 44       | 10.09%  |
| 8.01-16.0  | 7        | 1.61%   |
| 0.51-1.0   | 3        | 0.69%   |
| 16.01-24.0 | 1        | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 169      | 39.76%  |
| 2      | 126      | 29.65%  |
| 3      | 59       | 13.88%  |
| 4      | 25       | 5.88%   |
| 5      | 20       | 4.71%   |
| 6      | 14       | 3.29%   |
| 8      | 4        | 0.94%   |
| 0      | 4        | 0.94%   |
| 7      | 3        | 0.71%   |
| 11     | 1        | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 216      | 51.67%  |
| No        | 202      | 48.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 412      | 99.04%  |
| No        | 4        | 0.96%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 213      | 51.08%  |
| Yes       | 204      | 48.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 295      | 70.07%  |
| Yes       | 126      | 29.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 118      | 28.37%  |
| Germany      | 49       | 11.78%  |
| UK           | 33       | 7.93%   |
| Brazil       | 25       | 6.01%   |
| Canada       | 14       | 3.37%   |
| Poland       | 13       | 3.13%   |
| Netherlands  | 12       | 2.88%   |
| Spain        | 11       | 2.64%   |
| Italy        | 11       | 2.64%   |
| India        | 9        | 2.16%   |
| Hungary      | 8        | 1.92%   |
| France       | 7        | 1.68%   |
| Argentina    | 6        | 1.44%   |
| Russia       | 5        | 1.2%    |
| Mexico       | 5        | 1.2%    |
| Australia    | 5        | 1.2%    |
| Turkey       | 4        | 0.96%   |
| Switzerland  | 4        | 0.96%   |
| Sweden       | 4        | 0.96%   |
| South Africa | 4        | 0.96%   |
| Portugal     | 4        | 0.96%   |
| Norway       | 4        | 0.96%   |
| Denmark      | 4        | 0.96%   |
| Ukraine      | 3        | 0.72%   |
| Romania      | 3        | 0.72%   |
| Malaysia     | 3        | 0.72%   |
| Japan        | 3        | 0.72%   |
| Czechia      | 3        | 0.72%   |
| Croatia      | 3        | 0.72%   |
| Chile        | 3        | 0.72%   |
| Belgium      | 3        | 0.72%   |
| Taiwan       | 2        | 0.48%   |
| Slovenia     | 2        | 0.48%   |
| Serbia       | 2        | 0.48%   |
| New Zealand  | 2        | 0.48%   |
| Greece       | 2        | 0.48%   |
| El Salvador  | 2        | 0.48%   |
| Egypt        | 2        | 0.48%   |
| China        | 2        | 0.48%   |
| Austria      | 2        | 0.48%   |
| Vietnam      | 1        | 0.24%   |
| Slovakia     | 1        | 0.24%   |
| Peru         | 1        | 0.24%   |
| Panama       | 1        | 0.24%   |
| Nicaragua    | 1        | 0.24%   |
| Mozambique   | 1        | 0.24%   |
| Lithuania    | 1        | 0.24%   |
| Jamaica      | 1        | 0.24%   |
| Israel       | 1        | 0.24%   |
| Indonesia    | 1        | 0.24%   |
| Guatemala    | 1        | 0.24%   |
| Cyprus       | 1        | 0.24%   |
| Belarus      | 1        | 0.24%   |
| Bangladesh   | 1        | 0.24%   |
| Algeria      | 1        | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 5        | 1.18%   |
| Munich            | 3        | 0.71%   |
| Mentor            | 3        | 0.71%   |
| Dayton            | 3        | 0.71%   |
| Dallas            | 3        | 0.71%   |
| Cape Town         | 3        | 0.71%   |
| Athens            | 3        | 0.71%   |
| Zagreb            | 2        | 0.47%   |
| Warsaw            | 2        | 0.47%   |
| Vienna            | 2        | 0.47%   |
| Victoria          | 2        | 0.47%   |
| Vadodara          | 2        | 0.47%   |
| Twickenham        | 2        | 0.47%   |
| Stoke-on-Trent    | 2        | 0.47%   |
| SÃ£o Paulo      | 2        | 0.47%   |
| Rio de Janeiro    | 2        | 0.47%   |
| Richmond          | 2        | 0.47%   |
| Queens            | 2        | 0.47%   |
| Portland          | 2        | 0.47%   |
| Neath             | 2        | 0.47%   |
| Mount Olive       | 2        | 0.47%   |
| Minneapolis       | 2        | 0.47%   |
| Milan             | 2        | 0.47%   |
| Melbourne         | 2        | 0.47%   |
| Lomas de Zamora   | 2        | 0.47%   |
| Livingston        | 2        | 0.47%   |
| Kyiv              | 2        | 0.47%   |
| Kuala Lumpur      | 2        | 0.47%   |
| Houston           | 2        | 0.47%   |
| Hamburg           | 2        | 0.47%   |
| Fortaleza         | 2        | 0.47%   |
| Drummondville     | 2        | 0.47%   |
| Contagem          | 2        | 0.47%   |
| Cairo             | 2        | 0.47%   |
| Budapest          | 2        | 0.47%   |
| Bryan             | 2        | 0.47%   |
| Bernau bei Berlin | 2        | 0.47%   |
| Ankara            | 2        | 0.47%   |
| Alexandria        | 2        | 0.47%   |
| Zurich            | 1        | 0.24%   |
| Zlate Moravce     | 1        | 0.24%   |
| Zephyrhills       | 1        | 0.24%   |
| Yekaterinburg     | 1        | 0.24%   |
| Xalapa            | 1        | 0.24%   |
| Wysoka Glogowska  | 1        | 0.24%   |
| Wylie             | 1        | 0.24%   |
| Wuppertal         | 1        | 0.24%   |
| Wroclaw           | 1        | 0.24%   |
| Worden            | 1        | 0.24%   |
| Winnipeg          | 1        | 0.24%   |
| Williamsburg      | 1        | 0.24%   |
| Wilkau-Hasslau    | 1        | 0.24%   |
| Wijnegem          | 1        | 0.24%   |
| Wigan             | 1        | 0.24%   |
| West Valley City  | 1        | 0.24%   |
| Wellington        | 1        | 0.24%   |
| Warrenton         | 1        | 0.24%   |
| Warner Robins     | 1        | 0.24%   |
| Wanstead          | 1        | 0.24%   |
| Waldbroel         | 1        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 157      | 242    | 20.63%  |
| WDC                       | 126      | 171    | 16.56%  |
| Samsung Electronics       | 103      | 159    | 13.53%  |
| Kingston                  | 52       | 63     | 6.83%   |
| SanDisk                   | 47       | 56     | 6.18%   |
| Hitachi                   | 42       | 51     | 5.52%   |
| Toshiba                   | 40       | 47     | 5.26%   |
| Crucial                   | 23       | 30     | 3.02%   |
| Phison                    | 13       | 15     | 1.71%   |
| A-DATA Technology         | 13       | 14     | 1.71%   |
| Silicon Motion            | 11       | 18     | 1.45%   |
| Unknown                   | 10       | 16     | 1.31%   |
| China                     | 9        | 9      | 1.18%   |
| HGST                      | 8        | 10     | 1.05%   |
| Hewlett-Packard           | 7        | 10     | 0.92%   |
| MAXTOR                    | 6        | 7      | 0.79%   |
| Intel                     | 6        | 7      | 0.79%   |
| SK Hynix                  | 5        | 7      | 0.66%   |
| Lexar                     | 5        | 5      | 0.66%   |
| JMicron                   | 5        | 6      | 0.66%   |
| Super Talent              | 4        | 5      | 0.53%   |
| PNY                       | 4        | 5      | 0.53%   |
| OCZ                       | 4        | 4      | 0.53%   |
| Gigabyte Technology       | 4        | 4      | 0.53%   |
| XPG                       | 3        | 3      | 0.39%   |
| SPCC                      | 3        | 4      | 0.39%   |
| Realtek Semiconductor     | 3        | 4      | 0.39%   |
| Micron Technology         | 3        | 3      | 0.39%   |
| KingSpec                  | 3        | 4      | 0.39%   |
| Corsair                   | 3        | 3      | 0.39%   |
| SABRENT                   | 2        | 2      | 0.26%   |
| Netac                     | 2        | 2      | 0.26%   |
| Micron/Crucial Technology | 2        | 2      | 0.26%   |
| KIOXIA-EXCERIA            | 2        | 3      | 0.26%   |
| KingFast                  | 2        | 2      | 0.26%   |
| Intenso                   | 2        | 2      | 0.26%   |
| GOODRAM                   | 2        | 2      | 0.26%   |
| Apple                     | 2        | 2      | 0.26%   |
| Apacer                    | 2        | 2      | 0.26%   |
| XrayDisk                  | 1        | 1      | 0.13%   |
| WD MediaMax               | 1        | 2      | 0.13%   |
| Verbatim                  | 1        | 1      | 0.13%   |
| Transcend                 | 1        | 1      | 0.13%   |
| Teclast                   | 1        | 1      | 0.13%   |
| Team                      | 1        | 2      | 0.13%   |
| SuperSSpeed               | 1        | 2      | 0.13%   |
| Smartbuy                  | 1        | 1      | 0.13%   |
| Patriot                   | 1        | 1      | 0.13%   |
| OWC                       | 1        | 1      | 0.13%   |
| ORTIAL                    | 1        | 1      | 0.13%   |
| OCZ-VERTEX                | 1        | 1      | 0.13%   |
| MyDigitalSSD              | 1        | 1      | 0.13%   |
| Mushkin                   | 1        | 1      | 0.13%   |
| LaCie                     | 1        | 1      | 0.13%   |
| INNOVATION IT             | 1        | 1      | 0.13%   |
| HS-SSD-C100               | 1        | 1      | 0.13%   |
| GALAX                     | 1        | 1      | 0.13%   |
| Dogfish                   | 1        | 2      | 0.13%   |
| Config                    | 1        | 1      | 0.13%   |
| Unknown                   | 1        | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB      | 18       | 2.01%   |
| Kingston SA400S37240G 240GB SSD      | 15       | 1.67%   |
| WDC WD10EZEX-08WN4A0 1TB             | 11       | 1.23%   |
| Samsung SSD 860 EVO 500GB            | 11       | 1.23%   |
| Seagate ST1000DM010-2EP102 1TB       | 10       | 1.12%   |
| Samsung NVMe SSD Drive 500GB         | 10       | 1.12%   |
| Samsung NVMe SSD Drive 1TB           | 9        | 1%      |
| Seagate ST3500418AS 500GB            | 8        | 0.89%   |
| Seagate ST3500413AS 500GB            | 8        | 0.89%   |
| Samsung SSD 850 EVO 250GB            | 8        | 0.89%   |
| Kingston SA400S37120G 120GB SSD      | 8        | 0.89%   |
| Toshiba HDWD110 1TB                  | 7        | 0.78%   |
| Seagate ST1000DM003-1CH162 1TB       | 7        | 0.78%   |
| Samsung SSD 840 EVO 250GB            | 7        | 0.78%   |
| Toshiba DT01ACA100 1TB               | 6        | 0.67%   |
| Toshiba DT01ACA050 500GB             | 6        | 0.67%   |
| Seagate ST3500312CS 500GB            | 6        | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB       | 6        | 0.67%   |
| Seagate ST2000DM001-1CH164 2TB       | 6        | 0.67%   |
| Kingston SV300S37A120G 120GB SSD     | 6        | 0.67%   |
| Crucial CT500MX500SSD1 500GB         | 6        | 0.67%   |
| Unknown SD/MMC/MS PRO 64GB           | 5        | 0.56%   |
| Seagate ST2000DM001-9YN164 2TB       | 5        | 0.56%   |
| Seagate ST1000DM003-1ER162 1TB       | 5        | 0.56%   |
| Seagate Expansion+ 2TB               | 5        | 0.56%   |
| SanDisk SSD PLUS 240GB               | 5        | 0.56%   |
| Sandisk NVMe SSD Drive 1TB           | 5        | 0.56%   |
| Samsung SSD 870 QVO 1TB              | 5        | 0.56%   |
| Samsung SSD 870 EVO 1TB              | 5        | 0.56%   |
| Samsung HD103UJ 1TB                  | 5        | 0.56%   |
| Samsung HD103SJ 1TB                  | 5        | 0.56%   |
| Phison NVMe SSD Drive 512GB          | 5        | 0.56%   |
| Phison NVMe SSD Drive 1TB            | 5        | 0.56%   |
| Kingston SA400S37480G 480GB SSD      | 5        | 0.56%   |
| Hitachi HUA723020ALA641 2TB          | 5        | 0.56%   |
| WDC WD1600AAJS-75M0A0 160GB          | 4        | 0.45%   |
| Silicon Motion NVMe SSD Drive 128GB  | 4        | 0.45%   |
| Seagate ST8000DM004-2CX188 8TB       | 4        | 0.45%   |
| Seagate ST4000DM000-1F2168 4TB       | 4        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4        | 0.45%   |
| Sandisk NVMe SSD Drive 500GB         | 4        | 0.45%   |
| Samsung SSD 860 EVO 250GB            | 4        | 0.45%   |
| Samsung SSD 850 EVO 500GB            | 4        | 0.45%   |
| Samsung SSD 840 EVO 120GB            | 4        | 0.45%   |
| Kingston SV300S37A240G 240GB SSD     | 4        | 0.45%   |
| Crucial CT480BX500SSD1 480GB         | 4        | 0.45%   |
| Crucial CT240BX500SSD1 240GB         | 4        | 0.45%   |
| WDC WDBNCE5000PNC 500GB SSD          | 3        | 0.33%   |
| WDC WD5000AAKS-00V1A0 500GB          | 3        | 0.33%   |
| WDC WD10EZEX-60WN4A0 1TB             | 3        | 0.33%   |
| WDC WD10EZEX-60M2NA0 1TB             | 3        | 0.33%   |
| WDC WD10EZEX-08M2NA0 1TB             | 3        | 0.33%   |
| WDC WD10EARS-00Y5B1 1TB              | 3        | 0.33%   |
| Toshiba DT01ACA200 2TB               | 3        | 0.33%   |
| Super Talent FTM51N325H 512GB        | 3        | 0.33%   |
| Silicon Motion NVMe SSD Drive 512GB  | 3        | 0.33%   |
| Silicon Motion NVMe SSD Drive 1024GB | 3        | 0.33%   |
| Seagate ST4000DM004-2CV104 4TB       | 3        | 0.33%   |
| Seagate ST3250318AS 250GB            | 3        | 0.33%   |
| Seagate ST1000DX002-2DV162 1TB       | 3        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 156      | 234    | 38.81%  |
| WDC                 | 122      | 159    | 30.35%  |
| Hitachi             | 42       | 51     | 10.45%  |
| Toshiba             | 37       | 44     | 9.2%    |
| Samsung Electronics | 19       | 27     | 4.73%   |
| HGST                | 8        | 10     | 1.99%   |
| MAXTOR              | 6        | 7      | 1.49%   |
| Unknown             | 5        | 7      | 1.24%   |
| Hewlett-Packard     | 3        | 5      | 0.75%   |
| SABRENT             | 2        | 2      | 0.5%    |
| Apple               | 2        | 2      | 0.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 66       | 90     | 24.09%  |
| Kingston            | 47       | 56     | 17.15%  |
| SanDisk             | 35       | 43     | 12.77%  |
| Crucial             | 23       | 30     | 8.39%   |
| A-DATA Technology   | 12       | 13     | 4.38%   |
| WDC                 | 10       | 12     | 3.65%   |
| China               | 9        | 9      | 3.28%   |
| Lexar               | 5        | 5      | 1.82%   |
| Super Talent        | 4        | 5      | 1.46%   |
| PNY                 | 4        | 5      | 1.46%   |
| OCZ                 | 4        | 4      | 1.46%   |
| Intel               | 4        | 4      | 1.46%   |
| Hewlett-Packard     | 4        | 5      | 1.46%   |
| Gigabyte Technology | 4        | 4      | 1.46%   |
| SPCC                | 3        | 4      | 1.09%   |
| Micron Technology   | 3        | 3      | 1.09%   |
| KingSpec            | 3        | 4      | 1.09%   |
| Toshiba             | 2        | 2      | 0.73%   |
| SK Hynix            | 2        | 2      | 0.73%   |
| Seagate             | 2        | 2      | 0.73%   |
| Netac               | 2        | 2      | 0.73%   |
| KIOXIA-EXCERIA      | 2        | 3      | 0.73%   |
| Intenso             | 2        | 2      | 0.73%   |
| GOODRAM             | 2        | 2      | 0.73%   |
| Corsair             | 2        | 2      | 0.73%   |
| Apacer              | 2        | 2      | 0.73%   |
| Verbatim            | 1        | 1      | 0.36%   |
| Transcend           | 1        | 1      | 0.36%   |
| Teclast             | 1        | 1      | 0.36%   |
| Team                | 1        | 2      | 0.36%   |
| SuperSSpeed         | 1        | 2      | 0.36%   |
| Smartbuy            | 1        | 1      | 0.36%   |
| PHISON              | 1        | 1      | 0.36%   |
| Patriot             | 1        | 1      | 0.36%   |
| OWC                 | 1        | 1      | 0.36%   |
| ORTIAL              | 1        | 1      | 0.36%   |
| OCZ-VERTEX          | 1        | 1      | 0.36%   |
| MyDigitalSSD        | 1        | 1      | 0.36%   |
| Mushkin             | 1        | 1      | 0.36%   |
| INNOVATION IT       | 1        | 1      | 0.36%   |
| GALAX               | 1        | 1      | 0.36%   |
| Dogfish             | 1        | 2      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 296      | 548    | 47.9%   |
| SSD     | 220      | 334    | 35.6%   |
| NVMe    | 83       | 118    | 13.43%  |
| Unknown | 18       | 24     | 2.91%   |
| MMC     | 1        | 2      | 0.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 394      | 860    | 77.1%   |
| NVMe | 82       | 116    | 16.05%  |
| SAS  | 34       | 48     | 6.65%   |
| MMC  | 1        | 2      | 0.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 305      | 482    | 53.04%  |
| 0.51-1.0   | 161      | 242    | 28%     |
| 1.01-2.0   | 64       | 88     | 11.13%  |
| 3.01-4.0   | 21       | 32     | 3.65%   |
| 4.01-10.0  | 13       | 21     | 2.26%   |
| 2.01-3.0   | 11       | 17     | 1.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 119      | 27.8%   |
| 251-500        | 91       | 21.26%  |
| 501-1000       | 70       | 16.36%  |
| More than 3000 | 39       | 9.11%   |
| 1001-2000      | 38       | 8.88%   |
| 51-100         | 31       | 7.24%   |
| 2001-3000      | 15       | 3.5%    |
| 1-20           | 10       | 2.34%   |
| 21-50          | 9        | 2.1%    |
| Unknown        | 6        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 159      | 36.38%  |
| 21-50          | 98       | 22.43%  |
| 51-100         | 53       | 12.13%  |
| 101-250        | 37       | 8.47%   |
| 501-1000       | 22       | 5.03%   |
| More than 3000 | 21       | 4.81%   |
| 1001-2000      | 20       | 4.58%   |
| 251-500        | 18       | 4.12%   |
| Unknown        | 6        | 1.37%   |
| 2001-3000      | 3        | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD3200AAKS-22B3A0 320GB        | 1        | 1      | 8.33%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1        | 1      | 8.33%   |
| WDC WD10EZEX-21M2NA0 1TB           | 1        | 2      | 8.33%   |
| Toshiba MK3265GSX 320GB            | 1        | 1      | 8.33%   |
| Seagate ST9500420AS 500GB          | 1        | 1      | 8.33%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1      | 8.33%   |
| Seagate ST3500514NS 500GB          | 1        | 1      | 8.33%   |
| Seagate ST3320620AS 320GB          | 1        | 1      | 8.33%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 1        | 1      | 8.33%   |
| Seagate ST2000DM001-9YN164 2TB     | 1        | 1      | 8.33%   |
| Seagate ST2000DL003-9VT166 2TB     | 1        | 1      | 8.33%   |
| A-DATA Technology SX8200PNP 256GB  | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 6        | 7      | 54.55%  |
| WDC               | 3        | 4      | 27.27%  |
| Toshiba           | 1        | 1      | 9.09%   |
| A-DATA Technology | 1        | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 6        | 7      | 60%     |
| WDC     | 3        | 4      | 30%     |
| Toshiba | 1        | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 90%     |
| NVMe | 1        | 1      | 10%     |

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
| Detected | 386      | 947    | 89.77%  |
| Works    | 34       | 66     | 7.91%   |
| Malfunc  | 10       | 13     | 2.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 278      | 50.92%  |
| AMD                          | 129      | 23.63%  |
| Samsung Electronics          | 29       | 5.31%   |
| ASMedia Technology           | 20       | 3.66%   |
| Phison Electronics           | 13       | 2.38%   |
| Sandisk                      | 12       | 2.2%    |
| Silicon Motion               | 11       | 2.01%   |
| Marvell Technology Group     | 9        | 1.65%   |
| JMicron Technology           | 8        | 1.47%   |
| Nvidia                       | 7        | 1.28%   |
| Kingston Technology Company  | 7        | 1.28%   |
| VIA Technologies             | 4        | 0.73%   |
| SK Hynix                     | 3        | 0.55%   |
| Silicon Image                | 3        | 0.55%   |
| Realtek Semiconductor        | 3        | 0.55%   |
| ADATA Technology             | 3        | 0.55%   |
| Seagate Technology           | 2        | 0.37%   |
| Micron/Crucial Technology    | 2        | 0.37%   |
| Broadcom / LSI               | 2        | 0.37%   |
| Toshiba America Info Systems | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 68       | 9.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43       | 6.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 33       | 4.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32       | 4.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 29       | 4.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25       | 3.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 24       | 3.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 22       | 3.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 2.98%   |
| Intel SATA Controller [RAID mode]                                                       | 19       | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 2.7%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 18       | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17       | 2.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17       | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15       | 2.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 14       | 1.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14       | 1.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 1.7%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9        | 1.28%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 9        | 1.28%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 7        | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 0.99%   |
| Phison E12 NVMe Controller                                                              | 7        | 0.99%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 7        | 0.99%   |
| AMD FCH SATA Controller D                                                               | 7        | 0.99%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5        | 0.71%   |
| AMD FCH IDE Controller                                                                  | 5        | 0.71%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4        | 0.57%   |
| Nvidia MCP61 SATA Controller                                                            | 4        | 0.57%   |
| Nvidia MCP61 IDE                                                                        | 4        | 0.57%   |
| JMicron JMB368 IDE controller                                                           | 4        | 0.57%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 0.57%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 4        | 0.57%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.57%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 4        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 4        | 0.57%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 4        | 0.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.57%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.57%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3        | 0.43%   |
| Silicon Motion Non-Volatile memory controller                                           | 3        | 0.43%   |
| Sandisk Non-Volatile memory controller                                                  | 3        | 0.43%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.43%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.43%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.43%   |
| Marvell Group 88SE9120 SATA 6Gb/s Controller                                            | 3        | 0.43%   |
| Kingston Company A2000 NVMe SSD                                                         | 3        | 0.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3        | 0.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3        | 0.43%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 3        | 0.43%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3        | 0.43%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3        | 0.43%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.43%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 3        | 0.43%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller                        | 2        | 0.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2        | 0.28%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 326      | 58.42%  |
| IDE  | 115      | 20.61%  |
| NVMe | 82       | 14.7%   |
| RAID | 32       | 5.73%   |
| SCSI | 2        | 0.36%   |
| SAS  | 1        | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 281      | 67.55%  |
| AMD    | 135      | 32.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 2.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 11       | 2.64%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 1.92%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8        | 1.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 1.68%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 7        | 1.68%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 1.44%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 5        | 1.2%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 1.2%    |
| Intel Core i3-8100 CPU @ 3.60GHz            | 5        | 1.2%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 5        | 1.2%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 5        | 1.2%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 5        | 1.2%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 0.96%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 4        | 0.96%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.96%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.96%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 4        | 0.96%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 4        | 0.96%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 4        | 0.96%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.96%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.96%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4        | 0.96%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.96%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4        | 0.96%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 3        | 0.72%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 3        | 0.72%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 3        | 0.72%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.72%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3        | 0.72%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.72%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3        | 0.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3        | 0.72%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.72%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 3        | 0.72%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 3        | 0.72%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 3        | 0.72%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 3        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3        | 0.72%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 0.72%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.72%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3        | 0.72%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.72%   |
| AMD Phenom II X4 965 Processor              | 3        | 0.72%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.72%   |
| AMD FX-6300 Six-Core Processor              | 3        | 0.72%   |
| AMD FX-6100 Six-Core Processor              | 3        | 0.72%   |
| AMD FX-4100 Quad-Core Processor             | 3        | 0.72%   |
| Intel Xeon CPU X5650 @ 2.67GHz              | 2        | 0.48%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 2        | 0.48%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 2        | 0.48%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 0.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.48%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2        | 0.48%   |
| Intel Core i7 CPU 870 @ 2.93GHz             | 2        | 0.48%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2        | 0.48%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 2        | 0.48%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 2        | 0.48%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 2        | 0.48%   |
| Intel Core i5-4570S CPU @ 2.90GHz           | 2        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 87       | 20.91%  |
| Intel Core i7           | 46       | 11.06%  |
| Intel Core i3           | 44       | 10.58%  |
| AMD Ryzen 5             | 31       | 7.45%   |
| AMD FX                  | 23       | 5.53%   |
| Intel Xeon              | 18       | 4.33%   |
| AMD Ryzen 7             | 17       | 4.09%   |
| Intel Core 2 Quad       | 14       | 3.37%   |
| Intel Celeron           | 14       | 3.37%   |
| Intel Core 2 Duo        | 13       | 3.13%   |
| Other                   | 10       | 2.4%    |
| AMD Ryzen 3             | 10       | 2.4%    |
| Intel Pentium Dual-Core | 9        | 2.16%   |
| Intel Pentium           | 8        | 1.92%   |
| Intel Pentium Dual      | 7        | 1.68%   |
| AMD Ryzen 9             | 6        | 1.44%   |
| AMD Athlon II X2        | 6        | 1.44%   |
| AMD Phenom II X4        | 5        | 1.2%    |
| AMD A6                  | 5        | 1.2%    |
| AMD A8                  | 4        | 0.96%   |
| AMD A10                 | 4        | 0.96%   |
| Intel Pentium 4         | 3        | 0.72%   |
| AMD Athlon II X4        | 3        | 0.72%   |
| AMD Athlon II X3        | 3        | 0.72%   |
| Intel Pentium Gold      | 2        | 0.48%   |
| Intel Core i9           | 2        | 0.48%   |
| Intel Atom              | 2        | 0.48%   |
| AMD Phenom II X6        | 2        | 0.48%   |
| AMD GX                  | 2        | 0.48%   |
| AMD Athlon X4           | 2        | 0.48%   |
| AMD Athlon 64 X2        | 2        | 0.48%   |
| AMD Athlon 64           | 2        | 0.48%   |
| AMD Athlon              | 2        | 0.48%   |
| Intel Pentium D         | 1        | 0.24%   |
| Intel Core m3           | 1        | 0.24%   |
| Intel Core 2            | 1        | 0.24%   |
| AMD Ryzen 5 PRO         | 1        | 0.24%   |
| AMD Phenom              | 1        | 0.24%   |
| AMD Opteron             | 1        | 0.24%   |
| AMD E1                  | 1        | 0.24%   |
| AMD A4                  | 1        | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 185      | 44.47%  |
| 2      | 119      | 28.61%  |
| 6      | 54       | 12.98%  |
| 8      | 28       | 6.73%   |
| 3      | 10       | 2.4%    |
| 1      | 10       | 2.4%    |
| 12     | 5        | 1.2%    |
| 10     | 3        | 0.72%   |
| 16     | 2        | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 414      | 99.52%  |
| 2      | 2        | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 210      | 50.48%  |
| 1      | 206      | 49.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 416      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x306c3    | 52       | 12.38%  |
| 0x206a7    | 37       | 8.81%   |
| 0x306a9    | 36       | 8.57%   |
| 0x1067a    | 28       | 6.67%   |
| Unknown    | 26       | 6.19%   |
| 0x08701021 | 21       | 5%      |
| 0x506e3    | 19       | 4.52%   |
| 0x06000852 | 17       | 4.05%   |
| 0x0800820d | 10       | 2.38%   |
| 0x906ea    | 9        | 2.14%   |
| 0x906e9    | 9        | 2.14%   |
| 0x6fb      | 9        | 2.14%   |
| 0x06001119 | 8        | 1.9%    |
| 0xa0655    | 7        | 1.67%   |
| 0x6fd      | 7        | 1.67%   |
| 0x0600063e | 7        | 1.67%   |
| 0xa0671    | 6        | 1.43%   |
| 0x0a201016 | 6        | 1.43%   |
| 0x08701013 | 6        | 1.43%   |
| 0xa0653    | 5        | 1.19%   |
| 0x906eb    | 5        | 1.19%   |
| 0x010000c8 | 5        | 1.19%   |
| 0x08108109 | 4        | 0.95%   |
| 0x08101016 | 4        | 0.95%   |
| 0x0700010f | 4        | 0.95%   |
| 0x010000dc | 4        | 0.95%   |
| 0x010000db | 4        | 0.95%   |
| 0x406c4    | 3        | 0.71%   |
| 0x30678    | 3        | 0.71%   |
| 0x20652    | 3        | 0.71%   |
| 0x08001137 | 3        | 0.71%   |
| 0x010000c7 | 3        | 0.71%   |
| 0x906ed    | 2        | 0.48%   |
| 0x90672    | 2        | 0.48%   |
| 0x306e4    | 2        | 0.48%   |
| 0x206d7    | 2        | 0.48%   |
| 0x206c2    | 2        | 0.48%   |
| 0x106e5    | 2        | 0.48%   |
| 0x10676    | 2        | 0.48%   |
| 0x0a201009 | 2        | 0.48%   |
| 0x08001138 | 2        | 0.48%   |
| 0x06006705 | 2        | 0.48%   |
| 0x06003106 | 2        | 0.48%   |
| 0xf4a      | 1        | 0.24%   |
| 0xf49      | 1        | 0.24%   |
| 0xf47      | 1        | 0.24%   |
| 0xf43      | 1        | 0.24%   |
| 0x906ec    | 1        | 0.24%   |
| 0x806e9    | 1        | 0.24%   |
| 0x806c1    | 1        | 0.24%   |
| 0x706a1    | 1        | 0.24%   |
| 0x6f6      | 1        | 0.24%   |
| 0x50654    | 1        | 0.24%   |
| 0x406f1    | 1        | 0.24%   |
| 0x406c3    | 1        | 0.24%   |
| 0x40651    | 1        | 0.24%   |
| 0x306f2    | 1        | 0.24%   |
| 0x30661    | 1        | 0.24%   |
| 0x20655    | 1        | 0.24%   |
| 0x106a4    | 1        | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 58       | 13.94%  |
| SandyBridge      | 41       | 9.86%   |
| IvyBridge        | 38       | 9.13%   |
| Penryn           | 32       | 7.69%   |
| KabyLake         | 29       | 6.97%   |
| Zen 2            | 28       | 6.73%   |
| Piledriver       | 25       | 6.01%   |
| Skylake          | 20       | 4.81%   |
| K10              | 20       | 4.81%   |
| Core             | 18       | 4.33%   |
| Zen+             | 15       | 3.61%   |
| Zen              | 12       | 2.88%   |
| CometLake        | 12       | 2.88%   |
| Zen 3            | 10       | 2.4%    |
| Silvermont       | 7        | 1.68%   |
| Bulldozer        | 7        | 1.68%   |
| Westmere         | 6        | 1.44%   |
| Icelake          | 6        | 1.44%   |
| Jaguar           | 5        | 1.2%    |
| NetBurst         | 4        | 0.96%   |
| Nehalem          | 4        | 0.96%   |
| K8 Hammer        | 4        | 0.96%   |
| Excavator        | 4        | 0.96%   |
| Steamroller      | 2        | 0.48%   |
| Puma             | 2        | 0.48%   |
| TigerLake        | 1        | 0.24%   |
| K10 Llano        | 1        | 0.24%   |
| Goldmont plus    | 1        | 0.24%   |
| Broadwell        | 1        | 0.24%   |
| Bonnell          | 1        | 0.24%   |
| Alderlake Hybrid | 1        | 0.24%   |
| Unknown          | 1        | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 177      | 39.6%   |
| Intel            | 140      | 31.32%  |
| AMD              | 129      | 28.86%  |
| VIA Technologies | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28       | 6.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22       | 4.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16       | 3.55%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 15       | 3.33%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 2.44%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 9        | 2%      |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8        | 1.77%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 8        | 1.77%   |
| Intel HD Graphics 530                                                                    | 8        | 1.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8        | 1.77%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7        | 1.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 7        | 1.55%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 7        | 1.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6        | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6        | 1.33%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 6        | 1.33%   |
| Intel HD Graphics 630                                                                    | 6        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6        | 1.33%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 6        | 1.33%   |
| AMD RS780L [Radeon 3000]                                                                 | 6        | 1.33%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6        | 1.33%   |
| Nvidia GT218 [GeForce 210]                                                               | 5        | 1.11%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5        | 1.11%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5        | 1.11%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 1.11%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 5        | 1.11%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 4        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 0.89%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 3        | 0.67%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 3        | 0.67%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 3        | 0.67%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3        | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 3        | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                                       | 3        | 0.67%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 0.67%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3        | 0.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                                | 3        | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3        | 0.67%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 3        | 0.67%   |
| AMD RS880 [Radeon HD 4200]                                                               | 3        | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2        | 0.44%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 2        | 0.44%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 2        | 0.44%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.44%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 2        | 0.44%   |
| Nvidia GK104 [GeForce GTX 680]                                                           | 2        | 0.44%   |
| Nvidia GF119 [NVS 315]                                                                   | 2        | 0.44%   |
| Nvidia GF119 [GeForce GT 705]                                                            | 2        | 0.44%   |
| Nvidia GF116 [GeForce GT 545]                                                            | 2        | 0.44%   |
| Nvidia GA106 [GeForce RTX 3060]                                                          | 2        | 0.44%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 2        | 0.44%   |
| Nvidia G96C [GeForce GT 120]                                                             | 2        | 0.44%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 2        | 0.44%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 0.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 0.44%   |
| Intel AlderLake-S GT1                                                                    | 2        | 0.44%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 2        | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 166      | 39.71%  |
| 1 x Intel      | 118      | 28.23%  |
| 1 x AMD        | 115      | 27.51%  |
| Intel + AMD    | 6        | 1.44%   |
| Intel + Nvidia | 5        | 1.2%    |
| 2 x AMD        | 4        | 0.96%   |
| AMD + Nvidia   | 3        | 0.72%   |
| 1 x VIA        | 1        | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 276      | 66.35%  |
| Proprietary | 120      | 28.85%  |
| Unknown     | 20       | 4.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 161      | 38.42%  |
| 1.01-2.0   | 65       | 15.51%  |
| 0.51-1.0   | 60       | 14.32%  |
| 0.01-0.5   | 43       | 10.26%  |
| 3.01-4.0   | 33       | 7.88%   |
| 7.01-8.0   | 26       | 6.21%   |
| 5.01-6.0   | 16       | 3.82%   |
| 8.01-16.0  | 7        | 1.67%   |
| 2.01-3.0   | 6        | 1.43%   |
| 16.01-24.0 | 2        | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 63       | 15.11%  |
| Goldstar             | 40       | 9.59%   |
| Dell                 | 37       | 8.87%   |
| Hewlett-Packard      | 35       | 8.39%   |
| AOC                  | 29       | 6.95%   |
| Acer                 | 26       | 6.24%   |
| Philips              | 20       | 4.8%    |
| BenQ                 | 19       | 4.56%   |
| Ancor Communications | 16       | 3.84%   |
| LG Electronics       | 15       | 3.6%    |
| ViewSonic            | 8        | 1.92%   |
| Sceptre Tech         | 7        | 1.68%   |
| Iiyama               | 7        | 1.68%   |
| Unknown              | 7        | 1.68%   |
| Lenovo               | 6        | 1.44%   |
| HPN                  | 6        | 1.44%   |
| Unknown              | 5        | 1.2%    |
| Vizio                | 4        | 0.96%   |
| NEC Computers        | 4        | 0.96%   |
| Vestel               | 3        | 0.72%   |
| Sony                 | 3        | 0.72%   |
| Sharp                | 3        | 0.72%   |
| Panasonic            | 3        | 0.72%   |
| Microstep            | 3        | 0.72%   |
| Medion               | 3        | 0.72%   |
| Fujitsu Siemens      | 3        | 0.72%   |
| AUS                  | 3        | 0.72%   |
| ASUSTek Computer     | 3        | 0.72%   |
| Toshiba              | 2        | 0.48%   |
| OEM                  | 2        | 0.48%   |
| Lenovo Group Limited | 2        | 0.48%   |
| HannStar             | 2        | 0.48%   |
| FUS                  | 2        | 0.48%   |
| Xiaomi               | 1        | 0.24%   |
| Westinghouse         | 1        | 0.24%   |
| WAN                  | 1        | 0.24%   |
| Viotek               | 1        | 0.24%   |
| Vestel Elektronik    | 1        | 0.24%   |
| Unknown (AAA)        | 1        | 0.24%   |
| Seiki                | 1        | 0.24%   |
| Sceptre              | 1        | 0.24%   |
| Sanyo                | 1        | 0.24%   |
| PKB                  | 1        | 0.24%   |
| Packard Bell         | 1        | 0.24%   |
| ONN                  | 1        | 0.24%   |
| Mitsubishi           | 1        | 0.24%   |
| KTC                  | 1        | 0.24%   |
| IOD                  | 1        | 0.24%   |
| HCL                  | 1        | 0.24%   |
| HCG                  | 1        | 0.24%   |
| HannStar Display     | 1        | 0.24%   |
| Gigabyte Technology  | 1        | 0.24%   |
| GDH                  | 1        | 0.24%   |
| Gateway              | 1        | 0.24%   |
| Eizo                 | 1        | 0.24%   |
| CVT                  | 1        | 0.24%   |
| Belinea              | 1        | 0.24%   |
| BBY                  | 1        | 0.24%   |
| Arnos Instruments    | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 7        | 1.59%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 4        | 0.91%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                             | 3        | 0.68%   |
| Goldstar W1942 GSM4B6F 1440x900 410x260mm 19.1-inch                   | 3        | 0.68%   |
| Vizio VO37LFHDTV10A VIZ0043 1920x1080 820x460mm 37.0-inch             | 2        | 0.46%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 2        | 0.46%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch  | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 2        | 0.46%   |
| Samsung Electronics LCD Monitor SAM07BC 1360x768                      | 2        | 0.46%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.46%   |
| OEM 22_LCD_TV OEM3700 1920x540                                        | 2        | 0.46%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                       | 2        | 0.46%   |
| Hewlett-Packard W2072a HWP3000 1600x900 443x249mm 20.0-inch           | 2        | 0.46%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 2        | 0.46%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 0.46%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 2        | 0.46%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 2        | 0.46%   |
| Dell P190S DEL405B 1280x1024 376x301mm 19.0-inch                      | 2        | 0.46%   |
| Dell E2213 DELD04E 1680x1050 473x296mm 22.0-inch                      | 2        | 0.46%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 2        | 0.46%   |
| BenQ EW3270U BNQ7950 3840x2160 698x393mm 31.5-inch                    | 2        | 0.46%   |
| AOC 2260W AOC2260 1920x1080 477x268mm 21.5-inch                       | 2        | 0.46%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 2        | 0.46%   |
| Acer X223W ACR000D 1680x1050 474x296mm 22.0-inch                      | 2        | 0.46%   |
| Xiaomi Mi TV XMD00E2 1920x1080 708x398mm 32.0-inch                    | 1        | 0.23%   |
| Westinghouse SK-26H735S WDE6030 1366x768 576x324mm 26.0-inch          | 1        | 0.23%   |
| WAN 27MQ95FSHDRU WAN2700 2560x1440 600x330mm 27.0-inch                | 1        | 0.23%   |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1        | 0.23%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1        | 0.23%   |
| Viotek GNV27DB VTK2700 2560x1440 597x336mm 27.0-inch                  | 1        | 0.23%   |
| ViewSonic VX3258 series VSCA037 1920x1080 700x390mm 31.5-inch         | 1        | 0.23%   |
| ViewSonic VG510s VSCCA18 1024x768 304x228mm 15.0-inch                 | 1        | 0.23%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch         | 1        | 0.23%   |
| ViewSonic VA2252 SERIES VSC7731 1920x1080 476x268mm 21.5-inch         | 1        | 0.23%   |
| ViewSonic Q9-2 Series VSCC01D 1280x1024 380x300mm 19.1-inch           | 1        | 0.23%   |
| ViewSonic LCD Monitor VP3268-4K 1920x1080                             | 1        | 0.23%   |
| ViewSonic LCD Monitor VA2718-FHD 1920x1080                            | 1        | 0.23%   |
| ViewSonic LCD Monitor VA2256 Series 1920x1080                         | 1        | 0.23%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1100x620mm 49.7-inch | 1        | 0.23%   |
| Unknown LCD Monitor SAMSUNG 2464x900                                  | 1        | 0.23%   |
| Unknown LCD Monitor RTK                                               | 1        | 0.23%   |
| Unknown LCD Monitor OPD PX227H-HDMI1 4160x1440                        | 1        | 0.23%   |
| Unknown LCD Monitor LHC TE-3125 1920x1080                             | 1        | 0.23%   |
| Unknown LCD Monitor Kingston Technology 40'TV 1834x1031               | 1        | 0.23%   |
| Unknown LCD Monitor GKK MONITOR 1920x1080                             | 1        | 0.23%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1        | 0.23%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                      | 1        | 0.23%   |
| Toshiba LCD Monitor TV                                                | 1        | 0.23%   |
| Sony TV SNYEE01 1920x1080                                             | 1        | 0.23%   |
| Sony TV *00 SNYA405 3840x2160 952x535mm 43.0-inch                     | 1        | 0.23%   |
| Sony LCD Monitor TV 3840x1080                                         | 1        | 0.23%   |
| Sony AVAMP SNY9301 1280x720 708x398mm 32.0-inch                       | 1        | 0.23%   |
| Sharp LCD SHP3225 1360x768 640x360mm 28.9-inch                        | 1        | 0.23%   |
| Sharp LC-32LB261U SHP3243 1920x1080 698x392mm 31.5-inch               | 1        | 0.23%   |
| Sharp HDMI SHP0FE8 1920x1080 1152x648mm 52.0-inch                     | 1        | 0.23%   |
| Seiki SE19HT01 SEK0C76 1360x768 410x230mm 18.5-inch                   | 1        | 0.23%   |
| Sceptre Tech X505BV-FMQC SPT13C0 1920x1080                            | 1        | 0.23%   |
| Sceptre Tech X325BV-FMQR SPT0CB8 1920x1080 700x390mm 31.5-inch        | 1        | 0.23%   |
| Sceptre Tech Sceptre T24 SPT09AB 1920x1080 520x320mm 24.0-inch        | 1        | 0.23%   |
| Sceptre Tech Sceptre O35 SPT8928 3440x1440 819x346mm 35.0-inch        | 1        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 179      | 43.34%  |
| 3840x2160 (4K)     | 36       | 8.72%   |
| 1680x1050 (WSXGA+) | 27       | 6.54%   |
| Unknown            | 23       | 5.57%   |
| 1280x1024 (SXGA)   | 22       | 5.33%   |
| 1600x900 (HD+)     | 17       | 4.12%   |
| 1366x768 (WXGA)    | 17       | 4.12%   |
| 1440x900 (WXGA+)   | 15       | 3.63%   |
| 3840x1080          | 12       | 2.91%   |
| 2560x1440 (QHD)    | 11       | 2.66%   |
| 1360x768           | 10       | 2.42%   |
| 1920x1200 (WUXGA)  | 9        | 2.18%   |
| 3440x1440          | 8        | 1.94%   |
| 1920x540           | 3        | 0.73%   |
| 5760x2160          | 2        | 0.48%   |
| 3360x1080          | 2        | 0.48%   |
| 2560x1080          | 2        | 0.48%   |
| 1600x1200          | 2        | 0.48%   |
| 1024x768 (XGA)     | 2        | 0.48%   |
| 6400x1440          | 1        | 0.24%   |
| 4480x1440          | 1        | 0.24%   |
| 4160x1440          | 1        | 0.24%   |
| 3840x1600          | 1        | 0.24%   |
| 3780x2160          | 1        | 0.24%   |
| 3600x1080          | 1        | 0.24%   |
| 3360x1050          | 1        | 0.24%   |
| 3200x1200          | 1        | 0.24%   |
| 3120x1050          | 1        | 0.24%   |
| 2944x1080          | 1        | 0.24%   |
| 2560x1600          | 1        | 0.24%   |
| 2464x900           | 1        | 0.24%   |
| 1834x1031          | 1        | 0.24%   |
| 1280x720 (HD)      | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 96       | 23.65%  |
| 27      | 38       | 9.36%   |
| 24      | 38       | 9.36%   |
| 21      | 36       | 8.87%   |
| 23      | 35       | 8.62%   |
| 19      | 28       | 6.9%    |
| 22      | 21       | 5.17%   |
| 31      | 19       | 4.68%   |
| 18      | 18       | 4.43%   |
| 20      | 17       | 4.19%   |
| 17      | 10       | 2.46%   |
| 84      | 6        | 1.48%   |
| 34      | 6        | 1.48%   |
| 26      | 5        | 1.23%   |
| 54      | 4        | 0.99%   |
| 32      | 4        | 0.99%   |
| 40      | 3        | 0.74%   |
| 72      | 2        | 0.49%   |
| 48      | 2        | 0.49%   |
| 41      | 2        | 0.49%   |
| 35      | 2        | 0.49%   |
| 33      | 2        | 0.49%   |
| 28      | 2        | 0.49%   |
| 25      | 2        | 0.49%   |
| 15      | 2        | 0.49%   |
| 74      | 1        | 0.25%   |
| 52      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 42      | 1        | 0.25%   |
| 37      | 1        | 0.25%   |
| 36      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 105      | 26.65%  |
| 401-500     | 104      | 26.4%   |
| Unknown     | 96       | 24.37%  |
| 601-700     | 26       | 6.6%    |
| 351-400     | 14       | 3.55%   |
| 701-800     | 13       | 3.3%    |
| 301-350     | 10       | 2.54%   |
| 1501-2000   | 9        | 2.28%   |
| 1001-1500   | 7        | 1.78%   |
| 801-900     | 6        | 1.52%   |
| 901-1000    | 4        | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 204      | 53.26%  |
| Unknown | 92       | 24.02%  |
| 16/10   | 51       | 13.32%  |
| 5/4     | 19       | 4.96%   |
| 21/9    | 10       | 2.61%   |
| 4/3     | 4        | 1.04%   |
| 6/5     | 1        | 0.26%   |
| 32/9    | 1        | 0.26%   |
| 3/2     | 1        | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 106      | 26.37%  |
| Unknown        | 96       | 23.88%  |
| 151-200        | 58       | 14.43%  |
| 301-350        | 38       | 9.45%   |
| 351-500        | 34       | 8.46%   |
| 141-150        | 22       | 5.47%   |
| 251-300        | 20       | 4.98%   |
| More than 1000 | 15       | 3.73%   |
| 501-1000       | 10       | 2.49%   |
| 101-110        | 2        | 0.5%    |
| 121-130        | 1        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 200      | 52.49%  |
| Unknown | 96       | 25.2%   |
| 101-120 | 52       | 13.65%  |
| 1-50    | 15       | 3.94%   |
| 121-160 | 13       | 3.41%   |
| 161-240 | 5        | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 339      | 80.91%  |
| 2     | 56       | 13.37%  |
| 0     | 21       | 5.01%   |
| 3     | 3        | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 262      | 42.95%  |
| Intel                           | 157      | 25.74%  |
| Qualcomm Atheros                | 47       | 7.7%    |
| Ralink Technology               | 26       | 4.26%   |
| Broadcom                        | 19       | 3.11%   |
| TP-Link                         | 18       | 2.95%   |
| Ralink                          | 14       | 2.3%    |
| Nvidia                          | 6        | 0.98%   |
| MEDIATEK                        | 5        | 0.82%   |
| Samsung Electronics             | 4        | 0.66%   |
| Qualcomm Atheros Communications | 4        | 0.66%   |
| NetGear                         | 4        | 0.66%   |
| Microsoft                       | 4        | 0.66%   |
| Edimax Technology               | 4        | 0.66%   |
| Motorola PCS                    | 3        | 0.49%   |
| DisplayLink                     | 3        | 0.49%   |
| D-Link System                   | 3        | 0.49%   |
| ASIX Electronics                | 3        | 0.49%   |
| Xiaomi                          | 2        | 0.33%   |
| Marvell Technology Group        | 2        | 0.33%   |
| Huawei Technologies             | 2        | 0.33%   |
| D-Link                          | 2        | 0.33%   |
| Broadcom Limited                | 2        | 0.33%   |
| ZyDAS                           | 1        | 0.16%   |
| Research In Motion              | 1        | 0.16%   |
| Panasonic (Matsushita)          | 1        | 0.16%   |
| Padix (Rockfire)                | 1        | 0.16%   |
| OPPO Electronics                | 1        | 0.16%   |
| Linksys                         | 1        | 0.16%   |
| Lenovo                          | 1        | 0.16%   |
| Google                          | 1        | 0.16%   |
| Gemtek                          | 1        | 0.16%   |
| Exar                            | 1        | 0.16%   |
| Belkin Components               | 1        | 0.16%   |
| ASUSTek Computer                | 1        | 0.16%   |
| Arduino SA                      | 1        | 0.16%   |
| ADMtek                          | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 215      | 30.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28       | 4.02%   |
| Intel Wi-Fi 6 AX200                                               | 17       | 2.44%   |
| Intel I211 Gigabit Network Connection                             | 16       | 2.3%    |
| Intel Ethernet Connection I217-LM                                 | 16       | 2.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 14       | 2.01%   |
| Ralink MT7601U Wireless Adapter                                   | 13       | 1.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12       | 1.72%   |
| Realtek 802.11ac NIC                                              | 12       | 1.72%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 1.72%   |
| Intel Ethernet Controller I225-V                                  | 9        | 1.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 8        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 0.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 6        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5        | 0.72%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5        | 0.72%   |
| Intel Wireless-AC 9260                                            | 5        | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.72%   |
| Intel Ethernet Connection (2) I218-V                              | 5        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4        | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4        | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.57%   |
| Intel Wireless 7265                                               | 4        | 0.57%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 4        | 0.57%   |
| TP-Link TL WN823N RTL8192EU                                       | 3        | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 3        | 0.43%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.43%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3        | 0.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3        | 0.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3        | 0.43%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 3        | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.43%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.43%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.43%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.29%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2        | 0.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.29%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                   | 2        | 0.29%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2        | 0.29%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                         | 2        | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 57       | 24.57%  |
| Intel                           | 55       | 23.71%  |
| Ralink Technology               | 26       | 11.21%  |
| Qualcomm Atheros                | 23       | 9.91%   |
| TP-Link                         | 17       | 7.33%   |
| Ralink                          | 14       | 6.03%   |
| Broadcom                        | 7        | 3.02%   |
| Qualcomm Atheros Communications | 4        | 1.72%   |
| NetGear                         | 4        | 1.72%   |
| Microsoft                       | 4        | 1.72%   |
| MediaTek                        | 4        | 1.72%   |
| Edimax Technology               | 4        | 1.72%   |
| D-Link System                   | 2        | 0.86%   |
| D-Link                          | 2        | 0.86%   |
| Broadcom Limited                | 2        | 0.86%   |
| ZyDAS                           | 1        | 0.43%   |
| Panasonic (Matsushita)          | 1        | 0.43%   |
| Linksys                         | 1        | 0.43%   |
| Gemtek                          | 1        | 0.43%   |
| Belkin Components               | 1        | 0.43%   |
| ASUSTek Computer                | 1        | 0.43%   |
| ADMtek                          | 1        | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 17       | 7.23%   |
| Ralink MT7601U Wireless Adapter                                      | 13       | 5.53%   |
| Realtek 802.11ac NIC                                                 | 12       | 5.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 8        | 3.4%    |
| Ralink RT2870/RT3070 Wireless Adapter                                | 6        | 2.55%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 6        | 2.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 6        | 2.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 5        | 2.13%   |
| Ralink RT5370 Wireless Adapter                                       | 5        | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 5        | 2.13%   |
| Intel Wireless-AC 9260                                               | 5        | 2.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 4        | 1.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 4        | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4        | 1.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 4        | 1.7%    |
| Qualcomm Atheros AR9271 802.11n                                      | 4        | 1.7%    |
| Intel Wireless 7265                                                  | 4        | 1.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 4        | 1.7%    |
| TP-Link TL WN823N RTL8192EU                                          | 3        | 1.28%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 3        | 1.28%   |
| TP-Link 802.11ac NIC                                                 | 3        | 1.28%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 3        | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3        | 1.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3        | 1.28%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 3        | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3        | 1.28%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 3        | 1.28%   |
| TP-Link 802.11ac WLAN Adapter                                        | 2        | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 2        | 0.85%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                      | 2        | 0.85%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 2        | 0.85%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                            | 2        | 0.85%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                            | 2        | 0.85%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 2        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2        | 0.85%   |
| NetGear A6210                                                        | 2        | 0.85%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 2        | 0.85%   |
| MEDIATEK Network controller                                          | 2        | 0.85%   |
| Intel Wireless 8265 / 8275                                           | 2        | 0.85%   |
| Intel Wireless 8260                                                  | 2        | 0.85%   |
| Intel Wireless 7260                                                  | 2        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2        | 0.85%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 2        | 0.85%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 2        | 0.85%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT2870]             | 2        | 0.85%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070] | 2        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2        | 0.85%   |
| ZyDAS ZD1211B 802.11g                                                | 1        | 0.43%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1        | 0.43%   |
| TP-Link Archer T4U ver.3                                             | 1        | 0.43%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 1        | 0.43%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 1        | 0.43%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 1        | 0.43%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                               | 1        | 0.43%   |
| Realtek RTL8191SEvA Wireless LAN Controller                          | 1        | 0.43%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter              | 1        | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 1        | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 249      | 56.21%  |
| Intel                    | 128      | 28.89%  |
| Qualcomm Atheros         | 25       | 5.64%   |
| Broadcom                 | 12       | 2.71%   |
| Nvidia                   | 6        | 1.35%   |
| Samsung Electronics      | 4        | 0.9%    |
| DisplayLink              | 3        | 0.68%   |
| ASIX Electronics         | 3        | 0.68%   |
| Xiaomi                   | 2        | 0.45%   |
| Marvell Technology Group | 2        | 0.45%   |
| Huawei Technologies      | 2        | 0.45%   |
| TP-Link                  | 1        | 0.23%   |
| Research In Motion       | 1        | 0.23%   |
| OPPO Electronics         | 1        | 0.23%   |
| Motorola PCS             | 1        | 0.23%   |
| MediaTek                 | 1        | 0.23%   |
| Google                   | 1        | 0.23%   |
| D-Link System            | 1        | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 215      | 47.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28       | 6.14%   |
| Intel I211 Gigabit Network Connection                             | 16       | 3.51%   |
| Intel Ethernet Connection I217-LM                                 | 16       | 3.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14       | 3.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12       | 2.63%   |
| Intel Ethernet Connection (2) I219-V                              | 12       | 2.63%   |
| Intel Ethernet Controller I225-V                                  | 9        | 1.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6        | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 1.32%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.1%    |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.1%    |
| Intel 82579V Gigabit Network Connection                           | 5        | 1.1%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 4        | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.88%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 3        | 0.66%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 3        | 0.66%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.44%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2        | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2        | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 2        | 0.44%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2        | 0.44%   |
| ASIX AX88772                                                      | 2        | 0.44%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1        | 0.22%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.22%   |
| Research In Motion BlackBerry                                     | 1        | 0.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1        | 0.22%   |
| OPPO SM6115-QRD _SN:D6BC0450                                      | 1        | 0.22%   |
| Nvidia MCP73 Ethernet                                             | 1        | 0.22%   |
| Nvidia MCP51 Ethernet Controller                                  | 1        | 0.22%   |
| Motorola PCS motorola edge                                        | 1        | 0.22%   |
| MediaTek Wiko U316AT                                              | 1        | 0.22%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1        | 0.22%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.22%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.22%   |
| Intel Ethernet Connection (12) I219-V                             | 1        | 0.22%   |
| Intel 82578DM Gigabit Network Connection                          | 1        | 0.22%   |
| Intel 82578DC Gigabit Network Connection                          | 1        | 0.22%   |
| Intel 82566DM Gigabit Network Connection                          | 1        | 0.22%   |
| Intel 82562V-2 10/100 Network Connection                          | 1        | 0.22%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller     | 1        | 0.22%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1        | 0.22%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)            | 1        | 0.22%   |
| Huawei INE-LX2                                                    | 1        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 412      | 66.13%  |
| WiFi     | 205      | 32.91%  |
| Unknown  | 4        | 0.64%   |
| Modem    | 2        | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 402      | 69.19%  |
| WiFi     | 177      | 30.46%  |
| Unknown  | 2        | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 276      | 66.03%  |
| 2     | 123      | 29.43%  |
| 3     | 14       | 3.35%   |
| 0     | 4        | 0.96%   |
| 5     | 1        | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 290      | 69.05%  |
| Yes  | 130      | 30.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 43       | 33.08%  |
| Cambridge Silicon Radio         | 31       | 23.85%  |
| Realtek Semiconductor           | 20       | 15.38%  |
| Broadcom                        | 11       | 8.46%   |
| Qualcomm Atheros Communications | 6        | 4.62%   |
| ASUSTek Computer                | 5        | 3.85%   |
| MediaTek                        | 2        | 1.54%   |
| Dynex                           | 2        | 1.54%   |
| Dell                            | 2        | 1.54%   |
| National Semiconductor          | 1        | 0.77%   |
| Micro Star International        | 1        | 0.77%   |
| Lite-On Technology              | 1        | 0.77%   |
| IMC Networks                    | 1        | 0.77%   |
| Foxconn / Hon Hai               | 1        | 0.77%   |
| D-Link System                   | 1        | 0.77%   |
| Belkin Components               | 1        | 0.77%   |
| Apple                           | 1        | 0.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 31       | 23.85%  |
| Realtek Bluetooth Radio                                  | 19       | 14.62%  |
| Intel Bluetooth Device                                   | 11       | 8.46%   |
| Intel AX200 Bluetooth                                    | 10       | 7.69%   |
| Intel Bluetooth wireless interface                       | 8        | 6.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 6        | 4.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 6        | 4.62%   |
| Intel Wireless-AC 3168 Bluetooth                         | 5        | 3.85%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 2        | 1.54%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2        | 1.54%   |
| MediaTek Wireless_Device                                 | 2        | 1.54%   |
| Intel AX201 Bluetooth                                    | 2        | 1.54%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 2        | 1.54%   |
| Dell BT Mini-Receiver                                    | 2        | 1.54%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 2        | 1.54%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 1.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 2        | 1.54%   |
| Realtek RTL8821A Bluetooth                               | 1        | 0.77%   |
| Qualcomm Atheros  Bluetooth Device                       | 1        | 0.77%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.77%   |
| National Bluetooth Dongle                                | 1        | 0.77%   |
| Micro Star International Bluetooth Device                | 1        | 0.77%   |
| Lite-On Bluetooth Device                                 | 1        | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.77%   |
| IMC Networks Bluetooth Radio                             | 1        | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                       | 1        | 0.77%   |
| D-Link System DBT-122 Bluetooth                          | 1        | 0.77%   |
| Broadcom HP Bluetooth Module                             | 1        | 0.77%   |
| Broadcom Bluetooth 2.0+EDR dongle                        | 1        | 0.77%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 1        | 0.77%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 1        | 0.77%   |
| ASUS Bluetooth Radio                                     | 1        | 0.77%   |
| Apple Bluetooth USB Host Controller                      | 1        | 0.77%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 271      | 38.99%  |
| AMD                                  | 178      | 25.61%  |
| Nvidia                               | 162      | 23.31%  |
| C-Media Electronics                  | 17       | 2.45%   |
| Creative Labs                        | 8        | 1.15%   |
| Logitech                             | 6        | 0.86%   |
| Razer USA                            | 4        | 0.58%   |
| Plantronics                          | 4        | 0.58%   |
| JMTek                                | 4        | 0.58%   |
| VIA Technologies                     | 3        | 0.43%   |
| Texas Instruments                    | 3        | 0.43%   |
| Kingston Technology                  | 3        | 0.43%   |
| GN Netcom                            | 3        | 0.43%   |
| ASUSTek Computer                     | 2        | 0.29%   |
| XMOS                                 | 1        | 0.14%   |
| Valve Software                       | 1        | 0.14%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.14%   |
| Tenx Technology                      | 1        | 0.14%   |
| Swissonic                            | 1        | 0.14%   |
| SteelSeries ApS                      | 1        | 0.14%   |
| Silicon Labs                         | 1        | 0.14%   |
| SAVITECH                             | 1        | 0.14%   |
| ROCCAT                               | 1        | 0.14%   |
| Realtek Semiconductor                | 1        | 0.14%   |
| Numark                               | 1        | 0.14%   |
| Microsoft                            | 1        | 0.14%   |
| Micronas                             | 1        | 0.14%   |
| Micro Star International             | 1        | 0.14%   |
| LucidSound                           | 1        | 0.14%   |
| Klipsch Audio                        | 1        | 0.14%   |
| Insignia (Best Buy)                  | 1        | 0.14%   |
| iCreate Technologies                 | 1        | 0.14%   |
| iConnectivity                        | 1        | 0.14%   |
| Google                               | 1        | 0.14%   |
| GEMBIRD                              | 1        | 0.14%   |
| Focusrite-Novation                   | 1        | 0.14%   |
| FIFINE Microphones                   | 1        | 0.14%   |
| Creative Technology                  | 1        | 0.14%   |
| Corsair                              | 1        | 0.14%   |
| AudioQuest                           | 1        | 0.14%   |
| Asahi Kasei Microsystems             | 1        | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 52       | 6.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 45       | 5.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 41       | 5.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 35       | 4.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 32       | 4.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27       | 3.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 24       | 3.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24       | 3.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19       | 2.39%   |
| AMD FCH Azalia Controller                                                                         | 18       | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 16       | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 16       | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15       | 1.88%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13       | 1.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12       | 1.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 11       | 1.38%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 11       | 1.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10       | 1.26%   |
| Intel 200 Series PCH HD Audio                                                                     | 10       | 1.26%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 10       | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9        | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9        | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9        | 1.13%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9        | 1.13%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 9        | 1.13%   |
| Nvidia High Definition Audio Controller                                                           | 8        | 1.01%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 8        | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8        | 1.01%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 8        | 1.01%   |
| AMD Navi 10 HDMI Audio                                                                            | 8        | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 8        | 1.01%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8        | 1.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7        | 0.88%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 6        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6        | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5        | 0.63%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 5        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 5        | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5        | 0.63%   |
| Intel Audio device                                                                                | 5        | 0.63%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 5        | 0.63%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4        | 0.5%    |
| Nvidia MCP61 High Definition Audio                                                                | 4        | 0.5%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 4        | 0.5%    |
| JMTek USB PnP Audio Device                                                                        | 4        | 0.5%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 4        | 0.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 4        | 0.5%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4        | 0.5%    |
| AMD Trinity HDMI Audio Controller                                                                 | 4        | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4        | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4        | 0.5%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                                         | 4        | 0.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4        | 0.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3        | 0.38%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 3        | 0.38%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 0.38%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 3        | 0.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3        | 0.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3        | 0.38%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 3        | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 11       | 19.3%   |
| Kingston            | 7        | 12.28%  |
| G.Skill             | 7        | 12.28%  |
| Corsair             | 7        | 12.28%  |
| Samsung Electronics | 6        | 10.53%  |
| SK Hynix            | 5        | 8.77%   |
| Crucial             | 4        | 7.02%   |
| Micron Technology   | 3        | 5.26%   |
| Team                | 2        | 3.51%   |
| Ramaxel Technology  | 2        | 3.51%   |
| Goldkey             | 1        | 1.75%   |
| F7852C80            | 1        | 1.75%   |
| Unknown             | 1        | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 2        | 3.17%   |
| SK Hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s              | 2        | 3.17%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s            | 2        | 3.17%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3200MT/s                 | 2        | 3.17%   |
| Unknown RAM TM44D18UD04MU-NUK 4096MB DIMM DDR4 2400MT/s           | 1        | 1.59%   |
| Unknown RAM Module 8GB DIMM DDR4 2400MT/s                         | 1        | 1.59%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                              | 1        | 1.59%   |
| Unknown RAM Module 8192MB DIMM DDR4 2400MT/s                      | 1        | 1.59%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                      | 1        | 1.59%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                              | 1        | 1.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                              | 1        | 1.59%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                      | 1        | 1.59%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s                       | 1        | 1.59%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                            | 1        | 1.59%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                      | 1        | 1.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 1333MT/s                      | 1        | 1.59%   |
| Unknown RAM 04S2400CL17A 4096MB DIMM DDR4 2400MT/s                | 1        | 1.59%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s             | 1        | 1.59%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                | 1        | 1.59%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s              | 1        | 1.59%   |
| SK Hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s              | 1        | 1.59%   |
| SK Hynix RAM HMT325U6EFR8C-PB 2048MB DIMM DDR3 1600MT/s           | 1        | 1.59%   |
| SK Hynix RAM HKNNNFBMAVAR-NEH 2048MB Row Of Chips LPDDR4 3200MT/s | 1        | 1.59%   |
| Samsung RAM Module 8192MB DIMM DDR4 2133MT/s                      | 1        | 1.59%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s               | 1        | 1.59%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s               | 1        | 1.59%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s            | 1        | 1.59%   |
| Ramaxel RAM RMUA5110ME78HAF-2666 8GB DIMM DDR4 2667MT/s           | 1        | 1.59%   |
| Ramaxel RAM RMR5030ED58E8W1600 2048MB DIMM DDR3 1600MT/s          | 1        | 1.59%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s               | 1        | 1.59%   |
| Micron RAM 36KSF1G72PZ-1 8192MB DIMM DDR3 1600MT/s                | 1        | 1.59%   |
| Micron RAM 16KTF1G64AZ-1G6P1 8192MB DIMM DDR3 1600MT/s            | 1        | 1.59%   |
| Kingston RAM KHX2666C15D4/4G 4096MB DIMM DDR4 3200MT/s            | 1        | 1.59%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1867MT/s               | 1        | 1.59%   |
| Kingston RAM 99U5471-056.A00LF 8GB DIMM DDR3 1600MT/s             | 1        | 1.59%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s             | 1        | 1.59%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s        | 1        | 1.59%   |
| Kingston RAM 99U5403-065.A00LF 4GB DIMM DDR3 1600MT/s             | 1        | 1.59%   |
| Goldkey RAM BKH200UD25608-1333 2GB DIMM DDR3 1400MT/s             | 1        | 1.59%   |
| G.Skill RAM F4-3600C19-8GVRB 8GB DIMM DDR4 2933MT/s               | 1        | 1.59%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s            | 1        | 1.59%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 2933MT/s               | 1        | 1.59%   |
| G.Skill RAM F4-3200C16-16GTZR 16384MB DIMM DDR4 3333MT/s          | 1        | 1.59%   |
| G.Skill RAM F4-2666C15-8GVR 8192MB DIMM DDR4 2800MT/s             | 1        | 1.59%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s                | 1        | 1.59%   |
| G.Skill RAM F4-2400C15-8GIS 8GB DIMM DDR4 2400MT/s                | 1        | 1.59%   |
| F7852C80 RAM F641GU67F1600G0000 8GB DIMM DDR3 1333MT/s            | 1        | 1.59%   |
| Crucial RAM ST102464BA1339.16F 8GB DIMM DDR3 1333MT/s             | 1        | 1.59%   |
| Crucial RAM CT51264BA160BJ.C8F 4096MB DIMM DDR3 1600MT/s          | 1        | 1.59%   |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s          | 1        | 1.59%   |
| Crucial RAM BL8G32C16U4R.M8FE 8GB DIMM DDR4 2400MT/s              | 1        | 1.59%   |
| Corsair RAM CMW64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s            | 1        | 1.59%   |
| Corsair RAM CMK8GX4M1D3000C16 8GB DIMM DDR4 3200MT/s              | 1        | 1.59%   |
| Corsair RAM CMK32GX4M4D3600C18 8192MB DIMM DDR4 3600MT/s          | 1        | 1.59%   |
| Corsair RAM CMK16GX4M2Z2933C16 8192MB DIMM DDR4 3000MT/s          | 1        | 1.59%   |
| Corsair RAM CMH32GX4M2D3600C18 16384MB DIMM DDR4 3600MT/s         | 1        | 1.59%   |
| Corsair RAM CMD16GX4M2A2666C15 8GB DIMM DDR4 2667MT/s             | 1        | 1.59%   |
| Corsair RAM CMD16GX3M2A18 8192MB DIMM DDR3 1333MT/s               | 1        | 1.59%   |
| Unknown                                                           | 1        | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 24       | 47.06%  |
| DDR4    | 19       | 37.25%  |
| Unknown | 5        | 9.8%    |
| LPDDR4  | 1        | 1.96%   |
| DDR2    | 1        | 1.96%   |
| DDR     | 1        | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 49       | 96.08%  |
| SODIMM       | 1        | 1.96%   |
| Row Of Chips | 1        | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 28       | 50.91%  |
| 4096  | 17       | 30.91%  |
| 2048  | 5        | 9.09%   |
| 16384 | 4        | 7.27%   |
| 32768 | 1        | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 14       | 25.45%  |
| 1333  | 10       | 18.18%  |
| 3200  | 5        | 9.09%   |
| 2133  | 4        | 7.27%   |
| 3600  | 3        | 5.45%   |
| 2667  | 3        | 5.45%   |
| 2400  | 3        | 5.45%   |
| 1800  | 3        | 5.45%   |
| 3466  | 1        | 1.82%   |
| 3333  | 1        | 1.82%   |
| 3000  | 1        | 1.82%   |
| 2933  | 1        | 1.82%   |
| 2800  | 1        | 1.82%   |
| 2666  | 1        | 1.82%   |
| 1867  | 1        | 1.82%   |
| 1866  | 1        | 1.82%   |
| 1400  | 1        | 1.82%   |
| 667   | 1        | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 5        | 33.33%  |
| Samsung Electronics | 4        | 26.67%  |
| Hewlett-Packard     | 3        | 20%     |
| Brother Industries  | 2        | 13.33%  |
| Seiko Epson         | 1        | 6.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Seiko Epson XP-202 203 206 Series | 1        | 6.67%   |
| Samsung SCX-483x 5x3x Series      | 1        | 6.67%   |
| Samsung SCX-4200 series           | 1        | 6.67%   |
| Samsung SCX-3400 Series           | 1        | 6.67%   |
| Samsung C460 Series               | 1        | 6.67%   |
| HP OfficeJet 4650 series          | 1        | 6.67%   |
| HP LaserJet Professional P1102w   | 1        | 6.67%   |
| HP DeskJet 2700 series            | 1        | 6.67%   |
| Canon TS3100 series               | 1        | 6.67%   |
| Canon TR4500 series               | 1        | 6.67%   |
| Canon PIXMA MG2500 Series         | 1        | 6.67%   |
| Canon LiDE 400                    | 1        | 6.67%   |
| Canon iP4200                      | 1        | 6.67%   |
| Brother MFC-9140CDN               | 1        | 6.67%   |
| Brother DCP-L2540DW               | 1        | 6.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 2        | 66.67%  |
| Hewlett-Packard | 1        | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP ScanJet 2400c        | 1        | 33.33%  |
| Canon CanoScan LiDE 100 | 1        | 33.33%  |
| Canon CanoScan 8800F    | 1        | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 19       | 29.69%  |
| Microdia                      | 7        | 10.94%  |
| Microsoft                     | 5        | 7.81%   |
| Samsung Electronics           | 4        | 6.25%   |
| Sunplus Innovation Technology | 3        | 4.69%   |
| Generalplus Technology        | 3        | 4.69%   |
| ARC International             | 3        | 4.69%   |
| Realtek Semiconductor         | 2        | 3.13%   |
| Razer USA                     | 2        | 3.13%   |
| Chicony Electronics           | 2        | 3.13%   |
| Xiongmai                      | 1        | 1.56%   |
| Teslong Camera                | 1        | 1.56%   |
| Sonix Technology              | 1        | 1.56%   |
| lihappe8                      | 1        | 1.56%   |
| Jieli Technology              | 1        | 1.56%   |
| INOGENI                       | 1        | 1.56%   |
| HD 2MP WEBCAM                 | 1        | 1.56%   |
| Guillemot                     | 1        | 1.56%   |
| Genesys Logic                 | 1        | 1.56%   |
| Creative Technology           | 1        | 1.56%   |
| AVerMedia Technologies        | 1        | 1.56%   |
| Arkmicro Technologies         | 1        | 1.56%   |
| Apple                         | 1        | 1.56%   |
| Alcor Micro                   | 1        | 1.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 5        | 7.69%   |
| Samsung Galaxy A5 (MTP)                 | 4        | 6.15%   |
| Logitech HD Pro Webcam C920             | 4        | 6.15%   |
| Microsoft LifeCam HD-3000               | 3        | 4.62%   |
| Generalplus GENERAL WEBCAM              | 3        | 4.62%   |
| ARC International Camera                | 3        | 4.62%   |
| Sunplus Full HD webcam                  | 2        | 3.08%   |
| Razer USA Gaming Webcam [Kiyo]          | 2        | 3.08%   |
| Microdia Webcam Vitade AF               | 2        | 3.08%   |
| Logitech C922 Pro Stream Webcam         | 2        | 3.08%   |
| Xiongmai web camera                     | 1        | 1.54%   |
| Teslong Camera Teslong Camera           | 1        | 1.54%   |
| Sunplus WebCamera                       | 1        | 1.54%   |
| Sonix USB 2.0 Camera                    | 1        | 1.54%   |
| Realtek NexiGo N960E FHD Webcam         | 1        | 1.54%   |
| Realtek HP High Definition 1MP Webcam   | 1        | 1.54%   |
| Microsoft MicrosoftÃ‚ LifeCam Cinema | 1        | 1.54%   |
| Microsoft LifeCam VX-2000               | 1        | 1.54%   |
| Microdia USB Live camera                | 1        | 1.54%   |
| Microdia PC Camera (SN9C110)            | 1        | 1.54%   |
| Microdia Integrated Camera              | 1        | 1.54%   |
| Microdia Camera                         | 1        | 1.54%   |
| Microdia AUKEY PC-W1                    | 1        | 1.54%   |
| Logitech Webcam Pro 9000                | 1        | 1.54%   |
| Logitech Webcam C260                    | 1        | 1.54%   |
| Logitech QuickCam Pro for Notebooks     | 1        | 1.54%   |
| Logitech QuickCam Pro 4000              | 1        | 1.54%   |
| Logitech Portable Webcam C905           | 1        | 1.54%   |
| Logitech HD Webcam C910                 | 1        | 1.54%   |
| Logitech HD Webcam C615                 | 1        | 1.54%   |
| Logitech HD Webcam C525                 | 1        | 1.54%   |
| Logitech HD Webcam B990                 | 1        | 1.54%   |
| lihappe8 USB 2.0 Camera                 | 1        | 1.54%   |
| Jieli USB PHY 2.0                       | 1        | 1.54%   |
| INOGENI 1C2F-INOGENI 4K2USB3            | 1        | 1.54%   |
| HD 2MP WEBCAM HD 2MP WEBCAM             | 1        | 1.54%   |
| Guillemot Hercules HD Sunset            | 1        | 1.54%   |
| Genesys Logic Camera                    | 1        | 1.54%   |
| Creative Live! Cam Chat HD [VF0700]     | 1        | 1.54%   |
| Chicony HP High Definition 1MP Webcam   | 1        | 1.54%   |
| Chicony CNF8050 Webcam                  | 1        | 1.54%   |
| AVerMedia Live Streamer CAM 313         | 1        | 1.54%   |
| Arkmicro USB2.0 PC CAMERA               | 1        | 1.54%   |
| Apple iPhone 5/5C/5S/6/SE               | 1        | 1.54%   |
| Alcor Micro USB 2.0 PC Camera           | 1        | 1.54%   |

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


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Reiner SCT Kartensysteme | 1        | 25%     |
| Realtek Semiconductor    | 1        | 25%     |
| Alcor Micro              | 1        | 25%     |
| Advanced Card Systems    | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack e-com/pinpad   | 1        | 25%     |
| Realtek Semiconductor Smart Card Reader Interface | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader               | 1        | 25%     |
| Advanced Card Systems ACR39U                      | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 350      | 83.53%  |
| 1     | 61       | 14.56%  |
| 2     | 8        | 1.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 33       | 45.83%  |
| Graphics card            | 28       | 38.89%  |
| Chipcard                 | 3        | 4.17%   |
| Unassigned class         | 2        | 2.78%   |
| Multimedia controller    | 2        | 2.78%   |
| Storage/ide              | 1        | 1.39%   |
| Sound                    | 1        | 1.39%   |
| Communication controller | 1        | 1.39%   |
| Camera                   | 1        | 1.39%   |

