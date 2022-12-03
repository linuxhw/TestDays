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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | Notebook    | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | Notebook    | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Dell          | 0DPRF9 A00                  | All in one  | [3d0b820b58](https://linux-hardware.org/?probe=3d0b820b58) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | Notebook    | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
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
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
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


| Version                                | Computers | Percent |
|----------------------------------------|-----------|---------|
| 5.15.0-47-generic                      | 18        | 13.53%  |
| 5.15.0-48-generic                      | 13        | 9.77%   |
| 5.15.0-52-generic                      | 11        | 8.27%   |
| 5.15.0-46-generic                      | 11        | 8.27%   |
| 5.15.0-40-generic                      | 9         | 6.77%   |
| 5.15.0-25-generic                      | 8         | 6.02%   |
| 5.15.0-27-generic                      | 7         | 5.26%   |
| 5.15.0-53-generic                      | 6         | 4.51%   |
| 5.15.0-50-generic                      | 6         | 4.51%   |
| 5.15.0-43-generic                      | 6         | 4.51%   |
| 5.15.0-41-generic                      | 6         | 4.51%   |
| 5.15.0-30-generic                      | 4         | 3.01%   |
| 5.15.0-37-generic                      | 3         | 2.26%   |
| 5.15.0-52-lowlatency                   | 2         | 1.5%    |
| 5.15.0-39-generic                      | 2         | 1.5%    |
| 5.15.0-35-generic                      | 2         | 1.5%    |
| 6.0.8-x64v1-xanmod1                    | 1         | 0.75%   |
| 5.18.0-odroid-arm64                    | 1         | 0.75%   |
| 5.18.0-1-generic                       | 1         | 0.75%   |
| 5.18.0-051800-generic                  | 1         | 0.75%   |
| 5.17.1-051701-generic                  | 1         | 0.75%   |
| 5.17.0-rc4-next-20220217-g21d89a4d51a7 | 1         | 0.75%   |
| 5.17.0-1003-oem                        | 1         | 0.75%   |
| 5.15.0-46-lowlatency                   | 1         | 0.75%   |
| 5.15.0-33-generic                      | 1         | 0.75%   |
| 5.15.0-23-generic                      | 1         | 0.75%   |
| 5.15.0-22-generic                      | 1         | 0.75%   |
| 5.15.0-18-generic                      | 1         | 0.75%   |
| 5.15.0-11-generic                      | 1         | 0.75%   |
| 5.15.0-1014-raspi                      | 1         | 0.75%   |
| 5.15.0-1012-raspi                      | 1         | 0.75%   |
| 5.15.0-1011-raspi                      | 1         | 0.75%   |
| 5.14.0-1054-oem                        | 1         | 0.75%   |
| 5.13.0-52-generic                      | 1         | 0.75%   |
| 5.13.0-19-generic                      | 1         | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 115       | 92%     |
| 5.18.0  | 3         | 2.4%    |
| 5.17.0  | 2         | 1.6%    |
| 5.13.0  | 2         | 1.6%    |
| 6.0.8   | 1         | 0.8%    |
| 5.17.1  | 1         | 0.8%    |
| 5.14.0  | 1         | 0.8%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 115       | 92%     |
| 5.18    | 3         | 2.4%    |
| 5.17    | 3         | 2.4%    |
| 5.13    | 2         | 1.6%    |
| 6.0     | 1         | 0.8%    |
| 5.14    | 1         | 0.8%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 121       | 97.58%  |
| aarch64 | 2         | 1.61%   |
| armv7l  | 1         | 0.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MATE | 122       | 98.39%  |
| KDE5 | 2         | 1.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 121       | 97.58%  |
| Wayland | 3         | 2.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 102       | 80.95%  |
| Unknown | 13        | 10.32%  |
| GDM3    | 10        | 7.94%   |
| SDDM    | 1         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 50        | 40.32%  |
| fr_FR | 13        | 10.48%  |
| de_DE | 12        | 9.68%   |
| it_IT | 10        | 8.06%   |
| ru_RU | 5         | 4.03%   |
| en_GB | 5         | 4.03%   |
| pt_BR | 4         | 3.23%   |
| en_CA | 4         | 3.23%   |
| en_AU | 4         | 3.23%   |
| fi_FI | 3         | 2.42%   |
| de_CH | 3         | 2.42%   |
| hr_HR | 2         | 1.61%   |
| es_ES | 2         | 1.61%   |
| zh_CN | 1         | 0.81%   |
| pl_PL | 1         | 0.81%   |
| nl_NL | 1         | 0.81%   |
| es_PE | 1         | 0.81%   |
| es_AR | 1         | 0.81%   |
| en_IL | 1         | 0.81%   |
| C     | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 67        | 51.54%  |
| BIOS | 63        | 48.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 113       | 90.4%   |
| Zfs     | 4         | 3.2%    |
| Overlay | 4         | 3.2%    |
| Btrfs   | 2         | 1.6%    |
| Xfs     | 1         | 0.8%    |
| Jfs     | 1         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 83        | 64.84%  |
| Unknown | 35        | 27.34%  |
| MBR     | 10        | 7.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 83.87%  |
| Yes       | 20        | 16.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 60.32%  |
| Yes       | 50        | 39.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 21        | 16.94%  |
| ASUSTek Computer        | 21        | 16.94%  |
| Lenovo                  | 16        | 12.9%   |
| Dell                    | 13        | 10.48%  |
| MSI                     | 9         | 7.26%   |
| Apple                   | 5         | 4.03%   |
| Acer                    | 5         | 4.03%   |
| Intel                   | 4         | 3.23%   |
| ASRock                  | 4         | 3.23%   |
| Gigabyte Technology     | 3         | 2.42%   |
| Toshiba                 | 2         | 1.61%   |
| Unknown                 | 2         | 1.61%   |
| TYAN Computer           | 1         | 0.81%   |
| TrekStor                | 1         | 0.81%   |
| Sony                    | 1         | 0.81%   |
| Raspberry Pi Foundation | 1         | 0.81%   |
| Notebook                | 1         | 0.81%   |
| Microsoft               | 1         | 0.81%   |
| MicroByte               | 1         | 0.81%   |
| Medion                  | 1         | 0.81%   |
| LincPlus                | 1         | 0.81%   |
| LG Electronics          | 1         | 0.81%   |
| IPASON                  | 1         | 0.81%   |
| HYPERPC                 | 1         | 0.81%   |
| HUAWEI                  | 1         | 0.81%   |
| HONOR                   | 1         | 0.81%   |
| Hardkernel              | 1         | 0.81%   |
| Google                  | 1         | 0.81%   |
| Compaq                  | 1         | 0.81%   |
| Chuwi                   | 1         | 0.81%   |
| AZW                     | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP Compaq Elite 8300 SFF             | 2         | 1.61%   |
| Unknown                              | 2         | 1.61%   |
| TYAN S7012                           | 1         | 0.81%   |
| TrekStor Surfbook A13B               | 1         | 0.81%   |
| Toshiba Satellite P50-B-10Z          | 1         | 0.81%   |
| Toshiba Satellite C50D-A-133         | 1         | 0.81%   |
| Sony VPCEA36FG                       | 1         | 0.81%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 1         | 0.81%   |
| Notebook NJx0MU                      | 1         | 0.81%   |
| MSI p6-2330                          | 1         | 0.81%   |
| MSI MS-7C56                          | 1         | 0.81%   |
| MSI MS-7C09                          | 1         | 0.81%   |
| MSI MS-7C02                          | 1         | 0.81%   |
| MSI MS-7982                          | 1         | 0.81%   |
| MSI MS-7817                          | 1         | 0.81%   |
| MSI MS-7758                          | 1         | 0.81%   |
| MSI MS-7599                          | 1         | 0.81%   |
| MSI B02311                           | 1         | 0.81%   |
| Microsoft Surface 2                  | 1         | 0.81%   |
| MicroByte ezbook                     | 1         | 0.81%   |
| Medion MS-7797                       | 1         | 0.81%   |
| LincPlus LINNCPLUS P1                | 1         | 0.81%   |
| LG 17Z990-R.AAS8U1                   | 1         | 0.81%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.81%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.81%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.81%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 0.81%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.81%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.81%   |
| Lenovo ThinkCentre M710q 10MQSC0N00  | 1         | 0.81%   |
| Lenovo ThinkCentre M710q 10MQS0FR01  | 1         | 0.81%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 0.81%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 0.81%   |
| Lenovo T530-28ICB                    | 1         | 0.81%   |
| Lenovo IdeaPadFlex 6-14IKB 81EM      | 1         | 0.81%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 0.81%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 0.81%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 1         | 0.81%   |
| Lenovo IdeaPad 130-15AST 81H5        | 1         | 0.81%   |
| IPASON MaxBook P1                    | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 5         | 4.03%   |
| Dell Latitude      | 5         | 4.03%   |
| Lenovo IdeaPad     | 4         | 3.23%   |
| HP Pavilion        | 3         | 2.42%   |
| HP EliteBook       | 3         | 2.42%   |
| HP Compaq          | 3         | 2.42%   |
| ASUS ROG           | 3         | 2.42%   |
| ASUS PRIME         | 3         | 2.42%   |
| Acer Aspire        | 3         | 2.42%   |
| Toshiba Satellite  | 2         | 1.61%   |
| Lenovo ThinkCentre | 2         | 1.61%   |
| Lenovo ThinkBook   | 2         | 1.61%   |
| HP ProBook         | 2         | 1.61%   |
| HP ENVY            | 2         | 1.61%   |
| HP EliteDesk       | 2         | 1.61%   |
| Dell XPS           | 2         | 1.61%   |
| Dell Precision     | 2         | 1.61%   |
| Dell OptiPlex      | 2         | 1.61%   |
| Dell Inspiron      | 2         | 1.61%   |
| ASUS VivoBook      | 2         | 1.61%   |
| Unknown            | 2         | 1.61%   |
| TYAN S7012         | 1         | 0.81%   |
| TrekStor Surfbook  | 1         | 0.81%   |
| Sony VPCEA36FG     | 1         | 0.81%   |
| RPi Raspberry      | 1         | 0.81%   |
| Notebook NJx0MU    | 1         | 0.81%   |
| MSI p6-2330        | 1         | 0.81%   |
| MSI MS-7C56        | 1         | 0.81%   |
| MSI MS-7C09        | 1         | 0.81%   |
| MSI MS-7C02        | 1         | 0.81%   |
| MSI MS-7982        | 1         | 0.81%   |
| MSI MS-7817        | 1         | 0.81%   |
| MSI MS-7758        | 1         | 0.81%   |
| MSI MS-7599        | 1         | 0.81%   |
| MSI B02311         | 1         | 0.81%   |
| Microsoft Surface  | 1         | 0.81%   |
| MicroByte ezbook   | 1         | 0.81%   |
| Medion MS-7797     | 1         | 0.81%   |
| LincPlus LINNCPLUS | 1         | 0.81%   |
| LG 17Z990-R.AAS8U1 | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 24        | 19.35%  |
| 2020    | 12        | 9.68%   |
| 2018    | 12        | 9.68%   |
| 2012    | 11        | 8.87%   |
| 2013    | 8         | 6.45%   |
| 2010    | 8         | 6.45%   |
| 2019    | 7         | 5.65%   |
| 2014    | 7         | 5.65%   |
| 2011    | 6         | 4.84%   |
| 2009    | 6         | 4.84%   |
| 2022    | 5         | 4.03%   |
| 2016    | 4         | 3.23%   |
| 2015    | 4         | 3.23%   |
| 2017    | 3         | 2.42%   |
| 2007    | 2         | 1.61%   |
| 2006    | 2         | 1.61%   |
| Unknown | 2         | 1.61%   |
| 2008    | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 63        | 50.81%  |
| Desktop        | 48        | 38.71%  |
| Tablet         | 3         | 2.42%   |
| Mini pc        | 3         | 2.42%   |
| System on chip | 2         | 1.61%   |
| Convertible    | 2         | 1.61%   |
| All in one     | 2         | 1.61%   |
| Server         | 1         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 118       | 92.91%  |
| Enabled  | 9         | 7.09%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 99.19%  |
| Yes  | 1         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 25%     |
| 8.01-16.0   | 24        | 19.35%  |
| 3.01-4.0    | 22        | 17.74%  |
| 16.01-24.0  | 22        | 17.74%  |
| 32.01-64.0  | 17        | 13.71%  |
| 64.01-256.0 | 4         | 3.23%   |
| 24.01-32.0  | 2         | 1.61%   |
| 1.01-2.0    | 2         | 1.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 37        | 28.91%  |
| 1.01-2.0  | 33        | 25.78%  |
| 4.01-8.0  | 27        | 21.09%  |
| 3.01-4.0  | 18        | 14.06%  |
| 8.01-16.0 | 7         | 5.47%   |
| 0.51-1.0  | 6         | 4.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 62.1%   |
| 2      | 21        | 16.94%  |
| 3      | 13        | 10.48%  |
| 4      | 6         | 4.84%   |
| 6      | 4         | 3.23%   |
| 5      | 2         | 1.61%   |
| 7      | 1         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 60.48%  |
| Yes       | 49        | 39.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 80.65%  |
| No        | 24        | 19.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 82.26%  |
| No        | 22        | 17.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 64.8%   |
| No        | 44        | 35.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 20        | 16.13%  |
| Germany     | 14        | 11.29%  |
| Italy       | 13        | 10.48%  |
| France      | 12        | 9.68%   |
| Brazil      | 6         | 4.84%   |
| UK          | 5         | 4.03%   |
| Spain       | 5         | 4.03%   |
| Russia      | 5         | 4.03%   |
| Canada      | 5         | 4.03%   |
| Finland     | 4         | 3.23%   |
| Turkey      | 3         | 2.42%   |
| Switzerland | 3         | 2.42%   |
| Croatia     | 3         | 2.42%   |
| Australia   | 3         | 2.42%   |
| Serbia      | 2         | 1.61%   |
| Portugal    | 2         | 1.61%   |
| Estonia     | 2         | 1.61%   |
| Ukraine     | 1         | 0.81%   |
| Romania     | 1         | 0.81%   |
| Poland      | 1         | 0.81%   |
| Peru        | 1         | 0.81%   |
| Paraguay    | 1         | 0.81%   |
| Netherlands | 1         | 0.81%   |
| Israel      | 1         | 0.81%   |
| India       | 1         | 0.81%   |
| Hungary     | 1         | 0.81%   |
| Greece      | 1         | 0.81%   |
| Georgia     | 1         | 0.81%   |
| Colombia    | 1         | 0.81%   |
| China       | 1         | 0.81%   |
| Bulgaria    | 1         | 0.81%   |
| Belgium     | 1         | 0.81%   |
| Austria     | 1         | 0.81%   |
| Argentina   | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Zagreb           | 2         | 1.59%   |
| Vancouver        | 2         | 1.59%   |
| Turku            | 2         | 1.59%   |
| Paris            | 2         | 1.59%   |
| Melbourne        | 2         | 1.59%   |
| Mannheim         | 2         | 1.59%   |
| Lansdale         | 2         | 1.59%   |
| Berlin           | 2         | 1.59%   |
| Belgrade         | 2         | 1.59%   |
| York             | 1         | 0.79%   |
| Xining           | 1         | 0.79%   |
| Washington       | 1         | 0.79%   |
| Warsaw           | 1         | 0.79%   |
| Villeurbanne     | 1         | 0.79%   |
| Viana do Castelo | 1         | 0.79%   |
| Velyki Mosty     | 1         | 0.79%   |
| Varna            | 1         | 0.79%   |
| Valenciennes     | 1         | 0.79%   |
| Tula             | 1         | 0.79%   |
| Trenton          | 1         | 0.79%   |
| Toulon           | 1         | 0.79%   |
| Thane            | 1         | 0.79%   |
| Terrace          | 1         | 0.79%   |
| Tel Aviv         | 1         | 0.79%   |
| Tartu            | 1         | 0.79%   |
| Taranto          | 1         | 0.79%   |
| Talence          | 1         | 0.79%   |
| Stuttgart        | 1         | 0.79%   |
| St Petersburg    | 1         | 0.79%   |
| Split            | 1         | 0.79%   |
| Southampton      | 1         | 0.79%   |
| Seville          | 1         | 0.79%   |
| Settimo Torinese | 1         | 0.79%   |
| Selargius        | 1         | 0.79%   |
| Seia             | 1         | 0.79%   |
| Sauerlach        | 1         | 0.79%   |
| Sarospatak       | 1         | 0.79%   |
| Sao Paulo        | 1         | 0.79%   |
| Saint-Etienne    | 1         | 0.79%   |
| Rostov-on-Don    | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 48     | 17.02%  |
| WDC                 | 24        | 37     | 12.77%  |
| Seagate             | 19        | 23     | 10.11%  |
| Crucial             | 14        | 14     | 7.45%   |
| SanDisk             | 13        | 18     | 6.91%   |
| Toshiba             | 10        | 12     | 5.32%   |
| Unknown             | 9         | 12     | 4.79%   |
| Kingston            | 6         | 7      | 3.19%   |
| Phison              | 5         | 5      | 2.66%   |
| Hitachi             | 5         | 5      | 2.66%   |
| A-DATA Technology   | 5         | 5      | 2.66%   |
| SK hynix            | 4         | 4      | 2.13%   |
| SPCC                | 3         | 3      | 1.6%    |
| KingSpec            | 3         | 3      | 1.6%    |
| China               | 3         | 3      | 1.6%    |
| Netac               | 2         | 2      | 1.06%   |
| Micron Technology   | 2         | 2      | 1.06%   |
| KIOXIA              | 2         | 2      | 1.06%   |
| Intel               | 2         | 2      | 1.06%   |
| HGST                | 2         | 2      | 1.06%   |
| UMIS                | 1         | 1      | 0.53%   |
| SSSTC               | 1         | 1      | 0.53%   |
| RZX                 | 1         | 1      | 0.53%   |
| NGFF                | 1         | 1      | 0.53%   |
| Maxtor              | 1         | 1      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| LITEON              | 1         | 1      | 0.53%   |
| Lenovo              | 1         | 1      | 0.53%   |
| Kston               | 1         | 1      | 0.53%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.53%   |
| Kimtigo             | 1         | 1      | 0.53%   |
| KESU                | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| Intenso             | 1         | 1      | 0.53%   |
| Hjwdz               | 1         | 1      | 0.53%   |
| GOODRAM             | 1         | 1      | 0.53%   |
| Gigabyte Technology | 1         | 1      | 0.53%   |
| faspeed             | 1         | 1      | 0.53%   |
| DAS                 | 1         | 6      | 0.53%   |
| BAITITON            | 1         | 1      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Crucial CT1000BX500SSD1 1TB      | 4         | 1.85%   |
| Seagate ST2000DM001-1ER164 2TB   | 3         | 1.39%   |
| Crucial CT240BX500SSD1 240GB     | 3         | 1.39%   |
| Crucial CT2000MX500SSD1 2TB      | 3         | 1.39%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 2         | 0.93%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2         | 0.93%   |
| Toshiba MQ01ABF050 500GB         | 2         | 0.93%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.93%   |
| Seagate ST4000DM004-2CV104 4TB   | 2         | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB   | 2         | 0.93%   |
| SanDisk SSD PLUS 480GB           | 2         | 0.93%   |
| Samsung SSD 980 PRO 1TB          | 2         | 0.93%   |
| Samsung SSD 870 QVO 2TB          | 2         | 0.93%   |
| Samsung SSD 870 QVO 1TB          | 2         | 0.93%   |
| Samsung NVMe SSD Drive 1TB       | 2         | 0.93%   |
| Samsung MZVLQ512HBLU-00BH1 512GB | 2         | 0.93%   |
| Kingston SA400S37480G 480GB SSD  | 2         | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.46%   |
| WDC WDS100T2B0C 1TB              | 1         | 0.46%   |
| WDC WDBNCE0010PNC 1TB SSD        | 1         | 0.46%   |
| WDC WD800JD-22JNC0 69GB          | 1         | 0.46%   |
| WDC WD8001FZBX-00ASYA0 8TB       | 1         | 0.46%   |
| WDC WD6400AAKS-00E4A0 640GB      | 1         | 0.46%   |
| WDC WD60 EFAX-68JH4N1 6TB        | 1         | 0.46%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1         | 0.46%   |
| WDC WD5000AAKX-08ERMA0 500GB     | 1         | 0.46%   |
| WDC WD5000AAKX-003CA0 500GB      | 1         | 0.46%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1         | 0.46%   |
| WDC WD40EZRZ-22GXCB0 4TB         | 1         | 0.46%   |
| WDC WD40EFZX-68AWUN0 4TB         | 1         | 0.46%   |
| WDC WD40 PURZ-85TTDY0 4TB        | 1         | 0.46%   |
| WDC WD30EFRX-68N32N0 3TB         | 1         | 0.46%   |
| WDC WD3000HLFS-01G6U0 304GB      | 1         | 0.46%   |
| WDC WD2500AAKX-753CA1 250GB      | 1         | 0.46%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.46%   |
| WDC WD20EADS-00R6B0 2TB          | 1         | 0.46%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 1         | 0.46%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1         | 0.46%   |
| WDC WD10EZEX-75WN4A0 1TB         | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 32     | 35.59%  |
| Seagate             | 19        | 23     | 32.2%   |
| Toshiba             | 7         | 8      | 11.86%  |
| Hitachi             | 5         | 5      | 8.47%   |
| Samsung Electronics | 2         | 3      | 3.39%   |
| HGST                | 2         | 2      | 3.39%   |
| Maxtor              | 1         | 1      | 1.69%   |
| KESU                | 1         | 1      | 1.69%   |
| DAS                 | 1         | 6      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 19.74%  |
| Crucial             | 14        | 14     | 18.42%  |
| SanDisk             | 10        | 13     | 13.16%  |
| Kingston            | 4         | 4      | 5.26%   |
| A-DATA Technology   | 4         | 4      | 5.26%   |
| SPCC                | 3         | 3      | 3.95%   |
| KingSpec            | 3         | 3      | 3.95%   |
| China               | 3         | 3      | 3.95%   |
| WDC                 | 2         | 2      | 2.63%   |
| Unknown             | 1         | 1      | 1.32%   |
| Toshiba             | 1         | 2      | 1.32%   |
| SK hynix            | 1         | 1      | 1.32%   |
| RZX                 | 1         | 1      | 1.32%   |
| NGFF                | 1         | 1      | 1.32%   |
| Netac               | 1         | 1      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| LITEON              | 1         | 1      | 1.32%   |
| Kston               | 1         | 1      | 1.32%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.32%   |
| JMicron Technology  | 1         | 1      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| GOODRAM             | 1         | 1      | 1.32%   |
| BAITITON            | 1         | 1      | 1.32%   |
| ASMT                | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 60        | 84     | 37.04%  |
| HDD     | 46        | 81     | 28.4%   |
| NVMe    | 45        | 58     | 27.78%  |
| MMC     | 8         | 10     | 4.94%   |
| Unknown | 3         | 4      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 150    | 57.05%  |
| NVMe | 45        | 58     | 30.2%   |
| SAS  | 11        | 19     | 7.38%   |
| MMC  | 8         | 10     | 5.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 94     | 52.34%  |
| 0.51-1.0   | 34        | 39     | 26.56%  |
| 1.01-2.0   | 14        | 16     | 10.94%  |
| 3.01-4.0   | 7         | 8      | 5.47%   |
| 4.01-10.0  | 4         | 4      | 3.13%   |
| 2.01-3.0   | 2         | 4      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 27.78%  |
| 251-500        | 30        | 23.81%  |
| 501-1000       | 15        | 11.9%   |
| 1001-2000      | 12        | 9.52%   |
| More than 3000 | 11        | 8.73%   |
| 51-100         | 7         | 5.56%   |
| 21-50          | 6         | 4.76%   |
| 1-20           | 6         | 4.76%   |
| 2001-3000      | 3         | 2.38%   |
| Unknown        | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 26.19%  |
| 101-250        | 20        | 15.87%  |
| 21-50          | 19        | 15.08%  |
| 51-100         | 19        | 15.08%  |
| 501-1000       | 11        | 8.73%   |
| More than 3000 | 7         | 5.56%   |
| 251-500        | 7         | 5.56%   |
| 1001-2000      | 7         | 5.56%   |
| 2001-3000      | 2         | 1.59%   |
| Unknown        | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB              | 2         | 2      | 15.38%  |
| WDC WD1001FALS-40Y6A0 1TB                    | 1         | 1      | 7.69%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 7.69%   |
| Seagate ST2000DM001-1ER164 2TB               | 1         | 1      | 7.69%   |
| Samsung Electronics SSD 960 PRO 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 7.69%   |
| NGFF 2280 256GB SSD                          | 1         | 1      | 7.69%   |
| Netac SSD 256GB                              | 1         | 1      | 7.69%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 7.69%   |
| Hitachi HTS721080G9SA00 80GB                 | 1         | 1      | 7.69%   |
| DAS TerraMaster 500GB                        | 1         | 3      | 7.69%   |
| China SSD 180GB                              | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 30.77%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| NGFF                | 1         | 1      | 7.69%   |
| Netac               | 1         | 1      | 7.69%   |
| Intel               | 1         | 1      | 7.69%   |
| Hitachi             | 1         | 1      | 7.69%   |
| DAS                 | 1         | 3      | 7.69%   |
| China               | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 57.14%  |
| WDC     | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |
| DAS     | 1         | 3      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 9      | 50%     |
| SSD  | 4         | 4      | 33.33%  |
| NVMe | 2         | 2      | 16.67%  |

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
| Works    | 75        | 120    | 53.57%  |
| Detected | 53        | 102    | 37.86%  |
| Malfunc  | 12        | 15     | 8.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 80        | 50.63%  |
| AMD                            | 25        | 15.82%  |
| Samsung Electronics            | 18        | 11.39%  |
| SanDisk                        | 6         | 3.8%    |
| Phison Electronics             | 6         | 3.8%    |
| Toshiba America Info Systems   | 3         | 1.9%    |
| Kingston Technology Company    | 3         | 1.9%    |
| ASMedia Technology             | 3         | 1.9%    |
| SK hynix                       | 2         | 1.27%   |
| Silicon Motion                 | 2         | 1.27%   |
| KIOXIA                         | 2         | 1.27%   |
| ADATA Technology               | 2         | 1.27%   |
| Union Memory (Shenzhen)        | 1         | 0.63%   |
| Solid State Storage Technology | 1         | 0.63%   |
| Nvidia                         | 1         | 0.63%   |
| Micron Technology              | 1         | 0.63%   |
| Marvell Technology Group       | 1         | 0.63%   |
| Lenovo                         | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 15        | 8.15%   |
| Samsung NVMe SSD Controller 980                                                        | 9         | 4.89%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 6         | 3.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 3.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 3.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 5         | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 5         | 2.72%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 5         | 2.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 2.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 4         | 2.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 4         | 2.17%   |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 2.17%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 1.63%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 1.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 3         | 1.63%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 3         | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 3         | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 3         | 1.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 2         | 1.09%   |
| Phison NVMe Storage Controller                                                         | 2         | 1.09%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 1.09%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 2         | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 1.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 1.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                                 | 2         | 1.09%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 2         | 1.09%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 89        | 54.27%  |
| NVMe | 45        | 27.44%  |
| IDE  | 16        | 9.76%   |
| RAID | 14        | 8.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 91        | 73.39%  |
| AMD    | 30        | 24.19%  |
| ARM    | 3         | 2.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-3517U CPU @ 1.90GHz           | 3         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.61%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.61%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 1.61%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.61%   |
| ARM Processor                               | 2         | 1.61%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.61%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.61%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.81%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 0.81%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.81%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.81%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.81%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.81%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 0.81%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1         | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i7-8705G CPU @ 3.10GHz           | 1         | 0.81%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1         | 0.81%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.81%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.81%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.81%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.81%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1         | 0.81%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.81%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.81%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.81%   |
| Intel Core i7 CPU X 920 @ 2.00GHz           | 1         | 0.81%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1         | 0.81%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 0.81%   |
| Intel Core i5-7400T CPU @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i5-7260U CPU @ 2.20GHz           | 1         | 0.81%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 25        | 20.16%  |
| Intel Core i7        | 22        | 17.74%  |
| Other                | 18        | 14.52%  |
| AMD Ryzen 5          | 9         | 7.26%   |
| Intel Core i3        | 8         | 6.45%   |
| Intel Core 2 Duo     | 6         | 4.84%   |
| Intel Celeron        | 6         | 4.84%   |
| Intel Pentium        | 4         | 3.23%   |
| AMD Ryzen 7          | 3         | 2.42%   |
| AMD Ryzen 3          | 3         | 2.42%   |
| Intel Xeon           | 2         | 1.61%   |
| AMD Ryzen 9          | 2         | 1.61%   |
| AMD Athlon II X2     | 2         | 1.61%   |
| AMD A6               | 2         | 1.61%   |
| Intel Pentium Silver | 1         | 0.81%   |
| Intel Pentium 4      | 1         | 0.81%   |
| Intel Core 2 Quad    | 1         | 0.81%   |
| AMD Turion 64 Mobile | 1         | 0.81%   |
| AMD Ryzen 7 PRO      | 1         | 0.81%   |
| AMD Phenom II X6     | 1         | 0.81%   |
| AMD FX               | 1         | 0.81%   |
| AMD E1               | 1         | 0.81%   |
| AMD E                | 1         | 0.81%   |
| AMD Athlon II X4     | 1         | 0.81%   |
| AMD A8               | 1         | 0.81%   |
| AMD A4               | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 57        | 45.97%  |
| 2       | 40        | 32.26%  |
| 6       | 12        | 9.68%   |
| 8       | 8         | 6.45%   |
| 1       | 3         | 2.42%   |
| 12      | 2         | 1.61%   |
| 10      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 122       | 98.39%  |
| 2       | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 76        | 61.29%  |
| 1       | 47        | 37.9%   |
| Unknown | 1         | 0.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 123       | 99.19%  |
| Unknown        | 1         | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 39.53%  |
| 0x806c1    | 7         | 5.43%   |
| 0x306a9    | 7         | 5.43%   |
| 0x806d1    | 3         | 2.33%   |
| 0x506e3    | 3         | 2.33%   |
| 0x306c3    | 3         | 2.33%   |
| 0x206a7    | 3         | 2.33%   |
| 0x20655    | 3         | 2.33%   |
| 0x08108109 | 3         | 2.33%   |
| 0xa0671    | 2         | 1.55%   |
| 0x906ea    | 2         | 1.55%   |
| 0x906e9    | 2         | 1.55%   |
| 0x806ec    | 2         | 1.55%   |
| 0x806ea    | 2         | 1.55%   |
| 0x706e5    | 2         | 1.55%   |
| 0x706a8    | 2         | 1.55%   |
| 0x506c9    | 2         | 1.55%   |
| 0x40651    | 2         | 1.55%   |
| 0x1067a    | 2         | 1.55%   |
| 0x0a50000c | 2         | 1.55%   |
| 0x08608103 | 2         | 1.55%   |
| 0xa0653    | 1         | 0.78%   |
| 0x906ed    | 1         | 0.78%   |
| 0x906c0    | 1         | 0.78%   |
| 0x90672    | 1         | 0.78%   |
| 0x806eb    | 1         | 0.78%   |
| 0x806e9    | 1         | 0.78%   |
| 0x6fd      | 1         | 0.78%   |
| 0x6fb      | 1         | 0.78%   |
| 0x306f2    | 1         | 0.78%   |
| 0x30678    | 1         | 0.78%   |
| 0x206c2    | 1         | 0.78%   |
| 0x106e5    | 1         | 0.78%   |
| 0x10677    | 1         | 0.78%   |
| 0x08608102 | 1         | 0.78%   |
| 0x08101016 | 1         | 0.78%   |
| 0x07030105 | 1         | 0.78%   |
| 0x0700010f | 1         | 0.78%   |
| 0x06001119 | 1         | 0.78%   |
| 0x05000119 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 12%     |
| IvyBridge        | 12        | 9.6%    |
| Haswell          | 11        | 8.8%    |
| Unknown          | 10        | 8%      |
| TigerLake        | 8         | 6.4%    |
| Icelake          | 7         | 5.6%    |
| Westmere         | 6         | 4.8%    |
| Zen 2            | 5         | 4%      |
| Skylake          | 5         | 4%      |
| Penryn           | 5         | 4%      |
| Zen+             | 4         | 3.2%    |
| SandyBridge      | 4         | 3.2%    |
| K10              | 4         | 3.2%    |
| Zen 3            | 3         | 2.4%    |
| Zen              | 3         | 2.4%    |
| Goldmont plus    | 3         | 2.4%    |
| Silvermont       | 2         | 1.6%    |
| Nehalem          | 2         | 1.6%    |
| Goldmont         | 2         | 1.6%    |
| Excavator        | 2         | 1.6%    |
| Core             | 2         | 1.6%    |
| Puma             | 1         | 0.8%    |
| Piledriver       | 1         | 0.8%    |
| NetBurst         | 1         | 0.8%    |
| K8 Hammer        | 1         | 0.8%    |
| Jaguar           | 1         | 0.8%    |
| CometLake        | 1         | 0.8%    |
| Bulldozer        | 1         | 0.8%    |
| Broadwell        | 1         | 0.8%    |
| Bobcat           | 1         | 0.8%    |
| Alderlake Hybrid | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 69        | 49.29%  |
| AMD               | 41        | 29.29%  |
| Nvidia            | 29        | 20.71%  |
| ASPEED Technology | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 4.26%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 2.84%   |
| Intel HD Graphics 530                                                       | 4         | 2.84%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 2.13%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.13%   |
| AMD Renoir                                                                  | 3         | 2.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 2.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 2.13%   |
| AMD Lucienne                                                                | 3         | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 2.13%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.42%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.42%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.42%   |
| Intel UHD Graphics 620                                                      | 2         | 1.42%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.42%   |
| Intel JasperLake [UHD Graphics]                                             | 2         | 1.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.42%   |
| Intel HD Graphics 630                                                       | 2         | 1.42%   |
| Intel HD Graphics 620                                                       | 2         | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.71%   |
| Nvidia TU117M                                                               | 1         | 0.71%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.71%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.71%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 0.71%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX130]                                               | 1         | 0.71%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 0.71%   |
| Nvidia GK107M [GeForce GT 650M]                                             | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 44.35%  |
| 1 x AMD        | 32        | 25.81%  |
| 1 x Nvidia     | 17        | 13.71%  |
| Intel + Nvidia | 8         | 6.45%   |
| Intel + AMD    | 4         | 3.23%   |
| AMD + Nvidia   | 4         | 3.23%   |
| Other          | 3         | 2.42%   |
| AMD + ASPEED   | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 102       | 82.26%  |
| Proprietary | 16        | 12.9%   |
| Unknown     | 6         | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 87        | 69.6%   |
| 0.51-1.0   | 11        | 8.8%    |
| 0.01-0.5   | 10        | 8%      |
| 1.01-2.0   | 6         | 4.8%    |
| 3.01-4.0   | 5         | 4%      |
| 5.01-6.0   | 3         | 2.4%    |
| 7.01-8.0   | 1         | 0.8%    |
| 2.01-3.0   | 1         | 0.8%    |
| 8.01-16.0  | 1         | 0.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 21        | 15.22%  |
| BOE                     | 13        | 9.42%   |
| Chimei Innolux          | 12        | 8.7%    |
| LG Display              | 9         | 6.52%   |
| Goldstar                | 9         | 6.52%   |
| AU Optronics            | 8         | 5.8%    |
| Dell                    | 7         | 5.07%   |
| Philips                 | 6         | 4.35%   |
| Acer                    | 6         | 4.35%   |
| Apple                   | 5         | 3.62%   |
| Hewlett-Packard         | 4         | 2.9%    |
| BenQ                    | 4         | 2.9%    |
| Lenovo                  | 3         | 2.17%   |
| Iiyama                  | 3         | 2.17%   |
| Chi Mei Optoelectronics | 3         | 2.17%   |
| AOC                     | 3         | 2.17%   |
| Vizio                   | 2         | 1.45%   |
| Sharp                   | 2         | 1.45%   |
| PANDA                   | 2         | 1.45%   |
| Ancor Communications    | 2         | 1.45%   |
| Westinghouse            | 1         | 0.72%   |
| VMO                     | 1         | 0.72%   |
| ViewSonic               | 1         | 0.72%   |
| Unknown                 | 1         | 0.72%   |
| Toshiba                 | 1         | 0.72%   |
| Sony                    | 1         | 0.72%   |
| Sceptre Tech            | 1         | 0.72%   |
| Packard Bell            | 1         | 0.72%   |
| Insignia                | 1         | 0.72%   |
| Hitachi                 | 1         | 0.72%   |
| HannStar                | 1         | 0.72%   |
| Gateway                 | 1         | 0.72%   |
| CS_                     | 1         | 0.72%   |
| ASUSTek Computer        | 1         | 0.72%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.45%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.45%   |
| Apple LCD Monitor APP9CA3 1440x900 330x210mm 15.4-inch                | 2         | 1.45%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                    | 2         | 1.45%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch          | 1         | 0.72%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.72%   |
| Vizio XVT553SV VIZ0063 1920x1080 1210x680mm 54.6-inch                 | 1         | 0.72%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.72%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 0.72%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.72%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 0.72%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.72%   |
| Sharp LCD Monitor SHP1526 1920x1280 274x183mm 13.0-inch               | 1         | 0.72%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.72%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 0.72%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch   | 1         | 0.72%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 0.72%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.72%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch    | 1         | 0.72%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch     | 1         | 0.72%   |
| Samsung Electronics S24E650 SAM0CB9 1920x1080 521x293mm 23.5-inch     | 1         | 0.72%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 0.72%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch     | 1         | 0.72%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.72%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM0D4B 1360x768 609x347mm 27.6-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SAM03D3 1360x768 410x256mm 19.0-inch  | 1         | 0.72%   |
| Samsung Electronics EPSON PJ SECA605 1600x1200                        | 1         | 0.72%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch              | 1         | 0.72%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.72%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 65        | 51.18%  |
| 1366x768 (WXGA)    | 17        | 13.39%  |
| 3840x2160 (4K)     | 6         | 4.72%   |
| 2560x1440 (QHD)    | 6         | 4.72%   |
| 1440x900 (WXGA+)   | 6         | 4.72%   |
| 1680x1050 (WSXGA+) | 4         | 3.15%   |
| 1280x800 (WXGA)    | 4         | 3.15%   |
| 3440x1440          | 3         | 2.36%   |
| 2560x1600          | 3         | 2.36%   |
| 2160x1440          | 2         | 1.57%   |
| 1920x1280          | 2         | 1.57%   |
| 1360x768           | 2         | 1.57%   |
| 1280x1024 (SXGA)   | 2         | 1.57%   |
| 3840x2400          | 1         | 0.79%   |
| 2560x1080          | 1         | 0.79%   |
| 1920x1200 (WUXGA)  | 1         | 0.79%   |
| 1600x900 (HD+)     | 1         | 0.79%   |
| 1280x720 (HD)      | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 28        | 20.59%  |
| 27      | 13        | 9.56%   |
| 24      | 12        | 8.82%   |
| 23      | 12        | 8.82%   |
| 17      | 11        | 8.09%   |
| 21      | 10        | 7.35%   |
| 14      | 10        | 7.35%   |
| 13      | 10        | 7.35%   |
| 31      | 6         | 4.41%   |
| 34      | 4         | 2.94%   |
| 19      | 3         | 2.21%   |
| 12      | 3         | 2.21%   |
| 54      | 2         | 1.47%   |
| 22      | 2         | 1.47%   |
| 18      | 2         | 1.47%   |
| 84      | 1         | 0.74%   |
| 74      | 1         | 0.74%   |
| 40      | 1         | 0.74%   |
| 28      | 1         | 0.74%   |
| 25      | 1         | 0.74%   |
| 16      | 1         | 0.74%   |
| 11      | 1         | 0.74%   |
| Unknown | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 34.07%  |
| 501-600     | 36        | 26.67%  |
| 401-500     | 17        | 12.59%  |
| 201-300     | 10        | 7.41%   |
| 601-700     | 8         | 5.93%   |
| 351-400     | 8         | 5.93%   |
| 701-800     | 4         | 2.96%   |
| 1501-2000   | 2         | 1.48%   |
| 1001-1500   | 2         | 1.48%   |
| 801-900     | 1         | 0.74%   |
| Unknown     | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 88        | 73.33%  |
| 16/10 | 21        | 17.5%   |
| 3/2   | 4         | 3.33%   |
| 21/9  | 4         | 3.33%   |
| 5/4   | 3         | 2.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 29        | 21.64%  |
| 101-110        | 27        | 20.15%  |
| 81-90          | 16        | 11.94%  |
| 301-350        | 13        | 9.7%    |
| 351-500        | 11        | 8.21%   |
| 121-130        | 7         | 5.22%   |
| 151-200        | 5         | 3.73%   |
| 141-150        | 5         | 3.73%   |
| More than 1000 | 4         | 2.99%   |
| 71-80          | 4         | 2.99%   |
| 251-300        | 4         | 2.99%   |
| 61-70          | 3         | 2.24%   |
| 51-60          | 1         | 0.75%   |
| 131-140        | 1         | 0.75%   |
| 111-120        | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |
| 91-100         | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 49        | 37.98%  |
| 101-120       | 33        | 25.58%  |
| 121-160       | 32        | 24.81%  |
| 161-240       | 9         | 6.98%   |
| 1-50          | 4         | 3.1%    |
| More than 240 | 1         | 0.78%   |
| Unknown       | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 99        | 79.2%   |
| 2     | 22        | 17.6%   |
| 0     | 3         | 2.4%    |
| 3     | 1         | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 68        | 38.64%  |
| Intel                             | 65        | 36.93%  |
| Broadcom                          | 10        | 5.68%   |
| Qualcomm Atheros                  | 9         | 5.11%   |
| TP-Link                           | 3         | 1.7%    |
| Ralink                            | 3         | 1.7%    |
| ASIX Electronics                  | 3         | 1.7%    |
| Marvell Technology Group          | 2         | 1.14%   |
| Ericsson Business Mobile Networks | 2         | 1.14%   |
| Broadcom Limited                  | 2         | 1.14%   |
| Raspberry Pi                      | 1         | 0.57%   |
| Quectel Wireless Solutions        | 1         | 0.57%   |
| Qualcomm Atheros Communications   | 1         | 0.57%   |
| Nvidia                            | 1         | 0.57%   |
| NetGear                           | 1         | 0.57%   |
| Microchip Technology              | 1         | 0.57%   |
| MediaTek                          | 1         | 0.57%   |
| AVM                               | 1         | 0.57%   |
| ASUSTek Computer                  | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 20.37%  |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.31%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.39%   |
| Realtek 802.11ac NIC                                              | 3         | 1.39%   |
| Intel Wireless 7265                                               | 3         | 1.39%   |
| Intel Wireless 3165                                               | 3         | 1.39%   |
| Intel Wireless 3160                                               | 3         | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.39%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.93%   |
| Intel Wireless 7260                                               | 2         | 0.93%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 2         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.93%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.93%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.93%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2         | 0.93%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.46%   |
| TP-Link 802.11ac WLAN Adapter                                     | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 48.6%   |
| Realtek Semiconductor           | 28        | 26.17%  |
| Qualcomm Atheros                | 7         | 6.54%   |
| Broadcom                        | 6         | 5.61%   |
| TP-Link                         | 3         | 2.8%    |
| Ralink                          | 3         | 2.8%    |
| Broadcom Limited                | 2         | 1.87%   |
| Quectel Wireless Solutions      | 1         | 0.93%   |
| Qualcomm Atheros Communications | 1         | 0.93%   |
| NetGear                         | 1         | 0.93%   |
| MediaTek                        | 1         | 0.93%   |
| AVM                             | 1         | 0.93%   |
| ASUSTek Computer                | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 6         | 5.61%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 3.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 2.8%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.8%    |
| Realtek 802.11ac NIC                                           | 3         | 2.8%    |
| Intel Wireless 7265                                            | 3         | 2.8%    |
| Intel Wireless 3165                                            | 3         | 2.8%    |
| Intel Wireless 3160                                            | 3         | 2.8%    |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.87%   |
| Intel Wireless 7260                                            | 2         | 1.87%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 1.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.87%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.87%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.93%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.93%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.93%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.93%   |
| Realtek 802.11n                                                | 1         | 0.93%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.93%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.93%   |
| Quectel Wireless Solutions EM12G-ACER                          | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 54        | 52.94%  |
| Intel                    | 32        | 31.37%  |
| Broadcom                 | 6         | 5.88%   |
| Qualcomm Atheros         | 3         | 2.94%   |
| ASIX Electronics         | 3         | 2.94%   |
| Marvell Technology Group | 2         | 1.96%   |
| Nvidia                   | 1         | 0.98%   |
| Microchip Technology     | 1         | 0.98%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 44        | 41.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 5         | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 4.72%   |
| Intel Ethernet Controller I225-V                                               | 4         | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 2.83%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 2.83%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 2.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 2.83%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 1.89%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.89%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.89%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 1.89%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 2         | 1.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.94%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.94%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.94%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.94%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.94%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.94%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 0.94%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.94%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.94%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.94%   |
| Intel 82576 Gigabit Network Connection                                         | 1         | 0.94%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.94%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.94%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.94%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 49.76%  |
| Ethernet | 100       | 48.78%  |
| Modem    | 3         | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 58.33%  |
| Ethernet | 55        | 41.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 66        | 53.23%  |
| 1     | 49        | 39.52%  |
| 3     | 4         | 3.23%   |
| 0     | 4         | 3.23%   |
| 4     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 87        | 69.6%   |
| Yes  | 38        | 30.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 48.78%  |
| Realtek Semiconductor           | 14        | 17.07%  |
| IMC Networks                    | 5         | 6.1%    |
| Cambridge Silicon Radio         | 5         | 6.1%    |
| Broadcom                        | 5         | 6.1%    |
| Apple                           | 5         | 6.1%    |
| Toshiba                         | 1         | 1.22%   |
| Ralink                          | 1         | 1.22%   |
| Qualcomm Atheros Communications | 1         | 1.22%   |
| MediaTek                        | 1         | 1.22%   |
| Integrated System Solution      | 1         | 1.22%   |
| Hewlett-Packard                 | 1         | 1.22%   |
| Foxconn / Hon Hai               | 1         | 1.22%   |
| Belkin Components               | 1         | 1.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 15.85%  |
| Intel AX201 Bluetooth                                                               | 13        | 15.85%  |
| Realtek Bluetooth Radio                                                             | 11        | 13.41%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 4.88%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 3.66%   |
| Intel AX210 Bluetooth                                                               | 3         | 3.66%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.66%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.66%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.44%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.44%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 2         | 2.44%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.44%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.44%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.22%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.22%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.22%   |
| MediaTek Wireless_Device                                                            | 1         | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 1.22%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.22%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.22%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.22%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.22%   |
| Belkin Components F8T013 Bluetooth Adapter                                          | 1         | 1.22%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 88        | 50.29%  |
| AMD                     | 40        | 22.86%  |
| Nvidia                  | 26        | 14.86%  |
| C-Media Electronics     | 6         | 3.43%   |
| ASUSTek Computer        | 3         | 1.71%   |
| Logitech                | 2         | 1.14%   |
| Generalplus Technology  | 2         | 1.14%   |
| Meizu                   | 1         | 0.57%   |
| Kingston Technology     | 1         | 0.57%   |
| JMTek                   | 1         | 0.57%   |
| DSEA A/S                | 1         | 0.57%   |
| Creative Technology     | 1         | 0.57%   |
| Corsair                 | 1         | 0.57%   |
| Cambridge Silicon Radio | 1         | 0.57%   |
| Anlya.cn                | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 7.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 5.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 3.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 3.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 3.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 3.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 2.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.43%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.94%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.46%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.46%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.46%   |
| ASUSTek Computer USB Audio                                                 | 3         | 1.46%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.46%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.97%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.97%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.97%   |
| Generalplus Technology USB Audio Device                                    | 2         | 0.97%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.97%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 21        | 21%     |
| Samsung Electronics | 19        | 19%     |
| Crucial             | 11        | 11%     |
| Micron Technology   | 10        | 10%     |
| Unknown             | 9         | 9%      |
| Kingston            | 9         | 9%      |
| Corsair             | 8         | 8%      |
| Unknown (ABCD)      | 4         | 4%      |
| G.Skill             | 3         | 3%      |
| Nanya Technology    | 2         | 2%      |
| Unifosa             | 1         | 1%      |
| HBS                 | 1         | 1%      |
| A-DATA Technology   | 1         | 1%      |
| Unknown             | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 3.74%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 2.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.87%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 0.93%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.93%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 0.93%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.93%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s          | 1         | 0.93%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.93%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 0.93%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.93%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.93%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 0.93%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s             | 1         | 0.93%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.93%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.93%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s  | 1         | 0.93%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 0.93%   |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.93%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.93%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 52.87%  |
| DDR3    | 29        | 33.33%  |
| LPDDR4  | 7         | 8.05%   |
| DDR2    | 3         | 3.45%   |
| DDR     | 1         | 1.15%   |
| Unknown | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 52        | 57.14%  |
| DIMM         | 29        | 31.87%  |
| Row Of Chips | 9         | 9.89%   |
| Chip         | 1         | 1.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 38        | 39.18%  |
| 4096  | 30        | 30.93%  |
| 16384 | 18        | 18.56%  |
| 2048  | 7         | 7.22%   |
| 32768 | 2         | 2.06%   |
| 1024  | 2         | 2.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 19        | 20.65%  |
| 1600    | 17        | 18.48%  |
| 2667    | 13        | 14.13%  |
| 2400    | 12        | 13.04%  |
| 1333    | 7         | 7.61%   |
| 2133    | 3         | 3.26%   |
| Unknown | 3         | 3.26%   |
| 4267    | 2         | 2.17%   |
| 1334    | 2         | 2.17%   |
| 800     | 2         | 2.17%   |
| 4000    | 1         | 1.09%   |
| 3600    | 1         | 1.09%   |
| 3466    | 1         | 1.09%   |
| 3400    | 1         | 1.09%   |
| 3333    | 1         | 1.09%   |
| 3100    | 1         | 1.09%   |
| 2800    | 1         | 1.09%   |
| 2666    | 1         | 1.09%   |
| 1867    | 1         | 1.09%   |
| 1648    | 1         | 1.09%   |
| 1067    | 1         | 1.09%   |
| 1066    | 1         | 1.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Dymo-CoStar         | 2         | 33.33%  |
| Seiko Epson         | 1         | 16.67%  |
| Samsung Electronics | 1         | 16.67%  |
| Graphtec America    | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series        | 1         | 16.67%  |
| Samsung M2070 Series              | 1         | 16.67%  |
| Graphtec America Graphtec Printer | 1         | 16.67%  |
| Dymo-CoStar LabelWriter 450       | 1         | 16.67%  |
| Dymo-CoStar LabelWriter 310       | 1         | 16.67%  |
| Brother HL-3140CW series          | 1         | 16.67%  |

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
| Chicony Electronics                    | 21        | 28%     |
| Realtek Semiconductor                  | 8         | 10.67%  |
| Logitech                               | 7         | 9.33%   |
| Apple                                  | 5         | 6.67%   |
| Quanta                                 | 4         | 5.33%   |
| Microdia                               | 4         | 5.33%   |
| IMC Networks                           | 4         | 5.33%   |
| Syntek                                 | 3         | 4%      |
| Sunplus Innovation Technology          | 2         | 2.67%   |
| Luxvisions Innotech Limited            | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| ARC International                      | 2         | 2.67%   |
| Acer                                   | 2         | 2.67%   |
| Z-Star Microelectronics                | 1         | 1.33%   |
| U0AS01A-0                              | 1         | 1.33%   |
| Suyin                                  | 1         | 1.33%   |
| Ricoh                                  | 1         | 1.33%   |
| Microsoft                              | 1         | 1.33%   |
| Lite-On Technology                     | 1         | 1.33%   |
| Lenovo                                 | 1         | 1.33%   |
| Generalplus Technology                 | 1         | 1.33%   |
| Alcor Micro                            | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek USB Camera                            | 4         | 5.33%   |
| Syntek Integrated Camera                      | 3         | 4%      |
| Microdia Webcam Vitade AF                     | 3         | 4%      |
| Chicony integrated camera                     | 3         | 4%      |
| Chicony HP HD Camera                          | 3         | 4%      |
| Apple Built-in iSight                         | 3         | 4%      |
| Quanta HD User Facing                         | 2         | 2.67%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.67%   |
| Logitech Webcam C270                          | 2         | 2.67%   |
| IMC Networks USB2.0 HD UVC WebCam             | 2         | 2.67%   |
| Chicony HD User Facing                        | 2         | 2.67%   |
| ARC International Camera                      | 2         | 2.67%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA          | 1         | 1.33%   |
| U0AS01A-0 U0AS01A-0                           | 1         | 1.33%   |
| Suyin USB 2.0 Camera                          | 1         | 1.33%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 1.33%   |
| Sunplus HP Truevision HD                      | 1         | 1.33%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 1.33%   |
| Realtek Laptop_Integrated_Webcam_HD           | 1         | 1.33%   |
| Realtek Integrated_Webcam_HD                  | 1         | 1.33%   |
| Realtek Integrated Webcam HD                  | 1         | 1.33%   |
| Realtek HP 1.0MP High Definition Webcam       | 1         | 1.33%   |
| Quanta ov9734_techfront_camera                | 1         | 1.33%   |
| Quanta HP TrueVision HD Camera                | 1         | 1.33%   |
| Microsoft LifeCam VX-500 [1357]               | 1         | 1.33%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.33%   |
| Logitech Webcam C925e                         | 1         | 1.33%   |
| Logitech StreamCam                            | 1         | 1.33%   |
| Logitech QuickCam E 3500                      | 1         | 1.33%   |
| Logitech HD Webcam C525                       | 1         | 1.33%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.33%   |
| Lite-On HP HD Webcam                          | 1         | 1.33%   |
| Lenovo CNF7237&CNF7238                        | 1         | 1.33%   |
| IMC Networks TOSHIBA Web Camera - HD          | 1         | 1.33%   |
| IMC Networks Integrated Camera                | 1         | 1.33%   |
| Generalplus GENERAL WEBCAM                    | 1         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.33%   |
| Chicony USB2.0 Camera                         | 1         | 1.33%   |
| Chicony USB 2.0 Camera                        | 1         | 1.33%   |
| Chicony TOSHIBA Web Camera - HD               | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 33.33%  |
| Validity Sensors           | 3         | 25%     |
| Synaptics                  | 3         | 25%     |
| Upek                       | 1         | 8.33%   |
| Elan Microelectronics      | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                        | 4         | 33.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 8.33%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 8.33%   |
| Synaptics  WBDI                                            | 1         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 8.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 8.33%   |
| Unknown                                                    | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 50%     |
| Alcor Micro           | 2         | 20%     |
| SCM Microsystems      | 1         | 10%     |
| O2 Micro              | 1         | 10%     |
| Advanced Card Systems | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 20%     |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 10%     |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 72.22%  |
| 1     | 28        | 22.22%  |
| 2     | 5         | 3.97%   |
| 3     | 2         | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 12        | 30%     |
| Chipcard              | 10        | 25%     |
| Net/wireless          | 5         | 12.5%   |
| Graphics card         | 4         | 10%     |
| Camera                | 2         | 5%      |
| Bluetooth             | 2         | 5%      |
| Unassigned class      | 1         | 2.5%    |
| Network               | 1         | 2.5%    |
| Multimedia controller | 1         | 2.5%    |
| Flash memory          | 1         | 2.5%    |
| Card reader           | 1         | 2.5%    |

