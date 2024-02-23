Linux in UK - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UK/Desktop/README.md) and [notebooks](/Location/UK/Notebook/README.md).

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

Total: 13124

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3542               | Notebook    | [c7753ffa8e](https://linux-hardware.org/?probe=c7753ffa8e) | Feb 02, 2024 |
| Dell          | 0YC03K A03                  | Desktop     | [e6d016f309](https://linux-hardware.org/?probe=e6d016f309) | Feb 02, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [1546d8c6bf](https://linux-hardware.org/?probe=1546d8c6bf) | Feb 02, 2024 |
| Dell          | Inspiron 13-7359            | Notebook    | [82a1195ef5](https://linux-hardware.org/?probe=82a1195ef5) | Feb 02, 2024 |
| PC Special... | GK5CQ7Z                     | Notebook    | [d7632585fc](https://linux-hardware.org/?probe=d7632585fc) | Feb 02, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [48a998308b](https://linux-hardware.org/?probe=48a998308b) | Feb 02, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a64e17ff88](https://linux-hardware.org/?probe=a64e17ff88) | Feb 02, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [632421d681](https://linux-hardware.org/?probe=632421d681) | Feb 01, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ef0de660b6](https://linux-hardware.org/?probe=ef0de660b6) | Feb 01, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | Desktop     | [de6afda636](https://linux-hardware.org/?probe=de6afda636) | Feb 01, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [63fe6fecb5](https://linux-hardware.org/?probe=63fe6fecb5) | Feb 01, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [88448ddf49](https://linux-hardware.org/?probe=88448ddf49) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [397f03250d](https://linux-hardware.org/?probe=397f03250d) | Feb 01, 2024 |
| Acer          | Swift SF314-512             | Notebook    | [28bd75703e](https://linux-hardware.org/?probe=28bd75703e) | Feb 01, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [0b1c1e6784](https://linux-hardware.org/?probe=0b1c1e6784) | Feb 01, 2024 |
| TrekStor      | Primebook P14               | Notebook    | [ffd6c873de](https://linux-hardware.org/?probe=ffd6c873de) | Feb 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [9d2088ace3](https://linux-hardware.org/?probe=9d2088ace3) | Feb 01, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [172f182e36](https://linux-hardware.org/?probe=172f182e36) | Feb 01, 2024 |
| HP            | Pavilion dv6                | Notebook    | [9d58677c2a](https://linux-hardware.org/?probe=9d58677c2a) | Feb 01, 2024 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b2d8a38af3](https://linux-hardware.org/?probe=b2d8a38af3) | Feb 01, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [c58dd08065](https://linux-hardware.org/?probe=c58dd08065) | Jan 31, 2024 |
| HP            | 15                          | Notebook    | [5abc868cce](https://linux-hardware.org/?probe=5abc868cce) | Jan 31, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [348cad0405](https://linux-hardware.org/?probe=348cad0405) | Jan 31, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [20471f1e71](https://linux-hardware.org/?probe=20471f1e71) | Jan 31, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [85b45c9a2f](https://linux-hardware.org/?probe=85b45c9a2f) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [e12d7e5691](https://linux-hardware.org/?probe=e12d7e5691) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [68076b1cbd](https://linux-hardware.org/?probe=68076b1cbd) | Jan 31, 2024 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [5dcee96cdb](https://linux-hardware.org/?probe=5dcee96cdb) | Jan 31, 2024 |
| Dell          | Latitude E6430s             | Notebook    | [6eacf03c08](https://linux-hardware.org/?probe=6eacf03c08) | Jan 31, 2024 |
| Acer          | Swift SF314-42              | Notebook    | [32d0112bcd](https://linux-hardware.org/?probe=32d0112bcd) | Jan 30, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [3418c8d84c](https://linux-hardware.org/?probe=3418c8d84c) | Jan 30, 2024 |
| HP            | Pavilion dv6                | Notebook    | [e1e2c04f8c](https://linux-hardware.org/?probe=e1e2c04f8c) | Jan 30, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [809fd2e9fa](https://linux-hardware.org/?probe=809fd2e9fa) | Jan 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [0db5dcce8b](https://linux-hardware.org/?probe=0db5dcce8b) | Jan 30, 2024 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [57e466f18c](https://linux-hardware.org/?probe=57e466f18c) | Jan 30, 2024 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [b51ecf60ef](https://linux-hardware.org/?probe=b51ecf60ef) | Jan 30, 2024 |
| Biostar       | MCP6P3                      | Desktop     | [cbb6a42f28](https://linux-hardware.org/?probe=cbb6a42f28) | Jan 30, 2024 |
| Biostar       | MCP6P3                      | Desktop     | [55f83d7c17](https://linux-hardware.org/?probe=55f83d7c17) | Jan 30, 2024 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [87e2c70726](https://linux-hardware.org/?probe=87e2c70726) | Jan 30, 2024 |
| Acer          | Aspire E1-571               | Notebook    | [daf8c42eca](https://linux-hardware.org/?probe=daf8c42eca) | Jan 30, 2024 |
| Lenovo        | ThinkPad T510 43149TG       | Notebook    | [463b653f7a](https://linux-hardware.org/?probe=463b653f7a) | Jan 30, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | Notebook    | [7f42dbc84d](https://linux-hardware.org/?probe=7f42dbc84d) | Jan 30, 2024 |
| AWOW          | AK41                        | Notebook    | [4e8816ed0c](https://linux-hardware.org/?probe=4e8816ed0c) | Jan 30, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H5C... | Notebook    | [62bda5bd27](https://linux-hardware.org/?probe=62bda5bd27) | Jan 30, 2024 |
| HP            | Pavilion dv6                | Notebook    | [654b331eac](https://linux-hardware.org/?probe=654b331eac) | Jan 30, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1127b13645](https://linux-hardware.org/?probe=1127b13645) | Jan 30, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [88ff9ffee3](https://linux-hardware.org/?probe=88ff9ffee3) | Jan 30, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a214537a22](https://linux-hardware.org/?probe=a214537a22) | Jan 30, 2024 |
| HP            | Pavilion dv6                | Notebook    | [69c00fe459](https://linux-hardware.org/?probe=69c00fe459) | Jan 30, 2024 |
| Dell          | Latitude 7390               | Notebook    | [defc75091c](https://linux-hardware.org/?probe=defc75091c) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [ad26dae776](https://linux-hardware.org/?probe=ad26dae776) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [bc4394a85f](https://linux-hardware.org/?probe=bc4394a85f) | Jan 30, 2024 |
| Sony          | SVF1521Q1EW                 | Notebook    | [94c0695977](https://linux-hardware.org/?probe=94c0695977) | Jan 30, 2024 |
| AZW           | MINI S 10                   | Desktop     | [d707319ed7](https://linux-hardware.org/?probe=d707319ed7) | Jan 29, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7433d96930](https://linux-hardware.org/?probe=7433d96930) | Jan 29, 2024 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [f0e620b88a](https://linux-hardware.org/?probe=f0e620b88a) | Jan 29, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [fff97c0d16](https://linux-hardware.org/?probe=fff97c0d16) | Jan 29, 2024 |
| CyberPower... | Tracer II                   | Notebook    | [ca21b317a2](https://linux-hardware.org/?probe=ca21b317a2) | Jan 29, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [6309dc5c20](https://linux-hardware.org/?probe=6309dc5c20) | Jan 29, 2024 |
| Foxconn       | 2A8C                        | Desktop     | [042483c307](https://linux-hardware.org/?probe=042483c307) | Jan 29, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a86d2d1cf6](https://linux-hardware.org/?probe=a86d2d1cf6) | Jan 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [510f28a7d3](https://linux-hardware.org/?probe=510f28a7d3) | Jan 29, 2024 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [4ab253480b](https://linux-hardware.org/?probe=4ab253480b) | Jan 29, 2024 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [156193b673](https://linux-hardware.org/?probe=156193b673) | Jan 28, 2024 |
| Acer          | TDPS05 R3700                | Desktop     | [d2ef9055f2](https://linux-hardware.org/?probe=d2ef9055f2) | Jan 28, 2024 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [7c9fb93a37](https://linux-hardware.org/?probe=7c9fb93a37) | Jan 28, 2024 |
| Dell          | 08K0X7 A00                  | Desktop     | [981f5fcf48](https://linux-hardware.org/?probe=981f5fcf48) | Jan 28, 2024 |
| LG Electro... | 14T90R-K.AA77A1             | Convertible | [c552693e5d](https://linux-hardware.org/?probe=c552693e5d) | Jan 28, 2024 |
| Foxconn       | 946 7MA Series              | Desktop     | [8ef460557c](https://linux-hardware.org/?probe=8ef460557c) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [aa19c735f2](https://linux-hardware.org/?probe=aa19c735f2) | Jan 28, 2024 |
| Dell          | XPS L421X                   | Notebook    | [7eab16ad73](https://linux-hardware.org/?probe=7eab16ad73) | Jan 27, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c9870d08e7](https://linux-hardware.org/?probe=c9870d08e7) | Jan 27, 2024 |
| HP            | 8105                        | Desktop     | [41fdf37154](https://linux-hardware.org/?probe=41fdf37154) | Jan 27, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [75f6092ef1](https://linux-hardware.org/?probe=75f6092ef1) | Jan 27, 2024 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [7280098d0c](https://linux-hardware.org/?probe=7280098d0c) | Jan 27, 2024 |
| Biostar       | A10N-8800E                  | Desktop     | [6035efec56](https://linux-hardware.org/?probe=6035efec56) | Jan 27, 2024 |
| Biostar       | A10N-8800E                  | Desktop     | [9eab4dee46](https://linux-hardware.org/?probe=9eab4dee46) | Jan 27, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [be944e9cf6](https://linux-hardware.org/?probe=be944e9cf6) | Jan 27, 2024 |
| ASUSTek       | X551CA                      | Notebook    | [2147b3f8f3](https://linux-hardware.org/?probe=2147b3f8f3) | Jan 27, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [840164bd48](https://linux-hardware.org/?probe=840164bd48) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2d82723a5a](https://linux-hardware.org/?probe=2d82723a5a) | Jan 27, 2024 |
| Lenovo        | ThinkPad T430 2349SA2       | Notebook    | [8c4e929f6f](https://linux-hardware.org/?probe=8c4e929f6f) | Jan 27, 2024 |
| Dell          | Latitude E6430              | Notebook    | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [3f817efef4](https://linux-hardware.org/?probe=3f817efef4) | Jan 26, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [43bf0c55e8](https://linux-hardware.org/?probe=43bf0c55e8) | Jan 26, 2024 |
| Valve         | Jupiter                     | Notebook    | [b69df41d1b](https://linux-hardware.org/?probe=b69df41d1b) | Jan 26, 2024 |
| HP            | ProBook 455 G2              | Notebook    | [f8d011e007](https://linux-hardware.org/?probe=f8d011e007) | Jan 25, 2024 |
| Biostar       | Z490GTN                     | Desktop     | [4f1869ea6a](https://linux-hardware.org/?probe=4f1869ea6a) | Jan 25, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [23faf0c03e](https://linux-hardware.org/?probe=23faf0c03e) | Jan 25, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [fda3733e63](https://linux-hardware.org/?probe=fda3733e63) | Jan 25, 2024 |
| ECS           | H67H2-M2                    | Desktop     | [e4ad7bd4f2](https://linux-hardware.org/?probe=e4ad7bd4f2) | Jan 25, 2024 |
| Acer          | Swift SFG14-72              | Notebook    | [a9239eecc8](https://linux-hardware.org/?probe=a9239eecc8) | Jan 25, 2024 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | Desktop     | [bbc8707e00](https://linux-hardware.org/?probe=bbc8707e00) | Jan 25, 2024 |
| Dell          | 0GCY4M A01                  | Desktop     | [7570087915](https://linux-hardware.org/?probe=7570087915) | Jan 25, 2024 |
| ASUSTek       | Z97-P                       | Desktop     | [0803e06982](https://linux-hardware.org/?probe=0803e06982) | Jan 25, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [969d0f1bef](https://linux-hardware.org/?probe=969d0f1bef) | Jan 25, 2024 |
| Acer          | Swift SF314-57              | Notebook    | [352b6edd13](https://linux-hardware.org/?probe=352b6edd13) | Jan 25, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [24a5e0a03c](https://linux-hardware.org/?probe=24a5e0a03c) | Jan 25, 2024 |
| MSI           | MEG X399 CREATION           | Desktop     | [b598a0fd29](https://linux-hardware.org/?probe=b598a0fd29) | Jan 25, 2024 |
| Lenovo        | ThinkPad X250 20CM004XUK    | Notebook    | [a1e8059fd3](https://linux-hardware.org/?probe=a1e8059fd3) | Jan 25, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | Notebook    | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Apple         | MacBook10,1                 | Notebook    | [da3e59958f](https://linux-hardware.org/?probe=da3e59958f) | Jan 24, 2024 |
| Dell          | Latitude 7390               | Notebook    | [ba979ded0e](https://linux-hardware.org/?probe=ba979ded0e) | Jan 24, 2024 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [642c49982c](https://linux-hardware.org/?probe=642c49982c) | Jan 24, 2024 |
| AZW           | Gemini T45                  | Desktop     | [5a3dba74d6](https://linux-hardware.org/?probe=5a3dba74d6) | Jan 24, 2024 |
| AZW           | Gemini T45                  | Desktop     | [a0e1db7908](https://linux-hardware.org/?probe=a0e1db7908) | Jan 24, 2024 |
| AZW           | GT-R                        | Notebook    | [b9cc91d07d](https://linux-hardware.org/?probe=b9cc91d07d) | Jan 24, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [6eb8876e79](https://linux-hardware.org/?probe=6eb8876e79) | Jan 24, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [738c84d746](https://linux-hardware.org/?probe=738c84d746) | Jan 23, 2024 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [9e41ae4dc7](https://linux-hardware.org/?probe=9e41ae4dc7) | Jan 23, 2024 |
| ASUSTek       | Berkeley                    | Desktop     | [c7d349a7f0](https://linux-hardware.org/?probe=c7d349a7f0) | Jan 23, 2024 |
| HP            | ProBook 455 G1              | Notebook    | [224d863e1d](https://linux-hardware.org/?probe=224d863e1d) | Jan 23, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a756dd32a8](https://linux-hardware.org/?probe=a756dd32a8) | Jan 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [d2a4f1790a](https://linux-hardware.org/?probe=d2a4f1790a) | Jan 22, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [2f77e5be01](https://linux-hardware.org/?probe=2f77e5be01) | Jan 22, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [a4c212bc8e](https://linux-hardware.org/?probe=a4c212bc8e) | Jan 22, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [f2919e84e4](https://linux-hardware.org/?probe=f2919e84e4) | Jan 22, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19eaa1abc0](https://linux-hardware.org/?probe=19eaa1abc0) | Jan 22, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [97f9705158](https://linux-hardware.org/?probe=97f9705158) | Jan 22, 2024 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [a9b6876050](https://linux-hardware.org/?probe=a9b6876050) | Jan 22, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [a19e1e70ac](https://linux-hardware.org/?probe=a19e1e70ac) | Jan 22, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [7164188034](https://linux-hardware.org/?probe=7164188034) | Jan 22, 2024 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [2449b6b678](https://linux-hardware.org/?probe=2449b6b678) | Jan 22, 2024 |
| Lenovo        | ThinkPad X250 20CLS3320C    | Notebook    | [5525303ee4](https://linux-hardware.org/?probe=5525303ee4) | Jan 22, 2024 |
| Acer          | Swift SF314-511             | Notebook    | [c4578284c8](https://linux-hardware.org/?probe=c4578284c8) | Jan 22, 2024 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [7eea5af3e6](https://linux-hardware.org/?probe=7eea5af3e6) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| HP            | 18E5                        | Desktop     | [69ba380344](https://linux-hardware.org/?probe=69ba380344) | Jan 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8621eed350](https://linux-hardware.org/?probe=8621eed350) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [97588f48fc](https://linux-hardware.org/?probe=97588f48fc) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| Lenovo        | ThinkPad X201 3323DAG       | Notebook    | [27542f7432](https://linux-hardware.org/?probe=27542f7432) | Jan 21, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [bec3659c29](https://linux-hardware.org/?probe=bec3659c29) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Foxconn       | 946 7MA Series              | Desktop     | [40261803d6](https://linux-hardware.org/?probe=40261803d6) | Jan 21, 2024 |
| Lenovo        | ThinkPad T400 6474W7T       | Notebook    | [fa80320d7c](https://linux-hardware.org/?probe=fa80320d7c) | Jan 21, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [aaf1d1d0de](https://linux-hardware.org/?probe=aaf1d1d0de) | Jan 21, 2024 |
| Microsoft     | Surface Laptop 3            | Tablet      | [51f361caf2](https://linux-hardware.org/?probe=51f361caf2) | Jan 20, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [af044c261f](https://linux-hardware.org/?probe=af044c261f) | Jan 20, 2024 |
| ECS           | H61H2-M2                    | Desktop     | [ecb9ae8bed](https://linux-hardware.org/?probe=ecb9ae8bed) | Jan 20, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [5df2f7a287](https://linux-hardware.org/?probe=5df2f7a287) | Jan 20, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [8f41b6b7f9](https://linux-hardware.org/?probe=8f41b6b7f9) | Jan 20, 2024 |
| MSI           | Z270 GAMING M5              | Desktop     | [e8e8d1eac7](https://linux-hardware.org/?probe=e8e8d1eac7) | Jan 20, 2024 |
| Panasonic     | CF-52PFN32PE                | Notebook    | [8399ba74d7](https://linux-hardware.org/?probe=8399ba74d7) | Jan 20, 2024 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [52318f5ae6](https://linux-hardware.org/?probe=52318f5ae6) | Jan 20, 2024 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [5ab5b74cfa](https://linux-hardware.org/?probe=5ab5b74cfa) | Jan 20, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [3e3867681c](https://linux-hardware.org/?probe=3e3867681c) | Jan 19, 2024 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [a9b8760e3e](https://linux-hardware.org/?probe=a9b8760e3e) | Jan 19, 2024 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d10d02479b](https://linux-hardware.org/?probe=d10d02479b) | Jan 19, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [59c00448b4](https://linux-hardware.org/?probe=59c00448b4) | Jan 19, 2024 |
| Acer          | Swift SFG14-72              | Notebook    | [e37657c021](https://linux-hardware.org/?probe=e37657c021) | Jan 19, 2024 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [4b5ab9a0fd](https://linux-hardware.org/?probe=4b5ab9a0fd) | Jan 19, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [09fe6e6426](https://linux-hardware.org/?probe=09fe6e6426) | Jan 19, 2024 |
| LG Electro... | 14T90R-K.AA77A1             | Convertible | [199a0be0a5](https://linux-hardware.org/?probe=199a0be0a5) | Jan 19, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [0ee138a094](https://linux-hardware.org/?probe=0ee138a094) | Jan 19, 2024 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [4ac008d4c9](https://linux-hardware.org/?probe=4ac008d4c9) | Jan 19, 2024 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [27fefbcd84](https://linux-hardware.org/?probe=27fefbcd84) | Jan 19, 2024 |
| ASUSTek       | N55SL                       | Notebook    | [a6c913a5e2](https://linux-hardware.org/?probe=a6c913a5e2) | Jan 19, 2024 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [9b78c4adba](https://linux-hardware.org/?probe=9b78c4adba) | Jan 19, 2024 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [408beb089a](https://linux-hardware.org/?probe=408beb089a) | Jan 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4d77bb448](https://linux-hardware.org/?probe=e4d77bb448) | Jan 19, 2024 |
| GPD           | P2 MAX                      | Notebook    | [ec59cadd15](https://linux-hardware.org/?probe=ec59cadd15) | Jan 19, 2024 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [516bbcf7a3](https://linux-hardware.org/?probe=516bbcf7a3) | Jan 18, 2024 |
| BESSTAR Te... | UM700                       | Desktop     | [cf8648f144](https://linux-hardware.org/?probe=cf8648f144) | Jan 18, 2024 |
| HP            | 8298                        | Desktop     | [9702f87120](https://linux-hardware.org/?probe=9702f87120) | Jan 18, 2024 |
| Lenovo        | 3106 SDK0J40709 WIN 3259... | Desktop     | [370e1682cf](https://linux-hardware.org/?probe=370e1682cf) | Jan 18, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [518ca600f6](https://linux-hardware.org/?probe=518ca600f6) | Jan 18, 2024 |
| Dell          | XPS 9320                    | Notebook    | [eb5df7ed6d](https://linux-hardware.org/?probe=eb5df7ed6d) | Jan 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [1a9602bf0b](https://linux-hardware.org/?probe=1a9602bf0b) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | Notebook    | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| ASUSTek       | X541UAK                     | Notebook    | [bd74ab2cc7](https://linux-hardware.org/?probe=bd74ab2cc7) | Jan 17, 2024 |
| HP            | 3397                        | Desktop     | [a46224b9bc](https://linux-hardware.org/?probe=a46224b9bc) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236Y54       | Notebook    | [1364b82d7c](https://linux-hardware.org/?probe=1364b82d7c) | Jan 17, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [13bd535c3f](https://linux-hardware.org/?probe=13bd535c3f) | Jan 17, 2024 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [a3813e2aa2](https://linux-hardware.org/?probe=a3813e2aa2) | Jan 16, 2024 |
| Apple         | MacBookPro15,2              | Notebook    | [547ddaf81d](https://linux-hardware.org/?probe=547ddaf81d) | Jan 16, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [61ade3f6d3](https://linux-hardware.org/?probe=61ade3f6d3) | Jan 15, 2024 |
| Valve         | Galileo                     | Notebook    | [c9db96cd08](https://linux-hardware.org/?probe=c9db96cd08) | Jan 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff4dff4d2f](https://linux-hardware.org/?probe=ff4dff4d2f) | Jan 15, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [f7b5e8a248](https://linux-hardware.org/?probe=f7b5e8a248) | Jan 15, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [ff371f0408](https://linux-hardware.org/?probe=ff371f0408) | Jan 15, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [94858d9522](https://linux-hardware.org/?probe=94858d9522) | Jan 15, 2024 |
| Dell          | Latitude E5470              | Notebook    | [d9fcb7e121](https://linux-hardware.org/?probe=d9fcb7e121) | Jan 15, 2024 |
| ASUSTek       | N56VB                       | Notebook    | [3542693793](https://linux-hardware.org/?probe=3542693793) | Jan 15, 2024 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [46ceed2d83](https://linux-hardware.org/?probe=46ceed2d83) | Jan 15, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [9ae250d8a6](https://linux-hardware.org/?probe=9ae250d8a6) | Jan 15, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [cdfc29ad66](https://linux-hardware.org/?probe=cdfc29ad66) | Jan 15, 2024 |
| Valve         | Galileo                     | Notebook    | [5d92a542e4](https://linux-hardware.org/?probe=5d92a542e4) | Jan 14, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [cd7b830381](https://linux-hardware.org/?probe=cd7b830381) | Jan 14, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [84ecce6ca6](https://linux-hardware.org/?probe=84ecce6ca6) | Jan 14, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [761cd45b4a](https://linux-hardware.org/?probe=761cd45b4a) | Jan 14, 2024 |
| Dell          | 09M8Y8 A01                  | Desktop     | [0372519ba2](https://linux-hardware.org/?probe=0372519ba2) | Jan 14, 2024 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [7f4b2938a3](https://linux-hardware.org/?probe=7f4b2938a3) | Jan 14, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [3d9f1350b3](https://linux-hardware.org/?probe=3d9f1350b3) | Jan 14, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1b6a4a4985](https://linux-hardware.org/?probe=1b6a4a4985) | Jan 13, 2024 |
| PC Special... | P65_67RSRP                  | Notebook    | [f2af84bdfc](https://linux-hardware.org/?probe=f2af84bdfc) | Jan 13, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6be6b20963](https://linux-hardware.org/?probe=6be6b20963) | Jan 13, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [dba611325e](https://linux-hardware.org/?probe=dba611325e) | Jan 13, 2024 |
| Dell          | 073MMW A00                  | Desktop     | [88f464f54c](https://linux-hardware.org/?probe=88f464f54c) | Jan 13, 2024 |
| Acer          | FMCP7A-ION                  | Desktop     | [07a359d0d4](https://linux-hardware.org/?probe=07a359d0d4) | Jan 13, 2024 |
| HP            | 1998                        | Desktop     | [4201d22b9a](https://linux-hardware.org/?probe=4201d22b9a) | Jan 13, 2024 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [56b1b4f807](https://linux-hardware.org/?probe=56b1b4f807) | Jan 13, 2024 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [01dbc106fd](https://linux-hardware.org/?probe=01dbc106fd) | Jan 13, 2024 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [98b9fa844b](https://linux-hardware.org/?probe=98b9fa844b) | Jan 12, 2024 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b6d8783c20](https://linux-hardware.org/?probe=b6d8783c20) | Jan 12, 2024 |
| Lenovo        | ThinkPad X260 20F5S4A901    | Notebook    | [75e671c163](https://linux-hardware.org/?probe=75e671c163) | Jan 12, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [de5d52bcd5](https://linux-hardware.org/?probe=de5d52bcd5) | Jan 12, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Notebook    | [3be44d9c7c](https://linux-hardware.org/?probe=3be44d9c7c) | Jan 12, 2024 |
| Lenovo        | ThinkPad L570 20J9S0KG00    | Notebook    | [6d03ee96b8](https://linux-hardware.org/?probe=6d03ee96b8) | Jan 12, 2024 |
| Dell          | Latitude E6400              | Notebook    | [2059e9e8d0](https://linux-hardware.org/?probe=2059e9e8d0) | Jan 12, 2024 |
| Medion        | MS-7713                     | Desktop     | [6264963f7f](https://linux-hardware.org/?probe=6264963f7f) | Jan 11, 2024 |
| Dell          | 04TP5V A00                  | Mini pc     | [0f58e0a990](https://linux-hardware.org/?probe=0f58e0a990) | Jan 11, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [4d02212cbc](https://linux-hardware.org/?probe=4d02212cbc) | Jan 11, 2024 |
| HP            | 1494                        | Desktop     | [2d0efc2df1](https://linux-hardware.org/?probe=2d0efc2df1) | Jan 11, 2024 |
| Razer         | Blade Stealth               | Notebook    | [a8c542db2c](https://linux-hardware.org/?probe=a8c542db2c) | Jan 11, 2024 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [5e75e6b11a](https://linux-hardware.org/?probe=5e75e6b11a) | Jan 10, 2024 |
| ASUSTek       | N55SL                       | Notebook    | [b2c935edc3](https://linux-hardware.org/?probe=b2c935edc3) | Jan 10, 2024 |
| Dell          | Latitude E5470              | Notebook    | [a2211d635f](https://linux-hardware.org/?probe=a2211d635f) | Jan 10, 2024 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [c51ffcf76e](https://linux-hardware.org/?probe=c51ffcf76e) | Jan 10, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7c77830f2f](https://linux-hardware.org/?probe=7c77830f2f) | Jan 10, 2024 |
| Dell          | XPS 9320                    | Notebook    | [86cf8ad410](https://linux-hardware.org/?probe=86cf8ad410) | Jan 10, 2024 |
| Dell          | 04Y8V0 A02                  | Desktop     | [f3180a8cdf](https://linux-hardware.org/?probe=f3180a8cdf) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | Notebook    | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [b06f0958e4](https://linux-hardware.org/?probe=b06f0958e4) | Jan 09, 2024 |
| Supermicro    | X8DTU-6+                    | Server      | [a3373dc4bf](https://linux-hardware.org/?probe=a3373dc4bf) | Jan 09, 2024 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [4af36bad9f](https://linux-hardware.org/?probe=4af36bad9f) | Jan 09, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [8a0e17b484](https://linux-hardware.org/?probe=8a0e17b484) | Jan 09, 2024 |
| TI            | AM335x PocketBeagle         | Soc         | [dc70357482](https://linux-hardware.org/?probe=dc70357482) | Jan 09, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [0bc6f72a01](https://linux-hardware.org/?probe=0bc6f72a01) | Jan 09, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [2cb18af412](https://linux-hardware.org/?probe=2cb18af412) | Jan 09, 2024 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [a7c594cca5](https://linux-hardware.org/?probe=a7c594cca5) | Jan 08, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| LG Electro... | 15Z90RT-K.AD7AA1            | Notebook    | [be4ff0f44a](https://linux-hardware.org/?probe=be4ff0f44a) | Jan 08, 2024 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [960bf85acd](https://linux-hardware.org/?probe=960bf85acd) | Jan 08, 2024 |
| HUAWEI        | WRT-WX9                     | Notebook    | [5b9a494436](https://linux-hardware.org/?probe=5b9a494436) | Jan 08, 2024 |
| Acer          | Nitro AN517-52              | Notebook    | [1f601b8cb0](https://linux-hardware.org/?probe=1f601b8cb0) | Jan 08, 2024 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a9279f2618](https://linux-hardware.org/?probe=a9279f2618) | Jan 08, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [8ba032e1a2](https://linux-hardware.org/?probe=8ba032e1a2) | Jan 08, 2024 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [65b8b86d70](https://linux-hardware.org/?probe=65b8b86d70) | Jan 08, 2024 |
| Lenovo        | ThinkPad X220 4291RD2       | Notebook    | [dc1b40ea6f](https://linux-hardware.org/?probe=dc1b40ea6f) | Jan 08, 2024 |
| AWOW          | AK41                        | Notebook    | [62d6e6b631](https://linux-hardware.org/?probe=62d6e6b631) | Jan 08, 2024 |
| Dell          | Latitude 7280               | Notebook    | [de1f6a94e6](https://linux-hardware.org/?probe=de1f6a94e6) | Jan 08, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [6d4f4bbf6c](https://linux-hardware.org/?probe=6d4f4bbf6c) | Jan 08, 2024 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [82b3dcb60a](https://linux-hardware.org/?probe=82b3dcb60a) | Jan 08, 2024 |
| Shenzhen M... | F7BRC                       | Desktop     | [720a2d2f2e](https://linux-hardware.org/?probe=720a2d2f2e) | Jan 08, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [fd3f275cfb](https://linux-hardware.org/?probe=fd3f275cfb) | Jan 07, 2024 |
| ENTITY        | ENTYG11Q1                   | Notebook    | [b2ca051044](https://linux-hardware.org/?probe=b2ca051044) | Jan 07, 2024 |
| ENTITY        | ENTYG11Q1                   | Notebook    | [f9b0c03994](https://linux-hardware.org/?probe=f9b0c03994) | Jan 07, 2024 |
| Star Labs     | StarLite                    | Notebook    | [751432d737](https://linux-hardware.org/?probe=751432d737) | Jan 07, 2024 |
| HP            | 255 G1                      | Notebook    | [c7391eb57a](https://linux-hardware.org/?probe=c7391eb57a) | Jan 07, 2024 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [f827ab96ab](https://linux-hardware.org/?probe=f827ab96ab) | Jan 07, 2024 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [64b1b511e6](https://linux-hardware.org/?probe=64b1b511e6) | Jan 07, 2024 |
| HP            | 255 G1                      | Notebook    | [0b734c978f](https://linux-hardware.org/?probe=0b734c978f) | Jan 06, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [14528ba1f9](https://linux-hardware.org/?probe=14528ba1f9) | Jan 06, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [60f51d8b49](https://linux-hardware.org/?probe=60f51d8b49) | Jan 06, 2024 |
| ASUSTek       | X551CA                      | Notebook    | [78faa77bac](https://linux-hardware.org/?probe=78faa77bac) | Jan 06, 2024 |
| AZW           | Speed S                     | Notebook    | [a16b812e0d](https://linux-hardware.org/?probe=a16b812e0d) | Jan 06, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [34f9702909](https://linux-hardware.org/?probe=34f9702909) | Jan 06, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d4c6189dfc](https://linux-hardware.org/?probe=d4c6189dfc) | Jan 06, 2024 |
| Microsoft     | Surface Pro 4               | Tablet      | [de7da888f4](https://linux-hardware.org/?probe=de7da888f4) | Jan 06, 2024 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [768439db71](https://linux-hardware.org/?probe=768439db71) | Jan 06, 2024 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [99a8eed63b](https://linux-hardware.org/?probe=99a8eed63b) | Jan 05, 2024 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [3a9475e1ae](https://linux-hardware.org/?probe=3a9475e1ae) | Jan 05, 2024 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [8a19e590f8](https://linux-hardware.org/?probe=8a19e590f8) | Jan 05, 2024 |
| Toshiba       | Satellite L50D-B            | Notebook    | [7a713e9106](https://linux-hardware.org/?probe=7a713e9106) | Jan 05, 2024 |
| Pegatron      | EVANS                       | Desktop     | [ae4c2b1fae](https://linux-hardware.org/?probe=ae4c2b1fae) | Jan 05, 2024 |
| HP            | ENVY Notebook               | Notebook    | [8a2c65e297](https://linux-hardware.org/?probe=8a2c65e297) | Jan 05, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e5a4807041](https://linux-hardware.org/?probe=e5a4807041) | Jan 05, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [f7ad5f683a](https://linux-hardware.org/?probe=f7ad5f683a) | Jan 04, 2024 |
| HP            | Mini 210-1000               | Notebook    | [ddd4183f45](https://linux-hardware.org/?probe=ddd4183f45) | Jan 04, 2024 |
| HP            | Mini 210-1000               | Notebook    | [65f80ec87f](https://linux-hardware.org/?probe=65f80ec87f) | Jan 04, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a7dd37b5a2](https://linux-hardware.org/?probe=a7dd37b5a2) | Jan 04, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [c23d61cde7](https://linux-hardware.org/?probe=c23d61cde7) | Jan 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [348b004789](https://linux-hardware.org/?probe=348b004789) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | Notebook    | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| HP            | 8105                        | Desktop     | [c0cf6c94e0](https://linux-hardware.org/?probe=c0cf6c94e0) | Jan 04, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [934cb11b0b](https://linux-hardware.org/?probe=934cb11b0b) | Jan 03, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [0e5397d3f1](https://linux-hardware.org/?probe=0e5397d3f1) | Jan 03, 2024 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [e923fbb11a](https://linux-hardware.org/?probe=e923fbb11a) | Jan 03, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2f31bf4a09](https://linux-hardware.org/?probe=2f31bf4a09) | Jan 03, 2024 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [6fe5c13887](https://linux-hardware.org/?probe=6fe5c13887) | Jan 03, 2024 |
| HP            | 3397                        | Desktop     | [3339eb00ce](https://linux-hardware.org/?probe=3339eb00ce) | Jan 03, 2024 |
| Dell          | Precision 5510              | Notebook    | [762ef434f5](https://linux-hardware.org/?probe=762ef434f5) | Jan 03, 2024 |
| ASRock        | A520M-ITX/ac                | Desktop     | [7bd61f9bd1](https://linux-hardware.org/?probe=7bd61f9bd1) | Jan 02, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [31c94a2bae](https://linux-hardware.org/?probe=31c94a2bae) | Jan 02, 2024 |
| Star Labs     | StarLite                    | Notebook    | [9f0fae17e5](https://linux-hardware.org/?probe=9f0fae17e5) | Jan 02, 2024 |
| Microsoft     | Surface Laptop 4            | Tablet      | [8ddde2905e](https://linux-hardware.org/?probe=8ddde2905e) | Jan 02, 2024 |
| Dell          | Precision M3800             | Notebook    | [5867b0c6eb](https://linux-hardware.org/?probe=5867b0c6eb) | Jan 02, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [814a75afd3](https://linux-hardware.org/?probe=814a75afd3) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | Notebook    | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| Dell          | Inspiron 15 3530            | Notebook    | [ee21ee0e37](https://linux-hardware.org/?probe=ee21ee0e37) | Jan 01, 2024 |
| ASRock        | Z77 Professional            | Desktop     | [d1d9fce85d](https://linux-hardware.org/?probe=d1d9fce85d) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d4335b1132](https://linux-hardware.org/?probe=d4335b1132) | Jan 01, 2024 |
| HP            | 82A2                        | Desktop     | [7cc3d17916](https://linux-hardware.org/?probe=7cc3d17916) | Jan 01, 2024 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [58557ae7c7](https://linux-hardware.org/?probe=58557ae7c7) | Jan 01, 2024 |
| Pegatron      | EVANS                       | Desktop     | [b2a67b83cd](https://linux-hardware.org/?probe=b2a67b83cd) | Jan 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [8a1771af4b](https://linux-hardware.org/?probe=8a1771af4b) | Jan 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2f1b4ada4b](https://linux-hardware.org/?probe=2f1b4ada4b) | Jan 01, 2024 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [4fb6fd51a2](https://linux-hardware.org/?probe=4fb6fd51a2) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f45ebb1f0d](https://linux-hardware.org/?probe=f45ebb1f0d) | Dec 31, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [eb264efa92](https://linux-hardware.org/?probe=eb264efa92) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [915031852a](https://linux-hardware.org/?probe=915031852a) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [ba1b2a738a](https://linux-hardware.org/?probe=ba1b2a738a) | Dec 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [2f8ea60a38](https://linux-hardware.org/?probe=2f8ea60a38) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [60da2c756f](https://linux-hardware.org/?probe=60da2c756f) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [88a9972a33](https://linux-hardware.org/?probe=88a9972a33) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [91be04698f](https://linux-hardware.org/?probe=91be04698f) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [f805c2c9fc](https://linux-hardware.org/?probe=f805c2c9fc) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0fa90555a](https://linux-hardware.org/?probe=e0fa90555a) | Dec 29, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [403210cab1](https://linux-hardware.org/?probe=403210cab1) | Dec 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [50eef7421d](https://linux-hardware.org/?probe=50eef7421d) | Dec 29, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [9104adc237](https://linux-hardware.org/?probe=9104adc237) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [9e856c326a](https://linux-hardware.org/?probe=9e856c326a) | Dec 29, 2023 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [2433b4bc75](https://linux-hardware.org/?probe=2433b4bc75) | Dec 29, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [617d953e8f](https://linux-hardware.org/?probe=617d953e8f) | Dec 29, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [587d9f4fcb](https://linux-hardware.org/?probe=587d9f4fcb) | Dec 29, 2023 |
| Acer          | Aspire F5-571               | Notebook    | [d28fac242c](https://linux-hardware.org/?probe=d28fac242c) | Dec 29, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [935d08358c](https://linux-hardware.org/?probe=935d08358c) | Dec 29, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [45be79a808](https://linux-hardware.org/?probe=45be79a808) | Dec 29, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3700165122](https://linux-hardware.org/?probe=3700165122) | Dec 28, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [ba96083a55](https://linux-hardware.org/?probe=ba96083a55) | Dec 28, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [50111db215](https://linux-hardware.org/?probe=50111db215) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee1b832527](https://linux-hardware.org/?probe=ee1b832527) | Dec 28, 2023 |
| Google        | Nami                        | Notebook    | [3d7f7ba09c](https://linux-hardware.org/?probe=3d7f7ba09c) | Dec 28, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [d132700b11](https://linux-hardware.org/?probe=d132700b11) | Dec 28, 2023 |
| AWOW          | AK41                        | Notebook    | [d081509ed9](https://linux-hardware.org/?probe=d081509ed9) | Dec 28, 2023 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [4600a758fa](https://linux-hardware.org/?probe=4600a758fa) | Dec 27, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | Notebook    | [3ec4d2a40d](https://linux-hardware.org/?probe=3ec4d2a40d) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | Notebook    | [eb40e7ad5c](https://linux-hardware.org/?probe=eb40e7ad5c) | Dec 27, 2023 |
| HP            | 2AFB                        | Desktop     | [5279d471aa](https://linux-hardware.org/?probe=5279d471aa) | Dec 27, 2023 |
| ASUSTek       | UN42                        | Desktop     | [1b146f734f](https://linux-hardware.org/?probe=1b146f734f) | Dec 27, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [f745deb3d7](https://linux-hardware.org/?probe=f745deb3d7) | Dec 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [32c3fcc941](https://linux-hardware.org/?probe=32c3fcc941) | Dec 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bfa7e572a4](https://linux-hardware.org/?probe=bfa7e572a4) | Dec 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [fde01139b9](https://linux-hardware.org/?probe=fde01139b9) | Dec 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [25466d5d3b](https://linux-hardware.org/?probe=25466d5d3b) | Dec 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d661150c95](https://linux-hardware.org/?probe=d661150c95) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [c4f9e9de5e](https://linux-hardware.org/?probe=c4f9e9de5e) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [c129debcae](https://linux-hardware.org/?probe=c129debcae) | Dec 27, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | Notebook    | [b602153aeb](https://linux-hardware.org/?probe=b602153aeb) | Dec 26, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [ad5a093909](https://linux-hardware.org/?probe=ad5a093909) | Dec 26, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [fae868ef79](https://linux-hardware.org/?probe=fae868ef79) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | Notebook    | [5a76629311](https://linux-hardware.org/?probe=5a76629311) | Dec 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [ca94325310](https://linux-hardware.org/?probe=ca94325310) | Dec 26, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [83c0e37ece](https://linux-hardware.org/?probe=83c0e37ece) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ab75ea56b](https://linux-hardware.org/?probe=4ab75ea56b) | Dec 25, 2023 |
| PC Special... | 14 Fusion Pro               | Notebook    | [76bf311c34](https://linux-hardware.org/?probe=76bf311c34) | Dec 25, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [e6cbc30aad](https://linux-hardware.org/?probe=e6cbc30aad) | Dec 25, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fea4a4753e](https://linux-hardware.org/?probe=fea4a4753e) | Dec 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1f14807c5e](https://linux-hardware.org/?probe=1f14807c5e) | Dec 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [6ec124a0c4](https://linux-hardware.org/?probe=6ec124a0c4) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [eb3b2bf56b](https://linux-hardware.org/?probe=eb3b2bf56b) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [f57d2e51fe](https://linux-hardware.org/?probe=f57d2e51fe) | Dec 24, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [a5ef57e596](https://linux-hardware.org/?probe=a5ef57e596) | Dec 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [915a47dab1](https://linux-hardware.org/?probe=915a47dab1) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [2474ae00d3](https://linux-hardware.org/?probe=2474ae00d3) | Dec 24, 2023 |
| Dell          | Latitude 5300               | Notebook    | [68336d8bc1](https://linux-hardware.org/?probe=68336d8bc1) | Dec 24, 2023 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [7690d56522](https://linux-hardware.org/?probe=7690d56522) | Dec 24, 2023 |
| Dell          | Inspiron 15 3530            | Notebook    | [0688896e27](https://linux-hardware.org/?probe=0688896e27) | Dec 23, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [ce31053fe2](https://linux-hardware.org/?probe=ce31053fe2) | Dec 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [82c13c188b](https://linux-hardware.org/?probe=82c13c188b) | Dec 23, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [c9555a34f2](https://linux-hardware.org/?probe=c9555a34f2) | Dec 23, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c6caf2cc7a](https://linux-hardware.org/?probe=c6caf2cc7a) | Dec 22, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [e6827a291e](https://linux-hardware.org/?probe=e6827a291e) | Dec 22, 2023 |
| Dell          | Latitude 7300               | Notebook    | [8792895835](https://linux-hardware.org/?probe=8792895835) | Dec 22, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [38a9810e94](https://linux-hardware.org/?probe=38a9810e94) | Dec 22, 2023 |
| Dell          | Latitude E5510              | Notebook    | [92074a5231](https://linux-hardware.org/?probe=92074a5231) | Dec 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [03491495da](https://linux-hardware.org/?probe=03491495da) | Dec 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [aa3d919a29](https://linux-hardware.org/?probe=aa3d919a29) | Dec 22, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [b49d16daf5](https://linux-hardware.org/?probe=b49d16daf5) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| Lenovo        | ThinkPad X280 20KEA00SUK    | Notebook    | [bc380b4334](https://linux-hardware.org/?probe=bc380b4334) | Dec 21, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [ecefa48588](https://linux-hardware.org/?probe=ecefa48588) | Dec 21, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [5dd9b40dd6](https://linux-hardware.org/?probe=5dd9b40dd6) | Dec 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [bb26992a0a](https://linux-hardware.org/?probe=bb26992a0a) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [7597019eca](https://linux-hardware.org/?probe=7597019eca) | Dec 21, 2023 |
| ASRock        | H610M-HVS                   | Desktop     | [25b5c11ccc](https://linux-hardware.org/?probe=25b5c11ccc) | Dec 20, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [088b5d3bba](https://linux-hardware.org/?probe=088b5d3bba) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [98eee633b1](https://linux-hardware.org/?probe=98eee633b1) | Dec 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [eef5dcab57](https://linux-hardware.org/?probe=eef5dcab57) | Dec 20, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb71670ca0](https://linux-hardware.org/?probe=cb71670ca0) | Dec 20, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [7aa12c94c1](https://linux-hardware.org/?probe=7aa12c94c1) | Dec 20, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [3003aeb5a9](https://linux-hardware.org/?probe=3003aeb5a9) | Dec 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [8e6c8be806](https://linux-hardware.org/?probe=8e6c8be806) | Dec 19, 2023 |
| Dell          | Latitude 5340               | Notebook    | [c9d3b3d7a7](https://linux-hardware.org/?probe=c9d3b3d7a7) | Dec 19, 2023 |
| HP            | Notebook                    | Notebook    | [31d6fc4280](https://linux-hardware.org/?probe=31d6fc4280) | Dec 19, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0fd7e9086a](https://linux-hardware.org/?probe=0fd7e9086a) | Dec 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWA16R0... | Notebook    | [4f1e1945a7](https://linux-hardware.org/?probe=4f1e1945a7) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [5781ca34c8](https://linux-hardware.org/?probe=5781ca34c8) | Dec 19, 2023 |
| Gigabyte      | Z590I VISION D              | Desktop     | [92531d60e9](https://linux-hardware.org/?probe=92531d60e9) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Dell          | Inspiron 15 3535            | Notebook    | [f86bf3e2f1](https://linux-hardware.org/?probe=f86bf3e2f1) | Dec 18, 2023 |
| ASRock        | B650M Pro RS                | Desktop     | [df96c996dd](https://linux-hardware.org/?probe=df96c996dd) | Dec 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [38b0463b4a](https://linux-hardware.org/?probe=38b0463b4a) | Dec 18, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [8f34c208f2](https://linux-hardware.org/?probe=8f34c208f2) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [8596edc762](https://linux-hardware.org/?probe=8596edc762) | Dec 18, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [a62323f9e3](https://linux-hardware.org/?probe=a62323f9e3) | Dec 18, 2023 |
| Valve         | Jupiter                     | Notebook    | [f8d7e441a5](https://linux-hardware.org/?probe=f8d7e441a5) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0376612ef7](https://linux-hardware.org/?probe=0376612ef7) | Dec 18, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [ac4adad071](https://linux-hardware.org/?probe=ac4adad071) | Dec 18, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [474668dbec](https://linux-hardware.org/?probe=474668dbec) | Dec 18, 2023 |
| DTV           | G5A-BTJ1900                 | Other       | [f6c12e7381](https://linux-hardware.org/?probe=f6c12e7381) | Dec 18, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [c0b618e2ab](https://linux-hardware.org/?probe=c0b618e2ab) | Dec 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [825b7230bc](https://linux-hardware.org/?probe=825b7230bc) | Dec 18, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [2d0eb33a7a](https://linux-hardware.org/?probe=2d0eb33a7a) | Dec 17, 2023 |
| Lenovo        | ThinkPad T420 4180PR1       | Notebook    | [2c0267b77e](https://linux-hardware.org/?probe=2c0267b77e) | Dec 17, 2023 |
| Dell          | Latitude E6400              | Notebook    | [855a8f55c4](https://linux-hardware.org/?probe=855a8f55c4) | Dec 17, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [ce25ba67fb](https://linux-hardware.org/?probe=ce25ba67fb) | Dec 17, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [209df55714](https://linux-hardware.org/?probe=209df55714) | Dec 17, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [28d755787e](https://linux-hardware.org/?probe=28d755787e) | Dec 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [25525c17e0](https://linux-hardware.org/?probe=25525c17e0) | Dec 17, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [316b12645c](https://linux-hardware.org/?probe=316b12645c) | Dec 17, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [0f2293e8d1](https://linux-hardware.org/?probe=0f2293e8d1) | Dec 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [402a34ec30](https://linux-hardware.org/?probe=402a34ec30) | Dec 17, 2023 |
| Samsung       | 930QED                      | Convertible | [90cf6b2c26](https://linux-hardware.org/?probe=90cf6b2c26) | Dec 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [d6c8debc47](https://linux-hardware.org/?probe=d6c8debc47) | Dec 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [9105f33be2](https://linux-hardware.org/?probe=9105f33be2) | Dec 16, 2023 |
| HP            | 829A                        | Mini pc     | [e0b2d004a0](https://linux-hardware.org/?probe=e0b2d004a0) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [36f9f51f5d](https://linux-hardware.org/?probe=36f9f51f5d) | Dec 16, 2023 |
| HP            | 3397                        | Desktop     | [7b379848f1](https://linux-hardware.org/?probe=7b379848f1) | Dec 16, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [52012e39df](https://linux-hardware.org/?probe=52012e39df) | Dec 16, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [3e93a62792](https://linux-hardware.org/?probe=3e93a62792) | Dec 16, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [0558258245](https://linux-hardware.org/?probe=0558258245) | Dec 16, 2023 |
| AZW           | GT-R                        | Notebook    | [205436106b](https://linux-hardware.org/?probe=205436106b) | Dec 16, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [5af488fb21](https://linux-hardware.org/?probe=5af488fb21) | Dec 16, 2023 |
| Dell          | 0MY764 A00                  | All in one  | [2fd4dc6486](https://linux-hardware.org/?probe=2fd4dc6486) | Dec 16, 2023 |
| Dell          | 0MY764 A00                  | All in one  | [ad39174db9](https://linux-hardware.org/?probe=ad39174db9) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [ec182b1b52](https://linux-hardware.org/?probe=ec182b1b52) | Dec 16, 2023 |
| HP            | 2AFB                        | Desktop     | [4160a75172](https://linux-hardware.org/?probe=4160a75172) | Dec 15, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [d63cdec5eb](https://linux-hardware.org/?probe=d63cdec5eb) | Dec 15, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [3a2a8878eb](https://linux-hardware.org/?probe=3a2a8878eb) | Dec 15, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [69de9d26c7](https://linux-hardware.org/?probe=69de9d26c7) | Dec 15, 2023 |
| HP            | 8592                        | Desktop     | [511feb6066](https://linux-hardware.org/?probe=511feb6066) | Dec 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [921d38d2df](https://linux-hardware.org/?probe=921d38d2df) | Dec 15, 2023 |
| HP            | 8592                        | Desktop     | [c5817452fd](https://linux-hardware.org/?probe=c5817452fd) | Dec 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [67a32f0dd0](https://linux-hardware.org/?probe=67a32f0dd0) | Dec 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [283dc2dab5](https://linux-hardware.org/?probe=283dc2dab5) | Dec 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [39f4b40998](https://linux-hardware.org/?probe=39f4b40998) | Dec 14, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7e358e1c4b](https://linux-hardware.org/?probe=7e358e1c4b) | Dec 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [93e9419d49](https://linux-hardware.org/?probe=93e9419d49) | Dec 14, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3280eaaea1](https://linux-hardware.org/?probe=3280eaaea1) | Dec 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [bfca25b6c1](https://linux-hardware.org/?probe=bfca25b6c1) | Dec 14, 2023 |
| Schenker      | XMG NEO (E23)               | Notebook    | [ce84d5a464](https://linux-hardware.org/?probe=ce84d5a464) | Dec 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [1b81d3191b](https://linux-hardware.org/?probe=1b81d3191b) | Dec 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5eaaa9dcdc](https://linux-hardware.org/?probe=5eaaa9dcdc) | Dec 13, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [33d1f683ba](https://linux-hardware.org/?probe=33d1f683ba) | Dec 13, 2023 |
| Acer          | TMP645-M                    | Notebook    | [55c3db256a](https://linux-hardware.org/?probe=55c3db256a) | Dec 13, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3f2ed65cf0](https://linux-hardware.org/?probe=3f2ed65cf0) | Dec 13, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c266418637](https://linux-hardware.org/?probe=c266418637) | Dec 13, 2023 |
| Valve         | Galileo                     | Notebook    | [835c844aed](https://linux-hardware.org/?probe=835c844aed) | Dec 13, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9b20467a02](https://linux-hardware.org/?probe=9b20467a02) | Dec 13, 2023 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [25017a9de6](https://linux-hardware.org/?probe=25017a9de6) | Dec 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [920939b6c0](https://linux-hardware.org/?probe=920939b6c0) | Dec 13, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [01f7be08ae](https://linux-hardware.org/?probe=01f7be08ae) | Dec 13, 2023 |
| MSI           | MS-16Y1                     | Notebook    | [41ce29bec7](https://linux-hardware.org/?probe=41ce29bec7) | Dec 12, 2023 |
| GEO           | GEOBOOK 2E                  | Notebook    | [86b33e33ca](https://linux-hardware.org/?probe=86b33e33ca) | Dec 12, 2023 |
| GEO           | GEOBOOK 2E                  | Notebook    | [cac69d7624](https://linux-hardware.org/?probe=cac69d7624) | Dec 12, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [46b5f7ee7b](https://linux-hardware.org/?probe=46b5f7ee7b) | Dec 12, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [0a531cbda1](https://linux-hardware.org/?probe=0a531cbda1) | Dec 12, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [bcf9fba46f](https://linux-hardware.org/?probe=bcf9fba46f) | Dec 12, 2023 |
| Samsung       | R720                        | Notebook    | [a434163017](https://linux-hardware.org/?probe=a434163017) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [16e9faf4e6](https://linux-hardware.org/?probe=16e9faf4e6) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [05ceb8703b](https://linux-hardware.org/?probe=05ceb8703b) | Dec 12, 2023 |
| Samsung       | R720                        | Notebook    | [b7a2f3044e](https://linux-hardware.org/?probe=b7a2f3044e) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [c9eae3e15f](https://linux-hardware.org/?probe=c9eae3e15f) | Dec 12, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [39a6569b14](https://linux-hardware.org/?probe=39a6569b14) | Dec 12, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [e71cda8b04](https://linux-hardware.org/?probe=e71cda8b04) | Dec 12, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [c3d3cc14e8](https://linux-hardware.org/?probe=c3d3cc14e8) | Dec 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [f49dd0f010](https://linux-hardware.org/?probe=f49dd0f010) | Dec 12, 2023 |
| Dell          | 07WP95 A02                  | Desktop     | [b5d957b7ec](https://linux-hardware.org/?probe=b5d957b7ec) | Dec 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [31b92c3112](https://linux-hardware.org/?probe=31b92c3112) | Dec 11, 2023 |
| Entroware     | Poseidon                    | Desktop     | [88c52d72cc](https://linux-hardware.org/?probe=88c52d72cc) | Dec 11, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [ef34073e18](https://linux-hardware.org/?probe=ef34073e18) | Dec 11, 2023 |
| Simply NUC    | NUC12ZRB                    | Mini pc     | [773fd495da](https://linux-hardware.org/?probe=773fd495da) | Dec 11, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [3d89daa3fa](https://linux-hardware.org/?probe=3d89daa3fa) | Dec 11, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [76c38ed49a](https://linux-hardware.org/?probe=76c38ed49a) | Dec 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | Notebook    | [f604df3e48](https://linux-hardware.org/?probe=f604df3e48) | Dec 10, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [237db70b40](https://linux-hardware.org/?probe=237db70b40) | Dec 10, 2023 |
| Acer          | Aspire 6930G                | Notebook    | [eea9d9e525](https://linux-hardware.org/?probe=eea9d9e525) | Dec 10, 2023 |
| ASUSTek       | P8H61-MX USB3               | Desktop     | [60d3606ca9](https://linux-hardware.org/?probe=60d3606ca9) | Dec 10, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [35a10a1ae2](https://linux-hardware.org/?probe=35a10a1ae2) | Dec 10, 2023 |
| Sony          | SVE1511K1EW                 | Notebook    | [34875b90c4](https://linux-hardware.org/?probe=34875b90c4) | Dec 10, 2023 |
| MSI           | GS43VR 7RE                  | Notebook    | [23feee91ff](https://linux-hardware.org/?probe=23feee91ff) | Dec 10, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [a0d6ba0881](https://linux-hardware.org/?probe=a0d6ba0881) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [825eb9ef88](https://linux-hardware.org/?probe=825eb9ef88) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [e8705e98dc](https://linux-hardware.org/?probe=e8705e98dc) | Dec 08, 2023 |
| Dell          | G5 5590                     | Notebook    | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0fb56c3b77](https://linux-hardware.org/?probe=0fb56c3b77) | Dec 08, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [df7eb64dd1](https://linux-hardware.org/?probe=df7eb64dd1) | Dec 08, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [3ca33a4b88](https://linux-hardware.org/?probe=3ca33a4b88) | Dec 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0403680fc9](https://linux-hardware.org/?probe=0403680fc9) | Dec 07, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [031fd2298b](https://linux-hardware.org/?probe=031fd2298b) | Dec 07, 2023 |
| Gigabyte      | 970A-DS3                    | Desktop     | [cad7bc7542](https://linux-hardware.org/?probe=cad7bc7542) | Dec 07, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [5ba88bb243](https://linux-hardware.org/?probe=5ba88bb243) | Dec 06, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| HP            | 2AFB                        | Desktop     | [a91d9cd265](https://linux-hardware.org/?probe=a91d9cd265) | Dec 06, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [34d2104b8a](https://linux-hardware.org/?probe=34d2104b8a) | Dec 06, 2023 |
| Tactus        | IOTA Flo                    | Notebook    | [a79fecbfad](https://linux-hardware.org/?probe=a79fecbfad) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [38945d6d2e](https://linux-hardware.org/?probe=38945d6d2e) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [ce624b95df](https://linux-hardware.org/?probe=ce624b95df) | Dec 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [ad7bb46855](https://linux-hardware.org/?probe=ad7bb46855) | Dec 05, 2023 |
| HP            | ProBook 4540s               | Notebook    | [53eab461fb](https://linux-hardware.org/?probe=53eab461fb) | Dec 05, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [2cc0150e87](https://linux-hardware.org/?probe=2cc0150e87) | Dec 05, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [dfc33bff7a](https://linux-hardware.org/?probe=dfc33bff7a) | Dec 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [eebdbc8611](https://linux-hardware.org/?probe=eebdbc8611) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [fd95385327](https://linux-hardware.org/?probe=fd95385327) | Dec 04, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [8a8bfb131c](https://linux-hardware.org/?probe=8a8bfb131c) | Dec 04, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [54ecb0a8b8](https://linux-hardware.org/?probe=54ecb0a8b8) | Dec 04, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [73fa5936a1](https://linux-hardware.org/?probe=73fa5936a1) | Dec 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [325091c7a2](https://linux-hardware.org/?probe=325091c7a2) | Dec 04, 2023 |
| AZW           | S5 V01                      | Mini pc     | [326e621078](https://linux-hardware.org/?probe=326e621078) | Dec 04, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [dc816e1423](https://linux-hardware.org/?probe=dc816e1423) | Dec 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0caac1007d](https://linux-hardware.org/?probe=0caac1007d) | Dec 04, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [c2e09d65d5](https://linux-hardware.org/?probe=c2e09d65d5) | Dec 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f013a81cbb](https://linux-hardware.org/?probe=f013a81cbb) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [7b5f2ca2f9](https://linux-hardware.org/?probe=7b5f2ca2f9) | Dec 03, 2023 |
| Dell          | Precision 7530              | Notebook    | [e75b16ca5e](https://linux-hardware.org/?probe=e75b16ca5e) | Dec 03, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5e8bdafa0a](https://linux-hardware.org/?probe=5e8bdafa0a) | Dec 03, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [3c6a13271b](https://linux-hardware.org/?probe=3c6a13271b) | Dec 03, 2023 |
| Trigkey       | Green G4 10                 | Desktop     | [bade24732d](https://linux-hardware.org/?probe=bade24732d) | Dec 03, 2023 |
| Trigkey       | Green G4 10                 | Desktop     | [b3d175cddb](https://linux-hardware.org/?probe=b3d175cddb) | Dec 03, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [7f9b2fa7e0](https://linux-hardware.org/?probe=7f9b2fa7e0) | Dec 03, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [08ce611291](https://linux-hardware.org/?probe=08ce611291) | Dec 02, 2023 |
| HP            | ProBook 4540s               | Notebook    | [d83489845d](https://linux-hardware.org/?probe=d83489845d) | Dec 02, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [e6fd8cf7f1](https://linux-hardware.org/?probe=e6fd8cf7f1) | Dec 02, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [bb746b7506](https://linux-hardware.org/?probe=bb746b7506) | Dec 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [744c430aa7](https://linux-hardware.org/?probe=744c430aa7) | Dec 02, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [5cf002f5af](https://linux-hardware.org/?probe=5cf002f5af) | Dec 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [f366381075](https://linux-hardware.org/?probe=f366381075) | Dec 02, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [8fd7437767](https://linux-hardware.org/?probe=8fd7437767) | Dec 01, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV0R     | Notebook    | [933f88f7e6](https://linux-hardware.org/?probe=933f88f7e6) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [1ba43c09a6](https://linux-hardware.org/?probe=1ba43c09a6) | Nov 30, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [a4830c392f](https://linux-hardware.org/?probe=a4830c392f) | Nov 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [545d093510](https://linux-hardware.org/?probe=545d093510) | Nov 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [2251ba47fb](https://linux-hardware.org/?probe=2251ba47fb) | Nov 30, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [37545bd915](https://linux-hardware.org/?probe=37545bd915) | Nov 30, 2023 |
| HP            | 1495                        | Desktop     | [9dcb53a8c2](https://linux-hardware.org/?probe=9dcb53a8c2) | Nov 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [21a183f050](https://linux-hardware.org/?probe=21a183f050) | Nov 30, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [5e8be973c6](https://linux-hardware.org/?probe=5e8be973c6) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [2c9b3f229e](https://linux-hardware.org/?probe=2c9b3f229e) | Nov 29, 2023 |
| Unknown       | HX90                        | Desktop     | [54a2eb227b](https://linux-hardware.org/?probe=54a2eb227b) | Nov 29, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [dae10e70d0](https://linux-hardware.org/?probe=dae10e70d0) | Nov 29, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a97b3bd106](https://linux-hardware.org/?probe=a97b3bd106) | Nov 29, 2023 |
| Lenovo        | ThinkPad P52s 20LCA0ANUK    | Notebook    | [2cf85106d8](https://linux-hardware.org/?probe=2cf85106d8) | Nov 29, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [74536087d5](https://linux-hardware.org/?probe=74536087d5) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [d9e4a9a2cd](https://linux-hardware.org/?probe=d9e4a9a2cd) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e3e8042ebf](https://linux-hardware.org/?probe=e3e8042ebf) | Nov 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fc4e66ac12](https://linux-hardware.org/?probe=fc4e66ac12) | Nov 29, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [96af3871d2](https://linux-hardware.org/?probe=96af3871d2) | Nov 29, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [4948ddc4be](https://linux-hardware.org/?probe=4948ddc4be) | Nov 29, 2023 |
| Dell          | Inspiron 15 3530            | Notebook    | [410e2cc867](https://linux-hardware.org/?probe=410e2cc867) | Nov 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [b4fbd61258](https://linux-hardware.org/?probe=b4fbd61258) | Nov 28, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f2b1e6e4a9](https://linux-hardware.org/?probe=f2b1e6e4a9) | Nov 28, 2023 |
| Dell          | Latitude 7390               | Notebook    | [4cacd41fee](https://linux-hardware.org/?probe=4cacd41fee) | Nov 28, 2023 |
| AWOW          | AK41                        | Notebook    | [34d9bc9a34](https://linux-hardware.org/?probe=34d9bc9a34) | Nov 28, 2023 |
| AWOW          | AK41                        | Notebook    | [17f3a70619](https://linux-hardware.org/?probe=17f3a70619) | Nov 28, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [491dd5c51b](https://linux-hardware.org/?probe=491dd5c51b) | Nov 28, 2023 |
| Samsung       | 930QED                      | Convertible | [39e7044708](https://linux-hardware.org/?probe=39e7044708) | Nov 28, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [c867b76eff](https://linux-hardware.org/?probe=c867b76eff) | Nov 28, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [7be81f9e9c](https://linux-hardware.org/?probe=7be81f9e9c) | Nov 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7378c9d9a4](https://linux-hardware.org/?probe=7378c9d9a4) | Nov 28, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [549e026701](https://linux-hardware.org/?probe=549e026701) | Nov 28, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [5ab684ace6](https://linux-hardware.org/?probe=5ab684ace6) | Nov 27, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [bad53e91fc](https://linux-hardware.org/?probe=bad53e91fc) | Nov 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [d4488776c4](https://linux-hardware.org/?probe=d4488776c4) | Nov 27, 2023 |
| Dell          | Inspiron 1012               | Notebook    | [ffe483f5fd](https://linux-hardware.org/?probe=ffe483f5fd) | Nov 27, 2023 |
| ASUSTek       | G11CB                       | Desktop     | [31f2fc857d](https://linux-hardware.org/?probe=31f2fc857d) | Nov 27, 2023 |
| AZW           | GTR V01                     | Mini pc     | [36be46a799](https://linux-hardware.org/?probe=36be46a799) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| Dell          | Latitude D830               | Notebook    | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | 8184 X4                     | Desktop     | [0813228fc1](https://linux-hardware.org/?probe=0813228fc1) | Nov 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0RK00    | Notebook    | [96642d7e8e](https://linux-hardware.org/?probe=96642d7e8e) | Nov 27, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [16761c9d57](https://linux-hardware.org/?probe=16761c9d57) | Nov 27, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [2ccf3a5db5](https://linux-hardware.org/?probe=2ccf3a5db5) | Nov 26, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dda972d27c](https://linux-hardware.org/?probe=dda972d27c) | Nov 26, 2023 |
| HP            | 8704                        | Desktop     | [594422dbde](https://linux-hardware.org/?probe=594422dbde) | Nov 26, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [f2856297d6](https://linux-hardware.org/?probe=f2856297d6) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e552669069](https://linux-hardware.org/?probe=e552669069) | Nov 26, 2023 |
| HP            | 2820h                       | Desktop     | [b1659e17cb](https://linux-hardware.org/?probe=b1659e17cb) | Nov 26, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [cceb19120f](https://linux-hardware.org/?probe=cceb19120f) | Nov 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b0f55cc692](https://linux-hardware.org/?probe=b0f55cc692) | Nov 26, 2023 |
| Toshiba       | TECRA R940                  | Notebook    | [14de9f481a](https://linux-hardware.org/?probe=14de9f481a) | Nov 26, 2023 |
| Lenovo        | ThinkPad Edge E325 12973... | Notebook    | [0f165c67ac](https://linux-hardware.org/?probe=0f165c67ac) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [26b99168f7](https://linux-hardware.org/?probe=26b99168f7) | Nov 26, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e4c365b554](https://linux-hardware.org/?probe=e4c365b554) | Nov 26, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d327adff80](https://linux-hardware.org/?probe=d327adff80) | Nov 26, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [44dfa50d7d](https://linux-hardware.org/?probe=44dfa50d7d) | Nov 25, 2023 |
| MSI           | MAG B760M MORTAR WIFI DD... | Desktop     | [b11fcf42c2](https://linux-hardware.org/?probe=b11fcf42c2) | Nov 25, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [99daa92571](https://linux-hardware.org/?probe=99daa92571) | Nov 25, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [8973295484](https://linux-hardware.org/?probe=8973295484) | Nov 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [5bbefae656](https://linux-hardware.org/?probe=5bbefae656) | Nov 25, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [22bbe29da3](https://linux-hardware.org/?probe=22bbe29da3) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [082c36ab01](https://linux-hardware.org/?probe=082c36ab01) | Nov 25, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [62033adcb7](https://linux-hardware.org/?probe=62033adcb7) | Nov 25, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [4c874a153e](https://linux-hardware.org/?probe=4c874a153e) | Nov 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [5c29cfeb41](https://linux-hardware.org/?probe=5c29cfeb41) | Nov 25, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [1bf1e47f81](https://linux-hardware.org/?probe=1bf1e47f81) | Nov 24, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [4f78b76325](https://linux-hardware.org/?probe=4f78b76325) | Nov 24, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [d8bb656eaf](https://linux-hardware.org/?probe=d8bb656eaf) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [52e54c41e4](https://linux-hardware.org/?probe=52e54c41e4) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [0b9056b730](https://linux-hardware.org/?probe=0b9056b730) | Nov 24, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [a2313adb82](https://linux-hardware.org/?probe=a2313adb82) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f4a77c64b0](https://linux-hardware.org/?probe=f4a77c64b0) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1302407078](https://linux-hardware.org/?probe=1302407078) | Nov 24, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [7871e7654b](https://linux-hardware.org/?probe=7871e7654b) | Nov 24, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [16e9af1d1a](https://linux-hardware.org/?probe=16e9af1d1a) | Nov 24, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [e210f3a972](https://linux-hardware.org/?probe=e210f3a972) | Nov 24, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [59a3d34f64](https://linux-hardware.org/?probe=59a3d34f64) | Nov 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [0c58fa47b9](https://linux-hardware.org/?probe=0c58fa47b9) | Nov 24, 2023 |
| Dell          | 0TP406                      | Desktop     | [cc0c592ca4](https://linux-hardware.org/?probe=cc0c592ca4) | Nov 24, 2023 |
| Linx          | LINX1010L                   | Notebook    | [07d470eaac](https://linux-hardware.org/?probe=07d470eaac) | Nov 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b98f204f02](https://linux-hardware.org/?probe=b98f204f02) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | Notebook    | [e0be96f7e5](https://linux-hardware.org/?probe=e0be96f7e5) | Nov 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [7d55f31a65](https://linux-hardware.org/?probe=7d55f31a65) | Nov 23, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [48677cfae1](https://linux-hardware.org/?probe=48677cfae1) | Nov 23, 2023 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [31b35710ab](https://linux-hardware.org/?probe=31b35710ab) | Nov 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [b1d5cf3254](https://linux-hardware.org/?probe=b1d5cf3254) | Nov 23, 2023 |
| HP            | 3029h                       | Desktop     | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| Intel         | NUC7i5DNB J57626-502        | Mini pc     | [11e1ee6d39](https://linux-hardware.org/?probe=11e1ee6d39) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [24ebfe35c8](https://linux-hardware.org/?probe=24ebfe35c8) | Nov 22, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [b564a39ed5](https://linux-hardware.org/?probe=b564a39ed5) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [bcec28eaaa](https://linux-hardware.org/?probe=bcec28eaaa) | Nov 22, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7728d0ab4b](https://linux-hardware.org/?probe=7728d0ab4b) | Nov 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [157c8167b7](https://linux-hardware.org/?probe=157c8167b7) | Nov 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [525a89cf72](https://linux-hardware.org/?probe=525a89cf72) | Nov 22, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [5ff6b78e09](https://linux-hardware.org/?probe=5ff6b78e09) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [205b0b2438](https://linux-hardware.org/?probe=205b0b2438) | Nov 22, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [007d6a928b](https://linux-hardware.org/?probe=007d6a928b) | Nov 21, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [8f50ee2a5f](https://linux-hardware.org/?probe=8f50ee2a5f) | Nov 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [00c164e154](https://linux-hardware.org/?probe=00c164e154) | Nov 21, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [c3fc46a4a5](https://linux-hardware.org/?probe=c3fc46a4a5) | Nov 21, 2023 |
| GEO           | GeoFlex 110                 | Convertible | [48186c506a](https://linux-hardware.org/?probe=48186c506a) | Nov 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ec55064f1c](https://linux-hardware.org/?probe=ec55064f1c) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| GEO           | GeoFlex 110                 | Convertible | [cbb890150c](https://linux-hardware.org/?probe=cbb890150c) | Nov 20, 2023 |
| GEO           | GeoFlex 110                 | Convertible | [f8965dd876](https://linux-hardware.org/?probe=f8965dd876) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [7795e6e71f](https://linux-hardware.org/?probe=7795e6e71f) | Nov 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f58ea2a820](https://linux-hardware.org/?probe=f58ea2a820) | Nov 20, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [26ebeb2504](https://linux-hardware.org/?probe=26ebeb2504) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| Jumper        | EZbook                      | Notebook    | [f41c8192dc](https://linux-hardware.org/?probe=f41c8192dc) | Nov 20, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [db14a6cc67](https://linux-hardware.org/?probe=db14a6cc67) | Nov 20, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [9bf1dda551](https://linux-hardware.org/?probe=9bf1dda551) | Nov 19, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [7e047fc166](https://linux-hardware.org/?probe=7e047fc166) | Nov 19, 2023 |
| iOTA          | IOTA2320                    | Notebook    | [5c4d630f23](https://linux-hardware.org/?probe=5c4d630f23) | Nov 19, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [0de89fd40b](https://linux-hardware.org/?probe=0de89fd40b) | Nov 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [abaa669493](https://linux-hardware.org/?probe=abaa669493) | Nov 19, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [07fadadf4b](https://linux-hardware.org/?probe=07fadadf4b) | Nov 19, 2023 |
| HP            | 2B47                        | Desktop     | [86e6bb9503](https://linux-hardware.org/?probe=86e6bb9503) | Nov 19, 2023 |
| HP            | 2B47                        | Desktop     | [ba5e6806fc](https://linux-hardware.org/?probe=ba5e6806fc) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [a566513a93](https://linux-hardware.org/?probe=a566513a93) | Nov 19, 2023 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [be4bd9aeaf](https://linux-hardware.org/?probe=be4bd9aeaf) | Nov 18, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [fed171dba3](https://linux-hardware.org/?probe=fed171dba3) | Nov 18, 2023 |
| Dell          | Precision M6800             | Notebook    | [14dc3b5711](https://linux-hardware.org/?probe=14dc3b5711) | Nov 18, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [bfbed17470](https://linux-hardware.org/?probe=bfbed17470) | Nov 18, 2023 |
| Dell          | Inspiron 7591               | Notebook    | [edb7712542](https://linux-hardware.org/?probe=edb7712542) | Nov 18, 2023 |
| Dell          | 0DY62R A01                  | Desktop     | [03f9c7a1f2](https://linux-hardware.org/?probe=03f9c7a1f2) | Nov 17, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [0ebd3e6dd0](https://linux-hardware.org/?probe=0ebd3e6dd0) | Nov 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [8f0b8a5f62](https://linux-hardware.org/?probe=8f0b8a5f62) | Nov 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [6b4903cbb7](https://linux-hardware.org/?probe=6b4903cbb7) | Nov 17, 2023 |
| Google        | Liara                       | Notebook    | [0180a501ac](https://linux-hardware.org/?probe=0180a501ac) | Nov 17, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [9bb04e6b68](https://linux-hardware.org/?probe=9bb04e6b68) | Nov 17, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [17cf4dd653](https://linux-hardware.org/?probe=17cf4dd653) | Nov 17, 2023 |
| Google        | Liara                       | Notebook    | [081111241a](https://linux-hardware.org/?probe=081111241a) | Nov 16, 2023 |
| Google        | Liara                       | Notebook    | [c63d296cc8](https://linux-hardware.org/?probe=c63d296cc8) | Nov 16, 2023 |
| HP            | 89DC 0100                   | All in one  | [8de41c667e](https://linux-hardware.org/?probe=8de41c667e) | Nov 16, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [69d85e6c31](https://linux-hardware.org/?probe=69d85e6c31) | Nov 16, 2023 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [dbcccfee47](https://linux-hardware.org/?probe=dbcccfee47) | Nov 16, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [343e6ecd28](https://linux-hardware.org/?probe=343e6ecd28) | Nov 16, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [794f73f426](https://linux-hardware.org/?probe=794f73f426) | Nov 16, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [07a03ff43b](https://linux-hardware.org/?probe=07a03ff43b) | Nov 16, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a95e23a38b](https://linux-hardware.org/?probe=a95e23a38b) | Nov 16, 2023 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [54383b8394](https://linux-hardware.org/?probe=54383b8394) | Nov 16, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [b166167703](https://linux-hardware.org/?probe=b166167703) | Nov 16, 2023 |
| NZXT          | N7 B650E                    | Desktop     | [588de38c13](https://linux-hardware.org/?probe=588de38c13) | Nov 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [c7ef1a8bbd](https://linux-hardware.org/?probe=c7ef1a8bbd) | Nov 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [63ba7cf0b1](https://linux-hardware.org/?probe=63ba7cf0b1) | Nov 16, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [7e0ac6c6d6](https://linux-hardware.org/?probe=7e0ac6c6d6) | Nov 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8a19a6498c](https://linux-hardware.org/?probe=8a19a6498c) | Nov 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [844843779e](https://linux-hardware.org/?probe=844843779e) | Nov 16, 2023 |
| Intel         | DQ77MK AAG39642-500         | Desktop     | [19d77470a5](https://linux-hardware.org/?probe=19d77470a5) | Nov 16, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | Notebook    | [669eb1edcb](https://linux-hardware.org/?probe=669eb1edcb) | Nov 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [389f2adb17](https://linux-hardware.org/?probe=389f2adb17) | Nov 16, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [bd7e176e90](https://linux-hardware.org/?probe=bd7e176e90) | Nov 16, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [75a4902414](https://linux-hardware.org/?probe=75a4902414) | Nov 16, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [c951dffd5f](https://linux-hardware.org/?probe=c951dffd5f) | Nov 15, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [cc83fead4c](https://linux-hardware.org/?probe=cc83fead4c) | Nov 15, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [5992237ea5](https://linux-hardware.org/?probe=5992237ea5) | Nov 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [821a98f0f9](https://linux-hardware.org/?probe=821a98f0f9) | Nov 15, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [694833562c](https://linux-hardware.org/?probe=694833562c) | Nov 15, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [90bcff6517](https://linux-hardware.org/?probe=90bcff6517) | Nov 15, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [dc42526823](https://linux-hardware.org/?probe=dc42526823) | Nov 15, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [27fb977584](https://linux-hardware.org/?probe=27fb977584) | Nov 15, 2023 |
| Supermicro    | X11SPM-F                    | Server      | [fa3fb34e95](https://linux-hardware.org/?probe=fa3fb34e95) | Nov 15, 2023 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [7580fdc874](https://linux-hardware.org/?probe=7580fdc874) | Nov 15, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [e91aa41101](https://linux-hardware.org/?probe=e91aa41101) | Nov 15, 2023 |
| Alienware     | 14                          | Notebook    | [3f12c6cbcd](https://linux-hardware.org/?probe=3f12c6cbcd) | Nov 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [6a6b0096bb](https://linux-hardware.org/?probe=6a6b0096bb) | Nov 15, 2023 |
| Dell          | Latitude 5520               | Notebook    | [a50a13d22b](https://linux-hardware.org/?probe=a50a13d22b) | Nov 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [59f539dd3b](https://linux-hardware.org/?probe=59f539dd3b) | Nov 14, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [6a560e9f7c](https://linux-hardware.org/?probe=6a560e9f7c) | Nov 14, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Alienware     | 0P0JWX A00                  | Desktop     | [06fd25c3b5](https://linux-hardware.org/?probe=06fd25c3b5) | Nov 14, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [551661ff00](https://linux-hardware.org/?probe=551661ff00) | Nov 14, 2023 |
| Acer          | Aspire E1-572P              | Notebook    | [8644bc6bf3](https://linux-hardware.org/?probe=8644bc6bf3) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [23196bda4d](https://linux-hardware.org/?probe=23196bda4d) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [7b17ba0f7f](https://linux-hardware.org/?probe=7b17ba0f7f) | Nov 14, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [8c49972e61](https://linux-hardware.org/?probe=8c49972e61) | Nov 14, 2023 |
| AWOW          | AK41                        | Notebook    | [5d9f671218](https://linux-hardware.org/?probe=5d9f671218) | Nov 14, 2023 |
| AWOW          | AK41                        | Notebook    | [89e2926ff6](https://linux-hardware.org/?probe=89e2926ff6) | Nov 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e3926c718f](https://linux-hardware.org/?probe=e3926c718f) | Nov 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4f7bc6e075](https://linux-hardware.org/?probe=4f7bc6e075) | Nov 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [917ab5dcf0](https://linux-hardware.org/?probe=917ab5dcf0) | Nov 14, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [6ce3699c41](https://linux-hardware.org/?probe=6ce3699c41) | Nov 14, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [3e5fd22123](https://linux-hardware.org/?probe=3e5fd22123) | Nov 14, 2023 |
| Clevo         | W55xEU                      | Notebook    | [52795e38fa](https://linux-hardware.org/?probe=52795e38fa) | Nov 14, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [edc5aa4d33](https://linux-hardware.org/?probe=edc5aa4d33) | Nov 13, 2023 |
| HP            | 89DC 0100                   | All in one  | [c4d58d61e9](https://linux-hardware.org/?probe=c4d58d61e9) | Nov 13, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8e95b24f18](https://linux-hardware.org/?probe=8e95b24f18) | Nov 13, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [e592b6bf5d](https://linux-hardware.org/?probe=e592b6bf5d) | Nov 13, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [c143de0389](https://linux-hardware.org/?probe=c143de0389) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [00791aa199](https://linux-hardware.org/?probe=00791aa199) | Nov 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ed85cdf855](https://linux-hardware.org/?probe=ed85cdf855) | Nov 13, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [6c532c337f](https://linux-hardware.org/?probe=6c532c337f) | Nov 12, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [2651393e60](https://linux-hardware.org/?probe=2651393e60) | Nov 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [81dca17f20](https://linux-hardware.org/?probe=81dca17f20) | Nov 12, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [9ae5ddcf15](https://linux-hardware.org/?probe=9ae5ddcf15) | Nov 12, 2023 |
| Trigkey       | Green G4 10                 | Desktop     | [13e4a51787](https://linux-hardware.org/?probe=13e4a51787) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b2e3f1f31](https://linux-hardware.org/?probe=8b2e3f1f31) | Nov 12, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [c3e1b8c995](https://linux-hardware.org/?probe=c3e1b8c995) | Nov 12, 2023 |
| Linx          | LINX1010B                   | Notebook    | [aa641d2775](https://linux-hardware.org/?probe=aa641d2775) | Nov 12, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [b310ceb608](https://linux-hardware.org/?probe=b310ceb608) | Nov 12, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [f0db6bb1ae](https://linux-hardware.org/?probe=f0db6bb1ae) | Nov 11, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [df40ded027](https://linux-hardware.org/?probe=df40ded027) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [4c24ca4aa2](https://linux-hardware.org/?probe=4c24ca4aa2) | Nov 11, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [062edee7f6](https://linux-hardware.org/?probe=062edee7f6) | Nov 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [029e4d74e4](https://linux-hardware.org/?probe=029e4d74e4) | Nov 10, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f5147fc0f5](https://linux-hardware.org/?probe=f5147fc0f5) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [3b4f0e52cf](https://linux-hardware.org/?probe=3b4f0e52cf) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [ea0ea2dcff](https://linux-hardware.org/?probe=ea0ea2dcff) | Nov 10, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [a6085bc08f](https://linux-hardware.org/?probe=a6085bc08f) | Nov 10, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [a6a53a60f0](https://linux-hardware.org/?probe=a6a53a60f0) | Nov 10, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [e8cbd8b1b9](https://linux-hardware.org/?probe=e8cbd8b1b9) | Nov 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8cbcd6be](https://linux-hardware.org/?probe=ff8cbcd6be) | Nov 09, 2023 |
| Lenovo        | ThinkPad T420 4180AZ8       | Notebook    | [089405c957](https://linux-hardware.org/?probe=089405c957) | Nov 09, 2023 |
| Dell          | 0TY565                      | Desktop     | [9bf6328f12](https://linux-hardware.org/?probe=9bf6328f12) | Nov 09, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [5a4538afb3](https://linux-hardware.org/?probe=5a4538afb3) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A-1CK         | Notebook    | [630df1e190](https://linux-hardware.org/?probe=630df1e190) | Nov 09, 2023 |
| Toshiba       | Satellite C50-A-1CK         | Notebook    | [9eb1ed3f2b](https://linux-hardware.org/?probe=9eb1ed3f2b) | Nov 09, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [f107797037](https://linux-hardware.org/?probe=f107797037) | Nov 09, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [669cb641ab](https://linux-hardware.org/?probe=669cb641ab) | Nov 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [2e7ed7b6c8](https://linux-hardware.org/?probe=2e7ed7b6c8) | Nov 09, 2023 |
| Lenovo        | 3106 SDK0J40700 WIN 3258... | Desktop     | [95cf0f4ff0](https://linux-hardware.org/?probe=95cf0f4ff0) | Nov 08, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e46ed9f47e](https://linux-hardware.org/?probe=e46ed9f47e) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [978f54c17b](https://linux-hardware.org/?probe=978f54c17b) | Nov 08, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [6795a19ca5](https://linux-hardware.org/?probe=6795a19ca5) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [24ae8ff637](https://linux-hardware.org/?probe=24ae8ff637) | Nov 08, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5c1aced8cf](https://linux-hardware.org/?probe=5c1aced8cf) | Nov 08, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [6bc6e8bb07](https://linux-hardware.org/?probe=6bc6e8bb07) | Nov 08, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6e215a4ade](https://linux-hardware.org/?probe=6e215a4ade) | Nov 08, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [4077746212](https://linux-hardware.org/?probe=4077746212) | Nov 08, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [dbfe362cd8](https://linux-hardware.org/?probe=dbfe362cd8) | Nov 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c81bc71fdb](https://linux-hardware.org/?probe=c81bc71fdb) | Nov 08, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M7S... | Convertible | [d82b317402](https://linux-hardware.org/?probe=d82b317402) | Nov 07, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [48dbab4d36](https://linux-hardware.org/?probe=48dbab4d36) | Nov 07, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [2be7c3b6d6](https://linux-hardware.org/?probe=2be7c3b6d6) | Nov 07, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [7e3747e291](https://linux-hardware.org/?probe=7e3747e291) | Nov 07, 2023 |
| Dell          | 0TY565                      | Desktop     | [1597a5eaf7](https://linux-hardware.org/?probe=1597a5eaf7) | Nov 07, 2023 |
| Dell          | Latitude 5175               | Notebook    | [7b4721323a](https://linux-hardware.org/?probe=7b4721323a) | Nov 07, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [2e09b6a2b0](https://linux-hardware.org/?probe=2e09b6a2b0) | Nov 07, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [a675ce6c08](https://linux-hardware.org/?probe=a675ce6c08) | Nov 07, 2023 |
| HP            | 2AF3                        | Desktop     | [19333e743d](https://linux-hardware.org/?probe=19333e743d) | Nov 07, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [d698d770e1](https://linux-hardware.org/?probe=d698d770e1) | Nov 07, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [fecc1b7dff](https://linux-hardware.org/?probe=fecc1b7dff) | Nov 07, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [3ccd2441ac](https://linux-hardware.org/?probe=3ccd2441ac) | Nov 07, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [e2d2219122](https://linux-hardware.org/?probe=e2d2219122) | Nov 07, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [09b818e1d3](https://linux-hardware.org/?probe=09b818e1d3) | Nov 07, 2023 |
| MSI           | MS-6657                     | All in one  | [7d3b32e1cd](https://linux-hardware.org/?probe=7d3b32e1cd) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f51da852ca](https://linux-hardware.org/?probe=f51da852ca) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [35b7b043ff](https://linux-hardware.org/?probe=35b7b043ff) | Nov 07, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [c98cdea69b](https://linux-hardware.org/?probe=c98cdea69b) | Nov 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [744716992d](https://linux-hardware.org/?probe=744716992d) | Nov 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [c00bcace68](https://linux-hardware.org/?probe=c00bcace68) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6f9ee3fea0](https://linux-hardware.org/?probe=6f9ee3fea0) | Nov 06, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [26332591d7](https://linux-hardware.org/?probe=26332591d7) | Nov 06, 2023 |
| GMKtec        | NucBox K2                   | Desktop     | [a88d491579](https://linux-hardware.org/?probe=a88d491579) | Nov 06, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ad28c1e239](https://linux-hardware.org/?probe=ad28c1e239) | Nov 06, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [d95f04dd2c](https://linux-hardware.org/?probe=d95f04dd2c) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f48ca40214](https://linux-hardware.org/?probe=f48ca40214) | Nov 05, 2023 |
| HP            | ProBook 6470b               | Notebook    | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [5196f9303d](https://linux-hardware.org/?probe=5196f9303d) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7b281cb925](https://linux-hardware.org/?probe=7b281cb925) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [28e2c2aa38](https://linux-hardware.org/?probe=28e2c2aa38) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [7a8597dd50](https://linux-hardware.org/?probe=7a8597dd50) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | Notebook    | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a513bb8188](https://linux-hardware.org/?probe=a513bb8188) | Nov 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [4e3cd50b3f](https://linux-hardware.org/?probe=4e3cd50b3f) | Nov 04, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [dc13d6012b](https://linux-hardware.org/?probe=dc13d6012b) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| HP            | Presario C500 (GF849EA#A... | Notebook    | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [812ceefef6](https://linux-hardware.org/?probe=812ceefef6) | Nov 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [af20418f73](https://linux-hardware.org/?probe=af20418f73) | Nov 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [28f8f3e3cd](https://linux-hardware.org/?probe=28f8f3e3cd) | Nov 04, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [5117a849b3](https://linux-hardware.org/?probe=5117a849b3) | Nov 03, 2023 |
| Dell          | Precision 5550              | Notebook    | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [de50c92d6c](https://linux-hardware.org/?probe=de50c92d6c) | Nov 03, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [f69b9b159a](https://linux-hardware.org/?probe=f69b9b159a) | Nov 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [b526accbcd](https://linux-hardware.org/?probe=b526accbcd) | Nov 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | Desktop     | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Dell          | Vostro 5590                 | Notebook    | [aa355fcc89](https://linux-hardware.org/?probe=aa355fcc89) | Nov 02, 2023 |
| GreatWall     | W1011                       | Tablet      | [fe355d55c3](https://linux-hardware.org/?probe=fe355d55c3) | Nov 02, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [e082a50dde](https://linux-hardware.org/?probe=e082a50dde) | Nov 02, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d3d4d3dea3](https://linux-hardware.org/?probe=d3d4d3dea3) | Nov 01, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [1ca6496a6c](https://linux-hardware.org/?probe=1ca6496a6c) | Nov 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [801d83a570](https://linux-hardware.org/?probe=801d83a570) | Nov 01, 2023 |
| HP            | 0A58h                       | Desktop     | [9dd3c3fdfb](https://linux-hardware.org/?probe=9dd3c3fdfb) | Nov 01, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [226d669c79](https://linux-hardware.org/?probe=226d669c79) | Nov 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [037e92aebd](https://linux-hardware.org/?probe=037e92aebd) | Nov 01, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [6895dd827a](https://linux-hardware.org/?probe=6895dd827a) | Nov 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [5d58dd522f](https://linux-hardware.org/?probe=5d58dd522f) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [c7ce75613c](https://linux-hardware.org/?probe=c7ce75613c) | Nov 01, 2023 |
| Lenovo        | 3647 SDK0J40709 WIN 3259... | All in one  | [4f99b79f9e](https://linux-hardware.org/?probe=4f99b79f9e) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| Apple         | MacBook9,1                  | Notebook    | [44cec57d44](https://linux-hardware.org/?probe=44cec57d44) | Nov 01, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [d7b563a839](https://linux-hardware.org/?probe=d7b563a839) | Oct 31, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [962f4ccb9e](https://linux-hardware.org/?probe=962f4ccb9e) | Oct 31, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| HP            | G56                         | Notebook    | [db44e7df47](https://linux-hardware.org/?probe=db44e7df47) | Oct 31, 2023 |
| HP            | 0A58h                       | Desktop     | [f7c62b9410](https://linux-hardware.org/?probe=f7c62b9410) | Oct 31, 2023 |
| Lenovo        | ThinkPad T530 24296JG       | Notebook    | [b443eebcad](https://linux-hardware.org/?probe=b443eebcad) | Oct 31, 2023 |
| Alienware     | 14                          | Notebook    | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [72131fb5de](https://linux-hardware.org/?probe=72131fb5de) | Oct 31, 2023 |
| Dell          | 0R849J A01                  | Desktop     | [3891d2fd80](https://linux-hardware.org/?probe=3891d2fd80) | Oct 31, 2023 |
| HP            | Presario C500 (GF849EA#A... | Notebook    | [580f4bdb18](https://linux-hardware.org/?probe=580f4bdb18) | Oct 31, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [ef58eef71a](https://linux-hardware.org/?probe=ef58eef71a) | Oct 31, 2023 |
| Intel         | H311 DS3 V1.0               | Desktop     | [2eabffe817](https://linux-hardware.org/?probe=2eabffe817) | Oct 31, 2023 |
| Dell          | Latitude E5520              | Notebook    | [445903fc05](https://linux-hardware.org/?probe=445903fc05) | Oct 31, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [26479d99b9](https://linux-hardware.org/?probe=26479d99b9) | Oct 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [43772c58a4](https://linux-hardware.org/?probe=43772c58a4) | Oct 30, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0a5b6171b7](https://linux-hardware.org/?probe=0a5b6171b7) | Oct 30, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [8b1fe7cf44](https://linux-hardware.org/?probe=8b1fe7cf44) | Oct 30, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [4825358a5d](https://linux-hardware.org/?probe=4825358a5d) | Oct 30, 2023 |
| AWOW          | AK41                        | Notebook    | [bed4203da6](https://linux-hardware.org/?probe=bed4203da6) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [af050c4fa2](https://linux-hardware.org/?probe=af050c4fa2) | Oct 29, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9ca810aaa6](https://linux-hardware.org/?probe=9ca810aaa6) | Oct 29, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [1a14a8f0c4](https://linux-hardware.org/?probe=1a14a8f0c4) | Oct 29, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [a43802c314](https://linux-hardware.org/?probe=a43802c314) | Oct 29, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [7bdcd09429](https://linux-hardware.org/?probe=7bdcd09429) | Oct 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [57441db309](https://linux-hardware.org/?probe=57441db309) | Oct 29, 2023 |
| Panasonic     | CF-191HA23DE                | Notebook    | [3ccc424983](https://linux-hardware.org/?probe=3ccc424983) | Oct 29, 2023 |
| Dell          | Precision M6800             | Notebook    | [3645954ce0](https://linux-hardware.org/?probe=3645954ce0) | Oct 28, 2023 |
| Biostar       | G31D-M7                     | Desktop     | [192416033b](https://linux-hardware.org/?probe=192416033b) | Oct 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [967ed7a2b9](https://linux-hardware.org/?probe=967ed7a2b9) | Oct 28, 2023 |
| Dell          | Latitude E6500              | Notebook    | [41e90a6524](https://linux-hardware.org/?probe=41e90a6524) | Oct 28, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [7545369484](https://linux-hardware.org/?probe=7545369484) | Oct 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bee59e348e](https://linux-hardware.org/?probe=bee59e348e) | Oct 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [69a0449eee](https://linux-hardware.org/?probe=69a0449eee) | Oct 28, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [2ff3541961](https://linux-hardware.org/?probe=2ff3541961) | Oct 28, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [60372b59fe](https://linux-hardware.org/?probe=60372b59fe) | Oct 28, 2023 |
| HP            | 2AF3                        | Desktop     | [f7c7d92cea](https://linux-hardware.org/?probe=f7c7d92cea) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6a8554304e](https://linux-hardware.org/?probe=6a8554304e) | Oct 27, 2023 |
| Lenovo        | ThinkPad T450 20BUS00700    | Notebook    | [f74328fd58](https://linux-hardware.org/?probe=f74328fd58) | Oct 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [fe15ca03f2](https://linux-hardware.org/?probe=fe15ca03f2) | Oct 27, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [2c88e089bb](https://linux-hardware.org/?probe=2c88e089bb) | Oct 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JKC... | Notebook    | [c9ba633d37](https://linux-hardware.org/?probe=c9ba633d37) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | Notebook    | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [311f057665](https://linux-hardware.org/?probe=311f057665) | Oct 26, 2023 |
| HP            | EliteBook 630 13.3 inch ... | Notebook    | [8f57ab5108](https://linux-hardware.org/?probe=8f57ab5108) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ab3b2be8f5](https://linux-hardware.org/?probe=ab3b2be8f5) | Oct 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8f83740c8d](https://linux-hardware.org/?probe=8f83740c8d) | Oct 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [5b2aac75a9](https://linux-hardware.org/?probe=5b2aac75a9) | Oct 26, 2023 |
| AWOW          | AK41                        | Notebook    | [e40c573853](https://linux-hardware.org/?probe=e40c573853) | Oct 26, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [829d7d5108](https://linux-hardware.org/?probe=829d7d5108) | Oct 26, 2023 |
| Foxconn       | 2AA9h                       | Desktop     | [dade54701d](https://linux-hardware.org/?probe=dade54701d) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [8926585836](https://linux-hardware.org/?probe=8926585836) | Oct 26, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b75faeaf8a](https://linux-hardware.org/?probe=b75faeaf8a) | Oct 25, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [4d1e460056](https://linux-hardware.org/?probe=4d1e460056) | Oct 25, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [3a1de9e1d1](https://linux-hardware.org/?probe=3a1de9e1d1) | Oct 25, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [8a5e0bd9d6](https://linux-hardware.org/?probe=8a5e0bd9d6) | Oct 25, 2023 |
| Acer          | Nitro NP515-51              | Convertible | [ce16663fee](https://linux-hardware.org/?probe=ce16663fee) | Oct 25, 2023 |
| Dell          | Precision 7550              | Notebook    | [b6f0ce0285](https://linux-hardware.org/?probe=b6f0ce0285) | Oct 25, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f88a2686e9](https://linux-hardware.org/?probe=f88a2686e9) | Oct 25, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [62bbdaec23](https://linux-hardware.org/?probe=62bbdaec23) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [2b1387ee7c](https://linux-hardware.org/?probe=2b1387ee7c) | Oct 24, 2023 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [85f85dffbd](https://linux-hardware.org/?probe=85f85dffbd) | Oct 24, 2023 |
| Acer          | Aspire XC-1760              | Desktop     | [8a5c420847](https://linux-hardware.org/?probe=8a5c420847) | Oct 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [268b32d9bf](https://linux-hardware.org/?probe=268b32d9bf) | Oct 24, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [5ad24eb928](https://linux-hardware.org/?probe=5ad24eb928) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2d6bcd74d8](https://linux-hardware.org/?probe=2d6bcd74d8) | Oct 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [85fac54d6a](https://linux-hardware.org/?probe=85fac54d6a) | Oct 24, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [95b5ac0a0e](https://linux-hardware.org/?probe=95b5ac0a0e) | Oct 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [87102526a5](https://linux-hardware.org/?probe=87102526a5) | Oct 24, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [47b5a808aa](https://linux-hardware.org/?probe=47b5a808aa) | Oct 24, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [fc82aed364](https://linux-hardware.org/?probe=fc82aed364) | Oct 23, 2023 |
| Eii           | WSA116                      | Notebook    | [85da70314e](https://linux-hardware.org/?probe=85da70314e) | Oct 23, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [dc0db667dc](https://linux-hardware.org/?probe=dc0db667dc) | Oct 23, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [cd4e6f4d07](https://linux-hardware.org/?probe=cd4e6f4d07) | Oct 23, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d8c12e782e](https://linux-hardware.org/?probe=d8c12e782e) | Oct 23, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [9d7ecc567c](https://linux-hardware.org/?probe=9d7ecc567c) | Oct 23, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Gigabyte      | B85N PHOENIX-CF             | Desktop     | [a64a820d24](https://linux-hardware.org/?probe=a64a820d24) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [58a9a7a091](https://linux-hardware.org/?probe=58a9a7a091) | Oct 22, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [9b380c5e6a](https://linux-hardware.org/?probe=9b380c5e6a) | Oct 22, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [084dd63188](https://linux-hardware.org/?probe=084dd63188) | Oct 21, 2023 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [98a242f151](https://linux-hardware.org/?probe=98a242f151) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [b52eba9a1b](https://linux-hardware.org/?probe=b52eba9a1b) | Oct 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [e503ffe188](https://linux-hardware.org/?probe=e503ffe188) | Oct 21, 2023 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [b80592c227](https://linux-hardware.org/?probe=b80592c227) | Oct 21, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [f350ad7b18](https://linux-hardware.org/?probe=f350ad7b18) | Oct 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5e09b89469](https://linux-hardware.org/?probe=5e09b89469) | Oct 20, 2023 |
| MSI           | G41TM-P31                   | Desktop     | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [2adde1171a](https://linux-hardware.org/?probe=2adde1171a) | Oct 20, 2023 |
| Unknown       | Unknown                     | Soc         | [29ae977d06](https://linux-hardware.org/?probe=29ae977d06) | Oct 20, 2023 |
| HP            | EliteBook 630 13.3 inch ... | Notebook    | [e1ed7c2ee4](https://linux-hardware.org/?probe=e1ed7c2ee4) | Oct 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [fdbd97d08c](https://linux-hardware.org/?probe=fdbd97d08c) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| Pegatron      | Benicia                     | Desktop     | [c8ec5c8db0](https://linux-hardware.org/?probe=c8ec5c8db0) | Oct 19, 2023 |
| Novatech      | W9x0LU                      | Notebook    | [b6e3d3dfc9](https://linux-hardware.org/?probe=b6e3d3dfc9) | Oct 19, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9d63ed7f5f](https://linux-hardware.org/?probe=9d63ed7f5f) | Oct 19, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [9e4ac23c4b](https://linux-hardware.org/?probe=9e4ac23c4b) | Oct 19, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [6fc8b26d2c](https://linux-hardware.org/?probe=6fc8b26d2c) | Oct 19, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [baacbfa91a](https://linux-hardware.org/?probe=baacbfa91a) | Oct 19, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [827a7bf56c](https://linux-hardware.org/?probe=827a7bf56c) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [dae01ed766](https://linux-hardware.org/?probe=dae01ed766) | Oct 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [bc4cc061a2](https://linux-hardware.org/?probe=bc4cc061a2) | Oct 18, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [534b565ca1](https://linux-hardware.org/?probe=534b565ca1) | Oct 18, 2023 |
| HP            | 3646h                       | Desktop     | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| HP            | 2B44                        | Desktop     | [9ec07b67b2](https://linux-hardware.org/?probe=9ec07b67b2) | Oct 18, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [3d5d8ee9e6](https://linux-hardware.org/?probe=3d5d8ee9e6) | Oct 17, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [d1eeca057f](https://linux-hardware.org/?probe=d1eeca057f) | Oct 17, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [86d888a421](https://linux-hardware.org/?probe=86d888a421) | Oct 17, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [98b06c3d78](https://linux-hardware.org/?probe=98b06c3d78) | Oct 17, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [eac40d1a3b](https://linux-hardware.org/?probe=eac40d1a3b) | Oct 17, 2023 |
| Alienware     | m15                         | Notebook    | [34919bdeca](https://linux-hardware.org/?probe=34919bdeca) | Oct 17, 2023 |
| Dell          | Latitude 5490               | Notebook    | [d85f87c8b0](https://linux-hardware.org/?probe=d85f87c8b0) | Oct 17, 2023 |
| Dell          | G15 5515                    | Notebook    | [080e34562c](https://linux-hardware.org/?probe=080e34562c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| Dell          | Latitude E6540              | Notebook    | [27875d6fe5](https://linux-hardware.org/?probe=27875d6fe5) | Oct 16, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [0dcdd0a6a6](https://linux-hardware.org/?probe=0dcdd0a6a6) | Oct 16, 2023 |
| CompuLab      | fitlet2                     | Mini pc     | [9d9a814ffb](https://linux-hardware.org/?probe=9d9a814ffb) | Oct 16, 2023 |
| Lenovo        | ThinkPad E565 20EY000XUK    | Notebook    | [b7cf6113c4](https://linux-hardware.org/?probe=b7cf6113c4) | Oct 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [acd4052588](https://linux-hardware.org/?probe=acd4052588) | Oct 16, 2023 |
| Dell          | Precision M6700             | Notebook    | [2fb2e2e9a5](https://linux-hardware.org/?probe=2fb2e2e9a5) | Oct 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [d8ba22dd7f](https://linux-hardware.org/?probe=d8ba22dd7f) | Oct 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [386d015b42](https://linux-hardware.org/?probe=386d015b42) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| Lenovo        | YB1-X91F                    | Convertible | [430c262f7c](https://linux-hardware.org/?probe=430c262f7c) | Oct 15, 2023 |
| HP            | ProLiant ML350 Gen9         | Desktop     | [468a686a40](https://linux-hardware.org/?probe=468a686a40) | Oct 15, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [3d9bd14288](https://linux-hardware.org/?probe=3d9bd14288) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [22b5b65e16](https://linux-hardware.org/?probe=22b5b65e16) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| ASRock        | B85M                        | Desktop     | [1712e16d1c](https://linux-hardware.org/?probe=1712e16d1c) | Oct 15, 2023 |
| Google        | Careena                     | Notebook    | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | Notebook    | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [32422b446a](https://linux-hardware.org/?probe=32422b446a) | Oct 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1145      | 12.29%  |
| Ubuntu 18.04                 | 603       | 6.47%   |
| Ubuntu 22.04                 | 600       | 6.44%   |
| Zorin 16                     | 243       | 2.61%   |
| Arch Rolling                 | 206       | 2.21%   |
| Pop!_OS 22.04                | 185       | 1.99%   |
| Debian 11                    | 179       | 1.92%   |
| OpenMandriva 4.3             | 146       | 1.57%   |
| ArcoLinux Rolling            | 146       | 1.57%   |
| OpenMandriva 4.2             | 133       | 1.43%   |
| Manjaro                      | 132       | 1.42%   |
| Linux Mint 20.3              | 126       | 1.35%   |
| Linux Mint 21.1              | 119       | 1.28%   |
| Linux Mint 20.2              | 115       | 1.23%   |
| Fedora 38                    | 115       | 1.23%   |
| Linux Mint 19.3              | 112       | 1.2%    |
| KDE neon 20.04               | 112       | 1.2%    |
| Pop!_OS 20.04                | 108       | 1.16%   |
| Ubuntu 19.04                 | 105       | 1.13%   |
| Ubuntu 20.10                 | 101       | 1.08%   |
| Linux Mint 21.2              | 101       | 1.08%   |
| Pop!_OS 21.04                | 100       | 1.07%   |
| Arch                         | 97        | 1.04%   |
| Zorin 15                     | 94        | 1.01%   |
| Ubuntu 21.10                 | 94        | 1.01%   |
| Debian 12                    | 91        | 0.98%   |
| Ubuntu 19.10                 | 89        | 0.96%   |
| Pop!_OS 20.10                | 86        | 0.92%   |
| Linux Mint 20.1              | 86        | 0.92%   |
| OpenMandriva 23.01           | 82        | 0.88%   |
| Ubuntu 21.04                 | 81        | 0.87%   |
| OpenMandriva 23.03           | 79        | 0.85%   |
| Xubuntu 20.04                | 77        | 0.83%   |
| Fedora 36                    | 72        | 0.77%   |
| Fedora 37                    | 69        | 0.74%   |
| Ubuntu 23.04                 | 67        | 0.72%   |
| Linux Mint 20                | 67        | 0.72%   |
| openSUSE Tumbleweed-XXXXXXXX | 66        | 0.71%   |
| OpenMandriva 23.08           | 65        | 0.7%    |
| Fedora 39                    | 62        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2931      | 33.25%  |
| Linux Mint    | 812       | 9.21%   |
| OpenMandriva  | 556       | 6.31%   |
| Fedora        | 554       | 6.28%   |
| Pop!_OS       | 511       | 5.8%    |
| Debian        | 367       | 4.16%   |
| Zorin         | 362       | 4.11%   |
| Arch          | 301       | 3.41%   |
| Manjaro       | 263       | 2.98%   |
| Kubuntu       | 213       | 2.42%   |
| KDE neon      | 172       | 1.95%   |
| Xubuntu       | 169       | 1.92%   |
| ArcoLinux     | 150       | 1.7%    |
| SteamOS       | 130       | 1.47%   |
| openSUSE      | 94        | 1.07%   |
| Gentoo        | 86        | 0.98%   |
| ROSA          | 79        | 0.9%    |
| Elementary    | 79        | 0.9%    |
| Ubuntu MATE   | 69        | 0.78%   |
| Lubuntu       | 64        | 0.73%   |
| Kali          | 58        | 0.66%   |
| Endless       | 57        | 0.65%   |
| Ubuntu Unity  | 53        | 0.6%    |
| Clear Linux   | 46        | 0.52%   |
| BlackPanther  | 46        | 0.52%   |
| EndeavourOS   | 41        | 0.47%   |
| Nobara        | 40        | 0.45%   |
| LMDE          | 38        | 0.43%   |
| MX            | 36        | 0.41%   |
| Garuda Linux  | 29        | 0.33%   |
| CentOS        | 28        | 0.32%   |
| Raspbian      | 27        | 0.31%   |
| Ubuntu Budgie | 25        | 0.28%   |
| Parrot        | 21        | 0.24%   |
| RHEL          | 20        | 0.23%   |
| Peppermint    | 19        | 0.22%   |
| NixOS         | 18        | 0.2%    |
| Slackware     | 15        | 0.17%   |
| ChimeraOS     | 10        | 0.11%   |
| Alpine        | 9         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 1.46%   |
| 5.16.7-desktop-1omv4003  | 137       | 1.32%   |
| 5.10.14-desktop-1omv4002 | 130       | 1.25%   |
| 5.15.0-56-generic        | 86        | 0.83%   |
| 5.4.0-48-generic         | 81        | 0.78%   |
| 6.2.6-desktop-1omv2390   | 78        | 0.75%   |
| 5.4.0-52-generic         | 76        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 74        | 0.71%   |
| 5.4.0-29-generic         | 73        | 0.7%    |
| 5.4.0-26-generic         | 70        | 0.67%   |
| 5.3.0-28-generic         | 65        | 0.63%   |
| 5.15.0-58-generic        | 65        | 0.63%   |
| 5.15.0-52-generic        | 65        | 0.63%   |
| 5.15.0-46-generic        | 64        | 0.62%   |
| 5.3.0-40-generic         | 60        | 0.58%   |
| 6.4.11-desktop-1omv2390  | 54        | 0.52%   |
| 5.4.0-40-generic         | 53        | 0.51%   |
| 5.4.0-58-generic         | 52        | 0.5%    |
| 5.4.0-37-generic         | 51        | 0.49%   |
| 5.11.0-27-generic        | 51        | 0.49%   |
| 6.2.0-26-generic         | 49        | 0.47%   |
| 5.15.0-91-generic        | 47        | 0.45%   |
| 6.5.0-14-generic         | 46        | 0.44%   |
| 5.4.0-65-generic         | 45        | 0.43%   |
| 5.4.0-33-generic         | 45        | 0.43%   |
| 5.11.0-38-generic        | 45        | 0.43%   |
| 5.0.0-32-generic         | 45        | 0.43%   |
| 5.4.0-91-generic         | 43        | 0.41%   |
| 5.19.0-35-generic        | 43        | 0.41%   |
| 5.13.0-7614-generic      | 43        | 0.41%   |
| 5.11.0-25-generic        | 43        | 0.41%   |
| 5.13.0-valve36-1-neptune | 42        | 0.4%    |
| 5.4.0-7634-generic       | 41        | 0.39%   |
| 5.4.0-74-generic         | 41        | 0.39%   |
| 5.4.0-54-generic         | 41        | 0.39%   |
| 5.3.0-46-generic         | 41        | 0.39%   |
| 5.4.0-66-generic         | 40        | 0.38%   |
| 5.8.0-7630-generic       | 39        | 0.38%   |
| 5.8.0-43-generic         | 39        | 0.38%   |
| 5.11.0-7620-generic      | 39        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1524      | 15.72%  |
| 5.15.0  | 915       | 9.44%   |
| 5.13.0  | 479       | 4.94%   |
| 5.11.0  | 457       | 4.71%   |
| 5.8.0   | 451       | 4.65%   |
| 4.15.0  | 422       | 4.35%   |
| 5.3.0   | 374       | 3.86%   |
| 6.2.0   | 301       | 3.1%    |
| 5.19.0  | 298       | 3.07%   |
| 5.0.0   | 244       | 2.52%   |
| 5.10.0  | 209       | 2.16%   |
| 4.18.0  | 183       | 1.89%   |
| 5.16.7  | 138       | 1.42%   |
| 5.10.14 | 130       | 1.34%   |
| 6.1.0   | 127       | 1.31%   |
| 6.2.6   | 121       | 1.25%   |
| 6.5.0   | 120       | 1.24%   |
| 6.1.1   | 79        | 0.81%   |
| 6.4.11  | 63        | 0.65%   |
| 4.19.0  | 58        | 0.6%    |
| 6.5.6   | 43        | 0.44%   |
| 5.14.0  | 38        | 0.39%   |
| 5.17.5  | 37        | 0.38%   |
| 4.18.16 | 34        | 0.35%   |
| 6.0.0   | 33        | 0.34%   |
| 6.5.5   | 29        | 0.3%    |
| 6.0.12  | 27        | 0.28%   |
| 6.6.2   | 26        | 0.27%   |
| 6.0.6   | 26        | 0.27%   |
| 4.9.60  | 26        | 0.27%   |
| 5.9.16  | 25        | 0.26%   |
| 6.6.6   | 22        | 0.23%   |
| 5.18.0  | 22        | 0.23%   |
| 5.16.13 | 22        | 0.23%   |
| 6.6.8   | 21        | 0.22%   |
| 6.2.9   | 21        | 0.22%   |
| 4.4.0   | 21        | 0.22%   |
| 6.4.6   | 20        | 0.21%   |
| 6.4.12  | 20        | 0.21%   |
| 6.6.7   | 19        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1616      | 16.91%  |
| 5.15    | 1114      | 11.66%  |
| 5.13    | 565       | 5.91%   |
| 5.8     | 538       | 5.63%   |
| 6.2     | 531       | 5.56%   |
| 5.11    | 516       | 5.4%    |
| 5.10    | 477       | 4.99%   |
| 5.3     | 425       | 4.45%   |
| 4.15    | 424       | 4.44%   |
| 5.19    | 390       | 4.08%   |
| 6.1     | 386       | 4.04%   |
| 6.5     | 256       | 2.68%   |
| 5.0     | 254       | 2.66%   |
| 5.16    | 250       | 2.62%   |
| 4.18    | 220       | 2.3%    |
| 6.4     | 194       | 2.03%   |
| 6.0     | 158       | 1.65%   |
| 6.6     | 147       | 1.54%   |
| 5.14    | 112       | 1.17%   |
| 5.17    | 111       | 1.16%   |
| 6.3     | 106       | 1.11%   |
| 5.9     | 95        | 0.99%   |
| 5.18    | 93        | 0.97%   |
| 4.19    | 91        | 0.95%   |
| 5.12    | 88        | 0.92%   |
| 5.6     | 79        | 0.83%   |
| 4.9     | 74        | 0.77%   |
| 5.7     | 68        | 0.71%   |
| 5.5     | 42        | 0.44%   |
| 4.4     | 25        | 0.26%   |
| 5.2     | 23        | 0.24%   |
| 5.1     | 16        | 0.17%   |
| 6.7     | 11        | 0.12%   |
| 4.14    | 10        | 0.1%    |
| 3.10    | 10        | 0.1%    |
| 4.1     | 9         | 0.09%   |
| 4.20    | 5         | 0.05%   |
| 4.13    | 5         | 0.05%   |
| 3.13    | 4         | 0.04%   |
| 4.8     | 3         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8154      | 96.5%   |
| i686    | 184       | 2.18%   |
| aarch64 | 80        | 0.95%   |
| armv7l  | 30        | 0.36%   |
| riscv64 | 1         | 0.01%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 3984      | 44.97%  |
| KDE5             | 1553      | 17.53%  |
| Unknown          | 1009      | 11.39%  |
| X-Cinnamon       | 668       | 7.54%   |
| XFCE             | 595       | 6.72%   |
| MATE             | 221       | 2.49%   |
| KDE              | 180       | 2.03%   |
| Cinnamon         | 102       | 1.15%   |
| Pantheon         | 75        | 0.85%   |
| LXQt             | 74        | 0.84%   |
| LXDE             | 58        | 0.65%   |
| Unity            | 56        | 0.63%   |
| Budgie           | 38        | 0.43%   |
| KDE4             | 36        | 0.41%   |
| i3               | 36        | 0.41%   |
| GNOME Flashback  | 30        | 0.34%   |
| Hyprland         | 18        | 0.2%    |
| sway             | 17        | 0.19%   |
| Deepin           | 13        | 0.15%   |
| Openbox          | 12        | 0.14%   |
| GNOME Classic    | 11        | 0.12%   |
| awesome          | 11        | 0.12%   |
| qtile            | 8         | 0.09%   |
| lightdm-xsession | 7         | 0.08%   |
| xmonad           | 6         | 0.07%   |
| bspwm            | 6         | 0.07%   |
| trinity          | 4         | 0.05%   |
| Enlightenment    | 4         | 0.05%   |
| chadwm           | 4         | 0.05%   |
| mwm              | 3         | 0.03%   |
| DWM              | 3         | 0.03%   |
| Unicorn:XFCE     | 2         | 0.02%   |
| icewm            | 2         | 0.02%   |
| i3-with-shmlog   | 2         | 0.02%   |
| Cutefish         | 2         | 0.02%   |
| BunsenLabs       | 2         | 0.02%   |
| xubuntu          | 1         | 0.01%   |
| WindowMaker      | 1         | 0.01%   |
| Phosh:GNOME      | 1         | 0.01%   |
| LeftWM           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6433      | 73.8%   |
| Wayland | 1559      | 17.88%  |
| Unknown | 492       | 5.64%   |
| Tty     | 232       | 2.66%   |
| Web     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4610      | 52.29%  |
| SDDM    | 1267      | 14.37%  |
| GDM3    | 1037      | 11.76%  |
| GDM     | 812       | 9.21%   |
| LightDM | 811       | 9.2%    |
| TDM     | 198       | 2.25%   |
| KDM     | 35        | 0.4%    |
| XDM     | 16        | 0.18%   |
| LXDM    | 10        | 0.11%   |
| SLiM    | 7         | 0.08%   |
| Ly      | 6         | 0.07%   |
| GREETD  | 3         | 0.03%   |
| XINIT   | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| LY-DM   | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| en_GB          | 6319      | 72.88%  |
| en_US          | 1120      | 12.92%  |
| Unknown        | 833       | 9.61%   |
| C              | 149       | 1.72%   |
| pl_PL          | 68        | 0.78%   |
| ru_RU          | 16        | 0.18%   |
| POSIX          | 16        | 0.18%   |
| de_DE          | 14        | 0.16%   |
| en_IE          | 12        | 0.14%   |
| en_CA          | 11        | 0.13%   |
| it_IT          | 10        | 0.12%   |
| fr_FR          | 10        | 0.12%   |
| en_AU          | 8         | 0.09%   |
| en_IN          | 7         | 0.08%   |
| ro_RO          | 6         | 0.07%   |
| hu_HU          | 6         | 0.07%   |
| es_ES          | 6         | 0.07%   |
| cs_CZ          | 6         | 0.07%   |
| C.UTF8         | 6         | 0.07%   |
| zh_CN          | 4         | 0.05%   |
| pt_PT          | 4         | 0.05%   |
| lt_LT          | 4         | 0.05%   |
| uk_UA          | 3         | 0.03%   |
| sk_SK          | 3         | 0.03%   |
| pt_BR          | 3         | 0.03%   |
| nl_NL          | 2         | 0.02%   |
| en_ZA          | 2         | 0.02%   |
| en_US.utf-8    | 2         | 0.02%   |
| en_GB.iso88591 | 2         | 0.02%   |
| da_DK          | 2         | 0.02%   |
| bg_BG          | 2         | 0.02%   |
| wbp_AU         | 1         | 0.01%   |
| us             | 1         | 0.01%   |
| tr_TR          | 1         | 0.01%   |
| ru_UA          | 1         | 0.01%   |
| nl_BE          | 1         | 0.01%   |
| fi_FI          | 1         | 0.01%   |
| et_EE          | 1         | 0.01%   |
| en_SG          | 1         | 0.01%   |
| en_NZ          | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 4422      | 51.18%  |
| EFI  | 4218      | 48.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6464      | 74.11%  |
| Btrfs    | 922       | 10.57%  |
| Overlay  | 578       | 6.63%   |
| Tmpfs    | 277       | 3.18%   |
| Unknown  | 234       | 2.68%   |
| Xfs      | 123       | 1.41%   |
| Zfs      | 70        | 0.8%    |
| Ext2     | 22        | 0.25%   |
| Ext3     | 13        | 0.15%   |
| F2fs     | 11        | 0.13%   |
| Aufs     | 3         | 0.03%   |
| XXXX     | 1         | 0.01%   |
| Rootfs   | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Lvm      | 1         | 0.01%   |
| ExX4     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 4698      | 54.09%  |
| GPT     | 3219      | 37.06%  |
| MBR     | 768       | 8.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7353      | 85.1%   |
| Yes       | 1287      | 14.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6304      | 73.29%  |
| Yes       | 2298      | 26.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1296      | 15.35%  |
| ASUSTek Computer        | 1227      | 14.53%  |
| Lenovo                  | 1089      | 12.9%   |
| Hewlett-Packard         | 1048      | 12.41%  |
| Gigabyte Technology     | 599       | 7.1%    |
| MSI                     | 467       | 5.53%   |
| Acer                    | 398       | 4.71%   |
| Apple                   | 258       | 3.06%   |
| ASRock                  | 242       | 2.87%   |
| Toshiba                 | 184       | 2.18%   |
| Intel                   | 145       | 1.72%   |
| Valve                   | 120       | 1.42%   |
| Samsung Electronics     | 95        | 1.13%   |
| Raspberry Pi Foundation | 85        | 1.01%   |
| Unknown                 | 72        | 0.85%   |
| Sony                    | 69        | 0.82%   |
| Microsoft               | 53        | 0.63%   |
| HUAWEI                  | 52        | 0.62%   |
| Google                  | 52        | 0.62%   |
| Fujitsu                 | 51        | 0.6%    |
| PC Specialist           | 48        | 0.57%   |
| Packard Bell            | 38        | 0.45%   |
| AZW                     | 38        | 0.45%   |
| Foxconn                 | 36        | 0.43%   |
| Notebook                | 34        | 0.4%    |
| Alienware               | 33        | 0.39%   |
| Pegatron                | 25        | 0.3%    |
| Razer                   | 24        | 0.28%   |
| Medion                  | 23        | 0.27%   |
| Fujitsu Siemens         | 23        | 0.27%   |
| Biostar                 | 22        | 0.26%   |
| GEO                     | 21        | 0.25%   |
| Star Labs               | 20        | 0.24%   |
| Linx                    | 18        | 0.21%   |
| Entroware               | 17        | 0.2%    |
| AMI                     | 16        | 0.19%   |
| Supermicro              | 14        | 0.17%   |
| Dixonsxp                | 14        | 0.17%   |
| TUXEDO                  | 13        | 0.15%   |
| LG Electronics          | 13        | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Valve Jupiter                      | 117       | 1.39%   |
| Unknown                            | 96        | 1.14%   |
| ASUS All Series                    | 86        | 1.02%   |
| Dell OptiPlex 7010                 | 38        | 0.45%   |
| MSI MS-7C02                        | 30        | 0.36%   |
| HP Pavilion g6                     | 27        | 0.32%   |
| RPi Raspberry Pi                   | 24        | 0.28%   |
| ASUS M5A78L-M/USB3                 | 23        | 0.27%   |
| MSI MS-7C37                        | 22        | 0.26%   |
| HP Notebook                        | 22        | 0.26%   |
| ASUS TUF Gaming X570-PLUS          | 22        | 0.26%   |
| Dell OptiPlex 780                  | 21        | 0.25%   |
| Dell OptiPlex 755                  | 21        | 0.25%   |
| HP Pavilion 15                     | 20        | 0.24%   |
| ASUS ROG STRIX B450-F GAMING       | 20        | 0.24%   |
| HP Pavilion Notebook               | 19        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 18        | 0.21%   |
| Dell OptiPlex 790                  | 18        | 0.21%   |
| ASUS PRIME A320M-K                 | 18        | 0.21%   |
| Dell XPS 15 9570                   | 17        | 0.2%    |
| Gigabyte 970A-DS3P                 | 16        | 0.19%   |
| Dell XPS 15 9560                   | 16        | 0.19%   |
| Dell XPS 15 7590                   | 16        | 0.19%   |
| MSI MS-7C91                        | 15        | 0.18%   |
| Microsoft Surface Pro 4            | 15        | 0.18%   |
| Gigabyte X570 AORUS ELITE          | 15        | 0.18%   |
| Dell Inspiron 1545                 | 15        | 0.18%   |
| ASUS ROG STRIX B550-F GAMING       | 15        | 0.18%   |
| Dell XPS 13 9380                   | 14        | 0.17%   |
| Dell XPS 13 9370                   | 14        | 0.17%   |
| Dell XPS 13 9360                   | 14        | 0.17%   |
| MSI MS-7B79                        | 13        | 0.15%   |
| Dell OptiPlex 3020                 | 13        | 0.15%   |
| Dell Latitude E6400                | 13        | 0.15%   |
| HP Pavilion dv6                    | 12        | 0.14%   |
| Gigabyte GA-78LMT-USB3             | 12        | 0.14%   |
| Gigabyte B450M DS3H                | 12        | 0.14%   |
| Gigabyte A320M-S2H                 | 12        | 0.14%   |
| Dell Latitude E6410                | 12        | 0.14%   |
| ASUS PRIME B450-PLUS               | 12        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 519       | 6.15%   |
| Dell Latitude          | 295       | 3.49%   |
| Acer Aspire            | 283       | 3.35%   |
| Dell Inspiron          | 268       | 3.17%   |
| Dell OptiPlex          | 231       | 2.74%   |
| Dell XPS               | 222       | 2.63%   |
| ASUS ROG               | 199       | 2.36%   |
| HP Pavilion            | 171       | 2.03%   |
| Toshiba Satellite      | 159       | 1.88%   |
| Lenovo IdeaPad         | 157       | 1.86%   |
| ASUS PRIME             | 151       | 1.79%   |
| Dell Precision         | 124       | 1.47%   |
| HP EliteBook           | 123       | 1.46%   |
| Valve Jupiter          | 117       | 1.39%   |
| HP Compaq              | 105       | 1.24%   |
| Unknown                | 96        | 1.14%   |
| ASUS All               | 86        | 1.02%   |
| RPi Raspberry          | 85        | 1.01%   |
| Lenovo ThinkCentre     | 84        | 1%      |
| ASUS VivoBook          | 80        | 0.95%   |
| HP Laptop              | 79        | 0.94%   |
| HP ProBook             | 76        | 0.9%    |
| HP ENVY                | 68        | 0.81%   |
| ASUS TUF               | 67        | 0.79%   |
| Lenovo Yoga            | 61        | 0.72%   |
| Microsoft Surface      | 53        | 0.63%   |
| Dell Vostro            | 53        | 0.63%   |
| Gigabyte X570          | 43        | 0.51%   |
| Lenovo Legion          | 37        | 0.44%   |
| HP ProLiant            | 37        | 0.44%   |
| HP EliteDesk           | 36        | 0.43%   |
| ASUS Zenbook           | 35        | 0.41%   |
| ASUS M5A78L-M          | 33        | 0.39%   |
| Acer Swift             | 32        | 0.38%   |
| MSI MS-7C02            | 30        | 0.36%   |
| HP Stream              | 30        | 0.36%   |
| HP Spectre             | 27        | 0.32%   |
| Gigabyte GA-78LMT-USB3 | 27        | 0.32%   |
| Razer Blade            | 24        | 0.28%   |
| HP ZBook               | 23        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 786       | 9.31%   |
| 2019    | 701       | 8.3%    |
| 2020    | 689       | 8.16%   |
| 2012    | 638       | 7.56%   |
| 2013    | 578       | 6.85%   |
| 2017    | 563       | 6.67%   |
| 2014    | 538       | 6.37%   |
| 2021    | 536       | 6.35%   |
| 2011    | 524       | 6.21%   |
| 2015    | 425       | 5.03%   |
| 2016    | 417       | 4.94%   |
| 2010    | 415       | 4.92%   |
| 2022    | 406       | 4.81%   |
| 2008    | 322       | 3.81%   |
| 2009    | 321       | 3.8%    |
| 2007    | 215       | 2.55%   |
| 2023    | 149       | 1.76%   |
| Unknown | 91        | 1.08%   |
| 2006    | 89        | 1.05%   |
| 2005    | 27        | 0.32%   |
| 2004    | 6         | 0.07%   |
| 2003    | 3         | 0.04%   |
| 2002    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4313      | 51.09%  |
| Desktop        | 3309      | 39.2%   |
| Convertible    | 199       | 2.36%   |
| Mini pc        | 187       | 2.22%   |
| All in one     | 149       | 1.76%   |
| Tablet         | 112       | 1.33%   |
| System on chip | 100       | 1.18%   |
| Server         | 67        | 0.79%   |
| Phone          | 4         | 0.05%   |
| Other          | 1         | 0.01%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7824      | 91.94%  |
| Enabled  | 686       | 8.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8368      | 99.11%  |
| Yes  | 75        | 0.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1924      | 22.34%  |
| 16.01-24.0      | 1833      | 21.29%  |
| 8.01-16.0       | 1490      | 17.3%   |
| 3.01-4.0        | 1395      | 16.2%   |
| 32.01-64.0      | 978       | 11.36%  |
| 1.01-2.0        | 343       | 3.98%   |
| 64.01-256.0     | 279       | 3.24%   |
| 24.01-32.0      | 147       | 1.71%   |
| 2.01-3.0        | 138       | 1.6%    |
| 0.51-1.0        | 65        | 0.75%   |
| More than 256.0 | 12        | 0.14%   |
| 0.01-0.5        | 7         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 3300      | 34.72%  |
| 2.01-3.0    | 2335      | 24.57%  |
| 4.01-8.0    | 1413      | 14.87%  |
| 3.01-4.0    | 1249      | 13.14%  |
| 0.51-1.0    | 559       | 5.88%   |
| 8.01-16.0   | 401       | 4.22%   |
| 0.01-0.5    | 128       | 1.35%   |
| 16.01-24.0  | 63        | 0.66%   |
| 24.01-32.0  | 26        | 0.27%   |
| 32.01-64.0  | 19        | 0.2%    |
| 64.01-256.0 | 7         | 0.07%   |
| Unknown     | 4         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4941      | 56.38%  |
| 2       | 2188      | 24.97%  |
| 3       | 718       | 8.19%   |
| 4       | 392       | 4.47%   |
| 5       | 217       | 2.48%   |
| 6       | 108       | 1.23%   |
| 0       | 80        | 0.91%   |
| 7       | 44        | 0.5%    |
| 8       | 21        | 0.24%   |
| 9       | 15        | 0.17%   |
| 11      | 9         | 0.1%    |
| 10      | 8         | 0.09%   |
| Unknown | 8         | 0.09%   |
| 12      | 5         | 0.06%   |
| 13      | 3         | 0.03%   |
| 29      | 1         | 0.01%   |
| 25      | 1         | 0.01%   |
| 23      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5269      | 61.76%  |
| Yes       | 3262      | 38.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7025      | 83.01%  |
| No        | 1438      | 16.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6526      | 76.6%   |
| No        | 1994      | 23.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5120      | 59.83%  |
| No        | 3437      | 40.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UK      | 8442      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| London              | 539       | 5.74%   |
| Manchester          | 212       | 2.26%   |
| Birmingham          | 158       | 1.68%   |
| Bristol             | 145       | 1.55%   |
| Glasgow             | 140       | 1.49%   |
| Edinburgh           | 128       | 1.36%   |
| Leeds               | 114       | 1.21%   |
| Sheffield           | 113       | 1.2%    |
| Nottingham          | 112       | 1.19%   |
| Liverpool           | 110       | 1.17%   |
| Reading             | 89        | 0.95%   |
| Islington           | 86        | 0.92%   |
| Cambridge           | 74        | 0.79%   |
| Norwich             | 66        | 0.7%    |
| Southampton         | 65        | 0.69%   |
| Croydon             | 62        | 0.66%   |
| Leicester           | 61        | 0.65%   |
| Cardiff             | 61        | 0.65%   |
| Milton Keynes       | 60        | 0.64%   |
| Coventry            | 58        | 0.62%   |
| Derby               | 57        | 0.61%   |
| Bradford            | 56        | 0.6%    |
| York                | 51        | 0.54%   |
| Hackney             | 51        | 0.54%   |
| Newcastle upon Tyne | 49        | 0.52%   |
| Oxford              | 48        | 0.51%   |
| Swindon             | 45        | 0.48%   |
| Brighton            | 45        | 0.48%   |
| Aberdeen            | 43        | 0.46%   |
| Gloucester          | 42        | 0.45%   |
| Bolton              | 41        | 0.44%   |
| Plymouth            | 40        | 0.43%   |
| Wolverhampton       | 39        | 0.42%   |
| Wigan               | 38        | 0.4%    |
| Sunderland          | 36        | 0.38%   |
| Walsall             | 35        | 0.37%   |
| Belfast             | 34        | 0.36%   |
| Stockport           | 33        | 0.35%   |
| Southwark           | 33        | 0.35%   |
| Peterborough        | 33        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1961      | 3117   | 15.27%  |
| Seagate                     | 1815      | 3081   | 14.13%  |
| WDC                         | 1680      | 2802   | 13.08%  |
| Toshiba                     | 829       | 1152   | 6.45%   |
| SanDisk                     | 790       | 1090   | 6.15%   |
| Unknown                     | 712       | 989    | 5.54%   |
| Crucial                     | 701       | 1033   | 5.46%   |
| Kingston                    | 555       | 747    | 4.32%   |
| Hitachi                     | 428       | 593    | 3.33%   |
| SK hynix                    | 297       | 351    | 2.31%   |
| Intel                       | 277       | 383    | 2.16%   |
| HGST                        | 185       | 270    | 1.44%   |
| Phison                      | 168       | 223    | 1.31%   |
| Micron Technology           | 162       | 190    | 1.26%   |
| Apple                       | 138       | 193    | 1.07%   |
| China                       | 136       | 185    | 1.06%   |
| A-DATA Technology           | 107       | 146    | 0.83%   |
| KIOXIA                      | 95        | 123    | 0.74%   |
| Phison Electronics          | 94        | 145    | 0.73%   |
| Micron/Crucial Technology   | 85        | 122    | 0.66%   |
| OCZ                         | 75        | 86     | 0.58%   |
| PNY                         | 71        | 92     | 0.55%   |
| Silicon Motion              | 70        | 91     | 0.55%   |
| LITEON                      | 68        | 87     | 0.53%   |
| Maxtor                      | 61        | 93     | 0.47%   |
| Unknown                     | 61        | 79     | 0.47%   |
| Transcend                   | 60        | 72     | 0.47%   |
| Corsair                     | 56        | 76     | 0.44%   |
| Kingston Technology Company | 53        | 58     | 0.41%   |
| Fujitsu                     | 47        | 67     | 0.37%   |
| Integral                    | 43        | 49     | 0.33%   |
| Netac                       | 40        | 53     | 0.31%   |
| LITEONIT                    | 38        | 47     | 0.3%    |
| SABRENT                     | 33        | 41     | 0.26%   |
| JMicron Technology          | 33        | 46     | 0.26%   |
| SPCC                        | 29        | 44     | 0.23%   |
| Patriot                     | 29        | 47     | 0.23%   |
| Gigabyte Technology         | 29        | 40     | 0.23%   |
| ASMT                        | 29        | 61     | 0.23%   |
| Realtek                     | 21        | 24     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                             | 135       | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 116       | 0.8%    |
| Kingston SA400S37240G 240GB SSD                    | 107       | 0.74%   |
| Samsung SSD 850 EVO 250GB                          | 106       | 0.73%   |
| Seagate ST3500312CS 500GB                          | 99        | 0.68%   |
| Unknown MMC Card  64GB                             | 96        | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                        | 94        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                     | 93        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                     | 93        | 0.64%   |
| Samsung SSD 850 EVO 500GB                          | 93        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                       | 89        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 79        | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB                     | 78        | 0.54%   |
| Samsung SSD 860 EVO 500GB                          | 75        | 0.52%   |
| Kingston SA400S37120G 120GB SSD                    | 75        | 0.52%   |
| Samsung SSD 860 EVO 1TB                            | 71        | 0.49%   |
| Unknown MMC Card  128GB                            | 70        | 0.48%   |
| Toshiba MQ01ABD100 1TB                             | 69        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                       | 65        | 0.45%   |
| Seagate ST500DM002-1BD142 500GB                    | 63        | 0.43%   |
| Samsung NVMe SSD Drive 500GB                       | 63        | 0.43%   |
| Unknown                                            | 61        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                       | 59        | 0.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 58        | 0.4%    |
| Samsung NVMe SSD Drive 512GB                       | 54        | 0.37%   |
| Unknown SD/MMC/MS PRO 256GB                        | 51        | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                     | 51        | 0.35%   |
| Samsung NVMe SSD Drive 1TB                         | 50        | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                         | 49        | 0.34%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 49        | 0.34%   |
| Crucial CT250MX500SSD1 250GB                       | 49        | 0.34%   |
| Seagate Expansion 1TB                              | 48        | 0.33%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                | 48        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                   | 46        | 0.32%   |
| Unknown MMC Card  512GB                            | 45        | 0.31%   |
| Toshiba DT01ACA100 1TB                             | 45        | 0.31%   |
| Crucial CT1000BX500SSD1 1TB                        | 45        | 0.31%   |
| Kingston SA400S37480G 480GB SSD                    | 44        | 0.3%    |
| SanDisk SSD PLUS 480GB                             | 43        | 0.3%    |
| Samsung SSD 840 EVO 250GB                          | 43        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1756      | 2948   | 36.07%  |
| WDC                 | 1317      | 2248   | 27.05%  |
| Toshiba             | 603       | 837    | 12.39%  |
| Hitachi             | 427       | 591    | 8.77%   |
| Samsung Electronics | 239       | 343    | 4.91%   |
| HGST                | 183       | 267    | 3.76%   |
| Unknown             | 58        | 80     | 1.19%   |
| Apple               | 54        | 65     | 1.11%   |
| Maxtor              | 51        | 82     | 1.05%   |
| Fujitsu             | 47        | 67     | 0.97%   |
| ASMT                | 19        | 50     | 0.39%   |
| JMicron Technology  | 17        | 26     | 0.35%   |
| Hewlett-Packard     | 15        | 50     | 0.31%   |
| TO Exter            | 14        | 16     | 0.29%   |
| SSK                 | 8         | 11     | 0.16%   |
| USB3.0              | 6         | 11     | 0.12%   |
| External            | 6         | 11     | 0.12%   |
| LaCie               | 5         | 6      | 0.1%    |
| WD MediaMax         | 4         | 4      | 0.08%   |
| HPE                 | 4         | 7      | 0.08%   |
| ASMT109x            | 3         | 5      | 0.06%   |
| USB                 | 2         | 2      | 0.04%   |
| RSH-339             | 2         | 2      | 0.04%   |
| KESU                | 2         | 6      | 0.04%   |
| Initio              | 2         | 2      | 0.04%   |
| IBM/Hitachi         | 2         | 2      | 0.04%   |
| ExcelStor           | 2         | 5      | 0.04%   |
| ASMedia             | 2         | 2      | 0.04%   |
| TDAS                | 1         | 8      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SSI                 | 1         | 1      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| NETAPP              | 1         | 4      | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| LIO-ORG             | 1         | 8      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| Inateck             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 948       | 1439   | 22.15%  |
| Crucial             | 624       | 927    | 14.58%  |
| SanDisk             | 478       | 624    | 11.17%  |
| Kingston            | 468       | 631    | 10.93%  |
| WDC                 | 227       | 322    | 5.3%    |
| China               | 131       | 177    | 3.06%   |
| Intel               | 100       | 115    | 2.34%   |
| A-DATA Technology   | 82        | 112    | 1.92%   |
| OCZ                 | 75        | 86     | 1.75%   |
| Toshiba             | 74        | 98     | 1.73%   |
| Micron Technology   | 69        | 80     | 1.61%   |
| PNY                 | 68        | 85     | 1.59%   |
| SK hynix            | 67        | 83     | 1.57%   |
| LITEON              | 66        | 85     | 1.54%   |
| Apple               | 64        | 80     | 1.5%    |
| Transcend           | 55        | 67     | 1.29%   |
| Integral            | 43        | 49     | 1%      |
| LITEONIT            | 38        | 47     | 0.89%   |
| Netac               | 36        | 47     | 0.84%   |
| SABRENT             | 33        | 41     | 0.77%   |
| Corsair             | 32        | 45     | 0.75%   |
| Patriot             | 28        | 46     | 0.65%   |
| SPCC                | 25        | 39     | 0.58%   |
| Seagate             | 25        | 32     | 0.58%   |
| Gigabyte Technology | 22        | 31     | 0.51%   |
| Drevo               | 20        | 34     | 0.47%   |
| KIOXIA-EXCERIA      | 17        | 25     | 0.4%    |
| Team                | 16        | 19     | 0.37%   |
| Lexar               | 15        | 17     | 0.35%   |
| Unknown             | 14        | 20     | 0.33%   |
| Vaseky              | 13        | 19     | 0.3%    |
| TCSUNBOW            | 12        | 20     | 0.28%   |
| ORTIAL              | 11        | 12     | 0.26%   |
| XUM                 | 10        | 10     | 0.23%   |
| Maxtor              | 10        | 11     | 0.23%   |
| ASMT                | 10        | 10     | 0.23%   |
| Unknown             | 9         | 10     | 0.21%   |
| Teclast             | 8         | 11     | 0.19%   |
| Plextor             | 8         | 11     | 0.19%   |
| KingSpec            | 8         | 11     | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3969      | 7783   | 35.26%  |
| SSD     | 3584      | 5920   | 31.84%  |
| NVMe    | 2864      | 4260   | 25.45%  |
| MMC     | 659       | 876    | 5.86%   |
| Unknown | 179       | 279    | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6092      | 12982  | 59.81%  |
| NVMe | 2856      | 4228   | 28.04%  |
| MMC  | 659       | 876    | 6.47%   |
| SAS  | 579       | 1032   | 5.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4513      | 7538   | 55.31%  |
| 0.51-1.0        | 2226      | 3499   | 27.28%  |
| 1.01-2.0        | 761       | 1297   | 9.33%   |
| 3.01-4.0        | 236       | 494    | 2.89%   |
| 4.01-10.0       | 201       | 450    | 2.46%   |
| 2.01-3.0        | 190       | 341    | 2.33%   |
| 10.01-20.0      | 31        | 82     | 0.38%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2351      | 26.01%  |
| 251-500        | 1789      | 19.79%  |
| 501-1000       | 1382      | 15.29%  |
| 1001-2000      | 746       | 8.25%   |
| 1-20           | 642       | 7.1%    |
| More than 3000 | 609       | 6.74%   |
| 51-100         | 566       | 6.26%   |
| 21-50          | 388       | 4.29%   |
| 2001-3000      | 294       | 3.25%   |
| Unknown        | 273       | 3.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3610      | 38.46%  |
| 21-50          | 1547      | 16.48%  |
| 101-250        | 1119      | 11.92%  |
| 51-100         | 997       | 10.62%  |
| 251-500        | 700       | 7.46%   |
| 501-1000       | 492       | 5.24%   |
| 1001-2000      | 317       | 3.38%   |
| Unknown        | 273       | 2.91%   |
| More than 3000 | 220       | 2.34%   |
| 2001-3000      | 109       | 1.16%   |
| 0              | 2         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 9         | 14     | 1.35%   |
| Seagate ST9500325AS 500GB                | 8         | 12     | 1.2%    |
| Seagate ST3500418AS 500GB                | 7         | 7      | 1.05%   |
| Seagate ST500LM021-1KJ152 500GB          | 6         | 7      | 0.9%    |
| Seagate ST500DM002-1BD142 500GB          | 6         | 6      | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB           | 6         | 6      | 0.9%    |
| Samsung Electronics HD103UJ 1TB          | 6         | 8      | 0.9%    |
| HGST HTS725050A7E630 500GB               | 6         | 9      | 0.9%    |
| Seagate ST3500312CS 500GB                | 5         | 7      | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB           | 5         | 6      | 0.75%   |
| Hitachi HTS547575A9E384 752GB            | 5         | 7      | 0.75%   |
| HGST HTS721010A9E630 1TB                 | 5         | 5      | 0.75%   |
| HGST HTS541010A9E680 1TB                 | 5         | 5      | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 4         | 11     | 0.6%    |
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB          | 4         | 5      | 0.6%    |
| SanDisk SSD PLUS 240GB                   | 4         | 4      | 0.6%    |
| Samsung Electronics SSD 960 EVO 250GB    | 4         | 5      | 0.6%    |
| Samsung Electronics HD103SJ 1TB          | 4         | 5      | 0.6%    |
| Hitachi HTS545025B9A300 250GB            | 4         | 4      | 0.6%    |
| Hitachi HTS542512K9SA00 120GB            | 4         | 4      | 0.6%    |
| Hitachi HDT721010SLA360 1TB              | 4         | 5      | 0.6%    |
| Hitachi HDS721010CLA332 1TB              | 4         | 4      | 0.6%    |
| WDC WD6400AAKS-22A7B2 640GB              | 3         | 3      | 0.45%   |
| WDC WD60EFRX-68L0BN1 6TB                 | 3         | 20     | 0.45%   |
| WDC WD5000BEVT-75A0RT0 500GB             | 3         | 5      | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 3         | 3      | 0.45%   |
| WDC WD10EARS-00Y5B1 1TB                  | 3         | 4      | 0.45%   |
| Toshiba MK1656GSY 160GB                  | 3         | 3      | 0.45%   |
| Toshiba DT01ACA050 500GB                 | 3         | 4      | 0.45%   |
| Seagate ST9320325AS 320GB                | 3         | 4      | 0.45%   |
| Seagate ST3500620AS 500GB                | 3         | 4      | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB           | 3         | 3      | 0.45%   |
| Seagate ST1000LM014-SSHD-8GB             | 3         | 4      | 0.45%   |
| SanDisk SSD PLUS 480GB                   | 3         | 3      | 0.45%   |
| Samsung Electronics SSD 970 EVO Plus 1TB | 3         | 4      | 0.45%   |
| Samsung Electronics SSD 840 Series 120GB | 3         | 3      | 0.45%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 4      | 0.45%   |
| Intel SSDSC2BF180A5L 180GB               | 3         | 3      | 0.45%   |
| Intel SSDPEKKW512G7 512GB                | 3         | 6      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 196    | 23.68%  |
| WDC                 | 139       | 215    | 21.65%  |
| Hitachi             | 73        | 99     | 11.37%  |
| Samsung Electronics | 57        | 77     | 8.88%   |
| Toshiba             | 43        | 49     | 6.7%    |
| Crucial             | 28        | 35     | 4.36%   |
| Intel               | 21        | 32     | 3.27%   |
| HGST                | 20        | 23     | 3.12%   |
| SanDisk             | 17        | 21     | 2.65%   |
| Kingston            | 11        | 16     | 1.71%   |
| SK hynix            | 9         | 9      | 1.4%    |
| A-DATA Technology   | 7         | 10     | 1.09%   |
| Micron Technology   | 6         | 6      | 0.93%   |
| LITEON              | 6         | 7      | 0.93%   |
| Maxtor              | 5         | 7      | 0.78%   |
| Fujitsu             | 5         | 6      | 0.78%   |
| Drevo               | 4         | 12     | 0.62%   |
| Corsair             | 4         | 8      | 0.62%   |
| China               | 4         | 4      | 0.62%   |
| OCZ                 | 3         | 3      | 0.47%   |
| Hewlett-Packard     | 3         | 3      | 0.47%   |
| WD MediaMax         | 2         | 2      | 0.31%   |
| Unknown             | 2         | 2      | 0.31%   |
| Netac               | 2         | 2      | 0.31%   |
| BAITITON            | 2         | 5      | 0.31%   |
| Apple               | 2         | 3      | 0.31%   |
| Zheino              | 1         | 2      | 0.16%   |
| XrayDisk            | 1         | 1      | 0.16%   |
| VENO                | 1         | 1      | 0.16%   |
| Team                | 1         | 1      | 0.16%   |
| Mushkin             | 1         | 1      | 0.16%   |
| LITEONIT            | 1         | 2      | 0.16%   |
| Lexar               | 1         | 1      | 0.16%   |
| KingSpec            | 1         | 1      | 0.16%   |
| HECTRON             | 1         | 1      | 0.16%   |
| faspeed             | 1         | 1      | 0.16%   |
| BIWIN               | 1         | 1      | 0.16%   |
| Apacer              | 1         | 1      | 0.16%   |
| AGI                 | 1         | 1      | 0.16%   |
| 2-Power             | 1         | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 152       | 196    | 32.97%  |
| WDC                 | 133       | 208    | 28.85%  |
| Hitachi             | 73        | 99     | 15.84%  |
| Toshiba             | 40        | 46     | 8.68%   |
| Samsung Electronics | 24        | 33     | 5.21%   |
| HGST                | 20        | 23     | 4.34%   |
| Maxtor              | 5         | 7      | 1.08%   |
| Fujitsu             | 5         | 6      | 1.08%   |
| Hewlett-Packard     | 3         | 3      | 0.65%   |
| WD MediaMax         | 2         | 2      | 0.43%   |
| Unknown             | 2         | 2      | 0.43%   |
| Apple               | 2         | 3      | 0.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 418       | 628    | 69.9%   |
| SSD  | 149       | 198    | 24.92%  |
| NVMe | 31        | 43     | 5.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB              | 2         | 3      | 18.18%  |
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 9.09%   |
| Toshiba DT01ACA100 1TB                        | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB           | 1         | 1      | 9.09%   |
| Seagate ST3160815AS 160GB                     | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 980 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 960 EVO 250GB         | 1         | 2      | 9.09%   |
| Samsung Electronics HD502IJ 500GB             | 1         | 1      | 9.09%   |
| Hitachi HTS547550A9E384 500GB                 | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba                 | 4         | 5      | 36.36%  |
| Samsung Electronics     | 3         | 4      | 27.27%  |
| Seagate                 | 2         | 2      | 18.18%  |
| Union Memory (Shenzhen) | 1         | 1      | 9.09%   |
| Hitachi                 | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5507      | 12097  | 60.19%  |
| Works    | 3055      | 6139   | 33.39%  |
| Malfunc  | 578       | 869    | 6.32%   |
| Failed   | 10        | 13     | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5194      | 48.24%  |
| AMD                              | 1816      | 16.87%  |
| Samsung Electronics              | 1039      | 9.65%   |
| SanDisk                          | 481       | 4.47%   |
| Phison Electronics               | 291       | 2.7%    |
| SK hynix                         | 225       | 2.09%   |
| ASMedia Technology               | 202       | 1.88%   |
| Toshiba America Info Systems     | 170       | 1.58%   |
| Nvidia                           | 166       | 1.54%   |
| Micron/Crucial Technology        | 163       | 1.51%   |
| Kingston Technology Company      | 139       | 1.29%   |
| Marvell Technology Group         | 129       | 1.2%    |
| Micron Technology                | 96        | 0.89%   |
| JMicron Technology               | 95        | 0.88%   |
| KIOXIA                           | 90        | 0.84%   |
| Silicon Motion                   | 79        | 0.73%   |
| ADATA Technology                 | 51        | 0.47%   |
| LSI Logic / Symbios Logic        | 38        | 0.35%   |
| Broadcom / LSI                   | 29        | 0.27%   |
| Seagate Technology               | 27        | 0.25%   |
| Apple                            | 24        | 0.22%   |
| VIA Technologies                 | 22        | 0.2%    |
| Silicon Image                    | 22        | 0.2%    |
| O2 Micro                         | 20        | 0.19%   |
| MAXIO Technology (Hangzhou)      | 16        | 0.15%   |
| Hewlett-Packard                  | 16        | 0.15%   |
| Silicon Integrated Systems [SiS] | 15        | 0.14%   |
| Realtek Semiconductor            | 14        | 0.13%   |
| Union Memory (Shenzhen)          | 13        | 0.12%   |
| Lenovo                           | 13        | 0.12%   |
| Solid State Storage Technology   | 12        | 0.11%   |
| Shenzhen Longsys Electronics     | 10        | 0.09%   |
| Adaptec                          | 10        | 0.09%   |
| Lite-On Technology               | 7         | 0.07%   |
| Solidigm                         | 5         | 0.05%   |
| INNOGRIT                         | 5         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.03%   |
| Netac Technology                 | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1182      | 9.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 512       | 4.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 353       | 2.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 337       | 2.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 326       | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 285       | 2.28%   |
| AMD 400 Series Chipset SATA Controller                                         | 252       | 2.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 203       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 200       | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 195       | 1.56%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 192       | 1.54%   |
| Intel Volume Management Device NVMe RAID Controller                            | 187       | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 185       | 1.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 174       | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 170       | 1.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 166       | 1.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 157       | 1.26%   |
| Intel SATA Controller [RAID mode]                                              | 152       | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 152       | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 150       | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 144       | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 140       | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 136       | 1.09%   |
| Phison E12 NVMe Controller                                                     | 132       | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 132       | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 131       | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 128       | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 116       | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 109       | 0.87%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 107       | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 107       | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 106       | 0.85%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 103       | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 100       | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 98        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 95        | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 89        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 82        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 82        | 0.66%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 78        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5936      | 54.88%  |
| NVMe | 2875      | 26.58%  |
| IDE  | 1197      | 11.07%  |
| RAID | 736       | 6.8%    |
| SAS  | 45        | 0.42%   |
| SCSI | 27        | 0.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6061      | 71.8%   |
| AMD                   | 2270      | 26.89%  |
| ARM                   | 106       | 1.26%   |
| sifive,u74-mc         | 1         | 0.01%   |
| QUALCOMM              | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| CentaurHauls          | 1         | 0.01%   |
| Unknown               | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 120       | 1.42%   |
| AMD Ryzen 5 3600 6-Core Processor             | 90        | 1.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 81        | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 77        | 0.91%   |
| ARM Processor                                 | 73        | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 60        | 0.71%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 58        | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 56        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 55        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 55        | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 54        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 53        | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 50        | 0.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 50        | 0.59%   |
| AMD FX-8350 Eight-Core Processor              | 49        | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 47        | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 47        | 0.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 47        | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 45        | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 44        | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 0.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 42        | 0.5%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 42        | 0.5%    |
| Intel Core i7-4790K CPU @ 4.00GHz             | 41        | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 41        | 0.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 41        | 0.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 39        | 0.46%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 39        | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 39        | 0.46%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 39        | 0.46%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 38        | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 37        | 0.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 37        | 0.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 35        | 0.41%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 35        | 0.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 0.41%   |
| AMD FX-6300 Six-Core Processor                | 35        | 0.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 34        | 0.4%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 34        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1673      | 19.77%  |
| Intel Core i7           | 1543      | 18.23%  |
| Other                   | 722       | 8.53%   |
| Intel Core i3           | 516       | 6.1%    |
| AMD Ryzen 5             | 479       | 5.66%   |
| AMD Ryzen 7             | 415       | 4.9%    |
| Intel Celeron           | 413       | 4.88%   |
| Intel Core 2 Duo        | 356       | 4.21%   |
| Intel Xeon              | 223       | 2.63%   |
| Intel Pentium           | 203       | 2.4%    |
| AMD Ryzen 9             | 194       | 2.29%   |
| AMD FX                  | 172       | 2.03%   |
| Intel Atom              | 148       | 1.75%   |
| AMD Ryzen 3             | 94        | 1.11%   |
| AMD A6                  | 90        | 1.06%   |
| AMD A8                  | 89        | 1.05%   |
| Intel Pentium Dual-Core | 84        | 0.99%   |
| Intel Core 2 Quad       | 71        | 0.84%   |
| Intel Core i9           | 64        | 0.76%   |
| AMD A10                 | 63        | 0.74%   |
| Intel Core 2            | 60        | 0.71%   |
| AMD A4                  | 47        | 0.56%   |
| Intel Pentium Dual      | 45        | 0.53%   |
| AMD Athlon II X2        | 43        | 0.51%   |
| AMD Ryzen 7 PRO         | 34        | 0.4%    |
| AMD Phenom II X4        | 34        | 0.4%    |
| AMD Ryzen Threadripper  | 31        | 0.37%   |
| ARM BCM                 | 30        | 0.35%   |
| Intel Genuine           | 29        | 0.34%   |
| AMD Athlon 64 X2        | 28        | 0.33%   |
| AMD Athlon              | 26        | 0.31%   |
| AMD E1                  | 25        | 0.3%    |
| AMD E                   | 25        | 0.3%    |
| Intel Pentium 4         | 23        | 0.27%   |
| Intel Celeron Dual-Core | 21        | 0.25%   |
| Intel Pentium Silver    | 19        | 0.22%   |
| AMD Athlon II X4        | 18        | 0.21%   |
| Intel Pentium D         | 17        | 0.2%    |
| AMD Phenom II X6        | 16        | 0.19%   |
| Intel Celeron M         | 15        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3263      | 38.57%  |
| 4       | 2961      | 35%     |
| 6       | 819       | 9.68%   |
| 8       | 686       | 8.11%   |
| 1       | 200       | 2.36%   |
| 12      | 179       | 2.12%   |
| 16      | 110       | 1.3%    |
| 3       | 70        | 0.83%   |
| 10      | 64        | 0.76%   |
| 14      | 52        | 0.61%   |
| 24      | 23        | 0.27%   |
| 32      | 9         | 0.11%   |
| Unknown | 9         | 0.11%   |
| 20      | 4         | 0.05%   |
| 28      | 3         | 0.04%   |
| 64      | 2         | 0.02%   |
| 40      | 2         | 0.02%   |
| 36      | 2         | 0.02%   |
| 44      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8327      | 98.64%  |
| 2       | 101       | 1.2%    |
| Unknown | 9         | 0.11%   |
| 4       | 3         | 0.04%   |
| 3       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5571      | 65.91%  |
| 1       | 2872      | 33.98%  |
| Unknown | 9         | 0.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8202      | 96.85%  |
| Unknown        | 184       | 2.17%   |
| 32-bit         | 76        | 0.9%    |
| 64-bit         | 7         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2766      | 31.36%  |
| 0x306a9    | 398       | 4.51%   |
| 0x206a7    | 384       | 4.35%   |
| 0x306c3    | 324       | 3.67%   |
| 0x1067a    | 277       | 3.14%   |
| 0x906ea    | 172       | 1.95%   |
| 0x806ea    | 154       | 1.75%   |
| 0x506e3    | 152       | 1.72%   |
| 0x08701021 | 145       | 1.64%   |
| 0x806e9    | 143       | 1.62%   |
| 0x806ec    | 137       | 1.55%   |
| 0x406e3    | 136       | 1.54%   |
| 0x40651    | 132       | 1.5%    |
| 0x20655    | 121       | 1.37%   |
| 0x806c1    | 120       | 1.36%   |
| 0x906e9    | 119       | 1.35%   |
| 0x306d4    | 116       | 1.32%   |
| 0x6fd      | 98        | 1.11%   |
| 0x406c4    | 92        | 1.04%   |
| 0x06000852 | 86        | 0.98%   |
| 0x010000c8 | 85        | 0.96%   |
| 0x0800820d | 83        | 0.94%   |
| 0x30678    | 77        | 0.87%   |
| 0x08108109 | 73        | 0.83%   |
| 0x06001119 | 70        | 0.79%   |
| 0x10676    | 69        | 0.78%   |
| 0x0a50000c | 62        | 0.7%    |
| 0x08701013 | 58        | 0.66%   |
| 0x506c9    | 56        | 0.63%   |
| 0xa0652    | 53        | 0.6%    |
| 0x6fb      | 53        | 0.6%    |
| 0x706e5    | 52        | 0.59%   |
| 0x08600106 | 50        | 0.57%   |
| 0x20652    | 49        | 0.56%   |
| 0x06006705 | 49        | 0.56%   |
| 0x906ed    | 46        | 0.52%   |
| 0x406c3    | 46        | 0.52%   |
| 0x08108102 | 43        | 0.49%   |
| 0x706a1    | 41        | 0.46%   |
| 0x06003106 | 41        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 1196      | 14.12%  |
| Haswell           | 694       | 8.19%   |
| IvyBridge         | 566       | 6.68%   |
| SandyBridge       | 542       | 6.4%    |
| Unknown           | 486       | 5.74%   |
| Skylake           | 444       | 5.24%   |
| Penryn            | 438       | 5.17%   |
| Zen 2             | 406       | 4.79%   |
| Silvermont        | 289       | 3.41%   |
| Core              | 283       | 3.34%   |
| Zen 3             | 279       | 3.29%   |
| Zen+              | 275       | 3.25%   |
| Westmere          | 266       | 3.14%   |
| Piledriver        | 223       | 2.63%   |
| TigerLake         | 206       | 2.43%   |
| K10               | 188       | 2.22%   |
| Broadwell         | 186       | 2.2%    |
| Zen               | 170       | 2.01%   |
| CometLake         | 156       | 1.84%   |
| Alderlake Hybrid  | 148       | 1.75%   |
| Icelake           | 130       | 1.53%   |
| Excavator         | 129       | 1.52%   |
| Goldmont plus     | 113       | 1.33%   |
| Nehalem           | 85        | 1%      |
| Goldmont          | 73        | 0.86%   |
| Puma              | 63        | 0.74%   |
| K8 Hammer         | 62        | 0.73%   |
| Steamroller       | 60        | 0.71%   |
| Bonnell           | 52        | 0.61%   |
| Bobcat            | 52        | 0.61%   |
| NetBurst          | 45        | 0.53%   |
| P6                | 41        | 0.48%   |
| Jaguar            | 34        | 0.4%    |
| Bulldozer         | 31        | 0.37%   |
| Tremont           | 23        | 0.27%   |
| K8 & K10 hybrid   | 13        | 0.15%   |
| K10 Llano         | 13        | 0.15%   |
| Gracemont         | 7         | 0.08%   |
| K6                | 4         | 0.05%   |
| Meteorlake Hybrid | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4642      | 48.56%  |
| Nvidia                                       | 2599      | 27.19%  |
| AMD                                          | 2228      | 23.31%  |
| Matrox Electronics Systems                   | 44        | 0.46%   |
| Silicon Integrated Systems [SiS]             | 15        | 0.16%   |
| ASPEED Technology                            | 15        | 0.16%   |
| ATI Technologies                             | 8         | 0.08%   |
| VIA Technologies                             | 5         | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| Huawei Technologies                          | 1         | 0.01%   |
| Alliance Semiconductor                       | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 401       | 4.06%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 316       | 3.2%    |
| Intel UHD Graphics 620                                                                   | 196       | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 185       | 1.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 184       | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 181       | 1.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 177       | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 169       | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 169       | 1.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 166       | 1.68%   |
| Intel HD Graphics 620                                                                    | 165       | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 162       | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 152       | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 151       | 1.53%   |
| Intel HD Graphics 5500                                                                   | 123       | 1.25%   |
| Intel HD Graphics 530                                                                    | 121       | 1.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 119       | 1.2%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 119       | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 118       | 1.19%   |
| Intel HD Graphics 630                                                                    | 118       | 1.19%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 117       | 1.18%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 117       | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 108       | 1.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 107       | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 98        | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 90        | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 84        | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 78        | 0.79%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 75        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 73        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 72        | 0.73%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 65        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 65        | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 63        | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 63        | 0.64%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 63        | 0.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 61        | 0.62%   |
| AMD Lucienne                                                                             | 61        | 0.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 60        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 59        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| 1 x Intel                            | 3580      | 41.96%  |
| 1 x AMD                              | 1887      | 22.12%  |
| 1 x Nvidia                           | 1630      | 19.11%  |
| Intel + Nvidia                       | 807       | 9.46%   |
| Intel + AMD                          | 130       | 1.52%   |
| Other                                | 122       | 1.43%   |
| AMD + Nvidia                         | 113       | 1.32%   |
| 2 x AMD                              | 101       | 1.18%   |
| 1 x Matrox                           | 38        | 0.45%   |
| 2 x Nvidia                           | 35        | 0.41%   |
| 2 x Intel                            | 30        | 0.35%   |
| 1 x SiS                              | 14        | 0.16%   |
| Nvidia + ASPEED                      | 7         | 0.08%   |
| 1 x ASPEED                           | 7         | 0.08%   |
| 1 x VIA                              | 5         | 0.06%   |
| Nvidia + Matrox                      | 4         | 0.05%   |
| Intel + AMD + 1 x Nvidia             | 4         | 0.05%   |
| 2 x AMD + 1 x Nvidia                 | 3         | 0.04%   |
| Intel + 2 x Nvidia                   | 2         | 0.02%   |
| 3 x AMD                              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox              | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED              | 1         | 0.01%   |
| 2 x AMD + 1 x Alliance Semiconductor | 1         | 0.01%   |
| 1 x XGI                              | 1         | 0.01%   |
| 1 x Intel + 3 x Nvidia               | 1         | 0.01%   |
| Intel + 2 x AMD                      | 1         | 0.01%   |
| Intel + AMD + 3 x Nvidia             | 1         | 0.01%   |
| 1 x Huawei Technologies              | 1         | 0.01%   |
| AMD + SiS                            | 1         | 0.01%   |
| AMD + Matrox                         | 1         | 0.01%   |
| AMD + ASPEED                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6683      | 77.64%  |
| Proprietary | 1495      | 17.37%  |
| Unknown     | 430       | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5067      | 57.97%  |
| 0.01-0.5   | 953       | 10.9%   |
| 1.01-2.0   | 867       | 9.92%   |
| 0.51-1.0   | 547       | 6.26%   |
| 3.01-4.0   | 495       | 5.66%   |
| 7.01-8.0   | 393       | 4.5%    |
| 5.01-6.0   | 187       | 2.14%   |
| 8.01-16.0  | 152       | 1.74%   |
| 2.01-3.0   | 60        | 0.69%   |
| 16.01-24.0 | 15        | 0.17%   |
| 4.01-5.0   | 2         | 0.02%   |
| 24.01-32.0 | 1         | 0.01%   |
| 0          | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1029      | 11.49%  |
| AU Optronics            | 947       | 10.57%  |
| LG Display              | 760       | 8.48%   |
| Dell                    | 639       | 7.13%   |
| Chimei Innolux          | 598       | 6.68%   |
| BOE                     | 592       | 6.61%   |
| Acer                    | 367       | 4.1%    |
| Goldstar                | 310       | 3.46%   |
| Hewlett-Packard         | 289       | 3.23%   |
| AOC                     | 287       | 3.2%    |
| BenQ                    | 284       | 3.17%   |
| Sharp                   | 261       | 2.91%   |
| Apple                   | 213       | 2.38%   |
| Iiyama                  | 201       | 2.24%   |
| Lenovo                  | 178       | 1.99%   |
| Ancor Communications    | 158       | 1.76%   |
| Philips                 | 137       | 1.53%   |
| ViewSonic               | 97        | 1.08%   |
| Chi Mei Optoelectronics | 92        | 1.03%   |
| Sony                    | 90        | 1%      |
| ASUSTek Computer        | 83        | 0.93%   |
| Valve                   | 79        | 0.88%   |
| PANDA                   | 73        | 0.82%   |
| Unknown                 | 72        | 0.8%    |
| HannStar                | 68        | 0.76%   |
| Panasonic               | 63        | 0.7%    |
| InfoVision              | 55        | 0.61%   |
| LG Philips              | 52        | 0.58%   |
| Toshiba                 | 50        | 0.56%   |
| Vestel Elektronik       | 49        | 0.55%   |
| LG Electronics          | 45        | 0.5%    |
| MSI                     | 43        | 0.48%   |
| NEC Computers           | 34        | 0.38%   |
| CSO                     | 27        | 0.3%    |
| Gigabyte Technology     | 26        | 0.29%   |
| Analogix                | 26        | 0.29%   |
| Hitachi                 | 24        | 0.27%   |
| OEM                     | 20        | 0.22%   |
| Idek Iiyama             | 18        | 0.2%    |
| CVT                     | 17        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 73        | 0.79%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 48        | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 47        | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 38        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 33        | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 33        | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 31        | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 31        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 31        | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 30        | 0.32%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 27        | 0.29%   |
| Analogix ANX7530 U ANX7539 800x1280                                   | 26        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 24        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 23        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 22        | 0.24%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 22        | 0.24%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                       | 22        | 0.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 21        | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 21        | 0.23%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 20        | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 20        | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 19        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 19        | 0.2%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 19        | 0.2%    |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 18        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 18        | 0.19%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 18        | 0.19%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 17        | 0.18%   |
| OEM 19W_LCD_TV OEM3700 1920x540                                       | 17        | 0.18%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                     | 17        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 16        | 0.17%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 16        | 0.17%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 15        | 0.16%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 15        | 0.16%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 14        | 0.15%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 14        | 0.15%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 14        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 14        | 0.15%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 14        | 0.15%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 14        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3555      | 41.22%  |
| 1366x768 (WXGA)    | 1392      | 16.14%  |
| 3840x2160 (4K)     | 711       | 8.24%   |
| 2560x1440 (QHD)    | 479       | 5.55%   |
| 1280x1024 (SXGA)   | 261       | 3.03%   |
| 1280x800 (WXGA)    | 231       | 2.68%   |
| 1920x1200 (WUXGA)  | 227       | 2.63%   |
| 1600x900 (HD+)     | 225       | 2.61%   |
| 1680x1050 (WSXGA+) | 206       | 2.39%   |
| 1440x900 (WXGA+)   | 203       | 2.35%   |
| 3440x1440          | 120       | 1.39%   |
| Unknown            | 115       | 1.33%   |
| 800x1280           | 99        | 1.15%   |
| 2560x1600          | 81        | 0.94%   |
| 2560x1080          | 66        | 0.77%   |
| 1360x768           | 63        | 0.73%   |
| 3840x1080          | 56        | 0.65%   |
| 1920x540           | 51        | 0.59%   |
| 3840x2400          | 46        | 0.53%   |
| 2880x1800          | 45        | 0.52%   |
| 1024x768 (XGA)     | 34        | 0.39%   |
| 2736x1824          | 29        | 0.34%   |
| 3200x1800 (QHD+)   | 28        | 0.32%   |
| 1600x1200          | 24        | 0.28%   |
| 1024x600           | 24        | 0.28%   |
| 2160x1440          | 21        | 0.24%   |
| 1280x720 (HD)      | 21        | 0.24%   |
| 2288x1287          | 14        | 0.16%   |
| 2256x1504          | 14        | 0.16%   |
| 1920x1280          | 12        | 0.14%   |
| 5120x1440          | 8         | 0.09%   |
| 3072x1920          | 8         | 0.09%   |
| 3000x2000          | 8         | 0.09%   |
| 5760x1080          | 7         | 0.08%   |
| 3840x1200          | 6         | 0.07%   |
| 3456x2160          | 6         | 0.07%   |
| 1680x945           | 6         | 0.07%   |
| 7680x2160          | 5         | 0.06%   |
| 3840x1600          | 5         | 0.06%   |
| 3200x1080          | 5         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1975      | 22.15%  |
| 13      | 859       | 9.64%   |
| 27      | 733       | 8.22%   |
| 24      | 643       | 7.21%   |
| Unknown | 534       | 5.99%   |
| 14      | 532       | 5.97%   |
| 23      | 530       | 5.95%   |
| 21      | 506       | 5.68%   |
| 17      | 424       | 4.76%   |
| 12      | 251       | 2.82%   |
| 19      | 221       | 2.48%   |
| 31      | 207       | 2.32%   |
| 84      | 139       | 1.56%   |
| 11      | 139       | 1.56%   |
| 34      | 138       | 1.55%   |
| 22      | 124       | 1.39%   |
| 18      | 100       | 1.12%   |
| 20      | 92        | 1.03%   |
| 7       | 76        | 0.85%   |
| 16      | 75        | 0.84%   |
| 72      | 72        | 0.81%   |
| 26      | 52        | 0.58%   |
| 32      | 50        | 0.56%   |
| 10      | 46        | 0.52%   |
| 25      | 44        | 0.49%   |
| 54      | 33        | 0.37%   |
| 40      | 28        | 0.31%   |
| 3       | 26        | 0.29%   |
| 48      | 22        | 0.25%   |
| 28      | 22        | 0.25%   |
| 33      | 21        | 0.24%   |
| 39      | 19        | 0.21%   |
| 65      | 18        | 0.2%    |
| 52      | 13        | 0.15%   |
| 46      | 13        | 0.15%   |
| 60      | 12        | 0.13%   |
| 35      | 12        | 0.13%   |
| 142     | 11        | 0.12%   |
| 43      | 9         | 0.1%    |
| 42      | 9         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2948      | 33.59%  |
| 501-600        | 1773      | 20.2%   |
| 201-300        | 973       | 11.09%  |
| 401-500        | 906       | 10.32%  |
| Unknown        | 534       | 6.08%   |
| 351-400        | 518       | 5.9%    |
| 601-700        | 336       | 3.83%   |
| 701-800        | 215       | 2.45%   |
| 1501-2000      | 215       | 2.45%   |
| 1001-1500      | 153       | 1.74%   |
| 1-100          | 99        | 1.13%   |
| 801-900        | 64        | 0.73%   |
| 901-1000       | 21        | 0.24%   |
| More than 2000 | 13        | 0.15%   |
| 101-200        | 9         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5886      | 72.12%  |
| 16/10   | 1039      | 12.73%  |
| Unknown | 463       | 5.67%   |
| 5/4     | 242       | 2.97%   |
| 21/9    | 167       | 2.05%   |
| 3/2     | 124       | 1.52%   |
| 0.67    | 73        | 0.89%   |
| 4/3     | 68        | 0.83%   |
| 6/5     | 44        | 0.54%   |
| 32/9    | 25        | 0.31%   |
| 1.00    | 16        | 0.2%    |
| 0.62    | 6         | 0.07%   |
| 0.56    | 3         | 0.04%   |
| 3.20    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1967      | 22.28%  |
| 201-250        | 1424      | 16.13%  |
| 81-90          | 943       | 10.68%  |
| 301-350        | 772       | 8.74%   |
| Unknown        | 534       | 6.05%   |
| 151-200        | 475       | 5.38%   |
| 71-80          | 458       | 5.19%   |
| 351-500        | 445       | 5.04%   |
| More than 1000 | 336       | 3.81%   |
| 121-130        | 259       | 2.93%   |
| 251-300        | 249       | 2.82%   |
| 61-70          | 223       | 2.53%   |
| 141-150        | 183       | 2.07%   |
| 51-60          | 144       | 1.63%   |
| 501-1000       | 119       | 1.35%   |
| 1-40           | 108       | 1.22%   |
| 111-120        | 75        | 0.85%   |
| 131-140        | 50        | 0.57%   |
| 41-50          | 42        | 0.48%   |
| 91-100         | 22        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2676      | 31.06%  |
| 101-120       | 2090      | 24.26%  |
| 121-160       | 2082      | 24.17%  |
| 161-240       | 699       | 8.11%   |
| Unknown       | 534       | 6.2%    |
| More than 240 | 310       | 3.6%    |
| 1-50          | 224       | 2.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6924      | 79.78%  |
| 2     | 1173      | 13.52%  |
| 0     | 439       | 5.06%   |
| 3     | 130       | 1.5%    |
| 4     | 12        | 0.14%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4231      | 33.71%  |
| Intel                             | 4206      | 33.51%  |
| Qualcomm Atheros                  | 1223      | 9.74%   |
| Broadcom                          | 832       | 6.63%   |
| Ralink Technology                 | 233       | 1.86%   |
| Marvell Technology Group          | 184       | 1.47%   |
| Broadcom Limited                  | 177       | 1.41%   |
| MediaTek                          | 161       | 1.28%   |
| TP-Link                           | 141       | 1.12%   |
| Nvidia                            | 132       | 1.05%   |
| Ralink                            | 123       | 0.98%   |
| ASIX Electronics                  | 66        | 0.53%   |
| Samsung Electronics               | 50        | 0.4%    |
| DisplayLink                       | 50        | 0.4%    |
| Microsoft                         | 43        | 0.34%   |
| Ericsson Business Mobile Networks | 43        | 0.34%   |
| Dell                              | 40        | 0.32%   |
| Qualcomm                          | 39        | 0.31%   |
| NetGear                           | 33        | 0.26%   |
| Lenovo                            | 32        | 0.25%   |
| Qualcomm Atheros Communications   | 30        | 0.24%   |
| Belkin Components                 | 30        | 0.24%   |
| Huawei Technologies               | 28        | 0.22%   |
| Edimax Technology                 | 27        | 0.22%   |
| Aquantia                          | 25        | 0.2%    |
| Sierra Wireless                   | 22        | 0.18%   |
| Hewlett-Packard                   | 20        | 0.16%   |
| ASUSTek Computer                  | 17        | 0.14%   |
| Microchip Technology              | 16        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.12%   |
| Xiaomi                            | 14        | 0.11%   |
| Google                            | 13        | 0.1%    |
| Mellanox Technologies             | 12        | 0.1%    |
| JMicron Technology                | 12        | 0.1%    |
| OPPO Electronics                  | 11        | 0.09%   |
| D-Link                            | 11        | 0.09%   |
| Apple                             | 11        | 0.09%   |
| VIA Technologies                  | 10        | 0.08%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.07%   |
| D-Link System                     | 8         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2713      | 18.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 455       | 3.07%   |
| Intel Wi-Fi 6 AX200                                                    | 404       | 2.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 337       | 2.27%   |
| Intel I211 Gigabit Network Connection                                  | 271       | 1.83%   |
| Intel Wireless 8265 / 8275                                             | 250       | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 236       | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 210       | 1.42%   |
| Intel Wireless 7265                                                    | 201       | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                      | 199       | 1.34%   |
| Intel Wireless 7260                                                    | 186       | 1.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 174       | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 166       | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 164       | 1.11%   |
| Intel Wireless 3165                                                    | 148       | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 146       | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 141       | 0.95%   |
| Intel Wi-Fi 6 AX201                                                    | 141       | 0.95%   |
| Intel Wireless 8260                                                    | 140       | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 133       | 0.9%    |
| Intel Ethernet Connection (2) I219-V                                   | 133       | 0.9%    |
| Intel Ethernet Connection I217-LM                                      | 127       | 0.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 116       | 0.78%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 105       | 0.71%   |
| Intel Ethernet Controller I225-V                                       | 103       | 0.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 97        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 95        | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 94        | 0.63%   |
| Realtek 802.11ac NIC                                                   | 88        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 86        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 82        | 0.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 80        | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 79        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 79        | 0.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 79        | 0.53%   |
| Ralink MT7601U Wireless Adapter                                        | 78        | 0.53%   |
| Intel Ethernet Connection (4) I219-LM                                  | 75        | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 74        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                                   | 74        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                          | 74        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3085      | 44.22%  |
| Realtek Semiconductor             | 1226      | 17.57%  |
| Qualcomm Atheros                  | 987       | 14.15%  |
| Broadcom                          | 536       | 7.68%   |
| Ralink Technology                 | 233       | 3.34%   |
| MediaTek                          | 150       | 2.15%   |
| TP-Link                           | 134       | 1.92%   |
| Broadcom Limited                  | 129       | 1.85%   |
| Ralink                            | 122       | 1.75%   |
| Marvell Technology Group          | 42        | 0.6%    |
| Microsoft                         | 40        | 0.57%   |
| NetGear                           | 33        | 0.47%   |
| Qualcomm Atheros Communications   | 30        | 0.43%   |
| Belkin Components                 | 29        | 0.42%   |
| Edimax Technology                 | 27        | 0.39%   |
| Qualcomm                          | 26        | 0.37%   |
| Dell                              | 23        | 0.33%   |
| Sierra Wireless                   | 22        | 0.32%   |
| ASUSTek Computer                  | 16        | 0.23%   |
| D-Link                            | 11        | 0.16%   |
| Ericsson Business Mobile Networks | 9         | 0.13%   |
| IMC Networks                      | 7         | 0.1%    |
| D-Link System                     | 7         | 0.1%    |
| Micro Star International          | 6         | 0.09%   |
| Fibocom                           | 6         | 0.09%   |
| ZyDAS                             | 5         | 0.07%   |
| Gemtek                            | 5         | 0.07%   |
| Linksys                           | 4         | 0.06%   |
| Wacom                             | 3         | 0.04%   |
| TRENDnet                          | 3         | 0.04%   |
| Sitecom Europe                    | 3         | 0.04%   |
| Wilocity                          | 2         | 0.03%   |
| Qualcomm Technologies             | 2         | 0.03%   |
| Philips (or NXP)                  | 2         | 0.03%   |
| Hewlett-Packard                   | 2         | 0.03%   |
| Texas Instruments                 | 1         | 0.01%   |
| Senao                             | 1         | 0.01%   |
| InProComm                         | 1         | 0.01%   |
| Fujitsu Siemens Computers         | 1         | 0.01%   |
| CyberTAN Technology               | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 404       | 5.74%   |
| Intel Wireless 8265 / 8275                                              | 250       | 3.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 210       | 2.98%   |
| Intel Wireless 7265                                                     | 201       | 2.86%   |
| Intel Wireless 7260                                                     | 186       | 2.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 174       | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 166       | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 164       | 2.33%   |
| Intel Wireless 3165                                                     | 148       | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 146       | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 141       | 2%      |
| Intel Wi-Fi 6 AX201                                                     | 141       | 2%      |
| Intel Wireless 8260                                                     | 140       | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 133       | 1.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 116       | 1.65%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 105       | 1.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 97        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 95        | 1.35%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 94        | 1.34%   |
| Realtek 802.11ac NIC                                                    | 88        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 86        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 82        | 1.16%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 80        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 79        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 79        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 79        | 1.12%   |
| Ralink MT7601U Wireless Adapter                                         | 78        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 74        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 74        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 65        | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 64        | 0.91%   |
| Ralink RT5370 Wireless Adapter                                          | 62        | 0.88%   |
| Intel Wireless 3160                                                     | 62        | 0.88%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter            | 62        | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 0.78%   |
| Intel WiFi Link 5100                                                    | 55        | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 54        | 0.77%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 52        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 50        | 0.71%   |
| Intel Centrino Ultimate-N 6300                                          | 48        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3669      | 49.24%  |
| Intel                                  | 2234      | 29.98%  |
| Broadcom                               | 416       | 5.58%   |
| Qualcomm Atheros                       | 348       | 4.67%   |
| Marvell Technology Group               | 142       | 1.91%   |
| Nvidia                                 | 132       | 1.77%   |
| ASIX Electronics                       | 66        | 0.89%   |
| Broadcom Limited                       | 51        | 0.68%   |
| DisplayLink                            | 50        | 0.67%   |
| Samsung Electronics                    | 49        | 0.66%   |
| Lenovo                                 | 29        | 0.39%   |
| Aquantia                               | 25        | 0.34%   |
| Huawei Technologies                    | 24        | 0.32%   |
| Xiaomi                                 | 14        | 0.19%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.19%   |
| Microchip Technology                   | 14        | 0.19%   |
| Qualcomm                               | 13        | 0.17%   |
| Google                                 | 13        | 0.17%   |
| JMicron Technology                     | 12        | 0.16%   |
| OPPO Electronics                       | 11        | 0.15%   |
| Mellanox Technologies                  | 11        | 0.15%   |
| VIA Technologies                       | 10        | 0.13%   |
| MediaTek                               | 9         | 0.12%   |
| Apple                                  | 9         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 8         | 0.11%   |
| TP-Link                                | 7         | 0.09%   |
| ICS Advent                             | 7         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.08%   |
| Motorola PCS                           | 6         | 0.08%   |
| Hewlett-Packard                        | 5         | 0.07%   |
| Attansic Technology                    | 5         | 0.07%   |
| T & A Mobile Phones                    | 4         | 0.05%   |
| Standard Microsystems                  | 4         | 0.05%   |
| Emulex                                 | 4         | 0.05%   |
| Microsoft                              | 3         | 0.04%   |
| HTC (High Tech Computer)               | 3         | 0.04%   |
| 3Com                                   | 3         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| Research In Motion                     | 2         | 0.03%   |
| QLogic                                 | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 2713      | 35.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 455       | 5.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 337       | 4.41%   |
| Intel I211 Gigabit Network Connection                                  | 271       | 3.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 236       | 3.09%   |
| Realtek RTL8125 2.5GbE Controller                                      | 199       | 2.6%    |
| Intel Ethernet Connection (2) I219-V                                   | 133       | 1.74%   |
| Intel Ethernet Connection I217-LM                                      | 127       | 1.66%   |
| Intel Ethernet Controller I225-V                                       | 103       | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                                  | 75        | 0.98%   |
| Intel Ethernet Connection (7) I219-V                                   | 74        | 0.97%   |
| Intel 82579V Gigabit Network Connection                                | 72        | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 71        | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 65        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 62        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                          | 55        | 0.72%   |
| Nvidia MCP61 Ethernet                                                  | 53        | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 53        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                  | 52        | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 51        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 50        | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                  | 49        | 0.64%   |
| Intel Ethernet Connection (4) I219-V                                   | 48        | 0.63%   |
| Intel 82574L Gigabit Network Connection                                | 48        | 0.63%   |
| Intel Ethernet Connection I217-V                                       | 47        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                                   | 45        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 44        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                               | 43        | 0.56%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 42        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 39        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 39        | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                   | 38        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 38        | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 37        | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 37        | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                  | 36        | 0.47%   |
| Nvidia MCP79 Ethernet                                                  | 33        | 0.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 32        | 0.42%   |
| Intel Ethernet Connection I219-V                                       | 31        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 30        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7018      | 51.25%  |
| WiFi     | 6519      | 47.6%   |
| Modem    | 137       | 1%      |
| Unknown  | 20        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 5055      | 57.85%  |
| Ethernet | 3681      | 42.13%  |
| Modem    | 1         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4391      | 51.66%  |
| 1     | 3616      | 42.55%  |
| 0     | 224       | 2.64%   |
| 3     | 191       | 2.25%   |
| 4     | 48        | 0.56%   |
| 5     | 19        | 0.22%   |
| 6     | 8         | 0.09%   |
| 8     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7333      | 85.45%  |
| Yes  | 1249      | 14.55%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2442      | 46.97%  |
| Realtek Semiconductor           | 436       | 8.39%   |
| Cambridge Silicon Radio         | 363       | 6.98%   |
| Qualcomm Atheros Communications | 347       | 6.67%   |
| Broadcom                        | 310       | 5.96%   |
| IMC Networks                    | 252       | 4.85%   |
| Apple                           | 233       | 4.48%   |
| Foxconn / Hon Hai               | 148       | 2.85%   |
| Lite-On Technology              | 118       | 2.27%   |
| ASUSTek Computer                | 87        | 1.67%   |
| Dell                            | 82        | 1.58%   |
| Toshiba                         | 63        | 1.21%   |
| Hewlett-Packard                 | 48        | 0.92%   |
| MediaTek                        | 47        | 0.9%    |
| Marvell Semiconductor           | 38        | 0.73%   |
| Realtek                         | 26        | 0.5%    |
| TP-Link                         | 21        | 0.4%    |
| Belkin Components               | 20        | 0.38%   |
| Alps Electric                   | 19        | 0.37%   |
| Foxconn International           | 14        | 0.27%   |
| Integrated System Solution      | 13        | 0.25%   |
| USI                             | 11        | 0.21%   |
| Ralink                          | 11        | 0.21%   |
| Ralink Technology               | 7         | 0.13%   |
| Taiyo Yuden                     | 6         | 0.12%   |
| Askey Computer                  | 6         | 0.12%   |
| Micro Star International        | 5         | 0.1%    |
| Logitech                        | 5         | 0.1%    |
| HTC (High Tech Computer)        | 5         | 0.1%    |
| Unknown                         | 4         | 0.08%   |
| Edimax Technology               | 3         | 0.06%   |
| Sitecom Europe                  | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| GN Netcom                       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Cypress Semiconductor           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 942       | 18.1%   |
| Intel AX201 Bluetooth                               | 390       | 7.5%    |
| Intel AX200 Bluetooth                               | 373       | 7.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 363       | 6.98%   |
| Realtek Bluetooth Radio                             | 311       | 5.98%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 246       | 4.73%   |
| IMC Networks Bluetooth Radio                        | 171       | 3.29%   |
| Intel Bluetooth Device                              | 146       | 2.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 128       | 2.46%   |
| Apple Bluetooth Host Controller                     | 112       | 2.15%   |
| Intel AX210 Bluetooth                               | 105       | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 95        | 1.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 94        | 1.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 87        | 1.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 84        | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 79        | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 70        | 1.35%   |
| Foxconn / Hon Hai Bluetooth Device                  | 64        | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 63        | 1.21%   |
| Apple Bluetooth USB Host Controller                 | 59        | 1.13%   |
| MediaTek Wireless_Device                            | 47        | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 47        | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 43        | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 39        | 0.75%   |
| IMC Networks Wireless_Device                        | 35        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 0.65%   |
| Marvell Bluetooth and Wireless LAN Composite        | 34        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 34        | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 34        | 0.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 0.6%    |
| Lite-On Bluetooth Device                            | 29        | 0.56%   |
| IMC Networks Bluetooth Device                       | 27        | 0.52%   |
| Realtek Bluetooth Radio                             | 26        | 0.5%    |
| Dell DW375 Bluetooth Module                         | 26        | 0.5%    |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 24        | 0.46%   |
| Apple Bluetooth HCI                                 | 24        | 0.46%   |
| Toshiba Bluetooth Device                            | 22        | 0.42%   |
| TP-Link UB500 Adapter                               | 21        | 0.4%    |
| Dell BCM20702A0 Bluetooth Module                    | 21        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 5755      | 48.84%  |
| AMD                                  | 2555      | 21.68%  |
| Nvidia                               | 2048      | 17.38%  |
| C-Media Electronics                  | 217       | 1.84%   |
| Creative Labs                        | 97        | 0.82%   |
| Logitech                             | 78        | 0.66%   |
| Texas Instruments                    | 66        | 0.56%   |
| Realtek Semiconductor                | 49        | 0.42%   |
| JMTek                                | 45        | 0.38%   |
| ASUSTek Computer                     | 45        | 0.38%   |
| Razer USA                            | 42        | 0.36%   |
| Focusrite-Novation                   | 41        | 0.35%   |
| GN Netcom                            | 39        | 0.33%   |
| Creative Technology                  | 38        | 0.32%   |
| SteelSeries ApS                      | 34        | 0.29%   |
| Plantronics                          | 33        | 0.28%   |
| Micro Star International             | 32        | 0.27%   |
| Corsair                              | 24        | 0.2%    |
| VIA Technologies                     | 22        | 0.19%   |
| Lenovo                               | 22        | 0.19%   |
| Kingston Technology                  | 22        | 0.19%   |
| Blue Microphones                     | 22        | 0.19%   |
| Generalplus Technology               | 21        | 0.18%   |
| Apple                                | 16        | 0.14%   |
| Silicon Integrated Systems [SiS]     | 15        | 0.13%   |
| KTMicro                              | 14        | 0.12%   |
| BEHRINGER International              | 14        | 0.12%   |
| XMOS                                 | 12        | 0.1%    |
| Tenx Technology                      | 12        | 0.1%    |
| Sennheiser Communications            | 12        | 0.1%    |
| Hewlett-Packard                      | 12        | 0.1%    |
| Dell                                 | 12        | 0.1%    |
| AKAI Professional M.I.               | 11        | 0.09%   |
| Thesycon Systemsoftware & Consulting | 10        | 0.08%   |
| Sony                                 | 9         | 0.08%   |
| DSEA A/S                             | 9         | 0.08%   |
| ATI Technologies                     | 9         | 0.08%   |
| Microsoft                            | 8         | 0.07%   |
| GYROCOM C&C                          | 8         | 0.07%   |
| FiiO Electronics Technology          | 8         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 624       | 4.46%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 606       | 4.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 555       | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 471       | 3.37%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 402       | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 390       | 2.79%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 324       | 2.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 309       | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 303       | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 291       | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 282       | 2.02%   |
| AMD FCH Azalia Controller                                                                         | 275       | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 257       | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 214       | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 207       | 1.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 205       | 1.47%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 203       | 1.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 202       | 1.44%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 188       | 1.34%   |
| Intel 8 Series HD Audio Controller                                                                | 186       | 1.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 184       | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 170       | 1.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 169       | 1.21%   |
| Intel Broadwell-U Audio Controller                                                                | 166       | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 165       | 1.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 165       | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 159       | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 148       | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 124       | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 124       | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 122       | 0.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 121       | 0.86%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 119       | 0.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 117       | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 116       | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 112       | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 105       | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 105       | 0.75%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 105       | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 98        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 940       | 19.64%  |
| SK hynix            | 871       | 18.2%   |
| Corsair             | 578       | 12.08%  |
| Micron Technology   | 497       | 10.38%  |
| Crucial             | 449       | 9.38%   |
| Kingston            | 427       | 8.92%   |
| Unknown             | 413       | 8.63%   |
| Ramaxel Technology  | 73        | 1.53%   |
| A-DATA Technology   | 65        | 1.36%   |
| Elpida              | 60        | 1.25%   |
| Nanya Technology    | 55        | 1.15%   |
| G.Skill             | 51        | 1.07%   |
| Unknown (ABCD)      | 45        | 0.94%   |
| Unknown             | 38        | 0.79%   |
| Team                | 30        | 0.63%   |
| Patriot             | 21        | 0.44%   |
| Hewlett-Packard     | 11        | 0.23%   |
| Transcend           | 10        | 0.21%   |
| Qimonda             | 9         | 0.19%   |
| ASint Technology    | 8         | 0.17%   |
| A Force             | 8         | 0.17%   |
| Timetec             | 7         | 0.15%   |
| Apacer              | 7         | 0.15%   |
| Toshiba             | 6         | 0.13%   |
| GOODRAM             | 6         | 0.13%   |
| KLEVV               | 5         | 0.1%    |
| GSkill              | 4         | 0.08%   |
| Essencore           | 4         | 0.08%   |
| 4ea5                | 4         | 0.08%   |
| Neo Forza           | 3         | 0.06%   |
| Lexar Co Limited    | 3         | 0.06%   |
| Lexar               | 3         | 0.06%   |
| ff                  | 3         | 0.06%   |
| CSX                 | 3         | 0.06%   |
| Axiom               | 3         | 0.06%   |
| V-Color             | 2         | 0.04%   |
| Unknown (F301)      | 2         | 0.04%   |
| Unknown (0x0702)    | 2         | 0.04%   |
| Unknown (0B38)      | 2         | 0.04%   |
| Thermaltake         | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 53        | 1.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 48        | 0.93%   |
| Unknown                                                             | 38        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 37        | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 32        | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 30        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 30        | 0.58%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 29        | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 27        | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 26        | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 26        | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 25        | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 24        | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 23        | 0.45%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 23        | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s               | 22        | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 21        | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 21        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 21        | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 21        | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 19        | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 19        | 0.37%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s             | 18        | 0.35%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s              | 18        | 0.35%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 17        | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 17        | 0.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 17        | 0.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 17        | 0.33%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s               | 17        | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 16        | 0.31%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 16        | 0.31%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 16        | 0.31%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 16        | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 15        | 0.29%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 15        | 0.29%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 15        | 0.29%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 14        | 0.27%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 14        | 0.27%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 14        | 0.27%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 14        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1903      | 45.53%  |
| DDR3    | 1307      | 31.27%  |
| DDR2    | 214       | 5.12%   |
| LPDDR4  | 192       | 4.59%   |
| LPDDR3  | 141       | 3.37%   |
| SDRAM   | 119       | 2.85%   |
| Unknown | 118       | 2.82%   |
| DDR5    | 98        | 2.34%   |
| LPDDR5  | 52        | 1.24%   |
| DDR     | 27        | 0.65%   |
| DRAM    | 9         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2185      | 52.97%  |
| DIMM         | 1541      | 37.36%  |
| Row Of Chips | 335       | 8.12%   |
| Unknown      | 27        | 0.65%   |
| Chip         | 24        | 0.58%   |
| RIMM         | 7         | 0.17%   |
| FB-DIMM      | 6         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 1716      | 37.94%  |
| 4096   | 1188      | 26.27%  |
| 16384  | 710       | 15.7%   |
| 2048   | 540       | 11.94%  |
| 32768  | 173       | 3.82%   |
| 1024   | 170       | 3.76%   |
| 512    | 20        | 0.44%   |
| 256    | 2         | 0.04%   |
| 131072 | 1         | 0.02%   |
| 49152  | 1         | 0.02%   |
| 16     | 1         | 0.02%   |
| 13     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 853       | 18.82%  |
| 3200    | 612       | 13.5%   |
| 2667    | 580       | 12.8%   |
| 2400    | 342       | 7.54%   |
| 1333    | 293       | 6.46%   |
| 2133    | 236       | 5.21%   |
| 3600    | 143       | 3.15%   |
| 667     | 120       | 2.65%   |
| 1867    | 112       | 2.47%   |
| 800     | 102       | 2.25%   |
| 1334    | 100       | 2.21%   |
| 4267    | 77        | 1.7%    |
| 4800    | 66        | 1.46%   |
| Unknown | 64        | 1.41%   |
| 1067    | 56        | 1.24%   |
| 6400    | 55        | 1.21%   |
| 3733    | 46        | 1.01%   |
| 3000    | 46        | 1.01%   |
| 1066    | 43        | 0.95%   |
| 3800    | 37        | 0.82%   |
| 3266    | 36        | 0.79%   |
| 2048    | 34        | 0.75%   |
| 1866    | 34        | 0.75%   |
| 1800    | 33        | 0.73%   |
| 3400    | 32        | 0.71%   |
| 2933    | 30        | 0.66%   |
| 4199    | 28        | 0.62%   |
| 2666    | 25        | 0.55%   |
| 3533    | 23        | 0.51%   |
| 533     | 22        | 0.49%   |
| 4266    | 21        | 0.46%   |
| 2800    | 21        | 0.46%   |
| 400     | 16        | 0.35%   |
| 3066    | 13        | 0.29%   |
| 975     | 12        | 0.26%   |
| 6000    | 10        | 0.22%   |
| 3666    | 10        | 0.22%   |
| 5600    | 9         | 0.2%    |
| 3534    | 8         | 0.18%   |
| 49926   | 7         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 81        | 40.7%   |
| Canon                 | 36        | 18.09%  |
| Samsung Electronics   | 20        | 10.05%  |
| Brother Industries    | 20        | 10.05%  |
| Seiko Epson           | 16        | 8.04%   |
| Prolific Technology   | 5         | 2.51%   |
| Lexmark International | 5         | 2.51%   |
| STMicroelectronics    | 2         | 1.01%   |
| QinHeng Electronics   | 2         | 1.01%   |
| Oki Data              | 2         | 1.01%   |
| Kyocera               | 2         | 1.01%   |
| Dymo-CoStar           | 2         | 1.01%   |
| Seiko Instruments     | 1         | 0.5%    |
| Ricoh                 | 1         | 0.5%    |
| Pantum                | 1         | 0.5%    |
| KODAK                 | 1         | 0.5%    |
| Dell                  | 1         | 0.5%    |
| Apple                 | 1         | 0.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 7         | 3.48%   |
| HP ENVY 4520 series                                       | 6         | 2.99%   |
| Canon PIXMA MG2500 Series                                 | 6         | 2.99%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.49%   |
| HP ENVY 5000 series                                       | 5         | 2.49%   |
| Samsung M2020 Series                                      | 4         | 1.99%   |
| HP DeskJet 2600 series                                    | 4         | 1.99%   |
| Canon PIXMA MG3600 Series                                 | 4         | 1.99%   |
| HP OfficeJet 3830 series                                  | 3         | 1.49%   |
| HP DeskJet 2130 series                                    | 3         | 1.49%   |
| Canon TS3100 series                                       | 3         | 1.49%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1%      |
| Seiko Epson XP-240 Series                                 | 2         | 1%      |
| Seiko Epson XP-200 Series                                 | 2         | 1%      |
| Samsung ML-2250 Series                                    | 2         | 1%      |
| Samsung ML-216x Series Laser Printer                      | 2         | 1%      |
| Samsung C43x Series                                       | 2         | 1%      |
| QinHeng CH340S                                            | 2         | 1%      |
| Oki Data USB Device                                       | 2         | 1%      |
| HP Officejet 4630 series                                  | 2         | 1%      |
| HP LaserJet P2015 series                                  | 2         | 1%      |
| HP LaserJet P1005                                         | 2         | 1%      |
| HP LaserJet 200 colorMFP M276nw                           | 2         | 1%      |
| HP ENVY Photo 6200 series                                 | 2         | 1%      |
| HP Deskjet F2280 series                                   | 2         | 1%      |
| HP DeskJet 3700 series                                    | 2         | 1%      |
| HP DeskJet 3630 series                                    | 2         | 1%      |
| HP DeskJet 2700 series                                    | 2         | 1%      |
| HP Deskjet 2540 series                                    | 2         | 1%      |
| HP Deskjet 1510                                           | 2         | 1%      |
| HP Deskjet 1000 J110 series                               | 2         | 1%      |
| HP Color LaserJet CP1215                                  | 2         | 1%      |
| Canon PIXMA MX920 Series                                  | 2         | 1%      |
| Canon PIXMA MP495                                         | 2         | 1%      |
| Canon MG5700 series                                       | 2         | 1%      |
| Canon iP7200 series                                       | 2         | 1%      |
| Canon CanoScan LiDE 300                                   | 2         | 1%      |
| Brother HL-3140CW series                                  | 2         | 1%      |
| Brother DCP-7055 scanner/printer                          | 2         | 1%      |
| Seiko Instruments SLP-450 Driver                          | 1         | 0.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 30        | 61.22%  |
| Seiko Epson        | 10        | 20.41%  |
| Ultima Electronics | 3         | 6.12%   |
| Hewlett-Packard    | 3         | 6.12%   |
| UMAX               | 1         | 2.04%   |
| Mustek Systems     | 1         | 2.04%   |
| AGFA-Gevaert NV    | 1         | 2.04%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 10.2%   |
| Canon CanoScan LiDE 220                                                               | 5         | 10.2%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 8.16%   |
| Canon CanoScan LIDE 25                                                                | 3         | 6.12%   |
| Canon CanoScan LiDE 200                                                               | 3         | 6.12%   |
| Canon CanoScan LiDE 110                                                               | 3         | 6.12%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 4.08%   |
| Seiko Epson Scanner                                                                   | 2         | 4.08%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 4.08%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 2         | 4.08%   |
| HP ScanJet 5300c/5370c                                                                | 2         | 4.08%   |
| Canon CanoScan LiDE 100                                                               | 2         | 4.08%   |
| UMAX Astra 2200/2200SU                                                                | 1         | 2.04%   |
| Ultima Artec E+ Pro                                                                   | 1         | 2.04%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 1         | 2.04%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 2.04%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 2.04%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 2.04%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 1         | 2.04%   |
| HP Scanjet G2710                                                                      | 1         | 2.04%   |
| Canon CanoScan LiDE 90                                                                | 1         | 2.04%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.04%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 2.04%   |
| Canon CanoScan LiDE 210                                                               | 1         | 2.04%   |
| Canon CanoScan 3000/3000F/3000ex                                                      | 1         | 2.04%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 1         | 2.04%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1015      | 20.99%  |
| Microdia                               | 492       | 10.17%  |
| Realtek Semiconductor                  | 368       | 7.61%   |
| IMC Networks                           | 345       | 7.13%   |
| Logitech                               | 338       | 6.99%   |
| Sunplus Innovation Technology          | 238       | 4.92%   |
| Bison Electronics                      | 206       | 4.26%   |
| Apple                                  | 193       | 3.99%   |
| Quanta                                 | 172       | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 160       | 3.31%   |
| Suyin                                  | 129       | 2.67%   |
| Lite-On Technology                     | 115       | 2.38%   |
| Acer                                   | 96        | 1.99%   |
| Syntek                                 | 95        | 1.96%   |
| Microsoft                              | 90        | 1.86%   |
| Silicon Motion                         | 69        | 1.43%   |
| Alcor Micro                            | 54        | 1.12%   |
| Luxvisions Innotech Limited            | 53        | 1.1%    |
| Samsung Electronics                    | 50        | 1.03%   |
| Ricoh                                  | 48        | 0.99%   |
| Lenovo                                 | 46        | 0.95%   |
| Z-Star Microelectronics                | 37        | 0.77%   |
| ARC International                      | 32        | 0.66%   |
| Generalplus Technology                 | 30        | 0.62%   |
| GEMBIRD                                | 27        | 0.56%   |
| Sonix Technology                       | 24        | 0.5%    |
| MacroSilicon                           | 18        | 0.37%   |
| Creative Technology                    | 18        | 0.37%   |
| ALi                                    | 16        | 0.33%   |
| Razer USA                              | 14        | 0.29%   |
| Primax Electronics                     | 14        | 0.29%   |
| SunplusIT                              | 13        | 0.27%   |
| Aveo Technology                        | 10        | 0.21%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.19%   |
| OmniVision Technologies                | 9         | 0.19%   |
| Huawei Technologies                    | 9         | 0.19%   |
| Hewlett-Packard                        | 9         | 0.19%   |
| Tobii Technology AB                    | 8         | 0.17%   |
| Sunplus Technology                     | 8         | 0.17%   |
| Intel                                  | 8         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 209       | 4.28%   |
| Chicony Integrated Camera                               | 186       | 3.81%   |
| Realtek Integrated_Webcam_HD                            | 140       | 2.87%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 99        | 2.03%   |
| IMC Networks Integrated Camera                          | 99        | 2.03%   |
| Logitech HD Pro Webcam C920                             | 94        | 1.92%   |
| Chicony HD WebCam                                       | 83        | 1.7%    |
| Sunplus Integrated_Webcam_HD                            | 75        | 1.54%   |
| Logitech Webcam C270                                    | 63        | 1.29%   |
| Chicony TOSHIBA Web Camera - HD                         | 59        | 1.21%   |
| Apple FaceTime HD Camera (Built-in)                     | 56        | 1.15%   |
| Apple Built-in iSight                                   | 56        | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 51        | 1.04%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 50        | 1.02%   |
| Bison Integrated Camera                                 | 44        | 0.9%    |
| Microdia Webcam Vitade AF                               | 43        | 0.88%   |
| Syntek Integrated Camera                                | 42        | 0.86%   |
| Microdia Integrated Webcam                              | 42        | 0.86%   |
| Lite-On Integrated Camera                               | 42        | 0.86%   |
| Realtek USB Camera                                      | 40        | 0.82%   |
| Chicony HP TrueVision HD Camera                         | 39        | 0.8%    |
| Microdia USB 2.0 Camera                                 | 38        | 0.78%   |
| Chicony USB2.0 Camera                                   | 36        | 0.74%   |
| Chicony USB 2.0 Camera                                  | 36        | 0.74%   |
| Microsoft LifeCam HD-3000                               | 35        | 0.72%   |
| Chicony HP Truevision HD                                | 35        | 0.72%   |
| Chicony HP HD Camera                                    | 33        | 0.68%   |
| Chicony EasyCamera                                      | 32        | 0.66%   |
| ARC International Camera                                | 32        | 0.66%   |
| Quanta HD User Facing                                   | 31        | 0.63%   |
| Chicony HP Wide Vision HD Camera                        | 31        | 0.63%   |
| Bison BisonCam,NB Pro                                   | 31        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                 | 29        | 0.59%   |
| Acer SunplusIT Integrated Camera                        | 29        | 0.59%   |
| Syntek Lenovo EasyCamera                                | 27        | 0.55%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 27        | 0.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 26        | 0.53%   |
| Alcor Micro USB 2.0 Camera                              | 26        | 0.53%   |
| Acer Integrated Camera                                  | 26        | 0.53%   |
| Chicony VGA Webcam                                      | 25        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 252       | 30.58%  |
| Synaptics                          | 224       | 27.18%  |
| Shenzhen Goodix Technology         | 130       | 15.78%  |
| Upek                               | 57        | 6.92%   |
| AuthenTec                          | 56        | 6.8%    |
| Elan Microelectronics              | 40        | 4.85%   |
| LighTuning Technology              | 39        | 4.73%   |
| STMicroelectronics                 | 18        | 2.18%   |
| Samsung Electronics                | 3         | 0.36%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.24%   |
| HOLTEK                             | 2         | 0.24%   |
| Focal-systems.Corp                 | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 63        | 7.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 55        | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 47        | 5.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 46        | 5.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 42        | 5.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 4.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 33        | 4%      |
| Synaptics UWP WBDI                                                         | 32        | 3.88%   |
| Shenzhen Goodix FingerPrint                                                | 31        | 3.76%   |
| Validity Sensors Synaptics WBDI                                            | 26        | 3.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.31%   |
| Validity Sensors VFS491                                                    | 19        | 2.31%   |
| Synaptics  WBDI                                                            | 19        | 2.31%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 2.18%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 17        | 2.06%   |
| Elan ELAN:Fingerprint                                                      | 17        | 2.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 2.06%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 1.94%   |
| AuthenTec AES2810                                                          | 16        | 1.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 1.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.7%    |
| Elan ELAN:ARM-M4                                                           | 13        | 1.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 11        | 1.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.21%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 1.21%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 10        | 1.21%   |
| Unknown                                                                    | 10        | 1.21%   |
| Synaptics WBDI                                                             | 9         | 1.09%   |
| Synaptics UWP WBDI Device                                                  | 9         | 1.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 1.09%   |
| Synaptics WBDI Device                                                      | 8         | 0.97%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 6         | 0.73%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.73%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 6         | 0.73%   |
| AuthenTec AES1600                                                          | 6         | 0.73%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 202       | 50.75%  |
| Alcor Micro               | 94        | 23.62%  |
| Upek                      | 30        | 7.54%   |
| O2 Micro                  | 27        | 6.78%   |
| Lenovo                    | 25        | 6.28%   |
| Gemalto (was Gemplus)     | 5         | 1.26%   |
| SCM Microsystems          | 3         | 0.75%   |
| OmniKey                   | 3         | 0.75%   |
| Yubico.com                | 1         | 0.25%   |
| Purism, SPC               | 1         | 0.25%   |
| Hewlett-Packard           | 1         | 0.25%   |
| Clay Logic                | 1         | 0.25%   |
| Chicony Electronics       | 1         | 0.25%   |
| Cherry                    | 1         | 0.25%   |
| Bit4id                    | 1         | 0.25%   |
| Aladdin Knowledge Systems | 1         | 0.25%   |
| Advanced Card Systems     | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 89        | 22.36%  |
| Broadcom BCM5880 Secure Applications Processor                               | 75        | 18.84%  |
| Broadcom 5880                                                                | 54        | 13.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 36        | 9.05%   |
| Broadcom 58200                                                               | 35        | 8.79%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 30        | 7.54%   |
| Lenovo Integrated Smart Card Reader                                          | 23        | 5.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 5.53%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.26%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.75%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.5%    |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.5%    |
| Lenovo Smartcard Keyboard                                                    | 2         | 0.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.5%    |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.25%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.25%   |
| Purism, SPC Librem Key                                                       | 1         | 0.25%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.25%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.25%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.25%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.25%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.25%   |
| Bit4id miniLector EVO                                                        | 1         | 0.25%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.25%   |
| Advanced Card Systems ACR1252 CL Reader PICC                                 | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6088      | 70.07%  |
| 1     | 2062      | 23.73%  |
| 2     | 436       | 5.02%   |
| 3     | 73        | 0.84%   |
| 4     | 14        | 0.16%   |
| 5     | 8         | 0.09%   |
| 7     | 4         | 0.05%   |
| 6     | 3         | 0.03%   |
| 8     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 804       | 25.77%  |
| Graphics card            | 683       | 21.89%  |
| Net/wireless             | 479       | 15.35%  |
| Chipcard                 | 361       | 11.57%  |
| Multimedia controller    | 207       | 6.63%   |
| Communication controller | 124       | 3.97%   |
| Sound                    | 74        | 2.37%   |
| Camera                   | 74        | 2.37%   |
| Unassigned class         | 70        | 2.24%   |
| Bluetooth                | 62        | 1.99%   |
| Storage                  | 44        | 1.41%   |
| Net/ethernet             | 33        | 1.06%   |
| Card reader              | 27        | 0.87%   |
| Modem                    | 19        | 0.61%   |
| Network                  | 18        | 0.58%   |
| Storage/raid             | 10        | 0.32%   |
| Flash memory             | 8         | 0.26%   |
| Dvb card                 | 7         | 0.22%   |
| Firewire controller      | 6         | 0.19%   |
| Storage/ide              | 5         | 0.16%   |
| Storage/nvme             | 3         | 0.1%    |
| Unclassified device      | 1         | 0.03%   |
| Tv card                  | 1         | 0.03%   |

