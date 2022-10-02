Ubuntu MATE 22.04 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE_22.04/Notebook/README.md).

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

Total: 138

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5df0554ade](https://linux-hardware.org/?probe=5df0554ade) | Oct 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [9eba2a1ed4](https://linux-hardware.org/?probe=9eba2a1ed4) | Oct 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [91c0e46209](https://linux-hardware.org/?probe=91c0e46209) | Sep 28, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [09411a9eb9](https://linux-hardware.org/?probe=09411a9eb9) | Sep 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [25b9bc1637](https://linux-hardware.org/?probe=25b9bc1637) | Sep 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0cfbd1e652](https://linux-hardware.org/?probe=0cfbd1e652) | Sep 24, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c89ed0e55a](https://linux-hardware.org/?probe=c89ed0e55a) | Sep 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0a1fb0cc40](https://linux-hardware.org/?probe=0a1fb0cc40) | Sep 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [47d871031b](https://linux-hardware.org/?probe=47d871031b) | Sep 19, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27d1aacb6](https://linux-hardware.org/?probe=f27d1aacb6) | Sep 18, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f9a798b3b](https://linux-hardware.org/?probe=2f9a798b3b) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [43264d7e6e](https://linux-hardware.org/?probe=43264d7e6e) | Sep 15, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [9889cc50de](https://linux-hardware.org/?probe=9889cc50de) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [a72ef6cb0b](https://linux-hardware.org/?probe=a72ef6cb0b) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8c6f7ca8a0](https://linux-hardware.org/?probe=8c6f7ca8a0) | Sep 10, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4ac227c8fe](https://linux-hardware.org/?probe=4ac227c8fe) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [928ba60e7e](https://linux-hardware.org/?probe=928ba60e7e) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fd02bdd474](https://linux-hardware.org/?probe=fd02bdd474) | Sep 02, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [169efa4465](https://linux-hardware.org/?probe=169efa4465) | Aug 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [81d8e17fed](https://linux-hardware.org/?probe=81d8e17fed) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5103a6fa3d](https://linux-hardware.org/?probe=5103a6fa3d) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d9d556aea3](https://linux-hardware.org/?probe=d9d556aea3) | Aug 26, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [90476bcf5e](https://linux-hardware.org/?probe=90476bcf5e) | Aug 25, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| AZW           | GK55                        | Desktop     | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [84091d13ef](https://linux-hardware.org/?probe=84091d13ef) | Aug 11, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [40099f2516](https://linux-hardware.org/?probe=40099f2516) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b44bebcab6](https://linux-hardware.org/?probe=b44bebcab6) | Aug 01, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| MSI           | 2AE0                        | Desktop     | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | Desktop     | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Dell          | Latitude E4200              | Notebook    | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3e74ebae5a](https://linux-hardware.org/?probe=3e74ebae5a) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [5f1b339a57](https://linux-hardware.org/?probe=5f1b339a57) | Jul 07, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [4070d60511](https://linux-hardware.org/?probe=4070d60511) | Jul 05, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| MicroByte     | ezbook                      | Notebook    | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [72831de308](https://linux-hardware.org/?probe=72831de308) | Jun 21, 2022 |
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [30b6c5f641](https://linux-hardware.org/?probe=30b6c5f641) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [7941caaa08](https://linux-hardware.org/?probe=7941caaa08) | May 29, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Unknown       | HX90                        | Desktop     | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | Notebook    | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| TYAN Compu... | S7012                       | Server      | [018f293210](https://linux-hardware.org/?probe=018f293210) | Apr 28, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-47-generic     | 18        | 18.75%  |
| 5.15.0-46-generic     | 11        | 11.46%  |
| 5.15.0-40-generic     | 10        | 10.42%  |
| 5.15.0-27-generic     | 7         | 7.29%   |
| 5.15.0-25-generic     | 7         | 7.29%   |
| 5.15.0-48-generic     | 5         | 5.21%   |
| 5.15.0-41-generic     | 5         | 5.21%   |
| 5.15.0-43-generic     | 4         | 4.17%   |
| 5.15.0-37-generic     | 4         | 4.17%   |
| 5.15.0-30-generic     | 4         | 4.17%   |
| 5.15.0-39-generic     | 2         | 2.08%   |
| 5.15.0-35-generic     | 2         | 2.08%   |
| 5.18.0-odroid-arm64   | 1         | 1.04%   |
| 5.18.0-1-generic      | 1         | 1.04%   |
| 5.18.0-051800-generic | 1         | 1.04%   |
| 5.17.1-051701-generic | 1         | 1.04%   |
| 5.17.0-1003-oem       | 1         | 1.04%   |
| 5.15.0-48-lowlatency  | 1         | 1.04%   |
| 5.15.0-46-lowlatency  | 1         | 1.04%   |
| 5.15.0-33-generic     | 1         | 1.04%   |
| 5.15.0-23-generic     | 1         | 1.04%   |
| 5.15.0-22-generic     | 1         | 1.04%   |
| 5.15.0-18-generic     | 1         | 1.04%   |
| 5.15.0-11-generic     | 1         | 1.04%   |
| 5.15.0-1014-raspi     | 1         | 1.04%   |
| 5.15.0-1012-raspi     | 1         | 1.04%   |
| 5.15.0-1011-raspi     | 1         | 1.04%   |
| 5.13.0-52-generic     | 1         | 1.04%   |
| 5.13.0-19-generic     | 1         | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 81        | 92.05%  |
| 5.18.0  | 3         | 3.41%   |
| 5.13.0  | 2         | 2.27%   |
| 5.17.1  | 1         | 1.14%   |
| 5.17.0  | 1         | 1.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 81        | 92.05%  |
| 5.18    | 3         | 3.41%   |
| 5.17    | 2         | 2.27%   |
| 5.13    | 2         | 2.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 85        | 97.7%   |
| aarch64 | 2         | 2.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MATE | 85        | 97.7%   |
| KDE5 | 2         | 2.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 85        | 97.7%   |
| Wayland | 2         | 2.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 69        | 78.41%  |
| GDM3    | 9         | 10.23%  |
| Unknown | 9         | 10.23%  |
| SDDM    | 1         | 1.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 39        | 44.83%  |
| de_DE | 9         | 10.34%  |
| fr_FR | 8         | 9.2%    |
| it_IT | 7         | 8.05%   |
| pt_BR | 4         | 4.6%    |
| en_AU | 4         | 4.6%    |
| ru_RU | 3         | 3.45%   |
| en_GB | 3         | 3.45%   |
| en_CA | 3         | 3.45%   |
| de_CH | 2         | 2.3%    |
| zh_CN | 1         | 1.15%   |
| nl_NL | 1         | 1.15%   |
| es_PE | 1         | 1.15%   |
| es_ES | 1         | 1.15%   |
| es_AR | 1         | 1.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 46        | 50.55%  |
| BIOS | 45        | 49.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 79        | 89.77%  |
| Zfs     | 4         | 4.55%   |
| Overlay | 2         | 2.27%   |
| Btrfs   | 2         | 2.27%   |
| Jfs     | 1         | 1.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 49        | 55.06%  |
| Unknown | 32        | 35.96%  |
| MBR     | 8         | 8.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 83.91%  |
| Yes       | 14        | 16.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 56        | 63.64%  |
| Yes       | 32        | 36.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 13        | 14.94%  |
| ASUSTek Computer        | 13        | 14.94%  |
| Lenovo                  | 11        | 12.64%  |
| Dell                    | 11        | 12.64%  |
| MSI                     | 6         | 6.9%    |
| Intel                   | 4         | 4.6%    |
| Apple                   | 4         | 4.6%    |
| Gigabyte Technology     | 2         | 2.3%    |
| ASRock                  | 2         | 2.3%    |
| Acer                    | 2         | 2.3%    |
| Unknown                 | 2         | 2.3%    |
| TYAN Computer           | 1         | 1.15%   |
| TrekStor                | 1         | 1.15%   |
| Sony                    | 1         | 1.15%   |
| Raspberry Pi Foundation | 1         | 1.15%   |
| Notebook                | 1         | 1.15%   |
| MicroByte               | 1         | 1.15%   |
| Medion                  | 1         | 1.15%   |
| LincPlus                | 1         | 1.15%   |
| LG Electronics          | 1         | 1.15%   |
| IPASON                  | 1         | 1.15%   |
| HYPERPC                 | 1         | 1.15%   |
| HUAWEI                  | 1         | 1.15%   |
| HONOR                   | 1         | 1.15%   |
| Hardkernel              | 1         | 1.15%   |
| Google                  | 1         | 1.15%   |
| Compaq                  | 1         | 1.15%   |
| AZW                     | 1         | 1.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP Compaq Elite 8300 SFF             | 2         | 2.3%    |
| Unknown                              | 2         | 2.3%    |
| TYAN S7012                           | 1         | 1.15%   |
| TrekStor Surfbook A13B               | 1         | 1.15%   |
| Sony VPCEA36FG                       | 1         | 1.15%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 1         | 1.15%   |
| Notebook NJx0MU                      | 1         | 1.15%   |
| MSI p6-2330                          | 1         | 1.15%   |
| MSI MS-7C02                          | 1         | 1.15%   |
| MSI MS-7982                          | 1         | 1.15%   |
| MSI MS-7817                          | 1         | 1.15%   |
| MSI MS-7599                          | 1         | 1.15%   |
| MSI B02311                           | 1         | 1.15%   |
| MicroByte ezbook                     | 1         | 1.15%   |
| Medion MS-7797                       | 1         | 1.15%   |
| LincPlus LINNCPLUS P1                | 1         | 1.15%   |
| LG 17Z990-R.AAS8U1                   | 1         | 1.15%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 1.15%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 1.15%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 1.15%   |
| Lenovo ThinkCentre M83z 10C20003FR   | 1         | 1.15%   |
| Lenovo ThinkCentre M710q 10MQSC0N00  | 1         | 1.15%   |
| Lenovo ThinkCentre M710q 10MQS0FR01  | 1         | 1.15%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 1.15%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 1.15%   |
| Lenovo IdeaPadFlex 6-14IKB 81EM      | 1         | 1.15%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 1.15%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 1.15%   |
| IPASON MaxBook P1                    | 1         | 1.15%   |
| Intel NUC8i7HNK                      | 1         | 1.15%   |
| Intel NUC7i5BNK                      | 1         | 1.15%   |
| Intel Kabylake Platform              | 1         | 1.15%   |
| Intel H81U                           | 1         | 1.15%   |
| HYPERPC PLAY                         | 1         | 1.15%   |
| HUAWEI KLVD-WXX9                     | 1         | 1.15%   |
| HONOR BOHK-WAX9X                     | 1         | 1.15%   |
| HP ProDesk 600 G2 DM                 | 1         | 1.15%   |
| HP Pavilion 590-p0049 3LC38AA        | 1         | 1.15%   |
| HP Pavilion 15                       | 1         | 1.15%   |
| HP Notebook                          | 1         | 1.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Latitude      | 4         | 4.6%    |
| Lenovo ThinkCentre | 3         | 3.45%   |
| HP EliteBook       | 3         | 3.45%   |
| HP Compaq          | 3         | 3.45%   |
| ASUS PRIME         | 3         | 3.45%   |
| Lenovo ThinkPad    | 2         | 2.3%    |
| Lenovo ThinkBook   | 2         | 2.3%    |
| Lenovo IdeaPad     | 2         | 2.3%    |
| HP Pavilion        | 2         | 2.3%    |
| Dell XPS           | 2         | 2.3%    |
| Dell Precision     | 2         | 2.3%    |
| Dell OptiPlex      | 2         | 2.3%    |
| ASUS VivoBook      | 2         | 2.3%    |
| ASUS ROG           | 2         | 2.3%    |
| Acer Aspire        | 2         | 2.3%    |
| Unknown            | 2         | 2.3%    |
| TYAN S7012         | 1         | 1.15%   |
| TrekStor Surfbook  | 1         | 1.15%   |
| Sony VPCEA36FG     | 1         | 1.15%   |
| RPi Raspberry      | 1         | 1.15%   |
| Notebook NJx0MU    | 1         | 1.15%   |
| MSI p6-2330        | 1         | 1.15%   |
| MSI MS-7C02        | 1         | 1.15%   |
| MSI MS-7982        | 1         | 1.15%   |
| MSI MS-7817        | 1         | 1.15%   |
| MSI MS-7599        | 1         | 1.15%   |
| MSI B02311         | 1         | 1.15%   |
| MicroByte ezbook   | 1         | 1.15%   |
| Medion MS-7797     | 1         | 1.15%   |
| LincPlus LINNCPLUS | 1         | 1.15%   |
| LG 17Z990-R.AAS8U1 | 1         | 1.15%   |
| Lenovo V15         | 1         | 1.15%   |
| Lenovo IdeaPadFlex | 1         | 1.15%   |
| IPASON MaxBook     | 1         | 1.15%   |
| Intel NUC8i7HNK    | 1         | 1.15%   |
| Intel NUC7i5BNK    | 1         | 1.15%   |
| Intel Kabylake     | 1         | 1.15%   |
| Intel H81U         | 1         | 1.15%   |
| HYPERPC PLAY       | 1         | 1.15%   |
| HUAWEI KLVD-WXX9   | 1         | 1.15%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 16        | 18.39%  |
| 2020    | 9         | 10.34%  |
| 2018    | 8         | 9.2%    |
| 2010    | 7         | 8.05%   |
| 2019    | 6         | 6.9%    |
| 2013    | 6         | 6.9%    |
| 2012    | 6         | 6.9%    |
| 2009    | 6         | 6.9%    |
| 2015    | 4         | 4.6%    |
| 2022    | 3         | 3.45%   |
| 2017    | 3         | 3.45%   |
| 2011    | 3         | 3.45%   |
| 2016    | 2         | 2.3%    |
| 2014    | 2         | 2.3%    |
| 2006    | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |
| 2008    | 1         | 1.15%   |
| 2007    | 1         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 40        | 45.98%  |
| Desktop        | 37        | 42.53%  |
| Mini pc        | 3         | 3.45%   |
| System on chip | 2         | 2.3%    |
| Tablet         | 2         | 2.3%    |
| Convertible    | 1         | 1.15%   |
| All in one     | 1         | 1.15%   |
| Server         | 1         | 1.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 83        | 93.26%  |
| Enabled  | 6         | 6.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 86        | 98.85%  |
| Yes  | 1         | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 24.14%  |
| 3.01-4.0    | 17        | 19.54%  |
| 8.01-16.0   | 16        | 18.39%  |
| 16.01-24.0  | 15        | 17.24%  |
| 32.01-64.0  | 12        | 13.79%  |
| 64.01-256.0 | 4         | 4.6%    |
| 24.01-32.0  | 1         | 1.15%   |
| 1.01-2.0    | 1         | 1.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 27        | 30%     |
| 1.01-2.0  | 24        | 26.67%  |
| 4.01-8.0  | 16        | 17.78%  |
| 3.01-4.0  | 15        | 16.67%  |
| 8.01-16.0 | 4         | 4.44%   |
| 0.51-1.0  | 4         | 4.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 62.07%  |
| 2      | 13        | 14.94%  |
| 3      | 10        | 11.49%  |
| 4      | 5         | 5.75%   |
| 6      | 3         | 3.45%   |
| 5      | 2         | 2.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 57.47%  |
| Yes       | 37        | 42.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 81.61%  |
| No        | 16        | 18.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 82.76%  |
| No        | 15        | 17.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 55        | 63.22%  |
| No        | 32        | 36.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 16        | 18.39%  |
| Germany     | 12        | 13.79%  |
| Italy       | 10        | 11.49%  |
| France      | 7         | 8.05%   |
| Brazil      | 6         | 6.9%    |
| Canada      | 4         | 4.6%    |
| UK          | 3         | 3.45%   |
| Spain       | 3         | 3.45%   |
| Russia      | 3         | 3.45%   |
| Australia   | 3         | 3.45%   |
| Switzerland | 2         | 2.3%    |
| Ukraine     | 1         | 1.15%   |
| Turkey      | 1         | 1.15%   |
| Serbia      | 1         | 1.15%   |
| Romania     | 1         | 1.15%   |
| Portugal    | 1         | 1.15%   |
| Peru        | 1         | 1.15%   |
| Paraguay    | 1         | 1.15%   |
| Netherlands | 1         | 1.15%   |
| India       | 1         | 1.15%   |
| Georgia     | 1         | 1.15%   |
| Finland     | 1         | 1.15%   |
| Estonia     | 1         | 1.15%   |
| Croatia     | 1         | 1.15%   |
| Colombia    | 1         | 1.15%   |
| China       | 1         | 1.15%   |
| Belgium     | 1         | 1.15%   |
| Austria     | 1         | 1.15%   |
| Argentina   | 1         | 1.15%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Vancouver         | 2         | 2.25%   |
| Paris             | 2         | 2.25%   |
| Melbourne         | 2         | 2.25%   |
| Mannheim          | 2         | 2.25%   |
| Berlin            | 2         | 2.25%   |
| York              | 1         | 1.12%   |
| Xining            | 1         | 1.12%   |
| Viana do Castelo  | 1         | 1.12%   |
| Velyki Mosty      | 1         | 1.12%   |
| Valenciennes      | 1         | 1.12%   |
| Thane             | 1         | 1.12%   |
| Terrace           | 1         | 1.12%   |
| Talence           | 1         | 1.12%   |
| Stuttgart         | 1         | 1.12%   |
| Split             | 1         | 1.12%   |
| Southampton       | 1         | 1.12%   |
| Seville           | 1         | 1.12%   |
| Settimo Torinese  | 1         | 1.12%   |
| Selargius         | 1         | 1.12%   |
| Sauerlach         | 1         | 1.12%   |
| Sao Paulo         | 1         | 1.12%   |
| Rostov-on-Don     | 1         | 1.12%   |
| Porto Alegre      | 1         | 1.12%   |
| Pindamonhangaba   | 1         | 1.12%   |
| Pärnu            | 1         | 1.12%   |
| Palermo           | 1         | 1.12%   |
| Overpelt          | 1         | 1.12%   |
| Ortuella          | 1         | 1.12%   |
| Noventa Vicentina | 1         | 1.12%   |
| North Wilkesboro  | 1         | 1.12%   |
| Nievole           | 1         | 1.12%   |
| Newport News      | 1         | 1.12%   |
| Naaldwijk         | 1         | 1.12%   |
| Mountain Home     | 1         | 1.12%   |
| Mount Waverley    | 1         | 1.12%   |
| Moscow            | 1         | 1.12%   |
| Milan             | 1         | 1.12%   |
| Miami             | 1         | 1.12%   |
| Memphis           | 1         | 1.12%   |
| Medellín         | 1         | 1.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 36     | 17.56%  |
| WDC                 | 16        | 23     | 12.21%  |
| Seagate             | 14        | 17     | 10.69%  |
| Crucial             | 9         | 9      | 6.87%   |
| Unknown             | 8         | 11     | 6.11%   |
| Toshiba             | 8         | 9      | 6.11%   |
| SanDisk             | 6         | 11     | 4.58%   |
| Hitachi             | 5         | 5      | 3.82%   |
| Phison              | 4         | 4      | 3.05%   |
| Kingston            | 4         | 5      | 3.05%   |
| KingSpec            | 3         | 3      | 2.29%   |
| A-DATA Technology   | 3         | 3      | 2.29%   |
| SK hynix            | 2         | 2      | 1.53%   |
| China               | 2         | 2      | 1.53%   |
| SSSTC               | 1         | 1      | 0.76%   |
| SPCC                | 1         | 1      | 0.76%   |
| RZX                 | 1         | 1      | 0.76%   |
| NGFF                | 1         | 1      | 0.76%   |
| Netac               | 1         | 1      | 0.76%   |
| Micron Technology   | 1         | 1      | 0.76%   |
| Maxtor              | 1         | 1      | 0.76%   |
| LITEON              | 1         | 1      | 0.76%   |
| Lenovo              | 1         | 1      | 0.76%   |
| Kston               | 1         | 1      | 0.76%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.76%   |
| KIOXIA              | 1         | 1      | 0.76%   |
| Kimtigo             | 1         | 1      | 0.76%   |
| KESU                | 1         | 1      | 0.76%   |
| JMicron Technology  | 1         | 1      | 0.76%   |
| Intenso             | 1         | 1      | 0.76%   |
| Intel               | 1         | 1      | 0.76%   |
| Hjwdz               | 1         | 1      | 0.76%   |
| GOODRAM             | 1         | 1      | 0.76%   |
| Gigabyte Technology | 1         | 1      | 0.76%   |
| faspeed             | 1         | 1      | 0.76%   |
| DAS                 | 1         | 6      | 0.76%   |
| BAITITON            | 1         | 1      | 0.76%   |
| ASMT                | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Crucial CT1000BX500SSD1 1TB        | 4         | 2.68%   |
| Seagate ST2000DM001-1ER164 2TB     | 3         | 2.01%   |
| WDC WD40EZAZ-00SF3B0 4TB           | 2         | 1.34%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 1.34%   |
| Samsung SSD 980 PRO 1TB            | 2         | 1.34%   |
| Samsung SSD 870 QVO 1TB            | 2         | 1.34%   |
| Samsung NVMe SSD Drive 1TB         | 2         | 1.34%   |
| Kingston SA400S37480G 480GB SSD    | 2         | 1.34%   |
| Crucial CT240BX500SSD1 240GB       | 2         | 1.34%   |
| WDC WDS100T2B0C 1TB                | 1         | 0.67%   |
| WDC WDBNCE0010PNC 1TB SSD          | 1         | 0.67%   |
| WDC WD6400AAKS-00E4A0 640GB        | 1         | 0.67%   |
| WDC WD60 EFAX-68JH4N1 6TB          | 1         | 0.67%   |
| WDC WD5000AZLX-75K2TA0 500GB       | 1         | 0.67%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1         | 0.67%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 0.67%   |
| WDC WD40 PURZ-85TTDY0 4TB          | 1         | 0.67%   |
| WDC WD30EFRX-68N32N0 3TB           | 1         | 0.67%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 0.67%   |
| WDC WD3000HLFS-01G6U0 304GB        | 1         | 0.67%   |
| WDC WD2500AAKX-753CA1 250GB        | 1         | 0.67%   |
| WDC WD10EZRZ-00HTKB0 1TB           | 1         | 0.67%   |
| WDC WD10EZRX-00A8LB0 1TB           | 1         | 0.67%   |
| WDC WD10EZEX-75WN4A0 1TB           | 1         | 0.67%   |
| WDC WD10EZEX-60ZF5A0 1TB           | 1         | 0.67%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1         | 0.67%   |
| WDC WD10EZEX-00KUWA0 1TB           | 1         | 0.67%   |
| WDC WD1001FALS-40Y6A0 1TB          | 1         | 0.67%   |
| WDC WD10 01FALS-00J7B1 1TB         | 1         | 0.67%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB | 1         | 0.67%   |
| Unknown SLD64G  64GB               | 1         | 0.67%   |
| Unknown SD/MMC 16GB                | 1         | 0.67%   |
| Unknown SC32G  32GB                | 1         | 0.67%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 1         | 0.67%   |
| Unknown EFAQK  512GB               | 1         | 0.67%   |
| Unknown CBADS  32GB                | 1         | 0.67%   |
| Unknown BJTD4R  32GB               | 1         | 0.67%   |
| Unknown Biwin  64GB                | 1         | 0.67%   |
| Unknown 256GB PCS 2.5" S           | 1         | 0.67%   |
| Toshiba THNSNK256GVN8 256GB SSD    | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 20     | 32.56%  |
| Seagate             | 14        | 17     | 32.56%  |
| Toshiba             | 5         | 5      | 11.63%  |
| Hitachi             | 5         | 5      | 11.63%  |
| Samsung Electronics | 2         | 3      | 4.65%   |
| Maxtor              | 1         | 1      | 2.33%   |
| KESU                | 1         | 1      | 2.33%   |
| DAS                 | 1         | 6      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 15     | 22.45%  |
| Crucial             | 9         | 9      | 18.37%  |
| SanDisk             | 5         | 7      | 10.2%   |
| Kingston            | 3         | 3      | 6.12%   |
| KingSpec            | 3         | 3      | 6.12%   |
| China               | 2         | 2      | 4.08%   |
| A-DATA Technology   | 2         | 2      | 4.08%   |
| WDC                 | 1         | 1      | 2.04%   |
| Unknown             | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 2      | 2.04%   |
| SPCC                | 1         | 1      | 2.04%   |
| RZX                 | 1         | 1      | 2.04%   |
| NGFF                | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| LITEON              | 1         | 1      | 2.04%   |
| Kston               | 1         | 1      | 2.04%   |
| KIOXIA-EXCERIA      | 1         | 1      | 2.04%   |
| Intenso             | 1         | 1      | 2.04%   |
| GOODRAM             | 1         | 1      | 2.04%   |
| BAITITON            | 1         | 1      | 2.04%   |
| ASMT                | 1         | 1      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 40        | 56     | 35.4%   |
| NVMe    | 32        | 43     | 28.32%  |
| HDD     | 32        | 58     | 28.32%  |
| MMC     | 6         | 8      | 5.31%   |
| Unknown | 3         | 4      | 2.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 60        | 101    | 56.07%  |
| NVMe | 31        | 42     | 28.97%  |
| SAS  | 10        | 18     | 9.35%   |
| MMC  | 6         | 8      | 5.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 67     | 55.29%  |
| 0.51-1.0   | 22        | 28     | 25.88%  |
| 1.01-2.0   | 9         | 11     | 10.59%  |
| 3.01-4.0   | 4         | 4      | 4.71%   |
| 4.01-10.0  | 2         | 2      | 2.35%   |
| 2.01-3.0   | 1         | 2      | 1.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 26.14%  |
| 251-500        | 21        | 23.86%  |
| 501-1000       | 13        | 14.77%  |
| More than 3000 | 8         | 9.09%   |
| 1001-2000      | 7         | 7.95%   |
| 51-100         | 5         | 5.68%   |
| 21-50          | 4         | 4.55%   |
| 1-20           | 4         | 4.55%   |
| 2001-3000      | 2         | 2.27%   |
| Unknown        | 1         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 27.27%  |
| 21-50          | 14        | 15.91%  |
| 101-250        | 14        | 15.91%  |
| 51-100         | 10        | 11.36%  |
| 501-1000       | 9         | 10.23%  |
| More than 3000 | 5         | 5.68%   |
| 251-500        | 5         | 5.68%   |
| 1001-2000      | 5         | 5.68%   |
| 2001-3000      | 1         | 1.14%   |
| Unknown        | 1         | 1.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 22.22%  |
| WDC WD1001FALS-40Y6A0 1TB           | 1         | 1      | 11.11%  |
| Seagate ST2000DM001-1ER164 2TB      | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 960 PRO 1TB | 1         | 1      | 11.11%  |
| NGFF 2280 256GB SSD                 | 1         | 1      | 11.11%  |
| Hitachi HTS721080G9SA00 80GB        | 1         | 1      | 11.11%  |
| DAS TerraMaster 500GB               | 1         | 3      | 11.11%  |
| China SSD 180GB                     | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| WDC                 | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| NGFF                | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |
| DAS                 | 1         | 3      | 11.11%  |
| China               | 1         | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |
| DAS     | 1         | 3      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 8      | 62.5%   |
| SSD  | 2         | 2      | 25%     |
| NVMe | 1         | 1      | 12.5%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 50        | 78     | 51.02%  |
| Detected | 40        | 80     | 40.82%  |
| Malfunc  | 8         | 11     | 8.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 60        | 54.55%  |
| AMD                            | 15        | 13.64%  |
| Samsung Electronics            | 12        | 10.91%  |
| Phison Electronics             | 5         | 4.55%   |
| SanDisk                        | 3         | 2.73%   |
| SK hynix                       | 2         | 1.82%   |
| Silicon Motion                 | 2         | 1.82%   |
| KIOXIA                         | 2         | 1.82%   |
| Kingston Technology Company    | 2         | 1.82%   |
| ASMedia Technology             | 2         | 1.82%   |
| Toshiba America Info Systems   | 1         | 0.91%   |
| Solid State Storage Technology | 1         | 0.91%   |
| Nvidia                         | 1         | 0.91%   |
| Lenovo                         | 1         | 0.91%   |
| ADATA Technology               | 1         | 0.91%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 7.63%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 3.82%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 2.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 2.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 2.29%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 2.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.53%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.53%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.53%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.53%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.53%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 1.53%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 2         | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 2         | 1.53%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.76%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.76%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.76%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.76%   |
| Phison NVMe Storage Controller                                                 | 1         | 0.76%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.76%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 63        | 54.31%  |
| NVMe | 31        | 26.72%  |
| RAID | 11        | 9.48%   |
| IDE  | 11        | 9.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 68        | 78.16%  |
| AMD    | 17        | 19.54%  |
| ARM    | 2         | 2.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 3.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 2.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 2.3%    |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 2.3%    |
| ARM Processor                               | 2         | 2.3%    |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 2.3%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 2.3%    |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 1.15%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 1.15%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 1.15%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.15%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 1.15%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 1.15%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 1.15%   |
| Intel Core i7-8705G CPU @ 3.10GHz           | 1         | 1.15%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 1.15%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1         | 1.15%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 1.15%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.15%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.15%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.15%   |
| Intel Core i7-3517U CPU @ 1.90GHz           | 1         | 1.15%   |
| Intel Core i7 CPU X 920 @ 2.00GHz           | 1         | 1.15%   |
| Intel Core i5-7400T CPU @ 2.40GHz           | 1         | 1.15%   |
| Intel Core i5-7260U CPU @ 2.20GHz           | 1         | 1.15%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 1.15%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 1.15%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 1.15%   |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 1         | 1.15%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 1.15%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.15%   |
| Intel Core i5-3330S CPU @ 2.70GHz           | 1         | 1.15%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.15%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 1         | 1.15%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 1         | 1.15%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 1         | 1.15%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 1         | 1.15%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 1         | 1.15%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 17        | 19.54%  |
| Other                | 14        | 16.09%  |
| Intel Core i7        | 13        | 14.94%  |
| Intel Core i3        | 8         | 9.2%    |
| AMD Ryzen 5          | 6         | 6.9%    |
| Intel Core 2 Duo     | 5         | 5.75%   |
| Intel Celeron        | 5         | 5.75%   |
| Intel Pentium        | 4         | 4.6%    |
| Intel Xeon           | 2         | 2.3%    |
| AMD Ryzen 9          | 2         | 2.3%    |
| Intel Pentium 4      | 1         | 1.15%   |
| Intel Core 2 Quad    | 1         | 1.15%   |
| AMD Turion 64 Mobile | 1         | 1.15%   |
| AMD Ryzen 7 PRO      | 1         | 1.15%   |
| AMD Ryzen 7          | 1         | 1.15%   |
| AMD Phenom II X6     | 1         | 1.15%   |
| AMD E                | 1         | 1.15%   |
| AMD Athlon II X4     | 1         | 1.15%   |
| AMD A8               | 1         | 1.15%   |
| AMD A6               | 1         | 1.15%   |
| AMD A4               | 1         | 1.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 40        | 45.98%  |
| 2       | 28        | 32.18%  |
| 8       | 6         | 6.9%    |
| 6       | 6         | 6.9%    |
| 1       | 3         | 3.45%   |
| 12      | 2         | 2.3%    |
| 10      | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 85        | 97.7%   |
| 2       | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 54        | 62.07%  |
| 1       | 32        | 36.78%  |
| Unknown | 1         | 1.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 87        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 39.33%  |
| 0x806c1    | 6         | 6.74%   |
| 0x306a9    | 4         | 4.49%   |
| 0x806d1    | 3         | 3.37%   |
| 0x306c3    | 3         | 3.37%   |
| 0x20655    | 3         | 3.37%   |
| 0x906e9    | 2         | 2.25%   |
| 0x806ea    | 2         | 2.25%   |
| 0x706e5    | 2         | 2.25%   |
| 0x706a8    | 2         | 2.25%   |
| 0x506c9    | 2         | 2.25%   |
| 0x1067a    | 2         | 2.25%   |
| 0x0a50000c | 2         | 2.25%   |
| 0xa0671    | 1         | 1.12%   |
| 0xa0653    | 1         | 1.12%   |
| 0x906ed    | 1         | 1.12%   |
| 0x90672    | 1         | 1.12%   |
| 0x806ec    | 1         | 1.12%   |
| 0x806eb    | 1         | 1.12%   |
| 0x806e9    | 1         | 1.12%   |
| 0x6fd      | 1         | 1.12%   |
| 0x506e3    | 1         | 1.12%   |
| 0x40651    | 1         | 1.12%   |
| 0x306f2    | 1         | 1.12%   |
| 0x206c2    | 1         | 1.12%   |
| 0x206a7    | 1         | 1.12%   |
| 0x106e5    | 1         | 1.12%   |
| 0x10677    | 1         | 1.12%   |
| 0x08108109 | 1         | 1.12%   |
| 0x08101016 | 1         | 1.12%   |
| 0x07030105 | 1         | 1.12%   |
| 0x06001119 | 1         | 1.12%   |
| 0x05000119 | 1         | 1.12%   |
| 0x010000dc | 1         | 1.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 11        | 12.64%  |
| IvyBridge        | 8         | 9.2%    |
| Haswell          | 8         | 9.2%    |
| TigerLake        | 7         | 8.05%   |
| Westmere         | 6         | 6.9%    |
| IceLake          | 6         | 6.9%    |
| Penryn           | 5         | 5.75%   |
| Zen 2            | 3         | 3.45%   |
| Zen              | 3         | 3.45%   |
| Skylake          | 3         | 3.45%   |
| Goldmont plus    | 3         | 3.45%   |
| Zen+             | 2         | 2.3%    |
| Zen 3            | 2         | 2.3%    |
| Silvermont       | 2         | 2.3%    |
| Nehalem          | 2         | 2.3%    |
| K10              | 2         | 2.3%    |
| Goldmont         | 2         | 2.3%    |
| Unknown          | 2         | 2.3%    |
| SandyBridge      | 1         | 1.15%   |
| Puma             | 1         | 1.15%   |
| Piledriver       | 1         | 1.15%   |
| NetBurst         | 1         | 1.15%   |
| K8 Hammer        | 1         | 1.15%   |
| Excavator        | 1         | 1.15%   |
| Core             | 1         | 1.15%   |
| CometLake        | 1         | 1.15%   |
| Bobcat           | 1         | 1.15%   |
| Alderlake Hybrid | 1         | 1.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 50        | 52.63%  |
| AMD               | 23        | 24.21%  |
| Nvidia            | 21        | 22.11%  |
| ASPEED Technology | 1         | 1.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 3.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 3.16%   |
| Intel HD Graphics 530                                                       | 3         | 3.16%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 3.16%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 3.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 3.16%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 2.11%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 2.11%   |
| Intel UHD Graphics 620                                                      | 2         | 2.11%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 2.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 2.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 2.11%   |
| Intel HD Graphics 630                                                       | 2         | 2.11%   |
| Intel HD Graphics 620                                                       | 2         | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 2.11%   |
| AMD Cezanne                                                                 | 2         | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 1.05%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 1.05%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 1.05%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 1.05%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 1.05%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 1.05%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 1.05%   |
| Nvidia GK107M [GeForce GT 650M]                                             | 1         | 1.05%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                 | 1         | 1.05%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 1.05%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 1.05%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 1         | 1.05%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 1         | 1.05%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                          | 1         | 1.05%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1         | 1.05%   |
| Nvidia G92GLM [Quadro FX 2800M]                                             | 1         | 1.05%   |
| Nvidia C79 [GeForce 9400M]                                                  | 1         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 1.05%   |
| Intel Tiger Lake UHD Graphics                                               | 1         | 1.05%   |
| Intel Tiger Lake Iris Xe Graphics                                           | 1         | 1.05%   |
| Intel Iris Plus Graphics 640                                                | 1         | 1.05%   |
| Intel HD Graphics 500                                                       | 1         | 1.05%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 49.43%  |
| 1 x AMD        | 18        | 20.69%  |
| 1 x Nvidia     | 14        | 16.09%  |
| Intel + Nvidia | 5         | 5.75%   |
| Other          | 2         | 2.3%    |
| Intel + AMD    | 2         | 2.3%    |
| AMD + Nvidia   | 2         | 2.3%    |
| AMD + ASPEED   | 1         | 1.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 71        | 81.61%  |
| Proprietary | 13        | 14.94%  |
| Unknown     | 3         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 72.73%  |
| 0.51-1.0   | 8         | 9.09%   |
| 0.01-0.5   | 6         | 6.82%   |
| 3.01-4.0   | 3         | 3.41%   |
| 1.01-2.0   | 3         | 3.41%   |
| 5.01-6.0   | 2         | 2.27%   |
| 7.01-8.0   | 1         | 1.14%   |
| 8.01-16.0  | 1         | 1.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 16.49%  |
| BOE                     | 9         | 9.28%   |
| Chimei Innolux          | 8         | 8.25%   |
| Goldstar                | 6         | 6.19%   |
| Philips                 | 5         | 5.15%   |
| LG Display              | 4         | 4.12%   |
| Hewlett-Packard         | 4         | 4.12%   |
| Apple                   | 4         | 4.12%   |
| Acer                    | 4         | 4.12%   |
| Lenovo                  | 3         | 3.09%   |
| Iiyama                  | 3         | 3.09%   |
| BenQ                    | 3         | 3.09%   |
| AU Optronics            | 3         | 3.09%   |
| AOC                     | 3         | 3.09%   |
| Vizio                   | 2         | 2.06%   |
| Sharp                   | 2         | 2.06%   |
| Dell                    | 2         | 2.06%   |
| Chi Mei Optoelectronics | 2         | 2.06%   |
| Ancor Communications    | 2         | 2.06%   |
| Westinghouse            | 1         | 1.03%   |
| Toshiba                 | 1         | 1.03%   |
| Sony                    | 1         | 1.03%   |
| Sceptre Tech            | 1         | 1.03%   |
| PANDA                   | 1         | 1.03%   |
| Packard Bell            | 1         | 1.03%   |
| Insignia                | 1         | 1.03%   |
| Hitachi                 | 1         | 1.03%   |
| HannStar                | 1         | 1.03%   |
| Gateway                 | 1         | 1.03%   |
| CS_                     | 1         | 1.03%   |
| ASUSTek Computer        | 1         | 1.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 2.06%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 2.06%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch          | 1         | 1.03%   |
| Vizio XVT553SV VIZ0063 1920x1080 1210x680mm 54.6-inch                 | 1         | 1.03%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                  | 1         | 1.03%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 1.03%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 1.03%   |
| Sharp LCD Monitor SHP1526 1920x1280 274x183mm 13.0-inch               | 1         | 1.03%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 1.03%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 1.03%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 1.03%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch   | 1         | 1.03%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 1.03%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch    | 1         | 1.03%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch     | 1         | 1.03%   |
| Samsung Electronics S24E650 SAM0CB9 1920x1080 521x293mm 23.5-inch     | 1         | 1.03%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1         | 1.03%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 1.03%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 1.03%   |
| Samsung Electronics LCD Monitor SAM0D4B 1366x768 609x347mm 27.6-inch  | 1         | 1.03%   |
| Samsung Electronics EPSON PJ SECA605 1600x1200                        | 1         | 1.03%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch              | 1         | 1.03%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 1.03%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 1         | 1.03%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 1.03%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch               | 1         | 1.03%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 1.03%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch         | 1         | 1.03%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 1.03%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 1         | 1.03%   |
| Lenovo LEN-M82-C LEN00A2 1920x1080 476x268mm 21.5-inch                | 1         | 1.03%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch               | 1         | 1.03%   |
| Lenovo C27-35 LEN66BA 1920x1080 597x336mm 27.0-inch                   | 1         | 1.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 43        | 47.25%  |
| 1366x768 (WXGA)    | 10        | 10.99%  |
| 3840x2160 (4K)     | 6         | 6.59%   |
| 2560x1440 (QHD)    | 5         | 5.49%   |
| 1440x900 (WXGA+)   | 5         | 5.49%   |
| 1680x1050 (WSXGA+) | 4         | 4.4%    |
| 1280x800 (WXGA)    | 4         | 4.4%    |
| 3440x1440          | 3         | 3.3%    |
| 2560x1600          | 2         | 2.2%    |
| 1920x1280          | 2         | 2.2%    |
| 1280x1024 (SXGA)   | 2         | 2.2%    |
| 3840x2400          | 1         | 1.1%    |
| 2160x1440          | 1         | 1.1%    |
| 1600x900 (HD+)     | 1         | 1.1%    |
| 1360x768           | 1         | 1.1%    |
| 1280x720 (HD)      | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 18        | 18.56%  |
| 27      | 11        | 11.34%  |
| 23      | 10        | 10.31%  |
| 17      | 10        | 10.31%  |
| 21      | 9         | 9.28%   |
| 13      | 7         | 7.22%   |
| 24      | 6         | 6.19%   |
| 31      | 5         | 5.15%   |
| 14      | 4         | 4.12%   |
| 34      | 3         | 3.09%   |
| 22      | 2         | 2.06%   |
| 19      | 2         | 2.06%   |
| 12      | 2         | 2.06%   |
| 84      | 1         | 1.03%   |
| 54      | 1         | 1.03%   |
| 40      | 1         | 1.03%   |
| 28      | 1         | 1.03%   |
| 25      | 1         | 1.03%   |
| 18      | 1         | 1.03%   |
| 16      | 1         | 1.03%   |
| Unknown | 1         | 1.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 29        | 30.21%  |
| 501-600     | 26        | 27.08%  |
| 401-500     | 14        | 14.58%  |
| 601-700     | 7         | 7.29%   |
| 351-400     | 7         | 7.29%   |
| 201-300     | 6         | 6.25%   |
| 701-800     | 3         | 3.13%   |
| 801-900     | 1         | 1.04%   |
| 1501-2000   | 1         | 1.04%   |
| 1001-1500   | 1         | 1.04%   |
| Unknown     | 1         | 1.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 59        | 68.6%   |
| 16/10 | 18        | 20.93%  |
| 5/4   | 3         | 3.49%   |
| 3/2   | 3         | 3.49%   |
| 21/9  | 3         | 3.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 21        | 22.11%  |
| 101-110        | 17        | 17.89%  |
| 301-350        | 11        | 11.58%  |
| 351-500        | 9         | 9.47%   |
| 81-90          | 8         | 8.42%   |
| 121-130        | 6         | 6.32%   |
| 151-200        | 5         | 5.26%   |
| 141-150        | 4         | 4.21%   |
| 71-80          | 3         | 3.16%   |
| More than 1000 | 2         | 2.11%   |
| 61-70          | 2         | 2.11%   |
| 251-300        | 2         | 2.11%   |
| 131-140        | 1         | 1.05%   |
| 111-120        | 1         | 1.05%   |
| 501-1000       | 1         | 1.05%   |
| 91-100         | 1         | 1.05%   |
| Unknown        | 1         | 1.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 35        | 38.89%  |
| 101-120       | 26        | 28.89%  |
| 121-160       | 18        | 20%     |
| 161-240       | 7         | 7.78%   |
| 1-50          | 2         | 2.22%   |
| More than 240 | 1         | 1.11%   |
| Unknown       | 1         | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 70        | 79.55%  |
| 2     | 16        | 18.18%  |
| 3     | 1         | 1.14%   |
| 0     | 1         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 47        | 38.21%  |
| Intel                             | 47        | 38.21%  |
| Broadcom                          | 7         | 5.69%   |
| Qualcomm Atheros                  | 6         | 4.88%   |
| Ralink                            | 2         | 1.63%   |
| Marvell Technology Group          | 2         | 1.63%   |
| ASIX Electronics                  | 2         | 1.63%   |
| TP-Link                           | 1         | 0.81%   |
| Raspberry Pi                      | 1         | 0.81%   |
| Qualcomm Atheros Communications   | 1         | 0.81%   |
| Nvidia                            | 1         | 0.81%   |
| NetGear                           | 1         | 0.81%   |
| MediaTek                          | 1         | 0.81%   |
| Ericsson Business Mobile Networks | 1         | 0.81%   |
| Broadcom Limited                  | 1         | 0.81%   |
| AVM                               | 1         | 0.81%   |
| ASUSTek Computer                  | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 19.48%  |
| Intel Wireless 8265 / 8275                                        | 5         | 3.25%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.95%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.95%   |
| Intel Wireless 3165                                               | 3         | 1.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.95%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.3%    |
| Realtek 802.11ac NIC                                              | 2         | 1.3%    |
| Intel Wireless 7260                                               | 2         | 1.3%    |
| Intel Wireless 3160                                               | 2         | 1.3%    |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.3%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 2         | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 2         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.3%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.3%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.3%    |
| TP-Link Archer T4U ver.3                                          | 1         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.65%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.65%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.65%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.65%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.65%   |
| Raspberry Pi Pico                                                 | 1         | 0.65%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 48%     |
| Realtek Semiconductor           | 21        | 28%     |
| Broadcom                        | 5         | 6.67%   |
| Qualcomm Atheros                | 4         | 5.33%   |
| Ralink                          | 2         | 2.67%   |
| TP-Link                         | 1         | 1.33%   |
| Qualcomm Atheros Communications | 1         | 1.33%   |
| NetGear                         | 1         | 1.33%   |
| MediaTek                        | 1         | 1.33%   |
| Broadcom Limited                | 1         | 1.33%   |
| AVM                             | 1         | 1.33%   |
| ASUSTek Computer                | 1         | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 5         | 6.67%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 4%      |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 4%      |
| Intel Wireless 3165                                                     | 3         | 4%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 2.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.67%   |
| Realtek 802.11ac NIC                                                    | 2         | 2.67%   |
| Intel Wireless 7260                                                     | 2         | 2.67%   |
| Intel Wireless 3160                                                     | 2         | 2.67%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.67%   |
| TP-Link Archer T4U ver.3                                                | 1         | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.33%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 1.33%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.33%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.33%   |
| NetGear A6150                                                           | 1         | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.33%   |
| Intel Wireless 7265                                                     | 1         | 1.33%   |
| Intel WiFi Link 5100                                                    | 1         | 1.33%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 1.33%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 52.05%  |
| Intel                    | 24        | 32.88%  |
| Broadcom                 | 4         | 5.48%   |
| Qualcomm Atheros         | 2         | 2.74%   |
| Marvell Technology Group | 2         | 2.74%   |
| ASIX Electronics         | 2         | 2.74%   |
| Nvidia                   | 1         | 1.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 38.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 5.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.9%    |
| Intel Ethernet Controller I225-V                                               | 3         | 3.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 3.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 2.6%    |
| Intel I210 Gigabit Network Connection                                          | 2         | 2.6%    |
| Intel Ethernet Connection I217-V                                               | 2         | 2.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 2.6%    |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 2.6%    |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 2.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 2.6%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.3%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.3%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.3%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.3%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 1.3%    |
| Intel I211 Gigabit Network Connection                                          | 1         | 1.3%    |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.3%    |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 1.3%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.3%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.3%    |
| Intel 82576 Gigabit Network Connection                                         | 1         | 1.3%    |
| Intel 82574L Gigabit Network Connection                                        | 1         | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 1.3%    |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 1.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.3%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 49.66%  |
| Ethernet | 71        | 48.97%  |
| Modem    | 2         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 54        | 55.67%  |
| Ethernet | 43        | 44.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 46        | 52.87%  |
| 1     | 35        | 40.23%  |
| 3     | 3         | 3.45%   |
| 0     | 2         | 2.3%    |
| 4     | 1         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 59        | 67.05%  |
| Yes  | 29        | 32.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 28        | 50%     |
| Realtek Semiconductor      | 9         | 16.07%  |
| Broadcom                   | 4         | 7.14%   |
| Apple                      | 4         | 7.14%   |
| IMC Networks               | 3         | 5.36%   |
| Cambridge Silicon Radio    | 2         | 3.57%   |
| Ralink                     | 1         | 1.79%   |
| MediaTek                   | 1         | 1.79%   |
| Integrated System Solution | 1         | 1.79%   |
| Hewlett-Packard            | 1         | 1.79%   |
| Foxconn / Hon Hai          | 1         | 1.79%   |
| Belkin Components          | 1         | 1.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 17.86%  |
| Intel AX201 Bluetooth                                                               | 9         | 16.07%  |
| Realtek Bluetooth Radio                                                             | 6         | 10.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 5.36%   |
| Intel AX210 Bluetooth                                                               | 2         | 3.57%   |
| Intel AX200 Bluetooth                                                               | 2         | 3.57%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 3.57%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 2         | 3.57%   |
| Apple Bluetooth Host Controller                                                     | 2         | 3.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.79%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 1.79%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.79%   |
| MediaTek Wireless_Device                                                            | 1         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.79%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.79%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 1.79%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.79%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.79%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.79%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.79%   |
| Belkin Components F8T013 Bluetooth Adapter                                          | 1         | 1.79%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.79%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 65        | 52.42%  |
| AMD                    | 24        | 19.35%  |
| Nvidia                 | 20        | 16.13%  |
| C-Media Electronics    | 6         | 4.84%   |
| Logitech               | 2         | 1.61%   |
| Generalplus Technology | 2         | 1.61%   |
| ASUSTek Computer       | 2         | 1.61%   |
| Meizu                  | 1         | 0.81%   |
| JMTek                  | 1         | 0.81%   |
| Corsair                | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 5.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 5.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 5.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.35%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 3.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.9%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 2.17%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.17%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.17%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 1.45%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.45%   |
| Generalplus Technology Usb Audio Device                                    | 2         | 1.45%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.45%   |
| ASUSTek Computer USB Audio                                                 | 2         | 1.45%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.45%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.72%   |
| Nvidia stereo controller                                                   | 1         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.72%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.72%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 14        | 20.59%  |
| Samsung Electronics | 11        | 16.18%  |
| Unknown             | 9         | 13.24%  |
| Kingston            | 8         | 11.76%  |
| Micron Technology   | 6         | 8.82%   |
| Crucial             | 5         | 7.35%   |
| Unknown (ABCD)      | 4         | 5.88%   |
| Corsair             | 4         | 5.88%   |
| G.Skill             | 3         | 4.41%   |
| Unifosa             | 1         | 1.47%   |
| Nanya Technology    | 1         | 1.47%   |
| HBS                 | 1         | 1.47%   |
| Unknown             | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 4         | 5.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 2.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.35%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 1.35%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 1.35%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 1.35%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.35%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 1.35%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.35%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s          | 1         | 1.35%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.35%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 1.35%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 1.35%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR 800MT/s               | 1         | 1.35%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.35%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.35%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.35%   |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.35%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 1         | 1.35%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s           | 1         | 1.35%   |
| Samsung RAM M3 78T2953EZ3-CF7 1GB DIMM DDR2 800MT/s              | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 52.54%  |
| DDR3    | 17        | 28.81%  |
| LPDDR4  | 6         | 10.17%  |
| DDR2    | 3         | 5.08%   |
| DDR     | 1         | 1.69%   |
| Unknown | 1         | 1.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 59.68%  |
| DIMM         | 18        | 29.03%  |
| Row Of Chips | 7         | 11.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 25        | 36.76%  |
| 8192  | 20        | 29.41%  |
| 16384 | 14        | 20.59%  |
| 2048  | 5         | 7.35%   |
| 32768 | 2         | 2.94%   |
| 1024  | 2         | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 13        | 20.31%  |
| 2667    | 11        | 17.19%  |
| 2400    | 11        | 17.19%  |
| 1600    | 9         | 14.06%  |
| 1333    | 5         | 7.81%   |
| Unknown | 3         | 4.69%   |
| 4267    | 2         | 3.13%   |
| 2133    | 2         | 3.13%   |
| 800     | 2         | 3.13%   |
| 3333    | 1         | 1.56%   |
| 2666    | 1         | 1.56%   |
| 1867    | 1         | 1.56%   |
| 1334    | 1         | 1.56%   |
| 1067    | 1         | 1.56%   |
| 1066    | 1         | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Dymo-CoStar      | 2         | 50%     |
| Seiko Epson      | 1         | 25%     |
| Graphtec America | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series        | 1         | 25%     |
| Graphtec America Graphtec Printer | 1         | 25%     |
| Dymo-CoStar LabelWriter 450       | 1         | 25%     |
| Dymo-CoStar LabelWriter 310       | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 11        | 21.57%  |
| Realtek Semiconductor                  | 7         | 13.73%  |
| Logitech                               | 5         | 9.8%    |
| Apple                                  | 5         | 9.8%    |
| Microdia                               | 3         | 5.88%   |
| Syntek                                 | 2         | 3.92%   |
| Quanta                                 | 2         | 3.92%   |
| Luxvisions Innotech Limited            | 2         | 3.92%   |
| IMC Networks                           | 2         | 3.92%   |
| ARC International                      | 2         | 3.92%   |
| U0AS01A-0                              | 1         | 1.96%   |
| Suyin                                  | 1         | 1.96%   |
| Sunplus Innovation Technology          | 1         | 1.96%   |
| Ricoh                                  | 1         | 1.96%   |
| Microsoft                              | 1         | 1.96%   |
| Lenovo                                 | 1         | 1.96%   |
| Generalplus Technology                 | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.96%   |
| Alcor Micro                            | 1         | 1.96%   |
| Acer                                   | 1         | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                   | 3         | 5.88%   |
| Syntek Integrated Camera                                | 2         | 3.92%   |
| Realtek USB2.0 camera                                   | 2         | 3.92%   |
| Microdia Webcam Vitade AF                               | 2         | 3.92%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 3.92%   |
| Chicony Integrated Camera                               | 2         | 3.92%   |
| ARC International Camera                                | 2         | 3.92%   |
| U0AS01A-0 U0AS01A-0                                     | 1         | 1.96%   |
| Suyin USB 2.0 Camera                                    | 1         | 1.96%   |
| Sunplus Integrated_Webcam_FHD                           | 1         | 1.96%   |
| Ricoh Dell Laptop Integrated Webcam                     | 1         | 1.96%   |
| Realtek USB Camera                                      | 1         | 1.96%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 1.96%   |
| Realtek Integrated_Webcam_HD                            | 1         | 1.96%   |
| Realtek Integrated Webcam HD                            | 1         | 1.96%   |
| Realtek HP 1.0MP High Definition Webcam                 | 1         | 1.96%   |
| Quanta ov9734_techfront_camera                          | 1         | 1.96%   |
| Quanta HD User Facing                                   | 1         | 1.96%   |
| Microsoft LifeCam VX-500 [1357]                         | 1         | 1.96%   |
| Microdia Integrated_Webcam_2M                           | 1         | 1.96%   |
| Logitech Webcam C925e                                   | 1         | 1.96%   |
| Logitech Webcam C270                                    | 1         | 1.96%   |
| Logitech StreamCam                                      | 1         | 1.96%   |
| Logitech QuickCam E 3500                                | 1         | 1.96%   |
| Logitech HD Webcam C525                                 | 1         | 1.96%   |
| Lenovo CNF7237&CNF7238                                  | 1         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 1         | 1.96%   |
| IMC Networks Integrated Camera                          | 1         | 1.96%   |
| Generalplus GENERAL WEBCAM                              | 1         | 1.96%   |
| Chicony USB2.0 VGA UVC WebCam                           | 1         | 1.96%   |
| Chicony USB2.0 Camera                                   | 1         | 1.96%   |
| Chicony USB 2.0 Camera                                  | 1         | 1.96%   |
| Chicony LG Camera                                       | 1         | 1.96%   |
| Chicony Integrated HP HD Webcam                         | 1         | 1.96%   |
| Chicony HP Webcam                                       | 1         | 1.96%   |
| Chicony HP Truevision HD                                | 1         | 1.96%   |
| Chicony HP HD Camera                                    | 1         | 1.96%   |
| Chicony HD Webcam                                       | 1         | 1.96%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 1         | 1.96%   |
| Apple iPhone5/5C/5S/6                                   | 1         | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 57.14%  |
| Validity Sensors           | 1         | 14.29%  |
| Upek                       | 1         | 14.29%  |
| Synaptics                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 4         | 57.14%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 14.29%  |
| Synaptics  WBDI                                        | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 71.43%  |
| SCM Microsystems      | 1         | 14.29%  |
| Advanced Card Systems | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 14.29%  |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 65        | 73.86%  |
| 1     | 19        | 21.59%  |
| 2     | 3         | 3.41%   |
| 3     | 1         | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 7         | 26.92%  |
| Chipcard           | 7         | 26.92%  |
| Net/wireless       | 3         | 11.54%  |
| Graphics card      | 2         | 7.69%   |
| Bluetooth          | 2         | 7.69%   |
| Unassigned class   | 1         | 3.85%   |
| Network            | 1         | 3.85%   |
| Flash memory       | 1         | 3.85%   |
| Card reader        | 1         | 3.85%   |
| Camera             | 1         | 3.85%   |

