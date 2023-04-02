Linux in Portugal - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Portugal/Desktop/README.md) and [notebooks](/Location/Portugal/Notebook/README.md).

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

Total: 2085

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3db646f782](https://linux-hardware.org/?probe=3db646f782) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e6b01be2f1](https://linux-hardware.org/?probe=e6b01be2f1) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| HP            | 3646h                       | Desktop     | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [22290c7abf](https://linux-hardware.org/?probe=22290c7abf) | Mar 19, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| ASUSTek       | X202EV                      | Notebook    | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| HP            | ENVY Notebook               | Notebook    | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | Notebook    | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | Notebook    | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | Notebook    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | Notebook    | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [2728efea53](https://linux-hardware.org/?probe=2728efea53) | Mar 05, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [7235211822](https://linux-hardware.org/?probe=7235211822) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e61f05b7f6](https://linux-hardware.org/?probe=e61f05b7f6) | Mar 05, 2023 |
| MSI           | GF72 8RD                    | Notebook    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [73776ef4dd](https://linux-hardware.org/?probe=73776ef4dd) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | Notebook    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | Notebook    | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8fb68b4ad6](https://linux-hardware.org/?probe=8fb68b4ad6) | Feb 26, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | Notebook    | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | Notebook    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [fe75bac6ce](https://linux-hardware.org/?probe=fe75bac6ce) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [605089c66c](https://linux-hardware.org/?probe=605089c66c) | Feb 19, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [3ebf4858b8](https://linux-hardware.org/?probe=3ebf4858b8) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| MSI           | Z68MA-ED55                  | Desktop     | [e2bd6f0fb4](https://linux-hardware.org/?probe=e2bd6f0fb4) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | Notebook    | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4344acac5e](https://linux-hardware.org/?probe=4344acac5e) | Feb 11, 2023 |
| Gigabyte      | P65                         | Notebook    | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| IBM           | 819046G                     | Desktop     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| MSI           | A78M-E35                    | Desktop     | [ba4515e5ea](https://linux-hardware.org/?probe=ba4515e5ea) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | Notebook    | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3bba794976](https://linux-hardware.org/?probe=3bba794976) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [9299261af6](https://linux-hardware.org/?probe=9299261af6) | Feb 05, 2023 |
| Dell          | Precision 7550              | Notebook    | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [d0cf3a9d76](https://linux-hardware.org/?probe=d0cf3a9d76) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [a8f54f681a](https://linux-hardware.org/?probe=a8f54f681a) | Feb 01, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | Notebook    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Acer          | RS740DVF                    | Desktop     | [6aaeb06f9a](https://linux-hardware.org/?probe=6aaeb06f9a) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| ASUSTek       | UX360CA                     | Notebook    | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Pegatron      | Narra6                      | Desktop     | [ac9462ee8e](https://linux-hardware.org/?probe=ac9462ee8e) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [11ce0ed5ad](https://linux-hardware.org/?probe=11ce0ed5ad) | Jan 18, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [cd6cedc906](https://linux-hardware.org/?probe=cd6cedc906) | Jan 17, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [c0441ff1e5](https://linux-hardware.org/?probe=c0441ff1e5) | Jan 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [d27b435baf](https://linux-hardware.org/?probe=d27b435baf) | Jan 10, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [cb970f09e6](https://linux-hardware.org/?probe=cb970f09e6) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [8d177b0b8d](https://linux-hardware.org/?probe=8d177b0b8d) | Jan 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [39ec0d3441](https://linux-hardware.org/?probe=39ec0d3441) | Jan 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| HP            | 83EE                        | Desktop     | [cb43945233](https://linux-hardware.org/?probe=cb43945233) | Jan 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [aff5a2ce85](https://linux-hardware.org/?probe=aff5a2ce85) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [db0e909d27](https://linux-hardware.org/?probe=db0e909d27) | Jan 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [eefb2d0334](https://linux-hardware.org/?probe=eefb2d0334) | Jan 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [76d75de6ac](https://linux-hardware.org/?probe=76d75de6ac) | Jan 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfb32a8abb](https://linux-hardware.org/?probe=dfb32a8abb) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [9d307c5f2f](https://linux-hardware.org/?probe=9d307c5f2f) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [bc835cbca9](https://linux-hardware.org/?probe=bc835cbca9) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | Notebook    | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [042fb842d2](https://linux-hardware.org/?probe=042fb842d2) | Dec 27, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [b181e9e5a3](https://linux-hardware.org/?probe=b181e9e5a3) | Dec 26, 2022 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [896aebf101](https://linux-hardware.org/?probe=896aebf101) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| HP            | 0980h                       | Desktop     | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [5d91d96949](https://linux-hardware.org/?probe=5d91d96949) | Dec 20, 2022 |
| HP            | 0980h                       | Desktop     | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | Notebook    | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Dell          | 0MY171 A00                  | Desktop     | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [2e1fc34b39](https://linux-hardware.org/?probe=2e1fc34b39) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [34157244aa](https://linux-hardware.org/?probe=34157244aa) | Dec 05, 2022 |
| Packard Be... | FIH57                       | Desktop     | [a98f4adbab](https://linux-hardware.org/?probe=a98f4adbab) | Dec 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [5ab13c42b3](https://linux-hardware.org/?probe=5ab13c42b3) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [b3ab0684c5](https://linux-hardware.org/?probe=b3ab0684c5) | Dec 03, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [e28a13071a](https://linux-hardware.org/?probe=e28a13071a) | Dec 02, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [44a7c01e06](https://linux-hardware.org/?probe=44a7c01e06) | Dec 02, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [e5468e4258](https://linux-hardware.org/?probe=e5468e4258) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| HP            | 18E7                        | Desktop     | [5a5c2667a5](https://linux-hardware.org/?probe=5a5c2667a5) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | Notebook    | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | Notebook    | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | Notebook    | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | Notebook    | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | Notebook    | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | Notebook    | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | Notebook    | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [fe997bad04](https://linux-hardware.org/?probe=fe997bad04) | Nov 03, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [1bbd4f8bd9](https://linux-hardware.org/?probe=1bbd4f8bd9) | Nov 03, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46dd8d9b6](https://linux-hardware.org/?probe=c46dd8d9b6) | Nov 01, 2022 |
| Dell          | Latitude E6510              | Notebook    | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | Notebook    | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | Notebook    | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | Notebook    | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | Notebook    | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| HP            | 8158 A01                    | Mini pc     | [d7021dfe8a](https://linux-hardware.org/?probe=d7021dfe8a) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| HP            | 805D                        | Desktop     | [ece9f05ea6](https://linux-hardware.org/?probe=ece9f05ea6) | Oct 14, 2022 |
| HP            | 805D                        | Desktop     | [f10271c447](https://linux-hardware.org/?probe=f10271c447) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [abe6a3fde2](https://linux-hardware.org/?probe=abe6a3fde2) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | Notebook    | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | Notebook    | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| ASRock        | B550 Pro4                   | Desktop     | [a1009d700e](https://linux-hardware.org/?probe=a1009d700e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [70a7e5cad3](https://linux-hardware.org/?probe=70a7e5cad3) | Sep 20, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [b5a8d40602](https://linux-hardware.org/?probe=b5a8d40602) | Sep 18, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [a7931f2026](https://linux-hardware.org/?probe=a7931f2026) | Sep 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [eb81d635df](https://linux-hardware.org/?probe=eb81d635df) | Sep 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [71717109c3](https://linux-hardware.org/?probe=71717109c3) | Sep 10, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [4a791df589](https://linux-hardware.org/?probe=4a791df589) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| OEM           | Intel H81                   | Desktop     | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| MSI           | B85M-E45                    | Desktop     | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | Basswood                    | Desktop     | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | Notebook    | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | Notebook    | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [5eb6c551b0](https://linux-hardware.org/?probe=5eb6c551b0) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [ae71cae955](https://linux-hardware.org/?probe=ae71cae955) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [b3dbd37276](https://linux-hardware.org/?probe=b3dbd37276) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Acer          | FMCP7AM                     | Desktop     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| IP3 Tech      | AH215                       | All in one  | [10fb10ae7f](https://linux-hardware.org/?probe=10fb10ae7f) | Jul 08, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | Notebook    | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3c116356e3](https://linux-hardware.org/?probe=3c116356e3) | Jun 26, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [90038bfa8e](https://linux-hardware.org/?probe=90038bfa8e) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| HP            | ProLiant DL385 G7           | Server      | [89a03359cd](https://linux-hardware.org/?probe=89a03359cd) | Jun 20, 2022 |
| Toshiba       | NB305                       | Notebook    | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | Desktop     | [70438d549d](https://linux-hardware.org/?probe=70438d549d) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | Desktop     | [56abd525d8](https://linux-hardware.org/?probe=56abd525d8) | Jun 14, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| HP            | ProLiant DL385 G7           | Server      | [a232d0abd8](https://linux-hardware.org/?probe=a232d0abd8) | Jun 08, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | Notebook    | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | Notebook    | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | Notebook    | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f2e5a856f4](https://linux-hardware.org/?probe=f2e5a856f4) | May 25, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [37f92aa173](https://linux-hardware.org/?probe=37f92aa173) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [08dedbb3cb](https://linux-hardware.org/?probe=08dedbb3cb) | May 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a83bed6668](https://linux-hardware.org/?probe=a83bed6668) | May 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | Notebook    | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| ASRockRack    | X399D8A-2T                  | Desktop     | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| MSI           | GT72VR 6RD                  | Notebook    | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| Gigabyte      | Z77P-D3                     | Desktop     | [40de59e6f7](https://linux-hardware.org/?probe=40de59e6f7) | May 10, 2022 |
| MSI           | Modern 15 A10RAS            | Notebook    | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [2a10a13430](https://linux-hardware.org/?probe=2a10a13430) | May 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| MSI           | MS-7053                     | Desktop     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| HP            | 8719                        | Desktop     | [7e0ae3d91f](https://linux-hardware.org/?probe=7e0ae3d91f) | Apr 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [2641eee3f1](https://linux-hardware.org/?probe=2641eee3f1) | Apr 21, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a21dad9ee4](https://linux-hardware.org/?probe=a21dad9ee4) | Apr 20, 2022 |
| ASUSTek       | X102BA                      | Notebook    | [00fbb5cbff](https://linux-hardware.org/?probe=00fbb5cbff) | Apr 20, 2022 |
| Lenovo        | ThinkPad L390 20NR001EPG    | Notebook    | [d83b89a414](https://linux-hardware.org/?probe=d83b89a414) | Apr 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [278c76b54f](https://linux-hardware.org/?probe=278c76b54f) | Apr 18, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0c4c081e71](https://linux-hardware.org/?probe=0c4c081e71) | Apr 17, 2022 |
| Toshiba       | Satellite L775-151          | Notebook    | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | Notebook    | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | Notebook    | [a9407bd227](https://linux-hardware.org/?probe=a9407bd227) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | Notebook    | [7403ce7189](https://linux-hardware.org/?probe=7403ce7189) | Apr 16, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5f49d4d7d8](https://linux-hardware.org/?probe=5f49d4d7d8) | Apr 14, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [fba984b898](https://linux-hardware.org/?probe=fba984b898) | Apr 11, 2022 |
| Positivo      | H14BU08                     | Notebook    | [11014257c0](https://linux-hardware.org/?probe=11014257c0) | Apr 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4ca643452e](https://linux-hardware.org/?probe=4ca643452e) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8adf631258](https://linux-hardware.org/?probe=8adf631258) | Apr 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [00c3a80eb1](https://linux-hardware.org/?probe=00c3a80eb1) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ec5daa2c06](https://linux-hardware.org/?probe=ec5daa2c06) | Apr 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9493efcabe](https://linux-hardware.org/?probe=9493efcabe) | Apr 03, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [f9bbaea819](https://linux-hardware.org/?probe=f9bbaea819) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [944f40aa28](https://linux-hardware.org/?probe=944f40aa28) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5dce001675](https://linux-hardware.org/?probe=5dce001675) | Mar 31, 2022 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [740b44dda7](https://linux-hardware.org/?probe=740b44dda7) | Mar 30, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [3cdc036c09](https://linux-hardware.org/?probe=3cdc036c09) | Mar 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [73c18f75a9](https://linux-hardware.org/?probe=73c18f75a9) | Mar 29, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [41870b3fdb](https://linux-hardware.org/?probe=41870b3fdb) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fc92c7a9d2](https://linux-hardware.org/?probe=fc92c7a9d2) | Mar 28, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [7e8bfac4b7](https://linux-hardware.org/?probe=7e8bfac4b7) | Mar 27, 2022 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [96afe8ccf1](https://linux-hardware.org/?probe=96afe8ccf1) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [a2921a6b4c](https://linux-hardware.org/?probe=a2921a6b4c) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [ca5720c46b](https://linux-hardware.org/?probe=ca5720c46b) | Mar 25, 2022 |
| Toshiba       | Satellite P50-B-10V         | Notebook    | [1f6acfd782](https://linux-hardware.org/?probe=1f6acfd782) | Mar 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f146cb600a](https://linux-hardware.org/?probe=f146cb600a) | Mar 24, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [ab3b8653a6](https://linux-hardware.org/?probe=ab3b8653a6) | Mar 23, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [17ceb0fd9f](https://linux-hardware.org/?probe=17ceb0fd9f) | Mar 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [882be4cd35](https://linux-hardware.org/?probe=882be4cd35) | Mar 19, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [9024337e9f](https://linux-hardware.org/?probe=9024337e9f) | Mar 19, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [46b8c80485](https://linux-hardware.org/?probe=46b8c80485) | Mar 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [5b345c55f7](https://linux-hardware.org/?probe=5b345c55f7) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [1fea8c1b2b](https://linux-hardware.org/?probe=1fea8c1b2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [fabbaeb1bb](https://linux-hardware.org/?probe=fabbaeb1bb) | Mar 16, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [483e47645c](https://linux-hardware.org/?probe=483e47645c) | Mar 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [3aded823d8](https://linux-hardware.org/?probe=3aded823d8) | Mar 13, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [aef8901d13](https://linux-hardware.org/?probe=aef8901d13) | Mar 08, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [6bed69bcdb](https://linux-hardware.org/?probe=6bed69bcdb) | Mar 08, 2022 |
| HP            | 0A54h                       | Desktop     | [2dfc948414](https://linux-hardware.org/?probe=2dfc948414) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [18bc15734f](https://linux-hardware.org/?probe=18bc15734f) | Mar 07, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a90d26bc2d](https://linux-hardware.org/?probe=a90d26bc2d) | Mar 06, 2022 |
| Lenovo        | ThinkPad W541 20EGS03100    | Notebook    | [f7b51cf262](https://linux-hardware.org/?probe=f7b51cf262) | Mar 05, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [b5678eb9d3](https://linux-hardware.org/?probe=b5678eb9d3) | Mar 05, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [87a5df55b8](https://linux-hardware.org/?probe=87a5df55b8) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [dd40993d97](https://linux-hardware.org/?probe=dd40993d97) | Mar 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c1b8c2903d](https://linux-hardware.org/?probe=c1b8c2903d) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [67241eca45](https://linux-hardware.org/?probe=67241eca45) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [06455796f9](https://linux-hardware.org/?probe=06455796f9) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [01b50ec980](https://linux-hardware.org/?probe=01b50ec980) | Mar 01, 2022 |
| HP            | 3396                        | Desktop     | [f952a8f044](https://linux-hardware.org/?probe=f952a8f044) | Mar 01, 2022 |
| MSI           | B85M-E45                    | Desktop     | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [8aa7469422](https://linux-hardware.org/?probe=8aa7469422) | Feb 27, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [1d156021e3](https://linux-hardware.org/?probe=1d156021e3) | Feb 26, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b223305dc1](https://linux-hardware.org/?probe=b223305dc1) | Feb 26, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Biostar       | H81MHV3                     | Desktop     | [3fd07aef04](https://linux-hardware.org/?probe=3fd07aef04) | Feb 25, 2022 |
| Positivo      | H14BU08                     | Notebook    | [b3cb8e0d72](https://linux-hardware.org/?probe=b3cb8e0d72) | Feb 25, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e72b93aadf](https://linux-hardware.org/?probe=e72b93aadf) | Feb 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e9d9cfb3e9](https://linux-hardware.org/?probe=e9d9cfb3e9) | Feb 24, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [20b0cf0db9](https://linux-hardware.org/?probe=20b0cf0db9) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [48d36e9bae](https://linux-hardware.org/?probe=48d36e9bae) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [60adc82fb8](https://linux-hardware.org/?probe=60adc82fb8) | Feb 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cf3e28fb31](https://linux-hardware.org/?probe=cf3e28fb31) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| IBM           | 819046G                     | Desktop     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| ASUSTek       | P5VDC-X                     | Desktop     | [40943e3ee0](https://linux-hardware.org/?probe=40943e3ee0) | Feb 22, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [2a35f863c2](https://linux-hardware.org/?probe=2a35f863c2) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | Notebook    | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | Notebook    | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [013349e12a](https://linux-hardware.org/?probe=013349e12a) | Feb 19, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f114f6ea54](https://linux-hardware.org/?probe=f114f6ea54) | Feb 18, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [b6f947ed63](https://linux-hardware.org/?probe=b6f947ed63) | Feb 18, 2022 |
| HP            | 83F3                        | Desktop     | [9421f4385a](https://linux-hardware.org/?probe=9421f4385a) | Feb 18, 2022 |
| Dell          | Latitude E6440              | Notebook    | [1d4bac917c](https://linux-hardware.org/?probe=1d4bac917c) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [f7ee45924c](https://linux-hardware.org/?probe=f7ee45924c) | Feb 17, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b39fbbaec6](https://linux-hardware.org/?probe=b39fbbaec6) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [8441ab9eb2](https://linux-hardware.org/?probe=8441ab9eb2) | Feb 15, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [c2f63ae6d7](https://linux-hardware.org/?probe=c2f63ae6d7) | Feb 14, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [cdd4414bbd](https://linux-hardware.org/?probe=cdd4414bbd) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [fb81da9fa5](https://linux-hardware.org/?probe=fb81da9fa5) | Feb 13, 2022 |
| MSI           | MS-7053                     | Desktop     | [2ee97bf0a8](https://linux-hardware.org/?probe=2ee97bf0a8) | Feb 13, 2022 |
| Dell          | Precision 3561              | Notebook    | [23c3392c57](https://linux-hardware.org/?probe=23c3392c57) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6c64279dbc](https://linux-hardware.org/?probe=6c64279dbc) | Feb 12, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [0dd30d1e7e](https://linux-hardware.org/?probe=0dd30d1e7e) | Feb 11, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | Notebook    | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| MSI           | H61M-P20                    | Desktop     | [81b315b229](https://linux-hardware.org/?probe=81b315b229) | Feb 09, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f5d9f92aad](https://linux-hardware.org/?probe=f5d9f92aad) | Feb 09, 2022 |
| HP            | 8103 A01                    | Mini pc     | [60924b9fd9](https://linux-hardware.org/?probe=60924b9fd9) | Feb 08, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| MSI           | B85M-E45                    | Desktop     | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6bee100b0a](https://linux-hardware.org/?probe=6bee100b0a) | Feb 06, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [a554a842f7](https://linux-hardware.org/?probe=a554a842f7) | Feb 05, 2022 |
| Dell          | Latitude D630               | Notebook    | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [722271e199](https://linux-hardware.org/?probe=722271e199) | Feb 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [62cf8cdd3c](https://linux-hardware.org/?probe=62cf8cdd3c) | Feb 02, 2022 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [a3f3367577](https://linux-hardware.org/?probe=a3f3367577) | Feb 02, 2022 |
| Dell          | Latitude D630               | Notebook    | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [c3e03d2551](https://linux-hardware.org/?probe=c3e03d2551) | Feb 01, 2022 |
| ASUSTek       | P5K3L-ASUS-S1-P5G35         | Desktop     | [f9e7838b90](https://linux-hardware.org/?probe=f9e7838b90) | Jan 31, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [e0c36731ca](https://linux-hardware.org/?probe=e0c36731ca) | Jan 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [b4f3d4f1ee](https://linux-hardware.org/?probe=b4f3d4f1ee) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [77d230b476](https://linux-hardware.org/?probe=77d230b476) | Jan 29, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [435c894ed4](https://linux-hardware.org/?probe=435c894ed4) | Jan 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [5b23faaf76](https://linux-hardware.org/?probe=5b23faaf76) | Jan 22, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [90249388ff](https://linux-hardware.org/?probe=90249388ff) | Jan 22, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [3791490565](https://linux-hardware.org/?probe=3791490565) | Jan 22, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6fd36db1e0](https://linux-hardware.org/?probe=6fd36db1e0) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [c7f9080e23](https://linux-hardware.org/?probe=c7f9080e23) | Jan 18, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [ca83027c67](https://linux-hardware.org/?probe=ca83027c67) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b27ed63a97](https://linux-hardware.org/?probe=b27ed63a97) | Jan 16, 2022 |
| MSI           | MS-7053                     | Desktop     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [9338817523](https://linux-hardware.org/?probe=9338817523) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a8ff8d111b](https://linux-hardware.org/?probe=a8ff8d111b) | Jan 11, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | Notebook    | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [5ba5bfc822](https://linux-hardware.org/?probe=5ba5bfc822) | Jan 11, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [468890e10d](https://linux-hardware.org/?probe=468890e10d) | Jan 08, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [7587e6c439](https://linux-hardware.org/?probe=7587e6c439) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [a3194a0ed3](https://linux-hardware.org/?probe=a3194a0ed3) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a140e77bfe](https://linux-hardware.org/?probe=a140e77bfe) | Jan 05, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| HP            | ProBook 4530s               | Notebook    | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | Notebook    | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [83285ade95](https://linux-hardware.org/?probe=83285ade95) | Jan 02, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [602fe88681](https://linux-hardware.org/?probe=602fe88681) | Jan 02, 2022 |
| Timi          | TM1701                      | Notebook    | [594f40016d](https://linux-hardware.org/?probe=594f40016d) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Gigabyte      | P41T-D3P                    | Desktop     | [1c94714d99](https://linux-hardware.org/?probe=1c94714d99) | Jan 01, 2022 |
| Google        | Sion                        | Desktop     | [08215c86b6](https://linux-hardware.org/?probe=08215c86b6) | Dec 31, 2021 |
| Dell          | Latitude D420               | Notebook    | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| ASUSTek       | A_F_K31AN                   | Desktop     | [4bd56c7243](https://linux-hardware.org/?probe=4bd56c7243) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | Desktop     | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [6f891ac715](https://linux-hardware.org/?probe=6f891ac715) | Dec 29, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d988f944f8](https://linux-hardware.org/?probe=d988f944f8) | Dec 28, 2021 |
| Huanan        | X79-8D VAA31                | Desktop     | [79be6da608](https://linux-hardware.org/?probe=79be6da608) | Dec 26, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1daccedded](https://linux-hardware.org/?probe=1daccedded) | Dec 26, 2021 |
| HP            | 1998                        | Desktop     | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [fe1f7f03e2](https://linux-hardware.org/?probe=fe1f7f03e2) | Dec 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Acer          | Aspire ES1-520              | Notebook    | [7a43d12de6](https://linux-hardware.org/?probe=7a43d12de6) | Dec 20, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| MSI           | MS-7053                     | Desktop     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | Desktop     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [ad0dc6b737](https://linux-hardware.org/?probe=ad0dc6b737) | Dec 17, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [67b8998643](https://linux-hardware.org/?probe=67b8998643) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f9a4ac885d](https://linux-hardware.org/?probe=f9a4ac885d) | Dec 17, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [0ecac9e450](https://linux-hardware.org/?probe=0ecac9e450) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | Notebook    | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [830b8475ac](https://linux-hardware.org/?probe=830b8475ac) | Dec 15, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [4b7a0b485e](https://linux-hardware.org/?probe=4b7a0b485e) | Dec 15, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [6248556dd7](https://linux-hardware.org/?probe=6248556dd7) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | Notebook    | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [11fb7ea1d7](https://linux-hardware.org/?probe=11fb7ea1d7) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [23579d8b3a](https://linux-hardware.org/?probe=23579d8b3a) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [66796a4303](https://linux-hardware.org/?probe=66796a4303) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1d9d5bfe12](https://linux-hardware.org/?probe=1d9d5bfe12) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | Notebook    | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| Fujitsu       | D3521-A1 S26361-D3521-A1... | Server      | [cded98e996](https://linux-hardware.org/?probe=cded98e996) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [8e4401834b](https://linux-hardware.org/?probe=8e4401834b) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Packard Be... | EasyNote_MX37-V-101PT       | Notebook    | [6f8e7042c4](https://linux-hardware.org/?probe=6f8e7042c4) | Nov 30, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Pegatron      | Benicia                     | Desktop     | [d50daedc5d](https://linux-hardware.org/?probe=d50daedc5d) | Nov 26, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [6b926197c9](https://linux-hardware.org/?probe=6b926197c9) | Nov 24, 2021 |
| HP            | Pavilion 15                 | Notebook    | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [22f1f5326e](https://linux-hardware.org/?probe=22f1f5326e) | Nov 21, 2021 |
| HP            | 15 TS                       | Notebook    | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| Clevo         | M7X0SU                      | Notebook    | [a9638079c6](https://linux-hardware.org/?probe=a9638079c6) | Nov 20, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [517d6787c9](https://linux-hardware.org/?probe=517d6787c9) | Nov 20, 2021 |
| Biostar       | FX9830M                     | Desktop     | [f845fe2694](https://linux-hardware.org/?probe=f845fe2694) | Nov 19, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [32a54aa260](https://linux-hardware.org/?probe=32a54aa260) | Nov 19, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [21a3bdf255](https://linux-hardware.org/?probe=21a3bdf255) | Nov 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8fc5db0cd9](https://linux-hardware.org/?probe=8fc5db0cd9) | Nov 17, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [2c4fd499c5](https://linux-hardware.org/?probe=2c4fd499c5) | Nov 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [3f54f48e23](https://linux-hardware.org/?probe=3f54f48e23) | Nov 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [5f28060674](https://linux-hardware.org/?probe=5f28060674) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [6c0ee3ae74](https://linux-hardware.org/?probe=6c0ee3ae74) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [be61c60b41](https://linux-hardware.org/?probe=be61c60b41) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [9fa65491aa](https://linux-hardware.org/?probe=9fa65491aa) | Nov 12, 2021 |
| ASUSTek       | X202EV                      | Notebook    | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| Lenovo        | ThinkPad T420 4177Q5U       | Notebook    | [02ce053478](https://linux-hardware.org/?probe=02ce053478) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [c13d42cb63](https://linux-hardware.org/?probe=c13d42cb63) | Nov 10, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [7d9fdf4b73](https://linux-hardware.org/?probe=7d9fdf4b73) | Nov 10, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [fd25e09529](https://linux-hardware.org/?probe=fd25e09529) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8403f5c97f](https://linux-hardware.org/?probe=8403f5c97f) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4a2a86c38](https://linux-hardware.org/?probe=d4a2a86c38) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [c7b52e35cf](https://linux-hardware.org/?probe=c7b52e35cf) | Nov 08, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | G62                         | Notebook    | [a4a0360f3a](https://linux-hardware.org/?probe=a4a0360f3a) | Nov 06, 2021 |
| HP            | G62                         | Notebook    | [cd87bfa19b](https://linux-hardware.org/?probe=cd87bfa19b) | Nov 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [87daccdc88](https://linux-hardware.org/?probe=87daccdc88) | Nov 05, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [0b933dd493](https://linux-hardware.org/?probe=0b933dd493) | Nov 03, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [c22b81abd4](https://linux-hardware.org/?probe=c22b81abd4) | Nov 02, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | Notebook    | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | Notebook    | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Standard      | Unknown                     | Notebook    | [3cccd4bf9f](https://linux-hardware.org/?probe=3cccd4bf9f) | Nov 02, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [ca8418c85b](https://linux-hardware.org/?probe=ca8418c85b) | Nov 02, 2021 |
| Acer          | Aspire E1-570G              | Notebook    | [9c6c7691c9](https://linux-hardware.org/?probe=9c6c7691c9) | Nov 02, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [f92fa1f111](https://linux-hardware.org/?probe=f92fa1f111) | Oct 31, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [d1fc84613e](https://linux-hardware.org/?probe=d1fc84613e) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [7095848f26](https://linux-hardware.org/?probe=7095848f26) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [ce23f8d9f9](https://linux-hardware.org/?probe=ce23f8d9f9) | Oct 30, 2021 |
| MSI           | P55-CD53                    | Desktop     | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| Standard      | Unknown                     | Notebook    | [1bf7e2da2f](https://linux-hardware.org/?probe=1bf7e2da2f) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| Acer          | Aspire 5732Z                | Notebook    | [9d4f7a1a4b](https://linux-hardware.org/?probe=9d4f7a1a4b) | Oct 27, 2021 |
| ASUSTek       | X453MA                      | Notebook    | [4a70424b2f](https://linux-hardware.org/?probe=4a70424b2f) | Oct 27, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [9b382500c5](https://linux-hardware.org/?probe=9b382500c5) | Oct 27, 2021 |
| ASUSTek       | A_F_K31AN                   | Desktop     | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| Dell          | Latitude E5400              | Notebook    | [7049bbe182](https://linux-hardware.org/?probe=7049bbe182) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [4826046b43](https://linux-hardware.org/?probe=4826046b43) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | Notebook    | [b3e2853259](https://linux-hardware.org/?probe=b3e2853259) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | Notebook    | [5af2c96114](https://linux-hardware.org/?probe=5af2c96114) | Oct 24, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [7a6479dc2d](https://linux-hardware.org/?probe=7a6479dc2d) | Oct 23, 2021 |
| HP            | Notebook                    | Notebook    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Lenovo        | ThinkPad T480 20L6S7PE06    | Notebook    | [28857899a2](https://linux-hardware.org/?probe=28857899a2) | Oct 20, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [005e2591e8](https://linux-hardware.org/?probe=005e2591e8) | Oct 17, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [0b02aa22d4](https://linux-hardware.org/?probe=0b02aa22d4) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6360789a1c](https://linux-hardware.org/?probe=6360789a1c) | Oct 14, 2021 |
| eMachines     | E520 V1.06                  | Notebook    | [97c667e3c0](https://linux-hardware.org/?probe=97c667e3c0) | Oct 14, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| HP            | Pavilion g6                 | Notebook    | [5eba384acd](https://linux-hardware.org/?probe=5eba384acd) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [2ee0e02dca](https://linux-hardware.org/?probe=2ee0e02dca) | Oct 08, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [b73e4dc969](https://linux-hardware.org/?probe=b73e4dc969) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [cc60b4cc30](https://linux-hardware.org/?probe=cc60b4cc30) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [dae39c15c9](https://linux-hardware.org/?probe=dae39c15c9) | Oct 06, 2021 |
| HP            | G62                         | Notebook    | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [426eac3a94](https://linux-hardware.org/?probe=426eac3a94) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [b1996e39c6](https://linux-hardware.org/?probe=b1996e39c6) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [47def5d058](https://linux-hardware.org/?probe=47def5d058) | Oct 05, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [eeae519a3e](https://linux-hardware.org/?probe=eeae519a3e) | Oct 04, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96cf9ba56a](https://linux-hardware.org/?probe=96cf9ba56a) | Sep 30, 2021 |
| ASUSTek       | X453MA                      | Notebook    | [782dfc1a5f](https://linux-hardware.org/?probe=782dfc1a5f) | Sep 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [07116867d0](https://linux-hardware.org/?probe=07116867d0) | Sep 30, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [c6c9f72f10](https://linux-hardware.org/?probe=c6c9f72f10) | Sep 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [1466ee93ee](https://linux-hardware.org/?probe=1466ee93ee) | Sep 29, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [985d394a66](https://linux-hardware.org/?probe=985d394a66) | Sep 29, 2021 |
| ASUSTek       | M4N68T-M                    | Desktop     | [adaee7ea4e](https://linux-hardware.org/?probe=adaee7ea4e) | Sep 28, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [053ea52cd6](https://linux-hardware.org/?probe=053ea52cd6) | Sep 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [0a3653d139](https://linux-hardware.org/?probe=0a3653d139) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a5de874a12](https://linux-hardware.org/?probe=a5de874a12) | Sep 26, 2021 |
| Dell          | Latitude 5400               | Notebook    | [c94a87ddcd](https://linux-hardware.org/?probe=c94a87ddcd) | Sep 26, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Shuttle       | NC03U                       | Desktop     | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Fujitsu       | LIFEBOOK AH552/SL           | Notebook    | [adefc47ea8](https://linux-hardware.org/?probe=adefc47ea8) | Sep 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [6a1f29d17c](https://linux-hardware.org/?probe=6a1f29d17c) | Sep 22, 2021 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [8a14f4f8ce](https://linux-hardware.org/?probe=8a14f4f8ce) | Sep 20, 2021 |
| Foxconn       | A74ML-K                     | Desktop     | [b7a9a59c77](https://linux-hardware.org/?probe=b7a9a59c77) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a7a8c2cead](https://linux-hardware.org/?probe=a7a8c2cead) | Sep 18, 2021 |
| Biostar       | A68MHE                      | Desktop     | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [134fab4631](https://linux-hardware.org/?probe=134fab4631) | Sep 17, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [82058974d9](https://linux-hardware.org/?probe=82058974d9) | Sep 17, 2021 |
| Libretrend    | LT1000                      | Desktop     | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [78a5f6cc5b](https://linux-hardware.org/?probe=78a5f6cc5b) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [fd9704ad22](https://linux-hardware.org/?probe=fd9704ad22) | Sep 16, 2021 |
| ASUSTek       | F5SL                        | Notebook    | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Sony          | VGN-FZ21M                   | Notebook    | [f68a8cedaa](https://linux-hardware.org/?probe=f68a8cedaa) | Sep 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9286413a5](https://linux-hardware.org/?probe=c9286413a5) | Sep 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6488a302af](https://linux-hardware.org/?probe=6488a302af) | Sep 15, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Acer          | Elena                       | Desktop     | [c05122b62f](https://linux-hardware.org/?probe=c05122b62f) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [232a307a5b](https://linux-hardware.org/?probe=232a307a5b) | Sep 14, 2021 |
| Acer          | Aspire ES1-520              | Notebook    | [4b4f263238](https://linux-hardware.org/?probe=4b4f263238) | Sep 14, 2021 |
| Intel         | powered classmate PC        | Notebook    | [15cb9c7764](https://linux-hardware.org/?probe=15cb9c7764) | Sep 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [1ef0a151b1](https://linux-hardware.org/?probe=1ef0a151b1) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | Desktop     | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bfe6584c68](https://linux-hardware.org/?probe=bfe6584c68) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e82ca3db5b](https://linux-hardware.org/?probe=e82ca3db5b) | Sep 12, 2021 |
| MSI           | GE75 Raider 8RF             | Notebook    | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c50b07bfbc](https://linux-hardware.org/?probe=c50b07bfbc) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [24053a2921](https://linux-hardware.org/?probe=24053a2921) | Sep 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b34fb7492d](https://linux-hardware.org/?probe=b34fb7492d) | Sep 07, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [b92b2f815b](https://linux-hardware.org/?probe=b92b2f815b) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e65bcd50d4](https://linux-hardware.org/?probe=e65bcd50d4) | Sep 05, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [f617f97f20](https://linux-hardware.org/?probe=f617f97f20) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| Dell          | 0X947H A01                  | Server      | [e36bfcd946](https://linux-hardware.org/?probe=e36bfcd946) | Sep 02, 2021 |
| Dell          | 0X947H A01                  | Server      | [faee3aa1d7](https://linux-hardware.org/?probe=faee3aa1d7) | Sep 02, 2021 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [54825c8496](https://linux-hardware.org/?probe=54825c8496) | Sep 02, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [3a4c36db86](https://linux-hardware.org/?probe=3a4c36db86) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [62e286b6bc](https://linux-hardware.org/?probe=62e286b6bc) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [84ed2a684d](https://linux-hardware.org/?probe=84ed2a684d) | Aug 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6d630f76dc](https://linux-hardware.org/?probe=6d630f76dc) | Aug 30, 2021 |
| ASRock        | 760GM-HDV                   | Desktop     | [7b2322353d](https://linux-hardware.org/?probe=7b2322353d) | Aug 29, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [c431035e14](https://linux-hardware.org/?probe=c431035e14) | Aug 28, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [26e4c99970](https://linux-hardware.org/?probe=26e4c99970) | Aug 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [25c5f20a00](https://linux-hardware.org/?probe=25c5f20a00) | Aug 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [fcfdefc5ce](https://linux-hardware.org/?probe=fcfdefc5ce) | Aug 24, 2021 |
| Unknown       | 1.0                         | Desktop     | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| Acer          | Aspire one 1-431            | Notebook    | [1d73bf7163](https://linux-hardware.org/?probe=1d73bf7163) | Aug 23, 2021 |
| HP            | Compaq Presario CQ50        | Notebook    | [afde6653db](https://linux-hardware.org/?probe=afde6653db) | Aug 20, 2021 |
| ECS           | Livermore8                  | Desktop     | [a86f5a7745](https://linux-hardware.org/?probe=a86f5a7745) | Aug 18, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [c2dee4fe1c](https://linux-hardware.org/?probe=c2dee4fe1c) | Aug 14, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [c1e4d1748b](https://linux-hardware.org/?probe=c1e4d1748b) | Aug 14, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [ae9629c543](https://linux-hardware.org/?probe=ae9629c543) | Aug 13, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [d045383640](https://linux-hardware.org/?probe=d045383640) | Aug 12, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [f3e17cb791](https://linux-hardware.org/?probe=f3e17cb791) | Aug 12, 2021 |
| ASUSTek       | X541UV                      | Notebook    | [3f45acb762](https://linux-hardware.org/?probe=3f45acb762) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3fb07ec1ab](https://linux-hardware.org/?probe=3fb07ec1ab) | Aug 11, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f8bd1ccc54](https://linux-hardware.org/?probe=f8bd1ccc54) | Aug 09, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [0576757382](https://linux-hardware.org/?probe=0576757382) | Aug 08, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [77c994366c](https://linux-hardware.org/?probe=77c994366c) | Aug 04, 2021 |
| Biostar       | A68MHE                      | Desktop     | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ea96dd2fc0](https://linux-hardware.org/?probe=ea96dd2fc0) | Aug 03, 2021 |
| Acer          | Extensa 5635ZG              | Notebook    | [7b18fd92ec](https://linux-hardware.org/?probe=7b18fd92ec) | Aug 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [dde43dfc5f](https://linux-hardware.org/?probe=dde43dfc5f) | Jul 31, 2021 |
| Acer          | Extensa 5635ZG              | Notebook    | [920920b284](https://linux-hardware.org/?probe=920920b284) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [a6df82ec75](https://linux-hardware.org/?probe=a6df82ec75) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [b33ddef912](https://linux-hardware.org/?probe=b33ddef912) | Jul 30, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [a4d0bd11cf](https://linux-hardware.org/?probe=a4d0bd11cf) | Jul 30, 2021 |
| Packard Be... | EasyNote MB65               | Notebook    | [f659f0645c](https://linux-hardware.org/?probe=f659f0645c) | Jul 28, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [bd1b8e13fe](https://linux-hardware.org/?probe=bd1b8e13fe) | Jul 28, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [0e3d86e5fc](https://linux-hardware.org/?probe=0e3d86e5fc) | Jul 28, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e877303c3f](https://linux-hardware.org/?probe=e877303c3f) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| ASUSTek       | X550DP                      | Notebook    | [fab8695920](https://linux-hardware.org/?probe=fab8695920) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [a2ba4d937e](https://linux-hardware.org/?probe=a2ba4d937e) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N3S27C00    | Notebook    | [f4f26a9357](https://linux-hardware.org/?probe=f4f26a9357) | Jul 24, 2021 |
| Sony          | VGN-AW21Z_B                 | Notebook    | [16afdefee9](https://linux-hardware.org/?probe=16afdefee9) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [996bc7336f](https://linux-hardware.org/?probe=996bc7336f) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [84d70d9bde](https://linux-hardware.org/?probe=84d70d9bde) | Jul 23, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [189789f8d5](https://linux-hardware.org/?probe=189789f8d5) | Jul 23, 2021 |
| Toshiba       | Satellite M70               | Notebook    | [ffe4b92da3](https://linux-hardware.org/?probe=ffe4b92da3) | Jul 21, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [bdd8ae093d](https://linux-hardware.org/?probe=bdd8ae093d) | Jul 21, 2021 |
| Dell          | 04MFRM A02                  | Desktop     | [9d92f05e1c](https://linux-hardware.org/?probe=9d92f05e1c) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | Desktop     | [2b2a31a2f9](https://linux-hardware.org/?probe=2b2a31a2f9) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1056457127](https://linux-hardware.org/?probe=1056457127) | Jul 17, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6e299e2f37](https://linux-hardware.org/?probe=6e299e2f37) | Jul 16, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [288b6b0769](https://linux-hardware.org/?probe=288b6b0769) | Jul 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4004b6bcb6](https://linux-hardware.org/?probe=4004b6bcb6) | Jul 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [1a9dfe2f20](https://linux-hardware.org/?probe=1a9dfe2f20) | Jul 16, 2021 |
| Toshiba       | Satellite P50-C             | Notebook    | [3b8ead252b](https://linux-hardware.org/?probe=3b8ead252b) | Jul 15, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [d26cb48393](https://linux-hardware.org/?probe=d26cb48393) | Jul 14, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [9d1dfce344](https://linux-hardware.org/?probe=9d1dfce344) | Jul 13, 2021 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [e2a2b5ba07](https://linux-hardware.org/?probe=e2a2b5ba07) | Jul 13, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [9d9f33c5e5](https://linux-hardware.org/?probe=9d9f33c5e5) | Jul 12, 2021 |
| Acer          | NC-V3-575G-58LU             | Notebook    | [da6da7fbd6](https://linux-hardware.org/?probe=da6da7fbd6) | Jul 11, 2021 |
| ASUSTek       | G50V                        | Notebook    | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [e663cfd24c](https://linux-hardware.org/?probe=e663cfd24c) | Jul 10, 2021 |
| Dell          | Latitude D530               | Notebook    | [d48cd58890](https://linux-hardware.org/?probe=d48cd58890) | Jul 09, 2021 |
| Dell          | Precision M4600             | Notebook    | [388aad414f](https://linux-hardware.org/?probe=388aad414f) | Jul 08, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3bde956fe7](https://linux-hardware.org/?probe=3bde956fe7) | Jul 08, 2021 |
| Dell          | Latitude D530               | Notebook    | [21ad721b61](https://linux-hardware.org/?probe=21ad721b61) | Jul 07, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [59233d0bff](https://linux-hardware.org/?probe=59233d0bff) | Jul 07, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [77c0819e0f](https://linux-hardware.org/?probe=77c0819e0f) | Jul 07, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [17afd519cb](https://linux-hardware.org/?probe=17afd519cb) | Jul 06, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0bdc8750c3](https://linux-hardware.org/?probe=0bdc8750c3) | Jul 05, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [119260db14](https://linux-hardware.org/?probe=119260db14) | Jul 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0e79f21646](https://linux-hardware.org/?probe=0e79f21646) | Jul 05, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [66b161d8d5](https://linux-hardware.org/?probe=66b161d8d5) | Jul 02, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [bc362bd630](https://linux-hardware.org/?probe=bc362bd630) | Jun 30, 2021 |
| ASRock        | H370M-ITX/ac                | Desktop     | [a6c720d609](https://linux-hardware.org/?probe=a6c720d609) | Jun 29, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d6ef1b054b](https://linux-hardware.org/?probe=d6ef1b054b) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d2a4ffa502](https://linux-hardware.org/?probe=d2a4ffa502) | Jun 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| HP            | ENVY 17                     | Notebook    | [c6b33cf692](https://linux-hardware.org/?probe=c6b33cf692) | Jun 22, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [46e46cdce1](https://linux-hardware.org/?probe=46e46cdce1) | Jun 20, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [02ee8d11bc](https://linux-hardware.org/?probe=02ee8d11bc) | Jun 19, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Dell          | XPS 13 9305                 | Notebook    | [d1799a89c4](https://linux-hardware.org/?probe=d1799a89c4) | Jun 17, 2021 |
| Dell          | Latitude E6520              | Notebook    | [718e90b724](https://linux-hardware.org/?probe=718e90b724) | Jun 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d244c62623](https://linux-hardware.org/?probe=d244c62623) | Jun 16, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b796c5a183](https://linux-hardware.org/?probe=b796c5a183) | Jun 16, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| SLIMBOOK      | PROX15-INTEL                | Notebook    | [f471ae0176](https://linux-hardware.org/?probe=f471ae0176) | Jun 15, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [d6df0a85b4](https://linux-hardware.org/?probe=d6df0a85b4) | Jun 12, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [c7295eb580](https://linux-hardware.org/?probe=c7295eb580) | Jun 12, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a9aed643ab](https://linux-hardware.org/?probe=a9aed643ab) | Jun 12, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [86307cc238](https://linux-hardware.org/?probe=86307cc238) | Jun 12, 2021 |
| ASUSTek       | K73SV                       | Notebook    | [228feaed8e](https://linux-hardware.org/?probe=228feaed8e) | Jun 12, 2021 |
| Google        | Coral                       | Notebook    | [f6cf3ed923](https://linux-hardware.org/?probe=f6cf3ed923) | Jun 11, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 199       | 13.19%  |
| Ubuntu 18.04                 | 139       | 9.21%   |
| Ubuntu 22.04                 | 60        | 3.98%   |
| OpenMandriva 4.3             | 48        | 3.18%   |
| Debian 11                    | 37        | 2.45%   |
| OpenMandriva 4.2             | 36        | 2.39%   |
| Zorin 16                     | 32        | 2.12%   |
| Zorin 15                     | 29        | 1.92%   |
| Pop!_OS 20.04                | 28        | 1.86%   |
| Pop!_OS 22.04                | 25        | 1.66%   |
| KDE neon 20.04               | 23        | 1.52%   |
| Ubuntu 19.10                 | 22        | 1.46%   |
| Linux Mint 20.3              | 22        | 1.46%   |
| Linux Mint 19.3              | 22        | 1.46%   |
| Linux Mint 20                | 21        | 1.39%   |
| Debian 10                    | 21        | 1.39%   |
| Manjaro                      | 20        | 1.33%   |
| Fedora 34                    | 20        | 1.33%   |
| Pop!_OS 21.04                | 19        | 1.26%   |
| Linux Mint 20.1              | 19        | 1.26%   |
| Arch Rolling                 | 19        | 1.26%   |
| Ubuntu 19.04                 | 17        | 1.13%   |
| Xubuntu 20.04                | 16        | 1.06%   |
| Ubuntu 20.10                 | 16        | 1.06%   |
| OpenMandriva 4.50            | 16        | 1.06%   |
| OpenMandriva 23.01           | 16        | 1.06%   |
| Fedora 36                    | 16        | 1.06%   |
| Arch                         | 16        | 1.06%   |
| Ubuntu 21.10                 | 15        | 0.99%   |
| Ubuntu 21.04                 | 15        | 0.99%   |
| Pop!_OS 20.10                | 15        | 0.99%   |
| Xubuntu 18.04                | 14        | 0.93%   |
| Pop!_OS 21.10                | 14        | 0.93%   |
| Fedora 33                    | 14        | 0.93%   |
| ArcoLinux Rolling            | 14        | 0.93%   |
| Linux Mint 19.1              | 13        | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 0.8%    |
| Linux Mint 21.1              | 12        | 0.8%    |
| Linux Mint 21                | 12        | 0.8%    |
| Linux Mint 20.2              | 12        | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 480       | 33.47%  |
| Linux Mint    | 136       | 9.48%   |
| OpenMandriva  | 116       | 8.09%   |
| Pop!_OS       | 98        | 6.83%   |
| Fedora        | 81        | 5.65%   |
| Debian        | 68        | 4.74%   |
| Zorin         | 62        | 4.32%   |
| Manjaro       | 51        | 3.56%   |
| Endless       | 41        | 2.86%   |
| Arch          | 36        | 2.51%   |
| Xubuntu       | 34        | 2.37%   |
| KDE neon      | 33        | 2.3%    |
| ROSA          | 19        | 1.32%   |
| Kubuntu       | 17        | 1.19%   |
| openSUSE      | 16        | 1.12%   |
| Elementary    | 16        | 1.12%   |
| ArcoLinux     | 15        | 1.05%   |
| Ubuntu Unity  | 10        | 0.7%    |
| Ubuntu MATE   | 9         | 0.63%   |
| Slackware     | 7         | 0.49%   |
| LMDE          | 7         | 0.49%   |
| Clear Linux   | 7         | 0.49%   |
| Ubuntu Budgie | 6         | 0.42%   |
| EndeavourOS   | 6         | 0.42%   |
| Nobara        | 5         | 0.35%   |
| Lubuntu       | 5         | 0.35%   |
| Gentoo        | 5         | 0.35%   |
| UbuntuDDE     | 3         | 0.21%   |
| Peppermint    | 3         | 0.21%   |
| CentOS        | 3         | 0.21%   |
| XCP-ng        | 2         | 0.14%   |
| SteamOS       | 2         | 0.14%   |
| Reborn OS     | 2         | 0.14%   |
| Raspbian      | 2         | 0.14%   |
| Parrot        | 2         | 0.14%   |
| MX            | 2         | 0.14%   |
| Manjaro-ARM   | 2         | 0.14%   |
| Devuan        | 2         | 0.14%   |
| BlackPanther  | 2         | 0.14%   |
| BigLinux      | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 40        | 2.39%   |
| 5.4.0-42-generic         | 38        | 2.27%   |
| 5.10.14-desktop-1omv4002 | 35        | 2.09%   |
| 5.15.0-56-generic        | 19        | 1.14%   |
| 5.3.0-46-generic         | 16        | 0.96%   |
| 5.4.0-58-generic         | 15        | 0.9%    |
| 5.4.0-52-generic         | 15        | 0.9%    |
| 6.1.1-desktop-1omv2290   | 14        | 0.84%   |
| 5.4.0-29-generic         | 14        | 0.84%   |
| 5.15.0-58-generic        | 13        | 0.78%   |
| 5.15.0-52-generic        | 13        | 0.78%   |
| 5.15.0-48-generic        | 13        | 0.78%   |
| 5.15.0-46-generic        | 13        | 0.78%   |
| 5.11.0-38-generic        | 13        | 0.78%   |
| 5.4.0-26-generic         | 12        | 0.72%   |
| 5.3.0-28-generic         | 12        | 0.72%   |
| 5.0.0-37-generic         | 12        | 0.72%   |
| 5.4.0-7634-generic       | 11        | 0.66%   |
| 5.19.0-76051900-generic  | 11        | 0.66%   |
| 5.14.14-desktop-1omv4050 | 11        | 0.66%   |
| 5.10.0-8-amd64           | 11        | 0.66%   |
| 5.8.0-43-generic         | 10        | 0.6%    |
| 5.4.0-48-generic         | 10        | 0.6%    |
| 5.15.0-41-generic        | 10        | 0.6%    |
| 5.0.0-25-generic         | 10        | 0.6%    |
| 4.18.0-15-generic        | 10        | 0.6%    |
| 5.8.0-48-generic         | 9         | 0.54%   |
| 5.3.0-40-generic         | 9         | 0.54%   |
| 5.11.0-43-generic        | 9         | 0.54%   |
| 4.15.0-46-generic        | 9         | 0.54%   |
| 5.8.0-44-generic         | 8         | 0.48%   |
| 5.4.0-37-generic         | 8         | 0.48%   |
| 5.13.0-39-generic        | 8         | 0.48%   |
| 4.18.0-25-generic        | 8         | 0.48%   |
| 5.4.0-65-generic         | 7         | 0.42%   |
| 5.4.0-40-generic         | 7         | 0.42%   |
| 5.4.0-31-generic         | 7         | 0.42%   |
| 5.4.0-28-generic         | 7         | 0.42%   |
| 5.15.0-53-generic        | 7         | 0.42%   |
| 5.15.0-43-generic        | 7         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 270       | 17.25%  |
| 5.15.0  | 118       | 7.54%   |
| 4.15.0  | 109       | 6.96%   |
| 5.8.0   | 93        | 5.94%   |
| 5.11.0  | 85        | 5.43%   |
| 5.3.0   | 83        | 5.3%    |
| 5.13.0  | 70        | 4.47%   |
| 5.0.0   | 58        | 3.71%   |
| 4.18.0  | 47        | 3%      |
| 5.16.7  | 40        | 2.56%   |
| 5.10.0  | 40        | 2.56%   |
| 5.10.14 | 37        | 2.36%   |
| 5.19.0  | 34        | 2.17%   |
| 4.19.0  | 24        | 1.53%   |
| 6.1.1   | 17        | 1.09%   |
| 5.14.14 | 11        | 0.7%    |
| 5.11.12 | 9         | 0.58%   |
| 6.0.9   | 6         | 0.38%   |
| 5.14.0  | 6         | 0.38%   |
| 4.9.155 | 6         | 0.38%   |
| 4.4.0   | 6         | 0.38%   |
| 6.2.6   | 5         | 0.32%   |
| 6.0.6   | 5         | 0.32%   |
| 6.0.12  | 5         | 0.32%   |
| 5.15.7  | 5         | 0.32%   |
| 5.13.19 | 5         | 0.32%   |
| 5.12.4  | 5         | 0.32%   |
| 6.0.0   | 4         | 0.26%   |
| 5.8.16  | 4         | 0.26%   |
| 5.7.10  | 4         | 0.26%   |
| 5.7.0   | 4         | 0.26%   |
| 5.6.0   | 4         | 0.26%   |
| 5.16.11 | 4         | 0.26%   |
| 5.15.11 | 4         | 0.26%   |
| 5.14.16 | 4         | 0.26%   |
| 4.9.60  | 4         | 0.26%   |
| 4.9.0   | 4         | 0.26%   |
| 6.2.0   | 3         | 0.19%   |
| 6.1.4   | 3         | 0.19%   |
| 6.1.12  | 3         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 286       | 18.49%  |
| 5.15    | 161       | 10.41%  |
| 5.8     | 116       | 7.5%    |
| 4.15    | 110       | 7.11%   |
| 5.11    | 99        | 6.4%    |
| 5.10    | 96        | 6.21%   |
| 5.3     | 86        | 5.56%   |
| 5.13    | 84        | 5.43%   |
| 5.16    | 63        | 4.07%   |
| 5.0     | 59        | 3.81%   |
| 5.19    | 53        | 3.43%   |
| 4.18    | 51        | 3.3%    |
| 6.1     | 36        | 2.33%   |
| 6.0     | 32        | 2.07%   |
| 5.14    | 31        | 2%      |
| 4.19    | 28        | 1.81%   |
| 5.12    | 22        | 1.42%   |
| 4.9     | 20        | 1.29%   |
| 5.7     | 16        | 1.03%   |
| 5.9     | 15        | 0.97%   |
| 5.17    | 15        | 0.97%   |
| 5.6     | 14        | 0.9%    |
| 5.18    | 13        | 0.84%   |
| 6.2     | 12        | 0.78%   |
| 5.5     | 10        | 0.65%   |
| 4.4     | 6         | 0.39%   |
| 5.2     | 4         | 0.26%   |
| 4.12    | 2         | 0.13%   |
| 4.10    | 2         | 0.13%   |
| 5.1     | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |
| 3.10    | 1         | 0.06%   |
| 2.6     | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1309      | 94.79%  |
| i686    | 63        | 4.56%   |
| aarch64 | 7         | 0.51%   |
| armv7l  | 2         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 641       | 44.15%  |
| KDE5            | 218       | 15.01%  |
| Unknown         | 216       | 14.88%  |
| XFCE            | 111       | 7.64%   |
| X-Cinnamon      | 103       | 7.09%   |
| KDE             | 32        | 2.2%    |
| MATE            | 28        | 1.93%   |
| Pantheon        | 15        | 1.03%   |
| Cinnamon        | 14        | 0.96%   |
| KDE4            | 12        | 0.83%   |
| Budgie          | 12        | 0.83%   |
| Unity           | 11        | 0.76%   |
| i3              | 10        | 0.69%   |
| awesome         | 6         | 0.41%   |
| LXQt            | 5         | 0.34%   |
| LXDE            | 5         | 0.34%   |
| Deepin          | 4         | 0.28%   |
| GNOME Flashback | 3         | 0.21%   |
| Openbox         | 2         | 0.14%   |
| qtile           | 1         | 0.07%   |
| LeftWM          | 1         | 0.07%   |
| Hyprland        | 1         | 0.07%   |
| fluxbox         | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1104      | 78.08%  |
| Wayland | 186       | 13.15%  |
| Unknown | 115       | 8.13%   |
| Tty     | 9         | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 813       | 56.73%  |
| SDDM    | 190       | 13.26%  |
| GDM     | 139       | 9.7%    |
| GDM3    | 130       | 9.07%   |
| LightDM | 101       | 7.05%   |
| TDM     | 43        | 3%      |
| KDM     | 12        | 0.84%   |
| XDM     | 4         | 0.28%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_PT   | 575       | 40.41%  |
| en_US   | 492       | 34.57%  |
| Unknown | 199       | 13.98%  |
| en_GB   | 71        | 4.99%   |
| C       | 26        | 1.83%   |
| pt_BR   | 23        | 1.62%   |
| fr_FR   | 7         | 0.49%   |
| ru_RU   | 5         | 0.35%   |
| en_IE   | 5         | 0.35%   |
| de_DE   | 5         | 0.35%   |
| es_ES   | 4         | 0.28%   |
| sv_SE   | 3         | 0.21%   |
| POSIX   | 2         | 0.14%   |
| en_CA   | 2         | 0.14%   |
| sk_SK   | 1         | 0.07%   |
| it_IT   | 1         | 0.07%   |
| en_IN   | 1         | 0.07%   |
| Default | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 800       | 56.46%  |
| EFI  | 617       | 43.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1103      | 78.51%  |
| Overlay  | 103       | 7.33%   |
| Btrfs    | 99        | 7.05%   |
| Unknown  | 67        | 4.77%   |
| Xfs      | 14        | 1%      |
| Zfs      | 7         | 0.5%    |
| Ext2     | 5         | 0.36%   |
| Ext3     | 4         | 0.28%   |
| Reiserfs | 1         | 0.07%   |
| F2fs     | 1         | 0.07%   |
| Aufs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 867       | 61.1%   |
| GPT     | 415       | 29.25%  |
| MBR     | 137       | 9.65%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1224      | 87.62%  |
| Yes       | 173       | 12.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 998       | 70.93%  |
| Yes       | 409       | 29.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 315       | 22.83%  |
| Hewlett-Packard         | 213       | 15.43%  |
| Lenovo                  | 182       | 13.19%  |
| Acer                    | 105       | 7.61%   |
| MSI                     | 80        | 5.8%    |
| Toshiba                 | 77        | 5.58%   |
| Dell                    | 66        | 4.78%   |
| Gigabyte Technology     | 56        | 4.06%   |
| Sony                    | 41        | 2.97%   |
| Apple                   | 34        | 2.46%   |
| ASRock                  | 26        | 1.88%   |
| HUAWEI                  | 19        | 1.38%   |
| Samsung Electronics     | 14        | 1.01%   |
| Intel                   | 13        | 0.94%   |
| Fujitsu                 | 10        | 0.72%   |
| Notebook                | 9         | 0.65%   |
| Foxconn                 | 8         | 0.58%   |
| Raspberry Pi Foundation | 7         | 0.51%   |
| Packard Bell            | 7         | 0.51%   |
| Unknown                 | 7         | 0.51%   |
| TUXEDO                  | 6         | 0.43%   |
| eMachines               | 6         | 0.43%   |
| Pegatron                | 4         | 0.29%   |
| Phoenix/SiS             | 3         | 0.22%   |
| LG Electronics          | 3         | 0.22%   |
| Clevo                   | 3         | 0.22%   |
| Chuwi                   | 3         | 0.22%   |
| Biostar                 | 3         | 0.22%   |
| AMI                     | 3         | 0.22%   |
| Teclast                 | 2         | 0.14%   |
| SLIMBOOK                | 2         | 0.14%   |
| Positivo                | 2         | 0.14%   |
| OEM                     | 2         | 0.14%   |
| OBSIDIAN-PC             | 2         | 0.14%   |
| Minix                   | 2         | 0.14%   |
| Microsoft               | 2         | 0.14%   |
| Medion                  | 2         | 0.14%   |
| IP3 Tech                | 2         | 0.14%   |
| INSYS                   | 2         | 0.14%   |
| Huanan                  | 2         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 20        | 1.45%   |
| ASUS All Series                        | 15        | 1.09%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 11        | 0.8%    |
| Unknown                                | 9         | 0.65%   |
| Toshiba Satellite C660                 | 8         | 0.58%   |
| HP Pavilion g6                         | 8         | 0.58%   |
| HP Pavilion dv6                        | 8         | 0.58%   |
| HP G62                                 | 7         | 0.51%   |
| HP Notebook                            | 6         | 0.43%   |
| Toshiba Satellite L650                 | 5         | 0.36%   |
| MSI MS-7817                            | 5         | 0.36%   |
| Lenovo Legion 5 15ACH6H 82JU           | 5         | 0.36%   |
| ASUS X555LJ                            | 5         | 0.36%   |
| ASUS X555LD                            | 5         | 0.36%   |
| ASUS X541UV                            | 5         | 0.36%   |
| Acer Extensa 5620                      | 5         | 0.36%   |
| Toshiba Satellite L500                 | 4         | 0.29%   |
| Toshiba Satellite L40                  | 4         | 0.29%   |
| Toshiba Satellite A200                 | 4         | 0.29%   |
| Lenovo Y520-15IKBN 80WK                | 4         | 0.29%   |
| HUAWEI NBLK-WAX9X                      | 4         | 0.29%   |
| HP Pavilion Notebook                   | 4         | 0.29%   |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.29%   |
| HP Compaq Presario CQ60                | 4         | 0.29%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 4         | 0.29%   |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 4         | 0.29%   |
| ASUS P5G41T-M LX                       | 4         | 0.29%   |
| ASUS H110M-K                           | 4         | 0.29%   |
| Acer Aspire E5-551G                    | 4         | 0.29%   |
| Toshiba Satellite L50D-B               | 3         | 0.22%   |
| MSI Modern 14 A10RB                    | 3         | 0.22%   |
| Lenovo Legion 5 15ARH05 82B5           | 3         | 0.22%   |
| Lenovo IdeaPad 320-15AST 80XV          | 3         | 0.22%   |
| Lenovo G50-45 80E3                     | 3         | 0.22%   |
| Intel powered classmate PC             | 3         | 0.22%   |
| HUAWEI WRT-WX9                         | 3         | 0.22%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 3         | 0.22%   |
| HP Pavilion 15                         | 3         | 0.22%   |
| HP OMEN by Laptop                      | 3         | 0.22%   |
| HP Compaq Presario CQ61                | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 87        | 6.3%    |
| Acer Aspire           | 85        | 6.16%   |
| Toshiba Satellite     | 67        | 4.86%   |
| HP Pavilion           | 58        | 4.2%    |
| Lenovo IdeaPad        | 49        | 3.55%   |
| HP Compaq             | 33        | 2.39%   |
| ASUS VivoBook         | 33        | 2.39%   |
| ASUS PRIME            | 24        | 1.74%   |
| HP EliteBook          | 22        | 1.59%   |
| Dell Latitude         | 22        | 1.59%   |
| Sony VGN-FZ31Z        | 20        | 1.45%   |
| ASUS ROG              | 16        | 1.16%   |
| HP ProBook            | 15        | 1.09%   |
| ASUS All              | 15        | 1.09%   |
| Lenovo Legion         | 13        | 0.94%   |
| Dell XPS              | 13        | 0.94%   |
| HP Laptop             | 12        | 0.87%   |
| Dell OptiPlex         | 11        | 0.8%    |
| HP OMEN               | 10        | 0.72%   |
| ASUS ZenBook          | 10        | 0.72%   |
| HP ENVY               | 9         | 0.65%   |
| Dell Inspiron         | 9         | 0.65%   |
| ASUS P5G41T-M         | 9         | 0.65%   |
| Unknown               | 9         | 0.65%   |
| Dell Precision        | 8         | 0.58%   |
| ASUS TUF              | 8         | 0.58%   |
| Acer Extensa          | 8         | 0.58%   |
| RPi Raspberry         | 7         | 0.51%   |
| HP G62                | 7         | 0.51%   |
| Packard Bell EasyNote | 6         | 0.43%   |
| MSI Modern            | 6         | 0.43%   |
| HP ProLiant           | 6         | 0.43%   |
| HP ProDesk            | 6         | 0.43%   |
| HP Notebook           | 6         | 0.43%   |
| Gigabyte B550         | 6         | 0.43%   |
| MSI MS-7817           | 5         | 0.36%   |
| ASUS X555LJ           | 5         | 0.36%   |
| ASUS X555LD           | 5         | 0.36%   |
| ASUS X541UV           | 5         | 0.36%   |
| Lenovo Yoga           | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 127       | 9.2%    |
| 2018    | 120       | 8.7%    |
| 2019    | 112       | 8.12%   |
| 2010    | 112       | 8.12%   |
| 2015    | 84        | 6.09%   |
| 2014    | 83        | 6.01%   |
| 2013    | 79        | 5.72%   |
| 2012    | 79        | 5.72%   |
| 2008    | 76        | 5.51%   |
| 2017    | 73        | 5.29%   |
| 2007    | 73        | 5.29%   |
| 2016    | 72        | 5.22%   |
| 2011    | 72        | 5.22%   |
| 2009    | 72        | 5.22%   |
| 2021    | 68        | 4.93%   |
| 2006    | 29        | 2.1%    |
| 2022    | 21        | 1.52%   |
| 2005    | 14        | 1.01%   |
| Unknown | 10        | 0.72%   |
| 2004    | 3         | 0.22%   |
| 2003    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 917       | 66.45%  |
| Desktop        | 402       | 29.13%  |
| Mini pc        | 14        | 1.01%   |
| Convertible    | 13        | 0.94%   |
| Tablet         | 9         | 0.65%   |
| System on chip | 8         | 0.58%   |
| All in one     | 8         | 0.58%   |
| Server         | 8         | 0.58%   |
| Phone          | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1293      | 92.23%  |
| Enabled  | 109       | 7.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1376      | 99.71%  |
| Yes  | 4         | 0.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 368       | 26.15%  |
| 4.01-8.0        | 305       | 21.68%  |
| 16.01-24.0      | 228       | 16.2%   |
| 8.01-16.0       | 225       | 15.99%  |
| 32.01-64.0      | 110       | 7.82%   |
| 1.01-2.0        | 92        | 6.54%   |
| 2.01-3.0        | 32        | 2.27%   |
| 64.01-256.0     | 18        | 1.28%   |
| 24.01-32.0      | 14        | 1%      |
| 0.51-1.0        | 14        | 1%      |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 593       | 38.91%  |
| 2.01-3.0    | 324       | 21.26%  |
| 4.01-8.0    | 227       | 14.9%   |
| 3.01-4.0    | 170       | 11.15%  |
| 0.51-1.0    | 116       | 7.61%   |
| 8.01-16.0   | 62        | 4.07%   |
| 0.01-0.5    | 15        | 0.98%   |
| 16.01-24.0  | 10        | 0.66%   |
| 24.01-32.0  | 4         | 0.26%   |
| 32.01-64.0  | 1         | 0.07%   |
| 64.01-256.0 | 1         | 0.07%   |
| Unknown     | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 895       | 63.21%  |
| 2      | 347       | 24.51%  |
| 3      | 92        | 6.5%    |
| 4      | 40        | 2.82%   |
| 0      | 17        | 1.2%    |
| 5      | 10        | 0.71%   |
| 6      | 7         | 0.49%   |
| 11     | 2         | 0.14%   |
| 10     | 2         | 0.14%   |
| 7      | 2         | 0.14%   |
| 87     | 1         | 0.07%   |
| 8      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 849       | 61.3%   |
| Yes       | 536       | 38.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1198      | 86.5%   |
| No        | 187       | 13.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1081      | 77.77%  |
| No        | 309       | 22.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 779       | 55.52%  |
| No        | 624       | 44.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Portugal | 1380      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lisbon                       | 331       | 22.52%  |
| Porto                        | 123       | 8.37%   |
| Funchal                      | 33        | 2.24%   |
| Amadora                      | 33        | 2.24%   |
| Vila Nova de Gaia            | 32        | 2.18%   |
| Braga                        | 30        | 2.04%   |
| Coimbra                      | 27        | 1.84%   |
| Setúbal                     | 23        | 1.56%   |
| Aveiro                       | 23        | 1.56%   |
| Leiria                       | 21        | 1.43%   |
| Faro                         | 21        | 1.43%   |
| Cascais                      | 18        | 1.22%   |
| Loures                       | 17        | 1.16%   |
| Sintra                       | 13        | 0.88%   |
| Evora                        | 12        | 0.82%   |
| Bragança                    | 12        | 0.82%   |
| Almada                       | 12        | 0.82%   |
| Póvoa de Varzim             | 11        | 0.75%   |
| Mem Martins                  | 11        | 0.75%   |
| Guimaraes                    | 11        | 0.75%   |
| Viana do Castelo             | 10        | 0.68%   |
| Torres Vedras                | 10        | 0.68%   |
| Portimao                     | 10        | 0.68%   |
| Odivelas                     | 10        | 0.68%   |
| Amora                        | 10        | 0.68%   |
| Viseu                        | 9         | 0.61%   |
| Santarém                    | 9         | 0.61%   |
| Povoa de Santa Iria          | 9         | 0.61%   |
| Matosinhos Municipality      | 9         | 0.61%   |
| Alverca do Ribatejo          | 9         | 0.61%   |
| Trofa                        | 8         | 0.54%   |
| Maia                         | 8         | 0.54%   |
| Figueira da Foz Municipality | 8         | 0.54%   |
| Feira                        | 8         | 0.54%   |
| Cacem                        | 8         | 0.54%   |
| Vila Nova de Famalicao       | 7         | 0.48%   |
| Vila do Conde                | 7         | 0.48%   |
| Sao Joao da Madeira          | 7         | 0.48%   |
| Sao Domingos de Rana         | 7         | 0.48%   |
| Santo Tirso                  | 7         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 285       | 396    | 14.84%  |
| WDC                       | 263       | 422    | 13.69%  |
| Seagate                   | 234       | 374    | 12.18%  |
| Toshiba                   | 179       | 268    | 9.32%   |
| Kingston                  | 177       | 230    | 9.21%   |
| SanDisk                   | 88        | 106    | 4.58%   |
| Unknown                   | 84        | 122    | 4.37%   |
| Crucial                   | 78        | 101    | 4.06%   |
| Hitachi                   | 74        | 85     | 3.85%   |
| HGST                      | 42        | 57     | 2.19%   |
| Intel                     | 39        | 61     | 2.03%   |
| SK hynix                  | 31        | 36     | 1.61%   |
| Micron Technology         | 23        | 27     | 1.2%    |
| Maxtor                    | 21        | 35     | 1.09%   |
| KIOXIA                    | 21        | 37     | 1.09%   |
| Fujitsu                   | 21        | 22     | 1.09%   |
| GOODRAM                   | 18        | 21     | 0.94%   |
| Apple                     | 14        | 14     | 0.73%   |
| PNY                       | 13        | 18     | 0.68%   |
| BlueRay                   | 12        | 14     | 0.62%   |
| Phison                    | 10        | 16     | 0.52%   |
| A-DATA Technology         | 10        | 10     | 0.52%   |
| KIOXIA-EXCERIA            | 9         | 10     | 0.47%   |
| China                     | 9         | 10     | 0.47%   |
| S3+                       | 8         | 17     | 0.42%   |
| JMicron Technology        | 8         | 8      | 0.42%   |
| LITEON                    | 7         | 8      | 0.36%   |
| Hewlett-Packard           | 7         | 8      | 0.36%   |
| Emtec                     | 7         | 8      | 0.36%   |
| Unknown                   | 7         | 8      | 0.36%   |
| Transcend                 | 6         | 7      | 0.31%   |
| Micron/Crucial Technology | 6         | 11     | 0.31%   |
| Team                      | 5         | 6      | 0.26%   |
| Silicon Motion            | 5         | 5      | 0.26%   |
| Phison Electronics        | 5         | 6      | 0.26%   |
| OCZ                       | 5         | 5      | 0.26%   |
| KingDian                  | 4         | 7      | 0.21%   |
| Gigabyte Technology       | 4         | 5      | 0.21%   |
| ExcelStor                 | 4         | 4      | 0.21%   |
| Vaseky                    | 3         | 3      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 32        | 1.56%   |
| Kingston SA400S37120G 120GB SSD                     | 26        | 1.26%   |
| Unknown MMC Card  32GB                              | 24        | 1.17%   |
| Toshiba MQ01ABD100 1TB                              | 19        | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 19        | 0.92%   |
| Kingston SV300S37A120G 120GB SSD                    | 19        | 0.92%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.92%   |
| Seagate ST1000DM010-2EP102 1TB                      | 15        | 0.73%   |
| Seagate ST500LT012-1DG142 500GB                     | 14        | 0.68%   |
| Samsung SSD 850 EVO 250GB                           | 14        | 0.68%   |
| Kingston SA400S37480G 480GB SSD                     | 14        | 0.68%   |
| Crucial CT240M500SSD1 240GB                         | 14        | 0.68%   |
| Unknown MMC Card  64GB                              | 13        | 0.63%   |
| Toshiba MQ01ABF050 500GB                            | 13        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                      | 13        | 0.63%   |
| Samsung SSD 860 EVO 500GB                           | 13        | 0.63%   |
| Kingston SV300S37A240G 240GB SSD                    | 13        | 0.63%   |
| Seagate ST9500325AS 500GB                           | 12        | 0.58%   |
| Unknown MMC64G  64GB                                | 11        | 0.53%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 10        | 0.49%   |
| Seagate ST3500418AS 500GB                           | 10        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                        | 10        | 0.49%   |
| Samsung NVMe SSD Drive 512GB                        | 10        | 0.49%   |
| Crucial CT240BX500SSD1 240GB                        | 10        | 0.49%   |
| Samsung SSD 840 EVO 250GB                           | 9         | 0.44%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.44%   |
| Crucial CT500MX500SSD1 500GB                        | 9         | 0.44%   |
| Toshiba HDWD110 1TB                                 | 8         | 0.39%   |
| Seagate Expansion+ 2TB                              | 8         | 0.39%   |
| SanDisk NVMe SSD Drive 256GB                        | 8         | 0.39%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 8         | 0.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 8         | 0.39%   |
| Toshiba TR200 240GB SSD                             | 7         | 0.34%   |
| Toshiba MQ04ABF100 1TB                              | 7         | 0.34%   |
| SK hynix NVMe SSD Drive 256GB                       | 7         | 0.34%   |
| Samsung SSD 860 QVO 1TB                             | 7         | 0.34%   |
| Kingston SUV400S37240G 240GB SSD                    | 7         | 0.34%   |
| Kingston SUV400S37120G 120GB SSD                    | 7         | 0.34%   |
| Kingston NVMe SSD Drive 512GB                       | 7         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 228       | 364    | 28.79%  |
| WDC                 | 201       | 312    | 25.38%  |
| Toshiba             | 132       | 209    | 16.67%  |
| Hitachi             | 74        | 85     | 9.34%   |
| Samsung Electronics | 57        | 78     | 7.2%    |
| HGST                | 42        | 57     | 5.3%    |
| Fujitsu             | 20        | 21     | 2.53%   |
| Maxtor              | 17        | 24     | 2.15%   |
| ExcelStor           | 4         | 4      | 0.51%   |
| Apple               | 3         | 3      | 0.38%   |
| USB                 | 2         | 2      | 0.25%   |
| MSFT                | 2         | 12     | 0.25%   |
| Dell                | 2         | 4      | 0.25%   |
| ASMedia             | 2         | 3      | 0.25%   |
| USB3.0              | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |
| Quantum             | 1         | 1      | 0.13%   |
| HPE                 | 1         | 4      | 0.13%   |
| Hewlett-Packard     | 1         | 2      | 0.13%   |
| ASMT                | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 155       | 196    | 23.56%  |
| Samsung Electronics | 127       | 173    | 19.3%   |
| Crucial             | 74        | 96     | 11.25%  |
| SanDisk             | 46        | 55     | 6.99%   |
| WDC                 | 34        | 52     | 5.17%   |
| Toshiba             | 27        | 36     | 4.1%    |
| GOODRAM             | 16        | 19     | 2.43%   |
| Intel               | 12        | 15     | 1.82%   |
| BlueRay             | 10        | 11     | 1.52%   |
| Apple               | 10        | 10     | 1.52%   |
| A-DATA Technology   | 10        | 10     | 1.52%   |
| PNY                 | 9         | 13     | 1.37%   |
| China               | 9         | 10     | 1.37%   |
| S3+                 | 8         | 17     | 1.22%   |
| SK hynix            | 7         | 7      | 1.06%   |
| Emtec               | 7         | 8      | 1.06%   |
| Transcend           | 6         | 7      | 0.91%   |
| Micron Technology   | 6         | 9      | 0.91%   |
| Hewlett-Packard     | 6         | 6      | 0.91%   |
| Team                | 5         | 6      | 0.76%   |
| OCZ                 | 5         | 5      | 0.76%   |
| LITEON              | 5         | 6      | 0.76%   |
| KIOXIA-EXCERIA      | 5         | 5      | 0.76%   |
| JMicron Technology  | 5         | 5      | 0.76%   |
| Unknown             | 4         | 4      | 0.61%   |
| Seagate             | 4         | 6      | 0.61%   |
| Maxtor              | 4         | 11     | 0.61%   |
| KingDian            | 4         | 7      | 0.61%   |
| Vaseky              | 3         | 3      | 0.46%   |
| Netac               | 3         | 3      | 0.46%   |
| Gigabyte Technology | 3         | 3      | 0.46%   |
| 2-Power             | 3         | 4      | 0.46%   |
| TCSUNBOW            | 2         | 2      | 0.3%    |
| Unknown             | 2         | 2      | 0.3%    |
| Zheino              | 1         | 2      | 0.15%   |
| XrayDisk            | 1         | 2      | 0.15%   |
| Verbatim            | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 1      | 0.15%   |
| Teclast             | 1         | 1      | 0.15%   |
| TEAM T25            | 1         | 1      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 680       | 1188   | 39.4%   |
| SSD     | 583       | 846    | 33.78%  |
| NVMe    | 361       | 532    | 20.92%  |
| MMC     | 81        | 119    | 4.69%   |
| Unknown | 21        | 24     | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1043      | 1993   | 67.82%  |
| NVMe | 361       | 529    | 23.47%  |
| MMC  | 81        | 119    | 5.27%   |
| SAS  | 53        | 68     | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 846       | 1334   | 67.79%  |
| 0.51-1.0   | 302       | 452    | 24.2%   |
| 1.01-2.0   | 58        | 91     | 4.65%   |
| 2.01-3.0   | 15        | 21     | 1.2%    |
| 4.01-10.0  | 14        | 22     | 1.12%   |
| 3.01-4.0   | 10        | 25     | 0.8%    |
| 10.01-20.0 | 2         | 88     | 0.16%   |
| 0          | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 418       | 28.71%  |
| 251-500        | 337       | 23.15%  |
| 501-1000       | 187       | 12.84%  |
| 51-100         | 124       | 8.52%   |
| 1-20           | 111       | 7.62%   |
| 1001-2000      | 90        | 6.18%   |
| 21-50          | 70        | 4.81%   |
| More than 3000 | 48        | 3.3%    |
| 2001-3000      | 37        | 2.54%   |
| Unknown        | 34        | 2.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 627       | 41.66%  |
| 21-50          | 279       | 18.54%  |
| 101-250        | 170       | 11.3%   |
| 51-100         | 158       | 10.5%   |
| 251-500        | 98        | 6.51%   |
| 501-1000       | 62        | 4.12%   |
| 1001-2000      | 48        | 3.19%   |
| Unknown        | 34        | 2.26%   |
| More than 3000 | 16        | 1.06%   |
| 2001-3000      | 13        | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB        | 13        | 13     | 10.24%  |
| Kingston SV300S37A120G 120GB SSD   | 6         | 6      | 4.72%   |
| Seagate ST9500325AS 500GB          | 3         | 3      | 2.36%   |
| Seagate ST3500418AS 500GB          | 3         | 3      | 2.36%   |
| WDC WD800JD-60LSA0 80GB            | 2         | 2      | 1.57%   |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 2      | 1.57%   |
| Toshiba MK2552GSX 250GB            | 2         | 2      | 1.57%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 1.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 1.57%   |
| Samsung Electronics HD252HJ 250GB  | 2         | 2      | 1.57%   |
| Kingston SV300S37A240G 240GB SSD   | 2         | 2      | 1.57%   |
| Kingston SUV400S37240G 240GB SSD   | 2         | 2      | 1.57%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.57%   |
| HGST HTS721010A9E630 1TB           | 2         | 2      | 1.57%   |
| WDC WD6400AADS-00M2B0 640GB        | 1         | 1      | 0.79%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 0.79%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 0.79%   |
| WDC WD5000BPVT-22HXZT1 500GB       | 1         | 1      | 0.79%   |
| WDC WD5000AZRX-00A3KB0 500GB       | 1         | 1      | 0.79%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1         | 1      | 0.79%   |
| WDC WD5000AAKS-00A7B0 500GB        | 1         | 4      | 0.79%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 2      | 0.79%   |
| WDC WD3200BEVT-22A23T0 320GB       | 1         | 1      | 0.79%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1         | 1      | 0.79%   |
| WDC WD30EZRS-11J99B1 3TB           | 1         | 1      | 0.79%   |
| WDC WD2500JS-40TGB0 250GB          | 1         | 1      | 0.79%   |
| WDC WD20EARS-00MVWB0 2TB           | 1         | 1      | 0.79%   |
| WDC WD10JPVT-22A1YT0 1TB           | 1         | 1      | 0.79%   |
| WDC WD10EZRZ-00Z5HB0 1TB           | 1         | 1      | 0.79%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1         | 1      | 0.79%   |
| WDC WD10EAVS-00D7B1 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EARS-00Y5B1 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EALX-009BA0 1TB            | 1         | 1      | 0.79%   |
| WDC WD10EADS-11M2B1 1TB            | 1         | 1      | 0.79%   |
| WDC WD1002FBYS-02A6B0 1TB          | 1         | 1      | 0.79%   |
| WDC WD1001FALS-00J7B0 1TB          | 1         | 4      | 0.79%   |
| USB 3.1 120GB                      | 1         | 1      | 0.79%   |
| Unknown FM-25S2S-60GBP2 64GB SSD   | 1         | 1      | 0.79%   |
| Toshiba Q300. 240GB SSD            | 1         | 1      | 0.79%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 0.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 20.97%  |
| Seagate             | 21        | 24     | 16.94%  |
| Hitachi             | 15        | 15     | 12.1%   |
| Crucial             | 15        | 15     | 12.1%   |
| Kingston            | 11        | 11     | 8.87%   |
| Toshiba             | 10        | 11     | 8.06%   |
| Samsung Electronics | 8         | 10     | 6.45%   |
| Maxtor              | 4         | 7      | 3.23%   |
| HGST                | 2         | 2      | 1.61%   |
| USB                 | 1         | 1      | 0.81%   |
| Unknown             | 1         | 1      | 0.81%   |
| SK hynix            | 1         | 1      | 0.81%   |
| SanDisk             | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| KingDian            | 1         | 2      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| HP Phison           | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |
| China               | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |
| A-DATA Technology   | 1         | 1      | 0.81%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 30.23%  |
| Seagate             | 21        | 24     | 24.42%  |
| Hitachi             | 15        | 15     | 17.44%  |
| Toshiba             | 9         | 10     | 10.47%  |
| Samsung Electronics | 6         | 7      | 6.98%   |
| Maxtor              | 4         | 7      | 4.65%   |
| HGST                | 2         | 2      | 2.33%   |
| USB                 | 1         | 1      | 1.16%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 101    | 68.33%  |
| SSD  | 38        | 40     | 31.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750640NS 752GB | 1         | 1      | 50%     |
| HGST HTS541010B7E610 1TB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 936       | 1867   | 63.5%   |
| Works    | 419       | 699    | 28.43%  |
| Malfunc  | 117       | 141    | 7.94%   |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 914       | 56%     |
| AMD                              | 234       | 14.34%  |
| Samsung Electronics              | 121       | 7.41%   |
| SanDisk                          | 70        | 4.29%   |
| Kingston Technology Company      | 27        | 1.65%   |
| Nvidia                           | 25        | 1.53%   |
| JMicron Technology               | 24        | 1.47%   |
| Toshiba America Info Systems     | 23        | 1.41%   |
| KIOXIA                           | 23        | 1.41%   |
| SK hynix                         | 22        | 1.35%   |
| Phison Electronics               | 20        | 1.23%   |
| Micron Technology                | 18        | 1.1%    |
| ASMedia Technology               | 17        | 1.04%   |
| Silicon Integrated Systems [SiS] | 15        | 0.92%   |
| VIA Technologies                 | 13        | 0.8%    |
| Marvell Technology Group         | 13        | 0.8%    |
| Micron/Crucial Technology        | 10        | 0.61%   |
| Union Memory (Shenzhen)          | 6         | 0.37%   |
| LSI Logic / Symbios Logic        | 6         | 0.37%   |
| Silicon Motion                   | 5         | 0.31%   |
| Lite-On Technology               | 5         | 0.31%   |
| Shenzhen Longsys Electronics     | 3         | 0.18%   |
| Hewlett-Packard                  | 3         | 0.18%   |
| ADATA Technology                 | 3         | 0.18%   |
| Solid State Storage Technology   | 2         | 0.12%   |
| Realtek Semiconductor            | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| Adaptec                          | 2         | 0.12%   |
| ULi Electronics                  | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Enmotus                          | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 162       | 8.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 66        | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 64        | 3.3%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 60        | 3.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 58        | 2.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 53        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 50        | 2.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 48        | 2.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 46        | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 43        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43        | 2.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 42        | 2.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41        | 2.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 36        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 27        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26        | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 1.24%   |
| Samsung NVMe SSD Controller 980                                                         | 22        | 1.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 22        | 1.13%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22        | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 21        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 20        | 1.03%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 19        | 0.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 19        | 0.98%   |
| Micron NVMe Storage Controller                                                          | 18        | 0.93%   |
| Intel SSD 660P Series                                                                   | 18        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 17        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 16        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 0.82%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 15        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 15        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 14        | 0.72%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 0.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14        | 0.72%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 13        | 0.67%   |
| Phison E12 NVMe Controller                                                              | 13        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 950       | 56.05%  |
| NVMe | 363       | 21.42%  |
| IDE  | 282       | 16.64%  |
| RAID | 95        | 5.6%    |
| SCSI | 3         | 0.18%   |
| SAS  | 2         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1077      | 78.04%  |
| AMD    | 294       | 21.3%   |
| ARM    | 9         | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 24        | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 20        | 1.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 18        | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 0.94%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 13        | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 0.87%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 11        | 0.8%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 0.8%    |
| AMD 3020e with Radeon Graphics                | 11        | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.65%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 9         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.65%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 9         | 0.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.58%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.58%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 8         | 0.58%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.58%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 7         | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.51%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.51%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 7         | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 7         | 0.51%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 7         | 0.51%   |
| ARM Processor                                 | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 271       | 19.61%  |
| Intel Core i5           | 253       | 18.31%  |
| Intel Core i3           | 93        | 6.73%   |
| Intel Core 2 Duo        | 91        | 6.58%   |
| Other                   | 84        | 6.08%   |
| AMD Ryzen 5             | 75        | 5.43%   |
| AMD Ryzen 7             | 62        | 4.49%   |
| Intel Celeron           | 54        | 3.91%   |
| Intel Atom              | 46        | 3.33%   |
| Intel Pentium Dual-Core | 39        | 2.82%   |
| Intel Pentium Dual      | 28        | 2.03%   |
| Intel Pentium           | 26        | 1.88%   |
| AMD FX                  | 26        | 1.88%   |
| Intel Xeon              | 25        | 1.81%   |
| Intel Core 2 Quad       | 22        | 1.59%   |
| Intel Core 2            | 21        | 1.52%   |
| Intel Genuine           | 14        | 1.01%   |
| Intel Pentium 4         | 13        | 0.94%   |
| AMD A4                  | 13        | 0.94%   |
| AMD A6                  | 12        | 0.87%   |
| AMD Ryzen 3             | 11        | 0.8%    |
| AMD A8                  | 10        | 0.72%   |
| AMD Ryzen 9             | 8         | 0.58%   |
| AMD A10                 | 8         | 0.58%   |
| AMD E2                  | 7         | 0.51%   |
| Intel Pentium D         | 6         | 0.43%   |
| Intel Pentium M         | 5         | 0.36%   |
| AMD E                   | 5         | 0.36%   |
| AMD Athlon              | 5         | 0.36%   |
| Intel Core i9           | 3         | 0.22%   |
| AMD Ryzen 7 PRO         | 3         | 0.22%   |
| AMD Athlon II X3        | 3         | 0.22%   |
| AMD Athlon II X2        | 3         | 0.22%   |
| AMD Athlon 64           | 3         | 0.22%   |
| Intel Pentium Gold      | 2         | 0.14%   |
| Intel Core m3           | 2         | 0.14%   |
| Intel Celeron M         | 2         | 0.14%   |
| ARM BCM                 | 2         | 0.14%   |
| AMD Ryzen Threadripper  | 2         | 0.14%   |
| AMD Mobile Sempron      | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 619       | 44.76%  |
| 4       | 477       | 34.49%  |
| 6       | 113       | 8.17%   |
| 8       | 79        | 5.71%   |
| 1       | 51        | 3.69%   |
| 3       | 14        | 1.01%   |
| 12      | 7         | 0.51%   |
| 10      | 7         | 0.51%   |
| 16      | 5         | 0.36%   |
| Unknown | 5         | 0.36%   |
| 14      | 4         | 0.29%   |
| 36      | 1         | 0.07%   |
| 24      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1369      | 99.2%   |
| 2       | 7         | 0.51%   |
| Unknown | 4         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 840       | 60.78%  |
| 1       | 537       | 38.86%  |
| Unknown | 5         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1311      | 94.32%  |
| Unknown        | 49        | 3.53%   |
| 32-bit         | 23        | 1.65%   |
| 64-bit         | 7         | 0.5%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 337       | 23.52%  |
| 0x1067a    | 72        | 5.02%   |
| 0x306a9    | 70        | 4.88%   |
| 0x206a7    | 70        | 4.88%   |
| 0x906ea    | 40        | 2.79%   |
| 0x10676    | 40        | 2.79%   |
| 0x806ec    | 37        | 2.58%   |
| 0x306c3    | 36        | 2.51%   |
| 0x6fd      | 34        | 2.37%   |
| 0x806ea    | 33        | 2.3%    |
| 0x506e3    | 29        | 2.02%   |
| 0x806c1    | 27        | 1.88%   |
| 0x40651    | 26        | 1.81%   |
| 0x20655    | 23        | 1.61%   |
| 0x306d4    | 21        | 1.47%   |
| 0x406e3    | 20        | 1.4%    |
| 0x20652    | 19        | 1.33%   |
| 0x30678    | 18        | 1.26%   |
| 0x806eb    | 17        | 1.19%   |
| 0x906e9    | 16        | 1.12%   |
| 0x806e9    | 16        | 1.12%   |
| 0x406c4    | 15        | 1.05%   |
| 0x06000852 | 15        | 1.05%   |
| 0x6fb      | 14        | 0.98%   |
| 0x6f6      | 13        | 0.91%   |
| 0x106e5    | 13        | 0.91%   |
| 0x08108109 | 13        | 0.91%   |
| 0x08701021 | 12        | 0.84%   |
| 0x406c3    | 11        | 0.77%   |
| 0x0a50000c | 11        | 0.77%   |
| 0x08200103 | 11        | 0.77%   |
| 0x0800820d | 11        | 0.77%   |
| 0xa0652    | 10        | 0.7%    |
| 0x08108102 | 9         | 0.63%   |
| 0x106ca    | 8         | 0.56%   |
| 0x08600106 | 8         | 0.56%   |
| 0x08600104 | 8         | 0.56%   |
| 0x07030105 | 8         | 0.56%   |
| 0x906a3    | 6         | 0.42%   |
| 0x706e5    | 6         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 198       | 14.33%  |
| Penryn           | 139       | 10.06%  |
| Haswell          | 94        | 6.8%    |
| IvyBridge        | 87        | 6.3%    |
| Core             | 86        | 6.22%   |
| SandyBridge      | 84        | 6.08%   |
| Skylake          | 71        | 5.14%   |
| Silvermont       | 59        | 4.27%   |
| Westmere         | 55        | 3.98%   |
| Zen 2            | 46        | 3.33%   |
| Zen+             | 44        | 3.18%   |
| Zen 3            | 39        | 2.82%   |
| TigerLake        | 37        | 2.68%   |
| Zen              | 35        | 2.53%   |
| Broadwell        | 30        | 2.17%   |
| Unknown          | 29        | 2.1%    |
| Piledriver       | 27        | 1.95%   |
| CometLake        | 24        | 1.74%   |
| NetBurst         | 21        | 1.52%   |
| Excavator        | 18        | 1.3%    |
| Bonnell          | 18        | 1.3%    |
| Puma             | 17        | 1.23%   |
| Nehalem          | 16        | 1.16%   |
| K10              | 14        | 1.01%   |
| P6               | 13        | 0.94%   |
| IceLake          | 12        | 0.87%   |
| Jaguar           | 10        | 0.72%   |
| Steamroller      | 9         | 0.65%   |
| K8 Hammer        | 9         | 0.65%   |
| Goldmont plus    | 9         | 0.65%   |
| Alderlake Hybrid | 9         | 0.65%   |
| Bobcat           | 7         | 0.51%   |
| Goldmont         | 6         | 0.43%   |
| K8 & K10 hybrid  | 4         | 0.29%   |
| Bulldozer        | 3         | 0.22%   |
| K10 Llano        | 2         | 0.14%   |
| Tremont          | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 764       | 45.02%  |
| Nvidia                           | 510       | 30.05%  |
| AMD                              | 406       | 23.92%  |
| Silicon Integrated Systems [SiS] | 11        | 0.65%   |
| Matrox Electronics Systems       | 3         | 0.18%   |
| ASPEED Technology                | 3         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 3.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 54        | 3.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 2.15%   |
| Intel UHD Graphics 620                                                                   | 37        | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 1.93%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 1.59%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 1.47%   |
| AMD Renoir                                                                               | 26        | 1.47%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.36%   |
| Intel HD Graphics 530                                                                    | 24        | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 23        | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 23        | 1.3%    |
| Intel HD Graphics 620                                                                    | 21        | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1.19%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 20        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.08%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 19        | 1.08%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 17        | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 14        | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.74%   |
| Intel HD Graphics 630                                                                    | 13        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.74%   |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 0.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.62%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.62%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.62%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 11        | 0.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 481       | 34.6%   |
| 1 x AMD         | 304       | 21.87%  |
| 1 x Nvidia      | 249       | 17.91%  |
| Intel + Nvidia  | 224       | 16.12%  |
| Intel + AMD     | 46        | 3.31%   |
| AMD + Nvidia    | 31        | 2.23%   |
| 2 x AMD         | 26        | 1.87%   |
| 1 x SiS         | 11        | 0.79%   |
| Other           | 9         | 0.65%   |
| 2 x Nvidia      | 2         | 0.14%   |
| Nvidia + ASPEED | 2         | 0.14%   |
| 1 x Matrox      | 2         | 0.14%   |
| 2 x Intel       | 1         | 0.07%   |
| Nvidia + Matrox | 1         | 0.07%   |
| 1 x ASPEED      | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1093      | 78.02%  |
| Proprietary | 244       | 17.42%  |
| Unknown     | 64        | 4.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 736       | 51.83%  |
| 0.01-0.5   | 227       | 15.99%  |
| 1.01-2.0   | 183       | 12.89%  |
| 0.51-1.0   | 123       | 8.66%   |
| 3.01-4.0   | 79        | 5.56%   |
| 7.01-8.0   | 34        | 2.39%   |
| 5.01-6.0   | 26        | 1.83%   |
| 8.01-16.0  | 7         | 0.49%   |
| 2.01-3.0   | 5         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 207       | 14.28%  |
| Samsung Electronics     | 181       | 12.48%  |
| Chimei Innolux          | 144       | 9.93%   |
| LG Display              | 123       | 8.48%   |
| BOE                     | 110       | 7.59%   |
| Goldstar                | 104       | 7.17%   |
| Hewlett-Packard         | 70        | 4.83%   |
| Ancor Communications    | 69        | 4.76%   |
| Dell                    | 40        | 2.76%   |
| Apple                   | 32        | 2.21%   |
| AOC                     | 31        | 2.14%   |
| Chi Mei Optoelectronics | 30        | 2.07%   |
| BenQ                    | 27        | 1.86%   |
| Philips                 | 24        | 1.66%   |
| Lenovo                  | 24        | 1.66%   |
| LG Philips              | 21        | 1.45%   |
| PANDA                   | 18        | 1.24%   |
| Acer                    | 16        | 1.1%    |
| Sony                    | 14        | 0.97%   |
| Sharp                   | 14        | 0.97%   |
| ASUSTek Computer        | 14        | 0.97%   |
| LG Electronics          | 12        | 0.83%   |
| Unknown                 | 11        | 0.76%   |
| MSI                     | 7         | 0.48%   |
| CPT                     | 7         | 0.48%   |
| Seiko/Epson             | 6         | 0.41%   |
| InfoVision              | 6         | 0.41%   |
| ViewSonic               | 5         | 0.34%   |
| Toshiba                 | 4         | 0.28%   |
| HUAWEI                  | 4         | 0.28%   |
| HPN                     | 4         | 0.28%   |
| HannStar                | 4         | 0.28%   |
| Fujitsu Siemens         | 4         | 0.28%   |
| Mi                      | 3         | 0.21%   |
| LGD                     | 3         | 0.21%   |
| Lenovo Group Limited    | 3         | 0.21%   |
| CSO                     | 3         | 0.21%   |
| ___                     | 2         | 0.14%   |
| Vestel Elektronik       | 2         | 0.14%   |
| RTK                     | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 12        | 0.8%    |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 11        | 0.74%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 6         | 0.4%    |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 6         | 0.4%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.4%    |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch         | 6         | 0.4%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 6         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.34%   |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.34%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.34%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 5         | 0.34%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.34%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 4         | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.27%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                      | 4         | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.27%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 4         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 545       | 39.69%  |
| 1366x768 (WXGA)    | 347       | 25.27%  |
| 1280x1024 (SXGA)   | 74        | 5.39%   |
| 3840x2160 (4K)     | 68        | 4.95%   |
| 1280x800 (WXGA)    | 60        | 4.37%   |
| 1600x900 (HD+)     | 41        | 2.99%   |
| 1440x900 (WXGA+)   | 39        | 2.84%   |
| 1680x1050 (WSXGA+) | 36        | 2.62%   |
| 2560x1440 (QHD)    | 34        | 2.48%   |
| 1920x1200 (WUXGA)  | 19        | 1.38%   |
| 2560x1080          | 12        | 0.87%   |
| 1360x768           | 12        | 0.87%   |
| Unknown            | 12        | 0.87%   |
| 1024x768 (XGA)     | 9         | 0.66%   |
| 3440x1440          | 8         | 0.58%   |
| 2160x1440          | 6         | 0.44%   |
| 1024x600           | 6         | 0.44%   |
| 2560x1600          | 5         | 0.36%   |
| 3840x2400          | 4         | 0.29%   |
| 3840x1080          | 4         | 0.29%   |
| 2880x1800          | 4         | 0.29%   |
| 3200x1800 (QHD+)   | 3         | 0.22%   |
| 2288x1287          | 3         | 0.22%   |
| 1400x1050          | 3         | 0.22%   |
| 1152x864           | 3         | 0.22%   |
| 640x480            | 1         | 0.07%   |
| 4560x1080          | 1         | 0.07%   |
| 4480x1600          | 1         | 0.07%   |
| 3520x1080          | 1         | 0.07%   |
| 3360x1080          | 1         | 0.07%   |
| 3360x1050          | 1         | 0.07%   |
| 3280x1080          | 1         | 0.07%   |
| 3240x2160          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2944x1080          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2726x768           | 1         | 0.07%   |
| 2560x2520          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 479       | 33.01%  |
| 13      | 121       | 8.34%   |
| 14      | 120       | 8.27%   |
| 21      | 95        | 6.55%   |
| 24      | 91        | 6.27%   |
| 17      | 82        | 5.65%   |
| Unknown | 72        | 4.96%   |
| 23      | 69        | 4.76%   |
| 27      | 68        | 4.69%   |
| 19      | 46        | 3.17%   |
| 18      | 27        | 1.86%   |
| 20      | 21        | 1.45%   |
| 34      | 19        | 1.31%   |
| 12      | 18        | 1.24%   |
| 11      | 17        | 1.17%   |
| 31      | 16        | 1.1%    |
| 22      | 16        | 1.1%    |
| 10      | 12        | 0.83%   |
| 16      | 10        | 0.69%   |
| 84      | 9         | 0.62%   |
| 54      | 6         | 0.41%   |
| 40      | 6         | 0.41%   |
| 25      | 6         | 0.41%   |
| 72      | 5         | 0.34%   |
| 33      | 3         | 0.21%   |
| 32      | 3         | 0.21%   |
| 26      | 3         | 0.21%   |
| 46      | 2         | 0.14%   |
| 28      | 2         | 0.14%   |
| 142     | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 691       | 48.53%  |
| 501-600        | 211       | 14.82%  |
| 401-500        | 176       | 12.36%  |
| 201-300        | 106       | 7.44%   |
| 351-400        | 81        | 5.69%   |
| Unknown        | 72        | 5.06%   |
| 601-700        | 27        | 1.9%    |
| 701-800        | 26        | 1.83%   |
| 1501-2000      | 14        | 0.98%   |
| 1001-1500      | 10        | 0.7%    |
| 801-900        | 7         | 0.49%   |
| More than 2000 | 1         | 0.07%   |
| 101-200        | 1         | 0.07%   |
| 901-1000       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 959       | 73.15%  |
| 16/10   | 163       | 12.43%  |
| 5/4     | 64        | 4.88%   |
| Unknown | 64        | 4.88%   |
| 4/3     | 24        | 1.83%   |
| 21/9    | 19        | 1.45%   |
| 3/2     | 13        | 0.99%   |
| 6/5     | 3         | 0.23%   |
| 32/9    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 472       | 32.73%  |
| 201-250        | 228       | 15.81%  |
| 81-90          | 192       | 13.31%  |
| 151-200        | 89        | 6.17%   |
| Unknown        | 72        | 4.99%   |
| 301-350        | 70        | 4.85%   |
| 141-150        | 63        | 4.37%   |
| 71-80          | 48        | 3.33%   |
| 351-500        | 40        | 2.77%   |
| 121-130        | 32        | 2.22%   |
| 251-300        | 27        | 1.87%   |
| More than 1000 | 23        | 1.6%    |
| 61-70          | 18        | 1.25%   |
| 51-60          | 17        | 1.18%   |
| 111-120        | 13        | 0.9%    |
| 41-50          | 12        | 0.83%   |
| 501-1000       | 12        | 0.83%   |
| 131-140        | 9         | 0.62%   |
| 91-100         | 4         | 0.28%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 452       | 32.29%  |
| 101-120       | 430       | 30.71%  |
| 121-160       | 352       | 25.14%  |
| Unknown       | 72        | 5.14%   |
| 161-240       | 58        | 4.14%   |
| More than 240 | 20        | 1.43%   |
| 1-50          | 16        | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1108      | 78.3%   |
| 2     | 198       | 13.99%  |
| 0     | 81        | 5.72%   |
| 3     | 24        | 1.7%    |
| 4     | 4         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 745       | 35.82%  |
| Intel                             | 555       | 26.68%  |
| Qualcomm Atheros                  | 314       | 15.1%   |
| Broadcom                          | 138       | 6.63%   |
| Marvell Technology Group          | 53        | 2.55%   |
| TP-Link                           | 41        | 1.97%   |
| Broadcom Limited                  | 25        | 1.2%    |
| Nvidia                            | 22        | 1.06%   |
| Qualcomm Atheros Communications   | 18        | 0.87%   |
| MediaTek                          | 18        | 0.87%   |
| Ralink                            | 16        | 0.77%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.72%   |
| Ralink Technology                 | 13        | 0.63%   |
| D-Link                            | 9         | 0.43%   |
| ASIX Electronics                  | 7         | 0.34%   |
| ASUSTek Computer                  | 6         | 0.29%   |
| VIA Technologies                  | 5         | 0.24%   |
| Sierra Wireless                   | 5         | 0.24%   |
| Samsung Electronics               | 5         | 0.24%   |
| JMicron Technology                | 4         | 0.19%   |
| Ericsson Business Mobile Networks | 4         | 0.19%   |
| Attansic Technology               | 4         | 0.19%   |
| Lenovo                            | 3         | 0.14%   |
| ICS Advent                        | 3         | 0.14%   |
| Hewlett-Packard                   | 3         | 0.14%   |
| Edimax Technology                 | 3         | 0.14%   |
| DisplayLink                       | 3         | 0.14%   |
| D-Link System                     | 3         | 0.14%   |
| TRENDnet                          | 2         | 0.1%    |
| Mellanox Technologies             | 2         | 0.1%    |
| Huawei Technologies               | 2         | 0.1%    |
| Fibocom                           | 2         | 0.1%    |
| Dresden Elektronik                | 2         | 0.1%    |
| Dell                              | 2         | 0.1%    |
| Belkin Components                 | 2         | 0.1%    |
| ADMtek                            | 2         | 0.1%    |
| Accton Technology                 | 2         | 0.1%    |
| Xiaomi                            | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 507       | 21.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 115       | 4.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 1.95%   |
| Intel Wi-Fi 6 AX200                                                     | 41        | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 39        | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 34        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 1.33%   |
| Intel Wireless 8265 / 8275                                              | 32        | 1.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 27        | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.08%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 25        | 1.04%   |
| Intel Wi-Fi 6 AX201                                                     | 25        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 1.04%   |
| Intel Wireless 7265                                                     | 24        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 22        | 0.91%   |
| Intel Wireless 7260                                                     | 21        | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 0.83%   |
| Intel Wireless 8260                                                     | 20        | 0.83%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 19        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 0.79%   |
| Intel Wireless 3165                                                     | 18        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                       | 17        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.67%   |
| Intel I211 Gigabit Network Connection                                   | 16        | 0.67%   |
| Intel 82579V Gigabit Network Connection                                 | 16        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 0.62%   |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 15        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 15        | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 14        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 447       | 39.95%  |
| Qualcomm Atheros                      | 257       | 22.97%  |
| Realtek Semiconductor                 | 179       | 16%     |
| Broadcom                              | 95        | 8.49%   |
| TP-Link                               | 23        | 2.06%   |
| Qualcomm Atheros Communications       | 18        | 1.61%   |
| MediaTek                              | 17        | 1.52%   |
| Ralink                                | 16        | 1.43%   |
| Broadcom Limited                      | 15        | 1.34%   |
| Ralink Technology                     | 13        | 1.16%   |
| D-Link                                | 9         | 0.8%    |
| ASUSTek Computer                      | 6         | 0.54%   |
| Sierra Wireless                       | 5         | 0.45%   |
| Edimax Technology                     | 3         | 0.27%   |
| TRENDnet                              | 2         | 0.18%   |
| Marvell Technology Group              | 2         | 0.18%   |
| Fibocom                               | 2         | 0.18%   |
| Dell                                  | 2         | 0.18%   |
| Belkin Components                     | 2         | 0.18%   |
| Sitecom Europe                        | 1         | 0.09%   |
| Microsoft                             | 1         | 0.09%   |
| Micro Star International              | 1         | 0.09%   |
| D-Link System                         | 1         | 0.09%   |
| Accton Technology                     | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 4.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 4.2%    |
| Intel Wi-Fi 6 AX200                                                     | 41        | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 39        | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 2.86%   |
| Intel Wireless 8265 / 8275                                              | 32        | 2.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 2.32%   |
| Intel Wi-Fi 6 AX201                                                     | 25        | 2.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 2.23%   |
| Intel Wireless 7265                                                     | 24        | 2.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 23        | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 22        | 1.96%   |
| Intel Wireless 7260                                                     | 21        | 1.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 20        | 1.79%   |
| Intel Wireless 8260                                                     | 20        | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 1.7%    |
| Intel Wireless 3165                                                     | 18        | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 17        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 1.34%   |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 1.25%   |
| Intel Wireless 3160                                                     | 13        | 1.16%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 0.98%   |
| Intel WiFi Link 5100                                                    | 10        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.89%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.71%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 688       | 55.17%  |
| Intel                            | 235       | 18.85%  |
| Qualcomm Atheros                 | 91        | 7.3%    |
| Broadcom                         | 61        | 4.89%   |
| Marvell Technology Group         | 51        | 4.09%   |
| Nvidia                           | 22        | 1.76%   |
| TP-Link                          | 19        | 1.52%   |
| Silicon Integrated Systems [SiS] | 15        | 1.2%    |
| Broadcom Limited                 | 10        | 0.8%    |
| ASIX Electronics                 | 7         | 0.56%   |
| VIA Technologies                 | 5         | 0.4%    |
| Samsung Electronics              | 5         | 0.4%    |
| JMicron Technology               | 4         | 0.32%   |
| Attansic Technology              | 4         | 0.32%   |
| Lenovo                           | 3         | 0.24%   |
| ICS Advent                       | 3         | 0.24%   |
| DisplayLink                      | 3         | 0.24%   |
| Mellanox Technologies            | 2         | 0.16%   |
| Hewlett-Packard                  | 2         | 0.16%   |
| D-Link System                    | 2         | 0.16%   |
| ADMtek                           | 2         | 0.16%   |
| Xiaomi                           | 1         | 0.08%   |
| T & A Mobile Phones              | 1         | 0.08%   |
| Standard Microsystems            | 1         | 0.08%   |
| Silicom                          | 1         | 0.08%   |
| Qualcomm                         | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| LSI                              | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| Archos                           | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |
| Allwinner Technology             | 1         | 0.08%   |
| Accton Technology                | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 507       | 40.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 115       | 9.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 34        | 2.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 27        | 2.14%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 25        | 1.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 19        | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                              | 17        | 1.34%   |
| Intel I211 Gigabit Network Connection                                          | 16        | 1.27%   |
| Intel 82579V Gigabit Network Connection                                        | 16        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 15        | 1.19%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 15        | 1.19%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 14        | 1.11%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 13        | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                           | 12        | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 11        | 0.87%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.71%   |
| Intel Ethernet Connection I217-LM                                              | 9         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 0.63%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 8         | 0.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.55%   |
| Intel Ethernet Connection (2) I218-V                                           | 7         | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 7         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.47%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.47%   |
| Nvidia MCP61 Ethernet                                                          | 6         | 0.47%   |
| Intel Ethernet Connection I219-LM                                              | 6         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                           | 6         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 6         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.4%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 5         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.4%    |
| Intel Ethernet Connection (14) I219-V                                          | 5         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 0.4%    |
| Intel 82573L Gigabit Ethernet Controller                                       | 5         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1197      | 52.11%  |
| WiFi     | 1078      | 46.93%  |
| Modem    | 20        | 0.87%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 844       | 58.61%  |
| Ethernet | 596       | 41.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 794       | 57.37%  |
| 1     | 541       | 39.09%  |
| 0     | 29        | 2.1%    |
| 3     | 12        | 0.87%   |
| 6     | 3         | 0.22%   |
| 10    | 2         | 0.14%   |
| 5     | 2         | 0.14%   |
| 4     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1065      | 75.42%  |
| Yes  | 347       | 24.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 317       | 40.43%  |
| Realtek Semiconductor           | 84        | 10.71%  |
| Qualcomm Atheros Communications | 55        | 7.02%   |
| IMC Networks                    | 53        | 6.76%   |
| Lite-On Technology              | 42        | 5.36%   |
| Foxconn / Hon Hai               | 37        | 4.72%   |
| Broadcom                        | 34        | 4.34%   |
| Cambridge Silicon Radio         | 33        | 4.21%   |
| Apple                           | 31        | 3.95%   |
| ASUSTek Computer                | 28        | 3.57%   |
| Toshiba                         | 18        | 2.3%    |
| Hewlett-Packard                 | 14        | 1.79%   |
| Realtek                         | 9         | 1.15%   |
| Dell                            | 9         | 1.15%   |
| Ralink                          | 5         | 0.64%   |
| Alps Electric                   | 4         | 0.51%   |
| TP-Link                         | 2         | 0.26%   |
| Ralink Technology               | 2         | 0.26%   |
| Marvell Semiconductor           | 2         | 0.26%   |
| Belkin Components               | 2         | 0.26%   |
| MediaTek                        | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Chicony Electronics             | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 126       | 16.07%  |
| Realtek Bluetooth Radio                                                             | 58        | 7.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 55        | 7.02%   |
| Intel AX201 Bluetooth                                                               | 54        | 6.89%   |
| Intel AX200 Bluetooth                                                               | 42        | 5.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 33        | 4.21%   |
| IMC Networks Bluetooth Device                                                       | 29        | 3.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 17        | 2.17%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 16        | 2.04%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 1.66%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.66%   |
| Apple Bluetooth Host Controller                                                     | 13        | 1.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.53%   |
| IMC Networks Bluetooth Radio                                                        | 11        | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 1.4%    |
| Lite-On Bluetooth Device                                                            | 10        | 1.28%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.28%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 10        | 1.28%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 1.28%   |
| Realtek Bluetooth Radio                                                             | 9         | 1.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.15%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 8         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.89%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.89%   |
| IMC Networks Wireless_Device                                                        | 7         | 0.89%   |
| Intel Bluetooth Device                                                              | 6         | 0.77%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.64%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.64%   |
| Lite-On BCM43142A0                                                                  | 5         | 0.64%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.64%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.64%   |
| Toshiba Integrated Bluetooth HCI                                                    | 4         | 0.51%   |
| Toshiba Askey Bluetooth Module                                                      | 4         | 0.51%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 4         | 0.51%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.51%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 4         | 0.51%   |
| ASUS ASUS USB-BT500                                                                 | 4         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 997       | 53.92%  |
| AMD                                  | 390       | 21.09%  |
| Nvidia                               | 284       | 15.36%  |
| C-Media Electronics                  | 23        | 1.24%   |
| Creative Labs                        | 20        | 1.08%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.81%   |
| Logitech                             | 11        | 0.59%   |
| Kingston Technology                  | 10        | 0.54%   |
| JMTek                                | 10        | 0.54%   |
| Realtek Semiconductor                | 7         | 0.38%   |
| Razer USA                            | 7         | 0.38%   |
| Texas Instruments                    | 6         | 0.32%   |
| GN Netcom                            | 5         | 0.27%   |
| Hewlett-Packard                      | 4         | 0.22%   |
| Creative Technology                  | 4         | 0.22%   |
| ASUSTek Computer                     | 4         | 0.22%   |
| Plantronics                          | 3         | 0.16%   |
| Generalplus Technology               | 3         | 0.16%   |
| Focusrite-Novation                   | 3         | 0.16%   |
| VIA Technologies                     | 2         | 0.11%   |
| SteelSeries ApS                      | 2         | 0.11%   |
| Micro Star International             | 2         | 0.11%   |
| Lenovo                               | 2         | 0.11%   |
| EGO SYStems                          | 2         | 0.11%   |
| DSEA A/S                             | 2         | 0.11%   |
| Corsair                              | 2         | 0.11%   |
| Apple                                | 2         | 0.11%   |
| XMOS                                 | 1         | 0.05%   |
| WinChipHead                          | 1         | 0.05%   |
| ULi Electronics                      | 1         | 0.05%   |
| Turtle Beach                         | 1         | 0.05%   |
| Trust                                | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Silicon Motion                       | 1         | 0.05%   |
| Sennheiser Communications            | 1         | 0.05%   |
| Samsung Electronics                  | 1         | 0.05%   |
| Samson Technologies                  | 1         | 0.05%   |
| Philips (or NXP)                     | 1         | 0.05%   |
| Microchip Technology                 | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 112       | 5.18%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 90        | 4.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 87        | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 77        | 3.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 73        | 3.38%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 68        | 3.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 68        | 3.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 61        | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 50        | 2.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 49        | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 47        | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 45        | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 42        | 1.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 41        | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 38        | 1.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 1.76%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 37        | 1.71%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 1.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 34        | 1.57%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 33        | 1.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 33        | 1.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 32        | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 32        | 1.48%   |
| Intel Broadwell-U Audio Controller                                                                | 29        | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 1.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 28        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 27        | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 27        | 1.25%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 24        | 1.11%   |
| Nvidia High Definition Audio Controller                                                           | 22        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 20        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 18        | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 17        | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 15        | 0.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 0.69%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 15        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 178       | 24.52%  |
| SK hynix            | 135       | 18.6%   |
| Unknown             | 108       | 14.88%  |
| Kingston            | 93        | 12.81%  |
| Micron Technology   | 55        | 7.58%   |
| G.Skill             | 38        | 5.23%   |
| Crucial             | 24        | 3.31%   |
| Corsair             | 22        | 3.03%   |
| Ramaxel Technology  | 14        | 1.93%   |
| A-DATA Technology   | 9         | 1.24%   |
| Team                | 8         | 1.1%    |
| Elpida              | 8         | 1.1%    |
| Nanya Technology    | 6         | 0.83%   |
| Transcend           | 4         | 0.55%   |
| Unknown (ABCD)      | 3         | 0.41%   |
| Unknown             | 3         | 0.41%   |
| Apacer              | 2         | 0.28%   |
| Unigen              | 1         | 0.14%   |
| Unifosa             | 1         | 0.14%   |
| Toshiba             | 1         | 0.14%   |
| Teikon              | 1         | 0.14%   |
| Silicon Power       | 1         | 0.14%   |
| PUSKILL             | 1         | 0.14%   |
| Patriot             | 1         | 0.14%   |
| Netlist             | 1         | 0.14%   |
| Lexar               | 1         | 0.14%   |
| Kimtigo             | 1         | 0.14%   |
| Infineon            | 1         | 0.14%   |
| Hewlett-Packard     | 1         | 0.14%   |
| GOODRAM             | 1         | 0.14%   |
| Goldkey             | 1         | 0.14%   |
| Essencore Limited   | 1         | 0.14%   |
| 48spaces            | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 23        | 2.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 13        | 1.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 1.15%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.77%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.64%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.64%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.51%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 3         | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 3         | 0.38%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.38%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.38%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.38%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.38%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.38%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 284       | 44.72%  |
| DDR3    | 195       | 30.71%  |
| DDR2    | 65        | 10.24%  |
| Unknown | 23        | 3.62%   |
| SDRAM   | 20        | 3.15%   |
| LPDDR4  | 18        | 2.83%   |
| LPDDR3  | 17        | 2.68%   |
| DDR     | 7         | 1.1%    |
| LPDDR5  | 3         | 0.47%   |
| DDR5    | 3         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 390       | 61.81%  |
| DIMM         | 180       | 28.53%  |
| Row Of Chips | 57        | 9.03%   |
| FB-DIMM      | 2         | 0.32%   |
| Chip         | 2         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 228       | 32.9%   |
| 4096    | 197       | 28.43%  |
| 2048    | 116       | 16.74%  |
| 16384   | 98        | 14.14%  |
| 1024    | 29        | 4.18%   |
| 32768   | 17        | 2.45%   |
| 512     | 6         | 0.87%   |
| 256     | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 128       | 18.71%  |
| 2667    | 111       | 16.23%  |
| 3200    | 84        | 12.28%  |
| Unknown | 51        | 7.46%   |
| 2400    | 48        | 7.02%   |
| 1333    | 41        | 5.99%   |
| 2133    | 33        | 4.82%   |
| 667     | 24        | 3.51%   |
| 1334    | 20        | 2.92%   |
| 1867    | 12        | 1.75%   |
| 800     | 12        | 1.75%   |
| 8400    | 10        | 1.46%   |
| 3600    | 9         | 1.32%   |
| 1067    | 9         | 1.32%   |
| 4267    | 8         | 1.17%   |
| 3266    | 8         | 1.17%   |
| 3000    | 7         | 1.02%   |
| 533     | 7         | 1.02%   |
| 4199    | 6         | 0.88%   |
| 2666    | 5         | 0.73%   |
| 1866    | 4         | 0.58%   |
| 1066    | 4         | 0.58%   |
| 400     | 4         | 0.58%   |
| 6400    | 3         | 0.44%   |
| 4800    | 3         | 0.44%   |
| 3800    | 3         | 0.44%   |
| 3733    | 3         | 0.44%   |
| 3400    | 3         | 0.44%   |
| 2048    | 3         | 0.44%   |
| 4000    | 2         | 0.29%   |
| 2933    | 2         | 0.29%   |
| 2000    | 2         | 0.29%   |
| 1800    | 2         | 0.29%   |
| 43889   | 1         | 0.15%   |
| 4266    | 1         | 0.15%   |
| 3866    | 1         | 0.15%   |
| 3534    | 1         | 0.15%   |
| 3466    | 1         | 0.15%   |
| 3334    | 1         | 0.15%   |
| 3066    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 20        | 64.52%  |
| Canon                  | 3         | 9.68%   |
| Seiko Epson            | 2         | 6.45%   |
| Brother Industries     | 2         | 6.45%   |
| Xerox                  | 1         | 3.23%   |
| Samsung Electronics    | 1         | 3.23%   |
| Panasonic (Matsushita) | 1         | 3.23%   |
| Lexmark International  | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP Deskjet 1050 J410                 | 4         | 12.12%  |
| Xerox Phaser 6000B                   | 1         | 3.03%   |
| Seiko Epson XP-225 Series            | 1         | 3.03%   |
| Seiko Epson AcuLaser C1700           | 1         | 3.03%   |
| Samsung ML-1640 Series Laser Printer | 1         | 3.03%   |
| Panasonic (Matsushita) KX-FLB851SP   | 1         | 3.03%   |
| Lexmark International E120(n)        | 1         | 3.03%   |
| HP OfficeJet 5200 series             | 1         | 3.03%   |
| HP Officejet 4620 series             | 1         | 3.03%   |
| HP Officejet 4500 G510g-m            | 1         | 3.03%   |
| HP OfficeJet 3830 series             | 1         | 3.03%   |
| HP LaserJet Professional P1102w      | 1         | 3.03%   |
| HP LaserJet M14-M17                  | 1         | 3.03%   |
| HP ENVY 6000 series                  | 1         | 3.03%   |
| HP ENVY 4520 series                  | 1         | 3.03%   |
| HP DeskJet F4100 Printer series      | 1         | 3.03%   |
| HP DeskJet F300 series               | 1         | 3.03%   |
| HP DeskJet F2492 All-in-One          | 1         | 3.03%   |
| HP DeskJet 930c                      | 1         | 3.03%   |
| HP DeskJet 3630 series               | 1         | 3.03%   |
| HP Deskjet 3050A                     | 1         | 3.03%   |
| HP Deskjet 3050 J610 series          | 1         | 3.03%   |
| HP DeskJet 2700 series               | 1         | 3.03%   |
| HP DeskJet 2130 series               | 1         | 3.03%   |
| Canon TS6300 series                  | 1         | 3.03%   |
| Canon PIXMA TS6250                   | 1         | 3.03%   |
| Canon PIXMA MG2900 Series            | 1         | 3.03%   |
| Canon LBP6200                        | 1         | 3.03%   |
| Brother DCP-L3550CDW series          | 1         | 3.03%   |
| Brother DCP-1610W                    | 1         | 3.03%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Mustek Systems  | 4         | 44.44%  |
| Canon           | 3         | 33.33%  |
| Seiko Epson     | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB    | 3         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 11.11%  |
| Mustek Systems BearPaw 2448 CU Pro    | 1         | 11.11%  |
| HP ScanJet 5300c/5370c                | 1         | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20    | 1         | 11.11%  |
| Canon CanoScan LiDE 110               | 1         | 11.11%  |
| Canon CanoScan 4400F                  | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 231       | 24.97%  |
| IMC Networks                           | 113       | 12.22%  |
| Realtek Semiconductor                  | 69        | 7.46%   |
| Acer                                   | 57        | 6.16%   |
| Suyin                                  | 46        | 4.97%   |
| Quanta                                 | 40        | 4.32%   |
| Microdia                               | 40        | 4.32%   |
| Ricoh                                  | 31        | 3.35%   |
| Logitech                               | 30        | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) | 27        | 2.92%   |
| Sunplus Innovation Technology          | 26        | 2.81%   |
| Syntek                                 | 24        | 2.59%   |
| Lite-On Technology                     | 24        | 2.59%   |
| Apple                                  | 23        | 2.49%   |
| Microsoft                              | 16        | 1.73%   |
| Luxvisions Innotech Limited            | 12        | 1.3%    |
| Creative Technology                    | 12        | 1.3%    |
| Silicon Motion                         | 10        | 1.08%   |
| Hewlett-Packard                        | 8         | 0.86%   |
| Alcor Micro                            | 8         | 0.86%   |
| Z-Star Microelectronics                | 7         | 0.76%   |
| Lenovo                                 | 7         | 0.76%   |
| Importek                               | 7         | 0.76%   |
| Generalplus Technology                 | 7         | 0.76%   |
| Samsung Electronics                    | 6         | 0.65%   |
| Bison Electronics                      | 6         | 0.65%   |
| WaveRider Communications               | 3         | 0.32%   |
| Cubeternet                             | 3         | 0.32%   |
| Aveo Technology                        | 3         | 0.32%   |
| ALi                                    | 3         | 0.32%   |
| Sonix Technology                       | 2         | 0.22%   |
| Primax Electronics                     | 2         | 0.22%   |
| Philips (or NXP)                       | 2         | 0.22%   |
| Jieli Technology                       | 2         | 0.22%   |
| DigiTech                               | 2         | 0.22%   |
| Y Media                                | 1         | 0.11%   |
| Xiaomi                                 | 1         | 0.11%   |
| Trust                                  | 1         | 0.11%   |
| Razer USA                              | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 32        | 3.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 31        | 3.34%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 21        | 2.26%   |
| IMC Networks Integrated Camera                      | 21        | 2.26%   |
| Chicony HD Webcam                                   | 21        | 2.26%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 1.94%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 1.61%   |
| Chicony USB 2.0 Camera                              | 13        | 1.4%    |
| Chicony CNF9055 Toshiba Webcam                      | 13        | 1.4%    |
| Acer Integrated Camera                              | 13        | 1.4%    |
| Realtek USB Camera                                  | 12        | 1.29%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 11        | 1.18%   |
| Realtek EasyCamera                                  | 11        | 1.18%   |
| Microdia Integrated_Webcam_HD                       | 11        | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 1.18%   |
| Quanta HP Wide Vision HD Camera                     | 9         | 0.97%   |
| Microsoft LifeCam HD-3000                           | 9         | 0.97%   |
| IMC Networks HD Camera                              | 9         | 0.97%   |
| Syntek Integrated Camera                            | 8         | 0.86%   |
| Realtek Integrated_Webcam_HD                        | 8         | 0.86%   |
| Realtek HD WebCam                                   | 8         | 0.86%   |
| Chicony HP Truevision HD                            | 8         | 0.86%   |
| Suyin USB 2.0 Camera                                | 7         | 0.75%   |
| Quanta HP TrueVision HD Camera                      | 7         | 0.75%   |
| Microdia Sonix USB 2.0 Camera                       | 7         | 0.75%   |
| Logitech Webcam C270                                | 7         | 0.75%   |
| Lite-On Integrated Camera                           | 7         | 0.75%   |
| IMC Networks ov9734_azurewave_camera                | 7         | 0.75%   |
| Chicony HP HD Camera                                | 7         | 0.75%   |
| Apple Built-in iSight                               | 7         | 0.75%   |
| Acer HD Webcam                                      | 7         | 0.75%   |
| Syntek EasyCamera                                   | 6         | 0.65%   |
| Sunplus HD WebCam                                   | 6         | 0.65%   |
| Samsung Galaxy A5 (MTP)                             | 6         | 0.65%   |
| Realtek USB2.0-Camera                               | 6         | 0.65%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.65%   |
| HP Webcam HD 2300                                   | 6         | 0.65%   |
| Generalplus 808 Camera #9 (web-cam mode)            | 6         | 0.65%   |
| Chicony VGA Webcam                                  | 6         | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                        | 6         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 48        | 34.53%  |
| Validity Sensors                   | 40        | 28.78%  |
| Shenzhen Goodix Technology         | 20        | 14.39%  |
| AuthenTec                          | 11        | 7.91%   |
| Elan Microelectronics              | 7         | 5.04%   |
| Upek                               | 6         | 4.32%   |
| LighTuning Technology              | 4         | 2.88%   |
| STMicroelectronics                 | 2         | 1.44%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 10.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 7.19%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 5.76%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.6%    |
| Synaptics UWP WBDI Device                                                  | 5         | 3.6%    |
| AuthenTec AES1600                                                          | 5         | 3.6%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 2.88%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.88%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.88%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.16%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.16%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.16%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.16%   |
| Synaptics WBDI                                                             | 3         | 2.16%   |
| Synaptics UWP WBDI                                                         | 3         | 2.16%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.16%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.16%   |
| AuthenTec AES2810                                                          | 3         | 2.16%   |
| Validity Sensors VFS491                                                    | 2         | 1.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.44%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.44%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 1.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.44%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.44%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.44%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.72%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.72%   |
| Synaptics WBDI Device                                                      | 1         | 0.72%   |
| Synaptics  WBDI                                                            | 1         | 0.72%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.72%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 24        | 34.78%  |
| Broadcom              | 17        | 24.64%  |
| Gemalto (was Gemplus) | 7         | 10.14%  |
| O2 Micro              | 5         | 7.25%   |
| Lenovo                | 3         | 4.35%   |
| SCM Microsystems      | 2         | 2.9%    |
| Realtek Semiconductor | 2         | 2.9%    |
| BIT4ID                | 2         | 2.9%    |
| Advanced Card Systems | 2         | 2.9%    |
| Yubico.com            | 1         | 1.45%   |
| Upek                  | 1         | 1.45%   |
| Hewlett-Packard       | 1         | 1.45%   |
| Chicony Electronics   | 1         | 1.45%   |
| Cherry                | 1         | 1.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 10.14%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 8.7%    |
| Broadcom 58200                                                               | 6         | 8.7%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.8%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.35%   |
| Broadcom 5880                                                                | 3         | 4.35%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.9%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 2.9%    |
| BIT4ID miniLector EVO                                                        | 2         | 2.9%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 2.9%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.45%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.45%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.45%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.45%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.45%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.45%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 996       | 70.04%  |
| 1     | 330       | 23.21%  |
| 2     | 75        | 5.27%   |
| 3     | 15        | 1.05%   |
| 4     | 5         | 0.35%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 148       | 28.52%  |
| Fingerprint reader       | 138       | 26.59%  |
| Net/wireless             | 63        | 12.14%  |
| Chipcard                 | 53        | 10.21%  |
| Multimedia controller    | 42        | 8.09%   |
| Camera                   | 17        | 3.28%   |
| Bluetooth                | 12        | 2.31%   |
| Card reader              | 10        | 1.93%   |
| Storage                  | 7         | 1.35%   |
| Communication controller | 7         | 1.35%   |
| Modem                    | 5         | 0.96%   |
| Network                  | 4         | 0.77%   |
| Net/ethernet             | 4         | 0.77%   |
| Flash memory             | 4         | 0.77%   |
| Unassigned class         | 2         | 0.39%   |
| Sound                    | 2         | 0.39%   |
| Dvb card                 | 1         | 0.19%   |

