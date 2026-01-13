Ubuntu Studio - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Studio.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Studio/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Studio/Notebook/README.md).

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

Total: 330

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | CM6340                      | Desktop     | [4cac6f6b9c](https://linux-hardware.org/?probe=4cac6f6b9c) | Nov 17, 2025 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [4ab93b5a44](https://linux-hardware.org/?probe=4ab93b5a44) | Oct 25, 2025 |
| Lenovo        | G50-80 80E5                 | Notebook    | [43b34ee3cb](https://linux-hardware.org/?probe=43b34ee3cb) | Oct 25, 2025 |
| Dell          | 0VD5HY A07                  | Desktop     | [6055227e85](https://linux-hardware.org/?probe=6055227e85) | Oct 16, 2025 |
| HP            | 8055                        | Desktop     | [bce6fbfe28](https://linux-hardware.org/?probe=bce6fbfe28) | Oct 15, 2025 |
| HP            | ZBook 15 G3                 | Notebook    | [cbb40cc359](https://linux-hardware.org/?probe=cbb40cc359) | Oct 13, 2025 |
| Acer          | Aspire AG15-42P             | Notebook    | [3322344bca](https://linux-hardware.org/?probe=3322344bca) | Oct 11, 2025 |
| Dell          | 0HY9JP A02                  | Desktop     | [fe08b94fa8](https://linux-hardware.org/?probe=fe08b94fa8) | Oct 08, 2025 |
| Gigabyte      | B650M GAMING PLUS WIFI      | Desktop     | [d4b0a08df4](https://linux-hardware.org/?probe=d4b0a08df4) | Sep 16, 2025 |
| Samsung       | 700Z7C                      | Notebook    | [5d318252c4](https://linux-hardware.org/?probe=5d318252c4) | Sep 07, 2025 |
| Gigabyte      | B650M GAMING PLUS WIFI      | Desktop     | [350bd77ebe](https://linux-hardware.org/?probe=350bd77ebe) | Aug 30, 2025 |
| Dell          | 0XNJ2Y A00                  | Desktop     | [611805cb86](https://linux-hardware.org/?probe=611805cb86) | Aug 23, 2025 |
| Dell          | 0XNJ2Y A00                  | Desktop     | [bbb846e6c3](https://linux-hardware.org/?probe=bbb846e6c3) | Aug 23, 2025 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a2dbe3fbfa](https://linux-hardware.org/?probe=a2dbe3fbfa) | Aug 12, 2025 |
| Alienware     | 16X Aurora AC16251          | Notebook    | [8877f4e027](https://linux-hardware.org/?probe=8877f4e027) | Jul 31, 2025 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [ae2e4435bd](https://linux-hardware.org/?probe=ae2e4435bd) | Jul 16, 2025 |
| MSI           | B550M PRO-VDH               | Desktop     | [0d1acc43ef](https://linux-hardware.org/?probe=0d1acc43ef) | Jul 02, 2025 |
| Notebook      | N8xEJEK                     | Notebook    | [b6e2a0deef](https://linux-hardware.org/?probe=b6e2a0deef) | Jun 05, 2025 |
| Lenovo        | Legion 9 16IRX9 83G0        | Notebook    | [fea13dc137](https://linux-hardware.org/?probe=fea13dc137) | May 23, 2025 |
| Acer          | Swift SFG14-42              | Notebook    | [ad709b8e5f](https://linux-hardware.org/?probe=ad709b8e5f) | May 18, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [e63e22bb2f](https://linux-hardware.org/?probe=e63e22bb2f) | May 18, 2025 |
| Gigabyte      | AERO 17 XB                  | Notebook    | [dd8b3e1d0c](https://linux-hardware.org/?probe=dd8b3e1d0c) | Mar 25, 2025 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [84ec19b5d9](https://linux-hardware.org/?probe=84ec19b5d9) | Mar 22, 2025 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [7488d92ad7](https://linux-hardware.org/?probe=7488d92ad7) | Mar 03, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [5b5fe01c8c](https://linux-hardware.org/?probe=5b5fe01c8c) | Feb 23, 2025 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cf2814f7bc](https://linux-hardware.org/?probe=cf2814f7bc) | Feb 19, 2025 |
| HP            | 212B                        | Desktop     | [6ba5de0521](https://linux-hardware.org/?probe=6ba5de0521) | Feb 15, 2025 |
| HP            | 212B                        | Desktop     | [5145984b7f](https://linux-hardware.org/?probe=5145984b7f) | Feb 15, 2025 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [41694d55b3](https://linux-hardware.org/?probe=41694d55b3) | Feb 03, 2025 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [5fa7e8de2d](https://linux-hardware.org/?probe=5fa7e8de2d) | Feb 03, 2025 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [8d90bb7b53](https://linux-hardware.org/?probe=8d90bb7b53) | Feb 03, 2025 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [79b1b7133a](https://linux-hardware.org/?probe=79b1b7133a) | Jan 30, 2025 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [52ca7b8bbd](https://linux-hardware.org/?probe=52ca7b8bbd) | Jan 30, 2025 |
| Lenovo        | 330E SDK0K17763 WIN 1801... | Mini pc     | [21d00482da](https://linux-hardware.org/?probe=21d00482da) | Jan 30, 2025 |
| Lenovo        | 3728 SDK0J40709 WIN 3259... | Desktop     | [04c0c560d4](https://linux-hardware.org/?probe=04c0c560d4) | Jan 03, 2025 |
| MSI           | Prestige 13 AI+ Evo A2VM... | Notebook    | [e0ef8014cc](https://linux-hardware.org/?probe=e0ef8014cc) | Dec 31, 2024 |
| ASUSTek       | N750JV                      | Notebook    | [39dd282ac2](https://linux-hardware.org/?probe=39dd282ac2) | Dec 26, 2024 |
| Unknown       | Unknown                     | Notebook    | [ee3d394ad4](https://linux-hardware.org/?probe=ee3d394ad4) | Dec 22, 2024 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [0a76d54f2a](https://linux-hardware.org/?probe=0a76d54f2a) | Dec 11, 2024 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [27824c7505](https://linux-hardware.org/?probe=27824c7505) | Dec 09, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [9e14504376](https://linux-hardware.org/?probe=9e14504376) | Dec 02, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [0dc0dd7a62](https://linux-hardware.org/?probe=0dc0dd7a62) | Nov 20, 2024 |
| MSI           | Z370 PC PRO                 | Desktop     | [518166326c](https://linux-hardware.org/?probe=518166326c) | Nov 11, 2024 |
| ASRock        | H97M Pro4                   | Desktop     | [c694317e1f](https://linux-hardware.org/?probe=c694317e1f) | Nov 08, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7ae1cb1ad0](https://linux-hardware.org/?probe=7ae1cb1ad0) | Nov 01, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [a1c6d79081](https://linux-hardware.org/?probe=a1c6d79081) | Oct 23, 2024 |
| Sony          | VPCCB3C5E                   | Notebook    | [32c8a0fd43](https://linux-hardware.org/?probe=32c8a0fd43) | Oct 23, 2024 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [1bf6907ed6](https://linux-hardware.org/?probe=1bf6907ed6) | Oct 20, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [8132169207](https://linux-hardware.org/?probe=8132169207) | Oct 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [d875e5f8df](https://linux-hardware.org/?probe=d875e5f8df) | Oct 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ffd8af5438](https://linux-hardware.org/?probe=ffd8af5438) | Sep 25, 2024 |
| Lenovo        | ThinkCentre M58p 7220RY8    | Desktop     | [9a160a771d](https://linux-hardware.org/?probe=9a160a771d) | Sep 16, 2024 |
| Alienware     | 01NYPT A00                  | Desktop     | [953351e395](https://linux-hardware.org/?probe=953351e395) | Aug 31, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [ce7cf8209e](https://linux-hardware.org/?probe=ce7cf8209e) | Aug 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [7d197b82ba](https://linux-hardware.org/?probe=7d197b82ba) | Aug 29, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b6ee09c245](https://linux-hardware.org/?probe=b6ee09c245) | Aug 14, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [53a28ccde0](https://linux-hardware.org/?probe=53a28ccde0) | Aug 14, 2024 |
| Lenovo        | ThinkPad T450s 20BWS0X00... | Notebook    | [a6f146c7b7](https://linux-hardware.org/?probe=a6f146c7b7) | Aug 09, 2024 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [a1636d9c36](https://linux-hardware.org/?probe=a1636d9c36) | Aug 01, 2024 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [337a3488ce](https://linux-hardware.org/?probe=337a3488ce) | Aug 01, 2024 |
| HP            | 2B16                        | Desktop     | [f8836660b7](https://linux-hardware.org/?probe=f8836660b7) | Jul 24, 2024 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [0b60161050](https://linux-hardware.org/?probe=0b60161050) | Jul 24, 2024 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [93e318f098](https://linux-hardware.org/?probe=93e318f098) | Jul 24, 2024 |
| Dell          | Precision 5520              | Notebook    | [d7b6062639](https://linux-hardware.org/?probe=d7b6062639) | Jul 21, 2024 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [e3507bd66f](https://linux-hardware.org/?probe=e3507bd66f) | Jul 08, 2024 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [34e04923f3](https://linux-hardware.org/?probe=34e04923f3) | Jun 28, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [54b86a5399](https://linux-hardware.org/?probe=54b86a5399) | Jun 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [a3ffc85576](https://linux-hardware.org/?probe=a3ffc85576) | Jun 21, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [0bf1e098c0](https://linux-hardware.org/?probe=0bf1e098c0) | Jun 19, 2024 |
| Lenovo        | IdeaPad Slim 3 16IAH8 83... | Notebook    | [ae3b8db2e7](https://linux-hardware.org/?probe=ae3b8db2e7) | Jun 18, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [eec5a148c0](https://linux-hardware.org/?probe=eec5a148c0) | Jun 14, 2024 |
| Lenovo        | ThinkPad T420 4236A38       | Notebook    | [fb0d42ccdd](https://linux-hardware.org/?probe=fb0d42ccdd) | Jun 13, 2024 |
| Dell          | Latitude 3450               | Notebook    | [c7b7155c10](https://linux-hardware.org/?probe=c7b7155c10) | Jun 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [1d8af97b78](https://linux-hardware.org/?probe=1d8af97b78) | May 15, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [87a9fcc5ab](https://linux-hardware.org/?probe=87a9fcc5ab) | May 12, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [134f7ad848](https://linux-hardware.org/?probe=134f7ad848) | May 10, 2024 |
| Acer          | Nitro AN16-41               | Notebook    | [4ccd0953dd](https://linux-hardware.org/?probe=4ccd0953dd) | May 09, 2024 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [a62c895461](https://linux-hardware.org/?probe=a62c895461) | Apr 26, 2024 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [25245adc43](https://linux-hardware.org/?probe=25245adc43) | Apr 26, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1572659f68](https://linux-hardware.org/?probe=1572659f68) | Apr 24, 2024 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [0d6a3363b8](https://linux-hardware.org/?probe=0d6a3363b8) | Apr 15, 2024 |
| ASUSTek       | P5WDG2 WS Pro               | Desktop     | [c370aff195](https://linux-hardware.org/?probe=c370aff195) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [b3cf1a2d4e](https://linux-hardware.org/?probe=b3cf1a2d4e) | Apr 05, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [ddd85b18e6](https://linux-hardware.org/?probe=ddd85b18e6) | Apr 04, 2024 |
| HP            | Pavilion 15                 | Notebook    | [520fd1241e](https://linux-hardware.org/?probe=520fd1241e) | Mar 14, 2024 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | Notebook    | [cf518d2630](https://linux-hardware.org/?probe=cf518d2630) | Mar 10, 2024 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [bf844ef78f](https://linux-hardware.org/?probe=bf844ef78f) | Mar 09, 2024 |
| Lenovo        | ThinkPad L540 20AV004VGE    | Notebook    | [05d6a4d686](https://linux-hardware.org/?probe=05d6a4d686) | Feb 03, 2024 |
| Dell          | Latitude E6420              | Notebook    | [f4dcc8c239](https://linux-hardware.org/?probe=f4dcc8c239) | Jan 26, 2024 |
| Acer          | Aspire A317-53              | Notebook    | [efa0303d01](https://linux-hardware.org/?probe=efa0303d01) | Jan 24, 2024 |
| Dell          | Inspiron 3482               | Notebook    | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | Notebook    | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [1265cfb294](https://linux-hardware.org/?probe=1265cfb294) | Dec 21, 2023 |
| ASUSTek       | P5G41-M                     | Desktop     | [cbab9e248d](https://linux-hardware.org/?probe=cbab9e248d) | Dec 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [6067c56124](https://linux-hardware.org/?probe=6067c56124) | Dec 19, 2023 |
| Intel         | Unknown                     | Desktop     | [3ae9554945](https://linux-hardware.org/?probe=3ae9554945) | Dec 05, 2023 |
| Dell          | 0PRR48 A01                  | Desktop     | [0942eb512e](https://linux-hardware.org/?probe=0942eb512e) | Nov 30, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [51b0a49d02](https://linux-hardware.org/?probe=51b0a49d02) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
| Dell          | System XPS L502X            | Notebook    | [33f54ee5dc](https://linux-hardware.org/?probe=33f54ee5dc) | Nov 16, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| Lenovo        | ZIWB2                       | Notebook    | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Gigabyte      | H270-HD3P-CF                | Desktop     | [43fedd61b1](https://linux-hardware.org/?probe=43fedd61b1) | Oct 23, 2023 |
| Gigabyte      | H270-HD3P-CF                | Desktop     | [22baba8799](https://linux-hardware.org/?probe=22baba8799) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480 20L50101US    | Notebook    | [c6913c1b75](https://linux-hardware.org/?probe=c6913c1b75) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [188b107eb5](https://linux-hardware.org/?probe=188b107eb5) | Oct 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e1caa679f](https://linux-hardware.org/?probe=7e1caa679f) | Sep 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [5a57428971](https://linux-hardware.org/?probe=5a57428971) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bab5438645](https://linux-hardware.org/?probe=bab5438645) | Sep 22, 2023 |
| HP            | 829A                        | Mini pc     | [52aac4ac46](https://linux-hardware.org/?probe=52aac4ac46) | Sep 16, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [794f6d999a](https://linux-hardware.org/?probe=794f6d999a) | Sep 12, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [69bf752a4a](https://linux-hardware.org/?probe=69bf752a4a) | Sep 06, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [6ffb2379fa](https://linux-hardware.org/?probe=6ffb2379fa) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ab3c1508f9](https://linux-hardware.org/?probe=ab3c1508f9) | Aug 30, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [17136ed242](https://linux-hardware.org/?probe=17136ed242) | Aug 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fcfb9cd970](https://linux-hardware.org/?probe=fcfb9cd970) | Aug 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c3490914f6](https://linux-hardware.org/?probe=c3490914f6) | Aug 26, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [499c14b0f7](https://linux-hardware.org/?probe=499c14b0f7) | Aug 26, 2023 |
| Toshiba       | Satellite A505              | Notebook    | [a7b1465809](https://linux-hardware.org/?probe=a7b1465809) | Aug 25, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [191aa2a04f](https://linux-hardware.org/?probe=191aa2a04f) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | Notebook    | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [50ee937fb2](https://linux-hardware.org/?probe=50ee937fb2) | Aug 02, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [c04f6d6467](https://linux-hardware.org/?probe=c04f6d6467) | Aug 01, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [d3718d1a8d](https://linux-hardware.org/?probe=d3718d1a8d) | Jul 16, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [60e43d39b2](https://linux-hardware.org/?probe=60e43d39b2) | Jul 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [97ebfed554](https://linux-hardware.org/?probe=97ebfed554) | Jul 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [57d511fdb3](https://linux-hardware.org/?probe=57d511fdb3) | Jun 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV03     | Notebook    | [c2a4d4d2c0](https://linux-hardware.org/?probe=c2a4d4d2c0) | Jun 17, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5a1b8d9fd3](https://linux-hardware.org/?probe=5a1b8d9fd3) | Jun 04, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [33aa60eaa2](https://linux-hardware.org/?probe=33aa60eaa2) | May 22, 2023 |
| Lenovo        | ThinkPad L460 20FVS3JK00    | Notebook    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [bffa46ef83](https://linux-hardware.org/?probe=bffa46ef83) | May 07, 2023 |
| ASUSTek       | M4A785-M                    | Desktop     | [cbf9d11153](https://linux-hardware.org/?probe=cbf9d11153) | May 07, 2023 |
| ECS           | H410-SF110                  | Desktop     | [5e5011bdd3](https://linux-hardware.org/?probe=5e5011bdd3) | May 07, 2023 |
| HP            | 1495                        | Desktop     | [d6e629523f](https://linux-hardware.org/?probe=d6e629523f) | May 01, 2023 |
| DEPO Compu... | MS-7846                     | Desktop     | [bf72733735](https://linux-hardware.org/?probe=bf72733735) | Apr 13, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [2743830739](https://linux-hardware.org/?probe=2743830739) | Apr 11, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6347cdcf9c](https://linux-hardware.org/?probe=6347cdcf9c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [3ce456f3c8](https://linux-hardware.org/?probe=3ce456f3c8) | Mar 25, 2023 |
| Fujitsu       | D3162-B1 S26361-D3162-B1    | Desktop     | [a2c287936d](https://linux-hardware.org/?probe=a2c287936d) | Mar 24, 2023 |
| Lenovo        | ThinkPad X250 20CL001LMB    | Notebook    | [d78880e600](https://linux-hardware.org/?probe=d78880e600) | Mar 17, 2023 |
| HP            | Pavilion dv8                | Notebook    | [105a616a39](https://linux-hardware.org/?probe=105a616a39) | Mar 14, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [8553f4abea](https://linux-hardware.org/?probe=8553f4abea) | Mar 13, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [7d9e6e46db](https://linux-hardware.org/?probe=7d9e6e46db) | Mar 13, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [257b3941af](https://linux-hardware.org/?probe=257b3941af) | Mar 10, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | TP300UA                     | Notebook    | [22ff7f5827](https://linux-hardware.org/?probe=22ff7f5827) | Feb 20, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| Dell          | Latitude 5511               | Notebook    | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [ffc97bf3de](https://linux-hardware.org/?probe=ffc97bf3de) | Feb 06, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c63c663181](https://linux-hardware.org/?probe=c63c663181) | Jan 30, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [bb321263f8](https://linux-hardware.org/?probe=bb321263f8) | Jan 24, 2023 |
| HP            | 1497                        | Desktop     | [5f7e021023](https://linux-hardware.org/?probe=5f7e021023) | Jan 22, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [db3b391bd0](https://linux-hardware.org/?probe=db3b391bd0) | Jan 20, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [3140672f28](https://linux-hardware.org/?probe=3140672f28) | Jan 10, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [3d8320e362](https://linux-hardware.org/?probe=3d8320e362) | Dec 25, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [f36c085389](https://linux-hardware.org/?probe=f36c085389) | Dec 25, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [9d689be2ab](https://linux-hardware.org/?probe=9d689be2ab) | Dec 11, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [a888eb38b3](https://linux-hardware.org/?probe=a888eb38b3) | Dec 01, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [78defd6c12](https://linux-hardware.org/?probe=78defd6c12) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [b76898d624](https://linux-hardware.org/?probe=b76898d624) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [5147db88ea](https://linux-hardware.org/?probe=5147db88ea) | Nov 14, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1d490bb7d1](https://linux-hardware.org/?probe=1d490bb7d1) | Nov 11, 2022 |
| HP            | 09F8h                       | Desktop     | [f1107e91f2](https://linux-hardware.org/?probe=f1107e91f2) | Nov 01, 2022 |
| MSI           | Z77A-G45 Thunderbolt        | Desktop     | [fa189cf50b](https://linux-hardware.org/?probe=fa189cf50b) | Oct 30, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [55771f0c33](https://linux-hardware.org/?probe=55771f0c33) | Oct 18, 2022 |
| Lenovo        | ThinkPad X230 2333A86       | Notebook    | [7e0028c2fa](https://linux-hardware.org/?probe=7e0028c2fa) | Oct 18, 2022 |
| Gigabyte      | X79S-UP5                    | Desktop     | [62f59af32c](https://linux-hardware.org/?probe=62f59af32c) | Oct 15, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5bfc8f0a7d](https://linux-hardware.org/?probe=5bfc8f0a7d) | Sep 30, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [2dc3febd4d](https://linux-hardware.org/?probe=2dc3febd4d) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [5b39dcf114](https://linux-hardware.org/?probe=5b39dcf114) | Sep 19, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [b1d97f239e](https://linux-hardware.org/?probe=b1d97f239e) | Sep 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [de37b9cf96](https://linux-hardware.org/?probe=de37b9cf96) | Sep 13, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [d6d8f577e0](https://linux-hardware.org/?probe=d6d8f577e0) | Sep 12, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [07428c96e1](https://linux-hardware.org/?probe=07428c96e1) | Sep 11, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [c129f7c9b1](https://linux-hardware.org/?probe=c129f7c9b1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a23b4a8cd4](https://linux-hardware.org/?probe=a23b4a8cd4) | Aug 27, 2022 |
| HP            | 18E7                        | Desktop     | [698520133f](https://linux-hardware.org/?probe=698520133f) | Aug 22, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [5cbe471be8](https://linux-hardware.org/?probe=5cbe471be8) | Aug 19, 2022 |
| Lenovo        | 36F4 SDK0J40697 WIN 3305... | All in one  | [4b585d8c34](https://linux-hardware.org/?probe=4b585d8c34) | Aug 18, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [45491460bc](https://linux-hardware.org/?probe=45491460bc) | Aug 12, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| HP            | G62                         | Notebook    | [3c4aab40ae](https://linux-hardware.org/?probe=3c4aab40ae) | Jul 20, 2022 |
| AZW           | SER V01                     | Mini pc     | [0bf81855b6](https://linux-hardware.org/?probe=0bf81855b6) | Jul 18, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [25e69108df](https://linux-hardware.org/?probe=25e69108df) | Jul 03, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [e45e0b0c90](https://linux-hardware.org/?probe=e45e0b0c90) | Jun 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [4ed102b3fa](https://linux-hardware.org/?probe=4ed102b3fa) | Jun 15, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6023bfb4cc](https://linux-hardware.org/?probe=6023bfb4cc) | Jun 09, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [a4aa661ab1](https://linux-hardware.org/?probe=a4aa661ab1) | Jun 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [bcd22d5d0e](https://linux-hardware.org/?probe=bcd22d5d0e) | May 20, 2022 |
| Getac         | S400G3                      | Notebook    | [56cc8b4c1a](https://linux-hardware.org/?probe=56cc8b4c1a) | May 16, 2022 |
| Dell          | 0RW203                      | Desktop     | [fc3e449b4d](https://linux-hardware.org/?probe=fc3e449b4d) | May 09, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b2bddaf1b1](https://linux-hardware.org/?probe=b2bddaf1b1) | Apr 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [02b0c35fed](https://linux-hardware.org/?probe=02b0c35fed) | Apr 27, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [cebf5b3135](https://linux-hardware.org/?probe=cebf5b3135) | Apr 17, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3c048f588e](https://linux-hardware.org/?probe=3c048f588e) | Apr 12, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [aff1557d72](https://linux-hardware.org/?probe=aff1557d72) | Apr 11, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [a87f9de14e](https://linux-hardware.org/?probe=a87f9de14e) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | Desktop     | [01ad19348a](https://linux-hardware.org/?probe=01ad19348a) | Mar 20, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [3f8fe40793](https://linux-hardware.org/?probe=3f8fe40793) | Mar 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [4206238fce](https://linux-hardware.org/?probe=4206238fce) | Mar 01, 2022 |
| HP            | Sona                        | Notebook    | [4fcab0b3b7](https://linux-hardware.org/?probe=4fcab0b3b7) | Feb 24, 2022 |
| HP            | Sona                        | Notebook    | [d0b3189e0f](https://linux-hardware.org/?probe=d0b3189e0f) | Feb 24, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [82f706b315](https://linux-hardware.org/?probe=82f706b315) | Feb 11, 2022 |
| Google        | Nami                        | Notebook    | [5f1ba9ab72](https://linux-hardware.org/?probe=5f1ba9ab72) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [feb1c1d6a2](https://linux-hardware.org/?probe=feb1c1d6a2) | Feb 10, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5a1bf3cb9e](https://linux-hardware.org/?probe=5a1bf3cb9e) | Feb 04, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [fe9fed2a45](https://linux-hardware.org/?probe=fe9fed2a45) | Jan 26, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [5ccce1fb71](https://linux-hardware.org/?probe=5ccce1fb71) | Jan 21, 2022 |
| Lenovo        | ThinkPad T520 4243K86       | Notebook    | [91adda5a0e](https://linux-hardware.org/?probe=91adda5a0e) | Jan 21, 2022 |
| Clevo         | W35_37ET                    | Notebook    | [f8858fd0c3](https://linux-hardware.org/?probe=f8858fd0c3) | Jan 20, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [b479441fe2](https://linux-hardware.org/?probe=b479441fe2) | Jan 15, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [7f94c66f93](https://linux-hardware.org/?probe=7f94c66f93) | Jan 09, 2022 |
| AZW           | GK35                        | Desktop     | [ed1be3dbf7](https://linux-hardware.org/?probe=ed1be3dbf7) | Jan 07, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [e071d4f83a](https://linux-hardware.org/?probe=e071d4f83a) | Jan 02, 2022 |
| ASUSTek       | ROG STRIX Z490-I GAMING     | Desktop     | [4c55363bc2](https://linux-hardware.org/?probe=4c55363bc2) | Dec 04, 2021 |
| Toshiba       | Satellite C855              | Notebook    | [7914ab9929](https://linux-hardware.org/?probe=7914ab9929) | Dec 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [22033e7185](https://linux-hardware.org/?probe=22033e7185) | Oct 05, 2021 |
| Toshiba       | Satellite L755D             | Notebook    | [aca989dcc4](https://linux-hardware.org/?probe=aca989dcc4) | Sep 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| ASUSTek       | UX305FA                     | Notebook    | [91b4275b9b](https://linux-hardware.org/?probe=91b4275b9b) | Aug 25, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [35e6393ea4](https://linux-hardware.org/?probe=35e6393ea4) | Aug 01, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [b62225a801](https://linux-hardware.org/?probe=b62225a801) | Jul 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [9d8c462df3](https://linux-hardware.org/?probe=9d8c462df3) | Jul 20, 2021 |
| HP            | Pavilion dv6                | Notebook    | [089a39fe70](https://linux-hardware.org/?probe=089a39fe70) | Jul 07, 2021 |
| Acer          | Aspire U5-710               | All in one  | [c2ff1a33ee](https://linux-hardware.org/?probe=c2ff1a33ee) | Jun 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [64c8a86c5b](https://linux-hardware.org/?probe=64c8a86c5b) | Jun 19, 2021 |
| HP            | 1495                        | Desktop     | [56251d62e1](https://linux-hardware.org/?probe=56251d62e1) | Jun 17, 2021 |
| Intel Clie... | LAPBC510                    | Notebook    | [06421d0916](https://linux-hardware.org/?probe=06421d0916) | Jun 15, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [f88f0c3680](https://linux-hardware.org/?probe=f88f0c3680) | Jun 14, 2021 |
| Pegatron      | NARRA3                      | Desktop     | [38ac9a9ea6](https://linux-hardware.org/?probe=38ac9a9ea6) | May 18, 2021 |
| Dell          | 0P4T42 A00                  | All in one  | [80ca4b15a5](https://linux-hardware.org/?probe=80ca4b15a5) | May 16, 2021 |
| HP            | 158A                        | Desktop     | [2fac0fa486](https://linux-hardware.org/?probe=2fac0fa486) | May 01, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ef264215af](https://linux-hardware.org/?probe=ef264215af) | Apr 24, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [04a4129216](https://linux-hardware.org/?probe=04a4129216) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [749002b5ad](https://linux-hardware.org/?probe=749002b5ad) | Apr 20, 2021 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [aec24cb317](https://linux-hardware.org/?probe=aec24cb317) | Apr 20, 2021 |
| Dell          | Precision M4500             | Notebook    | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | P8P67 EVO                   | Desktop     | [5e98e0ae38](https://linux-hardware.org/?probe=5e98e0ae38) | Apr 14, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [43cb3af3a5](https://linux-hardware.org/?probe=43cb3af3a5) | Apr 12, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [9414f40cf2](https://linux-hardware.org/?probe=9414f40cf2) | Apr 03, 2021 |
| Fujitsu       | D3654-C1 S26361-D3654-C1    | Desktop     | [4cd56bcfa1](https://linux-hardware.org/?probe=4cd56bcfa1) | Apr 02, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [5ff7a11404](https://linux-hardware.org/?probe=5ff7a11404) | Mar 28, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7b7a266de6](https://linux-hardware.org/?probe=7b7a266de6) | Mar 22, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [d9f29b65da](https://linux-hardware.org/?probe=d9f29b65da) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [369f0a0cdb](https://linux-hardware.org/?probe=369f0a0cdb) | Mar 12, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e4fb438978](https://linux-hardware.org/?probe=e4fb438978) | Feb 24, 2021 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [19bc1494c6](https://linux-hardware.org/?probe=19bc1494c6) | Feb 21, 2021 |
| Sony          | VGN-NS31M_W                 | Notebook    | [dcc1660569](https://linux-hardware.org/?probe=dcc1660569) | Feb 17, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [387cfadf45](https://linux-hardware.org/?probe=387cfadf45) | Feb 06, 2021 |
| IBM           | 8188PPV                     | Desktop     | [6d4f098a65](https://linux-hardware.org/?probe=6d4f098a65) | Jan 31, 2021 |
| Dell          | 02YRK5 A01                  | Desktop     | [6a2d5cd538](https://linux-hardware.org/?probe=6a2d5cd538) | Jan 30, 2021 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [c9af16a580](https://linux-hardware.org/?probe=c9af16a580) | Jan 24, 2021 |
| Dell          | 0D28YY A03                  | Desktop     | [e74dbb590d](https://linux-hardware.org/?probe=e74dbb590d) | Jan 21, 2021 |
| Intel         | DQ965GF AAD41676-402        | Desktop     | [2e9a342427](https://linux-hardware.org/?probe=2e9a342427) | Jan 13, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [13edd89415](https://linux-hardware.org/?probe=13edd89415) | Jan 11, 2021 |
| ASUSTek       | U56E                        | Notebook    | [eba46128ee](https://linux-hardware.org/?probe=eba46128ee) | Jan 04, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [a8ebb648f7](https://linux-hardware.org/?probe=a8ebb648f7) | Jan 03, 2021 |
| Acer          | Aspire X3400                | Desktop     | [da9e0d0bb4](https://linux-hardware.org/?probe=da9e0d0bb4) | Jan 02, 2021 |
| Packard Be... | WMCP78M                     | Desktop     | [6a6c4577d4](https://linux-hardware.org/?probe=6a6c4577d4) | Dec 31, 2020 |
| HP            | 1850                        | Desktop     | [b86e749745](https://linux-hardware.org/?probe=b86e749745) | Dec 30, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4332bc902d](https://linux-hardware.org/?probe=4332bc902d) | Dec 21, 2020 |
| Dell          | 0J3C2F A00                  | Desktop     | [b2e5d9d8b0](https://linux-hardware.org/?probe=b2e5d9d8b0) | Dec 09, 2020 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [2291f0c106](https://linux-hardware.org/?probe=2291f0c106) | Dec 08, 2020 |
| Dell          | 04YP6J A02                  | Desktop     | [6c15ba650c](https://linux-hardware.org/?probe=6c15ba650c) | Dec 06, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505443aeb1](https://linux-hardware.org/?probe=505443aeb1) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [73e35c07b8](https://linux-hardware.org/?probe=73e35c07b8) | Dec 02, 2020 |
| MSI           | Z270 MPOWER GAMING TITAN... | Desktop     | [3b24badd98](https://linux-hardware.org/?probe=3b24badd98) | Dec 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [1b1044cc21](https://linux-hardware.org/?probe=1b1044cc21) | Nov 28, 2020 |
| Medion        | B360H4-EM V1.0              | Desktop     | [1915ad5c58](https://linux-hardware.org/?probe=1915ad5c58) | Nov 15, 2020 |
| Dell          | Latitude E6530              | Notebook    | [3d606b3078](https://linux-hardware.org/?probe=3d606b3078) | Nov 09, 2020 |
| ASUSTek       | CS-B                        | Desktop     | [4e0f76c433](https://linux-hardware.org/?probe=4e0f76c433) | Nov 02, 2020 |
| Dell          | Latitude E7250              | Notebook    | [d5e2f8b706](https://linux-hardware.org/?probe=d5e2f8b706) | Nov 01, 2020 |
| Acer          | ASPIRE1420P_MSFT            | Notebook    | [5185b46abc](https://linux-hardware.org/?probe=5185b46abc) | Oct 31, 2020 |
| HP            | 3047h                       | Desktop     | [a23efe0e20](https://linux-hardware.org/?probe=a23efe0e20) | Oct 26, 2020 |
| ASRock        | H55M/USB3                   | Desktop     | [74202436b2](https://linux-hardware.org/?probe=74202436b2) | Oct 18, 2020 |
| Dell          | 0F8098                      | Desktop     | [a2217fa6a7](https://linux-hardware.org/?probe=a2217fa6a7) | Sep 25, 2020 |
| Dell          | 0F8098                      | Desktop     | [2c747bcc47](https://linux-hardware.org/?probe=2c747bcc47) | Sep 25, 2020 |
| Avell High... | Avell G1555 MUV / A62 MU... | Notebook    | [c2994bb093](https://linux-hardware.org/?probe=c2994bb093) | Sep 18, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [e00620b124](https://linux-hardware.org/?probe=e00620b124) | Sep 06, 2020 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [57d3d832f5](https://linux-hardware.org/?probe=57d3d832f5) | Sep 04, 2020 |
| Dell          | Latitude E4300              | Notebook    | [3e0fb2e03f](https://linux-hardware.org/?probe=3e0fb2e03f) | Sep 03, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [03bcf3b1fd](https://linux-hardware.org/?probe=03bcf3b1fd) | Sep 02, 2020 |
| HP            | Compaq 8510p                | Notebook    | [2ea87d13f0](https://linux-hardware.org/?probe=2ea87d13f0) | Aug 26, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [d4f13322ac](https://linux-hardware.org/?probe=d4f13322ac) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [d2851c54e9](https://linux-hardware.org/?probe=d2851c54e9) | Aug 18, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [92e2a05f2d](https://linux-hardware.org/?probe=92e2a05f2d) | Aug 13, 2020 |
| ASUSTek       | 1001P                       | Notebook    | [0ae5a1aab2](https://linux-hardware.org/?probe=0ae5a1aab2) | Aug 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [96ba8dc0e8](https://linux-hardware.org/?probe=96ba8dc0e8) | Jul 31, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [3162979c2e](https://linux-hardware.org/?probe=3162979c2e) | Jul 24, 2020 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [d21c458a4f](https://linux-hardware.org/?probe=d21c458a4f) | Jul 24, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [957ec007de](https://linux-hardware.org/?probe=957ec007de) | Jun 27, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [cb240b6e7e](https://linux-hardware.org/?probe=cb240b6e7e) | Jun 05, 2020 |
| HP            | Notebook                    | Notebook    | [e406d5cf9e](https://linux-hardware.org/?probe=e406d5cf9e) | Jun 02, 2020 |
| Apple         | Mac-F2268DAE                | All in one  | [8271aeba33](https://linux-hardware.org/?probe=8271aeba33) | Mar 19, 2020 |
| Lenovo        | ThinkPad W530 2447IG0       | Notebook    | [f7125d9a17](https://linux-hardware.org/?probe=f7125d9a17) | Mar 19, 2020 |
| Lenovo        | ThinkPad X230 23245S1       | Notebook    | [047f29b7c7](https://linux-hardware.org/?probe=047f29b7c7) | Nov 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ebbf8cd8d4](https://linux-hardware.org/?probe=ebbf8cd8d4) | May 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Studio 20.04 | 87        | 31.07%  |
| Ubuntu Studio 22.04 | 74        | 26.43%  |
| Ubuntu Studio 24.04 | 45        | 16.07%  |
| Ubuntu Studio 23.04 | 13        | 4.64%   |
| Ubuntu Studio 20.10 | 13        | 4.64%   |
| Ubuntu Studio 22.10 | 10        | 3.57%   |
| Ubuntu Studio 23.10 | 9         | 3.21%   |
| Ubuntu Studio 25.04 | 7         | 2.5%    |
| Ubuntu Studio 21.10 | 7         | 2.5%    |
| Ubuntu Studio 21.04 | 5         | 1.79%   |
| Ubuntu Studio 24.10 | 4         | 1.43%   |
| Ubuntu Studio 18.04 | 3         | 1.07%   |
| Ubuntu Studio 19.10 | 2         | 0.71%   |
| Ubuntu Studio 16.04 | 1         | 0.36%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Studio | 277       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 6.8.0-47-lowlatency    | 7         | 2.43%   |
| 6.8.0-31-lowlatency    | 6         | 2.08%   |
| 6.2.0-1009-lowlatency  | 6         | 2.08%   |
| 5.15.0-56-lowlatency   | 5         | 1.74%   |
| 5.15.0-46-lowlatency   | 5         | 1.74%   |
| 5.13.0-28-lowlatency   | 5         | 1.74%   |
| 6.8.0-85-lowlatency    | 4         | 1.39%   |
| 6.8.0-52-lowlatency    | 4         | 1.39%   |
| 6.2.0-1003-lowlatency  | 4         | 1.39%   |
| 5.4.0-52-lowlatency    | 4         | 1.39%   |
| 5.4.0-42-lowlatency    | 4         | 1.39%   |
| 6.8.0-41-lowlatency    | 3         | 1.04%   |
| 6.5.0-28-lowlatency    | 3         | 1.04%   |
| 6.5.0-27-lowlatency    | 3         | 1.04%   |
| 6.2.0-1012-lowlatency  | 3         | 1.04%   |
| 5.8.0-55-lowlatency    | 3         | 1.04%   |
| 5.8.0-50-lowlatency    | 3         | 1.04%   |
| 5.8.0-44-lowlatency    | 3         | 1.04%   |
| 5.8.0-25-lowlatency    | 3         | 1.04%   |
| 5.4.0-65-lowlatency    | 3         | 1.04%   |
| 5.4.0-26-lowlatency    | 3         | 1.04%   |
| 5.19.0-1007-lowlatency | 3         | 1.04%   |
| 5.15.0-67-lowlatency   | 3         | 1.04%   |
| 5.15.0-58-lowlatency   | 3         | 1.04%   |
| 5.15.0-52-lowlatency   | 3         | 1.04%   |
| 5.15.0-50-lowlatency   | 3         | 1.04%   |
| 5.15.0-48-lowlatency   | 3         | 1.04%   |
| 5.15.0-47-lowlatency   | 3         | 1.04%   |
| 5.11.0-44-lowlatency   | 3         | 1.04%   |
| 5.11.0-34-lowlatency   | 3         | 1.04%   |
| 6.8.0-53-lowlatency    | 2         | 0.69%   |
| 6.8.0-45-lowlatency    | 2         | 0.69%   |
| 6.8.0-39-lowlatency    | 2         | 0.69%   |
| 6.8.0-35-lowlatency    | 2         | 0.69%   |
| 6.5.0-41-lowlatency    | 2         | 0.69%   |
| 6.5.0-25-lowlatency    | 2         | 0.69%   |
| 6.5.0-15-lowlatency    | 2         | 0.69%   |
| 6.5.0-13-lowlatency    | 2         | 0.69%   |
| 6.2.0-1018-lowlatency  | 2         | 0.69%   |
| 6.2.0-1014-lowlatency  | 2         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 58        | 20.71%  |
| 5.4.0   | 53        | 18.93%  |
| 6.8.0   | 40        | 14.29%  |
| 5.8.0   | 23        | 8.21%   |
| 6.2.0   | 22        | 7.86%   |
| 6.5.0   | 17        | 6.07%   |
| 5.11.0  | 15        | 5.36%   |
| 5.19.0  | 14        | 5%      |
| 6.11.0  | 10        | 3.57%   |
| 5.13.0  | 10        | 3.57%   |
| 6.14.0  | 8         | 2.86%   |
| 4.15.0  | 3         | 1.07%   |
| 5.3.0   | 2         | 0.71%   |
| 6.2.8   | 1         | 0.36%   |
| 5.7.6   | 1         | 0.36%   |
| 5.17.1  | 1         | 0.36%   |
| 5.15.6  | 1         | 0.36%   |
| 4.4.0   | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 59        | 21.07%  |
| 5.4     | 53        | 18.93%  |
| 6.8     | 40        | 14.29%  |
| 6.2     | 23        | 8.21%   |
| 5.8     | 23        | 8.21%   |
| 6.5     | 17        | 6.07%   |
| 5.11    | 15        | 5.36%   |
| 5.19    | 14        | 5%      |
| 6.11    | 10        | 3.57%   |
| 5.13    | 10        | 3.57%   |
| 6.14    | 8         | 2.86%   |
| 4.15    | 3         | 1.07%   |
| 5.3     | 2         | 0.71%   |
| 5.7     | 1         | 0.36%   |
| 5.17    | 1         | 0.36%   |
| 4.4     | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 275       | 99.28%  |
| i686    | 1         | 0.36%   |
| aarch64 | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 157       | 56.47%  |
| XFCE            | 86        | 30.94%  |
| GNOME           | 16        | 5.76%   |
| KDE6            | 10        | 3.6%    |
| LXQt            | 3         | 1.08%   |
| MATE            | 2         | 0.72%   |
| KDE             | 1         | 0.36%   |
| GNOME Flashback | 1         | 0.36%   |
| Cinnamon        | 1         | 0.36%   |
| Unknown         | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 247       | 88.85%  |
| Wayland | 27        | 9.71%   |
| Tty     | 4         | 1.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 161       | 58.12%  |
| LightDM | 54        | 19.49%  |
| TDM     | 49        | 17.69%  |
| GDM     | 11        | 3.97%   |
| LXDM    | 1         | 0.36%   |
| GDM3    | 1         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 121       | 43.53%  |
| fr_FR      | 31        | 11.15%  |
| de_DE      | 19        | 6.83%   |
| en_GB      | 15        | 5.4%    |
| C          | 14        | 5.04%   |
| it_IT      | 12        | 4.32%   |
| ru_RU      | 8         | 2.88%   |
| es_ES      | 8         | 2.88%   |
| en_CA      | 7         | 2.52%   |
| pt_BR      | 6         | 2.16%   |
| en_AU      | 3         | 1.08%   |
| nl_NL      | 2         | 0.72%   |
| hu_HU      | 2         | 0.72%   |
| es_MX      | 2         | 0.72%   |
| es_AR      | 2         | 0.72%   |
| en_IE      | 2         | 0.72%   |
| en_AG      | 2         | 0.72%   |
| Unknown    | 2         | 0.72%   |
| tr_TR      | 1         | 0.36%   |
| sv_SE      | 1         | 0.36%   |
| sk_SK      | 1         | 0.36%   |
| nl_BE      | 1         | 0.36%   |
| nb_NO      | 1         | 0.36%   |
| fr_FR.UTF8 | 1         | 0.36%   |
| fr_CH      | 1         | 0.36%   |
| fr_BE      | 1         | 0.36%   |
| es_NI      | 1         | 0.36%   |
| es_GT      | 1         | 0.36%   |
| es_CR      | 1         | 0.36%   |
| en_NZ      | 1         | 0.36%   |
| en_NG      | 1         | 0.36%   |
| en_IL      | 1         | 0.36%   |
| en_DE      | 1         | 0.36%   |
| de_CH      | 1         | 0.36%   |
| de_AT      | 1         | 0.36%   |
| ca_ES      | 1         | 0.36%   |
| ca_AD      | 1         | 0.36%   |
| bg_BG      | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 176       | 63.54%  |
| BIOS | 101       | 36.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 261       | 94.22%  |
| Overlay | 13        | 4.69%   |
| Xfs     | 1         | 0.36%   |
| Ext3    | 1         | 0.36%   |
| Ext2    | 1         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 198       | 71.48%  |
| MBR  | 79        | 28.52%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 221       | 78.93%  |
| Yes       | 59        | 21.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 57.19%  |
| Yes       | 119       | 42.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 50        | 18.05%  |
| Lenovo                               | 44        | 15.88%  |
| Hewlett-Packard                      | 36        | 13%     |
| Dell                                 | 35        | 12.64%  |
| Gigabyte Technology                  | 23        | 8.3%    |
| Apple                                | 12        | 4.33%   |
| Acer                                 | 12        | 4.33%   |
| MSI                                  | 11        | 3.97%   |
| Toshiba                              | 4         | 1.44%   |
| Intel                                | 4         | 1.44%   |
| Fujitsu                              | 4         | 1.44%   |
| ASRock                               | 4         | 1.44%   |
| Samsung Electronics                  | 3         | 1.08%   |
| Unknown                              | 3         | 1.08%   |
| Sony                                 | 2         | 0.72%   |
| HUAWEI                               | 2         | 0.72%   |
| AZW                                  | 2         | 0.72%   |
| Alienware                            | 2         | 0.72%   |
| win element                          | 1         | 0.36%   |
| System76                             | 1         | 0.36%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.36%   |
| Razer                                | 1         | 0.36%   |
| Raspberry Pi Foundation              | 1         | 0.36%   |
| Pegatron                             | 1         | 0.36%   |
| Packard Bell                         | 1         | 0.36%   |
| Notebook                             | 1         | 0.36%   |
| Microsoft                            | 1         | 0.36%   |
| Medion                               | 1         | 0.36%   |
| Intel Client Systems                 | 1         | 0.36%   |
| IBM                                  | 1         | 0.36%   |
| GPU Company                          | 1         | 0.36%   |
| Google                               | 1         | 0.36%   |
| Getac                                | 1         | 0.36%   |
| Foxconn                              | 1         | 0.36%   |
| ECS                                  | 1         | 0.36%   |
| DEPO Computers                       | 1         | 0.36%   |
| COM1                                 | 1         | 0.36%   |
| Clevo                                | 1         | 0.36%   |
| Avell High Performance               | 1         | 0.36%   |
| ATOPNUC                              | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 4         | 1.44%   |
| Unknown                                    | 4         | 1.44%   |
| HP Pavilion dv6                            | 3         | 1.08%   |
| Dell OptiPlex 790                          | 3         | 1.08%   |
| MSI MS-7C95                                | 2         | 0.72%   |
| Lenovo G50-45 80E3                         | 2         | 0.72%   |
| HP ZBook 15 G3                             | 2         | 0.72%   |
| HP EliteBook 840 G3                        | 2         | 0.72%   |
| Gigabyte B550M DS3H                        | 2         | 0.72%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 0.72%   |
| ASUS PRIME X570-PRO                        | 2         | 0.72%   |
| ASUS M4A785-M                              | 2         | 0.72%   |
| Apple iMac18,3                             | 2         | 0.72%   |
| win element MoreFine S500+                 | 1         | 0.36%   |
| Toshiba Satellite L755D                    | 1         | 0.36%   |
| Toshiba Satellite L505                     | 1         | 0.36%   |
| Toshiba Satellite C855                     | 1         | 0.36%   |
| Toshiba Satellite A505                     | 1         | 0.36%   |
| System76 Thelio                            | 1         | 0.36%   |
| Sony VPCCB3C5E                             | 1         | 0.36%   |
| Sony VGN-NS31M_W                           | 1         | 0.36%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.36%   |
| Samsung 730QCJ/730QCR                      | 1         | 0.36%   |
| Samsung 700Z7C                             | 1         | 0.36%   |
| Samsung 305V4A/305V5A                      | 1         | 0.36%   |
| Razer Blade Stealth 13 Late 2019           | 1         | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 1         | 0.36%   |
| Pegatron FL368AA-UUZ SR5612CH              | 1         | 0.36%   |
| Packard Bell IMEDIA S3220                  | 1         | 0.36%   |
| Notebook N8xEJEK                           | 1         | 0.36%   |
| MSI Prestige 13 AI+ Evo A2VMG              | 1         | 0.36%   |
| MSI PC Primescan AC                        | 1         | 0.36%   |
| MSI MS-7E06                                | 1         | 0.36%   |
| MSI MS-7E02                                | 1         | 0.36%   |
| MSI MS-7D99                                | 1         | 0.36%   |
| MSI MS-7A57                                | 1         | 0.36%   |
| MSI MS-7752                                | 1         | 0.36%   |
| MSI MS-7693                                | 1         | 0.36%   |
| MSI Alpha 15 A4DEK                         | 1         | 0.36%   |
| Microsoft Surface Laptop 3                 | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 19        | 6.86%   |
| Lenovo IdeaPad       | 10        | 3.61%   |
| Dell OptiPlex        | 10        | 3.61%   |
| ASUS ROG             | 10        | 3.61%   |
| Dell Inspiron        | 9         | 3.25%   |
| HP Compaq            | 8         | 2.89%   |
| Acer Aspire          | 8         | 2.89%   |
| Dell Latitude        | 7         | 2.53%   |
| HP EliteBook         | 6         | 2.17%   |
| Dell Precision       | 6         | 2.17%   |
| HP Pavilion          | 5         | 1.81%   |
| ASUS PRIME           | 5         | 1.81%   |
| Toshiba Satellite    | 4         | 1.44%   |
| ASUS All             | 4         | 1.44%   |
| Unknown              | 4         | 1.44%   |
| Lenovo Legion        | 3         | 1.08%   |
| HP ZBook             | 3         | 1.08%   |
| Fujitsu ESPRIMO      | 3         | 1.08%   |
| ASUS TUF             | 3         | 1.08%   |
| ASUS ASUS            | 3         | 1.08%   |
| MSI MS-7C95          | 2         | 0.72%   |
| Lenovo ThinkCentre   | 2         | 0.72%   |
| Lenovo IdeaPadFlex   | 2         | 0.72%   |
| Lenovo IdeaCentre    | 2         | 0.72%   |
| Lenovo G50-45        | 2         | 0.72%   |
| HP Laptop            | 2         | 0.72%   |
| HP EliteDesk         | 2         | 0.72%   |
| Gigabyte X570        | 2         | 0.72%   |
| Gigabyte B550M       | 2         | 0.72%   |
| Gigabyte B450M       | 2         | 0.72%   |
| Gigabyte AERO        | 2         | 0.72%   |
| ASUS VivoBook        | 2         | 0.72%   |
| ASUS P8P67           | 2         | 0.72%   |
| ASUS M4A785-M        | 2         | 0.72%   |
| Apple iMac18         | 2         | 0.72%   |
| Apple iMac11         | 2         | 0.72%   |
| Acer Nitro           | 2         | 0.72%   |
| win element MoreFine | 1         | 0.36%   |
| System76 Thelio      | 1         | 0.36%   |
| Sony VPCCB3C5E       | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 31        | 11.19%  |
| 2018 | 21        | 7.58%   |
| 2014 | 21        | 7.58%   |
| 2019 | 19        | 6.86%   |
| 2016 | 19        | 6.86%   |
| 2012 | 18        | 6.5%    |
| 2011 | 18        | 6.5%    |
| 2015 | 17        | 6.14%   |
| 2013 | 17        | 6.14%   |
| 2021 | 16        | 5.78%   |
| 2008 | 15        | 5.42%   |
| 2022 | 14        | 5.05%   |
| 2017 | 13        | 4.69%   |
| 2009 | 10        | 3.61%   |
| 2010 | 9         | 3.25%   |
| 2024 | 6         | 2.17%   |
| 2023 | 5         | 1.81%   |
| 2007 | 4         | 1.44%   |
| 2005 | 3         | 1.08%   |
| 2025 | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 132       | 47.65%  |
| Desktop        | 122       | 44.04%  |
| All in one     | 10        | 3.61%   |
| Mini pc        | 7         | 2.53%   |
| Convertible    | 3         | 1.08%   |
| Tablet         | 2         | 0.72%   |
| System on chip | 1         | 0.36%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 254       | 91.7%   |
| Enabled  | 23        | 8.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 275       | 99.28%  |
| Yes  | 2         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 76        | 27.24%  |
| 16.01-24.0  | 58        | 20.79%  |
| 8.01-16.0   | 49        | 17.56%  |
| 32.01-64.0  | 40        | 14.34%  |
| 3.01-4.0    | 22        | 7.89%   |
| 64.01-256.0 | 21        | 7.53%   |
| 24.01-32.0  | 6         | 2.15%   |
| 1.01-2.0    | 4         | 1.43%   |
| 2.01-3.0    | 3         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 70        | 24.73%  |
| 1.01-2.0   | 70        | 24.73%  |
| 4.01-8.0   | 60        | 21.2%   |
| 3.01-4.0   | 51        | 18.02%  |
| 8.01-16.0  | 22        | 7.77%   |
| 0.51-1.0   | 4         | 1.41%   |
| 24.01-32.0 | 3         | 1.06%   |
| 16.01-24.0 | 2         | 0.71%   |
| 32.01-64.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 150       | 53.76%  |
| 2      | 85        | 30.47%  |
| 3      | 20        | 7.17%   |
| 4      | 7         | 2.51%   |
| 5      | 6         | 2.15%   |
| 7      | 5         | 1.79%   |
| 0      | 2         | 0.72%   |
| 16     | 1         | 0.36%   |
| 11     | 1         | 0.36%   |
| 10     | 1         | 0.36%   |
| 6      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 168       | 60.43%  |
| Yes       | 110       | 39.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 89.21%  |
| No        | 30        | 10.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 212       | 76.53%  |
| No        | 65        | 23.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 62.45%  |
| No        | 104       | 37.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 79        | 28.42%  |
| France       | 32        | 11.51%  |
| Germany      | 29        | 10.43%  |
| Italy        | 17        | 6.12%   |
| Canada       | 11        | 3.96%   |
| Spain        | 10        | 3.6%    |
| UK           | 9         | 3.24%   |
| Russia       | 9         | 3.24%   |
| Brazil       | 8         | 2.88%   |
| Austria      | 6         | 2.16%   |
| Sweden       | 5         | 1.8%    |
| Mexico       | 5         | 1.8%    |
| Belgium      | 5         | 1.8%    |
| Australia    | 5         | 1.8%    |
| Netherlands  | 4         | 1.44%   |
| Switzerland  | 3         | 1.08%   |
| Norway       | 3         | 1.08%   |
| Turkey       | 2         | 0.72%   |
| Taiwan       | 2         | 0.72%   |
| Romania      | 2         | 0.72%   |
| Ivory Coast  | 2         | 0.72%   |
| Israel       | 2         | 0.72%   |
| Indonesia    | 2         | 0.72%   |
| Hungary      | 2         | 0.72%   |
| Costa Rica   | 2         | 0.72%   |
| Bulgaria     | 2         | 0.72%   |
| Argentina    | 2         | 0.72%   |
| Yemen        | 1         | 0.36%   |
| Sri Lanka    | 1         | 0.36%   |
| South Africa | 1         | 0.36%   |
| Slovakia     | 1         | 0.36%   |
| Poland       | 1         | 0.36%   |
| Philippines  | 1         | 0.36%   |
| Peru         | 1         | 0.36%   |
| Nigeria      | 1         | 0.36%   |
| Nicaragua    | 1         | 0.36%   |
| New Zealand  | 1         | 0.36%   |
| Luxembourg   | 1         | 0.36%   |
| Kenya        | 1         | 0.36%   |
| Ireland      | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Vienna               | 4         | 1.41%   |
| Stockholm            | 4         | 1.41%   |
| Paris                | 4         | 1.41%   |
| Madrid               | 4         | 1.41%   |
| Munich               | 3         | 1.06%   |
| Montreal             | 3         | 1.06%   |
| Houston              | 3         | 1.06%   |
| Vizille              | 2         | 0.71%   |
| Turin                | 2         | 0.71%   |
| Toronto              | 2         | 0.71%   |
| Stuttgart            | 2         | 0.71%   |
| San Francisco        | 2         | 0.71%   |
| Portland             | 2         | 0.71%   |
| Moscow               | 2         | 0.71%   |
| Montelupo Fiorentino | 2         | 0.71%   |
| Mississauga          | 2         | 0.71%   |
| Miami                | 2         | 0.71%   |
| Mexico City          | 2         | 0.71%   |
| Hamburg              | 2         | 0.71%   |
| Groningen            | 2         | 0.71%   |
| Fürth               | 2         | 0.71%   |
| Denver               | 2         | 0.71%   |
| Chicago              | 2         | 0.71%   |
| Budapest             | 2         | 0.71%   |
| Bucharest            | 2         | 0.71%   |
| Brighton             | 2         | 0.71%   |
| Béziers             | 2         | 0.71%   |
| Abidjan              | 2         | 0.71%   |
| Zele                 | 1         | 0.35%   |
| Zanesville           | 1         | 0.35%   |
| Yonkers              | 1         | 0.35%   |
| Yekaterinburg        | 1         | 0.35%   |
| Wroclaw              | 1         | 0.35%   |
| Woonsocket           | 1         | 0.35%   |
| Woodland Park        | 1         | 0.35%   |
| Wilmington           | 1         | 0.35%   |
| Wildenfels           | 1         | 0.35%   |
| West Mifflin         | 1         | 0.35%   |
| Warner Robins        | 1         | 0.35%   |
| Voiron               | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 67        | 89     | 15.4%   |
| WDC                         | 65        | 80     | 14.94%  |
| Seagate                     | 55        | 83     | 12.64%  |
| SanDisk                     | 31        | 34     | 7.13%   |
| Toshiba                     | 22        | 23     | 5.06%   |
| Hitachi                     | 16        | 17     | 3.68%   |
| Crucial                     | 15        | 21     | 3.45%   |
| SK hynix                    | 14        | 16     | 3.22%   |
| Kingston                    | 14        | 15     | 3.22%   |
| Intel                       | 10        | 16     | 2.3%    |
| Unknown                     | 7         | 7      | 1.61%   |
| Micron Technology           | 7         | 7      | 1.61%   |
| PNY                         | 6         | 7      | 1.38%   |
| Phison                      | 6         | 6      | 1.38%   |
| Apple                       | 6         | 8      | 1.38%   |
| Kingston Technology Company | 5         | 6      | 1.15%   |
| HGST                        | 5         | 6      | 1.15%   |
| UMIS                        | 3         | 3      | 0.69%   |
| Team                        | 3         | 3      | 0.69%   |
| SPCC                        | 3         | 3      | 0.69%   |
| Lexar                       | 3         | 6      | 0.69%   |
| KIOXIA                      | 3         | 3      | 0.69%   |
| JMicron Technology          | 3         | 3      | 0.69%   |
| Intenso                     | 3         | 3      | 0.69%   |
| China                       | 3         | 3      | 0.69%   |
| ASMT                        | 3         | 3      | 0.69%   |
| A-DATA Technology           | 3         | 4      | 0.69%   |
| Unknown                     | 3         | 3      | 0.69%   |
| USB                         | 2         | 2      | 0.46%   |
| Silicon Motion              | 2         | 2      | 0.46%   |
| Realtek                     | 2         | 2      | 0.46%   |
| Patriot                     | 2         | 2      | 0.46%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.46%   |
| LITEON                      | 2         | 2      | 0.46%   |
| Fujitsu                     | 2         | 2      | 0.46%   |
| Corsair                     | 2         | 3      | 0.46%   |
| BHT                         | 2         | 2      | 0.46%   |
| XrayDisk                    | 1         | 1      | 0.23%   |
| XPG                         | 1         | 1      | 0.23%   |
| Wibtek                      | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                    | 4         | 0.81%   |
| Seagate ST500DM002-1BD142 500GB           | 4         | 0.81%   |
| Seagate ST2000DM001-1ER164 2TB            | 4         | 0.81%   |
| Seagate Expansion 2TB                     | 4         | 0.81%   |
| Samsung SSD 870 EVO 1TB                   | 4         | 0.81%   |
| Samsung SSD 860 EVO 500GB                 | 4         | 0.81%   |
| Crucial CT500MX500SSD1 500GB              | 4         | 0.81%   |
| Crucial CT1000MX500SSD1 1TB               | 4         | 0.81%   |
| WDC WDS200T2B0A-00SM50 2TB SSD            | 3         | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 3         | 0.61%   |
| Toshiba DT01ACA100 1TB                    | 3         | 0.61%   |
| Toshiba DT01ACA050 500GB                  | 3         | 0.61%   |
| Seagate ST2000DM008-2FR102 2TB            | 3         | 0.61%   |
| Seagate Expansion Desk 4TB                | 3         | 0.61%   |
| SanDisk NVMe SSD Drive 1TB                | 3         | 0.61%   |
| Samsung SSD 850 EVO 500GB                 | 3         | 0.61%   |
| Phison Sabrent 2TB                        | 3         | 0.61%   |
| Kingston SA400S37240G 240GB SSD           | 3         | 0.61%   |
| Unknown                                   | 3         | 0.61%   |
| WDC WDS500G3X0C-00SJG0 500GB              | 2         | 0.41%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 2         | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 2         | 0.41%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 2         | 0.41%   |
| USB SanDisk 3.2Gen1 496GB                 | 2         | 0.41%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 0.41%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 0.41%   |
| Toshiba HDWD130 3TB                       | 2         | 0.41%   |
| Team T253X6001T 1024GB SSD                | 2         | 0.41%   |
| SPCC Solid State Disk 256GB               | 2         | 0.41%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 2         | 0.41%   |
| Seagate ST500LM021-1KJ152 500GB           | 2         | 0.41%   |
| Seagate ST5000LM000-2AN170 5TB            | 2         | 0.41%   |
| Seagate ST2000LM015-2E8174 2TB            | 2         | 0.41%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 0.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 0.41%   |
| Seagate ST1000DM003-1CH162 1TB            | 2         | 0.41%   |
| SanDisk SSD PLUS 240GB                    | 2         | 0.41%   |
| SanDisk SSD PLUS 1000GB                   | 2         | 0.41%   |
| SanDisk SDSSDA240G 240GB                  | 2         | 0.41%   |
| SanDisk NVMe SSD Drive 2TB                | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 78     | 32.32%  |
| WDC                 | 50        | 60     | 30.49%  |
| Toshiba             | 21        | 22     | 12.8%   |
| Hitachi             | 16        | 17     | 9.76%   |
| Samsung Electronics | 5         | 5      | 3.05%   |
| HGST                | 5         | 6      | 3.05%   |
| Apple               | 3         | 3      | 1.83%   |
| JMicron Technology  | 2         | 2      | 1.22%   |
| Fujitsu             | 2         | 2      | 1.22%   |
| USB 3.0             | 1         | 2      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |
| TO Exter            | 1         | 1      | 0.61%   |
| Maxtor              | 1         | 1      | 0.61%   |
| Inateck             | 1         | 1      | 0.61%   |
| External            | 1         | 1      | 0.61%   |
| ASMT                | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 38     | 22.92%  |
| SanDisk             | 22        | 23     | 15.28%  |
| Kingston            | 13        | 14     | 9.03%   |
| Crucial             | 12        | 18     | 8.33%   |
| WDC                 | 7         | 9      | 4.86%   |
| PNY                 | 6         | 7      | 4.17%   |
| SK hynix            | 4         | 5      | 2.78%   |
| SPCC                | 3         | 3      | 2.08%   |
| Micron Technology   | 3         | 3      | 2.08%   |
| Intenso             | 3         | 3      | 2.08%   |
| China               | 3         | 3      | 2.08%   |
| Team                | 2         | 2      | 1.39%   |
| Patriot             | 2         | 2      | 1.39%   |
| BHT                 | 2         | 2      | 1.39%   |
| ASMT                | 2         | 2      | 1.39%   |
| A-DATA Technology   | 2         | 2      | 1.39%   |
| XrayDisk            | 1         | 1      | 0.69%   |
| Wibtek              | 1         | 1      | 0.69%   |
| V-GeN               | 1         | 1      | 0.69%   |
| Toshiba             | 1         | 1      | 0.69%   |
| Seagate             | 1         | 1      | 0.69%   |
| SCY                 | 1         | 1      | 0.69%   |
| RX7                 | 1         | 1      | 0.69%   |
| Reeinno             | 1         | 1      | 0.69%   |
| Pioneer             | 1         | 2      | 0.69%   |
| OCZ                 | 1         | 1      | 0.69%   |
| NGFF                | 1         | 1      | 0.69%   |
| LITEONIT            | 1         | 1      | 0.69%   |
| LITEON              | 1         | 1      | 0.69%   |
| Lexar               | 1         | 1      | 0.69%   |
| Leven               | 1         | 1      | 0.69%   |
| LDLC                | 1         | 1      | 0.69%   |
| KingSpec            | 1         | 1      | 0.69%   |
| Intel               | 1         | 1      | 0.69%   |
| Integral            | 1         | 1      | 0.69%   |
| Fanxiang            | 1         | 1      | 0.69%   |
| EDGE eMe            | 1         | 1      | 0.69%   |
| Dogfish             | 1         | 1      | 0.69%   |
| Corsair             | 1         | 1      | 0.69%   |
| ASMedia             | 1         | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 132       | 203    | 35.29%  |
| SSD     | 120       | 162    | 32.09%  |
| NVMe    | 104       | 148    | 27.81%  |
| MMC     | 11        | 12     | 2.94%   |
| Unknown | 7         | 7      | 1.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 200       | 339    | 58.48%  |
| NVMe | 104       | 146    | 30.41%  |
| SAS  | 27        | 35     | 7.89%   |
| MMC  | 11        | 12     | 3.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 145       | 182    | 51.24%  |
| 0.51-1.0   | 81        | 98     | 28.62%  |
| 1.01-2.0   | 34        | 41     | 12.01%  |
| 3.01-4.0   | 10        | 12     | 3.53%   |
| 4.01-10.0  | 7         | 24     | 2.47%   |
| 2.01-3.0   | 6         | 8      | 2.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 25.18%  |
| 251-500        | 56        | 19.86%  |
| 501-1000       | 52        | 18.44%  |
| 1001-2000      | 41        | 14.54%  |
| More than 3000 | 23        | 8.16%   |
| 51-100         | 14        | 4.96%   |
| 21-50          | 11        | 3.9%    |
| 1-20           | 8         | 2.84%   |
| 2001-3000      | 6         | 2.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 26.5%   |
| 21-50          | 51        | 18.02%  |
| 101-250        | 40        | 14.13%  |
| 51-100         | 32        | 11.31%  |
| 251-500        | 29        | 10.25%  |
| 501-1000       | 25        | 8.83%   |
| More than 3000 | 13        | 4.59%   |
| 1001-2000      | 13        | 4.59%   |
| 2001-3000      | 5         | 1.77%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 3         | 3      | 5.36%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 2         | 3      | 3.57%   |
| Samsung Electronics HD753LJ 752GB                   | 2         | 2      | 3.57%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 1.79%   |
| WDC WD5000AVDS-63U7B1 500GB                         | 1         | 1      | 1.79%   |
| WDC WD5000AAKS-00TMA0 500GB                         | 1         | 1      | 1.79%   |
| WDC WD3200BPVT-80ZEST0 320GB                        | 1         | 1      | 1.79%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 1.79%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 1.79%   |
| WDC WD30EZRX-00MMMB0 3TB                            | 1         | 1      | 1.79%   |
| WDC WD2500BEVT-22ZCT0 250GB                         | 1         | 1      | 1.79%   |
| WDC WD1600AAJS-08L7A0 160GB                         | 1         | 1      | 1.79%   |
| WDC WD10EZEX-22BN5A0 1TB                            | 1         | 1      | 1.79%   |
| WDC WD10EAVS-32D7B1 1TB                             | 1         | 1      | 1.79%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 1      | 1.79%   |
| UMIS RPITJ512VME2OWD 512GB                          | 1         | 1      | 1.79%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 1.79%   |
| Toshiba MK1637GSX 160GB                             | 1         | 1      | 1.79%   |
| Toshiba HDWE140 4TB                                 | 1         | 1      | 1.79%   |
| SSSTC CL1-4D512 512GB                               | 1         | 1      | 1.79%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 2      | 1.79%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 1.79%   |
| Seagate ST9320320AS 320GB                           | 1         | 1      | 1.79%   |
| Seagate ST8000DM004-2CX1 8TB                        | 1         | 6      | 1.79%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 1.79%   |
| Seagate ST3320820AS 320GB                           | 1         | 1      | 1.79%   |
| Seagate ST3200822AS 200GB                           | 1         | 1      | 1.79%   |
| Seagate ST2000DM006-2DM164 2TB                      | 1         | 1      | 1.79%   |
| Seagate ST2000DM001-9YN164 2TB                      | 1         | 1      | 1.79%   |
| Seagate ST2000DM001-1CH164 2TB                      | 1         | 1      | 1.79%   |
| Seagate ST1000VM002-9ZL162 1TB                      | 1         | 1      | 1.79%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 1.79%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 1.79%   |
| Samsung Electronics SSD 970 EVO 1TB S467NF0K604975T | 1         | 1      | 1.79%   |
| Samsung Electronics SSD 970 EVO 1TB                 | 1         | 1      | 1.79%   |
| Samsung Electronics SSD 960 PRO 512GB               | 1         | 1      | 1.79%   |
| Samsung Electronics HN-M500MBB 500GB                | 1         | 1      | 1.79%   |
| Samsung Electronics HM320JI 320GB                   | 1         | 1      | 1.79%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 1.79%   |
| KingSpec P3-256 256GB SSD                           | 1         | 1      | 1.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 19     | 25.45%  |
| WDC                 | 11        | 12     | 20%     |
| Samsung Electronics | 9         | 10     | 16.36%  |
| Hitachi             | 7         | 7      | 12.73%  |
| Toshiba             | 3         | 3      | 5.45%   |
| A-DATA Technology   | 2         | 2      | 3.64%   |
| UMIS                | 1         | 1      | 1.82%   |
| SSSTC               | 1         | 1      | 1.82%   |
| SK hynix            | 1         | 2      | 1.82%   |
| SanDisk             | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| HGST                | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 19     | 34.15%  |
| WDC                 | 11        | 12     | 26.83%  |
| Hitachi             | 7         | 7      | 17.07%  |
| Samsung Electronics | 4         | 4      | 9.76%   |
| Toshiba             | 3         | 3      | 7.32%   |
| HGST                | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 47     | 73.08%  |
| SSD  | 9         | 11     | 17.31%  |
| NVMe | 5         | 5      | 9.62%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD10EAVS-00D7B1 1TB               | 1         | 1      | 50%     |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 236       | 414    | 71.95%  |
| Malfunc  | 52        | 63     | 15.85%  |
| Detected | 37        | 52     | 11.28%  |
| Failed   | 2         | 2      | 0.61%   |
| Fixed    | 1         | 1      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 186       | 48.82%  |
| AMD                            | 62        | 16.27%  |
| Samsung Electronics            | 37        | 9.71%   |
| SanDisk                        | 18        | 4.72%   |
| SK hynix                       | 10        | 2.62%   |
| Phison Electronics             | 10        | 2.62%   |
| ASMedia Technology             | 7         | 1.84%   |
| Marvell Technology Group       | 6         | 1.57%   |
| Kingston Technology Company    | 6         | 1.57%   |
| Union Memory (Shenzhen)        | 4         | 1.05%   |
| Micron Technology              | 4         | 1.05%   |
| Silicon Motion                 | 3         | 0.79%   |
| Nvidia                         | 3         | 0.79%   |
| Micron/Crucial Technology      | 3         | 0.79%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.79%   |
| Realtek Semiconductor          | 2         | 0.52%   |
| KIOXIA                         | 2         | 0.52%   |
| JMicron Technology             | 2         | 0.52%   |
| VIA Technologies               | 1         | 0.26%   |
| Toshiba America Info Systems   | 1         | 0.26%   |
| Solid State Storage Technology | 1         | 0.26%   |
| Silicon Image                  | 1         | 0.26%   |
| Shenzhen Longsys Electronics   | 1         | 0.26%   |
| Seagate Technology             | 1         | 0.26%   |
| LSI Logic / Symbios Logic      | 1         | 0.26%   |
| Lite-On Technology             | 1         | 0.26%   |
| INNOGRIT                       | 1         | 0.26%   |
| HighPoint Technologies         | 1         | 0.26%   |
| Apple                          | 1         | 0.26%   |
| ADATA Technology               | 1         | 0.26%   |
| Adaptec                        | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 39        | 8.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 3.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 3.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 3.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 2.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 2.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.84%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 8         | 1.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 7         | 1.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.61%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 7         | 1.61%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 1.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.15%   |
| Phison E12 NVMe Controller                                                     | 5         | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 1.15%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 5         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.15%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 4         | 0.92%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.92%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.69%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3         | 0.69%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 3         | 0.69%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 0.69%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 3         | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.69%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 3         | 0.69%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.69%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 213       | 56.35%  |
| NVMe | 105       | 27.78%  |
| IDE  | 34        | 8.99%   |
| RAID | 22        | 5.82%   |
| SAS  | 3         | 0.79%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 201       | 72.56%  |
| AMD    | 75        | 27.08%  |
| ARM    | 1         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 4         | 1.44%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 4         | 1.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1.08%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 1.08%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 1.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 1.08%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 3         | 1.08%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 3         | 1.08%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.08%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 3         | 1.08%   |
| AMD Ryzen 7 5825U with Radeon Graphics  | 3         | 1.08%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 3         | 1.08%   |
| Intel Core i9-9900K CPU @ 3.60GHz       | 2         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 2         | 0.72%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.72%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.72%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 0.72%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 2         | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.72%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.72%   |
| Intel Core i5-4440 CPU @ 3.10GHz        | 2         | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.72%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 2         | 0.72%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 0.72%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.72%   |
| Intel Core i5 CPU 650 @ 3.20GHz         | 2         | 0.72%   |
| Intel Core i3-6100 CPU @ 3.70GHz        | 2         | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 2         | 0.72%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 2         | 0.72%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 2         | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 2         | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 0.72%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 2         | 0.72%   |
| AMD Ryzen 9 3950X 16-Core Processor     | 2         | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 2         | 0.72%   |
| AMD Ryzen 7 3800X 8-Core Processor      | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 64        | 23.1%   |
| Intel Core i5          | 64        | 23.1%   |
| Other                  | 20        | 7.22%   |
| AMD Ryzen 5            | 20        | 7.22%   |
| Intel Core i3          | 15        | 5.42%   |
| AMD Ryzen 7            | 13        | 4.69%   |
| AMD Ryzen 9            | 9         | 3.25%   |
| Intel Celeron          | 8         | 2.89%   |
| Intel Core i9          | 7         | 2.53%   |
| Intel Core 2 Duo       | 7         | 2.53%   |
| Intel Xeon             | 6         | 2.17%   |
| AMD Phenom II X4       | 4         | 1.44%   |
| AMD FX                 | 4         | 1.44%   |
| Intel Core 2 Quad      | 3         | 1.08%   |
| AMD Ryzen 3            | 3         | 1.08%   |
| AMD E                  | 3         | 1.08%   |
| Intel Pentium 4        | 2         | 0.72%   |
| Intel Pentium          | 2         | 0.72%   |
| Intel Core             | 2         | 0.72%   |
| AMD Athlon II X2       | 2         | 0.72%   |
| AMD A8                 | 2         | 0.72%   |
| AMD A4                 | 2         | 0.72%   |
| Intel Pentium Dual     | 1         | 0.36%   |
| Intel Pentium D        | 1         | 0.36%   |
| Intel Genuine          | 1         | 0.36%   |
| Intel Core 2           | 1         | 0.36%   |
| AMD Ryzen Threadripper | 1         | 0.36%   |
| AMD Ryzen 5 PRO        | 1         | 0.36%   |
| AMD Ryzen 3 PRO        | 1         | 0.36%   |
| AMD E2                 | 1         | 0.36%   |
| AMD E1                 | 1         | 0.36%   |
| AMD Athlon X4          | 1         | 0.36%   |
| AMD Athlon II X4       | 1         | 0.36%   |
| AMD Athlon Dual Core   | 1         | 0.36%   |
| AMD Athlon 64 X2       | 1         | 0.36%   |
| AMD A6                 | 1         | 0.36%   |
| AMD A10                | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 104       | 37.55%  |
| 2      | 89        | 32.13%  |
| 6      | 35        | 12.64%  |
| 8      | 24        | 8.66%   |
| 16     | 6         | 2.17%   |
| 10     | 5         | 1.81%   |
| 12     | 4         | 1.44%   |
| 14     | 3         | 1.08%   |
| 1      | 3         | 1.08%   |
| 24     | 2         | 0.72%   |
| 32     | 1         | 0.36%   |
| 18     | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 276       | 99.64%  |
| 2      | 1         | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 194       | 70.04%  |
| 1      | 83        | 29.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 276       | 99.64%  |
| 32-bit         | 1         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 37.63%  |
| 0x306c3    | 14        | 5.02%   |
| 0x306a9    | 14        | 5.02%   |
| 0x206a7    | 14        | 5.02%   |
| 0x906ea    | 9         | 3.23%   |
| 0x306d4    | 6         | 2.15%   |
| 0x506e3    | 5         | 1.79%   |
| 0x08600104 | 5         | 1.79%   |
| 0x806ea    | 4         | 1.43%   |
| 0x806c1    | 4         | 1.43%   |
| 0x0a50000c | 4         | 1.43%   |
| 0x08701021 | 4         | 1.43%   |
| 0xa0652    | 3         | 1.08%   |
| 0x906e9    | 3         | 1.08%   |
| 0x706e5    | 3         | 1.08%   |
| 0x406e3    | 3         | 1.08%   |
| 0x40651    | 3         | 1.08%   |
| 0x106e5    | 3         | 1.08%   |
| 0x10676    | 3         | 1.08%   |
| 0x0a50000d | 3         | 1.08%   |
| 0x08600106 | 3         | 1.08%   |
| 0x08108109 | 3         | 1.08%   |
| 0x010000c8 | 3         | 1.08%   |
| 0xf41      | 2         | 0.72%   |
| 0xa0655    | 2         | 0.72%   |
| 0x906ed    | 2         | 0.72%   |
| 0x6fd      | 2         | 0.72%   |
| 0x206d7    | 2         | 0.72%   |
| 0x106a5    | 2         | 0.72%   |
| 0x07030105 | 2         | 0.72%   |
| 0x010000b6 | 2         | 0.72%   |
| 0xf65      | 1         | 0.36%   |
| 0x906ec    | 1         | 0.36%   |
| 0x906a4    | 1         | 0.36%   |
| 0x906a3    | 1         | 0.36%   |
| 0x90675    | 1         | 0.36%   |
| 0x806ec    | 1         | 0.36%   |
| 0x806e9    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x6fb      | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 34        | 12.27%  |
| Haswell          | 29        | 10.47%  |
| Skylake          | 23        | 8.3%    |
| Zen 2            | 21        | 7.58%   |
| SandyBridge      | 21        | 7.58%   |
| IvyBridge        | 17        | 6.14%   |
| Zen 3            | 13        | 4.69%   |
| Broadwell        | 11        | 3.97%   |
| Alderlake Hybrid | 11        | 3.97%   |
| Penryn           | 9         | 3.25%   |
| Unknown          | 9         | 3.25%   |
| Zen+             | 6         | 2.17%   |
| Westmere         | 6         | 2.17%   |
| TigerLake        | 6         | 2.17%   |
| Nehalem          | 6         | 2.17%   |
| K10              | 6         | 2.17%   |
| CometLake        | 6         | 2.17%   |
| Piledriver       | 5         | 1.81%   |
| IceLake          | 5         | 1.81%   |
| Core             | 5         | 1.81%   |
| Puma             | 4         | 1.44%   |
| NetBurst         | 3         | 1.08%   |
| K10 Llano        | 3         | 1.08%   |
| Goldmont         | 3         | 1.08%   |
| Excavator        | 3         | 1.08%   |
| Zen              | 2         | 0.72%   |
| Lunarlake Hybrid | 2         | 0.72%   |
| K8 Hammer        | 2         | 0.72%   |
| Goldmont plus    | 2         | 0.72%   |
| Bobcat           | 2         | 0.72%   |
| Steamroller      | 1         | 0.36%   |
| Silvermont       | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 147       | 44.14%  |
| Nvidia | 104       | 31.23%  |
| AMD    | 82        | 24.62%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 13        | 3.79%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 11        | 3.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 2.62%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 9         | 2.62%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 8         | 2.33%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 8         | 2.33%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 7         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 2.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 7         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 1.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6         | 1.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6         | 1.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 1.46%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 5         | 1.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 1.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 1.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 4         | 1.17%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 4         | 1.17%   |
| Intel Iris Plus Graphics G7                                                 | 4         | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                         | 4         | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 1.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 0.87%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3         | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3         | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 0.87%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3         | 0.87%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 3         | 0.87%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                     | 3         | 0.87%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 3         | 0.87%   |
| AMD Barcelo                                                                 | 3         | 0.87%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 2         | 0.58%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 2         | 0.58%   |
| Nvidia GK208BM [GeForce 920M]                                               | 2         | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2         | 0.58%   |
| Nvidia GF108M [GeForce GT 525M]                                             | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 99        | 35.61%  |
| 1 x AMD        | 61        | 21.94%  |
| 1 x Nvidia     | 57        | 20.5%   |
| Intel + Nvidia | 36        | 12.95%  |
| AMD + Nvidia   | 10        | 3.6%    |
| 2 x AMD        | 6         | 2.16%   |
| Intel + AMD    | 5         | 1.8%    |
| 2 x Nvidia     | 2         | 0.72%   |
| Other          | 1         | 0.36%   |
| 2 x Intel      | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 221       | 79.5%   |
| Proprietary | 50        | 17.99%  |
| Unknown     | 7         | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 43.93%  |
| 0.01-0.5   | 37        | 13.21%  |
| 1.01-2.0   | 36        | 12.86%  |
| 0.51-1.0   | 27        | 9.64%   |
| 3.01-4.0   | 21        | 7.5%    |
| 8.01-16.0  | 13        | 4.64%   |
| 7.01-8.0   | 12        | 4.29%   |
| 5.01-6.0   | 7         | 2.5%    |
| 16.01-24.0 | 2         | 0.71%   |
| 32.01-64.0 | 1         | 0.36%   |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 43        | 13.78%  |
| AU Optronics            | 32        | 10.26%  |
| LG Display              | 25        | 8.01%   |
| Goldstar                | 21        | 6.73%   |
| BOE                     | 21        | 6.73%   |
| Chimei Innolux          | 19        | 6.09%   |
| Hewlett-Packard         | 16        | 5.13%   |
| Dell                    | 16        | 5.13%   |
| Philips                 | 15        | 4.81%   |
| Acer                    | 11        | 3.53%   |
| Apple                   | 10        | 3.21%   |
| Ancor Communications    | 8         | 2.56%   |
| Sharp                   | 6         | 1.92%   |
| BenQ                    | 6         | 1.92%   |
| Lenovo                  | 5         | 1.6%    |
| Sony                    | 4         | 1.28%   |
| ASUSTek Computer        | 4         | 1.28%   |
| Eizo                    | 3         | 0.96%   |
| Chi Mei Optoelectronics | 3         | 0.96%   |
| AOC                     | 3         | 0.96%   |
| ViewSonic               | 2         | 0.64%   |
| Unknown                 | 2         | 0.64%   |
| ONN                     | 2         | 0.64%   |
| Iiyama                  | 2         | 0.64%   |
| HKC                     | 2         | 0.64%   |
| Hitachi                 | 2         | 0.64%   |
| Hannspree               | 2         | 0.64%   |
| Fujitsu Siemens         | 2         | 0.64%   |
| Westinghouse            | 1         | 0.32%   |
| VIE                     | 1         | 0.32%   |
| UGD                     | 1         | 0.32%   |
| TVT                     | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| TCH                     | 1         | 0.32%   |
| Targa Visionary         | 1         | 0.32%   |
| Seiki                   | 1         | 0.32%   |
| RTK                     | 1         | 0.32%   |
| Onkyo                   | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.91%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 2         | 0.61%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 2         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 2         | 0.61%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 2         | 0.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.61%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.61%   |
| Hannspree HF207 HSG18C5 1600x900 443x249mm 20.0-inch                  | 2         | 0.61%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2         | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.61%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.61%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.61%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch         | 2         | 0.61%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 0.61%   |
| Apple iMac APPAE11 3840x2160 597x336mm 27.0-inch                      | 2         | 0.61%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 2         | 0.61%   |
| Westinghouse SK-26H730S WDE15CC 1366x768 575x323mm 26.0-inch          | 1         | 0.3%    |
| ViewSonic VX2758-C-MH VSC35DD 1920x1080 597x336mm 27.0-inch           | 1         | 0.3%    |
| ViewSonic VA2432-FHD VSCB639 1920x1080 527x296mm 23.8-inch            | 1         | 0.3%    |
| VIE LED MONITOR VIE2302 1920x1080 473x296mm 22.0-inch                 | 1         | 0.3%    |
| Unknown LCD Monitor SAMSUNG 5760x2160                                 | 1         | 0.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.3%    |
| UGD Artist 12 pro UGD1102 1920x1080 256x144mm 11.6-inch               | 1         | 0.3%    |
| TVT T910 TVT005E 1280x1024 376x301mm 19.0-inch                        | 1         | 0.3%    |
| Toshiba HisenseUS-TV TSB0030 1920x1080 800x450mm 36.1-inch            | 1         | 0.3%    |
| TCH HDMI TCH5600 1920x1080 344x194mm 15.5-inch                        | 1         | 0.3%    |
| Targa Visionary LCD 24-1 Wide TARA240 1920x1080 521x293mm 23.5-inch   | 1         | 0.3%    |
| Sony TV SNYEA01 1920x1080                                             | 1         | 0.3%    |
| Sony TV SNY4201 1360x768 710x400mm 32.1-inch                          | 1         | 0.3%    |
| Sony TV *30 SNYB105 3840x2160 1218x685mm 55.0-inch                    | 1         | 0.3%    |
| Sony TV *00 SNY8004 3840x2160 1439x809mm 65.0-inch                    | 1         | 0.3%    |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 0.3%    |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.3%    |
| Sharp LQ134N1JW54 SHP154F 1920x1200 288x180mm 13.4-inch               | 1         | 0.3%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 142       | 47.65%  |
| 1366x768 (WXGA)    | 43        | 14.43%  |
| 3840x2160 (4K)     | 30        | 10.07%  |
| 1280x1024 (SXGA)   | 13        | 4.36%   |
| 1680x1050 (WSXGA+) | 12        | 4.03%   |
| 2560x1440 (QHD)    | 10        | 3.36%   |
| 1920x1200 (WUXGA)  | 10        | 3.36%   |
| 1600x900 (HD+)     | 8         | 2.68%   |
| 1440x900 (WXGA+)   | 4         | 1.34%   |
| 2880x1800          | 3         | 1.01%   |
| 1360x768           | 3         | 1.01%   |
| 1280x800 (WXGA)    | 3         | 1.01%   |
| 3440x1440          | 2         | 0.67%   |
| 2560x1600          | 2         | 0.67%   |
| Unknown            | 2         | 0.67%   |
| 5760x2160          | 1         | 0.34%   |
| 3840x1080          | 1         | 0.34%   |
| 3280x1080          | 1         | 0.34%   |
| 3200x2000          | 1         | 0.34%   |
| 2496x1664          | 1         | 0.34%   |
| 2288x1287          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 1920x540           | 1         | 0.34%   |
| 1600x1200          | 1         | 0.34%   |
| 1400x1050          | 1         | 0.34%   |
| 1024x768 (XGA)     | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 71        | 22.68%  |
| 27      | 30        | 9.58%   |
| 21      | 28        | 8.95%   |
| 24      | 26        | 8.31%   |
| 13      | 24        | 7.67%   |
| 23      | 20        | 6.39%   |
| 17      | 18        | 5.75%   |
| 14      | 15        | 4.79%   |
| 31      | 12        | 3.83%   |
| 22      | 10        | 3.19%   |
| 19      | 9         | 2.88%   |
| 84      | 6         | 1.92%   |
| 18      | 6         | 1.92%   |
| 16      | 6         | 1.92%   |
| 20      | 5         | 1.6%    |
| 12      | 5         | 1.6%    |
| 32      | 3         | 0.96%   |
| Unknown | 3         | 0.96%   |
| 72      | 2         | 0.64%   |
| 54      | 2         | 0.64%   |
| 26      | 2         | 0.64%   |
| 142     | 1         | 0.32%   |
| 75      | 1         | 0.32%   |
| 65      | 1         | 0.32%   |
| 52      | 1         | 0.32%   |
| 50      | 1         | 0.32%   |
| 49      | 1         | 0.32%   |
| 43      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 34      | 1         | 0.32%   |
| 11      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 107       | 34.97%  |
| 501-600        | 70        | 22.88%  |
| 401-500        | 52        | 16.99%  |
| 351-400        | 19        | 6.21%   |
| 201-300        | 18        | 5.88%   |
| 601-700        | 15        | 4.9%    |
| 1501-2000      | 9         | 2.94%   |
| 1001-1500      | 6         | 1.96%   |
| 701-800        | 4         | 1.31%   |
| Unknown        | 3         | 0.98%   |
| More than 2000 | 1         | 0.33%   |
| 801-900        | 1         | 0.33%   |
| 901-1000       | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 216       | 77.14%  |
| 16/10   | 42        | 15%     |
| 5/4     | 10        | 3.57%   |
| 3/2     | 3         | 1.07%   |
| Unknown | 3         | 1.07%   |
| 4/3     | 2         | 0.71%   |
| 6/5     | 1         | 0.36%   |
| 32/9    | 1         | 0.36%   |
| 21/9    | 1         | 0.36%   |
| 1.00    | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 23.05%  |
| 201-250        | 65        | 21.1%   |
| 301-350        | 31        | 10.06%  |
| 81-90          | 30        | 9.74%   |
| 151-200        | 18        | 5.84%   |
| 351-500        | 16        | 5.19%   |
| More than 1000 | 15        | 4.87%   |
| 141-150        | 13        | 4.22%   |
| 251-300        | 11        | 3.57%   |
| 121-130        | 10        | 3.25%   |
| 71-80          | 9         | 2.92%   |
| 61-70          | 5         | 1.62%   |
| 111-120        | 5         | 1.62%   |
| 501-1000       | 3         | 0.97%   |
| Unknown        | 3         | 0.97%   |
| 131-140        | 2         | 0.65%   |
| 51-60          | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 110       | 37.16%  |
| 101-120       | 73        | 24.66%  |
| 121-160       | 72        | 24.32%  |
| 161-240       | 25        | 8.45%   |
| 1-50          | 8         | 2.7%    |
| More than 240 | 5         | 1.69%   |
| Unknown       | 3         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 219       | 78.21%  |
| 2     | 55        | 19.64%  |
| 3     | 4         | 1.43%   |
| 4     | 1         | 0.36%   |
| 0     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 151       | 35.36%  |
| Realtek Semiconductor             | 148       | 34.66%  |
| Qualcomm Atheros                  | 39        | 9.13%   |
| Broadcom                          | 22        | 5.15%   |
| MediaTek                          | 14        | 3.28%   |
| Ralink                            | 5         | 1.17%   |
| TP-Link                           | 4         | 0.94%   |
| Broadcom Limited                  | 4         | 0.94%   |
| ASIX Electronics                  | 4         | 0.94%   |
| Ralink Technology                 | 3         | 0.7%    |
| Nvidia                            | 3         | 0.7%    |
| Aquantia                          | 3         | 0.7%    |
| Qualcomm Atheros Communications   | 2         | 0.47%   |
| Marvell Technology Group          | 2         | 0.47%   |
| Lenovo                            | 2         | 0.47%   |
| Ericsson Business Mobile Networks | 2         | 0.47%   |
| DisplayLink                       | 2         | 0.47%   |
| ZyDAS                             | 1         | 0.23%   |
| Xiaomi                            | 1         | 0.23%   |
| Wacom                             | 1         | 0.23%   |
| Sierra Wireless                   | 1         | 0.23%   |
| Shenzhen Goodix Technology        | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| NetGear                           | 1         | 0.23%   |
| Motorola PCS                      | 1         | 0.23%   |
| Microsoft                         | 1         | 0.23%   |
| InterBiometrics                   | 1         | 0.23%   |
| Input Club                        | 1         | 0.23%   |
| ICS Advent                        | 1         | 0.23%   |
| Huawei Technologies               | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Google                            | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| ASUSTek Computer                  | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 102       | 20.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 3.94%   |
| Intel Wireless 7265                                                    | 12        | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 1.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 10        | 1.97%   |
| Intel Wireless 8260                                                    | 9         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 1.58%   |
| Intel Wireless 8265 / 8275                                             | 7         | 1.38%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.38%   |
| Intel I211 Gigabit Network Connection                                  | 7         | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 7         | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 1.38%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6         | 1.18%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.18%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 0.99%   |
| Intel Wireless 7260                                                    | 5         | 0.99%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 5         | 0.99%   |
| Intel Wi-Fi 6 AX201                                                    | 5         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.79%   |
| Realtek 802.11ac NIC                                                   | 4         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.79%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4         | 0.79%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 0.79%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 4         | 0.79%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.59%   |
| Realtek Killer E2600 GbE Controller                                    | 3         | 0.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 0.59%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 3         | 0.59%   |
| Intel Wireless 3165                                                    | 3         | 0.59%   |
| Intel Wireless 3160                                                    | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 48.86%  |
| Realtek Semiconductor           | 33        | 15.07%  |
| Qualcomm Atheros                | 30        | 13.7%   |
| Broadcom                        | 15        | 6.85%   |
| MediaTek                        | 12        | 5.48%   |
| Ralink                          | 5         | 2.28%   |
| TP-Link                         | 4         | 1.83%   |
| Ralink Technology               | 3         | 1.37%   |
| Qualcomm Atheros Communications | 2         | 0.91%   |
| Broadcom Limited                | 2         | 0.91%   |
| ZyDAS                           | 1         | 0.46%   |
| Wacom                           | 1         | 0.46%   |
| Sierra Wireless                 | 1         | 0.46%   |
| NetGear                         | 1         | 0.46%   |
| Microsoft                       | 1         | 0.46%   |
| ASUSTek Computer                | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                                           | 12        | 5.45%   |
| Intel Wireless 8260                                                           | 9         | 4.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 8         | 3.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 8         | 3.64%   |
| Intel Wireless 8265 / 8275                                                    | 7         | 3.18%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 3.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 7         | 3.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 7         | 3.18%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 6         | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 2.27%   |
| Intel Wireless 7260                                                           | 5         | 2.27%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                     | 5         | 2.27%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 1.82%   |
| Realtek 802.11ac NIC                                                          | 4         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 4         | 1.82%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 4         | 1.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 4         | 1.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 3         | 1.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 3         | 1.36%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]          | 3         | 1.36%   |
| Intel Wireless 3165                                                           | 3         | 1.36%   |
| Intel Wireless 3160                                                           | 3         | 1.36%   |
| Intel WiFi Link 5100                                                          | 3         | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 3         | 1.36%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 3         | 1.36%   |
| Intel 700 Series Chipset CNVi WiFi                                            | 3         | 1.36%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 1.36%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 0.91%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 2         | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 2         | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 0.91%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.91%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 2         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 2         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.91%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 131       | 47.81%  |
| Intel                    | 93        | 33.94%  |
| Broadcom                 | 13        | 4.74%   |
| Qualcomm Atheros         | 12        | 4.38%   |
| ASIX Electronics         | 4         | 1.46%   |
| Nvidia                   | 3         | 1.09%   |
| Aquantia                 | 3         | 1.09%   |
| Marvell Technology Group | 2         | 0.73%   |
| Lenovo                   | 2         | 0.73%   |
| DisplayLink              | 2         | 0.73%   |
| Broadcom Limited         | 2         | 0.73%   |
| Xiaomi                   | 1         | 0.36%   |
| Samsung Electronics      | 1         | 0.36%   |
| Motorola PCS             | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| ICS Advent               | 1         | 0.36%   |
| Hewlett-Packard          | 1         | 0.36%   |
| Google                   | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 102       | 36.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 20        | 7.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 3.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 3.58%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.51%   |
| Intel Ethernet Controller I225-V                                               | 6         | 2.15%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 2.15%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.79%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.43%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 4         | 1.43%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.08%   |
| Realtek Killer E2600 GbE Controller                                            | 3         | 1.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 1.08%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.08%   |
| Intel Ethernet Connection (5) I219-LM                                          | 3         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.08%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3         | 1.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.72%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.72%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.72%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 0.72%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.72%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 0.72%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.36%   |
| Realtek USB 10/100/1G/2.5 LAN                                                  | 1         | 0.36%   |
| Realtek RTL8126 5GbE Controller                                                | 1         | 0.36%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.36%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 248       | 53.1%   |
| WiFi     | 211       | 45.18%  |
| Modem    | 8         | 1.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 50.66%  |
| Ethernet | 150       | 49.34%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 161       | 58.12%  |
| 1     | 107       | 38.63%  |
| 3     | 6         | 2.17%   |
| 0     | 3         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 202       | 72.4%   |
| Yes  | 77        | 27.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 50.29%  |
| Realtek Semiconductor           | 14        | 8%      |
| Qualcomm Atheros Communications | 11        | 6.29%   |
| Apple                           | 10        | 5.71%   |
| IMC Networks                    | 8         | 4.57%   |
| Cambridge Silicon Radio         | 8         | 4.57%   |
| Broadcom                        | 8         | 4.57%   |
| MediaTek                        | 5         | 2.86%   |
| Foxconn / Hon Hai               | 5         | 2.86%   |
| ASUSTek Computer                | 5         | 2.86%   |
| Realtek                         | 2         | 1.14%   |
| Ralink Technology               | 2         | 1.14%   |
| Lite-On Technology              | 2         | 1.14%   |
| Hewlett-Packard                 | 2         | 1.14%   |
| Dell                            | 2         | 1.14%   |
| TP-Link                         | 1         | 0.57%   |
| Ralink                          | 1         | 0.57%   |
| Foxconn International           | 1         | 0.57%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 21.71%  |
| Realtek Bluetooth Radio                             | 12        | 6.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 6.29%   |
| Intel Bluetooth Device                              | 9         | 5.14%   |
| Intel AX201 Bluetooth                               | 9         | 5.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 4.57%   |
| Intel AX200 Bluetooth                               | 7         | 4%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 3.43%   |
| MediaTek Wireless_Device                            | 5         | 2.86%   |
| Intel AX210 Bluetooth                               | 5         | 2.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.29%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 2.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 2.29%   |
| Apple Bluetooth USB Host Controller                 | 4         | 2.29%   |
| Apple Bluetooth Host Controller                     | 4         | 2.29%   |
| IMC Networks Wireless_Device                        | 3         | 1.71%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.71%   |
| Realtek Bluetooth Radio                             | 2         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.14%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.14%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.57%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.57%   |
| Ralink CSR BS8510                                   | 1         | 0.57%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.57%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.57%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.57%   |
| IMC Networks Bluetooth Device                       | 1         | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.57%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.57%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 194       | 41.45%  |
| AMD                                  | 92        | 19.66%  |
| Nvidia                               | 86        | 18.38%  |
| C-Media Electronics                  | 8         | 1.71%   |
| Focusrite-Novation                   | 6         | 1.28%   |
| Yamaha                               | 5         | 1.07%   |
| Texas Instruments                    | 5         | 1.07%   |
| PreSonus Audio Electronics           | 4         | 0.85%   |
| M-Audio                              | 4         | 0.85%   |
| Logitech                             | 4         | 0.85%   |
| JMTek                                | 4         | 0.85%   |
| ASUSTek Computer                     | 4         | 0.85%   |
| Plantronics                          | 3         | 0.64%   |
| Mackie Designs                       | 3         | 0.64%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.43%   |
| QinHeng Electronics                  | 2         | 0.43%   |
| Mark of the Unicorn                  | 2         | 0.43%   |
| Generalplus Technology               | 2         | 0.43%   |
| Creative Technology                  | 2         | 0.43%   |
| BEHRINGER International              | 2         | 0.43%   |
| ZOOM                                 | 1         | 0.21%   |
| Yealink Network Technology           | 1         | 0.21%   |
| Xilinx                               | 1         | 0.21%   |
| Unknown                              | 1         | 0.21%   |
| Universal Audio                      | 1         | 0.21%   |
| Thomann                              | 1         | 0.21%   |
| Textech International                | 1         | 0.21%   |
| Tenx Technology                      | 1         | 0.21%   |
| TEAC                                 | 1         | 0.21%   |
| Studiologic                          | 1         | 0.21%   |
| SteelSeries ApS                      | 1         | 0.21%   |
| Samson Technologies                  | 1         | 0.21%   |
| Realtek Semiconductor                | 1         | 0.21%   |
| Razer USA                            | 1         | 0.21%   |
| NXP Semiconductors                   | 1         | 0.21%   |
| MIDITECH                             | 1         | 0.21%   |
| Medeli Electronics                   | 1         | 0.21%   |
| Lenovo                               | 1         | 0.21%   |
| KTMicro                              | 1         | 0.21%   |
| Jieli Technology                     | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                     | 31        | 5.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 19        | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 18        | 3.25%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                       | 18        | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                        | 16        | 2.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 16        | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 13        | 2.35%   |
| Intel Sunrise Point-LP HD Audio                                                   | 13        | 2.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 13        | 2.35%   |
| AMD Starship/Matisse HD Audio Controller                                          | 13        | 2.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 10        | 1.81%   |
| Intel Broadwell-U Audio Controller                                                | 10        | 1.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 10        | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 10        | 1.81%   |
| AMD FCH Azalia Controller                                                         | 10        | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 8         | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 8         | 1.45%   |
| Intel 8 Series HD Audio Controller                                                | 7         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 7         | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 7         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 1.08%   |
| Intel Haswell-ULT HD Audio Controller                                             | 6         | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 6         | 1.08%   |
| Intel 200 Series PCH HD Audio                                                     | 6         | 1.08%   |
| Nvidia GP108 High Definition Audio Controller                                     | 5         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                                     | 5         | 0.9%    |
| Nvidia GA106 High Definition Audio Controller                                     | 5         | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                                     | 5         | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                         | 5         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                         | 5         | 0.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 5         | 0.9%    |
| AMD Radeon High Definition Audio Controller                                       | 5         | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 4         | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4         | 0.72%   |
| Intel Raptor Lake High Definition Audio Controller                                | 4         | 0.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 4         | 0.72%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 4         | 0.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 76        | 22.96%  |
| SK hynix            | 66        | 19.94%  |
| Kingston            | 37        | 11.18%  |
| Micron Technology   | 33        | 9.97%   |
| Unknown             | 24        | 7.25%   |
| Crucial             | 19        | 5.74%   |
| Corsair             | 17        | 5.14%   |
| G.Skill             | 14        | 4.23%   |
| Patriot             | 6         | 1.81%   |
| Ramaxel Technology  | 5         | 1.51%   |
| A-DATA Technology   | 5         | 1.51%   |
| Nanya Technology    | 4         | 1.21%   |
| Unknown             | 4         | 1.21%   |
| Elpida              | 3         | 0.91%   |
| Transcend           | 2         | 0.6%    |
| Timetec             | 2         | 0.6%    |
| Wodposit            | 1         | 0.3%    |
| Unifosa             | 1         | 0.3%    |
| Smart               | 1         | 0.3%    |
| S                   | 1         | 0.3%    |
| PNY                 | 1         | 0.3%    |
| OCZ                 | 1         | 0.3%    |
| M                   | 1         | 0.3%    |
| HBS                 | 1         | 0.3%    |
| Goldkey             | 1         | 0.3%    |
| CSX                 | 1         | 0.3%    |
| Avant               | 1         | 0.3%    |
| Apacer              | 1         | 0.3%    |
| Aeneon              | 1         | 0.3%    |
| 0194808980CE        | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 6         | 1.67%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s            | 4         | 1.11%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 4         | 1.11%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s   | 4         | 1.11%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s    | 4         | 1.11%   |
| Unknown                                                 | 4         | 1.11%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s  | 3         | 0.83%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s | 3         | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 3         | 0.83%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s       | 3         | 0.83%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s   | 3         | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 3         | 0.83%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3              | 3         | 0.83%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3600MT/s      | 3         | 0.83%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s    | 3         | 0.83%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                 | 2         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 2         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                | 2         | 0.56%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1600MT/s    | 2         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 2         | 0.56%   |
| SK hynix RAM HMCG88AGBSA095N 32GB SODIMM DDR5 5600MT/s  | 2         | 0.56%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s  | 2         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s  | 2         | 0.56%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s             | 2         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 2133MT/s            | 2         | 0.56%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s   | 2         | 0.56%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s  | 2         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 2         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s   | 2         | 0.56%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s  | 2         | 0.56%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s  | 2         | 0.56%   |
| Patriot RAM 2400 C15 Series 8GB SODIMM DDR4 2667MT/s    | 2         | 0.56%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 2         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s   | 2         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s    | 2         | 0.56%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s   | 2         | 0.56%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s  | 2         | 0.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 2         | 0.56%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2667MT/s  | 1         | 0.28%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                    | 1         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 121       | 42.76%  |
| DDR3    | 108       | 38.16%  |
| DDR2    | 16        | 5.65%   |
| DDR5    | 9         | 3.18%   |
| Unknown | 8         | 2.83%   |
| SDRAM   | 7         | 2.47%   |
| LPDDR5  | 5         | 1.77%   |
| LPDDR4  | 4         | 1.41%   |
| DDR     | 3         | 1.06%   |
| LPDDR3  | 2         | 0.71%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 148       | 52.86%  |
| DIMM         | 111       | 39.64%  |
| Row Of Chips | 15        | 5.36%   |
| Chip         | 2         | 0.71%   |
| Unknown      | 2         | 0.71%   |
| RIMM         | 1         | 0.36%   |
| FB-DIMM      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 116       | 36.59%  |
| 4096  | 92        | 29.02%  |
| 16384 | 43        | 13.56%  |
| 2048  | 31        | 9.78%   |
| 32768 | 20        | 6.31%   |
| 1024  | 11        | 3.47%   |
| 512   | 2         | 0.63%   |
| 65536 | 1         | 0.32%   |
| 256   | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 73        | 23.86%  |
| 3200    | 36        | 11.76%  |
| 2667    | 34        | 11.11%  |
| 2400    | 21        | 6.86%   |
| 1333    | 18        | 5.88%   |
| 2133    | 17        | 5.56%   |
| 3600    | 13        | 4.25%   |
| 667     | 8         | 2.61%   |
| 1334    | 7         | 2.29%   |
| 5600    | 6         | 1.96%   |
| 1866    | 6         | 1.96%   |
| 1800    | 6         | 1.96%   |
| 800     | 6         | 1.96%   |
| Unknown | 6         | 1.96%   |
| 6400    | 4         | 1.31%   |
| 1066    | 4         | 1.31%   |
| 4267    | 3         | 0.98%   |
| 2933    | 3         | 0.98%   |
| 2666    | 3         | 0.98%   |
| 1867    | 3         | 0.98%   |
| 1067    | 3         | 0.98%   |
| 4199    | 2         | 0.65%   |
| 3733    | 2         | 0.65%   |
| 3400    | 2         | 0.65%   |
| 3266    | 2         | 0.65%   |
| 533     | 2         | 0.65%   |
| 8533    | 1         | 0.33%   |
| 7200    | 1         | 0.33%   |
| 4802    | 1         | 0.33%   |
| 4800    | 1         | 0.33%   |
| 3866    | 1         | 0.33%   |
| 3800    | 1         | 0.33%   |
| 3500    | 1         | 0.33%   |
| 3467    | 1         | 0.33%   |
| 3466    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2934    | 1         | 0.33%   |
| 2800    | 1         | 0.33%   |
| 2465    | 1         | 0.33%   |
| 1639    | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 2         | 33.33%  |
| Ricoh           | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                 | Computers | Percent |
|-----------------------|-----------|---------|
| Canon LiDE 400        | 2         | 33.33%  |
| Ricoh Aficio SP 100SU | 1         | 16.67%  |
| HP OfficeJet Pro 6960 | 1         | 16.67%  |
| HP OfficeJet 6950     | 1         | 16.67%  |
| HP LaserJet 1022      | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LiDE 60 | 1         | 33.33%  |
| Canon CanoScan FB630U  | 1         | 33.33%  |
| Canon CanoScan 4200F   | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 17.06%  |
| Realtek Semiconductor                  | 12        | 7.06%   |
| IMC Networks                           | 12        | 7.06%   |
| Logitech                               | 11        | 6.47%   |
| Microdia                               | 10        | 5.88%   |
| Bison Electronics                      | 9         | 5.29%   |
| Syntek                                 | 8         | 4.71%   |
| Apple                                  | 8         | 4.71%   |
| Suyin                                  | 7         | 4.12%   |
| Sunplus Innovation Technology          | 7         | 4.12%   |
| Lite-On Technology                     | 6         | 3.53%   |
| Quanta                                 | 5         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.35%   |
| Sonix Technology                       | 3         | 1.76%   |
| Microsoft                              | 3         | 1.76%   |
| Luxvisions Innotech Limited            | 3         | 1.76%   |
| Xiongmai                               | 2         | 1.18%   |
| Silicon Motion                         | 2         | 1.18%   |
| Samsung Electronics                    | 2         | 1.18%   |
| Ricoh                                  | 2         | 1.18%   |
| Philips (or NXP)                       | 2         | 1.18%   |
| Intel                                  | 2         | 1.18%   |
| Generalplus Technology                 | 2         | 1.18%   |
| Dell                                   | 2         | 1.18%   |
| ViewSonic                              | 1         | 0.59%   |
| ViewQuest Technologies                 | 1         | 0.59%   |
| Trust                                  | 1         | 0.59%   |
| Sweex                                  | 1         | 0.59%   |
| Sunplus IT                             | 1         | 0.59%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.59%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.59%   |
| Razer USA                              | 1         | 0.59%   |
| OmniVision Technologies                | 1         | 0.59%   |
| MacroSilicon                           | 1         | 0.59%   |
| Jieli Technology                       | 1         | 0.59%   |
| Importek                               | 1         | 0.59%   |
| Huawei Technologies                    | 1         | 0.59%   |
| HRY                                    | 1         | 0.59%   |
| Elgato Systems                         | 1         | 0.59%   |
| Dynex                                  | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 7         | 4.09%   |
| Chicony integrated camera                           | 7         | 4.09%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 2.92%   |
| Bison Integrated Camera                             | 5         | 2.92%   |
| IMC Networks Integrated Camera                      | 4         | 2.34%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 2.34%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.75%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.75%   |
| Realtek Lenovo EasyCamera                           | 3         | 1.75%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.75%   |
| Logitech Webcam C270                                | 3         | 1.75%   |
| Lite-On Integrated Camera                           | 3         | 1.75%   |
| Chicony Integrated Camera [ThinkPad]                | 3         | 1.75%   |
| Chicony HD Webcam                                   | 3         | 1.75%   |
| Chicony HD User Facing                              | 3         | 1.75%   |
| Xiongmai web camera                                 | 2         | 1.17%   |
| Suyin USB 2.0 Camera                                | 2         | 1.17%   |
| Suyin Asus Integrated Webcam                        | 2         | 1.17%   |
| Sunplus HD WebCam                                   | 2         | 1.17%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 1.17%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.17%   |
| Lite-On HP HD Webcam                                | 2         | 1.17%   |
| Intel RealSense 3D Camera (Front F200)              | 2         | 1.17%   |
| Chicony HP HD Camera                                | 2         | 1.17%   |
| Chicony ACER HD User Facing                         | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.17%   |
| Apple FaceTime HD Camera                            | 2         | 1.17%   |
| Apple Built-in iSight                               | 2         | 1.17%   |
| ViewSonic PC Camera                                 | 1         | 0.58%   |
| ViewQuest Ability GABB Webcam                       | 1         | 0.58%   |
| Trust Canyon CNS-CWC6 Webcam                        | 1         | 0.58%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.58%   |
| Sweex USB keyboard                                  | 1         | 0.58%   |
| Suyin HP Webcam                                     | 1         | 0.58%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.58%   |
| Suyin HP TrueVision HD                              | 1         | 0.58%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                  | 1         | 0.58%   |
| Sunplus Full HD webcam                              | 1         | 0.58%   |
| Sunplus Dell HD Webcam                              | 1         | 0.58%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 48.15%  |
| Synaptics                  | 5         | 18.52%  |
| Shenzhen Goodix Technology | 4         | 14.81%  |
| LighTuning Technology      | 2         | 7.41%   |
| Samsung Electronics        | 1         | 3.7%    |
| Focal-systems.Corp         | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor      | 4         | 14.81%  |
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 2         | 7.41%   |
| Validity Sensors Fingerprint scanner              | 2         | 7.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 7.41%   |
| Shenzhen Goodix  Fingerprint Device               | 2         | 7.41%   |
| Shenzhen Goodix Fingerprint Reader                | 2         | 7.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 2         | 7.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 3.7%    |
| Validity Sensors VFS301 Fingerprint Reader        | 1         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 3.7%    |
| Synaptics Prometheus Fingerprint Reader           | 1         | 3.7%    |
| Synaptics Fingerprint reader [HP G6]              | 1         | 3.7%    |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 3.7%    |
| Focal-systems.Corp FT9201Fingerprint.             | 1         | 3.7%    |
| AuthenTec AES2501 Fingerprint Sensor              | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 5         | 41.67%  |
| Upek                | 3         | 25%     |
| Alcor Micro         | 2         | 16.67%  |
| Lenovo              | 1         | 8.33%   |
| Chicony Electronics | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 199       | 71.58%  |
| 1     | 68        | 24.46%  |
| 2     | 10        | 3.6%    |
| 3     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 31.03%  |
| Graphics card            | 16        | 18.39%  |
| Net/wireless             | 13        | 14.94%  |
| Chipcard                 | 10        | 11.49%  |
| Multimedia controller    | 5         | 5.75%   |
| Camera                   | 3         | 3.45%   |
| Unassigned class         | 2         | 2.3%    |
| Sound                    | 2         | 2.3%    |
| Communication controller | 2         | 2.3%    |
| Card reader              | 2         | 2.3%    |
| Storage/raid             | 1         | 1.15%   |
| Storage                  | 1         | 1.15%   |
| Net/ethernet             | 1         | 1.15%   |
| Modem                    | 1         | 1.15%   |
| Bluetooth                | 1         | 1.15%   |

