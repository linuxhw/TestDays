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

Total: 148

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.15.0-47-generic     | 18        | 15.65%  |
| 5.15.0-48-generic     | 13        | 11.3%   |
| 5.15.0-46-generic     | 11        | 9.57%   |
| 5.15.0-40-generic     | 9         | 7.83%   |
| 5.15.0-25-generic     | 8         | 6.96%   |
| 5.15.0-27-generic     | 7         | 6.09%   |
| 5.15.0-50-generic     | 6         | 5.22%   |
| 5.15.0-52-generic     | 5         | 4.35%   |
| 5.15.0-43-generic     | 5         | 4.35%   |
| 5.15.0-41-generic     | 5         | 4.35%   |
| 5.15.0-30-generic     | 4         | 3.48%   |
| 5.15.0-37-generic     | 3         | 2.61%   |
| 5.15.0-39-generic     | 2         | 1.74%   |
| 5.15.0-35-generic     | 2         | 1.74%   |
| 5.18.0-odroid-arm64   | 1         | 0.87%   |
| 5.18.0-1-generic      | 1         | 0.87%   |
| 5.18.0-051800-generic | 1         | 0.87%   |
| 5.17.1-051701-generic | 1         | 0.87%   |
| 5.17.0-1003-oem       | 1         | 0.87%   |
| 5.15.0-52-lowlatency  | 1         | 0.87%   |
| 5.15.0-46-lowlatency  | 1         | 0.87%   |
| 5.15.0-33-generic     | 1         | 0.87%   |
| 5.15.0-23-generic     | 1         | 0.87%   |
| 5.15.0-22-generic     | 1         | 0.87%   |
| 5.15.0-18-generic     | 1         | 0.87%   |
| 5.15.0-11-generic     | 1         | 0.87%   |
| 5.15.0-1014-raspi     | 1         | 0.87%   |
| 5.15.0-1012-raspi     | 1         | 0.87%   |
| 5.15.0-1011-raspi     | 1         | 0.87%   |
| 5.13.0-52-generic     | 1         | 0.87%   |
| 5.13.0-19-generic     | 1         | 0.87%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 101       | 93.52%  |
| 5.18.0  | 3         | 2.78%   |
| 5.13.0  | 2         | 1.85%   |
| 5.17.1  | 1         | 0.93%   |
| 5.17.0  | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 101       | 93.52%  |
| 5.18    | 3         | 2.78%   |
| 5.17    | 2         | 1.85%   |
| 5.13    | 2         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 105       | 98.13%  |
| aarch64 | 2         | 1.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MATE | 105       | 98.13%  |
| KDE5 | 2         | 1.87%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 104       | 97.2%   |
| Wayland | 3         | 2.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 86        | 78.9%   |
| Unknown | 12        | 11.01%  |
| GDM3    | 10        | 9.17%   |
| SDDM    | 1         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 45        | 42.06%  |
| fr_FR | 11        | 10.28%  |
| it_IT | 10        | 9.35%   |
| de_DE | 9         | 8.41%   |
| ru_RU | 5         | 4.67%   |
| pt_BR | 4         | 3.74%   |
| en_GB | 4         | 3.74%   |
| en_AU | 4         | 3.74%   |
| en_CA | 3         | 2.8%    |
| fi_FI | 2         | 1.87%   |
| de_CH | 2         | 1.87%   |
| zh_CN | 1         | 0.93%   |
| pl_PL | 1         | 0.93%   |
| nl_NL | 1         | 0.93%   |
| hr_HR | 1         | 0.93%   |
| es_PE | 1         | 0.93%   |
| es_ES | 1         | 0.93%   |
| es_AR | 1         | 0.93%   |
| en_IL | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 57        | 50.89%  |
| BIOS | 55        | 49.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 97        | 89.81%  |
| Zfs     | 4         | 3.7%    |
| Overlay | 3         | 2.78%   |
| Btrfs   | 2         | 1.85%   |
| Xfs     | 1         | 0.93%   |
| Jfs     | 1         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 67        | 60.91%  |
| Unknown | 34        | 30.91%  |
| MBR     | 9         | 8.18%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 83.18%  |
| Yes       | 18        | 16.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 60.55%  |
| Yes       | 43        | 39.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 18        | 16.82%  |
| Hewlett-Packard         | 16        | 14.95%  |
| Lenovo                  | 14        | 13.08%  |
| Dell                    | 12        | 11.21%  |
| MSI                     | 9         | 8.41%   |
| Apple                   | 5         | 4.67%   |
| Intel                   | 4         | 3.74%   |
| Gigabyte Technology     | 3         | 2.8%    |
| ASRock                  | 3         | 2.8%    |
| Acer                    | 2         | 1.87%   |
| Unknown                 | 2         | 1.87%   |
| TYAN Computer           | 1         | 0.93%   |
| TrekStor                | 1         | 0.93%   |
| Toshiba                 | 1         | 0.93%   |
| Sony                    | 1         | 0.93%   |
| Raspberry Pi Foundation | 1         | 0.93%   |
| Notebook                | 1         | 0.93%   |
| MicroByte               | 1         | 0.93%   |
| Medion                  | 1         | 0.93%   |
| LincPlus                | 1         | 0.93%   |
| LG Electronics          | 1         | 0.93%   |
| IPASON                  | 1         | 0.93%   |
| HYPERPC                 | 1         | 0.93%   |
| HUAWEI                  | 1         | 0.93%   |
| HONOR                   | 1         | 0.93%   |
| Hardkernel              | 1         | 0.93%   |
| Google                  | 1         | 0.93%   |
| Compaq                  | 1         | 0.93%   |
| Chuwi                   | 1         | 0.93%   |
| AZW                     | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP Compaq Elite 8300 SFF             | 2         | 1.87%   |
| Unknown                              | 2         | 1.87%   |
| TYAN S7012                           | 1         | 0.93%   |
| TrekStor Surfbook A13B               | 1         | 0.93%   |
| Toshiba Satellite C50D-A-133         | 1         | 0.93%   |
| Sony VPCEA36FG                       | 1         | 0.93%   |
| RPi Raspberry Pi 4 Model B Rev 1.4   | 1         | 0.93%   |
| Notebook NJx0MU                      | 1         | 0.93%   |
| MSI p6-2330                          | 1         | 0.93%   |
| MSI MS-7C56                          | 1         | 0.93%   |
| MSI MS-7C09                          | 1         | 0.93%   |
| MSI MS-7C02                          | 1         | 0.93%   |
| MSI MS-7982                          | 1         | 0.93%   |
| MSI MS-7817                          | 1         | 0.93%   |
| MSI MS-7758                          | 1         | 0.93%   |
| MSI MS-7599                          | 1         | 0.93%   |
| MSI B02311                           | 1         | 0.93%   |
| MicroByte ezbook                     | 1         | 0.93%   |
| Medion MS-7797                       | 1         | 0.93%   |
| LincPlus LINNCPLUS P1                | 1         | 0.93%   |
| LG 17Z990-R.AAS8U1                   | 1         | 0.93%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.93%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.93%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.93%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.93%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.93%   |
| Lenovo ThinkCentre M710q 10MQSC0N00  | 1         | 0.93%   |
| Lenovo ThinkCentre M710q 10MQS0FR01  | 1         | 0.93%   |
| Lenovo ThinkBook 16p Gen 2 20YM      | 1         | 0.93%   |
| Lenovo ThinkBook 14 G2 ITL 20VD      | 1         | 0.93%   |
| Lenovo T530-28ICB                    | 1         | 0.93%   |
| Lenovo IdeaPadFlex 6-14IKB 81EM      | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 1         | 0.93%   |
| Lenovo IdeaPad 3 15IIL05 81WE        | 1         | 0.93%   |
| Lenovo IdeaPad 3 15ALC6 82KU         | 1         | 0.93%   |
| IPASON MaxBook P1                    | 1         | 0.93%   |
| Intel NUC8i7HNK                      | 1         | 0.93%   |
| Intel NUC7i5BNK                      | 1         | 0.93%   |
| Intel Kabylake Platform              | 1         | 0.93%   |
| Intel H81U                           | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 4         | 3.74%   |
| Dell Latitude      | 4         | 3.74%   |
| Lenovo IdeaPad     | 3         | 2.8%    |
| HP EliteBook       | 3         | 2.8%    |
| HP Compaq          | 3         | 2.8%    |
| ASUS ROG           | 3         | 2.8%    |
| ASUS PRIME         | 3         | 2.8%    |
| Lenovo ThinkCentre | 2         | 1.87%   |
| Lenovo ThinkBook   | 2         | 1.87%   |
| HP Pavilion        | 2         | 1.87%   |
| HP ENVY            | 2         | 1.87%   |
| Dell XPS           | 2         | 1.87%   |
| Dell Precision     | 2         | 1.87%   |
| Dell OptiPlex      | 2         | 1.87%   |
| Dell Inspiron      | 2         | 1.87%   |
| ASUS VivoBook      | 2         | 1.87%   |
| Acer Aspire        | 2         | 1.87%   |
| Unknown            | 2         | 1.87%   |
| TYAN S7012         | 1         | 0.93%   |
| TrekStor Surfbook  | 1         | 0.93%   |
| Toshiba Satellite  | 1         | 0.93%   |
| Sony VPCEA36FG     | 1         | 0.93%   |
| RPi Raspberry      | 1         | 0.93%   |
| Notebook NJx0MU    | 1         | 0.93%   |
| MSI p6-2330        | 1         | 0.93%   |
| MSI MS-7C56        | 1         | 0.93%   |
| MSI MS-7C09        | 1         | 0.93%   |
| MSI MS-7C02        | 1         | 0.93%   |
| MSI MS-7982        | 1         | 0.93%   |
| MSI MS-7817        | 1         | 0.93%   |
| MSI MS-7758        | 1         | 0.93%   |
| MSI MS-7599        | 1         | 0.93%   |
| MSI B02311         | 1         | 0.93%   |
| MicroByte ezbook   | 1         | 0.93%   |
| Medion MS-7797     | 1         | 0.93%   |
| LincPlus LINNCPLUS | 1         | 0.93%   |
| LG 17Z990-R.AAS8U1 | 1         | 0.93%   |
| Lenovo V15         | 1         | 0.93%   |
| Lenovo T530-28ICB  | 1         | 0.93%   |
| Lenovo IdeaPadFlex | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 19        | 17.76%  |
| 2020    | 10        | 9.35%   |
| 2018    | 10        | 9.35%   |
| 2012    | 10        | 9.35%   |
| 2010    | 8         | 7.48%   |
| 2019    | 7         | 6.54%   |
| 2013    | 7         | 6.54%   |
| 2009    | 6         | 5.61%   |
| 2022    | 5         | 4.67%   |
| 2016    | 4         | 3.74%   |
| 2015    | 4         | 3.74%   |
| 2014    | 4         | 3.74%   |
| 2011    | 4         | 3.74%   |
| 2017    | 3         | 2.8%    |
| 2006    | 2         | 1.87%   |
| Unknown | 2         | 1.87%   |
| 2008    | 1         | 0.93%   |
| 2007    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 49        | 45.79%  |
| Desktop        | 46        | 42.99%  |
| Mini pc        | 3         | 2.8%    |
| System on chip | 2         | 1.87%   |
| Tablet         | 2         | 1.87%   |
| Convertible    | 2         | 1.87%   |
| All in one     | 2         | 1.87%   |
| Server         | 1         | 0.93%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 101       | 91.82%  |
| Enabled  | 9         | 8.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 106       | 99.07%  |
| Yes  | 1         | 0.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 27        | 25.23%  |
| 8.01-16.0   | 21        | 19.63%  |
| 3.01-4.0    | 18        | 16.82%  |
| 16.01-24.0  | 18        | 16.82%  |
| 32.01-64.0  | 16        | 14.95%  |
| 64.01-256.0 | 4         | 3.74%   |
| 24.01-32.0  | 2         | 1.87%   |
| 1.01-2.0    | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 32        | 28.83%  |
| 1.01-2.0  | 28        | 25.23%  |
| 4.01-8.0  | 23        | 20.72%  |
| 3.01-4.0  | 17        | 15.32%  |
| 8.01-16.0 | 6         | 5.41%   |
| 0.51-1.0  | 5         | 4.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 60.75%  |
| 2      | 18        | 16.82%  |
| 3      | 11        | 10.28%  |
| 4      | 6         | 5.61%   |
| 6      | 4         | 3.74%   |
| 5      | 2         | 1.87%   |
| 7      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 64        | 59.81%  |
| Yes       | 43        | 40.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 82.24%  |
| No        | 19        | 17.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 81.31%  |
| No        | 20        | 18.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 63.55%  |
| No        | 39        | 36.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 19        | 17.76%  |
| Italy       | 13        | 12.15%  |
| Germany     | 12        | 11.21%  |
| France      | 10        | 9.35%   |
| Brazil      | 6         | 5.61%   |
| Russia      | 5         | 4.67%   |
| UK          | 4         | 3.74%   |
| Canada      | 4         | 3.74%   |
| Spain       | 3         | 2.8%    |
| Finland     | 3         | 2.8%    |
| Australia   | 3         | 2.8%    |
| Turkey      | 2         | 1.87%   |
| Switzerland | 2         | 1.87%   |
| Portugal    | 2         | 1.87%   |
| Croatia     | 2         | 1.87%   |
| Ukraine     | 1         | 0.93%   |
| Serbia      | 1         | 0.93%   |
| Romania     | 1         | 0.93%   |
| Poland      | 1         | 0.93%   |
| Peru        | 1         | 0.93%   |
| Paraguay    | 1         | 0.93%   |
| Netherlands | 1         | 0.93%   |
| Israel      | 1         | 0.93%   |
| India       | 1         | 0.93%   |
| Hungary     | 1         | 0.93%   |
| Georgia     | 1         | 0.93%   |
| Estonia     | 1         | 0.93%   |
| Colombia    | 1         | 0.93%   |
| China       | 1         | 0.93%   |
| Belgium     | 1         | 0.93%   |
| Austria     | 1         | 0.93%   |
| Argentina   | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Vancouver        | 2         | 1.83%   |
| Turku            | 2         | 1.83%   |
| Paris            | 2         | 1.83%   |
| Melbourne        | 2         | 1.83%   |
| Mannheim         | 2         | 1.83%   |
| Lansdale         | 2         | 1.83%   |
| Berlin           | 2         | 1.83%   |
| Zagreb           | 1         | 0.92%   |
| York             | 1         | 0.92%   |
| Xining           | 1         | 0.92%   |
| Washington       | 1         | 0.92%   |
| Warsaw           | 1         | 0.92%   |
| Villeurbanne     | 1         | 0.92%   |
| Viana do Castelo | 1         | 0.92%   |
| Velyki Mosty     | 1         | 0.92%   |
| Valenciennes     | 1         | 0.92%   |
| Tula             | 1         | 0.92%   |
| Thane            | 1         | 0.92%   |
| Terrace          | 1         | 0.92%   |
| Tel Aviv         | 1         | 0.92%   |
| Taranto          | 1         | 0.92%   |
| Talence          | 1         | 0.92%   |
| Stuttgart        | 1         | 0.92%   |
| St Petersburg    | 1         | 0.92%   |
| Split            | 1         | 0.92%   |
| Southampton      | 1         | 0.92%   |
| Seville          | 1         | 0.92%   |
| Settimo Torinese | 1         | 0.92%   |
| Selargius        | 1         | 0.92%   |
| Seia             | 1         | 0.92%   |
| Sauerlach        | 1         | 0.92%   |
| Sarospatak       | 1         | 0.92%   |
| Sao Paulo        | 1         | 0.92%   |
| Saint-Etienne    | 1         | 0.92%   |
| Rostov-on-Don    | 1         | 0.92%   |
| Porto Alegre     | 1         | 0.92%   |
| Pindamonhangaba  | 1         | 0.92%   |
| Pärnu           | 1         | 0.92%   |
| Palermo          | 1         | 0.92%   |
| Overpelt         | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 45     | 17.47%  |
| WDC                 | 22        | 35     | 13.25%  |
| Seagate             | 16        | 19     | 9.64%   |
| SanDisk             | 12        | 17     | 7.23%   |
| Crucial             | 11        | 11     | 6.63%   |
| Toshiba             | 10        | 11     | 6.02%   |
| Unknown             | 8         | 11     | 4.82%   |
| Phison              | 5         | 5      | 3.01%   |
| Kingston            | 5         | 6      | 3.01%   |
| Hitachi             | 5         | 5      | 3.01%   |
| A-DATA Technology   | 4         | 4      | 2.41%   |
| KingSpec            | 3         | 3      | 1.81%   |
| China               | 3         | 3      | 1.81%   |
| SPCC                | 2         | 2      | 1.2%    |
| SK hynix            | 2         | 2      | 1.2%    |
| Netac               | 2         | 2      | 1.2%    |
| KIOXIA              | 2         | 2      | 1.2%    |
| UMIS                | 1         | 1      | 0.6%    |
| SSSTC               | 1         | 1      | 0.6%    |
| RZX                 | 1         | 1      | 0.6%    |
| NGFF                | 1         | 1      | 0.6%    |
| Micron Technology   | 1         | 1      | 0.6%    |
| Maxtor              | 1         | 1      | 0.6%    |
| LITEONIT            | 1         | 1      | 0.6%    |
| LITEON              | 1         | 1      | 0.6%    |
| Lenovo              | 1         | 1      | 0.6%    |
| Kston               | 1         | 1      | 0.6%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.6%    |
| Kimtigo             | 1         | 1      | 0.6%    |
| KESU                | 1         | 1      | 0.6%    |
| JMicron Technology  | 1         | 1      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| Intel               | 1         | 1      | 0.6%    |
| Hjwdz               | 1         | 1      | 0.6%    |
| HGST                | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| Gigabyte Technology | 1         | 1      | 0.6%    |
| faspeed             | 1         | 1      | 0.6%    |
| DAS                 | 1         | 6      | 0.6%    |
| BAITITON            | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Crucial CT1000BX500SSD1 1TB      | 4         | 2.07%   |
| Seagate ST2000DM001-1ER164 2TB   | 3         | 1.55%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 2         | 1.04%   |
| WDC WD30EFRX-68EUZN0 3TB         | 2         | 1.04%   |
| Toshiba MQ01ABF050 500GB         | 2         | 1.04%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 1.04%   |
| Seagate ST2000DM008-2FR102 2TB   | 2         | 1.04%   |
| SanDisk SSD PLUS 480GB           | 2         | 1.04%   |
| Samsung SSD 980 PRO 1TB          | 2         | 1.04%   |
| Samsung SSD 870 QVO 2TB          | 2         | 1.04%   |
| Samsung SSD 870 QVO 1TB          | 2         | 1.04%   |
| Samsung NVMe SSD Drive 1TB       | 2         | 1.04%   |
| Kingston SA400S37480G 480GB SSD  | 2         | 1.04%   |
| Crucial CT240BX500SSD1 240GB     | 2         | 1.04%   |
| Crucial CT2000MX500SSD1 2TB      | 2         | 1.04%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.52%   |
| WDC WDS100T2B0C 1TB              | 1         | 0.52%   |
| WDC WDBNCE0010PNC 1TB SSD        | 1         | 0.52%   |
| WDC WD800JD-22JNC0 69GB          | 1         | 0.52%   |
| WDC WD8001FZBX-00ASYA0 8TB       | 1         | 0.52%   |
| WDC WD6400AAKS-00E4A0 640GB      | 1         | 0.52%   |
| WDC WD60 EFAX-68JH4N1 6TB        | 1         | 0.52%   |
| WDC WD5000AZLX-75K2TA0 500GB     | 1         | 0.52%   |
| WDC WD5000AAKX-08ERMA0 500GB     | 1         | 0.52%   |
| WDC WD5000AAKX-003CA0 500GB      | 1         | 0.52%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1         | 0.52%   |
| WDC WD40EZRZ-22GXCB0 4TB         | 1         | 0.52%   |
| WDC WD40EFZX-68AWUN0 4TB         | 1         | 0.52%   |
| WDC WD40 PURZ-85TTDY0 4TB        | 1         | 0.52%   |
| WDC WD30EFRX-68N32N0 3TB         | 1         | 0.52%   |
| WDC WD3000HLFS-01G6U0 304GB      | 1         | 0.52%   |
| WDC WD2500AAKX-753CA1 250GB      | 1         | 0.52%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 1         | 0.52%   |
| WDC WD20EADS-00R6B0 2TB          | 1         | 0.52%   |
| WDC WD10EZRZ-00HTKB0 1TB         | 1         | 0.52%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1         | 0.52%   |
| WDC WD10EZEX-75WN4A0 1TB         | 1         | 0.52%   |
| WDC WD10EZEX-60ZF5A0 1TB         | 1         | 0.52%   |
| WDC WD10EZEX-60WN4A0 1TB         | 1         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB         | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 31     | 37.04%  |
| Seagate             | 16        | 19     | 29.63%  |
| Toshiba             | 7         | 7      | 12.96%  |
| Hitachi             | 5         | 5      | 9.26%   |
| Samsung Electronics | 2         | 3      | 3.7%    |
| Maxtor              | 1         | 1      | 1.85%   |
| KESU                | 1         | 1      | 1.85%   |
| HGST                | 1         | 1      | 1.85%   |
| DAS                 | 1         | 6      | 1.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 22.39%  |
| Crucial             | 11        | 11     | 16.42%  |
| SanDisk             | 9         | 12     | 13.43%  |
| Kingston            | 4         | 4      | 5.97%   |
| KingSpec            | 3         | 3      | 4.48%   |
| China               | 3         | 3      | 4.48%   |
| A-DATA Technology   | 3         | 3      | 4.48%   |
| WDC                 | 2         | 2      | 2.99%   |
| SPCC                | 2         | 2      | 2.99%   |
| Unknown             | 1         | 1      | 1.49%   |
| Toshiba             | 1         | 2      | 1.49%   |
| RZX                 | 1         | 1      | 1.49%   |
| NGFF                | 1         | 1      | 1.49%   |
| Netac               | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 1      | 1.49%   |
| LITEON              | 1         | 1      | 1.49%   |
| Kston               | 1         | 1      | 1.49%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.49%   |
| Intenso             | 1         | 1      | 1.49%   |
| GOODRAM             | 1         | 1      | 1.49%   |
| BAITITON            | 1         | 1      | 1.49%   |
| ASMT                | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 53        | 75     | 37.32%  |
| HDD     | 41        | 74     | 28.87%  |
| NVMe    | 39        | 52     | 27.46%  |
| MMC     | 6         | 8      | 4.23%   |
| Unknown | 3         | 4      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 135    | 58.02%  |
| NVMe | 38        | 51     | 29.01%  |
| SAS  | 11        | 19     | 8.4%    |
| MMC  | 6         | 8      | 4.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 86     | 53.51%  |
| 0.51-1.0   | 27        | 32     | 23.68%  |
| 1.01-2.0   | 14        | 16     | 12.28%  |
| 3.01-4.0   | 6         | 7      | 5.26%   |
| 4.01-10.0  | 4         | 4      | 3.51%   |
| 2.01-3.0   | 2         | 4      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 31        | 28.44%  |
| 251-500        | 23        | 21.1%   |
| 501-1000       | 14        | 12.84%  |
| More than 3000 | 11        | 10.09%  |
| 1001-2000      | 10        | 9.17%   |
| 51-100         | 6         | 5.5%    |
| 21-50          | 5         | 4.59%   |
| 1-20           | 5         | 4.59%   |
| 2001-3000      | 3         | 2.75%   |
| Unknown        | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 25.69%  |
| 21-50          | 17        | 15.6%   |
| 101-250        | 16        | 14.68%  |
| 51-100         | 16        | 14.68%  |
| 501-1000       | 10        | 9.17%   |
| More than 3000 | 7         | 6.42%   |
| 251-500        | 6         | 5.5%    |
| 1001-2000      | 6         | 5.5%    |
| 2001-3000      | 2         | 1.83%   |
| Unknown        | 1         | 0.92%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 2         | 2      | 20%     |
| WDC WD1001FALS-40Y6A0 1TB           | 1         | 1      | 10%     |
| Seagate ST2000DM001-1ER164 2TB      | 1         | 1      | 10%     |
| Samsung Electronics SSD 960 PRO 1TB | 1         | 1      | 10%     |
| NGFF 2280 256GB SSD                 | 1         | 1      | 10%     |
| Netac SSD 256GB                     | 1         | 1      | 10%     |
| Hitachi HTS721080G9SA00 80GB        | 1         | 1      | 10%     |
| DAS TerraMaster 500GB               | 1         | 3      | 10%     |
| China SSD 180GB                     | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 30%     |
| WDC                 | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| NGFF                | 1         | 1      | 10%     |
| Netac               | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| DAS                 | 1         | 3      | 10%     |
| China               | 1         | 1      | 10%     |

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
| HDD  | 5         | 8      | 55.56%  |
| SSD  | 3         | 3      | 33.33%  |
| NVMe | 1         | 1      | 11.11%  |

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
| Works    | 66        | 108    | 54.1%   |
| Detected | 47        | 93     | 38.52%  |
| Malfunc  | 9         | 12     | 7.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 72        | 51.8%   |
| AMD                            | 21        | 15.11%  |
| Samsung Electronics            | 15        | 10.79%  |
| Phison Electronics             | 6         | 4.32%   |
| SanDisk                        | 5         | 3.6%    |
| Toshiba America Info Systems   | 3         | 2.16%   |
| ASMedia Technology             | 3         | 2.16%   |
| SK hynix                       | 2         | 1.44%   |
| Silicon Motion                 | 2         | 1.44%   |
| KIOXIA                         | 2         | 1.44%   |
| Kingston Technology Company    | 2         | 1.44%   |
| Union Memory (Shenzhen)        | 1         | 0.72%   |
| Solid State Storage Technology | 1         | 0.72%   |
| Nvidia                         | 1         | 0.72%   |
| Marvell Technology Group       | 1         | 0.72%   |
| Lenovo                         | 1         | 0.72%   |
| ADATA Technology               | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 7.41%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 3.09%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 3.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 2.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 4         | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 2.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.47%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.85%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.85%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.85%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 3         | 1.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.23%   |
| Phison NVMe Storage Controller                                                 | 2         | 1.23%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 1.23%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.23%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 1.23%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 2         | 1.23%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.23%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.23%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.62%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.62%   |
| Toshiba America Info Systems Toshiba America Info SATA controller              | 1         | 0.62%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.62%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 80        | 55.94%  |
| NVMe | 38        | 26.57%  |
| IDE  | 13        | 9.09%   |
| RAID | 12        | 8.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 75.7%   |
| AMD    | 24        | 22.43%  |
| ARM    | 2         | 1.87%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-3517U CPU @ 1.90GHz           | 3         | 2.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.87%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 2         | 1.87%   |
| Intel 11th Gen Core i5-11600K @ 3.90GHz     | 2         | 1.87%   |
| ARM Processor                               | 2         | 1.87%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.87%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2         | 1.87%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.93%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz         | 1         | 0.93%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.93%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.93%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1         | 0.93%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 0.93%   |
| Intel Pentium 4 CPU 3.06GHz                 | 1         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.93%   |
| Intel Core i7-8705G CPU @ 3.10GHz           | 1         | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.93%   |
| Intel Core i7-7700T CPU @ 2.90GHz           | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.93%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.93%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1         | 0.93%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.93%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.93%   |
| Intel Core i7 CPU X 920 @ 2.00GHz           | 1         | 0.93%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 1         | 0.93%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1         | 0.93%   |
| Intel Core i5-7400T CPU @ 2.40GHz           | 1         | 0.93%   |
| Intel Core i5-7260U CPU @ 2.20GHz           | 1         | 0.93%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 1         | 0.93%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 1         | 0.93%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.93%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.93%   |
| Intel Core i5-4300Y CPU @ 1.60GHz           | 1         | 0.93%   |
| Intel Core i5-4250U CPU @ 1.30GHz           | 1         | 0.93%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 23        | 21.5%   |
| Intel Core i7        | 18        | 16.82%  |
| Other                | 16        | 14.95%  |
| Intel Core i3        | 7         | 6.54%   |
| AMD Ryzen 5          | 7         | 6.54%   |
| Intel Celeron        | 6         | 5.61%   |
| Intel Core 2 Duo     | 5         | 4.67%   |
| Intel Pentium        | 4         | 3.74%   |
| Intel Xeon           | 2         | 1.87%   |
| AMD Ryzen 9          | 2         | 1.87%   |
| AMD Ryzen 7          | 2         | 1.87%   |
| AMD Ryzen 3          | 2         | 1.87%   |
| Intel Pentium 4      | 1         | 0.93%   |
| Intel Core 2 Quad    | 1         | 0.93%   |
| AMD Turion 64 Mobile | 1         | 0.93%   |
| AMD Ryzen 7 PRO      | 1         | 0.93%   |
| AMD Phenom II X6     | 1         | 0.93%   |
| AMD FX               | 1         | 0.93%   |
| AMD E1               | 1         | 0.93%   |
| AMD E                | 1         | 0.93%   |
| AMD Athlon II X4     | 1         | 0.93%   |
| AMD Athlon II X2     | 1         | 0.93%   |
| AMD A8               | 1         | 0.93%   |
| AMD A6               | 1         | 0.93%   |
| AMD A4               | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 48        | 44.86%  |
| 2       | 35        | 32.71%  |
| 6       | 10        | 9.35%   |
| 8       | 7         | 6.54%   |
| 1       | 3         | 2.8%    |
| 12      | 2         | 1.87%   |
| 10      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 105       | 98.13%  |
| 2       | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 66        | 61.68%  |
| 1       | 40        | 37.38%  |
| Unknown | 1         | 0.93%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 107       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 39.09%  |
| 0x306a9    | 7         | 6.36%   |
| 0x806c1    | 5         | 4.55%   |
| 0x806d1    | 3         | 2.73%   |
| 0x506e3    | 3         | 2.73%   |
| 0x20655    | 3         | 2.73%   |
| 0x08108109 | 3         | 2.73%   |
| 0xa0671    | 2         | 1.82%   |
| 0x906ea    | 2         | 1.82%   |
| 0x906e9    | 2         | 1.82%   |
| 0x806ea    | 2         | 1.82%   |
| 0x706e5    | 2         | 1.82%   |
| 0x706a8    | 2         | 1.82%   |
| 0x506c9    | 2         | 1.82%   |
| 0x306c3    | 2         | 1.82%   |
| 0x206a7    | 2         | 1.82%   |
| 0x1067a    | 2         | 1.82%   |
| 0x0a50000c | 2         | 1.82%   |
| 0xa0653    | 1         | 0.91%   |
| 0x906ed    | 1         | 0.91%   |
| 0x906c0    | 1         | 0.91%   |
| 0x90672    | 1         | 0.91%   |
| 0x806ec    | 1         | 0.91%   |
| 0x806eb    | 1         | 0.91%   |
| 0x806e9    | 1         | 0.91%   |
| 0x6fd      | 1         | 0.91%   |
| 0x40651    | 1         | 0.91%   |
| 0x306f2    | 1         | 0.91%   |
| 0x206c2    | 1         | 0.91%   |
| 0x106e5    | 1         | 0.91%   |
| 0x10677    | 1         | 0.91%   |
| 0x08608103 | 1         | 0.91%   |
| 0x08101016 | 1         | 0.91%   |
| 0x07030105 | 1         | 0.91%   |
| 0x0700010f | 1         | 0.91%   |
| 0x06001119 | 1         | 0.91%   |
| 0x05000119 | 1         | 0.91%   |
| 0x010000dc | 1         | 0.91%   |
| 0x010000c7 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 12.04%  |
| IvyBridge        | 12        | 11.11%  |
| Haswell          | 8         | 7.41%   |
| TigerLake        | 7         | 6.48%   |
| Icelake          | 7         | 6.48%   |
| Westmere         | 6         | 5.56%   |
| Unknown          | 6         | 5.56%   |
| Skylake          | 5         | 4.63%   |
| Penryn           | 5         | 4.63%   |
| Zen+             | 4         | 3.7%    |
| Zen 3            | 3         | 2.78%   |
| Zen 2            | 3         | 2.78%   |
| Zen              | 3         | 2.78%   |
| K10              | 3         | 2.78%   |
| Goldmont plus    | 3         | 2.78%   |
| Silvermont       | 2         | 1.85%   |
| SandyBridge      | 2         | 1.85%   |
| Nehalem          | 2         | 1.85%   |
| Goldmont         | 2         | 1.85%   |
| Puma             | 1         | 0.93%   |
| Piledriver       | 1         | 0.93%   |
| NetBurst         | 1         | 0.93%   |
| K8 Hammer        | 1         | 0.93%   |
| Jaguar           | 1         | 0.93%   |
| Excavator        | 1         | 0.93%   |
| Core             | 1         | 0.93%   |
| CometLake        | 1         | 0.93%   |
| Bulldozer        | 1         | 0.93%   |
| Broadwell        | 1         | 0.93%   |
| Bobcat           | 1         | 0.93%   |
| Alderlake Hybrid | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 59        | 49.17%  |
| AMD               | 34        | 28.33%  |
| Nvidia            | 26        | 21.67%  |
| ASPEED Technology | 1         | 0.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 5%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 4.17%   |
| Intel HD Graphics 530                                                       | 4         | 3.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2.5%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 2.5%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 2.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3         | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 2.5%    |
| AMD Cezanne                                                                 | 3         | 2.5%    |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 1.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.67%   |
| Intel UHD Graphics 620                                                      | 2         | 1.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 1.67%   |
| Intel HD Graphics 630                                                       | 2         | 1.67%   |
| Intel HD Graphics 620                                                       | 2         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.67%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 1         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.83%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.83%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 0.83%   |
| Nvidia GM206GL [Quadro M2000]                                               | 1         | 0.83%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 1         | 0.83%   |
| Nvidia GK107M [GeForce GT 650M]                                             | 1         | 0.83%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                 | 1         | 0.83%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 0.83%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 1         | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.83%   |
| Nvidia GF108M [GeForce GT 635M]                                             | 1         | 0.83%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1         | 0.83%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                    | 1         | 0.83%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                          | 1         | 0.83%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1         | 0.83%   |
| Nvidia G92GLM [Quadro FX 2800M]                                             | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 44.86%  |
| 1 x AMD        | 27        | 25.23%  |
| 1 x Nvidia     | 17        | 15.89%  |
| Intel + Nvidia | 6         | 5.61%   |
| Intel + AMD    | 3         | 2.8%    |
| AMD + Nvidia   | 3         | 2.8%    |
| Other          | 2         | 1.87%   |
| AMD + ASPEED   | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 88        | 82.24%  |
| Proprietary | 15        | 14.02%  |
| Unknown     | 4         | 3.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 73        | 67.59%  |
| 0.51-1.0   | 10        | 9.26%   |
| 0.01-0.5   | 8         | 7.41%   |
| 1.01-2.0   | 6         | 5.56%   |
| 3.01-4.0   | 5         | 4.63%   |
| 5.01-6.0   | 3         | 2.78%   |
| 7.01-8.0   | 1         | 0.93%   |
| 2.01-3.0   | 1         | 0.93%   |
| 8.01-16.0  | 1         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 15%     |
| Chimei Innolux          | 11        | 9.17%   |
| BOE                     | 10        | 8.33%   |
| Goldstar                | 8         | 6.67%   |
| Philips                 | 6         | 5%      |
| LG Display              | 6         | 5%      |
| Dell                    | 6         | 5%      |
| Acer                    | 6         | 5%      |
| AU Optronics            | 5         | 4.17%   |
| Apple                   | 5         | 4.17%   |
| Hewlett-Packard         | 4         | 3.33%   |
| BenQ                    | 4         | 3.33%   |
| Lenovo                  | 3         | 2.5%    |
| Iiyama                  | 3         | 2.5%    |
| AOC                     | 3         | 2.5%    |
| Vizio                   | 2         | 1.67%   |
| Sharp                   | 2         | 1.67%   |
| Chi Mei Optoelectronics | 2         | 1.67%   |
| Ancor Communications    | 2         | 1.67%   |
| Westinghouse            | 1         | 0.83%   |
| VMO                     | 1         | 0.83%   |
| ViewSonic               | 1         | 0.83%   |
| Toshiba                 | 1         | 0.83%   |
| Sony                    | 1         | 0.83%   |
| Sceptre Tech            | 1         | 0.83%   |
| PANDA                   | 1         | 0.83%   |
| Packard Bell            | 1         | 0.83%   |
| Insignia                | 1         | 0.83%   |
| Hitachi                 | 1         | 0.83%   |
| HannStar                | 1         | 0.83%   |
| Gateway                 | 1         | 0.83%   |
| CS_                     | 1         | 0.83%   |
| ASUSTek Computer        | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.67%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 1.67%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 1.67%   |
| Acer ET322QU ACR0687 2560x1440 698x393mm 31.5-inch                    | 2         | 1.67%   |
| Westinghouse DWM40F1D1 WDT7811 1920x1080 890x500mm 40.2-inch          | 1         | 0.83%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch             | 1         | 0.83%   |
| Vizio XVT553SV VIZ0063 1920x1080 1210x680mm 54.6-inch                 | 1         | 0.83%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                   | 1         | 0.83%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 0.83%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 0.83%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.83%   |
| Sharp LCD Monitor SHP1526 1920x1280 274x183mm 13.0-inch               | 1         | 0.83%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.83%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.83%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch   | 1         | 0.83%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 1         | 0.83%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 480x270mm 21.7-inch    | 1         | 0.83%   |
| Samsung Electronics S32F351 SAM0D24 1920x1080 698x393mm 31.5-inch     | 1         | 0.83%   |
| Samsung Electronics S24E650 SAM0CB9 1920x1080 521x293mm 23.5-inch     | 1         | 0.83%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 1         | 0.83%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch     | 1         | 0.83%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.83%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SAM0D4B 1360x768 609x347mm 27.6-inch  | 1         | 0.83%   |
| Samsung Electronics EPSON PJ SECA605 1600x1200                        | 1         | 0.83%   |
| Philips PHL 345B1C PHL093D 3440x1440 797x334mm 34.0-inch              | 1         | 0.83%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch               | 1         | 0.83%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 1         | 0.83%   |
| Philips PHL 242E2F PHLC238 1920x1080 527x296mm 23.8-inch              | 1         | 0.83%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 0.83%   |
| Philips 246EL2SBH PHLC074 1920x1080 521x293mm 23.5-inch               | 1         | 0.83%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.83%   |
| Packard Bell Viseo223DX PKB037A 1920x1080 477x268mm 21.5-inch         | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 48.65%  |
| 1366x768 (WXGA)    | 14        | 12.61%  |
| 3840x2160 (4K)     | 6         | 5.41%   |
| 2560x1440 (QHD)    | 6         | 5.41%   |
| 1440x900 (WXGA+)   | 5         | 4.5%    |
| 1680x1050 (WSXGA+) | 4         | 3.6%    |
| 1280x800 (WXGA)    | 4         | 3.6%    |
| 3440x1440          | 3         | 2.7%    |
| 2560x1600          | 3         | 2.7%    |
| 2160x1440          | 2         | 1.8%    |
| 1920x1280          | 2         | 1.8%    |
| 1280x1024 (SXGA)   | 2         | 1.8%    |
| 3840x2400          | 1         | 0.9%    |
| 2560x1080          | 1         | 0.9%    |
| 1920x1200 (WUXGA)  | 1         | 0.9%    |
| 1600x900 (HD+)     | 1         | 0.9%    |
| 1360x768           | 1         | 0.9%    |
| 1280x720 (HD)      | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 22        | 18.64%  |
| 27      | 12        | 10.17%  |
| 23      | 12        | 10.17%  |
| 24      | 11        | 9.32%   |
| 17      | 10        | 8.47%   |
| 13      | 10        | 8.47%   |
| 21      | 9         | 7.63%   |
| 31      | 6         | 5.08%   |
| 14      | 5         | 4.24%   |
| 34      | 4         | 3.39%   |
| 12      | 3         | 2.54%   |
| 22      | 2         | 1.69%   |
| 19      | 2         | 1.69%   |
| 84      | 1         | 0.85%   |
| 74      | 1         | 0.85%   |
| 54      | 1         | 0.85%   |
| 40      | 1         | 0.85%   |
| 28      | 1         | 0.85%   |
| 25      | 1         | 0.85%   |
| 18      | 1         | 0.85%   |
| 16      | 1         | 0.85%   |
| 11      | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 29.91%  |
| 501-600     | 34        | 29.06%  |
| 401-500     | 14        | 11.97%  |
| 201-300     | 10        | 8.55%   |
| 601-700     | 8         | 6.84%   |
| 351-400     | 7         | 5.98%   |
| 701-800     | 4         | 3.42%   |
| 1501-2000   | 2         | 1.71%   |
| 801-900     | 1         | 0.85%   |
| 1001-1500   | 1         | 0.85%   |
| Unknown     | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 75        | 71.43%  |
| 16/10 | 19        | 18.1%   |
| 3/2   | 4         | 3.81%   |
| 21/9  | 4         | 3.81%   |
| 5/4   | 3         | 2.86%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 27        | 23.28%  |
| 101-110        | 21        | 18.1%   |
| 301-350        | 12        | 10.34%  |
| 81-90          | 11        | 9.48%   |
| 351-500        | 11        | 9.48%   |
| 121-130        | 6         | 5.17%   |
| 71-80          | 4         | 3.45%   |
| 251-300        | 4         | 3.45%   |
| 151-200        | 4         | 3.45%   |
| 141-150        | 4         | 3.45%   |
| More than 1000 | 3         | 2.59%   |
| 61-70          | 3         | 2.59%   |
| 51-60          | 1         | 0.86%   |
| 131-140        | 1         | 0.86%   |
| 111-120        | 1         | 0.86%   |
| 501-1000       | 1         | 0.86%   |
| 91-100         | 1         | 0.86%   |
| Unknown        | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 45        | 40.54%  |
| 101-120       | 28        | 25.23%  |
| 121-160       | 24        | 21.62%  |
| 161-240       | 9         | 8.11%   |
| 1-50          | 3         | 2.7%    |
| More than 240 | 1         | 0.9%    |
| Unknown       | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 86        | 79.63%  |
| 2     | 19        | 17.59%  |
| 0     | 2         | 1.85%   |
| 3     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 58        | 38.16%  |
| Intel                             | 55        | 36.18%  |
| Broadcom                          | 9         | 5.92%   |
| Qualcomm Atheros                  | 8         | 5.26%   |
| Ralink                            | 3         | 1.97%   |
| ASIX Electronics                  | 3         | 1.97%   |
| TP-Link                           | 2         | 1.32%   |
| Marvell Technology Group          | 2         | 1.32%   |
| Ericsson Business Mobile Networks | 2         | 1.32%   |
| Broadcom Limited                  | 2         | 1.32%   |
| Raspberry Pi                      | 1         | 0.66%   |
| Qualcomm Atheros Communications   | 1         | 0.66%   |
| Nvidia                            | 1         | 0.66%   |
| NetGear                           | 1         | 0.66%   |
| Microchip Technology              | 1         | 0.66%   |
| MediaTek                          | 1         | 0.66%   |
| AVM                               | 1         | 0.66%   |
| ASUSTek Computer                  | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 38        | 20.32%  |
| Intel Wireless 8265 / 8275                                        | 5         | 2.67%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 2.14%   |
| Intel Ethernet Controller I225-V                                  | 4         | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.6%    |
| Intel Wireless 3165                                               | 3         | 1.6%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.07%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.07%   |
| Realtek 802.11ac NIC                                              | 2         | 1.07%   |
| Intel Wireless 7265                                               | 2         | 1.07%   |
| Intel Wireless 3160                                               | 2         | 1.07%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 1.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.07%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.07%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.07%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.07%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.07%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.53%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.53%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                            | 1         | 0.53%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.53%   |
| Raspberry Pi Pico                                                 | 1         | 0.53%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 47.78%  |
| Realtek Semiconductor           | 23        | 25.56%  |
| Qualcomm Atheros                | 6         | 6.67%   |
| Broadcom                        | 6         | 6.67%   |
| Ralink                          | 3         | 3.33%   |
| TP-Link                         | 2         | 2.22%   |
| Broadcom Limited                | 2         | 2.22%   |
| Qualcomm Atheros Communications | 1         | 1.11%   |
| NetGear                         | 1         | 1.11%   |
| MediaTek                        | 1         | 1.11%   |
| AVM                             | 1         | 1.11%   |
| ASUSTek Computer                | 1         | 1.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 5         | 5.56%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 5.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 4.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 3.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 3.33%   |
| Intel Wireless 3165                                                     | 3         | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.22%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 2.22%   |
| Realtek 802.11ac NIC                                                    | 2         | 2.22%   |
| Intel Wireless 7265                                                     | 2         | 2.22%   |
| Intel Wireless 3160                                                     | 2         | 2.22%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.22%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 2.22%   |
| TP-Link Archer T4U ver.3                                                | 1         | 1.11%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 1.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.11%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 1.11%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                  | 1         | 1.11%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 1.11%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.11%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 1.11%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.11%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.11%   |
| NetGear A6150                                                           | 1         | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.11%   |
| Intel Wireless 8260                                                     | 1         | 1.11%   |
| Intel Wireless 7260                                                     | 1         | 1.11%   |
| Intel WiFi Link 5100                                                    | 1         | 1.11%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 47        | 52.22%  |
| Intel                    | 28        | 31.11%  |
| Broadcom                 | 5         | 5.56%   |
| Qualcomm Atheros         | 3         | 3.33%   |
| ASIX Electronics         | 3         | 3.33%   |
| Marvell Technology Group | 2         | 2.22%   |
| Nvidia                   | 1         | 1.11%   |
| Microchip Technology     | 1         | 1.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 38        | 40.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4         | 4.26%   |
| Intel Ethernet Controller I225-V                                               | 4         | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 4.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 3.19%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 3.19%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 3.19%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 3.19%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 2.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 2.13%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 2.13%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 2.13%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.06%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.06%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 1.06%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.06%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 1.06%   |
| Intel I211 Gigabit Network Connection                                          | 1         | 1.06%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.06%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 1.06%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 1.06%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 1.06%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.06%   |
| Intel 82576 Gigabit Network Connection                                         | 1         | 1.06%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.06%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.06%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 1.06%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 1         | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 88        | 49.44%  |
| WiFi     | 87        | 48.88%  |
| Modem    | 3         | 1.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 64        | 55.17%  |
| Ethernet | 52        | 44.83%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 55        | 51.4%   |
| 1     | 45        | 42.06%  |
| 3     | 4         | 3.74%   |
| 0     | 2         | 1.87%   |
| 4     | 1         | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 67.59%  |
| Yes  | 35        | 32.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 49.28%  |
| Realtek Semiconductor           | 11        | 15.94%  |
| Broadcom                        | 5         | 7.25%   |
| Apple                           | 5         | 7.25%   |
| IMC Networks                    | 3         | 4.35%   |
| Cambridge Silicon Radio         | 3         | 4.35%   |
| Toshiba                         | 1         | 1.45%   |
| Ralink                          | 1         | 1.45%   |
| Qualcomm Atheros Communications | 1         | 1.45%   |
| MediaTek                        | 1         | 1.45%   |
| Integrated System Solution      | 1         | 1.45%   |
| Hewlett-Packard                 | 1         | 1.45%   |
| Foxconn / Hon Hai               | 1         | 1.45%   |
| Belkin Components               | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 12        | 17.39%  |
| Intel AX201 Bluetooth                                                               | 10        | 14.49%  |
| Realtek Bluetooth Radio                                                             | 7         | 10.14%  |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 4.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.35%   |
| Intel AX210 Bluetooth                                                               | 3         | 4.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.9%    |
| Intel AX200 Bluetooth                                                               | 2         | 2.9%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.9%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 2         | 2.9%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.9%    |
| Apple Bluetooth Host Controller                                                     | 2         | 2.9%    |
| Toshiba Bluetooth Device                                                            | 1         | 1.45%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.45%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.45%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.45%   |
| MediaTek Wireless_Device                                                            | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.45%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 1.45%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.45%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.45%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.45%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 1.45%   |
| Belkin Components F8T013 Bluetooth Adapter                                          | 1         | 1.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 78        | 50%     |
| AMD                     | 34        | 21.79%  |
| Nvidia                  | 24        | 15.38%  |
| C-Media Electronics     | 6         | 3.85%   |
| ASUSTek Computer        | 3         | 1.92%   |
| Logitech                | 2         | 1.28%   |
| Generalplus Technology  | 2         | 1.28%   |
| Meizu                   | 1         | 0.64%   |
| Kingston Technology     | 1         | 0.64%   |
| JMTek                   | 1         | 0.64%   |
| Creative Technology     | 1         | 0.64%   |
| Corsair                 | 1         | 0.64%   |
| Cambridge Silicon Radio | 1         | 0.64%   |
| Unknown                 | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 6.74%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 6.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 3.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 3.93%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 2.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4         | 2.25%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.25%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.69%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.69%   |
| ASUSTek Computer USB Audio                                                 | 3         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.69%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.69%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.12%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.12%   |
| Generalplus Technology USB Audio Device                                    | 2         | 1.12%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.56%   |
| Nvidia stereo controller                                                   | 1         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 18        | 20.45%  |
| Samsung Electronics | 14        | 15.91%  |
| Unknown             | 9         | 10.23%  |
| Kingston            | 9         | 10.23%  |
| Crucial             | 9         | 10.23%  |
| Micron Technology   | 8         | 9.09%   |
| Corsair             | 8         | 9.09%   |
| Unknown (ABCD)      | 4         | 4.55%   |
| G.Skill             | 3         | 3.41%   |
| Nanya Technology    | 2         | 2.27%   |
| Unifosa             | 1         | 1.14%   |
| HBS                 | 1         | 1.14%   |
| A-DATA Technology   | 1         | 1.14%   |
| Unknown             | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 4.26%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 3.19%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.13%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR2 800MT/s                         | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 1.06%   |
| Unknown RAM Module 4GB DIMM                                      | 1         | 1.06%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.06%   |
| Unknown RAM Module 2GB DIMM DDR 1333MT/s                         | 1         | 1.06%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.06%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| Unknown RAM DDR4 NB 16G 2666 16384MB SODIMM DDR4 2667MT/s        | 1         | 1.06%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 1.06%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.06%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 1.06%   |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s              | 1         | 1.06%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT325U6EFR8C-PB 2GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 1         | 1.06%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.06%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 1         | 1.06%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 1         | 1.06%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |
| Samsung RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 1.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.06%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.06%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 40        | 53.33%  |
| DDR3    | 23        | 30.67%  |
| LPDDR4  | 7         | 9.33%   |
| DDR2    | 3         | 4%      |
| DDR     | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 53.16%  |
| DIMM         | 27        | 34.18%  |
| Row Of Chips | 9         | 11.39%  |
| Chip         | 1         | 1.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 29        | 34.12%  |
| 4096  | 28        | 32.94%  |
| 16384 | 17        | 20%     |
| 2048  | 7         | 8.24%   |
| 32768 | 2         | 2.35%   |
| 1024  | 2         | 2.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 15        | 18.75%  |
| 2667    | 13        | 16.25%  |
| 1600    | 13        | 16.25%  |
| 2400    | 11        | 13.75%  |
| 1333    | 7         | 8.75%   |
| 2133    | 3         | 3.75%   |
| Unknown | 3         | 3.75%   |
| 4267    | 2         | 2.5%    |
| 800     | 2         | 2.5%    |
| 4000    | 1         | 1.25%   |
| 3600    | 1         | 1.25%   |
| 3466    | 1         | 1.25%   |
| 3400    | 1         | 1.25%   |
| 3333    | 1         | 1.25%   |
| 3100    | 1         | 1.25%   |
| 2666    | 1         | 1.25%   |
| 1867    | 1         | 1.25%   |
| 1334    | 1         | 1.25%   |
| 1067    | 1         | 1.25%   |
| 1066    | 1         | 1.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Dymo-CoStar        | 2         | 40%     |
| Seiko Epson        | 1         | 20%     |
| Graphtec America   | 1         | 20%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series        | 1         | 20%     |
| Graphtec America Graphtec Printer | 1         | 20%     |
| Dymo-CoStar LabelWriter 450       | 1         | 20%     |
| Dymo-CoStar LabelWriter 310       | 1         | 20%     |
| Brother HL-3140CW series          | 1         | 20%     |

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
| Chicony Electronics                    | 14        | 22.58%  |
| Realtek Semiconductor                  | 7         | 11.29%  |
| Logitech                               | 7         | 11.29%  |
| Apple                                  | 5         | 8.06%   |
| Microdia                               | 4         | 6.45%   |
| Syntek                                 | 3         | 4.84%   |
| Sunplus Innovation Technology          | 2         | 3.23%   |
| Quanta                                 | 2         | 3.23%   |
| Luxvisions Innotech Limited            | 2         | 3.23%   |
| IMC Networks                           | 2         | 3.23%   |
| ARC International                      | 2         | 3.23%   |
| Acer                                   | 2         | 3.23%   |
| Z-Star Microelectronics                | 1         | 1.61%   |
| U0AS01A-0                              | 1         | 1.61%   |
| Suyin                                  | 1         | 1.61%   |
| Ricoh                                  | 1         | 1.61%   |
| Microsoft                              | 1         | 1.61%   |
| Lite-On Technology                     | 1         | 1.61%   |
| Lenovo                                 | 1         | 1.61%   |
| Generalplus Technology                 | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.61%   |
| Alcor Micro                            | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Syntek Integrated Camera                      | 3         | 4.84%   |
| Microdia Webcam Vitade AF                     | 3         | 4.84%   |
| Apple Built-in iSight                         | 3         | 4.84%   |
| Realtek MTD camera                            | 2         | 3.23%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 3.23%   |
| Logitech Webcam C270                          | 2         | 3.23%   |
| Chicony Integrated Camera                     | 2         | 3.23%   |
| ARC International Camera                      | 2         | 3.23%   |
| Z-Star HP 3-MegaPixel Webcam GX607AA          | 1         | 1.61%   |
| U0AS01A-0 U0AS01A-0                           | 1         | 1.61%   |
| Suyin USB 2.0 Camera                          | 1         | 1.61%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 1.61%   |
| Sunplus HP Truevision HD                      | 1         | 1.61%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 1.61%   |
| Realtek USB Camera                            | 1         | 1.61%   |
| Realtek Laptop_Integrated_Webcam_HD           | 1         | 1.61%   |
| Realtek Integrated_Webcam_HD                  | 1         | 1.61%   |
| Realtek Integrated Webcam HD                  | 1         | 1.61%   |
| Realtek HP 1.0MP High Definition Webcam       | 1         | 1.61%   |
| Quanta ov9734_techfront_camera                | 1         | 1.61%   |
| Quanta HD User Facing                         | 1         | 1.61%   |
| Microsoft LifeCam VX-500 [1357]               | 1         | 1.61%   |
| Microdia Integrated_Webcam_2M                 | 1         | 1.61%   |
| Logitech Webcam C925e                         | 1         | 1.61%   |
| Logitech StreamCam                            | 1         | 1.61%   |
| Logitech QuickCam E 3500                      | 1         | 1.61%   |
| Logitech HD Webcam C525                       | 1         | 1.61%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.61%   |
| Lite-On HP HD Webcam                          | 1         | 1.61%   |
| Lenovo CNF7237&CNF7238                        | 1         | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam             | 1         | 1.61%   |
| IMC Networks Integrated Camera                | 1         | 1.61%   |
| Generalplus GENERAL WEBCAM                    | 1         | 1.61%   |
| Chicony USB2.0 VGA UVC WebCam                 | 1         | 1.61%   |
| Chicony USB2.0 Camera                         | 1         | 1.61%   |
| Chicony USB 2.0 Camera                        | 1         | 1.61%   |
| Chicony TOSHIBA Web Camera - HD               | 1         | 1.61%   |
| Chicony LG Camera                             | 1         | 1.61%   |
| Chicony Laptop_Integrated_Webcam_2M           | 1         | 1.61%   |
| Chicony Integrated HP HD Webcam               | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 40%     |
| Validity Sensors           | 3         | 30%     |
| Synaptics                  | 2         | 20%     |
| Upek                       | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 4         | 40%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 10%     |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics  WBDI                                        | 1         | 10%     |
| Unknown                                                | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 5         | 62.5%   |
| SCM Microsystems      | 1         | 12.5%   |
| Alcor Micro           | 1         | 12.5%   |
| Advanced Card Systems | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 73.39%  |
| 1     | 23        | 21.1%   |
| 2     | 4         | 3.67%   |
| 3     | 2         | 1.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 10        | 30.3%   |
| Chipcard              | 8         | 24.24%  |
| Net/wireless          | 4         | 12.12%  |
| Graphics card         | 3         | 9.09%   |
| Bluetooth             | 2         | 6.06%   |
| Unassigned class      | 1         | 3.03%   |
| Network               | 1         | 3.03%   |
| Multimedia controller | 1         | 3.03%   |
| Flash memory          | 1         | 3.03%   |
| Card reader           | 1         | 3.03%   |
| Camera                | 1         | 3.03%   |

